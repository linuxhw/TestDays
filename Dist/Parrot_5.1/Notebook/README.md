Parrot 5.1 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 5.1.

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

Total: 69

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15s-fq1xxx           | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| Dell          | Inspiron 14 5410            | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Apple         | MacBookPro9,2               | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Acer          | Aspire A315-58              | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| HUAWEI        | BOD-WXX9                    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Dell          | G3 3500                     | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Dell          | Latitude 3350               | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Dell          | Latitude E5500              | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| Clevo         | W25xHPx                     | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| HP            | Presario CQ58               | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| Dell          | Inspiron 14 5410            | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Acer          | Nitro AN515-57              | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.18.0-14parrot1-amd64 | 26        | 50%     |
| 6.0.0-2parrot1-amd64   | 21        | 40.38%  |
| 6.0.0-12parrot1-amd64  | 4         | 7.69%   |
| 5.18.0-1parrot1-amd64  | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.18.0  | 27        | 51.92%  |
| 6.0.0   | 25        | 48.08%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.18    | 27        | 51.92%  |
| 6.0     | 25        | 48.08%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 47        | 90.38%  |
| KDE5    | 4         | 7.69%   |
| Unknown | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 52        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 39        | 75%     |
| Unknown | 12        | 23.08%  |
| SDDM    | 1         | 1.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 27        | 51.92%  |
| fr_FR | 5         | 9.62%   |
| it_IT | 3         | 5.77%   |
| en_GB | 3         | 5.77%   |
| ru_RU | 2         | 3.85%   |
| es_ES | 2         | 3.85%   |
| pt_BR | 1         | 1.92%   |
| pl_PL | 1         | 1.92%   |
| es_PE | 1         | 1.92%   |
| es_MX | 1         | 1.92%   |
| es_AR | 1         | 1.92%   |
| en_ZW | 1         | 1.92%   |
| en_IN | 1         | 1.92%   |
| en_CA | 1         | 1.92%   |
| en_AU | 1         | 1.92%   |
| de_DE | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 27        | 51.92%  |
| BIOS | 25        | 48.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 51        | 98.08%  |
| Overlay | 1         | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 30        | 57.69%  |
| Unknown | 13        | 25%     |
| MBR     | 9         | 17.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 92.31%  |
| Yes       | 4         | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 63.46%  |
| Yes       | 19        | 36.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 11        | 21.15%  |
| Hewlett-Packard      | 7         | 13.46%  |
| Dell                 | 6         | 11.54%  |
| ASUSTek Computer     | 6         | 11.54%  |
| Acer                 | 5         | 9.62%   |
| MSI                  | 3         | 5.77%   |
| Toshiba              | 2         | 3.85%   |
| Quanta               | 2         | 3.85%   |
| HUAWEI               | 2         | 3.85%   |
| Standard             | 1         | 1.92%   |
| Irbis                | 1         | 1.92%   |
| Intel Client Systems | 1         | 1.92%   |
| Clevo                | 1         | 1.92%   |
| BANGHO               | 1         | 1.92%   |
| Apple                | 1         | 1.92%   |
| Alienware            | 1         | 1.92%   |
| Unknown              | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 5.77%   |
| Quanta TW9/SW9                           | 2         | 3.85%   |
| Toshiba Satellite C855D                  | 1         | 1.92%   |
| Toshiba Satellite C75D-B                 | 1         | 1.92%   |
| MSI Katana GF66 12UD                     | 1         | 1.92%   |
| MSI Katana GF66 12UC                     | 1         | 1.92%   |
| MSI GT60                                 | 1         | 1.92%   |
| Lenovo ThinkPad X230 Tablet 34383V4      | 1         | 1.92%   |
| Lenovo ThinkPad X230 Tablet 343727U      | 1         | 1.92%   |
| Lenovo ThinkPad X220 Tablet 42962WU      | 1         | 1.92%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1S05B00 | 1         | 1.92%   |
| Lenovo ThinkPad T460 20FMS2J300          | 1         | 1.92%   |
| Lenovo ThinkPad E570 20H5009MUS          | 1         | 1.92%   |
| Lenovo ThinkPad E15 Gen 3 20YGCTO1WW     | 1         | 1.92%   |
| Lenovo ThinkPad E15 Gen 3 20YG0041MX     | 1         | 1.92%   |
| Lenovo LEGIONC7 82EH                     | 1         | 1.92%   |
| Lenovo Legion 5 15ACH6H 82JU             | 1         | 1.92%   |
| Lenovo IdeaPad 3 15IGL05 81WQ            | 1         | 1.92%   |
| Irbis NB121                              | 1         | 1.92%   |
| Intel Client Systems LAPBC510            | 1         | 1.92%   |
| HUAWEI BOHB-WAX9                         | 1         | 1.92%   |
| HUAWEI BOD-WXX9                          | 1         | 1.92%   |
| HP Victus by Laptop 16-e0xxx             | 1         | 1.92%   |
| HP Victus by Laptop 16-d1xxx             | 1         | 1.92%   |
| HP Presario CQ58                         | 1         | 1.92%   |
| HP Laptop 15s-fq1xxx                     | 1         | 1.92%   |
| HP Laptop 15-dy1xxx                      | 1         | 1.92%   |
| HP Laptop 15-bs0xx                       | 1         | 1.92%   |
| Dell Latitude E6520                      | 1         | 1.92%   |
| Dell Latitude E5500                      | 1         | 1.92%   |
| Dell Latitude 3350                       | 1         | 1.92%   |
| Dell Inspiron 14 5410                    | 1         | 1.92%   |
| Dell Inspiron 13-7378                    | 1         | 1.92%   |
| Dell G3 3500                             | 1         | 1.92%   |
| Clevo W25xHPx                            | 1         | 1.92%   |
| BANGHO GAMER GM-X 15s                    | 1         | 1.92%   |
| ASUS ZenBook UX482EA_UX482EA             | 1         | 1.92%   |
| ASUS Zenbook UX3402ZA_UX3402ZA           | 1         | 1.92%   |
| ASUS VivoBook_ASUSLaptop X515UA_M515UA   | 1         | 1.92%   |
| ASUS ASUS TUF Gaming F15 FX506LH_FX506LH | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 8         | 15.38%  |
| HP Laptop                     | 3         | 5.77%   |
| Dell Latitude                 | 3         | 5.77%   |
| ASUS ASUS                     | 3         | 5.77%   |
| Unknown                       | 3         | 5.77%   |
| Toshiba Satellite             | 2         | 3.85%   |
| Quanta TW9                    | 2         | 3.85%   |
| MSI Katana                    | 2         | 3.85%   |
| HP Victus                     | 2         | 3.85%   |
| Dell Inspiron                 | 2         | 3.85%   |
| ASUS Zenbook                  | 2         | 3.85%   |
| Acer Aspire                   | 2         | 3.85%   |
| MSI GT60                      | 1         | 1.92%   |
| Lenovo LEGIONC7               | 1         | 1.92%   |
| Lenovo Legion                 | 1         | 1.92%   |
| Lenovo IdeaPad                | 1         | 1.92%   |
| Irbis NB121                   | 1         | 1.92%   |
| Intel Client Systems LAPBC510 | 1         | 1.92%   |
| HUAWEI BOHB-WAX9              | 1         | 1.92%   |
| HUAWEI BOD-WXX9               | 1         | 1.92%   |
| HP Presario                   | 1         | 1.92%   |
| Dell G3                       | 1         | 1.92%   |
| Clevo W25xHPx                 | 1         | 1.92%   |
| BANGHO GAMER                  | 1         | 1.92%   |
| ASUS VivoBook                 | 1         | 1.92%   |
| Apple MacBookPro9             | 1         | 1.92%   |
| Alienware m15                 | 1         | 1.92%   |
| Acer Swift                    | 1         | 1.92%   |
| Acer Predator                 | 1         | 1.92%   |
| Acer Nitro                    | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 21        | 40.38%  |
| 2012 | 6         | 11.54%  |
| 2022 | 5         | 9.62%   |
| 2019 | 4         | 7.69%   |
| 2020 | 3         | 5.77%   |
| 2016 | 3         | 5.77%   |
| 2011 | 3         | 5.77%   |
| 2017 | 2         | 3.85%   |
| 2010 | 2         | 3.85%   |
| 2018 | 1         | 1.92%   |
| 2014 | 1         | 1.92%   |
| 2008 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 52        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 52        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 28.85%  |
| 16.01-24.0 | 15        | 28.85%  |
| 8.01-16.0  | 14        | 26.92%  |
| 3.01-4.0   | 6         | 11.54%  |
| 32.01-64.0 | 2         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 18        | 33.96%  |
| 1.01-2.0 | 18        | 33.96%  |
| 3.01-4.0 | 11        | 20.75%  |
| 4.01-8.0 | 5         | 9.43%   |
| 0.51-1.0 | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 76.92%  |
| 2      | 12        | 23.08%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 78.85%  |
| Yes       | 11        | 21.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 75%     |
| No        | 13        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 78.85%  |
| No        | 11        | 21.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 25%     |
| France       | 7         | 13.46%  |
| Russia       | 3         | 5.77%   |
| Italy        | 3         | 5.77%   |
| Spain        | 2         | 3.85%   |
| Netherlands  | 2         | 3.85%   |
| Kenya        | 2         | 3.85%   |
| Germany      | 2         | 3.85%   |
| Zimbabwe     | 1         | 1.92%   |
| UK           | 1         | 1.92%   |
| Sweden       | 1         | 1.92%   |
| Saudi Arabia | 1         | 1.92%   |
| Poland       | 1         | 1.92%   |
| Peru         | 1         | 1.92%   |
| Nepal        | 1         | 1.92%   |
| Namibia      | 1         | 1.92%   |
| Mongolia     | 1         | 1.92%   |
| Mexico       | 1         | 1.92%   |
| Luxembourg   | 1         | 1.92%   |
| Finland      | 1         | 1.92%   |
| Czechia      | 1         | 1.92%   |
| Canada       | 1         | 1.92%   |
| Brazil       | 1         | 1.92%   |
| Bangladesh   | 1         | 1.92%   |
| Australia    | 1         | 1.92%   |
| Argentina    | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Moscow              | 3         | 5.45%   |
| Lyon                | 2         | 3.64%   |
| Amsterdam           | 2         | 3.64%   |
| Warsaw              | 1         | 1.82%   |
| Visalia             | 1         | 1.82%   |
| Veracruz            | 1         | 1.82%   |
| Västerås          | 1         | 1.82%   |
| Ulan Bator          | 1         | 1.82%   |
| Turin               | 1         | 1.82%   |
| Swakopmund          | 1         | 1.82%   |
| San Juan            | 1         | 1.82%   |
| San Antonio         | 1         | 1.82%   |
| Rongai              | 1         | 1.82%   |
| Rome                | 1         | 1.82%   |
| Prague              | 1         | 1.82%   |
| Parsons             | 1         | 1.82%   |
| Parnamirim          | 1         | 1.82%   |
| Paris               | 1         | 1.82%   |
| Orange Park         | 1         | 1.82%   |
| Naples              | 1         | 1.82%   |
| Nanyuki             | 1         | 1.82%   |
| Nairobi             | 1         | 1.82%   |
| Mesa                | 1         | 1.82%   |
| Melbourne           | 1         | 1.82%   |
| Marshall            | 1         | 1.82%   |
| Luxembourg          | 1         | 1.82%   |
| London              | 1         | 1.82%   |
| Lima                | 1         | 1.82%   |
| Liberty             | 1         | 1.82%   |
| Les Mureaux         | 1         | 1.82%   |
| La Garenne-Colombes | 1         | 1.82%   |
| Jeddah              | 1         | 1.82%   |
| Houston             | 1         | 1.82%   |
| Helsinki            | 1         | 1.82%   |
| Harare              | 1         | 1.82%   |
| Estepona            | 1         | 1.82%   |
| Edmonton            | 1         | 1.82%   |
| Dresden             | 1         | 1.82%   |
| Dhaka               | 1         | 1.82%   |
| Dallas              | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 20%     |
| WDC                 | 8         | 9      | 13.33%  |
| Unknown             | 4         | 4      | 6.67%   |
| Toshiba             | 4         | 4      | 6.67%   |
| SK hynix            | 3         | 3      | 5%      |
| SanDisk             | 3         | 4      | 5%      |
| Micron Technology   | 3         | 3      | 5%      |
| Kingston            | 3         | 3      | 5%      |
| Intel               | 3         | 4      | 5%      |
| HGST                | 3         | 4      | 5%      |
| Unknown             | 3         | 3      | 5%      |
| YMTC                | 2         | 2      | 3.33%   |
| Hitachi             | 2         | 2      | 3.33%   |
| Seagate             | 1         | 1      | 1.67%   |
| LITEON              | 1         | 1      | 1.67%   |
| Hikvision           | 1         | 1      | 1.67%   |
| Crucial             | 1         | 1      | 1.67%   |
| BW-PSSD1            | 1         | 1      | 1.67%   |
| BR                  | 1         | 1      | 1.67%   |
| A-DATA Technology   | 1         | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown                                            | 3         | 4.62%   |
| YMTC PC005 256GB                                   | 2         | 3.08%   |
| Intel SSDPEKNU512GZ 512GB                          | 2         | 3.08%   |
| WDC WDS480G2G0C-00AJM0 480GB                       | 1         | 1.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 1.54%   |
| WDC WD5000BUCT-63PUZY0 500GB                       | 1         | 1.54%   |
| WDC WD3200BEVT-22A23T0 320GB                       | 1         | 1.54%   |
| WDC WD3200BEKT-75PVMT1 320GB                       | 1         | 1.54%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                 | 1         | 1.54%   |
| WDC PC SN530 SDBPNPZ-1T00-1114 1TB                 | 1         | 1.54%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB               | 1         | 1.54%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB               | 1         | 1.54%   |
| Unknown SD2GB                                      | 1         | 1.54%   |
| Unknown SD/MMC/MS PRO 250GB                        | 1         | 1.54%   |
| Unknown MMC Card  8GB                              | 1         | 1.54%   |
| Unknown MMC Card  64GB                             | 1         | 1.54%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.54%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 1.54%   |
| Toshiba KXG6AZNV256G 256GB                         | 1         | 1.54%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                  | 1         | 1.54%   |
| SK hynix PC801 NVMe 512GB                          | 1         | 1.54%   |
| SK hynix PC711 HFS512GDE9X073N 512GB               | 1         | 1.54%   |
| SK hynix HFM512GD3JX013N 512GB                     | 1         | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.54%   |
| Sandisk WD Black SN850 1TB                         | 1         | 1.54%   |
| SanDisk SD8SBAT256G1122 256GB SSD                  | 1         | 1.54%   |
| SanDisk NVMe SSD Drive 512GB                       | 1         | 1.54%   |
| SanDisk NVMe SSD Drive 1TB                         | 1         | 1.54%   |
| Samsung SSD 980 PRO 1TB                            | 1         | 1.54%   |
| Samsung SSD 970 EVO Plus 500GB                     | 1         | 1.54%   |
| Samsung SSD 970 EVO Plus 2TB                       | 1         | 1.54%   |
| Samsung SSD 860 EVO M.2 500GB                      | 1         | 1.54%   |
| Samsung PM981a NVMe 1024GB                         | 1         | 1.54%   |
| Samsung NVMe SSD Drive 512GB                       | 1         | 1.54%   |
| Samsung NVMe SSD Drive 1024GB                      | 1         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1         | 1.54%   |
| Samsung MZVLQ512HALU-00000 512GB                   | 1         | 1.54%   |
| Samsung MZVL2512HCJQ-00B00 512GB                   | 1         | 1.54%   |
| Samsung MZMPC128HBFU-000L1 128GB SSD               | 1         | 1.54%   |
| Samsung MZ7PD256HCGM-000H7 256GB SSD               | 1         | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 23.08%  |
| HGST                | 3         | 4      | 23.08%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Hitachi             | 2         | 2      | 15.38%  |
| Unknown             | 1         | 1      | 7.69%   |
| Seagate             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 36.36%  |
| Unknown             | 2         | 2      | 18.18%  |
| WDC                 | 1         | 1      | 9.09%   |
| SanDisk             | 1         | 1      | 9.09%   |
| LITEON              | 1         | 1      | 9.09%   |
| Crucial             | 1         | 1      | 9.09%   |
| BR                  | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 30        | 38     | 51.72%  |
| HDD     | 13        | 14     | 22.41%  |
| SSD     | 11        | 11     | 18.97%  |
| MMC     | 3         | 4      | 5.17%   |
| Unknown | 1         | 1      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 38     | 51.72%  |
| SATA | 23        | 24     | 39.66%  |
| MMC  | 3         | 4      | 5.17%   |
| SAS  | 2         | 2      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 19     | 73.91%  |
| 0.51-1.0   | 6         | 6      | 26.09%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 21.15%  |
| 501-1000   | 11        | 21.15%  |
| Unknown    | 11        | 21.15%  |
| 101-250    | 7         | 13.46%  |
| 1001-2000  | 5         | 9.62%   |
| 51-100     | 4         | 7.69%   |
| 1-20       | 2         | 3.85%   |
| 21-50      | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 22        | 41.51%  |
| Unknown  | 11        | 20.75%  |
| 51-100   | 8         | 15.09%  |
| 101-250  | 7         | 13.21%  |
| 251-500  | 2         | 3.77%   |
| 1-20     | 1         | 1.89%   |
| 501-1000 | 1         | 1.89%   |
| 0        | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 11.11%  |
| SanDisk SD8SBAT256G1122 256GB SSD | 1         | 1      | 11.11%  |
| LITEON CV8-8E128-HP 128GB SSD     | 1         | 1      | 11.11%  |
| Hitachi HTS723216L9SA60 160GB     | 1         | 1      | 11.11%  |
| HGST HTS725032A7E630 320GB        | 1         | 1      | 11.11%  |
| HGST HTS541010A9E680 1TB          | 1         | 1      | 11.11%  |
| Crucial CT525MX300SSD1 528GB      | 1         | 1      | 11.11%  |
| Unknown                           | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| Toshiba | 1         | 1      | 11.11%  |
| SanDisk | 1         | 1      | 11.11%  |
| LITEON  | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| Crucial | 1         | 1      | 11.11%  |
| Unknown | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 55.56%  |
| SSD  | 4         | 4      | 44.44%  |

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
| Works    | 29        | 35     | 50.88%  |
| Detected | 19        | 24     | 33.33%  |
| Malfunc  | 9         | 9      | 15.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 54.17%  |
| Samsung Electronics          | 7         | 9.72%   |
| SanDisk                      | 6         | 8.33%   |
| AMD                          | 5         | 6.94%   |
| SK hynix                     | 3         | 4.17%   |
| Micron Technology            | 3         | 4.17%   |
| Kingston Technology Company  | 3         | 4.17%   |
| Yangtze Memory Technologies  | 2         | 2.78%   |
| Toshiba America Info Systems | 1         | 1.39%   |
| Silicon Motion               | 1         | 1.39%   |
| KIOXIA                       | 1         | 1.39%   |
| ADATA Technology             | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                                    | 10        | 12.5%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 5%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 3.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 3.75%   |
| Intel Alder Lake-P SATA AHCI Controller                                                | 3         | 3.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.75%   |
| Yangtze Memory Non-Volatile memory controller                                          | 2         | 2.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 2         | 2.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 2.5%    |
| SanDisk PC SN530 NVMe SSD                                                              | 2         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.5%    |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.5%    |
| Micron 2450 NVMe SSD (DRAM-less)                                                       | 2         | 2.5%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 2.5%    |
| Intel Non-Volatile memory controller                                                   | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 2.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 1.25%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                     | 1         | 1.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 1.25%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.25%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 1.25%   |
| Micron NVMe Storage Controller                                                         | 1         | 1.25%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.25%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.25%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.25%   |
| Kingston Company NVMe Controller                                                       | 1         | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.25%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 1         | 1.25%   |
| Intel NVMe Controller                                                                  | 1         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 41.56%  |
| NVMe | 30        | 38.96%  |
| RAID | 13        | 16.88%  |
| IDE  | 2         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 84.62%  |
| AMD    | 8         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i5-12500H           | 3         | 5.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 5.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 3.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 3.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 3.85%   |
| Intel 12th Gen Core i7-12700H           | 2         | 3.85%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz | 2         | 3.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.92%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.92%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.92%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 1.92%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 1         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.92%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.92%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 1         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.92%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.92%   |
| Intel Core i5 CPU M 430 @ 2.27GHz       | 1         | 1.92%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.92%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 1         | 1.92%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 1         | 1.92%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 1         | 1.92%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 1.92%   |
| Intel Celeron CPU B820 @ 1.70GHz        | 1         | 1.92%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.92%   |
| Intel 12th Gen Core i5-1240P            | 1         | 1.92%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 1.92%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 1         | 1.92%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 1.92%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 1         | 1.92%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 1         | 1.92%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 1         | 1.92%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 1.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 16        | 30.77%  |
| Intel Core i7    | 9         | 17.31%  |
| Intel Core i5    | 8         | 15.38%  |
| Intel Core i3    | 6         | 11.54%  |
| Intel Celeron    | 4         | 7.69%   |
| AMD Ryzen 7      | 3         | 5.77%   |
| AMD Ryzen 5      | 2         | 3.85%   |
| AMD A6           | 2         | 3.85%   |
| Intel Core 2 Duo | 1         | 1.92%   |
| AMD Ryzen 3      | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 40.38%  |
| 4      | 12        | 23.08%  |
| 6      | 6         | 11.54%  |
| 12     | 5         | 9.62%   |
| 8      | 5         | 9.62%   |
| 14     | 2         | 3.85%   |
| 1      | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 73.08%  |
| 1      | 14        | 26.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 28.85%  |
| 0x906a3    | 7         | 13.46%  |
| 0xa0652    | 3         | 5.77%   |
| 0x706a8    | 3         | 5.77%   |
| 0x406e3    | 3         | 5.77%   |
| 0x306a9    | 3         | 5.77%   |
| 0x206a7    | 3         | 5.77%   |
| 0x08608103 | 3         | 5.77%   |
| 0x806c1    | 2         | 3.85%   |
| 0xa0660    | 1         | 1.92%   |
| 0x806ec    | 1         | 1.92%   |
| 0x806e9    | 1         | 1.92%   |
| 0x806d1    | 1         | 1.92%   |
| 0x706e5    | 1         | 1.92%   |
| 0x6fd      | 1         | 1.92%   |
| 0x40651    | 1         | 1.92%   |
| 0x106e5    | 1         | 1.92%   |
| 0x0a50000c | 1         | 1.92%   |
| 0x07030105 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 7         | 13.46%  |
| TigerLake        | 6         | 11.54%  |
| Alderlake Hybrid | 6         | 11.54%  |
| SandyBridge      | 4         | 7.69%   |
| IvyBridge        | 4         | 7.69%   |
| CometLake        | 4         | 7.69%   |
| Skylake          | 3         | 5.77%   |
| KabyLake         | 3         | 5.77%   |
| Goldmont plus    | 3         | 5.77%   |
| Zen 3            | 2         | 3.85%   |
| IceLake          | 2         | 3.85%   |
| Zen 2            | 1         | 1.92%   |
| Westmere         | 1         | 1.92%   |
| Puma             | 1         | 1.92%   |
| Piledriver       | 1         | 1.92%   |
| Nehalem          | 1         | 1.92%   |
| Haswell          | 1         | 1.92%   |
| Core             | 1         | 1.92%   |
| Broadwell        | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 59.72%  |
| Nvidia | 21        | 29.17%  |
| AMD    | 8         | 11.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                         | 7         | 9.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 6.94%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 4         | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 5.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 4.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 4.17%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 4.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 4.17%   |
| AMD Lucienne                                                              | 3         | 4.17%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.39%   |
| Nvidia TU117M                                                             | 1         | 1.39%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 1.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.39%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                  | 1         | 1.39%   |
| Nvidia GT215M [GeForce GT 335M]                                           | 1         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.39%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 1.39%   |
| Nvidia GF114M [GeForce GTX 670M]                                          | 1         | 1.39%   |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 1.39%   |
| Nvidia GF106M [GeForce GT 445M]                                           | 1         | 1.39%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 1.39%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.39%   |
| Intel HD Graphics 630                                                     | 1         | 1.39%   |
| Intel HD Graphics 620                                                     | 1         | 1.39%   |
| Intel HD Graphics 5500                                                    | 1         | 1.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.39%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.39%   |
| AMD Trinity 2 [Radeon HD 7520G]                                           | 1         | 1.39%   |
| AMD Renoir                                                                | 1         | 1.39%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 50%     |
| Intel + Nvidia | 17        | 32.69%  |
| 1 x AMD        | 5         | 9.62%   |
| AMD + Nvidia   | 3         | 5.77%   |
| 1 x Nvidia     | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 41        | 78.85%  |
| Proprietary | 11        | 21.15%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 78.85%  |
| 0.51-1.0   | 5         | 9.62%   |
| 3.01-4.0   | 2         | 3.85%   |
| 0.01-0.5   | 2         | 3.85%   |
| 2.01-3.0   | 1         | 1.92%   |
| 1.01-2.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 15        | 23.81%  |
| AU Optronics            | 13        | 20.63%  |
| LG Display              | 9         | 14.29%  |
| Chimei Innolux          | 7         | 11.11%  |
| Samsung Electronics     | 6         | 9.52%   |
| ___                     | 1         | 1.59%   |
| ViewSonic               | 1         | 1.59%   |
| Unknown                 | 1         | 1.59%   |
| STD                     | 1         | 1.59%   |
| Sharp                   | 1         | 1.59%   |
| Planar                  | 1         | 1.59%   |
| PANDA                   | 1         | 1.59%   |
| LG Philips              | 1         | 1.59%   |
| Hewlett-Packard         | 1         | 1.59%   |
| Eizo                    | 1         | 1.59%   |
| Dell                    | 1         | 1.59%   |
| Chi Mei Optoelectronics | 1         | 1.59%   |
| Apple                   | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 4.76%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 3         | 4.76%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 3.17%   |
| ___ LCDTV16 ___9000 1360x768                                             | 1         | 1.59%   |
| ViewSonic VA2718-FHD VSCD839 1920x1080 598x336mm 27.0-inch               | 1         | 1.59%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 1.59%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                        | 1         | 1.59%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 1         | 1.59%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 1         | 1.59%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch        | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 1         | 1.59%   |
| Planar PNR PL1910MW PNR1910 1440x900 410x257mm 19.1-inch                 | 1         | 1.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.59%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD06A5 1920x1080 344x194mm 15.5-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD050B 1920x1080 309x174mm 14.0-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.59%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch               | 1         | 1.59%   |
| Eizo EV2450 ENC2530 1920x1080 528x297mm 23.9-inch                        | 1         | 1.59%   |
| Dell E2416H DELA0CA 1920x1080 531x299mm 24.0-inch                        | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1591 1366x768 344x193mm 15.5-inch | 1         | 1.59%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE09F1 1920x1080 355x200mm 16.0-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE0990 2560x1600 344x215mm 16.0-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE0979 1366x768 256x144mm 11.6-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE0921 1920x515                                         | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 32        | 54.24%  |
| 1366x768 (WXGA)  | 14        | 23.73%  |
| 1600x900 (HD+)   | 3         | 5.08%   |
| 1440x900 (WXGA+) | 2         | 3.39%   |
| 1280x800 (WXGA)  | 2         | 3.39%   |
| 2880x1800        | 1         | 1.69%   |
| 2560x1600        | 1         | 1.69%   |
| 2240x1400        | 1         | 1.69%   |
| 1920x515         | 1         | 1.69%   |
| 1360x768         | 1         | 1.69%   |
| 1024x768 (XGA)   | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 49.21%  |
| 14      | 7         | 11.11%  |
| 17      | 4         | 6.35%   |
| 27      | 3         | 4.76%   |
| 16      | 3         | 4.76%   |
| 13      | 3         | 4.76%   |
| 12      | 3         | 4.76%   |
| 24      | 2         | 3.17%   |
| 11      | 2         | 3.17%   |
| Unknown | 2         | 3.17%   |
| 72      | 1         | 1.59%   |
| 31      | 1         | 1.59%   |
| 19      | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 61.9%   |
| 201-300     | 8         | 12.7%   |
| 351-400     | 6         | 9.52%   |
| 501-600     | 5         | 7.94%   |
| Unknown     | 2         | 3.17%   |
| 601-700     | 1         | 1.59%   |
| 401-500     | 1         | 1.59%   |
| 1501-2000   | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 85.45%  |
| 16/10 | 6         | 10.91%  |
| 4/3   | 1         | 1.82%   |
| 3.73  | 1         | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 52.38%  |
| 81-90          | 8         | 12.7%   |
| 121-130        | 4         | 6.35%   |
| 61-70          | 3         | 4.76%   |
| 301-350        | 3         | 4.76%   |
| 71-80          | 2         | 3.17%   |
| 51-60          | 2         | 3.17%   |
| 201-250        | 2         | 3.17%   |
| Unknown        | 2         | 3.17%   |
| More than 1000 | 1         | 1.59%   |
| 351-500        | 1         | 1.59%   |
| 151-200        | 1         | 1.59%   |
| 111-120        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 35        | 56.45%  |
| 101-120       | 12        | 19.35%  |
| 51-100        | 8         | 12.9%   |
| 161-240       | 3         | 4.84%   |
| Unknown       | 2         | 3.23%   |
| More than 240 | 1         | 1.61%   |
| 1-50          | 1         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 43        | 81.13%  |
| 2     | 8         | 15.09%  |
| 3     | 2         | 3.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 35        | 40.23%  |
| Realtek Semiconductor                  | 31        | 35.63%  |
| Qualcomm Atheros                       | 7         | 8.05%   |
| MediaTek                               | 4         | 4.6%    |
| TP-Link                                | 2         | 2.3%    |
| Xiaomi                                 | 1         | 1.15%   |
| Sony Ericsson Mobile Communications AB | 1         | 1.15%   |
| Samsung Electronics                    | 1         | 1.15%   |
| JMicron Technology                     | 1         | 1.15%   |
| D-Link                                 | 1         | 1.15%   |
| Broadcom Limited                       | 1         | 1.15%   |
| Broadcom                               | 1         | 1.15%   |
| Belkin Components                      | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 16.16%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 6.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 4.04%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 4.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 3.03%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 3.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.02%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.02%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.02%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.01%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.01%   |
| TP-Link 802.11ac NIC                                              | 1         | 1.01%   |
| Sony Ericsson Mobile AB G8341                                     | 1         | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.01%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.01%   |
| Realtek PCIe GbE Family Controller                                | 1         | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.01%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.01%   |
| Realtek 802.11ac NIC                                              | 1         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.01%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.01%   |
| Intel Wireless 8260                                               | 1         | 1.01%   |
| Intel Wireless 7265                                               | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 61.4%   |
| Realtek Semiconductor | 9         | 15.79%  |
| Qualcomm Atheros      | 4         | 7.02%   |
| MediaTek              | 4         | 7.02%   |
| TP-Link               | 2         | 3.51%   |
| D-Link                | 1         | 1.75%   |
| Broadcom              | 1         | 1.75%   |
| Belkin Components     | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                     | Notebooks | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                                          | 6         | 10.53%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                             | 4         | 7.02%   |
| Intel Wi-Fi 6 AX201                                                                       | 4         | 7.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                              | 4         | 7.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                  | 3         | 5.26%   |
| Intel Wi-Fi 6 AX200                                                                       | 3         | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                          | 2         | 3.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                                            | 2         | 3.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                          | 2         | 3.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                         | 2         | 3.51%   |
| Intel Comet Lake PCH CNVi WiFi                                                            | 2         | 3.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                | 1         | 1.75%   |
| TP-Link 802.11ac NIC                                                                      | 1         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                  | 1         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                  | 1         | 1.75%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                       | 1         | 1.75%   |
| Realtek RTL8723DE Wireless Network Adapter                                                | 1         | 1.75%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                | 1         | 1.75%   |
| Realtek 802.11ac NIC                                                                      | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                | 1         | 1.75%   |
| Intel Wireless 8265 / 8275                                                                | 1         | 1.75%   |
| Intel Wireless 8260                                                                       | 1         | 1.75%   |
| Intel Wireless 7265                                                                       | 1         | 1.75%   |
| Intel Wireless 7260                                                                       | 1         | 1.75%   |
| Intel WiFi Link 5100                                                                      | 1         | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                                           | 1         | 1.75%   |
| Intel Centrino Wireless-N 2230                                                            | 1         | 1.75%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                             | 1         | 1.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                              | 1         | 1.75%   |
| Intel Centrino Advanced-N 6200                                                            | 1         | 1.75%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                      | 1         | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                                            | 1         | 1.75%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU] | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 26        | 61.9%   |
| Intel                                  | 6         | 14.29%  |
| Qualcomm Atheros                       | 4         | 9.52%   |
| Xiaomi                                 | 1         | 2.38%   |
| Sony Ericsson Mobile Communications AB | 1         | 2.38%   |
| Samsung Electronics                    | 1         | 2.38%   |
| JMicron Technology                     | 1         | 2.38%   |
| Broadcom Limited                       | 1         | 2.38%   |
| Broadcom                               | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 38.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 9.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.76%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 4.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.38%   |
| Sony Ericsson Mobile AB G8341                                     | 1         | 2.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.38%   |
| Realtek PCIe GbE Family Controller                                | 1         | 2.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.38%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 2.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.38%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.38%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 57.14%  |
| Ethernet | 39        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 71.15%  |
| Ethernet | 15        | 28.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 69.81%  |
| 1     | 13        | 24.53%  |
| 0     | 2         | 3.77%   |
| 3     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 67.92%  |
| Yes  | 17        | 32.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 56.1%   |
| Realtek Semiconductor           | 5         | 12.2%   |
| IMC Networks                    | 5         | 12.2%   |
| Qualcomm Atheros Communications | 3         | 7.32%   |
| TP-Link                         | 1         | 2.44%   |
| Lite-On Technology              | 1         | 2.44%   |
| Dell                            | 1         | 2.44%   |
| Broadcom                        | 1         | 2.44%   |
| Apple                           | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 11        | 26.83%  |
| Realtek Bluetooth Radio                        | 3         | 7.32%   |
| Intel Bluetooth wireless interface             | 3         | 7.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 7.32%   |
| IMC Networks Wireless_Device                   | 3         | 7.32%   |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 4.88%   |
| Qualcomm Atheros Bluetooth                     | 2         | 4.88%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 4.88%   |
| Intel Bluetooth Device                         | 2         | 4.88%   |
| Intel AX200 Bluetooth                          | 2         | 4.88%   |
| TP-Link UB500 Adapter                          | 1         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 2.44%   |
| Lite-On Wireless_Device                        | 1         | 2.44%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.44%   |
| IMC Networks Bluetooth Device                  | 1         | 2.44%   |
| Dell DW375 Bluetooth Module                    | 1         | 2.44%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 2.44%   |
| Apple Bluetooth USB Host Controller            | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 62.86%  |
| Nvidia | 17        | 24.29%  |
| AMD    | 8         | 11.43%  |
| JMTek  | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 8.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 7.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 7.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 6.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 5.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 3.8%    |
| Nvidia Audio device                                                        | 3         | 3.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 3.8%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 3.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.53%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.53%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.27%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.27%   |
| JMTek USB Speaker                                                          | 1         | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.27%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.27%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.27%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 26.09%  |
| Micron Technology   | 9         | 19.57%  |
| SK hynix            | 8         | 17.39%  |
| Crucial             | 4         | 8.7%    |
| Unknown (ABCD)      | 2         | 4.35%   |
| Nanya Technology    | 2         | 4.35%   |
| A-DATA Technology   | 2         | 4.35%   |
| Transcend           | 1         | 2.17%   |
| Timetec             | 1         | 2.17%   |
| Ramaxel Technology  | 1         | 2.17%   |
| PNY                 | 1         | 2.17%   |
| Kingston            | 1         | 2.17%   |
| Elpida              | 1         | 2.17%   |
| ChangXin Memory     | 1         | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 4.26%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 4.26%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 4.26%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 4.26%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM 1334MT/s                   | 1         | 2.13%   |
| Timetec RAM SD3-1333 8192MB SODIMM DDR3 1333MT/s                 | 1         | 2.13%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 2.13%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.13%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 2.13%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.13%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 2.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.13%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.13%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.13%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 2.13%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 1         | 2.13%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| PNY RAM Module 8GB SODIMM DDR3 1600MT/s                          | 1         | 2.13%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 2.13%   |
| Nanya RAM M2S4G64CB8HG5N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 2.13%   |
| Micron RAM CT102464BF186D.C16 8192MB SODIMM DDR3 1867MT/s        | 1         | 2.13%   |
| Micron RAM 8ATF1G64HZ-2G3H1R 8GB SODIMM DDR4 2400MT/s            | 1         | 2.13%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.13%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 2.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.13%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Micron RAM 16HTF25664HY-800E1 2GB SODIMM DDR2 975MT/s            | 1         | 2.13%   |
| Kingston RAM SNY1333S9-2G-ELFEU 2GB SODIMM DDR3 1333MT/s         | 1         | 2.13%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 2.13%   |
| Crucial RAM CT8G4SFRA32A.M4FE 8GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Crucial RAM CT8G4SFRA32A.C8FR 8GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 19        | 47.5%   |
| DDR3   | 11        | 27.5%   |
| LPDDR4 | 4         | 10%     |
| LPDDR5 | 2         | 5%      |
| DDR5   | 2         | 5%      |
| LPDDR3 | 1         | 2.5%    |
| DDR2   | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 85%     |
| Row Of Chips | 6         | 15%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 26        | 65%     |
| 4096  | 5         | 12.5%   |
| 16384 | 4         | 10%     |
| 2048  | 4         | 10%     |
| 1024  | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 26.83%  |
| 1600  | 7         | 17.07%  |
| 2667  | 6         | 14.63%  |
| 2400  | 4         | 9.76%   |
| 6400  | 2         | 4.88%   |
| 4800  | 2         | 4.88%   |
| 1334  | 2         | 4.88%   |
| 1333  | 2         | 4.88%   |
| 4267  | 1         | 2.44%   |
| 3733  | 1         | 2.44%   |
| 2133  | 1         | 2.44%   |
| 1867  | 1         | 2.44%   |
| 975   | 1         | 2.44%   |

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
| Chicony Electronics                    | 9         | 20%     |
| IMC Networks                           | 7         | 15.56%  |
| Quanta                                 | 4         | 8.89%   |
| Sonix Technology                       | 3         | 6.67%   |
| Syntek                                 | 2         | 4.44%   |
| Suyin                                  | 2         | 4.44%   |
| Sunplus Innovation Technology          | 2         | 4.44%   |
| Realtek Semiconductor                  | 2         | 4.44%   |
| Microdia                               | 2         | 4.44%   |
| Luxvisions Innotech Limited            | 2         | 4.44%   |
| Apple                                  | 2         | 4.44%   |
| USB Camera CS                          | 1         | 2.22%   |
| USB Camera                             | 1         | 2.22%   |
| Samsung Electronics                    | 1         | 2.22%   |
| Logitech                               | 1         | 2.22%   |
| Importek                               | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |
| Bison Electronics                      | 1         | 2.22%   |
| Acer                                   | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                       | 2         | 4.44%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 4.44%   |
| Realtek Integrated_Webcam_HD                                   | 2         | 4.44%   |
| Quanta HD User Facing                                          | 2         | 4.44%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 4.44%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 4.44%   |
| IMC Networks Integrated Camera                                 | 2         | 4.44%   |
| Chicony HD User Facing                                         | 2         | 4.44%   |
| USB Camera USB Camera                                          | 1         | 2.22%   |
| USB Camera CS USB Camera CS                                    | 1         | 2.22%   |
| Suyin USB 2.0 UVC 1.3M WebCam                                  | 1         | 2.22%   |
| Suyin HP Webcam-50                                             | 1         | 2.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 2.22%   |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 2.22%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 1         | 2.22%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 2.22%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.22%   |
| Quanta HD Camera                                               | 1         | 2.22%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 2.22%   |
| Logitech BRIO Ultra HD Webcam                                  | 1         | 2.22%   |
| Importek TOSHIBA Web Camera                                    | 1         | 2.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 2.22%   |
| IMC Networks HP TrueVision HD Camera                           | 1         | 2.22%   |
| IMC Networks HD Camera                                         | 1         | 2.22%   |
| Chicony USB2.0 Camera                                          | 1         | 2.22%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 2.22%   |
| Chicony LG Webcam                                              | 1         | 2.22%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 2.22%   |
| Chicony Integrated Camera                                      | 1         | 2.22%   |
| Chicony HD Webcam                                              | 1         | 2.22%   |
| Chicony ACER FHD User Facing                                   | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.22%   |
| Bison Integrated Camera                                        | 1         | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 1         | 2.22%   |
| Apple FaceTime HD Camera                                       | 1         | 2.22%   |
| Acer HD Webcam                                                 | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 3         | 33.33%  |
| Validity Sensors           | 2         | 22.22%  |
| Elan Microelectronics      | 2         | 22.22%  |
| Upek                       | 1         | 11.11%  |
| Synaptics                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 3         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 11.11%  |
| Elan ELAN:Fingerprint                                  | 1         | 11.11%  |
| Elan ELAN:ARM-M4                                       | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 39        | 73.58%  |
| 1     | 11        | 20.75%  |
| 2     | 3         | 5.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 52.94%  |
| Multimedia controller | 2         | 11.76%  |
| Graphics card         | 2         | 11.76%  |
| Storage               | 1         | 5.88%   |
| Net/wireless          | 1         | 5.88%   |
| Chipcard              | 1         | 5.88%   |
| Camera                | 1         | 5.88%   |

