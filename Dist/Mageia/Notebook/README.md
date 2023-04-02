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

Total: 48

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | Latitude 7370               | [b8a0b25983](https://linux-hardware.org/?probe=b8a0b25983) | Mar 30, 2023 |
| HP       | ProBook 5330m               | [2ec50367d4](https://linux-hardware.org/?probe=2ec50367d4) | Mar 11, 2023 |
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
| Mageia 8 | 17        | 54.84%  |
| Mageia 7 | 11        | 35.48%  |
| Mageia 9 | 3         | 9.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Mageia | 29        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7  | 4         | 11.11%  |
| 5.7.19-desktop-1.mga7  | 3         | 8.33%   |
| 5.6.14-desktop-2.mga7  | 2         | 5.56%   |
| 5.15.4-desktop-1.mga8  | 2         | 5.56%   |
| 5.15.32-desktop-1.mga8 | 2         | 5.56%   |
| 6.2.2-desktop-2.mga9   | 1         | 2.78%   |
| 6.0.10-desktop-1.mga9  | 1         | 2.78%   |
| 5.9.6-desktop-1.mga8   | 1         | 2.78%   |
| 5.9.16-desktop-1.mga7  | 1         | 2.78%   |
| 5.9.11-desktop-3.mga8  | 1         | 2.78%   |
| 5.8.5-desktop-2.mga8   | 1         | 2.78%   |
| 5.7.8-desktop-1.mga8   | 1         | 2.78%   |
| 5.6.6-desktop-1.mga7   | 1         | 2.78%   |
| 5.18.15-desktop-1.mga8 | 1         | 2.78%   |
| 5.16.10-desktop-2.mga8 | 1         | 2.78%   |
| 5.15.98-desktop-1.mga8 | 1         | 2.78%   |
| 5.15.79-desktop-1.mga8 | 1         | 2.78%   |
| 5.15.43-desktop-1.mga8 | 1         | 2.78%   |
| 5.15.35-desktop-2.mga8 | 1         | 2.78%   |
| 5.10.46-desktop-1.mga8 | 1         | 2.78%   |
| 5.10.33-desktop-1.mga8 | 1         | 2.78%   |
| 5.10.30-desktop-1.mga8 | 1         | 2.78%   |
| 5.10.27-desktop-1.mga8 | 1         | 2.78%   |
| 5.10.25-desktop-1.mga8 | 1         | 2.78%   |
| 5.10.20-desktop-2.mga7 | 1         | 2.78%   |
| 5.10.16-desktop-1.mga8 | 1         | 2.78%   |
| 5.10.16-desktop-1.mga7 | 1         | 2.78%   |
| 5.10.12-desktop-2.mga8 | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7.19  | 7         | 19.44%  |
| 5.6.14  | 2         | 5.56%   |
| 5.15.4  | 2         | 5.56%   |
| 5.15.32 | 2         | 5.56%   |
| 5.10.16 | 2         | 5.56%   |
| 6.2.2   | 1         | 2.78%   |
| 6.0.10  | 1         | 2.78%   |
| 5.9.6   | 1         | 2.78%   |
| 5.9.16  | 1         | 2.78%   |
| 5.9.11  | 1         | 2.78%   |
| 5.8.5   | 1         | 2.78%   |
| 5.7.8   | 1         | 2.78%   |
| 5.6.6   | 1         | 2.78%   |
| 5.18.15 | 1         | 2.78%   |
| 5.16.10 | 1         | 2.78%   |
| 5.15.98 | 1         | 2.78%   |
| 5.15.79 | 1         | 2.78%   |
| 5.15.43 | 1         | 2.78%   |
| 5.15.35 | 1         | 2.78%   |
| 5.10.46 | 1         | 2.78%   |
| 5.10.33 | 1         | 2.78%   |
| 5.10.30 | 1         | 2.78%   |
| 5.10.27 | 1         | 2.78%   |
| 5.10.25 | 1         | 2.78%   |
| 5.10.20 | 1         | 2.78%   |
| 5.10.12 | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7     | 8         | 23.53%  |
| 5.15    | 8         | 23.53%  |
| 5.10    | 7         | 20.59%  |
| 5.9     | 3         | 8.82%   |
| 5.6     | 3         | 8.82%   |
| 6.2     | 1         | 2.94%   |
| 6.0     | 1         | 2.94%   |
| 5.8     | 1         | 2.94%   |
| 5.18    | 1         | 2.94%   |
| 5.16    | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 15        | 48.39%  |
| KDE     | 8         | 25.81%  |
| XFCE    | 4         | 12.9%   |
| GNOME   | 2         | 6.45%   |
| MATE    | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 28        | 96.55%  |
| Wayland | 1         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 13        | 44.83%  |
| Unknown | 13        | 44.83%  |
| TDM     | 2         | 6.9%    |
| LightDM | 1         | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 6         | 20.69%  |
| fr_FR | 5         | 17.24%  |
| en_GB | 4         | 13.79%  |
| de_DE | 3         | 10.34%  |
| it_IT | 2         | 6.9%    |
| es_GT | 2         | 6.9%    |
| ru_RU | 1         | 3.45%   |
| pt_BR | 1         | 3.45%   |
| pl_PL | 1         | 3.45%   |
| hu_HU | 1         | 3.45%   |
| es_MX | 1         | 3.45%   |
| es_ES | 1         | 3.45%   |
| bg_BG | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 20        | 62.5%   |
| BIOS | 12        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 28        | 96.55%  |
| Xfs  | 1         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 15        | 46.88%  |
| Unknown | 11        | 34.38%  |
| MBR     | 6         | 18.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 86.21%  |
| Yes       | 4         | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 77.42%  |
| Yes       | 7         | 22.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 7         | 24.14%  |
| Dell             | 5         | 17.24%  |
| Lenovo           | 4         | 13.79%  |
| ASUSTek Computer | 3         | 10.34%  |
| Notebook         | 2         | 6.9%    |
| Fujitsu          | 2         | 6.9%    |
| Acer             | 2         | 6.9%    |
| Toshiba          | 1         | 3.45%   |
| Schenker         | 1         | 3.45%   |
| Medion           | 1         | 3.45%   |
| Kiano            | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 6.9%    |
| Toshiba dynabook R73/A                   | 1         | 3.45%   |
| Schenker VIA_14_SVI14E20                 | 1         | 3.45%   |
| Notebook NL40_50GU                       | 1         | 3.45%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 3.45%   |
| Medion DEFENDER P10                      | 1         | 3.45%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 3.45%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 3.45%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 3.45%   |
| Lenovo G480 20149                        | 1         | 3.45%   |
| Kiano SlimNote 15.6                      | 1         | 3.45%   |
| HP Spectre 13 Ultrabook                  | 1         | 3.45%   |
| HP ProBook 5330m                         | 1         | 3.45%   |
| HP ProBook 445 G7                        | 1         | 3.45%   |
| HP Pavilion dv6                          | 1         | 3.45%   |
| HP EliteBook 840 G3                      | 1         | 3.45%   |
| Fujitsu LIFEBOOK E752                    | 1         | 3.45%   |
| Fujitsu CELSIUS H720                     | 1         | 3.45%   |
| Dell Precision 5530                      | 1         | 3.45%   |
| Dell Latitude E6530                      | 1         | 3.45%   |
| Dell Latitude E5570                      | 1         | 3.45%   |
| Dell Latitude 7370                       | 1         | 3.45%   |
| Dell Inspiron 5480                       | 1         | 3.45%   |
| ASUS X751LN                              | 1         | 3.45%   |
| ASUS X556URK                             | 1         | 3.45%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR     | 1         | 3.45%   |
| Acer Aspire V3-772                       | 1         | 3.45%   |
| Acer Aspire 7741                         | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell Latitude    | 3         | 10.34%  |
| Lenovo ThinkPad  | 2         | 6.9%    |
| HP ProBook       | 2         | 6.9%    |
| Acer Aspire      | 2         | 6.9%    |
| Unknown          | 2         | 6.9%    |
| Toshiba dynabook | 1         | 3.45%   |
| Schenker VIA     | 1         | 3.45%   |
| Notebook NL40    | 1         | 3.45%   |
| Notebook NH5x    | 1         | 3.45%   |
| Medion DEFENDER  | 1         | 3.45%   |
| Lenovo IdeaPad   | 1         | 3.45%   |
| Lenovo G480      | 1         | 3.45%   |
| Kiano SlimNote   | 1         | 3.45%   |
| HP Spectre       | 1         | 3.45%   |
| HP Pavilion      | 1         | 3.45%   |
| HP EliteBook     | 1         | 3.45%   |
| Fujitsu LIFEBOOK | 1         | 3.45%   |
| Fujitsu CELSIUS  | 1         | 3.45%   |
| Dell Precision   | 1         | 3.45%   |
| Dell Inspiron    | 1         | 3.45%   |
| ASUS X751LN      | 1         | 3.45%   |
| ASUS X556URK     | 1         | 3.45%   |
| ASUS VivoBook    | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 5         | 17.24%  |
| 2016 | 4         | 13.79%  |
| 2020 | 3         | 10.34%  |
| 2018 | 3         | 10.34%  |
| 2017 | 3         | 10.34%  |
| 2019 | 2         | 6.9%    |
| 2013 | 2         | 6.9%    |
| 2007 | 2         | 6.9%    |
| 2021 | 1         | 3.45%   |
| 2014 | 1         | 3.45%   |
| 2011 | 1         | 3.45%   |
| 2010 | 1         | 3.45%   |
| 2008 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 29        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 33.33%  |
| 3.01-4.0   | 6         | 20%     |
| 8.01-16.0  | 6         | 20%     |
| 16.01-24.0 | 5         | 16.67%  |
| 32.01-64.0 | 3         | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 13        | 39.39%  |
| 1.01-2.0 | 9         | 27.27%  |
| 4.01-8.0 | 6         | 18.18%  |
| 3.01-4.0 | 5         | 15.15%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 74.19%  |
| 2      | 7         | 22.58%  |
| 3      | 1         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 62.07%  |
| Yes       | 11        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 75.86%  |
| No        | 7         | 24.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 96.55%  |
| No        | 1         | 3.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 75.86%  |
| No        | 7         | 24.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 5         | 17.24%  |
| USA         | 3         | 10.34%  |
| UK          | 3         | 10.34%  |
| Italy       | 3         | 10.34%  |
| Germany     | 3         | 10.34%  |
| Guatemala   | 2         | 6.9%    |
| Russia      | 1         | 3.45%   |
| Romania     | 1         | 3.45%   |
| Poland      | 1         | 3.45%   |
| Netherlands | 1         | 3.45%   |
| Mexico      | 1         | 3.45%   |
| Indonesia   | 1         | 3.45%   |
| Greece      | 1         | 3.45%   |
| Colombia    | 1         | 3.45%   |
| Bulgaria    | 1         | 3.45%   |
| Brazil      | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Guatemala City        | 2         | 5.88%   |
| Wiwersheim            | 1         | 2.94%   |
| Tver                  | 1         | 2.94%   |
| Tours                 | 1         | 2.94%   |
| Toulouse              | 1         | 2.94%   |
| Surabaya              | 1         | 2.94%   |
| Strasbourg            | 1         | 2.94%   |
| Sao Paulo             | 1         | 2.94%   |
| Sant'Angelo Lodigiano | 1         | 2.94%   |
| San Antonio           | 1         | 2.94%   |
| Rommerskirchen        | 1         | 2.94%   |
| Rome                  | 1         | 2.94%   |
| Quaregna              | 1         | 2.94%   |
| Poznan                | 1         | 2.94%   |
| Paris                 | 1         | 2.94%   |
| Oxford                | 1         | 2.94%   |
| Odenville             | 1         | 2.94%   |
| Nordenham             | 1         | 2.94%   |
| Miercurea-Ciuc        | 1         | 2.94%   |
| Marino                | 1         | 2.94%   |
| Luce                  | 1         | 2.94%   |
| León                 | 1         | 2.94%   |
| Le Faouet             | 1         | 2.94%   |
| Giannitsa             | 1         | 2.94%   |
| Eaubonne              | 1         | 2.94%   |
| Dundee                | 1         | 2.94%   |
| Denver                | 1         | 2.94%   |
| Chemnitz              | 1         | 2.94%   |
| Burgas                | 1         | 2.94%   |
| Bradford              | 1         | 2.94%   |
| Bogotá               | 1         | 2.94%   |
| Aups                  | 1         | 2.94%   |
| Amsterdam             | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Unknown                 | 4         | 4      | 10.81%  |
| Toshiba                 | 4         | 5      | 10.81%  |
| Samsung Electronics     | 4         | 6      | 10.81%  |
| Kingston                | 4         | 5      | 10.81%  |
| WDC                     | 3         | 5      | 8.11%   |
| Seagate                 | 3         | 3      | 8.11%   |
| Hitachi                 | 3         | 3      | 8.11%   |
| Crucial                 | 2         | 2      | 5.41%   |
| Union Memory (Shenzhen) | 1         | 1      | 2.7%    |
| SK hynix                | 1         | 2      | 2.7%    |
| SanDisk                 | 1         | 1      | 2.7%    |
| Phison                  | 1         | 1      | 2.7%    |
| LDLC                    | 1         | 1      | 2.7%    |
| KingFast                | 1         | 1      | 2.7%    |
| JMicron Technology      | 1         | 1      | 2.7%    |
| Intel                   | 1         | 1      | 2.7%    |
| HGST                    | 1         | 5      | 2.7%    |
| China                   | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Crucial CT120BX500SSD1 120GB                 | 2         | 5%      |
| WDC WDS500G2B0C-00PXH0 500GB                 | 1         | 2.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 2.5%    |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 2.5%    |
| Unknown MMC Card  8GB                        | 1         | 2.5%    |
| Unknown MMC Card  7GB                        | 1         | 2.5%    |
| Unknown MMC Card  32GB                       | 1         | 2.5%    |
| Unknown MMC Card  16GB                       | 1         | 2.5%    |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.5%    |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2.5%    |
| Toshiba MQ04ABF100 1TB                       | 1         | 2.5%    |
| Toshiba MQ01ABF050 500GB                     | 1         | 2.5%    |
| Toshiba MQ01ABD100 1TB                       | 1         | 2.5%    |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB    | 1         | 2.5%    |
| SK hynix NVMe SSD Drive 512GB                | 1         | 2.5%    |
| Seagate ST96812AS 64GB                       | 1         | 2.5%    |
| Seagate ST320LT020-9YG142 320GB              | 1         | 2.5%    |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 2.5%    |
| SanDisk SD6SN1M-256G-1006 256GB SSD          | 1         | 2.5%    |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 2.5%    |
| Samsung SSD 870 QVO 1TB                      | 1         | 2.5%    |
| Samsung SSD 860 EVO 500GB                    | 1         | 2.5%    |
| Samsung NVMe SSD Drive 500GB                 | 1         | 2.5%    |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 2.5%    |
| Phison E12S-1TB-PHISON-SSD-B27B              | 1         | 2.5%    |
| LDLC F6+M.2 480 480GB                        | 1         | 2.5%    |
| Kingston SNVS1000G 1TB                       | 1         | 2.5%    |
| Kingston SA400S37480G 480GB SSD              | 1         | 2.5%    |
| Kingston SA400S37240G 240GB SSD              | 1         | 2.5%    |
| Kingston SA2000M8500G 500GB                  | 1         | 2.5%    |
| Kingston NVMe SSD Drive 1TB                  | 1         | 2.5%    |
| KingFast SSD 256GB                           | 1         | 2.5%    |
| JMicron Generic 500GB                        | 1         | 2.5%    |
| Intel SSDMCEAC120B3A 120GB                   | 1         | 2.5%    |
| Hitachi HTS725050A9A364 500GB                | 1         | 2.5%    |
| Hitachi HTS725050A7E630 500GB                | 1         | 2.5%    |
| Hitachi HTS545050A7E380 500GB                | 1         | 2.5%    |
| HGST HTS541010A9E680 1TB                     | 1         | 2.5%    |
| China SATA SSD 120GB                         | 1         | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 4      | 27.27%  |
| Seagate | 3         | 3      | 27.27%  |
| Hitachi | 3         | 3      | 27.27%  |
| WDC     | 1         | 3      | 9.09%   |
| HGST    | 1         | 5      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 21.43%  |
| Kingston            | 2         | 2      | 14.29%  |
| Crucial             | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| LDLC                | 1         | 1      | 7.14%   |
| KingFast            | 1         | 1      | 7.14%   |
| JMicron Technology  | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| China               | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 13        | 14     | 35.14%  |
| HDD  | 11        | 18     | 29.73%  |
| NVMe | 9         | 12     | 24.32%  |
| MMC  | 4         | 4      | 10.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 31     | 61.11%  |
| NVMe | 9         | 12     | 25%     |
| MMC  | 4         | 4      | 11.11%  |
| SAS  | 1         | 1      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 19     | 73.91%  |
| 0.51-1.0   | 6         | 13     | 26.09%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 13        | 44.83%  |
| 101-250    | 7         | 24.14%  |
| 501-1000   | 7         | 24.14%  |
| 1001-2000  | 1         | 3.45%   |
| 51-100     | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 8         | 25.81%  |
| 101-250   | 8         | 25.81%  |
| 1-20      | 7         | 22.58%  |
| 51-100    | 6         | 19.35%  |
| 1001-2000 | 1         | 3.23%   |
| 501-1000  | 1         | 3.23%   |

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
| Works    | 19        | 21     | 55.88%  |
| Detected | 12        | 24     | 35.29%  |
| Malfunc  | 3         | 3      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 23        | 67.65%  |
| AMD                          | 3         | 8.82%   |
| Samsung Electronics          | 2         | 5.88%   |
| Kingston Technology Company  | 2         | 5.88%   |
| Toshiba America Info Systems | 1         | 2.94%   |
| SK hynix                     | 1         | 2.94%   |
| SanDisk                      | 1         | 2.94%   |
| Phison Electronics           | 1         | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 13.51%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 10.81%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 5.41%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 2         | 5.41%   |
| AMD SB600 IDE                                                                  | 2         | 5.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.7%    |
| SK hynix BC511                                                                 | 1         | 2.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.7%    |
| Samsung NVMe SSD Controller 980                                                | 1         | 2.7%    |
| Phison E12 NVMe Controller                                                     | 1         | 2.7%    |
| Kingston Company NVMe Controller                                               | 1         | 2.7%    |
| Kingston Company A2000 NVMe SSD                                                | 1         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.7%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 2.7%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 2.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 66.67%  |
| NVMe | 8         | 22.22%  |
| IDE  | 3         | 8.33%   |
| RAID | 1         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 86.21%  |
| AMD    | 4         | 13.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 6.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 6.9%    |
| AMD Turion 64 X2 Mobile Technology TL-60      | 2         | 6.9%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 3.45%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 3.45%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 3.45%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 3.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.45%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 3.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.45%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 3.45%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 3.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 3.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.45%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 3.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 3.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 3.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 3.45%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 3.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.45%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 10        | 34.48%  |
| Intel Core i5           | 9         | 31.03%  |
| AMD Turion 64 X2 Mobile | 2         | 6.9%    |
| AMD Ryzen 7             | 2         | 6.9%    |
| Other                   | 1         | 3.45%   |
| Intel Pentium Silver    | 1         | 3.45%   |
| Intel Pentium           | 1         | 3.45%   |
| Intel Core m5           | 1         | 3.45%   |
| Intel Core i3           | 1         | 3.45%   |
| Intel Atom              | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 58.62%  |
| 4      | 8         | 27.59%  |
| 8      | 2         | 6.9%    |
| 6      | 2         | 6.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 75.86%  |
| 1      | 7         | 24.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 22.58%  |
| 0x306a9    | 4         | 12.9%   |
| 0x806e9    | 3         | 9.68%   |
| 0x406e3    | 3         | 9.68%   |
| 0x40651    | 2         | 6.45%   |
| 0xa0652    | 1         | 3.23%   |
| 0x906ea    | 1         | 3.23%   |
| 0x806ec    | 1         | 3.23%   |
| 0x806eb    | 1         | 3.23%   |
| 0x706a1    | 1         | 3.23%   |
| 0x506e3    | 1         | 3.23%   |
| 0x406c4    | 1         | 3.23%   |
| 0x306c3    | 1         | 3.23%   |
| 0x206a7    | 1         | 3.23%   |
| 0x20655    | 1         | 3.23%   |
| 0x08600106 | 1         | 3.23%   |
| 0x08108109 | 1         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 20.69%  |
| IvyBridge     | 5         | 17.24%  |
| Skylake       | 4         | 13.79%  |
| Haswell       | 3         | 10.34%  |
| SandyBridge   | 2         | 6.9%    |
| K8 Hammer     | 2         | 6.9%    |
| Zen+          | 1         | 3.45%   |
| Zen 2         | 1         | 3.45%   |
| Westmere      | 1         | 3.45%   |
| Silvermont    | 1         | 3.45%   |
| Goldmont plus | 1         | 3.45%   |
| CometLake     | 1         | 3.45%   |
| Unknown       | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 64.1%   |
| Nvidia | 9         | 23.08%  |
| AMD    | 5         | 12.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 12.82%  |
| Intel HD Graphics 620                                                                    | 3         | 7.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 5.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 5.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.13%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 2         | 5.13%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 2.56%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 2.56%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 2.56%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 2.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.56%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 2.56%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 2.56%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 2.56%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.56%   |
| Intel HD Graphics 530                                                                    | 1         | 2.56%   |
| Intel HD Graphics 515                                                                    | 1         | 2.56%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 2.56%   |
| AMD Renoir                                                                               | 1         | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 51.72%  |
| Intel + Nvidia | 9         | 31.03%  |
| 1 x AMD        | 4         | 13.79%  |
| Intel + AMD    | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 29        | 96.67%  |
| Proprietary | 1         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 62.5%   |
| 1.01-2.0   | 6         | 18.75%  |
| 0.01-0.5   | 3         | 9.38%   |
| 5.01-6.0   | 1         | 3.13%   |
| 3.01-4.0   | 1         | 3.13%   |
| 0.51-1.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 18.75%  |
| Chimei Innolux          | 6         | 18.75%  |
| BOE                     | 6         | 18.75%  |
| AU Optronics            | 4         | 12.5%   |
| Samsung Electronics     | 3         | 9.38%   |
| Sharp                   | 2         | 6.25%   |
| Chi Mei Optoelectronics | 2         | 6.25%   |
| Lenovo                  | 1         | 3.13%   |
| Ancor Communications    | 1         | 3.13%   |
| Acer                    | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch             | 2         | 6.06%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 3.03%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch                   | 1         | 3.03%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch        | 1         | 3.03%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch        | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC3155 1366x768 293x165mm 13.2-inch      | 1         | 3.03%   |
| LG Display LCD Monitor LGD066A 1920x1080 344x194mm 15.5-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 3.03%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 3.03%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 1         | 3.03%   |
| LG Display LCD Monitor LGD0215 1920x1080 345x194mm 15.6-inch              | 1         | 3.03%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                   | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch           | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch          | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 3.03%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE0806 1920x1080 309x173mm 13.9-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 1         | 3.03%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO429D 1920x1080 382x215mm 17.3-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 1         | 3.03%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch          | 1         | 3.03%   |
| Acer G247HL ACR03FA 1920x1080 531x299mm 24.0-inch                         | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 54.84%  |
| 1366x768 (WXGA)    | 6         | 19.35%  |
| 1600x900 (HD+)     | 3         | 9.68%   |
| 1280x800 (WXGA)    | 2         | 6.45%   |
| 3200x1800 (QHD+)   | 1         | 3.23%   |
| 1920x1200 (WUXGA)  | 1         | 3.23%   |
| 1680x1050 (WSXGA+) | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 40.63%  |
| 13     | 7         | 21.88%  |
| 17     | 6         | 18.75%  |
| 14     | 3         | 9.38%   |
| 24     | 2         | 6.25%   |
| 22     | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 62.5%   |
| 351-400     | 6         | 18.75%  |
| 201-300     | 3         | 9.38%   |
| 501-600     | 2         | 6.25%   |
| 401-500     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 86.67%  |
| 16/10 | 4         | 13.33%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 40.63%  |
| 81-90          | 7         | 21.88%  |
| 121-130        | 5         | 15.63%  |
| 71-80          | 3         | 9.38%   |
| 201-250        | 3         | 9.38%   |
| 131-140        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 51.61%  |
| 101-120       | 8         | 25.81%  |
| 51-100        | 5         | 16.13%  |
| More than 240 | 1         | 3.23%   |
| 161-240       | 1         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 26        | 89.66%  |
| 2     | 3         | 10.34%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 40%     |
| Realtek Semiconductor | 9         | 20%     |
| Qualcomm Atheros      | 6         | 13.33%  |
| Broadcom              | 6         | 13.33%  |
| Sierra Wireless       | 2         | 4.44%   |
| Broadcom Limited      | 2         | 4.44%   |
| Dell                  | 1         | 2.22%   |
| ASIX Electronics      | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 11.11%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 7.41%   |
| Intel Wireless 8260                                               | 3         | 5.56%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 5.56%   |
| Sierra Wireless MC8305 Modem                                      | 2         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 3.7%    |
| Broadcom BCM4311 802.11a/b/g                                      | 2         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.85%   |
| Intel Wireless-AC 9260                                            | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.85%   |
| Intel Wireless 7260                                               | 1         | 1.85%   |
| Intel Wireless 3165                                               | 1         | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.85%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.85%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.85%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                              | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.85%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.85%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.85%   |
| Broadcom BCM4323 802.11abgn Wireless Adapter                      | 1         | 1.85%   |
| ASIX AX88772B                                                     | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 53.13%  |
| Qualcomm Atheros      | 6         | 18.75%  |
| Broadcom              | 5         | 15.63%  |
| Sierra Wireless       | 2         | 6.25%   |
| Realtek Semiconductor | 1         | 3.13%   |
| Dell                  | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 12.5%   |
| Intel Wireless 8260                                            | 3         | 9.38%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 9.38%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 6.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 6.25%   |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 3.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Intel Wireless-AC 9260                                         | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.13%   |
| Intel Wireless 7260                                            | 1         | 3.13%   |
| Intel Wireless 3165                                            | 1         | 3.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 3.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 3.13%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 3.13%   |
| Broadcom BCM4323 802.11abgn Wireless Adapter                   | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 40.91%  |
| Realtek Semiconductor | 8         | 36.36%  |
| Broadcom Limited      | 2         | 9.09%   |
| Qualcomm Atheros      | 1         | 4.55%   |
| Broadcom              | 1         | 4.55%   |
| ASIX Electronics      | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 27.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 18.18%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 4.55%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.55%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.55%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 4.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.55%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 4.55%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 4.55%   |
| ASIX AX88772B                                                     | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 56%     |
| Ethernet | 22        | 44%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 83.87%  |
| Ethernet | 5         | 16.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 68.97%  |
| 1     | 8         | 27.59%  |
| 0     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 86.67%  |
| Yes  | 4         | 13.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 11        | 47.83%  |
| Hewlett-Packard         | 3         | 13.04%  |
| IMC Networks            | 2         | 8.7%    |
| Foxconn / Hon Hai       | 2         | 8.7%    |
| Realtek Semiconductor   | 1         | 4.35%   |
| Lite-On Technology      | 1         | 4.35%   |
| Dell                    | 1         | 4.35%   |
| Cambridge Silicon Radio | 1         | 4.35%   |
| Broadcom                | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 17.39%  |
| Intel AX200 Bluetooth                               | 3         | 13.04%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 8.7%    |
| IMC Networks Bluetooth Device                       | 2         | 8.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 8.7%    |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 8.7%    |
| Realtek Bluetooth Radio                             | 1         | 4.35%   |
| Lite-On Bluetooth Device                            | 1         | 4.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 4.35%   |
| Intel AX201 Bluetooth                               | 1         | 4.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 4.35%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 24        | 72.73%  |
| Nvidia              | 4         | 12.12%  |
| AMD                 | 4         | 12.12%  |
| C-Media Electronics | 1         | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 15.79%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 13.16%  |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5.26%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 5.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 2.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.63%   |
| Nvidia Audio device                                                        | 1         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.63%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.63%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.63%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.63%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 25%     |
| SK hynix            | 6         | 21.43%  |
| Kingston            | 4         | 14.29%  |
| Unknown             | 3         | 10.71%  |
| Micron Technology   | 3         | 10.71%  |
| Corsair             | 2         | 7.14%   |
| Unknown (ABCD)      | 1         | 3.57%   |
| Smart               | 1         | 3.57%   |
| Crucial             | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 3.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 3.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 3.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 3.45%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 3.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.45%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 3.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.45%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 3.45%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 3.45%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 3.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.45%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 3.45%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR 667MT/s             | 1         | 3.45%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 1         | 3.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 3.45%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s            | 1         | 3.45%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 3.45%   |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s                 | 1         | 3.45%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s                | 1         | 3.45%   |
| Kingston RAM ACR16D3LS1KBG/8G 8GB SODIMM DDR3 1600MT/s           | 1         | 3.45%   |
| Kingston RAM 9905428-102.A00G 4GB SODIMM DDR3 1600MT/s           | 1         | 3.45%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 3.45%   |
| Corsair RAM CMSX16GX4M1A2666C18 16GB SODIMM DDR4 2667MT/s        | 1         | 3.45%   |
| Corsair RAM CM4X8GF2666C18S2 8GB SODIMM DDR4 3000MT/s            | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 45.45%  |
| DDR3   | 9         | 40.91%  |
| LPDDR4 | 1         | 4.55%   |
| LPDDR3 | 1         | 4.55%   |
| DDR2   | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 22        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 11        | 47.83%  |
| 8192  | 8         | 34.78%  |
| 16384 | 2         | 8.7%    |
| 2048  | 2         | 8.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 8         | 32%     |
| 2667  | 4         | 16%     |
| 2400  | 4         | 16%     |
| 3200  | 2         | 8%      |
| 2133  | 2         | 8%      |
| 3000  | 1         | 4%      |
| 1334  | 1         | 4%      |
| 1066  | 1         | 4%      |
| 975   | 1         | 4%      |
| 667   | 1         | 4%      |

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
| Chicony Electronics                    | 13        | 46.43%  |
| Realtek Semiconductor                  | 3         | 10.71%  |
| Microdia                               | 2         | 7.14%   |
| IMC Networks                           | 2         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.14%   |
| Suyin                                  | 1         | 3.57%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Primax Electronics                     | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |
| Alcor Micro                            | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 3         | 10.34%  |
| Chicony Integrated Camera                                                  | 3         | 10.34%  |
| Realtek Integrated_Webcam_HD                                               | 2         | 6.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 6.9%    |
| Chicony FJ Camera                                                          | 2         | 6.9%    |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 3.45%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 3.45%   |
| Realtek USB Camera                                                         | 1         | 3.45%   |
| Primax HP Truevision FHD                                                   | 1         | 3.45%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 3.45%   |
| Microdia Integrated Webcam                                                 | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 3.45%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 3.45%   |
| Chicony Integrated IR Camera                                               | 1         | 3.45%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 3.45%   |
| Chicony HD WebCam                                                          | 1         | 3.45%   |
| Chicony 1.3M HD WebCam                                                     | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 3.45%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 1         | 3.45%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 3.45%   |
| Acer BisonCam,NB Pro                                                       | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| AuthenTec                  | 3         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor       | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI            | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner       | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device        | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader         | 1         | 11.11%  |
| AuthenTec Fingerprint Sensor               | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 60%     |
| O2 Micro | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 40%     |
| Broadcom 5880                                                                | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 14        | 45.16%  |
| 0     | 12        | 38.71%  |
| 2     | 3         | 9.68%   |
| 3     | 2         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 37.5%   |
| Graphics card         | 7         | 29.17%  |
| Chipcard              | 5         | 20.83%  |
| Net/wireless          | 1         | 4.17%   |
| Multimedia controller | 1         | 4.17%   |
| Camera                | 1         | 4.17%   |

