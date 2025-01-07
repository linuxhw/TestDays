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

Total: 659

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 7420               | [643874a1e2](https://linux-hardware.org/?probe=643874a1e2) | Jan 03, 2025 |
| Toshiba       | Satellite Pro S500          | [62a9b2c381](https://linux-hardware.org/?probe=62a9b2c381) | Jan 01, 2025 |
| Dell          | Inspiron 7420               | [f4cfceadf3](https://linux-hardware.org/?probe=f4cfceadf3) | Jan 01, 2025 |
| Lenovo        | ThinkPad T430 2347G2U       | [84d841764a](https://linux-hardware.org/?probe=84d841764a) | Dec 25, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [ba5d8c06f6](https://linux-hardware.org/?probe=ba5d8c06f6) | Dec 23, 2024 |
| Schenker      | XMG PRO 16 Studio (M24)     | [cb7a4908df](https://linux-hardware.org/?probe=cb7a4908df) | Dec 21, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [6461bf27f1](https://linux-hardware.org/?probe=6461bf27f1) | Dec 20, 2024 |
| HP            | Victus by Gaming Laptop ... | [d0585de2f5](https://linux-hardware.org/?probe=d0585de2f5) | Dec 18, 2024 |
| HP            | Victus by Gaming Laptop ... | [49259c4221](https://linux-hardware.org/?probe=49259c4221) | Dec 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e823717ef8](https://linux-hardware.org/?probe=e823717ef8) | Dec 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1c47a9e4d4](https://linux-hardware.org/?probe=1c47a9e4d4) | Dec 18, 2024 |
| HUAWEI        | NBD-WXX9                    | [627bafd258](https://linux-hardware.org/?probe=627bafd258) | Dec 15, 2024 |
| Samsung       | R530/R730                   | [995d2abd36](https://linux-hardware.org/?probe=995d2abd36) | Dec 14, 2024 |
| ASUSTek       | K501UB                      | [9bb21014e6](https://linux-hardware.org/?probe=9bb21014e6) | Dec 14, 2024 |
| Dell          | G15 5511                    | [fd366d5886](https://linux-hardware.org/?probe=fd366d5886) | Dec 12, 2024 |
| HP            | G62                         | [70f9d38537](https://linux-hardware.org/?probe=70f9d38537) | Dec 11, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [a8cdd032a9](https://linux-hardware.org/?probe=a8cdd032a9) | Dec 10, 2024 |
| Lenovo        | ThinkPad T440s 20ARS1EQ0... | [c4f09615ae](https://linux-hardware.org/?probe=c4f09615ae) | Dec 08, 2024 |
| HP            | Pavilion Laptop 15-cc1xx    | [8f790073ab](https://linux-hardware.org/?probe=8f790073ab) | Dec 07, 2024 |
| Google        | Delbin                      | [e761f97d94](https://linux-hardware.org/?probe=e761f97d94) | Dec 06, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [040113880f](https://linux-hardware.org/?probe=040113880f) | Dec 06, 2024 |
| Dell          | Latitude 5590               | [02ace3d15e](https://linux-hardware.org/?probe=02ace3d15e) | Dec 03, 2024 |
| Google        | Delbin                      | [0b18a9a18c](https://linux-hardware.org/?probe=0b18a9a18c) | Dec 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1cabb4b7bd](https://linux-hardware.org/?probe=1cabb4b7bd) | Dec 01, 2024 |
| HP            | Victus by Gaming Laptop ... | [be9e4b9467](https://linux-hardware.org/?probe=be9e4b9467) | Nov 29, 2024 |
| HP            | Victus by Gaming Laptop ... | [53747d81e3](https://linux-hardware.org/?probe=53747d81e3) | Nov 26, 2024 |
| Dell          | Latitude 5590               | [9249e52134](https://linux-hardware.org/?probe=9249e52134) | Nov 19, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cd51b4ca43](https://linux-hardware.org/?probe=cd51b4ca43) | Nov 18, 2024 |
| Dell          | Inspiron 3542               | [21d296d057](https://linux-hardware.org/?probe=21d296d057) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [92b243bc47](https://linux-hardware.org/?probe=92b243bc47) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1579ba23ea](https://linux-hardware.org/?probe=1579ba23ea) | Nov 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9497b471dc](https://linux-hardware.org/?probe=9497b471dc) | Nov 14, 2024 |
| Toshiba       | Satellite L755D             | [026c487fec](https://linux-hardware.org/?probe=026c487fec) | Nov 13, 2024 |
| Apple         | MacBookPro9,1               | [a41e7684ba](https://linux-hardware.org/?probe=a41e7684ba) | Nov 09, 2024 |
| Toshiba       | Satellite Pro L550          | [90ba079d9a](https://linux-hardware.org/?probe=90ba079d9a) | Nov 08, 2024 |
| Dynabook      | Satellite Pro C40-K         | [f8d851c4ec](https://linux-hardware.org/?probe=f8d851c4ec) | Nov 08, 2024 |
| Razer         | Blade 15 Advanced Model ... | [2d70625c33](https://linux-hardware.org/?probe=2d70625c33) | Nov 04, 2024 |
| Schenker      | SLIM14_SSL14L19             | [f7c0d965b7](https://linux-hardware.org/?probe=f7c0d965b7) | Nov 03, 2024 |
| Acer          | One 14 Z8-415               | [30bd329571](https://linux-hardware.org/?probe=30bd329571) | Nov 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6e52b4f65d](https://linux-hardware.org/?probe=6e52b4f65d) | Oct 31, 2024 |
| Schenker      | SLIM14_SSL14L19             | [fcf7985ef8](https://linux-hardware.org/?probe=fcf7985ef8) | Oct 31, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0ba3e2a6cf](https://linux-hardware.org/?probe=0ba3e2a6cf) | Oct 28, 2024 |
| Lenovo        | G50-30 80G0                 | [d0905f7bb9](https://linux-hardware.org/?probe=d0905f7bb9) | Oct 26, 2024 |
| ASUSTek       | K53E                        | [d27b0b2eee](https://linux-hardware.org/?probe=d27b0b2eee) | Oct 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [0d286dd3ac](https://linux-hardware.org/?probe=0d286dd3ac) | Oct 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9db5365bb8](https://linux-hardware.org/?probe=9db5365bb8) | Oct 20, 2024 |
| Google        | Drobit                      | [26edf296d3](https://linux-hardware.org/?probe=26edf296d3) | Oct 20, 2024 |
| Acer          | Nitro ANV15-41              | [c96376c69b](https://linux-hardware.org/?probe=c96376c69b) | Oct 13, 2024 |
| Dell          | Latitude 5490               | [968ebd0c22](https://linux-hardware.org/?probe=968ebd0c22) | Oct 11, 2024 |
| ASUSTek       | Strix GL704GW_GL704GW       | [2fca92d6b4](https://linux-hardware.org/?probe=2fca92d6b4) | Oct 11, 2024 |
| Dell          | Inspiron 7577               | [42d1b5a375](https://linux-hardware.org/?probe=42d1b5a375) | Oct 08, 2024 |
| HP            | ProBook 440 G2              | [fe177c4385](https://linux-hardware.org/?probe=fe177c4385) | Oct 07, 2024 |
| GPD           | G1618-04                    | [be67fe0e3e](https://linux-hardware.org/?probe=be67fe0e3e) | Sep 30, 2024 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [01fc4d5bf5](https://linux-hardware.org/?probe=01fc4d5bf5) | Sep 28, 2024 |
| Lenovo        | IdeaPad Z580                | [fb42cc4c6f](https://linux-hardware.org/?probe=fb42cc4c6f) | Sep 24, 2024 |
| Dell          | Inspiron 7577               | [ebda65fac2](https://linux-hardware.org/?probe=ebda65fac2) | Sep 23, 2024 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [99476c9cd3](https://linux-hardware.org/?probe=99476c9cd3) | Sep 23, 2024 |
| Avell High... | A62 LIV                     | [aa80a76284](https://linux-hardware.org/?probe=aa80a76284) | Sep 20, 2024 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [0975c90f12](https://linux-hardware.org/?probe=0975c90f12) | Sep 16, 2024 |
| Alienware     | 14                          | [c47b383fde](https://linux-hardware.org/?probe=c47b383fde) | Sep 13, 2024 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [da6201fca5](https://linux-hardware.org/?probe=da6201fca5) | Sep 11, 2024 |
| Alienware     | 14                          | [dda4311094](https://linux-hardware.org/?probe=dda4311094) | Sep 10, 2024 |
| MSI           | Summit E15 A11SCS           | [0de416afaf](https://linux-hardware.org/?probe=0de416afaf) | Sep 09, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [0abd493e22](https://linux-hardware.org/?probe=0abd493e22) | Sep 02, 2024 |
| Dell          | Inspiron 15 3525            | [4bc238278b](https://linux-hardware.org/?probe=4bc238278b) | Sep 01, 2024 |
| Avell High... | A62 LIV                     | [88cbf3c8bc](https://linux-hardware.org/?probe=88cbf3c8bc) | Aug 31, 2024 |
| Avell High... | A62 LIV                     | [11abb87f47](https://linux-hardware.org/?probe=11abb87f47) | Aug 31, 2024 |
| Dell          | Inspiron 15 3525            | [a9efa36c83](https://linux-hardware.org/?probe=a9efa36c83) | Aug 31, 2024 |
| Monster       | TULPAR T5 V23.2             | [9b4bf39bd8](https://linux-hardware.org/?probe=9b4bf39bd8) | Aug 25, 2024 |
| Acer          | Nitro AN515-43              | [21fa7cdf8b](https://linux-hardware.org/?probe=21fa7cdf8b) | Aug 25, 2024 |
| Apple         | MacBookPro15,1              | [18ccfcabb6](https://linux-hardware.org/?probe=18ccfcabb6) | Aug 25, 2024 |
| Dell          | Latitude E7440              | [6cddb30ec0](https://linux-hardware.org/?probe=6cddb30ec0) | Aug 24, 2024 |
| Dell          | Latitude E7440              | [bda506fc26](https://linux-hardware.org/?probe=bda506fc26) | Aug 24, 2024 |
| Alienware     | 17 R4                       | [4607e5603d](https://linux-hardware.org/?probe=4607e5603d) | Aug 24, 2024 |
| Lenovo        | ThinkPad T430 2349RQ3       | [344514d748](https://linux-hardware.org/?probe=344514d748) | Aug 23, 2024 |
| MSI           | GS66 Stealth 10UG           | [e1bd6aa8e1](https://linux-hardware.org/?probe=e1bd6aa8e1) | Aug 23, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [b8416663f7](https://linux-hardware.org/?probe=b8416663f7) | Aug 16, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [3e797134f0](https://linux-hardware.org/?probe=3e797134f0) | Aug 16, 2024 |
| Unknown       | Unknown                     | [a627eeb394](https://linux-hardware.org/?probe=a627eeb394) | Aug 13, 2024 |
| Avell High... | A62 LIV                     | [89892c500e](https://linux-hardware.org/?probe=89892c500e) | Aug 13, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ed0cfaf91b](https://linux-hardware.org/?probe=ed0cfaf91b) | Aug 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4bbef13098](https://linux-hardware.org/?probe=4bbef13098) | Aug 08, 2024 |
| Samsung       | R530/R730                   | [a67ee0342f](https://linux-hardware.org/?probe=a67ee0342f) | Aug 04, 2024 |
| GPD           | G1618-04                    | [c6aefccb2c](https://linux-hardware.org/?probe=c6aefccb2c) | Jul 27, 2024 |
| Valve         | Galileo                     | [79a07fcefb](https://linux-hardware.org/?probe=79a07fcefb) | Jul 26, 2024 |
| Lenovo        | ThinkPad P71 20HLS0UE00     | [400120df7a](https://linux-hardware.org/?probe=400120df7a) | Jul 25, 2024 |
| Dell          | Precision 7710              | [b0ff7b315d](https://linux-hardware.org/?probe=b0ff7b315d) | Jul 23, 2024 |
| Dell          | Precision 7520              | [ab03c13aca](https://linux-hardware.org/?probe=ab03c13aca) | Jul 23, 2024 |
| Dell          | Precision 7710              | [eaaefe2324](https://linux-hardware.org/?probe=eaaefe2324) | Jul 23, 2024 |
| GPU Compan... | GWNC214H34-SL               | [f6c5223f36](https://linux-hardware.org/?probe=f6c5223f36) | Jul 12, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0837d07786](https://linux-hardware.org/?probe=0837d07786) | Jul 11, 2024 |
| Lenovo        | ThinkPad T460s 20F90060G... | [24c071c2e6](https://linux-hardware.org/?probe=24c071c2e6) | Jul 10, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [0a9be595b1](https://linux-hardware.org/?probe=0a9be595b1) | Jul 09, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [e81695264a](https://linux-hardware.org/?probe=e81695264a) | Jul 09, 2024 |
| HP            | Laptop 15-da0xxx            | [60c0248abc](https://linux-hardware.org/?probe=60c0248abc) | Jul 04, 2024 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [313df6e324](https://linux-hardware.org/?probe=313df6e324) | Jun 29, 2024 |
| Notebook      | P640RE                      | [e191099edb](https://linux-hardware.org/?probe=e191099edb) | Jun 24, 2024 |
| MSI           | GP66 Leopard 10UG           | [c50af3b6c8](https://linux-hardware.org/?probe=c50af3b6c8) | Jun 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [869129230d](https://linux-hardware.org/?probe=869129230d) | Jun 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [ba2fcdc6b1](https://linux-hardware.org/?probe=ba2fcdc6b1) | Jun 20, 2024 |
| Fujitsu       | LIFEBOOK U7511              | [e3ecabe043](https://linux-hardware.org/?probe=e3ecabe043) | Jun 19, 2024 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [f33e866e3a](https://linux-hardware.org/?probe=f33e866e3a) | Jun 19, 2024 |
| HP            | Laptop 15-ef0xxx            | [1e8aa7a77f](https://linux-hardware.org/?probe=1e8aa7a77f) | Jun 18, 2024 |
| Dell          | Precision 5690              | [924b1ece6c](https://linux-hardware.org/?probe=924b1ece6c) | Jun 12, 2024 |
| PEAQ          | PNB P1115 MD99343           | [4e29fc0839](https://linux-hardware.org/?probe=4e29fc0839) | Jun 09, 2024 |
| Samsung       | R530/R730                   | [e9d3fc4719](https://linux-hardware.org/?probe=e9d3fc4719) | Jun 08, 2024 |
| HUAWEI        | BOM-WXX9                    | [e7e349c28e](https://linux-hardware.org/?probe=e7e349c28e) | Jun 07, 2024 |
| HUAWEI        | BOM-WXX9                    | [3c0ef8ae3f](https://linux-hardware.org/?probe=3c0ef8ae3f) | Jun 07, 2024 |
| MSI           | GL73 8RD                    | [232fab6257](https://linux-hardware.org/?probe=232fab6257) | Jun 07, 2024 |
| Gigabyte      | B450M K-CF                  | [0cb44e20e0](https://linux-hardware.org/?probe=0cb44e20e0) | Jun 06, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [9c2659e775](https://linux-hardware.org/?probe=9c2659e775) | May 28, 2024 |
| MSI           | GE66 Raider 10SFS           | [a6443b3b74](https://linux-hardware.org/?probe=a6443b3b74) | May 24, 2024 |
| Dell          | G15 Special Edition 5521    | [5bb64a1498](https://linux-hardware.org/?probe=5bb64a1498) | May 23, 2024 |
| Dell          | G15 Special Edition 5521    | [47bfbd5ead](https://linux-hardware.org/?probe=47bfbd5ead) | May 21, 2024 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [7cfed3af06](https://linux-hardware.org/?probe=7cfed3af06) | May 21, 2024 |
| Razer         | Blade 16 - RZ09-0510        | [965dc14fc2](https://linux-hardware.org/?probe=965dc14fc2) | May 20, 2024 |
| Acer          | Swift SF113-31              | [afefc4eb75](https://linux-hardware.org/?probe=afefc4eb75) | May 18, 2024 |
| Dell          | Latitude 5490               | [65385e527b](https://linux-hardware.org/?probe=65385e527b) | May 18, 2024 |
| Dell          | Latitude 5490               | [dcccf62ee8](https://linux-hardware.org/?probe=dcccf62ee8) | May 18, 2024 |
| MSI           | Modern 15 H B13M            | [f9839d0180](https://linux-hardware.org/?probe=f9839d0180) | May 17, 2024 |
| Casper        | EXCALIBUR G770              | [06a25f526f](https://linux-hardware.org/?probe=06a25f526f) | May 14, 2024 |
| Dell          | Latitude E6430              | [a145a37354](https://linux-hardware.org/?probe=a145a37354) | May 14, 2024 |
| Casper        | EXCALIBUR G770              | [b092716b6a](https://linux-hardware.org/?probe=b092716b6a) | May 12, 2024 |
| Dell          | G15 Special Edition 5521    | [6ac404598d](https://linux-hardware.org/?probe=6ac404598d) | May 12, 2024 |
| Acer          | Aspire A315-24P             | [4e002660a0](https://linux-hardware.org/?probe=4e002660a0) | May 10, 2024 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [4b77160a0a](https://linux-hardware.org/?probe=4b77160a0a) | May 09, 2024 |
| MSI           | Alpha 17 B5EEK              | [8f78e61ba3](https://linux-hardware.org/?probe=8f78e61ba3) | May 06, 2024 |
| MSI           | Alpha 17 B5EEK              | [38d719b3cc](https://linux-hardware.org/?probe=38d719b3cc) | May 05, 2024 |
| Dell          | G5 5590                     | [b32e4a3fcc](https://linux-hardware.org/?probe=b32e4a3fcc) | May 03, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2ffec4cb68](https://linux-hardware.org/?probe=2ffec4cb68) | Apr 29, 2024 |
| Timi          | Redmi G 2022                | [42d8e2e055](https://linux-hardware.org/?probe=42d8e2e055) | Apr 28, 2024 |
| MSI           | Stealth 15M B12UE           | [5a6ea85213](https://linux-hardware.org/?probe=5a6ea85213) | Apr 28, 2024 |
| HP            | Pavilion Notebook           | [baeaf7e578](https://linux-hardware.org/?probe=baeaf7e578) | Apr 26, 2024 |
| HP            | EliteBook 745 G2            | [3386466743](https://linux-hardware.org/?probe=3386466743) | Apr 25, 2024 |
| HP            | Laptop 17-cn0xxx            | [f9b7f5d81b](https://linux-hardware.org/?probe=f9b7f5d81b) | Apr 21, 2024 |
| HP            | Laptop 17-cn0xxx            | [6f3c85173f](https://linux-hardware.org/?probe=6f3c85173f) | Apr 20, 2024 |
| MSI           | P65 Creator 8SF             | [4765243dd1](https://linux-hardware.org/?probe=4765243dd1) | Apr 17, 2024 |
| Dell          | Inspiron 7737               | [1f91e64679](https://linux-hardware.org/?probe=1f91e64679) | Apr 17, 2024 |
| Dell          | Inspiron 7737               | [361844ede0](https://linux-hardware.org/?probe=361844ede0) | Apr 17, 2024 |
| MSI           | Stealth GS77 12UE           | [47ff584537](https://linux-hardware.org/?probe=47ff584537) | Apr 14, 2024 |
| Notebook      | P7xxDM2(-G)                 | [ee5809d062](https://linux-hardware.org/?probe=ee5809d062) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48f3d584f3](https://linux-hardware.org/?probe=48f3d584f3) | Apr 09, 2024 |
| MSI           | Stealth 15M B12UE           | [041874d8e0](https://linux-hardware.org/?probe=041874d8e0) | Apr 08, 2024 |
| Lenovo        | ThinkPad T430 2349RQ3       | [6988a75b14](https://linux-hardware.org/?probe=6988a75b14) | Apr 05, 2024 |
| HP            | EliteBook 745 G2            | [8d1226791a](https://linux-hardware.org/?probe=8d1226791a) | Mar 29, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [b1ff4c1ab1](https://linux-hardware.org/?probe=b1ff4c1ab1) | Mar 28, 2024 |
| Dell          | Precision 5540              | [e36c4c65ab](https://linux-hardware.org/?probe=e36c4c65ab) | Mar 26, 2024 |
| MSI           | P65 Creator 8SF             | [2ac35fb5df](https://linux-hardware.org/?probe=2ac35fb5df) | Mar 24, 2024 |
| HP            | Laptop 15-fc0xxx            | [45f2251b48](https://linux-hardware.org/?probe=45f2251b48) | Mar 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [2f1a34dcc7](https://linux-hardware.org/?probe=2f1a34dcc7) | Mar 17, 2024 |
| Lenovo        | ThinkPad X230 23249Q2       | [53750d45df](https://linux-hardware.org/?probe=53750d45df) | Mar 16, 2024 |
| HP            | Laptop 15-da1xxx            | [decbe9d726](https://linux-hardware.org/?probe=decbe9d726) | Mar 14, 2024 |
| GPD           | G1621-02                    | [382319d2bd](https://linux-hardware.org/?probe=382319d2bd) | Mar 13, 2024 |
| MSI           | Stealth 15M B12UE           | [a731c5f5eb](https://linux-hardware.org/?probe=a731c5f5eb) | Mar 13, 2024 |
| Apple         | MacBookAir6,1               | [de3cdad359](https://linux-hardware.org/?probe=de3cdad359) | Mar 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [92a2bca1a2](https://linux-hardware.org/?probe=92a2bca1a2) | Mar 08, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [386945e586](https://linux-hardware.org/?probe=386945e586) | Mar 07, 2024 |
| MSI           | Stealth 15M B12UE           | [59afccdc44](https://linux-hardware.org/?probe=59afccdc44) | Feb 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a71e9dba32](https://linux-hardware.org/?probe=a71e9dba32) | Feb 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e8bc13baa1](https://linux-hardware.org/?probe=e8bc13baa1) | Feb 25, 2024 |
| Lenovo        | Y520-15IKBM 80YY            | [c8de9e7dd7](https://linux-hardware.org/?probe=c8de9e7dd7) | Feb 25, 2024 |
| HP            | EliteBook 8560w             | [ea3d798358](https://linux-hardware.org/?probe=ea3d798358) | Feb 25, 2024 |
| HP            | EliteBook 8560w             | [d3a04fdf22](https://linux-hardware.org/?probe=d3a04fdf22) | Feb 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3a64f7e0a5](https://linux-hardware.org/?probe=3a64f7e0a5) | Feb 22, 2024 |
| Apple         | MacBookPro13,3              | [f6a0a37d75](https://linux-hardware.org/?probe=f6a0a37d75) | Feb 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4d44c78868](https://linux-hardware.org/?probe=4d44c78868) | Feb 15, 2024 |
| TECNO         | MEGABOOK T1                 | [33fe01408f](https://linux-hardware.org/?probe=33fe01408f) | Feb 14, 2024 |
| AZW           | GT-R                        | [d40b69a73e](https://linux-hardware.org/?probe=d40b69a73e) | Feb 13, 2024 |
| Apple         | MacBookPro11,1              | [9a6d21a18d](https://linux-hardware.org/?probe=9a6d21a18d) | Feb 10, 2024 |
| Dell          | Vostro 3580                 | [1d2758029b](https://linux-hardware.org/?probe=1d2758029b) | Feb 08, 2024 |
| Dell          | Vostro 3580                 | [0b028612c5](https://linux-hardware.org/?probe=0b028612c5) | Feb 08, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1ef50cb52c](https://linux-hardware.org/?probe=1ef50cb52c) | Feb 05, 2024 |
| Dell          | Inspiron 5759               | [b1fd1650b7](https://linux-hardware.org/?probe=b1fd1650b7) | Feb 04, 2024 |
| Acer          | Nitro AN515-54              | [a8ba2aabd5](https://linux-hardware.org/?probe=a8ba2aabd5) | Feb 04, 2024 |
| MSI           | Stealth 15M B12UE           | [b5d23740cc](https://linux-hardware.org/?probe=b5d23740cc) | Feb 04, 2024 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [cf1e9cdc22](https://linux-hardware.org/?probe=cf1e9cdc22) | Feb 03, 2024 |
| Acer          | Aspire A515-43              | [349b53e55a](https://linux-hardware.org/?probe=349b53e55a) | Feb 02, 2024 |
| Acer          | Predator PH317-53           | [4b8b265f8c](https://linux-hardware.org/?probe=4b8b265f8c) | Jan 23, 2024 |
| OriginPC      | EVO17-S                     | [085e0b26d0](https://linux-hardware.org/?probe=085e0b26d0) | Jan 21, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [217209efeb](https://linux-hardware.org/?probe=217209efeb) | Jan 18, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [12d61689c2](https://linux-hardware.org/?probe=12d61689c2) | Jan 18, 2024 |
| MSI           | Stealth 15M B12UE           | [64561711ef](https://linux-hardware.org/?probe=64561711ef) | Jan 18, 2024 |
| Apple         | MacBookPro9,2               | [a8557f8a49](https://linux-hardware.org/?probe=a8557f8a49) | Jan 17, 2024 |
| Razer         | Blade                       | [8bfee68ead](https://linux-hardware.org/?probe=8bfee68ead) | Jan 10, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1e21573b13](https://linux-hardware.org/?probe=1e21573b13) | Jan 05, 2024 |
| HP            | Laptop 15-dw0xxx            | [b732d30db5](https://linux-hardware.org/?probe=b732d30db5) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | [43bc3cd4bd](https://linux-hardware.org/?probe=43bc3cd4bd) | Jan 02, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [5cde8dcd78](https://linux-hardware.org/?probe=5cde8dcd78) | Jan 01, 2024 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [8ec110334b](https://linux-hardware.org/?probe=8ec110334b) | Dec 27, 2023 |
| Dell          | Latitude 5420               | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| Lenovo        | ThinkPad T500 20828WG       | [a3edf5e69b](https://linux-hardware.org/?probe=a3edf5e69b) | Dec 26, 2023 |
| Acer          | Aspire V3-571               | [0819197709](https://linux-hardware.org/?probe=0819197709) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [41256541b5](https://linux-hardware.org/?probe=41256541b5) | Dec 21, 2023 |
| Lenovo        | V14-ADA 82C6                | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | [1bd33b2c6b](https://linux-hardware.org/?probe=1bd33b2c6b) | Dec 18, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [30fc775598](https://linux-hardware.org/?probe=30fc775598) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [19d43a41f8](https://linux-hardware.org/?probe=19d43a41f8) | Dec 17, 2023 |
| HC            | HCAR357-MI                  | [daaf3e0f5f](https://linux-hardware.org/?probe=daaf3e0f5f) | Dec 12, 2023 |
| HUAWEI        | KLVC-WXX9                   | [3e8d09cc67](https://linux-hardware.org/?probe=3e8d09cc67) | Dec 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c6f72287f3](https://linux-hardware.org/?probe=c6f72287f3) | Dec 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [afd68e777f](https://linux-hardware.org/?probe=afd68e777f) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [9a8395654c](https://linux-hardware.org/?probe=9a8395654c) | Dec 06, 2023 |
| HP            | ProBook 450 G4              | [a41eb50b0e](https://linux-hardware.org/?probe=a41eb50b0e) | Dec 04, 2023 |
| Dell          | Inspiron 17-7779            | [16c9e2b55c](https://linux-hardware.org/?probe=16c9e2b55c) | Dec 04, 2023 |
| Dell          | Inspiron 5515               | [e099b86288](https://linux-hardware.org/?probe=e099b86288) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [cf6dd1eb40](https://linux-hardware.org/?probe=cf6dd1eb40) | Dec 01, 2023 |
| Samsung       | R530/R730                   | [d307e11a95](https://linux-hardware.org/?probe=d307e11a95) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3aa5e4bed1](https://linux-hardware.org/?probe=3aa5e4bed1) | Nov 30, 2023 |
| Dell          | Vostro 3583                 | [68c6f002f5](https://linux-hardware.org/?probe=68c6f002f5) | Nov 28, 2023 |
| Acer          | Nitro AN515-58              | [2ddc688d1d](https://linux-hardware.org/?probe=2ddc688d1d) | Nov 28, 2023 |
| HP            | Laptop 14-dk0xxx            | [9e97507512](https://linux-hardware.org/?probe=9e97507512) | Nov 27, 2023 |
| Lenovo        | G50-30 80G0                 | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Dell          | Latitude E5520              | [7c773e173a](https://linux-hardware.org/?probe=7c773e173a) | Nov 21, 2023 |
| HP            | ZBook 15                    | [7959bd4b85](https://linux-hardware.org/?probe=7959bd4b85) | Nov 18, 2023 |
| Dell          | Vostro 3583                 | [4ddc04a5ba](https://linux-hardware.org/?probe=4ddc04a5ba) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0fe7515de5](https://linux-hardware.org/?probe=0fe7515de5) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | [6bf67ac977](https://linux-hardware.org/?probe=6bf67ac977) | Nov 15, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [3567b57191](https://linux-hardware.org/?probe=3567b57191) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [197a03d08f](https://linux-hardware.org/?probe=197a03d08f) | Nov 12, 2023 |
| Samsung       | R530/R730                   | [e1177626c4](https://linux-hardware.org/?probe=e1177626c4) | Nov 11, 2023 |
| HP            | Laptop 15-ef2xxx            | [dd143f192c](https://linux-hardware.org/?probe=dd143f192c) | Nov 06, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| Dell          | Inspiron 3521               | [cdda6b5094](https://linux-hardware.org/?probe=cdda6b5094) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | [5bec5815bb](https://linux-hardware.org/?probe=5bec5815bb) | Oct 31, 2023 |
| Acer          | Predator PH317-51           | [941e333a3b](https://linux-hardware.org/?probe=941e333a3b) | Oct 27, 2023 |
| HP            | EliteBook 820 G1            | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [817367d444](https://linux-hardware.org/?probe=817367d444) | Oct 23, 2023 |
| HP            | EliteBook 820 G1            | [959fc54e2b](https://linux-hardware.org/?probe=959fc54e2b) | Oct 23, 2023 |
| Lenovo        | ThinkPad T460s 20F90060G... | [b44ed99aff](https://linux-hardware.org/?probe=b44ed99aff) | Oct 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [2079534fd9](https://linux-hardware.org/?probe=2079534fd9) | Oct 18, 2023 |
| Acer          | Aspire A715-42G             | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| Apple         | MacBookPro9,2               | [4b5b669131](https://linux-hardware.org/?probe=4b5b669131) | Oct 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [be6e7011cc](https://linux-hardware.org/?probe=be6e7011cc) | Oct 11, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [bc5016980d](https://linux-hardware.org/?probe=bc5016980d) | Oct 10, 2023 |
| HP            | Laptop 15-ef2xxx            | [ad00ca7536](https://linux-hardware.org/?probe=ad00ca7536) | Oct 07, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [e7906b9cd7](https://linux-hardware.org/?probe=e7906b9cd7) | Oct 04, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [1c7bef5950](https://linux-hardware.org/?probe=1c7bef5950) | Oct 04, 2023 |
| Acer          | Aspire A515-56              | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| AMI           | Intel                       | [ebb3577023](https://linux-hardware.org/?probe=ebb3577023) | Sep 23, 2023 |
| ASUSTek       | X455LD                      | [1e79e3536c](https://linux-hardware.org/?probe=1e79e3536c) | Sep 20, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| MSI           | Stealth 14Studio A13VE      | [e57ab86521](https://linux-hardware.org/?probe=e57ab86521) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [78ddadfb89](https://linux-hardware.org/?probe=78ddadfb89) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [3145861387](https://linux-hardware.org/?probe=3145861387) | Sep 12, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| Matsushita... | CF-74JCJBDAM                | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Unknown       | Unknown                     | [9441e027c6](https://linux-hardware.org/?probe=9441e027c6) | Sep 04, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3b0d2983a6](https://linux-hardware.org/?probe=3b0d2983a6) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [10951f0a65](https://linux-hardware.org/?probe=10951f0a65) | Sep 01, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [ac6c5c8969](https://linux-hardware.org/?probe=ac6c5c8969) | Sep 01, 2023 |
| MOTION        | NVX00                       | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| HP            | Laptop 15-da0xxx            | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5d571876c8](https://linux-hardware.org/?probe=5d571876c8) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2f4fd95449](https://linux-hardware.org/?probe=2f4fd95449) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Lenovo        | ThinkPad T61 7661ZSF        | [2a461c159d](https://linux-hardware.org/?probe=2a461c159d) | Aug 18, 2023 |
| ASUSTek       | GL552VW                     | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| Acer          | Nitro AN517-54              | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| HP            | Laptop 14-dq1xxx            | [68fff65eee](https://linux-hardware.org/?probe=68fff65eee) | Aug 10, 2023 |
| HP            | Laptop 14-dq1xxx            | [81a2d0415e](https://linux-hardware.org/?probe=81a2d0415e) | Aug 10, 2023 |
| Dell          | Precision 5530              | [3b10bebb7d](https://linux-hardware.org/?probe=3b10bebb7d) | Aug 10, 2023 |
| Apple         | MacBookPro9,1               | [65343a7900](https://linux-hardware.org/?probe=65343a7900) | Aug 06, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| HP            | Laptop 14-dq1xxx            | [4d98867c44](https://linux-hardware.org/?probe=4d98867c44) | Aug 02, 2023 |
| HP            | Laptop 14-dq1xxx            | [675811747f](https://linux-hardware.org/?probe=675811747f) | Aug 02, 2023 |
| Apple         | MacBookPro8,2               | [ba2cec8099](https://linux-hardware.org/?probe=ba2cec8099) | Aug 01, 2023 |
| HP            | Dev One Notebook PC         | [cdbcf58dcb](https://linux-hardware.org/?probe=cdbcf58dcb) | Jul 30, 2023 |
| HP            | ENVY Notebook               | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | [2dbda5ea48](https://linux-hardware.org/?probe=2dbda5ea48) | Jul 29, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| Alienware     | 13 R3                       | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [5d2c798252](https://linux-hardware.org/?probe=5d2c798252) | Jul 21, 2023 |
| ASUSTek       | GL502VM                     | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | [79ab32a714](https://linux-hardware.org/?probe=79ab32a714) | Jul 17, 2023 |
| Apple         | MacBookPro9,2               | [228fca7e43](https://linux-hardware.org/?probe=228fca7e43) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [047aac4298](https://linux-hardware.org/?probe=047aac4298) | Jun 25, 2023 |
| Notebook      | P870DM                      | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Apple         | MacBookPro11,2              | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| HUAWEI        | MACH-WX9                    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| Dell          | Latitude E6510              | [f3e9e3bbf1](https://linux-hardware.org/?probe=f3e9e3bbf1) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | [29d4909dd4](https://linux-hardware.org/?probe=29d4909dd4) | Jun 12, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| Apple         | MacBookPro14,1              | [f73406fa5d](https://linux-hardware.org/?probe=f73406fa5d) | Jun 04, 2023 |
| Apple         | MacBookPro14,1              | [1c2d6e0e5e](https://linux-hardware.org/?probe=1c2d6e0e5e) | Jun 04, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Notebook                    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Dell          | Precision 5520              | [c7097157ab](https://linux-hardware.org/?probe=c7097157ab) | May 28, 2023 |
| Apple         | MacBookPro9,2               | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| MICROBYTE     | ezbook                      | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| Acer          | Extensa 215-52              | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| Gigabyte      | G5 MD                       | [ad5fd46d55](https://linux-hardware.org/?probe=ad5fd46d55) | May 14, 2023 |
| HP            | OMEN by Laptop              | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| Acer          | Aspire 5750G                | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| MSI           | GL75 9SD                    | [522594401b](https://linux-hardware.org/?probe=522594401b) | May 07, 2023 |
| Acer          | Extensa 215-52              | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Lenovo        | ThinkPad W520 42824UU       | [c8474ef15e](https://linux-hardware.org/?probe=c8474ef15e) | May 01, 2023 |
| Monster       | TULPAR T5 V21.7             | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| Apple         | MacBookPro9,2               | [f48b78bda1](https://linux-hardware.org/?probe=f48b78bda1) | Apr 23, 2023 |
| MSI           | Stealth 15M B12UE           | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [a76057a8be](https://linux-hardware.org/?probe=a76057a8be) | Apr 19, 2023 |
| Sony          | SVF1521Q1EW                 | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| HUAWEI        | HVY-WXX9                    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| HP            | Pavilion 15                 | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [946646a961](https://linux-hardware.org/?probe=946646a961) | Mar 22, 2023 |
| HP            | EliteBook 8560w             | [f886dec5e7](https://linux-hardware.org/?probe=f886dec5e7) | Mar 22, 2023 |
| HP            | ZBook 15 G5                 | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Samsung       | R530/R730                   | [9cd7e18a6d](https://linux-hardware.org/?probe=9cd7e18a6d) | Mar 21, 2023 |
| Samsung       | R530/R730                   | [87292d633d](https://linux-hardware.org/?probe=87292d633d) | Mar 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [e0317127ea](https://linux-hardware.org/?probe=e0317127ea) | Mar 20, 2023 |
| HP            | EliteBook 8560w             | [da8abe8a8e](https://linux-hardware.org/?probe=da8abe8a8e) | Mar 19, 2023 |
| ASUSTek       | GL753VE                     | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Gigabyte      | G5 KD                       | [a3234542a9](https://linux-hardware.org/?probe=a3234542a9) | Mar 17, 2023 |
| HP            | EliteBook 8560w             | [8bab1523ae](https://linux-hardware.org/?probe=8bab1523ae) | Mar 16, 2023 |
| HP            | EliteBook 8560w             | [02015c3c38](https://linux-hardware.org/?probe=02015c3c38) | Mar 15, 2023 |
| Lenovo        | V15-IIL 82C5                | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Acer          | Aspire A515-46              | [f43d0b8fa2](https://linux-hardware.org/?probe=f43d0b8fa2) | Mar 06, 2023 |
| Acer          | Aspire E5-575G              | [b2fa34d832](https://linux-hardware.org/?probe=b2fa34d832) | Feb 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| HP            | Unknown                     | [06f5e98fdd](https://linux-hardware.org/?probe=06f5e98fdd) | Feb 20, 2023 |
| MSI           | GE75 Raider 9SE             | [0cf7067e58](https://linux-hardware.org/?probe=0cf7067e58) | Feb 18, 2023 |
| Dell          | Precision 7710              | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| MobileDema... | xTablet T1200               | [905b6efd7a](https://linux-hardware.org/?probe=905b6efd7a) | Feb 12, 2023 |
| Acer          | Aspire A715-41G             | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [59271934a3](https://linux-hardware.org/?probe=59271934a3) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 8560w             | [5140856482](https://linux-hardware.org/?probe=5140856482) | Feb 06, 2023 |
| HP            | EliteBook 8560w             | [62c1d53a4a](https://linux-hardware.org/?probe=62c1d53a4a) | Feb 06, 2023 |
| HP            | Unknown                     | [b1dacc0d29](https://linux-hardware.org/?probe=b1dacc0d29) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | [2c6c4d9777](https://linux-hardware.org/?probe=2c6c4d9777) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | [683f389938](https://linux-hardware.org/?probe=683f389938) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Garuda_Linux/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 285       | 62.78%  |
| Garuda Linux Rolling | 123       | 27.09%  |
| Garuda Linux         | 46        | 10.13%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Garuda Linux | 446       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 6.12.4-zen1-1-zen  | 9         | 1.76%   |
| 6.1.1-zen1-1-zen   | 8         | 1.56%   |
| 6.0.2-zen1-1-zen   | 8         | 1.56%   |
| 6.5.9-zen2-1-zen   | 7         | 1.37%   |
| 6.10.6-zen1-1-zen  | 7         | 1.37%   |
| 6.4.12-zen1-1-zen  | 6         | 1.17%   |
| 6.2.13-zen-1-zen   | 6         | 1.17%   |
| 6.11.5-zen1-1-zen  | 6         | 1.17%   |
| 5.17.9-zen1-1-zen  | 6         | 1.17%   |
| 6.9.5-zen1-1-zen   | 5         | 0.98%   |
| 6.9.3-zen1-1-zen   | 5         | 0.98%   |
| 6.8.9-zen1-2-zen   | 5         | 0.98%   |
| 6.6.8-zen1-1-zen   | 5         | 0.98%   |
| 6.11.8-zen1-2-zen  | 5         | 0.98%   |
| 6.11.6-zen1-1-zen  | 5         | 0.98%   |
| 6.10.10-zen1-1-zen | 5         | 0.98%   |
| 6.9.8-zen1-1-zen   | 4         | 0.78%   |
| 6.8.4-zen1-1-zen   | 4         | 0.78%   |
| 6.8.1-zen1-1-zen   | 4         | 0.78%   |
| 6.7.0-zen3-1-zen   | 4         | 0.78%   |
| 6.6.2-zen1-1-zen   | 4         | 0.78%   |
| 6.4.11-zen2-1-zen  | 4         | 0.78%   |
| 6.1.7-zen1-1-zen   | 4         | 0.78%   |
| 6.0.9-zen1-1-zen   | 4         | 0.78%   |
| 6.0.10-zen2-1-zen  | 4         | 0.78%   |
| 5.16.16-zen1-1-zen | 4         | 0.78%   |
| 5.14.14-zen1-1-zen | 4         | 0.78%   |
| 5.13.13-zen1-1-zen | 4         | 0.78%   |
| 6.8.7-zen1-2-zen   | 3         | 0.59%   |
| 6.7.6-zen1-1-zen   | 3         | 0.59%   |
| 6.6.7-zen1-1-zen   | 3         | 0.59%   |
| 6.6.3-zen1-1-zen   | 3         | 0.59%   |
| 6.6.1-zen1-1-zen   | 3         | 0.59%   |
| 6.5.3-zen1-1-zen   | 3         | 0.59%   |
| 6.4.8-zen1-1-zen   | 3         | 0.59%   |
| 6.3.8-zen1-1-zen   | 3         | 0.59%   |
| 6.2.12-zen1-1-zen  | 3         | 0.59%   |
| 6.11.2-zen1-1-zen  | 3         | 0.59%   |
| 6.10.8-zen1-1-zen  | 3         | 0.59%   |
| 6.1.11-zen1-1-zen  | 3         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.12.4  | 10        | 1.95%   |
| 6.0.2   | 9         | 1.76%   |
| 6.8.9   | 8         | 1.56%   |
| 6.5.9   | 8         | 1.56%   |
| 6.1.1   | 8         | 1.56%   |
| 6.10.6  | 7         | 1.37%   |
| 6.9.3   | 6         | 1.17%   |
| 6.8.7   | 6         | 1.17%   |
| 6.6.8   | 6         | 1.17%   |
| 6.4.12  | 6         | 1.17%   |
| 6.2.13  | 6         | 1.17%   |
| 6.11.5  | 6         | 1.17%   |
| 5.17.9  | 6         | 1.17%   |
| 6.9.5   | 5         | 0.98%   |
| 6.11.8  | 5         | 0.98%   |
| 6.11.6  | 5         | 0.98%   |
| 6.10.10 | 5         | 0.98%   |
| 6.1.9   | 5         | 0.98%   |
| 6.0.10  | 5         | 0.98%   |
| 6.9.8   | 4         | 0.78%   |
| 6.8.4   | 4         | 0.78%   |
| 6.8.1   | 4         | 0.78%   |
| 6.7.0   | 4         | 0.78%   |
| 6.6.3   | 4         | 0.78%   |
| 6.6.2   | 4         | 0.78%   |
| 6.6.1   | 4         | 0.78%   |
| 6.4.11  | 4         | 0.78%   |
| 6.3.1   | 4         | 0.78%   |
| 6.1.7   | 4         | 0.78%   |
| 6.0.9   | 4         | 0.78%   |
| 6.0.8   | 4         | 0.78%   |
| 5.19.7  | 4         | 0.78%   |
| 5.18.16 | 4         | 0.78%   |
| 5.17.3  | 4         | 0.78%   |
| 5.17.1  | 4         | 0.78%   |
| 5.16.16 | 4         | 0.78%   |
| 5.14.14 | 4         | 0.78%   |
| 5.13.13 | 4         | 0.78%   |
| 5.11.11 | 4         | 0.78%   |
| 6.9.0   | 3         | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 35        | 7.01%   |
| 6.1     | 32        | 6.41%   |
| 5.15    | 32        | 6.41%   |
| 6.0     | 31        | 6.21%   |
| 6.9     | 26        | 5.21%   |
| 6.8     | 26        | 5.21%   |
| 6.11    | 24        | 4.81%   |
| 6.4     | 23        | 4.61%   |
| 6.2     | 23        | 4.61%   |
| 6.10    | 22        | 4.41%   |
| 5.19    | 22        | 4.41%   |
| 5.16    | 21        | 4.21%   |
| 5.10    | 20        | 4.01%   |
| 6.5     | 19        | 3.81%   |
| 5.14    | 19        | 3.81%   |
| 6.7     | 18        | 3.61%   |
| 5.18    | 18        | 3.61%   |
| 5.17    | 18        | 3.61%   |
| 6.12    | 16        | 3.21%   |
| 6.3     | 13        | 2.61%   |
| 5.12    | 12        | 2.4%    |
| 5.11    | 12        | 2.4%    |
| 5.13    | 11        | 2.2%    |
| 5.9     | 4         | 0.8%    |
| 5.6     | 1         | 0.2%    |
| 5.4     | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 446       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 240       | 52.17%  |
| KDE6              | 75        | 16.3%   |
| GNOME             | 51        | 11.09%  |
| XFCE              | 24        | 5.22%   |
| KDE               | 23        | 5%      |
| X-Cinnamon        | 13        | 2.83%   |
| sway              | 9         | 1.96%   |
| Hyprland          | 4         | 0.87%   |
| Deepin            | 4         | 0.87%   |
| qtile-default     | 3         | 0.65%   |
| Cinnamon          | 3         | 0.65%   |
| qtile             | 2         | 0.43%   |
| i3                | 2         | 0.43%   |
| Unknown           | 2         | 0.43%   |
| Yaru:ubuntu:GNOME | 1         | 0.22%   |
| Unity             | 1         | 0.22%   |
| MATE              | 1         | 0.22%   |
| LXQt              | 1         | 0.22%   |
| awesome           | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 314       | 69.16%  |
| Wayland | 129       | 28.41%  |
| Unknown | 7         | 1.54%   |
| Tty     | 4         | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 208       | 45.81%  |
| Unknown | 170       | 37.44%  |
| LightDM | 36        | 7.93%   |
| GDM     | 34        | 7.49%   |
| GREETD  | 5         | 1.1%    |
| EMPTTY  | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 227       | 50.56%  |
| en_GB   | 44        | 9.8%    |
| de_DE   | 29        | 6.46%   |
| en_IN   | 25        | 5.57%   |
| en_CA   | 17        | 3.79%   |
| it_IT   | 16        | 3.56%   |
| pt_BR   | 13        | 2.9%    |
| pl_PL   | 10        | 2.23%   |
| ru_RU   | 8         | 1.78%   |
| tr_TR   | 6         | 1.34%   |
| fr_FR   | 6         | 1.34%   |
| es_MX   | 6         | 1.34%   |
| es_ES   | 4         | 0.89%   |
| en_ZA   | 4         | 0.89%   |
| nl_NL   | 3         | 0.67%   |
| es_CO   | 3         | 0.67%   |
| sv_SE   | 2         | 0.45%   |
| fi_FI   | 2         | 0.45%   |
| es_EC   | 2         | 0.45%   |
| es_AR   | 2         | 0.45%   |
| en_DK   | 2         | 0.45%   |
| en_AG   | 2         | 0.45%   |
| de_AT   | 2         | 0.45%   |
| zh_CN   | 1         | 0.22%   |
| vi_VN   | 1         | 0.22%   |
| uk_UA   | 1         | 0.22%   |
| ko_KR   | 1         | 0.22%   |
| ja_JP   | 1         | 0.22%   |
| hu_HU   | 1         | 0.22%   |
| fr_CA   | 1         | 0.22%   |
| es_VE   | 1         | 0.22%   |
| es_PE   | 1         | 0.22%   |
| es_BO   | 1         | 0.22%   |
| en_AU   | 1         | 0.22%   |
| el_GR   | 1         | 0.22%   |
| bg_BG   | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 261       | 57.87%  |
| BIOS | 190       | 42.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 434       | 97.09%  |
| Overlay | 6         | 1.34%   |
| Tmpfs   | 4         | 0.89%   |
| XXXXX   | 1         | 0.22%   |
| Xfs     | 1         | 0.22%   |
| F2fs    | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 266       | 58.85%  |
| Unknown | 167       | 36.95%  |
| MBR     | 19        | 4.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 401       | 89.11%  |
| Yes       | 49        | 10.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 321       | 71.18%  |
| Yes       | 130       | 28.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 88        | 19.73%  |
| Hewlett-Packard                | 70        | 15.7%   |
| ASUSTek Computer               | 67        | 15.02%  |
| Dell                           | 59        | 13.23%  |
| Acer                           | 39        | 8.74%   |
| MSI                            | 21        | 4.71%   |
| Apple                          | 14        | 3.14%   |
| HUAWEI                         | 8         | 1.79%   |
| Razer                          | 6         | 1.35%   |
| Notebook                       | 6         | 1.35%   |
| Toshiba                        | 5         | 1.12%   |
| Samsung Electronics            | 5         | 1.12%   |
| Alienware                      | 5         | 1.12%   |
| Unknown                        | 5         | 1.12%   |
| Gigabyte Technology            | 4         | 0.9%    |
| Google                         | 3         | 0.67%   |
| Fujitsu                        | 3         | 0.67%   |
| XIAOMI                         | 2         | 0.45%   |
| Sony                           | 2         | 0.45%   |
| Schenker                       | 2         | 0.45%   |
| Monster                        | 2         | 0.45%   |
| Medion                         | 2         | 0.45%   |
| HONOR                          | 2         | 0.45%   |
| GPU Company                    | 2         | 0.45%   |
| GPD                            | 2         | 0.45%   |
| Casper                         | 2         | 0.45%   |
| Valve                          | 1         | 0.22%   |
| Timi                           | 1         | 0.22%   |
| Standard                       | 1         | 0.22%   |
| PEAQ                           | 1         | 0.22%   |
| PC Specialist                  | 1         | 0.22%   |
| Panasonic                      | 1         | 0.22%   |
| OriginPC                       | 1         | 0.22%   |
| MOTION                         | 1         | 0.22%   |
| MobileDemand                   | 1         | 0.22%   |
| MICROBYTE                      | 1         | 0.22%   |
| Matsushita Electric Industrial | 1         | 0.22%   |
| Kogan                          | 1         | 0.22%   |
| HC                             | 1         | 0.22%   |
| Fujitsu Siemens                | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 1.79%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 5         | 1.12%   |
| Apple MacBookPro9,2                      | 5         | 1.12%   |
| HP Laptop 15-da0xxx                      | 3         | 0.67%   |
| Dell Inspiron 15 7000 Gaming             | 3         | 0.67%   |
| ASUS Vivobook Go E1504FA_E1504FA         | 3         | 0.67%   |
| XIAOMI Redmi Book Pro 15 2023            | 2         | 0.45%   |
| Razer Blade                              | 2         | 0.45%   |
| Notebook P7xxDM2(-G)                     | 2         | 0.45%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS0JT00 | 2         | 0.45%   |
| Lenovo ThinkPad W530 24474KG             | 2         | 0.45%   |
| Lenovo IdeaPad 3 15ITL05 81X8            | 2         | 0.45%   |
| HUAWEI HVY-WXX9                          | 2         | 0.45%   |
| HP ProBook 640 G1                        | 2         | 0.45%   |
| HP Pavilion Laptop 15-cc1xx              | 2         | 0.45%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 2         | 0.45%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 2         | 0.45%   |
| HP Pavilion dv6                          | 2         | 0.45%   |
| HP OMEN Laptop 15-en0xxx                 | 2         | 0.45%   |
| HP OMEN by Laptop 15-dh1xxx              | 2         | 0.45%   |
| HP Notebook                              | 2         | 0.45%   |
| HP Laptop 15-ef2xxx                      | 2         | 0.45%   |
| HP Laptop 15-ef0xxx                      | 2         | 0.45%   |
| HP Laptop 15-dy2xxx                      | 2         | 0.45%   |
| Gigabyte G5 MD                           | 2         | 0.45%   |
| Dell XPS 15 9500                         | 2         | 0.45%   |
| Dell Latitude E6430                      | 2         | 0.45%   |
| Dell Latitude E6420                      | 2         | 0.45%   |
| Dell Inspiron 7737                       | 2         | 0.45%   |
| Dell G15 Special Edition 5521            | 2         | 0.45%   |
| Casper EXCALIBUR G770                    | 2         | 0.45%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA   | 2         | 0.45%   |
| ASUS TUF Gaming FX505DT_FX505DT          | 2         | 0.45%   |
| ASUS ROG Zephyrus G15 GA503QR_GA503QR    | 2         | 0.45%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM    | 2         | 0.45%   |
| ASUS ROG Flow X13 GV301QH_GV301QH        | 2         | 0.45%   |
| Apple MacBookPro9,1                      | 2         | 0.45%   |
| Acer Nitro AN515-54                      | 2         | 0.45%   |
| Acer Nitro AN515-44                      | 2         | 0.45%   |
| Acer Aspire A515-51G                     | 2         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 35        | 7.85%   |
| Lenovo IdeaPad       | 27        | 6.05%   |
| Dell Inspiron        | 20        | 4.48%   |
| ASUS Vivobook        | 20        | 4.48%   |
| Acer Aspire          | 19        | 4.26%   |
| HP Laptop            | 18        | 4.04%   |
| HP Pavilion          | 16        | 3.59%   |
| Dell Latitude        | 16        | 3.59%   |
| ASUS ROG             | 16        | 3.59%   |
| Lenovo Legion        | 13        | 2.91%   |
| Acer Nitro           | 10        | 2.24%   |
| ASUS ASUS            | 9         | 2.02%   |
| HP OMEN              | 8         | 1.79%   |
| Dell Precision       | 8         | 1.79%   |
| Unknown              | 8         | 1.79%   |
| Dell XPS             | 7         | 1.57%   |
| Apple MacBookPro9    | 7         | 1.57%   |
| Razer Blade          | 6         | 1.35%   |
| HP EliteBook         | 6         | 1.35%   |
| Toshiba Satellite    | 5         | 1.12%   |
| HP ProBook           | 5         | 1.12%   |
| Acer Swift           | 5         | 1.12%   |
| HP Victus            | 4         | 0.9%    |
| Dell G15             | 4         | 0.9%    |
| ASUS TUF             | 4         | 0.9%    |
| MSI Stealth          | 3         | 0.67%   |
| Gigabyte G5          | 3         | 0.67%   |
| ASUS Zenbook         | 3         | 0.67%   |
| XIAOMI Redmi         | 2         | 0.45%   |
| Notebook P7xxDM2(-G) | 2         | 0.45%   |
| MSI Modern           | 2         | 0.45%   |
| MSI GF63             | 2         | 0.45%   |
| Monster TULPAR       | 2         | 0.45%   |
| HUAWEI HVY-WXX9      | 2         | 0.45%   |
| HP ZBook             | 2         | 0.45%   |
| HP Notebook          | 2         | 0.45%   |
| HP Compaq            | 2         | 0.45%   |
| Fujitsu LIFEBOOK     | 2         | 0.45%   |
| Dell Vostro          | 2         | 0.45%   |
| Casper EXCALIBUR     | 2         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 71        | 15.92%  |
| 2020    | 66        | 14.8%   |
| 2019    | 39        | 8.74%   |
| 2018    | 33        | 7.4%    |
| 2017    | 33        | 7.4%    |
| 2022    | 30        | 6.73%   |
| 2013    | 26        | 5.83%   |
| 2012    | 26        | 5.83%   |
| 2023    | 21        | 4.71%   |
| 2016    | 21        | 4.71%   |
| 2014    | 19        | 4.26%   |
| 2011    | 16        | 3.59%   |
| 2015    | 13        | 2.91%   |
| 2024    | 11        | 2.47%   |
| 2010    | 6         | 1.35%   |
| 2008    | 6         | 1.35%   |
| 2009    | 5         | 1.12%   |
| 2007    | 3         | 0.67%   |
| Unknown | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 446       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 446       | 99.78%  |
| Enabled  | 1         | 0.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 443       | 99.33%  |
| Yes  | 3         | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 127       | 28.22%  |
| 16.01-24.0  | 110       | 24.44%  |
| 8.01-16.0   | 101       | 22.44%  |
| 32.01-64.0  | 52        | 11.56%  |
| 3.01-4.0    | 33        | 7.33%   |
| 24.01-32.0  | 16        | 3.56%   |
| 64.01-256.0 | 10        | 2.22%   |
| 2.01-3.0    | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 167       | 34.65%  |
| 3.01-4.0   | 123       | 25.52%  |
| 2.01-3.0   | 112       | 23.24%  |
| 1.01-2.0   | 41        | 8.51%   |
| 8.01-16.0  | 35        | 7.26%   |
| 0.51-1.0   | 2         | 0.41%   |
| 32.01-64.0 | 1         | 0.21%   |
| 16.01-24.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 271       | 59.3%   |
| 2      | 152       | 33.26%  |
| 3      | 26        | 5.69%   |
| 4      | 7         | 1.53%   |
| 0      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 361       | 80.22%  |
| Yes       | 89        | 19.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 336       | 75%     |
| No        | 112       | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 433       | 97.09%  |
| No        | 13        | 2.91%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 404       | 89.78%  |
| No        | 46        | 10.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 119       | 26.44%  |
| Germany      | 41        | 9.11%   |
| India        | 28        | 6.22%   |
| UK           | 23        | 5.11%   |
| Canada       | 23        | 5.11%   |
| Italy        | 22        | 4.89%   |
| Poland       | 17        | 3.78%   |
| Brazil       | 17        | 3.78%   |
| Turkey       | 11        | 2.44%   |
| France       | 10        | 2.22%   |
| Spain        | 8         | 1.78%   |
| Russia       | 8         | 1.78%   |
| Netherlands  | 8         | 1.78%   |
| Mexico       | 8         | 1.78%   |
| Romania      | 6         | 1.33%   |
| Sweden       | 5         | 1.11%   |
| South Africa | 5         | 1.11%   |
| Greece       | 5         | 1.11%   |
| Colombia     | 5         | 1.11%   |
| Indonesia    | 4         | 0.89%   |
| Belgium      | 4         | 0.89%   |
| Vietnam      | 3         | 0.67%   |
| Switzerland  | 3         | 0.67%   |
| Pakistan     | 3         | 0.67%   |
| Hungary      | 3         | 0.67%   |
| Finland      | 3         | 0.67%   |
| Ecuador      | 3         | 0.67%   |
| Denmark      | 3         | 0.67%   |
| Austria      | 3         | 0.67%   |
| Australia    | 3         | 0.67%   |
| Slovenia     | 2         | 0.44%   |
| Singapore    | 2         | 0.44%   |
| Serbia       | 2         | 0.44%   |
| Morocco      | 2         | 0.44%   |
| Japan        | 2         | 0.44%   |
| Czechia      | 2         | 0.44%   |
| Croatia      | 2         | 0.44%   |
| China        | 2         | 0.44%   |
| Bulgaria     | 2         | 0.44%   |
| Bangladesh   | 2         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Istanbul           | 5         | 1.05%   |
| Berlin             | 5         | 1.05%   |
| Athens             | 5         | 1.05%   |
| Warsaw             | 4         | 0.84%   |
| Valencia           | 4         | 0.84%   |
| Mississauga        | 4         | 0.84%   |
| Milan              | 4         | 0.84%   |
| Los Angeles        | 4         | 0.84%   |
| London             | 4         | 0.84%   |
| Hyderabad          | 4         | 0.84%   |
| Toronto            | 3         | 0.63%   |
| Portland           | 3         | 0.63%   |
| New York           | 3         | 0.63%   |
| Mumbai             | 3         | 0.63%   |
| Moscow             | 3         | 0.63%   |
| Ho Chi Minh City   | 3         | 0.63%   |
| Frankfurt am Main  | 3         | 0.63%   |
| Düsseldorf        | 3         | 0.63%   |
| Drums              | 3         | 0.63%   |
| Copenhagen         | 3         | 0.63%   |
| Cape Town          | 3         | 0.63%   |
| Bengaluru          | 3         | 0.63%   |
| Zagreb             | 2         | 0.42%   |
| Wroclaw            | 2         | 0.42%   |
| Turin              | 2         | 0.42%   |
| Sydney             | 2         | 0.42%   |
| Sulzbach-Rosenberg | 2         | 0.42%   |
| Southwark          | 2         | 0.42%   |
| Southampton        | 2         | 0.42%   |
| Singapore          | 2         | 0.42%   |
| San Jose           | 2         | 0.42%   |
| Saint Paul         | 2         | 0.42%   |
| Pune               | 2         | 0.42%   |
| Prague             | 2         | 0.42%   |
| Poznan             | 2         | 0.42%   |
| Peterborough       | 2         | 0.42%   |
| Palermo            | 2         | 0.42%   |
| Noida              | 2         | 0.42%   |
| New Glasgow        | 2         | 0.42%   |
| Munich             | 2         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 116       | 142    | 18.01%  |
| SanDisk                     | 59        | 70     | 9.16%   |
| Seagate                     | 57        | 64     | 8.85%   |
| SK hynix                    | 41        | 54     | 6.37%   |
| WDC                         | 37        | 40     | 5.75%   |
| Toshiba                     | 32        | 38     | 4.97%   |
| Intel                       | 30        | 36     | 4.66%   |
| Unknown                     | 28        | 33     | 4.35%   |
| Micron Technology           | 22        | 29     | 3.42%   |
| Kingston                    | 18        | 18     | 2.8%    |
| HGST                        | 18        | 18     | 2.8%    |
| Crucial                     | 15        | 19     | 2.33%   |
| Phison Electronics          | 14        | 18     | 2.17%   |
| Hitachi                     | 11        | 11     | 1.71%   |
| KIOXIA                      | 10        | 12     | 1.55%   |
| Kingston Technology Company | 10        | 11     | 1.55%   |
| Silicon Motion              | 8         | 8      | 1.24%   |
| Micron/Crucial Technology   | 8         | 9      | 1.24%   |
| SPCC                        | 7         | 8      | 1.09%   |
| A-DATA Technology           | 6         | 9      | 0.93%   |
| SABRENT                     | 5         | 7      | 0.78%   |
| PNY                         | 5         | 5      | 0.78%   |
| Apple                       | 5         | 7      | 0.78%   |
| ADATA Technology            | 5         | 7      | 0.78%   |
| Phison                      | 4         | 4      | 0.62%   |
| China                       | 4         | 4      | 0.62%   |
| MAXIO Technology (Hangzhou) | 3         | 5      | 0.47%   |
| LITEON                      | 3         | 3      | 0.47%   |
| JMicron Technology          | 3         | 3      | 0.47%   |
| Hewlett-Packard             | 3         | 3      | 0.47%   |
| Corsair                     | 3         | 3      | 0.47%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.31%   |
| Solid State Storage         | 2         | 2      | 0.31%   |
| Realtek Semiconductor       | 2         | 2      | 0.31%   |
| Patriot                     | 2         | 7      | 0.31%   |
| LITEONIT                    | 2         | 2      | 0.31%   |
| JetFlash                    | 2         | 2      | 0.31%   |
| Intenso                     | 2         | 2      | 0.31%   |
| FORESEE                     | 2         | 2      | 0.31%   |
| Unknown                     | 2         | 3      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 22        | 3.27%   |
| Seagate ST1000LM035-1RK172 1TB                       | 12        | 1.78%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 11        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 11        | 1.63%   |
| Intel SSD 660P Series 1024GB                         | 11        | 1.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 8         | 1.19%   |
| HGST HTS721010A9E630 1TB                             | 8         | 1.19%   |
| Unknown MMC Card  64GB                               | 7         | 1.04%   |
| Seagate ST1000LM049-2GH172 1TB                       | 7         | 1.04%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 6         | 0.89%   |
| Samsung SSD 860 EVO 1TB                              | 6         | 0.89%   |
| Samsung NVMe SSD Drive 1TB                           | 6         | 0.89%   |
| Phison E16 PCIe4 NVMe Controller 1TB                 | 6         | 0.89%   |
| Toshiba MQ01ABD100 1TB                               | 5         | 0.74%   |
| Seagate ST1000LM014-1EJ164 1TB                       | 5         | 0.74%   |
| SABRENT Disk 2TB                                     | 5         | 0.74%   |
| Phison E12 NVMe Controller 480GB                     | 5         | 0.74%   |
| Intel SSDPEKNU512GZ 512GB                            | 5         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 4         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 4         | 0.59%   |
| Samsung SSD 870 EVO 1TB                              | 4         | 0.59%   |
| Samsung SSD 860 EVO 500GB                            | 4         | 0.59%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 4         | 0.59%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB              | 4         | 0.59%   |
| HGST HTS725050A7E630 500GB                           | 4         | 0.59%   |
| Unknown MMC Card  128GB                              | 3         | 0.45%   |
| Toshiba MQ04ABF100 1TB                               | 3         | 0.45%   |
| Toshiba MQ04ABD200 2TB                               | 3         | 0.45%   |
| Toshiba MQ01ABF050 500GB                             | 3         | 0.45%   |
| SPCC Solid State Disk 512GB                          | 3         | 0.45%   |
| SK hynix HFM001TD3JX013N 1024GB                      | 3         | 0.45%   |
| Seagate ST2000LM015-2E8174 2TB                       | 3         | 0.45%   |
| Seagate ST1000LM048-2E7172 1TB                       | 3         | 0.45%   |
| Sandisk WDC WDS500G2B0C-00PXH0 500GB                 | 3         | 0.45%   |
| Samsung SSD 980 500GB                                | 3         | 0.45%   |
| Samsung SSD 980 1TB                                  | 3         | 0.45%   |
| Samsung SSD 870 QVO 1TB                              | 3         | 0.45%   |
| Samsung SSD 860 EVO 250GB                            | 3         | 0.45%   |
| Samsung PSSD T7 500GB                                | 3         | 0.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 3         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 60     | 40.44%  |
| Toshiba             | 21        | 24     | 15.44%  |
| HGST                | 18        | 18     | 13.24%  |
| WDC                 | 17        | 19     | 12.5%   |
| Hitachi             | 11        | 11     | 8.09%   |
| SABRENT             | 5         | 7      | 3.68%   |
| Unknown             | 2         | 3      | 1.47%   |
| JMicron Technology  | 2         | 2      | 1.47%   |
| Samsung Electronics | 1         | 1      | 0.74%   |
| KESU                | 1         | 1      | 0.74%   |
| Initio              | 1         | 1      | 0.74%   |
| ASMT                | 1         | 1      | 0.74%   |
| Apple               | 1         | 2      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 48     | 25.9%   |
| SanDisk             | 16        | 21     | 9.64%   |
| Crucial             | 14        | 18     | 8.43%   |
| Kingston            | 10        | 10     | 6.02%   |
| SK hynix            | 8         | 11     | 4.82%   |
| WDC                 | 7         | 8      | 4.22%   |
| SPCC                | 6         | 7      | 3.61%   |
| A-DATA Technology   | 6         | 9      | 3.61%   |
| PNY                 | 5         | 5      | 3.01%   |
| Micron Technology   | 5         | 6      | 3.01%   |
| China               | 4         | 4      | 2.41%   |
| Toshiba             | 3         | 3      | 1.81%   |
| LITEON              | 3         | 3      | 1.81%   |
| Hewlett-Packard     | 3         | 3      | 1.81%   |
| Patriot             | 2         | 7      | 1.2%    |
| LITEONIT            | 2         | 2      | 1.2%    |
| FORESEE             | 2         | 2      | 1.2%    |
| Apple               | 2         | 2      | 1.2%    |
| Unknown             | 2         | 3      | 1.2%    |
| X12                 | 1         | 1      | 0.6%    |
| WODPOSIT            | 1         | 2      | 0.6%    |
| WDC WDS             | 1         | 1      | 0.6%    |
| VisionTek           | 1         | 2      | 0.6%    |
| Transcend           | 1         | 1      | 0.6%    |
| TCSUNBOW            | 1         | 2      | 0.6%    |
| TAMMUZ              | 1         | 2      | 0.6%    |
| SATAFIRM            | 1         | 1      | 0.6%    |
| PNY CS90            | 1         | 1      | 0.6%    |
| Pioneer             | 1         | 1      | 0.6%    |
| OWC                 | 1         | 1      | 0.6%    |
| Netac               | 1         | 1      | 0.6%    |
| Mushkin             | 1         | 1      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.6%    |
| KIOXIA-E            | 1         | 1      | 0.6%    |
| Intenso             | 1         | 1      | 0.6%    |
| GOODRAM             | 1         | 1      | 0.6%    |
| GLOWAY              | 1         | 2      | 0.6%    |
| Gigabyte Technology | 1         | 1      | 0.6%    |
| Emtec               | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 271       | 374    | 46.17%  |
| SSD     | 153       | 200    | 26.06%  |
| HDD     | 126       | 150    | 21.47%  |
| MMC     | 25        | 28     | 4.26%   |
| Unknown | 12        | 12     | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 270       | 369    | 48.56%  |
| SATA | 222       | 317    | 39.93%  |
| SAS  | 39        | 50     | 7.01%   |
| MMC  | 25        | 28     | 4.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 140       | 176    | 50.18%  |
| 0.51-1.0   | 113       | 140    | 40.5%   |
| 1.01-2.0   | 21        | 29     | 7.53%   |
| 3.01-4.0   | 4         | 4      | 1.43%   |
| 4.01-10.0  | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 163       | 35.51%  |
| 1001-2000      | 94        | 20.48%  |
| 501-1000       | 75        | 16.34%  |
| 2001-3000      | 62        | 13.51%  |
| 251-500        | 22        | 4.79%   |
| Unknown        | 22        | 4.79%   |
| 1-20           | 15        | 3.27%   |
| 101-250        | 6         | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 131       | 27.58%  |
| 251-500        | 81        | 17.05%  |
| 501-1000       | 80        | 16.84%  |
| 51-100         | 58        | 12.21%  |
| 1001-2000      | 51        | 10.74%  |
| More than 3000 | 22        | 4.63%   |
| Unknown        | 22        | 4.63%   |
| 2001-3000      | 15        | 3.16%   |
| 1-20           | 14        | 2.95%   |
| 0              | 1         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 11.11%  |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 11.11%  |
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 5.56%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 5.56%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 5.56%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 1         | 3      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 5.56%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 5.56%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 5.56%   |
| SanDisk SSD PLUS 1000GB               | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 860 EVO 500GB | 1         | 1      | 5.56%   |
| Hitachi HUA722020ALA331 2TB           | 1         | 1      | 5.56%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 5.56%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 5.56%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 5.56%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 27.78%  |
| HGST                | 4         | 4      | 22.22%  |
| Hitachi             | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| SK hynix            | 2         | 4      | 11.11%  |
| SanDisk             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 35.71%  |
| HGST    | 4         | 4      | 28.57%  |
| Hitachi | 3         | 3      | 21.43%  |
| WDC     | 2         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 14     | 76.47%  |
| NVMe | 2         | 4      | 11.76%  |
| SSD  | 2         | 2      | 11.76%  |

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
| Detected | 243       | 399    | 49.9%   |
| Works    | 227       | 345    | 46.61%  |
| Malfunc  | 17        | 20     | 3.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 274       | 44.48%  |
| Samsung Electronics            | 76        | 12.34%  |
| AMD                            | 60        | 9.74%   |
| SanDisk                        | 53        | 8.6%    |
| SK hynix                       | 33        | 5.36%   |
| Phison Electronics             | 21        | 3.41%   |
| Kingston Technology Company    | 18        | 2.92%   |
| Micron Technology              | 16        | 2.6%    |
| Toshiba America Info Systems   | 10        | 1.62%   |
| KIOXIA                         | 10        | 1.62%   |
| Micron/Crucial Technology      | 9         | 1.46%   |
| Silicon Motion                 | 8         | 1.3%    |
| ADATA Technology               | 5         | 0.81%   |
| Union Memory (Shenzhen)        | 4         | 0.65%   |
| Solid State Storage Technology | 3         | 0.49%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.49%   |
| Solidigm                       | 2         | 0.32%   |
| Realtek Semiconductor          | 2         | 0.32%   |
| Apple                          | 2         | 0.32%   |
| Yangtze Memory Technologies    | 1         | 0.16%   |
| Nvidia                         | 1         | 0.16%   |
| Marvell Technology Group       | 1         | 0.16%   |
| Lenovo                         | 1         | 0.16%   |
| INNOGRIT                       | 1         | 0.16%   |
| Biwin Storage Technology       | 1         | 0.16%   |
| ASMedia Technology             | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 58        | 8.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 34        | 5.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 32        | 4.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 28        | 4.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 3.99%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 20        | 3.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 20        | 3.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 3.07%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 19        | 2.92%   |
| Intel SSD 660P Series                                                          | 15        | 2.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 2.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 2%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 12        | 1.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 1.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 1.54%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 1.38%   |
| Phison E12 NVMe Controller                                                     | 9         | 1.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 1.23%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 8         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.23%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 7         | 1.08%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 7         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.08%   |
| Phison E16 PCIe4 NVMe Controller                                               | 6         | 0.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6         | 0.92%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 0.92%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 5         | 0.77%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 5         | 0.77%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 5         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.77%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 4         | 0.61%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 0.61%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 4         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.61%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 4         | 0.61%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 4         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 274       | 45.44%  |
| NVMe | 268       | 44.44%  |
| RAID | 55        | 9.12%   |
| IDE  | 6         | 1%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 314       | 70.4%   |
| AMD    | 132       | 29.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 3.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 2.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 2.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 2.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 2.24%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 2.02%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 2.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 1.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.35%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 1.35%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 6         | 1.35%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 1.12%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 1.12%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 5         | 1.12%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 5         | 1.12%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 5         | 1.12%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 1.12%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 0.9%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.9%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.9%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.9%    |
| Intel 12th Gen Core i7-12700H                 | 4         | 0.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.9%    |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics    | 4         | 0.9%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.9%    |
| AMD Ryzen 5 7520U with Radeon Graphics        | 4         | 0.9%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 3         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.67%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 0.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.67%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 0.67%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 117       | 26.23%  |
| Intel Core i5           | 80        | 17.94%  |
| Other                   | 56        | 12.56%  |
| AMD Ryzen 7             | 47        | 10.54%  |
| AMD Ryzen 5             | 46        | 10.31%  |
| Intel Core i3           | 26        | 5.83%   |
| Intel Celeron           | 12        | 2.69%   |
| AMD Ryzen 9             | 10        | 2.24%   |
| Intel Pentium           | 6         | 1.35%   |
| Intel Core 2 Duo        | 6         | 1.35%   |
| Intel Core i9           | 5         | 1.12%   |
| AMD Ryzen 7 PRO         | 5         | 1.12%   |
| AMD Ryzen 3             | 5         | 1.12%   |
| AMD A8                  | 5         | 1.12%   |
| AMD A6                  | 4         | 0.9%    |
| Intel Pentium Silver    | 3         | 0.67%   |
| AMD A10                 | 3         | 0.67%   |
| Intel Xeon              | 2         | 0.45%   |
| Intel Pentium Dual-Core | 2         | 0.45%   |
| Intel Core m3           | 1         | 0.22%   |
| Intel Core              | 1         | 0.22%   |
| AMD Turion              | 1         | 0.22%   |
| AMD FX                  | 1         | 0.22%   |
| AMD Athlon              | 1         | 0.22%   |
| AMD A4                  | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 146       | 32.74%  |
| 2      | 140       | 31.39%  |
| 6      | 71        | 15.92%  |
| 8      | 69        | 15.47%  |
| 14     | 10        | 2.24%   |
| 10     | 3         | 0.67%   |
| 24     | 2         | 0.45%   |
| 16     | 2         | 0.45%   |
| 12     | 2         | 0.45%   |
| 1      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 446       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 398       | 89.24%  |
| 1      | 48        | 10.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 446       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 305       | 66.45%  |
| 0x0a50000c | 12        | 2.61%   |
| 0x306a9    | 11        | 2.4%    |
| 0x206a7    | 9         | 1.96%   |
| 0x08108109 | 8         | 1.74%   |
| 0x806c1    | 7         | 1.53%   |
| 0xa0652    | 6         | 1.31%   |
| 0x906ea    | 6         | 1.31%   |
| 0x08600106 | 6         | 1.31%   |
| 0x906e9    | 5         | 1.09%   |
| 0x806ea    | 5         | 1.09%   |
| 0x806e9    | 5         | 1.09%   |
| 0x506e3    | 4         | 0.87%   |
| 0x306c3    | 4         | 0.87%   |
| 0x08600103 | 4         | 0.87%   |
| 0x806ec    | 3         | 0.65%   |
| 0x406e3    | 3         | 0.65%   |
| 0x40651    | 3         | 0.65%   |
| 0x0a50000d | 3         | 0.65%   |
| 0x0a404102 | 3         | 0.65%   |
| 0x08a00008 | 3         | 0.65%   |
| 0x08608103 | 3         | 0.65%   |
| 0x08600104 | 3         | 0.65%   |
| 0x08108102 | 3         | 0.65%   |
| 0x06006705 | 3         | 0.65%   |
| 0x906a3    | 2         | 0.44%   |
| 0x106e5    | 2         | 0.44%   |
| 0x0a704103 | 2         | 0.44%   |
| 0x0a601203 | 2         | 0.44%   |
| 0x0a50000b | 2         | 0.44%   |
| 0x08101007 | 2         | 0.44%   |
| 0xa0660    | 1         | 0.22%   |
| 0x806d1    | 1         | 0.22%   |
| 0x706e5    | 1         | 0.22%   |
| 0x706a8    | 1         | 0.22%   |
| 0x706a1    | 1         | 0.22%   |
| 0x506c9    | 1         | 0.22%   |
| 0x406c4    | 1         | 0.22%   |
| 0x306d4    | 1         | 0.22%   |
| 0x20655    | 1         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 90        | 20.18%  |
| Unknown           | 57        | 12.78%  |
| IvyBridge         | 28        | 6.28%   |
| Haswell           | 27        | 6.05%   |
| Zen 3             | 26        | 5.83%   |
| Zen 2             | 26        | 5.83%   |
| TigerLake         | 25        | 5.61%   |
| Skylake           | 25        | 5.61%   |
| Zen+              | 23        | 5.16%   |
| CometLake         | 22        | 4.93%   |
| SandyBridge       | 19        | 4.26%   |
| Broadwell         | 11        | 2.47%   |
| Alderlake Hybrid  | 11        | 2.47%   |
| Penryn            | 7         | 1.57%   |
| Goldmont plus     | 7         | 1.57%   |
| Westmere          | 6         | 1.35%   |
| IceLake           | 6         | 1.35%   |
| Excavator         | 6         | 1.35%   |
| Puma              | 4         | 0.9%    |
| Goldmont          | 4         | 0.9%    |
| Silvermont        | 3         | 0.67%   |
| Zen               | 2         | 0.45%   |
| Steamroller       | 2         | 0.45%   |
| Piledriver        | 2         | 0.45%   |
| Nehalem           | 2         | 0.45%   |
| Meteorlake Hybrid | 1         | 0.22%   |
| K8 & K10 hybrid   | 1         | 0.22%   |
| K10 Llano         | 1         | 0.22%   |
| Jaguar            | 1         | 0.22%   |
| Core              | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 294       | 45.16%  |
| Nvidia | 212       | 32.57%  |
| AMD    | 145       | 22.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 28        | 4.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 26        | 3.93%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 25        | 3.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 23        | 3.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 22        | 3.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 22        | 3.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 19        | 2.87%   |
| Intel UHD Graphics 620                                                    | 18        | 2.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 18        | 2.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 18        | 2.72%   |
| Intel HD Graphics 630                                                     | 17        | 2.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 16        | 2.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 15        | 2.27%   |
| AMD Rembrandt [Radeon 680M]                                               | 14        | 2.11%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 12        | 1.81%   |
| AMD Lucienne                                                              | 11        | 1.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 10        | 1.51%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 10        | 1.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 10        | 1.51%   |
| Intel HD Graphics 620                                                     | 10        | 1.51%   |
| Intel HD Graphics 5500                                                    | 10        | 1.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 10        | 1.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 9         | 1.36%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 9         | 1.36%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 8         | 1.21%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 8         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 7         | 1.06%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 7         | 1.06%   |
| Intel HD Graphics 530                                                     | 7         | 1.06%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 6         | 0.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 6         | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                             | 5         | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 5         | 0.76%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 5         | 0.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                       | 5         | 0.76%   |
| AMD Phoenix1                                                              | 5         | 0.76%   |
| AMD Mendocino                                                             | 5         | 0.76%   |
| Nvidia GM108M [GeForce MX110]                                             | 4         | 0.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 143       | 31.99%  |
| Intel + Nvidia     | 138       | 30.87%  |
| 1 x AMD            | 76        | 17%     |
| AMD + Nvidia       | 54        | 12.08%  |
| 1 x Nvidia         | 18        | 4.03%   |
| Intel + AMD        | 10        | 2.24%   |
| 2 x AMD            | 5         | 1.12%   |
| Intel + 2 x Nvidia | 2         | 0.45%   |
| 2 x Intel          | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 275       | 61.11%  |
| Proprietary | 171       | 38%     |
| Unknown     | 4         | 0.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 333       | 73.19%  |
| 0.01-0.5   | 57        | 12.53%  |
| 1.01-2.0   | 25        | 5.49%   |
| 5.01-6.0   | 12        | 2.64%   |
| 3.01-4.0   | 11        | 2.42%   |
| 7.01-8.0   | 10        | 2.2%    |
| 0.51-1.0   | 6         | 1.32%   |
| 8.01-16.0  | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 107       | 20.3%   |
| BOE                     | 82        | 15.56%  |
| Chimei Innolux          | 78        | 14.8%   |
| LG Display              | 62        | 11.76%  |
| Samsung Electronics     | 41        | 7.78%   |
| PANDA                   | 20        | 3.8%    |
| Sharp                   | 18        | 3.42%   |
| Dell                    | 15        | 2.85%   |
| Apple                   | 14        | 2.66%   |
| Acer                    | 9         | 1.71%   |
| Lenovo                  | 8         | 1.52%   |
| Goldstar                | 8         | 1.52%   |
| Hewlett-Packard         | 6         | 1.14%   |
| TMX                     | 4         | 0.76%   |
| Mi                      | 4         | 0.76%   |
| Sony                    | 3         | 0.57%   |
| InfoVision              | 3         | 0.57%   |
| CSO                     | 3         | 0.57%   |
| Chi Mei Optoelectronics | 3         | 0.57%   |
| AOC                     | 3         | 0.57%   |
| Vizio                   | 2         | 0.38%   |
| ViewSonic               | 2         | 0.38%   |
| Tianma XM               | 2         | 0.38%   |
| Philips                 | 2         | 0.38%   |
| LGD                     | 2         | 0.38%   |
| HKC                     | 2         | 0.38%   |
| BenQ                    | 2         | 0.38%   |
| ASUSTek Computer        | 2         | 0.38%   |
| Valve                   | 1         | 0.19%   |
| SDC                     | 1         | 0.19%   |
| Pixio                   | 1         | 0.19%   |
| OUT                     | 1         | 0.19%   |
| MStar                   | 1         | 0.19%   |
| MSI                     | 1         | 0.19%   |
| JRY                     | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| Iiyama                  | 1         | 0.19%   |
| GPD                     | 1         | 0.19%   |
| Gateway                 | 1         | 0.19%   |
| G-Story                 | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 1.13%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.75%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 0.75%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.75%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                      | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 3         | 0.57%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 0.57%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 2         | 0.38%   |
| TMX TL156MDMP31-0 TMX2005 3200x2000 336x210mm 15.6-inch               | 2         | 0.38%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 2         | 0.38%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 2         | 0.38%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.38%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 2         | 0.38%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.38%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 2         | 0.38%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 2         | 0.38%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 2         | 0.38%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch             | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch      | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch      | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch      | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 273       | 55.6%   |
| 1366x768 (WXGA)    | 81        | 16.5%   |
| 2560x1440 (QHD)    | 27        | 5.5%    |
| 3840x2160 (4K)     | 21        | 4.28%   |
| 1600x900 (HD+)     | 16        | 3.26%   |
| 2560x1600          | 11        | 2.24%   |
| 1920x1200 (WUXGA)  | 9         | 1.83%   |
| 1680x1050 (WSXGA+) | 8         | 1.63%   |
| 2880x1800          | 7         | 1.43%   |
| 1280x800 (WXGA)    | 7         | 1.43%   |
| 3440x1440          | 4         | 0.81%   |
| 1440x900 (WXGA+)   | 4         | 0.81%   |
| 3840x2400          | 3         | 0.61%   |
| 3200x2000          | 2         | 0.41%   |
| 3000x2000          | 2         | 0.41%   |
| 2160x1440          | 2         | 0.41%   |
| 1280x1024 (SXGA)   | 2         | 0.41%   |
| 800x1280           | 1         | 0.2%    |
| 3520x1080          | 1         | 0.2%    |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 2880x1440          | 1         | 0.2%    |
| 2560x1080          | 1         | 0.2%    |
| 2256x1504          | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1600x1200          | 1         | 0.2%    |
| 1280x768           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 256       | 48.95%  |
| 14      | 56        | 10.71%  |
| 13      | 44        | 8.41%   |
| 17      | 43        | 8.22%   |
| 27      | 19        | 3.63%   |
| 16      | 19        | 3.63%   |
| 24      | 12        | 2.29%   |
| 23      | 11        | 2.1%    |
| 31      | 9         | 1.72%   |
| 18      | 8         | 1.53%   |
| Unknown | 8         | 1.53%   |
| 21      | 7         | 1.34%   |
| 34      | 3         | 0.57%   |
| 20      | 3         | 0.57%   |
| 19      | 3         | 0.57%   |
| 12      | 3         | 0.57%   |
| 11      | 3         | 0.57%   |
| 72      | 2         | 0.38%   |
| 54      | 2         | 0.38%   |
| 22      | 2         | 0.38%   |
| 85      | 1         | 0.19%   |
| 84      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 43      | 1         | 0.19%   |
| 40      | 1         | 0.19%   |
| 35      | 1         | 0.19%   |
| 29      | 1         | 0.19%   |
| 28      | 1         | 0.19%   |
| 25      | 1         | 0.19%   |
| 7       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 346       | 66.41%  |
| 351-400     | 51        | 9.79%   |
| 501-600     | 42        | 8.06%   |
| 201-300     | 27        | 5.18%   |
| 401-500     | 21        | 4.03%   |
| 601-700     | 12        | 2.3%    |
| Unknown     | 8         | 1.54%   |
| 1501-2000   | 4         | 0.77%   |
| 701-800     | 3         | 0.58%   |
| 1001-1500   | 3         | 0.58%   |
| 801-900     | 2         | 0.38%   |
| 901-1000    | 1         | 0.19%   |
| 1-100       | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 395       | 84.58%  |
| 16/10   | 51        | 10.92%  |
| 3/2     | 5         | 1.07%   |
| 21/9    | 5         | 1.07%   |
| Unknown | 4         | 0.86%   |
| 4/3     | 3         | 0.64%   |
| 5/4     | 2         | 0.43%   |
| 2.00    | 1         | 0.21%   |
| 0.62    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 259       | 49.71%  |
| 81-90          | 89        | 17.08%  |
| 121-130        | 43        | 8.25%   |
| 201-250        | 28        | 5.37%   |
| 301-350        | 20        | 3.84%   |
| 351-500        | 14        | 2.69%   |
| 111-120        | 13        | 2.5%    |
| 71-80          | 10        | 1.92%   |
| Unknown        | 8         | 1.54%   |
| More than 1000 | 7         | 1.34%   |
| 151-200        | 7         | 1.34%   |
| 141-150        | 7         | 1.34%   |
| 251-300        | 4         | 0.77%   |
| 61-70          | 3         | 0.58%   |
| 51-60          | 3         | 0.58%   |
| 501-1000       | 2         | 0.38%   |
| 91-100         | 2         | 0.38%   |
| 1-40           | 1         | 0.19%   |
| 131-140        | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 263       | 51.07%  |
| 101-120       | 110       | 21.36%  |
| 51-100        | 61        | 11.84%  |
| 161-240       | 46        | 8.93%   |
| More than 240 | 21        | 4.08%   |
| Unknown       | 8         | 1.55%   |
| 1-50          | 6         | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 360       | 79.3%   |
| 2     | 87        | 19.16%  |
| 3     | 6         | 1.32%   |
| 0     | 1         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 258       | 35.2%   |
| Intel                             | 250       | 34.11%  |
| Qualcomm Atheros                  | 76        | 10.37%  |
| MediaTek                          | 40        | 5.46%   |
| Broadcom                          | 34        | 4.64%   |
| Samsung Electronics               | 9         | 1.23%   |
| TP-Link                           | 8         | 1.09%   |
| Xiaomi                            | 6         | 0.82%   |
| Ralink Technology                 | 6         | 0.82%   |
| Sierra Wireless                   | 5         | 0.68%   |
| Qualcomm                          | 4         | 0.55%   |
| Dell                              | 4         | 0.55%   |
| NetGear                           | 3         | 0.41%   |
| DisplayLink                       | 3         | 0.41%   |
| ASIX Electronics                  | 3         | 0.41%   |
| Wacom                             | 2         | 0.27%   |
| Ericsson Business Mobile Networks | 2         | 0.27%   |
| ASUSTek Computer                  | 2         | 0.27%   |
| Unknown                           | 2         | 0.27%   |
| ZyXEL Communications              | 1         | 0.14%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.14%   |
| Shenzhen Goodix Technology        | 1         | 0.14%   |
| Ralink                            | 1         | 0.14%   |
| QinHeng Electronics               | 1         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.14%   |
| Nvidia                            | 1         | 0.14%   |
| Motorola PCS                      | 1         | 0.14%   |
| Microsoft                         | 1         | 0.14%   |
| Marvell Technology Group          | 1         | 0.14%   |
| Lenovo                            | 1         | 0.14%   |
| ICS Advent                        | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |
| Dresden Elektronik                | 1         | 0.14%   |
| Broadcom Limited                  | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 160       | 18.82%  |
| Intel Wi-Fi 6 AX200                                                    | 34        | 4%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 2.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 21        | 2.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 20        | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 18        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18        | 2.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 18        | 2.12%   |
| Intel Wi-Fi 6 AX201                                                    | 17        | 2%      |
| Intel Wireless 8265 / 8275                                             | 16        | 1.88%   |
| Intel Wireless 7265                                                    | 15        | 1.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 1.76%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 1.53%   |
| Intel Wireless 7260                                                    | 13        | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 11        | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 1.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 9         | 1.06%   |
| Intel Wireless 3165                                                    | 9         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 9         | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 8         | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 8         | 0.94%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 7         | 0.82%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 0.82%   |
| Intel Wireless 8260                                                    | 7         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 6         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 6         | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 6         | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 5         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.59%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 5         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 239       | 50.64%  |
| Realtek Semiconductor | 73        | 15.47%  |
| Qualcomm Atheros      | 63        | 13.35%  |
| MediaTek              | 34        | 7.2%    |
| Broadcom              | 29        | 6.14%   |
| TP-Link               | 8         | 1.69%   |
| Ralink Technology     | 6         | 1.27%   |
| Sierra Wireless       | 5         | 1.06%   |
| NetGear               | 3         | 0.64%   |
| Wacom                 | 2         | 0.42%   |
| Qualcomm              | 2         | 0.42%   |
| Dell                  | 2         | 0.42%   |
| ASUSTek Computer      | 2         | 0.42%   |
| ZyXEL Communications  | 1         | 0.21%   |
| Ralink                | 1         | 0.21%   |
| Hewlett-Packard       | 1         | 0.21%   |
| Broadcom Limited      | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 34        | 7.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 21        | 4.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 4.19%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 3.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 3.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18        | 3.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 3.77%   |
| Intel Wi-Fi 6 AX201                                            | 17        | 3.56%   |
| Intel Wireless 8265 / 8275                                     | 16        | 3.35%   |
| Intel Wireless 7265                                            | 15        | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 2.73%   |
| Intel Wireless 7260                                            | 13        | 2.73%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 11        | 2.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 1.89%   |
| Intel Wireless 3165                                            | 9         | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 1.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 8         | 1.68%   |
| Intel Wireless 8260                                            | 7         | 1.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 1.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 1.26%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 1.05%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 5         | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.05%   |
| Intel Wireless 3160                                            | 5         | 1.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.84%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 0.63%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 3         | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 219       | 61.52%  |
| Intel                      | 65        | 18.26%  |
| Qualcomm Atheros           | 24        | 6.74%   |
| Broadcom                   | 14        | 3.93%   |
| MediaTek                   | 7         | 1.97%   |
| Xiaomi                     | 6         | 1.69%   |
| Samsung Electronics        | 3         | 0.84%   |
| DisplayLink                | 3         | 0.84%   |
| ASIX Electronics           | 3         | 0.84%   |
| Qualcomm                   | 2         | 0.56%   |
| Unknown                    | 2         | 0.56%   |
| ZTE WCDMA Technologies MSM | 1         | 0.28%   |
| QinHeng Electronics        | 1         | 0.28%   |
| Nvidia                     | 1         | 0.28%   |
| Motorola PCS               | 1         | 0.28%   |
| Microsoft                  | 1         | 0.28%   |
| Marvell Technology Group   | 1         | 0.28%   |
| Lenovo                     | 1         | 0.28%   |
| ICS Advent                 | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 160       | 44.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 6.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 4.18%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 3.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 2.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 8         | 2.23%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 1.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 6         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 1.39%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 1.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.11%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.84%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 3         | 0.84%   |
| MediaTek Infinix SMART 5                                               | 3         | 0.84%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.56%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.56%   |
| Unknown                                                                | 2         | 0.56%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                            | 1         | 0.28%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]     | 1         | 0.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.28%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 1         | 0.28%   |
| Qualcomm POCO F3                                                       | 1         | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 433       | 55.37%  |
| Ethernet | 335       | 42.84%  |
| Modem    | 12        | 1.53%   |
| Unknown  | 2         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 376       | 82.1%   |
| Ethernet | 81        | 17.69%  |
| Modem    | 1         | 0.22%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 301       | 67.49%  |
| 1     | 137       | 30.72%  |
| 3     | 6         | 1.35%   |
| 0     | 2         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 311       | 68.65%  |
| Yes  | 142       | 31.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 209       | 51.35%  |
| Realtek Semiconductor           | 53        | 13.02%  |
| Qualcomm Atheros Communications | 35        | 8.6%    |
| IMC Networks                    | 32        | 7.86%   |
| Lite-On Technology              | 16        | 3.93%   |
| Foxconn / Hon Hai               | 15        | 3.69%   |
| Broadcom                        | 12        | 2.95%   |
| Apple                           | 11        | 2.7%    |
| MediaTek                        | 4         | 0.98%   |
| Dell                            | 4         | 0.98%   |
| Cambridge Silicon Radio         | 4         | 0.98%   |
| Toshiba                         | 2         | 0.49%   |
| Realtek                         | 2         | 0.49%   |
| Hewlett-Packard                 | 2         | 0.49%   |
| USI                             | 1         | 0.25%   |
| Opticis                         | 1         | 0.25%   |
| Belkin Components               | 1         | 0.25%   |
| ASUSTek Computer                | 1         | 0.25%   |
| Alps Electric                   | 1         | 0.25%   |
| AboCom Systems                  | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 60        | 14.74%  |
| Intel AX201 Bluetooth                                | 52        | 12.78%  |
| Intel AX200 Bluetooth                                | 32        | 7.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 31        | 7.62%   |
| Realtek Bluetooth Radio                              | 29        | 7.13%   |
| IMC Networks Wireless_Device                         | 20        | 4.91%   |
| Qualcomm Atheros  Bluetooth Device                   | 16        | 3.93%   |
| Realtek  Bluetooth 4.2 Adapter                       | 12        | 2.95%   |
| Intel AX210 Bluetooth                                | 11        | 2.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0               | 10        | 2.46%   |
| IMC Networks Bluetooth Radio                         | 9         | 2.21%   |
| Intel AX211 Bluetooth                                | 8         | 1.97%   |
| Apple Bluetooth USB Host Controller                  | 7         | 1.72%   |
| Realtek 802.11ac WLAN Adapter                        | 6         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 6         | 1.47%   |
| Lite-On Bluetooth Device                             | 5         | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                    | 5         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 1.23%   |
| Lite-On Wireless_Device                              | 4         | 0.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth           | 4         | 0.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 4         | 0.98%   |
| Apple Bluetooth Host Controller                      | 4         | 0.98%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 3         | 0.74%   |
| Realtek RTL8821A Bluetooth                           | 3         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                    | 3         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 3         | 0.74%   |
| MediaTek Wireless_Device                             | 3         | 0.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 3         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                     | 3         | 0.74%   |
| Dell DW375 Bluetooth Module                          | 3         | 0.74%   |
| Broadcom HP Portable Bumble Bee                      | 3         | 0.74%   |
| Realtek Bluetooth Radio                              | 2         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                     | 2         | 0.49%   |
| Intel Bluetooth Device                               | 2         | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter         | 2         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1)                          | 2         | 0.49%   |
| USI Bluetooth Device                                 | 1         | 0.25%   |
| Toshiba Integrated Bluetooth HCI                     | 1         | 0.25%   |
| Toshiba Askey for                                    | 1         | 0.25%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 312       | 50.4%   |
| AMD                         | 136       | 21.97%  |
| Nvidia                      | 132       | 21.32%  |
| Realtek Semiconductor       | 3         | 0.48%   |
| Logitech                    | 3         | 0.48%   |
| JMTek                       | 3         | 0.48%   |
| GN Netcom                   | 3         | 0.48%   |
| C-Media Electronics         | 3         | 0.48%   |
| Texas Instruments           | 2         | 0.32%   |
| Samsung Electronics         | 2         | 0.32%   |
| RODE Microphones            | 2         | 0.32%   |
| Generalplus Technology      | 2         | 0.32%   |
| Corsair                     | 2         | 0.32%   |
| Turtle Beach                | 1         | 0.16%   |
| Sony                        | 1         | 0.16%   |
| Sennheiser Communications   | 1         | 0.16%   |
| Phison Electronics          | 1         | 0.16%   |
| M-Audio                     | 1         | 0.16%   |
| Lenovo                      | 1         | 0.16%   |
| KTMicro                     | 1         | 0.16%   |
| Kingston Technology         | 1         | 0.16%   |
| Jieli Technology            | 1         | 0.16%   |
| Huawei Technologies         | 1         | 0.16%   |
| FX200                       | 1         | 0.16%   |
| FiiO Electronics Technology | 1         | 0.16%   |
| Dell                        | 1         | 0.16%   |
| Apple                       | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 111       | 14.57%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 5.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 43        | 5.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 31        | 4.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 3.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 3.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 2.89%   |
| Intel Comet Lake PCH cAVS                                                  | 21        | 2.76%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 21        | 2.76%   |
| Intel CM238 HD Audio Controller                                            | 19        | 2.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 18        | 2.36%   |
| Nvidia GA104 High Definition Audio Controller                              | 16        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 2.1%    |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 1.97%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 1.97%   |
| Nvidia GA106 High Definition Audio Controller                              | 14        | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13        | 1.71%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12        | 1.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 1.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 1.57%   |
| Nvidia GA107 High Definition Audio Controller                              | 11        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.44%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 1.31%   |
| AMD FCH Azalia Controller                                                  | 10        | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.18%   |
| Nvidia AD107 High Definition Audio Controller                              | 8         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                              | 5         | 0.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.66%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 0.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 96        | 27.91%  |
| SK hynix            | 77        | 22.38%  |
| Micron Technology   | 50        | 14.53%  |
| Crucial             | 28        | 8.14%   |
| Kingston            | 22        | 6.4%    |
| Ramaxel Technology  | 10        | 2.91%   |
| A-DATA Technology   | 8         | 2.33%   |
| Corsair             | 7         | 2.03%   |
| Unknown             | 6         | 1.74%   |
| Unknown (ABCD)      | 5         | 1.45%   |
| Nanya Technology    | 5         | 1.45%   |
| Unknown             | 4         | 1.16%   |
| Smart               | 3         | 0.87%   |
| Transcend           | 2         | 0.58%   |
| Team                | 2         | 0.58%   |
| Patriot             | 2         | 0.58%   |
| Hewlett-Packard     | 2         | 0.58%   |
| Wilk                | 1         | 0.29%   |
| Unknown (0x0CAB)    | 1         | 0.29%   |
| Toshiba             | 1         | 0.29%   |
| Timetec             | 1         | 0.29%   |
| Smart Brazil        | 1         | 0.29%   |
| Sesame              | 1         | 0.29%   |
| PNY                 | 1         | 0.29%   |
| GOODRAM             | 1         | 0.29%   |
| G.Skill             | 1         | 0.29%   |
| Elpida              | 1         | 0.29%   |
| CSX                 | 1         | 0.29%   |
| Avant               | 1         | 0.29%   |
| Apacer              | 1         | 0.29%   |
| AMD                 | 1         | 0.29%   |
| 48spaces            | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 2.19%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 2.19%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 5         | 1.37%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.1%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.1%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 4         | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.1%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 4         | 1.1%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 1.1%    |
| Unknown                                                          | 4         | 1.1%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.82%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 3         | 0.82%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s                       | 3         | 0.82%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.82%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.82%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.55%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.55%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.55%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.55%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.55%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 169       | 58.48%  |
| DDR3   | 63        | 21.8%   |
| DDR5   | 21        | 7.27%   |
| LPDDR4 | 13        | 4.5%    |
| LPDDR5 | 11        | 3.81%   |
| LPDDR3 | 7         | 2.42%   |
| DDR2   | 4         | 1.38%   |
| SDRAM  | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 266       | 90.78%  |
| Row Of Chips | 25        | 8.53%   |
| Chip         | 1         | 0.34%   |
| Unknown      | 1         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 149       | 47%     |
| 4096  | 81        | 25.55%  |
| 16384 | 64        | 20.19%  |
| 32768 | 13        | 4.1%    |
| 2048  | 10        | 3.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 88        | 28.03%  |
| 2667  | 64        | 20.38%  |
| 1600  | 52        | 16.56%  |
| 2400  | 27        | 8.6%    |
| 4800  | 16        | 5.1%    |
| 2133  | 13        | 4.14%   |
| 1334  | 8         | 2.55%   |
| 6400  | 7         | 2.23%   |
| 4266  | 6         | 1.91%   |
| 5600  | 5         | 1.59%   |
| 1333  | 5         | 1.59%   |
| 3266  | 4         | 1.27%   |
| 8400  | 2         | 0.64%   |
| 7500  | 2         | 0.64%   |
| 2933  | 2         | 0.64%   |
| 1867  | 2         | 0.64%   |
| 800   | 2         | 0.64%   |
| 667   | 2         | 0.64%   |
| 7467  | 1         | 0.32%   |
| 4267  | 1         | 0.32%   |
| 4199  | 1         | 0.32%   |
| 3733  | 1         | 0.32%   |
| 2267  | 1         | 0.32%   |
| 1866  | 1         | 0.32%   |
| 1066  | 1         | 0.32%   |

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
| Chicony Electronics                    | 89        | 22.47%  |
| IMC Networks                           | 56        | 14.14%  |
| Quanta                                 | 34        | 8.59%   |
| Microdia                               | 29        | 7.32%   |
| Realtek Semiconductor                  | 28        | 7.07%   |
| Bison Electronics                      | 28        | 7.07%   |
| Sunplus Innovation Technology          | 19        | 4.8%    |
| Luxvisions Innotech Limited            | 16        | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.28%   |
| Apple                                  | 11        | 2.78%   |
| Syntek                                 | 9         | 2.27%   |
| Suyin                                  | 7         | 1.77%   |
| Sonix Technology                       | 7         | 1.77%   |
| Logitech                               | 6         | 1.52%   |
| Silicon Motion                         | 5         | 1.26%   |
| Lite-On Technology                     | 5         | 1.26%   |
| SunplusIT                              | 4         | 1.01%   |
| ShineTech                              | 4         | 1.01%   |
| Acer                                   | 4         | 1.01%   |
| Alcor Micro                            | 3         | 0.76%   |
| Samsung Electronics                    | 2         | 0.51%   |
| Primax Electronics                     | 2         | 0.51%   |
| Microsoft                              | 2         | 0.51%   |
| Lenovo                                 | 2         | 0.51%   |
| WaveRider Communications               | 1         | 0.25%   |
| Tobii Technology AB                    | 1         | 0.25%   |
| Shine-optics                           | 1         | 0.25%   |
| KYE Systems (Mouse Systems)            | 1         | 0.25%   |
| Intel                                  | 1         | 0.25%   |
| Importek                               | 1         | 0.25%   |
| icSpring                               | 1         | 0.25%   |
| Genesys Logic                          | 1         | 0.25%   |
| GEMBIRD                                | 1         | 0.25%   |
| DigiTech                               | 1         | 0.25%   |
| Creative Technology                    | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 27        | 6.78%   |
| Microdia Integrated_Webcam_HD                        | 18        | 4.52%   |
| IMC Networks Integrated Camera                       | 18        | 4.52%   |
| Chicony Integrated Camera                            | 16        | 4.02%   |
| Chicony HD Webcam                                    | 10        | 2.51%   |
| Sunplus Integrated_Webcam_HD                         | 9         | 2.26%   |
| Quanta HD User Facing                                | 8         | 2.01%   |
| Bison HD Webcam                                      | 8         | 2.01%   |
| Apple FaceTime HD Camera                             | 8         | 2.01%   |
| Syntek Integrated Camera                             | 7         | 1.76%   |
| Realtek Integrated_Webcam_HD                         | 7         | 1.76%   |
| Chicony HD User Facing                               | 7         | 1.76%   |
| Bison Integrated Camera                              | 7         | 1.76%   |
| Sonix USB2.0 HD UVC WebCam                           | 6         | 1.51%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 6         | 1.51%   |
| Chicony HP Wide Vision HD Camera                     | 6         | 1.51%   |
| Quanta HP Wide Vision HD Camera                      | 5         | 1.26%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 1.26%   |
| Chicony EasyCamera                                   | 5         | 1.26%   |
| ShineTech USB2.0 HD UVC WebCam                       | 4         | 1.01%   |
| Chicony Integrated HD WebCam                         | 4         | 1.01%   |
| Chicony Chicony USB2.0 Camera                        | 4         | 1.01%   |
| Quanta USB2.0 HD UVC WebCam                          | 3         | 0.75%   |
| Quanta HP TrueVision HD Camera                       | 3         | 0.75%   |
| Quanta ACER HD User Facing                           | 3         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera        | 3         | 0.75%   |
| Logitech HD Pro Webcam C920                          | 3         | 0.75%   |
| IMC Networks HD Camera                               | 3         | 0.75%   |
| Chicony USB 2.0 Camera                               | 3         | 0.75%   |
| Chicony HP Truevision HD                             | 3         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 3         | 0.75%   |
| Bison HD Camera                                      | 3         | 0.75%   |
| SunplusIT XiaoMi USB 2.0 Webcam                      | 2         | 0.5%    |
| Silicon Motion Web Camera                            | 2         | 0.5%    |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 0.5%    |
| Realtek USB2.0 camera                                | 2         | 0.5%    |
| Realtek USB Camera                                   | 2         | 0.5%    |
| Realtek Integrated Webcam HD                         | 2         | 0.5%    |
| Realtek Integrated Webcam                            | 2         | 0.5%    |
| Realtek HP Truevision HD                             | 2         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 31.25%  |
| Synaptics                  | 13        | 20.31%  |
| Elan Microelectronics      | 11        | 17.19%  |
| Shenzhen Goodix Technology | 7         | 10.94%  |
| LighTuning Technology      | 6         | 9.38%   |
| AuthenTec                  | 5         | 7.81%   |
| Focal-systems.Corp         | 2         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                           | 7         | 10.94%  |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 7.81%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 4         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.69%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 4.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 3.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.13%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.13%   |
| Synaptics WBDI Device                                                      | 2         | 3.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 3.13%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 3.13%   |
| AuthenTec AES2810                                                          | 2         | 3.13%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.56%   |
| Validity Sensors VFS491                                                    | 1         | 1.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.56%   |
| Synaptics WBDI                                                             | 1         | 1.56%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.56%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 1.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.56%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.56%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 16        | 51.61%  |
| Alcor Micro      | 9         | 29.03%  |
| Upek             | 3         | 9.68%   |
| Lenovo           | 2         | 6.45%   |
| SCM Microsystems | 1         | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 29.03%  |
| Broadcom 5880                                                                | 6         | 19.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 16.13%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 12.9%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 9.68%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.45%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 3.23%   |
| Broadcom 58200                                                               | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 241       | 52.85%  |
| 0     | 98        | 21.49%  |
| 2     | 97        | 21.27%  |
| 3     | 19        | 4.17%   |
| 4     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 304       | 61.41%  |
| Fingerprint reader       | 64        | 12.93%  |
| Graphics card            | 34        | 6.87%   |
| Chipcard                 | 30        | 6.06%   |
| Net/wireless             | 19        | 3.84%   |
| Multimedia controller    | 18        | 3.64%   |
| Camera                   | 8         | 1.62%   |
| Net/ethernet             | 6         | 1.21%   |
| Storage                  | 4         | 0.81%   |
| Network                  | 3         | 0.61%   |
| Bluetooth                | 2         | 0.4%    |
| Wireless                 | 1         | 0.2%    |
| Sound                    | 1         | 0.2%    |
| Modem                    | 1         | 0.2%    |

