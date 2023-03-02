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

Total: 59

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 9.1 | 14        | 30.43%  |
| Rocky Linux 8.5 | 11        | 23.91%  |
| Rocky Linux 9.0 | 9         | 19.57%  |
| Rocky Linux 8.4 | 8         | 17.39%  |
| Rocky Linux 8.7 | 2         | 4.35%   |
| Rocky Linux 8.6 | 1         | 2.17%   |
| Rocky Linux 8.3 | 1         | 2.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 46        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 19.15%  |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 8.51%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 8.51%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 6.38%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 4.26%   |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 4.26%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 4.26%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 4.26%   |
| 4.18.0-305.el8.x86_64            | 2         | 4.26%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 4.26%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 4.26%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 4.26%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 2.13%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 2.13%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 1         | 2.13%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1         | 2.13%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 2.13%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 1         | 2.13%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1         | 2.13%   |
| 5.10.89-1.el8.x86_64             | 1         | 2.13%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 2.13%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1         | 2.13%   |
| 4.18.0-240.22.1.el8.x86_64       | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 23        | 50%     |
| 4.18.0  | 20        | 43.48%  |
| 5.4.157 | 1         | 2.17%   |
| 5.16.15 | 1         | 2.17%   |
| 5.10.89 | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 23        | 50%     |
| 4.18    | 20        | 43.48%  |
| 5.4     | 1         | 2.17%   |
| 5.16    | 1         | 2.17%   |
| 5.10    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 35        | 76.09%  |
| MATE          | 3         | 6.52%   |
| KDE5          | 3         | 6.52%   |
| XFCE          | 2         | 4.35%   |
| X-Cinnamon    | 1         | 2.17%   |
| GNOME Classic | 1         | 2.17%   |
| Unknown       | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 30        | 65.22%  |
| X11     | 15        | 32.61%  |
| Tty     | 1         | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 50%     |
| GDM     | 17        | 36.96%  |
| SDDM    | 4         | 8.7%    |
| LightDM | 2         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 34        | 73.91%  |
| ru_RU | 2         | 4.35%   |
| en_ZA | 2         | 4.35%   |
| de_DE | 2         | 4.35%   |
| pt_BR | 1         | 2.17%   |
| it_IT | 1         | 2.17%   |
| fr_FR | 1         | 2.17%   |
| en_IE | 1         | 2.17%   |
| en_CA | 1         | 2.17%   |
| C     | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 36        | 78.26%  |
| BIOS | 10        | 21.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 37        | 80.43%  |
| Ext4 | 8         | 17.39%  |
| Ext3 | 1         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 50%     |
| GPT     | 21        | 45.65%  |
| MBR     | 2         | 4.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 89.13%  |
| Yes       | 5         | 10.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 78.26%  |
| Yes       | 10        | 21.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 17        | 36.96%  |
| Dell             | 10        | 21.74%  |
| Hewlett-Packard  | 9         | 19.57%  |
| ASUSTek Computer | 4         | 8.7%    |
| Toshiba          | 2         | 4.35%   |
| Positivo         | 1         | 2.17%   |
| HUAWEI           | 1         | 2.17%   |
| BANGHO           | 1         | 2.17%   |
| Acer             | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                    | 1         | 2.17%   |
| Toshiba Satellite E45-B                | 1         | 2.17%   |
| Positivo Mobile                        | 1         | 2.17%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 2.17%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 2.17%   |
| Lenovo ThinkPad W500 406132G           | 1         | 2.17%   |
| Lenovo ThinkPad T480 20L6S8B500        | 1         | 2.17%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 2.17%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS  | 1         | 2.17%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 2.17%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW    | 1         | 2.17%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK    | 1         | 2.17%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 2.17%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 2.17%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 2.17%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 2.17%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 2.17%   |
| Lenovo IdeaPad S210 Touch 20257        | 1         | 2.17%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 2.17%   |
| Lenovo IdeaPad 500S-14ISK 80Q3         | 1         | 2.17%   |
| HUAWEI KLVD-WXX9                       | 1         | 2.17%   |
| HP ZBook 15u G6                        | 1         | 2.17%   |
| HP ZBook 15 G3                         | 1         | 2.17%   |
| HP ZBook 15 G2                         | 1         | 2.17%   |
| HP ProBook 640 G3                      | 1         | 2.17%   |
| HP Pavilion g6                         | 1         | 2.17%   |
| HP Laptop 17-ca1xxx                    | 1         | 2.17%   |
| HP Laptop 15-dy2xxx                    | 1         | 2.17%   |
| HP EliteBook 840 G7 Notebook PC        | 1         | 2.17%   |
| HP EliteBook 2560p                     | 1         | 2.17%   |
| Dell XPS 17 9720                       | 1         | 2.17%   |
| Dell XPS 15 7590                       | 1         | 2.17%   |
| Dell Vostro 3500                       | 1         | 2.17%   |
| Dell Precision M6800                   | 1         | 2.17%   |
| Dell Latitude 5500                     | 1         | 2.17%   |
| Dell Latitude 5430                     | 1         | 2.17%   |
| Dell Latitude 5420                     | 1         | 2.17%   |
| Dell Latitude 3420                     | 1         | 2.17%   |
| Dell Inspiron 15-3573                  | 1         | 2.17%   |
| Dell Inspiron 14 5425                  | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 9         | 19.57%  |
| Lenovo IdeaPad    | 6         | 13.04%  |
| Dell Latitude     | 4         | 8.7%    |
| HP ZBook          | 3         | 6.52%   |
| Lenovo Legion     | 2         | 4.35%   |
| HP Laptop         | 2         | 4.35%   |
| HP EliteBook      | 2         | 4.35%   |
| Dell XPS          | 2         | 4.35%   |
| Dell Inspiron     | 2         | 4.35%   |
| ASUS ASUS         | 2         | 4.35%   |
| Toshiba TECRA     | 1         | 2.17%   |
| Toshiba Satellite | 1         | 2.17%   |
| Positivo Mobile   | 1         | 2.17%   |
| HUAWEI KLVD-WXX9  | 1         | 2.17%   |
| HP ProBook        | 1         | 2.17%   |
| HP Pavilion       | 1         | 2.17%   |
| Dell Vostro       | 1         | 2.17%   |
| Dell Precision    | 1         | 2.17%   |
| BANGHO BES        | 1         | 2.17%   |
| ASUS VivoBook     | 1         | 2.17%   |
| ASUS ROG          | 1         | 2.17%   |
| Acer Aspire       | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 17.39%  |
| 2021 | 6         | 13.04%  |
| 2019 | 6         | 13.04%  |
| 2022 | 4         | 8.7%    |
| 2014 | 4         | 8.7%    |
| 2018 | 3         | 6.52%   |
| 2013 | 3         | 6.52%   |
| 2011 | 3         | 6.52%   |
| 2016 | 2         | 4.35%   |
| 2015 | 2         | 4.35%   |
| 2010 | 2         | 4.35%   |
| 2017 | 1         | 2.17%   |
| 2012 | 1         | 2.17%   |
| 2009 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 46        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 39        | 84.78%  |
| Enabled  | 7         | 15.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 18        | 39.13%  |
| 4.01-8.0    | 11        | 23.91%  |
| 32.01-64.0  | 8         | 17.39%  |
| 16.01-24.0  | 6         | 13.04%  |
| 3.01-4.0    | 2         | 4.35%   |
| 64.01-256.0 | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 27.08%  |
| 2.01-3.0   | 13        | 27.08%  |
| 3.01-4.0   | 11        | 22.92%  |
| 8.01-16.0  | 5         | 10.42%  |
| 1.01-2.0   | 4         | 8.33%   |
| 16.01-24.0 | 1         | 2.08%   |
| 0.51-1.0   | 1         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 76.09%  |
| 2      | 7         | 15.22%  |
| 3      | 3         | 6.52%   |
| 4      | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 80.43%  |
| Yes       | 9         | 19.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 80.85%  |
| No        | 9         | 19.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 95.65%  |
| No        | 2         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 86.96%  |
| No        | 6         | 13.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 28.26%  |
| South Africa | 2         | 4.35%   |
| Russia       | 2         | 4.35%   |
| Poland       | 2         | 4.35%   |
| Italy        | 2         | 4.35%   |
| Germany      | 2         | 4.35%   |
| Czechia      | 2         | 4.35%   |
| Brazil       | 2         | 4.35%   |
| Belgium      | 2         | 4.35%   |
| Uzbekistan   | 1         | 2.17%   |
| UAE          | 1         | 2.17%   |
| Turkey       | 1         | 2.17%   |
| Sweden       | 1         | 2.17%   |
| Slovakia     | 1         | 2.17%   |
| Saudi Arabia | 1         | 2.17%   |
| Pakistan     | 1         | 2.17%   |
| Netherlands  | 1         | 2.17%   |
| Malaysia     | 1         | 2.17%   |
| Kazakhstan   | 1         | 2.17%   |
| Ireland      | 1         | 2.17%   |
| Hungary      | 1         | 2.17%   |
| France       | 1         | 2.17%   |
| China        | 1         | 2.17%   |
| Canada       | 1         | 2.17%   |
| Austria      | 1         | 2.17%   |
| Argentina    | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Žilina                | 1         | 2.17%   |
| Xi'an                  | 1         | 2.17%   |
| Vienna                 | 1         | 2.17%   |
| Torrington             | 1         | 2.17%   |
| Syracuse               | 1         | 2.17%   |
| Smolensk               | 1         | 2.17%   |
| Senigallia             | 1         | 2.17%   |
| Scarborough            | 1         | 2.17%   |
| San Miguel de Tucumán | 1         | 2.17%   |
| Riyadh                 | 1         | 2.17%   |
| Rawalpindi             | 1         | 2.17%   |
| Prague                 | 1         | 2.17%   |
| Philadelphia           | 1         | 2.17%   |
| Ottignies              | 1         | 2.17%   |
| Örebro                | 1         | 2.17%   |
| Oakley                 | 1         | 2.17%   |
| Nur-Sultan             | 1         | 2.17%   |
| Mugla                  | 1         | 2.17%   |
| Mossel Bay             | 1         | 2.17%   |
| Moscow                 | 1         | 2.17%   |
| Montreal               | 1         | 2.17%   |
| Melun                  | 1         | 2.17%   |
| Kutno                  | 1         | 2.17%   |
| Krakow                 | 1         | 2.17%   |
| Kansas City            | 1         | 2.17%   |
| Johor Bahru            | 1         | 2.17%   |
| Jaú                   | 1         | 2.17%   |
| Houston                | 1         | 2.17%   |
| Glin                   | 1         | 2.17%   |
| Forest                 | 1         | 2.17%   |
| Fairbanks              | 1         | 2.17%   |
| Enschede               | 1         | 2.17%   |
| Elizabethtown          | 1         | 2.17%   |
| Dreieich               | 1         | 2.17%   |
| Centurion              | 1         | 2.17%   |
| Castelverde            | 1         | 2.17%   |
| Bukhara                | 1         | 2.17%   |
| Budapest               | 1         | 2.17%   |
| Brussels               | 1         | 2.17%   |
| Brno                   | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 15        | 17     | 24.19%  |
| WDC                     | 6         | 6      | 9.68%   |
| Kingston                | 5         | 5      | 8.06%   |
| Toshiba                 | 4         | 5      | 6.45%   |
| Sandisk                 | 4         | 6      | 6.45%   |
| SK hynix                | 3         | 5      | 4.84%   |
| Unknown                 | 2         | 2      | 3.23%   |
| Seagate                 | 2         | 2      | 3.23%   |
| Lexar                   | 2         | 2      | 3.23%   |
| Intel                   | 2         | 2      | 3.23%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.61%   |
| UMIS                    | 1         | 1      | 1.61%   |
| StoreJet                | 1         | 1      | 1.61%   |
| Phison                  | 1         | 1      | 1.61%   |
| Micron Technology       | 1         | 1      | 1.61%   |
| LITEONIT                | 1         | 1      | 1.61%   |
| LITEON                  | 1         | 1      | 1.61%   |
| JMicron Technology      | 1         | 1      | 1.61%   |
| INDMEM                  | 1         | 1      | 1.61%   |
| HS-SSD-C100             | 1         | 1      | 1.61%   |
| Hitachi                 | 1         | 1      | 1.61%   |
| Fujitsu                 | 1         | 1      | 1.61%   |
| Dogfish                 | 1         | 1      | 1.61%   |
| Crucial                 | 1         | 1      | 1.61%   |
| AGI                     | 1         | 1      | 1.61%   |
| ADATA Technology        | 1         | 1      | 1.61%   |
| A-DATA Technology       | 1         | 1      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung SSD 870 EVO 1TB                          | 2         | 3.03%   |
| Lexar 512GB SSD                                  | 2         | 3.03%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1.52%   |
| WDC WDBNCE0010PNC 1TB SSD                        | 1         | 1.52%   |
| WDC WD5000LPCX-24C6HT0 500GB                     | 1         | 1.52%   |
| WDC WD5000BPVT-00A1YT0 500GB                     | 1         | 1.52%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1.52%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1.52%   |
| Unknown SD/MMC/MS PRO 16GB                       | 1         | 1.52%   |
| Unknown MMC Card  64GB                           | 1         | 1.52%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB     | 1         | 1.52%   |
| UMIS RPFTJ128PDD2EWX 128GB                       | 1         | 1.52%   |
| Toshiba THNSNJ512GACU 512GB SSD                  | 1         | 1.52%   |
| Toshiba THNSNJ128G8NU 128GB SSD                  | 1         | 1.52%   |
| Toshiba NVMe SSD Drive 512GB                     | 1         | 1.52%   |
| Toshiba KXG6AZNV1T02 1TB                         | 1         | 1.52%   |
| Toshiba KXG6APNV2T04 2TB                         | 1         | 1.52%   |
| StoreJet Disk 1TB                                | 1         | 1.52%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB        | 1         | 1.52%   |
| SK hynix SHPP41-2000GM 2TB                       | 1         | 1.52%   |
| SK hynix NVMe SSD Drive 512GB                    | 1         | 1.52%   |
| SK hynix BC511 NVMe 512GB                        | 1         | 1.52%   |
| Seagate ST9320325AS 320GB                        | 1         | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1.52%   |
| Sandisk WD PC SN735 SDBPNHH-1T00-1002 1024GB     | 1         | 1.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 1         | 1.52%   |
| SanDisk SSD PLUS 1000GB                          | 1         | 1.52%   |
| SanDisk SD5SG2256G1052E 256GB SSD                | 1         | 1.52%   |
| SanDisk Extreme 55AE 500GB SSD                   | 1         | 1.52%   |
| Samsung SSD 970 EVO 500GB                        | 1         | 1.52%   |
| Samsung SSD 870 QVO 2TB                          | 1         | 1.52%   |
| Samsung SSD 860 QVO 4TB                          | 1         | 1.52%   |
| Samsung SSD 860 EVO 500GB                        | 1         | 1.52%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB           | 1         | 1.52%   |
| Samsung PM9A1 NVMe SED 512GB                     | 1         | 1.52%   |
| Samsung PM991a NVMe 512GB                        | 1         | 1.52%   |
| Samsung NVMe SSD Drive 512GB                     | 1         | 1.52%   |
| Samsung NVMe SSD Drive 1024GB                    | 1         | 1.52%   |
| Samsung MZVLB512HBJQ-000L7 512GB                 | 1         | 1.52%   |
| Samsung MZVLB512HBJQ-000L2 512GB                 | 1         | 1.52%   |

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
| NVMe    | 25        | 31     | 46.3%   |
| SSD     | 17        | 24     | 31.48%  |
| HDD     | 8         | 10     | 14.81%  |
| Unknown | 3         | 3      | 5.56%   |
| MMC     | 1         | 1      | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 25        | 31     | 46.3%   |
| SATA | 23        | 32     | 42.59%  |
| SAS  | 5         | 5      | 9.26%   |
| MMC  | 1         | 1      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 17     | 51.85%  |
| 0.51-1.0   | 10        | 13     | 37.04%  |
| 1.01-2.0   | 2         | 2      | 7.41%   |
| 3.01-4.0   | 1         | 2      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 18        | 39.13%  |
| 101-250        | 12        | 26.09%  |
| 501-1000       | 5         | 10.87%  |
| 1001-2000      | 4         | 8.7%    |
| 2001-3000      | 3         | 6.52%   |
| 51-100         | 3         | 6.52%   |
| More than 3000 | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 34.78%  |
| 21-50     | 11        | 23.91%  |
| 101-250   | 7         | 15.22%  |
| 51-100    | 5         | 10.87%  |
| 251-500   | 3         | 6.52%   |
| 1001-2000 | 2         | 4.35%   |
| 501-1000  | 2         | 4.35%   |

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
| Works    | 25        | 34     | 51.02%  |
| Detected | 24        | 35     | 48.98%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 50%     |
| Samsung Electronics          | 8         | 14.29%  |
| AMD                          | 5         | 8.93%   |
| SK hynix                     | 3         | 5.36%   |
| Toshiba America Info Systems | 2         | 3.57%   |
| SanDisk                      | 2         | 3.57%   |
| Kingston Technology Company  | 2         | 3.57%   |
| Union Memory (Shenzhen)      | 1         | 1.79%   |
| Shenzhen Longsys Electronics | 1         | 1.79%   |
| Realtek Semiconductor        | 1         | 1.79%   |
| Phison Electronics           | 1         | 1.79%   |
| Micron Technology            | 1         | 1.79%   |
| ADATA Technology             | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 5%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 3.33%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 3.33%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 3.33%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 3.33%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 3.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 2         | 3.33%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.67%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                                       | 1         | 1.67%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.67%   |
| SK hynix BC511                                                                         | 1         | 1.67%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                            | 1         | 1.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.67%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 1.67%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 1.67%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 1.67%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.67%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.67%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.67%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.67%   |
| Intel SSD 660P Series                                                                  | 1         | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.67%   |
| Intel Non-Volatile memory controller                                                   | 1         | 1.67%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 25        | 43.86%  |
| SATA | 24        | 42.11%  |
| IDE  | 5         | 8.77%   |
| RAID | 3         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 80.43%  |
| AMD    | 9         | 19.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 8.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 4.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 4.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 2.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 2.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 2.17%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 2.17%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 2.17%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 2.17%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 2.17%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2.17%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.17%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 2.17%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 2.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.17%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.17%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 2.17%   |
| Intel Celeron CPU 1037U @ 1.80GHz             | 1         | 2.17%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.17%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.17%   |
| Intel 12th Gen Core i5-1245U                  | 1         | 2.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 2.17%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 2.17%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 1         | 2.17%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.17%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 15        | 32.61%  |
| Other                | 10        | 21.74%  |
| Intel Core i5        | 9         | 19.57%  |
| AMD Ryzen 5          | 4         | 8.7%    |
| AMD Ryzen 7          | 2         | 4.35%   |
| Intel Pentium Silver | 1         | 2.17%   |
| Intel Core i3        | 1         | 2.17%   |
| Intel Core 2 Duo     | 1         | 2.17%   |
| Intel Celeron        | 1         | 2.17%   |
| AMD Ryzen 5 PRO      | 1         | 2.17%   |
| AMD A8               | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 21        | 45.65%  |
| 2      | 12        | 26.09%  |
| 6      | 6         | 13.04%  |
| 8      | 3         | 6.52%   |
| 14     | 1         | 2.17%   |
| 12     | 1         | 2.17%   |
| 10     | 1         | 2.17%   |
| 1      | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 86.96%  |
| 1      | 6         | 13.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 7         | 15.22%  |
| 0x806c1    | 6         | 13.04%  |
| 0x806ec    | 4         | 8.7%    |
| 0xa0652    | 3         | 6.52%   |
| 0x906a3    | 2         | 4.35%   |
| 0x506e3    | 2         | 4.35%   |
| 0x306a9    | 2         | 4.35%   |
| 0x206a7    | 2         | 4.35%   |
| 0x0a50000c | 2         | 4.35%   |
| 0x08600104 | 2         | 4.35%   |
| 0x906ea    | 1         | 2.17%   |
| 0x906a4    | 1         | 2.17%   |
| 0x806ea    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x706a1    | 1         | 2.17%   |
| 0x406e3    | 1         | 2.17%   |
| 0x40651    | 1         | 2.17%   |
| 0x20655    | 1         | 2.17%   |
| 0x10676    | 1         | 2.17%   |
| 0x0a50000d | 1         | 2.17%   |
| 0x0a404101 | 1         | 2.17%   |
| 0x08108102 | 1         | 2.17%   |
| 0x06006705 | 1         | 2.17%   |
| 0x06001116 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 8         | 17.39%  |
| KabyLake         | 7         | 15.22%  |
| TigerLake        | 6         | 13.04%  |
| Zen 3            | 3         | 6.52%   |
| Skylake          | 3         | 6.52%   |
| CometLake        | 3         | 6.52%   |
| Alderlake Hybrid | 3         | 6.52%   |
| Zen 2            | 2         | 4.35%   |
| SandyBridge      | 2         | 4.35%   |
| IvyBridge        | 2         | 4.35%   |
| Zen+             | 1         | 2.17%   |
| Westmere         | 1         | 2.17%   |
| Piledriver       | 1         | 2.17%   |
| Penryn           | 1         | 2.17%   |
| Goldmont plus    | 1         | 2.17%   |
| Excavator        | 1         | 2.17%   |
| Unknown          | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 51.52%  |
| Nvidia | 22        | 33.33%  |
| AMD    | 10        | 15.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 8.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 7.46%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 4.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 4.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 4.48%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 2         | 2.99%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 2.99%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.99%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 2.99%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 2.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.99%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.49%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.49%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.49%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.49%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 1.49%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 1.49%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.49%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 1.49%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.49%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.49%   |
| Intel UHD Graphics 620                                                    | 1         | 1.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.49%   |
| Intel HD Graphics 620                                                     | 1         | 1.49%   |
| Intel HD Graphics 530                                                     | 1         | 1.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.49%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.49%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 1         | 1.49%   |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 1.49%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.49%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 36.96%  |
| Intel + Nvidia | 15        | 32.61%  |
| 1 x Nvidia     | 4         | 8.7%    |
| 1 x AMD        | 4         | 8.7%    |
| AMD + Nvidia   | 3         | 6.52%   |
| Intel + AMD    | 2         | 4.35%   |
| 2 x AMD        | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 78.26%  |
| Proprietary | 9         | 19.57%  |
| Unknown     | 1         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 53.19%  |
| 3.01-4.0   | 8         | 17.02%  |
| 1.01-2.0   | 5         | 10.64%  |
| 0.01-0.5   | 5         | 10.64%  |
| 5.01-6.0   | 2         | 4.26%   |
| 7.01-8.0   | 1         | 2.13%   |
| 0.51-1.0   | 1         | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 12        | 19.05%  |
| AU Optronics        | 10        | 15.87%  |
| BOE                 | 9         | 14.29%  |
| Samsung Electronics | 6         | 9.52%   |
| Dell                | 5         | 7.94%   |
| Chimei Innolux      | 5         | 7.94%   |
| Goldstar            | 4         | 6.35%   |
| Sharp               | 2         | 3.17%   |
| Philips             | 2         | 3.17%   |
| AOC                 | 2         | 3.17%   |
| PANDA               | 1         | 1.59%   |
| Panasonic           | 1         | 1.59%   |
| Lenovo              | 1         | 1.59%   |
| InfoVision          | 1         | 1.59%   |
| Gigabyte Technology | 1         | 1.59%   |
| BenQ                | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 3.08%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.54%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.54%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.54%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 1.54%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.54%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 1.54%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.54%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.54%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.54%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.54%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.54%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 1.54%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 1         | 1.54%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.54%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 1.54%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.54%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.54%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.54%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.54%   |
| Gigabyte Technology G27QC A GBT2716 2560x1440 597x336mm 27.0-inch     | 1         | 1.54%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 1.54%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.54%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.54%   |
| Dell S2415H DELA0B5 1920x1080 527x296mm 23.8-inch                     | 1         | 1.54%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.54%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 50%     |
| 1366x768 (WXGA)    | 8         | 14.29%  |
| 3840x2160 (4K)     | 3         | 5.36%   |
| 2560x1440 (QHD)    | 3         | 5.36%   |
| 1600x900 (HD+)     | 3         | 5.36%   |
| 1920x1200 (WUXGA)  | 2         | 3.57%   |
| 1680x1050 (WSXGA+) | 2         | 3.57%   |
| 3840x2400          | 1         | 1.79%   |
| 3840x1080          | 1         | 1.79%   |
| 3440x1440          | 1         | 1.79%   |
| 2560x1080          | 1         | 1.79%   |
| 2240x1400          | 1         | 1.79%   |
| 2160x1440          | 1         | 1.79%   |
| Unknown            | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 23        | 37.1%   |
| 14     | 12        | 19.35%  |
| 27     | 6         | 9.68%   |
| 17     | 5         | 8.06%   |
| 13     | 5         | 8.06%   |
| 24     | 3         | 4.84%   |
| 21     | 3         | 4.84%   |
| 34     | 2         | 3.23%   |
| 49     | 1         | 1.61%   |
| 23     | 1         | 1.61%   |
| 22     | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 59.68%  |
| 501-600     | 9         | 14.52%  |
| 401-500     | 5         | 8.06%   |
| 351-400     | 5         | 8.06%   |
| 201-300     | 3         | 4.84%   |
| 701-800     | 2         | 3.23%   |
| 1001-1500   | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 42        | 80.77%  |
| 16/10 | 5         | 9.62%   |
| 3/2   | 2         | 3.85%   |
| 21/9  | 2         | 3.85%   |
| 32/9  | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 37.7%   |
| 81-90          | 16        | 26.23%  |
| 301-350        | 6         | 9.84%   |
| 201-250        | 6         | 9.84%   |
| 121-130        | 5         | 8.2%    |
| 351-500        | 2         | 3.28%   |
| 71-80          | 1         | 1.64%   |
| 151-200        | 1         | 1.64%   |
| 501-1000       | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 30        | 48.39%  |
| 101-120       | 14        | 22.58%  |
| 51-100        | 10        | 16.13%  |
| 161-240       | 5         | 8.06%   |
| More than 240 | 3         | 4.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 65.22%  |
| 2     | 11        | 23.91%  |
| 3     | 3         | 6.52%   |
| 4     | 1         | 2.17%   |
| 0     | 1         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 47.22%  |
| Realtek Semiconductor | 22        | 30.56%  |
| Qualcomm Atheros      | 5         | 6.94%   |
| MediaTek              | 4         | 5.56%   |
| Ralink                | 1         | 1.39%   |
| Lenovo                | 1         | 1.39%   |
| JMicron Technology    | 1         | 1.39%   |
| Dell                  | 1         | 1.39%   |
| D-Link                | 1         | 1.39%   |
| Broadcom Limited      | 1         | 1.39%   |
| Broadcom              | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 14.61%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 5.62%   |
| Intel Wireless 7260                                               | 5         | 5.62%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.49%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 4.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 3.37%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 3.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 3.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.25%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.25%   |
| Intel Wireless 8260                                               | 2         | 2.25%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.12%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.12%   |
| MediaTek WLAN controller                                          | 1         | 1.12%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.12%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.12%   |
| Intel Wireless 7265                                               | 1         | 1.12%   |
| Intel Wireless 3160                                               | 1         | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.12%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.12%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 73.33%  |
| Qualcomm Atheros      | 4         | 8.89%   |
| Realtek Semiconductor | 3         | 6.67%   |
| MediaTek              | 2         | 4.44%   |
| Ralink                | 1         | 2.22%   |
| Dell                  | 1         | 2.22%   |
| Broadcom Limited      | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                                                | 5         | 11.11%  |
| Intel Wi-Fi 6 AX201                                                                                                | 4         | 8.89%   |
| Intel Wi-Fi 6 AX200                                                                                                | 3         | 6.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                     | 3         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                       | 3         | 6.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 3         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                                                                         | 2         | 4.44%   |
| Intel Wireless 8260                                                                                                | 2         | 4.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                           | 2         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 1         | 2.22%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                         | 1         | 2.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                                        | 1         | 2.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                          | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                         | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 1         | 2.22%   |
| MediaTek WLAN controller                                                                                           | 1         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                      | 1         | 2.22%   |
| Intel Wireless 7265                                                                                                | 1         | 2.22%   |
| Intel Wireless 3160                                                                                                | 1         | 2.22%   |
| Intel Ultimate N WiFi Link 5300                                                                                    | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                    | 1         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                  | 1         | 2.22%   |
| Intel Centrino Wireless-N 135                                                                                      | 1         | 2.22%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1         | 2.22%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                                         | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 48.84%  |
| Intel                 | 15        | 34.88%  |
| MediaTek              | 2         | 4.65%   |
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
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 11.36%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 4.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.27%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 2.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.27%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.27%   |
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
| WiFi     | 44        | 54.32%  |
| Ethernet | 37        | 45.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 70.59%  |
| Ethernet | 15        | 29.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 32        | 69.57%  |
| 1     | 13        | 28.26%  |
| 3     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 71.74%  |
| Yes  | 13        | 28.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 65%     |
| Qualcomm Atheros Communications | 4         | 10%     |
| Foxconn / Hon Hai               | 3         | 7.5%    |
| Realtek Semiconductor           | 2         | 5%      |
| Ralink                          | 1         | 2.5%    |
| IMC Networks                    | 1         | 2.5%    |
| Hewlett-Packard                 | 1         | 2.5%    |
| Dell                            | 1         | 2.5%    |
| Broadcom                        | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 10        | 25%     |
| Intel AX201 Bluetooth                              | 8         | 20%     |
| Qualcomm Atheros  Bluetooth Device                 | 3         | 7.5%    |
| Intel AX200 Bluetooth                              | 3         | 7.5%    |
| Foxconn / Hon Hai Wireless_Device                  | 3         | 7.5%    |
| Intel Bluetooth Device                             | 2         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 2.5%    |
| Realtek Bluetooth Radio                            | 1         | 2.5%    |
| Ralink RT3290 Bluetooth                            | 1         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 2.5%    |
| IMC Networks Wireless_Device                       | 1         | 2.5%    |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 2.5%    |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 37        | 52.11%  |
| Nvidia              | 14        | 19.72%  |
| AMD                 | 9         | 12.68%  |
| Logitech            | 2         | 2.82%   |
| GN Netcom           | 2         | 2.82%   |
| Conexant Systems    | 2         | 2.82%   |
| Saitek              | 1         | 1.41%   |
| Huawei Technologies | 1         | 1.41%   |
| Hewlett-Packard     | 1         | 1.41%   |
| Creative Technology | 1         | 1.41%   |
| C-Media Electronics | 1         | 1.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 8.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 5.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 4.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.57%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 3.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 3.57%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 3.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 3.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 3.57%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.38%   |
| Saitek Cyborg F.R.E.Q.5 Gaming Headset                                     | 1         | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.19%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.19%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.19%   |
| Logitech Stereo H650e                                                      | 1         | 1.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.19%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.19%   |
| Huawei Technologies MateView GT                                            | 1         | 1.19%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.19%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.19%   |
| GN Netcom Jabra EVOLVE 65                                                  | 1         | 1.19%   |
| Creative Technology Sound Blaster Play! 3                                  | 1         | 1.19%   |
| Conexant Systems HP Dock Audio                                             | 1         | 1.19%   |
| Conexant Systems CONEXANT USB AUDIO                                        | 1         | 1.19%   |
| C-Media Electronics JPL-100-USB                                            | 1         | 1.19%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 26.92%  |
| SK hynix            | 6         | 23.08%  |
| Micron Technology   | 3         | 11.54%  |
| Crucial             | 2         | 7.69%   |
| Smart               | 1         | 3.85%   |
| Ramaxel Technology  | 1         | 3.85%   |
| Magnum Tech         | 1         | 3.85%   |
| Lexar Co Limited    | 1         | 3.85%   |
| Lexar               | 1         | 3.85%   |
| Kingston            | 1         | 3.85%   |
| G.Skill             | 1         | 3.85%   |
| A-DATA Technology   | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s          | 1         | 3.85%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 1         | 3.85%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 3.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s      | 1         | 3.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 3.85%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 3.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 3.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 1         | 3.85%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 3.85%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 3.85%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s   | 1         | 3.85%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s      | 1         | 3.85%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s        | 1         | 3.85%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 3.85%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s          | 1         | 3.85%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s          | 1         | 3.85%   |
| Lexar Co Limited RAM LD4AS008G-2666SC 8GB SODIMM DDR4 2667MT/s | 1         | 3.85%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 3.85%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s           | 1         | 3.85%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| A-DATA RAM AO1P32NC8T1-BZ4SHD 8GB SODIMM DDR4 3200MT/s         | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 58.33%  |
| DDR3   | 7         | 29.17%  |
| LPDDR5 | 1         | 4.17%   |
| LPDDR4 | 1         | 4.17%   |
| DDR5   | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 91.67%  |
| Row Of Chips | 2         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 72%     |
| 16384 | 3         | 12%     |
| 4096  | 3         | 12%     |
| 32768 | 1         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 8         | 32%     |
| 2667  | 7         | 28%     |
| 1600  | 6         | 24%     |
| 6400  | 1         | 4%      |
| 4800  | 1         | 4%      |
| 4266  | 1         | 4%      |
| 2133  | 1         | 4%      |

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
| IMC Networks                           | 8         | 19.05%  |
| Chicony Electronics                    | 8         | 19.05%  |
| Microdia                               | 5         | 11.9%   |
| Syntek                                 | 3         | 7.14%   |
| Sunplus Innovation Technology          | 3         | 7.14%   |
| Realtek Semiconductor                  | 2         | 4.76%   |
| Logitech                               | 2         | 4.76%   |
| Acer                                   | 2         | 4.76%   |
| Suyin                                  | 1         | 2.38%   |
| Quanta                                 | 1         | 2.38%   |
| Luxvisions Innotech Limited            | 1         | 2.38%   |
| Lite-On Technology                     | 1         | 2.38%   |
| Lenovo                                 | 1         | 2.38%   |
| Intel                                  | 1         | 2.38%   |
| DLEQNA19IFK6G2                         | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.38%   |
| Apple                                  | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 5         | 11.9%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 9.52%   |
| IMC Networks Integrated Camera                                             | 3         | 7.14%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 4.76%   |
| Syntek Integrated Camera                                                   | 1         | 2.38%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.38%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 2.38%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 2.38%   |
| Sunplus FHD Camera Microphone                                              | 1         | 2.38%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.38%   |
| Realtek EasyCamera                                                         | 1         | 2.38%   |
| Quanta HP Webcam                                                           | 1         | 2.38%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 2.38%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 2.38%   |
| Logitech HD Pro Webcam C920                                                | 1         | 2.38%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 2.38%   |
| Lite-On HP HD Webcam                                                       | 1         | 2.38%   |
| Lenovo UVC Camera                                                          | 1         | 2.38%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 2.38%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 2.38%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.38%   |
| IMC Networks HD Camera                                                     | 1         | 2.38%   |
| DLEQNA19IFK6G2 HP TrueVision HD Camera                                     | 1         | 2.38%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.38%   |
| Chicony HP HD Camera                                                       | 1         | 2.38%   |
| Chicony HD WebCam                                                          | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 2.38%   |
| Acer Integrated RGB Camera                                                 | 1         | 2.38%   |
| Acer Integrated Camera                                                     | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 38.46%  |
| Synaptics                  | 5         | 38.46%  |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| LighTuning Technology      | 1         | 7.69%   |
| AuthenTec                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 15.38%  |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 7.69%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device                        | 1         | 7.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 7.69%   |
| AuthenTec AES2810                                          | 1         | 7.69%   |

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
| 0     | 22        | 47.83%  |
| 1     | 19        | 41.3%   |
| 2     | 5         | 10.87%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 44.83%  |
| Graphics card         | 6         | 20.69%  |
| Chipcard              | 3         | 10.34%  |
| Net/wireless          | 2         | 6.9%    |
| Net/ethernet          | 2         | 6.9%    |
| Multimedia controller | 1         | 3.45%   |
| Card reader           | 1         | 3.45%   |
| Bluetooth             | 1         | 3.45%   |

