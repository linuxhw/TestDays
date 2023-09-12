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

Total: 84

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 9.1 | 21        | 31.34%  |
| Rocky Linux 8.5 | 11        | 16.42%  |
| Rocky Linux 9.2 | 9         | 13.43%  |
| Rocky Linux 9.0 | 9         | 13.43%  |
| Rocky Linux 8.4 | 8         | 11.94%  |
| Rocky Linux 8.8 | 4         | 5.97%   |
| Rocky Linux 8.7 | 3         | 4.48%   |
| Rocky Linux 8.6 | 1         | 1.49%   |
| Rocky Linux 8.3 | 1         | 1.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 67        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 13.04%  |
| 5.14.0-284.25.1.el9_2.x86_64     | 5         | 7.25%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 5.8%    |
| 5.14.0-162.23.1.el9_1.x86_64     | 4         | 5.8%    |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 5.8%    |
| 5.14.0-284.18.1.el9_2.x86_64     | 3         | 4.35%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 4.35%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 2.9%    |
| 5.14.0-162.6.1.el9_1.x86_64      | 2         | 2.9%    |
| 5.14.0-162.18.1.el9_1.x86_64     | 2         | 2.9%    |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 2.9%    |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 2.9%    |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 2.9%    |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 2.9%    |
| 4.18.0-305.el8.x86_64            | 2         | 2.9%    |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 2.9%    |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 2.9%    |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 2.9%    |
| 6.4.12-1.el8.elrepo.x86_64       | 1         | 1.45%   |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 1.45%   |
| 6.2.10-1.el8.elrepo.x86_64       | 1         | 1.45%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.45%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 1.45%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 1         | 1.45%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1         | 1.45%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.45%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 1         | 1.45%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 1.45%   |
| 5.10.89-1.el8.x86_64             | 1         | 1.45%   |
| 4.18.0-477.21.1.el8_8.x86_64     | 1         | 1.45%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.45%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1         | 1.45%   |
| 4.18.0-240.22.1.el8.x86_64       | 1         | 1.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 38        | 56.72%  |
| 4.18.0  | 23        | 34.33%  |
| 6.4.12  | 1         | 1.49%   |
| 6.2.12  | 1         | 1.49%   |
| 6.2.10  | 1         | 1.49%   |
| 5.4.157 | 1         | 1.49%   |
| 5.16.15 | 1         | 1.49%   |
| 5.10.89 | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 38        | 56.72%  |
| 4.18    | 23        | 34.33%  |
| 6.2     | 2         | 2.99%   |
| 6.4     | 1         | 1.49%   |
| 5.4     | 1         | 1.49%   |
| 5.16    | 1         | 1.49%   |
| 5.10    | 1         | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 67        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 46        | 68.66%  |
| MATE          | 6         | 8.96%   |
| KDE5          | 6         | 8.96%   |
| XFCE          | 3         | 4.48%   |
| X-Cinnamon    | 3         | 4.48%   |
| Unknown       | 2         | 2.99%   |
| GNOME Classic | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 38        | 56.72%  |
| X11     | 27        | 40.3%   |
| Tty     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 47.76%  |
| GDM     | 24        | 35.82%  |
| LightDM | 6         | 8.96%   |
| SDDM    | 5         | 7.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 50        | 74.63%  |
| de_DE | 3         | 4.48%   |
| ru_RU | 2         | 2.99%   |
| en_ZA | 2         | 2.99%   |
| en_IE | 2         | 2.99%   |
| en_CA | 2         | 2.99%   |
| C     | 2         | 2.99%   |
| zh_TW | 1         | 1.49%   |
| pt_BR | 1         | 1.49%   |
| it_IT | 1         | 1.49%   |
| fr_FR | 1         | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 83.58%  |
| BIOS | 11        | 16.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 58        | 86.57%  |
| Ext4 | 8         | 11.94%  |
| Ext3 | 1         | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 33        | 49.25%  |
| Unknown | 31        | 46.27%  |
| MBR     | 3         | 4.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 88.06%  |
| Yes       | 8         | 11.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 77.61%  |
| Yes       | 15        | 22.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 25        | 37.31%  |
| Hewlett-Packard  | 14        | 20.9%   |
| Dell             | 12        | 17.91%  |
| ASUSTek Computer | 7         | 10.45%  |
| Toshiba          | 2         | 2.99%   |
| Acer             | 2         | 2.99%   |
| Positivo         | 1         | 1.49%   |
| HUAWEI           | 1         | 1.49%   |
| Beelink          | 1         | 1.49%   |
| BANGHO           | 1         | 1.49%   |
| Apple            | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 1.49%   |
| Toshiba Satellite E45-B                  | 1         | 1.49%   |
| Positivo Mobile                          | 1         | 1.49%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900 | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 1.49%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 1.49%   |
| Lenovo ThinkPad W500 406132G             | 1         | 1.49%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 1.49%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 1.49%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 1.49%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 1.49%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 1.49%   |
| Lenovo ThinkPad T14 Gen 3 21AH00HXGE     | 1         | 1.49%   |
| Lenovo ThinkPad P15s Gen 1 20T4CTO1WW    | 1         | 1.49%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV     | 1         | 1.49%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 1.49%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK      | 1         | 1.49%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB     | 1         | 1.49%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 1.49%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.49%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.49%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 1.49%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.49%   |
| Lenovo IdeaPad S210 Touch 20257          | 1         | 1.49%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 1         | 1.49%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 1.49%   |
| Lenovo IdeaPad 3 15ITL6 82H8             | 1         | 1.49%   |
| HUAWEI KLVD-WXX9                         | 1         | 1.49%   |
| HP ZBook 15u G6                          | 1         | 1.49%   |
| HP ZBook 15u G5                          | 1         | 1.49%   |
| HP ZBook 15 G3                           | 1         | 1.49%   |
| HP ZBook 15 G2                           | 1         | 1.49%   |
| HP ProBook 645 G1                        | 1         | 1.49%   |
| HP ProBook 640 G3                        | 1         | 1.49%   |
| HP Pavilion g6                           | 1         | 1.49%   |
| HP Laptop 17-ca1xxx                      | 1         | 1.49%   |
| HP Laptop 15-fc0xxx                      | 1         | 1.49%   |
| HP Laptop 15-dy2xxx                      | 1         | 1.49%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 16        | 23.88%  |
| Lenovo IdeaPad     | 7         | 10.45%  |
| HP ZBook           | 4         | 5.97%   |
| HP EliteBook       | 4         | 5.97%   |
| Dell XPS           | 4         | 5.97%   |
| Dell Latitude      | 4         | 5.97%   |
| HP Laptop          | 3         | 4.48%   |
| ASUS ASUS          | 3         | 4.48%   |
| Lenovo Legion      | 2         | 2.99%   |
| HP ProBook         | 2         | 2.99%   |
| Dell Inspiron      | 2         | 2.99%   |
| Acer Aspire        | 2         | 2.99%   |
| Toshiba TECRA      | 1         | 1.49%   |
| Toshiba Satellite  | 1         | 1.49%   |
| Positivo Mobile    | 1         | 1.49%   |
| HUAWEI KLVD-WXX9   | 1         | 1.49%   |
| HP Pavilion        | 1         | 1.49%   |
| Dell Vostro        | 1         | 1.49%   |
| Dell Precision     | 1         | 1.49%   |
| Beelink BT3        | 1         | 1.49%   |
| BANGHO BES         | 1         | 1.49%   |
| ASUS VivoBook      | 1         | 1.49%   |
| ASUS UX430UNR      | 1         | 1.49%   |
| ASUS ROG           | 1         | 1.49%   |
| ASUS G752VM        | 1         | 1.49%   |
| Apple MacBookPro11 | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 10        | 14.93%  |
| 2022 | 9         | 13.43%  |
| 2021 | 8         | 11.94%  |
| 2019 | 7         | 10.45%  |
| 2018 | 6         | 8.96%   |
| 2014 | 5         | 7.46%   |
| 2017 | 4         | 5.97%   |
| 2015 | 4         | 5.97%   |
| 2013 | 3         | 4.48%   |
| 2012 | 3         | 4.48%   |
| 2011 | 3         | 4.48%   |
| 2016 | 2         | 2.99%   |
| 2010 | 2         | 2.99%   |
| 2009 | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 54        | 80.6%   |
| Enabled  | 13        | 19.4%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 22        | 32.84%  |
| 4.01-8.0    | 17        | 25.37%  |
| 32.01-64.0  | 14        | 20.9%   |
| 16.01-24.0  | 8         | 11.94%  |
| 3.01-4.0    | 3         | 4.48%   |
| 24.01-32.0  | 2         | 2.99%   |
| 64.01-256.0 | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 34.29%  |
| 2.01-3.0   | 15        | 21.43%  |
| 3.01-4.0   | 14        | 20%     |
| 1.01-2.0   | 7         | 10%     |
| 8.01-16.0  | 6         | 8.57%   |
| 0.51-1.0   | 2         | 2.86%   |
| 24.01-32.0 | 1         | 1.43%   |
| 16.01-24.0 | 1         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 77.61%  |
| 2      | 10        | 14.93%  |
| 3      | 4         | 5.97%   |
| 4      | 1         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 85.07%  |
| Yes       | 10        | 14.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 82.35%  |
| No        | 12        | 17.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 98.51%  |
| No        | 1         | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 88.06%  |
| No        | 8         | 11.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 21        | 31.34%  |
| Germany      | 4         | 5.97%   |
| Russia       | 3         | 4.48%   |
| Poland       | 3         | 4.48%   |
| South Africa | 2         | 2.99%   |
| Netherlands  | 2         | 2.99%   |
| Italy        | 2         | 2.99%   |
| Ireland      | 2         | 2.99%   |
| Hungary      | 2         | 2.99%   |
| Czechia      | 2         | 2.99%   |
| Canada       | 2         | 2.99%   |
| Brazil       | 2         | 2.99%   |
| Belgium      | 2         | 2.99%   |
| Uzbekistan   | 1         | 1.49%   |
| UAE          | 1         | 1.49%   |
| Turkey       | 1         | 1.49%   |
| Taiwan       | 1         | 1.49%   |
| Sweden       | 1         | 1.49%   |
| Spain        | 1         | 1.49%   |
| Slovakia     | 1         | 1.49%   |
| Saudi Arabia | 1         | 1.49%   |
| Pakistan     | 1         | 1.49%   |
| Norway       | 1         | 1.49%   |
| Malaysia     | 1         | 1.49%   |
| Kazakhstan   | 1         | 1.49%   |
| France       | 1         | 1.49%   |
| Croatia      | 1         | 1.49%   |
| China        | 1         | 1.49%   |
| Bulgaria     | 1         | 1.49%   |
| Austria      | 1         | 1.49%   |
| Argentina    | 1         | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Philadelphia           | 2         | 2.99%   |
| Enschede               | 2         | 2.99%   |
| Budapest               | 2         | 2.99%   |
| Žilina                | 1         | 1.49%   |
| Xi'an                  | 1         | 1.49%   |
| Westerville            | 1         | 1.49%   |
| Vienna                 | 1         | 1.49%   |
| Troisdorf              | 1         | 1.49%   |
| Torrington             | 1         | 1.49%   |
| Taoyuan City           | 1         | 1.49%   |
| Syracuse               | 1         | 1.49%   |
| Spokane                | 1         | 1.49%   |
| Split                  | 1         | 1.49%   |
| Sofia                  | 1         | 1.49%   |
| Smolensk               | 1         | 1.49%   |
| Senigallia             | 1         | 1.49%   |
| Scarborough            | 1         | 1.49%   |
| San Miguel de Tucumán | 1         | 1.49%   |
| Riyadh                 | 1         | 1.49%   |
| Rawalpindi             | 1         | 1.49%   |
| Qualicum Beach         | 1         | 1.49%   |
| Prague                 | 1         | 1.49%   |
| Ottignies              | 1         | 1.49%   |
| Oslo                   | 1         | 1.49%   |
| Örebro                | 1         | 1.49%   |
| Oakley                 | 1         | 1.49%   |
| Nur-Sultan             | 1         | 1.49%   |
| Mugla                  | 1         | 1.49%   |
| Mossel Bay             | 1         | 1.49%   |
| Moscow                 | 1         | 1.49%   |
| Montreal               | 1         | 1.49%   |
| Melun                  | 1         | 1.49%   |
| Madrid                 | 1         | 1.49%   |
| Lodz                   | 1         | 1.49%   |
| Lenexa                 | 1         | 1.49%   |
| Kutno                  | 1         | 1.49%   |
| Krakow                 | 1         | 1.49%   |
| Kansas City            | 1         | 1.49%   |
| Johor Bahru            | 1         | 1.49%   |
| Jaú                   | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 23        | 26     | 26.14%  |
| Sandisk                   | 9         | 11     | 10.23%  |
| WDC                       | 8         | 8      | 9.09%   |
| Kingston                  | 5         | 5      | 5.68%   |
| Intel                     | 5         | 5      | 5.68%   |
| Toshiba                   | 4         | 5      | 4.55%   |
| Unknown                   | 3         | 3      | 3.41%   |
| SK hynix                  | 3         | 5      | 3.41%   |
| Seagate                   | 3         | 3      | 3.41%   |
| Micron Technology         | 3         | 3      | 3.41%   |
| Lexar                     | 2         | 2      | 2.27%   |
| Dogfish                   | 2         | 2      | 2.27%   |
| A-DATA Technology         | 2         | 2      | 2.27%   |
| Union Memory (Shenzhen)   | 1         | 1      | 1.14%   |
| UMIS                      | 1         | 1      | 1.14%   |
| StoreJet                  | 1         | 1      | 1.14%   |
| Phison                    | 1         | 2      | 1.14%   |
| Micron/Crucial Technology | 1         | 1      | 1.14%   |
| LITEONIT                  | 1         | 1      | 1.14%   |
| LITEON                    | 1         | 1      | 1.14%   |
| JMicron Technology        | 1         | 1      | 1.14%   |
| INDMEM                    | 1         | 1      | 1.14%   |
| HS-SSD-C100               | 1         | 1      | 1.14%   |
| Hitachi                   | 1         | 1      | 1.14%   |
| Fujitsu                   | 1         | 1      | 1.14%   |
| Crucial                   | 1         | 1      | 1.14%   |
| ASMT                      | 1         | 1      | 1.14%   |
| AGI                       | 1         | 1      | 1.14%   |
| ADATA Technology          | 1         | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 3         | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 3         | 3.23%   |
| Samsung SSD 870 EVO 1TB                               | 2         | 2.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 2         | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 2         | 2.15%   |
| Lexar 512GB SSD                                       | 2         | 2.15%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                      | 1         | 1.08%   |
| WDC WDBNCE0010PNC 1TB SSD                             | 1         | 1.08%   |
| WDC WD5000LPCX-24C6HT0 500GB                          | 1         | 1.08%   |
| WDC WD5000BPVT-00A1YT0 500GB                          | 1         | 1.08%   |
| WDC WD40 EFRX-68N32N0 4TB                             | 1         | 1.08%   |
| WDC WD10SPCX-24HWST1 1TB                              | 1         | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB                              | 1         | 1.08%   |
| WDC WD Blue SA510 M.2 2280 1000GB                     | 1         | 1.08%   |
| Unknown SD/MMC/MS PRO 1GB                             | 1         | 1.08%   |
| Unknown S0J38Y  64GB                                  | 1         | 1.08%   |
| Unknown MMC Card  64GB                                | 1         | 1.08%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB          | 1         | 1.08%   |
| UMIS RPFTJ128PDD2EWX 128GB                            | 1         | 1.08%   |
| Toshiba THNSNJ512GACU 512GB SSD                       | 1         | 1.08%   |
| Toshiba THNSNJ128G8NU 128GB SSD                       | 1         | 1.08%   |
| Toshiba NVMe SSD Drive 512GB                          | 1         | 1.08%   |
| Toshiba KXG6AZNV1T02 1TB                              | 1         | 1.08%   |
| Toshiba KXG6APNV2T04 2TB                              | 1         | 1.08%   |
| StoreJet Disk 2TB                                     | 1         | 1.08%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB             | 1         | 1.08%   |
| SK hynix SHPP41-2000GM 2TB                            | 1         | 1.08%   |
| SK hynix NVMe SSD Drive 512GB                         | 1         | 1.08%   |
| SK hynix BC511 NVMe 512GB                             | 1         | 1.08%   |
| Seagate ST9320325AS 320GB                             | 1         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 1.08%   |
| Seagate One Touch HDD 5TB                             | 1         | 1.08%   |
| Sandisk WD_BLACK SN770 1TB                            | 1         | 1.08%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1TB             | 1         | 1.08%   |
| SanDisk SSD PLUS 1000GB                               | 1         | 1.08%   |
| SanDisk SDSSDA120G 120GB                              | 1         | 1.08%   |
| SanDisk SD8SN8U512G1002 512GB SSD                     | 1         | 1.08%   |
| SanDisk SD5SG2256G1052E 256GB SSD                     | 1         | 1.08%   |
| SanDisk Extreme 55AE 1TB SSD                          | 1         | 1.08%   |
| Samsung SSD 970 EVO 500GB                             | 1         | 1.08%   |

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
| Samsung Electronics | 8         | 9      | 26.67%  |
| SanDisk             | 4         | 5      | 13.33%  |
| WDC                 | 3         | 3      | 10%     |
| Kingston            | 3         | 3      | 10%     |
| Toshiba             | 2         | 2      | 6.67%   |
| Dogfish             | 2         | 2      | 6.67%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| Lexar               | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| INDMEM              | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| ASMT                | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 40        | 48     | 50%     |
| SSD     | 25        | 32     | 31.25%  |
| HDD     | 10        | 12     | 12.5%   |
| Unknown | 3         | 3      | 3.75%   |
| MMC     | 2         | 2      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 40        | 48     | 50.63%  |
| SATA | 30        | 39     | 37.97%  |
| SAS  | 7         | 8      | 8.86%   |
| MMC  | 2         | 2      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 22     | 51.35%  |
| 0.51-1.0   | 12        | 15     | 32.43%  |
| 1.01-2.0   | 3         | 3      | 8.11%   |
| 3.01-4.0   | 2         | 3      | 5.41%   |
| 4.01-10.0  | 1         | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 29.85%  |
| 101-250        | 19        | 28.36%  |
| 501-1000       | 13        | 19.4%   |
| 1001-2000      | 5         | 7.46%   |
| 51-100         | 4         | 5.97%   |
| 2001-3000      | 3         | 4.48%   |
| More than 3000 | 2         | 2.99%   |
| 1-20           | 1         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 32.35%  |
| 21-50          | 17        | 25%     |
| 101-250        | 11        | 16.18%  |
| 51-100         | 9         | 13.24%  |
| 251-500        | 4         | 5.88%   |
| 1001-2000      | 2         | 2.94%   |
| 501-1000       | 2         | 2.94%   |
| More than 3000 | 1         | 1.47%   |

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
| Works    | 37        | 51     | 52.11%  |
| Detected | 33        | 45     | 46.48%  |
| Malfunc  | 1         | 1      | 1.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 37        | 46.84%  |
| Samsung Electronics          | 15        | 18.99%  |
| AMD                          | 6         | 7.59%   |
| SanDisk                      | 5         | 6.33%   |
| SK hynix                     | 3         | 3.8%    |
| Micron Technology            | 3         | 3.8%    |
| Toshiba America Info Systems | 2         | 2.53%   |
| Kingston Technology Company  | 2         | 2.53%   |
| Union Memory (Shenzhen)      | 1         | 1.27%   |
| Shenzhen Longsys Electronics | 1         | 1.27%   |
| Realtek Semiconductor        | 1         | 1.27%   |
| Phison Electronics           | 1         | 1.27%   |
| Micron/Crucial Technology    | 1         | 1.27%   |
| ADATA Technology             | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 6.98%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 6.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 5.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 4.65%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 4.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 4.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 3.49%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.49%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 3.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.33%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 2.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.33%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 2.33%   |
| Intel SSD 660P Series                                                          | 2         | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.33%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile     | 2         | 2.33%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 1         | 1.16%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 1.16%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 1.16%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.16%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1         | 1.16%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.16%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.16%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.16%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.16%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.16%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.16%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.16%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.16%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]  | 1         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 40        | 48.78%  |
| SATA | 32        | 39.02%  |
| RAID | 5         | 6.1%    |
| IDE  | 5         | 6.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 83.58%  |
| AMD    | 11        | 16.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 4         | 5.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 3         | 4.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 3         | 4.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.99%   |
| Intel Core i7-10610U CPU @ 1.80GHz       | 2         | 2.99%   |
| Intel 12th Gen Core i7-1260P             | 2         | 2.99%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz  | 2         | 2.99%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz        | 1         | 1.49%   |
| Intel Core i7-7600U CPU @ 2.80GHz        | 1         | 1.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 1.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 1         | 1.49%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz       | 1         | 1.49%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz       | 1         | 1.49%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz       | 1         | 1.49%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 1         | 1.49%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz       | 1         | 1.49%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 1         | 1.49%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 1         | 1.49%   |
| Intel Core i7-10875H CPU @ 2.30GHz       | 1         | 1.49%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 1.49%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 1.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 1.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 1.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.49%   |
| Intel Core i5-4200M CPU @ 2.50GHz        | 1         | 1.49%   |
| Intel Core i5-3427U CPU @ 1.80GHz        | 1         | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.49%   |
| Intel Core i3 CPU M 380 @ 2.53GHz        | 1         | 1.49%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz     | 1         | 1.49%   |
| Intel Celeron CPU 1037U @ 1.80GHz        | 1         | 1.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz        | 1         | 1.49%   |
| Intel 12th Gen Core i7-12700H            | 1         | 1.49%   |
| Intel 12th Gen Core i7-1265U             | 1         | 1.49%   |
| Intel 12th Gen Core i7-12650H            | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 24        | 35.82%  |
| Other                | 17        | 25.37%  |
| Intel Core i5        | 11        | 16.42%  |
| AMD Ryzen 5          | 4         | 5.97%   |
| AMD Ryzen 7          | 2         | 2.99%   |
| Intel Pentium Silver | 1         | 1.49%   |
| Intel Core i3        | 1         | 1.49%   |
| Intel Core 2 Duo     | 1         | 1.49%   |
| Intel Celeron        | 1         | 1.49%   |
| Intel Atom           | 1         | 1.49%   |
| AMD Ryzen 5 PRO      | 1         | 1.49%   |
| AMD Ryzen 3          | 1         | 1.49%   |
| AMD A8               | 1         | 1.49%   |
| AMD A10              | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 31        | 46.27%  |
| 2      | 17        | 25.37%  |
| 6      | 7         | 10.45%  |
| 10     | 4         | 5.97%   |
| 8      | 4         | 5.97%   |
| 12     | 2         | 2.99%   |
| 14     | 1         | 1.49%   |
| 1      | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 58        | 86.57%  |
| 1      | 9         | 13.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 67        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 8         | 11.94%  |
| 0x306c3    | 7         | 10.45%  |
| 0x806ec    | 5         | 7.46%   |
| 0xa0652    | 4         | 5.97%   |
| 0x806ea    | 4         | 5.97%   |
| 0x506e3    | 3         | 4.48%   |
| 0x306a9    | 3         | 4.48%   |
| Unknown    | 3         | 4.48%   |
| 0x906a4    | 2         | 2.99%   |
| 0x906a3    | 2         | 2.99%   |
| 0x806e9    | 2         | 2.99%   |
| 0x306d4    | 2         | 2.99%   |
| 0x206a7    | 2         | 2.99%   |
| 0x0a50000c | 2         | 2.99%   |
| 0x08600104 | 2         | 2.99%   |
| 0x906ea    | 1         | 1.49%   |
| 0x806d1    | 1         | 1.49%   |
| 0x706a1    | 1         | 1.49%   |
| 0x406e3    | 1         | 1.49%   |
| 0x406c4    | 1         | 1.49%   |
| 0x40661    | 1         | 1.49%   |
| 0x40651    | 1         | 1.49%   |
| 0x20655    | 1         | 1.49%   |
| 0x10676    | 1         | 1.49%   |
| 0x0a50000d | 1         | 1.49%   |
| 0x0a404101 | 1         | 1.49%   |
| 0x08a00006 | 1         | 1.49%   |
| 0x08108102 | 1         | 1.49%   |
| 0x06006705 | 1         | 1.49%   |
| 0x06001119 | 1         | 1.49%   |
| 0x06001116 | 1         | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 17.91%  |
| Haswell          | 9         | 13.43%  |
| TigerLake        | 8         | 11.94%  |
| Alderlake Hybrid | 7         | 10.45%  |
| Skylake          | 4         | 5.97%   |
| CometLake        | 4         | 5.97%   |
| Zen 3            | 3         | 4.48%   |
| IvyBridge        | 3         | 4.48%   |
| Zen 2            | 2         | 2.99%   |
| SandyBridge      | 2         | 2.99%   |
| Piledriver       | 2         | 2.99%   |
| Broadwell        | 2         | 2.99%   |
| Unknown          | 2         | 2.99%   |
| Zen+             | 1         | 1.49%   |
| Westmere         | 1         | 1.49%   |
| Silvermont       | 1         | 1.49%   |
| Penryn           | 1         | 1.49%   |
| Icelake          | 1         | 1.49%   |
| Goldmont plus    | 1         | 1.49%   |
| Excavator        | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 55.91%  |
| Nvidia | 29        | 31.18%  |
| AMD    | 12        | 12.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 8.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 5.32%   |
| Intel UHD Graphics 620                                                    | 4         | 4.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 4         | 4.26%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 3.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 3.19%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 3         | 3.19%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 3         | 3.19%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 3.19%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 2.13%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 2         | 2.13%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 2.13%   |
| Nvidia GM108M [GeForce 940M]                                              | 2         | 2.13%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.13%   |
| Intel HD Graphics 620                                                     | 2         | 2.13%   |
| Intel HD Graphics 5500                                                    | 2         | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.13%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.06%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.06%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 1.06%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 1.06%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 1.06%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.06%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.06%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 1.06%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 1.06%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.06%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 1.06%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.06%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.06%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 1.06%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.06%   |
| Intel HD Graphics 530                                                     | 1         | 1.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 43.28%  |
| Intel + Nvidia | 21        | 31.34%  |
| 1 x AMD        | 6         | 8.96%   |
| 1 x Nvidia     | 5         | 7.46%   |
| AMD + Nvidia   | 3         | 4.48%   |
| Intel + AMD    | 2         | 2.99%   |
| 2 x AMD        | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 55        | 82.09%  |
| Proprietary | 11        | 16.42%  |
| Unknown     | 1         | 1.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 55.88%  |
| 3.01-4.0   | 10        | 14.71%  |
| 1.01-2.0   | 7         | 10.29%  |
| 0.01-0.5   | 6         | 8.82%   |
| 5.01-6.0   | 3         | 4.41%   |
| 7.01-8.0   | 2         | 2.94%   |
| 0.51-1.0   | 2         | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 15        | 16.3%   |
| AU Optronics        | 14        | 15.22%  |
| BOE                 | 11        | 11.96%  |
| Chimei Innolux      | 9         | 9.78%   |
| Dell                | 8         | 8.7%    |
| Samsung Electronics | 7         | 7.61%   |
| Goldstar            | 6         | 6.52%   |
| Sharp               | 4         | 4.35%   |
| Philips             | 3         | 3.26%   |
| InfoVision          | 3         | 3.26%   |
| PANDA               | 2         | 2.17%   |
| AOC                 | 2         | 2.17%   |
| Panasonic           | 1         | 1.09%   |
| Lenovo              | 1         | 1.09%   |
| Hewlett-Packard     | 1         | 1.09%   |
| Gigabyte Technology | 1         | 1.09%   |
| CSO                 | 1         | 1.09%   |
| BenQ                | 1         | 1.09%   |
| Apple               | 1         | 1.09%   |
| Acer                | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 2.11%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 2         | 2.11%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 2.11%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.05%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 1.05%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 1.05%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.05%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 1.05%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.05%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 1.05%   |
| Philips PHL 499P9 PHL092A 3840x1080 1193x336mm 48.8-inch              | 1         | 1.05%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.05%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 1.05%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.05%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.05%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.05%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.05%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.05%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 1         | 1.05%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.05%   |
| InfoVision LCD Monitor IVO8CBE 1920x1200 302x189mm 14.0-inch          | 1         | 1.05%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 1         | 1.05%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 1.05%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 1         | 1.05%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 46.43%  |
| 1366x768 (WXGA)    | 11        | 13.1%   |
| 2560x1440 (QHD)    | 6         | 7.14%   |
| 1920x1200 (WUXGA)  | 5         | 5.95%   |
| 3840x2160 (4K)     | 4         | 4.76%   |
| 3840x2400          | 3         | 3.57%   |
| 3440x1440          | 3         | 3.57%   |
| 1600x900 (HD+)     | 3         | 3.57%   |
| 3840x1080          | 2         | 2.38%   |
| 2560x1080          | 2         | 2.38%   |
| 1680x1050 (WSXGA+) | 2         | 2.38%   |
| 2880x1800          | 1         | 1.19%   |
| 2240x1400          | 1         | 1.19%   |
| 2160x1440          | 1         | 1.19%   |
| Unknown            | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 31        | 33.7%   |
| 14     | 19        | 20.65%  |
| 27     | 8         | 8.7%    |
| 13     | 7         | 7.61%   |
| 17     | 6         | 6.52%   |
| 34     | 4         | 4.35%   |
| 24     | 4         | 4.35%   |
| 21     | 4         | 4.35%   |
| 31     | 2         | 2.17%   |
| 49     | 1         | 1.09%   |
| 48     | 1         | 1.09%   |
| 40     | 1         | 1.09%   |
| 23     | 1         | 1.09%   |
| 22     | 1         | 1.09%   |
| 16     | 1         | 1.09%   |
| 12     | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 58.7%   |
| 501-600     | 12        | 13.04%  |
| 401-500     | 6         | 6.52%   |
| 351-400     | 6         | 6.52%   |
| 201-300     | 5         | 5.43%   |
| 701-800     | 4         | 4.35%   |
| 601-700     | 2         | 2.17%   |
| 1001-1500   | 2         | 2.17%   |
| 801-900     | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 58        | 75.32%  |
| 16/10 | 11        | 14.29%  |
| 21/9  | 4         | 5.19%   |
| 32/9  | 2         | 2.6%    |
| 3/2   | 2         | 2.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 32.97%  |
| 81-90          | 24        | 26.37%  |
| 301-350        | 8         | 8.79%   |
| 201-250        | 8         | 8.79%   |
| 351-500        | 6         | 6.59%   |
| 121-130        | 6         | 6.59%   |
| 501-1000       | 3         | 3.3%    |
| 71-80          | 2         | 2.2%    |
| 111-120        | 2         | 2.2%    |
| 61-70          | 1         | 1.1%    |
| 151-200        | 1         | 1.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 39        | 42.86%  |
| 101-120       | 19        | 20.88%  |
| 51-100        | 17        | 18.68%  |
| 161-240       | 10        | 10.99%  |
| More than 240 | 6         | 6.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 61.19%  |
| 2     | 19        | 28.36%  |
| 3     | 4         | 5.97%   |
| 0     | 2         | 2.99%   |
| 4     | 1         | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 46.3%   |
| Realtek Semiconductor | 31        | 28.7%   |
| Qualcomm Atheros      | 6         | 5.56%   |
| ASIX Electronics      | 5         | 4.63%   |
| MediaTek              | 4         | 3.7%    |
| Lenovo                | 3         | 2.78%   |
| Broadcom              | 3         | 2.78%   |
| Ralink                | 1         | 0.93%   |
| JMicron Technology    | 1         | 0.93%   |
| Dell                  | 1         | 0.93%   |
| D-Link                | 1         | 0.93%   |
| Broadcom Limited      | 1         | 0.93%   |
| ASUSTek Computer      | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 17        | 12.69%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 8         | 5.97%   |
| Intel Wireless 8265 / 8275                                         | 6         | 4.48%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 4.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 6         | 4.48%   |
| Intel Wireless 7260                                                | 5         | 3.73%   |
| ASIX AX88179 Gigabit Ethernet                                      | 5         | 3.73%   |
| Intel Ethernet Connection I217-LM                                  | 4         | 2.99%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 4         | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.24%   |
| Intel Wireless 8260                                                | 3         | 2.24%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 2.24%   |
| Intel Ethernet Connection (4) I219-V                               | 3         | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 3         | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 2         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.49%   |
| Lenovo ThinkPad TBT 3 Dock                                         | 2         | 1.49%   |
| Intel Wireless 7265                                                | 2         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                              | 2         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 1.49%   |
| Intel Ethernet Connection (16) I219-V                              | 2         | 1.49%   |
| Intel Ethernet Connection (16) I219-LM                             | 2         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 2         | 1.49%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R] | 1         | 0.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 1         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                              | 1         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                  | 1         | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                          | 1         | 0.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 1         | 0.75%   |
| Lenovo USB-C to LAN                                                | 1         | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller             | 1         | 0.75%   |
| Intel Wireless 3160                                                | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 70.59%  |
| Realtek Semiconductor | 5         | 7.35%   |
| Qualcomm Atheros      | 5         | 7.35%   |
| MediaTek              | 4         | 5.88%   |
| Broadcom              | 2         | 2.94%   |
| Ralink                | 1         | 1.47%   |
| Dell                  | 1         | 1.47%   |
| Broadcom Limited      | 1         | 1.47%   |
| ASUSTek Computer      | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                                                         | 6         | 8.82%   |
| Intel Wi-Fi 6 AX201                                                                                                | 6         | 8.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 6         | 8.82%   |
| Intel Wireless 7260                                                                                                | 5         | 7.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 4         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 4         | 5.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 4.41%   |
| Intel Wireless 8260                                                                                                | 3         | 4.41%   |
| Intel Wi-Fi 6 AX200                                                                                                | 3         | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 2         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 2.94%   |
| Intel Wireless 7265                                                                                                | 2         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 2.94%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]                                                 | 1         | 1.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                        | 1         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 1.47%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 1.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 1.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                      | 1         | 1.47%   |
| Intel Wireless 3160                                                                                                | 1         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                             | 1         | 1.47%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 1.47%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 1.47%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 1.47%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                                         | 1         | 1.47%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                                        | 1         | 1.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                                    | 1         | 1.47%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                                                     | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 43.08%  |
| Intel                 | 25        | 38.46%  |
| ASIX Electronics      | 5         | 7.69%   |
| Lenovo                | 3         | 4.62%   |
| Qualcomm Atheros      | 1         | 1.54%   |
| JMicron Technology    | 1         | 1.54%   |
| D-Link                | 1         | 1.54%   |
| Broadcom              | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 25.76%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 12.12%  |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 7.58%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 6.06%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.03%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 3.03%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.03%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 3.03%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 3.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.52%   |
| Lenovo USB-C to LAN                                               | 1         | 1.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.52%   |
| Intel Ethernet controller                                         | 1         | 1.52%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.52%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.52%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.52%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 1.52%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 54.55%  |
| Ethernet | 55        | 45.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 65%     |
| Ethernet | 28        | 35%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 67.16%  |
| 1     | 21        | 31.34%  |
| 3     | 1         | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 74.63%  |
| Yes  | 17        | 25.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 67.8%   |
| Realtek Semiconductor           | 4         | 6.78%   |
| Qualcomm Atheros Communications | 4         | 6.78%   |
| Foxconn / Hon Hai               | 3         | 5.08%   |
| Broadcom                        | 3         | 5.08%   |
| Ralink                          | 1         | 1.69%   |
| IMC Networks                    | 1         | 1.69%   |
| Hewlett-Packard                 | 1         | 1.69%   |
| Dell                            | 1         | 1.69%   |
| Apple                           | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 16        | 27.12%  |
| Intel AX201 Bluetooth                              | 13        | 22.03%  |
| Intel Bluetooth Device                             | 4         | 6.78%   |
| Realtek Bluetooth Radio                            | 3         | 5.08%   |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 5.08%   |
| Intel AX200 Bluetooth                              | 3         | 5.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 3.39%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 3.39%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 1.69%   |
| Ralink RT3290 Bluetooth                            | 1         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.69%   |
| Intel AX210 Bluetooth                              | 1         | 1.69%   |
| IMC Networks Wireless_Device                       | 1         | 1.69%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.69%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth        | 1         | 1.69%   |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 1.69%   |
| Broadcom HP Portable Bumble Bee                    | 1         | 1.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 1.69%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.69%   |
| Apple Bluetooth Host Controller                    | 1         | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 53.4%   |
| Nvidia                | 17        | 16.5%   |
| AMD                   | 11        | 10.68%  |
| Logitech              | 4         | 3.88%   |
| Lenovo                | 2         | 1.94%   |
| GN Netcom             | 2         | 1.94%   |
| Conexant Systems      | 2         | 1.94%   |
| C-Media Electronics   | 2         | 1.94%   |
| Texas Instruments     | 1         | 0.97%   |
| Tenx Technology       | 1         | 0.97%   |
| Saitek                | 1         | 0.97%   |
| Realtek Semiconductor | 1         | 0.97%   |
| Huawei Technologies   | 1         | 0.97%   |
| Hewlett-Packard       | 1         | 0.97%   |
| Creative Technology   | 1         | 0.97%   |
| ASUSTek Computer      | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 6.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 6.61%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 6.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 5.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 4.13%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 3.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.48%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.48%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.65%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.65%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.65%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.65%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.83%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.83%   |
| Saitek Cyborg F.R.E.Q.5 Gaming Headset                                     | 1         | 0.83%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.83%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.83%   |
| Nvidia Audio device                                                        | 1         | 0.83%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.83%   |
| Logitech Stereo H650e                                                      | 1         | 0.83%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1         | 0.83%   |
| Logitech Headset H390                                                      | 1         | 0.83%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 0.83%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.83%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 34.09%  |
| SK hynix            | 12        | 27.27%  |
| Micron Technology   | 4         | 9.09%   |
| Crucial             | 4         | 9.09%   |
| Kingston            | 2         | 4.55%   |
| Smart               | 1         | 2.27%   |
| Ramaxel Technology  | 1         | 2.27%   |
| Magnum Tech         | 1         | 2.27%   |
| Lexar Co Limited    | 1         | 2.27%   |
| Lexar               | 1         | 2.27%   |
| G.Skill             | 1         | 2.27%   |
| A-DATA Technology   | 1         | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 4.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 4.44%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s          | 1         | 2.22%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                   | 1         | 2.22%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1         | 2.22%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.22%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 1         | 2.22%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.22%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 2.22%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 2.22%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 2.22%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                   | 1         | 2.22%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 1         | 2.22%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s    | 1         | 2.22%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 2.22%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 2.22%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s   | 1         | 2.22%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s   | 1         | 2.22%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB LPDDR5 5500MT/s                | 1         | 2.22%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s      | 1         | 2.22%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s        | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s          | 1         | 2.22%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16384MB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s          | 1         | 2.22%   |
| Lexar Co Limited RAM LD4AS008G-2666SC 8GB SODIMM DDR4 2667MT/s | 1         | 2.22%   |
| Kingston RAM 9905703-006.A00G 16GB SODIMM DDR4 2400MT/s        | 1         | 2.22%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 2.22%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s      | 1         | 2.22%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s     | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 56.41%  |
| DDR3   | 10        | 25.64%  |
| DDR5   | 3         | 7.69%   |
| LPDDR5 | 2         | 5.13%   |
| LPDDR4 | 1         | 2.56%   |
| LPDDR3 | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 87.5%   |
| Row Of Chips | 4         | 10%     |
| Unknown      | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 54.76%  |
| 16384 | 10        | 23.81%  |
| 4096  | 7         | 16.67%  |
| 32768 | 2         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 13        | 32.5%   |
| 2667  | 8         | 20%     |
| 1600  | 8         | 20%     |
| 4800  | 3         | 7.5%    |
| 2400  | 2         | 5%      |
| 2133  | 2         | 5%      |
| 6400  | 1         | 2.5%    |
| 5500  | 1         | 2.5%    |
| 4266  | 1         | 2.5%    |
| 1066  | 1         | 2.5%    |

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
| Chicony Electronics                    | 16        | 27.12%  |
| IMC Networks                           | 10        | 16.95%  |
| Realtek Semiconductor                  | 5         | 8.47%   |
| Microdia                               | 5         | 8.47%   |
| Syntek                                 | 3         | 5.08%   |
| Sunplus Innovation Technology          | 3         | 5.08%   |
| Luxvisions Innotech Limited            | 3         | 5.08%   |
| Bison Electronics                      | 3         | 5.08%   |
| Quanta                                 | 2         | 3.39%   |
| Logitech                               | 2         | 3.39%   |
| Suyin                                  | 1         | 1.69%   |
| Sonix Technology                       | 1         | 1.69%   |
| Lite-On Technology                     | 1         | 1.69%   |
| Lenovo                                 | 1         | 1.69%   |
| Intel                                  | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.69%   |
| Apple                                  | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 8         | 13.33%  |
| Microdia Integrated_Webcam_HD                                              | 4         | 6.67%   |
| IMC Networks Integrated Camera                                             | 4         | 6.67%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 5%      |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 5%      |
| Chicony HP HD Camera                                                       | 3         | 5%      |
| Syntek Lenovo EasyCamera                                                   | 2         | 3.33%   |
| Chicony HD WebCam                                                          | 2         | 3.33%   |
| Bison Integrated RGB Camera                                                | 2         | 3.33%   |
| Syntek Integrated Camera                                                   | 1         | 1.67%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.67%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.67%   |
| Sunplus FHD Camera Microphone                                              | 1         | 1.67%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 1.67%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 1.67%   |
| Realtek EasyCamera                                                         | 1         | 1.67%   |
| Quanta HP Webcam                                                           | 1         | 1.67%   |
| Quanta HP 5MP Camera                                                       | 1         | 1.67%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.67%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 1         | 1.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.67%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 1.67%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.67%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 1.67%   |
| Lite-On HP HD Webcam                                                       | 1         | 1.67%   |
| Lenovo UVC Camera                                                          | 1         | 1.67%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 1.67%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 1.67%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.67%   |
| IMC Networks HD Camera                                                     | 1         | 1.67%   |
| Chicony USB2.0 FHD UVC WebCam                                              | 1         | 1.67%   |
| Chicony thinkpad t430s camera                                              | 1         | 1.67%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.67%   |
| Chicony HP HD Webcam                                                       | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.67%   |
| Bison Integrated Camera                                                    | 1         | 1.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 36.36%  |
| Validity Sensors           | 7         | 31.82%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| LighTuning Technology      | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 13.64%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 9.09%   |
| Synaptics UWP WBDI Device                                                  | 2         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 9.09%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 4.55%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4.55%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 4.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.55%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 4.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.55%   |
| AuthenTec AES2810                                                          | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 50%     |
| Broadcom    | 2         | 33.33%  |
| O2 Micro    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 31        | 46.27%  |
| 1     | 29        | 43.28%  |
| 2     | 6         | 8.96%   |
| 3     | 1         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 22        | 50%     |
| Graphics card         | 7         | 15.91%  |
| Net/wireless          | 3         | 6.82%   |
| Net/ethernet          | 3         | 6.82%   |
| Multimedia controller | 3         | 6.82%   |
| Chipcard              | 3         | 6.82%   |
| Sound                 | 1         | 2.27%   |
| Card reader           | 1         | 2.27%   |
| Bluetooth             | 1         | 2.27%   |

