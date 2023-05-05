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

Total: 67

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.18.0-14parrot1-amd64 | 26        | 50.98%  |
| 6.0.0-2parrot1-amd64   | 20        | 39.22%  |
| 6.0.0-12parrot1-amd64  | 4         | 7.84%   |
| 5.18.0-1parrot1-amd64  | 1         | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.18.0  | 27        | 52.94%  |
| 6.0.0   | 24        | 47.06%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.18    | 27        | 52.94%  |
| 6.0     | 24        | 47.06%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 46        | 90.2%   |
| KDE5    | 4         | 7.84%   |
| Unknown | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 51        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 38        | 74.51%  |
| Unknown | 12        | 23.53%  |
| SDDM    | 1         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 26        | 50.98%  |
| fr_FR | 5         | 9.8%    |
| it_IT | 3         | 5.88%   |
| en_GB | 3         | 5.88%   |
| ru_RU | 2         | 3.92%   |
| es_ES | 2         | 3.92%   |
| pt_BR | 1         | 1.96%   |
| pl_PL | 1         | 1.96%   |
| es_PE | 1         | 1.96%   |
| es_MX | 1         | 1.96%   |
| es_AR | 1         | 1.96%   |
| en_ZW | 1         | 1.96%   |
| en_IN | 1         | 1.96%   |
| en_CA | 1         | 1.96%   |
| en_AU | 1         | 1.96%   |
| de_DE | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 27        | 52.94%  |
| BIOS | 24        | 47.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 51        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 29        | 56.86%  |
| Unknown | 13        | 25.49%  |
| MBR     | 9         | 17.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 92.16%  |
| Yes       | 4         | 7.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 64.71%  |
| Yes       | 18        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 11        | 21.57%  |
| Hewlett-Packard      | 6         | 11.76%  |
| Dell                 | 6         | 11.76%  |
| ASUSTek Computer     | 6         | 11.76%  |
| Acer                 | 5         | 9.8%    |
| MSI                  | 3         | 5.88%   |
| Toshiba              | 2         | 3.92%   |
| Quanta               | 2         | 3.92%   |
| HUAWEI               | 2         | 3.92%   |
| Standard             | 1         | 1.96%   |
| Irbis                | 1         | 1.96%   |
| Intel Client Systems | 1         | 1.96%   |
| Clevo                | 1         | 1.96%   |
| BANGHO               | 1         | 1.96%   |
| Apple                | 1         | 1.96%   |
| Alienware            | 1         | 1.96%   |
| Unknown              | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 3         | 5.88%   |
| Quanta TW9/SW9                             | 2         | 3.92%   |
| Toshiba Satellite C855D                    | 1         | 1.96%   |
| Toshiba Satellite C75D-B                   | 1         | 1.96%   |
| MSI Katana GF66 12UD                       | 1         | 1.96%   |
| MSI Katana GF66 12UC                       | 1         | 1.96%   |
| MSI GT60                                   | 1         | 1.96%   |
| Lenovo ThinkPad X230 Tablet 34383V4        | 1         | 1.96%   |
| Lenovo ThinkPad X230 Tablet 343727U        | 1         | 1.96%   |
| Lenovo ThinkPad X220 Tablet 42962WU        | 1         | 1.96%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1S05B00   | 1         | 1.96%   |
| Lenovo ThinkPad T460 20FMS2J300            | 1         | 1.96%   |
| Lenovo ThinkPad E570 20H5009MUS            | 1         | 1.96%   |
| Lenovo ThinkPad E15 Gen 3 20YGCTO1WW       | 1         | 1.96%   |
| Lenovo ThinkPad E15 Gen 3 20YG0041MX       | 1         | 1.96%   |
| Lenovo LEGIONC7 82EH                       | 1         | 1.96%   |
| Lenovo Legion 5 15ACH6H 82JU               | 1         | 1.96%   |
| Lenovo IdeaPad 3 15IGL05 81WQ              | 1         | 1.96%   |
| Irbis NB121                                | 1         | 1.96%   |
| Intel Client Systems LAPBC510              | 1         | 1.96%   |
| HUAWEI BOHB-WAX9                           | 1         | 1.96%   |
| HUAWEI BOD-WXX9                            | 1         | 1.96%   |
| HP Victus by Laptop 16-e0xxx               | 1         | 1.96%   |
| HP Victus by Laptop 16-d1xxx               | 1         | 1.96%   |
| HP Presario CQ58                           | 1         | 1.96%   |
| HP Laptop 15-dy1xxx                        | 1         | 1.96%   |
| HP Laptop 15-bs0xx                         | 1         | 1.96%   |
| Dell Latitude E6520                        | 1         | 1.96%   |
| Dell Latitude E5500                        | 1         | 1.96%   |
| Dell Latitude 3350                         | 1         | 1.96%   |
| Dell Inspiron 14 5410                      | 1         | 1.96%   |
| Dell Inspiron 13-7378                      | 1         | 1.96%   |
| Dell G3 3500                               | 1         | 1.96%   |
| Clevo W25xHPx                              | 1         | 1.96%   |
| BANGHO GAMER GM-X 15s                      | 1         | 1.96%   |
| ASUS ZenBook UX482EA_UX482EA               | 1         | 1.96%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X515UA_M515UA     | 1         | 1.96%   |
| ASUS ASUS TUF Gaming F15 FX506LH_FX506LH   | 1         | 1.96%   |
| ASUS ASUS TUF Gaming F15 FX506HCB_FX506HCB | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 8         | 15.69%  |
| Dell Latitude                 | 3         | 5.88%   |
| ASUS ASUS                     | 3         | 5.88%   |
| Unknown                       | 3         | 5.88%   |
| Toshiba Satellite             | 2         | 3.92%   |
| Quanta TW9                    | 2         | 3.92%   |
| MSI Katana                    | 2         | 3.92%   |
| HP Victus                     | 2         | 3.92%   |
| HP Laptop                     | 2         | 3.92%   |
| Dell Inspiron                 | 2         | 3.92%   |
| ASUS Zenbook                  | 2         | 3.92%   |
| Acer Aspire                   | 2         | 3.92%   |
| MSI GT60                      | 1         | 1.96%   |
| Lenovo LEGIONC7               | 1         | 1.96%   |
| Lenovo Legion                 | 1         | 1.96%   |
| Lenovo IdeaPad                | 1         | 1.96%   |
| Irbis NB121                   | 1         | 1.96%   |
| Intel Client Systems LAPBC510 | 1         | 1.96%   |
| HUAWEI BOHB-WAX9              | 1         | 1.96%   |
| HUAWEI BOD-WXX9               | 1         | 1.96%   |
| HP Presario                   | 1         | 1.96%   |
| Dell G3                       | 1         | 1.96%   |
| Clevo W25xHPx                 | 1         | 1.96%   |
| BANGHO GAMER                  | 1         | 1.96%   |
| ASUS VivoBook                 | 1         | 1.96%   |
| Apple MacBookPro9             | 1         | 1.96%   |
| Alienware m15                 | 1         | 1.96%   |
| Acer Swift                    | 1         | 1.96%   |
| Acer Predator                 | 1         | 1.96%   |
| Acer Nitro                    | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 21        | 41.18%  |
| 2022 | 5         | 9.8%    |
| 2012 | 4         | 7.84%   |
| 2020 | 3         | 5.88%   |
| 2019 | 3         | 5.88%   |
| 2016 | 3         | 5.88%   |
| 2011 | 3         | 5.88%   |
| 2017 | 2         | 3.92%   |
| 2013 | 2         | 3.92%   |
| 2010 | 2         | 3.92%   |
| 2018 | 1         | 1.96%   |
| 2014 | 1         | 1.96%   |
| 2008 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 51        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 51        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 15        | 29.41%  |
| 4.01-8.0   | 14        | 27.45%  |
| 8.01-16.0  | 14        | 27.45%  |
| 3.01-4.0   | 6         | 11.76%  |
| 32.01-64.0 | 2         | 3.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 18        | 34.62%  |
| 1.01-2.0 | 18        | 34.62%  |
| 3.01-4.0 | 11        | 21.15%  |
| 4.01-8.0 | 4         | 7.69%   |
| 0.51-1.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 76.47%  |
| 2      | 12        | 23.53%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 78.43%  |
| Yes       | 11        | 21.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 76.47%  |
| No        | 12        | 23.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 78.43%  |
| No        | 11        | 21.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 25.49%  |
| France       | 7         | 13.73%  |
| Russia       | 3         | 5.88%   |
| Italy        | 3         | 5.88%   |
| Spain        | 2         | 3.92%   |
| Kenya        | 2         | 3.92%   |
| Germany      | 2         | 3.92%   |
| Zimbabwe     | 1         | 1.96%   |
| UK           | 1         | 1.96%   |
| Sweden       | 1         | 1.96%   |
| Saudi Arabia | 1         | 1.96%   |
| Poland       | 1         | 1.96%   |
| Peru         | 1         | 1.96%   |
| Netherlands  | 1         | 1.96%   |
| Nepal        | 1         | 1.96%   |
| Namibia      | 1         | 1.96%   |
| Mongolia     | 1         | 1.96%   |
| Mexico       | 1         | 1.96%   |
| Luxembourg   | 1         | 1.96%   |
| Finland      | 1         | 1.96%   |
| Czechia      | 1         | 1.96%   |
| Canada       | 1         | 1.96%   |
| Brazil       | 1         | 1.96%   |
| Bangladesh   | 1         | 1.96%   |
| Australia    | 1         | 1.96%   |
| Argentina    | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Moscow              | 3         | 5.56%   |
| Lyon                | 2         | 3.7%    |
| Warsaw              | 1         | 1.85%   |
| Visalia             | 1         | 1.85%   |
| Veracruz            | 1         | 1.85%   |
| Västerås          | 1         | 1.85%   |
| Ulan Bator          | 1         | 1.85%   |
| Turin               | 1         | 1.85%   |
| Swakopmund          | 1         | 1.85%   |
| San Juan            | 1         | 1.85%   |
| San Antonio         | 1         | 1.85%   |
| Rongai              | 1         | 1.85%   |
| Rome                | 1         | 1.85%   |
| Prague              | 1         | 1.85%   |
| Parsons             | 1         | 1.85%   |
| Parnamirim          | 1         | 1.85%   |
| Paris               | 1         | 1.85%   |
| Orange Park         | 1         | 1.85%   |
| Naples              | 1         | 1.85%   |
| Nanyuki             | 1         | 1.85%   |
| Nairobi             | 1         | 1.85%   |
| Mesa                | 1         | 1.85%   |
| Melbourne           | 1         | 1.85%   |
| Marshall            | 1         | 1.85%   |
| Luxembourg          | 1         | 1.85%   |
| London              | 1         | 1.85%   |
| Lima                | 1         | 1.85%   |
| Liberty             | 1         | 1.85%   |
| Les Mureaux         | 1         | 1.85%   |
| La Garenne-Colombes | 1         | 1.85%   |
| Jeddah              | 1         | 1.85%   |
| Houston             | 1         | 1.85%   |
| Helsinki            | 1         | 1.85%   |
| Harare              | 1         | 1.85%   |
| Estepona            | 1         | 1.85%   |
| Edmonton            | 1         | 1.85%   |
| Dresden             | 1         | 1.85%   |
| Dhaka               | 1         | 1.85%   |
| Cologne             | 1         | 1.85%   |
| Coffs Harbour       | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 20.34%  |
| WDC                 | 8         | 9      | 13.56%  |
| Unknown             | 4         | 4      | 6.78%   |
| Toshiba             | 4         | 4      | 6.78%   |
| SK hynix            | 3         | 3      | 5.08%   |
| Sandisk             | 3         | 4      | 5.08%   |
| Micron Technology   | 3         | 3      | 5.08%   |
| Kingston            | 3         | 3      | 5.08%   |
| Intel               | 3         | 4      | 5.08%   |
| HGST                | 3         | 4      | 5.08%   |
| Unknown             | 3         | 3      | 5.08%   |
| YMTC                | 2         | 2      | 3.39%   |
| Hitachi             | 2         | 2      | 3.39%   |
| Seagate             | 1         | 1      | 1.69%   |
| Hikvision           | 1         | 1      | 1.69%   |
| Crucial             | 1         | 1      | 1.69%   |
| BW-PSSD1            | 1         | 1      | 1.69%   |
| BR                  | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown                                            | 3         | 4.69%   |
| YMTC PC005 256GB                                   | 2         | 3.13%   |
| Intel SSDPEKNU512GZ 512GB                          | 2         | 3.13%   |
| WDC WDS480G2G0C-00AJM0 480GB                       | 1         | 1.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 1.56%   |
| WDC WD5000BUCT-63PUZY0 500GB                       | 1         | 1.56%   |
| WDC WD3200BEVT-22A23T0 320GB                       | 1         | 1.56%   |
| WDC WD3200BEKT-75PVMT1 320GB                       | 1         | 1.56%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                 | 1         | 1.56%   |
| WDC PC SN530 SDBPNPZ-1T00-1114 1TB                 | 1         | 1.56%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB               | 1         | 1.56%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB               | 1         | 1.56%   |
| Unknown SD2GB                                      | 1         | 1.56%   |
| Unknown SD/MMC/MS PRO 249GB                        | 1         | 1.56%   |
| Unknown MMC Card  8GB                              | 1         | 1.56%   |
| Unknown MMC Card  64GB                             | 1         | 1.56%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.56%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 1.56%   |
| Toshiba KXG6AZNV256G 256GB                         | 1         | 1.56%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                  | 1         | 1.56%   |
| SK hynix PC801 NVMe 512GB                          | 1         | 1.56%   |
| SK hynix PC711 HFS512GDE9X073N 512GB               | 1         | 1.56%   |
| SK hynix HFM512GD3JX013N 512GB                     | 1         | 1.56%   |
| Seagate ST1000LM035-1RK172 970GB                   | 1         | 1.56%   |
| Sandisk WD Black SN850 1TB                         | 1         | 1.56%   |
| SanDisk SD8SBAT256G1122 256GB SSD                  | 1         | 1.56%   |
| SanDisk NVMe SSD Drive 512GB                       | 1         | 1.56%   |
| SanDisk NVMe SSD Drive 1TB                         | 1         | 1.56%   |
| Samsung SSD 980 PRO 1TB                            | 1         | 1.56%   |
| Samsung SSD 970 EVO Plus 500GB                     | 1         | 1.56%   |
| Samsung SSD 970 EVO Plus 2TB                       | 1         | 1.56%   |
| Samsung SSD 860 EVO M.2 500GB                      | 1         | 1.56%   |
| Samsung PM981a NVMe 1024GB                         | 1         | 1.56%   |
| Samsung NVMe SSD Drive 512GB                       | 1         | 1.56%   |
| Samsung NVMe SSD Drive 1024GB                      | 1         | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1         | 1.56%   |
| Samsung MZVLQ512HALU-00000 512GB                   | 1         | 1.56%   |
| Samsung MZVL2512HCJQ-00B00 512GB                   | 1         | 1.56%   |
| Samsung MZMPC128HBFU-000L1 128GB SSD               | 1         | 1.56%   |
| Samsung MZ7PD256HCGM-000H7 256GB SSD               | 1         | 1.56%   |

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
| Samsung Electronics | 4         | 4      | 40%     |
| Unknown             | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| Crucial             | 1         | 1      | 10%     |
| BR                  | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 30        | 38     | 52.63%  |
| HDD     | 13        | 14     | 22.81%  |
| SSD     | 10        | 10     | 17.54%  |
| MMC     | 3         | 4      | 5.26%   |
| Unknown | 1         | 1      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 38     | 52.63%  |
| SATA | 22        | 23     | 38.6%   |
| MMC  | 3         | 4      | 5.26%   |
| SAS  | 2         | 2      | 3.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 18     | 72.73%  |
| 0.51-1.0   | 6         | 6      | 27.27%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 21.57%  |
| 501-1000   | 11        | 21.57%  |
| Unknown    | 11        | 21.57%  |
| 101-250    | 7         | 13.73%  |
| 1001-2000  | 5         | 9.8%    |
| 51-100     | 4         | 7.84%   |
| 21-50      | 1         | 1.96%   |
| 1-20       | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 22        | 42.31%  |
| Unknown  | 11        | 21.15%  |
| 51-100   | 8         | 15.38%  |
| 101-250  | 7         | 13.46%  |
| 251-500  | 2         | 3.85%   |
| 501-1000 | 1         | 1.92%   |
| 0        | 1         | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 12.5%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 12.5%   |
| SanDisk SD8SBAT256G1122 256GB SSD | 1         | 1      | 12.5%   |
| Hitachi HTS723216L9SA60 160GB     | 1         | 1      | 12.5%   |
| HGST HTS725032A7E630 320GB        | 1         | 1      | 12.5%   |
| HGST HTS541010A9E680 1TB          | 1         | 1      | 12.5%   |
| Crucial CT525MX300SSD1 528GB      | 1         | 1      | 12.5%   |
| Unknown                           | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Toshiba | 1         | 1      | 12.5%   |
| SanDisk | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |
| Crucial | 1         | 1      | 12.5%   |
| Unknown | 1         | 1      | 12.5%   |

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
| HDD  | 5         | 5      | 62.5%   |
| SSD  | 3         | 3      | 37.5%   |

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
| Works    | 29        | 35     | 51.79%  |
| Detected | 19        | 24     | 33.93%  |
| Malfunc  | 8         | 8      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 38        | 53.52%  |
| Samsung Electronics          | 7         | 9.86%   |
| SanDisk                      | 6         | 8.45%   |
| AMD                          | 5         | 7.04%   |
| SK hynix                     | 3         | 4.23%   |
| Micron Technology            | 3         | 4.23%   |
| Kingston Technology Company  | 3         | 4.23%   |
| Yangtze Memory Technologies  | 2         | 2.82%   |
| Toshiba America Info Systems | 1         | 1.41%   |
| Silicon Motion               | 1         | 1.41%   |
| KIOXIA                       | 1         | 1.41%   |
| ADATA Technology             | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                                    | 10        | 12.66%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 6.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 6.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 5.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 3.8%    |
| Micron NVMe Storage Controller                                                         | 3         | 3.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 3.8%    |
| Intel Alder Lake-P SATA AHCI Controller                                                | 3         | 3.8%    |
| Yangtze Memory Non-Volatile memory controller                                          | 2         | 2.53%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 2         | 2.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 2.53%   |
| SanDisk NVMe Controller                                                                | 2         | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.53%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.53%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 2.53%   |
| Intel Non-Volatile memory controller                                                   | 2         | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 2.53%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 1.27%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                                       | 1         | 1.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 1.27%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.27%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 1.27%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.27%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.27%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.27%   |
| Kingston Company NVMe Controller                                                       | 1         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.27%   |
| Intel NVMe Controller                                                                  | 1         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.27%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                            | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 42.11%  |
| NVMe | 30        | 39.47%  |
| RAID | 12        | 15.79%  |
| IDE  | 2         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 84.31%  |
| AMD    | 8         | 15.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i5-12500H           | 3         | 5.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 5.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 3.92%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 3.92%   |
| Intel 12th Gen Core i7-12700H           | 2         | 3.92%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz | 2         | 3.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.96%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.96%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 1.96%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 1         | 1.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.96%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.96%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 1         | 1.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 1.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.96%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.96%   |
| Intel Core i5 CPU M 430 @ 2.27GHz       | 1         | 1.96%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.96%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 1         | 1.96%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 1         | 1.96%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 1         | 1.96%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 1         | 1.96%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 1.96%   |
| Intel Celeron CPU B820 @ 1.70GHz        | 1         | 1.96%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.96%   |
| Intel 12th Gen Core i5-1240P            | 1         | 1.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 1.96%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 1         | 1.96%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 1.96%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 1         | 1.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 1         | 1.96%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 1         | 1.96%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 1.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 16        | 31.37%  |
| Intel Core i7    | 9         | 17.65%  |
| Intel Core i5    | 8         | 15.69%  |
| Intel Core i3    | 5         | 9.8%    |
| Intel Celeron    | 4         | 7.84%   |
| AMD Ryzen 7      | 3         | 5.88%   |
| AMD Ryzen 5      | 2         | 3.92%   |
| AMD A6           | 2         | 3.92%   |
| Intel Core 2 Duo | 1         | 1.96%   |
| AMD Ryzen 3      | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 39.22%  |
| 4      | 12        | 23.53%  |
| 6      | 6         | 11.76%  |
| 12     | 5         | 9.8%    |
| 8      | 5         | 9.8%    |
| 14     | 2         | 3.92%   |
| 1      | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 72.55%  |
| 1      | 14        | 27.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 27.45%  |
| 0x906a3    | 7         | 13.73%  |
| 0xa0652    | 3         | 5.88%   |
| 0x706a8    | 3         | 5.88%   |
| 0x406e3    | 3         | 5.88%   |
| 0x306a9    | 3         | 5.88%   |
| 0x206a7    | 3         | 5.88%   |
| 0x08608103 | 3         | 5.88%   |
| 0x806c1    | 2         | 3.92%   |
| 0xa0660    | 1         | 1.96%   |
| 0x806ec    | 1         | 1.96%   |
| 0x806e9    | 1         | 1.96%   |
| 0x806d1    | 1         | 1.96%   |
| 0x706e5    | 1         | 1.96%   |
| 0x6fd      | 1         | 1.96%   |
| 0x40651    | 1         | 1.96%   |
| 0x106e5    | 1         | 1.96%   |
| 0x0a50000c | 1         | 1.96%   |
| 0x07030105 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 7         | 13.73%  |
| TigerLake        | 6         | 11.76%  |
| Alderlake Hybrid | 6         | 11.76%  |
| SandyBridge      | 4         | 7.84%   |
| IvyBridge        | 4         | 7.84%   |
| CometLake        | 4         | 7.84%   |
| Skylake          | 3         | 5.88%   |
| KabyLake         | 3         | 5.88%   |
| Goldmont plus    | 3         | 5.88%   |
| Zen 3            | 2         | 3.92%   |
| Zen 2            | 1         | 1.96%   |
| Westmere         | 1         | 1.96%   |
| Puma             | 1         | 1.96%   |
| Piledriver       | 1         | 1.96%   |
| Nehalem          | 1         | 1.96%   |
| IceLake          | 1         | 1.96%   |
| Haswell          | 1         | 1.96%   |
| Core             | 1         | 1.96%   |
| Broadwell        | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 59.15%  |
| Nvidia | 21        | 29.58%  |
| AMD    | 8         | 11.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                         | 7         | 9.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 7.04%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 4         | 5.63%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 5.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 5.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 4.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 4.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 4.23%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 4.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 4.23%   |
| AMD Lucienne                                                              | 3         | 4.23%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.41%   |
| Nvidia TU117M                                                             | 1         | 1.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.41%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                  | 1         | 1.41%   |
| Nvidia GT215M [GeForce GT 335M]                                           | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.41%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 1.41%   |
| Nvidia GF114M [GeForce GTX 670M]                                          | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 1.41%   |
| Nvidia GF106M [GeForce GT 445M]                                           | 1         | 1.41%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 1.41%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.41%   |
| Intel HD Graphics 630                                                     | 1         | 1.41%   |
| Intel HD Graphics 620                                                     | 1         | 1.41%   |
| Intel HD Graphics 5500                                                    | 1         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.41%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.41%   |
| AMD Trinity 2 [Radeon HD 7520G]                                           | 1         | 1.41%   |
| AMD Renoir                                                                | 1         | 1.41%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 49.02%  |
| Intel + Nvidia | 17        | 33.33%  |
| 1 x AMD        | 5         | 9.8%    |
| AMD + Nvidia   | 3         | 5.88%   |
| 1 x Nvidia     | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 40        | 78.43%  |
| Proprietary | 11        | 21.57%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 78.43%  |
| 0.51-1.0   | 5         | 9.8%    |
| 3.01-4.0   | 2         | 3.92%   |
| 0.01-0.5   | 2         | 3.92%   |
| 2.01-3.0   | 1         | 1.96%   |
| 1.01-2.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 15        | 24.19%  |
| AU Optronics            | 13        | 20.97%  |
| LG Display              | 9         | 14.52%  |
| Samsung Electronics     | 6         | 9.68%   |
| Chimei Innolux          | 6         | 9.68%   |
| ___                     | 1         | 1.61%   |
| ViewSonic               | 1         | 1.61%   |
| Unknown                 | 1         | 1.61%   |
| STD                     | 1         | 1.61%   |
| Sharp                   | 1         | 1.61%   |
| Planar                  | 1         | 1.61%   |
| PANDA                   | 1         | 1.61%   |
| LG Philips              | 1         | 1.61%   |
| Hewlett-Packard         | 1         | 1.61%   |
| Eizo                    | 1         | 1.61%   |
| Dell                    | 1         | 1.61%   |
| Chi Mei Optoelectronics | 1         | 1.61%   |
| Apple                   | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 4.84%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 3         | 4.84%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 3.23%   |
| ___ LCD TV ___9000 1360x768                                              | 1         | 1.61%   |
| ViewSonic VA2718-FHD VSCD839 1920x1080 598x336mm 27.0-inch               | 1         | 1.61%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 1.61%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                        | 1         | 1.61%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 1         | 1.61%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 1         | 1.61%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch        | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 1         | 1.61%   |
| Planar PNR PL1910MW PNR1910 1440x900 410x257mm 19.1-inch                 | 1         | 1.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.61%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD06A5 1920x1080 344x194mm 15.5-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD050B 1920x1080 309x174mm 14.0-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.61%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch               | 1         | 1.61%   |
| Eizo EV2450 ENC2530 1920x1080 528x297mm 23.9-inch                        | 1         | 1.61%   |
| Dell E2416H DELA0CA 1920x1080 531x299mm 24.0-inch                        | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1591 1366x768 344x193mm 15.5-inch | 1         | 1.61%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                    | 1         | 1.61%   |
| BOE LCD Monitor BOE09F1 1920x1080 355x200mm 16.0-inch                    | 1         | 1.61%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                    | 1         | 1.61%   |
| BOE LCD Monitor BOE0990 2560x1600 344x215mm 16.0-inch                    | 1         | 1.61%   |
| BOE LCD Monitor BOE0979 1366x768 256x144mm 11.6-inch                     | 1         | 1.61%   |
| BOE LCD Monitor BOE0921 1920x515                                         | 1         | 1.61%   |
| BOE LCD Monitor BOE090F 1920x1080 344x194mm 15.5-inch                    | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 31        | 53.45%  |
| 1366x768 (WXGA)  | 14        | 24.14%  |
| 1600x900 (HD+)   | 3         | 5.17%   |
| 1440x900 (WXGA+) | 2         | 3.45%   |
| 1280x800 (WXGA)  | 2         | 3.45%   |
| 2880x1800        | 1         | 1.72%   |
| 2560x1600        | 1         | 1.72%   |
| 2240x1400        | 1         | 1.72%   |
| 1920x515         | 1         | 1.72%   |
| 1360x768         | 1         | 1.72%   |
| 1024x768 (XGA)   | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 48.39%  |
| 14      | 7         | 11.29%  |
| 17      | 4         | 6.45%   |
| 27      | 3         | 4.84%   |
| 16      | 3         | 4.84%   |
| 13      | 3         | 4.84%   |
| 12      | 3         | 4.84%   |
| 24      | 2         | 3.23%   |
| 11      | 2         | 3.23%   |
| Unknown | 2         | 3.23%   |
| 72      | 1         | 1.61%   |
| 31      | 1         | 1.61%   |
| 19      | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 61.29%  |
| 201-300     | 8         | 12.9%   |
| 351-400     | 6         | 9.68%   |
| 501-600     | 5         | 8.06%   |
| Unknown     | 2         | 3.23%   |
| 601-700     | 1         | 1.61%   |
| 401-500     | 1         | 1.61%   |
| 1501-2000   | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 85.19%  |
| 16/10 | 6         | 11.11%  |
| 4/3   | 1         | 1.85%   |
| 3.73  | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 51.61%  |
| 81-90          | 8         | 12.9%   |
| 121-130        | 4         | 6.45%   |
| 61-70          | 3         | 4.84%   |
| 301-350        | 3         | 4.84%   |
| 71-80          | 2         | 3.23%   |
| 51-60          | 2         | 3.23%   |
| 201-250        | 2         | 3.23%   |
| Unknown        | 2         | 3.23%   |
| More than 1000 | 1         | 1.61%   |
| 351-500        | 1         | 1.61%   |
| 151-200        | 1         | 1.61%   |
| 111-120        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 55.74%  |
| 101-120       | 12        | 19.67%  |
| 51-100        | 8         | 13.11%  |
| 161-240       | 3         | 4.92%   |
| Unknown       | 2         | 3.28%   |
| More than 240 | 1         | 1.64%   |
| 1-50          | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 42        | 80.77%  |
| 2     | 8         | 15.38%  |
| 3     | 2         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 35        | 40.7%   |
| Realtek Semiconductor                  | 30        | 34.88%  |
| Qualcomm Atheros                       | 7         | 8.14%   |
| MediaTek                               | 4         | 4.65%   |
| TP-Link                                | 2         | 2.33%   |
| Xiaomi                                 | 1         | 1.16%   |
| Sony Ericsson Mobile Communications AB | 1         | 1.16%   |
| Samsung Electronics                    | 1         | 1.16%   |
| JMicron Technology                     | 1         | 1.16%   |
| D-Link                                 | 1         | 1.16%   |
| Broadcom Limited                       | 1         | 1.16%   |
| Broadcom                               | 1         | 1.16%   |
| Belkin Components                      | 1         | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 16.33%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 6.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 4.08%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 3.06%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 3.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.04%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.02%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.02%   |
| TP-Link 802.11ac NIC                                              | 1         | 1.02%   |
| Sony Ericsson Mobile AB G8341                                     | 1         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.02%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.02%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.02%   |
| Realtek PCIe GbE Family Controller                                | 1         | 1.02%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.02%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.02%   |
| Realtek 802.11ac NIC                                              | 1         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.02%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.02%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.02%   |
| Intel Wireless 8260                                               | 1         | 1.02%   |
| Intel Wireless 7265                                               | 1         | 1.02%   |
| Intel Wireless 7260                                               | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 62.5%   |
| Realtek Semiconductor | 8         | 14.29%  |
| Qualcomm Atheros      | 4         | 7.14%   |
| MediaTek              | 4         | 7.14%   |
| TP-Link               | 2         | 3.57%   |
| D-Link                | 1         | 1.79%   |
| Broadcom              | 1         | 1.79%   |
| Belkin Components     | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                     | Notebooks | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                                          | 6         | 10.71%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                             | 4         | 7.14%   |
| Intel Wi-Fi 6 AX201                                                                       | 4         | 7.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                              | 4         | 7.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                  | 3         | 5.36%   |
| Intel Wi-Fi 6 AX200                                                                       | 3         | 5.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                          | 2         | 3.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                                            | 2         | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                          | 2         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                         | 2         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                                            | 2         | 3.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                | 1         | 1.79%   |
| TP-Link 802.11ac NIC                                                                      | 1         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                  | 1         | 1.79%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                       | 1         | 1.79%   |
| Realtek RTL8723DE Wireless Network Adapter                                                | 1         | 1.79%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                | 1         | 1.79%   |
| Realtek 802.11ac NIC                                                                      | 1         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                | 1         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                | 1         | 1.79%   |
| Intel Wireless 8265 / 8275                                                                | 1         | 1.79%   |
| Intel Wireless 8260                                                                       | 1         | 1.79%   |
| Intel Wireless 7265                                                                       | 1         | 1.79%   |
| Intel Wireless 7260                                                                       | 1         | 1.79%   |
| Intel WiFi Link 5100                                                                      | 1         | 1.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                                           | 1         | 1.79%   |
| Intel Centrino Wireless-N 2230                                                            | 1         | 1.79%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                             | 1         | 1.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                              | 1         | 1.79%   |
| Intel Centrino Advanced-N 6200                                                            | 1         | 1.79%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                      | 1         | 1.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                                            | 1         | 1.79%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU] | 1         | 1.79%   |

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
| WiFi     | 51        | 56.67%  |
| Ethernet | 39        | 43.33%  |

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
| 2     | 37        | 71.15%  |
| 1     | 12        | 23.08%  |
| 0     | 2         | 3.85%   |
| 3     | 1         | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 69.23%  |
| Yes  | 16        | 30.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 57.5%   |
| IMC Networks                    | 5         | 12.5%   |
| Realtek Semiconductor           | 4         | 10%     |
| Qualcomm Atheros Communications | 3         | 7.5%    |
| TP-Link                         | 1         | 2.5%    |
| Lite-On Technology              | 1         | 2.5%    |
| Dell                            | 1         | 2.5%    |
| Broadcom                        | 1         | 2.5%    |
| Apple                           | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 11        | 27.5%   |
| Realtek Bluetooth Radio                        | 3         | 7.5%    |
| Intel Bluetooth wireless interface             | 3         | 7.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 7.5%    |
| IMC Networks Wireless_Device                   | 3         | 7.5%    |
| Qualcomm Atheros Bluetooth                     | 2         | 5%      |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 5%      |
| Intel Bluetooth Device                         | 2         | 5%      |
| Intel AX200 Bluetooth                          | 2         | 5%      |
| TP-Link UB500 Adapter                          | 1         | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 2.5%    |
| Lite-On Wireless_Device                        | 1         | 2.5%    |
| IMC Networks Bluetooth Radio                   | 1         | 2.5%    |
| IMC Networks Bluetooth Device                  | 1         | 2.5%    |
| Dell DW375 Bluetooth Module                    | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 2.5%    |
| Apple Bluetooth USB Host Controller            | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 62.32%  |
| Nvidia | 17        | 24.64%  |
| AMD    | 8         | 11.59%  |
| JMTek  | 1         | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 8.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 7.69%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 6.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 5.13%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 3.85%   |
| Nvidia Audio device                                                        | 3         | 3.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 3.85%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 3.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.56%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.28%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.28%   |
| JMTek USB Speaker                                                          | 1         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.28%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.28%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.28%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 26.67%  |
| Micron Technology   | 9         | 20%     |
| SK hynix            | 8         | 17.78%  |
| Crucial             | 4         | 8.89%   |
| Unknown (ABCD)      | 2         | 4.44%   |
| Nanya Technology    | 2         | 4.44%   |
| A-DATA Technology   | 2         | 4.44%   |
| Transcend           | 1         | 2.22%   |
| Timetec             | 1         | 2.22%   |
| PNY                 | 1         | 2.22%   |
| Kingston            | 1         | 2.22%   |
| Elpida              | 1         | 2.22%   |
| ChangXin Memory     | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 4.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 4.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 4.35%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 4.35%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM 1334MT/s                   | 1         | 2.17%   |
| Timetec RAM SD3-1333 8192MB SODIMM DDR3 1333MT/s                 | 1         | 2.17%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 2.17%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.17%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.17%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 2.17%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.17%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 2.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.17%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.17%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 2.17%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 1         | 2.17%   |
| PNY RAM Module 8GB SODIMM DDR3 1600MT/s                          | 1         | 2.17%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 2.17%   |
| Nanya RAM M2S4G64CB8HG5N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 2.17%   |
| Micron RAM CT102464BF186D.C16 8192MB SODIMM DDR3 1867MT/s        | 1         | 2.17%   |
| Micron RAM 8ATF1G64HZ-2G3H1R 8GB SODIMM DDR4 2400MT/s            | 1         | 2.17%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.17%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 2.17%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.17%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 1         | 2.17%   |
| Micron RAM 16HTF25664HY-800E1 2GB SODIMM DDR2 975MT/s            | 1         | 2.17%   |
| Kingston RAM SNY1333S9-2G-ELFEU 2GB SODIMM DDR3 1333MT/s         | 1         | 2.17%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 2.17%   |
| Crucial RAM CT8G4SFRA32A.M4FE 8GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| Crucial RAM CT8G4SFRA32A.C8FR 8GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 1         | 2.17%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 1         | 2.17%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 1         | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 46.15%  |
| DDR3   | 11        | 28.21%  |
| LPDDR4 | 4         | 10.26%  |
| LPDDR5 | 2         | 5.13%   |
| DDR5   | 2         | 5.13%   |
| LPDDR3 | 1         | 2.56%   |
| DDR2   | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 84.62%  |
| Row Of Chips | 6         | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 64.1%   |
| 4096  | 6         | 15.38%  |
| 2048  | 4         | 10.26%  |
| 16384 | 3         | 7.69%   |
| 1024  | 1         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 27.5%   |
| 1600  | 7         | 17.5%   |
| 2667  | 5         | 12.5%   |
| 2400  | 4         | 10%     |
| 6400  | 2         | 5%      |
| 4800  | 2         | 5%      |
| 1334  | 2         | 5%      |
| 1333  | 2         | 5%      |
| 4267  | 1         | 2.5%    |
| 3733  | 1         | 2.5%    |
| 2133  | 1         | 2.5%    |
| 1867  | 1         | 2.5%    |
| 975   | 1         | 2.5%    |

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
| Chicony Electronics                    | 9         | 20.45%  |
| IMC Networks                           | 7         | 15.91%  |
| Quanta                                 | 4         | 9.09%   |
| Sonix Technology                       | 3         | 6.82%   |
| Syntek                                 | 2         | 4.55%   |
| Suyin                                  | 2         | 4.55%   |
| Sunplus Innovation Technology          | 2         | 4.55%   |
| Realtek Semiconductor                  | 2         | 4.55%   |
| Microdia                               | 2         | 4.55%   |
| Apple                                  | 2         | 4.55%   |
| USB Camera CS                          | 1         | 2.27%   |
| Samsung Electronics                    | 1         | 2.27%   |
| Luxvisions Innotech Limited            | 1         | 2.27%   |
| Logitech                               | 1         | 2.27%   |
| Importek                               | 1         | 2.27%   |
| icSpring                               | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |
| Bison Electronics                      | 1         | 2.27%   |
| Acer                                   | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                       | 2         | 4.55%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 4.55%   |
| Realtek Integrated_Webcam_HD                                   | 2         | 4.55%   |
| Quanta HD User Facing                                          | 2         | 4.55%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 4.55%   |
| IMC Networks Integrated Camera                                 | 2         | 4.55%   |
| Chicony HD User Facing                                         | 2         | 4.55%   |
| USB Camera CS USB Camera CS                                    | 1         | 2.27%   |
| Suyin LG Webcam                                                | 1         | 2.27%   |
| Suyin HP Webcam-50                                             | 1         | 2.27%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 2.27%   |
| Sunplus Laptop Integrated Webcam HD                            | 1         | 2.27%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 1         | 2.27%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2.27%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.27%   |
| Quanta HD Camera                                               | 1         | 2.27%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.27%   |
| Logitech BRIO Ultra HD Webcam                                  | 1         | 2.27%   |
| Importek TOSHIBA Web Camera                                    | 1         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 2.27%   |
| IMC Networks HP TrueVision HD Camera                           | 1         | 2.27%   |
| IMC Networks HD Camera                                         | 1         | 2.27%   |
| icSpring camera                                                | 1         | 2.27%   |
| Chicony USB2.0 Camera                                          | 1         | 2.27%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 2.27%   |
| Chicony LG Webcam                                              | 1         | 2.27%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 2.27%   |
| Chicony Integrated Camera                                      | 1         | 2.27%   |
| Chicony HD Webcam                                              | 1         | 2.27%   |
| Chicony ACER FHD User Facing                                   | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.27%   |
| Bison HD Webcam                                                | 1         | 2.27%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 1         | 2.27%   |
| Apple FaceTime HD Camera                                       | 1         | 2.27%   |
| Acer Integrated Camera                                         | 1         | 2.27%   |

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
| 0     | 37        | 71.15%  |
| 1     | 12        | 23.08%  |
| 2     | 3         | 5.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 50%     |
| Graphics card         | 3         | 16.67%  |
| Multimedia controller | 2         | 11.11%  |
| Storage               | 1         | 5.56%   |
| Net/wireless          | 1         | 5.56%   |
| Chipcard              | 1         | 5.56%   |
| Camera                | 1         | 5.56%   |

