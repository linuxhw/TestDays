Rocky Linux - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

Total: 102

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown  | Unknown                     | [2d74d756b3](https://linux-hardware.org/?probe=2d74d756b3) | Jan 10, 2024 |
| Unknown  | DS16                        | [1951d37c43](https://linux-hardware.org/?probe=1951d37c43) | Jan 10, 2024 |
| Dell     | Inspiron 3501               | [7c421031f6](https://linux-hardware.org/?probe=7c421031f6) | Jan 04, 2024 |
| Lenovo   | G450 2949                   | [c8c0737175](https://linux-hardware.org/?probe=c8c0737175) | Dec 20, 2023 |
| Lenovo   | ThinkPad T430u 86147MG      | [0463c0adc2](https://linux-hardware.org/?probe=0463c0adc2) | Dec 17, 2023 |
| Dell     | Precision 5520              | [b3ea29b5a2](https://linux-hardware.org/?probe=b3ea29b5a2) | Dec 14, 2023 |
| Positivo | Q464C                       | [47071c986c](https://linux-hardware.org/?probe=47071c986c) | Dec 11, 2023 |
| Dell     | Vostro 3420                 | [95a9c16f88](https://linux-hardware.org/?probe=95a9c16f88) | Nov 28, 2023 |
| Lenovo   | Slim 7 ProX 14ARH7 82V2     | [f36053c77c](https://linux-hardware.org/?probe=f36053c77c) | Nov 13, 2023 |
| Lenovo   | G450 2949                   | [3f631dfb6e](https://linux-hardware.org/?probe=3f631dfb6e) | Nov 04, 2023 |
| Dell     | Latitude 7490               | [4859e397e4](https://linux-hardware.org/?probe=4859e397e4) | Nov 02, 2023 |
| HP       | EliteBook 645 14 inch G1... | [eb5712ae31](https://linux-hardware.org/?probe=eb5712ae31) | Oct 28, 2023 |
| Lenovo   | IdeaPad 1 14IGL7 82V6       | [407b6f9273](https://linux-hardware.org/?probe=407b6f9273) | Oct 15, 2023 |
| HP       | EliteBook 840 G5            | [0baddc9010](https://linux-hardware.org/?probe=0baddc9010) | Oct 11, 2023 |
| Lenovo   | ThinkPad T14s Gen 3 21BR... | [a607943a45](https://linux-hardware.org/?probe=a607943a45) | Oct 03, 2023 |
| HP       | EliteBook 840 G5            | [6615883de3](https://linux-hardware.org/?probe=6615883de3) | Oct 03, 2023 |
| HP       | Laptop 15s-fq1xxx           | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| Clevo    | P170EM                      | [ee87854652](https://linux-hardware.org/?probe=ee87854652) | Sep 14, 2023 |
| Apple    | MacBookPro11,4              | [ac1293fbf6](https://linux-hardware.org/?probe=ac1293fbf6) | Sep 02, 2023 |
| Apple    | MacBookPro11,4              | [1273e75666](https://linux-hardware.org/?probe=1273e75666) | Sep 02, 2023 |
| Dell     | XPS 15 9500                 | [88b6546b70](https://linux-hardware.org/?probe=88b6546b70) | Sep 01, 2023 |
| Lenovo   | ThinkPad T14 Gen 3 21AH0... | [9faf6d1836](https://linux-hardware.org/?probe=9faf6d1836) | Aug 30, 2023 |
| Dell     | XPS 13 9310                 | [40802d54a7](https://linux-hardware.org/?probe=40802d54a7) | Aug 27, 2023 |
| Lenovo   | ThinkPad X1 Carbon 3rd 2... | [62ca959d73](https://linux-hardware.org/?probe=62ca959d73) | Aug 21, 2023 |
| Lenovo   | ThinkPad P15s Gen 1 20T4... | [ceb8407c9a](https://linux-hardware.org/?probe=ceb8407c9a) | Aug 21, 2023 |
| HP       | Laptop 15-fc0xxx            | [fb346f4b46](https://linux-hardware.org/?probe=fb346f4b46) | Aug 15, 2023 |
| Lenovo   | ThinkPad T430 2347FF9       | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| HP       | ZBook 15u G5                | [1b0bb754bc](https://linux-hardware.org/?probe=1b0bb754bc) | Jul 28, 2023 |
| HP       | ZBook 15u G5                | [54684f905d](https://linux-hardware.org/?probe=54684f905d) | Jul 28, 2023 |
| Lenovo   | ThinkPad X270 20HMS79Q00    | [6a9d34223b](https://linux-hardware.org/?probe=6a9d34223b) | Jul 04, 2023 |
| ASUSTek  | G752VM                      | [b518236bd7](https://linux-hardware.org/?probe=b518236bd7) | Jun 21, 2023 |
| HP       | EliteBook 1040 14 inch G... | [47b86a7e60](https://linux-hardware.org/?probe=47b86a7e60) | Jun 14, 2023 |
| ASUSTek  | UX430UNR                    | [00ab711e0a](https://linux-hardware.org/?probe=00ab711e0a) | Jun 02, 2023 |
| HP       | ProBook 645 G1              | [f82952db4b](https://linux-hardware.org/?probe=f82952db4b) | May 14, 2023 |
| ASUSTek  | ASUS TUF Dash F15 FX517Z... | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| Beelink  | BT3 PRO                     | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| Acer     | Aspire E5-573G              | [5cff94f71e](https://linux-hardware.org/?probe=5cff94f71e) | May 07, 2023 |
| Lenovo   | ThinkPad P1 Gen 4i 20Y30... | [43e6345cb8](https://linux-hardware.org/?probe=43e6345cb8) | May 03, 2023 |
| Lenovo   | ThinkPad E14 Gen 4 21E30... | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| HUAWEI   | KLVD-WXX9                   | [ae500cf4af](https://linux-hardware.org/?probe=ae500cf4af) | Apr 22, 2023 |
| Lenovo   | IdeaPad 3 15ITL6 82H8       | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| HP       | EliteBook 840 G5            | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP       | EliteBook 840 G5            | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| ASUSTek  | ROG Strix G713RW_G713RW     | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| Lenovo   | ThinkPad T480 20L6S8B500    | [b4cbe5bf11](https://linux-hardware.org/?probe=b4cbe5bf11) | Feb 16, 2023 |
| Lenovo   | IdeaPad S210 Touch 20257    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell     | Latitude 5420               | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell     | Latitude 5420               | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| Lenovo   | ThinkPad P1 Gen 3 20TH00... | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Positivo | Mobile                      | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| Dell     | Inspiron 15-3573            | [b735bbde51](https://linux-hardware.org/?probe=b735bbde51) | Jan 29, 2023 |
| Lenovo   | ThinkPad P1 Gen 3 20TH00... | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Dell     | Precision M6800             | [bcd98b78c4](https://linux-hardware.org/?probe=bcd98b78c4) | Jan 19, 2023 |
| Dell     | Latitude 5420               | [cb511c0f82](https://linux-hardware.org/?probe=cb511c0f82) | Jan 18, 2023 |
| HP       | Laptop 15-dy2xxx            | [ff9464407f](https://linux-hardware.org/?probe=ff9464407f) | Jan 15, 2023 |
| HUAWEI   | KLVD-WXX9                   | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Lenovo   | IdeaPad Gaming 3 15ACH6 ... | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| HUAWEI   | KLVD-WXX9                   | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Dell     | XPS 17 9720                 | [ae26f02480](https://linux-hardware.org/?probe=ae26f02480) | Jan 03, 2023 |
| HP       | EliteBook 845 14 inch G9... | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| HP       | EliteBook 2560p             | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Dell     | Inspiron 14 5425            | [42f45d59d2](https://linux-hardware.org/?probe=42f45d59d2) | Dec 29, 2022 |
| HP       | ProBook 640 G3              | [03eba7b664](https://linux-hardware.org/?probe=03eba7b664) | Dec 15, 2022 |
| Lenovo   | ThinkPad T14s Gen 3 21BR... | [ede2606ad1](https://linux-hardware.org/?probe=ede2606ad1) | Dec 15, 2022 |
| Dell     | Vostro 3500                 | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| Lenovo   | ThinkPad P1 Gen 3 20THCT... | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X512... | [cda3087aaf](https://linux-hardware.org/?probe=cda3087aaf) | Oct 23, 2022 |
| HP       | Pavilion g6                 | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| BANGHO   | BES G1529                   | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Dell     | XPS 15 7590                 | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Dell     | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| HP       | ZBook 15u G6                | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| HP       | ZBook 15 G2                 | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| ASUSTek  | ASUS TUF Dash F15 FX516P... | [ce5ca74472](https://linux-hardware.org/?probe=ce5ca74472) | Jul 17, 2022 |
| Lenovo   | ThinkPad X1 Carbon 34483... | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell     | Latitude 3420               | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| HP       | EliteBook 840 G7 Noteboo... | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell     | Latitude 5500               | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo   | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell     | Latitude 5500               | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo   | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo   | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Lenovo   | Legion Y7000 2020H 81Y7     | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo   | Legion Y7000 2020H 81Y7     | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| Lenovo   | IdeaPad Y700-15ISK 80NV     | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP       | ZBook 15 G3                 | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo   | IdeaPad 500S-14ISK 80Q3     | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo   | ThinkPad W540 20BGCTO1WW    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| HP       | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Toshiba  | TECRA W50-A                 | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Lenovo   | ThinkPad T420 42365H1       | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo   | ThinkPad T420 42365H1       | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Lenovo   | ThinkPad W500 406132G       | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo   | IdeaPad Y410P 20216         | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo   | IdeaPad Y410P 20216         | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek  | ASUS TUF Gaming A15 FA50... | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba  | Satellite E45-B             | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| Acer     | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Rocky Linux 9.1 | 22        | 26.19%  |
| Rocky Linux 9.2 | 14        | 16.67%  |
| Rocky Linux 8.5 | 11        | 13.1%   |
| Rocky Linux 9.0 | 9         | 10.71%  |
| Rocky Linux 8.4 | 8         | 9.52%   |
| Rocky Linux 8.8 | 7         | 8.33%   |
| Rocky Linux 9.3 | 6         | 7.14%   |
| Rocky Linux 8.7 | 3         | 3.57%   |
| Rocky Linux 8.9 | 2         | 2.38%   |
| Rocky Linux 8.6 | 1         | 1.19%   |
| Rocky Linux 8.3 | 1         | 1.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 82        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 10.47%  |
| 5.14.0-284.25.1.el9_2.x86_64     | 5         | 5.81%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 4.65%   |
| 5.14.0-362.8.1.el9_3.x86_64      | 4         | 4.65%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 4         | 4.65%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 4         | 4.65%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 4         | 4.65%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 4.65%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 3         | 3.49%   |
| 4.18.0-477.27.1.el8_8.x86_64     | 3         | 3.49%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 3.49%   |
| 6.1.64-2.el9.x86_64              | 2         | 2.33%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 2.33%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 2         | 2.33%   |
| 4.18.0-513.9.1.el8_9.x86_64      | 2         | 2.33%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 2.33%   |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 2.33%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 2.33%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 2.33%   |
| 4.18.0-305.el8.x86_64            | 2         | 2.33%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 2.33%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 2.33%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 2.33%   |
| 6.4.12-1.el8.elrepo.x86_64       | 1         | 1.16%   |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 1.16%   |
| 6.2.10-1.el8.elrepo.x86_64       | 1         | 1.16%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.16%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 1.16%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 1         | 1.16%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1         | 1.16%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.16%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 1         | 1.16%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 1.16%   |
| 5.10.89-1.el8.x86_64             | 1         | 1.16%   |
| 4.18.0-477.21.1.el8_8.x86_64     | 1         | 1.16%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.16%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1         | 1.16%   |
| 4.18.0-240.22.1.el8.x86_64       | 1         | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 48        | 57.83%  |
| 4.18.0  | 27        | 32.53%  |
| 6.1.64  | 2         | 2.41%   |
| 6.4.12  | 1         | 1.2%    |
| 6.2.12  | 1         | 1.2%    |
| 6.2.10  | 1         | 1.2%    |
| 5.4.157 | 1         | 1.2%    |
| 5.16.15 | 1         | 1.2%    |
| 5.10.89 | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 48        | 57.83%  |
| 4.18    | 27        | 32.53%  |
| 6.2     | 2         | 2.41%   |
| 6.1     | 2         | 2.41%   |
| 6.4     | 1         | 1.2%    |
| 5.4     | 1         | 1.2%    |
| 5.16    | 1         | 1.2%    |
| 5.10    | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 58        | 70.73%  |
| KDE5          | 9         | 10.98%  |
| MATE          | 6         | 7.32%   |
| XFCE          | 3         | 3.66%   |
| X-Cinnamon    | 3         | 3.66%   |
| Unknown       | 2         | 2.44%   |
| GNOME Classic | 1         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 51        | 62.2%   |
| X11     | 29        | 35.37%  |
| Tty     | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 46.34%  |
| GDM     | 31        | 37.8%   |
| SDDM    | 7         | 8.54%   |
| LightDM | 6         | 7.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 59        | 71.95%  |
| de_DE | 3         | 3.66%   |
| ru_RU | 2         | 2.44%   |
| pt_BR | 2         | 2.44%   |
| it_IT | 2         | 2.44%   |
| es_ES | 2         | 2.44%   |
| en_ZA | 2         | 2.44%   |
| en_IE | 2         | 2.44%   |
| en_CA | 2         | 2.44%   |
| C     | 2         | 2.44%   |
| zh_TW | 1         | 1.22%   |
| fr_FR | 1         | 1.22%   |
| en_GB | 1         | 1.22%   |
| ca_ES | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 68        | 82.93%  |
| BIOS | 14        | 17.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 71        | 86.59%  |
| Ext4 | 10        | 12.2%   |
| Ext3 | 1         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 41        | 50%     |
| Unknown | 37        | 45.12%  |
| MBR     | 4         | 4.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 89.02%  |
| Yes       | 9         | 10.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 76.83%  |
| Yes       | 19        | 23.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 29        | 35.37%  |
| Hewlett-Packard  | 17        | 20.73%  |
| Dell             | 16        | 19.51%  |
| ASUSTek Computer | 7         | 8.54%   |
| Toshiba          | 2         | 2.44%   |
| Positivo         | 2         | 2.44%   |
| Acer             | 2         | 2.44%   |
| Unknown          | 2         | 2.44%   |
| HUAWEI           | 1         | 1.22%   |
| Clevo            | 1         | 1.22%   |
| Beelink          | 1         | 1.22%   |
| BANGHO           | 1         | 1.22%   |
| Apple            | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP EliteBook 840 G5                      | 2         | 2.44%   |
| Unknown                                  | 2         | 2.44%   |
| Toshiba TECRA W50-A                      | 1         | 1.22%   |
| Toshiba Satellite E45-B                  | 1         | 1.22%   |
| Positivo Q464C                           | 1         | 1.22%   |
| Positivo Mobile                          | 1         | 1.22%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900 | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 1.22%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 1.22%   |
| Lenovo ThinkPad W500 406132G             | 1         | 1.22%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 1.22%   |
| Lenovo ThinkPad T430u 86147MG            | 1         | 1.22%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 1.22%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 1.22%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 1.22%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 1.22%   |
| Lenovo ThinkPad T14 Gen 3 21AH00HXGE     | 1         | 1.22%   |
| Lenovo ThinkPad P15s Gen 1 20T4CTO1WW    | 1         | 1.22%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV     | 1         | 1.22%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 1.22%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK      | 1         | 1.22%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB     | 1         | 1.22%   |
| Lenovo Slim 7 ProX 14ARH7 82V2           | 1         | 1.22%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 1.22%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.22%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.22%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 1.22%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.22%   |
| Lenovo IdeaPad S210 Touch 20257          | 1         | 1.22%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 1         | 1.22%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 1.22%   |
| Lenovo IdeaPad 3 15ITL6 82H8             | 1         | 1.22%   |
| Lenovo IdeaPad 1 14IGL7 82V6             | 1         | 1.22%   |
| Lenovo G450 2949                         | 1         | 1.22%   |
| HUAWEI KLVD-WXX9                         | 1         | 1.22%   |
| HP ZBook 15u G6                          | 1         | 1.22%   |
| HP ZBook 15u G5                          | 1         | 1.22%   |
| HP ZBook 15 G3                           | 1         | 1.22%   |
| HP ZBook 15 G2                           | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 17        | 20.73%  |
| Lenovo IdeaPad     | 8         | 9.76%   |
| HP EliteBook       | 6         | 7.32%   |
| Dell Latitude      | 5         | 6.1%    |
| HP ZBook           | 4         | 4.88%   |
| HP Laptop          | 4         | 4.88%   |
| Dell XPS           | 4         | 4.88%   |
| Dell Inspiron      | 3         | 3.66%   |
| ASUS ASUS          | 3         | 3.66%   |
| Lenovo Legion      | 2         | 2.44%   |
| HP ProBook         | 2         | 2.44%   |
| Dell Vostro        | 2         | 2.44%   |
| Dell Precision     | 2         | 2.44%   |
| Acer Aspire        | 2         | 2.44%   |
| Unknown            | 2         | 2.44%   |
| Toshiba TECRA      | 1         | 1.22%   |
| Toshiba Satellite  | 1         | 1.22%   |
| Positivo Q464C     | 1         | 1.22%   |
| Positivo Mobile    | 1         | 1.22%   |
| Lenovo Slim        | 1         | 1.22%   |
| Lenovo G450        | 1         | 1.22%   |
| HUAWEI KLVD-WXX9   | 1         | 1.22%   |
| HP Pavilion        | 1         | 1.22%   |
| Clevo P170EM       | 1         | 1.22%   |
| Beelink BT3        | 1         | 1.22%   |
| BANGHO BES         | 1         | 1.22%   |
| ASUS VivoBook      | 1         | 1.22%   |
| ASUS UX430UNR      | 1         | 1.22%   |
| ASUS ROG           | 1         | 1.22%   |
| ASUS G752VM        | 1         | 1.22%   |
| Apple MacBookPro11 | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 12        | 14.63%  |
| 2020 | 12        | 14.63%  |
| 2021 | 8         | 9.76%   |
| 2019 | 8         | 9.76%   |
| 2018 | 8         | 9.76%   |
| 2017 | 5         | 6.1%    |
| 2014 | 5         | 6.1%    |
| 2012 | 5         | 6.1%    |
| 2015 | 4         | 4.88%   |
| 2023 | 3         | 3.66%   |
| 2013 | 3         | 3.66%   |
| 2011 | 3         | 3.66%   |
| 2016 | 2         | 2.44%   |
| 2010 | 2         | 2.44%   |
| 2009 | 2         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 82        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 65        | 79.27%  |
| Enabled  | 17        | 20.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 27        | 32.93%  |
| 4.01-8.0    | 19        | 23.17%  |
| 32.01-64.0  | 17        | 20.73%  |
| 16.01-24.0  | 8         | 9.76%   |
| 3.01-4.0    | 6         | 7.32%   |
| 24.01-32.0  | 3         | 3.66%   |
| 64.01-256.0 | 2         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 31.03%  |
| 3.01-4.0   | 19        | 21.84%  |
| 2.01-3.0   | 19        | 21.84%  |
| 8.01-16.0  | 10        | 11.49%  |
| 1.01-2.0   | 8         | 9.2%    |
| 0.51-1.0   | 2         | 2.3%    |
| 24.01-32.0 | 1         | 1.15%   |
| 16.01-24.0 | 1         | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 81.71%  |
| 2      | 10        | 12.2%   |
| 3      | 4         | 4.88%   |
| 4      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 85.37%  |
| Yes       | 12        | 14.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 81.93%  |
| No        | 15        | 18.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 96.34%  |
| No        | 3         | 3.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 86.59%  |
| No        | 11        | 13.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 26        | 31.71%  |
| Russia       | 4         | 4.88%   |
| Germany      | 4         | 4.88%   |
| Spain        | 3         | 3.66%   |
| Poland       | 3         | 3.66%   |
| Italy        | 3         | 3.66%   |
| Brazil       | 3         | 3.66%   |
| South Africa | 2         | 2.44%   |
| Netherlands  | 2         | 2.44%   |
| Ireland      | 2         | 2.44%   |
| Indonesia    | 2         | 2.44%   |
| Hungary      | 2         | 2.44%   |
| Czechia      | 2         | 2.44%   |
| Canada       | 2         | 2.44%   |
| Belgium      | 2         | 2.44%   |
| Argentina    | 2         | 2.44%   |
| Uzbekistan   | 1         | 1.22%   |
| UK           | 1         | 1.22%   |
| UAE          | 1         | 1.22%   |
| Turkey       | 1         | 1.22%   |
| Taiwan       | 1         | 1.22%   |
| Sweden       | 1         | 1.22%   |
| Slovakia     | 1         | 1.22%   |
| Saudi Arabia | 1         | 1.22%   |
| Pakistan     | 1         | 1.22%   |
| Norway       | 1         | 1.22%   |
| Malaysia     | 1         | 1.22%   |
| Kenya        | 1         | 1.22%   |
| Kazakhstan   | 1         | 1.22%   |
| France       | 1         | 1.22%   |
| Croatia      | 1         | 1.22%   |
| China        | 1         | 1.22%   |
| Bulgaria     | 1         | 1.22%   |
| Austria      | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Philadelphia           | 2         | 2.44%   |
| Moscow                 | 2         | 2.44%   |
| Enschede               | 2         | 2.44%   |
| Budapest               | 2         | 2.44%   |
| Bekasi                 | 2         | 2.44%   |
| Albuquerque            | 2         | 2.44%   |
| Žilina                | 1         | 1.22%   |
| Xi'an                  | 1         | 1.22%   |
| Woking                 | 1         | 1.22%   |
| Westerville            | 1         | 1.22%   |
| Walnut Creek           | 1         | 1.22%   |
| Viggiù                | 1         | 1.22%   |
| Vienna                 | 1         | 1.22%   |
| Troisdorf              | 1         | 1.22%   |
| Torrington             | 1         | 1.22%   |
| Taoyuan City           | 1         | 1.22%   |
| Syracuse               | 1         | 1.22%   |
| Spokane                | 1         | 1.22%   |
| Split                  | 1         | 1.22%   |
| Sofia                  | 1         | 1.22%   |
| Smolensk               | 1         | 1.22%   |
| Senigallia             | 1         | 1.22%   |
| Scarborough            | 1         | 1.22%   |
| Sao Paulo              | 1         | 1.22%   |
| San Miguel de Tucumán | 1         | 1.22%   |
| Rosario                | 1         | 1.22%   |
| Riyadh                 | 1         | 1.22%   |
| Rawalpindi             | 1         | 1.22%   |
| Qualicum Beach         | 1         | 1.22%   |
| Prague                 | 1         | 1.22%   |
| Ottignies              | 1         | 1.22%   |
| Oslo                   | 1         | 1.22%   |
| Örebro                | 1         | 1.22%   |
| Olympia                | 1         | 1.22%   |
| Oakley                 | 1         | 1.22%   |
| Nyahururu              | 1         | 1.22%   |
| Nur-Sultan             | 1         | 1.22%   |
| Niceville              | 1         | 1.22%   |
| Mugla                  | 1         | 1.22%   |
| Mossel Bay             | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 25        | 29     | 24.27%  |
| Sandisk                   | 9         | 11     | 8.74%   |
| WDC                       | 8         | 8      | 7.77%   |
| Micron Technology         | 7         | 7      | 6.8%    |
| Toshiba                   | 5         | 6      | 4.85%   |
| Kingston                  | 5         | 5      | 4.85%   |
| Intel                     | 5         | 5      | 4.85%   |
| Unknown                   | 4         | 4      | 3.88%   |
| SK hynix                  | 3         | 5      | 2.91%   |
| Seagate                   | 3         | 3      | 2.91%   |
| Lexar                     | 2         | 2      | 1.94%   |
| Dogfish                   | 2         | 2      | 1.94%   |
| Crucial                   | 2         | 2      | 1.94%   |
| A-DATA Technology         | 2         | 2      | 1.94%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.97%   |
| Union Memory              | 1         | 1      | 0.97%   |
| UMIS                      | 1         | 1      | 0.97%   |
| StoreJet                  | 1         | 1      | 0.97%   |
| PNY                       | 1         | 2      | 0.97%   |
| Phison                    | 1         | 2      | 0.97%   |
| Patriot                   | 1         | 1      | 0.97%   |
| Micron/Crucial Technology | 1         | 1      | 0.97%   |
| LITEONIT                  | 1         | 1      | 0.97%   |
| LITEON                    | 1         | 1      | 0.97%   |
| KIOXIA                    | 1         | 1      | 0.97%   |
| JMicron Technology        | 1         | 1      | 0.97%   |
| INDMEM                    | 1         | 1      | 0.97%   |
| HS-SSD-C100               | 1         | 1      | 0.97%   |
| Hitachi                   | 1         | 1      | 0.97%   |
| Fujitsu                   | 1         | 1      | 0.97%   |
| EAGET                     | 1         | 1      | 0.97%   |
| ASMT                      | 1         | 1      | 0.97%   |
| AGI                       | 1         | 1      | 0.97%   |
| ADATA Technology          | 1         | 1      | 0.97%   |
| Unknown                   | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 4         | 3.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 2.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 3         | 2.75%   |
| Unknown MMC Card  64GB                              | 2         | 1.83%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 1.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 1.83%   |
| Lexar 512GB SSD                                     | 2         | 1.83%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.92%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.92%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 0.92%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 0.92%   |
| WDC WD40 EFRX-68N32N0 4TB                           | 1         | 0.92%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.92%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.92%   |
| WDC WD Blue SA510 M.2 2280 1000GB                   | 1         | 0.92%   |
| Unknown SD/MMC/MS PRO 256GB                         | 1         | 0.92%   |
| Unknown S0J38Y  64GB                                | 1         | 0.92%   |
| Union Memory UMIS RPJTJ128MEE1MWX 128GB             | 1         | 0.92%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1         | 0.92%   |
| UMIS RPFTJ128PDD2EWX 128GB                          | 1         | 0.92%   |
| Toshiba THNSNJ512GACU 512GB SSD                     | 1         | 0.92%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 0.92%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 0.92%   |
| Toshiba KXG6AZNV1T02 1TB                            | 1         | 0.92%   |
| Toshiba KXG6APNV2T04 2TB                            | 1         | 0.92%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 0.92%   |
| StoreJet Disk 1TB                                   | 1         | 0.92%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB           | 1         | 0.92%   |
| SK hynix SHPP41-2000GM 2TB                          | 1         | 0.92%   |
| SK hynix NVMe SSD Drive 512GB                       | 1         | 0.92%   |
| SK hynix BC511 NVMe 512GB                           | 1         | 0.92%   |
| Seagate ST9320325AS 320GB                           | 1         | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 0.92%   |
| Seagate One Touch HDD 2TB                           | 1         | 0.92%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 0.92%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1TB           | 1         | 0.92%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 0.92%   |
| SanDisk SDSSDA120G 120GB                            | 1         | 0.92%   |
| SanDisk SD8SN8U512G1002 512GB SSD                   | 1         | 0.92%   |
| SanDisk SD5SG2256G1052E 256GB SSD                   | 1         | 0.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 5         | 5      | 41.67%  |
| Seagate  | 3         | 3      | 25%     |
| Unknown  | 1         | 1      | 8.33%   |
| StoreJet | 1         | 1      | 8.33%   |
| Hitachi  | 1         | 1      | 8.33%   |
| Fujitsu  | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 22.22%  |
| SanDisk             | 4         | 5      | 11.11%  |
| WDC                 | 3         | 3      | 8.33%   |
| Kingston            | 3         | 3      | 8.33%   |
| Toshiba             | 2         | 2      | 5.56%   |
| Dogfish             | 2         | 2      | 5.56%   |
| Crucial             | 2         | 2      | 5.56%   |
| PNY                 | 1         | 2      | 2.78%   |
| Patriot             | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| LITEONIT            | 1         | 1      | 2.78%   |
| LITEON              | 1         | 1      | 2.78%   |
| Lexar               | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| INDMEM              | 1         | 1      | 2.78%   |
| EAGET               | 1         | 1      | 2.78%   |
| ASMT                | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |
| Unknown             | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 48        | 57     | 50.53%  |
| SSD     | 31        | 39     | 32.63%  |
| HDD     | 10        | 12     | 10.53%  |
| MMC     | 3         | 3      | 3.16%   |
| Unknown | 3         | 3      | 3.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 48        | 57     | 51.06%  |
| SATA | 36        | 46     | 38.3%   |
| SAS  | 7         | 8      | 7.45%   |
| MMC  | 3         | 3      | 3.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 26     | 52.38%  |
| 0.51-1.0   | 14        | 18     | 33.33%  |
| 1.01-2.0   | 4         | 4      | 9.52%   |
| 3.01-4.0   | 2         | 3      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 25        | 30.49%  |
| 101-250        | 23        | 28.05%  |
| 501-1000       | 14        | 17.07%  |
| 1001-2000      | 6         | 7.32%   |
| 51-100         | 5         | 6.1%    |
| 2001-3000      | 3         | 3.66%   |
| More than 3000 | 2         | 2.44%   |
| 21-50          | 2         | 2.44%   |
| 1-20           | 2         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 33.33%  |
| 21-50          | 22        | 26.19%  |
| 101-250        | 13        | 15.48%  |
| 51-100         | 11        | 13.1%   |
| 251-500        | 5         | 5.95%   |
| 1001-2000      | 2         | 2.38%   |
| 501-1000       | 2         | 2.38%   |
| More than 3000 | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC WD40 EFRX-68N32N0 4TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Works    | 44        | 58     | 50.57%  |
| Detected | 42        | 55     | 48.28%  |
| Malfunc  | 1         | 1      | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 48        | 48.98%  |
| Samsung Electronics          | 17        | 17.35%  |
| Micron Technology            | 6         | 6.12%   |
| AMD                          | 6         | 6.12%   |
| SanDisk                      | 5         | 5.1%    |
| Toshiba America Info Systems | 3         | 3.06%   |
| SK hynix                     | 3         | 3.06%   |
| Union Memory (Shenzhen)      | 2         | 2.04%   |
| Kingston Technology Company  | 2         | 2.04%   |
| Shenzhen Longsys Electronics | 1         | 1.02%   |
| Realtek Semiconductor        | 1         | 1.02%   |
| Phison Electronics           | 1         | 1.02%   |
| Micron/Crucial Technology    | 1         | 1.02%   |
| KIOXIA                       | 1         | 1.02%   |
| ADATA Technology             | 1         | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 7         | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 6         | 5.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 5         | 4.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 5         | 4.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 4         | 3.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 4         | 3.81%   |
| Micron 3400 NVMe SSD [Hendrix]                                                                                     | 4         | 3.81%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 4         | 3.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 4         | 3.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 3         | 2.86%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 3         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 3         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 3         | 2.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                                               | 2         | 1.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 2         | 1.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 2         | 1.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                                                            | 2         | 1.9%    |
| Intel SSD 660P Series                                                                                              | 2         | 1.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 2         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 1.9%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile                                         | 2         | 1.9%    |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                                                              | 1         | 0.95%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                                                    | 1         | 0.95%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                                               | 1         | 0.95%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                                                 | 1         | 0.95%   |
| SK hynix PC611 NVMe Solid State Drive                                                                              | 1         | 0.95%   |
| SK hynix BC511 NVMe SSD                                                                                            | 1         | 0.95%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 0.95%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                                            | 1         | 0.95%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                                              | 1         | 0.95%   |
| Samsung NVMe SSD Controller SM951/PM951                                                                            | 1         | 0.95%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                                                  | 1         | 0.95%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 1         | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                                               | 1         | 0.95%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                                        | 1         | 0.95%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                                                   | 1         | 0.95%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 1         | 0.95%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                                                      | 1         | 0.95%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                                           | 1         | 0.95%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                                                   | 1         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 48        | 47.52%  |
| SATA | 41        | 40.59%  |
| RAID | 7         | 6.93%   |
| IDE  | 5         | 4.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 84.15%  |
| AMD    | 13        | 15.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 4.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 3.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 3.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.44%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 2         | 2.44%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 2.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2.44%   |
| Intel 12th Gen Core i7-1260P                | 2         | 2.44%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 2         | 2.44%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.22%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.22%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.22%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.22%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.22%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.22%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 1.22%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.22%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz          | 1         | 1.22%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.22%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.22%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.22%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.22%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.22%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.22%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.22%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.22%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.22%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.22%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.22%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 28        | 34.15%  |
| Other                   | 18        | 21.95%  |
| Intel Core i5           | 15        | 18.29%  |
| AMD Ryzen 5             | 4         | 4.88%   |
| Intel Celeron           | 3         | 3.66%   |
| Intel Atom              | 2         | 2.44%   |
| AMD Ryzen 7             | 2         | 2.44%   |
| AMD Ryzen 5 PRO         | 2         | 2.44%   |
| Intel Pentium Silver    | 1         | 1.22%   |
| Intel Pentium Dual-Core | 1         | 1.22%   |
| Intel Core i3           | 1         | 1.22%   |
| Intel Core 2 Duo        | 1         | 1.22%   |
| AMD Ryzen 9             | 1         | 1.22%   |
| AMD Ryzen 3             | 1         | 1.22%   |
| AMD A8                  | 1         | 1.22%   |
| AMD A10                 | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 39        | 47.56%  |
| 2      | 20        | 24.39%  |
| 6      | 8         | 9.76%   |
| 8      | 6         | 7.32%   |
| 10     | 5         | 6.1%    |
| 12     | 2         | 2.44%   |
| 14     | 1         | 1.22%   |
| 1      | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 83.13%  |
| 1      | 14        | 16.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 82        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 10.84%  |
| 0x806c1    | 8         | 9.64%   |
| 0x306c3    | 7         | 8.43%   |
| 0x806ea    | 6         | 7.23%   |
| 0xa0652    | 5         | 6.02%   |
| 0x806ec    | 5         | 6.02%   |
| 0x306a9    | 4         | 4.82%   |
| 0x506e3    | 3         | 3.61%   |
| 0x906a4    | 2         | 2.41%   |
| 0x906a3    | 2         | 2.41%   |
| 0x806e9    | 2         | 2.41%   |
| 0x306d4    | 2         | 2.41%   |
| 0x206a7    | 2         | 2.41%   |
| 0x0a50000d | 2         | 2.41%   |
| 0x0a50000c | 2         | 2.41%   |
| 0x08600104 | 2         | 2.41%   |
| 0x906ea    | 1         | 1.2%    |
| 0x906c0    | 1         | 1.2%    |
| 0x806d1    | 1         | 1.2%    |
| 0x706e5    | 1         | 1.2%    |
| 0x706a8    | 1         | 1.2%    |
| 0x706a1    | 1         | 1.2%    |
| 0x406e3    | 1         | 1.2%    |
| 0x406c4    | 1         | 1.2%    |
| 0x40661    | 1         | 1.2%    |
| 0x40651    | 1         | 1.2%    |
| 0x20655    | 1         | 1.2%    |
| 0x1067a    | 1         | 1.2%    |
| 0x10676    | 1         | 1.2%    |
| 0x0a404102 | 1         | 1.2%    |
| 0x0a404101 | 1         | 1.2%    |
| 0x08a00006 | 1         | 1.2%    |
| 0x08108102 | 1         | 1.2%    |
| 0x06006705 | 1         | 1.2%    |
| 0x06001119 | 1         | 1.2%    |
| 0x06001116 | 1         | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 17.07%  |
| Haswell          | 9         | 10.98%  |
| TigerLake        | 8         | 9.76%   |
| Alderlake Hybrid | 8         | 9.76%   |
| Skylake          | 5         | 6.1%    |
| IvyBridge        | 5         | 6.1%    |
| CometLake        | 5         | 6.1%    |
| Zen 3            | 4         | 4.88%   |
| IceLake          | 3         | 3.66%   |
| Unknown          | 3         | 3.66%   |
| Zen 2            | 2         | 2.44%   |
| Silvermont       | 2         | 2.44%   |
| SandyBridge      | 2         | 2.44%   |
| Piledriver       | 2         | 2.44%   |
| Penryn           | 2         | 2.44%   |
| Goldmont plus    | 2         | 2.44%   |
| Broadwell        | 2         | 2.44%   |
| Zen+             | 1         | 1.22%   |
| Westmere         | 1         | 1.22%   |
| Tremont          | 1         | 1.22%   |
| Excavator        | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 58.04%  |
| Nvidia | 32        | 28.57%  |
| AMD    | 15        | 13.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 7.08%   |
| Intel UHD Graphics 620                                                                   | 6         | 5.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 4.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 4.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.42%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 4         | 3.54%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.65%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 2.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.77%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 1.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.77%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 1.77%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.77%   |
| Intel HD Graphics 620                                                                    | 2         | 1.77%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.77%   |
| Intel HD Graphics 530                                                                    | 2         | 1.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.77%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 1.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.77%   |
| AMD Barcelo                                                                              | 2         | 1.77%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.88%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.88%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.88%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.88%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.88%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.88%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.88%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 0.88%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 0.88%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.88%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 47.56%  |
| Intel + Nvidia | 23        | 28.05%  |
| 1 x AMD        | 7         | 8.54%   |
| 1 x Nvidia     | 5         | 6.1%    |
| AMD + Nvidia   | 4         | 4.88%   |
| Intel + AMD    | 3         | 3.66%   |
| 2 x AMD        | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 85.37%  |
| Proprietary | 11        | 13.41%  |
| Unknown     | 1         | 1.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 57.83%  |
| 3.01-4.0   | 12        | 14.46%  |
| 1.01-2.0   | 8         | 9.64%   |
| 0.01-0.5   | 7         | 8.43%   |
| 5.01-6.0   | 3         | 3.61%   |
| 0.51-1.0   | 3         | 3.61%   |
| 7.01-8.0   | 2         | 2.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 14.91%  |
| LG Display              | 16        | 14.04%  |
| BOE                     | 16        | 14.04%  |
| Chimei Innolux          | 11        | 9.65%   |
| Goldstar                | 10        | 8.77%   |
| Samsung Electronics     | 9         | 7.89%   |
| Dell                    | 8         | 7.02%   |
| Sharp                   | 5         | 4.39%   |
| Philips                 | 3         | 2.63%   |
| InfoVision              | 3         | 2.63%   |
| PANDA                   | 2         | 1.75%   |
| Lenovo                  | 2         | 1.75%   |
| CSO                     | 2         | 1.75%   |
| AOC                     | 2         | 1.75%   |
| Sony                    | 1         | 0.88%   |
| Panasonic               | 1         | 0.88%   |
| Hewlett-Packard         | 1         | 0.88%   |
| Gigabyte Technology     | 1         | 0.88%   |
| Chi Mei Optoelectronics | 1         | 0.88%   |
| BenQ                    | 1         | 0.88%   |
| Apple                   | 1         | 0.88%   |
| Acer                    | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.69%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.69%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 1.69%   |
| Sony LCD Monitor MS_003C 1366x768 309x173mm 13.9-inch                 | 1         | 0.85%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.85%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 0.85%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 0.85%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.85%   |
| Philips PHL 499P9 PHL092A 3840x1080 1193x336mm 48.8-inch              | 1         | 0.85%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 0.85%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 0.85%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.85%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 47.12%  |
| 1366x768 (WXGA)    | 14        | 13.46%  |
| 2560x1440 (QHD)    | 6         | 5.77%   |
| 1920x1200 (WUXGA)  | 6         | 5.77%   |
| 3840x2160 (4K)     | 4         | 3.85%   |
| 3440x1440          | 4         | 3.85%   |
| 2560x1080          | 4         | 3.85%   |
| 3840x2400          | 3         | 2.88%   |
| 1600x900 (HD+)     | 3         | 2.88%   |
| 3840x1080          | 2         | 1.92%   |
| 1680x1050 (WSXGA+) | 2         | 1.92%   |
| 3072x1920          | 1         | 0.96%   |
| 2880x1800          | 1         | 0.96%   |
| 2240x1400          | 1         | 0.96%   |
| 2160x1440          | 1         | 0.96%   |
| 1920x550           | 1         | 0.96%   |
| 1360x768           | 1         | 0.96%   |
| Unknown            | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 35        | 30.43%  |
| 14      | 25        | 21.74%  |
| 13      | 10        | 8.7%    |
| 27      | 8         | 6.96%   |
| 17      | 7         | 6.09%   |
| 34      | 6         | 5.22%   |
| 24      | 5         | 4.35%   |
| 21      | 4         | 3.48%   |
| 40      | 2         | 1.74%   |
| 31      | 2         | 1.74%   |
| 23      | 2         | 1.74%   |
| 16      | 2         | 1.74%   |
| 49      | 1         | 0.87%   |
| 48      | 1         | 0.87%   |
| 35      | 1         | 0.87%   |
| 22      | 1         | 0.87%   |
| 18      | 1         | 0.87%   |
| 12      | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 59.65%  |
| 501-600     | 13        | 11.4%   |
| 401-500     | 7         | 6.14%   |
| 351-400     | 7         | 6.14%   |
| 701-800     | 6         | 5.26%   |
| 201-300     | 5         | 4.39%   |
| 801-900     | 3         | 2.63%   |
| 601-700     | 2         | 1.75%   |
| 1001-1500   | 2         | 1.75%   |
| Unknown     | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 71        | 73.96%  |
| 16/10 | 13        | 13.54%  |
| 21/9  | 7         | 7.29%   |
| 32/9  | 3         | 3.13%   |
| 3/2   | 2         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 29.82%  |
| 81-90          | 32        | 28.07%  |
| 201-250        | 10        | 8.77%   |
| 351-500        | 9         | 7.89%   |
| 301-350        | 8         | 7.02%   |
| 121-130        | 7         | 6.14%   |
| 501-1000       | 4         | 3.51%   |
| 111-120        | 3         | 2.63%   |
| 71-80          | 2         | 1.75%   |
| 61-70          | 1         | 0.88%   |
| 151-200        | 1         | 0.88%   |
| 141-150        | 1         | 0.88%   |
| 91-100         | 1         | 0.88%   |
| Unknown        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 44.25%  |
| 101-120       | 23        | 20.35%  |
| 51-100        | 22        | 19.47%  |
| 161-240       | 10        | 8.85%   |
| More than 240 | 7         | 6.19%   |
| Unknown       | 1         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 59.04%  |
| 2     | 27        | 32.53%  |
| 3     | 4         | 4.82%   |
| 0     | 2         | 2.41%   |
| 4     | 1         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 44.19%  |
| Realtek Semiconductor | 41        | 31.78%  |
| Qualcomm Atheros      | 7         | 5.43%   |
| MediaTek              | 5         | 3.88%   |
| ASIX Electronics      | 5         | 3.88%   |
| Lenovo                | 4         | 3.1%    |
| Broadcom              | 4         | 3.1%    |
| Ralink                | 1         | 0.78%   |
| JMicron Technology    | 1         | 0.78%   |
| Dell                  | 1         | 0.78%   |
| D-Link                | 1         | 0.78%   |
| Broadcom Limited      | 1         | 0.78%   |
| ASUSTek Computer      | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 13.58%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 7.41%   |
| Intel Wireless 8265 / 8275                                             | 8         | 4.94%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 3.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 3.7%    |
| Intel Wireless 7260                                                    | 5         | 3.09%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 3.09%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 2.47%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.47%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 2.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 2.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.85%   |
| Intel Wireless 8260                                                    | 3         | 1.85%   |
| Intel Wireless 7265                                                    | 3         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.23%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.23%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 1.23%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.23%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.62%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]     | 1         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.62%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 67.9%   |
| Realtek Semiconductor | 9         | 11.11%  |
| Qualcomm Atheros      | 6         | 7.41%   |
| MediaTek              | 5         | 6.17%   |
| Broadcom              | 2         | 2.47%   |
| Ralink                | 1         | 1.23%   |
| Dell                  | 1         | 1.23%   |
| Broadcom Limited      | 1         | 1.23%   |
| ASUSTek Computer      | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                                                         | 8         | 9.88%   |
| Intel Wi-Fi 6 AX201                                                                                                | 6         | 7.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 6         | 7.41%   |
| Intel Wireless 7260                                                                                                | 5         | 6.17%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 4         | 4.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 4         | 4.94%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                        | 3         | 3.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 3.7%    |
| Intel Wireless 8260                                                                                                | 3         | 3.7%    |
| Intel Wireless 7265                                                                                                | 3         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                                                                | 3         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 2         | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 2         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 2.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                      | 2         | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 2         | 2.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 2.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]                                                 | 1         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 1.23%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 1.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                                         | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 1.23%   |
| Intel Wireless 3165                                                                                                | 1         | 1.23%   |
| Intel Wireless 3160                                                                                                | 1         | 1.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                                          | 1         | 1.23%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                                                    | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 1.23%   |
| Intel Centrino Wireless-N 2230                                                                                     | 1         | 1.23%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 1.23%   |
| Intel Centrino Advanced-N 6235                                                                                     | 1         | 1.23%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 1.23%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter                                               | 1         | 1.23%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                                        | 1         | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                                    | 1         | 1.23%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                                                     | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 36        | 46.75%  |
| Intel                 | 27        | 35.06%  |
| ASIX Electronics      | 5         | 6.49%   |
| Lenovo                | 4         | 5.19%   |
| Broadcom              | 2         | 2.6%    |
| Qualcomm Atheros      | 1         | 1.3%    |
| JMicron Technology    | 1         | 1.3%    |
| D-Link                | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 27.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 14.81%  |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 6.17%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 4.94%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 3.7%    |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.7%    |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 2.47%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 2.47%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 2.47%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 2.47%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 1.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.23%   |
| Lenovo USB-C to LAN                                                    | 1         | 1.23%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                       | 1         | 1.23%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.23%   |
| Intel Ethernet controller                                              | 1         | 1.23%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.23%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 1.23%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.23%   |
| D-Link DUBE250 2.5GbE Adapter                                          | 1         | 1.23%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.23%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 54.11%  |
| Ethernet | 67        | 45.89%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 63.92%  |
| Ethernet | 35        | 36.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 53        | 64.63%  |
| 1     | 27        | 32.93%  |
| 3     | 1         | 1.22%   |
| 0     | 1         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 73.17%  |
| Yes  | 22        | 26.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 66.2%   |
| Realtek Semiconductor           | 8         | 11.27%  |
| Qualcomm Atheros Communications | 5         | 7.04%   |
| Foxconn / Hon Hai               | 3         | 4.23%   |
| Broadcom                        | 3         | 4.23%   |
| Ralink                          | 1         | 1.41%   |
| IMC Networks                    | 1         | 1.41%   |
| Hewlett-Packard                 | 1         | 1.41%   |
| Dell                            | 1         | 1.41%   |
| Apple                           | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 20        | 28.17%  |
| Intel AX201 Bluetooth                              | 13        | 18.31%  |
| Realtek Bluetooth Radio                            | 7         | 9.86%   |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 5.63%   |
| Intel Bluetooth Device                             | 4         | 5.63%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 3         | 4.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 3         | 4.23%   |
| Intel AX200 Bluetooth                              | 3         | 4.23%   |
| Foxconn / Hon Hai Wireless_Device                  | 2         | 2.82%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 1.41%   |
| Ralink RT3290 Bluetooth                            | 1         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.41%   |
| Intel AX210 Bluetooth                              | 1         | 1.41%   |
| IMC Networks Wireless_Device                       | 1         | 1.41%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.41%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth        | 1         | 1.41%   |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 1.41%   |
| Broadcom HP Portable Bumble Bee                    | 1         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.41%   |
| Apple Bluetooth Host Controller                    | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 54.92%  |
| Nvidia                | 17        | 13.93%  |
| AMD                   | 13        | 10.66%  |
| Logitech              | 4         | 3.28%   |
| Lenovo                | 3         | 2.46%   |
| Hewlett-Packard       | 2         | 1.64%   |
| GN Netcom             | 2         | 1.64%   |
| Conexant Systems      | 2         | 1.64%   |
| C-Media Electronics   | 2         | 1.64%   |
| VIA Technologies      | 1         | 0.82%   |
| Texas Instruments     | 1         | 0.82%   |
| Tenx Technology       | 1         | 0.82%   |
| Saitek                | 1         | 0.82%   |
| Realtek Semiconductor | 1         | 0.82%   |
| Plantronics           | 1         | 0.82%   |
| JMTek                 | 1         | 0.82%   |
| Huawei Technologies   | 1         | 0.82%   |
| Creative Technology   | 1         | 0.82%   |
| ASUSTek Computer      | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 7.04%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 6.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 5.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 5.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 5.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 3.52%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.11%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.11%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.41%   |
| Hewlett-Packard USB Audio                                                  | 2         | 1.41%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 1.41%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.41%   |
| VIA Technologies VX1                                                       | 1         | 0.7%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.7%    |
| Tenx Technology USB AUDIO                                                  | 1         | 0.7%    |
| Saitek Cyborg F.R.E.Q.5 Gaming Headset                                     | 1         | 0.7%    |
| Realtek Semiconductor USB Audio                                            | 1         | 0.7%    |
| Plantronics Blackwire 3220 Series                                          | 1         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia Audio device                                                        | 1         | 0.7%    |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 18        | 34.62%  |
| Samsung Electronics | 15        | 28.85%  |
| Micron Technology   | 5         | 9.62%   |
| Crucial             | 4         | 7.69%   |
| Kingston            | 2         | 3.85%   |
| Unknown (0x0080)    | 1         | 1.92%   |
| Smart               | 1         | 1.92%   |
| Ramaxel Technology  | 1         | 1.92%   |
| Magnum Tech         | 1         | 1.92%   |
| Lexar Co Limited    | 1         | 1.92%   |
| Lexar               | 1         | 1.92%   |
| G.Skill             | 1         | 1.92%   |
| A-DATA Technology   | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 5.66%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 2         | 3.77%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.77%   |
| Unknown (0x0080) RAM Module 16GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.89%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 1.89%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.89%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 1.89%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.89%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.89%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.89%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.89%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.89%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 1.89%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.89%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.89%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.89%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.89%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB LPDDR5 5500MT/s                  | 1         | 1.89%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.89%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.89%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.89%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 1         | 1.89%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 59.57%  |
| DDR3   | 11        | 23.4%   |
| LPDDR5 | 3         | 6.38%   |
| DDR5   | 3         | 6.38%   |
| LPDDR4 | 1         | 2.13%   |
| LPDDR3 | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 85.42%  |
| Row Of Chips | 6         | 12.5%   |
| Unknown      | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 50%     |
| 16384 | 13        | 26%     |
| 4096  | 9         | 18%     |
| 32768 | 3         | 6%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 15        | 31.25%  |
| 2667  | 11        | 22.92%  |
| 1600  | 8         | 16.67%  |
| 4800  | 3         | 6.25%   |
| 2400  | 3         | 6.25%   |
| 6400  | 2         | 4.17%   |
| 2133  | 2         | 4.17%   |
| 1066  | 2         | 4.17%   |
| 5500  | 1         | 2.08%   |
| 4266  | 1         | 2.08%   |

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
| Chicony Electronics                    | 18        | 24.32%  |
| IMC Networks                           | 12        | 16.22%  |
| Microdia                               | 8         | 10.81%  |
| Realtek Semiconductor                  | 7         | 9.46%   |
| Bison Electronics                      | 4         | 5.41%   |
| Syntek                                 | 3         | 4.05%   |
| Sunplus Innovation Technology          | 3         | 4.05%   |
| Luxvisions Innotech Limited            | 3         | 4.05%   |
| Logitech                               | 3         | 4.05%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.05%   |
| Quanta                                 | 2         | 2.7%    |
| USB Camera                             | 1         | 1.35%   |
| Suyin                                  | 1         | 1.35%   |
| Sonix Technology                       | 1         | 1.35%   |
| Silicon Motion                         | 1         | 1.35%   |
| Lite-On Technology                     | 1         | 1.35%   |
| Lenovo                                 | 1         | 1.35%   |
| Intel                                  | 1         | 1.35%   |
| Apple                                  | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 13.33%  |
| Microdia Integrated_Webcam_HD                       | 6         | 8%      |
| IMC Networks Integrated Camera                      | 5         | 6.67%   |
| Realtek Integrated_Webcam_HD                        | 4         | 5.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 4%      |
| Chicony HP HD Camera                                | 3         | 4%      |
| Syntek Lenovo EasyCamera                            | 2         | 2.67%   |
| Chicony HD WebCam                                   | 2         | 2.67%   |
| Bison Integrated RGB Camera                         | 2         | 2.67%   |
| USB Camera USB Camera                               | 1         | 1.33%   |
| Syntek Integrated Camera                            | 1         | 1.33%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.33%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.33%   |
| Sunplus FHD Camera Microphone                       | 1         | 1.33%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.33%   |
| Silicon Motion Lenovo EasyCamera                    | 1         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.33%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.33%   |
| Realtek EasyCamera                                  | 1         | 1.33%   |
| Quanta HP Webcam                                    | 1         | 1.33%   |
| Quanta HP 5MP Camera                                | 1         | 1.33%   |
| Microdia Webcam Vitade AF                           | 1         | 1.33%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.33%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 1.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.33%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.33%   |
| Logitech HD Webcam C615                             | 1         | 1.33%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.33%   |
| Logitech BRIO Ultra HD Webcam                       | 1         | 1.33%   |
| Lite-On HP HD Webcam                                | 1         | 1.33%   |
| Lenovo UVC Camera                                   | 1         | 1.33%   |
| Intel RealSense 3D Camera (Front F200)              | 1         | 1.33%   |
| IMC Networks TOSHIBA Web Camera - HD                | 1         | 1.33%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.33%   |
| IMC Networks HP TrueVision HD Camera                | 1         | 1.33%   |
| IMC Networks HD Camera                              | 1         | 1.33%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 1.33%   |
| Chicony thinkpad t430s camera                       | 1         | 1.33%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 32%     |
| Synaptics                  | 8         | 32%     |
| Shenzhen Goodix Technology | 4         | 16%     |
| Upek                       | 2         | 8%      |
| LighTuning Technology      | 1         | 4%      |
| Elan Microelectronics      | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 12%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 8%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 8%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 8%      |
| Synaptics UWP WBDI Device                                                  | 2         | 8%      |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 8%      |
| Shenzhen Goodix FingerPrint                                                | 2         | 8%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 4%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4%      |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4%      |
| Elan ELAN:Fingerprint                                                      | 1         | 4%      |
| AuthenTec AES2810                                                          | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Alcor Micro | 3         | 42.86%  |
| O2 Micro    | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Broadcom 58200                                                               | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 39        | 47.56%  |
| 1     | 35        | 42.68%  |
| 2     | 7         | 8.54%   |
| 3     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 25        | 48.08%  |
| Graphics card         | 7         | 13.46%  |
| Net/wireless          | 5         | 9.62%   |
| Multimedia controller | 4         | 7.69%   |
| Net/ethernet          | 3         | 5.77%   |
| Chipcard              | 3         | 5.77%   |
| Unassigned class      | 1         | 1.92%   |
| Sound                 | 1         | 1.92%   |
| Firewire controller   | 1         | 1.92%   |
| Card reader           | 1         | 1.92%   |
| Bluetooth             | 1         | 1.92%   |

