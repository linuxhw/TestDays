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

Total: 62

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 9.1 | 16        | 33.33%  |
| Rocky Linux 8.5 | 11        | 22.92%  |
| Rocky Linux 9.0 | 9         | 18.75%  |
| Rocky Linux 8.4 | 8         | 16.67%  |
| Rocky Linux 8.7 | 2         | 4.17%   |
| Rocky Linux 8.6 | 1         | 2.08%   |
| Rocky Linux 8.3 | 1         | 2.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 48        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 18.37%  |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 8.16%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 8.16%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 6.12%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 4.08%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 2         | 4.08%   |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 4.08%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 4.08%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 4.08%   |
| 4.18.0-305.el8.x86_64            | 2         | 4.08%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 4.08%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 4.08%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 4.08%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 2.04%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 2.04%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 1         | 2.04%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1         | 2.04%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 2.04%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 1         | 2.04%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 2.04%   |
| 5.10.89-1.el8.x86_64             | 1         | 2.04%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 2.04%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1         | 2.04%   |
| 4.18.0-240.22.1.el8.x86_64       | 1         | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 25        | 52.08%  |
| 4.18.0  | 20        | 41.67%  |
| 5.4.157 | 1         | 2.08%   |
| 5.16.15 | 1         | 2.08%   |
| 5.10.89 | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 25        | 52.08%  |
| 4.18    | 20        | 41.67%  |
| 5.4     | 1         | 2.08%   |
| 5.16    | 1         | 2.08%   |
| 5.10    | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 48        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 37        | 77.08%  |
| MATE          | 3         | 6.25%   |
| KDE5          | 3         | 6.25%   |
| XFCE          | 2         | 4.17%   |
| X-Cinnamon    | 1         | 2.08%   |
| GNOME Classic | 1         | 2.08%   |
| Unknown       | 1         | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 31        | 64.58%  |
| X11     | 16        | 33.33%  |
| Tty     | 1         | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 50%     |
| GDM     | 18        | 37.5%   |
| SDDM    | 4         | 8.33%   |
| LightDM | 2         | 4.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 35        | 72.92%  |
| ru_RU | 2         | 4.17%   |
| en_ZA | 2         | 4.17%   |
| en_CA | 2         | 4.17%   |
| de_DE | 2         | 4.17%   |
| pt_BR | 1         | 2.08%   |
| it_IT | 1         | 2.08%   |
| fr_FR | 1         | 2.08%   |
| en_IE | 1         | 2.08%   |
| C     | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 38        | 79.17%  |
| BIOS | 10        | 20.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 39        | 81.25%  |
| Ext4 | 8         | 16.67%  |
| Ext3 | 1         | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 50%     |
| GPT     | 22        | 45.83%  |
| MBR     | 2         | 4.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 89.58%  |
| Yes       | 5         | 10.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 79.17%  |
| Yes       | 10        | 20.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 18        | 37.5%   |
| Hewlett-Packard  | 10        | 20.83%  |
| Dell             | 10        | 20.83%  |
| ASUSTek Computer | 4         | 8.33%   |
| Toshiba          | 2         | 4.17%   |
| Positivo         | 1         | 2.08%   |
| HUAWEI           | 1         | 2.08%   |
| BANGHO           | 1         | 2.08%   |
| Acer             | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                    | 1         | 2.08%   |
| Toshiba Satellite E45-B                | 1         | 2.08%   |
| Positivo Mobile                        | 1         | 2.08%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 2.08%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 2.08%   |
| Lenovo ThinkPad W500 406132G           | 1         | 2.08%   |
| Lenovo ThinkPad T480 20L6S8B500        | 1         | 2.08%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 2.08%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS  | 1         | 2.08%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 2.08%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW    | 1         | 2.08%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK    | 1         | 2.08%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 2.08%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 2.08%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 2.08%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 2.08%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 2.08%   |
| Lenovo IdeaPad S210 Touch 20257        | 1         | 2.08%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 2.08%   |
| Lenovo IdeaPad 500S-14ISK 80Q3         | 1         | 2.08%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 1         | 2.08%   |
| HUAWEI KLVD-WXX9                       | 1         | 2.08%   |
| HP ZBook 15u G6                        | 1         | 2.08%   |
| HP ZBook 15 G3                         | 1         | 2.08%   |
| HP ZBook 15 G2                         | 1         | 2.08%   |
| HP ProBook 640 G3                      | 1         | 2.08%   |
| HP Pavilion g6                         | 1         | 2.08%   |
| HP Laptop 17-ca1xxx                    | 1         | 2.08%   |
| HP Laptop 15-dy2xxx                    | 1         | 2.08%   |
| HP EliteBook 840 G7 Notebook PC        | 1         | 2.08%   |
| HP EliteBook 840 G5                    | 1         | 2.08%   |
| HP EliteBook 2560p                     | 1         | 2.08%   |
| Dell XPS 17 9720                       | 1         | 2.08%   |
| Dell XPS 15 7590                       | 1         | 2.08%   |
| Dell Vostro 3500                       | 1         | 2.08%   |
| Dell Precision M6800                   | 1         | 2.08%   |
| Dell Latitude 5500                     | 1         | 2.08%   |
| Dell Latitude 5430                     | 1         | 2.08%   |
| Dell Latitude 5420                     | 1         | 2.08%   |
| Dell Latitude 3420                     | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 9         | 18.75%  |
| Lenovo IdeaPad    | 7         | 14.58%  |
| Dell Latitude     | 4         | 8.33%   |
| HP ZBook          | 3         | 6.25%   |
| HP EliteBook      | 3         | 6.25%   |
| Lenovo Legion     | 2         | 4.17%   |
| HP Laptop         | 2         | 4.17%   |
| Dell XPS          | 2         | 4.17%   |
| Dell Inspiron     | 2         | 4.17%   |
| ASUS ASUS         | 2         | 4.17%   |
| Toshiba TECRA     | 1         | 2.08%   |
| Toshiba Satellite | 1         | 2.08%   |
| Positivo Mobile   | 1         | 2.08%   |
| HUAWEI KLVD-WXX9  | 1         | 2.08%   |
| HP ProBook        | 1         | 2.08%   |
| HP Pavilion       | 1         | 2.08%   |
| Dell Vostro       | 1         | 2.08%   |
| Dell Precision    | 1         | 2.08%   |
| BANGHO BES        | 1         | 2.08%   |
| ASUS VivoBook     | 1         | 2.08%   |
| ASUS ROG          | 1         | 2.08%   |
| Acer Aspire       | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 16.67%  |
| 2021 | 7         | 14.58%  |
| 2019 | 6         | 12.5%   |
| 2022 | 4         | 8.33%   |
| 2018 | 4         | 8.33%   |
| 2014 | 4         | 8.33%   |
| 2013 | 3         | 6.25%   |
| 2011 | 3         | 6.25%   |
| 2016 | 2         | 4.17%   |
| 2015 | 2         | 4.17%   |
| 2010 | 2         | 4.17%   |
| 2017 | 1         | 2.08%   |
| 2012 | 1         | 2.08%   |
| 2009 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 48        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 39        | 81.25%  |
| Enabled  | 9         | 18.75%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 18        | 37.5%   |
| 4.01-8.0    | 12        | 25%     |
| 32.01-64.0  | 8         | 16.67%  |
| 16.01-24.0  | 6         | 12.5%   |
| 3.01-4.0    | 2         | 4.17%   |
| 24.01-32.0  | 1         | 2.08%   |
| 64.01-256.0 | 1         | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 30%     |
| 2.01-3.0   | 13        | 26%     |
| 3.01-4.0   | 11        | 22%     |
| 8.01-16.0  | 5         | 10%     |
| 1.01-2.0   | 4         | 8%      |
| 16.01-24.0 | 1         | 2%      |
| 0.51-1.0   | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 77.08%  |
| 2      | 7         | 14.58%  |
| 3      | 3         | 6.25%   |
| 4      | 1         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 81.25%  |
| Yes       | 9         | 18.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 79.59%  |
| No        | 10        | 20.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 87.5%   |
| No        | 6         | 12.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 27.08%  |
| South Africa | 2         | 4.17%   |
| Russia       | 2         | 4.17%   |
| Poland       | 2         | 4.17%   |
| Italy        | 2         | 4.17%   |
| Germany      | 2         | 4.17%   |
| Czechia      | 2         | 4.17%   |
| Canada       | 2         | 4.17%   |
| Brazil       | 2         | 4.17%   |
| Belgium      | 2         | 4.17%   |
| Uzbekistan   | 1         | 2.08%   |
| UAE          | 1         | 2.08%   |
| Turkey       | 1         | 2.08%   |
| Sweden       | 1         | 2.08%   |
| Slovakia     | 1         | 2.08%   |
| Saudi Arabia | 1         | 2.08%   |
| Pakistan     | 1         | 2.08%   |
| Netherlands  | 1         | 2.08%   |
| Malaysia     | 1         | 2.08%   |
| Kazakhstan   | 1         | 2.08%   |
| Ireland      | 1         | 2.08%   |
| Hungary      | 1         | 2.08%   |
| France       | 1         | 2.08%   |
| Croatia      | 1         | 2.08%   |
| China        | 1         | 2.08%   |
| Austria      | 1         | 2.08%   |
| Argentina    | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Žilina                | 1         | 2.08%   |
| Xi'an                  | 1         | 2.08%   |
| Vienna                 | 1         | 2.08%   |
| Torrington             | 1         | 2.08%   |
| Syracuse               | 1         | 2.08%   |
| Split                  | 1         | 2.08%   |
| Smolensk               | 1         | 2.08%   |
| Senigallia             | 1         | 2.08%   |
| Scarborough            | 1         | 2.08%   |
| San Miguel de Tucumán | 1         | 2.08%   |
| Riyadh                 | 1         | 2.08%   |
| Rawalpindi             | 1         | 2.08%   |
| Prague                 | 1         | 2.08%   |
| Philadelphia           | 1         | 2.08%   |
| Parksville             | 1         | 2.08%   |
| Ottignies              | 1         | 2.08%   |
| Örebro                | 1         | 2.08%   |
| Oakley                 | 1         | 2.08%   |
| Nur-Sultan             | 1         | 2.08%   |
| Mugla                  | 1         | 2.08%   |
| Mossel Bay             | 1         | 2.08%   |
| Moscow                 | 1         | 2.08%   |
| Montreal               | 1         | 2.08%   |
| Melun                  | 1         | 2.08%   |
| Kutno                  | 1         | 2.08%   |
| Krakow                 | 1         | 2.08%   |
| Kansas City            | 1         | 2.08%   |
| Johor Bahru            | 1         | 2.08%   |
| Jaú                   | 1         | 2.08%   |
| Houston                | 1         | 2.08%   |
| Glin                   | 1         | 2.08%   |
| Forest                 | 1         | 2.08%   |
| Fairbanks              | 1         | 2.08%   |
| Enschede               | 1         | 2.08%   |
| Elizabethtown          | 1         | 2.08%   |
| Dreieich               | 1         | 2.08%   |
| Centurion              | 1         | 2.08%   |
| Castelverde            | 1         | 2.08%   |
| Bukhara                | 1         | 2.08%   |
| Budapest               | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 17        | 19     | 26.56%  |
| WDC                     | 6         | 6      | 9.38%   |
| Kingston                | 5         | 5      | 7.81%   |
| Toshiba                 | 4         | 5      | 6.25%   |
| SanDisk                 | 4         | 6      | 6.25%   |
| SK hynix                | 3         | 5      | 4.69%   |
| Unknown                 | 2         | 2      | 3.13%   |
| Seagate                 | 2         | 2      | 3.13%   |
| Lexar                   | 2         | 2      | 3.13%   |
| Intel                   | 2         | 2      | 3.13%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.56%   |
| UMIS                    | 1         | 1      | 1.56%   |
| StoreJet                | 1         | 1      | 1.56%   |
| Phison                  | 1         | 1      | 1.56%   |
| Micron Technology       | 1         | 1      | 1.56%   |
| LITEONIT                | 1         | 1      | 1.56%   |
| LITEON                  | 1         | 1      | 1.56%   |
| JMicron Technology      | 1         | 1      | 1.56%   |
| INDMEM                  | 1         | 1      | 1.56%   |
| HS-SSD-C100             | 1         | 1      | 1.56%   |
| Hitachi                 | 1         | 1      | 1.56%   |
| Fujitsu                 | 1         | 1      | 1.56%   |
| Dogfish                 | 1         | 1      | 1.56%   |
| Crucial                 | 1         | 1      | 1.56%   |
| AGI                     | 1         | 1      | 1.56%   |
| ADATA Technology        | 1         | 1      | 1.56%   |
| A-DATA Technology       | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 870 EVO 1TB                             | 2         | 2.94%   |
| Lexar 512GB SSD                                     | 2         | 2.94%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 1.47%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 1.47%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 1.47%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 1.47%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1.47%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.47%   |
| Unknown SD/MMC/MS PRO 64GB                          | 1         | 1.47%   |
| Unknown MMC Card  64GB                              | 1         | 1.47%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1         | 1.47%   |
| UMIS RPFTJ128PDD2EWX 128GB                          | 1         | 1.47%   |
| Toshiba THNSNJ512GACU 512GB SSD                     | 1         | 1.47%   |
| Toshiba THNSNJ128G8NU 128GB SSD                     | 1         | 1.47%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 1.47%   |
| Toshiba KXG6AZNV1T02 1TB                            | 1         | 1.47%   |
| Toshiba KXG6APNV2T04 2TB                            | 1         | 1.47%   |
| StoreJet Disk 1TB                                   | 1         | 1.47%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB           | 1         | 1.47%   |
| SK hynix SHPP41-2000GM 2TB                          | 1         | 1.47%   |
| SK hynix NVMe SSD Drive 512GB                       | 1         | 1.47%   |
| SK hynix BC511 NVMe 512GB                           | 1         | 1.47%   |
| Seagate ST9320325AS 320GB                           | 1         | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.47%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1024GB        | 1         | 1.47%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB      | 1         | 1.47%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1.47%   |
| SanDisk SD5SG2256G1052E 256GB SSD                   | 1         | 1.47%   |
| SanDisk Extreme 55AE 2TB SSD                        | 1         | 1.47%   |
| Samsung SSD 970 EVO 500GB                           | 1         | 1.47%   |
| Samsung SSD 870 QVO 2TB                             | 1         | 1.47%   |
| Samsung SSD 860 QVO 4TB                             | 1         | 1.47%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 1.47%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 1         | 1.47%   |
| Samsung PM9A1 NVMe SED 512GB                        | 1         | 1.47%   |
| Samsung PM991a NVMe 512GB                           | 1         | 1.47%   |
| Samsung NVMe SSD Drive 512GB                        | 1         | 1.47%   |
| Samsung NVMe SSD Drive 1024GB                       | 1         | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 1         | 1.47%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 1         | 1.47%   |

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
| Samsung Electronics | 7         | 8      | 31.82%  |
| Kingston            | 3         | 3      | 13.64%  |
| WDC                 | 2         | 2      | 9.09%   |
| Toshiba             | 2         | 2      | 9.09%   |
| SanDisk             | 2         | 3      | 9.09%   |
| LITEONIT            | 1         | 1      | 4.55%   |
| LITEON              | 1         | 1      | 4.55%   |
| Lexar               | 1         | 1      | 4.55%   |
| INDMEM              | 1         | 1      | 4.55%   |
| Dogfish             | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 27        | 33     | 48.21%  |
| SSD     | 17        | 24     | 30.36%  |
| HDD     | 8         | 10     | 14.29%  |
| Unknown | 3         | 3      | 5.36%   |
| MMC     | 1         | 1      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 27        | 33     | 48.21%  |
| SATA | 23        | 32     | 41.07%  |
| SAS  | 5         | 5      | 8.93%   |
| MMC  | 1         | 1      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 16     | 48.15%  |
| 0.51-1.0   | 10        | 13     | 37.04%  |
| 1.01-2.0   | 3         | 3      | 11.11%  |
| 3.01-4.0   | 1         | 2      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 19        | 39.58%  |
| 101-250        | 12        | 25%     |
| 501-1000       | 6         | 12.5%   |
| 1001-2000      | 4         | 8.33%   |
| 2001-3000      | 3         | 6.25%   |
| 51-100         | 3         | 6.25%   |
| More than 3000 | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 33.33%  |
| 21-50     | 12        | 25%     |
| 101-250   | 7         | 14.58%  |
| 51-100    | 6         | 12.5%   |
| 251-500   | 3         | 6.25%   |
| 1001-2000 | 2         | 4.17%   |
| 501-1000  | 2         | 4.17%   |

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
| Works    | 26        | 35     | 50.98%  |
| Detected | 25        | 36     | 49.02%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 49.15%  |
| Samsung Electronics          | 10        | 16.95%  |
| AMD                          | 5         | 8.47%   |
| SK hynix                     | 3         | 5.08%   |
| Toshiba America Info Systems | 2         | 3.39%   |
| SanDisk                      | 2         | 3.39%   |
| Kingston Technology Company  | 2         | 3.39%   |
| Union Memory (Shenzhen)      | 1         | 1.69%   |
| Shenzhen Longsys Electronics | 1         | 1.69%   |
| Realtek Semiconductor        | 1         | 1.69%   |
| Phison Electronics           | 1         | 1.69%   |
| Micron Technology            | 1         | 1.69%   |
| ADATA Technology             | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 7.81%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 7.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 6.25%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 4.69%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 4.69%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 4.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 3.13%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 2         | 3.13%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.56%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                                       | 1         | 1.56%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.56%   |
| SK hynix BC511                                                                         | 1         | 1.56%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                            | 1         | 1.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.56%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 1.56%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 1.56%   |
| Realtek NVMe Controller                                                                | 1         | 1.56%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.56%   |
| Micron NVMe Storage Controller                                                         | 1         | 1.56%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.56%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.56%   |
| Intel SSD 660P Series                                                                  | 1         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.56%   |
| Intel Non-Volatile memory controller                                                   | 1         | 1.56%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 1.56%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 27        | 44.26%  |
| SATA | 25        | 40.98%  |
| IDE  | 5         | 8.2%    |
| RAID | 4         | 6.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 81.25%  |
| AMD    | 9         | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 4         | 8.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 4.17%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 2         | 4.17%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz   | 1         | 2.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 1         | 2.08%   |
| Intel Core i7-8665U CPU @ 1.90GHz          | 1         | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 1         | 2.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz          | 1         | 2.08%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 2.08%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz         | 1         | 2.08%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz         | 1         | 2.08%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz         | 1         | 2.08%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz         | 1         | 2.08%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 2.08%   |
| Intel Core i7-10875H CPU @ 2.30GHz         | 1         | 2.08%   |
| Intel Core i7-10610U CPU @ 1.80GHz         | 1         | 2.08%   |
| Intel Core i5-8365U CPU @ 1.60GHz          | 1         | 2.08%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 1         | 2.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 2.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 1         | 2.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 1         | 2.08%   |
| Intel Core i5-4200M CPU @ 2.50GHz          | 1         | 2.08%   |
| Intel Core i5-3427U CPU @ 1.80GHz          | 1         | 2.08%   |
| Intel Core i5-2540M CPU @ 2.60GHz          | 1         | 2.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 1         | 2.08%   |
| Intel Core i3 CPU M 380 @ 2.53GHz          | 1         | 2.08%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz       | 1         | 2.08%   |
| Intel Celeron CPU 1037U @ 1.80GHz          | 1         | 2.08%   |
| Intel 12th Gen Core i7-12700H              | 1         | 2.08%   |
| Intel 12th Gen Core i7-1260P               | 1         | 2.08%   |
| Intel 12th Gen Core i5-1245U               | 1         | 2.08%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 1         | 2.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 1         | 2.08%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz    | 1         | 2.08%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 1         | 2.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 1         | 2.08%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics | 1         | 2.08%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 1         | 2.08%   |
| AMD Ryzen 5 5600H with Radeon Graphics     | 1         | 2.08%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 16        | 33.33%  |
| Other                | 11        | 22.92%  |
| Intel Core i5        | 9         | 18.75%  |
| AMD Ryzen 5          | 4         | 8.33%   |
| AMD Ryzen 7          | 2         | 4.17%   |
| Intel Pentium Silver | 1         | 2.08%   |
| Intel Core i3        | 1         | 2.08%   |
| Intel Core 2 Duo     | 1         | 2.08%   |
| Intel Celeron        | 1         | 2.08%   |
| AMD Ryzen 5 PRO      | 1         | 2.08%   |
| AMD A8               | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 23        | 47.92%  |
| 2      | 12        | 25%     |
| 6      | 6         | 12.5%   |
| 8      | 3         | 6.25%   |
| 14     | 1         | 2.08%   |
| 12     | 1         | 2.08%   |
| 10     | 1         | 2.08%   |
| 1      | 1         | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 42        | 87.5%   |
| 1      | 6         | 12.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 7         | 14.58%  |
| 0x306c3    | 7         | 14.58%  |
| 0x806ec    | 4         | 8.33%   |
| 0xa0652    | 3         | 6.25%   |
| 0x906a3    | 2         | 4.17%   |
| 0x806ea    | 2         | 4.17%   |
| 0x506e3    | 2         | 4.17%   |
| 0x306a9    | 2         | 4.17%   |
| 0x206a7    | 2         | 4.17%   |
| 0x0a50000c | 2         | 4.17%   |
| 0x08600104 | 2         | 4.17%   |
| 0x906ea    | 1         | 2.08%   |
| 0x906a4    | 1         | 2.08%   |
| 0x806e9    | 1         | 2.08%   |
| 0x706a1    | 1         | 2.08%   |
| 0x406e3    | 1         | 2.08%   |
| 0x40651    | 1         | 2.08%   |
| 0x20655    | 1         | 2.08%   |
| 0x10676    | 1         | 2.08%   |
| 0x0a50000d | 1         | 2.08%   |
| 0x0a404101 | 1         | 2.08%   |
| 0x08108102 | 1         | 2.08%   |
| 0x06006705 | 1         | 2.08%   |
| 0x06001116 | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 8         | 16.67%  |
| Haswell          | 8         | 16.67%  |
| TigerLake        | 7         | 14.58%  |
| Zen 3            | 3         | 6.25%   |
| Skylake          | 3         | 6.25%   |
| CometLake        | 3         | 6.25%   |
| Alderlake Hybrid | 3         | 6.25%   |
| Zen 2            | 2         | 4.17%   |
| SandyBridge      | 2         | 4.17%   |
| IvyBridge        | 2         | 4.17%   |
| Zen+             | 1         | 2.08%   |
| Westmere         | 1         | 2.08%   |
| Piledriver       | 1         | 2.08%   |
| Penryn           | 1         | 2.08%   |
| Goldmont plus    | 1         | 2.08%   |
| Excavator        | 1         | 2.08%   |
| Unknown          | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 52.94%  |
| Nvidia | 22        | 32.35%  |
| AMD    | 10        | 14.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 10.14%  |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 7.25%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 4.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 4.35%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 2         | 2.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 2.9%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.9%    |
| Intel UHD Graphics 620                                                    | 2         | 2.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 2.9%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 2.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.9%    |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.45%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.45%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.45%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.45%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.45%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 1.45%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 1.45%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.45%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.45%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.45%   |
| Intel HD Graphics 620                                                     | 1         | 1.45%   |
| Intel HD Graphics 530                                                     | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.45%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.45%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 1         | 1.45%   |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 1.45%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 1.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.45%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 39.58%  |
| Intel + Nvidia | 15        | 31.25%  |
| 1 x Nvidia     | 4         | 8.33%   |
| 1 x AMD        | 4         | 8.33%   |
| AMD + Nvidia   | 3         | 6.25%   |
| Intel + AMD    | 2         | 4.17%   |
| 2 x AMD        | 1         | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 38        | 79.17%  |
| Proprietary | 9         | 18.75%  |
| Unknown     | 1         | 2.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 55.1%   |
| 3.01-4.0   | 8         | 16.33%  |
| 1.01-2.0   | 5         | 10.2%   |
| 0.01-0.5   | 5         | 10.2%   |
| 5.01-6.0   | 2         | 4.08%   |
| 7.01-8.0   | 1         | 2.04%   |
| 0.51-1.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 12        | 18.18%  |
| BOE                 | 10        | 15.15%  |
| AU Optronics        | 10        | 15.15%  |
| Samsung Electronics | 6         | 9.09%   |
| Dell                | 6         | 9.09%   |
| Chimei Innolux      | 5         | 7.58%   |
| Goldstar            | 4         | 6.06%   |
| Sharp               | 2         | 3.03%   |
| Philips             | 2         | 3.03%   |
| InfoVision          | 2         | 3.03%   |
| AOC                 | 2         | 3.03%   |
| PANDA               | 1         | 1.52%   |
| Panasonic           | 1         | 1.52%   |
| Lenovo              | 1         | 1.52%   |
| Gigabyte Technology | 1         | 1.52%   |
| BenQ                | 1         | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 2.94%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.47%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.47%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.47%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 1.47%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.47%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 1.47%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.47%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 1         | 1.47%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.47%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 1         | 1.47%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 1.47%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.47%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.47%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.47%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.47%   |
| Gigabyte Technology G27QC A GBT2716 2560x1440 597x336mm 27.0-inch     | 1         | 1.47%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 1.47%   |
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                   | 1         | 1.47%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.47%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.47%   |
| Dell S2415H DELA0B5 1920x1080 527x296mm 23.8-inch                     | 1         | 1.47%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 50.85%  |
| 1366x768 (WXGA)    | 8         | 13.56%  |
| 3840x2160 (4K)     | 3         | 5.08%   |
| 2560x1440 (QHD)    | 3         | 5.08%   |
| 1600x900 (HD+)     | 3         | 5.08%   |
| 3440x1440          | 2         | 3.39%   |
| 1920x1200 (WUXGA)  | 2         | 3.39%   |
| 1680x1050 (WSXGA+) | 2         | 3.39%   |
| 3840x2400          | 1         | 1.69%   |
| 3840x1080          | 1         | 1.69%   |
| 2560x1080          | 1         | 1.69%   |
| 2240x1400          | 1         | 1.69%   |
| 2160x1440          | 1         | 1.69%   |
| Unknown            | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 24        | 36.92%  |
| 14     | 13        | 20%     |
| 27     | 6         | 9.23%   |
| 17     | 5         | 7.69%   |
| 13     | 5         | 7.69%   |
| 34     | 3         | 4.62%   |
| 24     | 3         | 4.62%   |
| 21     | 3         | 4.62%   |
| 49     | 1         | 1.54%   |
| 23     | 1         | 1.54%   |
| 22     | 1         | 1.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 60%     |
| 501-600     | 9         | 13.85%  |
| 401-500     | 5         | 7.69%   |
| 351-400     | 5         | 7.69%   |
| 701-800     | 3         | 4.62%   |
| 201-300     | 3         | 4.62%   |
| 1001-1500   | 1         | 1.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 80%     |
| 16/10 | 5         | 9.09%   |
| 21/9  | 3         | 5.45%   |
| 3/2   | 2         | 3.64%   |
| 32/9  | 1         | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 37.5%   |
| 81-90          | 17        | 26.56%  |
| 301-350        | 6         | 9.38%   |
| 201-250        | 6         | 9.38%   |
| 121-130        | 5         | 7.81%   |
| 351-500        | 3         | 4.69%   |
| 71-80          | 1         | 1.56%   |
| 151-200        | 1         | 1.56%   |
| 501-1000       | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 49.23%  |
| 101-120       | 15        | 23.08%  |
| 51-100        | 10        | 15.38%  |
| 161-240       | 5         | 7.69%   |
| More than 240 | 3         | 4.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 31        | 64.58%  |
| 2     | 12        | 25%     |
| 3     | 3         | 6.25%   |
| 4     | 1         | 2.08%   |
| 0     | 1         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 48%     |
| Realtek Semiconductor | 23        | 30.67%  |
| Qualcomm Atheros      | 5         | 6.67%   |
| MediaTek              | 4         | 5.33%   |
| Ralink                | 1         | 1.33%   |
| Lenovo                | 1         | 1.33%   |
| JMicron Technology    | 1         | 1.33%   |
| Dell                  | 1         | 1.33%   |
| D-Link                | 1         | 1.33%   |
| Broadcom Limited      | 1         | 1.33%   |
| Broadcom              | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 13.98%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.45%   |
| Intel Wireless 7260                                               | 5         | 5.38%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 5.38%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 4.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 3.23%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.23%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.15%   |
| Intel Wireless 8260                                               | 2         | 2.15%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.15%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.08%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter          | 1         | 1.08%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.08%   |
| Intel Wireless 7265                                               | 1         | 1.08%   |
| Intel Wireless 3160                                               | 1         | 1.08%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.08%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 71.43%  |
| Qualcomm Atheros      | 4         | 8.16%   |
| MediaTek              | 4         | 8.16%   |
| Realtek Semiconductor | 3         | 6.12%   |
| Ralink                | 1         | 2.04%   |
| Dell                  | 1         | 2.04%   |
| Broadcom Limited      | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                                                | 5         | 10.2%   |
| Intel Wi-Fi 6 AX201                                                                                                | 5         | 10.2%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 3         | 6.12%   |
| Intel Wireless 8265 / 8275                                                                                         | 3         | 6.12%   |
| Intel Wi-Fi 6 AX200                                                                                                | 3         | 6.12%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 3         | 6.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 3         | 6.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 3         | 6.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 4.08%   |
| Intel Wireless 8260                                                                                                | 2         | 4.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 2.04%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 2.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 2.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 1         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 2.04%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter                                                           | 1         | 2.04%   |
| Intel Wireless 7265                                                                                                | 1         | 2.04%   |
| Intel Wireless 3160                                                                                                | 1         | 2.04%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 1         | 2.04%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 2.04%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 2.04%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                                         | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 51.16%  |
| Intel                 | 16        | 37.21%  |
| Qualcomm Atheros      | 1         | 2.33%   |
| Lenovo                | 1         | 2.33%   |
| JMicron Technology    | 1         | 2.33%   |
| D-Link                | 1         | 2.33%   |
| Broadcom              | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 29.55%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 13.64%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 4.55%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.27%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 2.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.27%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.27%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 2.27%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.27%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 2.27%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 55.81%  |
| Ethernet | 38        | 44.19%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 72.22%  |
| Ethernet | 15        | 27.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 68.75%  |
| 1     | 14        | 29.17%  |
| 3     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 72.92%  |
| Yes  | 13        | 27.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 66.67%  |
| Qualcomm Atheros Communications | 4         | 9.52%   |
| Foxconn / Hon Hai               | 3         | 7.14%   |
| Realtek Semiconductor           | 2         | 4.76%   |
| Ralink                          | 1         | 2.38%   |
| IMC Networks                    | 1         | 2.38%   |
| Hewlett-Packard                 | 1         | 2.38%   |
| Dell                            | 1         | 2.38%   |
| Broadcom                        | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 11        | 26.19%  |
| Intel AX201 Bluetooth                              | 9         | 21.43%  |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 7.14%   |
| Intel AX200 Bluetooth                              | 3         | 7.14%   |
| Foxconn / Hon Hai Wireless_Device                  | 3         | 7.14%   |
| Intel Bluetooth Device                             | 2         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 2.38%   |
| Realtek Bluetooth Radio                            | 1         | 2.38%   |
| Ralink RT3290 Bluetooth                            | 1         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 2.38%   |
| IMC Networks Wireless_Device                       | 1         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 2.38%   |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 2.38%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 39        | 52.7%   |
| Nvidia              | 14        | 18.92%  |
| AMD                 | 9         | 12.16%  |
| Logitech            | 3         | 4.05%   |
| GN Netcom           | 2         | 2.7%    |
| Conexant Systems    | 2         | 2.7%    |
| Saitek              | 1         | 1.35%   |
| Huawei Technologies | 1         | 1.35%   |
| Hewlett-Packard     | 1         | 1.35%   |
| Creative Technology | 1         | 1.35%   |
| C-Media Electronics | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 8.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 8.05%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 8.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 5.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 4.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 4.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.45%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 3.45%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 3.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 3.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 3.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.3%    |
| Saitek Cyborg F.R.E.Q.5 Gaming Headset                                     | 1         | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.15%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.15%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.15%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.15%   |
| Logitech Stereo H650e                                                      | 1         | 1.15%   |
| Logitech Headset H390                                                      | 1         | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.15%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.15%   |
| Huawei Technologies MateView GT                                            | 1         | 1.15%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.15%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.15%   |
| GN Netcom Jabra Evolve 65                                                  | 1         | 1.15%   |
| Creative Technology Sound Blaster Play! 3                                  | 1         | 1.15%   |
| Conexant Systems HP Dock Audio                                             | 1         | 1.15%   |
| Conexant Systems CONEXANT USB AUDIO                                        | 1         | 1.15%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 28.57%  |
| SK hynix            | 7         | 25%     |
| Micron Technology   | 3         | 10.71%  |
| Crucial             | 2         | 7.14%   |
| Smart               | 1         | 3.57%   |
| Ramaxel Technology  | 1         | 3.57%   |
| Magnum Tech         | 1         | 3.57%   |
| Lexar Co Limited    | 1         | 3.57%   |
| Lexar               | 1         | 3.57%   |
| Kingston            | 1         | 3.57%   |
| G.Skill             | 1         | 3.57%   |
| A-DATA Technology   | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 1         | 3.57%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s     | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.57%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 3.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 3.57%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 3.57%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 3.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 1         | 3.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s    | 1         | 3.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 3.57%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 3.57%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s   | 1         | 3.57%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s      | 1         | 3.57%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s        | 1         | 3.57%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s          | 1         | 3.57%   |
| Lexar Co Limited RAM LD4AS008G-2666SC 8GB SODIMM DDR4 2667MT/s | 1         | 3.57%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 3.57%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s           | 1         | 3.57%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s     | 1         | 3.57%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 1         | 3.57%   |
| A-DATA RAM AO1P32NC8T1-BZ4SHD 8GB SODIMM DDR4 3200MT/s         | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 60%     |
| DDR3   | 7         | 28%     |
| LPDDR5 | 1         | 4%      |
| LPDDR4 | 1         | 4%      |
| DDR5   | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 88.46%  |
| Row Of Chips | 3         | 11.54%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 69.23%  |
| 4096  | 4         | 15.38%  |
| 16384 | 3         | 11.54%  |
| 32768 | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 34.62%  |
| 2667  | 7         | 26.92%  |
| 1600  | 6         | 23.08%  |
| 6400  | 1         | 3.85%   |
| 4800  | 1         | 3.85%   |
| 4266  | 1         | 3.85%   |
| 2133  | 1         | 3.85%   |

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
| Chicony Electronics                    | 10        | 22.73%  |
| IMC Networks                           | 8         | 18.18%  |
| Microdia                               | 5         | 11.36%  |
| Syntek                                 | 3         | 6.82%   |
| Sunplus Innovation Technology          | 3         | 6.82%   |
| Realtek Semiconductor                  | 2         | 4.55%   |
| Luxvisions Innotech Limited            | 2         | 4.55%   |
| Logitech                               | 2         | 4.55%   |
| Bison Electronics                      | 2         | 4.55%   |
| Suyin                                  | 1         | 2.27%   |
| Quanta                                 | 1         | 2.27%   |
| Lite-On Technology                     | 1         | 2.27%   |
| Lenovo                                 | 1         | 2.27%   |
| Intel                                  | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |
| Apple                                  | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 6         | 13.64%  |
| Microdia Integrated_Webcam_HD                                              | 4         | 9.09%   |
| IMC Networks Integrated Camera                                             | 3         | 6.82%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 4.55%   |
| Chicony HP HD Camera                                                       | 2         | 4.55%   |
| Syntek Integrated Camera                                                   | 1         | 2.27%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.27%   |
| Sunplus WEMISS CM-A1                                                       | 1         | 2.27%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 2.27%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 2.27%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.27%   |
| Realtek EasyCamera                                                         | 1         | 2.27%   |
| Quanta HP Webcam                                                           | 1         | 2.27%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 2.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.27%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 2.27%   |
| Logitech HD Pro Webcam C920                                                | 1         | 2.27%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 2.27%   |
| Lite-On HP HD Webcam                                                       | 1         | 2.27%   |
| Lenovo UVC Camera                                                          | 1         | 2.27%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 2.27%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 2.27%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.27%   |
| IMC Networks HD Camera                                                     | 1         | 2.27%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.27%   |
| Chicony HD WebCam                                                          | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.27%   |
| Bison Integrated RGB Camera                                                | 1         | 2.27%   |
| Bison Integrated Camera                                                    | 1         | 2.27%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 1         | 2.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 40%     |
| Synaptics                  | 5         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 13.33%  |
| LighTuning Technology      | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 13.33%  |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 13.33%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 6.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 6.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 6.67%   |
| AuthenTec AES2810                                                          | 1         | 6.67%   |

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
| 0     | 22        | 45.83%  |
| 1     | 21        | 43.75%  |
| 2     | 5         | 10.42%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 48.39%  |
| Graphics card         | 6         | 19.35%  |
| Chipcard              | 3         | 9.68%   |
| Net/wireless          | 2         | 6.45%   |
| Net/ethernet          | 2         | 6.45%   |
| Multimedia controller | 1         | 3.23%   |
| Card reader           | 1         | 3.23%   |
| Bluetooth             | 1         | 3.23%   |

