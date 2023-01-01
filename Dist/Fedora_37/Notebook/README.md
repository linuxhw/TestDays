Fedora 37 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 592

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X390 20Q00051GE    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Valve         | Jupiter                     | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| System76      | Oryx Pro                    | [0d65e57758](https://linux-hardware.org/?probe=0d65e57758) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [591d985e85](https://linux-hardware.org/?probe=591d985e85) | Dec 31, 2022 |
| HP            | Pavilion dv6700             | [4b3b106bee](https://linux-hardware.org/?probe=4b3b106bee) | Dec 30, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [f7ed4a6609](https://linux-hardware.org/?probe=f7ed4a6609) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [d2cd50a2a6](https://linux-hardware.org/?probe=d2cd50a2a6) | Dec 30, 2022 |
| Timi          | A35S                        | [c62c9ae956](https://linux-hardware.org/?probe=c62c9ae956) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [ae7d821823](https://linux-hardware.org/?probe=ae7d821823) | Dec 30, 2022 |
| Dell          | XPS 15 9520                 | [19b4bfd852](https://linux-hardware.org/?probe=19b4bfd852) | Dec 30, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| Dell          | Inspiron N4050              | [b34f09894d](https://linux-hardware.org/?probe=b34f09894d) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [3c627bc707](https://linux-hardware.org/?probe=3c627bc707) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [b246257695](https://linux-hardware.org/?probe=b246257695) | Dec 29, 2022 |
| HP            | Stream Notebook PC 13       | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6c67e1435e](https://linux-hardware.org/?probe=6c67e1435e) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | [51bb19bbf2](https://linux-hardware.org/?probe=51bb19bbf2) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [bbd6e1daf5](https://linux-hardware.org/?probe=bbd6e1daf5) | Dec 29, 2022 |
| Acer          | Predator PH315-53           | [d5d0e740c1](https://linux-hardware.org/?probe=d5d0e740c1) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [2412713729](https://linux-hardware.org/?probe=2412713729) | Dec 29, 2022 |
| Dell          | G5 5590                     | [58bd69f40b](https://linux-hardware.org/?probe=58bd69f40b) | Dec 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [8901206dd0](https://linux-hardware.org/?probe=8901206dd0) | Dec 28, 2022 |
| Dell          | Inspiron 5458               | [269d455191](https://linux-hardware.org/?probe=269d455191) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [e23c23e61f](https://linux-hardware.org/?probe=e23c23e61f) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [5c4856e5c8](https://linux-hardware.org/?probe=5c4856e5c8) | Dec 28, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | [0852995abb](https://linux-hardware.org/?probe=0852995abb) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Google        | Voxel rev3                  | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| Dell          | Inspiron 16 5625            | [dbc2d2fc6f](https://linux-hardware.org/?probe=dbc2d2fc6f) | Dec 28, 2022 |
| HUAWEI        | HLYL-WXX9                   | [790b3dcdde](https://linux-hardware.org/?probe=790b3dcdde) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| HP            | G62                         | [05ad917600](https://linux-hardware.org/?probe=05ad917600) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| HUAWEI        | BOM-WXX9                    | [826a683b58](https://linux-hardware.org/?probe=826a683b58) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| MSI           | GL63 8RC                    | [0b973e252f](https://linux-hardware.org/?probe=0b973e252f) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| HP            | Laptop 15-dy5xxx            | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| Timi          | RedmiBook 15                | [cf38b14bc5](https://linux-hardware.org/?probe=cf38b14bc5) | Dec 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e41c8ca4ee](https://linux-hardware.org/?probe=e41c8ca4ee) | Dec 27, 2022 |
| Dell          | Latitude E7440              | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Dell          | Inspiron 15-3567            | [2f5381fa26](https://linux-hardware.org/?probe=2f5381fa26) | Dec 26, 2022 |
| HP            | ProBook 450 G7              | [dfedb566ff](https://linux-hardware.org/?probe=dfedb566ff) | Dec 26, 2022 |
| Lenovo        | G510 20238                  | [812d6eb07e](https://linux-hardware.org/?probe=812d6eb07e) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| Dell          | Inspiron 3521               | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| Dell          | Inspiron 5458               | [4e393c7334](https://linux-hardware.org/?probe=4e393c7334) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [ce352bf1b1](https://linux-hardware.org/?probe=ce352bf1b1) | Dec 26, 2022 |
| Acer          | Aspire A515-51              | [e763dd5dfe](https://linux-hardware.org/?probe=e763dd5dfe) | Dec 26, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Dell          | Inspiron 5759               | [d1938219e9](https://linux-hardware.org/?probe=d1938219e9) | Dec 26, 2022 |
| Dell          | Latitude 5580               | [72c0e42aeb](https://linux-hardware.org/?probe=72c0e42aeb) | Dec 26, 2022 |
| Acer          | Aspire A315-59              | [6625ce058f](https://linux-hardware.org/?probe=6625ce058f) | Dec 25, 2022 |
| HP            | ProBook 6465b               | [d0f5218f72](https://linux-hardware.org/?probe=d0f5218f72) | Dec 25, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| Dell          | XPS 15 9510                 | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| Dell          | Latitude 5510               | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| HUAWEI        | CREM-WXX9                   | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| HP            | Pavilion g6                 | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| Acer          | Aspire A514-54              | [ea57f4aa3a](https://linux-hardware.org/?probe=ea57f4aa3a) | Dec 24, 2022 |
| Dell          | Latitude 5420               | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Dell          | Latitude 5420               | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| ASUSTek       | X750JN                      | [d933b1a80b](https://linux-hardware.org/?probe=d933b1a80b) | Dec 23, 2022 |
| Jooyon Tec... | J6BF                        | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [627186e9e8](https://linux-hardware.org/?probe=627186e9e8) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Acer          | Aspire A515-57G             | [a208b5598e](https://linux-hardware.org/?probe=a208b5598e) | Dec 22, 2022 |
| Acer          | Aspire A515-57G             | [cccd3d01d7](https://linux-hardware.org/?probe=cccd3d01d7) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [677cb5b0b3](https://linux-hardware.org/?probe=677cb5b0b3) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| GPD           | P3 MAX                      | [9069ed5580](https://linux-hardware.org/?probe=9069ed5580) | Dec 22, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [6db25ba5ca](https://linux-hardware.org/?probe=6db25ba5ca) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fb60e7984c](https://linux-hardware.org/?probe=fb60e7984c) | Dec 21, 2022 |
| ASUSTek       | X450CA                      | [5b793f14ff](https://linux-hardware.org/?probe=5b793f14ff) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| Apple         | MacBookPro9,2               | [5bc62fc208](https://linux-hardware.org/?probe=5bc62fc208) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HP            | Stream Notebook PC 13       | [9c88ffc394](https://linux-hardware.org/?probe=9c88ffc394) | Dec 21, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [77c9275988](https://linux-hardware.org/?probe=77c9275988) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| Dell          | Latitude 5520               | [203652b6dd](https://linux-hardware.org/?probe=203652b6dd) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [1f1c718c61](https://linux-hardware.org/?probe=1f1c718c61) | Dec 21, 2022 |
| Timi          | Mi NoteBook Pro             | [b5bbb4f410](https://linux-hardware.org/?probe=b5bbb4f410) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| Dell          | Latitude 3420               | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| HP            | ZBook 15                    | [a3bf671d64](https://linux-hardware.org/?probe=a3bf671d64) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Dell          | Vostro 5620                 | [005d388376](https://linux-hardware.org/?probe=005d388376) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [bbfea042cd](https://linux-hardware.org/?probe=bbfea042cd) | Dec 20, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [011d3e746d](https://linux-hardware.org/?probe=011d3e746d) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [b30bf77d27](https://linux-hardware.org/?probe=b30bf77d27) | Dec 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [c67b4d2b31](https://linux-hardware.org/?probe=c67b4d2b31) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Sony          | SVE15133CNB                 | [a2bee3bb3f](https://linux-hardware.org/?probe=a2bee3bb3f) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [714d2a6dea](https://linux-hardware.org/?probe=714d2a6dea) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a5a207a46d](https://linux-hardware.org/?probe=a5a207a46d) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| Acer          | Swift SF114-32              | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [23b255ed61](https://linux-hardware.org/?probe=23b255ed61) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| Acer          | Aspire A315-31              | [e391c56a47](https://linux-hardware.org/?probe=e391c56a47) | Dec 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PG... | [938c10075a](https://linux-hardware.org/?probe=938c10075a) | Dec 18, 2022 |
| HP            | Laptop 15-da0xxx            | [b712a7bd77](https://linux-hardware.org/?probe=b712a7bd77) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| HP            | ProBook 450 G7              | [ad9bf6b390](https://linux-hardware.org/?probe=ad9bf6b390) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c9cc617e08](https://linux-hardware.org/?probe=c9cc617e08) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [f047451b08](https://linux-hardware.org/?probe=f047451b08) | Dec 17, 2022 |
| Sony          | SVE15133CNB                 | [acca7c4697](https://linux-hardware.org/?probe=acca7c4697) | Dec 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [49969f1b81](https://linux-hardware.org/?probe=49969f1b81) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [a481e4a590](https://linux-hardware.org/?probe=a481e4a590) | Dec 17, 2022 |
| GPD           | P2 MAX                      | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| ASUSTek       | X45C                        | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 3583               | [5629961182](https://linux-hardware.org/?probe=5629961182) | Dec 17, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [5ab1c3b848](https://linux-hardware.org/?probe=5ab1c3b848) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [645e7245d4](https://linux-hardware.org/?probe=645e7245d4) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [2ba98da01d](https://linux-hardware.org/?probe=2ba98da01d) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a767e0fbf0](https://linux-hardware.org/?probe=a767e0fbf0) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| Dell          | Vostro 5590                 | [3735674d3f](https://linux-hardware.org/?probe=3735674d3f) | Dec 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| Dell          | Inspiron 5566               | [ccfc358303](https://linux-hardware.org/?probe=ccfc358303) | Dec 16, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Lenovo        | ThinkPad W530 243858U       | [9dc4fb1abb](https://linux-hardware.org/?probe=9dc4fb1abb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [955de558cb](https://linux-hardware.org/?probe=955de558cb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [e1d8403247](https://linux-hardware.org/?probe=e1d8403247) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Dell          | Inspiron 7501               | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [b8cc280665](https://linux-hardware.org/?probe=b8cc280665) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1dd0f2a71f](https://linux-hardware.org/?probe=1dd0f2a71f) | Dec 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [85c38f0af3](https://linux-hardware.org/?probe=85c38f0af3) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [1380e253a5](https://linux-hardware.org/?probe=1380e253a5) | Dec 14, 2022 |
| Samsung       | 750XDA                      | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Dell          | Inspiron 3583               | [70992b154e](https://linux-hardware.org/?probe=70992b154e) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [44484456f8](https://linux-hardware.org/?probe=44484456f8) | Dec 14, 2022 |
| HP            | Laptop 14-fq1xxx            | [2da9ae7906](https://linux-hardware.org/?probe=2da9ae7906) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [034b34f6d6](https://linux-hardware.org/?probe=034b34f6d6) | Dec 13, 2022 |
| Pegatron      | C17A                        | [adde308568](https://linux-hardware.org/?probe=adde308568) | Dec 13, 2022 |
| HP            | Laptop 14-fq1xxx            | [ed92313ebc](https://linux-hardware.org/?probe=ed92313ebc) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| Acer          | Predator G9-591             | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Dell          | Inspiron 13-5368            | [952dd9d819](https://linux-hardware.org/?probe=952dd9d819) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| Dell          | Inspiron 7380               | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| HP            | ProBook 6570b               | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [9fb659eea3](https://linux-hardware.org/?probe=9fb659eea3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| MSI           | Modern 14 B11MOU            | [9739ffdf34](https://linux-hardware.org/?probe=9739ffdf34) | Dec 12, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| Toshiba       | Satellite A300              | [211e44e5d2](https://linux-hardware.org/?probe=211e44e5d2) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire E5-576G              | [9cc371883c](https://linux-hardware.org/?probe=9cc371883c) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| Notebook      | WA50SRQ                     | [da74211ac6](https://linux-hardware.org/?probe=da74211ac6) | Dec 11, 2022 |
| HP            | Pavilion g6                 | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| MSI           | Prestige 15 A11SCX          | [5941b1aed7](https://linux-hardware.org/?probe=5941b1aed7) | Dec 10, 2022 |
| MSI           | Prestige 15 A11SCX          | [ab1334fca2](https://linux-hardware.org/?probe=ab1334fca2) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [e80dfca4a8](https://linux-hardware.org/?probe=e80dfca4a8) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [72f0e70b26](https://linux-hardware.org/?probe=72f0e70b26) | Dec 10, 2022 |
| Pegatron      | C17A                        | [2437a88730](https://linux-hardware.org/?probe=2437a88730) | Dec 09, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Schenker      | VIA 15                      | [25883b06a1](https://linux-hardware.org/?probe=25883b06a1) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| HP            | 245 G8 Notebook PC          | [c291bac936](https://linux-hardware.org/?probe=c291bac936) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Aspire E1-572G              | [2dabd7cf91](https://linux-hardware.org/?probe=2dabd7cf91) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Acer          | Aspire E1-572G              | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | MACH-WX9                    | [5ed19862a7](https://linux-hardware.org/?probe=5ed19862a7) | Dec 08, 2022 |
| Dell          | Inspiron 5566               | [dcf5539e74](https://linux-hardware.org/?probe=dcf5539e74) | Dec 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [00995baaae](https://linux-hardware.org/?probe=00995baaae) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| Dell          | XPS 13 9350                 | [9779817777](https://linux-hardware.org/?probe=9779817777) | Dec 07, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [efe4d93e2d](https://linux-hardware.org/?probe=efe4d93e2d) | Dec 07, 2022 |
| Acer          | Aspire E5-571               | [d5d013b642](https://linux-hardware.org/?probe=d5d013b642) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Dell          | Latitude E6420              | [e87ced9ea4](https://linux-hardware.org/?probe=e87ced9ea4) | Dec 06, 2022 |
| Dell          | Latitude E6420              | [17c9263444](https://linux-hardware.org/?probe=17c9263444) | Dec 06, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [a3b78e7093](https://linux-hardware.org/?probe=a3b78e7093) | Dec 06, 2022 |
| Acer          | Predator G9-591             | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Acer          | Aspire E5-571               | [e9d00a798c](https://linux-hardware.org/?probe=e9d00a798c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| BANGHO        | BES T5                      | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| HP            | Laptop 14-fq1xxx            | [4f93d8895e](https://linux-hardware.org/?probe=4f93d8895e) | Dec 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [12e33b1925](https://linux-hardware.org/?probe=12e33b1925) | Dec 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| ASUSTek       | X510UNR                     | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [9b87c97ed5](https://linux-hardware.org/?probe=9b87c97ed5) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [fe17634e66](https://linux-hardware.org/?probe=fe17634e66) | Dec 05, 2022 |
| Dell          | Inspiron 13-7378            | [b628250da9](https://linux-hardware.org/?probe=b628250da9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| Sony          | SVE15133CNB                 | [16f43f11a1](https://linux-hardware.org/?probe=16f43f11a1) | Dec 04, 2022 |
| Dell          | Inspiron 5459               | [9b714617c8](https://linux-hardware.org/?probe=9b714617c8) | Dec 04, 2022 |
| Apple         | MacBookPro8,1               | [29fa28c3f1](https://linux-hardware.org/?probe=29fa28c3f1) | Dec 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [076685806a](https://linux-hardware.org/?probe=076685806a) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Dell          | Inspiron 5566               | [fb9c1854a2](https://linux-hardware.org/?probe=fb9c1854a2) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [937053920b](https://linux-hardware.org/?probe=937053920b) | Dec 04, 2022 |
| Acer          | Aspire A515-45              | [48d98f5da4](https://linux-hardware.org/?probe=48d98f5da4) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f93dd5ad2d](https://linux-hardware.org/?probe=f93dd5ad2d) | Dec 03, 2022 |
| Apple         | MacBookPro9,2               | [eadd4cd3e1](https://linux-hardware.org/?probe=eadd4cd3e1) | Dec 03, 2022 |
| Pegatron      | A15W8                       | [f33c1aea21](https://linux-hardware.org/?probe=f33c1aea21) | Dec 03, 2022 |
| HP            | Laptop 15s-fr2xxx           | [623e794238](https://linux-hardware.org/?probe=623e794238) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| MSI           | Modern 14 B4MW              | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [d64c6bc6f4](https://linux-hardware.org/?probe=d64c6bc6f4) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [a9f812a233](https://linux-hardware.org/?probe=a9f812a233) | Dec 03, 2022 |
| Acer          | Aspire A715-51G             | [65aa3f7e69](https://linux-hardware.org/?probe=65aa3f7e69) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | XPS 13 9350                 | [38c002d686](https://linux-hardware.org/?probe=38c002d686) | Dec 02, 2022 |
| Google        | Lick                        | [a03c415d36](https://linux-hardware.org/?probe=a03c415d36) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dc80fd6907](https://linux-hardware.org/?probe=dc80fd6907) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [be8f757095](https://linux-hardware.org/?probe=be8f757095) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [1e40d6a94b](https://linux-hardware.org/?probe=1e40d6a94b) | Dec 02, 2022 |
| HP            | Pavilion Laptop 14-bk0xx    | [57c3eeaf3d](https://linux-hardware.org/?probe=57c3eeaf3d) | Dec 02, 2022 |
| Acer          | Aspire A515-45              | [495abda40a](https://linux-hardware.org/?probe=495abda40a) | Dec 02, 2022 |
| Sony          | VPCEB1M1E                   | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [2397eee427](https://linux-hardware.org/?probe=2397eee427) | Dec 01, 2022 |
| Google        | Kasumi                      | [d67591d35c](https://linux-hardware.org/?probe=d67591d35c) | Dec 01, 2022 |
| Acer          | Iconia W4-820               | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [4ab89a8ad2](https://linux-hardware.org/?probe=4ab89a8ad2) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [de34f148b9](https://linux-hardware.org/?probe=de34f148b9) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [0128a48982](https://linux-hardware.org/?probe=0128a48982) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [f0ee9f78bd](https://linux-hardware.org/?probe=f0ee9f78bd) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [2df1670891](https://linux-hardware.org/?probe=2df1670891) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Notebook                    | [afac08b852](https://linux-hardware.org/?probe=afac08b852) | Nov 30, 2022 |
| Dell          | Inspiron 3580               | [6bc2705d99](https://linux-hardware.org/?probe=6bc2705d99) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S01Q3K    | [9fd6308179](https://linux-hardware.org/?probe=9fd6308179) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [38c4009dba](https://linux-hardware.org/?probe=38c4009dba) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Lenovo        | ThinkPad E550 20DF004RGE    | [a06fd97ee3](https://linux-hardware.org/?probe=a06fd97ee3) | Nov 29, 2022 |
| ASUSTek       | X756UXK                     | [a8fde1c59a](https://linux-hardware.org/?probe=a8fde1c59a) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Dell          | Latitude D620               | [9f6317405c](https://linux-hardware.org/?probe=9f6317405c) | Nov 29, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [bb023e130b](https://linux-hardware.org/?probe=bb023e130b) | Nov 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [fd821a4b54](https://linux-hardware.org/?probe=fd821a4b54) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Dell          | Latitude 7480               | [409c2f27c8](https://linux-hardware.org/?probe=409c2f27c8) | Nov 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [e1495dc120](https://linux-hardware.org/?probe=e1495dc120) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [901fa6e871](https://linux-hardware.org/?probe=901fa6e871) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [86f58e68b6](https://linux-hardware.org/?probe=86f58e68b6) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Unknown       | Unknown                     | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| HP            | Laptop 15-da1xxx            | [8c4cae32db](https://linux-hardware.org/?probe=8c4cae32db) | Nov 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [bdc1a14cd4](https://linux-hardware.org/?probe=bdc1a14cd4) | Nov 27, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [26083dd909](https://linux-hardware.org/?probe=26083dd909) | Nov 27, 2022 |
| ASUSTek       | N53Jf                       | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| AVITA         | NS14A6                      | [b9cc8fe757](https://linux-hardware.org/?probe=b9cc8fe757) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [dc561bb107](https://linux-hardware.org/?probe=dc561bb107) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [336d829333](https://linux-hardware.org/?probe=336d829333) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [74fcf5cb22](https://linux-hardware.org/?probe=74fcf5cb22) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a4dbfc0da9](https://linux-hardware.org/?probe=a4dbfc0da9) | Nov 26, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [15d49eb71a](https://linux-hardware.org/?probe=15d49eb71a) | Nov 26, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [83a97530e1](https://linux-hardware.org/?probe=83a97530e1) | Nov 26, 2022 |
| Google        | Glimmer                     | [8ad30368c9](https://linux-hardware.org/?probe=8ad30368c9) | Nov 26, 2022 |
| GPD           | G1621-02                    | [f0e9e8442c](https://linux-hardware.org/?probe=f0e9e8442c) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d845cbb51d](https://linux-hardware.org/?probe=d845cbb51d) | Nov 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [18130ae317](https://linux-hardware.org/?probe=18130ae317) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [376fc86892](https://linux-hardware.org/?probe=376fc86892) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [f46e1bc341](https://linux-hardware.org/?probe=f46e1bc341) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [682993f58f](https://linux-hardware.org/?probe=682993f58f) | Nov 25, 2022 |
| HP            | Laptop 14-dq1xxx            | [1e6fa19cc3](https://linux-hardware.org/?probe=1e6fa19cc3) | Nov 25, 2022 |
| Acer          | Nitro AN515-54              | [9226b4c616](https://linux-hardware.org/?probe=9226b4c616) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| Dell          | Inspiron 5370               | [469b2c3fd4](https://linux-hardware.org/?probe=469b2c3fd4) | Nov 24, 2022 |
| Toshiba       | Satellite S55-A             | [5466c61736](https://linux-hardware.org/?probe=5466c61736) | Nov 24, 2022 |
| ASUSTek       | Q550LF                      | [713f7b2c74](https://linux-hardware.org/?probe=713f7b2c74) | Nov 24, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [1c65fff6e7](https://linux-hardware.org/?probe=1c65fff6e7) | Nov 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d84bc82678](https://linux-hardware.org/?probe=d84bc82678) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5b18e83e0d](https://linux-hardware.org/?probe=5b18e83e0d) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Laptop 15-da0xxx            | [fa989478ad](https://linux-hardware.org/?probe=fa989478ad) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [fbf991818d](https://linux-hardware.org/?probe=fbf991818d) | Nov 23, 2022 |
| Apple         | MacBookPro9,2               | [3e176f0c26](https://linux-hardware.org/?probe=3e176f0c26) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [af778b2ec9](https://linux-hardware.org/?probe=af778b2ec9) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [04187e0d6e](https://linux-hardware.org/?probe=04187e0d6e) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [8a773e7358](https://linux-hardware.org/?probe=8a773e7358) | Nov 22, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [d49ca08585](https://linux-hardware.org/?probe=d49ca08585) | Nov 22, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d48ad61c01](https://linux-hardware.org/?probe=d48ad61c01) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| Acer          | Predator PH315-55           | [f411f75743](https://linux-hardware.org/?probe=f411f75743) | Nov 22, 2022 |
| HP            | Laptop 15-da0xxx            | [aef0888523](https://linux-hardware.org/?probe=aef0888523) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Acer          | Aspire A315-51              | [bcff111ecd](https://linux-hardware.org/?probe=bcff111ecd) | Nov 21, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [bce41d01ae](https://linux-hardware.org/?probe=bce41d01ae) | Nov 21, 2022 |
| Dell          | Latitude D620               | [d45ad40496](https://linux-hardware.org/?probe=d45ad40496) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| Dell          | Inspiron 3505               | [634f7d190d](https://linux-hardware.org/?probe=634f7d190d) | Nov 21, 2022 |
| HP            | ZBook 15 G4                 | [3378343bab](https://linux-hardware.org/?probe=3378343bab) | Nov 21, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [0e9d717db2](https://linux-hardware.org/?probe=0e9d717db2) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [aa4d9601ee](https://linux-hardware.org/?probe=aa4d9601ee) | Nov 21, 2022 |
| MSI           | Stealth GS66 12UGS          | [ca3d88f38d](https://linux-hardware.org/?probe=ca3d88f38d) | Nov 21, 2022 |
| Dell          | Latitude 7420               | [ca5319fd67](https://linux-hardware.org/?probe=ca5319fd67) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [5739045caa](https://linux-hardware.org/?probe=5739045caa) | Nov 20, 2022 |
| HUAWEI        | MACH-WX9                    | [32fa69ea64](https://linux-hardware.org/?probe=32fa69ea64) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | [9f6c38b4ee](https://linux-hardware.org/?probe=9f6c38b4ee) | Nov 20, 2022 |
| Acer          | Aspire A515-45              | [11e00d597d](https://linux-hardware.org/?probe=11e00d597d) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [678cfec38b](https://linux-hardware.org/?probe=678cfec38b) | Nov 20, 2022 |
| MSI           | Katana GF76 11UD            | [1f47d7c31b](https://linux-hardware.org/?probe=1f47d7c31b) | Nov 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | [5ff1608320](https://linux-hardware.org/?probe=5ff1608320) | Nov 19, 2022 |
| Apple         | MacBookPro11,5              | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| Google        | Celes                       | [00ed0ea4b5](https://linux-hardware.org/?probe=00ed0ea4b5) | Nov 19, 2022 |
| Sony          | SVE15133CNB                 | [3d78ceb657](https://linux-hardware.org/?probe=3d78ceb657) | Nov 19, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [bed1f98f04](https://linux-hardware.org/?probe=bed1f98f04) | Nov 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [f9b8181279](https://linux-hardware.org/?probe=f9b8181279) | Nov 19, 2022 |
| Google        | Lick                        | [6d8750d974](https://linux-hardware.org/?probe=6d8750d974) | Nov 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [87d8a1ee6b](https://linux-hardware.org/?probe=87d8a1ee6b) | Nov 19, 2022 |
| ASUSTek       | M80TA                       | [d2427d8942](https://linux-hardware.org/?probe=d2427d8942) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L6S3L400    | [ae98e93989](https://linux-hardware.org/?probe=ae98e93989) | Nov 18, 2022 |
| Google        | Careena                     | [81dd8e9906](https://linux-hardware.org/?probe=81dd8e9906) | Nov 18, 2022 |
| HP            | EliteBook 840 14 inch G9... | [b5d4ff63a5](https://linux-hardware.org/?probe=b5d4ff63a5) | Nov 18, 2022 |
| HP            | Laptop 15-ef1xxx            | [2e47c9c20f](https://linux-hardware.org/?probe=2e47c9c20f) | Nov 18, 2022 |
| Dell          | XPS 13 7390                 | [19d18ac52c](https://linux-hardware.org/?probe=19d18ac52c) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [33113bb27d](https://linux-hardware.org/?probe=33113bb27d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Acer          | Aspire A515-51              | [ee9d0faeef](https://linux-hardware.org/?probe=ee9d0faeef) | Nov 17, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [190c6d9cc7](https://linux-hardware.org/?probe=190c6d9cc7) | Nov 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [450e658685](https://linux-hardware.org/?probe=450e658685) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| Apple         | MacBookPro11,5              | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8b2d48cd24](https://linux-hardware.org/?probe=8b2d48cd24) | Nov 16, 2022 |
| MSI           | Katana GF76 11UD            | [fec345f330](https://linux-hardware.org/?probe=fec345f330) | Nov 16, 2022 |
| GPD           | G1619-04                    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | [03426a19e5](https://linux-hardware.org/?probe=03426a19e5) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e7343719c2](https://linux-hardware.org/?probe=e7343719c2) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [94983688d2](https://linux-hardware.org/?probe=94983688d2) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bafff409d9](https://linux-hardware.org/?probe=bafff409d9) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [1104a26017](https://linux-hardware.org/?probe=1104a26017) | Nov 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [119f9da4af](https://linux-hardware.org/?probe=119f9da4af) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [d2cf28fbb9](https://linux-hardware.org/?probe=d2cf28fbb9) | Nov 15, 2022 |
| Kraftway      | ACCORD                      | [7021cedadf](https://linux-hardware.org/?probe=7021cedadf) | Nov 15, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Lenovo        | ThinkPad L450 20DSS1GD00    | [b0ea02b16c](https://linux-hardware.org/?probe=b0ea02b16c) | Nov 13, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [09285b9428](https://linux-hardware.org/?probe=09285b9428) | Nov 13, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Laptop 15s-eq2xxx           | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0e3e3c885a](https://linux-hardware.org/?probe=0e3e3c885a) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2421b6c5a4](https://linux-hardware.org/?probe=2421b6c5a4) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3bcdc36fff](https://linux-hardware.org/?probe=3bcdc36fff) | Nov 11, 2022 |
| Dell          | Latitude 7480               | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| Dell          | Latitude 7480               | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| Acer          | Nitro AN515-46              | [741209999d](https://linux-hardware.org/?probe=741209999d) | Nov 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [4e535c916f](https://linux-hardware.org/?probe=4e535c916f) | Nov 10, 2022 |
| GPD           | G1619-04                    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [4a6aec2eb8](https://linux-hardware.org/?probe=4a6aec2eb8) | Nov 09, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [a2e9b34d94](https://linux-hardware.org/?probe=a2e9b34d94) | Nov 09, 2022 |
| Acer          | SW5-017                     | [d4ff3ee29e](https://linux-hardware.org/?probe=d4ff3ee29e) | Nov 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1cca3aa247](https://linux-hardware.org/?probe=1cca3aa247) | Nov 08, 2022 |
| Eluktronic... | P670RE3                     | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fc4fb9249e](https://linux-hardware.org/?probe=fc4fb9249e) | Nov 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [f0c2157642](https://linux-hardware.org/?probe=f0c2157642) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [df6426eef5](https://linux-hardware.org/?probe=df6426eef5) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [bae4adcff9](https://linux-hardware.org/?probe=bae4adcff9) | Nov 07, 2022 |
| Dell          | G3 3579                     | [b793526167](https://linux-hardware.org/?probe=b793526167) | Nov 06, 2022 |
| Dell          | Vostro 13 5310              | [c25e192969](https://linux-hardware.org/?probe=c25e192969) | Nov 05, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [a2905cad90](https://linux-hardware.org/?probe=a2905cad90) | Nov 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [80dbecb998](https://linux-hardware.org/?probe=80dbecb998) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| Lenovo        | Unknown                     | [0825807141](https://linux-hardware.org/?probe=0825807141) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9af713ef6e](https://linux-hardware.org/?probe=9af713ef6e) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d87e75abbf](https://linux-hardware.org/?probe=d87e75abbf) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dae32fcba7](https://linux-hardware.org/?probe=dae32fcba7) | Nov 04, 2022 |
| Alienware     | x17 R2                      | [2e25d30db1](https://linux-hardware.org/?probe=2e25d30db1) | Nov 04, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [a2d3502165](https://linux-hardware.org/?probe=a2d3502165) | Nov 04, 2022 |
| UNOWHY        | Y13G011S4EI                 | [da784a5c82](https://linux-hardware.org/?probe=da784a5c82) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [9fbf084c28](https://linux-hardware.org/?probe=9fbf084c28) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18b0671002](https://linux-hardware.org/?probe=18b0671002) | Nov 03, 2022 |
| HUAWEI        | CREM-WXX9                   | [870d04c833](https://linux-hardware.org/?probe=870d04c833) | Nov 03, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [984c379f69](https://linux-hardware.org/?probe=984c379f69) | Nov 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| GPD           | G1619-04                    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [1d24aac4ce](https://linux-hardware.org/?probe=1d24aac4ce) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2eb32b1bb3](https://linux-hardware.org/?probe=2eb32b1bb3) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [566d83485b](https://linux-hardware.org/?probe=566d83485b) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| HP            | ENVY 17                     | [5b845d9ee3](https://linux-hardware.org/?probe=5b845d9ee3) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [073ba962ff](https://linux-hardware.org/?probe=073ba962ff) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Dell          | Latitude 7490               | [95d0006efb](https://linux-hardware.org/?probe=95d0006efb) | Oct 30, 2022 |
| Dell          | XPS 13 9300                 | [cc62dbe2f6](https://linux-hardware.org/?probe=cc62dbe2f6) | Oct 29, 2022 |
| Dell          | XPS 13 9300                 | [301aab9126](https://linux-hardware.org/?probe=301aab9126) | Oct 29, 2022 |
| HP            | ZBook 15 G3                 | [c60b429baa](https://linux-hardware.org/?probe=c60b429baa) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [670823778e](https://linux-hardware.org/?probe=670823778e) | Oct 27, 2022 |
| Dell          | Latitude E7270              | [7f2c8b9e9c](https://linux-hardware.org/?probe=7f2c8b9e9c) | Oct 25, 2022 |
| Dell          | Latitude E7450              | [45e65cd626](https://linux-hardware.org/?probe=45e65cd626) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [dc8eab937b](https://linux-hardware.org/?probe=dc8eab937b) | Oct 24, 2022 |
| HP            | 340S G7 Notebook PC         | [406538a0de](https://linux-hardware.org/?probe=406538a0de) | Oct 23, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [41bade1339](https://linux-hardware.org/?probe=41bade1339) | Oct 21, 2022 |
| LG Electro... | 16Z90P-G.AP75D              | [1e1526e9d8](https://linux-hardware.org/?probe=1e1526e9d8) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| Dell          | Latitude 7420               | [332d2cd420](https://linux-hardware.org/?probe=332d2cd420) | Oct 19, 2022 |
| System76      | Kudu                        | [49c0e1c400](https://linux-hardware.org/?probe=49c0e1c400) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| Dell          | Precision 5510              | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Acer          | Aspire A717-71G             | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [678415db20](https://linux-hardware.org/?probe=678415db20) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2a36feb313](https://linux-hardware.org/?probe=2a36feb313) | Oct 16, 2022 |
| Timi          | TM1701                      | [c2b709ff0c](https://linux-hardware.org/?probe=c2b709ff0c) | Oct 15, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [dbd2328d0f](https://linux-hardware.org/?probe=dbd2328d0f) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3a8bdfb3f5](https://linux-hardware.org/?probe=3a8bdfb3f5) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9b0a923899](https://linux-hardware.org/?probe=9b0a923899) | Oct 13, 2022 |
| Acer          | Aspire A715-71G             | [2b0752150c](https://linux-hardware.org/?probe=2b0752150c) | Oct 12, 2022 |
| HP            | EliteBook 840 G6            | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| HP            | Laptop 15s-eq3xxx           | [2bd986670e](https://linux-hardware.org/?probe=2bd986670e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470s 20HGS09L0... | [7c384e5578](https://linux-hardware.org/?probe=7c384e5578) | Sep 30, 2022 |
| A-DATA Tec... | XENIA 14                    | [251f390772](https://linux-hardware.org/?probe=251f390772) | Sep 30, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| A-DATA Tec... | XENIA 14                    | [e819e5dc14](https://linux-hardware.org/?probe=e819e5dc14) | Sep 29, 2022 |
| HP            | ZBook 15 G3                 | [1d612b997a](https://linux-hardware.org/?probe=1d612b997a) | Sep 29, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [7c62f5131f](https://linux-hardware.org/?probe=7c62f5131f) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Dell          | XPS 13 9380                 | [332540a4c8](https://linux-hardware.org/?probe=332540a4c8) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Irbis         | NB264                       | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Samsung       | 270E5G/270E5U               | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | Laptop 14-dq2xxx            | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                      | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| 6.0.8-300.fc37.x86_64                                        | 54        | 11.84%  |
| 6.0.9-300.fc37.x86_64                                        | 51        | 11.18%  |
| 6.0.12-300.fc37.x86_64                                       | 49        | 10.75%  |
| 6.0.15-300.fc37.x86_64                                       | 40        | 8.77%   |
| 6.0.11-300.fc37.x86_64                                       | 35        | 7.68%   |
| 6.0.10-300.fc37.x86_64                                       | 35        | 7.68%   |
| 6.0.7-301.fc37.x86_64                                        | 28        | 6.14%   |
| 5.19.16-301.fc37.x86_64                                      | 25        | 5.48%   |
| 6.0.14-300.fc37.x86_64                                       | 15        | 3.29%   |
| 6.0.13-300.fc37.x86_64                                       | 13        | 2.85%   |
| 5.19.8-300.fc37.x86_64                                       | 10        | 2.19%   |
| 5.19.7-300.fc37.x86_64                                       | 9         | 1.97%   |
| 5.19.13-300.fc37.x86_64                                      | 9         | 1.97%   |
| 5.19.14-300.fc37.x86_64                                      | 7         | 1.54%   |
| 6.0.6-300.fc37.x86_64                                        | 6         | 1.32%   |
| 5.19.15-301.fc37.x86_64                                      | 6         | 1.32%   |
| 5.19.11-300.fc37.x86_64                                      | 6         | 1.32%   |
| 5.19.10-300.fc37.x86_64                                      | 6         | 1.32%   |
| 5.19.9-300.fc37.x86_64                                       | 5         | 1.1%    |
| 5.19.12-300.fc37.x86_64                                      | 4         | 0.88%   |
| 6.0.5-300.fc37.x86_64                                        | 3         | 0.66%   |
| 5.19.16-300.fc37.x86_64                                      | 3         | 0.66%   |
| 6.0.9-300.mbp.fc37.x86_64                                    | 2         | 0.44%   |
| 6.0.2-xm1.0.fc37.x86_64                                      | 2         | 0.44%   |
| 5.19.15-300.fc37.x86_64                                      | 2         | 0.44%   |
| 5.18.0-0.rc2.23.fc37.x86_64                                  | 2         | 0.44%   |
| 6.1.1-xm1.0.fc37.x86_64                                      | 1         | 0.22%   |
| 6.1.1-225.vanilla.1.fc37.x86_64                              | 1         | 0.22%   |
| 6.1.0-rc7+                                                   | 1         | 0.22%   |
| 6.1.0-rc6+                                                   | 1         | 0.22%   |
| 6.1.0-rc4+                                                   | 1         | 0.22%   |
| 6.1.0-65.vanilla.1.fc37.x86_64                               | 1         | 0.22%   |
| 6.1.0-0.rc6.46.fc38.x86_64                                   | 1         | 0.22%   |
| 6.1.0-0.rc4.34.inttf.fc37.x86_64                             | 1         | 0.22%   |
| 6.1.0-0.rc0.20221012git49da07006239.10.vanilla.1.fc37.x86_64 | 1         | 0.22%   |
| 6.0.9-350.vanilla.1.fc37.x86_64                              | 1         | 0.22%   |
| 6.0.9-302.rog.fc37.x86_64                                    | 1         | 0.22%   |
| 6.0.9-200.fc36.x86_64                                        | 1         | 0.22%   |
| 6.0.9                                                        | 1         | 0.22%   |
| 6.0.8-xm1.0.fc37.x86_64                                      | 1         | 0.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.9   | 57        | 12.5%   |
| 6.0.8   | 57        | 12.5%   |
| 6.0.12  | 49        | 10.75%  |
| 6.0.15  | 41        | 8.99%   |
| 6.0.10  | 36        | 7.89%   |
| 6.0.11  | 35        | 7.68%   |
| 5.19.16 | 29        | 6.36%   |
| 6.0.7   | 28        | 6.14%   |
| 6.0.14  | 15        | 3.29%   |
| 6.0.13  | 13        | 2.85%   |
| 5.19.8  | 10        | 2.19%   |
| 5.19.7  | 9         | 1.97%   |
| 5.19.13 | 9         | 1.97%   |
| 5.19.15 | 8         | 1.75%   |
| 6.1.0   | 7         | 1.54%   |
| 5.19.14 | 7         | 1.54%   |
| 5.19.10 | 7         | 1.54%   |
| 6.0.6   | 6         | 1.32%   |
| 5.19.12 | 6         | 1.32%   |
| 5.19.11 | 6         | 1.32%   |
| 5.19.9  | 5         | 1.1%    |
| 6.0.5   | 3         | 0.66%   |
| 5.19.0  | 3         | 0.66%   |
| 6.1.1   | 2         | 0.44%   |
| 6.0.2   | 2         | 0.44%   |
| 5.18.0  | 2         | 0.44%   |
| 6.0.0   | 1         | 0.22%   |
| 5.19.4  | 1         | 0.22%   |
| 5.17.5  | 1         | 0.22%   |
| 5.15.55 | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 337       | 75.39%  |
| 5.19    | 97        | 21.7%   |
| 6.1     | 9         | 2.01%   |
| 5.18    | 2         | 0.45%   |
| 5.17    | 1         | 0.22%   |
| 5.15    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 442       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 342       | 77.2%   |
| KDE5       | 68        | 15.35%  |
| Unknown    | 9         | 2.03%   |
| XFCE       | 6         | 1.35%   |
| X-Cinnamon | 5         | 1.13%   |
| MATE       | 4         | 0.9%    |
| LXDE       | 3         | 0.68%   |
| i3         | 2         | 0.45%   |
| xmonad     | 1         | 0.23%   |
| sway       | 1         | 0.23%   |
| LXQt       | 1         | 0.23%   |
| Cinnamon   | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 349       | 78.78%  |
| X11     | 85        | 19.19%  |
| Unknown | 7         | 1.58%   |
| Tty     | 2         | 0.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 229       | 51.81%  |
| GDM     | 155       | 35.07%  |
| SDDM    | 36        | 8.14%   |
| LightDM | 20        | 4.52%   |
| LXDM    | 2         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 226       | 51.13%  |
| ru_RU | 30        | 6.79%   |
| pt_BR | 23        | 5.2%    |
| en_GB | 23        | 5.2%    |
| it_IT | 15        | 3.39%   |
| fr_FR | 15        | 3.39%   |
| de_DE | 15        | 3.39%   |
| en_IN | 13        | 2.94%   |
| en_AU | 10        | 2.26%   |
| es_ES | 6         | 1.36%   |
| es_MX | 5         | 1.13%   |
| tr_TR | 4         | 0.9%    |
| es_AR | 4         | 0.9%    |
| en_CA | 4         | 0.9%    |
| zh_CN | 3         | 0.68%   |
| pl_PL | 3         | 0.68%   |
| hu_HU | 3         | 0.68%   |
| es_CL | 3         | 0.68%   |
| en_ZA | 3         | 0.68%   |
| en_PH | 3         | 0.68%   |
| C     | 3         | 0.68%   |
| zh_TW | 2         | 0.45%   |
| nl_NL | 2         | 0.45%   |
| en_IE | 2         | 0.45%   |
| de_AT | 2         | 0.45%   |
| ca_ES | 2         | 0.45%   |
| uk_UA | 1         | 0.23%   |
| sk_SK | 1         | 0.23%   |
| ro_RO | 1         | 0.23%   |
| pt_PT | 1         | 0.23%   |
| ja_JP | 1         | 0.23%   |
| fr_CA | 1         | 0.23%   |
| fi_FI | 1         | 0.23%   |
| es_US | 1         | 0.23%   |
| es_GT | 1         | 0.23%   |
| es_CU | 1         | 0.23%   |
| en_NZ | 1         | 0.23%   |
| en_IL | 1         | 0.23%   |
| en_DK | 1         | 0.23%   |
| en_AT | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 388       | 87.58%  |
| BIOS | 55        | 12.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 372       | 83.97%  |
| Ext4    | 66        | 14.9%   |
| Overlay | 3         | 0.68%   |
| Xfs     | 2         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 221       | 50%     |
| GPT     | 213       | 48.19%  |
| MBR     | 8         | 1.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 400       | 90.29%  |
| Yes       | 43        | 9.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 362       | 81.9%   |
| Yes       | 80        | 18.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 132       | 29.86%  |
| Hewlett-Packard       | 64        | 14.48%  |
| Dell                  | 61        | 13.8%   |
| ASUSTek Computer      | 55        | 12.44%  |
| Acer                  | 30        | 6.79%   |
| HUAWEI                | 19        | 4.3%    |
| MSI                   | 14        | 3.17%   |
| Apple                 | 10        | 2.26%   |
| Timi                  | 7         | 1.58%   |
| Google                | 6         | 1.36%   |
| GPD                   | 5         | 1.13%   |
| Toshiba               | 4         | 0.9%    |
| TUXEDO                | 3         | 0.68%   |
| System76              | 3         | 0.68%   |
| Schenker              | 3         | 0.68%   |
| Samsung Electronics   | 3         | 0.68%   |
| Sony                  | 2         | 0.45%   |
| Pegatron              | 2         | 0.45%   |
| MACHENIKE             | 2         | 0.45%   |
| Framework             | 2         | 0.45%   |
| Valve                 | 1         | 0.23%   |
| UNOWHY                | 1         | 0.23%   |
| SLIMBOOK              | 1         | 0.23%   |
| Positivo Bahia - VAIO | 1         | 0.23%   |
| Notebook              | 1         | 0.23%   |
| LG Electronics        | 1         | 0.23%   |
| Kraftway              | 1         | 0.23%   |
| Jooyon Tech           | 1         | 0.23%   |
| Irbis                 | 1         | 0.23%   |
| Eluktronics           | 1         | 0.23%   |
| BANGHO                | 1         | 0.23%   |
| AVITA                 | 1         | 0.23%   |
| Alienware             | 1         | 0.23%   |
| A-DATA Technology     | 1         | 0.23%   |
| Unknown               | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI CREM-WXX9                           | 4         | 0.9%    |
| Lenovo ThinkBook 15 G3 ACL 21A4            | 3         | 0.68%   |
| GPD G1619-04                               | 3         | 0.68%   |
| Dell Inspiron 5566                         | 3         | 0.68%   |
| Apple MacBookPro9,2                        | 3         | 0.68%   |
| Timi A35S                                  | 2         | 0.45%   |
| MSI Stealth GS66 12UGS                     | 2         | 0.45%   |
| MACHENIKE MACHCREATOR-16                   | 2         | 0.45%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 2         | 0.45%   |
| Lenovo Legion 5 15ACH6H 82JU               | 2         | 0.45%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 2         | 0.45%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 2         | 0.45%   |
| Lenovo IdeaPad 3 15ALC6 82KU               | 2         | 0.45%   |
| HUAWEI NBLB-WAX9N                          | 2         | 0.45%   |
| HUAWEI MACH-WX9                            | 2         | 0.45%   |
| HUAWEI KLVL-WXX9                           | 2         | 0.45%   |
| HUAWEI HVY-WXX9                            | 2         | 0.45%   |
| HUAWEI BOHK-WAX9X                          | 2         | 0.45%   |
| HP ProBook 640 G1                          | 2         | 0.45%   |
| HP ProBook 440 G7                          | 2         | 0.45%   |
| HP Pavilion Laptop 14-dv0xxx               | 2         | 0.45%   |
| HP OMEN by Laptop 16-c0xxx                 | 2         | 0.45%   |
| HP Laptop 15-dw3xxx                        | 2         | 0.45%   |
| HP Laptop 15-da0xxx                        | 2         | 0.45%   |
| HP EliteBook 820 G1                        | 2         | 0.45%   |
| Framework Laptop (12th Gen Intel Core)     | 2         | 0.45%   |
| Dell XPS 15 9520                           | 2         | 0.45%   |
| Dell XPS 13 9380                           | 2         | 0.45%   |
| Dell Latitude 7490                         | 2         | 0.45%   |
| Dell Latitude 7480                         | 2         | 0.45%   |
| Dell Latitude 7420                         | 2         | 0.45%   |
| Dell Latitude 5420                         | 2         | 0.45%   |
| Dell Inspiron 3583                         | 2         | 0.45%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.45%   |
| ASUS ZenBook UX534FTC_UX534FT              | 2         | 0.45%   |
| ASUS VivoBook_ASUSLaptop M5402RA_M5402RA   | 2         | 0.45%   |
| Apple MacBookPro10,1                       | 2         | 0.45%   |
| Acer Aspire A515-51                        | 2         | 0.45%   |
| Acer Aspire A515-45                        | 2         | 0.45%   |
| Unknown                                    | 2         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 78        | 17.65%  |
| Lenovo IdeaPad           | 27        | 6.11%   |
| Dell Inspiron            | 24        | 5.43%   |
| Dell Latitude            | 19        | 4.3%    |
| Acer Aspire              | 18        | 4.07%   |
| HP Laptop                | 16        | 3.62%   |
| HP Pavilion              | 15        | 3.39%   |
| Lenovo ThinkBook         | 14        | 3.17%   |
| ASUS VivoBook            | 13        | 2.94%   |
| Dell XPS                 | 12        | 2.71%   |
| ASUS ASUS                | 11        | 2.49%   |
| HP ProBook               | 10        | 2.26%   |
| ASUS ROG                 | 8         | 1.81%   |
| HP EliteBook             | 7         | 1.58%   |
| ASUS Zenbook             | 7         | 1.58%   |
| Lenovo Legion            | 6         | 1.36%   |
| HP ZBook                 | 6         | 1.36%   |
| MSI Modern               | 4         | 0.9%    |
| HUAWEI CREM-WXX9         | 4         | 0.9%    |
| Acer Predator            | 4         | 0.9%    |
| Acer Nitro               | 4         | 0.9%    |
| Toshiba Satellite        | 3         | 0.68%   |
| HP OMEN                  | 3         | 0.68%   |
| GPD G1619-04             | 3         | 0.68%   |
| Dell Vostro              | 3         | 0.68%   |
| Apple MacBookPro9        | 3         | 0.68%   |
| TUXEDO InfinityBook      | 2         | 0.45%   |
| Timi RedmiBook           | 2         | 0.45%   |
| Timi A35S                | 2         | 0.45%   |
| MSI Stealth              | 2         | 0.45%   |
| MACHENIKE MACHCREATOR-16 | 2         | 0.45%   |
| HUAWEI NBLB-WAX9N        | 2         | 0.45%   |
| HUAWEI MACH-WX9          | 2         | 0.45%   |
| HUAWEI KLVL-WXX9         | 2         | 0.45%   |
| HUAWEI HVY-WXX9          | 2         | 0.45%   |
| HUAWEI BOHK-WAX9X        | 2         | 0.45%   |
| HP ENVY                  | 2         | 0.45%   |
| Framework Laptop         | 2         | 0.45%   |
| Apple MacBookPro10       | 2         | 0.45%   |
| Unknown                  | 2         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 100       | 22.62%  |
| 2020 | 75        | 16.97%  |
| 2022 | 60        | 13.57%  |
| 2018 | 42        | 9.5%    |
| 2019 | 40        | 9.05%   |
| 2017 | 29        | 6.56%   |
| 2013 | 22        | 4.98%   |
| 2016 | 20        | 4.52%   |
| 2012 | 15        | 3.39%   |
| 2015 | 12        | 2.71%   |
| 2014 | 7         | 1.58%   |
| 2010 | 7         | 1.58%   |
| 2011 | 6         | 1.36%   |
| 2008 | 5         | 1.13%   |
| 2007 | 1         | 0.23%   |
| 2006 | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 442       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 317       | 71.72%  |
| Enabled  | 125       | 28.28%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 435       | 98.42%  |
| Yes  | 7         | 1.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 131       | 29.64%  |
| 16.01-24.0  | 104       | 23.53%  |
| 8.01-16.0   | 100       | 22.62%  |
| 32.01-64.0  | 47        | 10.63%  |
| 3.01-4.0    | 32        | 7.24%   |
| 64.01-256.0 | 11        | 2.49%   |
| 24.01-32.0  | 10        | 2.26%   |
| 1.01-2.0    | 5         | 1.13%   |
| 2.01-3.0    | 2         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 147       | 32.59%  |
| 2.01-3.0   | 112       | 24.83%  |
| 3.01-4.0   | 111       | 24.61%  |
| 8.01-16.0  | 38        | 8.43%   |
| 1.01-2.0   | 33        | 7.32%   |
| 0.51-1.0   | 7         | 1.55%   |
| 16.01-24.0 | 2         | 0.44%   |
| 24.01-32.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 333       | 75.17%  |
| 2      | 101       | 22.8%   |
| 3      | 6         | 1.35%   |
| 0      | 3         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 383       | 86.65%  |
| Yes       | 59        | 13.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 299       | 67.65%  |
| No        | 143       | 32.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 439       | 99.32%  |
| No        | 3         | 0.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 387       | 87.56%  |
| No        | 55        | 12.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 65        | 14.67%  |
| Russia              | 38        | 8.58%   |
| India               | 31        | 7%      |
| Brazil              | 31        | 7%      |
| Germany             | 29        | 6.55%   |
| Italy               | 25        | 5.64%   |
| France              | 18        | 4.06%   |
| Australia           | 13        | 2.93%   |
| Spain               | 12        | 2.71%   |
| Poland              | 10        | 2.26%   |
| Netherlands         | 10        | 2.26%   |
| Canada              | 10        | 2.26%   |
| Turkey              | 9         | 2.03%   |
| UK                  | 8         | 1.81%   |
| Mexico              | 8         | 1.81%   |
| Switzerland         | 7         | 1.58%   |
| Argentina           | 7         | 1.58%   |
| Czechia             | 6         | 1.35%   |
| Austria             | 6         | 1.35%   |
| Taiwan              | 5         | 1.13%   |
| Sweden              | 5         | 1.13%   |
| Hungary             | 5         | 1.13%   |
| Slovakia            | 4         | 0.9%    |
| Philippines         | 4         | 0.9%    |
| Ireland             | 4         | 0.9%    |
| Indonesia           | 4         | 0.9%    |
| Finland             | 4         | 0.9%    |
| South Africa        | 3         | 0.68%   |
| Norway              | 3         | 0.68%   |
| Japan               | 3         | 0.68%   |
| Chile               | 3         | 0.68%   |
| Trinidad and Tobago | 2         | 0.45%   |
| Thailand            | 2         | 0.45%   |
| Serbia              | 2         | 0.45%   |
| Qatar               | 2         | 0.45%   |
| Peru                | 2         | 0.45%   |
| Pakistan            | 2         | 0.45%   |
| Israel              | 2         | 0.45%   |
| Hong Kong           | 2         | 0.45%   |
| Dominican Republic  | 2         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 11        | 2.46%   |
| Madrid             | 5         | 1.12%   |
| Brisbane           | 5         | 1.12%   |
| Vienna             | 4         | 0.89%   |
| St Petersburg      | 4         | 0.89%   |
| Sao Paulo          | 4         | 0.89%   |
| Zapopan            | 3         | 0.67%   |
| Warsaw             | 3         | 0.67%   |
| Pune               | 3         | 0.67%   |
| Paris              | 3         | 0.67%   |
| Milan              | 3         | 0.67%   |
| Miami              | 3         | 0.67%   |
| Melbourne          | 3         | 0.67%   |
| London             | 3         | 0.67%   |
| Karlskrona         | 3         | 0.67%   |
| Jakarta            | 3         | 0.67%   |
| Istanbul           | 3         | 0.67%   |
| Easton             | 3         | 0.67%   |
| Delft              | 3         | 0.67%   |
| Curitiba           | 3         | 0.67%   |
| Chennai            | 3         | 0.67%   |
| Cape Town          | 3         | 0.67%   |
| Berlin             | 3         | 0.67%   |
| Bengaluru          | 3         | 0.67%   |
| Vladimir           | 2         | 0.45%   |
| Verona             | 2         | 0.45%   |
| Sydney             | 2         | 0.45%   |
| Springfield        | 2         | 0.45%   |
| Sao Jose           | 2         | 0.45%   |
| Santo Domingo Este | 2         | 0.45%   |
| Santiago           | 2         | 0.45%   |
| Rostov-on-Don      | 2         | 0.45%   |
| Rishon LeZiyyon    | 2         | 0.45%   |
| Prague             | 2         | 0.45%   |
| Portland           | 2         | 0.45%   |
| Perm               | 2         | 0.45%   |
| Oslo               | 2         | 0.45%   |
| Nizhniy Novgorod   | 2         | 0.45%   |
| New York           | 2         | 0.45%   |
| New Taipei         | 2         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 120       | 135    | 22.39%  |
| SanDisk                        | 55        | 60     | 10.26%  |
| WDC                            | 53        | 55     | 9.89%   |
| SK hynix                       | 49        | 49     | 9.14%   |
| Kingston                       | 30        | 31     | 5.6%    |
| Micron Technology              | 26        | 27     | 4.85%   |
| Toshiba                        | 23        | 24     | 4.29%   |
| Intel                          | 20        | 21     | 3.73%   |
| Unknown                        | 19        | 23     | 3.54%   |
| Seagate                        | 18        | 18     | 3.36%   |
| Crucial                        | 18        | 18     | 3.36%   |
| KIOXIA                         | 9         | 10     | 1.68%   |
| A-DATA Technology              | 7         | 8      | 1.31%   |
| Apple                          | 6         | 9      | 1.12%   |
| Hitachi                        | 5         | 5      | 0.93%   |
| HGST                           | 5         | 5      | 0.93%   |
| ADATA Technology               | 5         | 5      | 0.93%   |
| Micron/Crucial Technology      | 4         | 4      | 0.75%   |
| LITEON                         | 4         | 4      | 0.75%   |
| China                          | 4         | 4      | 0.75%   |
| UMIS                           | 3         | 3      | 0.56%   |
| Phison Electronics             | 3         | 3      | 0.56%   |
| Phison                         | 3         | 3      | 0.56%   |
| Kingston Technology Company    | 3         | 3      | 0.56%   |
| YMTC                           | 2         | 2      | 0.37%   |
| XPG                            | 2         | 2      | 0.37%   |
| SPCC                           | 2         | 2      | 0.37%   |
| Solid State Storage Technology | 2         | 2      | 0.37%   |
| Silicon Motion                 | 2         | 2      | 0.37%   |
| SABRENT                        | 2         | 2      | 0.37%   |
| PNY                            | 2         | 2      | 0.37%   |
| Lexar                          | 2         | 2      | 0.37%   |
| FORESEE                        | 2         | 2      | 0.37%   |
| Biwin Storage Technology       | 2         | 2      | 0.37%   |
| Unknown                        | 2         | 2      | 0.37%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.19%   |
| Teclast                        | 1         | 1      | 0.19%   |
| Team                           | 1         | 2      | 0.19%   |
| SYMWAVE                        | 1         | 1      | 0.19%   |
| Simmtronic                     | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB             | 20        | 3.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                | 9         | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB              | 9         | 1.64%   |
| Toshiba MQ04ABF100 1TB                                          | 8         | 1.45%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB                            | 7         | 1.27%   |
| Kingston SA400S37240G 240GB SSD                                 | 7         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 6         | 1.09%   |
| SK hynix BC501 NVMe Solid State Drive 512GB                     | 5         | 0.91%   |
| Sandisk WD Black SN850 1TB                                      | 5         | 0.91%   |
| Samsung MZALQ512HBLU-00BL2 512GB                                | 5         | 0.91%   |
| Crucial CT240BX500SSD1 240GB                                    | 5         | 0.91%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                | 4         | 0.73%   |
| Unknown MMC Card  64GB                                          | 4         | 0.73%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB                          | 4         | 0.73%   |
| Samsung MZVLQ512HALU-000H1 512GB                                | 4         | 0.73%   |
| Samsung MZVLQ512HALU-00000 512GB                                | 4         | 0.73%   |
| Samsung MZALQ512HALU-000L2 512GB                                | 4         | 0.73%   |
| KIOXIA KBG40ZNV512G 512GB                                       | 4         | 0.73%   |
| Intel SSD 600P Series 512GB                                     | 4         | 0.73%   |
| WDC WD10SPZX-60Z10T0 1TB                                        | 3         | 0.55%   |
| WDC WD10SPZX-21Z10T0 1TB                                        | 3         | 0.55%   |
| WDC PC SN730 SDBPNTY-512G                                       | 3         | 0.55%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 3         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 0.55%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB                 | 3         | 0.55%   |
| SanDisk NVMe SSD Drive 1TB                                      | 3         | 0.55%   |
| Samsung SSD 980 500GB                                           | 3         | 0.55%   |
| Samsung SSD 860 EVO 500GB                                       | 3         | 0.55%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                                | 3         | 0.55%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                                  | 3         | 0.55%   |
| Micron 2450_MTFDKBA512TFK 512GB                                 | 3         | 0.55%   |
| Micron 2210_MTFDHBA512QFD 512GB                                 | 3         | 0.55%   |
| Kingston OM8PCP3512F-AI1 512GB                                  | 3         | 0.55%   |
| Kingston OM8PCP3512F-AB 512GB                                   | 3         | 0.55%   |
| Intel SSDPEKNU512GZ 512GB                                       | 3         | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                                     | 3         | 0.55%   |
| Crucial CT1000BX500SSD1 1TB                                     | 3         | 0.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3         | 0.55%   |
| A-DATA IM2P33F8ABR2-256GB                                       | 3         | 0.55%   |
| YMTC PC005 512GB                                                | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 22        | 22     | 32.84%  |
| Seagate  | 18        | 18     | 26.87%  |
| Toshiba  | 16        | 16     | 23.88%  |
| Hitachi  | 5         | 5      | 7.46%   |
| HGST     | 5         | 5      | 7.46%   |
| External | 1         | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 27     | 20.83%  |
| Crucial             | 16        | 16     | 13.33%  |
| Kingston            | 14        | 14     | 11.67%  |
| WDC                 | 11        | 11     | 9.17%   |
| SanDisk             | 11        | 11     | 9.17%   |
| SK hynix            | 5         | 5      | 4.17%   |
| Micron Technology   | 4         | 4      | 3.33%   |
| China               | 4         | 4      | 3.33%   |
| Intel               | 3         | 3      | 2.5%    |
| Apple               | 3         | 3      | 2.5%    |
| SPCC                | 2         | 2      | 1.67%   |
| PNY                 | 2         | 2      | 1.67%   |
| LITEON              | 2         | 2      | 1.67%   |
| Lexar               | 2         | 2      | 1.67%   |
| FORESEE             | 2         | 2      | 1.67%   |
| A-DATA Technology   | 2         | 2      | 1.67%   |
| Toshiba             | 1         | 1      | 0.83%   |
| Teclast             | 1         | 1      | 0.83%   |
| Team                | 1         | 2      | 0.83%   |
| Ramaxel Technology  | 1         | 1      | 0.83%   |
| JAMESDONKEY         | 1         | 1      | 0.83%   |
| Intenso             | 1         | 1      | 0.83%   |
| HS-SSD-C100         | 1         | 1      | 0.83%   |
| GOODRAM             | 1         | 2      | 0.83%   |
| Gigabyte Technology | 1         | 1      | 0.83%   |
| ExeGate             | 1         | 1      | 0.83%   |
| Eluktro             | 1         | 1      | 0.83%   |
| Apacer              | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 300       | 354    | 58.94%  |
| SSD     | 117       | 124    | 22.99%  |
| HDD     | 67        | 67     | 13.16%  |
| MMC     | 21        | 25     | 4.13%   |
| Unknown | 4         | 4      | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 300       | 352    | 60.85%  |
| SATA | 164       | 189    | 33.27%  |
| MMC  | 21        | 25     | 4.26%   |
| SAS  | 8         | 8      | 1.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 122    | 62.22%  |
| 0.51-1.0   | 57        | 57     | 31.67%  |
| 1.01-2.0   | 7         | 8      | 3.89%   |
| 3.01-4.0   | 3         | 3      | 1.67%   |
| 4.01-10.0  | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 107       | 24.04%  |
| 251-500        | 92        | 20.67%  |
| 1-20           | 66        | 14.83%  |
| 101-250        | 56        | 12.58%  |
| 1001-2000      | 47        | 10.56%  |
| Unknown        | 36        | 8.09%   |
| 21-50          | 12        | 2.7%    |
| More than 3000 | 10        | 2.25%   |
| 51-100         | 10        | 2.25%   |
| 2001-3000      | 9         | 2.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 140       | 31.18%  |
| 21-50     | 80        | 17.82%  |
| 101-250   | 63        | 14.03%  |
| 51-100    | 57        | 12.69%  |
| 251-500   | 44        | 9.8%    |
| Unknown   | 36        | 8.02%   |
| 501-1000  | 22        | 4.9%    |
| 1001-2000 | 6         | 1.34%   |
| 2001-3000 | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 8.33%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 8.33%   |
| Toshiba MK3265GSX 320GB                             | 1         | 1      | 8.33%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 8.33%   |
| Seagate ST4000LM024-2AN17V 4TB                      | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 8.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 25%     |
| Seagate             | 3         | 3      | 25%     |
| WDC                 | 2         | 2      | 16.67%  |
| Micron Technology   | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 37.5%   |
| Seagate | 3         | 3      | 37.5%   |
| WDC     | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 66.67%  |
| SSD  | 4         | 4      | 33.33%  |

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
| Detected | 256       | 335    | 55.77%  |
| Works    | 191       | 227    | 41.61%  |
| Malfunc  | 12        | 12     | 2.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 233       | 39.36%  |
| Samsung Electronics            | 97        | 16.39%  |
| SanDisk                        | 65        | 10.98%  |
| AMD                            | 53        | 8.95%   |
| SK hynix                       | 44        | 7.43%   |
| Micron Technology              | 23        | 3.89%   |
| Kingston Technology Company    | 19        | 3.21%   |
| ADATA Technology               | 10        | 1.69%   |
| KIOXIA                         | 8         | 1.35%   |
| Toshiba America Info Systems   | 7         | 1.18%   |
| Phison Electronics             | 6         | 1.01%   |
| Micron/Crucial Technology      | 5         | 0.84%   |
| Yangtze Memory Technologies    | 3         | 0.51%   |
| Union Memory (Shenzhen)        | 3         | 0.51%   |
| Silicon Motion                 | 3         | 0.51%   |
| Lite-On Technology             | 3         | 0.51%   |
| Apple                          | 3         | 0.51%   |
| Solid State Storage Technology | 2         | 0.34%   |
| Biwin Storage Technology       | 2         | 0.34%   |
| Netac Technology               | 1         | 0.17%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.17%   |
| Lenovo                         | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 53        | 8.58%   |
| Samsung NVMe SSD Controller 980                                                | 38        | 6.15%   |
| Intel Volume Management Device NVMe RAID Controller                            | 38        | 6.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 36        | 5.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 34        | 5.5%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 26        | 4.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 25        | 4.05%   |
| Micron Non-Volatile memory controller                                          | 23        | 3.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 22        | 3.56%   |
| SanDisk Non-Volatile memory controller                                         | 21        | 3.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 21        | 3.4%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 15        | 2.43%   |
| Intel Tiger Lake-LP SATA Controller                                            | 14        | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 2.27%   |
| Kingston Company Company Non-Volatile memory controller                        | 12        | 1.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 1.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 11        | 1.78%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 9         | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.29%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 1.13%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 7         | 1.13%   |
| Intel Non-Volatile memory controller                                           | 7         | 1.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.13%   |
| SK hynix Non-Volatile memory controller                                        | 6         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 0.81%   |
| Intel SSD 600P Series                                                          | 4         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 0.65%   |
| Yangtze Memory Non-Volatile memory controller                                  | 3         | 0.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.49%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 3         | 0.49%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.49%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.49%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.49%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.49%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 299       | 50.42%  |
| SATA | 230       | 38.79%  |
| RAID | 61        | 10.29%  |
| IDE  | 3         | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 328       | 74.21%  |
| AMD    | 114       | 25.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 3.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 3.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 2.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 2.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 2.26%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 2.26%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 2.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 1.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.58%   |
| Intel 12th Gen Core i5-1240P                  | 7         | 1.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.36%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 1.36%   |
| Intel 12th Gen Core i9-12900H                 | 6         | 1.36%   |
| Intel 12th Gen Core i7-12700H                 | 6         | 1.36%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 1.36%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 1.36%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 1.36%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 1.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.13%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 1.13%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 1.13%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 1.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.9%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 0.9%    |
| AMD Ryzen 7 6800U with Radeon Graphics        | 4         | 0.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.9%    |
| AMD Ryzen 5 5625U with Radeon Graphics        | 4         | 0.9%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.9%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.68%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 98        | 22.17%  |
| Other                   | 94        | 21.27%  |
| Intel Core i7           | 81        | 18.33%  |
| AMD Ryzen 7             | 46        | 10.41%  |
| AMD Ryzen 5             | 35        | 7.92%   |
| Intel Core i3           | 24        | 5.43%   |
| Intel Celeron           | 12        | 2.71%   |
| AMD Ryzen 7 PRO         | 8         | 1.81%   |
| AMD Ryzen 3             | 7         | 1.58%   |
| Intel Core 2 Duo        | 6         | 1.36%   |
| AMD Ryzen 9             | 6         | 1.36%   |
| AMD Ryzen 5 PRO         | 6         | 1.36%   |
| Intel Core i9           | 4         | 0.9%    |
| Intel Pentium Silver    | 3         | 0.68%   |
| Intel Atom              | 3         | 0.68%   |
| AMD A4                  | 3         | 0.68%   |
| Intel Pentium Dual-Core | 1         | 0.23%   |
| Intel Core m5           | 1         | 0.23%   |
| Intel Core m3           | 1         | 0.23%   |
| Intel Core 2            | 1         | 0.23%   |
| AMD E1                  | 1         | 0.23%   |
| AMD A6                  | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 159       | 35.97%  |
| 2      | 125       | 28.28%  |
| 8      | 69        | 15.61%  |
| 6      | 52        | 11.76%  |
| 14     | 14        | 3.17%   |
| 12     | 13        | 2.94%   |
| 10     | 8         | 1.81%   |
| 16     | 1         | 0.23%   |
| 1      | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 442       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 399       | 90.27%  |
| 1      | 43        | 9.73%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 442       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 41        | 9.23%   |
| 0x806ec    | 31        | 6.98%   |
| 0x806ea    | 28        | 6.31%   |
| 0x906a3    | 27        | 6.08%   |
| 0x0a50000c | 27        | 6.08%   |
| Unknown    | 25        | 5.63%   |
| 0x306a9    | 22        | 4.95%   |
| 0x08600106 | 17        | 3.83%   |
| 0x806e9    | 16        | 3.6%    |
| 0x406e3    | 15        | 3.38%   |
| 0x08608103 | 15        | 3.38%   |
| 0x906ea    | 13        | 2.93%   |
| 0xa0652    | 12        | 2.7%    |
| 0x40651    | 9         | 2.03%   |
| 0x306d4    | 9         | 2.03%   |
| 0x08600104 | 9         | 2.03%   |
| 0x906a4    | 8         | 1.8%    |
| 0x806d1    | 8         | 1.8%    |
| 0x306c3    | 8         | 1.8%    |
| 0x08108109 | 8         | 1.8%    |
| 0x206a7    | 7         | 1.58%   |
| 0x906e9    | 6         | 1.35%   |
| 0x706a8    | 6         | 1.35%   |
| 0x0a404101 | 6         | 1.35%   |
| 0x806c2    | 5         | 1.13%   |
| 0x506e3    | 5         | 1.13%   |
| 0x806eb    | 4         | 0.9%    |
| 0x706e5    | 4         | 0.9%    |
| 0x1067a    | 4         | 0.9%    |
| 0x0a404102 | 4         | 0.9%    |
| 0x08608102 | 4         | 0.9%    |
| 0x906ed    | 3         | 0.68%   |
| 0x506c9    | 3         | 0.68%   |
| 0x906c0    | 2         | 0.45%   |
| 0x6fd      | 2         | 0.45%   |
| 0x406c4    | 2         | 0.45%   |
| 0x30678    | 2         | 0.45%   |
| 0x30673    | 2         | 0.45%   |
| 0x20655    | 2         | 0.45%   |
| 0x20652    | 2         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 110       | 24.89%  |
| TigerLake        | 49        | 11.09%  |
| Alderlake Hybrid | 36        | 8.14%   |
| Zen 3            | 34        | 7.69%   |
| Unknown          | 33        | 7.47%   |
| Zen 2            | 28        | 6.33%   |
| IvyBridge        | 22        | 4.98%   |
| Skylake          | 21        | 4.75%   |
| Haswell          | 18        | 4.07%   |
| IceLake          | 13        | 2.94%   |
| CometLake        | 12        | 2.71%   |
| Zen+             | 10        | 2.26%   |
| Broadwell        | 9         | 2.04%   |
| SandyBridge      | 7         | 1.58%   |
| Goldmont plus    | 7         | 1.58%   |
| Silvermont       | 6         | 1.36%   |
| Zen              | 4         | 0.9%    |
| Westmere         | 4         | 0.9%    |
| Penryn           | 4         | 0.9%    |
| Core             | 4         | 0.9%    |
| Goldmont         | 3         | 0.68%   |
| Excavator        | 3         | 0.68%   |
| Tremont          | 2         | 0.45%   |
| Nehalem          | 1         | 0.23%   |
| K10 Llano        | 1         | 0.23%   |
| Jaguar           | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 318       | 55.11%  |
| Nvidia | 130       | 22.53%  |
| AMD    | 129       | 22.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 41        | 7.02%   |
| AMD Renoir                                                                            | 28        | 4.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 27        | 4.62%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 26        | 4.45%   |
| Intel UHD Graphics 620                                                                | 25        | 4.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 22        | 3.77%   |
| AMD Lucienne                                                                          | 22        | 3.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 21        | 3.6%    |
| Intel HD Graphics 620                                                                 | 20        | 3.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 17        | 2.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 16        | 2.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 14        | 2.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 11        | 1.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 10        | 1.71%   |
| AMD Rembrandt [Radeon 680M]                                                           | 10        | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 10        | 1.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 9         | 1.54%   |
| Nvidia GP108M [GeForce MX150]                                                         | 9         | 1.54%   |
| Intel HD Graphics 5500                                                                | 9         | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 9         | 1.54%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 8         | 1.37%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 8         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 8         | 1.37%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 7         | 1.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 7         | 1.2%    |
| AMD Barcelo                                                                           | 7         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 6         | 1.03%   |
| Intel HD Graphics 630                                                                 | 6         | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 1.03%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 5         | 0.86%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 5         | 0.86%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 5         | 0.86%   |
| Nvidia TU117M                                                                         | 4         | 0.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 4         | 0.68%   |
| Intel HD Graphics 530                                                                 | 4         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 4         | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 4         | 0.68%   |
| Nvidia TU117M [GeForce MX450]                                                         | 3         | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 201       | 45.48%  |
| Intel + Nvidia     | 102       | 23.08%  |
| 1 x AMD            | 97        | 21.95%  |
| AMD + Nvidia       | 18        | 4.07%   |
| Intel + AMD        | 11        | 2.49%   |
| 1 x Nvidia         | 8         | 1.81%   |
| 2 x AMD            | 3         | 0.68%   |
| 2 x Intel          | 1         | 0.23%   |
| Intel + 2 x Nvidia | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 367       | 82.84%  |
| Proprietary | 73        | 16.48%  |
| Unknown     | 3         | 0.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 270       | 60.81%  |
| 0.01-0.5   | 71        | 15.99%  |
| 1.01-2.0   | 45        | 10.14%  |
| 3.01-4.0   | 23        | 5.18%   |
| 0.51-1.0   | 20        | 4.5%    |
| 5.01-6.0   | 8         | 1.8%    |
| 2.01-3.0   | 3         | 0.68%   |
| 7.01-8.0   | 2         | 0.45%   |
| 8.01-16.0  | 2         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 112       | 21.13%  |
| AU Optronics            | 99        | 18.68%  |
| Chimei Innolux          | 67        | 12.64%  |
| LG Display              | 54        | 10.19%  |
| Samsung Electronics     | 29        | 5.47%   |
| CSO                     | 15        | 2.83%   |
| PANDA                   | 14        | 2.64%   |
| Goldstar                | 14        | 2.64%   |
| Dell                    | 13        | 2.45%   |
| Sharp                   | 10        | 1.89%   |
| Lenovo                  | 10        | 1.89%   |
| Apple                   | 10        | 1.89%   |
| Hewlett-Packard         | 8         | 1.51%   |
| InfoVision              | 7         | 1.32%   |
| BenQ                    | 7         | 1.32%   |
| JDI                     | 5         | 0.94%   |
| AOC                     | 5         | 0.94%   |
| Philips                 | 4         | 0.75%   |
| Acer                    | 4         | 0.75%   |
| ViewSonic               | 3         | 0.57%   |
| Toshiba                 | 3         | 0.57%   |
| TMX                     | 3         | 0.57%   |
| Chi Mei Optoelectronics | 3         | 0.57%   |
| Sony                    | 2         | 0.38%   |
| Panasonic               | 2         | 0.38%   |
| MSI                     | 2         | 0.38%   |
| Mi                      | 2         | 0.38%   |
| LG Philips              | 2         | 0.38%   |
| HUAWEI                  | 2         | 0.38%   |
| ASUSTek Computer        | 2         | 0.38%   |
| Vizio                   | 1         | 0.19%   |
| Vestel Elektronik       | 1         | 0.19%   |
| Valve                   | 1         | 0.19%   |
| Tianma XM               | 1         | 0.19%   |
| Sceptre Tech            | 1         | 0.19%   |
| OEM                     | 1         | 0.19%   |
| NCS                     | 1         | 0.19%   |
| LNV                     | 1         | 0.19%   |
| ITE                     | 1         | 0.19%   |
| Iiyama                  | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 7         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 6         | 1.12%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.74%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 4         | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.74%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 3         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.56%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.56%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 3         | 0.56%   |
| CSO LCD Monitor CSO160A 2560x1600 345x215mm 16.0-inch                 | 3         | 0.56%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                 | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 0.56%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.56%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 3         | 0.56%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                | 3         | 0.56%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch               | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 2         | 0.37%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.37%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 2         | 0.37%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 2         | 0.37%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 2         | 0.37%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 0.37%   |
| Mi Monitor XMI3446 3440x1440 797x334mm 34.0-inch                      | 2         | 0.37%   |
| LG Display LCD Monitor LGD06F0 1920x1080 309x174mm 14.0-inch          | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 266       | 52.99%  |
| 1366x768 (WXGA)    | 71        | 14.14%  |
| 2560x1440 (QHD)    | 25        | 4.98%   |
| 2560x1600          | 22        | 4.38%   |
| 1920x1200 (WUXGA)  | 22        | 4.38%   |
| 3840x2160 (4K)     | 19        | 3.78%   |
| 2880x1800          | 13        | 2.59%   |
| 1600x900 (HD+)     | 11        | 2.19%   |
| 1280x800 (WXGA)    | 8         | 1.59%   |
| 3440x1440          | 6         | 1.2%    |
| 1280x1024 (SXGA)   | 6         | 1.2%    |
| 2520x1680          | 4         | 0.8%    |
| 3840x2400          | 3         | 0.6%    |
| 3000x2000          | 3         | 0.6%    |
| 2560x1080          | 3         | 0.6%    |
| 2256x1504          | 3         | 0.6%    |
| 2160x1440          | 3         | 0.6%    |
| 3456x2160          | 2         | 0.4%    |
| 2160x1350          | 2         | 0.4%    |
| 800x1280           | 1         | 0.2%    |
| 3840x1080          | 1         | 0.2%    |
| 3200x2000          | 1         | 0.2%    |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 2304x1440          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1680x1050 (WSXGA+) | 1         | 0.2%    |
| 1440x900 (WXGA+)   | 1         | 0.2%    |
| 1360x768           | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 202       | 37.69%  |
| 13      | 90        | 16.79%  |
| 14      | 83        | 15.49%  |
| 16      | 26        | 4.85%   |
| 27      | 23        | 4.29%   |
| 17      | 20        | 3.73%   |
| 24      | 19        | 3.54%   |
| 23      | 10        | 1.87%   |
| 34      | 9         | 1.68%   |
| 12      | 9         | 1.68%   |
| 21      | 8         | 1.49%   |
| 31      | 5         | 0.93%   |
| 18      | 4         | 0.75%   |
| 11      | 4         | 0.75%   |
| 40      | 3         | 0.56%   |
| 26      | 3         | 0.56%   |
| 20      | 3         | 0.56%   |
| 32      | 2         | 0.37%   |
| 29      | 2         | 0.37%   |
| 19      | 2         | 0.37%   |
| Unknown | 2         | 0.37%   |
| 84      | 1         | 0.19%   |
| 72      | 1         | 0.19%   |
| 54      | 1         | 0.19%   |
| 48      | 1         | 0.19%   |
| 47      | 1         | 0.19%   |
| 25      | 1         | 0.19%   |
| 7       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 349       | 65.85%  |
| 201-300     | 56        | 10.57%  |
| 501-600     | 50        | 9.43%   |
| 351-400     | 29        | 5.47%   |
| 401-500     | 15        | 2.83%   |
| 701-800     | 11        | 2.08%   |
| 601-700     | 9         | 1.7%    |
| 801-900     | 3         | 0.57%   |
| 1001-1500   | 3         | 0.57%   |
| 1501-2000   | 2         | 0.38%   |
| Unknown     | 2         | 0.38%   |
| 1-100       | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 365       | 77.83%  |
| 16/10 | 70        | 14.93%  |
| 3/2   | 14        | 2.99%   |
| 21/9  | 9         | 1.92%   |
| 4/3   | 6         | 1.28%   |
| 5/4   | 3         | 0.64%   |
| 32/9  | 1         | 0.21%   |
| 0.67  | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 205       | 38.25%  |
| 81-90          | 140       | 26.12%  |
| 71-80          | 32        | 5.97%   |
| 301-350        | 26        | 4.85%   |
| 201-250        | 26        | 4.85%   |
| 111-120        | 22        | 4.1%    |
| 121-130        | 19        | 3.54%   |
| 351-500        | 18        | 3.36%   |
| 251-300        | 9         | 1.68%   |
| 151-200        | 9         | 1.68%   |
| 61-70          | 8         | 1.49%   |
| 501-1000       | 5         | 0.93%   |
| 51-60          | 4         | 0.75%   |
| 141-150        | 4         | 0.75%   |
| More than 1000 | 3         | 0.56%   |
| 91-100         | 3         | 0.56%   |
| Unknown        | 2         | 0.37%   |
| 1-40           | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 247       | 47.32%  |
| 101-120       | 89        | 17.05%  |
| 161-240       | 77        | 14.75%  |
| 51-100        | 76        | 14.56%  |
| More than 240 | 31        | 5.94%   |
| Unknown       | 2         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 344       | 76.96%  |
| 2     | 86        | 19.24%  |
| 3     | 9         | 2.01%   |
| 0     | 7         | 1.57%   |
| 5     | 1         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 267       | 40.21%  |
| Realtek Semiconductor    | 229       | 34.49%  |
| Qualcomm Atheros         | 61        | 9.19%   |
| MediaTek                 | 30        | 4.52%   |
| Broadcom                 | 24        | 3.61%   |
| Lenovo                   | 7         | 1.05%   |
| Broadcom Limited         | 5         | 0.75%   |
| TP-Link                  | 4         | 0.6%    |
| Sierra Wireless          | 4         | 0.6%    |
| ASIX Electronics         | 4         | 0.6%    |
| Qualcomm                 | 3         | 0.45%   |
| ASUSTek Computer         | 3         | 0.45%   |
| Xiaomi                   | 2         | 0.3%    |
| Ralink                   | 2         | 0.3%    |
| Marvell Technology Group | 2         | 0.3%    |
| Hewlett-Packard          | 2         | 0.3%    |
| Google                   | 2         | 0.3%    |
| Fibocom                  | 2         | 0.3%    |
| DisplayLink              | 2         | 0.3%    |
| Samsung Electronics      | 1         | 0.15%   |
| Ralink Technology        | 1         | 0.15%   |
| Microsoft                | 1         | 0.15%   |
| Linksys                  | 1         | 0.15%   |
| Huawei Technologies      | 1         | 0.15%   |
| Dell                     | 1         | 0.15%   |
| D-Link                   | 1         | 0.15%   |
| Aquantia                 | 1         | 0.15%   |
| Apple                    | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 134       | 17.09%  |
| Intel Wi-Fi 6 AX201                                               | 42        | 5.36%   |
| Intel Wi-Fi 6 AX200                                               | 37        | 4.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 28        | 3.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 28        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 3.19%   |
| Intel Wireless 8265 / 8275                                        | 24        | 3.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 2.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 12        | 1.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 1.28%   |
| Intel Wireless 8260                                               | 9         | 1.15%   |
| Intel Wireless 7260                                               | 9         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.77%   |
| Intel Wireless 7265                                               | 6         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.77%   |
| Realtek Realtek Network controller                                | 5         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.64%   |
| Intel Wireless 3160                                               | 5         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.64%   |
| Intel Ethernet Connection (16) I219-V                             | 5         | 0.64%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.51%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.51%   |
| Intel Wireless 3165                                               | 4         | 0.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 261       | 56.62%  |
| Realtek Semiconductor | 74        | 16.05%  |
| Qualcomm Atheros      | 52        | 11.28%  |
| MediaTek              | 30        | 6.51%   |
| Broadcom              | 18        | 3.9%    |
| Broadcom Limited      | 5         | 1.08%   |
| Sierra Wireless       | 4         | 0.87%   |
| TP-Link               | 3         | 0.65%   |
| ASUSTek Computer      | 3         | 0.65%   |
| Ralink                | 2         | 0.43%   |
| Hewlett-Packard       | 2         | 0.43%   |
| Fibocom               | 2         | 0.43%   |
| Ralink Technology     | 1         | 0.22%   |
| Qualcomm              | 1         | 0.22%   |
| Linksys               | 1         | 0.22%   |
| Dell                  | 1         | 0.22%   |
| D-Link                | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 42        | 9.11%   |
| Intel Wi-Fi 6 AX200                                            | 37        | 8.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 28        | 6.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 28        | 6.07%   |
| Intel Wireless 8265 / 8275                                     | 24        | 5.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 4.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 3.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 2.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12        | 2.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 2.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 2.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 2.17%   |
| Intel Wireless 8260                                            | 9         | 1.95%   |
| Intel Wireless 7260                                            | 9         | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1.3%    |
| Intel Wireless 7265                                            | 6         | 1.3%    |
| Realtek Realtek Network controller                             | 5         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.08%   |
| Intel Wireless 3160                                            | 5         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.87%   |
| Intel Wireless 3165                                            | 4         | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.87%   |
| Intel Wireless-AC 9260                                         | 3         | 0.65%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 0.65%   |
| ASUS 802.11ac NIC                                              | 3         | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.43%   |
| Sierra Wireless EM7345 4G LTE                                  | 2         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 191       | 60.06%  |
| Intel                    | 78        | 24.53%  |
| Qualcomm Atheros         | 12        | 3.77%   |
| Broadcom                 | 11        | 3.46%   |
| Lenovo                   | 7         | 2.2%    |
| ASIX Electronics         | 4         | 1.26%   |
| Xiaomi                   | 2         | 0.63%   |
| Qualcomm                 | 2         | 0.63%   |
| Marvell Technology Group | 2         | 0.63%   |
| Google                   | 2         | 0.63%   |
| DisplayLink              | 2         | 0.63%   |
| TP-Link                  | 1         | 0.31%   |
| Samsung Electronics      | 1         | 0.31%   |
| Microsoft                | 1         | 0.31%   |
| Aquantia                 | 1         | 0.31%   |
| Apple                    | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 134       | 41.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 7.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 6.21%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 4.35%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.86%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 1.86%   |
| Intel Ethernet Connection (16) I219-V                             | 5         | 1.55%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.24%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 1.24%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.24%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.24%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.24%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.24%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.93%   |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.93%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.62%   |
| Qualcomm MegaFon M150-4                                           | 2         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.62%   |
| Intel Ethernet Controller I225-LM                                 | 2         | 0.62%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.62%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.62%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.62%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.62%   |
| Intel Ethernet Connection (10) I219-LM                            | 2         | 0.62%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.31%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 439       | 59.4%   |
| Ethernet | 299       | 40.46%  |
| Modem    | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 395       | 84.58%  |
| Ethernet | 72        | 15.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 265       | 59.95%  |
| 1     | 164       | 37.1%   |
| 3     | 9         | 2.04%   |
| 0     | 4         | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 333       | 75%     |
| Yes  | 111       | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 232       | 59.79%  |
| Realtek Semiconductor           | 48        | 12.37%  |
| Qualcomm Atheros Communications | 22        | 5.67%   |
| Foxconn / Hon Hai               | 20        | 5.15%   |
| IMC Networks                    | 17        | 4.38%   |
| Lite-On Technology              | 14        | 3.61%   |
| Realtek                         | 11        | 2.84%   |
| Broadcom                        | 8         | 2.06%   |
| Apple                           | 7         | 1.8%    |
| Toshiba                         | 2         | 0.52%   |
| Hewlett-Packard                 | 2         | 0.52%   |
| Opticis                         | 1         | 0.26%   |
| MediaTek                        | 1         | 0.26%   |
| Dell                            | 1         | 0.26%   |
| Corsair                         | 1         | 0.26%   |
| Cambridge Silicon Radio         | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                           | 66        | 17.01%  |
| Intel Bluetooth wireless interface              | 49        | 12.63%  |
| Realtek Bluetooth Radio                         | 40        | 10.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)  | 36        | 9.28%   |
| Intel AX200 Bluetooth                           | 36        | 9.28%   |
| Intel Bluetooth Device                          | 21        | 5.41%   |
| Qualcomm Atheros  Bluetooth Device              | 17        | 4.38%   |
| Foxconn / Hon Hai Wireless_Device               | 17        | 4.38%   |
| Intel AX210 Bluetooth                           | 12        | 3.09%   |
| Realtek Bluetooth Radio                         | 11        | 2.84%   |
| IMC Networks Wireless_Device                    | 9         | 2.32%   |
| Intel Wireless-AC 3168 Bluetooth                | 7         | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                  | 6         | 1.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth      | 5         | 1.29%   |
| Lite-On Bluetooth Device                        | 5         | 1.29%   |
| IMC Networks Bluetooth Radio                    | 4         | 1.03%   |
| Apple Bluetooth Host Controller                 | 4         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter        | 3         | 0.77%   |
| IMC Networks Bluetooth Device                   | 3         | 0.77%   |
| Apple Bluetooth USB Host Controller             | 3         | 0.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0          | 2         | 0.52%   |
| Lite-On Wireless_Device                         | 2         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                | 2         | 0.52%   |
| Intel Centrino Bluetooth Wireless Transceiver   | 2         | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device              | 2         | 0.52%   |
| Broadcom HP Portable Bumble Bee                 | 2         | 0.52%   |
| Broadcom BCM43142 Bluetooth 4.0                 | 2         | 0.52%   |
| Toshiba Integrated Bluetooth HCI                | 1         | 0.26%   |
| Toshiba Bluetooth Device                        | 1         | 0.26%   |
| Realtek RTL8821A Bluetooth                      | 1         | 0.26%   |
| Realtek RTL8723B Bluetooth                      | 1         | 0.26%   |
| Qualcomm Atheros Bluetooth (AR3011)             | 1         | 0.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0           | 1         | 0.26%   |
| Qualcomm Atheros AR3011 Bluetooth               | 1         | 0.26%   |
| Opticis Bluetooth Radio                         | 1         | 0.26%   |
| MediaTek Wireless_Device                        | 1         | 0.26%   |
| IMC Networks Bluetooth                          | 1         | 0.26%   |
| HP Broadcom 2070 Bluetooth Combo                | 1         | 0.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]   | 1         | 0.26%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller | 1         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 324       | 58.17%  |
| AMD                                  | 117       | 21.01%  |
| Nvidia                               | 71        | 12.75%  |
| Lenovo                               | 9         | 1.62%   |
| C-Media Electronics                  | 6         | 1.08%   |
| Logitech                             | 4         | 0.72%   |
| Plantronics                          | 3         | 0.54%   |
| Samsung Electronics                  | 2         | 0.36%   |
| Razer USA                            | 2         | 0.36%   |
| GN Netcom                            | 2         | 0.36%   |
| Apple                                | 2         | 0.36%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.18%   |
| Samson Technologies                  | 1         | 0.18%   |
| RODE Microphones                     | 1         | 0.18%   |
| Realtek Semiconductor                | 1         | 0.18%   |
| Power Delivery                       | 1         | 0.18%   |
| Microchip Technology                 | 1         | 0.18%   |
| Micro Star International             | 1         | 0.18%   |
| JMTek                                | 1         | 0.18%   |
| Huawei Technologies                  | 1         | 0.18%   |
| Hewlett-Packard                      | 1         | 0.18%   |
| Creative Technology                  | 1         | 0.18%   |
| Conexant Systems                     | 1         | 0.18%   |
| Blue Microphones                     | 1         | 0.18%   |
| ASUSTek Computer                     | 1         | 0.18%   |
| Alesis                               | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 102       | 14.89%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 78        | 11.39%  |
| Intel Sunrise Point-LP HD Audio                                            | 63        | 9.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 48        | 7.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 35        | 5.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 3.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 21        | 3.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 18        | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.9%    |
| Intel Comet Lake PCH cAVS                                                  | 12        | 1.75%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 1.31%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 1.31%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 1.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.31%   |
| Nvidia Audio device                                                        | 8         | 1.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 6         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.58%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 4         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.44%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 3         | 0.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 0.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 0.44%   |
| AMD High Definition Audio Controller                                       | 3         | 0.44%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 88        | 32.59%  |
| SK hynix            | 64        | 23.7%   |
| Micron Technology   | 41        | 15.19%  |
| Crucial             | 13        | 4.81%   |
| Kingston            | 12        | 4.44%   |
| Unknown             | 8         | 2.96%   |
| A-DATA Technology   | 8         | 2.96%   |
| Ramaxel Technology  | 5         | 1.85%   |
| G.Skill             | 4         | 1.48%   |
| Unknown             | 4         | 1.48%   |
| Elpida              | 3         | 1.11%   |
| Corsair             | 3         | 1.11%   |
| Goldkey             | 2         | 0.74%   |
| Avant               | 2         | 0.74%   |
| Unknown (ABCD)      | 1         | 0.37%   |
| Transcend           | 1         | 0.37%   |
| Timetec             | 1         | 0.37%   |
| Team                | 1         | 0.37%   |
| Smart Brazil        | 1         | 0.37%   |
| Smart               | 1         | 0.37%   |
| Qumo                | 1         | 0.37%   |
| Patriot             | 1         | 0.37%   |
| Nanya Technology    | 1         | 0.37%   |
| Kllisre             | 1         | 0.37%   |
| High Bridge         | 1         | 0.37%   |
| ASint Technology    | 1         | 0.37%   |
| 4ea5                | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 9         | 3.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 7         | 2.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 7         | 2.47%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 6         | 2.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s     | 6         | 2.12%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 5         | 1.77%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 5         | 1.77%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 5         | 1.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 4         | 1.41%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 1.41%   |
| Unknown                                                        | 4         | 1.41%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s   | 3         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 3         | 1.06%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 1.06%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s       | 3         | 1.06%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s            | 2         | 0.71%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.71%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.71%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s          | 2         | 0.71%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 0.71%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 0.71%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 0.71%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 2         | 0.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s       | 2         | 0.71%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 2         | 0.71%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.71%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s    | 2         | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 2         | 0.71%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 2         | 0.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.71%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM 4800MT/s            | 2         | 0.71%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s        | 2         | 0.71%   |
| Samsung RAM K4EBE3 4ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.71%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| Micron RAM MICRON/MT60B1G16HC-4 8GB SODIMM DDR5 4800MT/s       | 2         | 0.71%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s          | 2         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 143       | 65%     |
| DDR3   | 28        | 12.73%  |
| LPDDR4 | 13        | 5.91%   |
| LPDDR3 | 13        | 5.91%   |
| DDR5   | 10        | 4.55%   |
| LPDDR5 | 9         | 4.09%   |
| DDR2   | 3         | 1.36%   |
| SDRAM  | 1         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 177       | 78.32%  |
| Row Of Chips | 44        | 19.47%  |
| DIMM         | 2         | 0.88%   |
| Chip         | 2         | 0.88%   |
| Unknown      | 1         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 119       | 50.64%  |
| 4096  | 52        | 22.13%  |
| 16384 | 39        | 16.6%   |
| 32768 | 12        | 5.11%   |
| 2048  | 10        | 4.26%   |
| 1024  | 3         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 90        | 38.14%  |
| 2667    | 46        | 19.49%  |
| 1600    | 25        | 10.59%  |
| 2400    | 15        | 6.36%   |
| 2133    | 14        | 5.93%   |
| 4800    | 10        | 4.24%   |
| 6400    | 8         | 3.39%   |
| 4267    | 7         | 2.97%   |
| 4266    | 3         | 1.27%   |
| 3266    | 3         | 1.27%   |
| 1867    | 3         | 1.27%   |
| 1333    | 2         | 0.85%   |
| 800     | 2         | 0.85%   |
| 8400    | 1         | 0.42%   |
| 2933    | 1         | 0.42%   |
| 2048    | 1         | 0.42%   |
| 1334    | 1         | 0.42%   |
| 1066    | 1         | 0.42%   |
| 933     | 1         | 0.42%   |
| 667     | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Brother DCP-1600 | 1         | 100%    |

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
| Chicony Electronics                    | 102       | 24.82%  |
| IMC Networks                           | 60        | 14.6%   |
| Quanta                                 | 39        | 9.49%   |
| Acer                                   | 39        | 9.49%   |
| Microdia                               | 30        | 7.3%    |
| Realtek Semiconductor                  | 21        | 5.11%   |
| Sunplus Innovation Technology          | 19        | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 3.89%   |
| Syntek                                 | 15        | 3.65%   |
| Luxvisions Innotech Limited            | 13        | 3.16%   |
| Lite-On Technology                     | 10        | 2.43%   |
| Logitech                               | 8         | 1.95%   |
| Apple                                  | 7         | 1.7%    |
| Suyin                                  | 5         | 1.22%   |
| Sonix Technology                       | 5         | 1.22%   |
| Silicon Motion                         | 4         | 0.97%   |
| Tripath Technology                     | 3         | 0.73%   |
| Lenovo                                 | 2         | 0.49%   |
| Alcor Micro                            | 2         | 0.49%   |
| USB Camera CS                          | 1         | 0.24%   |
| USB Camera                             | 1         | 0.24%   |
| SunplusIT                              | 1         | 0.24%   |
| Primax Electronics                     | 1         | 0.24%   |
| Novatek Microelectronics               | 1         | 0.24%   |
| Microsoft                              | 1         | 0.24%   |
| MacroSilicon                           | 1         | 0.24%   |
| Importek                               | 1         | 0.24%   |
| Goodong Industry                       | 1         | 0.24%   |
| Generalplus Technology                 | 1         | 0.24%   |
| DJJHFA1BIF5595                         | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 43        | 10.41%  |
| Microdia Integrated_Webcam_HD                       | 20        | 4.84%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 19        | 4.6%    |
| Acer Integrated Camera                              | 19        | 4.6%    |
| IMC Networks Integrated Camera                      | 16        | 3.87%   |
| Realtek Integrated_Webcam_HD                        | 12        | 2.91%   |
| Syntek Integrated Camera                            | 8         | 1.94%   |
| IMC Networks HD Camera                              | 8         | 1.94%   |
| Chicony HD WebCam                                   | 8         | 1.94%   |
| Quanta HD User Facing                               | 7         | 1.69%   |
| Chicony HP TrueVision HD Camera                     | 7         | 1.69%   |
| Quanta HP TrueVision HD Camera                      | 6         | 1.45%   |
| Quanta HP Wide Vision HD Camera                     | 5         | 1.21%   |
| Quanta HP HD Camera                                 | 5         | 1.21%   |
| Quanta HD Webcam                                    | 5         | 1.21%   |
| Lite-On Integrated Camera                           | 5         | 1.21%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 5         | 1.21%   |
| Acer HD Webcam                                      | 5         | 1.21%   |
| Syntek EasyCamera                                   | 4         | 0.97%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 0.97%   |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 0.97%   |
| Chicony USB2.0 Camera                               | 4         | 0.97%   |
| Chicony EasyCamera                                  | 4         | 0.97%   |
| Apple FaceTime HD Camera                            | 4         | 0.97%   |
| Tripath PC Camera                                   | 3         | 0.73%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 0.73%   |
| Sunplus Integrated Webcam                           | 3         | 0.73%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 0.73%   |
| Microdia Integrated_Webcam_FHD                      | 3         | 0.73%   |
| Logitech StreamCam                                  | 3         | 0.73%   |
| IMC Networks XiaoMi Webcam                          | 3         | 0.73%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 0.73%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 0.73%   |
| Chicony ACER HD User Facing                         | 3         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 3         | 0.73%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 0.73%   |
| Acer SunplusIT Integrated Camera                    | 3         | 0.73%   |
| Acer HD Camera                                      | 3         | 0.73%   |
| Syntek Lenovo EasyCamera                            | 2         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 44        | 39.29%  |
| Shenzhen Goodix Technology         | 31        | 27.68%  |
| Validity Sensors                   | 19        | 16.96%  |
| Elan Microelectronics              | 12        | 10.71%  |
| LighTuning Technology              | 3         | 2.68%   |
| Upek                               | 1         | 0.89%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.89%   |
| AuthenTec                          | 1         | 0.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 26        | 23.21%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 22.32%  |
| Unknown                                                                    | 8         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 6.25%   |
| Elan ELAN:ARM-M4                                                           | 7         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 5.36%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.46%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.57%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.68%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.79%   |
| Synaptics  WBDI                                                            | 2         | 1.79%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.79%   |
| Validity Sensors VFS491                                                    | 1         | 0.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 0.89%   |
| Synaptics WBDI Device                                                      | 1         | 0.89%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.89%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.89%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.89%   |
| AuthenTec AES1600                                                          | 1         | 0.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 20        | 52.63%  |
| Broadcom              | 13        | 34.21%  |
| Lenovo                | 2         | 5.26%   |
| Upek                  | 1         | 2.63%   |
| O2 Micro              | 1         | 2.63%   |
| Gemalto (was Gemplus) | 1         | 2.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 52.63%  |
| Broadcom 58200                                                               | 6         | 15.79%  |
| Broadcom 5880                                                                | 5         | 13.16%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.63%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.63%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.63%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 2.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 249       | 55.96%  |
| 1     | 170       | 38.2%   |
| 2     | 21        | 4.72%   |
| 3     | 3         | 0.67%   |
| 5     | 2         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 111       | 48.47%  |
| Graphics card            | 45        | 19.65%  |
| Multimedia controller    | 23        | 10.04%  |
| Camera                   | 17        | 7.42%   |
| Net/wireless             | 10        | 4.37%   |
| Card reader              | 7         | 3.06%   |
| Chipcard                 | 6         | 2.62%   |
| Net/ethernet             | 3         | 1.31%   |
| Sound                    | 2         | 0.87%   |
| Communication controller | 2         | 0.87%   |
| Bluetooth                | 2         | 0.87%   |
| Storage                  | 1         | 0.44%   |

