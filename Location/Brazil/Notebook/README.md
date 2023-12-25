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

Total: 12485

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [19f8d4f0b4](https://linux-hardware.org/?probe=19f8d4f0b4) | Dec 24, 2023 |
| Samsung       | RV415/RV515                 | [da980644b4](https://linux-hardware.org/?probe=da980644b4) | Dec 24, 2023 |
| Notebook      | NJx0MU                      | [b57fdd9854](https://linux-hardware.org/?probe=b57fdd9854) | Dec 24, 2023 |
| Acer          | Nitro AN515-44              | [cc87c11e7b](https://linux-hardware.org/?probe=cc87c11e7b) | Dec 24, 2023 |
| Acer          | Nitro AN515-51              | [52a7a4d6d8](https://linux-hardware.org/?probe=52a7a4d6d8) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [d409d2fe79](https://linux-hardware.org/?probe=d409d2fe79) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [eae7bab112](https://linux-hardware.org/?probe=eae7bab112) | Dec 23, 2023 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [d65cca0578](https://linux-hardware.org/?probe=d65cca0578) | Dec 22, 2023 |
| Positivo      | W940TU                      | [40dff18a74](https://linux-hardware.org/?probe=40dff18a74) | Dec 22, 2023 |
| Acer          | Nitro AN515-44              | [5f1c04a086](https://linux-hardware.org/?probe=5f1c04a086) | Dec 22, 2023 |
| Dell          | Inspiron 7572               | [b6a03a82a6](https://linux-hardware.org/?probe=b6a03a82a6) | Dec 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [808fe0568d](https://linux-hardware.org/?probe=808fe0568d) | Dec 21, 2023 |
| Dell          | Inspiron 5448               | [edf818740d](https://linux-hardware.org/?probe=edf818740d) | Dec 21, 2023 |
| Dell          | Vostro 3550                 | [2c9d7daa8b](https://linux-hardware.org/?probe=2c9d7daa8b) | Dec 21, 2023 |
| Dell          | Inspiron 7572               | [cd9385a64b](https://linux-hardware.org/?probe=cd9385a64b) | Dec 21, 2023 |
| Alienware     | m16 R1 AMD                  | [8fc737975c](https://linux-hardware.org/?probe=8fc737975c) | Dec 21, 2023 |
| Valve         | Jupiter                     | [aecbb83cd6](https://linux-hardware.org/?probe=aecbb83cd6) | Dec 20, 2023 |
| ASUSTek       | X556URK                     | [b4f01c5bd5](https://linux-hardware.org/?probe=b4f01c5bd5) | Dec 19, 2023 |
| Daten Tecn... | DT02-M4                     | [8f754589f6](https://linux-hardware.org/?probe=8f754589f6) | Dec 19, 2023 |
| Acer          | Nitro AN515-43              | [963de967ae](https://linux-hardware.org/?probe=963de967ae) | Dec 19, 2023 |
| Acer          | Aspire E5-571               | [55a802f43c](https://linux-hardware.org/?probe=55a802f43c) | Dec 18, 2023 |
| Dell          | Latitude 3420               | [5fdda723cd](https://linux-hardware.org/?probe=5fdda723cd) | Dec 18, 2023 |
| GPD           | G1619-04                    | [63b517665b](https://linux-hardware.org/?probe=63b517665b) | Dec 18, 2023 |
| Toshiba       | IS 1413G                    | [458a8fb3f1](https://linux-hardware.org/?probe=458a8fb3f1) | Dec 18, 2023 |
| Dell          | G3 3590                     | [15decf2dfc](https://linux-hardware.org/?probe=15decf2dfc) | Dec 18, 2023 |
| Samsung       | 550P5C/550P7C               | [b06e8fbef4](https://linux-hardware.org/?probe=b06e8fbef4) | Dec 18, 2023 |
| Acer          | Nitro AN515-57              | [1bd5e5e36f](https://linux-hardware.org/?probe=1bd5e5e36f) | Dec 18, 2023 |
| Compal        | PBL1011                     | [8983f2e331](https://linux-hardware.org/?probe=8983f2e331) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | [c18f5d3a21](https://linux-hardware.org/?probe=c18f5d3a21) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | [982ae3655c](https://linux-hardware.org/?probe=982ae3655c) | Dec 18, 2023 |
| Notebook      | NJx0MU                      | [1446130ae9](https://linux-hardware.org/?probe=1446130ae9) | Dec 17, 2023 |
| Toshiba       | IS 1413G                    | [dde306e444](https://linux-hardware.org/?probe=dde306e444) | Dec 17, 2023 |
| Notebook      | NJx0MU                      | [80281cb193](https://linux-hardware.org/?probe=80281cb193) | Dec 17, 2023 |
| Dell          | Inspiron N4030              | [a77869199a](https://linux-hardware.org/?probe=a77869199a) | Dec 17, 2023 |
| Samsung       | 550XDA                      | [10ec283ed4](https://linux-hardware.org/?probe=10ec283ed4) | Dec 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [be717cf064](https://linux-hardware.org/?probe=be717cf064) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | [570a822273](https://linux-hardware.org/?probe=570a822273) | Dec 16, 2023 |
| Dell          | Inspiron 3583               | [890cf9cc41](https://linux-hardware.org/?probe=890cf9cc41) | Dec 16, 2023 |
| Dell          | Vostro 5490                 | [ca117be9d4](https://linux-hardware.org/?probe=ca117be9d4) | Dec 16, 2023 |
| Acer          | Nitro AN515-51              | [de83793263](https://linux-hardware.org/?probe=de83793263) | Dec 16, 2023 |
| Toshiba       | IS 1413G                    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Dell          | Inspiron 1525               | [b9daaa5978](https://linux-hardware.org/?probe=b9daaa5978) | Dec 15, 2023 |
| Acer          | Nitro AN515-57              | [7e43febcae](https://linux-hardware.org/?probe=7e43febcae) | Dec 15, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a043c13550](https://linux-hardware.org/?probe=a043c13550) | Dec 14, 2023 |
| Acer          | Nitro AN517-54              | [c16cb0947e](https://linux-hardware.org/?probe=c16cb0947e) | Dec 14, 2023 |
| Dell          | G15 5520                    | [12b6fa0914](https://linux-hardware.org/?probe=12b6fa0914) | Dec 14, 2023 |
| Dell          | Inspiron 7560               | [83034fb404](https://linux-hardware.org/?probe=83034fb404) | Dec 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d2b1e67451](https://linux-hardware.org/?probe=d2b1e67451) | Dec 14, 2023 |
| Dell          | G15 5520                    | [d212fe82aa](https://linux-hardware.org/?probe=d212fe82aa) | Dec 14, 2023 |
| Acer          | Nitro AN515-45              | [1ff0d683f4](https://linux-hardware.org/?probe=1ff0d683f4) | Dec 13, 2023 |
| Acer          | Nitro AN515-51              | [1522c84fb7](https://linux-hardware.org/?probe=1522c84fb7) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [bd8707be32](https://linux-hardware.org/?probe=bd8707be32) | Dec 13, 2023 |
| Dell          | Latitude E5470              | [cc7982deb0](https://linux-hardware.org/?probe=cc7982deb0) | Dec 13, 2023 |
| Dell          | Inspiron 15 5510            | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| Dell          | Latitude 3420               | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| Dell          | System XPS L502X            | [75c612f90d](https://linux-hardware.org/?probe=75c612f90d) | Dec 13, 2023 |
| Dell          | G3 3590                     | [e764bfc760](https://linux-hardware.org/?probe=e764bfc760) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | [74dc572dd7](https://linux-hardware.org/?probe=74dc572dd7) | Dec 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [74c0490d28](https://linux-hardware.org/?probe=74c0490d28) | Dec 12, 2023 |
| Positivo      | H14BT58                     | [74530bb40a](https://linux-hardware.org/?probe=74530bb40a) | Dec 12, 2023 |
| Positivo      | CHT12CP                     | [d9d4327551](https://linux-hardware.org/?probe=d9d4327551) | Dec 12, 2023 |
| Acer          | Predator G3-572             | [7de00d4eab](https://linux-hardware.org/?probe=7de00d4eab) | Dec 12, 2023 |
| Acer          | Aspire A315-510P            | [e2bdedca29](https://linux-hardware.org/?probe=e2bdedca29) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [843d02bea4](https://linux-hardware.org/?probe=843d02bea4) | Dec 11, 2023 |
| Positivo      | Q464C                       | [47071c986c](https://linux-hardware.org/?probe=47071c986c) | Dec 11, 2023 |
| Samsung       | Q470C/500P4C                | [f904c4ea67](https://linux-hardware.org/?probe=f904c4ea67) | Dec 11, 2023 |
| Dell          | Inspiron 3442               | [deced1a058](https://linux-hardware.org/?probe=deced1a058) | Dec 11, 2023 |
| Dell          | System XPS L502X            | [a612ae1881](https://linux-hardware.org/?probe=a612ae1881) | Dec 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [4af70588d9](https://linux-hardware.org/?probe=4af70588d9) | Dec 10, 2023 |
| Acer          | Aspire 5750                 | [bedb502b74](https://linux-hardware.org/?probe=bedb502b74) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| MSI           | Modern 15 B7M               | [cc6c41e7fd](https://linux-hardware.org/?probe=cc6c41e7fd) | Dec 10, 2023 |
| Toshiba       | IS 1412                     | [b5f0453a4b](https://linux-hardware.org/?probe=b5f0453a4b) | Dec 09, 2023 |
| Dell          | Vostro 3550                 | [f1a1a0841c](https://linux-hardware.org/?probe=f1a1a0841c) | Dec 08, 2023 |
| Dell          | Inspiron 15 3520            | [6452783d8a](https://linux-hardware.org/?probe=6452783d8a) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9f878d8d30](https://linux-hardware.org/?probe=9f878d8d30) | Dec 08, 2023 |
| Acer          | Aspire A315-41              | [778176acbe](https://linux-hardware.org/?probe=778176acbe) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [88ed0c98a0](https://linux-hardware.org/?probe=88ed0c98a0) | Dec 07, 2023 |
| Samsung       | 550XDA                      | [6501dce45c](https://linux-hardware.org/?probe=6501dce45c) | Dec 07, 2023 |
| Positivo      | Q4128C-S                    | [018aab637c](https://linux-hardware.org/?probe=018aab637c) | Dec 07, 2023 |
| Positivo B... | VJFE59F11X-B1011H           | [2f497e2103](https://linux-hardware.org/?probe=2f497e2103) | Dec 06, 2023 |
| ASUSTek       | K45A                        | [a5e618b2f9](https://linux-hardware.org/?probe=a5e618b2f9) | Dec 06, 2023 |
| ASUSTek       | K45A                        | [96d1051ede](https://linux-hardware.org/?probe=96d1051ede) | Dec 06, 2023 |
| Acer          | Nitro AN515-57              | [5b38f6200a](https://linux-hardware.org/?probe=5b38f6200a) | Dec 06, 2023 |
| Dell          | Inspiron 7472               | [ef77efb220](https://linux-hardware.org/?probe=ef77efb220) | Dec 06, 2023 |
| Dell          | Precision 7720              | [da0616987d](https://linux-hardware.org/?probe=da0616987d) | Dec 05, 2023 |
| Samsung       | RV419/RV420                 | [5f29bdfad1](https://linux-hardware.org/?probe=5f29bdfad1) | Dec 05, 2023 |
| Acer          | Aspire AV15-51              | [2691ac3f7d](https://linux-hardware.org/?probe=2691ac3f7d) | Dec 05, 2023 |
| Dell          | G7 7588                     | [8564f8e395](https://linux-hardware.org/?probe=8564f8e395) | Dec 05, 2023 |
| Valve         | Jupiter                     | [4ffa224365](https://linux-hardware.org/?probe=4ffa224365) | Dec 05, 2023 |
| Acer          | Aspire AV15-51              | [758a277d68](https://linux-hardware.org/?probe=758a277d68) | Dec 04, 2023 |
| Dell          | Inspiron 5567               | [03fe12170c](https://linux-hardware.org/?probe=03fe12170c) | Dec 04, 2023 |
| Samsung       | 550XDA                      | [b5bfe47576](https://linux-hardware.org/?probe=b5bfe47576) | Dec 04, 2023 |
| MSI           | Modern 15 B7M               | [f1757e8248](https://linux-hardware.org/?probe=f1757e8248) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [3222457362](https://linux-hardware.org/?probe=3222457362) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | [318a41e343](https://linux-hardware.org/?probe=318a41e343) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a7c5eb788c](https://linux-hardware.org/?probe=a7c5eb788c) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da6b435afa](https://linux-hardware.org/?probe=da6b435afa) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | [c4839c409c](https://linux-hardware.org/?probe=c4839c409c) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | [0dc4701502](https://linux-hardware.org/?probe=0dc4701502) | Dec 02, 2023 |
| Dell          | Latitude 3540               | [64067574ad](https://linux-hardware.org/?probe=64067574ad) | Dec 02, 2023 |
| Dell          | G15 5510                    | [bdfca2648a](https://linux-hardware.org/?probe=bdfca2648a) | Dec 02, 2023 |
| Dell          | Vostro 3525                 | [6d84ce1284](https://linux-hardware.org/?probe=6d84ce1284) | Dec 01, 2023 |
| Dell          | Inspiron 15-3567            | [520e1bdfa8](https://linux-hardware.org/?probe=520e1bdfa8) | Dec 01, 2023 |
| Acer          | Aspire A515-45              | [9875097d6a](https://linux-hardware.org/?probe=9875097d6a) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [32a0e568cc](https://linux-hardware.org/?probe=32a0e568cc) | Dec 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [dcbc9946d8](https://linux-hardware.org/?probe=dcbc9946d8) | Dec 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [95221dfaaf](https://linux-hardware.org/?probe=95221dfaaf) | Dec 01, 2023 |
| Dell          | Vostro 1510                 | [65480134bd](https://linux-hardware.org/?probe=65480134bd) | Dec 01, 2023 |
| HP            | Presario CQ43               | [5edf6adf85](https://linux-hardware.org/?probe=5edf6adf85) | Dec 01, 2023 |
| Dell          | Latitude E5410              | [074e7de8d8](https://linux-hardware.org/?probe=074e7de8d8) | Dec 01, 2023 |
| Multilaser    | PC31X                       | [1f63edb2f9](https://linux-hardware.org/?probe=1f63edb2f9) | Dec 01, 2023 |
| Dell          | Inspiron 15 3515            | [162854d649](https://linux-hardware.org/?probe=162854d649) | Nov 30, 2023 |
| Acer          | Predator PH315-52           | [bb1fc18586](https://linux-hardware.org/?probe=bb1fc18586) | Nov 30, 2023 |
| Samsung       | 550XDA                      | [5778304f73](https://linux-hardware.org/?probe=5778304f73) | Nov 30, 2023 |
| Dell          | G15 5511                    | [f77d3ad016](https://linux-hardware.org/?probe=f77d3ad016) | Nov 30, 2023 |
| Dell          | Vostro 3500                 | [bd6506d274](https://linux-hardware.org/?probe=bd6506d274) | Nov 30, 2023 |
| AMI           | AMD                         | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| Avell High... | B.ON                        | [22a1430347](https://linux-hardware.org/?probe=22a1430347) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d9b203868f](https://linux-hardware.org/?probe=d9b203868f) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7db0c2781b](https://linux-hardware.org/?probe=7db0c2781b) | Nov 29, 2023 |
| HP            | Pavilion dv6                | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| Acer          | Aspire 4732Z                | [6a849535fb](https://linux-hardware.org/?probe=6a849535fb) | Nov 29, 2023 |
| Dell          | Inspiron 15 3515            | [20007eacdb](https://linux-hardware.org/?probe=20007eacdb) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | [e41d34ea1c](https://linux-hardware.org/?probe=e41d34ea1c) | Nov 28, 2023 |
| HP            | Presario CQ43               | [eaab50d59c](https://linux-hardware.org/?probe=eaab50d59c) | Nov 28, 2023 |
| Dell          | Vostro 3583                 | [68c6f002f5](https://linux-hardware.org/?probe=68c6f002f5) | Nov 28, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [1eda316922](https://linux-hardware.org/?probe=1eda316922) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| Dell          | Inspiron 5566               | [df3eed7cc0](https://linux-hardware.org/?probe=df3eed7cc0) | Nov 27, 2023 |
| Dell          | Vostro 1510                 | [8cb1e628c2](https://linux-hardware.org/?probe=8cb1e628c2) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2522F25       | [d6988c10b5](https://linux-hardware.org/?probe=d6988c10b5) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2522F25       | [aadbbad61f](https://linux-hardware.org/?probe=aadbbad61f) | Nov 27, 2023 |
| Valve         | Jupiter                     | [a208b7bd3a](https://linux-hardware.org/?probe=a208b7bd3a) | Nov 26, 2023 |
| Philco        | 14H                         | [f4256fe390](https://linux-hardware.org/?probe=f4256fe390) | Nov 26, 2023 |
| Acer          | Swift SF514-56T             | [687fc34fd5](https://linux-hardware.org/?probe=687fc34fd5) | Nov 26, 2023 |
| Lenovo        | Unknown                     | [504a4bd033](https://linux-hardware.org/?probe=504a4bd033) | Nov 26, 2023 |
| HP            | Pavilion 14                 | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0f05f2568e](https://linux-hardware.org/?probe=0f05f2568e) | Nov 25, 2023 |
| Positivo      | C41TF                       | [09be1cbd3a](https://linux-hardware.org/?probe=09be1cbd3a) | Nov 25, 2023 |
| Dell          | Latitude 7430               | [1074b5c005](https://linux-hardware.org/?probe=1074b5c005) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0c42791b33](https://linux-hardware.org/?probe=0c42791b33) | Nov 25, 2023 |
| Dell          | Inspiron 5468               | [3422c91458](https://linux-hardware.org/?probe=3422c91458) | Nov 24, 2023 |
| Positivo      | S14CT01                     | [c1b3f4bc65](https://linux-hardware.org/?probe=c1b3f4bc65) | Nov 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [d69be34130](https://linux-hardware.org/?probe=d69be34130) | Nov 24, 2023 |
| A14CR         | Unknown                     | [c0924a368e](https://linux-hardware.org/?probe=c0924a368e) | Nov 24, 2023 |
| HP            | G62                         | [9d6424c4cc](https://linux-hardware.org/?probe=9d6424c4cc) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [199f9814a0](https://linux-hardware.org/?probe=199f9814a0) | Nov 24, 2023 |
| Samsung       | 960XFH                      | [2ad3d93589](https://linux-hardware.org/?probe=2ad3d93589) | Nov 24, 2023 |
| Compaq        | 420                         | [651aec3a5c](https://linux-hardware.org/?probe=651aec3a5c) | Nov 24, 2023 |
| Compaq        | 420                         | [df09fad001](https://linux-hardware.org/?probe=df09fad001) | Nov 23, 2023 |
| Samsung       | 270E5J/2570EJ               | [d6ab9c6df5](https://linux-hardware.org/?probe=d6ab9c6df5) | Nov 23, 2023 |
| Avell High... | A70 MOB                     | [d936aa95ef](https://linux-hardware.org/?probe=d936aa95ef) | Nov 23, 2023 |
| HP            | ProBook 4430s               | [847fb6fb22](https://linux-hardware.org/?probe=847fb6fb22) | Nov 23, 2023 |
| Acer          | Aspire A515-57              | [676da26c54](https://linux-hardware.org/?probe=676da26c54) | Nov 23, 2023 |
| HP            | ProBook 4430s               | [1b34dd379f](https://linux-hardware.org/?probe=1b34dd379f) | Nov 23, 2023 |
| HP            | 430                         | [a5ad87647a](https://linux-hardware.org/?probe=a5ad87647a) | Nov 23, 2023 |
| Acer          | Aspire ES1-531              | [01d429e284](https://linux-hardware.org/?probe=01d429e284) | Nov 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [8d944b2cf7](https://linux-hardware.org/?probe=8d944b2cf7) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [93a21a43d5](https://linux-hardware.org/?probe=93a21a43d5) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e95ef90dec](https://linux-hardware.org/?probe=e95ef90dec) | Nov 22, 2023 |
| Dell          | Inspiron 5502               | [eb86dc0b36](https://linux-hardware.org/?probe=eb86dc0b36) | Nov 22, 2023 |
| Dell          | Latitude 7430               | [44557e3a83](https://linux-hardware.org/?probe=44557e3a83) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0a82a8edc6](https://linux-hardware.org/?probe=0a82a8edc6) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f30de31399](https://linux-hardware.org/?probe=f30de31399) | Nov 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [2d0d992e3e](https://linux-hardware.org/?probe=2d0d992e3e) | Nov 22, 2023 |
| Positivo      | S14CT01                     | [dab6f65392](https://linux-hardware.org/?probe=dab6f65392) | Nov 22, 2023 |
| Positivo      | S14CT01                     | [b92cdc7457](https://linux-hardware.org/?probe=b92cdc7457) | Nov 22, 2023 |
| Samsung       | 530XBB                      | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| Dell          | Inspiron N5010              | [688d81c63c](https://linux-hardware.org/?probe=688d81c63c) | Nov 22, 2023 |
| Toshiba       | IS 1413G                    | [2f025c011d](https://linux-hardware.org/?probe=2f025c011d) | Nov 22, 2023 |
| Samsung       | 960XFH                      | [c8ff018414](https://linux-hardware.org/?probe=c8ff018414) | Nov 22, 2023 |
| Samsung       | 960XFH                      | [a379f59fb3](https://linux-hardware.org/?probe=a379f59fb3) | Nov 22, 2023 |
| Dell          | Inspiron 5547               | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| Acer          | Aspire A515-54G             | [8e8de2388b](https://linux-hardware.org/?probe=8e8de2388b) | Nov 21, 2023 |
| Toshiba       | IS 1412                     | [0ed3e8195d](https://linux-hardware.org/?probe=0ed3e8195d) | Nov 21, 2023 |
| HP            | 430                         | [65a26f2a32](https://linux-hardware.org/?probe=65a26f2a32) | Nov 21, 2023 |
| Samsung       | 550XDA                      | [4c1328b562](https://linux-hardware.org/?probe=4c1328b562) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d6c8994c15](https://linux-hardware.org/?probe=d6c8994c15) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | [96d6ec7f1f](https://linux-hardware.org/?probe=96d6ec7f1f) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | [c0a0353d6f](https://linux-hardware.org/?probe=c0a0353d6f) | Nov 20, 2023 |
| Dell          | G15 5530                    | [0d608c0d48](https://linux-hardware.org/?probe=0d608c0d48) | Nov 20, 2023 |
| Acer          | Nitro AN517-54              | [b93c6fb412](https://linux-hardware.org/?probe=b93c6fb412) | Nov 20, 2023 |
| Digibras      | NH4CU53                     | [25fff3f773](https://linux-hardware.org/?probe=25fff3f773) | Nov 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| HP            | Presario C700               | [c8a9963f71](https://linux-hardware.org/?probe=c8a9963f71) | Nov 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5edc51a963](https://linux-hardware.org/?probe=5edc51a963) | Nov 19, 2023 |
| Acer          | Predator PH315-52           | [b53d35a567](https://linux-hardware.org/?probe=b53d35a567) | Nov 19, 2023 |
| Dell          | Inspiron 5548               | [63fec114db](https://linux-hardware.org/?probe=63fec114db) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e26c4bc5ff](https://linux-hardware.org/?probe=e26c4bc5ff) | Nov 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [97ebdb3c3a](https://linux-hardware.org/?probe=97ebdb3c3a) | Nov 19, 2023 |
| Dell          | Inspiron 15-5568            | [18712e5bfd](https://linux-hardware.org/?probe=18712e5bfd) | Nov 19, 2023 |
| Acer          | Aspire 5920                 | [ceafa361bc](https://linux-hardware.org/?probe=ceafa361bc) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [07aecd2eb5](https://linux-hardware.org/?probe=07aecd2eb5) | Nov 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | [21433a0601](https://linux-hardware.org/?probe=21433a0601) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | [a9b37fa8a9](https://linux-hardware.org/?probe=a9b37fa8a9) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | [0e1fa61401](https://linux-hardware.org/?probe=0e1fa61401) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9073144bc1](https://linux-hardware.org/?probe=9073144bc1) | Nov 19, 2023 |
| Multilaser    | MLSH1H LINUX                | [5f9c8945b0](https://linux-hardware.org/?probe=5f9c8945b0) | Nov 18, 2023 |
| Dell          | Inspiron 5558               | [29cde3b62e](https://linux-hardware.org/?probe=29cde3b62e) | Nov 18, 2023 |
| Acer          | Aspire E1-532               | [8ec5ebb443](https://linux-hardware.org/?probe=8ec5ebb443) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [669208a0f6](https://linux-hardware.org/?probe=669208a0f6) | Nov 18, 2023 |
| Apple         | MacBookPro14,3              | [c8b5a88695](https://linux-hardware.org/?probe=c8b5a88695) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [a8095f2a1a](https://linux-hardware.org/?probe=a8095f2a1a) | Nov 18, 2023 |
| Multilaser    | MLSH1H LINUX                | [01d7e1aa14](https://linux-hardware.org/?probe=01d7e1aa14) | Nov 18, 2023 |
| HP            | Compaq Presario CQ50        | [a61196eaad](https://linux-hardware.org/?probe=a61196eaad) | Nov 18, 2023 |
| HP            | Compaq Presario CQ50        | [b8b635e62f](https://linux-hardware.org/?probe=b8b635e62f) | Nov 18, 2023 |
| Compaq        | Presario CQ-17              | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| Compal        | PBL1011                     | [d015fafb32](https://linux-hardware.org/?probe=d015fafb32) | Nov 17, 2023 |
| Dell          | Vostro 15 5510              | [21505599dd](https://linux-hardware.org/?probe=21505599dd) | Nov 17, 2023 |
| Dell          | Latitude 5420               | [cc85910964](https://linux-hardware.org/?probe=cc85910964) | Nov 17, 2023 |
| Acer          | Aspire A515-51G             | [44d575bc98](https://linux-hardware.org/?probe=44d575bc98) | Nov 17, 2023 |
| Toshiba       | IS 1413G                    | [97bc4b516e](https://linux-hardware.org/?probe=97bc4b516e) | Nov 17, 2023 |
| Dell          | Latitude 3540               | [85737e7d24](https://linux-hardware.org/?probe=85737e7d24) | Nov 17, 2023 |
| Acer          | Aspire A515-51G             | [18a6603dd9](https://linux-hardware.org/?probe=18a6603dd9) | Nov 17, 2023 |
| Dell          | Vostro 3300                 | [90986d4cf6](https://linux-hardware.org/?probe=90986d4cf6) | Nov 16, 2023 |
| Samsung       | 550XDA                      | [a823e2b0a5](https://linux-hardware.org/?probe=a823e2b0a5) | Nov 16, 2023 |
| Dell          | Inspiron 5567               | [ae0f1ed771](https://linux-hardware.org/?probe=ae0f1ed771) | Nov 16, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [4c58693314](https://linux-hardware.org/?probe=4c58693314) | Nov 16, 2023 |
| HP            | Pavilion g4                 | [37d7289eb6](https://linux-hardware.org/?probe=37d7289eb6) | Nov 16, 2023 |
| Samsung       | 300E5M/300E5L               | [0f53418be5](https://linux-hardware.org/?probe=0f53418be5) | Nov 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f1ba9de4ad](https://linux-hardware.org/?probe=f1ba9de4ad) | Nov 16, 2023 |
| Acer          | Nitro AN515-54              | [0ab66fd189](https://linux-hardware.org/?probe=0ab66fd189) | Nov 16, 2023 |
| Alienware     | m15 R6                      | [c341b25df2](https://linux-hardware.org/?probe=c341b25df2) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1fa32b3cb7](https://linux-hardware.org/?probe=1fa32b3cb7) | Nov 15, 2023 |
| Apple         | MacBookPro8,1               | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [d4c7bc8dc8](https://linux-hardware.org/?probe=d4c7bc8dc8) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | [4ddc04a5ba](https://linux-hardware.org/?probe=4ddc04a5ba) | Nov 15, 2023 |
| Acer          | Aspire E1-572               | [c7c8df77be](https://linux-hardware.org/?probe=c7c8df77be) | Nov 15, 2023 |
| Sony          | VGN-NS130AE                 | [7a70acb426](https://linux-hardware.org/?probe=7a70acb426) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0fe7515de5](https://linux-hardware.org/?probe=0fe7515de5) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | [6bf67ac977](https://linux-hardware.org/?probe=6bf67ac977) | Nov 15, 2023 |
| Dell          | Vostro 15 3510              | [9c0b7c2706](https://linux-hardware.org/?probe=9c0b7c2706) | Nov 15, 2023 |
| Dell          | Inspiron 1545               | [fd459af24b](https://linux-hardware.org/?probe=fd459af24b) | Nov 15, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [3be8e07c6c](https://linux-hardware.org/?probe=3be8e07c6c) | Nov 14, 2023 |
| Dell          | Inspiron 3583               | [d014ceb833](https://linux-hardware.org/?probe=d014ceb833) | Nov 14, 2023 |
| Acer          | Predator PH315-53           | [f2a6eea13e](https://linux-hardware.org/?probe=f2a6eea13e) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4e7f0bb4bc](https://linux-hardware.org/?probe=4e7f0bb4bc) | Nov 14, 2023 |
| Phoenix/Si... | M730SR                      | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| Acer          | Aspire A515-51G             | [50a49f6aa3](https://linux-hardware.org/?probe=50a49f6aa3) | Nov 14, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [65712a4bc0](https://linux-hardware.org/?probe=65712a4bc0) | Nov 14, 2023 |
| HP            | Pavilion dv5                | [f08fc1d52e](https://linux-hardware.org/?probe=f08fc1d52e) | Nov 13, 2023 |
| Acer          | Nitro AN517-54              | [37423cedf9](https://linux-hardware.org/?probe=37423cedf9) | Nov 13, 2023 |
| Sony          | VPCYB35AB                   | [2bc35e6541](https://linux-hardware.org/?probe=2bc35e6541) | Nov 13, 2023 |
| Acer          | Nitro AN515-54              | [656ba48c77](https://linux-hardware.org/?probe=656ba48c77) | Nov 12, 2023 |
| Acer          | Nitro AN515-54              | [6fb9ac1dd2](https://linux-hardware.org/?probe=6fb9ac1dd2) | Nov 12, 2023 |
| Dell          | Latitude 3420               | [5e829237c5](https://linux-hardware.org/?probe=5e829237c5) | Nov 12, 2023 |
| Apple         | MacBookPro8,1               | [cbde46d416](https://linux-hardware.org/?probe=cbde46d416) | Nov 12, 2023 |
| Toshiba       | IS 1413G                    | [9a070023f0](https://linux-hardware.org/?probe=9a070023f0) | Nov 12, 2023 |
| HP            | G42                         | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [5168262bbe](https://linux-hardware.org/?probe=5168262bbe) | Nov 11, 2023 |
| Philco        | 14H                         | [01ddcfeb9e](https://linux-hardware.org/?probe=01ddcfeb9e) | Nov 11, 2023 |
| Acer          | Nitro AN515-51              | [bcbad28ab7](https://linux-hardware.org/?probe=bcbad28ab7) | Nov 11, 2023 |
| Samsung       | 550XDA                      | [036d014b91](https://linux-hardware.org/?probe=036d014b91) | Nov 10, 2023 |
| Acer          | Aspire A315-54              | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [04eea37363](https://linux-hardware.org/?probe=04eea37363) | Nov 10, 2023 |
| HP            | ProBook 4430s               | [47b4ab5ae1](https://linux-hardware.org/?probe=47b4ab5ae1) | Nov 10, 2023 |
| HP            | ProBook 4430s               | [69a5aa0675](https://linux-hardware.org/?probe=69a5aa0675) | Nov 10, 2023 |
| Acer          | Aspire A315-23              | [95ea718240](https://linux-hardware.org/?probe=95ea718240) | Nov 10, 2023 |
| ASUSTek       | G60JX                       | [0ac4f1dfc0](https://linux-hardware.org/?probe=0ac4f1dfc0) | Nov 10, 2023 |
| Lenovo        | ThinkPad E14 20RB001YBR     | [5c84f04d34](https://linux-hardware.org/?probe=5c84f04d34) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| ASUSTek       | S400CA                      | [0e5628865a](https://linux-hardware.org/?probe=0e5628865a) | Nov 09, 2023 |
| HP            | 250 G8 Notebook PC          | [54073a3305](https://linux-hardware.org/?probe=54073a3305) | Nov 09, 2023 |
| Dell          | Vostro 5470                 | [f1ba64ccfc](https://linux-hardware.org/?probe=f1ba64ccfc) | Nov 09, 2023 |
| HP            | G42                         | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Vostro 5402                 | [67a604ba54](https://linux-hardware.org/?probe=67a604ba54) | Nov 08, 2023 |
| Acer          | Nitro AN515-54              | [fbdaa89128](https://linux-hardware.org/?probe=fbdaa89128) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | [b5982ee614](https://linux-hardware.org/?probe=b5982ee614) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| Acer          | Aspire F5-573G              | [00b9675b99](https://linux-hardware.org/?probe=00b9675b99) | Nov 08, 2023 |
| Dell          | Latitude 3480               | [993ca1c423](https://linux-hardware.org/?probe=993ca1c423) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | [3cf76cfbda](https://linux-hardware.org/?probe=3cf76cfbda) | Nov 08, 2023 |
| Acer          | Nitro AN515-46              | [69541ca76a](https://linux-hardware.org/?probe=69541ca76a) | Nov 07, 2023 |
| ASUSTek       | G60JX                       | [af79a74a4e](https://linux-hardware.org/?probe=af79a74a4e) | Nov 07, 2023 |
| Valve         | Jupiter                     | [b662e225f4](https://linux-hardware.org/?probe=b662e225f4) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | [c88fd34c8f](https://linux-hardware.org/?probe=c88fd34c8f) | Nov 07, 2023 |
| Dell          | Latitude 3480               | [58e8983502](https://linux-hardware.org/?probe=58e8983502) | Nov 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0cc84d3b82](https://linux-hardware.org/?probe=0cc84d3b82) | Nov 07, 2023 |
| Samsung       | 550P5C/550P7C               | [c7d84926af](https://linux-hardware.org/?probe=c7d84926af) | Nov 07, 2023 |
| Notebook      | NJx0MU                      | [70cdbefd00](https://linux-hardware.org/?probe=70cdbefd00) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | [8ee0ec30d3](https://linux-hardware.org/?probe=8ee0ec30d3) | Nov 06, 2023 |
| HP            | EliteBook 850 G6            | [0d00c42688](https://linux-hardware.org/?probe=0d00c42688) | Nov 06, 2023 |
| HP            | ENVY 15                     | [5f301610ee](https://linux-hardware.org/?probe=5f301610ee) | Nov 06, 2023 |
| Acer          | Aspire A515-51              | [5fafb134cf](https://linux-hardware.org/?probe=5fafb134cf) | Nov 06, 2023 |
| HP            | ENVY 15                     | [150ca6a1a0](https://linux-hardware.org/?probe=150ca6a1a0) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Positivo      | C41TF                       | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Notebook      | NJx0MU                      | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f0b35f0acb](https://linux-hardware.org/?probe=f0b35f0acb) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7060a82ed0](https://linux-hardware.org/?probe=7060a82ed0) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Digibras      | NH4CU53                     | [2c274cbad8](https://linux-hardware.org/?probe=2c274cbad8) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Dell          | Latitude E6430              | [6a724d5aa8](https://linux-hardware.org/?probe=6a724d5aa8) | Nov 04, 2023 |
| ASUSTek       | UX31A                       | [013a7815c3](https://linux-hardware.org/?probe=013a7815c3) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Google        | Bluebird                    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| MSI           | MS-1759                     | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Google        | Bluebird                    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | 246 G6 Notebook PC          | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| Dell          | Inspiron N4010              | [f8aed4abab](https://linux-hardware.org/?probe=f8aed4abab) | Nov 03, 2023 |
| Dell          | Latitude 3420               | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Multilaser    | PC13X                       | [1c6a314055](https://linux-hardware.org/?probe=1c6a314055) | Nov 03, 2023 |
| Acer          | Aspire 5750                 | [429b14ee32](https://linux-hardware.org/?probe=429b14ee32) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [6987861086](https://linux-hardware.org/?probe=6987861086) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5d06dbbe5f](https://linux-hardware.org/?probe=5d06dbbe5f) | Nov 03, 2023 |
| Dell          | Inspiron 5547               | [e14eb66450](https://linux-hardware.org/?probe=e14eb66450) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [9552d5f729](https://linux-hardware.org/?probe=9552d5f729) | Nov 02, 2023 |
| Acer          | AO722                       | [3464dc7b3c](https://linux-hardware.org/?probe=3464dc7b3c) | Nov 02, 2023 |
| Dell          | Latitude 3440               | [b50ed47992](https://linux-hardware.org/?probe=b50ed47992) | Nov 02, 2023 |
| Dell          | Latitude 3440               | [9426910684](https://linux-hardware.org/?probe=9426910684) | Nov 02, 2023 |
| HP            | ZBook 17 G5                 | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Samsung       | 960XFH                      | [6076e144ac](https://linux-hardware.org/?probe=6076e144ac) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | [b03928bc33](https://linux-hardware.org/?probe=b03928bc33) | Nov 01, 2023 |
| Dell          | Inspiron 5502               | [a1d2f7988e](https://linux-hardware.org/?probe=a1d2f7988e) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [446efaf1bb](https://linux-hardware.org/?probe=446efaf1bb) | Oct 31, 2023 |
| Apple         | MacBookPro8,1               | [27c6a9540f](https://linux-hardware.org/?probe=27c6a9540f) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [5b8af0fd77](https://linux-hardware.org/?probe=5b8af0fd77) | Oct 31, 2023 |
| Dell          | G15 5515                    | [c59e97ba9e](https://linux-hardware.org/?probe=c59e97ba9e) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [40ae523147](https://linux-hardware.org/?probe=40ae523147) | Oct 31, 2023 |
| HP            | ProBook 645 G1              | [b637cedab4](https://linux-hardware.org/?probe=b637cedab4) | Oct 31, 2023 |
| Dell          | Latitude 5400               | [e7f91d1c69](https://linux-hardware.org/?probe=e7f91d1c69) | Oct 30, 2023 |
| LG Electro... | 14Z980-G.BH51P1             | [879ba00b91](https://linux-hardware.org/?probe=879ba00b91) | Oct 30, 2023 |
| Acer          | Aspire 5733                 | [8a925b3630](https://linux-hardware.org/?probe=8a925b3630) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [931f0ed896](https://linux-hardware.org/?probe=931f0ed896) | Oct 30, 2023 |
| Dell          | Inspiron N4050              | [7d5dc09b04](https://linux-hardware.org/?probe=7d5dc09b04) | Oct 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE13    | [28a8f59777](https://linux-hardware.org/?probe=28a8f59777) | Oct 29, 2023 |
| Sony          | VPCCW13FB                   | [96516448b2](https://linux-hardware.org/?probe=96516448b2) | Oct 29, 2023 |
| Sony          | VPCCW13FB                   | [7092dfafd9](https://linux-hardware.org/?probe=7092dfafd9) | Oct 29, 2023 |
| Samsung       | 370E4K                      | [78ec3e796a](https://linux-hardware.org/?probe=78ec3e796a) | Oct 28, 2023 |
| Acer          | Aspire V3-571               | [6aa696ac55](https://linux-hardware.org/?probe=6aa696ac55) | Oct 28, 2023 |
| Samsung       | 550XCJ/550XCR               | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Sony          | SVS13A25PBS                 | [7cb087bd2d](https://linux-hardware.org/?probe=7cb087bd2d) | Oct 27, 2023 |
| Avell High... | 1513 Mxti                   | [9f5d60c02b](https://linux-hardware.org/?probe=9f5d60c02b) | Oct 27, 2023 |
| Acer          | Nitro AN515-47              | [8516768801](https://linux-hardware.org/?probe=8516768801) | Oct 26, 2023 |
| Acer          | Aspire 5050                 | [2129ab3e24](https://linux-hardware.org/?probe=2129ab3e24) | Oct 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [2bee900f03](https://linux-hardware.org/?probe=2bee900f03) | Oct 26, 2023 |
| Dell          | Inspiron 3437               | [a57068abbc](https://linux-hardware.org/?probe=a57068abbc) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c9e8482167](https://linux-hardware.org/?probe=c9e8482167) | Oct 26, 2023 |
| Lenovo        | Y720-15IKB 81CQ             | [7aec151a1c](https://linux-hardware.org/?probe=7aec151a1c) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76d22d10e6](https://linux-hardware.org/?probe=76d22d10e6) | Oct 25, 2023 |
| Samsung       | 270E5J/2570EJ               | [94f358053d](https://linux-hardware.org/?probe=94f358053d) | Oct 24, 2023 |
| Dell          | Vostro 3550                 | [2fb1e4bb71](https://linux-hardware.org/?probe=2fb1e4bb71) | Oct 24, 2023 |
| Samsung       | 670Z5E                      | [101b5bda5b](https://linux-hardware.org/?probe=101b5bda5b) | Oct 24, 2023 |
| Dell          | Inspiron 15-3567            | [879198d56a](https://linux-hardware.org/?probe=879198d56a) | Oct 24, 2023 |
| Dell          | Inspiron 15-3567            | [0e451d6616](https://linux-hardware.org/?probe=0e451d6616) | Oct 24, 2023 |
| Lenovo        | Y720-15IKB 81CQ             | [c0601dc338](https://linux-hardware.org/?probe=c0601dc338) | Oct 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [744dddac21](https://linux-hardware.org/?probe=744dddac21) | Oct 24, 2023 |
| Alienware     | m15 R6                      | [c6711f7b02](https://linux-hardware.org/?probe=c6711f7b02) | Oct 24, 2023 |
| Valve         | Jupiter                     | [83d3faf177](https://linux-hardware.org/?probe=83d3faf177) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | [24a664955f](https://linux-hardware.org/?probe=24a664955f) | Oct 23, 2023 |
| Acer          | Aspire A315-42G             | [65494c95ec](https://linux-hardware.org/?probe=65494c95ec) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | [c931b1ef73](https://linux-hardware.org/?probe=c931b1ef73) | Oct 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [da2cda923f](https://linux-hardware.org/?probe=da2cda923f) | Oct 23, 2023 |
| Dell          | Vostro 3400                 | [9c24bc3329](https://linux-hardware.org/?probe=9c24bc3329) | Oct 23, 2023 |
| Samsung       | RF511/RF411/RF711           | [6a62fa5cb6](https://linux-hardware.org/?probe=6a62fa5cb6) | Oct 23, 2023 |
| HP            | Pavilion dv7                | [c3e7ebfd20](https://linux-hardware.org/?probe=c3e7ebfd20) | Oct 23, 2023 |
| Acer          | Aspire E5-573               | [d83f4bf9ad](https://linux-hardware.org/?probe=d83f4bf9ad) | Oct 23, 2023 |
| Dell          | G15 5515                    | [758d007f45](https://linux-hardware.org/?probe=758d007f45) | Oct 23, 2023 |
| Dell          | G15 5515                    | [5853f5312f](https://linux-hardware.org/?probe=5853f5312f) | Oct 23, 2023 |
| Positivo      | C4128G-15                   | [8d9aa2f206](https://linux-hardware.org/?probe=8d9aa2f206) | Oct 23, 2023 |
| Acer          | Aspire A315-58              | [60402f4ad8](https://linux-hardware.org/?probe=60402f4ad8) | Oct 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [48d2114a2e](https://linux-hardware.org/?probe=48d2114a2e) | Oct 22, 2023 |
| HP            | Folio 13                    | [b7ed500d93](https://linux-hardware.org/?probe=b7ed500d93) | Oct 22, 2023 |
| Clevo         | M660SR                      | [56f8ab01f9](https://linux-hardware.org/?probe=56f8ab01f9) | Oct 22, 2023 |
| Dell          | Inspiron 3437               | [331cbd427d](https://linux-hardware.org/?probe=331cbd427d) | Oct 21, 2023 |
| HP            | Pavilion dv7                | [3379c8b4e7](https://linux-hardware.org/?probe=3379c8b4e7) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | [961c369ea4](https://linux-hardware.org/?probe=961c369ea4) | Oct 21, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [ad7ca8e192](https://linux-hardware.org/?probe=ad7ca8e192) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | [f19c18154b](https://linux-hardware.org/?probe=f19c18154b) | Oct 21, 2023 |
| Gateway       | NV55C                       | [bb0eb9e5dd](https://linux-hardware.org/?probe=bb0eb9e5dd) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | [d3b1d639f5](https://linux-hardware.org/?probe=d3b1d639f5) | Oct 21, 2023 |
| Compaq        | 434                         | [094bba21f8](https://linux-hardware.org/?probe=094bba21f8) | Oct 21, 2023 |
| LG Electro... | R410-G.BP21P1               | [36849f1a4c](https://linux-hardware.org/?probe=36849f1a4c) | Oct 21, 2023 |
| HP            | Folio 13                    | [99ff48ac3f](https://linux-hardware.org/?probe=99ff48ac3f) | Oct 20, 2023 |
| Avell High... | B.ON                        | [7f8ce9da76](https://linux-hardware.org/?probe=7f8ce9da76) | Oct 20, 2023 |
| Samsung       | 670Z5E                      | [ddc0c78bff](https://linux-hardware.org/?probe=ddc0c78bff) | Oct 20, 2023 |
| Dell          | Latitude 3490               | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| Dell          | Vostro 3300                 | [827b95e65c](https://linux-hardware.org/?probe=827b95e65c) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | [be03ed57d8](https://linux-hardware.org/?probe=be03ed57d8) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | [e648a8c32a](https://linux-hardware.org/?probe=e648a8c32a) | Oct 20, 2023 |
| Acer          | Aspire A315-42G             | [46d5d338b3](https://linux-hardware.org/?probe=46d5d338b3) | Oct 20, 2023 |
| Dell          | Vostro 3550                 | [db4e9dfc27](https://linux-hardware.org/?probe=db4e9dfc27) | Oct 20, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0506dfa238](https://linux-hardware.org/?probe=0506dfa238) | Oct 19, 2023 |
| Dell          | Vostro 3560                 | [aa95d1c178](https://linux-hardware.org/?probe=aa95d1c178) | Oct 19, 2023 |
| Dell          | Inspiron 5547               | [3dc947b334](https://linux-hardware.org/?probe=3dc947b334) | Oct 19, 2023 |
| Samsung       | 670Z5E                      | [aeec82cef9](https://linux-hardware.org/?probe=aeec82cef9) | Oct 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [e94e48868c](https://linux-hardware.org/?probe=e94e48868c) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [abafeadb35](https://linux-hardware.org/?probe=abafeadb35) | Oct 19, 2023 |
| Compaq        | Presario CQ-23              | [15c10707d0](https://linux-hardware.org/?probe=15c10707d0) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [ab3c18427d](https://linux-hardware.org/?probe=ab3c18427d) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a8e2b482f4](https://linux-hardware.org/?probe=a8e2b482f4) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ab21923ddd](https://linux-hardware.org/?probe=ab21923ddd) | Oct 19, 2023 |
| Dell          | Inspiron 15-3567            | [486e66cdee](https://linux-hardware.org/?probe=486e66cdee) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cf6314850a](https://linux-hardware.org/?probe=cf6314850a) | Oct 18, 2023 |
| Positivo      | Mobile                      | [5dedeac18e](https://linux-hardware.org/?probe=5dedeac18e) | Oct 18, 2023 |
| Sony          | VPCEA23FB                   | [dbfa513b31](https://linux-hardware.org/?probe=dbfa513b31) | Oct 18, 2023 |
| Acer          | Nitro AN515-54              | [877ec2dd85](https://linux-hardware.org/?probe=877ec2dd85) | Oct 18, 2023 |
| Dell          | Inspiron 15-3567            | [d77237b330](https://linux-hardware.org/?probe=d77237b330) | Oct 18, 2023 |
| Samsung       | 670Z5E                      | [65ee0747bc](https://linux-hardware.org/?probe=65ee0747bc) | Oct 18, 2023 |
| Lenovo        | B330S-15IKBR 81JV           | [5df1834272](https://linux-hardware.org/?probe=5df1834272) | Oct 18, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [041aba02ce](https://linux-hardware.org/?probe=041aba02ce) | Oct 17, 2023 |
| Dell          | Inspiron 7559               | [6280e4287a](https://linux-hardware.org/?probe=6280e4287a) | Oct 17, 2023 |
| Lenovo        | B330S-15IKBR 81JV           | [9e1356181f](https://linux-hardware.org/?probe=9e1356181f) | Oct 17, 2023 |
| Dell          | Inspiron 5448               | [5901b49079](https://linux-hardware.org/?probe=5901b49079) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | [33cba76fe6](https://linux-hardware.org/?probe=33cba76fe6) | Oct 17, 2023 |
| HP            | Folio 13 - 2000             | [c541a1603c](https://linux-hardware.org/?probe=c541a1603c) | Oct 17, 2023 |
| Dell          | Vostro 3550                 | [25ba718720](https://linux-hardware.org/?probe=25ba718720) | Oct 16, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | [e66f442843](https://linux-hardware.org/?probe=e66f442843) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | [eab86d1cc0](https://linux-hardware.org/?probe=eab86d1cc0) | Oct 16, 2023 |
| Positivo      | Q4128C-S                    | [ea1c91d413](https://linux-hardware.org/?probe=ea1c91d413) | Oct 16, 2023 |
| Acer          | Aspire E5-571               | [fcc76a61ae](https://linux-hardware.org/?probe=fcc76a61ae) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | [7f9e09a9e1](https://linux-hardware.org/?probe=7f9e09a9e1) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | [2571e4fd1b](https://linux-hardware.org/?probe=2571e4fd1b) | Oct 16, 2023 |
| Avell High... | C62 MOB                     | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| HP            | Pavilion dv6                | [4faf7bb285](https://linux-hardware.org/?probe=4faf7bb285) | Oct 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [90b07f2a8b](https://linux-hardware.org/?probe=90b07f2a8b) | Oct 15, 2023 |
| HP            | Pavilion dv6                | [52e554d0dc](https://linux-hardware.org/?probe=52e554d0dc) | Oct 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c12987d53a](https://linux-hardware.org/?probe=c12987d53a) | Oct 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [079342de2b](https://linux-hardware.org/?probe=079342de2b) | Oct 15, 2023 |
| Dell          | Inspiron N5010              | [9dae04bd63](https://linux-hardware.org/?probe=9dae04bd63) | Oct 15, 2023 |
| Acer          | Nitro AN517-54              | [2f6c2f44d3](https://linux-hardware.org/?probe=2f6c2f44d3) | Oct 15, 2023 |
| Samsung       | 550XCJ/550XCR               | [579dc4dabc](https://linux-hardware.org/?probe=579dc4dabc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [33a143a23d](https://linux-hardware.org/?probe=33a143a23d) | Oct 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c91ad6491](https://linux-hardware.org/?probe=3c91ad6491) | Oct 14, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [160af8609e](https://linux-hardware.org/?probe=160af8609e) | Oct 14, 2023 |
| Dell          | Inspiron 3501               | [a1ada382fa](https://linux-hardware.org/?probe=a1ada382fa) | Oct 14, 2023 |
| HP            | ProBook 640 G1              | [b00d98a451](https://linux-hardware.org/?probe=b00d98a451) | Oct 14, 2023 |
| HP            | ProBook 640 G1              | [15168951ed](https://linux-hardware.org/?probe=15168951ed) | Oct 13, 2023 |
| Samsung       | 550XBE/350XBE               | [27ea9922a6](https://linux-hardware.org/?probe=27ea9922a6) | Oct 13, 2023 |
| Dell          | Inspiron 5548               | [edb6e06451](https://linux-hardware.org/?probe=edb6e06451) | Oct 13, 2023 |
| Digibras      | NH4CU53                     | [40f4cfc21c](https://linux-hardware.org/?probe=40f4cfc21c) | Oct 13, 2023 |
| Acer          | Aspire A515-45              | [f5e57e4558](https://linux-hardware.org/?probe=f5e57e4558) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Acer          | Nitro AN515-47              | [0592faaf34](https://linux-hardware.org/?probe=0592faaf34) | Oct 12, 2023 |
| Acer          | Nitro AN515-44              | [65b1e10033](https://linux-hardware.org/?probe=65b1e10033) | Oct 12, 2023 |
| Acer          | Nitro AN515-44              | [6d2fdd060b](https://linux-hardware.org/?probe=6d2fdd060b) | Oct 12, 2023 |
| Acer          | Aspire E1-571               | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Dell          | Latitude 3490               | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Apple         | MacBookPro5,4               | [f68b19bbe5](https://linux-hardware.org/?probe=f68b19bbe5) | Oct 12, 2023 |
| Acer          | Aspire VX5-591G             | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| Dell          | Vostro 5490                 | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Gateway       | NE570                       | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Avell High... | B.ON                        | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [19f231af9a](https://linux-hardware.org/?probe=19f231af9a) | Oct 11, 2023 |
| Dell          | Vostro 1510                 | [6324053514](https://linux-hardware.org/?probe=6324053514) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c0882707d4](https://linux-hardware.org/?probe=c0882707d4) | Oct 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c397035651](https://linux-hardware.org/?probe=c397035651) | Oct 10, 2023 |
| Dell          | Latitude E6420              | [7508b7cf4f](https://linux-hardware.org/?probe=7508b7cf4f) | Oct 10, 2023 |
| Apple         | MacBookPro11,1              | [8a64a738ca](https://linux-hardware.org/?probe=8a64a738ca) | Oct 10, 2023 |
| Apple         | MacBookPro8,1               | [2192f74b2d](https://linux-hardware.org/?probe=2192f74b2d) | Oct 09, 2023 |
| Dell          | Inspiron 3421               | [1da5f9aefa](https://linux-hardware.org/?probe=1da5f9aefa) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Lenovo        | G480 20149                  | [ff58b011f2](https://linux-hardware.org/?probe=ff58b011f2) | Oct 09, 2023 |
| Dell          | Inspiron 3583               | [f2fe39dcc0](https://linux-hardware.org/?probe=f2fe39dcc0) | Oct 09, 2023 |
| Dell          | Inspiron 3583               | [f78bda610e](https://linux-hardware.org/?probe=f78bda610e) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [508c438c6a](https://linux-hardware.org/?probe=508c438c6a) | Oct 09, 2023 |
| Dell          | Vostro 7590                 | [d7188e68cb](https://linux-hardware.org/?probe=d7188e68cb) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 20RB0028BR     | [bb9133e0b8](https://linux-hardware.org/?probe=bb9133e0b8) | Oct 08, 2023 |
| Dell          | Inspiron 3421               | [b8557f2880](https://linux-hardware.org/?probe=b8557f2880) | Oct 08, 2023 |
| Dell          | Inspiron 3576               | [7e5e46c41a](https://linux-hardware.org/?probe=7e5e46c41a) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | [0d2d2cf2ae](https://linux-hardware.org/?probe=0d2d2cf2ae) | Oct 08, 2023 |
| HP            | ENVY dv7                    | [05ca6a125d](https://linux-hardware.org/?probe=05ca6a125d) | Oct 08, 2023 |
| HP            | Folio 13                    | [f4ed29d660](https://linux-hardware.org/?probe=f4ed29d660) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| ASUSTek       | G60JX                       | [e455f7fb08](https://linux-hardware.org/?probe=e455f7fb08) | Oct 08, 2023 |
| ASUSTek       | G60JX                       | [335e991de2](https://linux-hardware.org/?probe=335e991de2) | Oct 08, 2023 |
| Acer          | Aspire ES1-572              | [ac5943ef0c](https://linux-hardware.org/?probe=ac5943ef0c) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | [9f94f8934f](https://linux-hardware.org/?probe=9f94f8934f) | Oct 07, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [d375cfe649](https://linux-hardware.org/?probe=d375cfe649) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [0d8aca1f6e](https://linux-hardware.org/?probe=0d8aca1f6e) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [a2138fa3f8](https://linux-hardware.org/?probe=a2138fa3f8) | Oct 07, 2023 |
| Alienware     | m15 R7                      | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| Dell          | Latitude 3490               | [723d6797ae](https://linux-hardware.org/?probe=723d6797ae) | Oct 07, 2023 |
| Dell          | Inspiron 5421               | [90c1f511a6](https://linux-hardware.org/?probe=90c1f511a6) | Oct 06, 2023 |
| Dell          | Vostro 1510                 | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [62c8d86cfa](https://linux-hardware.org/?probe=62c8d86cfa) | Oct 06, 2023 |
| Acer          | Aspire ES1-572              | [2e48163fbd](https://linux-hardware.org/?probe=2e48163fbd) | Oct 06, 2023 |
| Sony          | VGN-SR150A                  | [f8fcbe4227](https://linux-hardware.org/?probe=f8fcbe4227) | Oct 06, 2023 |
| Positivo B... | VJFE55F11X-B0211H           | [8d54d8438d](https://linux-hardware.org/?probe=8d54d8438d) | Oct 05, 2023 |
| Acer          | Aspire ES1-572              | [651a8f8f97](https://linux-hardware.org/?probe=651a8f8f97) | Oct 05, 2023 |
| Apple         | MacBookPro11,1              | [e346a58990](https://linux-hardware.org/?probe=e346a58990) | Oct 05, 2023 |
| Philco Inf... | EC10IS2                     | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| Dell          | Inspiron 5490               | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| Positivo      | S14BW01                     | [3027fc7d9b](https://linux-hardware.org/?probe=3027fc7d9b) | Oct 04, 2023 |
| Dell          | Inspiron 5575               | [48afb4262c](https://linux-hardware.org/?probe=48afb4262c) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7bb81b99a0](https://linux-hardware.org/?probe=7bb81b99a0) | Oct 04, 2023 |
| Dell          | Inspiron 5547               | [06d30a9c8d](https://linux-hardware.org/?probe=06d30a9c8d) | Oct 03, 2023 |
| Apple         | MacBookPro8,1               | [cf2552023d](https://linux-hardware.org/?probe=cf2552023d) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [5813f8d107](https://linux-hardware.org/?probe=5813f8d107) | Oct 03, 2023 |
| MSI           | CR620                       | [be490381a9](https://linux-hardware.org/?probe=be490381a9) | Oct 03, 2023 |
| Dell          | Inspiron 5558               | [81c44f8b56](https://linux-hardware.org/?probe=81c44f8b56) | Oct 03, 2023 |
| Dell          | Inspiron 5480               | [666fbb9e46](https://linux-hardware.org/?probe=666fbb9e46) | Oct 03, 2023 |
| ASUSTek       | K45VM                       | [b4f51ced7a](https://linux-hardware.org/?probe=b4f51ced7a) | Oct 02, 2023 |
| Dell          | Latitude E6420              | [90883fd019](https://linux-hardware.org/?probe=90883fd019) | Oct 02, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [9574c05fb2](https://linux-hardware.org/?probe=9574c05fb2) | Oct 02, 2023 |
| Compaq        | 420                         | [b327579e60](https://linux-hardware.org/?probe=b327579e60) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | [60a8a7d13f](https://linux-hardware.org/?probe=60a8a7d13f) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | [28a54d8189](https://linux-hardware.org/?probe=28a54d8189) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Notebook      | NJx0MU                      | [f510af1acf](https://linux-hardware.org/?probe=f510af1acf) | Oct 01, 2023 |
| Dell          | Inspiron 15 3515            | [44bfa52d57](https://linux-hardware.org/?probe=44bfa52d57) | Oct 01, 2023 |
| Dell          | Inspiron 7580               | [8fa784881e](https://linux-hardware.org/?probe=8fa784881e) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | [7b44ef8cd1](https://linux-hardware.org/?probe=7b44ef8cd1) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | [a1f20bb140](https://linux-hardware.org/?probe=a1f20bb140) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | [1449844643](https://linux-hardware.org/?probe=1449844643) | Sep 30, 2023 |
| Tectoy        | Pense Bem Notebook          | [6a6e6af34c](https://linux-hardware.org/?probe=6a6e6af34c) | Sep 29, 2023 |
| Positivo      | C14CR01                     | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [772e866a05](https://linux-hardware.org/?probe=772e866a05) | Sep 29, 2023 |
| Dell          | Inspiron 5437               | [c0301c2fbb](https://linux-hardware.org/?probe=c0301c2fbb) | Sep 29, 2023 |
| Acer          | Nitro AN515-43              | [e55a394d41](https://linux-hardware.org/?probe=e55a394d41) | Sep 29, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [ccc715eeb6](https://linux-hardware.org/?probe=ccc715eeb6) | Sep 29, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| ASUSTek       | K45VM                       | [6c167e69a4](https://linux-hardware.org/?probe=6c167e69a4) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Acer          | Aspire E5-571               | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| Samsung       | 550XDA                      | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| Dell          | System XPS L502X            | [06d6fd95d1](https://linux-hardware.org/?probe=06d6fd95d1) | Sep 27, 2023 |
| Acer          | Aspire A315-53              | [c20a9f8f96](https://linux-hardware.org/?probe=c20a9f8f96) | Sep 27, 2023 |
| Dell          | G15 5520                    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Inspiron 5423               | [a6a3b2697f](https://linux-hardware.org/?probe=a6a3b2697f) | Sep 26, 2023 |
| Dell          | Inspiron 5567               | [6ebf39a37a](https://linux-hardware.org/?probe=6ebf39a37a) | Sep 26, 2023 |
| Dell          | Inspiron 5567               | [644a616222](https://linux-hardware.org/?probe=644a616222) | Sep 26, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [3d8dfdbf80](https://linux-hardware.org/?probe=3d8dfdbf80) | Sep 26, 2023 |
| HP            | Folio 13                    | [a5a1ae29a7](https://linux-hardware.org/?probe=a5a1ae29a7) | Sep 26, 2023 |
| Notebook      | NJx0MU                      | [89d81885ff](https://linux-hardware.org/?probe=89d81885ff) | Sep 26, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| HP            | Presario CQ43               | [c206dc84ad](https://linux-hardware.org/?probe=c206dc84ad) | Sep 25, 2023 |
| Acer          | Aspire F5-573G              | [a2f6814940](https://linux-hardware.org/?probe=a2f6814940) | Sep 25, 2023 |
| Dell          | Latitude E5440              | [f4accb1cb0](https://linux-hardware.org/?probe=f4accb1cb0) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | [e74a87d3f4](https://linux-hardware.org/?probe=e74a87d3f4) | Sep 25, 2023 |
| HP            | Presario CQ43               | [b2663eb2fa](https://linux-hardware.org/?probe=b2663eb2fa) | Sep 25, 2023 |
| Acer          | Nitro AN515-51              | [6d6d719f30](https://linux-hardware.org/?probe=6d6d719f30) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | [c643f10970](https://linux-hardware.org/?probe=c643f10970) | Sep 24, 2023 |
| Samsung       | 550XBE/350XBE               | [cdbacef976](https://linux-hardware.org/?probe=cdbacef976) | Sep 24, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [eb82ffb863](https://linux-hardware.org/?probe=eb82ffb863) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d71e760b5c](https://linux-hardware.org/?probe=d71e760b5c) | Sep 24, 2023 |
| Notebook      | NJx0MU                      | [84bba5e5a7](https://linux-hardware.org/?probe=84bba5e5a7) | Sep 24, 2023 |
| HP            | Presario CQ43               | [d5ee5e4318](https://linux-hardware.org/?probe=d5ee5e4318) | Sep 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [7022eac21d](https://linux-hardware.org/?probe=7022eac21d) | Sep 23, 2023 |
| Valve         | Jupiter                     | [287bf4d933](https://linux-hardware.org/?probe=287bf4d933) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [04141bd71c](https://linux-hardware.org/?probe=04141bd71c) | Sep 22, 2023 |
| Dell          | Latitude E7440              | [53e90ca355](https://linux-hardware.org/?probe=53e90ca355) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [65a21a4968](https://linux-hardware.org/?probe=65a21a4968) | Sep 22, 2023 |
| HP            | Folio 13                    | [66f8752b64](https://linux-hardware.org/?probe=66f8752b64) | Sep 22, 2023 |
| Lenovo        | ThinkPad X220 4286BB2       | [a3b217a707](https://linux-hardware.org/?probe=a3b217a707) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [dd328a6f1f](https://linux-hardware.org/?probe=dd328a6f1f) | Sep 21, 2023 |
| Samsung       | 550XBE/350XBE               | [522d50a437](https://linux-hardware.org/?probe=522d50a437) | Sep 21, 2023 |
| Samsung       | 550XDA                      | [2d15b3f4ca](https://linux-hardware.org/?probe=2d15b3f4ca) | Sep 21, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [5a74bb7dde](https://linux-hardware.org/?probe=5a74bb7dde) | Sep 20, 2023 |
| Dell          | XPS 13 9300                 | [49bb68e979](https://linux-hardware.org/?probe=49bb68e979) | Sep 20, 2023 |
| ASUSTek       | Z450UA                      | [60d85e59da](https://linux-hardware.org/?probe=60d85e59da) | Sep 20, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [16b2b018c1](https://linux-hardware.org/?probe=16b2b018c1) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | [d8305c7c45](https://linux-hardware.org/?probe=d8305c7c45) | Sep 20, 2023 |
| Samsung       | 960XFH                      | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Chuwi         | GemiBook Pro                | [7ff48f538f](https://linux-hardware.org/?probe=7ff48f538f) | Sep 19, 2023 |
| Dell          | Inspiron 3442               | [1f6ca2e4f7](https://linux-hardware.org/?probe=1f6ca2e4f7) | Sep 19, 2023 |
| Samsung       | 550XDA                      | [763631bfe7](https://linux-hardware.org/?probe=763631bfe7) | Sep 19, 2023 |
| Daten Tecn... | DT02-M4                     | [67c158a4f1](https://linux-hardware.org/?probe=67c158a4f1) | Sep 19, 2023 |
| Dell          | XPS 15 9560                 | [28d0c94948](https://linux-hardware.org/?probe=28d0c94948) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | [d68a92e72a](https://linux-hardware.org/?probe=d68a92e72a) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | [8b335d6bb0](https://linux-hardware.org/?probe=8b335d6bb0) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0ec89ecd46](https://linux-hardware.org/?probe=0ec89ecd46) | Sep 19, 2023 |
| Acer          | Aspire 5742                 | [430ed1fe6c](https://linux-hardware.org/?probe=430ed1fe6c) | Sep 19, 2023 |
| HP            | Compaq Mini 311-1100        | [418d54b71d](https://linux-hardware.org/?probe=418d54b71d) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b036a6058](https://linux-hardware.org/?probe=0b036a6058) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | [5701fbde3e](https://linux-hardware.org/?probe=5701fbde3e) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | [514a5308f2](https://linux-hardware.org/?probe=514a5308f2) | Sep 18, 2023 |
| ASUSTek       | X450CA                      | [b43a3aa61c](https://linux-hardware.org/?probe=b43a3aa61c) | Sep 18, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| Apple         | MacBookPro9,2               | [b8459514db](https://linux-hardware.org/?probe=b8459514db) | Sep 17, 2023 |
| Dell          | Inspiron 5566               | [56f2d4d1eb](https://linux-hardware.org/?probe=56f2d4d1eb) | Sep 17, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [48ea99b656](https://linux-hardware.org/?probe=48ea99b656) | Sep 16, 2023 |
| Acer          | Aspire 5750Z                | [d42482a830](https://linux-hardware.org/?probe=d42482a830) | Sep 16, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [f95cfdee8d](https://linux-hardware.org/?probe=f95cfdee8d) | Sep 16, 2023 |
| Dell          | Latitude E6430              | [a426075604](https://linux-hardware.org/?probe=a426075604) | Sep 16, 2023 |
| Compaq        | 420                         | [a0ce747ff2](https://linux-hardware.org/?probe=a0ce747ff2) | Sep 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| Digibras      | CL341                       | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Dell          | Vostro 1510                 | [bf4d733039](https://linux-hardware.org/?probe=bf4d733039) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| HP            | Folio 13                    | [9ed048b9e4](https://linux-hardware.org/?probe=9ed048b9e4) | Sep 14, 2023 |
| Acer          | Swift SF314-511             | [4714deba45](https://linux-hardware.org/?probe=4714deba45) | Sep 14, 2023 |
| Dell          | Vostro 1520                 | [5d70233702](https://linux-hardware.org/?probe=5d70233702) | Sep 14, 2023 |
| Dell          | Inspiron 5566               | [6c9eaad10e](https://linux-hardware.org/?probe=6c9eaad10e) | Sep 13, 2023 |
| Positivo      | C14CR21                     | [9d48466eab](https://linux-hardware.org/?probe=9d48466eab) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Dell          | Latitude E4300              | [ed27d2d51c](https://linux-hardware.org/?probe=ed27d2d51c) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Valve         | Jupiter                     | [bee3c23461](https://linux-hardware.org/?probe=bee3c23461) | Sep 12, 2023 |
| Dell          | Inspiron 15-3567            | [cb58094846](https://linux-hardware.org/?probe=cb58094846) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| HP            | EliteBook 840 G6            | [4318e0630c](https://linux-hardware.org/?probe=4318e0630c) | Sep 12, 2023 |
| LG Electro... | C400-G.BC22P1               | [caef8df1be](https://linux-hardware.org/?probe=caef8df1be) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [564a2ea72e](https://linux-hardware.org/?probe=564a2ea72e) | Sep 12, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [68f0df2a6c](https://linux-hardware.org/?probe=68f0df2a6c) | Sep 12, 2023 |
| Dell          | Latitude E6420              | [2a15e9a8e0](https://linux-hardware.org/?probe=2a15e9a8e0) | Sep 12, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | [a1f824e885](https://linux-hardware.org/?probe=a1f824e885) | Sep 12, 2023 |
| Positivo      | S14CT01                     | [57ed555d4b](https://linux-hardware.org/?probe=57ed555d4b) | Sep 11, 2023 |
| Dell          | Inspiron 5458               | [ab3824f3d0](https://linux-hardware.org/?probe=ab3824f3d0) | Sep 11, 2023 |
| Acer          | Aspire A315-23              | [ecdef7173c](https://linux-hardware.org/?probe=ecdef7173c) | Sep 11, 2023 |
| Acer          | Aspire A515-47              | [fdc2e70c28](https://linux-hardware.org/?probe=fdc2e70c28) | Sep 11, 2023 |
| Dell          | Vostro 3501                 | [7caa16d219](https://linux-hardware.org/?probe=7caa16d219) | Sep 11, 2023 |
| Dell          | Latitude E6420              | [7e57362cdc](https://linux-hardware.org/?probe=7e57362cdc) | Sep 11, 2023 |
| ASUSTek       | X510UAR                     | [671415f9ca](https://linux-hardware.org/?probe=671415f9ca) | Sep 11, 2023 |
| Samsung       | 530XBB                      | [f6039477c2](https://linux-hardware.org/?probe=f6039477c2) | Sep 11, 2023 |
| Sony          | VGN-FZ140E                  | [361226919e](https://linux-hardware.org/?probe=361226919e) | Sep 11, 2023 |
| Samsung       | 550XED                      | [69d754d35b](https://linux-hardware.org/?probe=69d754d35b) | Sep 11, 2023 |
| Samsung       | 550XED                      | [8187eca3e3](https://linux-hardware.org/?probe=8187eca3e3) | Sep 11, 2023 |
| Dell          | Vostro 3550                 | [4f0a6ec78c](https://linux-hardware.org/?probe=4f0a6ec78c) | Sep 10, 2023 |
| Positivo      | C464F                       | [e8154e06d4](https://linux-hardware.org/?probe=e8154e06d4) | Sep 10, 2023 |
| Dell          | G15 5511                    | [c382a29576](https://linux-hardware.org/?probe=c382a29576) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| Dell          | Latitude 7390               | [3644f0b002](https://linux-hardware.org/?probe=3644f0b002) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7c5a19bc69](https://linux-hardware.org/?probe=7c5a19bc69) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b05fdf4d62](https://linux-hardware.org/?probe=b05fdf4d62) | Sep 08, 2023 |
| Digibras      | NH4CU03                     | [0d0d0bf884](https://linux-hardware.org/?probe=0d0d0bf884) | Sep 07, 2023 |
| HP            | G42                         | [b33a0d0bf6](https://linux-hardware.org/?probe=b33a0d0bf6) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [89772ef854](https://linux-hardware.org/?probe=89772ef854) | Sep 07, 2023 |
| ASUSTek       | N56VZ                       | [37b42fff22](https://linux-hardware.org/?probe=37b42fff22) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9ea6ff204](https://linux-hardware.org/?probe=c9ea6ff204) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [2eae1044fc](https://linux-hardware.org/?probe=2eae1044fc) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | [4e54155977](https://linux-hardware.org/?probe=4e54155977) | Sep 07, 2023 |
| Samsung       | 300E5M/300E5L               | [8274cbca33](https://linux-hardware.org/?probe=8274cbca33) | Sep 07, 2023 |
| Acer          | AO722                       | [ae49a1e9c0](https://linux-hardware.org/?probe=ae49a1e9c0) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | [db4ba96400](https://linux-hardware.org/?probe=db4ba96400) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e207539e68](https://linux-hardware.org/?probe=e207539e68) | Sep 07, 2023 |
| Multilaser    | PC31X                       | [96d451c4a5](https://linux-hardware.org/?probe=96d451c4a5) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7410c2416c](https://linux-hardware.org/?probe=7410c2416c) | Sep 07, 2023 |
| Alienware     | m15 R7                      | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Dell          | Inspiron 7460               | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| Samsung       | RF511/RF411/RF711           | [ef99cba7a5](https://linux-hardware.org/?probe=ef99cba7a5) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [29f1d7759a](https://linux-hardware.org/?probe=29f1d7759a) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [344a00d524](https://linux-hardware.org/?probe=344a00d524) | Sep 06, 2023 |
| Standard      | MB45II/MB45IN               | [1e46c6aa81](https://linux-hardware.org/?probe=1e46c6aa81) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba05ae3ca2](https://linux-hardware.org/?probe=ba05ae3ca2) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [299a459ec5](https://linux-hardware.org/?probe=299a459ec5) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [0deab6fc8b](https://linux-hardware.org/?probe=0deab6fc8b) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | [aa37593b87](https://linux-hardware.org/?probe=aa37593b87) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | [230cd8c32e](https://linux-hardware.org/?probe=230cd8c32e) | Sep 06, 2023 |
| Dell          | G3 3500                     | [5da26d2241](https://linux-hardware.org/?probe=5da26d2241) | Sep 06, 2023 |
| Valve         | Jupiter                     | [da71ec43ea](https://linux-hardware.org/?probe=da71ec43ea) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [479d5ea49e](https://linux-hardware.org/?probe=479d5ea49e) | Sep 06, 2023 |
| Acer          | Aspire 5750Z                | [5bec99a137](https://linux-hardware.org/?probe=5bec99a137) | Sep 05, 2023 |
| Dell          | Inspiron 7560               | [dc22012520](https://linux-hardware.org/?probe=dc22012520) | Sep 05, 2023 |
| Dell          | G15 5530                    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| HP            | EliteBook 8470p             | [a658addd87](https://linux-hardware.org/?probe=a658addd87) | Sep 05, 2023 |
| Notebook      | NJx0MU                      | [c02fef3ca2](https://linux-hardware.org/?probe=c02fef3ca2) | Sep 05, 2023 |
| HP            | EliteBook 8470p             | [5cb02e099f](https://linux-hardware.org/?probe=5cb02e099f) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire A315-56              | [1f090fc4fd](https://linux-hardware.org/?probe=1f090fc4fd) | Sep 04, 2023 |
| Dell          | Inspiron 7580               | [b021fe57a6](https://linux-hardware.org/?probe=b021fe57a6) | Sep 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [8253da4d01](https://linux-hardware.org/?probe=8253da4d01) | Sep 04, 2023 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [d2ac233994](https://linux-hardware.org/?probe=d2ac233994) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Compaq        | 430                         | [ac9fb09e14](https://linux-hardware.org/?probe=ac9fb09e14) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [aeebc4664f](https://linux-hardware.org/?probe=aeebc4664f) | Sep 04, 2023 |
| HP            | ENVY 14 SPECTRE             | [1f0a26899c](https://linux-hardware.org/?probe=1f0a26899c) | Sep 04, 2023 |
| HP            | 1000                        | [59cd8d1250](https://linux-hardware.org/?probe=59cd8d1250) | Sep 04, 2023 |
| Notebook      | NJx0MU                      | [1c048ac799](https://linux-hardware.org/?probe=1c048ac799) | Sep 04, 2023 |
| Samsung       | RV415                       | [dc6aa3101f](https://linux-hardware.org/?probe=dc6aa3101f) | Sep 03, 2023 |
| Samsung       | RF511/RF411/RF711           | [522a10f139](https://linux-hardware.org/?probe=522a10f139) | Sep 03, 2023 |
| HP            | Folio 13                    | [d5844cc9e8](https://linux-hardware.org/?probe=d5844cc9e8) | Sep 03, 2023 |
| Acer          | Aspire 5750Z                | [f0b466e572](https://linux-hardware.org/?probe=f0b466e572) | Sep 03, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | [b9de538f7e](https://linux-hardware.org/?probe=b9de538f7e) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [c93a88de93](https://linux-hardware.org/?probe=c93a88de93) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [76b9023610](https://linux-hardware.org/?probe=76b9023610) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f5f8737b58](https://linux-hardware.org/?probe=f5f8737b58) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Samsung       | 530XBB                      | [30365848c4](https://linux-hardware.org/?probe=30365848c4) | Sep 02, 2023 |
| Dell          | Latitude 7400               | [c98434cc21](https://linux-hardware.org/?probe=c98434cc21) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| Samsung       | 500R5L/501R5L/500R5P        | [681c0ca0f9](https://linux-hardware.org/?probe=681c0ca0f9) | Sep 02, 2023 |
| Dell          | Latitude 2120               | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Dell          | Latitude 3410               | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Samsung       | 370E4K                      | [19f41e00da](https://linux-hardware.org/?probe=19f41e00da) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| Samsung       | 550XED                      | [ba2fe18193](https://linux-hardware.org/?probe=ba2fe18193) | Sep 01, 2023 |
| Dell          | G15 5520                    | [9cfb8ce55a](https://linux-hardware.org/?probe=9cfb8ce55a) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1f29e90c7f](https://linux-hardware.org/?probe=1f29e90c7f) | Sep 01, 2023 |
| Positivo      | Mobile                      | [3b32864073](https://linux-hardware.org/?probe=3b32864073) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Google        | Barla                       | [1beaca005d](https://linux-hardware.org/?probe=1beaca005d) | Sep 01, 2023 |
| HP            | Presario CQ43               | [9a02828a68](https://linux-hardware.org/?probe=9a02828a68) | Sep 01, 2023 |
| Dell          | Inspiron N4050              | [311af8113f](https://linux-hardware.org/?probe=311af8113f) | Aug 31, 2023 |
| Acer          | Predator PH315-52           | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [064705b919](https://linux-hardware.org/?probe=064705b919) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Dell          | Inspiron 15-3567            | [9e1df9ff88](https://linux-hardware.org/?probe=9e1df9ff88) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Dell          | G15 5530                    | [1027c8fe19](https://linux-hardware.org/?probe=1027c8fe19) | Aug 30, 2023 |
| Avell High... | C62 MOB                     | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2a5afc6557](https://linux-hardware.org/?probe=2a5afc6557) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [a5f9c0a211](https://linux-hardware.org/?probe=a5f9c0a211) | Aug 29, 2023 |
| Sony          | VPCEA36FX                   | [174aefbf35](https://linux-hardware.org/?probe=174aefbf35) | Aug 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fd0950b7c1](https://linux-hardware.org/?probe=fd0950b7c1) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [94f2581f9f](https://linux-hardware.org/?probe=94f2581f9f) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Aspire 5741Z                | [2127326562](https://linux-hardware.org/?probe=2127326562) | Aug 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [30006f030a](https://linux-hardware.org/?probe=30006f030a) | Aug 28, 2023 |
| Acer          | Aspire 4738                 | [6051c9190a](https://linux-hardware.org/?probe=6051c9190a) | Aug 28, 2023 |
| Apple         | MacBookPro16,2              | [65408b783f](https://linux-hardware.org/?probe=65408b783f) | Aug 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [e02ef868a3](https://linux-hardware.org/?probe=e02ef868a3) | Aug 28, 2023 |
| Positivo      | C14CU51                     | [7fa280c987](https://linux-hardware.org/?probe=7fa280c987) | Aug 28, 2023 |
| Dell          | Inspiron 5590               | [5036ce79f9](https://linux-hardware.org/?probe=5036ce79f9) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8b82375189](https://linux-hardware.org/?probe=8b82375189) | Aug 27, 2023 |
| Dell          | Inspiron 5502               | [b2ecdef159](https://linux-hardware.org/?probe=b2ecdef159) | Aug 27, 2023 |
| Dell          | Vostro 3501                 | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| LG Electro... | A530-T.BE76P1               | [6b9ae23c76](https://linux-hardware.org/?probe=6b9ae23c76) | Aug 27, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | [633ddecba0](https://linux-hardware.org/?probe=633ddecba0) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [a284c141d8](https://linux-hardware.org/?probe=a284c141d8) | Aug 27, 2023 |
| Timi          | TM1701                      | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [7566a0ed19](https://linux-hardware.org/?probe=7566a0ed19) | Aug 27, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35fede08aa](https://linux-hardware.org/?probe=35fede08aa) | Aug 26, 2023 |
| Positivo      | CHT14B                      | [81a8519b9e](https://linux-hardware.org/?probe=81a8519b9e) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [c0957b3538](https://linux-hardware.org/?probe=c0957b3538) | Aug 26, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [01750cc1d8](https://linux-hardware.org/?probe=01750cc1d8) | Aug 26, 2023 |
| Samsung       | RV419/RV420                 | [77e9d34f16](https://linux-hardware.org/?probe=77e9d34f16) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | [f0f9f25268](https://linux-hardware.org/?probe=f0f9f25268) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | [95aa33fc09](https://linux-hardware.org/?probe=95aa33fc09) | Aug 26, 2023 |
| Google        | Kasumi                      | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| Dell          | Latitude E6440              | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [878476c63f](https://linux-hardware.org/?probe=878476c63f) | Aug 25, 2023 |
| Acer          | Nitro AN515-44              | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Samsung       | RV419/RV420                 | [275cd1500e](https://linux-hardware.org/?probe=275cd1500e) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | [49769c9b38](https://linux-hardware.org/?probe=49769c9b38) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | [e3bc104b50](https://linux-hardware.org/?probe=e3bc104b50) | Aug 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [decfff1e51](https://linux-hardware.org/?probe=decfff1e51) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Dell          | Vostro 5470                 | [2e62ce7973](https://linux-hardware.org/?probe=2e62ce7973) | Aug 25, 2023 |
| Acer          | Aspire A315-23              | [34e1a0c5c4](https://linux-hardware.org/?probe=34e1a0c5c4) | Aug 24, 2023 |
| Samsung       | 300E5M/300E5L               | [4d99c3a598](https://linux-hardware.org/?probe=4d99c3a598) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |
| Dell          | Inspiron 7572               | [84f4498af0](https://linux-hardware.org/?probe=84f4498af0) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | [370de86ed7](https://linux-hardware.org/?probe=370de86ed7) | Aug 24, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [5e5059f835](https://linux-hardware.org/?probe=5e5059f835) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| Dell          | System XPS L502X            | [a5357a41b4](https://linux-hardware.org/?probe=a5357a41b4) | Aug 23, 2023 |
| Acer          | Aspire A314-35              | [c9896d5610](https://linux-hardware.org/?probe=c9896d5610) | Aug 23, 2023 |
| Positivo      | M7X0S Bottom                | [f78713080f](https://linux-hardware.org/?probe=f78713080f) | Aug 23, 2023 |
| Positivo      | C14CU51                     | [b8c9fbc7b7](https://linux-hardware.org/?probe=b8c9fbc7b7) | Aug 23, 2023 |
| Samsung       | 370E4K                      | [074e0669c7](https://linux-hardware.org/?probe=074e0669c7) | Aug 22, 2023 |
| Dell          | G3 3579                     | [49b4227da5](https://linux-hardware.org/?probe=49b4227da5) | Aug 22, 2023 |
| Dell          | Inspiron N4050              | [7d5c45785c](https://linux-hardware.org/?probe=7d5c45785c) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f2d55c9619](https://linux-hardware.org/?probe=f2d55c9619) | Aug 22, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [698fbb24ed](https://linux-hardware.org/?probe=698fbb24ed) | Aug 22, 2023 |
| Acer          | Aspire 5250                 | [8812e20762](https://linux-hardware.org/?probe=8812e20762) | Aug 22, 2023 |
| ASUSTek       | X510UAR                     | [cdef569014](https://linux-hardware.org/?probe=cdef569014) | Aug 22, 2023 |
| Acer          | Aspire E5-553G              | [d5350f0d1c](https://linux-hardware.org/?probe=d5350f0d1c) | Aug 22, 2023 |
| ASUSTek       | Z450UAK                     | [68fb2ce5ec](https://linux-hardware.org/?probe=68fb2ce5ec) | Aug 22, 2023 |
| Samsung       | 270E5J/2570EJ               | [04a07b8fa6](https://linux-hardware.org/?probe=04a07b8fa6) | Aug 22, 2023 |
| Intel         | HuronRiver Platform         | [7cf233eb4d](https://linux-hardware.org/?probe=7cf233eb4d) | Aug 22, 2023 |
| Sony          | SVE14123CBW                 | [b7891b51b2](https://linux-hardware.org/?probe=b7891b51b2) | Aug 21, 2023 |
| Sony          | SVE14123CBW                 | [9730d7f8f5](https://linux-hardware.org/?probe=9730d7f8f5) | Aug 21, 2023 |
| Acer          | Aspire 5750Z                | [8c15b251a7](https://linux-hardware.org/?probe=8c15b251a7) | Aug 21, 2023 |
| Dell          | Inspiron 15 3515            | [534e1dc3e5](https://linux-hardware.org/?probe=534e1dc3e5) | Aug 21, 2023 |
| ASUSTek       | X510URR                     | [d1ee285db9](https://linux-hardware.org/?probe=d1ee285db9) | Aug 21, 2023 |
| Packard Be... | EasyNote MZ36               | [d628db6497](https://linux-hardware.org/?probe=d628db6497) | Aug 21, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [feeca36aa9](https://linux-hardware.org/?probe=feeca36aa9) | Aug 21, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e2c346429e](https://linux-hardware.org/?probe=e2c346429e) | Aug 21, 2023 |
| Clevo         | W240HU/W250HUQ              | [4590ebf626](https://linux-hardware.org/?probe=4590ebf626) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b86411b8b0](https://linux-hardware.org/?probe=b86411b8b0) | Aug 21, 2023 |
| Dell          | Inspiron 5737               | [665dbda021](https://linux-hardware.org/?probe=665dbda021) | Aug 21, 2023 |
| Sony          | VPCEG15FB                   | [e3b2126509](https://linux-hardware.org/?probe=e3b2126509) | Aug 20, 2023 |
| Dell          | Inspiron 5558               | [ee47d4b6a7](https://linux-hardware.org/?probe=ee47d4b6a7) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Acer          | Aspire 5750                 | [5b7f4b5a45](https://linux-hardware.org/?probe=5b7f4b5a45) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Acer          | Aspire A315-53              | [03bd8885a0](https://linux-hardware.org/?probe=03bd8885a0) | Aug 20, 2023 |
| EUROCOM       | RACER 2.0                   | [b27f687c16](https://linux-hardware.org/?probe=b27f687c16) | Aug 20, 2023 |
| Alienware     | m15 R4                      | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [f75baa8a07](https://linux-hardware.org/?probe=f75baa8a07) | Aug 19, 2023 |
| Alienware     | m15 R4                      | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Samsung       | 550XBE/350XBE               | [1d08f612ba](https://linux-hardware.org/?probe=1d08f612ba) | Aug 19, 2023 |
| Dell          | Inspiron 5447               | [07a24f8880](https://linux-hardware.org/?probe=07a24f8880) | Aug 19, 2023 |
| ASUSTek       | UX410UQK                    | [cf7a7946dc](https://linux-hardware.org/?probe=cf7a7946dc) | Aug 19, 2023 |
| Samsung       | 300E5M/300E5L               | [e625280525](https://linux-hardware.org/?probe=e625280525) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f44bc6c057](https://linux-hardware.org/?probe=f44bc6c057) | Aug 19, 2023 |
| Positivo      | CHT14B                      | [28106aa94b](https://linux-hardware.org/?probe=28106aa94b) | Aug 19, 2023 |
| Dell          | Inspiron 7520               | [3cdfdae368](https://linux-hardware.org/?probe=3cdfdae368) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| Toshiba       | IS 1422                     | [2ad1bbf471](https://linux-hardware.org/?probe=2ad1bbf471) | Aug 18, 2023 |
| Dell          | Inspiron 15-3567            | [58af8f5102](https://linux-hardware.org/?probe=58af8f5102) | Aug 18, 2023 |
| Acer          | Aspire E1-421               | [bab5968f80](https://linux-hardware.org/?probe=bab5968f80) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [55b9d87888](https://linux-hardware.org/?probe=55b9d87888) | Aug 18, 2023 |
| Dell          | G3 3579                     | [567acf505b](https://linux-hardware.org/?probe=567acf505b) | Aug 17, 2023 |
| Dell          | Inspiron 15-3567            | [1739e9ff2d](https://linux-hardware.org/?probe=1739e9ff2d) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [1f416788fa](https://linux-hardware.org/?probe=1f416788fa) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [35b8929f7f](https://linux-hardware.org/?probe=35b8929f7f) | Aug 17, 2023 |
| Daten Tecn... | DV3N-4                      | [7a95cb94da](https://linux-hardware.org/?probe=7a95cb94da) | Aug 17, 2023 |
| Acer          | Aspire A315-33              | [a1db467e0a](https://linux-hardware.org/?probe=a1db467e0a) | Aug 16, 2023 |
| Acer          | Aspire 5050                 | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8733f22b33](https://linux-hardware.org/?probe=8733f22b33) | Aug 16, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [d7ec063f46](https://linux-hardware.org/?probe=d7ec063f46) | Aug 16, 2023 |
| Apple         | MacBookPro11,1              | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| Dell          | Vostro 3501                 | [c36d4d9de0](https://linux-hardware.org/?probe=c36d4d9de0) | Aug 15, 2023 |
| Samsung       | 550XDA                      | [5e5606074a](https://linux-hardware.org/?probe=5e5606074a) | Aug 15, 2023 |
| Multilaser    | PC13X                       | [d79767b027](https://linux-hardware.org/?probe=d79767b027) | Aug 15, 2023 |
| Topstar       | Cantiga & ICH9M Chipset     | [5102056c71](https://linux-hardware.org/?probe=5102056c71) | Aug 15, 2023 |
| Dell          | Latitude E6530              | [9cbe752127](https://linux-hardware.org/?probe=9cbe752127) | Aug 15, 2023 |
| Positivo      | S14CT01                     | [e865565207](https://linux-hardware.org/?probe=e865565207) | Aug 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [da3036b8e3](https://linux-hardware.org/?probe=da3036b8e3) | Aug 14, 2023 |
| Positivo      | N1250                       | [8c1d1f89f7](https://linux-hardware.org/?probe=8c1d1f89f7) | Aug 14, 2023 |
| Positivo      | N1250                       | [17ce4f01a7](https://linux-hardware.org/?probe=17ce4f01a7) | Aug 14, 2023 |
| Positivo      | Mobile                      | [4111fa6520](https://linux-hardware.org/?probe=4111fa6520) | Aug 14, 2023 |
| Alienware     | m15 R7                      | [a501a43d37](https://linux-hardware.org/?probe=a501a43d37) | Aug 14, 2023 |
| Acer          | Aspire E1-571               | [0afd683e48](https://linux-hardware.org/?probe=0afd683e48) | Aug 13, 2023 |
| HP            | 450                         | [242d41f5e9](https://linux-hardware.org/?probe=242d41f5e9) | Aug 13, 2023 |
| Acer          | Aspire A515-51              | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| Daten Tecn... | DT02-M4                     | [39acd7fbd5](https://linux-hardware.org/?probe=39acd7fbd5) | Aug 13, 2023 |
| HP            | Folio 13                    | [62fcebde8c](https://linux-hardware.org/?probe=62fcebde8c) | Aug 13, 2023 |
| Notebook      | NJx0MU                      | [b97fcb7117](https://linux-hardware.org/?probe=b97fcb7117) | Aug 12, 2023 |
| Samsung       | 300E5M/300E5L               | [9aa2cd7b81](https://linux-hardware.org/?probe=9aa2cd7b81) | Aug 12, 2023 |
| Notebook      | NJx0MU                      | [6f230d02c1](https://linux-hardware.org/?probe=6f230d02c1) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Multilaser    | PC024                       | [3311e26ac5](https://linux-hardware.org/?probe=3311e26ac5) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [53196a01fa](https://linux-hardware.org/?probe=53196a01fa) | Aug 12, 2023 |
| Dell          | Inspiron 5558               | [5bb31ccda3](https://linux-hardware.org/?probe=5bb31ccda3) | Aug 12, 2023 |
| Dell          | G3 3579                     | [09ba53e3c1](https://linux-hardware.org/?probe=09ba53e3c1) | Aug 12, 2023 |
| Acer          | Aspire F5-573G              | [019f3a6d1f](https://linux-hardware.org/?probe=019f3a6d1f) | Aug 11, 2023 |
| Acer          | Nitro AN517-54              | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| Unknown       | Unknown                     | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| Dell          | G15 5520                    | [3bec284af8](https://linux-hardware.org/?probe=3bec284af8) | Aug 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | [ea4ae0e0f3](https://linux-hardware.org/?probe=ea4ae0e0f3) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [97e0c46487](https://linux-hardware.org/?probe=97e0c46487) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | [2db90ee24e](https://linux-hardware.org/?probe=2db90ee24e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [30748e95eb](https://linux-hardware.org/?probe=30748e95eb) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Acer          | Aspire E5-571G              | [6c55de5ac8](https://linux-hardware.org/?probe=6c55de5ac8) | Aug 10, 2023 |
| Avell High... | A70 HYB                     | [9b03ae1cd3](https://linux-hardware.org/?probe=9b03ae1cd3) | Aug 10, 2023 |
| HP            | Folio 13                    | [67121fc711](https://linux-hardware.org/?probe=67121fc711) | Aug 10, 2023 |
| Avell         | A70 ION                     | [6ab02a34e4](https://linux-hardware.org/?probe=6ab02a34e4) | Aug 10, 2023 |
| Avell         | A70 ION                     | [b71c176ce3](https://linux-hardware.org/?probe=b71c176ce3) | Aug 10, 2023 |
| Acer          | Nitro AN517-51              | [bd3b7989f0](https://linux-hardware.org/?probe=bd3b7989f0) | Aug 10, 2023 |
| Dell          | Vostro 3501                 | [d606f83745](https://linux-hardware.org/?probe=d606f83745) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| Positivo      | Presley 3                   | [16ddbd1a75](https://linux-hardware.org/?probe=16ddbd1a75) | Aug 10, 2023 |
| HP            | Folio 13                    | [889aae1772](https://linux-hardware.org/?probe=889aae1772) | Aug 10, 2023 |
| Positivo      | Presley 3                   | [9edde2ea30](https://linux-hardware.org/?probe=9edde2ea30) | Aug 09, 2023 |
| ASRock        | H81M-HG4 R4.0               | [26c322239f](https://linux-hardware.org/?probe=26c322239f) | Aug 09, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | [4bd13ae71d](https://linux-hardware.org/?probe=4bd13ae71d) | Aug 09, 2023 |
| Acer          | Aspire A515-54G             | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| Dell          | Inspiron 15 3511            | [13cec81a99](https://linux-hardware.org/?probe=13cec81a99) | Aug 08, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dd127ca2df](https://linux-hardware.org/?probe=dd127ca2df) | Aug 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [788c24d04a](https://linux-hardware.org/?probe=788c24d04a) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ec7a911951](https://linux-hardware.org/?probe=ec7a911951) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Acer          | Aspire E5-553G              | [f7845429c8](https://linux-hardware.org/?probe=f7845429c8) | Aug 07, 2023 |
| Acer          | Nitro AN517-52              | [d24385ceb8](https://linux-hardware.org/?probe=d24385ceb8) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| HP            | 250 G6 Notebook PC          | [c130dece41](https://linux-hardware.org/?probe=c130dece41) | Aug 06, 2023 |
| Dell          | Inspiron 5547               | [8f33c0cf28](https://linux-hardware.org/?probe=8f33c0cf28) | Aug 06, 2023 |
| Notebook      | 1745                        | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |
| HP            | Pavilion dm4                | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [52b9918d42](https://linux-hardware.org/?probe=52b9918d42) | Aug 06, 2023 |
| Dell          | Inspiron N4050              | [af35c9ce49](https://linux-hardware.org/?probe=af35c9ce49) | Aug 05, 2023 |
| Acer          | Aspire E5-553G              | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6de5534e97](https://linux-hardware.org/?probe=6de5534e97) | Aug 05, 2023 |
| Dell          | Latitude 5410               | [2838e5d74c](https://linux-hardware.org/?probe=2838e5d74c) | Aug 05, 2023 |
| Dell          | Latitude E5440              | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| Multilaser    | PC024                       | [85a4bdd497](https://linux-hardware.org/?probe=85a4bdd497) | Aug 05, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [f03fa524d7](https://linux-hardware.org/?probe=f03fa524d7) | Aug 05, 2023 |
| Multilaser    | PC13X                       | [2f79cffddd](https://linux-hardware.org/?probe=2f79cffddd) | Aug 05, 2023 |
| HP            | Pavilion g4                 | [2094186715](https://linux-hardware.org/?probe=2094186715) | Aug 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [24a5183e69](https://linux-hardware.org/?probe=24a5183e69) | Aug 05, 2023 |
| Dell          | G15 5520                    | [baca0d14f5](https://linux-hardware.org/?probe=baca0d14f5) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8292d9f518](https://linux-hardware.org/?probe=8292d9f518) | Aug 04, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | [8b6b5ff142](https://linux-hardware.org/?probe=8b6b5ff142) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Acer          | Nitro AN517-54              | [aee5a21c76](https://linux-hardware.org/?probe=aee5a21c76) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | [bd88b4e8fa](https://linux-hardware.org/?probe=bd88b4e8fa) | Aug 04, 2023 |
| ASUSTek       | UX490UAR                    | [6a305978e3](https://linux-hardware.org/?probe=6a305978e3) | Aug 03, 2023 |
| Dell          | Inspiron 5566               | [21d7f13381](https://linux-hardware.org/?probe=21d7f13381) | Aug 03, 2023 |
| Lenovo        | ThinkPad Edge E431 6277C... | [6c542a6490](https://linux-hardware.org/?probe=6c542a6490) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [25dcc9a7c5](https://linux-hardware.org/?probe=25dcc9a7c5) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Positivo      | Q232B                       | [006d77a18c](https://linux-hardware.org/?probe=006d77a18c) | Aug 02, 2023 |
| Acer          | Aspire E1-572               | [af04d8d764](https://linux-hardware.org/?probe=af04d8d764) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Dell          | Inspiron 5566               | [c4e404738e](https://linux-hardware.org/?probe=c4e404738e) | Aug 01, 2023 |
| Apple         | MacBookPro8,1               | [56e2fa207e](https://linux-hardware.org/?probe=56e2fa207e) | Aug 01, 2023 |
| Itautec       | Infoway a7420               | [da7459a0ea](https://linux-hardware.org/?probe=da7459a0ea) | Aug 01, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [1f69ed5c1e](https://linux-hardware.org/?probe=1f69ed5c1e) | Aug 01, 2023 |
| HP            | Pavilion 14                 | [313aedd888](https://linux-hardware.org/?probe=313aedd888) | Jul 31, 2023 |
| Acer          | Aspire V3-571               | [9b9830aedf](https://linux-hardware.org/?probe=9b9830aedf) | Jul 31, 2023 |
| Dell          | Inspiron 7520               | [b87690f890](https://linux-hardware.org/?probe=b87690f890) | Jul 31, 2023 |
| Dell          | Latitude E5510              | [b9208e8c08](https://linux-hardware.org/?probe=b9208e8c08) | Jul 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | [8e49dde20d](https://linux-hardware.org/?probe=8e49dde20d) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | [8d6d8b9243](https://linux-hardware.org/?probe=8d6d8b9243) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | [13e9f3fa3c](https://linux-hardware.org/?probe=13e9f3fa3c) | Jul 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | [9268d1c4f9](https://linux-hardware.org/?probe=9268d1c4f9) | Jul 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Acer          | Aspire A315-53              | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [f3de23350d](https://linux-hardware.org/?probe=f3de23350d) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [3be466c09c](https://linux-hardware.org/?probe=3be466c09c) | Jul 30, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [2a0777f1fd](https://linux-hardware.org/?probe=2a0777f1fd) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [24c271e6fd](https://linux-hardware.org/?probe=24c271e6fd) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [bb2245d195](https://linux-hardware.org/?probe=bb2245d195) | Jul 30, 2023 |
| Dell          | Inspiron 5577               | [10b634ac99](https://linux-hardware.org/?probe=10b634ac99) | Jul 29, 2023 |
| Acer          | Nitro AN515-52              | [393c4b7fd3](https://linux-hardware.org/?probe=393c4b7fd3) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| HP            | Folio 13                    | [baaa648a4b](https://linux-hardware.org/?probe=baaa648a4b) | Jul 29, 2023 |
| Lenovo        | Unknown                     | [a1dac68b95](https://linux-hardware.org/?probe=a1dac68b95) | Jul 29, 2023 |
| Samsung       | 550XDA                      | [c140c9176e](https://linux-hardware.org/?probe=c140c9176e) | Jul 29, 2023 |
| Dell          | Inspiron N4050              | [701402e2a7](https://linux-hardware.org/?probe=701402e2a7) | Jul 29, 2023 |
| HP            | 250 G8 Notebook PC          | [502747dd18](https://linux-hardware.org/?probe=502747dd18) | Jul 29, 2023 |
| Dell          | Latitude 5400               | [9416ce803c](https://linux-hardware.org/?probe=9416ce803c) | Jul 28, 2023 |
| Dell          | Inspiron 7520               | [7509644961](https://linux-hardware.org/?probe=7509644961) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [8ca0357bf1](https://linux-hardware.org/?probe=8ca0357bf1) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [bca814cbb5](https://linux-hardware.org/?probe=bca814cbb5) | Jul 28, 2023 |
| Acer          | Aspire A515-45              | [6287e66ff2](https://linux-hardware.org/?probe=6287e66ff2) | Jul 27, 2023 |
| HP            | EliteBook 8540w             | [d91f2ff8ba](https://linux-hardware.org/?probe=d91f2ff8ba) | Jul 27, 2023 |
| A14CR         | Unknown                     | [4ceb4f6761](https://linux-hardware.org/?probe=4ceb4f6761) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Biostar       | B450MHP                     | [bb12598429](https://linux-hardware.org/?probe=bb12598429) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| Multilaser    | PC024                       | [fa5b5a3146](https://linux-hardware.org/?probe=fa5b5a3146) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| HP            | Folio 13                    | [a3269c0930](https://linux-hardware.org/?probe=a3269c0930) | Jul 26, 2023 |
| HP            | Pavilion 11 x360 PC         | [8daa291377](https://linux-hardware.org/?probe=8daa291377) | Jul 26, 2023 |
| Dell          | G3 3579                     | [b6b50ffa46](https://linux-hardware.org/?probe=b6b50ffa46) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [2e810b1c93](https://linux-hardware.org/?probe=2e810b1c93) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [4171fc8925](https://linux-hardware.org/?probe=4171fc8925) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | [f6400e37f6](https://linux-hardware.org/?probe=f6400e37f6) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | [7814bf14ac](https://linux-hardware.org/?probe=7814bf14ac) | Jul 26, 2023 |
| Valve         | Jupiter                     | [8ba9103155](https://linux-hardware.org/?probe=8ba9103155) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [9878121979](https://linux-hardware.org/?probe=9878121979) | Jul 26, 2023 |
| Notebook      | NJx0MU                      | [f720b1a032](https://linux-hardware.org/?probe=f720b1a032) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| Dell          | Inspiron 3501               | [62bcc903fd](https://linux-hardware.org/?probe=62bcc903fd) | Jul 25, 2023 |
| Acer          | Aspire A514-54              | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| Acer          | Aspire E5-571G              | [3f39162908](https://linux-hardware.org/?probe=3f39162908) | Jul 25, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 937       | 10.52%  |
| Ubuntu 18.04       | 602       | 6.76%   |
| Ubuntu 22.04       | 408       | 4.58%   |
| Pop!_OS 20.04      | 194       | 2.18%   |
| Linux Mint 20      | 190       | 2.13%   |
| Pop!_OS 22.04      | 183       | 2.05%   |
| Linux Mint 19.3    | 166       | 1.86%   |
| OpenMandriva 4.2   | 162       | 1.82%   |
| OpenMandriva 4.3   | 154       | 1.73%   |
| Linux Mint 20.3    | 152       | 1.71%   |
| Manjaro            | 142       | 1.59%   |
| Zorin 16           | 134       | 1.5%    |
| Linux Mint 19.1    | 122       | 1.37%   |
| Linux Mint 20.1    | 120       | 1.35%   |
| Fedora 38          | 120       | 1.35%   |
| Debian 11          | 118       | 1.32%   |
| Arch Rolling       | 118       | 1.32%   |
| Ubuntu 19.04       | 117       | 1.31%   |
| Arch               | 114       | 1.28%   |
| Linux Mint 20.2    | 113       | 1.27%   |
| KDE neon 20.04     | 113       | 1.27%   |
| Ubuntu 19.10       | 106       | 1.19%   |
| Linux Mint 21.1    | 106       | 1.19%   |
| Zorin 15           | 94        | 1.06%   |
| Debian 10          | 83        | 0.93%   |
| Fedora 35          | 80        | 0.9%    |
| OpenMandriva 23.01 | 73        | 0.82%   |
| Fedora 34          | 73        | 0.82%   |
| Pop!_OS 21.10      | 71        | 0.8%    |
| Fedora 37          | 71        | 0.8%    |
| Fedora 32          | 69        | 0.77%   |
| Endless 3.7.8      | 69        | 0.77%   |
| Xubuntu 20.04      | 68        | 0.76%   |
| Fedora 36          | 68        | 0.76%   |
| Pop!_OS 21.04      | 67        | 0.75%   |
| Endless 3.9.5      | 67        | 0.75%   |
| Linux Mint 21.2    | 62        | 0.7%    |
| Linux Mint 21      | 62        | 0.7%    |
| Kubuntu 20.04      | 62        | 0.7%    |
| Pop!_OS 20.10      | 60        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2399      | 28.31%  |
| Linux Mint    | 1116      | 13.17%  |
| Endless       | 904       | 10.67%  |
| Fedora        | 577       | 6.81%   |
| Pop!_OS       | 556       | 6.56%   |
| OpenMandriva  | 528       | 6.23%   |
| Debian        | 300       | 3.54%   |
| Manjaro       | 248       | 2.93%   |
| Zorin         | 232       | 2.74%   |
| Arch          | 222       | 2.62%   |
| KDE neon      | 155       | 1.83%   |
| Xubuntu       | 132       | 1.56%   |
| Kubuntu       | 132       | 1.56%   |
| openSUSE      | 91        | 1.07%   |
| Lubuntu       | 77        | 0.91%   |
| Elementary    | 72        | 0.85%   |
| Ubuntu MATE   | 65        | 0.77%   |
| ROSA          | 56        | 0.66%   |
| Ubuntu Unity  | 54        | 0.64%   |
| Kali          | 54        | 0.64%   |
| LMDE          | 48        | 0.57%   |
| ArcoLinux     | 44        | 0.52%   |
| BigLinux      | 35        | 0.41%   |
| Deepin        | 31        | 0.37%   |
| Ubuntu Budgie | 29        | 0.34%   |
| Clear Linux   | 27        | 0.32%   |
| LinuxFX       | 21        | 0.25%   |
| SteamOS       | 19        | 0.22%   |
| EndeavourOS   | 18        | 0.21%   |
| Garuda Linux  | 13        | 0.15%   |
| Parrot        | 12        | 0.14%   |
| Nobara        | 11        | 0.13%   |
| BlackPanther  | 11        | 0.13%   |
| Reborn OS     | 10        | 0.12%   |
| Peppermint    | 10        | 0.12%   |
| MX            | 10        | 0.12%   |
| Devuan        | 10        | 0.12%   |
| CentOS        | 10        | 0.12%   |
| Gentoo        | 9         | 0.11%   |
| UbuntuDDE     | 8         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 471       | 4.91%   |
| 5.8.0-14-generic         | 291       | 3.04%   |
| 5.10.14-desktop-1omv4002 | 156       | 1.63%   |
| 5.16.7-desktop-1omv4003  | 146       | 1.52%   |
| 5.4.0-19-generic         | 114       | 1.19%   |
| 5.3.0-28-generic         | 108       | 1.13%   |
| 5.11.0-35-generic        | 96        | 1%      |
| 5.15.0-56-generic        | 78        | 0.81%   |
| 5.4.0-7634-generic       | 74        | 0.77%   |
| 5.4.0-48-generic         | 72        | 0.75%   |
| 6.1.1-desktop-1omv2290   | 71        | 0.74%   |
| 5.4.0-40-generic         | 70        | 0.73%   |
| 4.15.0-46-generic        | 70        | 0.73%   |
| 5.4.0-26-generic         | 64        | 0.67%   |
| 5.4.0-58-generic         | 61        | 0.64%   |
| 5.4.0-52-generic         | 57        | 0.59%   |
| 5.4.0-47-generic         | 54        | 0.56%   |
| 6.2.6-desktop-1omv2390   | 52        | 0.54%   |
| 5.3.0-19-generic         | 50        | 0.52%   |
| 5.15.0-47-generic        | 50        | 0.52%   |
| 5.3.0-23-generic         | 47        | 0.49%   |
| 5.3.0-46-generic         | 46        | 0.48%   |
| 5.0.0-32-generic         | 46        | 0.48%   |
| 6.4.11-desktop-1omv2390  | 44        | 0.46%   |
| 5.4.0-29-generic         | 44        | 0.46%   |
| 4.18.0-15-generic        | 44        | 0.46%   |
| 5.3.0-40-generic         | 43        | 0.45%   |
| 5.15.0-46-generic        | 43        | 0.45%   |
| 5.4.0-65-generic         | 42        | 0.44%   |
| 5.15.0-52-generic        | 42        | 0.44%   |
| 5.4.0-39-generic         | 41        | 0.43%   |
| 5.0.0-37-generic         | 41        | 0.43%   |
| 5.4.0-80-generic         | 40        | 0.42%   |
| 6.2.6-76060206-generic   | 39        | 0.41%   |
| 5.4.0-70-generic         | 39        | 0.41%   |
| 5.0.0-25-generic         | 39        | 0.41%   |
| 5.15.0-58-generic        | 38        | 0.4%    |
| 5.13.0-30-generic        | 38        | 0.4%    |
| 5.11.0-7620-generic      | 38        | 0.4%    |
| 4.18.0-16-generic        | 38        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1862      | 20.44%  |
| 5.15.0  | 675       | 7.41%   |
| 5.8.0   | 625       | 6.86%   |
| 5.3.0   | 535       | 5.87%   |
| 4.15.0  | 519       | 5.7%    |
| 5.11.0  | 455       | 5%      |
| 5.0.0   | 320       | 3.51%   |
| 5.13.0  | 281       | 3.08%   |
| 4.18.0  | 232       | 2.55%   |
| 5.19.0  | 210       | 2.31%   |
| 5.10.0  | 166       | 1.82%   |
| 6.2.0   | 164       | 1.8%    |
| 5.10.14 | 158       | 1.73%   |
| 5.16.7  | 146       | 1.6%    |
| 4.19.0  | 101       | 1.11%   |
| 6.2.6   | 93        | 1.02%   |
| 6.1.0   | 82        | 0.9%    |
| 6.1.1   | 78        | 0.86%   |
| 6.4.11  | 52        | 0.57%   |
| 5.17.5  | 35        | 0.38%   |
| 6.0.12  | 32        | 0.35%   |
| 5.16.11 | 30        | 0.33%   |
| 5.14.0  | 30        | 0.33%   |
| 4.4.0   | 28        | 0.31%   |
| 6.5.0   | 27        | 0.3%    |
| 5.7.9   | 26        | 0.29%   |
| 6.4.6   | 25        | 0.27%   |
| 4.9.0   | 23        | 0.25%   |
| 5.15.15 | 20        | 0.22%   |
| 6.6.2   | 19        | 0.21%   |
| 6.5.6   | 19        | 0.21%   |
| 6.5.5   | 19        | 0.21%   |
| 6.4.8   | 19        | 0.21%   |
| 5.15.5  | 19        | 0.21%   |
| 6.2.15  | 17        | 0.19%   |
| 6.0.0   | 17        | 0.19%   |
| 5.9.16  | 17        | 0.19%   |
| 5.7.0   | 17        | 0.19%   |
| 5.14.21 | 17        | 0.19%   |
| 5.6.19  | 16        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1935      | 21.5%   |
| 5.15    | 847       | 9.41%   |
| 5.8     | 694       | 7.71%   |
| 5.3     | 579       | 6.43%   |
| 5.11    | 522       | 5.8%    |
| 4.15    | 519       | 5.77%   |
| 5.10    | 430       | 4.78%   |
| 6.2     | 357       | 3.97%   |
| 5.0     | 345       | 3.83%   |
| 5.13    | 336       | 3.73%   |
| 5.16    | 275       | 3.06%   |
| 6.1     | 272       | 3.02%   |
| 5.19    | 257       | 2.86%   |
| 4.18    | 248       | 2.76%   |
| 6.4     | 163       | 1.81%   |
| 6.5     | 129       | 1.43%   |
| 4.19    | 118       | 1.31%   |
| 6.0     | 113       | 1.26%   |
| 5.7     | 101       | 1.12%   |
| 5.17    | 98        | 1.09%   |
| 5.14    | 96        | 1.07%   |
| 5.18    | 78        | 0.87%   |
| 5.6     | 70        | 0.78%   |
| 5.9     | 66        | 0.73%   |
| 6.3     | 63        | 0.7%    |
| 5.12    | 61        | 0.68%   |
| 4.9     | 47        | 0.52%   |
| 6.6     | 43        | 0.48%   |
| 5.5     | 32        | 0.36%   |
| 4.4     | 31        | 0.34%   |
| 5.1     | 28        | 0.31%   |
| 5.2     | 15        | 0.17%   |
| 4.13    | 7         | 0.08%   |
| 4.20    | 5         | 0.06%   |
| 4.14    | 4         | 0.04%   |
| 4.10    | 4         | 0.04%   |
| 4.1     | 4         | 0.04%   |
| 3.10    | 3         | 0.03%   |
| 4.17    | 2         | 0.02%   |
| 6       | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 7896      | 97.78%  |
| i686   | 177       | 2.19%   |
| armv7l | 2         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4196      | 49.74%  |
| KDE5            | 1048      | 12.42%  |
| Unknown         | 998       | 11.83%  |
| X-Cinnamon      | 696       | 8.25%   |
| XFCE            | 554       | 6.57%   |
| MATE            | 210       | 2.49%   |
| KDE             | 160       | 1.9%    |
| Cinnamon        | 138       | 1.64%   |
| LXQt            | 88        | 1.04%   |
| Pantheon        | 66        | 0.78%   |
| Unity           | 56        | 0.66%   |
| Deepin          | 43        | 0.51%   |
| Budgie          | 41        | 0.49%   |
| LXDE            | 35        | 0.41%   |
| KDE4            | 25        | 0.3%    |
| i3              | 24        | 0.28%   |
| GNOME Classic   | 10        | 0.12%   |
| Endless:GNOME   | 10        | 0.12%   |
| sway            | 6         | 0.07%   |
| Hyprland        | 6         | 0.07%   |
| awesome         | 6         | 0.07%   |
| GNOME Flashback | 3         | 0.04%   |
| Enlightenment   | 3         | 0.04%   |
| Openbox         | 2         | 0.02%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Lubuntu         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| icewm           | 1         | 0.01%   |
| i3-with-shmlog  | 1         | 0.01%   |
| Hypr            | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| GNOME-Classic   | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| chadwm          | 1         | 0.01%   |
| bspwm           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6556      | 78.76%  |
| Wayland | 1220      | 14.66%  |
| Unknown | 513       | 6.16%   |
| Tty     | 35        | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5156      | 61.34%  |
| SDDM    | 901       | 10.72%  |
| GDM     | 821       | 9.77%   |
| GDM3    | 698       | 8.3%    |
| LightDM | 497       | 5.91%   |
| TDM     | 292       | 3.47%   |
| KDM     | 26        | 0.31%   |
| XDM     | 7         | 0.08%   |
| SLiM    | 4         | 0.05%   |
| Ly      | 2         | 0.02%   |
| MDM     | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang      | Notebooks | Percent |
|-----------|-----------|---------|
| pt_BR     | 5540      | 67.1%   |
| en_US     | 1542      | 18.68%  |
| Unknown   | 920       | 11.14%  |
| C         | 122       | 1.48%   |
| en_GB     | 44        | 0.53%   |
| pt_PT     | 33        | 0.4%    |
| es_ES     | 14        | 0.17%   |
| en_CA     | 6         | 0.07%   |
| fr_FR     | 5         | 0.06%   |
| de_DE     | 5         | 0.06%   |
| POSIX     | 3         | 0.04%   |
| ja_JP     | 2         | 0.02%   |
| it_IT     | 2         | 0.02%   |
| es_CL     | 2         | 0.02%   |
| en_DK     | 2         | 0.02%   |
| UTF-8     | 1         | 0.01%   |
| ru_RU     | 1         | 0.01%   |
| pt_BR~    | 1         | 0.01%   |
| pt_BRutf8 | 1         | 0.01%   |
| es_VE     | 1         | 0.01%   |
| es_PY     | 1         | 0.01%   |
| es_MX     | 1         | 0.01%   |
| es_AR     | 1         | 0.01%   |
| en_ZA     | 1         | 0.01%   |
| en-US     | 1         | 0.01%   |
| em_US     | 1         | 0.01%   |
| de_CH     | 1         | 0.01%   |
| C.UTF8    | 1         | 0.01%   |
| ar_EG     | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 4177      | 50.45%  |
| BIOS | 4102      | 49.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 6326      | 76.15%  |
| Btrfs   | 733       | 8.82%   |
| Overlay | 567       | 6.83%   |
| Unknown | 389       | 4.68%   |
| Tmpfs   | 166       | 2%      |
| Xfs     | 62        | 0.75%   |
| Zfs     | 29        | 0.35%   |
| Ext2    | 13        | 0.16%   |
| F2fs    | 10        | 0.12%   |
| Ext3    | 10        | 0.12%   |
| Aufs    | 2         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5358      | 64.48%  |
| GPT     | 2190      | 26.35%  |
| MBR     | 762       | 9.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7408      | 90.66%  |
| Yes       | 763       | 9.34%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6404      | 78.12%  |
| Yes       | 1794      | 21.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1866      | 23.11%  |
| Acer                   | 1539      | 19.06%  |
| Lenovo                 | 1034      | 12.81%  |
| Samsung Electronics    | 679       | 8.41%   |
| Hewlett-Packard        | 543       | 6.73%   |
| Positivo               | 519       | 6.43%   |
| ASUSTek Computer       | 473       | 5.86%   |
| Sony                   | 167       | 2.07%   |
| Apple                  | 111       | 1.37%   |
| LG Electronics         | 99        | 1.23%   |
| Avell High Performance | 92        | 1.14%   |
| Digibras               | 76        | 0.94%   |
| Itautec                | 73        | 0.9%    |
| Semp Toshiba           | 68        | 0.84%   |
| Unknown                | 68        | 0.84%   |
| Intel                  | 54        | 0.67%   |
| Compaq                 | 50        | 0.62%   |
| Multilaser             | 49        | 0.61%   |
| Positivo Bahia - VAIO  | 44        | 0.54%   |
| Philco                 | 43        | 0.53%   |
| Toshiba                | 36        | 0.45%   |
| OEM                    | 32        | 0.4%    |
| Notebook               | 28        | 0.35%   |
| Clevo                  | 26        | 0.32%   |
| Gateway                | 23        | 0.28%   |
| Google                 | 21        | 0.26%   |
| Compal                 | 21        | 0.26%   |
| Alienware              | 21        | 0.26%   |
| MSI                    | 19        | 0.24%   |
| Daten Tecnologia       | 16        | 0.2%    |
| Valve                  | 15        | 0.19%   |
| eMachines              | 13        | 0.16%   |
| Standard               | 12        | 0.15%   |
| Quanta                 | 12        | 0.15%   |
| Timi                   | 11        | 0.14%   |
| Chuwi                  | 9         | 0.11%   |
| CCE                    | 7         | 0.09%   |
| Login Informatica      | 6         | 0.07%   |
| LNV                    | 5         | 0.06%   |
| Gigabyte Technology    | 5         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 139       | 1.72%   |
| Positivo Mobile                             | 128       | 1.59%   |
| Unknown                                     | 115       | 1.42%   |
| Acer Nitro AN515-44                         | 89        | 1.1%    |
| Samsung 340XAA/350XAA/550XAA                | 73        | 0.9%    |
| Dell Inspiron 5566                          | 70        | 0.87%   |
| Acer Aspire A315-53                         | 70        | 0.87%   |
| Lenovo IdeaPad S145-15API 81V7              | 69        | 0.85%   |
| Dell Inspiron 15-3567                       | 63        | 0.78%   |
| Dell Inspiron 3583                          | 61        | 0.76%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 60        | 0.74%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 58        | 0.72%   |
| Acer Aspire A515-51                         | 54        | 0.67%   |
| Acer Aspire A315-34                         | 54        | 0.67%   |
| Acer Nitro AN517-51                         | 53        | 0.66%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 52        | 0.64%   |
| Samsung 300E5M/300E5L                       | 50        | 0.62%   |
| Samsung 550XDA                              | 49        | 0.61%   |
| Acer Nitro AN515-43                         | 46        | 0.57%   |
| Positivo S14CT01                            | 45        | 0.56%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 45        | 0.56%   |
| Dell Inspiron 3442                          | 45        | 0.56%   |
| HP G42                                      | 43        | 0.53%   |
| Dell Inspiron N4050                         | 41        | 0.51%   |
| Dell Inspiron 3421                          | 40        | 0.5%    |
| Acer Nitro AN515-52                         | 39        | 0.48%   |
| HP Pavilion g4                              | 36        | 0.45%   |
| Acer Aspire E5-571                          | 36        | 0.45%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 35        | 0.43%   |
| Digibras NH4CU03                            | 35        | 0.43%   |
| Dell Inspiron 7520                          | 35        | 0.43%   |
| Acer Aspire E1-571                          | 35        | 0.43%   |
| Dell Inspiron 5458                          | 34        | 0.42%   |
| Dell Inspiron 1525                          | 33        | 0.41%   |
| Acer Aspire A515-51G                        | 33        | 0.41%   |
| Dell Inspiron 1545                          | 32        | 0.4%    |
| Dell G3 3590                                | 32        | 0.4%    |
| ASUS VivoBook_ASUSLaptop X515DA_X515DA      | 32        | 0.4%    |
| Samsung 550XBE/350XBE                       | 31        | 0.38%   |
| Itautec Infoway                             | 31        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 1180      | 14.61%  |
| Acer Aspire       | 997       | 12.35%  |
| Lenovo IdeaPad    | 579       | 7.17%   |
| Acer Nitro        | 434       | 5.38%   |
| Dell Vostro       | 254       | 3.15%   |
| Lenovo ThinkPad   | 232       | 2.87%   |
| Dell Latitude     | 219       | 2.71%   |
| HP Pavilion       | 212       | 2.63%   |
| ASUS VivoBook     | 164       | 2.03%   |
| Positivo Mobile   | 128       | 1.59%   |
| Unknown           | 115       | 1.42%   |
| Samsung 340XAA    | 73        | 0.9%    |
| Itautec Infoway   | 73        | 0.9%    |
| Dell G3           | 63        | 0.78%   |
| HP ProBook        | 52        | 0.64%   |
| Samsung 300E5M    | 50        | 0.62%   |
| Samsung 550XDA    | 49        | 0.61%   |
| Samsung RV411     | 48        | 0.59%   |
| Positivo S14CT01  | 45        | 0.56%   |
| HP G42            | 43        | 0.53%   |
| Acer Predator     | 42        | 0.52%   |
| Dell System       | 41        | 0.51%   |
| HP EliteBook      | 40        | 0.5%    |
| Dell G15          | 37        | 0.46%   |
| Semp Toshiba IS   | 36        | 0.45%   |
| Digibras NH4CU03  | 35        | 0.43%   |
| HP Compaq         | 33        | 0.41%   |
| Samsung 550XBE    | 31        | 0.38%   |
| Digibras NH4CU53  | 31        | 0.38%   |
| Dell XPS          | 30        | 0.37%   |
| Compaq Presario   | 30        | 0.37%   |
| Toshiba Satellite | 29        | 0.36%   |
| Samsung 370E4K    | 28        | 0.35%   |
| Samsung 270E5J    | 28        | 0.35%   |
| Samsung RV415     | 26        | 0.32%   |
| Apple MacBookPro8 | 26        | 0.32%   |
| Positivo H14BT58  | 25        | 0.31%   |
| Positivo CHT14B   | 25        | 0.31%   |
| Lenovo G400s      | 25        | 0.31%   |
| Samsung 550XCJ    | 24        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 1023      | 12.67%  |
| 2012    | 797       | 9.87%   |
| 2011    | 728       | 9.02%   |
| 2018    | 632       | 7.83%   |
| 2013    | 618       | 7.65%   |
| 2017    | 605       | 7.49%   |
| 2016    | 586       | 7.26%   |
| 2020    | 499       | 6.18%   |
| 2021    | 491       | 6.08%   |
| 2010    | 475       | 5.88%   |
| 2014    | 425       | 5.26%   |
| 2015    | 351       | 4.35%   |
| 2008    | 285       | 3.53%   |
| 2009    | 243       | 3.01%   |
| 2022    | 104       | 1.29%   |
| 2007    | 102       | 1.26%   |
| 2006    | 38        | 0.47%   |
| 2023    | 30        | 0.37%   |
| Unknown | 29        | 0.36%   |
| 2005    | 9         | 0.11%   |
| 2004    | 4         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 8074      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6953      | 85.25%  |
| Enabled  | 1203      | 14.75%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8049      | 99.69%  |
| Yes  | 25        | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2684      | 32.65%  |
| 3.01-4.0    | 2210      | 26.88%  |
| 16.01-24.0  | 1133      | 13.78%  |
| 8.01-16.0   | 1129      | 13.73%  |
| 1.01-2.0    | 572       | 6.96%   |
| 2.01-3.0    | 193       | 2.35%   |
| 32.01-64.0  | 186       | 2.26%   |
| 24.01-32.0  | 49        | 0.6%    |
| 0.51-1.0    | 34        | 0.41%   |
| 64.01-256.0 | 30        | 0.36%   |
| 0.01-0.5    | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3181      | 35.63%  |
| 2.01-3.0   | 2504      | 28.05%  |
| 3.01-4.0   | 1220      | 13.66%  |
| 4.01-8.0   | 1165      | 13.05%  |
| 0.51-1.0   | 567       | 6.35%   |
| 8.01-16.0  | 226       | 2.53%   |
| 0.01-0.5   | 41        | 0.46%   |
| 16.01-24.0 | 17        | 0.19%   |
| 32.01-64.0 | 3         | 0.03%   |
| 24.01-32.0 | 2         | 0.02%   |
| Unknown    | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5721      | 69.5%   |
| 2      | 2259      | 27.44%  |
| 3      | 173       | 2.1%    |
| 0      | 59        | 0.72%   |
| 4      | 19        | 0.23%   |
| 6      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5126      | 63.17%  |
| Yes       | 2989      | 36.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7066      | 87.32%  |
| No        | 1026      | 12.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7823      | 96.6%   |
| No        | 275       | 3.4%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5858      | 71.77%  |
| No        | 2304      | 28.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 8074      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 987       | 11.63%  |
| Rio de Janeiro        | 444       | 5.23%   |
| Brasília             | 278       | 3.28%   |
| Curitiba              | 250       | 2.95%   |
| Belo Horizonte        | 232       | 2.73%   |
| Fortaleza             | 196       | 2.31%   |
| Porto Alegre          | 175       | 2.06%   |
| Salvador              | 133       | 1.57%   |
| Campinas              | 127       | 1.5%    |
| Recife                | 114       | 1.34%   |
| Goiânia              | 99        | 1.17%   |
| Florianópolis        | 91        | 1.07%   |
| Santo André          | 89        | 1.05%   |
| Natal                 | 87        | 1.03%   |
| Manaus                | 74        | 0.87%   |
| Osasco                | 71        | 0.84%   |
| Sao José dos Campos  | 70        | 0.83%   |
| Campo Grande          | 70        | 0.83%   |
| Sao Luís             | 68        | 0.8%    |
| Joao Pessoa           | 62        | 0.73%   |
| Maringá              | 60        | 0.71%   |
| Niterói              | 59        | 0.7%    |
| Belém                | 57        | 0.67%   |
| Teresina              | 56        | 0.66%   |
| Aracaju               | 53        | 0.62%   |
| Uberlândia           | 52        | 0.61%   |
| Sorocaba              | 52        | 0.61%   |
| Guarulhos             | 52        | 0.61%   |
| Joinville             | 50        | 0.59%   |
| Ribeirao Preto        | 47        | 0.55%   |
| Londrina              | 47        | 0.55%   |
| Maceió               | 44        | 0.52%   |
| Cuiabá               | 40        | 0.47%   |
| Sao Bernardo do Campo | 38        | 0.45%   |
| Juiz de Fora          | 38        | 0.45%   |
| Sao Jose              | 37        | 0.44%   |
| Sao Carlos            | 37        | 0.44%   |
| Canoas                | 34        | 0.4%    |
| Vitória              | 33        | 0.39%   |
| Santos                | 31        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 2133      | 2621   | 21.07%  |
| Seagate                        | 1455      | 1744   | 14.38%  |
| Kingston                       | 978       | 1176   | 9.66%   |
| Samsung Electronics            | 723       | 939    | 7.14%   |
| Toshiba                        | 672       | 787    | 6.64%   |
| SanDisk                        | 579       | 765    | 5.72%   |
| Unknown                        | 452       | 600    | 4.47%   |
| A-DATA Technology              | 430       | 549    | 4.25%   |
| Intel                          | 284       | 353    | 2.81%   |
| ADATA Technology               | 223       | 257    | 2.2%    |
| China                          | 219       | 277    | 2.16%   |
| Hitachi                        | 209       | 252    | 2.07%   |
| Crucial                        | 189       | 257    | 1.87%   |
| SK hynix                       | 147       | 188    | 1.45%   |
| LITEON                         | 117       | 139    | 1.16%   |
| HGST                           | 111       | 132    | 1.1%    |
| Silicon Motion                 | 91        | 107    | 0.9%    |
| KingSpec                       | 73        | 82     | 0.72%   |
| SSSTC                          | 57        | 61     | 0.56%   |
| JMicron Technology             | 50        | 56     | 0.49%   |
| Fujitsu                        | 48        | 58     | 0.47%   |
| Solid State Storage            | 45        | 56     | 0.44%   |
| Apple                          | 44        | 54     | 0.43%   |
| Solid State Storage Technology | 41        | 56     | 0.41%   |
| Netac                          | 40        | 46     | 0.4%    |
| Lexar                          | 40        | 50     | 0.4%    |
| KIOXIA                         | 40        | 49     | 0.4%    |
| Micron Technology              | 38        | 39     | 0.38%   |
| Phison                         | 36        | 39     | 0.36%   |
| Realtek Semiconductor          | 29        | 37     | 0.29%   |
| Corsair                        | 29        | 29     | 0.29%   |
| Unknown                        | 29        | 33     | 0.29%   |
| Kingston Technology Company    | 25        | 27     | 0.25%   |
| XrayDisk                       | 23        | 28     | 0.23%   |
| PNY                            | 23        | 37     | 0.23%   |
| Patriot                        | 22        | 25     | 0.22%   |
| Hewlett-Packard                | 20        | 23     | 0.2%    |
| Smart                          | 18        | 20     | 0.18%   |
| XPG                            | 17        | 21     | 0.17%   |
| WALRAM                         | 17        | 19     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 493       | 4.74%   |
| Kingston SA400S37240G 240GB SSD     | 334       | 3.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 273       | 2.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 242       | 2.33%   |
| Kingston SA400S37480G 480GB SSD     | 192       | 1.85%   |
| Kingston SA400S37120G 120GB SSD     | 145       | 1.39%   |
| Toshiba MQ01ABD100 1TB              | 143       | 1.37%   |
| WDC WD10SPZX-24Z10 1TB              | 140       | 1.35%   |
| Unknown MMC Card  32GB              | 133       | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB      | 112       | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB            | 106       | 1.02%   |
| Intel NVMe SSD Drive 512GB          | 98        | 0.94%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 93        | 0.89%   |
| Toshiba MQ04ABF100 1TB              | 91        | 0.87%   |
| WDC WD10SPZX-75Z10T2 1TB            | 87        | 0.84%   |
| Samsung HM321HI 320GB               | 82        | 0.79%   |
| Seagate ST9500325AS 500GB           | 80        | 0.77%   |
| SanDisk SSD PLUS 240GB              | 74        | 0.71%   |
| SanDisk NVMe SSD Drive 512GB        | 74        | 0.71%   |
| Intel SSDPEKKW256G7 256GB           | 70        | 0.67%   |
| Kingston SV300S37A120G 120GB SSD    | 69        | 0.66%   |
| ADATA NVMe SSD Drive 256GB          | 68        | 0.65%   |
| WDC WD10JPVX-75JC3T0 1TB            | 66        | 0.63%   |
| Seagate Expansion 1TB               | 65        | 0.62%   |
| Toshiba MQ01ABF050 500GB            | 61        | 0.59%   |
| SanDisk SSD PLUS 120GB              | 61        | 0.59%   |
| A-DATA IM2P33F3A NVMe 256GB         | 59        | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB      | 58        | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 57        | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 56        | 0.54%   |
| Seagate ST500LT012-9WS142 500GB     | 56        | 0.54%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 54        | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 54        | 0.52%   |
| ADATA SM2P32A8-256GC1 256GB         | 52        | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 49        | 0.47%   |
| WDC WD10JPCX-24UE4T0 1TB            | 49        | 0.47%   |
| WDC WD10SPZX-75Z10T1 1TB            | 46        | 0.44%   |
| Toshiba MQ01ABD050 500GB            | 44        | 0.42%   |
| SanDisk SSD PLUS 480GB              | 42        | 0.4%    |
| Seagate ST1000LM014-1EJ164 1TB      | 41        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1890      | 2235   | 40.19%  |
| Seagate             | 1444      | 1729   | 30.7%   |
| Toshiba             | 633       | 739    | 13.46%  |
| Samsung Electronics | 303       | 354    | 6.44%   |
| Hitachi             | 209       | 252    | 4.44%   |
| HGST                | 111       | 132    | 2.36%   |
| Fujitsu             | 46        | 55     | 0.98%   |
| Unknown             | 26        | 32     | 0.55%   |
| Apple               | 13        | 16     | 0.28%   |
| SAGE                | 7         | 11     | 0.15%   |
| XrayDisk            | 3         | 4      | 0.06%   |
| USB3.0              | 3         | 3      | 0.06%   |
| TO Exter            | 3         | 4      | 0.06%   |
| JMicron Technology  | 3         | 3      | 0.06%   |
| External            | 2         | 2      | 0.04%   |
| WALRAM              | 1         | 1      | 0.02%   |
| Phison              | 1         | 1      | 0.02%   |
| Maxtor 6            | 1         | 1      | 0.02%   |
| Maxtor              | 1         | 1      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 2      | 0.02%   |
| CLOVER              | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 927       | 1107   | 30.1%   |
| SanDisk             | 361       | 497    | 11.72%  |
| Samsung Electronics | 246       | 341    | 7.99%   |
| WDC                 | 232       | 291    | 7.53%   |
| China               | 219       | 277    | 7.11%   |
| A-DATA Technology   | 211       | 255    | 6.85%   |
| Crucial             | 178       | 242    | 5.78%   |
| LITEON              | 108       | 130    | 3.51%   |
| KingSpec            | 69        | 78     | 2.24%   |
| Lexar               | 38        | 48     | 1.23%   |
| JMicron Technology  | 37        | 43     | 1.2%    |
| Netac               | 34        | 37     | 1.1%    |
| Apple               | 28        | 34     | 0.91%   |
| Intel               | 25        | 30     | 0.81%   |
| PNY                 | 23        | 37     | 0.75%   |
| Corsair             | 22        | 22     | 0.71%   |
| Patriot             | 21        | 24     | 0.68%   |
| Smart               | 18        | 20     | 0.58%   |
| SK hynix            | 18        | 21     | 0.58%   |
| XrayDisk            | 16        | 17     | 0.52%   |
| Hewlett-Packard     | 16        | 18     | 0.52%   |
| Gigabyte Technology | 15        | 21     | 0.49%   |
| Unknown             | 13        | 14     | 0.42%   |
| LITEONIT            | 13        | 20     | 0.42%   |
| KingDian            | 13        | 19     | 0.42%   |
| Unknown             | 13        | 14     | 0.42%   |
| Toshiba             | 10        | 14     | 0.32%   |
| Seagate             | 9         | 10     | 0.29%   |
| Micron Technology   | 9         | 10     | 0.29%   |
| Win Memory          | 8         | 9      | 0.26%   |
| WALRAM              | 8         | 8      | 0.26%   |
| BHT                 | 7         | 7      | 0.23%   |
| HUSKY               | 6         | 7      | 0.19%   |
| BIWIN               | 6         | 6      | 0.19%   |
| S3+                 | 5         | 5      | 0.16%   |
| Advantech           | 5         | 6      | 0.16%   |
| Transcend           | 4         | 4      | 0.13%   |
| Maxtor              | 4         | 4      | 0.13%   |
| Lenovo              | 4         | 5      | 0.13%   |
| Vaseky              | 3         | 4      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4612      | 5579   | 47.31%  |
| SSD     | 2864      | 3840   | 29.38%  |
| NVMe    | 1802      | 2394   | 18.49%  |
| MMC     | 374       | 519    | 3.84%   |
| Unknown | 96        | 119    | 0.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6597      | 9236   | 73.27%  |
| NVMe | 1802      | 2394   | 20.01%  |
| MMC  | 374       | 519    | 4.15%   |
| SAS  | 231       | 302    | 2.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4692      | 6237   | 64.48%  |
| 0.51-1.0   | 2437      | 3005   | 33.49%  |
| 1.01-2.0   | 138       | 166    | 1.9%    |
| 3.01-4.0   | 5         | 5      | 0.07%   |
| 4.01-10.0  | 4         | 5      | 0.05%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2527      | 29.65%  |
| 251-500        | 2154      | 25.27%  |
| 501-1000       | 1498      | 17.58%  |
| 1-20           | 631       | 7.4%    |
| 51-100         | 505       | 5.93%   |
| 1001-2000      | 495       | 5.81%   |
| 21-50          | 409       | 4.8%    |
| Unknown        | 128       | 1.5%    |
| 2001-3000      | 96        | 1.13%   |
| More than 3000 | 80        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3330      | 37.67%  |
| 21-50          | 2066      | 23.37%  |
| 51-100         | 1166      | 13.19%  |
| 101-250        | 1157      | 13.09%  |
| 251-500        | 580       | 6.56%   |
| 501-1000       | 283       | 3.2%    |
| Unknown        | 128       | 1.45%   |
| 1001-2000      | 105       | 1.19%   |
| 2001-3000      | 13        | 0.15%   |
| More than 3000 | 12        | 0.14%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 38        | 42     | 6.95%   |
| Seagate ST9500325AS 500GB           | 21        | 23     | 3.84%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 21        | 23     | 3.84%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 15     | 2.74%   |
| Toshiba MQ01ABD100 1TB              | 12        | 12     | 2.19%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 12     | 1.83%   |
| Seagate ST9320325AS 320GB           | 8         | 8      | 1.46%   |
| Samsung Electronics HM160HI 160GB   | 8         | 8      | 1.46%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 1.28%   |
| Kingston SV300S37A120G 120GB SSD    | 7         | 8      | 1.28%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 7      | 1.1%    |
| WDC WD3200BPVT-22JJ5T0 320GB        | 6         | 6      | 1.1%    |
| Toshiba MQ02ABD100H 1TB             | 6         | 9      | 1.1%    |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 1.1%    |
| Seagate ST1000LM048-2E7172 1TB      | 6         | 7      | 1.1%    |
| SanDisk SSD PLUS 480GB              | 6         | 6      | 1.1%    |
| Kingston SA400S37240G 240GB SSD     | 6         | 6      | 1.1%    |
| WDC WD5000LPCX-24C6HT0 500GB        | 5         | 6      | 0.91%   |
| WDC WD10JPCX-24UE4T0 1TB            | 5         | 5      | 0.91%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 0.91%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 0.91%   |
| Seagate ST1000LM014-1EJ164 1TB      | 5         | 5      | 0.91%   |
| Samsung Electronics HM321HI 320GB   | 5         | 5      | 0.91%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 0.91%   |
| HGST HTS545050A7E680 500GB          | 5         | 5      | 0.91%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 4         | 4      | 0.73%   |
| WDC WD10SPZX-24Z10T0 1TB            | 4         | 5      | 0.73%   |
| Toshiba MK5065GSXF 500GB            | 4         | 5      | 0.73%   |
| Toshiba MK3259GSXP 320GB            | 4         | 4      | 0.73%   |
| Seagate ST9500423AS 500GB           | 4         | 4      | 0.73%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 4      | 0.73%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 4      | 0.73%   |
| Samsung Electronics HM500JI 500GB   | 4         | 4      | 0.73%   |
| Kingston SUV400S37240G 240GB SSD    | 4         | 5      | 0.73%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 4      | 0.73%   |
| HGST HCC545050A7E380 500GB          | 4         | 5      | 0.73%   |
| China SSD 120GB                     | 4         | 4      | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3         | 3      | 0.55%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 3         | 3      | 0.55%   |
| WDC WD3200BPVT-00JJ5T0 320GB        | 3         | 5      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 182       | 201    | 33.52%  |
| WDC                   | 102       | 112    | 18.78%  |
| Toshiba               | 76        | 85     | 14%     |
| Samsung Electronics   | 32        | 43     | 5.89%   |
| Hitachi               | 32        | 35     | 5.89%   |
| Kingston              | 25        | 29     | 4.6%    |
| SanDisk               | 16        | 16     | 2.95%   |
| China                 | 14        | 16     | 2.58%   |
| HGST                  | 12        | 13     | 2.21%   |
| A-DATA Technology     | 10        | 12     | 1.84%   |
| LITEON                | 4         | 5      | 0.74%   |
| Intel                 | 4         | 4      | 0.74%   |
| Fujitsu               | 4         | 5      | 0.74%   |
| PNY                   | 3         | 5      | 0.55%   |
| KingSpec              | 3         | 3      | 0.55%   |
| Crucial               | 3         | 3      | 0.55%   |
| WALRAM                | 2         | 2      | 0.37%   |
| Netac                 | 2         | 2      | 0.37%   |
| Micron Technology     | 2         | 2      | 0.37%   |
| Apple                 | 2         | 2      | 0.37%   |
| XrayDisk              | 1         | 1      | 0.18%   |
| XPG                   | 1         | 1      | 0.18%   |
| SSSTC                 | 1         | 1      | 0.18%   |
| SK hynix              | 1         | 1      | 0.18%   |
| Silicon Motion        | 1         | 1      | 0.18%   |
| ShiJi                 | 1         | 4      | 0.18%   |
| SAGE                  | 1         | 1      | 0.18%   |
| Realtek Semiconductor | 1         | 1      | 0.18%   |
| OCZ                   | 1         | 1      | 0.18%   |
| LITEONIT              | 1         | 2      | 0.18%   |
| Kross Elegance        | 1         | 1      | 0.18%   |
| JMicron Technology    | 1         | 1      | 0.18%   |
| ADATA Technology      | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 182       | 201    | 42.62%  |
| WDC                 | 92        | 102    | 21.55%  |
| Toshiba             | 75        | 84     | 17.56%  |
| Hitachi             | 32        | 35     | 7.49%   |
| Samsung Electronics | 28        | 39     | 6.56%   |
| HGST                | 12        | 13     | 2.81%   |
| Fujitsu             | 4         | 5      | 0.94%   |
| SAGE                | 1         | 1      | 0.23%   |
| Apple               | 1         | 1      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 426       | 481    | 78.6%   |
| SSD  | 100       | 110    | 18.45%  |
| NVMe | 16        | 21     | 2.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 14.29%  |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 7.14%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 7.14%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 7.14%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 7.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 7.14%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 7.14%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 7.14%   |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 7.14%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 7.14%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 42.86%  |
| WDC                 | 2         | 2      | 14.29%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Seagate             | 2         | 2      | 14.29%  |
| Maxtor              | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5813      | 8820   | 68.49%  |
| Works    | 2127      | 3004   | 25.06%  |
| Malfunc  | 532       | 612    | 6.27%   |
| Failed   | 14        | 14     | 0.16%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6636      | 71.97%  |
| AMD                              | 764       | 8.29%   |
| ADATA Technology                 | 454       | 4.92%   |
| SanDisk                          | 262       | 2.84%   |
| Samsung Electronics              | 201       | 2.18%   |
| Solid State Storage Technology   | 150       | 1.63%   |
| SK hynix                         | 124       | 1.34%   |
| Silicon Motion                   | 100       | 1.08%   |
| Silicon Integrated Systems [SiS] | 100       | 1.08%   |
| Kingston Technology Company      | 78        | 0.85%   |
| Phison Electronics               | 52        | 0.56%   |
| Realtek Semiconductor            | 41        | 0.44%   |
| Nvidia                           | 39        | 0.42%   |
| KIOXIA                           | 37        | 0.4%    |
| Toshiba America Info Systems     | 29        | 0.31%   |
| Micron Technology                | 29        | 0.31%   |
| VIA Technologies                 | 25        | 0.27%   |
| Micron/Crucial Technology        | 25        | 0.27%   |
| MAXIO Technology (Hangzhou)      | 21        | 0.23%   |
| Lite-On Technology               | 19        | 0.21%   |
| Union Memory (Shenzhen)          | 7         | 0.08%   |
| Netac Technology                 | 6         | 0.07%   |
| Marvell Technology Group         | 6         | 0.07%   |
| Shenzhen Longsys Electronics     | 4         | 0.04%   |
| Apple                            | 4         | 0.04%   |
| O2 Micro                         | 2         | 0.02%   |
| TenaFe                           | 1         | 0.01%   |
| Seagate Technology               | 1         | 0.01%   |
| Lenovo                           | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |
| Beijing Starblaze Technology     | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1096      | 10.82%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 870       | 8.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 677       | 6.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 566       | 5.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 515       | 5.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 419       | 4.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 339       | 3.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 325       | 3.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 261       | 2.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 217       | 2.14%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 207       | 2.04%   |
| Intel Tiger Lake-LP SATA Controller                                              | 201       | 1.98%   |
| Intel Volume Management Device NVMe RAID Controller                              | 171       | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 165       | 1.63%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                              | 163       | 1.61%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                       | 161       | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 155       | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 150       | 1.48%   |
| Intel Comet Lake SATA AHCI Controller                                            | 149       | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 144       | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 139       | 1.37%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 136       | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 133       | 1.31%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 122       | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 100       | 0.99%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 98        | 0.97%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 95        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 87        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 85        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 84        | 0.83%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 82        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 74        | 0.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 70        | 0.69%   |
| ADATA SM2P32A8 NVMe SSD (DRAM-less)                                              | 66        | 0.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 65        | 0.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 64        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 64        | 0.63%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 61        | 0.6%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 61        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 53        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 6505      | 66.81%  |
| NVMe | 1807      | 18.56%  |
| RAID | 819       | 8.41%   |
| IDE  | 605       | 6.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 7216      | 89.37%  |
| AMD    | 856       | 10.6%   |
| ARM    | 2         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 281       | 3.48%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 169       | 2.09%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 161       | 1.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 151       | 1.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 143       | 1.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 139       | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 137       | 1.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 137       | 1.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 127       | 1.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 118       | 1.46%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 116       | 1.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 116       | 1.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 112       | 1.39%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 101       | 1.25%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 100       | 1.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 99        | 1.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 99        | 1.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 97        | 1.2%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 96        | 1.19%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 95        | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 90        | 1.11%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 89        | 1.1%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 88        | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 85        | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 84        | 1.04%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 84        | 1.04%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 81        | 1%      |
| Intel Core i3-4005U CPU @ 1.70GHz             | 75        | 0.93%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 73        | 0.9%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 71        | 0.88%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 71        | 0.88%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 70        | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 69        | 0.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 69        | 0.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 69        | 0.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 65        | 0.8%    |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 63        | 0.78%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 60        | 0.74%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 60        | 0.74%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 59        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2320      | 28.72%  |
| Intel Core i7                  | 1592      | 19.71%  |
| Intel Core i3                  | 1224      | 15.15%  |
| Intel Celeron                  | 613       | 7.59%   |
| Other                          | 433       | 5.36%   |
| Intel Core 2 Duo               | 297       | 3.68%   |
| Intel Atom                     | 284       | 3.52%   |
| AMD Ryzen 5                    | 237       | 2.93%   |
| AMD Ryzen 7                    | 204       | 2.53%   |
| Intel Pentium                  | 153       | 1.89%   |
| Intel Pentium Dual-Core        | 148       | 1.83%   |
| Intel Pentium Dual             | 77        | 0.95%   |
| AMD E                          | 55        | 0.68%   |
| AMD C-60                       | 41        | 0.51%   |
| AMD E1                         | 35        | 0.43%   |
| AMD A4                         | 32        | 0.4%    |
| AMD A6                         | 28        | 0.35%   |
| Intel Genuine                  | 27        | 0.33%   |
| AMD A10                        | 24        | 0.3%    |
| Intel Core 2                   | 23        | 0.28%   |
| AMD C-70                       | 23        | 0.28%   |
| Intel Celeron Dual-Core        | 18        | 0.22%   |
| AMD C-50                       | 18        | 0.22%   |
| AMD Ryzen 3                    | 15        | 0.19%   |
| AMD A12                        | 15        | 0.19%   |
| AMD Ryzen 9                    | 12        | 0.15%   |
| AMD Mobile Sempron             | 12        | 0.15%   |
| Intel Celeron M                | 11        | 0.14%   |
| AMD Athlon II                  | 10        | 0.12%   |
| AMD Turion 64 Mobile           | 7         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 6         | 0.07%   |
| AMD Turion 64 X2 Mobile        | 6         | 0.07%   |
| AMD Turion II                  | 5         | 0.06%   |
| AMD Ryzen 7 PRO                | 5         | 0.06%   |
| AMD Phenom II                  | 5         | 0.06%   |
| AMD Athlon 64 X2               | 5         | 0.06%   |
| Intel Pentium M                | 4         | 0.05%   |
| Intel Pentium Gold             | 4         | 0.05%   |
| AMD Turion Neo X2              | 4         | 0.05%   |
| AMD A8                         | 4         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4988      | 61.76%  |
| 4       | 2326      | 28.8%   |
| 6       | 337       | 4.17%   |
| 8       | 199       | 2.46%   |
| 1       | 160       | 1.98%   |
| 14      | 28        | 0.35%   |
| 12      | 19        | 0.24%   |
| 10      | 12        | 0.15%   |
| Unknown | 3         | 0.04%   |
| 5       | 2         | 0.02%   |
| 3       | 2         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 8074      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6130      | 75.84%  |
| 1       | 1949      | 24.11%  |
| Unknown | 3         | 0.04%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7758      | 95.62%  |
| Unknown        | 295       | 3.64%   |
| 32-bit         | 45        | 0.55%   |
| 64-bit         | 15        | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2084      | 24.79%  |
| 0x206a7    | 623       | 7.41%   |
| 0x306a9    | 616       | 7.33%   |
| 0x806e9    | 409       | 4.86%   |
| 0x40651    | 359       | 4.27%   |
| 0x806ec    | 328       | 3.9%    |
| 0x20655    | 311       | 3.7%    |
| 0x906ea    | 300       | 3.57%   |
| 0x306d4    | 290       | 3.45%   |
| 0x406e3    | 278       | 3.31%   |
| 0x1067a    | 272       | 3.24%   |
| 0x806ea    | 257       | 3.06%   |
| 0x806c1    | 211       | 2.51%   |
| 0x406c4    | 167       | 1.99%   |
| 0x6fd      | 155       | 1.84%   |
| 0x08108109 | 103       | 1.23%   |
| 0x05000119 | 93        | 1.11%   |
| 0x08600103 | 89        | 1.06%   |
| 0x30678    | 87        | 1.03%   |
| 0x906e9    | 85        | 1.01%   |
| 0x706e5    | 82        | 0.98%   |
| 0x08108102 | 69        | 0.82%   |
| 0x706a1    | 65        | 0.77%   |
| 0x406c3    | 61        | 0.73%   |
| 0x306c3    | 60        | 0.71%   |
| 0x906ed    | 58        | 0.69%   |
| 0x706a8    | 57        | 0.68%   |
| 0xa0652    | 55        | 0.65%   |
| 0x20652    | 52        | 0.62%   |
| 0x806eb    | 50        | 0.59%   |
| 0x106ca    | 48        | 0.57%   |
| 0x08608103 | 37        | 0.44%   |
| 0x10676    | 36        | 0.43%   |
| 0x30661    | 34        | 0.4%    |
| 0x03000027 | 30        | 0.36%   |
| 0x506c9    | 29        | 0.34%   |
| 0x05000029 | 28        | 0.33%   |
| 0x10661    | 27        | 0.32%   |
| 0x0a50000c | 27        | 0.32%   |
| 0x506e3    | 24        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1933      | 23.92%  |
| IvyBridge        | 787       | 9.74%   |
| SandyBridge      | 774       | 9.58%   |
| Haswell          | 521       | 6.45%   |
| Westmere         | 449       | 5.56%   |
| Silvermont       | 398       | 4.93%   |
| Skylake          | 386       | 4.78%   |
| Penryn           | 377       | 4.67%   |
| Broadwell        | 352       | 4.36%   |
| TigerLake        | 313       | 3.87%   |
| Core             | 250       | 3.09%   |
| Zen+             | 218       | 2.7%    |
| Bobcat           | 160       | 1.98%   |
| Goldmont plus    | 152       | 1.88%   |
| Unknown          | 149       | 1.84%   |
| Icelake          | 147       | 1.82%   |
| Bonnell          | 107       | 1.32%   |
| CometLake        | 106       | 1.31%   |
| Zen 2            | 103       | 1.27%   |
| Excavator        | 47        | 0.58%   |
| Alderlake Hybrid | 47        | 0.58%   |
| K8 Hammer        | 45        | 0.56%   |
| Zen 3            | 38        | 0.47%   |
| Goldmont         | 37        | 0.46%   |
| K10 Llano        | 35        | 0.43%   |
| Zen              | 32        | 0.4%    |
| K10              | 29        | 0.36%   |
| P6               | 24        | 0.3%    |
| Jaguar           | 22        | 0.27%   |
| Nehalem          | 13        | 0.16%   |
| K8 & K10 hybrid  | 11        | 0.14%   |
| Piledriver       | 10        | 0.12%   |
| Puma             | 4         | 0.05%   |
| Steamroller      | 2         | 0.02%   |
| NetBurst         | 1         | 0.01%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6925      | 66.18%  |
| Nvidia                           | 2116      | 20.22%  |
| AMD                              | 1298      | 12.4%   |
| Silicon Integrated Systems [SiS] | 100       | 0.96%   |
| VIA Technologies                 | 25        | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 777       | 7.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 760       | 7.08%   |
| Intel HD Graphics 620                                                                    | 555       | 5.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 440       | 4.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 420       | 3.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 417       | 3.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 398       | 3.71%   |
| Intel HD Graphics 5500                                                                   | 329       | 3.07%   |
| Intel UHD Graphics 620                                                                   | 326       | 3.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 314       | 2.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 291       | 2.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 286       | 2.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 277       | 2.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 261       | 2.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 217       | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 188       | 1.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 160       | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 152       | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 149       | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 149       | 1.39%   |
| Intel HD Graphics 630                                                                    | 116       | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 112       | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 108       | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 106       | 0.99%   |
| Nvidia GM108M [GeForce MX110]                                                            | 101       | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 100       | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 98        | 0.91%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 97        | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 96        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 92        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 85        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 76        | 0.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 75        | 0.7%    |
| AMD Lucienne                                                                             | 73        | 0.68%   |
| Nvidia GP108M [GeForce MX250]                                                            | 59        | 0.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 55        | 0.51%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 52        | 0.48%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 52        | 0.48%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 50        | 0.47%   |
| Nvidia GP108M [GeForce MX230]                                                            | 48        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 4700      | 58.1%   |
| Intel + Nvidia | 1796      | 22.2%   |
| 1 x AMD        | 624       | 7.71%   |
| Intel + AMD    | 420       | 5.19%   |
| AMD + Nvidia   | 172       | 2.13%   |
| 1 x Nvidia     | 147       | 1.82%   |
| 1 x SiS        | 100       | 1.24%   |
| 2 x AMD        | 81        | 1%      |
| 1 x VIA        | 25        | 0.31%   |
| 2 x Intel      | 21        | 0.26%   |
| Other          | 4         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6610      | 81.03%  |
| Proprietary | 1315      | 16.12%  |
| Unknown     | 232       | 2.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5836      | 70.79%  |
| 1.01-2.0   | 1112      | 13.49%  |
| 0.01-0.5   | 583       | 7.07%   |
| 3.01-4.0   | 409       | 4.96%   |
| 0.51-1.0   | 198       | 2.4%    |
| 5.01-6.0   | 72        | 0.87%   |
| 2.01-3.0   | 17        | 0.21%   |
| 7.01-8.0   | 15        | 0.18%   |
| 8.01-16.0  | 2         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 1752      | 18.93%  |
| AU Optronics            | 1699      | 18.36%  |
| Chimei Innolux          | 1367      | 14.77%  |
| LG Display              | 1233      | 13.32%  |
| Samsung Electronics     | 937       | 10.12%  |
| Goldstar                | 504       | 5.45%   |
| Dell                    | 190       | 2.05%   |
| AOC                     | 187       | 2.02%   |
| Chi Mei Optoelectronics | 168       | 1.82%   |
| InfoVision              | 135       | 1.46%   |
| PANDA                   | 132       | 1.43%   |
| Apple                   | 108       | 1.17%   |
| Philips                 | 102       | 1.1%    |
| Lenovo                  | 70        | 0.76%   |
| Acer                    | 60        | 0.65%   |
| CPT                     | 50        | 0.54%   |
| HannStar                | 48        | 0.52%   |
| LG Philips              | 44        | 0.48%   |
| Sony                    | 40        | 0.43%   |
| SLD                     | 35        | 0.38%   |
| Hewlett-Packard         | 35        | 0.38%   |
| InnoLux Display         | 30        | 0.32%   |
| Sharp                   | 26        | 0.28%   |
| MTD                     | 20        | 0.22%   |
| Panasonic               | 15        | 0.16%   |
| KDC                     | 14        | 0.15%   |
| ASUSTek Computer        | 14        | 0.15%   |
| Valve                   | 13        | 0.14%   |
| GDH                     | 12        | 0.13%   |
| BenQ                    | 12        | 0.13%   |
| STA                     | 11        | 0.12%   |
| Toshiba                 | 10        | 0.11%   |
| Unknown (XXX)           | 9         | 0.1%    |
| Unknown                 | 9         | 0.1%    |
| SKY                     | 9         | 0.1%    |
| NCS                     | 9         | 0.1%    |
| VIE                     | 7         | 0.08%   |
| RTK                     | 7         | 0.08%   |
| ITE                     | 7         | 0.08%   |
| MStar                   | 6         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 129       | 1.39%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 127       | 1.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 126       | 1.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 126       | 1.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 115       | 1.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 110       | 1.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 107       | 1.15%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 106       | 1.14%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 103       | 1.11%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 86        | 0.92%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 82        | 0.88%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 80        | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 80        | 0.86%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 79        | 0.85%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 76        | 0.82%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 68        | 0.73%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 66        | 0.71%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 62        | 0.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 60        | 0.64%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 59        | 0.63%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 59        | 0.63%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 58        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 58        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 57        | 0.61%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 57        | 0.61%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 56        | 0.6%    |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 51        | 0.55%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 51        | 0.55%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 49        | 0.53%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 48        | 0.52%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.5%    |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 46        | 0.49%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 45        | 0.48%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 44        | 0.47%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 44        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 43        | 0.46%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 43        | 0.46%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch         | 42        | 0.45%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 41        | 0.44%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 40        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4745      | 53.79%  |
| 1920x1080 (FHD)    | 2627      | 29.78%  |
| 1280x800 (WXGA)    | 335       | 3.8%    |
| 2560x1080          | 194       | 2.2%    |
| 1600x900 (HD+)     | 185       | 2.1%    |
| 3840x2160 (4K)     | 136       | 1.54%   |
| 1440x900 (WXGA+)   | 112       | 1.27%   |
| 1360x768           | 80        | 0.91%   |
| 2560x1440 (QHD)    | 75        | 0.85%   |
| 1920x1200 (WUXGA)  | 57        | 0.65%   |
| 1024x600           | 42        | 0.48%   |
| 1680x1050 (WSXGA+) | 36        | 0.41%   |
| 1280x1024 (SXGA)   | 31        | 0.35%   |
| 2560x1600          | 23        | 0.26%   |
| 1024x768 (XGA)     | 23        | 0.26%   |
| 1920x540           | 21        | 0.24%   |
| 800x1280           | 13        | 0.15%   |
| 2880x1800          | 11        | 0.12%   |
| 1280x720 (HD)      | 11        | 0.12%   |
| 2288x1287          | 9         | 0.1%    |
| Unknown            | 8         | 0.09%   |
| 3840x2400          | 7         | 0.08%   |
| 1280x960           | 5         | 0.06%   |
| 3440x1440          | 4         | 0.05%   |
| 3200x1800 (QHD+)   | 4         | 0.05%   |
| 3840x1080          | 3         | 0.03%   |
| 2160x1440          | 3         | 0.03%   |
| 1024x576           | 2         | 0.02%   |
| 4240x1080          | 1         | 0.01%   |
| 3926x1080          | 1         | 0.01%   |
| 3840x1600          | 1         | 0.01%   |
| 3600x1080          | 1         | 0.01%   |
| 3456x2160          | 1         | 0.01%   |
| 3286x1080          | 1         | 0.01%   |
| 3200x2000          | 1         | 0.01%   |
| 3072x1920          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3982      | 43.1%   |
| 14      | 1699      | 18.39%  |
| 13      | 1460      | 15.8%   |
| 21      | 279       | 3.02%   |
| 23      | 237       | 2.56%   |
| 17      | 210       | 2.27%   |
| 18      | 182       | 1.97%   |
| 34      | 175       | 1.89%   |
| 24      | 142       | 1.54%   |
| 11      | 127       | 1.37%   |
| 27      | 119       | 1.29%   |
| 12      | 64        | 0.69%   |
| 19      | 60        | 0.65%   |
| 31      | 59        | 0.64%   |
| 20      | 56        | 0.61%   |
| Unknown | 53        | 0.57%   |
| 10      | 47        | 0.51%   |
| 40      | 31        | 0.34%   |
| 28      | 31        | 0.34%   |
| 54      | 27        | 0.29%   |
| 16      | 27        | 0.29%   |
| 72      | 24        | 0.26%   |
| 32      | 24        | 0.26%   |
| 84      | 20        | 0.22%   |
| 52      | 20        | 0.22%   |
| 22      | 19        | 0.21%   |
| 7       | 13        | 0.14%   |
| 46      | 9         | 0.1%    |
| 37      | 9         | 0.1%    |
| 26      | 8         | 0.09%   |
| 58      | 4         | 0.04%   |
| 65      | 3         | 0.03%   |
| 48      | 3         | 0.03%   |
| 86      | 2         | 0.02%   |
| 55      | 2         | 0.02%   |
| 47      | 2         | 0.02%   |
| 25      | 2         | 0.02%   |
| 142     | 1         | 0.01%   |
| 60      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 6787      | 74%     |
| 401-500        | 586       | 6.39%   |
| 501-600        | 483       | 5.27%   |
| 201-300        | 462       | 5.04%   |
| 351-400        | 322       | 3.51%   |
| 701-800        | 200       | 2.18%   |
| 601-700        | 102       | 1.11%   |
| 1001-1500      | 75        | 0.82%   |
| Unknown        | 53        | 0.58%   |
| 1501-2000      | 44        | 0.48%   |
| 801-900        | 41        | 0.45%   |
| 1-100          | 13        | 0.14%   |
| 901-1000       | 3         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 7159      | 88.52%  |
| 16/10   | 594       | 7.35%   |
| 21/9    | 200       | 2.47%   |
| 4/3     | 42        | 0.52%   |
| 5/4     | 35        | 0.43%   |
| Unknown | 24        | 0.3%    |
| 3/2     | 14        | 0.17%   |
| 0.67    | 13        | 0.16%   |
| 32/9    | 3         | 0.04%   |
| 0.56    | 2         | 0.02%   |
| 1.00    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3964      | 42.95%  |
| 81-90          | 2986      | 32.35%  |
| 201-250        | 593       | 6.42%   |
| 351-500        | 265       | 2.87%   |
| 151-200        | 194       | 2.1%    |
| 141-150        | 190       | 2.06%   |
| 71-80          | 169       | 1.83%   |
| 121-130        | 151       | 1.64%   |
| 51-60          | 127       | 1.38%   |
| 301-350        | 123       | 1.33%   |
| More than 1000 | 107       | 1.16%   |
| 501-1000       | 58        | 0.63%   |
| Unknown        | 53        | 0.57%   |
| 61-70          | 49        | 0.53%   |
| 251-300        | 48        | 0.52%   |
| 41-50          | 47        | 0.51%   |
| 131-140        | 37        | 0.4%    |
| 91-100         | 37        | 0.4%    |
| 111-120        | 19        | 0.21%   |
| 1-40           | 13        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 4912      | 54.45%  |
| 121-160       | 2330      | 25.83%  |
| 51-100        | 1392      | 15.43%  |
| 161-240       | 168       | 1.86%   |
| 1-50          | 138       | 1.53%   |
| Unknown       | 53        | 0.59%   |
| More than 240 | 28        | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6470      | 78.07%  |
| 2     | 1520      | 18.34%  |
| 0     | 221       | 2.67%   |
| 3     | 74        | 0.89%   |
| 4     | 2         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5866      | 41.7%   |
| Qualcomm Atheros                  | 3410      | 24.24%  |
| Intel                             | 2650      | 18.84%  |
| Broadcom                          | 771       | 5.48%   |
| JMicron Technology                | 212       | 1.51%   |
| Marvell Technology Group          | 197       | 1.4%    |
| Broadcom Limited                  | 161       | 1.14%   |
| Ralink                            | 148       | 1.05%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.71%   |
| Ralink Technology                 | 88        | 0.63%   |
| TP-Link                           | 69        | 0.49%   |
| Samsung Electronics               | 59        | 0.42%   |
| MediaTek                          | 42        | 0.3%    |
| ASIX Electronics                  | 42        | 0.3%    |
| Motorola PCS                      | 34        | 0.24%   |
| Xiaomi                            | 26        | 0.18%   |
| Nvidia                            | 26        | 0.18%   |
| VIA Technologies                  | 25        | 0.18%   |
| Qualcomm Atheros Communications   | 24        | 0.17%   |
| D-Link                            | 17        | 0.12%   |
| ICS Advent                        | 12        | 0.09%   |
| D-Link System                     | 11        | 0.08%   |
| DisplayLink                       | 9         | 0.06%   |
| Dell                              | 6         | 0.04%   |
| LG Electronics                    | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| Microsoft                         | 4         | 0.03%   |
| Huawei Technologies               | 4         | 0.03%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Qualcomm                          | 3         | 0.02%   |
| Edimax Technology                 | 3         | 0.02%   |
| AMD                               | 3         | 0.02%   |
| OPPO Electronics                  | 2         | 0.01%   |
| NetGear                           | 2         | 0.01%   |
| Micro Star International          | 2         | 0.01%   |
| ASUSTek Computer                  | 2         | 0.01%   |
| Arduino SA                        | 2         | 0.01%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| Spreadtrum Communications         | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3381      | 21.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1554      | 10.07%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 915       | 5.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 827       | 5.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 613       | 3.97%   |
| Intel Wi-Fi 6 AX200                                               | 334       | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 325       | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 318       | 2.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 316       | 2.05%   |
| Intel Wi-Fi 6 AX201                                               | 291       | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 232       | 1.5%    |
| Intel Wireless 7265                                               | 187       | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 180       | 1.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 156       | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 143       | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 141       | 0.91%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 140       | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 108       | 0.7%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 107       | 0.69%   |
| Intel Wireless 7260                                               | 106       | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 105       | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 101       | 0.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 98        | 0.64%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 97        | 0.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 95        | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 89        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 86        | 0.56%   |
| Intel Wireless 3165                                               | 86        | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 84        | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 81        | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 80        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 80        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 74        | 0.48%   |
| Intel Centrino Advanced-N 6235                                    | 74        | 0.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 73        | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 69        | 0.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 69        | 0.45%   |
| Intel Wireless 3160                                               | 68        | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 66        | 0.43%   |
| Intel Wireless 8265 / 8275                                        | 65        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3209      | 39.58%  |
| Intel                                 | 2588      | 31.92%  |
| Realtek Semiconductor                 | 1251      | 15.43%  |
| Broadcom                              | 554       | 6.83%   |
| Ralink                                | 148       | 1.83%   |
| Broadcom Limited                      | 101       | 1.25%   |
| Ralink Technology                     | 88        | 1.09%   |
| TP-Link                               | 53        | 0.65%   |
| MediaTek                              | 38        | 0.47%   |
| Qualcomm Atheros Communications       | 24        | 0.3%    |
| D-Link                                | 17        | 0.21%   |
| D-Link System                         | 11        | 0.14%   |
| Dell                                  | 5         | 0.06%   |
| Microsoft                             | 4         | 0.05%   |
| Edimax Technology                     | 3         | 0.04%   |
| NetGear                               | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| Sierra Wireless                       | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Linksys                               | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Ericsson Business Mobile Networks     | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 915       | 11.23%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 827       | 10.15%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 613       | 7.52%   |
| Intel Wi-Fi 6 AX200                                                     | 334       | 4.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 325       | 3.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 318       | 3.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 316       | 3.88%   |
| Intel Wi-Fi 6 AX201                                                     | 291       | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 232       | 2.85%   |
| Intel Wireless 7265                                                     | 187       | 2.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 180       | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 143       | 1.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 141       | 1.73%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 107       | 1.31%   |
| Intel Wireless 7260                                                     | 106       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 105       | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 101       | 1.24%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 95        | 1.17%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 89        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 1.06%   |
| Intel Wireless 3165                                                     | 86        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 81        | 0.99%   |
| Intel Centrino Advanced-N 6235                                          | 74        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 73        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 69        | 0.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 69        | 0.85%   |
| Intel Wireless 3160                                                     | 68        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 66        | 0.81%   |
| Intel Wireless 8265 / 8275                                              | 65        | 0.8%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 64        | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 64        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 63        | 0.77%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 62        | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 57        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 56        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                         | 54        | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 54        | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 53        | 0.65%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 53        | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 51        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 5227      | 72.82%  |
| Qualcomm Atheros                 | 442       | 6.16%   |
| Intel                            | 383       | 5.34%   |
| Broadcom                         | 303       | 4.22%   |
| JMicron Technology               | 212       | 2.95%   |
| Marvell Technology Group         | 197       | 2.74%   |
| Silicon Integrated Systems [SiS] | 100       | 1.39%   |
| Broadcom Limited                 | 67        | 0.93%   |
| ASIX Electronics                 | 42        | 0.59%   |
| Samsung Electronics              | 39        | 0.54%   |
| Xiaomi                           | 26        | 0.36%   |
| Motorola PCS                     | 26        | 0.36%   |
| VIA Technologies                 | 25        | 0.35%   |
| Nvidia                           | 25        | 0.35%   |
| TP-Link                          | 16        | 0.22%   |
| ICS Advent                       | 12        | 0.17%   |
| DisplayLink                      | 9         | 0.13%   |
| Lenovo                           | 5         | 0.07%   |
| Attansic Technology              | 4         | 0.06%   |
| Qualcomm                         | 3         | 0.04%   |
| MediaTek                         | 3         | 0.04%   |
| LG Electronics                   | 3         | 0.04%   |
| OPPO Electronics                 | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |
| Spreadtrum Communications        | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.01%   |
| Huawei Technologies              | 1         | 0.01%   |
| Apple                            | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3381      | 46.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1554      | 21.51%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 156       | 2.16%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 140       | 1.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 108       | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 98        | 1.36%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 97        | 1.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 84        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 80        | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 80        | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 74        | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 60        | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 60        | 0.83%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 56        | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                              | 46        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 46        | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 42        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 42        | 0.58%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 40        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 39        | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                                          | 37        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 36        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 31        | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 31        | 0.43%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 30        | 0.42%   |
| Motorola PCS moto g62 5G                                                       | 26        | 0.36%   |
| Intel Ethernet Connection I219-LM                                              | 26        | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 25        | 0.35%   |
| Intel 82577LM Gigabit Network Connection                                       | 25        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 24        | 0.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 24        | 0.33%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 24        | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 22        | 0.3%    |
| Intel Ethernet Connection I218-LM                                              | 22        | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 21        | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 20        | 0.28%   |
| Intel Ethernet Connection (13) I219-LM                                         | 20        | 0.28%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 19        | 0.26%   |
| Intel Ethernet Connection I217-LM                                              | 19        | 0.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 17        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7819      | 52.36%  |
| Ethernet | 7056      | 47.25%  |
| Modem    | 46        | 0.31%   |
| Unknown  | 12        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6734      | 79.42%  |
| Ethernet | 1743      | 20.56%  |
| Modem    | 1         | 0.01%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6632      | 81.91%  |
| 1     | 1178      | 14.55%  |
| 0     | 275       | 3.4%    |
| 3     | 12        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6077      | 73.13%  |
| Yes  | 2233      | 26.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2216      | 37.6%   |
| Qualcomm Atheros Communications | 1644      | 27.89%  |
| Lite-On Technology              | 711       | 12.06%  |
| Realtek Semiconductor           | 228       | 3.87%   |
| Broadcom                        | 216       | 3.66%   |
| IMC Networks                    | 165       | 2.8%    |
| Foxconn / Hon Hai               | 135       | 2.29%   |
| Cambridge Silicon Radio         | 107       | 1.82%   |
| Apple                           | 106       | 1.8%    |
| Dell                            | 87        | 1.48%   |
| Hewlett-Packard                 | 64        | 1.09%   |
| Ralink                          | 57        | 0.97%   |
| Smart Modular Technologies      | 45        | 0.76%   |
| Qcom                            | 28        | 0.48%   |
| Ralink Technology               | 18        | 0.31%   |
| Foxconn International           | 15        | 0.25%   |
| Alps Electric                   | 15        | 0.25%   |
| Askey Computer                  | 10        | 0.17%   |
| Toshiba                         | 6         | 0.1%    |
| Opticis                         | 5         | 0.08%   |
| ASUSTek Computer                | 5         | 0.08%   |
| Micro Star International        | 4         | 0.07%   |
| Syntek                          | 2         | 0.03%   |
| USI                             | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| MediaTek                        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 960       | 16.29%  |
| Intel Bluetooth wireless interface                                                  | 698       | 11.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 617       | 10.47%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 393       | 6.67%   |
| Intel AX200 Bluetooth                                                               | 330       | 5.6%    |
| Intel AX201 Bluetooth                                                               | 290       | 4.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 258       | 4.38%   |
| Realtek Bluetooth Radio                                                             | 162       | 2.75%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 147       | 2.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 135       | 2.29%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 129       | 2.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 107       | 1.82%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 104       | 1.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 100       | 1.7%    |
| Lite-On Bluetooth Device                                                            | 94        | 1.59%   |
| IMC Networks Bluetooth Radio                                                        | 94        | 1.59%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 69        | 1.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 63        | 1.07%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 62        | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 61        | 1.03%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 61        | 1.03%   |
| Ralink RT3290 Bluetooth                                                             | 57        | 0.97%   |
| Apple Bluetooth Host Controller                                                     | 55        | 0.93%   |
| Smart Modular Bluetooth Device                                                      | 45        | 0.76%   |
| Dell Wireless 365 Bluetooth                                                         | 37        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 34        | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 34        | 0.58%   |
| IMC Networks Bluetooth Device                                                       | 31        | 0.53%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 30        | 0.51%   |
| Apple Bluetooth USB Host Controller                                                 | 30        | 0.51%   |
| Lite-On Wireless_Device                                                             | 25        | 0.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 25        | 0.42%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 25        | 0.42%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 23        | 0.39%   |
| Intel Bluetooth Device                                                              | 23        | 0.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 23        | 0.39%   |
| Dell DW375 Bluetooth Module                                                         | 20        | 0.34%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 19        | 0.32%   |
| Realtek RTL8723A Bluetooth                                                          | 17        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 6893      | 73.45%  |
| Nvidia                                          | 1042      | 11.1%   |
| AMD                                             | 898       | 9.57%   |
| Silicon Integrated Systems [SiS]                | 100       | 1.07%   |
| C-Media Electronics                             | 90        | 0.96%   |
| Logitech                                        | 55        | 0.59%   |
| Generalplus Technology                          | 52        | 0.55%   |
| Kingston Technology                             | 29        | 0.31%   |
| VIA Technologies                                | 25        | 0.27%   |
| JMTek                                           | 22        | 0.23%   |
| Texas Instruments                               | 16        | 0.17%   |
| Corsair                                         | 14        | 0.15%   |
| Plantronics                                     | 13        | 0.14%   |
| Realtek Semiconductor                           | 11        | 0.12%   |
| Microsoft                                       | 11        | 0.12%   |
| GN Netcom                                       | 9         | 0.1%    |
| Sony                                            | 8         | 0.09%   |
| Samsung Electronics                             | 6         | 0.06%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.06%   |
| JBL                                             | 5         | 0.05%   |
| Dell                                            | 5         | 0.05%   |
| Samson Technologies                             | 4         | 0.04%   |
| Razer USA                                       | 4         | 0.04%   |
| BR25                                            | 4         | 0.04%   |
| SteelSeries ApS                                 | 3         | 0.03%   |
| Meizu                                           | 3         | 0.03%   |
| Lenovo                                          | 3         | 0.03%   |
| Goldvish                                        | 3         | 0.03%   |
| Focusrite-Novation                              | 3         | 0.03%   |
| BEHRINGER International                         | 3         | 0.03%   |
| Turtle Beach                                    | 2         | 0.02%   |
| Tdlasunnic                                      | 2         | 0.02%   |
| M-Audio                                         | 2         | 0.02%   |
| Hewlett-Packard                                 | 2         | 0.02%   |
| FIFINE Microphones                              | 2         | 0.02%   |
| EDFIER                                          | 2         | 0.02%   |
| Astro Gaming                                    | 2         | 0.02%   |
| Apple                                           | 2         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.01%   |
| Winbond Electronics                             | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1251      | 11.44%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1011      | 9.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 550       | 5.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 470       | 4.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 461       | 4.22%   |
| Intel 8 Series HD Audio Controller                                                                | 442       | 4.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 437       | 4%      |
| Intel Cannon Lake PCH cAVS                                                                        | 415       | 3.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 371       | 3.39%   |
| Intel Broadwell-U Audio Controller                                                                | 351       | 3.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 349       | 3.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 314       | 2.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 312       | 2.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 299       | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 243       | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 211       | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 170       | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 167       | 1.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 163       | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 152       | 1.39%   |
| AMD Wrestler HDMI Audio                                                                           | 150       | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 135       | 1.23%   |
| AMD FCH Azalia Controller                                                                         | 124       | 1.13%   |
| Intel CM238 HD Audio Controller                                                                   | 119       | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 119       | 1.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 112       | 1.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 106       | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 103       | 0.94%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 97        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 95        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 83        | 0.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 79        | 0.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 74        | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 60        | 0.55%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 55        | 0.5%    |
| Generalplus Technology USB Audio Device                                                           | 52        | 0.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 50        | 0.46%   |
| Nvidia Audio device                                                                               | 49        | 0.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 47        | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 45        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 625       | 18.63%  |
| Samsung Electronics | 459       | 13.69%  |
| Kingston            | 311       | 9.27%   |
| SK hynix            | 310       | 9.24%   |
| Unknown             | 302       | 9%      |
| A-DATA Technology   | 279       | 8.32%   |
| Teikon              | 173       | 5.16%   |
| Micron Technology   | 141       | 4.2%    |
| Smart Brazil        | 126       | 3.76%   |
| Crucial             | 93        | 2.77%   |
| Corsair             | 76        | 2.27%   |
| High Bridge         | 68        | 2.03%   |
| Elpida              | 47        | 1.4%    |
| Unknown (ABCD)      | 39        | 1.16%   |
| Unknown             | 36        | 1.07%   |
| Multilaser          | 27        | 0.81%   |
| Apacer              | 21        | 0.63%   |
| Nanya Technology    | 20        | 0.6%    |
| Kllisre             | 16        | 0.48%   |
| Patriot             | 15        | 0.45%   |
| Ramaxel Technology  | 13        | 0.39%   |
| HT Micron           | 13        | 0.39%   |
| PUSKILL             | 10        | 0.3%    |
| Unknown (0x0B5E)    | 8         | 0.24%   |
| Smart Modular       | 8         | 0.24%   |
| Avant               | 7         | 0.21%   |
| Team                | 6         | 0.18%   |
| Atermiter           | 6         | 0.18%   |
| Walton Chaintech    | 5         | 0.15%   |
| Transcend           | 4         | 0.12%   |
| RZX                 | 4         | 0.12%   |
| Kingmax             | 4         | 0.12%   |
| HBS                 | 4         | 0.12%   |
| G.Skill             | 4         | 0.12%   |
| Carry               | 4         | 0.12%   |
| 48spaces            | 4         | 0.12%   |
| Super Talent        | 3         | 0.09%   |
| Qimonda             | 3         | 0.09%   |
| Kreton              | 3         | 0.09%   |
| Juhor               | 3         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 85        | 2.34%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 54        | 1.49%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 53        | 1.46%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 49        | 1.35%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 46        | 1.27%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 46        | 1.27%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 44        | 1.21%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 43        | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 39        | 1.07%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 36        | 0.99%   |
| Unknown                                                          | 36        | 0.99%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 33        | 0.91%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 27        | 0.74%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 26        | 0.72%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 26        | 0.72%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 25        | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.66%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s         | 24        | 0.66%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 24        | 0.66%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 23        | 0.63%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 23        | 0.63%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 23        | 0.63%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 23        | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.61%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 22        | 0.61%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 3200MT/s         | 20        | 0.55%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 19        | 0.52%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 19        | 0.52%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 19        | 0.52%   |
| Smart RAM SF564128CJ8NWMNSEG 4096MB SODIMM DDR3 1600MT/s         | 18        | 0.5%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 18        | 0.5%    |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s           | 17        | 0.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 17        | 0.47%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s             | 17        | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 16        | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 16        | 0.44%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 16        | 0.44%   |
| A-DATA RAM 4JQA-0622AC 4GB SODIMM DDR4 3200MT/s                  | 16        | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 15        | 0.41%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 15        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1221      | 44.22%  |
| DDR4    | 1113      | 40.31%  |
| DDR2    | 159       | 5.76%   |
| LPDDR4  | 81        | 2.93%   |
| SDRAM   | 68        | 2.46%   |
| LPDDR3  | 35        | 1.27%   |
| DDR5    | 27        | 0.98%   |
| DRAM    | 22        | 0.8%    |
| LPDDR5  | 14        | 0.51%   |
| DDR     | 13        | 0.47%   |
| Unknown | 7         | 0.25%   |
| RAM     | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2605      | 94.35%  |
| Row Of Chips | 122       | 4.42%   |
| Unknown      | 19        | 0.69%   |
| DIMM         | 13        | 0.47%   |
| Chip         | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1206      | 38.08%  |
| 8192  | 883       | 27.88%  |
| 2048  | 600       | 18.95%  |
| 16384 | 324       | 10.23%  |
| 1024  | 92        | 2.9%    |
| 32768 | 57        | 1.8%    |
| 512   | 5         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 776       | 24.85%  |
| 2667    | 580       | 18.57%  |
| 2400    | 338       | 10.82%  |
| 3200    | 289       | 9.25%   |
| 1334    | 252       | 8.07%   |
| 1333    | 228       | 7.3%    |
| 2133    | 104       | 3.33%   |
| Unknown | 98        | 3.14%   |
| 800     | 66        | 2.11%   |
| 667     | 64        | 2.05%   |
| 1066    | 51        | 1.63%   |
| 4199    | 42        | 1.34%   |
| 1067    | 40        | 1.28%   |
| 4267    | 27        | 0.86%   |
| 4800    | 26        | 0.83%   |
| 975     | 25        | 0.8%    |
| 533     | 22        | 0.7%    |
| 2048    | 21        | 0.67%   |
| 3266    | 12        | 0.38%   |
| 1867    | 12        | 0.38%   |
| 6400    | 11        | 0.35%   |
| 8400    | 7         | 0.22%   |
| 3733    | 5         | 0.16%   |
| 2933    | 4         | 0.13%   |
| 1200    | 4         | 0.13%   |
| 7467    | 3         | 0.1%    |
| 5600    | 3         | 0.1%    |
| 400     | 2         | 0.06%   |
| 3466    | 1         | 0.03%   |
| 3400    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 2267    | 1         | 0.03%   |
| 1866    | 1         | 0.03%   |
| 1776    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1400    | 1         | 0.03%   |
| 666     | 1         | 0.03%   |
| 2       | 1         | 0.03%   |
| 1       | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 38.1%   |
| Seiko Epson         | 22        | 34.92%  |
| Canon               | 7         | 11.11%  |
| Samsung Electronics | 5         | 7.94%   |
| Brother Industries  | 3         | 4.76%   |
| Xerox               | 1         | 1.59%   |
| MIIIW               | 1         | 1.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                      | 7         | 11.11%  |
| HP LaserJet 1020                              | 3         | 4.76%   |
| HP DeskJet 2700 series                        | 3         | 4.76%   |
| Seiko Epson L6160 Series                      | 2         | 3.17%   |
| Seiko Epson L355 Series                       | 2         | 3.17%   |
| Seiko Epson ET-2600 Series                    | 2         | 3.17%   |
| Samsung M2020 Series                          | 2         | 3.17%   |
| HP LaserJet Professional P1102w               | 2         | 3.17%   |
| HP Ink Tank Wireless 410 series               | 2         | 3.17%   |
| HP Deskjet 3050 J610 series                   | 2         | 3.17%   |
| HP Deskjet 2540 series                        | 2         | 3.17%   |
| Canon PIXMA MG3600 Series                     | 2         | 3.17%   |
| Canon G3000 series                            | 2         | 3.17%   |
| Xerox Phaser 3040                             | 1         | 1.59%   |
| Seiko Epson XP-235 Series                     | 1         | 1.59%   |
| Seiko Epson USB2.0 Printer                    | 1         | 1.59%   |
| Seiko Epson Thermal Receipt Printer [TM-T20]  | 1         | 1.59%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.59%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]  | 1         | 1.59%   |
| Seiko Epson L805 Series                       | 1         | 1.59%   |
| Seiko Epson L382 Series                       | 1         | 1.59%   |
| Seiko Epson L360 Series                       | 1         | 1.59%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.59%   |
| Samsung SCX-4623 Series                       | 1         | 1.59%   |
| Samsung SCX-4200 series                       | 1         | 1.59%   |
| Samsung M332x 382x 402x Series                | 1         | 1.59%   |
| MIIIW MW Keyboard Air Mini                    | 1         | 1.59%   |
| HP LaserJet P2015 series                      | 1         | 1.59%   |
| HP LaserJet 1018                              | 1         | 1.59%   |
| HP DeskJet Plus 6400 series                   | 1         | 1.59%   |
| HP DeskJet F4200 series                       | 1         | 1.59%   |
| HP DeskJet F4100 Printer series               | 1         | 1.59%   |
| HP DeskJet D1360                              | 1         | 1.59%   |
| HP DeskJet 3630 series                        | 1         | 1.59%   |
| HP DeskJet 2300 series                        | 1         | 1.59%   |
| HP DeskJet 2130 series                        | 1         | 1.59%   |
| HP Deskjet 1510                               | 1         | 1.59%   |
| Canon G4010 series                            | 1         | 1.59%   |
| Canon G4000 series                            | 1         | 1.59%   |
| Canon G3010 series                            | 1         | 1.59%   |

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
| Chicony Electronics                    | 1542      | 20.8%   |
| Microdia                               | 917       | 12.37%  |
| Realtek Semiconductor                  | 750       | 10.12%  |
| Quanta                                 | 667       | 9%      |
| Silicon Motion                         | 592       | 7.98%   |
| Sunplus Innovation Technology          | 552       | 7.45%   |
| Bison Electronics                      | 388       | 5.23%   |
| IMC Networks                           | 353       | 4.76%   |
| Suyin                                  | 304       | 4.1%    |
| Syntek                                 | 255       | 3.44%   |
| Alcor Micro                            | 140       | 1.89%   |
| Acer                                   | 114       | 1.54%   |
| Apple                                  | 107       | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) | 96        | 1.29%   |
| Logitech                               | 66        | 0.89%   |
| Samsung Electronics                    | 61        | 0.82%   |
| Ricoh                                  | 54        | 0.73%   |
| Sonix Technology                       | 53        | 0.71%   |
| ALi                                    | 47        | 0.63%   |
| Lite-On Technology                     | 26        | 0.35%   |
| Importek                               | 25        | 0.34%   |
| OmniVision Technologies                | 24        | 0.32%   |
| icSpring                               | 22        | 0.3%    |
| Z-Star Microelectronics                | 21        | 0.28%   |
| Y Media                                | 19        | 0.26%   |
| Unknown                                | 19        | 0.26%   |
| SunplusIT                              | 19        | 0.26%   |
| Lenovo                                 | 13        | 0.18%   |
| Generalplus Technology                 | 13        | 0.18%   |
| LG Electronics                         | 11        | 0.15%   |
| Luxvisions Innotech Limited            | 10        | 0.13%   |
| Primax Electronics                     | 9         | 0.12%   |
| Intel                                  | 9         | 0.12%   |
| Unknown                                | 9         | 0.12%   |
| Pixart Imaging                         | 8         | 0.11%   |
| Sunplus Technology                     | 7         | 0.09%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.09%   |
| Microsoft                              | 7         | 0.09%   |
| Image Processor                        | 7         | 0.09%   |
| Camera                                 | 7         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 362       | 4.88%   |
| Realtek Integrated_Webcam_HD              | 326       | 4.39%   |
| Quanta HD User Facing                     | 290       | 3.91%   |
| Chicony HD User Facing                    | 235       | 3.17%   |
| Silicon Motion Web Camera                 | 227       | 3.06%   |
| Sunplus Integrated_Webcam_HD              | 224       | 3.02%   |
| Chicony HD WebCam                         | 205       | 2.76%   |
| Quanta VGA WebCam                         | 187       | 2.52%   |
| Chicony Integrated Camera                 | 174       | 2.34%   |
| Syntek Integrated Camera                  | 150       | 2.02%   |
| Chicony VGA WebCam                        | 149       | 2.01%   |
| Chicony USB 2.0 Camera                    | 145       | 1.95%   |
| Realtek Integrated Webcam                 | 124       | 1.67%   |
| Sunplus HD WebCam                         | 110       | 1.48%   |
| Quanta HD Webcam                          | 107       | 1.44%   |
| Alcor Micro USB 2.0 Camera                | 83        | 1.12%   |
| Microdia Laptop_Integrated_Webcam_HD      | 81        | 1.09%   |
| Realtek USB Camera                        | 80        | 1.08%   |
| Bison EasyCamera                          | 70        | 0.94%   |
| IMC Networks Integrated Camera            | 69        | 0.93%   |
| Microdia Dell Laptop Integrated Webcam HD | 64        | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)   | 61        | 0.82%   |
| Bison Lenovo EasyCamera                   | 60        | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 57        | 0.77%   |
| Silicon Motion WebCam SC-10HDD12636N      | 55        | 0.74%   |
| Microdia Integrated Webcam HD             | 54        | 0.73%   |
| Sonix USB2.0 HD UVC WebCam                | 53        | 0.71%   |
| IMC Networks USB2.0 HD UVC WebCam         | 51        | 0.69%   |
| Bison VGA WebCam                          | 50        | 0.67%   |
| Bison Integrated Camera                   | 49        | 0.66%   |
| Acer BisonCam, NB Pro                     | 49        | 0.66%   |
| Silicon Motion WebCam SCB-1100N           | 47        | 0.63%   |
| Silicon Motion WebCam SC-13HDL11939N      | 45        | 0.61%   |
| Syntek EasyCamera                         | 44        | 0.59%   |
| Silicon Motion WebCam SC-0311139N         | 44        | 0.59%   |
| Suyin Integrated_Webcam_HD                | 43        | 0.58%   |
| Bison HD Webcam                           | 43        | 0.58%   |
| Realtek HD WebCam                         | 42        | 0.57%   |
| Microdia Integrated Webcam                | 41        | 0.55%   |
| Chicony EasyCamera                        | 40        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 312       | 48.52%  |
| Synaptics                  | 71        | 11.04%  |
| Upek                       | 64        | 9.95%   |
| AuthenTec                  | 63        | 9.8%    |
| Shenzhen Goodix Technology | 61        | 9.49%   |
| LighTuning Technology      | 32        | 4.98%   |
| Samsung Electronics        | 20        | 3.11%   |
| Elan Microelectronics      | 11        | 1.71%   |
| STMicroelectronics         | 4         | 0.62%   |
| Focal-systems.Corp         | 2         | 0.31%   |
| Next Biometrics            | 1         | 0.16%   |
| DigitalPersona             | 1         | 0.16%   |
| Dell                       | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 119       | 18.51%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 54        | 8.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 4.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 29        | 4.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 29        | 4.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 26        | 4.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 26        | 4.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 3.89%   |
| Validity Sensors Fingerprint scanner                                       | 24        | 3.73%   |
| Shenzhen Goodix  FingerPrint Device                                        | 23        | 3.58%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 20        | 3.11%   |
| Samsung Fingerprint Device                                                 | 20        | 3.11%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 20        | 3.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 2.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 14        | 2.18%   |
| AuthenTec AES2810                                                          | 14        | 2.18%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.18%   |
| Validity Sensors VFS491                                                    | 12        | 1.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.87%   |
| Elan ELAN:Fingerprint                                                      | 11        | 1.71%   |
| AuthenTec Fingerprint Sensor                                               | 11        | 1.71%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 10        | 1.56%   |
| Synaptics  WBDI                                                            | 10        | 1.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.4%    |
| Upek TCS5B Fingerprint sensor                                              | 9         | 1.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 1.4%    |
| Shenzhen Goodix FingerPrint                                                | 9         | 1.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.93%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.62%   |
| AuthenTec AES1600                                                          | 4         | 0.62%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.47%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.31%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.16%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.16%   |
| Synaptics WBDI Device                                                      | 1         | 0.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 99        | 56.25%  |
| Alcor Micro               | 25        | 14.2%   |
| Lenovo                    | 14        | 7.95%   |
| Upek                      | 10        | 5.68%   |
| Giesecke & Devrient       | 10        | 5.68%   |
| Aladdin Knowledge Systems | 7         | 3.98%   |
| Watchdata                 | 5         | 2.84%   |
| O2 Micro                  | 3         | 1.7%    |
| SCM Microsystems          | 1         | 0.57%   |
| Gemalto (was Gemplus)     | 1         | 0.57%   |
| Advanced Card Systems     | 1         | 0.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 28        | 15.91%  |
| Broadcom 5880                                                                | 26        | 14.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 14.2%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 14.2%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 11.36%  |
| Lenovo Integrated Smart Card Reader                                          | 14        | 7.95%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 5.68%   |
| Giesecke & Devrient StarSign CUT                                             | 7         | 3.98%   |
| Aladdin Knowledge Systems Token JC                                           | 7         | 3.98%   |
| Watchdata USB Key                                                            | 5         | 2.84%   |
| Giesecke & Devrient StarSign CUT S                                           | 3         | 1.7%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.14%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.57%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.57%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.57%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 6168      | 75.03%  |
| 1     | 1763      | 21.45%  |
| 2     | 240       | 2.92%   |
| 3     | 31        | 0.38%   |
| 4     | 9         | 0.11%   |
| 7     | 4         | 0.05%   |
| 5     | 3         | 0.04%   |
| 8     | 2         | 0.02%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 729       | 31.09%  |
| Fingerprint reader       | 640       | 27.29%  |
| Multimedia controller    | 250       | 10.66%  |
| Net/wireless             | 188       | 8.02%   |
| Chipcard                 | 155       | 6.61%   |
| Bluetooth                | 97        | 4.14%   |
| Camera                   | 76        | 3.24%   |
| Communication controller | 49        | 2.09%   |
| Storage                  | 48        | 2.05%   |
| Sound                    | 38        | 1.62%   |
| Net/ethernet             | 27        | 1.15%   |
| Flash memory             | 23        | 0.98%   |
| Card reader              | 8         | 0.34%   |
| Modem                    | 7         | 0.3%    |
| Firewire controller      | 4         | 0.17%   |
| Network                  | 3         | 0.13%   |
| Unassigned class         | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

