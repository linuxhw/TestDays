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

Total: 51

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Kaisen 1.8 | 12        | 27.27%  |
| Kaisen 2.2 | 8         | 18.18%  |
| Kaisen 2.1 | 8         | 18.18%  |
| Kaisen 2.0 | 6         | 13.64%  |
| Kaisen 1.7 | 3         | 6.82%   |
| Kaisen 1.6 | 3         | 6.82%   |
| Kaisen 1.4 | 3         | 6.82%   |
| Kaisen 1.0 | 1         | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Kaisen | 44        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-kaisen5-amd64   | 12        | 27.27%  |
| 5.17.0-kaisen1-amd64   | 7         | 15.91%  |
| 5.15.0-kaisen1-amd64   | 7         | 15.91%  |
| 6.0.0-1kaisen-amd64    | 5         | 11.36%  |
| 5.10.0-kaisen3-amd64   | 3         | 6.82%   |
| 6.1.0-1kaisen-amd64    | 2         | 4.55%   |
| 5.8.0-kaisen2-amd64    | 2         | 4.55%   |
| 6.0.0-1kaisen-rt-amd64 | 1         | 2.27%   |
| 5.9.0-kaisen2-amd64    | 1         | 2.27%   |
| 5.5.0-kaisen1-amd64    | 1         | 2.27%   |
| 5.19.0-kaisen1-amd64   | 1         | 2.27%   |
| 5.16.0-kaisen1-amd64   | 1         | 2.27%   |
| 5.14.0-kaisen1-amd64   | 1         | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 34.09%  |
| 5.17.0  | 7         | 15.91%  |
| 5.15.0  | 7         | 15.91%  |
| 6.0.0   | 6         | 13.64%  |
| 6.1.0   | 2         | 4.55%   |
| 5.8.0   | 2         | 4.55%   |
| 5.9.0   | 1         | 2.27%   |
| 5.5.0   | 1         | 2.27%   |
| 5.19.0  | 1         | 2.27%   |
| 5.16.0  | 1         | 2.27%   |
| 5.14.0  | 1         | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 34.09%  |
| 5.17    | 7         | 15.91%  |
| 5.15    | 7         | 15.91%  |
| 6.0     | 6         | 13.64%  |
| 6.1     | 2         | 4.55%   |
| 5.8     | 2         | 4.55%   |
| 5.9     | 1         | 2.27%   |
| 5.5     | 1         | 2.27%   |
| 5.19    | 1         | 2.27%   |
| 5.16    | 1         | 2.27%   |
| 5.14    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 44        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 22        | 50%     |
| KDE5    | 13        | 29.55%  |
| XFCE    | 5         | 11.36%  |
| LXQt    | 2         | 4.55%   |
| LXDE    | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 44        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 30        | 68.18%  |
| TDM     | 12        | 27.27%  |
| SDDM    | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 23        | 52.27%  |
| fr_FR   | 11        | 25%     |
| pt_BR   | 3         | 6.82%   |
| de_DE   | 2         | 4.55%   |
| nl_NL   | 1         | 2.27%   |
| en_ZA   | 1         | 2.27%   |
| en_GB   | 1         | 2.27%   |
| de_CH   | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 29        | 65.91%  |
| BIOS | 15        | 34.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 24        | 54.55%  |
| Overlay | 15        | 34.09%  |
| Ext4    | 5         | 11.36%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 31        | 70.45%  |
| MBR     | 12        | 27.27%  |
| Unknown | 1         | 2.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 65.91%  |
| Yes       | 15        | 34.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 59.09%  |
| Yes       | 18        | 40.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 29.55%  |
| Lenovo              | 8         | 18.18%  |
| Dell                | 6         | 13.64%  |
| MSI                 | 4         | 9.09%   |
| Gigabyte Technology | 4         | 9.09%   |
| Samsung Electronics | 2         | 4.55%   |
| ASUSTek Computer    | 2         | 4.55%   |
| Apple               | 2         | 4.55%   |
| Intel               | 1         | 2.27%   |
| Foxconn             | 1         | 2.27%   |
| Acer                | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 840 G2                   | 2         | 4.55%   |
| Samsung 950QDB                        | 1         | 2.27%   |
| Samsung 370E4K                        | 1         | 2.27%   |
| MSI Vector GP76 12UH                  | 1         | 2.27%   |
| MSI MS-7C56                           | 1         | 2.27%   |
| MSI MS-7B09                           | 1         | 2.27%   |
| MSI MS-7816                           | 1         | 2.27%   |
| Lenovo ThinkPad T520 4243E51          | 1         | 2.27%   |
| Lenovo ThinkPad T450 20BV003SMS       | 1         | 2.27%   |
| Lenovo ThinkPad T431s 20AA000MUS      | 1         | 2.27%   |
| Lenovo ThinkPad T430 23427YU          | 1         | 2.27%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 2.27%   |
| Lenovo ThinkPad L470 20J4CTO1WW       | 1         | 2.27%   |
| Lenovo Legion Y530-15ICH 81FV         | 1         | 2.27%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 2.27%   |
| Intel H61M-S2PV                       | 1         | 2.27%   |
| HP Z400 Workstation                   | 1         | 2.27%   |
| HP ProBook 650 G2                     | 1         | 2.27%   |
| HP ProBook 645 G1                     | 1         | 2.27%   |
| HP Pavilion g7                        | 1         | 2.27%   |
| HP Pavilion 15                        | 1         | 2.27%   |
| HP Laptop 15-bw0xx                    | 1         | 2.27%   |
| HP EliteDesk 800 G2 TWR               | 1         | 2.27%   |
| HP EliteDesk 800 G1 DM                | 1         | 2.27%   |
| HP EliteBook 840 G1                   | 1         | 2.27%   |
| HP Elite Slice                        | 1         | 2.27%   |
| HP Compaq Pro 6300 MT                 | 1         | 2.27%   |
| Gigabyte M61PM-S2                     | 1         | 2.27%   |
| Gigabyte GA-6PXSV1                    | 1         | 2.27%   |
| Gigabyte B550M AORUS ELITE            | 1         | 2.27%   |
| Gigabyte AX370-Gaming K5              | 1         | 2.27%   |
| Foxconn s5-1204                       | 1         | 2.27%   |
| Dell XPS 13 9310 2-in-1               | 1         | 2.27%   |
| Dell Studio 540                       | 1         | 2.27%   |
| Dell Latitude 3540                    | 1         | 2.27%   |
| Dell Inspiron 15 7000 Gaming          | 1         | 2.27%   |
| Dell Inspiron 14 5401                 | 1         | 2.27%   |
| Dell G3 3500                          | 1         | 2.27%   |
| ASUS N76VB                            | 1         | 2.27%   |
| ASUS 970 PRO GAMING/AURA              | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 13.64%  |
| HP EliteBook          | 3         | 6.82%   |
| HP ProBook            | 2         | 4.55%   |
| HP Pavilion           | 2         | 4.55%   |
| HP EliteDesk          | 2         | 4.55%   |
| Dell Inspiron         | 2         | 4.55%   |
| Samsung 950QDB        | 1         | 2.27%   |
| Samsung 370E4K        | 1         | 2.27%   |
| MSI Vector            | 1         | 2.27%   |
| MSI MS-7C56           | 1         | 2.27%   |
| MSI MS-7B09           | 1         | 2.27%   |
| MSI MS-7816           | 1         | 2.27%   |
| Lenovo Legion         | 1         | 2.27%   |
| Lenovo IdeaPad        | 1         | 2.27%   |
| Intel H61M-S2PV       | 1         | 2.27%   |
| HP Z400               | 1         | 2.27%   |
| HP Laptop             | 1         | 2.27%   |
| HP Elite              | 1         | 2.27%   |
| HP Compaq             | 1         | 2.27%   |
| Gigabyte M61PM-S2     | 1         | 2.27%   |
| Gigabyte GA-6PXSV1    | 1         | 2.27%   |
| Gigabyte B550M        | 1         | 2.27%   |
| Gigabyte AX370-Gaming | 1         | 2.27%   |
| Foxconn s5-1204       | 1         | 2.27%   |
| Dell XPS              | 1         | 2.27%   |
| Dell Studio           | 1         | 2.27%   |
| Dell Latitude         | 1         | 2.27%   |
| Dell G3               | 1         | 2.27%   |
| ASUS N76VB            | 1         | 2.27%   |
| ASUS 970              | 1         | 2.27%   |
| Apple MacBookPro9     | 1         | 2.27%   |
| Apple iMac10          | 1         | 2.27%   |
| Acer Aspire           | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 6         | 13.64%  |
| 2013 | 6         | 13.64%  |
| 2017 | 5         | 11.36%  |
| 2016 | 4         | 9.09%   |
| 2015 | 4         | 9.09%   |
| 2011 | 4         | 9.09%   |
| 2014 | 3         | 6.82%   |
| 2012 | 3         | 6.82%   |
| 2021 | 2         | 4.55%   |
| 2010 | 2         | 4.55%   |
| 2022 | 1         | 2.27%   |
| 2018 | 1         | 2.27%   |
| 2009 | 1         | 2.27%   |
| 2008 | 1         | 2.27%   |
| 2006 | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 25        | 56.82%  |
| Desktop     | 15        | 34.09%  |
| Convertible | 2         | 4.55%   |
| All in one  | 1         | 2.27%   |
| Server      | 1         | 2.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 44        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 12        | 27.27%  |
| 8.01-16.0   | 11        | 25%     |
| 4.01-8.0    | 10        | 22.73%  |
| 3.01-4.0    | 4         | 9.09%   |
| 32.01-64.0  | 3         | 6.82%   |
| 64.01-256.0 | 2         | 4.55%   |
| 24.01-32.0  | 1         | 2.27%   |
| 1.01-2.0    | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 19        | 43.18%  |
| 2.01-3.0  | 9         | 20.45%  |
| 3.01-4.0  | 5         | 11.36%  |
| 4.01-8.0  | 4         | 9.09%   |
| 0.51-1.0  | 4         | 9.09%   |
| 8.01-16.0 | 3         | 6.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 52.27%  |
| 2      | 15        | 34.09%  |
| 4      | 3         | 6.82%   |
| 5      | 1         | 2.27%   |
| 3      | 1         | 2.27%   |
| 0      | 1         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 61.36%  |
| Yes       | 17        | 38.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 93.18%  |
| No        | 3         | 6.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 77.27%  |
| No        | 10        | 22.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 59.09%  |
| No        | 18        | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 31.82%  |
| France       | 12        | 27.27%  |
| Brazil       | 4         | 9.09%   |
| UK           | 2         | 4.55%   |
| Spain        | 2         | 4.55%   |
| Germany      | 2         | 4.55%   |
| Switzerland  | 1         | 2.27%   |
| South Africa | 1         | 2.27%   |
| Slovakia     | 1         | 2.27%   |
| Netherlands  | 1         | 2.27%   |
| Mexico       | 1         | 2.27%   |
| India        | 1         | 2.27%   |
| Belgium      | 1         | 2.27%   |
| Australia    | 1         | 2.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toulouse               | 2         | 4.55%   |
| Paris                  | 2         | 4.55%   |
| Meulan-en-Yvelines     | 2         | 4.55%   |
| Zumarraga              | 1         | 2.27%   |
| Villejuif              | 1         | 2.27%   |
| Valencia               | 1         | 2.27%   |
| Turlock                | 1         | 2.27%   |
| Tresses                | 1         | 2.27%   |
| Short Hills            | 1         | 2.27%   |
| Segovia                | 1         | 2.27%   |
| Sao Paulo              | 1         | 2.27%   |
| Rio de Janeiro         | 1         | 2.27%   |
| Rieschweiler-Muehlbach | 1         | 2.27%   |
| Prattville             | 1         | 2.27%   |
| Pinckney               | 1         | 2.27%   |
| Perth                  | 1         | 2.27%   |
| Nitra                  | 1         | 2.27%   |
| Nieuw-Vossemeer        | 1         | 2.27%   |
| Milwaukee              | 1         | 2.27%   |
| Middlesbrough          | 1         | 2.27%   |
| Miami                  | 1         | 2.27%   |
| Medway                 | 1         | 2.27%   |
| Mechanicsburg          | 1         | 2.27%   |
| Manchester             | 1         | 2.27%   |
| Malappuram             | 1         | 2.27%   |
| Maceió                | 1         | 2.27%   |
| Los Angeles            | 1         | 2.27%   |
| Las Vegas              | 1         | 2.27%   |
| La Clotte              | 1         | 2.27%   |
| Joaima                 | 1         | 2.27%   |
| Issy-les-Moulineaux    | 1         | 2.27%   |
| Gavere                 | 1         | 2.27%   |
| Friesoythe             | 1         | 2.27%   |
| Fort Lauderdale        | 1         | 2.27%   |
| Edenvale               | 1         | 2.27%   |
| Dijon                  | 1         | 2.27%   |
| Columbus               | 1         | 2.27%   |
| Brive-la-Gaillarde     | 1         | 2.27%   |
| Bern                   | 1         | 2.27%   |
| Apodaca                | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 10        | 11     | 15.38%  |
| Seagate                     | 10        | 11     | 15.38%  |
| Samsung Electronics         | 10        | 14     | 15.38%  |
| Kingston                    | 5         | 5      | 7.69%   |
| Toshiba                     | 3         | 3      | 4.62%   |
| SanDisk                     | 3         | 3      | 4.62%   |
| HGST                        | 3         | 3      | 4.62%   |
| KIOXIA                      | 2         | 2      | 3.08%   |
| Intel                       | 2         | 2      | 3.08%   |
| A-DATA Technology           | 2         | 2      | 3.08%   |
| TO Exter                    | 1         | 1      | 1.54%   |
| TCSUNBOW                    | 1         | 1      | 1.54%   |
| SK hynix                    | 1         | 1      | 1.54%   |
| Micron Technology           | 1         | 1      | 1.54%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.54%   |
| MARSHAL                     | 1         | 1      | 1.54%   |
| LITEONIT                    | 1         | 1      | 1.54%   |
| LITEON                      | 1         | 1      | 1.54%   |
| JMicron Technology          | 1         | 1      | 1.54%   |
| Hitachi                     | 1         | 1      | 1.54%   |
| Crucial                     | 1         | 1      | 1.54%   |
| Corsair                     | 1         | 1      | 1.54%   |
| China                       | 1         | 1      | 1.54%   |
| ASMedia                     | 1         | 1      | 1.54%   |
| Unknown                     | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD          | 2         | 2.86%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 2.86%   |
| Seagate ST500DM002-1BD142 500GB           | 2         | 2.86%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 2.86%   |
| HGST HTS541010A9E680 1TB                  | 2         | 2.86%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.43%   |
| WDC WD800BB-55JKC0 80GB                   | 1         | 1.43%   |
| WDC WD5003ABYX-18WERA0 500GB              | 1         | 1.43%   |
| WDC WD5000AAKX-60U6AA0 500GB              | 1         | 1.43%   |
| WDC WD3200BPVT-22ZEST0 320GB              | 1         | 1.43%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1.43%   |
| WDC WD20NPVZ-82WFZT0 2TB                  | 1         | 1.43%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.43%   |
| WDC WD10EZEX-75WN4A1 1TB                  | 1         | 1.43%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.43%   |
| Toshiba KXG6AZNV1T02 1TB                  | 1         | 1.43%   |
| Toshiba HDWD130 3TB                       | 1         | 1.43%   |
| TO Exter nal USB 3.0 320GB                | 1         | 1.43%   |
| TCSUNBOW N4 120GB SSD                     | 1         | 1.43%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.43%   |
| Seagate ST8000DM004-2CX188 8TB            | 1         | 1.43%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1.43%   |
| Seagate ST31000528AS 1TB                  | 1         | 1.43%   |
| Seagate ST2000DM008-2UB102 2TB            | 1         | 1.43%   |
| Seagate ST2000DM008-2FR102 2TB            | 1         | 1.43%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.43%   |
| SanDisk SSD PLUS 120 GB                   | 1         | 1.43%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD       | 1         | 1.43%   |
| SanDisk Portable SSD 1TB                  | 1         | 1.43%   |
| Samsung SSD 970 EVO Plus 500GB            | 1         | 1.43%   |
| Samsung SSD 970 EVO Plus 2TB              | 1         | 1.43%   |
| Samsung SSD 960 EVO 250GB                 | 1         | 1.43%   |
| Samsung SSD 860 QVO 1TB                   | 1         | 1.43%   |
| Samsung SSD 860 EVO 250GB                 | 1         | 1.43%   |
| Samsung SSD 850 PRO 256GB                 | 1         | 1.43%   |
| Samsung SSD 850 EVO 500GB                 | 1         | 1.43%   |
| Samsung SSD 750 EVO 250GB                 | 1         | 1.43%   |
| Samsung MZVLQ1T0HBLB-00B 1TB              | 1         | 1.43%   |
| Samsung MZMPA024HMCD-000L1 24GB SSD       | 1         | 1.43%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD      | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 25.93%  |
| Kingston            | 4         | 4      | 14.81%  |
| WDC                 | 3         | 3      | 11.11%  |
| SanDisk             | 3         | 3      | 11.11%  |
| A-DATA Technology   | 2         | 2      | 7.41%   |
| TO Exter            | 1         | 1      | 3.7%    |
| TCSUNBOW            | 1         | 1      | 3.7%    |
| LITEONIT            | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |
| China               | 1         | 1      | 3.7%    |
| Unknown             | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 29     | 40.35%  |
| SSD  | 22        | 27     | 38.6%   |
| NVMe | 12        | 15     | 21.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 51     | 68.52%  |
| NVMe | 12        | 15     | 22.22%  |
| SAS  | 5         | 5      | 9.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 36     | 59.57%  |
| 0.51-1.0   | 12        | 12     | 25.53%  |
| 1.01-2.0   | 4         | 5      | 8.51%   |
| 2.01-3.0   | 2         | 2      | 4.26%   |
| 4.01-10.0  | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 8         | 18.18%  |
| 251-500        | 7         | 15.91%  |
| 1-20           | 7         | 15.91%  |
| 1001-2000      | 5         | 11.36%  |
| 501-1000       | 5         | 11.36%  |
| Unknown        | 5         | 11.36%  |
| 51-100         | 4         | 9.09%   |
| More than 3000 | 1         | 2.27%   |
| 21-50          | 1         | 2.27%   |
| 2001-3000      | 1         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 50%     |
| 21-50          | 5         | 11.36%  |
| 501-1000       | 5         | 11.36%  |
| Unknown        | 5         | 11.36%  |
| 101-250        | 4         | 9.09%   |
| More than 3000 | 1         | 2.27%   |
| 251-500        | 1         | 2.27%   |
| 51-100         | 1         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 81.82%  |
| SSD  | 2         | 2      | 18.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 32        | 52     | 62.75%  |
| Malfunc  | 11        | 11     | 21.57%  |
| Detected | 7         | 7      | 13.73%  |
| Failed   | 1         | 1      | 1.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 55.77%  |
| AMD                          | 9         | 17.31%  |
| Samsung Electronics          | 4         | 7.69%   |
| Nvidia                       | 2         | 3.85%   |
| KIOXIA                       | 2         | 3.85%   |
| Toshiba America Info Systems | 1         | 1.92%   |
| SK hynix                     | 1         | 1.92%   |
| Phison Electronics           | 1         | 1.92%   |
| Micron Technology            | 1         | 1.92%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.92%   |
| Kingston Technology Company  | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 11.86%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 6.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 5.08%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 3.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 3.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.69%   |
| SK hynix BC511                                                                 | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.69%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.69%   |
| Phison NVMe Storage Controller                                                 | 1         | 1.69%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.69%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.69%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.69%   |
| Micron NVMe Storage Controller                                                 | 1         | 1.69%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 1.69%   |
| Kingston Company NVMe Controller                                               | 1         | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.69%   |
| Intel SSD 660P Series                                                          | 1         | 1.69%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.69%   |
| Intel C604/X79 series chipset 4-Port SATA/SAS Storage Control Unit             | 1         | 1.69%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.69%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.69%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.69%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 1.69%   |
| AMD X370 Series Chipset SATA Controller                                        | 1         | 1.69%   |
| AMD FCH IDE Controller                                                         | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 64.15%  |
| NVMe | 12        | 22.64%  |
| RAID | 3         | 5.66%   |
| IDE  | 3         | 5.66%   |
| SAS  | 1         | 1.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 75%     |
| AMD    | 11        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz               | 2         | 4.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 2         | 4.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 2         | 4.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 4.55%   |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1         | 2.27%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz            | 1         | 2.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 2.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 2.27%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 2.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 2.27%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 2.27%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 2.27%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 2.27%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1         | 2.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 1         | 2.27%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1         | 2.27%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1         | 2.27%   |
| Intel Core i5-4300U CPU @ 1.90GHz              | 1         | 2.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 2.27%   |
| Intel Core i5-3437U CPU @ 1.90GHz              | 1         | 2.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 2.27%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 2.27%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 2.27%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1         | 2.27%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz           | 1         | 2.27%   |
| Intel Celeron CPU U3600 @ 1.20GHz              | 1         | 2.27%   |
| Intel 12th Gen Core i7-12700H                  | 1         | 2.27%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 2.27%   |
| AMD Ryzen Threadripper 2920X 12-Core Processor | 1         | 2.27%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 1         | 2.27%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1         | 2.27%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 2.27%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 2.27%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 2.27%   |
| AMD Athlon 64 Processor 3800+                  | 1         | 2.27%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 2.27%   |
| AMD A6-5350M APU with Radeon HD Graphics       | 1         | 2.27%   |
| AMD A6-4400M APU with Radeon HD Graphics       | 1         | 2.27%   |
| AMD A10-5745M APU with Radeon HD Graphics      | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 14        | 31.82%  |
| Intel Core i7          | 7         | 15.91%  |
| Other                  | 5         | 11.36%  |
| Intel Xeon             | 2         | 4.55%   |
| Intel Pentium          | 2         | 4.55%   |
| AMD Ryzen 7            | 2         | 4.55%   |
| AMD Ryzen 5            | 2         | 4.55%   |
| AMD A6                 | 2         | 4.55%   |
| Intel Core i3          | 1         | 2.27%   |
| Intel Core 2 Quad      | 1         | 2.27%   |
| Intel Core 2 Duo       | 1         | 2.27%   |
| Intel Celeron          | 1         | 2.27%   |
| AMD Ryzen Threadripper | 1         | 2.27%   |
| AMD FX                 | 1         | 2.27%   |
| AMD Athlon 64          | 1         | 2.27%   |
| AMD A10                | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 40.91%  |
| 4      | 15        | 34.09%  |
| 1      | 4         | 9.09%   |
| 8      | 2         | 4.55%   |
| 6      | 2         | 4.55%   |
| 14     | 1         | 2.27%   |
| 12     | 1         | 2.27%   |
| 3      | 1         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 72.73%  |
| 1      | 12        | 27.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 11.36%  |
| 0x306d4    | 4         | 9.09%   |
| 0x806c1    | 3         | 6.82%   |
| 0x206a7    | 3         | 6.82%   |
| Unknown    | 3         | 6.82%   |
| 0x506e3    | 2         | 4.55%   |
| 0xa0652    | 1         | 2.27%   |
| 0x906ea    | 1         | 2.27%   |
| 0x906e9    | 1         | 2.27%   |
| 0x906a3    | 1         | 2.27%   |
| 0x806e9    | 1         | 2.27%   |
| 0x706e5    | 1         | 2.27%   |
| 0x6fb      | 1         | 2.27%   |
| 0x406e3    | 1         | 2.27%   |
| 0x40651    | 1         | 2.27%   |
| 0x306e4    | 1         | 2.27%   |
| 0x306c3    | 1         | 2.27%   |
| 0x20655    | 1         | 2.27%   |
| 0x106a5    | 1         | 2.27%   |
| 0x1067a    | 1         | 2.27%   |
| 0x0a20120a | 1         | 2.27%   |
| 0x08701021 | 1         | 2.27%   |
| 0x08600106 | 1         | 2.27%   |
| 0x0800820b | 1         | 2.27%   |
| 0x08001137 | 1         | 2.27%   |
| 0x06006705 | 1         | 2.27%   |
| 0x0600111f | 1         | 2.27%   |
| 0x06001119 | 1         | 2.27%   |
| 0x06001116 | 1         | 2.27%   |
| 0x06000822 | 1         | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 6         | 13.64%  |
| Piledriver       | 4         | 9.09%   |
| Haswell          | 4         | 9.09%   |
| Broadwell        | 4         | 9.09%   |
| TigerLake        | 3         | 6.82%   |
| Skylake          | 3         | 6.82%   |
| SandyBridge      | 3         | 6.82%   |
| KabyLake         | 3         | 6.82%   |
| Zen 2            | 2         | 4.55%   |
| Zen+             | 1         | 2.27%   |
| Zen 3            | 1         | 2.27%   |
| Zen              | 1         | 2.27%   |
| Westmere         | 1         | 2.27%   |
| Penryn           | 1         | 2.27%   |
| Nehalem          | 1         | 2.27%   |
| K8 Hammer        | 1         | 2.27%   |
| IceLake          | 1         | 2.27%   |
| Excavator        | 1         | 2.27%   |
| Core             | 1         | 2.27%   |
| CometLake        | 1         | 2.27%   |
| Alderlake Hybrid | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 55.77%  |
| Nvidia | 12        | 23.08%  |
| AMD    | 11        | 21.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                        | 4         | 7.55%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 7.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 5.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 5.66%   |
| Intel HD Graphics 530                                                         | 2         | 3.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 3.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 3.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 3.77%   |
| Nvidia TU117M                                                                 | 1         | 1.89%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1         | 1.89%   |
| Nvidia MCP7A [GeForce 9400]                                                   | 1         | 1.89%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 1.89%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 1.89%   |
| Nvidia GK107M [GeForce GT 740M]                                               | 1         | 1.89%   |
| Nvidia GF119M [Quadro NVS 4200M]                                              | 1         | 1.89%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 1         | 1.89%   |
| Nvidia G94GL [Quadro FX 1800]                                                 | 1         | 1.89%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.89%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.89%   |
| Intel HD Graphics 630                                                         | 1         | 1.89%   |
| Intel HD Graphics 620                                                         | 1         | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.89%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 1.89%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                    | 1         | 1.89%   |
| AMD Trinity 2 [Radeon HD 7520G]                                               | 1         | 1.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.89%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 1         | 1.89%   |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 1.89%   |
| AMD Richland [Radeon HD 8450G]                                                | 1         | 1.89%   |
| AMD Renoir                                                                    | 1         | 1.89%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 45.45%  |
| 1 x AMD        | 8         | 18.18%  |
| 1 x Nvidia     | 6         | 13.64%  |
| Intel + Nvidia | 6         | 13.64%  |
| Intel + AMD    | 2         | 4.55%   |
| 2 x Intel      | 1         | 2.27%   |
| 2 x AMD        | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 93.18%  |
| Proprietary | 2         | 4.55%   |
| Unknown     | 1         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 54.55%  |
| 7.01-8.0   | 5         | 11.36%  |
| 0.51-1.0   | 5         | 11.36%  |
| 1.01-2.0   | 4         | 9.09%   |
| 0.01-0.5   | 4         | 9.09%   |
| 3.01-4.0   | 2         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 7         | 15.56%  |
| LG Display              | 5         | 11.11%  |
| Samsung Electronics     | 4         | 8.89%   |
| Dell                    | 4         | 8.89%   |
| AU Optronics            | 4         | 8.89%   |
| Acer                    | 4         | 8.89%   |
| BOE                     | 3         | 6.67%   |
| Sharp                   | 2         | 4.44%   |
| Chi Mei Optoelectronics | 2         | 4.44%   |
| Apple                   | 2         | 4.44%   |
| Vizio                   | 1         | 2.22%   |
| Philips                 | 1         | 2.22%   |
| PANDA                   | 1         | 2.22%   |
| Lenovo                  | 1         | 2.22%   |
| Iiyama                  | 1         | 2.22%   |
| Hewlett-Packard         | 1         | 2.22%   |
| Grundig                 | 1         | 2.22%   |
| Goldstar                | 1         | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 2         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 2         | 4.35%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                        | 1         | 2.17%   |
| Sharp LQ173M1JW08 SHP1544 1920x1080 382x215mm 17.3-inch                   | 1         | 2.17%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch                   | 1         | 2.17%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch        | 1         | 2.17%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch     | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch     | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch      | 1         | 2.17%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 1         | 2.17%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 1         | 2.17%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch               | 1         | 2.17%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 1         | 2.17%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                      | 1         | 2.17%   |
| Hewlett-Packard V221 HWP3111 1920x1080 477x268mm 21.5-inch                | 1         | 2.17%   |
| Grundig WUXGA GRU4448 1920x540                                            | 1         | 2.17%   |
| Goldstar E1960 GSM4BE5 1360x768 406x229mm 18.4-inch                       | 1         | 2.17%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                         | 1         | 2.17%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                       | 1         | 2.17%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                        | 1         | 2.17%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                         | 1         | 2.17%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 2.17%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE05FE 1366x768 309x173mm 13.9-inch                      | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO453D 1920x1080 309x174mm 14.0-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.17%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                    | 1         | 2.17%   |
| Apple Color LCD APP9CBC 1920x1080 475x267mm 21.5-inch                     | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 21        | 50%     |
| 1366x768 (WXGA)   | 10        | 23.81%  |
| 1600x900 (HD+)    | 3         | 7.14%   |
| 3840x2160 (4K)    | 2         | 4.76%   |
| 1440x900 (WXGA+)  | 2         | 4.76%   |
| 2560x1440 (QHD)   | 1         | 2.38%   |
| 1920x1200 (WUXGA) | 1         | 2.38%   |
| 1360x768          | 1         | 2.38%   |
| 1280x800 (WXGA)   | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 11        | 24.44%  |
| 14     | 6         | 13.33%  |
| 13     | 6         | 13.33%  |
| 21     | 4         | 8.89%   |
| 17     | 3         | 6.67%   |
| 31     | 2         | 4.44%   |
| 27     | 2         | 4.44%   |
| 23     | 2         | 4.44%   |
| 19     | 2         | 4.44%   |
| 18     | 2         | 4.44%   |
| 54     | 1         | 2.22%   |
| 26     | 1         | 2.22%   |
| 25     | 1         | 2.22%   |
| 24     | 1         | 2.22%   |
| 11     | 1         | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 46.67%  |
| 401-500     | 8         | 17.78%  |
| 501-600     | 7         | 15.56%  |
| 351-400     | 3         | 6.67%   |
| 201-300     | 3         | 6.67%   |
| 601-700     | 2         | 4.44%   |
| 1001-1500   | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 90.24%  |
| 16/10 | 4         | 9.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 24.44%  |
| 101-110        | 11        | 24.44%  |
| 201-250        | 5         | 11.11%  |
| 151-200        | 5         | 11.11%  |
| 121-130        | 3         | 6.67%   |
| 351-500        | 2         | 4.44%   |
| 301-350        | 2         | 4.44%   |
| 251-300        | 2         | 4.44%   |
| More than 1000 | 1         | 2.22%   |
| 71-80          | 1         | 2.22%   |
| 51-60          | 1         | 2.22%   |
| 141-150        | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 16        | 35.56%  |
| 101-120 | 15        | 33.33%  |
| 51-100  | 12        | 26.67%  |
| 1-50    | 1         | 2.22%   |
| 161-240 | 1         | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 81.82%  |
| 2     | 7         | 15.91%  |
| 0     | 1         | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 36.36%  |
| Realtek Semiconductor | 18        | 27.27%  |
| Qualcomm Atheros      | 11        | 16.67%  |
| TP-Link               | 4         | 6.06%   |
| Broadcom              | 3         | 4.55%   |
| Nvidia                | 2         | 3.03%   |
| Lenovo                | 2         | 3.03%   |
| Sierra Wireless       | 1         | 1.52%   |
| ASUSTek Computer      | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 13.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 6.1%    |
| Intel Wireless 7265                                               | 4         | 4.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 2.44%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.44%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.44%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                       | 1         | 1.22%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.22%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.22%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.22%   |
| Realtek 802.11ac NIC                                              | 1         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.22%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.22%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.22%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.22%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.22%   |
| Lenovo P2a42                                                      | 1         | 1.22%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.22%   |
| Intel Wireless 8260                                               | 1         | 1.22%   |
| Intel Wireless 7260                                               | 1         | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.22%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 45.95%  |
| Qualcomm Atheros      | 10        | 27.03%  |
| TP-Link               | 4         | 10.81%  |
| Realtek Semiconductor | 3         | 8.11%   |
| Broadcom              | 2         | 5.41%   |
| ASUSTek Computer      | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 4         | 10.81%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 8.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 5.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 5.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 5.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 5.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 5.41%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 5.41%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1         | 2.7%    |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 2.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 2.7%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.7%    |
| Realtek 802.11ac NIC                                           | 1         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                     | 1         | 2.7%    |
| Intel Wireless 8260                                            | 1         | 2.7%    |
| Intel Wireless 7260                                            | 1         | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 2.7%    |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.7%    |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 2.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.7%    |
| ASUS 802.11ac NIC                                              | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 38.64%  |
| Intel                 | 17        | 38.64%  |
| Qualcomm Atheros      | 3         | 6.82%   |
| Nvidia                | 2         | 4.55%   |
| Lenovo                | 2         | 4.55%   |
| Broadcom              | 2         | 4.55%   |
| Sierra Wireless       | 1         | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 24.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 11.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.67%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 4.44%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 2.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.22%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.22%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.22%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.22%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 2.22%   |
| Lenovo P2a42                                                      | 1         | 2.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 2.22%   |
| Intel 82575EB Gigabit Network Connection                          | 1         | 2.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.22%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 54.67%  |
| WiFi     | 34        | 45.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 53.19%  |
| WiFi     | 22        | 46.81%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 59.09%  |
| 1     | 16        | 36.36%  |
| 4     | 1         | 2.27%   |
| 0     | 1         | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 72.73%  |
| Yes  | 12        | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 46.15%  |
| Qualcomm Atheros Communications | 5         | 19.23%  |
| Broadcom                        | 4         | 15.38%  |
| Apple                           | 2         | 7.69%   |
| IMC Networks                    | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 23.08%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 11.54%  |
| Intel AX201 Bluetooth                               | 2         | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 7.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.85%   |
| Intel Bluetooth Device                              | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.85%   |
| Intel AX210 Bluetooth                               | 1         | 3.85%   |
| Intel AX200 Bluetooth                               | 1         | 3.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.85%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 3.85%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.85%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 52.46%  |
| AMD                 | 12        | 19.67%  |
| Nvidia              | 11        | 18.03%  |
| Roland              | 1         | 1.64%   |
| Plantronics         | 1         | 1.64%   |
| Logitech            | 1         | 1.64%   |
| Lenovo              | 1         | 1.64%   |
| C-Media Electronics | 1         | 1.64%   |
| ASUSTek Computer    | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 5.41%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 5.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.05%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 4.05%   |
| AMD FCH Azalia Controller                                                  | 3         | 4.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 2.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.7%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 2.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 2.7%    |
| Roland QUAD-CAPTURE                                                        | 1         | 1.35%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.35%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.35%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.35%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.35%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.35%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.35%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.35%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.35%   |
| C-Media Electronics CM108 Audio Controller                                 | 1         | 1.35%   |
| ASUSTek Computer Xonar SoundCard                                           | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 12        | 22.64%  |
| Samsung Electronics | 12        | 22.64%  |
| Kingston            | 6         | 11.32%  |
| Crucial             | 6         | 11.32%  |
| Micron Technology   | 4         | 7.55%   |
| Unknown             | 2         | 3.77%   |
| G.Skill             | 2         | 3.77%   |
| Corsair             | 2         | 3.77%   |
| A-DATA Technology   | 2         | 3.77%   |
| Ramaxel Technology  | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |
| Apacer              | 1         | 1.89%   |
| A Force             | 1         | 1.89%   |
| 8A020000802C        | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 3.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 3.45%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2         | 3.45%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 3.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.72%   |
| Unknown RAM Module 1GB DIMM 400MT/s                          | 1         | 1.72%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.72%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1         | 1.72%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s         | 1         | 1.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.72%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.72%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.72%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.72%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 1.72%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.72%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.72%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.72%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.72%   |
| Samsung RAM M471B5173BH0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.72%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.72%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM 1333MT/s               | 1         | 1.72%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Samsung RAM 456789ABCDEFGHIJKL 8GB SODIMM DDR3 1600MT/s      | 1         | 1.72%   |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.72%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.72%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.72%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s         | 1         | 1.72%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s         | 1         | 1.72%   |
| Kingston RAM ASU16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.72%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s        | 1         | 1.72%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s         | 1         | 1.72%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 53.49%  |
| DDR4    | 16        | 37.21%  |
| LPDDR4  | 2         | 4.65%   |
| DDR2    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 61.36%  |
| DIMM         | 13        | 29.55%  |
| Row Of Chips | 3         | 6.82%   |
| Chip         | 1         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 45.83%  |
| 4096  | 15        | 31.25%  |
| 16384 | 6         | 12.5%   |
| 2048  | 4         | 8.33%   |
| 1024  | 1         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 17        | 37.78%  |
| 3200  | 5         | 11.11%  |
| 2667  | 4         | 8.89%   |
| 1333  | 3         | 6.67%   |
| 4267  | 2         | 4.44%   |
| 3600  | 2         | 4.44%   |
| 2400  | 2         | 4.44%   |
| 2133  | 2         | 4.44%   |
| 49926 | 1         | 2.22%   |
| 3733  | 1         | 2.22%   |
| 2933  | 1         | 2.22%   |
| 1648  | 1         | 2.22%   |
| 1334  | 1         | 2.22%   |
| 1067  | 1         | 2.22%   |
| 800   | 1         | 2.22%   |
| 400   | 1         | 2.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Kyocera             | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 22.22%  |
| Realtek Semiconductor                  | 3         | 11.11%  |
| Sunplus Innovation Technology          | 2         | 7.41%   |
| Microdia                               | 2         | 7.41%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.41%   |
| Bison Electronics                      | 2         | 7.41%   |
| Apple                                  | 2         | 7.41%   |
| Acer                                   | 2         | 7.41%   |
| Suyin                                  | 1         | 3.7%    |
| Silicon Motion                         | 1         | 3.7%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.7%    |
| Quanta                                 | 1         | 3.7%    |
| Lite-On Technology                     | 1         | 3.7%    |
| IMC Networks                           | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 2         | 7.41%   |
| Chicony Integrated Camera                           | 2         | 7.41%   |
| Chicony HP HD Webcam                                | 2         | 7.41%   |
| Acer Integrated Camera                              | 2         | 7.41%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 3.7%    |
| Sunplus Integrated Webcam                           | 1         | 3.7%    |
| Sunplus Asus Webcam                                 | 1         | 3.7%    |
| Silicon Motion ATIV VGA Camera                      | 1         | 3.7%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 1         | 3.7%    |
| Realtek Integrated Camera                           | 1         | 3.7%    |
| Quanta HP TrueVision HD Camera                      | 1         | 3.7%    |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                       | 1         | 3.7%    |
| Lite-On HP HD Webcam                                | 1         | 3.7%    |
| IMC Networks Integrated Camera                      | 1         | 3.7%    |
| Chicony HP Truevision HD                            | 1         | 3.7%    |
| Chicony HP HD Camera                                | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 3.7%    |
| Bison Integrated Camera                             | 1         | 3.7%    |
| Bison HD Webcam                                     | 1         | 3.7%    |
| Apple FaceTime HD Camera                            | 1         | 3.7%    |
| Apple Built-in iSight                               | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 71.43%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 4         | 57.14%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device          | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader           | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 26        | 59.09%  |
| 1     | 15        | 34.09%  |
| 2     | 2         | 4.55%   |
| 3     | 1         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 7         | 38.89%  |
| Net/wireless       | 5         | 27.78%  |
| Chipcard           | 2         | 11.11%  |
| Unassigned class   | 1         | 5.56%   |
| Graphics card      | 1         | 5.56%   |
| Card reader        | 1         | 5.56%   |
| Camera             | 1         | 5.56%   |

