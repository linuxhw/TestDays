Kaisen - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Kaisen.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kaisen/Desktop/README.md) and [notebooks](/Dist/Kaisen/Notebook/README.md).

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

Total: 53

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI      | MPG B550 GAMING EDGE WIF... | Desktop     | [9f8e4c6a70](https://linux-hardware.org/?probe=9f8e4c6a70) | Jun 30, 2023 |
| HP       | Notebook                    | Notebook    | [6cc93c4c8a](https://linux-hardware.org/?probe=6cc93c4c8a) | Jun 19, 2023 |
| MSI      | Z87-G43                     | Desktop     | [6babb6024e](https://linux-hardware.org/?probe=6babb6024e) | Apr 23, 2023 |
| MSI      | X399 SLI PLUS               | Desktop     | [ebb44ab29d](https://linux-hardware.org/?probe=ebb44ab29d) | Apr 22, 2023 |
| Dell     | XPS 13 9310 2-in-1          | Convertible | [e5bdd0c69a](https://linux-hardware.org/?probe=e5bdd0c69a) | Apr 13, 2023 |
| HP       | Laptop 15-bw0xx             | Notebook    | [0cef536369](https://linux-hardware.org/?probe=0cef536369) | Apr 10, 2023 |
| Lenovo   | ThinkPad T431s 20AA000MU... | Notebook    | [68779350fd](https://linux-hardware.org/?probe=68779350fd) | Feb 24, 2023 |
| HP       | 1825                        | Desktop     | [3ba7cec175](https://linux-hardware.org/?probe=3ba7cec175) | Feb 22, 2023 |
| MSI      | Z87-G43                     | Desktop     | [acbef2e01a](https://linux-hardware.org/?probe=acbef2e01a) | Feb 21, 2023 |
| Lenovo   | ThinkPad L470 20J4CTO1WW    | Notebook    | [7d55f655bb](https://linux-hardware.org/?probe=7d55f655bb) | Feb 15, 2023 |
| MSI      | B550-A PRO                  | Desktop     | [d2ebdf5627](https://linux-hardware.org/?probe=d2ebdf5627) | Dec 20, 2022 |
| Dell     | 0M017G A00                  | Desktop     | [6d65d5022d](https://linux-hardware.org/?probe=6d65d5022d) | Dec 20, 2022 |
| Dell     | G3 3500                     | Notebook    | [9a574c1075](https://linux-hardware.org/?probe=9a574c1075) | Oct 04, 2022 |
| Samsung  | 370E4K                      | Notebook    | [1a297b75f9](https://linux-hardware.org/?probe=1a297b75f9) | Sep 18, 2022 |
| Dell     | Inspiron 15 7000 Gaming     | Notebook    | [edc0c871cb](https://linux-hardware.org/?probe=edc0c871cb) | Sep 17, 2022 |
| ASUSTek  | N76VB                       | Notebook    | [e488dd7682](https://linux-hardware.org/?probe=e488dd7682) | Aug 27, 2022 |
| MSI      | Vector GP76 12UH            | Notebook    | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Acer     | Aspire One 753              | Notebook    | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Samsung  | 950QDB                      | Convertible | [3501e7feef](https://linux-hardware.org/?probe=3501e7feef) | Jul 17, 2022 |
| Samsung  | 950QDB                      | Convertible | [a8ec786d20](https://linux-hardware.org/?probe=a8ec786d20) | Jul 17, 2022 |
| HP       | 339A                        | Desktop     | [7cfe4b70f8](https://linux-hardware.org/?probe=7cfe4b70f8) | Jun 30, 2022 |
| HP       | 8053                        | Desktop     | [ff703fcbf1](https://linux-hardware.org/?probe=ff703fcbf1) | Jun 23, 2022 |
| ASUSTek  | 970 PRO GAMING/AURA         | Desktop     | [67dbfe0d98](https://linux-hardware.org/?probe=67dbfe0d98) | May 14, 2022 |
| Dell     | Latitude 3540               | Notebook    | [e4dd2ae509](https://linux-hardware.org/?probe=e4dd2ae509) | May 06, 2022 |
| Dell     | Inspiron 14 5401            | Notebook    | [d357bf876a](https://linux-hardware.org/?probe=d357bf876a) | Apr 02, 2022 |
| Lenovo   | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c9d1e057c3](https://linux-hardware.org/?probe=c9d1e057c3) | Jan 03, 2022 |
| HP       | EliteBook 840 G1            | Notebook    | [f04d152dbc](https://linux-hardware.org/?probe=f04d152dbc) | Dec 10, 2021 |
| Gigabyte | B550M AORUS ELITE           | Desktop     | [0105f991c1](https://linux-hardware.org/?probe=0105f991c1) | Dec 01, 2021 |
| Lenovo   | ThinkPad T520 4243E51       | Notebook    | [dbee2d500a](https://linux-hardware.org/?probe=dbee2d500a) | Nov 29, 2021 |
| Gigabyte | M61PM-S2                    | Desktop     | [ed3a73a8a0](https://linux-hardware.org/?probe=ed3a73a8a0) | Nov 02, 2021 |
| HP       | 81C3                        | Desktop     | [df2caaf484](https://linux-hardware.org/?probe=df2caaf484) | Oct 11, 2021 |
| HP       | Pavilion 15                 | Notebook    | [15e92e7427](https://linux-hardware.org/?probe=15e92e7427) | Sep 25, 2021 |
| Lenovo   | ThinkPad T450 20BV003SMS    | Notebook    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Lenovo   | ThinkPad T430 23427YU       | Notebook    | [9f7679f7be](https://linux-hardware.org/?probe=9f7679f7be) | Sep 06, 2021 |
| Apple    | Mac-F2268CC8                | All in one  | [7c349a10d2](https://linux-hardware.org/?probe=7c349a10d2) | Aug 19, 2021 |
| Lenovo   | ThinkPad T15 Gen 2i 20W4... | Notebook    | [7a6c5d1f4b](https://linux-hardware.org/?probe=7a6c5d1f4b) | Aug 16, 2021 |
| HP       | ProBook 650 G2              | Notebook    | [8bd4184e25](https://linux-hardware.org/?probe=8bd4184e25) | Aug 15, 2021 |
| HP       | ProBook 650 G2              | Notebook    | [9fef85ae5d](https://linux-hardware.org/?probe=9fef85ae5d) | Aug 11, 2021 |
| Gigabyte | AX370-Gaming K5-CF          | Desktop     | [d08d8c22f3](https://linux-hardware.org/?probe=d08d8c22f3) | Aug 06, 2021 |
| Intel    | H61M-S2PV                   | Desktop     | [a7ed913051](https://linux-hardware.org/?probe=a7ed913051) | Aug 05, 2021 |
| Foxconn  | 2ABF                        | Desktop     | [e722057484](https://linux-hardware.org/?probe=e722057484) | Jul 29, 2021 |
| HP       | 0B4Ch D                     | Desktop     | [775cf09e30](https://linux-hardware.org/?probe=775cf09e30) | Jul 23, 2021 |
| HP       | Pavilion g7                 | Notebook    | [2aba1a12dd](https://linux-hardware.org/?probe=2aba1a12dd) | Jul 21, 2021 |
| HP       | Pavilion g7                 | Notebook    | [a4cbb8c698](https://linux-hardware.org/?probe=a4cbb8c698) | Jul 15, 2021 |
| HP       | Pavilion g7                 | Notebook    | [3a0142c412](https://linux-hardware.org/?probe=3a0142c412) | Jul 13, 2021 |
| Gigabyte | GA-6PXSV1                   | Server      | [0ac54e7fb4](https://linux-hardware.org/?probe=0ac54e7fb4) | Jun 02, 2021 |
| HP       | EliteBook 840 G2            | Notebook    | [aa55e0ae92](https://linux-hardware.org/?probe=aa55e0ae92) | Apr 30, 2021 |
| HP       | ProBook 645 G1              | Notebook    | [501e0bc33f](https://linux-hardware.org/?probe=501e0bc33f) | Apr 15, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [871a04a1f3](https://linux-hardware.org/?probe=871a04a1f3) | Oct 27, 2020 |
| HP       | EliteBook 840 G2            | Notebook    | [d3d44f4bdf](https://linux-hardware.org/?probe=d3d44f4bdf) | Oct 22, 2020 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [51bd9bdbb7](https://linux-hardware.org/?probe=51bd9bdbb7) | Oct 08, 2020 |
| Apple    | MacBookPro9,2               | Notebook    | [65031a9a6d](https://linux-hardware.org/?probe=65031a9a6d) | May 29, 2020 |
| Apple    | MacBookPro9,2               | Notebook    | [7ad10f260f](https://linux-hardware.org/?probe=7ad10f260f) | May 18, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Kaisen 1.8 | 12        | 26.09%  |
| Kaisen 2.2 | 8         | 17.39%  |
| Kaisen 2.1 | 8         | 17.39%  |
| Kaisen 2.0 | 6         | 13.04%  |
| Kaisen 1.7 | 3         | 6.52%   |
| Kaisen 1.6 | 3         | 6.52%   |
| Kaisen 1.4 | 3         | 6.52%   |
| Kaisen 2.3 | 2         | 4.35%   |
| Kaisen 1.0 | 1         | 2.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Kaisen | 46        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-kaisen5-amd64   | 12        | 26.09%  |
| 5.17.0-kaisen1-amd64   | 7         | 15.22%  |
| 5.15.0-kaisen1-amd64   | 7         | 15.22%  |
| 6.0.0-1kaisen-amd64    | 5         | 10.87%  |
| 6.1.0-1kaisen-amd64    | 4         | 8.7%    |
| 5.10.0-kaisen3-amd64   | 3         | 6.52%   |
| 5.8.0-kaisen2-amd64    | 2         | 4.35%   |
| 6.0.0-1kaisen-rt-amd64 | 1         | 2.17%   |
| 5.9.0-kaisen2-amd64    | 1         | 2.17%   |
| 5.5.0-kaisen1-amd64    | 1         | 2.17%   |
| 5.19.0-kaisen1-amd64   | 1         | 2.17%   |
| 5.16.0-kaisen1-amd64   | 1         | 2.17%   |
| 5.14.0-kaisen1-amd64   | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 32.61%  |
| 5.17.0  | 7         | 15.22%  |
| 5.15.0  | 7         | 15.22%  |
| 6.0.0   | 6         | 13.04%  |
| 6.1.0   | 4         | 8.7%    |
| 5.8.0   | 2         | 4.35%   |
| 5.9.0   | 1         | 2.17%   |
| 5.5.0   | 1         | 2.17%   |
| 5.19.0  | 1         | 2.17%   |
| 5.16.0  | 1         | 2.17%   |
| 5.14.0  | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 32.61%  |
| 5.17    | 7         | 15.22%  |
| 5.15    | 7         | 15.22%  |
| 6.0     | 6         | 13.04%  |
| 6.1     | 4         | 8.7%    |
| 5.8     | 2         | 4.35%   |
| 5.9     | 1         | 2.17%   |
| 5.5     | 1         | 2.17%   |
| 5.19    | 1         | 2.17%   |
| 5.16    | 1         | 2.17%   |
| 5.14    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 22        | 47.83%  |
| KDE5    | 13        | 28.26%  |
| XFCE    | 7         | 15.22%  |
| LXQt    | 2         | 4.35%   |
| LXDE    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 45        | 97.83%  |
| Tty  | 1         | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 32        | 69.57%  |
| TDM     | 12        | 26.09%  |
| SDDM    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24        | 52.17%  |
| fr_FR   | 11        | 23.91%  |
| pt_BR   | 3         | 6.52%   |
| de_DE   | 2         | 4.35%   |
| nl_NL   | 1         | 2.17%   |
| es_ES   | 1         | 2.17%   |
| en_ZA   | 1         | 2.17%   |
| en_GB   | 1         | 2.17%   |
| de_CH   | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 31        | 67.39%  |
| BIOS | 15        | 32.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 24        | 52.17%  |
| Overlay | 17        | 36.96%  |
| Ext4    | 5         | 10.87%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 33        | 71.74%  |
| MBR     | 12        | 26.09%  |
| Unknown | 1         | 2.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 67.39%  |
| Yes       | 15        | 32.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 60.87%  |
| Yes       | 18        | 39.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 30.43%  |
| Lenovo              | 8         | 17.39%  |
| Dell                | 6         | 13.04%  |
| MSI                 | 5         | 10.87%  |
| Gigabyte Technology | 4         | 8.7%    |
| Samsung Electronics | 2         | 4.35%   |
| ASUSTek Computer    | 2         | 4.35%   |
| Apple               | 2         | 4.35%   |
| Intel               | 1         | 2.17%   |
| Foxconn             | 1         | 2.17%   |
| Acer                | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 840 G2                   | 2         | 4.35%   |
| Samsung 950QDB                        | 1         | 2.17%   |
| Samsung 370E4K                        | 1         | 2.17%   |
| MSI Vector GP76 12UH                  | 1         | 2.17%   |
| MSI MS-7C91                           | 1         | 2.17%   |
| MSI MS-7C56                           | 1         | 2.17%   |
| MSI MS-7B09                           | 1         | 2.17%   |
| MSI MS-7816                           | 1         | 2.17%   |
| Lenovo ThinkPad T520 4243E51          | 1         | 2.17%   |
| Lenovo ThinkPad T450 20BV003SMS       | 1         | 2.17%   |
| Lenovo ThinkPad T431s 20AA000MUS      | 1         | 2.17%   |
| Lenovo ThinkPad T430 23427YU          | 1         | 2.17%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 2.17%   |
| Lenovo ThinkPad L470 20J4CTO1WW       | 1         | 2.17%   |
| Lenovo Legion Y530-15ICH 81FV         | 1         | 2.17%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 2.17%   |
| Intel H61M-S2PV                       | 1         | 2.17%   |
| HP Z400 Workstation                   | 1         | 2.17%   |
| HP ProBook 650 G2                     | 1         | 2.17%   |
| HP ProBook 645 G1                     | 1         | 2.17%   |
| HP Pavilion g7                        | 1         | 2.17%   |
| HP Pavilion 15                        | 1         | 2.17%   |
| HP Notebook                           | 1         | 2.17%   |
| HP Laptop 15-bw0xx                    | 1         | 2.17%   |
| HP EliteDesk 800 G2 TWR               | 1         | 2.17%   |
| HP EliteDesk 800 G1 DM                | 1         | 2.17%   |
| HP EliteBook 840 G1                   | 1         | 2.17%   |
| HP Elite Slice                        | 1         | 2.17%   |
| HP Compaq Pro 6300 MT                 | 1         | 2.17%   |
| Gigabyte M61PM-S2                     | 1         | 2.17%   |
| Gigabyte GA-6PXSV1                    | 1         | 2.17%   |
| Gigabyte B550M AORUS ELITE            | 1         | 2.17%   |
| Gigabyte AX370-Gaming K5              | 1         | 2.17%   |
| Foxconn s5-1204                       | 1         | 2.17%   |
| Dell XPS 13 9310 2-in-1               | 1         | 2.17%   |
| Dell Studio 540                       | 1         | 2.17%   |
| Dell Latitude 3540                    | 1         | 2.17%   |
| Dell Inspiron 15 7000 Gaming          | 1         | 2.17%   |
| Dell Inspiron 14 5401                 | 1         | 2.17%   |
| Dell G3 3500                          | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 13.04%  |
| HP EliteBook          | 3         | 6.52%   |
| HP ProBook            | 2         | 4.35%   |
| HP Pavilion           | 2         | 4.35%   |
| HP EliteDesk          | 2         | 4.35%   |
| Dell Inspiron         | 2         | 4.35%   |
| Samsung 950QDB        | 1         | 2.17%   |
| Samsung 370E4K        | 1         | 2.17%   |
| MSI Vector            | 1         | 2.17%   |
| MSI MS-7C91           | 1         | 2.17%   |
| MSI MS-7C56           | 1         | 2.17%   |
| MSI MS-7B09           | 1         | 2.17%   |
| MSI MS-7816           | 1         | 2.17%   |
| Lenovo Legion         | 1         | 2.17%   |
| Lenovo IdeaPad        | 1         | 2.17%   |
| Intel H61M-S2PV       | 1         | 2.17%   |
| HP Z400               | 1         | 2.17%   |
| HP Notebook           | 1         | 2.17%   |
| HP Laptop             | 1         | 2.17%   |
| HP Elite              | 1         | 2.17%   |
| HP Compaq             | 1         | 2.17%   |
| Gigabyte M61PM-S2     | 1         | 2.17%   |
| Gigabyte GA-6PXSV1    | 1         | 2.17%   |
| Gigabyte B550M        | 1         | 2.17%   |
| Gigabyte AX370-Gaming | 1         | 2.17%   |
| Foxconn s5-1204       | 1         | 2.17%   |
| Dell XPS              | 1         | 2.17%   |
| Dell Studio           | 1         | 2.17%   |
| Dell Latitude         | 1         | 2.17%   |
| Dell G3               | 1         | 2.17%   |
| ASUS N76VB            | 1         | 2.17%   |
| ASUS 970              | 1         | 2.17%   |
| Apple MacBookPro9     | 1         | 2.17%   |
| Apple iMac10          | 1         | 2.17%   |
| Acer Aspire           | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 7         | 15.22%  |
| 2013 | 6         | 13.04%  |
| 2017 | 5         | 10.87%  |
| 2016 | 4         | 8.7%    |
| 2014 | 4         | 8.7%    |
| 2011 | 4         | 8.7%    |
| 2015 | 3         | 6.52%   |
| 2012 | 3         | 6.52%   |
| 2022 | 2         | 4.35%   |
| 2021 | 2         | 4.35%   |
| 2010 | 2         | 4.35%   |
| 2018 | 1         | 2.17%   |
| 2009 | 1         | 2.17%   |
| 2008 | 1         | 2.17%   |
| 2006 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 26        | 56.52%  |
| Desktop     | 16        | 34.78%  |
| Convertible | 2         | 4.35%   |
| All in one  | 1         | 2.17%   |
| Server      | 1         | 2.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 46        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 12        | 26.09%  |
| 4.01-8.0    | 11        | 23.91%  |
| 8.01-16.0   | 11        | 23.91%  |
| 3.01-4.0    | 4         | 8.7%    |
| 32.01-64.0  | 3         | 6.52%   |
| 64.01-256.0 | 3         | 6.52%   |
| 24.01-32.0  | 1         | 2.17%   |
| 1.01-2.0    | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 21        | 45.65%  |
| 2.01-3.0  | 9         | 19.57%  |
| 3.01-4.0  | 5         | 10.87%  |
| 4.01-8.0  | 4         | 8.7%    |
| 0.51-1.0  | 4         | 8.7%    |
| 8.01-16.0 | 3         | 6.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 52.17%  |
| 2      | 16        | 34.78%  |
| 4      | 3         | 6.52%   |
| 5      | 1         | 2.17%   |
| 3      | 1         | 2.17%   |
| 0      | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 60.87%  |
| Yes       | 18        | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 93.48%  |
| No        | 3         | 6.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 76.09%  |
| No        | 11        | 23.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 58.7%   |
| No        | 19        | 41.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 15        | 32.61%  |
| France       | 12        | 26.09%  |
| Brazil       | 4         | 8.7%    |
| Spain        | 3         | 6.52%   |
| UK           | 2         | 4.35%   |
| Germany      | 2         | 4.35%   |
| Switzerland  | 1         | 2.17%   |
| South Africa | 1         | 2.17%   |
| Slovakia     | 1         | 2.17%   |
| Netherlands  | 1         | 2.17%   |
| Mexico       | 1         | 2.17%   |
| India        | 1         | 2.17%   |
| Belgium      | 1         | 2.17%   |
| Australia    | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toulouse               | 2         | 4.35%   |
| Paris                  | 2         | 4.35%   |
| Meulan-en-Yvelines     | 2         | 4.35%   |
| Vitoria-Gasteiz        | 1         | 2.17%   |
| Villejuif              | 1         | 2.17%   |
| Valencia               | 1         | 2.17%   |
| Tresses                | 1         | 2.17%   |
| Starkville             | 1         | 2.17%   |
| Short Hills            | 1         | 2.17%   |
| Segovia                | 1         | 2.17%   |
| Sao Paulo              | 1         | 2.17%   |
| Santa Clara            | 1         | 2.17%   |
| Rio de Janeiro         | 1         | 2.17%   |
| Rieschweiler-Muehlbach | 1         | 2.17%   |
| Reno                   | 1         | 2.17%   |
| Prattville             | 1         | 2.17%   |
| Pinckney               | 1         | 2.17%   |
| Perth                  | 1         | 2.17%   |
| Nitra                  | 1         | 2.17%   |
| Nieuw-Vossemeer        | 1         | 2.17%   |
| Milwaukee              | 1         | 2.17%   |
| Middlesbrough          | 1         | 2.17%   |
| Miami                  | 1         | 2.17%   |
| Medway                 | 1         | 2.17%   |
| Mechanicsburg          | 1         | 2.17%   |
| Manchester             | 1         | 2.17%   |
| Malappuram             | 1         | 2.17%   |
| Madrid                 | 1         | 2.17%   |
| Maceió                | 1         | 2.17%   |
| Las Vegas              | 1         | 2.17%   |
| Lagorce                | 1         | 2.17%   |
| Joaima                 | 1         | 2.17%   |
| Issy-les-Moulineaux    | 1         | 2.17%   |
| Gavere                 | 1         | 2.17%   |
| Friesoythe             | 1         | 2.17%   |
| Fort Lauderdale        | 1         | 2.17%   |
| Edenvale               | 1         | 2.17%   |
| Dijon                  | 1         | 2.17%   |
| Columbus               | 1         | 2.17%   |
| Brive-la-Gaillarde     | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 11        | 15     | 16.18%  |
| WDC                         | 10        | 11     | 14.71%  |
| Seagate                     | 10        | 11     | 14.71%  |
| Kingston                    | 5         | 5      | 7.35%   |
| Toshiba                     | 3         | 3      | 4.41%   |
| SanDisk                     | 3         | 3      | 4.41%   |
| HGST                        | 3         | 3      | 4.41%   |
| KIOXIA                      | 2         | 2      | 2.94%   |
| Intel                       | 2         | 2      | 2.94%   |
| A-DATA Technology           | 2         | 2      | 2.94%   |
| TO Exter                    | 1         | 1      | 1.47%   |
| TCSUNBOW                    | 1         | 1      | 1.47%   |
| SK hynix                    | 1         | 1      | 1.47%   |
| Micron Technology           | 1         | 1      | 1.47%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.47%   |
| MARSHAL                     | 1         | 1      | 1.47%   |
| LITEONIT                    | 1         | 1      | 1.47%   |
| LITEON                      | 1         | 1      | 1.47%   |
| Lexar                       | 1         | 1      | 1.47%   |
| JMicron Technology          | 1         | 1      | 1.47%   |
| Hitachi                     | 1         | 1      | 1.47%   |
| Crucial                     | 1         | 1      | 1.47%   |
| Corsair                     | 1         | 1      | 1.47%   |
| China                       | 1         | 1      | 1.47%   |
| BHT                         | 1         | 1      | 1.47%   |
| ASMedia                     | 1         | 1      | 1.47%   |
| Unknown                     | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD          | 2         | 2.74%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 2.74%   |
| Seagate ST500DM002-1BD142 500GB           | 2         | 2.74%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 2.74%   |
| HGST HTS541010A9E680 1TB                  | 2         | 2.74%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.37%   |
| WDC WD800BB-55JKC0 80GB                   | 1         | 1.37%   |
| WDC WD5003ABYX-18WERA0 500GB              | 1         | 1.37%   |
| WDC WD5000AAKX-60U6AA0 500GB              | 1         | 1.37%   |
| WDC WD3200BPVT-22ZEST0 320GB              | 1         | 1.37%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1.37%   |
| WDC WD20NPVZ-82WFZT0 2TB                  | 1         | 1.37%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.37%   |
| WDC WD10EZEX-75WN4A1 1TB                  | 1         | 1.37%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.37%   |
| Toshiba KXG6AZNV1T02 1TB                  | 1         | 1.37%   |
| Toshiba HDWD130 3TB                       | 1         | 1.37%   |
| TO Exter nal USB 3.0 1TB                  | 1         | 1.37%   |
| TCSUNBOW N4 120GB SSD                     | 1         | 1.37%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.37%   |
| Seagate ST8000DM004-2CX188 8TB            | 1         | 1.37%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1.37%   |
| Seagate ST31000528AS 1TB                  | 1         | 1.37%   |
| Seagate ST2000DM008-2UB102 2TB            | 1         | 1.37%   |
| Seagate ST2000DM008-2FR102 2TB            | 1         | 1.37%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.37%   |
| SanDisk SSD PLUS 120 GB                   | 1         | 1.37%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD       | 1         | 1.37%   |
| SanDisk Portable SSD 1TB                  | 1         | 1.37%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 1.37%   |
| Samsung SSD 970 EVO Plus 500GB            | 1         | 1.37%   |
| Samsung SSD 970 EVO Plus 2TB              | 1         | 1.37%   |
| Samsung SSD 960 EVO 250GB                 | 1         | 1.37%   |
| Samsung SSD 860 QVO 1TB                   | 1         | 1.37%   |
| Samsung SSD 860 EVO 250GB                 | 1         | 1.37%   |
| Samsung SSD 850 PRO 256GB                 | 1         | 1.37%   |
| Samsung SSD 850 EVO 500GB                 | 1         | 1.37%   |
| Samsung SSD 750 EVO 250GB                 | 1         | 1.37%   |
| Samsung MZVLQ1T0HBLB-00B 1TB              | 1         | 1.37%   |
| Samsung MZMPA024HMCD-000L1 24GB SSD       | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 35.71%  |
| WDC                 | 8         | 8      | 28.57%  |
| HGST                | 3         | 3      | 10.71%  |
| Toshiba             | 2         | 2      | 7.14%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| MARSHAL             | 1         | 1      | 3.57%   |
| JMicron Technology  | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| ASMedia             | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 24.14%  |
| Kingston            | 4         | 4      | 13.79%  |
| WDC                 | 3         | 3      | 10.34%  |
| SanDisk             | 3         | 3      | 10.34%  |
| A-DATA Technology   | 2         | 2      | 6.9%    |
| TO Exter            | 1         | 1      | 3.45%   |
| TCSUNBOW            | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |
| LITEON              | 1         | 1      | 3.45%   |
| Lexar               | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| BHT                 | 1         | 1      | 3.45%   |
| Unknown             | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 23        | 29     | 38.98%  |
| HDD  | 23        | 29     | 38.98%  |
| NVMe | 13        | 16     | 22.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 53     | 67.86%  |
| NVMe | 13        | 16     | 23.21%  |
| SAS  | 5         | 5      | 8.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 38     | 61.22%  |
| 0.51-1.0   | 13        | 13     | 26.53%  |
| 1.01-2.0   | 3         | 4      | 6.12%   |
| 2.01-3.0   | 2         | 2      | 4.08%   |
| 4.01-10.0  | 1         | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 8         | 17.39%  |
| 1-20           | 8         | 17.39%  |
| 251-500        | 7         | 15.22%  |
| 1001-2000      | 5         | 10.87%  |
| 501-1000       | 5         | 10.87%  |
| Unknown        | 5         | 10.87%  |
| 51-100         | 4         | 8.7%    |
| 21-50          | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |
| 2001-3000      | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 52.17%  |
| 21-50          | 5         | 10.87%  |
| 501-1000       | 5         | 10.87%  |
| Unknown        | 5         | 10.87%  |
| 101-250        | 4         | 8.7%    |
| More than 3000 | 1         | 2.17%   |
| 251-500        | 1         | 2.17%   |
| 51-100         | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB   | 2         | 2      | 18.18%  |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1         | 1      | 9.09%   |
| WDC WD3200BPVT-22ZEST0 320GB      | 1         | 1      | 9.09%   |
| WDC WD20NPVZ-82WFZT0 2TB          | 1         | 1      | 9.09%   |
| Seagate ST8000DM004-2CX188 8TB    | 1         | 1      | 9.09%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 9.09%   |
| MARSHAL MAL2500SA-T54L 500GB      | 1         | 1      | 9.09%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 9.09%   |
| A-DATA Technology SU635 240GB SSD | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 4      | 36.36%  |
| WDC               | 3         | 3      | 27.27%  |
| MARSHAL           | 1         | 1      | 9.09%   |
| Hitachi           | 1         | 1      | 9.09%   |
| HGST              | 1         | 1      | 9.09%   |
| A-DATA Technology | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| WDC     | 2         | 2      | 22.22%  |
| MARSHAL | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 81.82%  |
| SSD  | 2         | 2      | 18.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 34        | 55     | 64.15%  |
| Malfunc  | 11        | 11     | 20.75%  |
| Detected | 7         | 7      | 13.21%  |
| Failed   | 1         | 1      | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 52.73%  |
| AMD                          | 11        | 20%     |
| Samsung Electronics          | 5         | 9.09%   |
| Nvidia                       | 2         | 3.64%   |
| KIOXIA                       | 2         | 3.64%   |
| Toshiba America Info Systems | 1         | 1.82%   |
| SK hynix                     | 1         | 1.82%   |
| Phison Electronics           | 1         | 1.82%   |
| Micron Technology            | 1         | 1.82%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.82%   |
| Kingston Technology Company  | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 12.9%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 6.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.84%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 4.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 3.23%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.61%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.61%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.61%   |
| Phison E8 PCIe3 NVMe Controller                                                | 1         | 1.61%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.61%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.61%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.61%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.61%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 1.61%   |
| Kingston Company NVMe Controller                                               | 1         | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.61%   |
| Intel SSD 660P Series                                                          | 1         | 1.61%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.61%   |
| Intel C604/X79 series chipset 4-Port SATA/SAS Storage Control Unit             | 1         | 1.61%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.61%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.61%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 1.61%   |
| AMD X370 Series Chipset SATA Controller                                        | 1         | 1.61%   |
| AMD FCH IDE Controller                                                         | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 36        | 64.29%  |
| NVMe | 13        | 23.21%  |
| RAID | 3         | 5.36%   |
| IDE  | 3         | 5.36%   |
| SAS  | 1         | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 71.74%  |
| AMD    | 13        | 28.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz               | 2         | 4.35%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 2         | 4.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 2         | 4.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 4.35%   |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1         | 2.17%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz            | 1         | 2.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 2.17%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 2.17%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 2.17%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 2.17%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 2.17%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 2.17%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1         | 2.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 1         | 2.17%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1         | 2.17%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1         | 2.17%   |
| Intel Core i5-4300U CPU @ 1.90GHz              | 1         | 2.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 2.17%   |
| Intel Core i5-3437U CPU @ 1.90GHz              | 1         | 2.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 2.17%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 2.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1         | 2.17%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz           | 1         | 2.17%   |
| Intel Celeron CPU U3600 @ 1.20GHz              | 1         | 2.17%   |
| Intel 12th Gen Core i7-12700H                  | 1         | 2.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 2.17%   |
| AMD Ryzen Threadripper 2920X 12-Core Processor | 1         | 2.17%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 2.17%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 1         | 2.17%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1         | 2.17%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 2.17%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 2.17%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics    | 1         | 2.17%   |
| AMD Athlon 64 Processor 3800+                  | 1         | 2.17%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 2.17%   |
| AMD A6-5350M APU with Radeon HD Graphics       | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 14        | 30.43%  |
| Intel Core i7          | 7         | 15.22%  |
| Other                  | 5         | 10.87%  |
| Intel Xeon             | 2         | 4.35%   |
| Intel Pentium          | 2         | 4.35%   |
| AMD Ryzen 7            | 2         | 4.35%   |
| AMD Ryzen 5            | 2         | 4.35%   |
| AMD A6                 | 2         | 4.35%   |
| Intel Core i3          | 1         | 2.17%   |
| Intel Core 2 Quad      | 1         | 2.17%   |
| Intel Core 2 Duo       | 1         | 2.17%   |
| Intel Celeron          | 1         | 2.17%   |
| AMD Ryzen Threadripper | 1         | 2.17%   |
| AMD Ryzen 9            | 1         | 2.17%   |
| AMD FX                 | 1         | 2.17%   |
| AMD E2                 | 1         | 2.17%   |
| AMD Athlon 64          | 1         | 2.17%   |
| AMD A10                | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 39.13%  |
| 4      | 16        | 34.78%  |
| 1      | 4         | 8.7%    |
| 12     | 2         | 4.35%   |
| 8      | 2         | 4.35%   |
| 6      | 2         | 4.35%   |
| 14     | 1         | 2.17%   |
| 3      | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 33        | 71.74%  |
| 1      | 13        | 28.26%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 10.87%  |
| 0x306d4    | 4         | 8.7%    |
| 0x806c1    | 3         | 6.52%   |
| 0x206a7    | 3         | 6.52%   |
| Unknown    | 3         | 6.52%   |
| 0x506e3    | 2         | 4.35%   |
| 0xa0652    | 1         | 2.17%   |
| 0x906ea    | 1         | 2.17%   |
| 0x906e9    | 1         | 2.17%   |
| 0x906a3    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x706e5    | 1         | 2.17%   |
| 0x6fb      | 1         | 2.17%   |
| 0x406e3    | 1         | 2.17%   |
| 0x40651    | 1         | 2.17%   |
| 0x306e4    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x20655    | 1         | 2.17%   |
| 0x106a5    | 1         | 2.17%   |
| 0x1067a    | 1         | 2.17%   |
| 0x0a20120a | 1         | 2.17%   |
| 0x0a201016 | 1         | 2.17%   |
| 0x08701021 | 1         | 2.17%   |
| 0x08600106 | 1         | 2.17%   |
| 0x0800820b | 1         | 2.17%   |
| 0x08001137 | 1         | 2.17%   |
| 0x07030106 | 1         | 2.17%   |
| 0x06006705 | 1         | 2.17%   |
| 0x0600111f | 1         | 2.17%   |
| 0x06001119 | 1         | 2.17%   |
| 0x06001116 | 1         | 2.17%   |
| 0x06000822 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 6         | 13.04%  |
| Piledriver       | 4         | 8.7%    |
| Haswell          | 4         | 8.7%    |
| Broadwell        | 4         | 8.7%    |
| TigerLake        | 3         | 6.52%   |
| Skylake          | 3         | 6.52%   |
| SandyBridge      | 3         | 6.52%   |
| KabyLake         | 3         | 6.52%   |
| Zen 3            | 2         | 4.35%   |
| Zen 2            | 2         | 4.35%   |
| Zen+             | 1         | 2.17%   |
| Zen              | 1         | 2.17%   |
| Westmere         | 1         | 2.17%   |
| Puma             | 1         | 2.17%   |
| Penryn           | 1         | 2.17%   |
| Nehalem          | 1         | 2.17%   |
| K8 Hammer        | 1         | 2.17%   |
| IceLake          | 1         | 2.17%   |
| Excavator        | 1         | 2.17%   |
| Core             | 1         | 2.17%   |
| CometLake        | 1         | 2.17%   |
| Alderlake Hybrid | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 53.7%   |
| Nvidia | 13        | 24.07%  |
| AMD    | 12        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                        | 4         | 7.27%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 7.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 5.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 5.45%   |
| Intel HD Graphics 530                                                         | 2         | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 3.64%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 3.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 3.64%   |
| Nvidia TU117M                                                                 | 1         | 1.82%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1         | 1.82%   |
| Nvidia MCP7A [GeForce 9400]                                                   | 1         | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 1.82%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 1.82%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 1.82%   |
| Nvidia GK107M [GeForce GT 740M]                                               | 1         | 1.82%   |
| Nvidia GF119M [Quadro NVS 4200M]                                              | 1         | 1.82%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 1         | 1.82%   |
| Nvidia G94GL [Quadro FX 1800]                                                 | 1         | 1.82%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.82%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.82%   |
| Intel HD Graphics 630                                                         | 1         | 1.82%   |
| Intel HD Graphics 620                                                         | 1         | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.82%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 1.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 1.82%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                    | 1         | 1.82%   |
| AMD Trinity 2 [Radeon HD 7520G]                                               | 1         | 1.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.82%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 1         | 1.82%   |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 1.82%   |
| AMD Richland [Radeon HD 8450G]                                                | 1         | 1.82%   |
| AMD Renoir                                                                    | 1         | 1.82%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 1         | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 43.48%  |
| 1 x AMD        | 9         | 19.57%  |
| 1 x Nvidia     | 7         | 15.22%  |
| Intel + Nvidia | 6         | 13.04%  |
| Intel + AMD    | 2         | 4.35%   |
| 2 x Intel      | 1         | 2.17%   |
| 2 x AMD        | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 93.48%  |
| Proprietary | 2         | 4.35%   |
| Unknown     | 1         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 52.17%  |
| 0.51-1.0   | 6         | 13.04%  |
| 7.01-8.0   | 5         | 10.87%  |
| 1.01-2.0   | 5         | 10.87%  |
| 0.01-0.5   | 4         | 8.7%    |
| 3.01-4.0   | 2         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 7         | 14.89%  |
| LG Display              | 5         | 10.64%  |
| AU Optronics            | 5         | 10.64%  |
| Samsung Electronics     | 4         | 8.51%   |
| Dell                    | 4         | 8.51%   |
| Acer                    | 4         | 8.51%   |
| BOE                     | 3         | 6.38%   |
| Sharp                   | 2         | 4.26%   |
| Chi Mei Optoelectronics | 2         | 4.26%   |
| Apple                   | 2         | 4.26%   |
| Vizio                   | 1         | 2.13%   |
| ViewSonic               | 1         | 2.13%   |
| Philips                 | 1         | 2.13%   |
| PANDA                   | 1         | 2.13%   |
| Lenovo                  | 1         | 2.13%   |
| Iiyama                  | 1         | 2.13%   |
| Hewlett-Packard         | 1         | 2.13%   |
| Grundig                 | 1         | 2.13%   |
| Goldstar                | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 2         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 2         | 4.17%   |
| Vizio E260MV VIZ0062 1920x1080 580x320mm 26.1-inch                        | 1         | 2.08%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 2.08%   |
| Sharp LQ173M1JW08 SHP1544 1920x1080 382x215mm 17.3-inch                   | 1         | 2.08%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch                   | 1         | 2.08%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch        | 1         | 2.08%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch      | 1         | 2.08%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 1         | 2.08%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 1         | 2.08%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch               | 1         | 2.08%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 1         | 2.08%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                      | 1         | 2.08%   |
| Hewlett-Packard V221 HWP3111 1920x1080 477x268mm 21.5-inch                | 1         | 2.08%   |
| Grundig WUXGA GRU4448 1920x1080                                           | 1         | 2.08%   |
| Goldstar E1960 GSM4BE5 1360x768 406x229mm 18.4-inch                       | 1         | 2.08%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                         | 1         | 2.08%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                       | 1         | 2.08%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                        | 1         | 2.08%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                         | 1         | 2.08%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                           | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch           | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 2.08%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 1         | 2.08%   |
| BOE LCD Monitor BOE05FE 1366x768 309x173mm 13.9-inch                      | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO453D 1920x1080 309x174mm 14.0-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch            | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 23        | 52.27%  |
| 1366x768 (WXGA)   | 10        | 22.73%  |
| 1600x900 (HD+)    | 3         | 6.82%   |
| 3840x2160 (4K)    | 2         | 4.55%   |
| 1440x900 (WXGA+)  | 2         | 4.55%   |
| 2560x1440 (QHD)   | 1         | 2.27%   |
| 1920x1200 (WUXGA) | 1         | 2.27%   |
| 1360x768          | 1         | 2.27%   |
| 1280x800 (WXGA)   | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 11        | 23.4%   |
| 14     | 7         | 14.89%  |
| 13     | 6         | 12.77%  |
| 21     | 4         | 8.51%   |
| 23     | 3         | 6.38%   |
| 17     | 3         | 6.38%   |
| 31     | 2         | 4.26%   |
| 27     | 2         | 4.26%   |
| 19     | 2         | 4.26%   |
| 18     | 2         | 4.26%   |
| 54     | 1         | 2.13%   |
| 26     | 1         | 2.13%   |
| 25     | 1         | 2.13%   |
| 24     | 1         | 2.13%   |
| 11     | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 46.81%  |
| 501-600     | 8         | 17.02%  |
| 401-500     | 8         | 17.02%  |
| 351-400     | 3         | 6.38%   |
| 201-300     | 3         | 6.38%   |
| 601-700     | 2         | 4.26%   |
| 1001-1500   | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 39        | 90.7%   |
| 16/10 | 4         | 9.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 25.53%  |
| 101-110        | 11        | 23.4%   |
| 201-250        | 6         | 12.77%  |
| 151-200        | 5         | 10.64%  |
| 121-130        | 3         | 6.38%   |
| 351-500        | 2         | 4.26%   |
| 301-350        | 2         | 4.26%   |
| 251-300        | 2         | 4.26%   |
| More than 1000 | 1         | 2.13%   |
| 71-80          | 1         | 2.13%   |
| 51-60          | 1         | 2.13%   |
| 141-150        | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 17        | 36.17%  |
| 101-120 | 15        | 31.91%  |
| 51-100  | 13        | 27.66%  |
| 1-50    | 1         | 2.13%   |
| 161-240 | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 82.61%  |
| 2     | 7         | 15.22%  |
| 0     | 1         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 36.23%  |
| Realtek Semiconductor | 20        | 28.99%  |
| Qualcomm Atheros      | 11        | 15.94%  |
| TP-Link               | 4         | 5.8%    |
| Broadcom              | 3         | 4.35%   |
| Nvidia                | 2         | 2.9%    |
| Lenovo                | 2         | 2.9%    |
| Sierra Wireless       | 1         | 1.45%   |
| ASUSTek Computer      | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 12.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.71%   |
| Intel Wireless 7265                                               | 4         | 4.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 2.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 2.35%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.35%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.35%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                       | 1         | 1.18%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.18%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.18%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.18%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.18%   |
| Realtek 802.11ac NIC                                              | 1         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.18%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.18%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.18%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.18%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.18%   |
| Lenovo P2a42                                                      | 1         | 1.18%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.18%   |
| Intel Wireless 8260                                               | 1         | 1.18%   |
| Intel Wireless 7260                                               | 1         | 1.18%   |
| Intel Wireless 3165                                               | 1         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.18%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.18%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.18%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 46.15%  |
| Qualcomm Atheros      | 10        | 25.64%  |
| TP-Link               | 4         | 10.26%  |
| Realtek Semiconductor | 3         | 7.69%   |
| Broadcom              | 2         | 5.13%   |
| Sierra Wireless       | 1         | 2.56%   |
| ASUSTek Computer      | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 4         | 10.26%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 7.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 5.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 5.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 5.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 5.13%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 5.13%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1         | 2.56%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 2.56%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 2.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 2.56%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.56%   |
| Realtek 802.11ac NIC                                           | 1         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.56%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.56%   |
| Intel Wireless 8260                                            | 1         | 2.56%   |
| Intel Wireless 7260                                            | 1         | 2.56%   |
| Intel Wireless 3165                                            | 1         | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 2.56%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.56%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 2.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.56%   |
| ASUS 802.11ac NIC                                              | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 42.22%  |
| Intel                 | 17        | 37.78%  |
| Qualcomm Atheros      | 3         | 6.67%   |
| Nvidia                | 2         | 4.44%   |
| Lenovo                | 2         | 4.44%   |
| Broadcom              | 2         | 4.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 23.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 10.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 4.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.17%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.17%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.17%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.17%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 2.17%   |
| Lenovo P2a42                                                      | 1         | 2.17%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.17%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.17%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 2.17%   |
| Intel 82575EB Gigabit Network Connection                          | 1         | 2.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 55.13%  |
| WiFi     | 35        | 44.87%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 53.06%  |
| WiFi     | 23        | 46.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 58.7%   |
| 1     | 17        | 36.96%  |
| 4     | 1         | 2.17%   |
| 0     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 71.74%  |
| Yes  | 13        | 28.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 48.15%  |
| Qualcomm Atheros Communications | 5         | 18.52%  |
| Broadcom                        | 4         | 14.81%  |
| Apple                           | 2         | 7.41%   |
| IMC Networks                    | 1         | 3.7%    |
| Foxconn / Hon Hai               | 1         | 3.7%    |
| Cambridge Silicon Radio         | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 25.93%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 11.11%  |
| Intel AX201 Bluetooth                               | 2         | 7.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 7.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.7%    |
| Intel Bluetooth Device                              | 1         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.7%    |
| Intel AX210 Bluetooth                               | 1         | 3.7%    |
| Intel AX200 Bluetooth                               | 1         | 3.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.7%    |
| Foxconn / Hon Hai Acer Module                       | 1         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.7%    |
| Broadcom HP Portable Bumble Bee                     | 1         | 3.7%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.7%    |
| Apple Bluetooth USB Host Controller                 | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 50.79%  |
| AMD                 | 13        | 20.63%  |
| Nvidia              | 12        | 19.05%  |
| Roland              | 1         | 1.59%   |
| Plantronics         | 1         | 1.59%   |
| Logitech            | 1         | 1.59%   |
| Lenovo              | 1         | 1.59%   |
| C-Media Electronics | 1         | 1.59%   |
| ASUSTek Computer    | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller          | 5         | 6.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                      | 4         | 5.19%   |
| Intel Broadwell-U Audio Controller                                           | 4         | 5.19%   |
| AMD FCH Azalia Controller                                                    | 4         | 5.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                  | 3         | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller   | 3         | 3.9%    |
| AMD Trinity HDMI Audio Controller                                            | 3         | 3.9%    |
| Nvidia GP107GL High Definition Audio Controller                              | 2         | 2.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                        | 2         | 2.6%    |
| Intel Sunrise Point-LP HD Audio                                              | 2         | 2.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                             | 2         | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller          | 2         | 2.6%    |
| Intel 8 Series HD Audio Controller                                           | 2         | 2.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller              | 2         | 2.6%    |
| AMD Starship/Matisse HD Audio Controller                                     | 2         | 2.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                          | 2         | 2.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                   | 2         | 2.6%    |
| Roland QUAD-CAPTURE                                                          | 1         | 1.3%    |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter) | 1         | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller               | 1         | 1.3%    |
| Nvidia TU106 High Definition Audio Controller                                | 1         | 1.3%    |
| Nvidia MCP79 High Definition Audio                                           | 1         | 1.3%    |
| Nvidia MCP61 High Definition Audio                                           | 1         | 1.3%    |
| Nvidia GP108 High Definition Audio Controller                                | 1         | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                           | 1         | 1.3%    |
| Nvidia GF119 HDMI Audio Controller                                           | 1         | 1.3%    |
| Nvidia GA104 High Definition Audio Controller                                | 1         | 1.3%    |
| Logitech [G533 Wireless Headset Dongle]                                      | 1         | 1.3%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                    | 1         | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller             | 1         | 1.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                    | 1         | 1.3%    |
| Intel Haswell-ULT HD Audio Controller                                        | 1         | 1.3%    |
| Intel Comet Lake PCH cAVS                                                    | 1         | 1.3%    |
| Intel CM238 HD Audio Controller                                              | 1         | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                   | 1         | 1.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller               | 1         | 1.3%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                      | 1         | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                     | 1         | 1.3%    |
| C-Media Electronics CM108 Audio Controller                                   | 1         | 1.3%    |
| ASUSTek Computer Xonar SoundCard                                             | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 12        | 21.82%  |
| Samsung Electronics | 12        | 21.82%  |
| Kingston            | 7         | 12.73%  |
| Crucial             | 6         | 10.91%  |
| Micron Technology   | 4         | 7.27%   |
| Unknown             | 2         | 3.64%   |
| G.Skill             | 2         | 3.64%   |
| Corsair             | 2         | 3.64%   |
| A-DATA Technology   | 2         | 3.64%   |
| Team                | 1         | 1.82%   |
| Ramaxel Technology  | 1         | 1.82%   |
| Elpida              | 1         | 1.82%   |
| Apacer              | 1         | 1.82%   |
| A Force             | 1         | 1.82%   |
| 8A020000802C        | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 3.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 3.33%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2         | 3.33%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 3.33%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.67%   |
| Unknown RAM Module 1GB DIMM 400MT/s                          | 1         | 1.67%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.67%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1         | 1.67%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s         | 1         | 1.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 1.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.67%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.67%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s    | 1         | 1.67%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.67%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.67%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.67%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.67%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.67%   |
| Samsung RAM M471B5173BH0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.67%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.67%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s          | 1         | 1.67%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.67%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.67%   |
| Samsung RAM 456789ABCDEFGHIJKL 8GB SODIMM DDR3 1600MT/s      | 1         | 1.67%   |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.67%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.67%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 1         | 1.67%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.67%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s         | 1         | 1.67%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s         | 1         | 1.67%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s        | 1         | 1.67%   |
| Kingston RAM ASU16D3LS1KBG/4G 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.67%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s        | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 24        | 53.33%  |
| DDR4    | 17        | 37.78%  |
| LPDDR4  | 2         | 4.44%   |
| DDR2    | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 60.87%  |
| DIMM         | 14        | 30.43%  |
| Row Of Chips | 3         | 6.52%   |
| Chip         | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 48%     |
| 4096  | 14        | 28%     |
| 16384 | 6         | 12%     |
| 2048  | 4         | 8%      |
| 32768 | 1         | 2%      |
| 1024  | 1         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 38.3%   |
| 3200  | 5         | 10.64%  |
| 2667  | 4         | 8.51%   |
| 1333  | 3         | 6.38%   |
| 4267  | 2         | 4.26%   |
| 3600  | 2         | 4.26%   |
| 2400  | 2         | 4.26%   |
| 2133  | 2         | 4.26%   |
| 49926 | 1         | 2.13%   |
| 3933  | 1         | 2.13%   |
| 3733  | 1         | 2.13%   |
| 2933  | 1         | 2.13%   |
| 1648  | 1         | 2.13%   |
| 1334  | 1         | 2.13%   |
| 1067  | 1         | 2.13%   |
| 800   | 1         | 2.13%   |
| 400   | 1         | 2.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Kyocera             | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung M2070 Series    | 1         | 50%     |
| Kyocera ECOSYS P5021cdw | 1         | 50%     |

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
| Chicony Electronics                    | 6         | 21.43%  |
| Realtek Semiconductor                  | 3         | 10.71%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 10.71%  |
| Bison Electronics                      | 3         | 10.71%  |
| Sunplus Innovation Technology          | 2         | 7.14%   |
| Microdia                               | 2         | 7.14%   |
| Apple                                  | 2         | 7.14%   |
| Suyin                                  | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.57%   |
| Quanta                                 | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |
| IMC Networks                           | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                            | 2         | 7.14%   |
| Chicony Integrated Camera                               | 2         | 7.14%   |
| Chicony HP HD Webcam                                    | 2         | 7.14%   |
| Bison Integrated Camera                                 | 2         | 7.14%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 3.57%   |
| Sunplus Integrated Webcam                               | 1         | 3.57%   |
| Sunplus Asus Webcam                                     | 1         | 3.57%   |
| Silicon Motion ATIV VGA Camera                          | 1         | 3.57%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 1         | 3.57%   |
| Realtek Integrated Camera                               | 1         | 3.57%   |
| Quanta HP TrueVision HD Camera                          | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                           | 1         | 3.57%   |
| Lite-On HP HD Webcam                                    | 1         | 3.57%   |
| IMC Networks Integrated Camera                          | 1         | 3.57%   |
| Chicony HP Truevision HD                                | 1         | 3.57%   |
| Chicony HP HD Camera                                    | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 3.57%   |
| Bison HD Webcam                                         | 1         | 3.57%   |
| Apple FaceTime HD Camera                                | 1         | 3.57%   |
| Apple Built-in iSight                                   | 1         | 3.57%   |
| Acer Integrated Camera                                  | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 71.43%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 4         | 57.14%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device          | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader           | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 28        | 60.87%  |
| 1     | 15        | 32.61%  |
| 2     | 2         | 4.35%   |
| 3     | 1         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 7         | 38.89%  |
| Net/wireless       | 5         | 27.78%  |
| Chipcard           | 2         | 11.11%  |
| Unassigned class   | 1         | 5.56%   |
| Graphics card      | 1         | 5.56%   |
| Card reader        | 1         | 5.56%   |
| Camera             | 1         | 5.56%   |

