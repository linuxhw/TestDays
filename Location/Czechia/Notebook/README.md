Linux in Czechia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 2008

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [a64852fe4a](https://linux-hardware.org/?probe=a64852fe4a) | Feb 02, 2024 |
| Dell          | Inspiron 7577               | [0155afe6f3](https://linux-hardware.org/?probe=0155afe6f3) | Feb 02, 2024 |
| Dell          | Inspiron 7566               | [e8f24dd8cf](https://linux-hardware.org/?probe=e8f24dd8cf) | Jan 31, 2024 |
| Acer          | Nitro AN515-42              | [9e4c4acd0d](https://linux-hardware.org/?probe=9e4c4acd0d) | Jan 30, 2024 |
| ASUSTek       | UX550VD                     | [3b742650db](https://linux-hardware.org/?probe=3b742650db) | Jan 29, 2024 |
| UMAX          | VisionBook 14Wr Plus        | [148a4486f3](https://linux-hardware.org/?probe=148a4486f3) | Jan 29, 2024 |
| HP            | ZBook Power 15.6 inch G1... | [6304caec55](https://linux-hardware.org/?probe=6304caec55) | Jan 29, 2024 |
| Samsung       | 300V3A                      | [53e3665790](https://linux-hardware.org/?probe=53e3665790) | Jan 27, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4b4af4b9b4](https://linux-hardware.org/?probe=4b4af4b9b4) | Jan 26, 2024 |
| Dell          | XPS 9320                    | [ed6a1f51f5](https://linux-hardware.org/?probe=ed6a1f51f5) | Jan 26, 2024 |
| HP            | 2000                        | [f1e38c4df2](https://linux-hardware.org/?probe=f1e38c4df2) | Jan 25, 2024 |
| HP            | EliteBook 840 G2            | [9ad67b6f8d](https://linux-hardware.org/?probe=9ad67b6f8d) | Jan 23, 2024 |
| HP            | EliteBook 840 G2            | [04f0c2393d](https://linux-hardware.org/?probe=04f0c2393d) | Jan 23, 2024 |
| HP            | Laptop 15-db0xxx            | [79cf6e6101](https://linux-hardware.org/?probe=79cf6e6101) | Jan 22, 2024 |
| Dell          | Latitude 5440               | [4ac53b51b3](https://linux-hardware.org/?probe=4ac53b51b3) | Jan 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5a444c3b35](https://linux-hardware.org/?probe=5a444c3b35) | Jan 22, 2024 |
| Lenovo        | G550 20023                  | [577e991c77](https://linux-hardware.org/?probe=577e991c77) | Jan 21, 2024 |
| Dell          | Latitude E6420              | [b0d535026a](https://linux-hardware.org/?probe=b0d535026a) | Jan 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | [a4aa40979a](https://linux-hardware.org/?probe=a4aa40979a) | Jan 18, 2024 |
| HP            | 530 Notebook PC(GU324AA#... | [785d324acb](https://linux-hardware.org/?probe=785d324acb) | Jan 18, 2024 |
| Dell          | Latitude 5591               | [b91323a39b](https://linux-hardware.org/?probe=b91323a39b) | Jan 17, 2024 |
| Acer          | Swift SFX14-41G             | [e3c95c6c18](https://linux-hardware.org/?probe=e3c95c6c18) | Jan 17, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [8e6afbe7c9](https://linux-hardware.org/?probe=8e6afbe7c9) | Jan 16, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [09e866e5e9](https://linux-hardware.org/?probe=09e866e5e9) | Jan 15, 2024 |
| HP            | Laptop 15-db0xxx            | [cb2cda915a](https://linux-hardware.org/?probe=cb2cda915a) | Jan 15, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | [60e35c48cf](https://linux-hardware.org/?probe=60e35c48cf) | Jan 14, 2024 |
| HP            | EliteBook 735 G5            | [53b86640e5](https://linux-hardware.org/?probe=53b86640e5) | Jan 12, 2024 |
| Apple         | MacBookPro9,2               | [696f5dd9e3](https://linux-hardware.org/?probe=696f5dd9e3) | Jan 12, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [2714705590](https://linux-hardware.org/?probe=2714705590) | Jan 12, 2024 |
| HP            | EliteBook 735 G5            | [c0282ee6a5](https://linux-hardware.org/?probe=c0282ee6a5) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | [0ca9774d55](https://linux-hardware.org/?probe=0ca9774d55) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | [a2ee63de30](https://linux-hardware.org/?probe=a2ee63de30) | Jan 11, 2024 |
| Acer          | Predator PH16-71            | [a2cae97378](https://linux-hardware.org/?probe=a2cae97378) | Jan 11, 2024 |
| Dell          | Inspiron 3793               | [60ded5e8e7](https://linux-hardware.org/?probe=60ded5e8e7) | Jan 11, 2024 |
| Dell          | Latitude 5440               | [61e99860d0](https://linux-hardware.org/?probe=61e99860d0) | Jan 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [10676b8682](https://linux-hardware.org/?probe=10676b8682) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| HP            | Compaq 610                  | [da1dd5ace4](https://linux-hardware.org/?probe=da1dd5ace4) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U938               | [b3dbded413](https://linux-hardware.org/?probe=b3dbded413) | Jan 07, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [6eaa268ce1](https://linux-hardware.org/?probe=6eaa268ce1) | Jan 07, 2024 |
| HP            | 250 G3                      | [259acacdb3](https://linux-hardware.org/?probe=259acacdb3) | Jan 06, 2024 |
| Acer          | Nitro AN515-44              | [4116ba8fb4](https://linux-hardware.org/?probe=4116ba8fb4) | Jan 05, 2024 |
| Acer          | Extensa 5230                | [2c36e88ef4](https://linux-hardware.org/?probe=2c36e88ef4) | Jan 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [5e72d133f1](https://linux-hardware.org/?probe=5e72d133f1) | Jan 02, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | [5983998e46](https://linux-hardware.org/?probe=5983998e46) | Jan 02, 2024 |
| Apple         | MacBookPro9,2               | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| HP            | Compaq 610                  | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| Dell          | XPS 13 9380                 | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| HP            | 2000                        | [eac2251c15](https://linux-hardware.org/?probe=eac2251c15) | Dec 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| Dell          | Latitude 5591               | [99b2702a06](https://linux-hardware.org/?probe=99b2702a06) | Dec 27, 2023 |
| Valve         | Jupiter                     | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [f91e53f3e0](https://linux-hardware.org/?probe=f91e53f3e0) | Dec 26, 2023 |
| HP            | 2000                        | [057698e1aa](https://linux-hardware.org/?probe=057698e1aa) | Dec 26, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [b08bd5ba2c](https://linux-hardware.org/?probe=b08bd5ba2c) | Dec 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [d7b7e34741](https://linux-hardware.org/?probe=d7b7e34741) | Dec 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [a79885417a](https://linux-hardware.org/?probe=a79885417a) | Dec 23, 2023 |
| HP            | ProBook 4540s               | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS25R00    | [91820391fd](https://linux-hardware.org/?probe=91820391fd) | Dec 23, 2023 |
| ASUSTek       | X555LA                      | [2f52e3fdc9](https://linux-hardware.org/?probe=2f52e3fdc9) | Dec 22, 2023 |
| HP            | ProBook 4540s               | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Dell          | Latitude 7490               | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ef2e756e7b](https://linux-hardware.org/?probe=ef2e756e7b) | Dec 21, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| Dell          | Precision M2800             | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| Sony          | VGN-FW455J                  | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Dell          | Latitude 7490               | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| ASUSTek       | X550CA                      | [fe7ad66674](https://linux-hardware.org/?probe=fe7ad66674) | Dec 13, 2023 |
| HP            | 2000                        | [40929a84a0](https://linux-hardware.org/?probe=40929a84a0) | Dec 10, 2023 |
| HP            | Laptop 15-fc0xxx            | [e55319a16a](https://linux-hardware.org/?probe=e55319a16a) | Dec 09, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [01f7b97e5d](https://linux-hardware.org/?probe=01f7b97e5d) | Dec 08, 2023 |
| Dell          | Latitude 5591               | [1961ebb904](https://linux-hardware.org/?probe=1961ebb904) | Dec 07, 2023 |
| Dell          | Latitude 5591               | [b9f6d020e8](https://linux-hardware.org/?probe=b9f6d020e8) | Dec 07, 2023 |
| Dell          | Precision 3550              | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| Valve         | Jupiter                     | [93bf1ceeec](https://linux-hardware.org/?probe=93bf1ceeec) | Dec 05, 2023 |
| Sony          | VPCS13S9E                   | [0cd7cfa9de](https://linux-hardware.org/?probe=0cd7cfa9de) | Dec 02, 2023 |
| Dynabook      | PORTEGE X50-G               | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| Lenovo        | ThinkPad T430 2349AK2       | [53a55a0da2](https://linux-hardware.org/?probe=53a55a0da2) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| Apple         | MacBookPro9,2               | [cfeac0b40f](https://linux-hardware.org/?probe=cfeac0b40f) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [71cf2f0a79](https://linux-hardware.org/?probe=71cf2f0a79) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| Acer          | Nitro AN515-58              | [c4a56c14f5](https://linux-hardware.org/?probe=c4a56c14f5) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [d1dc329e65](https://linux-hardware.org/?probe=d1dc329e65) | Nov 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [d0c3893980](https://linux-hardware.org/?probe=d0c3893980) | Nov 29, 2023 |
| Dell          | Latitude E6540              | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| UMAX          | VisionBook-N12R             | [e77e8d6999](https://linux-hardware.org/?probe=e77e8d6999) | Nov 26, 2023 |
| Acer          | Swift SF314-42              | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| Dell          | Latitude 5511               | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| HP            | EliteBook 840 G5            | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| Lenovo        | ThinkPad E450 20DC008DMC    | [56fc21d585](https://linux-hardware.org/?probe=56fc21d585) | Nov 23, 2023 |
| ASUSTek       | K54LY                       | [4ebc53e69c](https://linux-hardware.org/?probe=4ebc53e69c) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S9GM01    | [9c8590e300](https://linux-hardware.org/?probe=9c8590e300) | Nov 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [af566d6f0c](https://linux-hardware.org/?probe=af566d6f0c) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [748ea9f21b](https://linux-hardware.org/?probe=748ea9f21b) | Nov 21, 2023 |
| Dell          | Latitude E6430              | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| UMAX          | VisionBook-N12R             | [89e41854be](https://linux-hardware.org/?probe=89e41854be) | Nov 19, 2023 |
| Lenovo        | ThinkPad X201 3680DE3       | [38290dc3e7](https://linux-hardware.org/?probe=38290dc3e7) | Nov 17, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [ca7747546b](https://linux-hardware.org/?probe=ca7747546b) | Nov 17, 2023 |
| Dell          | Inspiron 7577               | [62e08b2285](https://linux-hardware.org/?probe=62e08b2285) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [2204427cc1](https://linux-hardware.org/?probe=2204427cc1) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [46cfd3f6bf](https://linux-hardware.org/?probe=46cfd3f6bf) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [001dd47e7d](https://linux-hardware.org/?probe=001dd47e7d) | Nov 12, 2023 |
| Acer          | Aspire E1-531               | [41e1f90785](https://linux-hardware.org/?probe=41e1f90785) | Nov 11, 2023 |
| Sony          | VPCEB4J0E                   | [c1e2a1a0da](https://linux-hardware.org/?probe=c1e2a1a0da) | Nov 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [47557dd574](https://linux-hardware.org/?probe=47557dd574) | Nov 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | G505 20240                  | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Dell          | Latitude E7440              | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | [ae8881b2b2](https://linux-hardware.org/?probe=ae8881b2b2) | Nov 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | [a3d91609e9](https://linux-hardware.org/?probe=a3d91609e9) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [60187ba0be](https://linux-hardware.org/?probe=60187ba0be) | Nov 04, 2023 |
| HP            | EliteBook 840 G5            | [a42017f05d](https://linux-hardware.org/?probe=a42017f05d) | Nov 02, 2023 |
| Dell          | Latitude 5480               | [567a2774f8](https://linux-hardware.org/?probe=567a2774f8) | Nov 01, 2023 |
| Dell          | Latitude E5470              | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [15573e8d54](https://linux-hardware.org/?probe=15573e8d54) | Oct 30, 2023 |
| HP            | 250 G3                      | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| ASUSTek       | X550CL                      | [a95ddd6798](https://linux-hardware.org/?probe=a95ddd6798) | Oct 26, 2023 |
| HP            | 250 G3                      | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [819d596b2e](https://linux-hardware.org/?probe=819d596b2e) | Oct 24, 2023 |
| HP            | EliteBook 840 G4            | [a6d732c859](https://linux-hardware.org/?probe=a6d732c859) | Oct 24, 2023 |
| Lenovo        | Unknown                     | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | [8f65236e52](https://linux-hardware.org/?probe=8f65236e52) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | [a523689a60](https://linux-hardware.org/?probe=a523689a60) | Oct 21, 2023 |
| Acer          | Swift SF314-42              | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Acer          | Aspire R3-131T              | [f8d2d274e1](https://linux-hardware.org/?probe=f8d2d274e1) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [79a2d6de1a](https://linux-hardware.org/?probe=79a2d6de1a) | Oct 19, 2023 |
| Dell          | XPS 13 9310                 | [3a6514e61a](https://linux-hardware.org/?probe=3a6514e61a) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [ba4661ac35](https://linux-hardware.org/?probe=ba4661ac35) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b2250f3c59](https://linux-hardware.org/?probe=b2250f3c59) | Oct 14, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Dell          | Latitude 5431               | [a85fc8f829](https://linux-hardware.org/?probe=a85fc8f829) | Oct 06, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3b55566de3](https://linux-hardware.org/?probe=3b55566de3) | Oct 05, 2023 |
| HP            | Pavilion Notebook           | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Dell          | Latitude E6420              | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| Sony          | VPCEB4J0E                   | [05864978df](https://linux-hardware.org/?probe=05864978df) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| Dell          | Precision 7710              | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Dell          | Inspiron 5515               | [5889ba673d](https://linux-hardware.org/?probe=5889ba673d) | Sep 27, 2023 |
| Sony          | VPCEB4J0E                   | [354e2be55e](https://linux-hardware.org/?probe=354e2be55e) | Sep 27, 2023 |
| HP            | EliteBook 8470p             | [a1fa543905](https://linux-hardware.org/?probe=a1fa543905) | Sep 27, 2023 |
| Acer          | Swift SF14-71T              | [10b657bd75](https://linux-hardware.org/?probe=10b657bd75) | Sep 25, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [336d5fe8c8](https://linux-hardware.org/?probe=336d5fe8c8) | Sep 25, 2023 |
| Dell          | Latitude 7400               | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [4bb581fb16](https://linux-hardware.org/?probe=4bb581fb16) | Sep 19, 2023 |
| Acer          | Aspire ES1-420              | [db308e1798](https://linux-hardware.org/?probe=db308e1798) | Sep 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Dell          | G3 3500                     | [293bbfe2d6](https://linux-hardware.org/?probe=293bbfe2d6) | Sep 12, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| Dell          | Latitude 7400               | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [30bf3f1f45](https://linux-hardware.org/?probe=30bf3f1f45) | Sep 05, 2023 |
| UMAX          | 13Wr                        | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| HP            | Unknown                     | [3809d7ad85](https://linux-hardware.org/?probe=3809d7ad85) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d6bca74de6](https://linux-hardware.org/?probe=d6bca74de6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | K53E                        | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| Acer          | Aspire E1-532               | [037143c4fd](https://linux-hardware.org/?probe=037143c4fd) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Valve         | Jupiter                     | [904e60e2d7](https://linux-hardware.org/?probe=904e60e2d7) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | [e751db6fd4](https://linux-hardware.org/?probe=e751db6fd4) | Aug 22, 2023 |
| Valve         | Jupiter                     | [57038f50cd](https://linux-hardware.org/?probe=57038f50cd) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [681310709d](https://linux-hardware.org/?probe=681310709d) | Aug 19, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| Dell          | Latitude 7440               | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [1fcc89106f](https://linux-hardware.org/?probe=1fcc89106f) | Aug 15, 2023 |
| HP            | Laptop 17-cp0xxx            | [620d12291b](https://linux-hardware.org/?probe=620d12291b) | Aug 15, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Dell          | XPS 13 7390                 | [f4e6886bd8](https://linux-hardware.org/?probe=f4e6886bd8) | Aug 13, 2023 |
| HP            | ZBook 17 G3                 | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| HP            | 250 G3                      | [6ba303bc6b](https://linux-hardware.org/?probe=6ba303bc6b) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ffa9b97bf7](https://linux-hardware.org/?probe=ffa9b97bf7) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [82dde7d058](https://linux-hardware.org/?probe=82dde7d058) | Aug 10, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [e1462f1e3a](https://linux-hardware.org/?probe=e1462f1e3a) | Aug 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 455 G7              | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [30d8fefda4](https://linux-hardware.org/?probe=30d8fefda4) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [f1cef350fb](https://linux-hardware.org/?probe=f1cef350fb) | Aug 07, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| Dell          | Latitude E6420              | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| Acer          | Aspire E5-572G              | [846dce7b1b](https://linux-hardware.org/?probe=846dce7b1b) | Aug 05, 2023 |
| Dell          | Latitude E5500              | [95ddcb321c](https://linux-hardware.org/?probe=95ddcb321c) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | [12ee4ed8f6](https://linux-hardware.org/?probe=12ee4ed8f6) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | [5a2ed78e49](https://linux-hardware.org/?probe=5a2ed78e49) | Aug 05, 2023 |
| Dell          | Latitude 7400               | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [e5be227d11](https://linux-hardware.org/?probe=e5be227d11) | Aug 03, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [6ec734b217](https://linux-hardware.org/?probe=6ec734b217) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASUSTek       | UX31E                       | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| Acer          | Aspire A315-24P             | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| Toshiba       | Satellite A135              | [91f5602ed7](https://linux-hardware.org/?probe=91f5602ed7) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Dell          | Latitude E7440              | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| Dell          | Latitude E5530 non-vPro     | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| Lenovo        | B5400 80B6QB0               | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f742573138](https://linux-hardware.org/?probe=f742573138) | Jul 12, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Lenovo        | ThinkPad E570 20H50074MC    | [029e84bf8a](https://linux-hardware.org/?probe=029e84bf8a) | Jul 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [bedadd4478](https://linux-hardware.org/?probe=bedadd4478) | Jul 05, 2023 |
| HP            | EliteBook 8770w             | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [73e054c849](https://linux-hardware.org/?probe=73e054c849) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| AMI           | Intel                       | [65aafdb0b0](https://linux-hardware.org/?probe=65aafdb0b0) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| ASUSTek       | UX31E                       | [37a73c8939](https://linux-hardware.org/?probe=37a73c8939) | Jul 01, 2023 |
| Acer          | Swift SF314-42              | [c5820f8068](https://linux-hardware.org/?probe=c5820f8068) | Jul 01, 2023 |
| UMAX          | VisionBook-N12R             | [6144190349](https://linux-hardware.org/?probe=6144190349) | Jun 30, 2023 |
| Acer          | NC-A515-51G-59DM            | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| ASUSTek       | GL552VX                     | [348e36123f](https://linux-hardware.org/?probe=348e36123f) | Jun 22, 2023 |
| ASUSTek       | UX31E                       | [51b4c8d9ef](https://linux-hardware.org/?probe=51b4c8d9ef) | Jun 22, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Acer          | Aspire ES1-420              | [76aab864d4](https://linux-hardware.org/?probe=76aab864d4) | Jun 19, 2023 |
| Dell          | Latitude E6540              | [3721b0046f](https://linux-hardware.org/?probe=3721b0046f) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [d3327c76f1](https://linux-hardware.org/?probe=d3327c76f1) | Jun 15, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| Acer          | Aspire ES1-420              | [5c3a2078ca](https://linux-hardware.org/?probe=5c3a2078ca) | Jun 14, 2023 |
| Dell          | XPS 15 9500                 | [77ce1af9f8](https://linux-hardware.org/?probe=77ce1af9f8) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f6e70e460f](https://linux-hardware.org/?probe=f6e70e460f) | Jun 11, 2023 |
| Dell          | Latitude 5420               | [956a995580](https://linux-hardware.org/?probe=956a995580) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| HP            | Laptop 15s-fq2xxx           | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| Dell          | Latitude 7400               | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| Acer          | Nitro AN515-44              | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| Timi          | A35S                        | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| Acer          | Aspire 7540                 | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Lenovo        | ThinkPad P51 20HJS01Q04     | [520eb0074c](https://linux-hardware.org/?probe=520eb0074c) | May 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Unknown       | Unknown                     | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| Dell          | G5 5587                     | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| Dell          | Vostro 5620                 | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| HP            | ProBook 4540s               | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | [14aeaeafe8](https://linux-hardware.org/?probe=14aeaeafe8) | May 15, 2023 |
| ASUSTek       | UX31E                       | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| Dell          | Latitude 7400               | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Dell          | Vostro 5620                 | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| HP            | EliteBook 8470p             | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Dell          | Latitude E7450              | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| Valve         | Jupiter                     | [1f41754528](https://linux-hardware.org/?probe=1f41754528) | May 03, 2023 |
| Apple         | MacBookAir3,1               | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| ASUSTek       | UX31E                       | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Acer          | Extensa 5620                | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| ASUSTek       | UX31E                       | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| Acer          | Aspire E1-572G              | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [fa228f68e4](https://linux-hardware.org/?probe=fa228f68e4) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [33bc801258](https://linux-hardware.org/?probe=33bc801258) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Valve         | Jupiter                     | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| Dell          | System XPS L502X            | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| HP            | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [db069c8b89](https://linux-hardware.org/?probe=db069c8b89) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [525241657b](https://linux-hardware.org/?probe=525241657b) | Apr 20, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [07e2728dfe](https://linux-hardware.org/?probe=07e2728dfe) | Apr 20, 2023 |
| Lenovo        | ThinkPad P52 20MAS5KM00     | [06ab19cc37](https://linux-hardware.org/?probe=06ab19cc37) | Apr 20, 2023 |
| HP            | Laptop 15-db1xxx            | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [59d15de09e](https://linux-hardware.org/?probe=59d15de09e) | Apr 15, 2023 |
| ASUSTek       | UX31E                       | [429e68a4ac](https://linux-hardware.org/?probe=429e68a4ac) | Apr 14, 2023 |
| HP            | ProBook 450 G6              | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| Acer          | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [9a592d3392](https://linux-hardware.org/?probe=9a592d3392) | Apr 11, 2023 |
| Acer          | Aspire A515-47              | [8a78c5b08f](https://linux-hardware.org/?probe=8a78c5b08f) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| ASUSTek       | UX31E                       | [3a1b0cca6b](https://linux-hardware.org/?probe=3a1b0cca6b) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | [b1168b92c0](https://linux-hardware.org/?probe=b1168b92c0) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e3078a63c3](https://linux-hardware.org/?probe=e3078a63c3) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1c8c26f5c0](https://linux-hardware.org/?probe=1c8c26f5c0) | Apr 02, 2023 |
| HP            | 250 G3                      | [2030ba57b9](https://linux-hardware.org/?probe=2030ba57b9) | Apr 02, 2023 |
| Dell          | Latitude 5511               | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0014e52bf3](https://linux-hardware.org/?probe=0014e52bf3) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| ASUSTek       | F7L                         | [8d6f90f843](https://linux-hardware.org/?probe=8d6f90f843) | Mar 29, 2023 |
| ASUSTek       | F7L                         | [cdc5ab3b8a](https://linux-hardware.org/?probe=cdc5ab3b8a) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | [6599d32d74](https://linux-hardware.org/?probe=6599d32d74) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | [64bef0aff5](https://linux-hardware.org/?probe=64bef0aff5) | Mar 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| Lenovo        | G780                        | [1ad87e5add](https://linux-hardware.org/?probe=1ad87e5add) | Mar 23, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| HP            | ProBook 450 G2              | [47992266f4](https://linux-hardware.org/?probe=47992266f4) | Mar 22, 2023 |
| HP            | ProBook 450 G2              | [dc56e35adc](https://linux-hardware.org/?probe=dc56e35adc) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| Acer          | TravelMate 7750ZG           | [5108cfe57c](https://linux-hardware.org/?probe=5108cfe57c) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Inspiron 5767               | [b7c8484508](https://linux-hardware.org/?probe=b7c8484508) | Mar 14, 2023 |
| ASUSTek       | UX31E                       | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| Dell          | Inspiron 5748               | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| ASUSTek       | K54LY                       | [a846675d7f](https://linux-hardware.org/?probe=a846675d7f) | Mar 09, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Dell          | Latitude E6420              | [c3384b7787](https://linux-hardware.org/?probe=c3384b7787) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| ASUSTek       | UX31E                       | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G531GT            | [810e15295b](https://linux-hardware.org/?probe=810e15295b) | Mar 03, 2023 |
| Dell          | Latitude 5421               | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | X555LA                      | [5dbbffb04e](https://linux-hardware.org/?probe=5dbbffb04e) | Mar 02, 2023 |
| UMAX          | VisionBook-N12R             | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| HP            | Laptop 15-rb0xx             | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | GX700                       | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| ASUSTek       | GL702VT                     | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| ASUSTek       | X200MA                      | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | EliteBook 8460p             | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f7fcfb7b18](https://linux-hardware.org/?probe=f7fcfb7b18) | Jan 19, 2023 |
| ASUSTek       | 1011PX                      | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad E550 20DF0081MC    | [1b7e734f36](https://linux-hardware.org/?probe=1b7e734f36) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [6841633faf](https://linux-hardware.org/?probe=6841633faf) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| HP            | 250 G3                      | [717fbc7972](https://linux-hardware.org/?probe=717fbc7972) | Jan 15, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [32f2651aa1](https://linux-hardware.org/?probe=32f2651aa1) | Jan 14, 2023 |
| HP            | ProBook 6560b               | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| Acer          | Extensa 2519                | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | Laptop 15-rb0xx             | [fd8d969adb](https://linux-hardware.org/?probe=fd8d969adb) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Dell          | Precision 5510              | [22a344ddad](https://linux-hardware.org/?probe=22a344ddad) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [42f10f6d45](https://linux-hardware.org/?probe=42f10f6d45) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X230 2320JNG       | [29d3023af5](https://linux-hardware.org/?probe=29d3023af5) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| UMAX          | VisionBook N14G Plus        | [412180b4de](https://linux-hardware.org/?probe=412180b4de) | Jan 06, 2023 |
| Acer          | TravelMate B115-M           | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASUSTek       | X405UA                      | [c56206ea8a](https://linux-hardware.org/?probe=c56206ea8a) | Jan 05, 2023 |
| Acer          | Aspire E1-531G              | [9b5a0200df](https://linux-hardware.org/?probe=9b5a0200df) | Jan 04, 2023 |
| Acer          | Aspire E1-531G              | [47813fa627](https://linux-hardware.org/?probe=47813fa627) | Jan 03, 2023 |
| HP            | ProBook 635 Aero G8         | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Google        | Chell                       | [02a0ae3bea](https://linux-hardware.org/?probe=02a0ae3bea) | Jan 02, 2023 |
| Valve         | Jupiter                     | [dc3612b4e1](https://linux-hardware.org/?probe=dc3612b4e1) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [2b646304f0](https://linux-hardware.org/?probe=2b646304f0) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK E736               | [8d54484965](https://linux-hardware.org/?probe=8d54484965) | Dec 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [7eb49ce0ab](https://linux-hardware.org/?probe=7eb49ce0ab) | Dec 24, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [4123115ef0](https://linux-hardware.org/?probe=4123115ef0) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| HP            | Pavilion TS 11              | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6e2cf6514a](https://linux-hardware.org/?probe=6e2cf6514a) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [b9ea8b5b2b](https://linux-hardware.org/?probe=b9ea8b5b2b) | Dec 08, 2022 |
| ASUSTek       | X55A                        | [283ef64c76](https://linux-hardware.org/?probe=283ef64c76) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| MSI           | Prestige 14 A11SCX          | [2b5a2c145c](https://linux-hardware.org/?probe=2b5a2c145c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| MSI           | Prestige 14 A11SCX          | [ca5bc5dfe6](https://linux-hardware.org/?probe=ca5bc5dfe6) | Dec 05, 2022 |
| ASUSTek       | UX31E                       | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e44ba4a41b](https://linux-hardware.org/?probe=e44ba4a41b) | Dec 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [2b1a977b21](https://linux-hardware.org/?probe=2b1a977b21) | Dec 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| HP            | 620                         | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 620                         | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Dell          | Precision 5510              | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| ASUSTek       | N61Jv                       | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | Pavilion dv7                | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Packard Be... | EasyNote TK85               | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| HP            | ProBook 4530s               | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| Dell          | Inspiron 5515               | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Pavilion g6                 | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | UX31E                       | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| UMAX          | VisionBook 12Wi 64G         | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | Pavilion dv7                | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | UX31E                       | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Dell          | Latitude E7250              | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Valve         | Jupiter                     | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| Dell          | Latitude 5531               | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| HP            | EliteBook 650 15.6 inch ... | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| Dell          | Latitude 5490               | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASUSTek       | UX31E                       | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | ElitePad 1000 G2            | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Acer          | Aspire A515-56              | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| Dell          | Latitude 5421               | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Dell          | Latitude 5531               | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| Dell          | Latitude 7520               | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | UX31E                       | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Valve         | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| ASUSTek       | UX31E                       | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| ASUSTek       | UX31E                       | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| ASUSTek       | UX31E                       | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| HP            | Pavilion dv6                | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| ASUSTek       | UX31E                       | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| Acer          | Aspire 3100                 | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Acer          | Swift SF314-52              | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| ASUSTek       | X555LB                      | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| ASUSTek       | UX31E                       | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| Lenovo        | B50-80 80EW                 | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | B50-80 80EW                 | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| Acer          | TravelMate 4670             | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| Acer          | Extensa 5630                | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Dell          | XPS 15 9550                 | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| ASUSTek       | UX31E                       | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Acer          | Aspire E5-573G              | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| ASUSTek       | UX31E                       | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Toshiba       | Satellite L750D             | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| Acer          | Extensa 5620                | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| ASUSTek       | UX31E                       | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Dell          | Latitude 7520               | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| ASUSTek       | UX31E                       | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| ASUSTek       | UX31E                       | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| ASUSTek       | X75A1                       | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| Google        | Chell                       | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| ASUSTek       | UX31E                       | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| Dell          | Latitude 5480               | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| ASUSTek       | F5RL                        | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| ASUSTek       | UX31E                       | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Dell          | Inspiron 5570               | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| ASUSTek       | UX31E                       | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | UX31E                       | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 159       | 10.45%  |
| Ubuntu 22.04                 | 83        | 5.46%   |
| Ubuntu 18.04                 | 83        | 5.46%   |
| OpenMandriva 4.2             | 75        | 4.93%   |
| OpenMandriva 4.50            | 58        | 3.81%   |
| OpenMandriva 4.3             | 40        | 2.63%   |
| Ubuntu 21.10                 | 29        | 1.91%   |
| Fedora 38                    | 28        | 1.84%   |
| Pop!_OS 22.04                | 27        | 1.78%   |
| Arch Rolling                 | 23        | 1.51%   |
| Zorin 16                     | 22        | 1.45%   |
| Ubuntu 19.10                 | 22        | 1.45%   |
| Fedora 34                    | 22        | 1.45%   |
| Zorin 15                     | 21        | 1.38%   |
| Ubuntu 20.10                 | 21        | 1.38%   |
| openSUSE Tumbleweed-XXXXXXXX | 21        | 1.38%   |
| OpenMandriva 23.01           | 21        | 1.38%   |
| Linux Mint 21.1              | 19        | 1.25%   |
| Debian 11                    | 19        | 1.25%   |
| Ubuntu 21.04                 | 18        | 1.18%   |
| Linux Mint 20                | 18        | 1.18%   |
| Arch                         | 17        | 1.12%   |
| Linux Mint 20.2              | 16        | 1.05%   |
| Linux Mint 19.3              | 16        | 1.05%   |
| OpenMandriva 23.03           | 15        | 0.99%   |
| Linux Mint 21.2              | 15        | 0.99%   |
| Linux Mint 20.3              | 15        | 0.99%   |
| Debian 12                    | 15        | 0.99%   |
| Manjaro                      | 14        | 0.92%   |
| Fedora 35                    | 14        | 0.92%   |
| Fedora 33                    | 14        | 0.92%   |
| Linux Mint 21                | 13        | 0.85%   |
| Linux Mint 20.1              | 13        | 0.85%   |
| Fedora 37                    | 13        | 0.85%   |
| Fedora 32                    | 13        | 0.85%   |
| Fedora 31                    | 13        | 0.85%   |
| Xubuntu 20.04                | 12        | 0.79%   |
| Ubuntu 19.04                 | 12        | 0.79%   |
| OpenMandriva 23.08           | 12        | 0.79%   |
| Kubuntu 22.04                | 12        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 431       | 30.2%   |
| OpenMandriva  | 228       | 15.98%  |
| Fedora        | 136       | 9.53%   |
| Linux Mint    | 126       | 8.83%   |
| Debian        | 49        | 3.43%   |
| Zorin         | 45        | 3.15%   |
| Pop!_OS       | 42        | 2.94%   |
| Arch          | 40        | 2.8%    |
| Xubuntu       | 38        | 2.66%   |
| Manjaro       | 37        | 2.59%   |
| Kubuntu       | 33        | 2.31%   |
| openSUSE      | 27        | 1.89%   |
| Gentoo        | 25        | 1.75%   |
| ROSA          | 19        | 1.33%   |
| KDE neon      | 15        | 1.05%   |
| Kali          | 15        | 1.05%   |
| Lubuntu       | 13        | 0.91%   |
| ArcoLinux     | 10        | 0.7%    |
| Elementary    | 9         | 0.63%   |
| SteamOS       | 8         | 0.56%   |
| Endless       | 8         | 0.56%   |
| Ubuntu MATE   | 7         | 0.49%   |
| RHEL          | 7         | 0.49%   |
| Ubuntu Unity  | 5         | 0.35%   |
| Ubuntu Budgie | 4         | 0.28%   |
| Parrot        | 4         | 0.28%   |
| NixOS         | 4         | 0.28%   |
| MX            | 4         | 0.28%   |
| EndeavourOS   | 4         | 0.28%   |
| BlackPanther  | 3         | 0.21%   |
| Rocky Linux   | 2         | 0.14%   |
| Nobara        | 2         | 0.14%   |
| LMDE          | 2         | 0.14%   |
| LinuxFX       | 2         | 0.14%   |
| Garuda Linux  | 2         | 0.14%   |
| Artix         | 2         | 0.14%   |
| Void Linux    | 1         | 0.07%   |
| UbuntuDDE     | 1         | 0.07%   |
| TUXEDO OS     | 1         | 0.07%   |
| SystemRescue  | 1         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 74        | 4.5%    |
| 5.14.7-desktop-1omv4050  | 55        | 3.35%   |
| 5.16.7-desktop-1omv4003  | 39        | 2.37%   |
| 5.4.0-42-generic         | 23        | 1.4%    |
| 6.1.1-desktop-1omv2290   | 20        | 1.22%   |
| 5.4.0-52-generic         | 15        | 0.91%   |
| 5.15.0-46-generic        | 15        | 0.91%   |
| 6.2.6-desktop-1omv2390   | 14        | 0.85%   |
| 5.4.0-26-generic         | 13        | 0.79%   |
| 5.15.0-56-generic        | 13        | 0.79%   |
| 5.4.0-58-generic         | 12        | 0.73%   |
| 5.3.0-40-generic         | 11        | 0.67%   |
| 6.2.0-26-generic         | 10        | 0.61%   |
| 5.15.0-58-generic        | 10        | 0.61%   |
| 6.6.2-desktop-1omv2390   | 9         | 0.55%   |
| 6.4.11-desktop-1omv2390  | 9         | 0.55%   |
| 5.4.0-65-generic         | 9         | 0.55%   |
| 5.15.0-48-generic        | 9         | 0.55%   |
| 5.0.0-37-generic         | 9         | 0.55%   |
| 6.2.0-39-generic         | 8         | 0.49%   |
| 5.8.0-59-generic         | 8         | 0.49%   |
| 5.4.0-48-generic         | 8         | 0.49%   |
| 5.4.0-40-generic         | 8         | 0.49%   |
| 5.15.0-78-generic        | 8         | 0.49%   |
| 5.15.0-52-generic        | 8         | 0.49%   |
| 5.13.0-21-generic        | 8         | 0.49%   |
| 6.2.6-76060206-generic   | 7         | 0.43%   |
| 5.4.0-91-generic         | 7         | 0.43%   |
| 5.19.0-32-generic        | 7         | 0.43%   |
| 5.11.0-27-generic        | 7         | 0.43%   |
| 6.1.0-13-amd64           | 6         | 0.36%   |
| 5.8.0-53-generic         | 6         | 0.36%   |
| 5.4.0-70-generic         | 6         | 0.36%   |
| 5.4.0-56-generic         | 6         | 0.36%   |
| 5.4.0-37-generic         | 6         | 0.36%   |
| 5.4.0-29-generic         | 6         | 0.36%   |
| 5.3.0-46-generic         | 6         | 0.36%   |
| 5.3.0-42-generic         | 6         | 0.36%   |
| 5.3.0-28-generic         | 6         | 0.36%   |
| 5.13.0-30-generic        | 6         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 197       | 12.71%  |
| 5.15.0  | 121       | 7.81%   |
| 5.10.14 | 74        | 4.77%   |
| 5.3.0   | 68        | 4.39%   |
| 5.13.0  | 67        | 4.32%   |
| 5.11.0  | 63        | 4.06%   |
| 5.8.0   | 58        | 3.74%   |
| 4.15.0  | 58        | 3.74%   |
| 5.14.7  | 56        | 3.61%   |
| 5.0.0   | 44        | 2.84%   |
| 6.2.0   | 41        | 2.65%   |
| 5.16.7  | 40        | 2.58%   |
| 5.19.0  | 39        | 2.52%   |
| 5.10.0  | 28        | 1.81%   |
| 6.5.0   | 26        | 1.68%   |
| 4.18.0  | 26        | 1.68%   |
| 6.1.1   | 23        | 1.48%   |
| 6.1.0   | 22        | 1.42%   |
| 6.2.6   | 21        | 1.35%   |
| 6.6.2   | 10        | 0.65%   |
| 6.5.6   | 10        | 0.65%   |
| 6.4.11  | 9         | 0.58%   |
| 4.19.0  | 8         | 0.52%   |
| 6.2.9   | 6         | 0.39%   |
| 6.0.0   | 6         | 0.39%   |
| 5.14.0  | 6         | 0.39%   |
| 6.2.15  | 5         | 0.32%   |
| 5.15.12 | 5         | 0.32%   |
| 4.13.0  | 5         | 0.32%   |
| 6.6.9   | 4         | 0.26%   |
| 6.6.6   | 4         | 0.26%   |
| 6.6.1   | 4         | 0.26%   |
| 6.5.5   | 4         | 0.26%   |
| 6.4.6   | 4         | 0.26%   |
| 6.3.8   | 4         | 0.26%   |
| 5.9.0   | 4         | 0.26%   |
| 5.6.16  | 4         | 0.26%   |
| 5.3.18  | 4         | 0.26%   |
| 5.17.0  | 4         | 0.26%   |
| 5.16.11 | 4         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 213       | 13.85%  |
| 5.15    | 152       | 9.88%   |
| 5.10    | 129       | 8.39%   |
| 6.2     | 84        | 5.46%   |
| 5.11    | 84        | 5.46%   |
| 5.13    | 80        | 5.2%    |
| 5.3     | 76        | 4.94%   |
| 5.14    | 75        | 4.88%   |
| 5.8     | 74        | 4.81%   |
| 6.1     | 70        | 4.55%   |
| 4.15    | 60        | 3.9%    |
| 5.16    | 57        | 3.71%   |
| 5.19    | 54        | 3.51%   |
| 6.5     | 50        | 3.25%   |
| 5.0     | 46        | 2.99%   |
| 6.6     | 28        | 1.82%   |
| 6.4     | 28        | 1.82%   |
| 4.18    | 28        | 1.82%   |
| 6.0     | 23        | 1.5%    |
| 5.17    | 20        | 1.3%    |
| 5.9     | 15        | 0.98%   |
| 5.6     | 15        | 0.98%   |
| 5.18    | 15        | 0.98%   |
| 4.19    | 12        | 0.78%   |
| 6.3     | 7         | 0.46%   |
| 5.12    | 7         | 0.46%   |
| 4.9     | 7         | 0.46%   |
| 5.7     | 6         | 0.39%   |
| 5.5     | 6         | 0.39%   |
| 4.13    | 5         | 0.33%   |
| 4.4     | 4         | 0.26%   |
| 6.7     | 2         | 0.13%   |
| 5.1     | 2         | 0.13%   |
| 4.8     | 1         | 0.07%   |
| 4.17    | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1356      | 97%     |
| i686   | 42        | 3%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 585       | 40.4%   |
| KDE5            | 368       | 25.41%  |
| Unknown         | 141       | 9.74%   |
| XFCE            | 115       | 7.94%   |
| X-Cinnamon      | 76        | 5.25%   |
| MATE            | 38        | 2.62%   |
| KDE             | 23        | 1.59%   |
| Cinnamon        | 19        | 1.31%   |
| LXQt            | 18        | 1.24%   |
| Pantheon        | 9         | 0.62%   |
| LXDE            | 7         | 0.48%   |
| Unity           | 6         | 0.41%   |
| KDE4            | 6         | 0.41%   |
| GNOME Flashback | 6         | 0.41%   |
| i3              | 5         | 0.35%   |
| Budgie          | 5         | 0.35%   |
| awesome         | 4         | 0.28%   |
| Hyprland        | 3         | 0.21%   |
| sway            | 2         | 0.14%   |
| qtile           | 2         | 0.14%   |
| openbox         | 2         | 0.14%   |
| XSession        | 1         | 0.07%   |
| xinitrc         | 1         | 0.07%   |
| xinit-compat    | 1         | 0.07%   |
| GNUstep         | 1         | 0.07%   |
| Enlightenment   | 1         | 0.07%   |
| DWM             | 1         | 0.07%   |
| Deepin          | 1         | 0.07%   |
| custom          | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1057      | 73.4%   |
| Wayland | 285       | 19.79%  |
| Unknown | 83        | 5.76%   |
| Tty     | 15        | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 591       | 40.87%  |
| SDDM    | 350       | 24.2%   |
| GDM3    | 165       | 11.41%  |
| GDM     | 146       | 10.1%   |
| LightDM | 137       | 9.47%   |
| TDM     | 39        | 2.7%    |
| KDM     | 5         | 0.35%   |
| XDM     | 4         | 0.28%   |
| SLiM    | 4         | 0.28%   |
| LXDM    | 3         | 0.21%   |
| Ly      | 1         | 0.07%   |
| GREETD  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| cs_CZ   | 748       | 52.49%  |
| en_US   | 444       | 31.16%  |
| Unknown | 124       | 8.7%    |
| en_GB   | 30        | 2.11%   |
| C       | 28        | 1.96%   |
| ru_RU   | 18        | 1.26%   |
| sk_SK   | 5         | 0.35%   |
| pl_PL   | 5         | 0.35%   |
| uk_UA   | 3         | 0.21%   |
| POSIX   | 3         | 0.21%   |
| de_DE   | 3         | 0.21%   |
| it_IT   | 2         | 0.14%   |
| fr_FR   | 2         | 0.14%   |
| tr_TR   | 1         | 0.07%   |
| ro_RO   | 1         | 0.07%   |
| pt_PT   | 1         | 0.07%   |
| es_ES   | 1         | 0.07%   |
| en_NG   | 1         | 0.07%   |
| en_CA   | 1         | 0.07%   |
| en_150  | 1         | 0.07%   |
| el_GR   | 1         | 0.07%   |
| de_CH   | 1         | 0.07%   |
| bg_BG   | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 724       | 50.56%  |
| BIOS | 708       | 49.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 924       | 64.71%  |
| Overlay  | 234       | 16.39%  |
| Btrfs    | 150       | 10.5%   |
| Tmpfs    | 40        | 2.8%    |
| Unknown  | 33        | 2.31%   |
| Xfs      | 28        | 1.96%   |
| Zfs      | 10        | 0.7%    |
| Ext3     | 3         | 0.21%   |
| Ext2     | 2         | 0.14%   |
| Aufs     | 2         | 0.14%   |
| Reiserfs | 1         | 0.07%   |
| F2fs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 619       | 43.53%  |
| GPT     | 563       | 39.59%  |
| MBR     | 240       | 16.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1281      | 90.85%  |
| Yes       | 129       | 9.15%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 927       | 65.01%  |
| Yes       | 499       | 34.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 370       | 26.47%  |
| ASUSTek Computer               | 268       | 19.17%  |
| Hewlett-Packard                | 260       | 18.6%   |
| Dell                           | 198       | 14.16%  |
| Acer                           | 132       | 9.44%   |
| UMAX                           | 22        | 1.57%   |
| MSI                            | 18        | 1.29%   |
| Toshiba                        | 17        | 1.22%   |
| Sony                           | 17        | 1.22%   |
| Fujitsu                        | 12        | 0.86%   |
| Valve                          | 8         | 0.57%   |
| Apple                          | 8         | 0.57%   |
| HUAWEI                         | 7         | 0.5%    |
| TUXEDO                         | 6         | 0.43%   |
| Unknown                        | 6         | 0.43%   |
| Google                         | 5         | 0.36%   |
| Timi                           | 4         | 0.29%   |
| Packard Bell                   | 4         | 0.29%   |
| Fujitsu Siemens                | 4         | 0.29%   |
| Notebook                       | 3         | 0.21%   |
| Samsung Electronics            | 2         | 0.14%   |
| Insyde                         | 2         | 0.14%   |
| Dynabook                       | 2         | 0.14%   |
| Chuwi                          | 2         | 0.14%   |
| Alienware                      | 2         | 0.14%   |
| Standard                       | 1         | 0.07%   |
| SmbiosType1_SystemManufacturer | 1         | 0.07%   |
| SLIMBOOK                       | 1         | 0.07%   |
| Purism                         | 1         | 0.07%   |
| Prestigio                      | 1         | 0.07%   |
| Panasonic                      | 1         | 0.07%   |
| Medion                         | 1         | 0.07%   |
| Jumper                         | 1         | 0.07%   |
| Intel                          | 1         | 0.07%   |
| INET                           | 1         | 0.07%   |
| In-Sing                        | 1         | 0.07%   |
| IBM                            | 1         | 0.07%   |
| Gigabyte Technology            | 1         | 0.07%   |
| EUROCOM                        | 1         | 0.07%   |
| eMachines                      | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 127       | 9.08%   |
| Unknown                               | 10        | 0.72%   |
| Valve Jupiter                         | 8         | 0.57%   |
| HP ProBook 455 G7                     | 7         | 0.5%    |
| Dell Latitude E6420                   | 7         | 0.5%    |
| HP ProBook 4540s                      | 6         | 0.43%   |
| HP EliteBook 845 G8 Notebook PC       | 6         | 0.43%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.36%   |
| Lenovo IdeaPad S145-15AST 81N3        | 5         | 0.36%   |
| HP ProBook 4530s                      | 5         | 0.36%   |
| HP ProBook 450 G5                     | 5         | 0.36%   |
| HP Pavilion dv7                       | 5         | 0.36%   |
| HP EliteBook 840 G6                   | 5         | 0.36%   |
| HP EliteBook 840 G3                   | 5         | 0.36%   |
| Dell XPS 15 9560                      | 5         | 0.36%   |
| Dell Latitude E6400                   | 5         | 0.36%   |
| Dell Latitude 5401                    | 5         | 0.36%   |
| HP Notebook                           | 4         | 0.29%   |
| HP 250 G6 Notebook PC                 | 4         | 0.29%   |
| HP 250 G3                             | 4         | 0.29%   |
| Dell XPS 15 7590                      | 4         | 0.29%   |
| Dell Precision M6500                  | 4         | 0.29%   |
| Dell Latitude E7440                   | 4         | 0.29%   |
| Dell Latitude E5470                   | 4         | 0.29%   |
| Dell Latitude 5480                    | 4         | 0.29%   |
| Acer Extensa 5620                     | 4         | 0.29%   |
| UMAX VisionBook-N12R                  | 3         | 0.21%   |
| UMAX VisionBook 15Wg Plus             | 3         | 0.21%   |
| Lenovo Z50-75 80EC                    | 3         | 0.21%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D0Y | 3         | 0.21%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.21%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.21%   |
| Lenovo IdeaPad Z580                   | 3         | 0.21%   |
| Lenovo IdeaPad S130-11IGM 81J1        | 3         | 0.21%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 3         | 0.21%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 3         | 0.21%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 3         | 0.21%   |
| Lenovo IdeaPad 5 14ABA7 82SE          | 3         | 0.21%   |
| Lenovo IdeaPad 3 15ARE05 81W4         | 3         | 0.21%   |
| HP Victus by Laptop 16-e0xxx          | 3         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 195       | 13.95%  |
| ASUS UX31E            | 127       | 9.08%   |
| Dell Latitude         | 101       | 7.22%   |
| Lenovo IdeaPad        | 79        | 5.65%   |
| Acer Aspire           | 77        | 5.51%   |
| HP EliteBook          | 70        | 5.01%   |
| HP ProBook            | 64        | 4.58%   |
| Dell XPS              | 29        | 2.07%   |
| HP Pavilion           | 27        | 1.93%   |
| Dell Inspiron         | 25        | 1.79%   |
| Dell Precision        | 21        | 1.5%    |
| HP ZBook              | 19        | 1.36%   |
| Lenovo Yoga           | 17        | 1.22%   |
| Lenovo Legion         | 17        | 1.22%   |
| HP Laptop             | 17        | 1.22%   |
| HP Compaq             | 17        | 1.22%   |
| ASUS VivoBook         | 17        | 1.22%   |
| Toshiba Satellite     | 16        | 1.14%   |
| UMAX VisionBook       | 15        | 1.07%   |
| ASUS ZenBook          | 15        | 1.07%   |
| Acer Extensa          | 15        | 1.07%   |
| Acer Swift            | 13        | 0.93%   |
| HP 250                | 12        | 0.86%   |
| Fujitsu LIFEBOOK      | 12        | 0.86%   |
| Acer TravelMate       | 12        | 0.86%   |
| Lenovo ThinkBook      | 10        | 0.72%   |
| Unknown               | 10        | 0.72%   |
| Dell Vostro           | 9         | 0.64%   |
| ASUS ASUS             | 9         | 0.64%   |
| Valve Jupiter         | 8         | 0.57%   |
| ASUS ROG              | 8         | 0.57%   |
| Acer Nitro            | 7         | 0.5%    |
| Packard Bell EasyNote | 4         | 0.29%   |
| HP Victus             | 4         | 0.29%   |
| HP OMEN               | 4         | 0.29%   |
| HP Notebook           | 4         | 0.29%   |
| Dell G5               | 4         | 0.29%   |
| UMAX VisionBook-N12R  | 3         | 0.21%   |
| TUXEDO InfinityBook   | 3         | 0.21%   |
| Lenovo Z50-75         | 3         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 209       | 14.95%  |
| 2020    | 133       | 9.51%   |
| 2021    | 124       | 8.87%   |
| 2019    | 115       | 8.23%   |
| 2018    | 97        | 6.94%   |
| 2012    | 86        | 6.15%   |
| 2017    | 78        | 5.58%   |
| 2014    | 78        | 5.58%   |
| 2013    | 72        | 5.15%   |
| 2015    | 69        | 4.94%   |
| 2008    | 63        | 4.51%   |
| 2016    | 62        | 4.43%   |
| 2022    | 58        | 4.15%   |
| 2010    | 50        | 3.58%   |
| 2007    | 33        | 2.36%   |
| 2009    | 31        | 2.22%   |
| 2023    | 20        | 1.43%   |
| 2006    | 13        | 0.93%   |
| 2005    | 3         | 0.21%   |
| 2004    | 2         | 0.14%   |
| Unknown | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1398      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1237      | 87.24%  |
| Enabled  | 181       | 12.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1392      | 99.57%  |
| Yes  | 6         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 386       | 27.22%  |
| 4.01-8.0    | 299       | 21.09%  |
| 8.01-16.0   | 243       | 17.14%  |
| 16.01-24.0  | 208       | 14.67%  |
| 32.01-64.0  | 125       | 8.82%   |
| 1.01-2.0    | 73        | 5.15%   |
| 2.01-3.0    | 27        | 1.9%    |
| 24.01-32.0  | 26        | 1.83%   |
| 64.01-256.0 | 16        | 1.13%   |
| 0.51-1.0    | 14        | 0.99%   |
| 0.01-0.5    | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 551       | 35.64%  |
| 2.01-3.0   | 334       | 21.6%   |
| 4.01-8.0   | 246       | 15.91%  |
| 3.01-4.0   | 200       | 12.94%  |
| 8.01-16.0  | 89        | 5.76%   |
| 0.51-1.0   | 86        | 5.56%   |
| 0.01-0.5   | 19        | 1.23%   |
| 16.01-24.0 | 17        | 1.1%    |
| 32.01-64.0 | 2         | 0.13%   |
| 24.01-32.0 | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1115      | 78.03%  |
| 2      | 264       | 18.47%  |
| 3      | 32        | 2.24%   |
| 0      | 15        | 1.05%   |
| 4      | 2         | 0.14%   |
| 7      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 993       | 70.73%  |
| Yes       | 411       | 29.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1173      | 83.31%  |
| No        | 235       | 16.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1377      | 98.43%  |
| No        | 22        | 1.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1040      | 73.55%  |
| No        | 374       | 26.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Czechia | 1398      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Prague               | 597       | 40.95%  |
| Brno                 | 122       | 8.37%   |
| Ostrava              | 44        | 3.02%   |
| Pilsen               | 29        | 1.99%   |
| Olomouc              | 21        | 1.44%   |
| Pardubice            | 18        | 1.23%   |
| Liberec              | 17        | 1.17%   |
| Hradec Králové     | 14        | 0.96%   |
| České Budějovice  | 14        | 0.96%   |
| Brdo                 | 14        | 0.96%   |
| Chomutov             | 11        | 0.75%   |
| Most                 | 10        | 0.69%   |
| Havířov            | 10        | 0.69%   |
| Zlín                | 9         | 0.62%   |
| Jihlava              | 8         | 0.55%   |
| Znojmo               | 7         | 0.48%   |
| Opava                | 7         | 0.48%   |
| Karlovy Vary         | 7         | 0.48%   |
| Ústí nad Labem     | 6         | 0.41%   |
| Tábor               | 6         | 0.41%   |
| Roznov pod Radhostem | 6         | 0.41%   |
| Příbram            | 6         | 0.41%   |
| Kladno               | 6         | 0.41%   |
| Přerov              | 5         | 0.34%   |
| Mariánské Lázně  | 5         | 0.34%   |
| Jedovnice            | 5         | 0.34%   |
| Ceska Kamenice       | 5         | 0.34%   |
| Třebíč            | 4         | 0.27%   |
| Teplice              | 4         | 0.27%   |
| Slavkov u Brna       | 4         | 0.27%   |
| Šlapanice           | 4         | 0.27%   |
| Prelouc              | 4         | 0.27%   |
| Pelhrimov            | 4         | 0.27%   |
| Mladá Boleslav      | 4         | 0.27%   |
| Milovice             | 4         | 0.27%   |
| Kralupy nad Vltavou  | 4         | 0.27%   |
| Frýdek-Místek      | 4         | 0.27%   |
| Česká Lípa        | 4         | 0.27%   |
| Celakovice           | 4         | 0.27%   |
| Beroun               | 4         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 294       | 386    | 17.54%  |
| SanDisk                        | 213       | 230    | 12.71%  |
| WDC                            | 159       | 189    | 9.49%   |
| Seagate                        | 158       | 212    | 9.43%   |
| Toshiba                        | 121       | 145    | 7.22%   |
| Kingston                       | 90        | 98     | 5.37%   |
| Unknown                        | 85        | 118    | 5.07%   |
| SK hynix                       | 80        | 96     | 4.77%   |
| Micron Technology              | 59        | 75     | 3.52%   |
| Hitachi                        | 54        | 63     | 3.22%   |
| Intel                          | 51        | 59     | 3.04%   |
| HGST                           | 44        | 55     | 2.63%   |
| A-DATA Technology              | 28        | 31     | 1.67%   |
| Patriot                        | 26        | 31     | 1.55%   |
| Crucial                        | 26        | 36     | 1.55%   |
| KIOXIA                         | 22        | 35     | 1.31%   |
| Apacer                         | 12        | 17     | 0.72%   |
| Unknown                        | 12        | 13     | 0.72%   |
| Transcend                      | 11        | 12     | 0.66%   |
| LITEONIT                       | 9         | 12     | 0.54%   |
| Fujitsu                        | 7         | 7      | 0.42%   |
| China                          | 7         | 8      | 0.42%   |
| Apple                          | 7         | 9      | 0.42%   |
| Verbatim                       | 6         | 6      | 0.36%   |
| Phison Electronics             | 6         | 7      | 0.36%   |
| Phison                         | 6         | 13     | 0.36%   |
| LITEON                         | 6         | 6      | 0.36%   |
| Silicon Motion                 | 5         | 5      | 0.3%    |
| UMAX                           | 4         | 4      | 0.24%   |
| Micron/Crucial Technology      | 4         | 4      | 0.24%   |
| JMicron Technology             | 4         | 4      | 0.24%   |
| GOODRAM                        | 4         | 5      | 0.24%   |
| Gigabyte Technology            | 4         | 9      | 0.24%   |
| ASMedia                        | 4         | 6      | 0.24%   |
| Team                           | 3         | 3      | 0.18%   |
| Solid State Storage Technology | 3         | 3      | 0.18%   |
| Lenovo                         | 3         | 4      | 0.18%   |
| Kingston Technology Company    | 3         | 3      | 0.18%   |
| UMIS                           | 2         | 2      | 0.12%   |
| Realtek Semiconductor          | 2         | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                             | 126       | 7.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 20        | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB                     | 18        | 1.03%   |
| Unknown MMC Card  32GB                             | 17        | 0.97%   |
| Samsung NVMe SSD Drive 512GB                       | 17        | 0.97%   |
| HGST HTS721010A9E630 1TB                           | 16        | 0.92%   |
| Samsung SSD 860 EVO 500GB                          | 13        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 13        | 0.74%   |
| Unknown MMC Card  64GB                             | 12        | 0.69%   |
| SanDisk NVMe SSD Drive 512GB                       | 12        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                    | 12        | 0.69%   |
| Unknown                                            | 12        | 0.69%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 11        | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 10        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 10        | 0.57%   |
| Kingston SA400S37240G 240GB SSD                    | 10        | 0.57%   |
| Unknown MMC Card  16GB                             | 9         | 0.51%   |
| Toshiba MQ01ABD100 1TB                             | 9         | 0.51%   |
| Seagate ST500LT012-1DG142 500GB                    | 9         | 0.51%   |
| HGST HTS725050A7E630 500GB                         | 9         | 0.51%   |
| Toshiba NVMe SSD Drive 256GB                       | 8         | 0.46%   |
| Toshiba MQ04ABF100 1TB                             | 8         | 0.46%   |
| Toshiba MQ01ABF050 500GB                           | 8         | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                      | 8         | 0.46%   |
| Samsung SSD 850 EVO 250GB                          | 8         | 0.46%   |
| Patriot Burst 480GB SSD                            | 8         | 0.46%   |
| Seagate ST9500420AS 500GB                          | 7         | 0.4%    |
| SanDisk NVMe SSD Drive 1024GB                      | 7         | 0.4%    |
| Samsung SSD 860 EVO 1TB                            | 7         | 0.4%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 7         | 0.4%    |
| Kingston SA400S37120G 120GB SSD                    | 7         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 6         | 0.34%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 6         | 0.34%   |
| Unknown MMC Card  128GB                            | 6         | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                       | 6         | 0.34%   |
| Seagate ST500LM000-1EJ162 500GB                    | 6         | 0.34%   |
| Seagate ST2000LM007-1R8174 2TB                     | 6         | 0.34%   |
| SanDisk NVMe SSD Drive 1TB                         | 6         | 0.34%   |
| SanDisk DF4032  32GB                               | 6         | 0.34%   |
| Samsung SSD 980 1TB                                | 6         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 156       | 210    | 36.11%  |
| WDC                 | 93        | 109    | 21.53%  |
| Toshiba             | 69        | 77     | 15.97%  |
| Hitachi             | 54        | 63     | 12.5%   |
| HGST                | 44        | 55     | 10.19%  |
| Fujitsu             | 7         | 7      | 1.62%   |
| Samsung Electronics | 2         | 2      | 0.46%   |
| JMicron Technology  | 2         | 2      | 0.46%   |
| Unknown             | 1         | 1      | 0.23%   |
| TO Exter            | 1         | 2      | 0.23%   |
| StoreJet            | 1         | 1      | 0.23%   |
| IBM/Hitachi         | 1         | 1      | 0.23%   |
| Apple               | 1         | 3      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 161       | 166    | 27.1%   |
| Samsung Electronics | 119       | 145    | 20.03%  |
| Kingston            | 65        | 71     | 10.94%  |
| WDC                 | 29        | 40     | 4.88%   |
| Patriot             | 26        | 31     | 4.38%   |
| A-DATA Technology   | 25        | 28     | 4.21%   |
| Crucial             | 22        | 32     | 3.7%    |
| Intel               | 21        | 23     | 3.54%   |
| Micron Technology   | 17        | 22     | 2.86%   |
| SK hynix            | 13        | 14     | 2.19%   |
| Apacer              | 12        | 17     | 2.02%   |
| Transcend           | 11        | 12     | 1.85%   |
| Toshiba             | 11        | 13     | 1.85%   |
| LITEONIT            | 9         | 12     | 1.52%   |
| China               | 7         | 8      | 1.18%   |
| Verbatim            | 6         | 6      | 1.01%   |
| Apple               | 5         | 5      | 0.84%   |
| UMAX                | 4         | 4      | 0.67%   |
| LITEON              | 4         | 4      | 0.67%   |
| GOODRAM             | 3         | 4      | 0.51%   |
| Gigabyte Technology | 3         | 7      | 0.51%   |
| ASMedia             | 3         | 4      | 0.51%   |
| Team                | 2         | 2      | 0.34%   |
| ASMT                | 2         | 2      | 0.34%   |
| USB3.0              | 1         | 1      | 0.17%   |
| UMIS                | 1         | 1      | 0.17%   |
| ShanDianZhe         | 1         | 1      | 0.17%   |
| Seagate             | 1         | 1      | 0.17%   |
| SABRENT             | 1         | 1      | 0.17%   |
| OCZ                 | 1         | 4      | 0.17%   |
| Netac               | 1         | 1      | 0.17%   |
| Mushkin             | 1         | 1      | 0.17%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.17%   |
| KingSpec            | 1         | 1      | 0.17%   |
| HPE                 | 1         | 1      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |
| CT500MX5            | 1         | 1      | 0.17%   |
| ADATA SU            | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 570       | 689    | 35.4%   |
| NVMe    | 509       | 693    | 31.61%  |
| HDD     | 419       | 533    | 26.02%  |
| MMC     | 102       | 135    | 6.34%   |
| Unknown | 10        | 14     | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 897       | 1177   | 57.68%  |
| NVMe | 508       | 691    | 32.67%  |
| MMC  | 102       | 135    | 6.56%   |
| SAS  | 48        | 61     | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 719       | 885    | 73.97%  |
| 0.51-1.0   | 228       | 298    | 23.46%  |
| 1.01-2.0   | 23        | 36     | 2.37%   |
| 3.01-4.0   | 2         | 3      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 349       | 23.92%  |
| 251-500        | 346       | 23.71%  |
| 1-20           | 246       | 16.86%  |
| 501-1000       | 198       | 13.57%  |
| 51-100         | 96        | 6.58%   |
| 1001-2000      | 75        | 5.14%   |
| 21-50          | 57        | 3.91%   |
| Unknown        | 51        | 3.5%    |
| More than 3000 | 26        | 1.78%   |
| 2001-3000      | 15        | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 678       | 44.61%  |
| 21-50          | 209       | 13.75%  |
| 101-250        | 196       | 12.89%  |
| 51-100         | 161       | 10.59%  |
| 251-500        | 131       | 8.62%   |
| 501-1000       | 56        | 3.68%   |
| Unknown        | 51        | 3.36%   |
| 1001-2000      | 25        | 1.64%   |
| More than 3000 | 7         | 0.46%   |
| 2001-3000      | 6         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 126       | 127    | 60.58%  |
| HGST HTS725050A7E630 500GB            | 4         | 5      | 1.92%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 4      | 1.44%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.96%   |
| Toshiba MK1234GSX 120GB               | 2         | 2      | 0.96%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.96%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.96%   |
| Hitachi HTS541610J9SA00 100GB         | 2         | 2      | 0.96%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.48%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.48%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.48%   |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.48%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.48%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 0.48%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.48%   |
| Toshiba MK8037GSX 80GB                | 1         | 1      | 0.48%   |
| Toshiba MK7559GSXP 752GB              | 1         | 1      | 0.48%   |
| Toshiba MK6465GSXN 640GB              | 1         | 1      | 0.48%   |
| Toshiba MK5056GSY 500GB               | 1         | 1      | 0.48%   |
| Toshiba MK2561GSYN 250GB              | 1         | 1      | 0.48%   |
| Toshiba MK2552GSX 250GB               | 1         | 1      | 0.48%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 0.48%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 1      | 0.48%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.48%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 0.48%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 0.48%   |
| Seagate ST9500420ASG 500GB            | 1         | 1      | 0.48%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 0.48%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 0.48%   |
| Seagate ST9250410ASG 250GB            | 1         | 1      | 0.48%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 0.48%   |
| Seagate ST9200420ASG 200GB            | 1         | 1      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 0.48%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 0.48%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 1      | 0.48%   |
| SanDisk SD8SBAT-032G-1006 32GB SSD    | 1         | 1      | 0.48%   |
| SanDisk SD7SB3Q256G1002 256GB SSD     | 1         | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 128       | 129    | 61.54%  |
| Seagate             | 18        | 19     | 8.65%   |
| Hitachi             | 13        | 13     | 6.25%   |
| Toshiba             | 12        | 12     | 5.77%   |
| HGST                | 8         | 9      | 3.85%   |
| Samsung Electronics | 7         | 8      | 3.37%   |
| SK hynix            | 6         | 7      | 2.88%   |
| WDC                 | 5         | 5      | 2.4%    |
| Intel               | 3         | 3      | 1.44%   |
| A-DATA Technology   | 2         | 3      | 0.96%   |
| Micron Technology   | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 2      | 0.48%   |
| Kingston            | 1         | 1      | 0.48%   |
| IBM/Hitachi         | 1         | 1      | 0.48%   |
| Fujitsu             | 1         | 1      | 0.48%   |
| Crucial             | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 18        | 19     | 31.58%  |
| Hitachi     | 13        | 13     | 22.81%  |
| Toshiba     | 12        | 12     | 21.05%  |
| HGST        | 8         | 9      | 14.04%  |
| WDC         | 4         | 4      | 7.02%   |
| IBM/Hitachi | 1         | 1      | 1.75%   |
| Fujitsu     | 1         | 1      | 1.75%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 144       | 147    | 69.57%  |
| HDD  | 56        | 59     | 27.05%  |
| NVMe | 7         | 9      | 3.38%   |

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
| Detected | 742       | 1181   | 50.48%  |
| Works    | 522       | 668    | 35.51%  |
| Malfunc  | 206       | 215    | 14.01%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 955       | 58.09%  |
| Samsung Electronics              | 183       | 11.13%  |
| AMD                              | 157       | 9.55%   |
| SanDisk                          | 81        | 4.93%   |
| SK hynix                         | 64        | 3.89%   |
| Micron Technology                | 42        | 2.55%   |
| Toshiba America Info Systems     | 40        | 2.43%   |
| Kingston Technology Company      | 28        | 1.7%    |
| KIOXIA                           | 25        | 1.52%   |
| Phison Electronics               | 16        | 0.97%   |
| Micron/Crucial Technology        | 8         | 0.49%   |
| Silicon Motion                   | 7         | 0.43%   |
| Union Memory (Shenzhen)          | 5         | 0.3%    |
| ADATA Technology                 | 5         | 0.3%    |
| Lite-On Technology               | 4         | 0.24%   |
| Solid State Storage Technology   | 3         | 0.18%   |
| Silicon Integrated Systems [SiS] | 3         | 0.18%   |
| Nvidia                           | 3         | 0.18%   |
| Lenovo                           | 3         | 0.18%   |
| Realtek Semiconductor            | 2         | 0.12%   |
| JMicron Technology               | 2         | 0.12%   |
| ASMedia Technology               | 2         | 0.12%   |
| VIA Technologies                 | 1         | 0.06%   |
| O2 Micro                         | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.06%   |
| Marvell Technology Group         | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 193       | 10.96%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 132       | 7.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 87        | 4.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 80        | 4.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 75        | 4.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 63        | 3.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 57        | 3.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 52        | 2.95%   |
| Intel Volume Management Device NVMe RAID Controller                              | 47        | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 39        | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 38        | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 35        | 1.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 33        | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 30        | 1.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 28        | 1.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 28        | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 27        | 1.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 27        | 1.53%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 24        | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 23        | 1.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 23        | 1.31%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 22        | 1.25%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 1.02%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 17        | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 16        | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 16        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 13        | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 12        | 0.68%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 11        | 0.62%   |
| Intel SSD 660P Series                                                            | 11        | 0.62%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 11        | 0.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 11        | 0.62%   |
| SK hynix BC511 NVMe SSD                                                          | 10        | 0.57%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 10        | 0.57%   |
| Micron 2300 NVMe SSD [Santana]                                                   | 10        | 0.57%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 10        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 966       | 57.3%   |
| NVMe | 511       | 30.31%  |
| RAID | 118       | 7%      |
| IDE  | 91        | 5.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1133      | 81.04%  |
| AMD    | 265       | 18.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 127       | 9.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 1.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 20        | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 1.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 1.07%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 15        | 1.07%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 1%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 13        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 0.86%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.86%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 12        | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 11        | 0.79%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 0.79%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 10        | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 10        | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 0.71%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 10        | 0.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.57%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 8         | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 8         | 0.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.57%   |
| AMD Custom APU 0405                           | 8         | 0.57%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 7         | 0.5%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 7         | 0.5%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 409       | 29.24%  |
| Intel Core i5           | 270       | 19.3%   |
| Other                   | 118       | 8.43%   |
| Intel Celeron           | 88        | 6.29%   |
| Intel Core 2 Duo        | 78        | 5.58%   |
| Intel Core i3           | 71        | 5.08%   |
| AMD Ryzen 5             | 68        | 4.86%   |
| AMD Ryzen 7             | 55        | 3.93%   |
| Intel Pentium           | 35        | 2.5%    |
| AMD Ryzen 7 PRO         | 30        | 2.14%   |
| Intel Atom              | 25        | 1.79%   |
| AMD A6                  | 14        | 1%      |
| AMD A4                  | 13        | 0.93%   |
| AMD Ryzen 5 PRO         | 10        | 0.71%   |
| AMD Ryzen 3             | 9         | 0.64%   |
| Intel Celeron M         | 8         | 0.57%   |
| AMD A8                  | 8         | 0.57%   |
| Intel Pentium Dual-Core | 7         | 0.5%    |
| Intel Genuine           | 7         | 0.5%    |
| Intel Core 2            | 6         | 0.43%   |
| AMD E1                  | 6         | 0.43%   |
| Intel Pentium Silver    | 5         | 0.36%   |
| Intel Celeron Dual-Core | 5         | 0.36%   |
| Intel Pentium M         | 4         | 0.29%   |
| Intel Pentium Dual      | 4         | 0.29%   |
| AMD Turion II           | 4         | 0.29%   |
| AMD Ryzen 9             | 4         | 0.29%   |
| AMD E                   | 4         | 0.29%   |
| Intel Xeon              | 3         | 0.21%   |
| Intel Core i9           | 3         | 0.21%   |
| AMD Turion 64 X2 Mobile | 3         | 0.21%   |
| AMD Mobile Sempron      | 3         | 0.21%   |
| AMD FX                  | 3         | 0.21%   |
| AMD E2                  | 3         | 0.21%   |
| AMD A10                 | 3         | 0.21%   |
| AMD Athlon X2           | 2         | 0.14%   |
| AMD Athlon II Dual-Core | 2         | 0.14%   |
| AMD A12                 | 2         | 0.14%   |
| Intel Core m5           | 1         | 0.07%   |
| Intel Core Duo          | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 706       | 50.43%  |
| 4       | 406       | 29%     |
| 6       | 119       | 8.5%    |
| 8       | 95        | 6.79%   |
| 1       | 34        | 2.43%   |
| 14      | 13        | 0.93%   |
| 12      | 12        | 0.86%   |
| 10      | 10        | 0.71%   |
| 24      | 2         | 0.14%   |
| 16      | 2         | 0.14%   |
| Unknown | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1398      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1033      | 73.84%  |
| 1       | 365       | 26.09%  |
| Unknown | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1363      | 97.22%  |
| 32-bit         | 21        | 1.5%    |
| Unknown        | 17        | 1.21%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 379       | 26.17%  |
| 0x206a7    | 183       | 12.64%  |
| 0x306a9    | 50        | 3.45%   |
| 0x806ec    | 42        | 2.9%    |
| 0x806ea    | 42        | 2.9%    |
| 0x1067a    | 39        | 2.69%   |
| 0x406e3    | 38        | 2.62%   |
| 0x806c1    | 34        | 2.35%   |
| 0x40651    | 33        | 2.28%   |
| 0x0a50000c | 32        | 2.21%   |
| 0x08600106 | 31        | 2.14%   |
| 0x906ea    | 30        | 2.07%   |
| 0x306c3    | 28        | 1.93%   |
| 0x806e9    | 26        | 1.8%    |
| 0x306d4    | 25        | 1.73%   |
| 0x6fd      | 21        | 1.45%   |
| 0x30678    | 19        | 1.31%   |
| 0xa0652    | 16        | 1.1%    |
| 0x20655    | 16        | 1.1%    |
| 0x506e3    | 15        | 1.04%   |
| 0x706a1    | 14        | 0.97%   |
| 0x08608103 | 14        | 0.97%   |
| 0x906e9    | 13        | 0.9%    |
| 0x10676    | 13        | 0.9%    |
| 0x08108102 | 13        | 0.9%    |
| 0x706e5    | 12        | 0.83%   |
| 0x406c3    | 12        | 0.83%   |
| 0x06006705 | 12        | 0.83%   |
| 0x406c4    | 11        | 0.76%   |
| 0x906ed    | 10        | 0.69%   |
| 0x906a3    | 10        | 0.69%   |
| 0x08600104 | 10        | 0.69%   |
| 0x6e8      | 8         | 0.55%   |
| 0x506c9    | 8         | 0.55%   |
| 0x08600103 | 8         | 0.55%   |
| 0x07030105 | 8         | 0.55%   |
| 0x806eb    | 7         | 0.48%   |
| 0x806d1    | 7         | 0.48%   |
| 0x20652    | 7         | 0.48%   |
| 0x106e5    | 7         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 232       | 16.6%   |
| SandyBridge      | 213       | 15.24%  |
| Haswell          | 88        | 6.29%   |
| IvyBridge        | 75        | 5.36%   |
| Skylake          | 70        | 5.01%   |
| Penryn           | 66        | 4.72%   |
| Zen 2            | 63        | 4.51%   |
| Zen 3            | 56        | 4.01%   |
| Silvermont       | 56        | 4.01%   |
| Unknown          | 51        | 3.65%   |
| TigerLake        | 49        | 3.51%   |
| Core             | 46        | 3.29%   |
| Broadwell        | 35        | 2.5%    |
| Alderlake Hybrid | 35        | 2.5%    |
| Westmere         | 33        | 2.36%   |
| Goldmont plus    | 30        | 2.15%   |
| CometLake        | 23        | 1.65%   |
| Excavator        | 22        | 1.57%   |
| Icelake          | 21        | 1.5%    |
| Zen+             | 20        | 1.43%   |
| P6               | 13        | 0.93%   |
| Bonnell          | 12        | 0.86%   |
| Puma             | 11        | 0.79%   |
| Goldmont         | 11        | 0.79%   |
| Nehalem          | 9         | 0.64%   |
| Bobcat           | 9         | 0.64%   |
| Piledriver       | 8         | 0.57%   |
| Zen              | 7         | 0.5%    |
| K8 Hammer        | 7         | 0.5%    |
| K10              | 7         | 0.5%    |
| Steamroller      | 6         | 0.43%   |
| Jaguar           | 6         | 0.43%   |
| Tremont          | 4         | 0.29%   |
| K8 & K10 hybrid  | 3         | 0.21%   |
| K10 Llano        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1034      | 59.09%  |
| Nvidia                           | 360       | 20.57%  |
| AMD                              | 352       | 20.11%  |
| Silicon Integrated Systems [SiS] | 2         | 0.11%   |
| VIA Technologies                 | 1         | 0.06%   |
| ATI Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 204       | 11.23%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 3.85%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 62        | 3.41%   |
| Intel UHD Graphics 620                                                                   | 56        | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 2.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 42        | 2.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 2.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 39        | 2.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 36        | 1.98%   |
| Intel HD Graphics 620                                                                    | 31        | 1.71%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 30        | 1.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 26        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 1.1%    |
| Intel HD Graphics 630                                                                    | 20        | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 1.1%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 20        | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 20        | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 1.1%    |
| AMD Lucienne                                                                             | 20        | 1.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 19        | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 18        | 0.99%   |
| Intel HD Graphics 530                                                                    | 17        | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 15        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 0.72%   |
| Intel HD Graphics 500                                                                    | 11        | 0.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.55%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 10        | 0.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.55%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 708       | 50.64%  |
| Intel + Nvidia | 259       | 18.53%  |
| 1 x AMD        | 234       | 16.74%  |
| 1 x Nvidia     | 67        | 4.79%   |
| Intel + AMD    | 58        | 4.15%   |
| AMD + Nvidia   | 33        | 2.36%   |
| 2 x AMD        | 27        | 1.93%   |
| 2 x Intel      | 8         | 0.57%   |
| 1 x SiS        | 2         | 0.14%   |
| Other          | 1         | 0.07%   |
| 1 x VIA        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1202      | 85.25%  |
| Proprietary | 170       | 12.06%  |
| Unknown     | 38        | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 956       | 66.67%  |
| 0.01-0.5   | 171       | 11.92%  |
| 1.01-2.0   | 156       | 10.88%  |
| 0.51-1.0   | 66        | 4.6%    |
| 3.01-4.0   | 56        | 3.91%   |
| 5.01-6.0   | 18        | 1.26%   |
| 7.01-8.0   | 6         | 0.42%   |
| 2.01-3.0   | 4         | 0.28%   |
| 8.01-16.0  | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 315       | 18.48%  |
| LG Display              | 212       | 12.43%  |
| BOE                     | 171       | 10.03%  |
| Chimei Innolux          | 168       | 9.85%   |
| Samsung Electronics     | 155       | 9.09%   |
| CPT                     | 129       | 7.57%   |
| Dell                    | 74        | 4.34%   |
| Eizo                    | 62        | 3.64%   |
| Sharp                   | 44        | 2.58%   |
| Lenovo                  | 40        | 2.35%   |
| Chi Mei Optoelectronics | 34        | 1.99%   |
| Hewlett-Packard         | 32        | 1.88%   |
| PANDA                   | 31        | 1.82%   |
| Philips                 | 29        | 1.7%    |
| Goldstar                | 22        | 1.29%   |
| BenQ                    | 20        | 1.17%   |
| LG Philips              | 18        | 1.06%   |
| AOC                     | 18        | 1.06%   |
| CSO                     | 13        | 0.76%   |
| Acer                    | 13        | 0.76%   |
| InfoVision              | 12        | 0.7%    |
| Iiyama                  | 9         | 0.53%   |
| Apple                   | 8         | 0.47%   |
| Sony                    | 7         | 0.41%   |
| Ancor Communications    | 7         | 0.41%   |
| Quanta Display          | 6         | 0.35%   |
| Valve                   | 5         | 0.29%   |
| Panasonic               | 5         | 0.29%   |
| HannStar                | 5         | 0.29%   |
| Toshiba                 | 4         | 0.23%   |
| NEC Computers           | 4         | 0.23%   |
| ASUSTek Computer        | 4         | 0.23%   |
| Fujitsu Siemens         | 3         | 0.18%   |
| Vestel Elektronik       | 2         | 0.12%   |
| Unknown                 | 2         | 0.12%   |
| OEM                     | 2         | 0.12%   |
| JDI                     | 2         | 0.12%   |
| Hitachi                 | 2         | 0.12%   |
| DENON                   | 2         | 0.12%   |
| ViewSonic               | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 127       | 7.28%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 57        | 3.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.86%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 13        | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 12        | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 10        | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.52%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 8         | 0.46%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 7         | 0.4%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 7         | 0.4%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 7         | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 7         | 0.4%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 7         | 0.4%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 7         | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 6         | 0.34%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 6         | 0.34%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 6         | 0.34%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 5         | 0.29%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 5         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch      | 5         | 0.29%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 5         | 0.29%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 5         | 0.29%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 5         | 0.29%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch                | 5         | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 5         | 0.29%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 5         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 678       | 42.7%   |
| 1366x768 (WXGA)    | 283       | 17.82%  |
| 1600x900 (HD+)     | 203       | 12.78%  |
| 3840x2160 (4K)     | 113       | 7.12%   |
| 1280x800 (WXGA)    | 67        | 4.22%   |
| 2560x1440 (QHD)    | 57        | 3.59%   |
| 1920x1200 (WUXGA)  | 46        | 2.9%    |
| 2560x1600          | 21        | 1.32%   |
| 1680x1050 (WSXGA+) | 20        | 1.26%   |
| 1440x900 (WXGA+)   | 18        | 1.13%   |
| 1280x1024 (SXGA)   | 8         | 0.5%    |
| 1024x600           | 8         | 0.5%    |
| 2880x1800          | 6         | 0.38%   |
| 800x1280           | 5         | 0.31%   |
| 3440x1440          | 5         | 0.31%   |
| 1024x768 (XGA)     | 5         | 0.31%   |
| 3840x2400          | 4         | 0.25%   |
| 1360x768           | 4         | 0.25%   |
| 3456x2160          | 3         | 0.19%   |
| 3000x2000          | 3         | 0.19%   |
| 2160x1440          | 3         | 0.19%   |
| 1920x540           | 3         | 0.19%   |
| Unknown            | 3         | 0.19%   |
| 3840x1200          | 2         | 0.13%   |
| 3200x1800 (QHD+)   | 2         | 0.13%   |
| 2880x1620          | 2         | 0.13%   |
| 2160x1350          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 8320x2160          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1080          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 2560x1080          | 1         | 0.06%   |
| 2288x1287          | 1         | 0.06%   |
| 2256x1504          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1920x515           | 1         | 0.06%   |
| 1280x720 (HD)      | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 583       | 34.07%  |
| 13      | 307       | 17.94%  |
| 14      | 199       | 11.63%  |
| 17      | 98        | 5.73%   |
| 24      | 97        | 5.67%   |
| 27      | 73        | 4.27%   |
| 31      | 72        | 4.21%   |
| 23      | 46        | 2.69%   |
| 12      | 33        | 1.93%   |
| 11      | 33        | 1.93%   |
| 21      | 27        | 1.58%   |
| 16      | 26        | 1.52%   |
| Unknown | 14        | 0.82%   |
| 22      | 11        | 0.64%   |
| 10      | 11        | 0.64%   |
| 84      | 8         | 0.47%   |
| 20      | 8         | 0.47%   |
| 18      | 8         | 0.47%   |
| 34      | 6         | 0.35%   |
| 19      | 6         | 0.35%   |
| 33      | 5         | 0.29%   |
| 7       | 5         | 0.29%   |
| 40      | 4         | 0.23%   |
| 32      | 4         | 0.23%   |
| 26      | 4         | 0.23%   |
| 25      | 4         | 0.23%   |
| 54      | 3         | 0.18%   |
| 43      | 3         | 0.18%   |
| 72      | 2         | 0.12%   |
| 49      | 2         | 0.12%   |
| 28      | 2         | 0.12%   |
| 142     | 1         | 0.06%   |
| 60      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 38      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 889       | 52.76%  |
| 201-300        | 283       | 16.8%   |
| 501-600        | 195       | 11.57%  |
| 351-400        | 117       | 6.94%   |
| 601-700        | 84        | 4.99%   |
| 401-500        | 55        | 3.26%   |
| 701-800        | 15        | 0.89%   |
| Unknown        | 14        | 0.83%   |
| 1501-2000      | 10        | 0.59%   |
| 1001-1500      | 10        | 0.59%   |
| 801-900        | 6         | 0.36%   |
| 1-100          | 5         | 0.3%    |
| More than 2000 | 1         | 0.06%   |
| 901-1000       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1177      | 82.42%  |
| 16/10   | 199       | 13.94%  |
| 3/2     | 11        | 0.77%   |
| Unknown | 10        | 0.7%    |
| 5/4     | 8         | 0.56%   |
| 4/3     | 7         | 0.49%   |
| 21/9    | 7         | 0.49%   |
| 0.67    | 5         | 0.35%   |
| 3.20    | 2         | 0.14%   |
| 3.73    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 577       | 33.88%  |
| 81-90          | 308       | 18.09%  |
| 71-80          | 195       | 11.45%  |
| 201-250        | 134       | 7.87%   |
| 351-500        | 89        | 5.23%   |
| 121-130        | 79        | 4.64%   |
| 301-350        | 78        | 4.58%   |
| 251-300        | 38        | 2.23%   |
| 61-70          | 33        | 1.94%   |
| 51-60          | 33        | 1.94%   |
| 111-120        | 25        | 1.47%   |
| 151-200        | 21        | 1.23%   |
| More than 1000 | 17        | 1%      |
| 131-140        | 16        | 0.94%   |
| Unknown        | 14        | 0.82%   |
| 41-50          | 11        | 0.65%   |
| 141-150        | 11        | 0.65%   |
| 501-1000       | 10        | 0.59%   |
| 91-100         | 9         | 0.53%   |
| 1-40           | 5         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 786       | 48.79%  |
| 101-120       | 340       | 21.1%   |
| 51-100        | 306       | 18.99%  |
| 161-240       | 119       | 7.39%   |
| More than 240 | 34        | 2.11%   |
| Unknown       | 14        | 0.87%   |
| 1-50          | 12        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1039      | 71.9%   |
| 2     | 321       | 22.21%  |
| 3     | 45        | 3.11%   |
| 0     | 39        | 2.7%    |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 742       | 32.47%  |
| Realtek Semiconductor                  | 606       | 26.52%  |
| Qualcomm Atheros                       | 392       | 17.16%  |
| Samsung Electronics                    | 130       | 5.69%   |
| Broadcom                               | 126       | 5.51%   |
| Broadcom Limited                       | 48        | 2.1%    |
| MediaTek                               | 46        | 2.01%   |
| Lenovo                                 | 27        | 1.18%   |
| Marvell Technology Group               | 24        | 1.05%   |
| Dell                                   | 17        | 0.74%   |
| ASIX Electronics                       | 17        | 0.74%   |
| Ralink                                 | 13        | 0.57%   |
| Sierra Wireless                        | 12        | 0.53%   |
| DisplayLink                            | 11        | 0.48%   |
| Ralink Technology                      | 10        | 0.44%   |
| TP-Link                                | 9         | 0.39%   |
| Qualcomm Atheros Communications        | 8         | 0.35%   |
| Qualcomm                               | 7         | 0.31%   |
| Ericsson Business Mobile Networks      | 5         | 0.22%   |
| Attansic Technology                    | 5         | 0.22%   |
| Hewlett-Packard                        | 4         | 0.18%   |
| Xiaomi                                 | 3         | 0.13%   |
| Fibocom                                | 3         | 0.13%   |
| Spreadtrum Communications              | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.09%   |
| Huawei Technologies                    | 2         | 0.09%   |
| D-Link                                 | 2         | 0.09%   |
| VIA Technologies                       | 1         | 0.04%   |
| Prusa                                  | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |
| Fujitsu Siemens Computers              | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |
| Arduino SA                             | 1         | 0.04%   |
| AMD                                    | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 380       | 13.89%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 155       | 5.67%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 127       | 4.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 87        | 3.18%   |
| Intel Wi-Fi 6 AX200                                                    | 86        | 3.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 67        | 2.45%   |
| Intel Wireless 8265 / 8275                                             | 65        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 54        | 1.97%   |
| Intel Wireless 7260                                                    | 50        | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 41        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 40        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 40        | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 39        | 1.43%   |
| Intel Wireless 8260                                                    | 37        | 1.35%   |
| Intel Wi-Fi 6 AX201                                                    | 37        | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 35        | 1.28%   |
| Intel Wireless 7265                                                    | 31        | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 31        | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                                  | 30        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 29        | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 29        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 29        | 1.06%   |
| Intel Wireless 3165                                                    | 28        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 26        | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 25        | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 23        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 20        | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 19        | 0.69%   |
| Intel WiFi Link 5100                                                   | 18        | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 18        | 0.66%   |
| Intel Ethernet Connection I217-LM                                      | 18        | 0.66%   |
| Intel 82567LM Gigabit Network Connection                               | 18        | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 17        | 0.62%   |
| Intel Ethernet Connection I219-LM                                      | 17        | 0.62%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                          | 17        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 16        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 16        | 0.59%   |
| Intel Wireless 3160                                                    | 15        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 720       | 49.86%  |
| Qualcomm Atheros                  | 345       | 23.89%  |
| Realtek Semiconductor             | 153       | 10.6%   |
| Broadcom                          | 81        | 5.61%   |
| MediaTek                          | 42        | 2.91%   |
| Broadcom Limited                  | 26        | 1.8%    |
| Ralink                            | 13        | 0.9%    |
| Sierra Wireless                   | 12        | 0.83%   |
| Dell                              | 11        | 0.76%   |
| Ralink Technology                 | 10        | 0.69%   |
| TP-Link                           | 8         | 0.55%   |
| Qualcomm Atheros Communications   | 8         | 0.55%   |
| Qualcomm                          | 6         | 0.42%   |
| Fibocom                           | 3         | 0.21%   |
| Hewlett-Packard                   | 2         | 0.14%   |
| Fujitsu Siemens Computers         | 1         | 0.07%   |
| Ericsson Business Mobile Networks | 1         | 0.07%   |
| D-Link                            | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 155       | 10.7%   |
| Intel Wi-Fi 6 AX200                                                     | 86        | 5.94%   |
| Intel Wireless 8265 / 8275                                              | 65        | 4.49%   |
| Intel Wireless 7260                                                     | 50        | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 39        | 2.69%   |
| Intel Wireless 8260                                                     | 37        | 2.56%   |
| Intel Wi-Fi 6 AX201                                                     | 37        | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 2.42%   |
| Intel Wireless 7265                                                     | 31        | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 31        | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 29        | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 29        | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 2%      |
| Intel Wireless 3165                                                     | 28        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 1.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 25        | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 23        | 1.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 20        | 1.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 19        | 1.31%   |
| Intel WiFi Link 5100                                                    | 18        | 1.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 16        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.1%    |
| Intel Wireless 3160                                                     | 15        | 1.04%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 11        | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 11        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.69%   |
| Intel Ultimate N WiFi Link 5300                                         | 10        | 0.69%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 536       | 43.19%  |
| Intel                                  | 307       | 24.74%  |
| Samsung Electronics                    | 130       | 10.48%  |
| Qualcomm Atheros                       | 86        | 6.93%   |
| Broadcom                               | 54        | 4.35%   |
| Lenovo                                 | 27        | 2.18%   |
| Marvell Technology Group               | 24        | 1.93%   |
| Broadcom Limited                       | 22        | 1.77%   |
| ASIX Electronics                       | 17        | 1.37%   |
| DisplayLink                            | 11        | 0.89%   |
| Attansic Technology                    | 5         | 0.4%    |
| MediaTek                               | 4         | 0.32%   |
| Xiaomi                                 | 3         | 0.24%   |
| Spreadtrum Communications              | 2         | 0.16%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.16%   |
| VIA Technologies                       | 1         | 0.08%   |
| TP-Link                                | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Qualcomm                               | 1         | 0.08%   |
| Motorola PCS                           | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| Huawei Technologies                    | 1         | 0.08%   |
| Hewlett-Packard                        | 1         | 0.08%   |
| Google                                 | 1         | 0.08%   |
| Foxconn / Hon Hai                      | 1         | 0.08%   |
| D-Link                                 | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 380       | 30.02%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 127       | 10.03%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 87        | 6.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 67        | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 54        | 4.27%   |
| Intel Ethernet Connection (4) I219-LM                                          | 30        | 2.37%   |
| Intel Ethernet Connection I217-LM                                              | 18        | 1.42%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.42%   |
| Intel Ethernet Connection I219-LM                                              | 17        | 1.34%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 15        | 1.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 14        | 1.11%   |
| Intel Ethernet Connection (4) I219-V                                           | 14        | 1.11%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 13        | 1.03%   |
| Intel Ethernet Connection (6) I219-V                                           | 13        | 1.03%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 12        | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                                          | 12        | 0.95%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                                          | 9         | 0.71%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 9         | 0.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 7         | 0.55%   |
| Intel Ethernet Connection I219-V                                               | 7         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.47%   |
| Realtek Killer E2600 GbE Controller                                            | 6         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 6         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 6         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.47%   |
| Intel Ethernet Connection (16) I219-LM                                         | 6         | 0.47%   |
| Intel Ethernet Connection (11) I219-LM                                         | 6         | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 6         | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 0.47%   |
| Intel Ethernet Connection I217-V                                               | 5         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1378      | 53.66%  |
| Ethernet | 1169      | 45.52%  |
| Modem    | 20        | 0.78%   |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1032      | 69.4%   |
| Ethernet | 455       | 30.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 941       | 67.21%  |
| 1     | 419       | 29.93%  |
| 0     | 26        | 1.86%   |
| 3     | 14        | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1201      | 84.52%  |
| Yes  | 220       | 15.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 523       | 50%     |
| Realtek Semiconductor           | 103       | 9.85%   |
| Qualcomm Atheros Communications | 77        | 7.36%   |
| IMC Networks                    | 74        | 7.07%   |
| Foxconn / Hon Hai               | 56        | 5.35%   |
| Broadcom                        | 55        | 5.26%   |
| Lite-On Technology              | 45        | 4.3%    |
| Hewlett-Packard                 | 29        | 2.77%   |
| Dell                            | 18        | 1.72%   |
| ASUSTek Computer                | 15        | 1.43%   |
| Ralink                          | 10        | 0.96%   |
| Apple                           | 7         | 0.67%   |
| Cambridge Silicon Radio         | 6         | 0.57%   |
| MediaTek                        | 5         | 0.48%   |
| Alps Electric                   | 5         | 0.48%   |
| Toshiba                         | 4         | 0.38%   |
| Realtek                         | 4         | 0.38%   |
| Foxconn International           | 3         | 0.29%   |
| USI                             | 2         | 0.19%   |
| Ralink Technology               | 2         | 0.19%   |
| Micro Star International        | 1         | 0.1%    |
| Fujitsu Siemens Computers       | 1         | 0.1%    |
| Askey Computer                  | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 212       | 20.27%  |
| Intel AX201 Bluetooth                                                               | 92        | 8.8%    |
| Intel AX200 Bluetooth                                                               | 86        | 8.22%   |
| Realtek Bluetooth Radio                                                             | 73        | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 66        | 6.31%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 31        | 2.96%   |
| Intel Bluetooth Device                                                              | 31        | 2.96%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 24        | 2.29%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 1.91%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 18        | 1.72%   |
| IMC Networks Bluetooth Radio                                                        | 17        | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1.53%   |
| IMC Networks Bluetooth Device                                                       | 16        | 1.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 1.43%   |
| IMC Networks Wireless_Device                                                        | 15        | 1.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 15        | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 14        | 1.34%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 13        | 1.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.15%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 1.05%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 0.96%   |
| Dell DW375 Bluetooth Module                                                         | 10        | 0.96%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 0.76%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 0.76%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 8         | 0.76%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.57%   |
| Lite-On Bluetooth Device                                                            | 6         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.57%   |
| Intel AX210 Bluetooth                                                               | 6         | 0.57%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 6         | 0.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.57%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.48%   |
| Lite-On Wireless_Device                                                             | 5         | 0.48%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1109      | 63.55%  |
| AMD                                  | 298       | 17.08%  |
| Nvidia                               | 171       | 9.8%    |
| Lenovo                               | 33        | 1.89%   |
| C-Media Electronics                  | 21        | 1.2%    |
| Realtek Semiconductor                | 20        | 1.15%   |
| GN Netcom                            | 18        | 1.03%   |
| Logitech                             | 8         | 0.46%   |
| Hewlett-Packard                      | 8         | 0.46%   |
| JMTek                                | 6         | 0.34%   |
| Creative Technology                  | 5         | 0.29%   |
| Plantronics                          | 4         | 0.23%   |
| Kingston Technology                  | 4         | 0.23%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.17%   |
| Sennheiser Communications            | 3         | 0.17%   |
| Yamaha                               | 2         | 0.11%   |
| RODE Microphones                     | 2         | 0.11%   |
| Razer USA                            | 2         | 0.11%   |
| Harman                               | 2         | 0.11%   |
| GYROCOM C&C                          | 2         | 0.11%   |
| Dell                                 | 2         | 0.11%   |
| BEHRINGER International              | 2         | 0.11%   |
| Yealink Network Technology           | 1         | 0.06%   |
| VIA Technologies                     | 1         | 0.06%   |
| Trust                                | 1         | 0.06%   |
| Toshiba                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Texas Instruments                    | 1         | 0.06%   |
| Syntek                               | 1         | 0.06%   |
| SteelSeries ApS                      | 1         | 0.06%   |
| Samson Technologies                  | 1         | 0.06%   |
| Orbbec 3D Technology International   | 1         | 0.06%   |
| M-Audio                              | 1         | 0.06%   |
| Generalplus Technology               | 1         | 0.06%   |
| Focusrite-Novation                   | 1         | 0.06%   |
| ELMCU                                | 1         | 0.06%   |
| DigiTech                             | 1         | 0.06%   |
| Datelink Technology                  | 1         | 0.06%   |
| Conexant Systems                     | 1         | 0.06%   |
| Cambridge Silicon Radio              | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 199       | 9.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 175       | 8.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 137       | 6.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 111       | 5.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 87        | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 61        | 2.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 49        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 48        | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 47        | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 42        | 2.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 42        | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 41        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 37        | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 37        | 1.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 35        | 1.68%   |
| Intel Broadwell-U Audio Controller                                                                | 35        | 1.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 35        | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 34        | 1.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 33        | 1.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 29        | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 23        | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 22        | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 22        | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 1.01%   |
| Realtek Semiconductor USB Audio                                                                   | 20        | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20        | 0.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 20        | 0.96%   |
| AMD High Definition Audio Controller                                                              | 20        | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 19        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 19        | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 19        | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 0.81%   |
| Nvidia Audio device                                                                               | 15        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 0.62%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 12        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 242       | 25%     |
| SK hynix             | 191       | 19.73%  |
| Elpida               | 143       | 14.77%  |
| Micron Technology    | 130       | 13.43%  |
| Kingston             | 102       | 10.54%  |
| Unknown              | 43        | 4.44%   |
| Crucial              | 30        | 3.1%    |
| Ramaxel Technology   | 23        | 2.38%   |
| Unknown (ABCD)       | 14        | 1.45%   |
| Corsair              | 12        | 1.24%   |
| A-DATA Technology    | 10        | 1.03%   |
| Nanya Technology     | 8         | 0.83%   |
| Patriot              | 5         | 0.52%   |
| Transcend            | 3         | 0.31%   |
| Unknown              | 3         | 0.31%   |
| Unknown (AB)         | 1         | 0.1%    |
| ProMos/Mosel Vitelic | 1         | 0.1%    |
| OnBoard              | 1         | 0.1%    |
| Nayna                | 1         | 0.1%    |
| Golden Empire        | 1         | 0.1%    |
| G.Skill              | 1         | 0.1%    |
| fef5                 | 1         | 0.1%    |
| ASint Technology     | 1         | 0.1%    |
| 48spaces             | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                          | 126       | 12.49%  |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 17        | 1.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 14        | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 12        | 1.19%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 12        | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 11        | 1.09%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 10        | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 9         | 0.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 9         | 0.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 0.89%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 0.79%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 7         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 7         | 0.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 7         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 7         | 0.69%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s               | 7         | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 5         | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 5         | 0.5%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 5         | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 0.5%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 5         | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 5         | 0.5%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 5         | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.4%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 4         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.4%    |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.4%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 365       | 43.76%  |
| DDR3    | 322       | 38.61%  |
| LPDDR4  | 54        | 6.47%   |
| DDR2    | 29        | 3.48%   |
| LPDDR3  | 20        | 2.4%    |
| SDRAM   | 15        | 1.8%    |
| LPDDR5  | 14        | 1.68%   |
| DDR5    | 8         | 0.96%   |
| DDR     | 4         | 0.48%   |
| Unknown | 3         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 750       | 89.39%  |
| Row Of Chips | 74        | 8.82%   |
| Chip         | 10        | 1.19%   |
| Unknown      | 3         | 0.36%   |
| DIMM         | 2         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 307       | 34.11%  |
| 2048  | 205       | 22.78%  |
| 4096  | 182       | 20.22%  |
| 16384 | 154       | 17.11%  |
| 32768 | 26        | 2.89%   |
| 1024  | 21        | 2.33%   |
| 512   | 2         | 0.22%   |
| 6144  | 1         | 0.11%   |
| 3072  | 1         | 0.11%   |
| 256   | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 182       | 20.54%  |
| 1333    | 146       | 16.48%  |
| 1600    | 135       | 15.24%  |
| 2667    | 130       | 14.67%  |
| 2400    | 67        | 7.56%   |
| 2133    | 37        | 4.18%   |
| 1334    | 34        | 3.84%   |
| 4267    | 20        | 2.26%   |
| 667     | 14        | 1.58%   |
| Unknown | 14        | 1.58%   |
| 6400    | 12        | 1.35%   |
| 1067    | 12        | 1.35%   |
| 3266    | 11        | 1.24%   |
| 1867    | 11        | 1.24%   |
| 2048    | 7         | 0.79%   |
| 800     | 7         | 0.79%   |
| 4800    | 6         | 0.68%   |
| 4266    | 6         | 0.68%   |
| 4199    | 6         | 0.68%   |
| 975     | 5         | 0.56%   |
| 533     | 5         | 0.56%   |
| 8400    | 4         | 0.45%   |
| 1066    | 4         | 0.45%   |
| 5600    | 3         | 0.34%   |
| 3733    | 3         | 0.34%   |
| 7500    | 1         | 0.11%   |
| 5500    | 1         | 0.11%   |
| 2933    | 1         | 0.11%   |
| 1639    | 1         | 0.11%   |
| 1400    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 2         | 33.33%  |
| Xerox               | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Prolific Technology | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Xerox Phaser 3260                | 1         | 16.67%  |
| Samsung M2070 Series             | 1         | 16.67%  |
| Prolific PL2305 Parallel Port    | 1         | 16.67%  |
| HP LaserJet Professional P 1102w | 1         | 16.67%  |
| Canon LBP3010/LBP3018/LBP3050    | 1         | 16.67%  |
| Canon G2020 series               | 1         | 16.67%  |

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
| Chicony Electronics                    | 303       | 26.81%  |
| Realtek Semiconductor                  | 110       | 9.73%   |
| IMC Networks                           | 110       | 9.73%   |
| Microdia                               | 91        | 8.05%   |
| Bison Electronics                      | 74        | 6.55%   |
| Sunplus Innovation Technology          | 73        | 6.46%   |
| Quanta                                 | 51        | 4.51%   |
| Lite-On Technology                     | 46        | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 3.98%   |
| Acer                                   | 40        | 3.54%   |
| Suyin                                  | 36        | 3.19%   |
| Syntek                                 | 31        | 2.74%   |
| Apple                                  | 15        | 1.33%   |
| Luxvisions Innotech Limited            | 13        | 1.15%   |
| Ricoh                                  | 12        | 1.06%   |
| Lenovo                                 | 11        | 0.97%   |
| Alcor Micro                            | 11        | 0.97%   |
| Logitech                               | 9         | 0.8%    |
| Sonix Technology                       | 6         | 0.53%   |
| Samsung Electronics                    | 6         | 0.53%   |
| Primax Electronics                     | 5         | 0.44%   |
| USB Camera                             | 4         | 0.35%   |
| Silicon Motion                         | 3         | 0.27%   |
| Microsoft                              | 2         | 0.18%   |
| Intel                                  | 2         | 0.18%   |
| 8SSC21D67422V1SR3AV5KW1                | 2         | 0.18%   |
| Z-Star Microelectronics                | 1         | 0.09%   |
| Sunplus Technology                     | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Ruision                                | 1         | 0.09%   |
| Pixart Imaging                         | 1         | 0.09%   |
| Orbbec 3D Technology International     | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| lihappe8                               | 1         | 0.09%   |
| KYE Systems (Mouse Systems)            | 1         | 0.09%   |
| Hopewin Electronic Material            | 1         | 0.09%   |
| Goodong Industry                       | 1         | 0.09%   |
| Genesys Logic                          | 1         | 0.09%   |
| GEMBIRD                                | 1         | 0.09%   |
| eMPIA Technology                       | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 80        | 7.05%   |
| IMC Networks Integrated Camera                | 49        | 4.32%   |
| Realtek Integrated_Webcam_HD                  | 43        | 3.79%   |
| Microdia Integrated_Webcam_HD                 | 42        | 3.7%    |
| Chicony HD WebCam                             | 31        | 2.73%   |
| Chicony HP HD Camera                          | 30        | 2.64%   |
| IMC Networks USB2.0 HD UVC WebCam             | 24        | 2.11%   |
| Bison Integrated Camera                       | 22        | 1.94%   |
| Lite-On HP HD Camera                          | 21        | 1.85%   |
| Bison Lenovo EasyCamera                       | 18        | 1.59%   |
| Syntek Integrated Camera                      | 17        | 1.5%    |
| Realtek USB Camera                            | 17        | 1.5%    |
| Sunplus Integrated_Webcam_HD                  | 16        | 1.41%   |
| Chicony Integrated Camera (1280x720@30)       | 14        | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 13        | 1.15%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 12        | 1.06%   |
| Quanta HP HD Camera                           | 12        | 1.06%   |
| Lite-On Integrated Camera                     | 12        | 1.06%   |
| Acer SunplusIT Integrated Camera              | 12        | 1.06%   |
| Acer Integrated Camera                        | 12        | 1.06%   |
| Quanta HD User Facing                         | 11        | 0.97%   |
| Microdia Integrated Webcam                    | 11        | 0.97%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 11        | 0.97%   |
| Sunplus HD WebCam                             | 10        | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                 | 10        | 0.88%   |
| Chicony Lenovo EasyCamera                     | 9         | 0.79%   |
| Bison Lenovo Integrated Webcam                | 9         | 0.79%   |
| Syntek Lenovo EasyCamera                      | 8         | 0.7%    |
| Lenovo Integrated Webcam                      | 8         | 0.7%    |
| Chicony HP HD Webcam                          | 8         | 0.7%    |
| Chicony FJ Camera                             | 8         | 0.7%    |
| Sunplus Laptop Integrated Webcam HD           | 7         | 0.62%   |
| Sunplus Asus Webcam                           | 7         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 7         | 0.62%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 6         | 0.53%   |
| Sunplus HP HD Webcam [Fixed]                  | 6         | 0.53%   |
| Samsung Galaxy series, misc. (MTP mode)       | 6         | 0.53%   |
| Realtek USB2.0 VGA UVC WebCam                 | 6         | 0.53%   |
| Realtek USB2.0 HD UVC WebCam                  | 6         | 0.53%   |
| Realtek Acer 640 x 480 laptop camera          | 6         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 107       | 34.74%  |
| Validity Sensors                   | 103       | 33.44%  |
| Shenzhen Goodix Technology         | 34        | 11.04%  |
| AuthenTec                          | 29        | 9.42%   |
| Upek                               | 14        | 4.55%   |
| Elan Microelectronics              | 10        | 3.25%   |
| LighTuning Technology              | 7         | 2.27%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.65%   |
| STMicroelectronics                 | 1         | 0.32%   |
| Microsoft                          | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 10.06%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 9.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 6.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 5.84%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 5.84%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 4.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 14        | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 4.22%   |
| AuthenTec AES2810                                                          | 12        | 3.9%    |
| Validity Sensors VFS491                                                    | 11        | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 2.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 2.92%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.6%    |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.27%   |
| AuthenTec AES1600                                                          | 7         | 2.27%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.95%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.95%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.95%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.62%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.97%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.97%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.97%   |
| Synaptics  WBDI                                                            | 3         | 0.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.65%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.65%   |
| Synaptics WBDI                                                             | 2         | 0.65%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.65%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.32%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.32%   |
| Synaptics WBDI Device                                                      | 1         | 0.32%   |
| Synaptics UWP WBDI                                                         | 1         | 0.32%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.32%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 77        | 55%     |
| Alcor Micro               | 42        | 30%     |
| O2 Micro                  | 9         | 6.43%   |
| Lenovo                    | 5         | 3.57%   |
| Upek                      | 2         | 1.43%   |
| SCM Microsystems          | 2         | 1.43%   |
| Purism, SPC               | 1         | 0.71%   |
| Gemalto (was Gemplus)     | 1         | 0.71%   |
| Aladdin Knowledge Systems | 1         | 0.71%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 42        | 30%     |
| Broadcom 58200                                                               | 25        | 17.86%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 14.29%  |
| Broadcom 5880                                                                | 18        | 12.86%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.71%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.43%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.43%   |
| Purism, SPC Librem Key                                                       | 1         | 0.71%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.71%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.71%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.71%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 818       | 57.4%   |
| 1     | 455       | 31.93%  |
| 2     | 125       | 8.77%   |
| 3     | 21        | 1.47%   |
| 5     | 3         | 0.21%   |
| 4     | 3         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 302       | 39.22%  |
| Graphics card            | 144       | 18.7%   |
| Chipcard                 | 121       | 15.71%  |
| Net/wireless             | 48        | 6.23%   |
| Multimedia controller    | 34        | 4.42%   |
| Camera                   | 25        | 3.25%   |
| Storage                  | 24        | 3.12%   |
| Bluetooth                | 22        | 2.86%   |
| Communication controller | 13        | 1.69%   |
| Card reader              | 13        | 1.69%   |
| Flash memory             | 7         | 0.91%   |
| Net/ethernet             | 6         | 0.78%   |
| Modem                    | 5         | 0.65%   |
| Sound                    | 4         | 0.52%   |
| Storage/ata              | 1         | 0.13%   |
| Network                  | 1         | 0.13%   |

