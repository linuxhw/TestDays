Linux in UK - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 6102

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6440              | [ad28c1e239](https://linux-hardware.org/?probe=ad28c1e239) | Nov 06, 2023 |
| HP            | ProBook 6470b               | [50c1d43281](https://linux-hardware.org/?probe=50c1d43281) | Nov 05, 2023 |
| HP            | 250 G5 Notebook PC          | [7b281cb925](https://linux-hardware.org/?probe=7b281cb925) | Nov 05, 2023 |
| Valve         | Jupiter                     | [28e2c2aa38](https://linux-hardware.org/?probe=28e2c2aa38) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [7a8597dd50](https://linux-hardware.org/?probe=7a8597dd50) | Nov 05, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [fc01ceb47b](https://linux-hardware.org/?probe=fc01ceb47b) | Nov 05, 2023 |
| Dell          | Inspiron 7501               | [0926c7cdad](https://linux-hardware.org/?probe=0926c7cdad) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [dc13d6012b](https://linux-hardware.org/?probe=dc13d6012b) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| HP            | Presario C500 (GF849EA#A... | [a4965dff09](https://linux-hardware.org/?probe=a4965dff09) | Nov 04, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [812ceefef6](https://linux-hardware.org/?probe=812ceefef6) | Nov 04, 2023 |
| Valve         | Jupiter                     | [af20418f73](https://linux-hardware.org/?probe=af20418f73) | Nov 04, 2023 |
| Valve         | Jupiter                     | [28f8f3e3cd](https://linux-hardware.org/?probe=28f8f3e3cd) | Nov 04, 2023 |
| HUAWEI        | MRGFG-XX                    | [5117a849b3](https://linux-hardware.org/?probe=5117a849b3) | Nov 03, 2023 |
| Dell          | Precision 5550              | [033e294199](https://linux-hardware.org/?probe=033e294199) | Nov 03, 2023 |
| Toshiba       | Satellite C660D             | [de50c92d6c](https://linux-hardware.org/?probe=de50c92d6c) | Nov 03, 2023 |
| Valve         | Jupiter                     | [b526accbcd](https://linux-hardware.org/?probe=b526accbcd) | Nov 03, 2023 |
| Dell          | Vostro 5590                 | [aa355fcc89](https://linux-hardware.org/?probe=aa355fcc89) | Nov 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [5d58dd522f](https://linux-hardware.org/?probe=5d58dd522f) | Nov 01, 2023 |
| Apple         | MacBook9,1                  | [44cec57d44](https://linux-hardware.org/?probe=44cec57d44) | Nov 01, 2023 |
| Apple         | MacBookAir5,1               | [d7b563a839](https://linux-hardware.org/?probe=d7b563a839) | Oct 31, 2023 |
| HP            | G56                         | [db44e7df47](https://linux-hardware.org/?probe=db44e7df47) | Oct 31, 2023 |
| Lenovo        | ThinkPad T530 24296JG       | [b443eebcad](https://linux-hardware.org/?probe=b443eebcad) | Oct 31, 2023 |
| Alienware     | 14                          | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [72131fb5de](https://linux-hardware.org/?probe=72131fb5de) | Oct 31, 2023 |
| HP            | Presario C500 (GF849EA#A... | [580f4bdb18](https://linux-hardware.org/?probe=580f4bdb18) | Oct 31, 2023 |
| Dell          | Latitude E5520              | [445903fc05](https://linux-hardware.org/?probe=445903fc05) | Oct 31, 2023 |
| Toshiba       | Satellite C660D             | [26479d99b9](https://linux-hardware.org/?probe=26479d99b9) | Oct 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [43772c58a4](https://linux-hardware.org/?probe=43772c58a4) | Oct 30, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| AWOW          | AK41                        | [bed4203da6](https://linux-hardware.org/?probe=bed4203da6) | Oct 30, 2023 |
| ASUSTek       | X551CA                      | [1a14a8f0c4](https://linux-hardware.org/?probe=1a14a8f0c4) | Oct 29, 2023 |
| ASUSTek       | X551CA                      | [a43802c314](https://linux-hardware.org/?probe=a43802c314) | Oct 29, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [7bdcd09429](https://linux-hardware.org/?probe=7bdcd09429) | Oct 29, 2023 |
| HP            | Pavilion g6                 | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Panasonic     | CF-191HA23DE                | [3ccc424983](https://linux-hardware.org/?probe=3ccc424983) | Oct 29, 2023 |
| Dell          | Precision M6800             | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| Dell          | Latitude E6500              | [41e90a6524](https://linux-hardware.org/?probe=41e90a6524) | Oct 28, 2023 |
| Dell          | Inspiron MM061              | [7545369484](https://linux-hardware.org/?probe=7545369484) | Oct 28, 2023 |
| Dell          | XPS 15 9560                 | [69a0449eee](https://linux-hardware.org/?probe=69a0449eee) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6a8554304e](https://linux-hardware.org/?probe=6a8554304e) | Oct 27, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | [f74328fd58](https://linux-hardware.org/?probe=f74328fd58) | Oct 27, 2023 |
| Apple         | MacBookPro7,1               | [fe15ca03f2](https://linux-hardware.org/?probe=fe15ca03f2) | Oct 27, 2023 |
| Dell          | Inspiron 1501               | [2c88e089bb](https://linux-hardware.org/?probe=2c88e089bb) | Oct 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JKC... | [c9ba633d37](https://linux-hardware.org/?probe=c9ba633d37) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [311f057665](https://linux-hardware.org/?probe=311f057665) | Oct 26, 2023 |
| HP            | EliteBook 630 13.3 inch ... | [8f57ab5108](https://linux-hardware.org/?probe=8f57ab5108) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | [5b2aac75a9](https://linux-hardware.org/?probe=5b2aac75a9) | Oct 26, 2023 |
| AWOW          | AK41                        | [e40c573853](https://linux-hardware.org/?probe=e40c573853) | Oct 26, 2023 |
| Acer          | Aspire A514-55              | [4d1e460056](https://linux-hardware.org/?probe=4d1e460056) | Oct 25, 2023 |
| Acer          | Aspire A514-55              | [3a1de9e1d1](https://linux-hardware.org/?probe=3a1de9e1d1) | Oct 25, 2023 |
| Dell          | Precision 7550              | [b6f0ce0285](https://linux-hardware.org/?probe=b6f0ce0285) | Oct 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [2b1387ee7c](https://linux-hardware.org/?probe=2b1387ee7c) | Oct 24, 2023 |
| Toshiba       | Satellite NB10t-A-102       | [85f85dffbd](https://linux-hardware.org/?probe=85f85dffbd) | Oct 24, 2023 |
| Eii           | WSA116                      | [85da70314e](https://linux-hardware.org/?probe=85da70314e) | Oct 23, 2023 |
| Dell          | XPS 13 9300                 | [9d7ecc567c](https://linux-hardware.org/?probe=9d7ecc567c) | Oct 23, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [38823c0a55](https://linux-hardware.org/?probe=38823c0a55) | Oct 22, 2023 |
| Dell          | Inspiron 3501               | [084dd63188](https://linux-hardware.org/?probe=084dd63188) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [e503ffe188](https://linux-hardware.org/?probe=e503ffe188) | Oct 21, 2023 |
| Lenovo        | V330-14ARR 81B1             | [b80592c227](https://linux-hardware.org/?probe=b80592c227) | Oct 21, 2023 |
| Dell          | Latitude E6400              | [5e09b89469](https://linux-hardware.org/?probe=5e09b89469) | Oct 20, 2023 |
| ASUSTek       | X453MA                      | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| HP            | EliteBook 630 13.3 inch ... | [e1ed7c2ee4](https://linux-hardware.org/?probe=e1ed7c2ee4) | Oct 20, 2023 |
| Valve         | Jupiter                     | [fdbd97d08c](https://linux-hardware.org/?probe=fdbd97d08c) | Oct 20, 2023 |
| Novatech      | W9x0LU                      | [b6e3d3dfc9](https://linux-hardware.org/?probe=b6e3d3dfc9) | Oct 19, 2023 |
| HUAWEI        | HN-WX9X                     | [6fc8b26d2c](https://linux-hardware.org/?probe=6fc8b26d2c) | Oct 19, 2023 |
| HUAWEI        | HN-WX9X                     | [827a7bf56c](https://linux-hardware.org/?probe=827a7bf56c) | Oct 19, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [dae01ed766](https://linux-hardware.org/?probe=dae01ed766) | Oct 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [bc4cc061a2](https://linux-hardware.org/?probe=bc4cc061a2) | Oct 18, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| HP            | ProBook 645 G1              | [d1eeca057f](https://linux-hardware.org/?probe=d1eeca057f) | Oct 17, 2023 |
| Alienware     | m15                         | [34919bdeca](https://linux-hardware.org/?probe=34919bdeca) | Oct 17, 2023 |
| Dell          | Latitude 5490               | [d85f87c8b0](https://linux-hardware.org/?probe=d85f87c8b0) | Oct 17, 2023 |
| Dell          | G15 5515                    | [080e34562c](https://linux-hardware.org/?probe=080e34562c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [da0024090d](https://linux-hardware.org/?probe=da0024090d) | Oct 16, 2023 |
| Dell          | Latitude E6540              | [27875d6fe5](https://linux-hardware.org/?probe=27875d6fe5) | Oct 16, 2023 |
| Dell          | XPS 15 9500                 | [0dcdd0a6a6](https://linux-hardware.org/?probe=0dcdd0a6a6) | Oct 16, 2023 |
| Lenovo        | ThinkPad E565 20EY000XUK    | [b7cf6113c4](https://linux-hardware.org/?probe=b7cf6113c4) | Oct 16, 2023 |
| Dell          | Precision M6700             | [2fb2e2e9a5](https://linux-hardware.org/?probe=2fb2e2e9a5) | Oct 16, 2023 |
| Valve         | Jupiter                     | [d8ba22dd7f](https://linux-hardware.org/?probe=d8ba22dd7f) | Oct 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [386d015b42](https://linux-hardware.org/?probe=386d015b42) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| HUAWEI        | CREF-XX                     | [3d9bd14288](https://linux-hardware.org/?probe=3d9bd14288) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| Google        | Careena                     | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| ASUSTek       | K70IO                       | [e9d2ce541a](https://linux-hardware.org/?probe=e9d2ce541a) | Oct 13, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [d14e3ec320](https://linux-hardware.org/?probe=d14e3ec320) | Oct 13, 2023 |
| Dell          | Precision 3580              | [f2a080ed43](https://linux-hardware.org/?probe=f2a080ed43) | Oct 13, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [1b88716ae2](https://linux-hardware.org/?probe=1b88716ae2) | Oct 13, 2023 |
| Dell          | XPS 15 9530                 | [f5f02b30f0](https://linux-hardware.org/?probe=f5f02b30f0) | Oct 13, 2023 |
| Dell          | Precision 7520              | [de5b9c8fa1](https://linux-hardware.org/?probe=de5b9c8fa1) | Oct 13, 2023 |
| HUAWEI        | BOHL-WXX9                   | [85cc4b4c4a](https://linux-hardware.org/?probe=85cc4b4c4a) | Oct 12, 2023 |
| Dell          | Inspiron 3505               | [dad114bac6](https://linux-hardware.org/?probe=dad114bac6) | Oct 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f767f8dd4d](https://linux-hardware.org/?probe=f767f8dd4d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [6396467c6d](https://linux-hardware.org/?probe=6396467c6d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [18b3c9fef8](https://linux-hardware.org/?probe=18b3c9fef8) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [7c843b4c27](https://linux-hardware.org/?probe=7c843b4c27) | Oct 12, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [02c2fabd1e](https://linux-hardware.org/?probe=02c2fabd1e) | Oct 11, 2023 |
| Dell          | Precision 3571              | [ac3735cea4](https://linux-hardware.org/?probe=ac3735cea4) | Oct 11, 2023 |
| Dell          | Inspiron 15 3525            | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [b4db6e379a](https://linux-hardware.org/?probe=b4db6e379a) | Oct 10, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [162889c4a3](https://linux-hardware.org/?probe=162889c4a3) | Oct 10, 2023 |
| Dell          | Inspiron 13-7359            | [64ad406dc0](https://linux-hardware.org/?probe=64ad406dc0) | Oct 10, 2023 |
| HP            | ProBook 450 G7              | [5805e4a7cb](https://linux-hardware.org/?probe=5805e4a7cb) | Oct 10, 2023 |
| Valve         | Jupiter                     | [daeb359dfb](https://linux-hardware.org/?probe=daeb359dfb) | Oct 10, 2023 |
| AZW           | SEi                         | [ed42118987](https://linux-hardware.org/?probe=ed42118987) | Oct 10, 2023 |
| ASUSTek       | N75SL                       | [8d6fe1b102](https://linux-hardware.org/?probe=8d6fe1b102) | Oct 09, 2023 |
| Dell          | Inspiron 13-5378            | [ee7086c9da](https://linux-hardware.org/?probe=ee7086c9da) | Oct 09, 2023 |
| Toshiba       | Satellite Pro R50-B         | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [44aa7c21f9](https://linux-hardware.org/?probe=44aa7c21f9) | Oct 09, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [02a4135aff](https://linux-hardware.org/?probe=02a4135aff) | Oct 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [d6b0808093](https://linux-hardware.org/?probe=d6b0808093) | Oct 09, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [6ffcd3c463](https://linux-hardware.org/?probe=6ffcd3c463) | Oct 09, 2023 |
| MSI           | Katana GF66 11UG            | [0816e0912b](https://linux-hardware.org/?probe=0816e0912b) | Oct 09, 2023 |
| Acer          | Aspire A517-52              | [fbe223cc6d](https://linux-hardware.org/?probe=fbe223cc6d) | Oct 08, 2023 |
| Acer          | Aspire A517-52              | [2a51c0c510](https://linux-hardware.org/?probe=2a51c0c510) | Oct 08, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | [43f05c011e](https://linux-hardware.org/?probe=43f05c011e) | Oct 08, 2023 |
| Valve         | Jupiter                     | [83976ddca6](https://linux-hardware.org/?probe=83976ddca6) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| PC Special... | P65_P67RGRERA               | [c2779bc01c](https://linux-hardware.org/?probe=c2779bc01c) | Oct 08, 2023 |
| Valve         | Jupiter                     | [aa51056093](https://linux-hardware.org/?probe=aa51056093) | Oct 08, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7f27dfbc34](https://linux-hardware.org/?probe=7f27dfbc34) | Oct 07, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [2adab9deb5](https://linux-hardware.org/?probe=2adab9deb5) | Oct 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e087628f2a](https://linux-hardware.org/?probe=e087628f2a) | Oct 07, 2023 |
| Apple         | MacBookAir6,1               | [9bd895191b](https://linux-hardware.org/?probe=9bd895191b) | Oct 06, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [da6b1b88e6](https://linux-hardware.org/?probe=da6b1b88e6) | Oct 06, 2023 |
| Star Labs     | StarBook                    | [57a76a9d14](https://linux-hardware.org/?probe=57a76a9d14) | Oct 06, 2023 |
| Lenovo        | ThinkPad T430 2349STC       | [53e8d1302b](https://linux-hardware.org/?probe=53e8d1302b) | Oct 05, 2023 |
| Dell          | Latitude 7390               | [6204f328e3](https://linux-hardware.org/?probe=6204f328e3) | Oct 05, 2023 |
| Dell          | XPS 15 9560                 | [381be666c0](https://linux-hardware.org/?probe=381be666c0) | Oct 04, 2023 |
| Fujitsu Si... | LIFEBOOK T4215              | [392481b855](https://linux-hardware.org/?probe=392481b855) | Oct 04, 2023 |
| Sony          | SVE1511K1ESI                | [935bdcf05c](https://linux-hardware.org/?probe=935bdcf05c) | Oct 04, 2023 |
| Toshiba       | Satellite C50-A-1DV         | [190ce47896](https://linux-hardware.org/?probe=190ce47896) | Oct 03, 2023 |
| Toshiba       | Satellite C50-A-1DV         | [791e483369](https://linux-hardware.org/?probe=791e483369) | Oct 03, 2023 |
| Acer          | Aspire 5720                 | [6009fced37](https://linux-hardware.org/?probe=6009fced37) | Oct 03, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [fc95f3feef](https://linux-hardware.org/?probe=fc95f3feef) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3657d65cec](https://linux-hardware.org/?probe=3657d65cec) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | [57b94fa258](https://linux-hardware.org/?probe=57b94fa258) | Oct 02, 2023 |
| Dell          | Inspiron 3542               | [4e74bbc8e2](https://linux-hardware.org/?probe=4e74bbc8e2) | Oct 02, 2023 |
| Samsung       | 750XED                      | [33e2bf8845](https://linux-hardware.org/?probe=33e2bf8845) | Oct 02, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8cc4ccdbec](https://linux-hardware.org/?probe=8cc4ccdbec) | Oct 01, 2023 |
| Dell          | Inspiron 13-5378            | [c25e886d9d](https://linux-hardware.org/?probe=c25e886d9d) | Oct 01, 2023 |
| Dell          | XPS 15 9500                 | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| Acer          | Predator G9-793             | [fd305490af](https://linux-hardware.org/?probe=fd305490af) | Oct 01, 2023 |
| Valve         | Jupiter                     | [d64d0a1997](https://linux-hardware.org/?probe=d64d0a1997) | Sep 30, 2023 |
| Entroware     | Hybris                      | [5b124e9b7f](https://linux-hardware.org/?probe=5b124e9b7f) | Sep 30, 2023 |
| HP            | Pavilion dv5                | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Acer          | Aspire 7741                 | [80d27e2808](https://linux-hardware.org/?probe=80d27e2808) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [2afa933d2a](https://linux-hardware.org/?probe=2afa933d2a) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [a7a8e627cb](https://linux-hardware.org/?probe=a7a8e627cb) | Sep 30, 2023 |
| OEGStone      | C4100/C5100                 | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WY00    | [6a18fb9b21](https://linux-hardware.org/?probe=6a18fb9b21) | Sep 29, 2023 |
| Alienware     | m16 R1 AMD                  | [710a10efce](https://linux-hardware.org/?probe=710a10efce) | Sep 29, 2023 |
| Alienware     | x15 R1                      | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| Google        | Swanky                      | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | [cb2cbda84d](https://linux-hardware.org/?probe=cb2cbda84d) | Sep 28, 2023 |
| Dell          | Precision 3560              | [14af02a240](https://linux-hardware.org/?probe=14af02a240) | Sep 28, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dcf11408af](https://linux-hardware.org/?probe=dcf11408af) | Sep 28, 2023 |
| Valve         | Jupiter                     | [39bc0d89fe](https://linux-hardware.org/?probe=39bc0d89fe) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5M000    | [58ddf5337a](https://linux-hardware.org/?probe=58ddf5337a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| Dell          | Precision 5570              | [f00d32a04a](https://linux-hardware.org/?probe=f00d32a04a) | Sep 27, 2023 |
| Toshiba       | Satellite A200              | [6bdac98313](https://linux-hardware.org/?probe=6bdac98313) | Sep 27, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [9a3f695f09](https://linux-hardware.org/?probe=9a3f695f09) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [fb82c6e942](https://linux-hardware.org/?probe=fb82c6e942) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [c7ec123b46](https://linux-hardware.org/?probe=c7ec123b46) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| Valve         | Jupiter                     | [277f5aca9b](https://linux-hardware.org/?probe=277f5aca9b) | Sep 26, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| ASUSTek       | X551CA                      | [1fdceb9309](https://linux-hardware.org/?probe=1fdceb9309) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [47d912c5a9](https://linux-hardware.org/?probe=47d912c5a9) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [d2a926c703](https://linux-hardware.org/?probe=d2a926c703) | Sep 26, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [2568280c44](https://linux-hardware.org/?probe=2568280c44) | Sep 25, 2023 |
| Valve         | Jupiter                     | [7a64b4c44f](https://linux-hardware.org/?probe=7a64b4c44f) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS0EXOO    | [0818b5e737](https://linux-hardware.org/?probe=0818b5e737) | Sep 24, 2023 |
| HP            | ProBook 6545b               | [b0abb62083](https://linux-hardware.org/?probe=b0abb62083) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | [8b5b196475](https://linux-hardware.org/?probe=8b5b196475) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | [65d749c96e](https://linux-hardware.org/?probe=65d749c96e) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | [f4232cfca8](https://linux-hardware.org/?probe=f4232cfca8) | Sep 23, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [083c0510ac](https://linux-hardware.org/?probe=083c0510ac) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d3322d740d](https://linux-hardware.org/?probe=d3322d740d) | Sep 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [13a9f1d65a](https://linux-hardware.org/?probe=13a9f1d65a) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | [c84457748d](https://linux-hardware.org/?probe=c84457748d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | Pavilion g6                 | [c49107d782](https://linux-hardware.org/?probe=c49107d782) | Sep 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [e63d1ae740](https://linux-hardware.org/?probe=e63d1ae740) | Sep 22, 2023 |
| Dell          | XPS 15 9560                 | [a437fe8bcf](https://linux-hardware.org/?probe=a437fe8bcf) | Sep 21, 2023 |
| Toshiba       | Satellite L855              | [ee1cb0c5cc](https://linux-hardware.org/?probe=ee1cb0c5cc) | Sep 21, 2023 |
| ASUSTek       | X550CL                      | [6c2de2dfb8](https://linux-hardware.org/?probe=6c2de2dfb8) | Sep 21, 2023 |
| PC Special... | Ionico 16                   | [dd18901106](https://linux-hardware.org/?probe=dd18901106) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| ASUSTek       | X501A                       | [5045eb238f](https://linux-hardware.org/?probe=5045eb238f) | Sep 20, 2023 |
| Acer          | Swift SF314-512             | [5c5a2a36e2](https://linux-hardware.org/?probe=5c5a2a36e2) | Sep 20, 2023 |
| HP            | EliteBook 845 14 inch G9... | [35d24c31cf](https://linux-hardware.org/?probe=35d24c31cf) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| ASUSTek       | K52F                        | [8d4b7a978b](https://linux-hardware.org/?probe=8d4b7a978b) | Sep 19, 2023 |
| Dell          | Precision 5550              | [a1c163a7e2](https://linux-hardware.org/?probe=a1c163a7e2) | Sep 19, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| ASUSTek       | X550CL                      | [2d5c5ab820](https://linux-hardware.org/?probe=2d5c5ab820) | Sep 19, 2023 |
| Valve         | Jupiter                     | [7baec97424](https://linux-hardware.org/?probe=7baec97424) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Dell          | Precision 3581              | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Apple         | MacBookPro5,4               | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Unknown       | M17PRO                      | [ccf362f14d](https://linux-hardware.org/?probe=ccf362f14d) | Sep 17, 2023 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [612bda7c21](https://linux-hardware.org/?probe=612bda7c21) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| HP            | EliteBook 820 G4            | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | GS43VR 7RE                  | [d9893a35c8](https://linux-hardware.org/?probe=d9893a35c8) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | [9bfcaaa71a](https://linux-hardware.org/?probe=9bfcaaa71a) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | [bad46323d7](https://linux-hardware.org/?probe=bad46323d7) | Sep 16, 2023 |
| Dell          | XPS 9320                    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| Dell          | Latitude E5570              | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [2073aca95d](https://linux-hardware.org/?probe=2073aca95d) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [fa484cf261](https://linux-hardware.org/?probe=fa484cf261) | Sep 15, 2023 |
| Dell          | XPS 15 9560                 | [c1f02dd477](https://linux-hardware.org/?probe=c1f02dd477) | Sep 15, 2023 |
| Dell          | XPS 9320                    | [054584d248](https://linux-hardware.org/?probe=054584d248) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| Clevo         | P170EM                      | [ee87854652](https://linux-hardware.org/?probe=ee87854652) | Sep 14, 2023 |
| Dell          | Precision 7530              | [035a4eb568](https://linux-hardware.org/?probe=035a4eb568) | Sep 14, 2023 |
| Dell          | Latitude 7390               | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aea796bbd9](https://linux-hardware.org/?probe=aea796bbd9) | Sep 14, 2023 |
| Acer          | AOA150                      | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Dell          | Latitude 7390               | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | [255f6ba979](https://linux-hardware.org/?probe=255f6ba979) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| HP            | Pavilion Notebook           | [e4a14b2349](https://linux-hardware.org/?probe=e4a14b2349) | Sep 11, 2023 |
| ASUSTek       | N551JX                      | [8c034b254e](https://linux-hardware.org/?probe=8c034b254e) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [36c9a9e4d4](https://linux-hardware.org/?probe=36c9a9e4d4) | Sep 10, 2023 |
| HP            | 255 G7 Notebook PC          | [c5be1f9523](https://linux-hardware.org/?probe=c5be1f9523) | Sep 10, 2023 |
| Google        | Lillipup                    | [c3a892cdca](https://linux-hardware.org/?probe=c3a892cdca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [3021f551f4](https://linux-hardware.org/?probe=3021f551f4) | Sep 09, 2023 |
| Valve         | Jupiter                     | [249a085da0](https://linux-hardware.org/?probe=249a085da0) | Sep 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a03aa3f52d](https://linux-hardware.org/?probe=a03aa3f52d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fd38d07a69](https://linux-hardware.org/?probe=fd38d07a69) | Sep 08, 2023 |
| Apple         | MacBookPro10,1              | [81aab795b5](https://linux-hardware.org/?probe=81aab795b5) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [2614f063f8](https://linux-hardware.org/?probe=2614f063f8) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4fd02051b6](https://linux-hardware.org/?probe=4fd02051b6) | Sep 07, 2023 |
| Unknown       | Unknown                     | [16cb5e0d5b](https://linux-hardware.org/?probe=16cb5e0d5b) | Sep 06, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 20MD0014UK      | [428c816118](https://linux-hardware.org/?probe=428c816118) | Sep 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | [f24dc99222](https://linux-hardware.org/?probe=f24dc99222) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [8b44f9cbdc](https://linux-hardware.org/?probe=8b44f9cbdc) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [f50ce96f55](https://linux-hardware.org/?probe=f50ce96f55) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | [6ab6bec7be](https://linux-hardware.org/?probe=6ab6bec7be) | Sep 05, 2023 |
| Notebook      | NL5xNU                      | [306dab3d42](https://linux-hardware.org/?probe=306dab3d42) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | [7165368bfe](https://linux-hardware.org/?probe=7165368bfe) | Sep 04, 2023 |
| Dell          | Inspiron 5770               | [1f2c94fe31](https://linux-hardware.org/?probe=1f2c94fe31) | Sep 03, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS24300    | [a28d4357d8](https://linux-hardware.org/?probe=a28d4357d8) | Sep 03, 2023 |
| Dell          | Latitude E6410              | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| Dell          | Studio 1735                 | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| Framework     | Laptop                      | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [024e3beca4](https://linux-hardware.org/?probe=024e3beca4) | Sep 03, 2023 |
| Timi          | TM1613                      | [6acee9a858](https://linux-hardware.org/?probe=6acee9a858) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| Dell          | Vostro 3590                 | [9a914c816e](https://linux-hardware.org/?probe=9a914c816e) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| ASUSTek       | UX305CA                     | [2220cac066](https://linux-hardware.org/?probe=2220cac066) | Sep 01, 2023 |
| HUAWEI        | MACH-WX9                    | [6f761aa23b](https://linux-hardware.org/?probe=6f761aa23b) | Aug 31, 2023 |
| Dell          | XPS 15 9560                 | [cef6754cd9](https://linux-hardware.org/?probe=cef6754cd9) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| ASUSTek       | S500CA                      | [60d87bd79b](https://linux-hardware.org/?probe=60d87bd79b) | Aug 30, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [18f51f883e](https://linux-hardware.org/?probe=18f51f883e) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459BN8       | [38c0341384](https://linux-hardware.org/?probe=38c0341384) | Aug 30, 2023 |
| Dell          | XPS 15 9560                 | [a31df2b8fe](https://linux-hardware.org/?probe=a31df2b8fe) | Aug 30, 2023 |
| Dell          | Latitude 5290               | [0b4debc293](https://linux-hardware.org/?probe=0b4debc293) | Aug 30, 2023 |
| Lenovo        | G500 20236                  | [93f309e8ad](https://linux-hardware.org/?probe=93f309e8ad) | Aug 29, 2023 |
| Acer          | Aspire 5720                 | [36403a156e](https://linux-hardware.org/?probe=36403a156e) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [7d8714663f](https://linux-hardware.org/?probe=7d8714663f) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| Acer          | Aspire V5-471               | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [9f725ce1a7](https://linux-hardware.org/?probe=9f725ce1a7) | Aug 28, 2023 |
| Apple         | MacBookPro5,1               | [62464b6b0d](https://linux-hardware.org/?probe=62464b6b0d) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [c091e0bc8b](https://linux-hardware.org/?probe=c091e0bc8b) | Aug 28, 2023 |
| Dell          | Latitude E7240              | [1eab9b5f8d](https://linux-hardware.org/?probe=1eab9b5f8d) | Aug 28, 2023 |
| Valve         | Jupiter                     | [8a68ffe7b0](https://linux-hardware.org/?probe=8a68ffe7b0) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| Dell          | Latitude 7480               | [95f7cd5046](https://linux-hardware.org/?probe=95f7cd5046) | Aug 27, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [1e2c15f171](https://linux-hardware.org/?probe=1e2c15f171) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Studio 1737                 | [8e668fe167](https://linux-hardware.org/?probe=8e668fe167) | Aug 27, 2023 |
| ZOOSTORM      | 7200-9062A                  | [5ee843d3d1](https://linux-hardware.org/?probe=5ee843d3d1) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Acer          | Aspire V5-571               | [033994cebf](https://linux-hardware.org/?probe=033994cebf) | Aug 26, 2023 |
| Acer          | Aspire A515-56              | [53b787dc90](https://linux-hardware.org/?probe=53b787dc90) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Unknown       | Unknown                     | [dc1c907cda](https://linux-hardware.org/?probe=dc1c907cda) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Acer          | Aspire V3-571               | [376d5e8a22](https://linux-hardware.org/?probe=376d5e8a22) | Aug 25, 2023 |
| HUAWEI        | MACHR-WX9                   | [a8c4ca7aee](https://linux-hardware.org/?probe=a8c4ca7aee) | Aug 25, 2023 |
| Packard Be... | EasyNote TJ66               | [010fe56f65](https://linux-hardware.org/?probe=010fe56f65) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7355715562](https://linux-hardware.org/?probe=7355715562) | Aug 25, 2023 |
| Notebook      | NL5xNU                      | [116561b889](https://linux-hardware.org/?probe=116561b889) | Aug 25, 2023 |
| Lenovo        | ThinkPad T430 2349KAG       | [f2348b8eee](https://linux-hardware.org/?probe=f2348b8eee) | Aug 25, 2023 |
| PC Special... | Ionico 16                   | [78125c34b4](https://linux-hardware.org/?probe=78125c34b4) | Aug 25, 2023 |
| Sony          | SVF15A1M2ES                 | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Google        | Eldrid                      | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| Valve         | Jupiter                     | [98dce455d0](https://linux-hardware.org/?probe=98dce455d0) | Aug 24, 2023 |
| HP            | Laptop 17-cn0xxx            | [5b5a4fa5d9](https://linux-hardware.org/?probe=5b5a4fa5d9) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | AOD255                      | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [0005c7836c](https://linux-hardware.org/?probe=0005c7836c) | Aug 22, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | [fce52ede18](https://linux-hardware.org/?probe=fce52ede18) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | [9cd3fa37a0](https://linux-hardware.org/?probe=9cd3fa37a0) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [62cddb0954](https://linux-hardware.org/?probe=62cddb0954) | Aug 21, 2023 |
| Medion        | Akoya THE TOUCH 10          | [c121ae9a76](https://linux-hardware.org/?probe=c121ae9a76) | Aug 21, 2023 |
| Apple         | MacBookPro14,1              | [dc96aa9cee](https://linux-hardware.org/?probe=dc96aa9cee) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | [97a87f1178](https://linux-hardware.org/?probe=97a87f1178) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [cb1eebf517](https://linux-hardware.org/?probe=cb1eebf517) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [87d16e9431](https://linux-hardware.org/?probe=87d16e9431) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 14S           | [323664ecb8](https://linux-hardware.org/?probe=323664ecb8) | Aug 18, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [c9e9e56ddd](https://linux-hardware.org/?probe=c9e9e56ddd) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Dell          | XPS 15 9530                 | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Dell          | Inspiron 7370               | [2676762739](https://linux-hardware.org/?probe=2676762739) | Aug 16, 2023 |
| Acer          | Aspire V5-571               | [bb39a5a125](https://linux-hardware.org/?probe=bb39a5a125) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| Sony          | VPCEH3N6E                   | [884688ddbf](https://linux-hardware.org/?probe=884688ddbf) | Aug 15, 2023 |
| Samsung       | 755XDA                      | [3be32e2365](https://linux-hardware.org/?probe=3be32e2365) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Google        | Bobba360                    | [e2ae1afdcc](https://linux-hardware.org/?probe=e2ae1afdcc) | Aug 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [fe4612b027](https://linux-hardware.org/?probe=fe4612b027) | Aug 14, 2023 |
| Google        | Bobba360                    | [f211501fde](https://linux-hardware.org/?probe=f211501fde) | Aug 14, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| Dell          | XPS 15 9560                 | [2461c78ff0](https://linux-hardware.org/?probe=2461c78ff0) | Aug 13, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [cd8b4a2836](https://linux-hardware.org/?probe=cd8b4a2836) | Aug 13, 2023 |
| HP            | Pavilion dv5                | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS3320C    | [51f9e0c482](https://linux-hardware.org/?probe=51f9e0c482) | Aug 13, 2023 |
| Toshiba       | Satellite C50D-A-13G        | [e1a3542078](https://linux-hardware.org/?probe=e1a3542078) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| Acer          | Aspire A317-53              | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| HP            | Pavilion dv5                | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [f062831bd7](https://linux-hardware.org/?probe=f062831bd7) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [24629e2553](https://linux-hardware.org/?probe=24629e2553) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| Acer          | Aspire A317-53              | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Dell          | Inspiron 7537               | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Dell          | Latitude D630               | [a57bb7cde1](https://linux-hardware.org/?probe=a57bb7cde1) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [6738a625d8](https://linux-hardware.org/?probe=6738a625d8) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [66488bdd81](https://linux-hardware.org/?probe=66488bdd81) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| Acer          | Aspire 1825PTZ              | [553d2539fa](https://linux-hardware.org/?probe=553d2539fa) | Aug 07, 2023 |
| Acer          | Aspire A515-56              | [84b0c88b0a](https://linux-hardware.org/?probe=84b0c88b0a) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [de8e0fbde8](https://linux-hardware.org/?probe=de8e0fbde8) | Aug 07, 2023 |
| HP            | Laptop 15-da0xxx            | [0cb4da66e3](https://linux-hardware.org/?probe=0cb4da66e3) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| Dell          | Latitude 5411               | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [3e9ce860b6](https://linux-hardware.org/?probe=3e9ce860b6) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Unknown       | Unknown                     | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| Acer          | Aspire A515-56              | [dfe905b869](https://linux-hardware.org/?probe=dfe905b869) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Dell          | Latitude 5590               | [83d389e795](https://linux-hardware.org/?probe=83d389e795) | Aug 06, 2023 |
| Dell          | Venue 8 Pro 5855            | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Lenovo        | 100w Gen 3 82HY             | [3feb7899d2](https://linux-hardware.org/?probe=3feb7899d2) | Aug 05, 2023 |
| GPD           | G1621-02                    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| HP            | 470 G7 Notebook PC          | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a9072f3117](https://linux-hardware.org/?probe=a9072f3117) | Aug 04, 2023 |
| HP            | 255 G3                      | [c8b3db6b0b](https://linux-hardware.org/?probe=c8b3db6b0b) | Aug 03, 2023 |
| Acer          | Aspire 7750G                | [71f5ef03f9](https://linux-hardware.org/?probe=71f5ef03f9) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Valve         | Jupiter                     | [f928feaff9](https://linux-hardware.org/?probe=f928feaff9) | Aug 02, 2023 |
| Toshiba       | Satellite C660              | [5e74aca4e7](https://linux-hardware.org/?probe=5e74aca4e7) | Aug 02, 2023 |
| HP            | Pavilion 15                 | [c66316cd62](https://linux-hardware.org/?probe=c66316cd62) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| HP            | Pavilion 15                 | [1ad3dc2f1b](https://linux-hardware.org/?probe=1ad3dc2f1b) | Aug 01, 2023 |
| Lenovo        | Flex 2-14 20404             | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| HP            | ProBook 430 G3              | [a42e1c787e](https://linux-hardware.org/?probe=a42e1c787e) | Jul 30, 2023 |
| Valve         | Jupiter                     | [82e4fa2fbc](https://linux-hardware.org/?probe=82e4fa2fbc) | Jul 30, 2023 |
| HP            | ENVY Notebook               | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Razer         | Blade                       | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| Dell          | Latitude E6420              | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | [3486243fd6](https://linux-hardware.org/?probe=3486243fd6) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| Dell          | XPS 9320                    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Valve         | Jupiter                     | [ff714f1791](https://linux-hardware.org/?probe=ff714f1791) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro12,1              | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| Dell          | Latitude 3410               | [449e4c62f3](https://linux-hardware.org/?probe=449e4c62f3) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| Dell          | Inspiron 13-5378            | [cd318f6b75](https://linux-hardware.org/?probe=cd318f6b75) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Acer          | Aspire A515-56              | [7c716b6ab0](https://linux-hardware.org/?probe=7c716b6ab0) | Jul 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | [84ab2faa6f](https://linux-hardware.org/?probe=84ab2faa6f) | Jul 27, 2023 |
| PC Special... | Ionico 16                   | [5c91300246](https://linux-hardware.org/?probe=5c91300246) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Valve         | Jupiter                     | [1adda13639](https://linux-hardware.org/?probe=1adda13639) | Jul 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | [ee10ac6c06](https://linux-hardware.org/?probe=ee10ac6c06) | Jul 26, 2023 |
| HP            | Notebook                    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Dell          | Latitude 5530               | [cccd0bf0b8](https://linux-hardware.org/?probe=cccd0bf0b8) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| MSI           | Katana GF66 11UG            | [bd45023e8e](https://linux-hardware.org/?probe=bd45023e8e) | Jul 25, 2023 |
| Acer          | Swift SFE16-43              | [ada40722ae](https://linux-hardware.org/?probe=ada40722ae) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [e46d04faa8](https://linux-hardware.org/?probe=e46d04faa8) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [0b7f69aaf6](https://linux-hardware.org/?probe=0b7f69aaf6) | Jul 25, 2023 |
| Chuwi         | CoreBook Pro                | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Dell          | Inspiron 5570               | [3d08e59ce3](https://linux-hardware.org/?probe=3d08e59ce3) | Jul 24, 2023 |
| Dell          | Latitude 2110               | [05a7868709](https://linux-hardware.org/?probe=05a7868709) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| Gigabyte      | P17FR5                      | [817b78d77b](https://linux-hardware.org/?probe=817b78d77b) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | Notebook                    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | [e42f9111c6](https://linux-hardware.org/?probe=e42f9111c6) | Jul 23, 2023 |
| Dell          | XPS 15 9570                 | [9a62fe1979](https://linux-hardware.org/?probe=9a62fe1979) | Jul 22, 2023 |
| Valve         | Jupiter                     | [0e8e6ce1ae](https://linux-hardware.org/?probe=0e8e6ce1ae) | Jul 22, 2023 |
| Valve         | Jupiter                     | [fa8db9f24a](https://linux-hardware.org/?probe=fa8db9f24a) | Jul 22, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [c06811057a](https://linux-hardware.org/?probe=c06811057a) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| Dell          | System XPS L702X            | [21f1d68bc1](https://linux-hardware.org/?probe=21f1d68bc1) | Jul 21, 2023 |
| Apple         | MacBookAir7,1               | [e82f5072df](https://linux-hardware.org/?probe=e82f5072df) | Jul 20, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Acer          | Aspire A317-53              | [d8e84157ab](https://linux-hardware.org/?probe=d8e84157ab) | Jul 20, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e0b92a00b5](https://linux-hardware.org/?probe=e0b92a00b5) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV000YUK    | [0e89144534](https://linux-hardware.org/?probe=0e89144534) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| HP            | Laptop 15-dw0xxx            | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| Valve         | Jupiter                     | [3abdfed88b](https://linux-hardware.org/?probe=3abdfed88b) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| Valve         | Jupiter                     | [4beb3117df](https://linux-hardware.org/?probe=4beb3117df) | Jul 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a448a20876](https://linux-hardware.org/?probe=a448a20876) | Jul 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [958f57fd27](https://linux-hardware.org/?probe=958f57fd27) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| Dell          | Inspiron 1501               | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Acer          | Aspire A317-53              | [9dd235116d](https://linux-hardware.org/?probe=9dd235116d) | Jul 16, 2023 |
| Dell          | G5 5587                     | [fc861c593a](https://linux-hardware.org/?probe=fc861c593a) | Jul 16, 2023 |
| Acer          | Predator PH315-52           | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [35f3837811](https://linux-hardware.org/?probe=35f3837811) | Jul 16, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Acer          | Aspire A315-32              | [7044de848c](https://linux-hardware.org/?probe=7044de848c) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| HP            | Pavilion 15                 | [95f81cdf21](https://linux-hardware.org/?probe=95f81cdf21) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Dell          | XPS 13 9300                 | [ca425f6c38](https://linux-hardware.org/?probe=ca425f6c38) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| Notebook      | N150ZU                      | [61be22ac36](https://linux-hardware.org/?probe=61be22ac36) | Jul 14, 2023 |
| Dell          | Inspiron 15 3520            | [163766c886](https://linux-hardware.org/?probe=163766c886) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| Google        | Droid                       | [9b77a9ba04](https://linux-hardware.org/?probe=9b77a9ba04) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T0Q    | [0d5f86f700](https://linux-hardware.org/?probe=0d5f86f700) | Jul 13, 2023 |
| MSI           | GT70 2PE                    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd2c7b0c60](https://linux-hardware.org/?probe=dd2c7b0c60) | Jul 12, 2023 |
| Google        | Lillipup                    | [b7b430e7b4](https://linux-hardware.org/?probe=b7b430e7b4) | Jul 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [15067533b3](https://linux-hardware.org/?probe=15067533b3) | Jul 12, 2023 |
| HP            | EliteBook Folio 1040 G3     | [95c073864d](https://linux-hardware.org/?probe=95c073864d) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ad18a95d12](https://linux-hardware.org/?probe=ad18a95d12) | Jul 12, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9479004a7e](https://linux-hardware.org/?probe=9479004a7e) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [ad75f0a6e0](https://linux-hardware.org/?probe=ad75f0a6e0) | Jul 12, 2023 |
| Dell          | XPS 15 9530                 | [d78fb6bdd4](https://linux-hardware.org/?probe=d78fb6bdd4) | Jul 12, 2023 |
| HP            | 630                         | [671710637c](https://linux-hardware.org/?probe=671710637c) | Jul 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [90466d16ca](https://linux-hardware.org/?probe=90466d16ca) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| Sony          | SVP1321M2EB                 | [e767bbc26b](https://linux-hardware.org/?probe=e767bbc26b) | Jul 11, 2023 |
| Sony          | VPCZ214GX                   | [d63fc5c563](https://linux-hardware.org/?probe=d63fc5c563) | Jul 11, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [56de408d31](https://linux-hardware.org/?probe=56de408d31) | Jul 10, 2023 |
| Valve         | Jupiter                     | [5d55bf223d](https://linux-hardware.org/?probe=5d55bf223d) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96ca518dc6](https://linux-hardware.org/?probe=96ca518dc6) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| Apple         | MacBookPro10,1              | [43ec3cf70b](https://linux-hardware.org/?probe=43ec3cf70b) | Jul 09, 2023 |
| Dell          | XPS 15 9530                 | [513a03f793](https://linux-hardware.org/?probe=513a03f793) | Jul 08, 2023 |
| Apple         | MacBookPro10,1              | [ef7acb569d](https://linux-hardware.org/?probe=ef7acb569d) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [ffde5244e6](https://linux-hardware.org/?probe=ffde5244e6) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [2e2541c7a6](https://linux-hardware.org/?probe=2e2541c7a6) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [03f454349c](https://linux-hardware.org/?probe=03f454349c) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [bdc65d0c9f](https://linux-hardware.org/?probe=bdc65d0c9f) | Jul 05, 2023 |
| Lenovo        | ThinkPad T400 6474W7T       | [56144d66ac](https://linux-hardware.org/?probe=56144d66ac) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [bb0e10ceef](https://linux-hardware.org/?probe=bb0e10ceef) | Jul 05, 2023 |
| MSI           | GF75 Thin 9SC               | [b180548e9c](https://linux-hardware.org/?probe=b180548e9c) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d5b720740f](https://linux-hardware.org/?probe=d5b720740f) | Jul 04, 2023 |
| Valve         | Jupiter                     | [8b40767026](https://linux-hardware.org/?probe=8b40767026) | Jul 04, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | EliteBook 2540p             | [d69b1af76b](https://linux-hardware.org/?probe=d69b1af76b) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | [9c8f32ac20](https://linux-hardware.org/?probe=9c8f32ac20) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | [6c32038385](https://linux-hardware.org/?probe=6c32038385) | Jul 02, 2023 |
| Dell          | G3 3779                     | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| Alienware     | m16 R1 AMD                  | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| HP            | Stream Notebook PC 11       | [c1e18957a4](https://linux-hardware.org/?probe=c1e18957a4) | Jul 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e9f511bc00](https://linux-hardware.org/?probe=e9f511bc00) | Jul 01, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [8f38634e0e](https://linux-hardware.org/?probe=8f38634e0e) | Jul 01, 2023 |
| lapbook       | S15 PRO                     | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Toshiba       | Satellite Pro L650          | [d8da913f23](https://linux-hardware.org/?probe=d8da913f23) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| Valve         | Jupiter                     | [89d751f07f](https://linux-hardware.org/?probe=89d751f07f) | Jun 30, 2023 |
| HP            | Unknown                     | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [93e0628fbe](https://linux-hardware.org/?probe=93e0628fbe) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| Google        | Reef                        | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| HP            | ProBook 450 G2              | [2b47aff042](https://linux-hardware.org/?probe=2b47aff042) | Jun 28, 2023 |
| Lenovo        | ThinkPad X240 20AL007LUK    | [ee0761a131](https://linux-hardware.org/?probe=ee0761a131) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | [dc758ef355](https://linux-hardware.org/?probe=dc758ef355) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| Valve         | Jupiter                     | [f6d3a1e787](https://linux-hardware.org/?probe=f6d3a1e787) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [88baca047c](https://linux-hardware.org/?probe=88baca047c) | Jun 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Apple         | MacBook4,1                  | [fe27e643ac](https://linux-hardware.org/?probe=fe27e643ac) | Jun 26, 2023 |
| HP            | Unknown                     | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| Toshiba       | Satellite C650              | [54ef5b6567](https://linux-hardware.org/?probe=54ef5b6567) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| ASUSTek       | TP550LA                     | [7728203a8a](https://linux-hardware.org/?probe=7728203a8a) | Jun 22, 2023 |
| ASUSTek       | TP550LA                     | [fed72172d2](https://linux-hardware.org/?probe=fed72172d2) | Jun 22, 2023 |
| Medion        | Erazer P6661 MD60303        | [22fb03fe41](https://linux-hardware.org/?probe=22fb03fe41) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| Acer          | Aspire 5742Z                | [d1513c944e](https://linux-hardware.org/?probe=d1513c944e) | Jun 21, 2023 |
| HP            | Unknown                     | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| Dell          | Latitude E7450              | [4760bb7306](https://linux-hardware.org/?probe=4760bb7306) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| Alienware     | 17 R3                       | [45613f348f](https://linux-hardware.org/?probe=45613f348f) | Jun 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [53b1d3f262](https://linux-hardware.org/?probe=53b1d3f262) | Jun 20, 2023 |
| Dell          | Latitude 7390               | [98d09ed56c](https://linux-hardware.org/?probe=98d09ed56c) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| Dell          | Latitude 5430               | [1797038bf6](https://linux-hardware.org/?probe=1797038bf6) | Jun 17, 2023 |
| HP            | ENVY m6                     | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1b0dd608b2](https://linux-hardware.org/?probe=1b0dd608b2) | Jun 16, 2023 |
| GEO           | GEOBOOK 2E                  | [9ab9fe3052](https://linux-hardware.org/?probe=9ab9fe3052) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| Acer          | Aspire ES1-522              | [25f52202b2](https://linux-hardware.org/?probe=25f52202b2) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [89ac5ef04b](https://linux-hardware.org/?probe=89ac5ef04b) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| HP            | Unknown                     | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [9b67ef406b](https://linux-hardware.org/?probe=9b67ef406b) | Jun 14, 2023 |
| Google        | Ampton                      | [294fa26d20](https://linux-hardware.org/?probe=294fa26d20) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [448deb90fa](https://linux-hardware.org/?probe=448deb90fa) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | [e7f84bdb10](https://linux-hardware.org/?probe=e7f84bdb10) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | [7b3593a797](https://linux-hardware.org/?probe=7b3593a797) | Jun 13, 2023 |
| Lenovo        | IdeaPad Y580                | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [6dadff138b](https://linux-hardware.org/?probe=6dadff138b) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | Vostro 3550                 | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| Dell          | Latitude 5411               | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [f47c4b27fe](https://linux-hardware.org/?probe=f47c4b27fe) | Jun 13, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [40d06bae85](https://linux-hardware.org/?probe=40d06bae85) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [4c5907abd5](https://linux-hardware.org/?probe=4c5907abd5) | Jun 12, 2023 |
| Timi          | RedmiBook Pro 14            | [7b2e093b24](https://linux-hardware.org/?probe=7b2e093b24) | Jun 12, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [0b42de0b42](https://linux-hardware.org/?probe=0b42de0b42) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [5286f937d8](https://linux-hardware.org/?probe=5286f937d8) | Jun 11, 2023 |
| Valve         | Jupiter                     | [b7ffc34483](https://linux-hardware.org/?probe=b7ffc34483) | Jun 11, 2023 |
| Acer          | Aspire F5-571               | [e54e3157fc](https://linux-hardware.org/?probe=e54e3157fc) | Jun 11, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [777f28f9e8](https://linux-hardware.org/?probe=777f28f9e8) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| HP            | Pavilion g6                 | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| HP            | ProBook 4510s               | [43a29ea83e](https://linux-hardware.org/?probe=43a29ea83e) | Jun 09, 2023 |
| Dell          | XPS 13 9333                 | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Dell          | Inspiron 3583               | [adcb3b193a](https://linux-hardware.org/?probe=adcb3b193a) | Jun 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [50c36acc0d](https://linux-hardware.org/?probe=50c36acc0d) | Jun 09, 2023 |
| Lenovo        | Z50-70 20354                | [28a5b69096](https://linux-hardware.org/?probe=28a5b69096) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| HONOR         | NBR-WAX9                    | [697f2b18e8](https://linux-hardware.org/?probe=697f2b18e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [340054cdd5](https://linux-hardware.org/?probe=340054cdd5) | Jun 08, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [73fa9d854f](https://linux-hardware.org/?probe=73fa9d854f) | Jun 07, 2023 |
| Dell          | XPS 9320                    | [ff5fc17acc](https://linux-hardware.org/?probe=ff5fc17acc) | Jun 07, 2023 |
| Valve         | Jupiter                     | [27771c5ea8](https://linux-hardware.org/?probe=27771c5ea8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | [629a290a98](https://linux-hardware.org/?probe=629a290a98) | Jun 07, 2023 |
| Sony          | VPCEH3N6E                   | [788ddd35a8](https://linux-hardware.org/?probe=788ddd35a8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e4335c33f6](https://linux-hardware.org/?probe=e4335c33f6) | Jun 06, 2023 |
| Valve         | Jupiter                     | [99a7a5bd6e](https://linux-hardware.org/?probe=99a7a5bd6e) | Jun 06, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [413ef09459](https://linux-hardware.org/?probe=413ef09459) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [b969b91080](https://linux-hardware.org/?probe=b969b91080) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| MSI           | Katana GF66 11UG            | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | [5716ed966d](https://linux-hardware.org/?probe=5716ed966d) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | [a3d127e3ba](https://linux-hardware.org/?probe=a3d127e3ba) | Jun 04, 2023 |
| Dell          | Latitude E5520              | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | [fc6e3f084f](https://linux-hardware.org/?probe=fc6e3f084f) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| Dell          | Latitude 5420               | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | [a9c6f5e0e6](https://linux-hardware.org/?probe=a9c6f5e0e6) | Jun 04, 2023 |
| HP            | Notebook                    | [45553d6493](https://linux-hardware.org/?probe=45553d6493) | Jun 04, 2023 |
| Acer          | Aspire A317-53              | [406fc17c32](https://linux-hardware.org/?probe=406fc17c32) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| HP            | Pavilion 15                 | [dc8f67bb03](https://linux-hardware.org/?probe=dc8f67bb03) | Jun 03, 2023 |
| Apple         | MacBookPro8,1               | [7bdff81d7d](https://linux-hardware.org/?probe=7bdff81d7d) | Jun 03, 2023 |
| Valve         | Jupiter                     | [e7409e91d9](https://linux-hardware.org/?probe=e7409e91d9) | Jun 03, 2023 |
| Sony          | SVF1521A1EW                 | [4e3fe0308e](https://linux-hardware.org/?probe=4e3fe0308e) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | [194299200c](https://linux-hardware.org/?probe=194299200c) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| Dell          | Inspiron 5558               | [5f63504f03](https://linux-hardware.org/?probe=5f63504f03) | May 31, 2023 |
| Dell          | Inspiron 5593               | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| Acer          | Aspire ES1-512              | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Acer          | Aspire A317-53              | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Valve         | Jupiter                     | [66bff91fdb](https://linux-hardware.org/?probe=66bff91fdb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Acer          | Aspire E5-575               | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Dell          | Latitude D630               | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| ASUSTek       | X550CA                      | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Apple         | MacBookPro15,4              | [9ee2d1266b](https://linux-hardware.org/?probe=9ee2d1266b) | May 27, 2023 |
| Dell          | Inspiron 3505               | [ce0ecf0cce](https://linux-hardware.org/?probe=ce0ecf0cce) | May 27, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [a88cd7c5a6](https://linux-hardware.org/?probe=a88cd7c5a6) | May 25, 2023 |
| Dell          | XPS 15 9560                 | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| Dell          | Latitude 5521               | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | [4bbba2e730](https://linux-hardware.org/?probe=4bbba2e730) | May 25, 2023 |
| Dell          | Latitude 7390               | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| Lenovo        | ThinkPad T431s 20ACA01V0... | [253f7d5359](https://linux-hardware.org/?probe=253f7d5359) | May 24, 2023 |
| Lenovo        | ThinkPad W530 24472BG       | [6431c2bb45](https://linux-hardware.org/?probe=6431c2bb45) | May 24, 2023 |
| Lenovo        | ThinkPad T470s 20HGS4RU0... | [ac8df81694](https://linux-hardware.org/?probe=ac8df81694) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [2cf9c98869](https://linux-hardware.org/?probe=2cf9c98869) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [4da667cc7e](https://linux-hardware.org/?probe=4da667cc7e) | May 23, 2023 |
| HP            | Notebook                    | [6e7c128799](https://linux-hardware.org/?probe=6e7c128799) | May 23, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| Acer          | Aspire A317-53              | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Unknown       | Unknown                     | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| Valve         | Jupiter                     | [c7f1f9d62a](https://linux-hardware.org/?probe=c7f1f9d62a) | May 22, 2023 |
| HP            | Pavilion 15                 | [548626d011](https://linux-hardware.org/?probe=548626d011) | May 21, 2023 |
| HP            | Pavilion 15                 | [05f3c4f274](https://linux-hardware.org/?probe=05f3c4f274) | May 21, 2023 |
| Apple         | MacBook4,1                  | [d404dc5e03](https://linux-hardware.org/?probe=d404dc5e03) | May 21, 2023 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [5a30bf445a](https://linux-hardware.org/?probe=5a30bf445a) | May 21, 2023 |
| ASUSTek       | X705UDR                     | [e1f2bf110a](https://linux-hardware.org/?probe=e1f2bf110a) | May 20, 2023 |
| Dell          | Latitude 7280               | [9b98a88e3d](https://linux-hardware.org/?probe=9b98a88e3d) | May 19, 2023 |
| Apple         | MacBookPro15,2              | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Eii           | WSA116                      | [cff66832fd](https://linux-hardware.org/?probe=cff66832fd) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| Advent        | Roma                        | [f6ca4c331a](https://linux-hardware.org/?probe=f6ca4c331a) | May 19, 2023 |
| Dell          | XPS 15 9550                 | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Entroware     | Kratos                      | [ecf875b8e5](https://linux-hardware.org/?probe=ecf875b8e5) | May 18, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [3c8dcfcf15](https://linux-hardware.org/?probe=3c8dcfcf15) | May 18, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [ba813a3367](https://linux-hardware.org/?probe=ba813a3367) | May 18, 2023 |
| Acer          | Aspire A514-55              | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookPro11,1              | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| HP            | EliteBook 8770w             | [d4884bd764](https://linux-hardware.org/?probe=d4884bd764) | May 17, 2023 |
| HP            | Laptop 15s-fq4xxx           | [c6d11a2f8e](https://linux-hardware.org/?probe=c6d11a2f8e) | May 17, 2023 |
| Google        | Samus                       | [d627862e56](https://linux-hardware.org/?probe=d627862e56) | May 16, 2023 |
| eMachines     | E625                        | [8638b2b8c8](https://linux-hardware.org/?probe=8638b2b8c8) | May 15, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | [1bf9f3a0df](https://linux-hardware.org/?probe=1bf9f3a0df) | May 15, 2023 |
| Acer          | Extensa 215-52              | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Dell          | Inspiron 5405               | [9d3ae56a5e](https://linux-hardware.org/?probe=9d3ae56a5e) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [8921a6d64e](https://linux-hardware.org/?probe=8921a6d64e) | May 14, 2023 |
| Valve         | Jupiter                     | [6df9aa02d5](https://linux-hardware.org/?probe=6df9aa02d5) | May 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [162219b0fe](https://linux-hardware.org/?probe=162219b0fe) | May 14, 2023 |
| ASUSTek       | X510UQR                     | [2062004d5f](https://linux-hardware.org/?probe=2062004d5f) | May 14, 2023 |
| HP            | Pavilion dv6                | [46e74189f2](https://linux-hardware.org/?probe=46e74189f2) | May 13, 2023 |
| PC Special... | P65_67RSRP                  | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| Dell          | G7 7700                     | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| ASUSTek       | X580VD                      | [971b7bfcd1](https://linux-hardware.org/?probe=971b7bfcd1) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8bad0045f6](https://linux-hardware.org/?probe=8bad0045f6) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [78e2c8b948](https://linux-hardware.org/?probe=78e2c8b948) | May 12, 2023 |
| Valve         | Jupiter                     | [01ee28074b](https://linux-hardware.org/?probe=01ee28074b) | May 12, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| Toshiba       | Satellite C75-A             | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| Acer          | Swift SFX14-51G             | [e18646482f](https://linux-hardware.org/?probe=e18646482f) | May 11, 2023 |
| Dell          | Latitude 7390               | [ab2ea4f7a0](https://linux-hardware.org/?probe=ab2ea4f7a0) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| Acer          | Aspire E3-111               | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| Dell          | Latitude 5420               | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Sony          | SVT1312B4E                  | [dc0f581bc3](https://linux-hardware.org/?probe=dc0f581bc3) | May 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Google        | Auron_Yuna                  | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | [30bd232e19](https://linux-hardware.org/?probe=30bd232e19) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | [923397bc88](https://linux-hardware.org/?probe=923397bc88) | May 07, 2023 |
| Lenovo        | V110-15IKB 80TH             | [a908ca11db](https://linux-hardware.org/?probe=a908ca11db) | May 07, 2023 |
| HP            | x2 210                      | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| HP            | x2 210                      | [f7a174063f](https://linux-hardware.org/?probe=f7a174063f) | May 07, 2023 |
| HP            | x2 210                      | [b3c5b71d27](https://linux-hardware.org/?probe=b3c5b71d27) | May 07, 2023 |
| Dell          | Latitude E7440              | [e49cf2551c](https://linux-hardware.org/?probe=e49cf2551c) | May 07, 2023 |
| Lenovo        | G50-80 80L0                 | [af42781d8a](https://linux-hardware.org/?probe=af42781d8a) | May 06, 2023 |
| Dell          | Studio 1749                 | [43eb37cfd7](https://linux-hardware.org/?probe=43eb37cfd7) | May 06, 2023 |
| Dell          | Latitude E4200              | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| Google        | Samus                       | [aed9bd140f](https://linux-hardware.org/?probe=aed9bd140f) | May 06, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [a7ef6c976c](https://linux-hardware.org/?probe=a7ef6c976c) | May 06, 2023 |
| Dell          | XPS 15 9560                 | [644110c9b9](https://linux-hardware.org/?probe=644110c9b9) | May 06, 2023 |
| MSI           | GS43VR 7RE                  | [4eb5973faa](https://linux-hardware.org/?probe=4eb5973faa) | May 06, 2023 |
| HP            | Laptop 17-ca1xxx            | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | [db330cab38](https://linux-hardware.org/?probe=db330cab38) | May 05, 2023 |
| Dell          | Inspiron 3505               | [8e19b0629d](https://linux-hardware.org/?probe=8e19b0629d) | May 05, 2023 |
| Dell          | Latitude 5400               | [f7f8025263](https://linux-hardware.org/?probe=f7f8025263) | May 05, 2023 |
| Medion        | Akoya E1317T                | [e8eb05a52a](https://linux-hardware.org/?probe=e8eb05a52a) | May 05, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [624e1c3f06](https://linux-hardware.org/?probe=624e1c3f06) | May 05, 2023 |
| Acer          | Extensa 215-52              | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Google        | Samus                       | [a7dfa29233](https://linux-hardware.org/?probe=a7dfa29233) | May 04, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [c20844716d](https://linux-hardware.org/?probe=c20844716d) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [f87b1ac774](https://linux-hardware.org/?probe=f87b1ac774) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [d8b268f8f7](https://linux-hardware.org/?probe=d8b268f8f7) | May 03, 2023 |
| MSI           | CX62 6QD                    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| Valve         | Jupiter                     | [388caab99a](https://linux-hardware.org/?probe=388caab99a) | May 02, 2023 |
| Acer          | Aspire A317-53              | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| Advent        | Roma                        | [ec7568545d](https://linux-hardware.org/?probe=ec7568545d) | May 02, 2023 |
| ASUSTek       | X401A1                      | [2a7d35cc4e](https://linux-hardware.org/?probe=2a7d35cc4e) | May 01, 2023 |
| HP            | ProBook 430 G4              | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| lapbook       | S15 PRO                     | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Dell          | Precision 5530              | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| HP            | EliteBook 8470p             | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad X230 2325V1K       | [d630569df9](https://linux-hardware.org/?probe=d630569df9) | Apr 30, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [dff6f75899](https://linux-hardware.org/?probe=dff6f75899) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| HP            | ENVY Notebook               | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| Dell          | XPS 13 9350                 | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Valve         | Jupiter                     | [0958caf898](https://linux-hardware.org/?probe=0958caf898) | Apr 27, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Acer          | Aspire A514-54              | [19ca73662f](https://linux-hardware.org/?probe=19ca73662f) | Apr 25, 2023 |
| Google        | Sasuke                      | [7615a1b1e5](https://linux-hardware.org/?probe=7615a1b1e5) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| Dell          | Latitude XT2                | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| HP            | Stream Notebook PC 13       | [455c6b5e28](https://linux-hardware.org/?probe=455c6b5e28) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [982ca9079d](https://linux-hardware.org/?probe=982ca9079d) | Apr 23, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [25e942e55c](https://linux-hardware.org/?probe=25e942e55c) | Apr 22, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [936e6fc768](https://linux-hardware.org/?probe=936e6fc768) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e0763f0f69](https://linux-hardware.org/?probe=e0763f0f69) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dfbfce9d2e](https://linux-hardware.org/?probe=dfbfce9d2e) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [66f95f2851](https://linux-hardware.org/?probe=66f95f2851) | Apr 21, 2023 |
| Google        | Swanky                      | [92156daf53](https://linux-hardware.org/?probe=92156daf53) | Apr 21, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [1ba852f185](https://linux-hardware.org/?probe=1ba852f185) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| HP            | ProBook 4540s               | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| Dell          | G5 5590                     | [c7334114be](https://linux-hardware.org/?probe=c7334114be) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| HP            | Laptop 15-da1xxx            | [c7a5aadd85](https://linux-hardware.org/?probe=c7a5aadd85) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| Sony          | SVF1521Q1EW                 | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| ASUSTek       | X550LD                      | [5c07d2203c](https://linux-hardware.org/?probe=5c07d2203c) | Apr 17, 2023 |
| Sony          | SVE1711C5E                  | [e4fbd8fca9](https://linux-hardware.org/?probe=e4fbd8fca9) | Apr 17, 2023 |
| Dell          | XPS 17 9700                 | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| HP            | ProBook 450 G1              | [000e6c6702](https://linux-hardware.org/?probe=000e6c6702) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| HP            | 250 G4 Notebook PC          | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [f5940f5ed5](https://linux-hardware.org/?probe=f5940f5ed5) | Apr 14, 2023 |
| Dell          | XPS 15 7590                 | [f3248c9bca](https://linux-hardware.org/?probe=f3248c9bca) | Apr 14, 2023 |
| Clevo         | W760T/M740T/M760T           | [0dfaa8f0e8](https://linux-hardware.org/?probe=0dfaa8f0e8) | Apr 14, 2023 |
| Unknown       | Unknown                     | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| HUAWEI        | MRG-WXX                     | [56c255e5f0](https://linux-hardware.org/?probe=56c255e5f0) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [bd9c1c1e6d](https://linux-hardware.org/?probe=bd9c1c1e6d) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Unknown       | Unknown                     | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [9ac01d9237](https://linux-hardware.org/?probe=9ac01d9237) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| Sony          | SVE1711C5E                  | [07c6f843fb](https://linux-hardware.org/?probe=07c6f843fb) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Google        | Gnawty                      | [ddb0fea339](https://linux-hardware.org/?probe=ddb0fea339) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| Gigabyte      | MMLP3AP-00                  | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| HP            | EliteBook 2560p             | [bc5cbcd2cb](https://linux-hardware.org/?probe=bc5cbcd2cb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [b1c4404d58](https://linux-hardware.org/?probe=b1c4404d58) | Apr 09, 2023 |
| Google        | Ampton                      | [e3945d7727](https://linux-hardware.org/?probe=e3945d7727) | Apr 08, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [14a3d5f4be](https://linux-hardware.org/?probe=14a3d5f4be) | Apr 08, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [aab830c5dd](https://linux-hardware.org/?probe=aab830c5dd) | Apr 07, 2023 |
| Google        | Bluebird                    | [6ab22238ac](https://linux-hardware.org/?probe=6ab22238ac) | Apr 07, 2023 |
| Apple         | MacBookPro13,3              | [77c6d48d6b](https://linux-hardware.org/?probe=77c6d48d6b) | Apr 06, 2023 |
| HP            | Laptop 15-db0xxx            | [e05bffcc8a](https://linux-hardware.org/?probe=e05bffcc8a) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | [e2b1578d42](https://linux-hardware.org/?probe=e2b1578d42) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | [2cd7831b58](https://linux-hardware.org/?probe=2cd7831b58) | Apr 06, 2023 |
| Google        | Bard                        | [cc1d159d0c](https://linux-hardware.org/?probe=cc1d159d0c) | Apr 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8bf7c8a569](https://linux-hardware.org/?probe=8bf7c8a569) | Apr 05, 2023 |
| Dell          | Latitude E5550              | [5527315153](https://linux-hardware.org/?probe=5527315153) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Dell          | Latitude 5480               | [40ec4e3ec9](https://linux-hardware.org/?probe=40ec4e3ec9) | Apr 04, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [4e7cae1fde](https://linux-hardware.org/?probe=4e7cae1fde) | Apr 04, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1af0b7675b](https://linux-hardware.org/?probe=1af0b7675b) | Apr 04, 2023 |
| Dell          | Studio 1558                 | [e9b75d657d](https://linux-hardware.org/?probe=e9b75d657d) | Apr 04, 2023 |
| Lenovo        | Brazos                      | [6415cb26c2](https://linux-hardware.org/?probe=6415cb26c2) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7f3280e60](https://linux-hardware.org/?probe=d7f3280e60) | Apr 03, 2023 |
| Advent        | Roma                        | [e1bd64e5b5](https://linux-hardware.org/?probe=e1bd64e5b5) | Apr 03, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [36c7cf7a43](https://linux-hardware.org/?probe=36c7cf7a43) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [3ec9fed32b](https://linux-hardware.org/?probe=3ec9fed32b) | Apr 02, 2023 |
| Apple         | MacBook4,1                  | [dda3791c20](https://linux-hardware.org/?probe=dda3791c20) | Apr 01, 2023 |
| Eii           | WSA116                      | [00bf1c190b](https://linux-hardware.org/?probe=00bf1c190b) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | [4fc2057b02](https://linux-hardware.org/?probe=4fc2057b02) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| HP            | Notebook                    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| Acer          | Aspire A715-41G             | [cea0d2797d](https://linux-hardware.org/?probe=cea0d2797d) | Apr 01, 2023 |
| Samsung       | R530/R730/R540              | [714ed0f007](https://linux-hardware.org/?probe=714ed0f007) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | [82d28ac7c0](https://linux-hardware.org/?probe=82d28ac7c0) | Apr 01, 2023 |
| Valve         | Jupiter                     | [2628ea9d8e](https://linux-hardware.org/?probe=2628ea9d8e) | Apr 01, 2023 |
| Novatech      | NL40_50CU                   | [caaa544589](https://linux-hardware.org/?probe=caaa544589) | Apr 01, 2023 |
| Valve         | Jupiter                     | [d5e7a881e6](https://linux-hardware.org/?probe=d5e7a881e6) | Mar 31, 2023 |
| Valve         | Jupiter                     | [5b3718d617](https://linux-hardware.org/?probe=5b3718d617) | Mar 31, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [fe51f2c62f](https://linux-hardware.org/?probe=fe51f2c62f) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [31d333ecc9](https://linux-hardware.org/?probe=31d333ecc9) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [492d575f31](https://linux-hardware.org/?probe=492d575f31) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Dell          | Inspiron 5767               | [1c80487906](https://linux-hardware.org/?probe=1c80487906) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| Lenovo        | ThinkPad T460p 20HYSJKDO... | [1d24c2743f](https://linux-hardware.org/?probe=1d24c2743f) | Mar 29, 2023 |
| Valve         | Jupiter                     | [a63f5d9198](https://linux-hardware.org/?probe=a63f5d9198) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Dell          | Inspiron N5110              | [2b09d1f769](https://linux-hardware.org/?probe=2b09d1f769) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| Dell          | XPS 15 7590                 | [aeec5e2588](https://linux-hardware.org/?probe=aeec5e2588) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | [8fde777c54](https://linux-hardware.org/?probe=8fde777c54) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| LG Electro... | 16Z90Q-K.AA78A1             | [009542d035](https://linux-hardware.org/?probe=009542d035) | Mar 26, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| Samsung       | R530/R730/R540              | [7e37be5b8c](https://linux-hardware.org/?probe=7e37be5b8c) | Mar 25, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [1ea635d2a0](https://linux-hardware.org/?probe=1ea635d2a0) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| Dell          | Latitude E6420              | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Apple         | MacBook4,1                  | [7ade2b1d1a](https://linux-hardware.org/?probe=7ade2b1d1a) | Mar 24, 2023 |
| Dell          | Precision 3510              | [2ea0671f5d](https://linux-hardware.org/?probe=2ea0671f5d) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [bc6baa37ef](https://linux-hardware.org/?probe=bc6baa37ef) | Mar 24, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| Notebook      | W510LU                      | [076125acc3](https://linux-hardware.org/?probe=076125acc3) | Mar 23, 2023 |
| Sony          | SVF1521Q1EW                 | [10d078d9e2](https://linux-hardware.org/?probe=10d078d9e2) | Mar 22, 2023 |
| Valve         | Jupiter                     | [8fc3d21cf8](https://linux-hardware.org/?probe=8fc3d21cf8) | Mar 22, 2023 |
| Dell          | XPS 13 9380                 | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | [9c3ac61461](https://linux-hardware.org/?probe=9c3ac61461) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | [10431e8027](https://linux-hardware.org/?probe=10431e8027) | Mar 20, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Fujitsu Si... | AMILO Xi 3670               | [bb018988d6](https://linux-hardware.org/?probe=bb018988d6) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c9c86f1e79](https://linux-hardware.org/?probe=c9c86f1e79) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [29a6e93a49](https://linux-hardware.org/?probe=29a6e93a49) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Valve         | Jupiter                     | [8b7918d34b](https://linux-hardware.org/?probe=8b7918d34b) | Mar 20, 2023 |
| Sony          | VPCEH3N6E                   | [9de8a9a50a](https://linux-hardware.org/?probe=9de8a9a50a) | Mar 20, 2023 |
| Notebook      | PCx0Dx                      | [cd5adbbfc0](https://linux-hardware.org/?probe=cd5adbbfc0) | Mar 19, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 549       | 12.43%  |
| Ubuntu 18.04       | 278       | 6.29%   |
| Ubuntu 22.04       | 267       | 6.04%   |
| Zorin 16           | 113       | 2.56%   |
| Pop!_OS 22.04      | 88        | 1.99%   |
| OpenMandriva 4.3   | 84        | 1.9%    |
| Arch Rolling       | 82        | 1.86%   |
| Debian 11          | 76        | 1.72%   |
| Linux Mint 19.3    | 68        | 1.54%   |
| Fedora 38          | 63        | 1.43%   |
| Ubuntu 19.04       | 62        | 1.4%    |
| Manjaro            | 62        | 1.4%    |
| Linux Mint 20.3    | 61        | 1.38%   |
| OpenMandriva 4.2   | 60        | 1.36%   |
| Linux Mint 21.1    | 57        | 1.29%   |
| Pop!_OS 20.04      | 55        | 1.25%   |
| Linux Mint 20.2    | 55        | 1.25%   |
| ArcoLinux Rolling  | 54        | 1.22%   |
| Arch               | 54        | 1.22%   |
| Ubuntu 20.10       | 53        | 1.2%    |
| Zorin 15           | 52        | 1.18%   |
| KDE neon 20.04     | 52        | 1.18%   |
| Ubuntu 21.10       | 51        | 1.15%   |
| Linux Mint 20.1    | 50        | 1.13%   |
| Ubuntu 19.10       | 49        | 1.11%   |
| Pop!_OS 21.04      | 45        | 1.02%   |
| Ubuntu 21.04       | 44        | 1%      |
| OpenMandriva 23.01 | 44        | 1%      |
| OpenMandriva 23.03 | 41        | 0.93%   |
| Xubuntu 20.04      | 39        | 0.88%   |
| Linux Mint 20      | 36        | 0.82%   |
| Pop!_OS 20.10      | 34        | 0.77%   |
| Fedora 37          | 34        | 0.77%   |
| Pop!_OS 21.10      | 33        | 0.75%   |
| Fedora 36          | 33        | 0.75%   |
| Fedora 35          | 33        | 0.75%   |
| Fedora 34          | 33        | 0.75%   |
| Ubuntu 18.10       | 31        | 0.7%    |
| Linux Mint 21      | 30        | 0.68%   |
| BlackPanther 18.1  | 30        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1399      | 33.23%  |
| Linux Mint    | 389       | 9.24%   |
| Fedora        | 278       | 6.6%    |
| OpenMandriva  | 266       | 6.32%   |
| Pop!_OS       | 239       | 5.68%   |
| Zorin         | 173       | 4.11%   |
| Manjaro       | 136       | 3.23%   |
| Debian        | 136       | 3.23%   |
| Arch          | 134       | 3.18%   |
| SteamOS       | 102       | 2.42%   |
| Kubuntu       | 99        | 2.35%   |
| Xubuntu       | 93        | 2.21%   |
| KDE neon      | 78        | 1.85%   |
| ArcoLinux     | 58        | 1.38%   |
| Elementary    | 47        | 1.12%   |
| Lubuntu       | 42        | 1%      |
| ROSA          | 37        | 0.88%   |
| Ubuntu MATE   | 36        | 0.86%   |
| openSUSE      | 34        | 0.81%   |
| Kali          | 31        | 0.74%   |
| Gentoo        | 31        | 0.74%   |
| BlackPanther  | 31        | 0.74%   |
| Ubuntu Unity  | 29        | 0.69%   |
| Endless       | 29        | 0.69%   |
| MX            | 21        | 0.5%    |
| EndeavourOS   | 21        | 0.5%    |
| LMDE          | 20        | 0.48%   |
| Garuda Linux  | 19        | 0.45%   |
| Clear Linux   | 19        | 0.45%   |
| Ubuntu Budgie | 16        | 0.38%   |
| Parrot        | 15        | 0.36%   |
| Peppermint    | 13        | 0.31%   |
| CentOS        | 11        | 0.26%   |
| Nobara        | 9         | 0.21%   |
| NixOS         | 8         | 0.19%   |
| RHEL          | 7         | 0.17%   |
| Q4OS          | 5         | 0.12%   |
| PureOS        | 5         | 0.12%   |
| Linux Lite    | 5         | 0.12%   |
| blendOS       | 5         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 79        | 1.62%   |
| 5.4.0-42-generic         | 77        | 1.58%   |
| 5.10.14-desktop-1omv4002 | 57        | 1.17%   |
| 5.15.0-56-generic        | 49        | 1.01%   |
| 5.13.0-valve36-1-neptune | 42        | 0.86%   |
| 6.2.6-desktop-1omv2390   | 41        | 0.84%   |
| 5.4.0-48-generic         | 40        | 0.82%   |
| 5.4.0-52-generic         | 39        | 0.8%    |
| 6.1.1-desktop-1omv2290   | 38        | 0.78%   |
| 5.15.0-52-generic        | 38        | 0.78%   |
| 5.15.0-58-generic        | 37        | 0.76%   |
| 5.4.0-29-generic         | 35        | 0.72%   |
| 5.3.0-40-generic         | 35        | 0.72%   |
| 5.11.0-27-generic        | 34        | 0.7%    |
| 5.4.0-26-generic         | 33        | 0.68%   |
| 5.3.0-28-generic         | 33        | 0.68%   |
| 5.15.0-46-generic        | 33        | 0.68%   |
| 5.4.0-58-generic         | 30        | 0.62%   |
| 5.4.0-40-generic         | 29        | 0.6%    |
| 5.0.0-32-generic         | 29        | 0.6%    |
| 5.11.0-38-generic        | 28        | 0.58%   |
| 5.8.0-43-generic         | 25        | 0.51%   |
| 5.3.0-42-generic         | 25        | 0.51%   |
| 5.19.0-35-generic        | 25        | 0.51%   |
| 6.2.0-26-generic         | 24        | 0.49%   |
| 5.4.0-91-generic         | 24        | 0.49%   |
| 5.11.0-37-generic        | 24        | 0.49%   |
| 5.11.0-25-generic        | 24        | 0.49%   |
| 5.4.0-65-generic         | 23        | 0.47%   |
| 5.4.0-7634-generic       | 22        | 0.45%   |
| 5.4.0-33-generic         | 22        | 0.45%   |
| 5.13.0-7614-generic      | 22        | 0.45%   |
| 5.13.0-28-generic        | 22        | 0.45%   |
| 5.0.0-37-generic         | 22        | 0.45%   |
| 4.18.16-desktop-1bP      | 22        | 0.45%   |
| 5.8.0-50-generic         | 21        | 0.43%   |
| 5.8.0-44-generic         | 21        | 0.43%   |
| 5.4.0-56-generic         | 21        | 0.43%   |
| 5.4.0-54-generic         | 21        | 0.43%   |
| 5.3.0-46-generic         | 21        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 738       | 16.2%   |
| 5.15.0  | 425       | 9.33%   |
| 5.13.0  | 282       | 6.19%   |
| 5.11.0  | 243       | 5.33%   |
| 5.8.0   | 234       | 5.14%   |
| 5.3.0   | 204       | 4.48%   |
| 4.15.0  | 203       | 4.46%   |
| 5.19.0  | 158       | 3.47%   |
| 5.0.0   | 137       | 3.01%   |
| 6.2.0   | 120       | 2.63%   |
| 5.10.0  | 102       | 2.24%   |
| 4.18.0  | 92        | 2.02%   |
| 5.16.7  | 79        | 1.73%   |
| 6.2.6   | 64        | 1.4%    |
| 5.10.14 | 57        | 1.25%   |
| 6.1.0   | 45        | 0.99%   |
| 6.1.1   | 39        | 0.86%   |
| 4.19.0  | 30        | 0.66%   |
| 4.18.16 | 23        | 0.5%    |
| 6.4.11  | 21        | 0.46%   |
| 5.14.0  | 17        | 0.37%   |
| 5.17.5  | 16        | 0.35%   |
| 6.0.6   | 15        | 0.33%   |
| 6.0.0   | 15        | 0.33%   |
| 6.2.9   | 14        | 0.31%   |
| 6.5.5   | 12        | 0.26%   |
| 6.4.6   | 12        | 0.26%   |
| 6.4.12  | 12        | 0.26%   |
| 6.3.5   | 12        | 0.26%   |
| 4.9.60  | 12        | 0.26%   |
| 6.5.0   | 11        | 0.24%   |
| 6.0.12  | 11        | 0.24%   |
| 5.17.1  | 11        | 0.24%   |
| 5.16.0  | 11        | 0.24%   |
| 6.5.6   | 10        | 0.22%   |
| 5.9.16  | 10        | 0.22%   |
| 5.15.12 | 10        | 0.22%   |
| 4.4.0   | 10        | 0.22%   |
| 5.18.10 | 9         | 0.2%    |
| 5.9.0   | 8         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 774       | 17.15%  |
| 5.15    | 517       | 11.46%  |
| 5.13    | 322       | 7.13%   |
| 5.8     | 279       | 6.18%   |
| 5.11    | 267       | 5.92%   |
| 6.2     | 233       | 5.16%   |
| 5.3     | 228       | 5.05%   |
| 5.10    | 208       | 4.61%   |
| 4.15    | 204       | 4.52%   |
| 5.19    | 199       | 4.41%   |
| 6.1     | 156       | 3.46%   |
| 5.16    | 145       | 3.21%   |
| 5.0     | 144       | 3.19%   |
| 4.18    | 117       | 2.59%   |
| 6.4     | 88        | 1.95%   |
| 6.0     | 78        | 1.73%   |
| 5.17    | 58        | 1.29%   |
| 6.3     | 55        | 1.22%   |
| 5.14    | 54        | 1.2%    |
| 6.5     | 48        | 1.06%   |
| 5.9     | 46        | 1.02%   |
| 4.19    | 46        | 1.02%   |
| 5.12    | 42        | 0.93%   |
| 5.6     | 38        | 0.84%   |
| 4.9     | 33        | 0.73%   |
| 5.18    | 32        | 0.71%   |
| 5.7     | 30        | 0.66%   |
| 5.5     | 19        | 0.42%   |
| 5.2     | 11        | 0.24%   |
| 4.4     | 11        | 0.24%   |
| 5.1     | 8         | 0.18%   |
| 3.10    | 4         | 0.09%   |
| 4.20    | 3         | 0.07%   |
| 4.16    | 3         | 0.07%   |
| 4.14    | 3         | 0.07%   |
| 4.8     | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 4.1     | 2         | 0.04%   |
| 4.6     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3945      | 97.07%  |
| i686    | 118       | 2.9%    |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1891      | 44.66%  |
| KDE5             | 762       | 18%     |
| Unknown          | 426       | 10.06%  |
| X-Cinnamon       | 318       | 7.51%   |
| XFCE             | 307       | 7.25%   |
| MATE             | 111       | 2.62%   |
| KDE              | 85        | 2.01%   |
| Cinnamon         | 46        | 1.09%   |
| Pantheon         | 44        | 1.04%   |
| LXQt             | 44        | 1.04%   |
| Unity            | 31        | 0.73%   |
| LXDE             | 28        | 0.66%   |
| Budgie           | 23        | 0.54%   |
| i3               | 22        | 0.52%   |
| GNOME Flashback  | 18        | 0.43%   |
| KDE4             | 14        | 0.33%   |
| sway             | 9         | 0.21%   |
| Hyprland         | 7         | 0.17%   |
| qtile            | 6         | 0.14%   |
| GNOME Classic    | 6         | 0.14%   |
| awesome          | 6         | 0.14%   |
| bspwm            | 4         | 0.09%   |
| xmonad           | 3         | 0.07%   |
| trinity          | 3         | 0.07%   |
| openbox          | 3         | 0.07%   |
| Deepin           | 3         | 0.07%   |
| i3-with-shmlog   | 2         | 0.05%   |
| DWM              | 2         | 0.05%   |
| chadwm           | 2         | 0.05%   |
| Unicorn:XFCE     | 1         | 0.02%   |
| mwm              | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| Hypr             | 1         | 0.02%   |
| GNUstep          | 1         | 0.02%   |
| Enlightenment    | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3134      | 75.17%  |
| Wayland | 754       | 18.09%  |
| Unknown | 234       | 5.61%   |
| Tty     | 47        | 1.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2179      | 51.61%  |
| SDDM    | 604       | 14.31%  |
| GDM3    | 467       | 11.06%  |
| GDM     | 455       | 10.78%  |
| LightDM | 382       | 9.05%   |
| TDM     | 101       | 2.39%   |
| KDM     | 15        | 0.36%   |
| XDM     | 5         | 0.12%   |
| LXDM    | 5         | 0.12%   |
| Ly      | 4         | 0.09%   |
| SLiM    | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| en_GB          | 2996      | 71.95%  |
| en_US          | 548       | 13.16%  |
| Unknown        | 417       | 10.01%  |
| C              | 58        | 1.39%   |
| pl_PL          | 41        | 0.98%   |
| de_DE          | 10        | 0.24%   |
| fr_FR          | 9         | 0.22%   |
| it_IT          | 7         | 0.17%   |
| en_CA          | 7         | 0.17%   |
| en_AU          | 7         | 0.17%   |
| ru_RU          | 6         | 0.14%   |
| POSIX          | 6         | 0.14%   |
| es_ES          | 6         | 0.14%   |
| en_IN          | 5         | 0.12%   |
| en_IE          | 5         | 0.12%   |
| cs_CZ          | 5         | 0.12%   |
| hu_HU          | 4         | 0.1%    |
| zh_CN          | 3         | 0.07%   |
| ro_RO          | 3         | 0.07%   |
| uk_UA          | 2         | 0.05%   |
| sk_SK          | 2         | 0.05%   |
| pt_PT          | 2         | 0.05%   |
| pt_BR          | 2         | 0.05%   |
| tr_TR          | 1         | 0.02%   |
| nl_BE          | 1         | 0.02%   |
| en_US.utf-8    | 1         | 0.02%   |
| en_IL          | 1         | 0.02%   |
| en_HK          | 1         | 0.02%   |
| en_GG          | 1         | 0.02%   |
| en_GB.utf-8    | 1         | 0.02%   |
| en_GB.iso88591 | 1         | 0.02%   |
| en_AG          | 1         | 0.02%   |
| enGB           | 1         | 0.02%   |
| da_DK          | 1         | 0.02%   |
| C.UTF8         | 1         | 0.02%   |
| bg_BG          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2128      | 51.38%  |
| BIOS | 2014      | 48.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3127      | 74.81%  |
| Btrfs   | 456       | 10.91%  |
| Overlay | 284       | 6.79%   |
| Unknown | 112       | 2.68%   |
| Tmpfs   | 98        | 2.34%   |
| Xfs     | 50        | 1.2%    |
| Zfs     | 33        | 0.79%   |
| Ext2    | 9         | 0.22%   |
| F2fs    | 6         | 0.14%   |
| Ext3    | 4         | 0.1%    |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2283      | 54.84%  |
| GPT     | 1505      | 36.15%  |
| MBR     | 375       | 9.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3695      | 89.49%  |
| Yes       | 434       | 10.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3125      | 75.85%  |
| Yes       | 995       | 24.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 803       | 19.78%  |
| Dell                | 794       | 19.56%  |
| Hewlett-Packard     | 662       | 16.31%  |
| ASUSTek Computer    | 292       | 7.19%   |
| Acer                | 291       | 7.17%   |
| Toshiba             | 176       | 4.33%   |
| Apple               | 130       | 3.2%    |
| Valve               | 104       | 2.56%   |
| Samsung Electronics | 78        | 1.92%   |
| Sony                | 65        | 1.6%    |
| MSI                 | 63        | 1.55%   |
| HUAWEI              | 49        | 1.21%   |
| Google              | 48        | 1.18%   |
| PC Specialist       | 46        | 1.13%   |
| Notebook            | 32        | 0.79%   |
| Unknown             | 32        | 0.79%   |
| Alienware           | 23        | 0.57%   |
| Star Labs           | 20        | 0.49%   |
| Razer               | 20        | 0.49%   |
| Fujitsu             | 19        | 0.47%   |
| Packard Bell        | 18        | 0.44%   |
| Fujitsu Siemens     | 15        | 0.37%   |
| Entroware           | 15        | 0.37%   |
| Dixonsxp            | 14        | 0.34%   |
| TUXEDO              | 13        | 0.32%   |
| GEO                 | 12        | 0.3%    |
| Clevo               | 12        | 0.3%    |
| LG Electronics      | 11        | 0.27%   |
| Linx                | 9         | 0.22%   |
| Gigabyte Technology | 9         | 0.22%   |
| Advent              | 9         | 0.22%   |
| Timi                | 8         | 0.2%    |
| Panasonic           | 8         | 0.2%    |
| Jumper              | 8         | 0.2%    |
| Framework           | 8         | 0.2%    |
| eMachines           | 8         | 0.2%    |
| OEGStone            | 7         | 0.17%   |
| Novatech            | 7         | 0.17%   |
| Medion              | 7         | 0.17%   |
| Intel               | 7         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Valve Jupiter           | 104       | 2.56%   |
| Unknown                 | 54        | 1.33%   |
| HP Pavilion g6          | 26        | 0.64%   |
| HP Notebook             | 21        | 0.52%   |
| HP Pavilion 15          | 20        | 0.49%   |
| HP Pavilion Notebook    | 17        | 0.42%   |
| Dell XPS 15 9560        | 16        | 0.39%   |
| Dell XPS 15 7590        | 16        | 0.39%   |
| Dell Inspiron 1545      | 15        | 0.37%   |
| Dell XPS 15 9570        | 14        | 0.34%   |
| Dell XPS 13 9380        | 14        | 0.34%   |
| Dell XPS 13 9370        | 14        | 0.34%   |
| Dell XPS 13 9360        | 13        | 0.32%   |
| Dell Latitude E6400     | 13        | 0.32%   |
| Dell Latitude E6410     | 12        | 0.3%    |
| Apple MacBookPro12,1    | 12        | 0.3%    |
| Toshiba Satellite C660  | 11        | 0.27%   |
| Lenovo V145-15AST 81MT  | 11        | 0.27%   |
| Dell XPS 13 7390        | 11        | 0.27%   |
| Dell Latitude E7240     | 11        | 0.27%   |
| HP Pavilion dv6         | 10        | 0.25%   |
| HP Laptop 15-da0xxx     | 10        | 0.25%   |
| HP Laptop 15-bw0xx      | 10        | 0.25%   |
| Dell XPS 15 9550        | 10        | 0.25%   |
| Dell XPS 15 9510        | 10        | 0.25%   |
| Dell XPS 15 9500        | 10        | 0.25%   |
| Dell Latitude E7450     | 10        | 0.25%   |
| Dell Latitude E7440     | 10        | 0.25%   |
| Apple MacBookPro9,2     | 10        | 0.25%   |
| Acer Aspire ES1-531     | 10        | 0.25%   |
| Lenovo Z50-75 80EC      | 9         | 0.22%   |
| HP 15                   | 9         | 0.22%   |
| Dell XPS 13 9310        | 9         | 0.22%   |
| Dell XPS 13 9305        | 9         | 0.22%   |
| Dell Latitude E6420     | 9         | 0.22%   |
| Apple MacBookPro5,5     | 9         | 0.22%   |
| Dell Inspiron 5570      | 8         | 0.2%    |
| Toshiba Satellite C50-B | 7         | 0.17%   |
| Star Labs LabTop        | 7         | 0.17%   |
| Razer Blade             | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 462       | 11.38%  |
| Dell Latitude         | 271       | 6.67%   |
| Acer Aspire           | 208       | 5.12%   |
| Dell Inspiron         | 202       | 4.98%   |
| Dell XPS              | 186       | 4.58%   |
| Toshiba Satellite     | 153       | 3.77%   |
| Lenovo IdeaPad        | 148       | 3.65%   |
| HP Pavilion           | 145       | 3.57%   |
| HP EliteBook          | 110       | 2.71%   |
| Valve Jupiter         | 104       | 2.56%   |
| HP Laptop             | 73        | 1.8%    |
| HP ProBook            | 71        | 1.75%   |
| ASUS VivoBook         | 70        | 1.72%   |
| Dell Precision        | 55        | 1.35%   |
| Unknown               | 54        | 1.33%   |
| HP ENVY               | 35        | 0.86%   |
| HP Compaq             | 32        | 0.79%   |
| Lenovo Legion         | 30        | 0.74%   |
| Acer Swift            | 29        | 0.71%   |
| HP Stream             | 28        | 0.69%   |
| ASUS Zenbook          | 28        | 0.69%   |
| Dell Vostro           | 26        | 0.64%   |
| ASUS ROG              | 24        | 0.59%   |
| Lenovo Yoga           | 23        | 0.57%   |
| HP Notebook           | 21        | 0.52%   |
| Razer Blade           | 20        | 0.49%   |
| Lenovo ThinkBook      | 20        | 0.49%   |
| HP ZBook              | 20        | 0.49%   |
| HP 255                | 19        | 0.47%   |
| HP Presario           | 18        | 0.44%   |
| Packard Bell EasyNote | 17        | 0.42%   |
| Fujitsu LIFEBOOK      | 16        | 0.39%   |
| ASUS ASUS             | 16        | 0.39%   |
| Acer Nitro            | 16        | 0.39%   |
| HP OMEN               | 15        | 0.37%   |
| Dell System           | 13        | 0.32%   |
| Apple MacBookPro9     | 13        | 0.32%   |
| Apple MacBookPro5     | 13        | 0.32%   |
| Apple MacBookPro12    | 12        | 0.3%    |
| Apple MacBookPro11    | 12        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 355       | 8.74%   |
| 2019    | 341       | 8.4%    |
| 2020    | 326       | 8.03%   |
| 2012    | 303       | 7.46%   |
| 2021    | 285       | 7.02%   |
| 2013    | 284       | 7%      |
| 2017    | 262       | 6.45%   |
| 2011    | 256       | 6.31%   |
| 2015    | 243       | 5.99%   |
| 2016    | 232       | 5.71%   |
| 2014    | 232       | 5.71%   |
| 2022    | 226       | 5.57%   |
| 2010    | 192       | 4.73%   |
| 2008    | 169       | 4.16%   |
| 2009    | 147       | 3.62%   |
| 2007    | 97        | 2.39%   |
| 2023    | 53        | 1.31%   |
| 2006    | 41        | 1.01%   |
| 2005    | 8         | 0.2%    |
| Unknown | 6         | 0.15%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4060      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3646      | 88.91%  |
| Enabled  | 455       | 11.09%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3990      | 98.25%  |
| Yes  | 71        | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1178      | 28.6%   |
| 3.01-4.0    | 799       | 19.4%   |
| 16.01-24.0  | 746       | 18.11%  |
| 8.01-16.0   | 690       | 16.75%  |
| 32.01-64.0  | 270       | 6.55%   |
| 1.01-2.0    | 226       | 5.49%   |
| 2.01-3.0    | 92        | 2.23%   |
| 64.01-256.0 | 45        | 1.09%   |
| 24.01-32.0  | 39        | 0.95%   |
| 0.51-1.0    | 33        | 0.8%    |
| 0.01-0.5    | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1661      | 37.05%  |
| 2.01-3.0   | 1110      | 24.76%  |
| 4.01-8.0   | 639       | 14.25%  |
| 3.01-4.0   | 575       | 12.83%  |
| 0.51-1.0   | 286       | 6.38%   |
| 8.01-16.0  | 148       | 3.3%    |
| 0.01-0.5   | 37        | 0.83%   |
| 16.01-24.0 | 17        | 0.38%   |
| 24.01-32.0 | 7         | 0.16%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3001      | 72.37%  |
| 2      | 973       | 23.46%  |
| 3      | 105       | 2.53%   |
| 0      | 36        | 0.87%   |
| 4      | 21        | 0.51%   |
| 5      | 5         | 0.12%   |
| 7      | 3         | 0.07%   |
| 9      | 1         | 0.02%   |
| 8      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2663      | 65.27%  |
| Yes       | 1417      | 34.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3096      | 76.01%  |
| No        | 977       | 23.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4003      | 98.55%  |
| No        | 59        | 1.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3182      | 77.59%  |
| No        | 919       | 22.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 4060      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 278       | 6.2%    |
| Manchester          | 90        | 2.01%   |
| Birmingham          | 82        | 1.83%   |
| Glasgow             | 75        | 1.67%   |
| Edinburgh           | 70        | 1.56%   |
| Bristol             | 57        | 1.27%   |
| Leeds               | 55        | 1.23%   |
| Liverpool           | 50        | 1.12%   |
| Sheffield           | 48        | 1.07%   |
| Nottingham          | 47        | 1.05%   |
| Islington           | 43        | 0.96%   |
| Reading             | 40        | 0.89%   |
| Cambridge           | 39        | 0.87%   |
| Coventry            | 34        | 0.76%   |
| Norwich             | 33        | 0.74%   |
| Leicester           | 32        | 0.71%   |
| Oxford              | 31        | 0.69%   |
| Southampton         | 30        | 0.67%   |
| Croydon             | 30        | 0.67%   |
| Aberdeen            | 28        | 0.62%   |
| York                | 26        | 0.58%   |
| Milton Keynes       | 26        | 0.58%   |
| Cardiff             | 26        | 0.58%   |
| Bradford            | 24        | 0.54%   |
| Plymouth            | 22        | 0.49%   |
| Gloucester          | 22        | 0.49%   |
| Brighton            | 22        | 0.49%   |
| Bolton              | 22        | 0.49%   |
| Swindon             | 21        | 0.47%   |
| Newcastle upon Tyne | 21        | 0.47%   |
| Chesterfield        | 21        | 0.47%   |
| Wolverhampton       | 20        | 0.45%   |
| Kensington          | 20        | 0.45%   |
| Hackney             | 20        | 0.45%   |
| Colchester          | 20        | 0.45%   |
| Belfast             | 20        | 0.45%   |
| Wigan               | 19        | 0.42%   |
| Harrow              | 19        | 0.42%   |
| Walsall             | 18        | 0.4%    |
| Derby               | 18        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 784       | 1045   | 15.68%  |
| Seagate                     | 476       | 646    | 9.52%   |
| WDC                         | 475       | 608    | 9.5%    |
| Unknown                     | 448       | 580    | 8.96%   |
| Toshiba                     | 428       | 530    | 8.56%   |
| SanDisk                     | 315       | 390    | 6.3%    |
| Crucial                     | 216       | 294    | 4.32%   |
| SK hynix                    | 209       | 245    | 4.18%   |
| Kingston                    | 193       | 240    | 3.86%   |
| Hitachi                     | 178       | 212    | 3.56%   |
| Intel                       | 148       | 176    | 2.96%   |
| HGST                        | 122       | 179    | 2.44%   |
| Micron Technology           | 108       | 129    | 2.16%   |
| Apple                       | 64        | 83     | 1.28%   |
| KIOXIA                      | 55        | 66     | 1.1%    |
| Phison                      | 46        | 54     | 0.92%   |
| Phison Electronics          | 43        | 49     | 0.86%   |
| China                       | 42        | 60     | 0.84%   |
| LITEON                      | 39        | 50     | 0.78%   |
| A-DATA Technology           | 38        | 46     | 0.76%   |
| Fujitsu                     | 32        | 42     | 0.64%   |
| PNY                         | 31        | 37     | 0.62%   |
| Unknown                     | 30        | 34     | 0.6%    |
| Transcend                   | 28        | 35     | 0.56%   |
| Silicon Motion              | 26        | 31     | 0.52%   |
| Micron/Crucial Technology   | 26        | 27     | 0.52%   |
| LITEONIT                    | 26        | 33     | 0.52%   |
| Kingston Technology Company | 22        | 24     | 0.44%   |
| O2 Micro                    | 17        | 18     | 0.34%   |
| Integral                    | 14        | 16     | 0.28%   |
| SPCC                        | 12        | 18     | 0.24%   |
| OCZ                         | 12        | 13     | 0.24%   |
| Lenovo                      | 12        | 13     | 0.24%   |
| SABRENT                     | 9         | 9      | 0.18%   |
| Realtek                     | 9         | 9      | 0.18%   |
| JMicron Technology          | 9         | 14     | 0.18%   |
| Corsair                     | 9         | 13     | 0.18%   |
| Team                        | 8         | 9      | 0.16%   |
| TCSUNBOW                    | 7         | 11     | 0.14%   |
| Patriot                     | 7         | 13     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                             | 98        | 1.87%   |
| Seagate ST1000LM035-1RK172 1TB                     | 63        | 1.2%    |
| Toshiba MQ01ABD100 1TB                             | 53        | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 53        | 1.01%   |
| Unknown MMC Card  64GB                             | 49        | 0.94%   |
| Unknown MMC Card  128GB                            | 39        | 0.75%   |
| Unknown MMC Card  512GB                            | 38        | 0.73%   |
| Samsung NVMe SSD Drive 512GB                       | 37        | 0.71%   |
| Toshiba MQ01ABF050 500GB                           | 34        | 0.65%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 33        | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 32        | 0.61%   |
| Unknown MMC Card  16GB                             | 31        | 0.59%   |
| HGST HTS721010A9E630 1TB                           | 31        | 0.59%   |
| HGST HTS541010A9E680 1TB                           | 30        | 0.57%   |
| Unknown                                            | 30        | 0.57%   |
| Samsung SSD 850 EVO 500GB                          | 29        | 0.55%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 29        | 0.55%   |
| Crucial CT500MX500SSD1 500GB                       | 29        | 0.55%   |
| Kingston SA400S37240G 240GB SSD                    | 28        | 0.54%   |
| Toshiba NVMe SSD Drive 256GB                       | 25        | 0.48%   |
| Samsung SSD 860 EVO 500GB                          | 25        | 0.48%   |
| Kingston SA400S37120G 120GB SSD                    | 25        | 0.48%   |
| Samsung SSD 850 EVO 250GB                          | 24        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                        | 24        | 0.46%   |
| Unknown SD/MMC/MS PRO 16GB                         | 23        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                       | 23        | 0.44%   |
| Seagate ST9500325AS 500GB                          | 21        | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                    | 21        | 0.4%    |
| Seagate ST2000LM003 HN-M201RAD 2TB                 | 21        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                       | 21        | 0.4%    |
| Kingston SA400S37480G 480GB SSD                    | 21        | 0.4%    |
| Toshiba MQ04ABF100 1TB                             | 20        | 0.38%   |
| Samsung NVMe SSD Drive 1024GB                      | 20        | 0.38%   |
| Crucial CT240BX500SSD1 240GB                       | 20        | 0.38%   |
| Unknown MMC Card  256GB                            | 19        | 0.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 19        | 0.36%   |
| SK hynix NVMe SSD Drive 512GB                      | 18        | 0.34%   |
| Crucial CT250MX500SSD1 250GB                       | 18        | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                       | 17        | 0.32%   |
| SanDisk NVMe SSD Drive 256GB                       | 17        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 461       | 624    | 31.9%   |
| WDC                 | 283       | 361    | 19.58%  |
| Toshiba             | 276       | 332    | 19.1%   |
| Hitachi             | 178       | 212    | 12.32%  |
| HGST                | 122       | 179    | 8.44%   |
| Samsung Electronics | 46        | 51     | 3.18%   |
| Fujitsu             | 32        | 42     | 2.21%   |
| Unknown             | 23        | 27     | 1.59%   |
| Apple               | 7         | 7      | 0.48%   |
| SSK                 | 3         | 4      | 0.21%   |
| Initio              | 2         | 2      | 0.14%   |
| IBM/Hitachi         | 2         | 2      | 0.14%   |
| ASMT                | 2         | 25     | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
| Maxone              | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| JMicron Technology  | 1         | 4      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| Generic-            | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 336       | 452    | 21.24%  |
| Crucial             | 198       | 273    | 12.52%  |
| SanDisk             | 176       | 213    | 11.13%  |
| Kingston            | 153       | 186    | 9.67%   |
| WDC                 | 86        | 121    | 5.44%   |
| Intel               | 53        | 57     | 3.35%   |
| Micron Technology   | 46        | 54     | 2.91%   |
| SK hynix            | 42        | 54     | 2.65%   |
| Toshiba             | 39        | 53     | 2.47%   |
| China               | 39        | 54     | 2.47%   |
| Apple               | 38        | 48     | 2.4%    |
| LITEON              | 37        | 48     | 2.34%   |
| PNY                 | 30        | 35     | 1.9%    |
| A-DATA Technology   | 29        | 35     | 1.83%   |
| Transcend           | 27        | 34     | 1.71%   |
| LITEONIT            | 26        | 33     | 1.64%   |
| Integral            | 14        | 16     | 0.88%   |
| OCZ                 | 12        | 13     | 0.76%   |
| SPCC                | 11        | 16     | 0.7%    |
| Seagate             | 9         | 9      | 0.57%   |
| SABRENT             | 9         | 9      | 0.57%   |
| Unknown             | 7         | 7      | 0.44%   |
| Team                | 7         | 8      | 0.44%   |
| Patriot             | 7         | 13     | 0.44%   |
| Netac               | 7         | 10     | 0.44%   |
| TCSUNBOW            | 6         | 10     | 0.38%   |
| Star                | 6         | 7      | 0.38%   |
| Drevo               | 6         | 9      | 0.38%   |
| Corsair             | 6         | 10     | 0.38%   |
| BHT                 | 6         | 9      | 0.38%   |
| Lexar               | 5         | 6      | 0.32%   |
| Gigabyte Technology | 5         | 6      | 0.32%   |
| ORTIAL              | 4         | 4      | 0.25%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.25%   |
| BIWIN               | 4         | 4      | 0.25%   |
| ZTC                 | 3         | 6      | 0.19%   |
| Zheino              | 3         | 5      | 0.19%   |
| XUM                 | 3         | 3      | 0.19%   |
| Vaseky              | 3         | 4      | 0.19%   |
| TO Exter            | 3         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1435      | 2038   | 30.33%  |
| HDD     | 1400      | 1879   | 29.59%  |
| NVMe    | 1398      | 1839   | 29.55%  |
| MMC     | 446       | 575    | 9.43%   |
| Unknown | 52        | 64     | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2604      | 3772   | 56.63%  |
| NVMe | 1393      | 1818   | 30.3%   |
| MMC  | 446       | 575    | 9.7%    |
| SAS  | 155       | 230    | 3.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1955      | 2685   | 68.69%  |
| 0.51-1.0   | 760       | 1031   | 26.7%   |
| 1.01-2.0   | 102       | 138    | 3.58%   |
| 3.01-4.0   | 13        | 38     | 0.46%   |
| 2.01-3.0   | 10        | 13     | 0.35%   |
| 4.01-10.0  | 6         | 12     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1259      | 29.35%  |
| 251-500        | 1006      | 23.46%  |
| 501-1000       | 642       | 14.97%  |
| 1-20           | 338       | 7.88%   |
| 51-100         | 303       | 7.06%   |
| 21-50          | 251       | 5.85%   |
| 1001-2000      | 234       | 5.46%   |
| Unknown        | 116       | 2.7%    |
| More than 3000 | 82        | 1.91%   |
| 2001-3000      | 58        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1885      | 42.42%  |
| 21-50          | 833       | 18.74%  |
| 101-250        | 565       | 12.71%  |
| 51-100         | 496       | 11.16%  |
| 251-500        | 303       | 6.82%   |
| 501-1000       | 149       | 3.35%   |
| Unknown        | 116       | 2.61%   |
| 1001-2000      | 63        | 1.42%   |
| More than 3000 | 17        | 0.38%   |
| 2001-3000      | 16        | 0.36%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 6         | 10     | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 2.94%   |
| HGST HTS725050A7E630 500GB                     | 6         | 9      | 2.94%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 2.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 5      | 1.96%   |
| Toshiba MK1656GSY 160GB                        | 3         | 3      | 1.47%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 3      | 1.47%   |
| Intel SSDSC2BF180A5L 180GB                     | 3         | 3      | 1.47%   |
| Hitachi HTS543216L9A300 160GB                  | 3         | 3      | 1.47%   |
| Hitachi HTS542512K9SA00 120GB                  | 3         | 3      | 1.47%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.47%   |
| WDC WD2500BEVT-80A23T0 250GB                   | 2         | 5      | 0.98%   |
| Toshiba MK5065GSXN 500GB                       | 2         | 2      | 0.98%   |
| Toshiba MK3256GSY 320GB                        | 2         | 3      | 0.98%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 0.98%   |
| Seagate ST2000LX001-1RG174 2TB                 | 2         | 2      | 0.98%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 3      | 0.98%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.98%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.98%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 0.98%   |
| LITEON LCH-256V2S-11 2.5 7mm 256GB SSD         | 2         | 2      | 0.98%   |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD           | 2         | 2      | 0.98%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 0.98%   |
| Hitachi HTS545050A7E380 500GB                  | 2         | 2      | 0.98%   |
| Hitachi HTS545032B9A302 320GB                  | 2         | 3      | 0.98%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.98%   |
| Hitachi HTS545025B9A300 250GB                  | 2         | 2      | 0.98%   |
| Hitachi HTS541680J9SA00 80GB                   | 2         | 2      | 0.98%   |
| HGST HTS721010A9E630 1TB                       | 2         | 2      | 0.98%   |
| Drevo X1 SSD 64GB                              | 2         | 2      | 0.98%   |
| Crucial CT525MX300SSD4 528GB                   | 2         | 2      | 0.98%   |
| Zheino CHN mSATA02M 256 256GB SSD              | 1         | 2      | 0.49%   |
| WDC WD7500BPVT-60HXZT3 752GB                   | 1         | 1      | 0.49%   |
| WDC WD5000BPVT-55HXZT3 500GB                   | 1         | 1      | 0.49%   |
| WDC WD5000BEVT-75A0RT0 500GB                   | 1         | 1      | 0.49%   |
| WDC WD5000BEVT-60A0RT0 500GB                   | 1         | 2      | 0.49%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 0.49%   |
| WDC WD5000BEKT-75KA9T0 500GB                   | 1         | 1      | 0.49%   |
| WDC WD3200LPCX-24C6HT0 320GB                   | 1         | 1      | 0.49%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 56     | 24.14%  |
| Hitachi             | 35        | 38     | 17.24%  |
| Toshiba             | 23        | 24     | 11.33%  |
| WDC                 | 15        | 20     | 7.39%   |
| HGST                | 15        | 18     | 7.39%   |
| Samsung Electronics | 12        | 13     | 5.91%   |
| Crucial             | 10        | 10     | 4.93%   |
| Intel               | 8         | 8      | 3.94%   |
| SanDisk             | 5         | 5      | 2.46%   |
| Kingston            | 5         | 7      | 2.46%   |
| LITEON              | 4         | 4      | 1.97%   |
| Fujitsu             | 4         | 5      | 1.97%   |
| Micron Technology   | 3         | 3      | 1.48%   |
| SK hynix            | 2         | 2      | 0.99%   |
| Drevo               | 2         | 2      | 0.99%   |
| A-DATA Technology   | 2         | 2      | 0.99%   |
| Zheino              | 1         | 2      | 0.49%   |
| Team                | 1         | 1      | 0.49%   |
| OCZ                 | 1         | 1      | 0.49%   |
| LITEONIT            | 1         | 2      | 0.49%   |
| HECTRON             | 1         | 1      | 0.49%   |
| Corsair             | 1         | 1      | 0.49%   |
| China               | 1         | 1      | 0.49%   |
| BAITITON            | 1         | 1      | 0.49%   |
| 2-Power             | 1         | 1      | 0.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 56     | 34.27%  |
| Hitachi             | 35        | 38     | 24.48%  |
| Toshiba             | 21        | 22     | 14.69%  |
| HGST                | 15        | 18     | 10.49%  |
| WDC                 | 14        | 19     | 9.79%   |
| Samsung Electronics | 5         | 5      | 3.5%    |
| Fujitsu             | 4         | 5      | 2.8%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 142       | 163    | 70.3%   |
| SSD  | 56        | 61     | 27.72%  |
| NVMe | 4         | 4      | 1.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB | 1         | 1      | 33.33%  |
| Toshiba THNSN5512GPUK NVMe 512GB              | 1         | 2      | 33.33%  |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba                 | 2         | 3      | 66.67%  |
| Union Memory (Shenzhen) | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2640      | 4226   | 61.88%  |
| Works    | 1424      | 1937   | 33.38%  |
| Malfunc  | 199       | 228    | 4.66%   |
| Failed   | 3         | 4      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2716      | 58.22%  |
| Samsung Electronics              | 460       | 9.86%   |
| AMD                              | 452       | 9.69%   |
| Sandisk                          | 234       | 5.02%   |
| SK hynix                         | 163       | 3.49%   |
| Toshiba America Info Systems     | 120       | 2.57%   |
| Phison Electronics               | 97        | 2.08%   |
| Micron Technology                | 64        | 1.37%   |
| Kingston Technology Company      | 62        | 1.33%   |
| KIOXIA                           | 54        | 1.16%   |
| Micron/Crucial Technology        | 42        | 0.9%    |
| Nvidia                           | 40        | 0.86%   |
| Silicon Motion                   | 29        | 0.62%   |
| O2 Micro                         | 17        | 0.36%   |
| Apple                            | 17        | 0.36%   |
| ADATA Technology                 | 14        | 0.3%    |
| Silicon Integrated Systems [SiS] | 12        | 0.26%   |
| Solid State Storage Technology   | 11        | 0.24%   |
| Lenovo                           | 11        | 0.24%   |
| Union Memory (Shenzhen)          | 7         | 0.15%   |
| Marvell Technology Group         | 6         | 0.13%   |
| Shenzhen Longsys Electronics     | 5         | 0.11%   |
| Lite-On Technology               | 5         | 0.11%   |
| VIA Technologies                 | 4         | 0.09%   |
| Yangtze Memory Technologies      | 3         | 0.06%   |
| Realtek Semiconductor            | 3         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| JMicron Technology               | 3         | 0.06%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| ASMedia Technology               | 2         | 0.04%   |
| Solidigm                         | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 382       | 7.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 310       | 6.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 269       | 5.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 266       | 5.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 211       | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 189       | 3.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 168       | 3.36%   |
| Intel Volume Management Device NVMe RAID Controller                              | 134       | 2.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 129       | 2.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 120       | 2.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 115       | 2.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 93        | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 92        | 1.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 82        | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 80        | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 79        | 1.58%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 71        | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 68        | 1.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 60        | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 57        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 54        | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 54        | 1.08%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 53        | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 53        | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 51        | 1.02%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 49        | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 48        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 47        | 0.94%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 46        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 44        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 41        | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 40        | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 39        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 39        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 36        | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 36        | 0.72%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 31        | 0.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 30        | 0.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 28        | 0.56%   |
| Intel SSD 660P Series                                                            | 28        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2669      | 55.6%   |
| NVMe | 1403      | 29.23%  |
| RAID | 413       | 8.6%    |
| IDE  | 315       | 6.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3330      | 82.02%  |
| AMD    | 729       | 17.96%  |
| ARM    | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 104       | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 61        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 56        | 1.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 53        | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 52        | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 50        | 1.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 50        | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 47        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 45        | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 45        | 1.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 44        | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 43        | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 40        | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 39        | 0.96%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 39        | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 38        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 38        | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 38        | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 37        | 0.91%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 37        | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 35        | 0.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 33        | 0.81%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 30        | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 29        | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 29        | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 27        | 0.66%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 27        | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 24        | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 23        | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 23        | 0.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 23        | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 22        | 0.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 22        | 0.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 21        | 0.52%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.52%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 21        | 0.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 20        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 960       | 23.63%  |
| Intel Core i7           | 885       | 21.78%  |
| Other                   | 424       | 10.44%  |
| Intel Celeron           | 277       | 6.82%   |
| Intel Core i3           | 271       | 6.67%   |
| Intel Core 2 Duo        | 211       | 5.19%   |
| AMD Ryzen 7             | 117       | 2.88%   |
| AMD Ryzen 5             | 115       | 2.83%   |
| Intel Pentium           | 110       | 2.71%   |
| Intel Atom              | 81        | 1.99%   |
| AMD A6                  | 62        | 1.53%   |
| AMD A8                  | 43        | 1.06%   |
| Intel Pentium Dual-Core | 37        | 0.91%   |
| AMD Ryzen 3             | 36        | 0.89%   |
| Intel Core 2            | 33        | 0.81%   |
| AMD A4                  | 28        | 0.69%   |
| Intel Pentium Dual      | 27        | 0.66%   |
| Intel Genuine           | 25        | 0.62%   |
| AMD Ryzen 9             | 25        | 0.62%   |
| Intel Core i9           | 23        | 0.57%   |
| Intel Celeron Dual-Core | 21        | 0.52%   |
| AMD E1                  | 20        | 0.49%   |
| AMD Ryzen 7 PRO         | 19        | 0.47%   |
| AMD A10                 | 17        | 0.42%   |
| AMD E                   | 16        | 0.39%   |
| Intel Pentium Silver    | 15        | 0.37%   |
| Intel Celeron M         | 15        | 0.37%   |
| AMD E2                  | 14        | 0.34%   |
| Intel Pentium M         | 10        | 0.25%   |
| AMD Athlon              | 9         | 0.22%   |
| AMD Turion 64 X2 Mobile | 8         | 0.2%    |
| AMD Athlon II           | 8         | 0.2%    |
| AMD FX                  | 7         | 0.17%   |
| AMD Athlon X2           | 7         | 0.17%   |
| AMD Turion 64 Mobile    | 6         | 0.15%   |
| AMD Ryzen 5 PRO         | 6         | 0.15%   |
| Intel Pentium Gold      | 5         | 0.12%   |
| Intel Core m3           | 5         | 0.12%   |
| Intel Core M            | 5         | 0.12%   |
| AMD Phenom II           | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2141      | 52.71%  |
| 4      | 1278      | 31.46%  |
| 6      | 226       | 5.56%   |
| 8      | 212       | 5.22%   |
| 1      | 109       | 2.68%   |
| 14     | 36        | 0.89%   |
| 12     | 31        | 0.76%   |
| 10     | 26        | 0.64%   |
| 3      | 2         | 0.05%   |
| 16     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4059      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2896      | 71.28%  |
| 1      | 1167      | 28.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3956      | 97.15%  |
| 32-bit         | 58        | 1.42%   |
| Unknown        | 58        | 1.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1253      | 29.72%  |
| 0x306a9    | 234       | 5.55%   |
| 0x206a7    | 206       | 4.89%   |
| 0x1067a    | 156       | 3.7%    |
| 0x806ec    | 121       | 2.87%   |
| 0x806ea    | 121       | 2.87%   |
| 0x40651    | 120       | 2.85%   |
| 0x406e3    | 112       | 2.66%   |
| 0x806e9    | 108       | 2.56%   |
| 0x306d4    | 104       | 2.47%   |
| 0x20655    | 97        | 2.3%    |
| 0x806c1    | 93        | 2.21%   |
| 0x906ea    | 88        | 2.09%   |
| 0x6fd      | 69        | 1.64%   |
| 0x406c4    | 65        | 1.54%   |
| 0x306c3    | 64        | 1.52%   |
| 0x30678    | 62        | 1.47%   |
| 0x906e9    | 50        | 1.19%   |
| 0xa0652    | 49        | 1.16%   |
| 0x506e3    | 44        | 1.04%   |
| 0x506c9    | 44        | 1.04%   |
| 0x06006705 | 42        | 1%      |
| 0x0a50000c | 41        | 0.97%   |
| 0x08108109 | 39        | 0.93%   |
| 0x706e5    | 37        | 0.88%   |
| 0x08108102 | 36        | 0.85%   |
| 0x406c3    | 35        | 0.83%   |
| 0x20652    | 33        | 0.78%   |
| 0x10676    | 32        | 0.76%   |
| 0x806d1    | 31        | 0.74%   |
| 0x906a3    | 30        | 0.71%   |
| 0x706a1    | 30        | 0.71%   |
| 0x07030105 | 30        | 0.71%   |
| 0x6f6      | 25        | 0.59%   |
| 0x08600106 | 25        | 0.59%   |
| 0x06006704 | 23        | 0.55%   |
| 0x806eb    | 21        | 0.5%    |
| 0x05000119 | 20        | 0.47%   |
| 0x08600104 | 19        | 0.45%   |
| 0x08608103 | 18        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 730       | 17.95%  |
| IvyBridge        | 304       | 7.47%   |
| Haswell          | 274       | 6.74%   |
| SandyBridge      | 266       | 6.54%   |
| Penryn           | 220       | 5.41%   |
| Skylake          | 219       | 5.38%   |
| Unknown          | 214       | 5.26%   |
| Silvermont       | 205       | 5.04%   |
| Westmere         | 164       | 4.03%   |
| Core             | 155       | 3.81%   |
| TigerLake        | 154       | 3.79%   |
| Broadwell        | 147       | 3.61%   |
| Zen+             | 93        | 2.29%   |
| Icelake          | 91        | 2.24%   |
| Excavator        | 85        | 2.09%   |
| CometLake        | 80        | 1.97%   |
| Zen 2            | 75        | 1.84%   |
| Alderlake Hybrid | 72        | 1.77%   |
| Goldmont plus    | 66        | 1.62%   |
| Zen 3            | 62        | 1.52%   |
| Puma             | 55        | 1.35%   |
| Goldmont         | 52        | 1.28%   |
| P6               | 41        | 1.01%   |
| Zen              | 39        | 0.96%   |
| Bobcat           | 35        | 0.86%   |
| Bonnell          | 32        | 0.79%   |
| K10              | 23        | 0.57%   |
| Piledriver       | 22        | 0.54%   |
| Jaguar           | 22        | 0.54%   |
| K8 Hammer        | 20        | 0.49%   |
| Steamroller      | 14        | 0.34%   |
| K8 & K10 hybrid  | 13        | 0.32%   |
| Nehalem          | 11        | 0.27%   |
| K10 Llano        | 6         | 0.15%   |
| Tremont          | 4         | 0.1%    |
| NetBurst         | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3070      | 62.9%   |
| Nvidia                           | 931       | 19.07%  |
| AMD                              | 863       | 17.68%  |
| Silicon Integrated Systems [SiS] | 12        | 0.25%   |
| VIA Technologies                 | 4         | 0.08%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 288       | 5.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 252       | 5%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 174       | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 159       | 3.16%   |
| Intel UHD Graphics 620                                                                   | 151       | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 138       | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 136       | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 133       | 2.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 133       | 2.64%   |
| Intel HD Graphics 620                                                                    | 128       | 2.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 117       | 2.32%   |
| Intel HD Graphics 5500                                                                   | 110       | 2.18%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 104       | 2.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 103       | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 101       | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 99        | 1.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 95        | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 88        | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 71        | 1.41%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 70        | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 66        | 1.31%   |
| Intel HD Graphics 630                                                                    | 63        | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 60        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 60        | 1.19%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 56        | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 55        | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 54        | 1.07%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 50        | 0.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 49        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 48        | 0.95%   |
| Intel HD Graphics 530                                                                    | 48        | 0.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 45        | 0.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 42        | 0.83%   |
| Intel HD Graphics 500                                                                    | 42        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 37        | 0.73%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 35        | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 33        | 0.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 33        | 0.66%   |
| AMD Lucienne                                                                             | 33        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 32        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2294      | 56.29%  |
| 1 x AMD                  | 684       | 16.79%  |
| Intel + Nvidia           | 669       | 16.42%  |
| 1 x Nvidia               | 200       | 4.91%   |
| Intel + AMD              | 87        | 2.13%   |
| AMD + Nvidia             | 58        | 1.42%   |
| 2 x AMD                  | 34        | 0.83%   |
| 2 x Intel                | 20        | 0.49%   |
| 1 x SiS                  | 12        | 0.29%   |
| Other                    | 8         | 0.2%    |
| 1 x VIA                  | 4         | 0.1%    |
| 2 x Nvidia               | 3         | 0.07%   |
| Intel + 2 x Nvidia       | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3537      | 86.06%  |
| Proprietary | 484       | 11.78%  |
| Unknown     | 89        | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2889      | 69.43%  |
| 0.01-0.5   | 470       | 11.3%   |
| 1.01-2.0   | 333       | 8%      |
| 3.01-4.0   | 185       | 4.45%   |
| 0.51-1.0   | 163       | 3.92%   |
| 5.01-6.0   | 63        | 1.51%   |
| 7.01-8.0   | 40        | 0.96%   |
| 2.01-3.0   | 9         | 0.22%   |
| 8.01-16.0  | 9         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 841       | 18.88%  |
| LG Display              | 675       | 15.15%  |
| Chimei Innolux          | 539       | 12.1%   |
| BOE                     | 505       | 11.34%  |
| Samsung Electronics     | 460       | 10.33%  |
| Sharp                   | 208       | 4.67%   |
| Apple                   | 133       | 2.99%   |
| Dell                    | 113       | 2.54%   |
| Lenovo                  | 95        | 2.13%   |
| Chi Mei Optoelectronics | 84        | 1.89%   |
| PANDA                   | 66        | 1.48%   |
| Goldstar                | 63        | 1.41%   |
| Valve                   | 60        | 1.35%   |
| LG Philips              | 50        | 1.12%   |
| Acer                    | 48        | 1.08%   |
| Hewlett-Packard         | 47        | 1.06%   |
| Iiyama                  | 37        | 0.83%   |
| BenQ                    | 37        | 0.83%   |
| InfoVision              | 36        | 0.81%   |
| AOC                     | 32        | 0.72%   |
| Analogix                | 26        | 0.58%   |
| CSO                     | 23        | 0.52%   |
| Philips                 | 22        | 0.49%   |
| Ancor Communications    | 21        | 0.47%   |
| Panasonic               | 18        | 0.4%    |
| Sony                    | 15        | 0.34%   |
| ViewSonic               | 13        | 0.29%   |
| Toshiba                 | 13        | 0.29%   |
| LGD                     | 13        | 0.29%   |
| InnoLux Display         | 12        | 0.27%   |
| HannStar                | 11        | 0.25%   |
| Vestel Elektronik       | 9         | 0.2%    |
| ASUSTek Computer        | 9         | 0.2%    |
| Quanta Display          | 7         | 0.16%   |
| CPT                     | 7         | 0.16%   |
| Seiko/Epson             | 6         | 0.13%   |
| Unknown                 | 5         | 0.11%   |
| JDI                     | 5         | 0.11%   |
| TMX                     | 4         | 0.09%   |
| NEC Computers           | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 60        | 1.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 45        | 1%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 35        | 0.78%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 33        | 0.73%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 32        | 0.71%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 31        | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 29        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 26        | 0.58%   |
| Analogix ANX7530 U ANX7539 800x1280                                   | 26        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 23        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 22        | 0.49%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 21        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 18        | 0.4%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 18        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 17        | 0.38%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 16        | 0.36%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 15        | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 14        | 0.31%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 14        | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 14        | 0.31%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 13        | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 13        | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 13        | 0.29%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 13        | 0.29%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 12        | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 12        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 12        | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 11        | 0.24%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 11        | 0.24%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch           | 11        | 0.24%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 11        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1611      | 37.96%  |
| 1366x768 (WXGA)    | 1280      | 30.16%  |
| 1280x800 (WXGA)    | 216       | 5.09%   |
| 3840x2160 (4K)     | 196       | 4.62%   |
| 1600x900 (HD+)     | 161       | 3.79%   |
| 2560x1440 (QHD)    | 132       | 3.11%   |
| 1920x1200 (WUXGA)  | 85        | 2%      |
| 800x1280           | 83        | 1.96%   |
| 1440x900 (WXGA+)   | 82        | 1.93%   |
| 2560x1600          | 60        | 1.41%   |
| 3840x2400          | 38        | 0.9%    |
| 2880x1800          | 36        | 0.85%   |
| 1680x1050 (WSXGA+) | 32        | 0.75%   |
| 3440x1440          | 26        | 0.61%   |
| 3200x1800 (QHD+)   | 23        | 0.54%   |
| 1024x600           | 21        | 0.49%   |
| 1280x1024 (SXGA)   | 19        | 0.45%   |
| 2160x1440          | 14        | 0.33%   |
| 2560x1080          | 12        | 0.28%   |
| 2256x1504          | 10        | 0.24%   |
| Unknown            | 10        | 0.24%   |
| 1360x768           | 9         | 0.21%   |
| 3072x1920          | 7         | 0.16%   |
| 1920x540           | 7         | 0.16%   |
| 3456x2160          | 6         | 0.14%   |
| 1024x768 (XGA)     | 6         | 0.14%   |
| 2560x1700          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 1680x945           | 5         | 0.12%   |
| 3000x2000          | 4         | 0.09%   |
| 3840x1080          | 3         | 0.07%   |
| 3200x2000          | 3         | 0.07%   |
| 2880x1920          | 3         | 0.07%   |
| 2520x1680          | 3         | 0.07%   |
| 1280x768           | 3         | 0.07%   |
| 3120x2080          | 2         | 0.05%   |
| 2304x1440          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 2240x1400          | 2         | 0.05%   |
| 2160x1350          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1781      | 40.09%  |
| 13      | 701       | 15.78%  |
| 14      | 453       | 10.2%   |
| 17      | 281       | 6.33%   |
| 12      | 194       | 4.37%   |
| 27      | 137       | 3.08%   |
| 11      | 124       | 2.79%   |
| 24      | 106       | 2.39%   |
| 23      | 79        | 1.78%   |
| 21      | 76        | 1.71%   |
| Unknown | 61        | 1.37%   |
| 7       | 60        | 1.35%   |
| 16      | 54        | 1.22%   |
| 31      | 43        | 0.97%   |
| 34      | 34        | 0.77%   |
| 10      | 32        | 0.72%   |
| 18      | 29        | 0.65%   |
| 3       | 26        | 0.59%   |
| 84      | 23        | 0.52%   |
| 19      | 18        | 0.41%   |
| 25      | 15        | 0.34%   |
| 22      | 13        | 0.29%   |
| 26      | 11        | 0.25%   |
| 72      | 10        | 0.23%   |
| 20      | 9         | 0.2%    |
| 40      | 8         | 0.18%   |
| 8       | 8         | 0.18%   |
| 54      | 7         | 0.16%   |
| 48      | 6         | 0.14%   |
| 32      | 5         | 0.11%   |
| 65      | 4         | 0.09%   |
| 86      | 3         | 0.07%   |
| 50      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |
| 33      | 3         | 0.07%   |
| 28      | 3         | 0.07%   |
| 142     | 2         | 0.05%   |
| 49      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 39      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2513      | 56.92%  |
| 201-300        | 764       | 17.3%   |
| 351-400        | 355       | 8.04%   |
| 501-600        | 314       | 7.11%   |
| 401-500        | 129       | 2.92%   |
| 1-100          | 83        | 1.88%   |
| 601-700        | 61        | 1.38%   |
| Unknown        | 61        | 1.38%   |
| 701-800        | 42        | 0.95%   |
| 1501-2000      | 35        | 0.79%   |
| 1001-1500      | 31        | 0.7%    |
| 801-900        | 13        | 0.29%   |
| 101-200        | 8         | 0.18%   |
| More than 2000 | 3         | 0.07%   |
| 901-1000       | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3206      | 79.63%  |
| 16/10   | 542       | 13.46%  |
| 0.67    | 60        | 1.49%   |
| 3/2     | 56        | 1.39%   |
| Unknown | 55        | 1.37%   |
| 21/9    | 40        | 0.99%   |
| 6/5     | 29        | 0.72%   |
| 5/4     | 16        | 0.4%    |
| 4/3     | 11        | 0.27%   |
| 32/9    | 3         | 0.07%   |
| 1.00    | 3         | 0.07%   |
| 0.62    | 2         | 0.05%   |
| 0.56    | 2         | 0.05%   |
| 3.40    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1775      | 40.04%  |
| 81-90          | 818       | 18.45%  |
| 71-80          | 333       | 7.51%   |
| 121-130        | 234       | 5.28%   |
| 201-250        | 226       | 5.1%    |
| 61-70          | 186       | 4.2%    |
| 301-350        | 146       | 3.29%   |
| 51-60          | 126       | 2.84%   |
| 1-40           | 91        | 2.05%   |
| 351-500        | 90        | 2.03%   |
| More than 1000 | 64        | 1.44%   |
| Unknown        | 61        | 1.38%   |
| 111-120        | 54        | 1.22%   |
| 131-140        | 47        | 1.06%   |
| 151-200        | 45        | 1.02%   |
| 251-300        | 43        | 0.97%   |
| 41-50          | 31        | 0.7%    |
| 141-150        | 30        | 0.68%   |
| 501-1000       | 18        | 0.41%   |
| 91-100         | 15        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1667      | 38.07%  |
| 101-120       | 1295      | 29.57%  |
| 51-100        | 613       | 14%     |
| 161-240       | 469       | 10.71%  |
| More than 240 | 225       | 5.14%   |
| Unknown       | 61        | 1.39%   |
| 1-50          | 49        | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3448      | 83.37%  |
| 2     | 545       | 13.18%  |
| 0     | 87        | 2.1%    |
| 3     | 51        | 1.23%   |
| 4     | 4         | 0.1%    |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2212      | 35.25%  |
| Realtek Semiconductor             | 1918      | 30.56%  |
| Qualcomm Atheros                  | 839       | 13.37%  |
| Broadcom                          | 462       | 7.36%   |
| Broadcom Limited                  | 108       | 1.72%   |
| Marvell Technology Group          | 93        | 1.48%   |
| MediaTek                          | 61        | 0.97%   |
| Ralink Technology                 | 54        | 0.86%   |
| Ralink                            | 47        | 0.75%   |
| TP-Link                           | 46        | 0.73%   |
| Ericsson Business Mobile Networks | 42        | 0.67%   |
| ASIX Electronics                  | 37        | 0.59%   |
| Dell                              | 34        | 0.54%   |
| Qualcomm                          | 29        | 0.46%   |
| DisplayLink                       | 29        | 0.46%   |
| Nvidia                            | 28        | 0.45%   |
| Lenovo                            | 25        | 0.4%    |
| Samsung Electronics               | 22        | 0.35%   |
| Hewlett-Packard                   | 20        | 0.32%   |
| Sierra Wireless                   | 16        | 0.25%   |
| JMicron Technology                | 12        | 0.19%   |
| Huawei Technologies               | 12        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.18%   |
| NetGear                           | 8         | 0.13%   |
| Edimax Technology                 | 8         | 0.13%   |
| Qualcomm Atheros Communications   | 6         | 0.1%    |
| ICS Advent                        | 6         | 0.1%    |
| Google                            | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 5         | 0.08%   |
| Micro Star International          | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| Attansic Technology               | 5         | 0.08%   |
| ASUSTek Computer                  | 5         | 0.08%   |
| Apple                             | 5         | 0.08%   |
| Xiaomi                            | 4         | 0.06%   |
| VIA Technologies                  | 4         | 0.06%   |
| Fibocom                           | 4         | 0.06%   |
| OPPO Electronics                  | 3         | 0.05%   |
| Motorola PCS                      | 3         | 0.05%   |
| AMD                               | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1020      | 13.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 398       | 5.23%   |
| Intel Wi-Fi 6 AX200                                                     | 184       | 2.42%   |
| Intel Wireless 8265 / 8275                                              | 176       | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 172       | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 164       | 2.16%   |
| Intel Wireless 7265                                                     | 151       | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 150       | 1.97%   |
| Intel Wireless 7260                                                     | 146       | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 140       | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 136       | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 130       | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 128       | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 115       | 1.51%   |
| Intel Wireless 8260                                                     | 105       | 1.38%   |
| Intel Wi-Fi 6 AX201                                                     | 101       | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 96        | 1.26%   |
| Intel Wireless 3165                                                     | 91        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 86        | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 76        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 73        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 0.91%   |
| Intel 82577LM Gigabit Network Connection                                | 67        | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                   | 66        | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 0.85%   |
| Intel Ethernet Connection I218-LM                                       | 64        | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 63        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 63        | 0.83%   |
| Intel Wireless 3160                                                     | 54        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 53        | 0.7%    |
| Intel Wireless-AC 9260                                                  | 51        | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 49        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 49        | 0.64%   |
| Intel WiFi Link 5100                                                    | 48        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 46        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                          | 46        | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 45        | 0.59%   |
| Intel Ethernet Connection I219-LM                                       | 45        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                   | 45        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2121      | 49.89%  |
| Qualcomm Atheros                  | 727       | 17.1%   |
| Realtek Semiconductor             | 650       | 15.29%  |
| Broadcom                          | 354       | 8.33%   |
| Broadcom Limited                  | 85        | 2%      |
| MediaTek                          | 56        | 1.32%   |
| Ralink Technology                 | 54        | 1.27%   |
| Ralink                            | 47        | 1.11%   |
| TP-Link                           | 39        | 0.92%   |
| Qualcomm                          | 18        | 0.42%   |
| Dell                              | 18        | 0.42%   |
| Sierra Wireless                   | 16        | 0.38%   |
| NetGear                           | 8         | 0.19%   |
| Ericsson Business Mobile Networks | 8         | 0.19%   |
| Edimax Technology                 | 8         | 0.19%   |
| Qualcomm Atheros Communications   | 6         | 0.14%   |
| Micro Star International          | 5         | 0.12%   |
| Belkin Components                 | 5         | 0.12%   |
| Fibocom                           | 4         | 0.09%   |
| ASUSTek Computer                  | 4         | 0.09%   |
| Wacom                             | 2         | 0.05%   |
| Qualcomm Technologies             | 2         | 0.05%   |
| Hewlett-Packard                   | 2         | 0.05%   |
| D-Link                            | 2         | 0.05%   |
| ZyDAS                             | 1         | 0.02%   |
| Senao                             | 1         | 0.02%   |
| Microsoft                         | 1         | 0.02%   |
| Marvell Technology Group          | 1         | 0.02%   |
| Linksys                           | 1         | 0.02%   |
| InProComm                         | 1         | 0.02%   |
| Fujitsu Siemens Computers         | 1         | 0.02%   |
| Askey Computer                    | 1         | 0.02%   |
| Apple                             | 1         | 0.02%   |
| 3Com                              | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 184       | 4.31%   |
| Intel Wireless 8265 / 8275                                              | 176       | 4.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 164       | 3.84%   |
| Intel Wireless 7265                                                     | 151       | 3.53%   |
| Intel Wireless 7260                                                     | 146       | 3.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 140       | 3.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 136       | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 130       | 3.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 128       | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 115       | 2.69%   |
| Intel Wireless 8260                                                     | 105       | 2.46%   |
| Intel Wi-Fi 6 AX201                                                     | 101       | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 96        | 2.25%   |
| Intel Wireless 3165                                                     | 91        | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 86        | 2.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 76        | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 73        | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 63        | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 62        | 1.45%   |
| Intel Wireless 3160                                                     | 54        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 53        | 1.24%   |
| Intel Wireless-AC 9260                                                  | 51        | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 49        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 49        | 1.15%   |
| Intel WiFi Link 5100                                                    | 48        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 46        | 1.08%   |
| Intel Centrino Ultimate-N 6300                                          | 46        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 45        | 1.05%   |
| Intel Centrino Advanced-N 6235                                          | 44        | 1.03%   |
| Intel Centrino Advanced-N 6200                                          | 42        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 40        | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 38        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 36        | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 33        | 0.77%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 32        | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 31        | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 30        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1632      | 51%     |
| Intel                            | 816       | 25.5%   |
| Qualcomm Atheros                 | 209       | 6.53%   |
| Broadcom                         | 177       | 5.53%   |
| Marvell Technology Group         | 92        | 2.88%   |
| ASIX Electronics                 | 37        | 1.16%   |
| DisplayLink                      | 29        | 0.91%   |
| Nvidia                           | 28        | 0.88%   |
| Broadcom Limited                 | 26        | 0.81%   |
| Samsung Electronics              | 22        | 0.69%   |
| Lenovo                           | 22        | 0.69%   |
| JMicron Technology               | 12        | 0.38%   |
| Qualcomm                         | 11        | 0.34%   |
| Silicon Integrated Systems [SiS] | 10        | 0.31%   |
| Huawei Technologies              | 10        | 0.31%   |
| TP-Link                          | 7         | 0.22%   |
| ICS Advent                       | 6         | 0.19%   |
| Google                           | 6         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.16%   |
| Hewlett-Packard                  | 5         | 0.16%   |
| Attansic Technology              | 5         | 0.16%   |
| Xiaomi                           | 4         | 0.13%   |
| VIA Technologies                 | 4         | 0.13%   |
| MediaTek                         | 4         | 0.13%   |
| Apple                            | 4         | 0.13%   |
| OPPO Electronics                 | 3         | 0.09%   |
| Motorola PCS                     | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.06%   |
| Microchip Technology             | 2         | 0.06%   |
| HTC (High Tech Computer)         | 2         | 0.06%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Research In Motion               | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ASUSTek Computer                 | 1         | 0.03%   |
| Aquantia                         | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1020      | 31.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 398       | 12.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 172       | 5.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 150       | 4.64%   |
| Intel 82577LM Gigabit Network Connection                          | 67        | 2.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 66        | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 64        | 1.98%   |
| Intel Ethernet Connection I219-LM                                 | 45        | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 1.39%   |
| Intel 82567LM Gigabit Network Connection                          | 42        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 40        | 1.24%   |
| Intel Ethernet Connection (4) I219-V                              | 38        | 1.18%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 36        | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                     | 33        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.93%   |
| Intel Ethernet Connection I219-V                                  | 27        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 26        | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 20        | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18        | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 18        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 17        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 17        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.46%   |
| Intel 82566MM Gigabit Network Connection                          | 15        | 0.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 15        | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14        | 0.43%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 14        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 13        | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 13        | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 13        | 0.4%    |
| Realtek Killer E3000 2.5GbE Controller                            | 12        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4002      | 55.65%  |
| Ethernet | 3092      | 42.99%  |
| Modem    | 92        | 1.28%   |
| Unknown  | 6         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3455      | 81.05%  |
| Ethernet | 808       | 18.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2798      | 68.85%  |
| 1     | 1188      | 29.23%  |
| 0     | 59        | 1.45%   |
| 3     | 18        | 0.44%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3569      | 86.44%  |
| Yes  | 560       | 13.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1573      | 48.97%  |
| Qualcomm Atheros Communications | 279       | 8.69%   |
| Realtek Semiconductor           | 267       | 8.31%   |
| Broadcom                        | 208       | 6.48%   |
| IMC Networks                    | 207       | 6.44%   |
| Foxconn / Hon Hai               | 113       | 3.52%   |
| Apple                           | 112       | 3.49%   |
| Lite-On Technology              | 99        | 3.08%   |
| Dell                            | 74        | 2.3%    |
| Cambridge Silicon Radio         | 66        | 2.05%   |
| Toshiba                         | 60        | 1.87%   |
| Hewlett-Packard                 | 44        | 1.37%   |
| Realtek                         | 24        | 0.75%   |
| Alps Electric                   | 19        | 0.59%   |
| Foxconn International           | 14        | 0.44%   |
| Ralink                          | 9         | 0.28%   |
| ASUSTek Computer                | 8         | 0.25%   |
| USI                             | 7         | 0.22%   |
| Ralink Technology               | 6         | 0.19%   |
| Askey Computer                  | 6         | 0.19%   |
| Taiyo Yuden                     | 5         | 0.16%   |
| Belkin Components               | 4         | 0.12%   |
| TP-Link                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| MediaTek                        | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 686       | 21.34%  |
| Intel AX201 Bluetooth                               | 269       | 8.37%   |
| Intel AX200 Bluetooth                               | 180       | 5.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 162       | 5.04%   |
| Realtek Bluetooth Radio                             | 158       | 4.92%   |
| IMC Networks Bluetooth Radio                        | 139       | 4.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 105       | 3.27%   |
| Intel Bluetooth Device                              | 90        | 2.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 76        | 2.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 73        | 2.27%   |
| Apple Bluetooth Host Controller                     | 71        | 2.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 66        | 2.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 65        | 2.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 58        | 1.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 54        | 1.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.34%   |
| Broadcom BCM2045B (BDC-2.1)                         | 42        | 1.31%   |
| Intel AX210 Bluetooth                               | 41        | 1.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 31        | 0.96%   |
| Apple Bluetooth USB Host Controller                 | 29        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 0.81%   |
| IMC Networks Wireless_Device                        | 26        | 0.81%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.81%   |
| Realtek Bluetooth Radio                             | 24        | 0.75%   |
| IMC Networks Bluetooth Device                       | 23        | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 22        | 0.68%   |
| Toshiba Bluetooth Device                            | 21        | 0.65%   |
| Lite-On Bluetooth Device                            | 20        | 0.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 20        | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 16        | 0.5%    |
| Broadcom HP Portable SoftSailing                    | 16        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 14        | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.44%   |
| Toshiba Atheros AR3012 Bluetooth                    | 12        | 0.37%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3238      | 67.09%  |
| AMD                              | 783       | 16.22%  |
| Nvidia                           | 498       | 10.32%  |
| C-Media Electronics              | 38        | 0.79%   |
| Realtek Semiconductor            | 29        | 0.6%    |
| GN Netcom                        | 21        | 0.44%   |
| Plantronics                      | 20        | 0.41%   |
| Lenovo                           | 18        | 0.37%   |
| Texas Instruments                | 14        | 0.29%   |
| Silicon Integrated Systems [SiS] | 12        | 0.25%   |
| Logitech                         | 11        | 0.23%   |
| Apple                            | 11        | 0.23%   |
| JMTek                            | 10        | 0.21%   |
| Creative Technology              | 8         | 0.17%   |
| ASUSTek Computer                 | 7         | 0.15%   |
| VIA Technologies                 | 5         | 0.1%    |
| Hewlett-Packard                  | 5         | 0.1%    |
| Corsair                          | 5         | 0.1%    |
| Conexant Systems                 | 5         | 0.1%    |
| SteelSeries ApS                  | 4         | 0.08%   |
| Sennheiser Communications        | 4         | 0.08%   |
| RODE Microphones                 | 4         | 0.08%   |
| Kingston Technology              | 4         | 0.08%   |
| Generalplus Technology           | 4         | 0.08%   |
| Focusrite-Novation               | 4         | 0.08%   |
| Blue Microphones                 | 4         | 0.08%   |
| Yamaha                           | 3         | 0.06%   |
| XMOS                             | 3         | 0.06%   |
| Sony                             | 3         | 0.06%   |
| Razer USA                        | 3         | 0.06%   |
| PreSonus Audio Electronics       | 3         | 0.06%   |
| Google                           | 3         | 0.06%   |
| Dell                             | 3         | 0.06%   |
| Samsung Electronics              | 2         | 0.04%   |
| Native Instruments               | 2         | 0.04%   |
| M-Audio                          | 2         | 0.04%   |
| GYROCOM C&C                      | 2         | 0.04%   |
| AudioQuest                       | 2         | 0.04%   |
| AKAI Professional M.I.           | 2         | 0.04%   |
| Trust                            | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 456       | 7.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 355       | 6.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 323       | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 213       | 3.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 210       | 3.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 175       | 3.02%   |
| Intel 8 Series HD Audio Controller                                                                | 161       | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 160       | 2.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 154       | 2.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 151       | 2.61%   |
| Intel Broadwell-U Audio Controller                                                                | 147       | 2.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 142       | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 141       | 2.44%   |
| AMD FCH Azalia Controller                                                                         | 136       | 2.35%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 128       | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 123       | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 114       | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 110       | 1.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 102       | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 97        | 1.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 91        | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 88        | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 88        | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 84        | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 81        | 1.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 75        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 74        | 1.28%   |
| Intel CM238 HD Audio Controller                                                                   | 71        | 1.23%   |
| AMD High Definition Audio Controller                                                              | 71        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 70        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 66        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 60        | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 60        | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 54        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 52        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 49        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 49        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 43        | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 40        | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 37        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 639       | 27.18%  |
| SK hynix            | 577       | 24.54%  |
| Micron Technology   | 311       | 13.23%  |
| Crucial             | 188       | 8%      |
| Unknown             | 161       | 6.85%   |
| Kingston            | 155       | 6.59%   |
| Corsair             | 56        | 2.38%   |
| Ramaxel Technology  | 49        | 2.08%   |
| Elpida              | 41        | 1.74%   |
| Nanya Technology    | 35        | 1.49%   |
| A-DATA Technology   | 26        | 1.11%   |
| Unknown (ABCD)      | 21        | 0.89%   |
| Unknown             | 16        | 0.68%   |
| Toshiba             | 6         | 0.26%   |
| Qimonda             | 5         | 0.21%   |
| GSkill              | 4         | 0.17%   |
| GOODRAM             | 4         | 0.17%   |
| Essencore           | 4         | 0.17%   |
| 4ea5                | 4         | 0.17%   |
| Transcend           | 3         | 0.13%   |
| Patriot             | 3         | 0.13%   |
| ff                  | 3         | 0.13%   |
| ASint Technology    | 3         | 0.13%   |
| Apacer              | 3         | 0.13%   |
| A Force             | 3         | 0.13%   |
| Timetec             | 2         | 0.09%   |
| Team                | 2         | 0.09%   |
| SHARETRONIC         | 2         | 0.09%   |
| Neo Forza           | 2         | 0.09%   |
| Innodisk            | 2         | 0.09%   |
| G.Skill             | 2         | 0.09%   |
| fef5                | 2         | 0.09%   |
| V-Color             | 1         | 0.04%   |
| Unknown (F301)      | 1         | 0.04%   |
| Unknown (CB83)      | 1         | 0.04%   |
| Unknown (0B38)      | 1         | 0.04%   |
| Smart               | 1         | 0.04%   |
| OnBoard             | 1         | 0.04%   |
| Miron               | 1         | 0.04%   |
| Memox               | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 49        | 1.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 27        | 1.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 1.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 1%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 24        | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 21        | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 20        | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.8%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.76%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.72%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 16        | 0.64%   |
| Unknown                                                          | 16        | 0.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.6%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 15        | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.56%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 14        | 0.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 14        | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 13        | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.52%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 13        | 0.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 12        | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 0.48%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 10        | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.4%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 887       | 43.8%   |
| DDR3    | 659       | 32.54%  |
| DDR2    | 114       | 5.63%   |
| LPDDR4  | 113       | 5.58%   |
| LPDDR3  | 103       | 5.09%   |
| SDRAM   | 55        | 2.72%   |
| DDR5    | 35        | 1.73%   |
| LPDDR5  | 27        | 1.33%   |
| Unknown | 14        | 0.69%   |
| DDR     | 10        | 0.49%   |
| DRAM    | 8         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1737      | 86.37%  |
| Row Of Chips | 221       | 10.99%  |
| Unknown      | 24        | 1.19%   |
| Chip         | 19        | 0.94%   |
| DIMM         | 10        | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 856       | 38.7%   |
| 4096  | 633       | 28.62%  |
| 2048  | 286       | 12.93%  |
| 16384 | 282       | 12.75%  |
| 1024  | 84        | 3.8%    |
| 32768 | 57        | 2.58%   |
| 512   | 13        | 0.59%   |
| 256   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 475       | 21.89%  |
| 2667    | 431       | 19.86%  |
| 3200    | 333       | 15.35%  |
| 2400    | 149       | 6.87%   |
| 2133    | 123       | 5.67%   |
| 1334    | 92        | 4.24%   |
| 1333    | 66        | 3.04%   |
| 667     | 60        | 2.76%   |
| 1867    | 50        | 2.3%    |
| 4267    | 47        | 2.17%   |
| Unknown | 42        | 1.94%   |
| 1067    | 40        | 1.84%   |
| 4800    | 34        | 1.57%   |
| 800     | 29        | 1.34%   |
| 4199    | 27        | 1.24%   |
| 6400    | 26        | 1.2%    |
| 3266    | 25        | 1.15%   |
| 2048    | 21        | 0.97%   |
| 1066    | 18        | 0.83%   |
| 4266    | 14        | 0.65%   |
| 975     | 11        | 0.51%   |
| 533     | 10        | 0.46%   |
| 1866    | 8         | 0.37%   |
| 3733    | 6         | 0.28%   |
| 8400    | 5         | 0.23%   |
| 333     | 4         | 0.18%   |
| 3000    | 3         | 0.14%   |
| 1639    | 3         | 0.14%   |
| 400     | 3         | 0.14%   |
| 5600    | 2         | 0.09%   |
| 2933    | 2         | 0.09%   |
| 1776    | 2         | 0.09%   |
| 933     | 2         | 0.09%   |
| 7467    | 1         | 0.05%   |
| 5500    | 1         | 0.05%   |
| 1777    | 1         | 0.05%   |
| 1596    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |
| 666     | 1         | 0.05%   |
| 100     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 10        | 31.25%  |
| Hewlett-Packard       | 6         | 18.75%  |
| Brother Industries    | 4         | 12.5%   |
| Samsung Electronics   | 3         | 9.38%   |
| Lexmark International | 3         | 9.38%   |
| Prolific Technology   | 2         | 6.25%   |
| STMicroelectronics    | 1         | 3.13%   |
| Seiko Epson           | 1         | 3.13%   |
| Kyocera               | 1         | 3.13%   |
| KODAK                 | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series                                 | 3         | 9.09%   |
| Prolific PL2305 Parallel Port                             | 2         | 6.06%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.03%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 3.03%   |
| Samsung CLX-6260 Series                                   | 1         | 3.03%   |
| Samsung CLP-300 Series                                    | 1         | 3.03%   |
| Samsung C43x Series                                       | 1         | 3.03%   |
| Lexmark International MS610de                             | 1         | 3.03%   |
| Lexmark International C544                                | 1         | 3.03%   |
| Lexmark International 640 Series                          | 1         | 3.03%   |
| Kyocera FS-1041                                           | 1         | 3.03%   |
| KODAK ESP 5 AiO                                           | 1         | 3.03%   |
| HP Officejet 4630 series                                  | 1         | 3.03%   |
| HP LaserJet P2015 series                                  | 1         | 3.03%   |
| HP LaserJet 1010                                          | 1         | 3.03%   |
| HP ENVY Photo 6200 series                                 | 1         | 3.03%   |
| HP ENVY 4520 series                                       | 1         | 3.03%   |
| HP Deskjet 2540 series                                    | 1         | 3.03%   |
| Canon SELPHY CP400                                        | 1         | 3.03%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.03%   |
| Canon PIXMA MG2500 Series                                 | 1         | 3.03%   |
| Canon MF4360-4390                                         | 1         | 3.03%   |
| Canon LiDE 400                                            | 1         | 3.03%   |
| Canon LiDE 300                                            | 1         | 3.03%   |
| Canon iX6500 series                                       | 1         | 3.03%   |
| Canon iP4800 series                                       | 1         | 3.03%   |
| Brother PT-9500PC                                         | 1         | 3.03%   |
| Brother MFC-J4540DW                                       | 1         | 3.03%   |
| Brother DCP-L3510CDW                                      | 1         | 3.03%   |
| Brother DCP-7025 Printer                                  | 1         | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 62.5%   |
| Seiko Epson     | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 2         | 25%     |
| Seiko Epson Scanner                         | 1         | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 5300c/5370c                      | 1         | 12.5%   |
| Canon CanoScan LiDE 600F                    | 1         | 12.5%   |
| Canon CanoScan LiDE 220                     | 1         | 12.5%   |
| Canon CanoScan LiDE 200                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 882       | 25.35%  |
| Microdia                               | 392       | 11.27%  |
| IMC Networks                           | 303       | 8.71%   |
| Realtek Semiconductor                  | 297       | 8.54%   |
| Sunplus Innovation Technology          | 194       | 5.58%   |
| Bison Electronics                      | 194       | 5.58%   |
| Cheng Uei Precision Industry (Foxlink) | 140       | 4.02%   |
| Quanta                                 | 139       | 4%      |
| Suyin                                  | 110       | 3.16%   |
| Lite-On Technology                     | 95        | 2.73%   |
| Apple                                  | 86        | 2.47%   |
| Syntek                                 | 78        | 2.24%   |
| Acer                                   | 64        | 1.84%   |
| Silicon Motion                         | 63        | 1.81%   |
| Logitech                               | 52        | 1.49%   |
| Alcor Micro                            | 49        | 1.41%   |
| Ricoh                                  | 46        | 1.32%   |
| Lenovo                                 | 40        | 1.15%   |
| Luxvisions Innotech Limited            | 36        | 1.03%   |
| Samsung Electronics                    | 19        | 0.55%   |
| Sonix Technology                       | 16        | 0.46%   |
| ALi                                    | 16        | 0.46%   |
| Z-Star Microelectronics                | 15        | 0.43%   |
| Primax Electronics                     | 13        | 0.37%   |
| Microsoft                              | 12        | 0.34%   |
| SunplusIT                              | 8         | 0.23%   |
| Importek                               | 8         | 0.23%   |
| Sunplus Technology                     | 7         | 0.2%    |
| OmniVision Technologies                | 6         | 0.17%   |
| Intel                                  | 6         | 0.17%   |
| Generalplus Technology                 | 6         | 0.17%   |
| DigiTech                               | 6         | 0.17%   |
| GEMBIRD                                | 5         | 0.14%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.11%   |
| Razer USA                              | 4         | 0.11%   |
| ARC International                      | 4         | 0.11%   |
| MacroSilicon                           | 3         | 0.09%   |
| Google                                 | 3         | 0.09%   |
| Genesys Logic                          | 3         | 0.09%   |
| Foxconn / Hon Hai                      | 3         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 197       | 5.63%   |
| Chicony Integrated Camera                               | 160       | 4.57%   |
| Realtek Integrated_Webcam_HD                            | 108       | 3.08%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 87        | 2.49%   |
| IMC Networks Integrated Camera                          | 83        | 2.37%   |
| Chicony HD WebCam                                       | 71        | 2.03%   |
| Sunplus Integrated_Webcam_HD                            | 69        | 1.97%   |
| Chicony TOSHIBA Web Camera - HD                         | 54        | 1.54%   |
| Microdia Integrated Webcam                              | 41        | 1.17%   |
| Chicony USB2.0 Camera                                   | 40        | 1.14%   |
| Bison Integrated Camera                                 | 40        | 1.14%   |
| Chicony HP TrueVision HD Camera                         | 37        | 1.06%   |
| Lite-On Integrated Camera                               | 35        | 1%      |
| Syntek Integrated Camera                                | 32        | 0.91%   |
| Apple Built-in iSight                                   | 32        | 0.91%   |
| Chicony HP HD Camera                                    | 30        | 0.86%   |
| Chicony HP Truevision HD                                | 28        | 0.8%    |
| Bison BisonCam,NB Pro                                   | 28        | 0.8%    |
| Chicony EasyCamera                                      | 27        | 0.77%   |
| Quanta HD User Facing                                   | 26        | 0.74%   |
| Bison SunplusIT Integrated Camera                       | 26        | 0.74%   |
| Chicony VGA Webcam                                      | 25        | 0.71%   |
| Chicony Integrated Camera (1280x720@30)                 | 25        | 0.71%   |
| Syntek Lenovo EasyCamera                                | 24        | 0.69%   |
| Realtek USB Camera                                      | 24        | 0.69%   |
| Apple FaceTime HD Camera                                | 24        | 0.69%   |
| Alcor Micro USB 2.0 Camera                              | 24        | 0.69%   |
| Bison Lenovo EasyCamera                                 | 23        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 21        | 0.6%    |
| Chicony HP Wide Vision HD Camera                        | 21        | 0.6%    |
| Chicony USB 2.0 Camera                                  | 20        | 0.57%   |
| Chicony CNF9055 Toshiba Webcam                          | 20        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 20        | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 19        | 0.54%   |
| Lenovo Integrated Webcam [R5U877]                       | 19        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 19        | 0.54%   |
| Sunplus HD WebCam                                       | 18        | 0.51%   |
| Realtek Integrated Webcam HD                            | 18        | 0.51%   |
| Chicony HD User Facing                                  | 18        | 0.51%   |
| Suyin HP Truevision HD                                  | 17        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 223       | 32.84%  |
| Synaptics                          | 164       | 24.15%  |
| Shenzhen Goodix Technology         | 112       | 16.49%  |
| AuthenTec                          | 53        | 7.81%   |
| Upek                               | 52        | 7.66%   |
| LighTuning Technology              | 31        | 4.57%   |
| Elan Microelectronics              | 25        | 3.68%   |
| STMicroelectronics                 | 14        | 2.06%   |
| Samsung Electronics                | 2         | 0.29%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.29%   |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 59        | 8.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 50        | 7.36%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 44        | 6.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 6.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 38        | 5.6%    |
| Shenzhen Goodix FingerPrint                                                | 31        | 4.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 4.12%   |
| Validity Sensors Synaptics WBDI                                            | 22        | 3.24%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 3.24%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.8%    |
| Validity Sensors VFS491                                                    | 18        | 2.65%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 16        | 2.36%   |
| AuthenTec AES2810                                                          | 15        | 2.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 2.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.06%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.06%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 14        | 2.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.91%   |
| Elan ELAN:Fingerprint                                                      | 13        | 1.91%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.77%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.77%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 11        | 1.62%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.47%   |
| Synaptics UWP WBDI                                                         | 10        | 1.47%   |
| Unknown                                                                    | 10        | 1.47%   |
| Synaptics WBDI Device                                                      | 8         | 1.18%   |
| Synaptics UWP WBDI Device                                                  | 8         | 1.18%   |
| Synaptics  WBDI                                                            | 8         | 1.18%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.18%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.03%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 1.03%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.03%   |
| AuthenTec AES1600                                                          | 6         | 0.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.74%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.74%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.59%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 189       | 53.39%  |
| Alcor Micro           | 77        | 21.75%  |
| Upek                  | 29        | 8.19%   |
| O2 Micro              | 24        | 6.78%   |
| Lenovo                | 24        | 6.78%   |
| Gemalto (was Gemplus) | 4         | 1.13%   |
| SCM Microsystems      | 3         | 0.85%   |
| Purism, SPC           | 1         | 0.28%   |
| Clay Logic            | 1         | 0.28%   |
| Chicony Electronics   | 1         | 0.28%   |
| Cherry                | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 76        | 21.47%  |
| Broadcom BCM5880 Secure Applications Processor                               | 73        | 20.62%  |
| Broadcom 5880                                                                | 49        | 13.84%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 9.89%   |
| Broadcom 58200                                                               | 30        | 8.47%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 8.19%   |
| Lenovo Integrated Smart Card Reader                                          | 23        | 6.5%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 5.37%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.41%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.85%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.56%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.28%   |
| Purism, SPC Librem Key                                                       | 1         | 0.28%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.28%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.28%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.28%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.28%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2622      | 63.09%  |
| 1     | 1192      | 28.68%  |
| 2     | 288       | 6.93%   |
| 3     | 42        | 1.01%   |
| 4     | 5         | 0.12%   |
| 5     | 4         | 0.1%    |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 661       | 35.01%  |
| Chipcard                 | 323       | 17.11%  |
| Graphics card            | 312       | 16.53%  |
| Net/wireless             | 212       | 11.23%  |
| Multimedia controller    | 113       | 5.99%   |
| Communication controller | 43        | 2.28%   |
| Camera                   | 41        | 2.17%   |
| Storage                  | 40        | 2.12%   |
| Bluetooth                | 38        | 2.01%   |
| Sound                    | 22        | 1.17%   |
| Card reader              | 21        | 1.11%   |
| Net/ethernet             | 18        | 0.95%   |
| Modem                    | 16        | 0.85%   |
| Network                  | 8         | 0.42%   |
| Flash memory             | 8         | 0.42%   |
| Firewire controller      | 5         | 0.26%   |
| Storage/nvme             | 3         | 0.16%   |
| Unassigned class         | 2         | 0.11%   |
| Storage/ide              | 2         | 0.11%   |

