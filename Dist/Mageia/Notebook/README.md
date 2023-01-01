Mageia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Mageia.

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

Total: 46

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | Unknown                     | [702ed67add](https://linux-hardware.org/?probe=702ed67add) | Dec 17, 2022 |
| HP       | Unknown                     | [d952fd785e](https://linux-hardware.org/?probe=d952fd785e) | Dec 17, 2022 |
| Fujitsu  | CELSIUS H720                | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| Irbis    | NB264                       | [103ca2d20b](https://linux-hardware.org/?probe=103ca2d20b) | Sep 16, 2022 |
| ASUSTek  | X751LN                      | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| Schenker | VIA_14_SVI14E20             | [3adb69bbf5](https://linux-hardware.org/?probe=3adb69bbf5) | Jun 03, 2022 |
| Notebook | NH5x_NH7x_HHx_HJx_HKx       | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Dell     | Latitude E5570              | [ec640c6644](https://linux-hardware.org/?probe=ec640c6644) | May 12, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Toshiba  | dynabook R73/A              | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| Dell     | Latitude E5570              | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell     | Latitude E5570              | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell     | Precision 5530              | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [46250d420a](https://linux-hardware.org/?probe=46250d420a) | Aug 14, 2021 |
| Lenovo   | ThinkPad T61 6468AE2        | [216fbf401b](https://linux-hardware.org/?probe=216fbf401b) | Aug 05, 2021 |
| ASUSTek  | X751LN                      | [8c0efa94e8](https://linux-hardware.org/?probe=8c0efa94e8) | Jul 08, 2021 |
| Notebook | NL40_50GU                   | [baa8447288](https://linux-hardware.org/?probe=baa8447288) | May 08, 2021 |
| Medion   | DEFENDER P10                | [cb752c0a4a](https://linux-hardware.org/?probe=cb752c0a4a) | May 01, 2021 |
| Medion   | DEFENDER P10                | [f42aa05a37](https://linux-hardware.org/?probe=f42aa05a37) | May 01, 2021 |
| Fujitsu  | LIFEBOOK E752               | [8ec052ba75](https://linux-hardware.org/?probe=8ec052ba75) | Apr 15, 2021 |
| Lenovo   | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| ASUSTek  | X751LN                      | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| ASUSTek  | X556URK                     | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| ASUSTek  | X751LN                      | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| Dell     | Latitude E6530              | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Dell     | Inspiron 5480               | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| Kiano    | SlimNote 15.6               | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano    | SlimNote 15.6               | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
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
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| Lenovo   | G570 20079                  | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Mageia 8 | 16        | 55.17%  |
| Mageia 7 | 11        | 37.93%  |
| Mageia 9 | 2         | 6.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Mageia | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7  | 4         | 11.76%  |
| 5.7.19-desktop-1.mga7  | 3         | 8.82%   |
| 5.6.14-desktop-2.mga7  | 2         | 5.88%   |
| 5.15.4-desktop-1.mga8  | 2         | 5.88%   |
| 5.15.32-desktop-1.mga8 | 2         | 5.88%   |
| 6.0.10-desktop-1.mga9  | 1         | 2.94%   |
| 5.9.6-desktop-1.mga8   | 1         | 2.94%   |
| 5.9.16-desktop-1.mga7  | 1         | 2.94%   |
| 5.9.11-desktop-3.mga8  | 1         | 2.94%   |
| 5.8.5-desktop-2.mga8   | 1         | 2.94%   |
| 5.7.8-desktop-1.mga8   | 1         | 2.94%   |
| 5.6.6-desktop-1.mga7   | 1         | 2.94%   |
| 5.18.15-desktop-1.mga8 | 1         | 2.94%   |
| 5.16.10-desktop-2.mga8 | 1         | 2.94%   |
| 5.15.79-desktop-1.mga8 | 1         | 2.94%   |
| 5.15.43-desktop-1.mga8 | 1         | 2.94%   |
| 5.15.35-desktop-2.mga8 | 1         | 2.94%   |
| 5.10.46-desktop-1.mga8 | 1         | 2.94%   |
| 5.10.33-desktop-1.mga8 | 1         | 2.94%   |
| 5.10.30-desktop-1.mga8 | 1         | 2.94%   |
| 5.10.27-desktop-1.mga8 | 1         | 2.94%   |
| 5.10.25-desktop-1.mga8 | 1         | 2.94%   |
| 5.10.20-desktop-2.mga7 | 1         | 2.94%   |
| 5.10.16-desktop-1.mga8 | 1         | 2.94%   |
| 5.10.16-desktop-1.mga7 | 1         | 2.94%   |
| 5.10.12-desktop-2.mga8 | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7.19  | 7         | 20.59%  |
| 5.6.14  | 2         | 5.88%   |
| 5.15.4  | 2         | 5.88%   |
| 5.15.32 | 2         | 5.88%   |
| 5.10.16 | 2         | 5.88%   |
| 6.0.10  | 1         | 2.94%   |
| 5.9.6   | 1         | 2.94%   |
| 5.9.16  | 1         | 2.94%   |
| 5.9.11  | 1         | 2.94%   |
| 5.8.5   | 1         | 2.94%   |
| 5.7.8   | 1         | 2.94%   |
| 5.6.6   | 1         | 2.94%   |
| 5.18.15 | 1         | 2.94%   |
| 5.16.10 | 1         | 2.94%   |
| 5.15.79 | 1         | 2.94%   |
| 5.15.43 | 1         | 2.94%   |
| 5.15.35 | 1         | 2.94%   |
| 5.10.46 | 1         | 2.94%   |
| 5.10.33 | 1         | 2.94%   |
| 5.10.30 | 1         | 2.94%   |
| 5.10.27 | 1         | 2.94%   |
| 5.10.25 | 1         | 2.94%   |
| 5.10.20 | 1         | 2.94%   |
| 5.10.12 | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7     | 8         | 25%     |
| 5.15    | 7         | 21.88%  |
| 5.10    | 7         | 21.88%  |
| 5.9     | 3         | 9.38%   |
| 5.6     | 3         | 9.38%   |
| 6.0     | 1         | 3.13%   |
| 5.8     | 1         | 3.13%   |
| 5.18    | 1         | 3.13%   |
| 5.16    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 14        | 48.28%  |
| KDE     | 7         | 24.14%  |
| XFCE    | 4         | 13.79%  |
| GNOME   | 2         | 6.9%    |
| MATE    | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 26        | 96.3%   |
| Wayland | 1         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 13        | 48.15%  |
| SDDM    | 11        | 40.74%  |
| TDM     | 2         | 7.41%   |
| LightDM | 1         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| fr_FR | 5         | 18.52%  |
| en_US | 5         | 18.52%  |
| en_GB | 4         | 14.81%  |
| it_IT | 2         | 7.41%   |
| es_GT | 2         | 7.41%   |
| de_DE | 2         | 7.41%   |
| ru_RU | 1         | 3.7%    |
| pt_BR | 1         | 3.7%    |
| pl_PL | 1         | 3.7%    |
| hu_HU | 1         | 3.7%    |
| es_MX | 1         | 3.7%    |
| es_ES | 1         | 3.7%    |
| bg_BG | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 20        | 66.67%  |
| BIOS | 10        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 26        | 96.3%   |
| Xfs  | 1         | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 14        | 46.67%  |
| Unknown | 11        | 36.67%  |
| MBR     | 5         | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 85.19%  |
| Yes       | 4         | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 75.86%  |
| Yes       | 7         | 24.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 6         | 22.22%  |
| Lenovo           | 4         | 14.81%  |
| Dell             | 4         | 14.81%  |
| ASUSTek Computer | 3         | 11.11%  |
| Notebook         | 2         | 7.41%   |
| Fujitsu          | 2         | 7.41%   |
| Acer             | 2         | 7.41%   |
| Toshiba          | 1         | 3.7%    |
| Schenker         | 1         | 3.7%    |
| Medion           | 1         | 3.7%    |
| Kiano            | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 7.41%   |
| Toshiba dynabook R73/A                   | 1         | 3.7%    |
| Schenker VIA_14_SVI14E20                 | 1         | 3.7%    |
| Notebook NL40_50GU                       | 1         | 3.7%    |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 3.7%    |
| Medion DEFENDER P10                      | 1         | 3.7%    |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 3.7%    |
| Lenovo ThinkPad T430 2342A19             | 1         | 3.7%    |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 3.7%    |
| Lenovo G480 20149                        | 1         | 3.7%    |
| Kiano SlimNote 15.6                      | 1         | 3.7%    |
| HP Spectre 13 Ultrabook                  | 1         | 3.7%    |
| HP ProBook 445 G7                        | 1         | 3.7%    |
| HP Pavilion dv6                          | 1         | 3.7%    |
| HP EliteBook 840 G3                      | 1         | 3.7%    |
| Fujitsu LIFEBOOK E752                    | 1         | 3.7%    |
| Fujitsu CELSIUS H720                     | 1         | 3.7%    |
| Dell Precision 5530                      | 1         | 3.7%    |
| Dell Latitude E6530                      | 1         | 3.7%    |
| Dell Latitude E5570                      | 1         | 3.7%    |
| Dell Inspiron 5480                       | 1         | 3.7%    |
| ASUS X751LN                              | 1         | 3.7%    |
| ASUS X556URK                             | 1         | 3.7%    |
| ASUS VivoBook 15_ASUS Laptop X507UAR     | 1         | 3.7%    |
| Acer Aspire V3-772                       | 1         | 3.7%    |
| Acer Aspire 7741                         | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo ThinkPad  | 2         | 7.41%   |
| Dell Latitude    | 2         | 7.41%   |
| Acer Aspire      | 2         | 7.41%   |
| Unknown          | 2         | 7.41%   |
| Toshiba dynabook | 1         | 3.7%    |
| Schenker VIA     | 1         | 3.7%    |
| Notebook NL40    | 1         | 3.7%    |
| Notebook NH5x    | 1         | 3.7%    |
| Medion DEFENDER  | 1         | 3.7%    |
| Lenovo IdeaPad   | 1         | 3.7%    |
| Lenovo G480      | 1         | 3.7%    |
| Kiano SlimNote   | 1         | 3.7%    |
| HP Spectre       | 1         | 3.7%    |
| HP ProBook       | 1         | 3.7%    |
| HP Pavilion      | 1         | 3.7%    |
| HP EliteBook     | 1         | 3.7%    |
| Fujitsu LIFEBOOK | 1         | 3.7%    |
| Fujitsu CELSIUS  | 1         | 3.7%    |
| Dell Precision   | 1         | 3.7%    |
| Dell Inspiron    | 1         | 3.7%    |
| ASUS X751LN      | 1         | 3.7%    |
| ASUS X556URK     | 1         | 3.7%    |
| ASUS VivoBook    | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 5         | 18.52%  |
| 2016 | 4         | 14.81%  |
| 2020 | 3         | 11.11%  |
| 2018 | 3         | 11.11%  |
| 2019 | 2         | 7.41%   |
| 2017 | 2         | 7.41%   |
| 2013 | 2         | 7.41%   |
| 2007 | 2         | 7.41%   |
| 2021 | 1         | 3.7%    |
| 2014 | 1         | 3.7%    |
| 2010 | 1         | 3.7%    |
| 2008 | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 27        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 27        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 32.14%  |
| 3.01-4.0   | 6         | 21.43%  |
| 16.01-24.0 | 5         | 17.86%  |
| 8.01-16.0  | 5         | 17.86%  |
| 32.01-64.0 | 3         | 10.71%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 12        | 38.71%  |
| 1.01-2.0 | 9         | 29.03%  |
| 4.01-8.0 | 5         | 16.13%  |
| 3.01-4.0 | 5         | 16.13%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 72.41%  |
| 2      | 7         | 24.14%  |
| 3      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 59.26%  |
| Yes       | 11        | 40.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 77.78%  |
| No        | 6         | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 96.3%   |
| No        | 1         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 74.07%  |
| No        | 7         | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 5         | 18.52%  |
| UK          | 3         | 11.11%  |
| Italy       | 3         | 11.11%  |
| USA         | 2         | 7.41%   |
| Guatemala   | 2         | 7.41%   |
| Germany     | 2         | 7.41%   |
| Russia      | 1         | 3.7%    |
| Romania     | 1         | 3.7%    |
| Poland      | 1         | 3.7%    |
| Netherlands | 1         | 3.7%    |
| Mexico      | 1         | 3.7%    |
| Indonesia   | 1         | 3.7%    |
| Greece      | 1         | 3.7%    |
| Colombia    | 1         | 3.7%    |
| Bulgaria    | 1         | 3.7%    |
| Brazil      | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Guatemala City        | 2         | 6.25%   |
| Wiwersheim            | 1         | 3.13%   |
| Tver                  | 1         | 3.13%   |
| Tours                 | 1         | 3.13%   |
| Toulouse              | 1         | 3.13%   |
| Surabaya              | 1         | 3.13%   |
| Strasbourg            | 1         | 3.13%   |
| Sao Paulo             | 1         | 3.13%   |
| Sant'Angelo Lodigiano | 1         | 3.13%   |
| Rommerskirchen        | 1         | 3.13%   |
| Rome                  | 1         | 3.13%   |
| Quaregna              | 1         | 3.13%   |
| Poznan                | 1         | 3.13%   |
| Paris                 | 1         | 3.13%   |
| Oxford                | 1         | 3.13%   |
| Odenville             | 1         | 3.13%   |
| Nordenham             | 1         | 3.13%   |
| Miercurea-Ciuc        | 1         | 3.13%   |
| Marino                | 1         | 3.13%   |
| Luce                  | 1         | 3.13%   |
| León                 | 1         | 3.13%   |
| Le Faouet             | 1         | 3.13%   |
| Giannitsa             | 1         | 3.13%   |
| Eaubonne              | 1         | 3.13%   |
| Dundee                | 1         | 3.13%   |
| Denver                | 1         | 3.13%   |
| Burgas                | 1         | 3.13%   |
| Bradford              | 1         | 3.13%   |
| Bogotá               | 1         | 3.13%   |
| Aups                  | 1         | 3.13%   |
| Amsterdam             | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Unknown                 | 4         | 4      | 11.43%  |
| Toshiba                 | 4         | 5      | 11.43%  |
| Samsung Electronics     | 4         | 6      | 11.43%  |
| Kingston                | 4         | 5      | 11.43%  |
| WDC                     | 3         | 5      | 8.57%   |
| Seagate                 | 3         | 3      | 8.57%   |
| Hitachi                 | 2         | 2      | 5.71%   |
| Crucial                 | 2         | 2      | 5.71%   |
| Union Memory (Shenzhen) | 1         | 1      | 2.86%   |
| SK hynix                | 1         | 2      | 2.86%   |
| SanDisk                 | 1         | 1      | 2.86%   |
| Phison                  | 1         | 1      | 2.86%   |
| LDLC                    | 1         | 1      | 2.86%   |
| JMicron Technology      | 1         | 1      | 2.86%   |
| Intel                   | 1         | 1      | 2.86%   |
| HGST                    | 1         | 5      | 2.86%   |
| China                   | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Crucial CT120BX500SSD1 120GB                 | 2         | 5.26%   |
| WDC WDS500G2B0C-00PXH0 500GB                 | 1         | 2.63%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 2.63%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 2.63%   |
| Unknown MMC Card  8GB                        | 1         | 2.63%   |
| Unknown MMC Card  7GB                        | 1         | 2.63%   |
| Unknown MMC Card  32GB                       | 1         | 2.63%   |
| Unknown MMC Card  16GB                       | 1         | 2.63%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.63%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2.63%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 2.63%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 2.63%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 2.63%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB    | 1         | 2.63%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 2.63%   |
| Seagate ST96812AS 64GB                       | 1         | 2.63%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 2.63%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 2.63%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD          | 1         | 2.63%   |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 2.63%   |
| Samsung SSD 870 QVO 1TB                      | 1         | 2.63%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 2.63%   |
| Samsung NVMe SSD Drive 500GB                 | 1         | 2.63%   |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 2.63%   |
| Phison E12S-1TB-PHISON-SSD-B27B              | 1         | 2.63%   |
| LDLC F6+M.2 480 480GB SSD                    | 1         | 2.63%   |
| Kingston SNVS1000G 1TB                       | 1         | 2.63%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 2.63%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 2.63%   |
| Kingston SA2000M8500G 500GB                  | 1         | 2.63%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 2.63%   |
| JMicron Generic 240GB SSD                    | 1         | 2.63%   |
| Intel SSDMCEAC120B3A 120GB                   | 1         | 2.63%   |
| Hitachi HTS725050A9A364 500GB                | 1         | 2.63%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 2.63%   |
| HGST HTS541010A9E680 1TB                     | 1         | 2.63%   |
| China SATA SSD 120GB                         | 1         | 2.63%   |

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
| HGST    | 1         | 5      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 23.08%  |
| Kingston            | 2         | 2      | 15.38%  |
| Crucial             | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| SanDisk             | 1         | 1      | 7.69%   |
| LDLC                | 1         | 1      | 7.69%   |
| JMicron Technology  | 1         | 1      | 7.69%   |
| Intel               | 1         | 1      | 7.69%   |
| China               | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 13     | 34.29%  |
| HDD  | 10        | 17     | 28.57%  |
| NVMe | 9         | 12     | 25.71%  |
| MMC  | 4         | 4      | 11.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 29     | 58.82%  |
| NVMe | 9         | 12     | 26.47%  |
| MMC  | 4         | 4      | 11.76%  |
| SAS  | 1         | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 17     | 71.43%  |
| 0.51-1.0   | 6         | 13     | 28.57%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 12        | 44.44%  |
| 501-1000   | 7         | 25.93%  |
| 101-250    | 6         | 22.22%  |
| 1001-2000  | 1         | 3.7%    |
| 51-100     | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 8         | 27.59%  |
| 21-50     | 7         | 24.14%  |
| 1-20      | 6         | 20.69%  |
| 51-100    | 6         | 20.69%  |
| 1001-2000 | 1         | 3.45%   |
| 501-1000  | 1         | 3.45%   |

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
| Works    | 17        | 19     | 53.13%  |
| Detected | 12        | 24     | 37.5%   |
| Malfunc  | 3         | 3      | 9.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 65.63%  |
| AMD                          | 3         | 9.38%   |
| Samsung Electronics          | 2         | 6.25%   |
| Kingston Technology Company  | 2         | 6.25%   |
| Toshiba America Info Systems | 1         | 3.13%   |
| SK hynix                     | 1         | 3.13%   |
| SanDisk                      | 1         | 3.13%   |
| Phison Electronics           | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 11.43%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 11.43%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 5.71%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 2         | 5.71%   |
| AMD SB600 IDE                                                                  | 2         | 5.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.86%   |
| SK hynix BC511                                                                 | 1         | 2.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.86%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 2.86%   |
| Phison E12 NVMe Controller                                                     | 1         | 2.86%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 2.86%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.86%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 2.86%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.86%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 64.71%  |
| NVMe | 8         | 23.53%  |
| IDE  | 3         | 8.82%   |
| RAID | 1         | 2.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 85.19%  |
| AMD    | 4         | 14.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 7.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 7.41%   |
| AMD Turion 64 X2 Mobile Technology TL-60      | 2         | 7.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 3.7%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 3.7%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 3.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.7%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 3.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.7%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 3.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 3.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 3.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.7%    |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 3.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 3.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.7%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 10        | 37.04%  |
| Intel Core i5           | 8         | 29.63%  |
| AMD Turion 64 X2 Mobile | 2         | 7.41%   |
| AMD Ryzen 7             | 2         | 7.41%   |
| Other                   | 1         | 3.7%    |
| Intel Pentium Silver    | 1         | 3.7%    |
| Intel Pentium           | 1         | 3.7%    |
| Intel Core i3           | 1         | 3.7%    |
| Intel Atom              | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 55.56%  |
| 4      | 8         | 29.63%  |
| 8      | 2         | 7.41%   |
| 6      | 2         | 7.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 74.07%  |
| 1      | 7         | 25.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 20.69%  |
| 0x306a9    | 4         | 13.79%  |
| 0x806e9    | 3         | 10.34%  |
| 0x406e3    | 2         | 6.9%    |
| 0x40651    | 2         | 6.9%    |
| 0xa0652    | 1         | 3.45%   |
| 0x906ea    | 1         | 3.45%   |
| 0x806ec    | 1         | 3.45%   |
| 0x806eb    | 1         | 3.45%   |
| 0x706a1    | 1         | 3.45%   |
| 0x506e3    | 1         | 3.45%   |
| 0x406c4    | 1         | 3.45%   |
| 0x306c3    | 1         | 3.45%   |
| 0x206a7    | 1         | 3.45%   |
| 0x20655    | 1         | 3.45%   |
| 0x08600106 | 1         | 3.45%   |
| 0x08108109 | 1         | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 22.22%  |
| IvyBridge     | 5         | 18.52%  |
| Skylake       | 3         | 11.11%  |
| Haswell       | 3         | 11.11%  |
| K8 Hammer     | 2         | 7.41%   |
| Zen+          | 1         | 3.7%    |
| Zen 2         | 1         | 3.7%    |
| Westmere      | 1         | 3.7%    |
| Silvermont    | 1         | 3.7%    |
| SandyBridge   | 1         | 3.7%    |
| Goldmont plus | 1         | 3.7%    |
| CometLake     | 1         | 3.7%    |
| Unknown       | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 62.16%  |
| Nvidia | 9         | 24.32%  |
| AMD    | 5         | 13.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 13.51%  |
| Intel HD Graphics 620                                                                    | 3         | 8.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 5.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 5.41%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 2         | 5.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 2.7%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 2.7%    |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 2.7%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 2.7%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.7%    |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 2.7%    |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 2.7%    |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 2.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.7%    |
| Intel HD Graphics 530                                                                    | 1         | 2.7%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 2.7%    |
| AMD Renoir                                                                               | 1         | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 48.15%  |
| Intel + Nvidia | 9         | 33.33%  |
| 1 x AMD        | 4         | 14.81%  |
| Intel + AMD    | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 27        | 96.43%  |
| Proprietary | 1         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 60%     |
| 1.01-2.0   | 6         | 20%     |
| 0.01-0.5   | 3         | 10%     |
| 5.01-6.0   | 1         | 3.33%   |
| 3.01-4.0   | 1         | 3.33%   |
| 0.51-1.0   | 1         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 20%     |
| Chimei Innolux          | 6         | 20%     |
| BOE                     | 6         | 20%     |
| AU Optronics            | 4         | 13.33%  |
| Samsung Electronics     | 2         | 6.67%   |
| Chi Mei Optoelectronics | 2         | 6.67%   |
| Sharp                   | 1         | 3.33%   |
| Lenovo                  | 1         | 3.33%   |
| Ancor Communications    | 1         | 3.33%   |
| Acer                    | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch             | 2         | 6.45%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 3.23%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch        | 1         | 3.23%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch        | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 3.23%   |
| LG Display LCD Monitor LGD066A 1920x1080 344x194mm 15.5-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 3.23%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 3.23%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 1         | 3.23%   |
| LG Display LCD Monitor LGD0215 1920x1080 345x194mm 15.6-inch              | 1         | 3.23%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch           | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch          | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 3.23%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE0806 1920x1080 309x173mm 13.9-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 1         | 3.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO429D 1920x1080 382x215mm 17.3-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 1         | 3.23%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch          | 1         | 3.23%   |
| Acer G247HL ACR03FA 1920x1080 531x299mm 24.0-inch                         | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 58.62%  |
| 1366x768 (WXGA)    | 6         | 20.69%  |
| 1600x900 (HD+)     | 3         | 10.34%  |
| 1280x800 (WXGA)    | 2         | 6.9%    |
| 1680x1050 (WSXGA+) | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 43.33%  |
| 13     | 6         | 20%     |
| 17     | 5         | 16.67%  |
| 14     | 3         | 10%     |
| 24     | 2         | 6.67%   |
| 22     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 66.67%  |
| 351-400     | 5         | 16.67%  |
| 501-600     | 2         | 6.67%   |
| 201-300     | 2         | 6.67%   |
| 401-500     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 89.29%  |
| 16/10 | 3         | 10.71%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 43.33%  |
| 81-90          | 7         | 23.33%  |
| 121-130        | 5         | 16.67%  |
| 201-250        | 3         | 10%     |
| 71-80          | 2         | 6.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 15        | 51.72%  |
| 101-120 | 8         | 27.59%  |
| 51-100  | 5         | 17.24%  |
| 161-240 | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 88.89%  |
| 2     | 3         | 11.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 38.1%   |
| Realtek Semiconductor | 9         | 21.43%  |
| Qualcomm Atheros      | 6         | 14.29%  |
| Broadcom              | 5         | 11.9%   |
| Sierra Wireless       | 2         | 4.76%   |
| Broadcom Limited      | 2         | 4.76%   |
| Dell                  | 1         | 2.38%   |
| ASIX Electronics      | 1         | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 12%     |
| Intel Wireless 8260                                               | 3         | 6%      |
| Intel Wi-Fi 6 AX200                                               | 3         | 6%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 6%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6%      |
| Sierra Wireless MC8305 Modem                                      | 2         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 4%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 4%      |
| Broadcom BCM4311 802.11a/b/g                                      | 2         | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2%      |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2%      |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2%      |
| Intel Wireless-AC 9260                                            | 1         | 2%      |
| Intel Wireless 8265 / 8275                                        | 1         | 2%      |
| Intel Wireless 7260                                               | 1         | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 2%      |
| Intel Ethernet Connection I219-V                                  | 1         | 2%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2%      |
| Intel 82579V Gigabit Network Connection                           | 1         | 2%      |
| Dell DW5811e Snapdragonâ¢ X7 LTE                              | 1         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2%      |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 2%      |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 2%      |
| ASIX AX88772B                                                     | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 51.72%  |
| Qualcomm Atheros      | 6         | 20.69%  |
| Broadcom              | 4         | 13.79%  |
| Sierra Wireless       | 2         | 6.9%    |
| Realtek Semiconductor | 1         | 3.45%   |
| Dell                  | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 3         | 10.34%  |
| Intel Wi-Fi 6 AX200                                            | 3         | 10.34%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 10.34%  |
| Sierra Wireless MC8305 Modem                                   | 2         | 6.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 6.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 6.9%    |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 6.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 3.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.45%   |
| Intel Wireless-AC 9260                                         | 1         | 3.45%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.45%   |
| Intel Wireless 7260                                            | 1         | 3.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 3.45%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 8         | 38.1%   |
| Intel                 | 8         | 38.1%   |
| Broadcom Limited      | 2         | 9.52%   |
| Qualcomm Atheros      | 1         | 4.76%   |
| Broadcom              | 1         | 4.76%   |
| ASIX Electronics      | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 28.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 14.29%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 4.76%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.76%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.76%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 4.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.76%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 4.76%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 4.76%   |
| ASIX AX88772B                                                     | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 55.32%  |
| Ethernet | 21        | 44.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 82.76%  |
| Ethernet | 5         | 17.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 70.37%  |
| 1     | 7         | 25.93%  |
| 0     | 1         | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 89.29%  |
| Yes  | 3         | 10.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 10        | 47.62%  |
| IMC Networks            | 2         | 9.52%   |
| Hewlett-Packard         | 2         | 9.52%   |
| Foxconn / Hon Hai       | 2         | 9.52%   |
| Realtek Semiconductor   | 1         | 4.76%   |
| Lite-On Technology      | 1         | 4.76%   |
| Dell                    | 1         | 4.76%   |
| Cambridge Silicon Radio | 1         | 4.76%   |
| Broadcom                | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 14.29%  |
| Intel AX200 Bluetooth                               | 3         | 14.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 9.52%   |
| IMC Networks Bluetooth Device                       | 2         | 9.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 9.52%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 9.52%   |
| Realtek Bluetooth Radio                             | 1         | 4.76%   |
| Lite-On Bluetooth Device                            | 1         | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 4.76%   |
| Intel AX201 Bluetooth                               | 1         | 4.76%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 22        | 70.97%  |
| Nvidia              | 4         | 12.9%   |
| AMD                 | 4         | 12.9%   |
| C-Media Electronics | 1         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 13.89%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 13.89%  |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5.56%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 5.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 2.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.78%   |
| Nvidia Audio device                                                        | 1         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.78%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.78%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 2.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 24%     |
| SK hynix            | 5         | 20%     |
| Kingston            | 4         | 16%     |
| Micron Technology   | 3         | 12%     |
| Unknown             | 2         | 8%      |
| Corsair             | 2         | 8%      |
| Unknown (ABCD)      | 1         | 4%      |
| Smart               | 1         | 4%      |
| Crucial             | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 3.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 3.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 3.85%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 3.85%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 3.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.85%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 3.85%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 3.85%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 3.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 3.85%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR 667MT/s             | 1         | 3.85%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s            | 1         | 3.85%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 1         | 3.85%   |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s                 | 1         | 3.85%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s                | 1         | 3.85%   |
| Kingston RAM ACR16D3LS1KBG/8G 8GB SODIMM DDR3 1600MT/s           | 1         | 3.85%   |
| Kingston RAM 9905428-102.A00G 4GB SODIMM DDR3 1600MT/s           | 1         | 3.85%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 3.85%   |
| Corsair RAM CMSX16GX4M1A2666C18 16GB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| Corsair RAM CM4X8GF2666C18S2 8GB SODIMM DDR4 3000MT/s            | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 50%     |
| DDR3   | 8         | 40%     |
| LPDDR4 | 1         | 5%      |
| DDR2   | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 20        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 42.86%  |
| 8192  | 8         | 38.1%   |
| 16384 | 2         | 9.52%   |
| 2048  | 2         | 9.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 6         | 26.09%  |
| 2667  | 4         | 17.39%  |
| 2400  | 4         | 17.39%  |
| 3200  | 2         | 8.7%    |
| 2133  | 2         | 8.7%    |
| 3000  | 1         | 4.35%   |
| 1334  | 1         | 4.35%   |
| 1066  | 1         | 4.35%   |
| 975   | 1         | 4.35%   |
| 667   | 1         | 4.35%   |

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
| Chicony Electronics                    | 12        | 46.15%  |
| Realtek Semiconductor                  | 2         | 7.69%   |
| Microdia                               | 2         | 7.69%   |
| IMC Networks                           | 2         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.69%   |
| Suyin                                  | 1         | 3.85%   |
| Sunplus Innovation Technology          | 1         | 3.85%   |
| Primax Electronics                     | 1         | 3.85%   |
| Apple                                  | 1         | 3.85%   |
| Alcor Micro                            | 1         | 3.85%   |
| Acer                                   | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 3         | 11.11%  |
| Chicony Integrated Camera                                                  | 3         | 11.11%  |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 7.41%   |
| Chicony FJ Camera                                                          | 2         | 7.41%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 3.7%    |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 3.7%    |
| Realtek USB Camera                                                         | 1         | 3.7%    |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.7%    |
| Primax HP Truevision FHD                                                   | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                                              | 1         | 3.7%    |
| Microdia Integrated Webcam                                                 | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 3.7%    |
| Chicony Lenovo EasyCamera                                                  | 1         | 3.7%    |
| Chicony Integrated IR Camera                                               | 1         | 3.7%    |
| Chicony HD WebCam                                                          | 1         | 3.7%    |
| Chicony 1.3M HD WebCam                                                     | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 3.7%    |
| Apple iPhone5/5C/5S/6                                                      | 1         | 3.7%    |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 3.7%    |
| Acer BisonCam,NB Pro                                                       | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| AuthenTec                  | 3         | 37.5%   |
| Shenzhen Goodix Technology | 2         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor       | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI            | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner       | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device        | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader         | 1         | 12.5%   |
| AuthenTec Fingerprint Sensor               | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| O2 Micro | 2         | 50%     |
| Broadcom | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 44.83%  |
| 0     | 12        | 41.38%  |
| 3     | 2         | 6.9%    |
| 2     | 2         | 6.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 38.1%   |
| Graphics card         | 7         | 33.33%  |
| Chipcard              | 4         | 19.05%  |
| Multimedia controller | 1         | 4.76%   |
| Camera                | 1         | 4.76%   |

