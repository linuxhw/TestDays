Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

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

Total: 614

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0T0MHW A03                  | Desktop     | [eb50cfecc0](https://linux-hardware.org/?probe=eb50cfecc0) | Dec 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [614c58469c](https://linux-hardware.org/?probe=614c58469c) | Dec 01, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [7443fb3ad9](https://linux-hardware.org/?probe=7443fb3ad9) | Nov 13, 2024 |
| Positivo      | C4128A-14                   | Notebook    | [50f4d77aed](https://linux-hardware.org/?probe=50f4d77aed) | Nov 10, 2024 |
| Positivo      | C4128A-14                   | Notebook    | [49eddb2601](https://linux-hardware.org/?probe=49eddb2601) | Nov 10, 2024 |
| Dell          | Latitude 3140               | Notebook    | [c6b81cfb77](https://linux-hardware.org/?probe=c6b81cfb77) | Oct 31, 2024 |
| MSI           | Z97M GAMING                 | Desktop     | [ededbd4d75](https://linux-hardware.org/?probe=ededbd4d75) | Oct 14, 2024 |
| Toshiba       | Satellite L755D             | Notebook    | [ca7930fdb0](https://linux-hardware.org/?probe=ca7930fdb0) | Sep 26, 2024 |
| ASRock        | H170M Pro4                  | Desktop     | [5253f50483](https://linux-hardware.org/?probe=5253f50483) | Sep 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [d156c6ec4c](https://linux-hardware.org/?probe=d156c6ec4c) | Sep 10, 2024 |
| Dell          | Latitude 7480               | Notebook    | [d190ee0f7c](https://linux-hardware.org/?probe=d190ee0f7c) | Sep 09, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [3f40abc951](https://linux-hardware.org/?probe=3f40abc951) | Aug 25, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [cb2f55c33d](https://linux-hardware.org/?probe=cb2f55c33d) | Aug 18, 2024 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1dce3c5ac9](https://linux-hardware.org/?probe=1dce3c5ac9) | Apr 30, 2024 |
| HP            | 2B47                        | Desktop     | [3a165a34a7](https://linux-hardware.org/?probe=3a165a34a7) | Apr 27, 2024 |
| Dell          | 0773VG A02                  | Desktop     | [2db2c160ae](https://linux-hardware.org/?probe=2db2c160ae) | Apr 03, 2024 |
| HP            | 2AF7                        | Desktop     | [a9fd9938cd](https://linux-hardware.org/?probe=a9fd9938cd) | Apr 01, 2024 |
| Acer          | Aspire XC-603               | Desktop     | [68c8512ceb](https://linux-hardware.org/?probe=68c8512ceb) | Mar 09, 2024 |
| HP            | 89E9 0100                   | All in one  | [dedbe73fee](https://linux-hardware.org/?probe=dedbe73fee) | Mar 08, 2024 |
| MSI           | 970 GAMING                  | Desktop     | [940cdd271c](https://linux-hardware.org/?probe=940cdd271c) | Mar 01, 2024 |
| HP            | 89E9 0100                   | All in one  | [7c86412368](https://linux-hardware.org/?probe=7c86412368) | Feb 23, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [e2286ae69c](https://linux-hardware.org/?probe=e2286ae69c) | Feb 22, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [caa89e80d0](https://linux-hardware.org/?probe=caa89e80d0) | Feb 21, 2024 |
| ASUSTek       | V161GA                      | All in one  | [d1891af126](https://linux-hardware.org/?probe=d1891af126) | Feb 12, 2024 |
| ASUSTek       | P5K                         | Desktop     | [a93b9e89e3](https://linux-hardware.org/?probe=a93b9e89e3) | Feb 08, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [76604f435d](https://linux-hardware.org/?probe=76604f435d) | Feb 07, 2024 |
| Dell          | 0J7MNP A00                  | All in one  | [148caf0684](https://linux-hardware.org/?probe=148caf0684) | Feb 04, 2024 |
| Dell          | 0J7MNP A00                  | All in one  | [6a65fd96cc](https://linux-hardware.org/?probe=6a65fd96cc) | Feb 03, 2024 |
| Dell          | 0J7MNP A00                  | All in one  | [7a08cc9321](https://linux-hardware.org/?probe=7a08cc9321) | Feb 02, 2024 |
| Dell          | 0J7MNP A00                  | All in one  | [3ec79f8a00](https://linux-hardware.org/?probe=3ec79f8a00) | Feb 02, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [f3cb8642e0](https://linux-hardware.org/?probe=f3cb8642e0) | Feb 01, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c4221423f9](https://linux-hardware.org/?probe=c4221423f9) | Jan 31, 2024 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [916a39975c](https://linux-hardware.org/?probe=916a39975c) | Jan 31, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [e179099ff6](https://linux-hardware.org/?probe=e179099ff6) | Jan 29, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [0499bd177a](https://linux-hardware.org/?probe=0499bd177a) | Jan 27, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [ab1d389327](https://linux-hardware.org/?probe=ab1d389327) | Jan 27, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2ca75c65d6](https://linux-hardware.org/?probe=2ca75c65d6) | Jan 26, 2024 |
| Acer          | TravelMate B115-M           | Notebook    | [e91da1c312](https://linux-hardware.org/?probe=e91da1c312) | Jan 22, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [3055120492](https://linux-hardware.org/?probe=3055120492) | Jan 22, 2024 |
| Google        | Garg                        | Notebook    | [b306e0b88b](https://linux-hardware.org/?probe=b306e0b88b) | Jan 22, 2024 |
| MSI           | B85M-E45                    | Desktop     | [641e17fe01](https://linux-hardware.org/?probe=641e17fe01) | Jan 19, 2024 |
| MSI           | B85M-E45                    | Desktop     | [32fd96fdd0](https://linux-hardware.org/?probe=32fd96fdd0) | Jan 19, 2024 |
| MSI           | G41M-S01                    | Desktop     | [373595b73a](https://linux-hardware.org/?probe=373595b73a) | Jan 16, 2024 |
| Dell          | Latitude E5520              | Notebook    | [9700d44fe1](https://linux-hardware.org/?probe=9700d44fe1) | Jan 16, 2024 |
| Samsung       | 750XDA                      | Notebook    | [95d390939e](https://linux-hardware.org/?probe=95d390939e) | Jan 14, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [0afe07637c](https://linux-hardware.org/?probe=0afe07637c) | Jan 11, 2024 |
| MSI           | B85M-G43                    | Desktop     | [8982801bbb](https://linux-hardware.org/?probe=8982801bbb) | Jan 10, 2024 |
| Fujitsu       | E8420                       | Notebook    | [aeafbc2899](https://linux-hardware.org/?probe=aeafbc2899) | Jan 10, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7e0a72f2d3](https://linux-hardware.org/?probe=7e0a72f2d3) | Jan 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b8212584f9](https://linux-hardware.org/?probe=b8212584f9) | Jan 10, 2024 |
| Microsoft     | Surface Laptop 3            | Tablet      | [1970b79718](https://linux-hardware.org/?probe=1970b79718) | Jan 09, 2024 |
| HP            | 89E9 0100                   | All in one  | [0bd1e5bd43](https://linux-hardware.org/?probe=0bd1e5bd43) | Jan 08, 2024 |
| Dell          | Inspiron 5737               | Notebook    | [1700f72b17](https://linux-hardware.org/?probe=1700f72b17) | Jan 08, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [60be673722](https://linux-hardware.org/?probe=60be673722) | Jan 08, 2024 |
| Acer          | Aspire V3-471G              | Notebook    | [d96fe50b0e](https://linux-hardware.org/?probe=d96fe50b0e) | Jan 07, 2024 |
| Dell          | Inspiron 5493               | Notebook    | [eb9b8edc2c](https://linux-hardware.org/?probe=eb9b8edc2c) | Jan 07, 2024 |
| Acer          | Extensa 215-54G             | Notebook    | [3c25dd10dd](https://linux-hardware.org/?probe=3c25dd10dd) | Jan 06, 2024 |
| Acer          | Extensa 215-54G             | Notebook    | [031b668bcb](https://linux-hardware.org/?probe=031b668bcb) | Jan 06, 2024 |
| Fujitsu       | E8420                       | Notebook    | [8e0c9a6fa7](https://linux-hardware.org/?probe=8e0c9a6fa7) | Jan 06, 2024 |
| HP            | Elite x2 1012 G1            | Notebook    | [f7f2644543](https://linux-hardware.org/?probe=f7f2644543) | Jan 06, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [4ec5e534a6](https://linux-hardware.org/?probe=4ec5e534a6) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [54f70ad2a1](https://linux-hardware.org/?probe=54f70ad2a1) | Jan 05, 2024 |
| HP            | 89E9 0100                   | All in one  | [2b8684c45d](https://linux-hardware.org/?probe=2b8684c45d) | Jan 04, 2024 |
| MECHREVO      | S2 Air Series PF4NU1F       | Notebook    | [08703baf6e](https://linux-hardware.org/?probe=08703baf6e) | Jan 03, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [88bc9fe11f](https://linux-hardware.org/?probe=88bc9fe11f) | Jan 02, 2024 |
| HP            | 8710                        | Mini pc     | [be32ecba69](https://linux-hardware.org/?probe=be32ecba69) | Jan 02, 2024 |
| Dell          | Latitude E5470              | Notebook    | [fdc804210f](https://linux-hardware.org/?probe=fdc804210f) | Jan 01, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | Notebook    | [2872198e9f](https://linux-hardware.org/?probe=2872198e9f) | Jan 01, 2024 |
| Win Elemen... | M9                          | Desktop     | [33b3133a1c](https://linux-hardware.org/?probe=33b3133a1c) | Jan 01, 2024 |
| Win Elemen... | M9                          | Desktop     | [93f17e23c2](https://linux-hardware.org/?probe=93f17e23c2) | Jan 01, 2024 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [19be3bdc5b](https://linux-hardware.org/?probe=19be3bdc5b) | Dec 31, 2023 |
| MSI           | B85M-G43                    | Desktop     | [16b0ff5ec7](https://linux-hardware.org/?probe=16b0ff5ec7) | Dec 30, 2023 |
| HP            | 89E9 0100                   | All in one  | [e05f44b587](https://linux-hardware.org/?probe=e05f44b587) | Dec 30, 2023 |
| HP            | Notebook                    | Notebook    | [c5f68d3103](https://linux-hardware.org/?probe=c5f68d3103) | Dec 30, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8e46844acc](https://linux-hardware.org/?probe=8e46844acc) | Dec 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [493e09fce5](https://linux-hardware.org/?probe=493e09fce5) | Dec 28, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7d74ad36fd](https://linux-hardware.org/?probe=7d74ad36fd) | Dec 28, 2023 |
| Google        | Nami                        | Notebook    | [3d7f7ba09c](https://linux-hardware.org/?probe=3d7f7ba09c) | Dec 28, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1d2d72f2a2](https://linux-hardware.org/?probe=1d2d72f2a2) | Dec 27, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | Notebook    | [b602153aeb](https://linux-hardware.org/?probe=b602153aeb) | Dec 26, 2023 |
| Dell          | Latitude 5400               | Notebook    | [35adbae547](https://linux-hardware.org/?probe=35adbae547) | Dec 26, 2023 |
| ASRock        | Q1900M                      | Desktop     | [5a28e8874e](https://linux-hardware.org/?probe=5a28e8874e) | Dec 26, 2023 |
| HP            | 89E9 0100                   | All in one  | [43b8cda019](https://linux-hardware.org/?probe=43b8cda019) | Dec 26, 2023 |
| Dell          | Latitude 5400               | Notebook    | [7ddd773af2](https://linux-hardware.org/?probe=7ddd773af2) | Dec 25, 2023 |
| MECHREVO      | S2 Air Series PF4NU1F       | Notebook    | [edb1d110e2](https://linux-hardware.org/?probe=edb1d110e2) | Dec 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f47caaa0e1](https://linux-hardware.org/?probe=f47caaa0e1) | Dec 25, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [31291c7bc9](https://linux-hardware.org/?probe=31291c7bc9) | Dec 24, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [4f8558438f](https://linux-hardware.org/?probe=4f8558438f) | Dec 23, 2023 |
| Dell          | Latitude 5440               | Notebook    | [d7462b97ac](https://linux-hardware.org/?probe=d7462b97ac) | Dec 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [4e773891cd](https://linux-hardware.org/?probe=4e773891cd) | Dec 21, 2023 |
| Dell          | Latitude E5540              | Notebook    | [af5e30a046](https://linux-hardware.org/?probe=af5e30a046) | Dec 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [914826699f](https://linux-hardware.org/?probe=914826699f) | Dec 20, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [eac468f369](https://linux-hardware.org/?probe=eac468f369) | Dec 20, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [12f149be7f](https://linux-hardware.org/?probe=12f149be7f) | Dec 18, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [7bb3bd0328](https://linux-hardware.org/?probe=7bb3bd0328) | Dec 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cd04b1b3df](https://linux-hardware.org/?probe=cd04b1b3df) | Dec 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9986fed725](https://linux-hardware.org/?probe=9986fed725) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4a964fa296](https://linux-hardware.org/?probe=4a964fa296) | Dec 15, 2023 |
| HP            | 89E9 0100                   | All in one  | [2c48bcaae8](https://linux-hardware.org/?probe=2c48bcaae8) | Dec 15, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [f942d9c43e](https://linux-hardware.org/?probe=f942d9c43e) | Dec 13, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f6f31f5ed6](https://linux-hardware.org/?probe=f6f31f5ed6) | Dec 13, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [069de62879](https://linux-hardware.org/?probe=069de62879) | Dec 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1c31a8cd6f](https://linux-hardware.org/?probe=1c31a8cd6f) | Dec 12, 2023 |
| MECHREVO      | Kuangshi16Pro Series GM6... | Notebook    | [e551d0d31e](https://linux-hardware.org/?probe=e551d0d31e) | Dec 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2abe635055](https://linux-hardware.org/?probe=2abe635055) | Dec 10, 2023 |
| Huanan        | X99-F8                      | Desktop     | [8c534cb0a4](https://linux-hardware.org/?probe=8c534cb0a4) | Dec 09, 2023 |
| Huanan        | X99-F8                      | Desktop     | [6d1bdd1b81](https://linux-hardware.org/?probe=6d1bdd1b81) | Dec 09, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [87ef304fb0](https://linux-hardware.org/?probe=87ef304fb0) | Dec 07, 2023 |
| Alienware     | M17xR3                      | Notebook    | [0522045eab](https://linux-hardware.org/?probe=0522045eab) | Dec 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d7e2b60dc8](https://linux-hardware.org/?probe=d7e2b60dc8) | Dec 06, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [31de30cc0e](https://linux-hardware.org/?probe=31de30cc0e) | Dec 06, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [3a19753377](https://linux-hardware.org/?probe=3a19753377) | Dec 05, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [468a017a07](https://linux-hardware.org/?probe=468a017a07) | Dec 04, 2023 |
| Panasonic     | CF-52SL3DD1M                | Notebook    | [efdec9a15c](https://linux-hardware.org/?probe=efdec9a15c) | Dec 04, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [4d788fb96c](https://linux-hardware.org/?probe=4d788fb96c) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f3d0befef1](https://linux-hardware.org/?probe=f3d0befef1) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5dcf20cb88](https://linux-hardware.org/?probe=5dcf20cb88) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c6454cb058](https://linux-hardware.org/?probe=c6454cb058) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2f07094763](https://linux-hardware.org/?probe=2f07094763) | Dec 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [29d9e5aa67](https://linux-hardware.org/?probe=29d9e5aa67) | Dec 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [d45f900b4c](https://linux-hardware.org/?probe=d45f900b4c) | Dec 03, 2023 |
| Dell          | 03KPVW A00                  | All in one  | [86992c1526](https://linux-hardware.org/?probe=86992c1526) | Dec 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [9acb0576fd](https://linux-hardware.org/?probe=9acb0576fd) | Nov 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [3ed69dec15](https://linux-hardware.org/?probe=3ed69dec15) | Nov 30, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [6439b70362](https://linux-hardware.org/?probe=6439b70362) | Nov 28, 2023 |
| MSI           | Z97-GD65 GAMING             | Desktop     | [86230be0a7](https://linux-hardware.org/?probe=86230be0a7) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [e3473e64c5](https://linux-hardware.org/?probe=e3473e64c5) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [c9b79740d2](https://linux-hardware.org/?probe=c9b79740d2) | Nov 27, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [bfb937c0c0](https://linux-hardware.org/?probe=bfb937c0c0) | Nov 26, 2023 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | Notebook    | [7eed706de5](https://linux-hardware.org/?probe=7eed706de5) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [791f093fc3](https://linux-hardware.org/?probe=791f093fc3) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [a18b2f2c3e](https://linux-hardware.org/?probe=a18b2f2c3e) | Nov 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [b9b8e57c7c](https://linux-hardware.org/?probe=b9b8e57c7c) | Nov 25, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [83c2b87d3c](https://linux-hardware.org/?probe=83c2b87d3c) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | Notebook    | [0a24a8ef6d](https://linux-hardware.org/?probe=0a24a8ef6d) | Nov 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [cc934b68d9](https://linux-hardware.org/?probe=cc934b68d9) | Nov 22, 2023 |
| Toshiba       | Satellite P50-B-11V         | Notebook    | [448150c108](https://linux-hardware.org/?probe=448150c108) | Nov 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [56c19073cb](https://linux-hardware.org/?probe=56c19073cb) | Nov 20, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b11ea54568](https://linux-hardware.org/?probe=b11ea54568) | Nov 20, 2023 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [fff3e03a74](https://linux-hardware.org/?probe=fff3e03a74) | Nov 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [49139037ec](https://linux-hardware.org/?probe=49139037ec) | Nov 20, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [c97b664653](https://linux-hardware.org/?probe=c97b664653) | Nov 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [43a2a45d3f](https://linux-hardware.org/?probe=43a2a45d3f) | Nov 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [fef63b579f](https://linux-hardware.org/?probe=fef63b579f) | Nov 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [ebb7ed0d8c](https://linux-hardware.org/?probe=ebb7ed0d8c) | Nov 16, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [39c7028c1e](https://linux-hardware.org/?probe=39c7028c1e) | Nov 15, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [41e315a3e5](https://linux-hardware.org/?probe=41e315a3e5) | Nov 14, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [5a7374e5b0](https://linux-hardware.org/?probe=5a7374e5b0) | Nov 13, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [6525548dab](https://linux-hardware.org/?probe=6525548dab) | Nov 12, 2023 |
| Intel         | X99                         | Desktop     | [5c6225ea2d](https://linux-hardware.org/?probe=5c6225ea2d) | Nov 11, 2023 |
| Lenovo        | ThinkPad X395 20NLS0J400    | Notebook    | [f5d1d61be6](https://linux-hardware.org/?probe=f5d1d61be6) | Nov 10, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [8cc0e1c14d](https://linux-hardware.org/?probe=8cc0e1c14d) | Nov 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [919942c11f](https://linux-hardware.org/?probe=919942c11f) | Nov 08, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [98bc0094ec](https://linux-hardware.org/?probe=98bc0094ec) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | Notebook    | [050ecd56d1](https://linux-hardware.org/?probe=050ecd56d1) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c64e4d8a0b](https://linux-hardware.org/?probe=c64e4d8a0b) | Nov 05, 2023 |
| Lenovo        | XiaoXinPro 14 IRH8 83AL     | Notebook    | [de5461c78b](https://linux-hardware.org/?probe=de5461c78b) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [72b02cceec](https://linux-hardware.org/?probe=72b02cceec) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [8a35411be4](https://linux-hardware.org/?probe=8a35411be4) | Nov 05, 2023 |
| HP            | Pavilion dv6                | Notebook    | [60ff7a74af](https://linux-hardware.org/?probe=60ff7a74af) | Nov 05, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [95f3002643](https://linux-hardware.org/?probe=95f3002643) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6ea9e5b141](https://linux-hardware.org/?probe=6ea9e5b141) | Nov 04, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [c8521456ad](https://linux-hardware.org/?probe=c8521456ad) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [1da3521ff2](https://linux-hardware.org/?probe=1da3521ff2) | Nov 04, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [07e66cf3c5](https://linux-hardware.org/?probe=07e66cf3c5) | Nov 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [082adbf921](https://linux-hardware.org/?probe=082adbf921) | Nov 04, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [3ddccb994b](https://linux-hardware.org/?probe=3ddccb994b) | Nov 03, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d6749e3f8b](https://linux-hardware.org/?probe=d6749e3f8b) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [e5158e3f58](https://linux-hardware.org/?probe=e5158e3f58) | Oct 31, 2023 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [90b5515582](https://linux-hardware.org/?probe=90b5515582) | Oct 31, 2023 |
| Dell          | 0R849J A01                  | Desktop     | [3891d2fd80](https://linux-hardware.org/?probe=3891d2fd80) | Oct 31, 2023 |
| Huanan        | X99-F8                      | Desktop     | [0bcf4adaf6](https://linux-hardware.org/?probe=0bcf4adaf6) | Oct 31, 2023 |
| MSI           | Thin GF63 12VE              | Notebook    | [1776ca1088](https://linux-hardware.org/?probe=1776ca1088) | Oct 30, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [bf9ff8ba5b](https://linux-hardware.org/?probe=bf9ff8ba5b) | Oct 29, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [26cdf6bb35](https://linux-hardware.org/?probe=26cdf6bb35) | Oct 29, 2023 |
| Gigabyte      | B760 AORUS ELITE AX DDR4    | Desktop     | [53ff42384c](https://linux-hardware.org/?probe=53ff42384c) | Oct 29, 2023 |
| HP            | Presario CQ57               | Notebook    | [f35a975672](https://linux-hardware.org/?probe=f35a975672) | Oct 29, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [57c7ce8322](https://linux-hardware.org/?probe=57c7ce8322) | Oct 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [8d106c22bf](https://linux-hardware.org/?probe=8d106c22bf) | Oct 28, 2023 |
| Dell          | Latitude 3590               | Notebook    | [2d288fa42e](https://linux-hardware.org/?probe=2d288fa42e) | Oct 27, 2023 |
| Huanan        | X99-F8                      | Desktop     | [69329218c9](https://linux-hardware.org/?probe=69329218c9) | Oct 25, 2023 |
| LG Electro... | R310-K.AP31B                | Notebook    | [ac3922c573](https://linux-hardware.org/?probe=ac3922c573) | Oct 24, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [26691d6dfc](https://linux-hardware.org/?probe=26691d6dfc) | Oct 23, 2023 |
| Lenovo        | ThinkPad T420 4180DT9       | Notebook    | [8f8c03ab3b](https://linux-hardware.org/?probe=8f8c03ab3b) | Oct 22, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [dac0aa7f70](https://linux-hardware.org/?probe=dac0aa7f70) | Oct 22, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [150a11b476](https://linux-hardware.org/?probe=150a11b476) | Oct 21, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [4f6872735a](https://linux-hardware.org/?probe=4f6872735a) | Oct 21, 2023 |
| Google        | Pirika                      | Notebook    | [98eea3bc0f](https://linux-hardware.org/?probe=98eea3bc0f) | Oct 20, 2023 |
| MSI           | B85M-E45                    | Desktop     | [8c3f253c5e](https://linux-hardware.org/?probe=8c3f253c5e) | Oct 19, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [a3bc73fa83](https://linux-hardware.org/?probe=a3bc73fa83) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d561271316](https://linux-hardware.org/?probe=d561271316) | Oct 19, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0846a94456](https://linux-hardware.org/?probe=0846a94456) | Oct 17, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [2ba4da42b0](https://linux-hardware.org/?probe=2ba4da42b0) | Oct 16, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [bbe0a1064d](https://linux-hardware.org/?probe=bbe0a1064d) | Oct 15, 2023 |
| Sony          | VAIO                        | All in one  | [653a82e6b9](https://linux-hardware.org/?probe=653a82e6b9) | Oct 14, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [ef9aa5b89c](https://linux-hardware.org/?probe=ef9aa5b89c) | Oct 14, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [63c82d8692](https://linux-hardware.org/?probe=63c82d8692) | Oct 13, 2023 |
| MSI           | GE72 6QF                    | Notebook    | [94f1c85d10](https://linux-hardware.org/?probe=94f1c85d10) | Oct 13, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [aa4d9c935e](https://linux-hardware.org/?probe=aa4d9c935e) | Oct 12, 2023 |
| Compal        | PCW20                       | Notebook    | [94330b69a9](https://linux-hardware.org/?probe=94330b69a9) | Oct 11, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [1da5f9aefa](https://linux-hardware.org/?probe=1da5f9aefa) | Oct 09, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45d51130b0](https://linux-hardware.org/?probe=45d51130b0) | Oct 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [db64f95dac](https://linux-hardware.org/?probe=db64f95dac) | Oct 08, 2023 |
| Medion        | E15408                      | Notebook    | [5104fa354e](https://linux-hardware.org/?probe=5104fa354e) | Oct 07, 2023 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [2dc2d438ea](https://linux-hardware.org/?probe=2dc2d438ea) | Oct 07, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6c5a7d30f3](https://linux-hardware.org/?probe=6c5a7d30f3) | Oct 06, 2023 |
| AZW           | GTR V01                     | Mini pc     | [4ea472bae4](https://linux-hardware.org/?probe=4ea472bae4) | Oct 05, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [9274bccdad](https://linux-hardware.org/?probe=9274bccdad) | Oct 05, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7ad16296eb](https://linux-hardware.org/?probe=7ad16296eb) | Oct 05, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [fcfe482832](https://linux-hardware.org/?probe=fcfe482832) | Oct 04, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T52R     | Notebook    | [39983ac5b1](https://linux-hardware.org/?probe=39983ac5b1) | Oct 04, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [06c1e095a7](https://linux-hardware.org/?probe=06c1e095a7) | Oct 03, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [2e81483931](https://linux-hardware.org/?probe=2e81483931) | Oct 02, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [ab1e1fe545](https://linux-hardware.org/?probe=ab1e1fe545) | Oct 01, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [1df2dc7261](https://linux-hardware.org/?probe=1df2dc7261) | Oct 01, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9ced54f630](https://linux-hardware.org/?probe=9ced54f630) | Oct 01, 2023 |
| Dell          | 0MN1TX A02                  | Desktop     | [3f0eee5de0](https://linux-hardware.org/?probe=3f0eee5de0) | Oct 01, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [62740874ab](https://linux-hardware.org/?probe=62740874ab) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b4a58da74c](https://linux-hardware.org/?probe=b4a58da74c) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [e26d1b1ae4](https://linux-hardware.org/?probe=e26d1b1ae4) | Sep 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [074ab86d60](https://linux-hardware.org/?probe=074ab86d60) | Sep 29, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [618cd9dd90](https://linux-hardware.org/?probe=618cd9dd90) | Sep 29, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [1caa3c5c7e](https://linux-hardware.org/?probe=1caa3c5c7e) | Sep 28, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [cf0c9cc177](https://linux-hardware.org/?probe=cf0c9cc177) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0c9b2c687a](https://linux-hardware.org/?probe=0c9b2c687a) | Sep 28, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [773691291a](https://linux-hardware.org/?probe=773691291a) | Sep 28, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [243f89703d](https://linux-hardware.org/?probe=243f89703d) | Sep 26, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8142da7d40](https://linux-hardware.org/?probe=8142da7d40) | Sep 25, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [fee2fdb49a](https://linux-hardware.org/?probe=fee2fdb49a) | Sep 25, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [dc6cea804c](https://linux-hardware.org/?probe=dc6cea804c) | Sep 24, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [b063bf9f1e](https://linux-hardware.org/?probe=b063bf9f1e) | Sep 24, 2023 |
| ASUSTek       | X542UN                      | Notebook    | [76f91b9954](https://linux-hardware.org/?probe=76f91b9954) | Sep 24, 2023 |
| HP            | 2B2C                        | Desktop     | [79ccf62c55](https://linux-hardware.org/?probe=79ccf62c55) | Sep 23, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | Notebook    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [2fc60c03c3](https://linux-hardware.org/?probe=2fc60c03c3) | Sep 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [fc49b16c1c](https://linux-hardware.org/?probe=fc49b16c1c) | Sep 22, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ee0a21be07](https://linux-hardware.org/?probe=ee0a21be07) | Sep 21, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [27f3ee04f8](https://linux-hardware.org/?probe=27f3ee04f8) | Sep 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [5e059c90e1](https://linux-hardware.org/?probe=5e059c90e1) | Sep 21, 2023 |
| ASUSTek       | GL503VMF                    | Notebook    | [0e43a1da82](https://linux-hardware.org/?probe=0e43a1da82) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c1ca0a1d1c](https://linux-hardware.org/?probe=c1ca0a1d1c) | Sep 19, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [fe16b7a5a1](https://linux-hardware.org/?probe=fe16b7a5a1) | Sep 19, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [a2a7eacfe6](https://linux-hardware.org/?probe=a2a7eacfe6) | Sep 18, 2023 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [e80d14f9e4](https://linux-hardware.org/?probe=e80d14f9e4) | Sep 18, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [675cec7d95](https://linux-hardware.org/?probe=675cec7d95) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [eb2fcff0f3](https://linux-hardware.org/?probe=eb2fcff0f3) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [c95eedf70e](https://linux-hardware.org/?probe=c95eedf70e) | Sep 16, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [966d90cbc8](https://linux-hardware.org/?probe=966d90cbc8) | Sep 14, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [04bf6410bd](https://linux-hardware.org/?probe=04bf6410bd) | Sep 14, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [0c62999a52](https://linux-hardware.org/?probe=0c62999a52) | Sep 14, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cad3ce176d](https://linux-hardware.org/?probe=cad3ce176d) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| ASUSTek       | UX305FA                     | Notebook    | [e4ade39a1c](https://linux-hardware.org/?probe=e4ade39a1c) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a68551130a](https://linux-hardware.org/?probe=a68551130a) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3edc89267d](https://linux-hardware.org/?probe=3edc89267d) | Sep 13, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [82125c27c9](https://linux-hardware.org/?probe=82125c27c9) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [e793b9e3d9](https://linux-hardware.org/?probe=e793b9e3d9) | Sep 12, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [79d77d78be](https://linux-hardware.org/?probe=79d77d78be) | Sep 12, 2023 |
| MSI           | GE62 7RD                    | Notebook    | [ff590de77d](https://linux-hardware.org/?probe=ff590de77d) | Sep 11, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [671415f9ca](https://linux-hardware.org/?probe=671415f9ca) | Sep 11, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [bcfc38f6da](https://linux-hardware.org/?probe=bcfc38f6da) | Sep 11, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [86f844f512](https://linux-hardware.org/?probe=86f844f512) | Sep 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1ff3e228da](https://linux-hardware.org/?probe=1ff3e228da) | Sep 10, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [3bc292a4ce](https://linux-hardware.org/?probe=3bc292a4ce) | Sep 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [75ca1d0c52](https://linux-hardware.org/?probe=75ca1d0c52) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [83b997b3ab](https://linux-hardware.org/?probe=83b997b3ab) | Sep 09, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [5b2fda7ad6](https://linux-hardware.org/?probe=5b2fda7ad6) | Sep 09, 2023 |
| HP            | 2B18                        | Desktop     | [9c8753a19e](https://linux-hardware.org/?probe=9c8753a19e) | Sep 09, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [edb578f198](https://linux-hardware.org/?probe=edb578f198) | Sep 09, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [bb02ef5cc7](https://linux-hardware.org/?probe=bb02ef5cc7) | Sep 08, 2023 |
| Google        | Pirika                      | Notebook    | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| HP            | 2B3C                        | Desktop     | [471f0f283b](https://linux-hardware.org/?probe=471f0f283b) | Sep 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [55c623e23d](https://linux-hardware.org/?probe=55c623e23d) | Sep 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [db0c457b51](https://linux-hardware.org/?probe=db0c457b51) | Sep 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [b1329d0cc1](https://linux-hardware.org/?probe=b1329d0cc1) | Sep 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [efd67d7c17](https://linux-hardware.org/?probe=efd67d7c17) | Sep 02, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2acb1da32c](https://linux-hardware.org/?probe=2acb1da32c) | Sep 02, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [80a93a9457](https://linux-hardware.org/?probe=80a93a9457) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [9de67aa419](https://linux-hardware.org/?probe=9de67aa419) | Sep 01, 2023 |
| HP            | 18E9                        | Desktop     | [fd1f6decb2](https://linux-hardware.org/?probe=fd1f6decb2) | Sep 01, 2023 |
| Dell          | G15 5530                    | Notebook    | [ababfa6c5e](https://linux-hardware.org/?probe=ababfa6c5e) | Aug 31, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [92552fa038](https://linux-hardware.org/?probe=92552fa038) | Aug 30, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [ea78ba2d46](https://linux-hardware.org/?probe=ea78ba2d46) | Aug 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [176ad353fa](https://linux-hardware.org/?probe=176ad353fa) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [fc7834595f](https://linux-hardware.org/?probe=fc7834595f) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [5b896ea45c](https://linux-hardware.org/?probe=5b896ea45c) | Aug 29, 2023 |
| Acer          | Aspire V5-471               | Notebook    | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6b6ec006aa](https://linux-hardware.org/?probe=6b6ec006aa) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [ee8ee6bf06](https://linux-hardware.org/?probe=ee8ee6bf06) | Aug 28, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [c6614846b5](https://linux-hardware.org/?probe=c6614846b5) | Aug 28, 2023 |
| HP            | 2B18                        | Desktop     | [891ce74167](https://linux-hardware.org/?probe=891ce74167) | Aug 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [450512bee1](https://linux-hardware.org/?probe=450512bee1) | Aug 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [7423f83594](https://linux-hardware.org/?probe=7423f83594) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [6ae200367f](https://linux-hardware.org/?probe=6ae200367f) | Aug 27, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [ee07c69165](https://linux-hardware.org/?probe=ee07c69165) | Aug 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [8f85c500ec](https://linux-hardware.org/?probe=8f85c500ec) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [17a7fc84be](https://linux-hardware.org/?probe=17a7fc84be) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [d4cf1916d2](https://linux-hardware.org/?probe=d4cf1916d2) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [211472aacc](https://linux-hardware.org/?probe=211472aacc) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [16790cbb5f](https://linux-hardware.org/?probe=16790cbb5f) | Aug 26, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0c46e2d419](https://linux-hardware.org/?probe=0c46e2d419) | Aug 26, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [bca12d1c12](https://linux-hardware.org/?probe=bca12d1c12) | Aug 24, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [202017a190](https://linux-hardware.org/?probe=202017a190) | Aug 23, 2023 |
| Google        | Pirika                      | Notebook    | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | Notebook    | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| VIT           | P2402                       | Notebook    | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | Notebook    | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [cdef569014](https://linux-hardware.org/?probe=cdef569014) | Aug 22, 2023 |
| Win Elemen... | M9                          | Desktop     | [f161447dfc](https://linux-hardware.org/?probe=f161447dfc) | Aug 22, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [e00521ec88](https://linux-hardware.org/?probe=e00521ec88) | Aug 22, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [b7c9c3e0c4](https://linux-hardware.org/?probe=b7c9c3e0c4) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [882234a7b8](https://linux-hardware.org/?probe=882234a7b8) | Aug 22, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ee47d4b6a7](https://linux-hardware.org/?probe=ee47d4b6a7) | Aug 20, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [1d013fbf4b](https://linux-hardware.org/?probe=1d013fbf4b) | Aug 20, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [4456ccbc85](https://linux-hardware.org/?probe=4456ccbc85) | Aug 20, 2023 |
| MSI           | MEG Z390 ACE                | Desktop     | [5ab219fbd1](https://linux-hardware.org/?probe=5ab219fbd1) | Aug 20, 2023 |
| MSI           | H270M BAZOOKA               | Desktop     | [f51f1ce129](https://linux-hardware.org/?probe=f51f1ce129) | Aug 19, 2023 |
| Lenovo        | Rev B 82KU                  | Notebook    | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [faaba537ca](https://linux-hardware.org/?probe=faaba537ca) | Aug 18, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [6bda9908df](https://linux-hardware.org/?probe=6bda9908df) | Aug 16, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [d7ec063f46](https://linux-hardware.org/?probe=d7ec063f46) | Aug 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [11dafc79e8](https://linux-hardware.org/?probe=11dafc79e8) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [c078e667a4](https://linux-hardware.org/?probe=c078e667a4) | Aug 15, 2023 |
| Sony          | VAIO                        | All in one  | [a134fd35ac](https://linux-hardware.org/?probe=a134fd35ac) | Aug 13, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [878209b83a](https://linux-hardware.org/?probe=878209b83a) | Aug 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1c643cc90f](https://linux-hardware.org/?probe=1c643cc90f) | Aug 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [551d8f3fc8](https://linux-hardware.org/?probe=551d8f3fc8) | Aug 13, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [3e830ffabc](https://linux-hardware.org/?probe=3e830ffabc) | Aug 12, 2023 |
| Dell          | G3 3590                     | Notebook    | [084d659110](https://linux-hardware.org/?probe=084d659110) | Aug 11, 2023 |
| LNV           | L40-70                      | Notebook    | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [93a61b62a5](https://linux-hardware.org/?probe=93a61b62a5) | Aug 11, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [eee160a070](https://linux-hardware.org/?probe=eee160a070) | Aug 10, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [284cfb0f6d](https://linux-hardware.org/?probe=284cfb0f6d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [38ab435feb](https://linux-hardware.org/?probe=38ab435feb) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [e642e8e489](https://linux-hardware.org/?probe=e642e8e489) | Aug 08, 2023 |
| Sony          | VAIO                        | All in one  | [e924df8ac8](https://linux-hardware.org/?probe=e924df8ac8) | Aug 07, 2023 |
| Sony          | VAIO                        | All in one  | [8349b185e4](https://linux-hardware.org/?probe=8349b185e4) | Aug 07, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| WEIGO         | CDA-141AU                   | Notebook    | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8b84e48f4c](https://linux-hardware.org/?probe=8b84e48f4c) | Aug 04, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [5d5a4b489b](https://linux-hardware.org/?probe=5d5a4b489b) | Aug 03, 2023 |
| ASRock        | Z77 Professional            | Desktop     | [2f0bc369b4](https://linux-hardware.org/?probe=2f0bc369b4) | Aug 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| Dell          | G3 3590                     | Notebook    | [78aeeb1aa3](https://linux-hardware.org/?probe=78aeeb1aa3) | Aug 02, 2023 |
| Dell          | G3 3590                     | Notebook    | [47d3c9b9fe](https://linux-hardware.org/?probe=47d3c9b9fe) | Aug 02, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b0d7ab05f0](https://linux-hardware.org/?probe=b0d7ab05f0) | Aug 02, 2023 |
| AZW           | SER                         | Mini pc     | [de1abb2584](https://linux-hardware.org/?probe=de1abb2584) | Aug 02, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [39216c08ff](https://linux-hardware.org/?probe=39216c08ff) | Aug 01, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [70a56ad26d](https://linux-hardware.org/?probe=70a56ad26d) | Aug 01, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [f710ad8b96](https://linux-hardware.org/?probe=f710ad8b96) | Jul 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [eb14620792](https://linux-hardware.org/?probe=eb14620792) | Jul 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [20d5d0a3ad](https://linux-hardware.org/?probe=20d5d0a3ad) | Jul 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [3fb2cba3db](https://linux-hardware.org/?probe=3fb2cba3db) | Jul 29, 2023 |
| HP            | 82DD 0001                   | All in one  | [e6da7743f0](https://linux-hardware.org/?probe=e6da7743f0) | Jul 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [37440e19b5](https://linux-hardware.org/?probe=37440e19b5) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [a467ce5440](https://linux-hardware.org/?probe=a467ce5440) | Jul 28, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [dc632de3b5](https://linux-hardware.org/?probe=dc632de3b5) | Jul 27, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [5de59d7736](https://linux-hardware.org/?probe=5de59d7736) | Jul 27, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [762861205a](https://linux-hardware.org/?probe=762861205a) | Jul 26, 2023 |
| Intel         | B75                         | Desktop     | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [676bfc8484](https://linux-hardware.org/?probe=676bfc8484) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f5174240a7](https://linux-hardware.org/?probe=f5174240a7) | Jul 23, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [eb12521a96](https://linux-hardware.org/?probe=eb12521a96) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c95c0b0730](https://linux-hardware.org/?probe=c95c0b0730) | Jul 22, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [96f5f9ffdc](https://linux-hardware.org/?probe=96f5f9ffdc) | Jul 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c10ecff0f6](https://linux-hardware.org/?probe=c10ecff0f6) | Jul 19, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [54f9bd2050](https://linux-hardware.org/?probe=54f9bd2050) | Jul 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [866bc45d05](https://linux-hardware.org/?probe=866bc45d05) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [d23b7166b1](https://linux-hardware.org/?probe=d23b7166b1) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4236C92       | Notebook    | [a7b56f640a](https://linux-hardware.org/?probe=a7b56f640a) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [3c5ef629e4](https://linux-hardware.org/?probe=3c5ef629e4) | Jul 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4d00148664](https://linux-hardware.org/?probe=4d00148664) | Jul 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [e88c64ac3c](https://linux-hardware.org/?probe=e88c64ac3c) | Jul 16, 2023 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [59bf614ae2](https://linux-hardware.org/?probe=59bf614ae2) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [75d40e5a2b](https://linux-hardware.org/?probe=75d40e5a2b) | Jul 14, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [d477369e7e](https://linux-hardware.org/?probe=d477369e7e) | Jul 14, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [698c4a8958](https://linux-hardware.org/?probe=698c4a8958) | Jul 14, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [9946c63986](https://linux-hardware.org/?probe=9946c63986) | Jul 12, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [06f4243bee](https://linux-hardware.org/?probe=06f4243bee) | Jul 12, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [995e13dee9](https://linux-hardware.org/?probe=995e13dee9) | Jul 11, 2023 |
| Lenovo        | ThinkPad P72 20MCS0EU00     | Notebook    | [394bdbc596](https://linux-hardware.org/?probe=394bdbc596) | Jul 11, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [a5d9143c99](https://linux-hardware.org/?probe=a5d9143c99) | Jul 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [bbc78272ea](https://linux-hardware.org/?probe=bbc78272ea) | Jul 10, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [b5ddf3381c](https://linux-hardware.org/?probe=b5ddf3381c) | Jul 10, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [8fcda3580f](https://linux-hardware.org/?probe=8fcda3580f) | Jul 08, 2023 |
| Alienware     | 17                          | Notebook    | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [cd45163d47](https://linux-hardware.org/?probe=cd45163d47) | Jul 08, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [27e600a93b](https://linux-hardware.org/?probe=27e600a93b) | Jul 07, 2023 |
| Dell          | Latitude 7480               | Notebook    | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b23ba37244](https://linux-hardware.org/?probe=b23ba37244) | Jul 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ca637a5884](https://linux-hardware.org/?probe=ca637a5884) | Jul 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [407e00921f](https://linux-hardware.org/?probe=407e00921f) | Jul 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [fc70411ea4](https://linux-hardware.org/?probe=fc70411ea4) | Jul 03, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [107fe61a53](https://linux-hardware.org/?probe=107fe61a53) | Jul 02, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [7fee63007e](https://linux-hardware.org/?probe=7fee63007e) | Jul 02, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Medion        | Akoya P7818                 | Notebook    | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [c3118a3d89](https://linux-hardware.org/?probe=c3118a3d89) | Jun 29, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [895760e7db](https://linux-hardware.org/?probe=895760e7db) | Jun 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fa162784e0](https://linux-hardware.org/?probe=fa162784e0) | Jun 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| MSI           | Z77A-G41                    | Desktop     | [e7e4924bda](https://linux-hardware.org/?probe=e7e4924bda) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [284344e775](https://linux-hardware.org/?probe=284344e775) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [89d6a4edd2](https://linux-hardware.org/?probe=89d6a4edd2) | May 13, 2023 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [5cfbeb30e0](https://linux-hardware.org/?probe=5cfbeb30e0) | May 10, 2023 |
| Unknown       | Intel X79                   | Desktop     | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| Samsung       | 950QED                      | Convertible | [f2568c7949](https://linux-hardware.org/?probe=f2568c7949) | Apr 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | Notebook    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP            | 8437                        | Desktop     | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | Desktop     | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| Dell          | G5 5500                     | Notebook    | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS11Y00     | Notebook    | [0843074b87](https://linux-hardware.org/?probe=0843074b87) | Mar 09, 2023 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Acer          | Aspire GX-281               | Desktop     | [d318df6931](https://linux-hardware.org/?probe=d318df6931) | Mar 04, 2023 |
| JINGSHA       | Unknown                     | Desktop     | [c8bd846b63](https://linux-hardware.org/?probe=c8bd846b63) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [324020ca8b](https://linux-hardware.org/?probe=324020ca8b) | Feb 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d76b048134](https://linux-hardware.org/?probe=d76b048134) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [efd9f878d2](https://linux-hardware.org/?probe=efd9f878d2) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [3c2d4cf289](https://linux-hardware.org/?probe=3c2d4cf289) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0de8121880](https://linux-hardware.org/?probe=0de8121880) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f39ab69b74](https://linux-hardware.org/?probe=f39ab69b74) | Feb 01, 2023 |
| HP            | ProBook 6565b               | Notebook    | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| HP            | 828A                        | Desktop     | [5f430ba8d1](https://linux-hardware.org/?probe=5f430ba8d1) | Jan 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| HP            | 86EE                        | All in one  | [1fc671302e](https://linux-hardware.org/?probe=1fc671302e) | Jan 06, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [77768feff6](https://linux-hardware.org/?probe=77768feff6) | Jan 01, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion        | P6816                       | Notebook    | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo        | ThinkPad L450 20DT0000GE    | Notebook    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [a11de13c4f](https://linux-hardware.org/?probe=a11de13c4f) | Oct 04, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [6de76ddb0e](https://linux-hardware.org/?probe=6de76ddb0e) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Lenovo        | ThinkPad T430s 2356FG9      | Notebook    | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius      | NS585                       | Notebook    | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | Desktop     | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Dell          | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell          | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell          | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Dell          | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP            | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI           | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP            | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | Desktop     | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell          | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP            | 2179                        | Desktop     | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron      | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI           | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell          | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xero/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 452       | 97.2%   |
| Xero         | 13        | 2.8%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 464       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 6.4.12-arch1-1   | 55        | 10.85%  |
| 6.6.4-arch1-1    | 41        | 8.09%   |
| 6.5.9-arch2-1    | 35        | 6.9%    |
| 6.5.5-arch1-1    | 34        | 6.71%   |
| 6.4.9-arch1-1    | 28        | 5.52%   |
| 6.4.3-arch1-2    | 27        | 5.33%   |
| 6.6.8-arch1-1    | 8         | 1.58%   |
| 6.6.7-arch1-1    | 8         | 1.58%   |
| 6.6.3-arch1-1    | 7         | 1.38%   |
| 6.6.1-arch1-1    | 7         | 1.38%   |
| 6.4.2-arch1-1    | 6         | 1.18%   |
| 6.4.10-arch1-1   | 6         | 1.18%   |
| 6.4.1-arch2-1    | 6         | 1.18%   |
| 5.16.15-arch1-1  | 6         | 1.18%   |
| 6.6.2-arch1-1    | 5         | 0.99%   |
| 6.5.3-arch1-1    | 5         | 0.99%   |
| 6.1.12-arch1-1   | 5         | 0.99%   |
| 6.6.9-arch1-1    | 4         | 0.79%   |
| 6.4.4-arch1-1    | 4         | 0.79%   |
| 6.4.11-arch2-1   | 4         | 0.79%   |
| 6.3.9-arch1-1    | 4         | 0.79%   |
| 6.2.6-arch1-1    | 4         | 0.79%   |
| 5.18.16-arch1-1  | 4         | 0.79%   |
| 6.5.2-arch1-1    | 3         | 0.59%   |
| 6.4.8-arch1-1    | 3         | 0.59%   |
| 6.4.3-arch1-1    | 3         | 0.59%   |
| 6.1.1-arch1-1    | 3         | 0.59%   |
| 6.0.12-arch1-1   | 3         | 0.59%   |
| 5.17.9-arch1-1   | 3         | 0.59%   |
| 5.16.2-arch1-1   | 3         | 0.59%   |
| 5.16.1-arch1-1   | 3         | 0.59%   |
| 5.15.33-1-lts    | 3         | 0.59%   |
| 5.14.14-arch1-1  | 3         | 0.59%   |
| 6.7.0-arch3-1    | 2         | 0.39%   |
| 6.6.5-arch1-1    | 2         | 0.39%   |
| 6.5.7-arch1-1    | 2         | 0.39%   |
| 6.5.4-arch2-1    | 2         | 0.39%   |
| 6.4.7-zen1-1-zen | 2         | 0.39%   |
| 6.4.7-arch1-2    | 2         | 0.39%   |
| 6.4.7-arch1-1    | 2         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.12  | 57        | 11.24%  |
| 6.6.4   | 42        | 8.28%   |
| 6.5.9   | 36        | 7.1%    |
| 6.5.5   | 34        | 6.71%   |
| 6.4.3   | 31        | 6.11%   |
| 6.4.9   | 28        | 5.52%   |
| 6.6.8   | 9         | 1.78%   |
| 6.6.7   | 8         | 1.58%   |
| 6.4.7   | 8         | 1.58%   |
| 6.4.2   | 8         | 1.58%   |
| 6.4.10  | 8         | 1.58%   |
| 6.4.1   | 8         | 1.58%   |
| 6.6.3   | 7         | 1.38%   |
| 6.6.1   | 7         | 1.38%   |
| 6.4.11  | 6         | 1.18%   |
| 6.3.9   | 6         | 1.18%   |
| 5.16.15 | 6         | 1.18%   |
| 6.6.2   | 5         | 0.99%   |
| 6.5.3   | 5         | 0.99%   |
| 6.5.2   | 5         | 0.99%   |
| 6.4.4   | 5         | 0.99%   |
| 6.1.12  | 5         | 0.99%   |
| 6.6.9   | 4         | 0.79%   |
| 6.2.6   | 4         | 0.79%   |
| 6.0.12  | 4         | 0.79%   |
| 5.18.16 | 4         | 0.79%   |
| 5.14.14 | 4         | 0.79%   |
| 6.7.0   | 3         | 0.59%   |
| 6.6.6   | 3         | 0.59%   |
| 6.5.4   | 3         | 0.59%   |
| 6.4.8   | 3         | 0.59%   |
| 6.3.8   | 3         | 0.59%   |
| 6.1.1   | 3         | 0.59%   |
| 5.19.13 | 3         | 0.59%   |
| 5.17.9  | 3         | 0.59%   |
| 5.16.2  | 3         | 0.59%   |
| 5.16.16 | 3         | 0.59%   |
| 5.16.1  | 3         | 0.59%   |
| 5.15.33 | 3         | 0.59%   |
| 5.15.12 | 3         | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 157       | 31.98%  |
| 6.6     | 85        | 17.31%  |
| 6.5     | 85        | 17.31%  |
| 5.16    | 23        | 4.68%   |
| 6.1     | 19        | 3.87%   |
| 5.15    | 18        | 3.67%   |
| 6.3     | 15        | 3.05%   |
| 6.0     | 15        | 3.05%   |
| 6.2     | 14        | 2.85%   |
| 5.14    | 13        | 2.65%   |
| 5.19    | 11        | 2.24%   |
| 5.18    | 11        | 2.24%   |
| 6.7     | 8         | 1.63%   |
| 5.17    | 8         | 1.63%   |
| 5.10    | 3         | 0.61%   |
| 5.13    | 2         | 0.41%   |
| 6.12    | 1         | 0.2%    |
| 6.10    | 1         | 0.2%    |
| 5.12    | 1         | 0.2%    |
| 5.11    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 464       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 447       | 95.11%  |
| XFCE     | 10        | 2.13%   |
| GNOME    | 4         | 0.85%   |
| Hyprland | 3         | 0.64%   |
| KDE      | 2         | 0.43%   |
| Unknown  | 2         | 0.43%   |
| LeftWM   | 1         | 0.21%   |
| KDE6     | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 362       | 76.86%  |
| Wayland | 105       | 22.29%  |
| Tty     | 3         | 0.64%   |
| Unknown | 1         | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 410       | 86.5%   |
| Unknown | 33        | 6.96%   |
| LightDM | 28        | 5.91%   |
| GDM     | 2         | 0.42%   |
| TDM     | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 195       | 41.58%  |
| de_DE      | 37        | 7.89%   |
| en_IN      | 23        | 4.9%    |
| es_MX      | 20        | 4.26%   |
| en_GB      | 17        | 3.62%   |
| ru_RU      | 16        | 3.41%   |
| pl_PL      | 16        | 3.41%   |
| fr_FR      | 15        | 3.2%    |
| pt_BR      | 14        | 2.99%   |
| it_IT      | 14        | 2.99%   |
| en_CA      | 11        | 2.35%   |
| es_ES      | 10        | 2.13%   |
| C          | 9         | 1.92%   |
| tr_TR      | 8         | 1.71%   |
| en_AU      | 8         | 1.71%   |
| hu_HU      | 7         | 1.49%   |
| zh_CN      | 6         | 1.28%   |
| es_AR      | 5         | 1.07%   |
| en_ZA      | 3         | 0.64%   |
| de_AT      | 3         | 0.64%   |
| vi_VN      | 2         | 0.43%   |
| nb_NO      | 2         | 0.43%   |
| en_PH      | 2         | 0.43%   |
| en_DK      | 2         | 0.43%   |
| zh_HK      | 1         | 0.21%   |
| uk_UA      | 1         | 0.21%   |
| sv_SE      | 1         | 0.21%   |
| nl_NL      | 1         | 0.21%   |
| ko_KR      | 1         | 0.21%   |
| fr_BE      | 1         | 0.21%   |
| es_VE      | 1         | 0.21%   |
| es_SV      | 1         | 0.21%   |
| es_PE      | 1         | 0.21%   |
| es_CL      | 1         | 0.21%   |
| es_BO      | 1         | 0.21%   |
| en_IL      | 1         | 0.21%   |
| en_AG      | 1         | 0.21%   |
| el_GR@euro | 1         | 0.21%   |
| el_GR      | 1         | 0.21%   |
| de_LI      | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 352       | 75.37%  |
| BIOS | 115       | 24.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 222       | 46.84%  |
| Btrfs   | 144       | 30.38%  |
| Xfs     | 97        | 20.46%  |
| Overlay | 10        | 2.11%   |
| Nilfs2  | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 372       | 79.66%  |
| MBR     | 62        | 13.28%  |
| Unknown | 33        | 7.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 351       | 74.21%  |
| Yes       | 122       | 25.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 281       | 60.17%  |
| Yes       | 186       | 39.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 90        | 19.4%   |
| Lenovo              | 80        | 17.24%  |
| Dell                | 59        | 12.72%  |
| Hewlett-Packard     | 56        | 12.07%  |
| MSI                 | 33        | 7.11%   |
| Acer                | 25        | 5.39%   |
| Gigabyte Technology | 18        | 3.88%   |
| Apple               | 16        | 3.45%   |
| ASRock              | 13        | 2.8%    |
| HUAWEI              | 9         | 1.94%   |
| Toshiba             | 5         | 1.08%   |
| Intel               | 5         | 1.08%   |
| Pegatron            | 4         | 0.86%   |
| Medion              | 4         | 0.86%   |
| Timi                | 3         | 0.65%   |
| Microsoft           | 3         | 0.65%   |
| Google              | 3         | 0.65%   |
| ECS                 | 3         | 0.65%   |
| AZW                 | 3         | 0.65%   |
| Win Element         | 2         | 0.43%   |
| Samsung Electronics | 2         | 0.43%   |
| MECHREVO            | 2         | 0.43%   |
| Huanan              | 2         | 0.43%   |
| Fujitsu             | 2         | 0.43%   |
| BESSTAR Tech        | 2         | 0.43%   |
| Alienware           | 2         | 0.43%   |
| Unknown             | 2         | 0.43%   |
| ZOTAC               | 1         | 0.22%   |
| WEIGO               | 1         | 0.22%   |
| VIT                 | 1         | 0.22%   |
| Sony                | 1         | 0.22%   |
| Positivo            | 1         | 0.22%   |
| Panasonic           | 1         | 0.22%   |
| LNV                 | 1         | 0.22%   |
| LG Electronics      | 1         | 0.22%   |
| Juana Manso         | 1         | 0.22%   |
| JINGSHA             | 1         | 0.22%   |
| HONOR               | 1         | 0.22%   |
| Dynabook            | 1         | 0.22%   |
| Compal              | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell OptiPlex 9020                  | 4         | 0.86%   |
| Dell OptiPlex 7010                  | 4         | 0.86%   |
| MSI MS-7C37                         | 3         | 0.65%   |
| Dell Precision M3800                | 3         | 0.65%   |
| Unknown                             | 3         | 0.65%   |
| Win Element M9                      | 2         | 0.43%   |
| MSI MS-7971                         | 2         | 0.43%   |
| MSI Bravo 15 B5DD                   | 2         | 0.43%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1 | 2         | 0.43%   |
| HUAWEI BOM-WXX9                     | 2         | 0.43%   |
| HP Pavilion dv7                     | 2         | 0.43%   |
| HP Notebook                         | 2         | 0.43%   |
| HP Laptop 15-da0xxx                 | 2         | 0.43%   |
| Dell Studio XPS 8100                | 2         | 0.43%   |
| Dell Latitude E6520                 | 2         | 0.43%   |
| Dell Latitude E6430                 | 2         | 0.43%   |
| Dell Latitude 7480                  | 2         | 0.43%   |
| Dell Latitude 5420                  | 2         | 0.43%   |
| AZW SER                             | 2         | 0.43%   |
| ASUS TUF Gaming X570-PLUS           | 2         | 0.43%   |
| ASUS ROG Flow X13 GV301RC_GV301RC   | 2         | 0.43%   |
| ASUS PRIME B450M-A II               | 2         | 0.43%   |
| ASUS PRIME A320M-K                  | 2         | 0.43%   |
| Apple MacBookPro8,1                 | 2         | 0.43%   |
| Acer Nitro AN515-57                 | 2         | 0.43%   |
| ZOTAC ZBOX-ID88/ID89/ID90           | 1         | 0.22%   |
| WEIGO CDA-141AU                     | 1         | 0.22%   |
| VIT P2402                           | 1         | 0.22%   |
| Toshiba TECRA A11                   | 1         | 0.22%   |
| Toshiba Satellite Pro L300          | 1         | 0.22%   |
| Toshiba Satellite P50-B-11V         | 1         | 0.22%   |
| Toshiba Satellite L755D             | 1         | 0.22%   |
| Toshiba Satellite C55-C             | 1         | 0.22%   |
| Timi RedmiBook 14-APCS              | 1         | 0.22%   |
| Timi Redmi Book Pro 15 2022         | 1         | 0.22%   |
| Timi Redmi Book Pro 14 2022         | 1         | 0.22%   |
| Sony VGC-LV180ME                    | 1         | 0.22%   |
| Samsung 950QED                      | 1         | 0.22%   |
| Samsung 750XDA                      | 1         | 0.22%   |
| Positivo C4128A-14                  | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 33        | 7.11%   |
| Lenovo IdeaPad     | 23        | 4.96%   |
| ASUS ROG           | 20        | 4.31%   |
| Dell Latitude      | 18        | 3.88%   |
| Acer Aspire        | 17        | 3.66%   |
| Dell Inspiron      | 16        | 3.45%   |
| HP Laptop          | 14        | 3.02%   |
| HP Pavilion        | 12        | 2.59%   |
| ASUS TUF           | 12        | 2.59%   |
| Dell OptiPlex      | 10        | 2.16%   |
| ASUS VivoBook      | 10        | 2.16%   |
| ASUS PRIME         | 10        | 2.16%   |
| Lenovo Legion      | 6         | 1.29%   |
| ASUS ASUS          | 6         | 1.29%   |
| Lenovo Yoga        | 5         | 1.08%   |
| Toshiba Satellite  | 4         | 0.86%   |
| Dell Precision     | 4         | 0.86%   |
| Acer Nitro         | 4         | 0.86%   |
| MSI MS-7C37        | 3         | 0.65%   |
| Microsoft Surface  | 3         | 0.65%   |
| HP ProBook         | 3         | 0.65%   |
| Dell Studio        | 3         | 0.65%   |
| Apple MacBookPro11 | 3         | 0.65%   |
| Unknown            | 3         | 0.65%   |
| Win Element M9     | 2         | 0.43%   |
| Timi Redmi         | 2         | 0.43%   |
| MSI MS-7971        | 2         | 0.43%   |
| MSI Bravo          | 2         | 0.43%   |
| Lenovo IdeaPadFlex | 2         | 0.43%   |
| HUAWEI BOM-WXX9    | 2         | 0.43%   |
| HP ZBook           | 2         | 0.43%   |
| HP Notebook        | 2         | 0.43%   |
| HP ENVY            | 2         | 0.43%   |
| Gigabyte Z790      | 2         | 0.43%   |
| Gigabyte X570      | 2         | 0.43%   |
| Gigabyte B450M     | 2         | 0.43%   |
| Dell XPS           | 2         | 0.43%   |
| Dell Vostro        | 2         | 0.43%   |
| AZW SER            | 2         | 0.43%   |
| ASUS M5A99X        | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 63        | 13.58%  |
| 2020 | 57        | 12.28%  |
| 2021 | 56        | 12.07%  |
| 2018 | 35        | 7.54%   |
| 2017 | 33        | 7.11%   |
| 2014 | 29        | 6.25%   |
| 2013 | 29        | 6.25%   |
| 2012 | 26        | 5.6%    |
| 2022 | 24        | 5.17%   |
| 2011 | 24        | 5.17%   |
| 2015 | 22        | 4.74%   |
| 2016 | 18        | 3.88%   |
| 2023 | 16        | 3.45%   |
| 2009 | 10        | 2.16%   |
| 2008 | 9         | 1.94%   |
| 2010 | 8         | 1.72%   |
| 2007 | 3         | 0.65%   |
| 2024 | 2         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 270       | 58.19%  |
| Desktop     | 157       | 33.84%  |
| Convertible | 15        | 3.23%   |
| Mini pc     | 10        | 2.16%   |
| All in one  | 8         | 1.72%   |
| Tablet      | 3         | 0.65%   |
| Server      | 1         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 463       | 99.57%  |
| Enabled  | 2         | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 461       | 99.35%  |
| Yes  | 3         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 123       | 26.39%  |
| 16.01-24.0  | 121       | 25.97%  |
| 8.01-16.0   | 88        | 18.88%  |
| 3.01-4.0    | 61        | 13.09%  |
| 32.01-64.0  | 50        | 10.73%  |
| 24.01-32.0  | 11        | 2.36%   |
| 64.01-256.0 | 11        | 2.36%   |
| 2.01-3.0    | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 168       | 34.01%  |
| 2.01-3.0   | 155       | 31.38%  |
| 4.01-8.0   | 73        | 14.78%  |
| 3.01-4.0   | 68        | 13.77%  |
| 8.01-16.0  | 15        | 3.04%   |
| 16.01-24.0 | 8         | 1.62%   |
| 0.51-1.0   | 4         | 0.81%   |
| 0.01-0.5   | 2         | 0.4%    |
| 24.01-32.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 252       | 53.5%   |
| 2      | 135       | 28.66%  |
| 3      | 50        | 10.62%  |
| 4      | 15        | 3.18%   |
| 5      | 10        | 2.12%   |
| 6      | 5         | 1.06%   |
| 8      | 2         | 0.42%   |
| 7      | 2         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 347       | 74.78%  |
| Yes       | 117       | 25.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 380       | 81.72%  |
| No        | 85        | 18.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 387       | 83.05%  |
| No        | 79        | 16.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 346       | 74.09%  |
| No        | 121       | 25.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 86        | 18.42%  |
| Germany      | 46        | 9.85%   |
| India        | 28        | 6%      |
| Poland       | 20        | 4.28%   |
| Russia       | 19        | 4.07%   |
| France       | 18        | 3.85%   |
| Italy        | 16        | 3.43%   |
| Canada       | 16        | 3.43%   |
| Brazil       | 16        | 3.43%   |
| Turkey       | 13        | 2.78%   |
| Mexico       | 11        | 2.36%   |
| Argentina    | 11        | 2.36%   |
| Spain        | 10        | 2.14%   |
| UK           | 9         | 1.93%   |
| China        | 9         | 1.93%   |
| Hungary      | 8         | 1.71%   |
| Australia    | 8         | 1.71%   |
| Vietnam      | 6         | 1.28%   |
| Netherlands  | 6         | 1.28%   |
| Greece       | 5         | 1.07%   |
| Chile        | 5         | 1.07%   |
| Thailand     | 4         | 0.86%   |
| Romania      | 4         | 0.86%   |
| Pakistan     | 4         | 0.86%   |
| Norway       | 4         | 0.86%   |
| Morocco      | 4         | 0.86%   |
| Malaysia     | 4         | 0.86%   |
| Switzerland  | 3         | 0.64%   |
| South Africa | 3         | 0.64%   |
| Portugal     | 3         | 0.64%   |
| Philippines  | 3         | 0.64%   |
| Indonesia    | 3         | 0.64%   |
| Denmark      | 3         | 0.64%   |
| Colombia     | 3         | 0.64%   |
| Belgium      | 3         | 0.64%   |
| Austria      | 3         | 0.64%   |
| Venezuela    | 2         | 0.43%   |
| Syria        | 2         | 0.43%   |
| Sweden       | 2         | 0.43%   |
| Nepal        | 2         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Istanbul       | 7         | 1.48%   |
| Warsaw         | 6         | 1.27%   |
| Berlin         | 5         | 1.06%   |
| Red Lake       | 4         | 0.85%   |
| Portland       | 4         | 0.85%   |
| Longmont       | 4         | 0.85%   |
| Hamburg        | 4         | 0.85%   |
| Stuttgart      | 3         | 0.63%   |
| Seattle        | 3         | 0.63%   |
| Pune           | 3         | 0.63%   |
| Mexico City    | 3         | 0.63%   |
| Melbourne      | 3         | 0.63%   |
| Hanoi          | 3         | 0.63%   |
| Gdansk         | 3         | 0.63%   |
| Chicago        | 3         | 0.63%   |
| Chennai        | 3         | 0.63%   |
| Buenos Aires   | 3         | 0.63%   |
| Bengaluru      | 3         | 0.63%   |
| Voronezh       | 2         | 0.42%   |
| Ufa            | 2         | 0.42%   |
| Tehran         | 2         | 0.42%   |
| Tangerang      | 2         | 0.42%   |
| St Petersburg  | 2         | 0.42%   |
| Sao Paulo      | 2         | 0.42%   |
| Santa Rosa     | 2         | 0.42%   |
| Salt Lake City | 2         | 0.42%   |
| Sacramento     | 2         | 0.42%   |
| Pretoria       | 2         | 0.42%   |
| Poznan         | 2         | 0.42%   |
| Phoenix        | 2         | 0.42%   |
| Patna          | 2         | 0.42%   |
| Paris          | 2         | 0.42%   |
| Norfolk        | 2         | 0.42%   |
| Niterói       | 2         | 0.42%   |
| Munich         | 2         | 0.42%   |
| Mumbai         | 2         | 0.42%   |
| Moscow         | 2         | 0.42%   |
| Medellín      | 2         | 0.42%   |
| Mariahalom     | 2         | 0.42%   |
| Madurai        | 2         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 122       | 167    | 16.35%  |
| Seagate                      | 89        | 115    | 11.93%  |
| WDC                          | 85        | 109    | 11.39%  |
| Sandisk                      | 48        | 61     | 6.43%   |
| Kingston                     | 46        | 57     | 6.17%   |
| Toshiba                      | 41        | 45     | 5.5%    |
| Unknown                      | 24        | 31     | 3.22%   |
| SK hynix                     | 23        | 24     | 3.08%   |
| Intel                        | 23        | 35     | 3.08%   |
| Crucial                      | 23        | 31     | 3.08%   |
| Micron/Crucial Technology    | 15        | 18     | 2.01%   |
| Micron Technology            | 14        | 16     | 1.88%   |
| Phison Electronics           | 11        | 13     | 1.47%   |
| HGST                         | 11        | 12     | 1.47%   |
| Hitachi                      | 10        | 10     | 1.34%   |
| KIOXIA                       | 8         | 9      | 1.07%   |
| Apple                        | 8         | 8      | 1.07%   |
| China                        | 7         | 7      | 0.94%   |
| A-DATA Technology            | 7         | 7      | 0.94%   |
| Kingston Technology Company  | 6         | 7      | 0.8%    |
| ADATA Technology             | 6         | 6      | 0.8%    |
| JMicron Technology           | 5         | 5      | 0.67%   |
| Apacer                       | 5         | 6      | 0.67%   |
| Transcend                    | 4         | 4      | 0.54%   |
| Silicon Motion               | 4         | 6      | 0.54%   |
| Realtek Semiconductor        | 4         | 5      | 0.54%   |
| Phison                       | 4         | 4      | 0.54%   |
| MAXIO Technology (Hangzhou)  | 4         | 4      | 0.54%   |
| LITEONIT                     | 4         | 4      | 0.54%   |
| Intenso                      | 4         | 6      | 0.54%   |
| Team                         | 3         | 3      | 0.4%    |
| SPCC                         | 3         | 4      | 0.4%    |
| Shenzhen Longsys Electronics | 3         | 3      | 0.4%    |
| PNY                          | 3         | 3      | 0.4%    |
| OWC                          | 3         | 3      | 0.4%    |
| LITEON                       | 3         | 4      | 0.4%    |
| Yangtze Memory Technologies  | 2         | 2      | 0.27%   |
| SSK                          | 2         | 2      | 0.27%   |
| SAGE                         | 2         | 2      | 0.27%   |
| Plextor                      | 2         | 2      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 18        | 2.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 12        | 1.49%   |
| Crucial CT500MX500SSD1 500GB                                      | 10        | 1.24%   |
| Kingston SA400S37240G 240GB SSD                                   | 9         | 1.12%   |
| Unknown SD/MMC/MS PRO 128GB                                       | 8         | 0.99%   |
| Toshiba MQ04ABF100 1TB                                            | 8         | 0.99%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                  | 8         | 0.99%   |
| Samsung SSD 860 EVO 500GB                                         | 7         | 0.87%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 7         | 0.87%   |
| Kingston SA400S37960G 960GB SSD                                   | 7         | 0.87%   |
| Kingston SA400S37480G 480GB SSD                                   | 7         | 0.87%   |
| Unknown MMC Card  64GB                                            | 6         | 0.74%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 6         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB               | 6         | 0.74%   |
| Phison E12 NVMe Controller 480GB                                  | 6         | 0.74%   |
| Unknown MMC Card  128GB                                           | 5         | 0.62%   |
| Seagate ST1000DM003-1SB102 1TB                                    | 5         | 0.62%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                            | 4         | 0.5%    |
| Seagate ST2000DM006-2DM164 2TB                                    | 4         | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 4         | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                                    | 4         | 0.5%    |
| Seagate Expansion HDD 14TB                                        | 4         | 0.5%    |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 4         | 0.5%    |
| Samsung SSD 860 EVO 1TB                                           | 4         | 0.5%    |
| Samsung SSD 850 EVO 250GB                                         | 4         | 0.5%    |
| Phison PS5013 E13 NVMe Controller 512GB                           | 4         | 0.5%    |
| Kingston SNVS500G 500GB                                           | 4         | 0.5%    |
| JMicron Generic 500GB                                             | 4         | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                                       | 4         | 0.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 4         | 0.5%    |
| WDC WD20EZBX-00AYRA0 2TB                                          | 3         | 0.37%   |
| WDC WD10SPZX-24Z10 1TB                                            | 3         | 0.37%   |
| WDC WD10EZEX-60M2NA0 1TB                                          | 3         | 0.37%   |
| Toshiba MQ01ABD100 1TB                                            | 3         | 0.37%   |
| Toshiba DT01ACA300 3TB                                            | 3         | 0.37%   |
| Seagate ST1000LM049-2GH172 1TB                                    | 3         | 0.37%   |
| Seagate One Touch HDD 4TB                                         | 3         | 0.37%   |
| Sandisk WD_BLACK SN770 1TB                                        | 3         | 0.37%   |
| Sandisk WD Blue SN570 500GB                                       | 3         | 0.37%   |
| Samsung SSD 980 1TB                                               | 3         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 112    | 36.71%  |
| WDC                 | 66        | 83     | 27.85%  |
| Toshiba             | 30        | 33     | 12.66%  |
| HGST                | 11        | 12     | 4.64%   |
| Hitachi             | 10        | 10     | 4.22%   |
| Unknown             | 8         | 8      | 3.38%   |
| Samsung Electronics | 7         | 7      | 2.95%   |
| JMicron Technology  | 4         | 4      | 1.69%   |
| Intenso             | 3         | 5      | 1.27%   |
| SAGE                | 2         | 2      | 0.84%   |
| ASMedia             | 2         | 2      | 0.84%   |
| TO Exter            | 1         | 1      | 0.42%   |
| SABRENT             | 1         | 1      | 0.42%   |
| Maxtor              | 1         | 1      | 0.42%   |
| Maxone              | 1         | 1      | 0.42%   |
| KESU                | 1         | 1      | 0.42%   |
| ASMT                | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 51        | 62     | 20.99%  |
| Kingston            | 33        | 41     | 13.58%  |
| Crucial             | 23        | 31     | 9.47%   |
| SanDisk             | 17        | 18     | 7%      |
| WDC                 | 16        | 17     | 6.58%   |
| SK hynix            | 7         | 7      | 2.88%   |
| China               | 7         | 7      | 2.88%   |
| Apple               | 6         | 6      | 2.47%   |
| Apacer              | 5         | 6      | 2.06%   |
| A-DATA Technology   | 5         | 5      | 2.06%   |
| Transcend           | 4         | 4      | 1.65%   |
| LITEONIT            | 4         | 4      | 1.65%   |
| Team                | 3         | 3      | 1.23%   |
| SPCC                | 3         | 4      | 1.23%   |
| PNY                 | 3         | 3      | 1.23%   |
| OWC                 | 3         | 3      | 1.23%   |
| Micron Technology   | 3         | 3      | 1.23%   |
| LITEON              | 3         | 4      | 1.23%   |
| Intel               | 3         | 3      | 1.23%   |
| Toshiba             | 2         | 2      | 0.82%   |
| Plextor             | 2         | 2      | 0.82%   |
| Mushkin             | 2         | 2      | 0.82%   |
| Lexar               | 2         | 2      | 0.82%   |
| KingSpec            | 2         | 2      | 0.82%   |
| Hewlett-Packard     | 2         | 2      | 0.82%   |
| Emtec               | 2         | 2      | 0.82%   |
| Corsair             | 2         | 3      | 0.82%   |
| Zebronics           | 1         | 1      | 0.41%   |
| XrayDisk            | 1         | 2      | 0.41%   |
| Vaseky              | 1         | 1      | 0.41%   |
| tecmiyo             | 1         | 1      | 0.41%   |
| TARGET              | 1         | 1      | 0.41%   |
| S3+                 | 1         | 1      | 0.41%   |
| Phison              | 1         | 1      | 0.41%   |
| Patriot             | 1         | 1      | 0.41%   |
| OSCOO               | 1         | 1      | 0.41%   |
| OCZ                 | 1         | 1      | 0.41%   |
| NT-1TB              | 1         | 1      | 0.41%   |
| Netac               | 1         | 1      | 0.41%   |
| Leven               | 1         | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 230       | 326    | 35.06%  |
| SSD     | 206       | 277    | 31.4%   |
| HDD     | 198       | 285    | 30.18%  |
| MMC     | 17        | 24     | 2.59%   |
| Unknown | 5         | 5      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 311       | 511    | 51.32%  |
| NVMe | 229       | 321    | 37.79%  |
| SAS  | 49        | 61     | 8.09%   |
| MMC  | 17        | 24     | 2.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 223       | 295    | 51.98%  |
| 0.51-1.0   | 145       | 183    | 33.8%   |
| 1.01-2.0   | 33        | 43     | 7.69%   |
| 3.01-4.0   | 13        | 16     | 3.03%   |
| 2.01-3.0   | 6         | 7      | 1.4%    |
| 4.01-10.0  | 5         | 10     | 1.17%   |
| 10.01-20.0 | 4         | 8      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 120       | 25%     |
| 251-500        | 98        | 20.42%  |
| 501-1000       | 70        | 14.58%  |
| More than 3000 | 57        | 11.88%  |
| 1001-2000      | 50        | 10.42%  |
| 51-100         | 28        | 5.83%   |
| 21-50          | 17        | 3.54%   |
| 2001-3000      | 16        | 3.33%   |
| Unknown        | 16        | 3.33%   |
| 1-20           | 8         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 197       | 40.37%  |
| 21-50          | 94        | 19.26%  |
| 51-100         | 57        | 11.68%  |
| 101-250        | 52        | 10.66%  |
| 251-500        | 31        | 6.35%   |
| 501-1000       | 16        | 3.28%   |
| Unknown        | 16        | 3.28%   |
| More than 3000 | 9         | 1.84%   |
| 1001-2000      | 9         | 1.84%   |
| 2001-3000      | 7         | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2         | 2      | 1.98%   |
| Toshiba MK2555GSX 250GB               | 2         | 2      | 1.98%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.98%   |
| Seagate ST320LT012-9WS14C 320GB       | 2         | 3      | 1.98%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 1.98%   |
| Seagate ST1000DM010-2EP102 1TB        | 2         | 2      | 1.98%   |
| Seagate ST1000DM003-1ER162 1TB        | 2         | 4      | 1.98%   |
| ASMedia AS2115 4TB                    | 2         | 2      | 1.98%   |
| WDC WD7502AAEX-00Y9A0 752GB           | 1         | 1      | 0.99%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000LPCX-22VHAT0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 0.99%   |
| WDC WD3200AAJS-08L7A0 320GB           | 1         | 1      | 0.99%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 1      | 0.99%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1         | 1      | 0.99%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 0.99%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10EZEX-60M2NA0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.99%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 0.99%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 2      | 0.99%   |
| WDC WD10 EZEX-08WN4A0 1TB             | 1         | 1      | 0.99%   |
| WDC WD Green 2.5 480GB SSD            | 1         | 1      | 0.99%   |
| WDC WD Blue SA510 2.5 500GB           | 1         | 2      | 0.99%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 0.99%   |
| Toshiba MQ01ABF050M 500GB             | 1         | 1      | 0.99%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 0.99%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 0.99%   |
| Toshiba MK4058GSX 400GB               | 1         | 1      | 0.99%   |
| Toshiba MK3261GSYN 320GB              | 1         | 1      | 0.99%   |
| Toshiba MK3261GSY 320GB               | 1         | 1      | 0.99%   |
| TARGET SSD 128G                       | 1         | 1      | 0.99%   |
| SK hynix SC308 SATA 256GB SSD         | 1         | 1      | 0.99%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 1         | 1      | 0.99%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 0.99%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD | 1         | 1      | 0.99%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 36     | 32%     |
| WDC                 | 19        | 21     | 19%     |
| Toshiba             | 10        | 11     | 10%     |
| SK hynix            | 6         | 6      | 6%      |
| Hitachi             | 5         | 5      | 5%      |
| Samsung Electronics | 4         | 4      | 4%      |
| Kingston            | 4         | 4      | 4%      |
| HGST                | 3         | 3      | 3%      |
| Crucial             | 2         | 2      | 2%      |
| ASMedia             | 2         | 2      | 2%      |
| TARGET              | 1         | 1      | 1%      |
| SanDisk             | 1         | 2      | 1%      |
| SAGE                | 1         | 1      | 1%      |
| SABRENT             | 1         | 1      | 1%      |
| OWC                 | 1         | 1      | 1%      |
| Maxtor              | 1         | 1      | 1%      |
| LITEONIT            | 1         | 1      | 1%      |
| Intel               | 1         | 1      | 1%      |
| Corsair             | 1         | 1      | 1%      |
| China               | 1         | 1      | 1%      |
| Apple               | 1         | 1      | 1%      |
| ADATA Technology    | 1         | 1      | 1%      |
| A-DATA Technology   | 1         | 1      | 1%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 36     | 43.24%  |
| WDC                 | 17        | 18     | 22.97%  |
| Toshiba             | 10        | 11     | 13.51%  |
| Hitachi             | 5         | 5      | 6.76%   |
| HGST                | 3         | 3      | 4.05%   |
| Samsung Electronics | 2         | 2      | 2.7%    |
| ASMedia             | 2         | 2      | 2.7%    |
| SAGE                | 1         | 1      | 1.35%   |
| SABRENT             | 1         | 1      | 1.35%   |
| Maxtor              | 1         | 1      | 1.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 73        | 80     | 74.49%  |
| SSD  | 22        | 25     | 22.45%  |
| NVMe | 3         | 3      | 3.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 378       | 663    | 67.86%  |
| Malfunc  | 95        | 108    | 17.06%  |
| Detected | 82        | 144    | 14.72%  |
| Fixed    | 1         | 1      | 0.18%   |
| Failed   | 1         | 1      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 299       | 46.21%  |
| AMD                                     | 91        | 14.06%  |
| Samsung Electronics                     | 70        | 10.82%  |
| SanDisk                                 | 39        | 6.03%   |
| Kingston Technology Company             | 19        | 2.94%   |
| SK hynix                                | 16        | 2.47%   |
| Micron/Crucial Technology               | 15        | 2.32%   |
| ASMedia Technology                      | 15        | 2.32%   |
| Phison Electronics                      | 14        | 2.16%   |
| Micron Technology                       | 12        | 1.85%   |
| Toshiba America Info Systems            | 10        | 1.55%   |
| KIOXIA                                  | 8         | 1.24%   |
| ADATA Technology                        | 8         | 1.24%   |
| Realtek Semiconductor                   | 5         | 0.77%   |
| Silicon Motion                          | 4         | 0.62%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.62%   |
| Shenzhen Longsys Electronics            | 3         | 0.46%   |
| JMicron Technology                      | 3         | 0.46%   |
| Yangtze Memory Technologies             | 2         | 0.31%   |
| Nvidia                                  | 2         | 0.31%   |
| Marvell Technology Group                | 2         | 0.31%   |
| VIA Technologies                        | 1         | 0.15%   |
| Union Memory (Shenzhen)                 | 1         | 0.15%   |
| Shenzhen Unionmemory Information System | 1         | 0.15%   |
| Seagate Technology                      | 1         | 0.15%   |
| Biwin Storage Technology                | 1         | 0.15%   |
| Apple                                   | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 65        | 9.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 3.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24        | 3.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 23        | 3.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 20        | 2.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 2.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17        | 2.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 2.37%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 15        | 2.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14        | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 14        | 1.96%   |
| Intel SATA Controller [RAID mode]                                              | 12        | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 1.68%   |
| Intel Tiger Lake-LP SATA Controller                                            | 11        | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11        | 1.54%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.4%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 1.26%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 8         | 1.12%   |
| Phison E12 NVMe Controller                                                     | 8         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 0.98%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 7         | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 0.98%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 6         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 0.84%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 0.84%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 6         | 0.84%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 5         | 0.7%    |
| Intel SSD 660P Series                                                          | 5         | 0.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 0.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 337       | 52.49%  |
| NVMe | 229       | 35.67%  |
| RAID | 61        | 9.5%    |
| IDE  | 15        | 2.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 344       | 74.14%  |
| AMD    | 120       | 25.86%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 10        | 2.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 1.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz       | 7         | 1.5%    |
| AMD Ryzen 5 5600H with Radeon Graphics  | 7         | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 1.29%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 6         | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 1.29%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 6         | 1.29%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 6         | 1.29%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 1.07%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 5         | 1.07%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 5         | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 0.86%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 4         | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 0.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 0.86%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 4         | 0.86%   |
| Intel 12th Gen Core i5-12450H           | 4         | 0.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 4         | 0.86%   |
| AMD Ryzen 5 3600 6-Core Processor       | 4         | 0.86%   |
| Intel N100                              | 3         | 0.64%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 3         | 0.64%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 3         | 0.64%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 3         | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 3         | 0.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3         | 0.64%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 3         | 0.64%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 3         | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 3         | 0.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 0.64%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 3         | 0.64%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz | 3         | 0.64%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 3         | 0.64%   |
| AMD Ryzen 7 5800X3D 8-Core Processor    | 3         | 0.64%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 3         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 102       | 21.94%  |
| Intel Core i7           | 91        | 19.57%  |
| Other                   | 62        | 13.33%  |
| AMD Ryzen 5             | 53        | 11.4%   |
| Intel Core i3           | 37        | 7.96%   |
| AMD Ryzen 7             | 28        | 6.02%   |
| Intel Core 2 Duo        | 12        | 2.58%   |
| Intel Celeron           | 11        | 2.37%   |
| Intel Xeon              | 9         | 1.94%   |
| Intel Pentium           | 8         | 1.72%   |
| AMD Ryzen 3             | 7         | 1.51%   |
| Intel Core i9           | 4         | 0.86%   |
| AMD FX                  | 4         | 0.86%   |
| AMD A6                  | 4         | 0.86%   |
| AMD Ryzen 9             | 3         | 0.65%   |
| AMD Ryzen 7 PRO         | 3         | 0.65%   |
| AMD Athlon              | 3         | 0.65%   |
| Intel Pentium Dual-Core | 2         | 0.43%   |
| Intel Core 2 Quad       | 2         | 0.43%   |
| AMD E1                  | 2         | 0.43%   |
| AMD A8                  | 2         | 0.43%   |
| AMD A4                  | 2         | 0.43%   |
| Intel Pentium Silver    | 1         | 0.22%   |
| Intel Genuine           | 1         | 0.22%   |
| Intel Core m5           | 1         | 0.22%   |
| Intel Core M            | 1         | 0.22%   |
| Intel Atom              | 1         | 0.22%   |
| AMD Turion II Dual-Core | 1         | 0.22%   |
| AMD Ryzen Threadripper  | 1         | 0.22%   |
| AMD Ryzen 5 PRO         | 1         | 0.22%   |
| AMD Phenom II           | 1         | 0.22%   |
| AMD E2                  | 1         | 0.22%   |
| AMD E                   | 1         | 0.22%   |
| AMD C-60                | 1         | 0.22%   |
| AMD Athlon II X3        | 1         | 0.22%   |
| AMD A12                 | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 177       | 38.06%  |
| 2      | 148       | 31.83%  |
| 6      | 70        | 15.05%  |
| 8      | 43        | 9.25%   |
| 12     | 9         | 1.94%   |
| 16     | 6         | 1.29%   |
| 10     | 4         | 0.86%   |
| 3      | 3         | 0.65%   |
| 24     | 2         | 0.43%   |
| 14     | 2         | 0.43%   |
| 28     | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 462       | 99.57%  |
| 2      | 2         | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 371       | 79.78%  |
| 1      | 94        | 20.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 464       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 289       | 61.1%   |
| 0x08108109 | 12        | 2.54%   |
| 0x906ea    | 8         | 1.69%   |
| 0x0a50000c | 8         | 1.69%   |
| 0x08701021 | 8         | 1.69%   |
| 0x806c1    | 7         | 1.48%   |
| 0x806ec    | 6         | 1.27%   |
| 0x506e3    | 6         | 1.27%   |
| 0x306a9    | 6         | 1.27%   |
| 0x0a50000d | 6         | 1.27%   |
| 0x806e9    | 5         | 1.06%   |
| 0x0a404102 | 5         | 1.06%   |
| 0x906e9    | 4         | 0.85%   |
| 0x306c3    | 4         | 0.85%   |
| 0x0a201025 | 4         | 0.85%   |
| 0x0a201016 | 4         | 0.85%   |
| 0x08701030 | 4         | 0.85%   |
| 0x08608103 | 4         | 0.85%   |
| 0x08600106 | 4         | 0.85%   |
| 0x08108102 | 4         | 0.85%   |
| 0x0800820d | 4         | 0.85%   |
| 0x806eb    | 3         | 0.63%   |
| 0x206a7    | 3         | 0.63%   |
| 0x0a20120a | 3         | 0.63%   |
| 0x0810100b | 3         | 0.63%   |
| 0x06006705 | 3         | 0.63%   |
| 0x906ed    | 2         | 0.42%   |
| 0x906eb    | 2         | 0.42%   |
| 0x706a8    | 2         | 0.42%   |
| 0x40651    | 2         | 0.42%   |
| 0x106e5    | 2         | 0.42%   |
| 0x1067a    | 2         | 0.42%   |
| 0x0a201204 | 2         | 0.42%   |
| 0x08608104 | 2         | 0.42%   |
| 0x08001138 | 2         | 0.42%   |
| 0x0600611a | 2         | 0.42%   |
| 0x0500010d | 2         | 0.42%   |
| 0x05000101 | 2         | 0.42%   |
| 0x03000027 | 2         | 0.42%   |
| 0x010000c8 | 2         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 87        | 18.71%  |
| Haswell          | 46        | 9.89%   |
| Zen 3            | 31        | 6.67%   |
| TigerLake        | 30        | 6.45%   |
| IvyBridge        | 28        | 6.02%   |
| Zen+             | 23        | 4.95%   |
| Zen 2            | 23        | 4.95%   |
| SandyBridge      | 23        | 4.95%   |
| Skylake          | 22        | 4.73%   |
| Alderlake Hybrid | 20        | 4.3%    |
| IceLake          | 18        | 3.87%   |
| Broadwell        | 16        | 3.44%   |
| Unknown          | 16        | 3.44%   |
| Penryn           | 13        | 2.8%    |
| Goldmont plus    | 9         | 1.94%   |
| CometLake        | 9         | 1.94%   |
| Zen              | 7         | 1.51%   |
| Excavator        | 6         | 1.29%   |
| Piledriver       | 5         | 1.08%   |
| Nehalem          | 5         | 1.08%   |
| Westmere         | 4         | 0.86%   |
| Silvermont       | 4         | 0.86%   |
| Gracemont        | 4         | 0.86%   |
| Core             | 4         | 0.86%   |
| Bobcat           | 4         | 0.86%   |
| K10              | 3         | 0.65%   |
| K10 Llano        | 2         | 0.43%   |
| Jaguar           | 2         | 0.43%   |
| Tremont          | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 265       | 46.57%  |
| Nvidia            | 171       | 30.05%  |
| AMD               | 132       | 23.2%   |
| ASPEED Technology | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 20        | 3.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17        | 2.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 17        | 2.95%   |
| Intel UHD Graphics 620                                                      | 15        | 2.6%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 15        | 2.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 13        | 2.25%   |
| Intel HD Graphics 620                                                       | 13        | 2.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 13        | 2.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13        | 2.25%   |
| Intel HD Graphics 5500                                                      | 11        | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 11        | 1.91%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 10        | 1.73%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 9         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 9         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 9         | 1.56%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 9         | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 8         | 1.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 1.21%   |
| AMD Lucienne                                                                | 7         | 1.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6         | 1.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 6         | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6         | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 6         | 1.04%   |
| AMD Rembrandt [Radeon 680M]                                                 | 6         | 1.04%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 6         | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                               | 5         | 0.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 5         | 0.87%   |
| Intel HD Graphics 630                                                       | 5         | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 0.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                               | 4         | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4         | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4         | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4         | 0.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 0.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 0.69%   |
| Intel HD Graphics 530                                                       | 4         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 168       | 36.13%  |
| 1 x AMD         | 105       | 22.58%  |
| Intel + Nvidia  | 79        | 16.99%  |
| 1 x Nvidia      | 76        | 16.34%  |
| AMD + Nvidia    | 13        | 2.8%    |
| Intel + AMD     | 10        | 2.15%   |
| 2 x Intel       | 7         | 1.51%   |
| 2 x AMD         | 4         | 0.86%   |
| 2 x Nvidia      | 2         | 0.43%   |
| Nvidia + ASPEED | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 384       | 81.88%  |
| Proprietary | 82        | 17.48%  |
| Unknown     | 3         | 0.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 239       | 51.07%  |
| 1.01-2.0   | 63        | 13.46%  |
| 0.01-0.5   | 43        | 9.19%   |
| 7.01-8.0   | 39        | 8.33%   |
| 3.01-4.0   | 36        | 7.69%   |
| 5.01-6.0   | 15        | 3.21%   |
| 0.51-1.0   | 14        | 2.99%   |
| 8.01-16.0  | 10        | 2.14%   |
| 2.01-3.0   | 7         | 1.5%    |
| 16.01-24.0 | 2         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 70        | 13.46%  |
| AU Optronics            | 60        | 11.54%  |
| Samsung Electronics     | 58        | 11.15%  |
| Chimei Innolux          | 55        | 10.58%  |
| LG Display              | 42        | 8.08%   |
| Goldstar                | 26        | 5%      |
| Hewlett-Packard         | 21        | 4.04%   |
| Apple                   | 16        | 3.08%   |
| Dell                    | 15        | 2.88%   |
| Acer                    | 13        | 2.5%    |
| Ancor Communications    | 11        | 2.12%   |
| Unknown                 | 10        | 1.92%   |
| Sharp                   | 10        | 1.92%   |
| BenQ                    | 10        | 1.92%   |
| AOC                     | 8         | 1.54%   |
| Philips                 | 7         | 1.35%   |
| PANDA                   | 7         | 1.35%   |
| MSI                     | 6         | 1.15%   |
| Lenovo                  | 6         | 1.15%   |
| ASUSTek Computer        | 6         | 1.15%   |
| Iiyama                  | 5         | 0.96%   |
| Sony                    | 4         | 0.77%   |
| Vizio                   | 3         | 0.58%   |
| CSO                     | 3         | 0.58%   |
| Chi Mei Optoelectronics | 3         | 0.58%   |
| Westinghouse            | 2         | 0.38%   |
| TMX                     | 2         | 0.38%   |
| Sceptre Tech            | 2         | 0.38%   |
| RTK                     | 2         | 0.38%   |
| HKC                     | 2         | 0.38%   |
| Hitachi                 | 2         | 0.38%   |
| Gigabyte Technology     | 2         | 0.38%   |
| Fujitsu Siemens         | 2         | 0.38%   |
| Eizo                    | 2         | 0.38%   |
| Unknown                 | 2         | 0.38%   |
| Yeyian                  | 1         | 0.19%   |
| Yamaha                  | 1         | 0.19%   |
| Wacom                   | 1         | 0.19%   |
| ViewSonic               | 1         | 0.19%   |
| UTV                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 9         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 6         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 4         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 4         | 0.75%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 4         | 0.75%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 3         | 0.56%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 3         | 0.56%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                   | 3         | 0.56%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.56%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 3         | 0.56%   |
| Sharp LQ134N1JW55 SHP1558 1920x1200 288x180mm 13.4-inch                 | 2         | 0.38%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2         | 0.38%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch   | 2         | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2         | 0.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 2         | 0.38%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 2         | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 0.38%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch            | 2         | 0.38%   |
| Hewlett-Packard 2310 HWP288E 1920x1080 510x287mm 23.0-inch              | 2         | 0.38%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                    | 2         | 0.38%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                | 2         | 0.38%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch                | 2         | 0.38%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                   | 2         | 0.38%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2         | 0.38%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                  | 2         | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2         | 0.38%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                      | 2         | 0.38%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch        | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.38%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                   | 2         | 0.38%   |
| BOE LCD Monitor BOE09AE 1920x1080 309x174mm 14.0-inch                   | 2         | 0.38%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 2         | 0.38%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                    | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 250       | 49.9%   |
| 1366x768 (WXGA)    | 74        | 14.77%  |
| 3840x2160 (4K)     | 34        | 6.79%   |
| 2560x1440 (QHD)    | 27        | 5.39%   |
| 1600x900 (HD+)     | 16        | 3.19%   |
| 1920x1200 (WUXGA)  | 12        | 2.4%    |
| 3440x1440          | 11        | 2.2%    |
| 2288x1287          | 9         | 1.8%    |
| 2560x1080          | 8         | 1.6%    |
| 1680x1050 (WSXGA+) | 8         | 1.6%    |
| 2560x1600          | 7         | 1.4%    |
| 1440x900 (WXGA+)   | 7         | 1.4%    |
| 1280x800 (WXGA)    | 7         | 1.4%    |
| 1360x768           | 5         | 1%      |
| 2160x1440          | 4         | 0.8%    |
| 1920x540           | 4         | 0.8%    |
| 1280x1024 (SXGA)   | 4         | 0.8%    |
| 2880x1800          | 3         | 0.6%    |
| 3840x1080          | 2         | 0.4%    |
| 3200x1800 (QHD+)   | 2         | 0.4%    |
| 3840x2400          | 1         | 0.2%    |
| 3200x2000          | 1         | 0.2%    |
| 2880x1920          | 1         | 0.2%    |
| 2256x1504          | 1         | 0.2%    |
| 1920x1280          | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 145       | 27.72%  |
| 13      | 56        | 10.71%  |
| 14      | 47        | 8.99%   |
| 24      | 40        | 7.65%   |
| 27      | 36        | 6.88%   |
| 23      | 28        | 5.35%   |
| 31      | 26        | 4.97%   |
| 21      | 24        | 4.59%   |
| 17      | 19        | 3.63%   |
| 34      | 13        | 2.49%   |
| Unknown | 10        | 1.91%   |
| 142     | 9         | 1.72%   |
| 16      | 9         | 1.72%   |
| 84      | 7         | 1.34%   |
| 19      | 5         | 0.96%   |
| 18      | 5         | 0.96%   |
| 54      | 4         | 0.76%   |
| 28      | 4         | 0.76%   |
| 11      | 4         | 0.76%   |
| 40      | 3         | 0.57%   |
| 29      | 3         | 0.57%   |
| 22      | 3         | 0.57%   |
| 20      | 3         | 0.57%   |
| 12      | 3         | 0.57%   |
| 72      | 2         | 0.38%   |
| 69      | 2         | 0.38%   |
| 58      | 2         | 0.38%   |
| 32      | 2         | 0.38%   |
| 52      | 1         | 0.19%   |
| 48      | 1         | 0.19%   |
| 46      | 1         | 0.19%   |
| 41      | 1         | 0.19%   |
| 39      | 1         | 0.19%   |
| 35      | 1         | 0.19%   |
| 33      | 1         | 0.19%   |
| 26      | 1         | 0.19%   |
| 10      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 223       | 43.05%  |
| 501-600        | 94        | 18.15%  |
| 401-500        | 39        | 7.53%   |
| 201-300        | 37        | 7.14%   |
| 601-700        | 36        | 6.95%   |
| 351-400        | 27        | 5.21%   |
| 701-800        | 16        | 3.09%   |
| 1501-2000      | 11        | 2.12%   |
| Unknown        | 10        | 1.93%   |
| More than 2000 | 9         | 1.74%   |
| 1001-1500      | 9         | 1.74%   |
| 801-900        | 6         | 1.16%   |
| 901-1000       | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 380       | 80.34%  |
| 16/10   | 44        | 9.3%    |
| 21/9    | 19        | 4.02%   |
| 1.00    | 9         | 1.9%    |
| 3/2     | 8         | 1.69%   |
| Unknown | 6         | 1.27%   |
| 5/4     | 4         | 0.85%   |
| 32/9    | 3         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 146       | 28.24%  |
| 81-90          | 83        | 16.05%  |
| 201-250        | 78        | 15.09%  |
| 351-500        | 45        | 8.7%    |
| 301-350        | 38        | 7.35%   |
| More than 1000 | 27        | 5.22%   |
| 71-80          | 20        | 3.87%   |
| 121-130        | 18        | 3.48%   |
| 151-200        | 16        | 3.09%   |
| 251-300        | 10        | 1.93%   |
| Unknown        | 10        | 1.93%   |
| 501-1000       | 7         | 1.35%   |
| 111-120        | 6         | 1.16%   |
| 51-60          | 4         | 0.77%   |
| 61-70          | 3         | 0.58%   |
| 141-150        | 3         | 0.58%   |
| 41-50          | 1         | 0.19%   |
| 131-140        | 1         | 0.19%   |
| 91-100         | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 171       | 33.79%  |
| 51-100        | 136       | 26.88%  |
| 101-120       | 119       | 23.52%  |
| 161-240       | 35        | 6.92%   |
| 1-50          | 23        | 4.55%   |
| More than 240 | 12        | 2.37%   |
| Unknown       | 10        | 1.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 386       | 82.66%  |
| 2     | 71        | 15.2%   |
| 3     | 7         | 1.5%    |
| 0     | 3         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 269       | 38.59%  |
| Intel                             | 240       | 34.43%  |
| Qualcomm Atheros                  | 65        | 9.33%   |
| Broadcom                          | 33        | 4.73%   |
| MediaTek                          | 14        | 2.01%   |
| Broadcom Limited                  | 12        | 1.72%   |
| TP-Link                           | 8         | 1.15%   |
| ASIX Electronics                  | 6         | 0.86%   |
| OPPO Electronics                  | 5         | 0.72%   |
| Ralink Technology                 | 4         | 0.57%   |
| Ralink                            | 4         | 0.57%   |
| Qualcomm                          | 4         | 0.57%   |
| Aquantia                          | 4         | 0.57%   |
| Marvell Technology Group          | 3         | 0.43%   |
| Sierra Wireless                   | 2         | 0.29%   |
| Samsung Electronics               | 2         | 0.29%   |
| Qualcomm Atheros Communications   | 2         | 0.29%   |
| Nvidia                            | 2         | 0.29%   |
| Microsoft                         | 2         | 0.29%   |
| Ericsson Business Mobile Networks | 2         | 0.29%   |
| ASUSTek Computer                  | 2         | 0.29%   |
| T & A Mobile Phones               | 1         | 0.14%   |
| QinHeng Electronics               | 1         | 0.14%   |
| NetGear                           | 1         | 0.14%   |
| Motorola PCS                      | 1         | 0.14%   |
| Microchip Technology              | 1         | 0.14%   |
| Lenovo                            | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |
| Google                            | 1         | 0.14%   |
| DisplayLink                       | 1         | 0.14%   |
| Dell                              | 1         | 0.14%   |
| D-Link                            | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 177       | 21.51%  |
| Intel Wi-Fi 6 AX201                                                    | 23        | 2.79%   |
| Intel Wi-Fi 6 AX200                                                    | 22        | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 20        | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 20        | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 17        | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                      | 17        | 2.07%   |
| Intel Wireless 8265 / 8275                                             | 15        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 14        | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 12        | 1.46%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 1.34%   |
| Intel Wireless 7265                                                    | 10        | 1.22%   |
| Intel Ethernet Connection (2) I219-V                                   | 10        | 1.22%   |
| Intel Ethernet Controller I225-V                                       | 9         | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 0.97%   |
| Intel Wireless 8260                                                    | 8         | 0.97%   |
| Intel Wireless 7260                                                    | 8         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 7         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7         | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 0.73%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 6         | 0.73%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.73%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 6         | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.61%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 0.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 5         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 199       | 48.89%  |
| Realtek Semiconductor           | 80        | 19.66%  |
| Qualcomm Atheros                | 47        | 11.55%  |
| Broadcom                        | 26        | 6.39%   |
| MediaTek                        | 14        | 3.44%   |
| Broadcom Limited                | 11        | 2.7%    |
| TP-Link                         | 8         | 1.97%   |
| Ralink Technology               | 4         | 0.98%   |
| Ralink                          | 4         | 0.98%   |
| Sierra Wireless                 | 2         | 0.49%   |
| Qualcomm Atheros Communications | 2         | 0.49%   |
| Microsoft                       | 2         | 0.49%   |
| Marvell Technology Group        | 2         | 0.49%   |
| ASUSTek Computer                | 2         | 0.49%   |
| Qualcomm                        | 1         | 0.25%   |
| NetGear                         | 1         | 0.25%   |
| Dell                            | 1         | 0.25%   |
| D-Link                          | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 23        | 5.62%   |
| Intel Wi-Fi 6 AX200                                                  | 22        | 5.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 20        | 4.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 17        | 4.16%   |
| Intel Wireless 8265 / 8275                                           | 15        | 3.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 12        | 2.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 12        | 2.93%   |
| Intel Wireless 7265                                                  | 10        | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 9         | 2.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 8         | 1.96%   |
| Intel Wireless 8260                                                  | 8         | 1.96%   |
| Intel Wireless 7260                                                  | 8         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 8         | 1.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 7         | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 7         | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 7         | 1.71%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 7         | 1.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 7         | 1.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 7         | 1.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 7         | 1.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 6         | 1.47%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 6         | 1.47%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 6         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 1.22%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 5         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 4         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 0.98%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 4         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 4         | 0.98%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 4         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 0.98%   |
| Intel Centrino Wireless-N 2230                                       | 4         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 3         | 0.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 3         | 0.73%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 0.73%   |
| Intel Wireless 3165                                                  | 3         | 0.73%   |
| Intel Wireless 3160                                                  | 3         | 0.73%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 3         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 228       | 57%     |
| Intel                    | 107       | 26.75%  |
| Qualcomm Atheros         | 22        | 5.5%    |
| Broadcom                 | 15        | 3.75%   |
| ASIX Electronics         | 6         | 1.5%    |
| OPPO Electronics         | 5         | 1.25%   |
| Aquantia                 | 4         | 1%      |
| Qualcomm                 | 3         | 0.75%   |
| Nvidia                   | 2         | 0.5%    |
| Motorola PCS             | 1         | 0.25%   |
| Microchip Technology     | 1         | 0.25%   |
| Marvell Technology Group | 1         | 0.25%   |
| Lenovo                   | 1         | 0.25%   |
| Huawei Technologies      | 1         | 0.25%   |
| Hewlett-Packard          | 1         | 0.25%   |
| DisplayLink              | 1         | 0.25%   |
| Broadcom Limited         | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 177       | 43.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 20        | 4.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 19        | 4.67%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 17        | 4.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 14        | 3.44%   |
| Intel I211 Gigabit Network Connection                                             | 11        | 2.7%    |
| Intel Ethernet Connection (2) I219-V                                              | 10        | 2.46%   |
| Intel Ethernet Controller I225-V                                                  | 9         | 2.21%   |
| Intel Ethernet Connection I217-LM                                                 | 6         | 1.47%   |
| ASIX AX88179 Gigabit Ethernet                                                     | 6         | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 5         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                                             | 5         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                 | 5         | 1.23%   |
| Realtek Killer E2600 GbE Controller                                               | 4         | 0.98%   |
| OPPO OnePlus Nord 4                                                               | 4         | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                              | 4         | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                   | 4         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                             | 3         | 0.74%   |
| Intel Ethernet Connection I219-LM                                                 | 3         | 0.74%   |
| Intel Ethernet Connection I218-LM                                                 | 3         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                              | 3         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                              | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                             | 3         | 0.74%   |
| Qualcomm POCO F3                                                                  | 2         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 2         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                         | 2         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                        | 2         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 2         | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                    | 2         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                             | 2         | 0.49%   |
| Intel Ethernet Connection (3) I218-V                                              | 2         | 0.49%   |
| Intel Ethernet Connection (13) I219-V                                             | 2         | 0.49%   |
| Intel Ethernet Connection (11) I219-V                                             | 2         | 0.49%   |
| Intel 82579V Gigabit Network Connection                                           | 2         | 0.49%   |
| Intel 82567LM Gigabit Network Connection                                          | 2         | 0.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                                 | 2         | 0.49%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 2         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                             | 1         | 0.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                         | 1         | 0.25%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                     | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 388       | 50.19%  |
| Ethernet | 378       | 48.9%   |
| Modem    | 7         | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 276       | 59.35%  |
| Ethernet | 189       | 40.65%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 252       | 54.08%  |
| 1     | 194       | 41.63%  |
| 3     | 14        | 3%      |
| 0     | 4         | 0.86%   |
| 8     | 1         | 0.21%   |
| 4     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 314       | 67.09%  |
| Yes  | 154       | 32.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 177       | 50.57%  |
| Realtek Semiconductor           | 43        | 12.29%  |
| Qualcomm Atheros Communications | 22        | 6.29%   |
| Apple                           | 18        | 5.14%   |
| IMC Networks                    | 16        | 4.57%   |
| Cambridge Silicon Radio         | 13        | 3.71%   |
| Broadcom                        | 13        | 3.71%   |
| Lite-On Technology              | 9         | 2.57%   |
| Foxconn / Hon Hai               | 8         | 2.29%   |
| ASUSTek Computer                | 7         | 2%      |
| Realtek                         | 6         | 1.71%   |
| MediaTek                        | 4         | 1.14%   |
| TP-Link                         | 3         | 0.86%   |
| Dell                            | 3         | 0.86%   |
| Toshiba                         | 2         | 0.57%   |
| Marvell Semiconductor           | 2         | 0.57%   |
| Alps Electric                   | 2         | 0.57%   |
| USI                             | 1         | 0.29%   |
| Taiyo Yuden                     | 1         | 0.29%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 47        | 13.43%  |
| Intel AX201 Bluetooth                               | 40        | 11.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 37        | 10.57%  |
| Realtek Bluetooth Radio                             | 26        | 7.43%   |
| Intel AX200 Bluetooth                               | 22        | 6.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 4.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 3.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 2.86%   |
| Apple Bluetooth Host Controller                     | 9         | 2.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 2%      |
| Intel AX210 Bluetooth                               | 7         | 2%      |
| Apple Bluetooth USB Host Controller                 | 7         | 2%      |
| Realtek Bluetooth Radio                             | 6         | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.71%   |
| Intel AX211 Bluetooth                               | 6         | 1.71%   |
| IMC Networks Wireless_Device                        | 6         | 1.71%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.43%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 1.14%   |
| MediaTek Wireless_Device                            | 4         | 1.14%   |
| Lite-On Bluetooth Device                            | 4         | 1.14%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 3         | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.57%   |
| IMC Networks Bluetooth Device                       | 2         | 0.57%   |
| IMC Networks BCM20702A0                             | 2         | 0.57%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.57%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 0.57%   |
| ASUS Bluetooth Radio                                | 2         | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.57%   |
| USI Bluetooth Device                                | 1         | 0.29%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.29%   |
| Toshiba BCM43142A0                                  | 1         | 0.29%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.29%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.29%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.29%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 342       | 50%     |
| AMD                                          | 145       | 21.2%   |
| Nvidia                                       | 123       | 17.98%  |
| C-Media Electronics                          | 12        | 1.75%   |
| Generalplus Technology                       | 5         | 0.73%   |
| Razer USA                                    | 4         | 0.58%   |
| Corsair                                      | 4         | 0.58%   |
| ASUSTek Computer                             | 4         | 0.58%   |
| Logitech                                     | 3         | 0.44%   |
| Kingston Technology                          | 3         | 0.44%   |
| GN Netcom                                    | 3         | 0.44%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.29%   |
| Realtek Semiconductor                        | 2         | 0.29%   |
| PreSonus Audio Electronics                   | 2         | 0.29%   |
| JMTek                                        | 2         | 0.29%   |
| Jieli Technology                             | 2         | 0.29%   |
| Hewlett-Packard                              | 2         | 0.29%   |
| Elgato Systems                               | 2         | 0.29%   |
| Barco Display Systems                        | 2         | 0.29%   |
| Apple                                        | 2         | 0.29%   |
| Trust                                        | 1         | 0.15%   |
| Tenx Technology                              | 1         | 0.15%   |
| TC Electronic                                | 1         | 0.15%   |
| SteelSeries ApS                              | 1         | 0.15%   |
| Soundprese                                   | 1         | 0.15%   |
| Sony                                         | 1         | 0.15%   |
| Shenzhen Riitek Technology                   | 1         | 0.15%   |
| Samsung Electronics                          | 1         | 0.15%   |
| Plantronics                                  | 1         | 0.15%   |
| Mark of the Unicorn                          | 1         | 0.15%   |
| Lenovo                                       | 1         | 0.15%   |
| JBL                                          | 1         | 0.15%   |
| Focusrite-Novation                           | 1         | 0.15%   |
| Fifine Microphones                           | 1         | 0.15%   |
| ELMCU                                        | 1         | 0.15%   |
| Digidesign                                   | 1         | 0.15%   |
| Astro Gaming                                 | 1         | 0.15%   |
| Arturia                                      | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 60        | 7.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 38        | 4.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 3.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 30        | 3.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 29        | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 3.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 24        | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 2.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18        | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 1.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.82%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 14        | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 1.46%   |
| Intel 200 Series PCH HD Audio                                              | 12        | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.33%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.21%   |
| AMD Navi 10 HDMI Audio                                                     | 10        | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 1.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9         | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 0.97%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 0.85%   |
| AMD FCH Azalia Controller                                                  | 7         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.73%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 112       | 21.17%  |
| SK hynix                     | 111       | 20.98%  |
| Micron Technology            | 68        | 12.85%  |
| Crucial                      | 38        | 7.18%   |
| Kingston                     | 36        | 6.81%   |
| Corsair                      | 30        | 5.67%   |
| G.Skill                      | 29        | 5.48%   |
| Unknown                      | 24        | 4.54%   |
| Ramaxel Technology           | 13        | 2.46%   |
| Team                         | 10        | 1.89%   |
| Elpida                       | 8         | 1.51%   |
| A-DATA Technology            | 8         | 1.51%   |
| Unknown                      | 5         | 0.95%   |
| Nanya Technology             | 3         | 0.57%   |
| GOODRAM                      | 3         | 0.57%   |
| Timetec                      | 2         | 0.38%   |
| Smart                        | 2         | 0.38%   |
| PNY                          | 2         | 0.38%   |
| Patriot Memory (PDP Systems) | 2         | 0.38%   |
| Patriot                      | 2         | 0.38%   |
| KingFast                     | 2         | 0.38%   |
| GeIL                         | 2         | 0.38%   |
| Unknown (ABCD)               | 1         | 0.19%   |
| Unifosa                      | 1         | 0.19%   |
| Transcend                    | 1         | 0.19%   |
| Smart Brazil                 | 1         | 0.19%   |
| Silicon Power                | 1         | 0.19%   |
| Reboto                       | 1         | 0.19%   |
| Ramos Technology             | 1         | 0.19%   |
| Qimonda                      | 1         | 0.19%   |
| Magnum Tech                  | 1         | 0.19%   |
| Kllisre                      | 1         | 0.19%   |
| Kimtigo                      | 1         | 0.19%   |
| Juhor                        | 1         | 0.19%   |
| Heoriady                     | 1         | 0.19%   |
| Guangzhou MiaoYuanJi         | 1         | 0.19%   |
| Goldkey                      | 1         | 0.19%   |
| Golden Empire                | 1         | 0.19%   |
| ChangXin Memory              | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s       | 9         | 1.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 8         | 1.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 7         | 1.26%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s | 6         | 1.08%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 6         | 1.08%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 6         | 1.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 6         | 1.08%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s          | 5         | 0.9%    |
| Unknown                                                        | 5         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 4         | 0.72%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 4         | 0.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 4         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 4         | 0.72%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 4         | 0.72%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 4         | 0.72%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s    | 4         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 4         | 0.72%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 4         | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s             | 3         | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 3         | 0.54%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 3         | 0.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 3         | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 0.54%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 3         | 0.54%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s         | 3         | 0.54%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 3         | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 3         | 0.54%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 3         | 0.54%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 2         | 0.36%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 2         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 2         | 0.36%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 2         | 0.36%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.36%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                   | 2         | 0.36%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 2         | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.36%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 243       | 54.98%  |
| DDR3    | 129       | 29.19%  |
| LPDDR4  | 16        | 3.62%   |
| DDR5    | 13        | 2.94%   |
| DDR2    | 11        | 2.49%   |
| LPDDR5  | 10        | 2.26%   |
| LPDDR3  | 9         | 2.04%   |
| SDRAM   | 6         | 1.36%   |
| Unknown | 3         | 0.68%   |
| DDR     | 2         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 258       | 57.98%  |
| DIMM         | 141       | 31.69%  |
| Row Of Chips | 41        | 9.21%   |
| Chip         | 3         | 0.67%   |
| Unknown      | 2         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 206       | 42.39%  |
| 4096  | 143       | 29.42%  |
| 16384 | 77        | 15.84%  |
| 2048  | 38        | 7.82%   |
| 32768 | 15        | 3.09%   |
| 1024  | 6         | 1.23%   |
| 24576 | 1         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 89        | 18.24%  |
| 2667    | 89        | 18.24%  |
| 1600    | 83        | 17.01%  |
| 2400    | 31        | 6.35%   |
| 1333    | 22        | 4.51%   |
| 2133    | 20        | 4.1%    |
| 3600    | 15        | 3.07%   |
| 6400    | 11        | 2.25%   |
| 4800    | 8         | 1.64%   |
| 3733    | 8         | 1.64%   |
| 3266    | 8         | 1.64%   |
| 1867    | 8         | 1.64%   |
| 1334    | 8         | 1.64%   |
| 800     | 7         | 1.43%   |
| 4267    | 6         | 1.23%   |
| 1866    | 6         | 1.23%   |
| 1067    | 6         | 1.23%   |
| 1066    | 6         | 1.23%   |
| 3000    | 5         | 1.02%   |
| 1800    | 5         | 1.02%   |
| 3800    | 4         | 0.82%   |
| 2933    | 4         | 0.82%   |
| 2666    | 4         | 0.82%   |
| Unknown | 4         | 0.82%   |
| 3400    | 3         | 0.61%   |
| 667     | 3         | 0.61%   |
| 4400    | 2         | 0.41%   |
| 4199    | 2         | 0.41%   |
| 3466    | 2         | 0.41%   |
| 2134    | 2         | 0.41%   |
| 2000    | 2         | 0.41%   |
| 1400    | 2         | 0.41%   |
| 8400    | 1         | 0.2%    |
| 7000    | 1         | 0.2%    |
| 6800    | 1         | 0.2%    |
| 6000    | 1         | 0.2%    |
| 5800    | 1         | 0.2%    |
| 4133    | 1         | 0.2%    |
| 3866    | 1         | 0.2%    |
| 3666    | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 37.5%   |
| Seiko Epson         | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |
| Canon               | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2870 Series                             | 1         | 12.5%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 12.5%   |
| Samsung ML-1640 Series Laser Printer                   | 1         | 12.5%   |
| HP LaserJet CP1525nw/x                                 | 1         | 12.5%   |
| HP DeskJet 2700 series                                 | 1         | 12.5%   |
| HP Deskjet 2050 J510                                   | 1         | 12.5%   |
| Canon PIXMA MG2500 Series                              | 1         | 12.5%   |
| Brother HL-5250DN Printer                              | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 2         | 66.67%  |
| Mustek Systems | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Mustek Systems BearPaw 2448 TA Plus | 1         | 33.33%  |
| Canon CanoScan LiDE 200             | 1         | 33.33%  |
| Canon CanoScan LiDE 110             | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 58        | 18.95%  |
| IMC Networks                           | 48        | 15.69%  |
| Bison Electronics                      | 26        | 8.5%    |
| Realtek Semiconductor                  | 25        | 8.17%   |
| Microdia                               | 24        | 7.84%   |
| Quanta                                 | 21        | 6.86%   |
| Sunplus Innovation Technology          | 14        | 4.58%   |
| Apple                                  | 13        | 4.25%   |
| Logitech                               | 9         | 2.94%   |
| Syntek                                 | 8         | 2.61%   |
| Lite-On Technology                     | 8         | 2.61%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.61%   |
| Luxvisions Innotech Limited            | 6         | 1.96%   |
| Suyin                                  | 5         | 1.63%   |
| SunplusIT                              | 3         | 0.98%   |
| Samsung Electronics                    | 3         | 0.98%   |
| Microsoft                              | 3         | 0.98%   |
| Generalplus Technology                 | 3         | 0.98%   |
| Ricoh                                  | 2         | 0.65%   |
| Creative Technology                    | 2         | 0.65%   |
| Unknown                                | 2         | 0.65%   |
| Z-Star Microelectronics                | 1         | 0.33%   |
| Y Media                                | 1         | 0.33%   |
| Sonix Technology                       | 1         | 0.33%   |
| Silicon Motion                         | 1         | 0.33%   |
| ShineTech                              | 1         | 0.33%   |
| Panasonic (Matsushita)                 | 1         | 0.33%   |
| OPPO Electronics                       | 1         | 0.33%   |
| LG Innotek                             | 1         | 0.33%   |
| Jieli Technology                       | 1         | 0.33%   |
| Intel                                  | 1         | 0.33%   |
| Aveo Technology                        | 1         | 0.33%   |
| Alpha Imaging Technology               | 1         | 0.33%   |
| ALi                                    | 1         | 0.33%   |
| Alcor Micro                            | 1         | 0.33%   |
| Acer                                   | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 17        | 5.5%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 15        | 4.85%   |
| IMC Networks Integrated Camera                       | 12        | 3.88%   |
| Realtek Integrated_Webcam_HD                         | 11        | 3.56%   |
| Syntek Integrated Camera                             | 8         | 2.59%   |
| Microdia Integrated_Webcam_HD                        | 8         | 2.59%   |
| Quanta HP TrueVision HD Camera                       | 7         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 7         | 2.27%   |
| Quanta HD User Facing                                | 6         | 1.94%   |
| Lite-On Integrated Camera                            | 6         | 1.94%   |
| Bison Integrated Camera                              | 6         | 1.94%   |
| IMC Networks HD Camera                               | 5         | 1.62%   |
| Chicony HD WebCam                                    | 5         | 1.62%   |
| Bison HD Webcam                                      | 5         | 1.62%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 4         | 1.29%   |
| Apple FaceTime HD Camera                             | 4         | 1.29%   |
| Samsung Galaxy series, misc. (MTP mode)              | 3         | 0.97%   |
| Realtek USB2.0 HD UVC WebCam                         | 3         | 0.97%   |
| Microdia Webcam Vitade AF                            | 3         | 0.97%   |
| Microdia USB 2.0 Camera                              | 3         | 0.97%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 0.97%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 0.97%   |
| Chicony HP TrueVision HD Camera                      | 3         | 0.97%   |
| Chicony EasyCamera                                   | 3         | 0.97%   |
| Bison Lenovo Integrated Webcam                       | 3         | 0.97%   |
| Sunplus Laptop Integrated Webcam FHD                 | 2         | 0.65%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 0.65%   |
| Sunplus Integrated_Webcam_FHD                        | 2         | 0.65%   |
| Realtek Integrated Webcam_HD                         | 2         | 0.65%   |
| Realtek EasyCamera                                   | 2         | 0.65%   |
| Quanta ov9734_techfront_camera                       | 2         | 0.65%   |
| Microdia Integrated Webcam                           | 2         | 0.65%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.65%   |
| Logitech BRIO Ultra HD Webcam                        | 2         | 0.65%   |
| IMC Networks VGA UVC WebCam                          | 2         | 0.65%   |
| Generalplus GENERAL WEBCAM                           | 2         | 0.65%   |
| Creative Live! Cam Sync 1080p V2                     | 2         | 0.65%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.65%   |
| Chicony USB 2.0 Camera                               | 2         | 0.65%   |
| Chicony Integrated IR Camera                         | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 32.08%  |
| Validity Sensors           | 16        | 30.19%  |
| Shenzhen Goodix Technology | 11        | 20.75%  |
| Elan Microelectronics      | 4         | 7.55%   |
| LighTuning Technology      | 2         | 3.77%   |
| AuthenTec                  | 2         | 3.77%   |
| HOLTEK                     | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 15.09%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 9.43%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 7.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 7.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.66%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 5.66%   |
| Synaptics  WBDI                                                            | 3         | 5.66%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 3.77%   |
| Synaptics WBDI                                                             | 2         | 3.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.77%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.89%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.89%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.89%   |
| Synaptics UWP WBDI                                                         | 1         | 1.89%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.89%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.89%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.89%   |
| LighTuning Fingerprint Sensor                                              | 1         | 1.89%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.89%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 1.89%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 1.89%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.89%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.89%   |
| AuthenTec AES2810                                                          | 1         | 1.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 7         | 31.82%  |
| Broadcom                          | 6         | 27.27%  |
| Upek                              | 3         | 13.64%  |
| O2 Micro                          | 2         | 9.09%   |
| Yubico.com                        | 1         | 4.55%   |
| VASCO Data Security International | 1         | 4.55%   |
| Gemalto (was Gemplus)             | 1         | 4.55%   |
| Clay Logic                        | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                             | 7         | 31.82%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)      | 3         | 13.64%  |
| Broadcom BCM5880 Secure Applications Processor                  | 3         | 13.64%  |
| O2 Micro OZ776 CCID Smartcard Reader                            | 2         | 9.09%   |
| Broadcom 58200                                                  | 2         | 9.09%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                             | 1         | 4.55%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1         | 4.55%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 1         | 4.55%   |
| Clay Logic Nitrokey Pro                                         | 1         | 4.55%   |
| Broadcom 5880                                                   | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 351       | 75.16%  |
| 1     | 99        | 21.2%   |
| 2     | 16        | 3.43%   |
| 3     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 53        | 39.85%  |
| Chipcard              | 20        | 15.04%  |
| Graphics card         | 19        | 14.29%  |
| Net/wireless          | 10        | 7.52%   |
| Multimedia controller | 10        | 7.52%   |
| Camera                | 6         | 4.51%   |
| Unassigned class      | 5         | 3.76%   |
| Storage               | 4         | 3.01%   |
| Bluetooth             | 3         | 2.26%   |
| Sound                 | 1         | 0.75%   |
| Network               | 1         | 0.75%   |
| Net/ethernet          | 1         | 0.75%   |

