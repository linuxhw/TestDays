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

Total: 60

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI      | Crosshair 15 A11UEK         | Notebook    | [c99f9c7e61](https://linux-hardware.org/?probe=c99f9c7e61) | Apr 27, 2024 |
| HP       | ProBook 640 G1              | Notebook    | [75c9689f14](https://linux-hardware.org/?probe=75c9689f14) | Feb 26, 2024 |
| ASUSTek  | X751LAB                     | Notebook    | [f2f0720a64](https://linux-hardware.org/?probe=f2f0720a64) | Jan 18, 2024 |
| ASUSTek  | X751LAB                     | Notebook    | [035f9d17bd](https://linux-hardware.org/?probe=035f9d17bd) | Jan 12, 2024 |
| HP       | ENVY x360 Convertible 15... | Convertible | [48f3e5b7d8](https://linux-hardware.org/?probe=48f3e5b7d8) | Dec 05, 2023 |
| HP       | ENVY x360 Convertible 15... | Convertible | [0fca0314d6](https://linux-hardware.org/?probe=0fca0314d6) | Dec 05, 2023 |
| MSI      | H81M-E33                    | Desktop     | [471e20b9ee](https://linux-hardware.org/?probe=471e20b9ee) | Oct 11, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Kaisen 1.8 | 12        | 23.53%  |
| Kaisen 2.1 | 9         | 17.65%  |
| Kaisen 2.2 | 8         | 15.69%  |
| Kaisen 2.3 | 6         | 11.76%  |
| Kaisen 2.0 | 6         | 11.76%  |
| Kaisen 1.7 | 3         | 5.88%   |
| Kaisen 1.6 | 3         | 5.88%   |
| Kaisen 1.4 | 3         | 5.88%   |
| Kaisen 1.0 | 1         | 1.96%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Kaisen | 51        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-kaisen5-amd64   | 12        | 23.53%  |
| 5.17.0-kaisen1-amd64   | 8         | 15.69%  |
| 5.15.0-kaisen1-amd64   | 7         | 13.73%  |
| 6.0.0-1kaisen-amd64    | 5         | 9.8%    |
| 6.5.0-1kaisen-amd64    | 4         | 7.84%   |
| 6.1.0-1kaisen-amd64    | 4         | 7.84%   |
| 5.10.0-kaisen3-amd64   | 3         | 5.88%   |
| 5.8.0-kaisen2-amd64    | 2         | 3.92%   |
| 6.0.0-1kaisen-rt-amd64 | 1         | 1.96%   |
| 5.9.0-kaisen2-amd64    | 1         | 1.96%   |
| 5.5.0-kaisen1-amd64    | 1         | 1.96%   |
| 5.19.0-kaisen1-amd64   | 1         | 1.96%   |
| 5.16.0-kaisen1-amd64   | 1         | 1.96%   |
| 5.14.0-kaisen1-amd64   | 1         | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 29.41%  |
| 5.17.0  | 8         | 15.69%  |
| 5.15.0  | 7         | 13.73%  |
| 6.0.0   | 6         | 11.76%  |
| 6.5.0   | 4         | 7.84%   |
| 6.1.0   | 4         | 7.84%   |
| 5.8.0   | 2         | 3.92%   |
| 5.9.0   | 1         | 1.96%   |
| 5.5.0   | 1         | 1.96%   |
| 5.19.0  | 1         | 1.96%   |
| 5.16.0  | 1         | 1.96%   |
| 5.14.0  | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 29.41%  |
| 5.17    | 8         | 15.69%  |
| 5.15    | 7         | 13.73%  |
| 6.0     | 6         | 11.76%  |
| 6.5     | 4         | 7.84%   |
| 6.1     | 4         | 7.84%   |
| 5.8     | 2         | 3.92%   |
| 5.9     | 1         | 1.96%   |
| 5.5     | 1         | 1.96%   |
| 5.19    | 1         | 1.96%   |
| 5.16    | 1         | 1.96%   |
| 5.14    | 1         | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 24        | 47.06%  |
| KDE5    | 15        | 29.41%  |
| XFCE    | 8         | 15.69%  |
| LXQt    | 2         | 3.92%   |
| LXDE    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 50        | 98.04%  |
| Tty  | 1         | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 36        | 70.59%  |
| TDM     | 12        | 23.53%  |
| SDDM    | 2         | 3.92%   |
| Unknown | 1         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 25        | 49.02%  |
| fr_FR   | 11        | 21.57%  |
| pt_BR   | 3         | 5.88%   |
| de_DE   | 3         | 5.88%   |
| nl_NL   | 1         | 1.96%   |
| fr_BE   | 1         | 1.96%   |
| es_ES   | 1         | 1.96%   |
| en_ZA   | 1         | 1.96%   |
| en_IN   | 1         | 1.96%   |
| en_GB   | 1         | 1.96%   |
| de_CH   | 1         | 1.96%   |
| C       | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 66.67%  |
| BIOS | 17        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 29        | 56.86%  |
| Overlay | 17        | 33.33%  |
| Ext4    | 5         | 9.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 36        | 70.59%  |
| MBR     | 14        | 27.45%  |
| Unknown | 1         | 1.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 68.63%  |
| Yes       | 16        | 31.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 64.71%  |
| Yes       | 18        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 31.37%  |
| Lenovo              | 8         | 15.69%  |
| MSI                 | 7         | 13.73%  |
| Dell                | 6         | 11.76%  |
| Gigabyte Technology | 4         | 7.84%   |
| ASUSTek Computer    | 3         | 5.88%   |
| Samsung Electronics | 2         | 3.92%   |
| Apple               | 2         | 3.92%   |
| Intel               | 1         | 1.96%   |
| Foxconn             | 1         | 1.96%   |
| Acer                | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 840 G2                   | 2         | 3.92%   |
| Samsung 950QDB                        | 1         | 1.96%   |
| Samsung 370E4K                        | 1         | 1.96%   |
| MSI Vector GP76 12UH                  | 1         | 1.96%   |
| MSI MS-7C91                           | 1         | 1.96%   |
| MSI MS-7C56                           | 1         | 1.96%   |
| MSI MS-7B09                           | 1         | 1.96%   |
| MSI MS-7817                           | 1         | 1.96%   |
| MSI MS-7816                           | 1         | 1.96%   |
| MSI Crosshair 15 A11UEK               | 1         | 1.96%   |
| Lenovo ThinkPad T520 4243E51          | 1         | 1.96%   |
| Lenovo ThinkPad T450 20BV003SMS       | 1         | 1.96%   |
| Lenovo ThinkPad T431s 20AA000MUS      | 1         | 1.96%   |
| Lenovo ThinkPad T430 23427YU          | 1         | 1.96%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 1.96%   |
| Lenovo ThinkPad L470 20J4CTO1WW       | 1         | 1.96%   |
| Lenovo Legion Y530-15ICH 81FV         | 1         | 1.96%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 1.96%   |
| Intel H61M-S2PV                       | 1         | 1.96%   |
| HP Z400 Workstation                   | 1         | 1.96%   |
| HP ProBook 650 G2                     | 1         | 1.96%   |
| HP ProBook 645 G1                     | 1         | 1.96%   |
| HP ProBook 640 G1                     | 1         | 1.96%   |
| HP Pavilion g7                        | 1         | 1.96%   |
| HP Pavilion 15                        | 1         | 1.96%   |
| HP Notebook                           | 1         | 1.96%   |
| HP Laptop 15-bw0xx                    | 1         | 1.96%   |
| HP ENVY x360 Convertible 15m-dr0xxx   | 1         | 1.96%   |
| HP EliteDesk 800 G2 TWR               | 1         | 1.96%   |
| HP EliteDesk 800 G1 DM                | 1         | 1.96%   |
| HP EliteBook 840 G1                   | 1         | 1.96%   |
| HP Elite Slice                        | 1         | 1.96%   |
| HP Compaq Pro 6300 MT                 | 1         | 1.96%   |
| Gigabyte M61PM-S2                     | 1         | 1.96%   |
| Gigabyte GA-6PXSV1                    | 1         | 1.96%   |
| Gigabyte B550M AORUS ELITE            | 1         | 1.96%   |
| Gigabyte AX370-Gaming K5              | 1         | 1.96%   |
| Foxconn s5-1204                       | 1         | 1.96%   |
| Dell XPS 13 9310 2-in-1               | 1         | 1.96%   |
| Dell Studio 540                       | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 11.76%  |
| HP ProBook            | 3         | 5.88%   |
| HP EliteBook          | 3         | 5.88%   |
| HP Pavilion           | 2         | 3.92%   |
| HP EliteDesk          | 2         | 3.92%   |
| Dell Inspiron         | 2         | 3.92%   |
| Samsung 950QDB        | 1         | 1.96%   |
| Samsung 370E4K        | 1         | 1.96%   |
| MSI Vector            | 1         | 1.96%   |
| MSI MS-7C91           | 1         | 1.96%   |
| MSI MS-7C56           | 1         | 1.96%   |
| MSI MS-7B09           | 1         | 1.96%   |
| MSI MS-7817           | 1         | 1.96%   |
| MSI MS-7816           | 1         | 1.96%   |
| MSI Crosshair         | 1         | 1.96%   |
| Lenovo Legion         | 1         | 1.96%   |
| Lenovo IdeaPad        | 1         | 1.96%   |
| Intel H61M-S2PV       | 1         | 1.96%   |
| HP Z400               | 1         | 1.96%   |
| HP Notebook           | 1         | 1.96%   |
| HP Laptop             | 1         | 1.96%   |
| HP ENVY               | 1         | 1.96%   |
| HP Elite              | 1         | 1.96%   |
| HP Compaq             | 1         | 1.96%   |
| Gigabyte M61PM-S2     | 1         | 1.96%   |
| Gigabyte GA-6PXSV1    | 1         | 1.96%   |
| Gigabyte B550M        | 1         | 1.96%   |
| Gigabyte AX370-Gaming | 1         | 1.96%   |
| Foxconn s5-1204       | 1         | 1.96%   |
| Dell XPS              | 1         | 1.96%   |
| Dell Studio           | 1         | 1.96%   |
| Dell Latitude         | 1         | 1.96%   |
| Dell G3               | 1         | 1.96%   |
| ASUS X751LAB          | 1         | 1.96%   |
| ASUS N76VB            | 1         | 1.96%   |
| ASUS 970              | 1         | 1.96%   |
| Apple MacBookPro9     | 1         | 1.96%   |
| Apple iMac10          | 1         | 1.96%   |
| Acer Aspire           | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 15.69%  |
| 2013 | 8         | 15.69%  |
| 2017 | 5         | 9.8%    |
| 2016 | 4         | 7.84%   |
| 2015 | 4         | 7.84%   |
| 2014 | 4         | 7.84%   |
| 2011 | 4         | 7.84%   |
| 2021 | 3         | 5.88%   |
| 2012 | 3         | 5.88%   |
| 2022 | 2         | 3.92%   |
| 2010 | 2         | 3.92%   |
| 2018 | 1         | 1.96%   |
| 2009 | 1         | 1.96%   |
| 2008 | 1         | 1.96%   |
| 2006 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 29        | 56.86%  |
| Desktop     | 17        | 33.33%  |
| Convertible | 3         | 5.88%   |
| All in one  | 1         | 1.96%   |
| Server      | 1         | 1.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 51        | 100%    |

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


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 27.45%  |
| 16.01-24.0  | 13        | 25.49%  |
| 8.01-16.0   | 12        | 23.53%  |
| 3.01-4.0    | 4         | 7.84%   |
| 32.01-64.0  | 3         | 5.88%   |
| 64.01-256.0 | 3         | 5.88%   |
| 24.01-32.0  | 1         | 1.96%   |
| 1.01-2.0    | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 23        | 45.1%   |
| 2.01-3.0  | 10        | 19.61%  |
| 3.01-4.0  | 6         | 11.76%  |
| 4.01-8.0  | 5         | 9.8%    |
| 0.51-1.0  | 4         | 7.84%   |
| 8.01-16.0 | 3         | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 49.02%  |
| 2      | 20        | 39.22%  |
| 4      | 3         | 5.88%   |
| 5      | 1         | 1.96%   |
| 3      | 1         | 1.96%   |
| 0      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 60.78%  |
| Yes       | 20        | 39.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 92.16%  |
| No        | 4         | 7.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 76.47%  |
| No        | 12        | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 58.82%  |
| No        | 21        | 41.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 17        | 33.33%  |
| France       | 12        | 23.53%  |
| Brazil       | 4         | 7.84%   |
| Spain        | 3         | 5.88%   |
| Germany      | 3         | 5.88%   |
| UK           | 2         | 3.92%   |
| India        | 2         | 3.92%   |
| Belgium      | 2         | 3.92%   |
| Switzerland  | 1         | 1.96%   |
| South Africa | 1         | 1.96%   |
| Slovakia     | 1         | 1.96%   |
| Netherlands  | 1         | 1.96%   |
| Mexico       | 1         | 1.96%   |
| Australia    | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toulouse               | 2         | 3.92%   |
| Paris                  | 2         | 3.92%   |
| Meulan-en-Yvelines     | 2         | 3.92%   |
| Vitoria-Gasteiz        | 1         | 1.96%   |
| Villejuif              | 1         | 1.96%   |
| Valencia               | 1         | 1.96%   |
| Tresses                | 1         | 1.96%   |
| Starkville             | 1         | 1.96%   |
| Short Hills            | 1         | 1.96%   |
| Segovia                | 1         | 1.96%   |
| Sao Paulo              | 1         | 1.96%   |
| Santa Clara            | 1         | 1.96%   |
| Salt Lake City         | 1         | 1.96%   |
| Roesrath               | 1         | 1.96%   |
| Rio de Janeiro         | 1         | 1.96%   |
| Rieschweiler-Muehlbach | 1         | 1.96%   |
| Reno                   | 1         | 1.96%   |
| Prattville             | 1         | 1.96%   |
| Pinckney               | 1         | 1.96%   |
| Perth                  | 1         | 1.96%   |
| Nitra                  | 1         | 1.96%   |
| Nieuw-Vossemeer        | 1         | 1.96%   |
| Milwaukee              | 1         | 1.96%   |
| Middlesbrough          | 1         | 1.96%   |
| Miami                  | 1         | 1.96%   |
| Medway                 | 1         | 1.96%   |
| Mechanicsburg          | 1         | 1.96%   |
| Manchester             | 1         | 1.96%   |
| Malappuram             | 1         | 1.96%   |
| Madrid                 | 1         | 1.96%   |
| Maceió                | 1         | 1.96%   |
| Liège                 | 1         | 1.96%   |
| Lawley                 | 1         | 1.96%   |
| Las Vegas              | 1         | 1.96%   |
| Lagorce                | 1         | 1.96%   |
| Joaima                 | 1         | 1.96%   |
| Issy-les-Moulineaux    | 1         | 1.96%   |
| Gavere                 | 1         | 1.96%   |
| Friesoythe             | 1         | 1.96%   |
| Fort Lauderdale        | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 11        | 12     | 14.47%  |
| Samsung Electronics         | 11        | 15     | 14.47%  |
| Seagate                     | 10        | 11     | 13.16%  |
| Toshiba                     | 5         | 5      | 6.58%   |
| Kingston                    | 5         | 5      | 6.58%   |
| SanDisk                     | 3         | 3      | 3.95%   |
| Intel                       | 3         | 4      | 3.95%   |
| HGST                        | 3         | 3      | 3.95%   |
| Micron Technology           | 2         | 2      | 2.63%   |
| KIOXIA                      | 2         | 2      | 2.63%   |
| A-DATA Technology           | 2         | 2      | 2.63%   |
| Unknown                     | 2         | 2      | 2.63%   |
| Unknown                     | 1         | 1      | 1.32%   |
| TO Exter                    | 1         | 1      | 1.32%   |
| TCSUNBOW                    | 1         | 1      | 1.32%   |
| SK hynix                    | 1         | 1      | 1.32%   |
| Mushkin                     | 1         | 1      | 1.32%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.32%   |
| MARSHAL                     | 1         | 1      | 1.32%   |
| LITEONIT                    | 1         | 1      | 1.32%   |
| LITEON                      | 1         | 1      | 1.32%   |
| Lexar                       | 1         | 1      | 1.32%   |
| JMicron Technology          | 1         | 1      | 1.32%   |
| Hitachi                     | 1         | 1      | 1.32%   |
| Crucial                     | 1         | 1      | 1.32%   |
| Corsair                     | 1         | 1      | 1.32%   |
| China                       | 1         | 1      | 1.32%   |
| BHT                         | 1         | 1      | 1.32%   |
| ASMedia                     | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD          | 2         | 2.44%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 2.44%   |
| Seagate ST500DM002-1BD142 500GB           | 2         | 2.44%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 2.44%   |
| HGST HTS541010A9E680 1TB                  | 2         | 2.44%   |
| Unknown                                   | 2         | 2.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.22%   |
| WDC WD800BB-55JKC0 80GB                   | 1         | 1.22%   |
| WDC WD5003ABYX-18WERA0 500GB              | 1         | 1.22%   |
| WDC WD5000AAKX-60U6AA0 500GB              | 1         | 1.22%   |
| WDC WD3200BPVT-22ZEST0 320GB              | 1         | 1.22%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1.22%   |
| WDC WD20NPVZ-82WFZT0 2TB                  | 1         | 1.22%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.22%   |
| WDC WD10EZEX-75WN4A1 1TB                  | 1         | 1.22%   |
| WDC WD Green 2.5 480GB SSD                | 1         | 1.22%   |
| Unknown SD  1GB                           | 1         | 1.22%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.22%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.22%   |
| Toshiba KXG6AZNV1T02 1TB                  | 1         | 1.22%   |
| Toshiba HDWD130 3TB                       | 1         | 1.22%   |
| Toshiba DT01ACA050 500GB                  | 1         | 1.22%   |
| TO Exter nal USB 3.0 500GB                | 1         | 1.22%   |
| TCSUNBOW N4 120GB SSD                     | 1         | 1.22%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.22%   |
| Seagate ST8000DM004-2CX188 8TB            | 1         | 1.22%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1.22%   |
| Seagate ST31000528AS 1TB                  | 1         | 1.22%   |
| Seagate ST2000DM008-2UB102 2TB            | 1         | 1.22%   |
| Seagate ST2000DM008-2FR102 2TB            | 1         | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.22%   |
| SanDisk SSD PLUS 120 GB                   | 1         | 1.22%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD       | 1         | 1.22%   |
| SanDisk Portable SSD 1TB                  | 1         | 1.22%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 1.22%   |
| Samsung SSD 970 EVO Plus 500GB            | 1         | 1.22%   |
| Samsung SSD 970 EVO Plus 2TB              | 1         | 1.22%   |
| Samsung SSD 960 EVO 250GB                 | 1         | 1.22%   |
| Samsung SSD 860 QVO 1TB                   | 1         | 1.22%   |
| Samsung SSD 860 EVO 250GB                 | 1         | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 32.26%  |
| WDC                 | 8         | 8      | 25.81%  |
| Toshiba             | 4         | 4      | 12.9%   |
| HGST                | 3         | 3      | 9.68%   |
| TO Exter            | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| MARSHAL             | 1         | 1      | 3.23%   |
| JMicron Technology  | 1         | 1      | 3.23%   |
| Hitachi             | 1         | 1      | 3.23%   |
| Unknown             | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 22.58%  |
| WDC                 | 4         | 4      | 12.9%   |
| Kingston            | 4         | 4      | 12.9%   |
| SanDisk             | 3         | 3      | 9.68%   |
| A-DATA Technology   | 2         | 2      | 6.45%   |
| TCSUNBOW            | 1         | 1      | 3.23%   |
| Mushkin             | 1         | 1      | 3.23%   |
| LITEONIT            | 1         | 1      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| Lexar               | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| Crucial             | 1         | 1      | 3.23%   |
| China               | 1         | 1      | 3.23%   |
| BHT                 | 1         | 1      | 3.23%   |
| ASMedia             | 1         | 1      | 3.23%   |
| Unknown             | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 32     | 39.71%  |
| SSD  | 25        | 31     | 36.76%  |
| NVMe | 15        | 19     | 22.06%  |
| MMC  | 1         | 1      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 57     | 65.63%  |
| NVMe | 15        | 19     | 23.44%  |
| SAS  | 6         | 6      | 9.38%   |
| MMC  | 1         | 1      | 1.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 43     | 62.75%  |
| 0.51-1.0   | 12        | 12     | 23.53%  |
| 1.01-2.0   | 3         | 4      | 5.88%   |
| 2.01-3.0   | 2         | 2      | 3.92%   |
| 10.01-20.0 | 1         | 1      | 1.96%   |
| 4.01-10.0  | 1         | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 10        | 19.61%  |
| 101-250        | 9         | 17.65%  |
| 1-20           | 8         | 15.69%  |
| 501-1000       | 6         | 11.76%  |
| 1001-2000      | 5         | 9.8%    |
| Unknown        | 5         | 9.8%    |
| 51-100         | 4         | 7.84%   |
| 21-50          | 2         | 3.92%   |
| More than 3000 | 1         | 1.96%   |
| 2001-3000      | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 49.02%  |
| 21-50          | 7         | 13.73%  |
| 501-1000       | 5         | 9.8%    |
| Unknown        | 5         | 9.8%    |
| 101-250        | 4         | 7.84%   |
| 251-500        | 2         | 3.92%   |
| 51-100         | 2         | 3.92%   |
| More than 3000 | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB   | 2         | 2      | 13.33%  |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-22ZEST0 320GB      | 1         | 1      | 6.67%   |
| WDC WD20NPVZ-82WFZT0 2TB          | 1         | 1      | 6.67%   |
| WDC WD Green 2.5 480GB SSD        | 1         | 1      | 6.67%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 6.67%   |
| Seagate ST8000DM004-2CX188 8TB    | 1         | 1      | 6.67%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 6.67%   |
| Mushkin MKNSSDEC240GB             | 1         | 1      | 6.67%   |
| MARSHAL MAL2500SA-T54L 500GB      | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 6.67%   |
| A-DATA Technology SU635 240GB SSD | 1         | 1      | 6.67%   |
| Unknown                           | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 4      | 26.67%  |
| Seagate           | 4         | 4      | 26.67%  |
| Toshiba           | 1         | 1      | 6.67%   |
| Mushkin           | 1         | 1      | 6.67%   |
| MARSHAL           | 1         | 1      | 6.67%   |
| Hitachi           | 1         | 1      | 6.67%   |
| HGST              | 1         | 1      | 6.67%   |
| A-DATA Technology | 1         | 1      | 6.67%   |
| Unknown           | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 36.36%  |
| WDC     | 2         | 2      | 18.18%  |
| Toshiba | 1         | 1      | 9.09%   |
| MARSHAL | 1         | 1      | 9.09%   |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |
| Unknown | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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
| Works    | 37        | 59     | 61.67%  |
| Malfunc  | 14        | 15     | 23.33%  |
| Detected | 8         | 8      | 13.33%  |
| Failed   | 1         | 1      | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 34        | 55.74%  |
| AMD                          | 11        | 18.03%  |
| Samsung Electronics          | 5         | 8.2%    |
| Nvidia                       | 2         | 3.28%   |
| Micron Technology            | 2         | 3.28%   |
| KIOXIA                       | 2         | 3.28%   |
| Toshiba America Info Systems | 1         | 1.64%   |
| SK hynix                     | 1         | 1.64%   |
| Phison Electronics           | 1         | 1.64%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.64%   |
| Kingston Technology Company  | 1         | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 11.59%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 7.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.35%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 4.35%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 2.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 2.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.45%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.45%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.45%   |
| Phison E8 PCIe3 x2 NVMe Controller                                             | 1         | 1.45%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.45%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.45%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.45%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.45%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.45%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.45%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 1         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.45%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.45%   |
| Intel SSD 660P Series                                                          | 1         | 1.45%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.45%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.45%   |
| Intel C604/X79 series chipset 4-Port SATA/SAS Storage Control Unit             | 1         | 1.45%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.45%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.45%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 40        | 63.49%  |
| NVMe | 15        | 23.81%  |
| RAID | 4         | 6.35%   |
| IDE  | 3         | 4.76%   |
| SAS  | 1         | 1.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 74.51%  |
| AMD    | 13        | 25.49%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-5200U CPU @ 2.20GHz              | 3         | 5.88%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 2         | 3.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 2         | 3.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 3.92%   |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1         | 1.96%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz            | 1         | 1.96%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1         | 1.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 1.96%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 1.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 1.96%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 1.96%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 1.96%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1         | 1.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 1         | 1.96%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1         | 1.96%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1         | 1.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz              | 1         | 1.96%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 1.96%   |
| Intel Core i5-4210M CPU @ 2.60GHz              | 1         | 1.96%   |
| Intel Core i5-3437U CPU @ 1.90GHz              | 1         | 1.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 1.96%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 1.96%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 1.96%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1         | 1.96%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz           | 1         | 1.96%   |
| Intel Celeron CPU U3600 @ 1.20GHz              | 1         | 1.96%   |
| Intel 12th Gen Core i7-12700H                  | 1         | 1.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 1.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 1         | 1.96%   |
| AMD Ryzen Threadripper 2920X 12-Core Processor | 1         | 1.96%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 1.96%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 1         | 1.96%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1         | 1.96%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 1.96%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 1.96%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 16        | 31.37%  |
| Intel Core i7          | 8         | 15.69%  |
| Other                  | 6         | 11.76%  |
| Intel Pentium          | 3         | 5.88%   |
| Intel Xeon             | 2         | 3.92%   |
| AMD Ryzen 7            | 2         | 3.92%   |
| AMD Ryzen 5            | 2         | 3.92%   |
| AMD A6                 | 2         | 3.92%   |
| Intel Core i3          | 1         | 1.96%   |
| Intel Core 2 Quad      | 1         | 1.96%   |
| Intel Core 2 Duo       | 1         | 1.96%   |
| Intel Celeron          | 1         | 1.96%   |
| AMD Ryzen Threadripper | 1         | 1.96%   |
| AMD Ryzen 9            | 1         | 1.96%   |
| AMD FX                 | 1         | 1.96%   |
| AMD E2                 | 1         | 1.96%   |
| AMD Athlon 64          | 1         | 1.96%   |
| AMD A10                | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 41.18%  |
| 4      | 17        | 33.33%  |
| 1      | 4         | 7.84%   |
| 8      | 3         | 5.88%   |
| 12     | 2         | 3.92%   |
| 6      | 2         | 3.92%   |
| 14     | 1         | 1.96%   |
| 3      | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 72.55%  |
| 1      | 14        | 27.45%  |

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
| Unknown    | 7         | 13.73%  |
| 0x306a9    | 5         | 9.8%    |
| 0x306d4    | 4         | 7.84%   |
| 0x806c1    | 3         | 5.88%   |
| 0x206a7    | 3         | 5.88%   |
| 0x506e3    | 2         | 3.92%   |
| 0x306c3    | 2         | 3.92%   |
| 0xa0652    | 1         | 1.96%   |
| 0x906ea    | 1         | 1.96%   |
| 0x906e9    | 1         | 1.96%   |
| 0x906a3    | 1         | 1.96%   |
| 0x806e9    | 1         | 1.96%   |
| 0x706e5    | 1         | 1.96%   |
| 0x6fb      | 1         | 1.96%   |
| 0x406e3    | 1         | 1.96%   |
| 0x40651    | 1         | 1.96%   |
| 0x306e4    | 1         | 1.96%   |
| 0x20655    | 1         | 1.96%   |
| 0x106a5    | 1         | 1.96%   |
| 0x1067a    | 1         | 1.96%   |
| 0x0a20120a | 1         | 1.96%   |
| 0x0a201016 | 1         | 1.96%   |
| 0x08701021 | 1         | 1.96%   |
| 0x08600106 | 1         | 1.96%   |
| 0x0800820b | 1         | 1.96%   |
| 0x08001137 | 1         | 1.96%   |
| 0x07030106 | 1         | 1.96%   |
| 0x06006705 | 1         | 1.96%   |
| 0x0600111f | 1         | 1.96%   |
| 0x06001119 | 1         | 1.96%   |
| 0x06001116 | 1         | 1.96%   |
| 0x06000822 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 6         | 11.76%  |
| Haswell          | 6         | 11.76%  |
| Broadwell        | 5         | 9.8%    |
| Piledriver       | 4         | 7.84%   |
| KabyLake         | 4         | 7.84%   |
| TigerLake        | 3         | 5.88%   |
| Skylake          | 3         | 5.88%   |
| SandyBridge      | 3         | 5.88%   |
| Zen 3            | 2         | 3.92%   |
| Zen 2            | 2         | 3.92%   |
| IceLake          | 2         | 3.92%   |
| Zen+             | 1         | 1.96%   |
| Zen              | 1         | 1.96%   |
| Westmere         | 1         | 1.96%   |
| Puma             | 1         | 1.96%   |
| Penryn           | 1         | 1.96%   |
| Nehalem          | 1         | 1.96%   |
| K8 Hammer        | 1         | 1.96%   |
| Excavator        | 1         | 1.96%   |
| Core             | 1         | 1.96%   |
| CometLake        | 1         | 1.96%   |
| Alderlake Hybrid | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 55%     |
| Nvidia | 15        | 25%     |
| AMD    | 12        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                        | 5         | 8.2%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 6.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 4.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 4.92%   |
| Intel HD Graphics 530                                                         | 2         | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 3.28%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 3.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 3.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.64%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1         | 1.64%   |
| Nvidia MCP7A [GeForce 9400]                                                   | 1         | 1.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 1.64%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 1.64%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 1.64%   |
| Nvidia GK107M [GeForce GT 740M]                                               | 1         | 1.64%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1         | 1.64%   |
| Nvidia GF119M [Quadro NVS 4200M]                                              | 1         | 1.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.64%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 1         | 1.64%   |
| Nvidia G94GL [Quadro FX 1800]                                                 | 1         | 1.64%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.64%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.64%   |
| Intel HD Graphics 630                                                         | 1         | 1.64%   |
| Intel HD Graphics 620                                                         | 1         | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 1         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 1.64%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                    | 1         | 1.64%   |
| AMD Trinity 2 [Radeon HD 7520G]                                               | 1         | 1.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 45.1%   |
| 1 x AMD        | 9         | 17.65%  |
| 1 x Nvidia     | 8         | 15.69%  |
| Intel + Nvidia | 7         | 13.73%  |
| Intel + AMD    | 2         | 3.92%   |
| 2 x Intel      | 1         | 1.96%   |
| 2 x AMD        | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 48        | 94.12%  |
| Proprietary | 2         | 3.92%   |
| Unknown     | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 52.94%  |
| 1.01-2.0   | 6         | 11.76%  |
| 0.51-1.0   | 6         | 11.76%  |
| 7.01-8.0   | 5         | 9.8%    |
| 0.01-0.5   | 4         | 7.84%   |
| 3.01-4.0   | 2         | 3.92%   |
| 5.01-6.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 8         | 15.38%  |
| AU Optronics            | 7         | 13.46%  |
| LG Display              | 6         | 11.54%  |
| Samsung Electronics     | 4         | 7.69%   |
| Dell                    | 4         | 7.69%   |
| Acer                    | 4         | 7.69%   |
| BOE                     | 3         | 5.77%   |
| Sharp                   | 2         | 3.85%   |
| Hewlett-Packard         | 2         | 3.85%   |
| Chi Mei Optoelectronics | 2         | 3.85%   |
| Apple                   | 2         | 3.85%   |
| Vizio                   | 1         | 1.92%   |
| ViewSonic               | 1         | 1.92%   |
| Philips                 | 1         | 1.92%   |
| PANDA                   | 1         | 1.92%   |
| Lenovo                  | 1         | 1.92%   |
| Iiyama                  | 1         | 1.92%   |
| Grundig                 | 1         | 1.92%   |
| Goldstar                | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 2         | 3.77%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 2         | 3.77%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                        | 1         | 1.89%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 1.89%   |
| Sharp LQ173M1JW08 SHP1544 1920x1080 382x215mm 17.3-inch                   | 1         | 1.89%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch                   | 1         | 1.89%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch        | 1         | 1.89%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch      | 1         | 1.89%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 1         | 1.89%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 1         | 1.89%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch               | 1         | 1.89%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch               | 1         | 1.89%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 1         | 1.89%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                      | 1         | 1.89%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch                | 1         | 1.89%   |
| Hewlett-Packard V221 HWP3111 1920x1080 477x268mm 21.5-inch                | 1         | 1.89%   |
| Grundig WXGA GRU4448 1600x1200                                            | 1         | 1.89%   |
| Goldstar E1960 GSM4BE5 1360x768 406x229mm 18.4-inch                       | 1         | 1.89%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                         | 1         | 1.89%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                       | 1         | 1.89%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                        | 1         | 1.89%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                         | 1         | 1.89%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 1.89%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 1         | 1.89%   |
| BOE LCD Monitor BOE05FE 1366x768 309x173mm 13.9-inch                      | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 25        | 51.02%  |
| 1366x768 (WXGA)   | 10        | 20.41%  |
| 1600x900 (HD+)    | 5         | 10.2%   |
| 3840x2160 (4K)    | 2         | 4.08%   |
| 1440x900 (WXGA+)  | 2         | 4.08%   |
| 2560x1440 (QHD)   | 1         | 2.04%   |
| 1920x1200 (WUXGA) | 1         | 2.04%   |
| 1360x768          | 1         | 2.04%   |
| 1280x800 (WXGA)   | 1         | 2.04%   |
| 1280x1024 (SXGA)  | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 13        | 25%     |
| 14     | 8         | 15.38%  |
| 13     | 6         | 11.54%  |
| 17     | 5         | 9.62%   |
| 21     | 4         | 7.69%   |
| 23     | 3         | 5.77%   |
| 31     | 2         | 3.85%   |
| 27     | 2         | 3.85%   |
| 19     | 2         | 3.85%   |
| 18     | 2         | 3.85%   |
| 54     | 1         | 1.92%   |
| 26     | 1         | 1.92%   |
| 25     | 1         | 1.92%   |
| 24     | 1         | 1.92%   |
| 11     | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 50%     |
| 501-600     | 8         | 15.38%  |
| 401-500     | 8         | 15.38%  |
| 351-400     | 4         | 7.69%   |
| 201-300     | 3         | 5.77%   |
| 601-700     | 2         | 3.85%   |
| 1001-1500   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 89.58%  |
| 16/10 | 4         | 8.33%   |
| 5/4   | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 25%     |
| 101-110        | 13        | 25%     |
| 201-250        | 6         | 11.54%  |
| 151-200        | 5         | 9.62%   |
| 121-130        | 4         | 7.69%   |
| 351-500        | 2         | 3.85%   |
| 301-350        | 2         | 3.85%   |
| 251-300        | 2         | 3.85%   |
| 141-150        | 2         | 3.85%   |
| More than 1000 | 1         | 1.92%   |
| 71-80          | 1         | 1.92%   |
| 51-60          | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 20        | 38.46%  |
| 101-120 | 16        | 30.77%  |
| 51-100  | 14        | 26.92%  |
| 1-50    | 1         | 1.92%   |
| 161-240 | 1         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 84.31%  |
| 2     | 7         | 13.73%  |
| 0     | 1         | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 36.84%  |
| Realtek Semiconductor | 23        | 30.26%  |
| Qualcomm Atheros      | 12        | 15.79%  |
| TP-Link               | 4         | 5.26%   |
| Broadcom              | 3         | 3.95%   |
| Nvidia                | 2         | 2.63%   |
| Lenovo                | 2         | 2.63%   |
| Sierra Wireless       | 1         | 1.32%   |
| ASUSTek Computer      | 1         | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 15.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 5.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 4.3%    |
| Intel Wireless 7265                                                    | 4         | 4.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 3.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 2.15%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 2.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 2.15%   |
| Intel Wireless 7260                                                    | 2         | 2.15%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 2.15%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 2.15%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 2.15%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 2.15%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                            | 1         | 1.08%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 1.08%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                          | 1         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 1.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.08%   |
| Realtek 802.11ac NIC                                                   | 1         | 1.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.08%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 1.08%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.08%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.08%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 1.08%   |
| Lenovo P2a42                                                           | 1         | 1.08%   |
| Intel Wireless 8265 / 8275                                             | 1         | 1.08%   |
| Intel Wireless 8260                                                    | 1         | 1.08%   |
| Intel Wireless 3165                                                    | 1         | 1.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 1.08%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 48.84%  |
| Qualcomm Atheros      | 11        | 25.58%  |
| TP-Link               | 4         | 9.3%    |
| Realtek Semiconductor | 3         | 6.98%   |
| Broadcom              | 2         | 4.65%   |
| Sierra Wireless       | 1         | 2.33%   |
| ASUSTek Computer      | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 4         | 9.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 6.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 6.98%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 4.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 4.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 4.65%   |
| Intel Wireless 7260                                            | 2         | 4.65%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.65%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1         | 2.33%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 2.33%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 2.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 2.33%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.33%   |
| Realtek 802.11ac NIC                                           | 1         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.33%   |
| Intel Wireless 8260                                            | 1         | 2.33%   |
| Intel Wireless 3165                                            | 1         | 2.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.33%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 2.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.33%   |
| ASUS 802.11ac NIC                                              | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 44.9%   |
| Intel                 | 18        | 36.73%  |
| Qualcomm Atheros      | 3         | 6.12%   |
| Nvidia                | 2         | 4.08%   |
| Lenovo                | 2         | 4.08%   |
| Broadcom              | 2         | 4.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 28%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 8%      |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 4%      |
| Intel I211 Gigabit Network Connection                                  | 2         | 4%      |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 4%      |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 4%      |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 2%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 2%      |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 2%      |
| Nvidia MCP79 Ethernet                                                  | 1         | 2%      |
| Nvidia MCP61 Ethernet                                                  | 1         | 2%      |
| Lenovo USB-C Dock Ethernet                                             | 1         | 2%      |
| Lenovo P2a42                                                           | 1         | 2%      |
| Intel Ethernet Connection I219-V                                       | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                      | 1         | 2%      |
| Intel Ethernet Connection I217-V                                       | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                      | 1         | 2%      |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2%      |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 2%      |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 2%      |
| Intel 82575EB Gigabit Network Connection                               | 1         | 2%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 2%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 54.65%  |
| WiFi     | 39        | 45.35%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 51.85%  |
| WiFi     | 26        | 48.15%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 30        | 58.82%  |
| 1     | 19        | 37.25%  |
| 4     | 1         | 1.96%   |
| 0     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 70.59%  |
| Yes  | 15        | 29.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 53.33%  |
| Qualcomm Atheros Communications | 5         | 16.67%  |
| Broadcom                        | 4         | 13.33%  |
| Apple                           | 2         | 6.67%   |
| IMC Networks                    | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Cambridge Silicon Radio         | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 20%     |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 10%     |
| Intel AX201 Bluetooth                               | 3         | 10%     |
| Intel Bluetooth Device                              | 2         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 6.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.33%   |
| Intel AX211 Bluetooth                               | 1         | 3.33%   |
| Intel AX210 Bluetooth                               | 1         | 3.33%   |
| Intel AX200 Bluetooth                               | 1         | 3.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.33%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.33%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 3.33%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 37        | 52.86%  |
| Nvidia              | 14        | 20%     |
| AMD                 | 13        | 18.57%  |
| Roland              | 1         | 1.43%   |
| Plantronics         | 1         | 1.43%   |
| Logitech            | 1         | 1.43%   |
| Lenovo              | 1         | 1.43%   |
| C-Media Electronics | 1         | 1.43%   |
| ASUSTek Computer    | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP High Definition Audio Controller                      | 5         | 5.81%   |
| Intel Broadwell-U Audio Controller                                           | 5         | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller          | 5         | 5.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller          | 4         | 4.65%   |
| AMD FCH Azalia Controller                                                    | 4         | 4.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                  | 3         | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller   | 3         | 3.49%   |
| AMD Trinity HDMI Audio Controller                                            | 3         | 3.49%   |
| Nvidia GP107GL High Definition Audio Controller                              | 2         | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                        | 2         | 2.33%   |
| Nvidia GK107 HDMI Audio Controller                                           | 2         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller             | 2         | 2.33%   |
| Intel Sunrise Point-LP HD Audio                                              | 2         | 2.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                             | 2         | 2.33%   |
| Intel 8 Series HD Audio Controller                                           | 2         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller              | 2         | 2.33%   |
| AMD Starship/Matisse HD Audio Controller                                     | 2         | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                          | 2         | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                   | 2         | 2.33%   |
| Roland QUAD-CAPTURE                                                          | 1         | 1.16%   |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter) | 1         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller               | 1         | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                | 1         | 1.16%   |
| Nvidia MCP79 High Definition Audio                                           | 1         | 1.16%   |
| Nvidia MCP61 High Definition Audio                                           | 1         | 1.16%   |
| Nvidia GP108 High Definition Audio Controller                                | 1         | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                           | 1         | 1.16%   |
| Nvidia GA106 High Definition Audio Controller                                | 1         | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                                | 1         | 1.16%   |
| Logitech [G533 Wireless Headset Dongle]                                      | 1         | 1.16%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                    | 1         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                       | 1         | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                    | 1         | 1.16%   |
| Intel Haswell-ULT HD Audio Controller                                        | 1         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                    | 1         | 1.16%   |
| Intel CM238 HD Audio Controller                                              | 1         | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                       | 1         | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                   | 1         | 1.16%   |
| Intel C600/X79 series chipset High Definition Audio Controller               | 1         | 1.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                      | 1         | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 24.59%  |
| SK hynix            | 14        | 22.95%  |
| Kingston            | 7         | 11.48%  |
| Crucial             | 7         | 11.48%  |
| Micron Technology   | 4         | 6.56%   |
| Unknown             | 2         | 3.28%   |
| G.Skill             | 2         | 3.28%   |
| Corsair             | 2         | 3.28%   |
| A-DATA Technology   | 2         | 3.28%   |
| Team                | 1         | 1.64%   |
| Ramaxel Technology  | 1         | 1.64%   |
| Elpida              | 1         | 1.64%   |
| Apacer              | 1         | 1.64%   |
| A Force             | 1         | 1.64%   |
| 8A020000802C        | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s    | 2         | 2.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 2.99%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.99%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2         | 2.99%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 2.99%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.49%   |
| Unknown RAM Module 1GB DIMM 400MT/s                          | 1         | 1.49%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s         | 1         | 1.49%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.49%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1         | 1.49%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1         | 1.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.49%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 1.49%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1.49%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.49%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.49%   |
| Samsung RAM M471B5173BH0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.49%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s          | 1         | 1.49%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.49%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.49%   |
| Samsung RAM 456789ABCDEFGHIJKL 8GB SODIMM DDR3 1600MT/s      | 1         | 1.49%   |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.49%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 1         | 1.49%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.49%   |
| Micron RAM 16JTF51264AZ-1G4M1 4096MB DIMM DDR3 1333MT/s      | 1         | 1.49%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s         | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 27        | 54%     |
| DDR4    | 19        | 38%     |
| LPDDR4  | 2         | 4%      |
| DDR2    | 1         | 2%      |
| Unknown | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 62.75%  |
| DIMM         | 15        | 29.41%  |
| Row Of Chips | 3         | 5.88%   |
| Chip         | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 47.27%  |
| 4096  | 17        | 30.91%  |
| 16384 | 6         | 10.91%  |
| 2048  | 4         | 7.27%   |
| 32768 | 1         | 1.82%   |
| 1024  | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 21        | 40.38%  |
| 3200  | 6         | 11.54%  |
| 2667  | 5         | 9.62%   |
| 1333  | 3         | 5.77%   |
| 4267  | 2         | 3.85%   |
| 3600  | 2         | 3.85%   |
| 2400  | 2         | 3.85%   |
| 2133  | 2         | 3.85%   |
| 49926 | 1         | 1.92%   |
| 3933  | 1         | 1.92%   |
| 3733  | 1         | 1.92%   |
| 2933  | 1         | 1.92%   |
| 1648  | 1         | 1.92%   |
| 1334  | 1         | 1.92%   |
| 1067  | 1         | 1.92%   |
| 800   | 1         | 1.92%   |
| 400   | 1         | 1.92%   |

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
| Chicony Electronics                    | 6         | 19.35%  |
| Realtek Semiconductor                  | 4         | 12.9%   |
| Bison Electronics                      | 4         | 12.9%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 9.68%   |
| Sunplus Innovation Technology          | 2         | 6.45%   |
| Microdia                               | 2         | 6.45%   |
| Lite-On Technology                     | 2         | 6.45%   |
| Apple                                  | 2         | 6.45%   |
| Suyin                                  | 1         | 3.23%   |
| Silicon Motion                         | 1         | 3.23%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.23%   |
| Quanta                                 | 1         | 3.23%   |
| IMC Networks                           | 1         | 3.23%   |
| Acer                                   | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                            | 2         | 6.45%   |
| Lite-On HP HD Webcam                                    | 2         | 6.45%   |
| Chicony Integrated Camera                               | 2         | 6.45%   |
| Chicony HP HD Webcam                                    | 2         | 6.45%   |
| Bison Integrated Camera                                 | 2         | 6.45%   |
| Bison HD Webcam                                         | 2         | 6.45%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 3.23%   |
| Sunplus USB2.0 Camera                                   | 1         | 3.23%   |
| Sunplus Asus Webcam                                     | 1         | 3.23%   |
| Silicon Motion ATIV VGA Camera                          | 1         | 3.23%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 1         | 3.23%   |
| Realtek USB Camera                                      | 1         | 3.23%   |
| Realtek Integrated Camera                               | 1         | 3.23%   |
| Quanta HP TrueVision HD Camera                          | 1         | 3.23%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 3.23%   |
| Microdia Integrated_Webcam_HD                           | 1         | 3.23%   |
| IMC Networks Integrated Camera                          | 1         | 3.23%   |
| Chicony HP Truevision HD                                | 1         | 3.23%   |
| Chicony HP HD Camera                                    | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 3.23%   |
| Apple FaceTime HD Camera                                | 1         | 3.23%   |
| Apple Built-in iSight                                   | 1         | 3.23%   |
| Acer Integrated Camera                                  | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 66.67%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| Synaptics                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 5         | 55.56%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 11.11%  |
| Synaptics UWP WBDI                           | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device          | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader           | 1         | 11.11%  |

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
| 0     | 31        | 60.78%  |
| 1     | 17        | 33.33%  |
| 2     | 2         | 3.92%   |
| 3     | 1         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 9         | 45%     |
| Net/wireless       | 5         | 25%     |
| Chipcard           | 2         | 10%     |
| Unassigned class   | 1         | 5%      |
| Graphics card      | 1         | 5%      |
| Card reader        | 1         | 5%      |
| Camera             | 1         | 5%      |

