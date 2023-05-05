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

Total: 56

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 9         | 21.43%  |
| 5.14.0-70.17.1.el9_0.x86_64  | 6         | 14.29%  |
| 5.14.0-70.5.1.el9_0.x86_64   | 4         | 9.52%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 4         | 9.52%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 4         | 9.52%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3         | 7.14%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2         | 4.76%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 4.76%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 2         | 4.76%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 4.76%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 2.38%   |
| 5.14.0-70.17.1.el9_0.aarch64 | 1         | 2.38%   |
| 5.14.0-39.el9.x86_64         | 1         | 2.38%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 40        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 40        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 39        | 97.5%   |
| aarch64 | 1         | 2.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 38        | 95%     |
| GNOME Classic | 1         | 2.5%    |
| Unknown       | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 27        | 67.5%   |
| X11     | 11        | 27.5%   |
| Tty     | 2         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 57.5%   |
| GDM     | 16        | 40%     |
| SDDM    | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 31        | 77.5%   |
| en_GB | 3         | 7.5%    |
| pt_BR | 2         | 5%      |
| en_IN | 2         | 5%      |
| ru_RU | 1         | 2.5%    |
| ja_JP | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 37        | 92.5%   |
| BIOS | 3         | 7.5%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 38        | 95%     |
| Ext4 | 2         | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 52.5%   |
| GPT     | 18        | 45%     |
| MBR     | 1         | 2.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 85%     |
| Yes       | 6         | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 90%     |
| Yes       | 4         | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 7         | 17.5%   |
| Lenovo                  | 6         | 15%     |
| Gigabyte Technology     | 5         | 12.5%   |
| ASUSTek Computer        | 5         | 12.5%   |
| MSI                     | 4         | 10%     |
| Hewlett-Packard         | 3         | 7.5%    |
| Unknown                 | 3         | 7.5%    |
| Samsung Electronics     | 1         | 2.5%    |
| Razer                   | 1         | 2.5%    |
| Raspberry Pi Foundation | 1         | 2.5%    |
| Intel                   | 1         | 2.5%    |
| Hardkernel              | 1         | 2.5%    |
| ASRock                  | 1         | 2.5%    |
| Acer                    | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 7.5%    |
| Samsung 730QCJ/730QCR                    | 1         | 2.5%    |
| Razer Blade 15 Mid 2019-Base             | 1         | 2.5%    |
| RPi Raspberry Pi 4 Model B               | 1         | 2.5%    |
| MSI MS-7C95                              | 1         | 2.5%    |
| MSI MS-7B89                              | 1         | 2.5%    |
| MSI GP75 Leopard 9SD                     | 1         | 2.5%    |
| MSI GE72VR 7RF                           | 1         | 2.5%    |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US | 1         | 2.5%    |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00     | 1         | 2.5%    |
| Lenovo ThinkPad Edge E431 62771L7        | 1         | 2.5%    |
| Lenovo ThinkPad E14 20RA001MMZ           | 1         | 2.5%    |
| Lenovo ThinkBook 14-IIL 20SL             | 1         | 2.5%    |
| Lenovo ThinkBook 13s-IWL 20R9            | 1         | 2.5%    |
| Intel H81                                | 1         | 2.5%    |
| HP ProBook 640 G2                        | 1         | 2.5%    |
| HP Laptop 14s-dk0xxx                     | 1         | 2.5%    |
| HP 340S G7                               | 1         | 2.5%    |
| Hardkernel ODROID-H3                     | 1         | 2.5%    |
| Gigabyte X670E AORUS MASTER              | 1         | 2.5%    |
| Gigabyte MU72-SU0-00                     | 1         | 2.5%    |
| Gigabyte H510M H                         | 1         | 2.5%    |
| Gigabyte B550M AORUS PRO-P               | 1         | 2.5%    |
| Gigabyte AERO 15 KD                      | 1         | 2.5%    |
| Dell XPS 17 9710                         | 1         | 2.5%    |
| Dell Precision 7920 Tower                | 1         | 2.5%    |
| Dell Precision 7560                      | 1         | 2.5%    |
| Dell Precision 7510                      | 1         | 2.5%    |
| Dell Latitude E7450                      | 1         | 2.5%    |
| Dell Latitude 3410                       | 1         | 2.5%    |
| Dell Inspiron 5559                       | 1         | 2.5%    |
| ASUS Z450LA                              | 1         | 2.5%    |
| ASUS VivoBook_ASUSLaptop X515MA_A516MA   | 1         | 2.5%    |
| ASUS TUF Gaming Z690-PLUS WIFI D4        | 1         | 2.5%    |
| ASUS PRIME Z690-P WIFI                   | 1         | 2.5%    |
| ASUS PRIME Z590-A                        | 1         | 2.5%    |
| ASRock Z370 Professional Gaming i7       | 1         | 2.5%    |
| Acer Aspire XC-330                       | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 4         | 10%     |
| Dell Precision       | 3         | 7.5%    |
| Unknown              | 3         | 7.5%    |
| Lenovo ThinkBook     | 2         | 5%      |
| Dell Latitude        | 2         | 5%      |
| ASUS PRIME           | 2         | 5%      |
| Samsung 730QCJ       | 1         | 2.5%    |
| Razer Blade          | 1         | 2.5%    |
| RPi Raspberry        | 1         | 2.5%    |
| MSI MS-7C95          | 1         | 2.5%    |
| MSI MS-7B89          | 1         | 2.5%    |
| MSI GP75             | 1         | 2.5%    |
| MSI GE72VR           | 1         | 2.5%    |
| Intel H81            | 1         | 2.5%    |
| HP ProBook           | 1         | 2.5%    |
| HP Laptop            | 1         | 2.5%    |
| HP 340S              | 1         | 2.5%    |
| Hardkernel ODROID-H3 | 1         | 2.5%    |
| Gigabyte X670E       | 1         | 2.5%    |
| Gigabyte MU72-SU0-00 | 1         | 2.5%    |
| Gigabyte H510M       | 1         | 2.5%    |
| Gigabyte B550M       | 1         | 2.5%    |
| Gigabyte AERO        | 1         | 2.5%    |
| Dell XPS             | 1         | 2.5%    |
| Dell Inspiron        | 1         | 2.5%    |
| ASUS Z450LA          | 1         | 2.5%    |
| ASUS VivoBook        | 1         | 2.5%    |
| ASUS TUF             | 1         | 2.5%    |
| ASRock Z370          | 1         | 2.5%    |
| Acer Aspire          | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 22.5%   |
| 2022 | 7         | 17.5%   |
| 2021 | 7         | 17.5%   |
| 2020 | 6         | 15%     |
| 2017 | 3         | 7.5%    |
| 2016 | 2         | 5%      |
| 2015 | 2         | 5%      |
| 2023 | 1         | 2.5%    |
| 2018 | 1         | 2.5%    |
| 2014 | 1         | 2.5%    |
| 2013 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 23        | 57.5%   |
| Desktop        | 14        | 35%     |
| Server         | 2         | 5%      |
| System on chip | 1         | 2.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 35        | 85.37%  |
| Enabled  | 6         | 14.63%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 16        | 40%     |
| 4.01-8.0        | 9         | 22.5%   |
| 32.01-64.0      | 6         | 15%     |
| 64.01-256.0     | 5         | 12.5%   |
| 3.01-4.0        | 3         | 7.5%    |
| More than 256.0 | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 17        | 40.48%  |
| 4.01-8.0  | 8         | 19.05%  |
| 3.01-4.0  | 7         | 16.67%  |
| 1.01-2.0  | 5         | 11.9%   |
| 8.01-16.0 | 5         | 11.9%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 48.78%  |
| 2      | 12        | 29.27%  |
| 3      | 5         | 12.2%   |
| 5      | 3         | 7.32%   |
| 4      | 1         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 82.5%   |
| Yes       | 7         | 17.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 82.5%   |
| No        | 7         | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 82.5%   |
| No        | 7         | 17.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 73.17%  |
| No        | 11        | 26.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 14        | 35%     |
| India       | 6         | 15%     |
| UK          | 2         | 5%      |
| Turkey      | 2         | 5%      |
| Chile       | 2         | 5%      |
| Canada      | 2         | 5%      |
| Brazil      | 2         | 5%      |
| Switzerland | 1         | 2.5%    |
| Sri Lanka   | 1         | 2.5%    |
| Russia      | 1         | 2.5%    |
| Norway      | 1         | 2.5%    |
| Jordan      | 1         | 2.5%    |
| Japan       | 1         | 2.5%    |
| Indonesia   | 1         | 2.5%    |
| Guatemala   | 1         | 2.5%    |
| Germany     | 1         | 2.5%    |
| Finland     | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Santiago       | 2         | 4.88%   |
| Turku          | 1         | 2.44%   |
| Sutton         | 1         | 2.44%   |
| Stavropol      | 1         | 2.44%   |
| Skien          | 1         | 2.44%   |
| Shrewsbury     | 1         | 2.44%   |
| Sao Paulo      | 1         | 2.44%   |
| Sainte-Marie   | 1         | 2.44%   |
| Saint Paul     | 1         | 2.44%   |
| Providence     | 1         | 2.44%   |
| Prairieville   | 1         | 2.44%   |
| Piracicaba     | 1         | 2.44%   |
| Pforzheim      | 1         | 2.44%   |
| Oldham         | 1         | 2.44%   |
| New Delhi      | 1         | 2.44%   |
| Morton         | 1         | 2.44%   |
| Mohegan Lake   | 1         | 2.44%   |
| Mattapoisett   | 1         | 2.44%   |
| Maltepe        | 1         | 2.44%   |
| Kolkata        | 1         | 2.44%   |
| Kochi          | 1         | 2.44%   |
| Houston        | 1         | 2.44%   |
| Guatemala City | 1         | 2.44%   |
| Ghaziabad      | 1         | 2.44%   |
| Ernakulam      | 1         | 2.44%   |
| Denver         | 1         | 2.44%   |
| Denizli        | 1         | 2.44%   |
| Corona         | 1         | 2.44%   |
| Colombo        | 1         | 2.44%   |
| Chuorinkan     | 1         | 2.44%   |
| Christiansburg | 1         | 2.44%   |
| Cherry Hill    | 1         | 2.44%   |
| Canton         | 1         | 2.44%   |
| Bern           | 1         | 2.44%   |
| Bengaluru      | 1         | 2.44%   |
| Beeton         | 1         | 2.44%   |
| Bay Shore      | 1         | 2.44%   |
| Bandung        | 1         | 2.44%   |
| Baltimore      | 1         | 2.44%   |
| Amman          | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 13        | 15     | 18.31%  |
| WDC                       | 7         | 9      | 9.86%   |
| Seagate                   | 6         | 8      | 8.45%   |
| SanDisk                   | 5         | 5      | 7.04%   |
| Toshiba                   | 3         | 3      | 4.23%   |
| SK hynix                  | 3         | 3      | 4.23%   |
| Phison                    | 3         | 3      | 4.23%   |
| KIOXIA                    | 3         | 4      | 4.23%   |
| Kingston                  | 3         | 3      | 4.23%   |
| China                     | 3         | 3      | 4.23%   |
| Unknown                   | 2         | 2      | 2.82%   |
| Micron Technology         | 2         | 2      | 2.82%   |
| KingSpec                  | 2         | 2      | 2.82%   |
| Intel                     | 2         | 3      | 2.82%   |
| HGST                      | 2         | 2      | 2.82%   |
| ADATA Technology          | 2         | 2      | 2.82%   |
| XUM                       | 1         | 1      | 1.41%   |
| SSSTC                     | 1         | 1      | 1.41%   |
| SABRENT                   | 1         | 1      | 1.41%   |
| PNY                       | 1         | 1      | 1.41%   |
| Plextor                   | 1         | 1      | 1.41%   |
| Micron/Crucial Technology | 1         | 2      | 1.41%   |
| Hitachi                   | 1         | 1      | 1.41%   |
| Golden                    | 1         | 1      | 1.41%   |
| Gigabyte Technology       | 1         | 1      | 1.41%   |
| A-DATA Technology         | 1         | 1      | 1.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 2         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 2.7%    |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 2.7%    |
| HGST HTS721010A9E630 1TB                           | 2         | 2.7%    |
| XUM HX256GSSDSATA3 256GB                           | 1         | 1.35%   |
| WDC WDBA3V5000ANC-WRSN 500GB                       | 1         | 1.35%   |
| WDC WD5000AVCS-632DY1 500GB                        | 1         | 1.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1         | 1.35%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 1         | 1.35%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.35%   |
| WDC WD10SPSX-00A6WT0 1TB                           | 1         | 1.35%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1         | 1.35%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 1.35%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 1         | 1.35%   |
| Unknown SDU1  64GB                                 | 1         | 1.35%   |
| Unknown SD/MMC/MS PRO 249GB                        | 1         | 1.35%   |
| Toshiba MQ01ACF050 500GB                           | 1         | 1.35%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1.35%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.35%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                     | 1         | 1.35%   |
| SK hynix SHGP31-1000GM 1TB                         | 1         | 1.35%   |
| SK hynix SC401 SATA 512GB SSD                      | 1         | 1.35%   |
| SK hynix NVMe SSD Drive 1024GB                     | 1         | 1.35%   |
| Seagate ST9250315AS 250GB                          | 1         | 1.35%   |
| Seagate ST3500312CS 500GB                          | 1         | 1.35%   |
| Seagate ST31000528AS 1TB                           | 1         | 1.35%   |
| Seagate ST18000NM000J-2TV103 18TB                  | 1         | 1.35%   |
| Seagate ST1000LM049-2GH172 1TB                     | 1         | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB                     | 1         | 1.35%   |
| Sandisk WD Blue SN570 500GB                        | 1         | 1.35%   |
| SanDisk SDSSDHII480G 480GB                         | 1         | 1.35%   |
| SanDisk NVMe SSD Drive 1TB                         | 1         | 1.35%   |
| Samsung SSD 980 1TB                                | 1         | 1.35%   |
| Samsung SSD 970 EVO Plus 500GB                     | 1         | 1.35%   |
| Samsung SSD 970 EVO Plus 1TB                       | 1         | 1.35%   |
| Samsung SSD 883 DCT 960GB                          | 1         | 1.35%   |
| Samsung SSD 870 EVO 1TB                            | 1         | 1.35%   |
| Samsung SSD 860 EVO 4TB                            | 1         | 1.35%   |
| Samsung SSD 840 EVO 120GB                          | 1         | 1.35%   |
| Samsung NVMe SSD Drive 2TB                         | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 8      | 31.58%  |
| Seagate | 6         | 8      | 31.58%  |
| Toshiba | 3         | 3      | 15.79%  |
| HGST    | 2         | 2      | 10.53%  |
| Unknown | 1         | 1      | 5.26%   |
| Hitachi | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 27.78%  |
| China               | 3         | 3      | 16.67%  |
| KingSpec            | 2         | 2      | 11.11%  |
| XUM                 | 1         | 1      | 5.56%   |
| SK hynix            | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| PNY                 | 1         | 1      | 5.56%   |
| Plextor             | 1         | 1      | 5.56%   |
| Kingston            | 1         | 1      | 5.56%   |
| Intel               | 1         | 2      | 5.56%   |
| Gigabyte Technology | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 29        | 36     | 46.03%  |
| SSD     | 16        | 19     | 25.4%   |
| HDD     | 16        | 23     | 25.4%   |
| MMC     | 1         | 1      | 1.59%   |
| Unknown | 1         | 1      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 29        | 35     | 50.88%  |
| SATA | 25        | 42     | 43.86%  |
| SAS  | 2         | 2      | 3.51%   |
| MMC  | 1         | 1      | 1.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 14        | 20     | 48.28%  |
| 0.01-0.5   | 12        | 17     | 41.38%  |
| 3.01-4.0   | 1         | 1      | 3.45%   |
| 10.01-20.0 | 1         | 2      | 3.45%   |
| 1.01-2.0   | 1         | 2      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 34.15%  |
| 251-500        | 9         | 21.95%  |
| 501-1000       | 7         | 17.07%  |
| 1001-2000      | 6         | 14.63%  |
| 51-100         | 3         | 7.32%   |
| More than 3000 | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 18        | 43.9%   |
| 21-50          | 10        | 24.39%  |
| 51-100         | 5         | 12.2%   |
| 251-500        | 4         | 9.76%   |
| 101-250        | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Intel SSDSC2BA800G4R 800GB | 1         | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 2      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 24        | 50     | 57.14%  |
| Works    | 17        | 28     | 40.48%  |
| Malfunc  | 1         | 2      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 28        | 43.08%  |
| Samsung Electronics         | 8         | 12.31%  |
| AMD                         | 6         | 9.23%   |
| SanDisk                     | 5         | 7.69%   |
| Phison Electronics          | 3         | 4.62%   |
| KIOXIA                      | 3         | 4.62%   |
| ADATA Technology            | 3         | 4.62%   |
| SK hynix                    | 2         | 3.08%   |
| Micron Technology           | 2         | 3.08%   |
| Kingston Technology Company | 2         | 3.08%   |
| Micron/Crucial Technology   | 1         | 1.54%   |
| Broadcom / LSI              | 1         | 1.54%   |
| ASMedia Technology          | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 4.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 4.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.23%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4.23%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 2.82%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 2.82%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.82%   |
| Phison E12 NVMe Controller                                                     | 2         | 2.82%   |
| Micron NVMe Storage Controller                                                 | 2         | 2.82%   |
| KIOXIA Non-Volatile memory controller                                          | 2         | 2.82%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 2.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.82%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2         | 2.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.82%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 2.82%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 2         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 2.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.82%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.41%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.41%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.41%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 1.41%   |
| Intel SSD 660P Series                                                          | 1         | 1.41%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.41%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.41%   |
| Intel C620 Series Chipset Family IDE Redirection                               | 1         | 1.41%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 28        | 42.42%  |
| SATA | 28        | 42.42%  |
| RAID | 9         | 13.64%  |
| IDE  | 1         | 1.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 82.5%   |
| AMD    | 6         | 15%     |
| ARM    | 1         | 2.5%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 5%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 5%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 5%      |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 5%      |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 2.5%    |
| Intel Xeon Silver 4310 CPU @ 2.10GHz          | 1         | 2.5%    |
| Intel Xeon Platinum 8168 CPU @ 2.70GHz        | 1         | 2.5%    |
| Intel Pentium Silver N6005 @ 2.00GHz          | 1         | 2.5%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 2.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 2.5%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.5%    |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1         | 2.5%    |
| Intel Core i5-3470S CPU @ 2.90GHz             | 1         | 2.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 2.5%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 2.5%    |
| Intel Celeron N5105 @ 2.00GHz                 | 1         | 2.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.5%    |
| Intel 13th Gen Core i5-13600K                 | 1         | 2.5%    |
| Intel 12th Gen Core i9-12900K                 | 1         | 2.5%    |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.5%    |
| Intel 12th Gen Core i5-1235U                  | 1         | 2.5%    |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i7-11700F @ 2.50GHz       | 1         | 2.5%    |
| ARM Processor                                 | 1         | 2.5%    |
| AMD Ryzen 9 7900X 12-Core Processor           | 1         | 2.5%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G  | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 9         | 22.5%   |
| Intel Core i5        | 9         | 22.5%   |
| Intel Core i7        | 8         | 20%     |
| AMD Ryzen 5          | 4         | 10%     |
| Intel Core i3        | 2         | 5%      |
| Intel Celeron        | 2         | 5%      |
| Intel Xeon Silver    | 1         | 2.5%    |
| Intel Xeon Platinum  | 1         | 2.5%    |
| Intel Xeon           | 1         | 2.5%    |
| Intel Pentium Silver | 1         | 2.5%    |
| AMD Ryzen 9          | 1         | 2.5%    |
| AMD A4               | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 14        | 35%     |
| 2      | 8         | 20%     |
| 6      | 7         | 17.5%   |
| 8      | 5         | 12.5%   |
| 12     | 3         | 7.5%    |
| 48     | 1         | 2.5%    |
| 14     | 1         | 2.5%    |
| 10     | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 97.5%   |
| 2      | 1         | 2.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 80%     |
| 1      | 8         | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 10%     |
| 0x806d1    | 3         | 7.5%    |
| 0x306a9    | 3         | 7.5%    |
| 0xa0671    | 2         | 5%      |
| 0x906ea    | 2         | 5%      |
| 0x906c0    | 2         | 5%      |
| 0x706e5    | 2         | 5%      |
| 0x406e3    | 2         | 5%      |
| 0x08701021 | 2         | 5%      |
| 0xb0671    | 1         | 2.5%    |
| 0x906ed    | 1         | 2.5%    |
| 0x906e9    | 1         | 2.5%    |
| 0x906a4    | 1         | 2.5%    |
| 0x906a3    | 1         | 2.5%    |
| 0x90672    | 1         | 2.5%    |
| 0x706a8    | 1         | 2.5%    |
| 0x606a6    | 1         | 2.5%    |
| 0x506e3    | 1         | 2.5%    |
| 0x50654    | 1         | 2.5%    |
| 0x40651    | 1         | 2.5%    |
| 0x306d4    | 1         | 2.5%    |
| 0x306c3    | 1         | 2.5%    |
| 0x0a601203 | 1         | 2.5%    |
| 0x0a50000c | 1         | 2.5%    |
| 0x08108109 | 1         | 2.5%    |
| 0x06006705 | 1         | 2.5%    |
| Unknown    | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 8         | 20%     |
| Icelake          | 8         | 20%     |
| Skylake          | 4         | 10%     |
| Alderlake Hybrid | 4         | 10%     |
| IvyBridge        | 3         | 7.5%    |
| Zen 2            | 2         | 5%      |
| Tremont          | 2         | 5%      |
| Haswell          | 2         | 5%      |
| Unknown          | 2         | 5%      |
| Zen+             | 1         | 2.5%    |
| Zen 3            | 1         | 2.5%    |
| Goldmont plus    | 1         | 2.5%    |
| Excavator        | 1         | 2.5%    |
| Broadwell        | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 25        | 53.19%  |
| Nvidia            | 13        | 27.66%  |
| AMD               | 8         | 17.02%  |
| ASPEED Technology | 1         | 2.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 6.12%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 4.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 4.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 4.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 4.08%   |
| Intel JasperLake [UHD Graphics]                                               | 2         | 4.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 4.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 4.08%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 2.04%   |
| Nvidia TU117GL [T400 4GB]                                                     | 1         | 2.04%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 2.04%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 2.04%   |
| Nvidia GP104GL [Quadro P4000]                                                 | 1         | 2.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1         | 2.04%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 2.04%   |
| Nvidia GA106 [Geforce RTX 3050]                                               | 1         | 2.04%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 2.04%   |
| Nvidia G92 [GeForce 9800 GT]                                                  | 1         | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 2.04%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 1         | 2.04%   |
| Intel HD Graphics 630                                                         | 1         | 2.04%   |
| Intel HD Graphics 5500                                                        | 1         | 2.04%   |
| Intel HD Graphics 530                                                         | 1         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.04%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 2.04%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 2.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 2.04%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 2.04%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 2.04%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                              | 1         | 2.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 2.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 2.04%   |
| AMD Raphael                                                                   | 1         | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.04%   |
| AMD Navi 24 [Radeon PRO W6400]                                                | 1         | 2.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 1         | 2.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 2.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 45%     |
| 1 x Nvidia     | 7         | 17.5%   |
| Intel + Nvidia | 5         | 12.5%   |
| 1 x AMD        | 4         | 10%     |
| Intel + AMD    | 2         | 5%      |
| Other          | 1         | 2.5%    |
| 2 x Nvidia     | 1         | 2.5%    |
| 2 x AMD        | 1         | 2.5%    |
| AMD + ASPEED   | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 80%     |
| Proprietary | 5         | 12.5%   |
| Unknown     | 3         | 7.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 52.5%   |
| 1.01-2.0   | 4         | 10%     |
| 7.01-8.0   | 3         | 7.5%    |
| 5.01-6.0   | 3         | 7.5%    |
| 3.01-4.0   | 3         | 7.5%    |
| 0.01-0.5   | 2         | 5%      |
| 2.01-3.0   | 1         | 2.5%    |
| 16.01-24.0 | 1         | 2.5%    |
| 8.01-16.0  | 1         | 2.5%    |
| 0.51-1.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 8         | 18.6%   |
| Samsung Electronics | 5         | 11.63%  |
| Chimei Innolux      | 4         | 9.3%    |
| LG Display          | 3         | 6.98%   |
| Goldstar            | 3         | 6.98%   |
| Dell                | 3         | 6.98%   |
| Sharp               | 2         | 4.65%   |
| Lenovo              | 2         | 4.65%   |
| AU Optronics        | 2         | 4.65%   |
| Unknown             | 1         | 2.33%   |
| STD                 | 1         | 2.33%   |
| Sony                | 1         | 2.33%   |
| OUT                 | 1         | 2.33%   |
| Haier               | 1         | 2.33%   |
| Gigabyte Technology | 1         | 2.33%   |
| Deco Gear           | 1         | 2.33%   |
| CSO                 | 1         | 2.33%   |
| BenQ                | 1         | 2.33%   |
| ASUSTek Computer    | 1         | 2.33%   |
| Acer                | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor SAMSUNG                                            | 1         | 2.17%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1         | 2.17%   |
| Sony TV SNYD703 1360x768                                               | 1         | 2.17%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                | 1         | 2.17%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                | 1         | 2.17%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1         | 2.17%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1         | 2.17%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1         | 2.17%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1         | 2.17%   |
| Samsung Electronics LCD Monitor S34J55x 7280x2160                      | 1         | 2.17%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1         | 2.17%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch           | 1         | 2.17%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch           | 1         | 2.17%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch           | 1         | 2.17%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch               | 1         | 2.17%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch             | 1         | 2.17%   |
| Lenovo LCD Monitor LEN1144 1920x1080 518x324mm 24.1-inch               | 1         | 2.17%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                | 1         | 2.17%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 1         | 2.17%   |
| Goldstar LG UltraFine GSM5B11                                          | 1         | 2.17%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                  | 1         | 2.17%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 1         | 2.17%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                     | 1         | 2.17%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                       | 1         | 2.17%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                      | 1         | 2.17%   |
| Deco Gear DGVIEW220 DGVFFFF 3440x1440 819x346mm 35.0-inch              | 1         | 2.17%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch                  | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1760 1920x1080 381x214mm 17.2-inch       | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch       | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch       | 1         | 2.17%   |
| BOE LCD Monitor BOE0A62 1920x1080 309x174mm 14.0-inch                  | 1         | 2.17%   |
| BOE LCD Monitor BOE08FA 1920x1080 294x165mm 13.3-inch                  | 1         | 2.17%   |
| BOE LCD Monitor BOE07D7 1920x1080 294x165mm 13.3-inch                  | 1         | 2.17%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                  | 1         | 2.17%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                   | 1         | 2.17%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                  | 1         | 2.17%   |
| BOE LCD Monitor BOE069A 1366x768 309x173mm 13.9-inch                   | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 45.45%  |
| 3840x2160 (4K)     | 5         | 11.36%  |
| 1366x768 (WXGA)    | 5         | 11.36%  |
| 2560x1440 (QHD)    | 3         | 6.82%   |
| 1680x1050 (WSXGA+) | 2         | 4.55%   |
| Unknown            | 2         | 4.55%   |
| 7280x2160          | 1         | 2.27%   |
| 3440x1440          | 1         | 2.27%   |
| 2160x1350          | 1         | 2.27%   |
| 1920x1200 (WUXGA)  | 1         | 2.27%   |
| 1600x900 (HD+)     | 1         | 2.27%   |
| 1280x768           | 1         | 2.27%   |
| 1280x1024 (SXGA)   | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 11        | 25%     |
| 27      | 4         | 9.09%   |
| 21      | 4         | 9.09%   |
| 15      | 4         | 9.09%   |
| 23      | 3         | 6.82%   |
| 17      | 3         | 6.82%   |
| 14      | 3         | 6.82%   |
| 72      | 2         | 4.55%   |
| 31      | 2         | 4.55%   |
| 64      | 1         | 2.27%   |
| 52      | 1         | 2.27%   |
| 35      | 1         | 2.27%   |
| 24      | 1         | 2.27%   |
| 20      | 1         | 2.27%   |
| 19      | 1         | 2.27%   |
| 16      | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 37.21%  |
| 501-600     | 7         | 16.28%  |
| 401-500     | 5         | 11.63%  |
| 351-400     | 4         | 9.3%    |
| 201-300     | 3         | 6.98%   |
| 601-700     | 2         | 4.65%   |
| 1501-2000   | 2         | 4.65%   |
| 1001-1500   | 2         | 4.65%   |
| 801-900     | 1         | 2.33%   |
| Unknown     | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 78.38%  |
| 16/10   | 4         | 10.81%  |
| 5/4     | 1         | 2.7%    |
| 4/3     | 1         | 2.7%    |
| 21/9    | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 25.58%  |
| 201-250        | 5         | 11.63%  |
| More than 1000 | 4         | 9.3%    |
| 301-350        | 4         | 9.3%    |
| 101-110        | 4         | 9.3%    |
| 71-80          | 3         | 6.98%   |
| 351-500        | 3         | 6.98%   |
| 151-200        | 3         | 6.98%   |
| 121-130        | 3         | 6.98%   |
| 251-300        | 1         | 2.33%   |
| 131-140        | 1         | 2.33%   |
| Unknown        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 28.21%  |
| 101-120       | 10        | 25.64%  |
| 51-100        | 9         | 23.08%  |
| 161-240       | 4         | 10.26%  |
| More than 240 | 2         | 5.13%   |
| 1-50          | 2         | 5.13%   |
| Unknown       | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 70.73%  |
| 2     | 5         | 12.2%   |
| 0     | 4         | 9.76%   |
| 3     | 2         | 4.88%   |
| 4     | 1         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 53.57%  |
| Realtek Semiconductor | 21        | 37.5%   |
| Qualcomm Atheros      | 2         | 3.57%   |
| Tehuti Networks       | 1         | 1.79%   |
| ASUSTek Computer      | 1         | 1.79%   |
| Aquantia              | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 13.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5.26%   |
| Intel Ethernet Controller I225-V                                  | 4         | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 3.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 3.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.63%   |
| Intel Wireless 8260                                               | 2         | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 2.63%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.63%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 2.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.63%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.63%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.32%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.32%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.32%   |
| Intel Wireless 7265                                               | 1         | 1.32%   |
| Intel Wireless 3160                                               | 1         | 1.32%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.32%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.32%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.32%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 1.32%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.32%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.32%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 79.41%  |
| Realtek Semiconductor | 6         | 17.65%  |
| ASUSTek Computer      | 1         | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]         | 4         | 11.76%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 3         | 8.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 3         | 8.82%   |
| Intel Wireless 8260                                      | 2         | 5.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                          | 2         | 5.88%   |
| Intel Cannon Lake PCH CNVi WiFi                          | 2         | 5.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                         | 2         | 5.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                         | 2         | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1         | 2.94%   |
| Realtek RTL8723DE Wireless Network Adapter               | 1         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter          | 1         | 2.94%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter               | 1         | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 1         | 2.94%   |
| Realtek 802.11n WLAN Adapter                             | 1         | 2.94%   |
| Intel Wireless 7265                                      | 1         | 2.94%   |
| Intel Wireless 3160                                      | 1         | 2.94%   |
| Intel Wi-Fi 6 AX201 160MHz                               | 1         | 2.94%   |
| Intel Wi-Fi 6 AX200                                      | 1         | 2.94%   |
| Intel Tiger Lake PCH CNVi WiFi                           | 1         | 2.94%   |
| Intel Centrino Wireless-N 2230                           | 1         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 1         | 2.94%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]      | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 54.05%  |
| Intel                 | 13        | 35.14%  |
| Qualcomm Atheros      | 2         | 5.41%   |
| Tehuti Networks       | 1         | 2.7%    |
| Aquantia              | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 23.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.9%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 9.52%   |
| Intel Ethernet Controller I225-V                                  | 4         | 9.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.76%   |
| Intel I210 Gigabit Network Connection                             | 2         | 4.76%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 4.76%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 2.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.38%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.38%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 2.38%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 2.38%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 2.38%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 50%     |
| Ethernet | 33        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 52.27%  |
| Ethernet | 21        | 47.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 57.5%   |
| 1     | 11        | 27.5%   |
| 4     | 3         | 7.5%    |
| 3     | 2         | 5%      |
| 0     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 77.5%   |
| Yes  | 9         | 22.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 25        | 78.13%  |
| Realtek Semiconductor      | 2         | 6.25%   |
| Cambridge Silicon Radio    | 2         | 6.25%   |
| Integrated System Solution | 1         | 3.13%   |
| IMC Networks               | 1         | 3.13%   |
| Broadcom                   | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                 | 7         | 21.88%  |
| Intel Wireless-AC 3168 Bluetooth                      | 4         | 12.5%   |
| Intel Bluetooth wireless interface                    | 4         | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4         | 12.5%   |
| Intel AX210 Bluetooth                                 | 3         | 9.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 3.13%   |
| Realtek Bluetooth Radio                               | 1         | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 3.13%   |
| Intel Bluetooth Device                                | 1         | 3.13%   |
| Intel AX200 Bluetooth                                 | 1         | 3.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 3.13%   |
| IMC Networks Bluetooth Radio                          | 1         | 3.13%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 32        | 50.79%  |
| Nvidia                                       | 12        | 19.05%  |
| AMD                                          | 8         | 12.7%   |
| Texas Instruments                            | 3         | 4.76%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.59%   |
| Sony                                         | 1         | 1.59%   |
| Realtek Semiconductor                        | 1         | 1.59%   |
| Logitech                                     | 1         | 1.59%   |
| LG Electronics                               | 1         | 1.59%   |
| Creative Labs                                | 1         | 1.59%   |
| Corsair                                      | 1         | 1.59%   |
| Blue Microphones                             | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 6.85%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 4.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 4.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 4.11%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2         | 2.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 2.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.74%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 2.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.74%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 2.74%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 1.37%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 1.37%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 1.37%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.37%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.37%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.37%   |
| Logitech Headset H340                                                      | 1         | 1.37%   |
| LG Electronics USB Audio                                                   | 1         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.37%   |
| Intel Lewisburg MROM 0                                                     | 1         | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.37%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.37%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 4         | 23.53%  |
| Samsung Electronics | 4         | 23.53%  |
| Kingston            | 3         | 17.65%  |
| G.Skill             | 2         | 11.76%  |
| Unknown             | 1         | 5.88%   |
| Smart               | 1         | 5.88%   |
| Micron Technology   | 1         | 5.88%   |
| Crucial             | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 5.56%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 5.56%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s        | 1         | 5.56%   |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s        | 1         | 5.56%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 5.56%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 5.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 5.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 5.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 5.56%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s          | 1         | 5.56%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 5.56%   |
| Micron RAM Module 8GB Chip LPDDR4                            | 1         | 5.56%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s        | 1         | 5.56%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 1         | 5.56%   |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 5.56%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM 6400MT/s              | 1         | 5.56%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 1         | 5.56%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s         | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 58.82%  |
| DDR3   | 3         | 17.65%  |
| LPDDR4 | 2         | 11.76%  |
| LPDDR5 | 1         | 5.88%   |
| DDR5   | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 47.06%  |
| DIMM         | 6         | 35.29%  |
| Row Of Chips | 2         | 11.76%  |
| Chip         | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 44.44%  |
| 16384 | 6         | 33.33%  |
| 4096  | 2         | 11.11%  |
| 65536 | 1         | 5.56%   |
| 2048  | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 6400    | 2         | 11.11%  |
| 3600    | 2         | 11.11%  |
| 3200    | 2         | 11.11%  |
| 2667    | 2         | 11.11%  |
| 2400    | 2         | 11.11%  |
| 2133    | 2         | 11.11%  |
| 2933    | 1         | 5.56%   |
| 2666    | 1         | 5.56%   |
| 1867    | 1         | 5.56%   |
| 1600    | 1         | 5.56%   |
| 1333    | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 4         | 14.29%  |
| Chicony Electronics                    | 4         | 14.29%  |
| Sunplus Innovation Technology          | 2         | 7.14%   |
| Realtek Semiconductor                  | 2         | 7.14%   |
| Microdia                               | 2         | 7.14%   |
| vivo                                   | 1         | 3.57%   |
| Syntek                                 | 1         | 3.57%   |
| Suyin                                  | 1         | 3.57%   |
| Sonix Technology                       | 1         | 3.57%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.57%   |
| Quanta                                 | 1         | 3.57%   |
| Microsoft                              | 1         | 3.57%   |
| Luxvisions Innotech Limited            | 1         | 3.57%   |
| Logitech                               | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |
| LG Electronics                         | 1         | 3.57%   |
| Generalplus Technology                 | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| Bison Electronics                      | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 2         | 7.14%   |
| Chicony Integrated Camera                                      | 2         | 7.14%   |
| vivo V2023                                                     | 1         | 3.57%   |
| Syntek Integrated Camera                                       | 1         | 3.57%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 3.57%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 3.57%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 3.57%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 3.57%   |
| Realtek Full HD webcam                                         | 1         | 3.57%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 3.57%   |
| Microsoft LifeCam VX-2000                                      | 1         | 3.57%   |
| Microdia USB 2.0 Camera                                        | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.57%   |
| Luxvisions Innotech Limited Integrated RGB Camera              | 1         | 3.57%   |
| Logitech Webcam C250                                           | 1         | 3.57%   |
| Lite-On HP HD Camera                                           | 1         | 3.57%   |
| LG LG UltraFine Display Camera                                 | 1         | 3.57%   |
| IMC Networks XHC Camera                                        | 1         | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.57%   |
| IMC Networks USB Camera                                        | 1         | 3.57%   |
| IMC Networks Integrated Camera                                 | 1         | 3.57%   |
| Generalplus WEB CAM                                            | 1         | 3.57%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 3.57%   |
| Chicony HD Webcam                                              | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.57%   |
| Bison BisonCam, NB Pro                                         | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 40%     |
| Validity Sensors           | 1         | 20%     |
| Synaptics                  | 1         | 20%     |
| Samsung Electronics        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 2         | 40%     |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 27        | 67.5%   |
| 1     | 10        | 25%     |
| 4     | 1         | 2.5%    |
| 3     | 1         | 2.5%    |
| 2     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 5         | 26.32%  |
| Graphics card            | 4         | 21.05%  |
| Unassigned class         | 2         | 10.53%  |
| Multimedia controller    | 2         | 10.53%  |
| Storage/ide              | 1         | 5.26%   |
| Net/wireless             | 1         | 5.26%   |
| Net/ethernet             | 1         | 5.26%   |
| Communication controller | 1         | 5.26%   |
| Card reader              | 1         | 5.26%   |
| Camera                   | 1         | 5.26%   |

