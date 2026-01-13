AlmaLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

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

Total: 119

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Inspiron 3793               | [14ececb143](https://linux-hardware.org/?probe=14ececb143) | Dec 13, 2025 |
| Lenovo    | ThinkPad P14s Gen 5 AMD ... | [6386a90620](https://linux-hardware.org/?probe=6386a90620) | Nov 30, 2025 |
| HP        | OMEN by Laptop 17-ck1xxx    | [81b19f590a](https://linux-hardware.org/?probe=81b19f590a) | Nov 01, 2025 |
| Lenovo    | ThinkPad P50 20EQS3B30R     | [9eb8122f08](https://linux-hardware.org/?probe=9eb8122f08) | Oct 30, 2025 |
| Dell      | Pro Max 16 MC16250          | [f17528762c](https://linux-hardware.org/?probe=f17528762c) | Sep 22, 2025 |
| Unknown   | Unknown                     | [b4a7dc6dea](https://linux-hardware.org/?probe=b4a7dc6dea) | Aug 17, 2025 |
| Lenovo    | G700 20251                  | [3abd3c98b9](https://linux-hardware.org/?probe=3abd3c98b9) | Jun 21, 2025 |
| HUAWEI    | BOD-WXX9                    | [094c7d11b2](https://linux-hardware.org/?probe=094c7d11b2) | Jun 11, 2025 |
| Samsung   | R530/R730/P530              | [d673085045](https://linux-hardware.org/?probe=d673085045) | May 15, 2025 |
| Lenovo    | Legion Slim 5 16AHP9 83D... | [a62025ce3c](https://linux-hardware.org/?probe=a62025ce3c) | May 12, 2025 |
| Dell      | Inspiron 15 3520            | [88d2d390ab](https://linux-hardware.org/?probe=88d2d390ab) | May 08, 2025 |
| Toshiba   | Satellite C50-A             | [1a6125c8e8](https://linux-hardware.org/?probe=1a6125c8e8) | Mar 09, 2025 |
| Lenovo    | ThinkPad X201 3249PJ2       | [4f11732833](https://linux-hardware.org/?probe=4f11732833) | Feb 10, 2025 |
| Lenovo    | ThinkPad X201 3249PJ2       | [7abf14106c](https://linux-hardware.org/?probe=7abf14106c) | Feb 10, 2025 |
| Lenovo    | ThinkPad E490 20N80019RT    | [f390dac47e](https://linux-hardware.org/?probe=f390dac47e) | Feb 06, 2025 |
| Acer      | TravelMate 5735Z            | [661c43dfab](https://linux-hardware.org/?probe=661c43dfab) | Jan 23, 2025 |
| ASUSTek   | G75VW                       | [b6fcb8b227](https://linux-hardware.org/?probe=b6fcb8b227) | Jan 08, 2025 |
| Lenovo    | ThinkPad T14s Gen 6 21M1... | [f05b1b8a31](https://linux-hardware.org/?probe=f05b1b8a31) | Dec 21, 2024 |
| Dell      | Vostro 3550                 | [3b5445782a](https://linux-hardware.org/?probe=3b5445782a) | Dec 12, 2024 |
| HUAWEI    | BOD-WXX9                    | [28a641e4dd](https://linux-hardware.org/?probe=28a641e4dd) | Nov 22, 2024 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [0a20cf1768](https://linux-hardware.org/?probe=0a20cf1768) | Nov 09, 2024 |
| HP        | Falco                       | [f270f62d2c](https://linux-hardware.org/?probe=f270f62d2c) | Nov 08, 2024 |
| ASUSTek   | ROG Zephyrus GX550LWS_GX... | [a73a429ab8](https://linux-hardware.org/?probe=a73a429ab8) | Oct 27, 2024 |
| Dell      | Latitude 7480               | [83e587119c](https://linux-hardware.org/?probe=83e587119c) | Oct 18, 2024 |
| ASUSTek   | Strix 15 GL503GE            | [550001d98f](https://linux-hardware.org/?probe=550001d98f) | Sep 20, 2024 |
| Lenovo    | ThinkPad E15 Gen 4 21E60... | [fa1b825886](https://linux-hardware.org/?probe=fa1b825886) | Sep 10, 2024 |
| Lenovo    | ThinkPad E15 Gen 4 21E60... | [9f2adb4d94](https://linux-hardware.org/?probe=9f2adb4d94) | Sep 10, 2024 |
| ASUSTek   | GL552VW                     | [2a780be401](https://linux-hardware.org/?probe=2a780be401) | Aug 14, 2024 |
| HP        | ENVY 15                     | [4b7e703303](https://linux-hardware.org/?probe=4b7e703303) | Jul 10, 2024 |
| Lenovo    | ThinkPad E470c 20H3A013C... | [3a0eb6920e](https://linux-hardware.org/?probe=3a0eb6920e) | Jul 08, 2024 |
| Lenovo    | ThinkPad W701 2541W12       | [85fd4bfe94](https://linux-hardware.org/?probe=85fd4bfe94) | Jul 06, 2024 |
| ASUSTek   | G75VW                       | [ab084dfd84](https://linux-hardware.org/?probe=ab084dfd84) | Jun 19, 2024 |
| Lenovo    | ThinkPad X390 20Q00039CD    | [1a88d526f1](https://linux-hardware.org/?probe=1a88d526f1) | Jun 16, 2024 |
| HP        | ENVY 15                     | [a7591276ca](https://linux-hardware.org/?probe=a7591276ca) | Jun 09, 2024 |
| ASUSTek   | GL552VW                     | [e29deb87ee](https://linux-hardware.org/?probe=e29deb87ee) | May 28, 2024 |
| Lenovo    | ThinkPad X1 Nano Gen 1 2... | [c5f9a761a9](https://linux-hardware.org/?probe=c5f9a761a9) | May 05, 2024 |
| Acer      | Aspire E1-571               | [0f3b954320](https://linux-hardware.org/?probe=0f3b954320) | May 02, 2024 |
| Toshiba   | Satellite C50-A             | [cabe5d7a20](https://linux-hardware.org/?probe=cabe5d7a20) | Apr 23, 2024 |
| Acer      | Aspire A315-59              | [f1c498121d](https://linux-hardware.org/?probe=f1c498121d) | Mar 13, 2024 |
| Toshiba   | Satellite C50-A             | [64c28ad883](https://linux-hardware.org/?probe=64c28ad883) | Mar 05, 2024 |
| Toshiba   | Satellite C50-A             | [2229c82401](https://linux-hardware.org/?probe=2229c82401) | Mar 03, 2024 |
| Dell      | Inspiron 5379               | [43522636f8](https://linux-hardware.org/?probe=43522636f8) | Mar 02, 2024 |
| Lenovo    | ThinkPad T480s 20L70028U... | [3ce277e7b9](https://linux-hardware.org/?probe=3ce277e7b9) | Feb 25, 2024 |
| ASUSTek   | GL552VW                     | [3d01ffb3f6](https://linux-hardware.org/?probe=3d01ffb3f6) | Feb 13, 2024 |
| Dell      | Inspiron 5379               | [ac5fe15861](https://linux-hardware.org/?probe=ac5fe15861) | Feb 12, 2024 |
| HP        | Falco                       | [9a82a5b9e8](https://linux-hardware.org/?probe=9a82a5b9e8) | Jan 26, 2024 |
| HP        | ENVY 15                     | [95ec6d10d0](https://linux-hardware.org/?probe=95ec6d10d0) | Jan 19, 2024 |
| Acer      | TravelMate 5735Z            | [6d759892ab](https://linux-hardware.org/?probe=6d759892ab) | Jan 12, 2024 |
| Acer      | TravelMate 5735Z            | [2ad65584c2](https://linux-hardware.org/?probe=2ad65584c2) | Jan 11, 2024 |
| HP        | Falco                       | [f6a8ee9181](https://linux-hardware.org/?probe=f6a8ee9181) | Jan 11, 2024 |
| Dell      | Precision 5680              | [82dc0a13bb](https://linux-hardware.org/?probe=82dc0a13bb) | Jan 10, 2024 |
| Timi      | TM1709                      | [f566951fd0](https://linux-hardware.org/?probe=f566951fd0) | Dec 14, 2023 |
| Lenovo    | ThinkPad X1 Carbon 6th 2... | [e5415e7df5](https://linux-hardware.org/?probe=e5415e7df5) | Dec 12, 2023 |
| AOCWEI    | A2                          | [ac8272a8a8](https://linux-hardware.org/?probe=ac8272a8a8) | Nov 26, 2023 |
| Acer      | Aspire E5-553               | [a8349dda46](https://linux-hardware.org/?probe=a8349dda46) | Nov 16, 2023 |
| Dell      | XPS 13 9360                 | [e0bc805f38](https://linux-hardware.org/?probe=e0bc805f38) | Nov 16, 2023 |
| AOCWEI    | A2                          | [1006e22f22](https://linux-hardware.org/?probe=1006e22f22) | Nov 09, 2023 |
| Toshiba   | Satellite C50-A             | [056e939d6d](https://linux-hardware.org/?probe=056e939d6d) | Nov 09, 2023 |
| Toshiba   | Satellite C50-A             | [6c8040c314](https://linux-hardware.org/?probe=6c8040c314) | Nov 08, 2023 |
| Notebook  | NS50_70MU                   | [ad21a28397](https://linux-hardware.org/?probe=ad21a28397) | Oct 28, 2023 |
| Notebook  | NS50_70MU                   | [166a51fa8d](https://linux-hardware.org/?probe=166a51fa8d) | Oct 27, 2023 |
| Dell      | Precision 7760              | [4b42c6c7f1](https://linux-hardware.org/?probe=4b42c6c7f1) | Oct 14, 2023 |
| HP        | Laptop 14-ep0xxx            | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo    | G580 20157                  | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| Dell      | Latitude E5420              | [0b1b042a5b](https://linux-hardware.org/?probe=0b1b042a5b) | Sep 19, 2023 |
| HP        | Notebook                    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| Dell      | Inspiron 5379               | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Dell      | Inspiron 5379               | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| Dell      | Latitude 5490               | [058fba578a](https://linux-hardware.org/?probe=058fba578a) | Aug 20, 2023 |
| Lenovo    | ThinkPad E14 Gen 2 20TBS... | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Timi      | RedmiBook 14-APCS           | [d8939be040](https://linux-hardware.org/?probe=d8939be040) | Aug 06, 2023 |
| HP        | 17-ak041ur                  | [5881affa24](https://linux-hardware.org/?probe=5881affa24) | Jul 18, 2023 |
| Dell      | Inspiron 5555               | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| Dell      | Inspiron 5555               | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| Dell      | Inspiron 5555               | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Maibenben | MaiBook X series            | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| Dell      | Inspiron 5555               | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| MSI       | GL75 9SE                    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| HP        | ZBook 17 G2                 | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| TUXEDO    | Aura 15 Gen1                | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO    | Aura 15 Gen1                | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Lenovo    | ThinkPad P1 Gen 4i 20Y30... | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Google    | Kefka                       | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Dell      | Inspiron 3501               | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Lenovo    | V14-ARE 82DQ                | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| HP        | Falco                       | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell      | Latitude E6510              | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| HP        | Falco                       | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| HP        | EliteBook 850 G8 Noteboo... | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo    | B50-30 20382                | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Lenovo    | Legion Y530-15ICH 81FV      | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| Toshiba   | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer      | TMP453-MG                   | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Acer      | TravelMate 5735Z            | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| HP        | Falco                       | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP        | Laptop 15-ef1xxx            | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP        | ENVY dv6                    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| HP        | Laptop 17-cp0xxx            | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| HP        | EliteBook 8470p             | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google    | Kohaku                      | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google    | Kohaku                      | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo    | ThinkPad T440s 20ARS32P0... | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Lenovo    | ThinkBook 13s-IWL 20R9      | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S1S... | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Intel     | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel     | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Dell      | Inspiron 3185               | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell      | Inspiron 3185               | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo    | Yoga 2 13 20344             | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo    | IdeaPad S145-15IWL 81MV     | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| HP        | EliteBook 8570w             | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek   | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo    | Legion 5 15IMH05H 81Y6      | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| Dell      | Inspiron 3185               | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell      | Inspiron 3185               | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell      | Inspiron 3185               | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| Lenovo    | IdeaPad 330-15ARR 81D2      | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| AlmaLinux 9.3  | 13        | 14.29%  |
| AlmaLinux 9.2  | 13        | 14.29%  |
| AlmaLinux 9.4  | 11        | 12.09%  |
| AlmaLinux 9.5  | 9         | 9.89%   |
| AlmaLinux 9.1  | 8         | 8.79%   |
| AlmaLinux 9.0  | 6         | 6.59%   |
| AlmaLinux 8.6  | 5         | 5.49%   |
| AlmaLinux 8.4  | 5         | 5.49%   |
| AlmaLinux 9.6  | 4         | 4.4%    |
| AlmaLinux 8.8  | 3         | 3.3%    |
| AlmaLinux 8.3  | 3         | 3.3%    |
| AlmaLinux 8.10 | 3         | 3.3%    |
| AlmaLinux 8.9  | 2         | 2.2%    |
| AlmaLinux 8.5  | 2         | 2.2%    |
| AlmaLinux 10.0 | 2         | 2.2%    |
| AlmaLinux 8.7  | 1         | 1.1%    |
| AlmaLinux 10.1 | 1         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| AlmaLinux | 80        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64    | 5         | 5.26%   |
| 5.14.0-362.8.1.el9_3.x86_64     | 4         | 4.21%   |
| 5.14.0-362.13.1.el9_3.x86_64    | 4         | 4.21%   |
| 5.14.0-284.25.1.el9_2.x86_64    | 4         | 4.21%   |
| 5.14.0-162.6.1.el9_1.x86_64     | 4         | 4.21%   |
| 5.14.0-503.40.1.el9_5.x86_64    | 3         | 3.16%   |
| 5.14.0-427.22.1.el9_4.x86_64    | 3         | 3.16%   |
| 5.14.0-362.18.1.el9_3.x86_64    | 3         | 3.16%   |
| 5.14.0-70.22.1.el9_0.x86_64     | 2         | 2.11%   |
| 5.14.0-70.13.1.el9_0.x86_64     | 2         | 2.11%   |
| 5.14.0-503.11.1.el9_5.x86_64    | 2         | 2.11%   |
| 5.14.0-362.24.2.el9_3.x86_64    | 2         | 2.11%   |
| 5.14.0-284.11.1.el9_2.x86_64    | 2         | 2.11%   |
| 5.14.0-162.18.1.el9_1.x86_64    | 2         | 2.11%   |
| 5.14.0-162.12.1.el9_1.x86_64    | 2         | 2.11%   |
| 4.18.0-372.26.1.el8_6.x86_64    | 2         | 2.11%   |
| 4.18.0-305.7.1.el8_4.x86_64     | 2         | 2.11%   |
| 4.18.0-240.15.1.el8_3.x86_64    | 2         | 2.11%   |
| 6.8.8-1.el8.elrepo.x86_64       | 1         | 1.05%   |
| 6.4.0-1.el8.elrepo.x86_64       | 1         | 1.05%   |
| 6.12.0-55.40.1.el10_0.x86_64    | 1         | 1.05%   |
| 6.12.0-55.25.1.el10_0.x86_64_v2 | 1         | 1.05%   |
| 6.12.0-124.8.1.el10_1.x86_64    | 1         | 1.05%   |
| 6.1.92-1.el9.elrepo.x86_64      | 1         | 1.05%   |
| 6.1.81-1.el9.elrepo.x86_64      | 1         | 1.05%   |
| 6.1.120-1.el9.elrepo.x86_64     | 1         | 1.05%   |
| 5.4.175-1.el8.elrepo.x86_64     | 1         | 1.05%   |
| 5.14.0-70.26.1.el9_0.x86_64     | 1         | 1.05%   |
| 5.14.0-70.17.1.el9_0.x86_64     | 1         | 1.05%   |
| 5.14.0-570.44.1.el9_6.x86_64    | 1         | 1.05%   |
| 5.14.0-570.22.1.el9_6.x86_64    | 1         | 1.05%   |
| 5.14.0-570.19.1.el9_6.x86_64    | 1         | 1.05%   |
| 5.14.0-503.26.1.el9_5.x86_64    | 1         | 1.05%   |
| 5.14.0-503.23.1.el9_5.x86_64    | 1         | 1.05%   |
| 5.14.0-503.15.1.el9_5.x86_64    | 1         | 1.05%   |
| 5.14.0-503.14.1.el9_5.x86_64    | 1         | 1.05%   |
| 5.14.0-427.42.1.el9_4.x86_64    | 1         | 1.05%   |
| 5.14.0-427.40.1.el9_4.x86_64    | 1         | 1.05%   |
| 5.14.0-427.37.1.el9_4.x86_64    | 1         | 1.05%   |
| 5.14.0-427.35.1.el9_4.x86_64    | 1         | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 54        | 65.06%  |
| 4.18.0  | 20        | 24.1%   |
| 6.12.0  | 3         | 3.61%   |
| 6.8.8   | 1         | 1.2%    |
| 6.4.0   | 1         | 1.2%    |
| 6.1.92  | 1         | 1.2%    |
| 6.1.81  | 1         | 1.2%    |
| 6.1.120 | 1         | 1.2%    |
| 5.4.175 | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 54        | 65.85%  |
| 4.18    | 20        | 24.39%  |
| 6.12    | 3         | 3.66%   |
| 6.1     | 2         | 2.44%   |
| 6.8     | 1         | 1.22%   |
| 6.4     | 1         | 1.22%   |
| 5.4     | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 55        | 67.9%   |
| KDE5            | 10        | 12.35%  |
| XFCE            | 6         | 7.41%   |
| MATE            | 6         | 7.41%   |
| GNOME Classic   | 2         | 2.47%   |
| GNOME Flashback | 1         | 1.23%   |
| Unknown         | 1         | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 54        | 65.85%  |
| X11     | 23        | 28.05%  |
| Tty     | 5         | 6.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 49.38%  |
| GDM     | 29        | 35.8%   |
| SDDM    | 6         | 7.41%   |
| LightDM | 6         | 7.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 42        | 52.5%   |
| de_DE | 9         | 11.25%  |
| pl_PL | 4         | 5%      |
| it_IT | 4         | 5%      |
| fr_FR | 3         | 3.75%   |
| en_GB | 3         | 3.75%   |
| C     | 3         | 3.75%   |
| ru_RU | 2         | 2.5%    |
| pt_BR | 1         | 1.25%   |
| nl_BE | 1         | 1.25%   |
| ko_KR | 1         | 1.25%   |
| ja_JP | 1         | 1.25%   |
| fr_BE | 1         | 1.25%   |
| es_VE | 1         | 1.25%   |
| es_ES | 1         | 1.25%   |
| en_IN | 1         | 1.25%   |
| en_IE | 1         | 1.25%   |
| en_CA | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 72.5%   |
| BIOS | 22        | 27.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Xfs   | 65        | 81.25%  |
| Ext4  | 14        | 17.5%   |
| Tmpfs | 1         | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 46.91%  |
| GPT     | 34        | 41.98%  |
| MBR     | 9         | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 90.12%  |
| Yes       | 8         | 9.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 87.5%   |
| Yes       | 10        | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 35%     |
| Dell                | 14        | 17.5%   |
| Hewlett-Packard     | 13        | 16.25%  |
| ASUSTek Computer    | 5         | 6.25%   |
| Acer                | 5         | 6.25%   |
| Toshiba             | 2         | 2.5%    |
| Timi                | 2         | 2.5%    |
| Google              | 2         | 2.5%    |
| TUXEDO              | 1         | 1.25%   |
| Samsung Electronics | 1         | 1.25%   |
| Notebook            | 1         | 1.25%   |
| MSI                 | 1         | 1.25%   |
| Maibenben           | 1         | 1.25%   |
| Intel               | 1         | 1.25%   |
| HUAWEI              | 1         | 1.25%   |
| AOCWEI              | 1         | 1.25%   |
| Unknown             | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                       | 1         | 1.25%   |
| Toshiba Satellite L50-C                   | 1         | 1.25%   |
| Toshiba Satellite C50-A                   | 1         | 1.25%   |
| Timi TM1709                               | 1         | 1.25%   |
| Timi RedmiBook 14-APCS                    | 1         | 1.25%   |
| Samsung R530/R730/P530                    | 1         | 1.25%   |
| Notebook NS50_70MU                        | 1         | 1.25%   |
| MSI GL75 9SE                              | 1         | 1.25%   |
| Maibenben MaiBook X series                | 1         | 1.25%   |
| Lenovo Yoga 2 13 20344                    | 1         | 1.25%   |
| Lenovo V14-ARE 82DQ                       | 1         | 1.25%   |
| Lenovo ThinkPad X390 20Q00039CD           | 1         | 1.25%   |
| Lenovo ThinkPad X201 3249PJ2              | 1         | 1.25%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UNS02500  | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT  | 1         | 1.25%   |
| Lenovo ThinkPad W701 2541W12              | 1         | 1.25%   |
| Lenovo ThinkPad T480s 20L70028US          | 1         | 1.25%   |
| Lenovo ThinkPad T440s 20ARS32P00          | 1         | 1.25%   |
| Lenovo ThinkPad T14s Gen 6 21M1CTO1WW     | 1         | 1.25%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00      | 1         | 1.25%   |
| Lenovo ThinkPad P50 20EQS3B30R            | 1         | 1.25%   |
| Lenovo ThinkPad P14s Gen 5 AMD 21ME001LUS | 1         | 1.25%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS      | 1         | 1.25%   |
| Lenovo ThinkPad E490 20N80019RT           | 1         | 1.25%   |
| Lenovo ThinkPad E470c 20H3A013CD          | 1         | 1.25%   |
| Lenovo ThinkPad E15 Gen 4 21E600CCMB      | 1         | 1.25%   |
| Lenovo ThinkPad E14 Gen 2 20TBS0CK00      | 1         | 1.25%   |
| Lenovo Legion Y530-15ICH 81FV             | 1         | 1.25%   |
| Lenovo Legion Slim 5 16AHP9 83DH          | 1         | 1.25%   |
| Lenovo Legion 5 15IMH05H 81Y6             | 1         | 1.25%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 1.25%   |
| Lenovo IdeaPad S145-15IWL 81MV            | 1         | 1.25%   |
| Lenovo IdeaPad 330-15ARR 81D2             | 1         | 1.25%   |
| Lenovo IdeaPad 3 15IIL05 81WE             | 1         | 1.25%   |
| Lenovo G700 20251                         | 1         | 1.25%   |
| Lenovo G580 20157                         | 1         | 1.25%   |
| Lenovo B50-30 20382                       | 1         | 1.25%   |
| Intel powered classmate PC                | 1         | 1.25%   |
| HUAWEI BOD-WXX9                           | 1         | 1.25%   |
| HP ZBook 17 G2                            | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 16        | 20%     |
| Dell Inspiron     | 5         | 6.25%   |
| Lenovo IdeaPad    | 4         | 5%      |
| Dell Latitude     | 4         | 5%      |
| Lenovo Legion     | 3         | 3.75%   |
| HP Laptop         | 3         | 3.75%   |
| HP EliteBook      | 3         | 3.75%   |
| Acer Aspire       | 3         | 3.75%   |
| Toshiba Satellite | 2         | 2.5%    |
| HP ENVY           | 2         | 2.5%    |
| Dell Precision    | 2         | 2.5%    |
| TUXEDO Aura       | 1         | 1.25%   |
| Timi TM1709       | 1         | 1.25%   |
| Timi RedmiBook    | 1         | 1.25%   |
| Samsung R530      | 1         | 1.25%   |
| Notebook NS50     | 1         | 1.25%   |
| MSI GL75          | 1         | 1.25%   |
| Maibenben MaiBook | 1         | 1.25%   |
| Lenovo Yoga       | 1         | 1.25%   |
| Lenovo V14-ARE    | 1         | 1.25%   |
| Lenovo G700       | 1         | 1.25%   |
| Lenovo G580       | 1         | 1.25%   |
| Lenovo B50-30     | 1         | 1.25%   |
| Intel powered     | 1         | 1.25%   |
| HUAWEI BOD-WXX9   | 1         | 1.25%   |
| HP ZBook          | 1         | 1.25%   |
| HP OMEN           | 1         | 1.25%   |
| HP Notebook       | 1         | 1.25%   |
| HP Falco          | 1         | 1.25%   |
| HP 17-ak041ur     | 1         | 1.25%   |
| Google Kohaku     | 1         | 1.25%   |
| Google Kefka      | 1         | 1.25%   |
| Dell XPS          | 1         | 1.25%   |
| Dell Vostro       | 1         | 1.25%   |
| Dell Pro          | 1         | 1.25%   |
| ASUS Strix        | 1         | 1.25%   |
| ASUS ROG          | 1         | 1.25%   |
| ASUS GL552VW      | 1         | 1.25%   |
| ASUS G75VW        | 1         | 1.25%   |
| ASUS ASUS         | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 14        | 17.5%   |
| 2018 | 9         | 11.25%  |
| 2019 | 8         | 10%     |
| 2022 | 6         | 7.5%    |
| 2012 | 6         | 7.5%    |
| 2011 | 5         | 6.25%   |
| 2010 | 5         | 6.25%   |
| 2023 | 4         | 5%      |
| 2015 | 4         | 5%      |
| 2013 | 4         | 5%      |
| 2024 | 3         | 3.75%   |
| 2021 | 3         | 3.75%   |
| 2017 | 3         | 3.75%   |
| 2014 | 3         | 3.75%   |
| 2016 | 2         | 2.5%    |
| 2025 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 80        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 71        | 87.65%  |
| Enabled  | 10        | 12.35%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 96.25%  |
| Yes  | 3         | 3.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 27        | 33.75%  |
| 4.01-8.0    | 24        | 30%     |
| 3.01-4.0    | 10        | 12.5%   |
| 32.01-64.0  | 6         | 7.5%    |
| 16.01-24.0  | 6         | 7.5%    |
| 24.01-32.0  | 3         | 3.75%   |
| 64.01-256.0 | 2         | 2.5%    |
| 1.01-2.0    | 2         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 25        | 28.41%  |
| 3.01-4.0  | 20        | 22.73%  |
| 1.01-2.0  | 19        | 21.59%  |
| 4.01-8.0  | 17        | 19.32%  |
| 8.01-16.0 | 4         | 4.55%   |
| 0.51-1.0  | 3         | 3.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 69.51%  |
| 2      | 22        | 26.83%  |
| 3      | 2         | 2.44%   |
| 0      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 75%     |
| Yes       | 20        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 80.25%  |
| No        | 16        | 19.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 96.25%  |
| No        | 3         | 3.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 83.95%  |
| No        | 13        | 16.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 19        | 23.75%  |
| Germany      | 10        | 12.5%   |
| Italy        | 5         | 6.25%   |
| Poland       | 4         | 5%      |
| France       | 4         | 5%      |
| Spain        | 3         | 3.75%   |
| Russia       | 3         | 3.75%   |
| Indonesia    | 3         | 3.75%   |
| India        | 3         | 3.75%   |
| China        | 3         | 3.75%   |
| Canada       | 3         | 3.75%   |
| Belgium      | 3         | 3.75%   |
| South Africa | 2         | 2.5%    |
| Netherlands  | 2         | 2.5%    |
| Venezuela    | 1         | 1.25%   |
| UK           | 1         | 1.25%   |
| Sweden       | 1         | 1.25%   |
| South Korea  | 1         | 1.25%   |
| Romania      | 1         | 1.25%   |
| Puerto Rico  | 1         | 1.25%   |
| Pakistan     | 1         | 1.25%   |
| Mexico       | 1         | 1.25%   |
| Japan        | 1         | 1.25%   |
| Hungary      | 1         | 1.25%   |
| Bulgaria     | 1         | 1.25%   |
| Brazil       | 1         | 1.25%   |
| Bangladesh   | 1         | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Hamburg            | 4         | 4.76%   |
| Queens             | 2         | 2.38%   |
| Milano             | 2         | 2.38%   |
| Los Angeles        | 2         | 2.38%   |
| Johannesburg       | 2         | 2.38%   |
| Dresden            | 2         | 2.38%   |
| Berlin             | 2         | 2.38%   |
| Yokohama           | 1         | 1.19%   |
| Winterswijk        | 1         | 1.19%   |
| Wejherowo          | 1         | 1.19%   |
| Warsaw             | 1         | 1.19%   |
| Wandlitz           | 1         | 1.19%   |
| Uppsala            | 1         | 1.19%   |
| Thiruvananthapuram | 1         | 1.19%   |
| Tampa              | 1         | 1.19%   |
| Suzhou             | 1         | 1.19%   |
| South Tangerang    | 1         | 1.19%   |
| Sofia              | 1         | 1.19%   |
| Seville            | 1         | 1.19%   |
| Sao Paulo          | 1         | 1.19%   |
| Saint-Brieuc       | 1         | 1.19%   |
| Rome               | 1         | 1.19%   |
| Regina             | 1         | 1.19%   |
| Redlands           | 1         | 1.19%   |
| Pikesville         | 1         | 1.19%   |
| Penza              | 1         | 1.19%   |
| Parla              | 1         | 1.19%   |
| Paris              | 1         | 1.19%   |
| Ottawa             | 1         | 1.19%   |
| Minneapolis        | 1         | 1.19%   |
| Milan              | 1         | 1.19%   |
| Mangalore          | 1         | 1.19%   |
| Malang             | 1         | 1.19%   |
| Lübeck            | 1         | 1.19%   |
| Lipetsk            | 1         | 1.19%   |
| Lille              | 1         | 1.19%   |
| Leighton Buzzard   | 1         | 1.19%   |
| Land O' Lakes      | 1         | 1.19%   |
| Lahore             | 1         | 1.19%   |
| Lafayette          | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 13        | 14     | 13%     |
| Seagate                     | 8         | 8      | 8%      |
| WDC                         | 7         | 8      | 7%      |
| SK hynix                    | 7         | 9      | 7%      |
| Sandisk                     | 5         | 5      | 5%      |
| KIOXIA                      | 4         | 4      | 4%      |
| Intel                       | 4         | 5      | 4%      |
| Hitachi                     | 4         | 5      | 4%      |
| Unknown                     | 3         | 4      | 3%      |
| Micron Technology           | 3         | 3      | 3%      |
| Kingston Technology Company | 3         | 4      | 3%      |
| Kingston                    | 3         | 3      | 3%      |
| Crucial                     | 3         | 4      | 3%      |
| Toshiba                     | 2         | 5      | 2%      |
| Plextor                     | 2         | 2      | 2%      |
| Phison Electronics          | 2         | 2      | 2%      |
| Netac                       | 2         | 2      | 2%      |
| LITEONIT                    | 2         | 6      | 2%      |
| HGST                        | 2         | 4      | 2%      |
| A-DATA Technology           | 2         | 2      | 2%      |
| WUXIN                       | 1         | 1      | 1%      |
| Union Memory                | 1         | 1      | 1%      |
| Transcend                   | 1         | 1      | 1%      |
| T-FORCE                     | 1         | 2      | 1%      |
| SSSTC                       | 1         | 1      | 1%      |
| Silicon Motion              | 1         | 2      | 1%      |
| Realtek Semiconductor       | 1         | 1      | 1%      |
| Patriot                     | 1         | 3      | 1%      |
| MidasForce                  | 1         | 3      | 1%      |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1%      |
| Lite-On Technology          | 1         | 1      | 1%      |
| Lenovo                      | 1         | 1      | 1%      |
| JMicron Technology          | 1         | 1      | 1%      |
| Intenso                     | 1         | 1      | 1%      |
| HJDK                        | 1         | 1      | 1%      |
| Emtec                       | 1         | 2      | 1%      |
| Dell                        | 1         | 2      | 1%      |
| China                       | 1         | 1      | 1%      |
| ASMT                        | 1         | 2      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| SK hynix SC311 SATA 256GB                         | 3         | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 2.94%   |
| WDC WD10SPZX-24Z10 1TB                            | 2         | 1.96%   |
| Unknown SD/MMC/MS PRO 2GB                         | 2         | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB                    | 2         | 1.96%   |
| Samsung SSD 870 EVO 500GB                         | 2         | 1.96%   |
| Phison PS5013 E13 NVMe Controller 500GB           | 2         | 1.96%   |
| KIOXIA KXG8AZNV1T02 LA 1024GB                     | 2         | 1.96%   |
| Kingston Company SNV2S1000G 1TB                   | 2         | 1.96%   |
| HGST HTS541010A9E680 1TB                          | 2         | 1.96%   |
| WUXIN G8 128GB                                    | 1         | 0.98%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.98%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 0.98%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.98%   |
| WDC WD10JPVX-00JC3T0 1TB                          | 1         | 0.98%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB              | 1         | 0.98%   |
| Unknown MMC Card  16GB                            | 1         | 0.98%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB           | 1         | 0.98%   |
| Transcend TS256GMTE220S 256GB                     | 1         | 0.98%   |
| Toshiba MQ01ABD075 752GB                          | 1         | 0.98%   |
| Toshiba MK6475GSX 640GB                           | 1         | 0.98%   |
| T-FORCE 1TB                                       | 1         | 0.98%   |
| SSSTC CL1-3D256 256GB                             | 1         | 0.98%   |
| SK hynix SKHynix_HFS512GEJ9X115N 512GB            | 1         | 0.98%   |
| SK hynix PC801 NVMe 1TB                           | 1         | 0.98%   |
| SK hynix NVMe SSD Drive 256GB                     | 1         | 0.98%   |
| SK hynix BC511 NVMe 256GB                         | 1         | 0.98%   |
| Silicon Motion PCIe-8 SSD 256GB                   | 1         | 0.98%   |
| Seagate ST9500423AS 500GB                         | 1         | 0.98%   |
| Seagate ST9500325AS 500GB                         | 1         | 0.98%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 0.98%   |
| Seagate ST250LM004 HN-M250MBB 250GB               | 1         | 0.98%   |
| Seagate ST1000LX015-1U7172 1TB                    | 1         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 0.98%   |
| Sandisk WD PC SN740 SDDQMQD-512G-1001 512GB       | 1         | 0.98%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB             | 1         | 0.98%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB   | 1         | 0.98%   |
| SanDisk SD8TN8U512G1001 512GB SSD                 | 1         | 0.98%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD               | 1         | 0.98%   |
| Samsung SSD PM810 FDE 2.5 256GB                   | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 30.77%  |
| WDC     | 6         | 7      | 23.08%  |
| Hitachi | 4         | 5      | 15.38%  |
| Unknown | 2         | 3      | 7.69%   |
| Toshiba | 2         | 5      | 7.69%   |
| HGST    | 2         | 4      | 7.69%   |
| T-FORCE | 1         | 2      | 3.85%   |
| ASMT    | 1         | 2      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 12.5%   |
| SK hynix            | 3         | 5      | 9.38%   |
| Kingston            | 3         | 3      | 9.38%   |
| Crucial             | 3         | 4      | 9.38%   |
| SanDisk             | 2         | 2      | 6.25%   |
| Plextor             | 2         | 2      | 6.25%   |
| LITEONIT            | 2         | 6      | 6.25%   |
| Intel               | 2         | 3      | 6.25%   |
| A-DATA Technology   | 2         | 2      | 6.25%   |
| WUXIN               | 1         | 1      | 3.13%   |
| Patriot             | 1         | 3      | 3.13%   |
| Netac               | 1         | 1      | 3.13%   |
| MidasForce          | 1         | 3      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| Intenso             | 1         | 1      | 3.13%   |
| HJDK                | 1         | 1      | 3.13%   |
| Dell                | 1         | 2      | 3.13%   |
| China               | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 36        | 42     | 37.89%  |
| SSD     | 30        | 45     | 31.58%  |
| HDD     | 26        | 36     | 27.37%  |
| Unknown | 2         | 3      | 2.11%   |
| MMC     | 1         | 1      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 76     | 54.44%  |
| NVMe | 36        | 42     | 40%     |
| SAS  | 4         | 8      | 4.44%   |
| MMC  | 1         | 1      | 1.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 51     | 65.45%  |
| 0.51-1.0   | 17        | 25     | 30.91%  |
| 1.01-2.0   | 2         | 5      | 3.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 28        | 34.15%  |
| 251-500    | 21        | 25.61%  |
| 501-1000   | 15        | 18.29%  |
| 1001-2000  | 7         | 8.54%   |
| 51-100     | 6         | 7.32%   |
| 1-20       | 3         | 3.66%   |
| 21-50      | 2         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 38        | 44.19%  |
| 21-50    | 19        | 22.09%  |
| 101-250  | 12        | 13.95%  |
| 51-100   | 10        | 11.63%  |
| 251-500  | 6         | 6.98%   |
| 501-1000 | 1         | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| LITEONIT LSS-16L6G-HP 16GB SSD | 1         | 5      | 25%     |
| Hitachi HTS545050B9A300 500GB  | 1         | 1      | 25%     |
| Hitachi HTS545050A7E380 500GB  | 1         | 1      | 25%     |
| HGST HTS541010A9E680 1TB       | 1         | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Hitachi  | 2         | 2      | 50%     |
| LITEONIT | 1         | 5      | 25%     |
| HGST     | 1         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 66.67%  |
| HGST    | 1         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 75%     |
| SSD  | 1         | 5      | 25%     |

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
| Detected | 41        | 65     | 49.4%   |
| Works    | 38        | 53     | 45.78%  |
| Malfunc  | 4         | 9      | 4.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 50        | 52.08%  |
| Samsung Electronics            | 9         | 9.38%   |
| AMD                            | 8         | 8.33%   |
| Sandisk                        | 4         | 4.17%   |
| SK hynix                       | 3         | 3.13%   |
| KIOXIA                         | 3         | 3.13%   |
| Kingston Technology Company    | 3         | 3.13%   |
| Union Memory (Shenzhen)        | 2         | 2.08%   |
| Silicon Motion                 | 2         | 2.08%   |
| Phison Electronics             | 2         | 2.08%   |
| Micron Technology              | 2         | 2.08%   |
| Toshiba America Info Systems   | 1         | 1.04%   |
| Solid State Storage Technology | 1         | 1.04%   |
| Realtek Semiconductor          | 1         | 1.04%   |
| Netac Technology               | 1         | 1.04%   |
| MAXIO Technology (Hangzhou)    | 1         | 1.04%   |
| Marvell Technology Group       | 1         | 1.04%   |
| Lite-On Technology             | 1         | 1.04%   |
| Lenovo                         | 1         | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 8         | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 6         | 6%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 5%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 5         | 5%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 4         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 4         | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 3%      |
| Intel Volume Management Device NVMe RAID Controller                          | 3         | 3%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 3         | 3%      |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                           | 2         | 2%      |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 2         | 2%      |
| KIOXIA NVMe SSD Controller XG8                                               | 2         | 2%      |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                         | 2         | 2%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 2%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 2%      |
| Intel Alder Lake-P SATA AHCI Controller                                      | 2         | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 2%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 2%      |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB              | 1         | 1%      |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                        | 1         | 1%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 1%      |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 1         | 1%      |
| SK hynix BC511 NVMe SSD                                                      | 1         | 1%      |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1%      |
| Silicon Motion Non-Volatile memory controller                                | 1         | 1%      |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                               | 1         | 1%      |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 1         | 1%      |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)    | 1         | 1%      |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 1%      |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                  | 1         | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 1%      |
| Realtek RTS5763DL x2 NVMe SSD Controller                                     | 1         | 1%      |
| Netac NV3000 NVMe SSD (DRAM-less)                                            | 1         | 1%      |
| Micron 3400 NVMe SSD [Hendrix]                                               | 1         | 1%      |
| Micron 2650 NVMe SSD (DRAM-less)                                             | 1         | 1%      |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                     | 1         | 1%      |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 1%      |
| Lite-On CX2-8B256, CX2-8B512 NVMe SSD                                        | 1         | 1%      |
| Lenovo LENSE30512GMSP34MEAT3TA                                               | 1         | 1%      |
| KIOXIA NVMe SSD Controller XG7                                               | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 51.06%  |
| NVMe | 36        | 38.3%   |
| RAID | 9         | 9.57%   |
| IDE  | 1         | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 81.25%  |
| AMD    | 15        | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 3.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 2         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.5%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 2.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 2.5%    |
| Intel 12th Gen Core i3-1215U                | 2         | 2.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.5%    |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 1.25%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.25%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.25%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.25%   |
| Intel Pentium CPU 3825U @ 1.90GHz           | 1         | 1.25%   |
| Intel Core Ultra 7 265H                     | 1         | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.25%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.25%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.25%   |
| Intel Core i7-7560U CPU @ 2.40GHz           | 1         | 1.25%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.25%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.25%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.25%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.25%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.25%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.25%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.25%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.25%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 1.25%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.25%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.25%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.25%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.25%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 1.25%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.25%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 22.5%   |
| Intel Core i7           | 17        | 21.25%  |
| Other                   | 14        | 17.5%   |
| Intel Core i3           | 7         | 8.75%   |
| AMD Ryzen 7             | 5         | 6.25%   |
| Intel Celeron           | 4         | 5%      |
| Intel Pentium           | 3         | 3.75%   |
| AMD Ryzen 5             | 2         | 2.5%    |
| AMD A12                 | 2         | 2.5%    |
| Intel Xeon              | 1         | 1.25%   |
| Intel Pentium Dual-Core | 1         | 1.25%   |
| Intel Core              | 1         | 1.25%   |
| Intel Atom              | 1         | 1.25%   |
| AMD Ryzen 7 PRO         | 1         | 1.25%   |
| AMD Ryzen 3             | 1         | 1.25%   |
| AMD A6                  | 1         | 1.25%   |
| AMD A10                 | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 41.25%  |
| 4      | 26        | 32.5%   |
| 8      | 8         | 10%     |
| 6      | 7         | 8.75%   |
| 14     | 2         | 2.5%    |
| 10     | 2         | 2.5%    |
| 16     | 1         | 1.25%   |
| 1      | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 68        | 85%     |
| 1      | 12        | 15%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 80        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 42.86%  |
| 0x306a9    | 5         | 5.95%   |
| 0x806ec    | 4         | 4.76%   |
| 0x806c1    | 3         | 3.57%   |
| 0x40651    | 3         | 3.57%   |
| 0x806ea    | 2         | 2.38%   |
| 0x806d1    | 2         | 2.38%   |
| 0x206a7    | 2         | 2.38%   |
| 0x08600106 | 2         | 2.38%   |
| 0x08108109 | 2         | 2.38%   |
| 0x0600611a | 2         | 2.38%   |
| 0xb06a3    | 1         | 1.19%   |
| 0xa0652    | 1         | 1.19%   |
| 0x906ed    | 1         | 1.19%   |
| 0x906ea    | 1         | 1.19%   |
| 0x906a4    | 1         | 1.19%   |
| 0x806e9    | 1         | 1.19%   |
| 0x406e3    | 1         | 1.19%   |
| 0x406c4    | 1         | 1.19%   |
| 0x306d4    | 1         | 1.19%   |
| 0x306c3    | 1         | 1.19%   |
| 0x30678    | 1         | 1.19%   |
| 0x30673    | 1         | 1.19%   |
| 0x20655    | 1         | 1.19%   |
| 0x106ca    | 1         | 1.19%   |
| 0x1067a    | 1         | 1.19%   |
| 0x0a50000c | 1         | 1.19%   |
| 0x08608103 | 1         | 1.19%   |
| 0x0810100b | 1         | 1.19%   |
| 0x06006705 | 1         | 1.19%   |
| 0x06006704 | 1         | 1.19%   |
| 0x06006110 | 1         | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 16        | 20%     |
| IvyBridge        | 7         | 8.75%   |
| Alderlake Hybrid | 6         | 7.5%    |
| TigerLake        | 5         | 6.25%   |
| Haswell          | 5         | 6.25%   |
| Excavator        | 5         | 6.25%   |
| Unknown          | 5         | 6.25%   |
| Skylake          | 4         | 5%      |
| Silvermont       | 4         | 5%      |
| IceLake          | 4         | 5%      |
| Westmere         | 3         | 3.75%   |
| SandyBridge      | 3         | 3.75%   |
| Zen+             | 2         | 2.5%    |
| Zen 2            | 2         | 2.5%    |
| CometLake        | 2         | 2.5%    |
| Zen 3            | 1         | 1.25%   |
| Zen              | 1         | 1.25%   |
| Penryn           | 1         | 1.25%   |
| Nehalem          | 1         | 1.25%   |
| Goldmont plus    | 1         | 1.25%   |
| Broadwell        | 1         | 1.25%   |
| Bonnell          | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 59%     |
| Nvidia | 24        | 24%     |
| AMD    | 17        | 17%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 5         | 4.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.97%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 2.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.98%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 2         | 1.98%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 2         | 1.98%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 1.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.98%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 2         | 1.98%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.98%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.98%   |
| AMD HawkPoint1                                                                           | 2         | 1.98%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.99%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.99%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.99%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.99%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.99%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.99%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.99%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.99%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.99%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.99%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.99%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 0.99%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.99%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 51.25%  |
| Intel + Nvidia | 16        | 20%     |
| 1 x AMD        | 12        | 15%     |
| 1 x Nvidia     | 6         | 7.5%    |
| Intel + AMD    | 2         | 2.5%    |
| AMD + Nvidia   | 2         | 2.5%    |
| 2 x AMD        | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 72        | 87.8%   |
| Proprietary | 7         | 8.54%   |
| Unknown     | 3         | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 64.2%   |
| 0.01-0.5   | 11        | 13.58%  |
| 5.01-6.0   | 5         | 6.17%   |
| 1.01-2.0   | 5         | 6.17%   |
| 3.01-4.0   | 4         | 4.94%   |
| 0.51-1.0   | 3         | 3.7%    |
| 7.01-8.0   | 1         | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 17        | 19.54%  |
| AU Optronics            | 16        | 18.39%  |
| LG Display              | 13        | 14.94%  |
| Chimei Innolux          | 9         | 10.34%  |
| Samsung Electronics     | 8         | 9.2%    |
| PANDA                   | 5         | 5.75%   |
| Lenovo                  | 3         | 3.45%   |
| InfoVision              | 3         | 3.45%   |
| Chi Mei Optoelectronics | 3         | 3.45%   |
| Sharp                   | 2         | 2.3%    |
| Dell                    | 2         | 2.3%    |
| BenQ                    | 2         | 2.3%    |
| Seiki                   | 1         | 1.15%   |
| HannStar                | 1         | 1.15%   |
| CSOT                    | 1         | 1.15%   |
| BOE Technology Group    | 1         | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 2.27%   |
| BenQ BL902 BNQ8008 1280x1024 376x301mm 19.0-inch                      | 2         | 2.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 2.27%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 2.27%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 1.14%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch               | 1         | 1.14%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                   | 1         | 1.14%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC4164 3840x2400 344x215mm 16.0-inch | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 1.14%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 1.14%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 1         | 1.14%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch               | 1         | 1.14%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 1.14%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.14%   |
| PANDA LCD Monitor NCP002A 1920x1080 344x194mm 15.5-inch               | 1         | 1.14%   |
| LG Display LCD Monitor LGD07A8 1920x1200 345x215mm 16.0-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch           | 1         | 1.14%   |
| Lenovo LCD Monitor LEN406A 1920x1200 367x230mm 17.1-inch              | 1         | 1.14%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.14%   |
| Lenovo B140UAN02.7 LEN403A 1920x1200 302x188mm 14.0-inch              | 1         | 1.14%   |
| InfoVision LCD Monitor IVO8C39 1920x1200 300x190mm 14.0-inch          | 1         | 1.14%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch          | 1         | 1.14%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.14%   |
| HannStar LCD Monitor HSD0001 1920x1080 309x174mm 14.0-inch            | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 49        | 56.98%  |
| 1366x768 (WXGA)   | 17        | 19.77%  |
| 1920x1200 (WUXGA) | 4         | 4.65%   |
| 1600x900 (HD+)    | 4         | 4.65%   |
| 3840x2160 (4K)    | 3         | 3.49%   |
| 2560x1600         | 2         | 2.33%   |
| 1280x1024 (SXGA)  | 2         | 2.33%   |
| 3840x2400         | 1         | 1.16%   |
| 3840x1100         | 1         | 1.16%   |
| 3200x1800 (QHD+)  | 1         | 1.16%   |
| 2160x1350         | 1         | 1.16%   |
| 1280x800 (WXGA)   | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 35.23%  |
| 14      | 14        | 15.91%  |
| 13      | 14        | 15.91%  |
| 17      | 12        | 13.64%  |
| 16      | 4         | 4.55%   |
| 31      | 3         | 3.41%   |
| 19      | 2         | 2.27%   |
| 11      | 2         | 2.27%   |
| 40      | 1         | 1.14%   |
| 27      | 1         | 1.14%   |
| 24      | 1         | 1.14%   |
| 21      | 1         | 1.14%   |
| 12      | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 64.37%  |
| 351-400     | 14        | 16.09%  |
| 201-300     | 9         | 10.34%  |
| 601-700     | 3         | 3.45%   |
| 501-600     | 2         | 2.3%    |
| 801-900     | 1         | 1.15%   |
| 401-500     | 1         | 1.15%   |
| Unknown     | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 69        | 84.15%  |
| 16/10   | 8         | 9.76%   |
| 5/4     | 2         | 2.44%   |
| 3/2     | 1         | 1.22%   |
| 3.40    | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 35.23%  |
| 81-90          | 21        | 23.86%  |
| 121-130        | 9         | 10.23%  |
| 71-80          | 6         | 6.82%   |
| 111-120        | 4         | 4.55%   |
| 51-60          | 3         | 3.41%   |
| 351-500        | 3         | 3.41%   |
| 131-140        | 3         | 3.41%   |
| 201-250        | 2         | 2.27%   |
| 151-200        | 2         | 2.27%   |
| 61-70          | 1         | 1.14%   |
| 301-350        | 1         | 1.14%   |
| 501-1000       | 1         | 1.14%   |
| Unknown        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 45        | 52.33%  |
| 101-120       | 19        | 22.09%  |
| 161-240       | 8         | 9.3%    |
| 51-100        | 7         | 8.14%   |
| More than 240 | 5         | 5.81%   |
| 1-50          | 1         | 1.16%   |
| Unknown       | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 70        | 86.42%  |
| 2     | 9         | 11.11%  |
| 0     | 2         | 2.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 33.06%  |
| Realtek Semiconductor           | 39        | 31.45%  |
| Qualcomm Atheros                | 20        | 16.13%  |
| Broadcom                        | 5         | 4.03%   |
| Broadcom Limited                | 4         | 3.23%   |
| TP-Link                         | 3         | 2.42%   |
| Samsung Electronics             | 2         | 1.61%   |
| MediaTek                        | 2         | 1.61%   |
| Sierra Wireless                 | 1         | 0.81%   |
| Ralink Technology               | 1         | 0.81%   |
| Qualcomm Technologies           | 1         | 0.81%   |
| Qualcomm Atheros Communications | 1         | 0.81%   |
| Qualcomm                        | 1         | 0.81%   |
| Marvell Technology Group        | 1         | 0.81%   |
| Lenovo                          | 1         | 0.81%   |
| ASIX Electronics                | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23        | 15.03%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 3.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 3.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 3.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.61%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.61%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.96%   |
| Intel Wireless 7260                                                    | 3         | 1.96%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.96%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 1.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.31%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.31%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.31%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 1.31%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1         | 0.65%   |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.65%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.65%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 45.12%  |
| Qualcomm Atheros                | 18        | 21.95%  |
| Realtek Semiconductor           | 14        | 17.07%  |
| Broadcom                        | 4         | 4.88%   |
| Broadcom Limited                | 2         | 2.44%   |
| TP-Link                         | 1         | 1.22%   |
| Sierra Wireless                 | 1         | 1.22%   |
| Ralink Technology               | 1         | 1.22%   |
| Qualcomm Technologies           | 1         | 1.22%   |
| Qualcomm Atheros Communications | 1         | 1.22%   |
| Qualcomm                        | 1         | 1.22%   |
| MediaTek                        | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 6         | 7.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 5         | 6.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 5         | 6.1%    |
| Intel Wireless 8265 / 8275                                       | 4         | 4.88%   |
| Intel Wi-Fi 6 AX201                                              | 4         | 4.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 3         | 3.66%   |
| Intel Wireless 7260                                              | 3         | 3.66%   |
| Intel Wi-Fi 6 AX200                                              | 3         | 3.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                | 3         | 3.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 2         | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 2         | 2.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]        | 2         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 2         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                   | 2         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 2         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                           | 1         | 1.22%   |
| Sierra Wireless EM7345 4G LTE                                    | 1         | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 1         | 1.22%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1.22%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter              | 1         | 1.22%   |
| Realtek RTL8723DE Wireless Network Adapter                       | 1         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 1.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                      | 1         | 1.22%   |
| Ralink MT7601U Wireless Adapter                                  | 1         | 1.22%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800] | 1         | 1.22%   |
| Qualcomm QCNFA765 Wireless Network Adapter                       | 1         | 1.22%   |
| Qualcomm Atheros AR9271 802.11n                                  | 1         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1         | 1.22%   |
| MediaTek MT7663 802.11ac PCI Express Wireless Network Adapter    | 1         | 1.22%   |
| Intel Wireless 8260                                              | 1         | 1.22%   |
| Intel Wireless 7265                                              | 1         | 1.22%   |
| Intel Wireless 3165                                              | 1         | 1.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]          | 1         | 1.22%   |
| Intel Raptor Lake PCH CNVi WiFi                                  | 1         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1.22%   |
| Intel Centrino Wireless-N 2230                                   | 1         | 1.22%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 50.75%  |
| Intel                    | 18        | 26.87%  |
| Qualcomm Atheros         | 4         | 5.97%   |
| TP-Link                  | 2         | 2.99%   |
| Samsung Electronics      | 2         | 2.99%   |
| Broadcom Limited         | 2         | 2.99%   |
| MediaTek                 | 1         | 1.49%   |
| Marvell Technology Group | 1         | 1.49%   |
| Lenovo                   | 1         | 1.49%   |
| Broadcom                 | 1         | 1.49%   |
| ASIX Electronics         | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 23        | 32.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 7.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 5.63%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 4.23%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 4.23%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 2         | 2.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 2.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 2.82%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.41%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1         | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.41%   |
| MediaTek A015                                                                  | 1         | 1.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.41%   |
| Lenovo Lenovo USB-C to LAN                                                     | 1         | 1.41%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.41%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.41%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.41%   |
| Intel Ethernet Connection (24) I219-LM                                         | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.41%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 1.41%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.41%   |
| Intel Arrow Lake CNVi WiFi                                                     | 1         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 1         | 1.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 1.41%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 54.23%  |
| Ethernet | 65        | 45.77%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 64.44%  |
| Ethernet | 32        | 35.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 55        | 68.75%  |
| 1     | 24        | 30%     |
| 0     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 69.51%  |
| Yes  | 25        | 30.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 48.53%  |
| Realtek Semiconductor           | 11        | 16.18%  |
| Qualcomm Atheros Communications | 9         | 13.24%  |
| Foxconn / Hon Hai               | 4         | 5.88%   |
| Broadcom                        | 4         | 5.88%   |
| IMC Networks                    | 3         | 4.41%   |
| Lite-On Technology              | 2         | 2.94%   |
| Foxconn International           | 1         | 1.47%   |
| Cambridge Silicon Radio         | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 9         | 13.24%  |
| Intel Bluetooth wireless interface                  | 9         | 13.24%  |
| Intel AX201 Bluetooth                               | 9         | 13.24%  |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 10.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.88%   |
| Intel Bluetooth Device                              | 3         | 4.41%   |
| Intel AX200 Bluetooth                               | 3         | 4.41%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 4.41%   |
| Intel AX210 Bluetooth                               | 2         | 2.94%   |
| IMC Networks Bluetooth Device                       | 2         | 2.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 2.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.47%   |
| Lite-On Wireless_Device                             | 1         | 1.47%   |
| Lite-On Bluetooth Device                            | 1         | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.47%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.47%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 65        | 63.73%  |
| Nvidia               | 16        | 15.69%  |
| AMD                  | 15        | 14.71%  |
| C-Media Electronics  | 4         | 3.92%   |
| Logitech             | 1         | 0.98%   |
| Conrad Electronic SE | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 10        | 8.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 7.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 6.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 4.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 4.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 3.31%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.31%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.48%   |
| C-Media Electronics C-Media USB Audio Device                                                      | 3         | 2.48%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 3         | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.48%   |
| AMD Radeon High Definition Audio Controller                                                       | 3         | 2.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.48%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.65%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 2         | 1.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.65%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 1.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.65%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.83%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.83%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 29.82%  |
| SK hynix            | 14        | 24.56%  |
| Kingston            | 7         | 12.28%  |
| Micron Technology   | 6         | 10.53%  |
| Elpida              | 3         | 5.26%   |
| Unknown (0x0100)    | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |
| Timetec             | 1         | 1.75%   |
| Team                | 1         | 1.75%   |
| Smart               | 1         | 1.75%   |
| Nanya Technology    | 1         | 1.75%   |
| GOODRAM             | 1         | 1.75%   |
| Crucial             | 1         | 1.75%   |
| Corsair             | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 2         | 3.28%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.28%   |
| Elpida RAM EBJ81UG8EFU0-GN-F 8GB SODIMM DDR3 1600MT/s            | 2         | 3.28%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Unknown (0x0100) RAM R744G2133S1S 4GB SODIMM DDR4 1866MT/s       | 1         | 1.64%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.64%   |
| Team RAM TEAMGROUP-SD3-1333 8GB SODIMM DDR3 1334MT/s             | 1         | 1.64%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 1         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.64%   |
| SK hynix RAM HMCG78AHBVA315N 16GB SODIMM DDR5 6400MT/s           | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 1.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.64%   |
| SK hynix RAM H58G78BK7BX114 16GB SODIMM LPDDR5 7500MT/s          | 1         | 1.64%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.64%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.64%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.64%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.64%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.64%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M425R1GB4PB0-CWMOL 8GB SODIMM DDR5 5600MT/s          | 1         | 1.64%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1600MT/s             | 1         | 1.64%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.64%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 46.51%  |
| DDR3   | 13        | 30.23%  |
| LPDDR3 | 3         | 6.98%   |
| LPDDR5 | 2         | 4.65%   |
| LPDDR4 | 2         | 4.65%   |
| DDR5   | 2         | 4.65%   |
| DDR2   | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 81.82%  |
| Row Of Chips | 8         | 18.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 20        | 41.67%  |
| 4096  | 17        | 35.42%  |
| 16384 | 5         | 10.42%  |
| 32768 | 3         | 6.25%   |
| 2048  | 3         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 26.92%  |
| 1600  | 9         | 17.31%  |
| 2667  | 8         | 15.38%  |
| 2133  | 3         | 5.77%   |
| 1334  | 3         | 5.77%   |
| 6400  | 2         | 3.85%   |
| 4267  | 2         | 3.85%   |
| 2400  | 2         | 3.85%   |
| 1866  | 2         | 3.85%   |
| 1333  | 2         | 3.85%   |
| 7500  | 1         | 1.92%   |
| 5600  | 1         | 1.92%   |
| 1067  | 1         | 1.92%   |
| 800   | 1         | 1.92%   |
| 667   | 1         | 1.92%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 17        | 22.97%  |
| IMC Networks                           | 9         | 12.16%  |
| Realtek Semiconductor                  | 8         | 10.81%  |
| Bison Electronics                      | 8         | 10.81%  |
| Sunplus Innovation Technology          | 4         | 5.41%   |
| Microdia                               | 4         | 5.41%   |
| Luxvisions Innotech Limited            | 4         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.41%   |
| Syntek                                 | 3         | 4.05%   |
| Suyin                                  | 3         | 4.05%   |
| Quanta                                 | 2         | 2.7%    |
| Z-Star Microelectronics                | 1         | 1.35%   |
| SunplusIT                              | 1         | 1.35%   |
| Ricoh                                  | 1         | 1.35%   |
| Logitech                               | 1         | 1.35%   |
| Importek                               | 1         | 1.35%   |
| icSpring                               | 1         | 1.35%   |
| DigiTech                               | 1         | 1.35%   |
| Unknown                                | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                              | 6         | 8%      |
| Bison Integrated Camera                                     | 4         | 5.33%   |
| Syntek Integrated Camera                                    | 3         | 4%      |
| Realtek Integrated_Webcam_HD                                | 3         | 4%      |
| Chicony HP Truevision HD                                    | 3         | 4%      |
| Microdia Integrated Webcam HD                               | 2         | 2.67%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 2.67%   |
| Chicony Integrated HP HD Webcam                             | 2         | 2.67%   |
| Chicony Integrated Camera                                   | 2         | 2.67%   |
| Z-Star Vimicro USB Camera(358boot)                          | 1         | 1.33%   |
| Suyin HP Truevision HD                                      | 1         | 1.33%   |
| Suyin HD WebCam                                             | 1         | 1.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.33%   |
| SunplusIT HD Webcam                                         | 1         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.33%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.33%   |
| Sunplus HD WebCam                                           | 1         | 1.33%   |
| Sunplus ASUS Webcam                                         | 1         | 1.33%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 1.33%   |
| Realtek Integrated_Webcam_FHD                               | 1         | 1.33%   |
| Realtek Integrated Webcam_HD                                | 1         | 1.33%   |
| Realtek Integrated Webcam HD                                | 1         | 1.33%   |
| Realtek EasyCamera                                          | 1         | 1.33%   |
| Realtek Bluetooth Radio                                     | 1         | 1.33%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.33%   |
| Quanta HD Webcam                                            | 1         | 1.33%   |
| Microdia Lenovo EasyCamera                                  | 1         | 1.33%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 1.33%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.33%   |
| Logitech HD Pro Webcam C920                                 | 1         | 1.33%   |
| Importek TOSHIBA Web Camera - HD                            | 1         | 1.33%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.33%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.33%   |
| IMC Networks HD Camera                                      | 1         | 1.33%   |
| icSpring camera                                             | 1         | 1.33%   |
| DigiTech USB 2.0 PC Camera                                  | 1         | 1.33%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 1.33%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.33%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 50%     |
| Synaptics                  | 5         | 27.78%  |
| Upek                       | 2         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 11.11%  |
| Validity Sensors VFS491                                | 2         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 11.11%  |
| Synaptics UWP WBDI Device                              | 2         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.56%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5.56%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 5.56%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 2         | 40%     |
| SCM Microsystems | 1         | 20%     |
| Lenovo           | 1         | 20%     |
| Alcor Micro      | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 20%     |
| Lenovo Integrated Smart Card Reader                    | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 20%     |
| Broadcom 58200                                         | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                    | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 43        | 52.44%  |
| 1     | 31        | 37.8%   |
| 2     | 6         | 7.32%   |
| 7     | 1         | 1.22%   |
| 4     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 35.29%  |
| Graphics card         | 9         | 17.65%  |
| Net/wireless          | 8         | 15.69%  |
| Multimedia controller | 5         | 9.8%    |
| Sound                 | 2         | 3.92%   |
| Firewire controller   | 2         | 3.92%   |
| Chipcard              | 2         | 3.92%   |
| Bluetooth             | 2         | 3.92%   |
| Storage               | 1         | 1.96%   |
| Net/ethernet          | 1         | 1.96%   |
| Camera                | 1         | 1.96%   |

