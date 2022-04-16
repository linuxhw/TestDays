Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 63

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | 970 GAMING                  | [1ed579d3d1](https://linux-hardware.org/?probe=1ed579d3d1) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | [dae8a4db62](https://linux-hardware.org/?probe=dae8a4db62) | Apr 16, 2022 |
| Unknown       | Unknown                     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Gigabyte      | B75M-D3P                    | [cfb6502298](https://linux-hardware.org/?probe=cfb6502298) | Apr 14, 2022 |
| MSI           | MEG X570 UNIFY              | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [1009093226](https://linux-hardware.org/?probe=1009093226) | Apr 10, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [62c84ef4b4](https://linux-hardware.org/?probe=62c84ef4b4) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [07bde861ad](https://linux-hardware.org/?probe=07bde861ad) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Unknown       | HX90                        | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| HP            | 1495                        | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fa9314716d](https://linux-hardware.org/?probe=fa9314716d) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d2f9498bd2](https://linux-hardware.org/?probe=d2f9498bd2) | Apr 05, 2022 |
| Acer          | Aspire XC-603               | [ef344607ad](https://linux-hardware.org/?probe=ef344607ad) | Apr 04, 2022 |
| Packard Be... | IMEDIA S2110A               | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| Le Cube 1     | Unknown                     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| HP            | 1589                        | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| Unknown       | T3 MRD                      | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| Unknown       | T3 MRD                      | [35ab38818d](https://linux-hardware.org/?probe=35ab38818d) | Feb 28, 2022 |
| Unknown       | T3 MRD                      | [01dd9cefa7](https://linux-hardware.org/?probe=01dd9cefa7) | Feb 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Dell          | 0YXT71 A03                  | [19227aa57d](https://linux-hardware.org/?probe=19227aa57d) | Feb 11, 2022 |
| HP            | 212B                        | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| ASRockRack    | X470D4U2/1N1                | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [b69dafbb2b](https://linux-hardware.org/?probe=b69dafbb2b) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| Gigabyte      | GB-BSi7-1165G7              | [ab94ff1199](https://linux-hardware.org/?probe=ab94ff1199) | Jan 20, 2022 |
| MSI           | Z490-A PRO                  | [b2655bbd43](https://linux-hardware.org/?probe=b2655bbd43) | Jan 15, 2022 |
| MSI           | C236A WORKSTATION           | [97795d3ebc](https://linux-hardware.org/?probe=97795d3ebc) | Jan 07, 2022 |
| Intel         | H61                         | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [0db33a5b23](https://linux-hardware.org/?probe=0db33a5b23) | Dec 10, 2021 |
| Huanan        | X99 F8D V2.2                | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Gigabyte      | EP31-DS3L                   | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| MSI           | MS-7235                     | [bbfa7fb897](https://linux-hardware.org/?probe=bbfa7fb897) | Oct 24, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.15.0-25-generic        | 13       | 26%     |
| 5.15.0-23-generic        | 10       | 20%     |
| 5.15.0-18-generic        | 9        | 18%     |
| 5.13.0-19-generic        | 7        | 14%     |
| 5.15.0-22-generic        | 3        | 6%      |
| 5.17.2-051702-generic    | 1        | 2%      |
| 5.17.1-051701-generic    | 1        | 2%      |
| 5.17.0-tkg-cacule        | 1        | 2%      |
| 5.16.0-051600-generic    | 1        | 2%      |
| 5.15.13-051513-generic   | 1        | 2%      |
| 5.15.0-17-generic        | 1        | 2%      |
| 5.15.0-051500rc7-generic | 1        | 2%      |
| 5.13.0-20-generic        | 1        | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 35       | 72.92%  |
| 5.13.0  | 8        | 16.67%  |
| 5.17.2  | 1        | 2.08%   |
| 5.17.1  | 1        | 2.08%   |
| 5.17.0  | 1        | 2.08%   |
| 5.16.0  | 1        | 2.08%   |
| 5.15.13 | 1        | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 36       | 75%     |
| 5.13    | 8        | 16.67%  |
| 5.17    | 3        | 6.25%   |
| 5.16    | 1        | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 48       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 44       | 91.67%  |
| Unknown         | 2        | 4.17%   |
| X-Cinnamon      | 1        | 2.08%   |
| GNOME Flashback | 1        | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 24       | 50%     |
| X11     | 22       | 45.83%  |
| Tty     | 1        | 2.08%   |
| Unknown | 1        | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 38       | 79.17%  |
| Unknown | 6        | 12.5%   |
| LightDM | 2        | 4.17%   |
| GDM     | 2        | 4.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 20       | 41.67%  |
| de_DE | 6        | 12.5%   |
| pt_BR | 5        | 10.42%  |
| cs_CZ | 4        | 8.33%   |
| fr_FR | 2        | 4.17%   |
| zh_TW | 1        | 2.08%   |
| zh_CN | 1        | 2.08%   |
| th_TH | 1        | 2.08%   |
| ru_RU | 1        | 2.08%   |
| ro_RO | 1        | 2.08%   |
| pl_PL | 1        | 2.08%   |
| it_IT | 1        | 2.08%   |
| es_ES | 1        | 2.08%   |
| en_IN | 1        | 2.08%   |
| en_GB | 1        | 2.08%   |
| en_CA | 1        | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 64.58%  |
| EFI  | 17       | 35.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 42       | 85.71%  |
| Xfs     | 3        | 6.12%   |
| Btrfs   | 2        | 4.08%   |
| Zfs     | 1        | 2.04%   |
| Overlay | 1        | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 72.92%  |
| GPT     | 13       | 27.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 68.75%  |
| Yes       | 15       | 31.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 50%     |
| No        | 24       | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 11       | 22.92%  |
| MSI                 | 9        | 18.75%  |
| ASUSTek Computer    | 7        | 14.58%  |
| Hewlett-Packard     | 4        | 8.33%   |
| Dell                | 3        | 6.25%   |
| Unknown             | 3        | 6.25%   |
| Lenovo              | 2        | 4.17%   |
| Packard Bell        | 1        | 2.08%   |
| Maxtang             | 1        | 2.08%   |
| Le Cube 1           | 1        | 2.08%   |
| Intel               | 1        | 2.08%   |
| Huanan              | 1        | 2.08%   |
| Fujitsu             | 1        | 2.08%   |
| ASRockRack          | 1        | 2.08%   |
| ASRock              | 1        | 2.08%   |
| Acer                | 1        | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 4        | 8.33%   |
| ASUS ROG STRIX B350-F GAMING      | 2        | 4.17%   |
| Packard Bell IMEDIA S2110         | 1        | 2.08%   |
| MSI MS-7D54                       | 1        | 2.08%   |
| MSI MS-7D42                       | 1        | 2.08%   |
| MSI MS-7C75                       | 1        | 2.08%   |
| MSI MS-7C35                       | 1        | 2.08%   |
| MSI MS-7B84                       | 1        | 2.08%   |
| MSI MS-7A32                       | 1        | 2.08%   |
| MSI MS-7998                       | 1        | 2.08%   |
| MSI MS-7693                       | 1        | 2.08%   |
| MSI MS-7235                       | 1        | 2.08%   |
| Maxtang FP30                      | 1        | 2.08%   |
| Lenovo ThinkCentre M73 10B6001SUS | 1        | 2.08%   |
| Lenovo QiTianM520-D164 90K7S03T00 | 1        | 2.08%   |
| Intel H61                         | 1        | 2.08%   |
| Huanan X99 F8D V2.2               | 1        | 2.08%   |
| HP Z440 Workstation               | 1        | 2.08%   |
| HP Z420 Workstation               | 1        | 2.08%   |
| HP ProLiant ML110 G7              | 1        | 2.08%   |
| HP Compaq 8200 Elite SFF PC       | 1        | 2.08%   |
| Gigabyte Z690 UD AX               | 1        | 2.08%   |
| Gigabyte X570S AORUS PRO AX       | 1        | 2.08%   |
| Gigabyte X570 I AORUS PRO WIFI    | 1        | 2.08%   |
| Gigabyte X570 AORUS ELITE         | 1        | 2.08%   |
| Gigabyte M52L-S3                  | 1        | 2.08%   |
| Gigabyte H61M-DS2 DVI             | 1        | 2.08%   |
| Gigabyte H55M-S2HP                | 1        | 2.08%   |
| Gigabyte GB-BSi7-1165G7           | 1        | 2.08%   |
| Gigabyte EP31-DS3L                | 1        | 2.08%   |
| Gigabyte B75M-D3P                 | 1        | 2.08%   |
| Gigabyte B365 M AORUS ELITE       | 1        | 2.08%   |
| Fujitsu ESPRIMO Q520              | 1        | 2.08%   |
| Dell OptiPlex 7070                | 1        | 2.08%   |
| Dell OptiPlex 7010                | 1        | 2.08%   |
| Dell Inspiron 5675                | 1        | 2.08%   |
| ASUS ROG STRIX B550-I GAMING      | 1        | 2.08%   |
| ASUS P8H61-M LX3 R2.0             | 1        | 2.08%   |
| ASUS P5P41T/USB3                  | 1        | 2.08%   |
| ASUS M4A87TD/USB3                 | 1        | 2.08%   |
| ASUS K30AD_M31AD_M51AD            | 1        | 2.08%   |
| ASRockRack 520004                 | 1        | 2.08%   |
| ASRock 970 Extreme3 R2.0          | 1        | 2.08%   |
| Acer Aspire XC-603                | 1        | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Unknown                 | 4        | 8.33%   |
| ASUS ROG                | 3        | 6.25%   |
| Gigabyte X570           | 2        | 4.17%   |
| Dell OptiPlex           | 2        | 4.17%   |
| Packard Bell IMEDIA     | 1        | 2.08%   |
| MSI MS-7D54             | 1        | 2.08%   |
| MSI MS-7D42             | 1        | 2.08%   |
| MSI MS-7C75             | 1        | 2.08%   |
| MSI MS-7C35             | 1        | 2.08%   |
| MSI MS-7B84             | 1        | 2.08%   |
| MSI MS-7A32             | 1        | 2.08%   |
| MSI MS-7998             | 1        | 2.08%   |
| MSI MS-7693             | 1        | 2.08%   |
| MSI MS-7235             | 1        | 2.08%   |
| Maxtang FP30            | 1        | 2.08%   |
| Lenovo ThinkCentre      | 1        | 2.08%   |
| Lenovo QiTianM520-D164  | 1        | 2.08%   |
| Intel H61               | 1        | 2.08%   |
| Huanan X99              | 1        | 2.08%   |
| HP Z440                 | 1        | 2.08%   |
| HP Z420                 | 1        | 2.08%   |
| HP ProLiant             | 1        | 2.08%   |
| HP Compaq               | 1        | 2.08%   |
| Gigabyte Z690           | 1        | 2.08%   |
| Gigabyte X570S          | 1        | 2.08%   |
| Gigabyte M52L-S3        | 1        | 2.08%   |
| Gigabyte H61M-DS2       | 1        | 2.08%   |
| Gigabyte H55M-S2HP      | 1        | 2.08%   |
| Gigabyte GB-BSi7-1165G7 | 1        | 2.08%   |
| Gigabyte EP31-DS3L      | 1        | 2.08%   |
| Gigabyte B75M-D3P       | 1        | 2.08%   |
| Gigabyte B365           | 1        | 2.08%   |
| Fujitsu ESPRIMO         | 1        | 2.08%   |
| Dell Inspiron           | 1        | 2.08%   |
| ASUS P8H61-M            | 1        | 2.08%   |
| ASUS P5P41T             | 1        | 2.08%   |
| ASUS M4A87TD            | 1        | 2.08%   |
| ASUS K30AD              | 1        | 2.08%   |
| ASRockRack 520004       | 1        | 2.08%   |
| ASRock 970              | 1        | 2.08%   |
| Acer Aspire             | 1        | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 8        | 16.67%  |
| 2019 | 8        | 16.67%  |
| 2012 | 6        | 12.5%   |
| 2020 | 5        | 10.42%  |
| 2017 | 4        | 8.33%   |
| 2014 | 3        | 6.25%   |
| 2010 | 3        | 6.25%   |
| 2018 | 2        | 4.17%   |
| 2013 | 2        | 4.17%   |
| 2011 | 2        | 4.17%   |
| 2016 | 1        | 2.08%   |
| 2015 | 1        | 2.08%   |
| 2008 | 1        | 2.08%   |
| 2007 | 1        | 2.08%   |
| 2006 | 1        | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 48       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 47       | 97.92%  |
| Enabled  | 1        | 2.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 10       | 20.83%  |
| 32.01-64.0  | 9        | 18.75%  |
| 64.01-256.0 | 9        | 18.75%  |
| 3.01-4.0    | 8        | 16.67%  |
| 4.01-8.0    | 7        | 14.58%  |
| 8.01-16.0   | 5        | 10.42%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 20       | 40.82%  |
| 2.01-3.0   | 12       | 24.49%  |
| 4.01-8.0   | 6        | 12.24%  |
| 3.01-4.0   | 5        | 10.2%   |
| 8.01-16.0  | 4        | 8.16%   |
| 24.01-32.0 | 1        | 2.04%   |
| 0.51-1.0   | 1        | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 16       | 32.65%  |
| 1      | 15       | 30.61%  |
| 4      | 7        | 14.29%  |
| 3      | 5        | 10.2%   |
| 8      | 2        | 4.08%   |
| 5      | 2        | 4.08%   |
| 20     | 1        | 2.04%   |
| 6      | 1        | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 59.18%  |
| Yes       | 20       | 40.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 52.08%  |
| No        | 23       | 47.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 54.17%  |
| Yes       | 22       | 45.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 12       | 25%     |
| Germany      | 7        | 14.58%  |
| Brazil       | 5        | 10.42%  |
| Czechia      | 4        | 8.33%   |
| Spain        | 2        | 4.17%   |
| Russia       | 2        | 4.17%   |
| France       | 2        | 4.17%   |
| UK           | 1        | 2.08%   |
| Thailand     | 1        | 2.08%   |
| Taiwan       | 1        | 2.08%   |
| Sweden       | 1        | 2.08%   |
| South Korea  | 1        | 2.08%   |
| Saudi Arabia | 1        | 2.08%   |
| Romania      | 1        | 2.08%   |
| Poland       | 1        | 2.08%   |
| Lithuania    | 1        | 2.08%   |
| Japan        | 1        | 2.08%   |
| Italy        | 1        | 2.08%   |
| India        | 1        | 2.08%   |
| China        | 1        | 2.08%   |
| Canada       | 1        | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ostrava             | 2        | 4.17%   |
| Madrid              | 2        | 4.17%   |
| Woodland Hills      | 1        | 2.08%   |
| Warsaw              | 1        | 2.08%   |
| Walled Lake         | 1        | 2.08%   |
| Vilnius             | 1        | 2.08%   |
| Sutton Coldfield    | 1        | 2.08%   |
| Suffolk             | 1        | 2.08%   |
| St Petersburg       | 1        | 2.08%   |
| Springdale          | 1        | 2.08%   |
| Soest               | 1        | 2.08%   |
| Seoul               | 1        | 2.08%   |
| Senonches           | 1        | 2.08%   |
| Seattle             | 1        | 2.08%   |
| San Valentino Torio | 1        | 2.08%   |
| Recife              | 1        | 2.08%   |
| Prague              | 1        | 2.08%   |
| Pilsen              | 1        | 2.08%   |
| Phuket              | 1        | 2.08%   |
| Pacatuba            | 1        | 2.08%   |
| Osasco              | 1        | 2.08%   |
| Oakland             | 1        | 2.08%   |
| Novosibirsk         | 1        | 2.08%   |
| Newark              | 1        | 2.08%   |
| New Taipei          | 1        | 2.08%   |
| Moses Lake          | 1        | 2.08%   |
| Millville           | 1        | 2.08%   |
| Lund                | 1        | 2.08%   |
| La Mesa             | 1        | 2.08%   |
| Krefeld             | 1        | 2.08%   |
| Hyattsville         | 1        | 2.08%   |
| Hamm                | 1        | 2.08%   |
| Hamburg             | 1        | 2.08%   |
| Gudensberg          | 1        | 2.08%   |
| Fredericton         | 1        | 2.08%   |
| Frankfurt am Main   | 1        | 2.08%   |
| Curitiba            | 1        | 2.08%   |
| Chantonnay          | 1        | 2.08%   |
| Bucharest           | 1        | 2.08%   |
| Bengaluru           | 1        | 2.08%   |
| Beijing             | 1        | 2.08%   |
| Bebedouro           | 1        | 2.08%   |
| Baton Rouge         | 1        | 2.08%   |
| Aspisheim           | 1        | 2.08%   |
| Al Qatif            | 1        | 2.08%   |
| Aichi               | 1        | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 19       | 25     | 20%     |
| WDC                       | 17       | 52     | 17.89%  |
| Samsung Electronics       | 13       | 21     | 13.68%  |
| Toshiba                   | 5        | 5      | 5.26%   |
| Kingston                  | 5        | 8      | 5.26%   |
| SanDisk                   | 4        | 4      | 4.21%   |
| OCZ                       | 3        | 9      | 3.16%   |
| Hitachi                   | 3        | 3      | 3.16%   |
| SK Hynix                  | 2        | 2      | 2.11%   |
| Phison                    | 2        | 2      | 2.11%   |
| JMicron                   | 2        | 2      | 2.11%   |
| Intenso                   | 2        | 2      | 2.11%   |
| Intel                     | 2        | 2      | 2.11%   |
| HGST                      | 2        | 3      | 2.11%   |
| Crucial                   | 2        | 2      | 2.11%   |
| China                     | 2        | 2      | 2.11%   |
| Unknown                   | 1        | 4      | 1.05%   |
| UMAX                      | 1        | 1      | 1.05%   |
| Transcend                 | 1        | 1      | 1.05%   |
| SPCC                      | 1        | 1      | 1.05%   |
| Silicon Motion            | 1        | 1      | 1.05%   |
| Micron/Crucial Technology | 1        | 1      | 1.05%   |
| Micron Technology         | 1        | 1      | 1.05%   |
| KIOXIA                    | 1        | 2      | 1.05%   |
| Gigabyte Technology       | 1        | 1      | 1.05%   |
| A-DATA Technology         | 1        | 1      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB       | 3        | 2.48%   |
| Samsung NVMe SSD Drive 1TB           | 3        | 2.48%   |
| WDC WD20SPZX-75UA7T1 2TB             | 2        | 1.65%   |
| WDC WD20EARX-00PASB0 2TB             | 2        | 1.65%   |
| WDC WD20EARS-00MVWB0 2TB             | 2        | 1.65%   |
| WDC WD10SPSX-60A6WT0 1TB             | 2        | 1.65%   |
| WDC WD10EZRX-00A8LB0 1TB             | 2        | 1.65%   |
| Toshiba DT01ACA050 500GB             | 2        | 1.65%   |
| Seagate ST2000VX005-1TD164 2TB       | 2        | 1.65%   |
| Seagate ST2000DM008-2FR102 2TB       | 2        | 1.65%   |
| Samsung SSD 980 PRO 1TB              | 2        | 1.65%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 1.65%   |
| Samsung SSD 850 EVO 500GB            | 2        | 1.65%   |
| Samsung NVMe SSD Drive 500GB         | 2        | 1.65%   |
| OCZ NVMe SSD Drive 256GB             | 2        | 1.65%   |
| JMicron Generic 256GB                | 2        | 1.65%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1        | 0.83%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1        | 0.83%   |
| WDC WD80EMAZ-00WJTA0 8TB             | 1        | 0.83%   |
| WDC WD80EFZX-68UW8N0 8TB             | 1        | 0.83%   |
| WDC WD80EFAX-68LHPN0 8TB             | 1        | 0.83%   |
| WDC WD80 EMAZ-00WJTA0 8TB            | 1        | 0.83%   |
| WDC WD6003FZBX-00K5WB0 6TB           | 1        | 0.83%   |
| WDC WD60 EFRX-68L0BN1 6TB            | 1        | 0.83%   |
| WDC WD40EFRX-68N32N0 4TB             | 1        | 0.83%   |
| WDC WD4000AAKS-00TMA0 400GB          | 1        | 0.83%   |
| WDC WD3200AAKS-00L9A0 320GB          | 1        | 0.83%   |
| WDC WD3200AAKS-00B3A0 320GB          | 1        | 0.83%   |
| WDC WD3200AAJS-00VWA0 320GB          | 1        | 0.83%   |
| WDC WD30EZRX-00D8PB0 3TB             | 1        | 0.83%   |
| WDC WD140EDFZ-11A0VA0 14TB           | 1        | 0.83%   |
| WDC WD12 0EMAZ-11BLFA 12TB           | 1        | 0.83%   |
| WDC WD10JPVX-08JC3T6 1TB             | 1        | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.83%   |
| WDC WD10EURX-63UY4Y0 1TB             | 1        | 0.83%   |
| WDC WD10EFRX-68FYTN0 1TB             | 1        | 0.83%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1        | 0.83%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 1        | 0.83%   |
| WDC WD1001FALS-00J7B0 1TB            | 1        | 0.83%   |
| WDC WD10 0EMAZ-00WJTA 10TB           | 1        | 0.83%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB | 1        | 0.83%   |
| Unknown MMC Card  64GB               | 1        | 0.83%   |
| UMAX 2280 64G SSD                    | 1        | 0.83%   |
| Transcend TS512GSSD370S 512GB        | 1        | 0.83%   |
| Toshiba HDWL120 2TB                  | 1        | 0.83%   |
| Toshiba HDWE140 4TB                  | 1        | 0.83%   |
| Toshiba DT01ACA100 1TB               | 1        | 0.83%   |
| SPCC Solid State Disk 256GB          | 1        | 0.83%   |
| SK Hynix NVMe SSD Drive 1TB          | 1        | 0.83%   |
| SK Hynix BC511 NVMe 256GB            | 1        | 0.83%   |
| Silicon Motion NVMe SSD Drive 256GB  | 1        | 0.83%   |
| Seagate ST8000AS 0002-1NA17Z 8TB     | 1        | 0.83%   |
| Seagate ST6000NM0115-1YZ110 6TB      | 1        | 0.83%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 0.83%   |
| Seagate ST3750640NS 752GB            | 1        | 0.83%   |
| Seagate ST3500410SV 500GB            | 1        | 0.83%   |
| Seagate ST3250312AS 250GB            | 1        | 0.83%   |
| Seagate ST2000LM007-1R8174 2TB       | 1        | 0.83%   |
| Seagate ST2000DM001-9YN164 2TB       | 1        | 0.83%   |
| Seagate ST2000DM001-1ER164 2TB       | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 19       | 25     | 43.18%  |
| WDC     | 15       | 49     | 34.09%  |
| Toshiba | 5        | 5      | 11.36%  |
| Hitachi | 3        | 3      | 6.82%   |
| HGST    | 2        | 3      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 9      | 20.69%  |
| Kingston            | 4        | 5      | 13.79%  |
| SanDisk             | 2        | 2      | 6.9%    |
| JMicron             | 2        | 2      | 6.9%    |
| Intenso             | 2        | 2      | 6.9%    |
| Intel               | 2        | 2      | 6.9%    |
| Crucial             | 2        | 2      | 6.9%    |
| China               | 2        | 2      | 6.9%    |
| UMAX                | 1        | 1      | 3.45%   |
| Transcend           | 1        | 1      | 3.45%   |
| SPCC                | 1        | 1      | 3.45%   |
| OCZ                 | 1        | 1      | 3.45%   |
| Micron Technology   | 1        | 1      | 3.45%   |
| Gigabyte Technology | 1        | 1      | 3.45%   |
| A-DATA Technology   | 1        | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 85     | 39.74%  |
| NVMe | 23       | 36     | 29.49%  |
| SSD  | 23       | 33     | 29.49%  |
| MMC  | 1        | 4      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 40       | 104    | 56.34%  |
| NVMe | 23       | 35     | 32.39%  |
| SAS  | 7        | 15     | 9.86%   |
| MMC  | 1        | 4      | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 35     | 39.34%  |
| 0.51-1.0   | 19       | 29     | 31.15%  |
| 1.01-2.0   | 11       | 29     | 18.03%  |
| 3.01-4.0   | 2        | 3      | 3.28%   |
| 10.01-20.0 | 2        | 6      | 3.28%   |
| 4.01-10.0  | 2        | 15     | 3.28%   |
| 2.01-3.0   | 1        | 1      | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 28.57%  |
| 501-1000       | 8        | 16.33%  |
| 251-500        | 7        | 14.29%  |
| 1001-2000      | 6        | 12.24%  |
| More than 3000 | 5        | 10.2%   |
| 2001-3000      | 3        | 6.12%   |
| 1-20           | 3        | 6.12%   |
| 51-100         | 2        | 4.08%   |
| Unknown        | 1        | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 17       | 34.69%  |
| 21-50          | 7        | 14.29%  |
| 251-500        | 5        | 10.2%   |
| 101-250        | 5        | 10.2%   |
| 51-100         | 5        | 10.2%   |
| More than 3000 | 4        | 8.16%   |
| 1001-2000      | 2        | 4.08%   |
| 2001-3000      | 1        | 2.04%   |
| 501-1000       | 1        | 2.04%   |
| 0              | 1        | 2.04%   |
| Unknown        | 1        | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3750640NS 752GB | 1        | 2      | 50%     |
| Intenso SSD 120GB         | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 2      | 50%     |
| Intenso | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 2      | 50%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 39       | 122    | 72.22%  |
| Works    | 13       | 33     | 24.07%  |
| Malfunc  | 2        | 3      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 27       | 33.75%  |
| AMD                         | 19       | 23.75%  |
| Samsung Electronics         | 9        | 11.25%  |
| Sandisk                     | 5        | 6.25%   |
| ASMedia Technology          | 3        | 3.75%   |
| SK Hynix                    | 2        | 2.5%    |
| Phison Electronics          | 2        | 2.5%    |
| OCZ Technology Group        | 2        | 2.5%    |
| Marvell Technology Group    | 2        | 2.5%    |
| Kingston Technology Company | 2        | 2.5%    |
| JMicron Technology          | 2        | 2.5%    |
| Silicon Motion              | 1        | 1.25%   |
| Nvidia                      | 1        | 1.25%   |
| Micron/Crucial Technology   | 1        | 1.25%   |
| LSI Logic / Symbios Logic   | 1        | 1.25%   |
| KIOXIA                      | 1        | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 13.13%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 5.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 3.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.03%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 2.02%   |
| Sandisk Non-Volatile memory controller                                                  | 2        | 2.02%   |
| OCZ Group RD400/400A SSD                                                                | 2        | 2.02%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2        | 2.02%   |
| JMicron JMB368 IDE controller                                                           | 2        | 2.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.02%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 2.02%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 2.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.02%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.02%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 1.01%   |
| SK Hynix BC511                                                                          | 1        | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.01%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.01%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.01%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.01%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.01%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.01%   |
| Micron/Crucial Non-Volatile memory controller                                           | 1        | 1.01%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.01%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.01%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 1        | 1.01%   |
| KIOXIA NVMe SSD Controller Cx6                                                          | 1        | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.01%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.01%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.01%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 1.01%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.01%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 36       | 48%     |
| NVMe | 23       | 30.67%  |
| IDE  | 11       | 14.67%  |
| RAID | 3        | 4%      |
| SAS  | 2        | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 28       | 58.33%  |
| AMD    | 20       | 41.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel 12th Gen Core i5-12600K                  | 2        | 4.17%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 4.17%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 2        | 4.17%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 4.17%   |
| Intel Xeon CPU E5-2696 v2 @ 2.50GHz            | 1        | 2.08%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz            | 1        | 2.08%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz            | 1        | 2.08%   |
| Intel Xeon CPU E31220 @ 3.10GHz                | 1        | 2.08%   |
| Intel Pentium CPU J2900 @ 2.41GHz              | 1        | 2.08%   |
| Intel Pentium CPU G3260T @ 2.90GHz             | 1        | 2.08%   |
| Intel Pentium 4 CPU 3.00GHz                    | 1        | 2.08%   |
| Intel Core i5-9500 CPU @ 3.00GHz               | 1        | 2.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 2.08%   |
| Intel Core i5-4460S CPU @ 2.90GHz              | 1        | 2.08%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 2.08%   |
| Intel Core i5-3450 CPU @ 3.10GHz               | 1        | 2.08%   |
| Intel Core i5-3340 CPU @ 3.10GHz               | 1        | 2.08%   |
| Intel Core i3-9100F CPU @ 3.60GHz              | 1        | 2.08%   |
| Intel Core i3-6300T CPU @ 3.30GHz              | 1        | 2.08%   |
| Intel Core i3-3225 CPU @ 3.30GHz               | 1        | 2.08%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1        | 2.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 2.08%   |
| Intel Core i3 CPU 540 @ 3.07GHz                | 1        | 2.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 2.08%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 2.08%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 2.08%   |
| Intel Celeron CPU G1620 @ 2.70GHz              | 1        | 2.08%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1        | 2.08%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1        | 2.08%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx | 1        | 2.08%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 2.08%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1        | 2.08%   |
| AMD Ryzen 7 PRO 3700 8-Core Processor          | 1        | 2.08%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 2.08%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 2.08%   |
| AMD Ryzen 7 1800X Eight-Core Processor         | 1        | 2.08%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 2.08%   |
| AMD PRO A12-8870 R7, 12 COMPUTE CORES 4C+8G    | 1        | 2.08%   |
| AMD Phenom II X6 1090T Processor               | 1        | 2.08%   |
| AMD Phenom II X4 965 Processor                 | 1        | 2.08%   |
| AMD FX-4300 Quad-Core Processor                | 1        | 2.08%   |
| AMD E1-1200 APU with Radeon HD Graphics        | 1        | 2.08%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+     | 1        | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 6        | 12.5%   |
| Intel Core i3      | 6        | 12.5%   |
| Other              | 5        | 10.42%  |
| AMD Ryzen 7        | 5        | 10.42%  |
| Intel Xeon         | 4        | 8.33%   |
| AMD Ryzen 9        | 4        | 8.33%   |
| AMD Ryzen 5        | 3        | 6.25%   |
| Intel Pentium      | 2        | 4.17%   |
| Intel Core 2 Duo   | 2        | 4.17%   |
| Intel Celeron      | 2        | 4.17%   |
| Intel Pentium 4    | 1        | 2.08%   |
| Intel Atom         | 1        | 2.08%   |
| AMD Ryzen Embedded | 1        | 2.08%   |
| AMD Ryzen 7 PRO    | 1        | 2.08%   |
| AMD Phenom II X6   | 1        | 2.08%   |
| AMD Phenom II X4   | 1        | 2.08%   |
| AMD FX             | 1        | 2.08%   |
| AMD E1             | 1        | 2.08%   |
| AMD Athlon 64 X2   | 1        | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 27.08%  |
| 2      | 12       | 25%     |
| 8      | 8        | 16.67%  |
| 6      | 6        | 12.5%   |
| 12     | 4        | 8.33%   |
| 10     | 2        | 4.17%   |
| 1      | 2        | 4.17%   |
| 28     | 1        | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 47       | 97.92%  |
| 2      | 1        | 2.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 56.25%  |
| 1      | 21       | 43.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 58.33%  |
| 0x306a9    | 2        | 4.17%   |
| 0x0a201016 | 2        | 4.17%   |
| 0xa0671    | 1        | 2.08%   |
| 0x906ea    | 1        | 2.08%   |
| 0x806c1    | 1        | 2.08%   |
| 0x706a1    | 1        | 2.08%   |
| 0x506e3    | 1        | 2.08%   |
| 0x306e4    | 1        | 2.08%   |
| 0x306c3    | 1        | 2.08%   |
| 0x10677    | 1        | 2.08%   |
| 0x0a201009 | 1        | 2.08%   |
| 0x08701021 | 1        | 2.08%   |
| 0x0810100b | 1        | 2.08%   |
| 0x08001137 | 1        | 2.08%   |
| 0x0600611a | 1        | 2.08%   |
| 0x06000852 | 1        | 2.08%   |
| 0x05000119 | 1        | 2.08%   |
| 0x010000c8 | 1        | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 7        | 14.58%  |
| Zen 3         | 6        | 12.5%   |
| Zen 2         | 4        | 8.33%   |
| Zen           | 4        | 8.33%   |
| Haswell       | 3        | 6.25%   |
| Silvermont    | 2        | 4.17%   |
| SandyBridge   | 2        | 4.17%   |
| KabyLake      | 2        | 4.17%   |
| K10           | 2        | 4.17%   |
| Broadwell     | 2        | 4.17%   |
| Unknown       | 2        | 4.17%   |
| Westmere      | 1        | 2.08%   |
| TigerLake     | 1        | 2.08%   |
| Skylake       | 1        | 2.08%   |
| Piledriver    | 1        | 2.08%   |
| Penryn        | 1        | 2.08%   |
| NetBurst      | 1        | 2.08%   |
| K8 Hammer     | 1        | 2.08%   |
| Icelake       | 1        | 2.08%   |
| Goldmont plus | 1        | 2.08%   |
| Excavator     | 1        | 2.08%   |
| Core          | 1        | 2.08%   |
| Bobcat        | 1        | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 21       | 41.18%  |
| Intel                      | 14       | 27.45%  |
| AMD                        | 14       | 27.45%  |
| Matrox Electronics Systems | 1        | 1.96%   |
| ASPEED Technology          | 1        | 1.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 5.88%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2        | 3.92%   |
| Intel AlderLake-S GT1                                                                    | 2        | 3.92%   |
| AMD Cezanne                                                                              | 2        | 3.92%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 1.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.96%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.96%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 1        | 1.96%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.96%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 1.96%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.96%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 1        | 1.96%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 1.96%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 1.96%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 1.96%   |
| Nvidia GA104GL [RTX A4000]                                                               | 1        | 1.96%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 1.96%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 1.96%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.96%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 1        | 1.96%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 1.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 1.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 1.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.96%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 1.96%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                                        | 1        | 1.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.96%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.96%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1        | 1.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 1.96%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                                 | 1        | 1.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 1.96%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1        | 1.96%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 1.96%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 20       | 41.67%  |
| 1 x AMD         | 14       | 29.17%  |
| 1 x Intel       | 12       | 25%     |
| Nvidia + Matrox | 1        | 2.08%   |
| 1 x ASPEED      | 1        | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 31       | 64.58%  |
| Proprietary | 14       | 29.17%  |
| Unknown     | 3        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 64.58%  |
| 1.01-2.0   | 5        | 10.42%  |
| 7.01-8.0   | 4        | 8.33%   |
| 0.51-1.0   | 3        | 6.25%   |
| 3.01-4.0   | 2        | 4.17%   |
| 8.01-16.0  | 2        | 4.17%   |
| 2.01-3.0   | 1        | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 24%     |
| Dell                 | 5        | 10%     |
| Philips              | 4        | 8%      |
| LG Electronics       | 3        | 6%      |
| Hewlett-Packard      | 3        | 6%      |
| ViewSonic            | 2        | 4%      |
| Onkyo                | 2        | 4%      |
| Lenovo               | 2        | 4%      |
| Goldstar             | 2        | 4%      |
| AOC                  | 2        | 4%      |
| Ancor Communications | 2        | 4%      |
| Acer                 | 2        | 4%      |
| Vizio                | 1        | 2%      |
| Vestel Elektronik    | 1        | 2%      |
| Skyworth             | 1        | 2%      |
| Sceptre Tech         | 1        | 2%      |
| Panasonic            | 1        | 2%      |
| KTC                  | 1        | 2%      |
| HUAWEI               | 1        | 2%      |
| Gigabyte Technology  | 1        | 2%      |
| Compal               | 1        | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Onkyo TX-NR747 ONK0F71 1920x1200 550x309mm 24.8-inch                    | 2        | 4%      |
| Vizio E40-D0 VIZ2001 1920x1080 885x498mm 40.0-inch                      | 1        | 2%      |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                  | 1        | 2%      |
| ViewSonic VG2719-2K VSC1935 2560x1440 597x336mm 27.0-inch               | 1        | 2%      |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch      | 1        | 2%      |
| Skyworth SII REPEATER SII214F 1920x1080 476x268mm 21.5-inch             | 1        | 2%      |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                  | 1        | 2%      |
| Samsung Electronics T24D391 SAM0B73 1920x1080 521x293mm 23.5-inch       | 1        | 2%      |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 2%      |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch     | 1        | 2%      |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1        | 2%      |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 2%      |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch       | 1        | 2%      |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1        | 2%      |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 2%      |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1        | 2%      |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1        | 2%      |
| Samsung Electronics LCD Monitor SAM08FC 1366x768                        | 1        | 2%      |
| Samsung Electronics LCD Monitor LS32A70 3840x2160                       | 1        | 2%      |
| Philips PHL 278E1 PHLC217 3840x2160 597x336mm 27.0-inch                 | 1        | 2%      |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 2%      |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1        | 2%      |
| Philips 224CL PHLC075 1920x1080 492x278mm 22.2-inch                     | 1        | 2%      |
| Panasonic 10SP_AMP MEI4012 1920x540                                     | 1        | 2%      |
| LG Electronics LCD Monitor LG ULTRAWIDE                                 | 1        | 2%      |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                       | 1        | 2%      |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                        | 1        | 2%      |
| Lenovo X24q-10 LEN61A4 2560x1440 527x296mm 23.8-inch                    | 1        | 2%      |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch                | 1        | 2%      |
| KTC 43 TV KTC4300 1920x1080 953x543mm 43.2-inch                         | 1        | 2%      |
| HUAWEI ZQE-CAA HWV6A25 3440x1440 797x334mm 34.0-inch                    | 1        | 2%      |
| Hewlett-Packard Z32 HPN3437 3840x2160 697x392mm 31.5-inch               | 1        | 2%      |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch             | 1        | 2%      |
| Hewlett-Packard 2710 HWP2893 1920x1080 600x340mm 27.2-inch              | 1        | 2%      |
| Goldstar W2252 GSM567E 1680x1050 474x296mm 22.0-inch                    | 1        | 2%      |
| Goldstar 27GN950 GSM5B9A 3840x2160 600x340mm 27.2-inch                  | 1        | 2%      |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch  | 1        | 2%      |
| Dell U2713H DELA091 2560x1440 597x336mm 27.0-inch                       | 1        | 2%      |
| Dell S2421HS DEL41F4 1920x1080 530x300mm 24.0-inch                      | 1        | 2%      |
| Dell LCD Monitor P2419H 4480x1080                                       | 1        | 2%      |
| Dell 1909W DELA03D 1440x900 408x255mm 18.9-inch                         | 1        | 2%      |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                      | 1        | 2%      |
| Compal TERRA 1940HA WOR1940 1280x1024 376x301mm 19.0-inch               | 1        | 2%      |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                        | 1        | 2%      |
| AOC 2778X AOC2778 2560x1440 597x336mm 27.0-inch                         | 1        | 2%      |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 1        | 2%      |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch   | 1        | 2%      |
| Acer KG271 A ACR0596 1920x1080 598x336mm 27.0-inch                      | 1        | 2%      |
| Acer G206HQL  ACR035A 1600x900 430x240mm 19.4-inch                      | 1        | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 28.57%  |
| 3840x2160 (4K)     | 10       | 20.41%  |
| 2560x1440 (QHD)    | 7        | 14.29%  |
| 1366x768 (WXGA)    | 3        | 6.12%   |
| 1280x1024 (SXGA)   | 3        | 6.12%   |
| 1920x1200 (WUXGA)  | 2        | 4.08%   |
| 1680x1050 (WSXGA+) | 2        | 4.08%   |
| 1440x900 (WXGA+)   | 2        | 4.08%   |
| 4480x1080          | 1        | 2.04%   |
| 3440x1440          | 1        | 2.04%   |
| 2560x1080          | 1        | 2.04%   |
| 1920x540           | 1        | 2.04%   |
| 1600x900 (HD+)     | 1        | 2.04%   |
| Unknown            | 1        | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 11       | 22.45%  |
| 23      | 7        | 14.29%  |
| Unknown | 6        | 12.24%  |
| 19      | 4        | 8.16%   |
| 21      | 3        | 6.12%   |
| 84      | 2        | 4.08%   |
| 43      | 2        | 4.08%   |
| 40      | 2        | 4.08%   |
| 31      | 2        | 4.08%   |
| 25      | 2        | 4.08%   |
| 22      | 2        | 4.08%   |
| 17      | 2        | 4.08%   |
| 65      | 1        | 2.04%   |
| 34      | 1        | 2.04%   |
| 32      | 1        | 2.04%   |
| 24      | 1        | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 37.5%   |
| 401-500     | 9        | 18.75%  |
| Unknown     | 6        | 12.5%   |
| 601-700     | 3        | 6.25%   |
| 801-900     | 2        | 4.17%   |
| 701-800     | 2        | 4.17%   |
| 301-350     | 2        | 4.17%   |
| 1501-2000   | 2        | 4.17%   |
| 901-1000    | 2        | 4.17%   |
| 351-400     | 1        | 2.08%   |
| 1001-1500   | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 32       | 69.57%  |
| 16/10   | 4        | 8.7%    |
| Unknown | 4        | 8.7%    |
| 5/4     | 3        | 6.52%   |
| 32/9    | 1        | 2.17%   |
| 3/2     | 1        | 2.17%   |
| 21/9    | 1        | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 24.49%  |
| 301-350        | 11       | 22.45%  |
| Unknown        | 6        | 12.24%  |
| 151-200        | 5        | 10.2%   |
| 351-500        | 4        | 8.16%   |
| 501-1000       | 4        | 8.16%   |
| More than 1000 | 3        | 6.12%   |
| 251-300        | 2        | 4.08%   |
| 141-150        | 2        | 4.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 51.06%  |
| 101-120 | 9        | 19.15%  |
| Unknown | 6        | 12.77%  |
| 1-50    | 3        | 6.38%   |
| 121-160 | 3        | 6.38%   |
| 161-240 | 2        | 4.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 85.42%  |
| 2     | 6        | 12.5%   |
| 0     | 1        | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 30       | 43.48%  |
| Intel                 | 27       | 39.13%  |
| Qualcomm Atheros      | 4        | 5.8%    |
| Xiaomi                | 1        | 1.45%   |
| TP-Link               | 1        | 1.45%   |
| Pulse-Eight           | 1        | 1.45%   |
| Nvidia                | 1        | 1.45%   |
| Mellanox Technologies | 1        | 1.45%   |
| MEDIATEK              | 1        | 1.45%   |
| Linksys               | 1        | 1.45%   |
| American Megatrends   | 1        | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 22.89%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 6.02%   |
| Intel I211 Gigabit Network Connection                             | 5        | 6.02%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 4.82%   |
| Intel Ethernet Controller I225-V                                  | 4        | 4.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 3.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.61%   |
| Realtek 802.11ac NIC                                              | 2        | 2.41%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.41%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.2%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 1.2%    |
| Pulse-Eight CEC Adapter                                           | 1        | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 1        | 1.2%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 1.2%    |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                     | 1        | 1.2%    |
| Linksys AE3000 802.11abgn (3x3) Wireless Adapter [Ralink RT3573]  | 1        | 1.2%    |
| Intel Wireless 8265 / 8275                                        | 1        | 1.2%    |
| Intel Wireless 7265                                               | 1        | 1.2%    |
| Intel Wireless 7260                                               | 1        | 1.2%    |
| Intel Wireless 3165                                               | 1        | 1.2%    |
| Intel I210 Gigabit Network Connection                             | 1        | 1.2%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.2%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.2%    |
| Intel Ethernet Connection (13) I219-V                             | 1        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.2%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.2%    |
| American Megatrends Virtual Ethernet                              | 1        | 1.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 50%     |
| Realtek Semiconductor | 7        | 26.92%  |
| Qualcomm Atheros      | 3        | 11.54%  |
| TP-Link               | 1        | 3.85%   |
| MEDIATEK              | 1        | 3.85%   |
| Linksys               | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                              | 4        | 15.38%  |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 3        | 11.54%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                           | 3        | 11.54%  |
| Realtek 802.11ac NIC                                             | 2        | 7.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]       | 1        | 3.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1        | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 1        | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 1        | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 1        | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1        | 3.85%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                    | 1        | 3.85%   |
| Linksys AE3000 802.11abgn (3x3) Wireless Adapter [Ralink RT3573] | 1        | 3.85%   |
| Intel Wireless 8265 / 8275                                       | 1        | 3.85%   |
| Intel Wireless 7265                                              | 1        | 3.85%   |
| Intel Wireless 7260                                              | 1        | 3.85%   |
| Intel Wireless 3165                                              | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 1        | 3.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 26       | 50%     |
| Intel                 | 21       | 40.38%  |
| Xiaomi                | 1        | 1.92%   |
| Qualcomm Atheros      | 1        | 1.92%   |
| Nvidia                | 1        | 1.92%   |
| Mellanox Technologies | 1        | 1.92%   |
| American Megatrends   | 1        | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 33.93%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 8.93%   |
| Intel I211 Gigabit Network Connection                             | 5        | 8.93%   |
| Intel Ethernet Controller I225-V                                  | 4        | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.36%   |
| Intel Ethernet Connection I217-V                                  | 2        | 3.57%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.79%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.79%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.79%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 1.79%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.79%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.79%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 1.79%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.79%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.79%   |
| American Megatrends Virtual Ethernet                              | 1        | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 64.86%  |
| WiFi     | 25       | 33.78%  |
| Modem    | 1        | 1.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 40       | 70.18%  |
| WiFi     | 17       | 29.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 54.17%  |
| 2     | 18       | 37.5%   |
| 3     | 4        | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 68.75%  |
| Yes  | 15       | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 47.83%  |
| Cambridge Silicon Radio         | 3        | 13.04%  |
| Realtek Semiconductor           | 2        | 8.7%    |
| Qualcomm Atheros Communications | 1        | 4.35%   |
| MediaTek                        | 1        | 4.35%   |
| Logitech                        | 1        | 4.35%   |
| Lite-On Technology              | 1        | 4.35%   |
| IMC Networks                    | 1        | 4.35%   |
| Dell                            | 1        | 4.35%   |
| Broadcom                        | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 13.04%  |
| Intel AX210 Bluetooth                               | 3        | 13.04%  |
| Intel AX200 Bluetooth                               | 3        | 13.04%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 13.04%  |
| Realtek Bluetooth Radio                             | 2        | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 4.35%   |
| MediaTek Wireless_Device                            | 1        | 4.35%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 4.35%   |
| Lite-On Bluetooth Device                            | 1        | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.35%   |
| Intel Bluetooth Device                              | 1        | 4.35%   |
| IMC Networks Bluetooth Radio                        | 1        | 4.35%   |
| Dell BCM20702A0 Bluetooth Module                    | 1        | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 26       | 34.21%  |
| AMD                      | 23       | 30.26%  |
| Nvidia                   | 20       | 26.32%  |
| C-Media Electronics      | 4        | 5.26%   |
| Micro Star International | 1        | 1.32%   |
| DigiTech                 | 1        | 1.32%   |
| Corsair                  | 1        | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 8        | 9.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4        | 4.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 4.6%    |
| Nvidia Audio device                                                               | 3        | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 3.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 3.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 3.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3        | 3.45%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 2.3%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 2.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 2.3%    |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 2.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 2.3%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 2.3%    |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 2.3%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 2        | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 2.3%    |
| AMD Navi 10 HDMI Audio                                                            | 2        | 2.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 2.3%    |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.15%   |
| Nvidia High Definition Audio Controller                                           | 1        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 1.15%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.15%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.15%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 1.15%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 1.15%   |
| Micro Star International USB Audio                                                | 1        | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1        | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.15%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 1.15%   |
| Intel Audio device                                                                | 1        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1        | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 1.15%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 1.15%   |
| DigiTech Lexicon Alpha                                                            | 1        | 1.15%   |
| Corsair Slipstream Multi-Device Receiver                                          | 1        | 1.15%   |
| C-Media Electronics USB Advanced Audio Device                                     | 1        | 1.15%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 1        | 1.15%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 1        | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1        | 1.15%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 1.15%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 18.18%  |
| Corsair             | 4        | 18.18%  |
| SK Hynix            | 3        | 13.64%  |
| Micron Technology   | 3        | 13.64%  |
| Samsung Electronics | 2        | 9.09%   |
| G.Skill             | 2        | 9.09%   |
| Unknown (ABCD)      | 1        | 4.55%   |
| Unknown             | 1        | 4.55%   |
| Patriot             | 1        | 4.55%   |
| Kllisre             | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 1        | 3.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 3.7%    |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                     | 1        | 3.7%    |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 3.7%    |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 3.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 1        | 3.7%    |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s           | 1        | 3.7%    |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                 | 1        | 3.7%    |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s            | 1        | 3.7%    |
| Micron RAM 38ADF2G72AZ-2G6E1 16GB DIMM DDR4 2133MT/s           | 1        | 3.7%    |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s           | 1        | 3.7%    |
| Micron RAM 18ASF2G72AZ-2G1A1 16GB DIMM DDR4 2133MT/s           | 1        | 3.7%    |
| Micron RAM 18ADF2G72AZ-2G6E1 16GB DIMM DDR4 2667MT/s           | 1        | 3.7%    |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s             | 1        | 3.7%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 3.7%    |
| Kingston RAM CL7-7-7 DDR3-1333 2GB DIMM DDR3 1333MT/s          | 1        | 3.7%    |
| Kingston RAM CBD26D4S9S1KC-4 4GB SODIMM DDR4 2667MT/s          | 1        | 3.7%    |
| Kingston RAM 99U5474-015.A00LF 2048MB DIMM 1600MT/s            | 1        | 3.7%    |
| Kingston RAM 9905428-123.A00LF 8GB SODIMM DDR3 1600MT/s        | 1        | 3.7%    |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s          | 1        | 3.7%    |
| G.Skill RAM F4-3200C22-16GRS 16384MB SODIMM DDR4 3200MT/s      | 1        | 3.7%    |
| Corsair RAM CMY8GX3M2A1866C9 4GB DIMM DDR3 1867MT/s            | 1        | 3.7%    |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s            | 1        | 3.7%    |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 1        | 3.7%    |
| Corsair RAM CML8GX3M2A1866C9 4GB DIMM DDR3 1867MT/s            | 1        | 3.7%    |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 1        | 3.7%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 11       | 55%     |
| DDR3    | 7        | 35%     |
| LPDDR4  | 1        | 5%      |
| Unknown | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 17       | 85%     |
| SODIMM | 3        | 15%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 8        | 38.1%   |
| 8192  | 6        | 28.57%  |
| 4096  | 5        | 23.81%  |
| 32768 | 1        | 4.76%   |
| 2048  | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 4        | 16.67%  |
| 1600  | 4        | 16.67%  |
| 3200  | 3        | 12.5%   |
| 2666  | 2        | 8.33%   |
| 1333  | 2        | 8.33%   |
| 1066  | 2        | 8.33%   |
| 3666  | 1        | 4.17%   |
| 3600  | 1        | 4.17%   |
| 3466  | 1        | 4.17%   |
| 2400  | 1        | 4.17%   |
| 2133  | 1        | 4.17%   |
| 1867  | 1        | 4.17%   |
| 1866  | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP OfficeJet 8700      | 1        | 50%     |
| Brother HL-1200 series | 1        | 50%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 2        | 22.22%  |
| webcam                        | 1        | 11.11%  |
| Sony                          | 1        | 11.11%  |
| Samsung Electronics           | 1        | 11.11%  |
| Realtek Semiconductor         | 1        | 11.11%  |
| Razer USA                     | 1        | 11.11%  |
| Hewlett-Packard               | 1        | 11.11%  |
| Generalplus Technology        | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| webcam webcam                  | 1        | 11.11%  |
| Sunplus USB camera             | 1        | 11.11%  |
| Sunplus Full HD webcam         | 1        | 11.11%  |
| Sony CEVCECM                   | 1        | 11.11%  |
| Samsung Galaxy A5 (MTP)        | 1        | 11.11%  |
| Realtek FULL HD 1080P Webcam   | 1        | 11.11%  |
| Razer USA Gaming Webcam [Kiyo] | 1        | 11.11%  |
| HP Webcam                      | 1        | 11.11%  |
| Generalplus GENERAL WEBCAM     | 1        | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 40       | 83.33%  |
| 1     | 7        | 14.58%  |
| 2     | 1        | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 50%     |
| Unassigned class         | 2        | 25%     |
| Net/wireless             | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |

