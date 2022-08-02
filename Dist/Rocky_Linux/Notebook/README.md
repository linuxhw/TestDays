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

Total: 30

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 8.5 | 11        | 50%     |
| Rocky Linux 8.4 | 8         | 36.36%  |
| Rocky Linux 9.0 | 2         | 9.09%   |
| Rocky Linux 8.3 | 1         | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 22        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 13.64%  |
| 4.18.0-348.20.1.el8_5.x86_64 | 2         | 9.09%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 9.09%   |
| 4.18.0-305.el8.x86_64        | 2         | 9.09%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 9.09%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 2         | 9.09%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2         | 9.09%   |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 4.55%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 1         | 4.55%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 1         | 4.55%   |
| 5.10.89-1.el8.x86_64         | 1         | 4.55%   |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 4.55%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 4.55%   |
| 4.18.0-240.22.1.el8.x86_64   | 1         | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 18        | 81.82%  |
| 5.14.0  | 2         | 9.09%   |
| 5.4.157 | 1         | 4.55%   |
| 5.10.89 | 1         | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 18        | 81.82%  |
| 5.14    | 2         | 9.09%   |
| 5.4     | 1         | 4.55%   |
| 5.10    | 1         | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 16        | 72.73%  |
| MATE          | 2         | 9.09%   |
| XFCE          | 1         | 4.55%   |
| X-Cinnamon    | 1         | 4.55%   |
| KDE5          | 1         | 4.55%   |
| GNOME Classic | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 12        | 54.55%  |
| X11     | 10        | 45.45%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 68.18%  |
| GDM     | 4         | 18.18%  |
| LightDM | 2         | 9.09%   |
| SDDM    | 1         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 15        | 68.18%  |
| en_ZA | 2         | 9.09%   |
| de_DE | 2         | 9.09%   |
| ru_RU | 1         | 4.55%   |
| pt_BR | 1         | 4.55%   |
| it_IT | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 15        | 68.18%  |
| BIOS | 7         | 31.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 16        | 72.73%  |
| Ext4 | 6         | 27.27%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 72.73%  |
| GPT     | 5         | 22.73%  |
| MBR     | 1         | 4.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 95.45%  |
| Yes       | 1         | 4.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 86.36%  |
| Yes       | 3         | 13.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 50%     |
| Hewlett-Packard  | 4         | 18.18%  |
| Toshiba          | 2         | 9.09%   |
| Dell             | 2         | 9.09%   |
| ASUSTek Computer | 2         | 9.09%   |
| Acer             | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 4.55%   |
| Toshiba Satellite E45-B                  | 1         | 4.55%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 4.55%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 4.55%   |
| Lenovo ThinkPad W500 406132G             | 1         | 4.55%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 4.55%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 4.55%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 4.55%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 4.55%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 4.55%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 4.55%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 4.55%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 4.55%   |
| HP ZBook 15 G3                           | 1         | 4.55%   |
| HP ZBook 15 G2                           | 1         | 4.55%   |
| HP Laptop 17-ca1xxx                      | 1         | 4.55%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 4.55%   |
| Dell Latitude 5500                       | 1         | 4.55%   |
| Dell Latitude 3420                       | 1         | 4.55%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 4.55%   |
| ASUS ASUS TUF Dash F15 FX516PM_FX516PM   | 1         | 4.55%   |
| Acer Aspire VN7-591G                     | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 22.73%  |
| Lenovo IdeaPad    | 4         | 18.18%  |
| Lenovo Legion     | 2         | 9.09%   |
| HP ZBook          | 2         | 9.09%   |
| Dell Latitude     | 2         | 9.09%   |
| ASUS ASUS         | 2         | 9.09%   |
| Toshiba TECRA     | 1         | 4.55%   |
| Toshiba Satellite | 1         | 4.55%   |
| HP Laptop         | 1         | 4.55%   |
| HP EliteBook      | 1         | 4.55%   |
| Acer Aspire       | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 4         | 18.18%  |
| 2021 | 3         | 13.64%  |
| 2019 | 3         | 13.64%  |
| 2014 | 3         | 13.64%  |
| 2016 | 2         | 9.09%   |
| 2015 | 2         | 9.09%   |
| 2018 | 1         | 4.55%   |
| 2013 | 1         | 4.55%   |
| 2012 | 1         | 4.55%   |
| 2011 | 1         | 4.55%   |
| 2009 | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 22        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 22        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 7         | 31.82%  |
| 4.01-8.0   | 5         | 22.73%  |
| 16.01-24.0 | 5         | 22.73%  |
| 32.01-64.0 | 4         | 18.18%  |
| 3.01-4.0   | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 8         | 36.36%  |
| 4.01-8.0  | 6         | 27.27%  |
| 2.01-3.0  | 4         | 18.18%  |
| 1.01-2.0  | 3         | 13.64%  |
| 8.01-16.0 | 1         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 15        | 68.18%  |
| 2      | 4         | 18.18%  |
| 3      | 3         | 13.64%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 86.36%  |
| Yes       | 3         | 13.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 95.45%  |
| No        | 1         | 4.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 90.91%  |
| No        | 2         | 9.09%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 6         | 27.27%  |
| South Africa | 2         | 9.09%   |
| Germany      | 2         | 9.09%   |
| Belgium      | 2         | 9.09%   |
| Sweden       | 1         | 4.55%   |
| Slovakia     | 1         | 4.55%   |
| Russia       | 1         | 4.55%   |
| Poland       | 1         | 4.55%   |
| Malaysia     | 1         | 4.55%   |
| Kazakhstan   | 1         | 4.55%   |
| Italy        | 1         | 4.55%   |
| Czechia      | 1         | 4.55%   |
| China        | 1         | 4.55%   |
| Brazil       | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Žilina      | 1         | 4.55%   |
| Xi'an        | 1         | 4.55%   |
| Smolensk     | 1         | 4.55%   |
| Senigallia   | 1         | 4.55%   |
| Scarborough  | 1         | 4.55%   |
| Prague       | 1         | 4.55%   |
| Philadelphia | 1         | 4.55%   |
| Ottignies    | 1         | 4.55%   |
| Örebro      | 1         | 4.55%   |
| Oakley       | 1         | 4.55%   |
| Nur-Sultan   | 1         | 4.55%   |
| Mossel Bay   | 1         | 4.55%   |
| Kutno        | 1         | 4.55%   |
| Johor Bahru  | 1         | 4.55%   |
| Jaú         | 1         | 4.55%   |
| Houston      | 1         | 4.55%   |
| Forest       | 1         | 4.55%   |
| Dreieich     | 1         | 4.55%   |
| Centurion    | 1         | 4.55%   |
| Brussels     | 1         | 4.55%   |
| Berlin       | 1         | 4.55%   |
| Ashburn      | 1         | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 10        | 12     | 29.41%  |
| Toshiba                 | 3         | 3      | 8.82%   |
| WDC                     | 2         | 2      | 5.88%   |
| Unknown                 | 2         | 2      | 5.88%   |
| Kingston                | 2         | 2      | 5.88%   |
| Union Memory (Shenzhen) | 1         | 1      | 2.94%   |
| UMIS                    | 1         | 1      | 2.94%   |
| StoreJet                | 1         | 1      | 2.94%   |
| SK hynix                | 1         | 2      | 2.94%   |
| Seagate                 | 1         | 1      | 2.94%   |
| SanDisk                 | 1         | 1      | 2.94%   |
| LITEONIT                | 1         | 1      | 2.94%   |
| LITEON                  | 1         | 1      | 2.94%   |
| Intel                   | 1         | 1      | 2.94%   |
| Hitachi                 | 1         | 1      | 2.94%   |
| Fujitsu                 | 1         | 1      | 2.94%   |
| Dogfish                 | 1         | 1      | 2.94%   |
| AGI                     | 1         | 1      | 2.94%   |
| ADATA Technology        | 1         | 1      | 2.94%   |
| A-DATA Technology       | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 2.78%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 2.78%   |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 2.78%   |
| Unknown MMC Card  64GB                       | 1         | 2.78%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.78%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 2.78%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 2.78%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 2.78%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2.78%   |
| StoreJet Disk 2TB                            | 1         | 2.78%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 2.78%   |
| SK hynix BC511 NVMe 512GB                    | 1         | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2.78%   |
| SanDisk SD5SG2256G1052E 256GB SSD            | 1         | 2.78%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 2.78%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 2.78%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 2.78%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 2.78%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 2.78%   |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2.78%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 2.78%   |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 2.78%   |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 2.78%   |
| Samsung MZNLN512HAJQ-000H1 512GB SSD         | 1         | 2.78%   |
| Samsung MZ7PD256HAFV-000H7 256GB SSD         | 1         | 2.78%   |
| LITEONIT LSS-24L6G 24GB SSD                  | 1         | 2.78%   |
| LITEON CV1-DB256 256GB SSD                   | 1         | 2.78%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 2.78%   |
| Kingston NVMe SSD Drive 512GB                | 1         | 2.78%   |
| Intel NVMe SSD Drive 512GB                   | 1         | 2.78%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 2.78%   |
| Fujitsu MHV2080BH 80GB                       | 1         | 2.78%   |
| Dogfish SSD 2TB                              | 1         | 2.78%   |
| AGI AGI960G18AI238 960GB                     | 1         | 2.78%   |
| ADATA NVMe SSD Drive 512GB                   | 1         | 2.78%   |
| A-DATA SWORDFISH 1TB                         | 1         | 2.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 28.57%  |
| Unknown  | 1         | 1      | 14.29%  |
| StoreJet | 1         | 1      | 14.29%  |
| Seagate  | 1         | 1      | 14.29%  |
| Hitachi  | 1         | 1      | 14.29%  |
| Fujitsu  | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 46.15%  |
| Toshiba             | 2         | 2      | 15.38%  |
| SanDisk             | 1         | 1      | 7.69%   |
| LITEONIT            | 1         | 1      | 7.69%   |
| LITEON              | 1         | 1      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| Dogfish             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 11        | 14     | 39.29%  |
| SSD     | 10        | 14     | 35.71%  |
| HDD     | 5         | 7      | 17.86%  |
| MMC     | 1         | 1      | 3.57%   |
| Unknown | 1         | 1      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 19     | 46.43%  |
| NVMe | 11        | 14     | 39.29%  |
| SAS  | 3         | 3      | 10.71%  |
| MMC  | 1         | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 10     | 44.44%  |
| 0.51-1.0   | 6         | 6      | 33.33%  |
| 1.01-2.0   | 3         | 3      | 16.67%  |
| 3.01-4.0   | 1         | 2      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 36.36%  |
| 101-250        | 7         | 31.82%  |
| 2001-3000      | 2         | 9.09%   |
| 501-1000       | 2         | 9.09%   |
| More than 3000 | 1         | 4.55%   |
| 1001-2000      | 1         | 4.55%   |
| 51-100         | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 7         | 31.82%  |
| 21-50     | 5         | 22.73%  |
| 101-250   | 4         | 18.18%  |
| 1001-2000 | 2         | 9.09%   |
| 51-100    | 2         | 9.09%   |
| 251-500   | 1         | 4.55%   |
| 501-1000  | 1         | 4.55%   |

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
| Detected | 16        | 25     | 66.67%  |
| Works    | 8         | 12     | 33.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 15        | 53.57%  |
| Samsung Electronics          | 4         | 14.29%  |
| AMD                          | 3         | 10.71%  |
| Union Memory (Shenzhen)      | 1         | 3.57%   |
| Toshiba America Info Systems | 1         | 3.57%   |
| SK hynix                     | 1         | 3.57%   |
| Realtek Semiconductor        | 1         | 3.57%   |
| Kingston Technology Company  | 1         | 3.57%   |
| ADATA Technology             | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 9.68%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 9.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 6.45%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 6.45%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 3.23%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 3.23%   |
| SK hynix BC511                                                                         | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 3.23%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 3.23%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 3.23%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 3.23%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 3.23%   |
| Intel SSD 660P Series                                                                  | 1         | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 3.23%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 3.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 3.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 3.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 3.23%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 14        | 48.28%  |
| NVMe | 11        | 37.93%  |
| IDE  | 4         | 13.79%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 77.27%  |
| AMD    | 5         | 22.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 9.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 4.55%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 4.55%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 4.55%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 4.55%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 4.55%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 4.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 4.55%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 4.55%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 4.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 4.55%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 4.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 4.55%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 4.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 4.55%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 4.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 4.55%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 1         | 4.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 4.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 4.55%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 10        | 45.45%  |
| Intel Core i5    | 4         | 18.18%  |
| Other            | 3         | 13.64%  |
| AMD Ryzen 5      | 2         | 9.09%   |
| Intel Core 2 Duo | 1         | 4.55%   |
| AMD Ryzen 7      | 1         | 4.55%   |
| AMD Ryzen 5 PRO  | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 12        | 54.55%  |
| 2      | 6         | 27.27%  |
| 6      | 3         | 13.64%  |
| 8      | 1         | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 86.36%  |
| 1      | 3         | 13.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 5         | 22.73%  |
| 0x806ec    | 2         | 9.09%   |
| 0x806c1    | 2         | 9.09%   |
| 0x506e3    | 2         | 9.09%   |
| 0x08600104 | 2         | 9.09%   |
| 0xa0652    | 1         | 4.55%   |
| 0x406e3    | 1         | 4.55%   |
| 0x40651    | 1         | 4.55%   |
| 0x306a9    | 1         | 4.55%   |
| 0x206a7    | 1         | 4.55%   |
| 0x10676    | 1         | 4.55%   |
| 0x0a50000c | 1         | 4.55%   |
| 0x08108102 | 1         | 4.55%   |
| 0x06006705 | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Haswell     | 6         | 27.27%  |
| Skylake     | 3         | 13.64%  |
| Zen 2       | 2         | 9.09%   |
| TigerLake   | 2         | 9.09%   |
| KabyLake    | 2         | 9.09%   |
| Zen+        | 1         | 4.55%   |
| Zen 3       | 1         | 4.55%   |
| SandyBridge | 1         | 4.55%   |
| Penryn      | 1         | 4.55%   |
| IvyBridge   | 1         | 4.55%   |
| Excavator   | 1         | 4.55%   |
| CometLake   | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Nvidia | 14        | 42.42%  |
| Intel  | 14        | 42.42%  |
| AMD    | 5         | 15.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Nvidia GK106GLM [Quadro K2100M]                                           | 3         | 9.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 9.09%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 6.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 6.06%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 3.03%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 3.03%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 3.03%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 3.03%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 3.03%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 3.03%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 3.03%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 3.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 3.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 3.03%   |
| Intel HD Graphics 530                                                     | 1         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 3.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 3.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 3.03%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 3.03%   |
| AMD Renoir                                                                | 1         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.03%   |
| AMD Cezanne                                                               | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 9         | 40.91%  |
| 1 x Nvidia     | 4         | 18.18%  |
| 1 x Intel      | 4         | 18.18%  |
| 1 x AMD        | 3         | 13.64%  |
| Intel + AMD    | 1         | 4.55%   |
| AMD + Nvidia   | 1         | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 16        | 72.73%  |
| Proprietary | 6         | 27.27%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 40.91%  |
| 1.01-2.0   | 5         | 22.73%  |
| 0.01-0.5   | 3         | 13.64%  |
| 5.01-6.0   | 2         | 9.09%   |
| 3.01-4.0   | 2         | 9.09%   |
| 0.51-1.0   | 1         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 14.29%  |
| AU Optronics        | 5         | 14.29%  |
| Goldstar            | 4         | 11.43%  |
| Dell                | 4         | 11.43%  |
| Chimei Innolux      | 4         | 11.43%  |
| BOE                 | 4         | 11.43%  |
| Samsung Electronics | 2         | 5.71%   |
| Philips             | 2         | 5.71%   |
| AOC                 | 2         | 5.71%   |
| PANDA               | 1         | 2.86%   |
| Panasonic           | 1         | 2.86%   |
| Lenovo              | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 2.7%    |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 2.7%    |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 2.7%    |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 2.7%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 2.7%    |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 1         | 2.7%    |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 2.7%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 2.7%    |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 2.7%    |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 2.7%    |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 2.7%    |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 2.7%    |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 2.7%    |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 2.7%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 2.7%    |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 2.7%    |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 2.7%    |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 2.7%    |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 2.7%    |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 2.7%    |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN14E6 1366x768 309x173mm 13.9-inch       | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 2.7%    |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 2.7%    |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 2.7%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 2.7%    |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 2.7%    |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x193mm 15.5-inch        | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 2.7%    |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1         | 2.7%    |
| AOC 2279WH AOC2279 1920x1080 477x268mm 21.5-inch                      | 1         | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 55.17%  |
| 1600x900 (HD+)     | 3         | 10.34%  |
| 3840x2160 (4K)     | 2         | 6.9%    |
| 1680x1050 (WSXGA+) | 2         | 6.9%    |
| 3440x1440          | 1         | 3.45%   |
| 2560x1440 (QHD)    | 1         | 3.45%   |
| 2560x1080          | 1         | 3.45%   |
| 1920x1200 (WUXGA)  | 1         | 3.45%   |
| 1366x768 (WXGA)    | 1         | 3.45%   |
| Unknown            | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 11        | 31.43%  |
| 14     | 7         | 20%     |
| 27     | 5         | 14.29%  |
| 21     | 3         | 8.57%   |
| 34     | 2         | 5.71%   |
| 17     | 2         | 5.71%   |
| 13     | 2         | 5.71%   |
| 24     | 1         | 2.86%   |
| 23     | 1         | 2.86%   |
| 22     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 57.14%  |
| 501-600     | 6         | 17.14%  |
| 401-500     | 5         | 14.29%  |
| 701-800     | 2         | 5.71%   |
| 351-400     | 2         | 5.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 80.77%  |
| 21/9  | 2         | 7.69%   |
| 16/10 | 2         | 7.69%   |
| 3/2   | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 32.35%  |
| 81-90          | 9         | 26.47%  |
| 301-350        | 5         | 14.71%  |
| 201-250        | 4         | 11.76%  |
| 351-500        | 2         | 5.88%   |
| 121-130        | 2         | 5.88%   |
| 151-200        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 58.82%  |
| 101-120       | 6         | 17.65%  |
| 51-100        | 6         | 17.65%  |
| More than 240 | 1         | 2.94%   |
| 161-240       | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11        | 50%     |
| 2     | 8         | 36.36%  |
| 3     | 2         | 9.09%   |
| 4     | 1         | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 54.29%  |
| Realtek Semiconductor | 12        | 34.29%  |
| Qualcomm Atheros      | 2         | 5.71%   |
| MediaTek              | 1         | 2.86%   |
| Broadcom              | 1         | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 25%     |
| Intel Wireless 7260                                               | 5         | 11.36%  |
| Intel Ethernet Connection I217-LM                                 | 3         | 6.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.55%   |
| Intel Wireless 8260                                               | 2         | 4.55%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 4.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.27%   |
| Intel Wireless 7265                                               | 1         | 2.27%   |
| Intel Wireless 3160                                               | 1         | 2.27%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.27%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 2.27%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.27%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.27%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 86.36%  |
| Realtek Semiconductor | 1         | 4.55%   |
| Qualcomm Atheros      | 1         | 4.55%   |
| MediaTek              | 1         | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 5         | 22.73%  |
| Intel Wireless 8260                                           | 2         | 9.09%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 9.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 9.09%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 4.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 4.55%   |
| Intel Wireless 7265                                           | 1         | 4.55%   |
| Intel Wireless 3160                                           | 1         | 4.55%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 4.55%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 4.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 4.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 4.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 57.14%  |
| Intel                 | 7         | 33.33%  |
| Qualcomm Atheros      | 1         | 4.76%   |
| Broadcom              | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 50%     |
| Intel Ethernet Connection I217-LM                                 | 3         | 13.64%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 9.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 4.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 4.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 4.55%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4.55%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 52.38%  |
| Ethernet | 20        | 47.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 70.83%  |
| Ethernet | 7         | 29.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 81.82%  |
| 1     | 3         | 13.64%  |
| 3     | 1         | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 68.18%  |
| Yes  | 7         | 31.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 80%     |
| Realtek Semiconductor           | 1         | 5%      |
| Qualcomm Atheros Communications | 1         | 5%      |
| Foxconn / Hon Hai               | 1         | 5%      |
| Broadcom                        | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 10        | 50%     |
| Intel AX201 Bluetooth                              | 4         | 20%     |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 5%      |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 1         | 5%      |
| Intel AX200 Bluetooth                              | 1         | 5%      |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 5%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 17        | 43.59%  |
| Nvidia              | 10        | 25.64%  |
| AMD                 | 5         | 12.82%  |
| Logitech            | 2         | 5.13%   |
| Hewlett-Packard     | 1         | 2.56%   |
| GN Netcom           | 1         | 2.56%   |
| Creative Technology | 1         | 2.56%   |
| Conexant Systems    | 1         | 2.56%   |
| C-Media Electronics | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 10.64%  |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 8.51%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 6.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 6.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 4.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 4.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 4.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.13%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.13%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.13%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 2.13%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 2.13%   |
| Logitech Stereo H650e                                                      | 1         | 2.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.13%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.13%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.13%   |
| Hewlett-Packard USB Audio                                                  | 1         | 2.13%   |
| GN Netcom Jabra EVOLVE 65                                                  | 1         | 2.13%   |
| Creative Technology Sound Blaster Play! 3                                  | 1         | 2.13%   |
| Conexant Systems HP Dock Audio                                             | 1         | 2.13%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.13%   |
| AMD High Definition Audio Controller                                       | 1         | 2.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 42.86%  |
| SK hynix            | 2         | 28.57%  |
| Micron Technology   | 1         | 14.29%  |
| Crucial             | 1         | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 14.29%  |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s | 1         | 14.29%  |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 14.29%  |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 14.29%  |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 14.29%  |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s         | 1         | 14.29%  |
| Crucial RAM CT16G4SFRA266.M16FRS 16384MB SODIMM DDR4 2667MT/s | 1         | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 3         | 42.86%  |
| DDR3   | 3         | 42.86%  |
| LPDDR4 | 1         | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 7         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 5         | 71.43%  |
| 16384 | 2         | 28.57%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 3         | 42.86%  |
| 1600  | 2         | 28.57%  |
| 4266  | 1         | 14.29%  |
| 3200  | 1         | 14.29%  |

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


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 6         | 27.27%  |
| Syntek                | 3         | 13.64%  |
| Realtek Semiconductor | 2         | 9.09%   |
| IMC Networks          | 2         | 9.09%   |
| Quanta                | 1         | 4.55%   |
| Microdia              | 1         | 4.55%   |
| Logitech              | 1         | 4.55%   |
| Lite-On Technology    | 1         | 4.55%   |
| Lenovo                | 1         | 4.55%   |
| Intel                 | 1         | 4.55%   |
| DJJHNA29IE70D3        | 1         | 4.55%   |
| Apple                 | 1         | 4.55%   |
| Acer                  | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Integrated Camera              | 4         | 18.18%  |
| Syntek Lenovo EasyCamera               | 2         | 9.09%   |
| Syntek Integrated Camera               | 1         | 4.55%   |
| Realtek Integrated_Webcam_HD           | 1         | 4.55%   |
| Realtek EasyCamera                     | 1         | 4.55%   |
| Quanta HP Webcam                       | 1         | 4.55%   |
| Microdia Integrated_Webcam_HD          | 1         | 4.55%   |
| Logitech BRIO Ultra HD Webcam          | 1         | 4.55%   |
| Lite-On HP HD Webcam                   | 1         | 4.55%   |
| Lenovo UVC Camera                      | 1         | 4.55%   |
| Intel RealSense 3D Camera (Front F200) | 1         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam      | 1         | 4.55%   |
| IMC Networks TOSHIBA Web Camera - HD   | 1         | 4.55%   |
| DJJHNA29IE70D3 HP HD Camera            | 1         | 4.55%   |
| Chicony HP HD Camera                   | 1         | 4.55%   |
| Chicony HD WebCam                      | 1         | 4.55%   |
| Apple iPhone 5/5C/5S/6/SE              | 1         | 4.55%   |
| Acer Integrated Camera                 | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 66.67%  |
| Synaptics        | 1         | 16.67%  |
| AuthenTec        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 33.33%  |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 16.67%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| AuthenTec AES2810                                         | 1         | 16.67%  |

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
| 1     | 10        | 45.45%  |
| 0     | 9         | 40.91%  |
| 2     | 3         | 13.64%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 37.5%   |
| Graphics card         | 3         | 18.75%  |
| Net/wireless          | 2         | 12.5%   |
| Chipcard              | 2         | 12.5%   |
| Net/ethernet          | 1         | 6.25%   |
| Multimedia controller | 1         | 6.25%   |
| Card reader           | 1         | 6.25%   |

