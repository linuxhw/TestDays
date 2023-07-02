OpenMandriva 23.03 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.03.

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

Total: 788

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| lapbook       | S15 PRO                     | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Acer          | Aspire A314-22              | [ef54ec3027](https://linux-hardware.org/?probe=ef54ec3027) | Jun 30, 2023 |
| Lenovo        | ThinkPad L430 246634S       | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| HP            | Laptop 15-db1xxx            | [6d3d6e002f](https://linux-hardware.org/?probe=6d3d6e002f) | Jun 30, 2023 |
| ASUSTek       | X555LAB                     | [99e1623ea0](https://linux-hardware.org/?probe=99e1623ea0) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a77c825995](https://linux-hardware.org/?probe=a77c825995) | Jun 29, 2023 |
| Dell          | System XPS L321X            | [abf6b8b341](https://linux-hardware.org/?probe=abf6b8b341) | Jun 29, 2023 |
| Acer          | Aspire 5830TG               | [8c001b69bb](https://linux-hardware.org/?probe=8c001b69bb) | Jun 29, 2023 |
| HP            | Pavilion dv6500             | [0286d2f5e5](https://linux-hardware.org/?probe=0286d2f5e5) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 50153CJ       | [1793064ee5](https://linux-hardware.org/?probe=1793064ee5) | Jun 29, 2023 |
| ASUSTek       | K54C                        | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| PCsmart       | PCSGOB14p-C                 | [a45977461f](https://linux-hardware.org/?probe=a45977461f) | Jun 27, 2023 |
| Clevo         | M540SS Bottom               | [4b613733a0](https://linux-hardware.org/?probe=4b613733a0) | Jun 27, 2023 |
| Dell          | Inspiron 7720               | [89858274fd](https://linux-hardware.org/?probe=89858274fd) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [501d3b5530](https://linux-hardware.org/?probe=501d3b5530) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Dell          | Precision M6400             | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [bce89b670d](https://linux-hardware.org/?probe=bce89b670d) | Jun 25, 2023 |
| Packard Be... | EasyNote TK85               | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| HP            | G62                         | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| Dell          | Latitude 3180               | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| HP            | Compaq 610                  | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| MSI           | S12T 3M/S12 3M              | [f135825cec](https://linux-hardware.org/?probe=f135825cec) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| Dell          | Inspiron 5557               | [cc0794fa6e](https://linux-hardware.org/?probe=cc0794fa6e) | Jun 21, 2023 |
| Sony          | VGN-NS21M_W                 | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| Acer          | One S1002                   | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| HP            | Notebook                    | [3460bcb864](https://linux-hardware.org/?probe=3460bcb864) | Jun 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [f84ddd7cac](https://linux-hardware.org/?probe=f84ddd7cac) | Jun 20, 2023 |
| Acer          | Aspire F5-771G              | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| Dell          | System XPS L502X            | [463e017820](https://linux-hardware.org/?probe=463e017820) | Jun 19, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| HP            | Laptop 14s-dk1xxx           | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS4840B     | [a60f1ae93e](https://linux-hardware.org/?probe=a60f1ae93e) | Jun 17, 2023 |
| ASUSTek       | X551CAP                     | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [d415965e91](https://linux-hardware.org/?probe=d415965e91) | Jun 17, 2023 |
| Monster       | HUMA H4 V5.2                | [491797a556](https://linux-hardware.org/?probe=491797a556) | Jun 17, 2023 |
| Dell          | XPS 15 9550                 | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| Acer          | Aspire V3-571               | [75c2da2c37](https://linux-hardware.org/?probe=75c2da2c37) | Jun 15, 2023 |
| HP            | EliteBook 2540p             | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| ASUSTek       | S400CA                      | [d512f1865e](https://linux-hardware.org/?probe=d512f1865e) | Jun 15, 2023 |
| Dell          | Inspiron 1501               | [456a49b146](https://linux-hardware.org/?probe=456a49b146) | Jun 13, 2023 |
| LincPlus      | LINNCPLUS P1                | [878dc2b05f](https://linux-hardware.org/?probe=878dc2b05f) | Jun 13, 2023 |
| Chuwi         | GemiBook Pro                | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
| Positivo      | C14CR01                     | [11d46971fa](https://linux-hardware.org/?probe=11d46971fa) | Jun 12, 2023 |
| ASUSTek       | X540SAA                     | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| Acer          | Aspire E1-572               | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [03660fb140](https://linux-hardware.org/?probe=03660fb140) | Jun 10, 2023 |
| HP            | G42                         | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| HP            | Stream Notebook PC 11       | [fd037bb738](https://linux-hardware.org/?probe=fd037bb738) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Lenovo        | Z50-70 20354                | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| Compaq        | 420                         | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Valve         | Jupiter                     | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| HP            | EliteBook 8440p             | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| Lenovo        | B51-80 80LM                 | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| Apple         | MacBookAir9,1               | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| Dell          | System Vostro 3450          | [ae337aeb9c](https://linux-hardware.org/?probe=ae337aeb9c) | May 31, 2023 |
| Timi          | RedmiBook 14 II             | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| HP            | 255 G8 Notebook PC          | [ea55e0ac39](https://linux-hardware.org/?probe=ea55e0ac39) | May 30, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Samsung       | RV419/RV420                 | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| Acer          | Aspire ES1-512              | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Google        | Auron_Paine                 | [66fd27934f](https://linux-hardware.org/?probe=66fd27934f) | May 29, 2023 |
| Acer          | Aspire E5-573               | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Lenovo        | ThinkPad W541 20EF000MUS    | [44c1329399](https://linux-hardware.org/?probe=44c1329399) | May 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [42b817db26](https://linux-hardware.org/?probe=42b817db26) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| Lenovo        | G400 20235                  | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| Dell          | Inspiron 7559               | [af1bb009ca](https://linux-hardware.org/?probe=af1bb009ca) | May 28, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Toshiba       | Satellite L500              | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| Acer          | Aspire 7540                 | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| Toshiba       | Satellite C645D             | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| HP            | 15 Notebook PC              | [3904ffdddf](https://linux-hardware.org/?probe=3904ffdddf) | May 27, 2023 |
| Acer          | Aspire A517-51G             | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| Dell          | Inspiron 5567               | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Dell          | Latitude 5290               | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| MSI           | GL75 Leopard 10SDK          | [41eac45c5e](https://linux-hardware.org/?probe=41eac45c5e) | May 25, 2023 |
| Dell          | Inspiron 15-3567            | [a8dd30a7bb](https://linux-hardware.org/?probe=a8dd30a7bb) | May 25, 2023 |
| Timi          | TM1701                      | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| Toshiba       | Satellite C660D             | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| Apple         | MacBookPro9,2               | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| Dell          | Latitude E6230              | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| ASUSTek       | K84L                        | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| HP            | Pavilion dv7                | [816fffab13](https://linux-hardware.org/?probe=816fffab13) | May 21, 2023 |
| Philco        | 14H                         | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | [03afaf2468](https://linux-hardware.org/?probe=03afaf2468) | May 21, 2023 |
| Fujitsu       | LIFEBOOK S752               | [906ba8b65c](https://linux-hardware.org/?probe=906ba8b65c) | May 21, 2023 |
| ASUSTek       | N53TK                       | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Lenovo        | Y50-70 20378                | [2aff70d7c9](https://linux-hardware.org/?probe=2aff70d7c9) | May 21, 2023 |
| Acer          | Aspire 4750                 | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| HP            | 15 Notebook PC              | [e1939cff8f](https://linux-hardware.org/?probe=e1939cff8f) | May 21, 2023 |
| Toshiba       | Satellite P300              | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| Dell          | Inspiron 1501               | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Dell          | Latitude 5285               | [0db3cfd34e](https://linux-hardware.org/?probe=0db3cfd34e) | May 20, 2023 |
| HP            | Laptop 15-ef2xxx            | [b563edd887](https://linux-hardware.org/?probe=b563edd887) | May 20, 2023 |
| HP            | 250 G2                      | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| Chuwi         | HeroBook Pro                | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| ASUSTek       | F7Se                        | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [82dca1cbb8](https://linux-hardware.org/?probe=82dca1cbb8) | May 18, 2023 |
| Toshiba       | Satellite L850-1HQ          | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [df73f83c15](https://linux-hardware.org/?probe=df73f83c15) | May 18, 2023 |
| Google        | Auron_Paine                 | [a836fcd48f](https://linux-hardware.org/?probe=a836fcd48f) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| HP            | Pavilion g6                 | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | [cfe4d9071b](https://linux-hardware.org/?probe=cfe4d9071b) | May 16, 2023 |
| Samsung       | R428/P428                   | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| HP            | Pavilion dv8                | [422d1fd213](https://linux-hardware.org/?probe=422d1fd213) | May 14, 2023 |
| Acer          | Aspire A114-32              | [6fdf42b8a9](https://linux-hardware.org/?probe=6fdf42b8a9) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Precision M4500             | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Lenovo        | G50-30 80G0                 | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Vostro 3400                 | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Toshiba       | Satellite C75-A             | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| Acer          | Extensa 5220                | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| HP            | Laptop 17-by0xxx            | [10b9d3a925](https://linux-hardware.org/?probe=10b9d3a925) | May 11, 2023 |
| Acer          | Aspire E1-521               | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| ASUSTek       | X555LAB                     | [2710a15a04](https://linux-hardware.org/?probe=2710a15a04) | May 10, 2023 |
| Samsung       | X420/X520                   | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Dell          | Precision M3800             | [e7b0097a72](https://linux-hardware.org/?probe=e7b0097a72) | May 09, 2023 |
| Dell          | Inspiron 5559               | [f7cb6c9251](https://linux-hardware.org/?probe=f7cb6c9251) | May 09, 2023 |
| Dell          | Latitude 5420               | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Fujitsu       | FMVA0500TP                  | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Acer          | Aspire VN7-592G             | [8ebde36ef2](https://linux-hardware.org/?probe=8ebde36ef2) | May 09, 2023 |
| Acer          | Aspire A515-56              | [57b843a3ca](https://linux-hardware.org/?probe=57b843a3ca) | May 09, 2023 |
| Apple         | MacBookPro11,4              | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| Dell          | Latitude E6440              | [6b8d3c96c5](https://linux-hardware.org/?probe=6b8d3c96c5) | May 09, 2023 |
| HP            | Pavilion dv7                | [1d9699c86f](https://linux-hardware.org/?probe=1d9699c86f) | May 09, 2023 |
| HP            | Pavilion dv6                | [531adb6cae](https://linux-hardware.org/?probe=531adb6cae) | May 09, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| HP            | 15                          | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| Acer          | Aspire ES1-132              | [10a13dcd68](https://linux-hardware.org/?probe=10a13dcd68) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| ASUSTek       | X202E                       | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| HP            | 15                          | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | XPS 13 9310                 | [3530619c98](https://linux-hardware.org/?probe=3530619c98) | May 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b734a6d6f3](https://linux-hardware.org/?probe=b734a6d6f3) | May 07, 2023 |
| Toshiba       | Satellite L655              | [9eef570443](https://linux-hardware.org/?probe=9eef570443) | May 07, 2023 |
| Lenovo        | G50-70 20351                | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| HP            | Presario CQ57               | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Dell          | System XPS L702X            | [210b876fe7](https://linux-hardware.org/?probe=210b876fe7) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3bf20b454](https://linux-hardware.org/?probe=b3bf20b454) | May 06, 2023 |
| Panasonic     | CF-54-1                     | [c964ce47c2](https://linux-hardware.org/?probe=c964ce47c2) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [094b22cf5a](https://linux-hardware.org/?probe=094b22cf5a) | May 06, 2023 |
| Toshiba       | Satellite L300D             | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| HP            | EliteBook 2530p             | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| ASUSTek       | K75DE                       | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| ASUSTek       | X401A1                      | [3fa1a1e9f0](https://linux-hardware.org/?probe=3fa1a1e9f0) | May 05, 2023 |
| Dell          | Inspiron 17-7779            | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| Medion        | E6232                       | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Gateway       | NE46R                       | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| HP            | Laptop 17-ak0xx             | [579c16cd5c](https://linux-hardware.org/?probe=579c16cd5c) | May 04, 2023 |
| HP            | EliteBook 8540p             | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Fujitsu       | FMVA705ABS                  | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [d8ec895bea](https://linux-hardware.org/?probe=d8ec895bea) | May 03, 2023 |
| Dell          | Latitude E6410              | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Dell          | Latitude E6540              | [e9f23b9574](https://linux-hardware.org/?probe=e9f23b9574) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [cb2a0efe72](https://linux-hardware.org/?probe=cb2a0efe72) | May 02, 2023 |
| Toshiba       | Satellite L755              | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| Lenovo        | V15-IGL 82C3                | [583642a695](https://linux-hardware.org/?probe=583642a695) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| HP            | Compaq 8510w                | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [15c04364fa](https://linux-hardware.org/?probe=15c04364fa) | May 01, 2023 |
| lapbook       | S15 PRO                     | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| HP            | Notebook                    | [4cece109d5](https://linux-hardware.org/?probe=4cece109d5) | Apr 30, 2023 |
| ASUSTek       | X501A1                      | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| Acer          | Aspire A315-33              | [fdba59c054](https://linux-hardware.org/?probe=fdba59c054) | Apr 30, 2023 |
| Acer          | AO725                       | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| HP            | Compaq 6720s                | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | ProBook 650 G4              | [fd991056e0](https://linux-hardware.org/?probe=fd991056e0) | Apr 30, 2023 |
| Dell          | Inspiron 15 3525            | [41c212fa2c](https://linux-hardware.org/?probe=41c212fa2c) | Apr 30, 2023 |
| Acer          | TravelMate B311-31          | [de172b8988](https://linux-hardware.org/?probe=de172b8988) | Apr 30, 2023 |
| Dell          | Vostro 15 3515              | [8f07407e1a](https://linux-hardware.org/?probe=8f07407e1a) | Apr 29, 2023 |
| Lenovo        | G50-30 80G0                 | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| Toshiba       | PORTEGE R830                | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Apple         | MacBookPro13,3              | [0f22698060](https://linux-hardware.org/?probe=0f22698060) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| HP            | Pavilion Notebook           | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| Dell          | Latitude 7390               | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| Medion        | X6816                       | [2c1807dad7](https://linux-hardware.org/?probe=2c1807dad7) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| ASUSTek       | X542URR                     | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| GPU Compan... | GWNR71517                   | [5fe84b74b0](https://linux-hardware.org/?probe=5fe84b74b0) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| Sony          | SVF15212CXW                 | [5d5367dc0e](https://linux-hardware.org/?probe=5d5367dc0e) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| HP            | ProBook 4330s               | [955f91641b](https://linux-hardware.org/?probe=955f91641b) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| Lenovo        | ThinkPad R61 8943DJG        | [afc3fc578e](https://linux-hardware.org/?probe=afc3fc578e) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| NEC Comput... | PC-LE150C2                  | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [32960eca65](https://linux-hardware.org/?probe=32960eca65) | Apr 27, 2023 |
| Dell          | Latitude E6400              | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [21577119ad](https://linux-hardware.org/?probe=21577119ad) | Apr 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Unknown       | Unknown                     | [208f6823ed](https://linux-hardware.org/?probe=208f6823ed) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| GPU Compan... | GWNR71517                   | [b8b58af983](https://linux-hardware.org/?probe=b8b58af983) | Apr 26, 2023 |
| ASUSTek       | X550VQ                      | [3c7d8a0268](https://linux-hardware.org/?probe=3c7d8a0268) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [2e6de51ded](https://linux-hardware.org/?probe=2e6de51ded) | Apr 26, 2023 |
| Login Info... | LOG-S14BW01-CD              | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| Sony          | VPCS13V9E                   | [3c1551d7be](https://linux-hardware.org/?probe=3c1551d7be) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| HP            | Compaq 15                   | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| Toshiba       | Satellite L305D             | [1bbf3a5e9c](https://linux-hardware.org/?probe=1bbf3a5e9c) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | [6aa907fd2e](https://linux-hardware.org/?probe=6aa907fd2e) | Apr 25, 2023 |
| Fujitsu       | LIFEBOOK S935               | [418c2c626e](https://linux-hardware.org/?probe=418c2c626e) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| Dell          | Latitude XT2                | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Chuwi         | GemiBook Pro                | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| Toshiba       | dynabook BX/67TG            | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6115e5ccd4](https://linux-hardware.org/?probe=6115e5ccd4) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 6930p             | [2ff545a3fc](https://linux-hardware.org/?probe=2ff545a3fc) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| HP            | ProBook 4330s               | [f6608ffee2](https://linux-hardware.org/?probe=f6608ffee2) | Apr 22, 2023 |
| HP            | ProBook 450 G3              | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Acer          | Extensa 5635Z               | [015e857f63](https://linux-hardware.org/?probe=015e857f63) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| HP            | Compaq 6720s                | [b980c3c57d](https://linux-hardware.org/?probe=b980c3c57d) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| Dell          | Inspiron 3520               | [11ea81f23c](https://linux-hardware.org/?probe=11ea81f23c) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| Dell          | Latitude 5400               | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| HP            | G62                         | [a0096bb254](https://linux-hardware.org/?probe=a0096bb254) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Toshiba       | dynabook T451/46EW          | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| HP            | ProBook 450 G2              | [14d03d2dd7](https://linux-hardware.org/?probe=14d03d2dd7) | Apr 19, 2023 |
| HP            | 255 G7 Notebook PC          | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| ASUSTek       | N501VW                      | [a31036cae1](https://linux-hardware.org/?probe=a31036cae1) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Acer          | Aspire 5733Z                | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| Dell          | Inspiron 15-3567            | [c5639cddcb](https://linux-hardware.org/?probe=c5639cddcb) | Apr 19, 2023 |
| Apple         | MacBookPro8,1               | [4e95dc284c](https://linux-hardware.org/?probe=4e95dc284c) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6fae9a24fb](https://linux-hardware.org/?probe=6fae9a24fb) | Apr 19, 2023 |
| HP            | Unknown                     | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | [76aabd80a0](https://linux-hardware.org/?probe=76aabd80a0) | Apr 18, 2023 |
| Acer          | AO722                       | [5fe24a9991](https://linux-hardware.org/?probe=5fe24a9991) | Apr 18, 2023 |
| Lenovo        | B50-30 20382                | [d8995dacdc](https://linux-hardware.org/?probe=d8995dacdc) | Apr 18, 2023 |
| Fujitsu       | FMVNA6HE                    | [609572e6f7](https://linux-hardware.org/?probe=609572e6f7) | Apr 18, 2023 |
| Lenovo        | ThinkPad P53 20QN001YUS     | [59549202bd](https://linux-hardware.org/?probe=59549202bd) | Apr 18, 2023 |
| Apple         | MacBookPro8,1               | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| HP            | ProBook 645 G1              | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| Medion        | E16401                      | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| HP            | Laptop 15-db1xxx            | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| Dell          | Latitude D830               | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Dell          | XPS 17 9700                 | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| Dell          | Precision 7510              | [abb2d93e32](https://linux-hardware.org/?probe=abb2d93e32) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Dell          | Latitude E6330              | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| ASUSTek       | K73E                        | [9ab8e37631](https://linux-hardware.org/?probe=9ab8e37631) | Apr 15, 2023 |
| Fujitsu Si... | ESPRIMO Mobile X9515        | [82ffd0e4bd](https://linux-hardware.org/?probe=82ffd0e4bd) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [6c711c5197](https://linux-hardware.org/?probe=6c711c5197) | Apr 15, 2023 |
| Dell          | Precision 7730              | [0e434903ec](https://linux-hardware.org/?probe=0e434903ec) | Apr 15, 2023 |
| MSI           | Modern 14 B10MW             | [c655afe860](https://linux-hardware.org/?probe=c655afe860) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| GPD           | G1619-01                    | [2edac2c38e](https://linux-hardware.org/?probe=2edac2c38e) | Apr 15, 2023 |
| MSI           | Prestige 15 A12SC           | [51259c6f0a](https://linux-hardware.org/?probe=51259c6f0a) | Apr 15, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [dfed605628](https://linux-hardware.org/?probe=dfed605628) | Apr 15, 2023 |
| Acer          | Swift SF314-511             | [f960c27052](https://linux-hardware.org/?probe=f960c27052) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | [f3b7c9c255](https://linux-hardware.org/?probe=f3b7c9c255) | Apr 14, 2023 |
| MSI           | Delta 15 A5EFK              | [44cdfb0917](https://linux-hardware.org/?probe=44cdfb0917) | Apr 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [a5cb4f9095](https://linux-hardware.org/?probe=a5cb4f9095) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Sony          | VGN-NR11Z_T                 | [d7d5674aa5](https://linux-hardware.org/?probe=d7d5674aa5) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [e3f3f9fd2b](https://linux-hardware.org/?probe=e3f3f9fd2b) | Apr 14, 2023 |
| HP            | Pavilion dv6                | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | G505 20240                  | [62bdfa97bd](https://linux-hardware.org/?probe=62bdfa97bd) | Apr 14, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [8fb8771c70](https://linux-hardware.org/?probe=8fb8771c70) | Apr 14, 2023 |
| Dell          | Latitude E6540              | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Toshiba       | Satellite L75D-A            | [210a475989](https://linux-hardware.org/?probe=210a475989) | Apr 13, 2023 |
| Acer          | Aspire A315-56              | [8c2cc310b2](https://linux-hardware.org/?probe=8c2cc310b2) | Apr 13, 2023 |
| System76      | Galago Pro                  | [9239e8d213](https://linux-hardware.org/?probe=9239e8d213) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a841c5fce3](https://linux-hardware.org/?probe=a841c5fce3) | Apr 13, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f983dadfeb](https://linux-hardware.org/?probe=f983dadfeb) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [830a3e27dd](https://linux-hardware.org/?probe=830a3e27dd) | Apr 13, 2023 |
| Toshiba       | Satellite L300D             | [76595cf176](https://linux-hardware.org/?probe=76595cf176) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| Dell          | Latitude E6230              | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Acer          | Aspire 5733Z                | [b42b19277c](https://linux-hardware.org/?probe=b42b19277c) | Apr 12, 2023 |
| ASUSTek       | K53U                        | [19ec753136](https://linux-hardware.org/?probe=19ec753136) | Apr 12, 2023 |
| HUAWEI        | HLYL-WXX9                   | [db51c5a1f3](https://linux-hardware.org/?probe=db51c5a1f3) | Apr 12, 2023 |
| Toshiba       | Satellite L350D             | [df4e0aa857](https://linux-hardware.org/?probe=df4e0aa857) | Apr 12, 2023 |
| HP            | Presario CQ62               | [edee5d8480](https://linux-hardware.org/?probe=edee5d8480) | Apr 12, 2023 |
| Samsung       | R460                        | [9908964d4a](https://linux-hardware.org/?probe=9908964d4a) | Apr 11, 2023 |
| Lenovo        | IdeaPad Z470                | [2348aee3d4](https://linux-hardware.org/?probe=2348aee3d4) | Apr 11, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| Dell          | Inspiron N4010              | [c52176294b](https://linux-hardware.org/?probe=c52176294b) | Apr 11, 2023 |
| Lenovo        | ThinkPad L580 20LW000VMX    | [7b2e3794c9](https://linux-hardware.org/?probe=7b2e3794c9) | Apr 11, 2023 |
| Lenovo        | B590 20206                  | [5aad144224](https://linux-hardware.org/?probe=5aad144224) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| Acer          | TM6495T                     | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Avell High... | A52 HYB                     | [0795bca947](https://linux-hardware.org/?probe=0795bca947) | Apr 11, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [eb294beef7](https://linux-hardware.org/?probe=eb294beef7) | Apr 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [52b464bfd3](https://linux-hardware.org/?probe=52b464bfd3) | Apr 10, 2023 |
| ASUSTek       | X541UV                      | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| Lenovo        | 3000 V200 07642XU           | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| ASUSTek       | G751JY                      | [618a195c21](https://linux-hardware.org/?probe=618a195c21) | Apr 10, 2023 |
| Packard Be... | EasyNote LS11HR             | [56f4b51911](https://linux-hardware.org/?probe=56f4b51911) | Apr 10, 2023 |
| ASUSTek       | UX303UB                     | [f94b0ee950](https://linux-hardware.org/?probe=f94b0ee950) | Apr 10, 2023 |
| HP            | EliteBook 840 G5            | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| HP            | EliteBook 2170p             | [34f1e1686e](https://linux-hardware.org/?probe=34f1e1686e) | Apr 10, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | [f90c2d47c7](https://linux-hardware.org/?probe=f90c2d47c7) | Apr 10, 2023 |
| Lenovo        | ThinkPad T420s 417152U      | [5964d01442](https://linux-hardware.org/?probe=5964d01442) | Apr 10, 2023 |
| Dell          | Inspiron 3583               | [502c993dfd](https://linux-hardware.org/?probe=502c993dfd) | Apr 10, 2023 |
| HP            | Notebook                    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| Gigabyte      | MMLP3AP-00                  | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [332f3ed32f](https://linux-hardware.org/?probe=332f3ed32f) | Apr 09, 2023 |
| Positivo      | A1000BW                     | [02295facdc](https://linux-hardware.org/?probe=02295facdc) | Apr 09, 2023 |
| Sony          | VPCEB1M1E                   | [c182925286](https://linux-hardware.org/?probe=c182925286) | Apr 09, 2023 |
| HP            | EliteBook 8570p             | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [d6cbe10f95](https://linux-hardware.org/?probe=d6cbe10f95) | Apr 09, 2023 |
| Lenovo        | B575 1450ABU                | [ef58d2e8e6](https://linux-hardware.org/?probe=ef58d2e8e6) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | [e66056ac2d](https://linux-hardware.org/?probe=e66056ac2d) | Apr 09, 2023 |
| Lenovo        | ThinkPad X131e 33722VU      | [5e2ba16114](https://linux-hardware.org/?probe=5e2ba16114) | Apr 09, 2023 |
| Samsung       | RV419                       | [88985a3d0d](https://linux-hardware.org/?probe=88985a3d0d) | Apr 09, 2023 |
| Sony          | SVE1713A1EW                 | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| Acer          | Aspire ES1-531              | [f36574c96a](https://linux-hardware.org/?probe=f36574c96a) | Apr 09, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | [779e8396d6](https://linux-hardware.org/?probe=779e8396d6) | Apr 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d261eb3697](https://linux-hardware.org/?probe=d261eb3697) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Google        | Lindar rev3                 | [e6dd3f6805](https://linux-hardware.org/?probe=e6dd3f6805) | Apr 09, 2023 |
| Dell          | Inspiron 7720               | [27df270817](https://linux-hardware.org/?probe=27df270817) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [fa54308baa](https://linux-hardware.org/?probe=fa54308baa) | Apr 09, 2023 |
| Apple         | MacBook5,2                  | [916db99ea5](https://linux-hardware.org/?probe=916db99ea5) | Apr 09, 2023 |
| Toshiba       | Satellite C660              | [bb9f88795d](https://linux-hardware.org/?probe=bb9f88795d) | Apr 09, 2023 |
| Acer          | Enduro EUN314-51WG          | [7f73117dba](https://linux-hardware.org/?probe=7f73117dba) | Apr 09, 2023 |
| Dell          | Latitude E6420              | [56f5370788](https://linux-hardware.org/?probe=56f5370788) | Apr 09, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [ea9bd3a740](https://linux-hardware.org/?probe=ea9bd3a740) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7659AB7        | [0b2f9a23ee](https://linux-hardware.org/?probe=0b2f9a23ee) | Apr 09, 2023 |
| Fujitsu       | LIFEBOOK E752               | [e60f7c9b72](https://linux-hardware.org/?probe=e60f7c9b72) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [c8173d40cd](https://linux-hardware.org/?probe=c8173d40cd) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [93e9be5f34](https://linux-hardware.org/?probe=93e9be5f34) | Apr 09, 2023 |
| Lenovo        | G50-70 20351                | [7ab9939757](https://linux-hardware.org/?probe=7ab9939757) | Apr 09, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [675aea5637](https://linux-hardware.org/?probe=675aea5637) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| HP            | Laptop 17-by4xxx            | [03cfb9e574](https://linux-hardware.org/?probe=03cfb9e574) | Apr 09, 2023 |
| HP            | Compaq 6530b (KR978UT#AB... | [3d8060476b](https://linux-hardware.org/?probe=3d8060476b) | Apr 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [5d39494c01](https://linux-hardware.org/?probe=5d39494c01) | Apr 09, 2023 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1701c2baae](https://linux-hardware.org/?probe=1701c2baae) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [869d7607e9](https://linux-hardware.org/?probe=869d7607e9) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| HP            | 250 G6 Notebook PC          | [22da370a63](https://linux-hardware.org/?probe=22da370a63) | Apr 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [12faf271f6](https://linux-hardware.org/?probe=12faf271f6) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| ASUSTek       | X751LN                      | [8bf4f37814](https://linux-hardware.org/?probe=8bf4f37814) | Apr 08, 2023 |
| Acer          | Predator PH315-54           | [edbc0b98a4](https://linux-hardware.org/?probe=edbc0b98a4) | Apr 08, 2023 |
| Standard      | SF20BA2                     | [17763324b6](https://linux-hardware.org/?probe=17763324b6) | Apr 08, 2023 |
| HP            | Notebook                    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| Dell          | Latitude 3410               | [9fd7d9d439](https://linux-hardware.org/?probe=9fd7d9d439) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [14a3d5f4be](https://linux-hardware.org/?probe=14a3d5f4be) | Apr 08, 2023 |
| Dell          | Inspiron 1520               | [b5b9ede1c6](https://linux-hardware.org/?probe=b5b9ede1c6) | Apr 08, 2023 |
| Toshiba       | dynabook R732/H             | [ff99abe105](https://linux-hardware.org/?probe=ff99abe105) | Apr 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1a6e63f6b2](https://linux-hardware.org/?probe=1a6e63f6b2) | Apr 08, 2023 |
| HP            | ProBook 6470b               | [9926dac4aa](https://linux-hardware.org/?probe=9926dac4aa) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Acer          | Aspire A515-56              | [7c8165c2ca](https://linux-hardware.org/?probe=7c8165c2ca) | Apr 08, 2023 |
| Acer          | Aspire A515-51G             | [34d03fbbcd](https://linux-hardware.org/?probe=34d03fbbcd) | Apr 08, 2023 |
| HP            | Laptop 15-dy2xxx            | [eadf220620](https://linux-hardware.org/?probe=eadf220620) | Apr 08, 2023 |
| Sony          | VJF155F11X-B0811B           | [89f9cc86a7](https://linux-hardware.org/?probe=89f9cc86a7) | Apr 08, 2023 |
| Acer          | Swift SF314-43              | [95cf4404c3](https://linux-hardware.org/?probe=95cf4404c3) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| Lenovo        | G50-70 20351                | [b8dd840f5d](https://linux-hardware.org/?probe=b8dd840f5d) | Apr 08, 2023 |
| VIT           | P2402                       | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [99305e0876](https://linux-hardware.org/?probe=99305e0876) | Apr 07, 2023 |
| Acer          | Aspire 5517                 | [bbedb2d88e](https://linux-hardware.org/?probe=bbedb2d88e) | Apr 07, 2023 |
| Dell          | Inspiron 11-3162            | [accdfd2253](https://linux-hardware.org/?probe=accdfd2253) | Apr 07, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| HP            | EliteBook 2530p             | [66ec38445f](https://linux-hardware.org/?probe=66ec38445f) | Apr 07, 2023 |
| Notebook      | NJ50_70CU                   | [0ad152ba3c](https://linux-hardware.org/?probe=0ad152ba3c) | Apr 07, 2023 |
| Dell          | Latitude 5400               | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| Lenovo        | ThinkPad T60 2008VW7        | [de0d5654c0](https://linux-hardware.org/?probe=de0d5654c0) | Apr 07, 2023 |
| ASUSTek       | A8Le                        | [c00ff94698](https://linux-hardware.org/?probe=c00ff94698) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [aab830c5dd](https://linux-hardware.org/?probe=aab830c5dd) | Apr 07, 2023 |
| HP            | ProBook 650 G4              | [0e9b21ff7e](https://linux-hardware.org/?probe=0e9b21ff7e) | Apr 07, 2023 |
| HP            | Pavilion 17                 | [43d7593dd5](https://linux-hardware.org/?probe=43d7593dd5) | Apr 07, 2023 |
| ASUSTek       | S551LN                      | [2c731aefae](https://linux-hardware.org/?probe=2c731aefae) | Apr 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a3ae05a7cb](https://linux-hardware.org/?probe=a3ae05a7cb) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| ASUSTek       | X555QA                      | [6fb3c3952e](https://linux-hardware.org/?probe=6fb3c3952e) | Apr 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5a900adcdc](https://linux-hardware.org/?probe=5a900adcdc) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d48cada4e3](https://linux-hardware.org/?probe=d48cada4e3) | Apr 07, 2023 |
| Dell          | XPS 17 9710                 | [b4c155dc99](https://linux-hardware.org/?probe=b4c155dc99) | Apr 07, 2023 |
| Dell          | Precision M3800             | [6fbee1d04d](https://linux-hardware.org/?probe=6fbee1d04d) | Apr 07, 2023 |
| Dell          | Latitude 5490               | [89f89d2a9e](https://linux-hardware.org/?probe=89f89d2a9e) | Apr 07, 2023 |
| HP            | 620                         | [2e14b2c046](https://linux-hardware.org/?probe=2e14b2c046) | Apr 07, 2023 |
| Lenovo        | ThinkPad T470s 20HF0001M... | [8c6105e5be](https://linux-hardware.org/?probe=8c6105e5be) | Apr 06, 2023 |
| eMachines     | E725                        | [758d0c86b2](https://linux-hardware.org/?probe=758d0c86b2) | Apr 06, 2023 |
| Dell          | Latitude E6440              | [d63602cd95](https://linux-hardware.org/?probe=d63602cd95) | Apr 06, 2023 |
| Acer          | Aspire E5-771               | [2ef87c5f77](https://linux-hardware.org/?probe=2ef87c5f77) | Apr 06, 2023 |
| HP            | ProBook 4740s               | [14fb51de44](https://linux-hardware.org/?probe=14fb51de44) | Apr 06, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2QF0... | [806fc59e4f](https://linux-hardware.org/?probe=806fc59e4f) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Samsung       | R540/R580/R780/SA41/E452... | [5c446bcf49](https://linux-hardware.org/?probe=5c446bcf49) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| ASUSTek       | K46CM                       | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| ASUSTek       | X55U                        | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3358152092](https://linux-hardware.org/?probe=3358152092) | Apr 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [0ca203f8b0](https://linux-hardware.org/?probe=0ca203f8b0) | Apr 06, 2023 |
| HP            | Laptop 15-bs0xx             | [c73108de7b](https://linux-hardware.org/?probe=c73108de7b) | Apr 06, 2023 |
| HP            | Compaq Presario CQ71        | [82c50e39ad](https://linux-hardware.org/?probe=82c50e39ad) | Apr 06, 2023 |
| Toshiba       | Satellite Pro L350          | [a75b4d94aa](https://linux-hardware.org/?probe=a75b4d94aa) | Apr 06, 2023 |
| MSI           | GL73 8RC                    | [c134ae92fc](https://linux-hardware.org/?probe=c134ae92fc) | Apr 06, 2023 |
| HP            | Laptop 15-db0xxx            | [e05bffcc8a](https://linux-hardware.org/?probe=e05bffcc8a) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| HUAWEI        | BOM-WXX9                    | [d4dd77439e](https://linux-hardware.org/?probe=d4dd77439e) | Apr 06, 2023 |
| Lenovo        | 3000 N200 0769DQJ           | [db1539e64a](https://linux-hardware.org/?probe=db1539e64a) | Apr 06, 2023 |
| Dell          | Inspiron 1720               | [0f0d515832](https://linux-hardware.org/?probe=0f0d515832) | Apr 06, 2023 |
| Dell          | Latitude E7440              | [3fc74781a7](https://linux-hardware.org/?probe=3fc74781a7) | Apr 06, 2023 |
| Positivo      | H14BT58                     | [135bb6e61a](https://linux-hardware.org/?probe=135bb6e61a) | Apr 06, 2023 |
| Apple         | MacBookPro5,5               | [4e0ff5c2f7](https://linux-hardware.org/?probe=4e0ff5c2f7) | Apr 06, 2023 |
| Lenovo        | ThinkPad X230 2324FU0       | [47be9d7510](https://linux-hardware.org/?probe=47be9d7510) | Apr 06, 2023 |
| ASUSTek       | S551LN                      | [bab2c0f0e4](https://linux-hardware.org/?probe=bab2c0f0e4) | Apr 06, 2023 |
| Dell          | Inspiron 3584               | [50f052ef1c](https://linux-hardware.org/?probe=50f052ef1c) | Apr 06, 2023 |
| HP            | 620                         | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Dell          | Latitude E4200              | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| Dell          | Latitude E5550              | [5527315153](https://linux-hardware.org/?probe=5527315153) | Apr 05, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [0240b337ac](https://linux-hardware.org/?probe=0240b337ac) | Apr 05, 2023 |
| HP            | EliteBook 6930p             | [8e769590fb](https://linux-hardware.org/?probe=8e769590fb) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [5d0489d439](https://linux-hardware.org/?probe=5d0489d439) | Apr 05, 2023 |
| HP            | Notebook                    | [99a9d4cae5](https://linux-hardware.org/?probe=99a9d4cae5) | Apr 05, 2023 |
| ASUSTek       | X71Q                        | [9a7d0f4b2b](https://linux-hardware.org/?probe=9a7d0f4b2b) | Apr 05, 2023 |
| Toshiba       | Satellite L640              | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad E470 20H1006VRT    | [a9b909f3df](https://linux-hardware.org/?probe=a9b909f3df) | Apr 05, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [e27fc333c6](https://linux-hardware.org/?probe=e27fc333c6) | Apr 05, 2023 |
| Sony          | VGN-CS31MR_P                | [c97f0353d0](https://linux-hardware.org/?probe=c97f0353d0) | Apr 05, 2023 |
| HP            | Victus by Gaming Laptop ... | [6ad0f579b6](https://linux-hardware.org/?probe=6ad0f579b6) | Apr 05, 2023 |
| Fujitsu       | FMVA45MRP2                  | [80b1f5983b](https://linux-hardware.org/?probe=80b1f5983b) | Apr 05, 2023 |
| Acer          | Aspire ES1-572              | [bb95a52e54](https://linux-hardware.org/?probe=bb95a52e54) | Apr 05, 2023 |
| Dell          | Latitude E6440              | [eea06ab302](https://linux-hardware.org/?probe=eea06ab302) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Evolute       | B14HM21                     | [be41163512](https://linux-hardware.org/?probe=be41163512) | Apr 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [a2b079980a](https://linux-hardware.org/?probe=a2b079980a) | Apr 05, 2023 |
| ASUSTek       | UX305UA                     | [5c19e22fe1](https://linux-hardware.org/?probe=5c19e22fe1) | Apr 05, 2023 |
| Acer          | Aspire E5-575               | [ba6c827f8f](https://linux-hardware.org/?probe=ba6c827f8f) | Apr 05, 2023 |
| HP            | Notebook                    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Lenovo        | V15-ADA 82C7                | [62dd2f5f34](https://linux-hardware.org/?probe=62dd2f5f34) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| Compumax C... | ONIX-CEL-0001               | [b3e9bc2fb0](https://linux-hardware.org/?probe=b3e9bc2fb0) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [f04b34af52](https://linux-hardware.org/?probe=f04b34af52) | Apr 04, 2023 |
| ASUSTek       | N501VW                      | [1db257af9f](https://linux-hardware.org/?probe=1db257af9f) | Apr 04, 2023 |
| HP            | EliteBook 8470w             | [47e8a4441b](https://linux-hardware.org/?probe=47e8a4441b) | Apr 04, 2023 |
| TPS           | C48P                        | [df8a2ac617](https://linux-hardware.org/?probe=df8a2ac617) | Apr 04, 2023 |
| Apple         | MacBookAir5,2               | [cb94d3ff68](https://linux-hardware.org/?probe=cb94d3ff68) | Apr 04, 2023 |
| eMachines     | D725                        | [f3cdf26e60](https://linux-hardware.org/?probe=f3cdf26e60) | Apr 04, 2023 |
| Dell          | Latitude 7280               | [e0fcb10ef5](https://linux-hardware.org/?probe=e0fcb10ef5) | Apr 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1af0b7675b](https://linux-hardware.org/?probe=1af0b7675b) | Apr 04, 2023 |
| HP            | ProBook 6570b               | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [ceeafa59a2](https://linux-hardware.org/?probe=ceeafa59a2) | Apr 04, 2023 |
| Acer          | Aspire ES1-572              | [39e1087c79](https://linux-hardware.org/?probe=39e1087c79) | Apr 04, 2023 |
| Dell          | Studio 1558                 | [e9b75d657d](https://linux-hardware.org/?probe=e9b75d657d) | Apr 04, 2023 |
| Lenovo        | IdeaPad Z585 20152          | [efb4022e4c](https://linux-hardware.org/?probe=efb4022e4c) | Apr 04, 2023 |
| ASUSTek       | S551LB                      | [cd1746937a](https://linux-hardware.org/?probe=cd1746937a) | Apr 04, 2023 |
| Timi          | TM1703                      | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [473898ff0e](https://linux-hardware.org/?probe=473898ff0e) | Apr 04, 2023 |
| Unknown       | Unknown                     | [7325272558](https://linux-hardware.org/?probe=7325272558) | Apr 04, 2023 |
| ASUSTek       | X200MA                      | [8cfe6c0f97](https://linux-hardware.org/?probe=8cfe6c0f97) | Apr 04, 2023 |
| Acer          | Aspire 4349                 | [43ae04b9c3](https://linux-hardware.org/?probe=43ae04b9c3) | Apr 04, 2023 |
| Lenovo        | B50-80 80LT                 | [163bfb5525](https://linux-hardware.org/?probe=163bfb5525) | Apr 03, 2023 |
| Toshiba       | Satellite L655              | [1381de4b71](https://linux-hardware.org/?probe=1381de4b71) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [cd18ce0a96](https://linux-hardware.org/?probe=cd18ce0a96) | Apr 03, 2023 |
| Lenovo        | ThinkPad X200 7459J74       | [d7f98c1ddb](https://linux-hardware.org/?probe=d7f98c1ddb) | Apr 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [770caf96be](https://linux-hardware.org/?probe=770caf96be) | Apr 03, 2023 |
| Lenovo        | B50-30 80ES                 | [11da2097ba](https://linux-hardware.org/?probe=11da2097ba) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7f3280e60](https://linux-hardware.org/?probe=d7f3280e60) | Apr 03, 2023 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [49b1cef736](https://linux-hardware.org/?probe=49b1cef736) | Apr 03, 2023 |
| Acer          | Aspire A515-51              | [c9245a7032](https://linux-hardware.org/?probe=c9245a7032) | Apr 03, 2023 |
| Dell          | Inspiron 3542               | [bcf9cf6ba6](https://linux-hardware.org/?probe=bcf9cf6ba6) | Apr 03, 2023 |
| HP            | EliteBook Folio G1          | [ad873ac967](https://linux-hardware.org/?probe=ad873ac967) | Apr 03, 2023 |
| Dell          | Latitude 7480               | [f1ca485181](https://linux-hardware.org/?probe=f1ca485181) | Apr 02, 2023 |
| ASUSTek       | UX303UB                     | [9b46784fd5](https://linux-hardware.org/?probe=9b46784fd5) | Apr 02, 2023 |
| HP            | Laptop 17-ca0xxx            | [6399f19b22](https://linux-hardware.org/?probe=6399f19b22) | Apr 02, 2023 |
| HP            | OMEN by Laptop              | [647c427d7b](https://linux-hardware.org/?probe=647c427d7b) | Apr 02, 2023 |
| HP            | Laptop 14-cm0xxx            | [984d71ee3d](https://linux-hardware.org/?probe=984d71ee3d) | Apr 02, 2023 |
| ASUSTek       | G71V                        | [6594dac071](https://linux-hardware.org/?probe=6594dac071) | Apr 02, 2023 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [3ec9fed32b](https://linux-hardware.org/?probe=3ec9fed32b) | Apr 02, 2023 |
| ASUSTek       | N53SV                       | [5b2c0ea506](https://linux-hardware.org/?probe=5b2c0ea506) | Apr 02, 2023 |
| HP            | Laptop 15q-ds0xxx           | [42bd53a04e](https://linux-hardware.org/?probe=42bd53a04e) | Apr 02, 2023 |
| ASUSTek       | X555LAB                     | [95f5025351](https://linux-hardware.org/?probe=95f5025351) | Apr 02, 2023 |
| AZW           | Speed S                     | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| PCSMART S.... | PNTGOB11CPE                 | [874d355cc4](https://linux-hardware.org/?probe=874d355cc4) | Apr 02, 2023 |
| Dell          | Latitude E5400              | [4b69d7d67c](https://linux-hardware.org/?probe=4b69d7d67c) | Apr 02, 2023 |
| ASUSTek       | G750JW                      | [b7c8d9cc5f](https://linux-hardware.org/?probe=b7c8d9cc5f) | Apr 01, 2023 |
| Dell          | System XPS L502X            | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| HP            | ProBook 455 G1              | [869f36fc4c](https://linux-hardware.org/?probe=869f36fc4c) | Apr 01, 2023 |
| Dell          | Latitude 5511               | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Dell          | Latitude E7470              | [3eb8069059](https://linux-hardware.org/?probe=3eb8069059) | Apr 01, 2023 |
| Acer          | Aspire A515-41G             | [f047e9361c](https://linux-hardware.org/?probe=f047e9361c) | Apr 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [eb7bbd9b91](https://linux-hardware.org/?probe=eb7bbd9b91) | Apr 01, 2023 |
| Notebook      | W54BL                       | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
| Toshiba       | dynabook T653/46JR          | [7f0e2d07b5](https://linux-hardware.org/?probe=7f0e2d07b5) | Apr 01, 2023 |
| Acer          | Aspire A715-41G             | [cea0d2797d](https://linux-hardware.org/?probe=cea0d2797d) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Dell          | Inspiron 15 5510            | [e169cd0886](https://linux-hardware.org/?probe=e169cd0886) | Apr 01, 2023 |
| HP            | Pavilion g7                 | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| Acer          | Aspire V5-121               | [d6cc7a67ab](https://linux-hardware.org/?probe=d6cc7a67ab) | Apr 01, 2023 |
| Acer          | Aspire 5740                 | [eeba9d18fa](https://linux-hardware.org/?probe=eeba9d18fa) | Apr 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [96c53eccb0](https://linux-hardware.org/?probe=96c53eccb0) | Apr 01, 2023 |
| Acer          | Aspire A315-35              | [659a4cfd5a](https://linux-hardware.org/?probe=659a4cfd5a) | Apr 01, 2023 |
| ASUSTek       | N752VX                      | [d426499408](https://linux-hardware.org/?probe=d426499408) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| Unknown       | X133                        | [950572f119](https://linux-hardware.org/?probe=950572f119) | Apr 01, 2023 |
| ASUSTek       | F3JP                        | [e561213582](https://linux-hardware.org/?probe=e561213582) | Apr 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [87bc2601f3](https://linux-hardware.org/?probe=87bc2601f3) | Apr 01, 2023 |
| ASUSTek       | S551LN                      | [916adbdf9f](https://linux-hardware.org/?probe=916adbdf9f) | Apr 01, 2023 |
| Sony          | VPCEH1S1R                   | [12100cdd4b](https://linux-hardware.org/?probe=12100cdd4b) | Apr 01, 2023 |
| Lenovo        | G505 20240                  | [d873632b2b](https://linux-hardware.org/?probe=d873632b2b) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| HP            | EliteBook 8470p             | [178ccc8d4d](https://linux-hardware.org/?probe=178ccc8d4d) | Apr 01, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [9db0830268](https://linux-hardware.org/?probe=9db0830268) | Apr 01, 2023 |
| Lenovo        | G560 20042                  | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| Toshiba       | Satellite C55-B             | [250e5371c1](https://linux-hardware.org/?probe=250e5371c1) | Apr 01, 2023 |
| Lenovo        | ThinkPad X230 2325DV4       | [6cff5cd5d1](https://linux-hardware.org/?probe=6cff5cd5d1) | Apr 01, 2023 |
| Dell          | Latitude 5580               | [10cbd4c04d](https://linux-hardware.org/?probe=10cbd4c04d) | Apr 01, 2023 |
| Fujitsu       | LIFEBOOK S935               | [11b63a22b5](https://linux-hardware.org/?probe=11b63a22b5) | Apr 01, 2023 |
| Sony          | VPCEA3BFX                   | [6215c985dd](https://linux-hardware.org/?probe=6215c985dd) | Apr 01, 2023 |
| Lenovo        | V15-IGL 82C3                | [4773b9449c](https://linux-hardware.org/?probe=4773b9449c) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | [eea311b1bb](https://linux-hardware.org/?probe=eea311b1bb) | Apr 01, 2023 |
| HP            | Laptop 15s-eq3xxx           | [758bb2556e](https://linux-hardware.org/?probe=758bb2556e) | Apr 01, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | [9de89fee19](https://linux-hardware.org/?probe=9de89fee19) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| Dell          | Latitude E7450              | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [93ef0bb287](https://linux-hardware.org/?probe=93ef0bb287) | Apr 01, 2023 |
| Samsung       | 270E5G/270E5U               | [67b91e463a](https://linux-hardware.org/?probe=67b91e463a) | Mar 31, 2023 |
| Acer          | Aspire A315-54K             | [d325177071](https://linux-hardware.org/?probe=d325177071) | Mar 31, 2023 |
| HP            | ProBook 440 G6              | [5198509903](https://linux-hardware.org/?probe=5198509903) | Mar 31, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [66a1075056](https://linux-hardware.org/?probe=66a1075056) | Mar 31, 2023 |
| Quanta        | QL3 TBD                     | [21673aecac](https://linux-hardware.org/?probe=21673aecac) | Mar 31, 2023 |
| HP            | Compaq Presario CQ60        | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Microtech     | ebookPro                    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Intel         | Kabylake Platform           | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Toshiba       | Satellite L655              | [d527726a1c](https://linux-hardware.org/?probe=d527726a1c) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [ad92e27c90](https://linux-hardware.org/?probe=ad92e27c90) | Mar 31, 2023 |
| Acer          | Aspire 7720                 | [073d49ce6b](https://linux-hardware.org/?probe=073d49ce6b) | Mar 31, 2023 |
| Dell          | Precision 5570              | [a3d5f928ee](https://linux-hardware.org/?probe=a3d5f928ee) | Mar 31, 2023 |
| Dell          | Latitude E7440              | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| HP            | 250 G5 Notebook PC          | [d271318192](https://linux-hardware.org/?probe=d271318192) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2347EP7       | [6fd7423cb6](https://linux-hardware.org/?probe=6fd7423cb6) | Mar 31, 2023 |
| HP            | Pavilion 15                 | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [29c4ba04a1](https://linux-hardware.org/?probe=29c4ba04a1) | Mar 31, 2023 |
| Acer          | Aspire ES1-531              | [aedba72f70](https://linux-hardware.org/?probe=aedba72f70) | Mar 31, 2023 |
| Unknown       | Unknown                     | [c30740a3eb](https://linux-hardware.org/?probe=c30740a3eb) | Mar 31, 2023 |
| HP            | Laptop 17-cp2xxx            | [854de8a433](https://linux-hardware.org/?probe=854de8a433) | Mar 31, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [d6c537b33b](https://linux-hardware.org/?probe=d6c537b33b) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [54f8c5082d](https://linux-hardware.org/?probe=54f8c5082d) | Mar 31, 2023 |
| Acer          | Aspire 1410                 | [58be80ea51](https://linux-hardware.org/?probe=58be80ea51) | Mar 31, 2023 |
| Acer          | Aspire 5720Z                | [ca2b750eeb](https://linux-hardware.org/?probe=ca2b750eeb) | Mar 31, 2023 |
| Acer          | TravelMate B311-31          | [3345b754b7](https://linux-hardware.org/?probe=3345b754b7) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| Notebook      | NL40_50GU                   | [a46afd7246](https://linux-hardware.org/?probe=a46afd7246) | Mar 31, 2023 |
| Star Labs     | Lite                        | [e3689ef845](https://linux-hardware.org/?probe=e3689ef845) | Mar 31, 2023 |
| Acer          | Aspire 7741                 | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HP            | Unknown                     | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [225e13e1f0](https://linux-hardware.org/?probe=225e13e1f0) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Toshiba       | Satellite P875              | [aba8c03541](https://linux-hardware.org/?probe=aba8c03541) | Mar 30, 2023 |
| ASUSTek       | K53SJ                       | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Notebook      | N150CU                      | [5da0df2cf0](https://linux-hardware.org/?probe=5da0df2cf0) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| HP            | EliteBook 2540p             | [6aae8ca2a0](https://linux-hardware.org/?probe=6aae8ca2a0) | Mar 30, 2023 |
| Dell          | XPS 17 9710                 | [6b37881138](https://linux-hardware.org/?probe=6b37881138) | Mar 30, 2023 |
| HP            | ProBook 6360b               | [cf027e03de](https://linux-hardware.org/?probe=cf027e03de) | Mar 30, 2023 |
| Acer          | Prespa M                    | [a6541a27d9](https://linux-hardware.org/?probe=a6541a27d9) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [afd41155ee](https://linux-hardware.org/?probe=afd41155ee) | Mar 30, 2023 |
| Lenovo        | G550 2958                   | [41f23ded68](https://linux-hardware.org/?probe=41f23ded68) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | V15-ADA 82C7                | [552ad08e05](https://linux-hardware.org/?probe=552ad08e05) | Mar 30, 2023 |
| Dell          | Latitude E7450              | [63e8748d1f](https://linux-hardware.org/?probe=63e8748d1f) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [d3eafe4568](https://linux-hardware.org/?probe=d3eafe4568) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Acer          | NC-M3-581T-33216G52MAKK     | [3f394d8b43](https://linux-hardware.org/?probe=3f394d8b43) | Mar 30, 2023 |
| Dell          | Latitude E6430              | [086b5d0f79](https://linux-hardware.org/?probe=086b5d0f79) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| Lenovo        | ThinkPad X395 20NLS0J400    | [e9d9710ef9](https://linux-hardware.org/?probe=e9d9710ef9) | Mar 30, 2023 |
| Dell          | Precision 5550              | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| HP            | Notebook                    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| Lenovo        | U41-70 80JV                 | [975da67142](https://linux-hardware.org/?probe=975da67142) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| Acer          | Aspire A515-57              | [06a3c07a40](https://linux-hardware.org/?probe=06a3c07a40) | Mar 29, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Dell          | System Inspiron N7110       | [cc23cb7065](https://linux-hardware.org/?probe=cc23cb7065) | Mar 29, 2023 |
| Samsung       | 670Z5E                      | [2bf528dfb1](https://linux-hardware.org/?probe=2bf528dfb1) | Mar 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [695a074faf](https://linux-hardware.org/?probe=695a074faf) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Acer          | Aspire E1-571G              | [574f00dff5](https://linux-hardware.org/?probe=574f00dff5) | Mar 29, 2023 |
| Acer          | Aspire E5-576               | [37fc62a287](https://linux-hardware.org/?probe=37fc62a287) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| Notebook      | NL40_50CU                   | [fe471635fb](https://linux-hardware.org/?probe=fe471635fb) | Mar 29, 2023 |
| Dell          | Vostro 5568                 | [0004be15a4](https://linux-hardware.org/?probe=0004be15a4) | Mar 28, 2023 |
| HP            | ENVY Notebook               | [98cd32ea44](https://linux-hardware.org/?probe=98cd32ea44) | Mar 28, 2023 |
| HP            | 250 G6 Notebook PC          | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Acer          | Aspire V3-571G              | [ecde786683](https://linux-hardware.org/?probe=ecde786683) | Mar 28, 2023 |
| HP            | Compaq 6510b (GR680ET)      | [716c4212c7](https://linux-hardware.org/?probe=716c4212c7) | Mar 28, 2023 |
| Lenovo        | V145-15AST 81MT             | [7fff3bb217](https://linux-hardware.org/?probe=7fff3bb217) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Acer          | Aspire E1-570               | [71b25255fa](https://linux-hardware.org/?probe=71b25255fa) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | Aspire E5-532G              | [35e076d9b5](https://linux-hardware.org/?probe=35e076d9b5) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK E556               | [bbd878e897](https://linux-hardware.org/?probe=bbd878e897) | Mar 28, 2023 |
| Dell          | Vostro 14-5480              | [b1ef6303a6](https://linux-hardware.org/?probe=b1ef6303a6) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK E556               | [3842c12714](https://linux-hardware.org/?probe=3842c12714) | Mar 28, 2023 |
| HP            | Pavilion Notebook           | [783330690d](https://linux-hardware.org/?probe=783330690d) | Mar 28, 2023 |
| Dell          | Latitude E5500              | [6fea10bf98](https://linux-hardware.org/?probe=6fea10bf98) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Dell          | Latitude 7490               | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | Latitude E5570              | [5b3d1ab8b9](https://linux-hardware.org/?probe=5b3d1ab8b9) | Mar 28, 2023 |
| Dell          | Inspiron 3558               | [c80d4c15ce](https://linux-hardware.org/?probe=c80d4c15ce) | Mar 28, 2023 |
| Dell          | Inspiron 5515               | [13a0d1426d](https://linux-hardware.org/?probe=13a0d1426d) | Mar 28, 2023 |
| Lenovo        | ThinkPad W520 4284E79       | [2d9875ca24](https://linux-hardware.org/?probe=2d9875ca24) | Mar 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [df27b06a95](https://linux-hardware.org/?probe=df27b06a95) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| ASUSTek       | X555DG                      | [6a464d8e68](https://linux-hardware.org/?probe=6a464d8e68) | Mar 27, 2023 |
| Acer          | Aspire E5-575               | [5964caaa02](https://linux-hardware.org/?probe=5964caaa02) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| Lenovo        | ThinkPad X220 42915P1       | [40d0cf6e14](https://linux-hardware.org/?probe=40d0cf6e14) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W1K       | [e093aace6e](https://linux-hardware.org/?probe=e093aace6e) | Mar 27, 2023 |
| Dell          | Latitude E6430              | [61ec1b65ed](https://linux-hardware.org/?probe=61ec1b65ed) | Mar 27, 2023 |
| Sony          | VPCSA2C5E                   | [60e85a64b0](https://linux-hardware.org/?probe=60e85a64b0) | Mar 27, 2023 |
| ASUSTek       | K56CA                       | [43f064cb46](https://linux-hardware.org/?probe=43f064cb46) | Mar 27, 2023 |
| Acer          | Aspire A515-45              | [d480257689](https://linux-hardware.org/?probe=d480257689) | Mar 27, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [580e3a1237](https://linux-hardware.org/?probe=580e3a1237) | Mar 27, 2023 |
| Acer          | Mammoth                     | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| Lenovo        | ThinkPad L450 20DS0001GE    | [17f869b10d](https://linux-hardware.org/?probe=17f869b10d) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS3WY0... | [d1e9fcddfc](https://linux-hardware.org/?probe=d1e9fcddfc) | Mar 27, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [7facc52f0e](https://linux-hardware.org/?probe=7facc52f0e) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| ASUSTek       | K54HR                       | [ac6cf948d5](https://linux-hardware.org/?probe=ac6cf948d5) | Mar 27, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e4a88fa14e](https://linux-hardware.org/?probe=e4a88fa14e) | Mar 27, 2023 |
| Lenovo        | B460e                       | [1c79a13a61](https://linux-hardware.org/?probe=1c79a13a61) | Mar 27, 2023 |
| Acer          | Aspire A315-56              | [db607e02ea](https://linux-hardware.org/?probe=db607e02ea) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [84d2bfb9cc](https://linux-hardware.org/?probe=84d2bfb9cc) | Mar 27, 2023 |
| Dell          | Inspiron 5448               | [b800b24cbd](https://linux-hardware.org/?probe=b800b24cbd) | Mar 27, 2023 |
| Acer          | Aspire V3-551               | [48409a7222](https://linux-hardware.org/?probe=48409a7222) | Mar 27, 2023 |
| Dell          | Latitude 7490               | [58ccd5d7e0](https://linux-hardware.org/?probe=58ccd5d7e0) | Mar 27, 2023 |
| HP            | Pavilion g6                 | [4b08001481](https://linux-hardware.org/?probe=4b08001481) | Mar 27, 2023 |
| Dell          | Inspiron 3537               | [5b1971e361](https://linux-hardware.org/?probe=5b1971e361) | Mar 27, 2023 |
| Acer          | Aspire A515-41G             | [33bccb2234](https://linux-hardware.org/?probe=33bccb2234) | Mar 27, 2023 |
| Sony          | VJFE52A0711H                | [f2186a4bc4](https://linux-hardware.org/?probe=f2186a4bc4) | Mar 27, 2023 |
| Lenovo        | ThinkPad L530 24812SG       | [163d4e376e](https://linux-hardware.org/?probe=163d4e376e) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Dell          | XPS 15 9520                 | [35718792af](https://linux-hardware.org/?probe=35718792af) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [7dbe4350b5](https://linux-hardware.org/?probe=7dbe4350b5) | Mar 26, 2023 |
| Acer          | Aspire E1-431               | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E744               | [f32cce4c6f](https://linux-hardware.org/?probe=f32cce4c6f) | Mar 26, 2023 |
| Lenovo        | ThinkPad X220 4290LR3       | [dffa03da18](https://linux-hardware.org/?probe=dffa03da18) | Mar 26, 2023 |
| Gigabyte      | A7 K1                       | [0eca943d2e](https://linux-hardware.org/?probe=0eca943d2e) | Mar 26, 2023 |
| Acer          | Aspire 5820                 | [3e0e45bc17](https://linux-hardware.org/?probe=3e0e45bc17) | Mar 26, 2023 |
| Dell          | Inspiron 3576               | [18352c181a](https://linux-hardware.org/?probe=18352c181a) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [51d034c8d1](https://linux-hardware.org/?probe=51d034c8d1) | Mar 25, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [1c88428088](https://linux-hardware.org/?probe=1c88428088) | Mar 22, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b6b5eb415f](https://linux-hardware.org/?probe=b6b5eb415f) | Mar 21, 2023 |
| Acer          | TravelMate 5760             | [712e36569d](https://linux-hardware.org/?probe=712e36569d) | Mar 20, 2023 |
| Acer          | Swift SF113-31              | [f1db5ada96](https://linux-hardware.org/?probe=f1db5ada96) | Mar 18, 2023 |
| Dell          | Latitude D530               | [c02081557b](https://linux-hardware.org/?probe=c02081557b) | Mar 18, 2023 |
| Dell          | Latitude E7470              | [f2dd0afe92](https://linux-hardware.org/?probe=f2dd0afe92) | Mar 17, 2023 |
| Toshiba       | Satellite C55-A-1T6         | [71751e4045](https://linux-hardware.org/?probe=71751e4045) | Mar 16, 2023 |
| HP            | ZBook 15 G5                 | [2af12bdf73](https://linux-hardware.org/?probe=2af12bdf73) | Mar 16, 2023 |
| Lenovo        | G400s 20244                 | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Inspiron 15-3567            | [97504eea44](https://linux-hardware.org/?probe=97504eea44) | Mar 13, 2023 |
| HONOR         | HYM-WXX                     | [366d00f0a7](https://linux-hardware.org/?probe=366d00f0a7) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0d7e6b4a80](https://linux-hardware.org/?probe=0d7e6b4a80) | Mar 12, 2023 |
| Unknown       | Unknown                     | [d1336c09a0](https://linux-hardware.org/?probe=d1336c09a0) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| Kiano         | Elegance 14.2               | [5714b30108](https://linux-hardware.org/?probe=5714b30108) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [6a40dced5b](https://linux-hardware.org/?probe=6a40dced5b) | Mar 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6e7ffbd8ad](https://linux-hardware.org/?probe=6e7ffbd8ad) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [efe5bcec0b](https://linux-hardware.org/?probe=efe5bcec0b) | Mar 07, 2023 |
| GPU Compan... | GWTN156-11                  | [c451be28c3](https://linux-hardware.org/?probe=c451be28c3) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [c517071efd](https://linux-hardware.org/?probe=c517071efd) | Mar 06, 2023 |
| HP            | Notebook                    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| HP            | Compaq Presario CQ60        | [cbdc8bcd6a](https://linux-hardware.org/?probe=cbdc8bcd6a) | Mar 06, 2023 |
| Dell          | Inspiron 5567               | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| GPU Compan... | GWTN156-11                  | [fe4af91506](https://linux-hardware.org/?probe=fe4af91506) | Mar 06, 2023 |
| Lenovo        | ThinkPad T550 20CJS02E00    | [d8535715f8](https://linux-hardware.org/?probe=d8535715f8) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7e0a15042f](https://linux-hardware.org/?probe=7e0a15042f) | Mar 05, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9186971572](https://linux-hardware.org/?probe=9186971572) | Mar 03, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.03/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-desktop-1omv2390   | 752       | 95.92%  |
| 6.2.2-desktop-1omv2390   | 20        | 2.55%   |
| 6.1.1-desktop-1omv2290   | 4         | 0.51%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.26%   |
| 5.16.13-desktop-1omv4003 | 2         | 0.26%   |
| 6.2.8-desktop-1omv2390   | 1         | 0.13%   |
| 6.2.7-desktop-1omv2390   | 1         | 0.13%   |
| 6.2.1-desktop-1omv2390   | 1         | 0.13%   |
| 6.1.22-xanmod1           | 1         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.6   | 752       | 95.92%  |
| 6.2.2   | 20        | 2.55%   |
| 6.1.1   | 4         | 0.51%   |
| 6.1.4   | 2         | 0.26%   |
| 5.16.13 | 2         | 0.26%   |
| 6.2.8   | 1         | 0.13%   |
| 6.2.7   | 1         | 0.13%   |
| 6.2.1   | 1         | 0.13%   |
| 6.1.22  | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 775       | 98.85%  |
| 6.1     | 7         | 0.89%   |
| 5.16    | 2         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 784       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 671       | 85.59%  |
| GNOME    | 55        | 7.02%   |
| LXQt     | 50        | 6.38%   |
| Cinnamon | 3         | 0.38%   |
| XFCE     | 2         | 0.26%   |
| Unknown  | 2         | 0.26%   |
| Budgie   | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 732       | 93.37%  |
| Wayland | 52        | 6.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 727       | 92.73%  |
| GDM     | 55        | 7.02%   |
| LightDM | 2         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 368       | 46.94%  |
| de_DE | 64        | 8.16%   |
| fr_FR | 50        | 6.38%   |
| pl_PL | 37        | 4.72%   |
| en_GB | 36        | 4.59%   |
| it_IT | 35        | 4.46%   |
| ru_RU | 33        | 4.21%   |
| pt_BR | 20        | 2.55%   |
| es_MX | 18        | 2.3%    |
| es_ES | 14        | 1.79%   |
| en_AU | 10        | 1.28%   |
| en_CA | 9         | 1.15%   |
| cs_CZ | 9         | 1.15%   |
| hu_HU | 7         | 0.89%   |
| tr_TR | 6         | 0.77%   |
| en_IN | 6         | 0.77%   |
| da_DK | 6         | 0.77%   |
| nl_NL | 5         | 0.64%   |
| pt_PT | 4         | 0.51%   |
| nl_BE | 4         | 0.51%   |
| es_PE | 4         | 0.51%   |
| es_AR | 4         | 0.51%   |
| fr_CH | 3         | 0.38%   |
| fr_BE | 3         | 0.38%   |
| en_NZ | 3         | 0.38%   |
| de_CH | 3         | 0.38%   |
| UTF-8 | 2         | 0.26%   |
| ja_JP | 2         | 0.26%   |
| es_CO | 2         | 0.26%   |
| es_CL | 2         | 0.26%   |
| en_ZA | 2         | 0.26%   |
| en_AG | 2         | 0.26%   |
| C     | 2         | 0.26%   |
| id_ID | 1         | 0.13%   |
| fr_CA | 1         | 0.13%   |
| es_VE | 1         | 0.13%   |
| es_UY | 1         | 0.13%   |
| en_PH | 1         | 0.13%   |
| en_DK | 1         | 0.13%   |
| de_AT | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 489       | 62.37%  |
| BIOS | 295       | 37.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 388       | 49.49%  |
| Overlay | 327       | 41.71%  |
| Btrfs   | 53        | 6.76%   |
| Xfs     | 9         | 1.15%   |
| F2fs    | 7         | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 624       | 79.59%  |
| MBR  | 160       | 20.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 446       | 56.89%  |
| Yes       | 338       | 43.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 505       | 64.41%  |
| Yes       | 279       | 35.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 173       | 22.07%  |
| Hewlett-Packard     | 136       | 17.35%  |
| Dell                | 107       | 13.65%  |
| ASUSTek Computer    | 87        | 11.1%   |
| Acer                | 81        | 10.33%  |
| Toshiba             | 36        | 4.59%   |
| Samsung Electronics | 19        | 2.42%   |
| Sony                | 14        | 1.79%   |
| Fujitsu             | 14        | 1.79%   |
| Apple               | 13        | 1.66%   |
| MSI                 | 10        | 1.28%   |
| Notebook            | 7         | 0.89%   |
| HUAWEI              | 5         | 0.64%   |
| Chuwi               | 5         | 0.64%   |
| Unknown             | 5         | 0.64%   |
| TUXEDO              | 4         | 0.51%   |
| GPU Company         | 4         | 0.51%   |
| Timi                | 3         | 0.38%   |
| Positivo            | 3         | 0.38%   |
| Packard Bell        | 3         | 0.38%   |
| Medion              | 3         | 0.38%   |
| lapbook             | 3         | 0.38%   |
| Kiano               | 3         | 0.38%   |
| Google              | 3         | 0.38%   |
| Gigabyte Technology | 2         | 0.26%   |
| Fujitsu Siemens     | 2         | 0.26%   |
| eMachines           | 2         | 0.26%   |
| Wortmann AG         | 1         | 0.13%   |
| VIT                 | 1         | 0.13%   |
| Valve               | 1         | 0.13%   |
| UMAX                | 1         | 0.13%   |
| TPS                 | 1         | 0.13%   |
| TEKNOSERVICE        | 1         | 0.13%   |
| System76            | 1         | 0.13%   |
| Star Labs           | 1         | 0.13%   |
| Standard            | 1         | 0.13%   |
| SLIMBOOK            | 1         | 0.13%   |
| Semp Toshiba        | 1         | 0.13%   |
| Razer               | 1         | 0.13%   |
| Quanta              | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP Notebook                                 | 8         | 1.02%   |
| Unknown                                     | 7         | 0.89%   |
| ASUS S551LN                                 | 6         | 0.77%   |
| Lenovo IdeaPad 1 14ADA05 82GW               | 5         | 0.64%   |
| Toshiba Satellite L655                      | 4         | 0.51%   |
| Samsung 950XCJ/951XCJ/950XCR                | 4         | 0.51%   |
| Lenovo V15-ADA 82C7                         | 4         | 0.51%   |
| Lenovo IdeaPad 3 15ALC6 82KU                | 4         | 0.51%   |
| HP 250 G6 Notebook PC                       | 4         | 0.51%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)          | 3         | 0.38%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 3         | 0.38%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3001LUK        | 3         | 0.38%   |
| Lenovo IdeaPad S145-15AST 81N3              | 3         | 0.38%   |
| Lenovo G50-70 20351                         | 3         | 0.38%   |
| lapbook S15 PRO                             | 3         | 0.38%   |
| Kiano Elegance 14.2                         | 3         | 0.38%   |
| HP Pavilion Notebook                        | 3         | 0.38%   |
| HP Laptop 15s-eq2xxx                        | 3         | 0.38%   |
| HP EliteBook 2530p                          | 3         | 0.38%   |
| HP 255 G8 Notebook PC                       | 3         | 0.38%   |
| Fujitsu LIFEBOOK S935                       | 3         | 0.38%   |
| Dell Latitude E6440                         | 3         | 0.38%   |
| Dell Latitude 7490                          | 3         | 0.38%   |
| Dell Inspiron 1720                          | 3         | 0.38%   |
| Dell Inspiron 15-3567                       | 3         | 0.38%   |
| Chuwi GemiBook Pro                          | 3         | 0.38%   |
| ASUS X555LAB                                | 3         | 0.38%   |
| Apple MacBookPro9,2                         | 3         | 0.38%   |
| Apple MacBookPro8,1                         | 3         | 0.38%   |
| Toshiba Satellite L350D                     | 2         | 0.26%   |
| Toshiba Satellite L300D                     | 2         | 0.26%   |
| Toshiba Satellite C660                      | 2         | 0.26%   |
| MSI Modern 14 B10MW                         | 2         | 0.26%   |
| Lenovo V15-IGL 82C3                         | 2         | 0.26%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK       | 2         | 0.26%   |
| Lenovo IdeaPad 330S-15IKB 81F5              | 2         | 0.26%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 2         | 0.26%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 2         | 0.26%   |
| Lenovo G570 20079                           | 2         | 0.26%   |
| Lenovo G550 2958                            | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 76        | 9.69%   |
| Acer Aspire           | 63        | 8.04%   |
| Lenovo IdeaPad        | 49        | 6.25%   |
| Dell Latitude         | 44        | 5.61%   |
| Dell Inspiron         | 34        | 4.34%   |
| Toshiba Satellite     | 30        | 3.83%   |
| HP Pavilion           | 27        | 3.44%   |
| HP Laptop             | 22        | 2.81%   |
| ASUS VivoBook         | 20        | 2.55%   |
| HP EliteBook          | 18        | 2.3%    |
| HP Compaq             | 15        | 1.91%   |
| HP ProBook            | 13        | 1.66%   |
| Fujitsu LIFEBOOK      | 10        | 1.28%   |
| HP Notebook           | 8         | 1.02%   |
| Dell Vostro           | 8         | 1.02%   |
| Dell Precision        | 8         | 1.02%   |
| Unknown               | 7         | 0.89%   |
| HP 250                | 6         | 0.77%   |
| Dell XPS              | 6         | 0.77%   |
| Dell System           | 6         | 0.77%   |
| ASUS S551LN           | 6         | 0.77%   |
| Toshiba dynabook      | 5         | 0.64%   |
| Lenovo Legion         | 5         | 0.64%   |
| Acer Swift            | 5         | 0.64%   |
| Samsung 950XCJ        | 4         | 0.51%   |
| Lenovo V15-ADA        | 4         | 0.51%   |
| HP 255                | 4         | 0.51%   |
| HP 15                 | 4         | 0.51%   |
| ASUS ROG              | 4         | 0.51%   |
| ASUS ASUS             | 4         | 0.51%   |
| Acer TravelMate       | 4         | 0.51%   |
| TUXEDO InfinityBook   | 3         | 0.38%   |
| Packard Bell EasyNote | 3         | 0.38%   |
| Lenovo G50-70         | 3         | 0.38%   |
| lapbook S15           | 3         | 0.38%   |
| Kiano Elegance        | 3         | 0.38%   |
| HP Victus             | 3         | 0.38%   |
| HP OMEN               | 3         | 0.38%   |
| Chuwi GemiBook        | 3         | 0.38%   |
| ASUS X555LAB          | 3         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 82        | 10.46%  |
| 2020    | 75        | 9.57%   |
| 2012    | 70        | 8.93%   |
| 2011    | 67        | 8.55%   |
| 2015    | 55        | 7.02%   |
| 2018    | 53        | 6.76%   |
| 2013    | 48        | 6.12%   |
| 2019    | 46        | 5.87%   |
| 2014    | 45        | 5.74%   |
| 2010    | 45        | 5.74%   |
| 2016    | 38        | 4.85%   |
| 2017    | 37        | 4.72%   |
| 2008    | 35        | 4.46%   |
| 2022    | 28        | 3.57%   |
| 2007    | 26        | 3.32%   |
| 2009    | 25        | 3.19%   |
| 2006    | 4         | 0.51%   |
| 2023    | 3         | 0.38%   |
| 2004    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 784       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 784       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 780       | 99.49%  |
| Yes  | 4         | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 292       | 37.24%  |
| 3.01-4.0    | 188       | 23.98%  |
| 16.01-24.0  | 104       | 13.27%  |
| 8.01-16.0   | 101       | 12.88%  |
| 32.01-64.0  | 32        | 4.08%   |
| 1.01-2.0    | 28        | 3.57%   |
| 2.01-3.0    | 19        | 2.42%   |
| 64.01-256.0 | 12        | 1.53%   |
| 24.01-32.0  | 8         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 492       | 62.76%  |
| 2.01-3.0 | 201       | 25.64%  |
| 0.51-1.0 | 48        | 6.12%   |
| 3.01-4.0 | 35        | 4.46%   |
| 4.01-8.0 | 7         | 0.89%   |
| 0.01-0.5 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 569       | 72.58%  |
| 2      | 178       | 22.7%   |
| 3      | 25        | 3.19%   |
| 0      | 10        | 1.28%   |
| 4      | 2         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 453       | 57.78%  |
| Yes       | 331       | 42.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 634       | 80.87%  |
| No        | 150       | 19.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 778       | 99.23%  |
| No        | 6         | 0.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 604       | 77.04%  |
| No        | 180       | 22.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 111       | 14.16%  |
| Germany     | 82        | 10.46%  |
| Italy       | 49        | 6.25%   |
| France      | 47        | 5.99%   |
| Poland      | 46        | 5.87%   |
| Russia      | 45        | 5.74%   |
| Brazil      | 39        | 4.97%   |
| UK          | 34        | 4.34%   |
| Japan       | 24        | 3.06%   |
| Spain       | 19        | 2.42%   |
| Canada      | 19        | 2.42%   |
| Mexico      | 15        | 1.91%   |
| India       | 15        | 1.91%   |
| Netherlands | 14        | 1.79%   |
| Czechia     | 12        | 1.53%   |
| Australia   | 12        | 1.53%   |
| Finland     | 11        | 1.4%    |
| Indonesia   | 10        | 1.28%   |
| Belgium     | 9         | 1.15%   |
| Argentina   | 9         | 1.15%   |
| Hungary     | 8         | 1.02%   |
| Denmark     | 8         | 1.02%   |
| Switzerland | 7         | 0.89%   |
| Romania     | 7         | 0.89%   |
| Peru        | 7         | 0.89%   |
| Colombia    | 7         | 0.89%   |
| Turkey      | 6         | 0.77%   |
| Portugal    | 6         | 0.77%   |
| Uruguay     | 4         | 0.51%   |
| Sweden      | 4         | 0.51%   |
| Slovakia    | 4         | 0.51%   |
| Saint Lucia | 4         | 0.51%   |
| Norway      | 4         | 0.51%   |
| Bulgaria    | 4         | 0.51%   |
| Venezuela   | 3         | 0.38%   |
| Réunion    | 3         | 0.38%   |
| New Zealand | 3         | 0.38%   |
| Lithuania   | 3         | 0.38%   |
| Greece      | 3         | 0.38%   |
| Egypt       | 3         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Warsaw         | 11        | 1.4%    |
| Moscow         | 10        | 1.28%   |
| St Petersburg  | 7         | 0.89%   |
| Milan          | 7         | 0.89%   |
| Lima           | 6         | 0.77%   |
| Freeport       | 6         | 0.77%   |
| Cologne        | 6         | 0.77%   |
| Rome           | 5         | 0.64%   |
| Paris          | 5         | 0.64%   |
| Berlin         | 5         | 0.64%   |
| Wuppertal      | 4         | 0.51%   |
| Ufa            | 4         | 0.51%   |
| Rio de Janeiro | 4         | 0.51%   |
| Prague         | 4         | 0.51%   |
| Munich         | 4         | 0.51%   |
| Montpellier    | 4         | 0.51%   |
| Mexico City    | 4         | 0.51%   |
| Los Angeles    | 4         | 0.51%   |
| Krakow         | 4         | 0.51%   |
| Helsinki       | 4         | 0.51%   |
| Hamburg        | 4         | 0.51%   |
| Geneva         | 4         | 0.51%   |
| Cheltenham     | 4         | 0.51%   |
| Castries       | 4         | 0.51%   |
| Bucharest      | 4         | 0.51%   |
| Brisbane       | 4         | 0.51%   |
| Bengaluru      | 4         | 0.51%   |
| Amadora        | 4         | 0.51%   |
| Victoria       | 3         | 0.38%   |
| Tokyo          | 3         | 0.38%   |
| Sydney         | 3         | 0.38%   |
| Skierniewice   | 3         | 0.38%   |
| Seattle        | 3         | 0.38%   |
| Saint-Denis    | 3         | 0.38%   |
| Poznan         | 3         | 0.38%   |
| Motherwell     | 3         | 0.38%   |
| Montreal       | 3         | 0.38%   |
| Montevideo     | 3         | 0.38%   |
| Madrid         | 3         | 0.38%   |
| Lyon           | 3         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 124       | 129    | 13.01%  |
| Seagate             | 120       | 123    | 12.59%  |
| WDC                 | 102       | 105    | 10.7%   |
| Toshiba             | 82        | 83     | 8.6%    |
| Crucial             | 48        | 50     | 5.04%   |
| Kingston            | 44        | 44     | 4.62%   |
| Hitachi             | 43        | 43     | 4.51%   |
| SanDisk             | 40        | 42     | 4.2%    |
| Unknown             | 38        | 38     | 3.99%   |
| HGST                | 28        | 30     | 2.94%   |
| SK hynix            | 20        | 20     | 2.1%    |
| Intel               | 20        | 20     | 2.1%    |
| Micron Technology   | 18        | 18     | 1.89%   |
| SPCC                | 14        | 14     | 1.47%   |
| JMicron Technology  | 13        | 13     | 1.36%   |
| Transcend           | 12        | 12     | 1.26%   |
| China               | 12        | 12     | 1.26%   |
| A-DATA Technology   | 11        | 11     | 1.15%   |
| KIOXIA              | 9         | 9      | 0.94%   |
| PNY                 | 8         | 8      | 0.84%   |
| Phison              | 8         | 8      | 0.84%   |
| Netac               | 7         | 7      | 0.73%   |
| Intenso             | 7         | 7      | 0.73%   |
| GOODRAM             | 7         | 7      | 0.73%   |
| Patriot             | 6         | 6      | 0.63%   |
| KingSpec            | 6         | 6      | 0.63%   |
| Fujitsu             | 6         | 6      | 0.63%   |
| Apple               | 6         | 6      | 0.63%   |
| Verbatim            | 5         | 5      | 0.52%   |
| UMIS                | 4         | 4      | 0.42%   |
| SSSTC               | 4         | 4      | 0.42%   |
| LITEON              | 4         | 4      | 0.42%   |
| Gigabyte Technology | 4         | 4      | 0.42%   |
| Apacer              | 4         | 4      | 0.42%   |
| Silicon Motion      | 3         | 3      | 0.31%   |
| ShiJi               | 3         | 3      | 0.31%   |
| Unknown             | 3         | 3      | 0.31%   |
| Wibtek              | 2         | 2      | 0.21%   |
| WALRAM              | 2         | 2      | 0.21%   |
| SPCC Sol            | 2         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 16        | 1.65%   |
| Seagate ST500LT012-1DG142 500GB      | 15        | 1.55%   |
| Seagate ST1000LM035-1RK172 1TB       | 15        | 1.55%   |
| Toshiba MQ01ABF050 500GB             | 11        | 1.13%   |
| Kingston SA400S37480G 480GB SSD      | 10        | 1.03%   |
| Toshiba MQ04ABF100 1TB               | 9         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 0.93%   |
| Seagate ST9500325AS 500GB            | 8         | 0.82%   |
| Seagate ST1000LM048-2E7172 1TB       | 8         | 0.82%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 0.82%   |
| SPCC Solid State Disk 512GB          | 7         | 0.72%   |
| SanDisk NVMe SSD Drive 1TB           | 7         | 0.72%   |
| Crucial CT500MX500SSD1 500GB         | 7         | 0.72%   |
| Crucial CT480BX500SSD1 480GB         | 7         | 0.72%   |
| Unknown SD32G  32GB                  | 6         | 0.62%   |
| Samsung SSD 860 EVO 500GB            | 6         | 0.62%   |
| JMicron Generic 240GB                | 6         | 0.62%   |
| Crucial CT240BX500SSD1 240GB         | 6         | 0.62%   |
| Verbatim Vi550 S3 512GB              | 5         | 0.52%   |
| Unknown MMC64G  64GB                 | 5         | 0.52%   |
| Samsung SSD 980 PRO 1TB              | 5         | 0.52%   |
| Hitachi HTS723232A7A364 320GB        | 5         | 0.52%   |
| Hitachi HTS547575A9E384 752GB        | 5         | 0.52%   |
| Hitachi HTS545050B9A300 500GB        | 5         | 0.52%   |
| HGST HTS545050A7E680 500GB           | 5         | 0.52%   |
| HGST HTS541010A9E680 1TB             | 5         | 0.52%   |
| WDC WDS120G2G0A-00JH30 128GB SSD     | 4         | 0.41%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 4         | 0.41%   |
| Toshiba MQ01ABD075 752GB             | 4         | 0.41%   |
| SSSTC CL1-4D256 256GB                | 4         | 0.41%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 4         | 0.41%   |
| SanDisk SSD PLUS 1000GB              | 4         | 0.41%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.41%   |
| Samsung MZVLB512HBJQ-000 512GB       | 4         | 0.41%   |
| Netac SSD 256GB                      | 4         | 0.41%   |
| Kingston SA400S37120G 120GB SSD      | 4         | 0.41%   |
| JMicron H/W JBOD 512GB SSD           | 4         | 0.41%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 0.41%   |
| HGST HTS721010A9E630 1TB             | 4         | 0.41%   |
| HGST HTS545050A7E380 500GB           | 4         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 117       | 119    | 35.03%  |
| Toshiba             | 70        | 70     | 20.96%  |
| WDC                 | 59        | 59     | 17.66%  |
| Hitachi             | 43        | 43     | 12.87%  |
| HGST                | 28        | 30     | 8.38%   |
| Fujitsu             | 6         | 6      | 1.8%    |
| Samsung Electronics | 3         | 3      | 0.9%    |
| Unknown             | 2         | 2      | 0.6%    |
| ASMedia             | 2         | 2      | 0.6%    |
| Apple               | 2         | 2      | 0.6%    |
| USB3.0              | 1         | 1      | 0.3%    |
| LaCie               | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 61     | 17.05%  |
| Crucial             | 38        | 39     | 10.8%   |
| Kingston            | 31        | 31     | 8.81%   |
| SanDisk             | 25        | 25     | 7.1%    |
| WDC                 | 16        | 16     | 4.55%   |
| SPCC                | 13        | 13     | 3.69%   |
| China               | 12        | 12     | 3.41%   |
| Micron Technology   | 11        | 11     | 3.13%   |
| Transcend           | 10        | 10     | 2.84%   |
| Toshiba             | 9         | 9      | 2.56%   |
| SK hynix            | 8         | 8      | 2.27%   |
| A-DATA Technology   | 8         | 8      | 2.27%   |
| Netac               | 7         | 7      | 1.99%   |
| Intel               | 7         | 7      | 1.99%   |
| PNY                 | 6         | 6      | 1.7%    |
| Patriot             | 6         | 6      | 1.7%    |
| Intenso             | 6         | 6      | 1.7%    |
| GOODRAM             | 6         | 6      | 1.7%    |
| Verbatim            | 5         | 5      | 1.42%   |
| KingSpec            | 5         | 5      | 1.42%   |
| LITEON              | 4         | 4      | 1.14%   |
| JMicron Technology  | 4         | 4      | 1.14%   |
| ShiJi               | 3         | 3      | 0.85%   |
| Seagate             | 3         | 3      | 0.85%   |
| Gigabyte Technology | 3         | 3      | 0.85%   |
| Apacer              | 3         | 3      | 0.85%   |
| Wibtek              | 2         | 2      | 0.57%   |
| SPCC Sol            | 2         | 2      | 0.57%   |
| KingFast            | 2         | 2      | 0.57%   |
| KingDian            | 2         | 2      | 0.57%   |
| Emtec               | 2         | 2      | 0.57%   |
| Apple               | 2         | 2      | 0.57%   |
| Wdstars             | 1         | 1      | 0.28%   |
| WDC WDS2            | 1         | 1      | 0.28%   |
| walram              | 1         | 1      | 0.28%   |
| V7                  | 1         | 1      | 0.28%   |
| TO Exter            | 1         | 1      | 0.28%   |
| Teclast             | 1         | 1      | 0.28%   |
| Star                | 1         | 1      | 0.28%   |
| RX7                 | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 327       | 354    | 36.21%  |
| HDD     | 319       | 338    | 35.33%  |
| NVMe    | 206       | 227    | 22.81%  |
| MMC     | 42        | 43     | 4.65%   |
| Unknown | 9         | 9      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 586       | 661    | 66.97%  |
| NVMe | 198       | 218    | 22.63%  |
| SAS  | 49        | 49     | 5.6%    |
| MMC  | 42        | 43     | 4.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 434       | 475    | 68.03%  |
| 0.51-1.0   | 189       | 201    | 29.62%  |
| 1.01-2.0   | 13        | 14     | 2.04%   |
| 3.01-4.0   | 1         | 1      | 0.16%   |
| 4.01-10.0  | 1         | 1      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 253       | 32.27%  |
| 101-250        | 163       | 20.79%  |
| 251-500        | 154       | 19.64%  |
| 501-1000       | 68        | 8.67%   |
| 51-100         | 48        | 6.12%   |
| 21-50          | 43        | 5.48%   |
| Unknown        | 24        | 3.06%   |
| 1001-2000      | 19        | 2.42%   |
| 2001-3000      | 8         | 1.02%   |
| More than 3000 | 4         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 626       | 79.85%  |
| 21-50          | 56        | 7.14%   |
| 101-250        | 27        | 3.44%   |
| 51-100         | 26        | 3.32%   |
| Unknown        | 24        | 3.06%   |
| 251-500        | 13        | 1.66%   |
| 501-1000       | 8         | 1.02%   |
| 1001-2000      | 3         | 0.38%   |
| More than 3000 | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB      | 6         | 6      | 3.64%   |
| Seagate ST9500325AS 500GB            | 5         | 5      | 3.03%   |
| Hitachi HTS723232A7A364 320GB        | 5         | 5      | 3.03%   |
| Toshiba MQ01ABD100 1TB               | 4         | 4      | 2.42%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 4      | 2.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 4      | 2.42%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 2.42%   |
| HGST HTS545050A7E680 500GB           | 4         | 4      | 2.42%   |
| HGST HTS541010A9E680 1TB             | 4         | 4      | 2.42%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 1.82%   |
| HGST HTS545050A7E380 500GB           | 3         | 3      | 1.82%   |
| Toshiba MQ01ABD050 500GB             | 2         | 2      | 1.21%   |
| Toshiba MK5075GSX 500GB              | 2         | 2      | 1.21%   |
| Toshiba MK5065GSX 500GB              | 2         | 2      | 1.21%   |
| Toshiba MK2529GSG 250GB              | 2         | 2      | 1.21%   |
| Toshiba MK1652GSX 160GB              | 2         | 2      | 1.21%   |
| Seagate ST9750420AS 752GB            | 2         | 2      | 1.21%   |
| Seagate ST320LT012-1DG14C 320GB      | 2         | 2      | 1.21%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 2      | 1.21%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 2      | 1.21%   |
| LITEON CV8-8E128-HP 128GB SSD        | 2         | 2      | 1.21%   |
| Hitachi HTS543232L9A300 320GB        | 2         | 2      | 1.21%   |
| WDC WD7500BPVT-24HXZT1 752GB         | 1         | 1      | 0.61%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 1      | 0.61%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 1      | 0.61%   |
| WDC WD5000BEVT-26A0RT0 500GB         | 1         | 1      | 0.61%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 1      | 0.61%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 1      | 0.61%   |
| WDC WD3200BUDT-63DPZY0 320GB         | 1         | 1      | 0.61%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 1      | 0.61%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 0.61%   |
| WDC WD3200BEVT-75ZCT0 320GB          | 1         | 1      | 0.61%   |
| WDC WD3200BEVT-26ZCT0 320GB          | 1         | 1      | 0.61%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1      | 0.61%   |
| WDC WD3200BEKT-75PVMT0 320GB         | 1         | 1      | 0.61%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 1      | 0.61%   |
| WDC WD20SPZX-60UA7T0 2TB             | 1         | 1      | 0.61%   |
| WDC WD Blue SA510 M.2 2280 500GB SSD | 1         | 1      | 0.61%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1      | 0.61%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 43     | 26.22%  |
| Toshiba             | 25        | 25     | 15.24%  |
| Hitachi             | 24        | 24     | 14.63%  |
| HGST                | 19        | 20     | 11.59%  |
| WDC                 | 16        | 16     | 9.76%   |
| SK hynix            | 5         | 5      | 3.05%   |
| Intel               | 5         | 5      | 3.05%   |
| Fujitsu             | 4         | 4      | 2.44%   |
| KingSpec            | 3         | 3      | 1.83%   |
| SPCC                | 2         | 2      | 1.22%   |
| Samsung Electronics | 2         | 2      | 1.22%   |
| LITEON              | 2         | 2      | 1.22%   |
| Intenso             | 2         | 2      | 1.22%   |
| China               | 2         | 2      | 1.22%   |
| A-DATA Technology   | 2         | 2      | 1.22%   |
| Teclast             | 1         | 1      | 0.61%   |
| SanDisk             | 1         | 1      | 0.61%   |
| Plextor             | 1         | 1      | 0.61%   |
| Netac               | 1         | 1      | 0.61%   |
| Micron Technology   | 1         | 1      | 0.61%   |
| Kingston            | 1         | 1      | 0.61%   |
| Crucial             | 1         | 1      | 0.61%   |
| Apple               | 1         | 1      | 0.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 43     | 32.82%  |
| Toshiba             | 24        | 24     | 18.32%  |
| Hitachi             | 24        | 24     | 18.32%  |
| HGST                | 19        | 20     | 14.5%   |
| WDC                 | 15        | 15     | 11.45%  |
| Fujitsu             | 4         | 4      | 3.05%   |
| Samsung Electronics | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 130       | 132    | 79.75%  |
| SSD  | 29        | 29     | 17.79%  |
| NVMe | 4         | 4      | 2.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MK3261GSYN 320GB   | 1         | 1      | 50%     |
| HGST HTS545050B7E660 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 616       | 709    | 70.97%  |
| Malfunc  | 160       | 165    | 18.43%  |
| Detected | 90        | 95     | 10.37%  |
| Failed   | 2         | 2      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 580       | 64.44%  |
| AMD                                     | 112       | 12.44%  |
| Samsung Electronics                     | 65        | 7.22%   |
| SanDisk                                 | 40        | 4.44%   |
| Kingston Technology Company             | 14        | 1.56%   |
| Phison Electronics                      | 13        | 1.44%   |
| SK hynix                                | 12        | 1.33%   |
| Micron/Crucial Technology               | 10        | 1.11%   |
| KIOXIA                                  | 9         | 1%      |
| Micron Technology                       | 7         | 0.78%   |
| Silicon Motion                          | 6         | 0.67%   |
| ADATA Technology                        | 5         | 0.56%   |
| Toshiba America Info Systems            | 4         | 0.44%   |
| Solid State Storage Technology          | 4         | 0.44%   |
| Nvidia                                  | 4         | 0.44%   |
| Union Memory (Shenzhen)                 | 3         | 0.33%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.22%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.22%   |
| Transcend                               | 1         | 0.11%   |
| Shenzhen Unionmemory Information System | 1         | 0.11%   |
| Shenzhen Longsys Electronics            | 1         | 0.11%   |
| Realtek Semiconductor                   | 1         | 0.11%   |
| Lenovo                                  | 1         | 0.11%   |
| JMicron Technology                      | 1         | 0.11%   |
| Biwin Storage Technology                | 1         | 0.11%   |
| Apple                                   | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 89        | 9.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 76        | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 71        | 7.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 52        | 5.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 38        | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 37        | 3.74%   |
| Intel Volume Management Device NVMe RAID Controller                              | 33        | 3.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 29        | 2.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 28        | 2.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 26        | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 25        | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 2.23%   |
| Samsung NVMe SSD Controller 980                                                  | 22        | 2.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 22        | 2.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 22        | 2.23%   |
| Intel Tiger Lake-LP SATA Controller                                              | 19        | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 17        | 1.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 16        | 1.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 16        | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 15        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 1.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 9         | 0.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 0.91%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 9         | 0.91%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 8         | 0.81%   |
| Intel Non-Volatile memory controller                                             | 8         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.81%   |
| Phison PS5013 E13 NVMe Controller                                                | 7         | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 6         | 0.61%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 6         | 0.61%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 6         | 0.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 0.61%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 5         | 0.51%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 5         | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 621       | 65.03%  |
| NVMe | 198       | 20.73%  |
| RAID | 72        | 7.54%   |
| IDE  | 64        | 6.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 634       | 80.87%  |
| AMD    | 150       | 19.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 13        | 1.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 1.53%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 11        | 1.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 1.28%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 1.28%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 10        | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 1.15%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 9         | 1.15%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 8         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 1.02%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 8         | 1.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 1.02%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 8         | 1.02%   |
| AMD 3020e with Radeon Graphics                | 8         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.89%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 7         | 0.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.77%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.77%   |
| Intel 12th Gen Core i7-12700H                 | 6         | 0.77%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 6         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.64%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 5         | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.64%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 5         | 0.64%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 5         | 0.64%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.64%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 5         | 0.64%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.64%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 5         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 174       | 22.19%  |
| Intel Core i7                  | 120       | 15.31%  |
| Intel Core i3                  | 87        | 11.1%   |
| Intel Celeron                  | 74        | 9.44%   |
| Other                          | 66        | 8.42%   |
| Intel Core 2 Duo               | 52        | 6.63%   |
| Intel Pentium                  | 32        | 4.08%   |
| AMD Ryzen 5                    | 30        | 3.83%   |
| AMD Ryzen 7                    | 21        | 2.68%   |
| AMD Ryzen 3                    | 17        | 2.17%   |
| Intel Pentium Dual             | 9         | 1.15%   |
| Intel Pentium Dual-Core        | 8         | 1.02%   |
| AMD A6                         | 8         | 1.02%   |
| AMD A8                         | 7         | 0.89%   |
| AMD A4                         | 6         | 0.77%   |
| AMD E                          | 5         | 0.64%   |
| AMD A10                        | 5         | 0.64%   |
| Intel Pentium Silver           | 4         | 0.51%   |
| Intel Core 2                   | 4         | 0.51%   |
| AMD Ryzen 9                    | 4         | 0.51%   |
| AMD E1                         | 4         | 0.51%   |
| AMD Athlon                     | 4         | 0.51%   |
| Intel Pentium Gold             | 3         | 0.38%   |
| Intel Core i9                  | 3         | 0.38%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.38%   |
| AMD C-70                       | 3         | 0.38%   |
| AMD A12                        | 3         | 0.38%   |
| Intel Genuine                  | 2         | 0.26%   |
| Intel Celeron Dual-Core        | 2         | 0.26%   |
| Intel Atom                     | 2         | 0.26%   |
| AMD Ryzen 7 PRO                | 2         | 0.26%   |
| AMD Phenom II                  | 2         | 0.26%   |
| AMD E2                         | 2         | 0.26%   |
| AMD C-60                       | 2         | 0.26%   |
| AMD Athlon X2                  | 2         | 0.26%   |
| AMD Athlon 64 X2               | 2         | 0.26%   |
| Intel Core m5                  | 1         | 0.13%   |
| Intel Core m3                  | 1         | 0.13%   |
| AMD V120                       | 1         | 0.13%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 511       | 65.18%  |
| 4      | 180       | 22.96%  |
| 8      | 32        | 4.08%   |
| 6      | 31        | 3.95%   |
| 1      | 18        | 2.3%    |
| 14     | 9         | 1.15%   |
| 10     | 2         | 0.26%   |
| 12     | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 784       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 521       | 66.45%  |
| 1      | 256       | 32.65%  |
| 4      | 5         | 0.64%   |
| 16     | 1         | 0.13%   |
| 8      | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 784       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 637       | 81.25%  |
| 0x08108109 | 20        | 2.55%   |
| 0x0a50000c | 13        | 1.66%   |
| 0x08608103 | 13        | 1.66%   |
| 0x08200103 | 8         | 1.02%   |
| 0x06006705 | 8         | 1.02%   |
| 0x08108102 | 7         | 0.89%   |
| 0x0500010d | 7         | 0.89%   |
| 0x0a50000d | 5         | 0.64%   |
| 0x0600611a | 5         | 0.64%   |
| 0x05000101 | 5         | 0.64%   |
| 0x08600106 | 4         | 0.51%   |
| 0x0700010b | 4         | 0.51%   |
| 0x06001119 | 4         | 0.51%   |
| 0x08608102 | 3         | 0.38%   |
| 0x0810100b | 3         | 0.38%   |
| 0x07030105 | 3         | 0.38%   |
| 0x08600104 | 2         | 0.26%   |
| 0x0600111f | 2         | 0.26%   |
| 0x0600110f | 2         | 0.26%   |
| 0x03000027 | 2         | 0.26%   |
| 0x02000057 | 2         | 0.26%   |
| 0x02000032 | 2         | 0.26%   |
| 0x010000c8 | 2         | 0.26%   |
| 0x010000b6 | 2         | 0.26%   |
| 0x906a3    | 1         | 0.13%   |
| 0x806e9    | 1         | 0.13%   |
| 0x506c9    | 1         | 0.13%   |
| 0x406e3    | 1         | 0.13%   |
| 0x306a9    | 1         | 0.13%   |
| 0x206a7    | 1         | 0.13%   |
| 0x0a50000b | 1         | 0.13%   |
| 0x0a404102 | 1         | 0.13%   |
| 0x08a00006 | 1         | 0.13%   |
| 0x08900201 | 1         | 0.13%   |
| 0x08600103 | 1         | 0.13%   |
| 0x08600102 | 1         | 0.13%   |
| 0x08101007 | 1         | 0.13%   |
| 0x07030106 | 1         | 0.13%   |
| 0x07000110 | 1         | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 101       | 12.88%  |
| IvyBridge        | 71        | 9.06%   |
| SandyBridge      | 62        | 7.91%   |
| Skylake          | 48        | 6.12%   |
| Haswell          | 46        | 5.87%   |
| Penryn           | 45        | 5.74%   |
| Westmere         | 39        | 4.97%   |
| TigerLake        | 37        | 4.72%   |
| Core             | 35        | 4.46%   |
| Silvermont       | 34        | 4.34%   |
| Broadwell        | 33        | 4.21%   |
| Zen+             | 27        | 3.44%   |
| Goldmont plus    | 25        | 3.19%   |
| Zen 3            | 19        | 2.42%   |
| Unknown          | 19        | 2.42%   |
| Icelake          | 17        | 2.17%   |
| Excavator        | 15        | 1.91%   |
| Alderlake Hybrid | 14        | 1.79%   |
| Bobcat           | 13        | 1.66%   |
| Zen              | 12        | 1.53%   |
| Goldmont         | 10        | 1.28%   |
| CometLake        | 10        | 1.28%   |
| Zen 2            | 9         | 1.15%   |
| Piledriver       | 9         | 1.15%   |
| K8 Hammer        | 7         | 0.89%   |
| K10              | 5         | 0.64%   |
| Jaguar           | 5         | 0.64%   |
| Puma             | 4         | 0.51%   |
| K8 & K10 hybrid  | 4         | 0.51%   |
| Tremont          | 3         | 0.38%   |
| Nehalem          | 3         | 0.38%   |
| K10 Llano        | 2         | 0.26%   |
| Bonnell          | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 573       | 61.02%  |
| AMD                              | 198       | 21.09%  |
| Nvidia                           | 166       | 17.68%  |
| Silicon Integrated Systems [SiS] | 2         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 6.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 57        | 5.85%   |
| Intel HD Graphics 620                                                                    | 36        | 3.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 35        | 3.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 3.59%   |
| Intel HD Graphics 5500                                                                   | 29        | 2.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 2.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 2.57%   |
| Intel UHD Graphics 620                                                                   | 22        | 2.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 2.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 1.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 1.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.64%   |
| AMD Lucienne                                                                             | 16        | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.64%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 1.54%   |
| Intel HD Graphics 530                                                                    | 15        | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.44%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 10        | 1.03%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.82%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 8         | 0.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.82%   |
| AMD Renoir                                                                               | 8         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.72%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 6         | 0.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.62%   |
| Intel HD Graphics 500                                                                    | 6         | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 376       | 47.96%  |
| 1 x AMD        | 142       | 18.11%  |
| Intel + Nvidia | 115       | 14.67%  |
| 2 x Intel      | 56        | 7.14%   |
| 1 x Nvidia     | 37        | 4.72%   |
| Intel + AMD    | 26        | 3.32%   |
| 2 x AMD        | 16        | 2.04%   |
| AMD + Nvidia   | 14        | 1.79%   |
| 1 x SiS        | 2         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 758       | 96.68%  |
| Proprietary | 19        | 2.42%   |
| Unknown     | 7         | 0.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 450       | 57.4%   |
| 0.01-0.5   | 114       | 14.54%  |
| 1.01-2.0   | 99        | 12.63%  |
| 3.01-4.0   | 50        | 6.38%   |
| 0.51-1.0   | 49        | 6.25%   |
| 5.01-6.0   | 11        | 1.4%    |
| 7.01-8.0   | 6         | 0.77%   |
| 8.01-16.0  | 4         | 0.51%   |
| 2.01-3.0   | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 188       | 23.21%  |
| LG Display              | 130       | 16.05%  |
| Chimei Innolux          | 118       | 14.57%  |
| BOE                     | 117       | 14.44%  |
| Samsung Electronics     | 76        | 9.38%   |
| Lenovo                  | 22        | 2.72%   |
| Sharp                   | 20        | 2.47%   |
| LG Philips              | 16        | 1.98%   |
| Chi Mei Optoelectronics | 16        | 1.98%   |
| Apple                   | 13        | 1.6%    |
| PANDA                   | 12        | 1.48%   |
| Hewlett-Packard         | 6         | 0.74%   |
| HannStar                | 6         | 0.74%   |
| Dell                    | 6         | 0.74%   |
| AOC                     | 6         | 0.74%   |
| Sony                    | 4         | 0.49%   |
| HKC                     | 4         | 0.49%   |
| Goldstar                | 4         | 0.49%   |
| CSO                     | 4         | 0.49%   |
| Unknown                 | 3         | 0.37%   |
| Philips                 | 3         | 0.37%   |
| InfoVision              | 3         | 0.37%   |
| Hitachi                 | 3         | 0.37%   |
| Acer                    | 3         | 0.37%   |
| Toppoly                 | 2         | 0.25%   |
| Panasonic               | 2         | 0.25%   |
| InnoLux Display         | 2         | 0.25%   |
| Xiaomi                  | 1         | 0.12%   |
| Vizio                   | 1         | 0.12%   |
| ViewSonic               | 1         | 0.12%   |
| Vestel Elektronik       | 1         | 0.12%   |
| Valve                   | 1         | 0.12%   |
| TMX                     | 1         | 0.12%   |
| STA                     | 1         | 0.12%   |
| Sceptre Tech            | 1         | 0.12%   |
| QUS                     | 1         | 0.12%   |
| MTD                     | 1         | 0.12%   |
| L                       | 1         | 0.12%   |
| Konka                   | 1         | 0.12%   |
| KDC                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 12        | 1.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 10        | 1.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 10        | 1.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 9         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.86%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.86%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 6         | 0.74%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 6         | 0.74%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 6         | 0.74%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 5         | 0.62%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 5         | 0.62%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 5         | 0.62%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 5         | 0.62%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 4         | 0.49%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 4         | 0.49%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.49%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch         | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 4         | 0.49%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.37%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch               | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 3         | 0.37%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 3         | 0.37%   |
| LG Philips LCD Monitor LPLA104 1440x900 367x230mm 17.1-inch           | 3         | 0.37%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 3         | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 308       | 38.69%  |
| 1920x1080 (FHD)    | 300       | 37.69%  |
| 1600x900 (HD+)     | 44        | 5.53%   |
| 1280x800 (WXGA)    | 42        | 5.28%   |
| 3840x2160 (4K)     | 18        | 2.26%   |
| 1440x900 (WXGA+)   | 18        | 2.26%   |
| 2560x1600          | 13        | 1.63%   |
| 2560x1440 (QHD)    | 11        | 1.38%   |
| 1920x1200 (WUXGA)  | 10        | 1.26%   |
| 3840x2400          | 4         | 0.5%    |
| 1680x1050 (WSXGA+) | 4         | 0.5%    |
| 2288x1287          | 3         | 0.38%   |
| 2160x1440          | 3         | 0.38%   |
| 3440x1440          | 2         | 0.25%   |
| 3200x1800 (QHD+)   | 2         | 0.25%   |
| 2880x1800          | 2         | 0.25%   |
| 800x1280           | 1         | 0.13%   |
| 3456x2160          | 1         | 0.13%   |
| 2240x1400          | 1         | 0.13%   |
| 2160x1350          | 1         | 0.13%   |
| 1920x540           | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1600x2560          | 1         | 0.13%   |
| 1400x1050          | 1         | 0.13%   |
| 1360x768           | 1         | 0.13%   |
| 1280x1024 (SXGA)   | 1         | 0.13%   |
| 1024x768 (XGA)     | 1         | 0.13%   |
| 1024x600           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 393       | 48.4%   |
| 13      | 104       | 12.81%  |
| 14      | 101       | 12.44%  |
| 17      | 75        | 9.24%   |
| 12      | 27        | 3.33%   |
| 11      | 20        | 2.46%   |
| 16      | 15        | 1.85%   |
| 27      | 11        | 1.35%   |
| 23      | 11        | 1.35%   |
| 24      | 9         | 1.11%   |
| 21      | 7         | 0.86%   |
| 31      | 6         | 0.74%   |
| 18      | 5         | 0.62%   |
| 142     | 3         | 0.37%   |
| 84      | 3         | 0.37%   |
| 65      | 2         | 0.25%   |
| 52      | 2         | 0.25%   |
| 32      | 2         | 0.25%   |
| Unknown | 2         | 0.25%   |
| 72      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 54      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 36      | 1         | 0.12%   |
| 35      | 1         | 0.12%   |
| 34      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |
| 22      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |
| 19      | 1         | 0.12%   |
| 8       | 1         | 0.12%   |
| 7       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 566       | 69.79%  |
| 351-400        | 86        | 10.6%   |
| 201-300        | 84        | 10.36%  |
| 501-600        | 30        | 3.7%    |
| 401-500        | 15        | 1.85%   |
| 601-700        | 7         | 0.86%   |
| 1001-1500      | 7         | 0.86%   |
| 701-800        | 4         | 0.49%   |
| 1501-2000      | 4         | 0.49%   |
| More than 2000 | 3         | 0.37%   |
| Unknown        | 2         | 0.25%   |
| 801-900        | 1         | 0.12%   |
| 101-200        | 1         | 0.12%   |
| 1-100          | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 651       | 85.1%   |
| 16/10   | 95        | 12.42%  |
| 3/2     | 8         | 1.05%   |
| 1.00    | 3         | 0.39%   |
| 4/3     | 2         | 0.26%   |
| 21/9    | 2         | 0.26%   |
| 5/4     | 1         | 0.13%   |
| 0.67    | 1         | 0.13%   |
| 0.63    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 395       | 48.65%  |
| 81-90          | 171       | 21.06%  |
| 121-130        | 56        | 6.9%    |
| 71-80          | 34        | 4.19%   |
| 61-70          | 26        | 3.2%    |
| 201-250        | 24        | 2.96%   |
| 51-60          | 20        | 2.46%   |
| 131-140        | 19        | 2.34%   |
| More than 1000 | 13        | 1.6%    |
| 351-500        | 11        | 1.35%   |
| 301-350        | 11        | 1.35%   |
| 111-120        | 11        | 1.35%   |
| 141-150        | 5         | 0.62%   |
| 251-300        | 4         | 0.49%   |
| 151-200        | 3         | 0.37%   |
| 91-100         | 3         | 0.37%   |
| 1-40           | 2         | 0.25%   |
| 501-1000       | 2         | 0.25%   |
| Unknown        | 2         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 318       | 39.45%  |
| 121-160       | 317       | 39.33%  |
| 51-100        | 98        | 12.16%  |
| 161-240       | 45        | 5.58%   |
| More than 240 | 16        | 1.99%   |
| 1-50          | 10        | 1.24%   |
| Unknown       | 2         | 0.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 713       | 90.94%  |
| 2     | 65        | 8.29%   |
| 0     | 5         | 0.64%   |
| 3     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 429       | 35.05%  |
| Intel                             | 403       | 32.92%  |
| Qualcomm Atheros                  | 195       | 15.93%  |
| Broadcom                          | 69        | 5.64%   |
| Broadcom Limited                  | 18        | 1.47%   |
| MediaTek                          | 16        | 1.31%   |
| Ralink                            | 13        | 1.06%   |
| Marvell Technology Group          | 12        | 0.98%   |
| TP-Link                           | 11        | 0.9%    |
| Ralink Technology                 | 7         | 0.57%   |
| Dell                              | 6         | 0.49%   |
| Sierra Wireless                   | 4         | 0.33%   |
| Nvidia                            | 4         | 0.33%   |
| NetGear                           | 3         | 0.25%   |
| JMicron Technology                | 3         | 0.25%   |
| Ericsson Business Mobile Networks | 3         | 0.25%   |
| Xiaomi                            | 2         | 0.16%   |
| T & A Mobile Phones               | 2         | 0.16%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.16%   |
| Qualcomm Atheros Communications   | 2         | 0.16%   |
| Linksys                           | 2         | 0.16%   |
| ICS Advent                        | 2         | 0.16%   |
| ASIX Electronics                  | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.08%   |
| Samsung Electronics               | 1         | 0.08%   |
| Qualcomm                          | 1         | 0.08%   |
| PLANEX                            | 1         | 0.08%   |
| Microsoft                         | 1         | 0.08%   |
| LG Electronics                    | 1         | 0.08%   |
| Lenovo                            | 1         | 0.08%   |
| Huawei Technologies               | 1         | 0.08%   |
| Holtek Semiconductor              | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |
| Attansic Technology               | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |
| Apple                             | 1         | 0.08%   |
| Android                           | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 247       | 16.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 89        | 6.03%   |
| Intel Wireless 7265                                                     | 40        | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 36        | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 33        | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 32        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 2.1%    |
| Intel Wi-Fi 6 AX201                                                     | 29        | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 26        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 24        | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.56%   |
| Intel Wireless 8265 / 8275                                              | 23        | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 22        | 1.49%   |
| Intel Wireless 3165                                                     | 20        | 1.36%   |
| Intel Wireless 8260                                                     | 18        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.02%   |
| Intel Wireless 7260                                                     | 15        | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 0.95%   |
| Intel Wireless 3160                                                     | 14        | 0.95%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                                   | 13        | 0.88%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 12        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 11        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                   | 11        | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.75%   |
| Intel WiFi Link 5100                                                    | 10        | 0.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.68%   |
| Intel Centrino Advanced-N 6200                                          | 10        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                | 10        | 0.68%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 9         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 9         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 391       | 48.27%  |
| Qualcomm Atheros                | 168       | 20.74%  |
| Realtek Semiconductor           | 142       | 17.53%  |
| Broadcom                        | 48        | 5.93%   |
| MediaTek                        | 15        | 1.85%   |
| Ralink                          | 13        | 1.6%    |
| Ralink Technology               | 7         | 0.86%   |
| Broadcom Limited                | 5         | 0.62%   |
| Sierra Wireless                 | 4         | 0.49%   |
| TP-Link                         | 3         | 0.37%   |
| Dell                            | 3         | 0.37%   |
| Qualcomm Atheros Communications | 2         | 0.25%   |
| NetGear                         | 2         | 0.25%   |
| Linksys                         | 2         | 0.25%   |
| Qualcomm                        | 1         | 0.12%   |
| PLANEX                          | 1         | 0.12%   |
| Microsoft                       | 1         | 0.12%   |
| D-Link System                   | 1         | 0.12%   |
| ASUSTek Computer                | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 40        | 4.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 36        | 4.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 33        | 4.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 3.81%   |
| Intel Wi-Fi 6 AX201                                                     | 29        | 3.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 27        | 3.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 24        | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.83%   |
| Intel Wireless 8265 / 8275                                              | 23        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 22        | 2.7%    |
| Intel Wireless 3165                                                     | 20        | 2.46%   |
| Intel Wireless 8260                                                     | 18        | 2.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 1.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.84%   |
| Intel Wireless 7260                                                     | 15        | 1.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.72%   |
| Intel Wireless 3160                                                     | 14        | 1.72%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.6%    |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 1.6%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 12        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 11        | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.35%   |
| Intel WiFi Link 5100                                                    | 10        | 1.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 1.23%   |
| Intel Centrino Advanced-N 6200                                          | 10        | 1.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 9         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 1.11%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.98%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 370       | 57.45%  |
| Intel                            | 133       | 20.65%  |
| Qualcomm Atheros                 | 53        | 8.23%   |
| Broadcom                         | 33        | 5.12%   |
| Broadcom Limited                 | 14        | 2.17%   |
| Marvell Technology Group         | 12        | 1.86%   |
| TP-Link                          | 8         | 1.24%   |
| Nvidia                           | 4         | 0.62%   |
| JMicron Technology               | 3         | 0.47%   |
| Xiaomi                           | 2         | 0.31%   |
| Silicon Integrated Systems [SiS] | 2         | 0.31%   |
| ICS Advent                       | 2         | 0.31%   |
| ASIX Electronics                 | 2         | 0.31%   |
| NetGear                          | 1         | 0.16%   |
| MediaTek                         | 1         | 0.16%   |
| LG Electronics                   | 1         | 0.16%   |
| Lenovo                           | 1         | 0.16%   |
| Attansic Technology              | 1         | 0.16%   |
| Apple                            | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 247       | 38.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 89        | 13.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 32        | 4.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 26        | 4.01%   |
| Intel Ethernet Connection (3) I218-LM                                          | 13        | 2.01%   |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 1.7%    |
| Intel 82567LM Gigabit Network Connection                                       | 10        | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 9         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 1.39%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 8         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 8         | 1.23%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 1.23%   |
| Intel 82566MM Gigabit Network Connection                                       | 7         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 6         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.93%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.93%   |
| Intel 82579V Gigabit Network Connection                                        | 6         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 6         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.77%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.77%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 4         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.46%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.46%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.46%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.46%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 0.46%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 3         | 0.46%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 3         | 0.46%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 2         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 778       | 54.56%  |
| Ethernet | 634       | 44.46%  |
| Modem    | 11        | 0.77%   |
| Unknown  | 3         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 583       | 75.71%  |
| Ethernet | 186       | 24.16%  |
| Modem    | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 582       | 74.23%  |
| 1     | 183       | 23.34%  |
| 0     | 17        | 2.17%   |
| 3     | 2         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 515       | 65.69%  |
| Yes  | 269       | 34.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 283       | 46.78%  |
| Realtek Semiconductor           | 67        | 11.07%  |
| Qualcomm Atheros Communications | 58        | 9.59%   |
| Broadcom                        | 36        | 5.95%   |
| IMC Networks                    | 33        | 5.45%   |
| Lite-On Technology              | 31        | 5.12%   |
| Foxconn / Hon Hai               | 18        | 2.98%   |
| Toshiba                         | 15        | 2.48%   |
| Hewlett-Packard                 | 15        | 2.48%   |
| Apple                           | 11        | 1.82%   |
| Dell                            | 10        | 1.65%   |
| Cambridge Silicon Radio         | 8         | 1.32%   |
| ASUSTek Computer                | 6         | 0.99%   |
| Ralink                          | 5         | 0.83%   |
| Realtek                         | 4         | 0.66%   |
| Chicony Electronics             | 2         | 0.33%   |
| Qcom                            | 1         | 0.17%   |
| Fujitsu                         | 1         | 0.17%   |
| Foxconn International           | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 135       | 22.31%  |
| Realtek Bluetooth Radio                             | 45        | 7.44%   |
| Intel AX201 Bluetooth                               | 44        | 7.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 43        | 7.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 26        | 4.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 2.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 2.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 2.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 2.15%   |
| Intel AX200 Bluetooth                               | 13        | 2.15%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 1.49%   |
| IMC Networks Wireless_Device                        | 9         | 1.49%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                         | 8         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.16%   |
| IMC Networks Bluetooth Device                       | 7         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.16%   |
| Intel AX210 Bluetooth                               | 6         | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.99%   |
| Apple Bluetooth Host Controller                     | 6         | 0.99%   |
| Toshiba Bluetooth Device                            | 5         | 0.83%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.83%   |
| Intel Bluetooth Device                              | 5         | 0.83%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.83%   |
| Realtek Bluetooth Radio                             | 4         | 0.66%   |
| Lite-On Wireless_Device                             | 4         | 0.66%   |
| IMC Networks Bluetooth                              | 4         | 0.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 0.66%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.5%    |
| Toshiba Askey Bluetooth Module                      | 3         | 0.5%    |
| Lite-On Bluetooth Device                            | 3         | 0.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.5%    |
| Foxconn / Hon Hai Acer Bluetooth module             | 3         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 628       | 69.01%  |
| AMD                              | 168       | 18.46%  |
| Nvidia                           | 87        | 9.56%   |
| Generalplus Technology           | 6         | 0.66%   |
| C-Media Electronics              | 5         | 0.55%   |
| Texas Instruments                | 2         | 0.22%   |
| Silicon Integrated Systems [SiS] | 2         | 0.22%   |
| JMTek                            | 2         | 0.22%   |
| THX                              | 1         | 0.11%   |
| PreSonus Audio Electronics       | 1         | 0.11%   |
| No brand                         | 1         | 0.11%   |
| Lenovo                           | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |
| GN Netcom                        | 1         | 0.11%   |
| EDIFIER                          | 1         | 0.11%   |
| Creative Technology              | 1         | 0.11%   |
| Corsair                          | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 90        | 8.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 83        | 7.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 76        | 6.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 57        | 5.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 45        | 4.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 42        | 3.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 38        | 3.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 37        | 3.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 35        | 3.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 33        | 2.96%   |
| Intel Broadwell-U Audio Controller                                                                | 33        | 2.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 28        | 2.51%   |
| Intel 8 Series HD Audio Controller                                                                | 28        | 2.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 26        | 2.33%   |
| AMD FCH Azalia Controller                                                                         | 26        | 2.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 25        | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 1.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 18        | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 0.99%   |
| AMD Wrestler HDMI Audio                                                                           | 11        | 0.99%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 9         | 0.81%   |
| AMD High Definition Audio Controller                                                              | 9         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.72%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 250       | 25.35%  |
| SK hynix                                         | 214       | 21.7%   |
| Micron Technology                                | 125       | 12.68%  |
| Kingston                                         | 89        | 9.03%   |
| Unknown                                          | 65        | 6.59%   |
| Crucial                                          | 35        | 3.55%   |
| Nanya Technology                                 | 25        | 2.54%   |
| Ramaxel Technology                               | 24        | 2.43%   |
| Elpida                                           | 23        | 2.33%   |
| Unknown (ABCD)                                   | 20        | 2.03%   |
| A-DATA Technology                                | 18        | 1.83%   |
| Corsair                                          | 9         | 0.91%   |
| Unknown                                          | 9         | 0.91%   |
| Transcend                                        | 8         | 0.81%   |
| Smart                                            | 7         | 0.71%   |
| Team                                             | 5         | 0.51%   |
| G.Skill                                          | 5         | 0.51%   |
| Qimonda                                          | 4         | 0.41%   |
| Patriot                                          | 4         | 0.41%   |
| Teikon                                           | 3         | 0.3%    |
| Innodisk                                         | 3         | 0.3%    |
| GOODRAM                                          | 3         | 0.3%    |
| Apacer                                           | 3         | 0.3%    |
| Unknown (0x48594D503132355336344350382D53362020) | 2         | 0.2%    |
| Timetec                                          | 2         | 0.2%    |
| Sesame                                           | 2         | 0.2%    |
| Neo Forza                                        | 2         | 0.2%    |
| Avant                                            | 2         | 0.2%    |
| Wilk                                             | 1         | 0.1%    |
| Walton Chaintech                                 | 1         | 0.1%    |
| Unknown (0xAD0A)                                 | 1         | 0.1%    |
| Unknown (0x48594D503131325336344350362D53362020) | 1         | 0.1%    |
| Unknown (0x31364854463235363634485A2D3830304831) | 1         | 0.1%    |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.1%    |
| Unknown (081A)                                   | 1         | 0.1%    |
| Toshiba                                          | 1         | 0.1%    |
| SHARETRONIC                                      | 1         | 0.1%    |
| Qumo                                             | 1         | 0.1%    |
| PUSKILL                                          | 1         | 0.1%    |
| PNY                                              | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 19        | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 17        | 1.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 1.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 1.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 1.44%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 15        | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 1.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.15%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 1.05%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 11        | 1.05%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 9         | 0.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 9         | 0.86%   |
| Unknown                                                          | 9         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.77%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 8         | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.67%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 7         | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 7         | 0.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.67%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 7         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 6         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 6         | 0.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 5         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 5         | 0.48%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.48%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 5         | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.48%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.48%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 343       | 42.77%  |
| DDR4    | 301       | 37.53%  |
| DDR2    | 62        | 7.73%   |
| LPDDR4  | 41        | 5.11%   |
| SDRAM   | 28        | 3.49%   |
| DDR     | 6         | 0.75%   |
| LPDDR3  | 5         | 0.62%   |
| DRAM    | 5         | 0.62%   |
| DDR5    | 4         | 0.5%    |
| Unknown | 4         | 0.5%    |
| LPDDR5  | 3         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 730       | 91.71%  |
| Row Of Chips | 50        | 6.28%   |
| DIMM         | 7         | 0.88%   |
| Unknown      | 7         | 0.88%   |
| Chip         | 2         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 342       | 37.67%  |
| 8192  | 285       | 31.39%  |
| 2048  | 161       | 17.73%  |
| 16384 | 63        | 6.94%   |
| 1024  | 33        | 3.63%   |
| 32768 | 22        | 2.42%   |
| 512   | 2         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 233       | 26.09%  |
| 3200    | 149       | 16.69%  |
| 2667    | 124       | 13.89%  |
| 2400    | 73        | 8.17%   |
| 1334    | 72        | 8.06%   |
| 1333    | 41        | 4.59%   |
| 667     | 37        | 4.14%   |
| 2133    | 23        | 2.58%   |
| 800     | 23        | 2.58%   |
| Unknown | 18        | 2.02%   |
| 4199    | 16        | 1.79%   |
| 1067    | 14        | 1.57%   |
| 3266    | 12        | 1.34%   |
| 2048    | 11        | 1.23%   |
| 1867    | 8         | 0.9%    |
| 4267    | 7         | 0.78%   |
| 533     | 7         | 0.78%   |
| 1066    | 5         | 0.56%   |
| 4800    | 4         | 0.45%   |
| 975     | 4         | 0.45%   |
| 3733    | 3         | 0.34%   |
| 8400    | 2         | 0.22%   |
| 6400    | 2         | 0.22%   |
| 4266    | 2         | 0.22%   |
| 1866    | 2         | 0.22%   |
| 5500    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 36.36%  |
| Brother Industries  | 3         | 27.27%  |
| Xerox               | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Prolific Technology | 1         | 9.09%   |
| Canon               | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox WorkCentre 6025               | 1         | 8.33%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 8.33%   |
| Prolific PL2305 Parallel Port       | 1         | 8.33%   |
| HP OfficeJet 6950                   | 1         | 8.33%   |
| HP Deskjet F4500 series             | 1         | 8.33%   |
| HP DeskJet 6122                     | 1         | 8.33%   |
| HP Deskjet 2050 J510                | 1         | 8.33%   |
| Canon LBP6030w/6018w                | 1         | 8.33%   |
| Brother Printer                     | 1         | 8.33%   |
| Brother MFC-J6535DW                 | 1         | 8.33%   |
| Brother MFC-J480DW                  | 1         | 8.33%   |
| Brother DCP-7010                    | 1         | 8.33%   |

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
| Chicony Electronics                    | 192       | 28.53%  |
| Realtek Semiconductor                  | 60        | 8.92%   |
| IMC Networks                           | 59        | 8.77%   |
| Microdia                               | 48        | 7.13%   |
| Sunplus Innovation Technology          | 37        | 5.5%    |
| Bison Electronics                      | 31        | 4.61%   |
| Suyin                                  | 30        | 4.46%   |
| Quanta                                 | 30        | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 4.01%   |
| Syntek                                 | 26        | 3.86%   |
| Silicon Motion                         | 14        | 2.08%   |
| Lite-On Technology                     | 14        | 2.08%   |
| Acer                                   | 14        | 2.08%   |
| Apple                                  | 13        | 1.93%   |
| Alcor Micro                            | 10        | 1.49%   |
| Luxvisions Innotech Limited            | 8         | 1.19%   |
| Ricoh                                  | 6         | 0.89%   |
| Primax Electronics                     | 6         | 0.89%   |
| Importek                               | 5         | 0.74%   |
| USB Camera                             | 4         | 0.59%   |
| Sonix Technology                       | 4         | 0.59%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.59%   |
| Lenovo                                 | 4         | 0.59%   |
| ALi                                    | 4         | 0.59%   |
| OmniVision Technologies                | 3         | 0.45%   |
| Z-Star Microelectronics                | 2         | 0.3%    |
| Y Media                                | 2         | 0.3%    |
| Sunplus Technology                     | 2         | 0.3%    |
| Samsung Electronics                    | 2         | 0.3%    |
| Logitech                               | 2         | 0.3%    |
| Intel                                  | 2         | 0.3%    |
| HRY                                    | 2         | 0.3%    |
| SunplusIT                              | 1         | 0.15%   |
| Huawei Technologies                    | 1         | 0.15%   |
| Goertek Electronics                    | 1         | 0.15%   |
| Genesys Logic                          | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| DigiTech                               | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 28        | 4.16%   |
| Chicony HD WebCam                                | 21        | 3.12%   |
| Microdia Integrated_Webcam_HD                    | 18        | 2.67%   |
| Syntek Integrated Camera                         | 16        | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                | 14        | 2.08%   |
| IMC Networks Integrated Camera                   | 14        | 2.08%   |
| Sunplus Integrated_Webcam_HD                     | 13        | 1.93%   |
| Realtek Integrated_Webcam_HD                     | 12        | 1.78%   |
| Realtek USB Camera                               | 11        | 1.63%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 11        | 1.63%   |
| Microdia Integrated Webcam                       | 9         | 1.34%   |
| Chicony Lenovo EasyCamera                        | 9         | 1.34%   |
| Chicony USB2.0 Camera                            | 8         | 1.19%   |
| Chicony FJ Camera                                | 8         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 8         | 1.19%   |
| Bison Integrated Camera                          | 8         | 1.19%   |
| Chicony VGA Webcam                               | 7         | 1.04%   |
| Chicony HP TrueVision HD Camera                  | 7         | 1.04%   |
| Chicony HP Truevision HD                         | 7         | 1.04%   |
| Chicony HD User Facing                           | 7         | 1.04%   |
| Suyin 1.3M HD WebCam                             | 6         | 0.89%   |
| Chicony TOSHIBA Web Camera - HD                  | 6         | 0.89%   |
| Chicony EasyCamera                               | 6         | 0.89%   |
| Apple FaceTime HD Camera                         | 6         | 0.89%   |
| Syntek Lenovo EasyCamera                         | 5         | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 5         | 0.74%   |
| Realtek Integrated Webcam                        | 5         | 0.74%   |
| Realtek EasyCamera                               | 5         | 0.74%   |
| Quanta VGA WebCam                                | 5         | 0.74%   |
| Quanta HP TrueVision HD Camera                   | 5         | 0.74%   |
| Quanta HD User Facing                            | 5         | 0.74%   |
| Lite-On Integrated Camera                        | 5         | 0.74%   |
| Chicony Camera                                   | 5         | 0.74%   |
| Bison ThinkPad Integrated Camera                 | 5         | 0.74%   |
| Alcor Micro USB 2.0 Camera                       | 5         | 0.74%   |
| Acer Integrated Camera                           | 5         | 0.74%   |
| Acer HD Webcam                                   | 5         | 0.74%   |
| USB Camera USB Camera                            | 4         | 0.59%   |
| Sunplus HD WebCam                                | 4         | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                       | 4         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 30.25%  |
| AuthenTec                  | 19        | 15.97%  |
| Synaptics                  | 15        | 12.61%  |
| Upek                       | 11        | 9.24%   |
| Shenzhen Goodix Technology | 11        | 9.24%   |
| Elan Microelectronics      | 10        | 8.4%    |
| LighTuning Technology      | 6         | 5.04%   |
| STMicroelectronics         | 4         | 3.36%   |
| Samsung Electronics        | 4         | 3.36%   |
| Focal-systems.Corp         | 3         | 2.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 8.4%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 7.56%   |
| AuthenTec AES2810                                                          | 8         | 6.72%   |
| Validity Sensors VFS491                                                    | 6         | 5.04%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 5.04%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 5.04%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.2%    |
| Elan ELAN:ARM-M4                                                           | 5         | 4.2%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 3.36%   |
| Synaptics UWP WBDI Device                                                  | 4         | 3.36%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 3.36%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 3.36%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 3.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.52%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.52%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 2.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.68%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.68%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.68%   |
| AuthenTec AES1600                                                          | 2         | 1.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.84%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.84%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.84%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.84%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.84%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.84%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.84%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 43.75%  |
| O2 Micro              | 12        | 25%     |
| Alcor Micro           | 7         | 14.58%  |
| Upek                  | 3         | 6.25%   |
| Lenovo                | 3         | 6.25%   |
| Realtek Semiconductor | 1         | 2.08%   |
| Advanced Card Systems | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 25%     |
| Broadcom 5880                                                                | 9         | 18.75%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 14.58%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 10.42%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.25%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.08%   |
| Broadcom 58200                                                               | 1         | 2.08%   |
| Advanced Card Systems ACR122U                                                | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 581       | 74.11%  |
| 1     | 180       | 22.96%  |
| 2     | 21        | 2.68%   |
| 3     | 2         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 119       | 53.6%   |
| Chipcard                 | 47        | 21.17%  |
| Graphics card            | 35        | 15.77%  |
| Net/wireless             | 5         | 2.25%   |
| Bluetooth                | 5         | 2.25%   |
| Storage                  | 3         | 1.35%   |
| Camera                   | 3         | 1.35%   |
| Multimedia controller    | 2         | 0.9%    |
| Communication controller | 2         | 0.9%    |
| Flash memory             | 1         | 0.45%   |

