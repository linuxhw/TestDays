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

Total: 36

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 8.5 | 11        | 39.29%  |
| Rocky Linux 9.0 | 8         | 28.57%  |
| Rocky Linux 8.4 | 8         | 28.57%  |
| Rocky Linux 8.3 | 1         | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 28        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-70.22.1.el9_0.x86_64  | 4         | 14.29%  |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 10.71%  |
| 5.14.0-70.26.1.el9_0.x86_64  | 2         | 7.14%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 2         | 7.14%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 7.14%   |
| 4.18.0-305.el8.x86_64        | 2         | 7.14%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 7.14%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 2         | 7.14%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2         | 7.14%   |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 3.57%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 1         | 3.57%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 1         | 3.57%   |
| 5.10.89-1.el8.x86_64         | 1         | 3.57%   |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 3.57%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 3.57%   |
| 4.18.0-240.22.1.el8.x86_64   | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 18        | 64.29%  |
| 5.14.0  | 8         | 28.57%  |
| 5.4.157 | 1         | 3.57%   |
| 5.10.89 | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 18        | 64.29%  |
| 5.14    | 8         | 28.57%  |
| 5.4     | 1         | 3.57%   |
| 5.10    | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 21        | 75%     |
| MATE          | 3         | 10.71%  |
| XFCE          | 1         | 3.57%   |
| X-Cinnamon    | 1         | 3.57%   |
| KDE5          | 1         | 3.57%   |
| GNOME Classic | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 17        | 60.71%  |
| X11     | 11        | 39.29%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 64.29%  |
| GDM     | 7         | 25%     |
| LightDM | 2         | 7.14%   |
| SDDM    | 1         | 3.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 67.86%  |
| ru_RU | 2         | 7.14%   |
| en_ZA | 2         | 7.14%   |
| de_DE | 2         | 7.14%   |
| pt_BR | 1         | 3.57%   |
| it_IT | 1         | 3.57%   |
| en_CA | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 20        | 71.43%  |
| BIOS | 8         | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 21        | 75%     |
| Ext4 | 6         | 21.43%  |
| Ext3 | 1         | 3.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 67.86%  |
| GPT     | 7         | 25%     |
| MBR     | 2         | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 89.29%  |
| Yes       | 3         | 10.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 85.71%  |
| Yes       | 4         | 14.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 39.29%  |
| Hewlett-Packard  | 6         | 21.43%  |
| Dell             | 4         | 14.29%  |
| ASUSTek Computer | 3         | 10.71%  |
| Toshiba          | 2         | 7.14%   |
| BANGHO           | 1         | 3.57%   |
| Acer             | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 3.57%   |
| Toshiba Satellite E45-B                  | 1         | 3.57%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 3.57%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 3.57%   |
| Lenovo ThinkPad W500 406132G             | 1         | 3.57%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 3.57%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 3.57%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 3.57%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 3.57%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 3.57%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 3.57%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 3.57%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 3.57%   |
| HP ZBook 15u G6                          | 1         | 3.57%   |
| HP ZBook 15 G3                           | 1         | 3.57%   |
| HP ZBook 15 G2                           | 1         | 3.57%   |
| HP Pavilion g6                           | 1         | 3.57%   |
| HP Laptop 17-ca1xxx                      | 1         | 3.57%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 3.57%   |
| Dell XPS 15 7590                         | 1         | 3.57%   |
| Dell Latitude 5500                       | 1         | 3.57%   |
| Dell Latitude 5430                       | 1         | 3.57%   |
| Dell Latitude 3420                       | 1         | 3.57%   |
| BANGHO BES G1529                         | 1         | 3.57%   |
| ASUS VivoBook_ASUSLaptop X512FL_X512FL   | 1         | 3.57%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 3.57%   |
| ASUS ASUS TUF Dash F15 FX516PM_FX516PM   | 1         | 3.57%   |
| Acer Aspire VN7-591G                     | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 17.86%  |
| Lenovo IdeaPad    | 4         | 14.29%  |
| HP ZBook          | 3         | 10.71%  |
| Dell Latitude     | 3         | 10.71%  |
| Lenovo Legion     | 2         | 7.14%   |
| ASUS ASUS         | 2         | 7.14%   |
| Toshiba TECRA     | 1         | 3.57%   |
| Toshiba Satellite | 1         | 3.57%   |
| HP Pavilion       | 1         | 3.57%   |
| HP Laptop         | 1         | 3.57%   |
| HP EliteBook      | 1         | 3.57%   |
| Dell XPS          | 1         | 3.57%   |
| BANGHO BES        | 1         | 3.57%   |
| ASUS VivoBook     | 1         | 3.57%   |
| Acer Aspire       | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 21.43%  |
| 2020 | 4         | 14.29%  |
| 2014 | 4         | 14.29%  |
| 2021 | 3         | 10.71%  |
| 2016 | 2         | 7.14%   |
| 2015 | 2         | 7.14%   |
| 2011 | 2         | 7.14%   |
| 2022 | 1         | 3.57%   |
| 2018 | 1         | 3.57%   |
| 2013 | 1         | 3.57%   |
| 2012 | 1         | 3.57%   |
| 2009 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 28        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 92.86%  |
| Enabled  | 2         | 7.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 10        | 35.71%  |
| 4.01-8.0   | 7         | 25%     |
| 32.01-64.0 | 5         | 17.86%  |
| 16.01-24.0 | 5         | 17.86%  |
| 3.01-4.0   | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 9         | 32.14%  |
| 4.01-8.0  | 6         | 21.43%  |
| 2.01-3.0  | 6         | 21.43%  |
| 1.01-2.0  | 4         | 14.29%  |
| 8.01-16.0 | 3         | 10.71%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 71.43%  |
| 2      | 5         | 17.86%  |
| 3      | 3         | 10.71%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 82.14%  |
| Yes       | 5         | 17.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 89.29%  |
| No        | 3         | 10.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 89.29%  |
| No        | 3         | 10.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 6         | 21.43%  |
| South Africa | 2         | 7.14%   |
| Russia       | 2         | 7.14%   |
| Germany      | 2         | 7.14%   |
| Czechia      | 2         | 7.14%   |
| Belgium      | 2         | 7.14%   |
| Turkey       | 1         | 3.57%   |
| Sweden       | 1         | 3.57%   |
| Slovakia     | 1         | 3.57%   |
| Poland       | 1         | 3.57%   |
| Netherlands  | 1         | 3.57%   |
| Malaysia     | 1         | 3.57%   |
| Kazakhstan   | 1         | 3.57%   |
| Italy        | 1         | 3.57%   |
| China        | 1         | 3.57%   |
| Canada       | 1         | 3.57%   |
| Brazil       | 1         | 3.57%   |
| Argentina    | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Žilina                | 1         | 3.57%   |
| Xi'an                  | 1         | 3.57%   |
| Smolensk               | 1         | 3.57%   |
| Senigallia             | 1         | 3.57%   |
| Scarborough            | 1         | 3.57%   |
| San Miguel de Tucumán | 1         | 3.57%   |
| Prague                 | 1         | 3.57%   |
| Philadelphia           | 1         | 3.57%   |
| Ottignies              | 1         | 3.57%   |
| Örebro                | 1         | 3.57%   |
| Oakley                 | 1         | 3.57%   |
| Nur-Sultan             | 1         | 3.57%   |
| Mugla                  | 1         | 3.57%   |
| Mossel Bay             | 1         | 3.57%   |
| Moscow                 | 1         | 3.57%   |
| Montreal               | 1         | 3.57%   |
| Kutno                  | 1         | 3.57%   |
| Johor Bahru            | 1         | 3.57%   |
| Jaú                   | 1         | 3.57%   |
| Houston                | 1         | 3.57%   |
| Forest                 | 1         | 3.57%   |
| Enschede               | 1         | 3.57%   |
| Dreieich               | 1         | 3.57%   |
| Centurion              | 1         | 3.57%   |
| Brussels               | 1         | 3.57%   |
| Brno                   | 1         | 3.57%   |
| Berlin                 | 1         | 3.57%   |
| Ashburn                | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 12        | 14     | 29.27%  |
| Kingston                | 4         | 4      | 9.76%   |
| WDC                     | 3         | 3      | 7.32%   |
| Toshiba                 | 3         | 3      | 7.32%   |
| Unknown                 | 2         | 2      | 4.88%   |
| Seagate                 | 2         | 2      | 4.88%   |
| Union Memory (Shenzhen) | 1         | 1      | 2.44%   |
| UMIS                    | 1         | 1      | 2.44%   |
| StoreJet                | 1         | 1      | 2.44%   |
| SK hynix                | 1         | 2      | 2.44%   |
| SanDisk                 | 1         | 1      | 2.44%   |
| LITEONIT                | 1         | 1      | 2.44%   |
| LITEON                  | 1         | 1      | 2.44%   |
| Intel                   | 1         | 1      | 2.44%   |
| HS-SSD-C100             | 1         | 1      | 2.44%   |
| Hitachi                 | 1         | 1      | 2.44%   |
| Fujitsu                 | 1         | 1      | 2.44%   |
| Dogfish                 | 1         | 1      | 2.44%   |
| AGI                     | 1         | 1      | 2.44%   |
| ADATA Technology        | 1         | 1      | 2.44%   |
| A-DATA Technology       | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD             | 1         | 2.33%   |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 2.33%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 2.33%   |
| Unknown SD/MMC/MS PRO 1TB                    | 1         | 2.33%   |
| Unknown MMC Card  64GB                       | 1         | 2.33%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.33%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 2.33%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 2.33%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 2.33%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2.33%   |
| StoreJet Disk 2TB                            | 1         | 2.33%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 2.33%   |
| SK hynix BC511 NVMe 512GB                    | 1         | 2.33%   |
| Seagate ST9320325AS 320GB                    | 1         | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2.33%   |
| SanDisk SD5SG2256G1052E 256GB SSD            | 1         | 2.33%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 2.33%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 2.33%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 2.33%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 2.33%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 2.33%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB       | 1         | 2.33%   |
| Samsung PM9A1 NVMe SED 512GB                 | 1         | 2.33%   |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2.33%   |
| Samsung NVMe SSD Drive 1024GB                | 1         | 2.33%   |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 2.33%   |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 2.33%   |
| Samsung MZNLN512HAJQ-000H1 512GB SSD         | 1         | 2.33%   |
| Samsung MZ7PD256HAFV-000H7 256GB SSD         | 1         | 2.33%   |
| LITEONIT LSS-24L6G 24GB SSD                  | 1         | 2.33%   |
| LITEON CV1-DB256 256GB SSD                   | 1         | 2.33%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 2.33%   |
| Kingston SA2000M81000G 1TB                   | 1         | 2.33%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD        | 1         | 2.33%   |
| Kingston NVMe SSD Drive 512GB                | 1         | 2.33%   |
| Intel NVMe SSD Drive 512GB                   | 1         | 2.33%   |
| HS-SSD-C100 240G                             | 1         | 2.33%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 2.33%   |
| Fujitsu MHV2080BH 80GB                       | 1         | 2.33%   |
| Dogfish SSD 2TB                              | 1         | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 25%     |
| Seagate  | 2         | 2      | 25%     |
| Unknown  | 1         | 1      | 12.5%   |
| StoreJet | 1         | 1      | 12.5%   |
| Hitachi  | 1         | 1      | 12.5%   |
| Fujitsu  | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 40%     |
| Toshiba             | 2         | 2      | 13.33%  |
| Kingston            | 2         | 2      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| LITEONIT            | 1         | 1      | 6.67%   |
| LITEON              | 1         | 1      | 6.67%   |
| Dogfish             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 14        | 17     | 40%     |
| SSD     | 12        | 16     | 34.29%  |
| HDD     | 6         | 8      | 17.14%  |
| Unknown | 2         | 2      | 5.71%   |
| MMC     | 1         | 1      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 23     | 47.06%  |
| NVMe | 14        | 17     | 41.18%  |
| SAS  | 3         | 3      | 8.82%   |
| MMC  | 1         | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 12     | 45%     |
| 0.51-1.0   | 7         | 7      | 35%     |
| 1.01-2.0   | 3         | 3      | 15%     |
| 3.01-4.0   | 1         | 2      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 10        | 35.71%  |
| 101-250        | 9         | 32.14%  |
| 501-1000       | 3         | 10.71%  |
| 2001-3000      | 2         | 7.14%   |
| 1001-2000      | 2         | 7.14%   |
| More than 3000 | 1         | 3.57%   |
| 51-100         | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 10        | 35.71%  |
| 21-50     | 5         | 17.86%  |
| 101-250   | 5         | 17.86%  |
| 251-500   | 2         | 7.14%   |
| 1001-2000 | 2         | 7.14%   |
| 501-1000  | 2         | 7.14%   |
| 51-100    | 2         | 7.14%   |

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
| Detected | 19        | 29     | 63.33%  |
| Works    | 11        | 15     | 36.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 18        | 51.43%  |
| Samsung Electronics          | 6         | 17.14%  |
| AMD                          | 4         | 11.43%  |
| Kingston Technology Company  | 2         | 5.71%   |
| Union Memory (Shenzhen)      | 1         | 2.86%   |
| Toshiba America Info Systems | 1         | 2.86%   |
| SK hynix                     | 1         | 2.86%   |
| Realtek Semiconductor        | 1         | 2.86%   |
| ADATA Technology             | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 10.53%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 4         | 10.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 7.89%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 5.26%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 2.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 2.63%   |
| SK hynix BC511                                                                         | 1         | 2.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 2.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 2.63%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 2.63%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 2.63%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 2.63%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 2.63%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 2.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 2.63%   |
| Intel SSD 660P Series                                                                  | 1         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 2.63%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 2.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 2.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 2.63%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 47.22%  |
| NVMe | 14        | 38.89%  |
| IDE  | 4         | 11.11%  |
| RAID | 1         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 78.57%  |
| AMD    | 6         | 21.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 7.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 3.57%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 3.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.57%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 3.57%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 3.57%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 3.57%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 3.57%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 3.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.57%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 3.57%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 3.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.57%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 3.57%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 3.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 3.57%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 3.57%   |
| Intel 12th Gen Core i5-1245U                  | 1         | 3.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.57%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 3.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.57%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 1         | 3.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 3.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.57%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.57%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 12        | 42.86%  |
| Intel Core i5    | 6         | 21.43%  |
| Other            | 4         | 14.29%  |
| AMD Ryzen 5      | 2         | 7.14%   |
| Intel Core 2 Duo | 1         | 3.57%   |
| AMD Ryzen 7      | 1         | 3.57%   |
| AMD Ryzen 5 PRO  | 1         | 3.57%   |
| AMD A8           | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 14        | 50%     |
| 2      | 8         | 28.57%  |
| 6      | 4         | 14.29%  |
| 10     | 1         | 3.57%   |
| 8      | 1         | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 89.29%  |
| 1      | 3         | 10.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 6         | 21.43%  |
| 0x806ec    | 4         | 14.29%  |
| 0x806c1    | 2         | 7.14%   |
| 0x506e3    | 2         | 7.14%   |
| 0x08600104 | 2         | 7.14%   |
| 0xa0652    | 1         | 3.57%   |
| 0x906ea    | 1         | 3.57%   |
| 0x906a4    | 1         | 3.57%   |
| 0x406e3    | 1         | 3.57%   |
| 0x40651    | 1         | 3.57%   |
| 0x306a9    | 1         | 3.57%   |
| 0x206a7    | 1         | 3.57%   |
| 0x10676    | 1         | 3.57%   |
| 0x0a50000c | 1         | 3.57%   |
| 0x08108102 | 1         | 3.57%   |
| 0x06006705 | 1         | 3.57%   |
| 0x06001116 | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 7         | 25%     |
| KabyLake         | 5         | 17.86%  |
| Skylake          | 3         | 10.71%  |
| Zen 2            | 2         | 7.14%   |
| TigerLake        | 2         | 7.14%   |
| Zen+             | 1         | 3.57%   |
| Zen 3            | 1         | 3.57%   |
| SandyBridge      | 1         | 3.57%   |
| Piledriver       | 1         | 3.57%   |
| Penryn           | 1         | 3.57%   |
| IvyBridge        | 1         | 3.57%   |
| Excavator        | 1         | 3.57%   |
| CometLake        | 1         | 3.57%   |
| Alderlake Hybrid | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 45.24%  |
| Nvidia | 16        | 38.1%   |
| AMD    | 7         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 9.3%    |
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 6.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 6.98%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 4.65%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 2.33%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 2.33%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 2.33%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 2.33%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 2.33%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 2.33%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 2.33%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 2.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 2.33%   |
| Intel VGA compatible controller                                           | 1         | 2.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 2.33%   |
| Intel HD Graphics 530                                                     | 1         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 2.33%   |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 2.33%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 2.33%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 2.33%   |
| AMD Renoir                                                                | 1         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2.33%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                          | 1         | 2.33%   |
| AMD Cezanne                                                               | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 11        | 39.29%  |
| 1 x Intel      | 6         | 21.43%  |
| 1 x Nvidia     | 4         | 14.29%  |
| 1 x AMD        | 3         | 10.71%  |
| Intel + AMD    | 2         | 7.14%   |
| 2 x AMD        | 1         | 3.57%   |
| AMD + Nvidia   | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 71.43%  |
| Proprietary | 7         | 25%     |
| Unknown     | 1         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 42.86%  |
| 1.01-2.0   | 5         | 17.86%  |
| 3.01-4.0   | 4         | 14.29%  |
| 0.01-0.5   | 4         | 14.29%  |
| 5.01-6.0   | 2         | 7.14%   |
| 0.51-1.0   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 7         | 17.07%  |
| AU Optronics        | 7         | 17.07%  |
| Goldstar            | 4         | 9.76%   |
| Dell                | 4         | 9.76%   |
| Chimei Innolux      | 4         | 9.76%   |
| BOE                 | 4         | 9.76%   |
| Samsung Electronics | 3         | 7.32%   |
| Philips             | 2         | 4.88%   |
| AOC                 | 2         | 4.88%   |
| Sharp               | 1         | 2.44%   |
| PANDA               | 1         | 2.44%   |
| Panasonic           | 1         | 2.44%   |
| Lenovo              | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 4.65%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 2.33%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 2.33%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 2.33%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 2.33%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 2.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 2.33%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 2.33%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 2.33%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 2.33%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 2.33%   |
| Goldstar W2252 GSM567D 1680x1050 490x320mm 23.0-inch                  | 1         | 2.33%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 2.33%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 2.33%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 2.33%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 2.33%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 2.33%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 2.33%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 2.33%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14E6 1366x768 309x173mm 13.9-inch       | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 2.33%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 2.33%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 2.33%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 2.33%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 2.33%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 19        | 54.29%  |
| 1600x900 (HD+)     | 3         | 8.57%   |
| 1366x768 (WXGA)    | 3         | 8.57%   |
| 3840x2160 (4K)     | 2         | 5.71%   |
| 1680x1050 (WSXGA+) | 2         | 5.71%   |
| 3840x1080          | 1         | 2.86%   |
| 3440x1440          | 1         | 2.86%   |
| 2560x1440 (QHD)    | 1         | 2.86%   |
| 2560x1080          | 1         | 2.86%   |
| 1920x1200 (WUXGA)  | 1         | 2.86%   |
| Unknown            | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 39.02%  |
| 14     | 7         | 17.07%  |
| 27     | 5         | 12.2%   |
| 21     | 3         | 7.32%   |
| 34     | 2         | 4.88%   |
| 17     | 2         | 4.88%   |
| 13     | 2         | 4.88%   |
| 49     | 1         | 2.44%   |
| 24     | 1         | 2.44%   |
| 23     | 1         | 2.44%   |
| 22     | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 60.98%  |
| 501-600     | 6         | 14.63%  |
| 401-500     | 5         | 12.2%   |
| 701-800     | 2         | 4.88%   |
| 351-400     | 2         | 4.88%   |
| 1001-1500   | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 81.25%  |
| 21/9  | 2         | 6.25%   |
| 16/10 | 2         | 6.25%   |
| 32/9  | 1         | 3.13%   |
| 3/2   | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 40%     |
| 81-90          | 9         | 22.5%   |
| 301-350        | 5         | 12.5%   |
| 201-250        | 4         | 10%     |
| 351-500        | 2         | 5%      |
| 121-130        | 2         | 5%      |
| 151-200        | 1         | 2.5%    |
| 501-1000       | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 57.5%   |
| 101-120       | 8         | 20%     |
| 51-100        | 7         | 17.5%   |
| More than 240 | 1         | 2.5%    |
| 161-240       | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 15        | 53.57%  |
| 2     | 9         | 32.14%  |
| 3     | 2         | 7.14%   |
| 4     | 1         | 3.57%   |
| 0     | 1         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 55.81%  |
| Realtek Semiconductor | 14        | 32.56%  |
| Qualcomm Atheros      | 2         | 4.65%   |
| Ralink                | 1         | 2.33%   |
| MediaTek              | 1         | 2.33%   |
| Broadcom              | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 20%     |
| Intel Wireless 7260                                               | 5         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.45%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 5.45%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 5.45%   |
| Intel Wireless 8260                                               | 2         | 3.64%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.64%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 3.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 3.64%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.82%   |
| Intel Wireless 7265                                               | 1         | 1.82%   |
| Intel Wireless 3160                                               | 1         | 1.82%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.82%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.82%   |
| Intel Centrino Wireless-N 135                                     | 1         | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.82%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 85.71%  |
| Realtek Semiconductor | 1         | 3.57%   |
| Ralink                | 1         | 3.57%   |
| Qualcomm Atheros      | 1         | 3.57%   |
| MediaTek              | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 5         | 17.86%  |
| Intel Wi-Fi 6 AX200                                           | 3         | 10.71%  |
| Intel Wireless 8260                                           | 2         | 7.14%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 7.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 7.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 7.14%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 3.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 3.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 3.57%   |
| Intel Wireless 7265                                           | 1         | 3.57%   |
| Intel Wireless 3160                                           | 1         | 3.57%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 3.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 3.57%   |
| Intel Centrino Wireless-N 135                                 | 1         | 3.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 53.85%  |
| Intel                 | 10        | 38.46%  |
| Qualcomm Atheros      | 1         | 3.85%   |
| Broadcom              | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 40.74%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 11.11%  |
| Intel Ethernet Connection I217-LM                                 | 3         | 11.11%  |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 7.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.7%    |
| Intel Ethernet Connection I217-V                                  | 1         | 3.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.7%    |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.7%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.7%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 53.85%  |
| Ethernet | 24        | 46.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 70.97%  |
| Ethernet | 9         | 29.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 78.57%  |
| 1     | 5         | 17.86%  |
| 3     | 1         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 71.43%  |
| Yes  | 8         | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 80%     |
| Realtek Semiconductor           | 1         | 4%      |
| Ralink                          | 1         | 4%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Broadcom                        | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 10        | 40%     |
| Intel AX201 Bluetooth                              | 4         | 16%     |
| Intel AX200 Bluetooth                              | 3         | 12%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 8%      |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 4%      |
| Ralink RT3290 Bluetooth                            | 1         | 4%      |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 4%      |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 4%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 22        | 48.89%  |
| Nvidia              | 10        | 22.22%  |
| AMD                 | 6         | 13.33%  |
| Logitech            | 2         | 4.44%   |
| Hewlett-Packard     | 1         | 2.22%   |
| GN Netcom           | 1         | 2.22%   |
| Creative Technology | 1         | 2.22%   |
| Conexant Systems    | 1         | 2.22%   |
| C-Media Electronics | 1         | 2.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 10.91%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 7.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 7.27%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 5.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 5.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 3.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 3.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 3.64%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 3.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.82%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.82%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.82%   |
| Logitech Stereo H650e                                                      | 1         | 1.82%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.82%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.82%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.82%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.82%   |
| GN Netcom Jabra EVOLVE 65                                                  | 1         | 1.82%   |
| Creative Technology Sound Blaster Play! 3                                  | 1         | 1.82%   |
| Conexant Systems HP Dock Audio                                             | 1         | 1.82%   |
| C-Media Electronics Lync USB Headset                                       | 1         | 1.82%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.82%   |
| AMD High Definition Audio Controller                                       | 1         | 1.82%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 36.36%  |
| SK hynix            | 2         | 18.18%  |
| Micron Technology   | 2         | 18.18%  |
| Magnum Tech         | 1         | 9.09%   |
| Kingston            | 1         | 9.09%   |
| Crucial             | 1         | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 9.09%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s | 1         | 9.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 9.09%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 9.09%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 9.09%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 9.09%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 1         | 9.09%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s      | 1         | 9.09%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s        | 1         | 9.09%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s     | 1         | 9.09%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 5         | 50%     |
| DDR3   | 4         | 40%     |
| LPDDR4 | 1         | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 10        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 72.73%  |
| 16384 | 2         | 18.18%  |
| 4096  | 1         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 4         | 40%     |
| 1600  | 3         | 30%     |
| 3200  | 2         | 20%     |
| 4266  | 1         | 10%     |

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
| Chicony Electronics                    | 6         | 22.22%  |
| Syntek                                 | 3         | 11.11%  |
| IMC Networks                           | 3         | 11.11%  |
| Realtek Semiconductor                  | 2         | 7.41%   |
| Microdia                               | 2         | 7.41%   |
| Suyin                                  | 1         | 3.7%    |
| Sunplus Innovation Technology          | 1         | 3.7%    |
| Quanta                                 | 1         | 3.7%    |
| Luxvisions Innotech Limited            | 1         | 3.7%    |
| Logitech                               | 1         | 3.7%    |
| Lite-On Technology                     | 1         | 3.7%    |
| Lenovo                                 | 1         | 3.7%    |
| Intel                                  | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.7%    |
| Apple                                  | 1         | 3.7%    |
| Acer                                   | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 14.81%  |
| Syntek Lenovo EasyCamera                                                   | 2         | 7.41%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 7.41%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 7.41%   |
| Syntek Integrated Camera                                                   | 1         | 3.7%    |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 3.7%    |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 3.7%    |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.7%    |
| Realtek EasyCamera                                                         | 1         | 3.7%    |
| Quanta HP Webcam                                                           | 1         | 3.7%    |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 3.7%    |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 3.7%    |
| Lite-On HP HD Webcam                                                       | 1         | 3.7%    |
| Lenovo UVC Camera                                                          | 1         | 3.7%    |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 3.7%    |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 3.7%    |
| Chicony HP HD Camera                                                       | 1         | 3.7%    |
| Chicony HD WebCam                                                          | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.7%    |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 3.7%    |
| Acer Integrated Camera                                                     | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 50%     |
| Synaptics             | 2         | 25%     |
| LighTuning Technology | 1         | 12.5%   |
| AuthenTec             | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 25%     |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 12.5%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 12.5%   |
| LighTuning EgisTec_ES603                                   | 1         | 12.5%   |
| AuthenTec AES2810                                          | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 33.33%  |
| Broadcom 58200                       | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 14        | 50%     |
| 0     | 11        | 39.29%  |
| 2     | 3         | 10.71%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 40%     |
| Graphics card         | 4         | 20%     |
| Net/wireless          | 2         | 10%     |
| Chipcard              | 2         | 10%     |
| Net/ethernet          | 1         | 5%      |
| Multimedia controller | 1         | 5%      |
| Card reader           | 1         | 5%      |
| Bluetooth             | 1         | 5%      |

