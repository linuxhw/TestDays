RHEL 9 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for RHEL 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL_9/Desktop/README.md) and [notebooks](/Dist/RHEL_9/Notebook/README.md).

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

Total: 62

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 07T4MC A02                  | Desktop     | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Dell          | Latitude E7450              | Notebook    | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | 0RN4PJ A02                  | Server      | [84012f61ff](https://linux-hardware.org/?probe=84012f61ff) | Nov 03, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [4776ecdc2a](https://linux-hardware.org/?probe=4776ecdc2a) | Jul 15, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [ab729dc8a5](https://linux-hardware.org/?probe=ab729dc8a5) | Jul 04, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [1cb6aead26](https://linux-hardware.org/?probe=1cb6aead26) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 9         | 18.75%  |
| 5.14.0-70.17.1.el9_0.x86_64  | 6         | 12.5%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 5         | 10.42%  |
| 5.14.0-70.5.1.el9_0.x86_64   | 4         | 8.33%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 4         | 8.33%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 4         | 8.33%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 3         | 6.25%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3         | 6.25%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2         | 4.17%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 4.17%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 4.17%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 2.08%   |
| 5.14.0-70.17.1.el9_0.aarch64 | 1         | 2.08%   |
| 5.14.0-39.el9.x86_64         | 1         | 2.08%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 46        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 46        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 45        | 97.83%  |
| aarch64 | 1         | 2.17%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 43        | 93.48%  |
| GNOME Classic | 2         | 4.35%   |
| Unknown       | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 30        | 65.22%  |
| X11     | 14        | 30.43%  |
| Tty     | 2         | 4.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 56.52%  |
| GDM     | 19        | 41.3%   |
| SDDM    | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 33        | 71.74%  |
| en_GB | 4         | 8.7%    |
| pt_BR | 2         | 4.35%   |
| en_IN | 2         | 4.35%   |
| ru_RU | 1         | 2.17%   |
| ja_JP | 1         | 2.17%   |
| es_ES | 1         | 2.17%   |
| en_NZ | 1         | 2.17%   |
| en_CA | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 43        | 93.48%  |
| BIOS | 3         | 6.52%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 44        | 95.65%  |
| Ext4 | 2         | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 52.17%  |
| GPT     | 21        | 45.65%  |
| MBR     | 1         | 2.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 82.61%  |
| Yes       | 8         | 17.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 86.96%  |
| Yes       | 6         | 13.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 9         | 19.57%  |
| Lenovo                  | 7         | 15.22%  |
| ASUSTek Computer        | 6         | 13.04%  |
| MSI                     | 5         | 10.87%  |
| Gigabyte Technology     | 5         | 10.87%  |
| Hewlett-Packard         | 4         | 8.7%    |
| Unknown                 | 3         | 6.52%   |
| Samsung Electronics     | 1         | 2.17%   |
| Razer                   | 1         | 2.17%   |
| Raspberry Pi Foundation | 1         | 2.17%   |
| Intel                   | 1         | 2.17%   |
| Hardkernel              | 1         | 2.17%   |
| ASRock                  | 1         | 2.17%   |
| Acer                    | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 6.52%   |
| Samsung 730QCJ/730QCR                    | 1         | 2.17%   |
| Razer Blade 15 Mid 2019-Base             | 1         | 2.17%   |
| RPi Raspberry Pi 4 Model B               | 1         | 2.17%   |
| MSI MS-7D54                              | 1         | 2.17%   |
| MSI MS-7C95                              | 1         | 2.17%   |
| MSI MS-7B89                              | 1         | 2.17%   |
| MSI GP75 Leopard 9SD                     | 1         | 2.17%   |
| MSI GE72VR 7RF                           | 1         | 2.17%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US | 1         | 2.17%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 2.17%   |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00     | 1         | 2.17%   |
| Lenovo ThinkPad Edge E431 62771L7        | 1         | 2.17%   |
| Lenovo ThinkPad E14 20RA001MMZ           | 1         | 2.17%   |
| Lenovo ThinkBook 14-IIL 20SL             | 1         | 2.17%   |
| Lenovo ThinkBook 13s-IWL 20R9            | 1         | 2.17%   |
| Intel H81                                | 1         | 2.17%   |
| HP ProBook 640 G2                        | 1         | 2.17%   |
| HP Laptop 14s-dk0xxx                     | 1         | 2.17%   |
| HP EliteBook 855 G7 Notebook PC          | 1         | 2.17%   |
| HP 340S G7                               | 1         | 2.17%   |
| Hardkernel ODROID-H3                     | 1         | 2.17%   |
| Gigabyte X670E AORUS MASTER              | 1         | 2.17%   |
| Gigabyte MU72-SU0-00                     | 1         | 2.17%   |
| Gigabyte H510M H                         | 1         | 2.17%   |
| Gigabyte B550M AORUS PRO-P               | 1         | 2.17%   |
| Gigabyte AERO 15 KD                      | 1         | 2.17%   |
| Dell XPS 17 9710                         | 1         | 2.17%   |
| Dell Precision Tower 5810                | 1         | 2.17%   |
| Dell Precision 7920 Tower                | 1         | 2.17%   |
| Dell Precision 7560                      | 1         | 2.17%   |
| Dell Precision 7510                      | 1         | 2.17%   |
| Dell PowerEdge T30                       | 1         | 2.17%   |
| Dell Latitude E7450                      | 1         | 2.17%   |
| Dell Latitude 3410                       | 1         | 2.17%   |
| Dell Inspiron 5559                       | 1         | 2.17%   |
| ASUS Z450LA                              | 1         | 2.17%   |
| ASUS VivoBook_ASUSLaptop X515MA_A516MA   | 1         | 2.17%   |
| ASUS TUF Gaming Z690-PLUS WIFI D4        | 1         | 2.17%   |
| ASUS TUF Gaming X570-PLUS                | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 5         | 10.87%  |
| Dell Precision       | 4         | 8.7%    |
| Unknown              | 3         | 6.52%   |
| Lenovo ThinkBook     | 2         | 4.35%   |
| Dell Latitude        | 2         | 4.35%   |
| ASUS TUF             | 2         | 4.35%   |
| ASUS PRIME           | 2         | 4.35%   |
| Samsung 730QCJ       | 1         | 2.17%   |
| Razer Blade          | 1         | 2.17%   |
| RPi Raspberry        | 1         | 2.17%   |
| MSI MS-7D54          | 1         | 2.17%   |
| MSI MS-7C95          | 1         | 2.17%   |
| MSI MS-7B89          | 1         | 2.17%   |
| MSI GP75             | 1         | 2.17%   |
| MSI GE72VR           | 1         | 2.17%   |
| Intel H81            | 1         | 2.17%   |
| HP ProBook           | 1         | 2.17%   |
| HP Laptop            | 1         | 2.17%   |
| HP EliteBook         | 1         | 2.17%   |
| HP 340S              | 1         | 2.17%   |
| Hardkernel ODROID-H3 | 1         | 2.17%   |
| Gigabyte X670E       | 1         | 2.17%   |
| Gigabyte MU72-SU0-00 | 1         | 2.17%   |
| Gigabyte H510M       | 1         | 2.17%   |
| Gigabyte B550M       | 1         | 2.17%   |
| Gigabyte AERO        | 1         | 2.17%   |
| Dell XPS             | 1         | 2.17%   |
| Dell PowerEdge       | 1         | 2.17%   |
| Dell Inspiron        | 1         | 2.17%   |
| ASUS Z450LA          | 1         | 2.17%   |
| ASUS VivoBook        | 1         | 2.17%   |
| ASRock Z370          | 1         | 2.17%   |
| Acer Aspire          | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 10        | 21.74%  |
| 2021 | 9         | 19.57%  |
| 2022 | 7         | 15.22%  |
| 2020 | 7         | 15.22%  |
| 2017 | 4         | 8.7%    |
| 2015 | 3         | 6.52%   |
| 2016 | 2         | 4.35%   |
| 2023 | 1         | 2.17%   |
| 2018 | 1         | 2.17%   |
| 2014 | 1         | 2.17%   |
| 2013 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 25        | 54.35%  |
| Desktop        | 18        | 39.13%  |
| Server         | 2         | 4.35%   |
| System on chip | 1         | 2.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 40        | 85.11%  |
| Enabled  | 7         | 14.89%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 17        | 36.96%  |
| 4.01-8.0        | 9         | 19.57%  |
| 32.01-64.0      | 9         | 19.57%  |
| 64.01-256.0     | 6         | 13.04%  |
| 3.01-4.0        | 3         | 6.52%   |
| More than 256.0 | 1         | 2.17%   |
| 24.01-32.0      | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 18        | 37.5%   |
| 4.01-8.0  | 10        | 20.83%  |
| 3.01-4.0  | 9         | 18.75%  |
| 8.01-16.0 | 6         | 12.5%   |
| 1.01-2.0  | 5         | 10.42%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 44.68%  |
| 2      | 14        | 29.79%  |
| 3      | 6         | 12.77%  |
| 5      | 4         | 8.51%   |
| 14     | 1         | 2.13%   |
| 4      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 82.61%  |
| Yes       | 8         | 17.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 84.78%  |
| No        | 7         | 15.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 78.26%  |
| No        | 10        | 21.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 70.21%  |
| No        | 14        | 29.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 34.78%  |
| India       | 6         | 13.04%  |
| UK          | 3         | 6.52%   |
| Canada      | 3         | 6.52%   |
| Turkey      | 2         | 4.35%   |
| Chile       | 2         | 4.35%   |
| Brazil      | 2         | 4.35%   |
| Switzerland | 1         | 2.17%   |
| Sri Lanka   | 1         | 2.17%   |
| Spain       | 1         | 2.17%   |
| Russia      | 1         | 2.17%   |
| Norway      | 1         | 2.17%   |
| New Zealand | 1         | 2.17%   |
| Jordan      | 1         | 2.17%   |
| Japan       | 1         | 2.17%   |
| Indonesia   | 1         | 2.17%   |
| Guatemala   | 1         | 2.17%   |
| Germany     | 1         | 2.17%   |
| Finland     | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Santiago       | 2         | 4.26%   |
| Whiteley       | 1         | 2.13%   |
| Wellington     | 1         | 2.13%   |
| Valencia       | 1         | 2.13%   |
| Tokyo          | 1         | 2.13%   |
| Sutton         | 1         | 2.13%   |
| Stratham       | 1         | 2.13%   |
| Stavropol      | 1         | 2.13%   |
| Skien          | 1         | 2.13%   |
| Sao Paulo      | 1         | 2.13%   |
| Sainte-Marie   | 1         | 2.13%   |
| Saint Paul     | 1         | 2.13%   |
| Providence     | 1         | 2.13%   |
| Prairieville   | 1         | 2.13%   |
| Piracicaba     | 1         | 2.13%   |
| Pforzheim      | 1         | 2.13%   |
| Oldham         | 1         | 2.13%   |
| New Delhi      | 1         | 2.13%   |
| Mohegan Lake   | 1         | 2.13%   |
| Mattapoisett   | 1         | 2.13%   |
| Maltepe        | 1         | 2.13%   |
| Lansing        | 1         | 2.13%   |
| Kolkata        | 1         | 2.13%   |
| Kochi          | 1         | 2.13%   |
| Houston        | 1         | 2.13%   |
| Helsinki       | 1         | 2.13%   |
| Guatemala City | 1         | 2.13%   |
| Ghaziabad      | 1         | 2.13%   |
| Fort Collins   | 1         | 2.13%   |
| Ernakulam      | 1         | 2.13%   |
| East Peoria    | 1         | 2.13%   |
| Denver         | 1         | 2.13%   |
| Denizli        | 1         | 2.13%   |
| Corona         | 1         | 2.13%   |
| Colombo        | 1         | 2.13%   |
| Christiansburg | 1         | 2.13%   |
| Cherry Hill    | 1         | 2.13%   |
| Canton         | 1         | 2.13%   |
| Bern           | 1         | 2.13%   |
| Bengaluru      | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 16        | 20     | 18.18%  |
| Seagate                   | 10        | 14     | 11.36%  |
| WDC                       | 9         | 16     | 10.23%  |
| Sandisk                   | 7         | 7      | 7.95%   |
| Toshiba                   | 3         | 3      | 3.41%   |
| SK hynix                  | 3         | 3      | 3.41%   |
| Phison                    | 3         | 3      | 3.41%   |
| KIOXIA                    | 3         | 4      | 3.41%   |
| Kingston                  | 3         | 3      | 3.41%   |
| Intel                     | 3         | 4      | 3.41%   |
| HGST                      | 3         | 3      | 3.41%   |
| China                     | 3         | 3      | 3.41%   |
| Unknown                   | 2         | 2      | 2.27%   |
| SABRENT                   | 2         | 2      | 2.27%   |
| Micron Technology         | 2         | 2      | 2.27%   |
| KingSpec                  | 2         | 2      | 2.27%   |
| Crucial                   | 2         | 3      | 2.27%   |
| ADATA Technology          | 2         | 2      | 2.27%   |
| XUM                       | 1         | 1      | 1.14%   |
| SSSTC                     | 1         | 1      | 1.14%   |
| PNY                       | 1         | 1      | 1.14%   |
| Plextor                   | 1         | 1      | 1.14%   |
| Micron/Crucial Technology | 1         | 2      | 1.14%   |
| Hitachi                   | 1         | 1      | 1.14%   |
| Golden                    | 1         | 1      | 1.14%   |
| Gigabyte Technology       | 1         | 1      | 1.14%   |
| Fantom                    | 1         | 1      | 1.14%   |
| A-DATA Technology         | 1         | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 3.03%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 2.02%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 2         | 2.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 2.02%   |
| SABRENT Disk 14TB                                   | 2         | 2.02%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                          | 2         | 2.02%   |
| HGST HTS721010A9E630 1TB                            | 2         | 2.02%   |
| XUM HX256GSSDSATA3 256GB                            | 1         | 1.01%   |
| WDC WDBA3V5000ANC-WRSN 500GB                        | 1         | 1.01%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 1         | 1.01%   |
| WDC WD5000AVCS-632DY1 500GB                         | 1         | 1.01%   |
| WDC WD50 00LPVX-22V0TT0 500GB                       | 1         | 1.01%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1         | 1.01%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 1.01%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1         | 1.01%   |
| WDC WD141KFGX-68FH9N0 14TB                          | 1         | 1.01%   |
| WDC WD140EFGX-68B0GN0 14TB                          | 1         | 1.01%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 1.01%   |
| WDC WD10SPSX-00A6WT0 1TB                            | 1         | 1.01%   |
| WDC WD10JPLX-00MBPT0 1TB                            | 1         | 1.01%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1.01%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 1         | 1.01%   |
| WDC WD100EFAX-68LHPN0 10TB                          | 1         | 1.01%   |
| Unknown SDU1  64GB                                  | 1         | 1.01%   |
| Unknown SD/MMC/MS PRO 64GB                          | 1         | 1.01%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1.01%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.01%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.01%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                      | 1         | 1.01%   |
| SK hynix SHGP31-1000GM 1TB                          | 1         | 1.01%   |
| SK hynix SC401 SATA 512GB SSD                       | 1         | 1.01%   |
| SK hynix NVMe SSD Drive 1024GB                      | 1         | 1.01%   |
| Seagate ST9250315AS 250GB                           | 1         | 1.01%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1         | 1.01%   |
| Seagate ST4000DM000-2AE166 4TB                      | 1         | 1.01%   |
| Seagate ST3500312CS 500GB                           | 1         | 1.01%   |
| Seagate ST31000528AS 1TB                            | 1         | 1.01%   |
| Seagate ST3000VN000-1HJ166 3TB                      | 1         | 1.01%   |
| Seagate ST18000NM000J-2TV103 18TB                   | 1         | 1.01%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 14     | 37.04%  |
| WDC     | 8         | 15     | 29.63%  |
| Toshiba | 3         | 3      | 11.11%  |
| HGST    | 3         | 3      | 11.11%  |
| Unknown | 1         | 1      | 3.7%    |
| Hitachi | 1         | 1      | 3.7%    |
| Fantom  | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 28%     |
| China               | 3         | 3      | 12%     |
| SanDisk             | 2         | 2      | 8%      |
| SABRENT             | 2         | 2      | 8%      |
| KingSpec            | 2         | 2      | 8%      |
| Crucial             | 2         | 2      | 8%      |
| XUM                 | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| Plextor             | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| Intel               | 1         | 2      | 4%      |
| Gigabyte Technology | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 34        | 40     | 44.16%  |
| SSD     | 21        | 27     | 27.27%  |
| HDD     | 20        | 38     | 25.97%  |
| MMC     | 1         | 1      | 1.3%    |
| Unknown | 1         | 1      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 34        | 40     | 49.28%  |
| SATA | 29        | 60     | 42.03%  |
| SAS  | 5         | 6      | 7.25%   |
| MMC  | 1         | 1      | 1.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 16        | 22     | 38.1%   |
| 0.01-0.5   | 15        | 22     | 35.71%  |
| 10.01-20.0 | 3         | 6      | 7.14%   |
| 4.01-10.0  | 3         | 6      | 7.14%   |
| 3.01-4.0   | 2         | 4      | 4.76%   |
| 1.01-2.0   | 2         | 3      | 4.76%   |
| 2.01-3.0   | 1         | 2      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 31.91%  |
| 251-500        | 11        | 23.4%   |
| 501-1000       | 8         | 17.02%  |
| 1001-2000      | 6         | 12.77%  |
| More than 3000 | 3         | 6.38%   |
| 51-100         | 3         | 6.38%   |
| Unknown        | 1         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 18        | 38.3%   |
| 21-50          | 11        | 23.4%   |
| 51-100         | 6         | 12.77%  |
| 251-500        | 5         | 10.64%  |
| 101-250        | 3         | 6.38%   |
| More than 3000 | 2         | 4.26%   |
| 1001-2000      | 1         | 2.13%   |
| Unknown        | 1         | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB  | 1         | 1      | 25%     |
| Seagate ST1000DM010-2EP102 1TB | 1         | 1      | 25%     |
| Intel SSDSC2BA800G4R 800GB     | 1         | 2      | 25%     |
| Crucial CT1000BX500SSD1 1TB    | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| Intel   | 1         | 2      | 25%     |
| Crucial | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 66.67%  |
| HDD  | 1         | 2      | 33.33%  |

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
| Detected | 28        | 57     | 54.9%   |
| Works    | 20        | 45     | 39.22%  |
| Malfunc  | 3         | 5      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 31        | 41.33%  |
| Samsung Electronics         | 10        | 13.33%  |
| AMD                         | 8         | 10.67%  |
| SanDisk                     | 6         | 8%      |
| Phison Electronics          | 3         | 4%      |
| KIOXIA                      | 3         | 4%      |
| ADATA Technology            | 3         | 4%      |
| SK hynix                    | 2         | 2.67%   |
| Micron/Crucial Technology   | 2         | 2.67%   |
| Micron Technology           | 2         | 2.67%   |
| Kingston Technology Company | 2         | 2.67%   |
| Broadcom / LSI              | 2         | 2.67%   |
| ASMedia Technology          | 1         | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 6.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 4         | 4.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 4         | 4.88%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 3.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 3.66%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 2         | 2.44%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 2         | 2.44%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 2.44%   |
| Phison E12 NVMe Controller                                                    | 2         | 2.44%   |
| Micron NVMe Storage Controller                                                | 2         | 2.44%   |
| KIOXIA Non-Volatile memory controller                                         | 2         | 2.44%   |
| Kingston Company Company Non-Volatile memory controller                       | 2         | 2.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 2.44%   |
| Intel SSD 660P Series                                                         | 2         | 2.44%   |
| Intel SATA Controller [RAID mode]                                             | 2         | 2.44%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 2         | 2.44%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 2.44%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 2         | 2.44%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 2         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 2.44%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 2.44%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 2.44%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 1.22%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                            | 1         | 1.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 1.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.22%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 1.22%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 1.22%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 1.22%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation         | 1         | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.22%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 1.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.22%   |
| Intel C620 Series Chipset Family IDE Redirection                              | 1         | 1.22%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 1         | 1.22%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 1.22%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 1         | 1.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 33        | 43.42%  |
| SATA | 31        | 40.79%  |
| RAID | 10        | 13.16%  |
| SAS  | 1         | 1.32%   |
| IDE  | 1         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 78.26%  |
| AMD    | 9         | 19.57%  |
| ARM    | 1         | 2.17%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz          | 2         | 4.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz         | 2         | 4.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 4.35%   |
| AMD Ryzen 5 3600 6-Core Processor          | 2         | 4.35%   |
| Intel Xeon W-11855M CPU @ 3.20GHz          | 1         | 2.17%   |
| Intel Xeon Silver 4310 CPU @ 2.10GHz       | 1         | 2.17%   |
| Intel Xeon Platinum 8168 CPU @ 2.70GHz     | 1         | 2.17%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz        | 1         | 2.17%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz        | 1         | 2.17%   |
| Intel Pentium Silver N6005 @ 2.00GHz       | 1         | 2.17%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 1         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 2.17%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 2.17%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 1         | 2.17%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 2.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 2.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 2.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 1         | 2.17%   |
| Intel Core i5-3570 CPU @ 3.40GHz           | 1         | 2.17%   |
| Intel Core i5-3470S CPU @ 2.90GHz          | 1         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 1         | 2.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz           | 1         | 2.17%   |
| Intel Core i3-4005U CPU @ 1.70GHz          | 1         | 2.17%   |
| Intel Celeron N5105 @ 2.00GHz              | 1         | 2.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 1         | 2.17%   |
| Intel 13th Gen Core i5-13600K              | 1         | 2.17%   |
| Intel 12th Gen Core i9-12900K              | 1         | 2.17%   |
| Intel 12th Gen Core i7-1260P               | 1         | 2.17%   |
| Intel 12th Gen Core i5-1235U               | 1         | 2.17%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz    | 1         | 2.17%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz    | 1         | 2.17%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 1         | 2.17%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz    | 1         | 2.17%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz    | 1         | 2.17%   |
| ARM Processor                              | 1         | 2.17%   |
| AMD Ryzen 9 7900X 12-Core Processor        | 1         | 2.17%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 1         | 2.17%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 1         | 2.17%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 1         | 2.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 10        | 21.74%  |
| Intel Core i5        | 9         | 19.57%  |
| Intel Core i7        | 8         | 17.39%  |
| AMD Ryzen 5          | 4         | 8.7%    |
| Intel Xeon           | 3         | 6.52%   |
| AMD Ryzen 9          | 3         | 6.52%   |
| Intel Core i3        | 2         | 4.35%   |
| Intel Celeron        | 2         | 4.35%   |
| Intel Xeon Silver    | 1         | 2.17%   |
| Intel Xeon Platinum  | 1         | 2.17%   |
| Intel Pentium Silver | 1         | 2.17%   |
| AMD Ryzen 7 PRO      | 1         | 2.17%   |
| AMD A4               | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 16        | 34.78%  |
| 2      | 8         | 17.39%  |
| 8      | 7         | 15.22%  |
| 6      | 7         | 15.22%  |
| 12     | 5         | 10.87%  |
| 48     | 1         | 2.17%   |
| 14     | 1         | 2.17%   |
| 10     | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 97.83%  |
| 2      | 1         | 2.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 36        | 78.26%  |
| 1      | 10        | 21.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 8.7%    |
| 0x806d1    | 4         | 8.7%    |
| 0x306a9    | 3         | 6.52%   |
| 0x08701021 | 3         | 6.52%   |
| 0xa0671    | 2         | 4.35%   |
| 0x906ea    | 2         | 4.35%   |
| 0x906c0    | 2         | 4.35%   |
| 0x706e5    | 2         | 4.35%   |
| 0x506e3    | 2         | 4.35%   |
| 0x406e3    | 2         | 4.35%   |
| 0xb0671    | 1         | 2.17%   |
| 0x906ed    | 1         | 2.17%   |
| 0x906e9    | 1         | 2.17%   |
| 0x906a4    | 1         | 2.17%   |
| 0x906a3    | 1         | 2.17%   |
| 0x90672    | 1         | 2.17%   |
| 0x706a8    | 1         | 2.17%   |
| 0x606a6    | 1         | 2.17%   |
| 0x50654    | 1         | 2.17%   |
| 0x406f1    | 1         | 2.17%   |
| 0x40651    | 1         | 2.17%   |
| 0x306d4    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x0a601203 | 1         | 2.17%   |
| 0x0a50000c | 1         | 2.17%   |
| 0x0a20120a | 1         | 2.17%   |
| 0x08600106 | 1         | 2.17%   |
| 0x08108109 | 1         | 2.17%   |
| 0x06006705 | 1         | 2.17%   |
| Unknown    | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Icelake          | 9         | 19.57%  |
| KabyLake         | 8         | 17.39%  |
| Skylake          | 5         | 10.87%  |
| Zen 2            | 4         | 8.7%    |
| Alderlake Hybrid | 4         | 8.7%    |
| IvyBridge        | 3         | 6.52%   |
| Zen 3            | 2         | 4.35%   |
| Tremont          | 2         | 4.35%   |
| Haswell          | 2         | 4.35%   |
| Broadwell        | 2         | 4.35%   |
| Unknown          | 2         | 4.35%   |
| Zen+             | 1         | 2.17%   |
| Goldmont plus    | 1         | 2.17%   |
| Excavator        | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 26        | 48.15%  |
| Nvidia            | 16        | 29.63%  |
| AMD               | 11        | 20.37%  |
| ASPEED Technology | 1         | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 5.36%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 3.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 3.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 3.57%   |
| Intel JasperLake [UHD Graphics]                                               | 2         | 3.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 3.57%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 2         | 3.57%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 1.79%   |
| Nvidia TU117GL [T400 4GB]                                                     | 1         | 1.79%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 1.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.79%   |
| Nvidia GP104GL [Quadro P4000]                                                 | 1         | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1         | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1         | 1.79%   |
| Nvidia GM206GL [Quadro M2000]                                                 | 1         | 1.79%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 1.79%   |
| Nvidia GA106 [Geforce RTX 3050]                                               | 1         | 1.79%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                            | 1         | 1.79%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 1.79%   |
| Nvidia G92 [GeForce 9800 GT]                                                  | 1         | 1.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.79%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 1         | 1.79%   |
| Intel HD Graphics P530                                                        | 1         | 1.79%   |
| Intel HD Graphics 630                                                         | 1         | 1.79%   |
| Intel HD Graphics 5500                                                        | 1         | 1.79%   |
| Intel HD Graphics 530                                                         | 1         | 1.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.79%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 1.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 1.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.79%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 1.79%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 1.79%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                              | 1         | 1.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.79%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.79%   |
| AMD Renoir                                                                    | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 39.13%  |
| 1 x Nvidia     | 10        | 21.74%  |
| 1 x AMD        | 7         | 15.22%  |
| Intel + Nvidia | 5         | 10.87%  |
| Intel + AMD    | 2         | 4.35%   |
| Other          | 1         | 2.17%   |
| 2 x Nvidia     | 1         | 2.17%   |
| 2 x AMD        | 1         | 2.17%   |
| AMD + ASPEED   | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 36        | 78.26%  |
| Proprietary | 7         | 15.22%  |
| Unknown     | 3         | 6.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 45.65%  |
| 7.01-8.0   | 6         | 13.04%  |
| 3.01-4.0   | 4         | 8.7%    |
| 1.01-2.0   | 4         | 8.7%    |
| 5.01-6.0   | 3         | 6.52%   |
| 0.01-0.5   | 3         | 6.52%   |
| 8.01-16.0  | 2         | 4.35%   |
| 2.01-3.0   | 1         | 2.17%   |
| 16.01-24.0 | 1         | 2.17%   |
| 0.51-1.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 8         | 15.38%  |
| Samsung Electronics  | 6         | 11.54%  |
| Chimei Innolux       | 5         | 9.62%   |
| Dell                 | 4         | 7.69%   |
| LG Display           | 3         | 5.77%   |
| Goldstar             | 3         | 5.77%   |
| Sharp                | 2         | 3.85%   |
| Lenovo               | 2         | 3.85%   |
| AU Optronics         | 2         | 3.85%   |
| Acer                 | 2         | 3.85%   |
| Unknown              | 1         | 1.92%   |
| STD                  | 1         | 1.92%   |
| Sony                 | 1         | 1.92%   |
| Philips              | 1         | 1.92%   |
| Panasonic            | 1         | 1.92%   |
| OUT                  | 1         | 1.92%   |
| Hewlett-Packard      | 1         | 1.92%   |
| Haier                | 1         | 1.92%   |
| Gigabyte Technology  | 1         | 1.92%   |
| Deco Gear            | 1         | 1.92%   |
| CSO                  | 1         | 1.92%   |
| BOE Technology Group | 1         | 1.92%   |
| BenQ                 | 1         | 1.92%   |
| ASUSTek Computer     | 1         | 1.92%   |
| AOC                  | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 2         | 3.64%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 1.82%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1         | 1.82%   |
| Sony TV SNYD703 1360x768                                               | 1         | 1.82%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                | 1         | 1.82%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1         | 1.82%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 510x290mm 23.1-inch   | 1         | 1.82%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1         | 1.82%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch      | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1         | 1.82%   |
| Samsung Electronics LCD Monitor S34J55x 7280x2160                      | 1         | 1.82%   |
| Philips PHL 322E1 PHLC20F 1920x1080 700x390mm 31.5-inch                | 1         | 1.82%   |
| Panasonic TV MEIA296 3840x2160 708x398mm 32.0-inch                     | 1         | 1.82%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1         | 1.82%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch           | 1         | 1.82%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch               | 1         | 1.82%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch             | 1         | 1.82%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch             | 1         | 1.82%   |
| Hewlett-Packard LCD Monitor Pavilion32                                 | 1         | 1.82%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                | 1         | 1.82%   |
| Goldstar LG UltraFine GSM5B11                                          | 1         | 1.82%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 1         | 1.82%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                  | 1         | 1.82%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 1         | 1.82%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                     | 1         | 1.82%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                       | 1         | 1.82%   |
| Dell P2419HC DELA11D 1920x1080 527x296mm 23.8-inch                     | 1         | 1.82%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                      | 1         | 1.82%   |
| Deco Gear DGVIEW220 DGVFFFF 3440x1440 819x346mm 35.0-inch              | 1         | 1.82%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch                  | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1760 1920x1080 381x214mm 17.2-inch       | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch       | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch       | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 45.1%   |
| 3840x2160 (4K)     | 6         | 11.76%  |
| 1366x768 (WXGA)    | 5         | 9.8%    |
| 2560x1440 (QHD)    | 4         | 7.84%   |
| Unknown            | 3         | 5.88%   |
| 1680x1050 (WSXGA+) | 2         | 3.92%   |
| 7280x2160          | 1         | 1.96%   |
| 5120x1440          | 1         | 1.96%   |
| 3440x1440          | 1         | 1.96%   |
| 2160x1350          | 1         | 1.96%   |
| 1920x1200 (WUXGA)  | 1         | 1.96%   |
| 1600x900 (HD+)     | 1         | 1.96%   |
| 1280x768           | 1         | 1.96%   |
| 1280x1024 (SXGA)   | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 11        | 21.57%  |
| 15      | 5         | 9.8%    |
| 27      | 4         | 7.84%   |
| 23      | 4         | 7.84%   |
| 21      | 4         | 7.84%   |
| 31      | 3         | 5.88%   |
| 17      | 3         | 5.88%   |
| 14      | 3         | 5.88%   |
| 72      | 2         | 3.92%   |
| 24      | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| 84      | 1         | 1.96%   |
| 64      | 1         | 1.96%   |
| 52      | 1         | 1.96%   |
| 35      | 1         | 1.96%   |
| 33      | 1         | 1.96%   |
| 20      | 1         | 1.96%   |
| 19      | 1         | 1.96%   |
| 16      | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 34%     |
| 501-600     | 9         | 18%     |
| 401-500     | 5         | 10%     |
| 351-400     | 4         | 8%      |
| 601-700     | 3         | 6%      |
| 201-300     | 3         | 6%      |
| 1501-2000   | 3         | 6%      |
| 1001-1500   | 2         | 4%      |
| Unknown     | 2         | 4%      |
| 801-900     | 1         | 2%      |
| 701-800     | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 34        | 79.07%  |
| 16/10   | 4         | 9.3%    |
| Unknown | 2         | 4.65%   |
| 5/4     | 1         | 2.33%   |
| 4/3     | 1         | 2.33%   |
| 21/9    | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 22%     |
| 201-250        | 7         | 14%     |
| More than 1000 | 5         | 10%     |
| 351-500        | 5         | 10%     |
| 101-110        | 5         | 10%     |
| 301-350        | 4         | 8%      |
| 71-80          | 3         | 6%      |
| 151-200        | 3         | 6%      |
| 121-130        | 3         | 6%      |
| Unknown        | 2         | 4%      |
| 251-300        | 1         | 2%      |
| 131-140        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 14        | 30.43%  |
| 121-160       | 12        | 26.09%  |
| 101-120       | 10        | 21.74%  |
| 161-240       | 4         | 8.7%    |
| More than 240 | 2         | 4.35%   |
| 1-50          | 2         | 4.35%   |
| Unknown       | 2         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 32        | 68.09%  |
| 2     | 8         | 17.02%  |
| 0     | 4         | 8.51%   |
| 5     | 1         | 2.13%   |
| 4     | 1         | 2.13%   |
| 3     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 54.69%  |
| Realtek Semiconductor | 24        | 37.5%   |
| Qualcomm Atheros      | 2         | 3.13%   |
| Tehuti Networks       | 1         | 1.56%   |
| ASUSTek Computer      | 1         | 1.56%   |
| Aquantia              | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 12.94%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 5.88%   |
| Intel Ethernet Controller I225-V                                  | 4         | 4.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 4.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 3.53%   |
| Intel Wireless 8260                                               | 2         | 2.35%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 2.35%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.35%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 2.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.35%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.35%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.18%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.18%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.18%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.18%   |
| Intel Wireless 7265                                               | 1         | 1.18%   |
| Intel Wireless 3160                                               | 1         | 1.18%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.18%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.18%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 1.18%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.18%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.18%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 81.08%  |
| Realtek Semiconductor | 6         | 16.22%  |
| ASUSTek Computer      | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 5         | 13.51%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]         | 4         | 10.81%  |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 3         | 8.11%   |
| Intel Wireless 8260                                      | 2         | 5.41%   |
| Intel Wi-Fi 6 AX200                                      | 2         | 5.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                          | 2         | 5.41%   |
| Intel Cannon Lake PCH CNVi WiFi                          | 2         | 5.41%   |
| Intel Alder Lake-S PCH CNVi WiFi                         | 2         | 5.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                         | 2         | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1         | 2.7%    |
| Realtek RTL8723DE Wireless Network Adapter               | 1         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter          | 1         | 2.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter               | 1         | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 1         | 2.7%    |
| Realtek 802.11n WLAN Adapter                             | 1         | 2.7%    |
| Intel Wireless 7265                                      | 1         | 2.7%    |
| Intel Wireless 3160                                      | 1         | 2.7%    |
| Intel Wi-Fi 6 AX201 160MHz                               | 1         | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                           | 1         | 2.7%    |
| Intel Centrino Wireless-N 2230                           | 1         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 1         | 2.7%    |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]      | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 53.49%  |
| Intel                 | 16        | 37.21%  |
| Qualcomm Atheros      | 2         | 4.65%   |
| Tehuti Networks       | 1         | 2.33%   |
| Aquantia              | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 22.92%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 10.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10.42%  |
| Intel Ethernet Controller I225-V                                  | 4         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6.25%   |
| Intel I210 Gigabit Network Connection                             | 2         | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 4.17%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 4.17%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 2.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.08%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.08%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 2.08%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 2.08%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 2.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 52%     |
| WiFi     | 36        | 48%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 52%     |
| WiFi     | 24        | 48%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 25        | 54.35%  |
| 1     | 15        | 32.61%  |
| 4     | 3         | 6.52%   |
| 3     | 2         | 4.35%   |
| 0     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 76.09%  |
| Yes  | 11        | 23.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 28        | 80%     |
| Realtek Semiconductor      | 2         | 5.71%   |
| Cambridge Silicon Radio    | 2         | 5.71%   |
| Integrated System Solution | 1         | 2.86%   |
| IMC Networks               | 1         | 2.86%   |
| Broadcom                   | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                 | 7         | 20%     |
| Intel AX210 Bluetooth                                 | 5         | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                      | 4         | 11.43%  |
| Intel Bluetooth wireless interface                    | 4         | 11.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4         | 11.43%  |
| Intel AX200 Bluetooth                                 | 2         | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 5.71%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 2.86%   |
| Realtek Bluetooth Radio                               | 1         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 2.86%   |
| Intel Bluetooth Device                                | 1         | 2.86%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 2.86%   |
| IMC Networks Bluetooth Radio                          | 1         | 2.86%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 35        | 46.67%  |
| Nvidia                                       | 15        | 20%     |
| AMD                                          | 11        | 14.67%  |
| Texas Instruments                            | 4         | 5.33%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.33%   |
| Sony                                         | 1         | 1.33%   |
| Realtek Semiconductor                        | 1         | 1.33%   |
| Micro Star International                     | 1         | 1.33%   |
| Logitech                                     | 1         | 1.33%   |
| LG Electronics                               | 1         | 1.33%   |
| Hewlett-Packard                              | 1         | 1.33%   |
| Creative Labs                                | 1         | 1.33%   |
| Corsair                                      | 1         | 1.33%   |
| Blue Microphones                             | 1         | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 6.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 4.6%    |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 3.45%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 3.45%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 3.45%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.3%    |
| Intel Jasper Lake HD Audio                                                 | 2         | 2.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.3%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2.3%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 2.3%    |
| AMD Navi 10 HDMI Audio                                                     | 2         | 2.3%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 1.15%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 1.15%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 1.15%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.15%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.15%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.15%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.15%   |
| Micro Star International USB Audio                                         | 1         | 1.15%   |
| Logitech Headset H340                                                      | 1         | 1.15%   |
| LG Electronics USB Audio                                                   | 1         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.15%   |
| Intel Lewisburg MROM 0                                                     | 1         | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.15%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 5         | 23.81%  |
| Samsung Electronics | 4         | 19.05%  |
| Kingston            | 3         | 14.29%  |
| G.Skill             | 3         | 14.29%  |
| Unknown             | 1         | 4.76%   |
| Team                | 1         | 4.76%   |
| Smart               | 1         | 4.76%   |
| Micron Technology   | 1         | 4.76%   |
| Crucial             | 1         | 4.76%   |
| Corsair             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 4.55%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s          | 1         | 4.55%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s        | 1         | 4.55%   |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s        | 1         | 4.55%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 4.55%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 4.55%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1         | 4.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 4.55%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 4.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 4.55%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s          | 1         | 4.55%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 4.55%   |
| Micron RAM Module 8GB Chip LPDDR4                            | 1         | 4.55%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s        | 1         | 4.55%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 1         | 4.55%   |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 4.55%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s         | 1         | 4.55%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 1         | 4.55%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s      | 1         | 4.55%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s         | 1         | 4.55%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 65%     |
| DDR3   | 3         | 15%     |
| LPDDR4 | 2         | 10%     |
| LPDDR5 | 1         | 5%      |
| DDR5   | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 9         | 45%     |
| SODIMM       | 8         | 40%     |
| Row Of Chips | 2         | 10%     |
| Chip         | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 45.45%  |
| 16384 | 8         | 36.36%  |
| 4096  | 2         | 9.09%   |
| 65536 | 1         | 4.55%   |
| 2048  | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3600    | 4         | 19.05%  |
| 2400    | 3         | 14.29%  |
| 6400    | 2         | 9.52%   |
| 3200    | 2         | 9.52%   |
| 2667    | 2         | 9.52%   |
| 2133    | 2         | 9.52%   |
| 2933    | 1         | 4.76%   |
| 2666    | 1         | 4.76%   |
| 1867    | 1         | 4.76%   |
| 1600    | 1         | 4.76%   |
| 1333    | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-4100 Series | 1         | 33.33%  |
| Seiko Epson WF-3520 Series | 1         | 33.33%  |
| Seiko Epson L3210 Series   | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 16.13%  |
| IMC Networks                           | 4         | 12.9%   |
| Sunplus Innovation Technology          | 2         | 6.45%   |
| Realtek Semiconductor                  | 2         | 6.45%   |
| Microdia                               | 2         | 6.45%   |
| vivo                                   | 1         | 3.23%   |
| Syntek                                 | 1         | 3.23%   |
| Suyin                                  | 1         | 3.23%   |
| Sonix Technology                       | 1         | 3.23%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.23%   |
| Remo Tech                              | 1         | 3.23%   |
| Quanta                                 | 1         | 3.23%   |
| Microsoft                              | 1         | 3.23%   |
| Luxvisions Innotech Limited            | 1         | 3.23%   |
| Logitech                               | 1         | 3.23%   |
| Lite-On Technology                     | 1         | 3.23%   |
| LG Electronics                         | 1         | 3.23%   |
| Generalplus Technology                 | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.23%   |
| Bison Electronics                      | 1         | 3.23%   |
| Acer                                   | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 2         | 6.45%   |
| Chicony Integrated Camera                                      | 2         | 6.45%   |
| vivo V2023                                                     | 1         | 3.23%   |
| Syntek Integrated Camera                                       | 1         | 3.23%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 3.23%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 3.23%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 3.23%   |
| Remo Tech OBSBOT Tiny 4K                                       | 1         | 3.23%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 3.23%   |
| Realtek FULL HD 1080P Webcam                                   | 1         | 3.23%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 3.23%   |
| Microsoft LifeCam VX-2000                                      | 1         | 3.23%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.23%   |
| Microdia CameraA                                               | 1         | 3.23%   |
| Luxvisions Innotech Limited Integrated RGB Camera              | 1         | 3.23%   |
| Logitech Webcam C250                                           | 1         | 3.23%   |
| Lite-On HP HD Camera                                           | 1         | 3.23%   |
| LG LG UltraFine Display Camera                                 | 1         | 3.23%   |
| IMC Networks XHC Camera                                        | 1         | 3.23%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.23%   |
| IMC Networks USB Camera                                        | 1         | 3.23%   |
| IMC Networks Integrated Camera                                 | 1         | 3.23%   |
| Generalplus GENERAL WEBCAM                                     | 1         | 3.23%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 3.23%   |
| Chicony HP HD Camera                                           | 1         | 3.23%   |
| Chicony HD Webcam                                              | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.23%   |
| Bison BisonCam, NB Pro                                         | 1         | 3.23%   |
| Acer Integrated Camera                                         | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 42.86%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |
| Validity Sensors           | 1         | 14.29%  |
| Samsung Electronics        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 28.57%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 28.57%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 14.29%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 14.29%  |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 30        | 65.22%  |
| 1     | 12        | 26.09%  |
| 2     | 2         | 4.35%   |
| 4     | 1         | 2.17%   |
| 3     | 1         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 30.43%  |
| Graphics card            | 4         | 17.39%  |
| Unassigned class         | 3         | 13.04%  |
| Multimedia controller    | 3         | 13.04%  |
| Storage/ide              | 1         | 4.35%   |
| Net/wireless             | 1         | 4.35%   |
| Net/ethernet             | 1         | 4.35%   |
| Communication controller | 1         | 4.35%   |
| Card reader              | 1         | 4.35%   |
| Camera                   | 1         | 4.35%   |

