Parrot 5.0 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

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

Total: 87

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | Pavilion dv6                | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP        | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Toshiba   | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [39351344b4](https://linux-hardware.org/?probe=39351344b4) | Jun 14, 2022 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo    | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo    | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Dell      | Inspiron 15-3567            | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HUAWEI    | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo    | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell      | Latitude E6540              | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell      | Latitude E6540              | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo    | Legion 5 15ACH6 82JW        | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo    | Legion 5 15ACH6 82JW        | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell      | Latitude 5400               | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo    | IdeaPad 320S-14IKB 80X4     | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Dell      | Latitude E6410              | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI       | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Lenovo    | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| ASUSTek   | ROG Strix G733ZX_G733ZX     | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI    | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP        | EliteBook 8470p             | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Lenovo    | IdeaPad L340-17API 81LY     | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| MSI       | Modern 15 A5M               | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple     | MacBookPro15,1              | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI       | Modern 15 A5M               | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer     | Blade 15 Base Model (Ear... | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| ASUSTek   | X540SAA                     | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo    | IdeaPad L340-17API 81LY     | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Toshiba   | Satellite Click 2 L35W-B    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI       | Modern 15 A5M               | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI       | Modern 15 A5M               | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI       | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP        | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek   | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| MSI       | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| ASUSTek   | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper    | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple     | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox   | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple     | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell      | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell      | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Jumper    | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple     | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper    | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi     | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung   | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba   | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer      | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi     | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer      | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| HP        | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP        | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell      | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo    | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| Acer      | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell      | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP        | Pavilion Laptop 14-ec0xx... | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP        | Pavilion Laptop 14-ec0xx... | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell      | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo    | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Lenovo    | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo    | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| MSI       | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP        | ZBook Firefly 14 G7 Mobi... | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Dell      | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| Acer      | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP        | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo    | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo    | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell      | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell      | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| HP        | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| HP        | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP        | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP        | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| HP        | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.16.0-12parrot1-amd64 | 27        | 42.19%  |
| 5.14.0-9parrot1-amd64  | 27        | 42.19%  |
| 5.14.0-2parrot1-amd64  | 6         | 9.38%   |
| 5.15.0-15parrot1-amd64 | 3         | 4.69%   |
| 5.15.0-5parrot1-amd64  | 1         | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 32        | 50.79%  |
| 5.16.0  | 27        | 42.86%  |
| 5.15.0  | 4         | 6.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 32        | 50.79%  |
| 5.16    | 27        | 42.86%  |
| 5.15    | 4         | 6.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 40        | 63.49%  |
| KDE5    | 21        | 33.33%  |
| KDE     | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 62        | 98.41%  |
| Wayland | 1         | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 35        | 55.56%  |
| Unknown | 27        | 42.86%  |
| SDDM    | 1         | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 33        | 52.38%  |
| en_GB | 7         | 11.11%  |
| es_ES | 5         | 7.94%   |
| en_IN | 3         | 4.76%   |
| ru_RU | 2         | 3.17%   |
| fr_FR | 2         | 3.17%   |
| en_AU | 2         | 3.17%   |
| de_DE | 2         | 3.17%   |
| pt_PT | 1         | 1.59%   |
| pt_BR | 1         | 1.59%   |
| es_PE | 1         | 1.59%   |
| es_MX | 1         | 1.59%   |
| es_AR | 1         | 1.59%   |
| en_ZA | 1         | 1.59%   |
| cs_CZ | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 38        | 60.32%  |
| EFI  | 25        | 39.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 53        | 84.13%  |
| Ext4    | 7         | 11.11%  |
| Overlay | 3         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 47.62%  |
| GPT     | 24        | 38.1%   |
| MBR     | 9         | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 88.89%  |
| Yes       | 7         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 68.25%  |
| Yes       | 20        | 31.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 22.22%  |
| Hewlett-Packard     | 11        | 17.46%  |
| Dell                | 11        | 17.46%  |
| MSI                 | 5         | 7.94%   |
| ASUSTek Computer    | 4         | 6.35%   |
| Acer                | 4         | 6.35%   |
| Toshiba             | 3         | 4.76%   |
| Apple               | 3         | 4.76%   |
| HUAWEI              | 2         | 3.17%   |
| Samsung Electronics | 1         | 1.59%   |
| Razer               | 1         | 1.59%   |
| Metabox             | 1         | 1.59%   |
| Jumper              | 1         | 1.59%   |
| Chuwi               | 1         | 1.59%   |
| Alienware           | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 4.76%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 2         | 3.17%   |
| HP Notebook                                        | 2         | 3.17%   |
| Dell Latitude E6410                                | 2         | 3.17%   |
| Toshiba Satellite-L845                             | 1         | 1.59%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 1.59%   |
| Toshiba Satellite C75D-B                           | 1         | 1.59%   |
| Samsung 550P5C/550P7C                              | 1         | 1.59%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 1.59%   |
| MSI GE62 6QE                                       | 1         | 1.59%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 1.59%   |
| Metabox Edge-Pro NS50MU                            | 1         | 1.59%   |
| Lenovo V330-15IKB 81AX                             | 1         | 1.59%   |
| Lenovo ThinkPad X230 2325N66                       | 1         | 1.59%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 1.59%   |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 1.59%   |
| Lenovo ThinkPad T470p 20J7S0CF00                   | 1         | 1.59%   |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 1.59%   |
| Lenovo Legion 5 15ACH6 82JW                        | 1         | 1.59%   |
| Lenovo IdeaPad Y580                                | 1         | 1.59%   |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 1.59%   |
| Lenovo IdeaPad 320S-14IKB 80X4                     | 1         | 1.59%   |
| Lenovo B50-80 80EW                                 | 1         | 1.59%   |
| Jumper EZbook                                      | 1         | 1.59%   |
| HUAWEI HVY-WXX9                                    | 1         | 1.59%   |
| HUAWEI BOHK-WAX9X                                  | 1         | 1.59%   |
| HP ZBook Firefly 14 G7 Mobile Workstation          | 1         | 1.59%   |
| HP ProBook 4535s                                   | 1         | 1.59%   |
| HP ProBook 440 G5                                  | 1         | 1.59%   |
| HP Pavilion Laptop 14-ec0xxx                       | 1         | 1.59%   |
| HP Pavilion g7                                     | 1         | 1.59%   |
| HP Pavilion dv6                                    | 1         | 1.59%   |
| HP Laptop 15q-dy0xxx                               | 1         | 1.59%   |
| HP EliteBook 8470p                                 | 1         | 1.59%   |
| HP EliteBook 840 G3                                | 1         | 1.59%   |
| Dell Latitude XT2                                  | 1         | 1.59%   |
| Dell Latitude E7450                                | 1         | 1.59%   |
| Dell Latitude E6540                                | 1         | 1.59%   |
| Dell Latitude 7480                                 | 1         | 1.59%   |
| Dell Latitude 5400                                 | 1         | 1.59%   |
| Dell Inspiron N5110                                | 1         | 1.59%   |
| Dell Inspiron 5580                                 | 1         | 1.59%   |
| Dell Inspiron 5570                                 | 1         | 1.59%   |
| Dell Inspiron 15-3567                              | 1         | 1.59%   |
| Chuwi GemiBook                                     | 1         | 1.59%   |
| ASUS X75VC                                         | 1         | 1.59%   |
| ASUS X540SAA                                       | 1         | 1.59%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR               | 1         | 1.59%   |
| ASUS ROG Strix G733ZX_G733ZX                       | 1         | 1.59%   |
| Apple MacBookPro15,1                               | 1         | 1.59%   |
| Apple MacBookAir3,1                                | 1         | 1.59%   |
| Apple MacBook7,1                                   | 1         | 1.59%   |
| Alienware M14xR1                                   | 1         | 1.59%   |
| Acer TravelMate 5720                               | 1         | 1.59%   |
| Acer Nitro AN517-41                                | 1         | 1.59%   |
| Acer Nitro AN515-54                                | 1         | 1.59%   |
| Acer Aspire A315-21                                | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 7         | 11.11%  |
| Lenovo ThinkPad        | 6         | 9.52%   |
| Lenovo IdeaPad         | 5         | 7.94%   |
| Dell Inspiron          | 4         | 6.35%   |
| MSI Modern             | 3         | 4.76%   |
| HP Pavilion            | 3         | 4.76%   |
| Toshiba Satellite      | 2         | 3.17%   |
| HP ProBook             | 2         | 3.17%   |
| HP Notebook            | 2         | 3.17%   |
| HP EliteBook           | 2         | 3.17%   |
| Acer Nitro             | 2         | 3.17%   |
| Toshiba Satellite-L845 | 1         | 1.59%   |
| Samsung 550P5C         | 1         | 1.59%   |
| Razer Blade            | 1         | 1.59%   |
| MSI GE62               | 1         | 1.59%   |
| MSI Creator            | 1         | 1.59%   |
| Metabox Edge-Pro       | 1         | 1.59%   |
| Lenovo V330-15IKB      | 1         | 1.59%   |
| Lenovo Legion          | 1         | 1.59%   |
| Lenovo B50-80          | 1         | 1.59%   |
| Jumper EZbook          | 1         | 1.59%   |
| HUAWEI HVY-WXX9        | 1         | 1.59%   |
| HUAWEI BOHK-WAX9X      | 1         | 1.59%   |
| HP ZBook               | 1         | 1.59%   |
| HP Laptop              | 1         | 1.59%   |
| Chuwi GemiBook         | 1         | 1.59%   |
| ASUS X75VC             | 1         | 1.59%   |
| ASUS X540SAA           | 1         | 1.59%   |
| ASUS VivoBook          | 1         | 1.59%   |
| ASUS ROG               | 1         | 1.59%   |
| Apple MacBookPro15     | 1         | 1.59%   |
| Apple MacBookAir3      | 1         | 1.59%   |
| Apple MacBook7         | 1         | 1.59%   |
| Alienware M14xR1       | 1         | 1.59%   |
| Acer TravelMate        | 1         | 1.59%   |
| Acer Aspire            | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 9         | 14.29%  |
| 2017 | 8         | 12.7%   |
| 2020 | 7         | 11.11%  |
| 2019 | 6         | 9.52%   |
| 2016 | 5         | 7.94%   |
| 2012 | 5         | 7.94%   |
| 2011 | 5         | 7.94%   |
| 2018 | 4         | 6.35%   |
| 2010 | 4         | 6.35%   |
| 2014 | 3         | 4.76%   |
| 2013 | 2         | 3.17%   |
| 2022 | 1         | 1.59%   |
| 2015 | 1         | 1.59%   |
| 2009 | 1         | 1.59%   |
| 2008 | 1         | 1.59%   |
| 2007 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 63        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 18        | 28.57%  |
| 32.01-64.0  | 10        | 15.87%  |
| 3.01-4.0    | 10        | 15.87%  |
| 16.01-24.0  | 10        | 15.87%  |
| 8.01-16.0   | 9         | 14.29%  |
| 64.01-256.0 | 3         | 4.76%   |
| 24.01-32.0  | 2         | 3.17%   |
| 1.01-2.0    | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 24        | 38.1%   |
| 1.01-2.0  | 18        | 28.57%  |
| 4.01-8.0  | 13        | 20.63%  |
| 3.01-4.0  | 5         | 7.94%   |
| 8.01-16.0 | 2         | 3.17%   |
| 0.51-1.0  | 1         | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 63.49%  |
| 2      | 21        | 33.33%  |
| 3      | 1         | 1.59%   |
| 0      | 1         | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 71.43%  |
| Yes       | 18        | 28.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 77.78%  |
| No        | 14        | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 98.41%  |
| No        | 1         | 1.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 85.71%  |
| No        | 9         | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 22        | 34.38%  |
| Spain        | 5         | 7.81%   |
| UK           | 4         | 6.25%   |
| Germany      | 4         | 6.25%   |
| India        | 3         | 4.69%   |
| South Africa | 2         | 3.13%   |
| Mexico       | 2         | 3.13%   |
| France       | 2         | 3.13%   |
| Denmark      | 2         | 3.13%   |
| Brazil       | 2         | 3.13%   |
| Australia    | 2         | 3.13%   |
| Russia       | 1         | 1.56%   |
| Portugal     | 1         | 1.56%   |
| Peru         | 1         | 1.56%   |
| Netherlands  | 1         | 1.56%   |
| Morocco      | 1         | 1.56%   |
| Kenya        | 1         | 1.56%   |
| Italy        | 1         | 1.56%   |
| Georgia      | 1         | 1.56%   |
| Czechia      | 1         | 1.56%   |
| Canada       | 1         | 1.56%   |
| Bulgaria     | 1         | 1.56%   |
| Austria      | 1         | 1.56%   |
| Argentina    | 1         | 1.56%   |
| Algeria      | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Seattle                | 3         | 4.69%   |
| Ruskin                 | 2         | 3.13%   |
| Camden                 | 2         | 3.13%   |
| Villa Carlos Paz       | 1         | 1.56%   |
| Vienna                 | 1         | 1.56%   |
| Ts'khinvali            | 1         | 1.56%   |
| Trivandrum             | 1         | 1.56%   |
| Tangier                | 1         | 1.56%   |
| Sydney                 | 1         | 1.56%   |
| Sumaré                | 1         | 1.56%   |
| St Petersburg          | 1         | 1.56%   |
| Spotsylvania           | 1         | 1.56%   |
| South Hamilton         | 1         | 1.56%   |
| Skive                  | 1         | 1.56%   |
| Saint Paul             | 1         | 1.56%   |
| Pretoria               | 1         | 1.56%   |
| Prague                 | 1         | 1.56%   |
| Plovdiv                | 1         | 1.56%   |
| Phoenix                | 1         | 1.56%   |
| Orofino                | 1         | 1.56%   |
| Opelousas              | 1         | 1.56%   |
| Nairobi                | 1         | 1.56%   |
| Mt. Pleasant           | 1         | 1.56%   |
| Mostoles               | 1         | 1.56%   |
| Montigny-le-Bretonneux | 1         | 1.56%   |
| Melbourne              | 1         | 1.56%   |
| Mazatlán              | 1         | 1.56%   |
| Mata de Sao Joao       | 1         | 1.56%   |
| Mangalagiri            | 1         | 1.56%   |
| Madrid                 | 1         | 1.56%   |
| Lynwood                | 1         | 1.56%   |
| Los Angeles            | 1         | 1.56%   |
| Lisbon                 | 1         | 1.56%   |
| Leduc                  | 1         | 1.56%   |
| La Magdalena           | 1         | 1.56%   |
| Islington              | 1         | 1.56%   |
| Houston                | 1         | 1.56%   |
| Herne                  | 1         | 1.56%   |
| Haßfurt               | 1         | 1.56%   |
| Eugene                 | 1         | 1.56%   |
| Esplugues de Llobregat | 1         | 1.56%   |
| East China Township    | 1         | 1.56%   |
| Durban                 | 1         | 1.56%   |
| Dresden                | 1         | 1.56%   |
| Dillon                 | 1         | 1.56%   |
| Dickson                | 1         | 1.56%   |
| Copenhagen             | 1         | 1.56%   |
| City of Saint Peters   | 1         | 1.56%   |
| Cannes                 | 1         | 1.56%   |
| Bristol                | 1         | 1.56%   |
| Birmingham             | 1         | 1.56%   |
| Berlin                 | 1         | 1.56%   |
| Bengaluru              | 1         | 1.56%   |
| Beachwood              | 1         | 1.56%   |
| Asti                   | 1         | 1.56%   |
| Arequipa               | 1         | 1.56%   |
| Amsterdam              | 1         | 1.56%   |
| Algiers                | 1         | 1.56%   |
| Alcorcón              | 1         | 1.56%   |
| Alcalá de Henares     | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 14     | 16.25%  |
| Toshiba             | 10        | 10     | 12.5%   |
| WDC                 | 7         | 8      | 8.75%   |
| Kingston            | 7         | 7      | 8.75%   |
| Seagate             | 5         | 5      | 6.25%   |
| Unknown             | 4         | 5      | 5%      |
| SanDisk             | 4         | 5      | 5%      |
| Hitachi             | 3         | 4      | 3.75%   |
| SK hynix            | 2         | 2      | 2.5%    |
| Micron Technology   | 2         | 2      | 2.5%    |
| HGST                | 2         | 2      | 2.5%    |
| Crucial             | 2         | 2      | 2.5%    |
| China               | 2         | 2      | 2.5%    |
| Apple               | 2         | 2      | 2.5%    |
| YMTC                | 1         | 1      | 1.25%   |
| Team                | 1         | 1      | 1.25%   |
| S3+                 | 1         | 1      | 1.25%   |
| PNY                 | 1         | 1      | 1.25%   |
| Phison              | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| LITEON              | 1         | 1      | 1.25%   |
| KingSpec            | 1         | 1      | 1.25%   |
| KingFast            | 1         | 2      | 1.25%   |
| Intenso             | 1         | 2      | 1.25%   |
| Intel               | 1         | 1      | 1.25%   |
| HUAWEI              | 1         | 1      | 1.25%   |
| BHT                 | 1         | 1      | 1.25%   |
| ASMedia             | 1         | 1      | 1.25%   |
| A-DATA Technology   | 1         | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                       | 5         | 5.88%   |
| Kingston NVMe SSD Drive 512GB                | 3         | 3.53%   |
| Unknown MMC Card  32GB                       | 2         | 2.35%   |
| Toshiba MQ01ABD075 752GB                     | 2         | 2.35%   |
| SanDisk NVMe SSD Drive 1TB                   | 2         | 2.35%   |
| Kingston SV300S37A120G 120GB SSD             | 2         | 2.35%   |
| YMTC PC005 512GB                             | 1         | 1.18%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.18%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1.18%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1         | 1.18%   |
| WDC WDBNCE2500PNC 250GB SSD                  | 1         | 1.18%   |
| WDC WD6400BPVT-75HXZT1 640GB                 | 1         | 1.18%   |
| WDC WD3200BPVT-00JJ5T0 320GB                 | 1         | 1.18%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 1.18%   |
| WDC WD10SPZX-24Z10 1TB                       | 1         | 1.18%   |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 1.18%   |
| Unknown SD  128GB                            | 1         | 1.18%   |
| Unknown ISOCOM  64GB                         | 1         | 1.18%   |
| Toshiba MQ01ACF050 500GB                     | 1         | 1.18%   |
| Toshiba MK2555GSXF 250GB                     | 1         | 1.18%   |
| Toshiba MK2533GSGF 250GB                     | 1         | 1.18%   |
| Team TM8PS7512G 512GB SSD                    | 1         | 1.18%   |
| SK hynix NVMe SSD Drive 1024GB               | 1         | 1.18%   |
| SK hynix HFS128G32TNF-N3A0A 128GB SSD        | 1         | 1.18%   |
| Seagate ST9250315AS 250GB                    | 1         | 1.18%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1.18%   |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 1         | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1.18%   |
| Seagate BUP Slim BK 1TB                      | 1         | 1.18%   |
| SanDisk SDSSDH3 2T00 2TB                     | 1         | 1.18%   |
| SanDisk NVMe SSD Drive 256GB                 | 1         | 1.18%   |
| SanDisk NVMe SSD Drive 1024GB                | 1         | 1.18%   |
| Samsung SSD 980 1TB                          | 1         | 1.18%   |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 1.18%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 1.18%   |
| Samsung NVMe SSD Drive 1024GB                | 1         | 1.18%   |
| Samsung MZVLB512HBJQ-000H1 512GB             | 1         | 1.18%   |
| Samsung MZVLB512HAJQ-000L7 512GB             | 1         | 1.18%   |
| Samsung MZVLB512HAJQ-00000 512GB             | 1         | 1.18%   |
| Samsung MZVLB256HAHQ-00000 256GB             | 1         | 1.18%   |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 1.18%   |
| Samsung MZVL22T0HBLB-00B00 2TB               | 1         | 1.18%   |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 1.18%   |
| Samsung MZMPC032HBCD-000L1 32GB SSD          | 1         | 1.18%   |
| Samsung MZALQ128HBHQ-000L2 128GB             | 1         | 1.18%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD         | 1         | 1.18%   |
| S3+ S3SSDC480 480GB                          | 1         | 1.18%   |
| PNY CS900 240GB SSD                          | 1         | 1.18%   |
| Phison Metabox Performance 2TB PCIe NVME SSD | 1         | 1.18%   |
| Netac S535N8/256 256GB                       | 1         | 1.18%   |
| Micron MTFDHBA512QFD-1AX1AABHA 512GB         | 1         | 1.18%   |
| Micron 3400_MTFDKBA1T0TFH 1TB                | 1         | 1.18%   |
| LITEON CV3-8D512-11 SATA 512GB SSD           | 1         | 1.18%   |
| Kingston SKC600512G 512GB SSD                | 1         | 1.18%   |
| Kingston SA2000M81000G 1TB                   | 1         | 1.18%   |
| KingSpec NT-1TB SSD                          | 1         | 1.18%   |
| KingFast SSD 512GB                           | 1         | 1.18%   |
| KingFast 512GB                               | 1         | 1.18%   |
| Intenso SSD SATAIII 480GB                    | 1         | 1.18%   |
| Intel SSDPEKKF256G7L 256GB                   | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 10        | 10     | 38.46%  |
| Seagate | 5         | 5      | 19.23%  |
| WDC     | 4         | 4      | 15.38%  |
| Hitachi | 3         | 4      | 11.54%  |
| HGST    | 2         | 2      | 7.69%   |
| Unknown | 1         | 1      | 3.85%   |
| ASMedia | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 15.38%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| Kingston            | 3         | 3      | 11.54%  |
| Crucial             | 2         | 2      | 7.69%   |
| China               | 2         | 2      | 7.69%   |
| Team                | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| SanDisk             | 1         | 1      | 3.85%   |
| S3+                 | 1         | 1      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| Netac               | 1         | 1      | 3.85%   |
| LITEON              | 1         | 1      | 3.85%   |
| KingSpec            | 1         | 1      | 3.85%   |
| KingFast            | 1         | 1      | 3.85%   |
| Intenso             | 1         | 2      | 3.85%   |
| BHT                 | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 25        | 27     | 32.89%  |
| HDD     | 24        | 27     | 31.58%  |
| NVMe    | 22        | 27     | 28.95%  |
| MMC     | 3         | 4      | 3.95%   |
| Unknown | 2         | 2      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 52     | 59.72%  |
| NVMe | 22        | 27     | 30.56%  |
| SAS  | 4         | 4      | 5.56%   |
| MMC  | 3         | 4      | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 32     | 56%     |
| 0.51-1.0   | 19        | 19     | 38%     |
| 1.01-2.0   | 3         | 3      | 6%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 30.16%  |
| 501-1000   | 12        | 19.05%  |
| 1001-2000  | 10        | 15.87%  |
| Unknown    | 9         | 14.29%  |
| 251-500    | 7         | 11.11%  |
| 2001-3000  | 2         | 3.17%   |
| 1-20       | 2         | 3.17%   |
| 21-50      | 1         | 1.59%   |
| 51-100     | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 21        | 33.33%  |
| 51-100   | 11        | 17.46%  |
| 1-20     | 9         | 14.29%  |
| Unknown  | 9         | 14.29%  |
| 251-500  | 6         | 9.52%   |
| 101-250  | 4         | 6.35%   |
| 501-1000 | 3         | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB   | 1         | 1      | 50%     |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 33        | 45     | 48.53%  |
| Works    | 33        | 40     | 48.53%  |
| Malfunc  | 2         | 2      | 2.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 41        | 54.67%  |
| Samsung Electronics         | 10        | 13.33%  |
| AMD                         | 8         | 10.67%  |
| Kingston Technology Company | 4         | 5.33%   |
| SanDisk                     | 3         | 4%      |
| Nvidia                      | 2         | 2.67%   |
| Micron Technology           | 2         | 2.67%   |
| Yangtze Memory Technologies | 1         | 1.33%   |
| SK hynix                    | 1         | 1.33%   |
| Phison Electronics          | 1         | 1.33%   |
| Apple                       | 1         | 1.33%   |
| ADATA Technology            | 1         | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 9.52%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 8.33%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 5         | 5.95%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 5         | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 4.76%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 3.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.38%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.38%   |
| Micron Non-Volatile memory controller                                            | 2         | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.38%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 2.38%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 1.19%   |
| SK hynix Gold P31 SSD                                                            | 1         | 1.19%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 1.19%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.19%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.19%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.19%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 1.19%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 1.19%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.19%   |
| Intel SSD 600P Series                                                            | 1         | 1.19%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.19%   |
| Intel Comet Lake PCH-H RAID                                                      | 1         | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.19%   |
| Apple ANS2 NVMe Controller                                                       | 1         | 1.19%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 34        | 45.95%  |
| NVMe | 22        | 29.73%  |
| RAID | 10        | 13.51%  |
| IDE  | 8         | 10.81%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 77.78%  |
| AMD    | 14        | 22.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 4.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.17%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 3.17%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 3.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 3.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 3.17%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.59%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.59%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.59%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 1.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.59%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.59%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.59%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.59%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.59%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.59%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.59%   |
| Intel 12th Gen Core i9-12900H                 | 1         | 1.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.59%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 1.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.59%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics   | 1         | 1.59%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 1.59%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 1.59%   |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 1.59%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 17        | 26.98%  |
| Intel Core i5    | 15        | 23.81%  |
| AMD Ryzen 7      | 6         | 9.52%   |
| Intel Core i3    | 5         | 7.94%   |
| Other            | 4         | 6.35%   |
| Intel Core 2 Duo | 4         | 6.35%   |
| Intel Celeron    | 3         | 4.76%   |
| AMD Ryzen 5      | 3         | 4.76%   |
| Intel Pentium    | 2         | 3.17%   |
| AMD A6           | 2         | 3.17%   |
| AMD E2           | 1         | 1.59%   |
| AMD A4           | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 46.03%  |
| 4      | 22        | 34.92%  |
| 8      | 6         | 9.52%   |
| 6      | 5         | 7.94%   |
| 14     | 1         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 77.78%  |
| 1      | 14        | 22.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 46.03%  |
| 0x806e9    | 5         | 7.94%   |
| 0x306a9    | 3         | 4.76%   |
| 0xa0652    | 2         | 3.17%   |
| 0x706e5    | 2         | 3.17%   |
| 0x406e3    | 2         | 3.17%   |
| 0x206a7    | 2         | 3.17%   |
| 0x1067a    | 2         | 3.17%   |
| 0x07030105 | 2         | 3.17%   |
| 0x906ed    | 1         | 1.59%   |
| 0x906ea    | 1         | 1.59%   |
| 0x906e9    | 1         | 1.59%   |
| 0x906a3    | 1         | 1.59%   |
| 0x806ec    | 1         | 1.59%   |
| 0x806eb    | 1         | 1.59%   |
| 0x806ea    | 1         | 1.59%   |
| 0x806d1    | 1         | 1.59%   |
| 0x706a8    | 1         | 1.59%   |
| 0x506c9    | 1         | 1.59%   |
| 0x306c3    | 1         | 1.59%   |
| 0x08600106 | 1         | 1.59%   |
| 0x08108109 | 1         | 1.59%   |
| 0x03000027 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 16        | 25.4%   |
| IvyBridge        | 6         | 9.52%   |
| SandyBridge      | 4         | 6.35%   |
| Penryn           | 4         | 6.35%   |
| Unknown          | 4         | 6.35%   |
| Skylake          | 3         | 4.76%   |
| Icelake          | 3         | 4.76%   |
| Zen+             | 2         | 3.17%   |
| Zen 3            | 2         | 3.17%   |
| Westmere         | 2         | 3.17%   |
| Silvermont       | 2         | 3.17%   |
| Puma             | 2         | 3.17%   |
| Excavator        | 2         | 3.17%   |
| CometLake        | 2         | 3.17%   |
| Broadwell        | 2         | 3.17%   |
| Zen 2            | 1         | 1.59%   |
| TigerLake        | 1         | 1.59%   |
| K10 Llano        | 1         | 1.59%   |
| Haswell          | 1         | 1.59%   |
| Goldmont plus    | 1         | 1.59%   |
| Goldmont         | 1         | 1.59%   |
| Alderlake Hybrid | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 53.57%  |
| AMD    | 21        | 25%     |
| Nvidia | 18        | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.81%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.65%   |
| Intel HD Graphics 620                                                                    | 4         | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.65%   |
| AMD Lucienne                                                                             | 4         | 4.65%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.33%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 2.33%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.33%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.33%   |
| AMD Cezanne                                                                              | 2         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.16%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.16%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 1.16%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 1.16%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.16%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.16%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.16%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.16%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 1.16%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                              | 1         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 1         | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.16%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 1.16%   |
| Intel HD Graphics 630                                                                    | 1         | 1.16%   |
| Intel HD Graphics 530                                                                    | 1         | 1.16%   |
| Intel HD Graphics 500                                                                    | 1         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.16%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.16%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.16%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.16%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.16%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.16%   |
| AMD Renoir                                                                               | 1         | 1.16%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.16%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.16%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.16%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 41.27%  |
| Intel + Nvidia | 14        | 22.22%  |
| 1 x AMD        | 13        | 20.63%  |
| Intel + AMD    | 5         | 7.94%   |
| 1 x Nvidia     | 2         | 3.17%   |
| AMD + Nvidia   | 2         | 3.17%   |
| 2 x AMD        | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 58        | 92.06%  |
| Proprietary | 4         | 6.35%   |
| Unknown     | 1         | 1.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 77.78%  |
| 1.01-2.0   | 5         | 7.94%   |
| 0.01-0.5   | 4         | 6.35%   |
| 3.01-4.0   | 3         | 4.76%   |
| 0.51-1.0   | 2         | 3.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 27.54%  |
| BOE                     | 14        | 20.29%  |
| LG Display              | 9         | 13.04%  |
| Chimei Innolux          | 8         | 11.59%  |
| Samsung Electronics     | 5         | 7.25%   |
| Chi Mei Optoelectronics | 3         | 4.35%   |
| Apple                   | 3         | 4.35%   |
| Lenovo                  | 2         | 2.9%    |
| Unknown (AAA)           | 1         | 1.45%   |
| PANDA                   | 1         | 1.45%   |
| ONN                     | 1         | 1.45%   |
| Kogan                   | 1         | 1.45%   |
| Goldstar                | 1         | 1.45%   |
| CSO                     | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 4.35%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                 | 1         | 1.45%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch      | 1         | 1.45%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch     | 1         | 1.45%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                  | 1         | 1.45%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                     | 1         | 1.45%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 1         | 1.45%   |
| Lenovo LCD Monitor LEN1144 1920x1200 520x320mm 24.0-inch                 | 1         | 1.45%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                      | 1         | 1.45%   |
| Kogan KAMN27F7TA KGN0270 1920x1080 600x330mm 27.0-inch                   | 1         | 1.45%   |
| Goldstar TV GSM0002 1920x1080 1150x650mm 52.0-inch                       | 1         | 1.45%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.45%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 1         | 1.45%   |
| BOE LCD Monitor BOE0A1C 1920x1080 344x194mm 15.5-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE07E8 1366x768 309x173mm 13.9-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 1         | 1.45%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                     | 1         | 1.45%   |
| AU Optronics LCD Monitor AUODB95 2560x1600 344x215mm 16.0-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUOA114 1280x800 261x163mm 12.1-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO5544 1280x800 303x189mm 14.1-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 26        | 40.63%  |
| 1366x768 (WXGA)  | 23        | 35.94%  |
| 1600x900 (HD+)   | 6         | 9.38%   |
| 1280x800 (WXGA)  | 4         | 6.25%   |
| 3840x2160 (4K)   | 1         | 1.56%   |
| 2880x1800        | 1         | 1.56%   |
| 2560x1600        | 1         | 1.56%   |
| 2160x1440        | 1         | 1.56%   |
| 1440x900 (WXGA+) | 1         | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 28        | 41.18%  |
| 14     | 12        | 17.65%  |
| 13     | 8         | 11.76%  |
| 17     | 6         | 8.82%   |
| 12     | 3         | 4.41%   |
| 27     | 2         | 2.94%   |
| 24     | 2         | 2.94%   |
| 16     | 2         | 2.94%   |
| 52     | 1         | 1.47%   |
| 40     | 1         | 1.47%   |
| 31     | 1         | 1.47%   |
| 21     | 1         | 1.47%   |
| 11     | 1         | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 69.12%  |
| 351-400     | 7         | 10.29%  |
| 201-300     | 6         | 8.82%   |
| 501-600     | 4         | 5.88%   |
| 801-900     | 1         | 1.47%   |
| 601-700     | 1         | 1.47%   |
| 401-500     | 1         | 1.47%   |
| 1001-1500   | 1         | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 85.48%  |
| 16/10 | 8         | 12.9%   |
| 3/2   | 1         | 1.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 42.65%  |
| 81-90          | 18        | 26.47%  |
| 121-130        | 5         | 7.35%   |
| 61-70          | 3         | 4.41%   |
| 71-80          | 2         | 2.94%   |
| 301-350        | 2         | 2.94%   |
| 201-250        | 2         | 2.94%   |
| More than 1000 | 1         | 1.47%   |
| 51-60          | 1         | 1.47%   |
| 351-500        | 1         | 1.47%   |
| 251-300        | 1         | 1.47%   |
| 131-140        | 1         | 1.47%   |
| 111-120        | 1         | 1.47%   |
| 501-1000       | 1         | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 41.18%  |
| 101-120       | 27        | 39.71%  |
| 51-100        | 7         | 10.29%  |
| 161-240       | 3         | 4.41%   |
| 1-50          | 2         | 2.94%   |
| More than 240 | 1         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 53        | 84.13%  |
| 2     | 8         | 12.7%   |
| 3     | 1         | 1.59%   |
| 0     | 1         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 34.95%  |
| Realtek Semiconductor           | 32        | 31.07%  |
| Qualcomm Atheros                | 12        | 11.65%  |
| Broadcom                        | 6         | 5.83%   |
| MediaTek                        | 4         | 3.88%   |
| Samsung Electronics             | 2         | 1.94%   |
| TP-Link                         | 1         | 0.97%   |
| Ralink                          | 1         | 0.97%   |
| Qualcomm Atheros Communications | 1         | 0.97%   |
| Nvidia                          | 1         | 0.97%   |
| NetGear                         | 1         | 0.97%   |
| Linksys                         | 1         | 0.97%   |
| Huawei Technologies             | 1         | 0.97%   |
| Broadcom Limited                | 1         | 0.97%   |
| ASUSTek Computer                | 1         | 0.97%   |
| ASIX Electronics                | 1         | 0.97%   |
| Apple                           | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 13        | 10.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 7.09%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.94%   |
| Intel Wireless 3165                                                     | 4         | 3.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 2.36%   |
| Realtek 802.11ac NIC                                                    | 3         | 2.36%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 2.36%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.36%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 1.57%   |
| Intel Wireless 3160                                                     | 2         | 1.57%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.57%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.57%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.57%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.57%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.79%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.79%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 0.79%   |
| NetGear A6210                                                           | 1         | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.79%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 0.79%   |
| Intel Wireless 8260                                                     | 1         | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.79%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.79%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.79%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                                   | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.79%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 47.3%   |
| Realtek Semiconductor           | 15        | 20.27%  |
| Qualcomm Atheros                | 8         | 10.81%  |
| Broadcom                        | 5         | 6.76%   |
| MediaTek                        | 4         | 5.41%   |
| TP-Link                         | 1         | 1.35%   |
| Ralink                          | 1         | 1.35%   |
| Qualcomm Atheros Communications | 1         | 1.35%   |
| NetGear                         | 1         | 1.35%   |
| Linksys                         | 1         | 1.35%   |
| Broadcom Limited                | 1         | 1.35%   |
| ASUSTek Computer                | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 5         | 6.76%   |
| Intel Wireless 3165                                                     | 4         | 5.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 4.05%   |
| Realtek 802.11ac NIC                                                    | 3         | 4.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 4.05%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 4.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.7%    |
| Intel Wireless 3160                                                     | 2         | 2.7%    |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.7%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.35%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.35%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.35%   |
| NetGear A6210                                                           | 1         | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.35%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.35%   |
| Intel Wireless 8260                                                     | 1         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.35%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.35%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.35%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.35%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.35%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 1.35%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.35%   |
| ASUS 802.11ac NIC                                                       | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 50%     |
| Intel                 | 13        | 26%     |
| Qualcomm Atheros      | 5         | 10%     |
| Samsung Electronics   | 2         | 4%      |
| Broadcom              | 2         | 4%      |
| Nvidia                | 1         | 2%      |
| ASIX Electronics      | 1         | 2%      |
| Apple                 | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 17.31%  |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 3.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.85%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 3.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.92%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.92%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.92%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.92%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.92%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.92%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.92%   |
| Apple iBridge                                                     | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 55.86%  |
| Ethernet | 48        | 43.24%  |
| Modem    | 1         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 77.27%  |
| Ethernet | 15        | 22.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 68.25%  |
| 1     | 19        | 30.16%  |
| 3     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 76.19%  |
| Yes  | 15        | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 51.85%  |
| Realtek Semiconductor           | 5         | 9.26%   |
| Qualcomm Atheros Communications | 4         | 7.41%   |
| MediaTek                        | 3         | 5.56%   |
| Toshiba                         | 2         | 3.7%    |
| Lite-On Technology              | 2         | 3.7%    |
| IMC Networks                    | 2         | 3.7%    |
| Broadcom                        | 2         | 3.7%    |
| Apple                           | 2         | 3.7%    |
| Realtek                         | 1         | 1.85%   |
| Ralink                          | 1         | 1.85%   |
| Foxconn / Hon Hai               | 1         | 1.85%   |
| Dell                            | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 13        | 24.07%  |
| Intel Bluetooth Device                           | 6         | 11.11%  |
| Realtek Bluetooth Radio                          | 4         | 7.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 4         | 7.41%   |
| MediaTek Wireless_Device                         | 3         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device               | 2         | 3.7%    |
| Intel AX200 Bluetooth                            | 2         | 3.7%    |
| Toshiba Bluetooth USB Host Controller            | 1         | 1.85%   |
| Toshiba BCM43142A0                               | 1         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 1.85%   |
| Realtek Bluetooth Radio                          | 1         | 1.85%   |
| Ralink RT3290 Bluetooth                          | 1         | 1.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                | 1         | 1.85%   |
| Lite-On Wireless_Device                          | 1         | 1.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 1.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 1.85%   |
| Intel AX210 Bluetooth                            | 1         | 1.85%   |
| IMC Networks Bluetooth Radio                     | 1         | 1.85%   |
| IMC Networks Bluetooth Device                    | 1         | 1.85%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth    | 1         | 1.85%   |
| Dell DW375 Bluetooth Module                      | 1         | 1.85%   |
| Broadcom HP Portable SoftSailing                 | 1         | 1.85%   |
| Broadcom BCM20702A0                              | 1         | 1.85%   |
| Apple Bluetooth USB Host Controller              | 1         | 1.85%   |
| Apple Bluetooth Host Controller                  | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 63.01%  |
| AMD    | 16        | 21.92%  |
| Nvidia | 10        | 13.7%   |
| Apple  | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 12.64%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 9.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 6.9%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.6%    |
| Nvidia Audio device                                                                               | 3         | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.3%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 2.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.3%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.3%    |
| AMD High Definition Audio Controller                                                              | 2         | 2.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.3%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.15%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.15%   |
| Apple Audio Device                                                                                | 1         | 1.15%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.15%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 27.27%  |
| Micron Technology   | 10        | 22.73%  |
| SK hynix            | 7         | 15.91%  |
| Crucial             | 5         | 11.36%  |
| Kingston            | 3         | 6.82%   |
| Unknown (ABCD)      | 2         | 4.55%   |
| Ramaxel Technology  | 2         | 4.55%   |
| Elpida              | 2         | 4.55%   |
| Saikano             | 1         | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 4.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 4.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 4.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 4.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 2         | 4.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 2         | 4.35%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 2.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.17%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 2.17%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 2.17%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 2.17%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 2.17%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 2.17%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s                | 1         | 2.17%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s        | 1         | 2.17%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                         | 1         | 2.17%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 2.17%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s                  | 1         | 2.17%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s            | 1         | 2.17%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s                | 1         | 2.17%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 2.17%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 1         | 2.17%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 2.17%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s               | 1         | 2.17%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s             | 1         | 2.17%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                | 1         | 2.17%   |
| Kingston RAM 9905711-007.A00G 4GB SODIMM DDR4 2400MT/s              | 1         | 2.17%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 2.17%   |
| Elpida RAM Module 1GB SODIMM DDR3 1067MT/s                          | 1         | 2.17%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s              | 1         | 2.17%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16384MB SODIMM DDR4 3200MT/s         | 1         | 2.17%   |
| Crucial RAM CT16G4SFRA266.C8FE 16GB SODIMM DDR4 2667MT/s            | 1         | 2.17%   |
| Crucial RAM CT16G4SFD832A.M16FRS 16384MB SODIMM DDR4 3200MT/s       | 1         | 2.17%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 1         | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 19        | 52.78%  |
| DDR3    | 11        | 30.56%  |
| LPDDR4  | 4         | 11.11%  |
| LPDDR3  | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 86.11%  |
| Row Of Chips | 5         | 13.89%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 19        | 47.5%   |
| 8192  | 9         | 22.5%   |
| 16384 | 7         | 17.5%   |
| 2048  | 2         | 5%      |
| 1024  | 2         | 5%      |
| 32768 | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 12        | 29.27%  |
| 3200  | 8         | 19.51%  |
| 1600  | 8         | 19.51%  |
| 2400  | 4         | 9.76%   |
| 1334  | 3         | 7.32%   |
| 4800  | 1         | 2.44%   |
| 3266  | 1         | 2.44%   |
| 1867  | 1         | 2.44%   |
| 1333  | 1         | 2.44%   |
| 1067  | 1         | 2.44%   |
| 800   | 1         | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 21.67%  |
| Acer                                   | 8         | 13.33%  |
| Microdia                               | 7         | 11.67%  |
| IMC Networks                           | 7         | 11.67%  |
| Apple                                  | 5         | 8.33%   |
| Sunplus Innovation Technology          | 3         | 5%      |
| Realtek Semiconductor                  | 3         | 5%      |
| Quanta                                 | 3         | 5%      |
| Syntek                                 | 1         | 1.67%   |
| Suyin                                  | 1         | 1.67%   |
| Silicon Motion                         | 1         | 1.67%   |
| Ricoh                                  | 1         | 1.67%   |
| Primax Electronics                     | 1         | 1.67%   |
| Luxvisions Innotech Limited            | 1         | 1.67%   |
| Lite-On Technology                     | 1         | 1.67%   |
| Importek                               | 1         | 1.67%   |
| Goertek Electronics                    | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.67%   |
| Alcor Micro                            | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                       | 3         | 5%      |
| Sunplus Integrated_Webcam_HD                         | 2         | 3.33%   |
| IMC Networks Integrated Camera                       | 2         | 3.33%   |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 3.33%   |
| Chicony Integrated Camera                            | 2         | 3.33%   |
| Chicony HP TrueVision HD                             | 2         | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 3.33%   |
| Acer SunplusIT Integrated Camera                     | 2         | 3.33%   |
| Syntek Integrated Camera                             | 1         | 1.67%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 1.67%   |
| Sunplus FHD Camera Microphone                        | 1         | 1.67%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 1.67%   |
| Ricoh HD Webcam                                      | 1         | 1.67%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.67%   |
| Realtek Integrated Webcam                            | 1         | 1.67%   |
| Realtek Integrated Camera                            | 1         | 1.67%   |
| Quanta VGA WebCam                                    | 1         | 1.67%   |
| Quanta HP TrueVision HD Camera                       | 1         | 1.67%   |
| Quanta HD User Facing                                | 1         | 1.67%   |
| Primax HP HD Webcam [Fixed]                          | 1         | 1.67%   |
| Microdia Webcam Vitade AF                            | 1         | 1.67%   |
| Microdia PC Microscope camera                        | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.67%   |
| Microdia Integrated Webcam                           | 1         | 1.67%   |
| Microdia HP Webcam-101                               | 1         | 1.67%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.67%   |
| Lite-On HP HD Camera                                 | 1         | 1.67%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 1.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.67%   |
| IMC Networks USB Camera                              | 1         | 1.67%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 1.67%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 1.67%   |
| IMC Networks HD Camera                               | 1         | 1.67%   |
| Goertek USB2.0 VGA UVC WebCam                        | 1         | 1.67%   |
| Chicony USB2.0 Camera                                | 1         | 1.67%   |
| Chicony Integrated HP HD Webcam                      | 1         | 1.67%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 1.67%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.67%   |
| Chicony HP HD Camera                                 | 1         | 1.67%   |
| Chicony HD User Facing                               | 1         | 1.67%   |
| Chicony EasyCamera                                   | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 1         | 1.67%   |
| Apple FaceTime HD Camera (Built-in)                  | 1         | 1.67%   |
| Apple FaceTime Camera                                | 1         | 1.67%   |
| Apple Built-in iSight                                | 1         | 1.67%   |
| Alcor Micro USB 2.0 Camera                           | 1         | 1.67%   |
| Acer Lenovo EasyCamera                               | 1         | 1.67%   |
| Acer HP TrueVision HD Webcam                         | 1         | 1.67%   |
| Acer HD Camera                                       | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 46.15%  |
| Synaptics                  | 4         | 30.77%  |
| Shenzhen Goodix Technology | 3         | 23.08%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 15.38%  |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                           | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner                      | 1         | 7.69%   |
| Synaptics  WBDI                                           | 1         | 7.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| OmniKey     | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 33.33%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 31        | 49.21%  |
| 1     | 28        | 44.44%  |
| 2     | 4         | 6.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 38.24%  |
| Net/wireless          | 8         | 23.53%  |
| Graphics card         | 5         | 14.71%  |
| Chipcard              | 5         | 14.71%  |
| Multimedia controller | 2         | 5.88%   |
| Bluetooth             | 1         | 2.94%   |

