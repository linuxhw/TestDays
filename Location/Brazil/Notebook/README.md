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

Total: 10466

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Philco        | 10D                         | [dd709d35db](https://linux-hardware.org/?probe=dd709d35db) | Feb 28, 2023 |
| Samsung       | 370E4K                      | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Dell          | G15 5510                    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| Dell          | G15 5510                    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| Samsung       | 370E4K                      | [d66bcd2bc8](https://linux-hardware.org/?probe=d66bcd2bc8) | Feb 27, 2023 |
| Dell          | Inspiron 1525               | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | [04c721038a](https://linux-hardware.org/?probe=04c721038a) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| HP            | 430                         | [f90c967f06](https://linux-hardware.org/?probe=f90c967f06) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86fac430ca](https://linux-hardware.org/?probe=86fac430ca) | Feb 26, 2023 |
| Samsung       | 370E4K                      | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| Dell          | Inspiron 3584               | [47eff629e0](https://linux-hardware.org/?probe=47eff629e0) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Intel         | HuronRiver Platform         | [2168c2bb5c](https://linux-hardware.org/?probe=2168c2bb5c) | Feb 26, 2023 |
| Dell          | G15 5520                    | [d68c28ea8d](https://linux-hardware.org/?probe=d68c28ea8d) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [75e601b927](https://linux-hardware.org/?probe=75e601b927) | Feb 26, 2023 |
| Dell          | Inspiron 3576               | [5911354b82](https://linux-hardware.org/?probe=5911354b82) | Feb 26, 2023 |
| Dell          | G7 7588                     | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Acer          | Acadia V1.45                | [faee032e6c](https://linux-hardware.org/?probe=faee032e6c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [af95b24466](https://linux-hardware.org/?probe=af95b24466) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| Samsung       | 550XBE/350XBE               | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c3d39f884](https://linux-hardware.org/?probe=5c3d39f884) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | Z450LA                      | [304be04748](https://linux-hardware.org/?probe=304be04748) | Feb 25, 2023 |
| Samsung       | RV415/RV515                 | [23c0509d46](https://linux-hardware.org/?probe=23c0509d46) | Feb 25, 2023 |
| Sony          | VPCCW13FB                   | [1772a3987b](https://linux-hardware.org/?probe=1772a3987b) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [d3354bd88c](https://linux-hardware.org/?probe=d3354bd88c) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6dd01c6a20](https://linux-hardware.org/?probe=6dd01c6a20) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1b5b668cea](https://linux-hardware.org/?probe=1b5b668cea) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c0af9c8bdb](https://linux-hardware.org/?probe=c0af9c8bdb) | Feb 24, 2023 |
| Positivo      | N1103                       | [b89c4551aa](https://linux-hardware.org/?probe=b89c4551aa) | Feb 24, 2023 |
| Positivo      | Q464C-O                     | [cda1faecb1](https://linux-hardware.org/?probe=cda1faecb1) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Avell High... | A70 MOB                     | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| Dell          | Inspiron N5010              | [5b4def0870](https://linux-hardware.org/?probe=5b4def0870) | Feb 23, 2023 |
| Dell          | Latitude 3420               | [86fd73d1e3](https://linux-hardware.org/?probe=86fd73d1e3) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| System76      | Gazelle                     | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| Acer          | Nitro AN515-52              | [05f7c375b7](https://linux-hardware.org/?probe=05f7c375b7) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe9944c457](https://linux-hardware.org/?probe=fe9944c457) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| Positivo      | Q464C                       | [1b08f16a08](https://linux-hardware.org/?probe=1b08f16a08) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | [5b173518b5](https://linux-hardware.org/?probe=5b173518b5) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | [107bd5b235](https://linux-hardware.org/?probe=107bd5b235) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c99d1595ec](https://linux-hardware.org/?probe=c99d1595ec) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Positivo      | S14SL01                     | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Dell          | Inspiron 3583               | [ad766a4190](https://linux-hardware.org/?probe=ad766a4190) | Feb 22, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Positivo      | S14CT01                     | [af73fc0481](https://linux-hardware.org/?probe=af73fc0481) | Feb 22, 2023 |
| Samsung       | 767XCL                      | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| Dell          | Inspiron 5547               | [ff88bcbafc](https://linux-hardware.org/?probe=ff88bcbafc) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [818012d7ef](https://linux-hardware.org/?probe=818012d7ef) | Feb 21, 2023 |
| Unknown       | Unknown                     | [08eab2bac4](https://linux-hardware.org/?probe=08eab2bac4) | Feb 21, 2023 |
| Avell High... | 1513                        | [0b46cb6de1](https://linux-hardware.org/?probe=0b46cb6de1) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [caccb434d2](https://linux-hardware.org/?probe=caccb434d2) | Feb 21, 2023 |
| Compaq        | 430                         | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| HP            | 1000                        | [91faf9460d](https://linux-hardware.org/?probe=91faf9460d) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | G40-80 80JE                 | [e7e12370af](https://linux-hardware.org/?probe=e7e12370af) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Unknown       | Unknown                     | [cccf0ea7f3](https://linux-hardware.org/?probe=cccf0ea7f3) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Acer          | Predator PH315-52           | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| HP            | Compaq Presario CQ42        | [001f2f1a86](https://linux-hardware.org/?probe=001f2f1a86) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | [ca537a9b24](https://linux-hardware.org/?probe=ca537a9b24) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | [d5dbc5770a](https://linux-hardware.org/?probe=d5dbc5770a) | Feb 19, 2023 |
| Notebook      | NJx0MU                      | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Multilaser    | PC130                       | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Acer          | Aspire A515-41G             | [e06b3509f1](https://linux-hardware.org/?probe=e06b3509f1) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Avell High... | B.ON                        | [d7f2dafd5e](https://linux-hardware.org/?probe=d7f2dafd5e) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [beff031939](https://linux-hardware.org/?probe=beff031939) | Feb 18, 2023 |
| Acer          | Aspire A515-51              | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| Samsung       | 270E5G/270E5U               | [daf6a78f6f](https://linux-hardware.org/?probe=daf6a78f6f) | Feb 17, 2023 |
| Samsung       | 550XDA                      | [d7f1482689](https://linux-hardware.org/?probe=d7f1482689) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| Dell          | Inspiron 3583               | [9200702bb7](https://linux-hardware.org/?probe=9200702bb7) | Feb 16, 2023 |
| Dell          | Inspiron 13-5378            | [cf5749e5be](https://linux-hardware.org/?probe=cf5749e5be) | Feb 16, 2023 |
| Positivo      | S14BW01                     | [c14428167e](https://linux-hardware.org/?probe=c14428167e) | Feb 16, 2023 |
| Positivo      | CHT14B                      | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | [7d55f655bb](https://linux-hardware.org/?probe=7d55f655bb) | Feb 15, 2023 |
| Acer          | Nitro AN515-54              | [4e0f0e0310](https://linux-hardware.org/?probe=4e0f0e0310) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [e42ed53dcf](https://linux-hardware.org/?probe=e42ed53dcf) | Feb 15, 2023 |
| Lenovo        | G470 20078                  | [8385999199](https://linux-hardware.org/?probe=8385999199) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| HP            | EliteBook 8460p             | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Acer          | Predator G3-572             | [410a9aae8c](https://linux-hardware.org/?probe=410a9aae8c) | Feb 14, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03f90da8d3](https://linux-hardware.org/?probe=03f90da8d3) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Dell          | Inspiron 5402               | [805931ad5f](https://linux-hardware.org/?probe=805931ad5f) | Feb 14, 2023 |
| Positivo      | CHT14B                      | [859e8a3c17](https://linux-hardware.org/?probe=859e8a3c17) | Feb 13, 2023 |
| Positivo      | CHT14B                      | [2d5b910ed3](https://linux-hardware.org/?probe=2d5b910ed3) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Samsung       | 550XDA                      | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| Toshiba       | IS 1413G                    | [75f2859a68](https://linux-hardware.org/?probe=75f2859a68) | Feb 12, 2023 |
| Toshiba       | IS 1413G                    | [ec0e0c6dc2](https://linux-hardware.org/?probe=ec0e0c6dc2) | Feb 12, 2023 |
| Samsung       | 767XCL                      | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Toshiba       | IS 1413G                    | [e32070b494](https://linux-hardware.org/?probe=e32070b494) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| Unknown       | Unknown                     | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Dell          | Inspiron 5590               | [594e3be773](https://linux-hardware.org/?probe=594e3be773) | Feb 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [2dca851444](https://linux-hardware.org/?probe=2dca851444) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| Acer          | Aspire 5720                 | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| Acer          | Aspire A515-45              | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| Intel         | HuronRiver Platform         | [e3ad5a0e88](https://linux-hardware.org/?probe=e3ad5a0e88) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| Dell          | Inspiron 5402               | [52125d1623](https://linux-hardware.org/?probe=52125d1623) | Feb 10, 2023 |
| Samsung       | 550XDA                      | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| HP            | ProBook 440 G5              | [0f111bd12b](https://linux-hardware.org/?probe=0f111bd12b) | Feb 09, 2023 |
| Dell          | Inspiron 7460               | [2c17efbcd7](https://linux-hardware.org/?probe=2c17efbcd7) | Feb 09, 2023 |
| Positivo      | Smash2                      | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Toshiba       | IS 1413G                    | [c5c9fb9b41](https://linux-hardware.org/?probe=c5c9fb9b41) | Feb 09, 2023 |
| Acer          | Aspire A315-53G             | [e2a551b06b](https://linux-hardware.org/?probe=e2a551b06b) | Feb 09, 2023 |
| Acer          | Predator PH315-55           | [452c65c04b](https://linux-hardware.org/?probe=452c65c04b) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | [5e1eb34232](https://linux-hardware.org/?probe=5e1eb34232) | Feb 09, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [43968e7a27](https://linux-hardware.org/?probe=43968e7a27) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [74f2ac0aeb](https://linux-hardware.org/?probe=74f2ac0aeb) | Feb 08, 2023 |
| Dell          | G15 5515                    | [3b0208199f](https://linux-hardware.org/?probe=3b0208199f) | Feb 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [acbbbca6e7](https://linux-hardware.org/?probe=acbbbca6e7) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Apple         | MacBookAir7,2               | [0a94d67455](https://linux-hardware.org/?probe=0a94d67455) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a2378e95f6](https://linux-hardware.org/?probe=a2378e95f6) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| Acer          | TravelMate P256-M           | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| Dell          | Inspiron 7580               | [986d240b5d](https://linux-hardware.org/?probe=986d240b5d) | Feb 06, 2023 |
| Quanta        | TWS                         | [275ccf1b58](https://linux-hardware.org/?probe=275ccf1b58) | Feb 05, 2023 |
| Dell          | G15 5510                    | [41bbdf84c2](https://linux-hardware.org/?probe=41bbdf84c2) | Feb 05, 2023 |
| Acer          | Aspire E1-572               | [02d439f664](https://linux-hardware.org/?probe=02d439f664) | Feb 05, 2023 |
| Lenovo        | G400s VILG1                 | [426348e103](https://linux-hardware.org/?probe=426348e103) | Feb 05, 2023 |
| Dell          | G15 5515                    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| Evolute       | SFX-65                      | [7b37b32f92](https://linux-hardware.org/?probe=7b37b32f92) | Feb 04, 2023 |
| Dell          | Inspiron 15-3567            | [7659183894](https://linux-hardware.org/?probe=7659183894) | Feb 04, 2023 |
| HP            | Compaq Presario CQ40        | [de29ca3277](https://linux-hardware.org/?probe=de29ca3277) | Feb 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Notebook      | NJx0MU                      | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| ASUSTek       | K45VM                       | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Dell          | Precision M4600             | [a0d6749416](https://linux-hardware.org/?probe=a0d6749416) | Feb 04, 2023 |
| Acer          | Aspire E1-572               | [6f3ba6b805](https://linux-hardware.org/?probe=6f3ba6b805) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| Acer          | Aspire E1-572               | [f99e3aa76d](https://linux-hardware.org/?probe=f99e3aa76d) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [b82450078c](https://linux-hardware.org/?probe=b82450078c) | Feb 03, 2023 |
| Dell          | Vostro 3550                 | [17a4a2e5fd](https://linux-hardware.org/?probe=17a4a2e5fd) | Feb 02, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [92d639c0f4](https://linux-hardware.org/?probe=92d639c0f4) | Feb 02, 2023 |
| Dell          | Latitude 7480               | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Positivo      | Mobile                      | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [721bc8fb78](https://linux-hardware.org/?probe=721bc8fb78) | Feb 02, 2023 |
| Insyde        | Braswell                    | [928b461a5b](https://linux-hardware.org/?probe=928b461a5b) | Feb 02, 2023 |
| Lenovo        | G40-80 80JE                 | [9a5e6fd61e](https://linux-hardware.org/?probe=9a5e6fd61e) | Feb 02, 2023 |
| Philco        | 14I                         | [8f9833285e](https://linux-hardware.org/?probe=8f9833285e) | Feb 01, 2023 |
| Acer          | Aspire E1-572               | [c4e6e989f5](https://linux-hardware.org/?probe=c4e6e989f5) | Feb 01, 2023 |
| Dell          | Inspiron 5566               | [b2dd8d93c7](https://linux-hardware.org/?probe=b2dd8d93c7) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | [fa4104f438](https://linux-hardware.org/?probe=fa4104f438) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | [ec80fcb8a5](https://linux-hardware.org/?probe=ec80fcb8a5) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Acer          | Nitro AN515-54              | [9aee0a798c](https://linux-hardware.org/?probe=9aee0a798c) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Dell          | Inspiron 15-3567            | [2f6f4bc8c7](https://linux-hardware.org/?probe=2f6f4bc8c7) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Samsung       | RV415/RV515                 | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | [bb5d758714](https://linux-hardware.org/?probe=bb5d758714) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | [e5dc585024](https://linux-hardware.org/?probe=e5dc585024) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire A515-41G             | [88db10e257](https://linux-hardware.org/?probe=88db10e257) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Avell High... | B.ON                        | [721fbbdeb2](https://linux-hardware.org/?probe=721fbbdeb2) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [1c62beb905](https://linux-hardware.org/?probe=1c62beb905) | Jan 29, 2023 |
| Samsung       | RV415/RV515                 | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [51245400df](https://linux-hardware.org/?probe=51245400df) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| Positivo      | Q464C-O                     | [e61f2d0622](https://linux-hardware.org/?probe=e61f2d0622) | Jan 29, 2023 |
| Acer          | Aspire 5733                 | [da753d74a1](https://linux-hardware.org/?probe=da753d74a1) | Jan 29, 2023 |
| Dell          | G15 5520                    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f1f5def619](https://linux-hardware.org/?probe=f1f5def619) | Jan 28, 2023 |
| Samsung       | RV415/RV515                 | [fd9d67e4b8](https://linux-hardware.org/?probe=fd9d67e4b8) | Jan 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [c74ea31148](https://linux-hardware.org/?probe=c74ea31148) | Jan 27, 2023 |
| HP            | Compaq 6530b                | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [5a32be51f4](https://linux-hardware.org/?probe=5a32be51f4) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Philco        | 14E                         | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [93be3d62c4](https://linux-hardware.org/?probe=93be3d62c4) | Jan 27, 2023 |
| Compaq        | 430                         | [069fa715b9](https://linux-hardware.org/?probe=069fa715b9) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [b4d0bbaf56](https://linux-hardware.org/?probe=b4d0bbaf56) | Jan 27, 2023 |
| Dell          | Inspiron 5468               | [d155136857](https://linux-hardware.org/?probe=d155136857) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [05dac90dec](https://linux-hardware.org/?probe=05dac90dec) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [0697311f5f](https://linux-hardware.org/?probe=0697311f5f) | Jan 27, 2023 |
| Dell          | G3 3500                     | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| Dell          | Vostro 3458                 | [3beffe6710](https://linux-hardware.org/?probe=3beffe6710) | Jan 26, 2023 |
| ASUSTek       | Z550SA                      | [f5ac147c1e](https://linux-hardware.org/?probe=f5ac147c1e) | Jan 26, 2023 |
| Multilaser    | PC150                       | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| Dell          | Latitude 5490               | [b392e71ce5](https://linux-hardware.org/?probe=b392e71ce5) | Jan 26, 2023 |
| Dell          | G3 3590                     | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| HP            | G60                         | [8fe616c588](https://linux-hardware.org/?probe=8fe616c588) | Jan 25, 2023 |
| HP            | Folio 13                    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| Digibras      | NH4CU03                     | [7de7df58a3](https://linux-hardware.org/?probe=7de7df58a3) | Jan 24, 2023 |
| Digibras      | NH4CU03                     | [fce5f618d8](https://linux-hardware.org/?probe=fce5f618d8) | Jan 24, 2023 |
| Dell          | Inspiron 3421               | [02491de92f](https://linux-hardware.org/?probe=02491de92f) | Jan 24, 2023 |
| Compaq        | 420                         | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| Acer          | Aspire A515-51              | [418e5a2787](https://linux-hardware.org/?probe=418e5a2787) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Insyde        | Braswell                    | [6abab0adc1](https://linux-hardware.org/?probe=6abab0adc1) | Jan 24, 2023 |
| Positivo      | N1240                       | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| ASUSTek       | K46CB                       | [62aa75f57a](https://linux-hardware.org/?probe=62aa75f57a) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [4a97e29245](https://linux-hardware.org/?probe=4a97e29245) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [54ebd7c5f8](https://linux-hardware.org/?probe=54ebd7c5f8) | Jan 23, 2023 |
| Dell          | Latitude 3420               | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| Notebook      | NJx0MU                      | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Alienware     | m15 R7                      | [e57302bf60](https://linux-hardware.org/?probe=e57302bf60) | Jan 23, 2023 |
| HP            | 540                         | [a4a7b26f42](https://linux-hardware.org/?probe=a4a7b26f42) | Jan 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7d4406c9bc](https://linux-hardware.org/?probe=7d4406c9bc) | Jan 22, 2023 |
| HP            | Pavilion dv4                | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Dell          | Vostro 3460                 | [569626e023](https://linux-hardware.org/?probe=569626e023) | Jan 22, 2023 |
| Dell          | G3 3500                     | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [697fbcd8d1](https://linux-hardware.org/?probe=697fbcd8d1) | Jan 22, 2023 |
| Dell          | G3 3500                     | [e81b4d5e46](https://linux-hardware.org/?probe=e81b4d5e46) | Jan 22, 2023 |
| Dell          | Inspiron N4050              | [6ddc2793d7](https://linux-hardware.org/?probe=6ddc2793d7) | Jan 21, 2023 |
| Dell          | Inspiron N4050              | [ae4c9eaa9c](https://linux-hardware.org/?probe=ae4c9eaa9c) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ed9d60d9b7](https://linux-hardware.org/?probe=ed9d60d9b7) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| Philco        | OEM                         | [a39f50ccfd](https://linux-hardware.org/?probe=a39f50ccfd) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [fa251ca13c](https://linux-hardware.org/?probe=fa251ca13c) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [965d1fa09f](https://linux-hardware.org/?probe=965d1fa09f) | Jan 20, 2023 |
| Acer          | Aspire E5-571               | [a37e873516](https://linux-hardware.org/?probe=a37e873516) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [138a9b3b0c](https://linux-hardware.org/?probe=138a9b3b0c) | Jan 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6364be5249](https://linux-hardware.org/?probe=6364be5249) | Jan 20, 2023 |
| Dell          | Inspiron N4050              | [46e35da681](https://linux-hardware.org/?probe=46e35da681) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| Dell          | Vostro 3400                 | [c158cd6095](https://linux-hardware.org/?probe=c158cd6095) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Notebook      | NJx0MU                      | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| Dell          | Inspiron 15-3567            | [33a3aac223](https://linux-hardware.org/?probe=33a3aac223) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [cc9e6f8862](https://linux-hardware.org/?probe=cc9e6f8862) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| Sony          | VPCCA15FX                   | [41138327da](https://linux-hardware.org/?probe=41138327da) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [183de4d0f6](https://linux-hardware.org/?probe=183de4d0f6) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62aa341472](https://linux-hardware.org/?probe=62aa341472) | Jan 19, 2023 |
| Sony          | VPCF236FM                   | [c2ed0fe829](https://linux-hardware.org/?probe=c2ed0fe829) | Jan 19, 2023 |
| Compal        | Unknown                     | [81abfdb7d5](https://linux-hardware.org/?probe=81abfdb7d5) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Compal        | Unknown                     | [14cc4178d9](https://linux-hardware.org/?probe=14cc4178d9) | Jan 18, 2023 |
| Acer          | Aspire A315-53              | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3f0d644eaf](https://linux-hardware.org/?probe=3f0d644eaf) | Jan 18, 2023 |
| Acer          | Aspire A515-51              | [1aac8c57f8](https://linux-hardware.org/?probe=1aac8c57f8) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [22d07dfddf](https://linux-hardware.org/?probe=22d07dfddf) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [032ac1d52e](https://linux-hardware.org/?probe=032ac1d52e) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| HP            | Pavilion Notebook           | [c2dd87db86](https://linux-hardware.org/?probe=c2dd87db86) | Jan 17, 2023 |
| Digibras      | NH4CU03                     | [cd9cdce064](https://linux-hardware.org/?probe=cd9cdce064) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| Positivo      | N1103                       | [e5b41b9ed2](https://linux-hardware.org/?probe=e5b41b9ed2) | Jan 17, 2023 |
| Acer          | Aspire E1-572P              | [72afaf995e](https://linux-hardware.org/?probe=72afaf995e) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | [69e87b6d65](https://linux-hardware.org/?probe=69e87b6d65) | Jan 17, 2023 |
| Dell          | Inspiron N4050              | [2de561e7f5](https://linux-hardware.org/?probe=2de561e7f5) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Unknown       | X133                        | [8d28e5a95e](https://linux-hardware.org/?probe=8d28e5a95e) | Jan 16, 2023 |
| Positivo      | CHT14B                      | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [a4ec4fedeb](https://linux-hardware.org/?probe=a4ec4fedeb) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [e7b345f3e0](https://linux-hardware.org/?probe=e7b345f3e0) | Jan 15, 2023 |
| Multilaser    | UB23X LINUX                 | [34a7d43639](https://linux-hardware.org/?probe=34a7d43639) | Jan 15, 2023 |
| Multilaser    | UB23X LINUX                 | [029812488b](https://linux-hardware.org/?probe=029812488b) | Jan 15, 2023 |
| ASUSTek       | X45C                        | [677c0ac809](https://linux-hardware.org/?probe=677c0ac809) | Jan 15, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [1dab471d62](https://linux-hardware.org/?probe=1dab471d62) | Jan 15, 2023 |
| Acer          | Aspire A315-34              | [656b21ed21](https://linux-hardware.org/?probe=656b21ed21) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| Dell          | Inspiron 7580               | [99f51ba1ef](https://linux-hardware.org/?probe=99f51ba1ef) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| Sony          | VPCEH10EB                   | [c9127c6375](https://linux-hardware.org/?probe=c9127c6375) | Jan 14, 2023 |
| Samsung       | 530XBB                      | [99a0fe43da](https://linux-hardware.org/?probe=99a0fe43da) | Jan 13, 2023 |
| Dell          | Latitude 3490               | [facb8b4852](https://linux-hardware.org/?probe=facb8b4852) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| Acer          | Aspire M5-481T              | [e2030307c8](https://linux-hardware.org/?probe=e2030307c8) | Jan 13, 2023 |
| Toshiba       | STI NA 1401                 | [8ac3087e41](https://linux-hardware.org/?probe=8ac3087e41) | Jan 13, 2023 |
| Apple         | MacBookAir4,1               | [7b8d494edb](https://linux-hardware.org/?probe=7b8d494edb) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| Acer          | Aspire E1-421               | [ebfd029f41](https://linux-hardware.org/?probe=ebfd029f41) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| ASUSTek       | X45C                        | [0cf650bc7b](https://linux-hardware.org/?probe=0cf650bc7b) | Jan 13, 2023 |
| Positivo      | Smash2                      | [d160522fb3](https://linux-hardware.org/?probe=d160522fb3) | Jan 13, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [e4912e6bfc](https://linux-hardware.org/?probe=e4912e6bfc) | Jan 12, 2023 |
| Dell          | G15 5520                    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| Acer          | Nitro AN515-44              | [66d71f6da1](https://linux-hardware.org/?probe=66d71f6da1) | Jan 12, 2023 |
| HP            | Compaq 6530b                | [8ebd66e8e6](https://linux-hardware.org/?probe=8ebd66e8e6) | Jan 12, 2023 |
| Lenovo        | ThinkPad X230 2325AH7       | [c1080083c4](https://linux-hardware.org/?probe=c1080083c4) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b106ffdf11](https://linux-hardware.org/?probe=b106ffdf11) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Dell          | Inspiron 3583               | [6081f3b43a](https://linux-hardware.org/?probe=6081f3b43a) | Jan 11, 2023 |
| Dell          | Inspiron 3583               | [e2c3a94f39](https://linux-hardware.org/?probe=e2c3a94f39) | Jan 11, 2023 |
| Dell          | Vostro 3550                 | [28e0a94885](https://linux-hardware.org/?probe=28e0a94885) | Jan 11, 2023 |
| Acer          | Aspire E1-572               | [43c14a1e54](https://linux-hardware.org/?probe=43c14a1e54) | Jan 11, 2023 |
| HP            | Presario C700               | [3674a9a180](https://linux-hardware.org/?probe=3674a9a180) | Jan 11, 2023 |
| Samsung       | 270E5G/270E5U               | [0ddeecd2b8](https://linux-hardware.org/?probe=0ddeecd2b8) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c79ad1fc10](https://linux-hardware.org/?probe=c79ad1fc10) | Jan 11, 2023 |
| LG Electro... | P420-G.BC44P1               | [7dd7c0d6e8](https://linux-hardware.org/?probe=7dd7c0d6e8) | Jan 11, 2023 |
| Sony          | VPCEA23FB                   | [d6a7454695](https://linux-hardware.org/?probe=d6a7454695) | Jan 11, 2023 |
| Acer          | Aspire E1-571               | [77e844abaf](https://linux-hardware.org/?probe=77e844abaf) | Jan 11, 2023 |
| Compaq        | 420                         | [65070f85d5](https://linux-hardware.org/?probe=65070f85d5) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a33cdf7213](https://linux-hardware.org/?probe=a33cdf7213) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [83f2f14d5c](https://linux-hardware.org/?probe=83f2f14d5c) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [dc3e0fffe7](https://linux-hardware.org/?probe=dc3e0fffe7) | Jan 10, 2023 |
| Acer          | Aspire A515-41G             | [e5ef8ca744](https://linux-hardware.org/?probe=e5ef8ca744) | Jan 10, 2023 |
| HP            | Mini 110-1000               | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [53d6bec0e8](https://linux-hardware.org/?probe=53d6bec0e8) | Jan 10, 2023 |
| Dell          | Inspiron N5010              | [f5d1f04d89](https://linux-hardware.org/?probe=f5d1f04d89) | Jan 10, 2023 |
| Positivo B... | VJFE52F11X-B0611H           | [91caa09e7b](https://linux-hardware.org/?probe=91caa09e7b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| Acer          | Aspire A315-56              | [b89e68d5ab](https://linux-hardware.org/?probe=b89e68d5ab) | Jan 10, 2023 |
| Avell High... | B.ON                        | [23b5b8565e](https://linux-hardware.org/?probe=23b5b8565e) | Jan 10, 2023 |
| Clevo         | W240HU/W250HUQ              | [b572e2679d](https://linux-hardware.org/?probe=b572e2679d) | Jan 10, 2023 |
| Acer          | Aspire A514-54              | [a786a0640f](https://linux-hardware.org/?probe=a786a0640f) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| Dell          | Inspiron 3442               | [f540a5f964](https://linux-hardware.org/?probe=f540a5f964) | Jan 09, 2023 |
| Dell          | Inspiron N4050              | [fbb23cdb65](https://linux-hardware.org/?probe=fbb23cdb65) | Jan 09, 2023 |
| Samsung       | 550XBE/350XBE               | [0f91e4728c](https://linux-hardware.org/?probe=0f91e4728c) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ee26fd6a5c](https://linux-hardware.org/?probe=ee26fd6a5c) | Jan 09, 2023 |
| Itautec       | Infoway w7535               | [36f64a3242](https://linux-hardware.org/?probe=36f64a3242) | Jan 09, 2023 |
| Acer          | Aspire 5750                 | [54ad46d626](https://linux-hardware.org/?probe=54ad46d626) | Jan 09, 2023 |
| Notebook      | NJx0MU                      | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| HP            | ProBook 6465b               | [336f10e70b](https://linux-hardware.org/?probe=336f10e70b) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Apple         | MacBook6,1                  | [1f38721115](https://linux-hardware.org/?probe=1f38721115) | Jan 08, 2023 |
| Itautec       | Infoway w7535               | [6b8430c407](https://linux-hardware.org/?probe=6b8430c407) | Jan 08, 2023 |
| Dell          | Inspiron 5567               | [a43647cad6](https://linux-hardware.org/?probe=a43647cad6) | Jan 08, 2023 |
| Gateway       | NE570                       | [3f65734a89](https://linux-hardware.org/?probe=3f65734a89) | Jan 07, 2023 |
| Standard      | MB40II                      | [4abb5712cc](https://linux-hardware.org/?probe=4abb5712cc) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f33ea77f0b](https://linux-hardware.org/?probe=f33ea77f0b) | Jan 07, 2023 |
| Dell          | Inspiron 15-3567            | [e9dadf5a23](https://linux-hardware.org/?probe=e9dadf5a23) | Jan 07, 2023 |
| ASUSTek       | X45C                        | [6366228fb2](https://linux-hardware.org/?probe=6366228fb2) | Jan 07, 2023 |
| Dell          | Inspiron 15-3567            | [173b427c35](https://linux-hardware.org/?probe=173b427c35) | Jan 07, 2023 |
| Notebook      | P17SM                       | [1822a60f02](https://linux-hardware.org/?probe=1822a60f02) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [313f5897bd](https://linux-hardware.org/?probe=313f5897bd) | Jan 07, 2023 |
| Dell          | G15 5510                    | [210d9c1c73](https://linux-hardware.org/?probe=210d9c1c73) | Jan 07, 2023 |
| Dell          | G15 5510                    | [7009360ecf](https://linux-hardware.org/?probe=7009360ecf) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7f2254139c](https://linux-hardware.org/?probe=7f2254139c) | Jan 07, 2023 |
| LG Electro... | U460-G.BG31P1               | [dea7419ce8](https://linux-hardware.org/?probe=dea7419ce8) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [79c60c460a](https://linux-hardware.org/?probe=79c60c460a) | Jan 07, 2023 |
| LG Electro... | A530-U.BE54P1               | [39c702d864](https://linux-hardware.org/?probe=39c702d864) | Jan 06, 2023 |
| Acer          | Aspire E5-574               | [511e5df827](https://linux-hardware.org/?probe=511e5df827) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [1e24b872bd](https://linux-hardware.org/?probe=1e24b872bd) | Jan 06, 2023 |
| Dell          | G15 5515                    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| Notebook      | NJx0MU                      | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [758acf54ff](https://linux-hardware.org/?probe=758acf54ff) | Jan 06, 2023 |
| Multilaser    | PC024                       | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [caa3df2f1c](https://linux-hardware.org/?probe=caa3df2f1c) | Jan 05, 2023 |
| Acer          | Nitro AN515-44              | [c1375455dc](https://linux-hardware.org/?probe=c1375455dc) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1d25f1df44](https://linux-hardware.org/?probe=1d25f1df44) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Acer          | Aspire A315-54              | [22b6517ed2](https://linux-hardware.org/?probe=22b6517ed2) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | G15 5510                    | [e0282d77f8](https://linux-hardware.org/?probe=e0282d77f8) | Jan 05, 2023 |
| Avell High... | B.ON                        | [99a8cc2270](https://linux-hardware.org/?probe=99a8cc2270) | Jan 05, 2023 |
| Multilaser    | PC024                       | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| ASUSTek       | X510UAR                     | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Acer          | Nitro AN515-54              | [26165b2acb](https://linux-hardware.org/?probe=26165b2acb) | Jan 04, 2023 |
| Acer          | Nitro AN515-54              | [1fd86a44c5](https://linux-hardware.org/?probe=1fd86a44c5) | Jan 04, 2023 |
| Acer          | Aspire A315-58              | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Sony          | VJF153                      | [f3643923cc](https://linux-hardware.org/?probe=f3643923cc) | Jan 04, 2023 |
| HP            | G42                         | [a1e6624ba4](https://linux-hardware.org/?probe=a1e6624ba4) | Jan 03, 2023 |
| Lenovo        | ThinkPad E550 20DF0030US    | [31d3e37e7f](https://linux-hardware.org/?probe=31d3e37e7f) | Jan 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [37cbf7c1a4](https://linux-hardware.org/?probe=37cbf7c1a4) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| Dell          | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Positivo      | H14CU01                     | [f668eee758](https://linux-hardware.org/?probe=f668eee758) | Jan 02, 2023 |
| Notebook      | NJx0MU                      | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [4d7f89dc6d](https://linux-hardware.org/?probe=4d7f89dc6d) | Dec 31, 2022 |
| Valve         | Jupiter                     | [97da60caa9](https://linux-hardware.org/?probe=97da60caa9) | Dec 31, 2022 |
| HP            | Folio 13                    | [9f00cfe432](https://linux-hardware.org/?probe=9f00cfe432) | Dec 31, 2022 |
| HP            | Folio 13                    | [3ed5b405cb](https://linux-hardware.org/?probe=3ed5b405cb) | Dec 31, 2022 |
| Unknown       | Unknown                     | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [18827f3f77](https://linux-hardware.org/?probe=18827f3f77) | Dec 31, 2022 |
| Acer          | Predator G3-572             | [ab03199a79](https://linux-hardware.org/?probe=ab03199a79) | Dec 30, 2022 |
| Compaq        | CQ-27                       | [fc5b98e1db](https://linux-hardware.org/?probe=fc5b98e1db) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| HP            | Pavilion dv6                | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| Acer          | Predator G3-572             | [f99480426f](https://linux-hardware.org/?probe=f99480426f) | Dec 29, 2022 |
| Samsung       | 550XBE/350XBE               | [33c4b80d0a](https://linux-hardware.org/?probe=33c4b80d0a) | Dec 29, 2022 |
| Dell          | Inspiron N4050              | [b34f09894d](https://linux-hardware.org/?probe=b34f09894d) | Dec 29, 2022 |
| Dell          | Inspiron 3583               | [35f6da18cc](https://linux-hardware.org/?probe=35f6da18cc) | Dec 29, 2022 |
| HP            | 250 G8 Notebook PC          | [754ba4696d](https://linux-hardware.org/?probe=754ba4696d) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| Acer          | Aspire A515-55              | [296961ae2d](https://linux-hardware.org/?probe=296961ae2d) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| Acer          | Predator PH315-53           | [d5d0e740c1](https://linux-hardware.org/?probe=d5d0e740c1) | Dec 29, 2022 |
| Dell          | G5 5590                     | [58bd69f40b](https://linux-hardware.org/?probe=58bd69f40b) | Dec 28, 2022 |
| Dell          | Inspiron 5458               | [269d455191](https://linux-hardware.org/?probe=269d455191) | Dec 28, 2022 |
| Lenovo        | 100-14IBY 80R7              | [92b2614ac2](https://linux-hardware.org/?probe=92b2614ac2) | Dec 28, 2022 |
| Samsung       | 550XDA                      | [6d744c7602](https://linux-hardware.org/?probe=6d744c7602) | Dec 28, 2022 |
| Samsung       | 550XDA                      | [b463fa7a54](https://linux-hardware.org/?probe=b463fa7a54) | Dec 28, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [5383fb814b](https://linux-hardware.org/?probe=5383fb814b) | Dec 28, 2022 |
| Positivo      | Hendrix                     | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Acer          | Aspire E5-574               | [15e48d4c24](https://linux-hardware.org/?probe=15e48d4c24) | Dec 27, 2022 |
| Acer          | Nitro AN515-54              | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | [22540f4247](https://linux-hardware.org/?probe=22540f4247) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | [b47449f70f](https://linux-hardware.org/?probe=b47449f70f) | Dec 27, 2022 |
| Dell          | Inspiron N4050              | [542b5ae2f6](https://linux-hardware.org/?probe=542b5ae2f6) | Dec 27, 2022 |
| Dell          | Vostro 5490                 | [d32b30987a](https://linux-hardware.org/?probe=d32b30987a) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Samsung       | 300E5M/300E5L               | [669e014ee6](https://linux-hardware.org/?probe=669e014ee6) | Dec 27, 2022 |
| Dell          | Inspiron 15-3567            | [2f5381fa26](https://linux-hardware.org/?probe=2f5381fa26) | Dec 26, 2022 |
| Dell          | Inspiron 7580               | [a1638729b2](https://linux-hardware.org/?probe=a1638729b2) | Dec 26, 2022 |
| Dell          | Vostro 5490                 | [97677e7c79](https://linux-hardware.org/?probe=97677e7c79) | Dec 26, 2022 |
| Dell          | Inspiron 5458               | [4e393c7334](https://linux-hardware.org/?probe=4e393c7334) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | SVF15213CBB                 | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
| HP            | ProBook 6465b               | [d0f5218f72](https://linux-hardware.org/?probe=d0f5218f72) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| Toshiba       | PORTEGE Z930                | [4a77067c41](https://linux-hardware.org/?probe=4a77067c41) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [ccd5d4bac3](https://linux-hardware.org/?probe=ccd5d4bac3) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| HP            | Pavilion g4                 | [a5d26c4498](https://linux-hardware.org/?probe=a5d26c4498) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c95a4418f0](https://linux-hardware.org/?probe=c95a4418f0) | Dec 24, 2022 |
| Dell          | Vostro 3500                 | [0d59e2b098](https://linux-hardware.org/?probe=0d59e2b098) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [28b89e2321](https://linux-hardware.org/?probe=28b89e2321) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Dell          | XPS L322X                   | [c127721464](https://linux-hardware.org/?probe=c127721464) | Dec 24, 2022 |
| Samsung       | RF511/RF411/RF711           | [b0a9f1ed91](https://linux-hardware.org/?probe=b0a9f1ed91) | Dec 24, 2022 |
| Valve         | Jupiter                     | [a38f241e2e](https://linux-hardware.org/?probe=a38f241e2e) | Dec 24, 2022 |
| Acer          | Aspire A514-54              | [ea57f4aa3a](https://linux-hardware.org/?probe=ea57f4aa3a) | Dec 24, 2022 |
| Samsung       | 550XBE/350XBE               | [4ea620705d](https://linux-hardware.org/?probe=4ea620705d) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Positivo      | Mobile                      | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Avell High... | B.ON                        | [ea8a4babbf](https://linux-hardware.org/?probe=ea8a4babbf) | Dec 24, 2022 |
| Dell          | Latitude 5420               | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Positivo      | H14BT58                     | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| Chuwi         | HeroBook Air                | [8f4eea6be8](https://linux-hardware.org/?probe=8f4eea6be8) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [6b2cd55178](https://linux-hardware.org/?probe=6b2cd55178) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Dell          | G3 3590                     | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | [22eafd12e4](https://linux-hardware.org/?probe=22eafd12e4) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | [f250052dff](https://linux-hardware.org/?probe=f250052dff) | Dec 23, 2022 |
| Positivo      | C4128E-S                    | [2fce43e57f](https://linux-hardware.org/?probe=2fce43e57f) | Dec 23, 2022 |
| Samsung       | 270E5J/2570EJ               | [7efb2defb9](https://linux-hardware.org/?probe=7efb2defb9) | Dec 23, 2022 |
| Acer          | Nitro AN515-51              | [9dca0f7674](https://linux-hardware.org/?probe=9dca0f7674) | Dec 22, 2022 |
| Dell          | Vostro 5490                 | [2d85a576e1](https://linux-hardware.org/?probe=2d85a576e1) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [37f100cf13](https://linux-hardware.org/?probe=37f100cf13) | Dec 22, 2022 |
| Dell          | Inspiron 5590               | [4e4cf63a0a](https://linux-hardware.org/?probe=4e4cf63a0a) | Dec 22, 2022 |
| Acer          | Nitro AN517-54              | [08539171a8](https://linux-hardware.org/?probe=08539171a8) | Dec 22, 2022 |
| Dell          | System XPS L502X            | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Positivo      | S14SL01                     | [476e8a784c](https://linux-hardware.org/?probe=476e8a784c) | Dec 21, 2022 |
| Positivo      | S14SL01                     | [08e3a4d7f2](https://linux-hardware.org/?probe=08e3a4d7f2) | Dec 21, 2022 |
| ASUSTek       | X450CA                      | [5b793f14ff](https://linux-hardware.org/?probe=5b793f14ff) | Dec 21, 2022 |
| Multilaser    | MLSH1H LINUX                | [70695e9f3b](https://linux-hardware.org/?probe=70695e9f3b) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [77c9275988](https://linux-hardware.org/?probe=77c9275988) | Dec 21, 2022 |
| Positivo      | C14CR21                     | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Dell          | Latitude 3420               | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| Samsung       | 300E5M/300E5L               | [4c6ab7c16e](https://linux-hardware.org/?probe=4c6ab7c16e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| Positivo      | Master N8340                | [643f2e00e0](https://linux-hardware.org/?probe=643f2e00e0) | Dec 20, 2022 |
| Dell          | Inspiron 15 5510            | [e1d9b06871](https://linux-hardware.org/?probe=e1d9b06871) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Acer          | Extensa 5230                | [0cfe897a2b](https://linux-hardware.org/?probe=0cfe897a2b) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Multilaser    | UB23X LINUX                 | [9f7503d89d](https://linux-hardware.org/?probe=9f7503d89d) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [751834957d](https://linux-hardware.org/?probe=751834957d) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Multilaser    | UB23X LINUX                 | [502d9cd6ce](https://linux-hardware.org/?probe=502d9cd6ce) | Dec 19, 2022 |
| Sony          | VPCEA23FB                   | [a374bedbed](https://linux-hardware.org/?probe=a374bedbed) | Dec 19, 2022 |
| Acer          | Extensa 5230                | [dfe70c9fdc](https://linux-hardware.org/?probe=dfe70c9fdc) | Dec 19, 2022 |
| HP            | ProBook 4530s               | [2c6a27a08d](https://linux-hardware.org/?probe=2c6a27a08d) | Dec 19, 2022 |
| HP            | ProBook 4530s               | [19892439d6](https://linux-hardware.org/?probe=19892439d6) | Dec 19, 2022 |
| Acer          | Nitro AN515-54              | [5254697dbb](https://linux-hardware.org/?probe=5254697dbb) | Dec 19, 2022 |
| Alienware     | m15 R7                      | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| ASUSTek       | X451CAP                     | [358fa50e0c](https://linux-hardware.org/?probe=358fa50e0c) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b1655d054](https://linux-hardware.org/?probe=7b1655d054) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [07ae580adc](https://linux-hardware.org/?probe=07ae580adc) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Gateway       | NV55C                       | [150f4e3dbc](https://linux-hardware.org/?probe=150f4e3dbc) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c0150b6ae](https://linux-hardware.org/?probe=5c0150b6ae) | Dec 17, 2022 |
| Samsung       | RV415/RV515                 | [dcf4e8200b](https://linux-hardware.org/?probe=dcf4e8200b) | Dec 17, 2022 |
| Sony          | VPCCW21FX                   | [9d82e3655b](https://linux-hardware.org/?probe=9d82e3655b) | Dec 17, 2022 |
| Avell High... | B.ON                        | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| Dell          | Inspiron 5547               | [9dede41c5d](https://linux-hardware.org/?probe=9dede41c5d) | Dec 17, 2022 |
| Dell          | Inspiron 3583               | [5629961182](https://linux-hardware.org/?probe=5629961182) | Dec 17, 2022 |
| Apple         | MacBookPro8,1               | [a30cdfc558](https://linux-hardware.org/?probe=a30cdfc558) | Dec 16, 2022 |
| Digibras      | US41II1                     | [6b1d584ff8](https://linux-hardware.org/?probe=6b1d584ff8) | Dec 16, 2022 |
| Chuwi         | HeroBook Air                | [6da143680b](https://linux-hardware.org/?probe=6da143680b) | Dec 16, 2022 |
| Dell          | Inspiron 5458               | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| Dell          | Latitude 5480               | [43e6598fd7](https://linux-hardware.org/?probe=43e6598fd7) | Dec 16, 2022 |
| Dell          | Inspiron 5566               | [ccfc358303](https://linux-hardware.org/?probe=ccfc358303) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0f73c873b1](https://linux-hardware.org/?probe=0f73c873b1) | Dec 16, 2022 |
| Toshiba       | IS 1442                     | [c028a09103](https://linux-hardware.org/?probe=c028a09103) | Dec 15, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [87f99a0bb2](https://linux-hardware.org/?probe=87f99a0bb2) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0da6ba8094](https://linux-hardware.org/?probe=0da6ba8094) | Dec 15, 2022 |
| Avell High... | A60 MUV                     | [204d35bad7](https://linux-hardware.org/?probe=204d35bad7) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f5a317963c](https://linux-hardware.org/?probe=f5a317963c) | Dec 15, 2022 |
| Dell          | G15 5511                    | [8454bbb59e](https://linux-hardware.org/?probe=8454bbb59e) | Dec 15, 2022 |
| Acer          | Nitro AN517-51              | [a621dbb00e](https://linux-hardware.org/?probe=a621dbb00e) | Dec 15, 2022 |
| Lenovo        | ThinkPad X230 23245QP       | [e525a77c95](https://linux-hardware.org/?probe=e525a77c95) | Dec 15, 2022 |
| Lenovo        | G460 20041                  | [b76fa704f7](https://linux-hardware.org/?probe=b76fa704f7) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| Dell          | Inspiron 5584               | [274fa56da6](https://linux-hardware.org/?probe=274fa56da6) | Dec 13, 2022 |
| Acer          | Aspire A514-54              | [6aa836cfc6](https://linux-hardware.org/?probe=6aa836cfc6) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [726380956e](https://linux-hardware.org/?probe=726380956e) | Dec 13, 2022 |
| Apple         | MacBookPro8,2               | [05ef133104](https://linux-hardware.org/?probe=05ef133104) | Dec 12, 2022 |
| Positivo B... | VJFE44F11X-B2111H           | [903b25c77f](https://linux-hardware.org/?probe=903b25c77f) | Dec 12, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [304bad9c19](https://linux-hardware.org/?probe=304bad9c19) | Dec 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ce1ae34933](https://linux-hardware.org/?probe=ce1ae34933) | Dec 12, 2022 |
| Dell          | Inspiron 15 3511            | [db4a92dae2](https://linux-hardware.org/?probe=db4a92dae2) | Dec 11, 2022 |
| Dell          | Inspiron 1545               | [31ad9ff6a7](https://linux-hardware.org/?probe=31ad9ff6a7) | Dec 10, 2022 |
| Dell          | Inspiron 1545               | [f147df85e6](https://linux-hardware.org/?probe=f147df85e6) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [e80dfca4a8](https://linux-hardware.org/?probe=e80dfca4a8) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [72f0e70b26](https://linux-hardware.org/?probe=72f0e70b26) | Dec 10, 2022 |
| Samsung       | 270E5K                      | [9164b7d324](https://linux-hardware.org/?probe=9164b7d324) | Dec 09, 2022 |
| Dell          | Inspiron 3583               | [93934b74f5](https://linux-hardware.org/?probe=93934b74f5) | Dec 09, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [63e4c154a2](https://linux-hardware.org/?probe=63e4c154a2) | Dec 09, 2022 |
| Positivo      | Mobile                      | [bc5f4e6c85](https://linux-hardware.org/?probe=bc5f4e6c85) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| Dell          | Latitude 3400               | [d01726a4d0](https://linux-hardware.org/?probe=d01726a4d0) | Dec 08, 2022 |
| Digibras      | US41II1                     | [b4651a173e](https://linux-hardware.org/?probe=b4651a173e) | Dec 08, 2022 |
| Dell          | Inspiron 5566               | [dcf5539e74](https://linux-hardware.org/?probe=dcf5539e74) | Dec 08, 2022 |
| Notebook      | NJx0MU                      | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [00995baaae](https://linux-hardware.org/?probe=00995baaae) | Dec 07, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [8575adb47e](https://linux-hardware.org/?probe=8575adb47e) | Dec 07, 2022 |
| Digibras      | US41II1                     | [eafbffa1b4](https://linux-hardware.org/?probe=eafbffa1b4) | Dec 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [db53a5df72](https://linux-hardware.org/?probe=db53a5df72) | Dec 07, 2022 |
| Positivo      | H14BT58                     | [c038df5c8c](https://linux-hardware.org/?probe=c038df5c8c) | Dec 07, 2022 |
| Dell          | Latitude E6420              | [e87ced9ea4](https://linux-hardware.org/?probe=e87ced9ea4) | Dec 06, 2022 |
| Dell          | Latitude E6420              | [17c9263444](https://linux-hardware.org/?probe=17c9263444) | Dec 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [87d3ead3ba](https://linux-hardware.org/?probe=87d3ead3ba) | Dec 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4eaf92f82b](https://linux-hardware.org/?probe=4eaf92f82b) | Dec 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [abe6a39746](https://linux-hardware.org/?probe=abe6a39746) | Dec 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| Acer          | Aspire F5-573               | [c5f8c3ee20](https://linux-hardware.org/?probe=c5f8c3ee20) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0e42e5cbeb](https://linux-hardware.org/?probe=0e42e5cbeb) | Dec 06, 2022 |
| Acer          | Aspire A515-56              | [9cb1b48840](https://linux-hardware.org/?probe=9cb1b48840) | Dec 05, 2022 |
| Acer          | Aspire A515-56              | [5108572656](https://linux-hardware.org/?probe=5108572656) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Dell          | Vostro 1310                 | [60bdc28f50](https://linux-hardware.org/?probe=60bdc28f50) | Dec 04, 2022 |
| Acer          | Aspire 5750                 | [bfe28498bd](https://linux-hardware.org/?probe=bfe28498bd) | Dec 04, 2022 |
| Dell          | Inspiron 5566               | [fb9c1854a2](https://linux-hardware.org/?probe=fb9c1854a2) | Dec 04, 2022 |
| Acer          | Aspire A515-45              | [48d98f5da4](https://linux-hardware.org/?probe=48d98f5da4) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [05ae64c1b8](https://linux-hardware.org/?probe=05ae64c1b8) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [ae6745045a](https://linux-hardware.org/?probe=ae6745045a) | Dec 04, 2022 |
| Samsung       | 270E5J/2570EJ               | [084c39f0b7](https://linux-hardware.org/?probe=084c39f0b7) | Dec 04, 2022 |
| Acer          | Swift SF514-56T             | [07e72975a2](https://linux-hardware.org/?probe=07e72975a2) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [d64c6bc6f4](https://linux-hardware.org/?probe=d64c6bc6f4) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [a9f812a233](https://linux-hardware.org/?probe=a9f812a233) | Dec 03, 2022 |
| Sony          | SVE14A18ECH                 | [4ea36d0512](https://linux-hardware.org/?probe=4ea36d0512) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Acer          | Aspire A515-54G             | [0bcc1e2664](https://linux-hardware.org/?probe=0bcc1e2664) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2bde4950e9](https://linux-hardware.org/?probe=2bde4950e9) | Dec 02, 2022 |
| Acer          | Aspire A515-45              | [495abda40a](https://linux-hardware.org/?probe=495abda40a) | Dec 02, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ae8f8361c1](https://linux-hardware.org/?probe=ae8f8361c1) | Dec 02, 2022 |
| Positivo B... | VJFE53F11X-B0511H           | [24b1be97d6](https://linux-hardware.org/?probe=24b1be97d6) | Dec 01, 2022 |
| Positivo B... | VJFE53F11X-B0511H           | [a2e91cba31](https://linux-hardware.org/?probe=a2e91cba31) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Samsung       | 300E5K/300E5Q               | [f6bb652f5a](https://linux-hardware.org/?probe=f6bb652f5a) | Nov 30, 2022 |
| Samsung       | 550XDA                      | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [d95adc01a7](https://linux-hardware.org/?probe=d95adc01a7) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Philco        | 14H                         | [8d29065667](https://linux-hardware.org/?probe=8d29065667) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Positivo B... | S14SL03                     | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| Dell          | Vostro 5470                 | [15c504a6ef](https://linux-hardware.org/?probe=15c504a6ef) | Nov 29, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [adb0404576](https://linux-hardware.org/?probe=adb0404576) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Acer          | TravelMate B113             | [567c2d2e20](https://linux-hardware.org/?probe=567c2d2e20) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Dell          | G15 5520                    | [251078d1b4](https://linux-hardware.org/?probe=251078d1b4) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [ab9e6cc193](https://linux-hardware.org/?probe=ab9e6cc193) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [a4d6ce5fa1](https://linux-hardware.org/?probe=a4d6ce5fa1) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | [99e1d10484](https://linux-hardware.org/?probe=99e1d10484) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | [7d3bf460f7](https://linux-hardware.org/?probe=7d3bf460f7) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [c41d8da6ac](https://linux-hardware.org/?probe=c41d8da6ac) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [47d9a5f1ca](https://linux-hardware.org/?probe=47d9a5f1ca) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [5d324af4d0](https://linux-hardware.org/?probe=5d324af4d0) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c3e10b2149](https://linux-hardware.org/?probe=c3e10b2149) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [cd5eb0566d](https://linux-hardware.org/?probe=cd5eb0566d) | Nov 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [3e969e8aa0](https://linux-hardware.org/?probe=3e969e8aa0) | Nov 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2965050f1a](https://linux-hardware.org/?probe=2965050f1a) | Nov 25, 2022 |
| ASUSTek       | Z450LA                      | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| Notebook      | NJx0MU                      | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| Acer          | Nitro AN515-52              | [c639db74cb](https://linux-hardware.org/?probe=c639db74cb) | Nov 25, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| Avell High... | STORM TWO                   | [d8a406b26c](https://linux-hardware.org/?probe=d8a406b26c) | Nov 24, 2022 |
| Sony          | VPCEA23FB                   | [187f57793d](https://linux-hardware.org/?probe=187f57793d) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47116ddd3e](https://linux-hardware.org/?probe=47116ddd3e) | Nov 24, 2022 |
| Toshiba       | IS 1442                     | [8a2d7b5a48](https://linux-hardware.org/?probe=8a2d7b5a48) | Nov 23, 2022 |
| Notebook      | NJx0MU                      | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Dell          | System Vostro 3460          | [4f9fb6602d](https://linux-hardware.org/?probe=4f9fb6602d) | Nov 23, 2022 |
| Samsung       | 270E5K                      | [871e23c67c](https://linux-hardware.org/?probe=871e23c67c) | Nov 23, 2022 |
| Samsung       | 270E5K                      | [398893bbd1](https://linux-hardware.org/?probe=398893bbd1) | Nov 23, 2022 |
| Positivo      | Mobile                      | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [0fd3b230e0](https://linux-hardware.org/?probe=0fd3b230e0) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Acer          | Aspire E5-574G              | [703b6ee54d](https://linux-hardware.org/?probe=703b6ee54d) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| Acer          | Nitro AN515-52              | [57b2e84560](https://linux-hardware.org/?probe=57b2e84560) | Nov 22, 2022 |
| Dell          | Latitude 5480               | [5b9f1e717c](https://linux-hardware.org/?probe=5b9f1e717c) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Dell          | Inspiron 5548               | [8d8a193e7b](https://linux-hardware.org/?probe=8d8a193e7b) | Nov 21, 2022 |
| Dell          | Inspiron 3442               | [d9678fb5a7](https://linux-hardware.org/?probe=d9678fb5a7) | Nov 21, 2022 |
| Acer          | Nitro AN515-52              | [308968646b](https://linux-hardware.org/?probe=308968646b) | Nov 21, 2022 |
| Toshiba       | IS 1422                     | [aa59e6576d](https://linux-hardware.org/?probe=aa59e6576d) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [aa4d9601ee](https://linux-hardware.org/?probe=aa4d9601ee) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [5739045caa](https://linux-hardware.org/?probe=5739045caa) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Acer          | Aspire A515-45              | [11e00d597d](https://linux-hardware.org/?probe=11e00d597d) | Nov 20, 2022 |
| Acer          | Nitro AN515-44              | [c6b85f956a](https://linux-hardware.org/?probe=c6b85f956a) | Nov 20, 2022 |
| Acer          | Aspire E1-571               | [35fc3411ec](https://linux-hardware.org/?probe=35fc3411ec) | Nov 20, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [1253590f60](https://linux-hardware.org/?probe=1253590f60) | Nov 20, 2022 |
| Samsung       | 767XCL                      | [729f4f303e](https://linux-hardware.org/?probe=729f4f303e) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e777561ba5](https://linux-hardware.org/?probe=e777561ba5) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [496647cddb](https://linux-hardware.org/?probe=496647cddb) | Nov 19, 2022 |
| Dell          | Inspiron 15-3567            | [5d6f9e57c5](https://linux-hardware.org/?probe=5d6f9e57c5) | Nov 19, 2022 |
| Dell          | Vostro 3501                 | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [1d527a6849](https://linux-hardware.org/?probe=1d527a6849) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| HP            | Presario CQ43               | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [f796cfccaa](https://linux-hardware.org/?probe=f796cfccaa) | Nov 17, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [873552cfae](https://linux-hardware.org/?probe=873552cfae) | Nov 17, 2022 |
| Compaq        | 420                         | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | [7d7f4061fa](https://linux-hardware.org/?probe=7d7f4061fa) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | [d36317c3be](https://linux-hardware.org/?probe=d36317c3be) | Nov 17, 2022 |
| Dell          | G15 5510                    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [7aa6773734](https://linux-hardware.org/?probe=7aa6773734) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [d5c4a2f02e](https://linux-hardware.org/?probe=d5c4a2f02e) | Nov 16, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Dell          | Inspiron 3583               | [1dc59dc45d](https://linux-hardware.org/?probe=1dc59dc45d) | Nov 16, 2022 |
| Sony          | SVE14A15FBB                 | [1b368520d1](https://linux-hardware.org/?probe=1b368520d1) | Nov 16, 2022 |
| Positivo B... | VJFE44F11X-B2111H           | [070af1bd42](https://linux-hardware.org/?probe=070af1bd42) | Nov 16, 2022 |
| Notebook      | NJx0MU                      | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Acer          | Aspire E5-571               | [3e04c315ee](https://linux-hardware.org/?probe=3e04c315ee) | Nov 15, 2022 |
| Daten Tecn... | DT02-M4                     | [783a9a5607](https://linux-hardware.org/?probe=783a9a5607) | Nov 15, 2022 |
| Gateway       | NV55C                       | [64d8e467d4](https://linux-hardware.org/?probe=64d8e467d4) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [a21cf96dd6](https://linux-hardware.org/?probe=a21cf96dd6) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [14e272fe11](https://linux-hardware.org/?probe=14e272fe11) | Nov 15, 2022 |
| Samsung       | RV411                       | [ded212573f](https://linux-hardware.org/?probe=ded212573f) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | [c6b6ee8cc8](https://linux-hardware.org/?probe=c6b6ee8cc8) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | [e751f32d49](https://linux-hardware.org/?probe=e751f32d49) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Lenovo        | G50-80 80R0                 | [35193d2431](https://linux-hardware.org/?probe=35193d2431) | Nov 14, 2022 |
| Dell          | Vostro 5470                 | [5b542891b7](https://linux-hardware.org/?probe=5b542891b7) | Nov 14, 2022 |
| Multilaser    | PC121                       | [5870f0d565](https://linux-hardware.org/?probe=5870f0d565) | Nov 14, 2022 |
| Acer          | Nitro AN517-54              | [b5c1404ef7](https://linux-hardware.org/?probe=b5c1404ef7) | Nov 13, 2022 |
| Dell          | G15 5510                    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| Google        | Celes                       | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Standard      | MB40II                      | [c95529c90a](https://linux-hardware.org/?probe=c95529c90a) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | [d3b618e418](https://linux-hardware.org/?probe=d3b618e418) | Nov 12, 2022 |
| Apple         | MacBookPro6,2               | [3c63d3fb1e](https://linux-hardware.org/?probe=3c63d3fb1e) | Nov 11, 2022 |
| Notebook      | NJx0MU                      | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| LG Electro... | 15Z970-E.BH91P1             | [347940efc3](https://linux-hardware.org/?probe=347940efc3) | Nov 11, 2022 |
| Toshiba       | IS 1422+                    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [fb2b32db6a](https://linux-hardware.org/?probe=fb2b32db6a) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Acer          | Aspire 5742                 | [9c688c611e](https://linux-hardware.org/?probe=9c688c611e) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| HP            | Pavilion dv2700             | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [63b53e81ed](https://linux-hardware.org/?probe=63b53e81ed) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [22b8b36df5](https://linux-hardware.org/?probe=22b8b36df5) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [3e808157a3](https://linux-hardware.org/?probe=3e808157a3) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a4bce0a93a](https://linux-hardware.org/?probe=a4bce0a93a) | Nov 07, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [589354a449](https://linux-hardware.org/?probe=589354a449) | Nov 07, 2022 |
| Dell          | Latitude 3410               | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [c2f8bf4caf](https://linux-hardware.org/?probe=c2f8bf4caf) | Nov 07, 2022 |
| ASUSTek       | K52Jr                       | [7be3408f46](https://linux-hardware.org/?probe=7be3408f46) | Nov 07, 2022 |
| Lenovo        | G475 20080                  | [f0f78f8e7e](https://linux-hardware.org/?probe=f0f78f8e7e) | Nov 07, 2022 |
| Acer          | Aspire 5742                 | [028e3c3f64](https://linux-hardware.org/?probe=028e3c3f64) | Nov 06, 2022 |
| Samsung       | 550XDA                      | [a57a40964e](https://linux-hardware.org/?probe=a57a40964e) | Nov 06, 2022 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [5afc3788fc](https://linux-hardware.org/?probe=5afc3788fc) | Nov 06, 2022 |
| Quanta        | TWS                         | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Positivo      | W940TU                      | [ad13b613fa](https://linux-hardware.org/?probe=ad13b613fa) | Nov 06, 2022 |
| Quanta        | TWS                         | [a800f54191](https://linux-hardware.org/?probe=a800f54191) | Nov 06, 2022 |
| Positivo      | W940TU                      | [ee23486fc7](https://linux-hardware.org/?probe=ee23486fc7) | Nov 06, 2022 |
| Acer          | Nitro AN515-44              | [91851e068d](https://linux-hardware.org/?probe=91851e068d) | Nov 06, 2022 |
| Dell          | Inspiron 15-3552            | [f72391a03b](https://linux-hardware.org/?probe=f72391a03b) | Nov 05, 2022 |
| Dell          | Inspiron 5402               | [109f44c580](https://linux-hardware.org/?probe=109f44c580) | Nov 05, 2022 |
| Samsung       | 270E5J/2570EJ               | [1466580b6e](https://linux-hardware.org/?probe=1466580b6e) | Nov 05, 2022 |
| Dell          | Vostro 13 5310              | [c25e192969](https://linux-hardware.org/?probe=c25e192969) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| Dell          | Inspiron 11-3168            | [71fac7ca47](https://linux-hardware.org/?probe=71fac7ca47) | Nov 05, 2022 |
| Toshiba       | IS 1422                     | [2ea67b9fac](https://linux-hardware.org/?probe=2ea67b9fac) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| Acer          | Nitro AN515-44              | [03176fa010](https://linux-hardware.org/?probe=03176fa010) | Nov 04, 2022 |
| Dell          | G15 5511                    | [68f1e6d4f0](https://linux-hardware.org/?probe=68f1e6d4f0) | Nov 04, 2022 |
| Sony          | VPCEA23FB                   | [ff50b0dd2a](https://linux-hardware.org/?probe=ff50b0dd2a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| Sony          | VPCEB4L1E                   | [5448ca63bc](https://linux-hardware.org/?probe=5448ca63bc) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [9fbf084c28](https://linux-hardware.org/?probe=9fbf084c28) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Avell High... | B.ON                        | [f0ea745f7d](https://linux-hardware.org/?probe=f0ea745f7d) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| Intel         | powered classmate PC        | [5e9392864a](https://linux-hardware.org/?probe=5e9392864a) | Nov 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [43609f5bd5](https://linux-hardware.org/?probe=43609f5bd5) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| Positivo      | Mobile                      | [f35235fdfa](https://linux-hardware.org/?probe=f35235fdfa) | Nov 03, 2022 |
| Positivo      | Mobile                      | [581c79bdee](https://linux-hardware.org/?probe=581c79bdee) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | [cdd5c3cca0](https://linux-hardware.org/?probe=cdd5c3cca0) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | [7d43f3c00b](https://linux-hardware.org/?probe=7d43f3c00b) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| Samsung       | 550P5C/550P7C               | [39cb4cb083](https://linux-hardware.org/?probe=39cb4cb083) | Nov 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | [09c2704bb0](https://linux-hardware.org/?probe=09c2704bb0) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| HP            | Pavilion 15                 | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Samsung       | 800G5M/800G5W               | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [973fc77891](https://linux-hardware.org/?probe=973fc77891) | Oct 31, 2022 |
| LG Electro... | A560-T.BG77P1               | [cad4120a42](https://linux-hardware.org/?probe=cad4120a42) | Oct 31, 2022 |
| Avell High... | B.ON                        | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c8970ae94a](https://linux-hardware.org/?probe=c8970ae94a) | Oct 31, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Samsung       | 800G5M/800G5W               | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| Dell          | Precision 5750              | [9b9addd3b7](https://linux-hardware.org/?probe=9b9addd3b7) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| Samsung       | 670Z5E                      | [159f89858c](https://linux-hardware.org/?probe=159f89858c) | Oct 28, 2022 |
| Avell High... | B.ON                        | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Samsung       | 275E4E/275E5E               | [d3aebcbac6](https://linux-hardware.org/?probe=d3aebcbac6) | Oct 27, 2022 |
| Lenovo        | Unknown                     | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [fe1166a134](https://linux-hardware.org/?probe=fe1166a134) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [b35b1298a8](https://linux-hardware.org/?probe=b35b1298a8) | Oct 27, 2022 |
| Acer          | Aspire A315-54              | [6de38f7802](https://linux-hardware.org/?probe=6de38f7802) | Oct 27, 2022 |
| Acer          | Nitro AN515-44              | [189ac65e5b](https://linux-hardware.org/?probe=189ac65e5b) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Dell          | Inspiron 5402               | [a7a8cc4cff](https://linux-hardware.org/?probe=a7a8cc4cff) | Oct 27, 2022 |
| Avell High... | A60 MUV                     | [ccdf105523](https://linux-hardware.org/?probe=ccdf105523) | Oct 26, 2022 |
| Sony          | VPCEA23FB                   | [1b9688e23f](https://linux-hardware.org/?probe=1b9688e23f) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | [a0adbfd7fe](https://linux-hardware.org/?probe=a0adbfd7fe) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | [519384ee8a](https://linux-hardware.org/?probe=519384ee8a) | Oct 26, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [562c9438d1](https://linux-hardware.org/?probe=562c9438d1) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | G40-80 80JE                 | [97dfa18602](https://linux-hardware.org/?probe=97dfa18602) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Acer          | Nitro AN515-43              | [9a9880cc6a](https://linux-hardware.org/?probe=9a9880cc6a) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | S500CA                      | [bc57450141](https://linux-hardware.org/?probe=bc57450141) | Oct 24, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [edfb470814](https://linux-hardware.org/?probe=edfb470814) | Oct 23, 2022 |
| Acer          | Aspire A315-53              | [5388646329](https://linux-hardware.org/?probe=5388646329) | Oct 23, 2022 |
| Dell          | Inspiron 3576               | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| Avell High... | C62 MOB                     | [3baeb7ee26](https://linux-hardware.org/?probe=3baeb7ee26) | Oct 22, 2022 |
| Acer          | Aspire A315-53              | [72f0c231fb](https://linux-hardware.org/?probe=72f0c231fb) | Oct 21, 2022 |
| Positivo      | S14CT01                     | [1a5f77c8f9](https://linux-hardware.org/?probe=1a5f77c8f9) | Oct 21, 2022 |
| Microboard    | Cantiga & ICH9M Chipset     | [1fffce3846](https://linux-hardware.org/?probe=1fffce3846) | Oct 21, 2022 |
| Avell High... | B.ON                        | [17ce0979b3](https://linux-hardware.org/?probe=17ce0979b3) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Dell          | Latitude E5410              | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| Positivo      | C4120F                      | [92338290da](https://linux-hardware.org/?probe=92338290da) | Oct 20, 2022 |
| Acer          | Aspire E5-574               | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Samsung       | 550XDA                      | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| Samsung       | 270E5J/2570EJ               | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| Lenovo        | G480                        | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| Avell High... | B.ON                        | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Teclast       | F7 Plus                     | [e77cad05c2](https://linux-hardware.org/?probe=e77cad05c2) | Oct 17, 2022 |
| ASUSTek       | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| Dell          | Inspiron 5447               | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Multilaser    | PC024                       | [892f53a067](https://linux-hardware.org/?probe=892f53a067) | Oct 17, 2022 |
| Acer          | Aspire 5750                 | [4e90ad293c](https://linux-hardware.org/?probe=4e90ad293c) | Oct 17, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [81cec7c137](https://linux-hardware.org/?probe=81cec7c137) | Oct 16, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [2d843ba905](https://linux-hardware.org/?probe=2d843ba905) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| Acer          | Nitro AN515-44              | [7293f219d8](https://linux-hardware.org/?probe=7293f219d8) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Alienware     | m15 R6                      | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| Acer          | Nitro AN515-44              | [8e16d67f02](https://linux-hardware.org/?probe=8e16d67f02) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Compaq        | 420                         | [cc3fae2a79](https://linux-hardware.org/?probe=cc3fae2a79) | Oct 15, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [19d249aa9c](https://linux-hardware.org/?probe=19d249aa9c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b5cfcb5d6c](https://linux-hardware.org/?probe=b5cfcb5d6c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a65b043bb7](https://linux-hardware.org/?probe=a65b043bb7) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | [491ba5984a](https://linux-hardware.org/?probe=491ba5984a) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | [d22d4118a7](https://linux-hardware.org/?probe=d22d4118a7) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| Acer          | Aspire A315-34              | [a95d9e55ba](https://linux-hardware.org/?probe=a95d9e55ba) | Oct 14, 2022 |
| Samsung       | 300E5M/300E5L               | [f8eae084ac](https://linux-hardware.org/?probe=f8eae084ac) | Oct 13, 2022 |
| Lenovo        | G50-80 80R0                 | [990bec11d7](https://linux-hardware.org/?probe=990bec11d7) | Oct 13, 2022 |
| Dell          | Inspiron 5567               | [754608b701](https://linux-hardware.org/?probe=754608b701) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Acer          | Aspire A315-53              | [3c99de982b](https://linux-hardware.org/?probe=3c99de982b) | Oct 13, 2022 |
| HP            | G42                         | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [d800a06da5](https://linux-hardware.org/?probe=d800a06da5) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [9d4c4f0c96](https://linux-hardware.org/?probe=9d4c4f0c96) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| Lenovo        | ThinkPad T480 20L6S1U700    | [df4489e9fb](https://linux-hardware.org/?probe=df4489e9fb) | Oct 12, 2022 |
| Acer          | Aspire ES1-572              | [7741ed43d0](https://linux-hardware.org/?probe=7741ed43d0) | Oct 12, 2022 |
| Acer          | Aspire A514-54              | [b566c0179a](https://linux-hardware.org/?probe=b566c0179a) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Acer          | Nitro AN515-52              | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| Acer          | Aspire E1-572               | [4097531dec](https://linux-hardware.org/?probe=4097531dec) | Oct 10, 2022 |
| Dell          | Latitude 5410               | [c69cc79a8e](https://linux-hardware.org/?probe=c69cc79a8e) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Samsung       | 550XBE/350XBE               | [bfce31736f](https://linux-hardware.org/?probe=bfce31736f) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Acer          | Nitro AN515-44              | [be45a704e2](https://linux-hardware.org/?probe=be45a704e2) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [acd8e18972](https://linux-hardware.org/?probe=acd8e18972) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| Acer          | Aspire A315-53              | [cdd4dd4637](https://linux-hardware.org/?probe=cdd4dd4637) | Oct 08, 2022 |
| Positivo      | Q232A                       | [658da8785e](https://linux-hardware.org/?probe=658da8785e) | Oct 08, 2022 |
| Standard      | MB40II                      | [97b446abda](https://linux-hardware.org/?probe=97b446abda) | Oct 08, 2022 |
| Unknown       | Unknown                     | [b941499384](https://linux-hardware.org/?probe=b941499384) | Oct 08, 2022 |
| Quanta        | TWS                         | [f7ba149979](https://linux-hardware.org/?probe=f7ba149979) | Oct 08, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [dd91590e9f](https://linux-hardware.org/?probe=dd91590e9f) | Oct 07, 2022 |
| Acer          | Aspire E1-571               | [fe1e7b060c](https://linux-hardware.org/?probe=fe1e7b060c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| Dell          | Inspiron 3542               | [f8d7d79e14](https://linux-hardware.org/?probe=f8d7d79e14) | Oct 07, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [6f08bf3d68](https://linux-hardware.org/?probe=6f08bf3d68) | Oct 07, 2022 |
| Positivo      | Mobile                      | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| Positivo      | W940SU2                     | [d403edabc4](https://linux-hardware.org/?probe=d403edabc4) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| Dell          | Inspiron 5537               | [75f96017fd](https://linux-hardware.org/?probe=75f96017fd) | Oct 05, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| Positivo      | C14CR01                     | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| Avell High... | B.ON                        | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Dell          | Inspiron 3442               | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Unknown       | Unknown                     | [23c45d949c](https://linux-hardware.org/?probe=23c45d949c) | Oct 04, 2022 |

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
| Ubuntu 20.04       | 910       | 12.16%  |
| Ubuntu 18.04       | 594       | 7.94%   |
| Ubuntu 22.04       | 225       | 3.01%   |
| Pop!_OS 20.04      | 193       | 2.58%   |
| Linux Mint 20      | 189       | 2.53%   |
| Linux Mint 19.3    | 165       | 2.2%    |
| OpenMandriva 4.2   | 156       | 2.08%   |
| OpenMandriva 4.3   | 145       | 1.94%   |
| Linux Mint 20.3    | 136       | 1.82%   |
| Linux Mint 19.1    | 122       | 1.63%   |
| Ubuntu 19.04       | 117       | 1.56%   |
| Linux Mint 20.1    | 117       | 1.56%   |
| Arch               | 114       | 1.52%   |
| Linux Mint 20.2    | 112       | 1.5%    |
| KDE neon 20.04     | 112       | 1.5%    |
| Pop!_OS 22.04      | 109       | 1.46%   |
| Manjaro            | 109       | 1.46%   |
| Ubuntu 19.10       | 106       | 1.42%   |
| Zorin 16           | 101       | 1.35%   |
| Debian 11          | 94        | 1.26%   |
| Zorin 15           | 91        | 1.22%   |
| Debian 10          | 83        | 1.11%   |
| Fedora 35          | 80        | 1.07%   |
| Fedora 34          | 73        | 0.98%   |
| Pop!_OS 21.10      | 71        | 0.95%   |
| Fedora 32          | 69        | 0.92%   |
| Endless 3.7.8      | 69        | 0.92%   |
| Xubuntu 20.04      | 68        | 0.91%   |
| Pop!_OS 21.04      | 67        | 0.9%    |
| Endless 3.9.5      | 67        | 0.9%    |
| Arch Rolling       | 67        | 0.9%    |
| Fedora 36          | 66        | 0.88%   |
| Kubuntu 20.04      | 62        | 0.83%   |
| Pop!_OS 20.10      | 60        | 0.8%    |
| Fedora 33          | 60        | 0.8%    |
| Ubuntu 20.10       | 56        | 0.75%   |
| OpenMandriva 23.01 | 56        | 0.75%   |
| Linux Mint 21      | 55        | 0.73%   |
| Linux Mint 19.2    | 55        | 0.73%   |
| Endless 3.9.1      | 53        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2125      | 29.71%  |
| Linux Mint    | 959       | 13.41%  |
| Endless       | 846       | 11.83%  |
| Pop!_OS       | 481       | 6.73%   |
| Fedora        | 421       | 5.89%   |
| OpenMandriva  | 386       | 5.4%    |
| Debian        | 225       | 3.15%   |
| Manjaro       | 205       | 2.87%   |
| Zorin         | 196       | 2.74%   |
| Arch          | 171       | 2.39%   |
| KDE neon      | 138       | 1.93%   |
| Xubuntu       | 123       | 1.72%   |
| Kubuntu       | 119       | 1.66%   |
| Lubuntu       | 70        | 0.98%   |
| Elementary    | 63        | 0.88%   |
| openSUSE      | 62        | 0.87%   |
| Ubuntu MATE   | 60        | 0.84%   |
| ROSA          | 52        | 0.73%   |
| Ubuntu Unity  | 51        | 0.71%   |
| Kali          | 39        | 0.55%   |
| LMDE          | 36        | 0.5%    |
| Deepin        | 30        | 0.42%   |
| Ubuntu Budgie | 28        | 0.39%   |
| Clear Linux   | 26        | 0.36%   |
| LinuxFX       | 21        | 0.29%   |
| ArcoLinux     | 20        | 0.28%   |
| EndeavourOS   | 14        | 0.2%    |
| BigLinux      | 14        | 0.2%    |
| BlackPanther  | 11        | 0.15%   |
| Parrot        | 10        | 0.14%   |
| CentOS        | 10        | 0.14%   |
| Reborn OS     | 9         | 0.13%   |
| Garuda Linux  | 9         | 0.13%   |
| UbuntuDDE     | 8         | 0.11%   |
| Peppermint    | 8         | 0.11%   |
| MX            | 8         | 0.11%   |
| Gentoo        | 7         | 0.1%    |
| Solus         | 6         | 0.08%   |
| Slackware     | 5         | 0.07%   |
| RHEL          | 5         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 471       | 5.86%   |
| 5.8.0-14-generic         | 285       | 3.55%   |
| 5.10.14-desktop-1omv4002 | 150       | 1.87%   |
| 5.16.7-desktop-1omv4003  | 140       | 1.74%   |
| 5.4.0-19-generic         | 114       | 1.42%   |
| 5.3.0-28-generic         | 108       | 1.34%   |
| 5.11.0-35-generic        | 88        | 1.1%    |
| 5.4.0-7634-generic       | 74        | 0.92%   |
| 5.4.0-48-generic         | 72        | 0.9%    |
| 5.4.0-40-generic         | 70        | 0.87%   |
| 4.15.0-46-generic        | 70        | 0.87%   |
| 5.4.0-26-generic         | 63        | 0.78%   |
| 5.15.0-56-generic        | 62        | 0.77%   |
| 5.4.0-58-generic         | 59        | 0.73%   |
| 5.4.0-52-generic         | 57        | 0.71%   |
| 6.1.1-desktop-1omv2290   | 54        | 0.67%   |
| 5.4.0-47-generic         | 54        | 0.67%   |
| 5.3.0-19-generic         | 50        | 0.62%   |
| 5.3.0-23-generic         | 47        | 0.59%   |
| 5.3.0-46-generic         | 46        | 0.57%   |
| 5.0.0-32-generic         | 46        | 0.57%   |
| 5.4.0-29-generic         | 44        | 0.55%   |
| 4.18.0-15-generic        | 44        | 0.55%   |
| 5.3.0-40-generic         | 43        | 0.54%   |
| 5.4.0-65-generic         | 42        | 0.52%   |
| 5.4.0-39-generic         | 41        | 0.51%   |
| 5.0.0-37-generic         | 41        | 0.51%   |
| 5.4.0-80-generic         | 40        | 0.5%    |
| 5.15.0-52-generic        | 40        | 0.5%    |
| 5.15.0-46-generic        | 40        | 0.5%    |
| 5.4.0-70-generic         | 39        | 0.49%   |
| 5.0.0-25-generic         | 39        | 0.49%   |
| 5.13.0-30-generic        | 38        | 0.47%   |
| 5.11.0-7620-generic      | 38        | 0.47%   |
| 4.18.0-16-generic        | 38        | 0.47%   |
| 5.4.0-91-generic         | 37        | 0.46%   |
| 5.4.0-37-generic         | 37        | 0.46%   |
| 4.15.0-20-generic        | 37        | 0.46%   |
| 5.15.0-58-generic        | 36        | 0.45%   |
| 5.4.0-74-generic         | 35        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1835      | 24.1%   |
| 5.8.0   | 617       | 8.1%    |
| 5.3.0   | 535       | 7.03%   |
| 4.15.0  | 514       | 6.75%   |
| 5.15.0  | 430       | 5.65%   |
| 5.11.0  | 429       | 5.63%   |
| 5.0.0   | 320       | 4.2%    |
| 5.13.0  | 269       | 3.53%   |
| 4.18.0  | 232       | 3.05%   |
| 5.10.14 | 152       | 2%      |
| 5.16.7  | 140       | 1.84%   |
| 5.10.0  | 128       | 1.68%   |
| 4.19.0  | 101       | 1.33%   |
| 5.19.0  | 73        | 0.96%   |
| 6.1.1   | 61        | 0.8%    |
| 5.17.5  | 35        | 0.46%   |
| 5.16.11 | 29        | 0.38%   |
| 5.14.0  | 27        | 0.35%   |
| 6.0.12  | 26        | 0.34%   |
| 5.7.9   | 26        | 0.34%   |
| 4.4.0   | 26        | 0.34%   |
| 5.15.15 | 20        | 0.26%   |
| 5.15.5  | 19        | 0.25%   |
| 4.9.0   | 19        | 0.25%   |
| 5.9.16  | 17        | 0.22%   |
| 5.7.0   | 17        | 0.22%   |
| 6.0.0   | 16        | 0.21%   |
| 5.6.19  | 16        | 0.21%   |
| 5.16.19 | 16        | 0.21%   |
| 5.11.12 | 16        | 0.21%   |
| 5.3.18  | 15        | 0.2%    |
| 5.16.15 | 15        | 0.2%    |
| 5.18.10 | 14        | 0.18%   |
| 5.17.0  | 14        | 0.18%   |
| 5.9.11  | 13        | 0.17%   |
| 5.6.0   | 13        | 0.17%   |
| 5.15.8  | 13        | 0.17%   |
| 6.0.6   | 12        | 0.16%   |
| 5.7.10  | 12        | 0.16%   |
| 5.13.13 | 12        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1907      | 25.35%  |
| 5.8     | 686       | 9.12%   |
| 5.15    | 591       | 7.85%   |
| 5.3     | 579       | 7.7%    |
| 4.15    | 514       | 6.83%   |
| 5.11    | 496       | 6.59%   |
| 5.10    | 384       | 5.1%    |
| 5.0     | 345       | 4.59%   |
| 5.13    | 323       | 4.29%   |
| 5.16    | 265       | 3.52%   |
| 4.18    | 248       | 3.3%    |
| 5.19    | 119       | 1.58%   |
| 4.19    | 118       | 1.57%   |
| 6.1     | 108       | 1.44%   |
| 6.0     | 101       | 1.34%   |
| 5.7     | 101       | 1.34%   |
| 5.17    | 98        | 1.3%    |
| 5.14    | 87        | 1.16%   |
| 5.18    | 76        | 1.01%   |
| 5.6     | 68        | 0.9%    |
| 5.9     | 66        | 0.88%   |
| 5.12    | 61        | 0.81%   |
| 4.9     | 43        | 0.57%   |
| 5.5     | 32        | 0.43%   |
| 4.4     | 29        | 0.39%   |
| 5.1     | 28        | 0.37%   |
| 5.2     | 15        | 0.2%    |
| 4.13    | 7         | 0.09%   |
| 4.20    | 5         | 0.07%   |
| 4.14    | 4         | 0.05%   |
| 4.10    | 4         | 0.05%   |
| 4.1     | 4         | 0.05%   |
| 6.2     | 3         | 0.04%   |
| 3.10    | 3         | 0.04%   |
| 4.17    | 2         | 0.03%   |
| 6       | 1         | 0.01%   |
| 4.8     | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 6666      | 97.47%  |
| i686   | 171       | 2.5%    |
| armv7l | 2         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3545      | 49.73%  |
| Unknown         | 978       | 13.72%  |
| KDE5            | 763       | 10.7%   |
| X-Cinnamon      | 565       | 7.93%   |
| XFCE            | 450       | 6.31%   |
| MATE            | 183       | 2.57%   |
| KDE             | 160       | 2.24%   |
| Cinnamon        | 129       | 1.81%   |
| LXQt            | 68        | 0.95%   |
| Pantheon        | 56        | 0.79%   |
| Unity           | 52        | 0.73%   |
| Deepin          | 39        | 0.55%   |
| Budgie          | 37        | 0.52%   |
| LXDE            | 32        | 0.45%   |
| KDE4            | 25        | 0.35%   |
| i3              | 19        | 0.27%   |
| GNOME Classic   | 9         | 0.13%   |
| awesome         | 5         | 0.07%   |
| sway            | 3         | 0.04%   |
| GNOME Flashback | 3         | 0.04%   |
| Enlightenment   | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Openbox         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| bspwm           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 5772      | 82.28%  |
| Wayland | 718       | 10.24%  |
| Unknown | 496       | 7.07%   |
| Tty     | 29        | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4574      | 64.48%  |
| GDM     | 751       | 10.59%  |
| SDDM    | 681       | 9.6%    |
| GDM3    | 408       | 5.75%   |
| LightDM | 352       | 4.96%   |
| TDM     | 292       | 4.12%   |
| KDM     | 26        | 0.37%   |
| XDM     | 5         | 0.07%   |
| SLiM    | 3         | 0.04%   |
| MDM     | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang      | Notebooks | Percent |
|-----------|-----------|---------|
| pt_BR     | 4665      | 66.79%  |
| en_US     | 1218      | 17.44%  |
| Unknown   | 912       | 13.06%  |
| C         | 94        | 1.35%   |
| en_GB     | 30        | 0.43%   |
| pt_PT     | 28        | 0.4%    |
| es_ES     | 11        | 0.16%   |
| fr_FR     | 5         | 0.07%   |
| en_CA     | 4         | 0.06%   |
| POSIX     | 3         | 0.04%   |
| de_DE     | 3         | 0.04%   |
| ja_JP     | 2         | 0.03%   |
| it_IT     | 2         | 0.03%   |
| ru_RU     | 1         | 0.01%   |
| pt_BRutf8 | 1         | 0.01%   |
| es_MX     | 1         | 0.01%   |
| es_CL     | 1         | 0.01%   |
| es_AR     | 1         | 0.01%   |
| en_DK     | 1         | 0.01%   |
| em_US     | 1         | 0.01%   |
| ar_EG     | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3504      | 50.02%  |
| EFI  | 3501      | 49.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5555      | 79.46%  |
| Btrfs   | 472       | 6.75%   |
| Overlay | 465       | 6.65%   |
| Unknown | 386       | 5.52%   |
| Xfs     | 46        | 0.66%   |
| Zfs     | 24        | 0.34%   |
| Tmpfs   | 15        | 0.21%   |
| Ext3    | 10        | 0.14%   |
| Ext2    | 10        | 0.14%   |
| F2fs    | 6         | 0.09%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4787      | 68.29%  |
| GPT     | 1595      | 22.75%  |
| MBR     | 628       | 8.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6270      | 90.76%  |
| Yes       | 638       | 9.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5417      | 78.13%  |
| Yes       | 1516      | 21.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1564      | 22.87%  |
| Acer                   | 1353      | 19.79%  |
| Lenovo                 | 853       | 12.47%  |
| Samsung Electronics    | 577       | 8.44%   |
| Hewlett-Packard        | 463       | 6.77%   |
| Positivo               | 454       | 6.64%   |
| ASUSTek Computer       | 382       | 5.59%   |
| Sony                   | 150       | 2.19%   |
| LG Electronics         | 92        | 1.35%   |
| Apple                  | 83        | 1.21%   |
| Avell High Performance | 72        | 1.05%   |
| Digibras               | 66        | 0.97%   |
| Itautec                | 65        | 0.95%   |
| Semp Toshiba           | 62        | 0.91%   |
| Unknown                | 62        | 0.91%   |
| Intel                  | 49        | 0.72%   |
| Philco                 | 40        | 0.58%   |
| Multilaser             | 39        | 0.57%   |
| Compaq                 | 38        | 0.56%   |
| Positivo Bahia - VAIO  | 35        | 0.51%   |
| Toshiba                | 34        | 0.5%    |
| OEM                    | 31        | 0.45%   |
| Notebook               | 25        | 0.37%   |
| Clevo                  | 22        | 0.32%   |
| Gateway                | 21        | 0.31%   |
| Compal                 | 19        | 0.28%   |
| MSI                    | 15        | 0.22%   |
| Google                 | 15        | 0.22%   |
| Alienware              | 13        | 0.19%   |
| Quanta                 | 11        | 0.16%   |
| Standard               | 10        | 0.15%   |
| eMachines              | 10        | 0.15%   |
| Timi                   | 8         | 0.12%   |
| Daten Tecnologia       | 8         | 0.12%   |
| Chuwi                  | 7         | 0.1%    |
| CCE                    | 7         | 0.1%    |
| Login Informatica      | 5         | 0.07%   |
| LNV                    | 5         | 0.07%   |
| TPVAOC                 | 4         | 0.06%   |
| IDEALMAX               | 4         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 135       | 1.97%   |
| Positivo Mobile                             | 118       | 1.73%   |
| Unknown                                     | 104       | 1.52%   |
| Acer Nitro AN515-44                         | 79        | 1.16%   |
| Acer Aspire A315-53                         | 68        | 0.99%   |
| Samsung 340XAA/350XAA/550XAA                | 67        | 0.98%   |
| Dell Inspiron 5566                          | 61        | 0.89%   |
| Lenovo IdeaPad S145-15API 81V7              | 60        | 0.88%   |
| Dell Inspiron 3583                          | 58        | 0.85%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 54        | 0.79%   |
| Acer Aspire A315-34                         | 53        | 0.78%   |
| Dell Inspiron 15-3567                       | 52        | 0.76%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 51        | 0.75%   |
| Acer Nitro AN517-51                         | 51        | 0.75%   |
| Acer Aspire A515-51                         | 48        | 0.7%    |
| Acer Nitro AN515-43                         | 45        | 0.66%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 42        | 0.61%   |
| HP G42                                      | 40        | 0.58%   |
| Samsung 300E5M/300E5L                       | 39        | 0.57%   |
| Dell Inspiron N4050                         | 38        | 0.56%   |
| Positivo S14CT01                            | 37        | 0.54%   |
| Dell Inspiron 3442                          | 37        | 0.54%   |
| Dell Inspiron 3421                          | 37        | 0.54%   |
| Acer Nitro AN515-52                         | 36        | 0.53%   |
| Dell Inspiron 7520                          | 33        | 0.48%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 32        | 0.47%   |
| Samsung 550XDA                              | 32        | 0.47%   |
| Dell Inspiron 1545                          | 32        | 0.47%   |
| Acer Aspire E1-571                          | 32        | 0.47%   |
| HP Pavilion g4                              | 31        | 0.45%   |
| Digibras NH4CU03                            | 31        | 0.45%   |
| Dell Inspiron 5458                          | 30        | 0.44%   |
| Acer Aspire E5-571                          | 30        | 0.44%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 28        | 0.41%   |
| Itautec Infoway                             | 28        | 0.41%   |
| Dell Inspiron 5437                          | 28        | 0.41%   |
| Dell G3 3590                                | 28        | 0.41%   |
| Dell Inspiron 5423                          | 27        | 0.39%   |
| Dell Inspiron 1525                          | 27        | 0.39%   |
| Acer Aspire A515-51G                        | 27        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 1023      | 14.96%  |
| Acer Aspire       | 880       | 12.87%  |
| Lenovo IdeaPad    | 466       | 6.81%   |
| Acer Nitro        | 382       | 5.59%   |
| Dell Vostro       | 209       | 3.06%   |
| Lenovo ThinkPad   | 192       | 2.81%   |
| HP Pavilion       | 184       | 2.69%   |
| Dell Latitude     | 166       | 2.43%   |
| Positivo Mobile   | 118       | 1.73%   |
| ASUS VivoBook     | 108       | 1.58%   |
| Unknown           | 104       | 1.52%   |
| Samsung 340XAA    | 67        | 0.98%   |
| Itautec Infoway   | 65        | 0.95%   |
| Dell G3           | 53        | 0.78%   |
| HP ProBook        | 47        | 0.69%   |
| Samsung RV411     | 45        | 0.66%   |
| HP G42            | 40        | 0.58%   |
| Samsung 300E5M    | 39        | 0.57%   |
| Positivo S14CT01  | 37        | 0.54%   |
| Dell System       | 37        | 0.54%   |
| HP EliteBook      | 35        | 0.51%   |
| Acer Predator     | 34        | 0.5%    |
| Samsung 550XDA    | 32        | 0.47%   |
| Semp Toshiba IS   | 31        | 0.45%   |
| Digibras NH4CU03  | 31        | 0.45%   |
| Toshiba Satellite | 28        | 0.41%   |
| Compaq Presario   | 27        | 0.39%   |
| Samsung 550XBE    | 26        | 0.38%   |
| Digibras NH4CU53  | 26        | 0.38%   |
| Samsung 370E4K    | 25        | 0.37%   |
| Samsung 270E5J    | 25        | 0.37%   |
| HP Compaq         | 25        | 0.37%   |
| Samsung RV415     | 24        | 0.35%   |
| Lenovo G400s      | 24        | 0.35%   |
| Positivo Q232A    | 23        | 0.34%   |
| Positivo H14BT58  | 23        | 0.34%   |
| Positivo CHT14B   | 23        | 0.34%   |
| Samsung 300E4C    | 22        | 0.32%   |
| Dell XPS          | 22        | 0.32%   |
| Samsung 300E5EV   | 21        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 905       | 13.23%  |
| 2012    | 713       | 10.43%  |
| 2011    | 635       | 9.29%   |
| 2018    | 566       | 8.28%   |
| 2013    | 542       | 7.93%   |
| 2017    | 514       | 7.52%   |
| 2016    | 506       | 7.4%    |
| 2010    | 424       | 6.2%    |
| 2020    | 388       | 5.67%   |
| 2014    | 371       | 5.43%   |
| 2015    | 310       | 4.53%   |
| 2021    | 300       | 4.39%   |
| 2008    | 250       | 3.66%   |
| 2009    | 219       | 3.2%    |
| 2007    | 88        | 1.29%   |
| 2022    | 35        | 0.51%   |
| 2006    | 34        | 0.5%    |
| Unknown | 25        | 0.37%   |
| 2005    | 9         | 0.13%   |
| 2004    | 4         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6838      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5838      | 84.65%  |
| Enabled  | 1059      | 15.35%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6820      | 99.74%  |
| Yes  | 18        | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2276      | 32.83%  |
| 3.01-4.0    | 1921      | 27.71%  |
| 8.01-16.0   | 968       | 13.96%  |
| 16.01-24.0  | 874       | 12.61%  |
| 1.01-2.0    | 516       | 7.44%   |
| 2.01-3.0    | 174       | 2.51%   |
| 32.01-64.0  | 112       | 1.62%   |
| 24.01-32.0  | 34        | 0.49%   |
| 0.51-1.0    | 33        | 0.48%   |
| 64.01-256.0 | 23        | 0.33%   |
| 0.01-0.5    | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2804      | 37.23%  |
| 2.01-3.0   | 2102      | 27.91%  |
| 3.01-4.0   | 995       | 13.21%  |
| 4.01-8.0   | 890       | 11.82%  |
| 0.51-1.0   | 519       | 6.89%   |
| 8.01-16.0  | 168       | 2.23%   |
| 0.01-0.5   | 40        | 0.53%   |
| 16.01-24.0 | 8         | 0.11%   |
| 32.01-64.0 | 3         | 0.04%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4881      | 70.13%  |
| 2      | 1879      | 27%     |
| 3      | 138       | 1.98%   |
| 0      | 51        | 0.73%   |
| 4      | 11        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4187      | 60.96%  |
| Yes       | 2681      | 39.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6078      | 88.69%  |
| No        | 775       | 11.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6630      | 96.75%  |
| No        | 223       | 3.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4891      | 70.82%  |
| No        | 2015      | 29.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 6838      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 844       | 11.77%  |
| Rio de Janeiro        | 371       | 5.18%   |
| Brasília             | 224       | 3.13%   |
| Curitiba              | 209       | 2.92%   |
| Belo Horizonte        | 200       | 2.79%   |
| Fortaleza             | 169       | 2.36%   |
| Porto Alegre          | 146       | 2.04%   |
| Salvador              | 114       | 1.59%   |
| Campinas              | 104       | 1.45%   |
| Recife                | 98        | 1.37%   |
| Goiânia              | 83        | 1.16%   |
| Florianópolis        | 81        | 1.13%   |
| Santo André          | 77        | 1.07%   |
| Natal                 | 75        | 1.05%   |
| Sao Luís             | 60        | 0.84%   |
| Manaus                | 59        | 0.82%   |
| Osasco                | 58        | 0.81%   |
| Campo Grande          | 57        | 0.8%    |
| Sao José dos Campos  | 54        | 0.75%   |
| Niterói              | 51        | 0.71%   |
| Joao Pessoa           | 50        | 0.7%    |
| Teresina              | 49        | 0.68%   |
| Maringá              | 48        | 0.67%   |
| Belém                | 48        | 0.67%   |
| Guarulhos             | 47        | 0.66%   |
| Sorocaba              | 45        | 0.63%   |
| Joinville             | 43        | 0.6%    |
| Uberlândia           | 41        | 0.57%   |
| Aracaju               | 41        | 0.57%   |
| Maceió               | 40        | 0.56%   |
| Londrina              | 40        | 0.56%   |
| Ribeirao Preto        | 39        | 0.54%   |
| Sao Jose              | 36        | 0.5%    |
| Cuiabá               | 35        | 0.49%   |
| Juiz de Fora          | 32        | 0.45%   |
| Vitória              | 31        | 0.43%   |
| Sao Carlos            | 31        | 0.43%   |
| Canoas                | 31        | 0.43%   |
| Sao Bernardo do Campo | 30        | 0.42%   |
| Americana             | 27        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 1912      | 2326   | 22.58%  |
| Seagate                        | 1303      | 1552   | 15.39%  |
| Kingston                       | 791       | 956    | 9.34%   |
| Samsung Electronics            | 607       | 779    | 7.17%   |
| Toshiba                        | 597       | 688    | 7.05%   |
| SanDisk                        | 484       | 633    | 5.71%   |
| Unknown                        | 380       | 506    | 4.49%   |
| A-DATA Technology              | 340       | 429    | 4.01%   |
| Intel                          | 263       | 319    | 3.11%   |
| Hitachi                        | 190       | 232    | 2.24%   |
| Crucial                        | 149       | 202    | 1.76%   |
| China                          | 145       | 177    | 1.71%   |
| ADATA Technology               | 145       | 169    | 1.71%   |
| SK hynix                       | 105       | 135    | 1.24%   |
| LITEON                         | 104       | 123    | 1.23%   |
| HGST                           | 101       | 120    | 1.19%   |
| Silicon Motion                 | 64        | 74     | 0.76%   |
| KingSpec                       | 53        | 60     | 0.63%   |
| Fujitsu                        | 42        | 49     | 0.5%    |
| JMicron Technology             | 37        | 43     | 0.44%   |
| Lexar                          | 34        | 43     | 0.4%    |
| SSSTC                          | 33        | 34     | 0.39%   |
| Phison                         | 32        | 35     | 0.38%   |
| Apple                          | 32        | 40     | 0.38%   |
| Solid State Storage Technology | 31        | 42     | 0.37%   |
| KIOXIA                         | 29        | 34     | 0.34%   |
| Netac                          | 27        | 29     | 0.32%   |
| Solid State Storage            | 26        | 29     | 0.31%   |
| Corsair                        | 26        | 26     | 0.31%   |
| Realtek Semiconductor          | 22        | 29     | 0.26%   |
| PNY                            | 20        | 27     | 0.24%   |
| Patriot                        | 18        | 21     | 0.21%   |
| Micron Technology              | 18        | 19     | 0.21%   |
| Smart                          | 17        | 19     | 0.2%    |
| Unknown                        | 17        | 18     | 0.2%    |
| XPG                            | 16        | 19     | 0.19%   |
| Hewlett-Packard                | 15        | 18     | 0.18%   |
| Gigabyte Technology            | 14        | 18     | 0.17%   |
| Micron/Crucial Technology      | 13        | 14     | 0.15%   |
| LITEONIT                       | 13        | 19     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 466       | 5.35%   |
| Kingston SA400S37240G 240GB SSD     | 276       | 3.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 253       | 2.91%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 217       | 2.49%   |
| Kingston SA400S37480G 480GB SSD     | 147       | 1.69%   |
| Toshiba MQ01ABD100 1TB              | 133       | 1.53%   |
| Kingston SA400S37120G 120GB SSD     | 127       | 1.46%   |
| WDC WD10SPZX-24Z10 1TB              | 122       | 1.4%    |
| Unknown MMC Card  32GB              | 117       | 1.34%   |
| Intel NVMe SSD Drive 512GB          | 98        | 1.13%   |
| WDC WD10JPVX-22JC3T0 1TB            | 95        | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB      | 95        | 1.09%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 87        | 1%      |
| WDC WD10SPZX-75Z10T2 1TB            | 78        | 0.9%    |
| Samsung HM321HI 320GB               | 76        | 0.87%   |
| Seagate ST9500325AS 500GB           | 73        | 0.84%   |
| Toshiba MQ04ABF100 1TB              | 71        | 0.82%   |
| SanDisk NVMe SSD Drive 512GB        | 71        | 0.82%   |
| Intel SSDPEKKW256G7 256GB           | 70        | 0.8%    |
| ADATA NVMe SSD Drive 256GB          | 67        | 0.77%   |
| SanDisk SSD PLUS 240GB              | 66        | 0.76%   |
| Kingston SV300S37A120G 120GB SSD    | 60        | 0.69%   |
| WDC WD10JPVX-75JC3T0 1TB            | 58        | 0.67%   |
| Seagate Expansion 1TB               | 57        | 0.65%   |
| Toshiba MQ01ABF050 500GB            | 56        | 0.64%   |
| SanDisk SSD PLUS 120GB              | 56        | 0.64%   |
| Seagate ST2000LM007-1R8174 2TB      | 54        | 0.62%   |
| Seagate ST500LT012-9WS142 500GB     | 53        | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 52        | 0.6%    |
| Seagate ST320LM001 HN-M320MBB 320GB | 50        | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 47        | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 45        | 0.52%   |
| WDC WD10JPCX-24UE4T0 1TB            | 44        | 0.51%   |
| Crucial CT240BX500SSD1 240GB        | 43        | 0.49%   |
| A-DATA IM2P33F3A NVMe 256GB         | 42        | 0.48%   |
| WDC WD10SPZX-75Z10T1 1TB            | 41        | 0.47%   |
| Intel NVMe SSD Drive 256GB          | 40        | 0.46%   |
| Toshiba MQ01ABD050 500GB            | 39        | 0.45%   |
| Seagate ST1000LM014-1EJ164 1TB      | 39        | 0.45%   |
| SanDisk SDSSDA240G 240GB            | 37        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1711      | 2011   | 40.23%  |
| Seagate             | 1295      | 1541   | 30.45%  |
| Toshiba             | 564       | 650    | 13.26%  |
| Samsung Electronics | 275       | 316    | 6.47%   |
| Hitachi             | 190       | 232    | 4.47%   |
| HGST                | 101       | 120    | 2.37%   |
| Fujitsu             | 41        | 47     | 0.96%   |
| JMicron Technology  | 32        | 38     | 0.75%   |
| Unknown             | 21        | 25     | 0.49%   |
| Apple               | 12        | 15     | 0.28%   |
| SAGE                | 4         | 7      | 0.09%   |
| USB3.0              | 1         | 1      | 0.02%   |
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
| Kingston            | 760       | 910    | 30.33%  |
| SanDisk             | 322       | 444    | 12.85%  |
| Samsung Electronics | 218       | 299    | 8.7%    |
| WDC                 | 195       | 238    | 7.78%   |
| A-DATA Technology   | 186       | 226    | 7.42%   |
| China               | 145       | 177    | 5.79%   |
| Crucial             | 141       | 191    | 5.63%   |
| LITEON              | 95        | 114    | 3.79%   |
| KingSpec            | 52        | 59     | 2.08%   |
| Lexar               | 33        | 42     | 1.32%   |
| Netac               | 23        | 25     | 0.92%   |
| Intel               | 22        | 26     | 0.88%   |
| Corsair             | 21        | 21     | 0.84%   |
| PNY                 | 20        | 27     | 0.8%    |
| Apple               | 19        | 23     | 0.76%   |
| Smart               | 17        | 19     | 0.68%   |
| Patriot             | 17        | 20     | 0.68%   |
| SK hynix            | 14        | 17     | 0.56%   |
| Unknown             | 13        | 14     | 0.52%   |
| LITEONIT            | 13        | 19     | 0.52%   |
| KingDian            | 12        | 18     | 0.48%   |
| Gigabyte Technology | 12        | 16     | 0.48%   |
| Hewlett-Packard     | 11        | 13     | 0.44%   |
| Unknown             | 10        | 11     | 0.4%    |
| Toshiba             | 9         | 10     | 0.36%   |
| Seagate             | 8         | 8      | 0.32%   |
| Micron Technology   | 8         | 9      | 0.32%   |
| BHT                 | 7         | 7      | 0.28%   |
| XrayDisk            | 6         | 7      | 0.24%   |
| WALRAM              | 5         | 5      | 0.2%    |
| BIWIN               | 5         | 5      | 0.2%    |
| Win Memory          | 4         | 5      | 0.16%   |
| S3+                 | 4         | 4      | 0.16%   |
| Maxtor              | 4         | 4      | 0.16%   |
| HUSKY               | 4         | 4      | 0.16%   |
| Vaseky              | 3         | 4      | 0.12%   |
| Transcend           | 3         | 3      | 0.12%   |
| RZX                 | 3         | 4      | 0.12%   |
| Plextor             | 3         | 3      | 0.12%   |
| OCZ                 | 3         | 3      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4167      | 5010   | 50.76%  |
| SSD     | 2350      | 3116   | 28.63%  |
| NVMe    | 1326      | 1714   | 16.15%  |
| MMC     | 307       | 431    | 3.74%   |
| Unknown | 59        | 72     | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5757      | 7982   | 76.17%  |
| NVMe | 1325      | 1713   | 17.53%  |
| MMC  | 307       | 431    | 4.06%   |
| SAS  | 169       | 217    | 2.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4067      | 5358   | 64.15%  |
| 0.51-1.0   | 2151      | 2621   | 33.93%  |
| 1.01-2.0   | 113       | 137    | 1.78%   |
| 4.01-10.0  | 5         | 6      | 0.08%   |
| 3.01-4.0   | 3         | 3      | 0.05%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2141      | 29.81%  |
| 251-500        | 1840      | 25.62%  |
| 501-1000       | 1301      | 18.12%  |
| 1-20           | 516       | 7.19%   |
| 51-100         | 431       | 6%      |
| 1001-2000      | 383       | 5.33%   |
| 21-50          | 350       | 4.87%   |
| Unknown        | 100       | 1.39%   |
| 2001-3000      | 66        | 0.92%   |
| More than 3000 | 53        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2844      | 38.17%  |
| 21-50          | 1767      | 23.71%  |
| 51-100         | 980       | 13.15%  |
| 101-250        | 971       | 13.03%  |
| 251-500        | 473       | 6.35%   |
| 501-1000       | 221       | 2.97%   |
| Unknown        | 100       | 1.34%   |
| 1001-2000      | 79        | 1.06%   |
| 2001-3000      | 9         | 0.12%   |
| More than 3000 | 7         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 30        | 32     | 6.73%   |
| Seagate ST9500325AS 500GB           | 21        | 23     | 4.71%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 19        | 21     | 4.26%   |
| Toshiba MQ01ABD100 1TB              | 12        | 12     | 2.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 12     | 2.69%   |
| Seagate ST500LT012-9WS142 500GB     | 9         | 11     | 2.02%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 1.57%   |
| Toshiba MQ02ABD100H 1TB             | 6         | 9      | 1.35%   |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 1.35%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 1.35%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 7      | 1.35%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 5      | 1.12%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 5         | 6      | 1.12%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 1.12%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 1.12%   |
| Samsung Electronics HM321HI 320GB   | 5         | 5      | 1.12%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 5      | 1.12%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 1.12%   |
| WDC WD10JPCX-24UE4T0 1TB            | 4         | 4      | 0.9%    |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 5      | 0.9%    |
| Seagate ST1000LM014-1EJ164 1TB      | 4         | 4      | 0.9%    |
| SanDisk SSD PLUS 480GB              | 4         | 4      | 0.9%    |
| Samsung Electronics HM160HI 160GB   | 4         | 4      | 0.9%    |
| Kingston SA400S37480G 480GB SSD     | 4         | 4      | 0.9%    |
| HGST HCC545050A7E380 500GB          | 4         | 4      | 0.9%    |
| WDC WD7500BPKT-75PK4T0 752GB        | 3         | 3      | 0.67%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 3         | 3      | 0.67%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 3      | 0.67%   |
| WDC WD3200BPVT-00JJ5T0 320GB        | 3         | 5      | 0.67%   |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 4      | 0.67%   |
| WDC WD10SPZX-24Z10 1TB              | 3         | 3      | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 3      | 0.67%   |
| Toshiba MQ01ACF050 500GB            | 3         | 3      | 0.67%   |
| Toshiba MQ01ABD032 320GB            | 3         | 3      | 0.67%   |
| Toshiba MK5061GSYN 500GB            | 3         | 3      | 0.67%   |
| Toshiba MK3259GSXP 320GB            | 3         | 3      | 0.67%   |
| Seagate ST9500423AS 500GB           | 3         | 3      | 0.67%   |
| Seagate ST9320423AS 320GB           | 3         | 3      | 0.67%   |
| Seagate ST9250410AS 250GB           | 3         | 3      | 0.67%   |
| Seagate ST9160314AS 160GB           | 3         | 4      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 155       | 168    | 35.07%  |
| WDC                 | 80        | 89     | 18.1%   |
| Toshiba             | 68        | 74     | 15.38%  |
| Hitachi             | 27        | 29     | 6.11%   |
| Samsung Electronics | 26        | 34     | 5.88%   |
| Kingston            | 22        | 26     | 4.98%   |
| SanDisk             | 11        | 11     | 2.49%   |
| HGST                | 8         | 8      | 1.81%   |
| China               | 8         | 9      | 1.81%   |
| A-DATA Technology   | 8         | 8      | 1.81%   |
| Fujitsu             | 4         | 5      | 0.9%    |
| PNY                 | 3         | 5      | 0.68%   |
| Intel               | 3         | 3      | 0.68%   |
| WALRAM              | 2         | 2      | 0.45%   |
| LITEON              | 2         | 2      | 0.45%   |
| KingSpec            | 2         | 2      | 0.45%   |
| Crucial             | 2         | 2      | 0.45%   |
| Apple               | 2         | 2      | 0.45%   |
| XrayDisk            | 1         | 1      | 0.23%   |
| XPG                 | 1         | 1      | 0.23%   |
| SK hynix            | 1         | 1      | 0.23%   |
| ShiJi               | 1         | 1      | 0.23%   |
| OCZ                 | 1         | 1      | 0.23%   |
| Micron Technology   | 1         | 1      | 0.23%   |
| LITEONIT            | 1         | 2      | 0.23%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| ADATA Technology    | 1         | 1      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 155       | 168    | 43.18%  |
| WDC                 | 74        | 83     | 20.61%  |
| Toshiba             | 67        | 73     | 18.66%  |
| Hitachi             | 27        | 29     | 7.52%   |
| Samsung Electronics | 22        | 30     | 6.13%   |
| HGST                | 8         | 8      | 2.23%   |
| Fujitsu             | 4         | 5      | 1.11%   |
| JMicron Technology  | 1         | 1      | 0.28%   |
| Apple               | 1         | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 358       | 398    | 81.18%  |
| SSD  | 71        | 79     | 16.1%   |
| NVMe | 12        | 12     | 2.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 18.18%  |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 9.09%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 9.09%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 9.09%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 9.09%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 36.36%  |
| WDC                 | 2         | 2      | 18.18%  |
| Toshiba             | 2         | 2      | 18.18%  |
| Seagate             | 2         | 2      | 18.18%  |
| Maxtor              | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5006      | 7496   | 70.13%  |
| Works    | 1688      | 2346   | 23.65%  |
| Malfunc  | 432       | 489    | 6.05%   |
| Failed   | 11        | 11     | 0.15%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5704      | 74.7%   |
| AMD                              | 634       | 8.3%    |
| ADATA Technology                 | 312       | 4.09%   |
| SanDisk                          | 195       | 2.55%   |
| Samsung Electronics              | 135       | 1.77%   |
| Solid State Storage Technology   | 103       | 1.35%   |
| Silicon Integrated Systems [SiS] | 94        | 1.23%   |
| SK hynix                         | 86        | 1.13%   |
| Silicon Motion                   | 72        | 0.94%   |
| Phison Electronics               | 42        | 0.55%   |
| Kingston Technology Company      | 40        | 0.52%   |
| Realtek Semiconductor            | 34        | 0.45%   |
| Nvidia                           | 34        | 0.45%   |
| KIOXIA                           | 28        | 0.37%   |
| VIA Technologies                 | 24        | 0.31%   |
| Toshiba America Info Systems     | 23        | 0.3%    |
| Micron/Crucial Technology        | 20        | 0.26%   |
| Lite-On Technology               | 18        | 0.24%   |
| Micron Technology                | 10        | 0.13%   |
| Union Memory (Shenzhen)          | 6         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.08%   |
| Marvell Technology Group         | 5         | 0.07%   |
| Netac Technology                 | 3         | 0.04%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Apple                            | 2         | 0.03%   |
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
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 944       | 11.21%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 782       | 9.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 610       | 7.24%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 459       | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 443       | 5.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 369       | 4.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 300       | 3.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 293       | 3.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 233       | 2.77%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 203       | 2.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 196       | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 145       | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 134       | 1.59%   |
| ADATA Non-Volatile memory controller                                             | 132       | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 128       | 1.52%   |
| Intel Comet Lake SATA AHCI Controller                                            | 122       | 1.45%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                      | 121       | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 120       | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 118       | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                              | 116       | 1.38%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 115       | 1.37%   |
| Solid State Storage Non-Volatile memory controller                               | 103       | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                              | 97        | 1.15%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 94        | 1.12%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 93        | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 89        | 1.06%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 77        | 0.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 74        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 73        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 71        | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 68        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 65        | 0.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 62        | 0.74%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 56        | 0.67%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 56        | 0.67%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 49        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 47        | 0.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 45        | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 45        | 0.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 35        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5688      | 70.22%  |
| NVMe | 1330      | 16.42%  |
| IDE  | 549       | 6.78%   |
| RAID | 533       | 6.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 6156      | 90.03%  |
| AMD    | 680       | 9.94%   |
| ARM    | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 242       | 3.54%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 160       | 2.34%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 144       | 2.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 129       | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 126       | 1.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 125       | 1.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 121       | 1.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 120       | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 117       | 1.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 108       | 1.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 98        | 1.43%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 91        | 1.33%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 89        | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 87        | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 87        | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 86        | 1.26%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 84        | 1.23%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 84        | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 80        | 1.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 79        | 1.15%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 78        | 1.14%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 77        | 1.13%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 75        | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 72        | 1.05%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 72        | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 71        | 1.04%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 64        | 0.94%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 64        | 0.94%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 64        | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 61        | 0.89%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 61        | 0.89%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 61        | 0.89%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 57        | 0.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 56        | 0.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 55        | 0.8%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 55        | 0.8%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 54        | 0.79%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 54        | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 54        | 0.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 53        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2020      | 29.54%  |
| Intel Core i7                  | 1397      | 20.43%  |
| Intel Core i3                  | 1073      | 15.69%  |
| Intel Celeron                  | 513       | 7.5%    |
| Intel Core 2 Duo               | 260       | 3.8%    |
| Intel Atom                     | 246       | 3.6%    |
| Other                          | 228       | 3.33%   |
| AMD Ryzen 5                    | 172       | 2.51%   |
| AMD Ryzen 7                    | 154       | 2.25%   |
| Intel Pentium Dual-Core        | 135       | 1.97%   |
| Intel Pentium                  | 130       | 1.9%    |
| Intel Pentium Dual             | 72        | 1.05%   |
| AMD E                          | 47        | 0.69%   |
| AMD C-60                       | 37        | 0.54%   |
| AMD E1                         | 32        | 0.47%   |
| AMD A4                         | 27        | 0.39%   |
| Intel Genuine                  | 26        | 0.38%   |
| AMD A6                         | 25        | 0.37%   |
| AMD C-70                       | 22        | 0.32%   |
| AMD A10                        | 21        | 0.31%   |
| Intel Core 2                   | 19        | 0.28%   |
| Intel Celeron Dual-Core        | 16        | 0.23%   |
| AMD C-50                       | 15        | 0.22%   |
| AMD A12                        | 14        | 0.2%    |
| AMD Ryzen 3                    | 12        | 0.18%   |
| AMD Mobile Sempron             | 12        | 0.18%   |
| Intel Celeron M                | 11        | 0.16%   |
| AMD Athlon II                  | 9         | 0.13%   |
| AMD Ryzen 9                    | 8         | 0.12%   |
| AMD Turion X2 Dual-Core Mobile | 6         | 0.09%   |
| AMD Turion 64 Mobile           | 6         | 0.09%   |
| AMD Turion II                  | 5         | 0.07%   |
| AMD Turion 64 X2 Mobile        | 5         | 0.07%   |
| AMD Phenom II                  | 5         | 0.07%   |
| Intel Pentium M                | 4         | 0.06%   |
| Intel Pentium Gold             | 4         | 0.06%   |
| AMD Ryzen 7 PRO                | 4         | 0.06%   |
| AMD Athlon 64 X2               | 4         | 0.06%   |
| AMD A8                         | 4         | 0.06%   |
| AMD V120                       | 3         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4360      | 63.74%  |
| 4       | 1912      | 27.95%  |
| 6       | 273       | 3.99%   |
| 1       | 145       | 2.12%   |
| 8       | 129       | 1.89%   |
| 14      | 7         | 0.1%    |
| 12      | 5         | 0.07%   |
| Unknown | 3         | 0.04%   |
| 10      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 3       | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6838      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5152      | 75.31%  |
| 1       | 1685      | 24.63%  |
| Unknown | 3         | 0.04%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6520      | 94.84%  |
| Unknown        | 295       | 4.29%   |
| 32-bit         | 45        | 0.65%   |
| 64-bit         | 15        | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1295      | 18.31%  |
| 0x306a9    | 590       | 8.34%   |
| 0x206a7    | 579       | 8.18%   |
| 0x806e9    | 380       | 5.37%   |
| 0x40651    | 333       | 4.71%   |
| 0x806ec    | 310       | 4.38%   |
| 0x906ea    | 292       | 4.13%   |
| 0x20655    | 290       | 4.1%    |
| 0x306d4    | 269       | 3.8%    |
| 0x406e3    | 265       | 3.75%   |
| 0x1067a    | 255       | 3.6%    |
| 0x806ea    | 245       | 3.46%   |
| 0x806c1    | 155       | 2.19%   |
| 0x406c4    | 153       | 2.16%   |
| 0x6fd      | 145       | 2.05%   |
| 0x05000119 | 85        | 1.2%    |
| 0x906e9    | 82        | 1.16%   |
| 0x30678    | 82        | 1.16%   |
| 0x08600103 | 79        | 1.12%   |
| 0x08108109 | 76        | 1.07%   |
| 0x706e5    | 69        | 0.98%   |
| 0x08108102 | 61        | 0.86%   |
| 0x906ed    | 58        | 0.82%   |
| 0x706a1    | 58        | 0.82%   |
| 0x306c3    | 56        | 0.79%   |
| 0x406c3    | 51        | 0.72%   |
| 0x706a8    | 50        | 0.71%   |
| 0x806eb    | 48        | 0.68%   |
| 0x20652    | 48        | 0.68%   |
| 0xa0652    | 47        | 0.66%   |
| 0x106ca    | 46        | 0.65%   |
| 0x30661    | 32        | 0.45%   |
| 0x10676    | 32        | 0.45%   |
| 0x03000027 | 28        | 0.4%    |
| 0x506c9    | 27        | 0.38%   |
| 0x05000029 | 27        | 0.38%   |
| 0x506e3    | 24        | 0.34%   |
| 0x10661    | 24        | 0.34%   |
| 0x0810100b | 21        | 0.3%    |
| 0x0600611a | 21        | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1691      | 24.73%  |
| IvyBridge        | 703       | 10.28%  |
| SandyBridge      | 676       | 9.88%   |
| Haswell          | 456       | 6.67%   |
| Westmere         | 398       | 5.82%   |
| Silvermont       | 340       | 4.97%   |
| Skylake          | 339       | 4.96%   |
| Penryn           | 336       | 4.91%   |
| Broadwell        | 310       | 4.53%   |
| Core             | 221       | 3.23%   |
| TigerLake        | 193       | 2.82%   |
| Zen+             | 173       | 2.53%   |
| Bobcat           | 142       | 2.08%   |
| Goldmont plus    | 121       | 1.77%   |
| IceLake          | 100       | 1.46%   |
| Bonnell          | 96        | 1.4%    |
| Zen 2            | 87        | 1.27%   |
| CometLake        | 78        | 1.14%   |
| Unknown          | 64        | 0.94%   |
| Excavator        | 40        | 0.58%   |
| K8 Hammer        | 39        | 0.57%   |
| Goldmont         | 33        | 0.48%   |
| K10 Llano        | 32        | 0.47%   |
| Zen              | 29        | 0.42%   |
| K10              | 28        | 0.41%   |
| P6               | 24        | 0.35%   |
| Jaguar           | 21        | 0.31%   |
| Zen 3            | 20        | 0.29%   |
| Nehalem          | 12        | 0.18%   |
| K8 & K10 hybrid  | 11        | 0.16%   |
| Alderlake Hybrid | 11        | 0.16%   |
| Piledriver       | 8         | 0.12%   |
| Puma             | 4         | 0.06%   |
| Steamroller      | 2         | 0.03%   |
| NetBurst         | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5901      | 66.51%  |
| Nvidia                           | 1785      | 20.12%  |
| AMD                              | 1069      | 12.05%  |
| Silicon Integrated Systems [SiS] | 94        | 1.06%   |
| VIA Technologies                 | 24        | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 694       | 7.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 665       | 7.3%    |
| Intel HD Graphics 620                                                                    | 475       | 5.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 386       | 4.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 373       | 4.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 371       | 4.07%   |
| Intel HD Graphics 5500                                                                   | 291       | 3.19%   |
| Intel UHD Graphics 620                                                                   | 280       | 3.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 276       | 3.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 271       | 2.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 262       | 2.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 247       | 2.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 240       | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 172       | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 161       | 1.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 160       | 1.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 141       | 1.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 131       | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 131       | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 121       | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 100       | 1.1%    |
| Intel HD Graphics 630                                                                    | 97        | 1.06%   |
| Nvidia GP108M [GeForce MX150]                                                            | 95        | 1.04%   |
| Nvidia TU117M                                                                            | 93        | 1.02%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 91        | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 90        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 87        | 0.95%   |
| Nvidia GM108M [GeForce MX110]                                                            | 87        | 0.95%   |
| AMD Renoir                                                                               | 86        | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 83        | 0.91%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 75        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 68        | 0.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 67        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 57        | 0.63%   |
| Nvidia GP108M [GeForce MX250]                                                            | 54        | 0.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 50        | 0.55%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 44        | 0.48%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 43        | 0.47%   |
| Nvidia GP108M [GeForce MX230]                                                            | 42        | 0.46%   |
| AMD Lucienne                                                                             | 41        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 4006      | 58.5%   |
| Intel + Nvidia | 1522      | 22.23%  |
| 1 x AMD        | 484       | 7.07%   |
| Intel + AMD    | 372       | 5.43%   |
| AMD + Nvidia   | 140       | 2.04%   |
| 1 x Nvidia     | 122       | 1.78%   |
| 1 x SiS        | 94        | 1.37%   |
| 2 x AMD        | 72        | 1.05%   |
| 1 x VIA        | 24        | 0.35%   |
| 2 x Intel      | 8         | 0.12%   |
| Other          | 4         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5577      | 80.79%  |
| Proprietary | 1122      | 16.25%  |
| Unknown     | 204       | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4842      | 69.43%  |
| 1.01-2.0   | 1002      | 14.37%  |
| 0.01-0.5   | 506       | 7.26%   |
| 3.01-4.0   | 363       | 5.21%   |
| 0.51-1.0   | 170       | 2.44%   |
| 5.01-6.0   | 64        | 0.92%   |
| 2.01-3.0   | 15        | 0.22%   |
| 7.01-8.0   | 11        | 0.16%   |
| 8.01-16.0  | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1502      | 19.16%  |
| BOE                     | 1449      | 18.48%  |
| Chimei Innolux          | 1126      | 14.36%  |
| LG Display              | 1085      | 13.84%  |
| Samsung Electronics     | 794       | 10.13%  |
| Goldstar                | 409       | 5.22%   |
| AOC                     | 160       | 2.04%   |
| Dell                    | 156       | 1.99%   |
| Chi Mei Optoelectronics | 152       | 1.94%   |
| InfoVision              | 118       | 1.51%   |
| PANDA                   | 109       | 1.39%   |
| Philips                 | 91        | 1.16%   |
| Apple                   | 81        | 1.03%   |
| Lenovo                  | 57        | 0.73%   |
| Acer                    | 50        | 0.64%   |
| HannStar                | 47        | 0.6%    |
| CPT                     | 47        | 0.6%    |
| LG Philips              | 35        | 0.45%   |
| Sony                    | 32        | 0.41%   |
| InnoLux Display         | 28        | 0.36%   |
| Hewlett-Packard         | 28        | 0.36%   |
| SLD                     | 27        | 0.34%   |
| Sharp                   | 21        | 0.27%   |
| MTD                     | 18        | 0.23%   |
| KDC                     | 14        | 0.18%   |
| Panasonic               | 13        | 0.17%   |
| Toshiba                 | 10        | 0.13%   |
| BenQ                    | 10        | 0.13%   |
| STA                     | 9         | 0.11%   |
| SKY                     | 9         | 0.11%   |
| ASUSTek Computer        | 9         | 0.11%   |
| Unknown                 | 8         | 0.1%    |
| NCS                     | 7         | 0.09%   |
| GDH                     | 7         | 0.09%   |
| RTK                     | 6         | 0.08%   |
| MStar                   | 6         | 0.08%   |
| ITE                     | 6         | 0.08%   |
| HB@                     | 6         | 0.08%   |
| AGO                     | 6         | 0.08%   |
| Unknown (XXX)           | 5         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 118       | 1.5%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 114       | 1.45%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 108       | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 102       | 1.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 101       | 1.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 98        | 1.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 96        | 1.22%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 96        | 1.22%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 79        | 1%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 74        | 0.94%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 73        | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 71        | 0.9%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 66        | 0.84%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 66        | 0.84%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 64        | 0.81%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 63        | 0.8%    |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 62        | 0.79%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 57        | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 57        | 0.72%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 55        | 0.7%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.68%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 54        | 0.68%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 52        | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 51        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 50        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 49        | 0.62%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 44        | 0.56%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 44        | 0.56%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 43        | 0.55%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 42        | 0.53%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 42        | 0.53%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 41        | 0.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 41        | 0.52%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 41        | 0.52%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 41        | 0.52%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 37        | 0.47%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 37        | 0.47%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 36        | 0.46%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 36        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 35        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4138      | 55.29%  |
| 1920x1080 (FHD)    | 2182      | 29.16%  |
| 1280x800 (WXGA)    | 290       | 3.87%   |
| 1600x900 (HD+)     | 163       | 2.18%   |
| 2560x1080          | 149       | 1.99%   |
| 3840x2160 (4K)     | 97        | 1.3%    |
| 1440x900 (WXGA+)   | 92        | 1.23%   |
| 1360x768           | 70        | 0.94%   |
| 2560x1440 (QHD)    | 46        | 0.61%   |
| 1920x1200 (WUXGA)  | 45        | 0.6%    |
| 1024x600           | 40        | 0.53%   |
| 1280x1024 (SXGA)   | 31        | 0.41%   |
| 1680x1050 (WSXGA+) | 28        | 0.37%   |
| 1024x768 (XGA)     | 21        | 0.28%   |
| 1920x540           | 17        | 0.23%   |
| 1280x720 (HD)      | 10        | 0.13%   |
| 2560x1600          | 8         | 0.11%   |
| 2288x1287          | 8         | 0.11%   |
| Unknown            | 8         | 0.11%   |
| 2880x1800          | 4         | 0.05%   |
| 3840x2400          | 3         | 0.04%   |
| 3840x1080          | 3         | 0.04%   |
| 3440x1440          | 3         | 0.04%   |
| 3200x1800 (QHD+)   | 3         | 0.04%   |
| 1280x960           | 3         | 0.04%   |
| 800x1280           | 2         | 0.03%   |
| 1024x576           | 2         | 0.03%   |
| 4240x1080          | 1         | 0.01%   |
| 3926x1080          | 1         | 0.01%   |
| 3600x1080          | 1         | 0.01%   |
| 3286x1080          | 1         | 0.01%   |
| 3200x2000          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |
| 2304x1440          | 1         | 0.01%   |
| 2256x1504          | 1         | 0.01%   |
| 2160x1440          | 1         | 0.01%   |
| 2160x1350          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3409      | 43.54%  |
| 14      | 1457      | 18.61%  |
| 13      | 1264      | 16.14%  |
| 21      | 223       | 2.85%   |
| 23      | 208       | 2.66%   |
| 17      | 172       | 2.2%    |
| 18      | 158       | 2.02%   |
| 34      | 138       | 1.76%   |
| 11      | 108       | 1.38%   |
| 24      | 107       | 1.37%   |
| 27      | 92        | 1.17%   |
| 12      | 54        | 0.69%   |
| 31      | 52        | 0.66%   |
| Unknown | 48        | 0.61%   |
| 20      | 47        | 0.6%    |
| 19      | 47        | 0.6%    |
| 10      | 45        | 0.57%   |
| 40      | 28        | 0.36%   |
| 28      | 19        | 0.24%   |
| 72      | 18        | 0.23%   |
| 32      | 18        | 0.23%   |
| 22      | 16        | 0.2%    |
| 84      | 15        | 0.19%   |
| 54      | 14        | 0.18%   |
| 52      | 14        | 0.18%   |
| 16      | 14        | 0.18%   |
| 47      | 7         | 0.09%   |
| 46      | 7         | 0.09%   |
| 37      | 7         | 0.09%   |
| 26      | 5         | 0.06%   |
| 58      | 3         | 0.04%   |
| 48      | 3         | 0.04%   |
| 65      | 2         | 0.03%   |
| 7       | 2         | 0.03%   |
| 142     | 1         | 0.01%   |
| 60      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |
| 55      | 1         | 0.01%   |
| 49      | 1         | 0.01%   |
| 42      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5830      | 75.06%  |
| 401-500        | 484       | 6.23%   |
| 501-600        | 392       | 5.05%   |
| 201-300        | 385       | 4.96%   |
| 351-400        | 266       | 3.42%   |
| 701-800        | 156       | 2.01%   |
| 601-700        | 78        | 1%      |
| 1001-1500      | 54        | 0.7%    |
| Unknown        | 48        | 0.62%   |
| 801-900        | 36        | 0.46%   |
| 1501-2000      | 33        | 0.42%   |
| 901-1000       | 2         | 0.03%   |
| 1-100          | 2         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6128      | 89.07%  |
| 16/10   | 486       | 7.06%   |
| 21/9    | 153       | 2.22%   |
| 4/3     | 40        | 0.58%   |
| 5/4     | 31        | 0.45%   |
| Unknown | 23        | 0.33%   |
| 3/2     | 13        | 0.19%   |
| 32/9    | 3         | 0.04%   |
| 0.67    | 2         | 0.03%   |
| 1.00    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3390      | 43.35%  |
| 81-90          | 2584      | 33.04%  |
| 201-250        | 477       | 6.1%    |
| 351-500        | 212       | 2.71%   |
| 151-200        | 165       | 2.11%   |
| 141-150        | 165       | 2.11%   |
| 71-80          | 133       | 1.7%    |
| 121-130        | 123       | 1.57%   |
| 51-60          | 108       | 1.38%   |
| 301-350        | 94        | 1.2%    |
| More than 1000 | 72        | 0.92%   |
| 501-1000       | 54        | 0.69%   |
| Unknown        | 48        | 0.61%   |
| 41-50          | 45        | 0.58%   |
| 61-70          | 41        | 0.52%   |
| 251-300        | 36        | 0.46%   |
| 91-100         | 34        | 0.43%   |
| 131-140        | 26        | 0.33%   |
| 111-120        | 11        | 0.14%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 4262      | 55.76%  |
| 121-160       | 1938      | 25.35%  |
| 51-100        | 1162      | 15.2%   |
| 1-50          | 108       | 1.41%   |
| 161-240       | 106       | 1.39%   |
| Unknown       | 48        | 0.63%   |
| More than 240 | 20        | 0.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5520      | 78.77%  |
| 2     | 1234      | 17.61%  |
| 0     | 194       | 2.77%   |
| 3     | 58        | 0.83%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4977      | 41.51%  |
| Qualcomm Atheros                  | 3047      | 25.41%  |
| Intel                             | 2136      | 17.81%  |
| Broadcom                          | 660       | 5.5%    |
| JMicron Technology                | 189       | 1.58%   |
| Marvell Technology Group          | 179       | 1.49%   |
| Broadcom Limited                  | 144       | 1.2%    |
| Ralink                            | 126       | 1.05%   |
| Silicon Integrated Systems [SiS]  | 94        | 0.78%   |
| Ralink Technology                 | 82        | 0.68%   |
| TP-Link                           | 53        | 0.44%   |
| Samsung Electronics               | 45        | 0.38%   |
| Motorola PCS                      | 30        | 0.25%   |
| ASIX Electronics                  | 26        | 0.22%   |
| VIA Technologies                  | 24        | 0.2%    |
| Nvidia                            | 24        | 0.2%    |
| Qualcomm Atheros Communications   | 23        | 0.19%   |
| Xiaomi                            | 22        | 0.18%   |
| D-Link                            | 15        | 0.13%   |
| MediaTek                          | 13        | 0.11%   |
| ICS Advent                        | 10        | 0.08%   |
| D-Link System                     | 9         | 0.08%   |
| DisplayLink                       | 6         | 0.05%   |
| Lenovo                            | 5         | 0.04%   |
| LG Electronics                    | 4         | 0.03%   |
| Huawei Technologies               | 4         | 0.03%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Qualcomm                          | 3         | 0.03%   |
| Edimax Technology                 | 3         | 0.03%   |
| Dell                              | 3         | 0.03%   |
| AMD                               | 3         | 0.03%   |
| OPPO                              | 2         | 0.02%   |
| NetGear                           | 2         | 0.02%   |
| Microsoft                         | 2         | 0.02%   |
| Micro Star International          | 2         | 0.02%   |
| ASUSTek Computer                  | 2         | 0.02%   |
| Arduino SA                        | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| Spreadtrum Communications         | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2904      | 22.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1360      | 10.35%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 810       | 6.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 730       | 5.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 562       | 4.28%   |
| Intel Wi-Fi 6 AX200                                               | 307       | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 296       | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 285       | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 284       | 2.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 207       | 1.57%   |
| Intel Wi-Fi 6 AX201                                               | 181       | 1.38%   |
| Intel Wireless 7265                                               | 155       | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 153       | 1.16%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 139       | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 129       | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 116       | 0.88%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 100       | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 98        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 97        | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 96        | 0.73%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 91        | 0.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 85        | 0.65%   |
| Intel Wireless 7260                                               | 81        | 0.62%   |
| Intel Wireless 3165                                               | 80        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 77        | 0.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 77        | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 76        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 75        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 73        | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 69        | 0.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 64        | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 62        | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 61        | 0.46%   |
| Intel Centrino Advanced-N 6235                                    | 61        | 0.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 58        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 58        | 0.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 58        | 0.44%   |
| Intel Wireless 3160                                               | 58        | 0.44%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 56        | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 56        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 2868      | 41.79%  |
| Intel                                 | 2084      | 30.37%  |
| Realtek Semiconductor                 | 1023      | 14.91%  |
| Broadcom                              | 470       | 6.85%   |
| Ralink                                | 126       | 1.84%   |
| Broadcom Limited                      | 91        | 1.33%   |
| Ralink Technology                     | 82        | 1.19%   |
| TP-Link                               | 42        | 0.61%   |
| Qualcomm Atheros Communications       | 23        | 0.34%   |
| D-Link                                | 15        | 0.22%   |
| MediaTek                              | 11        | 0.16%   |
| D-Link System                         | 9         | 0.13%   |
| Edimax Technology                     | 3         | 0.04%   |
| NetGear                               | 2         | 0.03%   |
| Microsoft                             | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Dell                                  | 2         | 0.03%   |
| Sierra Wireless                       | 1         | 0.01%   |
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
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 810       | 11.74%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 730       | 10.58%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 562       | 8.14%   |
| Intel Wi-Fi 6 AX200                                                     | 307       | 4.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 296       | 4.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 285       | 4.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 284       | 4.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 207       | 3%      |
| Intel Wi-Fi 6 AX201                                                     | 181       | 2.62%   |
| Intel Wireless 7265                                                     | 155       | 2.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 153       | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 129       | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 116       | 1.68%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 100       | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 96        | 1.39%   |
| Intel Wireless 7260                                                     | 81        | 1.17%   |
| Intel Wireless 3165                                                     | 80        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 77        | 1.12%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 77        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 75        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 64        | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 62        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 61        | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 61        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 58        | 0.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 58        | 0.84%   |
| Intel Wireless 3160                                                     | 58        | 0.84%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 56        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 56        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 54        | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 52        | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 51        | 0.74%   |
| Ralink MT7601U Wireless Adapter                                         | 50        | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 49        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 47        | 0.68%   |
| Intel Wireless 8265 / 8275                                              | 47        | 0.68%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 44        | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 41        | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 40        | 0.58%   |
| Intel WiFi Link 5100                                                    | 37        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4468      | 72.36%  |
| Qualcomm Atheros                 | 400       | 6.48%   |
| Intel                            | 313       | 5.07%   |
| Broadcom                         | 260       | 4.21%   |
| JMicron Technology               | 189       | 3.06%   |
| Marvell Technology Group         | 179       | 2.9%    |
| Silicon Integrated Systems [SiS] | 94        | 1.52%   |
| Broadcom Limited                 | 59        | 0.96%   |
| Samsung Electronics              | 45        | 0.73%   |
| ASIX Electronics                 | 26        | 0.42%   |
| VIA Technologies                 | 24        | 0.39%   |
| Nvidia                           | 23        | 0.37%   |
| Motorola PCS                     | 23        | 0.37%   |
| Xiaomi                           | 22        | 0.36%   |
| TP-Link                          | 11        | 0.18%   |
| ICS Advent                       | 10        | 0.16%   |
| DisplayLink                      | 6         | 0.1%    |
| Lenovo                           | 5         | 0.08%   |
| Attansic Technology              | 4         | 0.06%   |
| Qualcomm                         | 3         | 0.05%   |
| OPPO                             | 2         | 0.03%   |
| LG Electronics                   | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| Spreadtrum Communications        | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| MediaTek                         | 1         | 0.02%   |
| Huawei Technologies              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2904      | 46.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1360      | 21.9%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 139       | 2.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 98        | 1.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 97        | 1.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 91        | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 85        | 1.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 76        | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 73        | 1.18%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 69        | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 58        | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 56        | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 50        | 0.81%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 50        | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 42        | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 38        | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 36        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 31        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 30        | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                                          | 30        | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 28        | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 28        | 0.45%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 26        | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                              | 25        | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 24        | 0.39%   |
| Motorola PCS moto g(8) plus                                                    | 23        | 0.37%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 23        | 0.37%   |
| Intel 82577LM Gigabit Network Connection                                       | 22        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 21        | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 21        | 0.34%   |
| Intel Ethernet Connection I219-LM                                              | 21        | 0.34%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 21        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 20        | 0.32%   |
| Intel Ethernet Connection I218-LM                                              | 19        | 0.31%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 17        | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 17        | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 17        | 0.27%   |
| Intel Ethernet Connection I217-LM                                              | 16        | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 15        | 0.24%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 15        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6628      | 52.07%  |
| Ethernet | 6068      | 47.67%  |
| Modem    | 24        | 0.19%   |
| Unknown  | 10        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5727      | 79.69%  |
| Ethernet | 1459      | 20.3%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5718      | 83.46%  |
| 1     | 895       | 13.06%  |
| 0     | 228       | 3.33%   |
| 3     | 10        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5427      | 77.4%   |
| Yes  | 1585      | 22.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1761      | 35.8%   |
| Qualcomm Atheros Communications | 1443      | 29.34%  |
| Lite-On Technology              | 638       | 12.97%  |
| Broadcom                        | 200       | 4.07%   |
| Realtek Semiconductor           | 163       | 3.31%   |
| IMC Networks                    | 122       | 2.48%   |
| Foxconn / Hon Hai               | 116       | 2.36%   |
| Cambridge Silicon Radio         | 89        | 1.81%   |
| Apple                           | 81        | 1.65%   |
| Dell                            | 77        | 1.57%   |
| Hewlett-Packard                 | 53        | 1.08%   |
| Ralink                          | 47        | 0.96%   |
| Unknown                         | 39        | 0.79%   |
| Qcom                            | 25        | 0.51%   |
| Ralink Technology               | 16        | 0.33%   |
| Alps Electric                   | 13        | 0.26%   |
| Foxconn International           | 12        | 0.24%   |
| Askey Computer                  | 8         | 0.16%   |
| Toshiba                         | 4         | 0.08%   |
| ASUSTek Computer                | 4         | 0.08%   |
| Opticis                         | 3         | 0.06%   |
| Micro Star International        | 3         | 0.06%   |
| Syntek                          | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 825       | 16.77%  |
| Intel Bluetooth wireless interface                                                  | 579       | 11.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 484       | 9.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 363       | 7.38%   |
| Intel AX200 Bluetooth                                                               | 303       | 6.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 233       | 4.74%   |
| Intel AX201 Bluetooth                                                               | 175       | 3.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 130       | 2.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 125       | 2.54%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 117       | 2.38%   |
| Realtek Bluetooth Radio                                                             | 107       | 2.18%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 91        | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 89        | 1.81%   |
| Lite-On Bluetooth Device                                                            | 85        | 1.73%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 85        | 1.73%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 63        | 1.28%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 59        | 1.2%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 56        | 1.14%   |
| IMC Networks Bluetooth Radio                                                        | 55        | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 53        | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 52        | 1.06%   |
| Ralink RT3290 Bluetooth                                                             | 47        | 0.96%   |
| Unknown Bluetooth Device                                                            | 39        | 0.79%   |
| Apple Bluetooth Host Controller                                                     | 36        | 0.73%   |
| Dell Wireless 365 Bluetooth                                                         | 33        | 0.67%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 31        | 0.63%   |
| IMC Networks Bluetooth Device                                                       | 30        | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 27        | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 27        | 0.55%   |
| Apple Bluetooth USB Host Controller                                                 | 27        | 0.55%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.49%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 20        | 0.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 19        | 0.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 19        | 0.39%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 17        | 0.35%   |
| Dell DW375 Bluetooth Module                                                         | 17        | 0.35%   |
| Realtek RTL8723A Bluetooth                                                          | 15        | 0.3%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 15        | 0.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 15        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 5871      | 74.55%  |
| Nvidia                                          | 851       | 10.81%  |
| AMD                                             | 711       | 9.03%   |
| Silicon Integrated Systems [SiS]                | 94        | 1.19%   |
| C-Media Electronics                             | 67        | 0.85%   |
| Generalplus Technology                          | 42        | 0.53%   |
| Logitech                                        | 41        | 0.52%   |
| VIA Technologies                                | 24        | 0.3%    |
| Kingston Technology                             | 19        | 0.24%   |
| JMTek                                           | 18        | 0.23%   |
| Texas Instruments                               | 12        | 0.15%   |
| Corsair                                         | 11        | 0.14%   |
| Plantronics                                     | 10        | 0.13%   |
| Realtek Semiconductor                           | 9         | 0.11%   |
| Microsoft                                       | 9         | 0.11%   |
| GN Netcom                                       | 9         | 0.11%   |
| Samsung Electronics                             | 6         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.08%   |
| Sony                                            | 5         | 0.06%   |
| Samson Technologies                             | 4         | 0.05%   |
| JBL                                             | 4         | 0.05%   |
| SteelSeries ApS                                 | 3         | 0.04%   |
| Razer USA                                       | 3         | 0.04%   |
| Meizu                                           | 3         | 0.04%   |
| Lenovo                                          | 3         | 0.04%   |
| Goldvish                                        | 3         | 0.04%   |
| Dell                                            | 3         | 0.04%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Tdlasunnic                                      | 2         | 0.03%   |
| M-Audio                                         | 2         | 0.03%   |
| Jieli Technology                                | 2         | 0.03%   |
| Focusrite-Novation                              | 2         | 0.03%   |
| BY EDIFIER                                      | 2         | 0.03%   |
| BEHRINGER International                         | 2         | 0.03%   |
| Astro Gaming                                    | 2         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.01%   |
| Winbond Electronics                             | 1         | 0.01%   |
| Unknown (ABC)                                   | 1         | 0.01%   |
| Tenx Technology                                 | 1         | 0.01%   |
| Syntek                                          | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1074      | 11.69%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 907       | 9.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 472       | 5.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 409       | 4.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 387       | 4.21%   |
| Intel 8 Series HD Audio Controller                                                                | 386       | 4.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 382       | 4.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 347       | 3.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 322       | 3.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 309       | 3.36%   |
| Intel Broadwell-U Audio Controller                                                                | 309       | 3.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 280       | 3.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 266       | 2.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 197       | 2.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 192       | 2.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 178       | 1.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 151       | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 145       | 1.58%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 142       | 1.55%   |
| AMD Wrestler HDMI Audio                                                                           | 134       | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 121       | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 120       | 1.31%   |
| AMD FCH Azalia Controller                                                                         | 114       | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 100       | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 98        | 1.07%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 91        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 91        | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 84        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 80        | 0.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 71        | 0.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 66        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 61        | 0.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 60        | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 56        | 0.61%   |
| Generalplus Technology USB Audio Device                                                           | 42        | 0.46%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 40        | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 39        | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 38        | 0.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 0.36%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 32        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 509       | 19.1%   |
| Samsung Electronics | 358       | 13.43%  |
| Unknown             | 260       | 9.76%   |
| Kingston            | 248       | 9.31%   |
| SK hynix            | 247       | 9.27%   |
| A-DATA Technology   | 208       | 7.8%    |
| Teikon              | 140       | 5.25%   |
| Micron Technology   | 114       | 4.28%   |
| Smart Brazil        | 104       | 3.9%    |
| Crucial             | 67        | 2.51%   |
| Corsair             | 62        | 2.33%   |
| High Bridge         | 59        | 2.21%   |
| Elpida              | 43        | 1.61%   |
| Unknown (ABCD)      | 26        | 0.98%   |
| Multilaser          | 23        | 0.86%   |
| Apacer              | 18        | 0.68%   |
| Unknown             | 18        | 0.68%   |
| Nanya Technology    | 16        | 0.6%    |
| Kllisre             | 13        | 0.49%   |
| Patriot             | 12        | 0.45%   |
| Ramaxel Technology  | 11        | 0.41%   |
| HT Micron           | 11        | 0.41%   |
| PUSKILL             | 7         | 0.26%   |
| Smart Modular       | 5         | 0.19%   |
| Avant               | 5         | 0.19%   |
| Unknown (0x0B5E)    | 4         | 0.15%   |
| Team                | 4         | 0.15%   |
| RZX                 | 4         | 0.15%   |
| Carry               | 4         | 0.15%   |
| Atermiter           | 4         | 0.15%   |
| Super Talent        | 3         | 0.11%   |
| Kreton              | 3         | 0.11%   |
| Kingmax             | 3         | 0.11%   |
| HBS                 | 3         | 0.11%   |
| G.Skill             | 3         | 0.11%   |
| Walton Chaintech    | 2         | 0.08%   |
| Unknown (8A02)      | 2         | 0.08%   |
| Unknown (898F)      | 2         | 0.08%   |
| Unknown (0xAD0A)    | 2         | 0.08%   |
| Transcend           | 2         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 75        | 2.59%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 49        | 1.69%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 45        | 1.55%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 41        | 1.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 41        | 1.42%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 39        | 1.35%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 35        | 1.21%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 34        | 1.17%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 33        | 1.14%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 30        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 26        | 0.9%    |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 25        | 0.86%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.83%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 23        | 0.79%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 22        | 0.76%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 21        | 0.73%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 20        | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.69%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 19        | 0.66%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 19        | 0.66%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 18        | 0.62%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 18        | 0.62%   |
| Unknown                                                          | 18        | 0.62%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 17        | 0.59%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 17        | 0.59%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s         | 17        | 0.59%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 16        | 0.55%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 16        | 0.55%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 15        | 0.52%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 15        | 0.52%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 14        | 0.48%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 14        | 0.48%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 14        | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 13        | 0.45%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 13        | 0.45%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s           | 13        | 0.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.45%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s             | 13        | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.41%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1023      | 46.33%  |
| DDR4    | 851       | 38.54%  |
| DDR2    | 137       | 6.2%    |
| SDRAM   | 62        | 2.81%   |
| LPDDR4  | 59        | 2.67%   |
| LPDDR3  | 27        | 1.22%   |
| DRAM    | 18        | 0.82%   |
| DDR     | 12        | 0.54%   |
| DDR5    | 8         | 0.36%   |
| Unknown | 7         | 0.32%   |
| LPDDR5  | 3         | 0.14%   |
| RAM     | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2098      | 95.49%  |
| Row Of Chips | 79        | 3.6%    |
| Unknown      | 10        | 0.46%   |
| DIMM         | 8         | 0.36%   |
| Chip         | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1016      | 40.21%  |
| 8192  | 654       | 25.88%  |
| 2048  | 518       | 20.5%   |
| 16384 | 229       | 9.06%   |
| 1024  | 82        | 3.24%   |
| 32768 | 23        | 0.91%   |
| 512   | 5         | 0.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 646       | 25.94%  |
| 2667    | 474       | 19.04%  |
| 2400    | 285       | 11.45%  |
| 1334    | 216       | 8.67%   |
| 1333    | 184       | 7.39%   |
| 3200    | 152       | 6.1%    |
| Unknown | 89        | 3.57%   |
| 2133    | 80        | 3.21%   |
| 800     | 56        | 2.25%   |
| 667     | 51        | 2.05%   |
| 1066    | 40        | 1.61%   |
| 4199    | 38        | 1.53%   |
| 1067    | 38        | 1.53%   |
| 4267    | 23        | 0.92%   |
| 533     | 22        | 0.88%   |
| 975     | 21        | 0.84%   |
| 2048    | 19        | 0.76%   |
| 3266    | 9         | 0.36%   |
| 1867    | 9         | 0.36%   |
| 4800    | 8         | 0.32%   |
| 8400    | 6         | 0.24%   |
| 1200    | 4         | 0.16%   |
| 6400    | 3         | 0.12%   |
| 3733    | 3         | 0.12%   |
| 400     | 2         | 0.08%   |
| 3466    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 2933    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 1866    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1400    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 2       | 1         | 0.04%   |
| 1       | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 39.29%  |
| Seiko Epson         | 20        | 35.71%  |
| Samsung Electronics | 5         | 8.93%   |
| Canon               | 5         | 8.93%   |
| Brother Industries  | 2         | 3.57%   |
| Xerox               | 1         | 1.79%   |
| MIIIW               | 1         | 1.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 7         | 12.5%   |
| HP LaserJet 1020                             | 3         | 5.36%   |
| HP DeskJet 2700 series                       | 3         | 5.36%   |
| Seiko Epson L396 Series                      | 2         | 3.57%   |
| Seiko Epson L355 Series                      | 2         | 3.57%   |
| Seiko Epson ET-3750 Series                   | 2         | 3.57%   |
| Samsung M2020 Series                         | 2         | 3.57%   |
| HP LaserJet Professional P1102w              | 2         | 3.57%   |
| HP Ink Tank Wireless 410 series              | 2         | 3.57%   |
| HP Deskjet 3050 J610 series                  | 2         | 3.57%   |
| HP Deskjet 2540 series                       | 2         | 3.57%   |
| Canon G3000 series                           | 2         | 3.57%   |
| Xerox Phaser 3040                            | 1         | 1.79%   |
| Seiko Epson XP-230 Series                    | 1         | 1.79%   |
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 1.79%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.79%   |
| Seiko Epson L805 Series                      | 1         | 1.79%   |
| Seiko Epson L380 Series                      | 1         | 1.79%   |
| Seiko Epson L220 Series                      | 1         | 1.79%   |
| Seiko Epson ET-2700 Series                   | 1         | 1.79%   |
| Samsung SCX-4623 Series                      | 1         | 1.79%   |
| Samsung SCX-4200 series                      | 1         | 1.79%   |
| Samsung M332x 382x 402x Series               | 1         | 1.79%   |
| MIIIW MW Keyboard Air Mini                   | 1         | 1.79%   |
| HP LaserJet 1018                             | 1         | 1.79%   |
| HP DeskJet F4200 series                      | 1         | 1.79%   |
| HP DeskJet F4100 Printer series              | 1         | 1.79%   |
| HP DeskJet D1360                             | 1         | 1.79%   |
| HP DeskJet 3630 series                       | 1         | 1.79%   |
| HP DeskJet 2300 series                       | 1         | 1.79%   |
| HP DeskJet 2130 series                       | 1         | 1.79%   |
| HP Deskjet 1510                              | 1         | 1.79%   |
| Canon G4010 series                           | 1         | 1.79%   |
| Canon G4000 series                           | 1         | 1.79%   |
| Canon G3010 series                           | 1         | 1.79%   |
| Brother HL-5250DN Printer                    | 1         | 1.79%   |
| Brother DCP-7040                             | 1         | 1.79%   |

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
| Chicony Electronics                    | 1333      | 21.3%   |
| Microdia                               | 751       | 12%     |
| Realtek Semiconductor                  | 630       | 10.07%  |
| Quanta                                 | 586       | 9.36%   |
| Silicon Motion                         | 517       | 8.26%   |
| Sunplus Innovation Technology          | 477       | 7.62%   |
| Acer                                   | 416       | 6.65%   |
| IMC Networks                           | 289       | 4.62%   |
| Suyin                                  | 271       | 4.33%   |
| Syntek                                 | 202       | 3.23%   |
| Alcor Micro                            | 120       | 1.92%   |
| Apple                                  | 84        | 1.34%   |
| Cheng Uei Precision Industry (Foxlink) | 76        | 1.21%   |
| Samsung Electronics                    | 52        | 0.83%   |
| Logitech                               | 50        | 0.8%    |
| Ricoh                                  | 47        | 0.75%   |
| ALi                                    | 42        | 0.67%   |
| Sonix Technology                       | 26        | 0.42%   |
| Unknown                                | 24        | 0.38%   |
| Lite-On Technology                     | 23        | 0.37%   |
| Importek                               | 22        | 0.35%   |
| OmniVision Technologies                | 21        | 0.34%   |
| Z-Star Microelectronics                | 19        | 0.3%    |
| icSpring                               | 15        | 0.24%   |
| Y Media                                | 12        | 0.19%   |
| Lenovo                                 | 12        | 0.19%   |
| Bison Electronics                      | 11        | 0.18%   |
| LG Electronics                         | 10        | 0.16%   |
| Generalplus Technology                 | 10        | 0.16%   |
| Intel                                  | 9         | 0.14%   |
| SunplusIT                              | 8         | 0.13%   |
| Pixart Imaging                         | 8         | 0.13%   |
| Primax Electronics                     | 7         | 0.11%   |
| Microsoft                              | 7         | 0.11%   |
| Jieli Technology                       | 6         | 0.1%    |
| Image Processor                        | 6         | 0.1%    |
| Camera                                 | 6         | 0.1%    |
| Sunplus Technology                     | 5         | 0.08%   |
| JMicron Technology                     | 5         | 0.08%   |
| GEMBIRD                                | 5         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 293       | 4.68%   |
| Realtek Integrated_Webcam_HD              | 276       | 4.41%   |
| Quanta HD User Facing                     | 250       | 3.99%   |
| Chicony HD WebCam                         | 249       | 3.97%   |
| Chicony HD User Facing                    | 206       | 3.29%   |
| Silicon Motion Web Camera                 | 192       | 3.06%   |
| Sunplus Integrated_Webcam_HD              | 190       | 3.03%   |
| Quanta VGA WebCam                         | 176       | 2.81%   |
| Chicony Integrated Camera                 | 142       | 2.27%   |
| Chicony VGA WebCam                        | 137       | 2.19%   |
| Syntek Integrated Camera                  | 112       | 1.79%   |
| Sunplus HD WebCam                         | 101       | 1.61%   |
| Realtek Integrated Webcam                 | 101       | 1.61%   |
| Quanta HD Webcam                          | 99        | 1.58%   |
| Chicony USB 2.0 Camera                    | 85        | 1.36%   |
| Microdia Laptop_Integrated_Webcam_HD      | 75        | 1.2%    |
| Alcor Micro USB Camera                    | 74        | 1.18%   |
| Acer BisonCam, NB Pro                     | 65        | 1.04%   |
| Acer Lenovo EasyCamera                    | 64        | 1.02%   |
| Microdia Dell Laptop Integrated Webcam HD | 54        | 0.86%   |
| Acer EasyCamera                           | 54        | 0.86%   |
| Samsung Galaxy A5 (MTP)                   | 52        | 0.83%   |
| Acer HD Webcam                            | 51        | 0.81%   |
| Silicon Motion WebCam SC-10HDD12636N      | 50        | 0.8%    |
| IMC Networks Integrated Camera            | 50        | 0.8%    |
| Microdia Integrated Webcam HD             | 47        | 0.75%   |
| Realtek USB Camera                        | 44        | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam        | 43        | 0.69%   |
| Acer VGA WebCam                           | 43        | 0.69%   |
| Silicon Motion WebCam SCB-1100N           | 41        | 0.65%   |
| Silicon Motion WebCam SC-13HDL11939N      | 39        | 0.62%   |
| Realtek HD WebCam                         | 39        | 0.62%   |
| Syntek EasyCamera                         | 38        | 0.61%   |
| Suyin Integrated_Webcam_HD                | 38        | 0.61%   |
| Silicon Motion WebCam SC-0311139N         | 37        | 0.59%   |
| IMC Networks USB2.0 HD UVC WebCam         | 36        | 0.57%   |
| Chicony EasyCamera                        | 35        | 0.56%   |
| Silicon Motion WebCam SCB-0385N           | 33        | 0.53%   |
| Microdia Integrated Webcam                | 32        | 0.51%   |
| Chicony Lenovo EasyCamera                 | 32        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 272       | 49.64%  |
| AuthenTec                  | 58        | 10.58%  |
| Upek                       | 54        | 9.85%   |
| Synaptics                  | 54        | 9.85%   |
| Shenzhen Goodix Technology | 48        | 8.76%   |
| LighTuning Technology      | 29        | 5.29%   |
| Samsung Electronics        | 16        | 2.92%   |
| Elan Microelectronics      | 8         | 1.46%   |
| STMicroelectronics         | 4         | 0.73%   |
| Focal-systems.Corp         | 2         | 0.36%   |
| Next Biometrics            | 1         | 0.18%   |
| DigitalPersona             | 1         | 0.18%   |
| Dell                       | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 103       | 18.8%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 8.39%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 4.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 4.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 4.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 4.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 24        | 4.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.2%    |
| Validity Sensors Fingerprint scanner                                       | 21        | 3.83%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 3.28%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.92%   |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 2.92%   |
| Samsung Fingerprint Device                                                 | 16        | 2.92%   |
| AuthenTec AES2810                                                          | 14        | 2.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.55%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.19%   |
| Validity Sensors VFS491                                                    | 11        | 2.01%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 2.01%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 1.82%   |
| AuthenTec Fingerprint Sensor                                               | 10        | 1.82%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.46%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.46%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.28%   |
| Synaptics  WBDI                                                            | 7         | 1.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.28%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.09%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.91%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.91%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.36%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.36%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.36%   |
| AuthenTec AES1600                                                          | 2         | 0.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.18%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.18%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.18%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.18%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.18%   |
| Next Biometrics NB-2020-U Fingerprint Reader                               | 1         | 0.18%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 78        | 53.42%  |
| Alcor Micro               | 23        | 15.75%  |
| Lenovo                    | 13        | 8.9%    |
| Upek                      | 9         | 6.16%   |
| Giesecke & Devrient       | 7         | 4.79%   |
| Watchdata                 | 5         | 3.42%   |
| Aladdin Knowledge Systems | 5         | 3.42%   |
| O2 Micro                  | 3         | 2.05%   |
| SCM Microsystems          | 1         | 0.68%   |
| Gemalto (was Gemplus)     | 1         | 0.68%   |
| Advanced Card Systems     | 1         | 0.68%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 15.75%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 14.38%  |
| Broadcom 5880                                                                | 20        | 13.7%   |
| Broadcom 58200                                                               | 20        | 13.7%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 11.64%  |
| Lenovo Integrated Smart Card Reader                                          | 13        | 8.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 6.16%   |
| Watchdata USB Key                                                            | 5         | 3.42%   |
| Giesecke & Devrient StarSign CUT                                             | 5         | 3.42%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 3.42%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.37%   |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 1.37%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.68%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.68%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.68%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5267      | 75.76%  |
| 1     | 1473      | 21.19%  |
| 2     | 177       | 2.55%   |
| 3     | 18        | 0.26%   |
| 4     | 8         | 0.12%   |
| 7     | 4         | 0.06%   |
| 5     | 3         | 0.04%   |
| 8     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 570       | 29.95%  |
| Fingerprint reader       | 546       | 28.69%  |
| Multimedia controller    | 193       | 10.14%  |
| Net/wireless             | 150       | 7.88%   |
| Chipcard                 | 129       | 6.78%   |
| Bluetooth                | 80        | 4.2%    |
| Camera                   | 56        | 2.94%   |
| Communication controller | 41        | 2.15%   |
| Storage                  | 40        | 2.1%    |
| Sound                    | 31        | 1.63%   |
| Net/ethernet             | 22        | 1.16%   |
| Flash memory             | 20        | 1.05%   |
| Card reader              | 8         | 0.42%   |
| Modem                    | 7         | 0.37%   |
| Firewire controller      | 4         | 0.21%   |
| Network                  | 3         | 0.16%   |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |

