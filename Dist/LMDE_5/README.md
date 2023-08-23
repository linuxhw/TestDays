LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 658

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 859C                        | Desktop     | [24dd090f2c](https://linux-hardware.org/?probe=24dd090f2c) | Aug 09, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c86495f999](https://linux-hardware.org/?probe=c86495f999) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7fe1ce642a](https://linux-hardware.org/?probe=7fe1ce642a) | Aug 08, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0cb4da66e3](https://linux-hardware.org/?probe=0cb4da66e3) | Aug 07, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [dbcb2c4a80](https://linux-hardware.org/?probe=dbcb2c4a80) | Aug 07, 2023 |
| Medion        | TJ4125                      | Desktop     | [e35dc275ce](https://linux-hardware.org/?probe=e35dc275ce) | Aug 06, 2023 |
| Medion        | TJ4125                      | Desktop     | [0adec5cb7e](https://linux-hardware.org/?probe=0adec5cb7e) | Aug 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d3df0e8ee1](https://linux-hardware.org/?probe=d3df0e8ee1) | Aug 04, 2023 |
| HP            | Notebook                    | Notebook    | [499fc30d3a](https://linux-hardware.org/?probe=499fc30d3a) | Aug 03, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [37725aaff8](https://linux-hardware.org/?probe=37725aaff8) | Aug 03, 2023 |
| Intel         | X79                         | Desktop     | [051316466a](https://linux-hardware.org/?probe=051316466a) | Aug 01, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1bcc28bd33](https://linux-hardware.org/?probe=1bcc28bd33) | Jul 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [12932af713](https://linux-hardware.org/?probe=12932af713) | Jul 29, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [9d7e65fc0f](https://linux-hardware.org/?probe=9d7e65fc0f) | Jul 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [0882778c0a](https://linux-hardware.org/?probe=0882778c0a) | Jul 28, 2023 |
| Gateway       | NE71B                       | Notebook    | [341f524bc5](https://linux-hardware.org/?probe=341f524bc5) | Jul 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [374c405364](https://linux-hardware.org/?probe=374c405364) | Jul 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [199fe99179](https://linux-hardware.org/?probe=199fe99179) | Jul 25, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7aaa099507](https://linux-hardware.org/?probe=7aaa099507) | Jul 24, 2023 |
| Intel         | X79                         | Desktop     | [8037a9fc0e](https://linux-hardware.org/?probe=8037a9fc0e) | Jul 24, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | Notebook    | [65dfd39fb4](https://linux-hardware.org/?probe=65dfd39fb4) | Jul 21, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | Notebook    | [f7fcf9f782](https://linux-hardware.org/?probe=f7fcf9f782) | Jul 21, 2023 |
| Teclast       | F6 Pro                      | Notebook    | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad W530 2447CN4       | Notebook    | [670e470556](https://linux-hardware.org/?probe=670e470556) | Jul 16, 2023 |
| Dell          | 00F82W A02                  | Desktop     | [53b13b667d](https://linux-hardware.org/?probe=53b13b667d) | Jul 16, 2023 |
| Dell          | 00F82W A02                  | Desktop     | [293fa24c88](https://linux-hardware.org/?probe=293fa24c88) | Jul 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [d63b2efc8b](https://linux-hardware.org/?probe=d63b2efc8b) | Jul 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [88fb5ecc29](https://linux-hardware.org/?probe=88fb5ecc29) | Jul 09, 2023 |
| Medion        | TJ4125                      | Desktop     | [efa563ec1f](https://linux-hardware.org/?probe=efa563ec1f) | Jul 09, 2023 |
| Fujitsu Si... | AMILO Pa 1510               | Notebook    | [b51a760728](https://linux-hardware.org/?probe=b51a760728) | Jul 09, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d660aa6f35](https://linux-hardware.org/?probe=d660aa6f35) | Jul 09, 2023 |
| Lenovo        | ThinkPad X240 20AMS3S919    | Notebook    | [63e13bb1f2](https://linux-hardware.org/?probe=63e13bb1f2) | Jul 08, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [87872596c0](https://linux-hardware.org/?probe=87872596c0) | Jul 08, 2023 |
| Medion        | TJ4125                      | Desktop     | [38d2ffe2de](https://linux-hardware.org/?probe=38d2ffe2de) | Jul 08, 2023 |
| Medion        | TJ4125                      | Desktop     | [1de78b3365](https://linux-hardware.org/?probe=1de78b3365) | Jul 07, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [bdc65d0c9f](https://linux-hardware.org/?probe=bdc65d0c9f) | Jul 05, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [919f65a256](https://linux-hardware.org/?probe=919f65a256) | Jul 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [22a3b2defb](https://linux-hardware.org/?probe=22a3b2defb) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [da20e0f159](https://linux-hardware.org/?probe=da20e0f159) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d8113bbdf6](https://linux-hardware.org/?probe=d8113bbdf6) | Jul 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [8d8748e1dc](https://linux-hardware.org/?probe=8d8748e1dc) | Jul 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [89c111d3ec](https://linux-hardware.org/?probe=89c111d3ec) | Jul 02, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8090e762fe](https://linux-hardware.org/?probe=8090e762fe) | Jul 02, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [d305a15992](https://linux-hardware.org/?probe=d305a15992) | Jul 02, 2023 |
| Medion        | TJ4125                      | Desktop     | [e99bd03d75](https://linux-hardware.org/?probe=e99bd03d75) | Jul 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [729fb2873e](https://linux-hardware.org/?probe=729fb2873e) | Jul 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [633c55d4ba](https://linux-hardware.org/?probe=633c55d4ba) | Jun 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [5cebe0a1d0](https://linux-hardware.org/?probe=5cebe0a1d0) | Jun 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [327794cb1a](https://linux-hardware.org/?probe=327794cb1a) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [95e5472f48](https://linux-hardware.org/?probe=95e5472f48) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4ae6c879aa](https://linux-hardware.org/?probe=4ae6c879aa) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [888133764a](https://linux-hardware.org/?probe=888133764a) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [67a44b0d84](https://linux-hardware.org/?probe=67a44b0d84) | Jun 20, 2023 |
| Intel         | X79                         | Desktop     | [8c50d3b5e8](https://linux-hardware.org/?probe=8c50d3b5e8) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| HP            | Compaq 15                   | Notebook    | [d89a75cb42](https://linux-hardware.org/?probe=d89a75cb42) | Jun 20, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [0173559ed0](https://linux-hardware.org/?probe=0173559ed0) | Jun 19, 2023 |
| Medion        | TJ4125                      | Desktop     | [4c6aec7e33](https://linux-hardware.org/?probe=4c6aec7e33) | Jun 18, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| HP            | Compaq 15                   | Notebook    | [a60f50ade5](https://linux-hardware.org/?probe=a60f50ade5) | Jun 18, 2023 |
| Medion        | E6214                       | Notebook    | [5547ea042f](https://linux-hardware.org/?probe=5547ea042f) | Jun 17, 2023 |
| Medion        | E6214                       | Notebook    | [98ddb6700a](https://linux-hardware.org/?probe=98ddb6700a) | Jun 17, 2023 |
| Medion        | TJ4125                      | Desktop     | [fc102c077c](https://linux-hardware.org/?probe=fc102c077c) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [64da6bc381](https://linux-hardware.org/?probe=64da6bc381) | Jun 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [59b855f1a1](https://linux-hardware.org/?probe=59b855f1a1) | Jun 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [3eb12fd9bc](https://linux-hardware.org/?probe=3eb12fd9bc) | Jun 10, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [56421d7b0f](https://linux-hardware.org/?probe=56421d7b0f) | Jun 09, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| AZW           | GK mini                     | Desktop     | [d9d37cb11a](https://linux-hardware.org/?probe=d9d37cb11a) | Jun 08, 2023 |
| Google        | Lick                        | Notebook    | [d220804cab](https://linux-hardware.org/?probe=d220804cab) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [ac442da472](https://linux-hardware.org/?probe=ac442da472) | Jun 08, 2023 |
| Dell          | G5 5587                     | Notebook    | [909f234c06](https://linux-hardware.org/?probe=909f234c06) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [05a3b3210a](https://linux-hardware.org/?probe=05a3b3210a) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [eeaf6dbd4c](https://linux-hardware.org/?probe=eeaf6dbd4c) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [3faed0102f](https://linux-hardware.org/?probe=3faed0102f) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [81caf6e8cf](https://linux-hardware.org/?probe=81caf6e8cf) | Jun 04, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [e27deb35b8](https://linux-hardware.org/?probe=e27deb35b8) | Jun 03, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [60f94ec7f1](https://linux-hardware.org/?probe=60f94ec7f1) | Jun 03, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [0169222312](https://linux-hardware.org/?probe=0169222312) | Jun 03, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [135ce50995](https://linux-hardware.org/?probe=135ce50995) | Jun 03, 2023 |
| Intel         | B75                         | Desktop     | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Medion        | TJ4125                      | Desktop     | [6244ae0e43](https://linux-hardware.org/?probe=6244ae0e43) | Jun 02, 2023 |
| Unknown       | X99                         | Desktop     | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [c418655a3f](https://linux-hardware.org/?probe=c418655a3f) | Jun 02, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [309f368a92](https://linux-hardware.org/?probe=309f368a92) | Jun 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8f3525a119](https://linux-hardware.org/?probe=8f3525a119) | Jun 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7400ec0f1a](https://linux-hardware.org/?probe=7400ec0f1a) | May 31, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5e7eb5b41c](https://linux-hardware.org/?probe=5e7eb5b41c) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [d38a3af9af](https://linux-hardware.org/?probe=d38a3af9af) | May 27, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [bca0574da6](https://linux-hardware.org/?probe=bca0574da6) | May 27, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2be29f15b4](https://linux-hardware.org/?probe=2be29f15b4) | May 27, 2023 |
| Framework     | Laptop                      | Notebook    | [cdc855ea4c](https://linux-hardware.org/?probe=cdc855ea4c) | May 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bf6e9cf4d0](https://linux-hardware.org/?probe=bf6e9cf4d0) | May 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a3e5c89fe6](https://linux-hardware.org/?probe=a3e5c89fe6) | May 25, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | Notebook    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [9abb9659a8](https://linux-hardware.org/?probe=9abb9659a8) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3c82eec4d2](https://linux-hardware.org/?probe=3c82eec4d2) | May 23, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [04d3c59d2c](https://linux-hardware.org/?probe=04d3c59d2c) | May 22, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ee4eca623f](https://linux-hardware.org/?probe=ee4eca623f) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [49e536226c](https://linux-hardware.org/?probe=49e536226c) | May 19, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [2abefd21ea](https://linux-hardware.org/?probe=2abefd21ea) | May 19, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [feb9ed8589](https://linux-hardware.org/?probe=feb9ed8589) | May 19, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [ce94bc6589](https://linux-hardware.org/?probe=ce94bc6589) | May 18, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [311799f80a](https://linux-hardware.org/?probe=311799f80a) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | Desktop     | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | E2100N                      | Desktop     | [cce0e87f11](https://linux-hardware.org/?probe=cce0e87f11) | May 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [98f104037a](https://linux-hardware.org/?probe=98f104037a) | May 15, 2023 |
| AZW           | MINI S                      | Desktop     | [72c9908514](https://linux-hardware.org/?probe=72c9908514) | May 14, 2023 |
| AZW           | MINI S                      | Desktop     | [788d932e58](https://linux-hardware.org/?probe=788d932e58) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [42db835c47](https://linux-hardware.org/?probe=42db835c47) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3f4eafaf9c](https://linux-hardware.org/?probe=3f4eafaf9c) | May 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [42d9eb5bf8](https://linux-hardware.org/?probe=42d9eb5bf8) | May 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7c946d461d](https://linux-hardware.org/?probe=7c946d461d) | May 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [a0fcafbf70](https://linux-hardware.org/?probe=a0fcafbf70) | May 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [4d7467c0bc](https://linux-hardware.org/?probe=4d7467c0bc) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | Notebook    | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [99c9764b7e](https://linux-hardware.org/?probe=99c9764b7e) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a70e02af94](https://linux-hardware.org/?probe=a70e02af94) | May 09, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| AZW           | SEi                         | Notebook    | [4cd6ab54ba](https://linux-hardware.org/?probe=4cd6ab54ba) | May 08, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7d861acbd6](https://linux-hardware.org/?probe=7d861acbd6) | May 07, 2023 |
| Medion        | TJ4125                      | Desktop     | [583b49089e](https://linux-hardware.org/?probe=583b49089e) | May 07, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [eb82f6baa1](https://linux-hardware.org/?probe=eb82f6baa1) | May 06, 2023 |
| Medion        | E6214                       | Notebook    | [869c63244c](https://linux-hardware.org/?probe=869c63244c) | May 06, 2023 |
| Medion        | E6214                       | Notebook    | [64eeb6e165](https://linux-hardware.org/?probe=64eeb6e165) | May 06, 2023 |
| Medion        | TJ4125                      | Desktop     | [2255946fa5](https://linux-hardware.org/?probe=2255946fa5) | May 05, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c8347acd5d](https://linux-hardware.org/?probe=c8347acd5d) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [fd7043408f](https://linux-hardware.org/?probe=fd7043408f) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ae586408c4](https://linux-hardware.org/?probe=ae586408c4) | May 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Studio 1555                 | Notebook    | [4f9f0dc9bf](https://linux-hardware.org/?probe=4f9f0dc9bf) | May 01, 2023 |
| Lenovo        | 4068AGJ                     | Notebook    | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| HP            | Compaq 15                   | Notebook    | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| ASUSTek       | P7Q57-M DO                  | Desktop     | [897fc61b8c](https://linux-hardware.org/?probe=897fc61b8c) | Apr 30, 2023 |
| ASUSTek       | P7Q57-M DO                  | Desktop     | [4f502dcb59](https://linux-hardware.org/?probe=4f502dcb59) | Apr 30, 2023 |
| Medion        | E6214                       | Notebook    | [7bb9f39d76](https://linux-hardware.org/?probe=7bb9f39d76) | Apr 30, 2023 |
| Medion        | E6214                       | Notebook    | [39747632e6](https://linux-hardware.org/?probe=39747632e6) | Apr 30, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [16279b3c8b](https://linux-hardware.org/?probe=16279b3c8b) | Apr 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [ad46974b2a](https://linux-hardware.org/?probe=ad46974b2a) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | Notebook    | [a27eb72e94](https://linux-hardware.org/?probe=a27eb72e94) | Apr 29, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e5fe9aa407](https://linux-hardware.org/?probe=e5fe9aa407) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [73e11e9235](https://linux-hardware.org/?probe=73e11e9235) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | Notebook    | [f2f50094ba](https://linux-hardware.org/?probe=f2f50094ba) | Apr 28, 2023 |
| Medion        | TJ4125                      | Desktop     | [8f319cff50](https://linux-hardware.org/?probe=8f319cff50) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [6503ed5a4c](https://linux-hardware.org/?probe=6503ed5a4c) | Apr 28, 2023 |
| ASUSTek       | Z550SA                      | Notebook    | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [60d207eb63](https://linux-hardware.org/?probe=60d207eb63) | Apr 27, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [df6b1e8e17](https://linux-hardware.org/?probe=df6b1e8e17) | Apr 26, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [a22605adc9](https://linux-hardware.org/?probe=a22605adc9) | Apr 25, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a3a13c5cb1](https://linux-hardware.org/?probe=a3a13c5cb1) | Apr 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [1d5b5dcfc7](https://linux-hardware.org/?probe=1d5b5dcfc7) | Apr 24, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5827cd2604](https://linux-hardware.org/?probe=5827cd2604) | Apr 23, 2023 |
| Medion        | TJ4125                      | Desktop     | [faa241e4bc](https://linux-hardware.org/?probe=faa241e4bc) | Apr 23, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [93a6cb1a8a](https://linux-hardware.org/?probe=93a6cb1a8a) | Apr 22, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [3f172b49f2](https://linux-hardware.org/?probe=3f172b49f2) | Apr 21, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | Notebook    | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Medion        | E6214                       | Notebook    | [ff06e74c6d](https://linux-hardware.org/?probe=ff06e74c6d) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| Medion        | E6214                       | Notebook    | [ab33cd63b8](https://linux-hardware.org/?probe=ab33cd63b8) | Apr 16, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [c4b35f2a05](https://linux-hardware.org/?probe=c4b35f2a05) | Apr 16, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [12cb955c6f](https://linux-hardware.org/?probe=12cb955c6f) | Apr 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [3bb10a5574](https://linux-hardware.org/?probe=3bb10a5574) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d6f8675bc9](https://linux-hardware.org/?probe=d6f8675bc9) | Apr 11, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [4b50be64da](https://linux-hardware.org/?probe=4b50be64da) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d041ee40cc](https://linux-hardware.org/?probe=d041ee40cc) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [2c83dbd3ef](https://linux-hardware.org/?probe=2c83dbd3ef) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d1e9eaed8b](https://linux-hardware.org/?probe=d1e9eaed8b) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [82a96ca347](https://linux-hardware.org/?probe=82a96ca347) | Apr 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [05aaab32ca](https://linux-hardware.org/?probe=05aaab32ca) | Apr 08, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [816bb7a55c](https://linux-hardware.org/?probe=816bb7a55c) | Apr 06, 2023 |
| Dell          | Precision M4800             | Notebook    | [9283851416](https://linux-hardware.org/?probe=9283851416) | Apr 06, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [3ebdd0188a](https://linux-hardware.org/?probe=3ebdd0188a) | Apr 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4552b7c999](https://linux-hardware.org/?probe=4552b7c999) | Apr 01, 2023 |
| Medion        | E6214                       | Notebook    | [79f326e572](https://linux-hardware.org/?probe=79f326e572) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [b627db43dd](https://linux-hardware.org/?probe=b627db43dd) | Apr 01, 2023 |
| Medion        | E6214                       | Notebook    | [5766389c97](https://linux-hardware.org/?probe=5766389c97) | Apr 01, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Dell          | 00F82W A02                  | Desktop     | [8bf22304e0](https://linux-hardware.org/?probe=8bf22304e0) | Mar 31, 2023 |
| Medion        | E6214                       | Notebook    | [298e2f9c69](https://linux-hardware.org/?probe=298e2f9c69) | Mar 31, 2023 |
| HP            | Pavilion dm4                | Notebook    | [b7f2f9e2ab](https://linux-hardware.org/?probe=b7f2f9e2ab) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3844e429b1](https://linux-hardware.org/?probe=3844e429b1) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9cb1834208](https://linux-hardware.org/?probe=9cb1834208) | Mar 28, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [dd71be113d](https://linux-hardware.org/?probe=dd71be113d) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [6ac9c53a7e](https://linux-hardware.org/?probe=6ac9c53a7e) | Mar 26, 2023 |
| Medion        | E6214                       | Notebook    | [8ff346be04](https://linux-hardware.org/?probe=8ff346be04) | Mar 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8690ae647e](https://linux-hardware.org/?probe=8690ae647e) | Mar 26, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [ce4febfe16](https://linux-hardware.org/?probe=ce4febfe16) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [083feb0355](https://linux-hardware.org/?probe=083feb0355) | Mar 25, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| Star Labs     | StarBook                    | Notebook    | [b3957ad08f](https://linux-hardware.org/?probe=b3957ad08f) | Mar 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [79104099a5](https://linux-hardware.org/?probe=79104099a5) | Mar 20, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [fb5c67c585](https://linux-hardware.org/?probe=fb5c67c585) | Mar 19, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7051e25dc0](https://linux-hardware.org/?probe=7051e25dc0) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| ASRock        | B365M Pro4                  | Desktop     | [e237668eb2](https://linux-hardware.org/?probe=e237668eb2) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [29f50579db](https://linux-hardware.org/?probe=29f50579db) | Mar 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bf2b5490ba](https://linux-hardware.org/?probe=bf2b5490ba) | Mar 15, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [b410a4c017](https://linux-hardware.org/?probe=b410a4c017) | Mar 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | Notebook    | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| Gigabyte      | Z87X-OC Force-CF            | Desktop     | [17deac9c67](https://linux-hardware.org/?probe=17deac9c67) | Mar 12, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [22dd14abae](https://linux-hardware.org/?probe=22dd14abae) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| MSI           | 970A-G46                    | Desktop     | [8c3d20fa95](https://linux-hardware.org/?probe=8c3d20fa95) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z61m 9450HAG       | Notebook    | [5aa66edd35](https://linux-hardware.org/?probe=5aa66edd35) | Mar 04, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [fddb284e37](https://linux-hardware.org/?probe=fddb284e37) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| HIPER         | WORKBOOK                    | Notebook    | [85085220c9](https://linux-hardware.org/?probe=85085220c9) | Mar 01, 2023 |
| Supermicro    | X10SAE                      | Server      | [fff44d7132](https://linux-hardware.org/?probe=fff44d7132) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| Supermicro    | X10SAE                      | Server      | [b968ea6172](https://linux-hardware.org/?probe=b968ea6172) | Feb 25, 2023 |
| HP            | 2000                        | Notebook    | [2e234233cc](https://linux-hardware.org/?probe=2e234233cc) | Feb 25, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| Dell          | 0NK70N A03                  | Desktop     | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| itel Mobil... | SPIRIT 2                    | Notebook    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [392442adfb](https://linux-hardware.org/?probe=392442adfb) | Feb 16, 2023 |
| Dell          | 0MF24N A03                  | Desktop     | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [861c0d497e](https://linux-hardware.org/?probe=861c0d497e) | Feb 12, 2023 |
| Compaq        | 420                         | Notebook    | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [b8854f5844](https://linux-hardware.org/?probe=b8854f5844) | Feb 12, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| Star Labs     | StarBook                    | Notebook    | [08e31c8ad5](https://linux-hardware.org/?probe=08e31c8ad5) | Feb 10, 2023 |
| HP            | 843C                        | Desktop     | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Dell          | Precision M4800             | Notebook    | [3f97bef125](https://linux-hardware.org/?probe=3f97bef125) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| TUXEDO        | N8xxEZ                      | Notebook    | [680bdf5ada](https://linux-hardware.org/?probe=680bdf5ada) | Feb 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| Google        | Candy                       | Notebook    | [2b2368d61b](https://linux-hardware.org/?probe=2b2368d61b) | Jan 28, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Intel         | H61M-DS2V                   | Desktop     | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| Compaq        | 420                         | Notebook    | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | Desktop     | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Dell          | 0C27VV A01                  | Desktop     | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [d1a0c1ddf7](https://linux-hardware.org/?probe=d1a0c1ddf7) | Jan 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [f2b0c15a6d](https://linux-hardware.org/?probe=f2b0c15a6d) | Jan 22, 2023 |
| Dell          | Precision 5520              | Notebook    | [c202a2fa19](https://linux-hardware.org/?probe=c202a2fa19) | Jan 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| Fujitsu       | M2010                       | Notebook    | [dec6151200](https://linux-hardware.org/?probe=dec6151200) | Jan 20, 2023 |
| Toshiba       | PORTEGE M780                | Notebook    | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Google        | Candy                       | Notebook    | [f1609bed25](https://linux-hardware.org/?probe=f1609bed25) | Jan 16, 2023 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | B560                        | Notebook    | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel         | B75                         | Desktop     | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [96cf85d764](https://linux-hardware.org/?probe=96cf85d764) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [66199c3f54](https://linux-hardware.org/?probe=66199c3f54) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fb967bb48d](https://linux-hardware.org/?probe=fb967bb48d) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Google        | Ultima                      | Notebook    | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | Notebook    | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | Notebook    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | Notebook    | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [5a75bbfc48](https://linux-hardware.org/?probe=5a75bbfc48) | Dec 09, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | 8299                        | Desktop     | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | Notebook    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | Notebook    | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | Notebook    | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Dell          | 0N826N A03                  | Desktop     | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [8d633d6712](https://linux-hardware.org/?probe=8d633d6712) | Nov 05, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [d23c74b1f2](https://linux-hardware.org/?probe=d23c74b1f2) | Nov 05, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| HP            | 8299                        | Desktop     | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| Dell          | XPS L701X                   | Notebook    | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| HP            | 8299                        | Desktop     | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| AZW           | MINI S                      | Desktop     | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ff09bb4e1](https://linux-hardware.org/?probe=8ff09bb4e1) | Sep 22, 2022 |
| Gateway       | DX4870                      | Desktop     | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Medion        | P15648                      | Notebook    | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| Dell          | 0XC837                      | Desktop     | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [df362e9796](https://linux-hardware.org/?probe=df362e9796) | Sep 18, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [a251261add](https://linux-hardware.org/?probe=a251261add) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | Notebook    | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | Desktop     | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | Desktop     | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | Desktop     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| MSI           | B85I                        | Desktop     | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Microtech     | ebookPro                    | Notebook    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Framework     | Laptop                      | Notebook    | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | Notebook    | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | Notebook    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | Notebook    | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| AMI           | T3 MRD                      | Notebook    | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | Notebook    | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | Notebook    | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| Multilaser    | PC150                       | Notebook    | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | Notebook    | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | Notebook    | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | Notebook    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE_5/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-21-amd64          | 73        | 16.44%  |
| 5.10.0-12-amd64          | 60        | 13.51%  |
| 5.10.0-23-amd64          | 50        | 11.26%  |
| 5.10.0-19-amd64          | 37        | 8.33%   |
| 5.10.0-14-amd64          | 30        | 6.76%   |
| 5.10.0-20-amd64          | 29        | 6.53%   |
| 5.10.0-13-amd64          | 27        | 6.08%   |
| 5.10.0-18-amd64          | 25        | 5.63%   |
| 5.10.0-17-amd64          | 21        | 4.73%   |
| 5.10.0-15-amd64          | 19        | 4.28%   |
| 5.10.0-16-amd64          | 14        | 3.15%   |
| 5.10.0-22-amd64          | 13        | 2.93%   |
| 5.10.0-13-686            | 6         | 1.35%   |
| 6.1.0-0.deb11.7-amd64    | 4         | 0.9%    |
| 5.18.0-0.bpo.1-amd64     | 4         | 0.9%    |
| 5.16.0-0.bpo.4-amd64     | 4         | 0.9%    |
| 5.19.0-0.deb11.2-amd64   | 3         | 0.68%   |
| 6.1.0-0.deb11.6-amd64    | 2         | 0.45%   |
| 6.1.0-0.deb11.5-amd64    | 2         | 0.45%   |
| 5.10.0-12-686            | 2         | 0.45%   |
| 6.1.11-x64v1-xanmod1     | 1         | 0.23%   |
| 6.1.0-0.deb11.6-rt-amd64 | 1         | 0.23%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1         | 0.23%   |
| 6.0.0-0.deb11.2-amd64    | 1         | 0.23%   |
| 5.19.10-xanmod1          | 1         | 0.23%   |
| 5.18.0-4-amd64           | 1         | 0.23%   |
| 5.18.0-3-amd64           | 1         | 0.23%   |
| 5.16.0-0.bpo.3-amd64     | 1         | 0.23%   |
| 5.15.78-xanmod1          | 1         | 0.23%   |
| 5.15.70-xanmod1          | 1         | 0.23%   |
| 5.15.0-0.bpo.3-amd64     | 1         | 0.23%   |
| 5.10.0-22-686            | 1         | 0.23%   |
| 5.10.0-21-686            | 1         | 0.23%   |
| 5.10.0-20-686            | 1         | 0.23%   |
| 5.10.0-19-686            | 1         | 0.23%   |
| 5.10.0-17-686            | 1         | 0.23%   |
| 5.10.0-14-686            | 1         | 0.23%   |
| 5.10.0-11-686            | 1         | 0.23%   |
| 4.19.0-23-amd64          | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 378       | 92.65%  |
| 6.1.0   | 9         | 2.21%   |
| 5.18.0  | 6         | 1.47%   |
| 5.16.0  | 4         | 0.98%   |
| 5.19.0  | 3         | 0.74%   |
| 6.1.11  | 1         | 0.25%   |
| 6.0.2   | 1         | 0.25%   |
| 6.0.0   | 1         | 0.25%   |
| 5.19.10 | 1         | 0.25%   |
| 5.15.78 | 1         | 0.25%   |
| 5.15.70 | 1         | 0.25%   |
| 5.15.0  | 1         | 0.25%   |
| 4.19.0  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 378       | 92.87%  |
| 6.1     | 10        | 2.46%   |
| 5.18    | 6         | 1.47%   |
| 5.19    | 4         | 0.98%   |
| 5.16    | 4         | 0.98%   |
| 6.0     | 2         | 0.49%   |
| 5.15    | 2         | 0.49%   |
| 4.19    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 386       | 96.26%  |
| i686   | 15        | 3.74%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 346       | 85.43%  |
| Cinnamon   | 45        | 11.11%  |
| MATE       | 6         | 1.48%   |
| XFCE       | 2         | 0.49%   |
| KDE5       | 1         | 0.25%   |
| KDE        | 1         | 0.25%   |
| i3         | 1         | 0.25%   |
| GNOME      | 1         | 0.25%   |
| awesome    | 1         | 0.25%   |
| Unknown    | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 401       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 241       | 59.65%  |
| LightDM | 160       | 39.6%   |
| SDDM    | 2         | 0.5%    |
| GDM     | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 142       | 35.24%  |
| de_DE | 56        | 13.9%   |
| ru_RU | 34        | 8.44%   |
| pt_BR | 28        | 6.95%   |
| en_GB | 22        | 5.46%   |
| fr_FR | 17        | 4.22%   |
| it_IT | 15        | 3.72%   |
| pl_PL | 11        | 2.73%   |
| es_ES | 10        | 2.48%   |
| es_MX | 4         | 0.99%   |
| en_CA | 4         | 0.99%   |
| sv_SE | 3         | 0.74%   |
| fr_CA | 3         | 0.74%   |
| es_BO | 3         | 0.74%   |
| el_GR | 3         | 0.74%   |
| cs_CZ | 3         | 0.74%   |
| tr_TR | 2         | 0.5%    |
| ru_UA | 2         | 0.5%    |
| pt_PT | 2         | 0.5%    |
| ko_KR | 2         | 0.5%    |
| fr_BE | 2         | 0.5%    |
| es_AR | 2         | 0.5%    |
| en_NZ | 2         | 0.5%    |
| en_IE | 2         | 0.5%    |
| en_AU | 2         | 0.5%    |
| de_AT | 2         | 0.5%    |
| da_DK | 2         | 0.5%    |
| zh_CN | 1         | 0.25%   |
| sl_SI | 1         | 0.25%   |
| sk_SK | 1         | 0.25%   |
| nn_NO | 1         | 0.25%   |
| nl_AW | 1         | 0.25%   |
| ja_JP | 1         | 0.25%   |
| it_CH | 1         | 0.25%   |
| hu_HU | 1         | 0.25%   |
| fi_FI | 1         | 0.25%   |
| es_VE | 1         | 0.25%   |
| es_PE | 1         | 0.25%   |
| es_PA | 1         | 0.25%   |
| es_NI | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 244       | 60.7%   |
| BIOS | 158       | 39.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 365       | 90.8%   |
| Overlay | 15        | 3.73%   |
| Tmpfs   | 10        | 2.49%   |
| Btrfs   | 9         | 2.24%   |
| Xfs     | 3         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 241       | 59.65%  |
| GPT     | 115       | 28.47%  |
| MBR     | 48        | 11.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 367       | 91.07%  |
| Yes       | 36        | 8.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 345       | 85.61%  |
| Yes       | 58        | 14.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 63        | 15.71%  |
| Lenovo              | 60        | 14.96%  |
| Dell                | 50        | 12.47%  |
| ASUSTek Computer    | 45        | 11.22%  |
| Acer                | 28        | 6.98%   |
| Gigabyte Technology | 23        | 5.74%   |
| MSI                 | 17        | 4.24%   |
| Apple               | 14        | 3.49%   |
| Toshiba             | 10        | 2.49%   |
| ASRock              | 9         | 2.24%   |
| Intel               | 7         | 1.75%   |
| Medion              | 5         | 1.25%   |
| Fujitsu             | 5         | 1.25%   |
| AZW                 | 5         | 1.25%   |
| Samsung Electronics | 4         | 1%      |
| Google              | 4         | 1%      |
| Unknown             | 4         | 1%      |
| Sony                | 3         | 0.75%   |
| Star Labs           | 2         | 0.5%    |
| Packard Bell        | 2         | 0.5%    |
| GPU Company         | 2         | 0.5%    |
| Gateway             | 2         | 0.5%    |
| Fujitsu Siemens     | 2         | 0.5%    |
| Compaq              | 2         | 0.5%    |
| Alienware           | 2         | 0.5%    |
| Wortmann AG         | 1         | 0.25%   |
| TUXEDO              | 1         | 0.25%   |
| Timi                | 1         | 0.25%   |
| Teclast             | 1         | 0.25%   |
| Supermicro          | 1         | 0.25%   |
| STONE COMPUTERS     | 1         | 0.25%   |
| SiYW                | 1         | 0.25%   |
| Philco              | 1         | 0.25%   |
| Pegatron            | 1         | 0.25%   |
| Panasonic           | 1         | 0.25%   |
| Multilaser          | 1         | 0.25%   |
| Microtech           | 1         | 0.25%   |
| LincPlus            | 1         | 0.25%   |
| LG Electronics      | 1         | 0.25%   |
| Kruger&Matz         | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 6         | 1.5%    |
| Star Labs StarBook             | 2         | 0.5%    |
| MSI MS-7B79                    | 2         | 0.5%    |
| Lenovo IdeaPad 3 15ITL6 82H8   | 2         | 0.5%    |
| Lenovo IdeaPad 3 15ADA05 81W1  | 2         | 0.5%    |
| Lenovo G500 20236              | 2         | 0.5%    |
| Intel B75                      | 2         | 0.5%    |
| HP Pavilion Notebook           | 2         | 0.5%    |
| HP Pavilion dv6                | 2         | 0.5%    |
| HP Notebook                    | 2         | 0.5%    |
| HP Laptop 15z-ef2xxx           | 2         | 0.5%    |
| HP Laptop 15-dw3xxx            | 2         | 0.5%    |
| HP 250 G8 Notebook PC          | 2         | 0.5%    |
| HP 250 G7 Notebook PC          | 2         | 0.5%    |
| Gigabyte B450 AORUS M          | 2         | 0.5%    |
| Dell Latitude E6400            | 2         | 0.5%    |
| Dell Latitude E5540            | 2         | 0.5%    |
| Compaq 420                     | 2         | 0.5%    |
| AZW MINI S                     | 2         | 0.5%    |
| ASUS ROG STRIX B450-F GAMING   | 2         | 0.5%    |
| ASUS PRIME B350M-A             | 2         | 0.5%    |
| ASUS PRIME A320M-K             | 2         | 0.5%    |
| Apple MacBookPro11,1           | 2         | 0.5%    |
| Apple iMac7,1                  | 2         | 0.5%    |
| Acer Aspire E1-570G            | 2         | 0.5%    |
| Acer Aspire 7745G              | 2         | 0.5%    |
| Acer Aspire 5930               | 2         | 0.5%    |
| Wortmann AG TERRA_MOBILE_1713A | 1         | 0.25%   |
| TUXEDO N8xxEZ                  | 1         | 0.25%   |
| Toshiba Satellite Pro A50-C    | 1         | 0.25%   |
| Toshiba Satellite M55          | 1         | 0.25%   |
| Toshiba Satellite L855D        | 1         | 0.25%   |
| Toshiba Satellite L455         | 1         | 0.25%   |
| Toshiba Satellite L305         | 1         | 0.25%   |
| Toshiba Satellite L300D        | 1         | 0.25%   |
| Toshiba Satellite L300         | 1         | 0.25%   |
| Toshiba Satellite C850-D8K     | 1         | 0.25%   |
| Toshiba PORTEGE Z30-B          | 1         | 0.25%   |
| Toshiba PORTEGE M780           | 1         | 0.25%   |
| Timi RedmiBook 14-APCS         | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 25        | 6.23%   |
| Acer Aspire           | 23        | 5.74%   |
| Dell Latitude         | 13        | 3.24%   |
| Lenovo IdeaPad        | 12        | 2.99%   |
| HP Laptop             | 12        | 2.99%   |
| Dell Inspiron         | 11        | 2.74%   |
| HP Pavilion           | 10        | 2.49%   |
| Toshiba Satellite     | 8         | 2%      |
| Dell Precision        | 8         | 2%      |
| ASUS PRIME            | 8         | 2%      |
| HP EliteBook          | 7         | 1.75%   |
| ASUS VivoBook         | 6         | 1.5%    |
| ASUS ROG              | 6         | 1.5%    |
| Unknown               | 6         | 1.5%    |
| Dell Vostro           | 5         | 1.25%   |
| Dell OptiPlex         | 5         | 1.25%   |
| HP ProBook            | 4         | 1%      |
| HP Compaq             | 4         | 1%      |
| HP 250                | 4         | 1%      |
| HP ZBook              | 3         | 0.75%   |
| Gigabyte B450M        | 3         | 0.75%   |
| Gigabyte B450         | 3         | 0.75%   |
| Dell XPS              | 3         | 0.75%   |
| Toshiba PORTEGE       | 2         | 0.5%    |
| Star Labs StarBook    | 2         | 0.5%    |
| MSI MS-7B79           | 2         | 0.5%    |
| Lenovo Yoga           | 2         | 0.5%    |
| Lenovo ThinkCentre    | 2         | 0.5%    |
| Lenovo ThinkBook      | 2         | 0.5%    |
| Lenovo Legion         | 2         | 0.5%    |
| Lenovo IdeaPadFlex    | 2         | 0.5%    |
| Lenovo G500           | 2         | 0.5%    |
| Intel B75             | 2         | 0.5%    |
| HP Notebook           | 2         | 0.5%    |
| HP 255                | 2         | 0.5%    |
| Gigabyte A520M        | 2         | 0.5%    |
| Fujitsu Siemens AMILO | 2         | 0.5%    |
| Fujitsu LIFEBOOK      | 2         | 0.5%    |
| Compaq 420            | 2         | 0.5%    |
| AZW MINI              | 2         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 43        | 10.72%  |
| 2018 | 41        | 10.22%  |
| 2020 | 34        | 8.48%   |
| 2012 | 34        | 8.48%   |
| 2013 | 28        | 6.98%   |
| 2017 | 26        | 6.48%   |
| 2010 | 25        | 6.23%   |
| 2019 | 24        | 5.99%   |
| 2016 | 21        | 5.24%   |
| 2022 | 19        | 4.74%   |
| 2015 | 18        | 4.49%   |
| 2009 | 18        | 4.49%   |
| 2011 | 17        | 4.24%   |
| 2014 | 15        | 3.74%   |
| 2008 | 14        | 3.49%   |
| 2007 | 11        | 2.74%   |
| 2006 | 9         | 2.24%   |
| 2023 | 4         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 250       | 62.34%  |
| Desktop     | 129       | 32.17%  |
| Convertible | 8         | 2%      |
| All in one  | 6         | 1.5%    |
| Mini pc     | 4         | 1%      |
| Tablet      | 3         | 0.75%   |
| Server      | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 371       | 91.83%  |
| Enabled  | 33        | 8.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 394       | 98.25%  |
| Yes  | 7         | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 103       | 25.37%  |
| 3.01-4.0        | 80        | 19.7%   |
| 16.01-24.0      | 74        | 18.23%  |
| 8.01-16.0       | 65        | 16.01%  |
| 32.01-64.0      | 37        | 9.11%   |
| 1.01-2.0        | 19        | 4.68%   |
| 2.01-3.0        | 12        | 2.96%   |
| 64.01-256.0     | 7         | 1.72%   |
| 24.01-32.0      | 6         | 1.48%   |
| 0.51-1.0        | 2         | 0.49%   |
| More than 256.0 | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 171       | 39.68%  |
| 2.01-3.0   | 135       | 31.32%  |
| 3.01-4.0   | 49        | 11.37%  |
| 4.01-8.0   | 43        | 9.98%   |
| 0.51-1.0   | 22        | 5.1%    |
| 8.01-16.0  | 6         | 1.39%   |
| 24.01-32.0 | 2         | 0.46%   |
| 16.01-24.0 | 2         | 0.46%   |
| 32.01-64.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 260       | 63.57%  |
| 2      | 88        | 21.52%  |
| 3      | 30        | 7.33%   |
| 4      | 14        | 3.42%   |
| 5      | 9         | 2.2%    |
| 6      | 5         | 1.22%   |
| 0      | 2         | 0.49%   |
| 7      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 263       | 65.26%  |
| Yes       | 140       | 34.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 337       | 84.04%  |
| No        | 64        | 15.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 332       | 82.38%  |
| No        | 71        | 17.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 58.21%  |
| No        | 168       | 41.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 79        | 19.55%  |
| Germany      | 64        | 15.84%  |
| Russia       | 37        | 9.16%   |
| Brazil       | 29        | 7.18%   |
| Italy        | 24        | 5.94%   |
| France       | 19        | 4.7%    |
| UK           | 16        | 3.96%   |
| Poland       | 13        | 3.22%   |
| Spain        | 12        | 2.97%   |
| Canada       | 11        | 2.72%   |
| Sweden       | 6         | 1.49%   |
| Mexico       | 6         | 1.49%   |
| Australia    | 5         | 1.24%   |
| Bolivia      | 4         | 0.99%   |
| Belgium      | 4         | 0.99%   |
| Belarus      | 4         | 0.99%   |
| Turkey       | 3         | 0.74%   |
| Portugal     | 3         | 0.74%   |
| Greece       | 3         | 0.74%   |
| Chile        | 3         | 0.74%   |
| Austria      | 3         | 0.74%   |
| Vietnam      | 2         | 0.5%    |
| Venezuela    | 2         | 0.5%    |
| Ukraine      | 2         | 0.5%    |
| South Korea  | 2         | 0.5%    |
| South Africa | 2         | 0.5%    |
| Slovenia     | 2         | 0.5%    |
| Romania      | 2         | 0.5%    |
| Peru         | 2         | 0.5%    |
| Paraguay     | 2         | 0.5%    |
| New Zealand  | 2         | 0.5%    |
| Netherlands  | 2         | 0.5%    |
| Kazakhstan   | 2         | 0.5%    |
| Japan        | 2         | 0.5%    |
| Indonesia    | 2         | 0.5%    |
| Hungary      | 2         | 0.5%    |
| Finland      | 2         | 0.5%    |
| Denmark      | 2         | 0.5%    |
| Czechia      | 2         | 0.5%    |
| Argentina    | 2         | 0.5%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Berlin               | 9         | 2.14%   |
| Moscow               | 8         | 1.9%    |
| St Petersburg        | 4         | 0.95%   |
| Rome                 | 4         | 0.95%   |
| Munich               | 4         | 0.95%   |
| Madrid               | 4         | 0.95%   |
| Krakow               | 4         | 0.95%   |
| Delligsen            | 4         | 0.95%   |
| Rio de Janeiro       | 3         | 0.71%   |
| Oruro                | 3         | 0.71%   |
| Montreal             | 3         | 0.71%   |
| Milan                | 3         | 0.71%   |
| Miami                | 3         | 0.71%   |
| Frankfurt am Main    | 3         | 0.71%   |
| Belém               | 3         | 0.71%   |
| Vancouver            | 2         | 0.48%   |
| Toronto              | 2         | 0.48%   |
| Santiago             | 2         | 0.48%   |
| San Jose             | 2         | 0.48%   |
| Parma                | 2         | 0.48%   |
| New York             | 2         | 0.48%   |
| Neasden              | 2         | 0.48%   |
| Nashville            | 2         | 0.48%   |
| Mogi das Cruzes      | 2         | 0.48%   |
| Melbourne            | 2         | 0.48%   |
| Malmo                | 2         | 0.48%   |
| London               | 2         | 0.48%   |
| Lisbon               | 2         | 0.48%   |
| Lima                 | 2         | 0.48%   |
| Lamspringe           | 2         | 0.48%   |
| Krefeld              | 2         | 0.48%   |
| Jakarta              | 2         | 0.48%   |
| Hamburg              | 2         | 0.48%   |
| Freiburg im Breisgau | 2         | 0.48%   |
| Curitiba             | 2         | 0.48%   |
| Columbia City        | 2         | 0.48%   |
| Ciudad Juárez       | 2         | 0.48%   |
| Boynton Beach        | 2         | 0.48%   |
| Birmingham           | 2         | 0.48%   |
| Bend                 | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 82        | 129    | 14.41%  |
| Samsung Electronics       | 78        | 116    | 13.71%  |
| Seagate                   | 69        | 93     | 12.13%  |
| Kingston                  | 37        | 51     | 6.5%    |
| SanDisk                   | 30        | 43     | 5.27%   |
| Unknown                   | 28        | 43     | 4.92%   |
| Toshiba                   | 26        | 29     | 4.57%   |
| Crucial                   | 22        | 25     | 3.87%   |
| SK hynix                  | 16        | 17     | 2.81%   |
| Hitachi                   | 16        | 17     | 2.81%   |
| A-DATA Technology         | 11        | 12     | 1.93%   |
| Intel                     | 10        | 11     | 1.76%   |
| China                     | 9         | 11     | 1.58%   |
| Apple                     | 8         | 13     | 1.41%   |
| Micron Technology         | 7         | 8      | 1.23%   |
| PNY                       | 6         | 7      | 1.05%   |
| Phison                    | 5         | 9      | 0.88%   |
| Patriot                   | 5         | 5      | 0.88%   |
| HGST                      | 5         | 10     | 0.88%   |
| Unknown                   | 5         | 8      | 0.88%   |
| SPCC                      | 4         | 5      | 0.7%    |
| Silicon Motion            | 4         | 5      | 0.7%    |
| KingSpec                  | 4         | 4      | 0.7%    |
| Fujitsu                   | 4         | 4      | 0.7%    |
| ADATA Technology          | 4         | 5      | 0.7%    |
| Transcend                 | 3         | 5      | 0.53%   |
| Team                      | 3         | 3      | 0.53%   |
| Intenso                   | 3         | 3      | 0.53%   |
| GOODRAM                   | 3         | 3      | 0.53%   |
| Emtec                     | 3         | 3      | 0.53%   |
| ASMT                      | 3         | 4      | 0.53%   |
| Star Drive                | 2         | 2      | 0.35%   |
| Phison Electronics        | 2         | 2      | 0.35%   |
| Netac                     | 2         | 2      | 0.35%   |
| Micron/Crucial Technology | 2         | 4      | 0.35%   |
| KIOXIA                    | 2         | 9      | 0.35%   |
| Gigabyte Technology       | 2         | 4      | 0.35%   |
| Fanxiang                  | 2         | 2      | 0.35%   |
| XrayDisk                  | 1         | 2      | 0.18%   |
| WINTEC                    | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 1.27%   |
| Samsung SSD 850 EVO 250GB                           | 7         | 1.11%   |
| Kingston SA400S37480G 480GB SSD                     | 7         | 1.11%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 1.11%   |
| Samsung SSD 850 EVO 500GB                           | 6         | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 6         | 0.95%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.95%   |
| Unknown SD/MMC/MS PRO 128GB                         | 5         | 0.79%   |
| Unknown                                             | 5         | 0.79%   |
| Unknown MMC Card  64GB                              | 4         | 0.64%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 0.64%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 0.64%   |
| Samsung SSD 980 PRO 1TB                             | 4         | 0.64%   |
| Samsung SSD 970 EVO 500GB                           | 4         | 0.64%   |
| Crucial CT1000BX500SSD1 1TB                         | 4         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 0.48%   |
| Unknown MMC Card  128GB                             | 3         | 0.48%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 3         | 0.48%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 512GB | 3         | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3         | 0.48%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 3         | 0.48%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.48%   |
| Samsung SSD 980 1TB                                 | 3         | 0.48%   |
| Samsung SSD 840 EVO 250GB                           | 3         | 0.48%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.48%   |
| Crucial CT480BX500SSD1 480GB                        | 3         | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.32%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 2         | 0.32%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 2         | 0.32%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 2         | 0.32%   |
| WDC WD3003FZEX-00Z4SA0 3TB                          | 2         | 0.32%   |
| WDC WD1600BEVT-22ZCT0 160GB                         | 2         | 0.32%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 2         | 0.32%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB                | 2         | 0.32%   |
| Unknown SC128  128GB                                | 2         | 0.32%   |
| Unknown MMC Card  32GB                              | 2         | 0.32%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.32%   |
| Toshiba MQ01ACF050 500GB                            | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 69        | 92     | 33.82%  |
| WDC                 | 68        | 111    | 33.33%  |
| Toshiba             | 21        | 24     | 10.29%  |
| Hitachi             | 16        | 17     | 7.84%   |
| Samsung Electronics | 9         | 12     | 4.41%   |
| Unknown             | 5         | 5      | 2.45%   |
| HGST                | 5         | 10     | 2.45%   |
| Fujitsu             | 4         | 4      | 1.96%   |
| Intenso             | 2         | 2      | 0.98%   |
| ASMT                | 2         | 3      | 0.98%   |
| Initio              | 1         | 1      | 0.49%   |
| ASMedia             | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 53     | 17.84%  |
| Kingston            | 30        | 43     | 14.08%  |
| Crucial             | 21        | 24     | 9.86%   |
| SanDisk             | 15        | 21     | 7.04%   |
| A-DATA Technology   | 11        | 12     | 5.16%   |
| China               | 8         | 10     | 3.76%   |
| WDC                 | 7         | 8      | 3.29%   |
| PNY                 | 6         | 7      | 2.82%   |
| Apple               | 6         | 6      | 2.82%   |
| Patriot             | 5         | 5      | 2.35%   |
| KingSpec            | 4         | 4      | 1.88%   |
| Intel               | 4         | 4      | 1.88%   |
| Transcend           | 3         | 5      | 1.41%   |
| Toshiba             | 3         | 3      | 1.41%   |
| Team                | 3         | 3      | 1.41%   |
| SPCC                | 3         | 4      | 1.41%   |
| SK hynix            | 3         | 3      | 1.41%   |
| GOODRAM             | 3         | 3      | 1.41%   |
| Unknown             | 3         | 4      | 1.41%   |
| Netac               | 2         | 2      | 0.94%   |
| Micron Technology   | 2         | 2      | 0.94%   |
| Gigabyte Technology | 2         | 4      | 0.94%   |
| Emtec               | 2         | 2      | 0.94%   |
| WINTEC              | 1         | 1      | 0.47%   |
| Vaseky              | 1         | 3      | 0.47%   |
| TakeMS              | 1         | 1      | 0.47%   |
| T-FORCE             | 1         | 1      | 0.47%   |
| SSD PHIS            | 1         | 1      | 0.47%   |
| SD                  | 1         | 1      | 0.47%   |
| SCCTS-603-001T      | 1         | 1      | 0.47%   |
| Phison              | 1         | 5      | 0.47%   |
| ORICO               | 1         | 1      | 0.47%   |
| OCZ-VERTEX          | 1         | 1      | 0.47%   |
| OCZ                 | 1         | 1      | 0.47%   |
| NGFF                | 1         | 1      | 0.47%   |
| Microtech           | 1         | 2      | 0.47%   |
| LITEONIT            | 1         | 1      | 0.47%   |
| LITEON              | 1         | 1      | 0.47%   |
| Lexar               | 1         | 1      | 0.47%   |
| KODAK               | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 189       | 271    | 36.28%  |
| HDD     | 177       | 283    | 33.97%  |
| NVMe    | 115       | 163    | 22.07%  |
| MMC     | 24        | 37     | 4.61%   |
| Unknown | 16        | 21     | 3.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 306       | 543    | 65.52%  |
| NVMe | 113       | 161    | 24.2%   |
| SAS  | 24        | 34     | 5.14%   |
| MMC  | 24        | 37     | 5.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 233       | 350    | 62.63%  |
| 0.51-1.0   | 95        | 140    | 25.54%  |
| 1.01-2.0   | 20        | 25     | 5.38%   |
| 4.01-10.0  | 8         | 12     | 2.15%   |
| 3.01-4.0   | 7         | 12     | 1.88%   |
| 2.01-3.0   | 7         | 13     | 1.88%   |
| 10.01-20.0 | 2         | 2      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 130       | 31.55%  |
| 251-500        | 100       | 24.27%  |
| 501-1000       | 54        | 13.11%  |
| 1001-2000      | 38        | 9.22%   |
| 51-100         | 27        | 6.55%   |
| 1-20           | 21        | 5.1%    |
| More than 3000 | 16        | 3.88%   |
| 2001-3000      | 13        | 3.16%   |
| 21-50          | 12        | 2.91%   |
| Unknown        | 1         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 175       | 40.79%  |
| 21-50          | 84        | 19.58%  |
| 101-250        | 50        | 11.66%  |
| 51-100         | 50        | 11.66%  |
| 251-500        | 28        | 6.53%   |
| 501-1000       | 22        | 5.13%   |
| 1001-2000      | 9         | 2.1%    |
| More than 3000 | 5         | 1.17%   |
| 2001-3000      | 5         | 1.17%   |
| Unknown        | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 2.94%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.94%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 2.94%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 2.94%   |
| WDC WD1200BEVS-07LAT0 120GB           | 1         | 1      | 2.94%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 2.94%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 2.94%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 2.94%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 2.94%   |
| Toshiba HDWD110 1TB                   | 1         | 1      | 2.94%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 2.94%   |
| Seagate ST98823AS 80GB                | 1         | 1      | 2.94%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 2.94%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 2.94%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 2.94%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 2.94%   |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 2.94%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 980 PRO 1TB   | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 980 500GB     | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 2.94%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 2.94%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 2.94%   |
| Samsung Electronics HD153WI 1TB       | 1         | 1      | 2.94%   |
| Phison ES 512GB                       | 1         | 1      | 2.94%   |
| Intenso SSD 256GB                     | 1         | 1      | 2.94%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 2.94%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 2.94%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 2.94%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.94%   |
| Hitachi HDS721010KLA330 1TB           | 1         | 1      | 2.94%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 24.24%  |
| Samsung Electronics | 7         | 8      | 21.21%  |
| WDC                 | 5         | 6      | 15.15%  |
| Toshiba             | 3         | 3      | 9.09%   |
| Hitachi             | 3         | 3      | 9.09%   |
| Intel               | 2         | 2      | 6.06%   |
| WINTEC              | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Phison              | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 38.1%   |
| WDC                 | 5         | 6      | 23.81%  |
| Hitachi             | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| HGST                | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 22     | 62.5%   |
| SSD  | 7         | 7      | 21.88%  |
| NVMe | 5         | 6      | 15.63%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 267       | 488    | 60.96%  |
| Works    | 140       | 252    | 31.96%  |
| Malfunc  | 31        | 35     | 7.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 272       | 55.06%  |
| AMD                            | 82        | 16.6%   |
| Samsung Electronics            | 40        | 8.1%    |
| SanDisk                        | 20        | 4.05%   |
| SK hynix                       | 13        | 2.63%   |
| Phison Electronics             | 10        | 2.02%   |
| Kingston Technology Company    | 7         | 1.42%   |
| ASMedia Technology             | 6         | 1.21%   |
| Micron Technology              | 5         | 1.01%   |
| JMicron Technology             | 5         | 1.01%   |
| Silicon Motion                 | 4         | 0.81%   |
| Nvidia                         | 4         | 0.81%   |
| Marvell Technology Group       | 4         | 0.81%   |
| ADATA Technology               | 4         | 0.81%   |
| Micron/Crucial Technology      | 3         | 0.61%   |
| KIOXIA                         | 3         | 0.61%   |
| Broadcom / LSI                 | 3         | 0.61%   |
| VIA Technologies               | 2         | 0.4%    |
| Union Memory (Shenzhen)        | 2         | 0.4%    |
| Toshiba America Info Systems   | 2         | 0.4%    |
| Solid State Storage Technology | 1         | 0.2%    |
| LSI Logic / Symbios Logic      | 1         | 0.2%    |
| Apple                          | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 58        | 10.02%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 24        | 4.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 3.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 3.11%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 16        | 2.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 2.76%   |
| Samsung NVMe SSD Controller 980                                                  | 15        | 2.59%   |
| AMD 400 Series Chipset SATA Controller                                           | 15        | 2.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 13        | 2.25%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 2.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 11        | 1.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10        | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8         | 1.38%   |
| Phison PS5013 E13 NVMe Controller                                                | 7         | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.04%   |
| AMD FCH SATA Controller D                                                        | 6         | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5         | 0.86%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.86%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                           | 5         | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 0.69%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 0.69%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 307       | 58.93%  |
| NVMe | 114       | 21.88%  |
| IDE  | 53        | 10.17%  |
| RAID | 43        | 8.25%   |
| SAS  | 3         | 0.58%   |
| SCSI | 1         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 302       | 75.31%  |
| AMD    | 99        | 24.69%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 2.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.24%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 1.24%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.24%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 1.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.99%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 0.99%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.99%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 0.99%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 3         | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.74%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.74%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 3         | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.74%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.74%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 3         | 0.74%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz           | 2         | 0.5%    |
| Intel Pentium M processor 1.73GHz             | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.5%    |
| Intel Pentium CPU P6000 @ 1.87GHz             | 2         | 0.5%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.5%    |
| Intel Pentium CPU G645 @ 2.90GHz              | 2         | 0.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.5%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.5%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.5%    |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.5%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 78        | 19.4%   |
| Intel Core i7           | 51        | 12.69%  |
| Intel Core i3           | 35        | 8.71%   |
| Other                   | 31        | 7.71%   |
| AMD Ryzen 5             | 27        | 6.72%   |
| Intel Celeron           | 23        | 5.72%   |
| AMD Ryzen 7             | 23        | 5.72%   |
| Intel Core 2 Duo        | 19        | 4.73%   |
| Intel Pentium           | 14        | 3.48%   |
| Intel Xeon              | 12        | 2.99%   |
| Intel Atom              | 11        | 2.74%   |
| AMD Ryzen 3             | 10        | 2.49%   |
| Intel Pentium Dual-Core | 5         | 1.24%   |
| AMD E1                  | 5         | 1.24%   |
| AMD A4                  | 5         | 1.24%   |
| Intel Core 2            | 4         | 1%      |
| Intel Pentium Silver    | 3         | 0.75%   |
| Intel Pentium Gold      | 3         | 0.75%   |
| Intel Core 2 Quad       | 3         | 0.75%   |
| AMD Ryzen 9             | 3         | 0.75%   |
| AMD FX                  | 3         | 0.75%   |
| AMD Athlon              | 3         | 0.75%   |
| AMD A10                 | 3         | 0.75%   |
| Intel Pentium M         | 2         | 0.5%    |
| Intel Pentium Dual      | 2         | 0.5%    |
| Intel Pentium D         | 2         | 0.5%    |
| Intel Genuine           | 2         | 0.5%    |
| Intel Celeron M         | 2         | 0.5%    |
| AMD E2                  | 2         | 0.5%    |
| AMD Athlon II X2        | 2         | 0.5%    |
| AMD A8                  | 2         | 0.5%    |
| Intel Core m3           | 1         | 0.25%   |
| Intel Core i9           | 1         | 0.25%   |
| Intel Core 2 Extreme    | 1         | 0.25%   |
| AMD Turion 64 X2 Mobile | 1         | 0.25%   |
| AMD Phenom II X6        | 1         | 0.25%   |
| AMD Phenom II X4        | 1         | 0.25%   |
| AMD G                   | 1         | 0.25%   |
| AMD E                   | 1         | 0.25%   |
| AMD C-50                | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 187       | 46.4%   |
| 4      | 133       | 33%     |
| 8      | 32        | 7.94%   |
| 6      | 30        | 7.44%   |
| 1      | 11        | 2.73%   |
| 16     | 5         | 1.24%   |
| 12     | 3         | 0.74%   |
| 10     | 2         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 395       | 98.5%   |
| 2      | 6         | 1.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 262       | 65.17%  |
| 1      | 140       | 34.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 392       | 97.76%  |
| 32-bit         | 9         | 2.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 31        | 7.58%   |
| 0x206a7    | 22        | 5.38%   |
| 0x806c1    | 20        | 4.89%   |
| 0x306c3    | 17        | 4.16%   |
| 0x1067a    | 15        | 3.67%   |
| Unknown    | 15        | 3.67%   |
| 0x08108109 | 14        | 3.42%   |
| 0x406e3    | 13        | 3.18%   |
| 0x40651    | 13        | 3.18%   |
| 0x806ec    | 10        | 2.44%   |
| 0x806e9    | 9         | 2.2%    |
| 0x6fd      | 9         | 2.2%    |
| 0x20655    | 9         | 2.2%    |
| 0x08608103 | 9         | 2.2%    |
| 0x0a50000d | 8         | 1.96%   |
| 0x906ea    | 7         | 1.71%   |
| 0x806ea    | 7         | 1.71%   |
| 0x706a8    | 7         | 1.71%   |
| 0x506e3    | 7         | 1.71%   |
| 0x406c4    | 7         | 1.71%   |
| 0x906c0    | 6         | 1.47%   |
| 0x0800820d | 6         | 1.47%   |
| 0x706e5    | 5         | 1.22%   |
| 0x106e5    | 5         | 1.22%   |
| 0x08701021 | 5         | 1.22%   |
| 0x906ed    | 4         | 0.98%   |
| 0x906e9    | 4         | 0.98%   |
| 0x6f6      | 4         | 0.98%   |
| 0x30661    | 4         | 0.98%   |
| 0x20652    | 4         | 0.98%   |
| 0x106c2    | 4         | 0.98%   |
| 0x10676    | 4         | 0.98%   |
| 0x0a50000c | 4         | 0.98%   |
| 0x06006705 | 4         | 0.98%   |
| 0x06001119 | 4         | 0.98%   |
| 0xa0671    | 3         | 0.73%   |
| 0x806eb    | 3         | 0.73%   |
| 0x706a1    | 3         | 0.73%   |
| 0x6fb      | 3         | 0.73%   |
| 0x306d4    | 3         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 44        | 10.89%  |
| IvyBridge        | 34        | 8.42%   |
| Haswell          | 31        | 7.67%   |
| SandyBridge      | 26        | 6.44%   |
| Zen+             | 22        | 5.45%   |
| TigerLake        | 22        | 5.45%   |
| Skylake          | 20        | 4.95%   |
| Penryn           | 19        | 4.7%    |
| Unknown          | 18        | 4.46%   |
| Core             | 17        | 4.21%   |
| Zen 3            | 16        | 3.96%   |
| Westmere         | 16        | 3.96%   |
| Silvermont       | 13        | 3.22%   |
| Zen 2            | 10        | 2.48%   |
| Goldmont plus    | 10        | 2.48%   |
| Bonnell          | 9         | 2.23%   |
| Zen              | 8         | 1.98%   |
| Piledriver       | 7         | 1.73%   |
| Excavator        | 7         | 1.73%   |
| Tremont          | 6         | 1.49%   |
| Nehalem          | 6         | 1.49%   |
| Icelake          | 6         | 1.49%   |
| K10              | 5         | 1.24%   |
| P6               | 4         | 0.99%   |
| Jaguar           | 4         | 0.99%   |
| CometLake        | 4         | 0.99%   |
| Broadwell        | 4         | 0.99%   |
| Bobcat           | 4         | 0.99%   |
| Puma             | 3         | 0.74%   |
| NetBurst         | 3         | 0.74%   |
| K8 Hammer        | 2         | 0.5%    |
| Goldmont         | 2         | 0.5%    |
| Bulldozer        | 1         | 0.25%   |
| Alderlake Hybrid | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 232       | 50.66%  |
| Nvidia | 123       | 26.86%  |
| AMD    | 103       | 22.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 3.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 3.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 3.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 2.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 2.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.89%   |
| AMD Lucienne                                                                             | 9         | 1.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.47%   |
| Intel HD Graphics 620                                                                    | 7         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.47%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 6         | 1.26%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 1.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.26%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.26%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.26%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 1.26%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.84%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.84%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 0.84%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.84%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 0.63%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.63%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 3         | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 185       | 45.79%  |
| 1 x AMD        | 79        | 19.55%  |
| 1 x Nvidia     | 78        | 19.31%  |
| Intel + Nvidia | 37        | 9.16%   |
| 2 x AMD        | 9         | 2.23%   |
| AMD + Nvidia   | 8         | 1.98%   |
| Intel + AMD    | 7         | 1.73%   |
| Other          | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 333       | 82.02%  |
| Proprietary | 50        | 12.32%  |
| Unknown     | 23        | 5.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 217       | 53.19%  |
| 0.01-0.5   | 65        | 15.93%  |
| 1.01-2.0   | 59        | 14.46%  |
| 0.51-1.0   | 24        | 5.88%   |
| 3.01-4.0   | 22        | 5.39%   |
| 5.01-6.0   | 8         | 1.96%   |
| 7.01-8.0   | 7         | 1.72%   |
| 2.01-3.0   | 3         | 0.74%   |
| 8.01-16.0  | 2         | 0.49%   |
| 16.01-24.0 | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 13.35%  |
| LG Display              | 45        | 11.34%  |
| Samsung Electronics     | 44        | 11.08%  |
| Chimei Innolux          | 37        | 9.32%   |
| BOE                     | 34        | 8.56%   |
| Goldstar                | 17        | 4.28%   |
| Acer                    | 14        | 3.53%   |
| Dell                    | 13        | 3.27%   |
| Apple                   | 13        | 3.27%   |
| Hewlett-Packard         | 9         | 2.27%   |
| Chi Mei Optoelectronics | 9         | 2.27%   |
| Philips                 | 8         | 2.02%   |
| BenQ                    | 8         | 2.02%   |
| InfoVision              | 7         | 1.76%   |
| PANDA                   | 6         | 1.51%   |
| Unknown                 | 5         | 1.26%   |
| Sharp                   | 5         | 1.26%   |
| LG Philips              | 5         | 1.26%   |
| Lenovo                  | 5         | 1.26%   |
| ViewSonic               | 4         | 1.01%   |
| Sony                    | 4         | 1.01%   |
| HannStar                | 4         | 1.01%   |
| AOC                     | 4         | 1.01%   |
| Ancor Communications    | 4         | 1.01%   |
| SLD                     | 2         | 0.5%    |
| Sceptre Tech            | 2         | 0.5%    |
| Quanta Display          | 2         | 0.5%    |
| Panasonic               | 2         | 0.5%    |
| Insignia                | 2         | 0.5%    |
| Iiyama                  | 2         | 0.5%    |
| DENON                   | 2         | 0.5%    |
| ASUSTek Computer        | 2         | 0.5%    |
| ___                     | 1         | 0.25%   |
| Vestel Elektronik       | 1         | 0.25%   |
| Unknown (XXX)           | 1         | 0.25%   |
| TR_                     | 1         | 0.25%   |
| SKY                     | 1         | 0.25%   |
| PLN                     | 1         | 0.25%   |
| Planar                  | 1         | 0.25%   |
| Pioneer                 | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.98%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 3         | 0.73%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.73%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.73%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 0.73%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.73%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 2         | 0.49%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch           | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.49%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.49%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 2         | 0.49%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 2         | 0.49%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.49%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.49%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch              | 2         | 0.49%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 0.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.49%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 2         | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.49%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.49%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.49%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 2         | 0.49%   |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch                    | 2         | 0.49%   |
| ___ LCDTV16 ___0101 1920x1080                                            | 1         | 0.24%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch               | 1         | 0.24%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch            | 1         | 0.24%   |
| ViewSonic VG2756-4K VSC553A 3840x2160 597x336mm 27.0-inch                | 1         | 0.24%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch                 | 1         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 163       | 42.23%  |
| 1366x768 (WXGA)    | 94        | 24.35%  |
| 1600x900 (HD+)     | 18        | 4.66%   |
| 3840x2160 (4K)     | 15        | 3.89%   |
| 1920x1200 (WUXGA)  | 12        | 3.11%   |
| 1680x1050 (WSXGA+) | 11        | 2.85%   |
| 1280x800 (WXGA)    | 11        | 2.85%   |
| 1440x900 (WXGA+)   | 9         | 2.33%   |
| 2560x1440 (QHD)    | 8         | 2.07%   |
| 1280x1024 (SXGA)   | 7         | 1.81%   |
| 2560x1080          | 6         | 1.55%   |
| 1024x600           | 6         | 1.55%   |
| 3440x1440          | 5         | 1.3%    |
| 1360x768           | 4         | 1.04%   |
| Unknown            | 3         | 0.78%   |
| 3840x1080          | 2         | 0.52%   |
| 2880x1800          | 2         | 0.52%   |
| 2560x1600          | 2         | 0.52%   |
| 1280x768           | 2         | 0.52%   |
| 4480x1440          | 1         | 0.26%   |
| 2256x1504          | 1         | 0.26%   |
| 1600x1200          | 1         | 0.26%   |
| 1280x720 (HD)      | 1         | 0.26%   |
| 1024x768 (XGA)     | 1         | 0.26%   |
| 1024x576           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 128       | 31.92%  |
| 13      | 44        | 10.97%  |
| 24      | 29        | 7.23%   |
| Unknown | 29        | 7.23%   |
| 14      | 26        | 6.48%   |
| 17      | 19        | 4.74%   |
| 21      | 18        | 4.49%   |
| 27      | 15        | 3.74%   |
| 23      | 14        | 3.49%   |
| 12      | 9         | 2.24%   |
| 20      | 8         | 2%      |
| 11      | 8         | 2%      |
| 34      | 7         | 1.75%   |
| 10      | 7         | 1.75%   |
| 18      | 6         | 1.5%    |
| 72      | 5         | 1.25%   |
| 22      | 5         | 1.25%   |
| 31      | 4         | 1%      |
| 19      | 4         | 1%      |
| 40      | 2         | 0.5%    |
| 32      | 2         | 0.5%    |
| 28      | 2         | 0.5%    |
| 25      | 2         | 0.5%    |
| 84      | 1         | 0.25%   |
| 64      | 1         | 0.25%   |
| 54      | 1         | 0.25%   |
| 52      | 1         | 0.25%   |
| 33      | 1         | 0.25%   |
| 26      | 1         | 0.25%   |
| 16      | 1         | 0.25%   |
| 8       | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 178       | 45.41%  |
| 501-600     | 57        | 14.54%  |
| 201-300     | 43        | 10.97%  |
| 401-500     | 35        | 8.93%   |
| Unknown     | 29        | 7.4%    |
| 351-400     | 21        | 5.36%   |
| 701-800     | 10        | 2.55%   |
| 601-700     | 8         | 2.04%   |
| 1501-2000   | 6         | 1.53%   |
| 801-900     | 2         | 0.51%   |
| 1001-1500   | 2         | 0.51%   |
| 101-200     | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 278       | 74.93%  |
| 16/10   | 48        | 12.94%  |
| Unknown | 25        | 6.74%   |
| 21/9    | 10        | 2.7%    |
| 5/4     | 5         | 1.35%   |
| 4/3     | 4         | 1.08%   |
| 3/2     | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 127       | 31.99%  |
| 81-90          | 54        | 13.6%   |
| 201-250        | 51        | 12.85%  |
| Unknown        | 29        | 7.3%    |
| 71-80          | 16        | 4.03%   |
| 301-350        | 16        | 4.03%   |
| 351-500        | 15        | 3.78%   |
| 251-300        | 14        | 3.53%   |
| 151-200        | 13        | 3.27%   |
| 121-130        | 12        | 3.02%   |
| 61-70          | 9         | 2.27%   |
| 141-150        | 9         | 2.27%   |
| More than 1000 | 8         | 2.02%   |
| 51-60          | 8         | 2.02%   |
| 41-50          | 7         | 1.76%   |
| 131-140        | 4         | 1.01%   |
| 501-1000       | 2         | 0.5%    |
| 1-40           | 1         | 0.25%   |
| 111-120        | 1         | 0.25%   |
| 91-100         | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 115       | 29.41%  |
| 101-120       | 112       | 28.64%  |
| 51-100        | 108       | 27.62%  |
| Unknown       | 29        | 7.42%   |
| 161-240       | 17        | 4.35%   |
| 1-50          | 6         | 1.53%   |
| More than 240 | 4         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 339       | 83.29%  |
| 2     | 44        | 10.81%  |
| 0     | 21        | 5.16%   |
| 3     | 3         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 212       | 35.51%  |
| Intel                             | 190       | 31.83%  |
| Qualcomm Atheros                  | 67        | 11.22%  |
| Broadcom                          | 39        | 6.53%   |
| TP-Link                           | 10        | 1.68%   |
| Marvell Technology Group          | 10        | 1.68%   |
| Broadcom Limited                  | 10        | 1.68%   |
| MediaTek                          | 8         | 1.34%   |
| Ralink Technology                 | 6         | 1.01%   |
| Ralink                            | 4         | 0.67%   |
| Nvidia                            | 4         | 0.67%   |
| Samsung Electronics               | 3         | 0.5%    |
| NetGear                           | 3         | 0.5%    |
| Xiaomi                            | 2         | 0.34%   |
| Spreadtrum Communications         | 2         | 0.34%   |
| Huawei Technologies               | 2         | 0.34%   |
| Google                            | 2         | 0.34%   |
| Edimax Technology                 | 2         | 0.34%   |
| Dell                              | 2         | 0.34%   |
| VIA Technologies                  | 1         | 0.17%   |
| Tenda                             | 1         | 0.17%   |
| Sierra Wireless                   | 1         | 0.17%   |
| Qualcomm Atheros Communications   | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.17%   |
| Microsoft                         | 1         | 0.17%   |
| Microchip Technology              | 1         | 0.17%   |
| Mercucys                          | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| IMC Networks                      | 1         | 0.17%   |
| HTC (High Tech Computer)          | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Fibocom                           | 1         | 0.17%   |
| Ericsson Business Mobile Networks | 1         | 0.17%   |
| Davicom Semiconductor             | 1         | 0.17%   |
| Belkin Components                 | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 128       | 17.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 2.75%   |
| Intel Wireless 3165                                               | 14        | 1.92%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 1.79%   |
| Intel Wireless 8260                                               | 12        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.51%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.51%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.1%    |
| Intel Wireless 7265                                               | 8         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.96%   |
| Intel Wireless 7260                                               | 7         | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.96%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.69%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 4         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.55%   |
| Realtek 802.11ac NIC                                              | 4         | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4         | 0.55%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 0.55%   |
| Intel WiFi Link 5100                                              | 4         | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 145       | 41.08%  |
| Realtek Semiconductor           | 83        | 23.51%  |
| Qualcomm Atheros                | 45        | 12.75%  |
| Broadcom                        | 31        | 8.78%   |
| TP-Link                         | 9         | 2.55%   |
| MediaTek                        | 7         | 1.98%   |
| Broadcom Limited                | 7         | 1.98%   |
| Ralink Technology               | 6         | 1.7%    |
| Ralink                          | 4         | 1.13%   |
| NetGear                         | 3         | 0.85%   |
| Edimax Technology               | 2         | 0.57%   |
| Xiaomi                          | 1         | 0.28%   |
| Sierra Wireless                 | 1         | 0.28%   |
| Qualcomm Atheros Communications | 1         | 0.28%   |
| Microsoft                       | 1         | 0.28%   |
| Mercucys                        | 1         | 0.28%   |
| Marvell Technology Group        | 1         | 0.28%   |
| IMC Networks                    | 1         | 0.28%   |
| Fibocom                         | 1         | 0.28%   |
| Dell                            | 1         | 0.28%   |
| Belkin Components               | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 5.51%   |
| Intel Wireless 3165                                                     | 14        | 3.86%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 3.58%   |
| Intel Wireless 8260                                                     | 12        | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 11        | 3.03%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2.2%    |
| Intel Wireless 7265                                                     | 8         | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 7         | 1.93%   |
| Intel Wireless 7260                                                     | 7         | 1.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.1%    |
| Realtek 802.11ac NIC                                                    | 4         | 1.1%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4         | 1.1%    |
| Intel WiFi Link 5100                                                    | 4         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.1%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.83%   |
| Realtek RTL8187B Wireless Adapter                                       | 3         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.83%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.83%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 3         | 0.83%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 180       | 50.56%  |
| Intel                         | 95        | 26.69%  |
| Qualcomm Atheros              | 32        | 8.99%   |
| Broadcom                      | 11        | 3.09%   |
| Marvell Technology Group      | 9         | 2.53%   |
| Nvidia                        | 4         | 1.12%   |
| Samsung Electronics           | 3         | 0.84%   |
| Broadcom Limited              | 3         | 0.84%   |
| Spreadtrum Communications     | 2         | 0.56%   |
| Huawei Technologies           | 2         | 0.56%   |
| Google                        | 2         | 0.56%   |
| Xiaomi                        | 1         | 0.28%   |
| VIA Technologies              | 1         | 0.28%   |
| TP-Link                       | 1         | 0.28%   |
| Tenda                         | 1         | 0.28%   |
| Qualcomm                      | 1         | 0.28%   |
| OnePlus Technology (Shenzhen) | 1         | 0.28%   |
| Microchip Technology          | 1         | 0.28%   |
| MediaTek                      | 1         | 0.28%   |
| Lenovo                        | 1         | 0.28%   |
| JMicron Technology            | 1         | 0.28%   |
| HTC (High Tech Computer)      | 1         | 0.28%   |
| Hewlett-Packard               | 1         | 0.28%   |
| Davicom Semiconductor         | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 128       | 35.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 8.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 5.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.93%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.93%   |
| Intel Ethernet Connection I219-V                                  | 7         | 1.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 1.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 1.38%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 4         | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.1%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.1%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.83%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.83%   |
| Spreadtrum Spreadtrum Phone                                       | 2         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.55%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.55%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 336       | 50.07%  |
| WiFi     | 332       | 49.48%  |
| Modem    | 3         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 239       | 56.77%  |
| Ethernet | 182       | 43.23%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 230       | 57.36%  |
| 1     | 156       | 38.9%   |
| 0     | 10        | 2.49%   |
| 3     | 5         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 279       | 68.38%  |
| Yes  | 129       | 31.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 46.81%  |
| Realtek Semiconductor           | 38        | 16.17%  |
| Cambridge Silicon Radio         | 12        | 5.11%   |
| Apple                           | 12        | 5.11%   |
| Lite-On Technology              | 11        | 4.68%   |
| Foxconn / Hon Hai               | 11        | 4.68%   |
| Broadcom                        | 11        | 4.68%   |
| Qualcomm Atheros Communications | 9         | 3.83%   |
| Dell                            | 5         | 2.13%   |
| IMC Networks                    | 4         | 1.7%    |
| Hewlett-Packard                 | 4         | 1.7%    |
| MediaTek                        | 2         | 0.85%   |
| Foxconn International           | 2         | 0.85%   |
| ISSC                            | 1         | 0.43%   |
| Dynex                           | 1         | 0.43%   |
| Chicony Electronics             | 1         | 0.43%   |
| Askey Computer                  | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 20.43%  |
| Realtek Bluetooth Radio                             | 26        | 11.06%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 7.66%   |
| Intel AX201 Bluetooth                               | 17        | 7.23%   |
| Intel AX200 Bluetooth                               | 12        | 5.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 5.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 3.4%    |
| Intel AX210 Bluetooth                               | 5         | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.7%    |
| Lite-On Bluetooth Device                            | 4         | 1.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.28%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 1.28%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.28%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.28%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 1.28%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.28%   |
| Apple Bluetooth Host Controller                     | 3         | 1.28%   |
| Apple Bluetooth HCI                                 | 3         | 1.28%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.85%   |
| MediaTek Wireless_Device                            | 2         | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.85%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.85%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.85%   |
| Foxconn / Hon Hai Acer Module                       | 2         | 0.85%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 0.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.85%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.85%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.43%   |
| Lite-On Wireless_Device                             | 1         | 0.43%   |
| ISSC Bluetooth Device                               | 1         | 0.43%   |
| Intel Bluetooth Device                              | 1         | 0.43%   |
| IMC Networks Bluetooth Device                       | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 292       | 54.78%  |
| AMD                                  | 114       | 21.39%  |
| Nvidia                               | 94        | 17.64%  |
| C-Media Electronics                  | 7         | 1.31%   |
| Texas Instruments                    | 4         | 0.75%   |
| VIA Technologies                     | 2         | 0.38%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.38%   |
| KTMicro                              | 2         | 0.38%   |
| JMTek                                | 2         | 0.38%   |
| GN Netcom                            | 2         | 0.38%   |
| Yamaha                               | 1         | 0.19%   |
| Turtle Beach                         | 1         | 0.19%   |
| Sony                                 | 1         | 0.19%   |
| Realtek Semiconductor                | 1         | 0.19%   |
| QinHeng Electronics                  | 1         | 0.19%   |
| Native Instruments                   | 1         | 0.19%   |
| Micro Star International             | 1         | 0.19%   |
| Logitech                             | 1         | 0.19%   |
| Generalplus Technology               | 1         | 0.19%   |
| FUXIN                                | 1         | 0.19%   |
| Creative Technology                  | 1         | 0.19%   |
| Audioengine                          | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 48        | 7.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 5.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 4.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 23        | 3.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 3.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 20        | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 2.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 2.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 2.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 13        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 1.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.42%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.1%    |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.94%   |
| Intel Jasper Lake HD Audio                                                                        | 6         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 5         | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.79%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.63%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 4         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 48        | 24.49%  |
| SK hynix                     | 32        | 16.33%  |
| Unknown                      | 26        | 13.27%  |
| Micron Technology            | 19        | 9.69%   |
| Kingston                     | 15        | 7.65%   |
| Corsair                      | 10        | 5.1%    |
| Crucial                      | 8         | 4.08%   |
| G.Skill                      | 7         | 3.57%   |
| Nanya Technology             | 4         | 2.04%   |
| A-DATA Technology            | 4         | 2.04%   |
| Unknown (ABCD)               | 3         | 1.53%   |
| Team                         | 2         | 1.02%   |
| Ramaxel Technology           | 2         | 1.02%   |
| GSkill                       | 2         | 1.02%   |
| Elpida                       | 2         | 1.02%   |
| Unknown                      | 2         | 1.02%   |
| Strontium                    | 1         | 0.51%   |
| Smart                        | 1         | 0.51%   |
| PUSKILL                      | 1         | 0.51%   |
| Patriot Memory (PDP Systems) | 1         | 0.51%   |
| Lexar Co Limited             | 1         | 0.51%   |
| KLEVV                        | 1         | 0.51%   |
| GeIL                         | 1         | 0.51%   |
| AVEXIR                       | 1         | 0.51%   |
| AMD                          | 1         | 0.51%   |
| 4ea5                         | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 1.42%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.94%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.94%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 2         | 0.94%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.94%   |
| Micron RAM MT40A512M16TB-062E:R 4GB Row Of Chips DDR4 3200MT/s   | 2         | 0.94%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Unknown                                                          | 2         | 0.94%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.47%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.47%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DRAM                               | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.47%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 81        | 47.65%  |
| DDR3    | 57        | 33.53%  |
| DDR2    | 13        | 7.65%   |
| LPDDR4  | 7         | 4.12%   |
| SDRAM   | 6         | 3.53%   |
| LPDDR3  | 2         | 1.18%   |
| Unknown | 2         | 1.18%   |
| DRAM    | 1         | 0.59%   |
| DDR     | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 67.25%  |
| DIMM         | 44        | 25.73%  |
| Row Of Chips | 9         | 5.26%   |
| Unknown      | 2         | 1.17%   |
| Chip         | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 34.57%  |
| 4096  | 47        | 25%     |
| 2048  | 35        | 18.62%  |
| 16384 | 25        | 13.3%   |
| 32768 | 6         | 3.19%   |
| 1024  | 6         | 3.19%   |
| 512   | 4         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 39        | 21.43%  |
| 1600    | 34        | 18.68%  |
| 2667    | 23        | 12.64%  |
| 2400    | 15        | 8.24%   |
| 2133    | 9         | 4.95%   |
| 1333    | 9         | 4.95%   |
| 1334    | 8         | 4.4%    |
| Unknown | 7         | 3.85%   |
| 1067    | 6         | 3.3%    |
| 667     | 6         | 3.3%    |
| 3600    | 5         | 2.75%   |
| 533     | 3         | 1.65%   |
| 4199    | 2         | 1.1%    |
| 1867    | 2         | 1.1%    |
| 1866    | 2         | 1.1%    |
| 4267    | 1         | 0.55%   |
| 3733    | 1         | 0.55%   |
| 3533    | 1         | 0.55%   |
| 3266    | 1         | 0.55%   |
| 2666    | 1         | 0.55%   |
| 2267    | 1         | 0.55%   |
| 2048    | 1         | 0.55%   |
| 1800    | 1         | 0.55%   |
| 1200    | 1         | 0.55%   |
| 1066    | 1         | 0.55%   |
| 800     | 1         | 0.55%   |
| 266     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 3         | 50%     |
| Seiko Epson        | 1         | 16.67%  |
| Konica Minolta     | 1         | 16.67%  |
| Brother Industries | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson ET-2820 Series | 1         | 16.67%  |
| Konica Minolta 185         | 1         | 16.67%  |
| HP OfficeJet Pro 8730      | 1         | 16.67%  |
| HP OfficeJet 6200          | 1         | 16.67%  |
| HP DeskJet 2130 series     | 1         | 16.67%  |
| Brother MFC-L2685DW        | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 20.33%  |
| Microdia                               | 27        | 10.98%  |
| IMC Networks                           | 22        | 8.94%   |
| Sunplus Innovation Technology          | 16        | 6.5%    |
| Suyin                                  | 15        | 6.1%    |
| Realtek Semiconductor                  | 15        | 6.1%    |
| Quanta                                 | 12        | 4.88%   |
| Bison Electronics                      | 11        | 4.47%   |
| Luxvisions Innotech Limited            | 8         | 3.25%   |
| Logitech                               | 8         | 3.25%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.25%   |
| Acer                                   | 8         | 3.25%   |
| Apple                                  | 7         | 2.85%   |
| Syntek                                 | 6         | 2.44%   |
| Alcor Micro                            | 6         | 2.44%   |
| Importek                               | 3         | 1.22%   |
| Z-Star Microelectronics                | 2         | 0.81%   |
| Silicon Motion                         | 2         | 0.81%   |
| OmniVision Technologies                | 2         | 0.81%   |
| Lite-On Technology                     | 2         | 0.81%   |
| Lenovo                                 | 2         | 0.81%   |
| Huawei Technologies                    | 2         | 0.81%   |
| Creative Technology                    | 2         | 0.81%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.41%   |
| Samsung Electronics                    | 1         | 0.41%   |
| Pixart Imaging                         | 1         | 0.41%   |
| MacroSilicon                           | 1         | 0.41%   |
| Intel                                  | 1         | 0.41%   |
| icSpring                               | 1         | 0.41%   |
| eMPIA Technology                       | 1         | 0.41%   |
| ARC International                      | 1         | 0.41%   |
| Alpha Imaging Technology               | 1         | 0.41%   |
| ALi                                    | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 15        | 6.02%   |
| Microdia Integrated_Webcam_HD                                  | 14        | 5.62%   |
| IMC Networks Integrated Camera                                 | 6         | 2.41%   |
| Realtek USB Camera                                             | 5         | 2.01%   |
| Chicony HD Webcam                                              | 5         | 2.01%   |
| Acer Integrated Camera                                         | 5         | 2.01%   |
| Syntek Integrated Camera                                       | 4         | 1.61%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 1.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 1.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 4         | 1.61%   |
| Chicony HP TrueVision HD Camera                                | 4         | 1.61%   |
| Apple Built-in iSight                                          | 4         | 1.61%   |
| Sunplus HD WebCam                                              | 3         | 1.2%    |
| Sunplus 1080P Webcam                                           | 3         | 1.2%    |
| Realtek Lenovo EasyCamera                                      | 3         | 1.2%    |
| Microdia USB 2.0 Camera                                        | 3         | 1.2%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 3         | 1.2%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 1.2%    |
| Bison Integrated Camera                                        | 3         | 1.2%    |
| Suyin HP TrueVision HD                                         | 2         | 0.8%    |
| Suyin HD WebCam                                                | 2         | 0.8%    |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 2         | 0.8%    |
| Suyin Acer HD Crystal Eye webcam                               | 2         | 0.8%    |
| Sunplus Integrated_Webcam_HD                                   | 2         | 0.8%    |
| Quanta HP Webcam                                               | 2         | 0.8%    |
| Quanta HP HD Camera                                            | 2         | 0.8%    |
| Microdia Lenovo EasyCamera                                     | 2         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 2         | 0.8%    |
| Logitech Webcam C270                                           | 2         | 0.8%    |
| Lite-On HP TrueVision HD Camera                                | 2         | 0.8%    |
| IMC Networks EasyCamera                                        | 2         | 0.8%    |
| Huawei HiCamera                                                | 2         | 0.8%    |
| Chicony USB2.0 Camera                                          | 2         | 0.8%    |
| Chicony TOSHIBA Web Camera - FHD                               | 2         | 0.8%    |
| Chicony HP HD Camera                                           | 2         | 0.8%    |
| Chicony Camera                                                 | 2         | 0.8%    |
| Chicony 1.3M Webcam                                            | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 41.67%  |
| Synaptics                  | 4         | 11.11%  |
| AuthenTec                  | 4         | 11.11%  |
| Upek                       | 3         | 8.33%   |
| STMicroelectronics         | 2         | 5.56%   |
| Shenzhen Goodix Technology | 2         | 5.56%   |
| Focal-systems.Corp         | 2         | 5.56%   |
| Samsung Electronics        | 1         | 2.78%   |
| Microsoft                  | 1         | 2.78%   |
| LighTuning Technology      | 1         | 2.78%   |
| Elan Microelectronics      | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 8.33%   |
| Validity Sensors Synaptics WBDI                          | 2         | 5.56%   |
| Validity Sensors Fingerprint scanner                     | 2         | 5.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 5.56%   |
| STMicroelectronics Fingerprint Reader                    | 2         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 5.56%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 2         | 5.56%   |
| AuthenTec AES1600                                        | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 2.78%   |
| Validity Sensors VFS491                                  | 1         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 2.78%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 2.78%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 2.78%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 2.78%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 2.78%   |
| Synaptics WBDI                                           | 1         | 2.78%   |
| Synaptics UWP WBDI Device                                | 1         | 2.78%   |
| Samsung Fingerprint Sensor Device - 730B                 | 1         | 2.78%   |
| Microsoft Fingerprint Reader                             | 1         | 2.78%   |
| LighTuning Fingerprint Reader                            | 1         | 2.78%   |
| Elan ELAN:Fingerprint                                    | 1         | 2.78%   |
| AuthenTec Fingerprint Sensor                             | 1         | 2.78%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 53.33%  |
| Upek        | 2         | 13.33%  |
| O2 Micro    | 2         | 13.33%  |
| Alcor Micro | 2         | 13.33%  |
| Lenovo      | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 4         | 26.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 2         | 13.33%  |
| Broadcom 5880                                              | 2         | 13.33%  |
| Broadcom 58200                                             | 2         | 13.33%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 13.33%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 276       | 66.83%  |
| 1     | 115       | 27.85%  |
| 2     | 19        | 4.6%    |
| 4     | 2         | 0.48%   |
| 3     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 44        | 26.67%  |
| Graphics card            | 36        | 21.82%  |
| Fingerprint reader       | 35        | 21.21%  |
| Multimedia controller    | 19        | 11.52%  |
| Chipcard                 | 14        | 8.48%   |
| Communication controller | 4         | 2.42%   |
| Storage                  | 2         | 1.21%   |
| Camera                   | 2         | 1.21%   |
| Bluetooth                | 2         | 1.21%   |
| Unassigned class         | 1         | 0.61%   |
| Storage/raid             | 1         | 0.61%   |
| Sound                    | 1         | 0.61%   |
| Modem                    | 1         | 0.61%   |
| Flash memory             | 1         | 0.61%   |
| Dvb card                 | 1         | 0.61%   |
| Card reader              | 1         | 0.61%   |

