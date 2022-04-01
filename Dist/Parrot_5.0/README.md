Parrot 5.0 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_5.0/Desktop/README.md) and [notebooks](/Dist/Parrot_5.0/Notebook/README.md).

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

Total: 70

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| HP            | Pavilion g7                 | Notebook    | [d27bb0d31e](https://linux-hardware.org/?probe=d27bb0d31e) | Oct 31, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| HP            | Pavilion g7                 | Notebook    | [b386e97faa](https://linux-hardware.org/?probe=b386e97faa) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64  | 30        | 58.82%  |
| 5.15.0-15parrot1-amd64 | 7         | 13.73%  |
| 5.14.0-2parrot1-amd64  | 7         | 13.73%  |
| 5.16.0-12parrot1-amd64 | 6         | 11.76%  |
| 5.15.0-5parrot1-amd64  | 1         | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 35        | 71.43%  |
| 5.15.0  | 8         | 16.33%  |
| 5.16.0  | 6         | 12.24%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 35        | 71.43%  |
| 5.15    | 8         | 16.33%  |
| 5.16    | 6         | 12.24%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 48        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 28        | 58.33%  |
| KDE5    | 14        | 29.17%  |
| XFCE    | 2         | 4.17%   |
| Unknown | 2         | 4.17%   |
| KDE     | 1         | 2.08%   |
| GNOME   | 1         | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 46        | 95.83%  |
| Wayland | 2         | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 24        | 50%     |
| Unknown | 23        | 47.92%  |
| GDM     | 1         | 2.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 24        | 50%     |
| en_GB | 5         | 10.42%  |
| en_IN | 4         | 8.33%   |
| ru_RU | 3         | 6.25%   |
| es_ES | 2         | 4.17%   |
| cs_CZ | 2         | 4.17%   |
| pt_BR | 1         | 2.08%   |
| pl_PL | 1         | 2.08%   |
| fr_FR | 1         | 2.08%   |
| es_MX | 1         | 2.08%   |
| en_ZA | 1         | 2.08%   |
| en_DK | 1         | 2.08%   |
| en_AU | 1         | 2.08%   |
| de_DE | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 33        | 68.75%  |
| EFI  | 15        | 31.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 41        | 85.42%  |
| Ext4    | 5         | 10.42%  |
| Overlay | 2         | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 47.92%  |
| GPT     | 16        | 33.33%  |
| MBR     | 9         | 18.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 89.58%  |
| Yes       | 5         | 10.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 68.75%  |
| Yes       | 15        | 31.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 8         | 16.67%  |
| Lenovo              | 7         | 14.58%  |
| Hewlett-Packard     | 7         | 14.58%  |
| ASUSTek Computer    | 6         | 12.5%   |
| Acer                | 4         | 8.33%   |
| MSI                 | 2         | 4.17%   |
| Apple               | 2         | 4.17%   |
| Toshiba             | 1         | 2.08%   |
| SLIMBOOK            | 1         | 2.08%   |
| Samsung Electronics | 1         | 2.08%   |
| Microsoft           | 1         | 2.08%   |
| Metabox             | 1         | 2.08%   |
| Jumper              | 1         | 2.08%   |
| Gigabyte Technology | 1         | 2.08%   |
| ECS                 | 1         | 2.08%   |
| Daewoo Lucoms       | 1         | 2.08%   |
| Chuwi               | 1         | 2.08%   |
| ASRock              | 1         | 2.08%   |
| Alienware           | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                           | 2         | 4.17%   |
| HP Notebook                                 | 2         | 4.17%   |
| Toshiba Satellite C75D-B                    | 1         | 2.08%   |
| SLIMBOOK ONE-AMD-M4                         | 1         | 2.08%   |
| Samsung 550P5C/550P7C                       | 1         | 2.08%   |
| Microsoft Surface Book                      | 1         | 2.08%   |
| Metabox Edge-Pro NS50MU                     | 1         | 2.08%   |
| Lenovo Yoga C930-13IKB 81C4                 | 1         | 2.08%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 2.08%   |
| Lenovo ThinkPad T480 20L6SCYP00             | 1         | 2.08%   |
| Lenovo ThinkPad E14 20RA0016GE              | 1         | 2.08%   |
| Lenovo IdeaPad Y580                         | 1         | 2.08%   |
| Lenovo H530 10130                           | 1         | 2.08%   |
| Lenovo B50-80 80EW                          | 1         | 2.08%   |
| Jumper EZbook                               | 1         | 2.08%   |
| HP ProDesk 600 G1 SFF                       | 1         | 2.08%   |
| HP ProBook 4535s                            | 1         | 2.08%   |
| HP Pavilion g7                              | 1         | 2.08%   |
| HP Laptop 15q-dy0xxx                        | 1         | 2.08%   |
| HP EliteBook 840 G3                         | 1         | 2.08%   |
| Gigabyte A320M-S2H                          | 1         | 2.08%   |
| ECS GV460AA-ABA a6217c                      | 1         | 2.08%   |
| Dell OptiPlex 7010                          | 1         | 2.08%   |
| Dell OptiPlex 3020                          | 1         | 2.08%   |
| Dell Latitude XT2                           | 1         | 2.08%   |
| Dell Latitude E7450                         | 1         | 2.08%   |
| Dell Latitude E6410                         | 1         | 2.08%   |
| Dell Latitude 7480                          | 1         | 2.08%   |
| Dell Inspiron N5110                         | 1         | 2.08%   |
| Dell Inspiron 5570                          | 1         | 2.08%   |
| Daewoo Lucoms OEM                           | 1         | 2.08%   |
| Chuwi GemiBook                              | 1         | 2.08%   |
| ASUS X75VC                                  | 1         | 2.08%   |
| ASUS X540SAA                                | 1         | 2.08%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR        | 1         | 2.08%   |
| ASUS ROG CROSSHAIR VIII HERO                | 1         | 2.08%   |
| ASUS H170M-E D3                             | 1         | 2.08%   |
| ASUS Basic 3221BM                           | 1         | 2.08%   |
| ASRock Z87M Extreme4                        | 1         | 2.08%   |
| Apple MacBookAir3,1                         | 1         | 2.08%   |
| Apple MacBook7,1                            | 1         | 2.08%   |
| Alienware M14xR1                            | 1         | 2.08%   |
| Acer TravelMate 5720                        | 1         | 2.08%   |
| Acer Nitro AN517-41                         | 1         | 2.08%   |
| Acer Nitro AN515-54                         | 1         | 2.08%   |
| Acer Aspire A315-21                         | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Latitude       | 4         | 8.33%   |
| Lenovo ThinkPad     | 3         | 6.25%   |
| MSI Modern          | 2         | 4.17%   |
| HP Notebook         | 2         | 4.17%   |
| Dell OptiPlex       | 2         | 4.17%   |
| Dell Inspiron       | 2         | 4.17%   |
| Acer Nitro          | 2         | 4.17%   |
| Toshiba Satellite   | 1         | 2.08%   |
| SLIMBOOK ONE-AMD-M4 | 1         | 2.08%   |
| Samsung 550P5C      | 1         | 2.08%   |
| Microsoft Surface   | 1         | 2.08%   |
| Metabox Edge-Pro    | 1         | 2.08%   |
| Lenovo Yoga         | 1         | 2.08%   |
| Lenovo IdeaPad      | 1         | 2.08%   |
| Lenovo H530         | 1         | 2.08%   |
| Lenovo B50-80       | 1         | 2.08%   |
| Jumper EZbook       | 1         | 2.08%   |
| HP ProDesk          | 1         | 2.08%   |
| HP ProBook          | 1         | 2.08%   |
| HP Pavilion         | 1         | 2.08%   |
| HP Laptop           | 1         | 2.08%   |
| HP EliteBook        | 1         | 2.08%   |
| Gigabyte A320M-S2H  | 1         | 2.08%   |
| ECS GV460AA-ABA     | 1         | 2.08%   |
| Daewoo Lucoms OEM   | 1         | 2.08%   |
| Chuwi GemiBook      | 1         | 2.08%   |
| ASUS X75VC          | 1         | 2.08%   |
| ASUS X540SAA        | 1         | 2.08%   |
| ASUS VivoBook       | 1         | 2.08%   |
| ASUS ROG            | 1         | 2.08%   |
| ASUS H170M-E        | 1         | 2.08%   |
| ASUS Basic          | 1         | 2.08%   |
| ASRock Z87M         | 1         | 2.08%   |
| Apple MacBookAir3   | 1         | 2.08%   |
| Apple MacBook7      | 1         | 2.08%   |
| Alienware M14xR1    | 1         | 2.08%   |
| Acer TravelMate     | 1         | 2.08%   |
| Acer Aspire         | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 8         | 16.67%  |
| 2013 | 5         | 10.42%  |
| 2018 | 4         | 8.33%   |
| 2017 | 4         | 8.33%   |
| 2016 | 4         | 8.33%   |
| 2011 | 4         | 8.33%   |
| 2010 | 4         | 8.33%   |
| 2015 | 3         | 6.25%   |
| 2012 | 3         | 6.25%   |
| 2020 | 2         | 4.17%   |
| 2019 | 2         | 4.17%   |
| 2014 | 2         | 4.17%   |
| 2007 | 2         | 4.17%   |
| 2009 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 34        | 70.83%  |
| Desktop     | 12        | 25%     |
| Tablet      | 1         | 2.08%   |
| Convertible | 1         | 2.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 48        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 48        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 26.53%  |
| 8.01-16.0   | 12        | 24.49%  |
| 3.01-4.0    | 10        | 20.41%  |
| 32.01-64.0  | 7         | 14.29%  |
| 16.01-24.0  | 4         | 8.16%   |
| 64.01-256.0 | 2         | 4.08%   |
| 1.01-2.0    | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 19        | 38.78%  |
| 1.01-2.0   | 15        | 30.61%  |
| 4.01-8.0   | 6         | 12.24%  |
| 3.01-4.0   | 4         | 8.16%   |
| 8.01-16.0  | 2         | 4.08%   |
| 0.51-1.0   | 2         | 4.08%   |
| 16.01-24.0 | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 58.33%  |
| 2      | 16        | 33.33%  |
| 3      | 2         | 4.17%   |
| 6      | 1         | 2.08%   |
| 5      | 1         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 68.75%  |
| Yes       | 15        | 31.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 85.42%  |
| No        | 7         | 14.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 93.75%  |
| No        | 3         | 6.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 68.75%  |
| No        | 15        | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 32.65%  |
| UK           | 4         | 8.16%   |
| India        | 4         | 8.16%   |
| Netherlands  | 3         | 6.12%   |
| Denmark      | 3         | 6.12%   |
| Spain        | 2         | 4.08%   |
| Russia       | 2         | 4.08%   |
| Morocco      | 2         | 4.08%   |
| Czechia      | 2         | 4.08%   |
| Austria      | 2         | 4.08%   |
| South Africa | 1         | 2.04%   |
| Romania      | 1         | 2.04%   |
| Mexico       | 1         | 2.04%   |
| Germany      | 1         | 2.04%   |
| Georgia      | 1         | 2.04%   |
| France       | 1         | 2.04%   |
| Brazil       | 1         | 2.04%   |
| Australia    | 1         | 2.04%   |
| Algeria      | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Vienna               | 2         | 4.08%   |
| Tangier              | 2         | 4.08%   |
| Camden               | 2         | 4.08%   |
| Amsterdam            | 2         | 4.08%   |
| Viby J               | 1         | 2.04%   |
| Vapi                 | 1         | 2.04%   |
| Uherské Hradiště  | 1         | 2.04%   |
| Ts'khinvali          | 1         | 2.04%   |
| St Petersburg        | 1         | 2.04%   |
| Spotsylvania         | 1         | 2.04%   |
| Skive                | 1         | 2.04%   |
| Seattle              | 1         | 2.04%   |
| Sao Paulo            | 1         | 2.04%   |
| Saint Clair          | 1         | 2.04%   |
| Ruskin               | 1         | 2.04%   |
| Pretoria             | 1         | 2.04%   |
| Prague               | 1         | 2.04%   |
| Pittsburgh           | 1         | 2.04%   |
| Phoenix              | 1         | 2.04%   |
| Orofino              | 1         | 2.04%   |
| Newark               | 1         | 2.04%   |
| Mt. Pleasant         | 1         | 2.04%   |
| Mostoles             | 1         | 2.04%   |
| Milton               | 1         | 2.04%   |
| Melbourne            | 1         | 2.04%   |
| MazatlÃ¡n          | 1         | 2.04%   |
| Mangalagiri          | 1         | 2.04%   |
| Los Angeles          | 1         | 2.04%   |
| Krasnogorsk          | 1         | 2.04%   |
| Islington            | 1         | 2.04%   |
| Iasi                 | 1         | 2.04%   |
| Houston              | 1         | 2.04%   |
| Grand Junction       | 1         | 2.04%   |
| Dillon               | 1         | 2.04%   |
| Copenhagen           | 1         | 2.04%   |
| City of Saint Peters | 1         | 2.04%   |
| Cannes               | 1         | 2.04%   |
| Bussum               | 1         | 2.04%   |
| Bristol              | 1         | 2.04%   |
| Birmingham           | 1         | 2.04%   |
| Berlin               | 1         | 2.04%   |
| Beri Khas            | 1         | 2.04%   |
| Bengaluru            | 1         | 2.04%   |
| Algiers              | 1         | 2.04%   |
| AlcalÃ¡ de Henares | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 15.49%  |
| Toshiba             | 10        | 10     | 14.08%  |
| Samsung Electronics | 9         | 13     | 12.68%  |
| WDC                 | 8         | 9      | 11.27%  |
| Kingston            | 6         | 6      | 8.45%   |
| Sandisk             | 5         | 7      | 7.04%   |
| China               | 3         | 4      | 4.23%   |
| Hitachi             | 2         | 2      | 2.82%   |
| Crucial             | 2         | 2      | 2.82%   |
| Unknown             | 1         | 2      | 1.41%   |
| Team                | 1         | 1      | 1.41%   |
| Silicon Motion      | 1         | 1      | 1.41%   |
| PNY                 | 1         | 1      | 1.41%   |
| PLEXTOR             | 1         | 1      | 1.41%   |
| Phison              | 1         | 1      | 1.41%   |
| Netac               | 1         | 1      | 1.41%   |
| KingSpec            | 1         | 1      | 1.41%   |
| Intenso             | 1         | 2      | 1.41%   |
| HUAWEI              | 1         | 1      | 1.41%   |
| HGST                | 1         | 1      | 1.41%   |
| BHT                 | 1         | 1      | 1.41%   |
| ASMedia             | 1         | 1      | 1.41%   |
| Apple               | 1         | 1      | 1.41%   |
| A-DATA Technology   | 1         | 1      | 1.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                       | 3         | 3.9%    |
| Toshiba MQ01ABD075 752GB                     | 2         | 2.6%    |
| Toshiba DT01ACA200 2TB                       | 2         | 2.6%    |
| Seagate ST250DM000-1BD141 250GB              | 2         | 2.6%    |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 2         | 2.6%    |
| Kingston SV300S37A120G 120GB SSD             | 2         | 2.6%    |
| Kingston NVMe SSD Drive 512GB                | 2         | 2.6%    |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1.3%    |
| WDC WD6400BPVT-75HXZT1 640GB                 | 1         | 1.3%    |
| WDC WD2003FZEX-00Z4SA0 2TB                   | 1         | 1.3%    |
| WDC WD10PURX-64E5EY0 1TB                     | 1         | 1.3%    |
| WDC WD10EZRX-00L4HB0 1TB                     | 1         | 1.3%    |
| WDC WD10EARS-00Y5B1 1TB                      | 1         | 1.3%    |
| WDC PC SN720 SDAPNTW-512G-1101 512GB         | 1         | 1.3%    |
| Unknown SD  128GB                            | 1         | 1.3%    |
| Unknown ISOCOM  64GB                         | 1         | 1.3%    |
| Toshiba MQ01ACF050 500GB                     | 1         | 1.3%    |
| Toshiba MK2555GSXF 250GB                     | 1         | 1.3%    |
| Toshiba MK2533GSGF 250GB                     | 1         | 1.3%    |
| Team TM8PS7512G 512GB SSD                    | 1         | 1.3%    |
| Silicon Motion NVMe SSD Drive 128GB          | 1         | 1.3%    |
| Seagate ST9500325AS 500GB                    | 1         | 1.3%    |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1.3%    |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1.3%    |
| Seagate ST500LM000-SSHD-8GB                  | 1         | 1.3%    |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1.3%    |
| Seagate ST3500312CS 500GB                    | 1         | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1.3%    |
| Seagate ST1000DM003-1SB10C 1TB               | 1         | 1.3%    |
| SanDisk SDSSDH3 2T00 2TB                     | 1         | 1.3%    |
| SanDisk SD6SF1M128G1022I 128GB SSD           | 1         | 1.3%    |
| Sandisk NVMe SSD Drive 256GB                 | 1         | 1.3%    |
| Sandisk NVMe SSD Drive 250GB                 | 1         | 1.3%    |
| Sandisk NVMe SSD Drive 1TB                   | 1         | 1.3%    |
| Sandisk NVMe SSD Drive 1024GB                | 1         | 1.3%    |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 1.3%    |
| Samsung SSD 860 EVO 500GB                    | 1         | 1.3%    |
| Samsung SSD 860 EVO 250GB                    | 1         | 1.3%    |
| Samsung SSD 850 EVO 250GB                    | 1         | 1.3%    |
| Samsung SSD 840 Series 250GB                 | 1         | 1.3%    |
| Samsung NVMe SSD Drive 1024GB                | 1         | 1.3%    |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 1.3%    |
| Samsung MZVLB1T0HBLR-000L2 1TB               | 1         | 1.3%    |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 1.3%    |
| Samsung MZMPC032HBCD-000L1 32GB SSD          | 1         | 1.3%    |
| Samsung MZFLV128HCGR-000MV 128GB             | 1         | 1.3%    |
| Samsung HM500JI 500GB                        | 1         | 1.3%    |
| PNY CS900 240GB SSD                          | 1         | 1.3%    |
| PLEXTOR PX-512M6Pro 512GB SSD                | 1         | 1.3%    |
| Phison Metabox Performance 2TB PCIe NVME SSD | 1         | 1.3%    |
| Netac S535N8/256 256GB                       | 1         | 1.3%    |
| Kingston SKC600512G 512GB SSD                | 1         | 1.3%    |
| Kingston SA2000M81000G 1TB                   | 1         | 1.3%    |
| KingSpec NT-1TB SSD                          | 1         | 1.3%    |
| Intenso SSD SATAIII 512GB                    | 1         | 1.3%    |
| HUAWEI SD Storage 2GB                        | 1         | 1.3%    |
| Hitachi HTS542525K9SA00 250GB                | 1         | 1.3%    |
| Hitachi HTS542520K9SA00 200GB                | 1         | 1.3%    |
| HGST HTS541010A9E680 1TB                     | 1         | 1.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 35.48%  |
| Toshiba             | 10        | 10     | 32.26%  |
| WDC                 | 5         | 6      | 16.13%  |
| Hitachi             | 2         | 2      | 6.45%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| ASMedia             | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 20%     |
| Kingston            | 3         | 3      | 12%     |
| China               | 3         | 4      | 12%     |
| WDC                 | 2         | 2      | 8%      |
| SanDisk             | 2         | 2      | 8%      |
| Crucial             | 2         | 2      | 8%      |
| Team                | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| PLEXTOR             | 1         | 1      | 4%      |
| Netac               | 1         | 1      | 4%      |
| KingSpec            | 1         | 1      | 4%      |
| Intenso             | 1         | 2      | 4%      |
| BHT                 | 1         | 1      | 4%      |
| Apple               | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 25        | 33     | 40.32%  |
| SSD     | 23        | 29     | 37.1%   |
| NVMe    | 12        | 17     | 19.35%  |
| MMC     | 1         | 2      | 1.61%   |
| Unknown | 1         | 1      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 61     | 72.22%  |
| NVMe | 12        | 17     | 22.22%  |
| SAS  | 2         | 2      | 3.7%    |
| MMC  | 1         | 2      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 36     | 54.17%  |
| 0.51-1.0   | 16        | 19     | 33.33%  |
| 1.01-2.0   | 6         | 7      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 25%     |
| 501-1000   | 11        | 22.92%  |
| 1001-2000  | 10        | 20.83%  |
| 251-500    | 5         | 10.42%  |
| Unknown    | 4         | 8.33%   |
| 2001-3000  | 3         | 6.25%   |
| 51-100     | 2         | 4.17%   |
| 1-20       | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 17        | 34%     |
| 51-100    | 10        | 20%     |
| 251-500   | 5         | 10%     |
| 101-250   | 5         | 10%     |
| 1-20      | 4         | 8%      |
| 501-1000  | 4         | 8%      |
| Unknown   | 4         | 8%      |
| 1001-2000 | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD2003FZEX-00Z4SA0 2TB         | 1         | 1      | 11.11%  |
| Seagate ST9500325AS 500GB          | 1         | 1      | 11.11%  |
| Seagate ST250DM000-1BD141 250GB    | 1         | 1      | 11.11%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 11.11%  |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1         | 1      | 11.11%  |
| Samsung Electronics HM500JI 500GB  | 1         | 1      | 11.11%  |
| PLEXTOR PX-512M6Pro 512GB SSD      | 1         | 1      | 11.11%  |
| A-DATA Technology SX7000NP 128GB   | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 37.5%   |
| WDC                 | 1         | 1      | 12.5%   |
| SanDisk             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| PLEXTOR             | 1         | 1      | 12.5%   |
| A-DATA Technology   | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 60%     |
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 57.14%  |
| SSD  | 2         | 2      | 28.57%  |
| NVMe | 1         | 1      | 14.29%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 26        | 41     | 48.15%  |
| Works    | 24        | 32     | 44.44%  |
| Malfunc  | 4         | 9      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 29        | 53.7%   |
| AMD                         | 9         | 16.67%  |
| Sandisk                     | 4         | 7.41%   |
| Samsung Electronics         | 4         | 7.41%   |
| Nvidia                      | 3         | 5.56%   |
| Kingston Technology Company | 3         | 5.56%   |
| Silicon Motion              | 1         | 1.85%   |
| Phison Electronics          | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 14.75%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 9.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 8.2%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 4.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 4.92%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 3.28%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 3.28%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 3.28%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.64%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 1.64%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 1.64%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.64%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.64%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 1.64%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 1.64%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.64%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.64%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.64%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.64%   |
| AMD FCH SATA Controller D                                                        | 1         | 1.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 30        | 54.55%  |
| NVMe | 12        | 21.82%  |
| IDE  | 7         | 12.73%  |
| RAID | 6         | 10.91%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 75%     |
| AMD    | 12        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-2430M CPU @ 2.40GHz            | 2         | 4.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz             | 2         | 4.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics       | 2         | 4.17%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz          | 1         | 2.08%   |
| Intel Pentium CPU G630 @ 2.70GHz             | 1         | 2.08%   |
| Intel Pentium CPU G3260 @ 3.30GHz            | 1         | 2.08%   |
| Intel Core i7-8650U CPU @ 1.90GHz            | 1         | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 2.08%   |
| Intel Core i7-6600U CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 2.08%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 2.08%   |
| Intel Core i7-10850H CPU @ 2.70GHz           | 1         | 2.08%   |
| Intel Core i5-9300H CPU @ 2.40GHz            | 1         | 2.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 2.08%   |
| Intel Core i5-7400 CPU @ 3.00GHz             | 1         | 2.08%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 2.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz            | 1         | 2.08%   |
| Intel Core i5-4670S CPU @ 3.10GHz            | 1         | 2.08%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 2.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 2.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 1         | 2.08%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 2.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz         | 1         | 2.08%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz         | 1         | 2.08%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz         | 1         | 2.08%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 1         | 2.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 1         | 2.08%   |
| Intel Celeron J4125 CPU @ 2.00GHz            | 1         | 2.08%   |
| Intel Celeron CPU N3350 @ 1.10GHz            | 1         | 2.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 1         | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 2.08%   |
| AMD Ryzen 9 3900X 12-Core Processor          | 1         | 2.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics       | 1         | 2.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics       | 1         | 2.08%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics  | 1         | 2.08%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics  | 1         | 2.08%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+   | 1         | 2.08%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.08%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 1         | 2.08%   |
| AMD A6-3420M APU with Radeon HD Graphics     | 1         | 2.08%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 13        | 27.08%  |
| Intel Core i7    | 7         | 14.58%  |
| Intel Core 2 Duo | 5         | 10.42%  |
| Intel Core i3    | 4         | 8.33%   |
| AMD Ryzen 7      | 4         | 8.33%   |
| Intel Celeron    | 3         | 6.25%   |
| Other            | 2         | 4.17%   |
| Intel Pentium    | 2         | 4.17%   |
| AMD A6           | 2         | 4.17%   |
| Intel Xeon       | 1         | 2.08%   |
| AMD Ryzen 9      | 1         | 2.08%   |
| AMD Ryzen 3      | 1         | 2.08%   |
| AMD E2           | 1         | 2.08%   |
| AMD Athlon 64 X2 | 1         | 2.08%   |
| AMD A4           | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 54.17%  |
| 4      | 16        | 33.33%  |
| 8      | 4         | 8.33%   |
| 12     | 1         | 2.08%   |
| 6      | 1         | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 58.33%  |
| 1      | 20        | 41.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 52.08%  |
| 0x806e9    | 3         | 6.25%   |
| 0x1067a    | 3         | 6.25%   |
| 0x806ea    | 2         | 4.17%   |
| 0x406e3    | 2         | 4.17%   |
| 0x306a9    | 2         | 4.17%   |
| 0x206a7    | 2         | 4.17%   |
| 0x07030105 | 2         | 4.17%   |
| 0xa0652    | 1         | 2.08%   |
| 0x906ed    | 1         | 2.08%   |
| 0x706a8    | 1         | 2.08%   |
| 0x506c9    | 1         | 2.08%   |
| 0x306c3    | 1         | 2.08%   |
| 0x08701021 | 1         | 2.08%   |
| 0x03000027 | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 18.75%  |
| Penryn        | 5         | 10.42%  |
| Haswell       | 5         | 10.42%  |
| SandyBridge   | 4         | 8.33%   |
| IvyBridge     | 3         | 6.25%   |
| Zen 2         | 2         | 4.17%   |
| Skylake       | 2         | 4.17%   |
| Puma          | 2         | 4.17%   |
| Excavator     | 2         | 4.17%   |
| Broadwell     | 2         | 4.17%   |
| Unknown       | 2         | 4.17%   |
| Zen 3         | 1         | 2.08%   |
| Zen           | 1         | 2.08%   |
| Westmere      | 1         | 2.08%   |
| TigerLake     | 1         | 2.08%   |
| Silvermont    | 1         | 2.08%   |
| K8 Hammer     | 1         | 2.08%   |
| K10 Llano     | 1         | 2.08%   |
| Goldmont plus | 1         | 2.08%   |
| Goldmont      | 1         | 2.08%   |
| CometLake     | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 55.74%  |
| Nvidia | 14        | 22.95%  |
| AMD    | 13        | 21.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.35%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.76%   |
| Intel HD Graphics 620                                                                    | 3         | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.76%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 3.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.17%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.17%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 3.17%   |
| AMD Lucienne                                                                             | 2         | 3.17%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.59%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.59%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.59%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 1.59%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1         | 1.59%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.59%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 1.59%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.59%   |
| Intel HD Graphics 630                                                                    | 1         | 1.59%   |
| Intel HD Graphics 500                                                                    | 1         | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.59%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.59%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.59%   |
| AMD Renoir                                                                               | 1         | 1.59%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.59%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.59%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 1         | 1.59%   |
| AMD Cezanne                                                                              | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 45.83%  |
| 1 x AMD        | 9         | 18.75%  |
| 1 x Nvidia     | 7         | 14.58%  |
| Intel + Nvidia | 6         | 12.5%   |
| Intel + AMD    | 2         | 4.17%   |
| 2 x AMD        | 1         | 2.08%   |
| AMD + Nvidia   | 1         | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 89.8%   |
| Proprietary | 4         | 8.16%   |
| Unknown     | 1         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 73.47%  |
| 1.01-2.0   | 5         | 10.2%   |
| 0.01-0.5   | 4         | 8.16%   |
| 3.01-4.0   | 2         | 4.08%   |
| 7.01-8.0   | 1         | 2.04%   |
| 0.51-1.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 19.23%  |
| LG Display              | 6         | 11.54%  |
| BOE                     | 6         | 11.54%  |
| Chimei Innolux          | 5         | 9.62%   |
| Samsung Electronics     | 3         | 5.77%   |
| Chi Mei Optoelectronics | 3         | 5.77%   |
| Lenovo                  | 2         | 3.85%   |
| Apple                   | 2         | 3.85%   |
| Unknown (AAA)           | 1         | 1.92%   |
| Unknown                 | 1         | 1.92%   |
| Toshiba                 | 1         | 1.92%   |
| STD                     | 1         | 1.92%   |
| Philips                 | 1         | 1.92%   |
| Panasonic               | 1         | 1.92%   |
| ONN                     | 1         | 1.92%   |
| NEC Computers           | 1         | 1.92%   |
| Kogan                   | 1         | 1.92%   |
| Dell                    | 1         | 1.92%   |
| CSO                     | 1         | 1.92%   |
| BenQ                    | 1         | 1.92%   |
| Ativa                   | 1         | 1.92%   |
| AOC                     | 1         | 1.92%   |
| Acer                    | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 2         | 3.77%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                    | 1         | 1.89%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                 | 1         | 1.89%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                         | 1         | 1.89%   |
| STD Monitor STD0001 1920x1080                                            | 1         | 1.89%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch     | 1         | 1.89%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch     | 1         | 1.89%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                 | 1         | 1.89%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch             | 1         | 1.89%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                     | 1         | 1.89%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD05BC 3840x2160 309x174mm 14.0-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 1         | 1.89%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 1         | 1.89%   |
| Lenovo L200pwD LEN1156 1680x1050 433x271mm 20.1-inch                     | 1         | 1.89%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                      | 1         | 1.89%   |
| Kogan KAMN27F7TA KGN0270 1920x1080 600x330mm 27.0-inch                   | 1         | 1.89%   |
| Dell LCD Monitor P2417H                                                  | 1         | 1.89%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.89%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 1         | 1.89%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUOA114 1280x800 261x163mm 12.1-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.89%   |
| Ativa AT22HZR ATV0100 1920x1080 497x292mm 22.7-inch                      | 1         | 1.89%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 1         | 1.89%   |
| Apple Color LCD APP9CC0 1280x800 261x163mm 12.1-inch                     | 1         | 1.89%   |
| AOC LCD Monitor 2217 1680x1050                                           | 1         | 1.89%   |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                         | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 19        | 38.78%  |
| 1366x768 (WXGA)    | 11        | 22.45%  |
| 1680x1050 (WSXGA+) | 4         | 8.16%   |
| 1600x900 (HD+)     | 4         | 8.16%   |
| 3840x2160 (4K)     | 3         | 6.12%   |
| 1280x800 (WXGA)    | 3         | 6.12%   |
| 3840x1080          | 1         | 2.04%   |
| 2160x1440          | 1         | 2.04%   |
| 1920x1200 (WUXGA)  | 1         | 2.04%   |
| 1440x900 (WXGA+)   | 1         | 2.04%   |
| Unknown            | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 29.41%  |
| 17      | 6         | 11.76%  |
| 14      | 5         | 9.8%    |
| 13      | 5         | 9.8%    |
| 27      | 4         | 7.84%   |
| 22      | 3         | 5.88%   |
| 24      | 2         | 3.92%   |
| 12      | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| 40      | 1         | 1.96%   |
| 32      | 1         | 1.96%   |
| 31      | 1         | 1.96%   |
| 23      | 1         | 1.96%   |
| 21      | 1         | 1.96%   |
| 20      | 1         | 1.96%   |
| 11      | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 47.06%  |
| 501-600     | 7         | 13.73%  |
| 351-400     | 6         | 11.76%  |
| 401-500     | 5         | 9.8%    |
| 201-300     | 4         | 7.84%   |
| Unknown     | 2         | 3.92%   |
| 801-900     | 1         | 1.96%   |
| 701-800     | 1         | 1.96%   |
| 601-700     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 35        | 76.09%  |
| 16/10   | 8         | 17.39%  |
| Unknown | 2         | 4.35%   |
| 3/2     | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 29.41%  |
| 81-90          | 9         | 17.65%  |
| 201-250        | 5         | 9.8%    |
| 121-130        | 5         | 9.8%    |
| 301-350        | 4         | 7.84%   |
| 61-70          | 2         | 3.92%   |
| 351-500        | 2         | 3.92%   |
| 251-300        | 2         | 3.92%   |
| Unknown        | 2         | 3.92%   |
| 71-80          | 1         | 1.96%   |
| 51-60          | 1         | 1.96%   |
| 151-200        | 1         | 1.96%   |
| 131-140        | 1         | 1.96%   |
| 501-1000       | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 30.61%  |
| 101-120       | 14        | 28.57%  |
| 51-100        | 13        | 26.53%  |
| More than 240 | 3         | 6.12%   |
| Unknown       | 2         | 4.08%   |
| 1-50          | 1         | 2.04%   |
| 161-240       | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 77.55%  |
| 2     | 8         | 16.33%  |
| 0     | 2         | 4.08%   |
| 3     | 1         | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 29        | 31.87%  |
| Intel                           | 23        | 25.27%  |
| Qualcomm Atheros                | 9         | 9.89%   |
| Broadcom                        | 6         | 6.59%   |
| MEDIATEK                        | 5         | 5.49%   |
| Samsung Electronics             | 2         | 2.2%    |
| Nvidia                          | 2         | 2.2%    |
| TP-Link                         | 1         | 1.1%    |
| Ralink                          | 1         | 1.1%    |
| Qualcomm Atheros Communications | 1         | 1.1%    |
| OnePlus Technology (Shenzhen)   | 1         | 1.1%    |
| NetGear                         | 1         | 1.1%    |
| Microsoft                       | 1         | 1.1%    |
| Marvell Technology Group        | 1         | 1.1%    |
| Linksys                         | 1         | 1.1%    |
| ICS Advent                      | 1         | 1.1%    |
| Huawei Technologies             | 1         | 1.1%    |
| Gemtek                          | 1         | 1.1%    |
| D-Link System                   | 1         | 1.1%    |
| Broadcom Limited                | 1         | 1.1%    |
| ASUSTek Computer                | 1         | 1.1%    |
| ASIX Electronics                | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 14        | 13.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 6.73%   |
| Realtek 802.11n                                                         | 3         | 2.88%   |
| Intel Wireless 3165                                                     | 3         | 2.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 1.92%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 1.92%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 2         | 1.92%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.96%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.96%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.96%   |
| OnePlus (Shenzhen) AC2001                                               | 1         | 0.96%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 0.96%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.96%   |
| NetGear A6210                                                           | 1         | 0.96%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.96%   |
| MediaTek vivo                                                           | 1         | 0.96%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.96%   |
| MediaTek Infinix HOT 10 Play                                            | 1         | 0.96%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.96%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 0.96%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.96%   |
| Intel Wireless 8260                                                     | 1         | 0.96%   |
| Intel Wireless 3160                                                     | 1         | 0.96%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.96%   |
| Intel I211 Gigabit Network Connection                                   | 1         | 0.96%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.96%   |
| Intel Ethernet Connection I217-V                                        | 1         | 0.96%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.96%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.96%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 32.73%  |
| Realtek Semiconductor           | 12        | 21.82%  |
| Qualcomm Atheros                | 6         | 10.91%  |
| Broadcom                        | 5         | 9.09%   |
| MEDIATEK                        | 3         | 5.45%   |
| TP-Link                         | 1         | 1.82%   |
| Ralink                          | 1         | 1.82%   |
| Qualcomm Atheros Communications | 1         | 1.82%   |
| NetGear                         | 1         | 1.82%   |
| Microsoft                       | 1         | 1.82%   |
| Marvell Technology Group        | 1         | 1.82%   |
| Linksys                         | 1         | 1.82%   |
| Gemtek                          | 1         | 1.82%   |
| D-Link System                   | 1         | 1.82%   |
| Broadcom Limited                | 1         | 1.82%   |
| ASUSTek Computer                | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek 802.11n                                                         | 3         | 5.45%   |
| Intel Wireless 3165                                                     | 3         | 5.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 3.64%   |
| Realtek 802.11ac NIC                                                    | 2         | 3.64%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 2         | 3.64%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.64%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 3.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 3.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.82%   |
| NetGear A6210                                                           | 1         | 1.82%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 1.82%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.82%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.82%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.82%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.82%   |
| Intel Wireless 8260                                                     | 1         | 1.82%   |
| Intel Wireless 3160                                                     | 1         | 1.82%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.82%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.82%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.82%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.82%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.82%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.82%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 1         | 1.82%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1         | 1.82%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 1.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.82%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 52.17%  |
| Intel                 | 10        | 21.74%  |
| Qualcomm Atheros      | 3         | 6.52%   |
| Samsung Electronics   | 2         | 4.35%   |
| Nvidia                | 2         | 4.35%   |
| MediaTek              | 2         | 4.35%   |
| ICS Advent            | 1         | 2.17%   |
| Broadcom              | 1         | 2.17%   |
| ASIX Electronics      | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 29.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 14.89%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 4.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.13%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.13%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.13%   |
| Nvidia MCP89 Ethernet                                             | 1         | 2.13%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.13%   |
| MediaTek vivo                                                     | 1         | 2.13%   |
| MediaTek Infinix HOT 10 Play                                      | 1         | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.13%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.13%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 2.13%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.13%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 51.72%  |
| Ethernet | 40        | 45.98%  |
| Modem    | 1         | 1.15%   |
| Unknown  | 1         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 57.63%  |
| Ethernet | 25        | 42.37%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 60.42%  |
| 1     | 18        | 37.5%   |
| 3     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 75%     |
| Yes  | 12        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 45.45%  |
| Realtek Semiconductor           | 2         | 6.06%   |
| Qualcomm Atheros Communications | 2         | 6.06%   |
| MediaTek                        | 2         | 6.06%   |
| Lite-On Technology              | 2         | 6.06%   |
| IMC Networks                    | 2         | 6.06%   |
| Apple                           | 2         | 6.06%   |
| Toshiba                         | 1         | 3.03%   |
| Ralink                          | 1         | 3.03%   |
| Marvell Semiconductor           | 1         | 3.03%   |
| Foxconn / Hon Hai               | 1         | 3.03%   |
| Cambridge Silicon Radio         | 1         | 3.03%   |
| Broadcom                        | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 21.21%  |
| Intel AX201 Bluetooth                               | 3         | 9.09%   |
| MediaTek Wireless_Device                            | 2         | 6.06%   |
| Intel AX200 Bluetooth                               | 2         | 6.06%   |
| Toshiba BCM43142A0                                  | 1         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.03%   |
| Realtek Bluetooth Radio                             | 1         | 3.03%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.03%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 3.03%   |
| Lite-On Wireless_Device                             | 1         | 3.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.03%   |
| Intel Bluetooth Device                              | 1         | 3.03%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.03%   |
| IMC Networks Bluetooth Device                       | 1         | 3.03%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.03%   |
| Broadcom BCM20702A0                                 | 1         | 3.03%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.03%   |
| Apple Bluetooth Host Controller                     | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 59.65%  |
| AMD    | 12        | 21.05%  |
| Nvidia | 11        | 19.3%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 10.81%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 6.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 6.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 6.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 4.05%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.7%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.7%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.7%    |
| AMD High Definition Audio Controller                                                              | 2         | 2.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.7%    |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.35%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Intel USB PnP Sound Device                                                                        | 1         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.35%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 29.41%  |
| Unknown             | 4         | 11.76%  |
| SK Hynix            | 4         | 11.76%  |
| Micron Technology   | 4         | 11.76%  |
| Crucial             | 4         | 11.76%  |
| Unknown (ABCD)      | 2         | 5.88%   |
| Kingston            | 2         | 5.88%   |
| Elpida              | 2         | 5.88%   |
| Ramaxel Technology  | 1         | 2.94%   |
| G.Skill             | 1         | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 5.71%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 5.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 5.71%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 2.86%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                           | 1         | 2.86%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 2.86%   |
| Unknown RAM Module 2GB DIMM                                         | 1         | 2.86%   |
| SK Hynix RAM HYMP512U64CP8-Y5 1GB DIMM                              | 1         | 2.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 1         | 2.86%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                 | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 2.86%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 2.86%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 2.86%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 1         | 2.86%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s                | 1         | 2.86%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 2.86%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s            | 1         | 2.86%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s                | 1         | 2.86%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 2.86%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s              | 1         | 2.86%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                | 1         | 2.86%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s           | 1         | 2.86%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 2.86%   |
| Elpida RAM Module 1GB SODIMM DDR3 1067MT/s                          | 1         | 2.86%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s              | 1         | 2.86%   |
| Crucial RAM CT16G4SFD832A.M16FRS 16GB SODIMM DDR4 3200MT/s          | 1         | 2.86%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 1         | 2.86%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s            | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 12        | 46.15%  |
| DDR4    | 8         | 30.77%  |
| LPDDR4  | 3         | 11.54%  |
| SDRAM   | 1         | 3.85%   |
| LPDDR3  | 1         | 3.85%   |
| Unknown | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 68%     |
| DIMM         | 7         | 28%     |
| Row Of Chips | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 13        | 43.33%  |
| 8192  | 7         | 23.33%  |
| 2048  | 4         | 13.33%  |
| 1024  | 3         | 10%     |
| 16384 | 2         | 6.67%   |
| 32768 | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 8         | 26.67%  |
| 2667    | 5         | 16.67%  |
| 2400    | 3         | 10%     |
| 1334    | 3         | 10%     |
| 3200    | 2         | 6.67%   |
| 1067    | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| 3600    | 1         | 3.33%   |
| 3266    | 1         | 3.33%   |
| 2133    | 1         | 3.33%   |
| 1867    | 1         | 3.33%   |
| 800     | 1         | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 17.95%  |
| Microdia                               | 5         | 12.82%  |
| Acer                                   | 5         | 12.82%  |
| IMC Networks                           | 4         | 10.26%  |
| Apple                                  | 4         | 10.26%  |
| Quanta                                 | 3         | 7.69%   |
| Sunplus Innovation Technology          | 2         | 5.13%   |
| Teslong Camera                         | 1         | 2.56%   |
| Suyin                                  | 1         | 2.56%   |
| Silicon Motion                         | 1         | 2.56%   |
| Ricoh                                  | 1         | 2.56%   |
| Realtek Semiconductor                  | 1         | 2.56%   |
| Goertek Electronics                    | 1         | 2.56%   |
| Creative Technology                    | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.56%   |
| Alcor Micro                            | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 5.13%   |
| Chicony HP TrueVision HD                            | 2         | 5.13%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 5.13%   |
| Acer HD Webcam                                      | 2         | 5.13%   |
| Teslong Camera                                      | 1         | 2.56%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.56%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 2.56%   |
| Ricoh HD Webcam                                     | 1         | 2.56%   |
| Realtek Integrated Webcam                           | 1         | 2.56%   |
| Quanta VGA WebCam                                   | 1         | 2.56%   |
| Quanta HP TrueVision HD Camera                      | 1         | 2.56%   |
| Quanta HD User Facing                               | 1         | 2.56%   |
| Microdia Webcam Vitade AF                           | 1         | 2.56%   |
| Microdia PC Microscope camera                       | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 2.56%   |
| Microdia HP Integrated Webcam                       | 1         | 2.56%   |
| IMC Networks XHC Camera                             | 1         | 2.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 2.56%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 2.56%   |
| IMC Networks Integrated Camera                      | 1         | 2.56%   |
| Goertek USB2.0 VGA UVC WebCam                       | 1         | 2.56%   |
| Creative Live! Cam Sync HD [VF0770]                 | 1         | 2.56%   |
| Chicony USB2.0 Camera                               | 1         | 2.56%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 2.56%   |
| Chicony Integrated HP HD Webcam                     | 1         | 2.56%   |
| Chicony Integrated Camera                           | 1         | 2.56%   |
| Chicony HD User Facing                              | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.56%   |
| Apple FaceTime Camera                               | 1         | 2.56%   |
| Apple Built-in iSight                               | 1         | 2.56%   |
| Alcor Micro USB 2.0 PC cam                          | 1         | 2.56%   |
| Acer SunplusIT Integrated Camera                    | 1         | 2.56%   |
| Acer Lenovo EasyCamera                              | 1         | 2.56%   |
| Acer Integrated Camera                              | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 3         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 16.67%  |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 16.67%  |
| Synaptics  WBDI                                   | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 75%     |
| OmniKey  | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| OmniKey CardMan Smart@Link                                                   | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 48.98%  |
| 1     | 20        | 40.82%  |
| 2     | 5         | 10.2%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 9         | 33.33%  |
| Fingerprint reader       | 6         | 22.22%  |
| Graphics card            | 4         | 14.81%  |
| Multimedia controller    | 3         | 11.11%  |
| Chipcard                 | 3         | 11.11%  |
| Communication controller | 1         | 3.7%    |
| Bluetooth                | 1         | 3.7%    |

