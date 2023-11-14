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

Total: 93

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 9.1 | 22        | 29.33%  |
| Rocky Linux 9.2 | 13        | 17.33%  |
| Rocky Linux 8.5 | 11        | 14.67%  |
| Rocky Linux 9.0 | 9         | 12%     |
| Rocky Linux 8.4 | 8         | 10.67%  |
| Rocky Linux 8.8 | 7         | 9.33%   |
| Rocky Linux 8.7 | 3         | 4%      |
| Rocky Linux 8.6 | 1         | 1.33%   |
| Rocky Linux 8.3 | 1         | 1.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 74        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 11.69%  |
| 5.14.0-284.25.1.el9_2.x86_64     | 5         | 6.49%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 5.19%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 4         | 5.19%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 4         | 5.19%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 5.19%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 3         | 3.9%    |
| 5.14.0-162.18.1.el9_1.x86_64     | 3         | 3.9%    |
| 4.18.0-477.27.1.el8_8.x86_64     | 3         | 3.9%    |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 3.9%    |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 2.6%    |
| 5.14.0-162.6.1.el9_1.x86_64      | 2         | 2.6%    |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 2.6%    |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 2.6%    |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 2.6%    |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 2.6%    |
| 4.18.0-305.el8.x86_64            | 2         | 2.6%    |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 2.6%    |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 2.6%    |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 2.6%    |
| 6.4.12-1.el8.elrepo.x86_64       | 1         | 1.3%    |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 1.3%    |
| 6.2.10-1.el8.elrepo.x86_64       | 1         | 1.3%    |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.3%    |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 1.3%    |
| 5.14.0-70.30.1.el9_0.x86_64      | 1         | 1.3%    |
| 5.14.0-70.17.1.el9_0.x86_64      | 1         | 1.3%    |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.3%    |
| 5.14.0-284.11.1.el9_2.x86_64     | 1         | 1.3%    |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 1.3%    |
| 5.10.89-1.el8.x86_64             | 1         | 1.3%    |
| 4.18.0-477.21.1.el8_8.x86_64     | 1         | 1.3%    |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.3%    |
| 4.18.0-348.2.1.el8_5.x86_64      | 1         | 1.3%    |
| 4.18.0-240.22.1.el8.x86_64       | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 43        | 57.33%  |
| 4.18.0  | 26        | 34.67%  |
| 6.4.12  | 1         | 1.33%   |
| 6.2.12  | 1         | 1.33%   |
| 6.2.10  | 1         | 1.33%   |
| 5.4.157 | 1         | 1.33%   |
| 5.16.15 | 1         | 1.33%   |
| 5.10.89 | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 43        | 57.33%  |
| 4.18    | 26        | 34.67%  |
| 6.2     | 2         | 2.67%   |
| 6.4     | 1         | 1.33%   |
| 5.4     | 1         | 1.33%   |
| 5.16    | 1         | 1.33%   |
| 5.10    | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 74        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 52        | 70.27%  |
| KDE5          | 7         | 9.46%   |
| MATE          | 6         | 8.11%   |
| XFCE          | 3         | 4.05%   |
| X-Cinnamon    | 3         | 4.05%   |
| Unknown       | 2         | 2.7%    |
| GNOME Classic | 1         | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 44        | 59.46%  |
| X11     | 28        | 37.84%  |
| Tty     | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 47.3%   |
| GDM     | 28        | 37.84%  |
| LightDM | 6         | 8.11%   |
| SDDM    | 5         | 6.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 53        | 71.62%  |
| de_DE | 3         | 4.05%   |
| ru_RU | 2         | 2.7%    |
| es_ES | 2         | 2.7%    |
| en_ZA | 2         | 2.7%    |
| en_IE | 2         | 2.7%    |
| en_CA | 2         | 2.7%    |
| C     | 2         | 2.7%    |
| zh_TW | 1         | 1.35%   |
| pt_BR | 1         | 1.35%   |
| it_IT | 1         | 1.35%   |
| fr_FR | 1         | 1.35%   |
| en_GB | 1         | 1.35%   |
| ca_ES | 1         | 1.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 82.43%  |
| BIOS | 13        | 17.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 64        | 86.49%  |
| Ext4 | 9         | 12.16%  |
| Ext3 | 1         | 1.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 36        | 48.65%  |
| Unknown | 34        | 45.95%  |
| MBR     | 4         | 5.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 89.19%  |
| Yes       | 8         | 10.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 78.38%  |
| Yes       | 16        | 21.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 27        | 36.49%  |
| Hewlett-Packard  | 17        | 22.97%  |
| Dell             | 13        | 17.57%  |
| ASUSTek Computer | 7         | 9.46%   |
| Toshiba          | 2         | 2.7%    |
| Acer             | 2         | 2.7%    |
| Positivo         | 1         | 1.35%   |
| HUAWEI           | 1         | 1.35%   |
| Clevo            | 1         | 1.35%   |
| Beelink          | 1         | 1.35%   |
| BANGHO           | 1         | 1.35%   |
| Apple            | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP EliteBook 840 G5                      | 2         | 2.7%    |
| Toshiba TECRA W50-A                      | 1         | 1.35%   |
| Toshiba Satellite E45-B                  | 1         | 1.35%   |
| Positivo Mobile                          | 1         | 1.35%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900 | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 1.35%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 1.35%   |
| Lenovo ThinkPad W500 406132G             | 1         | 1.35%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 1.35%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 1.35%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 1.35%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 1.35%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 1.35%   |
| Lenovo ThinkPad T14 Gen 3 21AH00HXGE     | 1         | 1.35%   |
| Lenovo ThinkPad P15s Gen 1 20T4CTO1WW    | 1         | 1.35%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV     | 1         | 1.35%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 1.35%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK      | 1         | 1.35%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB     | 1         | 1.35%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 1.35%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.35%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.35%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 1.35%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.35%   |
| Lenovo IdeaPad S210 Touch 20257          | 1         | 1.35%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 1         | 1.35%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 1.35%   |
| Lenovo IdeaPad 3 15ITL6 82H8             | 1         | 1.35%   |
| Lenovo IdeaPad 1 14IGL7 82V6             | 1         | 1.35%   |
| Lenovo G450 2949                         | 1         | 1.35%   |
| HUAWEI KLVD-WXX9                         | 1         | 1.35%   |
| HP ZBook 15u G6                          | 1         | 1.35%   |
| HP ZBook 15u G5                          | 1         | 1.35%   |
| HP ZBook 15 G3                           | 1         | 1.35%   |
| HP ZBook 15 G2                           | 1         | 1.35%   |
| HP ProBook 645 G1                        | 1         | 1.35%   |
| HP ProBook 640 G3                        | 1         | 1.35%   |
| HP Pavilion g6                           | 1         | 1.35%   |
| HP Laptop 17-ca1xxx                      | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 16        | 21.62%  |
| Lenovo IdeaPad     | 8         | 10.81%  |
| HP EliteBook       | 6         | 8.11%   |
| Dell Latitude      | 5         | 6.76%   |
| HP ZBook           | 4         | 5.41%   |
| HP Laptop          | 4         | 5.41%   |
| Dell XPS           | 4         | 5.41%   |
| ASUS ASUS          | 3         | 4.05%   |
| Lenovo Legion      | 2         | 2.7%    |
| HP ProBook         | 2         | 2.7%    |
| Dell Inspiron      | 2         | 2.7%    |
| Acer Aspire        | 2         | 2.7%    |
| Toshiba TECRA      | 1         | 1.35%   |
| Toshiba Satellite  | 1         | 1.35%   |
| Positivo Mobile    | 1         | 1.35%   |
| Lenovo G450        | 1         | 1.35%   |
| HUAWEI KLVD-WXX9   | 1         | 1.35%   |
| HP Pavilion        | 1         | 1.35%   |
| Dell Vostro        | 1         | 1.35%   |
| Dell Precision     | 1         | 1.35%   |
| Clevo P170EM       | 1         | 1.35%   |
| Beelink BT3        | 1         | 1.35%   |
| BANGHO BES         | 1         | 1.35%   |
| ASUS VivoBook      | 1         | 1.35%   |
| ASUS UX430UNR      | 1         | 1.35%   |
| ASUS ROG           | 1         | 1.35%   |
| ASUS G752VM        | 1         | 1.35%   |
| Apple MacBookPro11 | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 10        | 13.51%  |
| 2020 | 10        | 13.51%  |
| 2021 | 8         | 10.81%  |
| 2019 | 8         | 10.81%  |
| 2018 | 8         | 10.81%  |
| 2014 | 5         | 6.76%   |
| 2017 | 4         | 5.41%   |
| 2015 | 4         | 5.41%   |
| 2012 | 4         | 5.41%   |
| 2013 | 3         | 4.05%   |
| 2011 | 3         | 4.05%   |
| 2016 | 2         | 2.7%    |
| 2010 | 2         | 2.7%    |
| 2009 | 2         | 2.7%    |
| 2023 | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 74        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 58        | 78.38%  |
| Enabled  | 16        | 21.62%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 24        | 32.43%  |
| 4.01-8.0    | 18        | 24.32%  |
| 32.01-64.0  | 15        | 20.27%  |
| 16.01-24.0  | 8         | 10.81%  |
| 3.01-4.0    | 5         | 6.76%   |
| 24.01-32.0  | 2         | 2.7%    |
| 64.01-256.0 | 2         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 30.77%  |
| 3.01-4.0   | 17        | 21.79%  |
| 2.01-3.0   | 17        | 21.79%  |
| 8.01-16.0  | 9         | 11.54%  |
| 1.01-2.0   | 7         | 8.97%   |
| 0.51-1.0   | 2         | 2.56%   |
| 24.01-32.0 | 1         | 1.28%   |
| 16.01-24.0 | 1         | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 79.73%  |
| 2      | 10        | 13.51%  |
| 3      | 4         | 5.41%   |
| 4      | 1         | 1.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 83.78%  |
| Yes       | 12        | 16.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 82.67%  |
| No        | 13        | 17.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 97.3%   |
| No        | 2         | 2.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 86.49%  |
| No        | 10        | 13.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 23        | 31.08%  |
| Germany      | 4         | 5.41%   |
| Spain        | 3         | 4.05%   |
| Russia       | 3         | 4.05%   |
| Poland       | 3         | 4.05%   |
| South Africa | 2         | 2.7%    |
| Netherlands  | 2         | 2.7%    |
| Italy        | 2         | 2.7%    |
| Ireland      | 2         | 2.7%    |
| Hungary      | 2         | 2.7%    |
| Czechia      | 2         | 2.7%    |
| Canada       | 2         | 2.7%    |
| Brazil       | 2         | 2.7%    |
| Belgium      | 2         | 2.7%    |
| Argentina    | 2         | 2.7%    |
| Uzbekistan   | 1         | 1.35%   |
| UK           | 1         | 1.35%   |
| UAE          | 1         | 1.35%   |
| Turkey       | 1         | 1.35%   |
| Taiwan       | 1         | 1.35%   |
| Sweden       | 1         | 1.35%   |
| Slovakia     | 1         | 1.35%   |
| Saudi Arabia | 1         | 1.35%   |
| Pakistan     | 1         | 1.35%   |
| Norway       | 1         | 1.35%   |
| Malaysia     | 1         | 1.35%   |
| Kenya        | 1         | 1.35%   |
| Kazakhstan   | 1         | 1.35%   |
| France       | 1         | 1.35%   |
| Croatia      | 1         | 1.35%   |
| China        | 1         | 1.35%   |
| Bulgaria     | 1         | 1.35%   |
| Austria      | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Philadelphia           | 2         | 2.7%    |
| Enschede               | 2         | 2.7%    |
| Budapest               | 2         | 2.7%    |
| Albuquerque            | 2         | 2.7%    |
| Žilina                | 1         | 1.35%   |
| Xi'an                  | 1         | 1.35%   |
| Woking                 | 1         | 1.35%   |
| Westerville            | 1         | 1.35%   |
| Vienna                 | 1         | 1.35%   |
| Troisdorf              | 1         | 1.35%   |
| Torrington             | 1         | 1.35%   |
| Taoyuan City           | 1         | 1.35%   |
| Syracuse               | 1         | 1.35%   |
| Spokane                | 1         | 1.35%   |
| Split                  | 1         | 1.35%   |
| Sofia                  | 1         | 1.35%   |
| Smolensk               | 1         | 1.35%   |
| Senigallia             | 1         | 1.35%   |
| Scarborough            | 1         | 1.35%   |
| San Miguel de Tucumán | 1         | 1.35%   |
| Rosario                | 1         | 1.35%   |
| Riyadh                 | 1         | 1.35%   |
| Rawalpindi             | 1         | 1.35%   |
| Qualicum Beach         | 1         | 1.35%   |
| Prague                 | 1         | 1.35%   |
| Ottignies              | 1         | 1.35%   |
| Oslo                   | 1         | 1.35%   |
| Örebro                | 1         | 1.35%   |
| Oakley                 | 1         | 1.35%   |
| Nyahururu              | 1         | 1.35%   |
| Nur-Sultan             | 1         | 1.35%   |
| Niceville              | 1         | 1.35%   |
| Mugla                  | 1         | 1.35%   |
| Mossel Bay             | 1         | 1.35%   |
| Moscow                 | 1         | 1.35%   |
| Montreal               | 1         | 1.35%   |
| Melun                  | 1         | 1.35%   |
| Madrid                 | 1         | 1.35%   |
| Lodz                   | 1         | 1.35%   |
| Lenexa                 | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 24        | 28     | 25.26%  |
| SanDisk                   | 9         | 11     | 9.47%   |
| WDC                       | 8         | 8      | 8.42%   |
| Micron Technology         | 5         | 5      | 5.26%   |
| Kingston                  | 5         | 5      | 5.26%   |
| Intel                     | 5         | 5      | 5.26%   |
| Toshiba                   | 4         | 5      | 4.21%   |
| Unknown                   | 3         | 3      | 3.16%   |
| SK hynix                  | 3         | 5      | 3.16%   |
| Seagate                   | 3         | 3      | 3.16%   |
| Lexar                     | 2         | 2      | 2.11%   |
| Dogfish                   | 2         | 2      | 2.11%   |
| Crucial                   | 2         | 2      | 2.11%   |
| A-DATA Technology         | 2         | 2      | 2.11%   |
| Union Memory (Shenzhen)   | 1         | 1      | 1.05%   |
| Union Memory              | 1         | 1      | 1.05%   |
| UMIS                      | 1         | 1      | 1.05%   |
| StoreJet                  | 1         | 1      | 1.05%   |
| PNY                       | 1         | 1      | 1.05%   |
| Phison                    | 1         | 2      | 1.05%   |
| Micron/Crucial Technology | 1         | 1      | 1.05%   |
| LITEONIT                  | 1         | 1      | 1.05%   |
| LITEON                    | 1         | 1      | 1.05%   |
| KIOXIA                    | 1         | 1      | 1.05%   |
| JMicron Technology        | 1         | 1      | 1.05%   |
| INDMEM                    | 1         | 1      | 1.05%   |
| HS-SSD-C100               | 1         | 1      | 1.05%   |
| Hitachi                   | 1         | 1      | 1.05%   |
| Fujitsu                   | 1         | 1      | 1.05%   |
| ASMT                      | 1         | 1      | 1.05%   |
| AGI                       | 1         | 1      | 1.05%   |
| ADATA Technology          | 1         | 1      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 4         | 3.96%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 3         | 2.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 2.97%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 1.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 2         | 1.98%   |
| Lexar 512GB SSD                                     | 2         | 1.98%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.99%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.99%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 0.99%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 0.99%   |
| WDC WD40 EFRX-68N32N0 4TB                           | 1         | 0.99%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.99%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.99%   |
| WDC WD Blue SA510 M.2 2280 1000GB SSD               | 1         | 0.99%   |
| Unknown SD/MMC/MS PRO 16GB                          | 1         | 0.99%   |
| Unknown S0J38Y  64GB                                | 1         | 0.99%   |
| Unknown MMC Card  64GB                              | 1         | 0.99%   |
| Union Memory UMIS RPJTJ128MEE1MWX 128GB             | 1         | 0.99%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1         | 0.99%   |
| UMIS RPFTJ128PDD2EWX 128GB                          | 1         | 0.99%   |
| Toshiba THNSNJ512GACU 512GB SSD                     | 1         | 0.99%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 0.99%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 0.99%   |
| Toshiba KXG6AZNV1T02 1TB                            | 1         | 0.99%   |
| Toshiba KXG6APNV2T04 2TB                            | 1         | 0.99%   |
| StoreJet Disk 2TB                                   | 1         | 0.99%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB           | 1         | 0.99%   |
| SK hynix SHPP41-2000GM 2TB                          | 1         | 0.99%   |
| SK hynix NVMe SSD Drive 512GB                       | 1         | 0.99%   |
| SK hynix BC511 NVMe 512GB                           | 1         | 0.99%   |
| Seagate ST9320325AS 320GB                           | 1         | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 0.99%   |
| Seagate One Touch HDD 5TB                           | 1         | 0.99%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 0.99%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1024GB        | 1         | 0.99%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 0.99%   |
| SanDisk SDSSDA120G 120GB                            | 1         | 0.99%   |
| SanDisk SD8SN8U512G1002 512GB SSD                   | 1         | 0.99%   |
| SanDisk SD5SG2256G1052E 256GB SSD                   | 1         | 0.99%   |
| SanDisk Extreme 55AE 1TB SSD                        | 1         | 0.99%   |

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
| Samsung Electronics | 8         | 9      | 24.24%  |
| SanDisk             | 4         | 5      | 12.12%  |
| WDC                 | 3         | 3      | 9.09%   |
| Kingston            | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Dogfish             | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| PNY                 | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| LITEONIT            | 1         | 1      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| Lexar               | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| INDMEM              | 1         | 1      | 3.03%   |
| ASMT                | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 44        | 53     | 50.57%  |
| SSD     | 28        | 35     | 32.18%  |
| HDD     | 10        | 12     | 11.49%  |
| Unknown | 3         | 3      | 3.45%   |
| MMC     | 2         | 2      | 2.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 53     | 51.16%  |
| SATA | 33        | 42     | 38.37%  |
| SAS  | 7         | 8      | 8.14%   |
| MMC  | 2         | 2      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 24     | 52.5%   |
| 0.51-1.0   | 13        | 16     | 32.5%   |
| 1.01-2.0   | 3         | 3      | 7.5%    |
| 3.01-4.0   | 2         | 3      | 5%      |
| 4.01-10.0  | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 23        | 31.08%  |
| 101-250        | 22        | 29.73%  |
| 501-1000       | 14        | 18.92%  |
| 1001-2000      | 5         | 6.76%   |
| 51-100         | 4         | 5.41%   |
| 2001-3000      | 3         | 4.05%   |
| More than 3000 | 2         | 2.7%    |
| 1-20           | 1         | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 31.58%  |
| 21-50          | 20        | 26.32%  |
| 101-250        | 13        | 17.11%  |
| 51-100         | 10        | 13.16%  |
| 251-500        | 4         | 5.26%   |
| 1001-2000      | 2         | 2.63%   |
| 501-1000       | 2         | 2.63%   |
| More than 3000 | 1         | 1.32%   |

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
| Works    | 40        | 54     | 50.63%  |
| Detected | 38        | 50     | 48.1%   |
| Malfunc  | 1         | 1      | 1.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 42        | 47.73%  |
| Samsung Electronics          | 16        | 18.18%  |
| AMD                          | 6         | 6.82%   |
| SanDisk                      | 5         | 5.68%   |
| Micron Technology            | 4         | 4.55%   |
| SK hynix                     | 3         | 3.41%   |
| Union Memory (Shenzhen)      | 2         | 2.27%   |
| Toshiba America Info Systems | 2         | 2.27%   |
| Kingston Technology Company  | 2         | 2.27%   |
| Shenzhen Longsys Electronics | 1         | 1.14%   |
| Realtek Semiconductor        | 1         | 1.14%   |
| Phison Electronics           | 1         | 1.14%   |
| Micron/Crucial Technology    | 1         | 1.14%   |
| KIOXIA                       | 1         | 1.14%   |
| ADATA Technology             | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 7.37%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 6.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 5.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 4.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 4.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 4.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 4.21%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 3.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 3.16%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 3.16%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 3.16%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.11%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 2.11%   |
| Intel SSD 660P Series                                                          | 2         | 2.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.11%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile     | 2         | 2.11%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                          | 1         | 1.05%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 1.05%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 1.05%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 1.05%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.05%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1         | 1.05%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.05%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 1.05%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.05%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.05%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.05%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.05%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.05%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.05%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 1.05%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 44        | 48.35%  |
| SATA | 35        | 38.46%  |
| RAID | 7         | 7.69%   |
| IDE  | 5         | 5.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 83.78%  |
| AMD    | 12        | 16.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 5.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 4.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 4.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.7%    |
| Intel Core i7-10610U CPU @ 1.80GHz          | 2         | 2.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 2.7%    |
| Intel 12th Gen Core i7-1260P                | 2         | 2.7%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 2         | 2.7%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.35%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.35%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.35%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.35%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 1.35%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.35%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz          | 1         | 1.35%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.35%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.35%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.35%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.35%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.35%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.35%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.35%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.35%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.35%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 1.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 26        | 35.14%  |
| Other                   | 17        | 22.97%  |
| Intel Core i5           | 13        | 17.57%  |
| AMD Ryzen 5             | 4         | 5.41%   |
| Intel Celeron           | 2         | 2.7%    |
| AMD Ryzen 7             | 2         | 2.7%    |
| AMD Ryzen 5 PRO         | 2         | 2.7%    |
| Intel Pentium Silver    | 1         | 1.35%   |
| Intel Pentium Dual-Core | 1         | 1.35%   |
| Intel Core i3           | 1         | 1.35%   |
| Intel Core 2 Duo        | 1         | 1.35%   |
| Intel Atom              | 1         | 1.35%   |
| AMD Ryzen 3             | 1         | 1.35%   |
| AMD A8                  | 1         | 1.35%   |
| AMD A10                 | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 35        | 47.3%   |
| 2      | 19        | 25.68%  |
| 6      | 8         | 10.81%  |
| 10     | 4         | 5.41%   |
| 8      | 4         | 5.41%   |
| 12     | 2         | 2.7%    |
| 14     | 1         | 1.35%   |
| 1      | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 84%     |
| 1      | 12        | 16%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 8         | 10.81%  |
| 0x306c3    | 7         | 9.46%   |
| 0x806ea    | 6         | 8.11%   |
| 0x806ec    | 5         | 6.76%   |
| 0xa0652    | 4         | 5.41%   |
| 0x306a9    | 4         | 5.41%   |
| 0x506e3    | 3         | 4.05%   |
| Unknown    | 3         | 4.05%   |
| 0x906a4    | 2         | 2.7%    |
| 0x906a3    | 2         | 2.7%    |
| 0x806e9    | 2         | 2.7%    |
| 0x306d4    | 2         | 2.7%    |
| 0x206a7    | 2         | 2.7%    |
| 0x0a50000d | 2         | 2.7%    |
| 0x0a50000c | 2         | 2.7%    |
| 0x08600104 | 2         | 2.7%    |
| 0x906ea    | 1         | 1.35%   |
| 0x806d1    | 1         | 1.35%   |
| 0x706e5    | 1         | 1.35%   |
| 0x706a8    | 1         | 1.35%   |
| 0x706a1    | 1         | 1.35%   |
| 0x406e3    | 1         | 1.35%   |
| 0x406c4    | 1         | 1.35%   |
| 0x40661    | 1         | 1.35%   |
| 0x40651    | 1         | 1.35%   |
| 0x20655    | 1         | 1.35%   |
| 0x1067a    | 1         | 1.35%   |
| 0x10676    | 1         | 1.35%   |
| 0x0a404101 | 1         | 1.35%   |
| 0x08a00006 | 1         | 1.35%   |
| 0x08108102 | 1         | 1.35%   |
| 0x06006705 | 1         | 1.35%   |
| 0x06001119 | 1         | 1.35%   |
| 0x06001116 | 1         | 1.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 18.92%  |
| Haswell          | 9         | 12.16%  |
| TigerLake        | 8         | 10.81%  |
| Alderlake Hybrid | 7         | 9.46%   |
| Zen 3            | 4         | 5.41%   |
| Skylake          | 4         | 5.41%   |
| IvyBridge        | 4         | 5.41%   |
| CometLake        | 4         | 5.41%   |
| Zen 2            | 2         | 2.7%    |
| SandyBridge      | 2         | 2.7%    |
| Piledriver       | 2         | 2.7%    |
| Penryn           | 2         | 2.7%    |
| IceLake          | 2         | 2.7%    |
| Goldmont plus    | 2         | 2.7%    |
| Broadwell        | 2         | 2.7%    |
| Unknown          | 2         | 2.7%    |
| Zen+             | 1         | 1.35%   |
| Westmere         | 1         | 1.35%   |
| Silvermont       | 1         | 1.35%   |
| Excavator        | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 57.43%  |
| Nvidia | 29        | 28.71%  |
| AMD    | 14        | 13.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 7.84%   |
| Intel UHD Graphics 620                                                    | 6         | 5.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 4.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 4         | 3.92%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.92%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 2.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 2.94%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 3         | 2.94%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 3         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 1.96%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 2         | 1.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 1.96%   |
| Nvidia GM108M [GeForce 940M]                                              | 2         | 1.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.96%   |
| Intel HD Graphics 620                                                     | 2         | 1.96%   |
| Intel HD Graphics 5500                                                    | 2         | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.96%   |
| AMD Barcelo                                                               | 2         | 1.96%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.98%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.98%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.98%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 0.98%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.98%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.98%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 0.98%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.98%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 0.98%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 0.98%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 0.98%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.98%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 0.98%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 0.98%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 0.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 0.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 45.95%  |
| Intel + Nvidia | 21        | 28.38%  |
| 1 x AMD        | 7         | 9.46%   |
| 1 x Nvidia     | 5         | 6.76%   |
| Intel + AMD    | 3         | 4.05%   |
| AMD + Nvidia   | 3         | 4.05%   |
| 2 x AMD        | 1         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 83.78%  |
| Proprietary | 11        | 14.86%  |
| Unknown     | 1         | 1.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 57.33%  |
| 3.01-4.0   | 10        | 13.33%  |
| 1.01-2.0   | 8         | 10.67%  |
| 0.01-0.5   | 7         | 9.33%   |
| 5.01-6.0   | 3         | 4%      |
| 7.01-8.0   | 2         | 2.67%   |
| 0.51-1.0   | 2         | 2.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 15.69%  |
| AU Optronics            | 16        | 15.69%  |
| BOE                     | 13        | 12.75%  |
| Chimei Innolux          | 9         | 8.82%   |
| Samsung Electronics     | 8         | 7.84%   |
| Goldstar                | 8         | 7.84%   |
| Dell                    | 8         | 7.84%   |
| Sharp                   | 4         | 3.92%   |
| Philips                 | 3         | 2.94%   |
| InfoVision              | 3         | 2.94%   |
| PANDA                   | 2         | 1.96%   |
| Lenovo                  | 2         | 1.96%   |
| AOC                     | 2         | 1.96%   |
| Panasonic               | 1         | 0.98%   |
| Hewlett-Packard         | 1         | 0.98%   |
| Gigabyte Technology     | 1         | 0.98%   |
| CSO                     | 1         | 0.98%   |
| Chi Mei Optoelectronics | 1         | 0.98%   |
| BenQ                    | 1         | 0.98%   |
| Apple                   | 1         | 0.98%   |
| Acer                    | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 1.89%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.94%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.94%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.94%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.94%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 0.94%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.94%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 0.94%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 0.94%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.94%   |
| Philips PHL 499P9 PHL092A 3840x1080 1193x336mm 48.8-inch              | 1         | 0.94%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 0.94%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 0.94%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.94%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 1         | 0.94%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 1         | 0.94%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 47.87%  |
| 1366x768 (WXGA)    | 12        | 12.77%  |
| 2560x1440 (QHD)    | 6         | 6.38%   |
| 1920x1200 (WUXGA)  | 5         | 5.32%   |
| 3840x2160 (4K)     | 4         | 4.26%   |
| 3440x1440          | 4         | 4.26%   |
| 3840x2400          | 3         | 3.19%   |
| 2560x1080          | 3         | 3.19%   |
| 1600x900 (HD+)     | 3         | 3.19%   |
| 3840x1080          | 2         | 2.13%   |
| 1680x1050 (WSXGA+) | 2         | 2.13%   |
| 2880x1800          | 1         | 1.06%   |
| 2240x1400          | 1         | 1.06%   |
| 2160x1440          | 1         | 1.06%   |
| 1360x768           | 1         | 1.06%   |
| Unknown            | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 32        | 31.07%  |
| 14     | 23        | 22.33%  |
| 27     | 8         | 7.77%   |
| 13     | 8         | 7.77%   |
| 17     | 7         | 6.8%    |
| 34     | 5         | 4.85%   |
| 24     | 4         | 3.88%   |
| 21     | 4         | 3.88%   |
| 31     | 2         | 1.94%   |
| 23     | 2         | 1.94%   |
| 49     | 1         | 0.97%   |
| 48     | 1         | 0.97%   |
| 40     | 1         | 0.97%   |
| 35     | 1         | 0.97%   |
| 22     | 1         | 0.97%   |
| 18     | 1         | 0.97%   |
| 16     | 1         | 0.97%   |
| 12     | 1         | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 60        | 58.82%  |
| 501-600     | 12        | 11.76%  |
| 401-500     | 7         | 6.86%   |
| 351-400     | 7         | 6.86%   |
| 701-800     | 5         | 4.9%    |
| 201-300     | 5         | 4.9%    |
| 801-900     | 2         | 1.96%   |
| 601-700     | 2         | 1.96%   |
| 1001-1500   | 2         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 65        | 75.58%  |
| 16/10 | 11        | 12.79%  |
| 21/9  | 6         | 6.98%   |
| 32/9  | 2         | 2.33%   |
| 3/2   | 2         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 30.39%  |
| 81-90          | 29        | 28.43%  |
| 201-250        | 9         | 8.82%   |
| 351-500        | 8         | 7.84%   |
| 301-350        | 8         | 7.84%   |
| 121-130        | 7         | 6.86%   |
| 501-1000       | 3         | 2.94%   |
| 71-80          | 2         | 1.96%   |
| 111-120        | 2         | 1.96%   |
| 61-70          | 1         | 0.98%   |
| 151-200        | 1         | 0.98%   |
| 141-150        | 1         | 0.98%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 45        | 44.55%  |
| 101-120       | 21        | 20.79%  |
| 51-100        | 19        | 18.81%  |
| 161-240       | 10        | 9.9%    |
| More than 240 | 6         | 5.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 45        | 60%     |
| 2     | 23        | 30.67%  |
| 3     | 4         | 5.33%   |
| 0     | 2         | 2.67%   |
| 4     | 1         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 45.3%   |
| Realtek Semiconductor | 35        | 29.91%  |
| Qualcomm Atheros      | 6         | 5.13%   |
| MediaTek              | 5         | 4.27%   |
| ASIX Electronics      | 5         | 4.27%   |
| Broadcom              | 4         | 3.42%   |
| Lenovo                | 3         | 2.56%   |
| Ralink                | 1         | 0.85%   |
| JMicron Technology    | 1         | 0.85%   |
| Dell                  | 1         | 0.85%   |
| D-Link                | 1         | 0.85%   |
| Broadcom Limited      | 1         | 0.85%   |
| ASUSTek Computer      | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 19        | 12.84%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 10        | 6.76%   |
| Intel Wireless 8265 / 8275                                         | 8         | 5.41%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 4.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 6         | 4.05%   |
| Intel Wireless 7260                                                | 5         | 3.38%   |
| ASIX AX88179 Gigabit Ethernet                                      | 5         | 3.38%   |
| Intel Ethernet Connection I217-LM                                  | 4         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                              | 4         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                     | 4         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.03%   |
| Intel Wireless 8260                                                | 3         | 2.03%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 2.03%   |
| Intel Ethernet Connection (4) I219-V                               | 3         | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 3         | 2.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 2         | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 2         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.35%   |
| Lenovo ThinkPad TBT 3 Dock                                         | 2         | 1.35%   |
| Intel Wireless 7265                                                | 2         | 1.35%   |
| Intel Ethernet Connection (6) I219-LM                              | 2         | 1.35%   |
| Intel Ethernet Connection (16) I219-V                              | 2         | 1.35%   |
| Intel Ethernet Connection (16) I219-LM                             | 2         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 2         | 1.35%   |
| Realtek USB 10/100/1G/2.5G LAN                                     | 1         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R] | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                              | 1         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                  | 1         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                          | 1         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.68%   |
| Lenovo USB-C to LAN                                                | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 68.92%  |
| Realtek Semiconductor | 7         | 9.46%   |
| Qualcomm Atheros      | 5         | 6.76%   |
| MediaTek              | 5         | 6.76%   |
| Broadcom              | 2         | 2.7%    |
| Ralink                | 1         | 1.35%   |
| Dell                  | 1         | 1.35%   |
| Broadcom Limited      | 1         | 1.35%   |
| ASUSTek Computer      | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                                                         | 8         | 10.81%  |
| Intel Wi-Fi 6 AX201                                                                                                | 6         | 8.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 6         | 8.11%   |
| Intel Wireless 7260                                                                                                | 5         | 6.76%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 4         | 5.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 4         | 5.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 4.05%   |
| Intel Wireless 8260                                                                                                | 3         | 4.05%   |
| Intel Wi-Fi 6 AX200                                                                                                | 3         | 4.05%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                        | 2         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 2         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 2.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                      | 2         | 2.7%    |
| Intel Wireless 7265                                                                                                | 2         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 2         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 2.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]                                                 | 1         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 1.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 1.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 1.35%   |
| Intel Wireless 3160                                                                                                | 1         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                             | 1         | 1.35%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 1.35%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 1.35%   |
| Intel Centrino Advanced-N 6235                                                                                     | 1         | 1.35%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 1.35%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter                                               | 1         | 1.35%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                                        | 1         | 1.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                                    | 1         | 1.35%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                                                     | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 31        | 43.66%  |
| Intel                 | 27        | 38.03%  |
| ASIX Electronics      | 5         | 7.04%   |
| Lenovo                | 3         | 4.23%   |
| Broadcom              | 2         | 2.82%   |
| Qualcomm Atheros      | 1         | 1.41%   |
| JMicron Technology    | 1         | 1.41%   |
| D-Link                | 1         | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 25.68%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 13.51%  |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 6.76%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 5.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 5.41%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.7%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 2.7%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.7%    |
| Intel Ethernet Connection (16) I219-V                             | 2         | 2.7%    |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 2.7%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.35%   |
| Lenovo USB-C to LAN                                               | 1         | 1.35%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.35%   |
| Intel Ethernet controller                                         | 1         | 1.35%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.35%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.35%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.35%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.35%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 1.35%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.35%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 54.14%  |
| Ethernet | 61        | 45.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 64.77%  |
| Ethernet | 31        | 35.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 49        | 66.22%  |
| 1     | 24        | 32.43%  |
| 3     | 1         | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 75.68%  |
| Yes  | 18        | 24.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 67.19%  |
| Realtek Semiconductor           | 6         | 9.38%   |
| Qualcomm Atheros Communications | 4         | 6.25%   |
| Foxconn / Hon Hai               | 3         | 4.69%   |
| Broadcom                        | 3         | 4.69%   |
| Ralink                          | 1         | 1.56%   |
| IMC Networks                    | 1         | 1.56%   |
| Hewlett-Packard                 | 1         | 1.56%   |
| Dell                            | 1         | 1.56%   |
| Apple                           | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 18        | 28.13%  |
| Intel AX201 Bluetooth                              | 13        | 20.31%  |
| Realtek Bluetooth Radio                            | 5         | 7.81%   |
| Intel Bluetooth Device                             | 4         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 4.69%   |
| Intel AX200 Bluetooth                              | 3         | 4.69%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 3.13%   |
| Foxconn / Hon Hai Wireless_Device                  | 2         | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 1.56%   |
| Ralink RT3290 Bluetooth                            | 1         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.56%   |
| Intel AX210 Bluetooth                              | 1         | 1.56%   |
| IMC Networks Wireless_Device                       | 1         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.56%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth        | 1         | 1.56%   |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 1.56%   |
| Broadcom HP Portable Bumble Bee                    | 1         | 1.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.56%   |
| Apple Bluetooth Host Controller                    | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 53.51%  |
| Nvidia                | 17        | 14.91%  |
| AMD                   | 12        | 10.53%  |
| Logitech              | 4         | 3.51%   |
| Lenovo                | 2         | 1.75%   |
| Hewlett-Packard       | 2         | 1.75%   |
| GN Netcom             | 2         | 1.75%   |
| Conexant Systems      | 2         | 1.75%   |
| C-Media Electronics   | 2         | 1.75%   |
| VIA Technologies      | 1         | 0.88%   |
| Texas Instruments     | 1         | 0.88%   |
| Tenx Technology       | 1         | 0.88%   |
| Saitek                | 1         | 0.88%   |
| Realtek Semiconductor | 1         | 0.88%   |
| Plantronics           | 1         | 0.88%   |
| JMTek                 | 1         | 0.88%   |
| Huawei Technologies   | 1         | 0.88%   |
| Creative Technology   | 1         | 0.88%   |
| ASUSTek Computer      | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 9         | 6.77%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 6.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 6.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 6.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 3.76%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 3.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.26%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.5%    |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.5%    |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.5%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.5%    |
| Hewlett-Packard USB Audio                                                  | 2         | 1.5%    |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.5%    |
| AMD FCH Azalia Controller                                                  | 2         | 1.5%    |
| VIA Technologies VX1                                                       | 1         | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.75%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.75%   |
| Saitek Cyborg F.R.E.Q.5 Gaming Headset                                     | 1         | 0.75%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.75%   |
| Plantronics Blackwire 3220 Series                                          | 1         | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.75%   |
| Nvidia Audio device                                                        | 1         | 0.75%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.75%   |
| Logitech Stereo H650e                                                      | 1         | 0.75%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 15        | 31.91%  |
| Samsung Electronics | 15        | 31.91%  |
| Micron Technology   | 4         | 8.51%   |
| Crucial             | 4         | 8.51%   |
| Kingston            | 2         | 4.26%   |
| Smart               | 1         | 2.13%   |
| Ramaxel Technology  | 1         | 2.13%   |
| Magnum Tech         | 1         | 2.13%   |
| Lexar Co Limited    | 1         | 2.13%   |
| Lexar               | 1         | 2.13%   |
| G.Skill             | 1         | 2.13%   |
| A-DATA Technology   | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 4.17%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 4.17%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.08%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                   | 1         | 2.08%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s             | 1         | 2.08%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                  | 1         | 2.08%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1         | 2.08%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16384MB SODIMM DDR4 3200MT/s     | 1         | 2.08%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 1         | 2.08%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.08%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 2.08%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 2.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 2.08%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 2.08%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 2.08%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 2.08%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                   | 1         | 2.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 1         | 2.08%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s    | 1         | 2.08%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.08%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 2.08%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 2.08%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s   | 1         | 2.08%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s   | 1         | 2.08%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB LPDDR5 5500MT/s                | 1         | 2.08%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s      | 1         | 2.08%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s        | 1         | 2.08%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 2.08%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s         | 1         | 2.08%   |
| Magnum Tech RAM MAGNUMTECH 8GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s          | 1         | 2.08%   |
| Lexar Co Limited RAM LD4AS008G-2666SC 8GB SODIMM DDR4 2667MT/s | 1         | 2.08%   |
| Kingston RAM 9905703-006.A00G 16GB SODIMM DDR4 2400MT/s        | 1         | 2.08%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 59.52%  |
| DDR3   | 10        | 23.81%  |
| DDR5   | 3         | 7.14%   |
| LPDDR5 | 2         | 4.76%   |
| LPDDR4 | 1         | 2.38%   |
| LPDDR3 | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 86.05%  |
| Row Of Chips | 5         | 11.63%  |
| Unknown      | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 51.11%  |
| 16384 | 11        | 24.44%  |
| 4096  | 8         | 17.78%  |
| 32768 | 3         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 32.56%  |
| 2667  | 9         | 20.93%  |
| 1600  | 8         | 18.6%   |
| 4800  | 3         | 6.98%   |
| 2400  | 3         | 6.98%   |
| 2133  | 2         | 4.65%   |
| 6400  | 1         | 2.33%   |
| 5500  | 1         | 2.33%   |
| 4266  | 1         | 2.33%   |
| 1066  | 1         | 2.33%   |

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
| Chicony Electronics                    | 16        | 24.24%  |
| IMC Networks                           | 12        | 18.18%  |
| Realtek Semiconductor                  | 6         | 9.09%   |
| Microdia                               | 5         | 7.58%   |
| Bison Electronics                      | 4         | 6.06%   |
| Syntek                                 | 3         | 4.55%   |
| Sunplus Innovation Technology          | 3         | 4.55%   |
| Luxvisions Innotech Limited            | 3         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.55%   |
| Quanta                                 | 2         | 3.03%   |
| Logitech                               | 2         | 3.03%   |
| Suyin                                  | 1         | 1.52%   |
| Sonix Technology                       | 1         | 1.52%   |
| Silicon Motion                         | 1         | 1.52%   |
| Lite-On Technology                     | 1         | 1.52%   |
| Lenovo                                 | 1         | 1.52%   |
| Intel                                  | 1         | 1.52%   |
| Apple                                  | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 8         | 11.94%  |
| IMC Networks Integrated Camera                                             | 5         | 7.46%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 5.97%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 4.48%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 4.48%   |
| Chicony HP HD Camera                                                       | 3         | 4.48%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 2.99%   |
| Chicony HD WebCam                                                          | 2         | 2.99%   |
| Bison Integrated RGB Camera                                                | 2         | 2.99%   |
| Syntek Integrated Camera                                                   | 1         | 1.49%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 1.49%   |
| Sunplus MTD Camera                                                         | 1         | 1.49%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.49%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.49%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 1.49%   |
| Silicon Motion Lenovo EasyCamera                                           | 1         | 1.49%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 1.49%   |
| Realtek Integrated Webcam_HD                                               | 1         | 1.49%   |
| Realtek EasyCamera                                                         | 1         | 1.49%   |
| Quanta HP Webcam                                                           | 1         | 1.49%   |
| Quanta HP 5MP Camera                                                       | 1         | 1.49%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.49%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 1         | 1.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.49%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 1.49%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.49%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 1.49%   |
| Lite-On HP HD Webcam                                                       | 1         | 1.49%   |
| Lenovo UVC Camera                                                          | 1         | 1.49%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 1.49%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 1.49%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.49%   |
| IMC Networks HP TrueVision HD Camera                                       | 1         | 1.49%   |
| IMC Networks HD Camera                                                     | 1         | 1.49%   |
| Chicony USB2.0 FHD UVC WebCam                                              | 1         | 1.49%   |
| Chicony thinkpad t430s camera                                              | 1         | 1.49%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.49%   |
| Chicony HP HD Webcam                                                       | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 33.33%  |
| Synaptics                  | 8         | 33.33%  |
| Shenzhen Goodix Technology | 4         | 16.67%  |
| Upek                       | 1         | 4.17%   |
| LighTuning Technology      | 1         | 4.17%   |
| Elan Microelectronics      | 1         | 4.17%   |
| AuthenTec                  | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 8.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 8.33%   |
| Synaptics UWP WBDI Device                                                  | 2         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 8.33%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 4.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4.17%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 4.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.17%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 4.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.17%   |
| AuthenTec AES2810                                                          | 1         | 4.17%   |

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
| 0     | 34        | 45.95%  |
| 1     | 32        | 43.24%  |
| 2     | 7         | 9.46%   |
| 3     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 24        | 48.98%  |
| Graphics card         | 7         | 14.29%  |
| Net/wireless          | 4         | 8.16%   |
| Net/ethernet          | 3         | 6.12%   |
| Multimedia controller | 3         | 6.12%   |
| Chipcard              | 3         | 6.12%   |
| Unassigned class      | 1         | 2.04%   |
| Sound                 | 1         | 2.04%   |
| Firewire controller   | 1         | 2.04%   |
| Card reader           | 1         | 2.04%   |
| Bluetooth             | 1         | 2.04%   |

