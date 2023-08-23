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

Total: 76

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 9.1 | 21        | 35%     |
| Rocky Linux 8.5 | 11        | 18.33%  |
| Rocky Linux 9.0 | 9         | 15%     |
| Rocky Linux 8.4 | 8         | 13.33%  |
| Rocky Linux 9.2 | 4         | 6.67%   |
| Rocky Linux 8.7 | 3         | 5%      |
| Rocky Linux 8.8 | 2         | 3.33%   |
| Rocky Linux 8.6 | 1         | 1.67%   |
| Rocky Linux 8.3 | 1         | 1.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 60        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 14.52%  |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 6.45%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 4         | 6.45%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 6.45%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 3         | 4.84%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 4.84%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 3.23%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 2         | 3.23%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 2         | 3.23%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 3.23%   |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 3.23%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 3.23%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 3.23%   |
| 4.18.0-305.el8.x86_64            | 2         | 3.23%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 3.23%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 3.23%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 3.23%   |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 1.61%   |
| 6.2.10-1.el8.elrepo.x86_64       | 1         | 1.61%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.61%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 1.61%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 1         | 1.61%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1         | 1.61%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.61%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 1         | 1.61%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 1.61%   |
| 5.10.89-1.el8.x86_64             | 1         | 1.61%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.61%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1         | 1.61%   |
| 4.18.0-240.22.1.el8.x86_64       | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 33        | 55%     |
| 4.18.0  | 22        | 36.67%  |
| 6.2.12  | 1         | 1.67%   |
| 6.2.10  | 1         | 1.67%   |
| 5.4.157 | 1         | 1.67%   |
| 5.16.15 | 1         | 1.67%   |
| 5.10.89 | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 33        | 55%     |
| 4.18    | 22        | 36.67%  |
| 6.2     | 2         | 3.33%   |
| 5.4     | 1         | 1.67%   |
| 5.16    | 1         | 1.67%   |
| 5.10    | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 60        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 44        | 73.33%  |
| KDE5          | 5         | 8.33%   |
| MATE          | 4         | 6.67%   |
| XFCE          | 3         | 5%      |
| Unknown       | 2         | 3.33%   |
| X-Cinnamon    | 1         | 1.67%   |
| GNOME Classic | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 38        | 63.33%  |
| X11     | 20        | 33.33%  |
| Tty     | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 48.33%  |
| GDM     | 23        | 38.33%  |
| SDDM    | 5         | 8.33%   |
| LightDM | 3         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 44        | 73.33%  |
| ru_RU | 2         | 3.33%   |
| en_ZA | 2         | 3.33%   |
| en_IE | 2         | 3.33%   |
| en_CA | 2         | 3.33%   |
| de_DE | 2         | 3.33%   |
| C     | 2         | 3.33%   |
| zh_TW | 1         | 1.67%   |
| pt_BR | 1         | 1.67%   |
| it_IT | 1         | 1.67%   |
| fr_FR | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 49        | 81.67%  |
| BIOS | 11        | 18.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 51        | 85%     |
| Ext4 | 8         | 13.33%  |
| Ext3 | 1         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 29        | 48.33%  |
| Unknown | 28        | 46.67%  |
| MBR     | 3         | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 90%     |
| Yes       | 6         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 76.67%  |
| Yes       | 14        | 23.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 22        | 36.67%  |
| Hewlett-Packard  | 13        | 21.67%  |
| Dell             | 10        | 16.67%  |
| ASUSTek Computer | 7         | 11.67%  |
| Toshiba          | 2         | 3.33%   |
| Acer             | 2         | 3.33%   |
| Positivo         | 1         | 1.67%   |
| HUAWEI           | 1         | 1.67%   |
| Beelink          | 1         | 1.67%   |
| BANGHO           | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 1.67%   |
| Toshiba Satellite E45-B                  | 1         | 1.67%   |
| Positivo Mobile                          | 1         | 1.67%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 1.67%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 1.67%   |
| Lenovo ThinkPad W500 406132G             | 1         | 1.67%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 1.67%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 1.67%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 1.67%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 1.67%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 1.67%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV     | 1         | 1.67%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 1.67%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK      | 1         | 1.67%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB     | 1         | 1.67%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 1.67%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.67%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.67%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 1.67%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.67%   |
| Lenovo IdeaPad S210 Touch 20257          | 1         | 1.67%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 1         | 1.67%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 1.67%   |
| Lenovo IdeaPad 3 15ITL6 82H8             | 1         | 1.67%   |
| HUAWEI KLVD-WXX9                         | 1         | 1.67%   |
| HP ZBook 15u G6                          | 1         | 1.67%   |
| HP ZBook 15u G5                          | 1         | 1.67%   |
| HP ZBook 15 G3                           | 1         | 1.67%   |
| HP ZBook 15 G2                           | 1         | 1.67%   |
| HP ProBook 645 G1                        | 1         | 1.67%   |
| HP ProBook 640 G3                        | 1         | 1.67%   |
| HP Pavilion g6                           | 1         | 1.67%   |
| HP Laptop 17-ca1xxx                      | 1         | 1.67%   |
| HP Laptop 15-dy2xxx                      | 1         | 1.67%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 1.67%   |
| HP EliteBook 840 G5                      | 1         | 1.67%   |
| HP EliteBook 2560p                       | 1         | 1.67%   |
| HP EliteBook 1040 14 inch G9 Notebook PC | 1         | 1.67%   |
| Dell XPS 17 9720                         | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 13        | 21.67%  |
| Lenovo IdeaPad    | 7         | 11.67%  |
| HP ZBook          | 4         | 6.67%   |
| HP EliteBook      | 4         | 6.67%   |
| Dell Latitude     | 4         | 6.67%   |
| ASUS ASUS         | 3         | 5%      |
| Lenovo Legion     | 2         | 3.33%   |
| HP ProBook        | 2         | 3.33%   |
| HP Laptop         | 2         | 3.33%   |
| Dell XPS          | 2         | 3.33%   |
| Dell Inspiron     | 2         | 3.33%   |
| Acer Aspire       | 2         | 3.33%   |
| Toshiba TECRA     | 1         | 1.67%   |
| Toshiba Satellite | 1         | 1.67%   |
| Positivo Mobile   | 1         | 1.67%   |
| HUAWEI KLVD-WXX9  | 1         | 1.67%   |
| HP Pavilion       | 1         | 1.67%   |
| Dell Vostro       | 1         | 1.67%   |
| Dell Precision    | 1         | 1.67%   |
| Beelink BT3       | 1         | 1.67%   |
| BANGHO BES        | 1         | 1.67%   |
| ASUS VivoBook     | 1         | 1.67%   |
| ASUS UX430UNR     | 1         | 1.67%   |
| ASUS ROG          | 1         | 1.67%   |
| ASUS G752VM       | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 13.33%  |
| 2020 | 8         | 13.33%  |
| 2022 | 7         | 11.67%  |
| 2019 | 7         | 11.67%  |
| 2018 | 6         | 10%     |
| 2014 | 5         | 8.33%   |
| 2017 | 3         | 5%      |
| 2015 | 3         | 5%      |
| 2013 | 3         | 5%      |
| 2011 | 3         | 5%      |
| 2016 | 2         | 3.33%   |
| 2012 | 2         | 3.33%   |
| 2010 | 2         | 3.33%   |
| 2009 | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 60        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 49        | 81.67%  |
| Enabled  | 11        | 18.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 19        | 31.67%  |
| 4.01-8.0    | 16        | 26.67%  |
| 32.01-64.0  | 13        | 21.67%  |
| 16.01-24.0  | 6         | 10%     |
| 3.01-4.0    | 3         | 5%      |
| 24.01-32.0  | 2         | 3.33%   |
| 64.01-256.0 | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 30.16%  |
| 2.01-3.0   | 15        | 23.81%  |
| 3.01-4.0   | 13        | 20.63%  |
| 1.01-2.0   | 7         | 11.11%  |
| 8.01-16.0  | 5         | 7.94%   |
| 0.51-1.0   | 2         | 3.17%   |
| 24.01-32.0 | 1         | 1.59%   |
| 16.01-24.0 | 1         | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 47        | 78.33%  |
| 2      | 8         | 13.33%  |
| 3      | 4         | 6.67%   |
| 4      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 83.33%  |
| Yes       | 10        | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 83.61%  |
| No        | 10        | 16.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 98.33%  |
| No        | 1         | 1.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 86.67%  |
| No        | 8         | 13.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 16        | 26.67%  |
| Russia       | 3         | 5%      |
| Poland       | 3         | 5%      |
| Germany      | 3         | 5%      |
| South Africa | 2         | 3.33%   |
| Italy        | 2         | 3.33%   |
| Ireland      | 2         | 3.33%   |
| Hungary      | 2         | 3.33%   |
| Czechia      | 2         | 3.33%   |
| Canada       | 2         | 3.33%   |
| Brazil       | 2         | 3.33%   |
| Belgium      | 2         | 3.33%   |
| Uzbekistan   | 1         | 1.67%   |
| UAE          | 1         | 1.67%   |
| Turkey       | 1         | 1.67%   |
| Taiwan       | 1         | 1.67%   |
| Sweden       | 1         | 1.67%   |
| Spain        | 1         | 1.67%   |
| Slovakia     | 1         | 1.67%   |
| Saudi Arabia | 1         | 1.67%   |
| Pakistan     | 1         | 1.67%   |
| Norway       | 1         | 1.67%   |
| Netherlands  | 1         | 1.67%   |
| Malaysia     | 1         | 1.67%   |
| Kazakhstan   | 1         | 1.67%   |
| France       | 1         | 1.67%   |
| Croatia      | 1         | 1.67%   |
| China        | 1         | 1.67%   |
| Bulgaria     | 1         | 1.67%   |
| Austria      | 1         | 1.67%   |
| Argentina    | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Budapest               | 2         | 3.33%   |
| Žilina                | 1         | 1.67%   |
| Xi'an                  | 1         | 1.67%   |
| Vienna                 | 1         | 1.67%   |
| Troisdorf              | 1         | 1.67%   |
| Torrington             | 1         | 1.67%   |
| Taoyuan City           | 1         | 1.67%   |
| Syracuse               | 1         | 1.67%   |
| Spokane                | 1         | 1.67%   |
| Split                  | 1         | 1.67%   |
| Sofia                  | 1         | 1.67%   |
| Smolensk               | 1         | 1.67%   |
| Senigallia             | 1         | 1.67%   |
| Scarborough            | 1         | 1.67%   |
| San Miguel de Tucumán | 1         | 1.67%   |
| Riyadh                 | 1         | 1.67%   |
| Rawalpindi             | 1         | 1.67%   |
| Qualicum Beach         | 1         | 1.67%   |
| Prague                 | 1         | 1.67%   |
| Philadelphia           | 1         | 1.67%   |
| Ottignies              | 1         | 1.67%   |
| Oslo                   | 1         | 1.67%   |
| Örebro                | 1         | 1.67%   |
| Oakley                 | 1         | 1.67%   |
| Nur-Sultan             | 1         | 1.67%   |
| Mugla                  | 1         | 1.67%   |
| Mossel Bay             | 1         | 1.67%   |
| Moscow                 | 1         | 1.67%   |
| Montreal               | 1         | 1.67%   |
| Melun                  | 1         | 1.67%   |
| Madrid                 | 1         | 1.67%   |
| Lodz                   | 1         | 1.67%   |
| Lenexa                 | 1         | 1.67%   |
| Kutno                  | 1         | 1.67%   |
| Krakow                 | 1         | 1.67%   |
| Kansas City            | 1         | 1.67%   |
| Johor Bahru            | 1         | 1.67%   |
| Jaú                   | 1         | 1.67%   |
| Inman                  | 1         | 1.67%   |
| Houston                | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 21        | 24     | 26.58%  |
| SanDisk                 | 7         | 9      | 8.86%   |
| WDC                     | 6         | 6      | 7.59%   |
| Kingston                | 5         | 5      | 6.33%   |
| Toshiba                 | 4         | 5      | 5.06%   |
| Intel                   | 4         | 4      | 5.06%   |
| Unknown                 | 3         | 3      | 3.8%    |
| SK hynix                | 3         | 5      | 3.8%    |
| Micron Technology       | 3         | 3      | 3.8%    |
| Seagate                 | 2         | 2      | 2.53%   |
| Lexar                   | 2         | 2      | 2.53%   |
| Dogfish                 | 2         | 2      | 2.53%   |
| A-DATA Technology       | 2         | 2      | 2.53%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.27%   |
| UMIS                    | 1         | 1      | 1.27%   |
| StoreJet                | 1         | 1      | 1.27%   |
| Phison                  | 1         | 2      | 1.27%   |
| LITEONIT                | 1         | 1      | 1.27%   |
| LITEON                  | 1         | 1      | 1.27%   |
| JMicron Technology      | 1         | 1      | 1.27%   |
| INDMEM                  | 1         | 1      | 1.27%   |
| HS-SSD-C100             | 1         | 1      | 1.27%   |
| Hitachi                 | 1         | 1      | 1.27%   |
| Fujitsu                 | 1         | 1      | 1.27%   |
| Crucial                 | 1         | 1      | 1.27%   |
| ASMT                    | 1         | 1      | 1.27%   |
| AGI                     | 1         | 1      | 1.27%   |
| ADATA Technology        | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 870 EVO 1TB                             | 2         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 2.38%   |
| Lexar 512GB SSD                                     | 2         | 2.38%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 1.19%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 1.19%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 1.19%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 1.19%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1.19%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.19%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 1.19%   |
| Unknown S0J38Y  64GB                                | 1         | 1.19%   |
| Unknown MMC Card  64GB                              | 1         | 1.19%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1         | 1.19%   |
| UMIS RPFTJ128PDD2EWX 128GB                          | 1         | 1.19%   |
| Toshiba THNSNJ512GACU 512GB SSD                     | 1         | 1.19%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 1.19%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 1.19%   |
| Toshiba KXG6AZNV1T02 1TB                            | 1         | 1.19%   |
| Toshiba KXG6APNV2T04 2TB                            | 1         | 1.19%   |
| StoreJet Disk 2TB                                   | 1         | 1.19%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB           | 1         | 1.19%   |
| SK hynix SHPP41-2000GM 2TB                          | 1         | 1.19%   |
| SK hynix NVMe SSD Drive 512GB                       | 1         | 1.19%   |
| SK hynix BC511 NVMe 512GB                           | 1         | 1.19%   |
| Seagate ST9320325AS 320GB                           | 1         | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.19%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 1.19%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1024GB        | 1         | 1.19%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 1         | 1.19%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1.19%   |
| SanDisk SDSSDA120G 120GB                            | 1         | 1.19%   |
| SanDisk SD8SN8U512G1002 512GB SSD                   | 1         | 1.19%   |
| SanDisk SD5SG2256G1052E 256GB SSD                   | 1         | 1.19%   |
| SanDisk Extreme 55AE 1TB SSD                        | 1         | 1.19%   |
| Samsung SSD 970 EVO 500GB                           | 1         | 1.19%   |
| Samsung SSD 870 QVO 2TB                             | 1         | 1.19%   |
| Samsung SSD 860 QVO 4TB                             | 1         | 1.19%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 1.19%   |
| Samsung PM9A1 NVMe SED 512GB                        | 1         | 1.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 4         | 4      | 40%     |
| Seagate  | 2         | 2      | 20%     |
| Unknown  | 1         | 1      | 10%     |
| StoreJet | 1         | 1      | 10%     |
| Hitachi  | 1         | 1      | 10%     |
| Fujitsu  | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 27.59%  |
| SanDisk             | 4         | 5      | 13.79%  |
| Kingston            | 3         | 3      | 10.34%  |
| WDC                 | 2         | 2      | 6.9%    |
| Toshiba             | 2         | 2      | 6.9%    |
| Dogfish             | 2         | 2      | 6.9%    |
| LITEONIT            | 1         | 1      | 3.45%   |
| LITEON              | 1         | 1      | 3.45%   |
| Lexar               | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| INDMEM              | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| ASMT                | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 34        | 42     | 47.89%  |
| SSD     | 24        | 31     | 33.8%   |
| HDD     | 8         | 10     | 11.27%  |
| Unknown | 3         | 3      | 4.23%   |
| MMC     | 2         | 2      | 2.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 34        | 42     | 48.57%  |
| SATA | 29        | 38     | 41.43%  |
| SAS  | 5         | 6      | 7.14%   |
| MMC  | 2         | 2      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 22     | 55.88%  |
| 0.51-1.0   | 11        | 14     | 32.35%  |
| 1.01-2.0   | 3         | 3      | 8.82%   |
| 3.01-4.0   | 1         | 2      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 19        | 31.67%  |
| 101-250        | 17        | 28.33%  |
| 501-1000       | 11        | 18.33%  |
| 1001-2000      | 4         | 6.67%   |
| 51-100         | 4         | 6.67%   |
| 2001-3000      | 3         | 5%      |
| More than 3000 | 1         | 1.67%   |
| 1-20           | 1         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 22        | 36.07%  |
| 21-50     | 14        | 22.95%  |
| 101-250   | 9         | 14.75%  |
| 51-100    | 9         | 14.75%  |
| 251-500   | 3         | 4.92%   |
| 1001-2000 | 2         | 3.28%   |
| 501-1000  | 2         | 3.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Works    | 33        | 47     | 52.38%  |
| Detected | 30        | 41     | 47.62%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 35        | 48.61%  |
| Samsung Electronics          | 13        | 18.06%  |
| AMD                          | 6         | 8.33%   |
| SK hynix                     | 3         | 4.17%   |
| SanDisk                      | 3         | 4.17%   |
| Micron Technology            | 3         | 4.17%   |
| Toshiba America Info Systems | 2         | 2.78%   |
| Kingston Technology Company  | 2         | 2.78%   |
| Union Memory (Shenzhen)      | 1         | 1.39%   |
| Shenzhen Longsys Electronics | 1         | 1.39%   |
| Realtek Semiconductor        | 1         | 1.39%   |
| Phison Electronics           | 1         | 1.39%   |
| ADATA Technology             | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 7.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 6.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 6.33%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 5.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 5.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 3.8%    |
| Samsung NVMe SSD Controller 980                                                        | 3         | 3.8%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 3.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 3.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 2.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 2.53%   |
| Micron 3400 NVMe SSD [Hendrix]                                                         | 2         | 2.53%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 2         | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 2.53%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 2.53%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                                  | 1         | 1.27%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                     | 1         | 1.27%   |
| SK hynix PC611 NVMe Solid State Drive                                                  | 1         | 1.27%   |
| SK hynix BC511 NVMe SSD                                                                | 1         | 1.27%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                      | 1         | 1.27%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                | 1         | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.27%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                  | 1         | 1.27%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 1.27%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                      | 1         | 1.27%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.27%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 1         | 1.27%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 1         | 1.27%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.27%   |
| Intel SSD 660P Series                                                                  | 1         | 1.27%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 34        | 45.33%  |
| SATA | 31        | 41.33%  |
| RAID | 5         | 6.67%   |
| IDE  | 5         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 83.33%  |
| AMD    | 10        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 4         | 6.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 3         | 5%      |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 3.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 3.33%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 1.67%   |
| Intel Core i7-8665U CPU @ 1.90GHz        | 1         | 1.67%   |
| Intel Core i7-7600U CPU @ 2.80GHz        | 1         | 1.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 1.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 1         | 1.67%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz       | 1         | 1.67%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz       | 1         | 1.67%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 1         | 1.67%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz       | 1         | 1.67%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 1         | 1.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 1         | 1.67%   |
| Intel Core i7-10875H CPU @ 2.30GHz       | 1         | 1.67%   |
| Intel Core i7-10610U CPU @ 1.80GHz       | 1         | 1.67%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 1.67%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 1.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 1.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 1.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 1.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.67%   |
| Intel Core i5-4200M CPU @ 2.50GHz        | 1         | 1.67%   |
| Intel Core i5-3427U CPU @ 1.80GHz        | 1         | 1.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 1.67%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 1         | 1.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.67%   |
| Intel Core i3 CPU M 380 @ 2.53GHz        | 1         | 1.67%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz     | 1         | 1.67%   |
| Intel Celeron CPU 1037U @ 1.80GHz        | 1         | 1.67%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz        | 1         | 1.67%   |
| Intel 12th Gen Core i7-12700H            | 1         | 1.67%   |
| Intel 12th Gen Core i7-1265U             | 1         | 1.67%   |
| Intel 12th Gen Core i7-12650H            | 1         | 1.67%   |
| Intel 12th Gen Core i7-1260P             | 1         | 1.67%   |
| Intel 12th Gen Core i5-1245U             | 1         | 1.67%   |
| Intel 12th Gen Core i5-1235U             | 1         | 1.67%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz  | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 20        | 33.33%  |
| Other                | 15        | 25%     |
| Intel Core i5        | 11        | 18.33%  |
| AMD Ryzen 5          | 4         | 6.67%   |
| AMD Ryzen 7          | 2         | 3.33%   |
| Intel Pentium Silver | 1         | 1.67%   |
| Intel Core i3        | 1         | 1.67%   |
| Intel Core 2 Duo     | 1         | 1.67%   |
| Intel Celeron        | 1         | 1.67%   |
| Intel Atom           | 1         | 1.67%   |
| AMD Ryzen 5 PRO      | 1         | 1.67%   |
| AMD A8               | 1         | 1.67%   |
| AMD A10              | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 27        | 45%     |
| 2      | 16        | 26.67%  |
| 6      | 6         | 10%     |
| 10     | 4         | 6.67%   |
| 8      | 4         | 6.67%   |
| 14     | 1         | 1.67%   |
| 12     | 1         | 1.67%   |
| 1      | 1         | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 85%     |
| 1      | 9         | 15%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 60        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 7         | 11.67%  |
| 0x306c3    | 7         | 11.67%  |
| 0x806ec    | 4         | 6.67%   |
| 0x806ea    | 4         | 6.67%   |
| 0xa0652    | 3         | 5%      |
| 0x506e3    | 3         | 5%      |
| 0x306a9    | 3         | 5%      |
| 0x906a4    | 2         | 3.33%   |
| 0x906a3    | 2         | 3.33%   |
| 0x806e9    | 2         | 3.33%   |
| 0x206a7    | 2         | 3.33%   |
| 0x0a50000c | 2         | 3.33%   |
| 0x08600104 | 2         | 3.33%   |
| Unknown    | 2         | 3.33%   |
| 0x906ea    | 1         | 1.67%   |
| 0x806d1    | 1         | 1.67%   |
| 0x706a1    | 1         | 1.67%   |
| 0x406e3    | 1         | 1.67%   |
| 0x406c4    | 1         | 1.67%   |
| 0x40651    | 1         | 1.67%   |
| 0x306d4    | 1         | 1.67%   |
| 0x20655    | 1         | 1.67%   |
| 0x10676    | 1         | 1.67%   |
| 0x0a50000d | 1         | 1.67%   |
| 0x0a404101 | 1         | 1.67%   |
| 0x08108102 | 1         | 1.67%   |
| 0x06006705 | 1         | 1.67%   |
| 0x06001119 | 1         | 1.67%   |
| 0x06001116 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 18.33%  |
| Haswell          | 8         | 13.33%  |
| TigerLake        | 7         | 11.67%  |
| Alderlake Hybrid | 6         | 10%     |
| Skylake          | 4         | 6.67%   |
| Zen 3            | 3         | 5%      |
| IvyBridge        | 3         | 5%      |
| CometLake        | 3         | 5%      |
| Zen 2            | 2         | 3.33%   |
| SandyBridge      | 2         | 3.33%   |
| Piledriver       | 2         | 3.33%   |
| Zen+             | 1         | 1.67%   |
| Westmere         | 1         | 1.67%   |
| Silvermont       | 1         | 1.67%   |
| Penryn           | 1         | 1.67%   |
| Icelake          | 1         | 1.67%   |
| Goldmont plus    | 1         | 1.67%   |
| Excavator        | 1         | 1.67%   |
| Broadwell        | 1         | 1.67%   |
| Unknown          | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 54.76%  |
| Nvidia | 27        | 32.14%  |
| AMD    | 11        | 13.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 8.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 5.88%   |
| Intel UHD Graphics 620                                                    | 4         | 4.71%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 3.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 3.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 3.53%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 3         | 3.53%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 3.53%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 2         | 2.35%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 2.35%   |
| Nvidia GM108M [GeForce 940M]                                              | 2         | 2.35%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.35%   |
| Intel HD Graphics 620                                                     | 2         | 2.35%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 2.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 2.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.35%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.18%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.18%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 1.18%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 1.18%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.18%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.18%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 1.18%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 1.18%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.18%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 1.18%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.18%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.18%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 1.18%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.18%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.18%   |
| Intel HD Graphics 5500                                                    | 1         | 1.18%   |
| Intel HD Graphics 530                                                     | 1         | 1.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.18%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 41.67%  |
| Intel + Nvidia | 19        | 31.67%  |
| 1 x Nvidia     | 5         | 8.33%   |
| 1 x AMD        | 5         | 8.33%   |
| AMD + Nvidia   | 3         | 5%      |
| Intel + AMD    | 2         | 3.33%   |
| 2 x AMD        | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 49        | 81.67%  |
| Proprietary | 10        | 16.67%  |
| Unknown     | 1         | 1.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 55.74%  |
| 3.01-4.0   | 9         | 14.75%  |
| 1.01-2.0   | 6         | 9.84%   |
| 0.01-0.5   | 5         | 8.2%    |
| 5.01-6.0   | 3         | 4.92%   |
| 7.01-8.0   | 2         | 3.28%   |
| 0.51-1.0   | 2         | 3.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 14        | 17.07%  |
| AU Optronics        | 13        | 15.85%  |
| BOE                 | 11        | 13.41%  |
| Dell                | 8         | 9.76%   |
| Chimei Innolux      | 8         | 9.76%   |
| Samsung Electronics | 7         | 8.54%   |
| Goldstar            | 4         | 4.88%   |
| Philips             | 3         | 3.66%   |
| InfoVision          | 3         | 3.66%   |
| Sharp               | 2         | 2.44%   |
| PANDA               | 2         | 2.44%   |
| AOC                 | 2         | 2.44%   |
| Panasonic           | 1         | 1.22%   |
| Lenovo              | 1         | 1.22%   |
| Gigabyte Technology | 1         | 1.22%   |
| BenQ                | 1         | 1.22%   |
| Acer                | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 2.38%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 2         | 2.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 2.38%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.19%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.19%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 1.19%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.19%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 1.19%   |
| Philips PHL 499P9 PHL092A 3840x1080 1193x336mm 48.8-inch              | 1         | 1.19%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.19%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 1.19%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.19%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD06F9 1920x1200 300x190mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 1         | 1.19%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.19%   |
| InfoVision LCD Monitor IVO8CBE 1920x1200 302x189mm 14.0-inch          | 1         | 1.19%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 1.19%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.19%   |
| Goldstar UltraFine GSM5B11 2560x2880 600x340mm 27.2-inch              | 1         | 1.19%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 1         | 1.19%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.19%   |
| Gigabyte Technology G27QC A GBT2716 2560x1440 600x340mm 27.2-inch     | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 50.68%  |
| 1366x768 (WXGA)    | 11        | 15.07%  |
| 2560x1440 (QHD)    | 4         | 5.48%   |
| 3840x2160 (4K)     | 3         | 4.11%   |
| 1920x1200 (WUXGA)  | 3         | 4.11%   |
| 1600x900 (HD+)     | 3         | 4.11%   |
| 3840x2400          | 2         | 2.74%   |
| 3840x1080          | 2         | 2.74%   |
| 3440x1440          | 2         | 2.74%   |
| 1680x1050 (WSXGA+) | 2         | 2.74%   |
| 2560x1080          | 1         | 1.37%   |
| 2240x1400          | 1         | 1.37%   |
| 2160x1440          | 1         | 1.37%   |
| Unknown            | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 27        | 33.33%  |
| 14     | 17        | 20.99%  |
| 27     | 8         | 9.88%   |
| 17     | 6         | 7.41%   |
| 13     | 6         | 7.41%   |
| 21     | 4         | 4.94%   |
| 34     | 3         | 3.7%    |
| 24     | 3         | 3.7%    |
| 49     | 1         | 1.23%   |
| 48     | 1         | 1.23%   |
| 31     | 1         | 1.23%   |
| 23     | 1         | 1.23%   |
| 22     | 1         | 1.23%   |
| 16     | 1         | 1.23%   |
| 12     | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 59.26%  |
| 501-600     | 11        | 13.58%  |
| 401-500     | 6         | 7.41%   |
| 351-400     | 6         | 7.41%   |
| 201-300     | 4         | 4.94%   |
| 701-800     | 3         | 3.7%    |
| 1001-1500   | 2         | 2.47%   |
| 601-700     | 1         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 54        | 79.41%  |
| 16/10 | 7         | 10.29%  |
| 21/9  | 3         | 4.41%   |
| 32/9  | 2         | 2.94%   |
| 3/2   | 2         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 33.75%  |
| 81-90          | 22        | 27.5%   |
| 301-350        | 8         | 10%     |
| 201-250        | 7         | 8.75%   |
| 121-130        | 6         | 7.5%    |
| 351-500        | 4         | 5%      |
| 501-1000       | 2         | 2.5%    |
| 71-80          | 1         | 1.25%   |
| 61-70          | 1         | 1.25%   |
| 151-200        | 1         | 1.25%   |
| 111-120        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 45.68%  |
| 101-120       | 19        | 23.46%  |
| 51-100        | 14        | 17.28%  |
| 161-240       | 7         | 8.64%   |
| More than 240 | 4         | 4.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 61.67%  |
| 2     | 17        | 28.33%  |
| 3     | 3         | 5%      |
| 0     | 2         | 3.33%   |
| 4     | 1         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 46.88%  |
| Realtek Semiconductor | 30        | 31.25%  |
| Qualcomm Atheros      | 6         | 6.25%   |
| MediaTek              | 4         | 4.17%   |
| Lenovo                | 2         | 2.08%   |
| Broadcom              | 2         | 2.08%   |
| ASIX Electronics      | 2         | 2.08%   |
| Ralink                | 1         | 1.04%   |
| JMicron Technology    | 1         | 1.04%   |
| Dell                  | 1         | 1.04%   |
| D-Link                | 1         | 1.04%   |
| Broadcom Limited      | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 14.29%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 6.72%   |
| Intel Wireless 8265 / 8275                                        | 6         | 5.04%   |
| Intel Wireless 7260                                               | 5         | 4.2%    |
| Intel Wi-Fi 6 AX201                                               | 5         | 4.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 4.2%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 3.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 2.52%   |
| Intel Wireless 8260                                               | 3         | 2.52%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.52%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 2.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.68%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.68%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.84%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.84%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.84%   |
| Lenovo USB-C to LAN                                               | 1         | 0.84%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.84%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.84%   |
| Intel Wireless 7265                                               | 1         | 0.84%   |
| Intel Wireless 3160                                               | 1         | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.84%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.84%   |
| Intel Ethernet controller                                         | 1         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 71.67%  |
| Qualcomm Atheros      | 5         | 8.33%   |
| Realtek Semiconductor | 4         | 6.67%   |
| MediaTek              | 4         | 6.67%   |
| Ralink                | 1         | 1.67%   |
| Dell                  | 1         | 1.67%   |
| Broadcom Limited      | 1         | 1.67%   |
| Broadcom              | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                                                         | 6         | 10%     |
| Intel Wireless 7260                                                                                                | 5         | 8.33%   |
| Intel Wi-Fi 6 AX201                                                                                                | 5         | 8.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 5         | 8.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 4         | 6.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 5%      |
| Intel Wireless 8260                                                                                                | 3         | 5%      |
| Intel Wi-Fi 6 AX200                                                                                                | 3         | 5%      |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 3         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 2         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 3.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 3.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                        | 1         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 1.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 1.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 1.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                      | 1         | 1.67%   |
| Intel Wireless 7265                                                                                                | 1         | 1.67%   |
| Intel Wireless 3160                                                                                                | 1         | 1.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                             | 1         | 1.67%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 1         | 1.67%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 1.67%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 1.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                                         | 1         | 1.67%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                                    | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 48.28%  |
| Intel                 | 22        | 37.93%  |
| Lenovo                | 2         | 3.45%   |
| ASIX Electronics      | 2         | 3.45%   |
| Qualcomm Atheros      | 1         | 1.72%   |
| JMicron Technology    | 1         | 1.72%   |
| D-Link                | 1         | 1.72%   |
| Broadcom              | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 28.81%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 13.56%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 6.78%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 5.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.39%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 3.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.39%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 3.39%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.69%   |
| Lenovo USB-C to LAN                                               | 1         | 1.69%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.69%   |
| Intel Ethernet controller                                         | 1         | 1.69%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.69%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.69%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.69%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 1.69%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 54.13%  |
| Ethernet | 50        | 45.87%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 65.71%  |
| Ethernet | 24        | 34.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 42        | 70%     |
| 1     | 17        | 28.33%  |
| 3     | 1         | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 75%     |
| Yes  | 15        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 67.31%  |
| Qualcomm Atheros Communications | 4         | 7.69%   |
| Realtek Semiconductor           | 3         | 5.77%   |
| Foxconn / Hon Hai               | 3         | 5.77%   |
| Broadcom                        | 3         | 5.77%   |
| Ralink                          | 1         | 1.92%   |
| IMC Networks                    | 1         | 1.92%   |
| Hewlett-Packard                 | 1         | 1.92%   |
| Dell                            | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 15        | 28.85%  |
| Intel AX201 Bluetooth                              | 10        | 19.23%  |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 5.77%   |
| Intel Bluetooth Device                             | 3         | 5.77%   |
| Intel AX200 Bluetooth                              | 3         | 5.77%   |
| Realtek Bluetooth Radio                            | 2         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 3.85%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 1.92%   |
| Ralink RT3290 Bluetooth                            | 1         | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.92%   |
| Intel AX210 Bluetooth                              | 1         | 1.92%   |
| IMC Networks Wireless_Device                       | 1         | 1.92%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.92%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth        | 1         | 1.92%   |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 1.92%   |
| Broadcom HP Portable Bumble Bee                    | 1         | 1.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 1.92%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 53.26%  |
| Nvidia                | 17        | 18.48%  |
| AMD                   | 10        | 10.87%  |
| Logitech              | 3         | 3.26%   |
| GN Netcom             | 2         | 2.17%   |
| Conexant Systems      | 2         | 2.17%   |
| Texas Instruments     | 1         | 1.09%   |
| Saitek                | 1         | 1.09%   |
| Realtek Semiconductor | 1         | 1.09%   |
| Lenovo                | 1         | 1.09%   |
| Huawei Technologies   | 1         | 1.09%   |
| Hewlett-Packard       | 1         | 1.09%   |
| Creative Technology   | 1         | 1.09%   |
| C-Media Electronics   | 1         | 1.09%   |
| ASUSTek Computer      | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 6.54%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 6.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 6.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 6.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 5.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.8%    |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 2.8%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 2.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.87%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.87%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.87%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.93%   |
| Saitek Cyborg F.R.E.Q.5 Gaming Headset                                     | 1         | 0.93%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia Audio device                                                        | 1         | 0.93%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.93%   |
| Logitech Stereo H650e                                                      | 1         | 0.93%   |
| Logitech Headset H390                                                      | 1         | 0.93%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.93%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 28.95%  |
| SK hynix            | 10        | 26.32%  |
| Micron Technology   | 4         | 10.53%  |
| Crucial             | 4         | 10.53%  |
| Kingston            | 2         | 5.26%   |
| Smart               | 1         | 2.63%   |
| Ramaxel Technology  | 1         | 2.63%   |
| Magnum Tech         | 1         | 2.63%   |
| Lexar Co Limited    | 1         | 2.63%   |
| Lexar               | 1         | 2.63%   |
| G.Skill             | 1         | 2.63%   |
| A-DATA Technology   | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 5.26%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                   | 1         | 2.63%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1         | 2.63%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 1         | 2.63%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.63%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 2.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 2.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 2.63%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 2.63%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 2.63%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                   | 1         | 2.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 1         | 2.63%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s    | 1         | 2.63%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 2.63%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 2.63%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s   | 1         | 2.63%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s   | 1         | 2.63%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s      | 1         | 2.63%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s        | 1         | 2.63%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s         | 1         | 2.63%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s            | 1         | 2.63%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s          | 1         | 2.63%   |
| Lexar Co Limited RAM LD4AS008G-2666SC 8GB SODIMM DDR4 2667MT/s | 1         | 2.63%   |
| Kingston RAM 9905703-006.A00G 16GB SODIMM DDR4 2400MT/s        | 1         | 2.63%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 2.63%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s           | 1         | 2.63%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s      | 1         | 2.63%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s     | 1         | 2.63%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 1         | 2.63%   |
| Crucial RAM BLS16G4S240FSD.16FAD 16GB SODIMM DDR4 2400MT/s     | 1         | 2.63%   |
| A-DATA RAM AO1P32NC8T1-BZ4SHD 8GB SODIMM DDR4 3200MT/s         | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 19        | 55.88%  |
| DDR3   | 9         | 26.47%  |
| DDR5   | 3         | 8.82%   |
| LPDDR5 | 1         | 2.94%   |
| LPDDR4 | 1         | 2.94%   |
| LPDDR3 | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 88.57%  |
| Row Of Chips | 4         | 11.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 20        | 55.56%  |
| 16384 | 8         | 22.22%  |
| 4096  | 6         | 16.67%  |
| 32768 | 2         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 10        | 28.57%  |
| 2667  | 8         | 22.86%  |
| 1600  | 7         | 20%     |
| 4800  | 3         | 8.57%   |
| 2400  | 2         | 5.71%   |
| 2133  | 2         | 5.71%   |
| 6400  | 1         | 2.86%   |
| 4266  | 1         | 2.86%   |
| 1066  | 1         | 2.86%   |

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
| Chicony Electronics                    | 15        | 27.78%  |
| IMC Networks                           | 9         | 16.67%  |
| Microdia                               | 5         | 9.26%   |
| Syntek                                 | 3         | 5.56%   |
| Sunplus Innovation Technology          | 3         | 5.56%   |
| Realtek Semiconductor                  | 3         | 5.56%   |
| Luxvisions Innotech Limited            | 3         | 5.56%   |
| Quanta                                 | 2         | 3.7%    |
| Logitech                               | 2         | 3.7%    |
| Suyin                                  | 1         | 1.85%   |
| Sonix Technology                       | 1         | 1.85%   |
| Lite-On Technology                     | 1         | 1.85%   |
| Lenovo                                 | 1         | 1.85%   |
| Intel                                  | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.85%   |
| Bison Electronics                      | 1         | 1.85%   |
| Apple                                  | 1         | 1.85%   |
| Acer                                   | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 7         | 12.73%  |
| Microdia Integrated_Webcam_HD                                              | 4         | 7.27%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 5.45%   |
| IMC Networks Integrated Camera                                             | 3         | 5.45%   |
| Chicony HP HD Camera                                                       | 3         | 5.45%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 3.64%   |
| Chicony HD WebCam                                                          | 2         | 3.64%   |
| Syntek Integrated Camera                                                   | 1         | 1.82%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 1.82%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.82%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.82%   |
| Sunplus 1080P Webcam                                                       | 1         | 1.82%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 1.82%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 1.82%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.82%   |
| Realtek EasyCamera                                                         | 1         | 1.82%   |
| Quanta HP Webcam                                                           | 1         | 1.82%   |
| Quanta HP 5MP Camera                                                       | 1         | 1.82%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.82%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 1         | 1.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.82%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 1.82%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.82%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 1.82%   |
| Lite-On HP HD Webcam                                                       | 1         | 1.82%   |
| Lenovo UVC Camera                                                          | 1         | 1.82%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 1.82%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 1.82%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.82%   |
| IMC Networks HD Camera                                                     | 1         | 1.82%   |
| Chicony USB2.0 FHD UVC WebCam                                              | 1         | 1.82%   |
| Chicony thinkpad t430s camera                                              | 1         | 1.82%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.82%   |
| Chicony HP HD Webcam                                                       | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.82%   |
| Bison Integrated Camera                                                    | 1         | 1.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 1         | 1.82%   |
| Acer Integrated RGB Camera                                                 | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 38.89%  |
| Synaptics                  | 6         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| LighTuning Technology      | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Synaptics UWP WBDI Device                                                  | 1         | 5.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 5.56%   |
| Elan ELAN:Fingerprint                                                      | 1         | 5.56%   |
| AuthenTec AES2810                                                          | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| O2 Micro    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 20%     |
| Broadcom 58200                                                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 30        | 50%     |
| 1     | 24        | 40%     |
| 2     | 5         | 8.33%   |
| 3     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 48.65%  |
| Graphics card         | 7         | 18.92%  |
| Net/ethernet          | 3         | 8.11%   |
| Chipcard              | 3         | 8.11%   |
| Net/wireless          | 2         | 5.41%   |
| Multimedia controller | 2         | 5.41%   |
| Card reader           | 1         | 2.7%    |
| Bluetooth             | 1         | 2.7%    |

