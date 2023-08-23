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

Total: 69

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | A320M-HDV R4.0              | Desktop     | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP            | 0AECh D                     | Desktop     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Lenovo        | STA7B38870 02               | Server      | [80a2f3d367](https://linux-hardware.org/?probe=80a2f3d367) | Jun 18, 2023 |
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
| 5.14.0-162.6.1.el9_1.x86_64  | 9         | 16.98%  |
| 5.14.0-70.17.1.el9_0.x86_64  | 6         | 11.32%  |
| 5.14.0-162.12.1.el9_1.x86_64 | 5         | 9.43%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 4         | 7.55%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 4         | 7.55%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 4         | 7.55%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 4         | 7.55%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 3         | 5.66%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3         | 5.66%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 3.77%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 2         | 3.77%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 3.77%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 1.89%   |
| 5.14.0-70.17.1.el9_0.aarch64 | 1         | 1.89%   |
| 5.14.0-39.el9.x86_64         | 1         | 1.89%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1         | 1.89%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 51        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 51        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 50        | 98.04%  |
| aarch64 | 1         | 1.96%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 48        | 94.12%  |
| GNOME Classic | 2         | 3.92%   |
| Unknown       | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 34        | 66.67%  |
| X11     | 15        | 29.41%  |
| Tty     | 2         | 3.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 54.9%   |
| GDM     | 22        | 43.14%  |
| SDDM    | 1         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 37        | 72.55%  |
| en_GB | 4         | 7.84%   |
| pt_BR | 3         | 5.88%   |
| en_IN | 2         | 3.92%   |
| ru_RU | 1         | 1.96%   |
| ja_JP | 1         | 1.96%   |
| es_ES | 1         | 1.96%   |
| en_NZ | 1         | 1.96%   |
| en_CA | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 90.2%   |
| BIOS | 5         | 9.8%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 49        | 96.08%  |
| Ext4 | 2         | 3.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 50.98%  |
| GPT     | 23        | 45.1%   |
| MBR     | 2         | 3.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 84.31%  |
| Yes       | 8         | 15.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 86.27%  |
| Yes       | 7         | 13.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 9         | 17.65%  |
| Lenovo                  | 8         | 15.69%  |
| MSI                     | 6         | 11.76%  |
| Hewlett-Packard         | 6         | 11.76%  |
| ASUSTek Computer        | 6         | 11.76%  |
| Gigabyte Technology     | 5         | 9.8%    |
| Unknown                 | 3         | 5.88%   |
| ASRock                  | 2         | 3.92%   |
| Samsung Electronics     | 1         | 1.96%   |
| Razer                   | 1         | 1.96%   |
| Raspberry Pi Foundation | 1         | 1.96%   |
| Intel                   | 1         | 1.96%   |
| Hardkernel              | 1         | 1.96%   |
| Acer                    | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 5.88%   |
| Samsung 730QCJ/730QCR                    | 1         | 1.96%   |
| Razer Blade 15 Mid 2019-Base             | 1         | 1.96%   |
| RPi Raspberry Pi 4 Model B               | 1         | 1.96%   |
| MSI MS-7D54                              | 1         | 1.96%   |
| MSI MS-7C95                              | 1         | 1.96%   |
| MSI MS-7B89                              | 1         | 1.96%   |
| MSI MS-7A71                              | 1         | 1.96%   |
| MSI GP75 Leopard 9SD                     | 1         | 1.96%   |
| MSI GE72VR 7RF                           | 1         | 1.96%   |
| Lenovo ThinkSystem SR950 V3              | 1         | 1.96%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US | 1         | 1.96%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 1.96%   |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00     | 1         | 1.96%   |
| Lenovo ThinkPad Edge E431 62771L7        | 1         | 1.96%   |
| Lenovo ThinkPad E14 20RA001MMZ           | 1         | 1.96%   |
| Lenovo ThinkBook 14-IIL 20SL             | 1         | 1.96%   |
| Lenovo ThinkBook 13s-IWL 20R9            | 1         | 1.96%   |
| Intel H81                                | 1         | 1.96%   |
| HP Z800 Workstation                      | 1         | 1.96%   |
| HP ProBook 640 G2                        | 1         | 1.96%   |
| HP Laptop 14s-dk0xxx                     | 1         | 1.96%   |
| HP EliteBook 855 G7 Notebook PC          | 1         | 1.96%   |
| HP EliteBook 2570p                       | 1         | 1.96%   |
| HP 340S G7                               | 1         | 1.96%   |
| Hardkernel ODROID-H3                     | 1         | 1.96%   |
| Gigabyte X670E AORUS MASTER              | 1         | 1.96%   |
| Gigabyte MU72-SU0-00                     | 1         | 1.96%   |
| Gigabyte H510M H                         | 1         | 1.96%   |
| Gigabyte B550M AORUS PRO-P               | 1         | 1.96%   |
| Gigabyte AERO 15 KD                      | 1         | 1.96%   |
| Dell XPS 17 9710                         | 1         | 1.96%   |
| Dell Precision Tower 5810                | 1         | 1.96%   |
| Dell Precision 7920 Tower                | 1         | 1.96%   |
| Dell Precision 7560                      | 1         | 1.96%   |
| Dell Precision 7510                      | 1         | 1.96%   |
| Dell PowerEdge T30                       | 1         | 1.96%   |
| Dell Latitude E7450                      | 1         | 1.96%   |
| Dell Latitude 3410                       | 1         | 1.96%   |
| Dell Inspiron 5559                       | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 5         | 9.8%    |
| Dell Precision       | 4         | 7.84%   |
| Unknown              | 3         | 5.88%   |
| Lenovo ThinkBook     | 2         | 3.92%   |
| HP EliteBook         | 2         | 3.92%   |
| Dell Latitude        | 2         | 3.92%   |
| ASUS TUF             | 2         | 3.92%   |
| ASUS PRIME           | 2         | 3.92%   |
| Samsung 730QCJ       | 1         | 1.96%   |
| Razer Blade          | 1         | 1.96%   |
| RPi Raspberry        | 1         | 1.96%   |
| MSI MS-7D54          | 1         | 1.96%   |
| MSI MS-7C95          | 1         | 1.96%   |
| MSI MS-7B89          | 1         | 1.96%   |
| MSI MS-7A71          | 1         | 1.96%   |
| MSI GP75             | 1         | 1.96%   |
| MSI GE72VR           | 1         | 1.96%   |
| Lenovo ThinkSystem   | 1         | 1.96%   |
| Intel H81            | 1         | 1.96%   |
| HP Z800              | 1         | 1.96%   |
| HP ProBook           | 1         | 1.96%   |
| HP Laptop            | 1         | 1.96%   |
| HP 340S              | 1         | 1.96%   |
| Hardkernel ODROID-H3 | 1         | 1.96%   |
| Gigabyte X670E       | 1         | 1.96%   |
| Gigabyte MU72-SU0-00 | 1         | 1.96%   |
| Gigabyte H510M       | 1         | 1.96%   |
| Gigabyte B550M       | 1         | 1.96%   |
| Gigabyte AERO        | 1         | 1.96%   |
| Dell XPS             | 1         | 1.96%   |
| Dell PowerEdge       | 1         | 1.96%   |
| Dell Inspiron        | 1         | 1.96%   |
| ASUS Z450LA          | 1         | 1.96%   |
| ASUS VivoBook        | 1         | 1.96%   |
| ASRock Z370          | 1         | 1.96%   |
| ASRock A320M-HDV     | 1         | 1.96%   |
| Acer Aspire          | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 10        | 19.61%  |
| 2021 | 9         | 17.65%  |
| 2022 | 7         | 13.73%  |
| 2020 | 7         | 13.73%  |
| 2017 | 4         | 7.84%   |
| 2016 | 3         | 5.88%   |
| 2015 | 3         | 5.88%   |
| 2023 | 2         | 3.92%   |
| 2018 | 2         | 3.92%   |
| 2014 | 1         | 1.96%   |
| 2013 | 1         | 1.96%   |
| 2012 | 1         | 1.96%   |
| 2010 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 26        | 50.98%  |
| Desktop        | 21        | 41.18%  |
| Server         | 3         | 5.88%   |
| System on chip | 1         | 1.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 45        | 86.54%  |
| Enabled  | 7         | 13.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 19        | 37.25%  |
| 4.01-8.0        | 10        | 19.61%  |
| 32.01-64.0      | 9         | 17.65%  |
| 64.01-256.0     | 6         | 11.76%  |
| 3.01-4.0        | 3         | 5.88%   |
| More than 256.0 | 2         | 3.92%   |
| 24.01-32.0      | 1         | 1.96%   |
| 16.01-24.0      | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 37.74%  |
| 3.01-4.0  | 11        | 20.75%  |
| 4.01-8.0  | 10        | 18.87%  |
| 8.01-16.0 | 7         | 13.21%  |
| 1.01-2.0  | 5         | 9.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 44.23%  |
| 2      | 16        | 30.77%  |
| 3      | 6         | 11.54%  |
| 5      | 4         | 7.69%   |
| 14     | 1         | 1.92%   |
| 6      | 1         | 1.92%   |
| 4      | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 80.39%  |
| Yes       | 10        | 19.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 86.27%  |
| No        | 7         | 13.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 74.51%  |
| No        | 13        | 25.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 65.38%  |
| No        | 18        | 34.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 37.25%  |
| India       | 6         | 11.76%  |
| UK          | 3         | 5.88%   |
| Canada      | 3         | 5.88%   |
| Brazil      | 3         | 5.88%   |
| Turkey      | 2         | 3.92%   |
| Chile       | 2         | 3.92%   |
| Switzerland | 1         | 1.96%   |
| Sri Lanka   | 1         | 1.96%   |
| Spain       | 1         | 1.96%   |
| Russia      | 1         | 1.96%   |
| Norway      | 1         | 1.96%   |
| New Zealand | 1         | 1.96%   |
| Kenya       | 1         | 1.96%   |
| Jordan      | 1         | 1.96%   |
| Japan       | 1         | 1.96%   |
| Indonesia   | 1         | 1.96%   |
| Guatemala   | 1         | 1.96%   |
| Germany     | 1         | 1.96%   |
| Finland     | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Santiago       | 2         | 3.85%   |
| Wildomar       | 1         | 1.92%   |
| Whiteley       | 1         | 1.92%   |
| Wellington     | 1         | 1.92%   |
| Wake Forest    | 1         | 1.92%   |
| Valencia       | 1         | 1.92%   |
| Tokyo          | 1         | 1.92%   |
| Sutton         | 1         | 1.92%   |
| Stratham       | 1         | 1.92%   |
| Stavropol      | 1         | 1.92%   |
| Skien          | 1         | 1.92%   |
| Sao Paulo      | 1         | 1.92%   |
| Sainte-Marie   | 1         | 1.92%   |
| Saint Paul     | 1         | 1.92%   |
| Ribeirao Preto | 1         | 1.92%   |
| Providence     | 1         | 1.92%   |
| Prairieville   | 1         | 1.92%   |
| Piracicaba     | 1         | 1.92%   |
| Pforzheim      | 1         | 1.92%   |
| Oldham         | 1         | 1.92%   |
| New Delhi      | 1         | 1.92%   |
| Nairobi        | 1         | 1.92%   |
| Mohegan Lake   | 1         | 1.92%   |
| Mattapoisett   | 1         | 1.92%   |
| Maltepe        | 1         | 1.92%   |
| Lansing        | 1         | 1.92%   |
| Kolkata        | 1         | 1.92%   |
| Kochi          | 1         | 1.92%   |
| Houston        | 1         | 1.92%   |
| Helsinki       | 1         | 1.92%   |
| Guatemala City | 1         | 1.92%   |
| Ghaziabad      | 1         | 1.92%   |
| Fort Collins   | 1         | 1.92%   |
| Ernakulam      | 1         | 1.92%   |
| East Peoria    | 1         | 1.92%   |
| Denver         | 1         | 1.92%   |
| Denizli        | 1         | 1.92%   |
| Corona         | 1         | 1.92%   |
| Colombo        | 1         | 1.92%   |
| Christiansburg | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 17        | 21     | 17.89%  |
| Seagate                   | 11        | 15     | 11.58%  |
| WDC                       | 10        | 17     | 10.53%  |
| SanDisk                   | 7         | 7      | 7.37%   |
| Toshiba                   | 4         | 4      | 4.21%   |
| Kingston                  | 4         | 4      | 4.21%   |
| Unknown                   | 3         | 5      | 3.16%   |
| SK hynix                  | 3         | 3      | 3.16%   |
| Phison                    | 3         | 3      | 3.16%   |
| Micron Technology         | 3         | 3      | 3.16%   |
| KIOXIA                    | 3         | 4      | 3.16%   |
| Intel                     | 3         | 4      | 3.16%   |
| HGST                      | 3         | 3      | 3.16%   |
| China                     | 3         | 3      | 3.16%   |
| SABRENT                   | 2         | 2      | 2.11%   |
| KingSpec                  | 2         | 2      | 2.11%   |
| Crucial                   | 2         | 3      | 2.11%   |
| ADATA Technology          | 2         | 2      | 2.11%   |
| XUM                       | 1         | 1      | 1.05%   |
| SSSTC                     | 1         | 1      | 1.05%   |
| PNY                       | 1         | 1      | 1.05%   |
| Plextor                   | 1         | 1      | 1.05%   |
| Micron/Crucial Technology | 1         | 2      | 1.05%   |
| Hitachi                   | 1         | 1      | 1.05%   |
| Golden                    | 1         | 1      | 1.05%   |
| Gigabyte Technology       | 1         | 1      | 1.05%   |
| Fantom                    | 1         | 1      | 1.05%   |
| A-DATA Technology         | 1         | 1      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 2.78%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 1.85%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 2         | 1.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 1.85%   |
| SABRENT Disk 1TB                                    | 2         | 1.85%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                          | 2         | 1.85%   |
| HGST HTS721010A9E630 1TB                            | 2         | 1.85%   |
| XUM HX256GSSDSATA3 256GB                            | 1         | 0.93%   |
| WDC WDBA3V5000ANC-WRSN 500GB                        | 1         | 0.93%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 1         | 0.93%   |
| WDC WD5000AVDS-63U7B0 500GB                         | 1         | 0.93%   |
| WDC WD5000AVCS-632DY1 500GB                         | 1         | 0.93%   |
| WDC WD50 00LPVX-22V0TT0 500GB                       | 1         | 0.93%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1         | 0.93%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 0.93%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1         | 0.93%   |
| WDC WD141KFGX-68FH9N0 14TB                          | 1         | 0.93%   |
| WDC WD140EFGX-68B0GN0 14TB                          | 1         | 0.93%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.93%   |
| WDC WD10SPSX-00A6WT0 1TB                            | 1         | 0.93%   |
| WDC WD10JPLX-00MBPT0 1TB                            | 1         | 0.93%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 0.93%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 1         | 0.93%   |
| WDC WD100EFAX-68LHPN0 10TB                          | 1         | 0.93%   |
| Unknown SDU1  64GB                                  | 1         | 0.93%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 0.93%   |
| Unknown SD/MMC/M.S.PRO 32GB                         | 1         | 0.93%   |
| Unknown SD/MMC 2GB                                  | 1         | 0.93%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 1         | 0.93%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.93%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 0.93%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                      | 1         | 0.93%   |
| SK hynix SHGP31-1000GM 1TB                          | 1         | 0.93%   |
| SK hynix SC401 SATA 512GB SSD                       | 1         | 0.93%   |
| SK hynix NVMe SSD Drive 1024GB                      | 1         | 0.93%   |
| Seagate ST9250315AS 250GB                           | 1         | 0.93%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1         | 0.93%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 15     | 36.67%  |
| WDC     | 9         | 16     | 30%     |
| Toshiba | 4         | 4      | 13.33%  |
| HGST    | 3         | 3      | 10%     |
| Unknown | 1         | 1      | 3.33%   |
| Hitachi | 1         | 1      | 3.33%   |
| Fantom  | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 32%     |
| China               | 3         | 3      | 12%     |
| SanDisk             | 2         | 2      | 8%      |
| Kingston            | 2         | 2      | 8%      |
| KingSpec            | 2         | 2      | 8%      |
| Crucial             | 2         | 2      | 8%      |
| XUM                 | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| Plextor             | 1         | 1      | 4%      |
| Intel               | 1         | 2      | 4%      |
| Gigabyte Technology | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 35        | 43     | 42.17%  |
| HDD     | 23        | 41     | 27.71%  |
| SSD     | 22        | 27     | 26.51%  |
| Unknown | 2         | 4      | 2.41%   |
| MMC     | 1         | 1      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 35        | 41     | 46.67%  |
| SATA | 33        | 65     | 44%     |
| SAS  | 6         | 9      | 8%      |
| MMC  | 1         | 1      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 27     | 42.22%  |
| 0.51-1.0   | 16        | 22     | 35.56%  |
| 4.01-10.0  | 3         | 6      | 6.67%   |
| 3.01-4.0   | 2         | 4      | 4.44%   |
| 10.01-20.0 | 2         | 4      | 4.44%   |
| 1.01-2.0   | 2         | 3      | 4.44%   |
| 2.01-3.0   | 1         | 2      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 32.69%  |
| 251-500        | 13        | 25%     |
| 501-1000       | 9         | 17.31%  |
| 1001-2000      | 6         | 11.54%  |
| More than 3000 | 3         | 5.77%   |
| 51-100         | 3         | 5.77%   |
| Unknown        | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 38.46%  |
| 21-50          | 13        | 25%     |
| 51-100         | 7         | 13.46%  |
| 251-500        | 5         | 9.62%   |
| 101-250        | 3         | 5.77%   |
| More than 3000 | 2         | 3.85%   |
| 1001-2000      | 1         | 1.92%   |
| Unknown        | 1         | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB   | 1         | 1      | 20%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 20%     |
| Seagate ST1000DM010-2EP102 1TB  | 1         | 1      | 20%     |
| Intel SSDSC2BA800G4R 800GB      | 1         | 2      | 20%     |
| Crucial CT1000BX500SSD1 1TB     | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Intel   | 1         | 2      | 20%     |
| Crucial | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 50%     |
| HDD  | 2         | 3      | 50%     |

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
| Detected | 31        | 63     | 54.39%  |
| Works    | 22        | 47     | 38.6%   |
| Malfunc  | 4         | 6      | 7.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 34        | 42.5%   |
| Samsung Electronics         | 10        | 12.5%   |
| AMD                         | 9         | 11.25%  |
| SanDisk                     | 6         | 7.5%    |
| Phison Electronics          | 3         | 3.75%   |
| Micron Technology           | 3         | 3.75%   |
| KIOXIA                      | 3         | 3.75%   |
| ADATA Technology            | 3         | 3.75%   |
| SK hynix                    | 2         | 2.5%    |
| Micron/Crucial Technology   | 2         | 2.5%    |
| Kingston Technology Company | 2         | 2.5%    |
| Broadcom / LSI              | 2         | 2.5%    |
| ASMedia Technology          | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 6.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 4         | 4.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 4         | 4.55%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 3.41%   |
| Intel SATA Controller [RAID mode]                                             | 3         | 3.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 3.41%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 2.27%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 2         | 2.27%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 2.27%   |
| Phison E12 NVMe Controller                                                    | 2         | 2.27%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 2         | 2.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 2.27%   |
| Intel SSD 660P Series                                                         | 2         | 2.27%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 2         | 2.27%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 2.27%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 2         | 2.27%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 2         | 2.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 2.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 2.27%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 1.14%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                            | 1         | 1.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.14%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 1.14%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 1.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 1.14%   |
| Micron 7450 PRO NVMe SSD                                                      | 1         | 1.14%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 1.14%   |
| Micron 2200S NVMe SSD [Cassandra]                                             | 1         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 1.14%   |
| Kingston Company KC3000/Renegade NVMe SSD                                     | 1         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation         | 1         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.14%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 34        | 41.98%  |
| SATA | 34        | 41.98%  |
| RAID | 11        | 13.58%  |
| SAS  | 1         | 1.23%   |
| IDE  | 1         | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 78.43%  |
| AMD    | 10        | 19.61%  |
| ARM    | 1         | 1.96%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 3.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 3.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 3.92%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 3.92%   |
| Intel Xeon W-11855M CPU @ 3.20GHz       | 1         | 1.96%   |
| Intel Xeon Silver 4310 CPU @ 2.10GHz    | 1         | 1.96%   |
| Intel Xeon Platinum 8468H               | 1         | 1.96%   |
| Intel Xeon Platinum 8168 CPU @ 2.70GHz  | 1         | 1.96%   |
| Intel Xeon CPU X5570 @ 2.93GHz          | 1         | 1.96%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz     | 1         | 1.96%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz     | 1         | 1.96%   |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1         | 1.96%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.96%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.96%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.96%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1         | 1.96%   |
| Intel Core i5-3470S CPU @ 2.90GHz       | 1         | 1.96%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.96%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 1         | 1.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.96%   |
| Intel Celeron N5105 @ 2.00GHz           | 1         | 1.96%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 1         | 1.96%   |
| Intel 13th Gen Core i5-13600K           | 1         | 1.96%   |
| Intel 12th Gen Core i9-12900K           | 1         | 1.96%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.96%   |
| Intel 12th Gen Core i5-1235U            | 1         | 1.96%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz | 1         | 1.96%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz | 1         | 1.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 1.96%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 1         | 1.96%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz | 1         | 1.96%   |
| ARM Processor                           | 1         | 1.96%   |
| AMD Ryzen 9 7900X 12-Core Processor     | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 10        | 19.61%  |
| Intel Core i5        | 10        | 19.61%  |
| Intel Core i7        | 9         | 17.65%  |
| Intel Xeon           | 4         | 7.84%   |
| AMD Ryzen 5          | 4         | 7.84%   |
| AMD Ryzen 9          | 3         | 5.88%   |
| Intel Xeon Platinum  | 2         | 3.92%   |
| Intel Core i3        | 2         | 3.92%   |
| Intel Celeron        | 2         | 3.92%   |
| Intel Xeon Silver    | 1         | 1.96%   |
| Intel Pentium Silver | 1         | 1.96%   |
| AMD Ryzen 7 PRO      | 1         | 1.96%   |
| AMD Athlon X4        | 1         | 1.96%   |
| AMD A4               | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 17        | 33.33%  |
| 2      | 10        | 19.61%  |
| 8      | 8         | 15.69%  |
| 6      | 7         | 13.73%  |
| 12     | 5         | 9.8%    |
| 384    | 1         | 1.96%   |
| 48     | 1         | 1.96%   |
| 14     | 1         | 1.96%   |
| 10     | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 94.12%  |
| 2      | 2         | 3.92%   |
| 8      | 1         | 1.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 80.39%  |
| 1      | 10        | 19.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 7.84%   |
| 0x806d1    | 4         | 7.84%   |
| 0x306a9    | 4         | 7.84%   |
| 0x08701021 | 3         | 5.88%   |
| 0xa0671    | 2         | 3.92%   |
| 0x906ea    | 2         | 3.92%   |
| 0x906e9    | 2         | 3.92%   |
| 0x906c0    | 2         | 3.92%   |
| 0x706e5    | 2         | 3.92%   |
| 0x506e3    | 2         | 3.92%   |
| 0x406e3    | 2         | 3.92%   |
| 0xb0671    | 1         | 1.96%   |
| 0x906ed    | 1         | 1.96%   |
| 0x906a4    | 1         | 1.96%   |
| 0x906a3    | 1         | 1.96%   |
| 0x90672    | 1         | 1.96%   |
| 0x806f6    | 1         | 1.96%   |
| 0x706a8    | 1         | 1.96%   |
| 0x606a6    | 1         | 1.96%   |
| 0x50654    | 1         | 1.96%   |
| 0x406f1    | 1         | 1.96%   |
| 0x40651    | 1         | 1.96%   |
| 0x306d4    | 1         | 1.96%   |
| 0x306c3    | 1         | 1.96%   |
| 0x106a5    | 1         | 1.96%   |
| 0x0a601203 | 1         | 1.96%   |
| 0x0a50000c | 1         | 1.96%   |
| 0x0a20120a | 1         | 1.96%   |
| 0x08600106 | 1         | 1.96%   |
| 0x08108109 | 1         | 1.96%   |
| 0x06006705 | 1         | 1.96%   |
| 0x0600611a | 1         | 1.96%   |
| Unknown    | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 17.65%  |
| Icelake          | 9         | 17.65%  |
| Skylake          | 5         | 9.8%    |
| Zen 2            | 4         | 7.84%   |
| IvyBridge        | 4         | 7.84%   |
| Alderlake Hybrid | 4         | 7.84%   |
| Zen 3            | 2         | 3.92%   |
| Tremont          | 2         | 3.92%   |
| Haswell          | 2         | 3.92%   |
| Excavator        | 2         | 3.92%   |
| Broadwell        | 2         | 3.92%   |
| Unknown          | 2         | 3.92%   |
| Zen+             | 1         | 1.96%   |
| Sapphire Rapids  | 1         | 1.96%   |
| Nehalem          | 1         | 1.96%   |
| Goldmont plus    | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 28        | 46.67%  |
| Nvidia            | 17        | 28.33%  |
| AMD               | 13        | 21.67%  |
| ASPEED Technology | 2         | 3.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 4.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 3.23%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 3.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 3.23%   |
| Intel JasperLake [UHD Graphics]                                               | 2         | 3.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 3.23%   |
| Intel HD Graphics 630                                                         | 2         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 3.23%   |
| ASPEED Technology ASPEED Graphics Family                                      | 2         | 3.23%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 2         | 3.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 3.23%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 1.61%   |
| Nvidia TU117GL [T400 4GB]                                                     | 1         | 1.61%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 1.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.61%   |
| Nvidia GP104GL [Quadro P4000]                                                 | 1         | 1.61%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1         | 1.61%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1         | 1.61%   |
| Nvidia GM206GL [Quadro M2000]                                                 | 1         | 1.61%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 1.61%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 1         | 1.61%   |
| Nvidia GA106 [Geforce RTX 3050]                                               | 1         | 1.61%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                            | 1         | 1.61%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 1.61%   |
| Nvidia G92 [GeForce 9800 GT]                                                  | 1         | 1.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.61%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 1         | 1.61%   |
| Intel HD Graphics P530                                                        | 1         | 1.61%   |
| Intel HD Graphics 5500                                                        | 1         | 1.61%   |
| Intel HD Graphics 530                                                         | 1         | 1.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.61%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 1.61%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 1.61%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.61%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                              | 1         | 1.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 37.25%  |
| 1 x Nvidia     | 11        | 21.57%  |
| 1 x AMD        | 8         | 15.69%  |
| Intel + Nvidia | 5         | 9.8%    |
| Intel + AMD    | 3         | 5.88%   |
| Other          | 1         | 1.96%   |
| 2 x Nvidia     | 1         | 1.96%   |
| 2 x AMD        | 1         | 1.96%   |
| 1 x ASPEED     | 1         | 1.96%   |
| AMD + ASPEED   | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 80.39%  |
| Proprietary | 7         | 13.73%  |
| Unknown     | 3         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 45.1%   |
| 7.01-8.0   | 7         | 13.73%  |
| 1.01-2.0   | 6         | 11.76%  |
| 3.01-4.0   | 4         | 7.84%   |
| 5.01-6.0   | 3         | 5.88%   |
| 0.01-0.5   | 3         | 5.88%   |
| 8.01-16.0  | 2         | 3.92%   |
| 2.01-3.0   | 1         | 1.96%   |
| 16.01-24.0 | 1         | 1.96%   |
| 0.51-1.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 8         | 14.29%  |
| BOE                  | 8         | 14.29%  |
| Dell                 | 5         | 8.93%   |
| Chimei Innolux       | 5         | 8.93%   |
| LG Display           | 3         | 5.36%   |
| Goldstar             | 3         | 5.36%   |
| Sharp                | 2         | 3.57%   |
| Lenovo               | 2         | 3.57%   |
| AU Optronics         | 2         | 3.57%   |
| Acer                 | 2         | 3.57%   |
| Vizio                | 1         | 1.79%   |
| Unknown              | 1         | 1.79%   |
| STD                  | 1         | 1.79%   |
| Sony                 | 1         | 1.79%   |
| Philips              | 1         | 1.79%   |
| Panasonic            | 1         | 1.79%   |
| OUT                  | 1         | 1.79%   |
| Hewlett-Packard      | 1         | 1.79%   |
| Haier                | 1         | 1.79%   |
| Gigabyte Technology  | 1         | 1.79%   |
| Deco Gear            | 1         | 1.79%   |
| CSO                  | 1         | 1.79%   |
| BOE Technology Group | 1         | 1.79%   |
| BenQ                 | 1         | 1.79%   |
| ASUSTek Computer     | 1         | 1.79%   |
| AOC                  | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 2         | 3.39%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 1         | 1.69%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 1.69%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1         | 1.69%   |
| Sony TV SNYD703 1360x768                                               | 1         | 1.69%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                | 1         | 1.69%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch   | 1         | 1.69%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch   | 1         | 1.69%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1         | 1.69%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch      | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1         | 1.69%   |
| Samsung Electronics LCD Monitor S34J55x 7280x2160                      | 1         | 1.69%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                | 1         | 1.69%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 1         | 1.69%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1         | 1.69%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch           | 1         | 1.69%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch               | 1         | 1.69%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch             | 1         | 1.69%   |
| Lenovo LCD Monitor LEN1144 1920x1080 520x320mm 24.0-inch               | 1         | 1.69%   |
| Hewlett-Packard LCD Monitor Pavilion32                                 | 1         | 1.69%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                | 1         | 1.69%   |
| Goldstar UltraFine GSM5B11 2560x2880 600x340mm 27.2-inch               | 1         | 1.69%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 1         | 1.69%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                  | 1         | 1.69%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 1         | 1.69%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                     | 1         | 1.69%   |
| Dell S2318HN/NX DELD0BF 1920x1080 509x286mm 23.0-inch                  | 1         | 1.69%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                       | 1         | 1.69%   |
| Dell P2419HC DELA11D 1920x1080 527x296mm 23.8-inch                     | 1         | 1.69%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                      | 1         | 1.69%   |
| Deco Gear DGVIEW220 DGVFFFF 3440x1440 819x346mm 35.0-inch              | 1         | 1.69%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch                  | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1760 1920x1080 381x214mm 17.2-inch       | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 25        | 45.45%  |
| 3840x2160 (4K)     | 6         | 10.91%  |
| 1366x768 (WXGA)    | 6         | 10.91%  |
| 2560x1440 (QHD)    | 4         | 7.27%   |
| Unknown            | 3         | 5.45%   |
| 1680x1050 (WSXGA+) | 2         | 3.64%   |
| 1280x1024 (SXGA)   | 2         | 3.64%   |
| 7280x2160          | 1         | 1.82%   |
| 5120x1440          | 1         | 1.82%   |
| 3440x1440          | 1         | 1.82%   |
| 2160x1350          | 1         | 1.82%   |
| 1920x1200 (WUXGA)  | 1         | 1.82%   |
| 1600x900 (HD+)     | 1         | 1.82%   |
| 1280x768           | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 12        | 21.82%  |
| 23      | 5         | 9.09%   |
| 15      | 5         | 9.09%   |
| 27      | 4         | 7.27%   |
| 21      | 4         | 7.27%   |
| 17      | 4         | 7.27%   |
| 31      | 3         | 5.45%   |
| 14      | 3         | 5.45%   |
| 72      | 2         | 3.64%   |
| 24      | 2         | 3.64%   |
| Unknown | 2         | 3.64%   |
| 84      | 1         | 1.82%   |
| 64      | 1         | 1.82%   |
| 52      | 1         | 1.82%   |
| 49      | 1         | 1.82%   |
| 35      | 1         | 1.82%   |
| 33      | 1         | 1.82%   |
| 20      | 1         | 1.82%   |
| 19      | 1         | 1.82%   |
| 16      | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 33.33%  |
| 501-600     | 10        | 18.52%  |
| 401-500     | 5         | 9.26%   |
| 351-400     | 4         | 7.41%   |
| 201-300     | 4         | 7.41%   |
| 601-700     | 3         | 5.56%   |
| 1501-2000   | 3         | 5.56%   |
| 1001-1500   | 3         | 5.56%   |
| Unknown     | 2         | 3.7%    |
| 801-900     | 1         | 1.85%   |
| 701-800     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 37        | 78.72%  |
| 16/10   | 4         | 8.51%   |
| 5/4     | 2         | 4.26%   |
| Unknown | 2         | 4.26%   |
| 4/3     | 1         | 2.13%   |
| 21/9    | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 20.37%  |
| 201-250        | 8         | 14.81%  |
| More than 1000 | 6         | 11.11%  |
| 351-500        | 5         | 9.26%   |
| 101-110        | 5         | 9.26%   |
| 71-80          | 4         | 7.41%   |
| 301-350        | 4         | 7.41%   |
| 151-200        | 3         | 5.56%   |
| 121-130        | 3         | 5.56%   |
| Unknown        | 2         | 3.7%    |
| 251-300        | 1         | 1.85%   |
| 141-150        | 1         | 1.85%   |
| 131-140        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 16        | 32%     |
| 121-160       | 12        | 24%     |
| 101-120       | 11        | 22%     |
| 161-240       | 4         | 8%      |
| 1-50          | 3         | 6%      |
| More than 240 | 2         | 4%      |
| Unknown       | 2         | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 69.23%  |
| 2     | 9         | 17.31%  |
| 0     | 4         | 7.69%   |
| 5     | 1         | 1.92%   |
| 4     | 1         | 1.92%   |
| 3     | 1         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 50.7%   |
| Realtek Semiconductor | 26        | 36.62%  |
| Qualcomm Atheros      | 3         | 4.23%   |
| Broadcom              | 2         | 2.82%   |
| Tehuti Networks       | 1         | 1.41%   |
| IBM                   | 1         | 1.41%   |
| ASUSTek Computer      | 1         | 1.41%   |
| Aquantia              | 1         | 1.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 13.98%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 5.38%   |
| Intel Ethernet Controller I225-V                                  | 4         | 4.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 4.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 3.23%   |
| Intel Wireless 8260                                               | 2         | 2.15%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 2.15%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.15%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.15%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 2.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.15%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.15%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.08%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.08%   |
| Intel Wireless 7265                                               | 1         | 1.08%   |
| Intel Wireless 3160                                               | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.08%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.08%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 1.08%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.08%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 76.92%  |
| Realtek Semiconductor | 6         | 15.38%  |
| Qualcomm Atheros      | 1         | 2.56%   |
| Broadcom              | 1         | 2.56%   |
| ASUSTek Computer      | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 5         | 12.82%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4         | 10.26%  |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 7.69%   |
| Intel Wireless 8260                                        | 2         | 5.13%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 5.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 2         | 5.13%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 5.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 2         | 5.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 2         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.56%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1         | 2.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 2.56%   |
| Realtek 802.11n WLAN Adapter                               | 1         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 2.56%   |
| Intel Wireless 7265                                        | 1         | 2.56%   |
| Intel Wireless 3160                                        | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                 | 1         | 2.56%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 2.56%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 2.56%   |
| Broadcom BCM4321 802.11b/g/n                               | 1         | 2.56%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]        | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 51.02%  |
| Intel                 | 17        | 34.69%  |
| Qualcomm Atheros      | 2         | 4.08%   |
| Broadcom              | 2         | 4.08%   |
| Tehuti Networks       | 1         | 2.04%   |
| IBM                   | 1         | 2.04%   |
| Aquantia              | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 24.07%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 9.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.26%   |
| Intel Ethernet Controller I225-V                                  | 4         | 7.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.56%   |
| Intel I210 Gigabit Network Connection                             | 2         | 3.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 3.7%    |
| Intel 82574L Gigabit Network Connection                           | 2         | 3.7%    |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 1.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.85%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.85%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 1.85%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.85%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.85%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.85%   |
| IBM RNDIS/CDC ETHER                                               | 1         | 1.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 44        | 53.66%  |
| WiFi     | 38        | 46.34%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 53.7%   |
| WiFi     | 25        | 46.3%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 50.98%  |
| 1     | 17        | 33.33%  |
| 4     | 4         | 7.84%   |
| 3     | 3         | 5.88%   |
| 0     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 72.55%  |
| Yes  | 14        | 27.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 28        | 77.78%  |
| Realtek Semiconductor      | 2         | 5.56%   |
| Cambridge Silicon Radio    | 2         | 5.56%   |
| Broadcom                   | 2         | 5.56%   |
| Integrated System Solution | 1         | 2.78%   |
| IMC Networks               | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                 | 7         | 19.44%  |
| Intel AX210 Bluetooth                                 | 5         | 13.89%  |
| Intel Wireless-AC 3168 Bluetooth                      | 4         | 11.11%  |
| Intel Bluetooth wireless interface                    | 4         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4         | 11.11%  |
| Intel AX200 Bluetooth                                 | 2         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 2.78%   |
| Realtek Bluetooth Radio                               | 1         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 2.78%   |
| Intel Bluetooth Device                                | 1         | 2.78%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 2.78%   |
| IMC Networks Bluetooth Radio                          | 1         | 2.78%   |
| Broadcom HP Portable SoftSailing                      | 1         | 2.78%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 38        | 46.34%  |
| Nvidia                                       | 16        | 19.51%  |
| AMD                                          | 13        | 15.85%  |
| Texas Instruments                            | 5         | 6.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.22%   |
| Sony                                         | 1         | 1.22%   |
| Realtek Semiconductor                        | 1         | 1.22%   |
| Micro Star International                     | 1         | 1.22%   |
| Logitech                                     | 1         | 1.22%   |
| LG Electronics                               | 1         | 1.22%   |
| Hewlett-Packard                              | 1         | 1.22%   |
| Creative Labs                                | 1         | 1.22%   |
| Corsair                                      | 1         | 1.22%   |
| Blue Microphones                             | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 6.32%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4         | 4.21%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 4.21%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 3.16%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 3.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 3.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.16%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.11%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.11%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 2.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.11%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.11%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 2.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 2.11%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 2.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 2.11%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 1.05%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 1.05%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 1.05%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.05%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.05%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.05%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.05%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.05%   |
| Micro Star International USB Audio                                         | 1         | 1.05%   |
| Logitech Headset H340                                                      | 1         | 1.05%   |
| LG Electronics USB Audio                                                   | 1         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 29.17%  |
| Samsung Electronics | 4         | 16.67%  |
| Kingston            | 3         | 12.5%   |
| G.Skill             | 3         | 12.5%   |
| Unknown             | 1         | 4.17%   |
| Team                | 1         | 4.17%   |
| Smart               | 1         | 4.17%   |
| Micron Technology   | 1         | 4.17%   |
| Elpida              | 1         | 4.17%   |
| Crucial             | 1         | 4.17%   |
| Corsair             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 3.7%    |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s          | 1         | 3.7%    |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 3.7%    |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s        | 1         | 3.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.7%    |
| SK hynix RAM HMCG94MEBRA123N 64GB DIMM DDR5 4800MT/s         | 1         | 3.7%    |
| SK hynix RAM HMCG94MEBRA121N 64GB DIMM DDR5 4800MT/s         | 1         | 3.7%    |
| SK hynix RAM HMCG94MEBRA109N 64GB DIMM DDR5 4800MT/s         | 1         | 3.7%    |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s        | 1         | 3.7%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.7%    |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 3.7%    |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1         | 3.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 3.7%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 3.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.7%    |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s          | 1         | 3.7%    |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.7%    |
| Micron RAM Module 8GB Chip LPDDR4                            | 1         | 3.7%    |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s        | 1         | 3.7%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 1         | 3.7%    |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 3.7%    |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s         | 1         | 3.7%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 1         | 3.7%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 1         | 3.7%    |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 1         | 3.7%    |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s         | 1         | 3.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 59.09%  |
| DDR3   | 4         | 18.18%  |
| LPDDR4 | 2         | 9.09%   |
| DDR5   | 2         | 9.09%   |
| LPDDR5 | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 10        | 45.45%  |
| SODIMM       | 9         | 40.91%  |
| Row Of Chips | 2         | 9.09%   |
| Chip         | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 41.67%  |
| 16384 | 8         | 33.33%  |
| 4096  | 3         | 12.5%   |
| 65536 | 2         | 8.33%   |
| 2048  | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3600    | 4         | 17.39%  |
| 2400    | 3         | 13.04%  |
| 6400    | 2         | 8.7%    |
| 3200    | 2         | 8.7%    |
| 2667    | 2         | 8.7%    |
| 2133    | 2         | 8.7%    |
| 1600    | 2         | 8.7%    |
| 4800    | 1         | 4.35%   |
| 2933    | 1         | 4.35%   |
| 2666    | 1         | 4.35%   |
| 1867    | 1         | 4.35%   |
| 1333    | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

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
| Chicony Electronics                    | 6         | 18.75%  |
| IMC Networks                           | 4         | 12.5%   |
| Sunplus Innovation Technology          | 2         | 6.25%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Microdia                               | 2         | 6.25%   |
| Bison Electronics                      | 2         | 6.25%   |
| vivo                                   | 1         | 3.13%   |
| Syntek                                 | 1         | 3.13%   |
| Suyin                                  | 1         | 3.13%   |
| Sonix Technology                       | 1         | 3.13%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.13%   |
| Remo Tech                              | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Microsoft                              | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| Logitech                               | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| LG Electronics                         | 1         | 3.13%   |
| Generalplus Technology                 | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 2         | 6.25%   |
| Chicony Integrated Camera                                      | 2         | 6.25%   |
| vivo V2023                                                     | 1         | 3.13%   |
| Syntek Integrated Camera                                       | 1         | 3.13%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 3.13%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 3.13%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 3.13%   |
| Remo Tech OBSBOT Tiny 4K                                       | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 3.13%   |
| Realtek FULL HD 1080P Webcam                                   | 1         | 3.13%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 3.13%   |
| Microsoft LifeCam VX-2000                                      | 1         | 3.13%   |
| Microdia USB 2.0 Camera                                        | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.13%   |
| Luxvisions Innotech Limited Integrated RGB Camera              | 1         | 3.13%   |
| Logitech Webcam C250                                           | 1         | 3.13%   |
| Lite-On HP HD Camera                                           | 1         | 3.13%   |
| LG LG UltraFine Display Camera                                 | 1         | 3.13%   |
| IMC Networks XHC Camera                                        | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.13%   |
| IMC Networks USB Camera                                        | 1         | 3.13%   |
| IMC Networks Integrated Camera                                 | 1         | 3.13%   |
| Generalplus WEB CAM                                            | 1         | 3.13%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 3.13%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 3.13%   |
| Chicony HP HD Camera                                           | 1         | 3.13%   |
| Chicony HD Webcam                                              | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.13%   |
| Bison Integrated Camera                                        | 1         | 3.13%   |
| Bison BisonCam, NB Pro                                         | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 37.5%   |
| Validity Sensors           | 2         | 25%     |
| Shenzhen Goodix Technology | 2         | 25%     |
| Samsung Electronics        | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 25%     |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 12.5%   |
| Validity Sensors VFS491                                   | 1         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 12.5%   |

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
| 0     | 32        | 62.75%  |
| 1     | 14        | 27.45%  |
| 2     | 3         | 5.88%   |
| 4     | 1         | 1.96%   |
| 3     | 1         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 30.77%  |
| Graphics card            | 4         | 15.38%  |
| Unassigned class         | 3         | 11.54%  |
| Multimedia controller    | 3         | 11.54%  |
| Net/wireless             | 2         | 7.69%   |
| Communication controller | 2         | 7.69%   |
| Storage/ide              | 1         | 3.85%   |
| Net/ethernet             | 1         | 3.85%   |
| Card reader              | 1         | 3.85%   |
| Camera                   | 1         | 3.85%   |

