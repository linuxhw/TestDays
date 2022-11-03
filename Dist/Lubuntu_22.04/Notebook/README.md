Lubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 82

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-43-generic     | 11        | 15.49%  |
| 5.15.0-30-generic     | 8         | 11.27%  |
| 5.15.0-46-generic     | 7         | 9.86%   |
| 5.15.0-27-generic     | 6         | 8.45%   |
| 5.15.0-25-generic     | 6         | 8.45%   |
| 5.15.0-47-generic     | 5         | 7.04%   |
| 5.15.0-50-generic     | 3         | 4.23%   |
| 5.15.0-48-generic     | 3         | 4.23%   |
| 5.15.0-41-generic     | 3         | 4.23%   |
| 5.15.0-40-generic     | 3         | 4.23%   |
| 5.15.0-35-generic     | 3         | 4.23%   |
| 5.15.0-52-generic     | 2         | 2.82%   |
| 5.15.0-37-generic     | 2         | 2.82%   |
| 5.15.0-33-generic     | 2         | 2.82%   |
| 5.19.8-xanmod1        | 1         | 1.41%   |
| 5.19.0-051900-generic | 1         | 1.41%   |
| 5.18.0-051800-generic | 1         | 1.41%   |
| 5.15.0-39-generic     | 1         | 1.41%   |
| 5.15.0-28-generic     | 1         | 1.41%   |
| 5.15.0-23-generic     | 1         | 1.41%   |
| 5.15.0-18-generic     | 1         | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 65        | 95.59%  |
| 5.19.8  | 1         | 1.47%   |
| 5.19.0  | 1         | 1.47%   |
| 5.18.0  | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 65        | 95.59%  |
| 5.19    | 2         | 2.94%   |
| 5.18    | 1         | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 64        | 98.46%  |
| X-Cinnamon | 1         | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 64        | 98.46%  |
| Tty  | 1         | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 61        | 93.85%  |
| Unknown | 3         | 4.62%   |
| LightDM | 1         | 1.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 18        | 27.27%  |
| pt_BR | 6         | 9.09%   |
| en_GB | 5         | 7.58%   |
| C     | 5         | 7.58%   |
| pl_PL | 4         | 6.06%   |
| it_IT | 4         | 6.06%   |
| fr_FR | 4         | 6.06%   |
| de_DE | 3         | 4.55%   |
| nl_BE | 2         | 3.03%   |
| es_CR | 2         | 3.03%   |
| en_CA | 2         | 3.03%   |
| en_AG | 2         | 3.03%   |
| ja_JP | 1         | 1.52%   |
| fi_FI | 1         | 1.52%   |
| es_MX | 1         | 1.52%   |
| es_CL | 1         | 1.52%   |
| es_AR | 1         | 1.52%   |
| en_ZA | 1         | 1.52%   |
| en_PH | 1         | 1.52%   |
| en_AU | 1         | 1.52%   |
| el_GR | 1         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 41        | 62.12%  |
| EFI  | 25        | 37.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 59        | 89.39%  |
| Overlay | 5         | 7.58%   |
| Ext2    | 1         | 1.52%   |
| Btrfs   | 1         | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 26        | 39.39%  |
| Unknown | 24        | 36.36%  |
| MBR     | 16        | 24.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 89.39%  |
| Yes       | 7         | 10.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 80.3%   |
| Yes       | 13        | 19.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 21.54%  |
| Dell             | 10        | 15.38%  |
| Hewlett-Packard  | 8         | 12.31%  |
| Google           | 5         | 7.69%   |
| Sony             | 3         | 4.62%   |
| ASUSTek Computer | 3         | 4.62%   |
| Apple            | 3         | 4.62%   |
| Acer             | 3         | 4.62%   |
| Mediacom         | 2         | 3.08%   |
| Gateway          | 2         | 3.08%   |
| Fujitsu          | 2         | 3.08%   |
| Unknown          | 2         | 3.08%   |
| Toshiba          | 1         | 1.54%   |
| Prestigio        | 1         | 1.54%   |
| Packard Bell     | 1         | 1.54%   |
| OEM              | 1         | 1.54%   |
| Kiano            | 1         | 1.54%   |
| Intel            | 1         | 1.54%   |
| IFSA             | 1         | 1.54%   |
| Chuwi            | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 4.62%   |
| Mediacom WinPad 11,6 FullHD- WPU11       | 2         | 3.08%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 2         | 3.08%   |
| Apple MacBookPro8,1                      | 2         | 3.08%   |
| Toshiba Satellite L40                    | 1         | 1.54%   |
| Sony VPCEB15FM                           | 1         | 1.54%   |
| Sony VGN-SZ71WN_C                        | 1         | 1.54%   |
| Sony SVE14A2V1EW                         | 1         | 1.54%   |
| Prestigio PSB141C01BFH                   | 1         | 1.54%   |
| Packard Bell EasyNote TS44HR             | 1         | 1.54%   |
| Lenovo Z70-80 80FG                       | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02 | 1         | 1.54%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 1.54%   |
| Lenovo ThinkPad T410 2537CS0             | 1         | 1.54%   |
| Lenovo ThinkPad SL510 2847CXG            | 1         | 1.54%   |
| Lenovo ThinkPad E550 20DF00CUFR          | 1         | 1.54%   |
| Lenovo IdeaPad S145-15IGM 81MX           | 1         | 1.54%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 1         | 1.54%   |
| Lenovo IdeaPad 330-15IKB Touch 81DJ      | 1         | 1.54%   |
| Lenovo G50-70 20351                      | 1         | 1.54%   |
| Lenovo G50-30 80G0                       | 1         | 1.54%   |
| Lenovo B590 20208                        | 1         | 1.54%   |
| Kiano SlimNote 14.1                      | 1         | 1.54%   |
| Intel Infoway                            | 1         | 1.54%   |
| IFSA Positivo BGH                        | 1         | 1.54%   |
| HP ProBook 640 G1                        | 1         | 1.54%   |
| HP ProBook 4730s                         | 1         | 1.54%   |
| HP Pavilion Sleekbook 15 PC              | 1         | 1.54%   |
| HP Pavilion g6                           | 1         | 1.54%   |
| HP Pavilion dv4                          | 1         | 1.54%   |
| HP Laptop 15-da0xxx                      | 1         | 1.54%   |
| HP 245 G2                                | 1         | 1.54%   |
| HP 15 Notebook PC                        | 1         | 1.54%   |
| Google Terra                             | 1         | 1.54%   |
| Google Relm                              | 1         | 1.54%   |
| Google Celes                             | 1         | 1.54%   |
| Google Bobba360                          | 1         | 1.54%   |
| Google Apel                              | 1         | 1.54%   |
| Gateway Sonic-C                          | 1         | 1.54%   |
| Gateway NE46R                            | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 5         | 7.69%   |
| Lenovo IdeaPad         | 5         | 7.69%   |
| HP Pavilion            | 3         | 4.62%   |
| Dell Latitude          | 3         | 4.62%   |
| Acer Aspire            | 3         | 4.62%   |
| Unknown                | 3         | 4.62%   |
| Mediacom WinPad        | 2         | 3.08%   |
| HP ProBook             | 2         | 3.08%   |
| Fujitsu LIFEBOOK       | 2         | 3.08%   |
| Dell XPS               | 2         | 3.08%   |
| Apple MacBookPro8      | 2         | 3.08%   |
| Toshiba Satellite      | 1         | 1.54%   |
| Sony VPCEB15FM         | 1         | 1.54%   |
| Sony VGN-SZ71WN        | 1         | 1.54%   |
| Sony SVE14A2V1EW       | 1         | 1.54%   |
| Prestigio PSB141C01BFH | 1         | 1.54%   |
| Packard Bell EasyNote  | 1         | 1.54%   |
| Lenovo Z70-80          | 1         | 1.54%   |
| Lenovo G50-70          | 1         | 1.54%   |
| Lenovo G50-30          | 1         | 1.54%   |
| Lenovo B590            | 1         | 1.54%   |
| Kiano SlimNote         | 1         | 1.54%   |
| Intel Infoway          | 1         | 1.54%   |
| IFSA Positivo          | 1         | 1.54%   |
| HP Laptop              | 1         | 1.54%   |
| HP 245                 | 1         | 1.54%   |
| HP 15                  | 1         | 1.54%   |
| Google Terra           | 1         | 1.54%   |
| Google Relm            | 1         | 1.54%   |
| Google Celes           | 1         | 1.54%   |
| Google Bobba360        | 1         | 1.54%   |
| Google Apel            | 1         | 1.54%   |
| Gateway Sonic-C        | 1         | 1.54%   |
| Gateway NE46R          | 1         | 1.54%   |
| Dell Vostro            | 1         | 1.54%   |
| Dell System            | 1         | 1.54%   |
| Dell Studio            | 1         | 1.54%   |
| Dell Precision         | 1         | 1.54%   |
| Dell Inspiron          | 1         | 1.54%   |
| Chuwi GemiBook         | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 9         | 13.85%  |
| 2011 | 8         | 12.31%  |
| 2013 | 7         | 10.77%  |
| 2019 | 5         | 7.69%   |
| 2014 | 5         | 7.69%   |
| 2016 | 4         | 6.15%   |
| 2008 | 4         | 6.15%   |
| 2022 | 3         | 4.62%   |
| 2021 | 3         | 4.62%   |
| 2020 | 3         | 4.62%   |
| 2015 | 3         | 4.62%   |
| 2010 | 3         | 4.62%   |
| 2007 | 3         | 4.62%   |
| 2017 | 2         | 3.08%   |
| 2009 | 2         | 3.08%   |
| 2018 | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 65        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 63        | 96.92%  |
| Enabled  | 2         | 3.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 92.31%  |
| Yes  | 5         | 7.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 26        | 39.39%  |
| 4.01-8.0   | 16        | 24.24%  |
| 1.01-2.0   | 10        | 15.15%  |
| 8.01-16.0  | 6         | 9.09%   |
| 2.01-3.0   | 4         | 6.06%   |
| 16.01-24.0 | 3         | 4.55%   |
| 32.01-64.0 | 1         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 31        | 46.97%  |
| 0.51-1.0 | 20        | 30.3%   |
| 2.01-3.0 | 12        | 18.18%  |
| 3.01-4.0 | 2         | 3.03%   |
| 4.01-8.0 | 1         | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 83.08%  |
| 2      | 10        | 15.38%  |
| 0      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 53.85%  |
| Yes       | 30        | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 76.92%  |
| No        | 15        | 23.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 90.77%  |
| No        | 6         | 9.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 67.69%  |
| No        | 21        | 32.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 10        | 15.38%  |
| Brazil       | 6         | 9.23%   |
| UK           | 4         | 6.15%   |
| Poland       | 4         | 6.15%   |
| Italy        | 4         | 6.15%   |
| Germany      | 4         | 6.15%   |
| France       | 4         | 6.15%   |
| Belgium      | 3         | 4.62%   |
| Vietnam      | 2         | 3.08%   |
| Russia       | 2         | 3.08%   |
| Hungary      | 2         | 3.08%   |
| Costa Rica   | 2         | 3.08%   |
| Canada       | 2         | 3.08%   |
| Ukraine      | 1         | 1.54%   |
| Turkey       | 1         | 1.54%   |
| Sweden       | 1         | 1.54%   |
| South Africa | 1         | 1.54%   |
| Portugal     | 1         | 1.54%   |
| Philippines  | 1         | 1.54%   |
| Netherlands  | 1         | 1.54%   |
| Mexico       | 1         | 1.54%   |
| Kenya        | 1         | 1.54%   |
| Japan        | 1         | 1.54%   |
| Indonesia    | 1         | 1.54%   |
| Greece       | 1         | 1.54%   |
| Finland      | 1         | 1.54%   |
| Chile        | 1         | 1.54%   |
| Australia    | 1         | 1.54%   |
| Argentina    | 1         | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 3         | 4.62%   |
| Sarospatak       | 2         | 3.08%   |
| Porto Alegre     | 2         | 3.08%   |
| Heredia          | 2         | 3.08%   |
| Yoshkar-Ola      | 1         | 1.54%   |
| Yorkville        | 1         | 1.54%   |
| Wolfhagen        | 1         | 1.54%   |
| Warsaw           | 1         | 1.54%   |
| Volzhskiy        | 1         | 1.54%   |
| Tychy            | 1         | 1.54%   |
| Thessaloniki     | 1         | 1.54%   |
| Surabaya         | 1         | 1.54%   |
| Stuttgart        | 1         | 1.54%   |
| Strzyzow         | 1         | 1.54%   |
| Stockholm        | 1         | 1.54%   |
| Southampton      | 1         | 1.54%   |
| South Burlington | 1         | 1.54%   |
| Sao Paulo        | 1         | 1.54%   |
| Santiago         | 1         | 1.54%   |
| Roswell          | 1         | 1.54%   |
| Rossano Veneto   | 1         | 1.54%   |
| Rio de Janeiro   | 1         | 1.54%   |
| Quezon City      | 1         | 1.54%   |
| Pretoria         | 1         | 1.54%   |
| Pontypool        | 1         | 1.54%   |
| Pisa             | 1         | 1.54%   |
| Perth Amboy      | 1         | 1.54%   |
| Palermo          | 1         | 1.54%   |
| Novo Gama        | 1         | 1.54%   |
| Newtown          | 1         | 1.54%   |
| New York         | 1         | 1.54%   |
| Nairobi          | 1         | 1.54%   |
| Minato-ku        | 1         | 1.54%   |
| Millville        | 1         | 1.54%   |
| Milan            | 1         | 1.54%   |
| Menen            | 1         | 1.54%   |
| Melbourne        | 1         | 1.54%   |
| Medford          | 1         | 1.54%   |
| Lisbon           | 1         | 1.54%   |
| Kyiv             | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 14        | 21     | 20.59%  |
| Toshiba             | 8         | 9      | 11.76%  |
| Seagate             | 8         | 8      | 11.76%  |
| WDC                 | 7         | 7      | 10.29%  |
| Samsung Electronics | 5         | 8      | 7.35%   |
| Hitachi             | 3         | 3      | 4.41%   |
| SPCC                | 2         | 3      | 2.94%   |
| SanDisk             | 2         | 2      | 2.94%   |
| Apacer              | 2         | 2      | 2.94%   |
| W800S               | 1         | 1      | 1.47%   |
| UMIS                | 1         | 1      | 1.47%   |
| Transcend           | 1         | 1      | 1.47%   |
| SK hynix            | 1         | 1      | 1.47%   |
| Rogueware           | 1         | 1      | 1.47%   |
| Micron Technology   | 1         | 1      | 1.47%   |
| Leqixiang           | 1         | 1      | 1.47%   |
| Lenovo              | 1         | 1      | 1.47%   |
| Kingston            | 1         | 1      | 1.47%   |
| KINGPOWER           | 1         | 1      | 1.47%   |
| Intel               | 1         | 1      | 1.47%   |
| HUSKY               | 1         | 1      | 1.47%   |
| HGST                | 1         | 1      | 1.47%   |
| Fujitsu             | 1         | 1      | 1.47%   |
| Crucial             | 1         | 1      | 1.47%   |
| Apple               | 1         | 2      | 1.47%   |
| A-DATA Technology   | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 1TB        | 2         | 2.67%   |
| Unknown NCard  32GB              | 2         | 2.67%   |
| Unknown MMC64G  64GB             | 2         | 2.67%   |
| Unknown DA4032  32GB             | 2         | 2.67%   |
| Toshiba MQ01ABF050 500GB         | 2         | 2.67%   |
| SPCC Solid State Disk 120GB      | 2         | 2.67%   |
| Seagate ST9500325AS 500GB        | 2         | 2.67%   |
| WDC WDS500G2B0A 500GB SSD        | 1         | 1.33%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 1.33%   |
| WDC WD5000LPCX-60VHAT0 500GB     | 1         | 1.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB     | 1         | 1.33%   |
| WDC WD3200BEKT-75PVMT1 320GB     | 1         | 1.33%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1.33%   |
| WDC WD10JPVX-75JC3T0 1TB         | 1         | 1.33%   |
| W800S 256GB SSD                  | 1         | 1.33%   |
| Unknown SF64G  64GB              | 1         | 1.33%   |
| Unknown SC64G  64GB              | 1         | 1.33%   |
| Unknown MMC Card  64GB           | 1         | 1.33%   |
| Unknown MMC Card  32GB           | 1         | 1.33%   |
| Unknown ISOCOM  64GB             | 1         | 1.33%   |
| Unknown HAG4a2  16GB             | 1         | 1.33%   |
| Unknown ED2S5  128GB             | 1         | 1.33%   |
| Unknown DA4064  64GB             | 1         | 1.33%   |
| Unknown CGND3R  64GB             | 1         | 1.33%   |
| Unknown BJNB4R  32GB             | 1         | 1.33%   |
| Unknown ASTC  8GB                | 1         | 1.33%   |
| Unknown ASTC  32GB               | 1         | 1.33%   |
| UMIS RPFTJ256PDD2MWX 256GB       | 1         | 1.33%   |
| Transcend TS512GMTS800 512GB SSD | 1         | 1.33%   |
| Toshiba THNSNJ128GCSY 128GB SSD  | 1         | 1.33%   |
| Toshiba MQ01ABD075 752GB         | 1         | 1.33%   |
| Toshiba MQ01ABD050 500GB         | 1         | 1.33%   |
| Toshiba MK8009GAH 80GB           | 1         | 1.33%   |
| Toshiba MK3261GSYN 320GB         | 1         | 1.33%   |
| Toshiba MK1646GSX 160GB          | 1         | 1.33%   |
| SK hynix NVMe SSD Drive 256GB    | 1         | 1.33%   |
| Seagate ST9320325ASG 320GB       | 1         | 1.33%   |
| Seagate ST9320325AS 320GB        | 1         | 1.33%   |
| Seagate ST320LT020-9YG142 320GB  | 1         | 1.33%   |
| Seagate ST320LT007-9ZV142 320GB  | 1         | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 28.57%  |
| Toshiba             | 7         | 8      | 25%     |
| WDC                 | 5         | 5      | 17.86%  |
| Hitachi             | 3         | 3      | 10.71%  |
| Unknown             | 2         | 2      | 7.14%   |
| Samsung Electronics | 1         | 4      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 16.67%  |
| WDC                 | 2         | 2      | 8.33%   |
| SPCC                | 2         | 3      | 8.33%   |
| Apacer              | 2         | 2      | 8.33%   |
| W800S               | 1         | 1      | 4.17%   |
| Transcend           | 1         | 1      | 4.17%   |
| Toshiba             | 1         | 1      | 4.17%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Rogueware           | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| Leqixiang           | 1         | 1      | 4.17%   |
| Lenovo              | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| KINGPOWER           | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| HUSKY               | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 32     | 40%     |
| SSD  | 24        | 25     | 34.29%  |
| MMC  | 15        | 20     | 21.43%  |
| NVMe | 3         | 4      | 4.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 55     | 70.59%  |
| MMC  | 15        | 20     | 22.06%  |
| NVMe | 3         | 4      | 4.41%   |
| SAS  | 2         | 2      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 45     | 76.47%  |
| 0.51-1.0   | 12        | 12     | 23.53%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 33.33%  |
| 251-500    | 20        | 30.3%   |
| 1-20       | 8         | 12.12%  |
| 51-100     | 6         | 9.09%   |
| 21-50      | 5         | 7.58%   |
| 501-1000   | 4         | 6.06%   |
| Unknown    | 1         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 39        | 59.09%  |
| 21-50   | 16        | 24.24%  |
| 101-250 | 5         | 7.58%   |
| 51-100  | 4         | 6.06%   |
| 251-500 | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 2         | 2      | 15.38%  |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 7.69%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 7.69%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 7.69%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 7.69%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 7.69%   |
| Samsung Electronics HM121HI 120GB  | 1         | 4      | 7.69%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 7.69%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 7.69%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 46.15%  |
| Toshiba             | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 4      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| Fujitsu             | 1         | 1      | 7.69%   |
| Apacer              | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 50%     |
| Toshiba             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 4      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| Fujitsu             | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 15     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

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
| Detected | 38        | 49     | 56.72%  |
| Works    | 16        | 16     | 23.88%  |
| Malfunc  | 13        | 16     | 19.4%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 47        | 83.93%  |
| AMD                     | 6         | 10.71%  |
| Union Memory (Shenzhen) | 1         | 1.79%   |
| SK hynix                | 1         | 1.79%   |
| Nvidia                  | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 12.9%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 8.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 8.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 6.45%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 6.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 4.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 4.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 3.23%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 1.61%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.61%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 1.61%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.61%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.61%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 1.61%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.61%   |
| AMD SB600 IDE                                                                    | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 49        | 81.67%  |
| IDE  | 7         | 11.67%  |
| RAID | 2         | 3.33%   |
| NVMe | 2         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 92.31%  |
| AMD    | 5         | 7.69%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 6.15%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 3.08%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 3.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 3.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 3.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 3.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 3.08%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 3.08%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 2         | 3.08%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 3.08%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 1.54%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 1.54%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.54%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.54%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.54%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 1.54%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.54%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 1.54%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.54%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.54%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 1         | 1.54%   |
| Intel Core i3-2348M CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.54%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.54%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 1.54%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 1         | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 15        | 23.08%  |
| Intel Celeron      | 15        | 23.08%  |
| Intel Core 2 Duo   | 8         | 12.31%  |
| Intel Core i7      | 7         | 10.77%  |
| Intel Core i3      | 5         | 7.69%   |
| Intel Atom         | 5         | 7.69%   |
| Intel Pentium      | 3         | 4.62%   |
| AMD A6             | 3         | 4.62%   |
| Intel Pentium Dual | 1         | 1.54%   |
| Intel Core 2       | 1         | 1.54%   |
| AMD E1             | 1         | 1.54%   |
| AMD E              | 1         | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 75.38%  |
| 4      | 14        | 21.54%  |
| 1      | 2         | 3.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 65        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 55.38%  |
| 2      | 29        | 44.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 30.77%  |
| 0x206a7    | 6         | 9.23%   |
| 0x306a9    | 5         | 7.69%   |
| 0x406c4    | 3         | 4.62%   |
| 0x406c3    | 3         | 4.62%   |
| 0x40651    | 3         | 4.62%   |
| 0x6fd      | 2         | 3.08%   |
| 0x20655    | 2         | 3.08%   |
| 0x1067a    | 2         | 3.08%   |
| 0x06006705 | 2         | 3.08%   |
| 0x906ed    | 1         | 1.54%   |
| 0x906c0    | 1         | 1.54%   |
| 0x806ec    | 1         | 1.54%   |
| 0x806ea    | 1         | 1.54%   |
| 0x806e9    | 1         | 1.54%   |
| 0x706a8    | 1         | 1.54%   |
| 0x706a1    | 1         | 1.54%   |
| 0x6fa      | 1         | 1.54%   |
| 0x6f6      | 1         | 1.54%   |
| 0x506e3    | 1         | 1.54%   |
| 0x506c9    | 1         | 1.54%   |
| 0x306c3    | 1         | 1.54%   |
| 0x30678    | 1         | 1.54%   |
| 0x106ca    | 1         | 1.54%   |
| 0x0700010f | 1         | 1.54%   |
| 0x06001116 | 1         | 1.54%   |
| 0x05000119 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 13        | 20%     |
| SandyBridge   | 8         | 12.31%  |
| IvyBridge     | 7         | 10.77%  |
| Haswell       | 6         | 9.23%   |
| Penryn        | 5         | 7.69%   |
| Core          | 5         | 7.69%   |
| KabyLake      | 4         | 6.15%   |
| Goldmont plus | 4         | 6.15%   |
| Westmere      | 2         | 3.08%   |
| Excavator     | 2         | 3.08%   |
| Broadwell     | 2         | 3.08%   |
| Tremont       | 1         | 1.54%   |
| Skylake       | 1         | 1.54%   |
| Piledriver    | 1         | 1.54%   |
| Jaguar        | 1         | 1.54%   |
| Goldmont      | 1         | 1.54%   |
| Bonnell       | 1         | 1.54%   |
| Bobcat        | 1         | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 77.46%  |
| AMD    | 11        | 15.49%  |
| Nvidia | 5         | 7.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 12.99%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 10.39%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 9.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 6.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 5.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 5.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 5.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 3.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.6%    |
| Intel HD Graphics 5500                                                                   | 2         | 2.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.6%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 2.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.6%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.6%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.3%    |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 1.3%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.3%    |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.3%    |
| Intel UHD Graphics 620                                                                   | 1         | 1.3%    |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.3%    |
| Intel HD Graphics 620                                                                    | 1         | 1.3%    |
| Intel HD Graphics 530                                                                    | 1         | 1.3%    |
| Intel HD Graphics 500                                                                    | 1         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.3%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.3%    |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.3%    |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.3%    |
| AMD RS600M [Radeon Xpress 1250]                                                          | 1         | 1.3%    |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 1.3%    |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 1.3%    |
| AMD Cape Verde PRO / Venus LE / Tropo PRO-L [Radeon HD 8830M / R7 250 / R7 M465X]        | 1         | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 72.31%  |
| 1 x AMD        | 5         | 7.69%   |
| Intel + AMD    | 4         | 6.15%   |
| 1 x Nvidia     | 3         | 4.62%   |
| Other          | 2         | 3.08%   |
| 2 x AMD        | 2         | 3.08%   |
| Intel + Nvidia | 2         | 3.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 98.46%  |
| Proprietary | 1         | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 86.15%  |
| 0.01-0.5   | 5         | 7.69%   |
| 1.01-2.0   | 3         | 4.62%   |
| 2.01-3.0   | 1         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 13        | 19.4%   |
| AU Optronics        | 13        | 19.4%   |
| Chimei Innolux      | 12        | 17.91%  |
| Samsung Electronics | 6         | 8.96%   |
| BOE                 | 6         | 8.96%   |
| Apple               | 4         | 5.97%   |
| Lenovo              | 2         | 2.99%   |
| CPT                 | 2         | 2.99%   |
| ViewSonic           | 1         | 1.49%   |
| Toshiba             | 1         | 1.49%   |
| Sharp               | 1         | 1.49%   |
| LG Philips          | 1         | 1.49%   |
| JVC                 | 1         | 1.49%   |
| JDI                 | 1         | 1.49%   |
| Goldstar            | 1         | 1.49%   |
| BenQ                | 1         | 1.49%   |
| Acer                | 1         | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 3         | 4.48%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 2.99%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 2.99%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 2.99%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 1.49%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 1.49%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.49%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 1.49%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 1.49%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.49%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.49%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch               | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 1.49%   |
| JVC FPDEUFY2 JVC221F 1920x1080                                        | 1         | 1.49%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 1.49%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 1         | 1.49%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 34        | 52.31%  |
| 1920x1080 (FHD)    | 10        | 15.38%  |
| 1280x800 (WXGA)    | 10        | 15.38%  |
| 1600x900 (HD+)     | 3         | 4.62%   |
| 3200x1800 (QHD+)   | 1         | 1.54%   |
| 3000x2000          | 1         | 1.54%   |
| 2560x1440 (QHD)    | 1         | 1.54%   |
| 2560x1080          | 1         | 1.54%   |
| 2160x1440          | 1         | 1.54%   |
| 1680x1050 (WSXGA+) | 1         | 1.54%   |
| 1528x1222          | 1         | 1.54%   |
| 1360x768           | 1         | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 21        | 31.34%  |
| 13      | 13        | 19.4%   |
| 14      | 11        | 16.42%  |
| 11      | 7         | 10.45%  |
| 17      | 4         | 5.97%   |
| 23      | 2         | 2.99%   |
| 28      | 1         | 1.49%   |
| 21      | 1         | 1.49%   |
| 19      | 1         | 1.49%   |
| 18      | 1         | 1.49%   |
| 16      | 1         | 1.49%   |
| 12      | 1         | 1.49%   |
| 10      | 1         | 1.49%   |
| 9       | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 55.22%  |
| 201-300     | 17        | 25.37%  |
| 351-400     | 5         | 7.46%   |
| 401-500     | 3         | 4.48%   |
| 501-600     | 2         | 2.99%   |
| 601-700     | 1         | 1.49%   |
| 101-200     | 1         | 1.49%   |
| Unknown     | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 74.6%   |
| 16/10 | 12        | 19.05%  |
| 3/2   | 2         | 3.17%   |
| 4/3   | 1         | 1.59%   |
| 21/9  | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 32.84%  |
| 101-110        | 21        | 31.34%  |
| 51-60          | 7         | 10.45%  |
| 121-130        | 4         | 5.97%   |
| 201-250        | 3         | 4.48%   |
| 71-80          | 2         | 2.99%   |
| 41-50          | 2         | 2.99%   |
| 61-70          | 1         | 1.49%   |
| 251-300        | 1         | 1.49%   |
| 151-200        | 1         | 1.49%   |
| 141-150        | 1         | 1.49%   |
| 131-140        | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 33        | 49.25%  |
| 121-160       | 16        | 23.88%  |
| 51-100        | 11        | 16.42%  |
| 161-240       | 4         | 5.97%   |
| More than 240 | 2         | 2.99%   |
| Unknown       | 1         | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 92.31%  |
| 2     | 4         | 6.15%   |
| 3     | 1         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 29        | 30.21%  |
| Intel                           | 27        | 28.13%  |
| Qualcomm Atheros                | 17        | 17.71%  |
| Broadcom                        | 8         | 8.33%   |
| Marvell Technology Group        | 3         | 3.13%   |
| Samsung Electronics             | 2         | 2.08%   |
| Broadcom Limited                | 2         | 2.08%   |
| TP-Link                         | 1         | 1.04%   |
| Sierra Wireless                 | 1         | 1.04%   |
| Ralink Technology               | 1         | 1.04%   |
| Qualcomm Atheros Communications | 1         | 1.04%   |
| Qualcomm                        | 1         | 1.04%   |
| Nvidia                          | 1         | 1.04%   |
| Microsoft                       | 1         | 1.04%   |
| ICS Advent                      | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 11.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 3.39%   |
| Intel Wireless 7260                                               | 4         | 3.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 2.54%   |
| Intel Wireless 7265                                               | 3         | 2.54%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 2.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.69%   |
| Intel Wireless 3160                                               | 2         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.69%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.69%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.85%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.85%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.85%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.85%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1         | 0.85%   |
| Qualcomm Mobile Router                                            | 1         | 0.85%   |
| Qualcomm Atheros UB94                                             | 1         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 42.86%  |
| Qualcomm Atheros                | 16        | 25.4%   |
| Realtek Semiconductor           | 11        | 17.46%  |
| Broadcom                        | 4         | 6.35%   |
| Sierra Wireless                 | 1         | 1.59%   |
| Ralink Technology               | 1         | 1.59%   |
| Qualcomm Atheros Communications | 1         | 1.59%   |
| Microsoft                       | 1         | 1.59%   |
| Broadcom Limited                | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.35%   |
| Intel Wireless 7260                                                     | 4         | 6.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 4.76%   |
| Intel Wireless 7265                                                     | 3         | 4.76%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.17%   |
| Intel Wireless 3160                                                     | 2         | 3.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 3.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 3.17%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.59%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.59%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.59%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.59%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.59%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 1.59%   |
| Qualcomm Atheros UB94                                                   | 1         | 1.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.59%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 1.59%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.59%   |
| Intel Wireless 8260                                                     | 1         | 1.59%   |
| Intel Wireless 3165                                                     | 1         | 1.59%   |
| Intel WiFi Link 5100                                                    | 1         | 1.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.59%   |
| Intel Centrino Wireless-N 105                                           | 1         | 1.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.59%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.59%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.59%   |
| Broadcom Limited BCM4311 802.11a/b/g                                    | 1         | 1.59%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 24        | 44.44%  |
| Intel                    | 10        | 18.52%  |
| Broadcom                 | 7         | 12.96%  |
| Qualcomm Atheros         | 3         | 5.56%   |
| Marvell Technology Group | 3         | 5.56%   |
| Samsung Electronics      | 2         | 3.7%    |
| TP-Link                  | 1         | 1.85%   |
| Qualcomm                 | 1         | 1.85%   |
| Nvidia                   | 1         | 1.85%   |
| ICS Advent               | 1         | 1.85%   |
| Broadcom Limited         | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 13        | 23.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 10.91%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 5.45%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 3.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 3.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 3.64%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 3.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 3.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 3.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.82%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.82%   |
| Qualcomm Mobile Router                                                         | 1         | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.82%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 1.82%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.82%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.82%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.82%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 1.82%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.82%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 1.82%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express                      | 1         | 1.82%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.82%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 54.63%  |
| Ethernet | 49        | 45.37%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 68.75%  |
| Ethernet | 20        | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 66.15%  |
| 1     | 15        | 23.08%  |
| 0     | 7         | 10.77%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 75.76%  |
| Yes  | 16        | 24.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 38.64%  |
| Realtek Semiconductor           | 7         | 15.91%  |
| Qualcomm Atheros Communications | 6         | 13.64%  |
| Dell                            | 3         | 6.82%   |
| Apple                           | 3         | 6.82%   |
| IMC Networks                    | 2         | 4.55%   |
| Foxconn / Hon Hai               | 2         | 4.55%   |
| Broadcom                        | 2         | 4.55%   |
| Syntek                          | 1         | 2.27%   |
| Alps Electric                   | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 12        | 27.27%  |
| Realtek Bluetooth Radio                                                             | 4         | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 6.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 6.82%   |
| Apple Bluetooth Host Controller                                                     | 3         | 6.82%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 4.55%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 2.27%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 2.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.27%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2.27%   |
| IMC Networks Bluetooth Device                                                       | 1         | 2.27%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 2.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.27%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 2.27%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 2.27%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 2.27%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 2.27%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 2.27%   |
| Alps Electric Bluetooth Adapter                                                     | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 83.08%  |
| AMD    | 7         | 10.77%  |
| Nvidia | 3         | 4.62%   |
| JMTek  | 1         | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 12.82%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 8.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 6.41%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 6.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 5.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 5.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.56%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.56%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.56%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.56%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.28%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.28%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.28%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.28%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.28%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.28%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 23.64%  |
| SK hynix            | 11        | 20%     |
| Unknown             | 9         | 16.36%  |
| Micron Technology   | 7         | 12.73%  |
| Elpida              | 3         | 5.45%   |
| Smart               | 2         | 3.64%   |
| Nanya Technology    | 2         | 3.64%   |
| Corsair             | 2         | 3.64%   |
| Unknown (ABCD)      | 1         | 1.82%   |
| Ramaxel Technology  | 1         | 1.82%   |
| Novatech            | 1         | 1.82%   |
| Kingston            | 1         | 1.82%   |
| HMD                 | 1         | 1.82%   |
| A-DATA Technology   | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 3.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 3.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 3.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.33%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 3.33%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.67%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.67%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.67%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.67%   |
| SK hynix RAM HT5SMRAP 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.67%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.67%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.67%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 1.67%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 1         | 1.67%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5674EB0-YK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 1.67%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.67%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 1.67%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.67%   |
| Novatech RAM N3S02H1600E-L R0 2GB SODIMM DDR3 1333MT/s           | 1         | 1.67%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.67%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s          | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 28        | 60.87%  |
| DDR4   | 8         | 17.39%  |
| DDR2   | 4         | 8.7%    |
| LPDDR4 | 3         | 6.52%   |
| LPDDR3 | 2         | 4.35%   |
| SDRAM  | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 86.96%  |
| Row Of Chips | 3         | 6.52%   |
| Unknown      | 3         | 6.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 21        | 38.18%  |
| 2048  | 20        | 36.36%  |
| 8192  | 6         | 10.91%  |
| 1024  | 4         | 7.27%   |
| 16384 | 2         | 3.64%   |
| 32768 | 1         | 1.82%   |
| 512   | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 34%     |
| 1333    | 6         | 12%     |
| 2667    | 4         | 8%      |
| 1334    | 3         | 6%      |
| 667     | 3         | 6%      |
| 3200    | 2         | 4%      |
| 2400    | 2         | 4%      |
| 1866    | 2         | 4%      |
| 1067    | 2         | 4%      |
| 1066    | 2         | 4%      |
| Unknown | 2         | 4%      |
| 4199    | 1         | 2%      |
| 3266    | 1         | 2%      |
| 2133    | 1         | 2%      |
| 1867    | 1         | 2%      |
| 975     | 1         | 2%      |

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
| Chicony Electronics                    | 14        | 25.93%  |
| Microdia                               | 8         | 14.81%  |
| Realtek Semiconductor                  | 5         | 9.26%   |
| Sunplus Innovation Technology          | 4         | 7.41%   |
| Syntek                                 | 3         | 5.56%   |
| IMC Networks                           | 3         | 5.56%   |
| Apple                                  | 3         | 5.56%   |
| Alcor Micro                            | 3         | 5.56%   |
| Quanta                                 | 2         | 3.7%    |
| Lenovo                                 | 2         | 3.7%    |
| Suyin                                  | 1         | 1.85%   |
| Silicon Motion                         | 1         | 1.85%   |
| Ricoh                                  | 1         | 1.85%   |
| Cubeternet                             | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.85%   |
| ALi                                    | 1         | 1.85%   |
| Acer                                   | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 9.09%   |
| Sunplus HD WebCam                                   | 2         | 3.64%   |
| Microdia Integrated Webcam                          | 2         | 3.64%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 3.64%   |
| Chicony HD WebCam                                   | 2         | 3.64%   |
| Chicony EasyCamera                                  | 2         | 3.64%   |
| Apple FaceTime HD Camera                            | 2         | 3.64%   |
| Alcor Micro HD Webcam                               | 2         | 3.64%   |
| Syntek USB2.0 Camera                                | 1         | 1.82%   |
| Syntek USB Camera Device                            | 1         | 1.82%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.82%   |
| Suyin 1.3M HD WebCam                                | 1         | 1.82%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.82%   |
| Sunplus Asus Webcam                                 | 1         | 1.82%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.82%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.82%   |
| Realtek USB Camera                                  | 1         | 1.82%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.82%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.82%   |
| Realtek Integrated Webcam HD                        | 1         | 1.82%   |
| Realtek EasyCamera                                  | 1         | 1.82%   |
| Quanta HP Webcam                                    | 1         | 1.82%   |
| Quanta Chromebook HD Camera                         | 1         | 1.82%   |
| Microdia Webcam Vitade AF                           | 1         | 1.82%   |
| Microdia Webcam                                     | 1         | 1.82%   |
| Microdia Lenovo EasyCamera                          | 1         | 1.82%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.82%   |
| Microdia HP Webcam-50                               | 1         | 1.82%   |
| Microdia 1.3 MPixel Integrated Webcam               | 1         | 1.82%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.82%   |
| Lenovo Integrated Webcam                            | 1         | 1.82%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.82%   |
| Cubeternet GL-UPC822 UVC WebCam                     | 1         | 1.82%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.82%   |
| Chicony HP Webcam                                   | 1         | 1.82%   |
| Chicony HP Truevision HD camera                     | 1         | 1.82%   |
| Chicony HP Truevision HD                            | 1         | 1.82%   |
| Chicony 720p HD Camera                              | 1         | 1.82%   |
| Chicony 5MP World Facing                            | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 5         | 45.45%  |
| Upek               | 3         | 27.27%  |
| STMicroelectronics | 2         | 18.18%  |
| AuthenTec          | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 27.27%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |

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


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Broadcom 5880                        | 2         | 66.67%  |
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 50        | 76.92%  |
| 1     | 15        | 23.08%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 11        | 73.33%  |
| Chipcard           | 3         | 20%     |
| Bluetooth          | 1         | 6.67%   |

