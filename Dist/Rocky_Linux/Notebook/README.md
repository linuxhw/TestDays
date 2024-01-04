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

Total: 99

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 9.1 | 22        | 27.16%  |
| Rocky Linux 9.2 | 14        | 17.28%  |
| Rocky Linux 8.5 | 11        | 13.58%  |
| Rocky Linux 9.0 | 9         | 11.11%  |
| Rocky Linux 8.4 | 8         | 9.88%   |
| Rocky Linux 8.8 | 7         | 8.64%   |
| Rocky Linux 9.3 | 4         | 4.94%   |
| Rocky Linux 8.7 | 3         | 3.7%    |
| Rocky Linux 8.9 | 1         | 1.23%   |
| Rocky Linux 8.6 | 1         | 1.23%   |
| Rocky Linux 8.3 | 1         | 1.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 79        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 10.84%  |
| 5.14.0-284.25.1.el9_2.x86_64     | 5         | 6.02%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 4.82%   |
| 5.14.0-362.8.1.el9_3.x86_64      | 4         | 4.82%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 4         | 4.82%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 4         | 4.82%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 4         | 4.82%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 4.82%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 3         | 3.61%   |
| 4.18.0-477.27.1.el8_8.x86_64     | 3         | 3.61%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 3.61%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 2.41%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 2         | 2.41%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 2.41%   |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 2.41%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 2.41%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 2.41%   |
| 4.18.0-305.el8.x86_64            | 2         | 2.41%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 2.41%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 2.41%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 2.41%   |
| 6.4.12-1.el8.elrepo.x86_64       | 1         | 1.2%    |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 1.2%    |
| 6.2.10-1.el8.elrepo.x86_64       | 1         | 1.2%    |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.2%    |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 1.2%    |
| 5.14.0-70.30.1.el9_0.x86_64      | 1         | 1.2%    |
| 5.14.0-70.17.1.el9_0.x86_64      | 1         | 1.2%    |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.2%    |
| 5.14.0-284.11.1.el9_2.x86_64     | 1         | 1.2%    |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 1.2%    |
| 5.10.89-1.el8.x86_64             | 1         | 1.2%    |
| 4.18.0-513.9.1.el8_9.x86_64      | 1         | 1.2%    |
| 4.18.0-477.21.1.el8_8.x86_64     | 1         | 1.2%    |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.2%    |
| 4.18.0-348.2.1.el8_5.x86_64      | 1         | 1.2%    |
| 4.18.0-240.22.1.el8.x86_64       | 1         | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 48        | 60%     |
| 4.18.0  | 26        | 32.5%   |
| 6.4.12  | 1         | 1.25%   |
| 6.2.12  | 1         | 1.25%   |
| 6.2.10  | 1         | 1.25%   |
| 5.4.157 | 1         | 1.25%   |
| 5.16.15 | 1         | 1.25%   |
| 5.10.89 | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 48        | 60%     |
| 4.18    | 26        | 32.5%   |
| 6.2     | 2         | 2.5%    |
| 6.4     | 1         | 1.25%   |
| 5.4     | 1         | 1.25%   |
| 5.16    | 1         | 1.25%   |
| 5.10    | 1         | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 79        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 57        | 72.15%  |
| KDE5          | 7         | 8.86%   |
| MATE          | 6         | 7.59%   |
| XFCE          | 3         | 3.8%    |
| X-Cinnamon    | 3         | 3.8%    |
| Unknown       | 2         | 2.53%   |
| GNOME Classic | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 48        | 60.76%  |
| X11     | 29        | 36.71%  |
| Tty     | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 37        | 46.84%  |
| GDM     | 31        | 39.24%  |
| LightDM | 6         | 7.59%   |
| SDDM    | 5         | 6.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 56        | 70.89%  |
| de_DE | 3         | 3.8%    |
| ru_RU | 2         | 2.53%   |
| pt_BR | 2         | 2.53%   |
| it_IT | 2         | 2.53%   |
| es_ES | 2         | 2.53%   |
| en_ZA | 2         | 2.53%   |
| en_IE | 2         | 2.53%   |
| en_CA | 2         | 2.53%   |
| C     | 2         | 2.53%   |
| zh_TW | 1         | 1.27%   |
| fr_FR | 1         | 1.27%   |
| en_GB | 1         | 1.27%   |
| ca_ES | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 65        | 82.28%  |
| BIOS | 14        | 17.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 68        | 86.08%  |
| Ext4 | 10        | 12.66%  |
| Ext3 | 1         | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 39        | 49.37%  |
| Unknown | 36        | 45.57%  |
| MBR     | 4         | 5.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 88.61%  |
| Yes       | 9         | 11.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 78.48%  |
| Yes       | 17        | 21.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 29        | 36.71%  |
| Hewlett-Packard  | 17        | 21.52%  |
| Dell             | 15        | 18.99%  |
| ASUSTek Computer | 7         | 8.86%   |
| Toshiba          | 2         | 2.53%   |
| Positivo         | 2         | 2.53%   |
| Acer             | 2         | 2.53%   |
| HUAWEI           | 1         | 1.27%   |
| Clevo            | 1         | 1.27%   |
| Beelink          | 1         | 1.27%   |
| BANGHO           | 1         | 1.27%   |
| Apple            | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP EliteBook 840 G5                      | 2         | 2.53%   |
| Toshiba TECRA W50-A                      | 1         | 1.27%   |
| Toshiba Satellite E45-B                  | 1         | 1.27%   |
| Positivo Q464C                           | 1         | 1.27%   |
| Positivo Mobile                          | 1         | 1.27%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900 | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 1.27%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 1.27%   |
| Lenovo ThinkPad W500 406132G             | 1         | 1.27%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 1.27%   |
| Lenovo ThinkPad T430u 86147MG            | 1         | 1.27%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 1.27%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 1.27%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 1.27%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 1.27%   |
| Lenovo ThinkPad T14 Gen 3 21AH00HXGE     | 1         | 1.27%   |
| Lenovo ThinkPad P15s Gen 1 20T4CTO1WW    | 1         | 1.27%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV     | 1         | 1.27%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 1.27%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK      | 1         | 1.27%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB     | 1         | 1.27%   |
| Lenovo Slim 7 ProX 14ARH7 82V2           | 1         | 1.27%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 1.27%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.27%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.27%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 1.27%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.27%   |
| Lenovo IdeaPad S210 Touch 20257          | 1         | 1.27%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 1         | 1.27%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 1.27%   |
| Lenovo IdeaPad 3 15ITL6 82H8             | 1         | 1.27%   |
| Lenovo IdeaPad 1 14IGL7 82V6             | 1         | 1.27%   |
| Lenovo G450 2949                         | 1         | 1.27%   |
| HUAWEI KLVD-WXX9                         | 1         | 1.27%   |
| HP ZBook 15u G6                          | 1         | 1.27%   |
| HP ZBook 15u G5                          | 1         | 1.27%   |
| HP ZBook 15 G3                           | 1         | 1.27%   |
| HP ZBook 15 G2                           | 1         | 1.27%   |
| HP ProBook 645 G1                        | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 17        | 21.52%  |
| Lenovo IdeaPad     | 8         | 10.13%  |
| HP EliteBook       | 6         | 7.59%   |
| Dell Latitude      | 5         | 6.33%   |
| HP ZBook           | 4         | 5.06%   |
| HP Laptop          | 4         | 5.06%   |
| Dell XPS           | 4         | 5.06%   |
| ASUS ASUS          | 3         | 3.8%    |
| Lenovo Legion      | 2         | 2.53%   |
| HP ProBook         | 2         | 2.53%   |
| Dell Vostro        | 2         | 2.53%   |
| Dell Precision     | 2         | 2.53%   |
| Dell Inspiron      | 2         | 2.53%   |
| Acer Aspire        | 2         | 2.53%   |
| Toshiba TECRA      | 1         | 1.27%   |
| Toshiba Satellite  | 1         | 1.27%   |
| Positivo Q464C     | 1         | 1.27%   |
| Positivo Mobile    | 1         | 1.27%   |
| Lenovo Slim        | 1         | 1.27%   |
| Lenovo G450        | 1         | 1.27%   |
| HUAWEI KLVD-WXX9   | 1         | 1.27%   |
| HP Pavilion        | 1         | 1.27%   |
| Clevo P170EM       | 1         | 1.27%   |
| Beelink BT3        | 1         | 1.27%   |
| BANGHO BES         | 1         | 1.27%   |
| ASUS VivoBook      | 1         | 1.27%   |
| ASUS UX430UNR      | 1         | 1.27%   |
| ASUS ROG           | 1         | 1.27%   |
| ASUS G752VM        | 1         | 1.27%   |
| Apple MacBookPro11 | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 12        | 15.19%  |
| 2020 | 11        | 13.92%  |
| 2021 | 8         | 10.13%  |
| 2019 | 8         | 10.13%  |
| 2018 | 8         | 10.13%  |
| 2017 | 5         | 6.33%   |
| 2014 | 5         | 6.33%   |
| 2012 | 5         | 6.33%   |
| 2015 | 4         | 5.06%   |
| 2013 | 3         | 3.8%    |
| 2011 | 3         | 3.8%    |
| 2016 | 2         | 2.53%   |
| 2010 | 2         | 2.53%   |
| 2009 | 2         | 2.53%   |
| 2023 | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 79        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 62        | 78.48%  |
| Enabled  | 17        | 21.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 26        | 32.91%  |
| 4.01-8.0    | 18        | 22.78%  |
| 32.01-64.0  | 16        | 20.25%  |
| 16.01-24.0  | 8         | 10.13%  |
| 3.01-4.0    | 6         | 7.59%   |
| 24.01-32.0  | 3         | 3.8%    |
| 64.01-256.0 | 2         | 2.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 26        | 30.95%  |
| 3.01-4.0   | 18        | 21.43%  |
| 2.01-3.0   | 18        | 21.43%  |
| 8.01-16.0  | 10        | 11.9%   |
| 1.01-2.0   | 8         | 9.52%   |
| 0.51-1.0   | 2         | 2.38%   |
| 24.01-32.0 | 1         | 1.19%   |
| 16.01-24.0 | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 81.01%  |
| 2      | 10        | 12.66%  |
| 3      | 4         | 5.06%   |
| 4      | 1         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 84.81%  |
| Yes       | 12        | 15.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 82.5%   |
| No        | 14        | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 96.2%   |
| No        | 3         | 3.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 86.08%  |
| No        | 11        | 13.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 25        | 31.65%  |
| Russia       | 4         | 5.06%   |
| Germany      | 4         | 5.06%   |
| Spain        | 3         | 3.8%    |
| Poland       | 3         | 3.8%    |
| Italy        | 3         | 3.8%    |
| Brazil       | 3         | 3.8%    |
| South Africa | 2         | 2.53%   |
| Netherlands  | 2         | 2.53%   |
| Ireland      | 2         | 2.53%   |
| Hungary      | 2         | 2.53%   |
| Czechia      | 2         | 2.53%   |
| Canada       | 2         | 2.53%   |
| Belgium      | 2         | 2.53%   |
| Argentina    | 2         | 2.53%   |
| Uzbekistan   | 1         | 1.27%   |
| UK           | 1         | 1.27%   |
| UAE          | 1         | 1.27%   |
| Turkey       | 1         | 1.27%   |
| Taiwan       | 1         | 1.27%   |
| Sweden       | 1         | 1.27%   |
| Slovakia     | 1         | 1.27%   |
| Saudi Arabia | 1         | 1.27%   |
| Pakistan     | 1         | 1.27%   |
| Norway       | 1         | 1.27%   |
| Malaysia     | 1         | 1.27%   |
| Kenya        | 1         | 1.27%   |
| Kazakhstan   | 1         | 1.27%   |
| France       | 1         | 1.27%   |
| Croatia      | 1         | 1.27%   |
| China        | 1         | 1.27%   |
| Bulgaria     | 1         | 1.27%   |
| Austria      | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Philadelphia           | 2         | 2.53%   |
| Moscow                 | 2         | 2.53%   |
| Enschede               | 2         | 2.53%   |
| Budapest               | 2         | 2.53%   |
| Albuquerque            | 2         | 2.53%   |
| Žilina                | 1         | 1.27%   |
| Xi'an                  | 1         | 1.27%   |
| Woking                 | 1         | 1.27%   |
| Westerville            | 1         | 1.27%   |
| Walnut Creek           | 1         | 1.27%   |
| Viggiù                | 1         | 1.27%   |
| Vienna                 | 1         | 1.27%   |
| Troisdorf              | 1         | 1.27%   |
| Torrington             | 1         | 1.27%   |
| Taoyuan City           | 1         | 1.27%   |
| Syracuse               | 1         | 1.27%   |
| Spokane                | 1         | 1.27%   |
| Split                  | 1         | 1.27%   |
| Sofia                  | 1         | 1.27%   |
| Smolensk               | 1         | 1.27%   |
| Senigallia             | 1         | 1.27%   |
| Scarborough            | 1         | 1.27%   |
| Sao Paulo              | 1         | 1.27%   |
| San Miguel de Tucumán | 1         | 1.27%   |
| Rosario                | 1         | 1.27%   |
| Riyadh                 | 1         | 1.27%   |
| Rawalpindi             | 1         | 1.27%   |
| Qualicum Beach         | 1         | 1.27%   |
| Prague                 | 1         | 1.27%   |
| Ottignies              | 1         | 1.27%   |
| Oslo                   | 1         | 1.27%   |
| Örebro                | 1         | 1.27%   |
| Olympia                | 1         | 1.27%   |
| Oakley                 | 1         | 1.27%   |
| Nyahururu              | 1         | 1.27%   |
| Nur-Sultan             | 1         | 1.27%   |
| Niceville              | 1         | 1.27%   |
| Mugla                  | 1         | 1.27%   |
| Mossel Bay             | 1         | 1.27%   |
| Montreal               | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 24        | 28     | 24%     |
| SanDisk                   | 9         | 11     | 9%      |
| WDC                       | 8         | 8      | 8%      |
| Micron Technology         | 7         | 7      | 7%      |
| Toshiba                   | 5         | 6      | 5%      |
| Kingston                  | 5         | 5      | 5%      |
| Intel                     | 5         | 5      | 5%      |
| Unknown                   | 4         | 4      | 4%      |
| SK hynix                  | 3         | 5      | 3%      |
| Seagate                   | 3         | 3      | 3%      |
| Lexar                     | 2         | 2      | 2%      |
| Dogfish                   | 2         | 2      | 2%      |
| Crucial                   | 2         | 2      | 2%      |
| A-DATA Technology         | 2         | 2      | 2%      |
| Union Memory (Shenzhen)   | 1         | 1      | 1%      |
| Union Memory              | 1         | 1      | 1%      |
| UMIS                      | 1         | 1      | 1%      |
| StoreJet                  | 1         | 1      | 1%      |
| PNY                       | 1         | 2      | 1%      |
| Phison                    | 1         | 2      | 1%      |
| Patriot                   | 1         | 1      | 1%      |
| Micron/Crucial Technology | 1         | 1      | 1%      |
| LITEONIT                  | 1         | 1      | 1%      |
| LITEON                    | 1         | 1      | 1%      |
| KIOXIA                    | 1         | 1      | 1%      |
| JMicron Technology        | 1         | 1      | 1%      |
| INDMEM                    | 1         | 1      | 1%      |
| HS-SSD-C100               | 1         | 1      | 1%      |
| Hitachi                   | 1         | 1      | 1%      |
| Fujitsu                   | 1         | 1      | 1%      |
| ASMT                      | 1         | 1      | 1%      |
| AGI                       | 1         | 1      | 1%      |
| ADATA Technology          | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4         | 3.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 3         | 2.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 3         | 2.83%   |
| Unknown MMC Card  64GB                              | 2         | 1.89%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 2         | 1.89%   |
| Lexar 512GB SSD                                     | 2         | 1.89%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.94%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.94%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 0.94%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 0.94%   |
| WDC WD40 EFRX-68N32N0 4TB                           | 1         | 0.94%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.94%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.94%   |
| WDC WD Blue SA510 M.2 2280 1000GB                   | 1         | 0.94%   |
| Unknown SD/MMC/MS PRO 512GB                         | 1         | 0.94%   |
| Unknown S0J38Y  64GB                                | 1         | 0.94%   |
| Union Memory UMIS RPJTJ128MEE1MWX 128GB             | 1         | 0.94%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1         | 0.94%   |
| UMIS RPFTJ128PDD2EWX 128GB                          | 1         | 0.94%   |
| Toshiba THNSNJ512GACU 512GB SSD                     | 1         | 0.94%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 0.94%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 0.94%   |
| Toshiba KXG6AZNV1T02 1TB                            | 1         | 0.94%   |
| Toshiba KXG6APNV2T04 2TB                            | 1         | 0.94%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 0.94%   |
| StoreJet Disk 1TB                                   | 1         | 0.94%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB           | 1         | 0.94%   |
| SK hynix SHPP41-2000GM 2TB                          | 1         | 0.94%   |
| SK hynix NVMe SSD Drive 512GB                       | 1         | 0.94%   |
| SK hynix BC511 NVMe 512GB                           | 1         | 0.94%   |
| Seagate ST9320325AS 320GB                           | 1         | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 0.94%   |
| Seagate One Touch HDD 5TB                           | 1         | 0.94%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 0.94%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1TB           | 1         | 0.94%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 0.94%   |
| SanDisk SDSSDA120G 120GB                            | 1         | 0.94%   |
| SanDisk SD8SN8U512G1002 512GB SSD                   | 1         | 0.94%   |
| SanDisk SD5SG2256G1052E 256GB SSD                   | 1         | 0.94%   |

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
| Samsung Electronics | 8         | 9      | 23.53%  |
| SanDisk             | 4         | 5      | 11.76%  |
| WDC                 | 3         | 3      | 8.82%   |
| Kingston            | 3         | 3      | 8.82%   |
| Toshiba             | 2         | 2      | 5.88%   |
| Dogfish             | 2         | 2      | 5.88%   |
| Crucial             | 2         | 2      | 5.88%   |
| PNY                 | 1         | 2      | 2.94%   |
| Patriot             | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 1      | 2.94%   |
| LITEON              | 1         | 1      | 2.94%   |
| Lexar               | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| INDMEM              | 1         | 1      | 2.94%   |
| ASMT                | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 47        | 56     | 51.09%  |
| SSD     | 29        | 37     | 31.52%  |
| HDD     | 10        | 12     | 10.87%  |
| MMC     | 3         | 3      | 3.26%   |
| Unknown | 3         | 3      | 3.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 47        | 56     | 51.65%  |
| SATA | 34        | 44     | 37.36%  |
| SAS  | 7         | 8      | 7.69%   |
| MMC  | 3         | 3      | 3.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 24     | 50%     |
| 0.51-1.0   | 14        | 18     | 35%     |
| 1.01-2.0   | 3         | 3      | 7.5%    |
| 3.01-4.0   | 2         | 3      | 5%      |
| 4.01-10.0  | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 25        | 31.65%  |
| 101-250        | 23        | 29.11%  |
| 501-1000       | 14        | 17.72%  |
| 1001-2000      | 5         | 6.33%   |
| 51-100         | 5         | 6.33%   |
| 2001-3000      | 3         | 3.8%    |
| More than 3000 | 2         | 2.53%   |
| 21-50          | 1         | 1.27%   |
| 1-20           | 1         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 27        | 33.33%  |
| 21-50          | 21        | 25.93%  |
| 101-250        | 13        | 16.05%  |
| 51-100         | 11        | 13.58%  |
| 251-500        | 4         | 4.94%   |
| 1001-2000      | 2         | 2.47%   |
| 501-1000       | 2         | 2.47%   |
| More than 3000 | 1         | 1.23%   |

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
| Works    | 42        | 56     | 50%     |
| Detected | 41        | 54     | 48.81%  |
| Malfunc  | 1         | 1      | 1.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 45        | 47.87%  |
| Samsung Electronics          | 16        | 17.02%  |
| Micron Technology            | 6         | 6.38%   |
| AMD                          | 6         | 6.38%   |
| SanDisk                      | 5         | 5.32%   |
| Toshiba America Info Systems | 3         | 3.19%   |
| SK hynix                     | 3         | 3.19%   |
| Union Memory (Shenzhen)      | 2         | 2.13%   |
| Kingston Technology Company  | 2         | 2.13%   |
| Shenzhen Longsys Electronics | 1         | 1.06%   |
| Realtek Semiconductor        | 1         | 1.06%   |
| Phison Electronics           | 1         | 1.06%   |
| Micron/Crucial Technology    | 1         | 1.06%   |
| KIOXIA                       | 1         | 1.06%   |
| ADATA Technology             | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 6.93%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 5.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 4.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 4.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.96%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 4         | 3.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 3.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 3.96%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 2.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.97%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.98%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.98%   |
| Intel SSD 660P Series                                                          | 2         | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.98%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile     | 2         | 1.98%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                          | 1         | 0.99%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 0.99%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.99%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.99%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.99%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.99%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1         | 0.99%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.99%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.99%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.99%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.99%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.99%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.99%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 0.99%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1         | 0.99%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 0.99%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 0.99%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 0.99%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 47        | 48.45%  |
| SATA | 38        | 39.18%  |
| RAID | 7         | 7.22%   |
| IDE  | 5         | 5.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 83.54%  |
| AMD    | 13        | 16.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 5.06%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 3.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 3.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.53%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 2         | 2.53%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 2.53%   |
| Intel 12th Gen Core i7-1260P                | 2         | 2.53%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 2         | 2.53%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.27%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.27%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.27%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.27%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.27%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 1.27%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.27%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz          | 1         | 1.27%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.27%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.27%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.27%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.27%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.27%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.27%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.27%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.27%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 27        | 34.18%  |
| Other                   | 18        | 22.78%  |
| Intel Core i5           | 14        | 17.72%  |
| AMD Ryzen 5             | 4         | 5.06%   |
| Intel Celeron           | 2         | 2.53%   |
| Intel Atom              | 2         | 2.53%   |
| AMD Ryzen 7             | 2         | 2.53%   |
| AMD Ryzen 5 PRO         | 2         | 2.53%   |
| Intel Pentium Silver    | 1         | 1.27%   |
| Intel Pentium Dual-Core | 1         | 1.27%   |
| Intel Core i3           | 1         | 1.27%   |
| Intel Core 2 Duo        | 1         | 1.27%   |
| AMD Ryzen 9             | 1         | 1.27%   |
| AMD Ryzen 3             | 1         | 1.27%   |
| AMD A8                  | 1         | 1.27%   |
| AMD A10                 | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 37        | 46.84%  |
| 2      | 20        | 25.32%  |
| 6      | 8         | 10.13%  |
| 10     | 5         | 6.33%   |
| 8      | 5         | 6.33%   |
| 12     | 2         | 2.53%   |
| 14     | 1         | 1.27%   |
| 1      | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 79        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 83.75%  |
| 1      | 13        | 16.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 79        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 8         | 10%     |
| Unknown    | 8         | 10%     |
| 0x306c3    | 7         | 8.75%   |
| 0x806ea    | 6         | 7.5%    |
| 0x806ec    | 5         | 6.25%   |
| 0xa0652    | 4         | 5%      |
| 0x306a9    | 4         | 5%      |
| 0x506e3    | 3         | 3.75%   |
| 0x906a4    | 2         | 2.5%    |
| 0x906a3    | 2         | 2.5%    |
| 0x806e9    | 2         | 2.5%    |
| 0x306d4    | 2         | 2.5%    |
| 0x206a7    | 2         | 2.5%    |
| 0x0a50000d | 2         | 2.5%    |
| 0x0a50000c | 2         | 2.5%    |
| 0x08600104 | 2         | 2.5%    |
| 0x906ea    | 1         | 1.25%   |
| 0x806d1    | 1         | 1.25%   |
| 0x706e5    | 1         | 1.25%   |
| 0x706a8    | 1         | 1.25%   |
| 0x706a1    | 1         | 1.25%   |
| 0x406e3    | 1         | 1.25%   |
| 0x406c4    | 1         | 1.25%   |
| 0x40661    | 1         | 1.25%   |
| 0x40651    | 1         | 1.25%   |
| 0x20655    | 1         | 1.25%   |
| 0x1067a    | 1         | 1.25%   |
| 0x10676    | 1         | 1.25%   |
| 0x0a404102 | 1         | 1.25%   |
| 0x0a404101 | 1         | 1.25%   |
| 0x08a00006 | 1         | 1.25%   |
| 0x08108102 | 1         | 1.25%   |
| 0x06006705 | 1         | 1.25%   |
| 0x06001119 | 1         | 1.25%   |
| 0x06001116 | 1         | 1.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 17.72%  |
| Haswell          | 9         | 11.39%  |
| TigerLake        | 8         | 10.13%  |
| Alderlake Hybrid | 8         | 10.13%  |
| Skylake          | 5         | 6.33%   |
| IvyBridge        | 5         | 6.33%   |
| Zen 3            | 4         | 5.06%   |
| CometLake        | 4         | 5.06%   |
| Unknown          | 3         | 3.8%    |
| Zen 2            | 2         | 2.53%   |
| Silvermont       | 2         | 2.53%   |
| SandyBridge      | 2         | 2.53%   |
| Piledriver       | 2         | 2.53%   |
| Penryn           | 2         | 2.53%   |
| Icelake          | 2         | 2.53%   |
| Goldmont plus    | 2         | 2.53%   |
| Broadwell        | 2         | 2.53%   |
| Zen+             | 1         | 1.27%   |
| Westmere         | 1         | 1.27%   |
| Excavator        | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 56.88%  |
| Nvidia | 32        | 29.36%  |
| AMD    | 15        | 13.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 7.27%   |
| Intel UHD Graphics 620                                                                   | 6         | 5.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 3.64%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 4         | 3.64%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 2.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.73%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 2.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.82%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 1.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.82%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 1.82%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.82%   |
| Intel HD Graphics 620                                                                    | 2         | 1.82%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.82%   |
| Intel HD Graphics 530                                                                    | 2         | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.82%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.82%   |
| AMD Barcelo                                                                              | 2         | 1.82%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.91%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.91%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.91%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.91%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.91%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.91%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.91%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.91%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.91%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 0.91%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 0.91%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.91%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 0.91%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 1         | 0.91%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 45.57%  |
| Intel + Nvidia | 23        | 29.11%  |
| 1 x AMD        | 7         | 8.86%   |
| 1 x Nvidia     | 5         | 6.33%   |
| AMD + Nvidia   | 4         | 5.06%   |
| Intel + AMD    | 3         | 3.8%    |
| 2 x AMD        | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 84.81%  |
| Proprietary | 11        | 13.92%  |
| Unknown     | 1         | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 56.25%  |
| 3.01-4.0   | 12        | 15%     |
| 1.01-2.0   | 8         | 10%     |
| 0.01-0.5   | 7         | 8.75%   |
| 5.01-6.0   | 3         | 3.75%   |
| 0.51-1.0   | 3         | 3.75%   |
| 7.01-8.0   | 2         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 15.6%   |
| LG Display              | 16        | 14.68%  |
| BOE                     | 14        | 12.84%  |
| Goldstar                | 10        | 9.17%   |
| Chimei Innolux          | 9         | 8.26%   |
| Samsung Electronics     | 8         | 7.34%   |
| Dell                    | 8         | 7.34%   |
| Sharp                   | 5         | 4.59%   |
| Philips                 | 3         | 2.75%   |
| InfoVision              | 3         | 2.75%   |
| PANDA                   | 2         | 1.83%   |
| Lenovo                  | 2         | 1.83%   |
| CSO                     | 2         | 1.83%   |
| AOC                     | 2         | 1.83%   |
| Sony                    | 1         | 0.92%   |
| Panasonic               | 1         | 0.92%   |
| Hewlett-Packard         | 1         | 0.92%   |
| Gigabyte Technology     | 1         | 0.92%   |
| Chi Mei Optoelectronics | 1         | 0.92%   |
| BenQ                    | 1         | 0.92%   |
| Apple                   | 1         | 0.92%   |
| Acer                    | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.77%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.77%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 1.77%   |
| Sony LCD Monitor MS_003C 1366x768 309x173mm 13.9-inch                 | 1         | 0.88%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 0.88%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.88%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 0.88%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 0.88%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.88%   |
| Philips PHL 499P9 PHL092A 3840x1080 1193x336mm 48.8-inch              | 1         | 0.88%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 0.88%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 0.88%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.88%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 47%     |
| 1366x768 (WXGA)    | 14        | 14%     |
| 2560x1440 (QHD)    | 6         | 6%      |
| 1920x1200 (WUXGA)  | 5         | 5%      |
| 3840x2160 (4K)     | 4         | 4%      |
| 3440x1440          | 4         | 4%      |
| 2560x1080          | 4         | 4%      |
| 3840x2400          | 3         | 3%      |
| 1600x900 (HD+)     | 3         | 3%      |
| 3840x1080          | 2         | 2%      |
| 1680x1050 (WSXGA+) | 2         | 2%      |
| 3072x1920          | 1         | 1%      |
| 2880x1800          | 1         | 1%      |
| 2240x1400          | 1         | 1%      |
| 2160x1440          | 1         | 1%      |
| 1360x768           | 1         | 1%      |
| Unknown            | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 33        | 30%     |
| 14     | 25        | 22.73%  |
| 13     | 10        | 9.09%   |
| 27     | 8         | 7.27%   |
| 17     | 7         | 6.36%   |
| 34     | 6         | 5.45%   |
| 24     | 5         | 4.55%   |
| 21     | 4         | 3.64%   |
| 31     | 2         | 1.82%   |
| 23     | 2         | 1.82%   |
| 49     | 1         | 0.91%   |
| 48     | 1         | 0.91%   |
| 40     | 1         | 0.91%   |
| 35     | 1         | 0.91%   |
| 22     | 1         | 0.91%   |
| 18     | 1         | 0.91%   |
| 16     | 1         | 0.91%   |
| 12     | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 59.63%  |
| 501-600     | 13        | 11.93%  |
| 401-500     | 7         | 6.42%   |
| 351-400     | 7         | 6.42%   |
| 701-800     | 6         | 5.5%    |
| 201-300     | 5         | 4.59%   |
| 801-900     | 2         | 1.83%   |
| 601-700     | 2         | 1.83%   |
| 1001-1500   | 2         | 1.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 69        | 75%     |
| 16/10 | 12        | 13.04%  |
| 21/9  | 7         | 7.61%   |
| 32/9  | 2         | 2.17%   |
| 3/2   | 2         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 32        | 29.36%  |
| 101-110        | 32        | 29.36%  |
| 201-250        | 10        | 9.17%   |
| 351-500        | 9         | 8.26%   |
| 301-350        | 8         | 7.34%   |
| 121-130        | 7         | 6.42%   |
| 501-1000       | 3         | 2.75%   |
| 71-80          | 2         | 1.83%   |
| 111-120        | 2         | 1.83%   |
| 61-70          | 1         | 0.92%   |
| 151-200        | 1         | 0.92%   |
| 141-150        | 1         | 0.92%   |
| 91-100         | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 47        | 43.52%  |
| 101-120       | 23        | 21.3%   |
| 51-100        | 21        | 19.44%  |
| 161-240       | 10        | 9.26%   |
| More than 240 | 7         | 6.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 60%     |
| 2     | 25        | 31.25%  |
| 3     | 4         | 5%      |
| 0     | 2         | 2.5%    |
| 4     | 1         | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 43.55%  |
| Realtek Semiconductor | 39        | 31.45%  |
| Qualcomm Atheros      | 7         | 5.65%   |
| MediaTek              | 5         | 4.03%   |
| ASIX Electronics      | 5         | 4.03%   |
| Lenovo                | 4         | 3.23%   |
| Broadcom              | 4         | 3.23%   |
| Ralink                | 1         | 0.81%   |
| JMicron Technology    | 1         | 0.81%   |
| Dell                  | 1         | 0.81%   |
| D-Link                | 1         | 0.81%   |
| Broadcom Limited      | 1         | 0.81%   |
| ASUSTek Computer      | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 21        | 13.38%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 12        | 7.64%   |
| Intel Wireless 8265 / 8275                                         | 8         | 5.1%    |
| Intel Wi-Fi 6 AX201                                                | 6         | 3.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 6         | 3.82%   |
| Intel Wireless 7260                                                | 5         | 3.18%   |
| ASIX AX88179 Gigabit Ethernet                                      | 5         | 3.18%   |
| Intel Ethernet Connection I217-LM                                  | 4         | 2.55%   |
| Intel Ethernet Connection (4) I219-LM                              | 4         | 2.55%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 4         | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 3         | 1.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 1.91%   |
| Intel Wireless 8260                                                | 3         | 1.91%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 1.91%   |
| Intel Ethernet Connection (4) I219-V                               | 3         | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 3         | 1.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 2         | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.27%   |
| Lenovo ThinkPad TBT 3 Dock                                         | 2         | 1.27%   |
| Intel Wireless 7265                                                | 2         | 1.27%   |
| Intel Ethernet Connection (6) I219-LM                              | 2         | 1.27%   |
| Intel Ethernet Connection (16) I219-V                              | 2         | 1.27%   |
| Intel Ethernet Connection (16) I219-LM                             | 2         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 2         | 1.27%   |
| Realtek USB 10/100/1G/2.5G LAN                                     | 1         | 0.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R] | 1         | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                              | 1         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                  | 1         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                          | 1         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 66.67%  |
| Realtek Semiconductor | 9         | 11.54%  |
| Qualcomm Atheros      | 6         | 7.69%   |
| MediaTek              | 5         | 6.41%   |
| Broadcom              | 2         | 2.56%   |
| Ralink                | 1         | 1.28%   |
| Dell                  | 1         | 1.28%   |
| Broadcom Limited      | 1         | 1.28%   |
| ASUSTek Computer      | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                                                         | 8         | 10.26%  |
| Intel Wi-Fi 6 AX201                                                                                                | 6         | 7.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 6         | 7.69%   |
| Intel Wireless 7260                                                                                                | 5         | 6.41%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 4         | 5.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 4         | 5.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                        | 3         | 3.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 3.85%   |
| Intel Wireless 8260                                                                                                | 3         | 3.85%   |
| Intel Wi-Fi 6 AX200                                                                                                | 3         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 2         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 2         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 2.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                      | 2         | 2.56%   |
| Intel Wireless 7265                                                                                                | 2         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 2         | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 2.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]                                                 | 1         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 1.28%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 1.28%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 1.28%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                                         | 1         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 1.28%   |
| Intel Wireless 3160                                                                                                | 1         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                             | 1         | 1.28%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 1.28%   |
| Intel Centrino Wireless-N 2230                                                                                     | 1         | 1.28%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 1.28%   |
| Intel Centrino Advanced-N 6235                                                                                     | 1         | 1.28%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 1.28%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter                                               | 1         | 1.28%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                                        | 1         | 1.28%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                                    | 1         | 1.28%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                                                     | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 45.33%  |
| Intel                 | 27        | 36%     |
| ASIX Electronics      | 5         | 6.67%   |
| Lenovo                | 4         | 5.33%   |
| Broadcom              | 2         | 2.67%   |
| Qualcomm Atheros      | 1         | 1.33%   |
| JMicron Technology    | 1         | 1.33%   |
| D-Link                | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 26.58%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 15.19%  |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 6.33%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 5.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 5.06%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.53%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 2.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.53%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 2.53%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 2.53%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.27%   |
| Lenovo USB-C to LAN                                               | 1         | 1.27%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.27%   |
| Intel Ethernet controller                                         | 1         | 1.27%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.27%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.27%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 1.27%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.27%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 53.9%   |
| Ethernet | 65        | 46.1%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 62.77%  |
| Ethernet | 35        | 37.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 51        | 64.56%  |
| 1     | 26        | 32.91%  |
| 3     | 1         | 1.27%   |
| 0     | 1         | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 73.42%  |
| Yes  | 21        | 26.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 64.71%  |
| Realtek Semiconductor           | 8         | 11.76%  |
| Qualcomm Atheros Communications | 5         | 7.35%   |
| Foxconn / Hon Hai               | 3         | 4.41%   |
| Broadcom                        | 3         | 4.41%   |
| Ralink                          | 1         | 1.47%   |
| IMC Networks                    | 1         | 1.47%   |
| Hewlett-Packard                 | 1         | 1.47%   |
| Dell                            | 1         | 1.47%   |
| Apple                           | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 18        | 26.47%  |
| Intel Bluetooth Device                             | 17        | 25%     |
| Realtek Bluetooth Radio                            | 7         | 10.29%  |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 5.88%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 3         | 4.41%   |
| Intel AX200 Bluetooth                              | 3         | 4.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 2.94%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 1.47%   |
| Ralink RT3290 Bluetooth                            | 1         | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.47%   |
| Intel AX210 Bluetooth                              | 1         | 1.47%   |
| IMC Networks Wireless_Device                       | 1         | 1.47%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.47%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth        | 1         | 1.47%   |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 1.47%   |
| Broadcom HP Portable Bumble Bee                    | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.47%   |
| Apple Bluetooth Host Controller                    | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 53.78%  |
| Nvidia                | 17        | 14.29%  |
| AMD                   | 13        | 10.92%  |
| Logitech              | 4         | 3.36%   |
| Lenovo                | 3         | 2.52%   |
| Hewlett-Packard       | 2         | 1.68%   |
| GN Netcom             | 2         | 1.68%   |
| Conexant Systems      | 2         | 1.68%   |
| C-Media Electronics   | 2         | 1.68%   |
| VIA Technologies      | 1         | 0.84%   |
| Texas Instruments     | 1         | 0.84%   |
| Tenx Technology       | 1         | 0.84%   |
| Saitek                | 1         | 0.84%   |
| Realtek Semiconductor | 1         | 0.84%   |
| Plantronics           | 1         | 0.84%   |
| JMTek                 | 1         | 0.84%   |
| Huawei Technologies   | 1         | 0.84%   |
| Creative Technology   | 1         | 0.84%   |
| ASUSTek Computer      | 1         | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 7.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 6.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 5.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 5.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 5.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 3.6%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.16%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 2.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.44%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.44%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.44%   |
| Hewlett-Packard USB Audio                                                  | 2         | 1.44%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 1.44%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.44%   |
| VIA Technologies VX1                                                       | 1         | 0.72%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.72%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.72%   |
| Saitek Cyborg F.R.E.Q.5 Gaming Headset                                     | 1         | 0.72%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.72%   |
| Plantronics Blackwire 3220 Series                                          | 1         | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia Audio device                                                        | 1         | 0.72%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.72%   |
| Logitech Stereo H650e                                                      | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 18        | 36%     |
| Samsung Electronics | 15        | 30%     |
| Micron Technology   | 4         | 8%      |
| Crucial             | 4         | 8%      |
| Kingston            | 2         | 4%      |
| Smart               | 1         | 2%      |
| Ramaxel Technology  | 1         | 2%      |
| Magnum Tech         | 1         | 2%      |
| Lexar Co Limited    | 1         | 2%      |
| Lexar               | 1         | 2%      |
| G.Skill             | 1         | 2%      |
| A-DATA Technology   | 1         | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 5.88%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 2         | 3.92%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.92%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.96%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 1.96%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.96%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 1.96%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.96%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.96%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.96%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.96%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.96%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 1.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.96%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.96%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.96%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.96%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.96%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.96%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB LPDDR5 5500MT/s                  | 1         | 1.96%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 1.96%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.96%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.96%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 1         | 1.96%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s            | 1         | 1.96%   |
| Lexar Co Limited RAM LD4AS008G-2666SC 8GB SODIMM DDR4 2667MT/s   | 1         | 1.96%   |
| Kingston RAM 9905703-006.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 26        | 57.78%  |
| DDR3   | 11        | 24.44%  |
| LPDDR5 | 3         | 6.67%   |
| DDR5   | 3         | 6.67%   |
| LPDDR4 | 1         | 2.22%   |
| LPDDR3 | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 84.78%  |
| Row Of Chips | 6         | 13.04%  |
| Unknown      | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 52.08%  |
| 16384 | 11        | 22.92%  |
| 4096  | 9         | 18.75%  |
| 32768 | 3         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 15        | 32.61%  |
| 2667  | 9         | 19.57%  |
| 1600  | 8         | 17.39%  |
| 4800  | 3         | 6.52%   |
| 2400  | 3         | 6.52%   |
| 6400  | 2         | 4.35%   |
| 2133  | 2         | 4.35%   |
| 1066  | 2         | 4.35%   |
| 5500  | 1         | 2.17%   |
| 4266  | 1         | 2.17%   |

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
| Chicony Electronics                    | 18        | 25%     |
| IMC Networks                           | 12        | 16.67%  |
| Realtek Semiconductor                  | 7         | 9.72%   |
| Microdia                               | 6         | 8.33%   |
| Bison Electronics                      | 4         | 5.56%   |
| Syntek                                 | 3         | 4.17%   |
| Sunplus Innovation Technology          | 3         | 4.17%   |
| Luxvisions Innotech Limited            | 3         | 4.17%   |
| Logitech                               | 3         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.17%   |
| Quanta                                 | 2         | 2.78%   |
| Suyin                                  | 1         | 1.39%   |
| Sonix Technology                       | 1         | 1.39%   |
| Silicon Motion                         | 1         | 1.39%   |
| Lite-On Technology                     | 1         | 1.39%   |
| Lenovo                                 | 1         | 1.39%   |
| Intel                                  | 1         | 1.39%   |
| icSpring                               | 1         | 1.39%   |
| Apple                                  | 1         | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 13.7%   |
| Microdia Integrated_Webcam_HD                       | 5         | 6.85%   |
| IMC Networks Integrated Camera                      | 5         | 6.85%   |
| Realtek Integrated_Webcam_HD                        | 4         | 5.48%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 4.11%   |
| Chicony HP HD Camera                                | 3         | 4.11%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.74%   |
| Chicony HD WebCam                                   | 2         | 2.74%   |
| Bison Integrated RGB Camera                         | 2         | 2.74%   |
| Syntek Integrated Camera                            | 1         | 1.37%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.37%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.37%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.37%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.37%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.37%   |
| Silicon Motion Lenovo EasyCamera                    | 1         | 1.37%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.37%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.37%   |
| Realtek EasyCamera                                  | 1         | 1.37%   |
| Quanta HP Webcam                                    | 1         | 1.37%   |
| Quanta HP 5MP Camera                                | 1         | 1.37%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.37%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 1.37%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.37%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.37%   |
| Logitech HD Webcam C615                             | 1         | 1.37%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.37%   |
| Logitech BRIO Ultra HD Webcam                       | 1         | 1.37%   |
| Lite-On HP HD Webcam                                | 1         | 1.37%   |
| Lenovo UVC Camera                                   | 1         | 1.37%   |
| Intel RealSense 3D Camera (Front F200)              | 1         | 1.37%   |
| IMC Networks TOSHIBA Web Camera - HD                | 1         | 1.37%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.37%   |
| IMC Networks HP TrueVision HD Camera                | 1         | 1.37%   |
| IMC Networks HD Camera                              | 1         | 1.37%   |
| icSpring camera                                     | 1         | 1.37%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 1.37%   |
| Chicony thinkpad t430s camera                       | 1         | 1.37%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.37%   |
| Chicony HP HD Webcam                                | 1         | 1.37%   |

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
| 0     | 36        | 45.57%  |
| 1     | 35        | 44.3%   |
| 2     | 7         | 8.86%   |
| 3     | 1         | 1.27%   |

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

