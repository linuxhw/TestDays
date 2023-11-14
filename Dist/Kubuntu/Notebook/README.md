Kubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Kubuntu.

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

Total: 3349

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15 3511            | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| HP            | ProBook 440 G7              | [1d1311204e](https://linux-hardware.org/?probe=1d1311204e) | Nov 05, 2023 |
| HP            | EliteBook 8470p             | [f154c5979f](https://linux-hardware.org/?probe=f154c5979f) | Nov 05, 2023 |
| HP            | Pavilion 15                 | [dd81ed04ea](https://linux-hardware.org/?probe=dd81ed04ea) | Nov 04, 2023 |
| HP            | Notebook                    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| DEXP          | Aquilon C14                 | [b91d7803a2](https://linux-hardware.org/?probe=b91d7803a2) | Nov 03, 2023 |
| Dell          | Latitude E7470              | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [3030ad2bc8](https://linux-hardware.org/?probe=3030ad2bc8) | Nov 02, 2023 |
| HUAWEI        | KPL-W0X                     | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | [6aa1f3a294](https://linux-hardware.org/?probe=6aa1f3a294) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | [3e65346dfd](https://linux-hardware.org/?probe=3e65346dfd) | Nov 02, 2023 |
| Wortmann      | 1220777_1400328             | [778b1abc73](https://linux-hardware.org/?probe=778b1abc73) | Nov 02, 2023 |
| Dell          | XPS 15 9570                 | [2efa290a39](https://linux-hardware.org/?probe=2efa290a39) | Nov 02, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [cde7923bf2](https://linux-hardware.org/?probe=cde7923bf2) | Nov 01, 2023 |
| Samsung       | 730QCJ/730QCR               | [67863a015a](https://linux-hardware.org/?probe=67863a015a) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | [f65225d50a](https://linux-hardware.org/?probe=f65225d50a) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | [69f7a5ebed](https://linux-hardware.org/?probe=69f7a5ebed) | Nov 01, 2023 |
| Sony          | VPCSA3J1E                   | [99b0d275ec](https://linux-hardware.org/?probe=99b0d275ec) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| Dell          | Latitude 7290               | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | [1e3f228931](https://linux-hardware.org/?probe=1e3f228931) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | [10382e8ed6](https://linux-hardware.org/?probe=10382e8ed6) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | [ebcacada49](https://linux-hardware.org/?probe=ebcacada49) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | [d8658ea415](https://linux-hardware.org/?probe=d8658ea415) | Oct 31, 2023 |
| Acer          | Aspire AV15-51              | [84064baf19](https://linux-hardware.org/?probe=84064baf19) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 15            | [2cad75b0fc](https://linux-hardware.org/?probe=2cad75b0fc) | Oct 31, 2023 |
| Dell          | Latitude 5530               | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Acer          | Aspire A715-51G             | [7ffe987b92](https://linux-hardware.org/?probe=7ffe987b92) | Oct 30, 2023 |
| Dell          | Precision M6800             | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| HP            | Laptop 17-cp0xxx            | [9b3c09e73a](https://linux-hardware.org/?probe=9b3c09e73a) | Oct 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e340ddc535](https://linux-hardware.org/?probe=e340ddc535) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [3bc6d6cfda](https://linux-hardware.org/?probe=3bc6d6cfda) | Oct 27, 2023 |
| EXTRA Comp... | MS-1758                     | [eced546e79](https://linux-hardware.org/?probe=eced546e79) | Oct 26, 2023 |
| Acer          | Nitro AN515-47              | [8516768801](https://linux-hardware.org/?probe=8516768801) | Oct 26, 2023 |
| HP            | Pavilion 17                 | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| HP            | ProBook 450 G7              | [d1c293b080](https://linux-hardware.org/?probe=d1c293b080) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| Shanghai Z... | ZXE CRB                     | [35b07b6e34](https://linux-hardware.org/?probe=35b07b6e34) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c64594fac3](https://linux-hardware.org/?probe=c64594fac3) | Oct 25, 2023 |
| WUYING        | NS01-4BGXG                  | [5c999216df](https://linux-hardware.org/?probe=5c999216df) | Oct 25, 2023 |
| HP            | Pavilion g7                 | [3bd963fd9e](https://linux-hardware.org/?probe=3bd963fd9e) | Oct 24, 2023 |
| HP            | 14                          | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | [0f08eb340b](https://linux-hardware.org/?probe=0f08eb340b) | Oct 24, 2023 |
| Dell          | Inspiron 5737               | [06247cab2e](https://linux-hardware.org/?probe=06247cab2e) | Oct 24, 2023 |
| HP            | Pavilion Notebook           | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [55c5bbce9f](https://linux-hardware.org/?probe=55c5bbce9f) | Oct 23, 2023 |
| AZW           | SEi                         | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| Dell          | Latitude E6520              | [5d73c1d444](https://linux-hardware.org/?probe=5d73c1d444) | Oct 22, 2023 |
| HP            | ProBook 4340s               | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| HP            | Laptop 15-ef0xxx            | [db0826b2fc](https://linux-hardware.org/?probe=db0826b2fc) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | [5962f780e9](https://linux-hardware.org/?probe=5962f780e9) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | [9990a91f59](https://linux-hardware.org/?probe=9990a91f59) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [130d199934](https://linux-hardware.org/?probe=130d199934) | Oct 21, 2023 |
| Dell          | Latitude E7470              | [4870f90403](https://linux-hardware.org/?probe=4870f90403) | Oct 20, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [91f29a5a63](https://linux-hardware.org/?probe=91f29a5a63) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [4bfe18fe76](https://linux-hardware.org/?probe=4bfe18fe76) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [e83ad29e5e](https://linux-hardware.org/?probe=e83ad29e5e) | Oct 20, 2023 |
| ASUSTek       | X450LCP                     | [ae3fec47c6](https://linux-hardware.org/?probe=ae3fec47c6) | Oct 19, 2023 |
| Acer          | AOD270                      | [20d5a5477c](https://linux-hardware.org/?probe=20d5a5477c) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| HP            | G60                         | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| GPU Compan... | GWTN141-10                  | [413edf8cdb](https://linux-hardware.org/?probe=413edf8cdb) | Oct 18, 2023 |
| Dell          | Precision 7520              | [bd78f68578](https://linux-hardware.org/?probe=bd78f68578) | Oct 18, 2023 |
| Dell          | Latitude E5470              | [be8c08b665](https://linux-hardware.org/?probe=be8c08b665) | Oct 18, 2023 |
| Dell          | G7 7790                     | [250d61d6a7](https://linux-hardware.org/?probe=250d61d6a7) | Oct 18, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [05ee51f822](https://linux-hardware.org/?probe=05ee51f822) | Oct 18, 2023 |
| GMKtec        | NucBox5                     | [4b4319490d](https://linux-hardware.org/?probe=4b4319490d) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| HP            | ProBook 440 G6              | [5860734f3a](https://linux-hardware.org/?probe=5860734f3a) | Oct 16, 2023 |
| Avell High... | C62 MOB                     | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| Dell          | Latitude E7470              | [59258fc186](https://linux-hardware.org/?probe=59258fc186) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| Acer          | Aspire A317-32              | [e4bcb7e688](https://linux-hardware.org/?probe=e4bcb7e688) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | [92049beb26](https://linux-hardware.org/?probe=92049beb26) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | [3eff97b04d](https://linux-hardware.org/?probe=3eff97b04d) | Oct 15, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [7045758f33](https://linux-hardware.org/?probe=7045758f33) | Oct 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [f18ac93db8](https://linux-hardware.org/?probe=f18ac93db8) | Oct 13, 2023 |
| Dell          | Latitude 7490               | [b5e38fe27e](https://linux-hardware.org/?probe=b5e38fe27e) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| HP            | EliteBook 8770w             | [bf26581f5d](https://linux-hardware.org/?probe=bf26581f5d) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [e6c5f903ce](https://linux-hardware.org/?probe=e6c5f903ce) | Oct 12, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [f48331f12b](https://linux-hardware.org/?probe=f48331f12b) | Oct 12, 2023 |
| HP            | ProBook 4540s               | [c3be7c74a0](https://linux-hardware.org/?probe=c3be7c74a0) | Oct 11, 2023 |
| Dell          | Vostro 5490                 | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Notebook      | W510LU                      | [7b46aa1486](https://linux-hardware.org/?probe=7b46aa1486) | Oct 11, 2023 |
| Alienware     | m16 R1                      | [6ea5ba513f](https://linux-hardware.org/?probe=6ea5ba513f) | Oct 11, 2023 |
| Alienware     | m16 R1                      | [f9c4374e7c](https://linux-hardware.org/?probe=f9c4374e7c) | Oct 11, 2023 |
| Dell          | Inspiron 3520               | [3fe42a607c](https://linux-hardware.org/?probe=3fe42a607c) | Oct 10, 2023 |
| Dell          | Latitude 5511               | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| Dell          | Latitude 5511               | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | Latitude 5530               | [95ec4384f9](https://linux-hardware.org/?probe=95ec4384f9) | Oct 10, 2023 |
| Dell          | Latitude 5530               | [4d218edfa4](https://linux-hardware.org/?probe=4d218edfa4) | Oct 10, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [3ba4207fd0](https://linux-hardware.org/?probe=3ba4207fd0) | Oct 09, 2023 |
| Dell          | Inspiron 7400               | [38b7ffd223](https://linux-hardware.org/?probe=38b7ffd223) | Oct 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7513e708f6](https://linux-hardware.org/?probe=7513e708f6) | Oct 07, 2023 |
| Medion        | E15302                      | [d26c76cedf](https://linux-hardware.org/?probe=d26c76cedf) | Oct 07, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [5ff0e17804](https://linux-hardware.org/?probe=5ff0e17804) | Oct 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [5b84610e15](https://linux-hardware.org/?probe=5b84610e15) | Oct 06, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [e796c2f9ba](https://linux-hardware.org/?probe=e796c2f9ba) | Oct 05, 2023 |
| Google        | Woomax                      | [2163941472](https://linux-hardware.org/?probe=2163941472) | Oct 04, 2023 |
| Dell          | Latitude 7490               | [ff1fcbaff6](https://linux-hardware.org/?probe=ff1fcbaff6) | Oct 04, 2023 |
| Dell          | Latitude 7490               | [7eca4901d4](https://linux-hardware.org/?probe=7eca4901d4) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [2fdd309c6a](https://linux-hardware.org/?probe=2fdd309c6a) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | [a9e2c9b64e](https://linux-hardware.org/?probe=a9e2c9b64e) | Oct 03, 2023 |
| Toshiba       | Satellite P850              | [4074b6cda1](https://linux-hardware.org/?probe=4074b6cda1) | Oct 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3f7231bda4](https://linux-hardware.org/?probe=3f7231bda4) | Oct 03, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [f349819e0a](https://linux-hardware.org/?probe=f349819e0a) | Oct 02, 2023 |
| Google        | Blorb                       | [04e37bafe3](https://linux-hardware.org/?probe=04e37bafe3) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [122f1d4ca8](https://linux-hardware.org/?probe=122f1d4ca8) | Oct 02, 2023 |
| Schenker      | VIA 15 Pro (M22)            | [1919690674](https://linux-hardware.org/?probe=1919690674) | Oct 01, 2023 |
| HP            | Pavilion 11 x360 PC         | [b3eb082c5e](https://linux-hardware.org/?probe=b3eb082c5e) | Oct 01, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [1330485afc](https://linux-hardware.org/?probe=1330485afc) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| HP            | ProBook 650 G1              | [c9aca83f04](https://linux-hardware.org/?probe=c9aca83f04) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| Alienware     | x15 R1                      | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| ASUSTek       | K72Jr                       | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| HP            | EliteBook 8770w             | [3286090099](https://linux-hardware.org/?probe=3286090099) | Sep 27, 2023 |
| ASUSTek       | K72Jr                       | [9f32819945](https://linux-hardware.org/?probe=9f32819945) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| CHIPHD        | NT125D                      | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Lenovo        | B480 20140                  | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Dell          | Latitude E5470              | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| Apple         | MacBookPro9,2               | [2691aa5f87](https://linux-hardware.org/?probe=2691aa5f87) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ad1f9f63c0](https://linux-hardware.org/?probe=ad1f9f63c0) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [d4060b585a](https://linux-hardware.org/?probe=d4060b585a) | Sep 20, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [c7142a0d96](https://linux-hardware.org/?probe=c7142a0d96) | Sep 20, 2023 |
| HP            | ENVY TS 15                  | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| Toshiba       | Satellite Pro C70-B         | [a24c6808ba](https://linux-hardware.org/?probe=a24c6808ba) | Sep 20, 2023 |
| Dell          | Precision 7520              | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| Dell          | Precision 7520              | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [6f676cd559](https://linux-hardware.org/?probe=6f676cd559) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| Dell          | Inspiron 5520               | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| HP            | Compaq 6820s                | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| Acer          | Aspire A515-57              | [a73abd96f1](https://linux-hardware.org/?probe=a73abd96f1) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| Notebook      | P65_P67SA                   | [4d11ae0ff7](https://linux-hardware.org/?probe=4d11ae0ff7) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [20ad52b9a4](https://linux-hardware.org/?probe=20ad52b9a4) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [9ea0aa4b28](https://linux-hardware.org/?probe=9ea0aa4b28) | Sep 10, 2023 |
| Valve         | Jupiter                     | [23da68a72c](https://linux-hardware.org/?probe=23da68a72c) | Sep 09, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | [5180b1e51e](https://linux-hardware.org/?probe=5180b1e51e) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | [6f3051262d](https://linux-hardware.org/?probe=6f3051262d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Notebook      | W65_67SR                    | [7169bc1dbb](https://linux-hardware.org/?probe=7169bc1dbb) | Sep 07, 2023 |
| Google        | Robo360                     | [86308cca01](https://linux-hardware.org/?probe=86308cca01) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| ASUSTek       | G551JM                      | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| Dell          | Latitude 7490               | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Dell          | Latitude E6500              | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| HP            | Notebook                    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [cdf37a1590](https://linux-hardware.org/?probe=cdf37a1590) | Sep 03, 2023 |
| Dell          | Latitude E6500              | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| Dell          | XPS 9315                    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| Avell High... | C62 MOB                     | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| mPTech        | ARC 11.6 128GB HD           | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z580                | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| Dell          | Precision 7780              | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| MSI           | GL65 9SE                    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Irbis         | NB123                       | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Dell          | Latitude E6520              | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| HP            | Laptop 17-ca1xxx            | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Schenker      | XMG PRO (E23)               | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Acer          | Nitro AN517-41              | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| Acer          | Aspire A515-51              | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Medion        | P651x series                | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Google        | Dragonair                   | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| GPD           | G1621-02                    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Precision 7670              | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| Dell          | Latitude E6420              | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| Dell          | Latitude 5530               | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| System76      | Galago Pro                  | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Alienware     | 14                          | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Dell          | Inspiron 16 7610            | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| HP            | G60                         | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Acer          | Aspire A515-45              | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| HP            | G62                         | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| HP            | Presario CQ62               | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| HP            | ENVY Notebook               | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| HP            | ZBook 17 G2                 | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| HP            | Pavilion 15                 | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| Dell          | G3 3779                     | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Unknown       | Unknown                     | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [9400bf75de](https://linux-hardware.org/?probe=9400bf75de) | Jul 09, 2023 |
| Acer          | Predator G3-572             | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Dell          | G3 3779                     | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| HP            | ProBook 650 G1              | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Dell          | Latitude 7530               | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Notebook      | PC5x_7xHP_HR_HS             | [e76be78ba9](https://linux-hardware.org/?probe=e76be78ba9) | Jul 02, 2023 |
| Dell          | G3 3779                     | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Dell          | G3 3779                     | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Dell          | Latitude E5450              | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| HP            | Laptop 14s-dq2xxx           | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Dell          | G3 3590                     | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| HP            | Notebook                    | [db641e216c](https://linux-hardware.org/?probe=db641e216c) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Dell          | Latitude 3310               | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Proline       | V1165C4                     | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Dell          | Latitude E6420              | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Irbis         | NB123                       | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Samsung       | 550XCJ/550XCR               | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Dell          | G3 3779                     | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Dell          | XPS 13 9333                 | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | Notebook                    | [1b099710b7](https://linux-hardware.org/?probe=1b099710b7) | Jun 08, 2023 |
| HP            | Notebook                    | [9bf82397c3](https://linux-hardware.org/?probe=9bf82397c3) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Acer          | Nitro AN515-56              | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| ASUSTek       | K50IJ                       | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| Dell          | Latitude E6500              | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Dell          | G15 5525                    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer          | Aspire A317-53              | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire E5-575               | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Acer          | Aspire A515-45              | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Google        | Bluebird                    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Acer          | Aspire V3-772               | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| Acer          | Aspire V3-772               | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Apple         | MacBookPro9,1               | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Acer          | Aspire A317-53              | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Fujitsu       | LIFEBOOK U748               | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| HP            | 350 G1                      | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME       | B95                         | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Notebook      | NLx0MU                      | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Dell          | Latitude E5530 non-vPro     | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Acer          | Swift SFX14-41G             | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | ENVY TS 15                  | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Dell          | XPS 15 7590                 | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| HP            | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Dell          | Latitude E6500              | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| PC Special... | P65_67RSRP                  | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| Dell          | G3 3590                     | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | Latitude E5470              | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Dell          | Latitude 5420               | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| HP            | EliteBook 8470p             | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| Dell          | Latitude 3570               | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Dell          | XPS 13 9300                 | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Google        | Lars                        | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Razer         | Blade Pro 17 (2019)         | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| HP            | ProBook 440 G5              | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Dell          | Latitude 5480               | [1ab8b910e4](https://linux-hardware.org/?probe=1ab8b910e4) | May 04, 2023 |
| ASUSTek       | X750JB                      | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| Dell          | Inspiron 3593               | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| Acer          | Aspire M5-481T              | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| Samsung       | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Dell          | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Carbon Sys... | Iridium 14                  | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | X510UAR                     | [d96138627b](https://linux-hardware.org/?probe=d96138627b) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| HP            | 630                         | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| Apple         | MacBookPro14,2              | [26a430e092](https://linux-hardware.org/?probe=26a430e092) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| ASUSTek       | X51RL                       | [ca3fb7f6d5](https://linux-hardware.org/?probe=ca3fb7f6d5) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Unknown       | Unknown                     | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| HP            | EliteBook 6930p             | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| Acer          | Aspire A515-45              | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Acer          | Aspire A515-57              | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Dell          | Vostro 15-3568              | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| MSI           | Modern 15 A5M               | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | Vostro 5620                 | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Avell High... | C62 MOB                     | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Clevo         | W340EU                      | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Clevo         | W340EU                      | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| Dell          | Latitude E6420              | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| HP            | Pavilion 11 x360 PC         | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| System76      | Gazelle                     | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Acer          | Aspire A515-46              | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Nitro AN515-45              | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Chuwi         | Hi10 Go                     | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Acer          | Nitro AN517-41              | [ecb7c49d2e](https://linux-hardware.org/?probe=ecb7c49d2e) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| Dell          | Inspiron 5593               | [36db3e5d78](https://linux-hardware.org/?probe=36db3e5d78) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [b265f91d10](https://linux-hardware.org/?probe=b265f91d10) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| ASUSTek       | GL503VD                     | [f4095c61ff](https://linux-hardware.org/?probe=f4095c61ff) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Medion        | E15410                      | [5ba9ffd6a8](https://linux-hardware.org/?probe=5ba9ffd6a8) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| Dell          | Latitude 5491               | [37746d7f71](https://linux-hardware.org/?probe=37746d7f71) | Jan 24, 2023 |
| Medion        | E15410                      | [f7e27f2ba9](https://linux-hardware.org/?probe=f7e27f2ba9) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [df35617170](https://linux-hardware.org/?probe=df35617170) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Dell          | Vostro 1014                 | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| Dell          | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Notebook                    | [1c935be3b1](https://linux-hardware.org/?probe=1c935be3b1) | Jan 18, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| Notebook      | W35xSS_370SS                | [2337667e0f](https://linux-hardware.org/?probe=2337667e0f) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3a97589bc9](https://linux-hardware.org/?probe=3a97589bc9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ed648f1f72](https://linux-hardware.org/?probe=ed648f1f72) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [b9df733a47](https://linux-hardware.org/?probe=b9df733a47) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [75209e7521](https://linux-hardware.org/?probe=75209e7521) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Dell          | Inspiron 5570               | [4ebc1e97c5](https://linux-hardware.org/?probe=4ebc1e97c5) | Jan 07, 2023 |
| Dell          | Inspiron 5570               | [86b0308f38](https://linux-hardware.org/?probe=86b0308f38) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| Acer          | Swift SF314-71              | [21ebb26df9](https://linux-hardware.org/?probe=21ebb26df9) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Acer          | Aspire M5-583P              | [1182d7305d](https://linux-hardware.org/?probe=1182d7305d) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Unknown       | Unknown                     | [7a85f424f5](https://linux-hardware.org/?probe=7a85f424f5) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [059e72c9a0](https://linux-hardware.org/?probe=059e72c9a0) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| MSI           | Alpha 17 B5EEK              | [a5881c627c](https://linux-hardware.org/?probe=a5881c627c) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion dv7                | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [60a56500f1](https://linux-hardware.org/?probe=60a56500f1) | Dec 18, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [89166d1da4](https://linux-hardware.org/?probe=89166d1da4) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c18a20ec35](https://linux-hardware.org/?probe=c18a20ec35) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| HP            | Pavilion g7                 | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| HP            | 550                         | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Monster       | TULPAR T7 V21.6             | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Google        | Kled                        | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Dell          | G3 3779                     | [3e85396dae](https://linux-hardware.org/?probe=3e85396dae) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| GPD           | G1621-02                    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| Dell          | Latitude E6440              | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| HP            | Unknown                     | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 758       | 30.95%  |
| Kubuntu 22.04   | 628       | 25.64%  |
| Kubuntu 22.10   | 157       | 6.41%   |
| Kubuntu 23.04   | 156       | 6.37%   |
| Kubuntu 21.10   | 151       | 6.17%   |
| Kubuntu 20.10   | 141       | 5.76%   |
| Kubuntu 21.04   | 126       | 5.14%   |
| Kubuntu 19.10   | 105       | 4.29%   |
| Kubuntu 18.04   | 102       | 4.16%   |
| Kubuntu 11      | 48        | 1.96%   |
| Kubuntu 23.10   | 30        | 1.22%   |
| Kubuntu 11.1    | 18        | 0.73%   |
| Kubuntu 19.04   | 9         | 0.37%   |
| Kubuntu 2.0     | 4         | 0.16%   |
| Kubuntu 16.04   | 4         | 0.16%   |
| Kubuntu 18.10   | 3         | 0.12%   |
| Kubuntu 14.04   | 3         | 0.12%   |
| Kubuntu         | 3         | 0.12%   |
| Kubuntu 20.08.3 | 1         | 0.04%   |
| Kubuntu 17.10   | 1         | 0.04%   |
| Kubuntu 17.04   | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Kubuntu | 2349      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 55        | 2.05%   |
| 6.2.0-20-generic  | 54        | 2.02%   |
| 5.15.0-52-generic | 51        | 1.9%    |
| 5.15.0-56-generic | 44        | 1.64%   |
| 5.19.0-35-generic | 38        | 1.42%   |
| 6.2.0-26-generic  | 35        | 1.31%   |
| 5.4.0-52-generic  | 35        | 1.31%   |
| 5.13.0-39-generic | 35        | 1.31%   |
| 5.4.0-48-generic  | 34        | 1.27%   |
| 5.15.0-48-generic | 30        | 1.12%   |
| 5.19.0-26-generic | 28        | 1.05%   |
| 5.15.0-58-generic | 28        | 1.05%   |
| 6.2.0-34-generic  | 27        | 1.01%   |
| 5.4.0-58-generic  | 27        | 1.01%   |
| 5.13.0-28-generic | 27        | 1.01%   |
| 5.15.0-46-generic | 26        | 0.97%   |
| 5.13.0-30-generic | 26        | 0.97%   |
| 5.19.0-23-generic | 25        | 0.93%   |
| 5.11.0-25-generic | 25        | 0.93%   |
| 5.4.0-40-generic  | 24        | 0.9%    |
| 5.19.0-38-generic | 24        | 0.9%    |
| 5.15.0-53-generic | 24        | 0.9%    |
| 6.2.0-33-generic  | 22        | 0.82%   |
| 5.3.0-40-generic  | 22        | 0.82%   |
| 5.19.0-31-generic | 22        | 0.82%   |
| 5.15.0-47-generic | 22        | 0.82%   |
| 5.15.0-43-generic | 22        | 0.82%   |
| 5.15.0-60-generic | 21        | 0.78%   |
| 5.11.0-37-generic | 21        | 0.78%   |
| 5.15.0-41-generic | 20        | 0.75%   |
| 6.2.0-32-generic  | 19        | 0.71%   |
| 5.4.0-47-generic  | 19        | 0.71%   |
| 5.4.0-29-generic  | 19        | 0.71%   |
| 5.13.0-22-generic | 19        | 0.71%   |
| 5.4.0-37-generic  | 18        | 0.67%   |
| 5.13.0-27-generic | 18        | 0.67%   |
| 5.4.0-65-generic  | 17        | 0.63%   |
| 5.3.0-42-generic  | 17        | 0.63%   |
| 5.15.0-25-generic | 17        | 0.63%   |
| 5.13.0-40-generic | 17        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 484       | 19.34%  |
| 5.4.0   | 482       | 19.26%  |
| 5.13.0  | 258       | 10.31%  |
| 5.19.0  | 247       | 9.87%   |
| 5.8.0   | 221       | 8.83%   |
| 6.2.0   | 212       | 8.47%   |
| 5.11.0  | 185       | 7.39%   |
| 5.3.0   | 129       | 5.16%   |
| 4.15.0  | 38        | 1.52%   |
| 6.5.0   | 26        | 1.04%   |
| 5.0.0   | 17        | 0.68%   |
| 5.10.0  | 13        | 0.52%   |
| 5.17.0  | 11        | 0.44%   |
| 5.14.0  | 8         | 0.32%   |
| 5.6.0   | 7         | 0.28%   |
| 6.1.0   | 6         | 0.24%   |
| 6.0.0   | 6         | 0.24%   |
| 6.0.9   | 5         | 0.2%    |
| 5.7.0   | 4         | 0.16%   |
| 4.4.0   | 4         | 0.16%   |
| 4.18.0  | 4         | 0.16%   |
| 6.4.8   | 3         | 0.12%   |
| 6.3.8   | 3         | 0.12%   |
| 5.12.0  | 3         | 0.12%   |
| 6.4.0   | 2         | 0.08%   |
| 6.3.7   | 2         | 0.08%   |
| 6.3.4   | 2         | 0.08%   |
| 6.3.0   | 2         | 0.08%   |
| 6.2.2   | 2         | 0.08%   |
| 6.2.16  | 2         | 0.08%   |
| 6.1.8   | 2         | 0.08%   |
| 6.1.12  | 2         | 0.08%   |
| 6.0.7   | 2         | 0.08%   |
| 5.9.10  | 2         | 0.08%   |
| 5.9.0   | 2         | 0.08%   |
| 5.19.5  | 2         | 0.08%   |
| 5.18.10 | 2         | 0.08%   |
| 5.15.5  | 2         | 0.08%   |
| 5.15.34 | 2         | 0.08%   |
| 5.13.1  | 2         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 495       | 19.82%  |
| 5.4     | 485       | 19.42%  |
| 5.13    | 264       | 10.57%  |
| 5.19    | 251       | 10.05%  |
| 5.8     | 229       | 9.17%   |
| 6.2     | 219       | 8.77%   |
| 5.11    | 189       | 7.57%   |
| 5.3     | 130       | 5.21%   |
| 4.15    | 38        | 1.52%   |
| 6.5     | 29        | 1.16%   |
| 5.10    | 17        | 0.68%   |
| 5.0     | 17        | 0.68%   |
| 6.1     | 16        | 0.64%   |
| 5.17    | 14        | 0.56%   |
| 5.14    | 14        | 0.56%   |
| 6.3     | 13        | 0.52%   |
| 6.0     | 13        | 0.52%   |
| 5.12    | 9         | 0.36%   |
| 5.6     | 8         | 0.32%   |
| 5.9     | 7         | 0.28%   |
| 6.4     | 6         | 0.24%   |
| 5.7     | 6         | 0.24%   |
| 5.18    | 5         | 0.2%    |
| 5.16    | 5         | 0.2%    |
| 4.18    | 5         | 0.2%    |
| 4.4     | 4         | 0.16%   |
| 5.5     | 3         | 0.12%   |
| 4.10    | 2         | 0.08%   |
| 5.1     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2346      | 99.87%  |
| i686   | 3         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 1855      | 77.84%  |
| KDE        | 495       | 20.77%  |
| GNOME      | 13        | 0.55%   |
| Cinnamon   | 5         | 0.21%   |
| MATE       | 3         | 0.13%   |
| KDE4       | 3         | 0.13%   |
| Budgie     | 3         | 0.13%   |
| XFCE       | 1         | 0.04%   |
| X-Cinnamon | 1         | 0.04%   |
| LXQt       | 1         | 0.04%   |
| i3         | 1         | 0.04%   |
| GNUstep    | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2236      | 94.43%  |
| Wayland | 112       | 4.73%   |
| Tty     | 20        | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1466      | 61.42%  |
| Unknown | 770       | 32.26%  |
| GDM     | 62        | 2.6%    |
| GDM3    | 43        | 1.8%    |
| LightDM | 32        | 1.34%   |
| TDM     | 11        | 0.46%   |
| SLiM    | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |
| KDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1014      | 42.84%  |
| de_DE   | 189       | 7.98%   |
| ru_RU   | 121       | 5.11%   |
| en_GB   | 108       | 4.56%   |
| it_IT   | 102       | 4.31%   |
| pt_BR   | 100       | 4.22%   |
| fr_FR   | 91        | 3.84%   |
| en_IN   | 60        | 2.53%   |
| es_ES   | 55        | 2.32%   |
| en_CA   | 50        | 2.11%   |
| Unknown | 43        | 1.82%   |
| pl_PL   | 42        | 1.77%   |
| en_AU   | 36        | 1.52%   |
| C       | 23        | 0.97%   |
| es_MX   | 18        | 0.76%   |
| cs_CZ   | 18        | 0.76%   |
| hu_HU   | 17        | 0.72%   |
| en_ZA   | 15        | 0.63%   |
| ru_UA   | 14        | 0.59%   |
| tr_TR   | 13        | 0.55%   |
| en_NZ   | 12        | 0.51%   |
| zh_CN   | 11        | 0.46%   |
| nl_NL   | 11        | 0.46%   |
| en_IE   | 10        | 0.42%   |
| es_CO   | 9         | 0.38%   |
| es_AR   | 9         | 0.38%   |
| sv_SE   | 7         | 0.3%    |
| pt_PT   | 7         | 0.3%    |
| fr_BE   | 7         | 0.3%    |
| es_CL   | 7         | 0.3%    |
| de_CH   | 7         | 0.3%    |
| fi_FI   | 6         | 0.25%   |
| es_VE   | 6         | 0.25%   |
| en_PH   | 6         | 0.25%   |
| de_AT   | 6         | 0.25%   |
| ca_ES   | 6         | 0.25%   |
| sk_SK   | 5         | 0.21%   |
| nl_BE   | 5         | 0.21%   |
| fr_CH   | 5         | 0.21%   |
| en_SG   | 5         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1451      | 60.79%  |
| BIOS | 936       | 39.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2100      | 88.72%  |
| Btrfs   | 82        | 3.46%   |
| Tmpfs   | 79        | 3.34%   |
| Overlay | 68        | 2.87%   |
| Xfs     | 15        | 0.63%   |
| Zfs     | 12        | 0.51%   |
| Unknown | 6         | 0.25%   |
| Ext2    | 3         | 0.13%   |
| Ext3    | 2         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1315      | 55.25%  |
| Unknown | 888       | 37.31%  |
| MBR     | 177       | 7.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2136      | 90.51%  |
| Yes       | 224       | 9.49%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1491      | 63.04%  |
| Yes       | 874       | 36.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 547       | 23.29%  |
| Dell                   | 429       | 18.26%  |
| Hewlett-Packard        | 408       | 17.37%  |
| ASUSTek Computer       | 236       | 10.05%  |
| Acer                   | 175       | 7.45%   |
| MSI                    | 61        | 2.6%    |
| HUAWEI                 | 47        | 2%      |
| Samsung Electronics    | 43        | 1.83%   |
| Apple                  | 36        | 1.53%   |
| Toshiba                | 28        | 1.19%   |
| Notebook               | 28        | 1.19%   |
| Sony                   | 22        | 0.94%   |
| Google                 | 21        | 0.89%   |
| TUXEDO                 | 20        | 0.85%   |
| Unknown                | 15        | 0.64%   |
| Timi                   | 14        | 0.6%    |
| Alienware              | 14        | 0.6%    |
| Gigabyte Technology    | 13        | 0.55%   |
| Positivo               | 10        | 0.43%   |
| Medion                 | 9         | 0.38%   |
| Fujitsu                | 9         | 0.38%   |
| System76               | 8         | 0.34%   |
| PC Specialist          | 8         | 0.34%   |
| GPU Company            | 7         | 0.3%    |
| Chuwi                  | 7         | 0.3%    |
| Schenker               | 6         | 0.26%   |
| Razer                  | 6         | 0.26%   |
| Packard Bell           | 6         | 0.26%   |
| LG Electronics         | 6         | 0.26%   |
| Intel                  | 6         | 0.26%   |
| Panasonic              | 5         | 0.21%   |
| Framework              | 5         | 0.21%   |
| HONOR                  | 4         | 0.17%   |
| Fujitsu Siemens        | 4         | 0.17%   |
| Avell High Performance | 4         | 0.17%   |
| Irbis                  | 3         | 0.13%   |
| Haier                  | 3         | 0.13%   |
| GPD                    | 3         | 0.13%   |
| Digma                  | 3         | 0.13%   |
| Clevo                  | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 26        | 1.11%   |
| HP Notebook                      | 10        | 0.43%   |
| HP Pavilion g6                   | 9         | 0.38%   |
| HP Pavilion dv6                  | 9         | 0.38%   |
| Dell XPS 15 9560                 | 9         | 0.38%   |
| HUAWEI NBLK-WAX9X                | 8         | 0.34%   |
| HP Pavilion 15                   | 8         | 0.34%   |
| Dell XPS 15 9570                 | 8         | 0.34%   |
| HP Pavilion dv7                  | 7         | 0.3%    |
| HP EliteBook 840 G5              | 7         | 0.3%    |
| HUAWEI HVY-WXX9                  | 6         | 0.26%   |
| HP Pavilion Notebook             | 6         | 0.26%   |
| HP EliteBook 840 G6              | 6         | 0.26%   |
| HP EliteBook 840 G3              | 6         | 0.26%   |
| Dell XPS 15 7590                 | 6         | 0.26%   |
| Dell Latitude 5480               | 6         | 0.26%   |
| HP 255 G8 Notebook PC            | 5         | 0.21%   |
| GPU Company GWTC116-2            | 5         | 0.21%   |
| Dell XPS 13 9310                 | 5         | 0.21%   |
| Dell Latitude E6540              | 5         | 0.21%   |
| Dell Latitude E6420              | 5         | 0.21%   |
| Dell Latitude 7490               | 5         | 0.21%   |
| Dell Latitude 5420               | 5         | 0.21%   |
| Dell Inspiron 5570               | 5         | 0.21%   |
| Dell Inspiron 15-3567            | 5         | 0.21%   |
| Acer Aspire A515-45              | 5         | 0.21%   |
| Lenovo Z50-75 80EC               | 4         | 0.17%   |
| Lenovo ThinkBook 15 G2 ITL 20VE  | 4         | 0.17%   |
| Lenovo Legion Y530-15ICH 81FV    | 4         | 0.17%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ | 4         | 0.17%   |
| Lenovo Legion 5 15ARH05H 82B1    | 4         | 0.17%   |
| Lenovo IdeaPad S145-15API 81V7   | 4         | 0.17%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7 | 4         | 0.17%   |
| Lenovo IdeaPad 5 15ARE05 81YQ    | 4         | 0.17%   |
| Lenovo IdeaPad 330-15IKB 81DE    | 4         | 0.17%   |
| Lenovo G50-70 20351              | 4         | 0.17%   |
| HUAWEI KLVL-WXX9                 | 4         | 0.17%   |
| HUAWEI CREM-WXX9                 | 4         | 0.17%   |
| HP ProBook 6470b                 | 4         | 0.17%   |
| HP ProBook 450 G7                | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 285       | 12.13%  |
| Dell Latitude      | 154       | 6.56%   |
| Lenovo IdeaPad     | 120       | 5.11%   |
| Acer Aspire        | 110       | 4.68%   |
| Dell Inspiron      | 101       | 4.3%    |
| HP Pavilion        | 94        | 4%      |
| Dell XPS           | 72        | 3.07%   |
| HP ProBook         | 68        | 2.89%   |
| HP EliteBook       | 64        | 2.72%   |
| ASUS VivoBook      | 60        | 2.55%   |
| HP Laptop          | 59        | 2.51%   |
| Dell Precision     | 41        | 1.75%   |
| Lenovo Legion      | 31        | 1.32%   |
| Dell Vostro        | 28        | 1.19%   |
| Acer Nitro         | 28        | 1.19%   |
| Unknown            | 26        | 1.11%   |
| Toshiba Satellite  | 24        | 1.02%   |
| Lenovo ThinkBook   | 24        | 1.02%   |
| ASUS ASUS          | 24        | 1.02%   |
| ASUS ROG           | 20        | 0.85%   |
| HP ZBook           | 19        | 0.81%   |
| Acer Swift         | 18        | 0.77%   |
| HP ENVY            | 16        | 0.68%   |
| ASUS Zenbook       | 14        | 0.6%    |
| Dell G3            | 12        | 0.51%   |
| Lenovo Yoga        | 11        | 0.47%   |
| ASUS TUF           | 11        | 0.47%   |
| HP Notebook        | 10        | 0.43%   |
| HP 255             | 10        | 0.43%   |
| HUAWEI NBLK-WAX9X  | 8         | 0.34%   |
| HP 250             | 8         | 0.34%   |
| Fujitsu LIFEBOOK   | 8         | 0.34%   |
| MSI Prestige       | 7         | 0.3%    |
| MSI Modern         | 7         | 0.3%    |
| HP OMEN            | 7         | 0.3%    |
| HP Compaq          | 7         | 0.3%    |
| Apple MacBookPro11 | 7         | 0.3%    |
| Acer Predator      | 7         | 0.3%    |
| Razer Blade        | 6         | 0.26%   |
| HUAWEI HVY-WXX9    | 6         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 310       | 13.2%   |
| 2019 | 302       | 12.86%  |
| 2021 | 271       | 11.54%  |
| 2018 | 204       | 8.68%   |
| 2012 | 157       | 6.68%   |
| 2017 | 155       | 6.6%    |
| 2013 | 143       | 6.09%   |
| 2014 | 142       | 6.05%   |
| 2011 | 142       | 6.05%   |
| 2022 | 127       | 5.41%   |
| 2016 | 113       | 4.81%   |
| 2015 | 85        | 3.62%   |
| 2010 | 59        | 2.51%   |
| 2008 | 56        | 2.38%   |
| 2023 | 35        | 1.49%   |
| 2009 | 29        | 1.23%   |
| 2007 | 19        | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2349      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2086      | 87.94%  |
| Enabled  | 286       | 12.06%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2321      | 98.81%  |
| Yes  | 28        | 1.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 657       | 27.78%  |
| 16.01-24.0  | 550       | 23.26%  |
| 8.01-16.0   | 443       | 18.73%  |
| 3.01-4.0    | 320       | 13.53%  |
| 32.01-64.0  | 252       | 10.66%  |
| 24.01-32.0  | 43        | 1.82%   |
| 1.01-2.0    | 43        | 1.82%   |
| 64.01-256.0 | 40        | 1.69%   |
| 2.01-3.0    | 17        | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 673       | 26.57%  |
| 4.01-8.0   | 582       | 22.98%  |
| 1.01-2.0   | 581       | 22.94%  |
| 3.01-4.0   | 440       | 17.37%  |
| 8.01-16.0  | 182       | 7.19%   |
| 0.51-1.0   | 46        | 1.82%   |
| 16.01-24.0 | 20        | 0.79%   |
| 24.01-32.0 | 6         | 0.24%   |
| 32.01-64.0 | 3         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1657      | 69.45%  |
| 2      | 625       | 26.19%  |
| 3      | 77        | 3.23%   |
| 4      | 16        | 0.67%   |
| 0      | 9         | 0.38%   |
| 6      | 1         | 0.04%   |
| 5      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1761      | 74.75%  |
| Yes       | 595       | 25.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1830      | 77.64%  |
| No        | 527       | 22.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2326      | 99.02%  |
| No        | 23        | 0.98%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1992      | 84.19%  |
| No        | 374       | 15.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 380       | 16.13%  |
| Germany      | 262       | 11.12%  |
| Russia       | 164       | 6.96%   |
| Italy        | 135       | 5.73%   |
| France       | 131       | 5.56%   |
| Brazil       | 131       | 5.56%   |
| UK           | 99        | 4.2%    |
| Spain        | 79        | 3.35%   |
| Poland       | 63        | 2.67%   |
| India        | 63        | 2.67%   |
| Canada       | 56        | 2.38%   |
| Netherlands  | 47        | 1.99%   |
| Mexico       | 38        | 1.61%   |
| Ukraine      | 36        | 1.53%   |
| Australia    | 35        | 1.49%   |
| Hungary      | 32        | 1.36%   |
| Czechia      | 31        | 1.32%   |
| Belgium      | 28        | 1.19%   |
| Turkey       | 25        | 1.06%   |
| Switzerland  | 23        | 0.98%   |
| Indonesia    | 23        | 0.98%   |
| South Africa | 18        | 0.76%   |
| Bulgaria     | 17        | 0.72%   |
| Sweden       | 16        | 0.68%   |
| Slovenia     | 15        | 0.64%   |
| Romania      | 15        | 0.64%   |
| China        | 15        | 0.64%   |
| Argentina    | 15        | 0.64%   |
| Portugal     | 14        | 0.59%   |
| Finland      | 14        | 0.59%   |
| Colombia     | 14        | 0.59%   |
| Austria      | 14        | 0.59%   |
| Slovakia     | 13        | 0.55%   |
| Ireland      | 13        | 0.55%   |
| Greece       | 13        | 0.55%   |
| Denmark      | 13        | 0.55%   |
| Iran         | 12        | 0.51%   |
| Croatia      | 12        | 0.51%   |
| Belarus      | 12        | 0.51%   |
| New Zealand  | 11        | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 50        | 2.03%   |
| Berlin            | 30        | 1.22%   |
| St Petersburg     | 22        | 0.89%   |
| Milan             | 22        | 0.89%   |
| Paris             | 21        | 0.85%   |
| Madrid            | 19        | 0.77%   |
| Warsaw            | 18        | 0.73%   |
| Cologne           | 17        | 0.69%   |
| Hamburg           | 16        | 0.65%   |
| Budapest          | 16        | 0.65%   |
| Rome              | 14        | 0.57%   |
| Sao Paulo         | 13        | 0.53%   |
| Zurich            | 11        | 0.45%   |
| Sofia             | 11        | 0.45%   |
| Prague            | 11        | 0.45%   |
| Munich            | 11        | 0.45%   |
| Minsk             | 11        | 0.45%   |
| Frankfurt am Main | 11        | 0.45%   |
| Amsterdam         | 11        | 0.45%   |
| Vienna            | 10        | 0.41%   |
| Sydney            | 10        | 0.41%   |
| Kyiv              | 10        | 0.41%   |
| Jakarta           | 10        | 0.41%   |
| Dublin            | 9         | 0.36%   |
| Bengaluru         | 9         | 0.36%   |
| Rio de Janeiro    | 8         | 0.32%   |
| Phoenix           | 8         | 0.32%   |
| Istanbul          | 8         | 0.32%   |
| Birmingham        | 8         | 0.32%   |
| Zagreb            | 7         | 0.28%   |
| Melbourne         | 7         | 0.28%   |
| Los Angeles       | 7         | 0.28%   |
| Helsinki          | 7         | 0.28%   |
| Dallas            | 7         | 0.28%   |
| Chennai           | 7         | 0.28%   |
| Belgrade          | 7         | 0.28%   |
| Athens            | 7         | 0.28%   |
| Wroclaw           | 6         | 0.24%   |
| Washington        | 6         | 0.24%   |
| Singapore         | 6         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 583       | 763    | 19.21%  |
| WDC                         | 322       | 391    | 10.61%  |
| Seagate                     | 256       | 318    | 8.43%   |
| Toshiba                     | 200       | 254    | 6.59%   |
| SanDisk                     | 188       | 233    | 6.19%   |
| Kingston                    | 182       | 206    | 6%      |
| SK hynix                    | 146       | 173    | 4.81%   |
| Unknown                     | 145       | 177    | 4.78%   |
| Intel                       | 134       | 169    | 4.42%   |
| Crucial                     | 114       | 139    | 3.76%   |
| Micron Technology           | 89        | 102    | 2.93%   |
| HGST                        | 72        | 84     | 2.37%   |
| Hitachi                     | 50        | 54     | 1.65%   |
| KIOXIA                      | 48        | 54     | 1.58%   |
| A-DATA Technology           | 43        | 46     | 1.42%   |
| China                       | 25        | 34     | 0.82%   |
| Apple                       | 23        | 29     | 0.76%   |
| LITEON                      | 22        | 23     | 0.72%   |
| Silicon Motion              | 20        | 23     | 0.66%   |
| SPCC                        | 18        | 19     | 0.59%   |
| Phison Electronics          | 15        | 15     | 0.49%   |
| Unknown                     | 15        | 16     | 0.49%   |
| PNY                         | 13        | 13     | 0.43%   |
| Phison                      | 13        | 13     | 0.43%   |
| Transcend                   | 12        | 12     | 0.4%    |
| LITEONIT                    | 11        | 13     | 0.36%   |
| JMicron Technology          | 11        | 12     | 0.36%   |
| Intenso                     | 11        | 13     | 0.36%   |
| SSSTC                       | 9         | 9      | 0.3%    |
| Micron/Crucial Technology   | 9         | 13     | 0.3%    |
| UMIS                        | 8         | 9      | 0.26%   |
| Team                        | 8         | 9      | 0.26%   |
| Patriot                     | 8         | 8      | 0.26%   |
| Kingston Technology Company | 8         | 8      | 0.26%   |
| Netac                       | 7         | 7      | 0.23%   |
| GOODRAM                     | 7         | 7      | 0.23%   |
| Fujitsu                     | 7         | 9      | 0.23%   |
| Corsair                     | 7         | 7      | 0.23%   |
| Apacer                      | 7         | 7      | 0.23%   |
| Union Memory                | 6         | 6      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 38        | 1.2%    |
| Toshiba MQ04ABF100 1TB                             | 27        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 27        | 0.85%   |
| Samsung SSD 860 EVO 500GB                          | 27        | 0.85%   |
| Unknown MMC Card  32GB                             | 26        | 0.82%   |
| HGST HTS721010A9E630 1TB                           | 25        | 0.79%   |
| Unknown MMC Card  64GB                             | 24        | 0.76%   |
| Toshiba MQ01ABD100 1TB                             | 24        | 0.76%   |
| Kingston SA400S37240G 240GB SSD                    | 22        | 0.69%   |
| Samsung NVMe SSD Drive 512GB                       | 21        | 0.66%   |
| Kingston SA400S37480G 480GB SSD                    | 19        | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                    | 18        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB                     | 17        | 0.54%   |
| SanDisk NVMe SSD Drive 512GB                       | 16        | 0.5%    |
| Samsung SSD 850 EVO 500GB                          | 16        | 0.5%    |
| Samsung SSD 850 EVO 250GB                          | 16        | 0.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 16        | 0.5%    |
| Unknown                                            | 15        | 0.47%   |
| Unknown MMC Card  128GB                            | 14        | 0.44%   |
| Seagate ST2000LM007-1R8174 2TB                     | 14        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                         | 14        | 0.44%   |
| SanDisk SSD PLUS 240GB                             | 13        | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                       | 13        | 0.41%   |
| Samsung SSD 860 EVO M.2 500GB                      | 13        | 0.41%   |
| Samsung SSD 860 EVO 1TB                            | 13        | 0.41%   |
| Intel SSDPEKNW512G8 512GB                          | 13        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                        | 13        | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 12        | 0.38%   |
| Toshiba MQ01ABF050 500GB                           | 12        | 0.38%   |
| SK hynix NVMe SSD Drive 512GB                      | 12        | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 12        | 0.38%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                     | 12        | 0.38%   |
| Intel SSD 660P Series 1024GB                       | 12        | 0.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 11        | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                         | 11        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                       | 11        | 0.35%   |
| HGST HTS541010A9E680 1TB                           | 11        | 0.35%   |
| Crucial CT500MX500SSD1 500GB                       | 11        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 10        | 0.32%   |
| WDC WD10SPZX-24Z10 1TB                             | 10        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 252       | 313    | 36.31%  |
| WDC                 | 169       | 197    | 24.35%  |
| Toshiba             | 112       | 143    | 16.14%  |
| HGST                | 71        | 83     | 10.23%  |
| Hitachi             | 50        | 54     | 7.2%    |
| Samsung Electronics | 13        | 16     | 1.87%   |
| Unknown             | 7         | 9      | 1.01%   |
| Fujitsu             | 7         | 9      | 1.01%   |
| Apple               | 4         | 4      | 0.58%   |
| External            | 3         | 4      | 0.43%   |
| USB3.0              | 1         | 1      | 0.14%   |
| SABRENT             | 1         | 1      | 0.14%   |
| KESU                | 1         | 1      | 0.14%   |
| JMicron Technology  | 1         | 1      | 0.14%   |
| ipTIME              | 1         | 1      | 0.14%   |
| HGST HTS            | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 253       | 334    | 25.87%  |
| Kingston            | 117       | 132    | 11.96%  |
| SanDisk             | 104       | 126    | 10.63%  |
| Crucial             | 95        | 118    | 9.71%   |
| WDC                 | 49        | 71     | 5.01%   |
| Intel               | 25        | 32     | 2.56%   |
| A-DATA Technology   | 25        | 25     | 2.56%   |
| China               | 24        | 33     | 2.45%   |
| Toshiba             | 23        | 33     | 2.35%   |
| Micron Technology   | 22        | 25     | 2.25%   |
| SK hynix            | 21        | 21     | 2.15%   |
| LITEON              | 17        | 17     | 1.74%   |
| SPCC                | 15        | 16     | 1.53%   |
| Transcend           | 11        | 11     | 1.12%   |
| PNY                 | 11        | 11     | 1.12%   |
| LITEONIT            | 11        | 13     | 1.12%   |
| Apple               | 11        | 11     | 1.12%   |
| Intenso             | 9         | 11     | 0.92%   |
| Patriot             | 8         | 8      | 0.82%   |
| Team                | 7         | 7      | 0.72%   |
| Goodram             | 7         | 7      | 0.72%   |
| Apacer              | 7         | 7      | 0.72%   |
| SABRENT             | 5         | 8      | 0.51%   |
| KingSpec            | 5         | 5      | 0.51%   |
| Dogfish             | 5         | 5      | 0.51%   |
| Corsair             | 5         | 5      | 0.51%   |
| Netac               | 4         | 4      | 0.41%   |
| Emtec               | 4         | 4      | 0.41%   |
| ASMT                | 4         | 5      | 0.41%   |
| Zheino              | 3         | 5      | 0.31%   |
| Verbatim            | 3         | 4      | 0.31%   |
| TO Exter            | 3         | 3      | 0.31%   |
| Lexar               | 3         | 3      | 0.31%   |
| Unknown             | 3         | 3      | 0.31%   |
| Smart               | 2         | 2      | 0.2%    |
| RZX                 | 2         | 3      | 0.2%    |
| Plextor             | 2         | 2      | 0.2%    |
| Mushkin             | 2         | 2      | 0.2%    |
| Kimtigo             | 2         | 2      | 0.2%    |
| FORESEE             | 2         | 2      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1126      | 1441   | 39.17%  |
| SSD     | 890       | 1196   | 30.96%  |
| HDD     | 677       | 838    | 23.55%  |
| MMC     | 146       | 176    | 5.08%   |
| Unknown | 36        | 42     | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1356      | 1955   | 49.83%  |
| NVMe | 1119      | 1433   | 41.12%  |
| MMC  | 146       | 176    | 5.37%   |
| SAS  | 100       | 129    | 3.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 948       | 1249   | 61%     |
| 0.51-1.0   | 505       | 655    | 32.5%   |
| 1.01-2.0   | 88        | 113    | 5.66%   |
| 3.01-4.0   | 7         | 11     | 0.45%   |
| 4.01-10.0  | 4         | 4      | 0.26%   |
| 2.01-3.0   | 2         | 2      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 690       | 28.48%  |
| 251-500        | 688       | 28.39%  |
| 501-1000       | 456       | 18.82%  |
| 1001-2000      | 203       | 8.38%   |
| 51-100         | 137       | 5.65%   |
| 1-20           | 75        | 3.1%    |
| 21-50          | 64        | 2.64%   |
| 2001-3000      | 51        | 2.1%    |
| More than 3000 | 49        | 2.02%   |
| Unknown        | 10        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 640       | 25.51%  |
| 101-250        | 497       | 19.81%  |
| 21-50          | 437       | 17.42%  |
| 51-100         | 356       | 14.19%  |
| 251-500        | 301       | 12%     |
| 501-1000       | 169       | 6.74%   |
| 1001-2000      | 68        | 2.71%   |
| More than 3000 | 18        | 0.72%   |
| 2001-3000      | 13        | 0.52%   |
| Unknown        | 10        | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 5         | 11     | 3.14%   |
| HGST HTS721010A9E630 1TB                 | 5         | 6      | 3.14%   |
| Toshiba MQ04ABF100 1TB                   | 4         | 4      | 2.52%   |
| Toshiba MQ01ABD100 1TB                   | 4         | 6      | 2.52%   |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 1.89%   |
| Seagate ST1000LM048-2E7172 1TB           | 3         | 3      | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 1.89%   |
| SanDisk SSD PLUS 240GB                   | 3         | 3      | 1.89%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 1.89%   |
| Hitachi HTS547564A9E384 640GB            | 3         | 3      | 1.89%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 1.89%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 2         | 2      | 1.26%   |
| Toshiba MQ01ABD075 752GB                 | 2         | 4      | 1.26%   |
| SK hynix SC401 SATA 512GB SSD            | 2         | 2      | 1.26%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.26%   |
| SK hynix BC711 HFM256GD3JX013N 256GB     | 2         | 2      | 1.26%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.26%   |
| Seagate ST2000LM007-1R8174 2TB           | 2         | 2      | 1.26%   |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.26%   |
| Hitachi HTS545050B9A300 500GB            | 2         | 2      | 1.26%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 1.26%   |
| Crucial CT500P1SSD8 500GB                | 2         | 2      | 1.26%   |
| Zheino CHN mSATA02M 256 256GB SSD        | 1         | 2      | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD         | 1         | 1      | 0.63%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.63%   |
| WDC WD6400BEVT-00A0RT0 640GB             | 1         | 1      | 0.63%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.63%   |
| WDC WD5000LPVX-55V0TT0 500GB             | 1         | 1      | 0.63%   |
| WDC WD5000LPVT-24G33T1 500GB             | 1         | 1      | 0.63%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 0.63%   |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.63%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.63%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.63%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB     | 1         | 1      | 0.63%   |
| VISIPRO SSD 256GB                        | 1         | 2      | 0.63%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.63%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.63%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1      | 0.63%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 2      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 20.13%  |
| Toshiba             | 25        | 30     | 15.72%  |
| Hitachi             | 14        | 14     | 8.81%   |
| Samsung Electronics | 12        | 13     | 7.55%   |
| HGST                | 12        | 13     | 7.55%   |
| WDC                 | 11        | 11     | 6.92%   |
| SK hynix            | 10        | 10     | 6.29%   |
| Crucial             | 9         | 10     | 5.66%   |
| SanDisk             | 8         | 8      | 5.03%   |
| Kingston            | 6         | 6      | 3.77%   |
| A-DATA Technology   | 5         | 5      | 3.14%   |
| Micron Technology   | 3         | 3      | 1.89%   |
| Intel               | 2         | 2      | 1.26%   |
| Zheino              | 1         | 2      | 0.63%   |
| VISIPRO             | 1         | 2      | 0.63%   |
| Team                | 1         | 1      | 0.63%   |
| R580                | 1         | 1      | 0.63%   |
| Mushkin             | 1         | 1      | 0.63%   |
| LITEONIT            | 1         | 1      | 0.63%   |
| LITEON              | 1         | 1      | 0.63%   |
| Drevo               | 1         | 1      | 0.63%   |
| BAITITON            | 1         | 3      | 0.63%   |
| ASENNO              | 1         | 1      | 0.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 35.16%  |
| Toshiba             | 21        | 26     | 23.08%  |
| Hitachi             | 14        | 14     | 15.38%  |
| HGST                | 12        | 13     | 13.19%  |
| WDC                 | 9         | 9      | 9.89%   |
| Samsung Electronics | 3         | 3      | 3.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 89        | 105    | 57.05%  |
| SSD  | 50        | 57     | 32.05%  |
| NVMe | 17        | 17     | 10.9%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 33.33%  |
| Intel SSDSC2KB960G8 960GB | 1         | 1      | 33.33%  |
| Acer SSD FA100 256GB      | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Acer    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1256      | 1720   | 49.2%   |
| Detected | 1139      | 1791   | 44.61%  |
| Malfunc  | 155       | 179    | 6.07%   |
| Failed   | 3         | 3      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1568      | 52.88%  |
| Samsung Electronics              | 339       | 11.43%  |
| AMD                              | 288       | 9.71%   |
| SanDisk                          | 192       | 6.48%   |
| SK hynix                         | 125       | 4.22%   |
| Kingston Technology Company      | 73        | 2.46%   |
| Toshiba America Info Systems     | 72        | 2.43%   |
| Micron Technology                | 67        | 2.26%   |
| KIOXIA                           | 45        | 1.52%   |
| Phison Electronics               | 32        | 1.08%   |
| Micron/Crucial Technology        | 28        | 0.94%   |
| Silicon Motion                   | 25        | 0.84%   |
| ADATA Technology                 | 23        | 0.78%   |
| Union Memory (Shenzhen)          | 17        | 0.57%   |
| Solid State Storage Technology   | 16        | 0.54%   |
| Realtek Semiconductor            | 11        | 0.37%   |
| Lite-On Technology               | 8         | 0.27%   |
| Apple                            | 6         | 0.2%    |
| Nvidia                           | 5         | 0.17%   |
| Lenovo                           | 5         | 0.17%   |
| Marvell Technology Group         | 3         | 0.1%    |
| Shenzhen Longsys Electronics     | 2         | 0.07%   |
| Netac Technology                 | 2         | 0.07%   |
| Biwin Storage Technology         | 2         | 0.07%   |
| Zhaoxin                          | 1         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Solidigm                         | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 267       | 8.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 182       | 5.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 171       | 5.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 163       | 5.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 155       | 4.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 107       | 3.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 102       | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 101       | 3.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 2.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 80        | 2.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 79        | 2.51%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 55        | 1.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 55        | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 1.71%   |
| Intel SSD 660P Series                                                          | 53        | 1.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 51        | 1.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 49        | 1.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 48        | 1.52%   |
| Intel Comet Lake SATA AHCI Controller                                          | 44        | 1.4%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 42        | 1.33%   |
| Intel Tiger Lake-LP SATA Controller                                            | 41        | 1.3%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 37        | 1.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 36        | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 35        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 34        | 1.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 33        | 1.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 31        | 0.98%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 28        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 26        | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 24        | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 23        | 0.73%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 23        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 23        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 22        | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 20        | 0.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 19        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 19        | 0.6%    |
| Micron 2210 NVMe SSD [Cobain]                                                  | 18        | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 18        | 0.57%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 16        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1565      | 51.84%  |
| NVMe | 1113      | 36.87%  |
| RAID | 274       | 9.08%   |
| IDE  | 67        | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1871      | 79.65%  |
| AMD          | 477       | 20.31%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 53        | 2.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 46        | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 44        | 1.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 43        | 1.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 42        | 1.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 38        | 1.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 36        | 1.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 34        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 34        | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 1.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 33        | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 1.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 31        | 1.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 31        | 1.32%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 31        | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 1.28%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 28        | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 1.11%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 26        | 1.11%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 0.98%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 22        | 0.94%   |
| Intel 12th Gen Core i7-12700H                 | 20        | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 18        | 0.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 18        | 0.77%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 17        | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 17        | 0.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 17        | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 16        | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 15        | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 15        | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.6%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 14        | 0.6%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 14        | 0.6%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 14        | 0.6%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 13        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 634       | 26.99%  |
| Intel Core i5           | 571       | 24.31%  |
| Other                   | 270       | 11.49%  |
| AMD Ryzen 7             | 143       | 6.09%   |
| AMD Ryzen 5             | 132       | 5.62%   |
| Intel Core i3           | 122       | 5.19%   |
| Intel Celeron           | 107       | 4.56%   |
| Intel Core 2 Duo        | 52        | 2.21%   |
| Intel Pentium           | 34        | 1.45%   |
| AMD Ryzen 3             | 26        | 1.11%   |
| AMD A6                  | 25        | 1.06%   |
| AMD Ryzen 7 PRO         | 24        | 1.02%   |
| AMD Ryzen 9             | 18        | 0.77%   |
| Intel Pentium Dual-Core | 16        | 0.68%   |
| Intel Core i9           | 16        | 0.68%   |
| Intel Atom              | 15        | 0.64%   |
| AMD A10                 | 15        | 0.64%   |
| Intel Pentium Silver    | 12        | 0.51%   |
| AMD A8                  | 12        | 0.51%   |
| AMD Ryzen 5 PRO         | 11        | 0.47%   |
| AMD E                   | 8         | 0.34%   |
| AMD Athlon              | 8         | 0.34%   |
| AMD A4                  | 8         | 0.34%   |
| Intel Genuine           | 7         | 0.3%    |
| AMD E1                  | 7         | 0.3%    |
| AMD FX                  | 6         | 0.26%   |
| AMD E2                  | 6         | 0.26%   |
| Intel Pentium Dual      | 5         | 0.21%   |
| Intel Core m3           | 5         | 0.21%   |
| Intel Celeron Dual-Core | 5         | 0.21%   |
| AMD Athlon II           | 4         | 0.17%   |
| Intel Xeon              | 3         | 0.13%   |
| Intel Core 2            | 3         | 0.13%   |
| AMD A12                 | 3         | 0.13%   |
| AMD PRO A10             | 2         | 0.09%   |
| AMD C-50                | 2         | 0.09%   |
| AMD Athlon II Dual-Core | 2         | 0.09%   |
| Intel Pentium Gold      | 1         | 0.04%   |
| Intel Core M            | 1         | 0.04%   |
| Intel Core 2 Quad       | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 923       | 39.28%  |
| 4      | 877       | 37.32%  |
| 6      | 250       | 10.64%  |
| 8      | 197       | 8.38%   |
| 14     | 32        | 1.36%   |
| 12     | 24        | 1.02%   |
| 10     | 22        | 0.94%   |
| 1      | 15        | 0.64%   |
| 24     | 5         | 0.21%   |
| 16     | 4         | 0.17%   |
| 5      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2349      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1945      | 82.59%  |
| 1      | 410       | 17.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2349      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 735       | 30.46%  |
| 0x306a9    | 114       | 4.72%   |
| 0x206a7    | 96        | 3.98%   |
| 0x806ec    | 94        | 3.9%    |
| 0x906ea    | 92        | 3.81%   |
| 0x806c1    | 89        | 3.69%   |
| 0x806ea    | 84        | 3.48%   |
| 0x40651    | 74        | 3.07%   |
| 0x306c3    | 63        | 2.61%   |
| 0x806e9    | 58        | 2.4%    |
| 0x406e3    | 56        | 2.32%   |
| 0x0a50000c | 45        | 1.86%   |
| 0x306d4    | 44        | 1.82%   |
| 0x08108109 | 44        | 1.82%   |
| 0x08600106 | 38        | 1.57%   |
| 0xa0652    | 37        | 1.53%   |
| 0x1067a    | 37        | 1.53%   |
| 0x906e9    | 36        | 1.49%   |
| 0x08108102 | 36        | 1.49%   |
| 0x906a3    | 35        | 1.45%   |
| 0x706e5    | 33        | 1.37%   |
| 0x806eb    | 26        | 1.08%   |
| 0x506e3    | 26        | 1.08%   |
| 0x08608103 | 24        | 0.99%   |
| 0x20655    | 21        | 0.87%   |
| 0x806d1    | 20        | 0.83%   |
| 0x706a8    | 20        | 0.83%   |
| 0x706a1    | 20        | 0.83%   |
| 0x406c4    | 18        | 0.75%   |
| 0x30678    | 16        | 0.66%   |
| 0x906ed    | 15        | 0.62%   |
| 0x08600104 | 15        | 0.62%   |
| 0x08600103 | 13        | 0.54%   |
| 0x07030105 | 13        | 0.54%   |
| 0x03000027 | 13        | 0.54%   |
| 0x6fd      | 12        | 0.5%    |
| 0x0a404102 | 12        | 0.5%    |
| 0x06006705 | 12        | 0.5%    |
| 0x20652    | 11        | 0.46%   |
| 0x906a4    | 10        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 543       | 23.1%   |
| Haswell          | 190       | 8.08%   |
| IvyBridge        | 171       | 7.27%   |
| TigerLake        | 142       | 6.04%   |
| SandyBridge      | 134       | 5.7%    |
| Skylake          | 118       | 5.02%   |
| Unknown          | 113       | 4.81%   |
| Zen+             | 98        | 4.17%   |
| Zen 2            | 94        | 4%      |
| Zen 3            | 79        | 3.36%   |
| IceLake          | 68        | 2.89%   |
| CometLake        | 67        | 2.85%   |
| Alderlake Hybrid | 67        | 2.85%   |
| Penryn           | 63        | 2.68%   |
| Broadwell        | 62        | 2.64%   |
| Goldmont plus    | 58        | 2.47%   |
| Silvermont       | 49        | 2.08%   |
| Westmere         | 46        | 1.96%   |
| Excavator        | 35        | 1.49%   |
| Core             | 31        | 1.32%   |
| Zen              | 19        | 0.81%   |
| Puma             | 19        | 0.81%   |
| Goldmont         | 16        | 0.68%   |
| K10 Llano        | 14        | 0.6%    |
| Bobcat           | 13        | 0.55%   |
| Piledriver       | 9         | 0.38%   |
| Jaguar           | 8         | 0.34%   |
| K10              | 7         | 0.3%    |
| Steamroller      | 5         | 0.21%   |
| Nehalem          | 5         | 0.21%   |
| Bonnell          | 4         | 0.17%   |
| Tremont          | 2         | 0.09%   |
| K8 & K10 hybrid  | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1762      | 56.29%  |
| Nvidia                           | 758       | 24.22%  |
| AMD                              | 607       | 19.39%  |
| Zhaoxin                          | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 157       | 4.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 133       | 4.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 129       | 4.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 123       | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 101       | 3.16%   |
| Intel UHD Graphics 620                                                                   | 99        | 3.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 93        | 2.91%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 93        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 86        | 2.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 83        | 2.6%    |
| Intel HD Graphics 620                                                                    | 77        | 2.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 73        | 2.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 71        | 2.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 64        | 2%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 60        | 1.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 59        | 1.85%   |
| Intel HD Graphics 5500                                                                   | 56        | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 48        | 1.5%    |
| AMD Lucienne                                                                             | 46        | 1.44%   |
| Intel HD Graphics 630                                                                    | 44        | 1.38%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 43        | 1.35%   |
| Intel HD Graphics 530                                                                    | 38        | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 37        | 1.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 32        | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 28        | 0.88%   |
| AMD Rembrandt [Radeon 680M]                                                              | 26        | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 25        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 24        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 24        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 23        | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 22        | 0.69%   |
| Intel Iris Plus Graphics G7                                                              | 22        | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 18        | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 18        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1056      | 44.88%  |
| Intel + Nvidia | 602       | 25.58%  |
| 1 x AMD        | 386       | 16.4%   |
| Intel + AMD    | 99        | 4.21%   |
| 1 x Nvidia     | 77        | 3.27%   |
| AMD + Nvidia   | 77        | 3.27%   |
| 2 x AMD        | 46        | 1.95%   |
| Other          | 4         | 0.17%   |
| 2 x Nvidia     | 2         | 0.08%   |
| 2 x Intel      | 2         | 0.08%   |
| 1 x Zhaoxin    | 1         | 0.04%   |
| 1 x SiS        | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1838      | 77.32%  |
| Proprietary | 501       | 21.08%  |
| Unknown     | 38        | 1.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1565      | 65.15%  |
| 1.01-2.0   | 252       | 10.49%  |
| 0.01-0.5   | 238       | 9.91%   |
| 3.01-4.0   | 143       | 5.95%   |
| 0.51-1.0   | 117       | 4.87%   |
| 5.01-6.0   | 42        | 1.75%   |
| 7.01-8.0   | 31        | 1.29%   |
| 2.01-3.0   | 12        | 0.5%    |
| 8.01-16.0  | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 498       | 17.57%  |
| BOE                     | 421       | 14.85%  |
| LG Display              | 391       | 13.79%  |
| Chimei Innolux          | 381       | 13.44%  |
| Samsung Electronics     | 272       | 9.59%   |
| Sharp                   | 107       | 3.77%   |
| Dell                    | 98        | 3.46%   |
| Goldstar                | 83        | 2.93%   |
| PANDA                   | 50        | 1.76%   |
| Lenovo                  | 48        | 1.69%   |
| Chi Mei Optoelectronics | 45        | 1.59%   |
| Hewlett-Packard         | 41        | 1.45%   |
| Apple                   | 39        | 1.38%   |
| Acer                    | 36        | 1.27%   |
| Philips                 | 32        | 1.13%   |
| InfoVision              | 25        | 0.88%   |
| AOC                     | 24        | 0.85%   |
| BenQ                    | 23        | 0.81%   |
| Ancor Communications    | 22        | 0.78%   |
| CSO                     | 18        | 0.63%   |
| ASUSTek Computer        | 15        | 0.53%   |
| ViewSonic               | 12        | 0.42%   |
| Iiyama                  | 11        | 0.39%   |
| Panasonic               | 7         | 0.25%   |
| LG Philips              | 7         | 0.25%   |
| Toshiba                 | 6         | 0.21%   |
| Sony                    | 6         | 0.21%   |
| Sceptre Tech            | 6         | 0.21%   |
| MSI                     | 5         | 0.18%   |
| CPT                     | 5         | 0.18%   |
| Seiko/Epson             | 4         | 0.14%   |
| NEC Computers           | 4         | 0.14%   |
| HannStar                | 4         | 0.14%   |
| Vizio                   | 3         | 0.11%   |
| Vestel Elektronik       | 3         | 0.11%   |
| Unknown                 | 3         | 0.11%   |
| SLD                     | 3         | 0.11%   |
| Medion                  | 3         | 0.11%   |
| LGD                     | 3         | 0.11%   |
| KDC                     | 3         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 22        | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 22        | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 21        | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 20        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 18        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 18        | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 15        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 15        | 0.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 15        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 13        | 0.45%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 13        | 0.45%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 12        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 11        | 0.38%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 10        | 0.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 10        | 0.35%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 9         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.31%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 8         | 0.28%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 8         | 0.28%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 8         | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 8         | 0.28%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 8         | 0.28%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 7         | 0.24%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 7         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 7         | 0.24%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 7         | 0.24%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 7         | 0.24%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 7         | 0.24%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 6         | 0.21%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 6         | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 6         | 0.21%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 6         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1277      | 48.89%  |
| 1366x768 (WXGA)    | 603       | 23.09%  |
| 3840x2160 (4K)     | 129       | 4.94%   |
| 1600x900 (HD+)     | 128       | 4.9%    |
| 2560x1440 (QHD)    | 104       | 3.98%   |
| 1920x1200 (WUXGA)  | 59        | 2.26%   |
| 1280x800 (WXGA)    | 40        | 1.53%   |
| 2560x1600          | 34        | 1.3%    |
| 2880x1800          | 27        | 1.03%   |
| 1440x900 (WXGA+)   | 27        | 1.03%   |
| 3840x2400          | 19        | 0.73%   |
| 1680x1050 (WSXGA+) | 18        | 0.69%   |
| 3440x1440          | 16        | 0.61%   |
| 2560x1080          | 16        | 0.61%   |
| 2160x1440          | 16        | 0.61%   |
| 1280x1024 (SXGA)   | 14        | 0.54%   |
| 2240x1400          | 9         | 0.34%   |
| 3200x1800 (QHD+)   | 8         | 0.31%   |
| 1360x768           | 8         | 0.31%   |
| 3840x1080          | 6         | 0.23%   |
| 2256x1504          | 6         | 0.23%   |
| 3456x2160          | 4         | 0.15%   |
| 3072x1920          | 4         | 0.15%   |
| 2520x1680          | 4         | 0.15%   |
| 1920x540           | 4         | 0.15%   |
| 1600x1200          | 4         | 0.15%   |
| Unknown            | 4         | 0.15%   |
| 3200x2000          | 3         | 0.11%   |
| 1920x1280          | 3         | 0.11%   |
| 1024x768 (XGA)     | 3         | 0.11%   |
| 1024x600           | 3         | 0.11%   |
| 1280x720 (HD)      | 2         | 0.08%   |
| 800x1280           | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 3000x1920          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |
| 2160x1350          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1123      | 39.57%  |
| 14      | 352       | 12.4%   |
| 13      | 345       | 12.16%  |
| 17      | 246       | 8.67%   |
| 27      | 127       | 4.47%   |
| 24      | 108       | 3.81%   |
| 23      | 88        | 3.1%    |
| 21      | 68        | 2.4%    |
| 16      | 60        | 2.11%   |
| 11      | 50        | 1.76%   |
| 12      | 46        | 1.62%   |
| 34      | 30        | 1.06%   |
| 31      | 28        | 0.99%   |
| Unknown | 25        | 0.88%   |
| 20      | 17        | 0.6%    |
| 18      | 17        | 0.6%    |
| 19      | 14        | 0.49%   |
| 22      | 10        | 0.35%   |
| 54      | 9         | 0.32%   |
| 84      | 8         | 0.28%   |
| 72      | 7         | 0.25%   |
| 40      | 7         | 0.25%   |
| 32      | 7         | 0.25%   |
| 25      | 6         | 0.21%   |
| 10      | 5         | 0.18%   |
| 26      | 4         | 0.14%   |
| 48      | 3         | 0.11%   |
| 42      | 3         | 0.11%   |
| 86      | 2         | 0.07%   |
| 65      | 2         | 0.07%   |
| 49      | 2         | 0.07%   |
| 46      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 78      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 63      | 1         | 0.04%   |
| 61      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1676      | 59.84%  |
| 501-600     | 299       | 10.67%  |
| 351-400     | 290       | 10.35%  |
| 201-300     | 256       | 9.14%   |
| 401-500     | 118       | 4.21%   |
| 601-700     | 42        | 1.5%    |
| 701-800     | 36        | 1.29%   |
| 1001-1500   | 25        | 0.89%   |
| Unknown     | 25        | 0.89%   |
| 1501-2000   | 17        | 0.61%   |
| 801-900     | 11        | 0.39%   |
| 901-1000    | 3         | 0.11%   |
| 1-100       | 2         | 0.07%   |
| 101-200     | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2051      | 85.03%  |
| 16/10   | 247       | 10.24%  |
| 3/2     | 34        | 1.41%   |
| 21/9    | 32        | 1.33%   |
| Unknown | 16        | 0.66%   |
| 5/4     | 14        | 0.58%   |
| 4/3     | 7         | 0.29%   |
| 32/9    | 4         | 0.17%   |
| 0.56    | 3         | 0.12%   |
| 6/5     | 1         | 0.04%   |
| 3.40    | 1         | 0.04%   |
| 0.67    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1123      | 39.77%  |
| 81-90          | 572       | 20.25%  |
| 201-250        | 216       | 7.65%   |
| 121-130        | 216       | 7.65%   |
| 301-350        | 133       | 4.71%   |
| 71-80          | 127       | 4.5%    |
| 351-500        | 63        | 2.23%   |
| 51-60          | 51        | 1.81%   |
| 111-120        | 51        | 1.81%   |
| 151-200        | 49        | 1.74%   |
| 61-70          | 40        | 1.42%   |
| More than 1000 | 36        | 1.27%   |
| 251-300        | 36        | 1.27%   |
| 131-140        | 25        | 0.89%   |
| Unknown        | 25        | 0.89%   |
| 141-150        | 20        | 0.71%   |
| 501-1000       | 20        | 0.71%   |
| 91-100         | 13        | 0.46%   |
| 41-50          | 5         | 0.18%   |
| 1-40           | 3         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1250      | 45.14%  |
| 101-120       | 692       | 24.99%  |
| 51-100        | 422       | 15.24%  |
| 161-240       | 227       | 8.2%    |
| More than 240 | 116       | 4.19%   |
| 1-50          | 37        | 1.34%   |
| Unknown       | 25        | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1810      | 75.42%  |
| 2     | 474       | 19.75%  |
| 3     | 68        | 2.83%   |
| 0     | 40        | 1.67%   |
| 4     | 8         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1341      | 36.04%  |
| Realtek Semiconductor             | 1322      | 35.53%  |
| Qualcomm Atheros                  | 448       | 12.04%  |
| Broadcom                          | 177       | 4.76%   |
| MediaTek                          | 96        | 2.58%   |
| Broadcom Limited                  | 33        | 0.89%   |
| Ralink                            | 32        | 0.86%   |
| Marvell Technology Group          | 22        | 0.59%   |
| ASIX Electronics                  | 22        | 0.59%   |
| TP-Link                           | 18        | 0.48%   |
| Lenovo                            | 17        | 0.46%   |
| Qualcomm                          | 16        | 0.43%   |
| Sierra Wireless                   | 15        | 0.4%    |
| DisplayLink                       | 15        | 0.4%    |
| Samsung Electronics               | 14        | 0.38%   |
| Ralink Technology                 | 12        | 0.32%   |
| Dell                              | 12        | 0.32%   |
| Hewlett-Packard                   | 11        | 0.3%    |
| Xiaomi                            | 10        | 0.27%   |
| Ericsson Business Mobile Networks | 10        | 0.27%   |
| Huawei Technologies               | 9         | 0.24%   |
| JMicron Technology                | 8         | 0.21%   |
| D-Link                            | 5         | 0.13%   |
| Apple                             | 5         | 0.13%   |
| Nvidia                            | 4         | 0.11%   |
| Google                            | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.08%   |
| T & A Mobile Phones               | 3         | 0.08%   |
| Qualcomm Atheros Communications   | 3         | 0.08%   |
| NetGear                           | 3         | 0.08%   |
| Motorola PCS                      | 3         | 0.08%   |
| Fibocom                           | 3         | 0.08%   |
| ZyDAS                             | 2         | 0.05%   |
| Edimax Technology                 | 2         | 0.05%   |
| ASUSTek Computer                  | 2         | 0.05%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |
| Texas Instruments                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 811       | 18.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 176       | 3.97%   |
| Intel Wi-Fi 6 AX200                                               | 148       | 3.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 116       | 2.61%   |
| Intel Wireless 8265 / 8275                                        | 115       | 2.59%   |
| Intel Wi-Fi 6 AX201                                               | 94        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 93        | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 92        | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 91        | 2.05%   |
| Intel Wireless 7260                                               | 85        | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 84        | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 84        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 73        | 1.65%   |
| Intel Wireless 7265                                               | 70        | 1.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 67        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 65        | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 64        | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 62        | 1.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 58        | 1.31%   |
| Intel Wireless 8260                                               | 56        | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 55        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 52        | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 45        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 41        | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 41        | 0.92%   |
| Intel Wireless 3165                                               | 39        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 36        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 34        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 28        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 25        | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 24        | 0.54%   |
| Intel Wireless-AC 9260                                            | 24        | 0.54%   |
| Intel Wireless 3160                                               | 24        | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 24        | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 24        | 0.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 23        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1283      | 52.71%  |
| Realtek Semiconductor                 | 391       | 16.06%  |
| Qualcomm Atheros                      | 378       | 15.53%  |
| Broadcom                              | 135       | 5.55%   |
| MediaTek                              | 93        | 3.82%   |
| Ralink                                | 32        | 1.31%   |
| Broadcom Limited                      | 26        | 1.07%   |
| Sierra Wireless                       | 15        | 0.62%   |
| TP-Link                               | 13        | 0.53%   |
| Ralink Technology                     | 12        | 0.49%   |
| Qualcomm                              | 12        | 0.49%   |
| Dell                                  | 7         | 0.29%   |
| D-Link                                | 5         | 0.21%   |
| Hewlett-Packard                       | 4         | 0.16%   |
| Ericsson Business Mobile Networks     | 4         | 0.16%   |
| Qualcomm Atheros Communications       | 3         | 0.12%   |
| NetGear                               | 3         | 0.12%   |
| Fibocom                               | 3         | 0.12%   |
| ZyDAS                                 | 2         | 0.08%   |
| Edimax Technology                     | 2         | 0.08%   |
| ASUSTek Computer                      | 2         | 0.08%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| Wacom                                 | 1         | 0.04%   |
| Texas Instruments                     | 1         | 0.04%   |
| Microsoft                             | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| D-Link System                         | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 148       | 6.04%   |
| Intel Wireless 8265 / 8275                                     | 115       | 4.69%   |
| Intel Wi-Fi 6 AX201                                            | 94        | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 93        | 3.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 92        | 3.75%   |
| Intel Wireless 7260                                            | 85        | 3.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 84        | 3.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 84        | 3.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 73        | 2.98%   |
| Intel Wireless 7265                                            | 70        | 2.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 67        | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 65        | 2.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 64        | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 62        | 2.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 57        | 2.32%   |
| Intel Wireless 8260                                            | 56        | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 55        | 2.24%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 52        | 2.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 41        | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 41        | 1.67%   |
| Intel Wireless 3165                                            | 39        | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 36        | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 34        | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 28        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 25        | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 24        | 0.98%   |
| Intel Wireless-AC 9260                                         | 24        | 0.98%   |
| Intel Wireless 3160                                            | 24        | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 24        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 23        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19        | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 19        | 0.77%   |
| Intel Centrino Advanced-N 6235                                 | 19        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 17        | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 16        | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 16        | 0.65%   |
| Realtek 802.11n WLAN Adapter                                   | 16        | 0.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 16        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1144      | 59.55%  |
| Intel                            | 456       | 23.74%  |
| Qualcomm Atheros                 | 104       | 5.41%   |
| Broadcom                         | 57        | 2.97%   |
| Marvell Technology Group         | 22        | 1.15%   |
| ASIX Electronics                 | 22        | 1.15%   |
| Lenovo                           | 17        | 0.88%   |
| DisplayLink                      | 15        | 0.78%   |
| Samsung Electronics              | 14        | 0.73%   |
| Xiaomi                           | 10        | 0.52%   |
| JMicron Technology               | 8         | 0.42%   |
| Broadcom Limited                 | 8         | 0.42%   |
| Huawei Technologies              | 6         | 0.31%   |
| TP-Link                          | 5         | 0.26%   |
| Apple                            | 5         | 0.26%   |
| Qualcomm                         | 4         | 0.21%   |
| Nvidia                           | 4         | 0.21%   |
| Google                           | 4         | 0.21%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.16%   |
| T & A Mobile Phones              | 3         | 0.16%   |
| MediaTek                         | 3         | 0.16%   |
| Motorola PCS                     | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 811       | 41.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 176       | 8.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 116       | 5.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 91        | 4.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 45        | 2.3%    |
| Intel Ethernet Connection I217-LM                                 | 25        | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 1.07%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.82%   |
| Intel Ethernet Connection (10) I219-V                             | 16        | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 7         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.36%   |
| Intel Ethernet Connection (16) I219-LM                            | 7         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2325      | 55.64%  |
| Ethernet | 1827      | 43.72%  |
| Modem    | 23        | 0.55%   |
| Unknown  | 4         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1961      | 78.47%  |
| Ethernet | 537       | 21.49%  |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1672      | 71.18%  |
| 1     | 614       | 26.14%  |
| 0     | 44        | 1.87%   |
| 3     | 18        | 0.77%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1901      | 80.01%  |
| Yes  | 475       | 19.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1077      | 53.61%  |
| Realtek Semiconductor           | 216       | 10.75%  |
| Qualcomm Atheros Communications | 179       | 8.91%   |
| IMC Networks                    | 106       | 5.28%   |
| Broadcom                        | 91        | 4.53%   |
| Lite-On Technology              | 85        | 4.23%   |
| Foxconn / Hon Hai               | 74        | 3.68%   |
| Dell                            | 34        | 1.69%   |
| Apple                           | 29        | 1.44%   |
| Realtek                         | 27        | 1.34%   |
| Ralink                          | 17        | 0.85%   |
| Cambridge Silicon Radio         | 15        | 0.75%   |
| Hewlett-Packard                 | 13        | 0.65%   |
| Toshiba                         | 12        | 0.6%    |
| Foxconn International           | 8         | 0.4%    |
| Ralink Technology               | 5         | 0.25%   |
| ASUSTek Computer                | 5         | 0.25%   |
| Alps Electric                   | 4         | 0.2%    |
| USI                             | 2         | 0.1%    |
| TP-Link                         | 2         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.1%    |
| Smart Modular Technologies      | 2         | 0.1%    |
| SINO WEALTH                     | 1         | 0.05%   |
| MediaTek                        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 376       | 18.7%   |
| Intel AX201 Bluetooth                               | 232       | 11.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 164       | 8.16%   |
| Intel AX200 Bluetooth                               | 144       | 7.16%   |
| Realtek Bluetooth Radio                             | 133       | 6.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 96        | 4.77%   |
| Intel Bluetooth Device                              | 73        | 3.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 61        | 3.03%   |
| IMC Networks Bluetooth Radio                        | 36        | 1.79%   |
| IMC Networks Wireless_Device                        | 34        | 1.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 30        | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 1.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 28        | 1.39%   |
| Realtek Bluetooth Radio                             | 27        | 1.34%   |
| Lite-On Bluetooth Device                            | 27        | 1.34%   |
| Intel AX210 Bluetooth                               | 24        | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 22        | 1.09%   |
| Lite-On Wireless_Device                             | 21        | 1.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 21        | 1.04%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.8%    |
| Apple Bluetooth Host Controller                     | 16        | 0.8%    |
| IMC Networks Bluetooth Device                       | 15        | 0.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 0.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 0.65%   |
| Broadcom HP Portable SoftSailing                    | 13        | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 11        | 0.55%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.5%    |
| Apple Bluetooth USB Host Controller                 | 10        | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.45%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.35%   |
| IMC Networks Bluetooth USB Host Controller          | 7         | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1853      | 61.95%  |
| AMD                                          | 518       | 17.32%  |
| Nvidia                                       | 391       | 13.07%  |
| Realtek Semiconductor                        | 26        | 0.87%   |
| GN Netcom                                    | 24        | 0.8%    |
| C-Media Electronics                          | 22        | 0.74%   |
| Logitech                                     | 15        | 0.5%    |
| Lenovo                                       | 15        | 0.5%    |
| Hewlett-Packard                              | 15        | 0.5%    |
| Plantronics                                  | 9         | 0.3%    |
| JMTek                                        | 8         | 0.27%   |
| Texas Instruments                            | 6         | 0.2%    |
| Razer USA                                    | 6         | 0.2%    |
| Generalplus Technology                       | 6         | 0.2%    |
| Creative Technology                          | 6         | 0.2%    |
| Sony                                         | 4         | 0.13%   |
| Dell                                         | 4         | 0.13%   |
| Sennheiser Communications                    | 3         | 0.1%    |
| Focusrite-Novation                           | 3         | 0.1%    |
| Conexant Systems                             | 3         | 0.1%    |
| CMX Systems                                  | 3         | 0.1%    |
| ZOOM                                         | 2         | 0.07%   |
| SteelSeries ApS                              | 2         | 0.07%   |
| Nordic Semiconductor ASA                     | 2         | 0.07%   |
| Microsoft                                    | 2         | 0.07%   |
| Kingston Technology                          | 2         | 0.07%   |
| GYROCOM C&C                                  | 2         | 0.07%   |
| Google                                       | 2         | 0.07%   |
| Corsair                                      | 2         | 0.07%   |
| Blue Microphones                             | 2         | 0.07%   |
| ASUSTek Computer                             | 2         | 0.07%   |
| Apple                                        | 2         | 0.07%   |
| Alesis                                       | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Zhaoxin                                      | 1         | 0.03%   |
| YZ Technology                                | 1         | 0.03%   |
| Winbond Electronics                          | 1         | 0.03%   |
| Trust                                        | 1         | 0.03%   |
| TerraTec Electronic                          | 1         | 0.03%   |
| Spreadtrum Communications                    | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 350       | 9.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 266       | 7.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 190       | 5.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 185       | 5.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 145       | 3.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 142       | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 115       | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 111       | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 102       | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 91        | 2.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 87        | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 87        | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 86        | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                               | 78        | 2.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 69        | 1.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 63        | 1.72%   |
| Intel Comet Lake PCH cAVS                                                  | 63        | 1.72%   |
| Intel Broadwell-U Audio Controller                                         | 62        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 61        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 60        | 1.64%   |
| AMD FCH Azalia Controller                                                  | 58        | 1.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 57        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 51        | 1.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 46        | 1.26%   |
| Intel CM238 HD Audio Controller                                            | 45        | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                   | 44        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 42        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 40        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 40        | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 34        | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 32        | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 28        | 0.76%   |
| Nvidia Audio device                                                        | 28        | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 27        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 26        | 0.71%   |
| Realtek Semiconductor USB Audio                                            | 25        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 25        | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 25        | 0.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 24        | 0.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 22        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 549       | 29.09%  |
| SK hynix            | 387       | 20.51%  |
| Micron Technology   | 253       | 13.41%  |
| Kingston            | 177       | 9.38%   |
| Crucial             | 118       | 6.25%   |
| Unknown             | 69        | 3.66%   |
| A-DATA Technology   | 46        | 2.44%   |
| Ramaxel Technology  | 44        | 2.33%   |
| Unknown (ABCD)      | 35        | 1.85%   |
| Elpida              | 30        | 1.59%   |
| Nanya Technology    | 25        | 1.32%   |
| Corsair             | 23        | 1.22%   |
| Smart               | 13        | 0.69%   |
| Unknown             | 13        | 0.69%   |
| Transcend           | 12        | 0.64%   |
| G.Skill             | 11        | 0.58%   |
| Apacer              | 6         | 0.32%   |
| Wilk                | 5         | 0.26%   |
| Team                | 5         | 0.26%   |
| Smart Brazil        | 5         | 0.26%   |
| GOODRAM             | 5         | 0.26%   |
| Teikon              | 4         | 0.21%   |
| Silicon Power       | 4         | 0.21%   |
| SHARETRONIC         | 3         | 0.16%   |
| Goldkey             | 3         | 0.16%   |
| ASint Technology    | 3         | 0.16%   |
| 4ea5                | 3         | 0.16%   |
| ff                  | 2         | 0.11%   |
| CSX                 | 2         | 0.11%   |
| AMD                 | 2         | 0.11%   |
| V-GeN               | 1         | 0.05%   |
| V-Color             | 1         | 0.05%   |
| Unknown (8AD6)      | 1         | 0.05%   |
| Unknown (8A02)      | 1         | 0.05%   |
| Unknown (08C8)      | 1         | 0.05%   |
| Unknown (08AE)      | 1         | 0.05%   |
| Timetec             | 1         | 0.05%   |
| Super Talent        | 1         | 0.05%   |
| Shenzhen Zhongteng  | 1         | 0.05%   |
| Shenzhen WODPOSIT   | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 31        | 1.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 1.31%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 24        | 1.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 1.21%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 1.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 20        | 1.01%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.91%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 18        | 0.91%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.91%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.86%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.76%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 13        | 0.66%   |
| Unknown                                                          | 13        | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 12        | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.61%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 12        | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.56%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.5%    |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 10        | 0.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.5%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.4%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 920       | 59.01%  |
| DDR3    | 399       | 25.59%  |
| LPDDR4  | 87        | 5.58%   |
| LPDDR3  | 45        | 2.89%   |
| DDR5    | 37        | 2.37%   |
| LPDDR5  | 26        | 1.67%   |
| DDR2    | 20        | 1.28%   |
| SDRAM   | 15        | 0.96%   |
| Unknown | 8         | 0.51%   |
| DDR     | 2         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1376      | 87.14%  |
| Row Of Chips | 170       | 10.77%  |
| Chip         | 14        | 0.89%   |
| Unknown      | 12        | 0.76%   |
| DIMM         | 7         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 784       | 45.71%  |
| 4096  | 439       | 25.6%   |
| 16384 | 326       | 19.01%  |
| 2048  | 98        | 5.71%   |
| 32768 | 51        | 2.97%   |
| 1024  | 16        | 0.93%   |
| 12288 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 421       | 25.06%  |
| 3200    | 387       | 23.04%  |
| 1600    | 299       | 17.8%   |
| 2400    | 161       | 9.58%   |
| 2133    | 70        | 4.17%   |
| 1334    | 58        | 3.45%   |
| 1333    | 47        | 2.8%    |
| 4800    | 33        | 1.96%   |
| 4267    | 29        | 1.73%   |
| 6400    | 23        | 1.37%   |
| 1867    | 22        | 1.31%   |
| 3266    | 20        | 1.19%   |
| Unknown | 14        | 0.83%   |
| 8400    | 13        | 0.77%   |
| 667     | 12        | 0.71%   |
| 1067    | 11        | 0.65%   |
| 4199    | 10        | 0.6%    |
| 800     | 10        | 0.6%    |
| 4266    | 8         | 0.48%   |
| 5600    | 5         | 0.3%    |
| 2048    | 5         | 0.3%    |
| 2933    | 3         | 0.18%   |
| 1066    | 3         | 0.18%   |
| 975     | 3         | 0.18%   |
| 3000    | 2         | 0.12%   |
| 1866    | 2         | 0.12%   |
| 7500    | 1         | 0.06%   |
| 7467    | 1         | 0.06%   |
| 3733    | 1         | 0.06%   |
| 2666    | 1         | 0.06%   |
| 2000    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |
| 533     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 5         | 25%     |
| Brother Industries  | 5         | 25%     |
| Hewlett-Packard     | 4         | 20%     |
| Samsung Electronics | 3         | 15%     |
| Seiko Epson         | 2         | 10%     |
| Xerox               | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Xerox Phaser 6500N                              | 1         | 5%      |
| Seiko Epson L3110 Series                        | 1         | 5%      |
| Seiko Epson ET-2700 Series                      | 1         | 5%      |
| Samsung Xerox Phaser 3117 Laser Printer         | 1         | 5%      |
| Samsung SCX-3200 Series                         | 1         | 5%      |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 5%      |
| HP LaserJet Professional P 1102w                | 1         | 5%      |
| HP LaserJet 1020                                | 1         | 5%      |
| HP DeskJet F300 series                          | 1         | 5%      |
| HP DeskJet 2300 series                          | 1         | 5%      |
| Canon PIXMA MX490 Series                        | 1         | 5%      |
| Canon PIXMA MP250                               | 1         | 5%      |
| Canon MF4800 Series                             | 1         | 5%      |
| Canon LBP6020                                   | 1         | 5%      |
| Canon iP2600 series                             | 1         | 5%      |
| Brother MFC-J4340DW                             | 1         | 5%      |
| Brother HL-L2390DW                              | 1         | 5%      |
| Brother HL-5450DN series                        | 1         | 5%      |
| Brother HL-2230 series                          | 1         | 5%      |
| Brother DCP-J1050DW                             | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 474       | 21.3%   |
| IMC Networks                           | 262       | 11.78%  |
| Microdia                               | 214       | 9.62%   |
| Realtek Semiconductor                  | 184       | 8.27%   |
| Bison Electronics                      | 166       | 7.46%   |
| Quanta                                 | 144       | 6.47%   |
| Sunplus Innovation Technology          | 127       | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 101       | 4.54%   |
| Syntek                                 | 57        | 2.56%   |
| Acer                                   | 56        | 2.52%   |
| Suyin                                  | 47        | 2.11%   |
| Lite-On Technology                     | 46        | 2.07%   |
| Silicon Motion                         | 40        | 1.8%    |
| Logitech                               | 40        | 1.8%    |
| Luxvisions Innotech Limited            | 37        | 1.66%   |
| Apple                                  | 32        | 1.44%   |
| Alcor Micro                            | 21        | 0.94%   |
| Sonix Technology                       | 17        | 0.76%   |
| Ricoh                                  | 16        | 0.72%   |
| Samsung Electronics                    | 14        | 0.63%   |
| Lenovo                                 | 12        | 0.54%   |
| SunplusIT                              | 9         | 0.4%    |
| Y Media                                | 7         | 0.31%   |
| Importek                               | 6         | 0.27%   |
| icSpring                               | 6         | 0.27%   |
| Sunplus Technology                     | 5         | 0.22%   |
| Primax Electronics                     | 5         | 0.22%   |
| Generalplus Technology                 | 5         | 0.22%   |
| Z-Star Microelectronics                | 4         | 0.18%   |
| USB Camera CS                          | 4         | 0.18%   |
| Microsoft                              | 4         | 0.18%   |
| ShineTech                              | 3         | 0.13%   |
| LG Electronics                         | 3         | 0.13%   |
| Intel                                  | 3         | 0.13%   |
| Genesys Logic                          | 3         | 0.13%   |
| GEMBIRD                                | 3         | 0.13%   |
| DigiTech                               | 3         | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.09%   |
| OYT Tech                               | 2         | 0.09%   |
| Novatek Microelectronics               | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 113       | 5.05%   |
| Microdia Integrated_Webcam_HD                                              | 107       | 4.79%   |
| IMC Networks Integrated Camera                                             | 80        | 3.58%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 79        | 3.53%   |
| Realtek Integrated_Webcam_HD                                               | 76        | 3.4%    |
| Sunplus Integrated_Webcam_HD                                               | 58        | 2.59%   |
| Chicony HD Webcam                                                          | 44        | 1.97%   |
| Bison Integrated Camera                                                    | 43        | 1.92%   |
| Syntek Integrated Camera                                                   | 39        | 1.74%   |
| Quanta HD User Facing                                                      | 31        | 1.39%   |
| Chicony USB2.0 Camera                                                      | 31        | 1.39%   |
| Chicony HP HD Camera                                                       | 29        | 1.3%    |
| Chicony HD User Facing                                                     | 28        | 1.25%   |
| Bison HD Webcam                                                            | 26        | 1.16%   |
| Acer Integrated Camera                                                     | 24        | 1.07%   |
| Microdia Integrated Webcam                                                 | 23        | 1.03%   |
| Quanta HP TrueVision HD Camera                                             | 20        | 0.89%   |
| Quanta HP HD Camera                                                        | 19        | 0.85%   |
| Lite-On Integrated Camera                                                  | 18        | 0.81%   |
| Chicony Integrated Camera (1280x720@30)                                    | 18        | 0.81%   |
| Bison Lenovo EasyCamera                                                    | 18        | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 16        | 0.72%   |
| Chicony HP Truevision HD camera                                            | 16        | 0.72%   |
| Chicony HP Wide Vision HD Camera                                           | 15        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 14        | 0.63%   |
| Realtek Integrated Webcam                                                  | 14        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 14        | 0.63%   |
| Bison BisonCam,NB Pro                                                      | 14        | 0.63%   |
| Sunplus HD WebCam                                                          | 13        | 0.58%   |
| Quanta HD Webcam                                                           | 13        | 0.58%   |
| Microdia Integrated_Webcam_FHD                                             | 13        | 0.58%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 13        | 0.58%   |
| IMC Networks HD Camera                                                     | 13        | 0.58%   |
| Chicony USB 2.0 Camera                                                     | 13        | 0.58%   |
| Chicony HP TrueVision HD                                                   | 13        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 13        | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 13        | 0.58%   |
| Realtek Integrated Webcam HD                                               | 12        | 0.54%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 12        | 0.54%   |
| IMC Networks ov9734_azurewave_camera                                       | 12        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 143       | 29.18%  |
| Validity Sensors                   | 135       | 27.55%  |
| Shenzhen Goodix Technology         | 99        | 20.2%   |
| Elan Microelectronics              | 37        | 7.55%   |
| Upek                               | 22        | 4.49%   |
| AuthenTec                          | 21        | 4.29%   |
| LighTuning Technology              | 20        | 4.08%   |
| STMicroelectronics                 | 5         | 1.02%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.82%   |
| Focal-systems.Corp                 | 2         | 0.41%   |
| Samsung Electronics                | 1         | 0.2%    |
| FocalTech                          | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 63        | 12.86%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 56        | 11.43%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 5.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 4.49%   |
| Elan ELAN:Fingerprint                                                      | 22        | 4.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 3.88%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 3.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 3.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 3.06%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 2.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 2.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 2.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 1.84%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.84%   |
| Validity Sensors VFS491                                                    | 8         | 1.63%   |
| AuthenTec AES2810                                                          | 8         | 1.63%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.43%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.43%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.43%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.22%   |
| Synaptics TouchPad                                                         | 6         | 1.22%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.02%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.02%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.02%   |
| Unknown                                                                    | 5         | 1.02%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.82%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.82%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.82%   |
| Synaptics UWP WBDI                                                         | 3         | 0.61%   |
| Synaptics  WBDI                                                            | 3         | 0.61%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.61%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.61%   |
| Synaptics WBDI Device                                                      | 2         | 0.41%   |
| Synaptics WBDI                                                             | 2         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 103       | 47.03%  |
| Alcor Micro               | 68        | 31.05%  |
| Upek                      | 14        | 6.39%   |
| O2 Micro                  | 9         | 4.11%   |
| Lenovo                    | 8         | 3.65%   |
| Yubico.com                | 2         | 0.91%   |
| Realtek Semiconductor     | 2         | 0.91%   |
| Clay Logic                | 2         | 0.91%   |
| Advanced Card Systems     | 2         | 0.91%   |
| Watchdata                 | 1         | 0.46%   |
| SCM Microsystems          | 1         | 0.46%   |
| In Focus Systems          | 1         | 0.46%   |
| Giesecke & Devrient       | 1         | 0.46%   |
| Fujitsu Siemens Computers | 1         | 0.46%   |
| Chicony Electronics       | 1         | 0.46%   |
| Bit4id                    | 1         | 0.46%   |
| Aladdin R.D.              | 1         | 0.46%   |
| Aladdin Knowledge Systems | 1         | 0.46%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 68        | 31.05%  |
| Broadcom 5880                                                                | 31        | 14.16%  |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 12.33%  |
| Broadcom 58200                                                               | 27        | 12.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 7.31%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 6.39%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 4.11%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.65%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.91%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.91%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.91%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.91%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.91%   |
| Watchdata USB Key                                                            | 1         | 0.46%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.46%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.46%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.46%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.46%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.46%   |
| Bit4id miniLector EVO                                                        | 1         | 0.46%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.46%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.46%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1409      | 58.66%  |
| 1     | 793       | 33.01%  |
| 2     | 174       | 7.24%   |
| 3     | 15        | 0.62%   |
| 4     | 5         | 0.21%   |
| 7     | 3         | 0.12%   |
| 6     | 2         | 0.08%   |
| 9     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 482       | 40.17%  |
| Chipcard                 | 198       | 16.5%   |
| Graphics card            | 179       | 14.92%  |
| Net/wireless             | 104       | 8.67%   |
| Camera                   | 58        | 4.83%   |
| Multimedia controller    | 49        | 4.08%   |
| Bluetooth                | 37        | 3.08%   |
| Sound                    | 21        | 1.75%   |
| Storage                  | 20        | 1.67%   |
| Card reader              | 19        | 1.58%   |
| Communication controller | 15        | 1.25%   |
| Net/ethernet             | 7         | 0.58%   |
| Network                  | 5         | 0.42%   |
| Modem                    | 5         | 0.42%   |
| Firewire controller      | 1         | 0.08%   |

