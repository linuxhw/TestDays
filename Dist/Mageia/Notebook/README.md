Mageia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Mageia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | Latitude E5570              | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell     | Latitude E5570              | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell     | Precision 5530              | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [46250d420a](https://linux-hardware.org/?probe=46250d420a) | Aug 14, 2021 |
| Lenovo   | ThinkPad T61 6468AE2        | [216fbf401b](https://linux-hardware.org/?probe=216fbf401b) | Aug 05, 2021 |
| ASUSTek  | X751LN                      | [8c0efa94e8](https://linux-hardware.org/?probe=8c0efa94e8) | Jul 08, 2021 |
| ASUSTek  | X751LN                      | [7619cf7632](https://linux-hardware.org/?probe=7619cf7632) | May 31, 2021 |
| ASUSTek  | X751LN                      | [70f882a983](https://linux-hardware.org/?probe=70f882a983) | May 31, 2021 |
| Notebook | NL40_50GU                   | [baa8447288](https://linux-hardware.org/?probe=baa8447288) | May 08, 2021 |
| Medion   | DEFENDER P10                | [cb752c0a4a](https://linux-hardware.org/?probe=cb752c0a4a) | May 01, 2021 |
| Medion   | DEFENDER P10                | [f42aa05a37](https://linux-hardware.org/?probe=f42aa05a37) | May 01, 2021 |
| Fujitsu  | LIFEBOOK E752               | [8ec052ba75](https://linux-hardware.org/?probe=8ec052ba75) | Apr 15, 2021 |
| Lenovo   | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| ASUSTek  | X751LN                      | [7da0db2567](https://linux-hardware.org/?probe=7da0db2567) | Apr 03, 2021 |
| ASUSTek  | X751LN                      | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| ASUSTek  | X556URK                     | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| ASUSTek  | X751LN                      | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| ASUSTek  | X751LN                      | [a8e9bcdc07](https://linux-hardware.org/?probe=a8e9bcdc07) | Feb 23, 2021 |
| Dell     | Latitude E6530              | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Dell     | Inspiron 5480               | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| ASUSTek  | X751LN                      | [6e7c6b5d77](https://linux-hardware.org/?probe=6e7c6b5d77) | Jan 16, 2021 |
| ASUSTek  | X751LN                      | [567ce23c0d](https://linux-hardware.org/?probe=567ce23c0d) | Jan 13, 2021 |
| ASUSTek  | X751LN                      | [513ff22c6f](https://linux-hardware.org/?probe=513ff22c6f) | Jan 13, 2021 |
| Kiano    | SlimNote 15.6               | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano    | SlimNote 15.6               | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek  | X751LN                      | [9136594961](https://linux-hardware.org/?probe=9136594961) | Jan 02, 2021 |
| ASUSTek  | X751LN                      | [ea55725f98](https://linux-hardware.org/?probe=ea55725f98) | Dec 30, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
| ASUSTek  | X751LN                      | [8399780a87](https://linux-hardware.org/?probe=8399780a87) | Dec 27, 2020 |
| ASUSTek  | X751LN                      | [f7f3533d54](https://linux-hardware.org/?probe=f7f3533d54) | Dec 27, 2020 |
| Dell     | Inspiron 5480               | [1261d0c9d3](https://linux-hardware.org/?probe=1261d0c9d3) | Dec 21, 2020 |
| HP       | Spectre 13 Ultrabook        | [9b88fe4fa5](https://linux-hardware.org/?probe=9b88fe4fa5) | Nov 30, 2020 |
| HP       | EliteBook 840 G3            | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP       | EliteBook 840 G3            | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| HP       | ProBook 445 G7              | [2e97281aa0](https://linux-hardware.org/?probe=2e97281aa0) | Nov 05, 2020 |
| Acer     | Aspire V3-772               | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| Dell     | Inspiron 5480               | [62bb8575f1](https://linux-hardware.org/?probe=62bb8575f1) | Oct 22, 2020 |
| HP       | Unknown                     | [b12d1589a1](https://linux-hardware.org/?probe=b12d1589a1) | Sep 08, 2020 |
| Acer     | Aspire 7741                 | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| HP       | Pavilion dv6                | [021a94f63e](https://linux-hardware.org/?probe=021a94f63e) | Sep 03, 2020 |
| Lenovo   | G480 20149                  | [5598a535c7](https://linux-hardware.org/?probe=5598a535c7) | Jul 24, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [8e31f45bf5](https://linux-hardware.org/?probe=8e31f45bf5) | May 07, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [db83d53491](https://linux-hardware.org/?probe=db83d53491) | May 07, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| Lenovo   | G570 20079                  | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7  | 4         | 14.29%  |
| 5.7.19-desktop-1.mga7  | 3         | 10.71%  |
| 5.6.14-desktop-2.mga7  | 2         | 7.14%   |
| 5.15.4-desktop-1.mga8  | 2         | 7.14%   |
| 5.9.6-desktop-1.mga8   | 1         | 3.57%   |
| 5.9.16-desktop-1.mga7  | 1         | 3.57%   |
| 5.9.11-desktop-3.mga8  | 1         | 3.57%   |
| 5.8.5-desktop-2.mga8   | 1         | 3.57%   |
| 5.7.8-desktop-1.mga8   | 1         | 3.57%   |
| 5.6.6-desktop-1.mga7   | 1         | 3.57%   |
| 5.10.46-desktop-1.mga8 | 1         | 3.57%   |
| 5.10.37-desktop-2.mga8 | 1         | 3.57%   |
| 5.10.33-desktop-1.mga8 | 1         | 3.57%   |
| 5.10.30-desktop-1.mga8 | 1         | 3.57%   |
| 5.10.3-desktop-1.mga7  | 1         | 3.57%   |
| 5.10.27-desktop-1.mga8 | 1         | 3.57%   |
| 5.10.25-desktop-1.mga8 | 1         | 3.57%   |
| 5.10.20-desktop-2.mga7 | 1         | 3.57%   |
| 5.10.16-desktop-1.mga8 | 1         | 3.57%   |
| 5.10.16-desktop-1.mga7 | 1         | 3.57%   |
| 5.10.12-desktop-2.mga8 | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7.19  | 7         | 25%     |
| 5.6.14  | 2         | 7.14%   |
| 5.15.4  | 2         | 7.14%   |
| 5.10.16 | 2         | 7.14%   |
| 5.9.6   | 1         | 3.57%   |
| 5.9.16  | 1         | 3.57%   |
| 5.9.11  | 1         | 3.57%   |
| 5.8.5   | 1         | 3.57%   |
| 5.7.8   | 1         | 3.57%   |
| 5.6.6   | 1         | 3.57%   |
| 5.10.46 | 1         | 3.57%   |
| 5.10.37 | 1         | 3.57%   |
| 5.10.33 | 1         | 3.57%   |
| 5.10.30 | 1         | 3.57%   |
| 5.10.3  | 1         | 3.57%   |
| 5.10.27 | 1         | 3.57%   |
| 5.10.25 | 1         | 3.57%   |
| 5.10.20 | 1         | 3.57%   |
| 5.10.12 | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7     | 8         | 33.33%  |
| 5.10    | 7         | 29.17%  |
| 5.9     | 3         | 12.5%   |
| 5.6     | 3         | 12.5%   |
| 5.15    | 2         | 8.33%   |
| 5.8     | 1         | 4.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 21        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 11        | 50%     |
| KDE     | 7         | 31.82%  |
| XFCE    | 2         | 9.09%   |
| MATE    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 21        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 10        | 47.62%  |
| Unknown | 9         | 42.86%  |
| TDM     | 2         | 9.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 5         | 23.81%  |
| fr_FR | 4         | 19.05%  |
| it_IT | 2         | 9.52%   |
| de_DE | 2         | 9.52%   |
| ru_RU | 1         | 4.76%   |
| pt_BR | 1         | 4.76%   |
| pl_PL | 1         | 4.76%   |
| hu_HU | 1         | 4.76%   |
| es_GT | 1         | 4.76%   |
| es_ES | 1         | 4.76%   |
| en_GB | 1         | 4.76%   |
| bg_BG | 1         | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 66.67%  |
| BIOS | 8         | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 21        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 11        | 47.83%  |
| Unknown | 7         | 30.43%  |
| MBR     | 5         | 21.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 85.71%  |
| Yes       | 3         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 72.73%  |
| Yes       | 6         | 27.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 5         | 23.81%  |
| Dell             | 4         | 19.05%  |
| Lenovo           | 3         | 14.29%  |
| ASUSTek Computer | 3         | 14.29%  |
| Acer             | 2         | 9.52%   |
| Notebook         | 1         | 4.76%   |
| Medion           | 1         | 4.76%   |
| Kiano            | 1         | 4.76%   |
| Fujitsu          | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Notebook NL40_50GU                   | 1         | 4.76%   |
| Medion DEFENDER P10                  | 1         | 4.76%   |
| Lenovo ThinkPad T430 2342A19         | 1         | 4.76%   |
| Lenovo IdeaPad 3 15ADA05 81W1        | 1         | 4.76%   |
| Lenovo G480 20149                    | 1         | 4.76%   |
| Kiano SlimNote 15.6                  | 1         | 4.76%   |
| HP Spectre 13 Ultrabook              | 1         | 4.76%   |
| HP ProBook 445 G7                    | 1         | 4.76%   |
| HP Pavilion dv6                      | 1         | 4.76%   |
| HP EliteBook 840 G3                  | 1         | 4.76%   |
| Fujitsu LIFEBOOK E752                | 1         | 4.76%   |
| Dell Precision 5530                  | 1         | 4.76%   |
| Dell Latitude E6530                  | 1         | 4.76%   |
| Dell Latitude E5570                  | 1         | 4.76%   |
| Dell Inspiron 5480                   | 1         | 4.76%   |
| ASUS X751LN                          | 1         | 4.76%   |
| ASUS X556URK                         | 1         | 4.76%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR | 1         | 4.76%   |
| Acer Aspire V3-772                   | 1         | 4.76%   |
| Acer Aspire 7741                     | 1         | 4.76%   |
| Unknown                              | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell Latitude    | 2         | 9.52%   |
| Acer Aspire      | 2         | 9.52%   |
| Notebook NL40    | 1         | 4.76%   |
| Medion DEFENDER  | 1         | 4.76%   |
| Lenovo ThinkPad  | 1         | 4.76%   |
| Lenovo IdeaPad   | 1         | 4.76%   |
| Lenovo G480      | 1         | 4.76%   |
| Kiano SlimNote   | 1         | 4.76%   |
| HP Spectre       | 1         | 4.76%   |
| HP ProBook       | 1         | 4.76%   |
| HP Pavilion      | 1         | 4.76%   |
| HP EliteBook     | 1         | 4.76%   |
| Fujitsu LIFEBOOK | 1         | 4.76%   |
| Dell Precision   | 1         | 4.76%   |
| Dell Inspiron    | 1         | 4.76%   |
| ASUS X751LN      | 1         | 4.76%   |
| ASUS X556URK     | 1         | 4.76%   |
| ASUS VivoBook    | 1         | 4.76%   |
| Unknown          | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 4         | 19.05%  |
| 2020 | 3         | 14.29%  |
| 2018 | 3         | 14.29%  |
| 2016 | 3         | 14.29%  |
| 2013 | 2         | 9.52%   |
| 2019 | 1         | 4.76%   |
| 2017 | 1         | 4.76%   |
| 2014 | 1         | 4.76%   |
| 2010 | 1         | 4.76%   |
| 2008 | 1         | 4.76%   |
| 2007 | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 21        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 21        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 36.36%  |
| 3.01-4.0   | 5         | 22.73%  |
| 8.01-16.0  | 5         | 22.73%  |
| 32.01-64.0 | 2         | 9.09%   |
| 16.01-24.0 | 2         | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 11        | 47.83%  |
| 1.01-2.0 | 6         | 26.09%  |
| 4.01-8.0 | 4         | 17.39%  |
| 3.01-4.0 | 2         | 8.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 81.82%  |
| 2      | 4         | 18.18%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 57.14%  |
| Yes       | 9         | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 76.19%  |
| No        | 5         | 23.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 95.24%  |
| No        | 1         | 4.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 71.43%  |
| No        | 6         | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| France    | 4         | 19.05%  |
| Italy     | 3         | 14.29%  |
| USA       | 2         | 9.52%   |
| Germany   | 2         | 9.52%   |
| UK        | 1         | 4.76%   |
| Russia    | 1         | 4.76%   |
| Romania   | 1         | 4.76%   |
| Poland    | 1         | 4.76%   |
| Indonesia | 1         | 4.76%   |
| Guatemala | 1         | 4.76%   |
| Greece    | 1         | 4.76%   |
| Colombia  | 1         | 4.76%   |
| Bulgaria  | 1         | 4.76%   |
| Brazil    | 1         | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Rome                | 2         | 8.33%   |
| Tver                | 1         | 4.17%   |
| Tours               | 1         | 4.17%   |
| Thessaloniki        | 1         | 4.17%   |
| São Paulo          | 1         | 4.17%   |
| Saint-Dié          | 1         | 4.17%   |
| Poznan              | 1         | 4.17%   |
| Pisa                | 1         | 4.17%   |
| Paris               | 1         | 4.17%   |
| Oxford              | 1         | 4.17%   |
| Odenville           | 1         | 4.17%   |
| Obernai             | 1         | 4.17%   |
| Nordenham           | 1         | 4.17%   |
| Miercurea-Ciuc      | 1         | 4.17%   |
| Lumajang            | 1         | 4.17%   |
| Lisieux             | 1         | 4.17%   |
| Guatemala City      | 1         | 4.17%   |
| Denver              | 1         | 4.17%   |
| Cologne             | 1         | 4.17%   |
| Casalecchio di Reno | 1         | 4.17%   |
| Burgas              | 1         | 4.17%   |
| Brindas             | 1         | 4.17%   |
| Bogotá             | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba                 | 3         | 4      | 11.54%  |
| Seagate                 | 3         | 3      | 11.54%  |
| Kingston                | 3         | 3      | 11.54%  |
| WDC                     | 2         | 4      | 7.69%   |
| Unknown                 | 2         | 2      | 7.69%   |
| Samsung Electronics     | 2         | 2      | 7.69%   |
| Hitachi                 | 2         | 2      | 7.69%   |
| Union Memory (Shenzhen) | 1         | 1      | 3.85%   |
| SK Hynix                | 1         | 2      | 3.85%   |
| SanDisk                 | 1         | 1      | 3.85%   |
| Phison                  | 1         | 1      | 3.85%   |
| LDLC                    | 1         | 1      | 3.85%   |
| Intel                   | 1         | 1      | 3.85%   |
| HGST                    | 1         | 6      | 3.85%   |
| Crucial                 | 1         | 1      | 3.85%   |
| China                   | 1         | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 3.7%    |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 3.7%    |
| Unknown MMC Card  32GB                       | 1         | 3.7%    |
| Unknown MMC Card  16GB                       | 1         | 3.7%    |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 3.7%    |
| Toshiba MQ04ABF100 1TB                       | 1         | 3.7%    |
| Toshiba MQ01ABF050 500GB                     | 1         | 3.7%    |
| Toshiba MQ01ABD100 1TB                       | 1         | 3.7%    |
| SK Hynix SKHynix_HFM512GDHTNI-87A0B 512GB    | 1         | 3.7%    |
| SK Hynix NVMe SSD Drive 512GB                | 1         | 3.7%    |
| Seagate ST96812AS 64GB                       | 1         | 3.7%    |
| Seagate ST320LT020-9YG142 320GB              | 1         | 3.7%    |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 3.7%    |
| SanDisk SD6SN1M-256G-1006 256GB SSD          | 1         | 3.7%    |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 3.7%    |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 3.7%    |
| Phison E12S-1TB-PHISON-SSD-B27B              | 1         | 3.7%    |
| LDLC F6+M.2 480 480GB SSD                    | 1         | 3.7%    |
| Kingston SA400S37240G 240GB SSD              | 1         | 3.7%    |
| Kingston SA2000M8500G 500GB                  | 1         | 3.7%    |
| Kingston NVMe SSD Drive 1TB                  | 1         | 3.7%    |
| Intel SSDMCEAC120B3A 120GB                   | 1         | 3.7%    |
| Hitachi HTS725050A9A364 500GB                | 1         | 3.7%    |
| Hitachi HTS545050A7E380 500GB                | 1         | 3.7%    |
| HGST HTS541010A9E680 1TB                     | 1         | 3.7%    |
| Crucial CT120BX500SSD1 120GB                 | 1         | 3.7%    |
| China SATA SSD 120GB                         | 1         | 3.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 4      | 30%     |
| Seagate | 3         | 3      | 30%     |
| Hitachi | 2         | 2      | 20%     |
| WDC     | 1         | 3      | 10%     |
| HGST    | 1         | 6      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 12.5%   |
| SanDisk             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| LDLC                | 1         | 1      | 12.5%   |
| Kingston            | 1         | 1      | 12.5%   |
| Intel               | 1         | 1      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |
| China               | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 18     | 38.46%  |
| SSD  | 8         | 8      | 30.77%  |
| NVMe | 6         | 7      | 23.08%  |
| MMC  | 2         | 2      | 7.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 26     | 66.67%  |
| NVMe | 6         | 7      | 25%     |
| MMC  | 2         | 2      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 13     | 70.59%  |
| 0.51-1.0   | 5         | 13     | 29.41%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 7         | 33.33%  |
| 501-1000   | 7         | 33.33%  |
| 101-250    | 5         | 23.81%  |
| 1001-2000  | 1         | 4.76%   |
| 51-100     | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 7         | 31.82%  |
| 1-20      | 5         | 22.73%  |
| 21-50     | 4         | 18.18%  |
| 51-100    | 4         | 18.18%  |
| 1001-2000 | 1         | 4.55%   |
| 501-1000  | 1         | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB          | 1         | 1      | 33.33%  |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 33.33%  |
| Hitachi HTS725050A9A364 500GB   | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Works    | 14        | 16     | 56%     |
| Detected | 8         | 16     | 32%     |
| Malfunc  | 3         | 3      | 12%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 17        | 70.83%  |
| Kingston Technology Company | 2         | 8.33%   |
| AMD                         | 2         | 8.33%   |
| SK Hynix                    | 1         | 4.17%   |
| Samsung Electronics         | 1         | 4.17%   |
| Phison Electronics          | 1         | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 11.54%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 11.54%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 7.69%   |
| SK Hynix BC511                                                                 | 1         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 3.85%   |
| Phison E12 NVMe Controller                                                     | 1         | 3.85%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 3.85%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 3.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 3.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 3.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 3.85%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 3.85%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 3.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 3.85%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 3.85%   |
| AMD SB600 IDE                                                                  | 1         | 3.85%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 68%     |
| NVMe | 5         | 20%     |
| IDE  | 2         | 8%      |
| RAID | 1         | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 85.71%  |
| AMD    | 3         | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 9.52%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 4.76%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 4.76%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 4.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 4.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 4.76%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 4.76%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 4.76%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 4.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 4.76%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 4.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 4.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 4.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 4.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 4.76%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 4.76%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 4.76%   |
| AMD Turion 64 X2 Mobile Technology TL-60      | 1         | 4.76%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 4.76%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 7         | 33.33%  |
| Intel Core i5           | 7         | 33.33%  |
| AMD Ryzen 7             | 2         | 9.52%   |
| Intel Pentium Silver    | 1         | 4.76%   |
| Intel Pentium           | 1         | 4.76%   |
| Intel Core i3           | 1         | 4.76%   |
| Intel Atom              | 1         | 4.76%   |
| AMD Turion 64 X2 Mobile | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 57.14%  |
| 4      | 6         | 28.57%  |
| 6      | 2         | 9.52%   |
| 8      | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 71.43%  |
| 1      | 6         | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 21        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 17.39%  |
| 0x306a9    | 3         | 13.04%  |
| 0x806e9    | 2         | 8.7%    |
| 0x40651    | 2         | 8.7%    |
| 0xa0652    | 1         | 4.35%   |
| 0x906ea    | 1         | 4.35%   |
| 0x806eb    | 1         | 4.35%   |
| 0x706a1    | 1         | 4.35%   |
| 0x506e3    | 1         | 4.35%   |
| 0x406e3    | 1         | 4.35%   |
| 0x406c4    | 1         | 4.35%   |
| 0x306c3    | 1         | 4.35%   |
| 0x206a7    | 1         | 4.35%   |
| 0x20655    | 1         | 4.35%   |
| 0x08600106 | 1         | 4.35%   |
| 0x08108109 | 1         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 4         | 19.05%  |
| IvyBridge     | 4         | 19.05%  |
| Haswell       | 3         | 14.29%  |
| Skylake       | 2         | 9.52%   |
| Zen+          | 1         | 4.76%   |
| Zen 2         | 1         | 4.76%   |
| Westmere      | 1         | 4.76%   |
| Silvermont    | 1         | 4.76%   |
| SandyBridge   | 1         | 4.76%   |
| K8 Hammer     | 1         | 4.76%   |
| Goldmont plus | 1         | 4.76%   |
| CometLake     | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 62.07%  |
| Nvidia | 7         | 24.14%  |
| AMD    | 4         | 13.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 13.79%  |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 6.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 3.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 3.45%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 3.45%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 3.45%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 3.45%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 3.45%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 3.45%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 3.45%   |
| Intel HD Graphics 620                                                                    | 1         | 3.45%   |
| Intel HD Graphics 530                                                                    | 1         | 3.45%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 3.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 3.45%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 3.45%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 3.45%   |
| AMD Renoir                                                                               | 1         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 10        | 47.62%  |
| Intel + Nvidia | 7         | 33.33%  |
| 1 x AMD        | 3         | 14.29%  |
| Intel + AMD    | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 95.45%  |
| Proprietary | 1         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 58.33%  |
| 1.01-2.0   | 5         | 20.83%  |
| 0.01-0.5   | 2         | 8.33%   |
| 5.01-6.0   | 1         | 4.17%   |
| 3.01-4.0   | 1         | 4.17%   |
| 0.51-1.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 5         | 20.83%  |
| LG Display              | 4         | 16.67%  |
| Chimei Innolux          | 4         | 16.67%  |
| AU Optronics            | 3         | 12.5%   |
| Samsung Electronics     | 2         | 8.33%   |
| Chi Mei Optoelectronics | 2         | 8.33%   |
| Sharp                   | 1         | 4.17%   |
| Lenovo                  | 1         | 4.17%   |
| Ancor Communications    | 1         | 4.17%   |
| Acer                    | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 4.17%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch        | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch      | 1         | 4.17%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 4.17%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 4.17%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 1         | 4.17%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                   | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch          | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 4.17%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 4.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 4.17%   |
| BOE LCD Monitor BOE0806 1920x1080 309x173mm 13.9-inch                     | 1         | 4.17%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 1         | 4.17%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch             | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO429D 1920x1080 382x215mm 17.3-inch            | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 1         | 4.17%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch          | 1         | 4.17%   |
| Acer G247HL ACR03FA 1920x1080 531x299mm 24.0-inch                         | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 13        | 56.52%  |
| 1366x768 (WXGA)    | 5         | 21.74%  |
| 1600x900 (HD+)     | 3         | 13.04%  |
| 1680x1050 (WSXGA+) | 1         | 4.35%   |
| 1280x800 (WXGA)    | 1         | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 41.67%  |
| 17     | 5         | 20.83%  |
| 14     | 3         | 12.5%   |
| 13     | 3         | 12.5%   |
| 24     | 2         | 8.33%   |
| 22     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 62.5%   |
| 351-400     | 5         | 20.83%  |
| 501-600     | 2         | 8.33%   |
| 401-500     | 1         | 4.17%   |
| 201-300     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 20        | 90.91%  |
| 16/10 | 2         | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 41.67%  |
| 81-90          | 5         | 20.83%  |
| 121-130        | 5         | 20.83%  |
| 201-250        | 3         | 12.5%   |
| 71-80          | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 47.83%  |
| 101-120 | 7         | 30.43%  |
| 51-100  | 4         | 17.39%  |
| 161-240 | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 85.71%  |
| 2     | 3         | 14.29%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 33.33%  |
| Realtek Semiconductor | 8         | 24.24%  |
| Qualcomm Atheros      | 6         | 18.18%  |
| Broadcom              | 4         | 12.12%  |
| Sierra Wireless       | 1         | 3.03%   |
| Dell                  | 1         | 3.03%   |
| Broadcom Limited      | 1         | 3.03%   |
| ASIX Electronics      | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 13.16%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 5.26%   |
| Intel Wireless 8260                                               | 2         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 5.26%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.63%   |
| Intel Wireless-AC 9260                                            | 1         | 2.63%   |
| Intel Wireless 7260                                               | 1         | 2.63%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.63%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 2.63%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.63%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.63%   |
| Dell DW5811e Snapdragon???�?? X7 LTE                              | 1         | 2.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.63%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 2.63%   |
| Broadcom BCM4311 802.11a/b/g                                      | 1         | 2.63%   |
| ASIX AX88772B                                                     | 1         | 2.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 45.45%  |
| Qualcomm Atheros      | 6         | 27.27%  |
| Broadcom              | 3         | 13.64%  |
| Sierra Wireless       | 1         | 4.55%   |
| Realtek Semiconductor | 1         | 4.55%   |
| Dell                  | 1         | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 9.09%   |
| Intel Wireless 8260                                            | 2         | 9.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 9.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 9.09%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 4.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 4.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 4.55%   |
| Intel Wireless-AC 9260                                         | 1         | 4.55%   |
| Intel Wireless 7260                                            | 1         | 4.55%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 4.55%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 4.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 4.55%   |
| Dell DW5811e Snapdragon???�?? X7 LTE                           | 1         | 4.55%   |
| Broadcom BCM4311 802.11a/b/g                                   | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 43.75%  |
| Intel                 | 5         | 31.25%  |
| Qualcomm Atheros      | 1         | 6.25%   |
| Broadcom Limited      | 1         | 6.25%   |
| Broadcom              | 1         | 6.25%   |
| ASIX Electronics      | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 31.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 12.5%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 6.25%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 6.25%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 6.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 6.25%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 6.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 6.25%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 6.25%   |
| ASIX AX88772B                                                     | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 55.56%  |
| Ethernet | 16        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 72%     |
| Ethernet | 7         | 28%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 14        | 66.67%  |
| 1     | 6         | 28.57%  |
| 0     | 1         | 4.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 90.91%  |
| Yes  | 2         | 9.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 7         | 43.75%  |
| IMC Networks            | 2         | 12.5%   |
| Realtek Semiconductor   | 1         | 6.25%   |
| Lite-On Technology      | 1         | 6.25%   |
| Hewlett-Packard         | 1         | 6.25%   |
| Foxconn / Hon Hai       | 1         | 6.25%   |
| Dell                    | 1         | 6.25%   |
| Cambridge Silicon Radio | 1         | 6.25%   |
| Broadcom                | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 3         | 18.75%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 12.5%   |
| IMC Networks Bluetooth Device                       | 2         | 12.5%   |
| Realtek Bluetooth Radio                             | 1         | 6.25%   |
| Lite-On Bluetooth Device                            | 1         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 6.25%   |
| Intel Bluetooth wireless interface                  | 1         | 6.25%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 6.25%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 6.25%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 17        | 73.91%  |
| AMD                 | 3         | 13.04%  |
| Nvidia              | 2         | 8.7%    |
| C-Media Electronics | 1         | 4.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 14.29%  |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 10.71%  |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 7.14%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 7.14%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2         | 7.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 3.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 3.57%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 3.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 3.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 3.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 3.57%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 23.81%  |
| SK Hynix            | 4         | 19.05%  |
| Kingston            | 4         | 19.05%  |
| Micron Technology   | 3         | 14.29%  |
| Unknown             | 2         | 9.52%   |
| Smart               | 1         | 4.76%   |
| Crucial             | 1         | 4.76%   |
| Corsair             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                  | 1         | 4.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                | 1         | 4.55%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                 | 1         | 4.55%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 4.55%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s    | 1         | 4.55%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s    | 1         | 4.55%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 4.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s        | 1         | 4.55%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 1         | 4.55%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s        | 1         | 4.55%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s       | 1         | 4.55%   |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s             | 1         | 4.55%   |
| Kingston RAM KCRXJ6-MIE 16384MB SODIMM DDR4 2667MT/s         | 1         | 4.55%   |
| Kingston RAM ACR16D3LS1KBG/8G 8GB SODIMM DDR3 1600MT/s       | 1         | 4.55%   |
| Kingston RAM 9905428-102.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 4.55%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s   | 1         | 4.55%   |
| Corsair RAM CMSX16GX4M1A2666C18 16384MB SODIMM DDR4 2667MT/s | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 8         | 47.06%  |
| DDR3 | 8         | 47.06%  |
| DDR2 | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 52.94%  |
| 8192  | 4         | 23.53%  |
| 16384 | 2         | 11.76%  |
| 2048  | 2         | 11.76%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 6         | 31.58%  |
| 2400  | 3         | 15.79%  |
| 3200  | 2         | 10.53%  |
| 2667  | 2         | 10.53%  |
| 2133  | 2         | 10.53%  |
| 1334  | 1         | 5.26%   |
| 1066  | 1         | 5.26%   |
| 975   | 1         | 5.26%   |
| 667   | 1         | 5.26%   |

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
| Chicony Electronics                    | 8         | 38.1%   |
| Realtek Semiconductor                  | 2         | 9.52%   |
| Microdia                               | 2         | 9.52%   |
| IMC Networks                           | 2         | 9.52%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 9.52%   |
| Suyin                                  | 1         | 4.76%   |
| Sunplus Innovation Technology          | 1         | 4.76%   |
| Primax Electronics                     | 1         | 4.76%   |
| Apple                                  | 1         | 4.76%   |
| Alcor Micro                            | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 9.52%   |
| Chicony USB2.0 Camera                                                      | 2         | 9.52%   |
| Chicony Integrated Camera                                                  | 2         | 9.52%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 4.76%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 4.76%   |
| Realtek USB Camera                                                         | 1         | 4.76%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 4.76%   |
| Primax HP Truevision FHD                                                   | 1         | 4.76%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 4.76%   |
| Microdia Integrated Webcam                                                 | 1         | 4.76%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 4.76%   |
| Chicony HD WebCam                                                          | 1         | 4.76%   |
| Chicony FJ Camera                                                          | 1         | 4.76%   |
| Chicony 1.3M HD WebCam                                                     | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 4.76%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 4.76%   |
| Alcor Micro USB 2.0 Web Camera                                             | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Shenzhen Goodix Technology | 2         | 40%     |
| AuthenTec                  | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Validity Sensors Fingerprint scanner       | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device        | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader         | 1         | 20%     |
| AuthenTec AES2501 Fingerprint Sensor       | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| O2 Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11        | 47.83%  |
| 0     | 9         | 39.13%  |
| 2     | 2         | 8.7%    |
| 3     | 1         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 6         | 37.5%   |
| Fingerprint reader    | 5         | 31.25%  |
| Chipcard              | 3         | 18.75%  |
| Multimedia controller | 1         | 6.25%   |
| Camera                | 1         | 6.25%   |

