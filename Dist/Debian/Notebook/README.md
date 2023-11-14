Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 8343

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8460p             | [cc6b66c576](https://linux-hardware.org/?probe=cc6b66c576) | Nov 06, 2023 |
| Aquarius      | NS585                       | [ddc8256647](https://linux-hardware.org/?probe=ddc8256647) | Nov 06, 2023 |
| Aquarius      | NS585                       | [2f4e49837d](https://linux-hardware.org/?probe=2f4e49837d) | Nov 06, 2023 |
| Aquarius      | NS585                       | [4fea63336a](https://linux-hardware.org/?probe=4fea63336a) | Nov 06, 2023 |
| HP            | 250 G7 Notebook PC          | [a2ad36d26c](https://linux-hardware.org/?probe=a2ad36d26c) | Nov 06, 2023 |
| Toshiba       | TECRA R950                  | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| HP            | Mini 210-3000               | [8b55a876a9](https://linux-hardware.org/?probe=8b55a876a9) | Nov 05, 2023 |
| Google        | Nami                        | [19c94b9484](https://linux-hardware.org/?probe=19c94b9484) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| HP            | EliteBook 840 G3            | [1bb894cf19](https://linux-hardware.org/?probe=1bb894cf19) | Nov 04, 2023 |
| HP            | Pavilion dv7                | [6a44cc2c3c](https://linux-hardware.org/?probe=6a44cc2c3c) | Nov 04, 2023 |
| Acer          | AO532h                      | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Google        | Bluebird                    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| Google        | Bluebird                    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | [bea6a6babf](https://linux-hardware.org/?probe=bea6a6babf) | Nov 04, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [0767db36fe](https://linux-hardware.org/?probe=0767db36fe) | Nov 04, 2023 |
| Dell          | Precision 7560              | [54a8deb305](https://linux-hardware.org/?probe=54a8deb305) | Nov 04, 2023 |
| ASUSTek       | X551CA                      | [20bee22e0a](https://linux-hardware.org/?probe=20bee22e0a) | Nov 03, 2023 |
| Packard Be... | EasyNote TK87               | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| Dell          | Latitude E6420              | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Google        | Enguarde                    | [bc6a541eb9](https://linux-hardware.org/?probe=bc6a541eb9) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| Lenovo        | G500s 20245                 | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1bdfa38b3e](https://linux-hardware.org/?probe=1bdfa38b3e) | Nov 03, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| ASUSTek       | X205TA                      | [b29e9ebfbe](https://linux-hardware.org/?probe=b29e9ebfbe) | Nov 03, 2023 |
| HP            | 250 G7 Notebook PC          | [1889111d8a](https://linux-hardware.org/?probe=1889111d8a) | Nov 03, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [212105774f](https://linux-hardware.org/?probe=212105774f) | Nov 02, 2023 |
| ASUSTek       | G750JX                      | [9493bec7e6](https://linux-hardware.org/?probe=9493bec7e6) | Nov 02, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [7c06ac2664](https://linux-hardware.org/?probe=7c06ac2664) | Nov 02, 2023 |
| Dell          | Vostro 14-3468              | [33a984f9f8](https://linux-hardware.org/?probe=33a984f9f8) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |
| Google        | Nasher360                   | [0d1cc1b584](https://linux-hardware.org/?probe=0d1cc1b584) | Nov 02, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [df4f43ca44](https://linux-hardware.org/?probe=df4f43ca44) | Nov 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [bb5bbc3e51](https://linux-hardware.org/?probe=bb5bbc3e51) | Nov 01, 2023 |
| Acer          | TravelMate P215-52          | [b9c3643e62](https://linux-hardware.org/?probe=b9c3643e62) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [ac563e5542](https://linux-hardware.org/?probe=ac563e5542) | Nov 01, 2023 |
| HP            | Laptop 15s-eq1xxx           | [075049b538](https://linux-hardware.org/?probe=075049b538) | Nov 01, 2023 |
| Dell          | Precision M4700             | [1d7e76c1d9](https://linux-hardware.org/?probe=1d7e76c1d9) | Nov 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [317aadad91](https://linux-hardware.org/?probe=317aadad91) | Nov 01, 2023 |
| Dell          | Vostro 5590                 | [300630cf8c](https://linux-hardware.org/?probe=300630cf8c) | Nov 01, 2023 |
| Dell          | Latitude 5480               | [1bf5aeba87](https://linux-hardware.org/?probe=1bf5aeba87) | Nov 01, 2023 |
| Toshiba       | Satellite L845              | [90e266bd8e](https://linux-hardware.org/?probe=90e266bd8e) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [2bdd27dc18](https://linux-hardware.org/?probe=2bdd27dc18) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [cb35a8d8f6](https://linux-hardware.org/?probe=cb35a8d8f6) | Oct 31, 2023 |
| HP            | 255 G8 Notebook PC          | [b9d1b13098](https://linux-hardware.org/?probe=b9d1b13098) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4ebd30711e](https://linux-hardware.org/?probe=4ebd30711e) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [a664733aaf](https://linux-hardware.org/?probe=a664733aaf) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [72131fb5de](https://linux-hardware.org/?probe=72131fb5de) | Oct 31, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [ea29ba4b58](https://linux-hardware.org/?probe=ea29ba4b58) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [5fc04a6d0a](https://linux-hardware.org/?probe=5fc04a6d0a) | Oct 31, 2023 |
| Lenovo        | ThinkPad X230 2325T55       | [bb4d04c61d](https://linux-hardware.org/?probe=bb4d04c61d) | Oct 31, 2023 |
| Apple         | MacBookPro9,1               | [8f7c5b801b](https://linux-hardware.org/?probe=8f7c5b801b) | Oct 31, 2023 |
| Apple         | MacBookPro9,1               | [4e15275faa](https://linux-hardware.org/?probe=4e15275faa) | Oct 31, 2023 |
| HP            | Victus by Gaming Laptop ... | [0f4fa9169b](https://linux-hardware.org/?probe=0f4fa9169b) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [40ae523147](https://linux-hardware.org/?probe=40ae523147) | Oct 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [2f63bfb399](https://linux-hardware.org/?probe=2f63bfb399) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [7e12621e6d](https://linux-hardware.org/?probe=7e12621e6d) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 14S           | [780e721e24](https://linux-hardware.org/?probe=780e721e24) | Oct 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [c4baf8a67b](https://linux-hardware.org/?probe=c4baf8a67b) | Oct 30, 2023 |
| THUNDEROBO... | 911AirD                     | [698adeeba7](https://linux-hardware.org/?probe=698adeeba7) | Oct 30, 2023 |
| Dell          | XPS 15 9520                 | [0fb7ced892](https://linux-hardware.org/?probe=0fb7ced892) | Oct 30, 2023 |
| Lenovo        | Flex 2 Pro-15               | [ff5f14115e](https://linux-hardware.org/?probe=ff5f14115e) | Oct 30, 2023 |
| Google        | Blooguard                   | [cd817fb666](https://linux-hardware.org/?probe=cd817fb666) | Oct 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [995b159589](https://linux-hardware.org/?probe=995b159589) | Oct 30, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| Gigabyte      | A5 X1                       | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | [586f08e1dc](https://linux-hardware.org/?probe=586f08e1dc) | Oct 30, 2023 |
| Lenovo        | ThinkPad 25 20K70000GE      | [ce13c83c47](https://linux-hardware.org/?probe=ce13c83c47) | Oct 29, 2023 |
| Lenovo        | ThinkPad 25 20K70000GE      | [597958381f](https://linux-hardware.org/?probe=597958381f) | Oct 29, 2023 |
| HP            | Pavilion g6                 | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [91f7b242b9](https://linux-hardware.org/?probe=91f7b242b9) | Oct 28, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| Acer          | Aspire 4752                 | [ce321700bc](https://linux-hardware.org/?probe=ce321700bc) | Oct 28, 2023 |
| Toshiba       | TECRA R950                  | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [dcd6988b7a](https://linux-hardware.org/?probe=dcd6988b7a) | Oct 28, 2023 |
| Acer          | Aspire A115-31              | [137821ca25](https://linux-hardware.org/?probe=137821ca25) | Oct 28, 2023 |
| TELECOMITA... | M7x0S                       | [feabc7e111](https://linux-hardware.org/?probe=feabc7e111) | Oct 28, 2023 |
| MSI           | WS63 7RK                    | [dcfa2c2f75](https://linux-hardware.org/?probe=dcfa2c2f75) | Oct 27, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d8bfe77d00](https://linux-hardware.org/?probe=d8bfe77d00) | Oct 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [198bee98eb](https://linux-hardware.org/?probe=198bee98eb) | Oct 27, 2023 |
| Lenovo        | G50-70 20351                | [39e2fb6be6](https://linux-hardware.org/?probe=39e2fb6be6) | Oct 27, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [67b966e75c](https://linux-hardware.org/?probe=67b966e75c) | Oct 27, 2023 |
| Google        | Enguarde                    | [074b44ce16](https://linux-hardware.org/?probe=074b44ce16) | Oct 26, 2023 |
| Acer          | Aspire 5750G                | [afe742ceca](https://linux-hardware.org/?probe=afe742ceca) | Oct 26, 2023 |
| Dell          | Latitude 5414               | [78fb4f9907](https://linux-hardware.org/?probe=78fb4f9907) | Oct 26, 2023 |
| Medion        | Unknown                     | [ffcdfb3003](https://linux-hardware.org/?probe=ffcdfb3003) | Oct 26, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B4I... | [afce107e0d](https://linux-hardware.org/?probe=afce107e0d) | Oct 26, 2023 |
| HP            | ProBook 4530s               | [b86df6ad72](https://linux-hardware.org/?probe=b86df6ad72) | Oct 26, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [cc3370083d](https://linux-hardware.org/?probe=cc3370083d) | Oct 26, 2023 |
| Exo           | Smart Serie R               | [d68b300ca7](https://linux-hardware.org/?probe=d68b300ca7) | Oct 26, 2023 |
| Toshiba       | Satellite L455D             | [29337c2310](https://linux-hardware.org/?probe=29337c2310) | Oct 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [303c4197c7](https://linux-hardware.org/?probe=303c4197c7) | Oct 26, 2023 |
| HP            | Compaq 15                   | [83fab35dec](https://linux-hardware.org/?probe=83fab35dec) | Oct 26, 2023 |
| Dell          | Latitude 5414               | [692b53f9d9](https://linux-hardware.org/?probe=692b53f9d9) | Oct 26, 2023 |
| HP            | Compaq 15                   | [41ada9e77d](https://linux-hardware.org/?probe=41ada9e77d) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bd6ab7e486](https://linux-hardware.org/?probe=bd6ab7e486) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bfe12f37dc](https://linux-hardware.org/?probe=bfe12f37dc) | Oct 25, 2023 |
| HP            | 15                          | [629c50d53a](https://linux-hardware.org/?probe=629c50d53a) | Oct 25, 2023 |
| Acer          | Aspire 5750G                | [b726b22da1](https://linux-hardware.org/?probe=b726b22da1) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [c66ebc8e70](https://linux-hardware.org/?probe=c66ebc8e70) | Oct 25, 2023 |
| Matsushita... | CF-30CTWAZBM                | [4211783dac](https://linux-hardware.org/?probe=4211783dac) | Oct 25, 2023 |
| Google        | Reks                        | [d397eae4e5](https://linux-hardware.org/?probe=d397eae4e5) | Oct 25, 2023 |
| Acer          | Aspire ES1-521              | [2df6fb3e2a](https://linux-hardware.org/?probe=2df6fb3e2a) | Oct 25, 2023 |
| MSI           | Katana GF76 11SC            | [b1a5449e72](https://linux-hardware.org/?probe=b1a5449e72) | Oct 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [71a22f4706](https://linux-hardware.org/?probe=71a22f4706) | Oct 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [8994962017](https://linux-hardware.org/?probe=8994962017) | Oct 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [b270ca3670](https://linux-hardware.org/?probe=b270ca3670) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [1406d2f4d5](https://linux-hardware.org/?probe=1406d2f4d5) | Oct 24, 2023 |
| Medion        | Unknown                     | [fa168b5e75](https://linux-hardware.org/?probe=fa168b5e75) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [56fa067caa](https://linux-hardware.org/?probe=56fa067caa) | Oct 24, 2023 |
| HP            | EliteBook 8740w             | [3669a01d21](https://linux-hardware.org/?probe=3669a01d21) | Oct 24, 2023 |
| Notebook      | P7xxDM(-G)                  | [bb211b2fb4](https://linux-hardware.org/?probe=bb211b2fb4) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | [0fb2b25961](https://linux-hardware.org/?probe=0fb2b25961) | Oct 24, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [dd704a643f](https://linux-hardware.org/?probe=dd704a643f) | Oct 24, 2023 |
| Acer          | Aspire 7750G                | [91006bdfa7](https://linux-hardware.org/?probe=91006bdfa7) | Oct 24, 2023 |
| Alienware     | m15 R6                      | [c6711f7b02](https://linux-hardware.org/?probe=c6711f7b02) | Oct 24, 2023 |
| ASUSTek       | G551JX                      | [db16c87fe8](https://linux-hardware.org/?probe=db16c87fe8) | Oct 24, 2023 |
| MSI           | GT62VR 6RD                  | [0d10c5251c](https://linux-hardware.org/?probe=0d10c5251c) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8754714bce](https://linux-hardware.org/?probe=8754714bce) | Oct 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [f4375f7115](https://linux-hardware.org/?probe=f4375f7115) | Oct 23, 2023 |
| Aquarius      | NS585                       | [3c793ad14b](https://linux-hardware.org/?probe=3c793ad14b) | Oct 23, 2023 |
| Aquarius      | NS585                       | [9e7366fb3a](https://linux-hardware.org/?probe=9e7366fb3a) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [c03a4ad29d](https://linux-hardware.org/?probe=c03a4ad29d) | Oct 23, 2023 |
| Timi          | Mi NoteBook Pro             | [470eb40837](https://linux-hardware.org/?probe=470eb40837) | Oct 23, 2023 |
| Acer          | Aspire E5-573               | [d83f4bf9ad](https://linux-hardware.org/?probe=d83f4bf9ad) | Oct 23, 2023 |
| HP            | Laptop 14s-dy5xxx           | [e873e5d24c](https://linux-hardware.org/?probe=e873e5d24c) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [4d383aebdc](https://linux-hardware.org/?probe=4d383aebdc) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [4cb151fdfe](https://linux-hardware.org/?probe=4cb151fdfe) | Oct 23, 2023 |
| Dell          | XPS 13 9300                 | [9d7ecc567c](https://linux-hardware.org/?probe=9d7ecc567c) | Oct 23, 2023 |
| Dell          | Precision 3571              | [a2ba806246](https://linux-hardware.org/?probe=a2ba806246) | Oct 22, 2023 |
| Dell          | Precision 3571              | [efedaee27d](https://linux-hardware.org/?probe=efedaee27d) | Oct 22, 2023 |
| Dell          | Inspiron 6000               | [be4108e195](https://linux-hardware.org/?probe=be4108e195) | Oct 22, 2023 |
| Dell          | XPS 15 9560                 | [c2c4d81d07](https://linux-hardware.org/?probe=c2c4d81d07) | Oct 22, 2023 |
| GPU Compan... | GWTC51427                   | [69b6cd7a6f](https://linux-hardware.org/?probe=69b6cd7a6f) | Oct 22, 2023 |
| Dell          | Vostro 14-3468              | [c9c6a8db9f](https://linux-hardware.org/?probe=c9c6a8db9f) | Oct 22, 2023 |
| Acer          | Swift SF314-42              | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Lenovo        | V130-15IGM 81HL             | [fc8d54a39c](https://linux-hardware.org/?probe=fc8d54a39c) | Oct 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [5e57624ceb](https://linux-hardware.org/?probe=5e57624ceb) | Oct 21, 2023 |
| Packard Be... | EasyNote TE11HC             | [dc33bae348](https://linux-hardware.org/?probe=dc33bae348) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f30ccc13f5](https://linux-hardware.org/?probe=f30ccc13f5) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d9a8c7946e](https://linux-hardware.org/?probe=d9a8c7946e) | Oct 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [5cac857cd9](https://linux-hardware.org/?probe=5cac857cd9) | Oct 20, 2023 |
| Lenovo        | V15-IIL 82C5                | [50f6d4cb01](https://linux-hardware.org/?probe=50f6d4cb01) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | [125e76df80](https://linux-hardware.org/?probe=125e76df80) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | [3a5c553fcb](https://linux-hardware.org/?probe=3a5c553fcb) | Oct 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2147efec4e](https://linux-hardware.org/?probe=2147efec4e) | Oct 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [423a16c64a](https://linux-hardware.org/?probe=423a16c64a) | Oct 20, 2023 |
| Dell          | G5 5505                     | [363d3c6d9c](https://linux-hardware.org/?probe=363d3c6d9c) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [64929e25f7](https://linux-hardware.org/?probe=64929e25f7) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [da8f06a8e0](https://linux-hardware.org/?probe=da8f06a8e0) | Oct 19, 2023 |
| Acer          | Aspire A315-34              | [1ec00092e6](https://linux-hardware.org/?probe=1ec00092e6) | Oct 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9c9781a7ee](https://linux-hardware.org/?probe=9c9781a7ee) | Oct 19, 2023 |
| Dell          | XPS 13 9380                 | [a108313537](https://linux-hardware.org/?probe=a108313537) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a8e2b482f4](https://linux-hardware.org/?probe=a8e2b482f4) | Oct 19, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [81bfadb2d9](https://linux-hardware.org/?probe=81bfadb2d9) | Oct 18, 2023 |
| Dell          | Precision 7560              | [847d5dfd06](https://linux-hardware.org/?probe=847d5dfd06) | Oct 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [8762d7b263](https://linux-hardware.org/?probe=8762d7b263) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | [5921ebc3f7](https://linux-hardware.org/?probe=5921ebc3f7) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | [b6619c64fd](https://linux-hardware.org/?probe=b6619c64fd) | Oct 18, 2023 |
| Dell          | Latitude E6420              | [f703c6bd74](https://linux-hardware.org/?probe=f703c6bd74) | Oct 17, 2023 |
| Dell          | Latitude E6430              | [54d411b12d](https://linux-hardware.org/?probe=54d411b12d) | Oct 17, 2023 |
| Google        | Reks                        | [1053eb8fee](https://linux-hardware.org/?probe=1053eb8fee) | Oct 17, 2023 |
| Google        | Reks                        | [84b42b74a0](https://linux-hardware.org/?probe=84b42b74a0) | Oct 17, 2023 |
| HP            | ProBook 645 G1              | [d1eeca057f](https://linux-hardware.org/?probe=d1eeca057f) | Oct 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [f9a0ba2cba](https://linux-hardware.org/?probe=f9a0ba2cba) | Oct 17, 2023 |
| Unknown       | Unknown                     | [f776cdb186](https://linux-hardware.org/?probe=f776cdb186) | Oct 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [902d95cec2](https://linux-hardware.org/?probe=902d95cec2) | Oct 17, 2023 |
| HP            | EliteBook 820 G2            | [14f5dbdc5a](https://linux-hardware.org/?probe=14f5dbdc5a) | Oct 17, 2023 |
| Acer          | Aspire V3-771               | [e56b3d3602](https://linux-hardware.org/?probe=e56b3d3602) | Oct 17, 2023 |
| Acer          | Aspire 7750G                | [6c7f890049](https://linux-hardware.org/?probe=6c7f890049) | Oct 17, 2023 |
| Acer          | Aspire A515-54              | [a89d6c8f24](https://linux-hardware.org/?probe=a89d6c8f24) | Oct 17, 2023 |
| Dell          | Precision 7560              | [5d9dd29a22](https://linux-hardware.org/?probe=5d9dd29a22) | Oct 17, 2023 |
| Juana Mans... | SF20GM7                     | [ea7e37eb5d](https://linux-hardware.org/?probe=ea7e37eb5d) | Oct 17, 2023 |
| Google        | Reks                        | [7610580a91](https://linux-hardware.org/?probe=7610580a91) | Oct 16, 2023 |
| HP            | Laptop 15-fd0xxx            | [0e6cc9fc48](https://linux-hardware.org/?probe=0e6cc9fc48) | Oct 16, 2023 |
| Acer          | Aspire 7750G                | [2a2d5e2425](https://linux-hardware.org/?probe=2a2d5e2425) | Oct 16, 2023 |
| ASUSTek       | 1015PN                      | [b6cbd56a75](https://linux-hardware.org/?probe=b6cbd56a75) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | [abfce57204](https://linux-hardware.org/?probe=abfce57204) | Oct 16, 2023 |
| Lenovo        | ThinkPad E565 20EY000XUK    | [b7cf6113c4](https://linux-hardware.org/?probe=b7cf6113c4) | Oct 16, 2023 |
| HUAWEI        | HVY-WXX9                    | [57e0cf4149](https://linux-hardware.org/?probe=57e0cf4149) | Oct 16, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [2408be3605](https://linux-hardware.org/?probe=2408be3605) | Oct 16, 2023 |
| Dell          | Inspiron 5567               | [d632a645e1](https://linux-hardware.org/?probe=d632a645e1) | Oct 16, 2023 |
| MSI           | GF63 Thin 11SC              | [1072e8d802](https://linux-hardware.org/?probe=1072e8d802) | Oct 16, 2023 |
| HP            | 250 G8 Notebook PC          | [38c84587d8](https://linux-hardware.org/?probe=38c84587d8) | Oct 16, 2023 |
| Apple         | MacBookAir4,1               | [f63091b76b](https://linux-hardware.org/?probe=f63091b76b) | Oct 16, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [33ce923fc9](https://linux-hardware.org/?probe=33ce923fc9) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| HP            | 15                          | [7cde663ae0](https://linux-hardware.org/?probe=7cde663ae0) | Oct 15, 2023 |
| Lenovo        | G50-70 20351                | [bdd8aeaf43](https://linux-hardware.org/?probe=bdd8aeaf43) | Oct 14, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [50ebc1407b](https://linux-hardware.org/?probe=50ebc1407b) | Oct 14, 2023 |
| HUAWEI        | KLVD-WXX9                   | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| Dell          | Inspiron 3501               | [a1ada382fa](https://linux-hardware.org/?probe=a1ada382fa) | Oct 14, 2023 |
| Dell          | Latitude 5400               | [26c8a94f7f](https://linux-hardware.org/?probe=26c8a94f7f) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [f35263745a](https://linux-hardware.org/?probe=f35263745a) | Oct 14, 2023 |
| Dell          | Latitude 5414               | [2984ae5140](https://linux-hardware.org/?probe=2984ae5140) | Oct 14, 2023 |
| Google        | Reks                        | [066e8305fe](https://linux-hardware.org/?probe=066e8305fe) | Oct 13, 2023 |
| Google        | Reks                        | [acb8eb7f44](https://linux-hardware.org/?probe=acb8eb7f44) | Oct 13, 2023 |
| Google        | Reks                        | [707eb71f31](https://linux-hardware.org/?probe=707eb71f31) | Oct 13, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [94e6d9d3cb](https://linux-hardware.org/?probe=94e6d9d3cb) | Oct 13, 2023 |
| Google        | Reks                        | [4bc10c8b6b](https://linux-hardware.org/?probe=4bc10c8b6b) | Oct 13, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | [5298e96c35](https://linux-hardware.org/?probe=5298e96c35) | Oct 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7ee4351584](https://linux-hardware.org/?probe=7ee4351584) | Oct 13, 2023 |
| Apple         | MacBookPro9,2               | [27b7cf72ac](https://linux-hardware.org/?probe=27b7cf72ac) | Oct 13, 2023 |
| Dell          | Latitude E6520              | [30a511af92](https://linux-hardware.org/?probe=30a511af92) | Oct 13, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [02c3723dae](https://linux-hardware.org/?probe=02c3723dae) | Oct 12, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d874291459](https://linux-hardware.org/?probe=d874291459) | Oct 12, 2023 |
| Toshiba       | Satellite L755              | [679e27a869](https://linux-hardware.org/?probe=679e27a869) | Oct 12, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b53da36041](https://linux-hardware.org/?probe=b53da36041) | Oct 12, 2023 |
| Google        | Reks                        | [20f8a11067](https://linux-hardware.org/?probe=20f8a11067) | Oct 12, 2023 |
| Google        | Reks                        | [4e35f7ebe4](https://linux-hardware.org/?probe=4e35f7ebe4) | Oct 12, 2023 |
| Google        | Reks                        | [41c6c948bb](https://linux-hardware.org/?probe=41c6c948bb) | Oct 12, 2023 |
| ASUSTek       | X541UJ                      | [c061e67481](https://linux-hardware.org/?probe=c061e67481) | Oct 12, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [24adbfd09a](https://linux-hardware.org/?probe=24adbfd09a) | Oct 11, 2023 |
| Google        | Reks                        | [1854f5e2fb](https://linux-hardware.org/?probe=1854f5e2fb) | Oct 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9de2f282f8](https://linux-hardware.org/?probe=9de2f282f8) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [dc4ce65d14](https://linux-hardware.org/?probe=dc4ce65d14) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [c26fe51dd5](https://linux-hardware.org/?probe=c26fe51dd5) | Oct 11, 2023 |
| Google        | Reks                        | [f9857342ec](https://linux-hardware.org/?probe=f9857342ec) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [4a0728b60c](https://linux-hardware.org/?probe=4a0728b60c) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [63c9bedd9d](https://linux-hardware.org/?probe=63c9bedd9d) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [77fe4b27cf](https://linux-hardware.org/?probe=77fe4b27cf) | Oct 11, 2023 |
| Google        | Reks                        | [9b2d9c0f7c](https://linux-hardware.org/?probe=9b2d9c0f7c) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [a735df7685](https://linux-hardware.org/?probe=a735df7685) | Oct 11, 2023 |
| Google        | Reks                        | [e78d454248](https://linux-hardware.org/?probe=e78d454248) | Oct 11, 2023 |
| Google        | Reks                        | [e7c6590991](https://linux-hardware.org/?probe=e7c6590991) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [627ce99f24](https://linux-hardware.org/?probe=627ce99f24) | Oct 11, 2023 |
| Google        | Reks                        | [cc53305ade](https://linux-hardware.org/?probe=cc53305ade) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d957b0375b](https://linux-hardware.org/?probe=d957b0375b) | Oct 11, 2023 |
| Google        | Reks                        | [286fdb3692](https://linux-hardware.org/?probe=286fdb3692) | Oct 11, 2023 |
| ASUSTek       | X541UJ                      | [0cb7dbb73b](https://linux-hardware.org/?probe=0cb7dbb73b) | Oct 11, 2023 |
| HP            | Laptop 15-fc0xxx            | [670b2194c0](https://linux-hardware.org/?probe=670b2194c0) | Oct 11, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cf3225396c](https://linux-hardware.org/?probe=cf3225396c) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| Prestigio     | Visconte Quad 3GK           | [5ffdb7e479](https://linux-hardware.org/?probe=5ffdb7e479) | Oct 11, 2023 |
| Google        | Reks                        | [4bd21164ba](https://linux-hardware.org/?probe=4bd21164ba) | Oct 10, 2023 |
| Google        | Reks                        | [e574b981ae](https://linux-hardware.org/?probe=e574b981ae) | Oct 10, 2023 |
| Google        | Reks                        | [5d44d0021b](https://linux-hardware.org/?probe=5d44d0021b) | Oct 10, 2023 |
| Google        | Reks                        | [a4300f1369](https://linux-hardware.org/?probe=a4300f1369) | Oct 10, 2023 |
| HP            | 15                          | [5dc6c32647](https://linux-hardware.org/?probe=5dc6c32647) | Oct 10, 2023 |
| Google        | Reks                        | [9b338e1cfb](https://linux-hardware.org/?probe=9b338e1cfb) | Oct 10, 2023 |
| Google        | Reks                        | [8c2146eff1](https://linux-hardware.org/?probe=8c2146eff1) | Oct 10, 2023 |
| Google        | Reks                        | [2d878f9b40](https://linux-hardware.org/?probe=2d878f9b40) | Oct 10, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [8ca2bf7fc9](https://linux-hardware.org/?probe=8ca2bf7fc9) | Oct 10, 2023 |
| Google        | Reks                        | [b206e1538b](https://linux-hardware.org/?probe=b206e1538b) | Oct 10, 2023 |
| Google        | Reks                        | [3cf1a391be](https://linux-hardware.org/?probe=3cf1a391be) | Oct 10, 2023 |
| Google        | Reks                        | [d694213be1](https://linux-hardware.org/?probe=d694213be1) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [f91905858e](https://linux-hardware.org/?probe=f91905858e) | Oct 10, 2023 |
| HUAWEI        | KLVL-WXXW                   | [3f6528d99d](https://linux-hardware.org/?probe=3f6528d99d) | Oct 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c1c56db09e](https://linux-hardware.org/?probe=c1c56db09e) | Oct 10, 2023 |
| Dell          | XPS 15 9570                 | [a40dbac784](https://linux-hardware.org/?probe=a40dbac784) | Oct 09, 2023 |
| ASUSTek       | N751JK                      | [855d2e95a7](https://linux-hardware.org/?probe=855d2e95a7) | Oct 09, 2023 |
| Dell          | XPS 15 9570                 | [d6aaf4c55d](https://linux-hardware.org/?probe=d6aaf4c55d) | Oct 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f95efe1e80](https://linux-hardware.org/?probe=f95efe1e80) | Oct 09, 2023 |
| Toshiba       | Satellite L755              | [74a043fcf5](https://linux-hardware.org/?probe=74a043fcf5) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [b3635689de](https://linux-hardware.org/?probe=b3635689de) | Oct 09, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [825a1ee4bb](https://linux-hardware.org/?probe=825a1ee4bb) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6d2a6c2a6f](https://linux-hardware.org/?probe=6d2a6c2a6f) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3c54fe835e](https://linux-hardware.org/?probe=3c54fe835e) | Oct 09, 2023 |
| MSI           | Katana GF66 11UG            | [0816e0912b](https://linux-hardware.org/?probe=0816e0912b) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a41b75e081](https://linux-hardware.org/?probe=a41b75e081) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [ac6149e371](https://linux-hardware.org/?probe=ac6149e371) | Oct 08, 2023 |
| TUXEDO        | InfinityBook S 14 v5        | [7ad7f14fea](https://linux-hardware.org/?probe=7ad7f14fea) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [e6ba7d9115](https://linux-hardware.org/?probe=e6ba7d9115) | Oct 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [91f26dd2c7](https://linux-hardware.org/?probe=91f26dd2c7) | Oct 08, 2023 |
| Acer          | Swift SF314-56G             | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| AXDIA Inte... | MYBOOK PRO 14 SE            | [344ed10ccd](https://linux-hardware.org/?probe=344ed10ccd) | Oct 07, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | [881454bd02](https://linux-hardware.org/?probe=881454bd02) | Oct 07, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [a830045a2a](https://linux-hardware.org/?probe=a830045a2a) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [cae6954f11](https://linux-hardware.org/?probe=cae6954f11) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [ca68af85fb](https://linux-hardware.org/?probe=ca68af85fb) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [f6a5a046b6](https://linux-hardware.org/?probe=f6a5a046b6) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [c7e6160070](https://linux-hardware.org/?probe=c7e6160070) | Oct 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [71bc4e1d3f](https://linux-hardware.org/?probe=71bc4e1d3f) | Oct 07, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [45be4f4f29](https://linux-hardware.org/?probe=45be4f4f29) | Oct 07, 2023 |
| Dell          | Latitude E6520              | [fea9ed801a](https://linux-hardware.org/?probe=fea9ed801a) | Oct 07, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [37eeaf5771](https://linux-hardware.org/?probe=37eeaf5771) | Oct 06, 2023 |
| Toshiba       | Satellite L755              | [63ad812f2f](https://linux-hardware.org/?probe=63ad812f2f) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [275c59d0de](https://linux-hardware.org/?probe=275c59d0de) | Oct 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [76449d7977](https://linux-hardware.org/?probe=76449d7977) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [212dd29010](https://linux-hardware.org/?probe=212dd29010) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5928c10f4a](https://linux-hardware.org/?probe=5928c10f4a) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [3bc146338b](https://linux-hardware.org/?probe=3bc146338b) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [82b7f17c90](https://linux-hardware.org/?probe=82b7f17c90) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5f740996ed](https://linux-hardware.org/?probe=5f740996ed) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [64ffddf53c](https://linux-hardware.org/?probe=64ffddf53c) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [26bb748122](https://linux-hardware.org/?probe=26bb748122) | Oct 06, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [a9fb0ad7d5](https://linux-hardware.org/?probe=a9fb0ad7d5) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5f9cd4dfbe](https://linux-hardware.org/?probe=5f9cd4dfbe) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [7f948138a8](https://linux-hardware.org/?probe=7f948138a8) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9b11272e7a](https://linux-hardware.org/?probe=9b11272e7a) | Oct 06, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [aaa295fa26](https://linux-hardware.org/?probe=aaa295fa26) | Oct 06, 2023 |
| Dell          | Latitude 7275               | [f1892c721d](https://linux-hardware.org/?probe=f1892c721d) | Oct 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1c741fc115](https://linux-hardware.org/?probe=1c741fc115) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [50fc69b25f](https://linux-hardware.org/?probe=50fc69b25f) | Oct 06, 2023 |
| Toshiba       | Satellite A205              | [7b78b2ea5b](https://linux-hardware.org/?probe=7b78b2ea5b) | Oct 06, 2023 |
| HP            | ZBook 14 G2                 | [e1b3f48f3c](https://linux-hardware.org/?probe=e1b3f48f3c) | Oct 05, 2023 |
| Exo           | Smart Serie L               | [812041d985](https://linux-hardware.org/?probe=812041d985) | Oct 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fc37084670](https://linux-hardware.org/?probe=fc37084670) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [763ef47e79](https://linux-hardware.org/?probe=763ef47e79) | Oct 05, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [1edb630be1](https://linux-hardware.org/?probe=1edb630be1) | Oct 05, 2023 |
| Dell          | Vostro 3490                 | [83f825d43e](https://linux-hardware.org/?probe=83f825d43e) | Oct 05, 2023 |
| Dell          | Latitude 7290               | [8822662fb7](https://linux-hardware.org/?probe=8822662fb7) | Oct 05, 2023 |
| Acer          | Aspire V5-531               | [555d578f86](https://linux-hardware.org/?probe=555d578f86) | Oct 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8ba8fa3184](https://linux-hardware.org/?probe=8ba8fa3184) | Oct 05, 2023 |
| Acer          | Aspire A317-54              | [12732988d1](https://linux-hardware.org/?probe=12732988d1) | Oct 05, 2023 |
| HP            | EliteBook 735 G6            | [94ac6e4439](https://linux-hardware.org/?probe=94ac6e4439) | Oct 04, 2023 |
| Philco Inf... | EC10IS2                     | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [258d726766](https://linux-hardware.org/?probe=258d726766) | Oct 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [bf9ddbe725](https://linux-hardware.org/?probe=bf9ddbe725) | Oct 04, 2023 |
| Lenovo        | ThinkPad P51 20HJS0RE02     | [892c35359f](https://linux-hardware.org/?probe=892c35359f) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [03949619e9](https://linux-hardware.org/?probe=03949619e9) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [627e882ad2](https://linux-hardware.org/?probe=627e882ad2) | Oct 04, 2023 |
| HP            | ZBook 17 G4                 | [ead2e4611e](https://linux-hardware.org/?probe=ead2e4611e) | Oct 04, 2023 |
| Acer          | Swift SF314-43              | [36d6c2e275](https://linux-hardware.org/?probe=36d6c2e275) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [82820de211](https://linux-hardware.org/?probe=82820de211) | Oct 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [db7fa034a7](https://linux-hardware.org/?probe=db7fa034a7) | Oct 03, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [e80a668fc3](https://linux-hardware.org/?probe=e80a668fc3) | Oct 03, 2023 |
| Acer          | Aspire V5-531               | [b6a9eaaec5](https://linux-hardware.org/?probe=b6a9eaaec5) | Oct 03, 2023 |
| Unknown       | Unknown                     | [a6849f7516](https://linux-hardware.org/?probe=a6849f7516) | Oct 03, 2023 |
| Notebook      | W65_67SJ                    | [4de813ee21](https://linux-hardware.org/?probe=4de813ee21) | Oct 03, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [48ee75db0b](https://linux-hardware.org/?probe=48ee75db0b) | Oct 03, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9c6c3cf92b](https://linux-hardware.org/?probe=9c6c3cf92b) | Oct 03, 2023 |
| Toshiba       | Satellite P75-A             | [10da36f2b7](https://linux-hardware.org/?probe=10da36f2b7) | Oct 03, 2023 |
| Lenovo        | ThinkPad E580 20KS003WUS    | [5aed5aaa9b](https://linux-hardware.org/?probe=5aed5aaa9b) | Oct 03, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [fc95f3feef](https://linux-hardware.org/?probe=fc95f3feef) | Oct 03, 2023 |
| Lenovo        | ThinkPad T450 20BUA007SG    | [85af04a1cc](https://linux-hardware.org/?probe=85af04a1cc) | Oct 03, 2023 |
| Acer          | TravelMate P414-51          | [520fe0b494](https://linux-hardware.org/?probe=520fe0b494) | Oct 03, 2023 |
| Acer          | Swift SF314-56G             | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [3a8b2b229a](https://linux-hardware.org/?probe=3a8b2b229a) | Oct 03, 2023 |
| Dell          | Wyse 5470                   | [301b504179](https://linux-hardware.org/?probe=301b504179) | Oct 03, 2023 |
| Google        | Reks                        | [00fe240f8b](https://linux-hardware.org/?probe=00fe240f8b) | Oct 02, 2023 |
| Google        | Reks                        | [c4dc39039e](https://linux-hardware.org/?probe=c4dc39039e) | Oct 02, 2023 |
| Google        | Reks                        | [0d9a805f5a](https://linux-hardware.org/?probe=0d9a805f5a) | Oct 02, 2023 |
| Google        | Reks                        | [22c6ac7ba8](https://linux-hardware.org/?probe=22c6ac7ba8) | Oct 02, 2023 |
| Google        | Reks                        | [0db25d0a2f](https://linux-hardware.org/?probe=0db25d0a2f) | Oct 02, 2023 |
| Dell          | Vostro 3500                 | [8624a6479e](https://linux-hardware.org/?probe=8624a6479e) | Oct 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [9637400928](https://linux-hardware.org/?probe=9637400928) | Oct 02, 2023 |
| Compaq        | 420                         | [b327579e60](https://linux-hardware.org/?probe=b327579e60) | Oct 02, 2023 |
| VALE          | Notebook Classic C140       | [0516711124](https://linux-hardware.org/?probe=0516711124) | Oct 02, 2023 |
| Google        | Treeya                      | [b2251358a1](https://linux-hardware.org/?probe=b2251358a1) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [cc181da4e1](https://linux-hardware.org/?probe=cc181da4e1) | Oct 02, 2023 |
| MSI           | GF63 Thin 9SC               | [3670f5ea70](https://linux-hardware.org/?probe=3670f5ea70) | Oct 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a3773ae099](https://linux-hardware.org/?probe=a3773ae099) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [f35e389d78](https://linux-hardware.org/?probe=f35e389d78) | Oct 02, 2023 |
| IX1401        | Unknown                     | [8014a1028b](https://linux-hardware.org/?probe=8014a1028b) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| Teclast       | F15Plus 2                   | [3779ac7003](https://linux-hardware.org/?probe=3779ac7003) | Oct 01, 2023 |
| HP            | Presario CQ57               | [e83f052dc8](https://linux-hardware.org/?probe=e83f052dc8) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480 20L6SA5Q2V    | [d9262b2225](https://linux-hardware.org/?probe=d9262b2225) | Oct 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [6443df8957](https://linux-hardware.org/?probe=6443df8957) | Oct 01, 2023 |
| Acer          | Aspire E1-571               | [2e7aba6432](https://linux-hardware.org/?probe=2e7aba6432) | Oct 01, 2023 |
| Packard Be... | EasyNote LM98               | [8fdf8eee6c](https://linux-hardware.org/?probe=8fdf8eee6c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| Acer          | AOA150                      | [969a729098](https://linux-hardware.org/?probe=969a729098) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [ed7bf5aee1](https://linux-hardware.org/?probe=ed7bf5aee1) | Oct 01, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [e7dad368d2](https://linux-hardware.org/?probe=e7dad368d2) | Sep 30, 2023 |
| Dell          | Latitude 5410               | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [de3079ae33](https://linux-hardware.org/?probe=de3079ae33) | Sep 30, 2023 |
| IX1401        | Unknown                     | [c77c1d010e](https://linux-hardware.org/?probe=c77c1d010e) | Sep 30, 2023 |
| HP            | Pavilion dv5                | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Alienware     | m15 R4                      | [a67899ed06](https://linux-hardware.org/?probe=a67899ed06) | Sep 30, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [703170e428](https://linux-hardware.org/?probe=703170e428) | Sep 30, 2023 |
| HP            | Notebook                    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| HP            | ProBook 450 G1              | [1cbae5b56a](https://linux-hardware.org/?probe=1cbae5b56a) | Sep 29, 2023 |
| HP            | Pavilion dv9000 (GA359UA... | [cea70d5f75](https://linux-hardware.org/?probe=cea70d5f75) | Sep 29, 2023 |
| Dell          | Latitude 5410               | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Lenovo        | ThinkPad T500 22439AG       | [e5a2cd9816](https://linux-hardware.org/?probe=e5a2cd9816) | Sep 29, 2023 |
| Lenovo        | ThinkPad E490 20N8000SRT    | [274b3b5210](https://linux-hardware.org/?probe=274b3b5210) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [1fcc841148](https://linux-hardware.org/?probe=1fcc841148) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [3cb2bdba37](https://linux-hardware.org/?probe=3cb2bdba37) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | [2668770971](https://linux-hardware.org/?probe=2668770971) | Sep 27, 2023 |
| Fujitsu       | LIFEBOOK E4512              | [08b39b38bd](https://linux-hardware.org/?probe=08b39b38bd) | Sep 27, 2023 |
| ASUSTek       | K50IJ                       | [8556633dad](https://linux-hardware.org/?probe=8556633dad) | Sep 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [1317c1f1a9](https://linux-hardware.org/?probe=1317c1f1a9) | Sep 27, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [1a472d3072](https://linux-hardware.org/?probe=1a472d3072) | Sep 27, 2023 |
| Dell          | Latitude E6530              | [40cdcd2545](https://linux-hardware.org/?probe=40cdcd2545) | Sep 27, 2023 |
| Acer          | Aspire 5951G                | [cae145acab](https://linux-hardware.org/?probe=cae145acab) | Sep 26, 2023 |
| Dell          | Vostro 14-3468              | [3fceb34932](https://linux-hardware.org/?probe=3fceb34932) | Sep 26, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d406193722](https://linux-hardware.org/?probe=d406193722) | Sep 26, 2023 |
| Dell          | Vostro 14-3468              | [a027aae826](https://linux-hardware.org/?probe=a027aae826) | Sep 26, 2023 |
| Dell          | XPS 9315                    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| Lenovo        | ThinkPad T420 4236EV9       | [d621ecd81f](https://linux-hardware.org/?probe=d621ecd81f) | Sep 26, 2023 |
| Lenovo        | ThinkPad L540 20AUS00N00    | [a8aee3f386](https://linux-hardware.org/?probe=a8aee3f386) | Sep 26, 2023 |
| Aquarius      | NS585                       | [ce1c1d6e56](https://linux-hardware.org/?probe=ce1c1d6e56) | Sep 26, 2023 |
| Acer          | Aspire A515-47              | [3c1e418bf0](https://linux-hardware.org/?probe=3c1e418bf0) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [9e9ff26362](https://linux-hardware.org/?probe=9e9ff26362) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | [b047457fd1](https://linux-hardware.org/?probe=b047457fd1) | Sep 25, 2023 |
| Dell          | XPS 15 9560                 | [a524453c71](https://linux-hardware.org/?probe=a524453c71) | Sep 25, 2023 |
| Lenovo        | G710 20252                  | [d7926809d7](https://linux-hardware.org/?probe=d7926809d7) | Sep 25, 2023 |
| HP            | Presario CQ43               | [c206dc84ad](https://linux-hardware.org/?probe=c206dc84ad) | Sep 25, 2023 |
| Aquarius      | NS585                       | [e901467e39](https://linux-hardware.org/?probe=e901467e39) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ab332c2dcb](https://linux-hardware.org/?probe=ab332c2dcb) | Sep 25, 2023 |
| Acer          | Aspire 5951G                | [4c50b8e9b0](https://linux-hardware.org/?probe=4c50b8e9b0) | Sep 25, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0CN0... | [9c0b702e21](https://linux-hardware.org/?probe=9c0b702e21) | Sep 24, 2023 |
| Dell          | XPS 15 9500                 | [fcff405070](https://linux-hardware.org/?probe=fcff405070) | Sep 24, 2023 |
| Dell          | XPS 15 9500                 | [5bedca0fe9](https://linux-hardware.org/?probe=5bedca0fe9) | Sep 24, 2023 |
| Valve         | Jupiter                     | [36fd2d4d96](https://linux-hardware.org/?probe=36fd2d4d96) | Sep 24, 2023 |
| Dell          | Latitude 5420               | [0e22f551b9](https://linux-hardware.org/?probe=0e22f551b9) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| HP            | 250 G4                      | [c9dac1b4d5](https://linux-hardware.org/?probe=c9dac1b4d5) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42309ddc8c](https://linux-hardware.org/?probe=42309ddc8c) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Vostro 14-3468              | [0b6bdbbecb](https://linux-hardware.org/?probe=0b6bdbbecb) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb276947f2](https://linux-hardware.org/?probe=eb276947f2) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [574c2193bb](https://linux-hardware.org/?probe=574c2193bb) | Sep 23, 2023 |
| Acer          | Nitro AN515-58              | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [e273beb83a](https://linux-hardware.org/?probe=e273beb83a) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ad1b8126d2](https://linux-hardware.org/?probe=ad1b8126d2) | Sep 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [0d786ffd74](https://linux-hardware.org/?probe=0d786ffd74) | Sep 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| Dell          | Latitude 3320               | [cf413808cb](https://linux-hardware.org/?probe=cf413808cb) | Sep 22, 2023 |
| Dell          | Latitude 3320               | [bd39ee30ac](https://linux-hardware.org/?probe=bd39ee30ac) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e75a2a8b71](https://linux-hardware.org/?probe=e75a2a8b71) | Sep 22, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [c14178c7fa](https://linux-hardware.org/?probe=c14178c7fa) | Sep 22, 2023 |
| Samsung       | R505                        | [8aef37cda9](https://linux-hardware.org/?probe=8aef37cda9) | Sep 22, 2023 |
| ASUSTek       | X555LJ                      | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| HP            | EliteBook 840 G3            | [b6379ef77c](https://linux-hardware.org/?probe=b6379ef77c) | Sep 22, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [ea491d194f](https://linux-hardware.org/?probe=ea491d194f) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e33bb92eb6](https://linux-hardware.org/?probe=e33bb92eb6) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e337cc85e5](https://linux-hardware.org/?probe=e337cc85e5) | Sep 20, 2023 |
| Acer          | Aspire E1-531               | [f0173f0458](https://linux-hardware.org/?probe=f0173f0458) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [228d31bf59](https://linux-hardware.org/?probe=228d31bf59) | Sep 20, 2023 |
| Dell          | XPS 13 9300                 | [49bb68e979](https://linux-hardware.org/?probe=49bb68e979) | Sep 20, 2023 |
| HP            | ProBook 450 G1              | [4e5ae95013](https://linux-hardware.org/?probe=4e5ae95013) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| Dell          | Precision 5560              | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5662d8f95c](https://linux-hardware.org/?probe=5662d8f95c) | Sep 20, 2023 |
| Dell          | Precision 7550              | [75394df91f](https://linux-hardware.org/?probe=75394df91f) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [963330511d](https://linux-hardware.org/?probe=963330511d) | Sep 19, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a5f79b33f4](https://linux-hardware.org/?probe=a5f79b33f4) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [b302c7b008](https://linux-hardware.org/?probe=b302c7b008) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [ec386099b2](https://linux-hardware.org/?probe=ec386099b2) | Sep 19, 2023 |
| HP            | Laptop 17-cp0xxx            | [05e3350e1f](https://linux-hardware.org/?probe=05e3350e1f) | Sep 19, 2023 |
| Dell          | XPS 13 9360                 | [149f246bd7](https://linux-hardware.org/?probe=149f246bd7) | Sep 19, 2023 |
| Acer          | Aspire A515-56              | [db16273e72](https://linux-hardware.org/?probe=db16273e72) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [af446fcb4d](https://linux-hardware.org/?probe=af446fcb4d) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [eae124fa61](https://linux-hardware.org/?probe=eae124fa61) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [5f8df7dfcb](https://linux-hardware.org/?probe=5f8df7dfcb) | Sep 19, 2023 |
| Dell          | Latitude E6430              | [d83d7bbfa8](https://linux-hardware.org/?probe=d83d7bbfa8) | Sep 18, 2023 |
| HP            | 15                          | [b016d5ee79](https://linux-hardware.org/?probe=b016d5ee79) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [ebfe5ca0b0](https://linux-hardware.org/?probe=ebfe5ca0b0) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| Aquarius      | NS585                       | [6ac8bd5909](https://linux-hardware.org/?probe=6ac8bd5909) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Acer          | TravelMate P446-MG          | [08d9d6868b](https://linux-hardware.org/?probe=08d9d6868b) | Sep 17, 2023 |
| Google        | Droid                       | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| HP            | Compaq Mini 311-1100        | [8bdfb6307c](https://linux-hardware.org/?probe=8bdfb6307c) | Sep 17, 2023 |
| HP            | Laptop 15-dw3xxx            | [f84a480b09](https://linux-hardware.org/?probe=f84a480b09) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cda370cdc3](https://linux-hardware.org/?probe=cda370cdc3) | Sep 16, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [b7c1a0a0a0](https://linux-hardware.org/?probe=b7c1a0a0a0) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [f5884967d0](https://linux-hardware.org/?probe=f5884967d0) | Sep 16, 2023 |
| Dell          | Latitude E5570              | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| Dell          | Precision 5570              | [8b3c21b110](https://linux-hardware.org/?probe=8b3c21b110) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [66b29aeb1d](https://linux-hardware.org/?probe=66b29aeb1d) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| ASUSTek       | X507UB                      | [ca19710375](https://linux-hardware.org/?probe=ca19710375) | Sep 15, 2023 |
| ASUSTek       | X751LN                      | [77ecc965aa](https://linux-hardware.org/?probe=77ecc965aa) | Sep 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffb2a765f](https://linux-hardware.org/?probe=0ffb2a765f) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| Dell          | Latitude 5440               | [93a296a628](https://linux-hardware.org/?probe=93a296a628) | Sep 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [033eca4030](https://linux-hardware.org/?probe=033eca4030) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| HP            | ProBook 6570b               | [fc5c01d215](https://linux-hardware.org/?probe=fc5c01d215) | Sep 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| MSI           | GS66 Stealth 11UG           | [304abac74b](https://linux-hardware.org/?probe=304abac74b) | Sep 13, 2023 |
| HP            | Stream Notebook PC 11       | [f4c5ae4297](https://linux-hardware.org/?probe=f4c5ae4297) | Sep 13, 2023 |
| Acer          | AOA150                      | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Lenovo        | ThinkPad X230 232036U       | [58ec12094c](https://linux-hardware.org/?probe=58ec12094c) | Sep 13, 2023 |
| Google        | Cave                        | [74c8e00b23](https://linux-hardware.org/?probe=74c8e00b23) | Sep 13, 2023 |
| Dell          | Latitude E6430              | [79cf77c6ba](https://linux-hardware.org/?probe=79cf77c6ba) | Sep 12, 2023 |
| Dell          | Latitude E7470              | [4f2094dfef](https://linux-hardware.org/?probe=4f2094dfef) | Sep 12, 2023 |
| Toshiba       | Satellite L640              | [ac5a264fea](https://linux-hardware.org/?probe=ac5a264fea) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [be2af85bb7](https://linux-hardware.org/?probe=be2af85bb7) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [0224dfd46f](https://linux-hardware.org/?probe=0224dfd46f) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [52b50b0d68](https://linux-hardware.org/?probe=52b50b0d68) | Sep 11, 2023 |
| Google        | Enguarde                    | [4fd827adc5](https://linux-hardware.org/?probe=4fd827adc5) | Sep 11, 2023 |
| Google        | Enguarde                    | [b2b5b5f73b](https://linux-hardware.org/?probe=b2b5b5f73b) | Sep 11, 2023 |
| Lenovo        | ThinkPad L380 20M50013GE    | [e7778dd80d](https://linux-hardware.org/?probe=e7778dd80d) | Sep 11, 2023 |
| HP            | 250 G3                      | [162574954f](https://linux-hardware.org/?probe=162574954f) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [24e256ad9e](https://linux-hardware.org/?probe=24e256ad9e) | Sep 11, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [57e8f1b556](https://linux-hardware.org/?probe=57e8f1b556) | Sep 11, 2023 |
| Samsung       | 550XED                      | [69d754d35b](https://linux-hardware.org/?probe=69d754d35b) | Sep 11, 2023 |
| Samsung       | 550XED                      | [8187eca3e3](https://linux-hardware.org/?probe=8187eca3e3) | Sep 11, 2023 |
| Panasonic     | CF-19RHR3DPM                | [11484f2d00](https://linux-hardware.org/?probe=11484f2d00) | Sep 10, 2023 |
| ASUSTek       | G751JT                      | [4395b1ccb2](https://linux-hardware.org/?probe=4395b1ccb2) | Sep 10, 2023 |
| Dell          | Precision 5530              | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| ASUSTek       | X550VX                      | [b1b59ca70c](https://linux-hardware.org/?probe=b1b59ca70c) | Sep 10, 2023 |
| Acer          | Extensa 5220                | [c4ea757260](https://linux-hardware.org/?probe=c4ea757260) | Sep 10, 2023 |
| HP            | Unknown                     | [cb5704a65f](https://linux-hardware.org/?probe=cb5704a65f) | Sep 10, 2023 |
| Google        | Lillipup                    | [c3a892cdca](https://linux-hardware.org/?probe=c3a892cdca) | Sep 10, 2023 |
| HP            | ProBook 6570b               | [3ed768081c](https://linux-hardware.org/?probe=3ed768081c) | Sep 09, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [780a68ac11](https://linux-hardware.org/?probe=780a68ac11) | Sep 09, 2023 |
| Acer          | Aspire E1-531               | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| Dell          | Inspiron 7580               | [9705f02462](https://linux-hardware.org/?probe=9705f02462) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [3865278574](https://linux-hardware.org/?probe=3865278574) | Sep 09, 2023 |
| Acer          | Nitro AN515-55              | [3f247b15c6](https://linux-hardware.org/?probe=3f247b15c6) | Sep 09, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005QU... | [0a57a98442](https://linux-hardware.org/?probe=0a57a98442) | Sep 09, 2023 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | [b3697e5a7e](https://linux-hardware.org/?probe=b3697e5a7e) | Sep 09, 2023 |
| Google        | Enguarde                    | [3ec3cf816b](https://linux-hardware.org/?probe=3ec3cf816b) | Sep 08, 2023 |
| Google        | Enguarde                    | [fa7b318083](https://linux-hardware.org/?probe=fa7b318083) | Sep 08, 2023 |
| Google        | Enguarde                    | [1621463a03](https://linux-hardware.org/?probe=1621463a03) | Sep 08, 2023 |
| Google        | Enguarde                    | [b54a785396](https://linux-hardware.org/?probe=b54a785396) | Sep 08, 2023 |
| Google        | Enguarde                    | [b35f66260b](https://linux-hardware.org/?probe=b35f66260b) | Sep 08, 2023 |
| Google        | Enguarde                    | [e754c23dd9](https://linux-hardware.org/?probe=e754c23dd9) | Sep 08, 2023 |
| Google        | Enguarde                    | [71e3d1a632](https://linux-hardware.org/?probe=71e3d1a632) | Sep 08, 2023 |
| Google        | Enguarde                    | [352198bb3c](https://linux-hardware.org/?probe=352198bb3c) | Sep 08, 2023 |
| Google        | Enguarde                    | [15edd97e90](https://linux-hardware.org/?probe=15edd97e90) | Sep 08, 2023 |
| Google        | Enguarde                    | [265336497a](https://linux-hardware.org/?probe=265336497a) | Sep 08, 2023 |
| Google        | Enguarde                    | [af54a959e3](https://linux-hardware.org/?probe=af54a959e3) | Sep 08, 2023 |
| Google        | Enguarde                    | [d102cf6258](https://linux-hardware.org/?probe=d102cf6258) | Sep 08, 2023 |
| Google        | Enguarde                    | [d6fd89750c](https://linux-hardware.org/?probe=d6fd89750c) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [4e756a7c7d](https://linux-hardware.org/?probe=4e756a7c7d) | Sep 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0899f8743](https://linux-hardware.org/?probe=e0899f8743) | Sep 08, 2023 |
| Dell          | Latitude 5530               | [ae835c8d8b](https://linux-hardware.org/?probe=ae835c8d8b) | Sep 08, 2023 |
| HP            | 250 G3                      | [51ef1d34d0](https://linux-hardware.org/?probe=51ef1d34d0) | Sep 08, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [c9d6171716](https://linux-hardware.org/?probe=c9d6171716) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Dell          | Latitude E5550              | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| ASUSTek       | X507UB                      | [4604e73045](https://linux-hardware.org/?probe=4604e73045) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b05fdf4d62](https://linux-hardware.org/?probe=b05fdf4d62) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [db6d9f2293](https://linux-hardware.org/?probe=db6d9f2293) | Sep 08, 2023 |
| Lenovo        | ThinkPad P43s 20RH001UMX    | [0fdff74089](https://linux-hardware.org/?probe=0fdff74089) | Sep 07, 2023 |
| Google        | Enguarde                    | [7718db84e9](https://linux-hardware.org/?probe=7718db84e9) | Sep 07, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9117a08473](https://linux-hardware.org/?probe=9117a08473) | Sep 07, 2023 |
| Google        | Enguarde                    | [8a82984679](https://linux-hardware.org/?probe=8a82984679) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e2f9ce90d3](https://linux-hardware.org/?probe=e2f9ce90d3) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [03f6b3b62b](https://linux-hardware.org/?probe=03f6b3b62b) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| HP            | ZBook 15 G3                 | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [1bcf7b95c6](https://linux-hardware.org/?probe=1bcf7b95c6) | Sep 05, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [75c15ac2e8](https://linux-hardware.org/?probe=75c15ac2e8) | Sep 05, 2023 |
| ASUSTek       | K53SD                       | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Lenovo        | ThinkPad T520 4243WCR       | [181ef642cd](https://linux-hardware.org/?probe=181ef642cd) | Sep 05, 2023 |
| Sony          | VGN-CS108D                  | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [eb05baece5](https://linux-hardware.org/?probe=eb05baece5) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| ASUSTek       | X541NC                      | [927ba04557](https://linux-hardware.org/?probe=927ba04557) | Sep 05, 2023 |
| Acer          | Aspire E1-531               | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| eMachines     | Rhine V1.42                 | [c18c4d64bd](https://linux-hardware.org/?probe=c18c4d64bd) | Sep 04, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [f7a6b9d479](https://linux-hardware.org/?probe=f7a6b9d479) | Sep 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d075cbe2e0](https://linux-hardware.org/?probe=d075cbe2e0) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| ASUSTek       | X507UB                      | [e74c3ad568](https://linux-hardware.org/?probe=e74c3ad568) | Sep 03, 2023 |
| HP            | EliteBook 2740p             | [c6d9dc5a3b](https://linux-hardware.org/?probe=c6d9dc5a3b) | Sep 03, 2023 |
| Dell          | Latitude 5414               | [704d861366](https://linux-hardware.org/?probe=704d861366) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Google        | Droid                       | [da26431a82](https://linux-hardware.org/?probe=da26431a82) | Sep 03, 2023 |
| Google        | Droid                       | [278861e9e8](https://linux-hardware.org/?probe=278861e9e8) | Sep 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S2KV20    | [248ef69016](https://linux-hardware.org/?probe=248ef69016) | Sep 03, 2023 |
| Acer          | Aspire A515-56              | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [7ba8b58ea7](https://linux-hardware.org/?probe=7ba8b58ea7) | Sep 03, 2023 |
| Toshiba       | Satellite L10W-B-101        | [1865cdf1ad](https://linux-hardware.org/?probe=1865cdf1ad) | Sep 02, 2023 |
| HP            | ZBook 15 G2                 | [d20f8f324d](https://linux-hardware.org/?probe=d20f8f324d) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| Samsung       | RF511/RF411/RF711           | [ab39767c20](https://linux-hardware.org/?probe=ab39767c20) | Sep 02, 2023 |
| Dell          | Latitude E6520              | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Lenovo        | G505 20240                  | [ea15ab596a](https://linux-hardware.org/?probe=ea15ab596a) | Sep 02, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [155023d91f](https://linux-hardware.org/?probe=155023d91f) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| Dell          | Latitude 5430               | [7a9eb9995d](https://linux-hardware.org/?probe=7a9eb9995d) | Sep 02, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [52e8a720ba](https://linux-hardware.org/?probe=52e8a720ba) | Sep 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [af78cafb1a](https://linux-hardware.org/?probe=af78cafb1a) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f98a2afc33](https://linux-hardware.org/?probe=f98a2afc33) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Google        | Enguarde                    | [d67a18c110](https://linux-hardware.org/?probe=d67a18c110) | Aug 30, 2023 |
| HP            | ProBook 6460b               | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| GPU Compan... | GWTN156-9                   | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [6d85c1d397](https://linux-hardware.org/?probe=6d85c1d397) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [c9a61f810d](https://linux-hardware.org/?probe=c9a61f810d) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [d6fded6169](https://linux-hardware.org/?probe=d6fded6169) | Aug 30, 2023 |
| Google        | Enguarde                    | [08ff2764b2](https://linux-hardware.org/?probe=08ff2764b2) | Aug 30, 2023 |
| Unknown       | Unknown                     | [3718299cea](https://linux-hardware.org/?probe=3718299cea) | Aug 29, 2023 |
| Google        | Enguarde                    | [e2e5a3dadc](https://linux-hardware.org/?probe=e2e5a3dadc) | Aug 29, 2023 |
| Google        | Enguarde                    | [e7a59ac286](https://linux-hardware.org/?probe=e7a59ac286) | Aug 29, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4bdfa8b9ea](https://linux-hardware.org/?probe=4bdfa8b9ea) | Aug 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | [41ce572b6d](https://linux-hardware.org/?probe=41ce572b6d) | Aug 29, 2023 |
| Acer          | Swift SF314-512             | [a41a08d4ae](https://linux-hardware.org/?probe=a41a08d4ae) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [62ff88eaf7](https://linux-hardware.org/?probe=62ff88eaf7) | Aug 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | [243b20df85](https://linux-hardware.org/?probe=243b20df85) | Aug 28, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [cea73826dc](https://linux-hardware.org/?probe=cea73826dc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | [9675488adc](https://linux-hardware.org/?probe=9675488adc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | [29e062fb36](https://linux-hardware.org/?probe=29e062fb36) | Aug 27, 2023 |
| Apple         | MacBookPro6,2               | [e25e18e9b1](https://linux-hardware.org/?probe=e25e18e9b1) | Aug 27, 2023 |
| Lenovo        | B590 20208                  | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [5ef3048a11](https://linux-hardware.org/?probe=5ef3048a11) | Aug 26, 2023 |
| Dell          | Latitude E6420              | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | GP76 Leopard 11UG           | [5de726089b](https://linux-hardware.org/?probe=5de726089b) | Aug 26, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [3b5476180b](https://linux-hardware.org/?probe=3b5476180b) | Aug 26, 2023 |
| Alienware     | m16 R1                      | [75f20a1519](https://linux-hardware.org/?probe=75f20a1519) | Aug 26, 2023 |
| Alienware     | m16 R1                      | [89cffc75ea](https://linux-hardware.org/?probe=89cffc75ea) | Aug 26, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4ca70b63ef](https://linux-hardware.org/?probe=4ca70b63ef) | Aug 25, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| HP            | Pavilion dv5                | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Acer          | Aspire VN7-793G             | [5d748b1e22](https://linux-hardware.org/?probe=5d748b1e22) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| MSI           | GS65 Stealth Thin 8RE       | [b53212efce](https://linux-hardware.org/?probe=b53212efce) | Aug 24, 2023 |
| Dell          | XPS 9320                    | [1ba8e13634](https://linux-hardware.org/?probe=1ba8e13634) | Aug 24, 2023 |
| ASUSTek       | X450LD                      | [b9187b37b7](https://linux-hardware.org/?probe=b9187b37b7) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [4d1d53f6d8](https://linux-hardware.org/?probe=4d1d53f6d8) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| HP            | Laptop 17-by4xxx            | [9fd582b91e](https://linux-hardware.org/?probe=9fd582b91e) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Acer          | Aspire ES1-311              | [93f204808e](https://linux-hardware.org/?probe=93f204808e) | Aug 23, 2023 |
| Lenovo        | IdeaPad Z485 20151          | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Panasonic     | CFMX4-1                     | [fd352acae8](https://linux-hardware.org/?probe=fd352acae8) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [6d7eeef62a](https://linux-hardware.org/?probe=6d7eeef62a) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| MSI           | Stealth 17Studio A13VF      | [ca952946e9](https://linux-hardware.org/?probe=ca952946e9) | Aug 23, 2023 |
| ASUSTek       | X507UB                      | [6c8e9739d4](https://linux-hardware.org/?probe=6c8e9739d4) | Aug 23, 2023 |
| Gigabyte      | AORUS 5 KE                  | [abfb96067f](https://linux-hardware.org/?probe=abfb96067f) | Aug 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| Positivo      | Mobile                      | [e39dbd02a9](https://linux-hardware.org/?probe=e39dbd02a9) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [8b219ffa3b](https://linux-hardware.org/?probe=8b219ffa3b) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [b460d0aa2d](https://linux-hardware.org/?probe=b460d0aa2d) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [285b51551c](https://linux-hardware.org/?probe=285b51551c) | Aug 22, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | [ae599c9d4b](https://linux-hardware.org/?probe=ae599c9d4b) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [627606b933](https://linux-hardware.org/?probe=627606b933) | Aug 22, 2023 |
| HP            | Laptop 15z-ef3xxx           | [cf603a20c0](https://linux-hardware.org/?probe=cf603a20c0) | Aug 22, 2023 |
| Sony          | SVE14123CBW                 | [b7891b51b2](https://linux-hardware.org/?probe=b7891b51b2) | Aug 21, 2023 |
| Sony          | SVE14123CBW                 | [9730d7f8f5](https://linux-hardware.org/?probe=9730d7f8f5) | Aug 21, 2023 |
| HP            | 250 G7 Notebook PC          | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0baece8878](https://linux-hardware.org/?probe=0baece8878) | Aug 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [43d120af0e](https://linux-hardware.org/?probe=43d120af0e) | Aug 21, 2023 |
| Dell          | Inspiron 15 3515            | [534e1dc3e5](https://linux-hardware.org/?probe=534e1dc3e5) | Aug 21, 2023 |
| Sony          | VPCEH2J9R                   | [a919beee79](https://linux-hardware.org/?probe=a919beee79) | Aug 21, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e2c346429e](https://linux-hardware.org/?probe=e2c346429e) | Aug 21, 2023 |
| Acer          | Aspire A517-53G             | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Dell          | Latitude E5550              | [0f3afef2ac](https://linux-hardware.org/?probe=0f3afef2ac) | Aug 20, 2023 |
| Valve         | Jupiter                     | [36e4b2146b](https://linux-hardware.org/?probe=36e4b2146b) | Aug 20, 2023 |
| EUROCOM       | RACER 2.0                   | [b27f687c16](https://linux-hardware.org/?probe=b27f687c16) | Aug 20, 2023 |
| Acer          | Aspire A515-56              | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
| Apple         | MacBookAir7,2               | [fb3c8c793c](https://linux-hardware.org/?probe=fb3c8c793c) | Aug 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ab5bc08964](https://linux-hardware.org/?probe=ab5bc08964) | Aug 19, 2023 |
| Dell          | Vostro 3501                 | [5369c283ad](https://linux-hardware.org/?probe=5369c283ad) | Aug 18, 2023 |
| Acer          | Extensa 5235                | [1dc9843f33](https://linux-hardware.org/?probe=1dc9843f33) | Aug 18, 2023 |
| Acer          | Aspire VN7-793G             | [b88e1a5605](https://linux-hardware.org/?probe=b88e1a5605) | Aug 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [95c536cff4](https://linux-hardware.org/?probe=95c536cff4) | Aug 18, 2023 |
| ASUSTek       | M3N                         | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e66c463188](https://linux-hardware.org/?probe=e66c463188) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [55b9d87888](https://linux-hardware.org/?probe=55b9d87888) | Aug 18, 2023 |
| HP            | Laptop 15-dy0xxx            | [f938725821](https://linux-hardware.org/?probe=f938725821) | Aug 18, 2023 |
| Alienware     | 17 R4                       | [c16cb58f29](https://linux-hardware.org/?probe=c16cb58f29) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [748298f0c8](https://linux-hardware.org/?probe=748298f0c8) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [24a295f95b](https://linux-hardware.org/?probe=24a295f95b) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4291MW5       | [adf4aceec8](https://linux-hardware.org/?probe=adf4aceec8) | Aug 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Acer          | Aspire one                  | [47131c09b2](https://linux-hardware.org/?probe=47131c09b2) | Aug 16, 2023 |
| Acer          | Aspire A515-52G             | [2d38a6554a](https://linux-hardware.org/?probe=2d38a6554a) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [69e443b8a8](https://linux-hardware.org/?probe=69e443b8a8) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [66c997fdec](https://linux-hardware.org/?probe=66c997fdec) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [e57e76260c](https://linux-hardware.org/?probe=e57e76260c) | Aug 16, 2023 |
| Google        | Phaser360                   | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Dell          | Vostro 3501                 | [c36d4d9de0](https://linux-hardware.org/?probe=c36d4d9de0) | Aug 15, 2023 |
| Acer          | Aspire A315-59              | [901f34e440](https://linux-hardware.org/?probe=901f34e440) | Aug 15, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [268eeb2657](https://linux-hardware.org/?probe=268eeb2657) | Aug 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [4c24f10db4](https://linux-hardware.org/?probe=4c24f10db4) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| Alienware     | m15 R4                      | [40d4ad1e4f](https://linux-hardware.org/?probe=40d4ad1e4f) | Aug 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [72e71d1afc](https://linux-hardware.org/?probe=72e71d1afc) | Aug 14, 2023 |
| Dell          | XPS 13 9360                 | [69b51e3f5a](https://linux-hardware.org/?probe=69b51e3f5a) | Aug 14, 2023 |
| MSI           | Z790 GAMING WIFI            | [95e340d91b](https://linux-hardware.org/?probe=95e340d91b) | Aug 14, 2023 |
| Beelink       | Gemini X                    | [1610652627](https://linux-hardware.org/?probe=1610652627) | Aug 14, 2023 |
| Google        | Blooglet                    | [b9967e65c2](https://linux-hardware.org/?probe=b9967e65c2) | Aug 14, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [57af1d89d6](https://linux-hardware.org/?probe=57af1d89d6) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Lenovo        | ThinkPad W530 24477V0       | [2e09955f2f](https://linux-hardware.org/?probe=2e09955f2f) | Aug 13, 2023 |
| HP            | Pavilion dv5                | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| Apple         | MacBookPro8,1               | [c7bc7c3f16](https://linux-hardware.org/?probe=c7bc7c3f16) | Aug 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b0524c4203](https://linux-hardware.org/?probe=b0524c4203) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Acer          | Swift SF314-512             | [7158f3e437](https://linux-hardware.org/?probe=7158f3e437) | Aug 12, 2023 |
| Dell          | Vostro 3500                 | [2ec62f31c9](https://linux-hardware.org/?probe=2ec62f31c9) | Aug 12, 2023 |
| Dell          | Latitude E6430              | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| Unknown       | Unknown                     | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Unknown       | Unknown                     | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| Unknown       | Unknown                     | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| Acer          | Swift SF314-512             | [e168ac1e62](https://linux-hardware.org/?probe=e168ac1e62) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 25372E6       | [69c4723b51](https://linux-hardware.org/?probe=69c4723b51) | Aug 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [a728658683](https://linux-hardware.org/?probe=a728658683) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| Acer          | Aspire A515-57              | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| Lenovo        | G460 20041                  | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [72655a5d65](https://linux-hardware.org/?probe=72655a5d65) | Aug 08, 2023 |
| Dell          | Inspiron 7537               | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| HONOR         | HYM-WXX                     | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| Acer          | Aspire E5-573G              | [305061b67e](https://linux-hardware.org/?probe=305061b67e) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Apple         | MacBook7,1                  | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [55e9e43f37](https://linux-hardware.org/?probe=55e9e43f37) | Aug 06, 2023 |
| Dell          | Inspiron 5547               | [8f33c0cf28](https://linux-hardware.org/?probe=8f33c0cf28) | Aug 06, 2023 |
| HP            | Presario CQ57               | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| GPU Compan... | GWNR71517                   | [d754d51977](https://linux-hardware.org/?probe=d754d51977) | Aug 06, 2023 |
| Dell          | Latitude E5440              | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b4cc5c436c](https://linux-hardware.org/?probe=b4cc5c436c) | Aug 06, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [89119ae1fc](https://linux-hardware.org/?probe=89119ae1fc) | Aug 06, 2023 |
| HP            | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Dell          | Inspiron 15 3511            | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Acer          | Aspire E5-553G              | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Acer          | Swift SF314-512             | [ca109297da](https://linux-hardware.org/?probe=ca109297da) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Shuttle       | DS47D                       | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| ASUSTek       | N501JW                      | [e7d254dbe5](https://linux-hardware.org/?probe=e7d254dbe5) | Aug 04, 2023 |
| Dell          | Latitude E6400              | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Dell          | XPS 9320                    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| Sony          | VGN-FW373D                  | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| HP            | Lantis                      | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [51ad22a795](https://linux-hardware.org/?probe=51ad22a795) | Aug 03, 2023 |
| Dell          | Vostro 3405                 | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Google        | Enguarde                    | [663e44ce58](https://linux-hardware.org/?probe=663e44ce58) | Aug 03, 2023 |
| Dell          | Inspiron 5566               | [21d7f13381](https://linux-hardware.org/?probe=21d7f13381) | Aug 03, 2023 |
| Acer          | Nitro AN515-57              | [cef74aa3cb](https://linux-hardware.org/?probe=cef74aa3cb) | Aug 03, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Samsung       | 305U1A                      | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| ASUSTek       | 1015BX                      | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [433a85501a](https://linux-hardware.org/?probe=433a85501a) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Vostro 5515                 | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [dfb33be517](https://linux-hardware.org/?probe=dfb33be517) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [d3250ef8d7](https://linux-hardware.org/?probe=d3250ef8d7) | Aug 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| ASUSTek       | G750JX                      | [06279baf34](https://linux-hardware.org/?probe=06279baf34) | Aug 01, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| Lenovo        | Flex 2-14 20404             | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| Google        | Kevin                       | [ca1037f6ca](https://linux-hardware.org/?probe=ca1037f6ca) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [961a4eebbd](https://linux-hardware.org/?probe=961a4eebbd) | Jul 31, 2023 |
| Packard Be... | H17HV                       | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| Dell          | Inspiron 15 3511            | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| Apple         | MacBookPro5,5               | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [f3de23350d](https://linux-hardware.org/?probe=f3de23350d) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [3be466c09c](https://linux-hardware.org/?probe=3be466c09c) | Jul 30, 2023 |
| Apple         | MacBookPro6,2               | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| Dell          | Latitude E5270              | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Apple         | MacBookPro9,1               | [3b030b25ac](https://linux-hardware.org/?probe=3b030b25ac) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| HP            | ProBook 640 G2              | [87a4b835cf](https://linux-hardware.org/?probe=87a4b835cf) | Jul 30, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0YW0... | [3ff995e8b7](https://linux-hardware.org/?probe=3ff995e8b7) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Sony          | SVS13A1Z9RN                 | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [7207a12cd1](https://linux-hardware.org/?probe=7207a12cd1) | Jul 29, 2023 |
| Dell          | Latitude 5520               | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| VALE          | Notebook Classic C140       | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| Dell          | Latitude 7480               | [4287f8186f](https://linux-hardware.org/?probe=4287f8186f) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Dell          | Precision 3520              | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Dell          | System XPS L702X            | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Apple         | MacBookPro5,2               | [2c6617e2f9](https://linux-hardware.org/?probe=2c6617e2f9) | Jul 27, 2023 |
| Acer          | Extensa 215-32              | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [6e7d094f7f](https://linux-hardware.org/?probe=6e7d094f7f) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Google        | Vortininja                  | [70f9ee30d3](https://linux-hardware.org/?probe=70f9ee30d3) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| Fujitsu       | LIFEBOOK U748               | [23d71a87d0](https://linux-hardware.org/?probe=23d71a87d0) | Jul 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Dell          | XPS 13 7390                 | [0217675942](https://linux-hardware.org/?probe=0217675942) | Jul 26, 2023 |
| Dell          | Precision 3520              | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Acer          | Swift SF314-512             | [856e36fa9c](https://linux-hardware.org/?probe=856e36fa9c) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ProBook 640 G2              | [ae244aab21](https://linux-hardware.org/?probe=ae244aab21) | Jul 25, 2023 |
| Apple         | MacBookPro5,5               | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Google        | Droid                       | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [835ca23b88](https://linux-hardware.org/?probe=835ca23b88) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [321bdf6295](https://linux-hardware.org/?probe=321bdf6295) | Jul 25, 2023 |
| Acer          | Aspire 3610                 | [b40dd6ad17](https://linux-hardware.org/?probe=b40dd6ad17) | Jul 25, 2023 |
| MSI           | Katana GF66 11UG            | [bd45023e8e](https://linux-hardware.org/?probe=bd45023e8e) | Jul 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [5c52eecd16](https://linux-hardware.org/?probe=5c52eecd16) | Jul 25, 2023 |
| SANTECH       | NHx0DB,DE                   | [80aa11a7e8](https://linux-hardware.org/?probe=80aa11a7e8) | Jul 25, 2023 |
| Dell          | Latitude 3420               | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [fd441fa52f](https://linux-hardware.org/?probe=fd441fa52f) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Timi          | A7S                         | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| Dell          | Latitude E7250              | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| Acer          | Aspire A315-21              | [17f482e878](https://linux-hardware.org/?probe=17f482e878) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | EliteBook 840 G1            | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| HP            | Presario CQ57               | [2c1bcfe898](https://linux-hardware.org/?probe=2c1bcfe898) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Dell          | Latitude 5580               | [06c9677557](https://linux-hardware.org/?probe=06c9677557) | Jul 22, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [7d88a01e49](https://linux-hardware.org/?probe=7d88a01e49) | Jul 22, 2023 |
| HP            | 635                         | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| ASUSTek       | K72Jr                       | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [031d46c9d0](https://linux-hardware.org/?probe=031d46c9d0) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| Acer          | Swift SF314-512             | [d82c78621f](https://linux-hardware.org/?probe=d82c78621f) | Jul 20, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [311144e138](https://linux-hardware.org/?probe=311144e138) | Jul 20, 2023 |
| Shanghai Z... | ZXE CRB                     | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Notebook      | N650DU                      | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| Acer          | Swift SF314-43              | [6f00498896](https://linux-hardware.org/?probe=6f00498896) | Jul 19, 2023 |
| HP            | Pavilion 15                 | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [524d69b498](https://linux-hardware.org/?probe=524d69b498) | Jul 19, 2023 |
| Acer          | Aspire 7739Z                | [3e75dec5e0](https://linux-hardware.org/?probe=3e75dec5e0) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| HP            | Pavilion 17                 | [bf76e4c333](https://linux-hardware.org/?probe=bf76e4c333) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| HP            | EliteBook 8570p             | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| Dell          | Vostro 3500                 | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| Google        | Lillipup                    | [7f7ba76942](https://linux-hardware.org/?probe=7f7ba76942) | Jul 18, 2023 |
| HP            | Pavilion 15                 | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c6da4f3b1e](https://linux-hardware.org/?probe=c6da4f3b1e) | Jul 18, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [1b210ca778](https://linux-hardware.org/?probe=1b210ca778) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| HP            | Laptop 17-cp0xxx            | [9d9ff78d29](https://linux-hardware.org/?probe=9d9ff78d29) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | [f4fc84ba4b](https://linux-hardware.org/?probe=f4fc84ba4b) | Jul 17, 2023 |
| ASUSTek       | X505BA                      | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Unknown       | TU-142                      | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| HP            | Pavilion dm1                | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Acer          | Aspire A515-57T             | [dd4a3bf595](https://linux-hardware.org/?probe=dd4a3bf595) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| Dell          | Latitude E6440              | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [497e6c5432](https://linux-hardware.org/?probe=497e6c5432) | Jul 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1625385cef](https://linux-hardware.org/?probe=1625385cef) | Jul 16, 2023 |
| Dell          | Latitude D610               | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [02af27da78](https://linux-hardware.org/?probe=02af27da78) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| Dell          | Latitude E6330              | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| Dell          | Latitude 7490               | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [c76e3df311](https://linux-hardware.org/?probe=c76e3df311) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Coradir       | Coradir/ES10IS5             | [571080a9d5](https://linux-hardware.org/?probe=571080a9d5) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| HP            | ProBook 640 G2              | [e5efd1b971](https://linux-hardware.org/?probe=e5efd1b971) | Jul 14, 2023 |
| HP            | EliteBook 840 G5            | [02b5ea8525](https://linux-hardware.org/?probe=02b5ea8525) | Jul 14, 2023 |
| HP            | Pavilion dm1                | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| Dell          | Inspiron 15 3511            | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Google        | Blorb                       | [6bbcc9b8f3](https://linux-hardware.org/?probe=6bbcc9b8f3) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| HP            | 245 G8                      | [07eefc20b0](https://linux-hardware.org/?probe=07eefc20b0) | Jul 13, 2023 |
| Valve         | Jupiter                     | [14f7ea4a48](https://linux-hardware.org/?probe=14f7ea4a48) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Google        | Reks                        | [680b857c0d](https://linux-hardware.org/?probe=680b857c0d) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [7d2bb16563](https://linux-hardware.org/?probe=7d2bb16563) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [b054249d03](https://linux-hardware.org/?probe=b054249d03) | Jul 13, 2023 |
| MSI           | Alpha 15 A4DEK              | [9a192c4a0b](https://linux-hardware.org/?probe=9a192c4a0b) | Jul 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [34ec75d601](https://linux-hardware.org/?probe=34ec75d601) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| MSI           | Stealth 16Studio A13VG      | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [603a591fcb](https://linux-hardware.org/?probe=603a591fcb) | Jul 12, 2023 |
| Google        | Lillipup                    | [b7b430e7b4](https://linux-hardware.org/?probe=b7b430e7b4) | Jul 12, 2023 |
| Positivo      | Mobile                      | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Acer          | Aspire 5820TG               | [86cfbf79ce](https://linux-hardware.org/?probe=86cfbf79ce) | Jul 12, 2023 |
| MSI           | FX603                       | [a2c598f9eb](https://linux-hardware.org/?probe=a2c598f9eb) | Jul 12, 2023 |
| MSI           | SUMMIT E13FlipEvo A12MT     | [90faae34f3](https://linux-hardware.org/?probe=90faae34f3) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| Dell          | Latitude 7275               | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| Fujitsu       | LIFEBOOK E780               | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| HP            | ProBook 4730s               | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| HP            | EliteBook 645 14 inch G9... | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 3392      | 56.07%  |
| Debian 12                       | 939       | 15.52%  |
| Debian 10                       | 855       | 14.13%  |
| Debian Testing                  | 357       | 5.9%    |
| Debian                          | 181       | 2.99%   |
| Debian 9                        | 146       | 2.41%   |
| Debian Unstable                 | 128       | 2.12%   |
| Debian 11-updates               | 27        | 0.45%   |
| Debian 8                        | 11        | 0.18%   |
| Debian Sid                      | 4         | 0.07%   |
| Debian 23                       | 3         | 0.05%   |
| Debian 22                       | 3         | 0.05%   |
| Debian Testing/unstable         | 2         | 0.03%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 5761      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 586       | 8.84%   |
| 5.10.0-10-amd64 | 491       | 7.41%   |
| 5.10.0-20-amd64 | 244       | 3.68%   |
| 5.10.0-21-amd64 | 241       | 3.63%   |
| 5.10.0-18-amd64 | 178       | 2.68%   |
| 6.1.0-9-amd64   | 173       | 2.61%   |
| 6.1.0-10-amd64  | 173       | 2.61%   |
| 5.10.0-9-amd64  | 173       | 2.61%   |
| 5.10.0-7-amd64  | 171       | 2.58%   |
| 5.10.0-16-amd64 | 167       | 2.52%   |
| 5.10.0-19-amd64 | 162       | 2.44%   |
| 6.1.0-13-amd64  | 155       | 2.34%   |
| 5.10.0-13-amd64 | 151       | 2.28%   |
| 6.1.0-12-amd64  | 119       | 1.79%   |
| 5.10.0-23-amd64 | 107       | 1.61%   |
| 6.1.0-11-amd64  | 105       | 1.58%   |
| 5.10.0-11-amd64 | 105       | 1.58%   |
| 4.19.0-9-amd64  | 85        | 1.28%   |
| 4.19.0-6-amd64  | 82        | 1.24%   |
| 5.10.0-14-amd64 | 80        | 1.21%   |
| 5.10.0-17-amd64 | 73        | 1.1%    |
| 4.19.0-13-amd64 | 69        | 1.04%   |
| 4.19.0-8-amd64  | 68        | 1.03%   |
| 5.10.0-15-amd64 | 54        | 0.81%   |
| 4.19.0-16-amd64 | 53        | 0.8%    |
| 6.1.0-7-amd64   | 52        | 0.78%   |
| 4.19.0-10-amd64 | 52        | 0.78%   |
| 5.15.0-2-amd64  | 51        | 0.77%   |
| 5.10.0-2-amd64  | 49        | 0.74%   |
| 4.19.0-12-amd64 | 47        | 0.71%   |
| 6.1.0-4-amd64   | 45        | 0.68%   |
| 5.10.0-22-amd64 | 45        | 0.68%   |
| 4.19.0-14-amd64 | 42        | 0.63%   |
| 5.10.0-6-amd64  | 41        | 0.62%   |
| 5.10.0-12-amd64 | 40        | 0.6%    |
| 4.19.0-17-amd64 | 40        | 0.6%    |
| 4.9.0-8-amd64   | 39        | 0.59%   |
| 5.18.0-2-amd64  | 31        | 0.47%   |
| 5.10.0-3-amd64  | 31        | 0.47%   |
| 6.1.0-6-amd64   | 28        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 3183      | 51.34%  |
| 6.1.0    | 932       | 15.03%  |
| 4.19.0   | 656       | 10.58%  |
| 6.0.0    | 147       | 2.37%   |
| 4.9.0    | 120       | 1.94%   |
| 5.18.0   | 108       | 1.74%   |
| 5.15.0   | 92        | 1.48%   |
| 5.9.0    | 74        | 1.19%   |
| 5.19.0   | 70        | 1.13%   |
| 5.16.0   | 69        | 1.11%   |
| 5.4.0    | 64        | 1.03%   |
| 5.7.0    | 59        | 0.95%   |
| 5.8.0    | 56        | 0.9%    |
| 5.14.0   | 53        | 0.85%   |
| 5.6.0    | 45        | 0.73%   |
| 6.4.0    | 40        | 0.65%   |
| 5.17.0   | 39        | 0.63%   |
| 6.3.0    | 30        | 0.48%   |
| 6.5.0    | 28        | 0.45%   |
| 5.3.0    | 19        | 0.31%   |
| 5.5.0    | 16        | 0.26%   |
| 5.2.0    | 12        | 0.19%   |
| 4.18.0   | 12        | 0.19%   |
| 6.2.16   | 10        | 0.16%   |
| 3.16.0   | 9         | 0.15%   |
| 5.12.0   | 6         | 0.1%    |
| 5.10.10  | 4         | 0.06%   |
| 6.4.3    | 3         | 0.05%   |
| 6.4.2    | 3         | 0.05%   |
| 6.3.4    | 3         | 0.05%   |
| 6.2.8    | 3         | 0.05%   |
| 6.1.15   | 3         | 0.05%   |
| 5.3.5    | 3         | 0.05%   |
| 5.17.5   | 3         | 0.05%   |
| 5.15.107 | 3         | 0.05%   |
| 5.13.19  | 3         | 0.05%   |
| 5.13.0   | 3         | 0.05%   |
| 5.11.0   | 3         | 0.05%   |
| 5.10.60  | 3         | 0.05%   |
| 5.10.181 | 3         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3212      | 51.92%  |
| 6.1     | 944       | 15.26%  |
| 4.19    | 660       | 10.67%  |
| 6.0     | 155       | 2.51%   |
| 4.9     | 123       | 1.99%   |
| 5.15    | 119       | 1.92%   |
| 5.18    | 113       | 1.83%   |
| 5.9     | 80        | 1.29%   |
| 5.4     | 76        | 1.23%   |
| 5.19    | 75        | 1.21%   |
| 5.16    | 73        | 1.18%   |
| 5.7     | 62        | 1%      |
| 5.8     | 61        | 0.99%   |
| 5.14    | 58        | 0.94%   |
| 6.4     | 53        | 0.86%   |
| 5.6     | 49        | 0.79%   |
| 5.17    | 48        | 0.78%   |
| 6.3     | 38        | 0.61%   |
| 6.5     | 33        | 0.53%   |
| 5.3     | 24        | 0.39%   |
| 5.5     | 19        | 0.31%   |
| 6.2     | 18        | 0.29%   |
| 5.2     | 18        | 0.29%   |
| 5.13    | 12        | 0.19%   |
| 4.18    | 12        | 0.19%   |
| 5.12    | 9         | 0.15%   |
| 5.11    | 9         | 0.15%   |
| 3.16    | 9         | 0.15%   |
| 3.10    | 4         | 0.06%   |
| 5.1     | 3         | 0.05%   |
| 5.0     | 3         | 0.05%   |
| 4.17    | 2         | 0.03%   |
| 4.15    | 2         | 0.03%   |
| 4.14    | 2         | 0.03%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5511      | 95.64%  |
| i686    | 236       | 4.1%    |
| armv7l  | 10        | 0.17%   |
| aarch64 | 4         | 0.07%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1659      | 28.04%  |
| Unknown           | 1319      | 22.3%   |
| KDE5              | 844       | 14.27%  |
| XFCE              | 775       | 13.1%   |
| MATE              | 255       | 4.31%   |
| X-Cinnamon        | 228       | 3.85%   |
| LXDE              | 173       | 2.92%   |
| Cinnamon          | 159       | 2.69%   |
| KDE               | 117       | 1.98%   |
| i3                | 105       | 1.77%   |
| LXQt              | 88        | 1.49%   |
| GNOME Flashback   | 40        | 0.68%   |
| lightdm-xsession  | 29        | 0.49%   |
| Budgie            | 18        | 0.3%    |
| openbox           | 16        | 0.27%   |
| GNOME Classic     | 15        | 0.25%   |
| trinity           | 14        | 0.24%   |
| awesome           | 6         | 0.1%    |
| sway              | 5         | 0.08%   |
| Enlightenment     | 5         | 0.08%   |
| dwm               | 5         | 0.08%   |
| bspwm             | 5         | 0.08%   |
| ICEWM             | 4         | 0.07%   |
| fluxbox           | 4         | 0.07%   |
| x-session-manager | 3         | 0.05%   |
| Cutefish          | 3         | 0.05%   |
| BunsenLabs        | 3         | 0.05%   |
| xmonad            | 2         | 0.03%   |
| Unity             | 2         | 0.03%   |
| KDE4              | 2         | 0.03%   |
| GNUstep           | 2         | 0.03%   |
| default           | 2         | 0.03%   |
| wmaker-common     | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| mwm               | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| Hyprland          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 3257      | 55.3%   |
| Wayland     | 1339      | 22.73%  |
| Unknown     | 1053      | 17.88%  |
| Tty         | 236       | 4.01%   |
| Unspecified | 4         | 0.07%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2225      | 37.59%  |
| LightDM | 1034      | 17.47%  |
| GDM     | 1010      | 17.06%  |
| SDDM    | 762       | 12.87%  |
| GDM3    | 506       | 8.55%   |
| TDM     | 310       | 5.24%   |
| XDM     | 22        | 0.37%   |
| SLiM    | 13        | 0.22%   |
| NODM    | 10        | 0.17%   |
| LXDM    | 10        | 0.17%   |
| KDM     | 8         | 0.14%   |
| Ly      | 4         | 0.07%   |
| GREETD  | 3         | 0.05%   |
| WDM     | 1         | 0.02%   |
| SU      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1854      | 31.69%  |
| Unknown | 1041      | 17.79%  |
| de_DE   | 388       | 6.63%   |
| ru_RU   | 383       | 6.55%   |
| fr_FR   | 322       | 5.5%    |
| en_GB   | 268       | 4.58%   |
| pt_BR   | 196       | 3.35%   |
| es_ES   | 161       | 2.75%   |
| it_IT   | 156       | 2.67%   |
| pl_PL   | 114       | 1.95%   |
| en_CA   | 72        | 1.23%   |
| C       | 61        | 1.04%   |
| es_MX   | 57        | 0.97%   |
| en_IN   | 55        | 0.94%   |
| en_AU   | 54        | 0.92%   |
| zh_CN   | 50        | 0.85%   |
| es_AR   | 45        | 0.77%   |
| en_IE   | 34        | 0.58%   |
| es_CL   | 33        | 0.56%   |
| sv_SE   | 32        | 0.55%   |
| hu_HU   | 30        | 0.51%   |
| de_CH   | 22        | 0.38%   |
| nl_NL   | 20        | 0.34%   |
| fi_FI   | 20        | 0.34%   |
| es_VE   | 20        | 0.34%   |
| de_AT   | 20        | 0.34%   |
| pt_PT   | 19        | 0.32%   |
| cs_CZ   | 18        | 0.31%   |
| es_CO   | 17        | 0.29%   |
| tr_TR   | 16        | 0.27%   |
| en_NZ   | 15        | 0.26%   |
| ja_JP   | 14        | 0.24%   |
| en_ZA   | 13        | 0.22%   |
| ca_ES   | 13        | 0.22%   |
| fr_BE   | 12        | 0.21%   |
| ko_KR   | 11        | 0.19%   |
| en_SG   | 11        | 0.19%   |
| zh_TW   | 10        | 0.17%   |
| sk_SK   | 10        | 0.17%   |
| fr_CH   | 10        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3562      | 61.15%  |
| BIOS | 2263      | 38.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4215      | 72.71%  |
| Overlay | 1161      | 20.03%  |
| Btrfs   | 198       | 3.42%   |
| Unknown | 78        | 1.35%   |
| Xfs     | 53        | 0.91%   |
| Tmpfs   | 33        | 0.57%   |
| Zfs     | 19        | 0.33%   |
| Ext2    | 16        | 0.28%   |
| Rootfs  | 10        | 0.17%   |
| Ext3    | 8         | 0.14%   |
| Aufs    | 4         | 0.07%   |
| Jfs     | 1         | 0.02%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3608      | 61.68%  |
| Unknown | 1148      | 19.62%  |
| MBR     | 1094      | 18.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4870      | 83.39%  |
| Yes       | 970       | 16.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4324      | 74.23%  |
| Yes       | 1501      | 25.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1291      | 22.41%  |
| Hewlett-Packard        | 869       | 15.08%  |
| Dell                   | 831       | 14.42%  |
| Apple                  | 671       | 11.65%  |
| ASUSTek Computer       | 529       | 9.18%   |
| Acer                   | 405       | 7.03%   |
| Google                 | 190       | 3.3%    |
| MSI                    | 100       | 1.74%   |
| Toshiba                | 98        | 1.7%    |
| Samsung Electronics    | 83        | 1.44%   |
| HUAWEI                 | 49        | 0.85%   |
| Sony                   | 48        | 0.83%   |
| Aquarius               | 48        | 0.83%   |
| Unknown                | 48        | 0.83%   |
| Notebook               | 33        | 0.57%   |
| Fujitsu                | 33        | 0.57%   |
| Medion                 | 18        | 0.31%   |
| Alienware              | 18        | 0.31%   |
| Panasonic              | 16        | 0.28%   |
| Packard Bell           | 16        | 0.28%   |
| Timi                   | 15        | 0.26%   |
| Positivo               | 15        | 0.26%   |
| TUXEDO                 | 14        | 0.24%   |
| Intel                  | 14        | 0.24%   |
| IBM                    | 13        | 0.23%   |
| LG Electronics         | 11        | 0.19%   |
| HONOR                  | 11        | 0.19%   |
| Clevo                  | 11        | 0.19%   |
| Fujitsu Siemens        | 9         | 0.16%   |
| Framework              | 9         | 0.16%   |
| Razer                  | 8         | 0.14%   |
| PC Specialist          | 8         | 0.14%   |
| GPU Company            | 8         | 0.14%   |
| Gigabyte Technology    | 8         | 0.14%   |
| eMachines              | 8         | 0.14%   |
| System76               | 6         | 0.1%    |
| SLIMBOOK               | 6         | 0.1%    |
| Chuwi                  | 6         | 0.1%    |
| Avell High Performance | 6         | 0.1%    |
| Schenker               | 5         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 355       | 6.16%   |
| Apple MacBookAir7,2                   | 80        | 1.39%   |
| Apple MacBookAir7,1                   | 77        | 1.34%   |
| Google Enguarde                       | 74        | 1.28%   |
| Unknown                               | 64        | 1.11%   |
| Apple MacBook2,1                      | 57        | 0.99%   |
| Aquarius NS585                        | 48        | 0.83%   |
| Google Reks                           | 44        | 0.76%   |
| HP Notebook                           | 28        | 0.49%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.42%   |
| Google Terra                          | 23        | 0.4%    |
| Apple MacBook4,1                      | 23        | 0.4%    |
| HP Pavilion g6                        | 18        | 0.31%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.28%   |
| Acer Aspire A315-23                   | 16        | 0.28%   |
| ASUS 1005HA                           | 15        | 0.26%   |
| HP EliteBook 840 G3                   | 14        | 0.24%   |
| HP Laptop 15-db0xxx                   | 13        | 0.23%   |
| Dell Latitude E7440                   | 13        | 0.23%   |
| Dell Latitude 7480                    | 13        | 0.23%   |
| HP EliteBook 8460p                    | 12        | 0.21%   |
| Dell Latitude E6430                   | 12        | 0.21%   |
| Dell Latitude E6420                   | 12        | 0.21%   |
| HP Pavilion dv6                       | 11        | 0.19%   |
| HP Laptop 15s-eq2xxx                  | 11        | 0.19%   |
| HP 255 G8 Notebook PC                 | 11        | 0.19%   |
| HP 250 G7 Notebook PC                 | 11        | 0.19%   |
| Dell Latitude E7450                   | 11        | 0.19%   |
| Dell Inspiron 5570                    | 11        | 0.19%   |
| Acer Aspire A515-56                   | 11        | 0.19%   |
| Dell Latitude 5420                    | 10        | 0.17%   |
| HP Pavilion Notebook                  | 9         | 0.16%   |
| Dell XPS 13 9310                      | 9         | 0.16%   |
| Dell Inspiron 15-3567                 | 9         | 0.16%   |
| Samsung 300E4C/300E5C/300E7C          | 8         | 0.14%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 8         | 0.14%   |
| HP Laptop 15-db1xxx                   | 8         | 0.14%   |
| HP Laptop 15-bw0xx                    | 8         | 0.14%   |
| HP EliteBook 845 G8 Notebook PC       | 8         | 0.14%   |
| HP EliteBook 840 G6                   | 8         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 850       | 14.75%  |
| Apple MacBook5    | 356       | 6.18%   |
| Dell Latitude     | 324       | 5.62%   |
| Acer Aspire       | 265       | 4.6%    |
| Dell Inspiron     | 236       | 4.1%    |
| Lenovo IdeaPad    | 224       | 3.89%   |
| HP EliteBook      | 180       | 3.12%   |
| Apple MacBookAir7 | 157       | 2.73%   |
| HP Pavilion       | 132       | 2.29%   |
| HP Laptop         | 123       | 2.14%   |
| HP ProBook        | 111       | 1.93%   |
| Dell XPS          | 96        | 1.67%   |
| ASUS VivoBook     | 90        | 1.56%   |
| Toshiba Satellite | 76        | 1.32%   |
| Google Enguarde   | 74        | 1.28%   |
| Dell Vostro       | 70        | 1.22%   |
| Dell Precision    | 65        | 1.13%   |
| Unknown           | 64        | 1.11%   |
| Apple MacBook2    | 57        | 0.99%   |
| Aquarius NS585    | 48        | 0.83%   |
| HP Compaq         | 46        | 0.8%    |
| Google Reks       | 44        | 0.76%   |
| HP ZBook          | 38        | 0.66%   |
| HP 250            | 38        | 0.66%   |
| Lenovo Legion     | 37        | 0.64%   |
| ASUS ZenBook      | 36        | 0.62%   |
| ASUS ASUS         | 36        | 0.62%   |
| Acer TravelMate   | 33        | 0.57%   |
| Acer Swift        | 30        | 0.52%   |
| Acer Nitro        | 30        | 0.52%   |
| Fujitsu LIFEBOOK  | 29        | 0.5%    |
| HP Notebook       | 28        | 0.49%   |
| Lenovo ThinkBook  | 27        | 0.47%   |
| HP 255            | 26        | 0.45%   |
| ASUS ROG          | 24        | 0.42%   |
| Google Terra      | 23        | 0.4%    |
| Apple MacBook4    | 23        | 0.4%    |
| HP ENVY           | 21        | 0.36%   |
| HP OMEN           | 20        | 0.35%   |
| Lenovo Yoga       | 17        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 539       | 9.36%   |
| 2021    | 537       | 9.32%   |
| 2020    | 519       | 9.01%   |
| 2009    | 516       | 8.96%   |
| 2018    | 366       | 6.35%   |
| 2012    | 361       | 6.27%   |
| 2017    | 349       | 6.06%   |
| 2011    | 349       | 6.06%   |
| 2016    | 337       | 5.85%   |
| 2015    | 308       | 5.35%   |
| 2022    | 291       | 5.05%   |
| 2013    | 288       | 5%      |
| 2014    | 282       | 4.89%   |
| 2010    | 214       | 3.71%   |
| 2008    | 173       | 3%      |
| 2007    | 138       | 2.4%    |
| 2023    | 90        | 1.56%   |
| 2006    | 37        | 0.64%   |
| 2005    | 27        | 0.47%   |
| Unknown | 16        | 0.28%   |
| 2004    | 11        | 0.19%   |
| 2003    | 11        | 0.19%   |
| 2002    | 2         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5761      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5300      | 91.51%  |
| Enabled  | 492       | 8.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5555      | 96.41%  |
| Yes  | 207       | 3.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1506      | 25.88%  |
| 3.01-4.0    | 1109      | 19.06%  |
| 16.01-24.0  | 963       | 16.55%  |
| 8.01-16.0   | 926       | 15.91%  |
| 1.01-2.0    | 589       | 10.12%  |
| 32.01-64.0  | 367       | 6.31%   |
| 2.01-3.0    | 112       | 1.92%   |
| 0.51-1.0    | 87        | 1.5%    |
| 64.01-256.0 | 76        | 1.31%   |
| 24.01-32.0  | 60        | 1.03%   |
| 0.01-0.5    | 22        | 0.38%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2280      | 36.82%  |
| 2.01-3.0   | 1318      | 21.28%  |
| 4.01-8.0   | 889       | 14.35%  |
| 3.01-4.0   | 700       | 11.3%   |
| 0.51-1.0   | 582       | 9.4%    |
| 8.01-16.0  | 239       | 3.86%   |
| 0.01-0.5   | 145       | 2.34%   |
| 16.01-24.0 | 23        | 0.37%   |
| Unknown    | 7         | 0.11%   |
| 24.01-32.0 | 5         | 0.08%   |
| 32.01-64.0 | 4         | 0.06%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4520      | 77.26%  |
| 2      | 1131      | 19.33%  |
| 3      | 135       | 2.31%   |
| 0      | 36        | 0.62%   |
| 4      | 21        | 0.36%   |
| 5      | 5         | 0.09%   |
| 7      | 2         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3887      | 67.23%  |
| Yes       | 1895      | 32.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4658      | 80.56%  |
| No        | 1124      | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5643      | 97.87%  |
| No        | 123       | 2.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4649      | 80.16%  |
| No        | 1151      | 19.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1433      | 24.7%   |
| Germany     | 563       | 9.7%    |
| Russia      | 453       | 7.81%   |
| France      | 400       | 6.89%   |
| Brazil      | 286       | 4.93%   |
| Spain       | 236       | 4.07%   |
| Italy       | 221       | 3.81%   |
| Poland      | 168       | 2.9%    |
| UK          | 136       | 2.34%   |
| Netherlands | 104       | 1.79%   |
| Canada      | 104       | 1.79%   |
| Mexico      | 82        | 1.41%   |
| India       | 79        | 1.36%   |
| Switzerland | 74        | 1.28%   |
| Sweden      | 73        | 1.26%   |
| China       | 70        | 1.21%   |
| Argentina   | 68        | 1.17%   |
| Australia   | 65        | 1.12%   |
| Ukraine     | 60        | 1.03%   |
| Turkey      | 56        | 0.97%   |
| Portugal    | 50        | 0.86%   |
| Hungary     | 50        | 0.86%   |
| Austria     | 50        | 0.86%   |
| Belgium     | 48        | 0.83%   |
| Czechia     | 43        | 0.74%   |
| Finland     | 40        | 0.69%   |
| Chile       | 39        | 0.67%   |
| Greece      | 37        | 0.64%   |
| Norway      | 36        | 0.62%   |
| Romania     | 35        | 0.6%    |
| Indonesia   | 32        | 0.55%   |
| Colombia    | 30        | 0.52%   |
| Ireland     | 28        | 0.48%   |
| Japan       | 25        | 0.43%   |
| Venezuela   | 24        | 0.41%   |
| New Zealand | 21        | 0.36%   |
| Bulgaria    | 21        | 0.36%   |
| Denmark     | 20        | 0.34%   |
| Thailand    | 19        | 0.33%   |
| Belarus     | 19        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 665       | 10.82%  |
| Dover-Foxcroft    | 229       | 3.73%   |
| Voronezh          | 165       | 2.68%   |
| Moscow            | 83        | 1.35%   |
| Paris             | 72        | 1.17%   |
| St Petersburg     | 56        | 0.91%   |
| Berlin            | 56        | 0.91%   |
| Madrid            | 44        | 0.72%   |
| Warsaw            | 41        | 0.67%   |
| Seville           | 40        | 0.65%   |
| Sao Paulo         | 39        | 0.63%   |
| Vienna            | 34        | 0.55%   |
| Milan             | 34        | 0.55%   |
| Munich            | 33        | 0.54%   |
| Amsterdam         | 31        | 0.5%    |
| Hamburg           | 28        | 0.46%   |
| London            | 23        | 0.37%   |
| Barcelona         | 23        | 0.37%   |
| Prague            | 22        | 0.36%   |
| Istanbul          | 21        | 0.34%   |
| Frankfurt am Main | 21        | 0.34%   |
| Budapest          | 21        | 0.34%   |
| Sydney            | 20        | 0.33%   |
| Dublin            | 20        | 0.33%   |
| Perm              | 19        | 0.31%   |
| Helsinki          | 19        | 0.31%   |
| Brasília         | 19        | 0.31%   |
| Athens            | 19        | 0.31%   |
| Zurich            | 18        | 0.29%   |
| Mexico City       | 18        | 0.29%   |
| Lisbon            | 18        | 0.29%   |
| Toronto           | 17        | 0.28%   |
| Rome              | 17        | 0.28%   |
| Singapore         | 15        | 0.24%   |
| Saltsjoe-Boo      | 15        | 0.24%   |
| Mesa              | 15        | 0.24%   |
| Melbourne         | 15        | 0.24%   |
| Leipzig           | 15        | 0.24%   |
| Cologne           | 15        | 0.24%   |
| Santiago          | 13        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1062      | 1359   | 15.23%  |
| WDC                         | 766       | 947    | 10.99%  |
| Seagate                     | 606       | 722    | 8.69%   |
| Toshiba                     | 514       | 578    | 7.37%   |
| Unknown                     | 464       | 610    | 6.65%   |
| Kingston                    | 374       | 478    | 5.36%   |
| SanDisk                     | 351       | 439    | 5.03%   |
| Fujitsu                     | 294       | 304    | 4.22%   |
| SK hynix                    | 278       | 336    | 3.99%   |
| Crucial                     | 267       | 322    | 3.83%   |
| Apple                       | 195       | 249    | 2.8%    |
| Hitachi                     | 182       | 212    | 2.61%   |
| Micron Technology           | 181       | 196    | 2.6%    |
| Intel                       | 175       | 217    | 2.51%   |
| A-DATA Technology           | 150       | 289    | 2.15%   |
| HGST                        | 138       | 159    | 1.98%   |
| KIOXIA                      | 80        | 94     | 1.15%   |
| Unknown                     | 50        | 58     | 0.72%   |
| China                       | 46        | 52     | 0.66%   |
| LITEON                      | 38        | 46     | 0.54%   |
| Intenso                     | 32        | 41     | 0.46%   |
| Phison                      | 31        | 40     | 0.44%   |
| Transcend                   | 30        | 38     | 0.43%   |
| SPCC                        | 30        | 38     | 0.43%   |
| Silicon Motion              | 29        | 34     | 0.42%   |
| PNY                         | 28        | 36     | 0.4%    |
| Patriot                     | 24        | 26     | 0.34%   |
| JMicron Technology          | 23        | 24     | 0.33%   |
| SSSTC                       | 22        | 22     | 0.32%   |
| LITEONIT                    | 20        | 25     | 0.29%   |
| Team                        | 19        | 21     | 0.27%   |
| SABRENT                     | 18        | 19     | 0.26%   |
| Micron/Crucial Technology   | 15        | 16     | 0.22%   |
| Netac                       | 14        | 19     | 0.2%    |
| GOODRAM                     | 14        | 16     | 0.2%    |
| Phison Electronics          | 13        | 17     | 0.19%   |
| OCZ                         | 13        | 15     | 0.19%   |
| ADATA Technology            | 13        | 13     | 0.19%   |
| Kingston Technology Company | 12        | 13     | 0.17%   |
| Hewlett-Packard             | 12        | 14     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                    | 238       | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB                    | 80        | 1.12%   |
| Apple SSD AP0128H 121GB                           | 77        | 1.08%   |
| Apple SSD SM0128G 121GB                           | 74        | 1.03%   |
| Kingston SA400S37240G 240GB SSD                   | 68        | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 61        | 0.85%   |
| Kingston SA400S37120G 120GB SSD                   | 58        | 0.81%   |
| Toshiba MK1655GSXF 160GB                          | 52        | 0.73%   |
| Toshiba MQ01ABD100 1TB                            | 50        | 0.7%    |
| HGST HTS721010A9E630 1TB                          | 50        | 0.7%    |
| A-DATA SU800 512GB SSD                            | 50        | 0.7%    |
| Unknown                                           | 50        | 0.7%    |
| Toshiba MQ04ABF100 1TB                            | 45        | 0.63%   |
| Toshiba MQ01ABF050 500GB                          | 43        | 0.6%    |
| Toshiba MK1653GSX 160GB                           | 43        | 0.6%    |
| Crucial CT500MX500SSD1 500GB                      | 43        | 0.6%    |
| Unknown AGND3R  16GB                              | 39        | 0.54%   |
| Unknown MMC Card  32GB                            | 38        | 0.53%   |
| Kingston SA400S37480G 480GB SSD                   | 36        | 0.5%    |
| Samsung SSD 860 EVO 500GB                         | 35        | 0.49%   |
| Samsung SSD 850 EVO 250GB                         | 35        | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                      | 34        | 0.48%   |
| Unknown HAG2e  16GB                               | 32        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB                   | 30        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                       | 30        | 0.42%   |
| Unknown MMC Card  64GB                            | 29        | 0.41%   |
| Seagate ST1000LM048-2E7172 1TB                    | 29        | 0.41%   |
| Samsung SSD 860 EVO 1TB                           | 27        | 0.38%   |
| Samsung SSD 860 EVO 250GB                         | 26        | 0.36%   |
| Unknown SDW16G  16GB                              | 25        | 0.35%   |
| Unknown DF4016  16GB                              | 25        | 0.35%   |
| Seagate ST9500325AS 500GB                         | 25        | 0.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 25        | 0.35%   |
| Samsung SSD 980 1TB                               | 24        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                  | 24        | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 23        | 0.32%   |
| Samsung SSD 850 EVO 500GB                         | 23        | 0.32%   |
| HGST HTS725050A7E630 500GB                        | 23        | 0.32%   |
| Crucial CT240BX500SSD1 240GB                      | 23        | 0.32%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 20        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 583       | 695    | 28%     |
| WDC                 | 432       | 497    | 20.75%  |
| Toshiba             | 369       | 408    | 17.72%  |
| Fujitsu             | 294       | 304    | 14.12%  |
| Hitachi             | 182       | 212    | 8.74%   |
| HGST                | 138       | 159    | 6.63%   |
| Samsung Electronics | 38        | 40     | 1.83%   |
| Unknown             | 18        | 21     | 0.86%   |
| IBM/Hitachi         | 5         | 6      | 0.24%   |
| Intenso             | 4         | 5      | 0.19%   |
| Apple               | 3         | 4      | 0.14%   |
| SILICONMOTION       | 2         | 2      | 0.1%    |
| ASMT                | 2         | 7      | 0.1%    |
| WALRAM              | 1         | 1      | 0.05%   |
| USB3.0              | 1         | 1      | 0.05%   |
| Unknown (CF)        | 1         | 1      | 0.05%   |
| SYMTEC              | 1         | 1      | 0.05%   |
| Space ke            | 1         | 1      | 0.05%   |
| SAGE                | 1         | 1      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| Maxone              | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| IBM                 | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 446       | 559    | 19.94%  |
| Kingston            | 285       | 382    | 12.74%  |
| Crucial             | 231       | 281    | 10.33%  |
| SanDisk             | 227       | 299    | 10.15%  |
| A-DATA Technology   | 112       | 235    | 5.01%   |
| Apple               | 105       | 121    | 4.69%   |
| WDC                 | 97        | 125    | 4.34%   |
| Micron Technology   | 63        | 69     | 2.82%   |
| SK hynix            | 53        | 61     | 2.37%   |
| Intel               | 50        | 55     | 2.24%   |
| China               | 46        | 52     | 2.06%   |
| Toshiba             | 37        | 41     | 1.65%   |
| LITEON              | 32        | 37     | 1.43%   |
| Transcend           | 27        | 35     | 1.21%   |
| Intenso             | 26        | 33     | 1.16%   |
| PNY                 | 24        | 31     | 1.07%   |
| SPCC                | 23        | 30     | 1.03%   |
| Patriot             | 21        | 23     | 0.94%   |
| LITEONIT            | 20        | 25     | 0.89%   |
| SABRENT             | 18        | 19     | 0.8%    |
| Team                | 17        | 19     | 0.76%   |
| OCZ                 | 13        | 15     | 0.58%   |
| Netac               | 13        | 18     | 0.58%   |
| GOODRAM             | 11        | 13     | 0.49%   |
| Lexar               | 10        | 11     | 0.45%   |
| Plextor             | 9         | 9      | 0.4%    |
| KingSpec            | 9         | 9      | 0.4%    |
| Apacer              | 9         | 9      | 0.4%    |
| LDLC                | 8         | 8      | 0.36%   |
| Hewlett-Packard     | 8         | 11     | 0.36%   |
| Unknown             | 8         | 8      | 0.36%   |
| KingDian            | 7         | 7      | 0.31%   |
| Seagate             | 6         | 6      | 0.27%   |
| Gigabyte Technology | 6         | 6      | 0.27%   |
| Dogfish             | 6         | 9      | 0.27%   |
| Corsair             | 6         | 6      | 0.27%   |
| ASMT                | 6         | 8      | 0.27%   |
| TO Exter            | 5         | 6      | 0.22%   |
| KIOXIA-EXCERIA      | 5         | 6      | 0.22%   |
| Lenovo              | 4         | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2085      | 2858   | 31.25%  |
| HDD     | 2038      | 2373   | 30.55%  |
| NVMe    | 1979      | 2607   | 29.66%  |
| MMC     | 505       | 660    | 7.57%   |
| Unknown | 65        | 73     | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3710      | 5055   | 58.02%  |
| NVMe | 1968      | 2583   | 30.78%  |
| MMC  | 505       | 660    | 7.9%    |
| SAS  | 211       | 273    | 3.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2876      | 3659   | 70.91%  |
| 0.51-1.0   | 1045      | 1398   | 25.76%  |
| 1.01-2.0   | 103       | 129    | 2.54%   |
| 3.01-4.0   | 13        | 20     | 0.32%   |
| 4.01-10.0  | 11        | 15     | 0.27%   |
| 2.01-3.0   | 8         | 10     | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1656      | 27.71%  |
| 251-500        | 1306      | 21.85%  |
| Unknown        | 834       | 13.96%  |
| 501-1000       | 786       | 13.15%  |
| 51-100         | 392       | 6.56%   |
| 1001-2000      | 329       | 5.51%   |
| 1-20           | 318       | 5.32%   |
| 21-50          | 217       | 3.63%   |
| 2001-3000      | 73        | 1.22%   |
| More than 3000 | 65        | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2233      | 36.13%  |
| Unknown        | 834       | 13.49%  |
| 21-50          | 830       | 13.43%  |
| 101-250        | 783       | 12.67%  |
| 51-100         | 657       | 10.63%  |
| 251-500        | 438       | 7.09%   |
| 501-1000       | 256       | 4.14%   |
| 1001-2000      | 98        | 1.59%   |
| More than 3000 | 23        | 0.37%   |
| 2001-3000      | 18        | 0.29%   |
| 0              | 11        | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 25        | 25     | 4.34%   |
| Seagate ST9500325AS 500GB                           | 13        | 13     | 2.26%   |
| Toshiba MQ01ABD100 1TB                              | 11        | 12     | 1.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 11        | 13     | 1.91%   |
| Hitachi HTS543216L9SA02 160GB                       | 11        | 11     | 1.91%   |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 1.56%   |
| Toshiba MK1655GSXF 160GB                            | 8         | 8      | 1.39%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 8         | 10     | 1.39%   |
| Seagate ST9500420AS 500GB                           | 8         | 8      | 1.39%   |
| Seagate ST500LM021-1KJ152 500GB                     | 7         | 7      | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                      | 7         | 8      | 1.22%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 7      | 1.22%   |
| Toshiba MQ01ABF050 500GB                            | 6         | 6      | 1.04%   |
| HGST HTS725050A7E630 500GB                          | 6         | 8      | 1.04%   |
| HGST HTS541010A9E680 1TB                            | 6         | 6      | 1.04%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 6      | 0.87%   |
| Kingston SV300S37A120G 120GB SSD                    | 5         | 5      | 0.87%   |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 0.87%   |
| HGST HTS721010A9E630 1TB                            | 5         | 6      | 0.87%   |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 0.69%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 4         | 4      | 0.69%   |
| Seagate ST9320325AS 320GB                           | 4         | 4      | 0.69%   |
| Seagate ST500LM000-SSHD-8GB                         | 4         | 4      | 0.69%   |
| Seagate ST320LT007-9ZV142 320GB                     | 4         | 6      | 0.69%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 4         | 4      | 0.69%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 4      | 0.69%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 4      | 0.69%   |
| HGST HTS545050A7E680 500GB                          | 4         | 4      | 0.69%   |
| Crucial CT275MX300SSD1 275GB                        | 4         | 4      | 0.69%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 3      | 0.52%   |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 3         | 4      | 0.52%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 3         | 3      | 0.52%   |
| Seagate ST9250315AS 250GB                           | 3         | 4      | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 3      | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 3      | 0.52%   |
| Samsung Electronics SSD 870 EVO 500GB               | 3         | 3      | 0.52%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 4      | 0.52%   |
| Hitachi HTS547550A9E384 500GB                       | 3         | 3      | 0.52%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 0.52%   |
| Hitachi HTS543232A7A384 320GB                       | 3         | 3      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 122    | 19.48%  |
| Hitachi             | 80        | 87     | 13.91%  |
| Toshiba             | 72        | 74     | 12.52%  |
| WDC                 | 52        | 56     | 9.04%   |
| Fujitsu             | 40        | 40     | 6.96%   |
| HGST                | 36        | 39     | 6.26%   |
| Samsung Electronics | 34        | 37     | 5.91%   |
| SK hynix            | 28        | 31     | 4.87%   |
| Kingston            | 20        | 21     | 3.48%   |
| Micron Technology   | 16        | 17     | 2.78%   |
| Intel               | 16        | 17     | 2.78%   |
| SanDisk             | 14        | 16     | 2.43%   |
| Crucial             | 11        | 12     | 1.91%   |
| A-DATA Technology   | 10        | 11     | 1.74%   |
| LITEONIT            | 3         | 4      | 0.52%   |
| LITEON              | 3         | 3      | 0.52%   |
| SSSTC               | 2         | 2      | 0.35%   |
| Lenovo              | 2         | 2      | 0.35%   |
| KingSpec            | 2         | 2      | 0.35%   |
| JMicron Technology  | 2         | 2      | 0.35%   |
| IBM/Hitachi         | 2         | 2      | 0.35%   |
| Corsair             | 2         | 2      | 0.35%   |
| Apple               | 2         | 3      | 0.35%   |
| Unknown             | 2         | 2      | 0.35%   |
| Team                | 1         | 1      | 0.17%   |
| ShiJi               | 1         | 4      | 0.17%   |
| Plextor             | 1         | 1      | 0.17%   |
| KingDian            | 1         | 1      | 0.17%   |
| Kimtigo             | 1         | 1      | 0.17%   |
| IBM                 | 1         | 1      | 0.17%   |
| HECTRON             | 1         | 1      | 0.17%   |
| GOODRAM             | 1         | 1      | 0.17%   |
| GLOWAY              | 1         | 1      | 0.17%   |
| Dogfish             | 1         | 1      | 0.17%   |
| DGM                 | 1         | 1      | 0.17%   |
| China               | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 122    | 27.38%  |
| Hitachi             | 80        | 87     | 19.56%  |
| Toshiba             | 71        | 73     | 17.36%  |
| WDC                 | 51        | 55     | 12.47%  |
| Fujitsu             | 40        | 40     | 9.78%   |
| HGST                | 36        | 39     | 8.8%    |
| Samsung Electronics | 15        | 15     | 3.67%   |
| IBM/Hitachi         | 2         | 2      | 0.49%   |
| IBM                 | 1         | 1      | 0.24%   |
| Apple               | 1         | 2      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 406       | 436    | 70.98%  |
| SSD     | 133       | 143    | 23.25%  |
| NVMe    | 32        | 39     | 5.59%   |
| Unknown | 1         | 1      | 0.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 11.11%  |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 11.11%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 11.11%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 11.11%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 11.11%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 11.11%  |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 2      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3868      | 5300   | 62.4%   |
| Detected | 1752      | 2641   | 28.26%  |
| Malfunc  | 569       | 619    | 9.18%   |
| Failed   | 9         | 10     | 0.15%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3474      | 53.55%  |
| Samsung Electronics              | 679       | 10.47%  |
| AMD                              | 545       | 8.4%    |
| Nvidia                           | 385       | 5.93%   |
| Sandisk                          | 350       | 5.4%    |
| SK hynix                         | 212       | 3.27%   |
| Micron Technology                | 118       | 1.82%   |
| Toshiba America Info Systems     | 117       | 1.8%    |
| Kingston Technology Company      | 100       | 1.54%   |
| Apple                            | 86        | 1.33%   |
| KIOXIA                           | 78        | 1.2%    |
| Phison Electronics               | 61        | 0.94%   |
| Micron/Crucial Technology        | 52        | 0.8%    |
| ADATA Technology                 | 51        | 0.79%   |
| Silicon Motion                   | 42        | 0.65%   |
| Solid State Storage Technology   | 27        | 0.42%   |
| Union Memory (Shenzhen)          | 20        | 0.31%   |
| Silicon Integrated Systems [SiS] | 14        | 0.22%   |
| Realtek Semiconductor            | 10        | 0.15%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.11%   |
| Lite-On Technology               | 7         | 0.11%   |
| Yangtze Memory Technologies      | 6         | 0.09%   |
| Shenzhen Longsys Electronics     | 6         | 0.09%   |
| Seagate Technology               | 6         | 0.09%   |
| Lenovo                           | 6         | 0.09%   |
| VIA Technologies                 | 3         | 0.05%   |
| ULi Electronics                  | 3         | 0.05%   |
| Silicon Image                    | 3         | 0.05%   |
| Marvell Technology Group         | 3         | 0.05%   |
| Jiangsu Huacun Elec.             | 3         | 0.05%   |
| Biwin Storage Technology         | 3         | 0.05%   |
| ASMedia Technology               | 3         | 0.05%   |
| INNOGRIT                         | 2         | 0.03%   |
| Transcend                        | 1         | 0.02%   |
| ShenZhen TIGO Semiconductor      | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 474       | 6.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 439       | 6.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 374       | 5.39%   |
| Nvidia MCP79 AHCI Controller                                                   | 365       | 5.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 271       | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 253       | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 245       | 3.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 192       | 2.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 170       | 2.45%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 159       | 2.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 141       | 2.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 132       | 1.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 122       | 1.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 103       | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 102       | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 98        | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 97        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 96        | 1.38%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 95        | 1.37%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 94        | 1.35%   |
| Intel Tiger Lake-LP SATA Controller                                            | 93        | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 93        | 1.34%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 87        | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                          | 85        | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 84        | 1.21%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 80        | 1.15%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 76        | 1.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 71        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 69        | 0.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 63        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 58        | 0.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 55        | 0.79%   |
| Intel SSD 660P Series                                                          | 54        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 51        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 50        | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 48        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 44        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 43        | 0.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 42        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3866      | 57.48%  |
| NVMe | 1971      | 29.3%   |
| RAID | 458       | 6.81%   |
| IDE  | 430       | 6.39%   |
| SCSI | 1         | 0.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 4888      | 84.83%  |
| AMD          | 854       | 14.82%  |
| ARM          | 13        | 0.23%   |
| CentaurHauls | 5         | 0.09%   |
| Unknown      | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 357       | 6.19%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 148       | 2.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 116       | 2.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 98        | 1.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 86        | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 85        | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 80        | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 79        | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 77        | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 77        | 1.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 70        | 1.21%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 69        | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 1.18%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 64        | 1.11%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 62        | 1.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 59        | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 57        | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 53        | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 52        | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 51        | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 50        | 0.87%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 48        | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 46        | 0.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 43        | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 42        | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 41        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 38        | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 35        | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 34        | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 34        | 0.59%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 34        | 0.59%   |
| Intel 12th Gen Core i7-12700H                 | 34        | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 34        | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 33        | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 33        | 0.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 33        | 0.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 31        | 0.54%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 30        | 0.52%   |
| Intel 12th Gen Core i5-1235U                  | 30        | 0.52%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 28        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1363      | 23.64%  |
| Intel Core i7           | 1074      | 18.63%  |
| Intel Core 2 Duo        | 578       | 10.02%  |
| Other                   | 569       | 9.87%   |
| Intel Celeron           | 432       | 7.49%   |
| Intel Core i3           | 371       | 6.43%   |
| AMD Ryzen 5             | 244       | 4.23%   |
| Intel Atom              | 163       | 2.83%   |
| AMD Ryzen 7             | 161       | 2.79%   |
| Intel Pentium           | 108       | 1.87%   |
| Intel Core 2            | 73        | 1.27%   |
| AMD Ryzen 7 PRO         | 62        | 1.08%   |
| AMD A6                  | 45        | 0.78%   |
| Intel Pentium Dual-Core | 36        | 0.62%   |
| Intel Pentium M         | 35        | 0.61%   |
| AMD A4                  | 31        | 0.54%   |
| Intel Genuine           | 28        | 0.49%   |
| AMD Ryzen 3             | 28        | 0.49%   |
| AMD Ryzen 9             | 27        | 0.47%   |
| AMD Ryzen 5 PRO         | 26        | 0.45%   |
| AMD A8                  | 25        | 0.43%   |
| Intel Pentium Dual      | 22        | 0.38%   |
| AMD E1                  | 19        | 0.33%   |
| AMD E                   | 19        | 0.33%   |
| Intel Pentium Silver    | 16        | 0.28%   |
| AMD A10                 | 16        | 0.28%   |
| Intel Celeron M         | 15        | 0.26%   |
| AMD E2                  | 15        | 0.26%   |
| Intel Core i9           | 11        | 0.19%   |
| AMD Athlon              | 10        | 0.17%   |
| Intel Pentium 4         | 9         | 0.16%   |
| Intel Xeon              | 8         | 0.14%   |
| Intel Core m3           | 8         | 0.14%   |
| AMD Turion 64 X2 Mobile | 8         | 0.14%   |
| AMD A12                 | 7         | 0.12%   |
| AMD C-60                | 6         | 0.1%    |
| AMD C-50                | 6         | 0.1%    |
| AMD Athlon II           | 6         | 0.1%    |
| Intel Core m7           | 5         | 0.09%   |
| Intel Core Duo          | 5         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3088      | 53.56%  |
| 4      | 1671      | 28.98%  |
| 6      | 337       | 5.84%   |
| 8      | 283       | 4.91%   |
| 1      | 216       | 3.75%   |
| 10     | 72        | 1.25%   |
| 14     | 53        | 0.92%   |
| 12     | 38        | 0.66%   |
| 16     | 5         | 0.09%   |
| 24     | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5760      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3918      | 67.94%  |
| 1      | 1848      | 32.04%  |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5557      | 96.43%  |
| 32-bit         | 132       | 2.29%   |
| Unknown        | 72        | 1.25%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1357      | 22.97%  |
| 0x1067a    | 473       | 8.01%   |
| 0x306d4    | 275       | 4.65%   |
| 0x306a9    | 261       | 4.42%   |
| 0x206a7    | 250       | 4.23%   |
| 0x806c1    | 221       | 3.74%   |
| 0x806ec    | 213       | 3.61%   |
| 0x806e9    | 157       | 2.66%   |
| 0x806ea    | 149       | 2.52%   |
| 0x40651    | 142       | 2.4%    |
| 0x406e3    | 139       | 2.35%   |
| 0x30678    | 131       | 2.22%   |
| 0x406c4    | 107       | 1.81%   |
| 0x306c3    | 98        | 1.66%   |
| 0x906ea    | 85        | 1.44%   |
| 0x20655    | 82        | 1.39%   |
| 0xa0652    | 78        | 1.32%   |
| 0x0a50000c | 75        | 1.27%   |
| 0x08108109 | 72        | 1.22%   |
| 0x6f6      | 68        | 1.15%   |
| 0x906a3    | 67        | 1.13%   |
| 0x08608103 | 62        | 1.05%   |
| 0x08600106 | 62        | 1.05%   |
| 0x706e5    | 54        | 0.91%   |
| 0x706a8    | 53        | 0.9%    |
| 0x906a4    | 52        | 0.88%   |
| 0x10676    | 51        | 0.86%   |
| 0x906eb    | 48        | 0.81%   |
| 0x08108102 | 48        | 0.81%   |
| 0x6fd      | 47        | 0.8%    |
| 0x806eb    | 44        | 0.74%   |
| 0x106ca    | 43        | 0.73%   |
| 0x906e9    | 41        | 0.69%   |
| 0x506e3    | 41        | 0.69%   |
| 0x06006705 | 39        | 0.66%   |
| 0x106c2    | 38        | 0.64%   |
| 0x506c9    | 37        | 0.63%   |
| 0x806d1    | 33        | 0.56%   |
| 0x0600611a | 32        | 0.54%   |
| 0x6d8      | 31        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1029      | 17.83%  |
| Penryn           | 568       | 9.84%   |
| IvyBridge        | 356       | 6.17%   |
| SandyBridge      | 345       | 5.98%   |
| Haswell          | 332       | 5.75%   |
| Broadwell        | 318       | 5.51%   |
| Silvermont       | 302       | 5.23%   |
| TigerLake        | 284       | 4.92%   |
| Skylake          | 265       | 4.59%   |
| Unknown          | 207       | 3.59%   |
| Core             | 169       | 2.93%   |
| Westmere         | 153       | 2.65%   |
| Zen+             | 148       | 2.56%   |
| Zen 3            | 134       | 2.32%   |
| Alderlake Hybrid | 131       | 2.27%   |
| Zen 2            | 127       | 2.2%    |
| CometLake        | 111       | 1.92%   |
| Bonnell          | 102       | 1.77%   |
| IceLake          | 98        | 1.7%    |
| Excavator        | 98        | 1.7%    |
| Goldmont plus    | 94        | 1.63%   |
| P6               | 76        | 1.32%   |
| Goldmont         | 49        | 0.85%   |
| Bobcat           | 47        | 0.81%   |
| Zen              | 37        | 0.64%   |
| Puma             | 31        | 0.54%   |
| Jaguar           | 27        | 0.47%   |
| K8 Hammer        | 20        | 0.35%   |
| Tremont          | 18        | 0.31%   |
| Piledriver       | 18        | 0.31%   |
| K10 Llano        | 17        | 0.29%   |
| Nehalem          | 15        | 0.26%   |
| NetBurst         | 14        | 0.24%   |
| K10              | 13        | 0.23%   |
| K8 & K10 hybrid  | 10        | 0.17%   |
| Steamroller      | 7         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4208      | 60.35%  |
| Nvidia                           | 1599      | 22.93%  |
| AMD                              | 1148      | 16.46%  |
| Silicon Integrated Systems [SiS] | 9         | 0.13%   |
| Zhaoxin                          | 4         | 0.06%   |
| VIA Technologies                 | 2         | 0.03%   |
| S3 Graphics                      | 2         | 0.03%   |
| Neomagic                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 355       | 4.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 329       | 4.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 312       | 4.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 251       | 3.46%   |
| Intel UHD Graphics 620                                                                   | 222       | 3.06%   |
| Intel HD Graphics 620                                                                    | 195       | 2.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 186       | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 186       | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 171       | 2.36%   |
| Intel HD Graphics 6000                                                                   | 157       | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 156       | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 154       | 2.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 153       | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 145       | 2%      |
| Intel HD Graphics 5500                                                                   | 144       | 1.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 124       | 1.71%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 123       | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 120       | 1.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 119       | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 118       | 1.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 112       | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 107       | 1.47%   |
| AMD Lucienne                                                                             | 92        | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 88        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 84        | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 84        | 1.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 84        | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 84        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 76        | 1.05%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 63        | 0.87%   |
| Intel HD Graphics 630                                                                    | 57        | 0.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 54        | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 52        | 0.72%   |
| Intel HD Graphics 530                                                                    | 51        | 0.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 51        | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 50        | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 49        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.66%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 46        | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 40        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 3060      | 53%     |
| Intel + Nvidia     | 938       | 16.25%  |
| 1 x AMD            | 803       | 13.91%  |
| 1 x Nvidia         | 561       | 9.72%   |
| Intel + AMD        | 180       | 3.12%   |
| AMD + Nvidia       | 99        | 1.71%   |
| 2 x AMD            | 66        | 1.14%   |
| Other              | 27        | 0.47%   |
| 2 x Intel          | 18        | 0.31%   |
| 1 x SiS            | 9         | 0.16%   |
| 1 x Zhaoxin        | 4         | 0.07%   |
| 2 x Nvidia         | 2         | 0.03%   |
| 1 x VIA            | 2         | 0.03%   |
| 1 x S3 Graphics    | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5031      | 86.27%  |
| Proprietary | 429       | 7.36%   |
| Unknown     | 372       | 6.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 4235      | 72.58%  |
| 0.01-0.5       | 820       | 14.05%  |
| 1.01-2.0       | 322       | 5.52%   |
| 3.01-4.0       | 187       | 3.2%    |
| 0.51-1.0       | 175       | 3%      |
| 5.01-6.0       | 45        | 0.77%   |
| 7.01-8.0       | 35        | 0.6%    |
| 2.01-3.0       | 11        | 0.19%   |
| 8.01-16.0      | 2         | 0.03%   |
| More than 64.0 | 1         | 0.02%   |
| 16.01-24.0     | 1         | 0.02%   |
| 0              | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1133      | 18.11%  |
| BOE                     | 838       | 13.4%   |
| LG Display              | 739       | 11.81%  |
| Chimei Innolux          | 727       | 11.62%  |
| Apple                   | 669       | 10.7%   |
| Samsung Electronics     | 516       | 8.25%   |
| Dell                    | 167       | 2.67%   |
| Lenovo                  | 150       | 2.4%    |
| Sharp                   | 134       | 2.14%   |
| Goldstar                | 116       | 1.85%   |
| Chi Mei Optoelectronics | 101       | 1.61%   |
| InfoVision              | 95        | 1.52%   |
| PANDA                   | 77        | 1.23%   |
| Hewlett-Packard         | 75        | 1.2%    |
| BenQ                    | 61        | 0.98%   |
| Philips                 | 59        | 0.94%   |
| AOC                     | 49        | 0.78%   |
| CSO                     | 45        | 0.72%   |
| Acer                    | 41        | 0.66%   |
| LG Philips              | 39        | 0.62%   |
| Iiyama                  | 39        | 0.62%   |
| HannStar                | 38        | 0.61%   |
| Ancor Communications    | 35        | 0.56%   |
| Unknown                 | 25        | 0.4%    |
| ViewSonic               | 23        | 0.37%   |
| Sony                    | 19        | 0.3%    |
| CPT                     | 18        | 0.29%   |
| Eizo                    | 16        | 0.26%   |
| ASUSTek Computer        | 14        | 0.22%   |
| Quanta Display          | 10        | 0.16%   |
| Panasonic               | 9         | 0.14%   |
| NEC Computers           | 9         | 0.14%   |
| MSI                     | 9         | 0.14%   |
| LGD                     | 7         | 0.11%   |
| Pixio                   | 6         | 0.1%    |
| InnoLux Display         | 6         | 0.1%    |
| Toshiba                 | 5         | 0.08%   |
| TMX                     | 5         | 0.08%   |
| Unknown                 | 5         | 0.08%   |
| Vizio                   | 4         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 210       | 3.32%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 191       | 3.02%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 70        | 1.11%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 49        | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 48        | 0.76%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 47        | 0.74%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 45        | 0.71%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 42        | 0.66%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.6%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 34        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 29        | 0.46%   |
| BOE LCD Monitor BOE06B3 1920x1080                                    | 29        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 29        | 0.46%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 29        | 0.46%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 29        | 0.46%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 26        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 26        | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 24        | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 23        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 22        | 0.35%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 21        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 19        | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 19        | 0.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 19        | 0.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 18        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 18        | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 18        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 17        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 17        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 17        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 16        | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 15        | 0.24%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 15        | 0.24%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 15        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 15        | 0.24%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2313      | 39.22%  |
| 1366x768 (WXGA)    | 1594      | 27.03%  |
| 1280x800 (WXGA)    | 605       | 10.26%  |
| 1600x900 (HD+)     | 241       | 4.09%   |
| 3840x2160 (4K)     | 178       | 3.02%   |
| 1440x900 (WXGA+)   | 158       | 2.68%   |
| 1920x1200 (WUXGA)  | 150       | 2.54%   |
| 2560x1440 (QHD)    | 137       | 2.32%   |
| 1024x600           | 78        | 1.32%   |
| 2560x1600          | 50        | 0.85%   |
| 1280x1024 (SXGA)   | 43        | 0.73%   |
| 1680x1050 (WSXGA+) | 41        | 0.7%    |
| 3840x2400          | 31        | 0.53%   |
| 2560x1080          | 31        | 0.53%   |
| 3440x1440          | 29        | 0.49%   |
| 2880x1800          | 26        | 0.44%   |
| 1360x768           | 22        | 0.37%   |
| 2288x1287          | 21        | 0.36%   |
| 1024x768 (XGA)     | 20        | 0.34%   |
| 3200x1800 (QHD+)   | 11        | 0.19%   |
| 2160x1440          | 11        | 0.19%   |
| 2256x1504          | 10        | 0.17%   |
| Unknown            | 10        | 0.17%   |
| 1600x1200          | 9         | 0.15%   |
| 3840x1080          | 7         | 0.12%   |
| 1400x1050          | 6         | 0.1%    |
| 3072x1920          | 5         | 0.08%   |
| 1920x540           | 5         | 0.08%   |
| 1280x720 (HD)      | 5         | 0.08%   |
| 3456x2160          | 4         | 0.07%   |
| 1024x576           | 4         | 0.07%   |
| 800x1280           | 3         | 0.05%   |
| 3840x1200          | 3         | 0.05%   |
| 3840x1100          | 3         | 0.05%   |
| 3200x2000          | 3         | 0.05%   |
| 2880x1920          | 3         | 0.05%   |
| 2880x1620          | 3         | 0.05%   |
| 2304x1440          | 3         | 0.05%   |
| 2240x1400          | 3         | 0.05%   |
| 1920x1280          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1967      | 31.46%  |
| 13      | 1333      | 21.32%  |
| 14      | 812       | 12.99%  |
| 17      | 347       | 5.55%   |
| 11      | 344       | 5.5%    |
| 24      | 223       | 3.57%   |
| 12      | 216       | 3.45%   |
| 27      | 173       | 2.77%   |
| 23      | 139       | 2.22%   |
| 21      | 120       | 1.92%   |
| 10      | 79        | 1.26%   |
| 16      | 70        | 1.12%   |
| Unknown | 54        | 0.86%   |
| 18      | 52        | 0.83%   |
| 34      | 49        | 0.78%   |
| 31      | 38        | 0.61%   |
| 19      | 37        | 0.59%   |
| 22      | 23        | 0.37%   |
| 142     | 21        | 0.34%   |
| 25      | 18        | 0.29%   |
| 20      | 16        | 0.26%   |
| 32      | 13        | 0.21%   |
| 72      | 12        | 0.19%   |
| 40      | 11        | 0.18%   |
| 54      | 10        | 0.16%   |
| 8       | 10        | 0.16%   |
| 84      | 8         | 0.13%   |
| 29      | 8         | 0.13%   |
| 28      | 7         | 0.11%   |
| 49      | 5         | 0.08%   |
| 46      | 5         | 0.08%   |
| 26      | 5         | 0.08%   |
| 48      | 4         | 0.06%   |
| 52      | 3         | 0.05%   |
| 43      | 3         | 0.05%   |
| 33      | 3         | 0.05%   |
| 7       | 2         | 0.03%   |
| 86      | 1         | 0.02%   |
| 69      | 1         | 0.02%   |
| 65      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3261      | 52.62%  |
| 201-300        | 1498      | 24.17%  |
| 501-600        | 504       | 8.13%   |
| 351-400        | 408       | 6.58%   |
| 401-500        | 225       | 3.63%   |
| 601-700        | 76        | 1.23%   |
| 701-800        | 65        | 1.05%   |
| Unknown        | 54        | 0.87%   |
| 1001-1500      | 34        | 0.55%   |
| More than 2000 | 21        | 0.34%   |
| 1501-2000      | 21        | 0.34%   |
| 801-900        | 14        | 0.23%   |
| 101-200        | 11        | 0.18%   |
| 1-100          | 3         | 0.05%   |
| 901-1000       | 2         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4252      | 76.11%  |
| 16/10   | 1075      | 19.24%  |
| 21/9    | 54        | 0.97%   |
| 5/4     | 43        | 0.77%   |
| 3/2     | 43        | 0.77%   |
| 4/3     | 40        | 0.72%   |
| Unknown | 35        | 0.63%   |
| 1.00    | 21        | 0.38%   |
| 32/9    | 6         | 0.11%   |
| 2.65    | 5         | 0.09%   |
| 3.40    | 3         | 0.05%   |
| 3.20    | 3         | 0.05%   |
| 0.67    | 2         | 0.04%   |
| 6/5     | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1963      | 31.48%  |
| 81-90          | 1792      | 28.74%  |
| 201-250        | 391       | 6.27%   |
| 51-60          | 347       | 5.56%   |
| 71-80          | 344       | 5.52%   |
| 121-130        | 281       | 4.51%   |
| 61-70          | 210       | 3.37%   |
| 301-350        | 177       | 2.84%   |
| 351-500        | 112       | 1.8%    |
| 251-300        | 95        | 1.52%   |
| 151-200        | 86        | 1.38%   |
| 41-50          | 79        | 1.27%   |
| 141-150        | 71        | 1.14%   |
| More than 1000 | 62        | 0.99%   |
| 111-120        | 60        | 0.96%   |
| Unknown        | 54        | 0.87%   |
| 131-140        | 46        | 0.74%   |
| 501-1000       | 29        | 0.47%   |
| 91-100         | 23        | 0.37%   |
| 1-40           | 14        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2618      | 42.81%  |
| 101-120       | 1952      | 31.92%  |
| 51-100        | 864       | 14.13%  |
| 161-240       | 420       | 6.87%   |
| More than 240 | 136       | 2.22%   |
| 1-50          | 71        | 1.16%   |
| Unknown       | 54        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4588      | 77.91%  |
| 2     | 858       | 14.57%  |
| 0     | 346       | 5.88%   |
| 3     | 94        | 1.6%    |
| 4     | 2         | 0.03%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2932      | 31.77%  |
| Realtek Semiconductor             | 2577      | 27.92%  |
| Qualcomm Atheros                  | 1158      | 12.55%  |
| Broadcom                          | 820       | 8.89%   |
| Nvidia                            | 379       | 4.11%   |
| Broadcom Limited                  | 276       | 2.99%   |
| Marvell Technology Group          | 156       | 1.69%   |
| MediaTek                          | 137       | 1.48%   |
| ASIX Electronics                  | 72        | 0.78%   |
| Ralink                            | 67        | 0.73%   |
| TP-Link                           | 50        | 0.54%   |
| Sierra Wireless                   | 43        | 0.47%   |
| Dell                              | 43        | 0.47%   |
| Qualcomm                          | 42        | 0.46%   |
| Samsung Electronics               | 39        | 0.42%   |
| Lenovo                            | 39        | 0.42%   |
| Ralink Technology                 | 35        | 0.38%   |
| Xiaomi                            | 34        | 0.37%   |
| JMicron Technology                | 32        | 0.35%   |
| Ericsson Business Mobile Networks | 29        | 0.31%   |
| DisplayLink                       | 25        | 0.27%   |
| Hewlett-Packard                   | 21        | 0.23%   |
| Huawei Technologies               | 18        | 0.2%    |
| Fibocom                           | 16        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 13        | 0.14%   |
| NetGear                           | 10        | 0.11%   |
| Qualcomm Atheros Communications   | 9         | 0.1%    |
| OPPO Electronics                  | 9         | 0.1%    |
| Cypress Semiconductor             | 9         | 0.1%    |
| ASUSTek Computer                  | 9         | 0.1%    |
| Motorola PCS                      | 7         | 0.08%   |
| Microchip Technology              | 7         | 0.08%   |
| Google                            | 7         | 0.08%   |
| Attansic Technology               | 7         | 0.08%   |
| ICS Advent                        | 6         | 0.07%   |
| D-Link                            | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| U-Blox                            | 5         | 0.05%   |
| Edimax Technology                 | 5         | 0.05%   |
| AMD                               | 5         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1549      | 14.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 425       | 3.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 369       | 3.34%   |
| Nvidia MCP79 Ethernet                                                                 | 366       | 3.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 252       | 2.28%   |
| Intel Wireless 8265 / 8275                                                            | 245       | 2.22%   |
| Intel Wireless 7260                                                                   | 238       | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 235       | 2.13%   |
| Intel Wireless 7265                                                                   | 228       | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 220       | 1.99%   |
| Intel Wi-Fi 6 AX200                                                                   | 205       | 1.86%   |
| Intel Wi-Fi 6 AX201                                                                   | 196       | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 168       | 1.52%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 164       | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 154       | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 143       | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 143       | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 137       | 1.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 137       | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 134       | 1.21%   |
| Intel Wireless 8260                                                                   | 131       | 1.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 122       | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 117       | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 107       | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 105       | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 96        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 93        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 86        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 85        | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 84        | 0.76%   |
| Intel Ethernet Connection I219-LM                                                     | 76        | 0.69%   |
| Intel Wireless 3165                                                                   | 73        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                                  | 69        | 0.62%   |
| Intel Ethernet Connection I218-LM                                                     | 67        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 67        | 0.61%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 60        | 0.54%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 59        | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 58        | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 58        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2773      | 46.94%  |
| Qualcomm Atheros                      | 1028      | 17.4%   |
| Realtek Semiconductor                 | 744       | 12.6%   |
| Broadcom                              | 691       | 11.7%   |
| Broadcom Limited                      | 228       | 3.86%   |
| MediaTek                              | 129       | 2.18%   |
| Ralink                                | 67        | 1.13%   |
| Sierra Wireless                       | 43        | 0.73%   |
| Ralink Technology                     | 35        | 0.59%   |
| TP-Link                               | 30        | 0.51%   |
| Dell                                  | 28        | 0.47%   |
| Qualcomm                              | 26        | 0.44%   |
| Fibocom                               | 16        | 0.27%   |
| NetGear                               | 10        | 0.17%   |
| Qualcomm Atheros Communications       | 9         | 0.15%   |
| ASUSTek Computer                      | 9         | 0.15%   |
| Hewlett-Packard                       | 5         | 0.08%   |
| Ericsson Business Mobile Networks     | 5         | 0.08%   |
| Edimax Technology                     | 5         | 0.08%   |
| D-Link                                | 4         | 0.07%   |
| Microsoft                             | 3         | 0.05%   |
| D-Link System                         | 3         | 0.05%   |
| Wilocity                              | 2         | 0.03%   |
| Quectel Wireless Solutions            | 2         | 0.03%   |
| Belkin Components                     | 2         | 0.03%   |
| 3Com                                  | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Marvell Technology Group              | 1         | 0.02%   |
| Linksys                               | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 369       | 6.21%   |
| Intel Wireless 8265 / 8275                                                            | 245       | 4.12%   |
| Intel Wireless 7260                                                                   | 238       | 4.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 235       | 3.96%   |
| Intel Wireless 7265                                                                   | 228       | 3.84%   |
| Intel Wi-Fi 6 AX200                                                                   | 205       | 3.45%   |
| Intel Wi-Fi 6 AX201                                                                   | 196       | 3.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 168       | 2.83%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 164       | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 154       | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 143       | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 143       | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 137       | 2.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 137       | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 134       | 2.26%   |
| Intel Wireless 8260                                                                   | 131       | 2.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 122       | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 117       | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 107       | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 105       | 1.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 93        | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 86        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 85        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 84        | 1.41%   |
| Intel Wireless 3165                                                                   | 73        | 1.23%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 58        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 58        | 0.98%   |
| Intel Wireless-AC 9260                                                                | 57        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 55        | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 54        | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 53        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 51        | 0.86%   |
| Intel Centrino Ultimate-N 6300                                                        | 49        | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 45        | 0.76%   |
| Intel Wireless 3160                                                                   | 44        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 38        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 37        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 37        | 0.62%   |
| Intel Centrino Advanced-N 6200                                                        | 37        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2290      | 46.66%  |
| Intel                            | 1188      | 24.21%  |
| Nvidia                           | 379       | 7.72%   |
| Qualcomm Atheros                 | 266       | 5.42%   |
| Broadcom                         | 180       | 3.67%   |
| Marvell Technology Group         | 155       | 3.16%   |
| ASIX Electronics                 | 72        | 1.47%   |
| Broadcom Limited                 | 51        | 1.04%   |
| Samsung Electronics              | 39        | 0.79%   |
| Lenovo                           | 39        | 0.79%   |
| Xiaomi                           | 34        | 0.69%   |
| JMicron Technology               | 32        | 0.65%   |
| DisplayLink                      | 25        | 0.51%   |
| TP-Link                          | 20        | 0.41%   |
| Qualcomm                         | 15        | 0.31%   |
| Silicon Integrated Systems [SiS] | 13        | 0.26%   |
| Huawei Technologies              | 12        | 0.24%   |
| OPPO Electronics                 | 9         | 0.18%   |
| Cypress Semiconductor            | 9         | 0.18%   |
| MediaTek                         | 8         | 0.16%   |
| Hewlett-Packard                  | 8         | 0.16%   |
| Microchip Technology             | 7         | 0.14%   |
| Google                           | 7         | 0.14%   |
| Attansic Technology              | 7         | 0.14%   |
| ICS Advent                       | 6         | 0.12%   |
| Apple                            | 6         | 0.12%   |
| Motorola PCS                     | 5         | 0.1%    |
| Spreadtrum Communications        | 4         | 0.08%   |
| VIA Technologies                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |
| National Semiconductor           | 2         | 0.04%   |
| LG Electronics                   | 2         | 0.04%   |
| D-Link                           | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| MosChip Semiconductor            | 1         | 0.02%   |
| Linksys                          | 1         | 0.02%   |
| LeEco                            | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1549      | 31.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 425       | 8.55%   |
| Nvidia MCP79 Ethernet                                             | 366       | 7.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 252       | 5.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 220       | 4.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 96        | 1.93%   |
| Intel Ethernet Connection I219-LM                                 | 76        | 1.53%   |
| Intel Ethernet Connection (4) I219-V                              | 69        | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 67        | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 67        | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 60        | 1.21%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 59        | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 52        | 1.05%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 43        | 0.87%   |
| Intel 82567LM Gigabit Network Connection                          | 43        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 42        | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 41        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 37        | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 36        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 36        | 0.72%   |
| Intel Ethernet Connection (13) I219-V                             | 36        | 0.72%   |
| Intel Ethernet Connection (10) I219-V                             | 29        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 27        | 0.54%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 25        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 25        | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 24        | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 24        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 23        | 0.46%   |
| Intel Ethernet Connection (16) I219-V                             | 23        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 22        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 20        | 0.4%    |
| Intel Ethernet Connection (13) I219-LM                            | 20        | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 18        | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5647      | 54.1%   |
| Ethernet | 4653      | 44.57%  |
| Modem    | 130       | 1.25%   |
| Unknown  | 9         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4361      | 71.34%  |
| Ethernet | 1751      | 28.64%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4184      | 72.5%   |
| 1     | 1442      | 24.99%  |
| 0     | 91        | 1.58%   |
| 3     | 52        | 0.9%    |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4747      | 81.17%  |
| Yes  | 1101      | 18.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2128      | 45.38%  |
| Apple                           | 652       | 13.9%   |
| Realtek Semiconductor           | 439       | 9.36%   |
| Qualcomm Atheros Communications | 394       | 8.4%    |
| Broadcom                        | 216       | 4.61%   |
| IMC Networks                    | 194       | 4.14%   |
| Lite-On Technology              | 176       | 3.75%   |
| Foxconn / Hon Hai               | 135       | 2.88%   |
| Dell                            | 70        | 1.49%   |
| Hewlett-Packard                 | 55        | 1.17%   |
| Cambridge Silicon Radio         | 49        | 1.04%   |
| Toshiba                         | 33        | 0.7%    |
| Realtek                         | 31        | 0.66%   |
| ASUSTek Computer                | 30        | 0.64%   |
| Ralink                          | 20        | 0.43%   |
| Foxconn International           | 10        | 0.21%   |
| USI                             | 9         | 0.19%   |
| Ralink Technology               | 9         | 0.19%   |
| Alps Electric                   | 8         | 0.17%   |
| MediaTek                        | 6         | 0.13%   |
| Taiyo Yuden                     | 4         | 0.09%   |
| Fujitsu                         | 4         | 0.09%   |
| Opticis                         | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| Chicony Electronics             | 2         | 0.04%   |
| Askey Computer                  | 2         | 0.04%   |
| Unknown                         | 1         | 0.02%   |
| TP-Link                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Marvell Semiconductor           | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 898       | 19.13%  |
| Intel AX201 Bluetooth                               | 392       | 8.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 353       | 7.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 330       | 7.03%   |
| Realtek Bluetooth Radio                             | 295       | 6.28%   |
| Qualcomm Atheros  Bluetooth Device                  | 219       | 4.67%   |
| Intel AX200 Bluetooth                               | 196       | 4.18%   |
| Apple Bluetooth USB Host Controller                 | 167       | 3.56%   |
| Intel Bluetooth Device                              | 129       | 2.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 93        | 1.98%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 59        | 1.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 54        | 1.15%   |
| IMC Networks Bluetooth Radio                        | 53        | 1.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 52        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 52        | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 51        | 1.09%   |
| IMC Networks Wireless_Device                        | 50        | 1.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 49        | 1.04%   |
| Apple Bluetooth Host Controller                     | 48        | 1.02%   |
| IMC Networks Bluetooth Device                       | 46        | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 45        | 0.96%   |
| Intel AX210 Bluetooth                               | 45        | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                         | 44        | 0.94%   |
| Lite-On Bluetooth Device                            | 42        | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 41        | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 0.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 39        | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 36        | 0.77%   |
| Realtek Bluetooth Radio                             | 31        | 0.66%   |
| Lite-On Wireless_Device                             | 27        | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 26        | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.53%   |
| Dell DW375 Bluetooth Module                         | 23        | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 22        | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                    | 21        | 0.45%   |
| Ralink RT3290 Bluetooth                             | 20        | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 19        | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 15        | 0.32%   |
| Broadcom HP Portable SoftSailing                    | 15        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4424      | 65.66%  |
| Nvidia                                       | 968       | 14.37%  |
| AMD                                          | 940       | 13.95%  |
| C-Media Electronics                          | 49        | 0.73%   |
| Realtek Semiconductor                        | 37        | 0.55%   |
| Lenovo                                       | 36        | 0.53%   |
| Logitech                                     | 35        | 0.52%   |
| Texas Instruments                            | 20        | 0.3%    |
| Plantronics                                  | 19        | 0.28%   |
| GN Netcom                                    | 19        | 0.28%   |
| Hewlett-Packard                              | 15        | 0.22%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.21%   |
| Generalplus Technology                       | 12        | 0.18%   |
| ASUSTek Computer                             | 11        | 0.16%   |
| JMTek                                        | 10        | 0.15%   |
| Creative Technology                          | 9         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.09%   |
| Focusrite-Novation                           | 6         | 0.09%   |
| Kingston Technology                          | 5         | 0.07%   |
| CMX Systems                                  | 5         | 0.07%   |
| Zhaoxin                                      | 4         | 0.06%   |
| RODE Microphones                             | 4         | 0.06%   |
| Razer USA                                    | 4         | 0.06%   |
| Dell                                         | 4         | 0.06%   |
| Yamaha                                       | 3         | 0.04%   |
| VIA Technologies                             | 3         | 0.04%   |
| ULi Electronics                              | 3         | 0.04%   |
| SteelSeries ApS                              | 3         | 0.04%   |
| Sennheiser Communications                    | 3         | 0.04%   |
| Microsoft                                    | 3         | 0.04%   |
| BEHRINGER International                      | 3         | 0.04%   |
| Apple                                        | 3         | 0.04%   |
| XMOS                                         | 2         | 0.03%   |
| Sony                                         | 2         | 0.03%   |
| SAVITECH                                     | 2         | 0.03%   |
| M-Audio                                      | 2         | 0.03%   |
| Fujitsu                                      | 2         | 0.03%   |
| ESS Technology                               | 2         | 0.03%   |
| Conexant Systems                             | 2         | 0.03%   |
| Blue Microphones                             | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 653       | 8.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 548       | 6.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 422       | 5.18%   |
| Nvidia MCP79 High Definition Audio                                                                | 368       | 4.52%   |
| Intel Broadwell-U Audio Controller                                                                | 318       | 3.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 314       | 3.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 301       | 3.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 282       | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 278       | 3.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 195       | 2.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 191       | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 191       | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 180       | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 180       | 2.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 176       | 2.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 167       | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 166       | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 160       | 1.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 140       | 1.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 138       | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 126       | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 121       | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 118       | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 118       | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 111       | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 104       | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 100       | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 94        | 1.15%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 93        | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 83        | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 65        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 64        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 64        | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 60        | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 59        | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 54        | 0.66%   |
| AMD High Definition Audio Controller                                                              | 52        | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 49        | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 46        | 0.56%   |
| Nvidia Audio device                                                                               | 40        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1483      | 26.96%  |
| SK hynix            | 1476      | 26.84%  |
| Micron Technology   | 651       | 11.84%  |
| Kingston            | 388       | 7.05%   |
| Unknown             | 365       | 6.64%   |
| Crucial             | 275       | 5%      |
| Elpida              | 151       | 2.75%   |
| A-DATA Technology   | 110       | 2%      |
| Ramaxel Technology  | 106       | 1.93%   |
| Corsair             | 62        | 1.13%   |
| Nanya Technology    | 57        | 1.04%   |
| Unknown (ABCD)      | 43        | 0.78%   |
| Smart               | 43        | 0.78%   |
| GOODRAM             | 26        | 0.47%   |
| G.Skill             | 26        | 0.47%   |
| Unknown             | 24        | 0.44%   |
| Transcend           | 23        | 0.42%   |
| Team                | 18        | 0.33%   |
| Teikon              | 11        | 0.2%    |
| Silicon Power       | 9         | 0.16%   |
| ASint Technology    | 9         | 0.16%   |
| Apacer              | 9         | 0.16%   |
| 4ea5                | 9         | 0.16%   |
| Patriot             | 8         | 0.15%   |
| ff                  | 8         | 0.15%   |
| 48spaces            | 8         | 0.15%   |
| Timetec             | 6         | 0.11%   |
| Smart Brazil        | 6         | 0.11%   |
| AMD                 | 5         | 0.09%   |
| Qimonda             | 4         | 0.07%   |
| PNY                 | 4         | 0.07%   |
| Neo Forza           | 4         | 0.07%   |
| fef5                | 4         | 0.07%   |
| Wilk                | 3         | 0.05%   |
| Kllisre             | 3         | 0.05%   |
| Infineon            | 3         | 0.05%   |
| Goldkey             | 3         | 0.05%   |
| CSX                 | 3         | 0.05%   |
| Avant               | 3         | 0.05%   |
| 2B0B00000000        | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 265       | 4.58%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.17%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 68        | 1.17%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 56        | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 55        | 0.95%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 50        | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 47        | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 46        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 46        | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 45        | 0.78%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 43        | 0.74%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 43        | 0.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 42        | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.71%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 40        | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 39        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 37        | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 0.6%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 34        | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 31        | 0.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.5%    |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 29        | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 27        | 0.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 27        | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 26        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 26        | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 26        | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.45%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.43%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.43%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 24        | 0.41%   |
| Unknown                                                          | 24        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 23        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1918      | 40.41%  |
| DDR3    | 1548      | 32.62%  |
| DDR2    | 628       | 13.23%  |
| LPDDR3  | 190       | 4%      |
| LPDDR4  | 185       | 3.9%    |
| SDRAM   | 93        | 1.96%   |
| DDR5    | 49        | 1.03%   |
| DDR     | 47        | 0.99%   |
| LPDDR5  | 43        | 0.91%   |
| Unknown | 32        | 0.67%   |
| DRAM    | 12        | 0.25%   |
| RAM     | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 4264      | 89.5%   |
| Row Of Chips | 346       | 7.26%   |
| Unknown      | 103       | 2.16%   |
| Chip         | 33        | 0.69%   |
| DIMM         | 18        | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1712      | 33.09%  |
| 4096  | 1292      | 24.97%  |
| 2048  | 781       | 15.09%  |
| 16384 | 596       | 11.52%  |
| 1024  | 585       | 11.31%  |
| 32768 | 137       | 2.65%   |
| 512   | 48        | 0.93%   |
| 256   | 18        | 0.35%   |
| 128   | 2         | 0.04%   |
| 8072  | 1         | 0.02%   |
| 1536  | 1         | 0.02%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1096      | 21.57%  |
| 3200    | 914       | 17.99%  |
| 2667    | 846       | 16.65%  |
| 800     | 398       | 7.83%   |
| 2400    | 308       | 6.06%   |
| 2133    | 225       | 4.43%   |
| 1334    | 212       | 4.17%   |
| 667     | 195       | 3.84%   |
| 1333    | 153       | 3.01%   |
| Unknown | 120       | 2.36%   |
| 1867    | 90        | 1.77%   |
| 1067    | 72        | 1.42%   |
| 4267    | 69        | 1.36%   |
| 4800    | 46        | 0.91%   |
| 3266    | 46        | 0.91%   |
| 6400    | 42        | 0.83%   |
| 4199    | 34        | 0.67%   |
| 1066    | 34        | 0.67%   |
| 533     | 28        | 0.55%   |
| 2048    | 22        | 0.43%   |
| 975     | 22        | 0.43%   |
| 8400    | 17        | 0.33%   |
| 4266    | 16        | 0.31%   |
| 400     | 12        | 0.24%   |
| 3733    | 9         | 0.18%   |
| 333     | 9         | 0.18%   |
| 1866    | 8         | 0.16%   |
| 266     | 8         | 0.16%   |
| 5600    | 6         | 0.12%   |
| 2666    | 4         | 0.08%   |
| 2933    | 3         | 0.06%   |
| 933     | 3         | 0.06%   |
| 1776    | 2         | 0.04%   |
| 1639    | 2         | 0.04%   |
| 7500    | 1         | 0.02%   |
| 7467    | 1         | 0.02%   |
| 3000    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1596    | 1         | 0.02%   |
| 666     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 34.21%  |
| Canon                 | 5         | 13.16%  |
| Brother Industries    | 5         | 13.16%  |
| Xerox                 | 4         | 10.53%  |
| Seiko Epson           | 2         | 5.26%   |
| Samsung Electronics   | 2         | 5.26%   |
| Kyocera               | 2         | 5.26%   |
| Xiaomi                | 1         | 2.63%   |
| STMicroelectronics    | 1         | 2.63%   |
| Pantum                | 1         | 2.63%   |
| Lexmark International | 1         | 2.63%   |
| Dymo-CoStar           | 1         | 2.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 10%     |
| Brother HL-L2340D series                                  | 2         | 5%      |
| Xiaomi MiMouse 2                                          | 1         | 2.5%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.5%    |
| Seiko Epson Printer                                       | 1         | 2.5%    |
| Seiko Epson L120 Series                                   | 1         | 2.5%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.5%    |
| Samsung CLX-3300 Series                                   | 1         | 2.5%    |
| Pantum P2500W series                                      | 1         | 2.5%    |
| Lexmark International E260dn                              | 1         | 2.5%    |
| Kyocera FS-1120MFP                                        | 1         | 2.5%    |
| Kyocera ECOSYS P2335d                                     | 1         | 2.5%    |
| HP Printing Support                                       | 1         | 2.5%    |
| HP OfficeJet 3830 series                                  | 1         | 2.5%    |
| HP LaserJet P1102                                         | 1         | 2.5%    |
| HP LaserJet P1005                                         | 1         | 2.5%    |
| HP LaserJet 1200                                          | 1         | 2.5%    |
| HP LaserJet 1160 series                                   | 1         | 2.5%    |
| HP LaserJet 1150                                          | 1         | 2.5%    |
| HP LaserJet 1022                                          | 1         | 2.5%    |
| HP LaserJet 1020                                          | 1         | 2.5%    |
| HP Ink Tank 110 series                                    | 1         | 2.5%    |
| HP EWS UPD                                                | 1         | 2.5%    |
| HP DeskJet 2600 series                                    | 1         | 2.5%    |
| HP Deskjet 2540 series                                    | 1         | 2.5%    |
| HP DeskJet 2130 series                                    | 1         | 2.5%    |
| Dymo-CoStar DYMO XTL                                      | 1         | 2.5%    |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 2.5%    |
| Canon PIXMA MX920 Series                                  | 1         | 2.5%    |
| Canon LiDE 300                                            | 1         | 2.5%    |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 2.5%    |
| Canon LBP2900                                             | 1         | 2.5%    |
| Canon G3010 series                                        | 1         | 2.5%    |
| Brother PT-9500PC                                         | 1         | 2.5%    |
| Brother MFC-L2707DW                                       | 1         | 2.5%    |
| Brother DCP-7010                                          | 1         | 2.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 7         | 43.75%  |
| Seiko Epson        | 5         | 31.25%  |
| Mustek Systems     | 2         | 12.5%   |
| Ultima Electronics | 1         | 6.25%   |
| Hewlett-Packard    | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                                                               | 2         | 12.5%   |
| Canon CanoScan LiDE 110                                                               | 2         | 12.5%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 6.25%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 6.25%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 6.25%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 6.25%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 6.25%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 6.25%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 6.25%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 1         | 6.25%   |
| HP Scanjet 200                                                                        | 1         | 6.25%   |
| Canon CanoScan LIDE 25                                                                | 1         | 6.25%   |
| Canon CanoScan LiDE 220                                                               | 1         | 6.25%   |
| Canon CanoScan LiDE 210                                                               | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1102      | 23.96%  |
| IMC Networks                           | 505       | 10.98%  |
| Microdia                               | 365       | 7.94%   |
| Quanta                                 | 359       | 7.81%   |
| Realtek Semiconductor                  | 356       | 7.74%   |
| Bison Electronics                      | 309       | 6.72%   |
| Sunplus Innovation Technology          | 259       | 5.63%   |
| Cheng Uei Precision Industry (Foxlink) | 144       | 3.13%   |
| Acer                                   | 144       | 3.13%   |
| Suyin                                  | 139       | 3.02%   |
| Lite-On Technology                     | 115       | 2.5%    |
| Syntek                                 | 106       | 2.3%    |
| Luxvisions Innotech Limited            | 102       | 2.22%   |
| Apple                                  | 84        | 1.83%   |
| Logitech                               | 65        | 1.41%   |
| Silicon Motion                         | 62        | 1.35%   |
| Alcor Micro                            | 46        | 1%      |
| Lenovo                                 | 40        | 0.87%   |
| Ricoh                                  | 34        | 0.74%   |
| Sonix Technology                       | 30        | 0.65%   |
| Z-Star Microelectronics                | 22        | 0.48%   |
| Primax Electronics                     | 20        | 0.43%   |
| Samsung Electronics                    | 16        | 0.35%   |
| icSpring                               | 13        | 0.28%   |
| ALi                                    | 13        | 0.28%   |
| SunplusIT                              | 12        | 0.26%   |
| Importek                               | 12        | 0.26%   |
| OmniVision Technologies                | 8         | 0.17%   |
| Genesys Logic                          | 8         | 0.17%   |
| Microsoft                              | 7         | 0.15%   |
| GEMBIRD                                | 6         | 0.13%   |
| MacroSilicon                           | 5         | 0.11%   |
| Intel                                  | 5         | 0.11%   |
| Generalplus Technology                 | 5         | 0.11%   |
| Y Media                                | 4         | 0.09%   |
| Sunplus Technology                     | 3         | 0.07%   |
| ShineTech                              | 3         | 0.07%   |
| Pixart Imaging                         | 3         | 0.07%   |
| ARC International                      | 3         | 0.07%   |
| 8SSC21D67422V1SR28902JL                | 3         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 299       | 6.46%   |
| Microdia Integrated_Webcam_HD                       | 183       | 3.95%   |
| IMC Networks Integrated Camera                      | 168       | 3.63%   |
| Realtek Integrated_Webcam_HD                        | 135       | 2.92%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 120       | 2.59%   |
| Quanta Chromebook HD Camera                         | 101       | 2.18%   |
| Chicony HD WebCam                                   | 91        | 1.97%   |
| Sunplus Integrated_Webcam_HD                        | 88        | 1.9%    |
| Bison Integrated Camera                             | 84        | 1.81%   |
| Chicony HP HD Camera                                | 63        | 1.36%   |
| Syntek Integrated Camera                            | 59        | 1.27%   |
| Acer BisonCam, NB Pro                               | 58        | 1.25%   |
| Quanta HP TrueVision HD Camera                      | 48        | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 48        | 1.04%   |
| Chicony USB2.0 HD UVC WebCam                        | 47        | 1.02%   |
| Quanta HD User Facing                               | 46        | 0.99%   |
| Lite-On Integrated Camera                           | 45        | 0.97%   |
| Acer Integrated Camera                              | 44        | 0.95%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 41        | 0.89%   |
| Bison SunplusIT Integrated Camera                   | 40        | 0.86%   |
| Microdia Integrated Webcam                          | 37        | 0.8%    |
| Chicony HD User Facing                              | 37        | 0.8%    |
| Sunplus HD WebCam                                   | 35        | 0.76%   |
| Chicony Integrated Camera (1280x720@30)             | 34        | 0.73%   |
| Quanta VGA WebCam                                   | 33        | 0.71%   |
| Chicony HP TrueVision HD Camera                     | 33        | 0.71%   |
| Quanta HP HD Camera                                 | 32        | 0.69%   |
| Bison Lenovo EasyCamera                             | 32        | 0.69%   |
| Lite-On HP HD Camera                                | 30        | 0.65%   |
| Chicony USB2.0 Camera                               | 28        | 0.6%    |
| Realtek Integrated Webcam                           | 27        | 0.58%   |
| Bison HD Webcam                                     | 27        | 0.58%   |
| Realtek USB Camera                                  | 26        | 0.56%   |
| Bison Lenovo Integrated Webcam                      | 26        | 0.56%   |
| Chicony HP Truevision HD                            | 25        | 0.54%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 25        | 0.54%   |
| Sonix USB2.0 HD UVC WebCam                          | 24        | 0.52%   |
| Chicony USB2.0 VGA UVC WebCam                       | 24        | 0.52%   |
| Chicony EasyCamera                                  | 24        | 0.52%   |
| Apple Built-in iSight                               | 23        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 309       | 32.12%  |
| Synaptics                          | 306       | 31.81%  |
| Shenzhen Goodix Technology         | 124       | 12.89%  |
| Upek                               | 56        | 5.82%   |
| AuthenTec                          | 56        | 5.82%   |
| Elan Microelectronics              | 51        | 5.3%    |
| LighTuning Technology              | 30        | 3.12%   |
| STMicroelectronics                 | 19        | 1.98%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 0.52%   |
| Focal-systems.Corp                 | 2         | 0.21%   |
| DigitalPersona                     | 2         | 0.21%   |
| Samsung Electronics                | 1         | 0.1%    |
| Microsoft                          | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 134       | 13.93%  |
| Shenzhen Goodix  Fingerprint Device                                        | 78        | 8.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 63        | 6.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 59        | 6.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 58        | 6.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 50        | 5.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 47        | 4.89%   |
| Validity Sensors Synaptics WBDI                                            | 28        | 2.91%   |
| Elan ELAN:Fingerprint                                                      | 28        | 2.91%   |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 2.49%   |
| Elan ELAN:ARM-M4                                                           | 23        | 2.39%   |
| AuthenTec AES2810                                                          | 23        | 2.39%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 22        | 2.29%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 2.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 20        | 2.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 19        | 1.98%   |
| Synaptics Fingerprint reader [HP G6]                                       | 18        | 1.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.77%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 1.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 16        | 1.66%   |
| Validity Sensors VFS491                                                    | 14        | 1.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.46%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.35%   |
| Synaptics UWP WBDI Device                                                  | 13        | 1.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.14%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.04%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.04%   |
| Synaptics  WBDI                                                            | 9         | 0.94%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 0.83%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 8         | 0.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 0.83%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.62%   |
| Synaptics WBDI                                                             | 6         | 0.62%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.62%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 0.52%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.52%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.52%   |
| Unknown                                                                    | 4         | 0.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 197       | 39.09%  |
| Alcor Micro               | 188       | 37.3%   |
| Upek                      | 35        | 6.94%   |
| Lenovo                    | 32        | 6.35%   |
| O2 Micro                  | 31        | 6.15%   |
| Gemalto (was Gemplus)     | 5         | 0.99%   |
| Yubico.com                | 4         | 0.79%   |
| Clay Logic                | 3         | 0.6%    |
| SCM Microsystems          | 2         | 0.4%    |
| Aladdin Knowledge Systems | 2         | 0.4%    |
| Advanced Card Systems     | 2         | 0.4%    |
| OmniKey                   | 1         | 0.2%    |
| Cherry                    | 1         | 0.2%    |
| C3PO                      | 1         | 0.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 185       | 36.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 56        | 11.11%  |
| Broadcom 58200                                                               | 53        | 10.52%  |
| Broadcom 5880                                                                | 50        | 9.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 36        | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 35        | 6.94%   |
| Lenovo Integrated Smart Card Reader                                          | 32        | 6.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 5.16%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 0.99%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.6%    |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.6%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.4%    |
| Clay Logic Nitrokey Start                                                    | 2         | 0.4%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.4%    |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.4%    |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.2%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.2%    |
| OmniKey CardMan 4321                                                         | 1         | 0.2%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.2%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.2%    |
| C3PO LTC31v2                                                                 | 1         | 0.2%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.2%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3373      | 57.08%  |
| 1     | 1916      | 32.43%  |
| 2     | 484       | 8.19%   |
| 3     | 115       | 1.95%   |
| 4     | 13        | 0.22%   |
| 5     | 7         | 0.12%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 957       | 30.4%   |
| Graphics card            | 794       | 25.22%  |
| Chipcard                 | 463       | 14.71%  |
| Net/wireless             | 284       | 9.02%   |
| Multimedia controller    | 275       | 8.74%   |
| Camera                   | 96        | 3.05%   |
| Bluetooth                | 70        | 2.22%   |
| Card reader              | 49        | 1.56%   |
| Storage                  | 43        | 1.37%   |
| Communication controller | 39        | 1.24%   |
| Sound                    | 24        | 0.76%   |
| Net/ethernet             | 19        | 0.6%    |
| Network                  | 11        | 0.35%   |
| Modem                    | 8         | 0.25%   |
| Flash memory             | 6         | 0.19%   |
| Wireless                 | 4         | 0.13%   |
| Unassigned class         | 2         | 0.06%   |
| Firewire controller      | 2         | 0.06%   |
| Tv card                  | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

