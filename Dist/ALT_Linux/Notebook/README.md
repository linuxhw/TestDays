ALT Linux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

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

Total: 336

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| Lenovo        | G70-70 80HW                 | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| HP            | EliteBook 2560p             | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| HP            | Mini 210-1000               | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Dell          | Vostro 3525                 | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| ICL           | RAYbook Si1407              | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Timi          | TM1701                      | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| Clevo         | NL41MU2                     | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| Clevo         | NL41MU2                     | [3c0893a822](https://linux-hardware.org/?probe=3c0893a822) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [ce24dc022b](https://linux-hardware.org/?probe=ce24dc022b) | May 10, 2023 |
| Clevo         | NL41MU2                     | [1d50da2ba5](https://linux-hardware.org/?probe=1d50da2ba5) | May 05, 2023 |
| F-PLUS EQU... | FNB-140-P1                  | [f78d6739f5](https://linux-hardware.org/?probe=f78d6739f5) | May 03, 2023 |
| Clevo         | NL41MU2                     | [67b2580836](https://linux-hardware.org/?probe=67b2580836) | May 03, 2023 |
| Acer          | Aspire 5935                 | [1ba45b2b8f](https://linux-hardware.org/?probe=1ba45b2b8f) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| Valve         | Jupiter                     | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| Valve         | Jupiter                     | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| Clevo         | NL41MU2                     | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | [2f1b310ca2](https://linux-hardware.org/?probe=2f1b310ca2) | Apr 21, 2023 |
| Clevo         | NL41MU2                     | [322f62ae77](https://linux-hardware.org/?probe=322f62ae77) | Apr 11, 2023 |
| Clevo         | NL41MU2                     | [720eed31f6](https://linux-hardware.org/?probe=720eed31f6) | Apr 10, 2023 |
| HP            | Pavilion dv6                | [5fddb7053d](https://linux-hardware.org/?probe=5fddb7053d) | Apr 07, 2023 |
| HP            | Pavilion dv6                | [67615ec9ff](https://linux-hardware.org/?probe=67615ec9ff) | Apr 05, 2023 |
| Timi          | TM1701                      | [5fc6e30961](https://linux-hardware.org/?probe=5fc6e30961) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK NH532              | [68a8171c0a](https://linux-hardware.org/?probe=68a8171c0a) | Mar 31, 2023 |
| ASUSTek       | K52JB                       | [45162c9123](https://linux-hardware.org/?probe=45162c9123) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | [c19cd604b3](https://linux-hardware.org/?probe=c19cd604b3) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [fc942702db](https://linux-hardware.org/?probe=fc942702db) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [ab5d4b339b](https://linux-hardware.org/?probe=ab5d4b339b) | Mar 30, 2023 |
| Clevo         | NL41MU2                     | [69abc76758](https://linux-hardware.org/?probe=69abc76758) | Mar 29, 2023 |
| Clevo         | NL41MU2                     | [60191a33b8](https://linux-hardware.org/?probe=60191a33b8) | Mar 27, 2023 |
| Clevo         | NL41MU2                     | [b56bf816d5](https://linux-hardware.org/?probe=b56bf816d5) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [88a5d2eb30](https://linux-hardware.org/?probe=88a5d2eb30) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [430f11129e](https://linux-hardware.org/?probe=430f11129e) | Mar 22, 2023 |
| HP            | Pavilion g7                 | [9fbef1354b](https://linux-hardware.org/?probe=9fbef1354b) | Mar 21, 2023 |
| ASUSTek       | X55A                        | [743d04e5fc](https://linux-hardware.org/?probe=743d04e5fc) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9e620a10f2](https://linux-hardware.org/?probe=9e620a10f2) | Mar 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [dcc115a880](https://linux-hardware.org/?probe=dcc115a880) | Mar 02, 2023 |
| Clevo         | NL41MU2                     | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Clevo         | NL41MU2                     | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| Clevo         | NL41MU2                     | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Clevo         | NL41MU2                     | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| Clevo         | NL41MU2                     | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| Clevo         | NL41MU2                     | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| Lenovo        | B560                        | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| Acer          | Aspire E1-530G              | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Dell          | Latitude 5580               | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| HP            | ProBook 440 G4              | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Clevo         | NL41MU2                     | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Timi          | Redmi Book Pro 14S          | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| Unknown       | Unknown                     | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Clevo         | NL41MU2                     | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| LTD Delovo... | 15Y                         | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Clevo         | NL41MU2                     | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| HP            | ProBook 440 G4              | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| Pegatron      | C15B                        | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| Apple         | MacBook4,1                  | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Irbis         | NB264                       | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| Unknown       | Unknown                     | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Unknown       | Unknown                     | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| Dell          | Vostro 14 5410              | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| HP            | 255 G4                      | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Samsung       | R560                        | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Timi          | TM1701                      | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Acer          | TravelMate 6292             | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| Toshiba       | dynabook Satellite T87/8... | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Acer          | AOA150                      | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| ASUSTek       | T100TAM                     | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| HUAWEI        | BOD-WXX9                    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | X550ZE                      | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| HP            | Pavilion g7                 | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| Lenovo        | G570 20079                  | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| HP            | Pavilion dv7                | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| Kraftway      | ACCORD                      | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| Panasonic     | CF-20-1                     | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| ICL           | Unknown                     | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| Lenovo        | V130-15IKB 81HN             | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| Apple         | MacBook7,1                  | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| ICL           | NJ50_70CU                   | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| Notebook      | NLx0MU                      | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Lenovo        | G570 20079                  | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| HP            | ZBook 17 G5                 | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| HP            | EliteBook 840 G4            | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| HP            | 250 G7 Notebook PC          | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| HP            | ProBook 440 G5              | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Timi          | TM1701                      | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| HP            | EliteBook 840 G4            | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Dell          | Latitude 3420               | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| Dell          | G5 5590                     | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| ASUSTek       | X200MA                      | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| Dell          | Latitude 3590               | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Samsung       | 750XDA                      | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASUSTek       | N46VZ                       | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Timi          | TM1701                      | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | N46VZ                       | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Durabook      | Z14                         | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| Aquarius      | NS585                       | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Dell          | G3 3779                     | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| HP            | EliteBook 8470p             | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Lenovo        | B50-10 80QR                 | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Acer          | NC-ES1-131-C1NL             | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| HP            | EliteBook 8470p             | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| HP            | Laptop 14s-dq1xxx           | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| Toshiba       | Satellite A100              | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| MSI           | X300/X340/X400 series       | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| ASUSTek       | N46VZ                       | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Samsung       | R510/P510                   | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire E1-571G              | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| HP            | Pavilion dv6700             | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| MSI           | MEGA BOOK S430              | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Lenovo        | G505s 20255                 | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| Samsung       | RV413/RV513/E3413           | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| Acer          | Aspire ES1-523              | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | 1001PXD                     | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Acer          | Aspire ES1-523              | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 54        | 21.6%   |
| ALT Linux 10.1     | 52        | 20.8%   |
| MOS 10             | 40        | 16%     |
| ALT Linux 10.0     | 30        | 12%     |
| ALT Linux 9.1      | 22        | 8.8%    |
| ALT Linux 9.2      | 10        | 4%      |
| ALT Linux 9.0      | 9         | 3.6%    |
| ALT Linux P10      | 6         | 2.4%    |
| ALT Linux 20201124 | 3         | 1.2%    |
| ALT Linux 10.2     | 3         | 1.2%    |
| ALT Linux 10.0.900 | 3         | 1.2%    |
| ALT Linux P9       | 2         | 0.8%    |
| ALT Linux P8       | 2         | 0.8%    |
| ALT Linux 8.2      | 2         | 0.8%    |
| ALT Linux 20220110 | 2         | 0.8%    |
| ALT Linux 20191026 | 2         | 0.8%    |
| ALT Linux 9        | 1         | 0.4%    |
| ALT Linux 8.990    | 1         | 0.4%    |
| ALT Linux 8.920    | 1         | 0.4%    |
| ALT Linux 8.3      | 1         | 0.4%    |
| ALT Linux 8.0.0    | 1         | 0.4%    |
| ALT Linux 20190624 | 1         | 0.4%    |
| ALT Linux 10.0.920 | 1         | 0.4%    |
| ALT Linux          | 1         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 235       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.10.102-std-def-alt1 | 38        | 14.34%  |
| 5.10.109-std-def-alt1 | 19        | 7.17%   |
| 5.10.139-std-def-alt1 | 15        | 5.66%   |
| 5.10.156-std-def-alt1 | 11        | 4.15%   |
| 5.15.34-un-def-alt1   | 8         | 3.02%   |
| 5.15.80-un-def-alt1   | 7         | 2.64%   |
| 5.10.88-std-def-alt1  | 7         | 2.64%   |
| 5.10.152-std-def-alt1 | 7         | 2.64%   |
| 5.10.123-std-def-alt1 | 6         | 2.26%   |
| 5.15.72-un-def-alt1   | 5         | 1.89%   |
| 5.15.76-un-def-alt1   | 4         | 1.51%   |
| 5.10.82-std-def-alt1  | 4         | 1.51%   |
| 5.10.164-std-def-alt1 | 4         | 1.51%   |
| 5.4.68-std-def-alt1.1 | 3         | 1.13%   |
| 5.4.28-std-def-alt1   | 3         | 1.13%   |
| 5.15.79-un-def-alt1   | 3         | 1.13%   |
| 5.15.73-un-def-alt1   | 3         | 1.13%   |
| 6.2.13-un-def-alt1    | 2         | 0.75%   |
| 6.1.30-un-def-alt1    | 2         | 0.75%   |
| 5.4.62-std-def-alt1   | 2         | 0.75%   |
| 5.4.51-std-def-alt1   | 2         | 0.75%   |
| 5.15.63-un-def-alt1   | 2         | 0.75%   |
| 5.15.52-un-def-alt1   | 2         | 0.75%   |
| 5.15.33-un-def-alt1   | 2         | 0.75%   |
| 5.15.25-un-def-alt1   | 2         | 0.75%   |
| 5.10.62-un-def-alt1   | 2         | 0.75%   |
| 5.10.61-un-def-alt1   | 2         | 0.75%   |
| 5.10.37-un-def-alt1   | 2         | 0.75%   |
| 5.10.32-un-def-alt1   | 2         | 0.75%   |
| 5.10.17-un-def-alt1   | 2         | 0.75%   |
| 5.10.168-std-def-alt1 | 2         | 0.75%   |
| 5.10.126-std-def-alt1 | 2         | 0.75%   |
| 5.10.113-std-def-alt1 | 2         | 0.75%   |
| 5.10.111-std-def-alt1 | 2         | 0.75%   |
| 4.19.79-std-def-alt1  | 2         | 0.75%   |
| 4.19.66-std-def-alt1  | 2         | 0.75%   |
| 4.19.102-std-def-alt1 | 2         | 0.75%   |
| 6.2.15-un-def-alt1    | 1         | 0.38%   |
| 6.1.29-un-def-alt1    | 1         | 0.38%   |
| 6.1.27-std-def-alt1   | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.102 | 38        | 14.34%  |
| 5.10.109 | 19        | 7.17%   |
| 5.10.139 | 15        | 5.66%   |
| 5.10.156 | 11        | 4.15%   |
| 5.15.80  | 8         | 3.02%   |
| 5.15.34  | 8         | 3.02%   |
| 5.10.88  | 7         | 2.64%   |
| 5.10.152 | 7         | 2.64%   |
| 5.10.123 | 6         | 2.26%   |
| 5.15.72  | 5         | 1.89%   |
| 5.15.76  | 4         | 1.51%   |
| 5.10.82  | 4         | 1.51%   |
| 5.10.164 | 4         | 1.51%   |
| 5.4.68   | 3         | 1.13%   |
| 5.4.28   | 3         | 1.13%   |
| 5.15.79  | 3         | 1.13%   |
| 5.15.73  | 3         | 1.13%   |
| 6.2.13   | 2         | 0.75%   |
| 6.1.30   | 2         | 0.75%   |
| 5.4.62   | 2         | 0.75%   |
| 5.4.51   | 2         | 0.75%   |
| 5.4.107  | 2         | 0.75%   |
| 5.15.91  | 2         | 0.75%   |
| 5.15.63  | 2         | 0.75%   |
| 5.15.52  | 2         | 0.75%   |
| 5.15.33  | 2         | 0.75%   |
| 5.15.25  | 2         | 0.75%   |
| 5.10.62  | 2         | 0.75%   |
| 5.10.61  | 2         | 0.75%   |
| 5.10.37  | 2         | 0.75%   |
| 5.10.32  | 2         | 0.75%   |
| 5.10.17  | 2         | 0.75%   |
| 5.10.168 | 2         | 0.75%   |
| 5.10.126 | 2         | 0.75%   |
| 5.10.118 | 2         | 0.75%   |
| 5.10.113 | 2         | 0.75%   |
| 5.10.111 | 2         | 0.75%   |
| 4.19.79  | 2         | 0.75%   |
| 4.19.66  | 2         | 0.75%   |
| 4.19.102 | 2         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 149       | 60.82%  |
| 5.15    | 46        | 18.78%  |
| 5.4     | 20        | 8.16%   |
| 4.19    | 11        | 4.49%   |
| 6.1     | 5         | 2.04%   |
| 6.2     | 3         | 1.22%   |
| 4.9     | 3         | 1.22%   |
| 5.18    | 2         | 0.82%   |
| 5.13    | 2         | 0.82%   |
| 5.7     | 1         | 0.41%   |
| 5.3     | 1         | 0.41%   |
| 5.16    | 1         | 0.41%   |
| 4.4     | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 224       | 95.32%  |
| i686   | 11        | 4.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 165       | 68.75%  |
| XFCE            | 32        | 13.33%  |
| Unknown         | 24        | 10%     |
| LXQt            | 7         | 2.92%   |
| Cinnamon        | 4         | 1.67%   |
| MATE            | 3         | 1.25%   |
| GNOME           | 3         | 1.25%   |
| GNOME Flashback | 2         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 228       | 96.61%  |
| Wayland | 4         | 1.69%   |
| Tty     | 3         | 1.27%   |
| Unknown | 1         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 136       | 56.2%   |
| LightDM | 57        | 23.55%  |
| Unknown | 24        | 9.92%   |
| TDM     | 22        | 9.09%   |
| GDM     | 2         | 0.83%   |
| XDM     | 1         | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| ru_RU      | 200       | 83.33%  |
| Unknown    | 26        | 10.83%  |
| en_US      | 10        | 4.17%   |
| POSIX      | 2         | 0.83%   |
| it_IT@euro | 1         | 0.42%   |
| C          | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 174       | 73.42%  |
| BIOS | 63        | 26.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 207       | 87.34%  |
| Overlay | 17        | 7.17%   |
| Btrfs   | 10        | 4.22%   |
| Unknown | 2         | 0.84%   |
| Xfs     | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 144       | 60.25%  |
| MBR     | 68        | 28.45%  |
| Unknown | 27        | 11.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 91.25%  |
| Yes       | 21        | 8.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 65.25%  |
| Yes       | 82        | 34.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Hewlett-Packard                   | 61        | 25.96%  |
| Clevo                             | 31        | 13.19%  |
| Lenovo                            | 24        | 10.21%  |
| ASUSTek Computer                  | 24        | 10.21%  |
| Acer                              | 17        | 7.23%   |
| ICL                               | 11        | 4.68%   |
| Dell                              | 10        | 4.26%   |
| HUAWEI                            | 9         | 3.83%   |
| Samsung Electronics               | 6         | 2.55%   |
| Apple                             | 5         | 2.13%   |
| 3Logic Group                      | 5         | 2.13%   |
| DEPO Computers                    | 4         | 1.7%    |
| Unknown                           | 4         | 1.7%    |
| MSI                               | 3         | 1.28%   |
| Toshiba                           | 2         | 0.85%   |
| Timi                              | 2         | 0.85%   |
| Panasonic                         | 2         | 0.85%   |
| Aquarius                          | 2         | 0.85%   |
| Valve                             | 1         | 0.43%   |
| Sony                              | 1         | 0.43%   |
| Pegatron                          | 1         | 0.43%   |
| LTD Delovoy Office                | 1         | 0.43%   |
| Kraftway                          | 1         | 0.43%   |
| IP3 Technology                    | 1         | 0.43%   |
| IP3 Tech                          | 1         | 0.43%   |
| Intel                             | 1         | 0.43%   |
| Fujitsu                           | 1         | 0.43%   |
| F-PLUS EQUIPMENT AND DEVELOPMENTS | 1         | 0.43%   |
| eMachines                         | 1         | 0.43%   |
| Durabook                          | 1         | 0.43%   |
| Compumax Computer                 | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Clevo NL41MU2                             | 31        | 13.19%  |
| HP 250 G7 Notebook PC                     | 12        | 5.11%   |
| HP ZBook 17 G5                            | 9         | 3.83%   |
| HP ProBook 440 G5                         | 8         | 3.4%    |
| ICL RAYbook Si1512                        | 6         | 2.55%   |
| Unknown                                   | 6         | 2.55%   |
| DEPO Computers DPC156                     | 4         | 1.7%    |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 3         | 1.28%   |
| HUAWEI NBD-WXX9                           | 3         | 1.28%   |
| HP EliteBook 840 G4                       | 3         | 1.28%   |
| HP 250 G6 Notebook PC                     | 3         | 1.28%   |
| Dell Latitude 3420                        | 3         | 1.28%   |
| ASUS VivoBook_ASUSLaptop M1503QA_M1503QA  | 3         | 1.28%   |
| 3Logic Group Graviton N15i-K2             | 3         | 1.28%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT      | 2         | 0.85%   |
| ICL NJ50_70CU                             | 2         | 0.85%   |
| HUAWEI KLVL-WXXW                          | 2         | 0.85%   |
| HP ProBook 440 G4                         | 2         | 0.85%   |
| HP EliteBook 8470p                        | 2         | 0.85%   |
| ASUS N46VZ                                | 2         | 0.85%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE | 2         | 0.85%   |
| Apple MacBook7,1                          | 2         | 0.85%   |
| Acer TravelMate 5760                      | 2         | 0.85%   |
| 3Logic Group Graviton N15i                | 2         | 0.85%   |
| Valve Jupiter                             | 1         | 0.43%   |
| Toshiba Satellite A100                    | 1         | 0.43%   |
| Toshiba dynabook Satellite T87/87M        | 1         | 0.43%   |
| Timi TM1701                               | 1         | 0.43%   |
| Timi Redmi Book Pro 14S                   | 1         | 0.43%   |
| Sony SVE1512H1RB                          | 1         | 0.43%   |
| Samsung SR70S/SR71S                       | 1         | 0.43%   |
| Samsung RV413/RV513/E3413                 | 1         | 0.43%   |
| Samsung R560                              | 1         | 0.43%   |
| Samsung R510/P510                         | 1         | 0.43%   |
| Samsung R509                              | 1         | 0.43%   |
| Samsung 750XDA                            | 1         | 0.43%   |
| Pegatron C15B                             | 1         | 0.43%   |
| Panasonic CF-C2CH2CBMG                    | 1         | 0.43%   |
| Panasonic CF-20-1                         | 1         | 0.43%   |
| MSI X300/X340/X400 series                 | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Clevo NL41MU2          | 31        | 13.19%  |
| HP 250                 | 16        | 6.81%   |
| HP ProBook             | 12        | 5.11%   |
| HP ZBook               | 9         | 3.83%   |
| HP Pavilion            | 9         | 3.83%   |
| Acer Aspire            | 9         | 3.83%   |
| ICL RAYbook            | 7         | 2.98%   |
| HP EliteBook           | 7         | 2.98%   |
| ASUS VivoBook          | 7         | 2.98%   |
| Lenovo ThinkPad        | 6         | 2.55%   |
| Unknown                | 6         | 2.55%   |
| Lenovo IdeaPad         | 5         | 2.13%   |
| Dell Latitude          | 5         | 2.13%   |
| ASUS ASUS              | 5         | 2.13%   |
| 3Logic Group Graviton  | 5         | 2.13%   |
| HP Laptop              | 4         | 1.7%    |
| DEPO Computers DPC156  | 4         | 1.7%    |
| Acer TravelMate        | 4         | 1.7%    |
| Lenovo ThinkBook       | 3         | 1.28%   |
| HUAWEI NBD-WXX9        | 3         | 1.28%   |
| ICL NJ50               | 2         | 0.85%   |
| HUAWEI KLVL-WXXW       | 2         | 0.85%   |
| HP 255                 | 2         | 0.85%   |
| Dell Vostro            | 2         | 0.85%   |
| ASUS N46VZ             | 2         | 0.85%   |
| Apple MacBook7         | 2         | 0.85%   |
| Valve Jupiter          | 1         | 0.43%   |
| Toshiba Satellite      | 1         | 0.43%   |
| Toshiba dynabook       | 1         | 0.43%   |
| Timi TM1701            | 1         | 0.43%   |
| Timi Redmi             | 1         | 0.43%   |
| Sony SVE1512H1RB       | 1         | 0.43%   |
| Samsung SR70S          | 1         | 0.43%   |
| Samsung RV413          | 1         | 0.43%   |
| Samsung R560           | 1         | 0.43%   |
| Samsung R510           | 1         | 0.43%   |
| Samsung R509           | 1         | 0.43%   |
| Samsung 750XDA         | 1         | 0.43%   |
| Pegatron C15B          | 1         | 0.43%   |
| Panasonic CF-C2CH2CBMG | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 47        | 20%     |
| 2021 | 31        | 13.19%  |
| 2018 | 26        | 11.06%  |
| 2017 | 20        | 8.51%   |
| 2020 | 19        | 8.09%   |
| 2019 | 16        | 6.81%   |
| 2011 | 12        | 5.11%   |
| 2010 | 10        | 4.26%   |
| 2008 | 9         | 3.83%   |
| 2016 | 8         | 3.4%    |
| 2014 | 8         | 3.4%    |
| 2012 | 7         | 2.98%   |
| 2009 | 7         | 2.98%   |
| 2015 | 4         | 1.7%    |
| 2013 | 4         | 1.7%    |
| 2007 | 4         | 1.7%    |
| 2006 | 2         | 0.85%   |
| 2023 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 235       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 180       | 75.63%  |
| Enabled  | 58        | 24.37%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 235       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 108       | 45.76%  |
| 16.01-24.0  | 51        | 21.61%  |
| 3.01-4.0    | 34        | 14.41%  |
| 8.01-16.0   | 21        | 8.9%    |
| 1.01-2.0    | 15        | 6.36%   |
| 2.01-3.0    | 3         | 1.27%   |
| 32.01-64.0  | 2         | 0.85%   |
| 64.01-256.0 | 1         | 0.42%   |
| 0.51-1.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 121       | 48.02%  |
| 2.01-3.0  | 50        | 19.84%  |
| 0.51-1.0  | 35        | 13.89%  |
| 3.01-4.0  | 20        | 7.94%   |
| 4.01-8.0  | 18        | 7.14%   |
| 0.01-0.5  | 5         | 1.98%   |
| 8.01-16.0 | 3         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 189       | 78.75%  |
| 2      | 42        | 17.5%   |
| 3      | 5         | 2.08%   |
| 0      | 3         | 1.25%   |
| 4      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 165       | 69.62%  |
| Yes       | 72        | 30.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 87.66%  |
| No        | 29        | 12.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 233       | 99.15%  |
| No        | 2         | 0.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 83.47%  |
| No        | 39        | 16.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Russia     | 220       | 93.62%  |
| Greece     | 4         | 1.7%    |
| Egypt      | 2         | 0.85%   |
| Uzbekistan | 1         | 0.43%   |
| Ukraine    | 1         | 0.43%   |
| Moldova    | 1         | 0.43%   |
| Italy      | 1         | 0.43%   |
| France     | 1         | 0.43%   |
| Czechia    | 1         | 0.43%   |
| Costa Rica | 1         | 0.43%   |
| Colombia   | 1         | 0.43%   |
| Belarus    | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 148       | 61.67%  |
| St Petersburg     | 12        | 5%      |
| Novosibirsk       | 6         | 2.5%    |
| Samara            | 4         | 1.67%   |
| Barnaul           | 4         | 1.67%   |
| Astrakhan         | 3         | 1.25%   |
| Voronezh          | 2         | 0.83%   |
| Tyumen            | 2         | 0.83%   |
| Saratov           | 2         | 0.83%   |
| Perm              | 2         | 0.83%   |
| Korolyov          | 2         | 0.83%   |
| Belgorod          | 2         | 0.83%   |
| Yekaterinburg     | 1         | 0.42%   |
| Vladimir          | 1         | 0.42%   |
| Verkhnyaya Pyshma | 1         | 0.42%   |
| Vergina           | 1         | 0.42%   |
| Ufa               | 1         | 0.42%   |
| Tura              | 1         | 0.42%   |
| Troitsk           | 1         | 0.42%   |
| Thessaloniki      | 1         | 0.42%   |
| Tashkent          | 1         | 0.42%   |
| Tambov            | 1         | 0.42%   |
| Surgut            | 1         | 0.42%   |
| Suez              | 1         | 0.42%   |
| Stary Oskol       | 1         | 0.42%   |
| Shepsi            | 1         | 0.42%   |
| Sevastopol        | 1         | 0.42%   |
| San José         | 1         | 0.42%   |
| Rubtsovsk         | 1         | 0.42%   |
| Roubaix           | 1         | 0.42%   |
| Rostov-on-Don     | 1         | 0.42%   |
| Prague            | 1         | 0.42%   |
| Omsk              | 1         | 0.42%   |
| Obninsk           | 1         | 0.42%   |
| Novorossiysk      | 1         | 0.42%   |
| Novichikha        | 1         | 0.42%   |
| Nizhny Tagil      | 1         | 0.42%   |
| Milan             | 1         | 0.42%   |
| Lipetsk           | 1         | 0.42%   |
| Lesosibirsk       | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| BIWIN                        | 32        | 33     | 11.47%  |
| Seagate                      | 31        | 36     | 11.11%  |
| Intel                        | 28        | 31     | 10.04%  |
| Samsung Electronics          | 27        | 40     | 9.68%   |
| WDC                          | 25        | 29     | 8.96%   |
| SK hynix                     | 19        | 21     | 6.81%   |
| Kingston                     | 15        | 15     | 5.38%   |
| Toshiba                      | 11        | 15     | 3.94%   |
| Foxline                      | 9         | 9      | 3.23%   |
| Phison                       | 7         | 8      | 2.51%   |
| Hitachi                      | 7         | 7      | 2.51%   |
| A-DATA Technology            | 6         | 8      | 2.15%   |
| HGST                         | 5         | 5      | 1.79%   |
| Unknown                      | 4         | 8      | 1.43%   |
| SanDisk                      | 4         | 4      | 1.43%   |
| Fujitsu                      | 4         | 4      | 1.43%   |
| XPG                          | 3         | 4      | 1.08%   |
| KingSpec                     | 3         | 3      | 1.08%   |
| Gigabyte Technology          | 3         | 3      | 1.08%   |
| Crucial                      | 3         | 3      | 1.08%   |
| Apacer                       | 3         | 4      | 1.08%   |
| Transcend                    | 2         | 2      | 0.72%   |
| SSSTC                        | 2         | 2      | 0.72%   |
| Phison Electronics           | 2         | 2      | 0.72%   |
| AMD                          | 2         | 2      | 0.72%   |
| Unknown                      | 2         | 2      | 0.72%   |
| Yangtze Memory Technologies  | 1         | 1      | 0.36%   |
| XrayDisk                     | 1         | 1      | 0.36%   |
| Smartbuy                     | 1         | 1      | 0.36%   |
| Silicon Motion               | 1         | 1      | 0.36%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.36%   |
| PNY                          | 1         | 1      | 0.36%   |
| Plextor                      | 1         | 1      | 0.36%   |
| Micron Technology            | 1         | 1      | 0.36%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.36%   |
| LuminouTek                   | 1         | 1      | 0.36%   |
| KIOXIA                       | 1         | 2      | 0.36%   |
| KingDian                     | 1         | 1      | 0.36%   |
| GOODRAM                      | 1         | 1      | 0.36%   |
| FORESEE                      | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| BIWIN CE480T5D101-256 256GB             | 32        | 11.15%  |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 12        | 4.18%   |
| Foxline FLSSD256M80E13TCX5 256GB        | 9         | 3.14%   |
| Seagate ST1000LM049-2GH172 1TB          | 8         | 2.79%   |
| Intel SSDPEMKF256G8H 256GB              | 8         | 2.79%   |
| Intel SSDPEKKF256G7H 256GB              | 8         | 2.79%   |
| Phison 311CD0512GB                      | 5         | 1.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 1.39%   |
| Samsung MZALQ256HAJD-000L2 256GB        | 4         | 1.39%   |
| Kingston OM8PDP3256B-A01 256GB          | 3         | 1.05%   |
| Intel SSDPEKNW512G8H 512GB              | 3         | 1.05%   |
| Intel SSDPEKNU512GZ 512GB               | 3         | 1.05%   |
| XPG SPECTRIX S40G 4TB                   | 2         | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.7%    |
| WDC WD5000LPLX-60ZNTT2 500GB            | 2         | 0.7%    |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 0.7%    |
| Transcend TS240GSSD220S 240GB           | 2         | 0.7%    |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.7%    |
| Toshiba KXG50ZNV256G 256GB              | 2         | 0.7%    |
| SSSTC CL1-3D256-Q11 NVMe 256GB          | 2         | 0.7%    |
| Seagate ST9250315AS 250GB               | 2         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.7%    |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.7%    |
| Samsung SSD 860 EVO M.2 250GB           | 2         | 0.7%    |
| Samsung SSD 860 EVO 250GB               | 2         | 0.7%    |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.7%    |
| Samsung MZVLQ512HALU-000H1 512GB        | 2         | 0.7%    |
| Kingston SUV400S37120G 120GB SSD        | 2         | 0.7%    |
| HGST HTS721010A9E630 1TB                | 2         | 0.7%    |
| Gigabyte GP-GSM2NE3256GNTD 256GB        | 2         | 0.7%    |
| Crucial CT120BX500SSD1 120GB            | 2         | 0.7%    |
| Unknown                                 | 2         | 0.7%    |
| Yangtze Memory NVMe SSD Drive 256GB     | 1         | 0.35%   |
| XrayDisk 240GB SSD                      | 1         | 0.35%   |
| XPG NVMe SSD Drive 256GB                | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.35%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 31        | 36     | 41.89%  |
| WDC      | 17        | 18     | 22.97%  |
| Toshiba  | 9         | 13     | 12.16%  |
| Hitachi  | 7         | 7      | 9.46%   |
| HGST     | 5         | 5      | 6.76%   |
| Fujitsu  | 4         | 4      | 5.41%   |
| External | 1         | 2      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 18.18%  |
| WDC                 | 5         | 8      | 9.09%   |
| Kingston            | 5         | 5      | 9.09%   |
| A-DATA Technology   | 4         | 4      | 7.27%   |
| KingSpec            | 3         | 3      | 5.45%   |
| Intel               | 3         | 3      | 5.45%   |
| Transcend           | 2         | 2      | 3.64%   |
| SK hynix            | 2         | 2      | 3.64%   |
| SanDisk             | 2         | 2      | 3.64%   |
| Crucial             | 2         | 2      | 3.64%   |
| AMD                 | 2         | 2      | 3.64%   |
| XrayDisk            | 1         | 1      | 1.82%   |
| Smartbuy            | 1         | 1      | 1.82%   |
| PNY                 | 1         | 1      | 1.82%   |
| Plextor             | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| LuminouTek          | 1         | 1      | 1.82%   |
| KingDian            | 1         | 1      | 1.82%   |
| GOODRAM             | 1         | 1      | 1.82%   |
| Gigabyte Technology | 1         | 1      | 1.82%   |
| Foxline             | 1         | 1      | 1.82%   |
| China               | 1         | 1      | 1.82%   |
| Biwintech           | 1         | 2      | 1.82%   |
| BaseTech            | 1         | 1      | 1.82%   |
| Apacer              | 1         | 2      | 1.82%   |
| Unknown             | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 137       | 166    | 50.55%  |
| HDD  | 73        | 85     | 26.94%  |
| SSD  | 54        | 61     | 19.93%  |
| MMC  | 7         | 11     | 2.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 137       | 166    | 53.31%  |
| SATA | 108       | 140    | 42.02%  |
| MMC  | 7         | 11     | 2.72%   |
| SAS  | 5         | 6      | 1.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 98     | 70.83%  |
| 0.51-1.0   | 31        | 44     | 25.83%  |
| 1.01-2.0   | 3         | 3      | 2.5%    |
| 4.01-10.0  | 1         | 1      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 133       | 54.29%  |
| 251-500    | 38        | 15.51%  |
| 51-100     | 26        | 10.61%  |
| 21-50      | 14        | 5.71%   |
| 501-1000   | 12        | 4.9%    |
| 1-20       | 11        | 4.49%   |
| 1001-2000  | 7         | 2.86%   |
| 2001-3000  | 3         | 1.22%   |
| Unknown    | 1         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 130       | 52%     |
| 21-50     | 61        | 24.4%   |
| 51-100    | 23        | 9.2%    |
| 101-250   | 16        | 6.4%    |
| 251-500   | 9         | 3.6%    |
| 501-1000  | 6         | 2.4%    |
| 1001-2000 | 4         | 1.6%    |
| Unknown   | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                  | Notebooks | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB                              | 2         | 2      | 8%      |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 7      | 8%      |
| XrayDisk 240GB SSD                                     | 1         | 1      | 4%      |
| WDC WD5000LPVX-60V0TT0 500GB                           | 1         | 1      | 4%      |
| WDC WD5000LPLX-60ZNTT2 500GB                           | 1         | 1      | 4%      |
| WDC WD1200BEVS-60UST0 120GB                            | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB                               | 1         | 1      | 4%      |
| Toshiba MK1637GSX 160GB                                | 1         | 1      | 4%      |
| SK hynix HFS128G39TND-N210A 128GB SSD                  | 1         | 1      | 4%      |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                | 1         | 1      | 4%      |
| Shenzhen Longsys Electronics FORESEE XP1000F512G 512GB | 1         | 1      | 4%      |
| Seagate ST9640320AS 640GB                              | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB                              | 1         | 1      | 4%      |
| Seagate ST9320423AS 320GB                              | 1         | 1      | 4%      |
| Intel SSDSCKKF256H6H 256GB                             | 1         | 1      | 4%      |
| Intel SSDSC2BW480A4 480GB                              | 1         | 1      | 4%      |
| Hitachi HTS725050A9A364 500GB                          | 1         | 1      | 4%      |
| Hitachi HTS543225L9A300 250GB                          | 1         | 1      | 4%      |
| Hitachi HTS542525K9A300 250GB                          | 1         | 1      | 4%      |
| Hitachi HTS541610J9SA00 100GB                          | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB                             | 1         | 1      | 4%      |
| Fujitsu MHW2160BH PL 160GB                             | 1         | 1      | 4%      |
| AMD R5SL120G 120GB SSD                                 | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 7         | 12     | 28%     |
| Hitachi                      | 4         | 4      | 16%     |
| WDC                          | 3         | 3      | 12%     |
| Toshiba                      | 2         | 2      | 8%      |
| SK hynix                     | 2         | 2      | 8%      |
| Intel                        | 2         | 2      | 8%      |
| XrayDisk                     | 1         | 1      | 4%      |
| Shenzhen Longsys Electronics | 1         | 1      | 4%      |
| HGST                         | 1         | 1      | 4%      |
| Fujitsu                      | 1         | 1      | 4%      |
| AMD                          | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 12     | 38.89%  |
| Hitachi | 4         | 4      | 22.22%  |
| WDC     | 3         | 3      | 16.67%  |
| Toshiba | 2         | 2      | 11.11%  |
| HGST    | 1         | 1      | 5.56%   |
| Fujitsu | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 23     | 72%     |
| SSD  | 5         | 5      | 20%     |
| NVMe | 2         | 2      | 8%      |

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
| Works    | 188       | 234    | 75.81%  |
| Detected | 35        | 59     | 14.11%  |
| Malfunc  | 25        | 30     | 10.08%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 184       | 56.62%  |
| INNOGRIT                       | 32        | 9.85%   |
| Phison Electronics             | 19        | 5.85%   |
| AMD                            | 18        | 5.54%   |
| Samsung Electronics            | 17        | 5.23%   |
| SK hynix                       | 16        | 4.92%   |
| Kingston Technology Company    | 10        | 3.08%   |
| SanDisk                        | 5         | 1.54%   |
| Nvidia                         | 5         | 1.54%   |
| Shenzhen Longsys Electronics   | 3         | 0.92%   |
| Toshiba America Info Systems   | 2         | 0.62%   |
| Solid State Storage Technology | 2         | 0.62%   |
| Realtek Semiconductor          | 2         | 0.62%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.62%   |
| ADATA Technology               | 2         | 0.62%   |
| Yangtze Memory Technologies    | 1         | 0.31%   |
| VIA Technologies               | 1         | 0.31%   |
| Silicon Motion                 | 1         | 0.31%   |
| Micron/Crucial Technology      | 1         | 0.31%   |
| KIOXIA                         | 1         | 0.31%   |
| Apple                          | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP SATA Controller                                          | 41        | 11.45%  |
| INNOGRIT Non-Volatile memory controller                                      | 32        | 8.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 26        | 7.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 19        | 5.31%   |
| Phison PS5013 E13 NVMe Controller                                            | 17        | 4.75%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 16        | 4.47%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 13        | 3.63%   |
| Intel Comet Lake SATA AHCI Controller                                        | 13        | 3.63%   |
| Samsung NVMe SSD Controller 980                                              | 10        | 2.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 10        | 2.79%   |
| Intel SSD 600P Series                                                        | 9         | 2.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 9         | 2.51%   |
| Intel Volume Management Device NVMe RAID Controller                          | 8         | 2.23%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 8         | 2.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 8         | 2.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 8         | 2.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 7         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 7         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 5         | 1.4%    |
| Kingston Company Company Non-Volatile memory controller                      | 4         | 1.12%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 4         | 1.12%   |
| Intel Non-Volatile memory controller                                         | 4         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 4         | 1.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 4         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 3         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 0.84%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 2         | 0.56%   |
| Solid State Storage Non-Volatile memory controller                           | 2         | 0.56%   |
| SK hynix BC511                                                               | 2         | 0.56%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                  | 2         | 0.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 2         | 0.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 2         | 0.56%   |
| Realtek RTS5763DL NVMe SSD Controller                                        | 2         | 0.56%   |
| Phison E12 NVMe Controller                                                   | 2         | 0.56%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                 | 2         | 0.56%   |
| Intel SSD 660P Series                                                        | 2         | 0.56%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 0.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 0.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 171       | 49%     |
| NVMe | 136       | 38.97%  |
| RAID | 27        | 7.74%   |
| IDE  | 15        | 4.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 201       | 85.53%  |
| AMD          | 33        | 14.04%  |
| CentaurHauls | 1         | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 46        | 19.57%  |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 5.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 5.11%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 11        | 4.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 4.26%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 7         | 2.98%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 2.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.28%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 1.28%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1.28%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.28%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.28%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.85%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 2         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.85%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.85%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 0.85%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 0.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.85%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.43%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.43%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.43%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.43%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.43%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.43%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.43%   |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 0.43%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.43%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.43%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.43%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 56        | 23.83%  |
| Other                   | 55        | 23.4%   |
| Intel Core i3           | 31        | 13.19%  |
| Intel Core i7           | 21        | 8.94%   |
| AMD Ryzen 5             | 11        | 4.68%   |
| Intel Core 2 Duo        | 10        | 4.26%   |
| AMD Ryzen 7             | 9         | 3.83%   |
| Intel Celeron           | 7         | 2.98%   |
| Intel Atom              | 6         | 2.55%   |
| Intel Pentium           | 5         | 2.13%   |
| AMD A8                  | 4         | 1.7%    |
| Intel Pentium Silver    | 2         | 0.85%   |
| Intel Pentium Gold      | 2         | 0.85%   |
| AMD E1                  | 2         | 0.85%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Pentium Dual      | 1         | 0.43%   |
| Intel Genuine           | 1         | 0.43%   |
| Intel Core m5           | 1         | 0.43%   |
| Intel Core Duo          | 1         | 0.43%   |
| Intel Core 2 Solo       | 1         | 0.43%   |
| Intel Celeron Dual-Core | 1         | 0.43%   |
| CentaurHauls VIA C7     | 1         | 0.43%   |
| AMD Turion 64 X2 Mobile | 1         | 0.43%   |
| AMD FX                  | 1         | 0.43%   |
| AMD E                   | 1         | 0.43%   |
| AMD C-60                | 1         | 0.43%   |
| AMD Athlon 64 X2        | 1         | 0.43%   |
| AMD A6                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 110       | 46.81%  |
| 2      | 90        | 38.3%   |
| 6      | 18        | 7.66%   |
| 8      | 8         | 3.4%    |
| 1      | 7         | 2.98%   |
| 12     | 1         | 0.43%   |
| 10     | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 235       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 193       | 82.13%  |
| 1      | 42        | 17.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 229       | 97.45%  |
| 32-bit         | 5         | 2.13%   |
| Unknown        | 1         | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 49        | 20.42%  |
| Unknown    | 39        | 16.25%  |
| 0x806e9    | 18        | 7.5%    |
| 0x806ec    | 15        | 6.25%   |
| 0x806ea    | 14        | 5.83%   |
| 0x906ea    | 11        | 4.58%   |
| 0xa0660    | 8         | 3.33%   |
| 0x1067a    | 8         | 3.33%   |
| 0x306a9    | 6         | 2.5%    |
| 0x206a7    | 6         | 2.5%    |
| 0x706e5    | 5         | 2.08%   |
| 0x406e3    | 4         | 1.67%   |
| 0x0a50000c | 4         | 1.67%   |
| 0x08600106 | 4         | 1.67%   |
| 0x40651    | 3         | 1.25%   |
| 0x106ca    | 3         | 1.25%   |
| 0x08108109 | 3         | 1.25%   |
| 0x706a8    | 2         | 0.83%   |
| 0x6fd      | 2         | 0.83%   |
| 0x306c3    | 2         | 0.83%   |
| 0x30678    | 2         | 0.83%   |
| 0x20655    | 2         | 0.83%   |
| 0x106c2    | 2         | 0.83%   |
| 0x10676    | 2         | 0.83%   |
| 0x08608102 | 2         | 0.83%   |
| 0x0700010f | 2         | 0.83%   |
| 0xa0652    | 1         | 0.42%   |
| 0x906c0    | 1         | 0.42%   |
| 0x906a4    | 1         | 0.42%   |
| 0x906a3    | 1         | 0.42%   |
| 0x806c2    | 1         | 0.42%   |
| 0x706a1    | 1         | 0.42%   |
| 0x6fa      | 1         | 0.42%   |
| 0x6ec      | 1         | 0.42%   |
| 0x6e8      | 1         | 0.42%   |
| 0x506c9    | 1         | 0.42%   |
| 0x406c3    | 1         | 0.42%   |
| 0x20652    | 1         | 0.42%   |
| 0x106e5    | 1         | 0.42%   |
| 0x0a404101 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 67        | 28.51%  |
| TigerLake        | 53        | 22.55%  |
| Penryn           | 10        | 4.26%   |
| SandyBridge      | 9         | 3.83%   |
| CometLake        | 9         | 3.83%   |
| Zen 3            | 8         | 3.4%    |
| IvyBridge        | 8         | 3.4%    |
| Westmere         | 6         | 2.55%   |
| Haswell          | 6         | 2.55%   |
| Unknown          | 6         | 2.55%   |
| Zen 2            | 5         | 2.13%   |
| IceLake          | 5         | 2.13%   |
| Bonnell          | 5         | 2.13%   |
| Zen+             | 4         | 1.7%    |
| Skylake          | 4         | 1.7%    |
| Silvermont       | 4         | 1.7%    |
| Goldmont plus    | 4         | 1.7%    |
| Core             | 4         | 1.7%    |
| P6               | 2         | 0.85%   |
| K8 Hammer        | 2         | 0.85%   |
| K10 Llano        | 2         | 0.85%   |
| Jaguar           | 2         | 0.85%   |
| Bobcat           | 2         | 0.85%   |
| Tremont          | 1         | 0.43%   |
| Steamroller      | 1         | 0.43%   |
| Puma             | 1         | 0.43%   |
| Piledriver       | 1         | 0.43%   |
| Nehalem          | 1         | 0.43%   |
| Goldmont         | 1         | 0.43%   |
| Excavator        | 1         | 0.43%   |
| Alderlake Hybrid | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 187       | 69.52%  |
| Nvidia           | 43        | 15.99%  |
| AMD              | 38        | 14.13%  |
| VIA Technologies | 1         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 49        | 17.63%  |
| Intel HD Graphics 620                                                         | 23        | 8.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 13        | 4.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 3.6%    |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                         | 9         | 3.24%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                              | 9         | 3.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9         | 3.24%   |
| Intel Comet Lake UHD Graphics                                                 | 8         | 2.88%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 8         | 2.88%   |
| Intel UHD Graphics 620                                                        | 5         | 1.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 1.8%    |
| AMD Renoir                                                                    | 5         | 1.8%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 4         | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 1.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 1.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 1.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 1.08%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 1.08%   |
| AMD Barcelo                                                                   | 3         | 1.08%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 2         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 2         | 0.72%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 2         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 0.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 0.72%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 0.72%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 0.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 0.72%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 0.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 0.72%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 2         | 0.72%   |
| AMD Lucienne                                                                  | 2         | 0.72%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]              | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 155       | 65.96%  |
| Intel + Nvidia | 27        | 11.49%  |
| 1 x AMD        | 25        | 10.64%  |
| 1 x Nvidia     | 12        | 5.11%   |
| 2 x AMD        | 5         | 2.13%   |
| Intel + AMD    | 4         | 1.7%    |
| AMD + Nvidia   | 4         | 1.7%    |
| Other          | 1         | 0.43%   |
| 2 x Intel      | 1         | 0.43%   |
| 1 x VIA        | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 217       | 91.56%  |
| Proprietary | 15        | 6.33%   |
| Unknown     | 5         | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 78.75%  |
| 0.01-0.5   | 22        | 9.17%   |
| 0.51-1.0   | 12        | 5%      |
| 3.01-4.0   | 10        | 4.17%   |
| 1.01-2.0   | 7         | 2.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 56        | 21.79%  |
| BOE                     | 54        | 21.01%  |
| AU Optronics            | 35        | 13.62%  |
| LG Display              | 24        | 9.34%   |
| Samsung Electronics     | 17        | 6.61%   |
| PANDA                   | 13        | 5.06%   |
| Sharp                   | 8         | 3.11%   |
| Chi Mei Optoelectronics | 6         | 2.33%   |
| PRM                     | 5         | 1.95%   |
| Apple                   | 5         | 1.95%   |
| BenQ                    | 4         | 1.56%   |
| AOC                     | 4         | 1.56%   |
| STA                     | 3         | 1.17%   |
| VIE                     | 2         | 0.78%   |
| AGO                     | 2         | 0.78%   |
| Valve                   | 1         | 0.39%   |
| TR_                     | 1         | 0.39%   |
| Toshiba                 | 1         | 0.39%   |
| Sony                    | 1         | 0.39%   |
| SBI                     | 1         | 0.39%   |
| RGT                     | 1         | 0.39%   |
| Panasonic               | 1         | 0.39%   |
| OBT                     | 1         | 0.39%   |
| KDC                     | 1         | 0.39%   |
| InnoLux Display         | 1         | 0.39%   |
| InfoVision              | 1         | 0.39%   |
| HKC                     | 1         | 0.39%   |
| Hitachi                 | 1         | 0.39%   |
| HannStar                | 1         | 0.39%   |
| Goldstar                | 1         | 0.39%   |
| FME                     | 1         | 0.39%   |
| CS_                     | 1         | 0.39%   |
| CPT                     | 1         | 0.39%   |
| Acer                    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 12        | 4.65%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 9         | 3.49%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 9         | 3.49%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 8         | 3.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 3.1%    |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                 | 6         | 2.33%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch        | 5         | 1.94%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 4         | 1.55%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                 | 4         | 1.55%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                 | 3         | 1.16%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch               | 3         | 1.16%   |
| Sharp LCD Monitor SHP1540 1920x1080 309x174mm 14.0-inch               | 3         | 1.16%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch          | 3         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.16%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 1.16%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 1.16%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.16%   |
| VIE IM27VL1 VIE2120 1920x1080 600x330mm 27.0-inch                     | 2         | 0.78%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 330x210mm 15.4-inch | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.78%   |
| PRM UST-P1 PRM7644 1920x1080                                          | 2         | 0.78%   |
| PRM 35 PRM2733 1280x1024                                              | 2         | 0.78%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 2         | 0.78%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO133C 1366x768 309x173mm 13.9-inch         | 2         | 0.78%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                 | 2         | 0.78%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 154       | 64.17%  |
| 1366x768 (WXGA)    | 43        | 17.92%  |
| 1280x800 (WXGA)    | 11        | 4.58%   |
| 1600x900 (HD+)     | 7         | 2.92%   |
| 1280x1024 (SXGA)   | 6         | 2.5%    |
| 2560x1600          | 3         | 1.25%   |
| 1024x600           | 3         | 1.25%   |
| 2160x1440          | 2         | 0.83%   |
| 1920x1200 (WUXGA)  | 2         | 0.83%   |
| 1680x1050 (WSXGA+) | 2         | 0.83%   |
| 1440x900 (WXGA+)   | 2         | 0.83%   |
| 800x1280           | 1         | 0.42%   |
| 3200x1800 (QHD+)   | 1         | 0.42%   |
| 2880x1620          | 1         | 0.42%   |
| 2560x1440 (QHD)    | 1         | 0.42%   |
| 1400x1050          | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 100       | 38.91%  |
| 13      | 48        | 18.68%  |
| 14      | 39        | 15.18%  |
| 17      | 22        | 8.56%   |
| 12      | 8         | 3.11%   |
| Unknown | 7         | 2.72%   |
| 24      | 5         | 1.95%   |
| 23      | 5         | 1.95%   |
| 27      | 4         | 1.56%   |
| 11      | 4         | 1.56%   |
| 21      | 3         | 1.17%   |
| 19      | 3         | 1.17%   |
| 10      | 3         | 1.17%   |
| 16      | 2         | 0.78%   |
| 59      | 1         | 0.39%   |
| 50      | 1         | 0.39%   |
| 8       | 1         | 0.39%   |
| 7       | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 67.7%   |
| 201-300     | 28        | 10.89%  |
| 351-400     | 25        | 9.73%   |
| 501-600     | 13        | 5.06%   |
| Unknown     | 7         | 2.72%   |
| 401-500     | 5         | 1.95%   |
| 1001-1500   | 2         | 0.78%   |
| 601-700     | 1         | 0.39%   |
| 101-200     | 1         | 0.39%   |
| 1-100       | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 206       | 85.12%  |
| 16/10 | 21        | 8.68%   |
| 5/4   | 5         | 2.07%   |
| 4/3   | 4         | 1.65%   |
| 3/2   | 4         | 1.65%   |
| 6/5   | 1         | 0.41%   |
| 0.67  | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 39.3%   |
| 81-90          | 80        | 31.13%  |
| 121-130        | 21        | 8.17%   |
| 71-80          | 10        | 3.89%   |
| 201-250        | 10        | 3.89%   |
| Unknown        | 7         | 2.72%   |
| 61-70          | 5         | 1.95%   |
| 51-60          | 4         | 1.56%   |
| 301-350        | 4         | 1.56%   |
| 41-50          | 3         | 1.17%   |
| 251-300        | 3         | 1.17%   |
| 151-200        | 3         | 1.17%   |
| More than 1000 | 2         | 0.78%   |
| 1-40           | 2         | 0.78%   |
| 131-140        | 1         | 0.39%   |
| 111-120        | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 161       | 62.89%  |
| 101-120       | 47        | 18.36%  |
| 51-100        | 24        | 9.38%   |
| 161-240       | 14        | 5.47%   |
| Unknown       | 7         | 2.73%   |
| 1-50          | 2         | 0.78%   |
| More than 240 | 1         | 0.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 208       | 87.39%  |
| 2     | 27        | 11.34%  |
| 0     | 2         | 0.84%   |
| 3     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 140       | 41.42%  |
| Realtek Semiconductor           | 97        | 28.7%   |
| Qualcomm Atheros                | 35        | 10.36%  |
| Broadcom                        | 23        | 6.8%    |
| Marvell Technology Group        | 6         | 1.78%   |
| D-Link                          | 6         | 1.78%   |
| Nvidia                          | 5         | 1.48%   |
| MediaTek                        | 5         | 1.48%   |
| JMicron Technology              | 3         | 0.89%   |
| ASIX Electronics                | 3         | 0.89%   |
| Sierra Wireless                 | 2         | 0.59%   |
| Huawei Technologies             | 2         | 0.59%   |
| Broadcom Limited                | 2         | 0.59%   |
| ASUSTek Computer                | 2         | 0.59%   |
| Ralink Technology               | 1         | 0.3%    |
| Ralink                          | 1         | 0.3%    |
| Qualcomm Atheros Communications | 1         | 0.3%    |
| Qualcomm                        | 1         | 0.3%    |
| Micro Star International        | 1         | 0.3%    |
| Hewlett-Packard                 | 1         | 0.3%    |
| DisplayLink                     | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 68        | 14.88%  |
| Intel Wi-Fi 6 AX201                                                     | 50        | 10.94%  |
| Intel Ethernet Connection (13) I219-V                                   | 39        | 8.53%   |
| Intel Wireless 8265 / 8275                                              | 17        | 3.72%   |
| Intel Ethernet Connection (10) I219-V                                   | 14        | 3.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.97%   |
| Intel Wireless 7265                                                     | 9         | 1.97%   |
| Intel Ethernet Connection (7) I219-LM                                   | 9         | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.97%   |
| Intel Ethernet Connection (6) I219-V                                    | 8         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.09%   |
| Intel Wireless 3165                                                     | 5         | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.88%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 4         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.88%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                | 4         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.66%   |
| Intel WiFi Link 5100                                                    | 3         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.66%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 0.66%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 136       | 56.67%  |
| Realtek Semiconductor           | 41        | 17.08%  |
| Qualcomm Atheros                | 32        | 13.33%  |
| Broadcom                        | 17        | 7.08%   |
| MediaTek                        | 5         | 2.08%   |
| Sierra Wireless                 | 2         | 0.83%   |
| ASUSTek Computer                | 2         | 0.83%   |
| Ralink Technology               | 1         | 0.42%   |
| Ralink                          | 1         | 0.42%   |
| Qualcomm Atheros Communications | 1         | 0.42%   |
| Micro Star International        | 1         | 0.42%   |
| Broadcom Limited                | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 50        | 20.58%  |
| Intel Wireless 8265 / 8275                                              | 17        | 7%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 4.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 4.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.7%    |
| Intel Wireless 7265                                                     | 9         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 3.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.06%   |
| Intel Wireless 3165                                                     | 5         | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.23%   |
| Intel WiFi Link 5100                                                    | 3         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.23%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.82%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.82%   |
| Intel WiMAX Connection 2400m                                            | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 0.82%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                          | 1         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.41%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 83        | 39.34%  |
| Realtek Semiconductor    | 81        | 38.39%  |
| Qualcomm Atheros         | 11        | 5.21%   |
| Broadcom                 | 8         | 3.79%   |
| Marvell Technology Group | 6         | 2.84%   |
| D-Link                   | 6         | 2.84%   |
| Nvidia                   | 5         | 2.37%   |
| JMicron Technology       | 3         | 1.42%   |
| ASIX Electronics         | 3         | 1.42%   |
| Huawei Technologies      | 2         | 0.95%   |
| Qualcomm                 | 1         | 0.47%   |
| DisplayLink              | 1         | 0.47%   |
| Broadcom Limited         | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 31.92%  |
| Intel Ethernet Connection (13) I219-V                             | 39        | 18.31%  |
| Intel Ethernet Connection (10) I219-V                             | 14        | 6.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 4.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 4.23%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 3.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.35%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 1.88%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.88%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 1.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.94%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.94%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 2         | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.47%   |
| Qualcomm Redmi Note 9 Pro                                         | 1         | 0.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.47%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.47%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.47%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.47%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.47%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.47%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.47%   |
| Huawei E353/E3131                                                 | 1         | 0.47%   |
| Huawei ANE-LX1                                                    | 1         | 0.47%   |
| DisplayLink StarTech USB3DOCKHDPC                                 | 1         | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 233       | 52.95%  |
| Ethernet | 206       | 46.82%  |
| Modem    | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 77.33%  |
| Ethernet | 56        | 22.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 193       | 82.13%  |
| 1     | 37        | 15.74%  |
| 0     | 4         | 1.7%    |
| 3     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 225       | 95.74%  |
| Yes  | 10        | 4.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 61.31%  |
| Realtek Semiconductor           | 15        | 7.54%   |
| IMC Networks                    | 13        | 6.53%   |
| Broadcom                        | 11        | 5.53%   |
| Qualcomm Atheros Communications | 7         | 3.52%   |
| Lite-On Technology              | 6         | 3.02%   |
| Hewlett-Packard                 | 5         | 2.51%   |
| Foxconn / Hon Hai               | 5         | 2.51%   |
| Apple                           | 4         | 2.01%   |
| Realtek                         | 3         | 1.51%   |
| ASUSTek Computer                | 2         | 1.01%   |
| USI                             | 1         | 0.5%    |
| Toshiba                         | 1         | 0.5%    |
| Ralink                          | 1         | 0.5%    |
| Opticis                         | 1         | 0.5%    |
| Chicony Electronics             | 1         | 0.5%    |
| Cambridge Silicon Radio         | 1         | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                       | 53        | 26.63%  |
| Intel Bluetooth wireless interface                          | 36        | 18.09%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 23        | 11.56%  |
| Realtek Bluetooth Radio                                     | 10        | 5.03%   |
| Intel Wireless-AC 3168 Bluetooth                            | 8         | 4.02%   |
| IMC Networks Wireless_Device                                | 6         | 3.02%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 2.01%   |
| Broadcom BCM2045 Bluetooth                                  | 4         | 2.01%   |
| Realtek Bluetooth Radio                                     | 3         | 1.51%   |
| Qualcomm Atheros  Bluetooth Device                          | 3         | 1.51%   |
| IMC Networks Bluetooth Device                               | 3         | 1.51%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.51%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 3         | 1.51%   |
| Apple Bluetooth Host Controller                             | 3         | 1.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 1.01%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.01%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 2         | 1.01%   |
| USI Bluetooth Module BCM92070                               | 1         | 0.5%    |
| Toshiba Integrated Bluetooth HCI                            | 1         | 0.5%    |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.5%    |
| Ralink RT3290 Bluetooth                                     | 1         | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.5%    |
| Opticis Bluetooth Radio                                     | 1         | 0.5%    |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.5%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.5%    |
| Lite-On Bluetooth Radio                                     | 1         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.5%    |
| Intel AX200 Bluetooth                                       | 1         | 0.5%    |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.5%    |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 0.5%    |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.5%    |
| Chicony Bluetooth (RTL8723BE)                               | 1         | 0.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.5%    |
| Broadcom HP Portable Bumble Bee                             | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 197       | 64.8%   |
| C-Media Electronics                          | 34        | 11.18%  |
| AMD                                          | 34        | 11.18%  |
| Nvidia                                       | 26        | 8.55%   |
| Promethean Limited                           | 7         | 2.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.33%   |
| VIA Technologies                             | 1         | 0.33%   |
| Realtek Semiconductor                        | 1         | 0.33%   |
| Logitech                                     | 1         | 0.33%   |
| ASUSTek Computer                             | 1         | 0.33%   |
| Apple                                        | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 53        | 15.87%  |
| Intel Sunrise Point-LP HD Audio                                            | 32        | 9.58%   |
| C-Media Electronics USB Advanced Audio Device                              | 32        | 9.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 22        | 6.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 4.49%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 3.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 3.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 3.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 2.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.4%    |
| Promethean Limited Audio                                                   | 7         | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 2.1%    |
| AMD FCH Azalia Controller                                                  | 7         | 2.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.2%    |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.6%    |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.6%    |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.6%    |
| Nvidia Audio device                                                        | 2         | 0.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 0.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.6%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 2         | 0.6%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 0.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.3%    |
| Realtek Semiconductor USB Audio                                            | 1         | 0.3%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.3%    |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 55        | 24.89%  |
| SK hynix            | 42        | 19%     |
| ACPI Digital        | 32        | 14.48%  |
| Unknown             | 17        | 7.69%   |
| Micron Technology   | 15        | 6.79%   |
| Kingston            | 15        | 6.79%   |
| Crucial             | 14        | 6.33%   |
| Foxline             | 5         | 2.26%   |
| Elpida              | 5         | 2.26%   |
| A-DATA Technology   | 5         | 2.26%   |
| ChangXin Memory     | 3         | 1.36%   |
| Unknown (ABCD)      | 2         | 0.9%    |
| Ramaxel Technology  | 2         | 0.9%    |
| Unknown             | 2         | 0.9%    |
| Shenzhen Longsys    | 1         | 0.45%   |
| SHARETRONIC         | 1         | 0.45%   |
| Patriot             | 1         | 0.45%   |
| Lexar Co Limited    | 1         | 0.45%   |
| Kimtigo             | 1         | 0.45%   |
| Corsair             | 1         | 0.45%   |
| AMD                 | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s   | 32        | 14.29%  |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 13        | 5.8%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                    | 9         | 4.02%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                    | 7         | 3.13%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 5         | 2.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 5         | 2.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 4         | 1.79%   |
| Foxline RAM FL2666D4S19-8G 8192MB SODIMM DDR4 2667MT/s          | 4         | 1.79%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s          | 4         | 1.79%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 3         | 1.34%   |
| Unknown RAM Module 2048MB SODIMM DDR2                           | 3         | 1.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 1.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s       | 3         | 1.34%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 3         | 1.34%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s           | 3         | 1.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.34%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s          | 3         | 1.34%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s           | 3         | 1.34%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s | 3         | 1.34%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 2         | 0.89%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 2         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 0.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s          | 2         | 0.89%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                     | 2         | 0.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.89%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s           | 2         | 0.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.89%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s         | 2         | 0.89%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s         | 2         | 0.89%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s         | 2         | 0.89%   |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s             | 2         | 0.89%   |
| Unknown                                                         | 2         | 0.89%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM 1067MT/s                          | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                        | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 140       | 68.29%  |
| DDR3    | 34        | 16.59%  |
| DDR2    | 17        | 8.29%   |
| LPDDR4  | 8         | 3.9%    |
| Unknown | 2         | 0.98%   |
| SDRAM   | 1         | 0.49%   |
| LPDDR5  | 1         | 0.49%   |
| LPDDR3  | 1         | 0.49%   |
| DDR5    | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 186       | 90.73%  |
| Row Of Chips | 18        | 8.78%   |
| DIMM         | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 81        | 38.57%  |
| 4096  | 51        | 24.29%  |
| 16384 | 47        | 22.38%  |
| 2048  | 19        | 9.05%   |
| 1024  | 8         | 3.81%   |
| 512   | 2         | 0.95%   |
| 32768 | 1         | 0.48%   |
| 1536  | 1         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 66        | 30.84%  |
| 2667    | 55        | 25.7%   |
| 1600    | 21        | 9.81%   |
| 2133    | 15        | 7.01%   |
| 667     | 10        | 4.67%   |
| 1334    | 9         | 4.21%   |
| 2400    | 8         | 3.74%   |
| Unknown | 6         | 2.8%    |
| 3266    | 4         | 1.87%   |
| 1067    | 4         | 1.87%   |
| 3733    | 3         | 1.4%    |
| 1333    | 3         | 1.4%    |
| 4267    | 2         | 0.93%   |
| 6400    | 1         | 0.47%   |
| 4800    | 1         | 0.47%   |
| 4199    | 1         | 0.47%   |
| 2933    | 1         | 0.47%   |
| 1867    | 1         | 0.47%   |
| 800     | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| 333     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 4         | 30.77%  |
| Xerox                  | 2         | 15.38%  |
| Samsung Electronics    | 2         | 15.38%  |
| Ricoh                  | 2         | 15.38%  |
| Brother Industries     | 2         | 15.38%  |
| Panasonic (Matsushita) | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung SCX-3400 Series           | 2         | 15.38%  |
| Brother HL-L2300D series          | 2         | 15.38%  |
| Xerox WorkCentre 5222             | 1         | 7.69%   |
| Xerox WorkCentre 3220             | 1         | 7.69%   |
| Ricoh SP 210SU                    | 1         | 7.69%   |
| Ricoh Aficio SP C240DN            | 1         | 7.69%   |
| Panasonic (Matsushita) KX-MB283RU | 1         | 7.69%   |
| Canon PIXMA MP190                 | 1         | 7.69%   |
| Canon MF4410                      | 1         | 7.69%   |
| Canon MF4010 series               | 1         | 7.69%   |
| Canon I-SENSYS MF4550d            | 1         | 7.69%   |

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
| Chicony Electronics                    | 47        | 21.17%  |
| Acer                                   | 40        | 18.02%  |
| Cheng Uei Precision Industry (Foxlink) | 30        | 13.51%  |
| IMC Networks                           | 26        | 11.71%  |
| Sunplus Innovation Technology          | 13        | 5.86%   |
| Quanta                                 | 10        | 4.5%    |
| Suyin                                  | 9         | 4.05%   |
| Realtek Semiconductor                  | 9         | 4.05%   |
| Syntek                                 | 6         | 2.7%    |
| Microdia                               | 5         | 2.25%   |
| Bison Electronics                      | 4         | 1.8%    |
| Apple                                  | 4         | 1.8%    |
| Z-Star Microelectronics                | 3         | 1.35%   |
| Sonix Technology                       | 2         | 0.9%    |
| Silicon Motion                         | 2         | 0.9%    |
| Lite-On Technology                     | 2         | 0.9%    |
| Y Media                                | 1         | 0.45%   |
| Unknown                                | 1         | 0.45%   |
| SunplusIT                              | 1         | 0.45%   |
| Ricoh                                  | 1         | 0.45%   |
| Primax Electronics                     | 1         | 0.45%   |
| Luxvisions Innotech Limited            | 1         | 0.45%   |
| Importek                               | 1         | 0.45%   |
| icSpring                               | 1         | 0.45%   |
| ALi                                    | 1         | 0.45%   |
| Alcor Micro                            | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer BisonCam,NB Pro                                           | 34        | 15.32%  |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 6.76%   |
| Chicony HP HD Camera                                           | 11        | 4.95%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 11        | 4.95%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 4.5%    |
| Chicony USB2.0 Camera                                          | 7         | 3.15%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 2.7%    |
| Realtek USB Camera                                             | 6         | 2.7%    |
| IMC Networks HD Camera                                         | 5         | 2.25%   |
| Chicony USB camera                                             | 5         | 2.25%   |
| Sunplus BKX Usb FHD Camera                                     | 4         | 1.8%    |
| IMC Networks Integrated Camera                                 | 4         | 1.8%    |
| Syntek Integrated Camera                                       | 3         | 1.35%   |
| Quanta ov9734_techfront_camera                                 | 3         | 1.35%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.35%   |
| Chicony Integrated Camera                                      | 3         | 1.35%   |
| Chicony HD WebCam                                              | 3         | 1.35%   |
| Apple Built-in iSight                                          | 3         | 1.35%   |
| Z-Star Vega USB 2.0 Camera                                     | 2         | 0.9%    |
| Syntek Lenovo EasyCamera                                       | 2         | 0.9%    |
| Suyin 1.3M HD WebCam                                           | 2         | 0.9%    |
| Sunplus Asus Webcam                                            | 2         | 0.9%    |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 0.9%    |
| Microdia Integrated_Webcam_HD                                  | 2         | 0.9%    |
| Chicony VGA Webcam                                             | 2         | 0.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 2         | 0.9%    |
| Chicony Lenovo EasyCamera                                      | 2         | 0.9%    |
| Chicony Integrated HP HD Webcam                                | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.9%    |
| Bison USB HD Webcam                                            | 2         | 0.9%    |
| Acer BisonCam, NB Pro                                          | 2         | 0.9%    |
| Z-Star Namuga 1.3M Webcam                                      | 1         | 0.45%   |
| Y Media USB Camera                                             | 1         | 0.45%   |
| Unknown USB2.0 Webcam                                          | 1         | 0.45%   |
| Syntek USB2.0 UVC PC Camera                                    | 1         | 0.45%   |
| Suyin Intel Webcam                                             | 1         | 0.45%   |
| Suyin HP Webcam                                                | 1         | 0.45%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.45%   |
| Suyin HP Truevision HD                                         | 1         | 0.45%   |
| Suyin Acer HD Crystal Eye webcam                               | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 9         | 27.27%  |
| Validity Sensors           | 7         | 21.21%  |
| Elan Microelectronics      | 7         | 21.21%  |
| LighTuning Technology      | 4         | 12.12%  |
| Synaptics                  | 3         | 9.09%   |
| Upek                       | 2         | 6.06%   |
| Focal-systems.Corp         | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 9         | 27.27%  |
| Elan ELAN:Fingerprint                                    | 5         | 15.15%  |
| LighTuning Fingerprint Reader                            | 3         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 6.06%   |
| Validity Sensors VFS491                                  | 2         | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 6.06%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 6.06%   |
| Elan ELAN:ARM-M4                                         | 2         | 6.06%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 3.03%   |
| Validity Sensors VFS471 Fingerprint Reader               | 1         | 3.03%   |
| Validity Sensors Fingerprint scanner                     | 1         | 3.03%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 3.03%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 75%     |
| Broadcom    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 75%     |
| Broadcom 5880                       | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 183       | 76.89%  |
| 1     | 40        | 16.81%  |
| 2     | 11        | 4.62%   |
| 3     | 3         | 1.26%   |
| 4     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 48.53%  |
| Graphics card            | 10        | 14.71%  |
| Communication controller | 8         | 11.76%  |
| Multimedia controller    | 4         | 5.88%   |
| Chipcard                 | 4         | 5.88%   |
| Net/ethernet             | 3         | 4.41%   |
| Camera                   | 2         | 2.94%   |
| Sound                    | 1         | 1.47%   |
| Net/wireless             | 1         | 1.47%   |
| Flash memory             | 1         | 1.47%   |
| Bluetooth                | 1         | 1.47%   |

