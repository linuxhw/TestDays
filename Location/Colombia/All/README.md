Linux in Colombia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Colombia/Desktop/README.md) and [notebooks](/Location/Colombia/Notebook/README.md).

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

Total: 1062

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Sony          | VPCEH37FJ                   | Notebook    | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| Lenovo        | Z40-75 80DW                 | Notebook    | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | H81M-E33                    | Desktop     | [d79b11186c](https://linux-hardware.org/?probe=d79b11186c) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Dell          | 0J2J3Y A00                  | Desktop     | [50f015312c](https://linux-hardware.org/?probe=50f015312c) | Jun 23, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [15d402e40c](https://linux-hardware.org/?probe=15d402e40c) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| MSI           | H81M-E33                    | Desktop     | [0d2ace0dde](https://linux-hardware.org/?probe=0d2ace0dde) | Jun 16, 2022 |
| MSI           | H81M-E33                    | Desktop     | [52dbd6f482](https://linux-hardware.org/?probe=52dbd6f482) | Jun 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Acer          | AO722                       | Notebook    | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| Gigabyte      | H61M-HD2                    | Desktop     | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [269af04437](https://linux-hardware.org/?probe=269af04437) | Jun 13, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [170031499c](https://linux-hardware.org/?probe=170031499c) | Jun 12, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [5e7659e141](https://linux-hardware.org/?probe=5e7659e141) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [77e3d238c1](https://linux-hardware.org/?probe=77e3d238c1) | Jun 10, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [0664b57ae1](https://linux-hardware.org/?probe=0664b57ae1) | Jun 09, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [47ef7a04b9](https://linux-hardware.org/?probe=47ef7a04b9) | Jun 06, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e5998cb70e](https://linux-hardware.org/?probe=e5998cb70e) | Jun 05, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [1368d41e8e](https://linux-hardware.org/?probe=1368d41e8e) | Jun 04, 2022 |
| Sony          | VGN-CS240T                  | Notebook    | [b25cbd1a6b](https://linux-hardware.org/?probe=b25cbd1a6b) | Jun 03, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [b7e4b7a2ec](https://linux-hardware.org/?probe=b7e4b7a2ec) | Jun 03, 2022 |
| Acer          | AOD260                      | Notebook    | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| HP            | 8054                        | Desktop     | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [883f055fb1](https://linux-hardware.org/?probe=883f055fb1) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [e475b560cf](https://linux-hardware.org/?probe=e475b560cf) | May 30, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [b52762040d](https://linux-hardware.org/?probe=b52762040d) | May 30, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [dc9d61a80b](https://linux-hardware.org/?probe=dc9d61a80b) | May 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [159819d677](https://linux-hardware.org/?probe=159819d677) | May 26, 2022 |
| Dell          | Latitude E5410              | Notebook    | [fcb77d9c00](https://linux-hardware.org/?probe=fcb77d9c00) | May 26, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [7c3a3077ff](https://linux-hardware.org/?probe=7c3a3077ff) | May 24, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [7dd1f5b528](https://linux-hardware.org/?probe=7dd1f5b528) | May 23, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [50a0ed5e81](https://linux-hardware.org/?probe=50a0ed5e81) | May 22, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [f05080d3fd](https://linux-hardware.org/?probe=f05080d3fd) | May 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [46f7672c43](https://linux-hardware.org/?probe=46f7672c43) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [6f6a96c1cb](https://linux-hardware.org/?probe=6f6a96c1cb) | May 22, 2022 |
| Timi          | A35S                        | Notebook    | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [b476e4fd95](https://linux-hardware.org/?probe=b476e4fd95) | May 20, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Dell          | Inspiron 3459               | Notebook    | [b36df0b4df](https://linux-hardware.org/?probe=b36df0b4df) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [915b4b3bf1](https://linux-hardware.org/?probe=915b4b3bf1) | May 16, 2022 |
| MSI           | Katana GF76 12UE            | Notebook    | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f7d3a9220c](https://linux-hardware.org/?probe=f7d3a9220c) | May 13, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [0d1e1d71ee](https://linux-hardware.org/?probe=0d1e1d71ee) | May 08, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [3ad9fd00c2](https://linux-hardware.org/?probe=3ad9fd00c2) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | Notebook    | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [0d68cb4fdd](https://linux-hardware.org/?probe=0d68cb4fdd) | May 04, 2022 |
| Toshiba       | Satellite L735              | Notebook    | [cb523c0933](https://linux-hardware.org/?probe=cb523c0933) | May 02, 2022 |
| Lenovo        | G450 2949                   | Notebook    | [8a97581747](https://linux-hardware.org/?probe=8a97581747) | May 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [af01f27647](https://linux-hardware.org/?probe=af01f27647) | Apr 30, 2022 |
| Dell          | Vostro 1510                 | Notebook    | [3b071a4b76](https://linux-hardware.org/?probe=3b071a4b76) | Apr 29, 2022 |
| Dell          | Vostro 1510                 | Notebook    | [483727ec47](https://linux-hardware.org/?probe=483727ec47) | Apr 29, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [a756a0148d](https://linux-hardware.org/?probe=a756a0148d) | Apr 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [8a8d7b120a](https://linux-hardware.org/?probe=8a8d7b120a) | Apr 24, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [9f8f3a2eb5](https://linux-hardware.org/?probe=9f8f3a2eb5) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [738850499d](https://linux-hardware.org/?probe=738850499d) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [fd8cacef33](https://linux-hardware.org/?probe=fd8cacef33) | Apr 23, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [7b24feb14a](https://linux-hardware.org/?probe=7b24feb14a) | Apr 21, 2022 |
| Lenovo        | Z40-70 20366                | Notebook    | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [81d7ace164](https://linux-hardware.org/?probe=81d7ace164) | Apr 18, 2022 |
| MSI           | Creator 15 A10SFS           | Notebook    | [42b2140343](https://linux-hardware.org/?probe=42b2140343) | Apr 15, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [1877553731](https://linux-hardware.org/?probe=1877553731) | Apr 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [4a159b7cd8](https://linux-hardware.org/?probe=4a159b7cd8) | Apr 14, 2022 |
| Acer          | Aspire 4740                 | Notebook    | [d401412daa](https://linux-hardware.org/?probe=d401412daa) | Apr 13, 2022 |
| Dell          | 0C1GJ7 A00                  | All in one  | [8dd3b0dfb9](https://linux-hardware.org/?probe=8dd3b0dfb9) | Apr 13, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [7349c76e13](https://linux-hardware.org/?probe=7349c76e13) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ab7173f335](https://linux-hardware.org/?probe=ab7173f335) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 4291AN3       | Notebook    | [848b7902d8](https://linux-hardware.org/?probe=848b7902d8) | Apr 10, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [1d7a301fe2](https://linux-hardware.org/?probe=1d7a301fe2) | Apr 08, 2022 |
| Toshiba       | Satellite L735              | Notebook    | [b7873249a4](https://linux-hardware.org/?probe=b7873249a4) | Apr 07, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f68ed48f1b](https://linux-hardware.org/?probe=f68ed48f1b) | Apr 06, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [b3601d9299](https://linux-hardware.org/?probe=b3601d9299) | Apr 05, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [38036fe92b](https://linux-hardware.org/?probe=38036fe92b) | Apr 05, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [65a5442605](https://linux-hardware.org/?probe=65a5442605) | Apr 04, 2022 |
| HP            | ProLiant ML150 Gen9         | Desktop     | [50114897cc](https://linux-hardware.org/?probe=50114897cc) | Apr 01, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [8623b2ac51](https://linux-hardware.org/?probe=8623b2ac51) | Mar 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [066fb2b2b9](https://linux-hardware.org/?probe=066fb2b2b9) | Mar 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [a7fbdd0858](https://linux-hardware.org/?probe=a7fbdd0858) | Mar 26, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [dc0e34cb10](https://linux-hardware.org/?probe=dc0e34cb10) | Mar 26, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [18bc4eb505](https://linux-hardware.org/?probe=18bc4eb505) | Mar 25, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| Acer          | Aspire 3690                 | Notebook    | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [e149d7ed93](https://linux-hardware.org/?probe=e149d7ed93) | Mar 23, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b15d85a6e9](https://linux-hardware.org/?probe=b15d85a6e9) | Mar 22, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [f8d12d8ab9](https://linux-hardware.org/?probe=f8d12d8ab9) | Mar 22, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [6d6865b081](https://linux-hardware.org/?probe=6d6865b081) | Mar 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7810210cf5](https://linux-hardware.org/?probe=7810210cf5) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| HP            | 550                         | Notebook    | [91f443bb06](https://linux-hardware.org/?probe=91f443bb06) | Mar 18, 2022 |
| HP            | 550                         | Notebook    | [8acaec9ff1](https://linux-hardware.org/?probe=8acaec9ff1) | Mar 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [8c94df31c1](https://linux-hardware.org/?probe=8c94df31c1) | Mar 16, 2022 |
| Lenovo        | N22 80S6                    | Notebook    | [279ca719c8](https://linux-hardware.org/?probe=279ca719c8) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [1b91ffaa87](https://linux-hardware.org/?probe=1b91ffaa87) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [21dfbc138d](https://linux-hardware.org/?probe=21dfbc138d) | Mar 13, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [1f267ffe6e](https://linux-hardware.org/?probe=1f267ffe6e) | Mar 11, 2022 |
| Lenovo        | ThinkPad T430 2347AF3       | Notebook    | [8fa4355200](https://linux-hardware.org/?probe=8fa4355200) | Mar 08, 2022 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [3298d34369](https://linux-hardware.org/?probe=3298d34369) | Mar 07, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | Notebook    | [b1a7b4593a](https://linux-hardware.org/?probe=b1a7b4593a) | Mar 07, 2022 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [1e54d4f165](https://linux-hardware.org/?probe=1e54d4f165) | Mar 06, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | Notebook    | [f10cf42ebf](https://linux-hardware.org/?probe=f10cf42ebf) | Mar 06, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d068227c07](https://linux-hardware.org/?probe=d068227c07) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [b887ed3aa2](https://linux-hardware.org/?probe=b887ed3aa2) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [07cade8a02](https://linux-hardware.org/?probe=07cade8a02) | Mar 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ac671d5e38](https://linux-hardware.org/?probe=ac671d5e38) | Mar 05, 2022 |
| HP            | 245 G3                      | Notebook    | [879094e00f](https://linux-hardware.org/?probe=879094e00f) | Mar 02, 2022 |
| ASUSTek       | K43E                        | Notebook    | [484fd9a41a](https://linux-hardware.org/?probe=484fd9a41a) | Feb 27, 2022 |
| Supermicro    | X7DA8                       | Desktop     | [fcf69abc8f](https://linux-hardware.org/?probe=fcf69abc8f) | Feb 25, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [4c58660705](https://linux-hardware.org/?probe=4c58660705) | Feb 22, 2022 |
| Dell          | Latitude 5179               | Notebook    | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA4V500    | Notebook    | [e6a94741de](https://linux-hardware.org/?probe=e6a94741de) | Feb 17, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [2505367a60](https://linux-hardware.org/?probe=2505367a60) | Feb 16, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e783775e08](https://linux-hardware.org/?probe=e783775e08) | Feb 14, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [217c73c9a6](https://linux-hardware.org/?probe=217c73c9a6) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [8bcb36b8c7](https://linux-hardware.org/?probe=8bcb36b8c7) | Feb 09, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [ce2c94c97c](https://linux-hardware.org/?probe=ce2c94c97c) | Feb 07, 2022 |
| Sony          | VGN-FW170J                  | Notebook    | [edead40b0d](https://linux-hardware.org/?probe=edead40b0d) | Feb 07, 2022 |
| Framework     | Laptop                      | Notebook    | [55d5b56564](https://linux-hardware.org/?probe=55d5b56564) | Feb 07, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [95b7145bd2](https://linux-hardware.org/?probe=95b7145bd2) | Feb 06, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| HP            | 240 G7                      | Notebook    | [48bc3b139b](https://linux-hardware.org/?probe=48bc3b139b) | Feb 03, 2022 |
| HP            | 1587h                       | Desktop     | [92625959b4](https://linux-hardware.org/?probe=92625959b4) | Feb 02, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [c7a35398d0](https://linux-hardware.org/?probe=c7a35398d0) | Feb 02, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [876f78e96c](https://linux-hardware.org/?probe=876f78e96c) | Feb 01, 2022 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [e0cbedce41](https://linux-hardware.org/?probe=e0cbedce41) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | Notebook    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | Notebook    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e9752ad35d](https://linux-hardware.org/?probe=e9752ad35d) | Jan 24, 2022 |
| MSI           | GF75 Thin 10SER             | Notebook    | [2e94cc2b4c](https://linux-hardware.org/?probe=2e94cc2b4c) | Jan 22, 2022 |
| MSI           | GE72 2QE                    | Notebook    | [cbd609290e](https://linux-hardware.org/?probe=cbd609290e) | Jan 21, 2022 |
| MSI           | GE72 2QE                    | Notebook    | [72843af2fc](https://linux-hardware.org/?probe=72843af2fc) | Jan 14, 2022 |
| ASUSTek       | Maximus IX CODE             | Desktop     | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [fb3b510c66](https://linux-hardware.org/?probe=fb3b510c66) | Jan 06, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [be57155d1f](https://linux-hardware.org/?probe=be57155d1f) | Jan 06, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [36a412db42](https://linux-hardware.org/?probe=36a412db42) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [8fba60c1a8](https://linux-hardware.org/?probe=8fba60c1a8) | Dec 28, 2021 |
| MSI           | H81M-E33                    | Desktop     | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [c9cffe7310](https://linux-hardware.org/?probe=c9cffe7310) | Dec 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| MSI           | B150A GAMING PRO            | Desktop     | [475ea42f9a](https://linux-hardware.org/?probe=475ea42f9a) | Dec 11, 2021 |
| HP            | 3047h                       | Desktop     | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b3f7681477](https://linux-hardware.org/?probe=b3f7681477) | Dec 06, 2021 |
| HP            | ProBook 6450b               | Notebook    | [df1987d444](https://linux-hardware.org/?probe=df1987d444) | Dec 04, 2021 |
| HP            | 14                          | Notebook    | [d7cb66a845](https://linux-hardware.org/?probe=d7cb66a845) | Nov 28, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [d8946eaf3c](https://linux-hardware.org/?probe=d8946eaf3c) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [cbe2fcd79d](https://linux-hardware.org/?probe=cbe2fcd79d) | Nov 26, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [92d9d82670](https://linux-hardware.org/?probe=92d9d82670) | Nov 25, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [e3a6c887f6](https://linux-hardware.org/?probe=e3a6c887f6) | Nov 25, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [7d66f3183b](https://linux-hardware.org/?probe=7d66f3183b) | Nov 24, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| HP            | ProBook 440 G1              | Notebook    | [6159b4aa5a](https://linux-hardware.org/?probe=6159b4aa5a) | Nov 20, 2021 |
| HP            | ProBook 440 G1              | Notebook    | [42d0889355](https://linux-hardware.org/?probe=42d0889355) | Nov 20, 2021 |
| ASUSTek       | X441NA                      | Notebook    | [da21de67fb](https://linux-hardware.org/?probe=da21de67fb) | Nov 18, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [2d4636d0ee](https://linux-hardware.org/?probe=2d4636d0ee) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [e5da3884b4](https://linux-hardware.org/?probe=e5da3884b4) | Nov 17, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [b98c646c47](https://linux-hardware.org/?probe=b98c646c47) | Nov 16, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [18152a84af](https://linux-hardware.org/?probe=18152a84af) | Nov 13, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [abd0cfab6b](https://linux-hardware.org/?probe=abd0cfab6b) | Nov 12, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [27aa14962f](https://linux-hardware.org/?probe=27aa14962f) | Nov 12, 2021 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [6514199d0c](https://linux-hardware.org/?probe=6514199d0c) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [de9d0e2b40](https://linux-hardware.org/?probe=de9d0e2b40) | Nov 08, 2021 |
| Lenovo        | ThinkPad T495 20NKS0QN0V    | Notebook    | [ceab02dda1](https://linux-hardware.org/?probe=ceab02dda1) | Nov 07, 2021 |
| Dell          | Latitude 7490               | Notebook    | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | Notebook    | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| HP            | Pavilion dv4                | Notebook    | [7e9733638c](https://linux-hardware.org/?probe=7e9733638c) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [c196661531](https://linux-hardware.org/?probe=c196661531) | Nov 01, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [dcd63f8987](https://linux-hardware.org/?probe=dcd63f8987) | Oct 31, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [809fe8da11](https://linux-hardware.org/?probe=809fe8da11) | Oct 30, 2021 |
| MSI           | 2A9Ch                       | Desktop     | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [7f70de1771](https://linux-hardware.org/?probe=7f70de1771) | Oct 26, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [6777af6e6a](https://linux-hardware.org/?probe=6777af6e6a) | Oct 26, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [eb596b1774](https://linux-hardware.org/?probe=eb596b1774) | Oct 25, 2021 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [cdd35d634d](https://linux-hardware.org/?probe=cdd35d634d) | Oct 24, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [d9c192ea8c](https://linux-hardware.org/?probe=d9c192ea8c) | Oct 23, 2021 |
| HP            | 2B0C MVB,A                  | All in one  | [46a74b74fc](https://linux-hardware.org/?probe=46a74b74fc) | Oct 22, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [61b1e7901a](https://linux-hardware.org/?probe=61b1e7901a) | Oct 17, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [dc7a02c862](https://linux-hardware.org/?probe=dc7a02c862) | Oct 15, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [d0b6443f5b](https://linux-hardware.org/?probe=d0b6443f5b) | Oct 12, 2021 |
| HP            | 240 G3                      | Notebook    | [a083502110](https://linux-hardware.org/?probe=a083502110) | Oct 11, 2021 |
| HP            | 240 G3                      | Notebook    | [1772f88ed6](https://linux-hardware.org/?probe=1772f88ed6) | Oct 11, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [ee28fa6dfb](https://linux-hardware.org/?probe=ee28fa6dfb) | Oct 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [05c0fc8d29](https://linux-hardware.org/?probe=05c0fc8d29) | Oct 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [330659159b](https://linux-hardware.org/?probe=330659159b) | Oct 07, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [14d286f67e](https://linux-hardware.org/?probe=14d286f67e) | Oct 07, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [d034cd0b4a](https://linux-hardware.org/?probe=d034cd0b4a) | Oct 07, 2021 |
| Foxconn       | H61MXE                      | Desktop     | [f684b8da61](https://linux-hardware.org/?probe=f684b8da61) | Oct 06, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| HP            | 2B0C MVB,A                  | All in one  | [b411cfd959](https://linux-hardware.org/?probe=b411cfd959) | Oct 04, 2021 |
| Pegatron      | 2AE2                        | Desktop     | [0309cddc66](https://linux-hardware.org/?probe=0309cddc66) | Oct 02, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a451fc441b](https://linux-hardware.org/?probe=a451fc441b) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [643c70dec0](https://linux-hardware.org/?probe=643c70dec0) | Sep 27, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [6476a95a04](https://linux-hardware.org/?probe=6476a95a04) | Sep 27, 2021 |
| Biostar       | G41D3C                      | Desktop     | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [0f6a772a44](https://linux-hardware.org/?probe=0f6a772a44) | Sep 25, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b30800b2f9](https://linux-hardware.org/?probe=b30800b2f9) | Sep 24, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [6e9f3c8012](https://linux-hardware.org/?probe=6e9f3c8012) | Sep 22, 2021 |
| ECS           | G31T-M7                     | Desktop     | [60bf966d06](https://linux-hardware.org/?probe=60bf966d06) | Sep 18, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [7922da571d](https://linux-hardware.org/?probe=7922da571d) | Sep 16, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e7afe651d3](https://linux-hardware.org/?probe=e7afe651d3) | Sep 16, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [e6fbfad3de](https://linux-hardware.org/?probe=e6fbfad3de) | Sep 16, 2021 |
| Gateway       | NV47H                       | Notebook    | [8cef362c2e](https://linux-hardware.org/?probe=8cef362c2e) | Sep 15, 2021 |
| Gateway       | NV47H                       | Notebook    | [0ad04889c5](https://linux-hardware.org/?probe=0ad04889c5) | Sep 15, 2021 |
| Dell          | Latitude E7270              | Notebook    | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| HP            | 18E9                        | Desktop     | [7a7dd34d6d](https://linux-hardware.org/?probe=7a7dd34d6d) | Sep 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [d4a19b90eb](https://linux-hardware.org/?probe=d4a19b90eb) | Sep 13, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [2300be2f19](https://linux-hardware.org/?probe=2300be2f19) | Sep 13, 2021 |
| HP            | 2000                        | Notebook    | [7d8cd719a2](https://linux-hardware.org/?probe=7d8cd719a2) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [052bfbd512](https://linux-hardware.org/?probe=052bfbd512) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [a3b7774236](https://linux-hardware.org/?probe=a3b7774236) | Sep 09, 2021 |
| Dell          | Inspiron 1110               | Notebook    | [890d9d9d24](https://linux-hardware.org/?probe=890d9d9d24) | Sep 08, 2021 |
| Dell          | Inspiron 1110               | Notebook    | [e299761316](https://linux-hardware.org/?probe=e299761316) | Sep 08, 2021 |
| Intel         | D945GCLF2D AAE59323-101     | Desktop     | [d6808fecbf](https://linux-hardware.org/?probe=d6808fecbf) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | X555QA                      | Notebook    | [043083e9e8](https://linux-hardware.org/?probe=043083e9e8) | Sep 04, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [badf1b0736](https://linux-hardware.org/?probe=badf1b0736) | Aug 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [33a8107059](https://linux-hardware.org/?probe=33a8107059) | Aug 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [fe2ba9da7c](https://linux-hardware.org/?probe=fe2ba9da7c) | Aug 28, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [08c766b957](https://linux-hardware.org/?probe=08c766b957) | Aug 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7e6a9f0430](https://linux-hardware.org/?probe=7e6a9f0430) | Aug 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [15d48710db](https://linux-hardware.org/?probe=15d48710db) | Aug 24, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [8aa8372f3c](https://linux-hardware.org/?probe=8aa8372f3c) | Aug 23, 2021 |
| HP            | 14                          | Notebook    | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| Pegatron      | 2AEE                        | Desktop     | [a3e6da7d21](https://linux-hardware.org/?probe=a3e6da7d21) | Aug 22, 2021 |
| Pegatron      | 2AEE                        | Desktop     | [0b0cf520ba](https://linux-hardware.org/?probe=0b0cf520ba) | Aug 22, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [a8d5b4ff89](https://linux-hardware.org/?probe=a8d5b4ff89) | Aug 22, 2021 |
| HP            | 18E9                        | Desktop     | [9ee974d2df](https://linux-hardware.org/?probe=9ee974d2df) | Aug 21, 2021 |
| HP            | 18E9                        | Desktop     | [838f27241e](https://linux-hardware.org/?probe=838f27241e) | Aug 21, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [e7f145f52b](https://linux-hardware.org/?probe=e7f145f52b) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| HP            | 304Ah                       | Desktop     | [4760a65d2f](https://linux-hardware.org/?probe=4760a65d2f) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [0acfc1ab65](https://linux-hardware.org/?probe=0acfc1ab65) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [27898f0b8e](https://linux-hardware.org/?probe=27898f0b8e) | Aug 20, 2021 |
| HP            | 304Ah                       | Desktop     | [67e7cc53c1](https://linux-hardware.org/?probe=67e7cc53c1) | Aug 18, 2021 |
| HP            | 8430 1000                   | All in one  | [38088141ff](https://linux-hardware.org/?probe=38088141ff) | Aug 17, 2021 |
| Timi          | A35S                        | Notebook    | [1f0e95ee1d](https://linux-hardware.org/?probe=1f0e95ee1d) | Aug 17, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3bf42ebeb8](https://linux-hardware.org/?probe=3bf42ebeb8) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| Dell          | Precision 3551              | Notebook    | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| Dell          | Precision 3551              | Notebook    | [aeeeb63990](https://linux-hardware.org/?probe=aeeeb63990) | Aug 10, 2021 |
| Dell          | 0CXTWJ A00                  | All in one  | [55b0b947be](https://linux-hardware.org/?probe=55b0b947be) | Aug 09, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [321af82bbf](https://linux-hardware.org/?probe=321af82bbf) | Aug 09, 2021 |
| Dell          | Latitude D630               | Notebook    | [ceb9ca591f](https://linux-hardware.org/?probe=ceb9ca591f) | Aug 05, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20eabf2484](https://linux-hardware.org/?probe=20eabf2484) | Aug 02, 2021 |
| MSI           | MS-16GF                     | Notebook    | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 4293B43       | Notebook    | [7accb85da9](https://linux-hardware.org/?probe=7accb85da9) | Jul 30, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [efc844205b](https://linux-hardware.org/?probe=efc844205b) | Jul 27, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [2ce8f90f70](https://linux-hardware.org/?probe=2ce8f90f70) | Jul 26, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [4a458edcf6](https://linux-hardware.org/?probe=4a458edcf6) | Jul 24, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| HP            | Presario CQ42               | Notebook    | [fa65f13c3b](https://linux-hardware.org/?probe=fa65f13c3b) | Jul 23, 2021 |
| Dell          | Inspiron 3493               | Notebook    | [df4bedc1fd](https://linux-hardware.org/?probe=df4bedc1fd) | Jul 21, 2021 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [e8b5870e50](https://linux-hardware.org/?probe=e8b5870e50) | Jul 19, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9182648939](https://linux-hardware.org/?probe=9182648939) | Jul 19, 2021 |
| Acer          | TravelMate P2410-G2-M       | Notebook    | [7088129430](https://linux-hardware.org/?probe=7088129430) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [36b0d241cd](https://linux-hardware.org/?probe=36b0d241cd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3c938f74fd](https://linux-hardware.org/?probe=3c938f74fd) | Jul 16, 2021 |
| MSI           | MS-7309                     | Desktop     | [8b431e8b6f](https://linux-hardware.org/?probe=8b431e8b6f) | Jul 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3508d853ae](https://linux-hardware.org/?probe=3508d853ae) | Jul 09, 2021 |
| Dell          | 0CXTWJ A00                  | All in one  | [c8d344a37f](https://linux-hardware.org/?probe=c8d344a37f) | Jul 07, 2021 |
| ASUSTek       | K401UQ                      | Notebook    | [9f9a853e03](https://linux-hardware.org/?probe=9f9a853e03) | Jul 05, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| ASUSTek       | G73Jw                       | Notebook    | [b1d6609434](https://linux-hardware.org/?probe=b1d6609434) | Jul 03, 2021 |
| Lenovo        | ThinkPad W510 4391BY8       | Notebook    | [12d0ff5c27](https://linux-hardware.org/?probe=12d0ff5c27) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [bc19b4b3bf](https://linux-hardware.org/?probe=bc19b4b3bf) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c1442501a0](https://linux-hardware.org/?probe=c1442501a0) | Jul 03, 2021 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7b71d5854c](https://linux-hardware.org/?probe=7b71d5854c) | Jul 01, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude 7414               | Notebook    | [5557aada9a](https://linux-hardware.org/?probe=5557aada9a) | Jun 28, 2021 |
| ASUSTek       | X441UA                      | Notebook    | [3574e8459f](https://linux-hardware.org/?probe=3574e8459f) | Jun 25, 2021 |
| HP            | Pavilion 10 TS              | Notebook    | [1759d8d1f8](https://linux-hardware.org/?probe=1759d8d1f8) | Jun 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b845fbd6b0](https://linux-hardware.org/?probe=b845fbd6b0) | Jun 20, 2021 |
| ASUSTek       | T101HA                      | Tablet      | [ae0e0904db](https://linux-hardware.org/?probe=ae0e0904db) | Jun 20, 2021 |
| ASUSTek       | T101HA                      | Tablet      | [5482959345](https://linux-hardware.org/?probe=5482959345) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [3eb01e93e5](https://linux-hardware.org/?probe=3eb01e93e5) | Jun 16, 2021 |
| Acer          | A315-41G                    | Notebook    | [c3b9603724](https://linux-hardware.org/?probe=c3b9603724) | Jun 15, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bd7d3a3b09](https://linux-hardware.org/?probe=bd7d3a3b09) | Jun 11, 2021 |
| Acer          | Aspire E5-471               | Notebook    | [f15409e7cc](https://linux-hardware.org/?probe=f15409e7cc) | Jun 10, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [2e841a4dc4](https://linux-hardware.org/?probe=2e841a4dc4) | Jun 09, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [a5547e4146](https://linux-hardware.org/?probe=a5547e4146) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d15f22008c](https://linux-hardware.org/?probe=d15f22008c) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [82dff2688d](https://linux-hardware.org/?probe=82dff2688d) | Jun 07, 2021 |
| Intel         | H61                         | Desktop     | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| HP            | Pavilion 10 TS              | Notebook    | [ad461cbf3e](https://linux-hardware.org/?probe=ad461cbf3e) | Jun 07, 2021 |
| HP            | 245 G6                      | Notebook    | [a3594ab925](https://linux-hardware.org/?probe=a3594ab925) | Jun 03, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| ONDA          | V919 AIR CH                 | Tablet      | [3317ba664d](https://linux-hardware.org/?probe=3317ba664d) | May 28, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [499479904d](https://linux-hardware.org/?probe=499479904d) | May 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [9f332f4fec](https://linux-hardware.org/?probe=9f332f4fec) | May 25, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| HP            | Notebook                    | Notebook    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | Notebook    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [33c1ecc56e](https://linux-hardware.org/?probe=33c1ecc56e) | May 19, 2021 |
| Toshiba       | Satellite C850-B797         | Notebook    | [834d15c08c](https://linux-hardware.org/?probe=834d15c08c) | May 16, 2021 |
| Toshiba       | Satellite C850-B797         | Notebook    | [0ece4b9e9e](https://linux-hardware.org/?probe=0ece4b9e9e) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [22eae98fb5](https://linux-hardware.org/?probe=22eae98fb5) | May 13, 2021 |
| Toshiba       | Satellite C850-B797         | Notebook    | [1355c6e459](https://linux-hardware.org/?probe=1355c6e459) | May 13, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [6889e28bfd](https://linux-hardware.org/?probe=6889e28bfd) | May 09, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [0ef93e6291](https://linux-hardware.org/?probe=0ef93e6291) | May 09, 2021 |
| Lenovo        | ThinkPad T420 42363Y5       | Notebook    | [5a93fb1b0b](https://linux-hardware.org/?probe=5a93fb1b0b) | May 07, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [5ad427cffb](https://linux-hardware.org/?probe=5ad427cffb) | May 04, 2021 |
| ASRock        | G965M-S                     | Desktop     | [dd116582af](https://linux-hardware.org/?probe=dd116582af) | May 03, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| Dell          | 00NH4P A09                  | Server      | [bed13d11ad](https://linux-hardware.org/?probe=bed13d11ad) | May 02, 2021 |
| Dell          | 00NH4P A09                  | Server      | [d03d113d9f](https://linux-hardware.org/?probe=d03d113d9f) | May 02, 2021 |
| Intel         | H61                         | Desktop     | [cca60711c8](https://linux-hardware.org/?probe=cca60711c8) | May 01, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [ae115d5ca8](https://linux-hardware.org/?probe=ae115d5ca8) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [34733fe16f](https://linux-hardware.org/?probe=34733fe16f) | Apr 29, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [037a465656](https://linux-hardware.org/?probe=037a465656) | Apr 28, 2021 |
| MSI           | 970A-G46                    | Desktop     | [f1035827e0](https://linux-hardware.org/?probe=f1035827e0) | Apr 26, 2021 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [6410827a2f](https://linux-hardware.org/?probe=6410827a2f) | Apr 25, 2021 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [a8c42b2d94](https://linux-hardware.org/?probe=a8c42b2d94) | Apr 25, 2021 |
| MSI           | 970A-G46                    | Desktop     | [9aa4264419](https://linux-hardware.org/?probe=9aa4264419) | Apr 22, 2021 |
| MSI           | K9A2 Platinum               | Desktop     | [fc4fd8ba0e](https://linux-hardware.org/?probe=fc4fd8ba0e) | Apr 19, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [7585c05b18](https://linux-hardware.org/?probe=7585c05b18) | Apr 19, 2021 |
| MSI           | K9A2 Platinum               | Desktop     | [ef223aa1d5](https://linux-hardware.org/?probe=ef223aa1d5) | Apr 16, 2021 |
| Notebook      | N150CU                      | Notebook    | [e62762a731](https://linux-hardware.org/?probe=e62762a731) | Apr 14, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [48ab0d2acd](https://linux-hardware.org/?probe=48ab0d2acd) | Apr 14, 2021 |
| Lenovo        | ThinkPad X260 20F5A0HB00    | Notebook    | [9163ce31dc](https://linux-hardware.org/?probe=9163ce31dc) | Apr 14, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [1263e938c8](https://linux-hardware.org/?probe=1263e938c8) | Apr 13, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [5fada7c64a](https://linux-hardware.org/?probe=5fada7c64a) | Apr 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [729cbf17a4](https://linux-hardware.org/?probe=729cbf17a4) | Apr 07, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [95df5a7ac5](https://linux-hardware.org/?probe=95df5a7ac5) | Apr 06, 2021 |
| HP            | x2 210 G2                   | Tablet      | [1c188b150f](https://linux-hardware.org/?probe=1c188b150f) | Apr 06, 2021 |
| Lenovo        | ThinkPad X230 2325BG3       | Notebook    | [90f6078b02](https://linux-hardware.org/?probe=90f6078b02) | Apr 04, 2021 |
| ASUSTek       | X555DG                      | Notebook    | [334a8d4184](https://linux-hardware.org/?probe=334a8d4184) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [cc61b2b6a7](https://linux-hardware.org/?probe=cc61b2b6a7) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [c079cb8fac](https://linux-hardware.org/?probe=c079cb8fac) | Apr 01, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2c67d604ff](https://linux-hardware.org/?probe=2c67d604ff) | Mar 28, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [f2760185e3](https://linux-hardware.org/?probe=f2760185e3) | Mar 26, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [87e7b3b248](https://linux-hardware.org/?probe=87e7b3b248) | Mar 22, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [1d422767e1](https://linux-hardware.org/?probe=1d422767e1) | Mar 20, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [ccb5c756ee](https://linux-hardware.org/?probe=ccb5c756ee) | Mar 20, 2021 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [2ebfc03ce7](https://linux-hardware.org/?probe=2ebfc03ce7) | Mar 20, 2021 |
| Acer          | AOD255                      | Notebook    | [2e5b228a04](https://linux-hardware.org/?probe=2e5b228a04) | Mar 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [843d061b78](https://linux-hardware.org/?probe=843d061b78) | Mar 15, 2021 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [87cabd058e](https://linux-hardware.org/?probe=87cabd058e) | Mar 13, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [8cb18a4f6c](https://linux-hardware.org/?probe=8cb18a4f6c) | Mar 11, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [a6e9e8ea5e](https://linux-hardware.org/?probe=a6e9e8ea5e) | Mar 11, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [29c1565b42](https://linux-hardware.org/?probe=29c1565b42) | Mar 10, 2021 |
| Acer          | AOD255                      | Notebook    | [f3a5b4b0e4](https://linux-hardware.org/?probe=f3a5b4b0e4) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [98d2580d9e](https://linux-hardware.org/?probe=98d2580d9e) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [91cd908a95](https://linux-hardware.org/?probe=91cd908a95) | Mar 05, 2021 |
| HP            | 2B09                        | Desktop     | [44e3728303](https://linux-hardware.org/?probe=44e3728303) | Mar 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d9708c63f5](https://linux-hardware.org/?probe=d9708c63f5) | Mar 04, 2021 |
| Dell          | Precision 3551              | Notebook    | [d75a598209](https://linux-hardware.org/?probe=d75a598209) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [bc879be58b](https://linux-hardware.org/?probe=bc879be58b) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [27b7f94851](https://linux-hardware.org/?probe=27b7f94851) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [935f9c5571](https://linux-hardware.org/?probe=935f9c5571) | Mar 03, 2021 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [4cb354b544](https://linux-hardware.org/?probe=4cb354b544) | Mar 02, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a758fdf9af](https://linux-hardware.org/?probe=a758fdf9af) | Mar 01, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a8bd4eacfc](https://linux-hardware.org/?probe=a8bd4eacfc) | Feb 28, 2021 |
| HP            | Pavilion 10 TS              | Notebook    | [5998c38555](https://linux-hardware.org/?probe=5998c38555) | Feb 26, 2021 |
| Intel         | DP67DE AAG10217-205         | Desktop     | [4b376912e1](https://linux-hardware.org/?probe=4b376912e1) | Feb 23, 2021 |
| Intel         | DP67DE AAG10217-205         | Desktop     | [497e0558af](https://linux-hardware.org/?probe=497e0558af) | Feb 23, 2021 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [ed29a42a57](https://linux-hardware.org/?probe=ed29a42a57) | Feb 23, 2021 |
| Dell          | Latitude E6220              | Notebook    | [1c0ab9fab1](https://linux-hardware.org/?probe=1c0ab9fab1) | Feb 23, 2021 |
| Dell          | Latitude E6220              | Notebook    | [19e1a4a1d6](https://linux-hardware.org/?probe=19e1a4a1d6) | Feb 23, 2021 |
| Dell          | Inspiron 3493               | Notebook    | [684245175e](https://linux-hardware.org/?probe=684245175e) | Feb 20, 2021 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [7581904d41](https://linux-hardware.org/?probe=7581904d41) | Feb 20, 2021 |
| Apple         | MacBookPro15,1              | Notebook    | [a148b9034a](https://linux-hardware.org/?probe=a148b9034a) | Feb 19, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [f6830c6ac2](https://linux-hardware.org/?probe=f6830c6ac2) | Feb 18, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [ecddf05f3e](https://linux-hardware.org/?probe=ecddf05f3e) | Feb 16, 2021 |
| BAKED         | P7xxDM2(-G)                 | Notebook    | [824169b9f7](https://linux-hardware.org/?probe=824169b9f7) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [8be5048c51](https://linux-hardware.org/?probe=8be5048c51) | Feb 15, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [8da12e7518](https://linux-hardware.org/?probe=8da12e7518) | Feb 14, 2021 |
| Nvidia        | Tegra                       | Soc         | [b49723230a](https://linux-hardware.org/?probe=b49723230a) | Feb 13, 2021 |
| Inspur        | M11JB R2.0/R1.1             | Notebook    | [5e5731f2b0](https://linux-hardware.org/?probe=5e5731f2b0) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Inspur        | M11JB R2.0/R1.1             | Notebook    | [90847dec81](https://linux-hardware.org/?probe=90847dec81) | Feb 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e97c86bc3](https://linux-hardware.org/?probe=6e97c86bc3) | Feb 10, 2021 |
| HP            | Notebook                    | Notebook    | [5224b13971](https://linux-hardware.org/?probe=5224b13971) | Feb 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [93004b8e8f](https://linux-hardware.org/?probe=93004b8e8f) | Feb 07, 2021 |
| Nvidia        | Tegra                       | Soc         | [ed22dcb6c2](https://linux-hardware.org/?probe=ed22dcb6c2) | Feb 07, 2021 |
| Dell          | Inspiron 7586               | Notebook    | [7e6463f517](https://linux-hardware.org/?probe=7e6463f517) | Feb 05, 2021 |
| ASUSTek       | X505BA                      | Notebook    | [8059f98337](https://linux-hardware.org/?probe=8059f98337) | Feb 03, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [909121ec95](https://linux-hardware.org/?probe=909121ec95) | Feb 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [b7460ea1e6](https://linux-hardware.org/?probe=b7460ea1e6) | Feb 02, 2021 |
| HP            | Presario CQ43               | Notebook    | [13eb02bc61](https://linux-hardware.org/?probe=13eb02bc61) | Feb 02, 2021 |
| HP            | Presario CQ43               | Notebook    | [a6d1b8df1e](https://linux-hardware.org/?probe=a6d1b8df1e) | Feb 02, 2021 |
| Notebook      | N150CU                      | Notebook    | [7753afd04f](https://linux-hardware.org/?probe=7753afd04f) | Jan 29, 2021 |
| Lenovo        | ThinkPad L430 2466EC5       | Notebook    | [8f5111df1d](https://linux-hardware.org/?probe=8f5111df1d) | Jan 28, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [b452e9e060](https://linux-hardware.org/?probe=b452e9e060) | Jan 27, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [eac34165b9](https://linux-hardware.org/?probe=eac34165b9) | Jan 27, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ab91702ac3](https://linux-hardware.org/?probe=ab91702ac3) | Jan 26, 2021 |
| GreatWall     | K41                         | Notebook    | [ddf99d904e](https://linux-hardware.org/?probe=ddf99d904e) | Jan 25, 2021 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| ASUSTek       | X555LN                      | Notebook    | [e649cc1304](https://linux-hardware.org/?probe=e649cc1304) | Jan 24, 2021 |
| ASUSTek       | X441UVK                     | Notebook    | [c73eaa8a8f](https://linux-hardware.org/?probe=c73eaa8a8f) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0ca25f14fb](https://linux-hardware.org/?probe=0ca25f14fb) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [419800f72d](https://linux-hardware.org/?probe=419800f72d) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [844d185dae](https://linux-hardware.org/?probe=844d185dae) | Jan 21, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [91a85ad436](https://linux-hardware.org/?probe=91a85ad436) | Jan 20, 2021 |
| Supermicro    | X9DRD-iF                    | Server      | [afe42b7e58](https://linux-hardware.org/?probe=afe42b7e58) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | Notebook    | [62de1cd91f](https://linux-hardware.org/?probe=62de1cd91f) | Jan 16, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8dcbe2b63e](https://linux-hardware.org/?probe=8dcbe2b63e) | Jan 15, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c969271698](https://linux-hardware.org/?probe=c969271698) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9bd74368f0](https://linux-hardware.org/?probe=9bd74368f0) | Jan 15, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [edcaecc674](https://linux-hardware.org/?probe=edcaecc674) | Jan 14, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [e5d77ec648](https://linux-hardware.org/?probe=e5d77ec648) | Jan 14, 2021 |
| Dell          | Precision 3551              | Notebook    | [c6524a92a4](https://linux-hardware.org/?probe=c6524a92a4) | Jan 13, 2021 |
| Intel         | H61                         | Desktop     | [d8489ff473](https://linux-hardware.org/?probe=d8489ff473) | Jan 11, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [81ab4a6cc7](https://linux-hardware.org/?probe=81ab4a6cc7) | Jan 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6d637febe2](https://linux-hardware.org/?probe=6d637febe2) | Jan 10, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [05b3190864](https://linux-hardware.org/?probe=05b3190864) | Jan 08, 2021 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [0d58fd33df](https://linux-hardware.org/?probe=0d58fd33df) | Jan 07, 2021 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [d1947d8c18](https://linux-hardware.org/?probe=d1947d8c18) | Jan 07, 2021 |
| Dell          | System XPS L502X            | Notebook    | [6548d3214b](https://linux-hardware.org/?probe=6548d3214b) | Jan 06, 2021 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4e9f49422a](https://linux-hardware.org/?probe=4e9f49422a) | Jan 04, 2021 |
| BAKED         | P7xxDM2(-G)                 | Notebook    | [c4206ecc26](https://linux-hardware.org/?probe=c4206ecc26) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | Notebook    | [f995163ff4](https://linux-hardware.org/?probe=f995163ff4) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | Notebook    | [2758658d90](https://linux-hardware.org/?probe=2758658d90) | Jan 04, 2021 |
| Biostar       | H61MHV                      | Desktop     | [60f41299a7](https://linux-hardware.org/?probe=60f41299a7) | Jan 04, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [801defb54c](https://linux-hardware.org/?probe=801defb54c) | Jan 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [6b7c6db0c5](https://linux-hardware.org/?probe=6b7c6db0c5) | Dec 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [10b0b04256](https://linux-hardware.org/?probe=10b0b04256) | Dec 30, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [10d64eecc5](https://linux-hardware.org/?probe=10d64eecc5) | Dec 30, 2020 |
| Gigabyte      | 970A-UD3                    | Desktop     | [4de6e16ced](https://linux-hardware.org/?probe=4de6e16ced) | Dec 30, 2020 |
| Dell          | 0G3HR7 A00                  | Desktop     | [1c8f1911c4](https://linux-hardware.org/?probe=1c8f1911c4) | Dec 29, 2020 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [e850bec31a](https://linux-hardware.org/?probe=e850bec31a) | Dec 29, 2020 |
| PCSMART       | Unknown                     | Desktop     | [5c91c760a5](https://linux-hardware.org/?probe=5c91c760a5) | Dec 28, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [3c4ea54770](https://linux-hardware.org/?probe=3c4ea54770) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d61f2aa238](https://linux-hardware.org/?probe=d61f2aa238) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [bca2708dcd](https://linux-hardware.org/?probe=bca2708dcd) | Dec 25, 2020 |
| ASUSTek       | X450CP                      | Notebook    | [1d2d82e5ee](https://linux-hardware.org/?probe=1d2d82e5ee) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [e395d72cbb](https://linux-hardware.org/?probe=e395d72cbb) | Dec 21, 2020 |
| HP            | Pavilion dv4                | Notebook    | [0f86ea7cab](https://linux-hardware.org/?probe=0f86ea7cab) | Dec 20, 2020 |
| HP            | ProBook 440 G3              | Notebook    | [ad30a7ae38](https://linux-hardware.org/?probe=ad30a7ae38) | Dec 20, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [c23ae5c475](https://linux-hardware.org/?probe=c23ae5c475) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | Notebook    | [2475252354](https://linux-hardware.org/?probe=2475252354) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | Notebook    | [a08f4cf4e5](https://linux-hardware.org/?probe=a08f4cf4e5) | Dec 19, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [263df4fa91](https://linux-hardware.org/?probe=263df4fa91) | Dec 19, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [69e3d131e9](https://linux-hardware.org/?probe=69e3d131e9) | Dec 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [73fa61c233](https://linux-hardware.org/?probe=73fa61c233) | Dec 15, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [dd0d449586](https://linux-hardware.org/?probe=dd0d449586) | Dec 14, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [246d659f60](https://linux-hardware.org/?probe=246d659f60) | Dec 11, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fb4783aeba](https://linux-hardware.org/?probe=fb4783aeba) | Dec 10, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [7633d83de8](https://linux-hardware.org/?probe=7633d83de8) | Dec 08, 2020 |
| Lenovo        | Yoga 700-11ISK 80QE         | Notebook    | [1a353b9226](https://linux-hardware.org/?probe=1a353b9226) | Dec 08, 2020 |
| ECS           | G31T-M7                     | Desktop     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3962cbfb58](https://linux-hardware.org/?probe=3962cbfb58) | Dec 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3d5a1c07e6](https://linux-hardware.org/?probe=3d5a1c07e6) | Dec 05, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [02fb63a36f](https://linux-hardware.org/?probe=02fb63a36f) | Dec 04, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [841208193d](https://linux-hardware.org/?probe=841208193d) | Dec 03, 2020 |
| ASUSTek       | K46CM                       | Notebook    | [490bae951e](https://linux-hardware.org/?probe=490bae951e) | Dec 01, 2020 |
| Lenovo        | G470 20078                  | Notebook    | [b0564c0e50](https://linux-hardware.org/?probe=b0564c0e50) | Dec 01, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [e90cdb39ef](https://linux-hardware.org/?probe=e90cdb39ef) | Nov 30, 2020 |
| Lenovo        | IdeaPad U510 20191          | Notebook    | [895b641220](https://linux-hardware.org/?probe=895b641220) | Nov 30, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [0a4b399149](https://linux-hardware.org/?probe=0a4b399149) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [0c9f7ea289](https://linux-hardware.org/?probe=0c9f7ea289) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [a5f5b59788](https://linux-hardware.org/?probe=a5f5b59788) | Nov 26, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [503b8f9701](https://linux-hardware.org/?probe=503b8f9701) | Nov 25, 2020 |
| ASUSTek       | X441NA                      | Notebook    | [61a5d6947b](https://linux-hardware.org/?probe=61a5d6947b) | Nov 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [73dc6959d6](https://linux-hardware.org/?probe=73dc6959d6) | Nov 23, 2020 |
| Unknown       | Unknown                     | Notebook    | [b0c0ef90cd](https://linux-hardware.org/?probe=b0c0ef90cd) | Nov 23, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [324e08922c](https://linux-hardware.org/?probe=324e08922c) | Nov 23, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [63124c698a](https://linux-hardware.org/?probe=63124c698a) | Nov 22, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a997f8c186](https://linux-hardware.org/?probe=a997f8c186) | Nov 22, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e24dba10a2](https://linux-hardware.org/?probe=e24dba10a2) | Nov 22, 2020 |
| ASUSTek       | X441NA                      | Notebook    | [e301cabf95](https://linux-hardware.org/?probe=e301cabf95) | Nov 21, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [5021095fd1](https://linux-hardware.org/?probe=5021095fd1) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [e5e8cfd574](https://linux-hardware.org/?probe=e5e8cfd574) | Nov 19, 2020 |
| ASRock        | AB350M-HDV                  | Desktop     | [4a503972bc](https://linux-hardware.org/?probe=4a503972bc) | Nov 18, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [026fdce11f](https://linux-hardware.org/?probe=026fdce11f) | Nov 13, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [b3752255e5](https://linux-hardware.org/?probe=b3752255e5) | Nov 13, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [a802e86d43](https://linux-hardware.org/?probe=a802e86d43) | Nov 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a39151865e](https://linux-hardware.org/?probe=a39151865e) | Nov 06, 2020 |
| HP            | ProBook 6450b               | Notebook    | [74c2b345b8](https://linux-hardware.org/?probe=74c2b345b8) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [5efbf0cf43](https://linux-hardware.org/?probe=5efbf0cf43) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3f9b54f16c](https://linux-hardware.org/?probe=3f9b54f16c) | Nov 05, 2020 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Lenovo        | G450 2949                   | Notebook    | [f9bb66b7a2](https://linux-hardware.org/?probe=f9bb66b7a2) | Nov 03, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [c4f1aaa3bb](https://linux-hardware.org/?probe=c4f1aaa3bb) | Nov 02, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [a283f0ab00](https://linux-hardware.org/?probe=a283f0ab00) | Nov 01, 2020 |
| ASUSTek       | X411UQ                      | Notebook    | [f3e110826b](https://linux-hardware.org/?probe=f3e110826b) | Nov 01, 2020 |
| ASUSTek       | X411UQ                      | Notebook    | [9786cce501](https://linux-hardware.org/?probe=9786cce501) | Nov 01, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [b252d0ad02](https://linux-hardware.org/?probe=b252d0ad02) | Oct 31, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [f08f791eaf](https://linux-hardware.org/?probe=f08f791eaf) | Oct 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [dcd8f2aa99](https://linux-hardware.org/?probe=dcd8f2aa99) | Oct 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cafb41376f](https://linux-hardware.org/?probe=cafb41376f) | Oct 26, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [fa89c085cf](https://linux-hardware.org/?probe=fa89c085cf) | Oct 25, 2020 |
| ASRock        | G31M-GS                     | Desktop     | [ed0373efb3](https://linux-hardware.org/?probe=ed0373efb3) | Oct 22, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [7157a6069b](https://linux-hardware.org/?probe=7157a6069b) | Oct 21, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [fb18c13ac7](https://linux-hardware.org/?probe=fb18c13ac7) | Oct 21, 2020 |
| MSI           | H81M-E33                    | Desktop     | [dc82b20825](https://linux-hardware.org/?probe=dc82b20825) | Oct 20, 2020 |
| MSI           | H81M-E33                    | Desktop     | [21a8676b32](https://linux-hardware.org/?probe=21a8676b32) | Oct 20, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d1e0bb32d7](https://linux-hardware.org/?probe=d1e0bb32d7) | Oct 19, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [89c3fe76c0](https://linux-hardware.org/?probe=89c3fe76c0) | Oct 18, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [0a4d06561e](https://linux-hardware.org/?probe=0a4d06561e) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [8fb2a0621d](https://linux-hardware.org/?probe=8fb2a0621d) | Oct 12, 2020 |
| Lenovo        | G40-45 80E1                 | Notebook    | [eefc7c92b2](https://linux-hardware.org/?probe=eefc7c92b2) | Oct 11, 2020 |
| Dell          | Latitude E7270              | Notebook    | [cff6ba0c00](https://linux-hardware.org/?probe=cff6ba0c00) | Oct 11, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [e04a055ab8](https://linux-hardware.org/?probe=e04a055ab8) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [c376c39381](https://linux-hardware.org/?probe=c376c39381) | Oct 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [4e2c32a972](https://linux-hardware.org/?probe=4e2c32a972) | Oct 07, 2020 |
| Dell          | Inspiron 3480               | Notebook    | [243905bcf2](https://linux-hardware.org/?probe=243905bcf2) | Oct 06, 2020 |
| Dell          | 0CXTWJ A00                  | All in one  | [d90e79c0b2](https://linux-hardware.org/?probe=d90e79c0b2) | Oct 05, 2020 |
| Lenovo        | ThinkCentre A58 7515A18     | Desktop     | [6d228ca955](https://linux-hardware.org/?probe=6d228ca955) | Oct 05, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [eaeba54519](https://linux-hardware.org/?probe=eaeba54519) | Oct 05, 2020 |
| MPS Mayori... | COIN ST800EDU               | Notebook    | [11e4ae4bfe](https://linux-hardware.org/?probe=11e4ae4bfe) | Oct 03, 2020 |
| MPS Mayori... | COIN ST800EDU               | Notebook    | [38a7d9f974](https://linux-hardware.org/?probe=38a7d9f974) | Oct 03, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [309b4ecbe6](https://linux-hardware.org/?probe=309b4ecbe6) | Oct 02, 2020 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [41c9698c88](https://linux-hardware.org/?probe=41c9698c88) | Oct 01, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [eb0e17a039](https://linux-hardware.org/?probe=eb0e17a039) | Oct 01, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e0afc29d83](https://linux-hardware.org/?probe=e0afc29d83) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [4ff7a5528c](https://linux-hardware.org/?probe=4ff7a5528c) | Sep 29, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [21ecdf1804](https://linux-hardware.org/?probe=21ecdf1804) | Sep 28, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [393e09d070](https://linux-hardware.org/?probe=393e09d070) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7ec7b7dbb0](https://linux-hardware.org/?probe=7ec7b7dbb0) | Sep 27, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c0ad55286f](https://linux-hardware.org/?probe=c0ad55286f) | Sep 26, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [be76b68bff](https://linux-hardware.org/?probe=be76b68bff) | Sep 25, 2020 |
| HP            | Notebook                    | Notebook    | [97099ba5b3](https://linux-hardware.org/?probe=97099ba5b3) | Sep 23, 2020 |
| Dell          | 0MM599                      | Desktop     | [bf8a1f8434](https://linux-hardware.org/?probe=bf8a1f8434) | Sep 22, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [4b3f7c31cc](https://linux-hardware.org/?probe=4b3f7c31cc) | Sep 21, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [bf2a498d90](https://linux-hardware.org/?probe=bf2a498d90) | Sep 21, 2020 |
| ASUSTek       | X441UVK                     | Notebook    | [4be17c95ab](https://linux-hardware.org/?probe=4be17c95ab) | Sep 18, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [b178b5269a](https://linux-hardware.org/?probe=b178b5269a) | Sep 18, 2020 |
| Dell          | Latitude E7270              | Notebook    | [76c31048e9](https://linux-hardware.org/?probe=76c31048e9) | Sep 14, 2020 |
| Toshiba       | Satellite U505              | Notebook    | [20507a8670](https://linux-hardware.org/?probe=20507a8670) | Sep 14, 2020 |
| TYAN Compu... | S4885 Thunder K8SQ S4885    | Server      | [64251b3f2a](https://linux-hardware.org/?probe=64251b3f2a) | Sep 12, 2020 |
| Dell          | Studio 1558                 | Notebook    | [bfa6ee72ad](https://linux-hardware.org/?probe=bfa6ee72ad) | Sep 11, 2020 |
| Dell          | Studio 1558                 | Notebook    | [09283ede94](https://linux-hardware.org/?probe=09283ede94) | Sep 11, 2020 |
| Acer          | TravelMate 5744             | Notebook    | [cd7e3646ff](https://linux-hardware.org/?probe=cd7e3646ff) | Sep 09, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [0a16cda83f](https://linux-hardware.org/?probe=0a16cda83f) | Sep 08, 2020 |
| Dell          | Inspiron N5040              | Notebook    | [7d81a97615](https://linux-hardware.org/?probe=7d81a97615) | Sep 07, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [4b2b8ed64f](https://linux-hardware.org/?probe=4b2b8ed64f) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [c184b08cc3](https://linux-hardware.org/?probe=c184b08cc3) | Sep 06, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [fcc32617ab](https://linux-hardware.org/?probe=fcc32617ab) | Sep 06, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [71698fa8ea](https://linux-hardware.org/?probe=71698fa8ea) | Sep 05, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [51936947d5](https://linux-hardware.org/?probe=51936947d5) | Sep 05, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [8f57e5d722](https://linux-hardware.org/?probe=8f57e5d722) | Sep 05, 2020 |
| PCSMART       | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [b641263269](https://linux-hardware.org/?probe=b641263269) | Sep 04, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [11adb16243](https://linux-hardware.org/?probe=11adb16243) | Sep 03, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [131299dd43](https://linux-hardware.org/?probe=131299dd43) | Sep 02, 2020 |
| ASUSTek       | X442UA                      | Notebook    | [cad592ae29](https://linux-hardware.org/?probe=cad592ae29) | Aug 31, 2020 |
| ASUSTek       | X442UA                      | Notebook    | [7697815bb5](https://linux-hardware.org/?probe=7697815bb5) | Aug 31, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| HP            | ProBook 440 G3              | Notebook    | [1e65e31e23](https://linux-hardware.org/?probe=1e65e31e23) | Aug 30, 2020 |
| Samsung       | R430/R480/R440              | Notebook    | [c37003dbfc](https://linux-hardware.org/?probe=c37003dbfc) | Aug 30, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c7c173a4d6](https://linux-hardware.org/?probe=c7c173a4d6) | Aug 28, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [c1fe24f51b](https://linux-hardware.org/?probe=c1fe24f51b) | Aug 28, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [07445986db](https://linux-hardware.org/?probe=07445986db) | Aug 24, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [eb0990afbe](https://linux-hardware.org/?probe=eb0990afbe) | Aug 23, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [f43e5244bc](https://linux-hardware.org/?probe=f43e5244bc) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7b4fcb3693](https://linux-hardware.org/?probe=7b4fcb3693) | Aug 21, 2020 |
| Dell          | 0D6H9T A01                  | Desktop     | [9c13b5e775](https://linux-hardware.org/?probe=9c13b5e775) | Aug 20, 2020 |
| Dell          | 0D6H9T A01                  | Desktop     | [40b95dab91](https://linux-hardware.org/?probe=40b95dab91) | Aug 20, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [2a6af22359](https://linux-hardware.org/?probe=2a6af22359) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [27987ebfb1](https://linux-hardware.org/?probe=27987ebfb1) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [6edc3d456f](https://linux-hardware.org/?probe=6edc3d456f) | Aug 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2151fb7ccb](https://linux-hardware.org/?probe=2151fb7ccb) | Aug 15, 2020 |
| MSI           | A68HM-E33                   | Desktop     | [819dd19a0e](https://linux-hardware.org/?probe=819dd19a0e) | Aug 14, 2020 |
| ASUSTek       | H110-PLUS                   | Desktop     | [28a6907d78](https://linux-hardware.org/?probe=28a6907d78) | Aug 14, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [a10db0a0f1](https://linux-hardware.org/?probe=a10db0a0f1) | Aug 13, 2020 |
| Acer          | AOD255                      | Notebook    | [627daa28b5](https://linux-hardware.org/?probe=627daa28b5) | Aug 11, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2a6b9c2763](https://linux-hardware.org/?probe=2a6b9c2763) | Aug 11, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76ee87fa06](https://linux-hardware.org/?probe=76ee87fa06) | Aug 07, 2020 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [95f6d41901](https://linux-hardware.org/?probe=95f6d41901) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c958c50dad](https://linux-hardware.org/?probe=c958c50dad) | Aug 07, 2020 |
| HP            | ENVY 15                     | Notebook    | [d2fab519a5](https://linux-hardware.org/?probe=d2fab519a5) | Aug 04, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Toshiba       | Satellite L645              | Notebook    | [2f81e753a6](https://linux-hardware.org/?probe=2f81e753a6) | Jul 31, 2020 |
| HP            | 245 G6                      | Notebook    | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [1b4b43f382](https://linux-hardware.org/?probe=1b4b43f382) | Jul 29, 2020 |
| HP            | G42                         | Notebook    | [80828bd820](https://linux-hardware.org/?probe=80828bd820) | Jul 29, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0928c9c524](https://linux-hardware.org/?probe=0928c9c524) | Jul 27, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [26022f582b](https://linux-hardware.org/?probe=26022f582b) | Jul 26, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [74cad2f13e](https://linux-hardware.org/?probe=74cad2f13e) | Jul 26, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [75928e5332](https://linux-hardware.org/?probe=75928e5332) | Jul 25, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b4f52ba1be](https://linux-hardware.org/?probe=b4f52ba1be) | Jul 25, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [17ecc94bc0](https://linux-hardware.org/?probe=17ecc94bc0) | Jul 24, 2020 |
| Toshiba       | Satellite M505              | Notebook    | [518faca568](https://linux-hardware.org/?probe=518faca568) | Jul 21, 2020 |
| Toshiba       | Satellite S75-A             | Notebook    | [a2fc5378af](https://linux-hardware.org/?probe=a2fc5378af) | Jul 21, 2020 |
| Toshiba       | Satellite M505              | Notebook    | [64f79b1c45](https://linux-hardware.org/?probe=64f79b1c45) | Jul 21, 2020 |
| Dell          | Latitude E7270              | Notebook    | [3240f0ae94](https://linux-hardware.org/?probe=3240f0ae94) | Jul 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1839ba41d3](https://linux-hardware.org/?probe=1839ba41d3) | Jul 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f179e69271](https://linux-hardware.org/?probe=f179e69271) | Jul 19, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [543185b30a](https://linux-hardware.org/?probe=543185b30a) | Jul 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e66cd74e47](https://linux-hardware.org/?probe=e66cd74e47) | Jul 18, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [67b506f12f](https://linux-hardware.org/?probe=67b506f12f) | Jul 16, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [65d309fa0f](https://linux-hardware.org/?probe=65d309fa0f) | Jul 16, 2020 |
| ASUSTek       | X456UA                      | Notebook    | [0bc503ae0b](https://linux-hardware.org/?probe=0bc503ae0b) | Jul 16, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8a858d88d0](https://linux-hardware.org/?probe=8a858d88d0) | Jul 15, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [260563b336](https://linux-hardware.org/?probe=260563b336) | Jul 15, 2020 |
| Gigabyte      | X570 UD                     | Desktop     | [dffcf158e7](https://linux-hardware.org/?probe=dffcf158e7) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [38242e89d2](https://linux-hardware.org/?probe=38242e89d2) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c4e21ddab2](https://linux-hardware.org/?probe=c4e21ddab2) | Jul 12, 2020 |
| ASUSTek       | X456UA                      | Notebook    | [6b61996456](https://linux-hardware.org/?probe=6b61996456) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [858cd73913](https://linux-hardware.org/?probe=858cd73913) | Jul 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [fc5d45e94a](https://linux-hardware.org/?probe=fc5d45e94a) | Jul 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f24093f04f](https://linux-hardware.org/?probe=f24093f04f) | Jul 09, 2020 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [b97d60900c](https://linux-hardware.org/?probe=b97d60900c) | Jul 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a57a22212c](https://linux-hardware.org/?probe=a57a22212c) | Jul 06, 2020 |
| ECS           | G31T-M7                     | Desktop     | [95cb3298ec](https://linux-hardware.org/?probe=95cb3298ec) | Jul 05, 2020 |
| ECS           | G31T-M7                     | Desktop     | [56b5cd6eac](https://linux-hardware.org/?probe=56b5cd6eac) | Jul 05, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [58e16275bc](https://linux-hardware.org/?probe=58e16275bc) | Jul 04, 2020 |
| HP            | Compaq 6730s                | Notebook    | [e128a9542c](https://linux-hardware.org/?probe=e128a9542c) | Jul 04, 2020 |
| Sony          | VAIO                        | All in one  | [f52b60725c](https://linux-hardware.org/?probe=f52b60725c) | Jul 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [dd5e302721](https://linux-hardware.org/?probe=dd5e302721) | Jul 03, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [ed75f47aa0](https://linux-hardware.org/?probe=ed75f47aa0) | Jun 30, 2020 |
| ASUSTek       | K46CM                       | Notebook    | [5260584205](https://linux-hardware.org/?probe=5260584205) | Jun 30, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [0999108dfb](https://linux-hardware.org/?probe=0999108dfb) | Jun 29, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [3cda40d161](https://linux-hardware.org/?probe=3cda40d161) | Jun 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aba4b6462f](https://linux-hardware.org/?probe=aba4b6462f) | Jun 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [a54dfa2b8b](https://linux-hardware.org/?probe=a54dfa2b8b) | Jun 27, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [fae71e18b2](https://linux-hardware.org/?probe=fae71e18b2) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [7e4c8ea12c](https://linux-hardware.org/?probe=7e4c8ea12c) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [5e921d68ff](https://linux-hardware.org/?probe=5e921d68ff) | Jun 25, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [9dfcf2f0cb](https://linux-hardware.org/?probe=9dfcf2f0cb) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f90ccba28d](https://linux-hardware.org/?probe=f90ccba28d) | Jun 23, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7e8026e797](https://linux-hardware.org/?probe=7e8026e797) | Jun 22, 2020 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [29f9ac42d8](https://linux-hardware.org/?probe=29f9ac42d8) | Jun 21, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [c8a9bbbaa0](https://linux-hardware.org/?probe=c8a9bbbaa0) | Jun 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [9a14812888](https://linux-hardware.org/?probe=9a14812888) | Jun 20, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3b75e28c9d](https://linux-hardware.org/?probe=3b75e28c9d) | Jun 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [73cda410f2](https://linux-hardware.org/?probe=73cda410f2) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a7d7f2f4f3](https://linux-hardware.org/?probe=a7d7f2f4f3) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d194146ff8](https://linux-hardware.org/?probe=d194146ff8) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5b4fdab686](https://linux-hardware.org/?probe=5b4fdab686) | Jun 18, 2020 |
| Biostar       | N68S3+                      | Desktop     | [3d289fd6d2](https://linux-hardware.org/?probe=3d289fd6d2) | Jun 15, 2020 |
| HP            | 8245 001                    | All in one  | [b348bc9186](https://linux-hardware.org/?probe=b348bc9186) | Jun 13, 2020 |
| HP            | 8245 001                    | All in one  | [3d2e0b5d1e](https://linux-hardware.org/?probe=3d2e0b5d1e) | Jun 13, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [a1ae232e58](https://linux-hardware.org/?probe=a1ae232e58) | Jun 13, 2020 |
| Acer          | Aspire 5532                 | Notebook    | [ce8deb0caa](https://linux-hardware.org/?probe=ce8deb0caa) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | Notebook    | [cc0f65e016](https://linux-hardware.org/?probe=cc0f65e016) | Jun 12, 2020 |
| Dell          | 054KM3 A00                  | Desktop     | [3e9f988a30](https://linux-hardware.org/?probe=3e9f988a30) | Jun 11, 2020 |
| Apple         | Mac-F2268CC8                | All in one  | [2212090ff2](https://linux-hardware.org/?probe=2212090ff2) | Jun 10, 2020 |
| Gateway       | M-6319                      | Notebook    | [5b3e8b9ef1](https://linux-hardware.org/?probe=5b3e8b9ef1) | Jun 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [52c8b6876e](https://linux-hardware.org/?probe=52c8b6876e) | Jun 08, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [aad1de590c](https://linux-hardware.org/?probe=aad1de590c) | Jun 07, 2020 |
| Acer          | Aspire E1-421               | Notebook    | [81073e838e](https://linux-hardware.org/?probe=81073e838e) | Jun 05, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [e7901f9d16](https://linux-hardware.org/?probe=e7901f9d16) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | Notebook    | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [9585e46a59](https://linux-hardware.org/?probe=9585e46a59) | Jun 04, 2020 |
| Lenovo        | ThinkPad T430u 86143HU      | Notebook    | [5a3bf0a8f5](https://linux-hardware.org/?probe=5a3bf0a8f5) | Jun 03, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [d45d40decd](https://linux-hardware.org/?probe=d45d40decd) | Jun 03, 2020 |
| ASUSTek       | K46CM                       | Notebook    | [994e39c619](https://linux-hardware.org/?probe=994e39c619) | Jun 02, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [841614c2d1](https://linux-hardware.org/?probe=841614c2d1) | Jun 01, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [8126e4dea3](https://linux-hardware.org/?probe=8126e4dea3) | Jun 01, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [8143bab4c5](https://linux-hardware.org/?probe=8143bab4c5) | May 30, 2020 |
| Acer          | Aspire E1-421               | Notebook    | [618908f152](https://linux-hardware.org/?probe=618908f152) | May 27, 2020 |
| ASUSTek       | X411UQ                      | Notebook    | [a3e9e016a6](https://linux-hardware.org/?probe=a3e9e016a6) | May 27, 2020 |
| Lenovo        | ThinkPad A475 20KMS0NG00    | Notebook    | [4572fa1657](https://linux-hardware.org/?probe=4572fa1657) | May 27, 2020 |
| Dell          | Inspiron 5521               | Notebook    | [169492fdd8](https://linux-hardware.org/?probe=169492fdd8) | May 26, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [871784f430](https://linux-hardware.org/?probe=871784f430) | May 26, 2020 |
| HP            | 430                         | Notebook    | [54ba3df0c8](https://linux-hardware.org/?probe=54ba3df0c8) | May 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c4c76cecbd](https://linux-hardware.org/?probe=c4c76cecbd) | May 23, 2020 |
| Lenovo        | 36DC SDK0J40679 WIN 3273... | All in one  | [a4afd5181f](https://linux-hardware.org/?probe=a4afd5181f) | May 23, 2020 |
| Lenovo        | 36DC SDK0J40679 WIN 3273... | All in one  | [3a811fe4cb](https://linux-hardware.org/?probe=3a811fe4cb) | May 23, 2020 |
| MSI           | A55M-P35                    | Desktop     | [1816e90106](https://linux-hardware.org/?probe=1816e90106) | May 22, 2020 |
| HP            | Laptop 14-bw0xx             | Notebook    | [c9c485db32](https://linux-hardware.org/?probe=c9c485db32) | May 22, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [a0a6bd1e26](https://linux-hardware.org/?probe=a0a6bd1e26) | May 22, 2020 |
| Sony          | SVF14A15CLB                 | Notebook    | [7fb2e1bda0](https://linux-hardware.org/?probe=7fb2e1bda0) | May 20, 2020 |
| Samsung       | 535U3C                      | Notebook    | [b3983a1b17](https://linux-hardware.org/?probe=b3983a1b17) | May 20, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| Lenovo        | Larne CRB 31900059 STD      | All in one  | [92b26540f0](https://linux-hardware.org/?probe=92b26540f0) | May 18, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [fe9c89b85a](https://linux-hardware.org/?probe=fe9c89b85a) | May 17, 2020 |
| Lenovo        | Larne CRB 31900059 STD      | All in one  | [6da745bc99](https://linux-hardware.org/?probe=6da745bc99) | May 17, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [dc1d621a65](https://linux-hardware.org/?probe=dc1d621a65) | May 15, 2020 |
| Lenovo        | G40-80 80E4                 | Notebook    | [70a6d29aa3](https://linux-hardware.org/?probe=70a6d29aa3) | May 15, 2020 |
| Samsung       | 535U3C                      | Notebook    | [fe2d93033d](https://linux-hardware.org/?probe=fe2d93033d) | May 13, 2020 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [c54d7ef6ee](https://linux-hardware.org/?probe=c54d7ef6ee) | May 10, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [5ed9a929ec](https://linux-hardware.org/?probe=5ed9a929ec) | May 10, 2020 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [cbf18515b3](https://linux-hardware.org/?probe=cbf18515b3) | May 10, 2020 |
| Sony          | SVE14121CLP                 | Notebook    | [df7e4c2b9f](https://linux-hardware.org/?probe=df7e4c2b9f) | May 09, 2020 |
| ASRock        | G965M-S                     | Desktop     | [9d4cff9871](https://linux-hardware.org/?probe=9d4cff9871) | May 05, 2020 |
| PCChips       | P17G ECS                    | Desktop     | [8220dc9d9a](https://linux-hardware.org/?probe=8220dc9d9a) | May 04, 2020 |
| HP            | 8381 1000                   | All in one  | [abf977e38b](https://linux-hardware.org/?probe=abf977e38b) | May 03, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [c8dd8d2166](https://linux-hardware.org/?probe=c8dd8d2166) | May 02, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [69942e79bd](https://linux-hardware.org/?probe=69942e79bd) | May 02, 2020 |
| Lenovo        | Larne CRB 31900059 WIN 2... | All in one  | [a7430e2754](https://linux-hardware.org/?probe=a7430e2754) | May 01, 2020 |
| Gigabyte      | H170-Gaming 3 DDR3          | Desktop     | [b6540749a2](https://linux-hardware.org/?probe=b6540749a2) | May 01, 2020 |
| HP            | 8381 1000                   | All in one  | [97a3637eb5](https://linux-hardware.org/?probe=97a3637eb5) | Apr 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [91627f8ac4](https://linux-hardware.org/?probe=91627f8ac4) | Apr 29, 2020 |
| Toshiba       | Satellite L515              | Notebook    | [c411228b1a](https://linux-hardware.org/?probe=c411228b1a) | Apr 28, 2020 |
| Inspur        | M11JB R2.0/R1.1             | Notebook    | [7f92b47ef4](https://linux-hardware.org/?probe=7f92b47ef4) | Apr 27, 2020 |
| HP            | Pavilion dv6                | Notebook    | [163dac19b3](https://linux-hardware.org/?probe=163dac19b3) | Apr 26, 2020 |
| HP            | Pavilion dv6                | Notebook    | [13cb9e8a90](https://linux-hardware.org/?probe=13cb9e8a90) | Apr 26, 2020 |
| MSI           | 970A-G43 PLUS               | Desktop     | [50a3cd26c8](https://linux-hardware.org/?probe=50a3cd26c8) | Apr 25, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [f429ce4848](https://linux-hardware.org/?probe=f429ce4848) | Apr 22, 2020 |
| Dell          | G5 5587                     | Notebook    | [dd4521b554](https://linux-hardware.org/?probe=dd4521b554) | Apr 21, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e5243ea838](https://linux-hardware.org/?probe=e5243ea838) | Apr 21, 2020 |
| HP            | Pavilion g4                 | Notebook    | [7e9785b653](https://linux-hardware.org/?probe=7e9785b653) | Apr 18, 2020 |
| ASUSTek       | X453SA                      | Notebook    | [ce1bd3affc](https://linux-hardware.org/?probe=ce1bd3affc) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| HP            | Pavilion g4                 | Notebook    | [3c6a4199c7](https://linux-hardware.org/?probe=3c6a4199c7) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Acer          | Aspire V5-471               | Notebook    | [6540209d65](https://linux-hardware.org/?probe=6540209d65) | Apr 16, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [010fdcb7ab](https://linux-hardware.org/?probe=010fdcb7ab) | Apr 16, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [8eae2753ce](https://linux-hardware.org/?probe=8eae2753ce) | Apr 16, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6ec2d663e5](https://linux-hardware.org/?probe=6ec2d663e5) | Apr 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a4b76d231e](https://linux-hardware.org/?probe=a4b76d231e) | Apr 15, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [2392a43f27](https://linux-hardware.org/?probe=2392a43f27) | Apr 14, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [50809e26ed](https://linux-hardware.org/?probe=50809e26ed) | Apr 14, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [cb760929c4](https://linux-hardware.org/?probe=cb760929c4) | Apr 14, 2020 |
| MSI           | MS-7309                     | Desktop     | [598ba6983d](https://linux-hardware.org/?probe=598ba6983d) | Apr 14, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [33747354e3](https://linux-hardware.org/?probe=33747354e3) | Apr 13, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [06fa247c32](https://linux-hardware.org/?probe=06fa247c32) | Apr 13, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [25e23d0bf7](https://linux-hardware.org/?probe=25e23d0bf7) | Apr 13, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | Notebook    | [823afb58b0](https://linux-hardware.org/?probe=823afb58b0) | Apr 12, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | Notebook    | [90b23eb96e](https://linux-hardware.org/?probe=90b23eb96e) | Apr 12, 2020 |
| Dell          | System Inspiron 5420        | Notebook    | [f74d698b46](https://linux-hardware.org/?probe=f74d698b46) | Apr 11, 2020 |
| Toshiba       | Satellite A505              | Notebook    | [f7f3c03ad9](https://linux-hardware.org/?probe=f7f3c03ad9) | Apr 10, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c4c866db0d](https://linux-hardware.org/?probe=c4c866db0d) | Apr 04, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0bb263546b](https://linux-hardware.org/?probe=0bb263546b) | Apr 04, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [6e2105feb5](https://linux-hardware.org/?probe=6e2105feb5) | Apr 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f9921167fc](https://linux-hardware.org/?probe=f9921167fc) | Apr 02, 2020 |
| HP            | Mini 311-1100               | Notebook    | [d4918f7f3c](https://linux-hardware.org/?probe=d4918f7f3c) | Mar 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b3c0d80908](https://linux-hardware.org/?probe=b3c0d80908) | Mar 26, 2020 |
| ASUSTek       | X455LD                      | Notebook    | [ec6c4486ca](https://linux-hardware.org/?probe=ec6c4486ca) | Mar 26, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [60f3879e96](https://linux-hardware.org/?probe=60f3879e96) | Mar 25, 2020 |
| Acer          | Aspire 4750                 | Notebook    | [4757577c86](https://linux-hardware.org/?probe=4757577c86) | Mar 23, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [38330a61d2](https://linux-hardware.org/?probe=38330a61d2) | Mar 23, 2020 |
| Lenovo        | ThinkPad T480 20L6S0VE00    | Notebook    | [4d090cecde](https://linux-hardware.org/?probe=4d090cecde) | Mar 22, 2020 |
| HP            | 3048h                       | Desktop     | [6b07a41174](https://linux-hardware.org/?probe=6b07a41174) | Mar 22, 2020 |
| ASRock        | H61M-VG4                    | Desktop     | [9a17b3a770](https://linux-hardware.org/?probe=9a17b3a770) | Mar 21, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [38d4ca1005](https://linux-hardware.org/?probe=38d4ca1005) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [d42c9c08ee](https://linux-hardware.org/?probe=d42c9c08ee) | Mar 19, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [1279383fb8](https://linux-hardware.org/?probe=1279383fb8) | Mar 17, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [68013dac14](https://linux-hardware.org/?probe=68013dac14) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [df4df13e54](https://linux-hardware.org/?probe=df4df13e54) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [12b38c9ebd](https://linux-hardware.org/?probe=12b38c9ebd) | Mar 16, 2020 |
| ASUSTek       | X505BP                      | Notebook    | [11da78a649](https://linux-hardware.org/?probe=11da78a649) | Mar 16, 2020 |
| Google        | Pantheon                    | Notebook    | [20acb09771](https://linux-hardware.org/?probe=20acb09771) | Mar 09, 2020 |
| Sony          | VGN-SR51MF_S                | Notebook    | [8783bf4fe5](https://linux-hardware.org/?probe=8783bf4fe5) | Mar 09, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [def3aa7871](https://linux-hardware.org/?probe=def3aa7871) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [6dccf0159e](https://linux-hardware.org/?probe=6dccf0159e) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [6ec6d9847c](https://linux-hardware.org/?probe=6ec6d9847c) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [e5c1b0bdce](https://linux-hardware.org/?probe=e5c1b0bdce) | Mar 07, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [20a4bdc803](https://linux-hardware.org/?probe=20a4bdc803) | Mar 05, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b4898d9e36](https://linux-hardware.org/?probe=b4898d9e36) | Mar 05, 2020 |
| ASUSTek       | X505BP                      | Notebook    | [88ec1bf424](https://linux-hardware.org/?probe=88ec1bf424) | Feb 29, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [fd8dfe766e](https://linux-hardware.org/?probe=fd8dfe766e) | Feb 24, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [96c28903af](https://linux-hardware.org/?probe=96c28903af) | Feb 24, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [1ee504b68f](https://linux-hardware.org/?probe=1ee504b68f) | Feb 24, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [c74cb1d856](https://linux-hardware.org/?probe=c74cb1d856) | Feb 22, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [239a155579](https://linux-hardware.org/?probe=239a155579) | Feb 22, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [303f2ada85](https://linux-hardware.org/?probe=303f2ada85) | Feb 19, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | Notebook    | [968045d52d](https://linux-hardware.org/?probe=968045d52d) | Feb 19, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [ed95aa0537](https://linux-hardware.org/?probe=ed95aa0537) | Feb 16, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [84c6ace757](https://linux-hardware.org/?probe=84c6ace757) | Feb 15, 2020 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [d0276ea845](https://linux-hardware.org/?probe=d0276ea845) | Feb 14, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [1d69448de6](https://linux-hardware.org/?probe=1d69448de6) | Feb 09, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [6d4ecdb510](https://linux-hardware.org/?probe=6d4ecdb510) | Feb 09, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | Notebook    | [30b395a14f](https://linux-hardware.org/?probe=30b395a14f) | Feb 08, 2020 |
| Dell          | Vostro 3400                 | Notebook    | [7ad384214e](https://linux-hardware.org/?probe=7ad384214e) | Feb 06, 2020 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [c59fbe99a2](https://linux-hardware.org/?probe=c59fbe99a2) | Feb 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8f38f0a1e3](https://linux-hardware.org/?probe=8f38f0a1e3) | Jan 20, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [b3a11d5f5d](https://linux-hardware.org/?probe=b3a11d5f5d) | Jan 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [25f6d11655](https://linux-hardware.org/?probe=25f6d11655) | Jan 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [94b406a65f](https://linux-hardware.org/?probe=94b406a65f) | Jan 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cf5b83db0d](https://linux-hardware.org/?probe=cf5b83db0d) | Jan 08, 2020 |
| ASUSTek       | X550ZE                      | Notebook    | [e06f76becf](https://linux-hardware.org/?probe=e06f76becf) | Jan 08, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [30389049c2](https://linux-hardware.org/?probe=30389049c2) | Jan 07, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [06421a5c44](https://linux-hardware.org/?probe=06421a5c44) | Jan 05, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [db9c0c83ce](https://linux-hardware.org/?probe=db9c0c83ce) | Jan 03, 2020 |
| Dell          | 0P301D A00                  | Desktop     | [298fac1e53](https://linux-hardware.org/?probe=298fac1e53) | Jan 03, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [854604bdad](https://linux-hardware.org/?probe=854604bdad) | Dec 31, 2019 |
| ASRock        | G41M-VS3                    | Desktop     | [c4c975b9f9](https://linux-hardware.org/?probe=c4c975b9f9) | Dec 29, 2019 |
| Dell          | Inspiron 5423               | Notebook    | [ed50d52b54](https://linux-hardware.org/?probe=ed50d52b54) | Dec 28, 2019 |
| Dell          | Inspiron 5423               | Notebook    | [5b5632e40c](https://linux-hardware.org/?probe=5b5632e40c) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b6846dfd95](https://linux-hardware.org/?probe=b6846dfd95) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [75a94cfe2f](https://linux-hardware.org/?probe=75a94cfe2f) | Dec 28, 2019 |
| Unknown       | GSUO H61V10C                | Desktop     | [96d964a1d9](https://linux-hardware.org/?probe=96d964a1d9) | Dec 23, 2019 |
| Dell          | Inspiron 5748               | Notebook    | [17ed1f4194](https://linux-hardware.org/?probe=17ed1f4194) | Dec 22, 2019 |
| HP            | Laptop 14-bp0xx             | Notebook    | [c99b71d804](https://linux-hardware.org/?probe=c99b71d804) | Dec 18, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [04a6d42a9c](https://linux-hardware.org/?probe=04a6d42a9c) | Dec 16, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [e142be5f58](https://linux-hardware.org/?probe=e142be5f58) | Dec 16, 2019 |
| Lenovo        | 36DA SDK0J40679 WIN 3273... | All in one  | [de2a851c8f](https://linux-hardware.org/?probe=de2a851c8f) | Dec 12, 2019 |
| Lenovo        | 36DA SDK0J40679 WIN 3273... | All in one  | [427c0eea33](https://linux-hardware.org/?probe=427c0eea33) | Dec 12, 2019 |
| Lenovo        | G40-45 80E1                 | Notebook    | [b1f6e07d2b](https://linux-hardware.org/?probe=b1f6e07d2b) | Dec 09, 2019 |
| HP            | Pavilion 10 TS              | Notebook    | [fbe754b72c](https://linux-hardware.org/?probe=fbe754b72c) | Nov 29, 2019 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d78bbdfa2a](https://linux-hardware.org/?probe=d78bbdfa2a) | Nov 18, 2019 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [7e957006e4](https://linux-hardware.org/?probe=7e957006e4) | Nov 18, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb6e592c0d](https://linux-hardware.org/?probe=cb6e592c0d) | Nov 18, 2019 |
| ASUSTek       | 1005HA                      | Notebook    | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [9515caaefa](https://linux-hardware.org/?probe=9515caaefa) | Nov 17, 2019 |
| ASRock        | H55M                        | Desktop     | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | Desktop     | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [4e2ba6330f](https://linux-hardware.org/?probe=4e2ba6330f) | Nov 09, 2019 |
| Lenovo        | ThinkPad E460 20EUA00900    | Notebook    | [a549aed5b4](https://linux-hardware.org/?probe=a549aed5b4) | Nov 08, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [36570780b5](https://linux-hardware.org/?probe=36570780b5) | Oct 30, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [5d4e6e95f1](https://linux-hardware.org/?probe=5d4e6e95f1) | Oct 30, 2019 |
| Dell          | XPS 15 9550                 | Notebook    | [7323abf391](https://linux-hardware.org/?probe=7323abf391) | Oct 29, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [4270a9638b](https://linux-hardware.org/?probe=4270a9638b) | Oct 29, 2019 |
| Dell          | XPS 15 9550                 | Notebook    | [c70f66f439](https://linux-hardware.org/?probe=c70f66f439) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [666b6342e0](https://linux-hardware.org/?probe=666b6342e0) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [36c76546e9](https://linux-hardware.org/?probe=36c76546e9) | Oct 29, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [3469bcd886](https://linux-hardware.org/?probe=3469bcd886) | Oct 28, 2019 |
| HP            | Laptop 14-bp0xx             | Notebook    | [2e6a129f3e](https://linux-hardware.org/?probe=2e6a129f3e) | Oct 24, 2019 |
| VIT           | P2412                       | Notebook    | [2604d0b890](https://linux-hardware.org/?probe=2604d0b890) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6206eb1a2f](https://linux-hardware.org/?probe=6206eb1a2f) | Oct 11, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [9a54660b4f](https://linux-hardware.org/?probe=9a54660b4f) | Oct 11, 2019 |
| MSI           | MS-7309                     | Desktop     | [2e6203af14](https://linux-hardware.org/?probe=2e6203af14) | Oct 09, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [d98faab3bc](https://linux-hardware.org/?probe=d98faab3bc) | Oct 09, 2019 |
| Toshiba       | NB 105                      | Notebook    | [07f2ac3953](https://linux-hardware.org/?probe=07f2ac3953) | Oct 08, 2019 |
| Toshiba       | NB 105                      | Notebook    | [56d1fb0551](https://linux-hardware.org/?probe=56d1fb0551) | Oct 08, 2019 |
| ASUSTek       | X505BP                      | Notebook    | [147a0012a9](https://linux-hardware.org/?probe=147a0012a9) | Oct 08, 2019 |
| HP            | Pavilion 10 TS              | Notebook    | [f1d915aa56](https://linux-hardware.org/?probe=f1d915aa56) | Oct 06, 2019 |
| Acer          | Aspire E3-111               | Notebook    | [cb12dc0dcd](https://linux-hardware.org/?probe=cb12dc0dcd) | Sep 18, 2019 |
| Chuwi         | LapBook Plus                | Notebook    | [2cc2dc7812](https://linux-hardware.org/?probe=2cc2dc7812) | Sep 15, 2019 |
| Samsung       | 535U3C                      | Notebook    | [3605b4bcc2](https://linux-hardware.org/?probe=3605b4bcc2) | Sep 15, 2019 |
| Fujitsu       | LIFEBOOK T734               | Notebook    | [38a59cafac](https://linux-hardware.org/?probe=38a59cafac) | Sep 07, 2019 |
| Acer          | Aspire E1-571               | Notebook    | [f7809cd921](https://linux-hardware.org/?probe=f7809cd921) | Sep 06, 2019 |
| HP            | 240 G4 Notebook PC          | Notebook    | [c29c743021](https://linux-hardware.org/?probe=c29c743021) | Sep 06, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [3181aa4496](https://linux-hardware.org/?probe=3181aa4496) | Sep 02, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [47661b90c1](https://linux-hardware.org/?probe=47661b90c1) | Aug 31, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e4ca853a88](https://linux-hardware.org/?probe=e4ca853a88) | Aug 30, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ebb5e97cc6](https://linux-hardware.org/?probe=ebb5e97cc6) | Aug 30, 2019 |
| Samsung       | 535U3C                      | Notebook    | [05752face4](https://linux-hardware.org/?probe=05752face4) | Aug 29, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f063afeba7](https://linux-hardware.org/?probe=f063afeba7) | Aug 28, 2019 |
| Lenovo        | G40-80 80E4                 | Notebook    | [386e041ee1](https://linux-hardware.org/?probe=386e041ee1) | Aug 27, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [934edb8a8d](https://linux-hardware.org/?probe=934edb8a8d) | Aug 19, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [d9d655f7eb](https://linux-hardware.org/?probe=d9d655f7eb) | Aug 19, 2019 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c3f8c454d5](https://linux-hardware.org/?probe=c3f8c454d5) | Aug 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [60d6ad276f](https://linux-hardware.org/?probe=60d6ad276f) | Aug 16, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9b10892d1f](https://linux-hardware.org/?probe=9b10892d1f) | Aug 12, 2019 |
| HP            | 81B9 1000                   | All in one  | [15c46542b5](https://linux-hardware.org/?probe=15c46542b5) | Aug 11, 2019 |
| HP            | 81B9 1000                   | All in one  | [c1e56da320](https://linux-hardware.org/?probe=c1e56da320) | Aug 11, 2019 |
| HP            | 240 G4 Notebook PC          | Notebook    | [8abebd7b2f](https://linux-hardware.org/?probe=8abebd7b2f) | Jul 31, 2019 |
| ASUSTek       | G73Jw                       | Notebook    | [34c2f4a1e6](https://linux-hardware.org/?probe=34c2f4a1e6) | Jul 31, 2019 |
| Acer          | Aspire V3-471               | Notebook    | [6e533b7623](https://linux-hardware.org/?probe=6e533b7623) | Jul 29, 2019 |
| HP            | ProLiant ML115 G1           | Desktop     | [8f0d70a883](https://linux-hardware.org/?probe=8f0d70a883) | Jul 29, 2019 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [7637f3de5f](https://linux-hardware.org/?probe=7637f3de5f) | Jul 28, 2019 |
| Dell          | OptiPlex GX260              | Desktop     | [6c061a7a15](https://linux-hardware.org/?probe=6c061a7a15) | Jul 23, 2019 |
| Acer          | Aspire 4750                 | Notebook    | [481b67d08f](https://linux-hardware.org/?probe=481b67d08f) | Jul 22, 2019 |
| HP            | Pavilion tx1000             | Notebook    | [4a6a073320](https://linux-hardware.org/?probe=4a6a073320) | Jul 22, 2019 |
| Acer          | Aspire 4750                 | Notebook    | [bf530b04c7](https://linux-hardware.org/?probe=bf530b04c7) | Jul 22, 2019 |
| HP            | Presario CQ43               | Notebook    | [4201cdd966](https://linux-hardware.org/?probe=4201cdd966) | Jul 20, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [b124f401f6](https://linux-hardware.org/?probe=b124f401f6) | Jul 17, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [ca74df306b](https://linux-hardware.org/?probe=ca74df306b) | Jul 14, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [c75d45bec4](https://linux-hardware.org/?probe=c75d45bec4) | Jul 14, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [05497b6d61](https://linux-hardware.org/?probe=05497b6d61) | Jul 12, 2019 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c4d6a7bc54](https://linux-hardware.org/?probe=c4d6a7bc54) | Jul 07, 2019 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [3462cd0ccd](https://linux-hardware.org/?probe=3462cd0ccd) | Jul 07, 2019 |
| MSI           | MS-7191                     | Desktop     | [d753273d7b](https://linux-hardware.org/?probe=d753273d7b) | Jul 03, 2019 |
| Dell          | 0RY206                      | Desktop     | [aed7ab6e58](https://linux-hardware.org/?probe=aed7ab6e58) | Jun 28, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [7a8cfa539b](https://linux-hardware.org/?probe=7a8cfa539b) | Jun 23, 2019 |
| HP            | ProBook 440 G2              | Notebook    | [592064f97e](https://linux-hardware.org/?probe=592064f97e) | Jun 23, 2019 |
| ASUSTek       | X542URR                     | Notebook    | [adf12d067f](https://linux-hardware.org/?probe=adf12d067f) | Jun 19, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3cecb13c13](https://linux-hardware.org/?probe=3cecb13c13) | Jun 18, 2019 |
| Gigabyte      | H81M-H                      | Desktop     | [bebf195e43](https://linux-hardware.org/?probe=bebf195e43) | Jun 18, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [af291d02cf](https://linux-hardware.org/?probe=af291d02cf) | Jun 17, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7061046667](https://linux-hardware.org/?probe=7061046667) | Jun 15, 2019 |
| HP            | Pavilion dm1                | Notebook    | [01e9de8250](https://linux-hardware.org/?probe=01e9de8250) | Jun 13, 2019 |
| HP            | Pavilion dm1                | Notebook    | [40f5482a9d](https://linux-hardware.org/?probe=40f5482a9d) | Jun 13, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f69654fec4](https://linux-hardware.org/?probe=f69654fec4) | Jun 13, 2019 |
| ASUSTek       | X455LAB                     | Notebook    | [6fc7fb8c0e](https://linux-hardware.org/?probe=6fc7fb8c0e) | Jun 12, 2019 |
| ASUSTek       | X455LAB                     | Notebook    | [a8004d007d](https://linux-hardware.org/?probe=a8004d007d) | Jun 12, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [cb1771b144](https://linux-hardware.org/?probe=cb1771b144) | Jun 12, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ca315cb07b](https://linux-hardware.org/?probe=ca315cb07b) | Jun 12, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [5e80fdb647](https://linux-hardware.org/?probe=5e80fdb647) | Jun 11, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8eaae370e1](https://linux-hardware.org/?probe=8eaae370e1) | Jun 10, 2019 |
| ASUSTek       | X450CC                      | Notebook    | [9604bdacb2](https://linux-hardware.org/?probe=9604bdacb2) | Jun 10, 2019 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [23bd541bf1](https://linux-hardware.org/?probe=23bd541bf1) | Jun 10, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [1eb4640c84](https://linux-hardware.org/?probe=1eb4640c84) | Jun 09, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [c4d7f7a2f4](https://linux-hardware.org/?probe=c4d7f7a2f4) | Jun 09, 2019 |
| Dell          | Inspiron 1420               | Notebook    | [09ca7997ac](https://linux-hardware.org/?probe=09ca7997ac) | Jun 09, 2019 |
| HP            | Pavilion tx1000             | Notebook    | [a783eb7140](https://linux-hardware.org/?probe=a783eb7140) | Jun 08, 2019 |
| HP            | Notebook                    | Notebook    | [c428093164](https://linux-hardware.org/?probe=c428093164) | Jun 06, 2019 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bf2a311ad2](https://linux-hardware.org/?probe=bf2a311ad2) | Jun 05, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [b828ffaace](https://linux-hardware.org/?probe=b828ffaace) | Jun 05, 2019 |
| HP            | ENVY 15                     | Notebook    | [f1ee36482d](https://linux-hardware.org/?probe=f1ee36482d) | Jun 03, 2019 |
| HP            | ENVY 15                     | Notebook    | [da05c24e64](https://linux-hardware.org/?probe=da05c24e64) | Jun 03, 2019 |
| HP            | ENVY 15                     | Notebook    | [b450947391](https://linux-hardware.org/?probe=b450947391) | Jun 03, 2019 |
| Acer          | Nitro AN515-52              | Notebook    | [30f1da590b](https://linux-hardware.org/?probe=30f1da590b) | Jun 03, 2019 |
| HP            | Pavilion x360 Convertibl... | Convertible | [92b2afa8f9](https://linux-hardware.org/?probe=92b2afa8f9) | Jun 03, 2019 |
| HP            | Pavilion x360 Convertibl... | Convertible | [57dfe20895](https://linux-hardware.org/?probe=57dfe20895) | Jun 03, 2019 |
| ASRock        | K8Upgrade-VM800             | Desktop     | [83cccbaf1a](https://linux-hardware.org/?probe=83cccbaf1a) | Jun 03, 2019 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e8f681bc78](https://linux-hardware.org/?probe=e8f681bc78) | Jun 03, 2019 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8174d512fa](https://linux-hardware.org/?probe=8174d512fa) | Jun 02, 2019 |
| ASRock        | G965M-S                     | Desktop     | [30b8a56200](https://linux-hardware.org/?probe=30b8a56200) | May 30, 2019 |
| HP            | 81BB                        | All in one  | [0f82f36e74](https://linux-hardware.org/?probe=0f82f36e74) | May 28, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [e11ecb2f55](https://linux-hardware.org/?probe=e11ecb2f55) | May 26, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [5b282c8861](https://linux-hardware.org/?probe=5b282c8861) | May 26, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [48cc73875b](https://linux-hardware.org/?probe=48cc73875b) | May 26, 2019 |
| Dell          | 0TT708 A01                  | Desktop     | [b732db0128](https://linux-hardware.org/?probe=b732db0128) | May 24, 2019 |
| Dell          | 0TT708 A01                  | Desktop     | [fbe3c00bb0](https://linux-hardware.org/?probe=fbe3c00bb0) | May 24, 2019 |
| ASUSTek       | X555LN                      | Notebook    | [2022ef16da](https://linux-hardware.org/?probe=2022ef16da) | May 23, 2019 |
| Lenovo        | ThinkPad X230 2325P35       | Notebook    | [d666ba7823](https://linux-hardware.org/?probe=d666ba7823) | May 22, 2019 |
| Unknown       | 775i65G                     | Desktop     | [0b6fd94458](https://linux-hardware.org/?probe=0b6fd94458) | May 19, 2019 |
| Unknown       | 775i65G                     | Desktop     | [2b8a659310](https://linux-hardware.org/?probe=2b8a659310) | May 18, 2019 |
| ASUSTek       | TP510UA                     | Convertible | [9565ccd6a2](https://linux-hardware.org/?probe=9565ccd6a2) | May 18, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [197946e655](https://linux-hardware.org/?probe=197946e655) | May 09, 2019 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [1700077449](https://linux-hardware.org/?probe=1700077449) | May 07, 2019 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [0a5569615d](https://linux-hardware.org/?probe=0a5569615d) | May 07, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [253b707c92](https://linux-hardware.org/?probe=253b707c92) | May 05, 2019 |
| Intel         | NUC7i7BNB J31145-311        | Mini pc     | [bda8f46ad6](https://linux-hardware.org/?probe=bda8f46ad6) | May 02, 2019 |
| Intel         | NUC7i7BNB J31145-311        | Mini pc     | [89b3484f48](https://linux-hardware.org/?probe=89b3484f48) | May 02, 2019 |
| Intel         | NUC7i7BNB J31145-311        | Mini pc     | [e608287029](https://linux-hardware.org/?probe=e608287029) | May 02, 2019 |
| Toshiba       | NB 105                      | Notebook    | [4662d43a44](https://linux-hardware.org/?probe=4662d43a44) | Apr 29, 2019 |
| Toshiba       | NB 105                      | Notebook    | [65ef86cd1c](https://linux-hardware.org/?probe=65ef86cd1c) | Apr 29, 2019 |
| ASUSTek       | X705UDR                     | Notebook    | [32a2339838](https://linux-hardware.org/?probe=32a2339838) | Apr 27, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [a6a1ecf366](https://linux-hardware.org/?probe=a6a1ecf366) | Apr 24, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b34ded162f](https://linux-hardware.org/?probe=b34ded162f) | Apr 22, 2019 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [29cf71291b](https://linux-hardware.org/?probe=29cf71291b) | Apr 21, 2019 |
| ASUSTek       | G73Jw                       | Notebook    | [2626377d36](https://linux-hardware.org/?probe=2626377d36) | Apr 20, 2019 |
| Apple         | MacBookAir6,2               | Notebook    | [a6dd71fdd3](https://linux-hardware.org/?probe=a6dd71fdd3) | Apr 19, 2019 |
| Biostar       | A55MLV                      | Desktop     | [38fd682351](https://linux-hardware.org/?probe=38fd682351) | Apr 19, 2019 |
| Lenovo        | ThinkPad T450 20BUS1S81F    | Notebook    | [c488c71bcd](https://linux-hardware.org/?probe=c488c71bcd) | Apr 17, 2019 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [93a44b1518](https://linux-hardware.org/?probe=93a44b1518) | Apr 17, 2019 |
| Lenovo        | ThinkPad T450 20BUS1S81F    | Notebook    | [f5fc1d9048](https://linux-hardware.org/?probe=f5fc1d9048) | Apr 17, 2019 |
| PCSMART       | AIRNOTE                     | Notebook    | [8ccaad6ff9](https://linux-hardware.org/?probe=8ccaad6ff9) | Apr 16, 2019 |
| PCSMART       | AIRNOTE                     | Notebook    | [fd6c64b14c](https://linux-hardware.org/?probe=fd6c64b14c) | Apr 16, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [b1b58b7d6b](https://linux-hardware.org/?probe=b1b58b7d6b) | Apr 16, 2019 |
| ASUSTek       | X505BP                      | Notebook    | [dcaf818df8](https://linux-hardware.org/?probe=dcaf818df8) | Apr 16, 2019 |
| Fujitsu       | LIFEBOOK T734               | Notebook    | [06582bdb98](https://linux-hardware.org/?probe=06582bdb98) | Apr 13, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [4eb3284db6](https://linux-hardware.org/?probe=4eb3284db6) | Apr 13, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [73f15e5986](https://linux-hardware.org/?probe=73f15e5986) | Apr 12, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [aea3995ddd](https://linux-hardware.org/?probe=aea3995ddd) | Apr 11, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [6245ed2348](https://linux-hardware.org/?probe=6245ed2348) | Apr 11, 2019 |
| HP            | 0A60h                       | Desktop     | [c59eb70baf](https://linux-hardware.org/?probe=c59eb70baf) | Apr 11, 2019 |
| HP            | 0A60h                       | Desktop     | [bd74dccea9](https://linux-hardware.org/?probe=bd74dccea9) | Apr 10, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [c5178f5550](https://linux-hardware.org/?probe=c5178f5550) | Apr 04, 2019 |
| ASUSTek       | N56JRH                      | Notebook    | [5764250d85](https://linux-hardware.org/?probe=5764250d85) | Apr 03, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [ef3d04377e](https://linux-hardware.org/?probe=ef3d04377e) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [be751979a7](https://linux-hardware.org/?probe=be751979a7) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [b9c1d97ec1](https://linux-hardware.org/?probe=b9c1d97ec1) | Apr 01, 2019 |
| Biostar       | A55MLV                      | Desktop     | [138e3baa2d](https://linux-hardware.org/?probe=138e3baa2d) | Mar 29, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [d3f5c5ac28](https://linux-hardware.org/?probe=d3f5c5ac28) | Mar 29, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [53fb4de336](https://linux-hardware.org/?probe=53fb4de336) | Mar 27, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [9a4cbb7444](https://linux-hardware.org/?probe=9a4cbb7444) | Mar 27, 2019 |
| ASUSTek       | TAICHI21                    | Notebook    | [ceedb83caa](https://linux-hardware.org/?probe=ceedb83caa) | Mar 25, 2019 |
| HP            | 14                          | Notebook    | [3532a15338](https://linux-hardware.org/?probe=3532a15338) | Mar 19, 2019 |
| Intel         | DH61CR AAG14064-207         | Desktop     | [2c44dea441](https://linux-hardware.org/?probe=2c44dea441) | Mar 17, 2019 |
| Sony          | SVE14A27CXH                 | Notebook    | [f8e75b8eca](https://linux-hardware.org/?probe=f8e75b8eca) | Mar 17, 2019 |
| Acer          | Aspire E3-111               | Notebook    | [e11f7a05d2](https://linux-hardware.org/?probe=e11f7a05d2) | Mar 14, 2019 |
| ASUSTek       | TAICHI21                    | Notebook    | [a90d891180](https://linux-hardware.org/?probe=a90d891180) | Mar 07, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [4fb49f65ef](https://linux-hardware.org/?probe=4fb49f65ef) | Feb 28, 2019 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [8d9fa49be1](https://linux-hardware.org/?probe=8d9fa49be1) | Feb 09, 2019 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5dcbf55671](https://linux-hardware.org/?probe=5dcbf55671) | Feb 09, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [e1e477a44d](https://linux-hardware.org/?probe=e1e477a44d) | Jan 24, 2019 |
| Dell          | Inspiron 5423               | Notebook    | [0ae4be99f8](https://linux-hardware.org/?probe=0ae4be99f8) | Jan 23, 2019 |
| Dell          | Inspiron 5423               | Notebook    | [0f80a72955](https://linux-hardware.org/?probe=0f80a72955) | Jan 23, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2ec93c29be](https://linux-hardware.org/?probe=2ec93c29be) | Jan 08, 2019 |
| HP            | 245 G6                      | Notebook    | [feeb8ea6f8](https://linux-hardware.org/?probe=feeb8ea6f8) | Jan 03, 2019 |
| ASUSTek       | X505BP                      | Notebook    | [7f4192344e](https://linux-hardware.org/?probe=7f4192344e) | Dec 29, 2018 |
| ASUSTek       | X505BP                      | Notebook    | [0999f0abc7](https://linux-hardware.org/?probe=0999f0abc7) | Dec 29, 2018 |
| HP            | 245 G6                      | Notebook    | [4289ff0916](https://linux-hardware.org/?probe=4289ff0916) | Dec 28, 2018 |
| HP            | 14                          | Notebook    | [0fe4f88e5a](https://linux-hardware.org/?probe=0fe4f88e5a) | Dec 19, 2018 |
| Acer          | Aspire ES1-572              | Notebook    | [d6d801ec2b](https://linux-hardware.org/?probe=d6d801ec2b) | Dec 19, 2018 |
| Acer          | Aspire ES1-572              | Notebook    | [002ca9c182](https://linux-hardware.org/?probe=002ca9c182) | Dec 19, 2018 |
| ASUSTek       | X505BP                      | Notebook    | [1388526b7f](https://linux-hardware.org/?probe=1388526b7f) | Dec 17, 2018 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [57ba3702e3](https://linux-hardware.org/?probe=57ba3702e3) | Dec 11, 2018 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [f67c3262d4](https://linux-hardware.org/?probe=f67c3262d4) | Dec 10, 2018 |
| Dell          | Latitude D620               | Notebook    | [81774e2415](https://linux-hardware.org/?probe=81774e2415) | Dec 07, 2018 |
| Acer          | Unknown                     | Notebook    | [02419cd635](https://linux-hardware.org/?probe=02419cd635) | Dec 03, 2018 |
| Samsung       | N148P                       | Notebook    | [629403b78b](https://linux-hardware.org/?probe=629403b78b) | Nov 25, 2018 |
| Acer          | Unknown                     | Notebook    | [e25ca67959](https://linux-hardware.org/?probe=e25ca67959) | Nov 20, 2018 |
| Acer          | Unknown                     | Notebook    | [f5a1c21578](https://linux-hardware.org/?probe=f5a1c21578) | Nov 18, 2018 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [06bcad286b](https://linux-hardware.org/?probe=06bcad286b) | Nov 18, 2018 |
| HP            | 2B13 A01                    | All in one  | [8553f899d5](https://linux-hardware.org/?probe=8553f899d5) | Nov 14, 2018 |
| HP            | 2B13 A01                    | All in one  | [80acd57528](https://linux-hardware.org/?probe=80acd57528) | Nov 14, 2018 |
| HP            | 1000                        | Notebook    | [e8425d849b](https://linux-hardware.org/?probe=e8425d849b) | Nov 10, 2018 |
| Toshiba       | Satellite C675D             | Notebook    | [aa4071d1df](https://linux-hardware.org/?probe=aa4071d1df) | Nov 05, 2018 |
| ASUSTek       | X542URR                     | Notebook    | [a5e2816233](https://linux-hardware.org/?probe=a5e2816233) | Nov 03, 2018 |
| ASUSTek       | X542URR                     | Notebook    | [2a42f7d935](https://linux-hardware.org/?probe=2a42f7d935) | Nov 03, 2018 |
| Acer          | Aspire 4736Z                | Notebook    | [0d5e0790a7](https://linux-hardware.org/?probe=0d5e0790a7) | Oct 30, 2018 |
| Acer          | Aspire 4736Z                | Notebook    | [17113b9ae5](https://linux-hardware.org/?probe=17113b9ae5) | Oct 30, 2018 |
| ASUSTek       | X505BP                      | Notebook    | [09546ff0fe](https://linux-hardware.org/?probe=09546ff0fe) | Oct 29, 2018 |
| ASUSTek       | X505BP                      | Notebook    | [24dffba93d](https://linux-hardware.org/?probe=24dffba93d) | Oct 29, 2018 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [890de967ad](https://linux-hardware.org/?probe=890de967ad) | Oct 26, 2018 |
| HP            | Pavilion 14                 | Notebook    | [a708531868](https://linux-hardware.org/?probe=a708531868) | Oct 25, 2018 |
| HP            | Pavilion 14                 | Notebook    | [dcd47dff54](https://linux-hardware.org/?probe=dcd47dff54) | Oct 25, 2018 |
| Toshiba       | Satellite C655              | Notebook    | [b158836f6e](https://linux-hardware.org/?probe=b158836f6e) | Oct 23, 2018 |
| Toshiba       | Satellite C655              | Notebook    | [347c50681c](https://linux-hardware.org/?probe=347c50681c) | Oct 23, 2018 |
| ASUSTek       | X455LD                      | Notebook    | [6224197a75](https://linux-hardware.org/?probe=6224197a75) | Oct 12, 2018 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [9f2347db71](https://linux-hardware.org/?probe=9f2347db71) | Oct 09, 2018 |
| Pegatron      | 2A73h                       | Desktop     | [9ab888ea4f](https://linux-hardware.org/?probe=9ab888ea4f) | Jun 19, 2018 |
| ASUSTek       | G550JK                      | Notebook    | [af5510f93b](https://linux-hardware.org/?probe=af5510f93b) | Jun 19, 2018 |
| HP            | 14                          | Notebook    | [13f12e2f48](https://linux-hardware.org/?probe=13f12e2f48) | May 23, 2018 |
| HP            | Compaq Presario CQ45        | Notebook    | [762d293955](https://linux-hardware.org/?probe=762d293955) | May 12, 2018 |
| Acer          | Aspire 4739                 | Notebook    | [31eeafc656](https://linux-hardware.org/?probe=31eeafc656) | Jan 04, 2018 |
| Lenovo        | G40-80 80E4                 | Notebook    | [1855d90774](https://linux-hardware.org/?probe=1855d90774) | Dec 19, 2017 |
| HP            | 2ADE                        | Desktop     | [af28bb9a2f](https://linux-hardware.org/?probe=af28bb9a2f) | Dec 01, 2017 |
| HP            | 2ADE                        | Desktop     | [a2ab5f4392](https://linux-hardware.org/?probe=a2ab5f4392) | Dec 01, 2017 |
| Acer          | Aspire 4739                 | Notebook    | [dc6c363798](https://linux-hardware.org/?probe=dc6c363798) | Oct 02, 2017 |
| HP            | Compaq Presario CQ45        | Notebook    | [5c6365ef1a](https://linux-hardware.org/?probe=5c6365ef1a) | Jul 21, 2017 |
| HP            | 0A54h                       | Desktop     | [1f795e5896](https://linux-hardware.org/?probe=1f795e5896) | Jun 29, 2017 |
| HP            | Compaq Presario CQ45        | Notebook    | [909a456d4f](https://linux-hardware.org/?probe=909a456d4f) | Apr 21, 2017 |
| HP            | Compaq Presario CQ45        | Notebook    | [6571151136](https://linux-hardware.org/?probe=6571151136) | Apr 21, 2017 |
| HP            | Compaq Presario CQ45        | Notebook    | [dc632cca26](https://linux-hardware.org/?probe=dc632cca26) | Mar 18, 2017 |
| HP            | 0A54h                       | Desktop     | [ef67a7d651](https://linux-hardware.org/?probe=ef67a7d651) | Feb 05, 2017 |
| HP            | Compaq Presario CQ45        | Notebook    | [c8bbfe9037](https://linux-hardware.org/?probe=c8bbfe9037) | Jan 04, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 113       | 15.01%  |
| Ubuntu 18.04                 | 101       | 13.41%  |
| OpenMandriva 4.3             | 25        | 3.32%   |
| Zorin 15                     | 16        | 2.12%   |
| KDE neon 20.04               | 16        | 2.12%   |
| Ubuntu 19.04                 | 15        | 1.99%   |
| OpenMandriva 4.2             | 15        | 1.99%   |
| Linux Mint 19.3              | 13        | 1.73%   |
| Ubuntu 16.04                 | 12        | 1.59%   |
| Linux Mint 20.2              | 12        | 1.59%   |
| Arch                         | 12        | 1.59%   |
| Arch Rolling                 | 11        | 1.46%   |
| Ubuntu 19.10                 | 10        | 1.33%   |
| Linux Mint 20.1              | 10        | 1.33%   |
| Fedora 34                    | 10        | 1.33%   |
| Debian 11                    | 10        | 1.33%   |
| ROSA R10                     | 9         | 1.2%    |
| Kubuntu 20.04                | 9         | 1.2%    |
| Fedora 35                    | 9         | 1.2%    |
| Zorin 16                     | 8         | 1.06%   |
| Ubuntu 20.10                 | 8         | 1.06%   |
| Manjaro                      | 8         | 1.06%   |
| Linux Mint 20.3              | 8         | 1.06%   |
| Fedora 33                    | 8         | 1.06%   |
| Debian 10                    | 8         | 1.06%   |
| Xubuntu 20.04                | 7         | 0.93%   |
| Pop!_OS 20.04                | 7         | 0.93%   |
| Linux Mint 20                | 7         | 0.93%   |
| Fedora 32                    | 7         | 0.93%   |
| ArcoLinux Rolling            | 7         | 0.93%   |
| Ubuntu 22.04                 | 6         | 0.8%    |
| Ubuntu 21.04                 | 6         | 0.8%    |
| Ubuntu 21.10                 | 5         | 0.66%   |
| Ubuntu 18.10                 | 5         | 0.66%   |
| ROSA R11                     | 5         | 0.66%   |
| Fedora 31                    | 5         | 0.66%   |
| Endless 3.8.3                | 5         | 0.66%   |
| Pop!_OS 21.10                | 4         | 0.53%   |
| Linux Mint 19.2              | 4         | 0.53%   |
| Linux Mint 19.1              | 4         | 0.53%   |
| Fedora 36                    | 4         | 0.53%   |
| Endless 3.9.5                | 4         | 0.53%   |
| Endless 3.6.0                | 4         | 0.53%   |
| Zorin 12                     | 3         | 0.4%    |
| Xubuntu 18.04                | 3         | 0.4%    |
| Ubuntu Budgie 20.04          | 3         | 0.4%    |
| ROSA R9                      | 3         | 0.4%    |
| ROSA R11.1                   | 3         | 0.4%    |
| ROSA 12.2                    | 3         | 0.4%    |
| Pop!_OS 21.04                | 3         | 0.4%    |
| Pop!_OS 20.10                | 3         | 0.4%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.4%    |
| KDE neon 18.04               | 3         | 0.4%    |
| Kali 2022.1                  | 3         | 0.4%    |
| Endless 3.9.4                | 3         | 0.4%    |
| Endless 3.9.1                | 3         | 0.4%    |
| Endless 3.9.0                | 3         | 0.4%    |
| Endless 3.8.6                | 3         | 0.4%    |
| Endless 3.8.4                | 3         | 0.4%    |
| Endless 3.8.1                | 3         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 272       | 38.04%  |
| Endless       | 63        | 8.81%   |
| Linux Mint    | 58        | 8.11%   |
| OpenMandriva  | 42        | 5.87%   |
| Fedora        | 38        | 5.31%   |
| Zorin         | 27        | 3.78%   |
| Manjaro       | 24        | 3.36%   |
| Arch          | 23        | 3.22%   |
| ROSA          | 21        | 2.94%   |
| Debian        | 21        | 2.94%   |
| Pop!_OS       | 19        | 2.66%   |
| KDE neon      | 18        | 2.52%   |
| Kubuntu       | 13        | 1.82%   |
| Xubuntu       | 12        | 1.68%   |
| Kali          | 8         | 1.12%   |
| ArcoLinux     | 8         | 1.12%   |
| Elementary    | 7         | 0.98%   |
| Lubuntu       | 6         | 0.84%   |
| openSUSE      | 5         | 0.7%    |
| Ubuntu Budgie | 3         | 0.42%   |
| Deepin        | 3         | 0.42%   |
| MX            | 2         | 0.28%   |
| Garuda Linux  | 2         | 0.28%   |
| EndeavourOS   | 2         | 0.28%   |
| Clear Linux   | 2         | 0.28%   |
| CentOS        | 2         | 0.28%   |
| BlackPanther  | 2         | 0.28%   |
| Xero          | 1         | 0.14%   |
| UbuntuDDE     | 1         | 0.14%   |
| Rocky Linux   | 1         | 0.14%   |
| RHEL          | 1         | 0.14%   |
| Reborn OS     | 1         | 0.14%   |
| Parrot        | 1         | 0.14%   |
| NixOS         | 1         | 0.14%   |
| Mageia        | 1         | 0.14%   |
| LMDE          | 1         | 0.14%   |
| LinuxFX       | 1         | 0.14%   |
| Linux Lite    | 1         | 0.14%   |
| Liberty OS    | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 28        | 3.5%    |
| 5.16.7-desktop-1omv4003         | 25        | 3.13%   |
| 5.8.0-14-generic                | 16        | 2%      |
| 5.10.14-desktop-1omv4002        | 15        | 1.88%   |
| 5.4.0-58-generic                | 14        | 1.75%   |
| 5.4.0-19-generic                | 12        | 1.5%    |
| 5.3.0-46-generic                | 9         | 1.13%   |
| 4.18.0-15-generic               | 9         | 1.13%   |
| 5.4.0-48-generic                | 8         | 1%      |
| 4.18.0-25-generic               | 8         | 1%      |
| 5.8.0-43-generic                | 7         | 0.88%   |
| 5.4.0-37-generic                | 7         | 0.88%   |
| 5.4.0-31-generic                | 7         | 0.88%   |
| 5.3.0-28-generic                | 7         | 0.88%   |
| 5.0.0-37-generic                | 7         | 0.88%   |
| 5.13.0-40-generic               | 6         | 0.75%   |
| 5.13.0-30-generic               | 6         | 0.75%   |
| 5.11.0-34-generic               | 6         | 0.75%   |
| 5.0.0-32-generic                | 6         | 0.75%   |
| 5.0.0-25-generic                | 6         | 0.75%   |
| 5.0.0-15-generic                | 6         | 0.75%   |
| 5.4.0-72-generic                | 5         | 0.63%   |
| 5.4.0-70-generic                | 5         | 0.63%   |
| 5.4.0-65-generic                | 5         | 0.63%   |
| 5.4.0-54-generic                | 5         | 0.63%   |
| 5.4.0-47-generic                | 5         | 0.63%   |
| 5.4.0-107-generic               | 5         | 0.63%   |
| 5.3.0-40-generic                | 5         | 0.63%   |
| 5.11.0-40-generic               | 5         | 0.63%   |
| 5.11.0-27-generic               | 5         | 0.63%   |
| 5.0.0-23-generic                | 5         | 0.63%   |
| 5.0.0-13-generic                | 5         | 0.63%   |
| 4.15.0-47-generic               | 5         | 0.63%   |
| 5.8.0-59-generic                | 4         | 0.5%    |
| 5.8.0-48-generic                | 4         | 0.5%    |
| 5.8.0-44-generic                | 4         | 0.5%    |
| 5.4.0-64-generic                | 4         | 0.5%    |
| 5.4.0-52-generic                | 4         | 0.5%    |
| 5.4.0-40-generic                | 4         | 0.5%    |
| 5.4.0-26-generic                | 4         | 0.5%    |
| 5.3.0-51-generic                | 4         | 0.5%    |
| 5.3.0-42-generic                | 4         | 0.5%    |
| 5.13.0-7620-generic             | 4         | 0.5%    |
| 5.13.0-37-generic               | 4         | 0.5%    |
| 5.13.0-27-generic               | 4         | 0.5%    |
| 5.11.0-38-generic               | 4         | 0.5%    |
| 5.11.0-25-generic               | 4         | 0.5%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 4         | 0.5%    |
| 4.18.0-21-generic               | 4         | 0.5%    |
| 4.18.0-16-generic               | 4         | 0.5%    |
| 4.15.0-54-generic               | 4         | 0.5%    |
| 5.4.0-97-generic                | 3         | 0.38%   |
| 5.4.0-89-generic                | 3         | 0.38%   |
| 5.4.0-88-generic                | 3         | 0.38%   |
| 5.4.0-84-generic                | 3         | 0.38%   |
| 5.4.0-81-generic                | 3         | 0.38%   |
| 5.4.0-59-generic                | 3         | 0.38%   |
| 5.4.0-45-generic                | 3         | 0.38%   |
| 5.4.0-39-generic                | 3         | 0.38%   |
| 5.4.0-33-generic                | 3         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 175       | 22.79%  |
| 4.15.0  | 61        | 7.94%   |
| 5.8.0   | 53        | 6.9%    |
| 5.3.0   | 51        | 6.64%   |
| 5.0.0   | 48        | 6.25%   |
| 4.18.0  | 40        | 5.21%   |
| 5.13.0  | 38        | 4.95%   |
| 5.11.0  | 33        | 4.3%    |
| 5.16.7  | 25        | 3.26%   |
| 5.10.14 | 15        | 1.95%   |
| 5.10.0  | 10        | 1.3%    |
| 5.15.0  | 9         | 1.17%   |
| 4.19.0  | 7         | 0.91%   |
| 4.9.60  | 5         | 0.65%   |
| 4.4.0   | 5         | 0.65%   |
| 5.8.5   | 4         | 0.52%   |
| 5.8.18  | 4         | 0.52%   |
| 4.13.0  | 4         | 0.52%   |
| 5.9.16  | 3         | 0.39%   |
| 5.6.0   | 3         | 0.39%   |
| 5.15.12 | 3         | 0.39%   |
| 5.14.0  | 3         | 0.39%   |
| 5.13.19 | 3         | 0.39%   |
| 5.12.4  | 3         | 0.39%   |
| 5.10.74 | 3         | 0.39%   |
| 5.1.0   | 3         | 0.39%   |
| 4.9.20  | 3         | 0.39%   |
| 4.9.0   | 3         | 0.39%   |
| 5.9.1   | 2         | 0.26%   |
| 5.7.19  | 2         | 0.26%   |
| 5.6.19  | 2         | 0.26%   |
| 5.6.15  | 2         | 0.26%   |
| 5.4.32  | 2         | 0.26%   |
| 5.3.12  | 2         | 0.26%   |
| 5.17.5  | 2         | 0.26%   |
| 5.17.3  | 2         | 0.26%   |
| 5.16.15 | 2         | 0.26%   |
| 5.16.0  | 2         | 0.26%   |
| 5.15.7  | 2         | 0.26%   |
| 5.15.28 | 2         | 0.26%   |
| 5.15.15 | 2         | 0.26%   |
| 5.14.10 | 2         | 0.26%   |
| 5.14.1  | 2         | 0.26%   |
| 5.13.5  | 2         | 0.26%   |
| 5.13.4  | 2         | 0.26%   |
| 5.11.11 | 2         | 0.26%   |
| 5.10.18 | 2         | 0.26%   |
| 4.9.95  | 2         | 0.26%   |
| 4.9.124 | 2         | 0.26%   |
| 4.18.16 | 2         | 0.26%   |
| 4.12.14 | 2         | 0.26%   |
| 4.10.0  | 2         | 0.26%   |
| 4.1.34  | 2         | 0.26%   |
| 5.9.6   | 1         | 0.13%   |
| 5.9.3   | 1         | 0.13%   |
| 5.9.14  | 1         | 0.13%   |
| 5.9.11  | 1         | 0.13%   |
| 5.9.10  | 1         | 0.13%   |
| 5.9.0   | 1         | 0.13%   |
| 5.8.7   | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 183       | 24.08%  |
| 5.8     | 64        | 8.42%   |
| 4.15    | 61        | 8.03%   |
| 5.3     | 56        | 7.37%   |
| 5.13    | 49        | 6.45%   |
| 5.0     | 49        | 6.45%   |
| 5.10    | 45        | 5.92%   |
| 4.18    | 43        | 5.66%   |
| 5.11    | 39        | 5.13%   |
| 5.16    | 31        | 4.08%   |
| 5.15    | 22        | 2.89%   |
| 4.9     | 17        | 2.24%   |
| 5.6     | 15        | 1.97%   |
| 5.14    | 12        | 1.58%   |
| 5.9     | 10        | 1.32%   |
| 5.17    | 10        | 1.32%   |
| 5.12    | 9         | 1.18%   |
| 5.7     | 8         | 1.05%   |
| 4.19    | 8         | 1.05%   |
| 4.4     | 5         | 0.66%   |
| 5.5     | 4         | 0.53%   |
| 4.13    | 4         | 0.53%   |
| 5.1     | 3         | 0.39%   |
| 4.12    | 3         | 0.39%   |
| 5.2     | 2         | 0.26%   |
| 5.18    | 2         | 0.26%   |
| 4.10    | 2         | 0.26%   |
| 4.1     | 2         | 0.26%   |
| 4.20    | 1         | 0.13%   |
| 4.14    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 679       | 96.86%  |
| i686    | 19        | 2.71%   |
| aarch64 | 3         | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 326       | 45.21%  |
| Unknown    | 130       | 18.03%  |
| KDE5       | 91        | 12.62%  |
| XFCE       | 49        | 6.8%    |
| X-Cinnamon | 34        | 4.72%   |
| KDE        | 26        | 3.61%   |
| KDE4       | 12        | 1.66%   |
| MATE       | 8         | 1.11%   |
| Unity      | 7         | 0.97%   |
| Pantheon   | 7         | 0.97%   |
| Cinnamon   | 7         | 0.97%   |
| Deepin     | 5         | 0.69%   |
| Budgie     | 5         | 0.69%   |
| LXQt       | 4         | 0.55%   |
| LXDE       | 3         | 0.42%   |
| i3         | 2         | 0.28%   |
| bspwm      | 2         | 0.28%   |
| awesome    | 2         | 0.28%   |
| ICEWM      | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 569       | 79.58%  |
| Unknown | 85        | 11.89%  |
| Wayland | 53        | 7.41%   |
| Tty     | 8         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 452       | 62.87%  |
| SDDM    | 78        | 10.85%  |
| GDM     | 76        | 10.57%  |
| LightDM | 48        | 6.68%   |
| GDM3    | 30        | 4.17%   |
| TDM     | 21        | 2.92%   |
| KDM     | 12        | 1.67%   |
| SLiM    | 1         | 0.14%   |
| LXDM    | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_CO   | 333       | 46.06%  |
| en_US   | 167       | 23.1%   |
| Unknown | 145       | 20.06%  |
| es_ES   | 43        | 5.95%   |
| es_MX   | 12        | 1.66%   |
| en_GB   | 4         | 0.55%   |
| es_PE   | 3         | 0.41%   |
| C       | 3         | 0.41%   |
| pt_BR   | 2         | 0.28%   |
| es_EC   | 2         | 0.28%   |
| pt_PT   | 1         | 0.14%   |
| pl_PL   | 1         | 0.14%   |
| it_IT   | 1         | 0.14%   |
| fr_FR   | 1         | 0.14%   |
| es_VE   | 1         | 0.14%   |
| es_CL   | 1         | 0.14%   |
| es_AR   | 1         | 0.14%   |
| en      | 1         | 0.14%   |
| de_DE   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 358       | 50.28%  |
| BIOS | 354       | 49.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 575       | 80.2%   |
| Unknown | 47        | 6.56%   |
| Overlay | 45        | 6.28%   |
| Btrfs   | 32        | 4.46%   |
| Xfs     | 11        | 1.53%   |
| Tmpfs   | 2         | 0.28%   |
| Ext2    | 2         | 0.28%   |
| Zfs     | 1         | 0.14%   |
| F2fs    | 1         | 0.14%   |
| Ext3    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 482       | 68.18%  |
| GPT     | 156       | 22.07%  |
| MBR     | 69        | 9.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 623       | 86.89%  |
| Yes       | 94        | 13.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 458       | 64.6%   |
| Yes       | 251       | 35.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUSTek Computer             | 159       | 22.68%  |
| Hewlett-Packard              | 135       | 19.26%  |
| Lenovo                       | 98        | 13.98%  |
| Dell                         | 57        | 8.13%   |
| Acer                         | 44        | 6.28%   |
| MSI                          | 32        | 4.56%   |
| Gigabyte Technology          | 30        | 4.28%   |
| ASRock                       | 24        | 3.42%   |
| Toshiba                      | 19        | 2.71%   |
| Apple                        | 14        | 2%      |
| Samsung Electronics          | 12        | 1.71%   |
| Intel                        | 12        | 1.71%   |
| Sony                         | 9         | 1.28%   |
| Unknown                      | 8         | 1.14%   |
| ECS                          | 5         | 0.71%   |
| Pegatron                     | 4         | 0.57%   |
| HUAWEI                       | 4         | 0.57%   |
| Foxconn                      | 4         | 0.57%   |
| Biostar                      | 4         | 0.57%   |
| PCSMART                      | 3         | 0.43%   |
| Supermicro                   | 2         | 0.29%   |
| Raspberry Pi Foundation      | 2         | 0.29%   |
| Notebook                     | 2         | 0.29%   |
| Gateway                      | 2         | 0.29%   |
| VIT                          | 1         | 0.14%   |
| TYAN Computer                | 1         | 0.14%   |
| Timi                         | 1         | 0.14%   |
| PCChips                      | 1         | 0.14%   |
| ONDA                         | 1         | 0.14%   |
| Nvidia                       | 1         | 0.14%   |
| MPS Mayorista de Colombia SA | 1         | 0.14%   |
| Inspur                       | 1         | 0.14%   |
| Hardkernel                   | 1         | 0.14%   |
| GreatWall                    | 1         | 0.14%   |
| Google                       | 1         | 0.14%   |
| Fujitsu Siemens              | 1         | 0.14%   |
| Fujitsu                      | 1         | 0.14%   |
| Framework                    | 1         | 0.14%   |
| Chuwi                        | 1         | 0.14%   |
| BAKED                        | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-db0xxx                        | 11        | 1.57%   |
| Unknown                                    | 10        | 1.43%   |
| Samsung 300E4C/300E5C/300E7C               | 5         | 0.71%   |
| HP Laptop 14-bs0xx                         | 5         | 0.71%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA    | 5         | 0.71%   |
| MSI MS-7309                                | 4         | 0.57%   |
| HP Notebook                                | 4         | 0.57%   |
| HP Laptop 14-cm1xxx                        | 4         | 0.57%   |
| HP 14                                      | 4         | 0.57%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.57%   |
| ASUS All Series                            | 4         | 0.57%   |
| MSI MS-7817                                | 3         | 0.43%   |
| Lenovo IdeaPad S340-14API 81NB             | 3         | 0.43%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 3         | 0.43%   |
| Lenovo G40-80 80E4                         | 3         | 0.43%   |
| Lenovo G40-45 80E1                         | 3         | 0.43%   |
| HP ProBook 450 G1                          | 3         | 0.43%   |
| HP Pavilion x360 Convertible 14-cd0xxx     | 3         | 0.43%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 3         | 0.43%   |
| HP Laptop 15-da0xxx                        | 3         | 0.43%   |
| HP 245 G6                                  | 3         | 0.43%   |
| Gigabyte H81M-H                            | 3         | 0.43%   |
| Gigabyte G31M-ES2C                         | 3         | 0.43%   |
| Gigabyte B450M DS3H                        | 3         | 0.43%   |
| ECS G31T-M7                                | 3         | 0.43%   |
| Dell XPS 15 9550                           | 3         | 0.43%   |
| Dell Vostro 3400                           | 3         | 0.43%   |
| ASUS X555QG                                | 3         | 0.43%   |
| ASUS X505BP                                | 3         | 0.43%   |
| ASUS X455LJ                                | 3         | 0.43%   |
| ASUS VivoBook_ASUSLaptop X512FB_X512FB     | 3         | 0.43%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA     | 3         | 0.43%   |
| ASUS VivoBook_ASUSLaptop X409DA_M409DA     | 3         | 0.43%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 3         | 0.43%   |
| ASUS T101HA                                | 3         | 0.43%   |
| ASUS M5A78L-M/USB3                         | 3         | 0.43%   |
| ASRock Wolfdale1333-D667                   | 3         | 0.43%   |
| ASRock G41M-VS3                            | 3         | 0.43%   |
| Acer Aspire E5-575G                        | 3         | 0.43%   |
| Acer Aspire A515-51                        | 3         | 0.43%   |
| Acer Aspire 4750                           | 3         | 0.43%   |
| Toshiba Satellite U505                     | 2         | 0.29%   |
| Toshiba NB 105                             | 2         | 0.29%   |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.29%   |
| Lenovo V330-14IKB 81B0                     | 2         | 0.29%   |
| Lenovo ThinkPad X13 Gen 1 20UGS2B800       | 2         | 0.29%   |
| Lenovo ThinkBook 13s G2 ITL 20V9           | 2         | 0.29%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 2         | 0.29%   |
| Lenovo IdeaPad 110-14IBR 80T6              | 2         | 0.29%   |
| Intel H61                                  | 2         | 0.29%   |
| HP ProBook 440 G7                          | 2         | 0.29%   |
| HP ProBook 440 G3                          | 2         | 0.29%   |
| HP ProBook 440 G2                          | 2         | 0.29%   |
| HP Presario CQ43                           | 2         | 0.29%   |
| HP Pavilion x360 Convertible 14-ba0xx      | 2         | 0.29%   |
| HP Pavilion Laptop 15-cw0xxx               | 2         | 0.29%   |
| HP Pavilion g4                             | 2         | 0.29%   |
| HP Pavilion dv4                            | 2         | 0.29%   |
| HP Pavilion 10 TS                          | 2         | 0.29%   |
| HP Laptop 14-ck0xxx                        | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS VivoBook            | 47        | 6.7%    |
| Lenovo IdeaPad           | 32        | 4.56%   |
| Acer Aspire              | 31        | 4.42%   |
| Lenovo ThinkPad          | 30        | 4.28%   |
| HP Laptop                | 30        | 4.28%   |
| HP Pavilion              | 26        | 3.71%   |
| Dell Inspiron            | 19        | 2.71%   |
| Toshiba Satellite        | 16        | 2.28%   |
| HP ProBook               | 16        | 2.28%   |
| HP Compaq                | 13        | 1.85%   |
| ASUS PRIME               | 13        | 1.85%   |
| Dell Latitude            | 10        | 1.43%   |
| Unknown                  | 10        | 1.43%   |
| Dell Vostro              | 8         | 1.14%   |
| ASUS ROG                 | 8         | 1.14%   |
| Dell OptiPlex            | 7         | 1%      |
| ASUS ZenBook             | 6         | 0.86%   |
| Samsung 300E4C           | 5         | 0.71%   |
| HP 245                   | 5         | 0.71%   |
| Dell XPS                 | 5         | 0.71%   |
| ASUS TUF                 | 5         | 0.71%   |
| MSI MS-7309              | 4         | 0.57%   |
| Lenovo Yoga              | 4         | 0.57%   |
| HP Notebook              | 4         | 0.57%   |
| HP ENVY                  | 4         | 0.57%   |
| HP EliteBook             | 4         | 0.57%   |
| HP 14                    | 4         | 0.57%   |
| ASUS All                 | 4         | 0.57%   |
| MSI MS-7817              | 3         | 0.43%   |
| Lenovo G40-80            | 3         | 0.43%   |
| Lenovo G40-45            | 3         | 0.43%   |
| HP ProLiant              | 3         | 0.43%   |
| HP Presario              | 3         | 0.43%   |
| HP All-in-One            | 3         | 0.43%   |
| HP 240                   | 3         | 0.43%   |
| Gigabyte X399            | 3         | 0.43%   |
| Gigabyte H81M-H          | 3         | 0.43%   |
| Gigabyte G31M-ES2C       | 3         | 0.43%   |
| Gigabyte B450M           | 3         | 0.43%   |
| ECS G31T-M7              | 3         | 0.43%   |
| ASUS X555QG              | 3         | 0.43%   |
| ASUS X505BP              | 3         | 0.43%   |
| ASUS X455LJ              | 3         | 0.43%   |
| ASUS T101HA              | 3         | 0.43%   |
| ASUS M5A78L-M            | 3         | 0.43%   |
| ASRock Wolfdale1333-D667 | 3         | 0.43%   |
| ASRock G41M-VS3          | 3         | 0.43%   |
| Acer TravelMate          | 3         | 0.43%   |
| Acer Nitro               | 3         | 0.43%   |
| Toshiba NB               | 2         | 0.29%   |
| RPi Raspberry            | 2         | 0.29%   |
| MSI PS63                 | 2         | 0.29%   |
| MSI GE60                 | 2         | 0.29%   |
| Lenovo Y520-15IKBN       | 2         | 0.29%   |
| Lenovo V330-14IKB        | 2         | 0.29%   |
| Lenovo ThinkCentre       | 2         | 0.29%   |
| Lenovo ThinkBook         | 2         | 0.29%   |
| Lenovo Legion            | 2         | 0.29%   |
| Lenovo IdeaCentre        | 2         | 0.29%   |
| Intel H61                | 2         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 79        | 11.27%  |
| 2019    | 74        | 10.56%  |
| 2017    | 71        | 10.13%  |
| 2012    | 54        | 7.7%    |
| 2011    | 51        | 7.28%   |
| 2010    | 50        | 7.13%   |
| 2020    | 46        | 6.56%   |
| 2015    | 45        | 6.42%   |
| 2013    | 44        | 6.28%   |
| 2014    | 41        | 5.85%   |
| 2009    | 32        | 4.56%   |
| 2016    | 29        | 4.14%   |
| 2021    | 24        | 3.42%   |
| 2008    | 23        | 3.28%   |
| 2007    | 20        | 2.85%   |
| 2006    | 9         | 1.28%   |
| 2022    | 3         | 0.43%   |
| Unknown | 3         | 0.43%   |
| 2005    | 2         | 0.29%   |
| 2003    | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 476       | 67.9%   |
| Desktop        | 180       | 25.68%  |
| All in one     | 19        | 2.71%   |
| Convertible    | 13        | 1.85%   |
| Tablet         | 6         | 0.86%   |
| System on chip | 3         | 0.43%   |
| Server         | 3         | 0.43%   |
| Mini pc        | 1         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 634       | 89.93%  |
| Enabled  | 71        | 10.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 700       | 99.86%  |
| Yes  | 1         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 214       | 30.27%  |
| 3.01-4.0    | 192       | 27.16%  |
| 8.01-16.0   | 121       | 17.11%  |
| 16.01-24.0  | 75        | 10.61%  |
| 1.01-2.0    | 44        | 6.22%   |
| 32.01-64.0  | 23        | 3.25%   |
| 2.01-3.0    | 19        | 2.69%   |
| 24.01-32.0  | 8         | 1.13%   |
| 0.51-1.0    | 7         | 0.99%   |
| 64.01-256.0 | 4         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 286       | 37.34%  |
| 2.01-3.0  | 220       | 28.72%  |
| 3.01-4.0  | 104       | 13.58%  |
| 4.01-8.0  | 76        | 9.92%   |
| 0.51-1.0  | 52        | 6.79%   |
| 8.01-16.0 | 24        | 3.13%   |
| 0.01-0.5  | 4         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 518       | 72.65%  |
| 2      | 152       | 21.32%  |
| 3      | 27        | 3.79%   |
| 4      | 11        | 1.54%   |
| 5      | 2         | 0.28%   |
| 8      | 1         | 0.14%   |
| 6      | 1         | 0.14%   |
| 0      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 443       | 62.84%  |
| Yes       | 262       | 37.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 606       | 86.2%   |
| No        | 97        | 13.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 575       | 81.68%  |
| No        | 129       | 18.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 441       | 62.73%  |
| No        | 262       | 37.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Colombia | 701       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Bogotá                     | 282       | 38.79%  |
| Medellín                   | 104       | 14.31%  |
| Santiago de Cali            | 66        | 9.08%   |
| Bucaramanga                 | 35        | 4.81%   |
| Barranquilla                | 33        | 4.54%   |
| Pereira                     | 19        | 2.61%   |
| Cartagena                   | 16        | 2.2%    |
| Manizales                   | 12        | 1.65%   |
| Envigado                    | 11        | 1.51%   |
| Cúcuta                     | 9         | 1.24%   |
| Villavicencio               | 8         | 1.1%    |
| Popayán                    | 8         | 1.1%    |
| Ibague                      | 7         | 0.96%   |
| Santa Marta                 | 6         | 0.83%   |
| Montería                   | 5         | 0.69%   |
| Bello                       | 5         | 0.69%   |
| Armenia                     | 5         | 0.69%   |
| Fusagasuga                  | 4         | 0.55%   |
| Chia                        | 4         | 0.55%   |
| Valledupar                  | 3         | 0.41%   |
| Tunja                       | 3         | 0.41%   |
| Sincelejo                   | 3         | 0.41%   |
| Rionegro                    | 3         | 0.41%   |
| Pasto                       | 3         | 0.41%   |
| Palmira                     | 3         | 0.41%   |
| Los Patios                  | 3         | 0.41%   |
| Ipiales                     | 3         | 0.41%   |
| Yopal                       | 2         | 0.28%   |
| Soledad                     | 2         | 0.28%   |
| Soacha                      | 2         | 0.28%   |
| Sabaneta                    | 2         | 0.28%   |
| Neiva                       | 2         | 0.28%   |
| La Estrella                 | 2         | 0.28%   |
| Facatativá                 | 2         | 0.28%   |
| Calarcá                    | 2         | 0.28%   |
| BogotГЎ                   | 2         | 0.28%   |
| Barrancabermeja             | 2         | 0.28%   |
| Zarzal                      | 1         | 0.14%   |
| Villagarzon                 | 1         | 0.14%   |
| Villa de San Diego de Ubate | 1         | 0.14%   |
| Tuluá                      | 1         | 0.14%   |
| Sogamoso                    | 1         | 0.14%   |
| San Gil                     | 1         | 0.14%   |
| San Andres de Palomo        | 1         | 0.14%   |
| San Agustin                 | 1         | 0.14%   |
| Puerto Carreño             | 1         | 0.14%   |
| Pitalito                    | 1         | 0.14%   |
| Piendamo                    | 1         | 0.14%   |
| Mosquera                    | 1         | 0.14%   |
| Mompos                      | 1         | 0.14%   |
| Mitú                       | 1         | 0.14%   |
| Marinilla                   | 1         | 0.14%   |
| Magangué                   | 1         | 0.14%   |
| La Loma                     | 1         | 0.14%   |
| Jamundi                     | 1         | 0.14%   |
| Itaguei                     | 1         | 0.14%   |
| Guadalajara de Buga         | 1         | 0.14%   |
| Giron                       | 1         | 0.14%   |
| Funza                       | 1         | 0.14%   |
| Floridablanca               | 1         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 176       | 218    | 19.13%  |
| WDC                       | 138       | 172    | 15%     |
| Toshiba                   | 134       | 155    | 14.57%  |
| Samsung Electronics       | 62        | 73     | 6.74%   |
| Kingston                  | 57        | 72     | 6.2%    |
| Hitachi                   | 57        | 69     | 6.2%    |
| SanDisk                   | 45        | 52     | 4.89%   |
| HGST                      | 33        | 42     | 3.59%   |
| A-DATA Technology         | 32        | 39     | 3.48%   |
| Unknown                   | 31        | 34     | 3.37%   |
| Crucial                   | 27        | 29     | 2.93%   |
| Maxtor                    | 14        | 15     | 1.52%   |
| SK hynix                  | 13        | 19     | 1.41%   |
| Intel                     | 13        | 14     | 1.41%   |
| China                     | 8         | 8      | 0.87%   |
| Apple                     | 8         | 8      | 0.87%   |
| Realtek Semiconductor     | 6         | 7      | 0.65%   |
| Phison                    | 6         | 8      | 0.65%   |
| Micron Technology         | 6         | 6      | 0.65%   |
| Gigabyte Technology       | 5         | 6      | 0.54%   |
| Fujitsu                   | 5         | 5      | 0.54%   |
| XPG                       | 4         | 4      | 0.43%   |
| Silicon Motion            | 3         | 3      | 0.33%   |
| PNY                       | 3         | 3      | 0.33%   |
| LITEONIT                  | 3         | 3      | 0.33%   |
| KingDian                  | 3         | 3      | 0.33%   |
| JMicron Technology        | 3         | 3      | 0.33%   |
| Transcend                 | 2         | 3      | 0.22%   |
| Team                      | 2         | 2      | 0.22%   |
| Lexar                     | 2         | 2      | 0.22%   |
| Hewlett-Packard           | 2         | 2      | 0.22%   |
| Corsair                   | 2         | 2      | 0.22%   |
| Zheino                    | 1         | 1      | 0.11%   |
| XrayDisk                  | 1         | 1      | 0.11%   |
| SUPERSONIC                | 1         | 1      | 0.11%   |
| SSSTC                     | 1         | 1      | 0.11%   |
| RDM-II                    | 1         | 2      | 0.11%   |
| Netac                     | 1         | 1      | 0.11%   |
| Micron/Crucial Technology | 1         | 1      | 0.11%   |
| LITEON                    | 1         | 2      | 0.11%   |
| KIOXIA                    | 1         | 2      | 0.11%   |
| KingSpec                  | 1         | 1      | 0.11%   |
| KINGBANK                  | 1         | 1      | 0.11%   |
| ExcelStor                 | 1         | 1      | 0.11%   |
| ASMT                      | 1         | 1      | 0.11%   |
| Argon                     | 1         | 1      | 0.11%   |
| Unknown                   | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 37        | 3.92%   |
| Toshiba MQ04ABF100 1TB              | 29        | 3.08%   |
| Toshiba MQ01ABF050 500GB            | 20        | 2.12%   |
| Toshiba DT01ACA100 1TB              | 18        | 1.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 17        | 1.8%    |
| Toshiba MQ01ABD100 1TB              | 16        | 1.7%    |
| Kingston SA400S37240G 240GB SSD     | 13        | 1.38%   |
| Seagate ST500LT012-1DG142 500GB     | 12        | 1.27%   |
| Kingston SA400S37120G 120GB SSD     | 11        | 1.17%   |
| Crucial CT240BX500SSD1 240GB        | 11        | 1.17%   |
| HGST HTS541010B7E610 1TB            | 8         | 0.85%   |
| HGST HTS541010A9E680 1TB            | 8         | 0.85%   |
| Unknown MMC Card  64GB              | 7         | 0.74%   |
| SanDisk NVMe SSD Drive 512GB        | 7         | 0.74%   |
| SanDisk NVMe SSD Drive 256GB        | 7         | 0.74%   |
| WDC WD10SPZX-24Z10 1TB              | 6         | 0.64%   |
| Toshiba HDWD110 1TB                 | 6         | 0.64%   |
| Toshiba DT01ACA200 2TB              | 6         | 0.64%   |
| Toshiba DT01ACA050 500GB            | 6         | 0.64%   |
| Seagate ST500LT012-9WS142 500GB     | 6         | 0.64%   |
| Kingston SA400S37480G 480GB SSD     | 6         | 0.64%   |
| Hitachi HDS721050CLA362 500GB       | 6         | 0.64%   |
| HGST HTS545050A7E680 500GB          | 6         | 0.64%   |
| Unknown SD/MMC/MS PRO 128GB         | 5         | 0.53%   |
| Unknown MMC Card  32GB              | 5         | 0.53%   |
| Seagate ST500LM030-1RK17D 500GB     | 5         | 0.53%   |
| Seagate ST500DM002-1BD142 500GB     | 5         | 0.53%   |
| SanDisk NVMe SSD Drive 1TB          | 5         | 0.53%   |
| Kingston SV300S37A120G 120GB SSD    | 5         | 0.53%   |
| Intel NVMe SSD Drive 512GB          | 5         | 0.53%   |
| Hitachi HDS721616PLA380 160GB       | 5         | 0.53%   |
| Crucial CT500MX500SSD1 500GB        | 5         | 0.53%   |
| A-DATA SU650 120GB SSD              | 5         | 0.53%   |
| A-DATA SU630 240GB SSD              | 5         | 0.53%   |
| WDC WD10SPZX-60Z10T0 1TB            | 4         | 0.42%   |
| Toshiba MQ01ABD050 500GB            | 4         | 0.42%   |
| SK hynix NVMe SSD Drive 256GB       | 4         | 0.42%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 4         | 0.42%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 0.42%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.42%   |
| Seagate ST1000DM003-1SB102 1TB      | 4         | 0.42%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.42%   |
| Samsung NVMe SSD Drive 512GB        | 4         | 0.42%   |
| Samsung NVMe SSD Drive 256GB        | 4         | 0.42%   |
| Realtek NVMe SSD Drive 512GB        | 4         | 0.42%   |
| Crucial CT1000BX500SSD1 1TB         | 4         | 0.42%   |
| A-DATA SU650NS38 240GB SSD          | 4         | 0.42%   |
| A-DATA SU630 480GB SSD              | 4         | 0.42%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 3         | 0.32%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 3         | 0.32%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3         | 0.32%   |
| WDC WD1600BEVT-75ZCT2 160GB         | 3         | 0.32%   |
| WDC WD1200BEVS-60UST0 120GB         | 3         | 0.32%   |
| WDC WD10JPCX-24UE4T0 1TB            | 3         | 0.32%   |
| WDC WD10EZEX-60WN4A0 1TB            | 3         | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 0.32%   |
| Seagate ST9500420AS 500GB           | 3         | 0.32%   |
| Seagate ST9500325AS 500GB           | 3         | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.32%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 176       | 218    | 31.26%  |
| Toshiba             | 130       | 149    | 23.09%  |
| WDC                 | 120       | 152    | 21.31%  |
| Hitachi             | 57        | 69     | 10.12%  |
| HGST                | 33        | 42     | 5.86%   |
| Samsung Electronics | 17        | 19     | 3.02%   |
| Maxtor              | 14        | 15     | 2.49%   |
| Unknown             | 5         | 6      | 0.89%   |
| Fujitsu             | 5         | 5      | 0.89%   |
| Apple               | 3         | 3      | 0.53%   |
| Phison              | 1         | 2      | 0.18%   |
| JMicron Technology  | 1         | 1      | 0.18%   |
| ExcelStor           | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 47        | 60     | 22.93%  |
| A-DATA Technology   | 30        | 37     | 14.63%  |
| Crucial             | 24        | 26     | 11.71%  |
| Samsung Electronics | 21        | 22     | 10.24%  |
| SanDisk             | 18        | 21     | 8.78%   |
| WDC                 | 11        | 12     | 5.37%   |
| China               | 8         | 8      | 3.9%    |
| Toshiba             | 5         | 6      | 2.44%   |
| Intel               | 4         | 5      | 1.95%   |
| Gigabyte Technology | 4         | 5      | 1.95%   |
| Apple               | 4         | 4      | 1.95%   |
| SK hynix            | 3         | 7      | 1.46%   |
| Micron Technology   | 3         | 3      | 1.46%   |
| LITEONIT            | 3         | 3      | 1.46%   |
| KingDian            | 3         | 3      | 1.46%   |
| Transcend           | 2         | 3      | 0.98%   |
| Team                | 2         | 2      | 0.98%   |
| PNY                 | 2         | 2      | 0.98%   |
| Lexar               | 2         | 2      | 0.98%   |
| Zheino              | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |
| Netac               | 1         | 1      | 0.49%   |
| LITEON              | 1         | 2      | 0.49%   |
| KingSpec            | 1         | 1      | 0.49%   |
| Hewlett-Packard     | 1         | 1      | 0.49%   |
| Corsair             | 1         | 1      | 0.49%   |
| Argon               | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 492       | 682    | 58.92%  |
| SSD     | 194       | 241    | 23.23%  |
| NVMe    | 117       | 140    | 14.01%  |
| MMC     | 25        | 28     | 2.99%   |
| Unknown | 7         | 8      | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 604       | 911    | 79.06%  |
| NVMe | 117       | 140    | 15.31%  |
| MMC  | 25        | 28     | 3.27%   |
| SAS  | 18        | 20     | 2.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 397       | 540    | 56.96%  |
| 0.51-1.0   | 263       | 329    | 37.73%  |
| 1.01-2.0   | 27        | 36     | 3.87%   |
| 4.01-10.0  | 4         | 5      | 0.57%   |
| 3.01-4.0   | 3         | 9      | 0.43%   |
| 2.01-3.0   | 2         | 2      | 0.29%   |
| 0          | 1         | 2      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 189       | 25.61%  |
| 251-500        | 175       | 23.71%  |
| 501-1000       | 151       | 20.46%  |
| 51-100         | 63        | 8.54%   |
| 1-20           | 55        | 7.45%   |
| 1001-2000      | 40        | 5.42%   |
| 21-50          | 33        | 4.47%   |
| Unknown        | 12        | 1.63%   |
| More than 3000 | 11        | 1.49%   |
| 2001-3000      | 9         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 320       | 42.05%  |
| 21-50          | 147       | 19.32%  |
| 101-250        | 102       | 13.4%   |
| 51-100         | 88        | 11.56%  |
| 251-500        | 49        | 6.44%   |
| 501-1000       | 31        | 4.07%   |
| Unknown        | 12        | 1.58%   |
| 1001-2000      | 6         | 0.79%   |
| More than 3000 | 3         | 0.39%   |
| 2001-3000      | 3         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 4      | 5.41%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 2         | 2      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB                | 2         | 2      | 2.7%    |
| Seagate ST1000DM003-1SB102 1TB                 | 2         | 2      | 2.7%    |
| A-DATA Technology SU630 480GB SSD              | 2         | 2      | 2.7%    |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 1.35%   |
| WDC WD5000BEVT-22A0RT0 500GB                   | 1         | 1      | 1.35%   |
| WDC WD5000AAKS-08V0A0 500GB                    | 1         | 1      | 1.35%   |
| WDC WD3200BPVT-24JJ5T0 320GB                   | 1         | 1      | 1.35%   |
| WDC WD3200BEKT-60F3T1 320GB                    | 1         | 1      | 1.35%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 1         | 1      | 1.35%   |
| WDC WD3200AAJS-60Z0A0 320GB                    | 1         | 1      | 1.35%   |
| WDC WD3200AAJS-56M0A0 320GB                    | 1         | 1      | 1.35%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 1.35%   |
| WDC WD1600BEKT-60V5T1 160GB                    | 1         | 1      | 1.35%   |
| WDC WD1600AAJS-75M0A0 160GB                    | 1         | 1      | 1.35%   |
| WDC WD10EURX-73FH1Y0 1TB                       | 1         | 1      | 1.35%   |
| WDC WD10EACS-00D6B1 1TB                        | 1         | 1      | 1.35%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 2      | 1.35%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.35%   |
| Toshiba MK7559GSXP 752GB                       | 1         | 1      | 1.35%   |
| Toshiba MK5076GSX 500GB                        | 1         | 1      | 1.35%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 1.35%   |
| Toshiba HDWD110 1TB                            | 1         | 1      | 1.35%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.35%   |
| Seagate ST9320423AS 320GB                      | 1         | 1      | 1.35%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 1.35%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 1.35%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 1.35%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 1.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 1.35%   |
| Seagate ST3320613AS 320GB                      | 1         | 3      | 1.35%   |
| Seagate ST3320311CS 320GB                      | 1         | 2      | 1.35%   |
| Seagate ST3250820AS 250GB                      | 1         | 1      | 1.35%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 1.35%   |
| Seagate ST2000DM001-1CH164 2TB                 | 1         | 1      | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB                 | 1         | 2      | 1.35%   |
| Seagate ST1000DM003-1ER162 1TB                 | 1         | 1      | 1.35%   |
| Seagate ST1000DM003-1CH162 1TB                 | 1         | 1      | 1.35%   |
| Samsung Electronics SSD 970 EVO 500GB          | 1         | 1      | 1.35%   |
| Samsung Electronics HM250HI 250GB              | 1         | 1      | 1.35%   |
| Samsung Electronics HD502HJ 500GB              | 1         | 1      | 1.35%   |
| Samsung Electronics HD322HJ 320GB              | 1         | 1      | 1.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.35%   |
| Maxtor STM3160211AS 160GB                      | 1         | 1      | 1.35%   |
| Maxtor 6B250S0 256GB                           | 1         | 1      | 1.35%   |
| Maxtor 53073H6 32GB                            | 1         | 1      | 1.35%   |
| Maxtor 2F040L0 41GB                            | 1         | 1      | 1.35%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 2      | 1.35%   |
| Hitachi HTS725032A9A364 320GB                  | 1         | 1      | 1.35%   |
| Hitachi HTS721080G9SA00 80GB                   | 1         | 1      | 1.35%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.35%   |
| Hitachi HTS545032B9A300 320GB                  | 1         | 1      | 1.35%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 1.35%   |
| Hitachi HTS543225L9A300 250GB                  | 1         | 5      | 1.35%   |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 1.35%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 1.35%   |
| Hitachi HDT721010SLA360 1TB                    | 1         | 2      | 1.35%   |
| Hitachi HDS728080PLAT20 82GB                   | 1         | 1      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 30     | 33.8%   |
| WDC                 | 12        | 13     | 16.9%   |
| Hitachi             | 12        | 17     | 16.9%   |
| Toshiba             | 6         | 7      | 8.45%   |
| Samsung Electronics | 4         | 4      | 5.63%   |
| Maxtor              | 4         | 4      | 5.63%   |
| HGST                | 2         | 2      | 2.82%   |
| A-DATA Technology   | 2         | 2      | 2.82%   |
| Micron Technology   | 1         | 1      | 1.41%   |
| Intel               | 1         | 2      | 1.41%   |
| Fujitsu             | 1         | 1      | 1.41%   |
| Crucial             | 1         | 1      | 1.41%   |
| Apple               | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 30     | 36.92%  |
| WDC                 | 12        | 13     | 18.46%  |
| Hitachi             | 12        | 17     | 18.46%  |
| Toshiba             | 6         | 7      | 9.23%   |
| Maxtor              | 4         | 4      | 6.15%   |
| Samsung Electronics | 3         | 3      | 4.62%   |
| HGST                | 2         | 2      | 3.08%   |
| Fujitsu             | 1         | 1      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 78     | 91.3%   |
| SSD  | 5         | 6      | 7.25%   |
| NVMe | 1         | 1      | 1.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Maxtor STM380211AS 80GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Maxtor | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 497       | 775    | 67.34%  |
| Works    | 171       | 238    | 23.17%  |
| Malfunc  | 69        | 85     | 9.35%   |
| Failed   | 1         | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 449       | 56.98%  |
| AMD                            | 187       | 23.73%  |
| SanDisk                        | 33        | 4.19%   |
| Samsung Electronics            | 25        | 3.17%   |
| Nvidia                         | 19        | 2.41%   |
| SK hynix                       | 10        | 1.27%   |
| Realtek Semiconductor          | 9         | 1.14%   |
| Kingston Technology Company    | 9         | 1.14%   |
| Phison Electronics             | 7         | 0.89%   |
| ASMedia Technology             | 7         | 0.89%   |
| VIA Technologies               | 6         | 0.76%   |
| Micron Technology              | 5         | 0.63%   |
| Silicon Motion                 | 4         | 0.51%   |
| Marvell Technology Group       | 3         | 0.38%   |
| JMicron Technology             | 3         | 0.38%   |
| ADATA Technology               | 3         | 0.38%   |
| Micron/Crucial Technology      | 2         | 0.25%   |
| Union Memory (Shenzhen)        | 1         | 0.13%   |
| Solid State Storage Technology | 1         | 0.13%   |
| LSI Logic / Symbios Logic      | 1         | 0.13%   |
| KIOXIA                         | 1         | 0.13%   |
| Hewlett-Packard                | 1         | 0.13%   |
| Biwin Storage Technology       | 1         | 0.13%   |
| Apple                          | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 143       | 15.75%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 55        | 6.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 36        | 3.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 35        | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 27        | 2.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 26        | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 22        | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18        | 1.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 16        | 1.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 16        | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16        | 1.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 14        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12        | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 11        | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 10        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10        | 1.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 8         | 0.88%   |
| Realtek Realtek Non-Volatile memory controller                                          | 8         | 0.88%   |
| Nvidia MCP61 SATA Controller                                                            | 8         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8         | 0.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8         | 0.88%   |
| Nvidia MCP61 IDE                                                                        | 7         | 0.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 7         | 0.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 0.66%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6         | 0.66%   |
| SanDisk PC SN520 NVMe SSD                                                               | 5         | 0.55%   |
| SanDisk Non-Volatile memory controller                                                  | 5         | 0.55%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 0.55%   |
| Micron Non-Volatile memory controller                                                   | 5         | 0.55%   |
| Intel SSD 660P Series                                                                   | 5         | 0.55%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 0.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 0.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 0.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 0.55%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 5         | 0.55%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 4         | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 4         | 0.44%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 0.44%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4         | 0.44%   |
| Phison E12 NVMe Controller                                                              | 4         | 0.44%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 4         | 0.44%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 4         | 0.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 4         | 0.44%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4         | 0.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 0.44%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 537       | 66.13%  |
| NVMe | 116       | 14.29%  |
| IDE  | 109       | 13.42%  |
| RAID | 49        | 6.03%   |
| SAS  | 1         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 482       | 68.76%  |
| AMD    | 216       | 30.81%  |
| ARM    | 3         | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 23        | 3.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 12        | 1.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 12        | 1.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 9         | 1.28%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 9         | 1.28%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 9         | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 8         | 1.14%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 8         | 1.14%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 8         | 1.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 7         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz               | 7         | 1%      |
| AMD Ryzen 5 3600 6-Core Processor               | 7         | 1%      |
| Intel Core i7-4510U CPU @ 2.00GHz               | 6         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 6         | 0.85%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 6         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 6         | 0.85%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 6         | 0.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 6         | 0.85%   |
| AMD FX-8320 Eight-Core Processor                | 6         | 0.85%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 6         | 0.85%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 5         | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 5         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 5         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 5         | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 5         | 0.71%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 5         | 0.71%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 5         | 0.71%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 5         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 4         | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 4         | 0.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 4         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 0.57%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 4         | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 4         | 0.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 4         | 0.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 4         | 0.57%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 4         | 0.57%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 4         | 0.57%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 4         | 0.57%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 4         | 0.57%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 4         | 0.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 4         | 0.57%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 4         | 0.57%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 4         | 0.57%   |
| AMD E-300 APU with Radeon HD Graphics           | 4         | 0.57%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 3         | 0.43%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz          | 3         | 0.43%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz          | 3         | 0.43%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz          | 3         | 0.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 0.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 3         | 0.43%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 3         | 0.43%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 3         | 0.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 3         | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 0.43%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 3         | 0.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 3         | 0.43%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 3         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 134       | 19.06%  |
| Intel Core i7                  | 111       | 15.79%  |
| Intel Core i3                  | 76        | 10.81%  |
| AMD Ryzen 5                    | 53        | 7.54%   |
| Intel Celeron                  | 44        | 6.26%   |
| Other                          | 38        | 5.41%   |
| Intel Core 2 Duo               | 23        | 3.27%   |
| Intel Atom                     | 22        | 3.13%   |
| AMD Ryzen 3                    | 17        | 2.42%   |
| Intel Pentium Dual-Core        | 14        | 1.99%   |
| AMD Ryzen 7                    | 13        | 1.85%   |
| AMD FX                         | 12        | 1.71%   |
| Intel Pentium Dual             | 11        | 1.56%   |
| Intel Pentium                  | 11        | 1.56%   |
| AMD A4                         | 9         | 1.28%   |
| AMD A12                        | 9         | 1.28%   |
| AMD A10                        | 9         | 1.28%   |
| AMD E1                         | 8         | 1.14%   |
| Intel Xeon                     | 7         | 1%      |
| AMD A8                         | 7         | 1%      |
| AMD A6                         | 7         | 1%      |
| AMD Ryzen 7 PRO                | 6         | 0.85%   |
| AMD Athlon 64 X2               | 5         | 0.71%   |
| Intel Core 2                   | 4         | 0.57%   |
| AMD Ryzen 9                    | 4         | 0.57%   |
| AMD Phenom II X6               | 4         | 0.57%   |
| AMD E                          | 4         | 0.57%   |
| AMD Athlon II X2               | 4         | 0.57%   |
| AMD Athlon                     | 4         | 0.57%   |
| AMD Ryzen Threadripper         | 3         | 0.43%   |
| AMD E2                         | 3         | 0.43%   |
| Intel Pentium 4                | 2         | 0.28%   |
| Intel Core m5                  | 2         | 0.28%   |
| Intel Celeron M                | 2         | 0.28%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.28%   |
| AMD Sempron                    | 2         | 0.28%   |
| AMD Phenom                     | 2         | 0.28%   |
| Intel Pentium D                | 1         | 0.14%   |
| Intel Genuine                  | 1         | 0.14%   |
| Intel Core M                   | 1         | 0.14%   |
| Intel Core i9                  | 1         | 0.14%   |
| Intel Core 2 Quad              | 1         | 0.14%   |
| Intel Celeron D                | 1         | 0.14%   |
| AMD V120                       | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.14%   |
| AMD Phenom II X4               | 1         | 0.14%   |
| AMD Mobile Sempron             | 1         | 0.14%   |
| AMD Dual Core Opteron          | 1         | 0.14%   |
| AMD C-70                       | 1         | 0.14%   |
| AMD C-60                       | 1         | 0.14%   |
| AMD Athlon II Neo              | 1         | 0.14%   |
| AMD Athlon 64                  | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 372       | 52.99%  |
| 4       | 222       | 31.62%  |
| 6       | 40        | 5.7%    |
| 1       | 31        | 4.42%   |
| 8       | 21        | 2.99%   |
| 3       | 5         | 0.71%   |
| 16      | 4         | 0.57%   |
| 12      | 3         | 0.43%   |
| 14      | 2         | 0.28%   |
| 10      | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 694       | 99%     |
| 2      | 7         | 1%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 451       | 64.06%  |
| 1       | 251       | 35.65%  |
| 8       | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 656       | 92.92%  |
| Unknown        | 39        | 5.52%   |
| 64-bit         | 7         | 0.99%   |
| 32-bit         | 4         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 15.13%  |
| 0x306a9    | 43        | 6.02%   |
| 0x206a7    | 41        | 5.74%   |
| 0x806ea    | 29        | 4.06%   |
| 0x306c3    | 24        | 3.36%   |
| 0x08108109 | 23        | 3.22%   |
| 0x406e3    | 22        | 3.08%   |
| 0x1067a    | 21        | 2.94%   |
| 0x06006705 | 20        | 2.8%    |
| 0x6fd      | 17        | 2.38%   |
| 0x40651    | 17        | 2.38%   |
| 0x306d4    | 15        | 2.1%    |
| 0x406c4    | 14        | 1.96%   |
| 0x906ea    | 13        | 1.82%   |
| 0x806ec    | 13        | 1.82%   |
| 0x806e9    | 13        | 1.82%   |
| 0x20655    | 13        | 1.82%   |
| 0x08108102 | 13        | 1.82%   |
| 0x806c1    | 10        | 1.4%    |
| 0x706e5    | 9         | 1.26%   |
| 0x706a1    | 9         | 1.26%   |
| 0x08701021 | 9         | 1.26%   |
| 0x06000852 | 9         | 1.26%   |
| 0x506e3    | 8         | 1.12%   |
| 0x10676    | 8         | 1.12%   |
| 0x806eb    | 7         | 0.98%   |
| 0x20652    | 7         | 0.98%   |
| 0x06006118 | 7         | 0.98%   |
| 0x05000119 | 7         | 0.98%   |
| 0x906e9    | 6         | 0.84%   |
| 0x30678    | 6         | 0.84%   |
| 0x106e5    | 6         | 0.84%   |
| 0x106ca    | 6         | 0.84%   |
| 0x08101007 | 6         | 0.84%   |
| 0x06006704 | 6         | 0.84%   |
| 0x0600611a | 6         | 0.84%   |
| 0xa0653    | 5         | 0.7%    |
| 0x6f6      | 5         | 0.7%    |
| 0x106c2    | 5         | 0.7%    |
| 0x08600106 | 5         | 0.7%    |
| 0x07030104 | 5         | 0.7%    |
| 0x010000c8 | 5         | 0.7%    |
| 0xa0652    | 4         | 0.56%   |
| 0x0a50000c | 4         | 0.56%   |
| 0x0810100b | 4         | 0.56%   |
| 0x07030105 | 4         | 0.56%   |
| 0x0700010f | 4         | 0.56%   |
| 0x06001119 | 4         | 0.56%   |
| 0x010000dc | 4         | 0.56%   |
| 0xf65      | 3         | 0.42%   |
| 0x406c3    | 3         | 0.42%   |
| 0x08608103 | 3         | 0.42%   |
| 0x08001138 | 3         | 0.42%   |
| 0x06003106 | 3         | 0.42%   |
| 0x03000027 | 3         | 0.42%   |
| 0xa0671    | 2         | 0.28%   |
| 0xa0655    | 2         | 0.28%   |
| 0x906a3    | 2         | 0.28%   |
| 0x706a8    | 2         | 0.28%   |
| 0x506c9    | 2         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 98        | 13.96%  |
| SandyBridge      | 51        | 7.26%   |
| IvyBridge        | 47        | 6.7%    |
| Haswell          | 47        | 6.7%    |
| Zen+             | 45        | 6.41%   |
| Excavator        | 40        | 5.7%    |
| Skylake          | 33        | 4.7%    |
| Penryn           | 33        | 4.7%    |
| Core             | 29        | 4.13%   |
| Silvermont       | 26        | 3.7%    |
| Westmere         | 25        | 3.56%   |
| Zen 2            | 24        | 3.42%   |
| Zen              | 18        | 2.56%   |
| Piledriver       | 16        | 2.28%   |
| Broadwell        | 16        | 2.28%   |
| K8 Hammer        | 14        | 1.99%   |
| K10              | 14        | 1.99%   |
| Icelake          | 13        | 1.85%   |
| CometLake        | 12        | 1.71%   |
| Bonnell          | 12        | 1.71%   |
| TigerLake        | 11        | 1.57%   |
| Puma             | 11        | 1.57%   |
| Goldmont plus    | 11        | 1.57%   |
| Bobcat           | 8         | 1.14%   |
| Nehalem          | 7         | 1%      |
| Jaguar           | 7         | 1%      |
| Unknown          | 7         | 1%      |
| Zen 3            | 6         | 0.85%   |
| NetBurst         | 6         | 0.85%   |
| Steamroller      | 4         | 0.57%   |
| Goldmont         | 4         | 0.57%   |
| K10 Llano        | 3         | 0.43%   |
| Alderlake Hybrid | 2         | 0.28%   |
| K8 & K10 hybrid  | 1         | 0.14%   |
| Bulldozer        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 420       | 51.66%  |
| AMD                        | 221       | 27.18%  |
| Nvidia                     | 163       | 20.05%  |
| Matrox Electronics Systems | 5         | 0.62%   |
| VIA Technologies           | 4         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 41        | 4.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 40        | 4.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 3.86%   |
| Intel UHD Graphics 620                                                                   | 27        | 3.16%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 26        | 3.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 2.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 2.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 2.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.99%   |
| Intel HD Graphics 620                                                                    | 17        | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 14        | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.52%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.29%   |
| AMD Renoir                                                                               | 11        | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.29%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 1.17%   |
| Intel HD Graphics 530                                                                    | 9         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 0.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 8         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.94%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 8         | 0.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 0.82%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 7         | 0.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 0.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 0.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.58%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 0.58%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.58%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.58%   |
| Intel HD Graphics 630                                                                    | 5         | 0.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 0.58%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 5         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.47%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.47%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.47%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.47%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.47%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 4         | 0.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.47%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 4         | 0.47%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.47%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.47%   |
| AMD RS780L [Radeon 3000]                                                                 | 4         | 0.47%   |
| AMD Lucienne                                                                             | 4         | 0.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.47%   |
| AMD Cezanne                                                                              | 4         | 0.47%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 317       | 45.09%  |
| 1 x AMD         | 172       | 24.47%  |
| Intel + Nvidia  | 87        | 12.38%  |
| 1 x Nvidia      | 67        | 9.53%   |
| 2 x AMD         | 28        | 3.98%   |
| Intel + AMD     | 13        | 1.85%   |
| AMD + Nvidia    | 7         | 1%      |
| 1 x VIA         | 4         | 0.57%   |
| 1 x Matrox      | 4         | 0.57%   |
| Other           | 3         | 0.43%   |
| Nvidia + Matrox | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 594       | 84.14%  |
| Proprietary | 75        | 10.62%  |
| Unknown     | 37        | 5.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 377       | 52.88%  |
| 1.01-2.0   | 120       | 16.83%  |
| 0.01-0.5   | 112       | 15.71%  |
| 0.51-1.0   | 51        | 7.15%   |
| 3.01-4.0   | 38        | 5.33%   |
| 7.01-8.0   | 5         | 0.7%    |
| 5.01-6.0   | 5         | 0.7%    |
| 8.01-16.0  | 3         | 0.42%   |
| 2.01-3.0   | 2         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 128       | 17.16%  |
| Samsung Electronics     | 119       | 15.95%  |
| AU Optronics            | 102       | 13.67%  |
| BOE                     | 77        | 10.32%  |
| LG Display              | 61        | 8.18%   |
| Goldstar                | 51        | 6.84%   |
| Hewlett-Packard         | 37        | 4.96%   |
| Dell                    | 23        | 3.08%   |
| Apple                   | 15        | 2.01%   |
| Acer                    | 15        | 2.01%   |
| Chi Mei Optoelectronics | 12        | 1.61%   |
| AOC                     | 11        | 1.47%   |
| PANDA                   | 10        | 1.34%   |
| Lenovo                  | 8         | 1.07%   |
| Sharp                   | 7         | 0.94%   |
| ViewSonic               | 6         | 0.8%    |
| Sony                    | 5         | 0.67%   |
| InnoLux Display         | 5         | 0.67%   |
| Unknown                 | 4         | 0.54%   |
| LG Philips              | 4         | 0.54%   |
| InfoVision              | 4         | 0.54%   |
| SAC                     | 3         | 0.4%    |
| LG Electronics          | 3         | 0.4%    |
| HannStar                | 3         | 0.4%    |
| CSO                     | 3         | 0.4%    |
| BenQ                    | 3         | 0.4%    |
| SANYO                   | 2         | 0.27%   |
| KTC                     | 2         | 0.27%   |
| ASUSTek Computer        | 2         | 0.27%   |
| Ancor Communications    | 2         | 0.27%   |
| AGO                     | 2         | 0.27%   |
| Westinghouse            | 1         | 0.13%   |
| Unknown (XXX)           | 1         | 0.13%   |
| SMC                     | 1         | 0.13%   |
| SKG                     | 1         | 0.13%   |
| PEGA                    | 1         | 0.13%   |
| NCS                     | 1         | 0.13%   |
| MStar                   | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| LTM                     | 1         | 0.13%   |
| KOA                     | 1         | 0.13%   |
| KDC                     | 1         | 0.13%   |
| HKC                     | 1         | 0.13%   |
| HannStar Display        | 1         | 0.13%   |
| eMachines               | 1         | 0.13%   |
| ELD                     | 1         | 0.13%   |
| DENON                   | 1         | 0.13%   |
| CHO                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 15        | 1.98%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 15        | 1.98%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 11        | 1.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 9         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 9         | 1.19%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                    | 8         | 1.06%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch           | 8         | 1.06%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch           | 8         | 1.06%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 7         | 0.93%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 6         | 0.79%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 6         | 0.79%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch     | 5         | 0.66%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 5         | 0.66%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 5         | 0.66%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                 | 5         | 0.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 5         | 0.66%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 5         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch         | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch           | 5         | 0.66%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 4         | 0.53%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                    | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch        | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch         | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 4         | 0.53%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                    | 4         | 0.53%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                    | 4         | 0.53%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                    | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 4         | 0.53%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                 | 3         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 3         | 0.4%    |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch    | 3         | 0.4%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 3         | 0.4%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch             | 3         | 0.4%    |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch             | 3         | 0.4%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 3         | 0.4%    |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch       | 3         | 0.4%    |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                     | 3         | 0.4%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 3         | 0.4%    |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                   | 3         | 0.4%    |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                     | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch        | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x174mm 14.0-inch         | 3         | 0.4%    |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                   | 3         | 0.4%    |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                    | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch           | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch           | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch           | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch           | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch           | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch           | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch           | 3         | 0.4%    |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                        | 3         | 0.4%    |
| Acer V206HQLB ACR051A 1366x768 434x236mm 19.4-inch                      | 3         | 0.4%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 2         | 0.26%   |
| Sony TV SNYF301 1920x1080                                               | 2         | 0.26%   |
| SANYO LCD TV SAN0523 1920x1080 443x249mm 20.0-inch                      | 2         | 0.26%   |
| Samsung Electronics U28E510 SAM0D63 3840x2160 607x345mm 27.5-inch       | 2         | 0.26%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch     | 2         | 0.26%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch    | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 329       | 46.01%  |
| 1920x1080 (FHD)    | 188       | 26.29%  |
| 1600x900 (HD+)     | 38        | 5.31%   |
| 3840x2160 (4K)     | 30        | 4.2%    |
| 1440x900 (WXGA+)   | 25        | 3.5%    |
| 1280x1024 (SXGA)   | 23        | 3.22%   |
| 1280x800 (WXGA)    | 18        | 2.52%   |
| 1360x768           | 9         | 1.26%   |
| 2560x1440 (QHD)    | 7         | 0.98%   |
| 1920x1200 (WUXGA)  | 7         | 0.98%   |
| 1024x600           | 7         | 0.98%   |
| 2560x1080          | 4         | 0.56%   |
| Unknown            | 4         | 0.56%   |
| 3840x1080          | 3         | 0.42%   |
| 2560x1600          | 3         | 0.42%   |
| 1680x1050 (WSXGA+) | 3         | 0.42%   |
| 1024x768 (XGA)     | 3         | 0.42%   |
| 3456x2160          | 2         | 0.28%   |
| 3440x1440          | 2         | 0.28%   |
| 2160x1440          | 2         | 0.28%   |
| 1280x720 (HD)      | 2         | 0.28%   |
| 3200x1080          | 1         | 0.14%   |
| 2880x1800          | 1         | 0.14%   |
| 2256x1504          | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1536x2048          | 1         | 0.14%   |
| 1152x864           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 176       | 23.44%  |
| 13      | 137       | 18.24%  |
| 14      | 105       | 13.98%  |
| 21      | 48        | 6.39%   |
| 23      | 36        | 4.79%   |
| 19      | 35        | 4.66%   |
| 17      | 34        | 4.53%   |
| 18      | 33        | 4.39%   |
| Unknown | 17        | 2.26%   |
| 20      | 16        | 2.13%   |
| 27      | 15        | 2%      |
| 24      | 13        | 1.73%   |
| 12      | 12        | 1.6%    |
| 11      | 12        | 1.6%    |
| 31      | 8         | 1.07%   |
| 10      | 8         | 1.07%   |
| 84      | 6         | 0.8%    |
| 47      | 6         | 0.8%    |
| 72      | 5         | 0.67%   |
| 22      | 5         | 0.67%   |
| 34      | 4         | 0.53%   |
| 48      | 2         | 0.27%   |
| 40      | 2         | 0.27%   |
| 26      | 2         | 0.27%   |
| 16      | 2         | 0.27%   |
| 8       | 2         | 0.27%   |
| 61      | 1         | 0.13%   |
| 60      | 1         | 0.13%   |
| 54      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 44      | 1         | 0.13%   |
| 43      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 28      | 1         | 0.13%   |
| 9       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 400       | 53.98%  |
| 401-500     | 130       | 17.54%  |
| 201-300     | 58        | 7.83%   |
| 501-600     | 57        | 7.69%   |
| 351-400     | 27        | 3.64%   |
| Unknown     | 17        | 2.29%   |
| 601-700     | 16        | 2.16%   |
| 1001-1500   | 13        | 1.75%   |
| 1501-2000   | 11        | 1.48%   |
| 701-800     | 5         | 0.67%   |
| 101-200     | 3         | 0.4%    |
| 801-900     | 2         | 0.27%   |
| 901-1000    | 2         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 561       | 83.11%  |
| 16/10   | 59        | 8.74%   |
| 5/4     | 21        | 3.11%   |
| Unknown | 15        | 2.22%   |
| 4/3     | 6         | 0.89%   |
| 21/9    | 5         | 0.74%   |
| 3/2     | 4         | 0.59%   |
| 32/9    | 3         | 0.44%   |
| 0.75    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 222       | 29.72%  |
| 101-110        | 174       | 23.29%  |
| 201-250        | 88        | 11.78%  |
| 151-200        | 58        | 7.76%   |
| 141-150        | 48        | 6.43%   |
| 71-80          | 20        | 2.68%   |
| 301-350        | 17        | 2.28%   |
| Unknown        | 17        | 2.28%   |
| More than 1000 | 15        | 2.01%   |
| 351-500        | 13        | 1.74%   |
| 121-130        | 13        | 1.74%   |
| 501-1000       | 13        | 1.74%   |
| 51-60          | 12        | 1.61%   |
| 61-70          | 10        | 1.34%   |
| 41-50          | 9         | 1.2%    |
| 251-300        | 7         | 0.94%   |
| 131-140        | 6         | 0.8%    |
| 111-120        | 3         | 0.4%    |
| 1-40           | 2         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 341       | 46.65%  |
| 51-100        | 194       | 26.54%  |
| 121-160       | 121       | 16.55%  |
| 1-50          | 23        | 3.15%   |
| 161-240       | 22        | 3.01%   |
| Unknown       | 17        | 2.33%   |
| More than 240 | 13        | 1.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 572       | 79.44%  |
| 2     | 105       | 14.58%  |
| 0     | 38        | 5.28%   |
| 3     | 4         | 0.56%   |
| 4     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 458       | 42.33%  |
| Intel                             | 205       | 18.95%  |
| Qualcomm Atheros                  | 174       | 16.08%  |
| Broadcom                          | 65        | 6.01%   |
| Broadcom Limited                  | 28        | 2.59%   |
| Ralink Technology                 | 25        | 2.31%   |
| TP-Link                           | 16        | 1.48%   |
| Ralink                            | 16        | 1.48%   |
| Nvidia                            | 16        | 1.48%   |
| Marvell Technology Group          | 10        | 0.92%   |
| Samsung Electronics               | 8         | 0.74%   |
| Qualcomm Atheros Communications   | 7         | 0.65%   |
| ICS Advent                        | 6         | 0.55%   |
| Xiaomi                            | 4         | 0.37%   |
| VIA Technologies                  | 4         | 0.37%   |
| MediaTek                          | 4         | 0.37%   |
| Huawei Technologies               | 4         | 0.37%   |
| ASIX Electronics                  | 4         | 0.37%   |
| Realtek                           | 3         | 0.28%   |
| D-Link System                     | 3         | 0.28%   |
| T & A Mobile Phones               | 2         | 0.18%   |
| Qualcomm                          | 2         | 0.18%   |
| Motorola PCS                      | 2         | 0.18%   |
| DisplayLink                       | 2         | 0.18%   |
| Wistron NeWeb                     | 1         | 0.09%   |
| Sundance Technology Inc / IC Plus | 1         | 0.09%   |
| STMicroelectronics                | 1         | 0.09%   |
| Quanta                            | 1         | 0.09%   |
| Prolific Technology               | 1         | 0.09%   |
| OPPO Electronics                  | 1         | 0.09%   |
| Mellanox Technologies             | 1         | 0.09%   |
| Lenovo                            | 1         | 0.09%   |
| JMicron Technology                | 1         | 0.09%   |
| Google                            | 1         | 0.09%   |
| Encore Electronics                | 1         | 0.09%   |
| Dell                              | 1         | 0.09%   |
| Aquantia                          | 1         | 0.09%   |
| 3Com                              | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 291       | 23.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 85        | 6.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 3.26%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 34        | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 2.46%   |
| Intel Wireless 8265 / 8275                                              | 28        | 2.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 1.59%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 15        | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 13        | 1.03%   |
| Ralink MT7601U Wireless Adapter                                         | 12        | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 11        | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.87%   |
| Intel Wireless 7260                                                     | 10        | 0.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                       | 9         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 0.64%   |
| Nvidia MCP61 Ethernet                                                   | 8         | 0.64%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 7         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 7         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.56%   |
| Intel Wireless 8260                                                     | 7         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 6         | 0.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.48%   |
| Intel Wireless 7265                                                     | 6         | 0.48%   |
| Intel I211 Gigabit Network Connection                                   | 6         | 0.48%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 0.48%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.4%    |
| Intel Wireless 3160                                                     | 5         | 0.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.4%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                 | 5         | 0.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 5         | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 5         | 0.4%    |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 5         | 0.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 4         | 0.32%   |
| TP-Link 802.11n NIC                                                     | 4         | 0.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 4         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 4         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 171       | 27.99%  |
| Realtek Semiconductor           | 164       | 26.84%  |
| Qualcomm Atheros                | 142       | 23.24%  |
| Broadcom                        | 38        | 6.22%   |
| Ralink Technology               | 25        | 4.09%   |
| Broadcom Limited                | 18        | 2.95%   |
| TP-Link                         | 16        | 2.62%   |
| Ralink                          | 16        | 2.62%   |
| Qualcomm Atheros Communications | 7         | 1.15%   |
| Realtek                         | 3         | 0.49%   |
| MediaTek                        | 3         | 0.49%   |
| D-Link System                   | 2         | 0.33%   |
| Wistron NeWeb                   | 1         | 0.16%   |
| Qualcomm                        | 1         | 0.16%   |
| Marvell Technology Group        | 1         | 0.16%   |
| Encore Electronics              | 1         | 0.16%   |
| Dell                            | 1         | 0.16%   |
| 3Com                            | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 6.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 34        | 5.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 5.05%   |
| Intel Wireless 8265 / 8275                                              | 28        | 4.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 4.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 4.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 3.26%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 3.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 2.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 2.12%   |
| Ralink MT7601U Wireless Adapter                                         | 12        | 1.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 11        | 1.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.79%   |
| Intel Wireless 7260                                                     | 10        | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.3%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 7         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.14%   |
| Intel Wireless 8260                                                     | 7         | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.98%   |
| Intel Wireless 7265                                                     | 6         | 0.98%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.98%   |
| Intel Wireless 3160                                                     | 5         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.81%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 5         | 0.81%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.81%   |
| TP-Link 802.11n NIC                                                     | 4         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.49%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 3         | 0.49%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.49%   |
| Realtek 802.11n NIC                                                     | 3         | 0.49%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.49%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.49%   |
| Broadcom Limited BCM43602 802.11ac Wireless LAN SoC                     | 3         | 0.49%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.49%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 0.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.33%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                    | 2         | 0.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 406       | 63.84%  |
| Intel                             | 71        | 11.16%  |
| Qualcomm Atheros                  | 47        | 7.39%   |
| Broadcom                          | 32        | 5.03%   |
| Nvidia                            | 16        | 2.52%   |
| Broadcom Limited                  | 10        | 1.57%   |
| Marvell Technology Group          | 9         | 1.42%   |
| Samsung Electronics               | 8         | 1.26%   |
| ICS Advent                        | 6         | 0.94%   |
| Xiaomi                            | 4         | 0.63%   |
| VIA Technologies                  | 4         | 0.63%   |
| Huawei Technologies               | 4         | 0.63%   |
| ASIX Electronics                  | 4         | 0.63%   |
| T & A Mobile Phones               | 2         | 0.31%   |
| DisplayLink                       | 2         | 0.31%   |
| Sundance Technology Inc / IC Plus | 1         | 0.16%   |
| Quanta                            | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| Prolific Technology               | 1         | 0.16%   |
| OPPO Electronics                  | 1         | 0.16%   |
| Mellanox Technologies             | 1         | 0.16%   |
| MediaTek                          | 1         | 0.16%   |
| Lenovo                            | 1         | 0.16%   |
| JMicron Technology                | 1         | 0.16%   |
| D-Link System                     | 1         | 0.16%   |
| Aquantia                          | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 291       | 45.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 85        | 13.28%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 15        | 2.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 13        | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                          | 9         | 1.41%   |
| Nvidia MCP61 Ethernet                                                      | 8         | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 7         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 6         | 0.94%   |
| Intel I211 Gigabit Network Connection                                      | 6         | 0.94%   |
| Intel Ethernet Connection I219-LM                                          | 6         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 5         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 5         | 0.78%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 5         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                            | 5         | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 5         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4         | 0.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 4         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 4         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                      | 4         | 0.63%   |
| Nvidia MCP79 Ethernet                                                      | 4         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 4         | 0.63%   |
| Intel Ethernet Connection I219-V                                           | 4         | 0.63%   |
| Intel 82579V Gigabit Network Connection                                    | 4         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                                   | 4         | 0.63%   |
| Huawei COL-L29                                                             | 4         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 3         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                 | 3         | 0.47%   |
| Intel Ethernet Controller I225-V                                           | 3         | 0.47%   |
| Intel Ethernet Connection I218-LM                                          | 3         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                       | 3         | 0.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                          | 3         | 0.47%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                        | 3         | 0.47%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                    | 3         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2         | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 2         | 0.31%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 2         | 0.31%   |
| Nvidia MCP67 Ethernet                                                      | 2         | 0.31%   |
| Intel Ethernet Connection (3) I218-LM                                      | 2         | 0.31%   |
| Intel Ethernet Connection (2) I219-V                                       | 2         | 0.31%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 0.31%   |
| Intel 82578DC Gigabit Network Connection                                   | 2         | 0.31%   |
| Intel 82566DM Gigabit Network Connection                                   | 2         | 0.31%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2         | 0.31%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2         | 0.31%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                     | 2         | 0.31%   |
| ASIX AX88772B                                                              | 2         | 0.31%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                               | 1         | 0.16%   |
| T & A Mobile Phones A507DL                                                 | 1         | 0.16%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.16%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1         | 0.16%   |
| Quanta HSUSB Device                                                        | 1         | 0.16%   |
| Qualcomm POCO F2 Pro                                                       | 1         | 0.16%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1         | 0.16%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1         | 0.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1         | 0.16%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1         | 0.16%   |
| Prolific PL25A1 Host-Host Bridge                                           | 1         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 605       | 51.1%   |
| WiFi     | 575       | 48.56%  |
| Unknown  | 3         | 0.25%   |
| Modem    | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 443       | 59.78%  |
| Ethernet | 297       | 40.08%  |
| Unknown  | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 421       | 59.97%  |
| 1     | 265       | 37.75%  |
| 0     | 9         | 1.28%   |
| 3     | 4         | 0.57%   |
| 7     | 1         | 0.14%   |
| 6     | 1         | 0.14%   |
| 4     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 660       | 93.35%  |
| Yes  | 47        | 6.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 141       | 31.69%  |
| Realtek Semiconductor           | 83        | 18.65%  |
| IMC Networks                    | 53        | 11.91%  |
| Qualcomm Atheros Communications | 44        | 9.89%   |
| Cambridge Silicon Radio         | 27        | 6.07%   |
| Lite-On Technology              | 26        | 5.84%   |
| Broadcom                        | 17        | 3.82%   |
| Apple                           | 13        | 2.92%   |
| Foxconn / Hon Hai               | 11        | 2.47%   |
| Ralink                          | 7         | 1.57%   |
| Hewlett-Packard                 | 6         | 1.35%   |
| Toshiba                         | 4         | 0.9%    |
| Foxconn International           | 3         | 0.67%   |
| Dell                            | 3         | 0.67%   |
| Alps Electric                   | 3         | 0.67%   |
| Realtek                         | 2         | 0.45%   |
| MediaTek                        | 1         | 0.22%   |
| ASUSTek Computer                | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 62        | 13.93%  |
| Realtek  Bluetooth 4.2 Adapter                              | 45        | 10.11%  |
| Realtek Bluetooth Radio                                     | 28        | 6.29%   |
| IMC Networks Bluetooth Radio                                | 28        | 6.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 27        | 6.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 25        | 5.62%   |
| Qualcomm Atheros  Bluetooth Device                          | 21        | 4.72%   |
| Intel AX200 Bluetooth                                       | 19        | 4.27%   |
| Intel Bluetooth Device                                      | 18        | 4.04%   |
| IMC Networks Bluetooth Device                               | 18        | 4.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 11        | 2.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 9         | 2.02%   |
| Ralink RT3290 Bluetooth                                     | 7         | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 7         | 1.57%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 6         | 1.35%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                | 6         | 1.35%   |
| Apple Bluetooth USB Host Controller                         | 6         | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 5         | 1.12%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 4         | 0.9%    |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 4         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                          | 4         | 0.9%    |
| Apple Bluetooth Host Controller                             | 4         | 0.9%    |
| Realtek RTL8821A Bluetooth                                  | 3         | 0.67%   |
| Lite-On Bluetooth Device                                    | 3         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 0.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 0.67%   |
| Foxconn International BCM43142A0 Bluetooth module           | 3         | 0.67%   |
| Broadcom BCM20702A0                                         | 3         | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 0.67%   |
| Alps Electric BCM2046 Bluetooth Device                      | 3         | 0.67%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 0.45%   |
| Realtek Bluetooth Radio                                     | 2         | 0.45%   |
| Lite-On Bluetooth Radio                                     | 2         | 0.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 0.45%   |
| IMC Networks Wireless_Device                                | 2         | 0.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 2         | 0.45%   |
| Dell Wireless 360 Bluetooth                                 | 2         | 0.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 0.45%   |
| Broadcom BCM20703A1 Bluetooth 4.1 + LE                      | 2         | 0.45%   |
| Apple Bluetooth HCI                                         | 2         | 0.45%   |
| Toshiba RT Bluetooth Radio                                  | 1         | 0.22%   |
| Toshiba Bluetooth Device                                    | 1         | 0.22%   |
| Toshiba BCM43142A0                                          | 1         | 0.22%   |
| Toshiba Askey Bluetooth Module                              | 1         | 0.22%   |
| Realtek CSR BS8510                                          | 1         | 0.22%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.22%   |
| MediaTek Wireless_Device                                    | 1         | 0.22%   |
| Lite-On BCM20702A0                                          | 1         | 0.22%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.22%   |
| Intel AX210 Bluetooth                                       | 1         | 0.22%   |
| IMC Networks Bluetooth USB Host Controller                  | 1         | 0.22%   |
| IMC Networks Bluetooth                                      | 1         | 0.22%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.22%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.22%   |
| Foxconn / Hon Hai BT                                        | 1         | 0.22%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.22%   |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 457       | 54.8%   |
| AMD                         | 228       | 27.34%  |
| Nvidia                      | 101       | 12.11%  |
| VIA Technologies            | 6         | 0.72%   |
| C-Media Electronics         | 6         | 0.72%   |
| JMTek                       | 4         | 0.48%   |
| Realtek Semiconductor       | 3         | 0.36%   |
| Logitech                    | 3         | 0.36%   |
| Creative Labs               | 3         | 0.36%   |
| Texas Instruments           | 2         | 0.24%   |
| Plantronics                 | 2         | 0.24%   |
| M-Audio                     | 2         | 0.24%   |
| Generalplus Technology      | 2         | 0.24%   |
| Turtle Beach                | 1         | 0.12%   |
| SteelSeries ApS             | 1         | 0.12%   |
| Sennheiser Communications   | 1         | 0.12%   |
| OLKB                        | 1         | 0.12%   |
| Microsoft                   | 1         | 0.12%   |
| Kingston Technology         | 1         | 0.12%   |
| Earth Computer Technologies | 1         | 0.12%   |
| Creative Technology         | 1         | 0.12%   |
| Corsair                     | 1         | 0.12%   |
| Cirrus Logic                | 1         | 0.12%   |
| Blue Microphones            | 1         | 0.12%   |
| BEHRINGER International     | 1         | 0.12%   |
| Avid Technology             | 1         | 0.12%   |
| Astro Gaming                | 1         | 0.12%   |
| Apple                       | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 74        | 6.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 70        | 6.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 51        | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 49        | 4.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 46        | 4.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 40        | 3.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 34        | 3.2%    |
| AMD FCH Azalia Controller                                                                         | 34        | 3.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 31        | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 30        | 2.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 29        | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 2.54%   |
| AMD High Definition Audio Controller                                                              | 26        | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 1.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 1.7%    |
| Intel 8 Series HD Audio Controller                                                                | 17        | 1.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 1.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 1.04%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 9         | 0.85%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 8         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.57%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.57%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 5         | 0.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.47%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.47%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.38%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.38%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 4         | 0.38%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.38%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 0.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 0.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 0.38%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.28%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.28%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 24.65%  |
| SK hynix            | 64        | 17.73%  |
| Micron Technology   | 45        | 12.47%  |
| Unknown             | 35        | 9.7%    |
| Kingston            | 24        | 6.65%   |
| A-DATA Technology   | 21        | 5.82%   |
| Corsair             | 13        | 3.6%    |
| Crucial             | 12        | 3.32%   |
| Ramaxel Technology  | 9         | 2.49%   |
| Elpida              | 6         | 1.66%   |
| Avant               | 5         | 1.39%   |
| G.Skill             | 4         | 1.11%   |
| Team                | 3         | 0.83%   |
| Super Talent        | 3         | 0.83%   |
| Nanya Technology    | 3         | 0.83%   |
| GeIL                | 3         | 0.83%   |
| Apacer              | 3         | 0.83%   |
| PNY                 | 2         | 0.55%   |
| Patriot             | 2         | 0.55%   |
| Kreton              | 2         | 0.55%   |
| Hewlett-Packard     | 2         | 0.55%   |
| Unknown (08AE)      | 1         | 0.28%   |
| Unigen              | 1         | 0.28%   |
| Transcend           | 1         | 0.28%   |
| Sesame              | 1         | 0.28%   |
| Qimonda             | 1         | 0.28%   |
| PUSKILL             | 1         | 0.28%   |
| Goldkey             | 1         | 0.28%   |
| ChangXin Memory     | 1         | 0.28%   |
| Centon              | 1         | 0.28%   |
| ASint Technology    | 1         | 0.28%   |
| Unknown             | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 8         | 2.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 7         | 1.84%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 7         | 1.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 6         | 1.58%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 5         | 1.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 5         | 1.32%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 4         | 1.05%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 4         | 1.05%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s          | 3         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 3         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 3         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 0.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 3         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.79%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s          | 3         | 0.79%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 3         | 0.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 2         | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 0.53%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.53%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 2         | 0.53%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 2         | 0.53%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 2         | 0.53%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 2         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 2         | 0.53%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s       | 2         | 0.53%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s          | 2         | 0.53%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s            | 2         | 0.53%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 2         | 0.53%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.53%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 2         | 0.53%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s       | 2         | 0.53%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.53%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s | 2         | 0.53%   |
| Micron RAM 4KTF25664HZ-1G9P1 2GB SODIMM DDR3 1776MT/s          | 2         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 0.53%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 2         | 0.53%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM DDR3 1600MT/s             | 2         | 0.53%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 800MT/s            | 2         | 0.53%   |
| Apacer RAM 76.A302G.D330B 2GB SODIMM DDR4 2400MT/s             | 2         | 0.53%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.53%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 2         | 0.53%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                    | 2         | 0.53%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 2666MT/s                | 2         | 0.53%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.26%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                      | 1         | 0.26%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 1         | 0.26%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 1         | 0.26%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 1         | 0.26%   |
| Unknown RAM Module 512MB SODIMM DRAM 533MT/s                   | 1         | 0.26%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 0.26%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                  | 1         | 0.26%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 130       | 45.45%  |
| DDR3    | 103       | 36.01%  |
| DDR2    | 17        | 5.94%   |
| SDRAM   | 13        | 4.55%   |
| LPDDR4  | 9         | 3.15%   |
| Unknown | 7         | 2.45%   |
| LPDDR3  | 4         | 1.4%    |
| DRAM    | 2         | 0.7%    |
| DDR     | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 190       | 67.62%  |
| DIMM         | 80        | 28.47%  |
| Row Of Chips | 11        | 3.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 129       | 39.21%  |
| 8192  | 98        | 29.79%  |
| 2048  | 49        | 14.89%  |
| 16384 | 28        | 8.51%   |
| 1024  | 15        | 4.56%   |
| 32768 | 7         | 2.13%   |
| 512   | 2         | 0.61%   |
| 128   | 1         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 71        | 22.83%  |
| 2667    | 61        | 19.61%  |
| 3200    | 30        | 9.65%   |
| 2400    | 23        | 7.4%    |
| 1333    | 21        | 6.75%   |
| 2133    | 14        | 4.5%    |
| Unknown | 13        | 4.18%   |
| 1334    | 11        | 3.54%   |
| 3266    | 8         | 2.57%   |
| 800     | 7         | 2.25%   |
| 3600    | 5         | 1.61%   |
| 1067    | 5         | 1.61%   |
| 667     | 5         | 1.61%   |
| 4267    | 4         | 1.29%   |
| 4199    | 3         | 0.96%   |
| 3000    | 3         | 0.96%   |
| 2666    | 3         | 0.96%   |
| 1867    | 3         | 0.96%   |
| 533     | 3         | 0.96%   |
| 1866    | 2         | 0.64%   |
| 1776    | 2         | 0.64%   |
| 1066    | 2         | 0.64%   |
| 333     | 2         | 0.64%   |
| 4800    | 1         | 0.32%   |
| 4266    | 1         | 0.32%   |
| 3800    | 1         | 0.32%   |
| 3733    | 1         | 0.32%   |
| 3500    | 1         | 0.32%   |
| 3400    | 1         | 0.32%   |
| 2800    | 1         | 0.32%   |
| 2176    | 1         | 0.32%   |
| 975     | 1         | 0.32%   |
| 200     | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 37.5%   |
| Seiko Epson         | 3         | 18.75%  |
| Samsung Electronics | 3         | 18.75%  |
| SAT                 | 1         | 6.25%   |
| Prolific Technology | 1         | 6.25%   |
| Canon               | 1         | 6.25%   |
| Brother Industries  | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w                       | 2         | 12.5%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 6.25%   |
| Seiko Epson L210 Series                                | 1         | 6.25%   |
| Seiko Epson L120 Series                                | 1         | 6.25%   |
| SAT SAT38TUSE                                          | 1         | 6.25%   |
| Samsung ML-2010P Mono Laser Printer                    | 1         | 6.25%   |
| Samsung M2020 Series                                   | 1         | 6.25%   |
| Samsung Composite Device                               | 1         | 6.25%   |
| Prolific PL2305 Parallel Port                          | 1         | 6.25%   |
| HP LaserJet CP 1025                                    | 1         | 6.25%   |
| HP LaserJet 1020                                       | 1         | 6.25%   |
| HP Laser 107a                                          | 1         | 6.25%   |
| HP Deskjet 2540 series                                 | 1         | 6.25%   |
| Canon G3000 series                                     | 1         | 6.25%   |
| Brother DCP-T710W                                      | 1         | 6.25%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 104       | 20.31%  |
| IMC Networks                           | 91        | 17.77%  |
| Realtek Semiconductor                  | 37        | 7.23%   |
| Acer                                   | 37        | 7.23%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 6.64%   |
| Microdia                               | 30        | 5.86%   |
| Quanta                                 | 22        | 4.3%    |
| Sunplus Innovation Technology          | 21        | 4.1%    |
| Lite-On Technology                     | 21        | 4.1%    |
| Silicon Motion                         | 14        | 2.73%   |
| Logitech                               | 14        | 2.73%   |
| Syntek                                 | 12        | 2.34%   |
| Suyin                                  | 12        | 2.34%   |
| Apple                                  | 9         | 1.76%   |
| KYE Systems (Mouse Systems)            | 7         | 1.37%   |
| Ricoh                                  | 6         | 1.17%   |
| Alcor Micro                            | 6         | 1.17%   |
| Cubeternet                             | 4         | 0.78%   |
| ALi                                    | 4         | 0.78%   |
| Z-Star Microelectronics                | 3         | 0.59%   |
| Microsoft                              | 3         | 0.59%   |
| Importek                               | 3         | 0.59%   |
| Samsung Electronics                    | 2         | 0.39%   |
| Pixart Imaging                         | 2         | 0.39%   |
| OmniVision Technologies                | 2         | 0.39%   |
| Lenovo                                 | 2         | 0.39%   |
| Huawei Technologies                    | 2         | 0.39%   |
| Arkmicro Technologies                  | 2         | 0.39%   |
| Unknown                                | 1         | 0.2%    |
| Sunplus Technology                     | 1         | 0.2%    |
| Sonix Technology                       | 1         | 0.2%    |
| Genesys Logic                          | 1         | 0.2%    |
| Generalplus Technology                 | 1         | 0.2%    |
| Alcorlink                              | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 42        | 8.2%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 23        | 4.49%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 15        | 2.93%   |
| Chicony Integrated Camera                                      | 12        | 2.34%   |
| Microdia Integrated_Webcam_HD                                  | 11        | 2.15%   |
| Chicony HP TrueVision HD Camera                                | 9         | 1.76%   |
| Acer Integrated Camera                                         | 9         | 1.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 8         | 1.56%   |
| Lite-On HP Webcam                                              | 7         | 1.37%   |
| IMC Networks Integrated Camera                                 | 7         | 1.37%   |
| Chicony Lenovo EasyCamera                                      | 7         | 1.37%   |
| Chicony HP Webcam                                              | 7         | 1.37%   |
| Realtek USB Camera                                             | 6         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 6         | 1.17%   |
| Syntek Integrated Camera                                       | 5         | 0.98%   |
| Lite-On HP Wide Vision HD Camera                               | 5         | 0.98%   |
| Acer Lenovo EasyCamera                                         | 5         | 0.98%   |
| Syntek EasyCamera                                              | 4         | 0.78%   |
| Suyin 1.3M HD WebCam                                           | 4         | 0.78%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 0.78%   |
| Sunplus HD WebCam                                              | 4         | 0.78%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 4         | 0.78%   |
| Realtek HD WebCam                                              | 4         | 0.78%   |
| Quanta HP Webcam                                               | 4         | 0.78%   |
| Lite-On HP HD Camera                                           | 4         | 0.78%   |
| IMC Networks VGA UVC WebCam                                    | 4         | 0.78%   |
| IMC Networks EasyCamera                                        | 4         | 0.78%   |
| Chicony HP High Definition 1MP Webcam                          | 4         | 0.78%   |
| Chicony HD WebCam                                              | 4         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 4         | 0.78%   |
| Acer HD Webcam                                                 | 4         | 0.78%   |
| Acer EasyCamera                                                | 4         | 0.78%   |
| Syntek Lenovo EasyCamera                                       | 3         | 0.59%   |
| Sunplus ASUS Webcam                                            | 3         | 0.59%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 3         | 0.59%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.59%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 0.59%   |
| Realtek HP Truevision HD                                       | 3         | 0.59%   |
| Quanta VGA WebCam                                              | 3         | 0.59%   |
| Quanta HP Wide Vision HD Camera                                | 3         | 0.59%   |
| Quanta HD Webcam                                               | 3         | 0.59%   |
| Microdia Integrated Webcam                                     | 3         | 0.59%   |
| Logitech C922 Pro Stream Webcam                                | 3         | 0.59%   |
| Lite-On Integrated Camera                                      | 3         | 0.59%   |
| Cubeternet GL-UPC822 UVC WebCam                                | 3         | 0.59%   |
| Chicony HP HD Camera                                           | 3         | 0.59%   |
| Chicony EasyCamera                                             | 3         | 0.59%   |
| Chicony CNF9055 Toshiba Webcam                                 | 3         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 3         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 3         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 3         | 0.59%   |
| Apple FaceTime HD Camera (Built-in)                            | 3         | 0.59%   |
| Apple Built-in iSight                                          | 3         | 0.59%   |
| ALi Gateway Webcam                                             | 3         | 0.59%   |
| Z-Star Webcam                                                  | 2         | 0.39%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 2         | 0.39%   |
| Suyin HD WebCam                                                | 2         | 0.39%   |
| Silicon Motion WebCam SC-03FFL11939N                           | 2         | 0.39%   |
| Silicon Motion HP Webcam-50                                    | 2         | 0.39%   |
| Silicon Motion HP Webcam                                       | 2         | 0.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 35.71%  |
| Synaptics                  | 18        | 25.71%  |
| Elan Microelectronics      | 11        | 15.71%  |
| Shenzhen Goodix Technology | 7         | 10%     |
| Upek                       | 4         | 5.71%   |
| LighTuning Technology      | 2         | 2.86%   |
| AuthenTec                  | 2         | 2.86%   |
| STMicroelectronics         | 1         | 1.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 11        | 15.71%  |
| Unknown                                                                    | 8         | 11.43%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.71%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 5.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 5.71%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 4.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.86%   |
| Synaptics  WBDI                                                            | 2         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.43%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.43%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.43%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.43%   |
| Synaptics WBDI Device                                                      | 1         | 1.43%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.43%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.43%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.43%   |
| AuthenTec AES2810                                                          | 1         | 1.43%   |
| AuthenTec AES1600                                                          | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 35.71%  |
| Upek                  | 2         | 14.29%  |
| O2 Micro              | 2         | 14.29%  |
| Lenovo                | 2         | 14.29%  |
| Alcor Micro           | 2         | 14.29%  |
| Gemalto (was Gemplus) | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 4         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 14.29%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                            | 1         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 7.14%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer     | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 479       | 67.28%  |
| 1     | 197       | 27.67%  |
| 2     | 34        | 4.78%   |
| 7     | 1         | 0.14%   |
| 3     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 26.42%  |
| Net/wireless             | 62        | 23.4%   |
| Graphics card            | 52        | 19.62%  |
| Multimedia controller    | 26        | 9.81%   |
| Chipcard                 | 14        | 5.28%   |
| Bluetooth                | 12        | 4.53%   |
| Communication controller | 7         | 2.64%   |
| Sound                    | 5         | 1.89%   |
| Camera                   | 4         | 1.51%   |
| Storage                  | 3         | 1.13%   |
| Card reader              | 3         | 1.13%   |
| Net/ethernet             | 2         | 0.75%   |
| Unassigned class         | 1         | 0.38%   |
| Storage/raid             | 1         | 0.38%   |
| Network                  | 1         | 0.38%   |
| Flash memory             | 1         | 0.38%   |
| Firewire controller      | 1         | 0.38%   |

