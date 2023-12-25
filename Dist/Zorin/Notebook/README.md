Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 4945

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6430              | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| HP            | Notebook                    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| Dell          | Latitude 5300               | [68336d8bc1](https://linux-hardware.org/?probe=68336d8bc1) | Dec 24, 2023 |
| Teclast       | F6 Plus                     | [a8fee53f37](https://linux-hardware.org/?probe=a8fee53f37) | Dec 24, 2023 |
| Acer          | Nitro AN517-55              | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| HP            | Victus by 15.6 inch Gami... | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| Unknown       | W1415A                      | [f1fbd72c23](https://linux-hardware.org/?probe=f1fbd72c23) | Dec 23, 2023 |
| Sony          | VPCF215FX                   | [1a79c8b60f](https://linux-hardware.org/?probe=1a79c8b60f) | Dec 23, 2023 |
| Apple         | MacBookPro7,1               | [0f291ca562](https://linux-hardware.org/?probe=0f291ca562) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| HP            | EliteBook 745 G6            | [9bf64ae4b7](https://linux-hardware.org/?probe=9bf64ae4b7) | Dec 23, 2023 |
| Medion        | X682X                       | [c0deb0e748](https://linux-hardware.org/?probe=c0deb0e748) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [ae01ab2ebe](https://linux-hardware.org/?probe=ae01ab2ebe) | Dec 22, 2023 |
| VTEX          | NOTEBOOK                    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Lenovo        | ThinkPad X131e 33691K7      | [360dc0f244](https://linux-hardware.org/?probe=360dc0f244) | Dec 21, 2023 |
| Dell          | Latitude 5440               | [bd5e743ebb](https://linux-hardware.org/?probe=bd5e743ebb) | Dec 21, 2023 |
| Dell          | Latitude E7270              | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| Dell          | Inspiron 15-3567            | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| HP            | 1000                        | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [50a3c349a0](https://linux-hardware.org/?probe=50a3c349a0) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [f79ed192ac](https://linux-hardware.org/?probe=f79ed192ac) | Dec 21, 2023 |
| Apple         | MacBookPro14,1              | [e221a6befb](https://linux-hardware.org/?probe=e221a6befb) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | [13432c28a6](https://linux-hardware.org/?probe=13432c28a6) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | [0eb55bee7d](https://linux-hardware.org/?probe=0eb55bee7d) | Dec 20, 2023 |
| Toshiba       | Satellite C850              | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [2dcde776ad](https://linux-hardware.org/?probe=2dcde776ad) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| Framework     | Laptop                      | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| HP            | ProBook 650 G1              | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Google        | Phaser360                   | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Medion        | E6246 MD63200               | [eda979df79](https://linux-hardware.org/?probe=eda979df79) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| HP            | ZBook 14u G6                | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Sony          | VGN-FW455J                  | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| Lenovo        | Y50-70 20378                | [07c7da687a](https://linux-hardware.org/?probe=07c7da687a) | Dec 17, 2023 |
| Lenovo        | Y50-70 20378                | [e6ad27a4dd](https://linux-hardware.org/?probe=e6ad27a4dd) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| Irbis         | NB12                        | [f6eb11e455](https://linux-hardware.org/?probe=f6eb11e455) | Dec 17, 2023 |
| Google        | Phaser360                   | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| HP            | Notebook                    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| HP            | 15                          | [b1de66d4ed](https://linux-hardware.org/?probe=b1de66d4ed) | Dec 16, 2023 |
| HP            | Notebook                    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X553MA                      | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Medion        | P7624                       | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Dell          | Inspiron 15 5510            | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| HP            | Notebook                    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| Dell          | Inspiron 3501               | [67a35f1dd7](https://linux-hardware.org/?probe=67a35f1dd7) | Dec 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| Apple         | MacBookPro8,3               | [08a4bea1d7](https://linux-hardware.org/?probe=08a4bea1d7) | Dec 09, 2023 |
| ASUSTek       | X550VC                      | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| Acer          | AOD257                      | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| Acer          | AOD257                      | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [45c2afd3f1](https://linux-hardware.org/?probe=45c2afd3f1) | Dec 08, 2023 |
| Dell          | Latitude E5470              | [cea78b64d4](https://linux-hardware.org/?probe=cea78b64d4) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| Dell          | Latitude 7490               | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| HP            | 255 G6 Notebook PC          | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| HP            | Pavilion dv7                | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| HP            | Pavilion dv5                | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| Dell          | XPS 13 9360                 | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| HP            | 15                          | [7bd98a81f6](https://linux-hardware.org/?probe=7bd98a81f6) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| AMI           | AMD                         | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| Medion        | Erazer P7643 MD60133        | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | 15                          | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| HP            | 15                          | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| Dell          | XPS 15 9550                 | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Dell          | Latitude D830               | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | ENVY m6                     | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Apple         | MacBookPro5,4               | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Toshiba       | TECRA W50-A                 | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| Lenovo        | Z710 20250                  | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| HP            | G5000 (GF767EA#B1A)         | [5239511cca](https://linux-hardware.org/?probe=5239511cca) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Unknown       | M17                         | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Medion        | E5214                       | [f3ab89b2d3](https://linux-hardware.org/?probe=f3ab89b2d3) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c883420b97](https://linux-hardware.org/?probe=c883420b97) | Nov 23, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| Acer          | Aspire ES1-731              | [649e8a4e24](https://linux-hardware.org/?probe=649e8a4e24) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| Samsung       | 530XBB                      | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| Acer          | Aspire One 721              | [e50838c5ff](https://linux-hardware.org/?probe=e50838c5ff) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Notebook      | NL40_50CU                   | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| Apple         | MacBookPro14,3              | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [84df1d0476](https://linux-hardware.org/?probe=84df1d0476) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| Medion        | E5214                       | [8e3148e284](https://linux-hardware.org/?probe=8e3148e284) | Nov 20, 2023 |
| HP            | ProBook 430 G2              | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [626d8d9409](https://linux-hardware.org/?probe=626d8d9409) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Lenovo        | ThinkPad X60 1707Y91        | [ac0e28ee75](https://linux-hardware.org/?probe=ac0e28ee75) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Medion        | E5214                       | [4513f3394d](https://linux-hardware.org/?probe=4513f3394d) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ec19f0fa52](https://linux-hardware.org/?probe=ec19f0fa52) | Nov 18, 2023 |
| Dell          | Latitude 5490               | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [7edaa0f1be](https://linux-hardware.org/?probe=7edaa0f1be) | Nov 15, 2023 |
| HP            | InsydeH2O EFI BIOS          | [559ef6212b](https://linux-hardware.org/?probe=559ef6212b) | Nov 15, 2023 |
| HP            | ZBook 14u G6                | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Compaq 6910p                | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [d00bbdf844](https://linux-hardware.org/?probe=d00bbdf844) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [493702778b](https://linux-hardware.org/?probe=493702778b) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00CNGE    | [35e0f85cf3](https://linux-hardware.org/?probe=35e0f85cf3) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a0105ee2c8](https://linux-hardware.org/?probe=a0105ee2c8) | Nov 13, 2023 |
| HP            | 15                          | [20b22b2eeb](https://linux-hardware.org/?probe=20b22b2eeb) | Nov 13, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [83d6eddd15](https://linux-hardware.org/?probe=83d6eddd15) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [55b706c3ec](https://linux-hardware.org/?probe=55b706c3ec) | Nov 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [4c40c1d213](https://linux-hardware.org/?probe=4c40c1d213) | Nov 11, 2023 |
| Unknown       | Unknown                     | [16acb0dabc](https://linux-hardware.org/?probe=16acb0dabc) | Nov 11, 2023 |
| Toshiba       | Satellite L655              | [b3c59942a1](https://linux-hardware.org/?probe=b3c59942a1) | Nov 11, 2023 |
| HP            | Presario CQ62               | [584d709751](https://linux-hardware.org/?probe=584d709751) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | Precision M6800             | [4ad69afe3a](https://linux-hardware.org/?probe=4ad69afe3a) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | [e4fd0fa1f0](https://linux-hardware.org/?probe=e4fd0fa1f0) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Lenovo        | Z40-70 20366                | [f1968605c1](https://linux-hardware.org/?probe=f1968605c1) | Nov 09, 2023 |
| Acer          | Aspire E1-531               | [6a30b05dcb](https://linux-hardware.org/?probe=6a30b05dcb) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| HP            | Compaq 6830s                | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [b7e993f677](https://linux-hardware.org/?probe=b7e993f677) | Nov 07, 2023 |
| Fujitsu Si... | AMILO Li 1818               | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Acer          | Aspire ES1-572              | [eea33256f6](https://linux-hardware.org/?probe=eea33256f6) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| Dell          | Latitude E7450              | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| Dell          | Latitude E6520              | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Sony          | SVS15116GAB                 | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | ENVY 17                     | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| HP            | ENVY 17                     | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| HP            | 250 G7 Notebook PC          | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| Acer          | Aspire 5738                 | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| Dell          | Precision 7530              | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| Dell          | Latitude 5490               | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| HP            | Pavilion g7                 | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| HP            | Compaq Presario CQ60        | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| HP            | 250 G8 Notebook PC          | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Alienware     | M14xR2                      | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dell          | Precision 5530              | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Medion        | E4251 MD61435               | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Dell          | G3 3579                     | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Acer          | Aspire ES1-521              | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| HP            | Pavilion dv6                | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| HP            | 470 17 inch G9              | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| HP            | Notebook                    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Dell          | XPS 13 9360                 | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| HP            | 250 G7 Notebook PC          | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Apple         | MacBook4,1                  | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| ASUSTek       | K54C                        | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Lenovo        | V110-14IAP 80TF             | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Dell          | Inspiron 5559               | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| HP            | Laptop 14-dq1xxx            | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [b1efa66e79](https://linux-hardware.org/?probe=b1efa66e79) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| TERRA         | TERRAPC                     | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| HP            | Notebook                    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Dell          | Latitude E5470              | [ca95c6f5bc](https://linux-hardware.org/?probe=ca95c6f5bc) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | 15                          | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| OEM           | Unknown                     | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Positivo      | Mobile                      | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| Dell          | Precision M4700             | [3680e0f79f](https://linux-hardware.org/?probe=3680e0f79f) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | EliteBook 8560p             | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Haier         | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| eMachines     | eMD728                      | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| HP            | Pavilion g7                 | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| IPASON        | P3                          | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Sony          | SVF14214CXW                 | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| ASUSTek       | G50VT                       | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Google        | Lars                        | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| Apple         | MacBookAir4,1               | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| HP            | Pavilion g6                 | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| Dell          | Latitude E7450              | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookAir7,2               | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| Framework     | Laptop                      | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| Dell          | XPS 17 9700                 | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Samsung       | N150/N210/N220              | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Apple         | MacBookPro10,1              | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Acer          | Aspire E5-574               | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Dell          | Latitude 3340               | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Chuwi         | GemiBook XPro               | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Aspire E1-570               | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Dell          | Precision M2800             | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| Apple         | MacBookPro10,1              | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | OMEN by Laptop              | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| ASUSTek       | GL702VI                     | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Acer          | Aspire E5-574               | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| HP            | 655                         | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| Dell          | Inspiron 3501               | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| HP            | ProBook 6570b               | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Unknown       | X133                        | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| HP            | EliteBook 8470p             | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Unknown       | E450                        | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | XPS 15 9560                 | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Acer          | Aspire E1-570               | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Acer          | Aspire V5-531               | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| Dell          | Latitude E6540              | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| ASUSTek       | K53U                        | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Dell          | Vostro 1510                 | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Acer          | AOHAPPY                     | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| HP            | Laptop 14-em0xxx            | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Acer          | AOHAPPY                     | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Acer          | Aspire E5-574               | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| Dell          | Vostro 3580                 | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| Positivo      | Q4128C-S                    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Inspiron 1545               | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Apple         | MacBookPro14,2              | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| HP            | ProBook 4540s               | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| HP            | Notebook                    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Google        | Cyan                        | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| Dell          | Latitude E6430              | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| HP            | kip                         | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Dell          | Precision M4500             | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | Latitude E5510              | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| HP            | 255 G5                      | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 2107      | 64.73%  |
| Zorin 15 | 1015      | 31.18%  |
| Zorin 12 | 115       | 3.53%   |
| Zorin 17 | 18        | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 3242      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 136       | 3.65%   |
| 5.11.0-38-generic | 101       | 2.71%   |
| 5.11.0-27-generic | 94        | 2.52%   |
| 5.15.0-52-generic | 93        | 2.49%   |
| 5.15.0-58-generic | 91        | 2.44%   |
| 5.15.0-46-generic | 88        | 2.36%   |
| 5.13.0-30-generic | 74        | 1.98%   |
| 5.3.0-40-generic  | 67        | 1.8%    |
| 5.11.0-37-generic | 67        | 1.8%    |
| 5.11.0-40-generic | 65        | 1.74%   |
| 5.15.0-78-generic | 64        | 1.72%   |
| 5.15.0-69-generic | 63        | 1.69%   |
| 5.15.0-67-generic | 63        | 1.69%   |
| 5.11.0-41-generic | 63        | 1.69%   |
| 5.4.0-42-generic  | 61        | 1.64%   |
| 5.13.0-39-generic | 60        | 1.61%   |
| 5.15.0-88-generic | 59        | 1.58%   |
| 5.11.0-34-generic | 57        | 1.53%   |
| 5.15.0-60-generic | 56        | 1.5%    |
| 5.11.0-43-generic | 56        | 1.5%    |
| 5.15.0-76-generic | 55        | 1.47%   |
| 5.15.0-71-generic | 54        | 1.45%   |
| 5.3.0-46-generic  | 53        | 1.42%   |
| 5.15.0-48-generic | 51        | 1.37%   |
| 5.13.0-44-generic | 48        | 1.29%   |
| 5.3.0-51-generic  | 47        | 1.26%   |
| 5.0.0-37-generic  | 47        | 1.26%   |
| 5.13.0-40-generic | 46        | 1.23%   |
| 5.15.0-86-generic | 43        | 1.15%   |
| 5.15.0-53-generic | 43        | 1.15%   |
| 5.15.0-84-generic | 42        | 1.13%   |
| 5.15.0-91-generic | 40        | 1.07%   |
| 5.13.0-35-generic | 40        | 1.07%   |
| 5.4.0-47-generic  | 38        | 1.02%   |
| 5.3.0-53-generic  | 37        | 0.99%   |
| 5.13.0-28-generic | 37        | 0.99%   |
| 5.3.0-42-generic  | 36        | 0.97%   |
| 5.15.0-89-generic | 36        | 0.97%   |
| 5.4.0-45-generic  | 35        | 0.94%   |
| 5.15.0-41-generic | 35        | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 1173      | 34.75%  |
| 5.4.0   | 593       | 17.57%  |
| 5.11.0  | 550       | 16.29%  |
| 5.13.0  | 406       | 12.03%  |
| 5.3.0   | 312       | 9.24%   |
| 4.15.0  | 111       | 3.29%   |
| 5.0.0   | 89        | 2.64%   |
| 4.18.0  | 45        | 1.33%   |
| 5.8.0   | 23        | 0.68%   |
| 6.2.0   | 18        | 0.53%   |
| 5.14.0  | 8         | 0.24%   |
| 6.3.13  | 4         | 0.12%   |
| 4.4.0   | 4         | 0.12%   |
| 6.5.7   | 2         | 0.06%   |
| 6.2.16  | 2         | 0.06%   |
| 5.6.0   | 2         | 0.06%   |
| 5.19.0  | 2         | 0.06%   |
| 5.18.15 | 2         | 0.06%   |
| 5.16.0  | 2         | 0.06%   |
| 5.10.0  | 2         | 0.06%   |
| 6.6.7   | 1         | 0.03%   |
| 6.6.1   | 1         | 0.03%   |
| 6.3.2   | 1         | 0.03%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.1.22  | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.9.12  | 1         | 0.03%   |
| 5.9.0   | 1         | 0.03%   |
| 5.7.1   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.4.1   | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.12 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 1175      | 34.8%   |
| 5.4     | 595       | 17.62%  |
| 5.11    | 550       | 16.29%  |
| 5.13    | 407       | 12.06%  |
| 5.3     | 312       | 9.24%   |
| 4.15    | 111       | 3.29%   |
| 5.0     | 89        | 2.64%   |
| 4.18    | 45        | 1.33%   |
| 5.8     | 23        | 0.68%   |
| 6.2     | 21        | 0.62%   |
| 5.14    | 8         | 0.24%   |
| 6.3     | 6         | 0.18%   |
| 5.19    | 6         | 0.18%   |
| 5.10    | 4         | 0.12%   |
| 4.4     | 4         | 0.12%   |
| 6.0     | 3         | 0.09%   |
| 5.18    | 3         | 0.09%   |
| 5.16    | 3         | 0.09%   |
| 6.6     | 2         | 0.06%   |
| 6.5     | 2         | 0.06%   |
| 5.9     | 2         | 0.06%   |
| 5.6     | 2         | 0.06%   |
| 6.1     | 1         | 0.03%   |
| 5.7     | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2964      | 91.34%  |
| i686   | 281       | 8.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 2328      | 71%     |
| XFCE       | 754       | 22.99%  |
| Unknown    | 173       | 5.28%   |
| X-Cinnamon | 7         | 0.21%   |
| KDE5       | 4         | 0.12%   |
| Unity      | 3         | 0.09%   |
| KDE        | 3         | 0.09%   |
| i3         | 2         | 0.06%   |
| Budgie     | 2         | 0.06%   |
| LXQt       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| Cinnamon   | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3084      | 94.17%  |
| Unknown | 108       | 3.3%    |
| Wayland | 82        | 2.5%    |
| Tty     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2544      | 77.23%  |
| GDM     | 274       | 8.32%   |
| GDM3    | 263       | 7.98%   |
| LightDM | 204       | 6.19%   |
| TDM     | 6         | 0.18%   |
| SDDM    | 2         | 0.06%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1134      | 34.68%  |
| de_DE   | 267       | 8.17%   |
| pt_BR   | 200       | 6.12%   |
| en_GB   | 191       | 5.84%   |
| Unknown | 127       | 3.88%   |
| it_IT   | 124       | 3.79%   |
| es_ES   | 110       | 3.36%   |
| fr_FR   | 108       | 3.3%    |
| en_IN   | 103       | 3.15%   |
| en_CA   | 92        | 2.81%   |
| pl_PL   | 82        | 2.51%   |
| en_AU   | 49        | 1.5%    |
| nl_NL   | 48        | 1.47%   |
| es_MX   | 47        | 1.44%   |
| pt_PT   | 43        | 1.31%   |
| ru_RU   | 39        | 1.19%   |
| cs_CZ   | 38        | 1.16%   |
| en_ZA   | 32        | 0.98%   |
| es_AR   | 31        | 0.95%   |
| tr_TR   | 26        | 0.8%    |
| sv_SE   | 25        | 0.76%   |
| es_CL   | 21        | 0.64%   |
| en_NZ   | 20        | 0.61%   |
| C       | 20        | 0.61%   |
| de_AT   | 18        | 0.55%   |
| hu_HU   | 17        | 0.52%   |
| de_CH   | 17        | 0.52%   |
| nl_BE   | 13        | 0.4%    |
| ja_JP   | 13        | 0.4%    |
| fr_CA   | 13        | 0.4%    |
| fr_BE   | 13        | 0.4%    |
| es_CO   | 12        | 0.37%   |
| el_GR   | 12        | 0.37%   |
| da_DK   | 11        | 0.34%   |
| es_PE   | 10        | 0.31%   |
| ro_RO   | 9         | 0.28%   |
| en_PH   | 9         | 0.28%   |
| bg_BG   | 8         | 0.24%   |
| ru_UA   | 7         | 0.21%   |
| hr_HR   | 7         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1648      | 50.17%  |
| EFI  | 1637      | 49.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2998      | 91.71%  |
| Tmpfs   | 87        | 2.66%   |
| Overlay | 69        | 2.11%   |
| Zfs     | 37        | 1.13%   |
| Btrfs   | 32        | 0.98%   |
| Ext2    | 22        | 0.67%   |
| Unknown | 17        | 0.52%   |
| Xfs     | 4         | 0.12%   |
| Ext3    | 3         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2772      | 84.46%  |
| GPT     | 390       | 11.88%  |
| MBR     | 120       | 3.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3100      | 95%     |
| Yes       | 163       | 5%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2755      | 84.51%  |
| Yes       | 505       | 15.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 731       | 22.55%  |
| Lenovo              | 518       | 15.98%  |
| Dell                | 494       | 15.24%  |
| ASUSTek Computer    | 307       | 9.47%   |
| Acer                | 262       | 8.08%   |
| Toshiba             | 169       | 5.21%   |
| Apple               | 97        | 2.99%   |
| Samsung Electronics | 61        | 1.88%   |
| Sony                | 56        | 1.73%   |
| MSI                 | 46        | 1.42%   |
| Google              | 33        | 1.02%   |
| Unknown             | 33        | 1.02%   |
| Packard Bell        | 29        | 0.89%   |
| HUAWEI              | 29        | 0.89%   |
| Positivo            | 23        | 0.71%   |
| Medion              | 22        | 0.68%   |
| Fujitsu Siemens     | 21        | 0.65%   |
| Fujitsu             | 20        | 0.62%   |
| Notebook            | 13        | 0.4%    |
| Alienware           | 13        | 0.4%    |
| Chuwi               | 10        | 0.31%   |
| AMI                 | 10        | 0.31%   |
| Panasonic           | 9         | 0.28%   |
| Multilaser          | 8         | 0.25%   |
| Gateway             | 8         | 0.25%   |
| eMachines           | 8         | 0.25%   |
| Itautec             | 7         | 0.22%   |
| Semp Toshiba        | 6         | 0.19%   |
| LG Electronics      | 6         | 0.19%   |
| Insyde              | 6         | 0.19%   |
| GPU Company         | 6         | 0.19%   |
| Digibras            | 6         | 0.19%   |
| Thomson             | 5         | 0.15%   |
| NEC Computers       | 5         | 0.15%   |
| Intel               | 5         | 0.15%   |
| Ematic              | 5         | 0.15%   |
| Clevo               | 5         | 0.15%   |
| TUXEDO              | 4         | 0.12%   |
| TrekStor            | 4         | 0.12%   |
| Razer               | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 62        | 1.91%   |
| HP Notebook             | 34        | 1.05%   |
| HP 15                   | 18        | 0.56%   |
| HP Pavilion Notebook    | 17        | 0.52%   |
| HP Pavilion dv6         | 17        | 0.52%   |
| HP Pavilion dv7         | 14        | 0.43%   |
| HP Pavilion 15          | 13        | 0.4%    |
| Toshiba Satellite C660  | 10        | 0.31%   |
| HP Pavilion g7          | 10        | 0.31%   |
| Dell Latitude E6400     | 10        | 0.31%   |
| Dell Latitude D630      | 10        | 0.31%   |
| Dell Inspiron 1545      | 10        | 0.31%   |
| HP Pavilion g6          | 9         | 0.28%   |
| Dell Inspiron 15-3567   | 9         | 0.28%   |
| Apple MacBookPro8,1     | 9         | 0.28%   |
| HP Laptop 15-bw0xx      | 8         | 0.25%   |
| Dell Latitude E6540     | 8         | 0.25%   |
| Apple MacBookPro12,1    | 8         | 0.25%   |
| HP Pavilion dv6700      | 7         | 0.22%   |
| HP EliteBook 8460p      | 7         | 0.22%   |
| HP EliteBook 840 G1     | 7         | 0.22%   |
| Dell Latitude E6430     | 7         | 0.22%   |
| Dell Latitude E6410     | 7         | 0.22%   |
| Dell Inspiron 3521      | 7         | 0.22%   |
| Dell Inspiron 1525      | 7         | 0.22%   |
| Apple MacBookPro11,1    | 7         | 0.22%   |
| Toshiba Satellite A100  | 6         | 0.19%   |
| HP ProBook 640 G1       | 6         | 0.19%   |
| HP ProBook 4540s        | 6         | 0.19%   |
| HP Pavilion dv5         | 6         | 0.19%   |
| HP Pavilion 17          | 6         | 0.19%   |
| HP Laptop 15-db0xxx     | 6         | 0.19%   |
| HP Compaq Presario CQ60 | 6         | 0.19%   |
| Dell Latitude E6520     | 6         | 0.19%   |
| Dell Latitude E5470     | 6         | 0.19%   |
| Dell Inspiron 7520      | 6         | 0.19%   |
| Positivo Mobile         | 5         | 0.15%   |
| Itautec Infoway         | 5         | 0.15%   |
| HUAWEI BOHK-WAX9X       | 5         | 0.15%   |
| HP Stream Notebook      | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 218       | 6.72%   |
| Dell Latitude         | 184       | 5.68%   |
| Acer Aspire           | 184       | 5.68%   |
| HP Pavilion           | 181       | 5.58%   |
| Dell Inspiron         | 179       | 5.52%   |
| Lenovo IdeaPad        | 160       | 4.94%   |
| Toshiba Satellite     | 143       | 4.41%   |
| HP EliteBook          | 93        | 2.87%   |
| HP ProBook            | 80        | 2.47%   |
| HP Laptop             | 68        | 2.1%    |
| Unknown               | 62        | 1.91%   |
| HP Compaq             | 55        | 1.7%    |
| ASUS VivoBook         | 43        | 1.33%   |
| Dell Vostro           | 37        | 1.14%   |
| HP Notebook           | 34        | 1.05%   |
| Packard Bell EasyNote | 27        | 0.83%   |
| Dell XPS              | 27        | 0.83%   |
| HP Stream             | 24        | 0.74%   |
| HP ENVY               | 24        | 0.74%   |
| Dell Precision        | 23        | 0.71%   |
| HP 15                 | 20        | 0.62%   |
| ASUS ZenBook          | 19        | 0.59%   |
| ASUS ROG              | 19        | 0.59%   |
| HP Presario           | 17        | 0.52%   |
| Lenovo Yoga           | 15        | 0.46%   |
| HP 255                | 15        | 0.46%   |
| HP OMEN               | 14        | 0.43%   |
| Fujitsu LIFEBOOK      | 14        | 0.43%   |
| Apple MacBookPro8     | 14        | 0.43%   |
| HP ZBook              | 13        | 0.4%    |
| ASUS ASUS             | 13        | 0.4%    |
| Lenovo Legion         | 12        | 0.37%   |
| Fujitsu Siemens AMILO | 12        | 0.37%   |
| Dell Studio           | 12        | 0.37%   |
| Apple MacBookPro11    | 12        | 0.37%   |
| Acer TravelMate       | 12        | 0.37%   |
| Dell System           | 11        | 0.34%   |
| Apple MacBookPro5     | 10        | 0.31%   |
| Acer Swift            | 10        | 0.31%   |
| Acer Nitro            | 10        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 284       | 8.76%   |
| 2012    | 272       | 8.39%   |
| 2013    | 263       | 8.11%   |
| 2010    | 224       | 6.91%   |
| 2008    | 209       | 6.45%   |
| 2018    | 203       | 6.26%   |
| 2014    | 200       | 6.17%   |
| 2019    | 192       | 5.92%   |
| 2017    | 189       | 5.83%   |
| 2021    | 186       | 5.74%   |
| 2015    | 179       | 5.52%   |
| 2020    | 171       | 5.27%   |
| 2016    | 166       | 5.12%   |
| 2007    | 158       | 4.87%   |
| 2009    | 150       | 4.63%   |
| 2022    | 60        | 1.85%   |
| 2006    | 56        | 1.73%   |
| 2005    | 37        | 1.14%   |
| 2023    | 34        | 1.05%   |
| Unknown | 6         | 0.19%   |
| 2003    | 2         | 0.06%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3242      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2860      | 87.57%  |
| Enabled  | 406       | 12.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3204      | 98.83%  |
| Yes  | 38        | 1.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 951       | 29.06%  |
| 3.01-4.0    | 940       | 28.73%  |
| 8.01-16.0   | 399       | 12.19%  |
| 1.01-2.0    | 336       | 10.27%  |
| 16.01-24.0  | 329       | 10.06%  |
| 2.01-3.0    | 117       | 3.58%   |
| 32.01-64.0  | 97        | 2.96%   |
| 0.51-1.0    | 73        | 2.23%   |
| 64.01-256.0 | 16        | 0.49%   |
| 24.01-32.0  | 14        | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1467      | 41.75%  |
| 2.01-3.0   | 1014      | 28.86%  |
| 3.01-4.0   | 404       | 11.5%   |
| 0.51-1.0   | 287       | 8.17%   |
| 4.01-8.0   | 274       | 7.8%    |
| 8.01-16.0  | 37        | 1.05%   |
| 0.01-0.5   | 25        | 0.71%   |
| 24.01-32.0 | 3         | 0.09%   |
| 16.01-24.0 | 3         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2519      | 76.45%  |
| 2      | 680       | 20.64%  |
| 3      | 68        | 2.06%   |
| 0      | 12        | 0.36%   |
| 4      | 10        | 0.3%    |
| 5      | 4         | 0.12%   |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1715      | 52.61%  |
| Yes       | 1545      | 47.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2647      | 81.45%  |
| No        | 603       | 18.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3140      | 96.73%  |
| No        | 106       | 3.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2150      | 65.61%  |
| No        | 1127      | 34.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 646       | 19.84%  |
| Germany      | 308       | 9.46%   |
| Brazil       | 232       | 7.13%   |
| UK           | 182       | 5.59%   |
| Italy        | 130       | 3.99%   |
| Canada       | 119       | 3.65%   |
| Spain        | 114       | 3.5%    |
| India        | 110       | 3.38%   |
| France       | 106       | 3.26%   |
| Netherlands  | 85        | 2.61%   |
| Poland       | 79        | 2.43%   |
| Mexico       | 71        | 2.18%   |
| Australia    | 55        | 1.69%   |
| Portugal     | 50        | 1.54%   |
| Sweden       | 44        | 1.35%   |
| Czechia      | 43        | 1.32%   |
| Russia       | 41        | 1.26%   |
| Argentina    | 40        | 1.23%   |
| Belgium      | 39        | 1.2%    |
| South Africa | 38        | 1.17%   |
| Austria      | 38        | 1.17%   |
| Turkey       | 35        | 1.07%   |
| Switzerland  | 35        | 1.07%   |
| Romania      | 35        | 1.07%   |
| Indonesia    | 30        | 0.92%   |
| Greece       | 27        | 0.83%   |
| New Zealand  | 23        | 0.71%   |
| Japan        | 21        | 0.64%   |
| Colombia     | 21        | 0.64%   |
| Chile        | 21        | 0.64%   |
| Hungary      | 20        | 0.61%   |
| Norway       | 19        | 0.58%   |
| Serbia       | 17        | 0.52%   |
| Egypt        | 17        | 0.52%   |
| Bulgaria     | 16        | 0.49%   |
| Denmark      | 15        | 0.46%   |
| Ireland      | 14        | 0.43%   |
| Finland      | 13        | 0.4%    |
| Ukraine      | 12        | 0.37%   |
| Philippines  | 12        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 24        | 0.7%    |
| Berlin         | 23        | 0.67%   |
| Vienna         | 22        | 0.64%   |
| Madrid         | 21        | 0.61%   |
| Sydney         | 20        | 0.59%   |
| Munich         | 18        | 0.53%   |
| Rome           | 17        | 0.5%    |
| Milan          | 16        | 0.47%   |
| Johannesburg   | 16        | 0.47%   |
| New York       | 15        | 0.44%   |
| Hamburg        | 15        | 0.44%   |
| Athens         | 15        | 0.44%   |
| Mexico City    | 14        | 0.41%   |
| Istanbul       | 14        | 0.41%   |
| Amsterdam      | 14        | 0.41%   |
| Rio de Janeiro | 13        | 0.38%   |
| Paris          | 13        | 0.38%   |
| Montreal       | 13        | 0.38%   |
| Auckland       | 13        | 0.38%   |
| Jakarta        | 12        | 0.35%   |
| Warsaw         | 11        | 0.32%   |
| Toronto        | 11        | 0.32%   |
| Stockholm      | 11        | 0.32%   |
| Seattle        | 11        | 0.32%   |
| Prague         | 11        | 0.32%   |
| Moscow         | 11        | 0.32%   |
| Denver         | 11        | 0.32%   |
| Dallas         | 11        | 0.32%   |
| Cairo          | 11        | 0.32%   |
| Bengaluru      | 11        | 0.32%   |
| Stuttgart      | 10        | 0.29%   |
| Nairobi        | 10        | 0.29%   |
| Delhi          | 10        | 0.29%   |
| Buenos Aires   | 10        | 0.29%   |
| Bucharest      | 10        | 0.29%   |
| Bogotá        | 10        | 0.29%   |
| Belgrade       | 10        | 0.29%   |
| Melbourne      | 9         | 0.26%   |
| Krakow         | 9         | 0.26%   |
| Kolkata        | 9         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 472       | 578    | 12.4%   |
| WDC                         | 452       | 555    | 11.88%  |
| Samsung Electronics         | 438       | 596    | 11.51%  |
| Toshiba                     | 380       | 434    | 9.99%   |
| Unknown                     | 334       | 455    | 8.78%   |
| SanDisk                     | 224       | 270    | 5.89%   |
| Hitachi                     | 174       | 204    | 4.57%   |
| Kingston                    | 169       | 209    | 4.44%   |
| Crucial                     | 123       | 150    | 3.23%   |
| HGST                        | 111       | 135    | 2.92%   |
| Intel                       | 95        | 117    | 2.5%    |
| SK hynix                    | 90        | 104    | 2.37%   |
| Micron Technology           | 70        | 86     | 1.84%   |
| China                       | 46        | 57     | 1.21%   |
| A-DATA Technology           | 45        | 51     | 1.18%   |
| Fujitsu                     | 44        | 47     | 1.16%   |
| Apple                       | 43        | 50     | 1.13%   |
| KIOXIA                      | 30        | 35     | 0.79%   |
| Intenso                     | 29        | 30     | 0.76%   |
| PNY                         | 22        | 26     | 0.58%   |
| SPCC                        | 21        | 28     | 0.55%   |
| Unknown                     | 21        | 23     | 0.55%   |
| Phison                      | 19        | 23     | 0.5%    |
| LITEONIT                    | 18        | 21     | 0.47%   |
| Netac                       | 17        | 17     | 0.45%   |
| LITEON                      | 17        | 21     | 0.45%   |
| Patriot                     | 16        | 20     | 0.42%   |
| Transcend                   | 15        | 20     | 0.39%   |
| JMicron Technology          | 13        | 14     | 0.34%   |
| GOODRAM                     | 13        | 14     | 0.34%   |
| Team                        | 12        | 13     | 0.32%   |
| Silicon Motion              | 11        | 12     | 0.29%   |
| Phison Electronics          | 9         | 9      | 0.24%   |
| OCZ                         | 9         | 10     | 0.24%   |
| SABRENT                     | 8         | 9      | 0.21%   |
| Hewlett-Packard             | 7         | 9      | 0.18%   |
| ASMT                        | 7         | 7      | 0.18%   |
| Kingston Technology Company | 6         | 7      | 0.16%   |
| KingSpec                    | 6         | 6      | 0.16%   |
| Plextor                     | 5         | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 115       | 2.91%   |
| Unknown MMC Card  64GB                              | 89        | 2.25%   |
| Seagate ST1000LM035-1RK172 1TB                      | 53        | 1.34%   |
| Toshiba MQ01ABF050 500GB                            | 52        | 1.32%   |
| Toshiba MQ01ABD100 1TB                              | 44        | 1.11%   |
| Seagate ST500LT012-1DG142 500GB                     | 41        | 1.04%   |
| Kingston SA400S37240G 240GB SSD                     | 39        | 0.99%   |
| Unknown MMC Card  128GB                             | 36        | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 35        | 0.89%   |
| Toshiba MQ04ABF100 1TB                              | 34        | 0.86%   |
| Seagate ST9500325AS 500GB                           | 29        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                     | 29        | 0.73%   |
| Unknown MMC Card  16GB                              | 27        | 0.68%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.61%   |
| Kingston SA400S37120G 120GB SSD                     | 23        | 0.58%   |
| Crucial CT240BX500SSD1 240GB                        | 23        | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 21        | 0.53%   |
| HGST HTS721010A9E630 1TB                            | 21        | 0.53%   |
| Unknown                                             | 21        | 0.53%   |
| SanDisk NVMe SSD Drive 256GB                        | 20        | 0.51%   |
| HGST HTS725050A7E630 500GB                          | 20        | 0.51%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 19        | 0.48%   |
| Samsung SSD 850 EVO 500GB                           | 18        | 0.46%   |
| HGST HTS545050A7E680 500GB                          | 18        | 0.46%   |
| HGST HTS541010A9E680 1TB                            | 18        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 18        | 0.46%   |
| Seagate Expansion 1TB                               | 17        | 0.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 17        | 0.43%   |
| Intel NVMe SSD Drive 512GB                          | 17        | 0.43%   |
| Hitachi HTS545032B9A300 320GB                       | 17        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 16        | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 15        | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB                         | 15        | 0.38%   |
| Samsung SSD 860 EVO 500GB                           | 14        | 0.35%   |
| Samsung SSD 860 EVO 250GB                           | 13        | 0.33%   |
| Samsung SSD 850 EVO 250GB                           | 13        | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 12        | 0.3%    |
| Toshiba MQ01ABD075 752GB                            | 12        | 0.3%    |
| Samsung HM160HI 160GB                               | 12        | 0.3%    |
| HGST HTS545050A7E380 500GB                          | 12        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 465       | 565    | 29.47%  |
| WDC                 | 381       | 459    | 24.14%  |
| Toshiba             | 318       | 358    | 20.15%  |
| Hitachi             | 174       | 204    | 11.03%  |
| HGST                | 111       | 135    | 7.03%   |
| Samsung Electronics | 48        | 53     | 3.04%   |
| Fujitsu             | 44        | 47     | 2.79%   |
| Unknown             | 15        | 21     | 0.95%   |
| Apple               | 5         | 5      | 0.32%   |
| IBM/Hitachi         | 4         | 5      | 0.25%   |
| TO Exter            | 2         | 3      | 0.13%   |
| JMicron Technology  | 2         | 2      | 0.13%   |
| XrayDisk            | 1         | 1      | 0.06%   |
| USB3.0              | 1         | 1      | 0.06%   |
| SSK                 | 1         | 1      | 0.06%   |
| SABRENT             | 1         | 1      | 0.06%   |
| Pioneer             | 1         | 1      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| KESU                | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| External            | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 233       | 327    | 18.91%  |
| Kingston            | 148       | 185    | 12.01%  |
| SanDisk             | 124       | 150    | 10.06%  |
| Crucial             | 120       | 145    | 9.74%   |
| WDC                 | 52        | 68     | 4.22%   |
| China               | 45        | 56     | 3.65%   |
| Intel               | 42        | 48     | 3.41%   |
| A-DATA Technology   | 38        | 44     | 3.08%   |
| Toshiba             | 33        | 37     | 2.68%   |
| Apple               | 32        | 36     | 2.6%    |
| SK hynix            | 30        | 34     | 2.44%   |
| Micron Technology   | 30        | 35     | 2.44%   |
| PNY                 | 22        | 26     | 1.79%   |
| SPCC                | 20        | 27     | 1.62%   |
| Intenso             | 20        | 20     | 1.62%   |
| LITEONIT            | 18        | 21     | 1.46%   |
| Netac               | 17        | 17     | 1.38%   |
| LITEON              | 17        | 21     | 1.38%   |
| Patriot             | 16        | 20     | 1.3%    |
| Transcend           | 15        | 20     | 1.22%   |
| Team                | 12        | 13     | 0.97%   |
| GOODRAM             | 12        | 13     | 0.97%   |
| OCZ                 | 9         | 10     | 0.73%   |
| JMicron Technology  | 7         | 8      | 0.57%   |
| ASMT                | 7         | 7      | 0.57%   |
| Phison              | 6         | 8      | 0.49%   |
| KingSpec            | 6         | 6      | 0.49%   |
| Unknown             | 6         | 8      | 0.49%   |
| Plextor             | 5         | 5      | 0.41%   |
| Hewlett-Packard     | 5         | 7      | 0.41%   |
| Teclast             | 4         | 4      | 0.32%   |
| Apacer              | 4         | 4      | 0.32%   |
| Verbatim            | 3         | 3      | 0.24%   |
| Mushkin             | 3         | 3      | 0.24%   |
| Lexar               | 3         | 3      | 0.24%   |
| Fanxiang            | 3         | 4      | 0.24%   |
| BHT                 | 3         | 4      | 0.24%   |
| Vaseky              | 2         | 3      | 0.16%   |
| TCSUNBOW            | 2         | 2      | 0.16%   |
| Leven               | 2         | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1543      | 1866   | 41.95%  |
| SSD     | 1168      | 1514   | 31.76%  |
| NVMe    | 572       | 755    | 15.55%  |
| MMC     | 334       | 452    | 9.08%   |
| Unknown | 61        | 69     | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2546      | 3295   | 71.54%  |
| NVMe | 567       | 746    | 15.93%  |
| MMC  | 334       | 452    | 9.38%   |
| SAS  | 112       | 163    | 3.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1995      | 2503   | 74.25%  |
| 0.51-1.0   | 630       | 790    | 23.45%  |
| 1.01-2.0   | 49        | 66     | 1.82%   |
| 4.01-10.0  | 8         | 12     | 0.3%    |
| 3.01-4.0   | 5         | 9      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1185      | 35.49%  |
| 251-500        | 852       | 25.52%  |
| 501-1000       | 420       | 12.58%  |
| 51-100         | 364       | 10.9%   |
| 21-50          | 223       | 6.68%   |
| 1001-2000      | 105       | 3.14%   |
| 1-20           | 100       | 2.99%   |
| Unknown        | 34        | 1.02%   |
| More than 3000 | 32        | 0.96%   |
| 2001-3000      | 24        | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1676      | 48.19%  |
| 21-50          | 863       | 24.81%  |
| 51-100         | 368       | 10.58%  |
| 101-250        | 310       | 8.91%   |
| 251-500        | 135       | 3.88%   |
| 501-1000       | 57        | 1.64%   |
| Unknown        | 34        | 0.98%   |
| 1001-2000      | 18        | 0.52%   |
| More than 3000 | 12        | 0.35%   |
| 2001-3000      | 5         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 3         | 3      | 4.17%   |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 4.17%   |
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 2.78%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 2.78%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 2.78%   |
| Seagate ST1000LM048-2E7172 1TB                   | 2         | 2      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB                   | 2         | 2      | 2.78%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 2.78%   |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 2.78%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.39%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.39%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.39%   |
| WDC WD3200BPVT-55ZEST0 320GB                     | 1         | 1      | 1.39%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.39%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.39%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.39%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.39%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.39%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.39%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.39%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.39%   |
| Toshiba MK5061GSY 500GB                          | 1         | 1      | 1.39%   |
| Toshiba MK2046GSX 200GB                          | 1         | 1      | 1.39%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.39%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.39%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 1.39%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.39%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.39%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.39%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.39%   |
| Seagate ST9160314AS 40GB                         | 1         | 1      | 1.39%   |
| Seagate ST9120822AS 120GB                        | 1         | 1      | 1.39%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.39%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.39%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.39%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.39%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 1.39%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 23     | 31.94%  |
| Toshiba             | 11        | 11     | 15.28%  |
| WDC                 | 8         | 8      | 11.11%  |
| HGST                | 8         | 9      | 11.11%  |
| Hitachi             | 5         | 5      | 6.94%   |
| Samsung Electronics | 4         | 4      | 5.56%   |
| Kingston            | 3         | 3      | 4.17%   |
| SK hynix            | 2         | 2      | 2.78%   |
| Teclast             | 1         | 1      | 1.39%   |
| POLION              | 1         | 1      | 1.39%   |
| Micron Technology   | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| Drevo               | 1         | 1      | 1.39%   |
| Unknown             | 1         | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 23     | 41.82%  |
| Toshiba             | 9         | 9      | 16.36%  |
| WDC                 | 8         | 8      | 14.55%  |
| HGST                | 8         | 9      | 14.55%  |
| Hitachi             | 5         | 5      | 9.09%   |
| Samsung Electronics | 2         | 2      | 3.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 56     | 76.39%  |
| SSD  | 15        | 15     | 20.83%  |
| NVMe | 2         | 2      | 2.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2925      | 4206   | 88.53%  |
| Works    | 305       | 374    | 9.23%   |
| Malfunc  | 71        | 73     | 2.15%   |
| Failed   | 2         | 2      | 0.06%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2357      | 68.26%  |
| AMD                              | 407       | 11.79%  |
| Samsung Electronics              | 191       | 5.53%   |
| SanDisk                          | 110       | 3.19%   |
| SK hynix                         | 57        | 1.65%   |
| Nvidia                           | 53        | 1.53%   |
| Micron Technology                | 41        | 1.19%   |
| Toshiba America Info Systems     | 31        | 0.9%    |
| Silicon Integrated Systems [SiS] | 31        | 0.9%    |
| KIOXIA                           | 30        | 0.87%   |
| Kingston Technology Company      | 27        | 0.78%   |
| Phison Electronics               | 23        | 0.67%   |
| Silicon Motion                   | 14        | 0.41%   |
| VIA Technologies                 | 12        | 0.35%   |
| ADATA Technology                 | 10        | 0.29%   |
| Micron/Crucial Technology        | 8         | 0.23%   |
| Marvell Technology Group         | 6         | 0.17%   |
| Union Memory (Shenzhen)          | 5         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.14%   |
| Lite-On Technology               | 5         | 0.14%   |
| JMicron Technology               | 5         | 0.14%   |
| Apple                            | 5         | 0.14%   |
| Realtek Semiconductor            | 4         | 0.12%   |
| ASMedia Technology               | 4         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Solid State Storage Technology   | 2         | 0.06%   |
| Silicon Image                    | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 312       | 8.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 261       | 6.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 233       | 6.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 208       | 5.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 185       | 4.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 165       | 4.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 128       | 3.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 127       | 3.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 105       | 2.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 103       | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 85        | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 75        | 1.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 70        | 1.81%   |
| Intel Volume Management Device NVMe RAID Controller                              | 64        | 1.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 62        | 1.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 61        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 56        | 1.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 53        | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 52        | 1.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 50        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 46        | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 44        | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 41        | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 39        | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 39        | 1.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 37        | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                              | 34        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 34        | 0.88%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 30        | 0.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 28        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 28        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                            | 26        | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 25        | 0.65%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 24        | 0.62%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 24        | 0.62%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 24        | 0.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 24        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 23        | 0.6%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 21        | 0.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 21        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2349      | 64.3%   |
| NVMe | 569       | 15.58%  |
| IDE  | 473       | 12.95%  |
| RAID | 262       | 7.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2727      | 84.11%  |
| AMD          | 514       | 15.85%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 39        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 38        | 1.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 37        | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 36        | 1.11%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 33        | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 32        | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 31        | 0.96%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 31        | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 29        | 0.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 27        | 0.83%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 27        | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 23        | 0.71%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 23        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 22        | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 22        | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 22        | 0.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 21        | 0.65%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 21        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.62%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 20        | 0.62%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 20        | 0.62%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 20        | 0.62%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.59%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 19        | 0.59%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 19        | 0.59%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 19        | 0.59%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 19        | 0.59%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.59%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 19        | 0.59%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 18        | 0.55%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 18        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 692       | 21.33%  |
| Intel Core i7           | 486       | 14.98%  |
| Intel Core i3           | 319       | 9.83%   |
| Intel Celeron           | 291       | 8.97%   |
| Intel Core 2 Duo        | 260       | 8.01%   |
| Intel Atom              | 172       | 5.3%    |
| Other                   | 153       | 4.71%   |
| Intel Pentium           | 107       | 3.3%    |
| AMD Ryzen 5             | 85        | 2.62%   |
| AMD Ryzen 7             | 55        | 1.69%   |
| AMD A6                  | 52        | 1.6%    |
| Intel Pentium Dual-Core | 46        | 1.42%   |
| Intel Genuine           | 42        | 1.29%   |
| AMD A4                  | 42        | 1.29%   |
| Intel Pentium Dual      | 33        | 1.02%   |
| Intel Core 2            | 28        | 0.86%   |
| AMD A10                 | 27        | 0.83%   |
| Intel Pentium M         | 26        | 0.8%    |
| AMD A8                  | 26        | 0.8%    |
| Intel Celeron M         | 25        | 0.77%   |
| AMD Ryzen 3             | 25        | 0.77%   |
| AMD E1                  | 22        | 0.68%   |
| AMD E                   | 20        | 0.62%   |
| AMD Turion 64 X2 Mobile | 17        | 0.52%   |
| Intel Core M            | 13        | 0.4%    |
| Intel Pentium Silver    | 12        | 0.37%   |
| AMD Ryzen 9             | 12        | 0.37%   |
| Intel Celeron Dual-Core | 10        | 0.31%   |
| AMD Turion 64 Mobile    | 9         | 0.28%   |
| AMD E2                  | 9         | 0.28%   |
| AMD Athlon II           | 9         | 0.28%   |
| AMD Athlon 64 X2        | 9         | 0.28%   |
| Intel Core Duo          | 8         | 0.25%   |
| AMD Sempron             | 7         | 0.22%   |
| AMD Mobile Sempron      | 7         | 0.22%   |
| AMD Athlon              | 7         | 0.22%   |
| AMD C-50                | 6         | 0.18%   |
| AMD Athlon X2           | 6         | 0.18%   |
| Intel Core m5           | 5         | 0.15%   |
| AMD Ryzen 7 PRO         | 5         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2028      | 62.5%   |
| 4      | 811       | 24.99%  |
| 1      | 191       | 5.89%   |
| 6      | 101       | 3.11%   |
| 8      | 78        | 2.4%    |
| 10     | 12        | 0.37%   |
| 14     | 10        | 0.31%   |
| 12     | 7         | 0.22%   |
| 16     | 3         | 0.09%   |
| 24     | 2         | 0.06%   |
| 3      | 2         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3242      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1921      | 59.25%  |
| 1      | 1321      | 40.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3122      | 96.27%  |
| 32-bit         | 119       | 3.67%   |
| Unknown        | 2         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 288       | 8.76%   |
| 0x206a7    | 278       | 8.45%   |
| 0x306a9    | 234       | 7.12%   |
| 0x1067a    | 171       | 5.2%    |
| 0x40651    | 143       | 4.35%   |
| 0x406e3    | 113       | 3.44%   |
| 0x20655    | 112       | 3.41%   |
| 0x306d4    | 107       | 3.25%   |
| 0x30678    | 93        | 2.83%   |
| 0x6fd      | 92        | 2.8%    |
| 0x306c3    | 88        | 2.68%   |
| 0x806e9    | 86        | 2.62%   |
| 0x806ea    | 75        | 2.28%   |
| 0x806c1    | 73        | 2.22%   |
| 0x406c4    | 68        | 2.07%   |
| 0x806ec    | 66        | 2.01%   |
| 0x10676    | 54        | 1.64%   |
| 0x706a8    | 49        | 1.49%   |
| 0x906ea    | 46        | 1.4%    |
| 0x506c9    | 44        | 1.34%   |
| 0x406c3    | 44        | 1.34%   |
| 0x706e5    | 41        | 1.25%   |
| 0x20652    | 41        | 1.25%   |
| 0x906e9    | 39        | 1.19%   |
| 0x106ca    | 36        | 1.09%   |
| 0x06006705 | 36        | 1.09%   |
| 0x08108109 | 35        | 1.06%   |
| 0x6e8      | 30        | 0.91%   |
| 0x6d8      | 30        | 0.91%   |
| 0x6f6      | 26        | 0.79%   |
| 0x07030105 | 26        | 0.79%   |
| 0x05000119 | 26        | 0.79%   |
| 0x0700010f | 25        | 0.76%   |
| 0x706a1    | 24        | 0.73%   |
| 0x106c2    | 24        | 0.73%   |
| 0x08108102 | 24        | 0.73%   |
| 0x6fb      | 23        | 0.7%    |
| 0x06001119 | 23        | 0.7%    |
| 0x0a50000c | 22        | 0.67%   |
| 0xa0652    | 21        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 365       | 11.26%  |
| SandyBridge      | 285       | 8.79%   |
| Haswell          | 251       | 7.74%   |
| IvyBridge        | 248       | 7.65%   |
| Penryn           | 238       | 7.34%   |
| Silvermont       | 236       | 7.28%   |
| Core             | 189       | 5.83%   |
| Westmere         | 160       | 4.94%   |
| Skylake          | 138       | 4.26%   |
| Broadwell        | 107       | 3.3%    |
| TigerLake        | 86        | 2.65%   |
| P6               | 84        | 2.59%   |
| Goldmont plus    | 79        | 2.44%   |
| Bonnell          | 71        | 2.19%   |
| Excavator        | 66        | 2.04%   |
| Zen+             | 63        | 1.94%   |
| IceLake          | 54        | 1.67%   |
| Unknown          | 53        | 1.63%   |
| K8 Hammer        | 48        | 1.48%   |
| Goldmont         | 47        | 1.45%   |
| Puma             | 42        | 1.3%    |
| Zen 2            | 41        | 1.26%   |
| Bobcat           | 39        | 1.2%    |
| Zen 3            | 38        | 1.17%   |
| Jaguar           | 32        | 0.99%   |
| Piledriver       | 28        | 0.86%   |
| CometLake        | 26        | 0.8%    |
| K10              | 24        | 0.74%   |
| Alderlake Hybrid | 22        | 0.68%   |
| K10 Llano        | 20        | 0.62%   |
| K8 & K10 hybrid  | 17        | 0.52%   |
| Zen              | 16        | 0.49%   |
| Nehalem          | 11        | 0.34%   |
| Tremont          | 7         | 0.22%   |
| Steamroller      | 7         | 0.22%   |
| NetBurst         | 4         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2394      | 62.59%  |
| AMD                              | 717       | 18.75%  |
| Nvidia                           | 675       | 17.65%  |
| Silicon Integrated Systems [SiS] | 28        | 0.73%   |
| VIA Technologies                 | 11        | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 256       | 6.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 236       | 5.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 148       | 3.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 145       | 3.58%   |
| Intel Core Processor Integrated Graphics Controller                                      | 120       | 2.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 118       | 2.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 118       | 2.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 105       | 2.59%   |
| Intel HD Graphics 620                                                                    | 91        | 2.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 86        | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 83        | 2.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 83        | 2.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 77        | 1.9%    |
| Intel UHD Graphics 620                                                                   | 75        | 1.85%   |
| Intel HD Graphics 5500                                                                   | 74        | 1.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 70        | 1.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 68        | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 65        | 1.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 52        | 1.28%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 51        | 1.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 48        | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 46        | 1.14%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 40        | 0.99%   |
| Intel HD Graphics 500                                                                    | 39        | 0.96%   |
| Intel HD Graphics 630                                                                    | 37        | 0.91%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 33        | 0.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 33        | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 32        | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 31        | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 31        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 30        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 28        | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 28        | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 27        | 0.67%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 25        | 0.62%   |
| AMD Lucienne                                                                             | 25        | 0.62%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 24        | 0.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 0.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1846      | 56.85%  |
| 1 x AMD        | 494       | 15.21%  |
| Intel + Nvidia | 411       | 12.66%  |
| 1 x Nvidia     | 217       | 6.68%   |
| Intel + AMD    | 130       | 4%      |
| 2 x AMD        | 53        | 1.63%   |
| AMD + Nvidia   | 41        | 1.26%   |
| 1 x SiS        | 28        | 0.86%   |
| 1 x VIA        | 11        | 0.34%   |
| Other          | 9         | 0.28%   |
| 2 x Nvidia     | 7         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2819      | 86.55%  |
| Proprietary | 329       | 10.1%   |
| Unknown     | 109       | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2177      | 66.27%  |
| 0.01-0.5   | 502       | 15.28%  |
| 1.01-2.0   | 271       | 8.25%   |
| 0.51-1.0   | 193       | 5.88%   |
| 3.01-4.0   | 90        | 2.74%   |
| 5.01-6.0   | 21        | 0.64%   |
| 7.01-8.0   | 17        | 0.52%   |
| 2.01-3.0   | 12        | 0.37%   |
| 8.01-16.0  | 2         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 644       | 19.53%  |
| LG Display              | 463       | 14.04%  |
| Samsung Electronics     | 432       | 13.1%   |
| Chimei Innolux          | 425       | 12.89%  |
| BOE                     | 408       | 12.37%  |
| Chi Mei Optoelectronics | 123       | 3.73%   |
| Apple                   | 98        | 2.97%   |
| LG Philips              | 80        | 2.43%   |
| Lenovo                  | 57        | 1.73%   |
| Sharp                   | 54        | 1.64%   |
| Goldstar                | 49        | 1.49%   |
| Dell                    | 45        | 1.36%   |
| InfoVision              | 38        | 1.15%   |
| PANDA                   | 34        | 1.03%   |
| Hewlett-Packard         | 22        | 0.67%   |
| CPT                     | 22        | 0.67%   |
| HannStar                | 18        | 0.55%   |
| Toshiba                 | 17        | 0.52%   |
| Sony                    | 15        | 0.45%   |
| Acer                    | 15        | 0.45%   |
| Philips                 | 12        | 0.36%   |
| BenQ                    | 12        | 0.36%   |
| Quanta Display          | 11        | 0.33%   |
| AOC                     | 11        | 0.33%   |
| Vizio                   | 10        | 0.3%    |
| LGD                     | 10        | 0.3%    |
| InnoLux Display         | 10        | 0.3%    |
| Seiko/Epson             | 9         | 0.27%   |
| Ancor Communications    | 9         | 0.27%   |
| Panasonic               | 8         | 0.24%   |
| Eizo                    | 7         | 0.21%   |
| SLD                     | 6         | 0.18%   |
| ASUSTek Computer        | 6         | 0.18%   |
| Iiyama                  | 5         | 0.15%   |
| BOE Technology Group    | 5         | 0.15%   |
| Unknown                 | 5         | 0.15%   |
| ViewSonic               | 4         | 0.12%   |
| Unknown                 | 4         | 0.12%   |
| KDC                     | 4         | 0.12%   |
| IBM                     | 4         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 35        | 1.05%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 27        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 25        | 0.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 20        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 19        | 0.57%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 18        | 0.54%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 17        | 0.51%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.48%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 16        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 15        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 15        | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.45%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.42%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 14        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 13        | 0.39%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 13        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 12        | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.36%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 11        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 11        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 11        | 0.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.3%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 10        | 0.3%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 9         | 0.27%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 9         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.27%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 9         | 0.27%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 9         | 0.27%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.27%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 9         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 8         | 0.24%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.24%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 8         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1322      | 41.15%  |
| 1920x1080 (FHD)    | 936       | 29.13%  |
| 1280x800 (WXGA)    | 247       | 7.69%   |
| 1600x900 (HD+)     | 208       | 6.47%   |
| 1440x900 (WXGA+)   | 88        | 2.74%   |
| 3840x2160 (4K)     | 65        | 2.02%   |
| 1024x600           | 48        | 1.49%   |
| 1920x1200 (WUXGA)  | 37        | 1.15%   |
| 1680x1050 (WSXGA+) | 32        | 1%      |
| 2560x1600          | 30        | 0.93%   |
| 2560x1440 (QHD)    | 26        | 0.81%   |
| 1360x768           | 15        | 0.47%   |
| 1280x1024 (SXGA)   | 14        | 0.44%   |
| 2880x1800          | 13        | 0.4%    |
| 2560x1080          | 11        | 0.34%   |
| 2160x1440          | 11        | 0.34%   |
| 3200x1800 (QHD+)   | 10        | 0.31%   |
| 1024x768 (XGA)     | 10        | 0.31%   |
| Unknown            | 10        | 0.31%   |
| 2256x1504          | 8         | 0.25%   |
| 1280x768           | 8         | 0.25%   |
| 1920x540           | 7         | 0.22%   |
| 3840x2400          | 6         | 0.19%   |
| 3840x1080          | 5         | 0.16%   |
| 3440x1440          | 5         | 0.16%   |
| 1680x945           | 4         | 0.12%   |
| 1400x1050          | 4         | 0.12%   |
| 1920x515           | 3         | 0.09%   |
| 1024x576           | 3         | 0.09%   |
| 5760x1080          | 2         | 0.06%   |
| 3600x1080          | 2         | 0.06%   |
| 2880x1920          | 2         | 0.06%   |
| 2880x1620          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2288x1287          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 5760x2160          | 1         | 0.03%   |
| 4480x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1432      | 43.5%   |
| 13      | 456       | 13.85%  |
| 14      | 388       | 11.79%  |
| 17      | 272       | 8.26%   |
| 11      | 123       | 3.74%   |
| 12      | 90        | 2.73%   |
| Unknown | 74        | 2.25%   |
| 10      | 60        | 1.82%   |
| 24      | 53        | 1.61%   |
| 27      | 50        | 1.52%   |
| 23      | 34        | 1.03%   |
| 21      | 33        | 1%      |
| 18      | 32        | 0.97%   |
| 16      | 32        | 0.97%   |
| 31      | 23        | 0.7%    |
| 34      | 19        | 0.58%   |
| 19      | 16        | 0.49%   |
| 20      | 12        | 0.36%   |
| 54      | 11        | 0.33%   |
| 22      | 11        | 0.33%   |
| 72      | 10        | 0.3%    |
| 40      | 8         | 0.24%   |
| 84      | 6         | 0.18%   |
| 8       | 5         | 0.15%   |
| 32      | 4         | 0.12%   |
| 25      | 4         | 0.12%   |
| 74      | 3         | 0.09%   |
| 52      | 3         | 0.09%   |
| 49      | 3         | 0.09%   |
| 26      | 3         | 0.09%   |
| 58      | 2         | 0.06%   |
| 48      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 37      | 2         | 0.06%   |
| 36      | 2         | 0.06%   |
| 29      | 2         | 0.06%   |
| 86      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |
| 59      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2046      | 62.34%  |
| 201-300     | 472       | 14.38%  |
| 351-400     | 332       | 10.12%  |
| 501-600     | 135       | 4.11%   |
| 401-500     | 101       | 3.08%   |
| Unknown     | 74        | 2.25%   |
| 601-700     | 30        | 0.91%   |
| 1001-1500   | 28        | 0.85%   |
| 701-800     | 26        | 0.79%   |
| 1501-2000   | 19        | 0.58%   |
| 801-900     | 11        | 0.34%   |
| 101-200     | 5         | 0.15%   |
| 901-1000    | 3         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2469      | 80.92%  |
| 16/10   | 442       | 14.49%  |
| Unknown | 55        | 1.8%    |
| 3/2     | 27        | 0.88%   |
| 4/3     | 19        | 0.62%   |
| 21/9    | 17        | 0.56%   |
| 5/4     | 13        | 0.43%   |
| 32/9    | 3         | 0.1%    |
| 3.73    | 3         | 0.1%    |
| 0.62    | 2         | 0.07%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1432      | 43.57%  |
| 81-90          | 703       | 21.39%  |
| 121-130        | 205       | 6.24%   |
| 71-80          | 135       | 4.11%   |
| 51-60          | 123       | 3.74%   |
| 201-250        | 109       | 3.32%   |
| 61-70          | 88        | 2.68%   |
| Unknown        | 74        | 2.25%   |
| 131-140        | 61        | 1.86%   |
| 41-50          | 60        | 1.83%   |
| 301-350        | 52        | 1.58%   |
| 351-500        | 47        | 1.43%   |
| More than 1000 | 44        | 1.34%   |
| 151-200        | 41        | 1.25%   |
| 141-150        | 40        | 1.22%   |
| 501-1000       | 21        | 0.64%   |
| 111-120        | 20        | 0.61%   |
| 91-100         | 14        | 0.43%   |
| 251-300        | 13        | 0.4%    |
| 1-40           | 5         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1390      | 42.86%  |
| 121-160       | 992       | 30.59%  |
| 51-100        | 534       | 16.47%  |
| 161-240       | 157       | 4.84%   |
| Unknown       | 74        | 2.28%   |
| More than 240 | 48        | 1.48%   |
| 1-50          | 48        | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2818      | 85.42%  |
| 2     | 342       | 10.37%  |
| 0     | 113       | 3.43%   |
| 3     | 23        | 0.7%    |
| 4     | 2         | 0.06%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1640      | 31.22%  |
| Intel                             | 1389      | 26.44%  |
| Qualcomm Atheros                  | 862       | 16.41%  |
| Broadcom                          | 510       | 9.71%   |
| Broadcom Limited                  | 165       | 3.14%   |
| Marvell Technology Group          | 95        | 1.81%   |
| Ralink                            | 64        | 1.22%   |
| Nvidia                            | 46        | 0.88%   |
| MediaTek                          | 40        | 0.76%   |
| TP-Link                           | 39        | 0.74%   |
| Silicon Integrated Systems [SiS]  | 29        | 0.55%   |
| Dell                              | 29        | 0.55%   |
| ASIX Electronics                  | 28        | 0.53%   |
| Samsung Electronics               | 27        | 0.51%   |
| Ralink Technology                 | 27        | 0.51%   |
| JMicron Technology                | 26        | 0.49%   |
| Sierra Wireless                   | 19        | 0.36%   |
| Xiaomi                            | 16        | 0.3%    |
| DisplayLink                       | 16        | 0.3%    |
| Hewlett-Packard                   | 15        | 0.29%   |
| Huawei Technologies               | 12        | 0.23%   |
| Qualcomm Atheros Communications   | 11        | 0.21%   |
| Ericsson Business Mobile Networks | 11        | 0.21%   |
| VIA Technologies                  | 10        | 0.19%   |
| OPPO Electronics                  | 9         | 0.17%   |
| NetGear                           | 9         | 0.17%   |
| ASUSTek Computer                  | 9         | 0.17%   |
| Edimax Technology                 | 8         | 0.15%   |
| AMD                               | 8         | 0.15%   |
| Qualcomm                          | 7         | 0.13%   |
| Motorola PCS                      | 7         | 0.13%   |
| Attansic Technology               | 6         | 0.11%   |
| D-Link                            | 5         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| Linksys                           | 4         | 0.08%   |
| Google                            | 4         | 0.08%   |
| D-Link System                     | 4         | 0.08%   |
| T & A Mobile Phones               | 3         | 0.06%   |
| Belkin Components                 | 3         | 0.06%   |
| ZyDAS                             | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 825       | 13.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 441       | 7.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 150       | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 139       | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 128       | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 123       | 1.97%   |
| Intel Wireless 7260                                                     | 120       | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 115       | 1.84%   |
| Intel Wireless 7265                                                     | 86        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 82        | 1.31%   |
| Intel Wireless 8265 / 8275                                              | 80        | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 80        | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                           | 73        | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 64        | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 1.02%   |
| Intel Wireless 8260                                                     | 62        | 0.99%   |
| Intel Wireless 3165                                                     | 61        | 0.98%   |
| Intel Wi-Fi 6 AX200                                                     | 60        | 0.96%   |
| Intel Wi-Fi 6 AX201                                                     | 57        | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 55        | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 55        | 0.88%   |
| Intel WiFi Link 5100                                                    | 54        | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 52        | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 44        | 0.7%    |
| Intel Wireless 3160                                                     | 40        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 39        | 0.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 38        | 0.61%   |
| Intel Ethernet Connection I218-LM                                       | 38        | 0.61%   |
| Intel Ethernet Connection I217-LM                                       | 38        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 36        | 0.58%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 36        | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 35        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 34        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                                | 34        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                                | 34        | 0.54%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1301      | 38.63%  |
| Qualcomm Atheros                  | 727       | 21.59%  |
| Realtek Semiconductor             | 567       | 16.83%  |
| Broadcom                          | 395       | 11.73%  |
| Broadcom Limited                  | 114       | 3.38%   |
| Ralink                            | 64        | 1.9%    |
| MediaTek                          | 32        | 0.95%   |
| TP-Link                           | 30        | 0.89%   |
| Ralink Technology                 | 27        | 0.8%    |
| Dell                              | 21        | 0.62%   |
| Sierra Wireless                   | 19        | 0.56%   |
| Qualcomm Atheros Communications   | 11        | 0.33%   |
| NetGear                           | 9         | 0.27%   |
| Edimax Technology                 | 8         | 0.24%   |
| ASUSTek Computer                  | 8         | 0.24%   |
| D-Link                            | 5         | 0.15%   |
| D-Link System                     | 4         | 0.12%   |
| Linksys                           | 3         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.09%   |
| Belkin Components                 | 3         | 0.09%   |
| ZyDAS                             | 2         | 0.06%   |
| Micro Star International          | 2         | 0.06%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Xiaomi                            | 1         | 0.03%   |
| TRENDnet                          | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Sitecom Europe                    | 1         | 0.03%   |
| Qualcomm                          | 1         | 0.03%   |
| Qcom                              | 1         | 0.03%   |
| Mercucys                          | 1         | 0.03%   |
| Lite-On Technology                | 1         | 0.03%   |
| IMC Networks                      | 1         | 0.03%   |
| Fibocom                           | 1         | 0.03%   |
| Ericsson Business Mobile Networks | 1         | 0.03%   |
| Askey Computer                    | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 150       | 4.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 139       | 4.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 123       | 3.62%   |
| Intel Wireless 7260                                                     | 120       | 3.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 115       | 3.38%   |
| Intel Wireless 7265                                                     | 86        | 2.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 82        | 2.41%   |
| Intel Wireless 8265 / 8275                                              | 80        | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 80        | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 73        | 2.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 1.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 64        | 1.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 1.88%   |
| Intel Wireless 8260                                                     | 62        | 1.82%   |
| Intel Wireless 3165                                                     | 61        | 1.8%    |
| Intel Wi-Fi 6 AX200                                                     | 60        | 1.77%   |
| Intel Wi-Fi 6 AX201                                                     | 57        | 1.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 55        | 1.62%   |
| Intel WiFi Link 5100                                                    | 54        | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 52        | 1.53%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 1.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 44        | 1.29%   |
| Intel Wireless 3160                                                     | 40        | 1.18%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 38        | 1.12%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 1.12%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 36        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 35        | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 34        | 1%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 30        | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 29        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 26        | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 26        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 26        | 0.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 26        | 0.77%   |
| Intel Centrino Wireless-N 2230                                          | 26        | 0.77%   |
| Intel Centrino Advanced-N 6235                                          | 26        | 0.77%   |
| Intel Centrino Advanced-N 6200                                          | 25        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1392      | 50.84%  |
| Intel                                  | 528       | 19.28%  |
| Qualcomm Atheros                       | 224       | 8.18%   |
| Broadcom                               | 179       | 6.54%   |
| Marvell Technology Group               | 95        | 3.47%   |
| Broadcom Limited                       | 56        | 2.05%   |
| Nvidia                                 | 46        | 1.68%   |
| ASIX Electronics                       | 28        | 1.02%   |
| Silicon Integrated Systems [SiS]       | 27        | 0.99%   |
| JMicron Technology                     | 26        | 0.95%   |
| Samsung Electronics                    | 18        | 0.66%   |
| DisplayLink                            | 16        | 0.58%   |
| Xiaomi                                 | 15        | 0.55%   |
| VIA Technologies                       | 10        | 0.37%   |
| TP-Link                                | 9         | 0.33%   |
| OPPO Electronics                       | 9         | 0.33%   |
| Huawei Technologies                    | 9         | 0.33%   |
| MediaTek                               | 7         | 0.26%   |
| Qualcomm                               | 6         | 0.22%   |
| Motorola PCS                           | 6         | 0.22%   |
| Attansic Technology                    | 6         | 0.22%   |
| Google                                 | 4         | 0.15%   |
| Hewlett-Packard                        | 3         | 0.11%   |
| T & A Mobile Phones                    | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.07%   |
| Lenovo                                 | 2         | 0.07%   |
| Davicom Semiconductor                  | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Novatel Wireless                       | 1         | 0.04%   |
| Motorola BCS                           | 1         | 0.04%   |
| Linksys                                | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| GoPro                                  | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 825       | 30%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 441       | 16.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 128       | 4.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 39        | 1.42%   |
| Intel Ethernet Connection I218-LM                                 | 38        | 1.38%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 1.31%   |
| Intel 82577LM Gigabit Network Connection                          | 34        | 1.24%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 1.24%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 1.16%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 31        | 1.13%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 26        | 0.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 26        | 0.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 24        | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.87%   |
| Intel 82566MM Gigabit Network Connection                          | 22        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 22        | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.73%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 20        | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.69%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18        | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 17        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.62%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 17        | 0.62%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 17        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.55%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 15        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.51%   |
| Nvidia MCP67 Ethernet                                             | 14        | 0.51%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.51%   |
| Intel PRO/100 VE Network Connection                               | 13        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3140      | 53.41%  |
| Ethernet | 2639      | 44.89%  |
| Modem    | 94        | 1.6%    |
| Unknown  | 6         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2640      | 78.71%  |
| Ethernet | 713       | 21.26%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2431      | 74.89%  |
| 1     | 671       | 20.67%  |
| 0     | 129       | 3.97%   |
| 3     | 15        | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2532      | 76.94%  |
| Yes  | 759       | 23.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 835       | 38.41%  |
| Qualcomm Atheros Communications | 256       | 11.78%  |
| Realtek Semiconductor           | 250       | 11.5%   |
| Broadcom                        | 164       | 7.54%   |
| IMC Networks                    | 96        | 4.42%   |
| Apple                           | 86        | 3.96%   |
| Foxconn / Hon Hai               | 78        | 3.59%   |
| Lite-On Technology              | 76        | 3.5%    |
| Dell                            | 71        | 3.27%   |
| Hewlett-Packard                 | 67        | 3.08%   |
| Toshiba                         | 43        | 1.98%   |
| Cambridge Silicon Radio         | 31        | 1.43%   |
| Ralink                          | 26        | 1.2%    |
| ASUSTek Computer                | 17        | 0.78%   |
| Realtek                         | 16        | 0.74%   |
| Alps Electric                   | 15        | 0.69%   |
| Foxconn International           | 13        | 0.6%    |
| Askey Computer                  | 7         | 0.32%   |
| Ralink Technology               | 6         | 0.28%   |
| Taiyo Yuden                     | 4         | 0.18%   |
| Dynex                           | 3         | 0.14%   |
| Chicony Electronics             | 3         | 0.14%   |
| Qcom                            | 2         | 0.09%   |
| MediaTek                        | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Unknown                         | 2         | 0.09%   |
| TP-Link                         | 1         | 0.05%   |
| Conwise Technology              | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 425       | 19.52%  |
| Realtek Bluetooth Radio                             | 151       | 6.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 112       | 5.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 110       | 5.05%   |
| Intel AX201 Bluetooth                               | 104       | 4.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 69        | 3.17%   |
| Intel AX200 Bluetooth                               | 58        | 2.66%   |
| Apple Bluetooth Host Controller                     | 50        | 2.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 48        | 2.2%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 41        | 1.88%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 40        | 1.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 37        | 1.7%    |
| IMC Networks Bluetooth Device                       | 35        | 1.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 1.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                    | 27        | 1.24%   |
| Ralink RT3290 Bluetooth                             | 26        | 1.19%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 1.19%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 25        | 1.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 1.1%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 1.06%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.96%   |
| Dell DW375 Bluetooth Module                         | 20        | 0.92%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.92%   |
| Intel AX210 Bluetooth                               | 19        | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.87%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 0.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 18        | 0.83%   |
| IMC Networks Wireless_Device                        | 18        | 0.83%   |
| Apple Bluetooth USB Host Controller                 | 16        | 0.73%   |
| Intel Bluetooth Device                              | 15        | 0.69%   |
| Realtek 802.11ac WLAN Adapter                       | 14        | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 14        | 0.64%   |
| Toshiba Bluetooth Device                            | 13        | 0.6%    |
| Realtek 802.11ac WLAN Adapter                       | 13        | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module   | 13        | 0.6%    |
| Dell Wireless 365 Bluetooth                         | 12        | 0.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.55%   |
| Apple Bluetooth HCI                                 | 12        | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2563      | 70.18%  |
| AMD                                  | 572       | 15.66%  |
| Nvidia                               | 375       | 10.27%  |
| Silicon Integrated Systems [SiS]     | 31        | 0.85%   |
| VIA Technologies                     | 11        | 0.3%    |
| C-Media Electronics                  | 11        | 0.3%    |
| Generalplus Technology               | 8         | 0.22%   |
| Tenx Technology                      | 6         | 0.16%   |
| Realtek Semiconductor                | 5         | 0.14%   |
| Creative Technology                  | 5         | 0.14%   |
| Texas Instruments                    | 4         | 0.11%   |
| SteelSeries ApS                      | 4         | 0.11%   |
| Plantronics                          | 4         | 0.11%   |
| Logitech                             | 4         | 0.11%   |
| Lenovo                               | 4         | 0.11%   |
| PreSonus Audio Electronics           | 3         | 0.08%   |
| JMTek                                | 3         | 0.08%   |
| GN Netcom                            | 3         | 0.08%   |
| Yamaha                               | 2         | 0.05%   |
| Hewlett-Packard                      | 2         | 0.05%   |
| Focusrite-Novation                   | 2         | 0.05%   |
| DSEA A/S                             | 2         | 0.05%   |
| DCMT Technology                      | 2         | 0.05%   |
| Corsair                              | 2         | 0.05%   |
| Apple                                | 2         | 0.05%   |
| AKAI Professional M.I.               | 2         | 0.05%   |
| ZOOM                                 | 1         | 0.03%   |
| XMOS                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Syntek                               | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| Roland                               | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| OPPO Electronics                     | 1         | 0.03%   |
| M-Audio                              | 1         | 0.03%   |
| Kingston Technology                  | 1         | 0.03%   |
| Huawei Technologies                  | 1         | 0.03%   |
| FiiO Electronics Technology          | 1         | 0.03%   |
| Dell                                 | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 300       | 6.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 299       | 6.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 233       | 5.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 203       | 4.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 186       | 4.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 171       | 3.87%   |
| Intel 8 Series HD Audio Controller                                                                | 150       | 3.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 146       | 3.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 145       | 3.28%   |
| AMD FCH Azalia Controller                                                                         | 140       | 3.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 133       | 3.01%   |
| Intel Broadwell-U Audio Controller                                                                | 107       | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 106       | 2.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 101       | 2.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 89        | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 86        | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 85        | 1.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 83        | 1.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 80        | 1.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 79        | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 74        | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 72        | 1.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 64        | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 56        | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 55        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 53        | 1.2%    |
| AMD High Definition Audio Controller                                                              | 51        | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 50        | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 47        | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 43        | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 41        | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 38        | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 32        | 0.72%   |
| AMD Wrestler HDMI Audio                                                                           | 32        | 0.72%   |
| AMD Trinity HDMI Audio Controller                                                                 | 28        | 0.63%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 26        | 0.59%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 26        | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 24        | 0.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 24        | 0.54%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 24        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 205       | 25.53%  |
| SK hynix               | 189       | 23.54%  |
| Micron Technology      | 95        | 11.83%  |
| Unknown                | 74        | 9.22%   |
| Kingston               | 59        | 7.35%   |
| Crucial                | 24        | 2.99%   |
| Unknown (ABCD)         | 23        | 2.86%   |
| Elpida                 | 16        | 1.99%   |
| Ramaxel Technology     | 15        | 1.87%   |
| Nanya Technology       | 15        | 1.87%   |
| A-DATA Technology      | 15        | 1.87%   |
| Smart                  | 10        | 1.25%   |
| Corsair                | 5         | 0.62%   |
| Qimonda                | 4         | 0.5%    |
| Timetec                | 3         | 0.37%   |
| Team                   | 3         | 0.37%   |
| G.Skill                | 3         | 0.37%   |
| Unknown                | 3         | 0.37%   |
| Transcend              | 2         | 0.25%   |
| Teikon                 | 2         | 0.25%   |
| Smart Brazil           | 2         | 0.25%   |
| SHARETRONIC            | 2         | 0.25%   |
| Patriot                | 2         | 0.25%   |
| High Bridge            | 2         | 0.25%   |
| ff                     | 2         | 0.25%   |
| fef5                   | 2         | 0.25%   |
| 4ea5                   | 2         | 0.25%   |
| Walton Chaintech       | 1         | 0.12%   |
| Unknown (08B5)         | 1         | 0.12%   |
| Unknown (07F7)         | 1         | 0.12%   |
| Unknown (000080B30080) | 1         | 0.12%   |
| Toshiba                | 1         | 0.12%   |
| Strontium              | 1         | 0.12%   |
| Silicon Power          | 1         | 0.12%   |
| PUSKILL                | 1         | 0.12%   |
| ProMos/Mosel Vitelic   | 1         | 0.12%   |
| pqi                    | 1         | 0.12%   |
| PNY                    | 1         | 0.12%   |
| Netlist                | 1         | 0.12%   |
| Nayna                  | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 20        | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 1.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 1.17%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 10        | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 1.06%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 8         | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.94%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.82%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.82%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.7%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 3200MT/s        | 5         | 0.59%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.59%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.59%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 5         | 0.59%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 4         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.47%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR 975MT/s             | 4         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.47%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 261       | 38.44%  |
| DDR4    | 234       | 34.46%  |
| DDR2    | 70        | 10.31%  |
| LPDDR4  | 43        | 6.33%   |
| SDRAM   | 24        | 3.53%   |
| LPDDR3  | 22        | 3.24%   |
| DRAM    | 6         | 0.88%   |
| Unknown | 6         | 0.88%   |
| DDR     | 5         | 0.74%   |
| LPDDR5  | 4         | 0.59%   |
| DDR5    | 4         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 586       | 87.07%  |
| Row Of Chips | 56        | 8.32%   |
| DIMM         | 14        | 2.08%   |
| Chip         | 9         | 1.34%   |
| Unknown      | 8         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 246       | 32.16%  |
| 4096  | 232       | 30.33%  |
| 2048  | 154       | 20.13%  |
| 16384 | 60        | 7.84%   |
| 1024  | 51        | 6.67%   |
| 512   | 12        | 1.57%   |
| 32768 | 8         | 1.05%   |
| 256   | 2         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 176       | 23.88%  |
| 2667    | 110       | 14.93%  |
| 3200    | 94        | 12.75%  |
| 2400    | 62        | 8.41%   |
| 1334    | 40        | 5.43%   |
| 667     | 38        | 5.16%   |
| 1333    | 31        | 4.21%   |
| 2133    | 30        | 4.07%   |
| Unknown | 27        | 3.66%   |
| 1066    | 16        | 2.17%   |
| 800     | 13        | 1.76%   |
| 4267    | 11        | 1.49%   |
| 975     | 11        | 1.49%   |
| 4199    | 10        | 1.36%   |
| 3266    | 10        | 1.36%   |
| 2048    | 10        | 1.36%   |
| 533     | 10        | 1.36%   |
| 1867    | 8         | 1.09%   |
| 1067    | 7         | 0.95%   |
| 6400    | 5         | 0.68%   |
| 8400    | 4         | 0.54%   |
| 4800    | 4         | 0.54%   |
| 400     | 3         | 0.41%   |
| 3733    | 2         | 0.27%   |
| 5600    | 1         | 0.14%   |
| 4266    | 1         | 0.14%   |
| 2933    | 1         | 0.14%   |
| 1866    | 1         | 0.14%   |
| 1639    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 39.39%  |
| Seiko Epson           | 6         | 18.18%  |
| Canon                 | 6         | 18.18%  |
| Brother Industries    | 3         | 9.09%   |
| Samsung Electronics   | 2         | 6.06%   |
| Zebra                 | 1         | 3.03%   |
| STMicroelectronics    | 1         | 3.03%   |
| Lexmark International | 1         | 3.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series                                 | 2         | 6.06%   |
| HP Deskjet 1510                                           | 2         | 6.06%   |
| HP DeskJet 1110 series                                    | 2         | 6.06%   |
| Zebra ZP 450 Printer                                      | 1         | 3.03%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.03%   |
| Seiko Epson XP-235 Series                                 | 1         | 3.03%   |
| Seiko Epson WF-2010 Series                                | 1         | 3.03%   |
| Seiko Epson Printer                                       | 1         | 3.03%   |
| Seiko Epson L3110 Series                                  | 1         | 3.03%   |
| Seiko Epson ET-2810 Series                                | 1         | 3.03%   |
| Seiko Epson AcuLaser C1700                                | 1         | 3.03%   |
| Samsung M2020 Series                                      | 1         | 3.03%   |
| Samsung CLX-3300 Series                                   | 1         | 3.03%   |
| Lexmark International 2400 series                         | 1         | 3.03%   |
| HP Laserjet P1505                                         | 1         | 3.03%   |
| HP LaserJet P1102                                         | 1         | 3.03%   |
| HP LaserJet 1200                                          | 1         | 3.03%   |
| HP LaserJet 1020                                          | 1         | 3.03%   |
| HP LaserJet 1000                                          | 1         | 3.03%   |
| HP DeskJet 2700 series                                    | 1         | 3.03%   |
| HP DeskJet 2300 series                                    | 1         | 3.03%   |
| Canon TS3100 series                                       | 1         | 3.03%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.03%   |
| Canon PIXMA MX340                                         | 1         | 3.03%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.03%   |
| Canon PIXMA MG3000 series                                 | 1         | 3.03%   |
| Canon MG2100 series                                       | 1         | 3.03%   |
| Brother MFC-L2730DW series                                | 1         | 3.03%   |
| Brother MFC-J5730DW                                       | 1         | 3.03%   |
| Brother DCP-T300                                          | 1         | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 50%     |
| Canon       | 3         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 3         | 50%     |
| Canon CanoScan LiDE 90                      | 1         | 16.67%  |
| Canon CanoScan LIDE 25                      | 1         | 16.67%  |
| Canon CanoScan LiDE 200                     | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 660       | 24.92%  |
| Microdia                               | 246       | 9.29%   |
| Realtek Semiconductor                  | 217       | 8.19%   |
| IMC Networks                           | 208       | 7.85%   |
| Bison Electronics                      | 150       | 5.66%   |
| Sunplus Innovation Technology          | 148       | 5.59%   |
| Suyin                                  | 132       | 4.98%   |
| Cheng Uei Precision Industry (Foxlink) | 119       | 4.49%   |
| Quanta                                 | 117       | 4.42%   |
| Apple                                  | 76        | 2.87%   |
| Syntek                                 | 71        | 2.68%   |
| Silicon Motion                         | 58        | 2.19%   |
| Lite-On Technology                     | 53        | 2%      |
| Alcor Micro                            | 50        | 1.89%   |
| Acer                                   | 45        | 1.7%    |
| Ricoh                                  | 35        | 1.32%   |
| Luxvisions Innotech Limited            | 24        | 0.91%   |
| Logitech                               | 20        | 0.76%   |
| ALi                                    | 19        | 0.72%   |
| Importek                               | 18        | 0.68%   |
| Samsung Electronics                    | 16        | 0.6%    |
| Sonix Technology                       | 15        | 0.57%   |
| Primax Electronics                     | 15        | 0.57%   |
| icSpring                               | 14        | 0.53%   |
| Z-Star Microelectronics                | 13        | 0.49%   |
| Lenovo                                 | 11        | 0.42%   |
| OmniVision Technologies                | 10        | 0.38%   |
| SunplusIT                              | 9         | 0.34%   |
| GEMBIRD                                | 9         | 0.34%   |
| Genesys Logic                          | 6         | 0.23%   |
| Y Media                                | 5         | 0.19%   |
| Microsoft                              | 5         | 0.19%   |
| Sunplus Technology                     | 4         | 0.15%   |
| Intel                                  | 4         | 0.15%   |
| Generalplus Technology                 | 3         | 0.11%   |
| ARC International                      | 3         | 0.11%   |
| Unknown                                | 3         | 0.11%   |
| YGTek                                  | 2         | 0.08%   |
| Tripath Technology                     | 2         | 0.08%   |
| LG Electronics                         | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 92        | 3.47%   |
| Microdia Integrated_Webcam_HD                    | 52        | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                | 49        | 1.85%   |
| Chicony HD WebCam                                | 42        | 1.58%   |
| Realtek Integrated_Webcam_HD                     | 41        | 1.54%   |
| Bison Integrated Camera                          | 38        | 1.43%   |
| Chicony HP Truevision HD                         | 37        | 1.39%   |
| Microdia Integrated Webcam                       | 36        | 1.36%   |
| Syntek Integrated Camera                         | 35        | 1.32%   |
| Realtek USB Camera                               | 33        | 1.24%   |
| IMC Networks Integrated Camera                   | 32        | 1.21%   |
| Chicony TOSHIBA Web Camera - HD                  | 32        | 1.21%   |
| Sunplus Integrated_Webcam_HD                     | 30        | 1.13%   |
| Bison Lenovo EasyCamera                          | 30        | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 29        | 1.09%   |
| Chicony USB 2.0 Camera                           | 26        | 0.98%   |
| Chicony HP TrueVision HD Camera                  | 25        | 0.94%   |
| Realtek Integrated Webcam                        | 23        | 0.87%   |
| Chicony Lenovo EasyCamera                        | 22        | 0.83%   |
| Chicony EasyCamera                               | 22        | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 22        | 0.83%   |
| Alcor Micro USB 2.0 Camera                       | 22        | 0.83%   |
| Sunplus HD WebCam                                | 21        | 0.79%   |
| Lite-On HP HD Camera                             | 21        | 0.79%   |
| Chicony VGA WebCam                               | 21        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 21        | 0.79%   |
| Apple FaceTime HD Camera                         | 20        | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                    | 19        | 0.72%   |
| Chicony HP Webcam                                | 19        | 0.72%   |
| Chicony HP HD Webcam                             | 19        | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 18        | 0.68%   |
| Quanta HP Webcam                                 | 18        | 0.68%   |
| Apple Built-in iSight                            | 18        | 0.68%   |
| Suyin HP Truevision HD                           | 17        | 0.64%   |
| Chicony HP HD Camera                             | 17        | 0.64%   |
| Chicony CNF9055 Toshiba Webcam                   | 17        | 0.64%   |
| Samsung Galaxy series, misc. (MTP mode)          | 16        | 0.6%    |
| Realtek HP Truevision HD                         | 16        | 0.6%    |
| Quanta HP TrueVision HD Camera                   | 16        | 0.6%    |
| Microdia Sonix USB 2.0 Camera                    | 16        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 212       | 46.8%   |
| AuthenTec                          | 66        | 14.57%  |
| Shenzhen Goodix Technology         | 45        | 9.93%   |
| Synaptics                          | 41        | 9.05%   |
| Upek                               | 35        | 7.73%   |
| Elan Microelectronics              | 21        | 4.64%   |
| STMicroelectronics                 | 19        | 4.19%   |
| LighTuning Technology              | 8         | 1.77%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.66%   |
| Samsung Electronics                | 2         | 0.44%   |
| Focal-systems.Corp                 | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 47        | 10.38%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 7.28%   |
| Shenzhen Goodix  Fingerprint Device                                        | 33        | 7.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 5.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 4.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 22        | 4.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.64%   |
| Validity Sensors VFS491                                                    | 20        | 4.42%   |
| STMicroelectronics Fingerprint Reader                                      | 19        | 4.19%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 3.97%   |
| AuthenTec AES2810                                                          | 18        | 3.97%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.65%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.43%   |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 2.43%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.21%   |
| AuthenTec AES1600                                                          | 10        | 2.21%   |
| Elan ELAN:Fingerprint                                                      | 9         | 1.99%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 1.77%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.55%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 1.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.1%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 1.1%    |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.88%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.88%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.66%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.66%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.44%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.44%   |
| Synaptics WBDI                                                             | 2         | 0.44%   |
| Synaptics  WBDI                                                            | 2         | 0.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.44%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 108       | 54%     |
| Alcor Micro                       | 35        | 17.5%   |
| O2 Micro                          | 29        | 14.5%   |
| Lenovo                            | 9         | 4.5%    |
| Upek                              | 8         | 4%      |
| Yubico.com                        | 2         | 1%      |
| VASCO Data Security International | 2         | 1%      |
| SCM Microsystems                  | 2         | 1%      |
| Realtek Semiconductor             | 2         | 1%      |
| OmniKey                           | 1         | 0.5%    |
| Gemalto (was Gemplus)             | 1         | 0.5%    |
| Fujitsu Siemens Computers         | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 48        | 23.88%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 16.92%  |
| Broadcom 5880                                                                | 28        | 13.93%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 12.94%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 11.94%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.48%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 3.98%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.49%   |
| Broadcom 58200                                                               | 5         | 2.49%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1%      |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1%      |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1%      |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1%      |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.5%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.5%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2069      | 62.83%  |
| 1     | 960       | 29.15%  |
| 2     | 230       | 6.98%   |
| 3     | 31        | 0.94%   |
| 4     | 2         | 0.06%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 446       | 30.34%  |
| Graphics card            | 335       | 22.79%  |
| Chipcard                 | 191       | 12.99%  |
| Net/wireless             | 178       | 12.11%  |
| Multimedia controller    | 114       | 7.76%   |
| Storage                  | 46        | 3.13%   |
| Modem                    | 38        | 2.59%   |
| Bluetooth                | 35        | 2.38%   |
| Communication controller | 17        | 1.16%   |
| Sound                    | 16        | 1.09%   |
| Camera                   | 15        | 1.02%   |
| Flash memory             | 13        | 0.88%   |
| Net/ethernet             | 8         | 0.54%   |
| Card reader              | 6         | 0.41%   |
| Network                  | 4         | 0.27%   |
| Storage/nvme             | 2         | 0.14%   |
| Storage/ide              | 2         | 0.14%   |
| Dvb card                 | 2         | 0.14%   |
| Unclassified device      | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |

