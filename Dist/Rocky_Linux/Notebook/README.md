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

Total: 42

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| HP      | EliteBook 2560p             | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Dell    | Inspiron 14 5425            | [42f45d59d2](https://linux-hardware.org/?probe=42f45d59d2) | Dec 29, 2022 |
| HP      | ProBook 640 G3              | [03eba7b664](https://linux-hardware.org/?probe=03eba7b664) | Dec 15, 2022 |
| Lenovo  | ThinkPad T14s Gen 3 21BR... | [ede2606ad1](https://linux-hardware.org/?probe=ede2606ad1) | Dec 15, 2022 |
| Dell    | Vostro 3500                 | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| Lenovo  | ThinkPad P1 Gen 3 20THCT... | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| ASUSTek | VivoBook_ASUSLaptop X512... | [cda3087aaf](https://linux-hardware.org/?probe=cda3087aaf) | Oct 23, 2022 |
| HP      | Pavilion g6                 | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| BANGHO  | BES G1529                   | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Dell    | XPS 15 7590                 | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Dell    | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| HP      | ZBook 15u G6                | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| HP      | ZBook 15 G2                 | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| ASUSTek | ASUS TUF Dash F15 FX516P... | [ce5ca74472](https://linux-hardware.org/?probe=ce5ca74472) | Jul 17, 2022 |
| Lenovo  | ThinkPad X1 Carbon 34483... | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell    | Latitude 3420               | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| HP      | EliteBook 840 G7 Noteboo... | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell    | Latitude 5500               | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell    | Latitude 5500               | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Lenovo  | Legion Y7000 2020H 81Y7     | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo  | Legion Y7000 2020H 81Y7     | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| Lenovo  | IdeaPad Y700-15ISK 80NV     | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP      | ZBook 15 G3                 | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo  | Legion 5 15ARH05H 82B1      | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo  | IdeaPad 500S-14ISK 80Q3     | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo  | ThinkPad W540 20BGCTO1WW    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| HP      | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Toshiba | TECRA W50-A                 | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Lenovo  | ThinkPad T420 42365H1       | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo  | ThinkPad T420 42365H1       | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Lenovo  | ThinkPad W500 406132G       | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Y410P 20216         | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Y410P 20216         | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek | ASUS TUF Gaming A15 FA50... | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba | Satellite E45-B             | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| Acer    | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Rocky Linux 8.5 | 11        | 32.35%  |
| Rocky Linux 9.0 | 9         | 26.47%  |
| Rocky Linux 8.4 | 8         | 23.53%  |
| Rocky Linux 9.1 | 3         | 8.82%   |
| Rocky Linux 8.7 | 1         | 2.94%   |
| Rocky Linux 8.6 | 1         | 2.94%   |
| Rocky Linux 8.3 | 1         | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 34        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.14.0-70.22.1.el9_0.x86_64     | 4         | 11.76%  |
| 5.14.0-162.6.1.el9_1.0.1.x86_64 | 3         | 8.82%   |
| 4.18.0-348.7.1.el8_5.x86_64     | 3         | 8.82%   |
| 5.14.0-70.26.1.el9_0.x86_64     | 2         | 5.88%   |
| 4.18.0-348.20.1.el8_5.x86_64    | 2         | 5.88%   |
| 4.18.0-348.12.2.el8_5.x86_64    | 2         | 5.88%   |
| 4.18.0-305.el8.x86_64           | 2         | 5.88%   |
| 4.18.0-305.3.1.el8_4.x86_64     | 2         | 5.88%   |
| 4.18.0-305.25.1.el8_4.x86_64    | 2         | 5.88%   |
| 4.18.0-305.10.2.el8_4.x86_64    | 2         | 5.88%   |
| 5.4.157-1.el8.elrepo.x86_64     | 1         | 2.94%   |
| 5.16.15-1.el8.elrepo.x86_64     | 1         | 2.94%   |
| 5.14.0-70.30.1.el9_0.x86_64     | 1         | 2.94%   |
| 5.14.0-70.17.1.el9_0.x86_64     | 1         | 2.94%   |
| 5.14.0-70.13.1.el9_0.x86_64     | 1         | 2.94%   |
| 5.10.89-1.el8.x86_64            | 1         | 2.94%   |
| 4.18.0-425.3.1.el8.x86_64       | 1         | 2.94%   |
| 4.18.0-348.el8.0.2.x86_64       | 1         | 2.94%   |
| 4.18.0-348.2.1.el8_5.x86_64     | 1         | 2.94%   |
| 4.18.0-240.22.1.el8.x86_64      | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 19        | 55.88%  |
| 5.14.0  | 12        | 35.29%  |
| 5.4.157 | 1         | 2.94%   |
| 5.16.15 | 1         | 2.94%   |
| 5.10.89 | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 19        | 55.88%  |
| 5.14    | 12        | 35.29%  |
| 5.4     | 1         | 2.94%   |
| 5.16    | 1         | 2.94%   |
| 5.10    | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 34        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 26        | 76.47%  |
| MATE          | 3         | 8.82%   |
| XFCE          | 2         | 5.88%   |
| X-Cinnamon    | 1         | 2.94%   |
| KDE5          | 1         | 2.94%   |
| GNOME Classic | 1         | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 22        | 64.71%  |
| X11     | 12        | 35.29%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 55.88%  |
| GDM     | 11        | 32.35%  |
| SDDM    | 2         | 5.88%   |
| LightDM | 2         | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 25        | 73.53%  |
| ru_RU | 2         | 5.88%   |
| en_ZA | 2         | 5.88%   |
| de_DE | 2         | 5.88%   |
| pt_BR | 1         | 2.94%   |
| it_IT | 1         | 2.94%   |
| en_CA | 1         | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 73.53%  |
| BIOS | 9         | 26.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 27        | 79.41%  |
| Ext4 | 6         | 17.65%  |
| Ext3 | 1         | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 58.82%  |
| GPT     | 12        | 35.29%  |
| MBR     | 2         | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 88.24%  |
| Yes       | 4         | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 85.29%  |
| Yes       | 5         | 14.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 13        | 38.24%  |
| Hewlett-Packard  | 8         | 23.53%  |
| Dell             | 6         | 17.65%  |
| ASUSTek Computer | 3         | 8.82%   |
| Toshiba          | 2         | 5.88%   |
| BANGHO           | 1         | 2.94%   |
| Acer             | 1         | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 2.94%   |
| Toshiba Satellite E45-B                  | 1         | 2.94%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 2.94%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 2.94%   |
| Lenovo ThinkPad W500 406132G             | 1         | 2.94%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 2.94%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 2.94%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 2.94%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 2.94%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 2.94%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 2.94%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 2.94%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 2.94%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 2.94%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 2.94%   |
| HP ZBook 15u G6                          | 1         | 2.94%   |
| HP ZBook 15 G3                           | 1         | 2.94%   |
| HP ZBook 15 G2                           | 1         | 2.94%   |
| HP ProBook 640 G3                        | 1         | 2.94%   |
| HP Pavilion g6                           | 1         | 2.94%   |
| HP Laptop 17-ca1xxx                      | 1         | 2.94%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 2.94%   |
| HP EliteBook 2560p                       | 1         | 2.94%   |
| Dell XPS 15 7590                         | 1         | 2.94%   |
| Dell Vostro 3500                         | 1         | 2.94%   |
| Dell Latitude 5500                       | 1         | 2.94%   |
| Dell Latitude 5430                       | 1         | 2.94%   |
| Dell Latitude 3420                       | 1         | 2.94%   |
| Dell Inspiron 14 5425                    | 1         | 2.94%   |
| BANGHO BES G1529                         | 1         | 2.94%   |
| ASUS VivoBook_ASUSLaptop X512FL_X512FL   | 1         | 2.94%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 2.94%   |
| ASUS ASUS TUF Dash F15 FX516PM_FX516PM   | 1         | 2.94%   |
| Acer Aspire VN7-591G                     | 1         | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 7         | 20.59%  |
| Lenovo IdeaPad    | 4         | 11.76%  |
| HP ZBook          | 3         | 8.82%   |
| Dell Latitude     | 3         | 8.82%   |
| Lenovo Legion     | 2         | 5.88%   |
| HP EliteBook      | 2         | 5.88%   |
| ASUS ASUS         | 2         | 5.88%   |
| Toshiba TECRA     | 1         | 2.94%   |
| Toshiba Satellite | 1         | 2.94%   |
| HP ProBook        | 1         | 2.94%   |
| HP Pavilion       | 1         | 2.94%   |
| HP Laptop         | 1         | 2.94%   |
| Dell XPS          | 1         | 2.94%   |
| Dell Vostro       | 1         | 2.94%   |
| Dell Inspiron     | 1         | 2.94%   |
| BANGHO BES        | 1         | 2.94%   |
| ASUS VivoBook     | 1         | 2.94%   |
| Acer Aspire       | 1         | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 17.65%  |
| 2020 | 5         | 14.71%  |
| 2021 | 4         | 11.76%  |
| 2014 | 4         | 11.76%  |
| 2011 | 3         | 8.82%   |
| 2022 | 2         | 5.88%   |
| 2016 | 2         | 5.88%   |
| 2015 | 2         | 5.88%   |
| 2018 | 1         | 2.94%   |
| 2017 | 1         | 2.94%   |
| 2013 | 1         | 2.94%   |
| 2012 | 1         | 2.94%   |
| 2010 | 1         | 2.94%   |
| 2009 | 1         | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 34        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 31        | 91.18%  |
| Enabled  | 3         | 8.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 12        | 35.29%  |
| 4.01-8.0    | 8         | 23.53%  |
| 32.01-64.0  | 6         | 17.65%  |
| 16.01-24.0  | 6         | 17.65%  |
| 3.01-4.0    | 1         | 2.94%   |
| 64.01-256.0 | 1         | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 10        | 29.41%  |
| 4.01-8.0   | 9         | 26.47%  |
| 2.01-3.0   | 6         | 17.65%  |
| 1.01-2.0   | 4         | 11.76%  |
| 8.01-16.0  | 4         | 11.76%  |
| 16.01-24.0 | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 73.53%  |
| 2      | 6         | 17.65%  |
| 3      | 3         | 8.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 82.35%  |
| Yes       | 6         | 17.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 88.24%  |
| No        | 4         | 11.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 88.24%  |
| No        | 4         | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 9         | 26.47%  |
| South Africa | 2         | 5.88%   |
| Russia       | 2         | 5.88%   |
| Germany      | 2         | 5.88%   |
| Czechia      | 2         | 5.88%   |
| Belgium      | 2         | 5.88%   |
| UAE          | 1         | 2.94%   |
| Turkey       | 1         | 2.94%   |
| Sweden       | 1         | 2.94%   |
| Slovakia     | 1         | 2.94%   |
| Poland       | 1         | 2.94%   |
| Pakistan     | 1         | 2.94%   |
| Netherlands  | 1         | 2.94%   |
| Malaysia     | 1         | 2.94%   |
| Kazakhstan   | 1         | 2.94%   |
| Italy        | 1         | 2.94%   |
| China        | 1         | 2.94%   |
| Canada       | 1         | 2.94%   |
| Brazil       | 1         | 2.94%   |
| Austria      | 1         | 2.94%   |
| Argentina    | 1         | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Žilina                | 1         | 2.94%   |
| Xi'an                  | 1         | 2.94%   |
| Vienna                 | 1         | 2.94%   |
| Syracuse               | 1         | 2.94%   |
| Smolensk               | 1         | 2.94%   |
| Senigallia             | 1         | 2.94%   |
| Scarborough            | 1         | 2.94%   |
| San Miguel de Tucumán | 1         | 2.94%   |
| Rawalpindi             | 1         | 2.94%   |
| Prague                 | 1         | 2.94%   |
| Philadelphia           | 1         | 2.94%   |
| Ottignies              | 1         | 2.94%   |
| Örebro                | 1         | 2.94%   |
| Oakley                 | 1         | 2.94%   |
| Nur-Sultan             | 1         | 2.94%   |
| Mugla                  | 1         | 2.94%   |
| Mossel Bay             | 1         | 2.94%   |
| Moscow                 | 1         | 2.94%   |
| Montreal               | 1         | 2.94%   |
| Kutno                  | 1         | 2.94%   |
| Kansas City            | 1         | 2.94%   |
| Johor Bahru            | 1         | 2.94%   |
| Jaú                   | 1         | 2.94%   |
| Houston                | 1         | 2.94%   |
| Forest                 | 1         | 2.94%   |
| Fairbanks              | 1         | 2.94%   |
| Enschede               | 1         | 2.94%   |
| Dreieich               | 1         | 2.94%   |
| Centurion              | 1         | 2.94%   |
| Brussels               | 1         | 2.94%   |
| Brno                   | 1         | 2.94%   |
| Berlin                 | 1         | 2.94%   |
| Ashburn                | 1         | 2.94%   |
| Abu Dhabi              | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 15        | 17     | 31.91%  |
| WDC                     | 4         | 4      | 8.51%   |
| Toshiba                 | 4         | 5      | 8.51%   |
| Kingston                | 4         | 4      | 8.51%   |
| Unknown                 | 2         | 2      | 4.26%   |
| Seagate                 | 2         | 2      | 4.26%   |
| Union Memory (Shenzhen) | 1         | 1      | 2.13%   |
| UMIS                    | 1         | 1      | 2.13%   |
| StoreJet                | 1         | 1      | 2.13%   |
| SK hynix                | 1         | 2      | 2.13%   |
| SanDisk                 | 1         | 1      | 2.13%   |
| LITEONIT                | 1         | 1      | 2.13%   |
| LITEON                  | 1         | 1      | 2.13%   |
| Lexar                   | 1         | 1      | 2.13%   |
| Intel                   | 1         | 1      | 2.13%   |
| HS-SSD-C100             | 1         | 1      | 2.13%   |
| Hitachi                 | 1         | 1      | 2.13%   |
| Fujitsu                 | 1         | 1      | 2.13%   |
| Dogfish                 | 1         | 1      | 2.13%   |
| AGI                     | 1         | 1      | 2.13%   |
| ADATA Technology        | 1         | 1      | 2.13%   |
| A-DATA Technology       | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Samsung SSD 870 EVO 1TB                      | 2         | 4%      |
| WDC WDS480G2G0A-00JH30 480GB SSD             | 1         | 2%      |
| WDC WD5000BPVT-00A1YT0 500GB                 | 1         | 2%      |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 2%      |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 2%      |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 2%      |
| Unknown MMC Card  64GB                       | 1         | 2%      |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2%      |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 2%      |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 2%      |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 2%      |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2%      |
| Toshiba KXG6AZNV1T02 1TB                     | 1         | 2%      |
| Toshiba KXG6APNV2T04 2TB                     | 1         | 2%      |
| StoreJet Disk 4TB                            | 1         | 2%      |
| SK hynix NVMe SSD Drive 512GB                | 1         | 2%      |
| SK hynix BC511 NVMe 512GB                    | 1         | 2%      |
| Seagate ST9320325AS 320GB                    | 1         | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2%      |
| SanDisk SD5SG2256G1052E 256GB SSD            | 1         | 2%      |
| Samsung SSD 970 EVO 500GB                    | 1         | 2%      |
| Samsung SSD 870 QVO 2TB                      | 1         | 2%      |
| Samsung SSD 860 QVO 4TB                      | 1         | 2%      |
| Samsung SSD 860 EVO 500GB                    | 1         | 2%      |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB       | 1         | 2%      |
| Samsung PM9A1 NVMe SED 512GB                 | 1         | 2%      |
| Samsung PM991a NVMe 512GB                    | 1         | 2%      |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2%      |
| Samsung NVMe SSD Drive 1024GB                | 1         | 2%      |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 2%      |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 2%      |
| Samsung MZVL2512HCJQ-00BL7 512GB             | 1         | 2%      |
| Samsung MZNLN512HAJQ-000H1 512GB SSD         | 1         | 2%      |
| Samsung MZ7PD256HAFV-000H7 256GB SSD         | 1         | 2%      |
| LITEONIT LSS-24L6G 24GB SSD                  | 1         | 2%      |
| LITEON CV1-DB256 256GB SSD                   | 1         | 2%      |
| Lexar 512GB SSD                              | 1         | 2%      |
| Kingston SA400S37120G 120GB SSD              | 1         | 2%      |
| Kingston SA2000M81000G 1TB                   | 1         | 2%      |
| Kingston RBUSNS8180DS3256GJ 256GB SSD        | 1         | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 3         | 3      | 33.33%  |
| Seagate  | 2         | 2      | 22.22%  |
| Unknown  | 1         | 1      | 11.11%  |
| StoreJet | 1         | 1      | 11.11%  |
| Hitachi  | 1         | 1      | 11.11%  |
| Fujitsu  | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 41.18%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Kingston            | 2         | 2      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| LITEONIT            | 1         | 1      | 5.88%   |
| LITEON              | 1         | 1      | 5.88%   |
| Lexar               | 1         | 1      | 5.88%   |
| Dogfish             | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 17        | 21     | 41.46%  |
| SSD     | 14        | 18     | 34.15%  |
| HDD     | 7         | 9      | 17.07%  |
| Unknown | 2         | 2      | 4.88%   |
| MMC     | 1         | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 26     | 47.5%   |
| NVMe | 17        | 21     | 42.5%   |
| SAS  | 3         | 3      | 7.5%    |
| MMC  | 1         | 1      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 14     | 47.83%  |
| 0.51-1.0   | 8         | 8      | 34.78%  |
| 3.01-4.0   | 2         | 3      | 8.7%    |
| 1.01-2.0   | 2         | 2      | 8.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 14        | 41.18%  |
| 101-250        | 9         | 26.47%  |
| 501-1000       | 5         | 14.71%  |
| 2001-3000      | 2         | 5.88%   |
| 1001-2000      | 2         | 5.88%   |
| More than 3000 | 1         | 2.94%   |
| 51-100         | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 12        | 35.29%  |
| 21-50     | 6         | 17.65%  |
| 101-250   | 5         | 14.71%  |
| 51-100    | 4         | 11.76%  |
| 251-500   | 3         | 8.82%   |
| 1001-2000 | 2         | 5.88%   |
| 501-1000  | 2         | 5.88%   |

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
| Detected | 20        | 30     | 55.56%  |
| Works    | 16        | 21     | 44.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 50%     |
| Samsung Electronics          | 8         | 19.05%  |
| AMD                          | 5         | 11.9%   |
| Toshiba America Info Systems | 2         | 4.76%   |
| Kingston Technology Company  | 2         | 4.76%   |
| Union Memory (Shenzhen)      | 1         | 2.38%   |
| SK hynix                     | 1         | 2.38%   |
| Realtek Semiconductor        | 1         | 2.38%   |
| ADATA Technology             | 1         | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 11.11%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 8.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 6.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 4.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 4.44%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 4.44%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 4.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 4.44%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 4.44%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 2.22%   |
| SK hynix BC511                                                                         | 1         | 2.22%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 2.22%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 2.22%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 2.22%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 2.22%   |
| Intel SSD 660P Series                                                                  | 1         | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 2.22%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 2.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 2.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 2.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 2.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 2.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 2.22%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 48.84%  |
| NVMe | 17        | 39.53%  |
| IDE  | 4         | 9.3%    |
| RAID | 1         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 79.41%  |
| AMD    | 7         | 20.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 5.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 5.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.94%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 2.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.94%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 2.94%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 2.94%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 2.94%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 2.94%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2.94%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.94%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 2.94%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.94%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.94%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 2.94%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 2.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.94%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 2.94%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.94%   |
| Intel 12th Gen Core i5-1245U                  | 1         | 2.94%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 2.94%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.94%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 1         | 2.94%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 1         | 2.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.94%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.94%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 1         | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 13        | 38.24%  |
| Intel Core i5    | 8         | 23.53%  |
| Other            | 6         | 17.65%  |
| AMD Ryzen 5      | 3         | 8.82%   |
| Intel Core 2 Duo | 1         | 2.94%   |
| AMD Ryzen 7      | 1         | 2.94%   |
| AMD Ryzen 5 PRO  | 1         | 2.94%   |
| AMD A8           | 1         | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 15        | 44.12%  |
| 2      | 10        | 29.41%  |
| 6      | 4         | 11.76%  |
| 8      | 2         | 5.88%   |
| 12     | 1         | 2.94%   |
| 10     | 1         | 2.94%   |
| 1      | 1         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 88.24%  |
| 1      | 4         | 11.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 6         | 17.65%  |
| 0x806ec    | 4         | 11.76%  |
| 0x806c1    | 3         | 8.82%   |
| 0xa0652    | 2         | 5.88%   |
| 0x506e3    | 2         | 5.88%   |
| 0x206a7    | 2         | 5.88%   |
| 0x08600104 | 2         | 5.88%   |
| 0x906ea    | 1         | 2.94%   |
| 0x906a4    | 1         | 2.94%   |
| 0x906a3    | 1         | 2.94%   |
| 0x806e9    | 1         | 2.94%   |
| 0x406e3    | 1         | 2.94%   |
| 0x40651    | 1         | 2.94%   |
| 0x306a9    | 1         | 2.94%   |
| 0x10676    | 1         | 2.94%   |
| 0x0a50000d | 1         | 2.94%   |
| 0x0a50000c | 1         | 2.94%   |
| 0x08108102 | 1         | 2.94%   |
| 0x06006705 | 1         | 2.94%   |
| 0x06001116 | 1         | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 7         | 20.59%  |
| KabyLake         | 6         | 17.65%  |
| TigerLake        | 3         | 8.82%   |
| Skylake          | 3         | 8.82%   |
| Zen 3            | 2         | 5.88%   |
| Zen 2            | 2         | 5.88%   |
| SandyBridge      | 2         | 5.88%   |
| CometLake        | 2         | 5.88%   |
| Alderlake Hybrid | 2         | 5.88%   |
| Zen+             | 1         | 2.94%   |
| Piledriver       | 1         | 2.94%   |
| Penryn           | 1         | 2.94%   |
| IvyBridge        | 1         | 2.94%   |
| Excavator        | 1         | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 48.98%  |
| Nvidia | 17        | 34.69%  |
| AMD    | 8         | 16.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 8%      |
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 6%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 6%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 6%      |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 4%      |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 4%      |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 2%      |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 2%      |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 2%      |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 2%      |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 2%      |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 2%      |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 2%      |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 2%      |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 2%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 2%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 2%      |
| Intel HD Graphics 620                                                     | 1         | 2%      |
| Intel HD Graphics 530                                                     | 1         | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2%      |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 1         | 2%      |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 2%      |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 2%      |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 2%      |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 2%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 2%      |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 2%      |
| AMD Renoir                                                                | 1         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2%      |
| AMD Lexa XT [Radeon PRO WX 3200]                                          | 1         | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 2%      |
| AMD Barcelo                                                               | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 12        | 35.29%  |
| 1 x Intel      | 10        | 29.41%  |
| 1 x Nvidia     | 4         | 11.76%  |
| 1 x AMD        | 4         | 11.76%  |
| Intel + AMD    | 2         | 5.88%   |
| 2 x AMD        | 1         | 2.94%   |
| AMD + Nvidia   | 1         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 76.47%  |
| Proprietary | 7         | 20.59%  |
| Unknown     | 1         | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 50%     |
| 1.01-2.0   | 5         | 14.71%  |
| 0.01-0.5   | 5         | 14.71%  |
| 3.01-4.0   | 4         | 11.76%  |
| 5.01-6.0   | 2         | 5.88%   |
| 0.51-1.0   | 1         | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 9         | 18%     |
| LG Display          | 8         | 16%     |
| Samsung Electronics | 6         | 12%     |
| Chimei Innolux      | 5         | 10%     |
| Goldstar            | 4         | 8%      |
| Dell                | 4         | 8%      |
| BOE                 | 4         | 8%      |
| Philips             | 2         | 4%      |
| AOC                 | 2         | 4%      |
| Sharp               | 1         | 2%      |
| PANDA               | 1         | 2%      |
| Panasonic           | 1         | 2%      |
| Lenovo              | 1         | 2%      |
| Gigabyte Technology | 1         | 2%      |
| BenQ                | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 3.85%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.92%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.92%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 1.92%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.92%   |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 1.92%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.92%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.92%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.92%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.92%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.92%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.92%   |
| Gigabyte Technology G27QC A GBT2716 2560x1440 597x336mm 27.0-inch     | 1         | 1.92%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 1.92%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.92%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.92%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.92%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14E6 1366x768 309x173mm 13.9-inch       | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 1.92%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 51.16%  |
| 1366x768 (WXGA)    | 4         | 9.3%    |
| 3840x2160 (4K)     | 3         | 6.98%   |
| 1600x900 (HD+)     | 3         | 6.98%   |
| 2560x1440 (QHD)    | 2         | 4.65%   |
| 1920x1200 (WUXGA)  | 2         | 4.65%   |
| 1680x1050 (WSXGA+) | 2         | 4.65%   |
| 3840x1080          | 1         | 2.33%   |
| 3440x1440          | 1         | 2.33%   |
| 2560x1080          | 1         | 2.33%   |
| 2240x1400          | 1         | 2.33%   |
| Unknown            | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 18        | 36.73%  |
| 14     | 8         | 16.33%  |
| 27     | 6         | 12.24%  |
| 13     | 5         | 10.2%   |
| 21     | 3         | 6.12%   |
| 34     | 2         | 4.08%   |
| 24     | 2         | 4.08%   |
| 17     | 2         | 4.08%   |
| 49     | 1         | 2.04%   |
| 23     | 1         | 2.04%   |
| 22     | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 59.18%  |
| 501-600     | 8         | 16.33%  |
| 401-500     | 5         | 10.2%   |
| 701-800     | 2         | 4.08%   |
| 351-400     | 2         | 4.08%   |
| 201-300     | 2         | 4.08%   |
| 1001-1500   | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 79.49%  |
| 16/10 | 4         | 10.26%  |
| 21/9  | 2         | 5.13%   |
| 32/9  | 1         | 2.56%   |
| 3/2   | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 37.5%   |
| 81-90          | 12        | 25%     |
| 301-350        | 6         | 12.5%   |
| 201-250        | 5         | 10.42%  |
| 351-500        | 2         | 4.17%   |
| 121-130        | 2         | 4.17%   |
| 71-80          | 1         | 2.08%   |
| 151-200        | 1         | 2.08%   |
| 501-1000       | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 51.02%  |
| 101-120       | 10        | 20.41%  |
| 51-100        | 9         | 18.37%  |
| 161-240       | 3         | 6.12%   |
| More than 240 | 2         | 4.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 55.88%  |
| 2     | 10        | 29.41%  |
| 3     | 3         | 8.82%   |
| 4     | 1         | 2.94%   |
| 0     | 1         | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 52.83%  |
| Realtek Semiconductor | 17        | 32.08%  |
| Qualcomm Atheros      | 3         | 5.66%   |
| MediaTek              | 2         | 3.77%   |
| Ralink                | 1         | 1.89%   |
| D-Link                | 1         | 1.89%   |
| Broadcom              | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 17.91%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 7.46%   |
| Intel Wireless 7260                                               | 5         | 7.46%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 4.48%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 4.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.99%   |
| Intel Wireless 8260                                               | 2         | 2.99%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.99%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.99%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.49%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.49%   |
| Intel Wireless 7265                                               | 1         | 1.49%   |
| Intel Wireless 3160                                               | 1         | 1.49%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.49%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.49%   |
| Intel Centrino Wireless-N 135                                     | 1         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.49%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 1.49%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 82.35%  |
| Qualcomm Atheros      | 2         | 5.88%   |
| MediaTek              | 2         | 5.88%   |
| Realtek Semiconductor | 1         | 2.94%   |
| Ralink                | 1         | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 5         | 14.71%  |
| Intel Wi-Fi 6 AX200                                           | 3         | 8.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 3         | 8.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 5.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 5.88%   |
| Intel Wireless 8260                                           | 2         | 5.88%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 5.88%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 5.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 5.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 5.88%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 2.94%   |
| Intel Wireless 8265 / 8275                                    | 1         | 2.94%   |
| Intel Wireless 7265                                           | 1         | 2.94%   |
| Intel Wireless 3160                                           | 1         | 2.94%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 2.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.94%   |
| Intel Centrino Wireless-N 135                                 | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 53.13%  |
| Intel                 | 12        | 37.5%   |
| Qualcomm Atheros      | 1         | 3.13%   |
| D-Link                | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 36.36%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 15.15%  |
| Intel Ethernet Connection I217-LM                                 | 3         | 9.09%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.03%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.03%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 3.03%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.03%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 3.03%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 53.97%  |
| Ethernet | 29        | 46.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 70.27%  |
| Ethernet | 11        | 29.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 73.53%  |
| 1     | 8         | 23.53%  |
| 3     | 1         | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 73.53%  |
| Yes  | 9         | 26.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 73.33%  |
| Qualcomm Atheros Communications | 2         | 6.67%   |
| Foxconn / Hon Hai               | 2         | 6.67%   |
| Realtek Semiconductor           | 1         | 3.33%   |
| Ralink                          | 1         | 3.33%   |
| Hewlett-Packard                 | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 10        | 33.33%  |
| Intel AX201 Bluetooth                              | 5         | 16.67%  |
| Intel AX200 Bluetooth                              | 3         | 10%     |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 6.67%   |
| Foxconn / Hon Hai Wireless_Device                  | 2         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 3.33%   |
| Ralink RT3290 Bluetooth                            | 1         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 3.33%   |
| Intel Bluetooth Device                             | 1         | 3.33%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 3.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 27        | 50.94%  |
| Nvidia              | 11        | 20.75%  |
| AMD                 | 7         | 13.21%  |
| Logitech            | 2         | 3.77%   |
| GN Netcom           | 2         | 3.77%   |
| Hewlett-Packard     | 1         | 1.89%   |
| Creative Technology | 1         | 1.89%   |
| Conexant Systems    | 1         | 1.89%   |
| C-Media Electronics | 1         | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 9.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 7.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 6.25%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 4.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 4.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 4.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 3.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 3.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 3.13%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 3.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 3.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.56%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.56%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.56%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.56%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.56%   |
| Logitech Stereo H650e                                                      | 1         | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.56%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.56%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.56%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.56%   |
| GN Netcom Jabra EVOLVE 65                                                  | 1         | 1.56%   |
| Creative Technology Sound Blaster Play! 3                                  | 1         | 1.56%   |
| Conexant Systems HP Dock Audio                                             | 1         | 1.56%   |
| C-Media Electronics Lync USB Headset                                       | 1         | 1.56%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.56%   |
| AMD High Definition Audio Controller                                       | 1         | 1.56%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 35.29%  |
| SK hynix            | 4         | 23.53%  |
| Micron Technology   | 2         | 11.76%  |
| Magnum Tech         | 1         | 5.88%   |
| Lexar               | 1         | 5.88%   |
| Kingston            | 1         | 5.88%   |
| Crucial             | 1         | 5.88%   |
| A-DATA Technology   | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 5.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 5.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 5.88%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s   | 1         | 5.88%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 5.88%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1         | 5.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 5.88%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 5.88%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 5.88%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 5.88%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 5.88%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 5.88%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s          | 1         | 5.88%   |
| Lexar RAM LD4AS008G-H2666GST 8GB SODIMM DDR4 2667MT/s        | 1         | 5.88%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 5.88%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s   | 1         | 5.88%   |
| A-DATA RAM AO1P32NC8T1-BZ4SHD 8GB SODIMM DDR4 3200MT/s       | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 60%     |
| DDR3   | 4         | 26.67%  |
| LPDDR5 | 1         | 6.67%   |
| LPDDR4 | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 93.33%  |
| Row Of Chips | 1         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 68.75%  |
| 16384 | 2         | 12.5%   |
| 4096  | 2         | 12.5%   |
| 32768 | 1         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 5         | 31.25%  |
| 2667  | 5         | 31.25%  |
| 1600  | 3         | 18.75%  |
| 6400  | 1         | 6.25%   |
| 4266  | 1         | 6.25%   |
| 2133  | 1         | 6.25%   |

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
| Chicony Electronics                    | 7         | 21.88%  |
| Microdia                               | 4         | 12.5%   |
| IMC Networks                           | 4         | 12.5%   |
| Syntek                                 | 3         | 9.38%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Acer                                   | 2         | 6.25%   |
| Suyin                                  | 1         | 3.13%   |
| Sunplus Innovation Technology          | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| Logitech                               | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| Lenovo                                 | 1         | 3.13%   |
| Intel                                  | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| Apple                                  | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 12.5%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 9.38%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 6.25%   |
| Syntek Integrated Camera                                                   | 1         | 3.13%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 3.13%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.13%   |
| Realtek EasyCamera                                                         | 1         | 3.13%   |
| Quanta HP Webcam                                                           | 1         | 3.13%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 3.13%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 3.13%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 3.13%   |
| Lite-On HP HD Webcam                                                       | 1         | 3.13%   |
| Lenovo UVC Camera                                                          | 1         | 3.13%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 3.13%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 3.13%   |
| IMC Networks Integrated Camera                                             | 1         | 3.13%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 3.13%   |
| Chicony HP HD Camera                                                       | 1         | 3.13%   |
| Chicony HD WebCam                                                          | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.13%   |
| Apple iPhone5/5C/5S/6                                                      | 1         | 3.13%   |
| Acer Integrated RGB Camera                                                 | 1         | 3.13%   |
| Acer Integrated Camera                                                     | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 50%     |
| Synaptics             | 3         | 30%     |
| LighTuning Technology | 1         | 10%     |
| AuthenTec             | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 10%     |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 10%     |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 10%     |
| AuthenTec AES2810                                          | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Broadcom    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader  | 2         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 25%     |
| Broadcom 58200                       | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 44.12%  |
| 1     | 14        | 41.18%  |
| 2     | 5         | 14.71%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 41.67%  |
| Graphics card         | 5         | 20.83%  |
| Chipcard              | 3         | 12.5%   |
| Net/wireless          | 2         | 8.33%   |
| Net/ethernet          | 1         | 4.17%   |
| Multimedia controller | 1         | 4.17%   |
| Card reader           | 1         | 4.17%   |
| Bluetooth             | 1         | 4.17%   |

