Linux in Poland - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 3857

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5420               | [0596aff5c4](https://linux-hardware.org/?probe=0596aff5c4) | Feb 28, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [756e003316](https://linux-hardware.org/?probe=756e003316) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [7060b60651](https://linux-hardware.org/?probe=7060b60651) | Feb 27, 2023 |
| HP            | ProBook 430 G6              | [a184aa7141](https://linux-hardware.org/?probe=a184aa7141) | Feb 27, 2023 |
| Lenovo        | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| ASUSTek       | K75VJ                       | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Dell          | Latitude 7390               | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| HP            | Notebook                    | [a1180ad479](https://linux-hardware.org/?probe=a1180ad479) | Feb 27, 2023 |
| HP            | Notebook                    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d57bb59dee](https://linux-hardware.org/?probe=d57bb59dee) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | Latitude 3190               | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | Notebook                    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| Acer          | Aspire ES1-711              | [8e397cc54f](https://linux-hardware.org/?probe=8e397cc54f) | Feb 26, 2023 |
| Gigabyte      | MMLP5AP-00                  | [eb5ca5bb8d](https://linux-hardware.org/?probe=eb5ca5bb8d) | Feb 26, 2023 |
| Valve         | Jupiter                     | [f7289abeb1](https://linux-hardware.org/?probe=f7289abeb1) | Feb 26, 2023 |
| Dell          | Latitude D630               | [cfdc009ff1](https://linux-hardware.org/?probe=cfdc009ff1) | Feb 26, 2023 |
| Acer          | Aspire E5-571G              | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Sony          | VGN-FZ31M                   | [6b830e36f1](https://linux-hardware.org/?probe=6b830e36f1) | Feb 25, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| HP            | EliteBook 840 G2            | [f1fa3164f9](https://linux-hardware.org/?probe=f1fa3164f9) | Feb 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [a85b9d1452](https://linux-hardware.org/?probe=a85b9d1452) | Feb 23, 2023 |
| MSI           | MS-7C02                     | [e2cdf5625c](https://linux-hardware.org/?probe=e2cdf5625c) | Feb 23, 2023 |
| Dell          | XPS 9320                    | [94e7c2d282](https://linux-hardware.org/?probe=94e7c2d282) | Feb 23, 2023 |
| MSI           | MS-7C02                     | [bfbb3aab2c](https://linux-hardware.org/?probe=bfbb3aab2c) | Feb 23, 2023 |
| ASUSTek       | 1215B                       | [970d77d150](https://linux-hardware.org/?probe=970d77d150) | Feb 22, 2023 |
| Notebook      | NS50_70MU                   | [a213ec0ba4](https://linux-hardware.org/?probe=a213ec0ba4) | Feb 22, 2023 |
| Apple         | MacBookPro8,1               | [b7071da133](https://linux-hardware.org/?probe=b7071da133) | Feb 22, 2023 |
| Dell          | Latitude 5491               | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK E744               | [bdcee122d3](https://linux-hardware.org/?probe=bdcee122d3) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Lenovo        | ThinkPad R61 8933W4S        | [fec1a43d91](https://linux-hardware.org/?probe=fec1a43d91) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410s 2924W3S      | [24081de7f1](https://linux-hardware.org/?probe=24081de7f1) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [5fc82de1e4](https://linux-hardware.org/?probe=5fc82de1e4) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Dell          | Latitude 3190               | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [3ddfaa902f](https://linux-hardware.org/?probe=3ddfaa902f) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [14e85e829f](https://linux-hardware.org/?probe=14e85e829f) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [7bc24845b3](https://linux-hardware.org/?probe=7bc24845b3) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [d6f20de9d5](https://linux-hardware.org/?probe=d6f20de9d5) | Feb 19, 2023 |
| Dell          | Vostro 5502                 | [49252b4695](https://linux-hardware.org/?probe=49252b4695) | Feb 19, 2023 |
| HP            | Unknown                     | [69b276cb01](https://linux-hardware.org/?probe=69b276cb01) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [238f636180](https://linux-hardware.org/?probe=238f636180) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| Dell          | Latitude 3520               | [8df8f4c6fc](https://linux-hardware.org/?probe=8df8f4c6fc) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Dell          | Inspiron 5570               | [be29883368](https://linux-hardware.org/?probe=be29883368) | Feb 17, 2023 |
| Dell          | Latitude 5491               | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Dell          | Latitude 5511               | [5c3a80271b](https://linux-hardware.org/?probe=5c3a80271b) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| Apple         | MacBookAir6,1               | [c96e404e3f](https://linux-hardware.org/?probe=c96e404e3f) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| MSI           | Creator Z17 A12UHST         | [a70040c510](https://linux-hardware.org/?probe=a70040c510) | Feb 16, 2023 |
| RTD Embedd... | CMA34CR                     | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Latitude 5480               | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| Lenovo        | Y50-70 20378                | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| GPU Compan... | GWTN141-4                   | [1492f5c475](https://linux-hardware.org/?probe=1492f5c475) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| Acer          | Aspire A315-35              | [971fa91888](https://linux-hardware.org/?probe=971fa91888) | Feb 14, 2023 |
| Google        | Lillipup                    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| Unknown       | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | [ec6afad108](https://linux-hardware.org/?probe=ec6afad108) | Feb 13, 2023 |
| Timi          | TM1613                      | [ce33c5c02e](https://linux-hardware.org/?probe=ce33c5c02e) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5511               | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| TrekStor      | Surfbook W2                 | [f43f606f80](https://linux-hardware.org/?probe=f43f606f80) | Feb 13, 2023 |
| Dell          | Latitude 3190               | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| Dell          | Latitude E6420              | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1LM0... | [8ee6dd00d1](https://linux-hardware.org/?probe=8ee6dd00d1) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Valve         | Jupiter                     | [081d9e5294](https://linux-hardware.org/?probe=081d9e5294) | Feb 11, 2023 |
| HP            | ProBook 430 G3              | [e995a466a1](https://linux-hardware.org/?probe=e995a466a1) | Feb 10, 2023 |
| Toshiba       | Satellite L750              | [b6239c152e](https://linux-hardware.org/?probe=b6239c152e) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad T530 2429MY2       | [9b5ffc7c58](https://linux-hardware.org/?probe=9b5ffc7c58) | Feb 09, 2023 |
| MSI           | Creator Z17 A12UHST         | [8885828bb8](https://linux-hardware.org/?probe=8885828bb8) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| Valve         | Jupiter                     | [26cb195bab](https://linux-hardware.org/?probe=26cb195bab) | Feb 08, 2023 |
| Dell          | Latitude 3570               | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [842956e023](https://linux-hardware.org/?probe=842956e023) | Feb 08, 2023 |
| Dell          | Latitude E6520              | [c9c89084e8](https://linux-hardware.org/?probe=c9c89084e8) | Feb 07, 2023 |
| Dell          | Latitude E4300              | [aaad0477e4](https://linux-hardware.org/?probe=aaad0477e4) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [307d491fc8](https://linux-hardware.org/?probe=307d491fc8) | Feb 07, 2023 |
| Dell          | Latitude 3520               | [d7569fa081](https://linux-hardware.org/?probe=d7569fa081) | Feb 06, 2023 |
| Valve         | Jupiter                     | [edc8beac1f](https://linux-hardware.org/?probe=edc8beac1f) | Feb 06, 2023 |
| Dell          | Latitude 5511               | [57e8ce4f20](https://linux-hardware.org/?probe=57e8ce4f20) | Feb 06, 2023 |
| Dell          | Latitude 3190               | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| HP            | EliteBook 820 G2            | [e8c0f3b7de](https://linux-hardware.org/?probe=e8c0f3b7de) | Feb 05, 2023 |
| HP            | EliteBook 820 G2            | [eb5a23a73b](https://linux-hardware.org/?probe=eb5a23a73b) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [dbef2c679a](https://linux-hardware.org/?probe=dbef2c679a) | Feb 05, 2023 |
| Dell          | Inspiron 5570               | [eb399b4ffa](https://linux-hardware.org/?probe=eb399b4ffa) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [14fb68ece0](https://linux-hardware.org/?probe=14fb68ece0) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| Dell          | Inspiron 5570               | [6e8ab1a5cb](https://linux-hardware.org/?probe=6e8ab1a5cb) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| Dell          | Vostro 3550                 | [4f1125bc93](https://linux-hardware.org/?probe=4f1125bc93) | Feb 04, 2023 |
| Lenovo        | G510 20238                  | [a385ff6f36](https://linux-hardware.org/?probe=a385ff6f36) | Feb 04, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c6dae92093](https://linux-hardware.org/?probe=c6dae92093) | Feb 03, 2023 |
| ASUSTek       | 1101HA                      | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| Dell          | Latitude 5480               | [da9f98059c](https://linux-hardware.org/?probe=da9f98059c) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| HP            | Unknown                     | [4b28efe30c](https://linux-hardware.org/?probe=4b28efe30c) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b1dc3d64b](https://linux-hardware.org/?probe=4b1dc3d64b) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| MSI           | GV62 7RD                    | [c22fffb4e9](https://linux-hardware.org/?probe=c22fffb4e9) | Feb 02, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [ac6a930ffc](https://linux-hardware.org/?probe=ac6a930ffc) | Feb 02, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [62f941075c](https://linux-hardware.org/?probe=62f941075c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| Dell          | Latitude 5410               | [717012530d](https://linux-hardware.org/?probe=717012530d) | Jan 31, 2023 |
| Unknown       | Unknown                     | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [aaaa563786](https://linux-hardware.org/?probe=aaaa563786) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [d1e99e3f04](https://linux-hardware.org/?probe=d1e99e3f04) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| Apple         | MacBookPro5,2               | [4cb11c2a78](https://linux-hardware.org/?probe=4cb11c2a78) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [ee87ac218f](https://linux-hardware.org/?probe=ee87ac218f) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [3cbac640e1](https://linux-hardware.org/?probe=3cbac640e1) | Jan 30, 2023 |
| Dell          | Latitude 3190               | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [81717ed3df](https://linux-hardware.org/?probe=81717ed3df) | Jan 30, 2023 |
| Apple         | MacBookPro11,1              | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | 1215B                       | [8d26a8d157](https://linux-hardware.org/?probe=8d26a8d157) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f6d7ba9d48](https://linux-hardware.org/?probe=f6d7ba9d48) | Jan 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| ASUSTek       | X540SA                      | [93aed28230](https://linux-hardware.org/?probe=93aed28230) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [af3748a4f0](https://linux-hardware.org/?probe=af3748a4f0) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | [e4ddea6092](https://linux-hardware.org/?probe=e4ddea6092) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| HP            | EliteBook Folio 1040 G1     | [4811286faf](https://linux-hardware.org/?probe=4811286faf) | Jan 26, 2023 |
| Dell          | XPS 9320                    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [baae797a05](https://linux-hardware.org/?probe=baae797a05) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [427a7fa0cb](https://linux-hardware.org/?probe=427a7fa0cb) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [7fcc3fb992](https://linux-hardware.org/?probe=7fcc3fb992) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [baf618d1a1](https://linux-hardware.org/?probe=baf618d1a1) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [615879d5e9](https://linux-hardware.org/?probe=615879d5e9) | Jan 24, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5ddcb9f78b](https://linux-hardware.org/?probe=5ddcb9f78b) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Dell          | Latitude 3190               | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [d3686f2fc3](https://linux-hardware.org/?probe=d3686f2fc3) | Jan 21, 2023 |
| Dell          | Latitude 9420               | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Dell          | Latitude 5501               | [72581be7e7](https://linux-hardware.org/?probe=72581be7e7) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| HP            | Pavilion dv5                | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Acer          | Aspire A114-31              | [b341182acd](https://linux-hardware.org/?probe=b341182acd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Dell          | Precision M6600             | [4d697ebfd5](https://linux-hardware.org/?probe=4d697ebfd5) | Jan 19, 2023 |
| Dell          | Inspiron 5567               | [a993e95dde](https://linux-hardware.org/?probe=a993e95dde) | Jan 19, 2023 |
| MSI           | Creator Z17 A12UHST         | [1fd7f0acb7](https://linux-hardware.org/?probe=1fd7f0acb7) | Jan 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [16f5041f1d](https://linux-hardware.org/?probe=16f5041f1d) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| Acer          | Aspire A114-31              | [30698dacda](https://linux-hardware.org/?probe=30698dacda) | Jan 19, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Alienware     | M17xR4                      | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Dell          | Precision 5750              | [592f9624d3](https://linux-hardware.org/?probe=592f9624d3) | Jan 18, 2023 |
| MSI           | GP65 Leopard 10SFK          | [3c09479564](https://linux-hardware.org/?probe=3c09479564) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [2ad3913a19](https://linux-hardware.org/?probe=2ad3913a19) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [6f463ee96b](https://linux-hardware.org/?probe=6f463ee96b) | Jan 18, 2023 |
| Dell          | Latitude D630               | [0d267a0217](https://linux-hardware.org/?probe=0d267a0217) | Jan 17, 2023 |
| HP            | Pavilion Gaming Notebook    | [03a01ae5f7](https://linux-hardware.org/?probe=03a01ae5f7) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| ASUSTek       | K53SJ                       | [267ce15a0c](https://linux-hardware.org/?probe=267ce15a0c) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | [79b74ef79b](https://linux-hardware.org/?probe=79b74ef79b) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| Dell          | Latitude 3190               | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Lenovo        | ThinkPad T510 4384FF3       | [b62dac21bd](https://linux-hardware.org/?probe=b62dac21bd) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| ASUSTek       | X510UQR                     | [2fb1d0a04c](https://linux-hardware.org/?probe=2fb1d0a04c) | Jan 14, 2023 |
| Acer          | AO725                       | [739986d5fa](https://linux-hardware.org/?probe=739986d5fa) | Jan 14, 2023 |
| Lenovo        | G585                        | [c7453a5e19](https://linux-hardware.org/?probe=c7453a5e19) | Jan 14, 2023 |
| MSI           | GE70 2QD                    | [5e408d7d3d](https://linux-hardware.org/?probe=5e408d7d3d) | Jan 14, 2023 |
| Dell          | Vostro 3550                 | [3f68ef3681](https://linux-hardware.org/?probe=3f68ef3681) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Samsung       | SR700                       | [329a7864c0](https://linux-hardware.org/?probe=329a7864c0) | Jan 13, 2023 |
| HP            | Notebook                    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| MSI           | GE70 2QD                    | [8dce1e9fdd](https://linux-hardware.org/?probe=8dce1e9fdd) | Jan 12, 2023 |
| Lenovo        | Legion Y740S-15IMH 81YX     | [b61eb04be5](https://linux-hardware.org/?probe=b61eb04be5) | Jan 11, 2023 |
| Sony          | VPCEJ2S1E                   | [f387a3dcf6](https://linux-hardware.org/?probe=f387a3dcf6) | Jan 11, 2023 |
| MSI           | GL75 9SE                    | [e3478b20bd](https://linux-hardware.org/?probe=e3478b20bd) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [140d48870a](https://linux-hardware.org/?probe=140d48870a) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [f6588e6319](https://linux-hardware.org/?probe=f6588e6319) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b828defe64](https://linux-hardware.org/?probe=b828defe64) | Jan 11, 2023 |
| Dell          | Latitude D630               | [64877fdf78](https://linux-hardware.org/?probe=64877fdf78) | Jan 11, 2023 |
| ASUSTek       | X550CC                      | [2aa757ef35](https://linux-hardware.org/?probe=2aa757ef35) | Jan 10, 2023 |
| Samsung       | 550P5C/550P7C               | [33529c6c45](https://linux-hardware.org/?probe=33529c6c45) | Jan 10, 2023 |
| Acer          | Extensa 2540                | [6bddd00c3f](https://linux-hardware.org/?probe=6bddd00c3f) | Jan 10, 2023 |
| Dell          | Latitude E4310              | [1cd2d3300a](https://linux-hardware.org/?probe=1cd2d3300a) | Jan 09, 2023 |
| Dell          | Latitude E5470              | [41c1a02ca6](https://linux-hardware.org/?probe=41c1a02ca6) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Lenovo        | ThinkPad X201 3626D15       | [3d615a1b12](https://linux-hardware.org/?probe=3d615a1b12) | Jan 09, 2023 |
| Dell          | Latitude 3190               | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| Samsung       | R780/R778                   | [e26d6dd084](https://linux-hardware.org/?probe=e26d6dd084) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| Lenovo        | G51-35 80M8                 | [fe19098e1d](https://linux-hardware.org/?probe=fe19098e1d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS0BX0T    | [e05bd2254f](https://linux-hardware.org/?probe=e05bd2254f) | Jan 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [de3c61df29](https://linux-hardware.org/?probe=de3c61df29) | Jan 08, 2023 |
| HP            | 655                         | [4c7544d7ad](https://linux-hardware.org/?probe=4c7544d7ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| HP            | ENVY m6                     | [b5089c7b29](https://linux-hardware.org/?probe=b5089c7b29) | Jan 07, 2023 |
| HP            | ProBook 5330m               | [37416931cd](https://linux-hardware.org/?probe=37416931cd) | Jan 07, 2023 |
| Lenovo        | S145-15API 81UT             | [fafc9e3fb7](https://linux-hardware.org/?probe=fafc9e3fb7) | Jan 07, 2023 |
| Apple         | MacBookPro9,2               | [e0e6ab58b6](https://linux-hardware.org/?probe=e0e6ab58b6) | Jan 06, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| MSI           | Creator Z17 A12UHST         | [d0299b2518](https://linux-hardware.org/?probe=d0299b2518) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [117e9ffed7](https://linux-hardware.org/?probe=117e9ffed7) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [cacdaaf5c5](https://linux-hardware.org/?probe=cacdaaf5c5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [bbedda14e5](https://linux-hardware.org/?probe=bbedda14e5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [d2c2a681a2](https://linux-hardware.org/?probe=d2c2a681a2) | Jan 05, 2023 |
| Acer          | Aspire A715-74G             | [e0cf0ea368](https://linux-hardware.org/?probe=e0cf0ea368) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [307c51149d](https://linux-hardware.org/?probe=307c51149d) | Jan 03, 2023 |
| Acer          | Nitro AN515-55              | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1a3964dd30](https://linux-hardware.org/?probe=1a3964dd30) | Jan 03, 2023 |
| Dell          | XPS 13 7390                 | [b45f76c172](https://linux-hardware.org/?probe=b45f76c172) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Acer          | Aspire E1-571               | [eb3f1a0f5f](https://linux-hardware.org/?probe=eb3f1a0f5f) | Jan 02, 2023 |
| Dell          | Latitude 3190               | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [c331237e28](https://linux-hardware.org/?probe=c331237e28) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [1ce680cb4d](https://linux-hardware.org/?probe=1ce680cb4d) | Jan 01, 2023 |
| Gigabyte      | RC14UD                      | [24d32a2b05](https://linux-hardware.org/?probe=24d32a2b05) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| HP            | EliteBook 745 G5            | [d819dbd901](https://linux-hardware.org/?probe=d819dbd901) | Dec 30, 2022 |
| HP            | ProBook 450 G7              | [ca7468f975](https://linux-hardware.org/?probe=ca7468f975) | Dec 29, 2022 |
| Dell          | Latitude E6420              | [9733c425b6](https://linux-hardware.org/?probe=9733c425b6) | Dec 29, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [e232c2de6d](https://linux-hardware.org/?probe=e232c2de6d) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Dell          | Latitude 3190               | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Acer          | Nitro AN515-31              | [249f50d430](https://linux-hardware.org/?probe=249f50d430) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 23472Y0       | [4a2d13391c](https://linux-hardware.org/?probe=4a2d13391c) | Dec 25, 2022 |
| GPU Compan... | GWTN141-10                  | [38ed4755c3](https://linux-hardware.org/?probe=38ed4755c3) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [bf600b6f1c](https://linux-hardware.org/?probe=bf600b6f1c) | Dec 22, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming FX505GE          | [094e72dc22](https://linux-hardware.org/?probe=094e72dc22) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [37513092d6](https://linux-hardware.org/?probe=37513092d6) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Latitude 3190               | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| Apple         | MacBookPro14,1              | [8c0c2353ab](https://linux-hardware.org/?probe=8c0c2353ab) | Dec 18, 2022 |
| Valve         | Jupiter                     | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Dell          | Latitude E6330              | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Dell          | Latitude E5570              | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | Latitude E6410              | [173f8a8dc8](https://linux-hardware.org/?probe=173f8a8dc8) | Dec 16, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Gigabyte      | MMLP3AP-00                  | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Google        | Ultima                      | [867abc2b8f](https://linux-hardware.org/?probe=867abc2b8f) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [37284f659a](https://linux-hardware.org/?probe=37284f659a) | Dec 13, 2022 |
| MSI           | Creator Z17 A12UHST         | [61685b4f1a](https://linux-hardware.org/?probe=61685b4f1a) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [334ca886a4](https://linux-hardware.org/?probe=334ca886a4) | Dec 12, 2022 |
| HP            | Pavilion dv7                | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Dell          | Latitude 3190               | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| Samsung       | 270E5G/270E5U               | [93075de512](https://linux-hardware.org/?probe=93075de512) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| Google        | Glimmer                     | [ad4b3f5575](https://linux-hardware.org/?probe=ad4b3f5575) | Dec 08, 2022 |
| Apple         | MacBookPro12,1              | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Dell          | Latitude 5480               | [0cd7d6e4c0](https://linux-hardware.org/?probe=0cd7d6e4c0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [9a859c9a5d](https://linux-hardware.org/?probe=9a859c9a5d) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [63b84a9439](https://linux-hardware.org/?probe=63b84a9439) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [119ec75a5f](https://linux-hardware.org/?probe=119ec75a5f) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Dell          | Latitude 3190               | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| MSI           | Creator Z17 A12UHST         | [afbbf473b9](https://linux-hardware.org/?probe=afbbf473b9) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [90c7688386](https://linux-hardware.org/?probe=90c7688386) | Dec 04, 2022 |
| Google        | Lars                        | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Dell          | XPS 15 9570                 | [ec5047129a](https://linux-hardware.org/?probe=ec5047129a) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Google        | Lars                        | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| Dell          | G15 5515                    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Dell          | Latitude 5480               | [4eba5810d7](https://linux-hardware.org/?probe=4eba5810d7) | Dec 03, 2022 |
| Dell          | Vostro 5502                 | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3d55f501c](https://linux-hardware.org/?probe=c3d55f501c) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [802af80043](https://linux-hardware.org/?probe=802af80043) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| HP            | ProBook 640 G2              | [56ceffe338](https://linux-hardware.org/?probe=56ceffe338) | Nov 28, 2022 |
| Dell          | Latitude 3190               | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| HUAWEI        | MRC-WX0                     | [98f550465b](https://linux-hardware.org/?probe=98f550465b) | Nov 28, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| ASUSTek       | G75VX                       | [87ef485975](https://linux-hardware.org/?probe=87ef485975) | Nov 27, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| HP            | ProBook 6470b               | [c8da54315e](https://linux-hardware.org/?probe=c8da54315e) | Nov 26, 2022 |
| Dell          | Latitude E6220              | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| Valve         | Jupiter                     | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| HP            | 250 G6 Notebook PC          | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| ASUSTek       | K51AC                       | [0b2413e13c](https://linux-hardware.org/?probe=0b2413e13c) | Nov 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [e7717a62cb](https://linux-hardware.org/?probe=e7717a62cb) | Nov 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [ac72570183](https://linux-hardware.org/?probe=ac72570183) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Pavilion dv6                | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [6d217fbd52](https://linux-hardware.org/?probe=6d217fbd52) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ad63d86cb9](https://linux-hardware.org/?probe=ad63d86cb9) | Nov 23, 2022 |
| HP            | G5000 (GF783EA#AKD)         | [2437328d23](https://linux-hardware.org/?probe=2437328d23) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [c345afe01a](https://linux-hardware.org/?probe=c345afe01a) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [e36ab20d8c](https://linux-hardware.org/?probe=e36ab20d8c) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [014cf9f78d](https://linux-hardware.org/?probe=014cf9f78d) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| HP            | EliteBook Folio 1040 G1     | [26ac531682](https://linux-hardware.org/?probe=26ac531682) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Dell          | Latitude 5490               | [295073cd07](https://linux-hardware.org/?probe=295073cd07) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0a98e4cae4](https://linux-hardware.org/?probe=0a98e4cae4) | Nov 21, 2022 |
| Dell          | Latitude 3190               | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [740b4f9f03](https://linux-hardware.org/?probe=740b4f9f03) | Nov 20, 2022 |
| HP            | Compaq Presario CQ60        | [3f18cccea5](https://linux-hardware.org/?probe=3f18cccea5) | Nov 20, 2022 |
| HUAWEI        | HVY-WXX9                    | [2030d33f00](https://linux-hardware.org/?probe=2030d33f00) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d8f53f887a](https://linux-hardware.org/?probe=d8f53f887a) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c967893dd4](https://linux-hardware.org/?probe=c967893dd4) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| Acer          | Aspire V3-772G              | [bc46ec232a](https://linux-hardware.org/?probe=bc46ec232a) | Nov 18, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| Dell          | Inspiron 13-5368            | [203df386a1](https://linux-hardware.org/?probe=203df386a1) | Nov 17, 2022 |
| Dell          | Inspiron 3451               | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | [fe520ea826](https://linux-hardware.org/?probe=fe520ea826) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| Valve         | Jupiter                     | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| Toshiba       | Satellite P300              | [02285947b8](https://linux-hardware.org/?probe=02285947b8) | Nov 13, 2022 |
| Dell          | Inspiron 3583               | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Acer          | Aspire E1-531G              | [9f3c8742f7](https://linux-hardware.org/?probe=9f3c8742f7) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Dell          | Latitude E6540              | [e28c12e783](https://linux-hardware.org/?probe=e28c12e783) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| Apple         | MacBookPro14,1              | [2981b232db](https://linux-hardware.org/?probe=2981b232db) | Nov 11, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [3ebec87cd1](https://linux-hardware.org/?probe=3ebec87cd1) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| Dell          | Latitude 7480               | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| Dell          | Latitude 7480               | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| MSI           | Stealth GS77 12UGS          | [bf125e16a2](https://linux-hardware.org/?probe=bf125e16a2) | Nov 10, 2022 |
| Dell          | Latitude E6330              | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| MSI           | Creator Z17 A12UHST         | [a3b1e0d746](https://linux-hardware.org/?probe=a3b1e0d746) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| MSI           | Stealth GS77 12UGS          | [ae6b308816](https://linux-hardware.org/?probe=ae6b308816) | Nov 08, 2022 |
| Dell          | G5 5587                     | [972a2dcaa0](https://linux-hardware.org/?probe=972a2dcaa0) | Nov 08, 2022 |
| Lenovo        | ThinkPad P53 20QQS2CY00     | [98e9599ea3](https://linux-hardware.org/?probe=98e9599ea3) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| MSI           | Creator Z17 A12UHST         | [891dbf2492](https://linux-hardware.org/?probe=891dbf2492) | Nov 07, 2022 |
| Acer          | Aspire E5-573G              | [fafbf5ba02](https://linux-hardware.org/?probe=fafbf5ba02) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| HP            | ProBook 6570b               | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Acer          | Aspire A715-74G             | [fa89b7a988](https://linux-hardware.org/?probe=fa89b7a988) | Nov 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [24e798d2a5](https://linux-hardware.org/?probe=24e798d2a5) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| HP            | EliteBook 745 G2            | [c6505744ca](https://linux-hardware.org/?probe=c6505744ca) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Dell          | Latitude E6430              | [2b6012cc1d](https://linux-hardware.org/?probe=2b6012cc1d) | Nov 02, 2022 |
| Dell          | G15 5515                    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| Dell          | G15 5515                    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| HP            | EliteBook 745 G2            | [0786ded6c8](https://linux-hardware.org/?probe=0786ded6c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Latitude 3190               | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| HP            | ProBook 6540b               | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0DD0... | [973a3662b9](https://linux-hardware.org/?probe=973a3662b9) | Oct 29, 2022 |
| Kruger&Mat... | KM1406                      | [70b8441ccf](https://linux-hardware.org/?probe=70b8441ccf) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [a7ff9a34d2](https://linux-hardware.org/?probe=a7ff9a34d2) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [73ddced77b](https://linux-hardware.org/?probe=73ddced77b) | Oct 28, 2022 |
| HP            | EliteBook 840 G6            | [89cc00ef58](https://linux-hardware.org/?probe=89cc00ef58) | Oct 28, 2022 |
| Fujitsu       | LIFEBOOK U728               | [c5867e7dd3](https://linux-hardware.org/?probe=c5867e7dd3) | Oct 28, 2022 |
| Dell          | XPS 15 9510                 | [d3879c6bb0](https://linux-hardware.org/?probe=d3879c6bb0) | Oct 28, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | [f936993d28](https://linux-hardware.org/?probe=f936993d28) | Oct 28, 2022 |
| Gateway       | P-7805u                     | [7597071801](https://linux-hardware.org/?probe=7597071801) | Oct 28, 2022 |
| Dell          | Latitude E6530              | [71b2df6eff](https://linux-hardware.org/?probe=71b2df6eff) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | [4261d8dd66](https://linux-hardware.org/?probe=4261d8dd66) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | [216730dba7](https://linux-hardware.org/?probe=216730dba7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Dell          | Latitude E6530              | [c271a351aa](https://linux-hardware.org/?probe=c271a351aa) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| HUAWEI        | HKD-WXX                     | [2ff7652d3a](https://linux-hardware.org/?probe=2ff7652d3a) | Oct 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [082e572642](https://linux-hardware.org/?probe=082e572642) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | [6ba1aaf015](https://linux-hardware.org/?probe=6ba1aaf015) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | [062d1d3b82](https://linux-hardware.org/?probe=062d1d3b82) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| MSI           | Creator Z17 A12UHST         | [18df556ca1](https://linux-hardware.org/?probe=18df556ca1) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Dell          | Latitude 3190               | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ZBook 17 G6                 | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [f282e79ccb](https://linux-hardware.org/?probe=f282e79ccb) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [ec27a5efb5](https://linux-hardware.org/?probe=ec27a5efb5) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [1f26696990](https://linux-hardware.org/?probe=1f26696990) | Oct 22, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [88a93e44f9](https://linux-hardware.org/?probe=88a93e44f9) | Oct 22, 2022 |
| ASUSTek       | X550LN                      | [7a6daf6023](https://linux-hardware.org/?probe=7a6daf6023) | Oct 22, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [f5af95bb9a](https://linux-hardware.org/?probe=f5af95bb9a) | Oct 21, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5def3f5324](https://linux-hardware.org/?probe=5def3f5324) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [344040aee1](https://linux-hardware.org/?probe=344040aee1) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| MSI           | Creator Z17 A12UHST         | [5d65b94f2b](https://linux-hardware.org/?probe=5d65b94f2b) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Dell          | Latitude 5421               | [77cbc2b788](https://linux-hardware.org/?probe=77cbc2b788) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b8dbd1daf9](https://linux-hardware.org/?probe=b8dbd1daf9) | Oct 17, 2022 |
| Dell          | Inspiron 3541               | [858e5b974b](https://linux-hardware.org/?probe=858e5b974b) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| Dell          | Latitude E6430              | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| Acer          | Aspire SW5-012              | [530046bf8a](https://linux-hardware.org/?probe=530046bf8a) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | ENVY 15                     | [09bfbadebe](https://linux-hardware.org/?probe=09bfbadebe) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Lenovo        | G500s 20245                 | [61539bde5e](https://linux-hardware.org/?probe=61539bde5e) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Acer          | Aspire A315-21              | [a122b26729](https://linux-hardware.org/?probe=a122b26729) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Lenovo        | ThinkPad T530 24297TG       | [d6dec1ab6d](https://linux-hardware.org/?probe=d6dec1ab6d) | Oct 12, 2022 |
| ASUSTek       | X705UDR                     | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| ASUSTek       | G750JW                      | [251f32c620](https://linux-hardware.org/?probe=251f32c620) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | [2aea48a0f2](https://linux-hardware.org/?probe=2aea48a0f2) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | [10d90de300](https://linux-hardware.org/?probe=10d90de300) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [4c575be5d7](https://linux-hardware.org/?probe=4c575be5d7) | Oct 10, 2022 |
| Acer          | Enduro EUN314-51W           | [14741407aa](https://linux-hardware.org/?probe=14741407aa) | Oct 10, 2022 |
| Dell          | Latitude 3190               | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| Dell          | Precision 7530              | [7f71730e68](https://linux-hardware.org/?probe=7f71730e68) | Oct 07, 2022 |
| Dell          | Inspiron 3451               | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | [4c7a6898bf](https://linux-hardware.org/?probe=4c7a6898bf) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| Dell          | Precision 3541              | [bfef2cb8a3](https://linux-hardware.org/?probe=bfef2cb8a3) | Oct 05, 2022 |
| ASUSTek       | X550CC                      | [147483a370](https://linux-hardware.org/?probe=147483a370) | Oct 05, 2022 |
| Valve         | Jupiter                     | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| Lenovo        | Z51-70 80K6                 | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6c821c0c08](https://linux-hardware.org/?probe=6c821c0c08) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dynabook      | PORTEGE X40-G               | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell          | Latitude 3190               | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Acer          | Aspire 5755G                | [c552cb5631](https://linux-hardware.org/?probe=c552cb5631) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| Acer          | Aspire 4733Z                | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [34006e3b46](https://linux-hardware.org/?probe=34006e3b46) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Acer          | Aspire A715-74G             | [17abc08754](https://linux-hardware.org/?probe=17abc08754) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| Lenovo        | G500s 20245                 | [b9001f7817](https://linux-hardware.org/?probe=b9001f7817) | Sep 29, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [be74c01cca](https://linux-hardware.org/?probe=be74c01cca) | Sep 29, 2022 |
| Dell          | Latitude E6330              | [b075fbcb56](https://linux-hardware.org/?probe=b075fbcb56) | Sep 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [82528435d8](https://linux-hardware.org/?probe=82528435d8) | Sep 29, 2022 |
| MSI           | Creator Z17 A12UHST         | [4b9249b9b0](https://linux-hardware.org/?probe=4b9249b9b0) | Sep 29, 2022 |
| Dell          | Inspiron 5558               | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Valve         | Jupiter                     | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| Dell          | Precision 3561              | [77a4030052](https://linux-hardware.org/?probe=77a4030052) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [70860ec433](https://linux-hardware.org/?probe=70860ec433) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [cb5f6f279b](https://linux-hardware.org/?probe=cb5f6f279b) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [3f11c520e0](https://linux-hardware.org/?probe=3f11c520e0) | Sep 26, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Valve         | Jupiter                     | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Acer          | P5WE0                       | [124f7bdd77](https://linux-hardware.org/?probe=124f7bdd77) | Sep 25, 2022 |
| HP            | Laptop 17-cp0xxx            | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Toshiba       | Satellite P205              | [2a1450578e](https://linux-hardware.org/?probe=2a1450578e) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | [98e97d946a](https://linux-hardware.org/?probe=98e97d946a) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | G505s 20255                 | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| HP            | EliteBook 840 G2            | [030ce84327](https://linux-hardware.org/?probe=030ce84327) | Sep 20, 2022 |
| Framework     | Laptop                      | [dd163cfa96](https://linux-hardware.org/?probe=dd163cfa96) | Sep 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21c74278f8](https://linux-hardware.org/?probe=21c74278f8) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [c77a454d4e](https://linux-hardware.org/?probe=c77a454d4e) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [4e8bf046d8](https://linux-hardware.org/?probe=4e8bf046d8) | Sep 19, 2022 |
| Apple         | MacBook9,1                  | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [85952e171d](https://linux-hardware.org/?probe=85952e171d) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [eb67db5bff](https://linux-hardware.org/?probe=eb67db5bff) | Sep 19, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [793fa18b58](https://linux-hardware.org/?probe=793fa18b58) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| Valve         | Jupiter                     | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| HP            | Notebook                    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Lenovo        | G50-80 80E5                 | [5023f912e2](https://linux-hardware.org/?probe=5023f912e2) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 5511               | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| HP            | ProBook 470 G5              | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Dell          | Inspiron 5584               | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Dell          | Inspiron 3451               | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [efc31007ac](https://linux-hardware.org/?probe=efc31007ac) | Sep 12, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HUAWEI        | KPL-W0X                     | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | [16fa00177a](https://linux-hardware.org/?probe=16fa00177a) | Sep 10, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| Gigabyte      | AORUS 15G XC                | [ea131dfe2c](https://linux-hardware.org/?probe=ea131dfe2c) | Sep 08, 2022 |
| Dell          | Latitude E6540              | [5700f37281](https://linux-hardware.org/?probe=5700f37281) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6812b52b92](https://linux-hardware.org/?probe=6812b52b92) | Sep 08, 2022 |
| Dell          | Inspiron 3541               | [2cc868e8f0](https://linux-hardware.org/?probe=2cc868e8f0) | Sep 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [6ee5358914](https://linux-hardware.org/?probe=6ee5358914) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [63524aa492](https://linux-hardware.org/?probe=63524aa492) | Sep 07, 2022 |
| HP            | EliteBook 8440p             | [5cf26fac4d](https://linux-hardware.org/?probe=5cf26fac4d) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4615004e85](https://linux-hardware.org/?probe=4615004e85) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d802875fec](https://linux-hardware.org/?probe=d802875fec) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | Latitude E6330              | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| HP            | 620                         | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6669ffa68e](https://linux-hardware.org/?probe=6669ffa68e) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [e249853663](https://linux-hardware.org/?probe=e249853663) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Valve         | Jupiter                     | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [12abd434b5](https://linux-hardware.org/?probe=12abd434b5) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Valve         | Jupiter                     | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Dell          | Latitude E6330              | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| ASUSTek       | F3E                         | [1314dc63b6](https://linux-hardware.org/?probe=1314dc63b6) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Dell          | Latitude E6400              | [666ba32534](https://linux-hardware.org/?probe=666ba32534) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| HP            | 15                          | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| ASUSTek       | X705UAP                     | [eacfc15b6c](https://linux-hardware.org/?probe=eacfc15b6c) | Aug 24, 2022 |
| Dell          | Inspiron 5402               | [936ea503c8](https://linux-hardware.org/?probe=936ea503c8) | Aug 24, 2022 |
| Acer          | Aspire E5-571               | [659e36b0ed](https://linux-hardware.org/?probe=659e36b0ed) | Aug 23, 2022 |
| Dell          | Latitude 5521               | [b14afc8c75](https://linux-hardware.org/?probe=b14afc8c75) | Aug 22, 2022 |
| Dell          | XPS 15 9560                 | [29d52f610c](https://linux-hardware.org/?probe=29d52f610c) | Aug 22, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Lenovo        | ThinkPad T400 6474B84       | [f8a6513790](https://linux-hardware.org/?probe=f8a6513790) | Aug 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Valve         | Jupiter                     | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [f21f1687d5](https://linux-hardware.org/?probe=f21f1687d5) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [04b38f1dfd](https://linux-hardware.org/?probe=04b38f1dfd) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| NEC Comput... | PC-LJ730MG6W                | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| MSI           | GT72S 6QE                   | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| HP            | EliteBook 2760p             | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| ASUSTek       | UX303LAB                    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| HP            | EliteBook 2760p             | [0ce6a49a7f](https://linux-hardware.org/?probe=0ce6a49a7f) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| Alienware     | M17xR4                      | [a9d3769b5b](https://linux-hardware.org/?probe=a9d3769b5b) | Aug 10, 2022 |
| Dell          | Latitude 5521               | [25f117c439](https://linux-hardware.org/?probe=25f117c439) | Aug 10, 2022 |
| HP            | Pavilion HDX9200            | [079cb2197b](https://linux-hardware.org/?probe=079cb2197b) | Aug 10, 2022 |
| HP            | 255 G4                      | [44b5858d14](https://linux-hardware.org/?probe=44b5858d14) | Aug 10, 2022 |
| HP            | Compaq Presario CQ60        | [20f30b16e5](https://linux-hardware.org/?probe=20f30b16e5) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| Dell          | Vostro 3500                 | [71390cb3ec](https://linux-hardware.org/?probe=71390cb3ec) | Aug 07, 2022 |
| PC Special... | Recoil II                   | [1e05c3546f](https://linux-hardware.org/?probe=1e05c3546f) | Aug 07, 2022 |
| ASUSTek       | K52JT                       | [013f296b81](https://linux-hardware.org/?probe=013f296b81) | Aug 07, 2022 |
| MSI           | Creator Z17 A12UHST         | [ccbb6bb183](https://linux-hardware.org/?probe=ccbb6bb183) | Aug 05, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [0a34d32db6](https://linux-hardware.org/?probe=0a34d32db6) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [e835f1eca5](https://linux-hardware.org/?probe=e835f1eca5) | Aug 04, 2022 |
| Acer          | Aspire E5-571               | [a249c68580](https://linux-hardware.org/?probe=a249c68580) | Aug 04, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | [7f2e8ddf72](https://linux-hardware.org/?probe=7f2e8ddf72) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | [1d0650ff70](https://linux-hardware.org/?probe=1d0650ff70) | Aug 03, 2022 |
| MSI           | Creator Z17 A12UHST         | [87533b4847](https://linux-hardware.org/?probe=87533b4847) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Acer          | Aspire 5730                 | [1541bd94e2](https://linux-hardware.org/?probe=1541bd94e2) | Jul 31, 2022 |
| Acer          | Aspire V5-591G              | [80396b28bf](https://linux-hardware.org/?probe=80396b28bf) | Jul 31, 2022 |
| HP            | 550                         | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Acer          | Aspire 5730                 | [8ac8b8a87a](https://linux-hardware.org/?probe=8ac8b8a87a) | Jul 30, 2022 |
| Dell          | Precision 5550              | [e11d4be493](https://linux-hardware.org/?probe=e11d4be493) | Jul 30, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| Dell          | Latitude E7470              | [9f4d55071c](https://linux-hardware.org/?probe=9f4d55071c) | Jul 28, 2022 |
| Dell          | Latitude 5421               | [ec91a9ea85](https://linux-hardware.org/?probe=ec91a9ea85) | Jul 27, 2022 |
| Lenovo        | G50-70 20351                | [4ddfbb6ad8](https://linux-hardware.org/?probe=4ddfbb6ad8) | Jul 26, 2022 |
| Toshiba       | Satellite L750D             | [c8e9ea3fdd](https://linux-hardware.org/?probe=c8e9ea3fdd) | Jul 26, 2022 |
| HP            | Laptop 15s-eq0xxx           | [aabcc30a17](https://linux-hardware.org/?probe=aabcc30a17) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | [597fb27e56](https://linux-hardware.org/?probe=597fb27e56) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | [8b1930ddbd](https://linux-hardware.org/?probe=8b1930ddbd) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Packard Be... | EasyNote TE11BZ             | [e1099c5342](https://linux-hardware.org/?probe=e1099c5342) | Jul 22, 2022 |
| Dell          | Inspiron MM061              | [8e0cd55a28](https://linux-hardware.org/?probe=8e0cd55a28) | Jul 22, 2022 |
| ASUSTek       | X550CL                      | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Latitude E6540              | [4688c6f312](https://linux-hardware.org/?probe=4688c6f312) | Jul 21, 2022 |
| HP            | EliteBook 840 G5            | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| HP            | 250 G6 Notebook PC          | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| MSI           | Creator Z17 A12UHST         | [ef0c958c66](https://linux-hardware.org/?probe=ef0c958c66) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Dell          | Inspiron 3451               | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Dell          | Latitude E6420              | [d3bbc4a899](https://linux-hardware.org/?probe=d3bbc4a899) | Jul 12, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [24dc866c51](https://linux-hardware.org/?probe=24dc866c51) | Jul 11, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| HP            | ProBook 4740s               | [18ff2d02bd](https://linux-hardware.org/?probe=18ff2d02bd) | Jul 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [6ed9abc24e](https://linux-hardware.org/?probe=6ed9abc24e) | Jul 10, 2022 |
| Lenovo        | ThinkPad R61 8932FJG        | [d783a022b3](https://linux-hardware.org/?probe=d783a022b3) | Jul 08, 2022 |
| Dell          | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| Acer          | Aspire A715-75G             | [4a6cc98dd6](https://linux-hardware.org/?probe=4a6cc98dd6) | Jul 08, 2022 |
| MSI           | GF63 Thin 8RCS              | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [5cf26aa015](https://linux-hardware.org/?probe=5cf26aa015) | Jul 08, 2022 |
| Lenovo        | ThinkPad T410 2537W2L       | [a2e55ad8ac](https://linux-hardware.org/?probe=a2e55ad8ac) | Jul 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [64dc631691](https://linux-hardware.org/?probe=64dc631691) | Jul 05, 2022 |
| HP            | ProBook 6475b               | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Dell          | Latitude 7280               | [5333012df2](https://linux-hardware.org/?probe=5333012df2) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Inspiron 5567               | [740ba48457](https://linux-hardware.org/?probe=740ba48457) | Jul 03, 2022 |
| Dell          | Latitude E6420              | [e1b517f8af](https://linux-hardware.org/?probe=e1b517f8af) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | X55U                        | [ed55b4ef39](https://linux-hardware.org/?probe=ed55b4ef39) | Jul 03, 2022 |
| Lenovo        | ThinkPad E470 20H1007MPB    | [7a20748cc1](https://linux-hardware.org/?probe=7a20748cc1) | Jul 03, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [8b717c6bdf](https://linux-hardware.org/?probe=8b717c6bdf) | Jul 02, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| Lenovo        | ThinkPad T450s 20BX002NM... | [3bb2e1821b](https://linux-hardware.org/?probe=3bb2e1821b) | Jul 01, 2022 |
| Dell          | Latitude 3420               | [651ab17da0](https://linux-hardware.org/?probe=651ab17da0) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [0e09c926c1](https://linux-hardware.org/?probe=0e09c926c1) | Jun 30, 2022 |
| Dell          | Inspiron M5040              | [64c8f1ad3f](https://linux-hardware.org/?probe=64c8f1ad3f) | Jun 29, 2022 |
| Lenovo        | G580 20150                  | [dbe5fe496a](https://linux-hardware.org/?probe=dbe5fe496a) | Jun 29, 2022 |
| Getac         | B300-X                      | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [a57e4e84f8](https://linux-hardware.org/?probe=a57e4e84f8) | Jun 29, 2022 |
| Dell          | Inspiron M5040              | [a9522b8288](https://linux-hardware.org/?probe=a9522b8288) | Jun 28, 2022 |
| Dell          | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| Dell          | Latitude 5511               | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| ASUSTek       | X751LK                      | [d7f4b1678b](https://linux-hardware.org/?probe=d7f4b1678b) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | [09dfab066c](https://linux-hardware.org/?probe=09dfab066c) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f82628e802](https://linux-hardware.org/?probe=f82628e802) | Jun 21, 2022 |
| Lenovo        | G50-30 80G0                 | [402aec2b04](https://linux-hardware.org/?probe=402aec2b04) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [d6c4bb6995](https://linux-hardware.org/?probe=d6c4bb6995) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [23f396c697](https://linux-hardware.org/?probe=23f396c697) | Jun 21, 2022 |
| HP            | Pavilion Notebook           | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Dell          | Inspiron 3451               | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [ee2f7822c9](https://linux-hardware.org/?probe=ee2f7822c9) | Jun 18, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [f944290604](https://linux-hardware.org/?probe=f944290604) | Jun 17, 2022 |
| Dell          | Latitude E5450              | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| Acer          | Aspire E1-570G              | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| mPTech        | ARC 11.6 128GB HD           | [b9469e3ae8](https://linux-hardware.org/?probe=b9469e3ae8) | Jun 15, 2022 |
| Dell          | Latitude E6430s             | [a1043bd5bf](https://linux-hardware.org/?probe=a1043bd5bf) | Jun 14, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| Dell          | Inspiron 3451               | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| Dell          | Latitude E5470              | [a4533cfbc7](https://linux-hardware.org/?probe=a4533cfbc7) | Jun 14, 2022 |
| Acer          | Aspire 7738                 | [39646d89f1](https://linux-hardware.org/?probe=39646d89f1) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e33ea31f97](https://linux-hardware.org/?probe=e33ea31f97) | Jun 13, 2022 |
| HP            | EliteBook 850 G2            | [10b796ad9c](https://linux-hardware.org/?probe=10b796ad9c) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | [fc31a9ec53](https://linux-hardware.org/?probe=fc31a9ec53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | [916ce4be3b](https://linux-hardware.org/?probe=916ce4be3b) | Jun 13, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| HP            | ZBook Studio G3             | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| Lenovo        | M490s 20214                 | [961e8807e9](https://linux-hardware.org/?probe=961e8807e9) | Jun 12, 2022 |
| ASUSTek       | K53BR                       | [b64b9e0f4a](https://linux-hardware.org/?probe=b64b9e0f4a) | Jun 12, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Acer          | Aspire A515-51G             | [785b725767](https://linux-hardware.org/?probe=785b725767) | Jun 10, 2022 |
| Dell          | Latitude 5310               | [fe0ffed6e4](https://linux-hardware.org/?probe=fe0ffed6e4) | Jun 10, 2022 |
| HP            | EliteBook 850 G3            | [e086b31446](https://linux-hardware.org/?probe=e086b31446) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| Dell          | Latitude E6420              | [a92cd16ef7](https://linux-hardware.org/?probe=a92cd16ef7) | Jun 10, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [58d62f94d4](https://linux-hardware.org/?probe=58d62f94d4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T500 2241A87       | [96b00f450d](https://linux-hardware.org/?probe=96b00f450d) | Jun 09, 2022 |
| Acer          | Nitro AN515-54              | [d14ead3bf7](https://linux-hardware.org/?probe=d14ead3bf7) | Jun 09, 2022 |
| HP            | ProBook 450 G5              | [cec4cb4af4](https://linux-hardware.org/?probe=cec4cb4af4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T530 2429B68       | [86e92f8a19](https://linux-hardware.org/?probe=86e92f8a19) | Jun 09, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ebc62a50b4](https://linux-hardware.org/?probe=ebc62a50b4) | Jun 08, 2022 |
| Acer          | Swift SF314-42              | [5af5c89f5e](https://linux-hardware.org/?probe=5af5c89f5e) | Jun 08, 2022 |
| Dell          | Latitude 5421               | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| Dell          | Precision 5550              | [a4bf41771c](https://linux-hardware.org/?probe=a4bf41771c) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| Dell          | Inspiron 3451               | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| HP            | Pavilion dv6700             | [a688137dd3](https://linux-hardware.org/?probe=a688137dd3) | Jun 07, 2022 |
| Unknown       | Unknown                     | [c0625a957b](https://linux-hardware.org/?probe=c0625a957b) | Jun 06, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Dell          | Latitude E6430              | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Fujitsu       | FMVA0800C                   | [bacd4a55bb](https://linux-hardware.org/?probe=bacd4a55bb) | Jun 05, 2022 |
| Acer          | Swift SF314-42              | [fbfcffd093](https://linux-hardware.org/?probe=fbfcffd093) | Jun 03, 2022 |
| Lenovo        | G580 20150                  | [ca44145e04](https://linux-hardware.org/?probe=ca44145e04) | Jun 03, 2022 |
| Dell          | Inspiron 3451               | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [2db8072ec9](https://linux-hardware.org/?probe=2db8072ec9) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5b88aad243](https://linux-hardware.org/?probe=5b88aad243) | Jun 02, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| Dell          | Inspiron 5749               | [408e42beb8](https://linux-hardware.org/?probe=408e42beb8) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d12c2f9f7c](https://linux-hardware.org/?probe=d12c2f9f7c) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Dell          | Inspiron 5521               | [4fdf9880d4](https://linux-hardware.org/?probe=4fdf9880d4) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| HP            | EliteBook 8440p             | [4df2d3c129](https://linux-hardware.org/?probe=4df2d3c129) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a08d3e5d4b](https://linux-hardware.org/?probe=a08d3e5d4b) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c71a8e9817](https://linux-hardware.org/?probe=c71a8e9817) | May 29, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| MSI           | GP76 Leopard 10UE           | [9e74d767a6](https://linux-hardware.org/?probe=9e74d767a6) | May 29, 2022 |
| Dell          | Inspiron 3451               | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [8e577a4a1a](https://linux-hardware.org/?probe=8e577a4a1a) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [b8c8e8baef](https://linux-hardware.org/?probe=b8c8e8baef) | May 27, 2022 |
| Dell          | Inspiron 3451               | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [cff9e3245c](https://linux-hardware.org/?probe=cff9e3245c) | May 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [29b8def5b3](https://linux-hardware.org/?probe=29b8def5b3) | May 25, 2022 |
| Dell          | Latitude 5310               | [2117fbfccb](https://linux-hardware.org/?probe=2117fbfccb) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | [ce09b72069](https://linux-hardware.org/?probe=ce09b72069) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | [cee3591bcd](https://linux-hardware.org/?probe=cee3591bcd) | May 25, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [0517751353](https://linux-hardware.org/?probe=0517751353) | May 24, 2022 |
| Dell          | Latitude 5310               | [cb40714b3f](https://linux-hardware.org/?probe=cb40714b3f) | May 24, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [ed4df544d6](https://linux-hardware.org/?probe=ed4df544d6) | May 24, 2022 |
| HP            | Pavilion 15                 | [4140810d35](https://linux-hardware.org/?probe=4140810d35) | May 24, 2022 |
| HP            | 250 G8 Notebook PC          | [2f4c72e2a9](https://linux-hardware.org/?probe=2f4c72e2a9) | May 24, 2022 |
| HP            | ProBook 6475b               | [5202cf8c75](https://linux-hardware.org/?probe=5202cf8c75) | May 23, 2022 |
| HP            | Pavilion 15                 | [ca77af8ab9](https://linux-hardware.org/?probe=ca77af8ab9) | May 23, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [d728114b9b](https://linux-hardware.org/?probe=d728114b9b) | May 22, 2022 |
| Acer          | Aspire E5-571G              | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| Acer          | Nitro AN515-54              | [04a8f20f28](https://linux-hardware.org/?probe=04a8f20f28) | May 21, 2022 |
| Dell          | Inspiron 3451               | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| Lenovo        | G50-70 20351                | [b6f469418c](https://linux-hardware.org/?probe=b6f469418c) | May 21, 2022 |
| Dell          | Latitude 5490               | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell          | Inspiron 3451               | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| HP            | EliteBook 8570w             | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| HP            | EliteBook 850 G6            | [1b672f1faa](https://linux-hardware.org/?probe=1b672f1faa) | May 20, 2022 |
| HP            | EliteBook 850 G6            | [d2232927a7](https://linux-hardware.org/?probe=d2232927a7) | May 20, 2022 |
| HP            | 250 G4 Notebook PC          | [1472f65ca0](https://linux-hardware.org/?probe=1472f65ca0) | May 19, 2022 |
| Sony          | VGN-NR32L_S                 | [2709583292](https://linux-hardware.org/?probe=2709583292) | May 18, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [5e0b60c547](https://linux-hardware.org/?probe=5e0b60c547) | May 17, 2022 |
| Dell          | Latitude E6230              | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| Dell          | Inspiron 5735               | [b678e46de2](https://linux-hardware.org/?probe=b678e46de2) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| Toshiba       | Satellite L750D             | [6a84eb18c8](https://linux-hardware.org/?probe=6a84eb18c8) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Dell          | Inspiron 3583               | [3589bb82ad](https://linux-hardware.org/?probe=3589bb82ad) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| Lenovo        | ThinkPad T500 2241W2B       | [2bd7b2d9a4](https://linux-hardware.org/?probe=2bd7b2d9a4) | May 14, 2022 |
| Packard Be... | EasyNote ENTF71BM           | [e8808a770a](https://linux-hardware.org/?probe=e8808a770a) | May 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Dell          | MXG061                      | [36b09ae01e](https://linux-hardware.org/?probe=36b09ae01e) | May 14, 2022 |
| HP            | 250 G4 Notebook PC          | [996bc01199](https://linux-hardware.org/?probe=996bc01199) | May 13, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [761f1a1cbd](https://linux-hardware.org/?probe=761f1a1cbd) | May 13, 2022 |
| Dell          | Inspiron 3541               | [7873185850](https://linux-hardware.org/?probe=7873185850) | May 12, 2022 |
| HP            | EliteBook 820 G1            | [dd51bb3592](https://linux-hardware.org/?probe=dd51bb3592) | May 12, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [c64195c6bb](https://linux-hardware.org/?probe=c64195c6bb) | May 12, 2022 |
| HP            | EliteBook 840 G1            | [a57e3f28c2](https://linux-hardware.org/?probe=a57e3f28c2) | May 12, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7d03983e37](https://linux-hardware.org/?probe=7d03983e37) | May 11, 2022 |
| Dell          | Precision 7530              | [d97721b6cf](https://linux-hardware.org/?probe=d97721b6cf) | May 11, 2022 |
| Dell          | Inspiron 3583               | [5b2b56f445](https://linux-hardware.org/?probe=5b2b56f445) | May 11, 2022 |
| Lenovo        | V15-IIL 82C5                | [b02040672d](https://linux-hardware.org/?probe=b02040672d) | May 11, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [af186fe9e3](https://linux-hardware.org/?probe=af186fe9e3) | May 10, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [b6fed1d4fe](https://linux-hardware.org/?probe=b6fed1d4fe) | May 10, 2022 |
| HP            | EliteBook 820 G3            | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| HP            | EliteBook 8570w             | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9e81b04453](https://linux-hardware.org/?probe=9e81b04453) | May 09, 2022 |
| HP            | EliteBook 8570w             | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 340       | 12.14%  |
| OpenMandriva 4.2             | 187       | 6.68%   |
| Ubuntu 18.04                 | 166       | 5.93%   |
| Ubuntu 22.04                 | 120       | 4.28%   |
| OpenMandriva 4.3             | 103       | 3.68%   |
| Debian 11                    | 84        | 3%      |
| Arch Rolling                 | 51        | 1.82%   |
| ROSA R10                     | 50        | 1.79%   |
| Linux Mint 20.3              | 42        | 1.5%    |
| Linux Mint 20.1              | 42        | 1.5%    |
| Arch                         | 42        | 1.5%    |
| KDE neon 20.04               | 40        | 1.43%   |
| ROSA R9                      | 39        | 1.39%   |
| OpenMandriva 23.01           | 37        | 1.32%   |
| Fedora 36                    | 36        | 1.29%   |
| ROSA R11.1                   | 34        | 1.21%   |
| Manjaro                      | 34        | 1.21%   |
| Linux Mint 20.2              | 33        | 1.18%   |
| Ubuntu 21.04                 | 32        | 1.14%   |
| Ubuntu 20.10                 | 32        | 1.14%   |
| Zorin 16                     | 31        | 1.11%   |
| Linux Mint 19.3              | 31        | 1.11%   |
| Fedora 37                    | 30        | 1.07%   |
| ROSA R11                     | 29        | 1.04%   |
| Zorin 15                     | 27        | 0.96%   |
| Ubuntu 19.10                 | 27        | 0.96%   |
| Linux Mint 20                | 27        | 0.96%   |
| Ubuntu 21.10                 | 26        | 0.93%   |
| Xubuntu 20.04                | 25        | 0.89%   |
| ROSA R8                      | 25        | 0.89%   |
| Fedora 33                    | 25        | 0.89%   |
| Fedora 32                    | 24        | 0.86%   |
| Fedora 35                    | 23        | 0.82%   |
| Ubuntu 22.10                 | 22        | 0.79%   |
| Linux Mint 21                | 22        | 0.79%   |
| openSUSE Tumbleweed-XXXXXXXX | 21        | 0.75%   |
| Debian 10                    | 21        | 0.75%   |
| Fedora 34                    | 20        | 0.71%   |
| Pop!_OS 20.04                | 19        | 0.68%   |
| Linux Mint 21.1              | 18        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 764       | 28.91%  |
| OpenMandriva  | 345       | 13.05%  |
| Linux Mint    | 219       | 8.29%   |
| ROSA          | 181       | 6.85%   |
| Fedora        | 175       | 6.62%   |
| Debian        | 125       | 4.73%   |
| Manjaro       | 106       | 4.01%   |
| Arch          | 89        | 3.37%   |
| Pop!_OS       | 69        | 2.61%   |
| Zorin         | 61        | 2.31%   |
| KDE neon      | 53        | 2.01%   |
| Kubuntu       | 49        | 1.85%   |
| Xubuntu       | 44        | 1.66%   |
| Kali          | 35        | 1.32%   |
| Lubuntu       | 26        | 0.98%   |
| openSUSE      | 23        | 0.87%   |
| Endless       | 23        | 0.87%   |
| Elementary    | 21        | 0.79%   |
| Gentoo        | 20        | 0.76%   |
| ArcoLinux     | 19        | 0.72%   |
| LMDE          | 15        | 0.57%   |
| Clear Linux   | 13        | 0.49%   |
| SteamOS       | 12        | 0.45%   |
| Nobara        | 11        | 0.42%   |
| EndeavourOS   | 11        | 0.42%   |
| Ubuntu Unity  | 10        | 0.38%   |
| Garuda Linux  | 9         | 0.34%   |
| Ubuntu MATE   | 8         | 0.3%    |
| LinuxFX       | 8         | 0.3%    |
| Ubuntu Budgie | 7         | 0.26%   |
| Peppermint    | 7         | 0.26%   |
| MX            | 7         | 0.26%   |
| BlackPanther  | 6         | 0.23%   |
| CentOS        | 5         | 0.19%   |
| Parrot        | 4         | 0.15%   |
| Linux Lite    | 4         | 0.15%   |
| Xero          | 3         | 0.11%   |
| Sparky        | 3         | 0.11%   |
| Solus         | 3         | 0.11%   |
| NixOS         | 3         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 5.78%   |
| 5.16.7-desktop-1omv4003         | 102       | 3.33%   |
| 5.4.0-42-generic                | 44        | 1.44%   |
| 6.1.1-desktop-1omv2290          | 35        | 1.14%   |
| 5.15.0-56-generic               | 29        | 0.95%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 26        | 0.85%   |
| 5.15.0-58-generic               | 25        | 0.82%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 24        | 0.78%   |
| 5.4.0-52-generic                | 22        | 0.72%   |
| 5.4.0-48-generic                | 22        | 0.72%   |
| 5.15.0-43-generic               | 22        | 0.72%   |
| 5.15.0-52-generic               | 21        | 0.69%   |
| 5.4.0-29-generic                | 20        | 0.65%   |
| 5.4.0-58-generic                | 19        | 0.62%   |
| 5.4.0-26-generic                | 19        | 0.62%   |
| 5.3.0-46-generic                | 18        | 0.59%   |
| 5.15.0-53-generic               | 18        | 0.59%   |
| 5.4.0-33-generic                | 17        | 0.56%   |
| 5.11.0-37-generic               | 17        | 0.56%   |
| 5.0.0-37-generic                | 17        | 0.56%   |
| 5.4.0-54-generic                | 16        | 0.52%   |
| 5.15.0-48-generic               | 16        | 0.52%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 16        | 0.52%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 16        | 0.52%   |
| 5.8.0-43-generic                | 15        | 0.49%   |
| 5.4.0-40-generic                | 14        | 0.46%   |
| 5.4.0-37-generic                | 14        | 0.46%   |
| 5.3.0-40-generic                | 14        | 0.46%   |
| 5.3.0-42-generic                | 13        | 0.42%   |
| 5.13.0-39-generic               | 13        | 0.42%   |
| 5.13.0-27-generic               | 13        | 0.42%   |
| 5.11.0-43-generic               | 13        | 0.42%   |
| 5.11.0-27-generic               | 13        | 0.42%   |
| 5.11.0-25-generic               | 13        | 0.42%   |
| 4.15.0-43-generic               | 13        | 0.42%   |
| 5.4.0-91-generic                | 12        | 0.39%   |
| 5.4.0-74-generic                | 12        | 0.39%   |
| 5.15.0-60-generic               | 12        | 0.39%   |
| 5.15.0-47-generic               | 12        | 0.39%   |
| 5.13.0-28-generic               | 12        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 438       | 15.07%  |
| 5.15.0  | 217       | 7.47%   |
| 5.10.14 | 178       | 6.13%   |
| 4.15.0  | 148       | 5.09%   |
| 5.11.0  | 144       | 4.96%   |
| 5.8.0   | 127       | 4.37%   |
| 5.13.0  | 117       | 4.03%   |
| 5.3.0   | 103       | 3.54%   |
| 5.16.7  | 103       | 3.54%   |
| 5.10.0  | 96        | 3.3%    |
| 5.0.0   | 61        | 2.1%    |
| 4.18.0  | 58        | 2%      |
| 5.19.0  | 38        | 1.31%   |
| 6.1.1   | 36        | 1.24%   |
| 4.9.20  | 35        | 1.2%    |
| 4.9.60  | 32        | 1.1%    |
| 4.19.0  | 30        | 1.03%   |
| 5.14.0  | 25        | 0.86%   |
| 4.1.34  | 22        | 0.76%   |
| 6.0.0   | 17        | 0.58%   |
| 5.11.12 | 14        | 0.48%   |
| 4.1.38  | 14        | 0.48%   |
| 5.17.0  | 12        | 0.41%   |
| 6.0.7   | 11        | 0.38%   |
| 5.9.0   | 11        | 0.38%   |
| 5.17.5  | 11        | 0.38%   |
| 5.4.32  | 10        | 0.34%   |
| 5.16.0  | 9         | 0.31%   |
| 5.5.0   | 8         | 0.28%   |
| 5.4.83  | 8         | 0.28%   |
| 4.9.76  | 8         | 0.28%   |
| 6.1.8   | 7         | 0.24%   |
| 6.1.10  | 7         | 0.24%   |
| 5.19.14 | 7         | 0.24%   |
| 5.18.12 | 7         | 0.24%   |
| 5.18.0  | 7         | 0.24%   |
| 5.16.11 | 7         | 0.24%   |
| 5.15.12 | 7         | 0.24%   |
| 4.9.155 | 7         | 0.24%   |
| 6.0.9   | 6         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 496       | 17.45%  |
| 5.10    | 325       | 11.43%  |
| 5.15    | 281       | 9.88%   |
| 5.11    | 182       | 6.4%    |
| 5.8     | 158       | 5.56%   |
| 5.16    | 155       | 5.45%   |
| 4.15    | 148       | 5.21%   |
| 5.13    | 134       | 4.71%   |
| 5.3     | 115       | 4.05%   |
| 4.9     | 100       | 3.52%   |
| 6.1     | 77        | 2.71%   |
| 5.19    | 74        | 2.6%    |
| 6.0     | 72        | 2.53%   |
| 5.0     | 67        | 2.36%   |
| 4.18    | 61        | 2.15%   |
| 5.14    | 55        | 1.93%   |
| 5.17    | 49        | 1.72%   |
| 5.9     | 42        | 1.48%   |
| 5.6     | 41        | 1.44%   |
| 5.18    | 39        | 1.37%   |
| 4.19    | 36        | 1.27%   |
| 4.1     | 35        | 1.23%   |
| 5.12    | 25        | 0.88%   |
| 5.5     | 23        | 0.81%   |
| 5.7     | 20        | 0.7%    |
| 4.4     | 8         | 0.28%   |
| 5.1     | 6         | 0.21%   |
| 3.10    | 4         | 0.14%   |
| 5.2     | 3         | 0.11%   |
| 6.2     | 2         | 0.07%   |
| 4.20    | 2         | 0.07%   |
| 4.13    | 2         | 0.07%   |
| 4.10    | 2         | 0.07%   |
| 4.17    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.12    | 1         | 0.04%   |
| 4.11    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2442      | 95.84%  |
| i686    | 105       | 4.12%   |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1000      | 37.48%  |
| KDE5            | 639       | 23.95%  |
| Unknown         | 255       | 9.56%   |
| XFCE            | 186       | 6.97%   |
| X-Cinnamon      | 153       | 5.73%   |
| KDE4            | 97        | 3.64%   |
| KDE             | 71        | 2.66%   |
| MATE            | 55        | 2.06%   |
| Cinnamon        | 41        | 1.54%   |
| LXQt            | 38        | 1.42%   |
| LXDE            | 34        | 1.27%   |
| Pantheon        | 19        | 0.71%   |
| i3              | 15        | 0.56%   |
| Budgie          | 14        | 0.52%   |
| Unity           | 12        | 0.45%   |
| Deepin          | 9         | 0.34%   |
| GNOME Flashback | 6         | 0.22%   |
| sway            | 3         | 0.11%   |
| GNOME Classic   | 3         | 0.11%   |
| awesome         | 3         | 0.11%   |
| Trinity         | 2         | 0.07%   |
| qtile           | 2         | 0.07%   |
| Hyprland        | 2         | 0.07%   |
| fluxbox         | 2         | 0.07%   |
| DWM             | 2         | 0.07%   |
| stumpwm         | 1         | 0.04%   |
| qt5ct           | 1         | 0.04%   |
| openbox         | 1         | 0.04%   |
| icewm           | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2083      | 79.44%  |
| Wayland | 381       | 14.53%  |
| Unknown | 131       | 5%      |
| Tty     | 27        | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1100      | 41.29%  |
| SDDM    | 617       | 23.16%  |
| GDM     | 333       | 12.5%   |
| GDM3    | 209       | 7.85%   |
| LightDM | 200       | 7.51%   |
| KDM     | 99        | 3.72%   |
| TDM     | 95        | 3.57%   |
| XDM     | 5         | 0.19%   |
| Ly      | 2         | 0.08%   |
| SLIMSKI | 1         | 0.04%   |
| SLiM    | 1         | 0.04%   |
| MDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pl_PL   | 1389      | 52.81%  |
| en_US   | 698       | 26.54%  |
| Unknown | 371       | 14.11%  |
| en_GB   | 71        | 2.7%    |
| C       | 41        | 1.56%   |
| ru_RU   | 15        | 0.57%   |
| szl_PL  | 9         | 0.34%   |
| de_DE   | 5         | 0.19%   |
| uk_UA   | 4         | 0.15%   |
| fr_FR   | 3         | 0.11%   |
| en_IE   | 3         | 0.11%   |
| ru_UA   | 2         | 0.08%   |
| nl_NL   | 2         | 0.08%   |
| it_IT   | 2         | 0.08%   |
| hu_HU   | 2         | 0.08%   |
| en_DK   | 2         | 0.08%   |
| C.UTF8  | 2         | 0.08%   |
| sk_SK   | 1         | 0.04%   |
| POSIX   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_IN   | 1         | 0.04%   |
| en_CA   | 1         | 0.04%   |
| en_AU   | 1         | 0.04%   |
| en_AG   | 1         | 0.04%   |
| af_ZA   | 1         | 0.04%   |
| aa_DJ   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1354      | 52.16%  |
| EFI  | 1242      | 47.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 1832      | 69.87%  |
| Overlay  | 332       | 12.66%  |
| Btrfs    | 209       | 7.97%   |
| Unknown  | 173       | 6.6%    |
| Xfs      | 36        | 1.37%   |
| Zfs      | 20        | 0.76%   |
| F2fs     | 9         | 0.34%   |
| Ext3     | 3         | 0.11%   |
| Ext2     | 3         | 0.11%   |
| Tmpfs    | 2         | 0.08%   |
| XXXXX    | 1         | 0.04%   |
| Rootfs   | 1         | 0.04%   |
| Bcachefs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1244      | 47.63%  |
| GPT     | 933       | 35.72%  |
| MBR     | 435       | 16.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2208      | 85.02%  |
| Yes       | 389       | 14.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1758      | 67.9%   |
| Yes       | 831       | 32.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 665       | 26.14%  |
| Dell                | 548       | 21.54%  |
| Hewlett-Packard     | 382       | 15.02%  |
| ASUSTek Computer    | 303       | 11.91%  |
| Acer                | 167       | 6.56%   |
| Samsung Electronics | 72        | 2.83%   |
| Toshiba             | 69        | 2.71%   |
| MSI                 | 60        | 2.36%   |
| Sony                | 34        | 1.34%   |
| HUAWEI              | 27        | 1.06%   |
| Apple               | 23        | 0.9%    |
| Fujitsu             | 21        | 0.83%   |
| Fujitsu Siemens     | 20        | 0.79%   |
| Valve               | 12        | 0.47%   |
| Packard Bell        | 12        | 0.47%   |
| Notebook            | 12        | 0.47%   |
| Google              | 12        | 0.47%   |
| eMachines           | 9         | 0.35%   |
| Medion              | 8         | 0.31%   |
| Timi                | 7         | 0.28%   |
| Kiano               | 6         | 0.24%   |
| Unknown             | 5         | 0.2%    |
| Kruger&Matz         | 4         | 0.16%   |
| Gigabyte Technology | 4         | 0.16%   |
| Alienware           | 4         | 0.16%   |
| mPTech              | 3         | 0.12%   |
| Clevo               | 3         | 0.12%   |
| Chuwi               | 3         | 0.12%   |
| TrekStor            | 2         | 0.08%   |
| Teclast             | 2         | 0.08%   |
| System76            | 2         | 0.08%   |
| Star Labs           | 2         | 0.08%   |
| Schenker            | 2         | 0.08%   |
| Panasonic           | 2         | 0.08%   |
| MODECOM             | 2         | 0.08%   |
| MAXDATA             | 2         | 0.08%   |
| Maibenben           | 2         | 0.08%   |
| Intel               | 2         | 0.08%   |
| IBM                 | 2         | 0.08%   |
| GPU Company         | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Dell Inspiron 3451                  | 31        | 1.22%   |
| Unknown                             | 26        | 1.02%   |
| Dell Latitude E6400                 | 15        | 0.59%   |
| Dell Latitude E6540                 | 14        | 0.55%   |
| Valve Jupiter                       | 12        | 0.47%   |
| Lenovo G50-30 80G0                  | 12        | 0.47%   |
| Dell Latitude 5480                  | 12        | 0.47%   |
| Dell Latitude E6430                 | 11        | 0.43%   |
| Dell Latitude D630                  | 11        | 0.43%   |
| HP Pavilion dv7                     | 10        | 0.39%   |
| Dell Latitude 5490                  | 10        | 0.39%   |
| Dell Latitude E6420                 | 9         | 0.35%   |
| ASUS X555LJ                         | 9         | 0.35%   |
| Lenovo Legion Y530-15ICH 81FV       | 8         | 0.31%   |
| Lenovo G580 20150                   | 8         | 0.31%   |
| Dell Latitude E7440                 | 8         | 0.31%   |
| Lenovo Legion Y540-15IRH 81SX       | 7         | 0.28%   |
| Lenovo G510 20238                   | 7         | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 7         | 0.28%   |
| HP Notebook                         | 7         | 0.28%   |
| HP EliteBook 6930p                  | 7         | 0.28%   |
| HP 15                               | 7         | 0.28%   |
| Dell Latitude E6330                 | 7         | 0.28%   |
| Dell Latitude E5430 non-vPro        | 7         | 0.28%   |
| Dell Latitude 5420                  | 7         | 0.28%   |
| Toshiba Satellite A300              | 6         | 0.24%   |
| Samsung 550P5C/550P7C               | 6         | 0.24%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 6         | 0.24%   |
| Lenovo Z51-70 80K6                  | 6         | 0.24%   |
| Lenovo Legion 5 15ARH05 82B5        | 6         | 0.24%   |
| Lenovo IdeaPad Y510P 20217          | 6         | 0.24%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 6         | 0.24%   |
| Lenovo IdeaPad 100-15IBD 80QQ       | 6         | 0.24%   |
| Lenovo G500 20236                   | 6         | 0.24%   |
| HUAWEI HVY-WXX9                     | 6         | 0.24%   |
| HP Pavilion g6                      | 6         | 0.24%   |
| HP Pavilion dv6                     | 6         | 0.24%   |
| HP Laptop 15-db1xxx                 | 6         | 0.24%   |
| HP 250 G6 Notebook PC               | 6         | 0.24%   |
| Dell Latitude E7450                 | 6         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 301       | 11.83%  |
| Dell Latitude         | 286       | 11.24%  |
| Dell Inspiron         | 143       | 5.62%   |
| Lenovo IdeaPad        | 133       | 5.23%   |
| Acer Aspire           | 105       | 4.13%   |
| HP EliteBook          | 83        | 3.26%   |
| HP Pavilion           | 81        | 3.18%   |
| HP ProBook            | 60        | 2.36%   |
| Toshiba Satellite     | 56        | 2.2%    |
| Lenovo Legion         | 47        | 1.85%   |
| ASUS VivoBook         | 35        | 1.38%   |
| Dell Precision        | 34        | 1.34%   |
| HP Laptop             | 30        | 1.18%   |
| Dell XPS              | 29        | 1.14%   |
| Dell Vostro           | 29        | 1.14%   |
| Unknown               | 26        | 1.02%   |
| HP Compaq             | 20        | 0.79%   |
| Fujitsu LIFEBOOK      | 19        | 0.75%   |
| HP 250                | 18        | 0.71%   |
| ASUS ASUS             | 17        | 0.67%   |
| ASUS TUF              | 16        | 0.63%   |
| HP ZBook              | 15        | 0.59%   |
| ASUS ROG              | 15        | 0.59%   |
| Acer Extensa          | 15        | 0.59%   |
| Lenovo ThinkBook      | 13        | 0.51%   |
| Valve Jupiter         | 12        | 0.47%   |
| Packard Bell EasyNote | 12        | 0.47%   |
| Lenovo G50-30         | 12        | 0.47%   |
| Lenovo Yoga           | 11        | 0.43%   |
| Acer TravelMate       | 11        | 0.43%   |
| Acer Nitro            | 11        | 0.43%   |
| HP OMEN               | 10        | 0.39%   |
| Lenovo G580           | 9         | 0.35%   |
| ASUS X555LJ           | 9         | 0.35%   |
| Acer Swift            | 9         | 0.35%   |
| Fujitsu Siemens AMILO | 8         | 0.31%   |
| Dell G3               | 8         | 0.31%   |
| ASUS Zenbook          | 8         | 0.31%   |
| Samsung 350V5C        | 7         | 0.28%   |
| Lenovo G510           | 7         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 221       | 8.69%   |
| 2012    | 218       | 8.57%   |
| 2013    | 210       | 8.25%   |
| 2011    | 210       | 8.25%   |
| 2020    | 207       | 8.14%   |
| 2014    | 173       | 6.8%    |
| 2008    | 171       | 6.72%   |
| 2018    | 169       | 6.64%   |
| 2015    | 164       | 6.45%   |
| 2021    | 137       | 5.39%   |
| 2017    | 137       | 5.39%   |
| 2010    | 135       | 5.31%   |
| 2016    | 117       | 4.6%    |
| 2007    | 101       | 3.97%   |
| 2009    | 89        | 3.5%    |
| 2022    | 44        | 1.73%   |
| 2006    | 33        | 1.3%    |
| 2005    | 3         | 0.12%   |
| 2023    | 2         | 0.08%   |
| 2004    | 2         | 0.08%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2544      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2355      | 91.88%  |
| Enabled  | 208       | 8.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2530      | 99.45%  |
| Yes  | 14        | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 652       | 25.3%   |
| 4.01-8.0    | 613       | 23.79%  |
| 8.01-16.0   | 424       | 16.45%  |
| 16.01-24.0  | 405       | 15.72%  |
| 32.01-64.0  | 211       | 8.19%   |
| 1.01-2.0    | 119       | 4.62%   |
| 2.01-3.0    | 84        | 3.26%   |
| 24.01-32.0  | 27        | 1.05%   |
| 64.01-256.0 | 22        | 0.85%   |
| 0.51-1.0    | 20        | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1068      | 37.54%  |
| 2.01-3.0   | 636       | 22.36%  |
| 4.01-8.0   | 369       | 12.97%  |
| 3.01-4.0   | 353       | 12.41%  |
| 0.51-1.0   | 242       | 8.51%   |
| 8.01-16.0  | 126       | 4.43%   |
| 0.01-0.5   | 30        | 1.05%   |
| 16.01-24.0 | 15        | 0.53%   |
| 24.01-32.0 | 6         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1906      | 73.2%   |
| 2      | 579       | 22.24%  |
| 3      | 70        | 2.69%   |
| 0      | 37        | 1.42%   |
| 4      | 10        | 0.38%   |
| 5      | 2         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1498      | 58.27%  |
| Yes       | 1073      | 41.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2229      | 87.27%  |
| No        | 325       | 12.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2494      | 97.92%  |
| No        | 53        | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1949      | 75.28%  |
| No        | 640       | 24.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 2544      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 599       | 21.84%  |
| Krakow                 | 224       | 8.17%   |
| Wroclaw                | 161       | 5.87%   |
| Poznan                 | 150       | 5.47%   |
| Lodz                   | 93        | 3.39%   |
| Gdansk                 | 89        | 3.24%   |
| Katowice               | 69        | 2.52%   |
| Lublin                 | 36        | 1.31%   |
| Gdynia                 | 31        | 1.13%   |
| Szczecin               | 30        | 1.09%   |
| Rzeszów               | 22        | 0.8%    |
| Ruda Śląska          | 22        | 0.8%    |
| Bialystok              | 22        | 0.8%    |
| Częstochowa           | 21        | 0.77%   |
| Torun                  | 20        | 0.73%   |
| Bydgoszcz              | 20        | 0.73%   |
| Elblag                 | 18        | 0.66%   |
| Gliwice                | 17        | 0.62%   |
| Bytom                  | 16        | 0.58%   |
| Olsztyn                | 14        | 0.51%   |
| Kielce                 | 14        | 0.51%   |
| Sosnowiec              | 13        | 0.47%   |
| Chorzów               | 13        | 0.47%   |
| Tarnów                | 12        | 0.44%   |
| Opole                  | 12        | 0.44%   |
| Płock                 | 11        | 0.4%    |
| Blizniew               | 11        | 0.4%    |
| Siemianowice Śląskie | 10        | 0.36%   |
| Pruszków              | 10        | 0.36%   |
| Zabrze                 | 9         | 0.33%   |
| Tychy                  | 9         | 0.33%   |
| Gorzów Wielkopolski   | 8         | 0.29%   |
| Bielsko-Biala          | 8         | 0.29%   |
| Zielona Góra          | 7         | 0.26%   |
| Skawina                | 7         | 0.26%   |
| Rybnik                 | 7         | 0.26%   |
| Mielec                 | 7         | 0.26%   |
| Chojnice               | 7         | 0.26%   |
| Wejherowo              | 6         | 0.22%   |
| Stalowa Wola           | 6         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 451       | 592    | 14.27%  |
| Seagate                     | 377       | 468    | 11.93%  |
| WDC                         | 355       | 434    | 11.23%  |
| Toshiba                     | 213       | 266    | 6.74%   |
| GOODRAM                     | 196       | 252    | 6.2%    |
| Unknown                     | 153       | 193    | 4.84%   |
| SanDisk                     | 138       | 173    | 4.37%   |
| Hitachi                     | 122       | 146    | 3.86%   |
| Kingston                    | 118       | 158    | 3.73%   |
| SK hynix                    | 116       | 146    | 3.67%   |
| Intel                       | 114       | 145    | 3.61%   |
| Crucial                     | 110       | 157    | 3.48%   |
| A-DATA Technology           | 108       | 127    | 3.42%   |
| HGST                        | 70        | 87     | 2.22%   |
| Micron Technology           | 62        | 80     | 1.96%   |
| KIOXIA                      | 32        | 36     | 1.01%   |
| SPCC                        | 30        | 36     | 0.95%   |
| Patriot                     | 26        | 34     | 0.82%   |
| Plextor                     | 25        | 37     | 0.79%   |
| PNY                         | 21        | 22     | 0.66%   |
| Fujitsu                     | 20        | 21     | 0.63%   |
| LITEON                      | 17        | 21     | 0.54%   |
| Phison                      | 13        | 18     | 0.41%   |
| LITEONIT                    | 13        | 14     | 0.41%   |
| Transcend                   | 12        | 13     | 0.38%   |
| KIOXIA-EXCERIA              | 12        | 13     | 0.38%   |
| China                       | 12        | 15     | 0.38%   |
| Apacer                      | 12        | 17     | 0.38%   |
| Phison Electronics          | 11        | 11     | 0.35%   |
| Apple                       | 9         | 11     | 0.28%   |
| Silicon Motion              | 8         | 10     | 0.25%   |
| OCZ                         | 8         | 8      | 0.25%   |
| JMicron Technology          | 8         | 8      | 0.25%   |
| Lenovo                      | 7         | 9      | 0.22%   |
| HUAWEI                      | 7         | 9      | 0.22%   |
| Unknown                     | 7         | 8      | 0.22%   |
| Union Memory                | 6         | 9      | 0.19%   |
| Lite-On                     | 5         | 6      | 0.16%   |
| Lexar                       | 5         | 5      | 0.16%   |
| Kingston Technology Company | 5         | 5      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 53        | 1.62%   |
| Seagate ST1000LM035-1RK172 1TB                      | 46        | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 38        | 1.16%   |
| Intel NVMe SSD Drive 512GB                          | 25        | 0.76%   |
| Unknown MMC Card  32GB                              | 24        | 0.73%   |
| Toshiba MQ01ABD100 1TB                              | 23        | 0.7%    |
| Crucial CT500MX500SSD1 500GB                        | 23        | 0.7%    |
| Seagate ST9500325AS 500GB                           | 22        | 0.67%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 22        | 0.67%   |
| GOODRAM SSD 120GB                                   | 22        | 0.67%   |
| Samsung NVMe SSD Drive 512GB                        | 21        | 0.64%   |
| HGST HTS721010A9E630 1TB                            | 19        | 0.58%   |
| Unknown MMC Card  64GB                              | 18        | 0.55%   |
| Kingston SA400S37240G 240GB SSD                     | 18        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                         | 18        | 0.55%   |
| SanDisk NVMe SSD Drive 512GB                        | 17        | 0.52%   |
| Samsung SSD 850 EVO 250GB                           | 17        | 0.52%   |
| Intel SSDPEKNW512G8H 512GB                          | 17        | 0.52%   |
| Toshiba MQ01ABF050 500GB                            | 16        | 0.49%   |
| Samsung SSD 860 EVO 500GB                           | 15        | 0.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 15        | 0.46%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 15        | 0.46%   |
| GOODRAM SSD 240GB                                   | 15        | 0.46%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 14        | 0.43%   |
| Seagate Expansion 1TB                               | 14        | 0.43%   |
| HGST HTS725050A7E630 500GB                          | 13        | 0.4%    |
| GOODRAM SSDPR-CX400-256 256GB                       | 13        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 13        | 0.4%    |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.37%   |
| HGST HTS545050A7E680 500GB                          | 12        | 0.37%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 12        | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 11        | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                        | 11        | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 11        | 0.34%   |
| Seagate ST1000LM014-SSHD-8GB                        | 11        | 0.34%   |
| Samsung SSD 860 EVO 250GB                           | 11        | 0.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 11        | 0.34%   |
| Patriot Burst 120GB SSD                             | 11        | 0.34%   |
| SPCC Solid State Disk 512GB                         | 10        | 0.31%   |
| Seagate ST9250315AS 250GB                           | 10        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 375       | 464    | 36.44%  |
| WDC                 | 240       | 287    | 23.32%  |
| Toshiba             | 143       | 178    | 13.9%   |
| Hitachi             | 122       | 146    | 11.86%  |
| HGST                | 70        | 87     | 6.8%    |
| Samsung Electronics | 33        | 34     | 3.21%   |
| Fujitsu             | 20        | 21     | 1.94%   |
| JMicron Technology  | 7         | 7      | 0.68%   |
| Unknown             | 5         | 5      | 0.49%   |
| USB3.0              | 3         | 3      | 0.29%   |
| ASMT                | 3         | 3      | 0.29%   |
| ASMedia             | 3         | 3      | 0.29%   |
| StoreJet            | 1         | 1      | 0.1%    |
| SAGE                | 1         | 1      | 0.1%    |
| PHD 3.0             | 1         | 1      | 0.1%    |
| LaCie               | 1         | 2      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 212       | 274    | 17.82%  |
| GOODRAM             | 193       | 249    | 16.22%  |
| Crucial             | 106       | 152    | 8.91%   |
| Kingston            | 90        | 120    | 7.56%   |
| A-DATA Technology   | 90        | 107    | 7.56%   |
| SanDisk             | 85        | 108    | 7.14%   |
| WDC                 | 52        | 58     | 4.37%   |
| Intel               | 34        | 39     | 2.86%   |
| SK hynix            | 32        | 40     | 2.69%   |
| Toshiba             | 30        | 32     | 2.52%   |
| Micron Technology   | 30        | 38     | 2.52%   |
| SPCC                | 28        | 34     | 2.35%   |
| Patriot             | 24        | 32     | 2.02%   |
| Plextor             | 22        | 34     | 1.85%   |
| LITEON              | 17        | 21     | 1.43%   |
| PNY                 | 15        | 16     | 1.26%   |
| LITEONIT            | 13        | 14     | 1.09%   |
| China               | 12        | 15     | 1.01%   |
| Transcend           | 11        | 12     | 0.92%   |
| KIOXIA-EXCERIA      | 11        | 12     | 0.92%   |
| Apacer              | 10        | 15     | 0.84%   |
| OCZ                 | 8         | 8      | 0.67%   |
| Apple               | 6         | 6      | 0.5%    |
| KingSpec            | 3         | 4      | 0.25%   |
| 2-Power             | 3         | 3      | 0.25%   |
| Unknown             | 3         | 3      | 0.25%   |
| Union Memory        | 2         | 3      | 0.17%   |
| Team                | 2         | 2      | 0.17%   |
| Ramaxel Technology  | 2         | 3      | 0.17%   |
| Netac               | 2         | 3      | 0.17%   |
| Intenso             | 2         | 2      | 0.17%   |
| HS-SSD-C100         | 2         | 3      | 0.17%   |
| Gigabyte Technology | 2         | 3      | 0.17%   |
| Corsair             | 2         | 2      | 0.17%   |
| BIWIN               | 2         | 2      | 0.17%   |
| Wolf                | 1         | 2      | 0.08%   |
| WDC WDS2            | 1         | 1      | 0.08%   |
| W800SH              | 1         | 1      | 0.08%   |
| Verbatim            | 1         | 1      | 0.08%   |
| V Series            | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1092      | 1502   | 36.6%   |
| HDD     | 989       | 1244   | 33.14%  |
| NVMe    | 731       | 997    | 24.5%   |
| MMC     | 139       | 175    | 4.66%   |
| Unknown | 33        | 41     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1856      | 2665   | 65.63%  |
| NVMe | 731       | 994    | 25.85%  |
| MMC  | 139       | 175    | 4.92%   |
| SAS  | 102       | 125    | 3.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1510      | 2046   | 73.95%  |
| 0.51-1.0   | 488       | 647    | 23.9%   |
| 1.01-2.0   | 34        | 42     | 1.67%   |
| 4.01-10.0  | 5         | 5      | 0.24%   |
| 2.01-3.0   | 4         | 5      | 0.2%    |
| 3.01-4.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 821       | 30.27%  |
| 251-500        | 608       | 22.42%  |
| 1-20           | 343       | 12.65%  |
| 501-1000       | 295       | 10.88%  |
| 51-100         | 237       | 8.74%   |
| 21-50          | 127       | 4.68%   |
| 1001-2000      | 120       | 4.42%   |
| Unknown        | 102       | 3.76%   |
| 2001-3000      | 34        | 1.25%   |
| More than 3000 | 25        | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1220      | 43.46%  |
| 21-50          | 459       | 16.35%  |
| 101-250        | 368       | 13.11%  |
| 51-100         | 351       | 12.5%   |
| 251-500        | 157       | 5.59%   |
| Unknown        | 102       | 3.63%   |
| 501-1000       | 100       | 3.56%   |
| 1001-2000      | 38        | 1.35%   |
| 2001-3000      | 8         | 0.29%   |
| More than 3000 | 4         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 8         | 8      | 2.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 8         | 9      | 2.82%   |
| Seagate ST500LT012-9WS142 500GB                | 7         | 26     | 2.46%   |
| Seagate ST500LT012-1DG142 500GB                | 5         | 8      | 1.76%   |
| HGST HTS545050A7E680 500GB                     | 5         | 5      | 1.76%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 4         | 4      | 1.41%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 4         | 4      | 1.41%   |
| Hitachi HTS541612J9SA00 120GB                  | 4         | 5      | 1.41%   |
| WDC WD3200BPVT-80ZEST0 320GB                   | 3         | 3      | 1.06%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.06%   |
| Toshiba MK1246GSX 120GB                        | 3         | 3      | 1.06%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 3         | 3      | 1.06%   |
| Seagate ST9500420AS 500GB                      | 3         | 3      | 1.06%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.06%   |
| Seagate ST9250827AS 250GB                      | 3         | 3      | 1.06%   |
| Seagate ST9250410AS 250GB                      | 3         | 3      | 1.06%   |
| Seagate ST320LT020-9YG142 320GB                | 3         | 3      | 1.06%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 4      | 1.06%   |
| WDC WD1600BEVT-75A23T0 160GB                   | 2         | 2      | 0.7%    |
| WDC WD1600BEVT-22A23T0 160GB                   | 2         | 2      | 0.7%    |
| Toshiba MK5075GSX 500GB                        | 2         | 2      | 0.7%    |
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 0.7%    |
| Toshiba MK1637GSX 160GB                        | 2         | 2      | 0.7%    |
| Seagate ST980811AS 80GB                        | 2         | 2      | 0.7%    |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.7%    |
| Seagate ST9160821AS 160GB                      | 2         | 3      | 0.7%    |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 2      | 0.7%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD            | 2         | 2      | 0.7%    |
| Samsung Electronics HM250HI 250GB              | 2         | 2      | 0.7%    |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 2         | 2      | 0.7%    |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD          | 2         | 2      | 0.7%    |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 0.7%    |
| Hitachi HTS543232A7A384 320GB                  | 2         | 3      | 0.7%    |
| Hitachi HTS543225L9SA00 250GB                  | 2         | 2      | 0.7%    |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.7%    |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.7%    |
| Hitachi HTS542512K9SA00 120GB                  | 2         | 2      | 0.7%    |
| HGST HTS725050A7E630 500GB                     | 2         | 3      | 0.7%    |
| HGST HTS725032A7E630 320GB                     | 2         | 2      | 0.7%    |
| HGST HTS545050A7E380 500GB                     | 2         | 2      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 101    | 25.8%   |
| WDC                 | 37        | 38     | 13.07%  |
| Toshiba             | 36        | 46     | 12.72%  |
| Hitachi             | 30        | 35     | 10.6%   |
| Samsung Electronics | 17        | 18     | 6.01%   |
| A-DATA Technology   | 16        | 18     | 5.65%   |
| HGST                | 15        | 16     | 5.3%    |
| SK hynix            | 8         | 8      | 2.83%   |
| SanDisk             | 6         | 7      | 2.12%   |
| Intel               | 6         | 6      | 2.12%   |
| Kingston            | 5         | 5      | 1.77%   |
| Micron Technology   | 4         | 4      | 1.41%   |
| Fujitsu             | 4         | 4      | 1.41%   |
| Crucial             | 4         | 7      | 1.41%   |
| LITEONIT            | 3         | 3      | 1.06%   |
| LITEON              | 3         | 3      | 1.06%   |
| ASMedia             | 3         | 3      | 1.06%   |
| Patriot             | 2         | 4      | 0.71%   |
| OCZ                 | 2         | 2      | 0.71%   |
| SPCC                | 1         | 1      | 0.35%   |
| RENICE              | 1         | 1      | 0.35%   |
| Plextor             | 1         | 1      | 0.35%   |
| Platinet            | 1         | 1      | 0.35%   |
| Lexar               | 1         | 1      | 0.35%   |
| Lenovo              | 1         | 1      | 0.35%   |
| China               | 1         | 1      | 0.35%   |
| Apple               | 1         | 1      | 0.35%   |
| Apacer              | 1         | 1      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 101    | 35.96%  |
| WDC                 | 35        | 36     | 17.24%  |
| Toshiba             | 33        | 43     | 16.26%  |
| Hitachi             | 30        | 35     | 14.78%  |
| HGST                | 15        | 16     | 7.39%   |
| Samsung Electronics | 10        | 10     | 4.93%   |
| Fujitsu             | 4         | 4      | 1.97%   |
| ASMedia             | 3         | 3      | 1.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 201       | 248    | 72.04%  |
| SSD  | 65        | 74     | 23.3%   |
| NVMe | 13        | 15     | 4.66%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB       | 1         | 1      | 20%     |
| WDC WD3200BEKT-75PVMT1 320GB    | 1         | 1      | 20%     |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 1      | 20%     |
| Toshiba MK3265GSXN 320GB        | 1         | 1      | 20%     |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1296      | 2015   | 47.93%  |
| Works    | 1130      | 1602   | 41.79%  |
| Malfunc  | 273       | 337    | 10.1%   |
| Failed   | 5         | 5      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1972      | 66.71%  |
| AMD                              | 238       | 8.05%   |
| Samsung Electronics              | 221       | 7.48%   |
| SanDisk                          | 115       | 3.89%   |
| SK hynix                         | 84        | 2.84%   |
| Toshiba America Info Systems     | 44        | 1.49%   |
| Phison Electronics               | 37        | 1.25%   |
| KIOXIA                           | 35        | 1.18%   |
| Micron Technology                | 32        | 1.08%   |
| Kingston Technology Company      | 32        | 1.08%   |
| ADATA Technology                 | 23        | 0.78%   |
| Nvidia                           | 19        | 0.64%   |
| Silicon Motion                   | 16        | 0.54%   |
| Union Memory (Shenzhen)          | 12        | 0.41%   |
| Silicon Integrated Systems [SiS] | 11        | 0.37%   |
| Lite-On Technology               | 9         | 0.3%    |
| Realtek Semiconductor            | 8         | 0.27%   |
| Micron/Crucial Technology        | 8         | 0.27%   |
| Solid State Storage Technology   | 7         | 0.24%   |
| Lenovo                           | 7         | 0.24%   |
| VIA Technologies                 | 5         | 0.17%   |
| Shenzhen Longsys Electronics     | 4         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.14%   |
| JMicron Technology               | 4         | 0.14%   |
| Yangtze Memory Technologies      | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| Silicon Image                    | 1         | 0.03%   |
| O2 Micro                         | 1         | 0.03%   |
| Marvell Technology Group         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 218       | 6.69%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 195       | 5.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 173       | 5.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 151       | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 150       | 4.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 126       | 3.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 111       | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 110       | 3.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 101       | 3.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 91        | 2.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 89        | 2.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 81        | 2.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 75        | 2.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 70        | 2.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 70        | 2.15%   |
| Samsung NVMe SSD Controller 980                                                | 66        | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 66        | 2.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 61        | 1.87%   |
| Intel SSD 660P Series                                                          | 55        | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 53        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 37        | 1.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 36        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 36        | 1.1%    |
| Micron Non-Volatile memory controller                                          | 32        | 0.98%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 32        | 0.98%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 31        | 0.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 29        | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 27        | 0.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 26        | 0.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 23        | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                          | 23        | 0.71%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 23        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 0.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 22        | 0.67%   |
| SK hynix BC511                                                                 | 21        | 0.64%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 20        | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 20        | 0.61%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 18        | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1831      | 59.03%  |
| NVMe | 740       | 23.86%  |
| IDE  | 299       | 9.64%   |
| RAID | 232       | 7.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2166      | 85.14%  |
| AMD          | 376       | 14.78%  |
| QUALCOMM     | 1         | 0.04%   |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 49        | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 42        | 1.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 38        | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 34        | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 1.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 32        | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 32        | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 29        | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 28        | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 22        | 0.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 21        | 0.82%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 21        | 0.82%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 21        | 0.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 21        | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.79%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.79%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 20        | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 19        | 0.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.75%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.67%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 17        | 0.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 17        | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.63%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 16        | 0.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.63%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 15        | 0.59%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 15        | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 15        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 716       | 28.13%  |
| Intel Core i7                  | 493       | 19.37%  |
| Intel Core 2 Duo               | 213       | 8.37%   |
| Intel Core i3                  | 210       | 8.25%   |
| Intel Celeron                  | 137       | 5.38%   |
| Other                          | 135       | 5.3%    |
| AMD Ryzen 5                    | 113       | 4.44%   |
| AMD Ryzen 7                    | 80        | 3.14%   |
| Intel Pentium                  | 79        | 3.1%    |
| Intel Atom                     | 53        | 2.08%   |
| Intel Pentium Dual-Core        | 36        | 1.41%   |
| AMD A6                         | 23        | 0.9%    |
| Intel Core 2                   | 20        | 0.79%   |
| Intel Pentium Dual             | 17        | 0.67%   |
| Intel Genuine                  | 15        | 0.59%   |
| AMD A8                         | 15        | 0.59%   |
| AMD Ryzen 7 PRO                | 14        | 0.55%   |
| AMD E                          | 12        | 0.47%   |
| Intel Celeron M                | 11        | 0.43%   |
| AMD E1                         | 11        | 0.43%   |
| AMD A4                         | 11        | 0.43%   |
| Intel Xeon                     | 9         | 0.35%   |
| AMD A10                        | 9         | 0.35%   |
| Intel Pentium M                | 8         | 0.31%   |
| AMD E2                         | 8         | 0.31%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.28%   |
| AMD Ryzen 9                    | 7         | 0.28%   |
| AMD Athlon X2                  | 7         | 0.28%   |
| AMD Ryzen 3                    | 6         | 0.24%   |
| Intel Core Duo                 | 5         | 0.2%    |
| AMD C-60                       | 5         | 0.2%    |
| Intel Core i9                  | 4         | 0.16%   |
| Intel Celeron Dual-Core        | 4         | 0.16%   |
| AMD Turion X2 Dual-Core Mobile | 4         | 0.16%   |
| AMD Ryzen 5 PRO                | 4         | 0.16%   |
| AMD Phenom II                  | 4         | 0.16%   |
| AMD Athlon II                  | 4         | 0.16%   |
| Intel Core M                   | 3         | 0.12%   |
| Intel Pentium Silver           | 2         | 0.08%   |
| Intel Core m5                  | 2         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1433      | 56.28%  |
| 4       | 729       | 28.63%  |
| 6       | 164       | 6.44%   |
| 8       | 111       | 4.36%   |
| 1       | 66        | 2.59%   |
| Unknown | 21        | 0.82%   |
| 14      | 10        | 0.39%   |
| 12      | 5         | 0.2%    |
| 10      | 3         | 0.12%   |
| 3       | 2         | 0.08%   |
| 192     | 1         | 0.04%   |
| 5       | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2541      | 99.88%  |
| Unknown | 2         | 0.08%   |
| 2       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1778      | 69.73%  |
| 1       | 750       | 29.41%  |
| Unknown | 21        | 0.82%   |
| 8       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2464      | 96.67%  |
| 32-bit         | 45        | 1.77%   |
| Unknown        | 39        | 1.53%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 457       | 17.46%  |
| 0x206a7    | 187       | 7.14%   |
| 0x306a9    | 178       | 6.8%    |
| 0x1067a    | 105       | 4.01%   |
| 0x40651    | 97        | 3.71%   |
| 0x20655    | 84        | 3.21%   |
| 0x906ea    | 81        | 3.09%   |
| 0x806ec    | 80        | 3.06%   |
| 0x306c3    | 79        | 3.02%   |
| 0x30678    | 79        | 3.02%   |
| 0x306d4    | 75        | 2.86%   |
| 0x806c1    | 74        | 2.83%   |
| 0x406e3    | 70        | 2.67%   |
| 0x6fd      | 69        | 2.64%   |
| 0x806ea    | 67        | 2.56%   |
| 0x806e9    | 57        | 2.18%   |
| 0x10676    | 50        | 1.91%   |
| 0x506e3    | 48        | 1.83%   |
| 0x906e9    | 43        | 1.64%   |
| 0x0a50000c | 37        | 1.41%   |
| 0x20652    | 31        | 1.18%   |
| 0xa0652    | 29        | 1.11%   |
| 0x08600106 | 27        | 1.03%   |
| 0x806eb    | 24        | 0.92%   |
| 0x08108109 | 24        | 0.92%   |
| 0x08108102 | 23        | 0.88%   |
| 0x706e5    | 20        | 0.76%   |
| 0x6fb      | 18        | 0.69%   |
| 0x6f6      | 17        | 0.65%   |
| 0x08600103 | 17        | 0.65%   |
| 0x906ed    | 16        | 0.61%   |
| 0x806d1    | 16        | 0.61%   |
| 0x106ca    | 16        | 0.61%   |
| 0x08600104 | 16        | 0.61%   |
| 0x406c3    | 15        | 0.57%   |
| 0x06001119 | 15        | 0.57%   |
| 0x106c2    | 14        | 0.53%   |
| 0x906a3    | 13        | 0.5%    |
| 0x05000119 | 13        | 0.5%    |
| 0x6e8      | 12        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 442       | 17.36%  |
| Haswell          | 218       | 8.56%   |
| IvyBridge        | 215       | 8.44%   |
| SandyBridge      | 214       | 8.41%   |
| Penryn           | 173       | 6.79%   |
| Skylake          | 142       | 5.58%   |
| Core             | 140       | 5.5%    |
| Westmere         | 126       | 4.95%   |
| Silvermont       | 119       | 4.67%   |
| Broadwell        | 99        | 3.89%   |
| Zen 2            | 86        | 3.38%   |
| TigerLake        | 84        | 3.3%    |
| Zen+             | 59        | 2.32%   |
| Zen 3            | 45        | 1.77%   |
| Unknown          | 42        | 1.65%   |
| Icelake          | 39        | 1.53%   |
| CometLake        | 37        | 1.45%   |
| Bonnell          | 33        | 1.3%    |
| Bobcat           | 30        | 1.18%   |
| P6               | 29        | 1.14%   |
| Zen              | 19        | 0.75%   |
| Piledriver       | 19        | 0.75%   |
| Goldmont plus    | 16        | 0.63%   |
| K8 & K10 hybrid  | 14        | 0.55%   |
| Alderlake Hybrid | 14        | 0.55%   |
| Puma             | 13        | 0.51%   |
| K8 Hammer        | 13        | 0.51%   |
| Excavator        | 13        | 0.51%   |
| Jaguar           | 12        | 0.47%   |
| K10              | 11        | 0.43%   |
| Goldmont         | 10        | 0.39%   |
| K10 Llano        | 9         | 0.35%   |
| Nehalem          | 6         | 0.24%   |
| Steamroller      | 4         | 0.16%   |
| Tremont          | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1926      | 58.49%  |
| Nvidia                           | 785       | 23.84%  |
| AMD                              | 571       | 17.34%  |
| Silicon Integrated Systems [SiS] | 6         | 0.18%   |
| VIA Technologies                 | 5         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 207       | 6.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 198       | 5.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 118       | 3.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 101       | 2.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 97        | 2.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 89        | 2.59%   |
| Intel HD Graphics 5500                                                                   | 87        | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 87        | 2.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 86        | 2.5%    |
| Intel UHD Graphics 620                                                                   | 82        | 2.38%   |
| AMD Renoir                                                                               | 80        | 2.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 79        | 2.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 77        | 2.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 72        | 2.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 70        | 2.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 70        | 2.03%   |
| Intel HD Graphics 620                                                                    | 66        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 60        | 1.74%   |
| Intel HD Graphics 630                                                                    | 49        | 1.42%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 47        | 1.37%   |
| Intel HD Graphics 530                                                                    | 47        | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 43        | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 1.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 38        | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 32        | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 32        | 0.93%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 27        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 26        | 0.76%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 26        | 0.76%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 25        | 0.73%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 24        | 0.7%    |
| Nvidia GM108M [GeForce 840M]                                                             | 21        | 0.61%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 21        | 0.61%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 21        | 0.61%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 0.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 20        | 0.58%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1242      | 48.71%  |
| Intel + Nvidia           | 544       | 21.33%  |
| 1 x AMD                  | 328       | 12.86%  |
| 1 x Nvidia               | 176       | 6.9%    |
| Intel + AMD              | 138       | 5.41%   |
| AMD + Nvidia             | 64        | 2.51%   |
| 2 x AMD                  | 39        | 1.53%   |
| 1 x SiS                  | 6         | 0.24%   |
| 1 x VIA                  | 5         | 0.2%    |
| 2 x Intel                | 4         | 0.16%   |
| Other                    | 2         | 0.08%   |
| 2 x Nvidia               | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2153      | 83.48%  |
| Proprietary | 357       | 13.84%  |
| Unknown     | 69        | 2.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1541      | 58.95%  |
| 1.01-2.0   | 357       | 13.66%  |
| 0.01-0.5   | 334       | 12.78%  |
| 0.51-1.0   | 159       | 6.08%   |
| 3.01-4.0   | 158       | 6.04%   |
| 5.01-6.0   | 44        | 1.68%   |
| 7.01-8.0   | 15        | 0.57%   |
| 2.01-3.0   | 4         | 0.15%   |
| 8.01-16.0  | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 539       | 18.33%  |
| LG Display              | 460       | 15.64%  |
| Samsung Electronics     | 369       | 12.55%  |
| BOE                     | 333       | 11.32%  |
| Chimei Innolux          | 309       | 10.51%  |
| Dell                    | 113       | 3.84%   |
| Chi Mei Optoelectronics | 104       | 3.54%   |
| Lenovo                  | 91        | 3.09%   |
| Goldstar                | 57        | 1.94%   |
| Iiyama                  | 54        | 1.84%   |
| Sharp                   | 42        | 1.43%   |
| LG Philips              | 40        | 1.36%   |
| PANDA                   | 31        | 1.05%   |
| Philips                 | 29        | 0.99%   |
| BenQ                    | 25        | 0.85%   |
| AOC                     | 23        | 0.78%   |
| Acer                    | 23        | 0.78%   |
| InfoVision              | 22        | 0.75%   |
| NEC Computers           | 21        | 0.71%   |
| Hewlett-Packard         | 20        | 0.68%   |
| Apple                   | 19        | 0.65%   |
| HannStar                | 16        | 0.54%   |
| Ancor Communications    | 16        | 0.54%   |
| CPT                     | 14        | 0.48%   |
| Eizo                    | 13        | 0.44%   |
| LGD                     | 9         | 0.31%   |
| CSO                     | 9         | 0.31%   |
| Toshiba                 | 8         | 0.27%   |
| Seiko/Epson             | 8         | 0.27%   |
| ASUSTek Computer        | 8         | 0.27%   |
| Sony                    | 7         | 0.24%   |
| Panasonic               | 6         | 0.2%    |
| Mi                      | 6         | 0.2%    |
| Fujitsu Siemens         | 6         | 0.2%    |
| Valve                   | 5         | 0.17%   |
| MSI                     | 5         | 0.17%   |
| InnoLux Display         | 5         | 0.17%   |
| IBM                     | 5         | 0.17%   |
| Vestel Elektronik       | 4         | 0.14%   |
| TMX                     | 4         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 1.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.96%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 28        | 0.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.73%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 21        | 0.7%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 20        | 0.67%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 19        | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.57%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 15        | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 15        | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.5%    |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 13        | 0.43%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.43%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 12        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 12        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.4%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.37%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.37%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 11        | 0.37%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 10        | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.33%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.3%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.3%    |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 9         | 0.3%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 9         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 9         | 0.3%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 8         | 0.27%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 8         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1112      | 40.72%  |
| 1366x768 (WXGA)    | 729       | 26.69%  |
| 1600x900 (HD+)     | 190       | 6.96%   |
| 1280x800 (WXGA)    | 175       | 6.41%   |
| 3840x2160 (4K)     | 85        | 3.11%   |
| 2560x1440 (QHD)    | 77        | 2.82%   |
| 1920x1200 (WUXGA)  | 65        | 2.38%   |
| 1440x900 (WXGA+)   | 63        | 2.31%   |
| 1680x1050 (WSXGA+) | 50        | 1.83%   |
| 1024x600           | 26        | 0.95%   |
| 1280x1024 (SXGA)   | 21        | 0.77%   |
| 2560x1600          | 18        | 0.66%   |
| 3440x1440          | 16        | 0.59%   |
| 800x1280           | 12        | 0.44%   |
| 2560x1080          | 12        | 0.44%   |
| Unknown            | 9         | 0.33%   |
| 2160x1440          | 8         | 0.29%   |
| 1024x768 (XGA)     | 7         | 0.26%   |
| 3840x2400          | 6         | 0.22%   |
| 2880x1800          | 6         | 0.22%   |
| 3200x1800 (QHD+)   | 5         | 0.18%   |
| 1680x945           | 4         | 0.15%   |
| 3840x1080          | 3         | 0.11%   |
| 3286x1080          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 3840x1600          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3000x2000          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 2256x1504          | 2         | 0.07%   |
| 1280x768           | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 6400x1600          | 1         | 0.04%   |
| 5120x1600          | 1         | 0.04%   |
| 3300x2200          | 1         | 0.04%   |
| 3200x2000          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1267      | 42.91%  |
| 13      | 338       | 11.45%  |
| 14      | 325       | 11.01%  |
| 17      | 225       | 7.62%   |
| 24      | 126       | 4.27%   |
| 23      | 100       | 3.39%   |
| 12      | 91        | 3.08%   |
| 27      | 88        | 2.98%   |
| Unknown | 63        | 2.13%   |
| 21      | 57        | 1.93%   |
| 11      | 35        | 1.19%   |
| 34      | 29        | 0.98%   |
| 10      | 28        | 0.95%   |
| 19      | 24        | 0.81%   |
| 22      | 23        | 0.78%   |
| 16      | 21        | 0.71%   |
| 31      | 17        | 0.58%   |
| 18      | 17        | 0.58%   |
| 48      | 10        | 0.34%   |
| 25      | 9         | 0.3%    |
| 20      | 9         | 0.3%    |
| 84      | 8         | 0.27%   |
| 40      | 6         | 0.2%    |
| 72      | 5         | 0.17%   |
| 7       | 5         | 0.17%   |
| 32      | 4         | 0.14%   |
| 43      | 3         | 0.1%    |
| 37      | 3         | 0.1%    |
| 65      | 2         | 0.07%   |
| 54      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 26      | 2         | 0.07%   |
| 142     | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 49      | 1         | 0.03%   |
| 46      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |
| 33      | 1         | 0.03%   |
| 29      | 1         | 0.03%   |
| 8       | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1750      | 60.24%  |
| 201-300        | 293       | 10.09%  |
| 501-600        | 289       | 9.95%   |
| 351-400        | 283       | 9.74%   |
| 401-500        | 116       | 3.99%   |
| Unknown        | 63        | 2.17%   |
| 701-800        | 34        | 1.17%   |
| 601-700        | 26        | 0.9%    |
| 1001-1500      | 17        | 0.59%   |
| 1501-2000      | 13        | 0.45%   |
| 801-900        | 10        | 0.34%   |
| 1-100          | 6         | 0.21%   |
| 901-1000       | 3         | 0.1%    |
| More than 2000 | 1         | 0.03%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2052      | 79.47%  |
| 16/10   | 368       | 14.25%  |
| Unknown | 46        | 1.78%   |
| 21/9    | 32        | 1.24%   |
| 3/2     | 29        | 1.12%   |
| 5/4     | 22        | 0.85%   |
| 4/3     | 15        | 0.58%   |
| 0.62    | 8         | 0.31%   |
| 0.67    | 5         | 0.19%   |
| 32/9    | 3         | 0.12%   |
| 6/5     | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1265      | 43.12%  |
| 81-90          | 541       | 18.44%  |
| 201-250        | 231       | 7.87%   |
| 121-130        | 177       | 6.03%   |
| 71-80          | 115       | 3.92%   |
| 61-70          | 90        | 3.07%   |
| 301-350        | 90        | 3.07%   |
| Unknown        | 63        | 2.15%   |
| 251-300        | 62        | 2.11%   |
| 351-500        | 52        | 1.77%   |
| 131-140        | 43        | 1.47%   |
| 151-200        | 40        | 1.36%   |
| 51-60          | 35        | 1.19%   |
| 41-50          | 28        | 0.95%   |
| More than 1000 | 27        | 0.92%   |
| 141-150        | 25        | 0.85%   |
| 91-100         | 16        | 0.55%   |
| 501-1000       | 15        | 0.51%   |
| 111-120        | 12        | 0.41%   |
| 1-40           | 7         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1175      | 40.83%  |
| 101-120       | 837       | 29.08%  |
| 51-100        | 596       | 20.71%  |
| 161-240       | 127       | 4.41%   |
| Unknown       | 63        | 2.19%   |
| More than 240 | 58        | 2.02%   |
| 1-50          | 22        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2065      | 78.76%  |
| 2     | 425       | 16.21%  |
| 3     | 64        | 2.44%   |
| 0     | 58        | 2.21%   |
| 4     | 8         | 0.31%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1491      | 35.51%  |
| Realtek Semiconductor             | 1173      | 27.94%  |
| Qualcomm Atheros                  | 633       | 15.08%  |
| Broadcom                          | 291       | 6.93%   |
| Broadcom Limited                  | 86        | 2.05%   |
| Dell                              | 69        | 1.64%   |
| Marvell Technology Group          | 62        | 1.48%   |
| Huawei Technologies               | 59        | 1.41%   |
| MediaTek                          | 38        | 0.9%    |
| Ralink                            | 32        | 0.76%   |
| Ericsson Business Mobile Networks | 25        | 0.6%    |
| TP-Link                           | 23        | 0.55%   |
| Samsung Electronics               | 22        | 0.52%   |
| Hewlett-Packard                   | 22        | 0.52%   |
| JMicron Technology                | 16        | 0.38%   |
| Xiaomi                            | 15        | 0.36%   |
| Sierra Wireless                   | 15        | 0.36%   |
| Lenovo                            | 12        | 0.29%   |
| Nvidia                            | 11        | 0.26%   |
| Ralink Technology                 | 10        | 0.24%   |
| DisplayLink                       | 10        | 0.24%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.21%   |
| ASIX Electronics                  | 9         | 0.21%   |
| Qualcomm Atheros Communications   | 8         | 0.19%   |
| Fibocom                           | 8         | 0.19%   |
| Qualcomm                          | 6         | 0.14%   |
| Motorola PCS                      | 5         | 0.12%   |
| ASUSTek Computer                  | 5         | 0.12%   |
| VIA Technologies                  | 4         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 3         | 0.07%   |
| NetGear                           | 3         | 0.07%   |
| Attansic Technology               | 3         | 0.07%   |
| Microsoft                         | 2         | 0.05%   |
| HTC (High Tech Computer)          | 2         | 0.05%   |
| Toshiba                           | 1         | 0.02%   |
| Tenda                             | 1         | 0.02%   |
| Sweex                             | 1         | 0.02%   |
| Sigma Designs                     | 1         | 0.02%   |
| Shenzhen Goodix Technology        | 1         | 0.02%   |
| Sagem                             | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 774       | 15.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 218       | 4.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 148       | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 109       | 2.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 109       | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 2.08%   |
| Intel Wireless 8265 / 8275                                              | 105       | 2.06%   |
| Intel Wi-Fi 6 AX200                                                     | 100       | 1.96%   |
| Intel Wireless 7260                                                     | 94        | 1.85%   |
| Intel Wireless 8260                                                     | 80        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 79        | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 76        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 72        | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 70        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 70        | 1.38%   |
| Intel Wi-Fi 6 AX201                                                     | 66        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 65        | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 62        | 1.22%   |
| Intel Wireless 7265                                                     | 60        | 1.18%   |
| Intel Wireless 3160                                                     | 58        | 1.14%   |
| Intel 82567LM Gigabit Network Connection                                | 50        | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 0.94%   |
| Intel Wireless 3165                                                     | 47        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 46        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 45        | 0.88%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                           | 43        | 0.84%   |
| Intel WiFi Link 5100                                                    | 42        | 0.83%   |
| Intel Ethernet Connection I218-LM                                       | 42        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                                | 40        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 38        | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 0.73%   |
| Huawei E353/E3131                                                       | 37        | 0.73%   |
| Intel Ethernet Connection I217-LM                                       | 33        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 33        | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.65%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                   | 31        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1417      | 53.43%  |
| Qualcomm Atheros                  | 528       | 19.91%  |
| Realtek Semiconductor             | 268       | 10.11%  |
| Broadcom                          | 200       | 7.54%   |
| Broadcom Limited                  | 49        | 1.85%   |
| Dell                              | 42        | 1.58%   |
| Ralink                            | 32        | 1.21%   |
| MediaTek                          | 23        | 0.87%   |
| TP-Link                           | 19        | 0.72%   |
| Sierra Wireless                   | 15        | 0.57%   |
| Ralink Technology                 | 10        | 0.38%   |
| Qualcomm Atheros Communications   | 8         | 0.3%    |
| Fibocom                           | 8         | 0.3%    |
| Ericsson Business Mobile Networks | 8         | 0.3%    |
| Hewlett-Packard                   | 6         | 0.23%   |
| ASUSTek Computer                  | 5         | 0.19%   |
| Qualcomm                          | 4         | 0.15%   |
| NetGear                           | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| Tenda                             | 1         | 0.04%   |
| Sweex                             | 1         | 0.04%   |
| Sagem                             | 1         | 0.04%   |
| Linksys                           | 1         | 0.04%   |
| Edimax Technology                 | 1         | 0.04%   |
| Belkin Components                 | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 109       | 4.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 109       | 4.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 3.99%   |
| Intel Wireless 8265 / 8275                                              | 105       | 3.95%   |
| Intel Wi-Fi 6 AX200                                                     | 100       | 3.77%   |
| Intel Wireless 7260                                                     | 94        | 3.54%   |
| Intel Wireless 8260                                                     | 80        | 3.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 79        | 2.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 76        | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 72        | 2.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 70        | 2.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 70        | 2.64%   |
| Intel Wi-Fi 6 AX201                                                     | 66        | 2.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 65        | 2.45%   |
| Intel Wireless 7265                                                     | 60        | 2.26%   |
| Intel Wireless 3160                                                     | 58        | 2.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 1.81%   |
| Intel Wireless 3165                                                     | 47        | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 46        | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 45        | 1.69%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 43        | 1.62%   |
| Intel WiFi Link 5100                                                    | 42        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 38        | 1.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 33        | 1.24%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 1.24%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 1.21%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 1.13%   |
| Intel Centrino Advanced-N 6235                                          | 29        | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 28        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 27        | 1.02%   |
| Intel Centrino Wireless-N 2230                                          | 27        | 1.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 19        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 17        | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1074      | 46.09%  |
| Intel                            | 655       | 28.11%  |
| Qualcomm Atheros                 | 186       | 7.98%   |
| Broadcom                         | 126       | 5.41%   |
| Marvell Technology Group         | 62        | 2.66%   |
| Huawei Technologies              | 42        | 1.8%    |
| Broadcom Limited                 | 38        | 1.63%   |
| Samsung Electronics              | 20        | 0.86%   |
| JMicron Technology               | 16        | 0.69%   |
| Xiaomi                           | 14        | 0.6%    |
| MediaTek                         | 14        | 0.6%    |
| Lenovo                           | 12        | 0.52%   |
| Nvidia                           | 11        | 0.47%   |
| DisplayLink                      | 10        | 0.43%   |
| Silicon Integrated Systems [SiS] | 9         | 0.39%   |
| ASIX Electronics                 | 9         | 0.39%   |
| Motorola PCS                     | 5         | 0.21%   |
| VIA Technologies                 | 4         | 0.17%   |
| TP-Link                          | 4         | 0.17%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| Attansic Technology              | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.09%   |
| Qualcomm                         | 2         | 0.09%   |
| HTC (High Tech Computer)         | 2         | 0.09%   |
| QinHeng Electronics              | 1         | 0.04%   |
| OPPO                             | 1         | 0.04%   |
| NetGear                          | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 774       | 33.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 218       | 9.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 148       | 6.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 2.65%   |
| Intel 82567LM Gigabit Network Connection                          | 50        | 2.13%   |
| Intel Ethernet Connection I218-LM                                 | 42        | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 40        | 1.71%   |
| Huawei E353/E3131                                                 | 37        | 1.58%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 1.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                             | 29        | 1.24%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 26        | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 1.11%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 0.9%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 18        | 0.77%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.68%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 15        | 0.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 14        | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 13        | 0.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.55%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.47%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.47%   |
| Intel 82566MM Gigabit Network Connection                          | 11        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2494      | 51.83%  |
| Ethernet | 2226      | 46.26%  |
| Modem    | 87        | 1.81%   |
| Unknown  | 5         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2045      | 77.26%  |
| Ethernet | 602       | 22.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2085      | 81.86%  |
| 1     | 426       | 16.73%  |
| 0     | 28        | 1.1%    |
| 3     | 8         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2395      | 93.26%  |
| Yes  | 173       | 6.74%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 925       | 47.1%   |
| Qualcomm Atheros Communications | 218       | 11.1%   |
| Broadcom                        | 158       | 8.04%   |
| Realtek Semiconductor           | 130       | 6.62%   |
| IMC Networks                    | 100       | 5.09%   |
| Dell                            | 82        | 4.18%   |
| Foxconn / Hon Hai               | 64        | 3.26%   |
| Hewlett-Packard                 | 59        | 3%      |
| Lite-On Technology              | 56        | 2.85%   |
| ASUSTek Computer                | 27        | 1.37%   |
| Toshiba                         | 24        | 1.22%   |
| Cambridge Silicon Radio         | 24        | 1.22%   |
| Apple                           | 19        | 0.97%   |
| Ralink                          | 17        | 0.87%   |
| Foxconn International           | 15        | 0.76%   |
| Realtek                         | 10        | 0.51%   |
| Chicony Electronics             | 6         | 0.31%   |
| Alps Electric                   | 6         | 0.31%   |
| Taiyo Yuden                     | 5         | 0.25%   |
| Ralink Technology               | 3         | 0.15%   |
| MediaTek                        | 3         | 0.15%   |
| Integrated System Solution      | 3         | 0.15%   |
| Micro Star International        | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| TP-Link                         | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 434       | 22.09%  |
| Intel AX201 Bluetooth                               | 141       | 7.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 128       | 6.51%   |
| Qualcomm Atheros  Bluetooth Device                  | 97        | 4.94%   |
| Intel AX200 Bluetooth                               | 94        | 4.78%   |
| Realtek Bluetooth Radio                             | 80        | 4.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 53        | 2.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 52        | 2.65%   |
| IMC Networks Bluetooth Radio                        | 40        | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 1.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 1.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 29        | 1.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 27        | 1.37%   |
| Dell BCM20702A0 Bluetooth Module                    | 26        | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24        | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 23        | 1.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 1.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 23        | 1.17%   |
| Dell DW375 Bluetooth Module                         | 22        | 1.12%   |
| IMC Networks Bluetooth Device                       | 19        | 0.97%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.87%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.87%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.81%   |
| Lite-On Bluetooth Device                            | 16        | 0.81%   |
| IMC Networks Wireless_Device                        | 16        | 0.81%   |
| Foxconn International BCM43142A0 Bluetooth module   | 15        | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 0.61%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.61%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.56%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 11        | 0.56%   |
| Dell Wireless 370 Bluetooth Mini-card               | 11        | 0.56%   |
| Dell Wireless 360 Bluetooth                         | 11        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 11        | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2121      | 68.33%  |
| AMD                                          | 429       | 13.82%  |
| Nvidia                                       | 381       | 12.27%  |
| C-Media Electronics                          | 17        | 0.55%   |
| Creative Technology                          | 15        | 0.48%   |
| Lenovo                                       | 14        | 0.45%   |
| Realtek Semiconductor                        | 13        | 0.42%   |
| Silicon Integrated Systems [SiS]             | 11        | 0.35%   |
| Plantronics                                  | 11        | 0.35%   |
| Logitech                                     | 11        | 0.35%   |
| GN Netcom                                    | 8         | 0.26%   |
| SteelSeries ApS                              | 6         | 0.19%   |
| VIA Technologies                             | 5         | 0.16%   |
| Texas Instruments                            | 5         | 0.16%   |
| Dell                                         | 5         | 0.16%   |
| Hewlett-Packard                              | 4         | 0.13%   |
| Focusrite-Novation                           | 4         | 0.13%   |
| Samson Technologies                          | 3         | 0.1%    |
| JMTek                                        | 3         | 0.1%    |
| Generalplus Technology                       | 3         | 0.1%    |
| DSEA A/S                                     | 3         | 0.1%    |
| TTGK Technology                              | 2         | 0.06%   |
| Kingston Technology                          | 2         | 0.06%   |
| DCMT Technology                              | 2         | 0.06%   |
| BEHRINGER International                      | 2         | 0.06%   |
| AudioQuest                                   | 2         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| USB MICROPHONE                               | 1         | 0.03%   |
| Turtle Beach                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Silicon Motion                               | 1         | 0.03%   |
| Sennheiser Communications                    | 1         | 0.03%   |
| SAVITECH                                     | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| Native Instruments                           | 1         | 0.03%   |
| MCS                                          | 1         | 0.03%   |
| Mark of the Unicorn                          | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |
| Jieli Technology                             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 253       | 6.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 242       | 6.53%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 218       | 5.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 174       | 4.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 163       | 4.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 132       | 3.56%   |
| Intel 8 Series HD Audio Controller                                                                | 122       | 3.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 120       | 3.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 118       | 3.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 108       | 2.92%   |
| Intel Broadwell-U Audio Controller                                                                | 99        | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 99        | 2.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 98        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 97        | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 87        | 2.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 84        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 77        | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 73        | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 72        | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 69        | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 67        | 1.81%   |
| Intel CM238 HD Audio Controller                                                                   | 55        | 1.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 53        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 52        | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 49        | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 45        | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 41        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 39        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 35        | 0.94%   |
| AMD Wrestler HDMI Audio                                                                           | 28        | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 28        | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 24        | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 24        | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 23        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 20        | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 20        | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 20        | 0.54%   |
| AMD Trinity HDMI Audio Controller                                                                 | 19        | 0.51%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 18        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 551       | 27.96%  |
| SK hynix                     | 414       | 21%     |
| Micron Technology            | 212       | 10.76%  |
| Kingston                     | 209       | 10.6%   |
| Unknown                      | 150       | 7.61%   |
| GOODRAM                      | 95        | 4.82%   |
| Crucial                      | 80        | 4.06%   |
| Ramaxel Technology           | 47        | 2.38%   |
| A-DATA Technology            | 45        | 2.28%   |
| Nanya Technology             | 36        | 1.83%   |
| Elpida                       | 32        | 1.62%   |
| Patriot                      | 16        | 0.81%   |
| Unknown                      | 13        | 0.66%   |
| Qimonda                      | 10        | 0.51%   |
| Wilk                         | 9         | 0.46%   |
| Unknown (ABCD)               | 7         | 0.36%   |
| Corsair                      | 7         | 0.36%   |
| ASint Technology             | 7         | 0.36%   |
| G.Skill                      | 5         | 0.25%   |
| Unifosa                      | 3         | 0.15%   |
| Apacer                       | 3         | 0.15%   |
| 48spaces                     | 3         | 0.15%   |
| Toshiba                      | 2         | 0.1%    |
| SHARETRONIC                  | 2         | 0.1%    |
| Patriot Memory (PDP Systems) | 2         | 0.1%    |
| Unknown (8A02)               | 1         | 0.05%   |
| Unknown (768A)               | 1         | 0.05%   |
| Transcend                    | 1         | 0.05%   |
| Swissbit                     | 1         | 0.05%   |
| Smart                        | 1         | 0.05%   |
| PNY                          | 1         | 0.05%   |
| Goldkey                      | 1         | 0.05%   |
| fef5                         | 1         | 0.05%   |
| ChangXin Memory              | 1         | 0.05%   |
| 430112204340C940             | 1         | 0.05%   |
| 430112174392063E             | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s      | 36        | 1.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 28        | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 28        | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 26        | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 24        | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 23        | 1.09%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 22        | 1.04%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s    | 22        | 1.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 21        | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 21        | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 20        | 0.95%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 20        | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 20        | 0.95%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s      | 18        | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 18        | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 17        | 0.81%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s     | 17        | 0.81%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s      | 16        | 0.76%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 15        | 0.71%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s    | 15        | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 14        | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 13        | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 13        | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 13        | 0.62%   |
| Unknown                                                    | 13        | 0.62%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 12        | 0.57%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 12        | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s   | 12        | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 12        | 0.57%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s    | 12        | 0.57%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s | 12        | 0.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 11        | 0.52%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s   | 11        | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 11        | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s     | 10        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 10        | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s      | 10        | 0.47%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s     | 10        | 0.47%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 10        | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 9         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 640       | 39.56%  |
| DDR4    | 632       | 39.06%  |
| DDR2    | 152       | 9.39%   |
| SDRAM   | 71        | 4.39%   |
| LPDDR4  | 49        | 3.03%   |
| LPDDR3  | 35        | 2.16%   |
| Unknown | 11        | 0.68%   |
| DDR     | 10        | 0.62%   |
| DDR5    | 9         | 0.56%   |
| DRAM    | 5         | 0.31%   |
| LPDDR5  | 4         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1484      | 93.39%  |
| Row Of Chips | 80        | 5.03%   |
| Chip         | 11        | 0.69%   |
| DIMM         | 7         | 0.44%   |
| Unknown      | 7         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 549       | 30.98%  |
| 8192    | 529       | 29.85%  |
| 2048    | 289       | 16.31%  |
| 16384   | 258       | 14.56%  |
| 1024    | 103       | 5.81%   |
| 32768   | 29        | 1.64%   |
| 512     | 9         | 0.51%   |
| Unknown | 4         | 0.23%   |
| 1536    | 1         | 0.06%   |
| 256     | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 458       | 25.85%  |
| 2667    | 320       | 18.06%  |
| 3200    | 235       | 13.26%  |
| 1334    | 115       | 6.49%   |
| 2400    | 97        | 5.47%   |
| 2133    | 78        | 4.4%    |
| 667     | 76        | 4.29%   |
| 1333    | 69        | 3.89%   |
| Unknown | 52        | 2.93%   |
| 4199    | 40        | 2.26%   |
| 1067    | 36        | 2.03%   |
| 800     | 29        | 1.64%   |
| 975     | 25        | 1.41%   |
| 2048    | 24        | 1.35%   |
| 533     | 22        | 1.24%   |
| 4267    | 15        | 0.85%   |
| 1867    | 14        | 0.79%   |
| 3266    | 12        | 0.68%   |
| 8400    | 10        | 0.56%   |
| 4800    | 10        | 0.56%   |
| 1066    | 8         | 0.45%   |
| 4266    | 5         | 0.28%   |
| 3733    | 5         | 0.28%   |
| 6400    | 4         | 0.23%   |
| 400     | 4         | 0.23%   |
| 333     | 4         | 0.23%   |
| 2933    | 1         | 0.06%   |
| 2134    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 1639    | 1         | 0.06%   |
| 933     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 45.45%  |
| Samsung Electronics | 4         | 18.18%  |
| Canon               | 3         | 13.64%  |
| Seiko Epson         | 2         | 9.09%   |
| Zebra               | 1         | 4.55%   |
| Xerox               | 1         | 4.55%   |
| Brother Industries  | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Deskjet F2280 series                 | 2         | 9.09%   |
| Zebra ZTC GX420t                        | 1         | 4.55%   |
| Xerox Phaser 6000B                      | 1         | 4.55%   |
| Seiko Epson L396 Series                 | 1         | 4.55%   |
| Seiko Epson AL-M310DN                   | 1         | 4.55%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.55%   |
| Samsung SCX-6545 Series                 | 1         | 4.55%   |
| Samsung SCX-3400 Series                 | 1         | 4.55%   |
| Samsung M2020 Series                    | 1         | 4.55%   |
| HP LaserJet P1102                       | 1         | 4.55%   |
| HP LaserJet P1005                       | 1         | 4.55%   |
| HP LaserJet 1020                        | 1         | 4.55%   |
| HP LaserJet 1018                        | 1         | 4.55%   |
| HP Ink Tank Wireless 410 series         | 1         | 4.55%   |
| HP Deskjet Ink Advant K209a-z           | 1         | 4.55%   |
| HP Deskjet D1500 series                 | 1         | 4.55%   |
| HP Deskjet 2540 series                  | 1         | 4.55%   |
| Canon PIXMA MG3000 series               | 1         | 4.55%   |
| Canon MG5600 series                     | 1         | 4.55%   |
| Canon LiDE 400                          | 1         | 4.55%   |
| Brother DCP-1610W                       | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 2         | 50%     |
| Plustek                | 1         | 25%     |
| Microtek International | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner         | 1         | 25%     |
| Microtek International USB1200 Scanner | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20     | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30          | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 525       | 24.08%  |
| IMC Networks                           | 237       | 10.87%  |
| Microdia                               | 228       | 10.46%  |
| Realtek Semiconductor                  | 201       | 9.22%   |
| Acer                                   | 173       | 7.94%   |
| Sunplus Innovation Technology          | 121       | 5.55%   |
| Quanta                                 | 104       | 4.77%   |
| Suyin                                  | 101       | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 77        | 3.53%   |
| Syntek                                 | 67        | 3.07%   |
| Silicon Motion                         | 51        | 2.34%   |
| Lite-On Technology                     | 49        | 2.25%   |
| Ricoh                                  | 28        | 1.28%   |
| Lenovo                                 | 24        | 1.1%    |
| Logitech                               | 23        | 1.06%   |
| Alcor Micro                            | 21        | 0.96%   |
| Luxvisions Innotech Limited            | 19        | 0.87%   |
| Apple                                  | 19        | 0.87%   |
| Z-Star Microelectronics                | 14        | 0.64%   |
| DigiTech                               | 11        | 0.5%    |
| Creative Technology                    | 10        | 0.46%   |
| Primax Electronics                     | 9         | 0.41%   |
| Intel                                  | 8         | 0.37%   |
| ALi                                    | 8         | 0.37%   |
| Samsung Electronics                    | 7         | 0.32%   |
| Sonix Technology                       | 5         | 0.23%   |
| Generalplus Technology                 | 5         | 0.23%   |
| Microsoft                              | 4         | 0.18%   |
| Importek                               | 4         | 0.18%   |
| Bison Electronics                      | 4         | 0.18%   |
| Sunplus Technology                     | 2         | 0.09%   |
| OmniVision Technologies                | 2         | 0.09%   |
| MacroSilicon                           | 2         | 0.09%   |
| Foxconn / Hon Hai                      | 2         | 0.09%   |
| DLEQNA19IFK6G2                         | 2         | 0.09%   |
| Cubeternet                             | 2         | 0.09%   |
| WaveRider Communications               | 1         | 0.05%   |
| Trust                                  | 1         | 0.05%   |
| Nokia Mobile Phones                    | 1         | 0.05%   |
| Nebraska Furniture Mart                | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 104       | 4.76%   |
| Microdia Integrated_Webcam_HD            | 79        | 3.61%   |
| Realtek Integrated_Webcam_HD             | 67        | 3.06%   |
| IMC Networks Integrated Camera           | 63        | 2.88%   |
| IMC Networks USB2.0 HD UVC WebCam        | 57        | 2.61%   |
| Sunplus Integrated_Webcam_HD             | 52        | 2.38%   |
| Chicony Lenovo EasyCamera                | 41        | 1.88%   |
| Acer Lenovo EasyCamera                   | 41        | 1.88%   |
| Microdia Integrated Webcam               | 37        | 1.69%   |
| Chicony HD WebCam                        | 37        | 1.69%   |
| Suyin Integrated_Webcam_HD               | 35        | 1.6%    |
| Acer Integrated Camera                   | 34        | 1.56%   |
| Syntek Lenovo EasyCamera                 | 29        | 1.33%   |
| Realtek Lenovo EasyCamera                | 25        | 1.14%   |
| Syntek Integrated Camera                 | 21        | 0.96%   |
| Lite-On Integrated Camera                | 21        | 0.96%   |
| Chicony USB2.0 HD UVC WebCam             | 21        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 20        | 0.91%   |
| Acer Lenovo Integrated Webcam            | 20        | 0.91%   |
| Quanta HP TrueVision HD Camera           | 19        | 0.87%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.82%   |
| Realtek USB Camera                       | 18        | 0.82%   |
| Quanta HD User Facing                    | 18        | 0.82%   |
| Chicony HP HD Camera                     | 18        | 0.82%   |
| Realtek Integrated Webcam HD             | 17        | 0.78%   |
| IMC Networks Integrated Webcam           | 17        | 0.78%   |
| Microdia Laptop_Integrated_Webcam_HD     | 16        | 0.73%   |
| Chicony USB 2.0 Camera                   | 16        | 0.73%   |
| Acer SunplusIT Integrated Camera         | 16        | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam            | 15        | 0.69%   |
| Realtek Integrated Webcam                | 14        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)  | 14        | 0.64%   |
| Lite-On HP HD Camera                     | 13        | 0.59%   |
| Chicony VGA Webcam                       | 13        | 0.59%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 13        | 0.59%   |
| Chicony HP HD Webcam [Fixed]             | 12        | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 11        | 0.5%    |
| Sunplus HD WebCam                        | 11        | 0.5%    |
| Silicon Motion WebCam SC-13HDL11939N     | 11        | 0.5%    |
| Quanta HP Webcam                         | 11        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 176       | 38.34%  |
| Synaptics                  | 99        | 21.57%  |
| Shenzhen Goodix Technology | 55        | 11.98%  |
| AuthenTec                  | 53        | 11.55%  |
| Upek                       | 35        | 7.63%   |
| LighTuning Technology      | 15        | 3.27%   |
| Elan Microelectronics      | 14        | 3.05%   |
| STMicroelectronics         | 12        | 2.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 8.28%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 8.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 34        | 7.41%   |
| Shenzhen Goodix  FingerPrint Device                                        | 30        | 6.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 5.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 4.79%   |
| AuthenTec AES2810                                                          | 22        | 4.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 4.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 3.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 3.7%    |
| Unknown                                                                    | 15        | 3.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 3.05%   |
| Validity Sensors VFS491                                                    | 12        | 2.61%   |
| STMicroelectronics Fingerprint Reader                                      | 12        | 2.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.4%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 2.4%    |
| Elan ELAN:Fingerprint                                                      | 10        | 2.18%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.96%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.74%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 1.74%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.31%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.31%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.31%   |
| AuthenTec AES1600                                                          | 6         | 1.31%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 1.09%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.87%   |
| Synaptics  WBDI                                                            | 4         | 0.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.87%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.87%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.87%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.87%   |
| Synaptics WBDI Device                                                      | 3         | 0.65%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.44%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 201       | 56.3%   |
| Alcor Micro               | 72        | 20.17%  |
| O2 Micro                  | 40        | 11.2%   |
| Lenovo                    | 20        | 5.6%    |
| Upek                      | 19        | 5.32%   |
| Gemalto (was Gemplus)     | 4         | 1.12%   |
| Aladdin Knowledge Systems | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 70        | 19.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 65        | 18.21%  |
| Broadcom 5880                                                                | 51        | 14.29%  |
| Broadcom 58200                                                               | 49        | 13.73%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 9.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 33        | 9.24%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.6%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 5.32%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.96%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.84%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.28%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.28%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.28%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.28%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1507      | 57.7%   |
| 1     | 842       | 32.24%  |
| 2     | 224       | 8.58%   |
| 3     | 31        | 1.19%   |
| 4     | 3         | 0.11%   |
| 7     | 2         | 0.08%   |
| 5     | 2         | 0.08%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 454       | 33.16%  |
| Chipcard                 | 324       | 23.67%  |
| Graphics card            | 279       | 20.38%  |
| Net/wireless             | 86        | 6.28%   |
| Storage                  | 46        | 3.36%   |
| Multimedia controller    | 44        | 3.21%   |
| Bluetooth                | 37        | 2.7%    |
| Camera                   | 24        | 1.75%   |
| Communication controller | 23        | 1.68%   |
| Card reader              | 16        | 1.17%   |
| Sound                    | 10        | 0.73%   |
| Modem                    | 7         | 0.51%   |
| Firewire controller      | 5         | 0.37%   |
| Net/ethernet             | 4         | 0.29%   |
| Flash memory             | 3         | 0.22%   |
| Dvb card                 | 3         | 0.22%   |
| Wireless                 | 1         | 0.07%   |
| Tv card                  | 1         | 0.07%   |
| Storage/raid             | 1         | 0.07%   |
| Network                  | 1         | 0.07%   |

