Fedora 35 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

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

Total: 1211

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 450 G7              | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| MSI           | Delta 15 A5EFK              | [1679888c2c](https://linux-hardware.org/?probe=1679888c2c) | May 29, 2022 |
| Dell          | Latitude E7450              | [929e69f0ad](https://linux-hardware.org/?probe=929e69f0ad) | May 27, 2022 |
| Dell          | Inspiron 5770               | [8bacf91a6b](https://linux-hardware.org/?probe=8bacf91a6b) | May 25, 2022 |
| Toshiba       | TECRA A50-C                 | [60a580cb3b](https://linux-hardware.org/?probe=60a580cb3b) | May 25, 2022 |
| Dell          | Vostro 3480                 | [7c5c6aa985](https://linux-hardware.org/?probe=7c5c6aa985) | May 24, 2022 |
| MSI           | GF63 Thin 9SC               | [a2a182a63e](https://linux-hardware.org/?probe=a2a182a63e) | May 23, 2022 |
| Notebook      | NL5xRU                      | [fa1c36e965](https://linux-hardware.org/?probe=fa1c36e965) | May 23, 2022 |
| Dell          | Precision M4400             | [681a684aa6](https://linux-hardware.org/?probe=681a684aa6) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [f9f00f46cc](https://linux-hardware.org/?probe=f9f00f46cc) | May 22, 2022 |
| HP            | ProBook 470 G5              | [1557d1e15f](https://linux-hardware.org/?probe=1557d1e15f) | May 21, 2022 |
| Dell          | Inspiron 5770               | [f87ba7a410](https://linux-hardware.org/?probe=f87ba7a410) | May 19, 2022 |
| HP            | ProBook 430 G5              | [be383d0db4](https://linux-hardware.org/?probe=be383d0db4) | May 19, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | [720ba0b788](https://linux-hardware.org/?probe=720ba0b788) | May 19, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [be93982cf0](https://linux-hardware.org/?probe=be93982cf0) | May 15, 2022 |
| Lenovo        | ThinkPad L540 20AUA27UFR    | [4a6dd68139](https://linux-hardware.org/?probe=4a6dd68139) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4276CTO       | [28cbc6ab88](https://linux-hardware.org/?probe=28cbc6ab88) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4276CTO       | [142c2d12f7](https://linux-hardware.org/?probe=142c2d12f7) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| ASUSTek       | X205TAW                     | [57d9d59b56](https://linux-hardware.org/?probe=57d9d59b56) | May 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| HUAWEI        | KLVL-WXXW                   | [367b6b7bcb](https://linux-hardware.org/?probe=367b6b7bcb) | May 12, 2022 |
| Acer          | Aspire A514-54              | [372742938a](https://linux-hardware.org/?probe=372742938a) | May 12, 2022 |
| Lenovo        | ThinkPad E595 20NFS05500    | [8656f72354](https://linux-hardware.org/?probe=8656f72354) | May 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cbced4dcff](https://linux-hardware.org/?probe=cbced4dcff) | May 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [73b4b6a015](https://linux-hardware.org/?probe=73b4b6a015) | May 11, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [3f587813b0](https://linux-hardware.org/?probe=3f587813b0) | May 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [3444835d49](https://linux-hardware.org/?probe=3444835d49) | May 10, 2022 |
| HP            | Laptop 14-ck0xxx            | [24b8860aaf](https://linux-hardware.org/?probe=24b8860aaf) | May 10, 2022 |
| Google        | Droid                       | [35d0a5a944](https://linux-hardware.org/?probe=35d0a5a944) | May 10, 2022 |
| Dell          | XPS 13 9310                 | [d95a50c16a](https://linux-hardware.org/?probe=d95a50c16a) | May 09, 2022 |
| Positivo      | C41TB                       | [6ba90f69f3](https://linux-hardware.org/?probe=6ba90f69f3) | May 09, 2022 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [ba03e5bb90](https://linux-hardware.org/?probe=ba03e5bb90) | May 08, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d5348dedec](https://linux-hardware.org/?probe=d5348dedec) | May 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [ddded0e6c3](https://linux-hardware.org/?probe=ddded0e6c3) | May 08, 2022 |
| MSI           | GE63 Raider RGB 8RE         | [34bd31c9f9](https://linux-hardware.org/?probe=34bd31c9f9) | May 07, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [2effde38b7](https://linux-hardware.org/?probe=2effde38b7) | May 07, 2022 |
| Apple         | MacBookPro11,1              | [08cbb5e9f7](https://linux-hardware.org/?probe=08cbb5e9f7) | May 07, 2022 |
| Lenovo        | G565 20071                  | [ef5983ea64](https://linux-hardware.org/?probe=ef5983ea64) | May 07, 2022 |
| Toshiba       | TECRA R840                  | [38ff1a3344](https://linux-hardware.org/?probe=38ff1a3344) | May 07, 2022 |
| Dell          | Precision 5510              | [749eb5ff32](https://linux-hardware.org/?probe=749eb5ff32) | May 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [38f5d37dcc](https://linux-hardware.org/?probe=38f5d37dcc) | May 07, 2022 |
| Google        | Droid                       | [422252faa5](https://linux-hardware.org/?probe=422252faa5) | May 07, 2022 |
| ASUSTek       | X205TAW                     | [577c71e530](https://linux-hardware.org/?probe=577c71e530) | May 06, 2022 |
| Fujitsu       | CELSIUS H720                | [7c41d6fd4d](https://linux-hardware.org/?probe=7c41d6fd4d) | May 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f3e4a840e8](https://linux-hardware.org/?probe=f3e4a840e8) | May 06, 2022 |
| Dell          | Precision M4700             | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| MSI           | GF63 Thin 10SCSR            | [ad8ee15b6d](https://linux-hardware.org/?probe=ad8ee15b6d) | May 06, 2022 |
| Dell          | Latitude 5420               | [dbe0cffc08](https://linux-hardware.org/?probe=dbe0cffc08) | May 06, 2022 |
| HP            | ZBook 17 G5                 | [5190bc7cf3](https://linux-hardware.org/?probe=5190bc7cf3) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [0ca81980a3](https://linux-hardware.org/?probe=0ca81980a3) | May 06, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8c1fedaa4b](https://linux-hardware.org/?probe=8c1fedaa4b) | May 06, 2022 |
| Dell          | Vostro 15 5510              | [e2b06a4a28](https://linux-hardware.org/?probe=e2b06a4a28) | May 05, 2022 |
| Apple         | MacBookPro6,2               | [7e44142aac](https://linux-hardware.org/?probe=7e44142aac) | May 05, 2022 |
| Apple         | MacBookPro6,2               | [8e99db77e1](https://linux-hardware.org/?probe=8e99db77e1) | May 05, 2022 |
| Dell          | XPS 13 9310                 | [fcfb95470e](https://linux-hardware.org/?probe=fcfb95470e) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | [428f653301](https://linux-hardware.org/?probe=428f653301) | May 05, 2022 |
| Timi          | Redmi G                     | [a2738a4d6e](https://linux-hardware.org/?probe=a2738a4d6e) | May 05, 2022 |
| ASUSTek       | X550CC                      | [8306d5b694](https://linux-hardware.org/?probe=8306d5b694) | May 05, 2022 |
| Teclast       | F7 Plus                     | [6aedd4e799](https://linux-hardware.org/?probe=6aedd4e799) | May 05, 2022 |
| Lenovo        | G50-70 20351                | [53f05e9b8c](https://linux-hardware.org/?probe=53f05e9b8c) | May 05, 2022 |
| HP            | Laptop 14-fq0xxx            | [29abb73f0b](https://linux-hardware.org/?probe=29abb73f0b) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| HP            | 635                         | [66305e8923](https://linux-hardware.org/?probe=66305e8923) | May 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [155ac0a54c](https://linux-hardware.org/?probe=155ac0a54c) | May 04, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [cf2375fae1](https://linux-hardware.org/?probe=cf2375fae1) | May 04, 2022 |
| Alienware     | m15 R4                      | [3b09d65e13](https://linux-hardware.org/?probe=3b09d65e13) | May 04, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | [9da4b1ddc5](https://linux-hardware.org/?probe=9da4b1ddc5) | May 03, 2022 |
| Chuwi         | Hi10 Go                     | [33ea61404a](https://linux-hardware.org/?probe=33ea61404a) | May 03, 2022 |
| ASUSTek       | X550CC                      | [e4918450ce](https://linux-hardware.org/?probe=e4918450ce) | May 03, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5c929eea1c](https://linux-hardware.org/?probe=5c929eea1c) | May 03, 2022 |
| Toshiba       | Satellite U940              | [3d6bd2511e](https://linux-hardware.org/?probe=3d6bd2511e) | May 03, 2022 |
| Acer          | Aspire A315-56              | [4321ddf926](https://linux-hardware.org/?probe=4321ddf926) | May 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3be0a0d66d](https://linux-hardware.org/?probe=3be0a0d66d) | May 03, 2022 |
| Alienware     | m15 R4                      | [1f5f3048d6](https://linux-hardware.org/?probe=1f5f3048d6) | May 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | [a00b8586b6](https://linux-hardware.org/?probe=a00b8586b6) | May 03, 2022 |
| HP            | Laptop 14s-dq1xxx           | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [90d0e8adb2](https://linux-hardware.org/?probe=90d0e8adb2) | May 02, 2022 |
| HP            | Pavilion 15                 | [d6bd192469](https://linux-hardware.org/?probe=d6bd192469) | May 01, 2022 |
| HP            | Pavilion 15                 | [ec8a9ceb87](https://linux-hardware.org/?probe=ec8a9ceb87) | May 01, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [73396d4b0b](https://linux-hardware.org/?probe=73396d4b0b) | May 01, 2022 |
| Acer          | Swift SF314-55G             | [1935c949a2](https://linux-hardware.org/?probe=1935c949a2) | May 01, 2022 |
| Dell          | Inspiron 15-3567            | [589f58c857](https://linux-hardware.org/?probe=589f58c857) | Apr 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [2065a3c2f3](https://linux-hardware.org/?probe=2065a3c2f3) | Apr 30, 2022 |
| Acer          | Aspire A514-54              | [70efbbb6c7](https://linux-hardware.org/?probe=70efbbb6c7) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| Dell          | XPS 13 7390                 | [aadc641825](https://linux-hardware.org/?probe=aadc641825) | Apr 29, 2022 |
| Dell          | Inspiron N5110              | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| Acer          | Aspire A515-56              | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| MSI           | Katana GF76 11SC            | [15dcec28fc](https://linux-hardware.org/?probe=15dcec28fc) | Apr 29, 2022 |
| Lenovo        | ThinkPad X390 20Q1SCDR00    | [41a3cac1f4](https://linux-hardware.org/?probe=41a3cac1f4) | Apr 29, 2022 |
| Unknown       | X133                        | [b90d940d9e](https://linux-hardware.org/?probe=b90d940d9e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Dell          | Latitude 5310               | [b4e7215e3b](https://linux-hardware.org/?probe=b4e7215e3b) | Apr 28, 2022 |
| HP            | 255 G6 Notebook PC          | [d52cf822df](https://linux-hardware.org/?probe=d52cf822df) | Apr 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [6f26e0d7bd](https://linux-hardware.org/?probe=6f26e0d7bd) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| System76      | Pangolin                    | [d326fc9a39](https://linux-hardware.org/?probe=d326fc9a39) | Apr 27, 2022 |
| Lenovo        | IdeaPad Y470 0855           | [ee26833b58](https://linux-hardware.org/?probe=ee26833b58) | Apr 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f3c9dd19da](https://linux-hardware.org/?probe=f3c9dd19da) | Apr 26, 2022 |
| HP            | Notebook                    | [ec93418371](https://linux-hardware.org/?probe=ec93418371) | Apr 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [e4c1fa069d](https://linux-hardware.org/?probe=e4c1fa069d) | Apr 26, 2022 |
| HP            | Pavilion Notebook           | [6a34230d87](https://linux-hardware.org/?probe=6a34230d87) | Apr 26, 2022 |
| Apple         | MacBookPro11,1              | [a8626eb701](https://linux-hardware.org/?probe=a8626eb701) | Apr 26, 2022 |
| HP            | ProBook 455R G6             | [3118a03e9b](https://linux-hardware.org/?probe=3118a03e9b) | Apr 25, 2022 |
| Google        | Bobba                       | [008afa9913](https://linux-hardware.org/?probe=008afa9913) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| Dell          | Inspiron 5567               | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [ac10947315](https://linux-hardware.org/?probe=ac10947315) | Apr 24, 2022 |
| HP            | EliteBook 850 G6            | [438ad440d0](https://linux-hardware.org/?probe=438ad440d0) | Apr 24, 2022 |
| ASUSTek       | X750JN                      | [343a4c47a6](https://linux-hardware.org/?probe=343a4c47a6) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [36f385210f](https://linux-hardware.org/?probe=36f385210f) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Acer          | Swift SF514-51              | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| Framework     | Laptop                      | [dbc00cbd42](https://linux-hardware.org/?probe=dbc00cbd42) | Apr 23, 2022 |
| Acer          | TravelMate P215-41-G2       | [dcfad64d9d](https://linux-hardware.org/?probe=dcfad64d9d) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [ce0b6939ac](https://linux-hardware.org/?probe=ce0b6939ac) | Apr 22, 2022 |
| Google        | Bobba                       | [5ad66cbf53](https://linux-hardware.org/?probe=5ad66cbf53) | Apr 22, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Sony          | VPCEB3PGX                   | [1771623608](https://linux-hardware.org/?probe=1771623608) | Apr 22, 2022 |
| Timi          | TM1701                      | [dba97f1875](https://linux-hardware.org/?probe=dba97f1875) | Apr 21, 2022 |
| HP            | ZBook 15 G3                 | [664867989b](https://linux-hardware.org/?probe=664867989b) | Apr 21, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [aa8173a46a](https://linux-hardware.org/?probe=aa8173a46a) | Apr 20, 2022 |
| Dell          | XPS 13 9350                 | [ed27d7c06d](https://linux-hardware.org/?probe=ed27d7c06d) | Apr 20, 2022 |
| Dell          | Inspiron 7577               | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| HP            | ElitePad 1000 G2            | [05daf3f64b](https://linux-hardware.org/?probe=05daf3f64b) | Apr 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Lenovo        | Z50-70 20354                | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Dell          | XPS 13 9310                 | [0f924d06d6](https://linux-hardware.org/?probe=0f924d06d6) | Apr 19, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [4fe85803b7](https://linux-hardware.org/?probe=4fe85803b7) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| HP            | Laptop 15-dw0xxx            | [7f35172610](https://linux-hardware.org/?probe=7f35172610) | Apr 19, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [fa995794ba](https://linux-hardware.org/?probe=fa995794ba) | Apr 18, 2022 |
| Apple         | MacBookPro9,2               | [812afb255a](https://linux-hardware.org/?probe=812afb255a) | Apr 18, 2022 |
| Acer          | Swift SF114-34              | [068741773e](https://linux-hardware.org/?probe=068741773e) | Apr 18, 2022 |
| ASUSTek       | G551JW                      | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Timi          | TM1604                      | [2c182df836](https://linux-hardware.org/?probe=2c182df836) | Apr 18, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [2369e789c7](https://linux-hardware.org/?probe=2369e789c7) | Apr 18, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [08f9942632](https://linux-hardware.org/?probe=08f9942632) | Apr 18, 2022 |
| Dell          | Latitude E5520              | [1b428165cf](https://linux-hardware.org/?probe=1b428165cf) | Apr 18, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | [db5f56be25](https://linux-hardware.org/?probe=db5f56be25) | Apr 18, 2022 |
| HP            | ElitePad 1000 G2            | [f7888cc252](https://linux-hardware.org/?probe=f7888cc252) | Apr 18, 2022 |
| HP            | Spectre Notebook            | [42d4ceac84](https://linux-hardware.org/?probe=42d4ceac84) | Apr 18, 2022 |
| HP            | Pavilion Laptop 15-cc6xx    | [42836ca452](https://linux-hardware.org/?probe=42836ca452) | Apr 17, 2022 |
| Chuwi         | HeroBook Air                | [647f782e9f](https://linux-hardware.org/?probe=647f782e9f) | Apr 17, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Positivo      | H14BU08                     | [43d44df3d2](https://linux-hardware.org/?probe=43d44df3d2) | Apr 16, 2022 |
| Alienware     | Area-51m R2                 | [e6a7b0ef42](https://linux-hardware.org/?probe=e6a7b0ef42) | Apr 16, 2022 |
| Dell          | Inspiron 5458               | [5f7dafa5b9](https://linux-hardware.org/?probe=5f7dafa5b9) | Apr 16, 2022 |
| Lenovo        | ThinkPad T490 20N3S19L00    | [5812cc4868](https://linux-hardware.org/?probe=5812cc4868) | Apr 16, 2022 |
| Dell          | XPS 13 9350                 | [d0e37d8bc1](https://linux-hardware.org/?probe=d0e37d8bc1) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b07e7e9974](https://linux-hardware.org/?probe=b07e7e9974) | Apr 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| Google        | Squawks                     | [a6dc68bba1](https://linux-hardware.org/?probe=a6dc68bba1) | Apr 15, 2022 |
| Notebook      | NH55RGQ                     | [a5b036d6a3](https://linux-hardware.org/?probe=a5b036d6a3) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [c14702d147](https://linux-hardware.org/?probe=c14702d147) | Apr 15, 2022 |
| Toshiba       | Satellite P755              | [fc39ac9f46](https://linux-hardware.org/?probe=fc39ac9f46) | Apr 15, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e9969def2d](https://linux-hardware.org/?probe=e9969def2d) | Apr 15, 2022 |
| Acer          | Aspire A515-51              | [dcae73146f](https://linux-hardware.org/?probe=dcae73146f) | Apr 15, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0646755403](https://linux-hardware.org/?probe=0646755403) | Apr 15, 2022 |
| Getac         | S410                        | [a0ec8cd50e](https://linux-hardware.org/?probe=a0ec8cd50e) | Apr 14, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [832620cf67](https://linux-hardware.org/?probe=832620cf67) | Apr 14, 2022 |
| Framework     | Laptop                      | [a5950266d1](https://linux-hardware.org/?probe=a5950266d1) | Apr 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0000... | [50325a2b5c](https://linux-hardware.org/?probe=50325a2b5c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [cc1fade012](https://linux-hardware.org/?probe=cc1fade012) | Apr 14, 2022 |
| Framework     | Laptop                      | [8734154fb6](https://linux-hardware.org/?probe=8734154fb6) | Apr 14, 2022 |
| ASUSTek       | ROG Strix G713QC_G713QC     | [c54b458c01](https://linux-hardware.org/?probe=c54b458c01) | Apr 14, 2022 |
| Lenovo        | G500 20236                  | [2decdc1731](https://linux-hardware.org/?probe=2decdc1731) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| Lenovo        | ThinkPad P52 20MAS17228     | [dac73320e9](https://linux-hardware.org/?probe=dac73320e9) | Apr 14, 2022 |
| Dell          | XPS 13 9360                 | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | Latitude E6230              | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [84815ec94e](https://linux-hardware.org/?probe=84815ec94e) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | [89de41a490](https://linux-hardware.org/?probe=89de41a490) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [5ef7e630fa](https://linux-hardware.org/?probe=5ef7e630fa) | Apr 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7e6cb72711](https://linux-hardware.org/?probe=7e6cb72711) | Apr 13, 2022 |
| Dell          | XPS 13 9370                 | [20ed59527a](https://linux-hardware.org/?probe=20ed59527a) | Apr 13, 2022 |
| Acer          | Aspire A715-74G             | [9f5a2049e3](https://linux-hardware.org/?probe=9f5a2049e3) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f365986dfc](https://linux-hardware.org/?probe=f365986dfc) | Apr 13, 2022 |
| Dell          | XPS 13 9360                 | [20f315a2e7](https://linux-hardware.org/?probe=20f315a2e7) | Apr 13, 2022 |
| Dell          | XPS 13 7390                 | [dcca838772](https://linux-hardware.org/?probe=dcca838772) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [332355ddfa](https://linux-hardware.org/?probe=332355ddfa) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [53ba287837](https://linux-hardware.org/?probe=53ba287837) | Apr 13, 2022 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [6dc94a82ab](https://linux-hardware.org/?probe=6dc94a82ab) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| Framework     | Laptop                      | [6de996aa1e](https://linux-hardware.org/?probe=6de996aa1e) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0c40d42b4a](https://linux-hardware.org/?probe=0c40d42b4a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| ASUSTek       | X75VCP                      | [21e0b65e1b](https://linux-hardware.org/?probe=21e0b65e1b) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| Dell          | Vostro 5470                 | [e79417a89e](https://linux-hardware.org/?probe=e79417a89e) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | [3385b17dd8](https://linux-hardware.org/?probe=3385b17dd8) | Apr 13, 2022 |
| Dell          | Latitude E6530              | [597013072b](https://linux-hardware.org/?probe=597013072b) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | [0d300b2fc3](https://linux-hardware.org/?probe=0d300b2fc3) | Apr 12, 2022 |
| HP            | EliteBook 2540p             | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | [4d7659bd74](https://linux-hardware.org/?probe=4d7659bd74) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| HP            | ProBook 455 G7              | [153f53dadd](https://linux-hardware.org/?probe=153f53dadd) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | ProBook 455 G7              | [edebd20c8e](https://linux-hardware.org/?probe=edebd20c8e) | Apr 11, 2022 |
| Acer          | Aspire E5-571               | [b6c1c28521](https://linux-hardware.org/?probe=b6c1c28521) | Apr 11, 2022 |
| Apple         | MacBookPro4,1               | [40dd641006](https://linux-hardware.org/?probe=40dd641006) | Apr 10, 2022 |
| Apple         | MacBookPro4,1               | [2e80786e39](https://linux-hardware.org/?probe=2e80786e39) | Apr 10, 2022 |
| HP            | Pavilion 15                 | [f69f54968e](https://linux-hardware.org/?probe=f69f54968e) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| ASUSTek       | X405UQ                      | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| Dell          | Latitude 7480               | [b235ce5f92](https://linux-hardware.org/?probe=b235ce5f92) | Apr 10, 2022 |
| ASUSTek       | X750JN                      | [703a4e77a3](https://linux-hardware.org/?probe=703a4e77a3) | Apr 09, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f8c3b429a2](https://linux-hardware.org/?probe=f8c3b429a2) | Apr 09, 2022 |
| Dell          | Latitude 7275               | [fe36710853](https://linux-hardware.org/?probe=fe36710853) | Apr 09, 2022 |
| Dell          | Latitude 7275               | [e6bc45d8d9](https://linux-hardware.org/?probe=e6bc45d8d9) | Apr 09, 2022 |
| Dell          | Inspiron 5458               | [7b3a49ec3c](https://linux-hardware.org/?probe=7b3a49ec3c) | Apr 09, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [eebc86ccbe](https://linux-hardware.org/?probe=eebc86ccbe) | Apr 09, 2022 |
| Dell          | Inspiron 15-3567            | [3ffa339c32](https://linux-hardware.org/?probe=3ffa339c32) | Apr 09, 2022 |
| Acer          | Aspire E1-531               | [9dbe75c090](https://linux-hardware.org/?probe=9dbe75c090) | Apr 09, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [e76eb71b7f](https://linux-hardware.org/?probe=e76eb71b7f) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [919af587bb](https://linux-hardware.org/?probe=919af587bb) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [3b16991947](https://linux-hardware.org/?probe=3b16991947) | Apr 08, 2022 |
| Dell          | XPS 13 7390                 | [03940a7514](https://linux-hardware.org/?probe=03940a7514) | Apr 08, 2022 |
| Acer          | Aspire A315-31              | [afd87f36b2](https://linux-hardware.org/?probe=afd87f36b2) | Apr 08, 2022 |
| ASUSTek       | N551JB                      | [edbf102771](https://linux-hardware.org/?probe=edbf102771) | Apr 08, 2022 |
| HP            | ProBook 445 G7 Notebook ... | [0d15f8a702](https://linux-hardware.org/?probe=0d15f8a702) | Apr 07, 2022 |
| Dell          | Latitude E6530              | [a99419647f](https://linux-hardware.org/?probe=a99419647f) | Apr 07, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [4a53e94722](https://linux-hardware.org/?probe=4a53e94722) | Apr 07, 2022 |
| Apple         | MacBookPro10,1              | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| ASUSTek       | N551JB                      | [e1f0b15197](https://linux-hardware.org/?probe=e1f0b15197) | Apr 07, 2022 |
| ASUSTek       | GL553VW                     | [779c7e3858](https://linux-hardware.org/?probe=779c7e3858) | Apr 07, 2022 |
| Framework     | Laptop                      | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [158e261517](https://linux-hardware.org/?probe=158e261517) | Apr 07, 2022 |
| Apple         | MacBookPro8,1               | [6cd80e7357](https://linux-hardware.org/?probe=6cd80e7357) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| Dell          | Latitude 3520               | [1ec7dedd4c](https://linux-hardware.org/?probe=1ec7dedd4c) | Apr 06, 2022 |
| Dell          | Precision 7550              | [89df3f1bfd](https://linux-hardware.org/?probe=89df3f1bfd) | Apr 06, 2022 |
| Intel         | Shark Bay Client platfor... | [8b1a97afe3](https://linux-hardware.org/?probe=8b1a97afe3) | Apr 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [a668b151a3](https://linux-hardware.org/?probe=a668b151a3) | Apr 06, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a6c37e7ee4](https://linux-hardware.org/?probe=a6c37e7ee4) | Apr 06, 2022 |
| Dell          | G3 3579                     | [9994b24cef](https://linux-hardware.org/?probe=9994b24cef) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [dbb3f589ad](https://linux-hardware.org/?probe=dbb3f589ad) | Apr 06, 2022 |
| Acer          | Nitro AN517-41              | [b7cc683cc7](https://linux-hardware.org/?probe=b7cc683cc7) | Apr 05, 2022 |
| Dell          | XPS 13 9305                 | [0e254bc578](https://linux-hardware.org/?probe=0e254bc578) | Apr 05, 2022 |
| Dell          | XPS 13 9370                 | [a2dd193a18](https://linux-hardware.org/?probe=a2dd193a18) | Apr 05, 2022 |
| Acer          | Aspire A315-31              | [219ae7c834](https://linux-hardware.org/?probe=219ae7c834) | Apr 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [00da75f071](https://linux-hardware.org/?probe=00da75f071) | Apr 05, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [18e1fc86be](https://linux-hardware.org/?probe=18e1fc86be) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [5c28fb1391](https://linux-hardware.org/?probe=5c28fb1391) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [92130ffb61](https://linux-hardware.org/?probe=92130ffb61) | Apr 04, 2022 |
| Dell          | XPS 15 9570                 | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [bdd5a36f62](https://linux-hardware.org/?probe=bdd5a36f62) | Apr 04, 2022 |
| Apple         | MacBookPro15,1              | [1c4423ca19](https://linux-hardware.org/?probe=1c4423ca19) | Apr 04, 2022 |
| HP            | ElitePad 1000 G2            | [d479e2ae4a](https://linux-hardware.org/?probe=d479e2ae4a) | Apr 04, 2022 |
| ASUSTek       | UX301LAA                    | [1c631fdb63](https://linux-hardware.org/?probe=1c631fdb63) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| Sony          | VPCEB4L1E                   | [358783a077](https://linux-hardware.org/?probe=358783a077) | Apr 03, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Latitude 5520               | [0fc592dd2c](https://linux-hardware.org/?probe=0fc592dd2c) | Apr 03, 2022 |
| HP            | EliteBook 8770w             | [e826deade2](https://linux-hardware.org/?probe=e826deade2) | Apr 03, 2022 |
| Framework     | Laptop                      | [a0e35b1871](https://linux-hardware.org/?probe=a0e35b1871) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| Dell          | Precision 5530              | [96b22b6124](https://linux-hardware.org/?probe=96b22b6124) | Apr 03, 2022 |
| Dell          | Inspiron 5548               | [d187a0de09](https://linux-hardware.org/?probe=d187a0de09) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| Samsung       | 270E5J/2570EJ               | [2911dea3f0](https://linux-hardware.org/?probe=2911dea3f0) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | ProBook 650 G1              | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| Acer          | Swift SF114-34              | [5dcb0a1847](https://linux-hardware.org/?probe=5dcb0a1847) | Apr 02, 2022 |
| Dell          | Latitude 5500               | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| Timi          | TM1612                      | [7eb83bb23a](https://linux-hardware.org/?probe=7eb83bb23a) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [3c89c6c9d8](https://linux-hardware.org/?probe=3c89c6c9d8) | Apr 02, 2022 |
| ASUSTek       | X750JN                      | [11153fc9f1](https://linux-hardware.org/?probe=11153fc9f1) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [055b15c7a9](https://linux-hardware.org/?probe=055b15c7a9) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| Gigabyte      | P65Q                        | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [82ec2ff5f6](https://linux-hardware.org/?probe=82ec2ff5f6) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [7aefa77b4b](https://linux-hardware.org/?probe=7aefa77b4b) | Apr 01, 2022 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [97505bf353](https://linux-hardware.org/?probe=97505bf353) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Dell          | Inspiron 14 5410            | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [d18cd45522](https://linux-hardware.org/?probe=d18cd45522) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [ec162ebae4](https://linux-hardware.org/?probe=ec162ebae4) | Apr 01, 2022 |
| GPU Compan... | GWTN141-4                   | [81e7639a72](https://linux-hardware.org/?probe=81e7639a72) | Apr 01, 2022 |
| HP            | ElitePad 1000 G2            | [b6da5f9629](https://linux-hardware.org/?probe=b6da5f9629) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Dell          | Inspiron 5548               | [06b3aacb51](https://linux-hardware.org/?probe=06b3aacb51) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [913c396bde](https://linux-hardware.org/?probe=913c396bde) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [6774f9f9c8](https://linux-hardware.org/?probe=6774f9f9c8) | Apr 01, 2022 |
| HP            | Laptop 17z-ca300            | [726d1e7b0f](https://linux-hardware.org/?probe=726d1e7b0f) | Mar 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [c01344bd43](https://linux-hardware.org/?probe=c01344bd43) | Mar 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | Pavilion Notebook           | [a18360bae8](https://linux-hardware.org/?probe=a18360bae8) | Mar 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6ab27f6f88](https://linux-hardware.org/?probe=6ab27f6f88) | Mar 31, 2022 |
| Samsung       | RC420/RC520/RC720           | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [43e45df9f5](https://linux-hardware.org/?probe=43e45df9f5) | Mar 30, 2022 |
| Toshiba       | TECRA Z50-A                 | [cd333e5720](https://linux-hardware.org/?probe=cd333e5720) | Mar 30, 2022 |
| Dell          | XPS 13 7390                 | [db3d70e53a](https://linux-hardware.org/?probe=db3d70e53a) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | [3a64f14cc4](https://linux-hardware.org/?probe=3a64f14cc4) | Mar 30, 2022 |
| HONOR         | NBD-WXX9                    | [dd51589f73](https://linux-hardware.org/?probe=dd51589f73) | Mar 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0f18e7b54b](https://linux-hardware.org/?probe=0f18e7b54b) | Mar 30, 2022 |
| HP            | Pavilion 17                 | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fd1759c341](https://linux-hardware.org/?probe=fd1759c341) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HP            | OMEN by Laptop              | [88b64a12df](https://linux-hardware.org/?probe=88b64a12df) | Mar 29, 2022 |
| Hampoo        | C1W6_AP123C_6GB Reserved    | [ff622b910d](https://linux-hardware.org/?probe=ff622b910d) | Mar 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Dell          | Vostro 3580                 | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c1384b9063](https://linux-hardware.org/?probe=c1384b9063) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| MSI           | Delta 15 A5EFK              | [9c5efbe2a7](https://linux-hardware.org/?probe=9c5efbe2a7) | Mar 28, 2022 |
| HP            | Pavilion Notebook           | [ac807c9324](https://linux-hardware.org/?probe=ac807c9324) | Mar 27, 2022 |
| Dell          | Inspiron 3505               | [c472ae03f6](https://linux-hardware.org/?probe=c472ae03f6) | Mar 27, 2022 |
| HP            | ProBook 470 G5              | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| HP            | EliteBook 850 G6            | [084d60ff3b](https://linux-hardware.org/?probe=084d60ff3b) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| Fujitsu       | LIFEBOOK E746               | [dc5e0a376b](https://linux-hardware.org/?probe=dc5e0a376b) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| Acer          | Aspire E5-575G              | [b47822d246](https://linux-hardware.org/?probe=b47822d246) | Mar 26, 2022 |
| ASUSTek       | N550JK                      | [a3ecefa43f](https://linux-hardware.org/?probe=a3ecefa43f) | Mar 26, 2022 |
| HP            | ElitePad 1000 G2            | [5861c8e75a](https://linux-hardware.org/?probe=5861c8e75a) | Mar 26, 2022 |
| Acer          | Aspire E5-573G              | [b78f0137ba](https://linux-hardware.org/?probe=b78f0137ba) | Mar 26, 2022 |
| Alienware     | m15 R6                      | [5505410995](https://linux-hardware.org/?probe=5505410995) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS09Y19    | [2602549f95](https://linux-hardware.org/?probe=2602549f95) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [1d0229f697](https://linux-hardware.org/?probe=1d0229f697) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [1ab1216e5b](https://linux-hardware.org/?probe=1ab1216e5b) | Mar 25, 2022 |
| Dell          | Vostro 5402                 | [b47655a721](https://linux-hardware.org/?probe=b47655a721) | Mar 25, 2022 |
| Sony          | VGN-FW180D                  | [9bbcb3d0ac](https://linux-hardware.org/?probe=9bbcb3d0ac) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [da358bbf5c](https://linux-hardware.org/?probe=da358bbf5c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [4a6b3d619c](https://linux-hardware.org/?probe=4a6b3d619c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [7d1fa138d0](https://linux-hardware.org/?probe=7d1fa138d0) | Mar 25, 2022 |
| HP            | Pavilion 11 x360 PC         | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| Lenovo        | G50-45 80E3                 | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| Dell          | XPS 15 9500                 | [911fd95d9f](https://linux-hardware.org/?probe=911fd95d9f) | Mar 25, 2022 |
| Dell          | Inspiron 5567               | [7c80283af3](https://linux-hardware.org/?probe=7c80283af3) | Mar 24, 2022 |
| Acer          | Aspire A515-43              | [52bc15cdf9](https://linux-hardware.org/?probe=52bc15cdf9) | Mar 24, 2022 |
| System76      | Gazelle                     | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| HP            | Laptop 15-db0xxx            | [ef1af7bbae](https://linux-hardware.org/?probe=ef1af7bbae) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [55730a4af8](https://linux-hardware.org/?probe=55730a4af8) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| ASUSTek       | X75VCP                      | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [6285900fd7](https://linux-hardware.org/?probe=6285900fd7) | Mar 22, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [f140780c32](https://linux-hardware.org/?probe=f140780c32) | Mar 22, 2022 |
| Acer          | Aspire A515-43              | [6934e641a4](https://linux-hardware.org/?probe=6934e641a4) | Mar 22, 2022 |
| Dell          | Latitude 5520               | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| Razer         | Blade Stealth               | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| Dell          | Inspiron 15 5501            | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | [40767d2545](https://linux-hardware.org/?probe=40767d2545) | Mar 20, 2022 |
| HP            | Laptop 14-dk0xxx            | [bde47f2d75](https://linux-hardware.org/?probe=bde47f2d75) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8366f92538](https://linux-hardware.org/?probe=8366f92538) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8f96005683](https://linux-hardware.org/?probe=8f96005683) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | [3c40b29b63](https://linux-hardware.org/?probe=3c40b29b63) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | [ce6b8e3716](https://linux-hardware.org/?probe=ce6b8e3716) | Mar 19, 2022 |
| Digibras      | NH4CU03                     | [7970a8e8d2](https://linux-hardware.org/?probe=7970a8e8d2) | Mar 19, 2022 |
| eMachines     | E725 V1.03                  | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Acer          | Aspire A317-51G             | [f2a7cadaff](https://linux-hardware.org/?probe=f2a7cadaff) | Mar 18, 2022 |
| Toshiba       | Satellite C855-12R          | [96554352c8](https://linux-hardware.org/?probe=96554352c8) | Mar 18, 2022 |
| Lenovo        | ThinkPad P53 20QN000HGE     | [db71f4d011](https://linux-hardware.org/?probe=db71f4d011) | Mar 18, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c869642fe9](https://linux-hardware.org/?probe=c869642fe9) | Mar 18, 2022 |
| Dell          | Latitude E6420              | [e97e686e5e](https://linux-hardware.org/?probe=e97e686e5e) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| Lenovo        | G40-80 80JE                 | [c41639222f](https://linux-hardware.org/?probe=c41639222f) | Mar 17, 2022 |
| Dell          | Inspiron 5502               | [b5aeb18001](https://linux-hardware.org/?probe=b5aeb18001) | Mar 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| Dell          | XPS 15 9550                 | [f7eb058e61](https://linux-hardware.org/?probe=f7eb058e61) | Mar 17, 2022 |
| Lenovo        | G50-70 20351                | [16ced37ed8](https://linux-hardware.org/?probe=16ced37ed8) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 428767U       | [380351014b](https://linux-hardware.org/?probe=380351014b) | Mar 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | [1ac160aea7](https://linux-hardware.org/?probe=1ac160aea7) | Mar 15, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [66bda745cd](https://linux-hardware.org/?probe=66bda745cd) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [62038e09e8](https://linux-hardware.org/?probe=62038e09e8) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [cbebb0b476](https://linux-hardware.org/?probe=cbebb0b476) | Mar 15, 2022 |
| MSI           | GE75 Raider 10SE            | [affad66907](https://linux-hardware.org/?probe=affad66907) | Mar 14, 2022 |
| Acer          | Calpella                    | [038e7b15ee](https://linux-hardware.org/?probe=038e7b15ee) | Mar 14, 2022 |
| MSI           | GE75 Raider 10SE            | [79744a34f1](https://linux-hardware.org/?probe=79744a34f1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | ProBook 6465b               | [95ecc6cdbd](https://linux-hardware.org/?probe=95ecc6cdbd) | Mar 14, 2022 |
| Apple         | MacBookPro9,2               | [b400e8a455](https://linux-hardware.org/?probe=b400e8a455) | Mar 14, 2022 |
| Apple         | MacBook7,1                  | [5cdaea7c5a](https://linux-hardware.org/?probe=5cdaea7c5a) | Mar 14, 2022 |
| Dell          | Vostro 1014                 | [8df761ef60](https://linux-hardware.org/?probe=8df761ef60) | Mar 13, 2022 |
| Apple         | MacBookPro16,1              | [9cce5830b5](https://linux-hardware.org/?probe=9cce5830b5) | Mar 13, 2022 |
| Positivo      | N1250                       | [e0ac8b69f1](https://linux-hardware.org/?probe=e0ac8b69f1) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [739b74effe](https://linux-hardware.org/?probe=739b74effe) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Dell          | Latitude 7285               | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6e9075eebf](https://linux-hardware.org/?probe=6e9075eebf) | Mar 13, 2022 |
| Dell          | Latitude 5511               | [ec15afa8e7](https://linux-hardware.org/?probe=ec15afa8e7) | Mar 12, 2022 |
| Dell          | Precision 5540              | [99b2435d7a](https://linux-hardware.org/?probe=99b2435d7a) | Mar 12, 2022 |
| Lenovo        | G780 20138                  | [276b115350](https://linux-hardware.org/?probe=276b115350) | Mar 12, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| Acer          | Aspire 5250                 | [a3f9e83752](https://linux-hardware.org/?probe=a3f9e83752) | Mar 11, 2022 |
| Dell          | Latitude 7480               | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [cbfe261386](https://linux-hardware.org/?probe=cbfe261386) | Mar 11, 2022 |
| HP            | Notebook                    | [de3091d5d4](https://linux-hardware.org/?probe=de3091d5d4) | Mar 11, 2022 |
| Apple         | MacBookPro10,1              | [2a4e580bd6](https://linux-hardware.org/?probe=2a4e580bd6) | Mar 11, 2022 |
| Dell          | G5 5505                     | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [f4a2cbf25a](https://linux-hardware.org/?probe=f4a2cbf25a) | Mar 10, 2022 |
| HP            | ZBook 14u G4                | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | [68e933e6a3](https://linux-hardware.org/?probe=68e933e6a3) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | [f1f2a94be9](https://linux-hardware.org/?probe=f1f2a94be9) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | [fc015f45ba](https://linux-hardware.org/?probe=fc015f45ba) | Mar 10, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [849f4141ce](https://linux-hardware.org/?probe=849f4141ce) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [49503537f5](https://linux-hardware.org/?probe=49503537f5) | Mar 09, 2022 |
| Positivo      | CHT12CP                     | [fa7f40245b](https://linux-hardware.org/?probe=fa7f40245b) | Mar 09, 2022 |
| Acer          | Aspire 4750                 | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [4378396a20](https://linux-hardware.org/?probe=4378396a20) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [02b4ade19f](https://linux-hardware.org/?probe=02b4ade19f) | Mar 08, 2022 |
| Acer          | Aspire A114-32              | [1260b41068](https://linux-hardware.org/?probe=1260b41068) | Mar 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| Dell          | Inspiron 5458               | [16f5e2d856](https://linux-hardware.org/?probe=16f5e2d856) | Mar 08, 2022 |
| Apple         | MacBookPro11,4              | [f3eb9f941a](https://linux-hardware.org/?probe=f3eb9f941a) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [2b8b852d07](https://linux-hardware.org/?probe=2b8b852d07) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| ASUSTek       | X550LC                      | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | G40-80 80JE                 | [2bf4890b1b](https://linux-hardware.org/?probe=2bf4890b1b) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e14e313311](https://linux-hardware.org/?probe=e14e313311) | Mar 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [856cb873fc](https://linux-hardware.org/?probe=856cb873fc) | Mar 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [fc4d2904c3](https://linux-hardware.org/?probe=fc4d2904c3) | Mar 06, 2022 |
| Acer          | Aspire E1-522               | [1d4f09c200](https://linux-hardware.org/?probe=1d4f09c200) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| HP            | ProBook 430 G5              | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [134d1cf65b](https://linux-hardware.org/?probe=134d1cf65b) | Mar 03, 2022 |
| Medion        | Akoya P6638                 | [102c7910e5](https://linux-hardware.org/?probe=102c7910e5) | Mar 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c5bf02a4d7](https://linux-hardware.org/?probe=c5bf02a4d7) | Mar 03, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [35507d8b67](https://linux-hardware.org/?probe=35507d8b67) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | [89e589ec6b](https://linux-hardware.org/?probe=89e589ec6b) | Mar 02, 2022 |
| Dell          | Latitude 5411               | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | G40-80 80JE                 | [476396ef7c](https://linux-hardware.org/?probe=476396ef7c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| System76      | Oryx Pro                    | [7c9f5c83cf](https://linux-hardware.org/?probe=7c9f5c83cf) | Mar 01, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f61c04b0a8](https://linux-hardware.org/?probe=f61c04b0a8) | Mar 01, 2022 |
| Dell          | Latitude 7285               | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| HP            | EliteBook 840 G3            | [9ffc6b43ec](https://linux-hardware.org/?probe=9ffc6b43ec) | Feb 28, 2022 |
| Acer          | Aspire E1-522               | [4245cd910a](https://linux-hardware.org/?probe=4245cd910a) | Feb 28, 2022 |
| HP            | Notebook                    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [fa94978a0b](https://linux-hardware.org/?probe=fa94978a0b) | Feb 28, 2022 |
| Apple         | MacBookAir7,2               | [e2bc04b6f4](https://linux-hardware.org/?probe=e2bc04b6f4) | Feb 27, 2022 |
| Apple         | MacBookAir7,2               | [592d42e16c](https://linux-hardware.org/?probe=592d42e16c) | Feb 27, 2022 |
| Lenovo        | G70-70 80HW007LNX           | [a0ba78ccea](https://linux-hardware.org/?probe=a0ba78ccea) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| HP            | Pavilion Notebook           | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | [24861666e2](https://linux-hardware.org/?probe=24861666e2) | Feb 27, 2022 |
| Lenovo        | IdeaPad S540-14IML Touch... | [22bb5f0b44](https://linux-hardware.org/?probe=22bb5f0b44) | Feb 27, 2022 |
| HUAWEI        | KLVL-WXX9                   | [efd62e1ed7](https://linux-hardware.org/?probe=efd62e1ed7) | Feb 26, 2022 |
| Dell          | XPS 13 9305                 | [36aacb1723](https://linux-hardware.org/?probe=36aacb1723) | Feb 26, 2022 |
| HP            | Pavilion g4                 | [0e40990ec2](https://linux-hardware.org/?probe=0e40990ec2) | Feb 26, 2022 |
| HP            | Pavilion 15                 | [463d26d75c](https://linux-hardware.org/?probe=463d26d75c) | Feb 26, 2022 |
| HP            | Pavilion 17                 | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| Acer          | Aspire E5-471               | [194baf83e9](https://linux-hardware.org/?probe=194baf83e9) | Feb 25, 2022 |
| Dell          | Latitude 3350               | [093650ba06](https://linux-hardware.org/?probe=093650ba06) | Feb 25, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [13b7868e73](https://linux-hardware.org/?probe=13b7868e73) | Feb 24, 2022 |
| Dell          | Inspiron 5567               | [0e9130cffe](https://linux-hardware.org/?probe=0e9130cffe) | Feb 24, 2022 |
| Google        | Snappy                      | [cf0b11bd65](https://linux-hardware.org/?probe=cf0b11bd65) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [15df5df598](https://linux-hardware.org/?probe=15df5df598) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| Lenovo        | IdeaPad 3 15IML05 U 81WB    | [73c7d63295](https://linux-hardware.org/?probe=73c7d63295) | Feb 23, 2022 |
| Google        | Edgar                       | [46f5948f03](https://linux-hardware.org/?probe=46f5948f03) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f09566c9ee](https://linux-hardware.org/?probe=f09566c9ee) | Feb 23, 2022 |
| Samsung       | 750XDA                      | [ad6823c08e](https://linux-hardware.org/?probe=ad6823c08e) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| MSI           | GE63VR 7RF                  | [68e1d81309](https://linux-hardware.org/?probe=68e1d81309) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| Dell          | Inspiron 7577               | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ee3ef301c2](https://linux-hardware.org/?probe=ee3ef301c2) | Feb 22, 2022 |
| Jumper        | EZbook                      | [9cded25245](https://linux-hardware.org/?probe=9cded25245) | Feb 22, 2022 |
| Lenovo        | V14-ADA 82C6                | [94c0f0f3a3](https://linux-hardware.org/?probe=94c0f0f3a3) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| HP            | Notebook                    | [d8dd214532](https://linux-hardware.org/?probe=d8dd214532) | Feb 21, 2022 |
| HP            | Laptop 14z-dk100            | [65130b9760](https://linux-hardware.org/?probe=65130b9760) | Feb 21, 2022 |
| eMachines     | E725 V1.03                  | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Acer          | Swift SFX14-41G             | [5eb9d81462](https://linux-hardware.org/?probe=5eb9d81462) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | [388a17923c](https://linux-hardware.org/?probe=388a17923c) | Feb 20, 2022 |
| ASUSTek       | G551JK                      | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [65c44b63d6](https://linux-hardware.org/?probe=65c44b63d6) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [d8c4226f82](https://linux-hardware.org/?probe=d8c4226f82) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| HP            | Notebook                    | [b2bc5693f7](https://linux-hardware.org/?probe=b2bc5693f7) | Feb 20, 2022 |
| Apple         | MacBookAir5,2               | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | [5d973743c8](https://linux-hardware.org/?probe=5d973743c8) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | [c73dc0aa9f](https://linux-hardware.org/?probe=c73dc0aa9f) | Feb 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [1ad67d12e0](https://linux-hardware.org/?probe=1ad67d12e0) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [c2f39e4414](https://linux-hardware.org/?probe=c2f39e4414) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [674256dc2a](https://linux-hardware.org/?probe=674256dc2a) | Feb 19, 2022 |
| HP            | ZBook 17 G4                 | [0ac02f47be](https://linux-hardware.org/?probe=0ac02f47be) | Feb 19, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [f988c3bfdc](https://linux-hardware.org/?probe=f988c3bfdc) | Feb 18, 2022 |
| Acer          | Aspire E5-575G              | [4cbc6b81bf](https://linux-hardware.org/?probe=4cbc6b81bf) | Feb 18, 2022 |
| Avell High... | B.ON                        | [3b3e1a7730](https://linux-hardware.org/?probe=3b3e1a7730) | Feb 18, 2022 |
| Dell          | Latitude E6330              | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| HP            | Dratini                     | [bb3f3445ee](https://linux-hardware.org/?probe=bb3f3445ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [c896752de0](https://linux-hardware.org/?probe=c896752de0) | Feb 17, 2022 |
| Inspire Te... | Trio Windows OD 1.0         | [a0f755c28a](https://linux-hardware.org/?probe=a0f755c28a) | Feb 17, 2022 |
| Avell High... | B.ON                        | [26b25d67d6](https://linux-hardware.org/?probe=26b25d67d6) | Feb 17, 2022 |
| Acer          | Predator G9-793             | [45ec93214f](https://linux-hardware.org/?probe=45ec93214f) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e03bf2b8a8](https://linux-hardware.org/?probe=e03bf2b8a8) | Feb 16, 2022 |
| System76      | Lemur Pro                   | [3a7527d1e3](https://linux-hardware.org/?probe=3a7527d1e3) | Feb 16, 2022 |
| ASUSTek       | T200TAC                     | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [9a9f646438](https://linux-hardware.org/?probe=9a9f646438) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| ASUSTek       | X550WE                      | [beed529fc3](https://linux-hardware.org/?probe=beed529fc3) | Feb 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Dell          | XPS 15 9550                 | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | [e82c11b42e](https://linux-hardware.org/?probe=e82c11b42e) | Feb 13, 2022 |
| Acer          | Aspire A514-54              | [1f5dd04a09](https://linux-hardware.org/?probe=1f5dd04a09) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| PC Special... | NH5xAx                      | [5e0b855dbf](https://linux-hardware.org/?probe=5e0b855dbf) | Feb 13, 2022 |
| Apple         | MacBookAir7,2               | [91fa01f5a6](https://linux-hardware.org/?probe=91fa01f5a6) | Feb 12, 2022 |
| Apple         | MacBookAir7,2               | [dc1249f2a1](https://linux-hardware.org/?probe=dc1249f2a1) | Feb 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [42674c38b2](https://linux-hardware.org/?probe=42674c38b2) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Acer          | Aspire A515-54G             | [f8e7f688a6](https://linux-hardware.org/?probe=f8e7f688a6) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [4c500fd383](https://linux-hardware.org/?probe=4c500fd383) | Feb 11, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [2cfb1f14b9](https://linux-hardware.org/?probe=2cfb1f14b9) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b2d14e7f15](https://linux-hardware.org/?probe=b2d14e7f15) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2661cf0743](https://linux-hardware.org/?probe=2661cf0743) | Feb 10, 2022 |
| Acer          | Nitro AN515-42              | [4906efe7f4](https://linux-hardware.org/?probe=4906efe7f4) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | [83ab33660d](https://linux-hardware.org/?probe=83ab33660d) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | [52bec77385](https://linux-hardware.org/?probe=52bec77385) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | [52d6fa9b66](https://linux-hardware.org/?probe=52d6fa9b66) | Feb 09, 2022 |
| HP            | EliteBook 840 G6            | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [b7e0365760](https://linux-hardware.org/?probe=b7e0365760) | Feb 08, 2022 |
| ASUSTek       | X75VC                       | [55fda8de04](https://linux-hardware.org/?probe=55fda8de04) | Feb 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [b4cfe297d4](https://linux-hardware.org/?probe=b4cfe297d4) | Feb 08, 2022 |
| Lenovo        | ThinkPad X230 23257R2       | [4fa07e0a61](https://linux-hardware.org/?probe=4fa07e0a61) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b400a64d30](https://linux-hardware.org/?probe=b400a64d30) | Feb 07, 2022 |
| Acer          | Aspire E5-575               | [cb02bc65cc](https://linux-hardware.org/?probe=cb02bc65cc) | Feb 07, 2022 |
| HP            | Pavilion dv6                | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5b6802c8e3](https://linux-hardware.org/?probe=5b6802c8e3) | Feb 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [61e4b1c45e](https://linux-hardware.org/?probe=61e4b1c45e) | Feb 06, 2022 |
| Lenovo        | G70-70 80HW007LNX           | [79e8d4895c](https://linux-hardware.org/?probe=79e8d4895c) | Feb 06, 2022 |
| Lenovo        | Ducati 5 82ES               | [3364f4de6b](https://linux-hardware.org/?probe=3364f4de6b) | Feb 06, 2022 |
| HP            | Compaq 6730s                | [8d1fa47bb0](https://linux-hardware.org/?probe=8d1fa47bb0) | Feb 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [73db0d90e9](https://linux-hardware.org/?probe=73db0d90e9) | Feb 06, 2022 |
| ASUSTek       | GL702VSK                    | [d3eb319919](https://linux-hardware.org/?probe=d3eb319919) | Feb 06, 2022 |
| Dell          | Inspiron 5537               | [79e02b1ade](https://linux-hardware.org/?probe=79e02b1ade) | Feb 05, 2022 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [ce23fdbead](https://linux-hardware.org/?probe=ce23fdbead) | Feb 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d457ee5311](https://linux-hardware.org/?probe=d457ee5311) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| HUAWEI        | NBM-WXX9                    | [5256293dec](https://linux-hardware.org/?probe=5256293dec) | Feb 05, 2022 |
| Framework     | Laptop                      | [64e6669cbc](https://linux-hardware.org/?probe=64e6669cbc) | Feb 04, 2022 |
| Dell          | Inspiron 5521               | [8d4968c10a](https://linux-hardware.org/?probe=8d4968c10a) | Feb 04, 2022 |
| Acer          | Aspire A515-43              | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ca238c69a5](https://linux-hardware.org/?probe=ca238c69a5) | Feb 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [862367b523](https://linux-hardware.org/?probe=862367b523) | Feb 03, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| Dell          | XPS 13 9310                 | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d9cc5f0548](https://linux-hardware.org/?probe=d9cc5f0548) | Feb 03, 2022 |
| Dell          | Latitude E6230              | [05d9080c0c](https://linux-hardware.org/?probe=05d9080c0c) | Feb 03, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [2cb72b3867](https://linux-hardware.org/?probe=2cb72b3867) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| Dell          | XPS 13 7390                 | [978273c0aa](https://linux-hardware.org/?probe=978273c0aa) | Feb 02, 2022 |
| Sony          | SVD1121Q2EB                 | [8e484b15d2](https://linux-hardware.org/?probe=8e484b15d2) | Feb 02, 2022 |
| HP            | ProBook 6465b               | [aca95b9f2d](https://linux-hardware.org/?probe=aca95b9f2d) | Feb 01, 2022 |
| Dell          | Vostro 3500                 | [c9cae610a6](https://linux-hardware.org/?probe=c9cae610a6) | Feb 01, 2022 |
| PC Special... | NH5xAx                      | [6c8a746762](https://linux-hardware.org/?probe=6c8a746762) | Feb 01, 2022 |
| Samsung       | RV409/RV509/RV709           | [535f5504f0](https://linux-hardware.org/?probe=535f5504f0) | Feb 01, 2022 |
| Dell          | Precision 5530              | [3bb85a7897](https://linux-hardware.org/?probe=3bb85a7897) | Jan 31, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [b7796bb104](https://linux-hardware.org/?probe=b7796bb104) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [8efcb72970](https://linux-hardware.org/?probe=8efcb72970) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [316ea97198](https://linux-hardware.org/?probe=316ea97198) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ebe757d792](https://linux-hardware.org/?probe=ebe757d792) | Jan 30, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N2000LFR    | [0c7293a8ec](https://linux-hardware.org/?probe=0c7293a8ec) | Jan 30, 2022 |
| Lenovo        | ThinkPad T420 4180F65       | [23a97a1da0](https://linux-hardware.org/?probe=23a97a1da0) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [88eae6cdfb](https://linux-hardware.org/?probe=88eae6cdfb) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [d8040d8fc4](https://linux-hardware.org/?probe=d8040d8fc4) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [209156e57d](https://linux-hardware.org/?probe=209156e57d) | Jan 29, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [2f9a17c907](https://linux-hardware.org/?probe=2f9a17c907) | Jan 29, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | [2440be23b6](https://linux-hardware.org/?probe=2440be23b6) | Jan 29, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4a98af8b6c](https://linux-hardware.org/?probe=4a98af8b6c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| Dell          | Latitude 5511               | [94f621a74b](https://linux-hardware.org/?probe=94f621a74b) | Jan 29, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c573633ba7](https://linux-hardware.org/?probe=c573633ba7) | Jan 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [bab2021d07](https://linux-hardware.org/?probe=bab2021d07) | Jan 28, 2022 |
| ASUSTek       | X510UNR                     | [64f7ad2ba1](https://linux-hardware.org/?probe=64f7ad2ba1) | Jan 27, 2022 |
| Toshiba       | Satellite C660              | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Mediacom      | GTZS                        | [10a0d977b0](https://linux-hardware.org/?probe=10a0d977b0) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b930fcaa84](https://linux-hardware.org/?probe=b930fcaa84) | Jan 26, 2022 |
| Dell          | XPS 13 7390                 | [95d6e59e28](https://linux-hardware.org/?probe=95d6e59e28) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [738074142b](https://linux-hardware.org/?probe=738074142b) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1bd39d2b68](https://linux-hardware.org/?probe=1bd39d2b68) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [9613005856](https://linux-hardware.org/?probe=9613005856) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | [e9f06efa7a](https://linux-hardware.org/?probe=e9f06efa7a) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [041c78217d](https://linux-hardware.org/?probe=041c78217d) | Jan 26, 2022 |
| Dell          | Precision 5510              | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Dell          | Latitude E7470              | [c47b0efb73](https://linux-hardware.org/?probe=c47b0efb73) | Jan 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [5846d2031f](https://linux-hardware.org/?probe=5846d2031f) | Jan 25, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c7fbcbcd07](https://linux-hardware.org/?probe=c7fbcbcd07) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Acer          | Nitro AN515-45              | [34568da477](https://linux-hardware.org/?probe=34568da477) | Jan 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [d6ea0ad749](https://linux-hardware.org/?probe=d6ea0ad749) | Jan 23, 2022 |
| SCHNEIDER     | SCL141CTP                   | [ff14e3fa97](https://linux-hardware.org/?probe=ff14e3fa97) | Jan 23, 2022 |
| HP            | ProBook 470 G5              | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | Inspiron N5110              | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [427ce82d40](https://linux-hardware.org/?probe=427ce82d40) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [2c0f007811](https://linux-hardware.org/?probe=2c0f007811) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [636e98e6e5](https://linux-hardware.org/?probe=636e98e6e5) | Jan 21, 2022 |
| Dell          | XPS 13 9350                 | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| Dell          | Latitude E6530              | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [c63c055197](https://linux-hardware.org/?probe=c63c055197) | Jan 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | [172a8a48ad](https://linux-hardware.org/?probe=172a8a48ad) | Jan 21, 2022 |
| Acer          | Aspire A315-41G             | [03a8c77758](https://linux-hardware.org/?probe=03a8c77758) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | [df698a1427](https://linux-hardware.org/?probe=df698a1427) | Jan 20, 2022 |
| Lenovo        | B490 37722QP                | [6b32b6b8ef](https://linux-hardware.org/?probe=6b32b6b8ef) | Jan 20, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [0ae4377d83](https://linux-hardware.org/?probe=0ae4377d83) | Jan 19, 2022 |
| Acer          | Aspire E5-573G              | [30829ce42e](https://linux-hardware.org/?probe=30829ce42e) | Jan 19, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [1a128aada0](https://linux-hardware.org/?probe=1a128aada0) | Jan 19, 2022 |
| Positivo      | H14BU08                     | [8fb0d7e730](https://linux-hardware.org/?probe=8fb0d7e730) | Jan 19, 2022 |
| Acer          | Swift SF314-42              | [a2e70fe7b1](https://linux-hardware.org/?probe=a2e70fe7b1) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | [533f74b810](https://linux-hardware.org/?probe=533f74b810) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [2407b5f5bb](https://linux-hardware.org/?probe=2407b5f5bb) | Jan 19, 2022 |
| Dell          | Latitude E6530              | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| Lenovo        | B490 37722QP                | [3113fb2078](https://linux-hardware.org/?probe=3113fb2078) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | [a168ef0aa5](https://linux-hardware.org/?probe=a168ef0aa5) | Jan 18, 2022 |
| Acer          | Predator PH315-51           | [d6edc6139f](https://linux-hardware.org/?probe=d6edc6139f) | Jan 17, 2022 |
| Jumper        | EZbook                      | [6c949f1929](https://linux-hardware.org/?probe=6c949f1929) | Jan 17, 2022 |
| HP            | ProBook 650 G1              | [8d78cc6770](https://linux-hardware.org/?probe=8d78cc6770) | Jan 16, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Acer          | Swift SF114-34              | [2098bc3881](https://linux-hardware.org/?probe=2098bc3881) | Jan 16, 2022 |
| HP            | ProBook 650 G1              | [829a2b8221](https://linux-hardware.org/?probe=829a2b8221) | Jan 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [779202413e](https://linux-hardware.org/?probe=779202413e) | Jan 15, 2022 |
| Dell          | Latitude 5480               | [6e363cb43c](https://linux-hardware.org/?probe=6e363cb43c) | Jan 15, 2022 |
| HP            | 15                          | [65d1bd3651](https://linux-hardware.org/?probe=65d1bd3651) | Jan 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [350fb6b638](https://linux-hardware.org/?probe=350fb6b638) | Jan 14, 2022 |
| Dell          | XPS 13 9310                 | [f695de13bf](https://linux-hardware.org/?probe=f695de13bf) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Apple         | MacBookPro11,3              | [0fbef723d5](https://linux-hardware.org/?probe=0fbef723d5) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS2CH0... | [7f440733c2](https://linux-hardware.org/?probe=7f440733c2) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [e9f23e9f5f](https://linux-hardware.org/?probe=e9f23e9f5f) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [85d81f357a](https://linux-hardware.org/?probe=85d81f357a) | Jan 13, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | [41f9777fcf](https://linux-hardware.org/?probe=41f9777fcf) | Jan 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [45d63385d2](https://linux-hardware.org/?probe=45d63385d2) | Jan 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| Dell          | XPS 13 7390                 | [10dea3ac81](https://linux-hardware.org/?probe=10dea3ac81) | Jan 11, 2022 |
| Lenovo        | IdeaPad Y470 20090          | [29ff376953](https://linux-hardware.org/?probe=29ff376953) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [34bf588c0b](https://linux-hardware.org/?probe=34bf588c0b) | Jan 11, 2022 |
| Dell          | Venue 10 Pro 5055           | [22d084e747](https://linux-hardware.org/?probe=22d084e747) | Jan 11, 2022 |
| HP            | EliteBook 820 G1            | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Lenovo        | ThinkPad T530 239265U       | [5aba32fde1](https://linux-hardware.org/?probe=5aba32fde1) | Jan 11, 2022 |
| Toshiba       | Satellite L855              | [5668d7e463](https://linux-hardware.org/?probe=5668d7e463) | Jan 10, 2022 |
| Toshiba       | Satellite L855              | [f14ba2d184](https://linux-hardware.org/?probe=f14ba2d184) | Jan 10, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [b6b9155c53](https://linux-hardware.org/?probe=b6b9155c53) | Jan 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [72db511d09](https://linux-hardware.org/?probe=72db511d09) | Jan 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [6b6c84515a](https://linux-hardware.org/?probe=6b6c84515a) | Jan 09, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [b9812a839e](https://linux-hardware.org/?probe=b9812a839e) | Jan 09, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| Dell          | XPS 13 9310                 | [e0dfa537f4](https://linux-hardware.org/?probe=e0dfa537f4) | Jan 08, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Dell          | Precision 3551              | [73d2d759ba](https://linux-hardware.org/?probe=73d2d759ba) | Jan 07, 2022 |
| Dell          | XPS 13 9310                 | [aa1ce4d9ca](https://linux-hardware.org/?probe=aa1ce4d9ca) | Jan 07, 2022 |
| Dell          | Precision 5510              | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| Toshiba       | Satellite L755              | [df6cc34c45](https://linux-hardware.org/?probe=df6cc34c45) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [a37ac164fb](https://linux-hardware.org/?probe=a37ac164fb) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [51930e8d89](https://linux-hardware.org/?probe=51930e8d89) | Jan 06, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6c5e2e7851](https://linux-hardware.org/?probe=6c5e2e7851) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cafe68988e](https://linux-hardware.org/?probe=cafe68988e) | Jan 06, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [8d8227634a](https://linux-hardware.org/?probe=8d8227634a) | Jan 06, 2022 |
| Panasonic     | CF-195FYCALM                | [19ad0002e5](https://linux-hardware.org/?probe=19ad0002e5) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| Samsung       | 550XDA                      | [1bdf544285](https://linux-hardware.org/?probe=1bdf544285) | Jan 05, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [270443c029](https://linux-hardware.org/?probe=270443c029) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [b97121f86e](https://linux-hardware.org/?probe=b97121f86e) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [9fa953475a](https://linux-hardware.org/?probe=9fa953475a) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8d492fa1d4](https://linux-hardware.org/?probe=8d492fa1d4) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [56a85d54e4](https://linux-hardware.org/?probe=56a85d54e4) | Jan 04, 2022 |
| Dell          | Latitude E5550              | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| Acer          | Swift SF114-34              | [3d15bf4d48](https://linux-hardware.org/?probe=3d15bf4d48) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [c3587d4c57](https://linux-hardware.org/?probe=c3587d4c57) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [0a39d6fe8c](https://linux-hardware.org/?probe=0a39d6fe8c) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| Dell          | Inspiron 7591               | [4044cf11d2](https://linux-hardware.org/?probe=4044cf11d2) | Jan 04, 2022 |
| Dell          | Inspiron 5402               | [3cae008c9d](https://linux-hardware.org/?probe=3cae008c9d) | Jan 04, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [d5e7352413](https://linux-hardware.org/?probe=d5e7352413) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [8cd52a2f8f](https://linux-hardware.org/?probe=8cd52a2f8f) | Jan 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3953d7ae46](https://linux-hardware.org/?probe=3953d7ae46) | Jan 03, 2022 |
| Dell          | XPS 15 7590                 | [b661a2cdf0](https://linux-hardware.org/?probe=b661a2cdf0) | Jan 03, 2022 |
| ASUSTek       | X542URR                     | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [0692c6e121](https://linux-hardware.org/?probe=0692c6e121) | Jan 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Dell          | Latitude E5570              | [34af93663b](https://linux-hardware.org/?probe=34af93663b) | Dec 31, 2021 |
| Google        | Coral                       | [23a0352176](https://linux-hardware.org/?probe=23a0352176) | Dec 31, 2021 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Dell          | XPS 13 9380                 | [cd66e486be](https://linux-hardware.org/?probe=cd66e486be) | Dec 31, 2021 |
| Apple         | MacBookPro8,2               | [298d5a0323](https://linux-hardware.org/?probe=298d5a0323) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [c6dbec8e70](https://linux-hardware.org/?probe=c6dbec8e70) | Dec 31, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [c1eeaec01b](https://linux-hardware.org/?probe=c1eeaec01b) | Dec 30, 2021 |
| Google        | Chell                       | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [bfd79da0e0](https://linux-hardware.org/?probe=bfd79da0e0) | Dec 30, 2021 |
| Dell          | Inspiron 3521               | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [c539559392](https://linux-hardware.org/?probe=c539559392) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [9ba0058839](https://linux-hardware.org/?probe=9ba0058839) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [dbcf70aced](https://linux-hardware.org/?probe=dbcf70aced) | Dec 29, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [41b463b6c4](https://linux-hardware.org/?probe=41b463b6c4) | Dec 28, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [433a512192](https://linux-hardware.org/?probe=433a512192) | Dec 28, 2021 |
| Lenovo        | ThinkPad E480 20KN001QPB    | [0615d7a112](https://linux-hardware.org/?probe=0615d7a112) | Dec 28, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [bea75ed7d5](https://linux-hardware.org/?probe=bea75ed7d5) | Dec 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Toshiba       | Satellite L12-C-104         | [fae8f8e1f9](https://linux-hardware.org/?probe=fae8f8e1f9) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | [f255947b6f](https://linux-hardware.org/?probe=f255947b6f) | Dec 27, 2021 |
| Dell          | XPS 13 7390                 | [572bbe8d7b](https://linux-hardware.org/?probe=572bbe8d7b) | Dec 27, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86651ee07a](https://linux-hardware.org/?probe=86651ee07a) | Dec 26, 2021 |
| Lenovo        | Ducati 5 82ES               | [61dd257cc7](https://linux-hardware.org/?probe=61dd257cc7) | Dec 26, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [56c0a83ab8](https://linux-hardware.org/?probe=56c0a83ab8) | Dec 26, 2021 |
| MSI           | Alpha 15 B5EEK              | [e076af5bf8](https://linux-hardware.org/?probe=e076af5bf8) | Dec 26, 2021 |
| HP            | 2000                        | [e3408eb743](https://linux-hardware.org/?probe=e3408eb743) | Dec 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1e8ce2ec6d](https://linux-hardware.org/?probe=1e8ce2ec6d) | Dec 25, 2021 |
| Dell          | Inspiron 5558               | [58e49e7f72](https://linux-hardware.org/?probe=58e49e7f72) | Dec 25, 2021 |
| Dell          | Latitude 7410               | [71a96bfc8f](https://linux-hardware.org/?probe=71a96bfc8f) | Dec 25, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe369b6b7](https://linux-hardware.org/?probe=6fe369b6b7) | Dec 25, 2021 |
| Cube          | i18-L                       | [6770cf2a44](https://linux-hardware.org/?probe=6770cf2a44) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [44dd4eee41](https://linux-hardware.org/?probe=44dd4eee41) | Dec 24, 2021 |
| HP            | Laptop 14-dk1xxx            | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| LDLC          | Mercure MH                  | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [abba53c091](https://linux-hardware.org/?probe=abba53c091) | Dec 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1962ddfdb4](https://linux-hardware.org/?probe=1962ddfdb4) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| HP            | 250 G1                      | [da8e31b740](https://linux-hardware.org/?probe=da8e31b740) | Dec 23, 2021 |
| Dell          | Inspiron 5447               | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| Apple         | MacBookPro11,3              | [1975ee2fc0](https://linux-hardware.org/?probe=1975ee2fc0) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7fc27f5255](https://linux-hardware.org/?probe=7fc27f5255) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| HP            | Pavilion 15                 | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ddb3571ec6](https://linux-hardware.org/?probe=ddb3571ec6) | Dec 20, 2021 |
| HUAWEI        | HVY-WXX9                    | [d335e16395](https://linux-hardware.org/?probe=d335e16395) | Dec 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [9c38b95aa0](https://linux-hardware.org/?probe=9c38b95aa0) | Dec 19, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [e380536aac](https://linux-hardware.org/?probe=e380536aac) | Dec 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [87399b5e8b](https://linux-hardware.org/?probe=87399b5e8b) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [85e3feaeba](https://linux-hardware.org/?probe=85e3feaeba) | Dec 19, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [cda7a2c35c](https://linux-hardware.org/?probe=cda7a2c35c) | Dec 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [6bf6c57117](https://linux-hardware.org/?probe=6bf6c57117) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e985e04d6d](https://linux-hardware.org/?probe=e985e04d6d) | Dec 17, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [6deb57beb2](https://linux-hardware.org/?probe=6deb57beb2) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| AVITA         | NS14A1US                    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [aba6548652](https://linux-hardware.org/?probe=aba6548652) | Dec 16, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [30a4a58c5d](https://linux-hardware.org/?probe=30a4a58c5d) | Dec 16, 2021 |
| Dell          | XPS 15 9500                 | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [ff779fe08f](https://linux-hardware.org/?probe=ff779fe08f) | Dec 16, 2021 |
| MSI           | GL63 9SC                    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | Pavilion dv7                | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Dell          | Latitude 5500               | [5b9479065e](https://linux-hardware.org/?probe=5b9479065e) | Dec 15, 2021 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [3edd54970c](https://linux-hardware.org/?probe=3edd54970c) | Dec 15, 2021 |
| ASUSTek       | K43U                        | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| Acer          | Swift SF314-43              | [2cabe8184b](https://linux-hardware.org/?probe=2cabe8184b) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4290797f32](https://linux-hardware.org/?probe=4290797f32) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [fb79be9e00](https://linux-hardware.org/?probe=fb79be9e00) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Dell          | Latitude 7300               | [23f38f8a7d](https://linux-hardware.org/?probe=23f38f8a7d) | Dec 14, 2021 |
| Acer          | Aspire A515-55              | [8d121836c9](https://linux-hardware.org/?probe=8d121836c9) | Dec 14, 2021 |
| Dell          | Latitude 7490               | [ae8a45bc5a](https://linux-hardware.org/?probe=ae8a45bc5a) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Acer          | Swift SF314-43              | [fd53be96e6](https://linux-hardware.org/?probe=fd53be96e6) | Dec 13, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| MSI           | Modern 14 B5M               | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Acer          | Aspire A315-31              | [24c8e29d95](https://linux-hardware.org/?probe=24c8e29d95) | Dec 12, 2021 |
| Dell          | Latitude 7290               | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1H60... | [ffb1c97626](https://linux-hardware.org/?probe=ffb1c97626) | Dec 12, 2021 |
| Dell          | Inspiron 5515               | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [54058ac7e2](https://linux-hardware.org/?probe=54058ac7e2) | Dec 11, 2021 |
| HP            | Pavilion Power Laptop 15... | [6d5c35bf9f](https://linux-hardware.org/?probe=6d5c35bf9f) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [584be17bec](https://linux-hardware.org/?probe=584be17bec) | Dec 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4fba952635](https://linux-hardware.org/?probe=4fba952635) | Dec 11, 2021 |
| HP            | ZBook 15 G2                 | [d7faa88624](https://linux-hardware.org/?probe=d7faa88624) | Dec 11, 2021 |
| Dell          | Latitude 7300               | [2bb3c232b6](https://linux-hardware.org/?probe=2bb3c232b6) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| Dell          | Inspiron 13 5310            | [7a721d2c05](https://linux-hardware.org/?probe=7a721d2c05) | Dec 10, 2021 |
| Dell          | Vostro 3400                 | [bcb885e52b](https://linux-hardware.org/?probe=bcb885e52b) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [4fe4d7393e](https://linux-hardware.org/?probe=4fe4d7393e) | Dec 10, 2021 |
| Acer          | Swift SFX14-41G             | [a81ed5c974](https://linux-hardware.org/?probe=a81ed5c974) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [4ba265c070](https://linux-hardware.org/?probe=4ba265c070) | Dec 10, 2021 |
| Lenovo        | G570 20079                  | [439a97ec9b](https://linux-hardware.org/?probe=439a97ec9b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [195283a93a](https://linux-hardware.org/?probe=195283a93a) | Dec 09, 2021 |
| Dell          | XPS 13 9305                 | [60e57ae6dd](https://linux-hardware.org/?probe=60e57ae6dd) | Dec 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [73645a62d6](https://linux-hardware.org/?probe=73645a62d6) | Dec 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [3880c485fb](https://linux-hardware.org/?probe=3880c485fb) | Dec 08, 2021 |
| Apple         | MacBookPro12,1              | [fcfdb2cedc](https://linux-hardware.org/?probe=fcfdb2cedc) | Dec 08, 2021 |
| Sony          | SVE1711Z1RB                 | [adb25167ea](https://linux-hardware.org/?probe=adb25167ea) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| HP            | 15 Notebook PC              | [0523a58e8a](https://linux-hardware.org/?probe=0523a58e8a) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Lenovo        | G570 20079                  | [a6722f2ff3](https://linux-hardware.org/?probe=a6722f2ff3) | Dec 07, 2021 |
| Sony          | SVE1713S1RW                 | [41775b7503](https://linux-hardware.org/?probe=41775b7503) | Dec 07, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [b5a282abf6](https://linux-hardware.org/?probe=b5a282abf6) | Dec 06, 2021 |
| Apple         | MacBookPro9,2               | [4fc7bc5515](https://linux-hardware.org/?probe=4fc7bc5515) | Dec 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [42fe75c227](https://linux-hardware.org/?probe=42fe75c227) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e18de7567f](https://linux-hardware.org/?probe=e18de7567f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [40640fd92f](https://linux-hardware.org/?probe=40640fd92f) | Dec 06, 2021 |
| Framework     | Laptop                      | [64dc54fbc6](https://linux-hardware.org/?probe=64dc54fbc6) | Dec 06, 2021 |
| Acer          | Nitro AN515-45              | [8641f9b078](https://linux-hardware.org/?probe=8641f9b078) | Dec 05, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [50d1714228](https://linux-hardware.org/?probe=50d1714228) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Dell          | Inspiron 5405               | [91806303e6](https://linux-hardware.org/?probe=91806303e6) | Dec 05, 2021 |
| Dell          | Latitude E6530              | [de5ad42b2f](https://linux-hardware.org/?probe=de5ad42b2f) | Dec 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [15e8e28073](https://linux-hardware.org/?probe=15e8e28073) | Dec 04, 2021 |
| Acer          | Aspire E5-571G              | [b006a547c8](https://linux-hardware.org/?probe=b006a547c8) | Dec 04, 2021 |
| HP            | ProBook 470 G5              | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [be3c6c3e84](https://linux-hardware.org/?probe=be3c6c3e84) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [23d42021b2](https://linux-hardware.org/?probe=23d42021b2) | Dec 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f90f047538](https://linux-hardware.org/?probe=f90f047538) | Dec 03, 2021 |
| Toshiba       | Satellite C70-A-K2W         | [8e46f67032](https://linux-hardware.org/?probe=8e46f67032) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [775ec45ab8](https://linux-hardware.org/?probe=775ec45ab8) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [b783f0a79d](https://linux-hardware.org/?probe=b783f0a79d) | Dec 03, 2021 |
| Gigabyte      | AERO 15 KB                  | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| Lenovo        | V15-ADA 82C7                | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Lenovo        | ThinkPad L390 20NSS43600    | [e9aae12812](https://linux-hardware.org/?probe=e9aae12812) | Dec 02, 2021 |
| Acer          | Nitro AN515-55              | [d5c6c6edee](https://linux-hardware.org/?probe=d5c6c6edee) | Dec 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | [94b9d8b093](https://linux-hardware.org/?probe=94b9d8b093) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [240ca54dfb](https://linux-hardware.org/?probe=240ca54dfb) | Dec 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8cebf41624](https://linux-hardware.org/?probe=8cebf41624) | Dec 01, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9b11575394](https://linux-hardware.org/?probe=9b11575394) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [610709bb66](https://linux-hardware.org/?probe=610709bb66) | Nov 30, 2021 |
| Acer          | Aspire E5-571G              | [f940ae414d](https://linux-hardware.org/?probe=f940ae414d) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b2d55bd445](https://linux-hardware.org/?probe=b2d55bd445) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [23ae32af07](https://linux-hardware.org/?probe=23ae32af07) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [074ec973ae](https://linux-hardware.org/?probe=074ec973ae) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [80bbba47f6](https://linux-hardware.org/?probe=80bbba47f6) | Nov 29, 2021 |
| Acer          | Aspire E5-571G              | [95cb3fe8b3](https://linux-hardware.org/?probe=95cb3fe8b3) | Nov 29, 2021 |
| Acer          | Predator G9-793             | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Dell          | G5 5590                     | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Notebook      | NB50TL                      | [15a716161c](https://linux-hardware.org/?probe=15a716161c) | Nov 28, 2021 |
| Dell          | Inspiron 5558               | [b003366a2c](https://linux-hardware.org/?probe=b003366a2c) | Nov 28, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [8e5c4cc27b](https://linux-hardware.org/?probe=8e5c4cc27b) | Nov 28, 2021 |
| Apple         | MacBookPro7,1               | [6a4ed949e9](https://linux-hardware.org/?probe=6a4ed949e9) | Nov 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [0852350348](https://linux-hardware.org/?probe=0852350348) | Nov 28, 2021 |
| Dell          | Latitude 7420               | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| HP            | Laptop 15s-fq2xxx           | [d559f82ee3](https://linux-hardware.org/?probe=d559f82ee3) | Nov 28, 2021 |
| Dell          | XPS 13 7390                 | [783b49e383](https://linux-hardware.org/?probe=783b49e383) | Nov 28, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [67f32be00d](https://linux-hardware.org/?probe=67f32be00d) | Nov 27, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [968f938b4e](https://linux-hardware.org/?probe=968f938b4e) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | [ef8336f76a](https://linux-hardware.org/?probe=ef8336f76a) | Nov 26, 2021 |
| Dell          | Precision 5550              | [41caa6a4a0](https://linux-hardware.org/?probe=41caa6a4a0) | Nov 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| ASUSTek       | K54C                        | [2604de426e](https://linux-hardware.org/?probe=2604de426e) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [3fe9bcf889](https://linux-hardware.org/?probe=3fe9bcf889) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [406001fc85](https://linux-hardware.org/?probe=406001fc85) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c207f61d91](https://linux-hardware.org/?probe=c207f61d91) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [96c90ad6c9](https://linux-hardware.org/?probe=96c90ad6c9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [039dbf659a](https://linux-hardware.org/?probe=039dbf659a) | Nov 26, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [a000027ce6](https://linux-hardware.org/?probe=a000027ce6) | Nov 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [366fe373c9](https://linux-hardware.org/?probe=366fe373c9) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [beff046f56](https://linux-hardware.org/?probe=beff046f56) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [2a96a2a7af](https://linux-hardware.org/?probe=2a96a2a7af) | Nov 25, 2021 |
| Sony          | VPCF131FM                   | [f0ba5e0db2](https://linux-hardware.org/?probe=f0ba5e0db2) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| Dell          | XPS 13 9300                 | [a91462bd5a](https://linux-hardware.org/?probe=a91462bd5a) | Nov 24, 2021 |
| HP            | EliteBook 735 G5            | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [44bf6f6d6f](https://linux-hardware.org/?probe=44bf6f6d6f) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3c3fbf498a](https://linux-hardware.org/?probe=3c3fbf498a) | Nov 23, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [5be975dd37](https://linux-hardware.org/?probe=5be975dd37) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| Acer          | Nitro AN515-54              | [b58b567113](https://linux-hardware.org/?probe=b58b567113) | Nov 22, 2021 |
| Apple         | MacBookPro11,4              | [7b9225653f](https://linux-hardware.org/?probe=7b9225653f) | Nov 22, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [365b3888e6](https://linux-hardware.org/?probe=365b3888e6) | Nov 22, 2021 |
| Fujitsu       | LIFEBOOK U747               | [ece0600e5d](https://linux-hardware.org/?probe=ece0600e5d) | Nov 22, 2021 |
| Apple         | MacBookPro7,1               | [c686d7d85c](https://linux-hardware.org/?probe=c686d7d85c) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [f779165258](https://linux-hardware.org/?probe=f779165258) | Nov 21, 2021 |
| Dell          | Latitude E5570              | [8cf8db7a89](https://linux-hardware.org/?probe=8cf8db7a89) | Nov 21, 2021 |
| Google        | Relm                        | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| HP            | Pavilion 17                 | [2d69072cdf](https://linux-hardware.org/?probe=2d69072cdf) | Nov 20, 2021 |
| Dell          | Latitude 5490               | [cbe23836bf](https://linux-hardware.org/?probe=cbe23836bf) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| Acer          | Swift SF514-51              | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [a524ba65b5](https://linux-hardware.org/?probe=a524ba65b5) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7e7b7d381e](https://linux-hardware.org/?probe=7e7b7d381e) | Nov 19, 2021 |
| Dell          | Inspiron 3593               | [0e670dc090](https://linux-hardware.org/?probe=0e670dc090) | Nov 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d7a5775f61](https://linux-hardware.org/?probe=d7a5775f61) | Nov 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [01a15306b9](https://linux-hardware.org/?probe=01a15306b9) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| ASUSTek       | X750JN                      | [bb6f44b058](https://linux-hardware.org/?probe=bb6f44b058) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f5a721bf24](https://linux-hardware.org/?probe=f5a721bf24) | Nov 19, 2021 |
| Dell          | Precision 5510              | [1d46cced08](https://linux-hardware.org/?probe=1d46cced08) | Nov 19, 2021 |
| HP            | Laptop 14s-fq0xxx           | [f9b7bdfef8](https://linux-hardware.org/?probe=f9b7bdfef8) | Nov 19, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [dc150f9fba](https://linux-hardware.org/?probe=dc150f9fba) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| HP            | Pavilion Notebook           | [01f7a4c33d](https://linux-hardware.org/?probe=01f7a4c33d) | Nov 18, 2021 |
| Acer          | Swift SF314-42              | [05020e1e61](https://linux-hardware.org/?probe=05020e1e61) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [427ee1a6de](https://linux-hardware.org/?probe=427ee1a6de) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Dell          | Latitude E7270              | [70a4c30534](https://linux-hardware.org/?probe=70a4c30534) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [02c2ed5954](https://linux-hardware.org/?probe=02c2ed5954) | Nov 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [c4763ca2a5](https://linux-hardware.org/?probe=c4763ca2a5) | Nov 16, 2021 |
| Acer          | Swift SF314-43              | [db85b885ae](https://linux-hardware.org/?probe=db85b885ae) | Nov 16, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b1f5ce8b7](https://linux-hardware.org/?probe=6b1f5ce8b7) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Toshiba       | Satellite C855-12R          | [ccf125eb47](https://linux-hardware.org/?probe=ccf125eb47) | Nov 16, 2021 |
| MSI           | Modern 15 A11M              | [6398858488](https://linux-hardware.org/?probe=6398858488) | Nov 16, 2021 |
| Notebook      | NH55RGQ                     | [b3cb30c28d](https://linux-hardware.org/?probe=b3cb30c28d) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [1119a0805e](https://linux-hardware.org/?probe=1119a0805e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| Apple         | MacBookPro6,2               | [75e80e1ea8](https://linux-hardware.org/?probe=75e80e1ea8) | Nov 15, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [06f896ff98](https://linux-hardware.org/?probe=06f896ff98) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [516e448510](https://linux-hardware.org/?probe=516e448510) | Nov 14, 2021 |
| MSI           | Modern 15 A11M              | [8b02ecc2b6](https://linux-hardware.org/?probe=8b02ecc2b6) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [70b84217bd](https://linux-hardware.org/?probe=70b84217bd) | Nov 14, 2021 |
| Dell          | Precision 3541              | [a21fd45ac3](https://linux-hardware.org/?probe=a21fd45ac3) | Nov 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [54bb479f64](https://linux-hardware.org/?probe=54bb479f64) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [d88aea84ef](https://linux-hardware.org/?probe=d88aea84ef) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| Apple         | MacBookPro6,2               | [a778aba19c](https://linux-hardware.org/?probe=a778aba19c) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| Dell          | Latitude 5511               | [dc7c10f4e2](https://linux-hardware.org/?probe=dc7c10f4e2) | Nov 13, 2021 |
| Dell          | Latitude 5511               | [b0ca679bc5](https://linux-hardware.org/?probe=b0ca679bc5) | Nov 13, 2021 |
| HP            | ProBook 430 G1              | [68633b9bf5](https://linux-hardware.org/?probe=68633b9bf5) | Nov 13, 2021 |
| MSI           | Delta 15 A5EFK              | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [9e8eab1073](https://linux-hardware.org/?probe=9e8eab1073) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 14-3467            | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| Apple         | MacBookPro10,2              | [5cbec68d6e](https://linux-hardware.org/?probe=5cbec68d6e) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| Acer          | Swift SFX14-41G             | [04e988d138](https://linux-hardware.org/?probe=04e988d138) | Nov 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Dell          | Precision 5510              | [80bbc48bce](https://linux-hardware.org/?probe=80bbc48bce) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| System76      | Oryx Pro                    | [77cf902290](https://linux-hardware.org/?probe=77cf902290) | Nov 11, 2021 |
| Apple         | MacBookPro9,2               | [61afe68685](https://linux-hardware.org/?probe=61afe68685) | Nov 11, 2021 |
| Dell          | Latitude E7440              | [e907f0bbf1](https://linux-hardware.org/?probe=e907f0bbf1) | Nov 11, 2021 |
| ASUSTek       | X202EV                      | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ac9d7f968f](https://linux-hardware.org/?probe=ac9d7f968f) | Nov 10, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | T102HA                      | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| HP            | ProBook 430 G1              | [99ece77400](https://linux-hardware.org/?probe=99ece77400) | Nov 10, 2021 |
| HUAWEI        | KPL-W0X                     | [807e59f1e3](https://linux-hardware.org/?probe=807e59f1e3) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c8fb558bb7](https://linux-hardware.org/?probe=c8fb558bb7) | Nov 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [81605538eb](https://linux-hardware.org/?probe=81605538eb) | Nov 09, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| HUAWEI        | HLYL-WXX9                   | [1c63b3b4ce](https://linux-hardware.org/?probe=1c63b3b4ce) | Nov 09, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [cb4e2271c0](https://linux-hardware.org/?probe=cb4e2271c0) | Nov 09, 2021 |
| Toshiba       | NB255                       | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| HP            | Notebook                    | [e254c5c947](https://linux-hardware.org/?probe=e254c5c947) | Nov 08, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | [5f5424fe84](https://linux-hardware.org/?probe=5f5424fe84) | Nov 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005GMH    | [146b572cd0](https://linux-hardware.org/?probe=146b572cd0) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | [8988b7e735](https://linux-hardware.org/?probe=8988b7e735) | Nov 08, 2021 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [b996ce8823](https://linux-hardware.org/?probe=b996ce8823) | Nov 07, 2021 |
| Lenovo        | Ducati 5 82ES               | [6269149643](https://linux-hardware.org/?probe=6269149643) | Nov 07, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [b4d29007be](https://linux-hardware.org/?probe=b4d29007be) | Nov 07, 2021 |
| Dell          | Latitude E7440              | [b2560457a5](https://linux-hardware.org/?probe=b2560457a5) | Nov 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [af116b7c35](https://linux-hardware.org/?probe=af116b7c35) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ced169a0b1](https://linux-hardware.org/?probe=ced169a0b1) | Nov 06, 2021 |
| Apple         | MacBookPro6,2               | [bde89fd503](https://linux-hardware.org/?probe=bde89fd503) | Nov 06, 2021 |
| HP            | ProBook 455 G1              | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| HP            | 250 G1                      | [1c52b861c7](https://linux-hardware.org/?probe=1c52b861c7) | Nov 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001XIX     | [98d8c0fbdb](https://linux-hardware.org/?probe=98d8c0fbdb) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Notebook      | W65_W67RZ                   | [153b2a920d](https://linux-hardware.org/?probe=153b2a920d) | Nov 05, 2021 |
| HONOR         | NBD-WXX9                    | [1030fbbff6](https://linux-hardware.org/?probe=1030fbbff6) | Nov 05, 2021 |
| Unknown       | Unknown                     | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| HP            | ZBook 14u G5                | [ec192642ba](https://linux-hardware.org/?probe=ec192642ba) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8e06f2617d](https://linux-hardware.org/?probe=8e06f2617d) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1a2dda8941](https://linux-hardware.org/?probe=1a2dda8941) | Nov 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [f29c3d7003](https://linux-hardware.org/?probe=f29c3d7003) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [a795236afd](https://linux-hardware.org/?probe=a795236afd) | Nov 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [cd291857e2](https://linux-hardware.org/?probe=cd291857e2) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [6ee78bd50a](https://linux-hardware.org/?probe=6ee78bd50a) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HN0013UK    | [8454cff91f](https://linux-hardware.org/?probe=8454cff91f) | Nov 04, 2021 |
| Dell          | Studio 1537                 | [d040c159b8](https://linux-hardware.org/?probe=d040c159b8) | Nov 04, 2021 |
| HP            | ProBook 430 G3              | [1d421060d7](https://linux-hardware.org/?probe=1d421060d7) | Nov 03, 2021 |
| Dell          | Precision 5510              | [eb702ce1e6](https://linux-hardware.org/?probe=eb702ce1e6) | Nov 03, 2021 |
| Dell          | Inspiron 5502               | [c68c3a5c3b](https://linux-hardware.org/?probe=c68c3a5c3b) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [10bd49d9c0](https://linux-hardware.org/?probe=10bd49d9c0) | Nov 03, 2021 |
| Dell          | Latitude 5590               | [5bc1ed5978](https://linux-hardware.org/?probe=5bc1ed5978) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| HP            | Laptop 14-dq2xxx            | [f30e20e67b](https://linux-hardware.org/?probe=f30e20e67b) | Nov 03, 2021 |
| Dell          | XPS 15 9570                 | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | [b65f4d5ba3](https://linux-hardware.org/?probe=b65f4d5ba3) | Nov 03, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [8c19662b7e](https://linux-hardware.org/?probe=8c19662b7e) | Nov 03, 2021 |
| Toshiba       | TECRA Z50-A                 | [4aae9bdc03](https://linux-hardware.org/?probe=4aae9bdc03) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [54b32173dd](https://linux-hardware.org/?probe=54b32173dd) | Nov 03, 2021 |
| Dell          | XPS 13 7390                 | [40df244ae9](https://linux-hardware.org/?probe=40df244ae9) | Nov 02, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1310b8abf4](https://linux-hardware.org/?probe=1310b8abf4) | Oct 30, 2021 |
| Framework     | Laptop                      | [04db6c2222](https://linux-hardware.org/?probe=04db6c2222) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [e9a8fb1275](https://linux-hardware.org/?probe=e9a8fb1275) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Alienware     | Area-51m R2                 | [c3f94d8599](https://linux-hardware.org/?probe=c3f94d8599) | Oct 24, 2021 |
| HP            | ProBook 470 G5              | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| HP            | EliteBook 8560w             | [98bd384a42](https://linux-hardware.org/?probe=98bd384a42) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| Acer          | Swift SF114-32              | [faa49a332b](https://linux-hardware.org/?probe=faa49a332b) | Oct 20, 2021 |
| HP            | EliteBook 820 G1            | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [4dbc231901](https://linux-hardware.org/?probe=4dbc231901) | Oct 18, 2021 |
| GPU Compan... | GWTN156-1                   | [3cb0b09b48](https://linux-hardware.org/?probe=3cb0b09b48) | Oct 17, 2021 |
| HP            | Laptop 14-df0xxx            | [ac488ba246](https://linux-hardware.org/?probe=ac488ba246) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [362e1d3b99](https://linux-hardware.org/?probe=362e1d3b99) | Oct 15, 2021 |
| Dell          | Precision 5550              | [15a0f61f84](https://linux-hardware.org/?probe=15a0f61f84) | Oct 14, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [bf8abdfb09](https://linux-hardware.org/?probe=bf8abdfb09) | Oct 14, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [3a844f7153](https://linux-hardware.org/?probe=3a844f7153) | Oct 14, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4bb5ac9410](https://linux-hardware.org/?probe=4bb5ac9410) | Oct 12, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [d4acf59f3b](https://linux-hardware.org/?probe=d4acf59f3b) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| HP            | ProBook 450 G3              | [2eeb05ff03](https://linux-hardware.org/?probe=2eeb05ff03) | Oct 09, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [f9b69ffa3d](https://linux-hardware.org/?probe=f9b69ffa3d) | Oct 08, 2021 |
| Dell          | Inspiron 5505               | [d136f5d8f7](https://linux-hardware.org/?probe=d136f5d8f7) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [146866c629](https://linux-hardware.org/?probe=146866c629) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | [db435ab99c](https://linux-hardware.org/?probe=db435ab99c) | Oct 03, 2021 |
| Lenovo        | G580 20150                  | [08adba2c54](https://linux-hardware.org/?probe=08adba2c54) | Oct 02, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | G580 20150                  | [1dbb7762f6](https://linux-hardware.org/?probe=1dbb7762f6) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Dell          | Studio 1537                 | [aae900457c](https://linux-hardware.org/?probe=aae900457c) | Oct 01, 2021 |
| Framework     | Laptop                      | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook      | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP            | G42                         | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| HP            | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell          | XPS 17 9700                 | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek       | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell          | Latitude E5470              | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell          | XPS 15 9550                 | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer          | Aspire ES1-572              | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell          | XPS 15 9570                 | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell          | XPS 13 9380                 | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| Notebook      | P377SM-A                    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Notebook      | P377SM-A                    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook      | P377SM-A                    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| 5.16.18-200.fc35.x86_64                | 92        | 9.09%   |
| 5.14.10-300.fc35.x86_64                | 65        | 6.42%   |
| 5.14.16-301.fc35.x86_64                | 45        | 4.45%   |
| 5.16.16-200.fc35.x86_64                | 42        | 4.15%   |
| 5.15.6-200.fc35.x86_64                 | 42        | 4.15%   |
| 5.16.12-200.fc35.x86_64                | 41        | 4.05%   |
| 5.15.12-200.fc35.x86_64                | 38        | 3.75%   |
| 5.14.18-300.fc35.x86_64                | 38        | 3.75%   |
| 5.17.4-200.fc35.x86_64                 | 36        | 3.56%   |
| 5.16.9-200.fc35.x86_64                 | 31        | 3.06%   |
| 5.17.5-200.fc35.x86_64                 | 29        | 2.87%   |
| 5.14.17-301.fc35.x86_64                | 28        | 2.77%   |
| 5.15.16-200.fc35.x86_64                | 27        | 2.67%   |
| 5.16.20-200.fc35.x86_64                | 24        | 2.37%   |
| 5.16.19-200.fc35.x86_64                | 24        | 2.37%   |
| 5.16.11-200.fc35.x86_64                | 24        | 2.37%   |
| 5.15.11-200.fc35.x86_64                | 24        | 2.37%   |
| 5.15.10-200.fc35.x86_64                | 21        | 2.08%   |
| 5.14.14-300.fc35.x86_64                | 21        | 2.08%   |
| 5.16.5-200.fc35.x86_64                 | 19        | 1.88%   |
| 5.15.13-200.fc35.x86_64                | 18        | 1.78%   |
| 5.15.14-200.fc35.x86_64                | 16        | 1.58%   |
| 5.16.8-200.fc35.x86_64                 | 15        | 1.48%   |
| 5.15.8-200.fc35.x86_64                 | 15        | 1.48%   |
| 5.15.4-201.fc35.x86_64                 | 15        | 1.48%   |
| 5.15.18-200.fc35.x86_64                | 14        | 1.38%   |
| 5.16.15-201.fc35.x86_64                | 13        | 1.28%   |
| 5.14.15-300.fc35.x86_64                | 13        | 1.28%   |
| 5.16.14-200.fc35.x86_64                | 12        | 1.19%   |
| 5.15.7-200.fc35.x86_64                 | 12        | 1.19%   |
| 5.15.5-200.fc35.x86_64                 | 12        | 1.19%   |
| 5.16.7-200.fc35.x86_64                 | 10        | 0.99%   |
| 5.15.17-200.fc35.x86_64                | 9         | 0.89%   |
| 5.14.9-300.fc35.x86_64                 | 9         | 0.89%   |
| 5.14.0-60.fc35.x86_64                  | 7         | 0.69%   |
| 5.16.17-200.fc35.x86_64                | 6         | 0.59%   |
| 5.16.10-200.fc35.x86_64                | 6         | 0.59%   |
| 5.15.15-200.fc35.x86_64                | 6         | 0.59%   |
| 5.14.11-300.fc35.x86_64                | 5         | 0.49%   |
| 5.14.0-0.rc5.42.fc35.x86_64            | 5         | 0.49%   |
| 5.17.7-200.fc35.x86_64                 | 4         | 0.4%    |
| 5.17.6-200.fc35.x86_64                 | 4         | 0.4%    |
| 5.16.13-200.fc35.x86_64                | 4         | 0.4%    |
| 5.17.8-200.fc35.x86_64                 | 3         | 0.3%    |
| 5.14.7-300.fc35.x86_64                 | 3         | 0.3%    |
| 5.14.12-300.fc35.x86_64                | 3         | 0.3%    |
| 5.17.5-xm1.0.fc35.x86_64               | 2         | 0.2%    |
| 5.16.12-250.vanilla.1.fc35.x86_64      | 2         | 0.2%    |
| 5.15.6-200.rog.fc35.x86_64             | 2         | 0.2%    |
| 5.14.3-300.fc35.x86_64                 | 2         | 0.2%    |
| 5.11.12-300.fc34.x86_64                | 2         | 0.2%    |
| 5.6.16-300.fc32.x86_64                 | 1         | 0.1%    |
| 5.18.0-60.vanilla.1.fc35.x86_64        | 1         | 0.1%    |
| 5.17.5-301.fsync.fc35.x86_64           | 1         | 0.1%    |
| 5.17.4-lqx1.0.fc35.x86_64              | 1         | 0.1%    |
| 5.17.3-xm1.0.fc35.x86_64               | 1         | 0.1%    |
| 5.17.3-302.fc36.x86_64                 | 1         | 0.1%    |
| 5.17.1-xm1.0.fc35.x86_64               | 1         | 0.1%    |
| 5.17.1-200.fc35.x86_64                 | 1         | 0.1%    |
| 5.17.0-0.rc5.102.vanilla.1.fc35.x86_64 | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.18 | 92        | 9.1%    |
| 5.14.10 | 65        | 6.43%   |
| 5.14.16 | 46        | 4.55%   |
| 5.16.16 | 44        | 4.35%   |
| 5.16.12 | 44        | 4.35%   |
| 5.15.6  | 44        | 4.35%   |
| 5.15.12 | 38        | 3.76%   |
| 5.14.18 | 38        | 3.76%   |
| 5.17.4  | 37        | 3.66%   |
| 5.17.5  | 32        | 3.17%   |
| 5.16.9  | 31        | 3.07%   |
| 5.14.17 | 28        | 2.77%   |
| 5.15.16 | 27        | 2.67%   |
| 5.16.20 | 25        | 2.47%   |
| 5.15.11 | 25        | 2.47%   |
| 5.16.19 | 24        | 2.37%   |
| 5.16.11 | 24        | 2.37%   |
| 5.14.14 | 22        | 2.18%   |
| 5.15.10 | 21        | 2.08%   |
| 5.15.13 | 20        | 1.98%   |
| 5.16.5  | 19        | 1.88%   |
| 5.15.8  | 17        | 1.68%   |
| 5.15.14 | 16        | 1.58%   |
| 5.16.8  | 15        | 1.48%   |
| 5.15.4  | 15        | 1.48%   |
| 5.14.0  | 15        | 1.48%   |
| 5.15.18 | 14        | 1.38%   |
| 5.14.15 | 14        | 1.38%   |
| 5.16.15 | 13        | 1.29%   |
| 5.15.5  | 13        | 1.29%   |
| 5.16.14 | 12        | 1.19%   |
| 5.15.7  | 12        | 1.19%   |
| 5.16.7  | 10        | 0.99%   |
| 5.14.9  | 10        | 0.99%   |
| 5.15.17 | 9         | 0.89%   |
| 5.16.17 | 7         | 0.69%   |
| 5.15.15 | 7         | 0.69%   |
| 5.16.10 | 6         | 0.59%   |
| 5.16.13 | 5         | 0.49%   |
| 5.14.11 | 5         | 0.49%   |
| 5.17.7  | 4         | 0.4%    |
| 5.17.6  | 4         | 0.4%    |
| 5.17.8  | 3         | 0.3%    |
| 5.14.7  | 3         | 0.3%    |
| 5.14.12 | 3         | 0.3%    |
| 5.17.3  | 2         | 0.2%    |
| 5.17.1  | 2         | 0.2%    |
| 5.16.0  | 2         | 0.2%    |
| 5.14.3  | 2         | 0.2%    |
| 5.13.19 | 2         | 0.2%    |
| 5.12.0  | 2         | 0.2%    |
| 5.11.12 | 2         | 0.2%    |
| 5.6.16  | 1         | 0.1%    |
| 5.18.0  | 1         | 0.1%    |
| 5.17.0  | 1         | 0.1%    |
| 5.16.2  | 1         | 0.1%    |
| 5.16.1  | 1         | 0.1%    |
| 5.15.32 | 1         | 0.1%    |
| 5.15.2  | 1         | 0.1%    |
| 5.15.19 | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 359       | 36.6%   |
| 5.15    | 273       | 27.83%  |
| 5.14    | 250       | 25.48%  |
| 5.17    | 84        | 8.56%   |
| 5.13    | 5         | 0.51%   |
| 5.12    | 3         | 0.31%   |
| 5.10    | 3         | 0.31%   |
| 5.11    | 2         | 0.2%    |
| 5.6     | 1         | 0.1%    |
| 5.18    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 919       | 99.89%  |
| aarch64 | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 718       | 77.04%  |
| KDE5            | 94        | 10.09%  |
| Unknown         | 30        | 3.22%   |
| X-Cinnamon      | 15        | 1.61%   |
| MATE            | 15        | 1.61%   |
| Cinnamon        | 15        | 1.61%   |
| XFCE            | 12        | 1.29%   |
| i3              | 8         | 0.86%   |
| GNOME Classic   | 6         | 0.64%   |
| sway            | 4         | 0.43%   |
| LXQt            | 3         | 0.32%   |
| LXDE            | 3         | 0.32%   |
| Pantheon        | 2         | 0.21%   |
| KDE             | 2         | 0.21%   |
| fluxbox         | 2         | 0.21%   |
| openbox         | 1         | 0.11%   |
| GNOME Flashback | 1         | 0.11%   |
| bspwm           | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 619       | 66.2%   |
| X11     | 292       | 31.23%  |
| Unknown | 16        | 1.71%   |
| Tty     | 8         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 446       | 48.01%  |
| GDM     | 365       | 39.29%  |
| LightDM | 58        | 6.24%   |
| SDDM    | 57        | 6.14%   |
| LXDM    | 2         | 0.22%   |
| XDM     | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 513       | 55.52%  |
| en_GB   | 76        | 8.23%   |
| pt_BR   | 48        | 5.19%   |
| ru_RU   | 40        | 4.33%   |
| fr_FR   | 28        | 3.03%   |
| de_DE   | 25        | 2.71%   |
| it_IT   | 22        | 2.38%   |
| pl_PL   | 14        | 1.52%   |
| es_ES   | 14        | 1.52%   |
| en_CA   | 14        | 1.52%   |
| en_AU   | 14        | 1.52%   |
| es_CL   | 8         | 0.87%   |
| es_MX   | 7         | 0.76%   |
| en_IN   | 7         | 0.76%   |
| tr_TR   | 6         | 0.65%   |
| C       | 6         | 0.65%   |
| zh_CN   | 5         | 0.54%   |
| nl_NL   | 5         | 0.54%   |
| sv_SE   | 4         | 0.43%   |
| fr_CA   | 4         | 0.43%   |
| es_AR   | 4         | 0.43%   |
| en_IL   | 4         | 0.43%   |
| de_AT   | 4         | 0.43%   |
| cs_CZ   | 4         | 0.43%   |
| Unknown | 4         | 0.43%   |
| uk_UA   | 3         | 0.32%   |
| en_NZ   | 3         | 0.32%   |
| sk_SK   | 2         | 0.22%   |
| ro_RO   | 2         | 0.22%   |
| pt_PT   | 2         | 0.22%   |
| nb_NO   | 2         | 0.22%   |
| fr_CH   | 2         | 0.22%   |
| fi_FI   | 2         | 0.22%   |
| es_NI   | 2         | 0.22%   |
| es_GT   | 2         | 0.22%   |
| es_CO   | 2         | 0.22%   |
| en_ZA   | 2         | 0.22%   |
| en_DE   | 2         | 0.22%   |
| ca_ES   | 2         | 0.22%   |
| szl_PL  | 1         | 0.11%   |
| ru_UA   | 1         | 0.11%   |
| nl_BE   | 1         | 0.11%   |
| lt_LT   | 1         | 0.11%   |
| hu_HU   | 1         | 0.11%   |
| ga_IE   | 1         | 0.11%   |
| fr_BE   | 1         | 0.11%   |
| es_PE   | 1         | 0.11%   |
| es_EC   | 1         | 0.11%   |
| en_SG   | 1         | 0.11%   |
| en_IE   | 1         | 0.11%   |
| en_DK   | 1         | 0.11%   |
| de_CH   | 1         | 0.11%   |
| da_DK   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 778       | 84.02%  |
| BIOS | 148       | 15.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 685       | 74.13%  |
| Ext4    | 212       | 22.94%  |
| Xfs     | 22        | 2.38%   |
| Overlay | 4         | 0.43%   |
| Unknown | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 453       | 48.61%  |
| GPT     | 432       | 46.35%  |
| MBR     | 47        | 5.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 830       | 89.25%  |
| Yes       | 100       | 10.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 763       | 82.22%  |
| Yes       | 165       | 17.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo                   | 268       | 29.13%  |
| Dell                     | 162       | 17.61%  |
| Hewlett-Packard          | 135       | 14.67%  |
| ASUSTek Computer         | 80        | 8.7%    |
| Acer                     | 65        | 7.07%   |
| Apple                    | 38        | 4.13%   |
| HUAWEI                   | 22        | 2.39%   |
| MSI                      | 18        | 1.96%   |
| Toshiba                  | 13        | 1.41%   |
| Notebook                 | 11        | 1.2%    |
| Framework                | 10        | 1.09%   |
| Sony                     | 9         | 0.98%   |
| Samsung Electronics      | 8         | 0.87%   |
| Google                   | 7         | 0.76%   |
| Positivo                 | 6         | 0.65%   |
| System76                 | 5         | 0.54%   |
| Razer                    | 5         | 0.54%   |
| TUXEDO                   | 4         | 0.43%   |
| Timi                     | 4         | 0.43%   |
| Fujitsu                  | 4         | 0.43%   |
| Alienware                | 4         | 0.43%   |
| Gigabyte Technology      | 3         | 0.33%   |
| Avell High Performance   | 3         | 0.33%   |
| PC Specialist            | 2         | 0.22%   |
| Panasonic                | 2         | 0.22%   |
| HONOR                    | 2         | 0.22%   |
| Hampoo                   | 2         | 0.22%   |
| GPU Company              | 2         | 0.22%   |
| Fujitsu Siemens          | 2         | 0.22%   |
| Chuwi                    | 2         | 0.22%   |
| Unknown                  | 2         | 0.22%   |
| Teclast                  | 1         | 0.11%   |
| SiComputer               | 1         | 0.11%   |
| SCHNEIDER                | 1         | 0.11%   |
| Schenker                 | 1         | 0.11%   |
| Positivo Bahia - VAIO    | 1         | 0.11%   |
| Pine Microsystems        | 1         | 0.11%   |
| Medion                   | 1         | 0.11%   |
| Mediacom                 | 1         | 0.11%   |
| Login Informatica        | 1         | 0.11%   |
| LG Electronics           | 1         | 0.11%   |
| LDLC                     | 1         | 0.11%   |
| Jumper                   | 1         | 0.11%   |
| Intel                    | 1         | 0.11%   |
| Inspire Technology Group | 1         | 0.11%   |
| Getac                    | 1         | 0.11%   |
| eMachines                | 1         | 0.11%   |
| Digibras                 | 1         | 0.11%   |
| Cube                     | 1         | 0.11%   |
| BESSTAR Tech             | 1         | 0.11%   |
| AVITA                    | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Framework Laptop                            | 10        | 1.09%   |
| HP Notebook                                 | 6         | 0.65%   |
| Dell XPS 13 9310                            | 6         | 0.65%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 5         | 0.54%   |
| HUAWEI KLVL-WXX9                            | 5         | 0.54%   |
| HP Pavilion Notebook                        | 5         | 0.54%   |
| Dell XPS 13 7390                            | 5         | 0.54%   |
| Dell XPS 13 9370                            | 4         | 0.43%   |
| Dell XPS 13 9305                            | 4         | 0.43%   |
| Dell Precision 5510                         | 4         | 0.43%   |
| Dell Latitude E7440                         | 4         | 0.43%   |
| Apple MacBookPro9,2                         | 4         | 0.43%   |
| MSI Delta 15 A5EFK                          | 3         | 0.33%   |
| Lenovo Legion Y530-15ICH 81FV               | 3         | 0.33%   |
| Lenovo IdeaPad S145-15API 81V7              | 3         | 0.33%   |
| Lenovo IdeaPad 530S-14IKB 81EU              | 3         | 0.33%   |
| Lenovo IdeaPad 3 14ALC6 82KT                | 3         | 0.33%   |
| HUAWEI KLVL-WXXW                            | 3         | 0.33%   |
| HUAWEI HVY-WXX9                             | 3         | 0.33%   |
| HP ProBook 430 G5                           | 3         | 0.33%   |
| HP Pavilion Laptop 15-eh0xxx                | 3         | 0.33%   |
| HP Pavilion Aero Laptop 13-be0xxx           | 3         | 0.33%   |
| HP Pavilion 15                              | 3         | 0.33%   |
| HP EliteBook 840 G3                         | 3         | 0.33%   |
| Dell XPS 17 9700                            | 3         | 0.33%   |
| Dell XPS 15 9570                            | 3         | 0.33%   |
| Dell XPS 15 9550                            | 3         | 0.33%   |
| Dell XPS 13 9380                            | 3         | 0.33%   |
| Dell XPS 13 9360                            | 3         | 0.33%   |
| Dell Latitude E6530                         | 3         | 0.33%   |
| Dell Latitude 7490                          | 3         | 0.33%   |
| Dell Inspiron N5110                         | 3         | 0.33%   |
| Dell Inspiron 5567                          | 3         | 0.33%   |
| Dell Inspiron 5458                          | 3         | 0.33%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM       | 3         | 0.33%   |
| ASUS ROG Strix G513QY_G513QY                | 3         | 0.33%   |
| Apple MacBookPro6,2                         | 3         | 0.33%   |
| Apple MacBookPro14,1                        | 3         | 0.33%   |
| Apple MacBookPro11,3                        | 3         | 0.33%   |
| Acer Swift SF314-42                         | 3         | 0.33%   |
| Acer Aspire A514-54                         | 3         | 0.33%   |
| Unknown                                     | 3         | 0.33%   |
| System76 Pangolin                           | 2         | 0.22%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 2         | 0.22%   |
| MSI GE75 Raider 10SE                        | 2         | 0.22%   |
| Lenovo Yoga S740-14IIL 81RS                 | 2         | 0.22%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW  | 2         | 0.22%   |
| Lenovo ThinkPad P1 Gen 3 20TJS53A00         | 2         | 0.22%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW        | 2         | 0.22%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ            | 2         | 0.22%   |
| Lenovo Legion 5 15ARH05H 82B1               | 2         | 0.22%   |
| Lenovo Legion 5 15ARH05 82B5                | 2         | 0.22%   |
| Lenovo IdeaPad Flex-14API 81SS              | 2         | 0.22%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7            | 2         | 0.22%   |
| Lenovo IdeaPad 320S-14IKB 81BN              | 2         | 0.22%   |
| Lenovo IdeaPad 320-15ISK 80XH               | 2         | 0.22%   |
| Lenovo IdeaPad 3 14ITL6 82H7                | 2         | 0.22%   |
| Lenovo IdeaPad 100-15IBD 80QQ               | 2         | 0.22%   |
| Lenovo G500 20236                           | 2         | 0.22%   |
| Lenovo G50-70 20351                         | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 152       | 16.52%  |
| Lenovo IdeaPad              | 60        | 6.52%   |
| Dell Latitude               | 49        | 5.33%   |
| Dell Inspiron               | 45        | 4.89%   |
| Dell XPS                    | 40        | 4.35%   |
| Acer Aspire                 | 37        | 4.02%   |
| HP Pavilion                 | 34        | 3.7%    |
| HP ProBook                  | 22        | 2.39%   |
| HP EliteBook                | 20        | 2.17%   |
| HP Laptop                   | 18        | 1.96%   |
| ASUS ROG                    | 18        | 1.96%   |
| Lenovo Legion               | 14        | 1.52%   |
| Lenovo ThinkBook            | 13        | 1.41%   |
| Dell Precision              | 13        | 1.41%   |
| ASUS VivoBook               | 13        | 1.41%   |
| Acer Swift                  | 12        | 1.3%    |
| HP ZBook                    | 11        | 1.2%    |
| Framework Laptop            | 10        | 1.09%   |
| Dell Vostro                 | 10        | 1.09%   |
| ASUS ASUS                   | 10        | 1.09%   |
| Acer Nitro                  | 10        | 1.09%   |
| Toshiba Satellite           | 9         | 0.98%   |
| Lenovo Yoga                 | 7         | 0.76%   |
| ASUS ZenBook                | 7         | 0.76%   |
| Apple MacBookPro11          | 7         | 0.76%   |
| HP Notebook                 | 6         | 0.65%   |
| HP ENVY                     | 6         | 0.65%   |
| HUAWEI KLVL-WXX9            | 5         | 0.54%   |
| HP OMEN                     | 5         | 0.54%   |
| Razer Blade                 | 4         | 0.43%   |
| Apple MacBookPro9           | 4         | 0.43%   |
| Toshiba TECRA               | 3         | 0.33%   |
| MSI GF63                    | 3         | 0.33%   |
| MSI Delta                   | 3         | 0.33%   |
| HUAWEI KLVL-WXXW            | 3         | 0.33%   |
| HUAWEI HVY-WXX9             | 3         | 0.33%   |
| Fujitsu LIFEBOOK            | 3         | 0.33%   |
| Apple MacBookPro6           | 3         | 0.33%   |
| Apple MacBookPro14          | 3         | 0.33%   |
| Apple MacBookPro10          | 3         | 0.33%   |
| Unknown                     | 3         | 0.33%   |
| TUXEDO InfinityBook         | 2         | 0.22%   |
| System76 Pangolin           | 2         | 0.22%   |
| Samsung RV411               | 2         | 0.22%   |
| Notebook NH5x               | 2         | 0.22%   |
| MSI Modern                  | 2         | 0.22%   |
| MSI GE75                    | 2         | 0.22%   |
| Lenovo G500                 | 2         | 0.22%   |
| Lenovo G50-70               | 2         | 0.22%   |
| HUAWEI NBLK-WAX9X           | 2         | 0.22%   |
| HUAWEI BOHK-WAX9X           | 2         | 0.22%   |
| HONOR NBD-WXX9              | 2         | 0.22%   |
| HP Compaq                   | 2         | 0.22%   |
| HP 15                       | 2         | 0.22%   |
| Gigabyte AERO               | 2         | 0.22%   |
| Fujitsu Siemens ESPRIMO     | 2         | 0.22%   |
| Dell G5                     | 2         | 0.22%   |
| Avell High Performance B.ON | 2         | 0.22%   |
| ASUS X550CC                 | 2         | 0.22%   |
| ASUS TUF                    | 2         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 180       | 19.57%  |
| 2021 | 150       | 16.3%   |
| 2019 | 114       | 12.39%  |
| 2018 | 88        | 9.57%   |
| 2017 | 66        | 7.17%   |
| 2016 | 59        | 6.41%   |
| 2013 | 52        | 5.65%   |
| 2015 | 44        | 4.78%   |
| 2011 | 42        | 4.57%   |
| 2014 | 41        | 4.46%   |
| 2012 | 37        | 4.02%   |
| 2010 | 18        | 1.96%   |
| 2008 | 11        | 1.2%    |
| 2009 | 9         | 0.98%   |
| 2022 | 7         | 0.76%   |
| 2007 | 2         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 920       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 745       | 80.54%  |
| Enabled  | 180       | 19.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 910       | 98.91%  |
| Yes  | 10        | 1.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 272       | 29.47%  |
| 16.01-24.0  | 227       | 24.59%  |
| 8.01-16.0   | 178       | 19.28%  |
| 32.01-64.0  | 107       | 11.59%  |
| 3.01-4.0    | 93        | 10.08%  |
| 64.01-256.0 | 19        | 2.06%   |
| 24.01-32.0  | 11        | 1.19%   |
| 1.01-2.0    | 11        | 1.19%   |
| 2.01-3.0    | 5         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 282       | 28.8%   |
| 4.01-8.0   | 272       | 27.78%  |
| 3.01-4.0   | 208       | 21.25%  |
| 1.01-2.0   | 126       | 12.87%  |
| 8.01-16.0  | 77        | 7.87%   |
| 16.01-24.0 | 6         | 0.61%   |
| 32.01-64.0 | 3         | 0.31%   |
| 0.51-1.0   | 3         | 0.31%   |
| 24.01-32.0 | 2         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 668       | 72.06%  |
| 2      | 225       | 24.27%  |
| 3      | 24        | 2.59%   |
| 0      | 4         | 0.43%   |
| 4      | 3         | 0.32%   |
| 5      | 2         | 0.22%   |
| 6      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 751       | 81.45%  |
| Yes       | 171       | 18.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 672       | 72.73%  |
| No        | 252       | 27.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 905       | 98.37%  |
| No        | 15        | 1.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 787       | 84.9%   |
| No        | 140       | 15.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 153       | 16.58%  |
| Brazil       | 77        | 8.34%   |
| Russia       | 68        | 7.37%   |
| Germany      | 51        | 5.53%   |
| Italy        | 39        | 4.23%   |
| France       | 34        | 3.68%   |
| UK           | 33        | 3.58%   |
| Canada       | 33        | 3.58%   |
| India        | 29        | 3.14%   |
| Spain        | 25        | 2.71%   |
| Poland       | 23        | 2.49%   |
| Netherlands  | 21        | 2.28%   |
| Sweden       | 18        | 1.95%   |
| Turkey       | 16        | 1.73%   |
| Austria      | 16        | 1.73%   |
| Czechia      | 14        | 1.52%   |
| Mexico       | 13        | 1.41%   |
| Australia    | 13        | 1.41%   |
| Indonesia    | 12        | 1.3%    |
| Norway       | 11        | 1.19%   |
| Ukraine      | 10        | 1.08%   |
| Romania      | 10        | 1.08%   |
| Hungary      | 10        | 1.08%   |
| Switzerland  | 9         | 0.98%   |
| Greece       | 9         | 0.98%   |
| Chile        | 9         | 0.98%   |
| Belgium      | 9         | 0.98%   |
| Portugal     | 8         | 0.87%   |
| Israel       | 8         | 0.87%   |
| China        | 7         | 0.76%   |
| Belarus      | 7         | 0.76%   |
| Argentina    | 7         | 0.76%   |
| Japan        | 6         | 0.65%   |
| Finland      | 6         | 0.65%   |
| South Africa | 5         | 0.54%   |
| Saudi Arabia | 5         | 0.54%   |
| New Zealand  | 5         | 0.54%   |
| Iran         | 5         | 0.54%   |
| Denmark      | 5         | 0.54%   |
| Croatia      | 5         | 0.54%   |
| Bulgaria     | 5         | 0.54%   |
| Philippines  | 4         | 0.43%   |
| Georgia      | 4         | 0.43%   |
| Egypt        | 3         | 0.33%   |
| Colombia     | 3         | 0.33%   |
| Algeria      | 3         | 0.33%   |
| Venezuela    | 2         | 0.22%   |
| Tunisia      | 2         | 0.22%   |
| Taiwan       | 2         | 0.22%   |
| Slovakia     | 2         | 0.22%   |
| Singapore    | 2         | 0.22%   |
| Serbia       | 2         | 0.22%   |
| Peru         | 2         | 0.22%   |
| Panama       | 2         | 0.22%   |
| Nicaragua    | 2         | 0.22%   |
| Myanmar      | 2         | 0.22%   |
| Malaysia     | 2         | 0.22%   |
| Kenya        | 2         | 0.22%   |
| Kazakhstan   | 2         | 0.22%   |
| Ireland      | 2         | 0.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 27        | 2.85%   |
| Sao Paulo         | 12        | 1.27%   |
| Istanbul          | 12        | 1.27%   |
| Milan             | 10        | 1.06%   |
| Vienna            | 9         | 0.95%   |
| Warsaw            | 7         | 0.74%   |
| St Petersburg     | 7         | 0.74%   |
| Munich            | 7         | 0.74%   |
| Sydney            | 6         | 0.63%   |
| Rome              | 6         | 0.63%   |
| Oslo              | 6         | 0.63%   |
| Montreal          | 6         | 0.63%   |
| Athens            | 6         | 0.63%   |
| Yekaterinburg     | 5         | 0.53%   |
| Fortaleza         | 5         | 0.53%   |
| Coimbatore        | 5         | 0.53%   |
| Berlin            | 5         | 0.53%   |
| Belo Horizonte    | 5         | 0.53%   |
| Amsterdam         | 5         | 0.53%   |
| Zurich            | 4         | 0.42%   |
| Zagreb            | 4         | 0.42%   |
| Vancouver         | 4         | 0.42%   |
| Sofia             | 4         | 0.42%   |
| Rio de Janeiro    | 4         | 0.42%   |
| Prague            | 4         | 0.42%   |
| Paris             | 4         | 0.42%   |
| Mumbai            | 4         | 0.42%   |
| Minsk             | 4         | 0.42%   |
| Madrid            | 4         | 0.42%   |
| Kyiv              | 4         | 0.42%   |
| K'alak'i T'bilisi | 4         | 0.42%   |
| Jakarta           | 4         | 0.42%   |
| Frankfurt am Main | 4         | 0.42%   |
| Chicago           | 4         | 0.42%   |
| Budapest          | 4         | 0.42%   |
| Bucharest         | 4         | 0.42%   |
| Wörgl            | 3         | 0.32%   |
| Strasbourg        | 3         | 0.32%   |
| Southampton       | 3         | 0.32%   |
| Seattle           | 3         | 0.32%   |
| Santo André      | 3         | 0.32%   |
| Santiago          | 3         | 0.32%   |
| Rotterdam         | 3         | 0.32%   |
| Portland          | 3         | 0.32%   |
| Odessa            | 3         | 0.32%   |
| Novosibirsk       | 3         | 0.32%   |
| Mexico City       | 3         | 0.32%   |
| Lyon              | 3         | 0.32%   |
| Los Angeles       | 3         | 0.32%   |
| Lawrenceville     | 3         | 0.32%   |
| Krakow            | 3         | 0.32%   |
| Helsinki          | 3         | 0.32%   |
| Hamburg           | 3         | 0.32%   |
| Gothenburg        | 3         | 0.32%   |
| Florianópolis    | 3         | 0.32%   |
| Düsseldorf       | 3         | 0.32%   |
| Calgary           | 3         | 0.32%   |
| Brno              | 3         | 0.32%   |
| Bengaluru         | 3         | 0.32%   |
| Barcelona         | 3         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 244       | 322    | 21.09%  |
| WDC                            | 125       | 134    | 10.8%   |
| Toshiba                        | 81        | 84     | 7%      |
| Seagate                        | 81        | 92     | 7%      |
| SK Hynix                       | 78        | 92     | 6.74%   |
| SanDisk                        | 76        | 91     | 6.57%   |
| Unknown                        | 61        | 72     | 5.27%   |
| Kingston                       | 56        | 61     | 4.84%   |
| Intel                          | 52        | 66     | 4.49%   |
| Micron Technology              | 37        | 45     | 3.2%    |
| Crucial                        | 32        | 35     | 2.77%   |
| KIOXIA                         | 28        | 33     | 2.42%   |
| Apple                          | 21        | 23     | 1.82%   |
| A-DATA Technology              | 16        | 17     | 1.38%   |
| HGST                           | 15        | 16     | 1.3%    |
| Phison                         | 12        | 13     | 1.04%   |
| LITEON                         | 11        | 11     | 0.95%   |
| Transcend                      | 10        | 12     | 0.86%   |
| Hitachi                        | 8         | 8      | 0.69%   |
| Silicon Motion                 | 7         | 7      | 0.61%   |
| XPG                            | 5         | 7      | 0.43%   |
| PLEXTOR                        | 5         | 6      | 0.43%   |
| Corsair                        | 5         | 5      | 0.43%   |
| China                          | 5         | 5      | 0.43%   |
| ADATA Technology               | 5         | 5      | 0.43%   |
| UMIS                           | 4         | 4      | 0.35%   |
| Team                           | 4         | 5      | 0.35%   |
| Lexar                          | 4         | 5      | 0.35%   |
| Unknown                        | 4         | 5      | 0.35%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.26%   |
| PNY                            | 3         | 4      | 0.26%   |
| Patriot                        | 3         | 3      | 0.26%   |
| Mushkin                        | 3         | 3      | 0.26%   |
| YMTC                           | 2         | 2      | 0.17%   |
| SPCC                           | 2         | 2      | 0.17%   |
| Realtek Semiconductor          | 2         | 3      | 0.17%   |
| Ramsta                         | 2         | 3      | 0.17%   |
| Netac                          | 2         | 2      | 0.17%   |
| LITEONIT                       | 2         | 2      | 0.17%   |
| Lenovo                         | 2         | 2      | 0.17%   |
| HPE                            | 2         | 3      | 0.17%   |
| Hewlett-Packard                | 2         | 1      | 0.17%   |
| Gigabyte Technology            | 2         | 2      | 0.17%   |
| FORESEE                        | 2         | 2      | 0.17%   |
| ASMT                           | 2         | 2      | 0.17%   |
| Zozt                           | 1         | 1      | 0.09%   |
| WDC WDS                        | 1         | 1      | 0.09%   |
| Vaseky                         | 1         | 1      | 0.09%   |
| USB3.1                         | 1         | 1      | 0.09%   |
| TO Exter                       | 1         | 1      | 0.09%   |
| Teclast                        | 1         | 1      | 0.09%   |
| TCSUNBOW                       | 1         | 1      | 0.09%   |
| SSSTC                          | 1         | 1      | 0.09%   |
| SSK                            | 1         | 1      | 0.09%   |
| Solid State Storage Technology | 1         | 1      | 0.09%   |
| MX                             | 1         | 1      | 0.09%   |
| Mass                           | 1         | 1      | 0.09%   |
| LDLC                           | 1         | 1      | 0.09%   |
| LaCie                          | 1         | 2      | 0.09%   |
| KingSpec                       | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB         | 31        | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB       | 17        | 1.4%    |
| SK Hynix NVMe SSD Drive 512GB        | 16        | 1.32%   |
| Sandisk NVMe SSD Drive 512GB         | 15        | 1.24%   |
| Samsung NVMe SSD Drive 256GB         | 14        | 1.16%   |
| Sandisk NVMe SSD Drive 256GB         | 13        | 1.07%   |
| Samsung NVMe SSD Drive 500GB         | 13        | 1.07%   |
| Kingston SA400S37480G 480GB SSD      | 13        | 1.07%   |
| Samsung NVMe SSD Drive 1TB           | 12        | 0.99%   |
| SK Hynix NVMe SSD Drive 256GB        | 11        | 0.91%   |
| Unknown MMC Card  64GB               | 10        | 0.83%   |
| Unknown MMC Card  32GB               | 10        | 0.83%   |
| Kingston SA400S37240G 240GB SSD      | 10        | 0.83%   |
| Intel NVMe SSD Drive 512GB           | 10        | 0.83%   |
| KIOXIA NVMe SSD Drive 512GB          | 9         | 0.74%   |
| Toshiba NVMe SSD Drive 512GB         | 8         | 0.66%   |
| Toshiba MQ04ABF100 1TB               | 8         | 0.66%   |
| Sandisk NVMe SSD Drive 500GB         | 8         | 0.66%   |
| Samsung NVMe SSD Drive 1024GB        | 8         | 0.66%   |
| SK Hynix NVMe SSD Drive 1024GB       | 7         | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 7         | 0.58%   |
| Sandisk NVMe SSD Drive 1TB           | 7         | 0.58%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 7         | 0.58%   |
| HGST HTS721010A9E630 1TB             | 7         | 0.58%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 6         | 0.5%    |
| Unknown MMC Card  128GB              | 6         | 0.5%    |
| Toshiba MQ01ABD100 1TB               | 6         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB      | 6         | 0.5%    |
| Seagate ST1000LM048-2E7172 1TB       | 6         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB         | 6         | 0.5%    |
| Samsung SSD 850 EVO 250GB            | 6         | 0.5%    |
| Phison 311CD0512GB                   | 6         | 0.5%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 5         | 0.41%   |
| SK Hynix BC711 NVMe 512GB            | 5         | 0.41%   |
| Sandisk NVMe SSD Drive 1024GB        | 5         | 0.41%   |
| Samsung SSD 980 PRO 500GB            | 5         | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB       | 5         | 0.41%   |
| Samsung SSD 970 EVO 1TB              | 5         | 0.41%   |
| Samsung SSD 860 EVO 500GB            | 5         | 0.41%   |
| Samsung NVMe SSD Drive 2TB           | 5         | 0.41%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 5         | 0.41%   |
| Micron NVMe SSD Drive 512GB          | 5         | 0.41%   |
| Micron 2210_MTFDHBA512QFD 512GB      | 5         | 0.41%   |
| KIOXIA NVMe SSD Drive 256GB          | 5         | 0.41%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 5         | 0.41%   |
| Crucial CT500MX500SSD1 500GB         | 5         | 0.41%   |
| Crucial CT1000MX500SSD1 1TB          | 5         | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB             | 4         | 0.33%   |
| Unknown SD128  128GB                 | 4         | 0.33%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.33%   |
| Toshiba KXG6AZNV512G 512GB           | 4         | 0.33%   |
| Toshiba KXG6AZNV256G 256GB           | 4         | 0.33%   |
| SK Hynix PC401 NVMe 512GB            | 4         | 0.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 4         | 0.33%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 0.33%   |
| Seagate Expansion 4TB                | 4         | 0.33%   |
| Samsung SSD 980 500GB                | 4         | 0.33%   |
| Samsung SSD 980 1TB                  | 4         | 0.33%   |
| Samsung SSD 860 EVO 250GB            | 4         | 0.33%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 91     | 38.83%  |
| WDC                 | 60        | 63     | 29.13%  |
| Toshiba             | 35        | 36     | 16.99%  |
| HGST                | 15        | 16     | 7.28%   |
| Hitachi             | 8         | 8      | 3.88%   |
| Unknown             | 3         | 3      | 1.46%   |
| Apple               | 2         | 2      | 0.97%   |
| Samsung Electronics | 1         | 1      | 0.49%   |
| LaCie               | 1         | 2      | 0.49%   |
| ASMT                | 1         | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 73        | 100    | 22.67%  |
| Kingston            | 41        | 45     | 12.73%  |
| Crucial             | 29        | 32     | 9.01%   |
| SanDisk             | 24        | 34     | 7.45%   |
| Intel               | 18        | 20     | 5.59%   |
| WDC                 | 16        | 18     | 4.97%   |
| Apple               | 14        | 14     | 4.35%   |
| A-DATA Technology   | 11        | 12     | 3.42%   |
| Micron Technology   | 10        | 12     | 3.11%   |
| Transcend           | 8         | 10     | 2.48%   |
| LITEON              | 8         | 8      | 2.48%   |
| SK Hynix            | 7         | 8      | 2.17%   |
| Toshiba             | 6         | 7      | 1.86%   |
| China               | 5         | 5      | 1.55%   |
| PNY                 | 3         | 4      | 0.93%   |
| PLEXTOR             | 3         | 4      | 0.93%   |
| Patriot             | 3         | 3      | 0.93%   |
| Mushkin             | 3         | 3      | 0.93%   |
| Team                | 2         | 3      | 0.62%   |
| SPCC                | 2         | 2      | 0.62%   |
| Ramsta              | 2         | 3      | 0.62%   |
| Netac               | 2         | 2      | 0.62%   |
| LITEONIT            | 2         | 2      | 0.62%   |
| Lexar               | 2         | 3      | 0.62%   |
| Gigabyte Technology | 2         | 2      | 0.62%   |
| FORESEE             | 2         | 2      | 0.62%   |
| Corsair             | 2         | 2      | 0.62%   |
| Zozt                | 1         | 1      | 0.31%   |
| WDC WDS             | 1         | 1      | 0.31%   |
| Vaseky              | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |
| TO Exter            | 1         | 1      | 0.31%   |
| Teclast             | 1         | 1      | 0.31%   |
| TCSUNBOW            | 1         | 1      | 0.31%   |
| MX                  | 1         | 1      | 0.31%   |
| KingSpec            | 1         | 1      | 0.31%   |
| JMicron             | 1         | 1      | 0.31%   |
| HUSKY               | 1         | 1      | 0.31%   |
| HPE                 | 1         | 2      | 0.31%   |
| Hewlett-Packard     | 1         | 1      | 0.31%   |
| GOODRAM             | 1         | 1      | 0.31%   |
| External            | 1         | 1      | 0.31%   |
| CT1000P2            | 1         | 1      | 0.31%   |
| BIWIN               | 1         | 1      | 0.31%   |
| ASMT                | 1         | 1      | 0.31%   |
| Apacer              | 1         | 1      | 0.31%   |
| ADATA SU            | 1         | 1      | 0.31%   |
| 1TB                 | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 520       | 657    | 47.36%  |
| SSD     | 306       | 383    | 27.87%  |
| HDD     | 201       | 223    | 18.31%  |
| MMC     | 57        | 73     | 5.19%   |
| Unknown | 14        | 14     | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 520       | 657    | 49.43%  |
| SATA | 437       | 574    | 41.54%  |
| MMC  | 57        | 73     | 5.42%   |
| SAS  | 38        | 46     | 3.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 330       | 389    | 64.83%  |
| 0.51-1.0   | 151       | 180    | 29.67%  |
| 1.01-2.0   | 21        | 29     | 4.13%   |
| 3.01-4.0   | 6         | 7      | 1.18%   |
| 4.01-10.0  | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 200       | 21.57%  |
| 251-500        | 181       | 19.53%  |
| 1-20           | 143       | 15.43%  |
| 101-250        | 139       | 14.99%  |
| 1001-2000      | 98        | 10.57%  |
| Unknown        | 84        | 9.06%   |
| 51-100         | 38        | 4.1%    |
| More than 3000 | 20        | 2.16%   |
| 21-50          | 13        | 1.4%    |
| 2001-3000      | 11        | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 307       | 32.18%  |
| 21-50          | 165       | 17.3%   |
| 101-250        | 148       | 15.51%  |
| 51-100         | 101       | 10.59%  |
| Unknown        | 84        | 8.81%   |
| 251-500        | 80        | 8.39%   |
| 501-1000       | 46        | 4.82%   |
| 1001-2000      | 20        | 2.1%    |
| More than 3000 | 2         | 0.21%   |
| 2001-3000      | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 2         | 2      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 4      | 5.56%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1      | 2.78%   |
| WDC WD1600BEVT-24A23T0 160GB                        | 1         | 1      | 2.78%   |
| WDC WD1600BEVS-60RST0 160GB                         | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD050V 500GB                           | 1         | 1      | 2.78%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1         | 1      | 2.78%   |
| Teclast 360GB A850 SSD                              | 1         | 1      | 2.78%   |
| SK Hynix SC308 SATA 256GB SSD                       | 1         | 1      | 2.78%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 2.78%   |
| Seagate ST95005620AS 500GB                          | 1         | 1      | 2.78%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 2.78%   |
| Samsung Electronics MZNLH256HAJD-000H1 256GB SSD    | 1         | 1      | 2.78%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.78%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD    | 1         | 1      | 2.78%   |
| PLEXTOR PX-256M8PeG 256GB                           | 1         | 1      | 2.78%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2      | 2.78%   |
| LITEON CV3-CE256 256GB SSD                          | 1         | 1      | 2.78%   |
| Intel SSDSCKKF256G8H 256GB                          | 1         | 1      | 2.78%   |
| Intel SSDSC2CT240A3 240GB                           | 1         | 1      | 2.78%   |
| Intel SSDSC2BF180A5L 180GB                          | 1         | 1      | 2.78%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.78%   |
| Hitachi HTS545025B9SA02 250GB                       | 1         | 1      | 2.78%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 1      | 2.78%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.78%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.78%   |
| Crucial CT240BX500SSD1 240GB                        | 1         | 1      | 2.78%   |
| Crucial CT1050MX300SSD1 1050GB                      | 1         | 1      | 2.78%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 2.78%   |
| A-DATA Technology IM2S3138E-128GM-B 128GB SSD       | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 19.44%  |
| Toshiba             | 4         | 4      | 11.11%  |
| Samsung Electronics | 4         | 4      | 11.11%  |
| WDC                 | 3         | 3      | 8.33%   |
| Intel               | 3         | 3      | 8.33%   |
| Hitachi             | 3         | 3      | 8.33%   |
| Crucial             | 3         | 3      | 8.33%   |
| SK Hynix            | 2         | 2      | 5.56%   |
| HGST                | 2         | 2      | 5.56%   |
| Teclast             | 1         | 1      | 2.78%   |
| PLEXTOR             | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 2      | 2.78%   |
| LITEON              | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 9      | 38.89%  |
| WDC     | 3         | 3      | 16.67%  |
| Toshiba | 3         | 3      | 16.67%  |
| Hitachi | 3         | 3      | 16.67%  |
| HGST    | 2         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 20     | 50%     |
| SSD  | 16        | 17     | 44.44%  |
| NVMe | 2         | 2      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 500       | 735    | 50.92%  |
| Works    | 445       | 575    | 45.32%  |
| Malfunc  | 36        | 39     | 3.67%   |
| Failed   | 1         | 1      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 529       | 45.33%  |
| Samsung Electronics              | 182       | 15.6%   |
| AMD                              | 107       | 9.17%   |
| Sandisk                          | 95        | 8.14%   |
| SK Hynix                         | 69        | 5.91%   |
| Toshiba America Info Systems     | 41        | 3.51%   |
| Micron Technology                | 27        | 2.31%   |
| KIOXIA                           | 26        | 2.23%   |
| Kingston Technology Company      | 15        | 1.29%   |
| Phison Electronics               | 14        | 1.2%    |
| Silicon Motion                   | 12        | 1.03%   |
| ADATA Technology                 | 12        | 1.03%   |
| Union Memory (Shenzhen)          | 6         | 0.51%   |
| Nvidia                           | 6         | 0.51%   |
| Lite-On Technology               | 5         | 0.43%   |
| Apple                            | 4         | 0.34%   |
| Realtek Semiconductor            | 3         | 0.26%   |
| Micron/Crucial Technology        | 3         | 0.26%   |
| Yangtze Memory Technologies      | 2         | 0.17%   |
| Solid State Storage Technology   | 2         | 0.17%   |
| Marvell Technology Group         | 2         | 0.17%   |
| Lenovo                           | 2         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| JMicron Technology               | 1         | 0.09%   |
| Beijing Starblaze Technology     | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 101       | 8.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 95        | 7.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 90        | 7.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 54        | 4.43%   |
| Samsung NVMe SSD Controller 980                                                  | 50        | 4.1%    |
| Intel Volume Management Device NVMe RAID Controller                              | 43        | 3.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 33        | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 33        | 2.7%    |
| SK Hynix Gold P31 SSD                                                            | 31        | 2.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 31        | 2.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 30        | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 2.46%   |
| Micron Non-Volatile memory controller                                            | 27        | 2.21%   |
| KIOXIA Non-Volatile memory controller                                            | 26        | 2.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 24        | 1.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 22        | 1.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 21        | 1.72%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 21        | 1.72%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 21        | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 21        | 1.72%   |
| Sandisk Non-Volatile memory controller                                           | 17        | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 17        | 1.39%   |
| SK Hynix Non-Volatile memory controller                                          | 15        | 1.23%   |
| Intel SSD 660P Series                                                            | 15        | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 12        | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 11        | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 11        | 0.9%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 10        | 0.82%   |
| Intel Non-Volatile memory controller                                             | 10        | 0.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 10        | 0.82%   |
| SK Hynix BC511                                                                   | 9         | 0.74%   |
| Phison PS5013 E13 NVMe Controller                                                | 9         | 0.74%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 8         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 8         | 0.66%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 8         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.66%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 7         | 0.57%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 7         | 0.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 0.57%   |
| ADATA Non-Volatile memory controller                                             | 7         | 0.57%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 6         | 0.49%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6         | 0.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 6         | 0.49%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 5         | 0.41%   |
| Sandisk PC SN520 NVMe SSD                                                        | 5         | 0.41%   |
| Samsung Apple PCIe SSD                                                           | 5         | 0.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.41%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 5         | 0.41%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 4         | 0.33%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.33%   |
| Samsung Electronics SATA controller                                              | 4         | 0.33%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.33%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 4         | 0.33%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 0.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 560       | 47.74%  |
| NVMe | 518       | 44.16%  |
| RAID | 80        | 6.82%   |
| IDE  | 15        | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 724       | 78.7%   |
| AMD    | 195       | 21.2%   |
| ARM    | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 35        | 3.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 32        | 3.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 2.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 17        | 1.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 1.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 16        | 1.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 1.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 1.52%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 1.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 1.2%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.09%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 10        | 1.09%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 9         | 0.98%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 0.98%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 9         | 0.98%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 8         | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.87%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 8         | 0.87%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 8         | 0.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.87%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 7         | 0.76%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 7         | 0.76%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 7         | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.76%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.76%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 0.65%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.65%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.65%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 0.65%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.65%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.65%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.65%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 5         | 0.54%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 5         | 0.54%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 5         | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.54%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.54%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.54%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 0.54%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 5         | 0.54%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 0.54%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 5         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 275       | 29.89%  |
| Intel Core i5           | 188       | 20.43%  |
| Other                   | 109       | 11.85%  |
| Intel Core i3           | 65        | 7.07%   |
| AMD Ryzen 7             | 61        | 6.63%   |
| AMD Ryzen 5             | 59        | 6.41%   |
| Intel Celeron           | 25        | 2.72%   |
| Intel Core 2 Duo        | 17        | 1.85%   |
| AMD Ryzen 9             | 17        | 1.85%   |
| Intel Core i9           | 11        | 1.2%    |
| Intel Atom              | 11        | 1.2%    |
| AMD Ryzen 7 PRO         | 11        | 1.2%    |
| AMD Ryzen 3             | 10        | 1.09%   |
| Intel Pentium           | 9         | 0.98%   |
| Intel Pentium Silver    | 5         | 0.54%   |
| AMD Ryzen 5 PRO         | 5         | 0.54%   |
| AMD Athlon              | 4         | 0.43%   |
| AMD A6                  | 4         | 0.43%   |
| AMD A4                  | 4         | 0.43%   |
| AMD A10                 | 4         | 0.43%   |
| AMD E                   | 3         | 0.33%   |
| AMD A8                  | 3         | 0.33%   |
| Intel Xeon              | 2         | 0.22%   |
| Intel Pentium Dual-Core | 2         | 0.22%   |
| Intel Pentium Dual      | 2         | 0.22%   |
| Intel Core m3           | 2         | 0.22%   |
| AMD E2                  | 2         | 0.22%   |
| Intel Genuine           | 1         | 0.11%   |
| Intel Core m7           | 1         | 0.11%   |
| Intel Core m5           | 1         | 0.11%   |
| Intel Core M            | 1         | 0.11%   |
| AMD Ryzen 3 PRO         | 1         | 0.11%   |
| AMD PRO A10             | 1         | 0.11%   |
| AMD Phenom II           | 1         | 0.11%   |
| AMD E1                  | 1         | 0.11%   |
| AMD C-60                | 1         | 0.11%   |
| AMD Athlon II           | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 389       | 42.28%  |
| 2      | 324       | 35.22%  |
| 8      | 99        | 10.76%  |
| 6      | 99        | 10.76%  |
| 14     | 2         | 0.22%   |
| 12     | 2         | 0.22%   |
| 10     | 2         | 0.22%   |
| 1      | 2         | 0.22%   |
| 3      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 920       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 785       | 85.33%  |
| 1      | 135       | 14.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 919       | 99.89%  |
| 64-bit         | 1         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 85        | 9.19%   |
| 0x806ec    | 67        | 7.24%   |
| 0x306a9    | 54        | 5.84%   |
| Unknown    | 52        | 5.62%   |
| 0x806ea    | 50        | 5.41%   |
| 0x806e9    | 40        | 4.32%   |
| 0x406e3    | 40        | 4.32%   |
| 0xa0652    | 37        | 4%      |
| 0x40651    | 37        | 4%      |
| 0x0a50000c | 35        | 3.78%   |
| 0x206a7    | 34        | 3.68%   |
| 0x906ea    | 32        | 3.46%   |
| 0x08600106 | 31        | 3.35%   |
| 0x306d4    | 25        | 2.7%    |
| 0x306c3    | 21        | 2.27%   |
| 0x08108109 | 20        | 2.16%   |
| 0x706e5    | 17        | 1.84%   |
| 0x08600104 | 16        | 1.73%   |
| 0x906ed    | 14        | 1.51%   |
| 0x08608103 | 14        | 1.51%   |
| 0x506e3    | 13        | 1.41%   |
| 0x08108102 | 13        | 1.41%   |
| 0x1067a    | 12        | 1.3%    |
| 0x906e9    | 11        | 1.19%   |
| 0x506c9    | 10        | 1.08%   |
| 0x20655    | 10        | 1.08%   |
| 0x806eb    | 9         | 0.97%   |
| 0x08608102 | 9         | 0.97%   |
| 0x806d1    | 8         | 0.86%   |
| 0x706a8    | 8         | 0.86%   |
| 0x30678    | 8         | 0.86%   |
| 0x406c4    | 7         | 0.76%   |
| 0x40661    | 5         | 0.54%   |
| 0x10676    | 5         | 0.54%   |
| 0x08600103 | 5         | 0.54%   |
| 0x06001119 | 5         | 0.54%   |
| 0x706a1    | 4         | 0.43%   |
| 0x6fd      | 4         | 0.43%   |
| 0x906c0    | 3         | 0.32%   |
| 0x806c2    | 3         | 0.32%   |
| 0x20652    | 3         | 0.32%   |
| 0x0a404101 | 3         | 0.32%   |
| 0x08701013 | 3         | 0.32%   |
| 0x0810100b | 3         | 0.32%   |
| 0x07030105 | 3         | 0.32%   |
| 0x0700010b | 3         | 0.32%   |
| 0x06006705 | 3         | 0.32%   |
| 0x05000101 | 3         | 0.32%   |
| 0xa0660    | 2         | 0.22%   |
| 0xa0655    | 2         | 0.22%   |
| 0x906a3    | 2         | 0.22%   |
| 0x406c3    | 2         | 0.22%   |
| 0x0a50000b | 2         | 0.22%   |
| 0x08600102 | 2         | 0.22%   |
| 0x08101016 | 2         | 0.22%   |
| 0x07030106 | 2         | 0.22%   |
| 0x0600611a | 2         | 0.22%   |
| 0x906eb    | 1         | 0.11%   |
| 0x6fa      | 1         | 0.11%   |
| 0x106ca    | 1         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 234       | 25.43%  |
| TigerLake        | 95        | 10.33%  |
| Haswell          | 67        | 7.28%   |
| Zen 2            | 61        | 6.63%   |
| Skylake          | 59        | 6.41%   |
| IvyBridge        | 56        | 6.09%   |
| CometLake        | 44        | 4.78%   |
| Zen 3            | 39        | 4.24%   |
| SandyBridge      | 36        | 3.91%   |
| Zen+             | 35        | 3.8%    |
| Unknown          | 29        | 3.15%   |
| IceLake          | 25        | 2.72%   |
| Broadwell        | 25        | 2.72%   |
| Silvermont       | 18        | 1.96%   |
| Penryn           | 17        | 1.85%   |
| Westmere         | 14        | 1.52%   |
| Goldmont plus    | 12        | 1.3%    |
| Goldmont         | 10        | 1.09%   |
| Zen              | 7         | 0.76%   |
| Puma             | 5         | 0.54%   |
| Piledriver       | 5         | 0.54%   |
| Excavator        | 5         | 0.54%   |
| Core             | 5         | 0.54%   |
| Bobcat           | 4         | 0.43%   |
| Tremont          | 3         | 0.33%   |
| Jaguar           | 3         | 0.33%   |
| K10 Llano        | 2         | 0.22%   |
| K10              | 2         | 0.22%   |
| Alderlake Hybrid | 2         | 0.22%   |
| Bonnell          | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 681       | 56.84%  |
| Nvidia                           | 285       | 23.79%  |
| AMD                              | 231       | 19.28%  |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 86        | 7.07%   |
| AMD Renoir                                                                               | 57        | 4.68%   |
| Intel UHD Graphics 620                                                                   | 53        | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 51        | 4.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 3.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 3.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 2.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 36        | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 35        | 2.88%   |
| Intel HD Graphics 620                                                                    | 35        | 2.88%   |
| AMD Cezanne                                                                              | 35        | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 2.3%    |
| AMD Lucienne                                                                             | 24        | 1.97%   |
| Intel HD Graphics 5500                                                                   | 21        | 1.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 17        | 1.4%    |
| Intel HD Graphics 530                                                                    | 13        | 1.07%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 12        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.99%   |
| Intel HD Graphics 630                                                                    | 12        | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 11        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.9%    |
| Nvidia TU117M                                                                            | 10        | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 0.82%   |
| Nvidia GP108M [GeForce MX250]                                                            | 9         | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 0.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.66%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.58%   |
| Intel Tiger Lake UHD Graphics                                                            | 7         | 0.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.58%   |
| Intel Iris Plus Graphics G7                                                              | 7         | 0.58%   |
| Intel HD Graphics 500                                                                    | 7         | 0.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 6         | 0.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 6         | 0.49%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 6         | 0.49%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.49%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 6         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 5         | 0.41%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 5         | 0.41%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 5         | 0.41%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.41%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.41%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.41%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 4         | 0.33%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 0.33%   |
| Intel HD Graphics 615                                                                    | 4         | 0.33%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 4         | 0.33%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.25%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 3         | 0.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 434       | 47.17%  |
| Intel + Nvidia | 214       | 23.26%  |
| 1 x AMD        | 152       | 16.52%  |
| 1 x Nvidia     | 38        | 4.13%   |
| AMD + Nvidia   | 33        | 3.59%   |
| Intel + AMD    | 29        | 3.15%   |
| 2 x AMD        | 16        | 1.74%   |
| Other          | 3         | 0.33%   |
| 1 x SiS        | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 773       | 83.57%  |
| Proprietary | 143       | 15.46%  |
| Unknown     | 9         | 0.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 581       | 62.61%  |
| 0.01-0.5   | 117       | 12.61%  |
| 1.01-2.0   | 115       | 12.39%  |
| 3.01-4.0   | 48        | 5.17%   |
| 0.51-1.0   | 35        | 3.77%   |
| 7.01-8.0   | 14        | 1.51%   |
| 5.01-6.0   | 9         | 0.97%   |
| 8.01-16.0  | 7         | 0.75%   |
| 2.01-3.0   | 2         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 187       | 16.5%   |
| Chimei Innolux          | 169       | 14.92%  |
| BOE                     | 165       | 14.56%  |
| LG Display              | 150       | 13.24%  |
| Samsung Electronics     | 78        | 6.88%   |
| Sharp                   | 59        | 5.21%   |
| Dell                    | 58        | 5.12%   |
| Apple                   | 37        | 3.27%   |
| Goldstar                | 31        | 2.74%   |
| Lenovo                  | 26        | 2.29%   |
| PANDA                   | 18        | 1.59%   |
| Philips                 | 15        | 1.32%   |
| Hewlett-Packard         | 15        | 1.32%   |
| CSO                     | 14        | 1.24%   |
| InfoVision              | 13        | 1.15%   |
| Acer                    | 13        | 1.15%   |
| AOC                     | 12        | 1.06%   |
| BenQ                    | 11        | 0.97%   |
| Chi Mei Optoelectronics | 10        | 0.88%   |
| Ancor Communications    | 7         | 0.62%   |
| TMX                     | 6         | 0.53%   |
| Iiyama                  | 4         | 0.35%   |
| ASUSTek Computer        | 4         | 0.35%   |
| ViewSonic               | 3         | 0.26%   |
| MSI                     | 3         | 0.26%   |
| InnoLux Display         | 3         | 0.26%   |
| Sony                    | 2         | 0.18%   |
| Panasonic               | 2         | 0.18%   |
| JRY                     | 2         | 0.18%   |
| Gigabyte Technology     | 2         | 0.18%   |
| Vizio                   | 1         | 0.09%   |
| Toshiba                 | 1         | 0.09%   |
| TIANMA XM               | 1         | 0.09%   |
| Targa Visionary         | 1         | 0.09%   |
| Sceptre Tech            | 1         | 0.09%   |
| ONN                     | 1         | 0.09%   |
| LGD                     | 1         | 0.09%   |
| JDI                     | 1         | 0.09%   |
| INX                     | 1         | 0.09%   |
| HUAWEI                  | 1         | 0.09%   |
| Hitachi                 | 1         | 0.09%   |
| CPT                     | 1         | 0.09%   |
| Compal                  | 1         | 0.09%   |
| AGO                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 1.38%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 10        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.69%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 7         | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 7         | 0.61%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 7         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 7         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 7         | 0.61%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 7         | 0.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 7         | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 7         | 0.61%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 6         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.52%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.52%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 6         | 0.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.52%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.43%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 5         | 0.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.43%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.43%   |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch                    | 5         | 0.43%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 5         | 0.43%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 4         | 0.35%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.35%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 4         | 0.35%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 4         | 0.35%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 4         | 0.35%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 4         | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 0.35%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 4         | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.35%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 4         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.35%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 4         | 0.35%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 4         | 0.35%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 4         | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 4         | 0.35%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 4         | 0.35%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 3         | 0.26%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 3         | 0.26%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 3         | 0.26%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 3         | 0.26%   |
| LG Display LCD Monitor LGD028E 1366x768 310x174mm 14.0-inch              | 3         | 0.26%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.26%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 3         | 0.26%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 3         | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 3         | 0.26%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 3         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 543       | 52.26%  |
| 1366x768 (WXGA)    | 189       | 18.19%  |
| 3840x2160 (4K)     | 67        | 6.45%   |
| 2560x1440 (QHD)    | 50        | 4.81%   |
| 1920x1200 (WUXGA)  | 29        | 2.79%   |
| 1600x900 (HD+)     | 27        | 2.6%    |
| 1280x800 (WXGA)    | 16        | 1.54%   |
| 2880x1800          | 14        | 1.35%   |
| 1440x900 (WXGA+)   | 14        | 1.35%   |
| 2560x1600          | 13        | 1.25%   |
| 3440x1440          | 10        | 0.96%   |
| 2256x1504          | 10        | 0.96%   |
| 2560x1080          | 8         | 0.77%   |
| 2160x1440          | 8         | 0.77%   |
| 3840x2400          | 7         | 0.67%   |
| 3200x1800 (QHD+)   | 6         | 0.58%   |
| 1680x1050 (WSXGA+) | 5         | 0.48%   |
| 2240x1400          | 3         | 0.29%   |
| 1280x1024 (SXGA)   | 3         | 0.29%   |
| 3200x2000          | 2         | 0.19%   |
| 3072x1920          | 2         | 0.19%   |
| 3000x2000          | 2         | 0.19%   |
| 2880x1920          | 2         | 0.19%   |
| 2160x1350          | 2         | 0.19%   |
| 3840x2560          | 1         | 0.1%    |
| 3840x1600          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 2736x1824          | 1         | 0.1%    |
| 1360x768           | 1         | 0.1%    |
| 1024x600           | 1         | 0.1%    |
| Unknown            | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 407       | 35.7%   |
| 13      | 218       | 19.12%  |
| 14      | 157       | 13.77%  |
| 27      | 59        | 5.18%   |
| 24      | 53        | 4.65%   |
| 17      | 46        | 4.04%   |
| 23      | 36        | 3.16%   |
| 12      | 32        | 2.81%   |
| 21      | 29        | 2.54%   |
| 34      | 16        | 1.4%    |
| 11      | 16        | 1.4%    |
| 16      | 13        | 1.14%   |
| 31      | 9         | 0.79%   |
| 40      | 6         | 0.53%   |
| 18      | 6         | 0.53%   |
| 19      | 4         | 0.35%   |
| Unknown | 4         | 0.35%   |
| 84      | 3         | 0.26%   |
| 26      | 3         | 0.26%   |
| 22      | 3         | 0.26%   |
| 20      | 3         | 0.26%   |
| 10      | 3         | 0.26%   |
| 35      | 2         | 0.18%   |
| 32      | 2         | 0.18%   |
| 28      | 2         | 0.18%   |
| 25      | 2         | 0.18%   |
| 54      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 673       | 59.45%  |
| 201-300     | 165       | 14.58%  |
| 501-600     | 139       | 12.28%  |
| 351-400     | 56        | 4.95%   |
| 401-500     | 42        | 3.71%   |
| 601-700     | 19        | 1.68%   |
| 701-800     | 18        | 1.59%   |
| 801-900     | 9         | 0.8%    |
| Unknown     | 4         | 0.35%   |
| 1501-2000   | 3         | 0.27%   |
| 1001-1500   | 2         | 0.18%   |
| 901-1000    | 2         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 793       | 83.12%  |
| 16/10   | 109       | 11.43%  |
| 3/2     | 26        | 2.73%   |
| 21/9    | 19        | 1.99%   |
| 5/4     | 3         | 0.31%   |
| Unknown | 2         | 0.21%   |
| 4/3     | 1         | 0.1%    |
| 32/9    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 410       | 35.96%  |
| 81-90          | 288       | 25.26%  |
| 201-250        | 101       | 8.86%   |
| 71-80          | 89        | 7.81%   |
| 301-350        | 60        | 5.26%   |
| 121-130        | 45        | 3.95%   |
| 351-500        | 32        | 2.81%   |
| 61-70          | 30        | 2.63%   |
| 251-300        | 21        | 1.84%   |
| 51-60          | 16        | 1.4%    |
| 151-200        | 12        | 1.05%   |
| 111-120        | 10        | 0.88%   |
| 501-1000       | 10        | 0.88%   |
| More than 1000 | 4         | 0.35%   |
| 141-150        | 4         | 0.35%   |
| Unknown        | 4         | 0.35%   |
| 41-50          | 3         | 0.26%   |
| 131-140        | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 523       | 47.2%   |
| 101-120       | 220       | 19.86%  |
| 51-100        | 162       | 14.62%  |
| 161-240       | 138       | 12.45%  |
| More than 240 | 59        | 5.32%   |
| Unknown       | 4         | 0.36%   |
| 1-50          | 2         | 0.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 685       | 73.66%  |
| 2     | 195       | 20.97%  |
| 3     | 32        | 3.44%   |
| 0     | 17        | 1.83%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 550       | 38.87%  |
| Realtek Semiconductor             | 468       | 33.07%  |
| Qualcomm Atheros                  | 148       | 10.46%  |
| Broadcom                          | 63        | 4.45%   |
| MEDIATEK                          | 37        | 2.61%   |
| Lenovo                            | 20        | 1.41%   |
| Broadcom Limited                  | 17        | 1.2%    |
| Ralink                            | 12        | 0.85%   |
| ASIX Electronics                  | 10        | 0.71%   |
| Sierra Wireless                   | 9         | 0.64%   |
| DisplayLink                       | 9         | 0.64%   |
| Dell                              | 9         | 0.64%   |
| Qualcomm                          | 7         | 0.49%   |
| Marvell Technology Group          | 7         | 0.49%   |
| TP-Link                           | 6         | 0.42%   |
| Xiaomi                            | 5         | 0.35%   |
| Ralink Technology                 | 4         | 0.28%   |
| Nvidia                            | 4         | 0.28%   |
| Hewlett-Packard                   | 3         | 0.21%   |
| Ericsson Business Mobile Networks | 3         | 0.21%   |
| ASUSTek Computer                  | 3         | 0.21%   |
| OPPO Electronics                  | 2         | 0.14%   |
| NetGear                           | 2         | 0.14%   |
| Linksys                           | 2         | 0.14%   |
| Huawei Technologies               | 2         | 0.14%   |
| Fibocom                           | 2         | 0.14%   |
| Cypress Semiconductor             | 2         | 0.14%   |
| Spreadtrum Communications         | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.07%   |
| Shenzhen Goodix Technology        | 1         | 0.07%   |
| Samsung Electronics               | 1         | 0.07%   |
| Qualcomm Atheros Communications   | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| HMD Global                        | 1         | 0.07%   |
| D-Link                            | 1         | 0.07%   |
| Apple                             | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 285       | 16.81%  |
| Intel Wi-Fi 6 AX200                                               | 84        | 4.96%   |
| Intel Wi-Fi 6 AX201                                               | 65        | 3.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 3.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60        | 3.54%   |
| Intel Wireless 8265 / 8275                                        | 50        | 2.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 36        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 34        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.95%   |
| Intel Wireless 8260                                               | 33        | 1.95%   |
| Intel Wireless 7260                                               | 33        | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 30        | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 28        | 1.65%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 28        | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 27        | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.42%   |
| Intel Wireless 7265                                               | 21        | 1.24%   |
| Intel Wireless 3165                                               | 18        | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 18        | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 17        | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 0.77%   |
| Intel Wireless-AC 9260                                            | 13        | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.77%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 12        | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 12        | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 12        | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 11        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.47%   |
| Intel Ethernet Connection (6) I219-LM                             | 8         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.41%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.41%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.41%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 7         | 0.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 7         | 0.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 7         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.35%   |
| Realtek 802.11ac NIC                                              | 6         | 0.35%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 6         | 0.35%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.35%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 6         | 0.35%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.35%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 539       | 56.74%  |
| Qualcomm Atheros                | 133       | 14%     |
| Realtek Semiconductor           | 124       | 13.05%  |
| Broadcom                        | 53        | 5.58%   |
| MEDIATEK                        | 35        | 3.68%   |
| Broadcom Limited                | 14        | 1.47%   |
| Ralink                          | 12        | 1.26%   |
| Sierra Wireless                 | 9         | 0.95%   |
| Qualcomm                        | 6         | 0.63%   |
| Dell                            | 6         | 0.63%   |
| TP-Link                         | 4         | 0.42%   |
| Ralink Technology               | 4         | 0.42%   |
| ASUSTek Computer                | 3         | 0.32%   |
| NetGear                         | 2         | 0.21%   |
| Fibocom                         | 2         | 0.21%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 84        | 8.81%   |
| Intel Wi-Fi 6 AX201                                            | 65        | 6.82%   |
| Intel Wireless 8265 / 8275                                     | 50        | 5.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 36        | 3.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 34        | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 33        | 3.46%   |
| Intel Wireless 8260                                            | 33        | 3.46%   |
| Intel Wireless 7260                                            | 33        | 3.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 3.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 30        | 3.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28        | 2.94%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 28        | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 27        | 2.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24        | 2.52%   |
| Intel Wireless 7265                                            | 21        | 2.2%    |
| Intel Wireless 3165                                            | 18        | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 18        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 17        | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 1.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 1.36%   |
| Intel Wireless-AC 9260                                         | 13        | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 1.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 1.15%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 11        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 7         | 0.73%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 7         | 0.73%   |
| Realtek 802.11ac NIC                                           | 6         | 0.63%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 6         | 0.63%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 6         | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 0.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.52%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.52%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 4         | 0.42%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.42%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 4         | 0.42%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 0.31%   |
| Intel Wireless 3160                                            | 3         | 0.31%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.31%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.31%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 0.31%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.31%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.21%   |
| Sierra Wireless EM7455                                         | 2         | 0.21%   |
| Sierra Wireless EM7345 4G LTE                                  | 2         | 0.21%   |
| Sierra Wireless EM7305                                         | 2         | 0.21%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.21%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.21%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.21%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.21%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.21%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 410       | 57.42%  |
| Intel                            | 182       | 25.49%  |
| Qualcomm Atheros                 | 26        | 3.64%   |
| Broadcom                         | 22        | 3.08%   |
| Lenovo                           | 20        | 2.8%    |
| ASIX Electronics                 | 10        | 1.4%    |
| DisplayLink                      | 9         | 1.26%   |
| Marvell Technology Group         | 7         | 0.98%   |
| Xiaomi                           | 5         | 0.7%    |
| Nvidia                           | 4         | 0.56%   |
| Broadcom Limited                 | 3         | 0.42%   |
| TP-Link                          | 2         | 0.28%   |
| OPPO Electronics                 | 2         | 0.28%   |
| MediaTek                         | 2         | 0.28%   |
| Cypress Semiconductor            | 2         | 0.28%   |
| Spreadtrum Communications        | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Samsung Electronics              | 1         | 0.14%   |
| Qualcomm                         | 1         | 0.14%   |
| Motorola PCS                     | 1         | 0.14%   |
| Linksys                          | 1         | 0.14%   |
| HMD Global                       | 1         | 0.14%   |
| Apple                            | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 285       | 38.99%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 60        | 8.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 60        | 8.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 29        | 3.97%   |
| Intel Ethernet Connection (4) I219-LM                                          | 17        | 2.33%   |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.78%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 1.64%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 1.64%   |
| Intel Ethernet Connection I218-LM                                              | 11        | 1.5%    |
| Intel Ethernet Connection (7) I219-LM                                          | 11        | 1.5%    |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 1.5%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 10        | 1.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 8         | 1.09%   |
| Intel Ethernet Connection (6) I219-LM                                          | 8         | 1.09%   |
| Intel Ethernet Connection I219-V                                               | 7         | 0.96%   |
| Intel Ethernet Connection (13) I219-V                                          | 7         | 0.96%   |
| Intel Ethernet Connection (10) I219-V                                          | 7         | 0.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.82%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 0.68%   |
| Intel Ethernet Connection (11) I219-LM                                         | 5         | 0.68%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 0.68%   |
| DisplayLink Dell Universal Dock D6000                                          | 5         | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.68%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.55%   |
| Intel Ethernet Connection (13) I219-LM                                         | 4         | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 3         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.41%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.41%   |
| Lenovo USB-C Dock Ethernet                                                     | 3         | 0.41%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.41%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.41%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.27%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.27%   |
| OPPO realme X50 5G                                                             | 2         | 0.27%   |
| MediaTek Vodafone Smart N10                                                    | 2         | 0.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.27%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.27%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.27%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.27%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.27%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 0.27%   |
| Cypress K38231_03                                                              | 2         | 0.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.27%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe                        | 2         | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.14%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.14%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.14%   |
| Spreadtrum Unisoc Phone                                                        | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 905       | 57.03%  |
| Ethernet | 671       | 42.28%  |
| Modem    | 10        | 0.63%   |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 799       | 81.86%  |
| Ethernet | 177       | 18.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 588       | 63.91%  |
| 1     | 303       | 32.93%  |
| 0     | 18        | 1.96%   |
| 3     | 11        | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 706       | 75.83%  |
| Yes  | 225       | 24.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 462       | 58.19%  |
| Realtek Semiconductor           | 75        | 9.45%   |
| Qualcomm Atheros Communications | 61        | 7.68%   |
| Lite-On Technology              | 34        | 4.28%   |
| IMC Networks                    | 32        | 4.03%   |
| Apple                           | 31        | 3.9%    |
| Foxconn / Hon Hai               | 30        | 3.78%   |
| Broadcom                        | 21        | 2.64%   |
| Realtek                         | 15        | 1.89%   |
| Ralink                          | 11        | 1.39%   |
| Cambridge Silicon Radio         | 6         | 0.76%   |
| Dell                            | 5         | 0.63%   |
| ASUSTek Computer                | 4         | 0.5%    |
| MediaTek                        | 2         | 0.25%   |
| Hewlett-Packard                 | 2         | 0.25%   |
| Foxconn International           | 2         | 0.25%   |
| Alps Electric                   | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 146       | 18.39%  |
| Intel AX201 Bluetooth                                                               | 124       | 15.62%  |
| Intel AX200 Bluetooth                                                               | 82        | 10.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 62        | 7.81%   |
| Realtek Bluetooth Radio                                                             | 36        | 4.53%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 36        | 4.53%   |
| Apple Bluetooth Host Controller                                                     | 21        | 2.64%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 16        | 2.02%   |
| Intel AX210 Bluetooth                                                               | 16        | 2.02%   |
| Realtek Bluetooth Radio                                                             | 15        | 1.89%   |
| IMC Networks Wireless_Device                                                        | 15        | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 12        | 1.51%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 12        | 1.51%   |
| Ralink RT3290 Bluetooth                                                             | 11        | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.39%   |
| Realtek 802.11ac WLAN Adapter                                                       | 10        | 1.26%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 9         | 1.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 9         | 1.13%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 1.13%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 9         | 1.13%   |
| Lite-On Bluetooth Device                                                            | 8         | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.01%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.88%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 0.76%   |
| Lite-On Wireless_Device                                                             | 6         | 0.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.76%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 0.63%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 0.5%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.5%    |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.38%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 0.38%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.25%   |
| MediaTek Wireless_Device                                                            | 2         | 0.25%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.25%   |
| Intel Bluetooth Device                                                              | 2         | 0.25%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.25%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.25%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.25%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.25%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.25%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.25%   |
| ASUS ASUS USB-BT500                                                                 | 2         | 0.25%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.13%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.13%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.13%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.13%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.13%   |
| IMC Networks Bluetooth                                                              | 1         | 0.13%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.13%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.13%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.13%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 704       | 57.8%   |
| AMD                              | 208       | 17.08%  |
| Nvidia                           | 170       | 13.96%  |
| Lenovo                           | 19        | 1.56%   |
| C-Media Electronics              | 17        | 1.4%    |
| GN Netcom                        | 13        | 1.07%   |
| Realtek Semiconductor            | 12        | 0.99%   |
| SteelSeries ApS                  | 6         | 0.49%   |
| Plantronics                      | 6         | 0.49%   |
| Hewlett-Packard                  | 5         | 0.41%   |
| Logitech                         | 4         | 0.33%   |
| Kingston Technology              | 4         | 0.33%   |
| JMTek                            | 4         | 0.33%   |
| Texas Instruments                | 3         | 0.25%   |
| Razer USA                        | 3         | 0.25%   |
| Creative Technology              | 3         | 0.25%   |
| CMX Systems                      | 3         | 0.25%   |
| XMOS                             | 2         | 0.16%   |
| Sony                             | 2         | 0.16%   |
| Sennheiser Communications        | 2         | 0.16%   |
| RODE Microphones                 | 2         | 0.16%   |
| PreSonus Audio Electronics       | 2         | 0.16%   |
| Generalplus Technology           | 2         | 0.16%   |
| Apple                            | 2         | 0.16%   |
| Tenx Technology                  | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| SAVITECH                         | 1         | 0.08%   |
| Samson Technologies              | 1         | 0.08%   |
| Micronas                         | 1         | 0.08%   |
| Magic Control Technology         | 1         | 0.08%   |
| M-Audio                          | 1         | 0.08%   |
| GYROCOM C&C                      | 1         | 0.08%   |
| Fujitsu                          | 1         | 0.08%   |
| FIFINE Microphones               | 1         | 0.08%   |
| EDFIER                           | 1         | 0.08%   |
| Dell                             | 1         | 0.08%   |
| Corsair                          | 1         | 0.08%   |
| Cooler Master                    | 1         | 0.08%   |
| Conexant Systems                 | 1         | 0.08%   |
| BY EDIFIER                       | 1         | 0.08%   |
| Blue Microphones                 | 1         | 0.08%   |
| Barco Display Systems            | 1         | 0.08%   |
| Arturia                          | 1         | 0.08%   |
| A4Tech                           | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 156       | 10.6%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 138       | 9.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 101       | 6.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 95        | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 59        | 4.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 47        | 3.19%   |
| Intel Comet Lake PCH cAVS                                                                         | 42        | 2.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 41        | 2.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 40        | 2.72%   |
| Intel 8 Series HD Audio Controller                                                                | 40        | 2.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 39        | 2.65%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 38        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 2.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 28        | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 25        | 1.7%    |
| Intel Broadwell-U Audio Controller                                                                | 25        | 1.7%    |
| Nvidia Audio device                                                                               | 23        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 17        | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 1.09%   |
| AMD FCH Azalia Controller                                                                         | 16        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 13        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 13        | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 0.88%   |
| Realtek Semiconductor USB Audio                                                                   | 12        | 0.82%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 12        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 10        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 9         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 0.61%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 9         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.54%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 0.48%   |
| Nvidia TU104 HD Audio Controller                                                                  | 6         | 0.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 6         | 0.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 0.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.34%   |
| Hewlett-Packard USB Audio                                                                         | 5         | 0.34%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 0.34%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 0.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.27%   |
| JMTek USB PnP Audio Device                                                                        | 4         | 0.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.27%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 3         | 0.2%    |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 3         | 0.2%    |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.2%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.2%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.2%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.2%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 186       | 31%     |
| SK Hynix            | 122       | 20.33%  |
| Micron Technology   | 96        | 16%     |
| Kingston            | 46        | 7.67%   |
| Crucial             | 43        | 7.17%   |
| Unknown             | 27        | 4.5%    |
| Ramaxel Technology  | 13        | 2.17%   |
| A-DATA Technology   | 12        | 2%      |
| Elpida              | 7         | 1.17%   |
| Smart               | 6         | 1%      |
| Team                | 5         | 0.83%   |
| Corsair             | 5         | 0.83%   |
| Unknown (ABCD)      | 3         | 0.5%    |
| Transcend           | 3         | 0.5%    |
| Smart Brazil        | 3         | 0.5%    |
| G.Skill             | 3         | 0.5%    |
| Avant               | 3         | 0.5%    |
| Nanya Technology    | 2         | 0.33%   |
| Goldkey             | 2         | 0.33%   |
| Unknown             | 2         | 0.33%   |
| Unknown (0x7301)    | 1         | 0.17%   |
| RZX                 | 1         | 0.17%   |
| Qimonda             | 1         | 0.17%   |
| PUSKILL             | 1         | 0.17%   |
| Patriot             | 1         | 0.17%   |
| Miron               | 1         | 0.17%   |
| GOODRAM             | 1         | 0.17%   |
| fef5                | 1         | 0.17%   |
| CSX                 | 1         | 0.17%   |
| ASint Technology    | 1         | 0.17%   |
| AMD                 | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 2.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.88%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 1.41%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 1.26%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.26%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.26%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.94%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.94%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 0.94%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 5         | 0.78%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 5         | 0.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 5         | 0.78%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.78%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.78%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.78%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s    | 5         | 0.78%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 4         | 0.63%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 4         | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.63%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.63%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.63%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.63%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.63%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s       | 4         | 0.63%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 4         | 0.63%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.47%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.47%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 3         | 0.47%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.47%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.47%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.47%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.47%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 3         | 0.47%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                      | 3         | 0.47%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 3         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.47%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.47%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 3         | 0.47%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 3         | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.47%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.47%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 3         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.31%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 2         | 0.31%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 285       | 56.44%  |
| DDR3    | 126       | 24.95%  |
| LPDDR4  | 39        | 7.72%   |
| LPDDR3  | 37        | 7.33%   |
| DDR2    | 9         | 1.78%   |
| Unknown | 5         | 0.99%   |
| SDRAM   | 4         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 419       | 80.89%  |
| Row Of Chips | 88        | 16.99%  |
| Chip         | 7         | 1.35%   |
| DIMM         | 2         | 0.39%   |
| Unknown      | 2         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 241       | 44.14%  |
| 4096  | 146       | 26.74%  |
| 16384 | 91        | 16.67%  |
| 2048  | 40        | 7.33%   |
| 32768 | 20        | 3.66%   |
| 1024  | 8         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 141       | 26.21%  |
| 2667    | 118       | 21.93%  |
| 1600    | 91        | 16.91%  |
| 2133    | 36        | 6.69%   |
| 2400    | 35        | 6.51%   |
| 4267    | 22        | 4.09%   |
| 1867    | 16        | 2.97%   |
| 1334    | 12        | 2.23%   |
| 1333    | 11        | 2.04%   |
| 1067    | 10        | 1.86%   |
| 3266    | 8         | 1.49%   |
| 1066    | 6         | 1.12%   |
| 667     | 6         | 1.12%   |
| 4266    | 5         | 0.93%   |
| 3733    | 5         | 0.93%   |
| 4199    | 4         | 0.74%   |
| 4800    | 3         | 0.56%   |
| 800     | 3         | 0.56%   |
| 2933    | 2         | 0.37%   |
| 8400    | 1         | 0.19%   |
| 1866    | 1         | 0.19%   |
| 975     | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3200 Series         | 1         | 20%     |
| Samsung CLX-6260 Series         | 1         | 20%     |
| Prolific PL2305 Parallel Port   | 1         | 20%     |
| HP LaserJet 400 colorMFP M475dw | 1         | 20%     |
| Canon TR8500 series             | 1         | 20%     |

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
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 198       | 22.37%  |
| IMC Networks                           | 102       | 11.53%  |
| Realtek Semiconductor                  | 88        | 9.94%   |
| Acer                                   | 84        | 9.49%   |
| Microdia                               | 79        | 8.93%   |
| Quanta                                 | 59        | 6.67%   |
| Sunplus Innovation Technology          | 43        | 4.86%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 4.07%   |
| Logitech                               | 28        | 3.16%   |
| Syntek                                 | 25        | 2.82%   |
| Lite-On Technology                     | 24        | 2.71%   |
| Apple                                  | 24        | 2.71%   |
| Suyin                                  | 14        | 1.58%   |
| Luxvisions Innotech Limited            | 14        | 1.58%   |
| Silicon Motion                         | 8         | 0.9%    |
| Samsung Electronics                    | 8         | 0.9%    |
| Alcor Micro                            | 6         | 0.68%   |
| Ricoh                                  | 4         | 0.45%   |
| Lenovo                                 | 4         | 0.45%   |
| ARC International                      | 4         | 0.45%   |
| USB Camera                             | 3         | 0.34%   |
| Sonix Technology                       | 3         | 0.34%   |
| Primax Electronics                     | 3         | 0.34%   |
| Microsoft                              | 3         | 0.34%   |
| Generalplus Technology                 | 3         | 0.34%   |
| Tobii Technology AB                    | 2         | 0.23%   |
| MacroSilicon                           | 2         | 0.23%   |
| Importek                               | 2         | 0.23%   |
| WaveRider Communications               | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| Razer USA                              | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| Omnivision                             | 1         | 0.11%   |
| Foxconn / Hon Hai                      | 1         | 0.11%   |
| DLUPCA1RSFZKI5                         | 1         | 0.11%   |
| DigiTech                               | 1         | 0.11%   |
| Creative Technology                    | 1         | 0.11%   |
| ANYKA                                  | 1         | 0.11%   |
| ALi                                    | 1         | 0.11%   |
| 2M UVC CAMERA                          | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 67        | 7.52%   |
| Microdia Integrated_Webcam_HD                                   | 51        | 5.72%   |
| IMC Networks Integrated Camera                                  | 46        | 5.16%   |
| Realtek Integrated_Webcam_HD                                    | 33        | 3.7%    |
| Acer Integrated Camera                                          | 31        | 3.48%   |
| Quanta HD User Facing                                           | 21        | 2.36%   |
| Syntek Integrated Camera                                        | 20        | 2.24%   |
| Sunplus Integrated_Webcam_HD                                    | 20        | 2.24%   |
| Chicony HD WebCam                                               | 20        | 2.24%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 19        | 2.13%   |
| Lite-On HP HD Camera                                            | 12        | 1.35%   |
| Quanta HP TrueVision HD Camera                                  | 11        | 1.23%   |
| Chicony Integrated Camera (1280x720@30)                         | 11        | 1.23%   |
| Apple Built-in iSight                                           | 10        | 1.12%   |
| Acer HD Webcam                                                  | 9         | 1.01%   |
| Samsung Galaxy A5 (MTP)                                         | 8         | 0.9%    |
| Microdia Integrated Webcam                                      | 8         | 0.9%    |
| Logitech Webcam C270                                            | 8         | 0.9%    |
| IMC Networks HD Camera                                          | 8         | 0.9%    |
| Acer SunplusIT Integrated Camera                                | 8         | 0.9%    |
| Acer Lenovo EasyCamera                                          | 8         | 0.9%    |
| Acer BisonCam,NB Pro                                            | 8         | 0.9%    |
| Realtek Integrated Webcam                                       | 7         | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 7         | 0.79%   |
| Chicony USB2.0 Camera                                           | 7         | 0.79%   |
| Chicony HP HD Camera                                            | 7         | 0.79%   |
| Chicony HD User Facing                                          | 7         | 0.79%   |
| Realtek USB Camera                                              | 6         | 0.67%   |
| Realtek Laptop Camera                                           | 6         | 0.67%   |
| Realtek Integrated Webcam HD                                    | 6         | 0.67%   |
| Quanta HP HD Camera                                             | 6         | 0.67%   |
| Logitech HD Pro Webcam C920                                     | 6         | 0.67%   |
| Lite-On Integrated Camera                                       | 6         | 0.67%   |
| IMC Networks ov9734_azurewave_camera                            | 6         | 0.67%   |
| Chicony USB 2.0 Camera                                          | 6         | 0.67%   |
| Chicony HP Wide Vision HD Camera                                | 6         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 6         | 0.67%   |
| Apple FaceTime HD Camera                                        | 6         | 0.67%   |
| Sunplus HK 1080P K20Pro                                         | 5         | 0.56%   |
| Sunplus HD WebCam                                               | 5         | 0.56%   |
| Realtek Integrated Camera                                       | 5         | 0.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 5         | 0.56%   |
| Logitech C922 Pro Stream Webcam                                 | 5         | 0.56%   |
| Chicony USB2.0 HD UVC WebCam                                    | 5         | 0.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 5         | 0.56%   |
| Chicony HP TrueVision HD                                        | 5         | 0.56%   |
| Chicony EasyCamera                                              | 5         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 5         | 0.56%   |
| Apple FaceTime HD Camera (Built-in)                             | 5         | 0.56%   |
| Syntek EasyCamera                                               | 4         | 0.45%   |
| Suyin Integrated_Webcam_HD                                      | 4         | 0.45%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 4         | 0.45%   |
| Quanta VGA WebCam                                               | 4         | 0.45%   |
| Chicony ThinkPad T490 Webcam                                    | 4         | 0.45%   |
| Chicony Lenovo EasyCamera                                       | 4         | 0.45%   |
| Chicony HP HD Webcam                                            | 4         | 0.45%   |
| ARC International Camera                                        | 4         | 0.45%   |
| Alcor Micro SHUNCCM2MP                                          | 4         | 0.45%   |
| Acer BisonCam, NB Pro                                           | 4         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 85        | 38.46%  |
| Validity Sensors           | 58        | 26.24%  |
| Shenzhen Goodix Technology | 48        | 21.72%  |
| Elan Microelectronics      | 13        | 5.88%   |
| Upek                       | 7         | 3.17%   |
| LighTuning Technology      | 6         | 2.71%   |
| AuthenTec                  | 4         | 1.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 50        | 22.62%  |
| Shenzhen Goodix  Fingerprint Device                                        | 31        | 14.03%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 7.69%   |
| Unknown                                                                    | 13        | 5.88%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 5.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 4.07%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 3.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.71%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.71%   |
| Validity Sensors VFS491                                                    | 5         | 2.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.26%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.81%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.36%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.36%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.9%    |
| Synaptics  WBDI                                                            | 2         | 0.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.9%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.45%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.45%   |
| Synaptics WBDI Device                                                      | 1         | 0.45%   |
| AuthenTec AES2810                                                          | 1         | 0.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 37        | 46.25%  |
| Broadcom                  | 31        | 38.75%  |
| Lenovo                    | 4         | 5%      |
| Upek                      | 3         | 3.75%   |
| O2 Micro                  | 2         | 2.5%    |
| Hewlett-Packard           | 1         | 1.25%   |
| Gemalto (was Gemplus)     | 1         | 1.25%   |
| Aladdin Knowledge Systems | 1         | 1.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 46.25%  |
| Broadcom 58200                                                               | 11        | 13.75%  |
| Broadcom 5880                                                                | 8         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 8.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.75%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.5%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.25%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.25%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 547       | 58.5%   |
| 1     | 308       | 32.94%  |
| 2     | 67        | 7.17%   |
| 3     | 10        | 1.07%   |
| 4     | 2         | 0.21%   |
| 5     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 215       | 45.36%  |
| Graphics card            | 104       | 21.94%  |
| Multimedia controller    | 52        | 10.97%  |
| Net/wireless             | 37        | 7.81%   |
| Camera                   | 19        | 4.01%   |
| Bluetooth                | 15        | 3.16%   |
| Chipcard                 | 12        | 2.53%   |
| Card reader              | 7         | 1.48%   |
| Storage                  | 4         | 0.84%   |
| Network                  | 3         | 0.63%   |
| Net/ethernet             | 3         | 0.63%   |
| Communication controller | 2         | 0.42%   |
| Sound                    | 1         | 0.21%   |

