Ubuntu Unity - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Unity.

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

Total: 823

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 15-cc5xx    | [68af03eefe](https://linux-hardware.org/?probe=68af03eefe) | Jun 10, 2023 |
| Dell          | G15 5511                    | [ddee46cbfa](https://linux-hardware.org/?probe=ddee46cbfa) | Jun 07, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [3067e6332a](https://linux-hardware.org/?probe=3067e6332a) | Jun 02, 2023 |
| GPU Compan... | GWTN156-11                  | [544fc521be](https://linux-hardware.org/?probe=544fc521be) | May 30, 2023 |
| Samsung       | 950XED                      | [8d4e3bcb94](https://linux-hardware.org/?probe=8d4e3bcb94) | May 08, 2023 |
| Dell          | XPS 15 9570                 | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Unknown       | AG958                       | [70aa4b6cf2](https://linux-hardware.org/?probe=70aa4b6cf2) | May 08, 2023 |
| Toshiba       | TECRA A11                   | [456421ff37](https://linux-hardware.org/?probe=456421ff37) | May 07, 2023 |
| Acer          | Aspire 7530G                | [5c19c9f6e4](https://linux-hardware.org/?probe=5c19c9f6e4) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [2016e42226](https://linux-hardware.org/?probe=2016e42226) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [4a6eed684e](https://linux-hardware.org/?probe=4a6eed684e) | Apr 26, 2023 |
| ASUSTek       | X45C                        | [759ed58d76](https://linux-hardware.org/?probe=759ed58d76) | Apr 23, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [85a8b8b452](https://linux-hardware.org/?probe=85a8b8b452) | Mar 26, 2023 |
| Alienware     | m17 R3                      | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Dell          | Latitude 7480               | [c4e5e8923c](https://linux-hardware.org/?probe=c4e5e8923c) | Mar 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [e1733fa8c9](https://linux-hardware.org/?probe=e1733fa8c9) | Mar 01, 2023 |
| Dell          | Latitude 7330               | [caf4a2b3ac](https://linux-hardware.org/?probe=caf4a2b3ac) | Feb 16, 2023 |
| HP            | Mini 210-1000               | [a97b152ab2](https://linux-hardware.org/?probe=a97b152ab2) | Feb 09, 2023 |
| HP            | Mini 210-1000               | [1546202e50](https://linux-hardware.org/?probe=1546202e50) | Feb 08, 2023 |
| ASUSTek       | 1101HA                      | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| HP            | ProBook 455 G1              | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | [c2dd87db86](https://linux-hardware.org/?probe=c2dd87db86) | Jan 17, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [674f3e9cae](https://linux-hardware.org/?probe=674f3e9cae) | Jan 17, 2023 |
| Acer          | Aspire V5-122P              | [c5d70f195f](https://linux-hardware.org/?probe=c5d70f195f) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [4d89e9dec4](https://linux-hardware.org/?probe=4d89e9dec4) | Jan 14, 2023 |
| Acer          | Aspire A515-46              | [79cb54f05f](https://linux-hardware.org/?probe=79cb54f05f) | Jan 12, 2023 |
| Lenovo        | ThinkPad Edge 030244U       | [f9833c6d79](https://linux-hardware.org/?probe=f9833c6d79) | Jan 03, 2023 |
| ASUSTek       | G71GX                       | [7650c66520](https://linux-hardware.org/?probe=7650c66520) | Jan 01, 2023 |
| HP            | ZBook Studio G5             | [6d0b6881ac](https://linux-hardware.org/?probe=6d0b6881ac) | Dec 30, 2022 |
| Samsung       | 550XBE/350XBE               | [33c4b80d0a](https://linux-hardware.org/?probe=33c4b80d0a) | Dec 29, 2022 |
| Apple         | MacBookPro9,2               | [ef194165fc](https://linux-hardware.org/?probe=ef194165fc) | Dec 24, 2022 |
| Lenovo        | IdeaPad S110 20126          | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [7fe5232b14](https://linux-hardware.org/?probe=7fe5232b14) | Dec 20, 2022 |
| Dell          | XPS 13 9370                 | [0f360efa8f](https://linux-hardware.org/?probe=0f360efa8f) | Dec 20, 2022 |
| Dell          | Latitude E5420              | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Irbis         | NB264                       | [4bb5935a41](https://linux-hardware.org/?probe=4bb5935a41) | Dec 19, 2022 |
| Irbis         | NB264                       | [1209e6c899](https://linux-hardware.org/?probe=1209e6c899) | Dec 19, 2022 |
| SINTRONES     | AMB-5000G1                  | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Gigabyte      | MMLP3AP-00                  | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| HP            | Pavilion dv7                | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| HP            | ProBook 650 G2              | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| ASUSTek       | 1225B                       | [87f1b143de](https://linux-hardware.org/?probe=87f1b143de) | Nov 27, 2022 |
| Chuwi         | CoreBook X                  | [f0e76c8866](https://linux-hardware.org/?probe=f0e76c8866) | Nov 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | [37d3dc95f1](https://linux-hardware.org/?probe=37d3dc95f1) | Nov 25, 2022 |
| HP            | EliteBook 8470p             | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| HP            | ZBook 14                    | [27b57aad86](https://linux-hardware.org/?probe=27b57aad86) | Nov 12, 2022 |
| Dell          | Inspiron 3543               | [227f62cdb9](https://linux-hardware.org/?probe=227f62cdb9) | Nov 11, 2022 |
| HP            | EliteBook 8470p             | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| Gigabyte      | AERO 15-X9                  | [f4ef4d30b0](https://linux-hardware.org/?probe=f4ef4d30b0) | Nov 06, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | [73ba8f75b7](https://linux-hardware.org/?probe=73ba8f75b7) | Nov 04, 2022 |
| HP            | Pavilion 10 TS              | [49e1be474a](https://linux-hardware.org/?probe=49e1be474a) | Nov 01, 2022 |
| ASUSTek       | U50Vg                       | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | G60                         | [e9af8a9e61](https://linux-hardware.org/?probe=e9af8a9e61) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c9393d50b5](https://linux-hardware.org/?probe=c9393d50b5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [5199be5418](https://linux-hardware.org/?probe=5199be5418) | Oct 24, 2022 |
| Acer          | Aspire A515-51              | [64030c9ba3](https://linux-hardware.org/?probe=64030c9ba3) | Oct 24, 2022 |
| Samsung       | 550P5C/550P7C               | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| Acer          | Aspire E5-551               | [0e72f3b2e8](https://linux-hardware.org/?probe=0e72f3b2e8) | Oct 21, 2022 |
| Dell          | XPS 13 9300                 | [ec9a97a15d](https://linux-hardware.org/?probe=ec9a97a15d) | Oct 20, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| Lenovo        | G580 2689H2G                | [1d81a2fb3b](https://linux-hardware.org/?probe=1d81a2fb3b) | Oct 18, 2022 |
| Notebook      | N15_17RD,RD2                | [50713b916b](https://linux-hardware.org/?probe=50713b916b) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | [8a3de9dbf2](https://linux-hardware.org/?probe=8a3de9dbf2) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | [3dd30d87be](https://linux-hardware.org/?probe=3dd30d87be) | Oct 18, 2022 |
| HP            | Presario C300 (RM500EA#A... | [c35d7b0ee3](https://linux-hardware.org/?probe=c35d7b0ee3) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| Dell          | Precision M3800             | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| IBM           | ThinkPad R51 1836Q4U        | [f77e633009](https://linux-hardware.org/?probe=f77e633009) | Oct 11, 2022 |
| Unknown       | Unknown                     | [fc558ece05](https://linux-hardware.org/?probe=fc558ece05) | Oct 02, 2022 |
| Dell          | Inspiron 3442               | [8272a6655b](https://linux-hardware.org/?probe=8272a6655b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | [be9d7b3e42](https://linux-hardware.org/?probe=be9d7b3e42) | Sep 28, 2022 |
| Acer          | AO532h                      | [383ce70d97](https://linux-hardware.org/?probe=383ce70d97) | Sep 25, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | [fef4bc54eb](https://linux-hardware.org/?probe=fef4bc54eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | [db6bdb0dbd](https://linux-hardware.org/?probe=db6bdb0dbd) | Sep 20, 2022 |
| Dell          | System XPS L702X            | [6f7b318b6d](https://linux-hardware.org/?probe=6f7b318b6d) | Sep 17, 2022 |
| Dell          | System XPS L702X            | [4b812d3653](https://linux-hardware.org/?probe=4b812d3653) | Sep 17, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | [3b63a75571](https://linux-hardware.org/?probe=3b63a75571) | Sep 16, 2022 |
| HUAWEI        | MACH-WX9                    | [f90bed17e2](https://linux-hardware.org/?probe=f90bed17e2) | Sep 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1d387a1216](https://linux-hardware.org/?probe=1d387a1216) | Sep 07, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [bceac5a658](https://linux-hardware.org/?probe=bceac5a658) | Aug 30, 2022 |
| Dell          | Latitude E6500              | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| Samsung       | R59P/R60P/R61P              | [552d907afc](https://linux-hardware.org/?probe=552d907afc) | Aug 20, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Lenovo        | ThinkPad Edge 030244U       | [b8b2ea30e1](https://linux-hardware.org/?probe=b8b2ea30e1) | Aug 08, 2022 |
| ASUSTek       | 1015PX                      | [af43595e7b](https://linux-hardware.org/?probe=af43595e7b) | Aug 08, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [2d4b30ec72](https://linux-hardware.org/?probe=2d4b30ec72) | Aug 07, 2022 |
| Samsung       | R59P/R60P/R61P              | [0ebff09d2b](https://linux-hardware.org/?probe=0ebff09d2b) | Aug 07, 2022 |
| HP            | ZBook 17 G3                 | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| Samsung       | R59P/R60P/R61P              | [93794bf0b1](https://linux-hardware.org/?probe=93794bf0b1) | Aug 01, 2022 |
| Samsung       | R59P/R60P/R61P              | [b0b9ddad28](https://linux-hardware.org/?probe=b0b9ddad28) | Jul 30, 2022 |
| Apple         | MacBookPro9,2               | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| Toshiba       | EQUIUM A110                 | [4b6ace9122](https://linux-hardware.org/?probe=4b6ace9122) | Jul 22, 2022 |
| Dell          | Inspiron 5566               | [f653a494f3](https://linux-hardware.org/?probe=f653a494f3) | Jul 18, 2022 |
| HP            | Presario V2000 (EC158UA#... | [d46bb41a18](https://linux-hardware.org/?probe=d46bb41a18) | Jul 08, 2022 |
| HP            | Presario V2000 (EC158UA#... | [c55a6d7cca](https://linux-hardware.org/?probe=c55a6d7cca) | Jul 08, 2022 |
| Samsung       | R59P/R60P/R61P              | [c09a3e0c24](https://linux-hardware.org/?probe=c09a3e0c24) | Jul 08, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [672749ef0e](https://linux-hardware.org/?probe=672749ef0e) | Jun 22, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [f395d01890](https://linux-hardware.org/?probe=f395d01890) | Jun 21, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [ba10f6ee4f](https://linux-hardware.org/?probe=ba10f6ee4f) | Jun 14, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [4f9d7a297e](https://linux-hardware.org/?probe=4f9d7a297e) | Jun 05, 2022 |
| Dell          | Inspiron 15 3511            | [3fbca187e7](https://linux-hardware.org/?probe=3fbca187e7) | May 31, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [55e99cb697](https://linux-hardware.org/?probe=55e99cb697) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| HP            | Compaq 6730s                | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| HP            | Compaq 6720s                | [b7ea743814](https://linux-hardware.org/?probe=b7ea743814) | May 22, 2022 |
| HP            | Compaq 6720s                | [c0b723e185](https://linux-hardware.org/?probe=c0b723e185) | May 22, 2022 |
| HP            | Mini 210-1000               | [f4d6735690](https://linux-hardware.org/?probe=f4d6735690) | May 20, 2022 |
| HP            | OMEN by Laptop              | [0a25740096](https://linux-hardware.org/?probe=0a25740096) | May 18, 2022 |
| HP            | Mini 110-1000               | [e1a5afc203](https://linux-hardware.org/?probe=e1a5afc203) | May 06, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [329673fcbf](https://linux-hardware.org/?probe=329673fcbf) | May 03, 2022 |
| HP            | 255 G6 Notebook PC          | [f639c7c8f5](https://linux-hardware.org/?probe=f639c7c8f5) | Apr 29, 2022 |
| Acer          | TM4750                      | [8254e2b47d](https://linux-hardware.org/?probe=8254e2b47d) | Apr 27, 2022 |
| Toshiba       | Satellite L300              | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Dell          | Latitude 5420               | [7ef3e515d9](https://linux-hardware.org/?probe=7ef3e515d9) | Apr 15, 2022 |
| Dell          | Latitude D630               | [6c715d7619](https://linux-hardware.org/?probe=6c715d7619) | Apr 09, 2022 |
| Timi          | TM1701                      | [e2930f3884](https://linux-hardware.org/?probe=e2930f3884) | Apr 06, 2022 |
| Lenovo        | ThinkPad P70 20ESS04S00     | [18bcdf72db](https://linux-hardware.org/?probe=18bcdf72db) | Apr 05, 2022 |
| HP            | ProBook 6550b               | [d337221af6](https://linux-hardware.org/?probe=d337221af6) | Apr 01, 2022 |
| eMachines     | eM350                       | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Panasonic     | CF-19AHUDX1M                | [638470e61d](https://linux-hardware.org/?probe=638470e61d) | Mar 25, 2022 |
| ASUSTek       | N501VW                      | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Apple         | MacBookPro1,1               | [4add06ac06](https://linux-hardware.org/?probe=4add06ac06) | Mar 17, 2022 |
| Apple         | MacBookPro1,1               | [1f948586ca](https://linux-hardware.org/?probe=1f948586ca) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | [737a2d4c61](https://linux-hardware.org/?probe=737a2d4c61) | Mar 14, 2022 |
| Medion        | Akoya THE TOUCH 10          | [be2c2c791c](https://linux-hardware.org/?probe=be2c2c791c) | Mar 09, 2022 |
| Apple         | MacBookPro1,1               | [6563e94c95](https://linux-hardware.org/?probe=6563e94c95) | Mar 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [33ce116b8a](https://linux-hardware.org/?probe=33ce116b8a) | Mar 08, 2022 |
| Dell          | System XPS L322X            | [2aa0c05f64](https://linux-hardware.org/?probe=2aa0c05f64) | Mar 06, 2022 |
| Toshiba       | Satellite Pro A40-C         | [49766126e1](https://linux-hardware.org/?probe=49766126e1) | Feb 27, 2022 |
| Dell          | Inspiron 1011               | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| MSI           | EX620                       | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| HP            | Compaq Mini CQ10-100        | [5a471683f7](https://linux-hardware.org/?probe=5a471683f7) | Feb 05, 2022 |
| Dell          | Latitude E6400              | [c55769f459](https://linux-hardware.org/?probe=c55769f459) | Feb 02, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [b685151ac1](https://linux-hardware.org/?probe=b685151ac1) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | [712c420215](https://linux-hardware.org/?probe=712c420215) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | [0c05019294](https://linux-hardware.org/?probe=0c05019294) | Jan 31, 2022 |
| ASUSTek       | X551CA                      | [0cb832f85f](https://linux-hardware.org/?probe=0cb832f85f) | Jan 27, 2022 |
| Medion        | Akoya THE TOUCH 10          | [753fcd1661](https://linux-hardware.org/?probe=753fcd1661) | Jan 08, 2022 |
| Lenovo        | G50-70 20351                | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| Dell          | Inspiron 5570               | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Lenovo        | ThinkPad T430 23426FU       | [53e2109383](https://linux-hardware.org/?probe=53e2109383) | Dec 30, 2021 |
| MSI           | GS66 Stealth 11UE           | [ab09d4463d](https://linux-hardware.org/?probe=ab09d4463d) | Dec 20, 2021 |
| Toshiba       | Satellite C600              | [dd417ecb87](https://linux-hardware.org/?probe=dd417ecb87) | Dec 15, 2021 |
| Sony          | VGN-NR430E                  | [305865a785](https://linux-hardware.org/?probe=305865a785) | Dec 12, 2021 |
| Sony          | VGN-NR430E                  | [3ca106703d](https://linux-hardware.org/?probe=3ca106703d) | Dec 11, 2021 |
| Dell          | Latitude 3410               | [4b84ebe353](https://linux-hardware.org/?probe=4b84ebe353) | Dec 08, 2021 |
| Dell          | Latitude 3410               | [c2a6a9ad6b](https://linux-hardware.org/?probe=c2a6a9ad6b) | Dec 08, 2021 |
| HP            | 255 G8 Notebook PC          | [a700683a6f](https://linux-hardware.org/?probe=a700683a6f) | Dec 05, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| Fujitsu Si... | LIFEBOOK E8310              | [09fd8a63b7](https://linux-hardware.org/?probe=09fd8a63b7) | Nov 30, 2021 |
| Sony          | VGN-FE31B                   | [9c79f90f8d](https://linux-hardware.org/?probe=9c79f90f8d) | Nov 27, 2021 |
| HP            | Pavilion 17                 | [b5f54d657a](https://linux-hardware.org/?probe=b5f54d657a) | Nov 27, 2021 |
| Acer          | Aspire 6920                 | [ecd71d1bde](https://linux-hardware.org/?probe=ecd71d1bde) | Nov 26, 2021 |
| Chuwi         | GemiBook Pro                | [1dc5d193a3](https://linux-hardware.org/?probe=1dc5d193a3) | Nov 24, 2021 |
| HP            | Pavilion Notebook           | [7045bece2c](https://linux-hardware.org/?probe=7045bece2c) | Nov 23, 2021 |
| Packard Be... | EasyNote TJ75               | [76b8b98ec9](https://linux-hardware.org/?probe=76b8b98ec9) | Nov 21, 2021 |
| Lenovo        | IdeaPad Z460 0913           | [0bb3eea006](https://linux-hardware.org/?probe=0bb3eea006) | Nov 16, 2021 |
| Lenovo        | G580 26897JJ                | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| Dell          | XPS 13 9310                 | [0c99cea4ba](https://linux-hardware.org/?probe=0c99cea4ba) | Nov 07, 2021 |
| Notebook      | NP50DE_DB                   | [6ecc612580](https://linux-hardware.org/?probe=6ecc612580) | Nov 07, 2021 |
| Dell          | Latitude 7490               | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| Fujitsu Si... | LIFEBOOK E8310              | [5f0bcd4c39](https://linux-hardware.org/?probe=5f0bcd4c39) | Oct 30, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [e4aa5740c5](https://linux-hardware.org/?probe=e4aa5740c5) | Oct 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [338ddd258e](https://linux-hardware.org/?probe=338ddd258e) | Oct 24, 2021 |
| Dell          | Precision 3520              | [cf720e50db](https://linux-hardware.org/?probe=cf720e50db) | Oct 24, 2021 |
| Dell          | Latitude D620               | [19049fd2bd](https://linux-hardware.org/?probe=19049fd2bd) | Oct 23, 2021 |
| Dell          | Latitude D620               | [08fd9efc01](https://linux-hardware.org/?probe=08fd9efc01) | Oct 23, 2021 |
| Acer          | Aspire E5-432               | [ff1a22fdc4](https://linux-hardware.org/?probe=ff1a22fdc4) | Oct 08, 2021 |
| Toshiba       | dynabook R634/K             | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Lenovo        | ThinkPad E15 20RD001CGE     | [f7d150a85c](https://linux-hardware.org/?probe=f7d150a85c) | Oct 04, 2021 |
| Apple         | MacBookPro5,3               | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | EliteBook 745 G2            | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Acer          | Aspire one 1-431            | [3ff4be2b55](https://linux-hardware.org/?probe=3ff4be2b55) | Sep 21, 2021 |
| Acer          | AO751h                      | [d217a1c6b7](https://linux-hardware.org/?probe=d217a1c6b7) | Sep 18, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Acer          | Acadia V1.45                | [aa3f685f0a](https://linux-hardware.org/?probe=aa3f685f0a) | Sep 15, 2021 |
| Acer          | Acadia V1.45                | [cd630332c7](https://linux-hardware.org/?probe=cd630332c7) | Sep 15, 2021 |
| Dell          | Inspiron 7577               | [1a39f562b3](https://linux-hardware.org/?probe=1a39f562b3) | Sep 13, 2021 |
| Dell          | Inspiron 1545               | [271309ac53](https://linux-hardware.org/?probe=271309ac53) | Sep 12, 2021 |
| Toshiba       | Satellite A100              | [0d3b75782b](https://linux-hardware.org/?probe=0d3b75782b) | Sep 03, 2021 |
| Panasonic     | CF-20-1                     | [6f921aa428](https://linux-hardware.org/?probe=6f921aa428) | Sep 02, 2021 |
| HUAWEI        | KPL-W0X                     | [27b23ba02b](https://linux-hardware.org/?probe=27b23ba02b) | Aug 29, 2021 |
| ARCELIK       | GNB 15xx B1 Serisi          | [8537b57efa](https://linux-hardware.org/?probe=8537b57efa) | Aug 24, 2021 |
| Dell          | Vostro 1015                 | [f0a640519a](https://linux-hardware.org/?probe=f0a640519a) | Aug 17, 2021 |
| Samsung       | R59P/R60P/R61P              | [87d045fa9c](https://linux-hardware.org/?probe=87d045fa9c) | Aug 16, 2021 |
| Samsung       | R59P/R60P/R61P              | [feaabd09c8](https://linux-hardware.org/?probe=feaabd09c8) | Aug 10, 2021 |
| Dell          | Latitude E7450              | [5e94ad6881](https://linux-hardware.org/?probe=5e94ad6881) | Aug 10, 2021 |
| Dell          | Latitude E7450              | [110fc3ebef](https://linux-hardware.org/?probe=110fc3ebef) | Aug 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [8227b4305d](https://linux-hardware.org/?probe=8227b4305d) | Aug 09, 2021 |
| Acer          | AO531h                      | [f677e6e910](https://linux-hardware.org/?probe=f677e6e910) | Aug 09, 2021 |
| Acer          | AO531h                      | [42bc030846](https://linux-hardware.org/?probe=42bc030846) | Aug 09, 2021 |
| Acer          | AO531h                      | [3475d2f343](https://linux-hardware.org/?probe=3475d2f343) | Aug 09, 2021 |
| HP            | ENVY 17                     | [1d6dd8440c](https://linux-hardware.org/?probe=1d6dd8440c) | Aug 05, 2021 |
| Dell          | Studio 1737                 | [b4f16960c4](https://linux-hardware.org/?probe=b4f16960c4) | Aug 05, 2021 |
| Teclast       | F6 Pro                      | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| Gateway       | NE570                       | [f9ccf3665f](https://linux-hardware.org/?probe=f9ccf3665f) | Jul 19, 2021 |
| Dell          | Inspiron 7577               | [b221cbc463](https://linux-hardware.org/?probe=b221cbc463) | Jul 17, 2021 |
| Timi          | A35S                        | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| Medion        | Akoya THE TOUCH 10          | [7908947c9f](https://linux-hardware.org/?probe=7908947c9f) | Jul 14, 2021 |
| HP            | Pavilion dv6                | [aee9cfed82](https://linux-hardware.org/?probe=aee9cfed82) | Jul 11, 2021 |
| Acer          | Aspire 7740                 | [d8694dd629](https://linux-hardware.org/?probe=d8694dd629) | Jul 09, 2021 |
| Dell          | Vostro 14-3468              | [2e203beafd](https://linux-hardware.org/?probe=2e203beafd) | Jul 08, 2021 |
| Dell          | Latitude 5511               | [cac1bff4a1](https://linux-hardware.org/?probe=cac1bff4a1) | Jul 06, 2021 |
| HP            | EliteBook 8540w             | [6130e48df9](https://linux-hardware.org/?probe=6130e48df9) | Jul 05, 2021 |
| HP            | EliteBook 8540w             | [8fcf62f37c](https://linux-hardware.org/?probe=8fcf62f37c) | Jul 05, 2021 |
| HP            | Pavilion g4                 | [fa58b1dd24](https://linux-hardware.org/?probe=fa58b1dd24) | Jun 30, 2021 |
| Dell          | Precision 7550              | [79a56a6b22](https://linux-hardware.org/?probe=79a56a6b22) | Jun 30, 2021 |
| Apple         | MacBook3,1                  | [4fd63df257](https://linux-hardware.org/?probe=4fd63df257) | Jun 30, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7MM0... | [4e01561e2d](https://linux-hardware.org/?probe=4e01561e2d) | Jun 25, 2021 |
| Dell          | Latitude 5591               | [0a888c201f](https://linux-hardware.org/?probe=0a888c201f) | Jun 25, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7MM0... | [424e9fe919](https://linux-hardware.org/?probe=424e9fe919) | Jun 24, 2021 |
| Dell          | Precision 5550              | [7b9e5a1b30](https://linux-hardware.org/?probe=7b9e5a1b30) | Jun 23, 2021 |
| Dell          | Latitude 5511               | [6625368d80](https://linux-hardware.org/?probe=6625368d80) | Jun 21, 2021 |
| Dell          | Latitude 5511               | [3b8bd7756c](https://linux-hardware.org/?probe=3b8bd7756c) | Jun 20, 2021 |
| HP            | ProBook 6550b               | [262ede4645](https://linux-hardware.org/?probe=262ede4645) | Jun 16, 2021 |
| Acer          | Aspire ES1-512              | [9814f75415](https://linux-hardware.org/?probe=9814f75415) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [3d0b697005](https://linux-hardware.org/?probe=3d0b697005) | Jun 09, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [977558100f](https://linux-hardware.org/?probe=977558100f) | Jun 09, 2021 |
| HP            | Notebook                    | [aa603459f8](https://linux-hardware.org/?probe=aa603459f8) | Jun 06, 2021 |
| Toshiba       | Satellite Pro A40-C         | [a467cae210](https://linux-hardware.org/?probe=a467cae210) | Jun 03, 2021 |
| Acer          | Aspire 4830TG               | [0233ed2211](https://linux-hardware.org/?probe=0233ed2211) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Lenovo        | ThinkPad T530 24291H4       | [9ecbb7a946](https://linux-hardware.org/?probe=9ecbb7a946) | May 28, 2021 |
| Hometech      | N1401A                      | [421dcf0a2f](https://linux-hardware.org/?probe=421dcf0a2f) | May 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | XPS 13 9370                 | [9b05fb9e1f](https://linux-hardware.org/?probe=9b05fb9e1f) | May 16, 2021 |
| Dell          | XPS 13 9370                 | [0d397cf104](https://linux-hardware.org/?probe=0d397cf104) | May 16, 2021 |
| Gigabyte      | AERO 15-X9                  | [df4d80f1f9](https://linux-hardware.org/?probe=df4d80f1f9) | May 14, 2021 |
| Acer          | LuganoII                    | [c26e330dae](https://linux-hardware.org/?probe=c26e330dae) | May 13, 2021 |
| Acer          | AOA150                      | [21647e22ba](https://linux-hardware.org/?probe=21647e22ba) | May 12, 2021 |
| Acer          | LuganoII                    | [3a87a5cef9](https://linux-hardware.org/?probe=3a87a5cef9) | May 12, 2021 |
| Lenovo        | M5400 20281                 | [b0b95cd759](https://linux-hardware.org/?probe=b0b95cd759) | May 09, 2021 |
| HP            | Pavilion dv6                | [dce60f14e1](https://linux-hardware.org/?probe=dce60f14e1) | May 08, 2021 |
| Lenovo        | 3000 N500 423374G           | [a2ec86f284](https://linux-hardware.org/?probe=a2ec86f284) | May 08, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [522b86dc40](https://linux-hardware.org/?probe=522b86dc40) | May 03, 2021 |
| Dell          | Latitude E5440              | [ea59351ece](https://linux-hardware.org/?probe=ea59351ece) | May 01, 2021 |
| Dell          | Latitude 7480               | [6b9e1797c6](https://linux-hardware.org/?probe=6b9e1797c6) | Apr 29, 2021 |
| Dell          | Vostro 5402                 | [bd53dff836](https://linux-hardware.org/?probe=bd53dff836) | Apr 23, 2021 |
| HP            | EliteBook 2560p             | [c75019619f](https://linux-hardware.org/?probe=c75019619f) | Apr 17, 2021 |
| Dell          | XPS 13 9360                 | [a7a9af4a65](https://linux-hardware.org/?probe=a7a9af4a65) | Apr 04, 2021 |
| Acer          | TravelMate 5530             | [6b6df6431c](https://linux-hardware.org/?probe=6b6df6431c) | Apr 02, 2021 |
| ASUSTek       | X550LD                      | [ed77da0a7f](https://linux-hardware.org/?probe=ed77da0a7f) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Dell          | Vostro 15-3568              | [2c8acbf86c](https://linux-hardware.org/?probe=2c8acbf86c) | Mar 21, 2021 |
| Dell          | Latitude 5591               | [440c09d385](https://linux-hardware.org/?probe=440c09d385) | Mar 19, 2021 |
| MSI           | EX620                       | [92223bedbf](https://linux-hardware.org/?probe=92223bedbf) | Mar 18, 2021 |
| Acer          | Aspire A515-56              | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| IDEALMAX      | H34                         | [3a80074655](https://linux-hardware.org/?probe=3a80074655) | Mar 17, 2021 |
| Sony          | VPCEB2M1E                   | [b66618f38f](https://linux-hardware.org/?probe=b66618f38f) | Mar 16, 2021 |
| Positivo      | Mobile                      | [b6bf80e4a0](https://linux-hardware.org/?probe=b6bf80e4a0) | Mar 15, 2021 |
| Dell          | Latitude E5250              | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS0LJ04    | [3ea7e7e0eb](https://linux-hardware.org/?probe=3ea7e7e0eb) | Mar 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS0LJ04    | [fbc708f40b](https://linux-hardware.org/?probe=fbc708f40b) | Mar 10, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [d55c9ab43d](https://linux-hardware.org/?probe=d55c9ab43d) | Mar 09, 2021 |
| Dell          | Latitude E5250              | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Toshiba       | Satellite U405D             | [c39fbac2a3](https://linux-hardware.org/?probe=c39fbac2a3) | Mar 07, 2021 |
| Dell          | Precision M3800             | [946b253122](https://linux-hardware.org/?probe=946b253122) | Mar 03, 2021 |
| Acer          | Aspire E1-571G              | [11e6858209](https://linux-hardware.org/?probe=11e6858209) | Feb 28, 2021 |
| Toshiba       | Satellite Pro A100          | [403755cbe6](https://linux-hardware.org/?probe=403755cbe6) | Feb 25, 2021 |
| Dell          | Latitude 7280               | [07efc65c6a](https://linux-hardware.org/?probe=07efc65c6a) | Feb 21, 2021 |
| Toshiba       | IS-1522                     | [6e0892a006](https://linux-hardware.org/?probe=6e0892a006) | Feb 19, 2021 |
| Acer          | Aspire 5610                 | [c5681a4097](https://linux-hardware.org/?probe=c5681a4097) | Feb 17, 2021 |
| Toshiba       | Satellite C50D-B            | [4114652578](https://linux-hardware.org/?probe=4114652578) | Feb 16, 2021 |
| Toshiba       | Satellite C50D-B            | [63a04a0d52](https://linux-hardware.org/?probe=63a04a0d52) | Feb 16, 2021 |
| Dell          | Latitude E4310              | [37a49f8182](https://linux-hardware.org/?probe=37a49f8182) | Feb 15, 2021 |
| Dell          | Latitude 7480               | [92f5ef8b15](https://linux-hardware.org/?probe=92f5ef8b15) | Feb 14, 2021 |
| Dell          | Latitude 7480               | [7fc96867c5](https://linux-hardware.org/?probe=7fc96867c5) | Feb 14, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | [ea78db0716](https://linux-hardware.org/?probe=ea78db0716) | Feb 14, 2021 |
| ASUSTek       | X55U                        | [aea7a001db](https://linux-hardware.org/?probe=aea7a001db) | Feb 13, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [4b2cd43abc](https://linux-hardware.org/?probe=4b2cd43abc) | Feb 10, 2021 |
| Dell          | Inspiron 3542               | [8e6c1aadd3](https://linux-hardware.org/?probe=8e6c1aadd3) | Feb 10, 2021 |
| Dell          | Inspiron 3542               | [2589d166ca](https://linux-hardware.org/?probe=2589d166ca) | Feb 10, 2021 |
| Dell          | G3 3779                     | [363e754d51](https://linux-hardware.org/?probe=363e754d51) | Feb 06, 2021 |
| Compal        | PBL10                       | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | 1005HA                      | [3271c9fcf1](https://linux-hardware.org/?probe=3271c9fcf1) | Feb 04, 2021 |
| HP            | ProBook 6550b               | [b41bf411ae](https://linux-hardware.org/?probe=b41bf411ae) | Jan 31, 2021 |
| Dell          | XPS 13 7390                 | [002dbe9174](https://linux-hardware.org/?probe=002dbe9174) | Jan 30, 2021 |
| Lenovo        | 3000 N500 423374G           | [e58a22a75a](https://linux-hardware.org/?probe=e58a22a75a) | Jan 30, 2021 |
| Dell          | XPS 13 9343                 | [b3c1b54fb7](https://linux-hardware.org/?probe=b3c1b54fb7) | Jan 30, 2021 |
| HP            | ProBook 4510s               | [90108b85c2](https://linux-hardware.org/?probe=90108b85c2) | Jan 28, 2021 |
| Lenovo        | ThinkPad T420s 41732AU      | [0f7cf25542](https://linux-hardware.org/?probe=0f7cf25542) | Jan 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | [407c5fa547](https://linux-hardware.org/?probe=407c5fa547) | Jan 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | [76ed8917b5](https://linux-hardware.org/?probe=76ed8917b5) | Jan 27, 2021 |
| HP            | ProBook 6550b               | [90cc726402](https://linux-hardware.org/?probe=90cc726402) | Jan 27, 2021 |
| HP            | EliteBook 820 G2            | [b45017b059](https://linux-hardware.org/?probe=b45017b059) | Jan 24, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdfeee2839](https://linux-hardware.org/?probe=bdfeee2839) | Jan 21, 2021 |
| HP            | ProBook 4510s               | [249c4254b8](https://linux-hardware.org/?probe=249c4254b8) | Jan 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| Dell          | Latitude D420               | [8cea54aabf](https://linux-hardware.org/?probe=8cea54aabf) | Jan 17, 2021 |
| Itautec       | Infoway w7430               | [de4a2289ae](https://linux-hardware.org/?probe=de4a2289ae) | Jan 14, 2021 |
| Lenovo        | ThinkPad E14 20RAS0BY00     | [0178b6f04d](https://linux-hardware.org/?probe=0178b6f04d) | Jan 13, 2021 |
| Lenovo        | ThinkPad R400 7440CL2       | [d9662809ae](https://linux-hardware.org/?probe=d9662809ae) | Jan 13, 2021 |
| Lenovo        | ThinkPad R400 7440CL2       | [2b357b7a62](https://linux-hardware.org/?probe=2b357b7a62) | Jan 13, 2021 |
| HP            | ProBook 4520s               | [46240490b5](https://linux-hardware.org/?probe=46240490b5) | Jan 12, 2021 |
| HP            | Pavilion g6                 | [a8eaaf47b0](https://linux-hardware.org/?probe=a8eaaf47b0) | Jan 10, 2021 |
| Toshiba       | Satellite L755              | [601e76c662](https://linux-hardware.org/?probe=601e76c662) | Jan 09, 2021 |
| Dell          | Inspiron N5030              | [e7b2580e2b](https://linux-hardware.org/?probe=e7b2580e2b) | Jan 09, 2021 |
| HP            | ProBook 6550b               | [af743262a6](https://linux-hardware.org/?probe=af743262a6) | Jan 09, 2021 |
| Dell          | Inspiron N5030              | [299420cc02](https://linux-hardware.org/?probe=299420cc02) | Jan 09, 2021 |
| HP            | 510 Notebook PC (RU964AA... | [fe8a07348f](https://linux-hardware.org/?probe=fe8a07348f) | Jan 08, 2021 |
| HP            | 510 Notebook PC (RU964AA... | [86ef2cddd1](https://linux-hardware.org/?probe=86ef2cddd1) | Jan 08, 2021 |
| HP            | ProBook 455 G1              | [7e08feac35](https://linux-hardware.org/?probe=7e08feac35) | Jan 07, 2021 |
| Packard Be... | EasyNote TK36               | [d5aeb5be31](https://linux-hardware.org/?probe=d5aeb5be31) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | [da33e577bf](https://linux-hardware.org/?probe=da33e577bf) | Jan 02, 2021 |
| Packard Be... | EasyNote TK36               | [43b59e2a0c](https://linux-hardware.org/?probe=43b59e2a0c) | Jan 02, 2021 |
| NEC Comput... | Packard Bell EasyNote       | [c0b37bc3c3](https://linux-hardware.org/?probe=c0b37bc3c3) | Jan 02, 2021 |
| NEC Comput... | Packard Bell EasyNote       | [953e9fbfda](https://linux-hardware.org/?probe=953e9fbfda) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | [3ccf619144](https://linux-hardware.org/?probe=3ccf619144) | Dec 31, 2020 |
| HP            | Compaq nc6400 (RH478EA#A... | [d7fd1a7a8d](https://linux-hardware.org/?probe=d7fd1a7a8d) | Dec 31, 2020 |
| Sony          | VGN-Z21MN_B                 | [db832121d8](https://linux-hardware.org/?probe=db832121d8) | Dec 30, 2020 |
| Acer          | Swift SF314-55G             | [6f94a2e40c](https://linux-hardware.org/?probe=6f94a2e40c) | Dec 30, 2020 |
| ASUSTek       | K53U                        | [92d200393a](https://linux-hardware.org/?probe=92d200393a) | Dec 29, 2020 |
| ASUSTek       | K53U                        | [99610b1976](https://linux-hardware.org/?probe=99610b1976) | Dec 29, 2020 |
| Advent        | Verona                      | [3cb47bf21d](https://linux-hardware.org/?probe=3cb47bf21d) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| Lenovo        | ThinkPad L450 20DT001DUS    | [dd815dfd6a](https://linux-hardware.org/?probe=dd815dfd6a) | Dec 25, 2020 |
| Apple         | MacBook5,1                  | [4a85297f60](https://linux-hardware.org/?probe=4a85297f60) | Dec 23, 2020 |
| Samsung       | R530/R730                   | [397b075add](https://linux-hardware.org/?probe=397b075add) | Dec 23, 2020 |
| Apple         | MacBookPro8,2               | [e99e06a590](https://linux-hardware.org/?probe=e99e06a590) | Dec 23, 2020 |
| Acer          | Aspire 7741                 | [bb04468cdd](https://linux-hardware.org/?probe=bb04468cdd) | Dec 22, 2020 |
| Dell          | Inspiron 15-3552            | [2d64eaea6f](https://linux-hardware.org/?probe=2d64eaea6f) | Dec 22, 2020 |
| Apple         | MacBook5,1                  | [f9cf955187](https://linux-hardware.org/?probe=f9cf955187) | Dec 22, 2020 |
| Fujitsu       | LIFEBOOK A557               | [b82c30b180](https://linux-hardware.org/?probe=b82c30b180) | Dec 21, 2020 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [289dc71948](https://linux-hardware.org/?probe=289dc71948) | Dec 21, 2020 |
| ASUSTek       | UX305FA                     | [01059cbee4](https://linux-hardware.org/?probe=01059cbee4) | Dec 20, 2020 |
| Dell          | Precision 5540              | [eea500d1e4](https://linux-hardware.org/?probe=eea500d1e4) | Dec 18, 2020 |
| Dell          | Precision 5540              | [0e06bc0dae](https://linux-hardware.org/?probe=0e06bc0dae) | Dec 18, 2020 |
| Dell          | Inspiron 910                | [87ff58828e](https://linux-hardware.org/?probe=87ff58828e) | Dec 16, 2020 |
| HP            | Laptop 15-da0xxx            | [73fa61c233](https://linux-hardware.org/?probe=73fa61c233) | Dec 15, 2020 |
| Dell          | Inspiron 1545               | [5a179cb315](https://linux-hardware.org/?probe=5a179cb315) | Dec 14, 2020 |
| Lenovo        | ThinkPad X301 4057W3A       | [ca140372c9](https://linux-hardware.org/?probe=ca140372c9) | Dec 13, 2020 |
| HP            | EliteBook 8470p             | [941a457fa1](https://linux-hardware.org/?probe=941a457fa1) | Dec 12, 2020 |
| Toshiba       | Portable PC                 | [9aec36b4b9](https://linux-hardware.org/?probe=9aec36b4b9) | Dec 11, 2020 |
| HP            | Laptop 15-da0xxx            | [fb4783aeba](https://linux-hardware.org/?probe=fb4783aeba) | Dec 10, 2020 |
| Dell          | Inspiron 1545               | [1bd7a01295](https://linux-hardware.org/?probe=1bd7a01295) | Dec 09, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | [dd93682c3c](https://linux-hardware.org/?probe=dd93682c3c) | Dec 09, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d9258de65c](https://linux-hardware.org/?probe=d9258de65c) | Dec 09, 2020 |
| Acer          | Extensa 2519                | [b2ccfa56ae](https://linux-hardware.org/?probe=b2ccfa56ae) | Dec 08, 2020 |
| Acer          | Extensa 2519                | [2e71470fef](https://linux-hardware.org/?probe=2e71470fef) | Dec 08, 2020 |
| Acer          | TravelMate 5530             | [0e494e91b0](https://linux-hardware.org/?probe=0e494e91b0) | Dec 06, 2020 |
| Dell          | Inspiron 7577               | [2a527149d7](https://linux-hardware.org/?probe=2a527149d7) | Dec 03, 2020 |
| Dell          | Latitude 7480               | [a04feb1736](https://linux-hardware.org/?probe=a04feb1736) | Dec 01, 2020 |
| Acer          | Aspire VN7-591G             | [a30c2da246](https://linux-hardware.org/?probe=a30c2da246) | Nov 26, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| Dell          | Inspiron 11-3168            | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Dell          | Inspiron 3542               | [1817281db6](https://linux-hardware.org/?probe=1817281db6) | Nov 21, 2020 |
| HP            | Pavilion dv6                | [ee09691432](https://linux-hardware.org/?probe=ee09691432) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Timi          | TM1701                      | [ee53272b88](https://linux-hardware.org/?probe=ee53272b88) | Nov 14, 2020 |
| HP            | ENVY 15                     | [fb33289aed](https://linux-hardware.org/?probe=fb33289aed) | Nov 13, 2020 |
| ASUSTek       | UL30VT                      | [d5921db40a](https://linux-hardware.org/?probe=d5921db40a) | Nov 12, 2020 |
| ASUSTek       | N76VB                       | [be1a7a1846](https://linux-hardware.org/?probe=be1a7a1846) | Nov 11, 2020 |
| HP            | ZBook 17 G3                 | [6edcc11c0e](https://linux-hardware.org/?probe=6edcc11c0e) | Nov 11, 2020 |
| HP            | ProBook 640 G2              | [239d1a4663](https://linux-hardware.org/?probe=239d1a4663) | Nov 09, 2020 |
| Dell          | XPS 13 7390                 | [78c640d460](https://linux-hardware.org/?probe=78c640d460) | Nov 09, 2020 |
| Dell          | Latitude XT2                | [8fba8f46db](https://linux-hardware.org/?probe=8fba8f46db) | Nov 08, 2020 |
| Acer          | Aspire 5738                 | [e349021135](https://linux-hardware.org/?probe=e349021135) | Nov 08, 2020 |
| Toshiba       | Satellite A505              | [d76aa15e2c](https://linux-hardware.org/?probe=d76aa15e2c) | Nov 07, 2020 |
| Lenovo        | ThinkPad X301 4057AL1       | [b52207277d](https://linux-hardware.org/?probe=b52207277d) | Nov 04, 2020 |
| ASUSTek       | X453SA                      | [1bb7c5cfe5](https://linux-hardware.org/?probe=1bb7c5cfe5) | Nov 03, 2020 |
| Lenovo        | ThinkPad T60 1951AH4        | [f23ac90595](https://linux-hardware.org/?probe=f23ac90595) | Nov 03, 2020 |
| Lenovo        | ThinkPad T60 1951AH4        | [52d6742358](https://linux-hardware.org/?probe=52d6742358) | Nov 03, 2020 |
| ASUSTek       | T101MT                      | [5842dd654b](https://linux-hardware.org/?probe=5842dd654b) | Nov 01, 2020 |
| Dell          | Inspiron 5567               | [16e2be9f0f](https://linux-hardware.org/?probe=16e2be9f0f) | Nov 01, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [7184b7e890](https://linux-hardware.org/?probe=7184b7e890) | Oct 29, 2020 |
| Dell          | Vostro 1000                 | [05849c4d22](https://linux-hardware.org/?probe=05849c4d22) | Oct 28, 2020 |
| Dell          | Vostro 1000                 | [f55377552a](https://linux-hardware.org/?probe=f55377552a) | Oct 27, 2020 |
| Dell          | Vostro 1400                 | [e27c854a39](https://linux-hardware.org/?probe=e27c854a39) | Oct 27, 2020 |
| Dell          | Vostro 1400                 | [102eafaf81](https://linux-hardware.org/?probe=102eafaf81) | Oct 27, 2020 |
| HUAWEI        | KPL-W0X                     | [cf48a4f7b0](https://linux-hardware.org/?probe=cf48a4f7b0) | Oct 26, 2020 |
| Lenovo        | ThinkPad T570 20H9CTO1WW    | [c8f0e5e6fa](https://linux-hardware.org/?probe=c8f0e5e6fa) | Oct 26, 2020 |
| ASUSTek       | K55VJ                       | [53e73c71d1](https://linux-hardware.org/?probe=53e73c71d1) | Oct 23, 2020 |
| ASUSTek       | K55VJ                       | [5351f3ac0f](https://linux-hardware.org/?probe=5351f3ac0f) | Oct 23, 2020 |
| Apple         | MacBookPro1,1               | [2a6c327452](https://linux-hardware.org/?probe=2a6c327452) | Oct 23, 2020 |
| Dell          | XPS 15 9560                 | [0ea98ac7d2](https://linux-hardware.org/?probe=0ea98ac7d2) | Oct 22, 2020 |
| Dell          | XPS 13 9310                 | [ca9da289db](https://linux-hardware.org/?probe=ca9da289db) | Oct 19, 2020 |
| Lenovo        | ThinkPad T60 1952EB4        | [62681b5680](https://linux-hardware.org/?probe=62681b5680) | Oct 19, 2020 |
| Intel         | JV10_CS                     | [8c95378d1f](https://linux-hardware.org/?probe=8c95378d1f) | Oct 18, 2020 |
| ASUSTek       | K53SJ                       | [5635f2d532](https://linux-hardware.org/?probe=5635f2d532) | Oct 16, 2020 |
| LG Electro... | P430-K.BE48P1               | [366bd09248](https://linux-hardware.org/?probe=366bd09248) | Oct 15, 2020 |
| Acer          | Aspire A515-51              | [a92208292e](https://linux-hardware.org/?probe=a92208292e) | Oct 13, 2020 |
| Lenovo        | Z710 20250                  | [c864fda22e](https://linux-hardware.org/?probe=c864fda22e) | Oct 13, 2020 |
| Acer          | Swift SF514-53T             | [cfac356307](https://linux-hardware.org/?probe=cfac356307) | Oct 13, 2020 |
| Fujitsu       | LIFEBOOK NH532              | [08ebefc47e](https://linux-hardware.org/?probe=08ebefc47e) | Oct 12, 2020 |
| Medion        | Akoya THE TOUCH 10          | [1500397c93](https://linux-hardware.org/?probe=1500397c93) | Oct 10, 2020 |
| HP            | Compaq Presario A900        | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| Lenovo        | G50-80 80E5                 | [80f6028032](https://linux-hardware.org/?probe=80f6028032) | Oct 07, 2020 |
| Apple         | MacBookPro1,1               | [03e2d99987](https://linux-hardware.org/?probe=03e2d99987) | Oct 07, 2020 |
| Toshiba       | Satellite A135              | [872e375f7d](https://linux-hardware.org/?probe=872e375f7d) | Oct 06, 2020 |
| Toshiba       | Satellite A135              | [51279c1662](https://linux-hardware.org/?probe=51279c1662) | Oct 06, 2020 |
| Dell          | G5 5590                     | [30d1a3f785](https://linux-hardware.org/?probe=30d1a3f785) | Oct 05, 2020 |
| HP            | Mini 210-1000               | [ad7e5e722f](https://linux-hardware.org/?probe=ad7e5e722f) | Oct 05, 2020 |
| Dell          | Studio 1537                 | [fb2730ecf5](https://linux-hardware.org/?probe=fb2730ecf5) | Oct 05, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HUAWEI        | WRT-WX9                     | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| LG Electro... | X120-H.CSVPG                | [548d6618e3](https://linux-hardware.org/?probe=548d6618e3) | Oct 02, 2020 |
| LG Electro... | X120-H.CSVPG                | [4853246cce](https://linux-hardware.org/?probe=4853246cce) | Oct 02, 2020 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [0f4425d89a](https://linux-hardware.org/?probe=0f4425d89a) | Oct 02, 2020 |
| HP            | ENVY TS m7                  | [1e21fdd484](https://linux-hardware.org/?probe=1e21fdd484) | Sep 30, 2020 |
| Dell          | Latitude E7450              | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell          | Latitude E7450              | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| Samsung       | R610                        | [6d82e49339](https://linux-hardware.org/?probe=6d82e49339) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| Samsung       | R610                        | [e8416ebd86](https://linux-hardware.org/?probe=e8416ebd86) | Sep 28, 2020 |
| Dell          | XPS 13 9343                 | [98a248903d](https://linux-hardware.org/?probe=98a248903d) | Sep 28, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [2a0e9530f3](https://linux-hardware.org/?probe=2a0e9530f3) | Sep 28, 2020 |
| Apple         | MacBook2,1                  | [a11af3313e](https://linux-hardware.org/?probe=a11af3313e) | Sep 28, 2020 |
| Itautec       | Infoway                     | [7208bdf264](https://linux-hardware.org/?probe=7208bdf264) | Sep 28, 2020 |
| Dell          | Inspiron 7560               | [e5c43c8206](https://linux-hardware.org/?probe=e5c43c8206) | Sep 28, 2020 |
| Toshiba       | Satellite L755              | [32e663a3d9](https://linux-hardware.org/?probe=32e663a3d9) | Sep 27, 2020 |
| HP            | EliteBook 755 G5            | [48467304f0](https://linux-hardware.org/?probe=48467304f0) | Sep 26, 2020 |
| HP            | EliteBook 755 G5            | [cee814d244](https://linux-hardware.org/?probe=cee814d244) | Sep 26, 2020 |
| HP            | EliteBook 8460p             | [a9c8f7c921](https://linux-hardware.org/?probe=a9c8f7c921) | Sep 26, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [cc52f7719c](https://linux-hardware.org/?probe=cc52f7719c) | Sep 26, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [48212a4f99](https://linux-hardware.org/?probe=48212a4f99) | Sep 26, 2020 |
| Dell          | XPS 13 9370                 | [6790f8d26f](https://linux-hardware.org/?probe=6790f8d26f) | Sep 24, 2020 |
| Dell          | G3 3500                     | [387113ea62](https://linux-hardware.org/?probe=387113ea62) | Sep 24, 2020 |
| MSI           | Creator 15M A10SD           | [9d39878ae6](https://linux-hardware.org/?probe=9d39878ae6) | Sep 23, 2020 |
| Dell          | Precision 3520              | [62f622c78a](https://linux-hardware.org/?probe=62f622c78a) | Sep 23, 2020 |
| Dell          | G3 3500                     | [9c5bcc318d](https://linux-hardware.org/?probe=9c5bcc318d) | Sep 22, 2020 |
| Dell          | G3 3500                     | [a2e67cdcc9](https://linux-hardware.org/?probe=a2e67cdcc9) | Sep 22, 2020 |
| Lenovo        | ThinkPad R61e 7650E8G       | [900df41d5f](https://linux-hardware.org/?probe=900df41d5f) | Sep 21, 2020 |
| HP            | ProBook 6470b               | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| ASUSTek       | F7F                         | [0ffb1837f3](https://linux-hardware.org/?probe=0ffb1837f3) | Sep 20, 2020 |
| Positivo      | Mobile                      | [c6539534cd](https://linux-hardware.org/?probe=c6539534cd) | Sep 19, 2020 |
| HP            | Pavilion ZV6000 (PZ987EA... | [1b21bd3742](https://linux-hardware.org/?probe=1b21bd3742) | Sep 17, 2020 |
| Toshiba       | Satellite L755              | [e702908245](https://linux-hardware.org/?probe=e702908245) | Sep 17, 2020 |
| HP            | EliteBook 840 G3            | [6261260ac9](https://linux-hardware.org/?probe=6261260ac9) | Sep 17, 2020 |
| HP            | EliteBook 840 G3            | [cfbf78b903](https://linux-hardware.org/?probe=cfbf78b903) | Sep 17, 2020 |
| Acer          | Aspire M3-481               | [55949e4f33](https://linux-hardware.org/?probe=55949e4f33) | Sep 17, 2020 |
| Dell          | Inspiron 3583               | [906a07309d](https://linux-hardware.org/?probe=906a07309d) | Sep 16, 2020 |
| Acer          | Aspire 8735                 | [a2a7136928](https://linux-hardware.org/?probe=a2a7136928) | Sep 16, 2020 |
| Acer          | Aspire 8735                 | [7b66b4dc9f](https://linux-hardware.org/?probe=7b66b4dc9f) | Sep 16, 2020 |
| HP            | ProBook 455 G7              | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP            | ProBook 455 G7              | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| Fujitsu Si... | STYLISTIC ST6012            | [72148c32bd](https://linux-hardware.org/?probe=72148c32bd) | Sep 11, 2020 |
| Fujitsu Si... | STYLISTIC ST6012            | [c505144130](https://linux-hardware.org/?probe=c505144130) | Sep 10, 2020 |
| Lenovo        | IdeaPad Z400 VIWZ1          | [030c29af1f](https://linux-hardware.org/?probe=030c29af1f) | Sep 10, 2020 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | [120e943a1b](https://linux-hardware.org/?probe=120e943a1b) | Sep 09, 2020 |
| Lenovo        | S10-3c 20074                | [0d39849816](https://linux-hardware.org/?probe=0d39849816) | Sep 08, 2020 |
| Lenovo        | ThinkPad R400 2787W11       | [2f2eb25da3](https://linux-hardware.org/?probe=2f2eb25da3) | Sep 07, 2020 |
| Acer          | Aspire 3680                 | [af35aa2ade](https://linux-hardware.org/?probe=af35aa2ade) | Sep 05, 2020 |
| Medion        | Akoya E1318T                | [edcd65aa12](https://linux-hardware.org/?probe=edcd65aa12) | Sep 03, 2020 |
| Lenovo        | ThinkPad T480s 20L7004PG... | [a5a20d77c9](https://linux-hardware.org/?probe=a5a20d77c9) | Sep 03, 2020 |
| Toshiba       | dynabook SS MX/25AE         | [8d195475bf](https://linux-hardware.org/?probe=8d195475bf) | Sep 02, 2020 |
| Toshiba       | Satellite C650D             | [10ae6c43c5](https://linux-hardware.org/?probe=10ae6c43c5) | Aug 30, 2020 |
| Toshiba       | Satellite C650D             | [57077112d3](https://linux-hardware.org/?probe=57077112d3) | Aug 30, 2020 |
| Dell          | Latitude D620               | [2cee9ad674](https://linux-hardware.org/?probe=2cee9ad674) | Aug 29, 2020 |
| HP            | 15 Notebook PC              | [f1588185ac](https://linux-hardware.org/?probe=f1588185ac) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Toshiba       | Satellite C50D-A-11Q        | [4b48f63343](https://linux-hardware.org/?probe=4b48f63343) | Aug 25, 2020 |
| HP            | Unknown                     | [d0efd61c2d](https://linux-hardware.org/?probe=d0efd61c2d) | Aug 25, 2020 |
| Dell          | Latitude E6410              | [e322cf98fb](https://linux-hardware.org/?probe=e322cf98fb) | Aug 25, 2020 |
| Lenovo        | Edge 15 80K9                | [15e564f54c](https://linux-hardware.org/?probe=15e564f54c) | Aug 23, 2020 |
| ASUSTek       | X55U                        | [494a947812](https://linux-hardware.org/?probe=494a947812) | Aug 23, 2020 |
| Toshiba       | Satellite U405              | [f1c6390b3e](https://linux-hardware.org/?probe=f1c6390b3e) | Aug 22, 2020 |
| HP            | ProBook 6460b               | [36272d35ee](https://linux-hardware.org/?probe=36272d35ee) | Aug 22, 2020 |
| Lenovo        | ThinkPad T500 2055WSP       | [fd5c4e454f](https://linux-hardware.org/?probe=fd5c4e454f) | Aug 21, 2020 |
| Dell          | Inspiron 5559               | [f025aea472](https://linux-hardware.org/?probe=f025aea472) | Aug 20, 2020 |
| Acer          | Aspire E5-553G              | [361152fbed](https://linux-hardware.org/?probe=361152fbed) | Aug 20, 2020 |
| Lenovo        | ThinkPad L430 24654A1       | [1f3055baa5](https://linux-hardware.org/?probe=1f3055baa5) | Aug 19, 2020 |
| Acer          | Aspire 4935 V1.02           | [25bd21367a](https://linux-hardware.org/?probe=25bd21367a) | Aug 19, 2020 |
| Acer          | Aspire 4935 V1.02           | [b441525d9e](https://linux-hardware.org/?probe=b441525d9e) | Aug 19, 2020 |
| Apple         | MacBookPro13,2              | [dc00e06c33](https://linux-hardware.org/?probe=dc00e06c33) | Aug 19, 2020 |
| Lenovo        | ThinkPad E470 20H20003BR    | [61dc6ea167](https://linux-hardware.org/?probe=61dc6ea167) | Aug 18, 2020 |
| HP            | Compaq 6730b (NN204ET#AB... | [e7408dcfa5](https://linux-hardware.org/?probe=e7408dcfa5) | Aug 17, 2020 |
| Apple         | MacBookPro1,1               | [c07ccea74c](https://linux-hardware.org/?probe=c07ccea74c) | Aug 17, 2020 |
| Itautec       | W7655                       | [36ee5a4438](https://linux-hardware.org/?probe=36ee5a4438) | Aug 17, 2020 |
| Itautec       | W7655                       | [c13826f24a](https://linux-hardware.org/?probe=c13826f24a) | Aug 16, 2020 |
| Samsung       | NC10                        | [dc87dc6f43](https://linux-hardware.org/?probe=dc87dc6f43) | Aug 16, 2020 |
| HP            | ZBook 14u G5                | [ecb7904486](https://linux-hardware.org/?probe=ecb7904486) | Aug 16, 2020 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [b88b8f8632](https://linux-hardware.org/?probe=b88b8f8632) | Aug 13, 2020 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [d4b87a0017](https://linux-hardware.org/?probe=d4b87a0017) | Aug 13, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [4b2756518b](https://linux-hardware.org/?probe=4b2756518b) | Aug 12, 2020 |
| Acer          | AOD255                      | [627daa28b5](https://linux-hardware.org/?probe=627daa28b5) | Aug 11, 2020 |
| HP            | EliteBook 8570w             | [c172701a56](https://linux-hardware.org/?probe=c172701a56) | Aug 11, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [e6328da842](https://linux-hardware.org/?probe=e6328da842) | Aug 10, 2020 |
| Lenovo        | G505 20240                  | [3badf66815](https://linux-hardware.org/?probe=3badf66815) | Aug 08, 2020 |
| Samsung       | R59P/R60P/R61P              | [96248ed0e5](https://linux-hardware.org/?probe=96248ed0e5) | Aug 07, 2020 |
| Samsung       | 270E5G/270E5U               | [3b51f2c435](https://linux-hardware.org/?probe=3b51f2c435) | Aug 06, 2020 |
| Dell          | Vostro 15-3568              | [a8ae8e7d68](https://linux-hardware.org/?probe=a8ae8e7d68) | Aug 05, 2020 |
| Lenovo        | M50-70 80HK                 | [4ea6dd3142](https://linux-hardware.org/?probe=4ea6dd3142) | Aug 04, 2020 |
| HP            | 15                          | [7f6981dba4](https://linux-hardware.org/?probe=7f6981dba4) | Aug 04, 2020 |
| Dell          | Inspiron 3442               | [e1e212c52e](https://linux-hardware.org/?probe=e1e212c52e) | Aug 03, 2020 |
| Apple         | MacBookPro13,2              | [45b4f88f53](https://linux-hardware.org/?probe=45b4f88f53) | Aug 01, 2020 |
| Timi          | TM1613                      | [ce5abb6b58](https://linux-hardware.org/?probe=ce5abb6b58) | Jul 31, 2020 |
| Toshiba       | Satellite C75D-B            | [311243fefe](https://linux-hardware.org/?probe=311243fefe) | Jul 29, 2020 |
| Toshiba       | Satellite C75D-B            | [b6c3db5d62](https://linux-hardware.org/?probe=b6c3db5d62) | Jul 29, 2020 |
| Acer          | LuganoII                    | [11b588f8af](https://linux-hardware.org/?probe=11b588f8af) | Jul 29, 2020 |
| HP            | ProBook 430 G3              | [7d3e5091ef](https://linux-hardware.org/?probe=7d3e5091ef) | Jul 29, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [953e68f29d](https://linux-hardware.org/?probe=953e68f29d) | Jul 29, 2020 |
| Dell          | Precision M3800             | [a8e05164be](https://linux-hardware.org/?probe=a8e05164be) | Jul 28, 2020 |
| ASUSTek       | 1101HA                      | [64f7e52a9d](https://linux-hardware.org/?probe=64f7e52a9d) | Jul 27, 2020 |
| Acer          | Aspire one                  | [cb5f7734ad](https://linux-hardware.org/?probe=cb5f7734ad) | Jul 27, 2020 |
| ASUSTek       | 1101HA                      | [7d761b8773](https://linux-hardware.org/?probe=7d761b8773) | Jul 27, 2020 |
| HP            | G62                         | [aa3b52f1ea](https://linux-hardware.org/?probe=aa3b52f1ea) | Jul 25, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| Dell          | Inspiron 5458               | [9d78f4363b](https://linux-hardware.org/?probe=9d78f4363b) | Jul 24, 2020 |
| Dell          | Inspiron 5590               | [ec0eb2593d](https://linux-hardware.org/?probe=ec0eb2593d) | Jul 24, 2020 |
| Lenovo        | IdeaPad Y530                | [e65b34145f](https://linux-hardware.org/?probe=e65b34145f) | Jul 23, 2020 |
| HP            | ENVY TS m7                  | [d0d8e40468](https://linux-hardware.org/?probe=d0d8e40468) | Jul 22, 2020 |
| Dell          | Vostro 15-3568              | [52281c5c2d](https://linux-hardware.org/?probe=52281c5c2d) | Jul 22, 2020 |
| Dell          | Latitude E4310              | [ebd0aeeec6](https://linux-hardware.org/?probe=ebd0aeeec6) | Jul 21, 2020 |
| Sony          | VPCM120AB                   | [de54365475](https://linux-hardware.org/?probe=de54365475) | Jul 18, 2020 |
| HP            | EliteBook 840 G5            | [e919ef10ac](https://linux-hardware.org/?probe=e919ef10ac) | Jul 15, 2020 |
| ASUSTek       | X541UAK                     | [789952264e](https://linux-hardware.org/?probe=789952264e) | Jul 13, 2020 |
| HP            | EliteBook 840 G4            | [60d19a8f76](https://linux-hardware.org/?probe=60d19a8f76) | Jul 13, 2020 |
| HP            | 530 Notebook PC(GH634AA#... | [271e393696](https://linux-hardware.org/?probe=271e393696) | Jul 12, 2020 |
| Medion        | P8610                       | [719c317781](https://linux-hardware.org/?probe=719c317781) | Jul 10, 2020 |
| Dell          | XPS 15 7590                 | [4a62b53405](https://linux-hardware.org/?probe=4a62b53405) | Jul 07, 2020 |
| Lenovo        | E4325 20306                 | [fad20cd5b9](https://linux-hardware.org/?probe=fad20cd5b9) | Jul 05, 2020 |
| Dell          | Vostro 3446                 | [3fac624026](https://linux-hardware.org/?probe=3fac624026) | Jul 01, 2020 |
| Sony          | VPCYB35AN                   | [d333a2a489](https://linux-hardware.org/?probe=d333a2a489) | Jun 30, 2020 |
| Dell          | Latitude D520               | [14b70df5bb](https://linux-hardware.org/?probe=14b70df5bb) | Jun 29, 2020 |
| Acer          | AOA150                      | [d77ef53611](https://linux-hardware.org/?probe=d77ef53611) | Jun 28, 2020 |
| Lenovo        | ThinkPad R400 2787W11       | [f584bf0743](https://linux-hardware.org/?probe=f584bf0743) | Jun 24, 2020 |
| Dell          | Latitude 2120               | [81e5528854](https://linux-hardware.org/?probe=81e5528854) | Jun 24, 2020 |
| Dell          | Latitude 2120               | [abf223959e](https://linux-hardware.org/?probe=abf223959e) | Jun 24, 2020 |
| ASUSTek       | L4000H                      | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| ASUSTek       | X75VD                       | [19be75e878](https://linux-hardware.org/?probe=19be75e878) | Jun 18, 2020 |
| Acer          | LuganoII                    | [7e838ae29c](https://linux-hardware.org/?probe=7e838ae29c) | Jun 17, 2020 |
| Sony          | VPCEH1L8E                   | [3b8814bf8e](https://linux-hardware.org/?probe=3b8814bf8e) | Jun 15, 2020 |
| Notebook      | W9x0LU                      | [862b20ad4a](https://linux-hardware.org/?probe=862b20ad4a) | Jun 14, 2020 |
| Acer          | Aspire E5-553G              | [7ac3604857](https://linux-hardware.org/?probe=7ac3604857) | Jun 14, 2020 |
| HP            | Pavilion dv7                | [84c62ec138](https://linux-hardware.org/?probe=84c62ec138) | Jun 13, 2020 |
| Toshiba       | Satellite A200              | [a71e147fa5](https://linux-hardware.org/?probe=a71e147fa5) | Jun 13, 2020 |
| Lenovo        | ThinkPad T430 23498R6       | [0abc86809d](https://linux-hardware.org/?probe=0abc86809d) | Jun 10, 2020 |
| ASUSTek       | X555LDB                     | [d332d315e0](https://linux-hardware.org/?probe=d332d315e0) | Jun 10, 2020 |
| TG            | NXI-A7000 Series            | [20018e6c2a](https://linux-hardware.org/?probe=20018e6c2a) | Jun 07, 2020 |
| HP            | Compaq nx7400 (EY508ES#A... | [d28414a8c7](https://linux-hardware.org/?probe=d28414a8c7) | Jun 06, 2020 |
| Gateway       | NV52 Series                 | [967f9cd454](https://linux-hardware.org/?probe=967f9cd454) | Jun 06, 2020 |
| Gateway       | NV52 Series                 | [df1a4710aa](https://linux-hardware.org/?probe=df1a4710aa) | Jun 06, 2020 |
| Dell          | Precision 3541              | [5a6781a448](https://linux-hardware.org/?probe=5a6781a448) | Jun 05, 2020 |
| HP            | ProBook 6550b               | [6293b416bd](https://linux-hardware.org/?probe=6293b416bd) | Jun 05, 2020 |
| Dell          | Precision 3541              | [be3ef4d26f](https://linux-hardware.org/?probe=be3ef4d26f) | Jun 04, 2020 |
| HP            | Pavilion dv6000 (RE149PA... | [cb4959392e](https://linux-hardware.org/?probe=cb4959392e) | Jun 03, 2020 |
| HP            | ProBook 440 G3              | [5c581c3814](https://linux-hardware.org/?probe=5c581c3814) | May 29, 2020 |
| HP            | ProBook 440 G3              | [2308b69ab8](https://linux-hardware.org/?probe=2308b69ab8) | May 28, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Dell          | XPS L701X                   | [20ec605202](https://linux-hardware.org/?probe=20ec605202) | May 26, 2020 |
| Dell          | Inspiron 1545               | [83046b7849](https://linux-hardware.org/?probe=83046b7849) | May 25, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | [cd8907b605](https://linux-hardware.org/?probe=cd8907b605) | May 23, 2020 |
| Acer          | Aspire one V1.03            | [558ed13a5a](https://linux-hardware.org/?probe=558ed13a5a) | May 22, 2020 |
| Toshiba       | Satellite L300              | [0c8ca0d58e](https://linux-hardware.org/?probe=0c8ca0d58e) | May 22, 2020 |
| Toshiba       | Satellite S70-B             | [1a3ffc8a72](https://linux-hardware.org/?probe=1a3ffc8a72) | May 21, 2020 |
| Dell          | Inspiron MM061              | [35895807f5](https://linux-hardware.org/?probe=35895807f5) | May 20, 2020 |
| VIT           | P3400                       | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| Lenovo        | G480 20156                  | [6cb3a28f6a](https://linux-hardware.org/?probe=6cb3a28f6a) | May 18, 2020 |
| Lenovo        | G480 20156                  | [7487bf67c4](https://linux-hardware.org/?probe=7487bf67c4) | May 18, 2020 |
| Dell          | Inspiron N5110              | [b5a1053ad3](https://linux-hardware.org/?probe=b5a1053ad3) | May 18, 2020 |
| HP            | ProBook 6550b               | [118d12cb4c](https://linux-hardware.org/?probe=118d12cb4c) | May 18, 2020 |
| ASUSTek       | UX305UA                     | [6d5f38b3d2](https://linux-hardware.org/?probe=6d5f38b3d2) | May 17, 2020 |
| Dell          | Vostro 2520                 | [ad99356f1b](https://linux-hardware.org/?probe=ad99356f1b) | May 17, 2020 |
| Dell          | Inspiron 3521               | [2210de4f65](https://linux-hardware.org/?probe=2210de4f65) | May 17, 2020 |
| ASUSTek       | UX305UA                     | [f32207ccb3](https://linux-hardware.org/?probe=f32207ccb3) | May 16, 2020 |
| Lex BayTra... | 3I380D                      | [4f8230c9a2](https://linux-hardware.org/?probe=4f8230c9a2) | May 16, 2020 |
| Lenovo        | ThinkPad T400 6475WNL       | [f3ac8274e3](https://linux-hardware.org/?probe=f3ac8274e3) | May 15, 2020 |
| Lenovo        | ThinkPad T400 6475WNL       | [00572d8593](https://linux-hardware.org/?probe=00572d8593) | May 15, 2020 |
| Toshiba       | NB505                       | [72e6f791ce](https://linux-hardware.org/?probe=72e6f791ce) | May 15, 2020 |
| Apple         | MacBookPro1,2               | [97001e1ce6](https://linux-hardware.org/?probe=97001e1ce6) | May 15, 2020 |
| ASUSTek       | X541SA                      | [9f6745d23a](https://linux-hardware.org/?probe=9f6745d23a) | May 15, 2020 |
| HP            | Presario C300 (RH208UA#A... | [50e95ff237](https://linux-hardware.org/?probe=50e95ff237) | May 14, 2020 |
| HP            | Presario C300 (RH208UA#A... | [6b4a8eab4c](https://linux-hardware.org/?probe=6b4a8eab4c) | May 14, 2020 |
| VIT           | P3400                       | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| ASUSTek       | X751LX                      | [83624c1187](https://linux-hardware.org/?probe=83624c1187) | May 14, 2020 |
| Lex BayTra... | 3I380D                      | [0b64a0a886](https://linux-hardware.org/?probe=0b64a0a886) | May 13, 2020 |
| Dell          | Inspiron 5570               | [f4130ff0f8](https://linux-hardware.org/?probe=f4130ff0f8) | May 11, 2020 |
| ASUSTek       | E202SA                      | [7381f36d6a](https://linux-hardware.org/?probe=7381f36d6a) | May 11, 2020 |
| HP            | G5000 (GF767EA#B1A)         | [39fd61954e](https://linux-hardware.org/?probe=39fd61954e) | May 10, 2020 |
| HP            | Compaq Presario CQ60        | [2dfcbbd4d8](https://linux-hardware.org/?probe=2dfcbbd4d8) | May 10, 2020 |
| Lenovo        | ThinkPad X100e 35084RG      | [e12da0b079](https://linux-hardware.org/?probe=e12da0b079) | May 09, 2020 |
| HP            | Pavilion dv6                | [d158cadba4](https://linux-hardware.org/?probe=d158cadba4) | May 08, 2020 |
| ASUSTek       | W5A                         | [dc722cc814](https://linux-hardware.org/?probe=dc722cc814) | May 07, 2020 |
| ASUSTek       | W5A                         | [87796c2fd4](https://linux-hardware.org/?probe=87796c2fd4) | May 07, 2020 |
| Lenovo        | 3000 G500 VIWGP             | [6d9498e4c2](https://linux-hardware.org/?probe=6d9498e4c2) | May 06, 2020 |
| HP            | ProBook 6550b               | [a66a5084a3](https://linux-hardware.org/?probe=a66a5084a3) | May 05, 2020 |
| HP            | Compaq 621                  | [1236725b50](https://linux-hardware.org/?probe=1236725b50) | May 05, 2020 |
| Dell          | Inspiron 1545               | [ce93456147](https://linux-hardware.org/?probe=ce93456147) | May 04, 2020 |
| Dell          | Inspiron 5567               | [7eb357588a](https://linux-hardware.org/?probe=7eb357588a) | May 04, 2020 |
| Itautec       | Infoway                     | [3b6ec6e95c](https://linux-hardware.org/?probe=3b6ec6e95c) | May 04, 2020 |
| ASUSTek       | K54C                        | [09ff64b15a](https://linux-hardware.org/?probe=09ff64b15a) | May 03, 2020 |
| Dell          | Latitude E6410              | [f0737d5440](https://linux-hardware.org/?probe=f0737d5440) | May 03, 2020 |
| HP            | EliteBook 745 G2            | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| ASUSTek       | K75VJ                       | [9a3f6325dc](https://linux-hardware.org/?probe=9a3f6325dc) | May 02, 2020 |
| ASUSTek       | K75VJ                       | [56b1736c9b](https://linux-hardware.org/?probe=56b1736c9b) | May 02, 2020 |
| Lenovo        | ThinkPad T490 20N2S07D00    | [b1d38c2260](https://linux-hardware.org/?probe=b1d38c2260) | May 02, 2020 |
| HP            | EliteBook 830 G5            | [d3768e3e33](https://linux-hardware.org/?probe=d3768e3e33) | May 02, 2020 |
| Sony          | VPCEH25EN                   | [655c814c3d](https://linux-hardware.org/?probe=655c814c3d) | Apr 30, 2020 |
| Dell          | Inspiron 1525               | [5b97d1d480](https://linux-hardware.org/?probe=5b97d1d480) | Apr 30, 2020 |
| ASUSTek       | G72GX                       | [de6b18fb9e](https://linux-hardware.org/?probe=de6b18fb9e) | Apr 28, 2020 |
| ASUSTek       | G72GX                       | [0d847a29ab](https://linux-hardware.org/?probe=0d847a29ab) | Apr 28, 2020 |
| SLIMBOOK      | Unknown                     | [13560b10be](https://linux-hardware.org/?probe=13560b10be) | Apr 28, 2020 |
| NEC Comput... | Versa Premium 5a            | [2ebe23dbfd](https://linux-hardware.org/?probe=2ebe23dbfd) | Apr 25, 2020 |
| Sony          | VGN-NW270F                  | [938bb8c95e](https://linux-hardware.org/?probe=938bb8c95e) | Apr 24, 2020 |
| Sony          | VGN-NW270F                  | [fea6fb950a](https://linux-hardware.org/?probe=fea6fb950a) | Apr 24, 2020 |
| VIT           | P3400                       | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| HP            | ProBook 440 G3              | [d4b19d60e9](https://linux-hardware.org/?probe=d4b19d60e9) | Apr 23, 2020 |
| Lenovo        | 1.01UL F40-30               | [f47294cfcf](https://linux-hardware.org/?probe=f47294cfcf) | Apr 23, 2020 |
| Acer          | Aspire ES1-420              | [4c7ef7f6bb](https://linux-hardware.org/?probe=4c7ef7f6bb) | Apr 22, 2020 |
| Dell          | Inspiron 15-3552            | [b5721fa9d5](https://linux-hardware.org/?probe=b5721fa9d5) | Apr 22, 2020 |
| Acer          | Extensa 5635Z               | [1e6ec15658](https://linux-hardware.org/?probe=1e6ec15658) | Apr 22, 2020 |
| Acer          | Aspire ES1-420              | [b91215f4ef](https://linux-hardware.org/?probe=b91215f4ef) | Apr 20, 2020 |
| Lenovo        | ThinkPad X200 7458Y28       | [97a042d661](https://linux-hardware.org/?probe=97a042d661) | Apr 20, 2020 |
| Lenovo        | ThinkPad T430 23501D3       | [ef23b7cd57](https://linux-hardware.org/?probe=ef23b7cd57) | Apr 19, 2020 |
| Dell          | Latitude E6520              | [a14bc6170a](https://linux-hardware.org/?probe=a14bc6170a) | Apr 19, 2020 |
| ASUSTek       | 1005HA                      | [5e56323e54](https://linux-hardware.org/?probe=5e56323e54) | Apr 19, 2020 |
| Fujitsu Si... | STYLISTIC ST5112            | [11b436117a](https://linux-hardware.org/?probe=11b436117a) | Apr 18, 2020 |
| Lenovo        | ThinkPad T430 23501D3       | [0676ef554d](https://linux-hardware.org/?probe=0676ef554d) | Apr 18, 2020 |
| ASUSTek       | P43SJ                       | [43a6fcc05e](https://linux-hardware.org/?probe=43a6fcc05e) | Apr 18, 2020 |
| Dell          | Latitude E6400              | [5132bac24a](https://linux-hardware.org/?probe=5132bac24a) | Apr 18, 2020 |
| Dell          | Inspiron 3185               | [9085b76bc2](https://linux-hardware.org/?probe=9085b76bc2) | Apr 18, 2020 |
| Dell          | Inspiron 3185               | [0284898568](https://linux-hardware.org/?probe=0284898568) | Apr 18, 2020 |
| MSI           | Prestige 15 A10SC           | [754f3c176f](https://linux-hardware.org/?probe=754f3c176f) | Apr 18, 2020 |
| Dell          | Inspiron MM061              | [cff92bdf34](https://linux-hardware.org/?probe=cff92bdf34) | Apr 16, 2020 |
| Dell          | Inspiron 3576               | [f13c5f31c8](https://linux-hardware.org/?probe=f13c5f31c8) | Apr 15, 2020 |
| HP            | Compaq Presario CQ60        | [3386ba8a3c](https://linux-hardware.org/?probe=3386ba8a3c) | Apr 15, 2020 |
| Dell          | Inspiron 3576               | [18fa847f1f](https://linux-hardware.org/?probe=18fa847f1f) | Apr 14, 2020 |
| Sony          | VGN-Z21MN_B                 | [89452da1dc](https://linux-hardware.org/?probe=89452da1dc) | Apr 14, 2020 |
| Dell          | Latitude D630               | [518fc3dfc3](https://linux-hardware.org/?probe=518fc3dfc3) | Apr 14, 2020 |
| Toshiba       | PORTEGE M780                | [a7232daef2](https://linux-hardware.org/?probe=a7232daef2) | Apr 14, 2020 |
| Dell          | Latitude D630               | [40d3ea7579](https://linux-hardware.org/?probe=40d3ea7579) | Apr 14, 2020 |
| HP            | Compaq Presario CQ40        | [2e5f5dd30a](https://linux-hardware.org/?probe=2e5f5dd30a) | Apr 13, 2020 |
| HP            | Compaq Presario CQ40        | [d5d9475dc1](https://linux-hardware.org/?probe=d5d9475dc1) | Apr 13, 2020 |
| Medion        | Akoya E1318T                | [7107850c16](https://linux-hardware.org/?probe=7107850c16) | Apr 12, 2020 |
| Intel         | CAPELL VALLEY CRB           | [2d21b4d154](https://linux-hardware.org/?probe=2d21b4d154) | Apr 12, 2020 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [3abad4b18a](https://linux-hardware.org/?probe=3abad4b18a) | Apr 12, 2020 |
| ASUSTek       | 1005HA                      | [ee675e0638](https://linux-hardware.org/?probe=ee675e0638) | Apr 12, 2020 |
| Toshiba       | Portable PC                 | [b6d0428f39](https://linux-hardware.org/?probe=b6d0428f39) | Apr 11, 2020 |
| Toshiba       | Portable PC                 | [6c71de9757](https://linux-hardware.org/?probe=6c71de9757) | Apr 11, 2020 |
| Acer          | Okinawa                     | [ea53ec1d8f](https://linux-hardware.org/?probe=ea53ec1d8f) | Apr 09, 2020 |
| Acer          | AOD257                      | [8e02677217](https://linux-hardware.org/?probe=8e02677217) | Apr 09, 2020 |
| HP            | Notebook                    | [243b502286](https://linux-hardware.org/?probe=243b502286) | Apr 09, 2020 |
| HP            | Notebook                    | [c4d76c217e](https://linux-hardware.org/?probe=c4d76c217e) | Apr 09, 2020 |
| Dell          | Inspiron 3576               | [78de5db868](https://linux-hardware.org/?probe=78de5db868) | Apr 08, 2020 |
| Lenovo        | B50-30 20382                | [70ccb27a0e](https://linux-hardware.org/?probe=70ccb27a0e) | Apr 07, 2020 |
| Positivo      | N1103                       | [cc072662e7](https://linux-hardware.org/?probe=cc072662e7) | Apr 06, 2020 |
| HP            | 246 G6 Notebook PC          | [a17480222d](https://linux-hardware.org/?probe=a17480222d) | Apr 04, 2020 |
| HP            | EliteBook 745 G2            | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| ASUSTek       | PU301LA                     | [84ffd7b059](https://linux-hardware.org/?probe=84ffd7b059) | Apr 02, 2020 |
| HP            | Compaq nc6320 (EY396EA#A... | [737a6eaa7d](https://linux-hardware.org/?probe=737a6eaa7d) | Apr 02, 2020 |
| Acer          | Aspire V5-431               | [65337d1b6e](https://linux-hardware.org/?probe=65337d1b6e) | Apr 02, 2020 |
| Positivo      | N1103                       | [65afb5b440](https://linux-hardware.org/?probe=65afb5b440) | Apr 01, 2020 |
| Positivo      | N1103                       | [d54fdf3157](https://linux-hardware.org/?probe=d54fdf3157) | Apr 01, 2020 |
| Lenovo        | B50-10 80QR                 | [587fb80750](https://linux-hardware.org/?probe=587fb80750) | Apr 01, 2020 |
| Acer          | Aspire V5-431               | [6b1aeb0f24](https://linux-hardware.org/?probe=6b1aeb0f24) | Apr 01, 2020 |
| Dell          | Inspiron 1564               | [9e8332bafa](https://linux-hardware.org/?probe=9e8332bafa) | Apr 01, 2020 |
| Toshiba       | TECRA S5                    | [2b75285e62](https://linux-hardware.org/?probe=2b75285e62) | Mar 31, 2020 |
| Dell          | Inspiron 1564               | [d94635d365](https://linux-hardware.org/?probe=d94635d365) | Mar 30, 2020 |
| Dell          | Inspiron 5570               | [eb90ede90d](https://linux-hardware.org/?probe=eb90ede90d) | Mar 29, 2020 |
| Lenovo        | B320-14IKB 81CC             | [05fac9890f](https://linux-hardware.org/?probe=05fac9890f) | Mar 29, 2020 |
| Dell          | Vostro 3558                 | [cb1025be79](https://linux-hardware.org/?probe=cb1025be79) | Mar 29, 2020 |
| HP            | Pavilion dv6                | [8ed8042b01](https://linux-hardware.org/?probe=8ed8042b01) | Mar 28, 2020 |
| HP            | Mini 210-1000               | [13a419156d](https://linux-hardware.org/?probe=13a419156d) | Mar 28, 2020 |
| Lenovo        | ThinkPad Edge E431 6277C... | [d7ba75061f](https://linux-hardware.org/?probe=d7ba75061f) | Mar 28, 2020 |
| HP            | Pavilion dv6                | [3f0e2ec177](https://linux-hardware.org/?probe=3f0e2ec177) | Mar 28, 2020 |
| HP            | Mini 210-1000               | [14e81921dd](https://linux-hardware.org/?probe=14e81921dd) | Mar 27, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [9bd3cb702e](https://linux-hardware.org/?probe=9bd3cb702e) | Mar 24, 2020 |
| Sony          | VGN-NR11Z_S                 | [69fb7aa4d4](https://linux-hardware.org/?probe=69fb7aa4d4) | Mar 23, 2020 |
| HP            | Presario C500 (GH939EA#A... | [9d467079b9](https://linux-hardware.org/?probe=9d467079b9) | Mar 22, 2020 |
| HP            | Presario C500 (GH939EA#A... | [2f05d7dce7](https://linux-hardware.org/?probe=2f05d7dce7) | Mar 22, 2020 |
| Dell          | Inspiron 5566               | [569830fcde](https://linux-hardware.org/?probe=569830fcde) | Mar 22, 2020 |
| Acer          | TravelMate 5720             | [8c2056a761](https://linux-hardware.org/?probe=8c2056a761) | Mar 21, 2020 |
| Positivo      | Mobile                      | [eec5ff220f](https://linux-hardware.org/?probe=eec5ff220f) | Mar 20, 2020 |
| Positivo      | Mobile                      | [20fb788845](https://linux-hardware.org/?probe=20fb788845) | Mar 20, 2020 |
| Acer          | Lugano M                    | [d131965ba5](https://linux-hardware.org/?probe=d131965ba5) | Mar 20, 2020 |
| Dell          | XPS 13 9360                 | [713d96799f](https://linux-hardware.org/?probe=713d96799f) | Mar 20, 2020 |
| Acer          | Lugano M                    | [4e99059ba4](https://linux-hardware.org/?probe=4e99059ba4) | Mar 20, 2020 |
| ASUSTek       | X455LAB                     | [cfe6c04671](https://linux-hardware.org/?probe=cfe6c04671) | Mar 19, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [7bb8688560](https://linux-hardware.org/?probe=7bb8688560) | Mar 19, 2020 |
| HP            | 250 G3                      | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Lex BayTra... | 3I380D D1                   | [21215f2e75](https://linux-hardware.org/?probe=21215f2e75) | Mar 18, 2020 |
| Dell          | XPS 13 9360                 | [bf956c272a](https://linux-hardware.org/?probe=bf956c272a) | Mar 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [511141014d](https://linux-hardware.org/?probe=511141014d) | Mar 15, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [fee112b1c2](https://linux-hardware.org/?probe=fee112b1c2) | Mar 15, 2020 |
| Hometech      | ALFA 100A                   | [f5a9479d87](https://linux-hardware.org/?probe=f5a9479d87) | Mar 15, 2020 |
| Dell          | Inspiron ME051              | [a60132b1ba](https://linux-hardware.org/?probe=a60132b1ba) | Mar 14, 2020 |
| Lenovo        | ThinkPad P52 20MAS33F00     | [231f2c2d7c](https://linux-hardware.org/?probe=231f2c2d7c) | Mar 12, 2020 |
| HP            | ProBook 4430s               | [c67c490b3a](https://linux-hardware.org/?probe=c67c490b3a) | Mar 12, 2020 |
| HP            | ProBook 4430s               | [fffb69f46a](https://linux-hardware.org/?probe=fffb69f46a) | Mar 12, 2020 |
| HP            | EliteBook 8440p             | [cd13c97ddb](https://linux-hardware.org/?probe=cd13c97ddb) | Mar 11, 2020 |
| Toshiba       | Satellite L40               | [467c320928](https://linux-hardware.org/?probe=467c320928) | Mar 11, 2020 |
| HP            | Pavilion g4                 | [a4c7e541ea](https://linux-hardware.org/?probe=a4c7e541ea) | Mar 10, 2020 |
| QCI           | IL1 March-MP                | [77a2a10d46](https://linux-hardware.org/?probe=77a2a10d46) | Mar 10, 2020 |
| Quanta        | QL3 TBD                     | [b3a25bef44](https://linux-hardware.org/?probe=b3a25bef44) | Mar 09, 2020 |
| Acer          | Cheela                      | [5f504f8819](https://linux-hardware.org/?probe=5f504f8819) | Mar 08, 2020 |
| Toshiba       | Satellite M70               | [6fe0c778e1](https://linux-hardware.org/?probe=6fe0c778e1) | Mar 06, 2020 |
| Fujitsu       | LIFEBOOK E780               | [062a02ab1e](https://linux-hardware.org/?probe=062a02ab1e) | Mar 04, 2020 |
| Dell          | Inspiron 3521               | [b0e7a3178b](https://linux-hardware.org/?probe=b0e7a3178b) | Mar 04, 2020 |
| Dell          | Inspiron 5770               | [fd882c0a0a](https://linux-hardware.org/?probe=fd882c0a0a) | Mar 04, 2020 |
| HP            | Pavilion 14                 | [dd94ec412f](https://linux-hardware.org/?probe=dd94ec412f) | Mar 02, 2020 |
| Toshiba       | Satellite M70               | [5cbf2d8b24](https://linux-hardware.org/?probe=5cbf2d8b24) | Mar 02, 2020 |
| HP            | Pavilion 14                 | [821cda0c0a](https://linux-hardware.org/?probe=821cda0c0a) | Feb 29, 2020 |
| HP            | Mini 210-4000               | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | Laptop 14-dk0xxx            | [d443f243ea](https://linux-hardware.org/?probe=d443f243ea) | Feb 25, 2020 |
| HP            | Laptop 14-dk0xxx            | [ab317bb551](https://linux-hardware.org/?probe=ab317bb551) | Feb 25, 2020 |
| Dell          | Latitude E5530 non-vPro     | [479798d56d](https://linux-hardware.org/?probe=479798d56d) | Feb 23, 2020 |
| Acer          | Aspire 4315                 | [b138f20f4f](https://linux-hardware.org/?probe=b138f20f4f) | Feb 23, 2020 |
| HP            | Laptop 15-dw0xxx            | [9c5def065e](https://linux-hardware.org/?probe=9c5def065e) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [a6fa451303](https://linux-hardware.org/?probe=a6fa451303) | Feb 21, 2020 |
| Alienware     | 17 R4                       | [1786be4cda](https://linux-hardware.org/?probe=1786be4cda) | Feb 21, 2020 |
| Acer          | Aspire 4315                 | [1e2a472e4b](https://linux-hardware.org/?probe=1e2a472e4b) | Feb 20, 2020 |
| Dell          | Precision M6300             | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th E... | [b913bc5cc5](https://linux-hardware.org/?probe=b913bc5cc5) | Feb 18, 2020 |
| Toshiba       | Satellite L745              | [bc067fa44c](https://linux-hardware.org/?probe=bc067fa44c) | Feb 16, 2020 |
| Dell          | Inspiron 5570               | [dd9f9c4446](https://linux-hardware.org/?probe=dd9f9c4446) | Feb 16, 2020 |
| BANGHO        | M7x0S                       | [f056d0963d](https://linux-hardware.org/?probe=f056d0963d) | Feb 13, 2020 |
| BANGHO        | M7x0S                       | [b44de4d481](https://linux-hardware.org/?probe=b44de4d481) | Feb 13, 2020 |
| ASUSTek       | 1005HA                      | [fe94758a61](https://linux-hardware.org/?probe=fe94758a61) | Feb 13, 2020 |
| ASUSTek       | F7F                         | [cb6fe2dd50](https://linux-hardware.org/?probe=cb6fe2dd50) | Feb 13, 2020 |
| Fujitsu Si... | LIFEBOOK S7020              | [0c1a11f760](https://linux-hardware.org/?probe=0c1a11f760) | Feb 11, 2020 |
| HP            | Pavilion g4                 | [001e8f8174](https://linux-hardware.org/?probe=001e8f8174) | Feb 11, 2020 |
| Toshiba       | Satellite L300              | [6c924b861c](https://linux-hardware.org/?probe=6c924b861c) | Feb 10, 2020 |
| HP            | Compaq Presario CQ60        | [bcdb839e6f](https://linux-hardware.org/?probe=bcdb839e6f) | Feb 10, 2020 |
| Toshiba       | Satellite L300              | [05342757e3](https://linux-hardware.org/?probe=05342757e3) | Feb 09, 2020 |
| Notebook      | W54_55SU1,SUW               | [cfb810024c](https://linux-hardware.org/?probe=cfb810024c) | Feb 08, 2020 |
| HP            | Compaq Presario CQ60        | [4529dea4e2](https://linux-hardware.org/?probe=4529dea4e2) | Feb 05, 2020 |
| Dell          | G5 5587                     | [35dab211ca](https://linux-hardware.org/?probe=35dab211ca) | Feb 02, 2020 |
| Apple         | MacBookPro7,1               | [4af76f3e04](https://linux-hardware.org/?probe=4af76f3e04) | Feb 02, 2020 |
| Apple         | MacBookPro7,1               | [05b351742f](https://linux-hardware.org/?probe=05b351742f) | Feb 02, 2020 |
| Apple         | MacBookPro7,1               | [579c9aeb6f](https://linux-hardware.org/?probe=579c9aeb6f) | Feb 02, 2020 |
| Dell          | Latitude D400               | [1629ff31a1](https://linux-hardware.org/?probe=1629ff31a1) | Jan 30, 2020 |
| Positivo      | H14BU08                     | [a51fa278a1](https://linux-hardware.org/?probe=a51fa278a1) | Jan 29, 2020 |
| Acer          | Nitro AN515-42              | [43bfe23e19](https://linux-hardware.org/?probe=43bfe23e19) | Jan 24, 2020 |
| Dell          | Latitude E4300              | [3a3c8e2e2d](https://linux-hardware.org/?probe=3a3c8e2e2d) | Jan 21, 2020 |
| HP            | HDX16                       | [c1888ecdc4](https://linux-hardware.org/?probe=c1888ecdc4) | Jan 21, 2020 |
| Dell          | Latitude D510               | [16d4712a17](https://linux-hardware.org/?probe=16d4712a17) | Jan 21, 2020 |
| Lenovo        | IdeaPad Z460 0913           | [0b8ae13c03](https://linux-hardware.org/?probe=0b8ae13c03) | Jan 19, 2020 |
| Fujitsu Si... | AMILO PI 1536               | [91574e4803](https://linux-hardware.org/?probe=91574e4803) | Jan 19, 2020 |
| Toshiba       | Satellite L500              | [10bcd37c3a](https://linux-hardware.org/?probe=10bcd37c3a) | Jan 17, 2020 |
| HP            | Pavilion dv6                | [620ab6d879](https://linux-hardware.org/?probe=620ab6d879) | Jan 17, 2020 |
| Apple         | MacBook2,1                  | [3e1bb440f1](https://linux-hardware.org/?probe=3e1bb440f1) | Jan 14, 2020 |
| HP            | Pavilion dv6                | [1ddff22ba3](https://linux-hardware.org/?probe=1ddff22ba3) | Jan 13, 2020 |
| Lenovo        | ThinkPad R61 8934FAF        | [25f7589cee](https://linux-hardware.org/?probe=25f7589cee) | Jan 10, 2020 |
| HP            | Pavilion dv6                | [b182a250d2](https://linux-hardware.org/?probe=b182a250d2) | Jan 05, 2020 |
| Acer          | Coniston                    | [239f09af80](https://linux-hardware.org/?probe=239f09af80) | Jan 05, 2020 |
| Dixonsxp      | Unknown                     | [7dc2298126](https://linux-hardware.org/?probe=7dc2298126) | Jan 04, 2020 |
| HP            | Pavilion dv6                | [cabb6b4ce4](https://linux-hardware.org/?probe=cabb6b4ce4) | Jan 01, 2020 |
| Acer          | Extensa 5620                | [46eef95619](https://linux-hardware.org/?probe=46eef95619) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Toshiba       | Satellite C850              | [344fc248fd](https://linux-hardware.org/?probe=344fc248fd) | Dec 30, 2019 |
| Lenovo        | G500s 20245                 | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | Pavilion dv6                | [e9a9c77c0e](https://linux-hardware.org/?probe=e9a9c77c0e) | Dec 29, 2019 |
| Dell          | Inspiron 5423               | [ed50d52b54](https://linux-hardware.org/?probe=ed50d52b54) | Dec 28, 2019 |
| Dell          | Inspiron 5423               | [5b5632e40c](https://linux-hardware.org/?probe=5b5632e40c) | Dec 28, 2019 |
| Toshiba       | Satellite L350D             | [313239f785](https://linux-hardware.org/?probe=313239f785) | Dec 28, 2019 |
| Gateway       | NV53A                       | [8f0fe2910d](https://linux-hardware.org/?probe=8f0fe2910d) | Dec 27, 2019 |
| HP            | 530 Notebook PC(KP479AA#... | [3e6684e155](https://linux-hardware.org/?probe=3e6684e155) | Dec 27, 2019 |
| Acer          | Extensa 5620                | [ba9eff4f3b](https://linux-hardware.org/?probe=ba9eff4f3b) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| ASUSTek       | X550EP                      | [19abb6c0fb](https://linux-hardware.org/?probe=19abb6c0fb) | Dec 23, 2019 |
| Lenovo        | ThinkPad Edge 03285EG       | [c9c2eff56c](https://linux-hardware.org/?probe=c9c2eff56c) | Dec 22, 2019 |
| MSI           | GV72 8RD                    | [727c36d58e](https://linux-hardware.org/?probe=727c36d58e) | Dec 20, 2019 |
| Fujitsu       | LIFEBOOK E743               | [da5836e2aa](https://linux-hardware.org/?probe=da5836e2aa) | Dec 19, 2019 |
| HP            | Pavilion 17                 | [6202d247cd](https://linux-hardware.org/?probe=6202d247cd) | Dec 18, 2019 |
| HP            | Pavilion dv6000 (RX019AV... | [e6d736339f](https://linux-hardware.org/?probe=e6d736339f) | Dec 18, 2019 |
| HP            | Pavilion Power Laptop 15... | [57d88c2293](https://linux-hardware.org/?probe=57d88c2293) | Dec 16, 2019 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [25325d332c](https://linux-hardware.org/?probe=25325d332c) | Dec 12, 2019 |
| Lenovo        | ThinkPad T61 7665V2R        | [dec2d5efb5](https://linux-hardware.org/?probe=dec2d5efb5) | Dec 12, 2019 |
| HP            | Pavilion dv6                | [6fc0731e65](https://linux-hardware.org/?probe=6fc0731e65) | Dec 11, 2019 |
| Toshiba       | Satellite C55-B             | [ab7fdcfebc](https://linux-hardware.org/?probe=ab7fdcfebc) | Dec 10, 2019 |
| Dell          | XPS 15 9550                 | [5add808e4a](https://linux-hardware.org/?probe=5add808e4a) | Dec 09, 2019 |
| HP            | G72                         | [eb3dad0132](https://linux-hardware.org/?probe=eb3dad0132) | Dec 09, 2019 |
| HP            | Pavilion 15                 | [b881a7c58c](https://linux-hardware.org/?probe=b881a7c58c) | Dec 09, 2019 |
| Fujitsu       | LIFEBOOK S782               | [153afabcb5](https://linux-hardware.org/?probe=153afabcb5) | Dec 04, 2019 |
| HP            | EliteBook 8560p             | [0d2fe88be0](https://linux-hardware.org/?probe=0d2fe88be0) | Nov 29, 2019 |
| Lenovo        | G570 4334                   | [0a5af961d7](https://linux-hardware.org/?probe=0a5af961d7) | Nov 29, 2019 |
| Lenovo        | ThinkPad T410 2537RB7       | [5b742ab47b](https://linux-hardware.org/?probe=5b742ab47b) | Nov 29, 2019 |
| Lenovo        | ThinkPad T410 2537RB7       | [8a01359212](https://linux-hardware.org/?probe=8a01359212) | Nov 29, 2019 |
| Lenovo        | G570 4334                   | [a3b3814f28](https://linux-hardware.org/?probe=a3b3814f28) | Nov 28, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| Dell          | System XPS L502X            | [623101188f](https://linux-hardware.org/?probe=623101188f) | Nov 20, 2019 |
| Dell          | Inspiron N5050              | [f4cae8af59](https://linux-hardware.org/?probe=f4cae8af59) | Nov 19, 2019 |
| Lenovo        | G50-70 20351                | [f79c20b038](https://linux-hardware.org/?probe=f79c20b038) | Nov 18, 2019 |
| Acer          | Aspire 7220                 | [4521ffbd6d](https://linux-hardware.org/?probe=4521ffbd6d) | Nov 18, 2019 |
| Lenovo        | IdeaPad S100c 20194         | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| HP            | Pavilion Notebook           | [e147d2f69a](https://linux-hardware.org/?probe=e147d2f69a) | Nov 14, 2019 |
| eMachines     | E725                        | [06977d3fe7](https://linux-hardware.org/?probe=06977d3fe7) | Nov 13, 2019 |
| eMachines     | E725                        | [0b59587edf](https://linux-hardware.org/?probe=0b59587edf) | Nov 13, 2019 |
| Lenovo        | V510-14IKB 80WR             | [649bc0e8ee](https://linux-hardware.org/?probe=649bc0e8ee) | Nov 13, 2019 |
| Lenovo        | V510-14IKB 80WR             | [a21f74c946](https://linux-hardware.org/?probe=a21f74c946) | Nov 13, 2019 |
| Lenovo        | V145-15AST 81MT             | [7e3fe1add7](https://linux-hardware.org/?probe=7e3fe1add7) | Nov 12, 2019 |
| Lenovo        | IdeaPadFlex 15 20309        | [26f33af041](https://linux-hardware.org/?probe=26f33af041) | Sep 20, 2019 |
| Acer          | Aspire E5-574G              | [b9139a5b72](https://linux-hardware.org/?probe=b9139a5b72) | Sep 05, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| Lenovo        | 3000 C100 076124P           | [edae63a429](https://linux-hardware.org/?probe=edae63a429) | Jun 19, 2019 |
| HP            | Notebook                    | [4fa9406328](https://linux-hardware.org/?probe=4fa9406328) | Apr 22, 2019 |
| Fujitsu       | FMVNE4N1E                   | [8e2c99692b](https://linux-hardware.org/?probe=8e2c99692b) | Dec 29, 2018 |
| Lenovo        | B50-80 80EW                 | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo        | B50-80 80EW                 | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| HUAWEI        | MateBook X                  | [766158c703](https://linux-hardware.org/?probe=766158c703) | Dec 23, 2018 |
| ASUSTek       | G551JX                      | [f8c670ca57](https://linux-hardware.org/?probe=f8c670ca57) | Dec 10, 2018 |
| ASUSTek       | G551JX                      | [b6fd8d2b78](https://linux-hardware.org/?probe=b6fd8d2b78) | Dec 10, 2018 |
| Dell          | Latitude 7290               | [bbfdf26e6c](https://linux-hardware.org/?probe=bbfdf26e6c) | Oct 16, 2018 |
| Dell          | Latitude 7290               | [c7c6a273e6](https://linux-hardware.org/?probe=c7c6a273e6) | Oct 16, 2018 |
| Hampoo        | C1W6_AP123C_6GB Reserved    | [38f6161d86](https://linux-hardware.org/?probe=38f6161d86) | Aug 26, 2018 |
| Dell          | XPS 15 9550                 | [ac68474628](https://linux-hardware.org/?probe=ac68474628) | Jun 22, 2018 |
| Dell          | XPS 15 9550                 | [9abdeaae72](https://linux-hardware.org/?probe=9abdeaae72) | Jun 22, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Unity/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu Unity 16.04 | 323       | 53.04%  |
| Ubuntu Unity 20.04 | 121       | 19.87%  |
| Ubuntu Unity 18.04 | 105       | 17.24%  |
| Ubuntu Unity 22.04 | 27        | 4.43%   |
| Ubuntu Unity 22.10 | 9         | 1.48%   |
| Ubuntu Unity 21.10 | 5         | 0.82%   |
| Ubuntu Unity 21.04 | 5         | 0.82%   |
| Ubuntu Unity 19.10 | 5         | 0.82%   |
| Ubuntu Unity 23.04 | 3         | 0.49%   |
| Ubuntu Unity 20.10 | 2         | 0.33%   |
| Ubuntu Unity 14.04 | 2         | 0.33%   |
| Ubuntu Unity 19.04 | 1         | 0.16%   |
| Ubuntu Unity 18.10 | 1         | 0.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu Unity | 607       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 4.15.0-142-generic | 46        | 7.08%   |
| 4.15.0-112-generic | 26        | 4%      |
| 4.15.0-99-generic  | 24        | 3.69%   |
| 4.4.0-210-generic  | 23        | 3.54%   |
| 4.15.0-91-generic  | 19        | 2.92%   |
| 4.15.0-96-generic  | 18        | 2.77%   |
| 4.15.0-72-generic  | 15        | 2.31%   |
| 4.15.0-45-generic  | 15        | 2.31%   |
| 5.4.0-48-generic   | 12        | 1.85%   |
| 5.4.0-42-generic   | 12        | 1.85%   |
| 4.15.0-88-generic  | 11        | 1.69%   |
| 4.15.0-118-generic | 9         | 1.38%   |
| 4.4.0-177-generic  | 8         | 1.23%   |
| 4.15.0-76-generic  | 8         | 1.23%   |
| 4.15.0-128-generic | 8         | 1.23%   |
| 4.15.0-101-generic | 8         | 1.23%   |
| 5.4.0-58-generic   | 7         | 1.08%   |
| 5.4.0-47-generic   | 7         | 1.08%   |
| 4.15.0-74-generic  | 7         | 1.08%   |
| 4.15.0-117-generic | 7         | 1.08%   |
| 5.4.0-52-generic   | 6         | 0.92%   |
| 4.4.0-176-generic  | 6         | 0.92%   |
| 4.4.0-174-generic  | 6         | 0.92%   |
| 4.15.0-70-generic  | 6         | 0.92%   |
| 4.15.0-133-generic | 6         | 0.92%   |
| 4.15.0-129-generic | 6         | 0.92%   |
| 4.15.0-107-generic | 6         | 0.92%   |
| 4.15.0-106-generic | 6         | 0.92%   |
| 5.15.0-56-generic  | 5         | 0.77%   |
| 4.4.0-184-generic  | 5         | 0.77%   |
| 4.4.0-173-generic  | 5         | 0.77%   |
| 4.15.0-122-generic | 5         | 0.77%   |
| 5.4.0-65-generic   | 4         | 0.62%   |
| 5.4.0-56-generic   | 4         | 0.62%   |
| 5.19.0-23-generic  | 4         | 0.62%   |
| 5.11.0-38-generic  | 4         | 0.62%   |
| 4.4.0-193-generic  | 4         | 0.62%   |
| 4.4.0-189-generic  | 4         | 0.62%   |
| 4.4.0-186-generic  | 4         | 0.62%   |
| 4.4.0-185-generic  | 4         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15.0  | 301       | 49.18%  |
| 5.4.0   | 98        | 16.01%  |
| 4.4.0   | 97        | 15.85%  |
| 5.15.0  | 22        | 3.59%   |
| 5.8.0   | 15        | 2.45%   |
| 5.19.0  | 15        | 2.45%   |
| 5.3.0   | 11        | 1.8%    |
| 5.11.0  | 11        | 1.8%    |
| 5.13.0  | 8         | 1.31%   |
| 5.0.0   | 6         | 0.98%   |
| 4.13.0  | 4         | 0.65%   |
| 6.2.0   | 3         | 0.49%   |
| 4.8.0   | 3         | 0.49%   |
| 4.18.0  | 2         | 0.33%   |
| 6.0.0   | 1         | 0.16%   |
| 5.9.6   | 1         | 0.16%   |
| 5.7.19  | 1         | 0.16%   |
| 5.7.1   | 1         | 0.16%   |
| 5.5.11  | 1         | 0.16%   |
| 5.4.14  | 1         | 0.16%   |
| 5.17.0  | 1         | 0.16%   |
| 5.16.8  | 1         | 0.16%   |
| 5.16.4  | 1         | 0.16%   |
| 5.14.0  | 1         | 0.16%   |
| 5.12.1  | 1         | 0.16%   |
| 5.12.0  | 1         | 0.16%   |
| 5.0.7   | 1         | 0.16%   |
| 4.19.88 | 1         | 0.16%   |
| 4.19.12 | 1         | 0.16%   |
| 3.13.0  | 1         | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15    | 301       | 49.18%  |
| 5.4     | 99        | 16.18%  |
| 4.4     | 97        | 15.85%  |
| 5.15    | 22        | 3.59%   |
| 5.8     | 15        | 2.45%   |
| 5.19    | 15        | 2.45%   |
| 5.3     | 11        | 1.8%    |
| 5.11    | 11        | 1.8%    |
| 5.13    | 8         | 1.31%   |
| 5.0     | 7         | 1.14%   |
| 4.13    | 4         | 0.65%   |
| 6.2     | 3         | 0.49%   |
| 4.8     | 3         | 0.49%   |
| 5.7     | 2         | 0.33%   |
| 5.16    | 2         | 0.33%   |
| 5.12    | 2         | 0.33%   |
| 4.19    | 2         | 0.33%   |
| 4.18    | 2         | 0.33%   |
| 6.0     | 1         | 0.16%   |
| 5.9     | 1         | 0.16%   |
| 5.5     | 1         | 0.16%   |
| 5.17    | 1         | 0.16%   |
| 5.14    | 1         | 0.16%   |
| 3.13    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 423       | 69.69%  |
| i686   | 184       | 30.31%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Unity | 598       | 98.36%  |
| GNOME | 9         | 1.48%   |
| KDE5  | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 557       | 91.61%  |
| Wayland | 49        | 8.06%   |
| Tty     | 2         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 370       | 59.87%  |
| LightDM | 126       | 20.39%  |
| GDM     | 101       | 16.34%  |
| GDM3    | 21        | 3.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 227       | 37.34%  |
| de_DE   | 47        | 7.73%   |
| pt_BR   | 42        | 6.91%   |
| en_IN   | 42        | 6.91%   |
| en_GB   | 28        | 4.61%   |
| fr_FR   | 26        | 4.28%   |
| Unknown | 20        | 3.29%   |
| it_IT   | 18        | 2.96%   |
| ru_RU   | 17        | 2.8%    |
| es_ES   | 16        | 2.63%   |
| pl_PL   | 11        | 1.81%   |
| en_AU   | 10        | 1.64%   |
| en_CA   | 9         | 1.48%   |
| hu_HU   | 8         | 1.32%   |
| tr_TR   | 5         | 0.82%   |
| pt_PT   | 5         | 0.82%   |
| en_ZA   | 5         | 0.82%   |
| zh_CN   | 4         | 0.66%   |
| nl_NL   | 4         | 0.66%   |
| es_MX   | 4         | 0.66%   |
| nl_BE   | 3         | 0.49%   |
| ja_JP   | 3         | 0.49%   |
| es_AR   | 3         | 0.49%   |
| el_GR   | 3         | 0.49%   |
| da_DK   | 3         | 0.49%   |
| cs_CZ   | 3         | 0.49%   |
| zh_TW   | 2         | 0.33%   |
| sv_SE   | 2         | 0.33%   |
| sk_SK   | 2         | 0.33%   |
| ro_RO   | 2         | 0.33%   |
| es_GT   | 2         | 0.33%   |
| es_CO   | 2         | 0.33%   |
| en_NZ   | 2         | 0.33%   |
| en_IE   | 2         | 0.33%   |
| de_CH   | 2         | 0.33%   |
| de_AT   | 2         | 0.33%   |
| C       | 2         | 0.33%   |
| bg_BG   | 2         | 0.33%   |
| th_TH   | 1         | 0.16%   |
| sl_SI   | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 388       | 63.71%  |
| EFI  | 221       | 36.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 594       | 97.86%  |
| Tmpfs    | 4         | 0.66%   |
| Ext3     | 2         | 0.33%   |
| Btrfs    | 2         | 0.33%   |
| Zfs      | 1         | 0.16%   |
| SquasXfs | 1         | 0.16%   |
| Overlay  | 1         | 0.16%   |
| Ext2     | 1         | 0.16%   |
| Aufs     | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 424       | 69.17%  |
| GPT     | 130       | 21.21%  |
| MBR     | 59        | 9.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 576       | 94.27%  |
| Yes       | 35        | 5.73%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 419       | 68.8%   |
| Yes       | 190       | 31.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 119       | 19.6%   |
| Dell                | 118       | 19.44%  |
| Lenovo              | 107       | 17.63%  |
| Acer                | 52        | 8.57%   |
| ASUSTek Computer    | 49        | 8.07%   |
| Toshiba             | 34        | 5.6%    |
| Apple               | 12        | 1.98%   |
| Sony                | 11        | 1.81%   |
| Fujitsu Siemens     | 10        | 1.65%   |
| Samsung Electronics | 9         | 1.48%   |
| Positivo            | 6         | 0.99%   |
| HUAWEI              | 6         | 0.99%   |
| Fujitsu             | 6         | 0.99%   |
| MSI                 | 5         | 0.82%   |
| Timi                | 4         | 0.66%   |
| Notebook            | 4         | 0.66%   |
| Medion              | 4         | 0.66%   |
| Itautec             | 4         | 0.66%   |
| LG Electronics      | 3         | 0.49%   |
| Panasonic           | 2         | 0.33%   |
| Packard Bell        | 2         | 0.33%   |
| NEC Computers       | 2         | 0.33%   |
| Lex BayTrail        | 2         | 0.33%   |
| Intel               | 2         | 0.33%   |
| Hometech            | 2         | 0.33%   |
| Gigabyte Technology | 2         | 0.33%   |
| Gateway             | 2         | 0.33%   |
| eMachines           | 2         | 0.33%   |
| Chuwi               | 2         | 0.33%   |
| Alienware           | 2         | 0.33%   |
| Unknown             | 2         | 0.33%   |
| VIT                 | 1         | 0.16%   |
| TG                  | 1         | 0.16%   |
| TELECOMITALIA       | 1         | 0.16%   |
| Teclast             | 1         | 0.16%   |
| SLIMBOOK            | 1         | 0.16%   |
| SINTRONES           | 1         | 0.16%   |
| Semp Toshiba        | 1         | 0.16%   |
| Quanta              | 1         | 0.16%   |
| QCI                 | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| HP Pavilion dv6                  | 6         | 0.99%   |
| Unknown                          | 5         | 0.82%   |
| HP ProBook 6550b                 | 4         | 0.66%   |
| HP Mini 210-1000                 | 4         | 0.66%   |
| Toshiba Satellite L300           | 3         | 0.49%   |
| Positivo Mobile                  | 3         | 0.49%   |
| Itautec Infoway                  | 3         | 0.49%   |
| HP Notebook                      | 3         | 0.49%   |
| Dell XPS 13 9370                 | 3         | 0.49%   |
| Dell Latitude 7480               | 3         | 0.49%   |
| Dell Inspiron 5570               | 3         | 0.49%   |
| Dell Inspiron 3521               | 3         | 0.49%   |
| Dell Inspiron 1545               | 3         | 0.49%   |
| ASUS 1005HA                      | 3         | 0.49%   |
| Toshiba Portable PC              | 2         | 0.33%   |
| Timi TM1701                      | 2         | 0.33%   |
| Positivo N1103                   | 2         | 0.33%   |
| Medion Akoya THE TOUCH 10        | 2         | 0.33%   |
| Lenovo V145-15AST 81MT           | 2         | 0.33%   |
| Lenovo G50-70 20351              | 2         | 0.33%   |
| HP ZBook 17 G3                   | 2         | 0.33%   |
| HP ProBook 455 G1                | 2         | 0.33%   |
| HP ProBook 440 G3                | 2         | 0.33%   |
| HP Pavilion Notebook             | 2         | 0.33%   |
| HP Pavilion g4                   | 2         | 0.33%   |
| HP Pavilion dv7                  | 2         | 0.33%   |
| HP Pavilion dv6000 (RP297UA#ABA) | 2         | 0.33%   |
| HP Compaq Presario CQ60          | 2         | 0.33%   |
| Dell XPS 15 9550                 | 2         | 0.33%   |
| Dell XPS 13 9360                 | 2         | 0.33%   |
| Dell XPS 13 9310                 | 2         | 0.33%   |
| Dell XPS 13 7390                 | 2         | 0.33%   |
| Dell Latitude E7450              | 2         | 0.33%   |
| Dell Latitude E6400              | 2         | 0.33%   |
| Dell Latitude E4310              | 2         | 0.33%   |
| Dell Latitude D630               | 2         | 0.33%   |
| Dell Latitude D620               | 2         | 0.33%   |
| Dell Inspiron MM061              | 2         | 0.33%   |
| Dell Inspiron 7577               | 2         | 0.33%   |
| Dell Inspiron 5567               | 2         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 55        | 9.06%   |
| Dell Inspiron            | 43        | 7.08%   |
| Dell Latitude            | 33        | 5.44%   |
| Acer Aspire              | 33        | 5.44%   |
| HP Pavilion              | 28        | 4.61%   |
| Toshiba Satellite        | 25        | 4.12%   |
| HP ProBook               | 18        | 2.97%   |
| Dell XPS                 | 17        | 2.8%    |
| Lenovo IdeaPad           | 16        | 2.64%   |
| HP Compaq                | 15        | 2.47%   |
| HP EliteBook             | 14        | 2.31%   |
| Dell Vostro              | 9         | 1.48%   |
| HP ZBook                 | 8         | 1.32%   |
| Dell Precision           | 7         | 1.15%   |
| HP Mini                  | 6         | 0.99%   |
| Fujitsu LIFEBOOK         | 5         | 0.82%   |
| Unknown                  | 5         | 0.82%   |
| Itautec Infoway          | 4         | 0.66%   |
| HP Presario              | 4         | 0.66%   |
| HP Laptop                | 4         | 0.66%   |
| HP ENVY                  | 4         | 0.66%   |
| Fujitsu Siemens LIFEBOOK | 4         | 0.66%   |
| ASUS VivoBook            | 4         | 0.66%   |
| Acer TravelMate          | 4         | 0.66%   |
| Acer Extensa             | 4         | 0.66%   |
| Positivo Mobile          | 3         | 0.49%   |
| Medion Akoya             | 3         | 0.49%   |
| Lenovo Legion            | 3         | 0.49%   |
| Lenovo 3000              | 3         | 0.49%   |
| HP Notebook              | 3         | 0.49%   |
| Dell System              | 3         | 0.49%   |
| ASUS 1005HA              | 3         | 0.49%   |
| Apple MacBookPro1        | 3         | 0.49%   |
| Toshiba TECRA            | 2         | 0.33%   |
| Toshiba Portable         | 2         | 0.33%   |
| Toshiba dynabook         | 2         | 0.33%   |
| Timi TM1701              | 2         | 0.33%   |
| Positivo N1103           | 2         | 0.33%   |
| Packard Bell EasyNote    | 2         | 0.33%   |
| Lex BayTrail 3I380D      | 2         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2008    | 58        | 9.56%   |
| 2009    | 50        | 8.24%   |
| 2010    | 45        | 7.41%   |
| 2015    | 39        | 6.43%   |
| 2012    | 39        | 6.43%   |
| 2017    | 38        | 6.26%   |
| 2011    | 38        | 6.26%   |
| 2018    | 36        | 5.93%   |
| 2007    | 36        | 5.93%   |
| 2019    | 35        | 5.77%   |
| 2016    | 34        | 5.6%    |
| 2014    | 32        | 5.27%   |
| 2013    | 31        | 5.11%   |
| 2006    | 29        | 4.78%   |
| 2020    | 26        | 4.28%   |
| 2021    | 15        | 2.47%   |
| 2005    | 15        | 2.47%   |
| 2022    | 8         | 1.32%   |
| Unknown | 2         | 0.33%   |
| 2002    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 607       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 562       | 92.59%  |
| Enabled  | 45        | 7.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 607       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 150       | 24.63%  |
| 4.01-8.0    | 109       | 17.9%   |
| 1.01-2.0    | 89        | 14.61%  |
| 16.01-24.0  | 83        | 13.63%  |
| 8.01-16.0   | 76        | 12.48%  |
| 0.51-1.0    | 37        | 6.08%   |
| 2.01-3.0    | 35        | 5.75%   |
| 32.01-64.0  | 19        | 3.12%   |
| 24.01-32.0  | 5         | 0.82%   |
| 64.01-256.0 | 4         | 0.66%   |
| 0.01-0.5    | 2         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 254       | 40.13%  |
| 0.51-1.0   | 115       | 18.17%  |
| 2.01-3.0   | 104       | 16.43%  |
| 4.01-8.0   | 72        | 11.37%  |
| 3.01-4.0   | 56        | 8.85%   |
| 8.01-16.0  | 21        | 3.32%   |
| 0.01-0.5   | 8         | 1.26%   |
| 32.01-64.0 | 1         | 0.16%   |
| 16.01-24.0 | 1         | 0.16%   |
| Unknown    | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 477       | 78.07%  |
| 2      | 114       | 18.66%  |
| 3      | 13        | 2.13%   |
| 0      | 6         | 0.98%   |
| 4      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 51.32%  |
| No        | 296       | 48.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 542       | 88.85%  |
| No        | 68        | 11.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 593       | 97.69%  |
| No        | 14        | 2.31%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 357       | 58.43%  |
| No        | 254       | 41.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 95        | 15.63%  |
| Germany      | 52        | 8.55%   |
| Brazil       | 52        | 8.55%   |
| India        | 44        | 7.24%   |
| UK           | 27        | 4.44%   |
| Russia       | 25        | 4.11%   |
| Spain        | 23        | 3.78%   |
| France       | 22        | 3.62%   |
| Italy        | 21        | 3.45%   |
| Belgium      | 13        | 2.14%   |
| Poland       | 11        | 1.81%   |
| Canada       | 11        | 1.81%   |
| Turkey       | 10        | 1.64%   |
| Australia    | 10        | 1.64%   |
| Romania      | 9         | 1.48%   |
| Netherlands  | 9         | 1.48%   |
| Ukraine      | 8         | 1.32%   |
| Hungary      | 8         | 1.32%   |
| Mexico       | 7         | 1.15%   |
| Japan        | 7         | 1.15%   |
| Portugal     | 6         | 0.99%   |
| Bulgaria     | 6         | 0.99%   |
| Vietnam      | 5         | 0.82%   |
| South Africa | 5         | 0.82%   |
| Morocco      | 5         | 0.82%   |
| Indonesia    | 5         | 0.82%   |
| Denmark      | 5         | 0.82%   |
| Czechia      | 5         | 0.82%   |
| Austria      | 5         | 0.82%   |
| Greece       | 4         | 0.66%   |
| Colombia     | 4         | 0.66%   |
| Argentina    | 4         | 0.66%   |
| Switzerland  | 3         | 0.49%   |
| Sweden       | 3         | 0.49%   |
| Slovakia     | 3         | 0.49%   |
| Pakistan     | 3         | 0.49%   |
| New Zealand  | 3         | 0.49%   |
| Ireland      | 3         | 0.49%   |
| Iran         | 3         | 0.49%   |
| Hong Kong    | 3         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 8         | 1.28%   |
| Berlin            | 6         | 0.96%   |
| Warsaw            | 5         | 0.8%    |
| Sydney            | 5         | 0.8%    |
| Moscow            | 5         | 0.8%    |
| Hyderabad         | 5         | 0.8%    |
| Brasília         | 5         | 0.8%    |
| Rome              | 4         | 0.64%   |
| Pune              | 4         | 0.64%   |
| New Delhi         | 4         | 0.64%   |
| Milan             | 4         | 0.64%   |
| Budapest          | 4         | 0.64%   |
| Bogotá           | 4         | 0.64%   |
| Bengaluru         | 4         | 0.64%   |
| Barcelona         | 4         | 0.64%   |
| St Petersburg     | 3         | 0.48%   |
| Rio de Janeiro    | 3         | 0.48%   |
| Paris             | 3         | 0.48%   |
| Mumbai            | 3         | 0.48%   |
| Montreal          | 3         | 0.48%   |
| Lisbon            | 3         | 0.48%   |
| Kyiv              | 3         | 0.48%   |
| Istanbul          | 3         | 0.48%   |
| Hanoi             | 3         | 0.48%   |
| Frankfurt am Main | 3         | 0.48%   |
| Delhi             | 3         | 0.48%   |
| Cape Town         | 3         | 0.48%   |
| Athens            | 3         | 0.48%   |
| Ankara            | 3         | 0.48%   |
| Amsterdam         | 3         | 0.48%   |
| Yekaterinburg     | 2         | 0.32%   |
| Wetteren          | 2         | 0.32%   |
| Voronezh          | 2         | 0.32%   |
| Vienna            | 2         | 0.32%   |
| Valencia          | 2         | 0.32%   |
| Sofia             | 2         | 0.32%   |
| Silkeborg         | 2         | 0.32%   |
| Shenzhen          | 2         | 0.32%   |
| Orlando           | 2         | 0.32%   |
| Nicosia           | 2         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 104       | 110    | 15.01%  |
| Seagate                        | 98        | 105    | 14.14%  |
| Toshiba                        | 88        | 100    | 12.7%   |
| Samsung Electronics            | 85        | 100    | 12.27%  |
| Hitachi                        | 57        | 59     | 8.23%   |
| HGST                           | 35        | 45     | 5.05%   |
| Kingston                       | 33        | 35     | 4.76%   |
| Unknown                        | 27        | 28     | 3.9%    |
| SanDisk                        | 21        | 23     | 3.03%   |
| Micron Technology              | 16        | 18     | 2.31%   |
| Crucial                        | 15        | 17     | 2.16%   |
| Fujitsu                        | 14        | 14     | 2.02%   |
| Intel                          | 13        | 14     | 1.88%   |
| SK hynix                       | 11        | 11     | 1.59%   |
| LITEON                         | 9         | 11     | 1.3%    |
| LITEONIT                       | 5         | 8      | 0.72%   |
| SPCC                           | 4         | 5      | 0.58%   |
| KIOXIA                         | 4         | 4      | 0.58%   |
| Intenso                        | 4         | 5      | 0.58%   |
| A-DATA Technology              | 4         | 4      | 0.58%   |
| Transcend                      | 3         | 3      | 0.43%   |
| PNY                            | 3         | 3      | 0.43%   |
| OCZ                            | 3         | 3      | 0.43%   |
| Verbatim                       | 2         | 2      | 0.29%   |
| StoreJet                       | 2         | 2      | 0.29%   |
| Silicon Motion                 | 2         | 2      | 0.29%   |
| Patriot                        | 2         | 2      | 0.29%   |
| Lenovo                         | 2         | 2      | 0.29%   |
| KingDian                       | 2         | 2      | 0.29%   |
| JMicron Technology             | 2         | 2      | 0.29%   |
| IBM/Hitachi                    | 2         | 2      | 0.29%   |
| Apple                          | 2         | 3      | 0.29%   |
| XrayDisk                       | 1         | 1      | 0.14%   |
| USB                            | 1         | 2      | 0.14%   |
| Team                           | 1         | 3      | 0.14%   |
| SUNEAST                        | 1         | 1      | 0.14%   |
| STEC                           | 1         | 1      | 0.14%   |
| Solid State Storage Technology | 1         | 1      | 0.14%   |
| SABRENT                        | 1         | 1      | 0.14%   |
| NGFF                           | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 14        | 1.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 1.42%   |
| HGST HTS545050A7E680 500GB          | 10        | 1.42%   |
| Toshiba MQ01ABF050 500GB            | 9         | 1.27%   |
| Unknown MMC Card  32GB              | 8         | 1.13%   |
| HGST HTS721010A9E630 1TB            | 6         | 0.85%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 0.71%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 0.71%   |
| Samsung NVMe SSD Drive 512GB        | 5         | 0.71%   |
| Samsung HM321HI 320GB               | 5         | 0.71%   |
| Samsung HM160HI 160GB               | 5         | 0.71%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 0.71%   |
| Kingston SA400S37120G 120GB SSD     | 5         | 0.71%   |
| Hitachi HTS545032B9A300 320GB       | 5         | 0.71%   |
| HGST HTS725050A7E630 500GB          | 5         | 0.71%   |
| Toshiba MQ01ACF050 500GB            | 4         | 0.57%   |
| Toshiba MQ01ABD075 752GB            | 4         | 0.57%   |
| Seagate ST9320423AS 320GB           | 4         | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 4         | 0.57%   |
| Samsung NVMe SSD Drive 256GB        | 4         | 0.57%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 0.57%   |
| Crucial CT240BX500SSD1 240GB        | 4         | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.42%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 3         | 0.42%   |
| WDC WD10JPVX-75JC3T0 1TB            | 3         | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.42%   |
| WDC WD10JPCX-24UE4T0 1TB            | 3         | 0.42%   |
| Unknown MMC Card  128GB             | 3         | 0.42%   |
| Seagate ST9500420AS 500GB           | 3         | 0.42%   |
| Seagate ST9500325AS 500GB           | 3         | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.42%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 0.42%   |
| SanDisk NVMe SSD Drive 256GB        | 3         | 0.42%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.42%   |
| Samsung SSD 850 EVO 500GB           | 3         | 0.42%   |
| LITEON CV8-8E128-HP 128GB SSD       | 3         | 0.42%   |
| Kingston SV300S37A240G 240GB SSD    | 3         | 0.42%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 0.42%   |
| Hitachi HTS545050A7E380 500GB       | 3         | 0.42%   |
| Hitachi HTS543216L9SA00 160GB       | 3         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 97        | 103    | 25.39%  |
| WDC                 | 86        | 91     | 22.51%  |
| Toshiba             | 70        | 79     | 18.32%  |
| Hitachi             | 57        | 59     | 14.92%  |
| HGST                | 35        | 45     | 9.16%   |
| Samsung Electronics | 16        | 17     | 4.19%   |
| Fujitsu             | 14        | 14     | 3.66%   |
| Unknown             | 2         | 2      | 0.52%   |
| IBM/Hitachi         | 2         | 2      | 0.52%   |
| USB                 | 1         | 2      | 0.26%   |
| StoreJet            | 1         | 1      | 0.26%   |
| Apple               | 1         | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 49     | 22.09%  |
| Kingston            | 27        | 29     | 15.7%   |
| Crucial             | 15        | 17     | 8.72%   |
| SanDisk             | 13        | 15     | 7.56%   |
| Micron Technology   | 10        | 11     | 5.81%   |
| WDC                 | 7         | 7      | 4.07%   |
| LITEON              | 7         | 9      | 4.07%   |
| Toshiba             | 5         | 6      | 2.91%   |
| LITEONIT            | 5         | 8      | 2.91%   |
| Intel               | 5         | 5      | 2.91%   |
| SK hynix            | 4         | 4      | 2.33%   |
| SPCC                | 3         | 3      | 1.74%   |
| PNY                 | 3         | 3      | 1.74%   |
| OCZ                 | 3         | 3      | 1.74%   |
| Intenso             | 3         | 3      | 1.74%   |
| A-DATA Technology   | 3         | 3      | 1.74%   |
| Verbatim            | 2         | 2      | 1.16%   |
| Transcend           | 2         | 2      | 1.16%   |
| Patriot             | 2         | 2      | 1.16%   |
| KingDian            | 2         | 2      | 1.16%   |
| JMicron Technology  | 2         | 2      | 1.16%   |
| Team                | 1         | 3      | 0.58%   |
| SUNEAST             | 1         | 1      | 0.58%   |
| StoreJet            | 1         | 1      | 0.58%   |
| SABRENT             | 1         | 1      | 0.58%   |
| NGFF                | 1         | 1      | 0.58%   |
| MidasForce          | 1         | 1      | 0.58%   |
| Lexar               | 1         | 1      | 0.58%   |
| Innodisk            | 1         | 1      | 0.58%   |
| GOODRAM             | 1         | 1      | 0.58%   |
| Dell                | 1         | 1      | 0.58%   |
| BIWIN               | 1         | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 372       | 416    | 55.52%  |
| SSD     | 161       | 198    | 24.03%  |
| NVMe    | 105       | 118    | 15.67%  |
| MMC     | 23        | 24     | 3.43%   |
| Unknown | 9         | 10     | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 500       | 599    | 77.04%  |
| NVMe | 105       | 118    | 16.18%  |
| MMC  | 23        | 24     | 3.54%   |
| SAS  | 21        | 25     | 3.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 405       | 465    | 75.56%  |
| 0.51-1.0   | 116       | 134    | 21.64%  |
| 1.01-2.0   | 12        | 12     | 2.24%   |
| 4.01-10.0  | 2         | 2      | 0.37%   |
| 10.01-20.0 | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 229       | 37.3%   |
| 251-500        | 164       | 26.71%  |
| 51-100         | 69        | 11.24%  |
| 501-1000       | 68        | 11.07%  |
| 21-50          | 35        | 5.7%    |
| 1001-2000      | 25        | 4.07%   |
| 1-20           | 13        | 2.12%   |
| 2001-3000      | 7         | 1.14%   |
| More than 3000 | 4         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 298       | 47.6%   |
| 101-250        | 87        | 13.9%   |
| 21-50          | 81        | 12.94%  |
| 51-100         | 77        | 12.3%   |
| 251-500        | 44        | 7.03%   |
| 501-1000       | 28        | 4.47%   |
| 1001-2000      | 9         | 1.44%   |
| More than 3000 | 1         | 0.16%   |
| 2001-3000      | 1         | 0.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 9.52%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 9.52%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 9.52%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 4.76%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100M 1TB               | 1         | 1      | 4.76%   |
| Toshiba MK3261GSYN 320GB              | 1         | 1      | 4.76%   |
| Toshiba MK3252GSX 320GB               | 1         | 2      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 4.76%   |
| Seagate ST1000LM 035-1RK172 1TB       | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 850 EVO 250GB | 1         | 1      | 4.76%   |
| Samsung Electronics HM320II 320GB     | 1         | 1      | 4.76%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 4.76%   |
| Hitachi HTS541040G9AT00 40GB          | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.76%   |
| HGST HTS541010A7E630 1TB              | 1         | 2      | 4.76%   |
| Crucial CT275MX300SSD1 275GB          | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 7      | 28.57%  |
| Seagate             | 4         | 4      | 19.05%  |
| HGST                | 4         | 5      | 19.05%  |
| WDC                 | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| Crucial             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 7      | 31.58%  |
| Seagate             | 4         | 4      | 21.05%  |
| HGST                | 4         | 5      | 21.05%  |
| WDC                 | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 21     | 90.48%  |
| SSD  | 2         | 2      | 9.52%   |

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
| Detected | 447       | 558    | 71.98%  |
| Works    | 153       | 185    | 24.64%  |
| Malfunc  | 21        | 23     | 3.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 481       | 72.88%  |
| AMD                              | 56        | 8.48%   |
| Samsung Electronics              | 33        | 5%      |
| SanDisk                          | 18        | 2.73%   |
| Toshiba America Info Systems     | 11        | 1.67%   |
| Silicon Integrated Systems [SiS] | 9         | 1.36%   |
| SK hynix                         | 7         | 1.06%   |
| Nvidia                           | 7         | 1.06%   |
| KIOXIA                           | 7         | 1.06%   |
| Micron Technology                | 6         | 0.91%   |
| Kingston Technology Company      | 6         | 0.91%   |
| VIA Technologies                 | 5         | 0.76%   |
| Silicon Motion                   | 5         | 0.76%   |
| Lite-On Technology               | 2         | 0.3%    |
| Lenovo                           | 2         | 0.3%    |
| Solid State Storage Technology   | 1         | 0.15%   |
| Seagate Technology               | 1         | 0.15%   |
| Phison Electronics               | 1         | 0.15%   |
| Apple                            | 1         | 0.15%   |
| ADATA Technology                 | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 50        | 6.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 46        | 6.13%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 41        | 5.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 35        | 4.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 28        | 3.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 28        | 3.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 27        | 3.6%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 26        | 3.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 24        | 3.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 24        | 3.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 21        | 2.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 2.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 17        | 2.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 2.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 16        | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 2%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 14        | 1.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 12        | 1.6%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 12        | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 1.46%   |
| Intel Comet Lake SATA AHCI Controller                                            | 10        | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 10        | 1.33%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 9         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 1.07%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 7         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.8%    |
| Micron NVMe Storage Controller                                                   | 6         | 0.8%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 6         | 0.8%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 5         | 0.67%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 5         | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 5         | 0.67%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 4         | 0.53%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 4         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 432       | 60.42%  |
| IDE  | 144       | 20.14%  |
| NVMe | 106       | 14.83%  |
| RAID | 33        | 4.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 539       | 88.8%   |
| AMD          | 67        | 11.04%  |
| CentaurHauls | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 16        | 2.64%   |
| Intel Atom CPU N270 @ 1.60GHz               | 13        | 2.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 12        | 1.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 9         | 1.48%   |
| Intel Pentium M processor 1.73GHz           | 8         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 7         | 1.15%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 6         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 6         | 0.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 6         | 0.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 6         | 0.99%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 6         | 0.99%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 6         | 0.99%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 6         | 0.99%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 6         | 0.99%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 0.99%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 5         | 0.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 5         | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 5         | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 5         | 0.82%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 5         | 0.82%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 5         | 0.82%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 4         | 0.66%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 4         | 0.66%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 4         | 0.66%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 4         | 0.66%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 4         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 4         | 0.66%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 4         | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 4         | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 0.66%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 4         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 114       | 18.78%  |
| Intel Core i7                  | 110       | 18.12%  |
| Intel Core 2 Duo               | 57        | 9.39%   |
| Intel Core i3                  | 49        | 8.07%   |
| Intel Atom                     | 39        | 6.43%   |
| Intel Celeron                  | 30        | 4.94%   |
| Other                          | 21        | 3.46%   |
| Intel Genuine                  | 21        | 3.46%   |
| Intel Pentium                  | 19        | 3.13%   |
| Intel Pentium Dual-Core        | 18        | 2.97%   |
| Intel Pentium M                | 14        | 2.31%   |
| Intel Celeron M                | 12        | 1.98%   |
| Intel Pentium Dual             | 11        | 1.81%   |
| Intel Core 2                   | 9         | 1.48%   |
| AMD Ryzen 5                    | 9         | 1.48%   |
| AMD A4                         | 8         | 1.32%   |
| Intel Core Duo                 | 5         | 0.82%   |
| AMD Ryzen 7                    | 5         | 0.82%   |
| Intel Core i9                  | 4         | 0.66%   |
| AMD A8                         | 4         | 0.66%   |
| AMD A10                        | 4         | 0.66%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.49%   |
| AMD E1                         | 3         | 0.49%   |
| AMD A6                         | 3         | 0.49%   |
| Intel Pentium Silver           | 2         | 0.33%   |
| Intel Celeron Dual-Core        | 2         | 0.33%   |
| AMD Ryzen 7 PRO                | 2         | 0.33%   |
| AMD E2                         | 2         | 0.33%   |
| AMD E                          | 2         | 0.33%   |
| AMD C-60                       | 2         | 0.33%   |
| AMD Athlon X2                  | 2         | 0.33%   |
| AMD Athlon II                  | 2         | 0.33%   |
| Intel Xeon                     | 1         | 0.16%   |
| Intel Mobile Pentium 4         | 1         | 0.16%   |
| Intel Core m5                  | 1         | 0.16%   |
| Intel Core m3                  | 1         | 0.16%   |
| Intel Core M                   | 1         | 0.16%   |
| Intel Core 2 Extreme           | 1         | 0.16%   |
| CentaurHauls VIA C7            | 1         | 0.16%   |
| AMD V140                       | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 367       | 60.36%  |
| 4      | 130       | 21.38%  |
| 1      | 72        | 11.84%  |
| 6      | 23        | 3.78%   |
| 8      | 11        | 1.81%   |
| 12     | 2         | 0.33%   |
| 14     | 1         | 0.16%   |
| 10     | 1         | 0.16%   |
| 3      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 607       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 353       | 58.06%  |
| 1      | 255       | 41.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 539       | 88.8%   |
| 32-bit         | 68        | 11.2%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 10.15%  |
| 0x1067a    | 46        | 7.53%   |
| 0x206a7    | 32        | 5.24%   |
| 0x306a9    | 31        | 5.07%   |
| 0x806e9    | 28        | 4.58%   |
| 0x6fd      | 25        | 4.09%   |
| 0x20655    | 20        | 3.27%   |
| 0x806ea    | 19        | 3.11%   |
| 0x106c2    | 18        | 2.95%   |
| 0x6e8      | 17        | 2.78%   |
| 0x40651    | 17        | 2.78%   |
| 0x106ca    | 16        | 2.62%   |
| 0x806ec    | 15        | 2.45%   |
| 0x6d8      | 15        | 2.45%   |
| 0x406e3    | 15        | 2.45%   |
| 0x306d4    | 15        | 2.45%   |
| 0x6ec      | 13        | 2.13%   |
| 0x906ea    | 12        | 1.96%   |
| 0x10676    | 12        | 1.96%   |
| 0x506e3    | 11        | 1.8%    |
| 0x30678    | 11        | 1.8%    |
| 0x20652    | 10        | 1.64%   |
| 0x306c3    | 9         | 1.47%   |
| 0xa0652    | 8         | 1.31%   |
| 0x906e9    | 8         | 1.31%   |
| 0x406c3    | 8         | 1.31%   |
| 0x6f6      | 7         | 1.15%   |
| 0x406c4    | 7         | 1.15%   |
| 0x05000119 | 7         | 1.15%   |
| 0x806c1    | 6         | 0.98%   |
| 0x0700010f | 6         | 0.98%   |
| 0x806eb    | 5         | 0.82%   |
| 0x10661    | 5         | 0.82%   |
| 0x07030105 | 5         | 0.82%   |
| 0x706e5    | 4         | 0.65%   |
| 0x6fb      | 4         | 0.65%   |
| 0x010000c8 | 4         | 0.65%   |
| 0x906a3    | 3         | 0.49%   |
| 0x08600106 | 3         | 0.49%   |
| 0x08108109 | 3         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 99        | 16.31%  |
| Penryn           | 61        | 10.05%  |
| P6               | 48        | 7.91%   |
| Core             | 46        | 7.58%   |
| SandyBridge      | 37        | 6.1%    |
| IvyBridge        | 36        | 5.93%   |
| Bonnell          | 36        | 5.93%   |
| Westmere         | 31        | 5.11%   |
| Skylake          | 31        | 5.11%   |
| Silvermont       | 28        | 4.61%   |
| Haswell          | 28        | 4.61%   |
| Broadwell        | 18        | 2.97%   |
| CometLake        | 10        | 1.65%   |
| Excavator        | 9         | 1.48%   |
| TigerLake        | 7         | 1.15%   |
| Bobcat           | 7         | 1.15%   |
| Zen+             | 6         | 0.99%   |
| K8 & K10 hybrid  | 6         | 0.99%   |
| Jaguar           | 6         | 0.99%   |
| IceLake          | 6         | 0.99%   |
| Unknown          | 6         | 0.99%   |
| Puma             | 5         | 0.82%   |
| K8 Hammer        | 5         | 0.82%   |
| Zen 2            | 4         | 0.66%   |
| K10              | 4         | 0.66%   |
| Goldmont plus    | 4         | 0.66%   |
| Alderlake Hybrid | 4         | 0.66%   |
| Zen 3            | 3         | 0.49%   |
| Zen              | 3         | 0.49%   |
| Piledriver       | 3         | 0.49%   |
| Steamroller      | 2         | 0.33%   |
| Nehalem          | 2         | 0.33%   |
| K10 Llano        | 2         | 0.33%   |
| Goldmont         | 2         | 0.33%   |
| Tremont          | 1         | 0.16%   |
| NetBurst         | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 471       | 64.97%  |
| Nvidia                           | 130       | 17.93%  |
| AMD                              | 110       | 15.17%  |
| Silicon Integrated Systems [SiS] | 9         | 1.24%   |
| VIA Technologies                 | 5         | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 42        | 5.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 42        | 5.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 34        | 4.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 4%      |
| Intel HD Graphics 620                                                                    | 28        | 3.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 26        | 3.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 3.13%   |
| Intel UHD Graphics 620                                                                   | 23        | 2.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 2%      |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 16        | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 2%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 16        | 2%      |
| Intel HD Graphics 5500                                                                   | 15        | 1.88%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 14        | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.63%   |
| Intel HD Graphics 530                                                                    | 12        | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.25%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1%      |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 7         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.88%   |
| Intel HD Graphics 630                                                                    | 7         | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 0.75%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 5         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 0.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.5%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 354       | 58.32%  |
| Intel + Nvidia | 92        | 15.16%  |
| 1 x AMD        | 75        | 12.36%  |
| 1 x Nvidia     | 33        | 5.44%   |
| Intel + AMD    | 24        | 3.95%   |
| 2 x AMD        | 9         | 1.48%   |
| 1 x SiS        | 9         | 1.48%   |
| 1 x VIA        | 5         | 0.82%   |
| 2 x Nvidia     | 3         | 0.49%   |
| AMD + Nvidia   | 2         | 0.33%   |
| Other          | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 516       | 84.87%  |
| Proprietary | 60        | 9.87%   |
| Unknown     | 32        | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 199       | 32.52%  |
| 0.01-0.5   | 163       | 26.63%  |
| 1.01-2.0   | 146       | 23.86%  |
| 3.01-4.0   | 68        | 11.11%  |
| 0.51-1.0   | 29        | 4.74%   |
| 5.01-6.0   | 4         | 0.65%   |
| 7.01-8.0   | 2         | 0.33%   |
| 2.01-3.0   | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 122       | 19.18%  |
| LG Display              | 90        | 14.15%  |
| Samsung Electronics     | 71        | 11.16%  |
| Chimei Innolux          | 62        | 9.75%   |
| BOE                     | 58        | 9.12%   |
| Chi Mei Optoelectronics | 27        | 4.25%   |
| Sharp                   | 23        | 3.62%   |
| Lenovo                  | 23        | 3.62%   |
| LG Philips              | 18        | 2.83%   |
| Apple                   | 13        | 2.04%   |
| Goldstar                | 12        | 1.89%   |
| HannStar                | 11        | 1.73%   |
| Dell                    | 11        | 1.73%   |
| Acer                    | 9         | 1.42%   |
| InnoLux Display         | 7         | 1.1%    |
| Ancor Communications    | 7         | 1.1%    |
| InfoVision              | 6         | 0.94%   |
| Hewlett-Packard         | 6         | 0.94%   |
| Seiko/Epson             | 5         | 0.79%   |
| Quanta Display          | 5         | 0.79%   |
| CPT                     | 5         | 0.79%   |
| Philips                 | 4         | 0.63%   |
| Vestel Elektronik       | 3         | 0.47%   |
| AOC                     | 3         | 0.47%   |
| ViewSonic               | 2         | 0.31%   |
| Unknown                 | 2         | 0.31%   |
| PANDA                   | 2         | 0.31%   |
| Panasonic               | 2         | 0.31%   |
| KDC                     | 2         | 0.31%   |
| Iiyama                  | 2         | 0.31%   |
| IBM                     | 2         | 0.31%   |
| CSO                     | 2         | 0.31%   |
| BenQ                    | 2         | 0.31%   |
| ___                     | 1         | 0.16%   |
| Westinghouse            | 1         | 0.16%   |
| Vizio                   | 1         | 0.16%   |
| Toshiba                 | 1         | 0.16%   |
| TCL                     | 1         | 0.16%   |
| Sony                    | 1         | 0.16%   |
| Sceptre                 | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 9         | 1.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.77%   |
| Seiko/Epson LCD Monitor 1366x768                                         | 4         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 4         | 0.62%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.62%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.46%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO0209 1024x600 195x113mm 8.9-inch  | 3         | 0.46%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.46%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 2         | 0.31%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                  | 2         | 0.31%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch                   | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SDC374A 3200x1800 293x165mm 13.2-inch    | 2         | 0.31%   |
| Quanta Display LCD Monitor QDS0027 1280x800 331x207mm 15.4-inch          | 2         | 0.31%   |
| LG Philips LCD Monitor LPLA500 1280x800 304x190mm 14.1-inch              | 2         | 0.31%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 2         | 0.31%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 2         | 0.31%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 0.31%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.31%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 201       | 32.68%  |
| 1920x1080 (FHD)    | 162       | 26.34%  |
| 1280x800 (WXGA)    | 60        | 9.76%   |
| 1600x900 (HD+)     | 29        | 4.72%   |
| 1024x600           | 28        | 4.55%   |
| 1440x900 (WXGA+)   | 25        | 4.07%   |
| 3840x2160 (4K)     | 24        | 3.9%    |
| 1680x1050 (WSXGA+) | 10        | 1.63%   |
| 1024x768 (XGA)     | 10        | 1.63%   |
| 1920x1200 (WUXGA)  | 8         | 1.3%    |
| 3200x1800 (QHD+)   | 6         | 0.98%   |
| 2560x1440 (QHD)    | 6         | 0.98%   |
| 1360x768           | 6         | 0.98%   |
| Unknown            | 6         | 0.98%   |
| 2160x1440          | 4         | 0.65%   |
| 1280x1024 (SXGA)   | 4         | 0.65%   |
| 3440x1440          | 3         | 0.49%   |
| 2560x1600          | 3         | 0.49%   |
| 3840x2400          | 2         | 0.33%   |
| 2880x1800          | 2         | 0.33%   |
| 2560x1080          | 2         | 0.33%   |
| 1920x540           | 2         | 0.33%   |
| 1680x945           | 2         | 0.33%   |
| 1280x720 (HD)      | 2         | 0.33%   |
| 3456x2160          | 1         | 0.16%   |
| 3360x1080          | 1         | 0.16%   |
| 3286x1080          | 1         | 0.16%   |
| 3000x2000          | 1         | 0.16%   |
| 2736x1824          | 1         | 0.16%   |
| 2732x768           | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1024x576           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 253       | 39.91%  |
| 14      | 91        | 14.35%  |
| 13      | 79        | 12.46%  |
| 17      | 39        | 6.15%   |
| 10      | 32        | 5.05%   |
| Unknown | 18        | 2.84%   |
| 27      | 14        | 2.21%   |
| 24      | 13        | 2.05%   |
| 12      | 12        | 1.89%   |
| 23      | 11        | 1.74%   |
| 11      | 11        | 1.74%   |
| 21      | 9         | 1.42%   |
| 31      | 6         | 0.95%   |
| 34      | 5         | 0.79%   |
| 22      | 5         | 0.79%   |
| 16      | 5         | 0.79%   |
| 84      | 4         | 0.63%   |
| 20      | 3         | 0.47%   |
| 19      | 3         | 0.47%   |
| 18      | 3         | 0.47%   |
| 8       | 3         | 0.47%   |
| 72      | 2         | 0.32%   |
| 40      | 2         | 0.32%   |
| 28      | 2         | 0.32%   |
| 26      | 2         | 0.32%   |
| 60      | 1         | 0.16%   |
| 54      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 42      | 1         | 0.16%   |
| 32      | 1         | 0.16%   |
| 30      | 1         | 0.16%   |
| 25      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 370       | 58.82%  |
| 201-300     | 101       | 16.06%  |
| 351-400     | 50        | 7.95%   |
| 501-600     | 39        | 6.2%    |
| 401-500     | 21        | 3.34%   |
| Unknown     | 18        | 2.86%   |
| 601-700     | 9         | 1.43%   |
| 701-800     | 6         | 0.95%   |
| 1501-2000   | 6         | 0.95%   |
| 101-200     | 3         | 0.48%   |
| 1001-1500   | 3         | 0.48%   |
| 801-900     | 2         | 0.32%   |
| 901-1000    | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 424       | 73.48%  |
| 16/10   | 111       | 19.24%  |
| 4/3     | 14        | 2.43%   |
| Unknown | 14        | 2.43%   |
| 3/2     | 6         | 1.04%   |
| 21/9    | 5         | 0.87%   |
| 5/4     | 3         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 255       | 40.35%  |
| 81-90          | 131       | 20.73%  |
| 71-80          | 34        | 5.38%   |
| 201-250        | 33        | 5.22%   |
| 41-50          | 32        | 5.06%   |
| 121-130        | 26        | 4.11%   |
| Unknown        | 18        | 2.85%   |
| 301-350        | 15        | 2.37%   |
| 351-500        | 12        | 1.9%    |
| 61-70          | 11        | 1.74%   |
| 51-60          | 11        | 1.74%   |
| 131-140        | 11        | 1.74%   |
| More than 1000 | 9         | 1.42%   |
| 151-200        | 7         | 1.11%   |
| 251-300        | 6         | 0.95%   |
| 91-100         | 6         | 0.95%   |
| 141-150        | 5         | 0.79%   |
| 501-1000       | 4         | 0.63%   |
| 1-40           | 3         | 0.47%   |
| 111-120        | 3         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 242       | 38.84%  |
| 121-160       | 169       | 27.13%  |
| 51-100        | 132       | 21.19%  |
| 161-240       | 29        | 4.65%   |
| More than 240 | 22        | 3.53%   |
| Unknown       | 18        | 2.89%   |
| 1-50          | 11        | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 499       | 81.01%  |
| 2     | 75        | 12.18%  |
| 0     | 32        | 5.19%   |
| 3     | 9         | 1.46%   |
| 6     | 1         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 291       | 29.25%  |
| Intel                             | 282       | 28.34%  |
| Qualcomm Atheros                  | 186       | 18.69%  |
| Broadcom                          | 89        | 8.94%   |
| Marvell Technology Group          | 29        | 2.91%   |
| Broadcom Limited                  | 28        | 2.81%   |
| Ralink                            | 16        | 1.61%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.9%    |
| TP-Link                           | 7         | 0.7%    |
| Ericsson Business Mobile Networks | 6         | 0.6%    |
| Nvidia                            | 5         | 0.5%    |
| VIA Technologies                  | 4         | 0.4%    |
| Xiaomi                            | 3         | 0.3%    |
| Sierra Wireless                   | 3         | 0.3%    |
| MediaTek                          | 3         | 0.3%    |
| JMicron Technology                | 3         | 0.3%    |
| Dell                              | 3         | 0.3%    |
| Samsung Electronics               | 2         | 0.2%    |
| Ralink Technology                 | 2         | 0.2%    |
| NetGear                           | 2         | 0.2%    |
| Huawei Technologies               | 2         | 0.2%    |
| Fibocom                           | 2         | 0.2%    |
| ASIX Electronics                  | 2         | 0.2%    |
| ZyDAS                             | 1         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.1%    |
| STMicroelectronics                | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| Qualcomm                          | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Lenovo                            | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Hewlett-Packard                   | 1         | 0.1%    |
| Espressif                         | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |
| DisplayLink                       | 1         | 0.1%    |
| Attansic Technology               | 1         | 0.1%    |
| Arduino SA                        | 1         | 0.1%    |
| Archos                            | 1         | 0.1%    |
| AMD                               | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 149       | 12.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 85        | 7.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 2.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 29        | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 2.33%   |
| Intel Wireless 8265 / 8275                                              | 27        | 2.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 16        | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 1.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 14        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 13        | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 13        | 1.08%   |
| Intel Wireless 7265                                                     | 13        | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 1.08%   |
| Intel Centrino Advanced-N 6200                                          | 13        | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                | 13        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 1%      |
| Intel Wireless 8260                                                     | 12        | 1%      |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                | 11        | 0.92%   |
| Intel Wireless 3165                                                     | 10        | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                   | 10        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 0.83%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 10        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.75%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 9         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.67%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 8         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 0.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 7         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.58%   |
| Intel Wireless 7260                                                     | 7         | 0.58%   |
| Intel Ultimate N WiFi Link 5300                                         | 7         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 265       | 43.09%  |
| Qualcomm Atheros                | 158       | 25.69%  |
| Realtek Semiconductor           | 77        | 12.52%  |
| Broadcom                        | 57        | 9.27%   |
| Broadcom Limited                | 19        | 3.09%   |
| Ralink                          | 16        | 2.6%    |
| TP-Link                         | 6         | 0.98%   |
| Sierra Wireless                 | 3         | 0.49%   |
| MediaTek                        | 3         | 0.49%   |
| Ralink Technology               | 2         | 0.33%   |
| NetGear                         | 2         | 0.33%   |
| Fibocom                         | 2         | 0.33%   |
| Dell                            | 2         | 0.33%   |
| ZyDAS                           | 1         | 0.16%   |
| Qualcomm Atheros Communications | 1         | 0.16%   |
| Edimax Technology               | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 5.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 29        | 4.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 4.52%   |
| Intel Wireless 8265 / 8275                                              | 27        | 4.36%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 4.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 2.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 2.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 2.26%   |
| Intel Wireless 7265                                                     | 13        | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 2.1%    |
| Intel Centrino Advanced-N 6200                                          | 13        | 2.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 1.94%   |
| Intel Wireless 8260                                                     | 12        | 1.94%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 1.78%   |
| Intel Wireless 3165                                                     | 10        | 1.62%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.62%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.62%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 10        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.29%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 8         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.29%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 1.29%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 1.13%   |
| Intel Wireless 7260                                                     | 7         | 1.13%   |
| Intel Ultimate N WiFi Link 5300                                         | 7         | 1.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 1.13%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 7         | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 0.97%   |
| Intel Wireless 3160                                                     | 6         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.81%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 269       | 48.73%  |
| Intel                            | 116       | 21.01%  |
| Qualcomm Atheros                 | 50        | 9.06%   |
| Broadcom                         | 41        | 7.43%   |
| Marvell Technology Group         | 29        | 5.25%   |
| Silicon Integrated Systems [SiS] | 9         | 1.63%   |
| Broadcom Limited                 | 9         | 1.63%   |
| Nvidia                           | 5         | 0.91%   |
| VIA Technologies                 | 4         | 0.72%   |
| Xiaomi                           | 3         | 0.54%   |
| JMicron Technology               | 3         | 0.54%   |
| Huawei Technologies              | 2         | 0.36%   |
| ASIX Electronics                 | 2         | 0.36%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.18%   |
| TP-Link                          | 1         | 0.18%   |
| Samsung Electronics              | 1         | 0.18%   |
| Qualcomm                         | 1         | 0.18%   |
| Motorola PCS                     | 1         | 0.18%   |
| Lenovo                           | 1         | 0.18%   |
| ICS Advent                       | 1         | 0.18%   |
| DisplayLink                      | 1         | 0.18%   |
| Attansic Technology              | 1         | 0.18%   |
| Archos                           | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 149       | 26.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 85        | 15.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 2.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 13        | 2.35%   |
| Intel 82567LM Gigabit Network Connection                          | 13        | 2.35%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 1.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 7         | 1.26%   |
| Intel PRO/100 VE Network Connection                               | 7         | 1.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 1.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 1.08%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 6         | 1.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.9%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.9%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 5         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.9%    |
| Intel 82577LC Gigabit Network Connection                          | 5         | 0.9%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 5         | 0.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4         | 0.72%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 4         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.54%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 3         | 0.54%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 593       | 51.12%  |
| Ethernet | 539       | 46.47%  |
| Modem    | 28        | 2.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 487       | 76.09%  |
| Ethernet | 153       | 23.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 490       | 80.72%  |
| 1     | 102       | 16.8%   |
| 0     | 8         | 1.32%   |
| 3     | 4         | 0.66%   |
| 4     | 2         | 0.33%   |
| 7     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 557       | 90.86%  |
| Yes  | 56        | 9.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 149       | 41.39%  |
| Qualcomm Atheros Communications | 43        | 11.94%  |
| Broadcom                        | 33        | 9.17%   |
| Realtek Semiconductor           | 27        | 7.5%    |
| Foxconn / Hon Hai               | 16        | 4.44%   |
| IMC Networks                    | 15        | 4.17%   |
| Apple                           | 11        | 3.06%   |
| Lite-On Technology              | 10        | 2.78%   |
| Hewlett-Packard                 | 9         | 2.5%    |
| Cambridge Silicon Radio         | 8         | 2.22%   |
| Ralink                          | 7         | 1.94%   |
| Toshiba                         | 6         | 1.67%   |
| Dell                            | 6         | 1.67%   |
| ASUSTek Computer                | 5         | 1.39%   |
| Alps Electric                   | 3         | 0.83%   |
| Taiyo Yuden                     | 2         | 0.56%   |
| Realtek                         | 2         | 0.56%   |
| Foxconn International           | 2         | 0.56%   |
| Smart Modular Technologies      | 1         | 0.28%   |
| Qcom                            | 1         | 0.28%   |
| Micro Star International        | 1         | 0.28%   |
| MediaTek                        | 1         | 0.28%   |
| Chicony Electronics             | 1         | 0.28%   |
| Askey Computer                  | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 74        | 20.56%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 6.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 6.11%   |
| Intel AX201 Bluetooth                               | 20        | 5.56%   |
| Realtek Bluetooth Radio                             | 14        | 3.89%   |
| Intel AX200 Bluetooth                               | 12        | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.94%   |
| Ralink RT3290 Bluetooth                             | 7         | 1.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.94%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 6         | 1.67%   |
| Intel Bluetooth Device                              | 6         | 1.67%   |
| Apple Bluetooth HCI                                 | 6         | 1.67%   |
| IMC Networks Bluetooth Device                       | 5         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 5         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.11%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.11%   |
| Apple Bluetooth Host Controller                     | 4         | 1.11%   |
| Toshiba Bluetooth Device                            | 3         | 0.83%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 3         | 0.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.83%   |
| Broadcom BCM2045 Bluetooth                          | 3         | 0.83%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.56%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.56%   |
| Realtek Bluetooth Radio                             | 2         | 0.56%   |
| Intel AX210 Bluetooth                               | 2         | 0.56%   |
| IMC Networks Bluetooth                              | 2         | 0.56%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.56%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 519       | 76.1%   |
| AMD                              | 76        | 11.14%  |
| Nvidia                           | 51        | 7.48%   |
| Silicon Integrated Systems [SiS] | 9         | 1.32%   |
| VIA Technologies                 | 5         | 0.73%   |
| Plantronics                      | 4         | 0.59%   |
| C-Media Electronics              | 3         | 0.44%   |
| Realtek Semiconductor            | 2         | 0.29%   |
| JMTek                            | 2         | 0.29%   |
| GN Netcom                        | 2         | 0.29%   |
| Yamaha                           | 1         | 0.15%   |
| Tenx Technology                  | 1         | 0.15%   |
| Samson Technologies              | 1         | 0.15%   |
| Pioneer DJ                       | 1         | 0.15%   |
| Logitech                         | 1         | 0.15%   |
| Blue Microphones                 | 1         | 0.15%   |
| BEHRINGER International          | 1         | 0.15%   |
| Alesis                           | 1         | 0.15%   |
| AKAI Professional M.I.           | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 72        | 9.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 70        | 8.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 56        | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 42        | 5.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 33        | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 31        | 3.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 28        | 3.57%   |
| AMD FCH Azalia Controller                                                                         | 22        | 2.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 2.3%    |
| Intel Broadwell-U Audio Controller                                                                | 18        | 2.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 1.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.15%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 1.15%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 9         | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 1.15%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.15%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.02%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 7         | 0.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 0.89%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 5         | 0.64%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.51%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 75        | 25.68%  |
| SK hynix            | 67        | 22.95%  |
| Micron Technology   | 33        | 11.3%   |
| Unknown             | 26        | 8.9%    |
| Kingston            | 19        | 6.51%   |
| Ramaxel Technology  | 12        | 4.11%   |
| Smart               | 10        | 3.42%   |
| Crucial             | 8         | 2.74%   |
| Corsair             | 8         | 2.74%   |
| Elpida              | 7         | 2.4%    |
| Transcend           | 4         | 1.37%   |
| Nanya Technology    | 4         | 1.37%   |
| A-DATA Technology   | 4         | 1.37%   |
| Unknown (ABCD)      | 2         | 0.68%   |
| Walton Chaintech    | 1         | 0.34%   |
| Unknown (89F7)      | 1         | 0.34%   |
| Silicon Power       | 1         | 0.34%   |
| SHARETRONIC         | 1         | 0.34%   |
| PUSKILL             | 1         | 0.34%   |
| Patriot             | 1         | 0.34%   |
| Netlist             | 1         | 0.34%   |
| High Bridge         | 1         | 0.34%   |
| Goldkey             | 1         | 0.34%   |
| G.Skill             | 1         | 0.34%   |
| ASint Technology    | 1         | 0.34%   |
| Apacer              | 1         | 0.34%   |
| Unknown             | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 1.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.29%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 1.29%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 1.29%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.29%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 1.29%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.97%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 3         | 0.97%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.97%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 3         | 0.97%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.97%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 2         | 0.65%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 2         | 0.65%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 2         | 0.65%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1334MT/s        | 2         | 0.65%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 2         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.65%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.65%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.65%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.65%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.65%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.65%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.65%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.65%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 101       | 40.56%  |
| DDR3    | 86        | 34.54%  |
| DDR2    | 23        | 9.24%   |
| LPDDR3  | 13        | 5.22%   |
| LPDDR4  | 11        | 4.42%   |
| SDRAM   | 7         | 2.81%   |
| DDR     | 3         | 1.2%    |
| DDR5    | 2         | 0.8%    |
| LPDDR5  | 1         | 0.4%    |
| DRAM    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 220       | 87.3%   |
| Row Of Chips | 27        | 10.71%  |
| Chip         | 3         | 1.19%   |
| DIMM         | 2         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 96        | 34.91%  |
| 4096  | 75        | 27.27%  |
| 16384 | 42        | 15.27%  |
| 2048  | 39        | 14.18%  |
| 1024  | 15        | 5.45%   |
| 32768 | 4         | 1.45%   |
| 512   | 4         | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 63        | 23.08%  |
| 2667    | 56        | 20.51%  |
| 3200    | 32        | 11.72%  |
| 2133    | 26        | 9.52%   |
| 1334    | 18        | 6.59%   |
| 2400    | 13        | 4.76%   |
| 667     | 13        | 4.76%   |
| Unknown | 12        | 4.4%    |
| 1333    | 8         | 2.93%   |
| 800     | 5         | 1.83%   |
| 1067    | 4         | 1.47%   |
| 4267    | 3         | 1.1%    |
| 1867    | 3         | 1.1%    |
| 8400    | 2         | 0.73%   |
| 4800    | 2         | 0.73%   |
| 4199    | 2         | 0.73%   |
| 3266    | 2         | 0.73%   |
| 533     | 2         | 0.73%   |
| 6400    | 1         | 0.37%   |
| 4266    | 1         | 0.37%   |
| 2048    | 1         | 0.37%   |
| 1866    | 1         | 0.37%   |
| 1639    | 1         | 0.37%   |
| 1066    | 1         | 0.37%   |
| 975     | 1         | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 55.56%  |
| Canon               | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| Brother Industries  | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-1640 Series Laser Printer | 1         | 11.11%  |
| HP OfficeJet 3830 series             | 1         | 11.11%  |
| HP LaserJet 1018                     | 1         | 11.11%  |
| HP EWS UPD                           | 1         | 11.11%  |
| HP DeskJet 930c                      | 1         | 11.11%  |
| HP DeskJet 2700 series               | 1         | 11.11%  |
| Canon PIXMA MX370 Series             | 1         | 11.11%  |
| Canon PIXMA MP250                    | 1         | 11.11%  |
| Brother MFC-L2710DW series           | 1         | 11.11%  |

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
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 109       | 22.85%  |
| Realtek Semiconductor                  | 53        | 11.11%  |
| Microdia                               | 49        | 10.27%  |
| IMC Networks                           | 38        | 7.97%   |
| Suyin                                  | 33        | 6.92%   |
| Sunplus Innovation Technology          | 29        | 6.08%   |
| Bison Electronics                      | 21        | 4.4%    |
| Quanta                                 | 18        | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 3.56%   |
| Apple                                  | 14        | 2.94%   |
| Acer                                   | 14        | 2.94%   |
| Lite-On Technology                     | 11        | 2.31%   |
| Syntek                                 | 10        | 2.1%    |
| Lenovo                                 | 10        | 2.1%    |
| Silicon Motion                         | 9         | 1.89%   |
| Importek                               | 6         | 1.26%   |
| Alcor Micro                            | 6         | 1.26%   |
| Luxvisions Innotech Limited            | 4         | 0.84%   |
| Logitech                               | 4         | 0.84%   |
| Z-Star Microelectronics                | 2         | 0.42%   |
| Samsung Electronics                    | 2         | 0.42%   |
| Ricoh                                  | 2         | 0.42%   |
| Primax Electronics                     | 2         | 0.42%   |
| Intel                                  | 2         | 0.42%   |
| eMPIA Technology                       | 2         | 0.42%   |
| ALi                                    | 2         | 0.42%   |
| USB Camera CS                          | 1         | 0.21%   |
| SunplusIT                              | 1         | 0.21%   |
| Pixart Imaging                         | 1         | 0.21%   |
| OmniVision Technologies                | 1         | 0.21%   |
| Microsoft                              | 1         | 0.21%   |
| icSpring                               | 1         | 0.21%   |
| DigiTech                               | 1         | 0.21%   |
| Creative Technology                    | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 21        | 4.4%    |
| Microdia Integrated_Webcam_HD            | 20        | 4.19%   |
| Chicony Integrated Camera                | 10        | 2.1%    |
| IMC Networks Integrated Camera           | 9         | 1.89%   |
| Chicony HP HD Camera                     | 9         | 1.89%   |
| Sunplus Integrated_Webcam_HD             | 8         | 1.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 6         | 1.26%   |
| Lenovo Integrated Webcam [R5U877]        | 6         | 1.26%   |
| Sunplus Asus Webcam                      | 5         | 1.05%   |
| Realtek Integrated Webcam HD             | 5         | 1.05%   |
| Realtek Integrated Webcam                | 5         | 1.05%   |
| Lite-On Integrated Camera                | 5         | 1.05%   |
| Chicony USB 2.0 Camera                   | 5         | 1.05%   |
| Chicony Lenovo EasyCamera                | 5         | 1.05%   |
| Chicony Camera                           | 5         | 1.05%   |
| Bison Lenovo Integrated Webcam           | 5         | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 5         | 1.05%   |
| Sunplus HD WebCam                        | 4         | 0.84%   |
| IMC Networks USB2.0 HD UVC WebCam        | 4         | 0.84%   |
| IMC Networks USB 2.0 Camera              | 4         | 0.84%   |
| IMC Networks Lenovo EasyCamera           | 4         | 0.84%   |
| Chicony USB2.0 VGA UVC WebCam            | 4         | 0.84%   |
| Chicony FJ Camera                        | 4         | 0.84%   |
| Syntek Lenovo EasyCamera                 | 3         | 0.63%   |
| Syntek Integrated Camera                 | 3         | 0.63%   |
| Suyin Integrated_Webcam_HD               | 3         | 0.63%   |
| Suyin HP Truevision HD                   | 3         | 0.63%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 3         | 0.63%   |
| Suyin Acer CrystalEye Webcam             | 3         | 0.63%   |
| Sunplus Laptop Integrated WebCam HD      | 3         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam             | 3         | 0.63%   |
| Realtek USB Camera                       | 3         | 0.63%   |
| Quanta Laptop_Integrated_Webcam_2HDM     | 3         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD     | 3         | 0.63%   |
| Microdia Integrated Webcam HD            | 3         | 0.63%   |
| Lite-On HP HD Camera                     | 3         | 0.63%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 0.63%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 0.63%   |
| Chicony Integrated HP HD Webcam          | 3         | 0.63%   |
| Chicony HP Truevision HD                 | 3         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 49        | 44.14%  |
| Synaptics                          | 17        | 15.32%  |
| AuthenTec                          | 16        | 14.41%  |
| Upek                               | 9         | 8.11%   |
| Shenzhen Goodix Technology         | 9         | 8.11%   |
| STMicroelectronics                 | 5         | 4.5%    |
| LighTuning Technology              | 3         | 2.7%    |
| Elan Microelectronics              | 2         | 1.8%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 9.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 7.21%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 6.31%   |
| AuthenTec AES2810                                                          | 6         | 5.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 4.5%    |
| STMicroelectronics Fingerprint Reader                                      | 5         | 4.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 3.6%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 3.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 3.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.6%    |
| Shenzhen Goodix FingerPrint                                                | 4         | 3.6%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.7%    |
| Validity Sensors VFS491                                                    | 3         | 2.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.7%    |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 2.7%    |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.8%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.8%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.8%    |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.8%    |
| Elan ELAN:Fingerprint                                                      | 2         | 1.8%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.8%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.8%    |
| AuthenTec AES1600                                                          | 2         | 1.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.9%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.9%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.9%    |
| Synaptics WBDI                                                             | 1         | 0.9%    |
| Synaptics  WBDI                                                            | 1         | 0.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.9%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.9%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 18        | 45%     |
| O2 Micro         | 9         | 22.5%   |
| Alcor Micro      | 7         | 17.5%   |
| Lenovo           | 3         | 7.5%    |
| SCM Microsystems | 2         | 5%      |
| Yubico.com       | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 17.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 15%     |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 15%     |
| Broadcom 5880                                                                | 5         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 10%     |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 7.5%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 7.5%    |
| Broadcom 58200                                                               | 3         | 7.5%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.5%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 2.5%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 364       | 59.67%  |
| 1     | 185       | 30.33%  |
| 2     | 48        | 7.87%   |
| 3     | 6         | 0.98%   |
| 4     | 3         | 0.49%   |
| 5     | 2         | 0.33%   |
| 7     | 1         | 0.16%   |
| 6     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 110       | 33.33%  |
| Graphics card            | 79        | 23.94%  |
| Chipcard                 | 39        | 11.82%  |
| Net/wireless             | 33        | 10%     |
| Communication controller | 15        | 4.55%   |
| Modem                    | 14        | 4.24%   |
| Storage                  | 11        | 3.33%   |
| Bluetooth                | 9         | 2.73%   |
| Sound                    | 7         | 2.12%   |
| Multimedia controller    | 5         | 1.52%   |
| Camera                   | 5         | 1.52%   |
| Flash memory             | 2         | 0.61%   |
| Card reader              | 1         | 0.3%    |

