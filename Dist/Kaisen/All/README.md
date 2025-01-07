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

Total: 64

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Pegatron | Benicia                     | Desktop     | [a4f82b02e6](https://linux-hardware.org/?probe=a4f82b02e6) | Nov 07, 2024 |
| ASUSTek  | PRIME B450M-GAMING II       | Desktop     | [43ae0c9603](https://linux-hardware.org/?probe=43ae0c9603) | Sep 02, 2024 |
| Apple    | Mac-942B59F58194171B iMa... | All in one  | [b818b892c7](https://linux-hardware.org/?probe=b818b892c7) | Jun 07, 2024 |
| HP       | 89E9 0100                   | All in one  | [6167aae8bd](https://linux-hardware.org/?probe=6167aae8bd) | May 29, 2024 |
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

![OS](./images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Kaisen 1.8 | 12        | 22.22%  |
| Kaisen 2.2 | 9         | 16.67%  |
| Kaisen 2.1 | 9         | 16.67%  |
| Kaisen 2.3 | 8         | 14.81%  |
| Kaisen 2.0 | 6         | 11.11%  |
| Kaisen 1.7 | 3         | 5.56%   |
| Kaisen 1.6 | 3         | 5.56%   |
| Kaisen 1.4 | 3         | 5.56%   |
| Kaisen 1.0 | 1         | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Kaisen | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-kaisen5-amd64   | 12        | 22.22%  |
| 5.17.0-kaisen1-amd64   | 8         | 14.81%  |
| 5.15.0-kaisen1-amd64   | 7         | 12.96%  |
| 6.0.0-1kaisen-amd64    | 6         | 11.11%  |
| 6.1.0-1kaisen-amd64    | 5         | 9.26%   |
| 6.5.0-1kaisen-amd64    | 4         | 7.41%   |
| 5.10.0-kaisen3-amd64   | 3         | 5.56%   |
| 5.8.0-kaisen2-amd64    | 2         | 3.7%    |
| 6.8.9-1kaisen-amd64    | 1         | 1.85%   |
| 6.0.0-1kaisen-rt-amd64 | 1         | 1.85%   |
| 5.9.0-kaisen2-amd64    | 1         | 1.85%   |
| 5.5.0-kaisen1-amd64    | 1         | 1.85%   |
| 5.19.0-kaisen1-amd64   | 1         | 1.85%   |
| 5.16.0-kaisen1-amd64   | 1         | 1.85%   |
| 5.14.0-kaisen1-amd64   | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 27.78%  |
| 5.17.0  | 8         | 14.81%  |
| 6.0.0   | 7         | 12.96%  |
| 5.15.0  | 7         | 12.96%  |
| 6.1.0   | 5         | 9.26%   |
| 6.5.0   | 4         | 7.41%   |
| 5.8.0   | 2         | 3.7%    |
| 6.8.9   | 1         | 1.85%   |
| 5.9.0   | 1         | 1.85%   |
| 5.5.0   | 1         | 1.85%   |
| 5.19.0  | 1         | 1.85%   |
| 5.16.0  | 1         | 1.85%   |
| 5.14.0  | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 27.78%  |
| 5.17    | 8         | 14.81%  |
| 6.0     | 7         | 12.96%  |
| 5.15    | 7         | 12.96%  |
| 6.1     | 5         | 9.26%   |
| 6.5     | 4         | 7.41%   |
| 5.8     | 2         | 3.7%    |
| 6.8     | 1         | 1.85%   |
| 5.9     | 1         | 1.85%   |
| 5.5     | 1         | 1.85%   |
| 5.19    | 1         | 1.85%   |
| 5.16    | 1         | 1.85%   |
| 5.14    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 25        | 46.3%   |
| KDE5    | 16        | 29.63%  |
| XFCE    | 9         | 16.67%  |
| LXQt    | 2         | 3.7%    |
| LXDE    | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 52        | 96.3%   |
| Tty  | 2         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 39        | 72.22%  |
| TDM     | 12        | 22.22%  |
| SDDM    | 2         | 3.7%    |
| Unknown | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 27        | 50%     |
| fr_FR   | 11        | 20.37%  |
| pt_BR   | 3         | 5.56%   |
| de_DE   | 3         | 5.56%   |
| C       | 2         | 3.7%    |
| nl_NL   | 1         | 1.85%   |
| fr_BE   | 1         | 1.85%   |
| es_ES   | 1         | 1.85%   |
| en_ZA   | 1         | 1.85%   |
| en_IN   | 1         | 1.85%   |
| en_GB   | 1         | 1.85%   |
| de_CH   | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 66.67%  |
| BIOS | 18        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 30        | 55.56%  |
| Overlay | 19        | 35.19%  |
| Ext4    | 5         | 9.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 38        | 70.37%  |
| MBR     | 15        | 27.78%  |
| Unknown | 1         | 1.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 68.52%  |
| Yes       | 17        | 31.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 64.81%  |
| Yes       | 19        | 35.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 31.48%  |
| Lenovo              | 8         | 14.81%  |
| MSI                 | 7         | 12.96%  |
| Dell                | 6         | 11.11%  |
| Gigabyte Technology | 4         | 7.41%   |
| ASUSTek Computer    | 3         | 5.56%   |
| Apple               | 3         | 5.56%   |
| Samsung Electronics | 2         | 3.7%    |
| Pegatron            | 1         | 1.85%   |
| Intel               | 1         | 1.85%   |
| Foxconn             | 1         | 1.85%   |
| Acer                | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP EliteBook 840 G2                      | 2         | 3.7%    |
| Samsung 950QDB                           | 1         | 1.85%   |
| Samsung 370E4K                           | 1         | 1.85%   |
| Pegatron NP201AA-ABA a6814y              | 1         | 1.85%   |
| MSI Vector GP76 12UH                     | 1         | 1.85%   |
| MSI MS-7C91                              | 1         | 1.85%   |
| MSI MS-7C56                              | 1         | 1.85%   |
| MSI MS-7B09                              | 1         | 1.85%   |
| MSI MS-7817                              | 1         | 1.85%   |
| MSI MS-7816                              | 1         | 1.85%   |
| MSI Crosshair 15 A11UEK                  | 1         | 1.85%   |
| Lenovo ThinkPad T520 4243E51             | 1         | 1.85%   |
| Lenovo ThinkPad T450 20BV003SMS          | 1         | 1.85%   |
| Lenovo ThinkPad T431s 20AA000MUS         | 1         | 1.85%   |
| Lenovo ThinkPad T430 23427YU             | 1         | 1.85%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW    | 1         | 1.85%   |
| Lenovo ThinkPad L470 20J4CTO1WW          | 1         | 1.85%   |
| Lenovo Legion Y530-15ICH 81FV            | 1         | 1.85%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.85%   |
| Intel H61M-S2PV                          | 1         | 1.85%   |
| HP Z400 Workstation                      | 1         | 1.85%   |
| HP ProBook 650 G2                        | 1         | 1.85%   |
| HP ProBook 645 G1                        | 1         | 1.85%   |
| HP ProBook 640 G1                        | 1         | 1.85%   |
| HP Pavilion g7                           | 1         | 1.85%   |
| HP Pavilion All-in-One Desktop 27-ca1xxx | 1         | 1.85%   |
| HP Pavilion 15                           | 1         | 1.85%   |
| HP Notebook                              | 1         | 1.85%   |
| HP Laptop 15-bw0xx                       | 1         | 1.85%   |
| HP ENVY x360 Convertible 15m-dr0xxx      | 1         | 1.85%   |
| HP EliteDesk 800 G2 TWR                  | 1         | 1.85%   |
| HP EliteDesk 800 G1 DM                   | 1         | 1.85%   |
| HP EliteBook 840 G1                      | 1         | 1.85%   |
| HP Elite Slice                           | 1         | 1.85%   |
| HP Compaq Pro 6300 MT                    | 1         | 1.85%   |
| Gigabyte M61PM-S2                        | 1         | 1.85%   |
| Gigabyte GA-6PXSV1                       | 1         | 1.85%   |
| Gigabyte B550M AORUS ELITE               | 1         | 1.85%   |
| Gigabyte AX370-Gaming K5                 | 1         | 1.85%   |
| Foxconn s5-1204                          | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 11.11%  |
| HP ProBook            | 3         | 5.56%   |
| HP Pavilion           | 3         | 5.56%   |
| HP EliteBook          | 3         | 5.56%   |
| HP EliteDesk          | 2         | 3.7%    |
| Dell Inspiron         | 2         | 3.7%    |
| Samsung 950QDB        | 1         | 1.85%   |
| Samsung 370E4K        | 1         | 1.85%   |
| Pegatron NP201AA-ABA  | 1         | 1.85%   |
| MSI Vector            | 1         | 1.85%   |
| MSI MS-7C91           | 1         | 1.85%   |
| MSI MS-7C56           | 1         | 1.85%   |
| MSI MS-7B09           | 1         | 1.85%   |
| MSI MS-7817           | 1         | 1.85%   |
| MSI MS-7816           | 1         | 1.85%   |
| MSI Crosshair         | 1         | 1.85%   |
| Lenovo Legion         | 1         | 1.85%   |
| Lenovo IdeaPad        | 1         | 1.85%   |
| Intel H61M-S2PV       | 1         | 1.85%   |
| HP Z400               | 1         | 1.85%   |
| HP Notebook           | 1         | 1.85%   |
| HP Laptop             | 1         | 1.85%   |
| HP ENVY               | 1         | 1.85%   |
| HP Elite              | 1         | 1.85%   |
| HP Compaq             | 1         | 1.85%   |
| Gigabyte M61PM-S2     | 1         | 1.85%   |
| Gigabyte GA-6PXSV1    | 1         | 1.85%   |
| Gigabyte B550M        | 1         | 1.85%   |
| Gigabyte AX370-Gaming | 1         | 1.85%   |
| Foxconn s5-1204       | 1         | 1.85%   |
| Dell XPS              | 1         | 1.85%   |
| Dell Studio           | 1         | 1.85%   |
| Dell Latitude         | 1         | 1.85%   |
| Dell G3               | 1         | 1.85%   |
| ASUS X751LAB          | 1         | 1.85%   |
| ASUS N76VB            | 1         | 1.85%   |
| ASUS 970              | 1         | 1.85%   |
| Apple MacBookPro9     | 1         | 1.85%   |
| Apple iMac12          | 1         | 1.85%   |
| Apple iMac10          | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 14.81%  |
| 2013 | 8         | 14.81%  |
| 2017 | 5         | 9.26%   |
| 2011 | 5         | 9.26%   |
| 2016 | 4         | 7.41%   |
| 2015 | 4         | 7.41%   |
| 2014 | 4         | 7.41%   |
| 2022 | 3         | 5.56%   |
| 2021 | 3         | 5.56%   |
| 2012 | 3         | 5.56%   |
| 2010 | 2         | 3.7%    |
| 2009 | 2         | 3.7%    |
| 2018 | 1         | 1.85%   |
| 2008 | 1         | 1.85%   |
| 2006 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 29        | 53.7%   |
| Desktop     | 18        | 33.33%  |
| Convertible | 3         | 5.56%   |
| All in one  | 3         | 5.56%   |
| Server      | 1         | 1.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 27.78%  |
| 16.01-24.0  | 15        | 27.78%  |
| 8.01-16.0   | 12        | 22.22%  |
| 3.01-4.0    | 4         | 7.41%   |
| 32.01-64.0  | 3         | 5.56%   |
| 64.01-256.0 | 3         | 5.56%   |
| 24.01-32.0  | 1         | 1.85%   |
| 1.01-2.0    | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 46.3%   |
| 2.01-3.0  | 10        | 18.52%  |
| 3.01-4.0  | 6         | 11.11%  |
| 4.01-8.0  | 5         | 9.26%   |
| 8.01-16.0 | 4         | 7.41%   |
| 0.51-1.0  | 4         | 7.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 50%     |
| 2      | 21        | 38.89%  |
| 4      | 3         | 5.56%   |
| 5      | 1         | 1.85%   |
| 3      | 1         | 1.85%   |
| 0      | 1         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 61.11%  |
| Yes       | 21        | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 92.59%  |
| No        | 4         | 7.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 77.78%  |
| No        | 12        | 22.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 59.26%  |
| No        | 22        | 40.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 19        | 35.19%  |
| France       | 12        | 22.22%  |
| Brazil       | 5         | 9.26%   |
| Spain        | 3         | 5.56%   |
| Germany      | 3         | 5.56%   |
| UK           | 2         | 3.7%    |
| India        | 2         | 3.7%    |
| Belgium      | 2         | 3.7%    |
| Switzerland  | 1         | 1.85%   |
| South Africa | 1         | 1.85%   |
| Slovakia     | 1         | 1.85%   |
| Netherlands  | 1         | 1.85%   |
| Mexico       | 1         | 1.85%   |
| Australia    | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toulouse               | 2         | 3.7%    |
| Paris                  | 2         | 3.7%    |
| Meulan-en-Yvelines     | 2         | 3.7%    |
| Westfield              | 1         | 1.85%   |
| Vitoria-Gasteiz        | 1         | 1.85%   |
| Villejuif              | 1         | 1.85%   |
| Valencia               | 1         | 1.85%   |
| Tresses                | 1         | 1.85%   |
| Starkville             | 1         | 1.85%   |
| Short Hills            | 1         | 1.85%   |
| Segovia                | 1         | 1.85%   |
| Sao Paulo              | 1         | 1.85%   |
| Santa Clara            | 1         | 1.85%   |
| Salt Lake City         | 1         | 1.85%   |
| Roesrath               | 1         | 1.85%   |
| Rio de Janeiro         | 1         | 1.85%   |
| Rieschweiler-Muehlbach | 1         | 1.85%   |
| Reno                   | 1         | 1.85%   |
| Prattville             | 1         | 1.85%   |
| Pinckney               | 1         | 1.85%   |
| Perth                  | 1         | 1.85%   |
| Nova Iguaçu           | 1         | 1.85%   |
| Nitra                  | 1         | 1.85%   |
| Nieuw-Vossemeer        | 1         | 1.85%   |
| Milwaukee              | 1         | 1.85%   |
| Middlesbrough          | 1         | 1.85%   |
| Miami                  | 1         | 1.85%   |
| Medway                 | 1         | 1.85%   |
| Mechanicsburg          | 1         | 1.85%   |
| Manchester             | 1         | 1.85%   |
| Malappuram             | 1         | 1.85%   |
| Madrid                 | 1         | 1.85%   |
| Maceió                | 1         | 1.85%   |
| Liège                 | 1         | 1.85%   |
| Lawley                 | 1         | 1.85%   |
| Las Vegas              | 1         | 1.85%   |
| Lagorce                | 1         | 1.85%   |
| Joaima                 | 1         | 1.85%   |
| Issy-les-Moulineaux    | 1         | 1.85%   |
| Gavere                 | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 13        | 16     | 16.05%  |
| Seagate                     | 11        | 12     | 13.58%  |
| Samsung Electronics         | 11        | 15     | 13.58%  |
| Kingston                    | 6         | 6      | 7.41%   |
| Toshiba                     | 5         | 5      | 6.17%   |
| Intel                       | 4         | 5      | 4.94%   |
| SanDisk                     | 3         | 3      | 3.7%    |
| HGST                        | 3         | 3      | 3.7%    |
| Micron Technology           | 2         | 2      | 2.47%   |
| KIOXIA                      | 2         | 2      | 2.47%   |
| A-DATA Technology           | 2         | 2      | 2.47%   |
| Unknown                     | 2         | 2      | 2.47%   |
| Unknown                     | 1         | 1      | 1.23%   |
| TO Exter                    | 1         | 1      | 1.23%   |
| TCSUNBOW                    | 1         | 1      | 1.23%   |
| SK hynix                    | 1         | 1      | 1.23%   |
| Mushkin                     | 1         | 1      | 1.23%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.23%   |
| MARSHAL                     | 1         | 1      | 1.23%   |
| LITEONIT                    | 1         | 1      | 1.23%   |
| LITEON                      | 1         | 1      | 1.23%   |
| Lexar                       | 1         | 1      | 1.23%   |
| JMicron Technology          | 1         | 1      | 1.23%   |
| Hitachi                     | 1         | 1      | 1.23%   |
| Crucial                     | 1         | 1      | 1.23%   |
| Corsair                     | 1         | 1      | 1.23%   |
| China                       | 1         | 1      | 1.23%   |
| BHT                         | 1         | 1      | 1.23%   |
| ASMedia                     | 1         | 1      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD          | 2         | 2.27%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 2.27%   |
| Seagate ST500DM002-1BD142 500GB           | 2         | 2.27%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 2.27%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.27%   |
| HGST HTS541010A9E680 1TB                  | 2         | 2.27%   |
| Unknown                                   | 2         | 2.27%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.14%   |
| WDC WD800BB-55JKC0 80GB                   | 1         | 1.14%   |
| WDC WD6400AAKS-65A7B2 640GB               | 1         | 1.14%   |
| WDC WD5003ABYX-18WERA0 500GB              | 1         | 1.14%   |
| WDC WD5000AAKX-60U6AA0 500GB              | 1         | 1.14%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1         | 1.14%   |
| WDC WD3200BPVT-22ZEST0 320GB              | 1         | 1.14%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1.14%   |
| WDC WD20NPVZ-82WFZT0 2TB                  | 1         | 1.14%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.14%   |
| WDC WD10EZEX-75WN4A1 1TB                  | 1         | 1.14%   |
| WDC WD10EZEX-00BN5A0 1TB                  | 1         | 1.14%   |
| WDC WD Green 2.5 480GB SSD                | 1         | 1.14%   |
| Unknown SD  1GB                           | 1         | 1.14%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.14%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.14%   |
| Toshiba KXG6AZNV1T02 1TB                  | 1         | 1.14%   |
| Toshiba HDWD130 3TB                       | 1         | 1.14%   |
| Toshiba DT01ACA050 500GB                  | 1         | 1.14%   |
| TO Exter nal USB 3.0 1024GB               | 1         | 1.14%   |
| TCSUNBOW N4 120GB SSD                     | 1         | 1.14%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.14%   |
| Seagate ST8000DM004-2CX188 8TB            | 1         | 1.14%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1.14%   |
| Seagate ST31000528AS 1TB                  | 1         | 1.14%   |
| Seagate ST3000DM001-1ER166 3TB            | 1         | 1.14%   |
| Seagate ST2000DM008-2UB102 2TB            | 1         | 1.14%   |
| Seagate ST2000DM008-2FR102 2TB            | 1         | 1.14%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.14%   |
| SanDisk SSD PLUS 120 GB                   | 1         | 1.14%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD       | 1         | 1.14%   |
| SanDisk Portable SSD 2TB                  | 1         | 1.14%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 32.35%  |
| WDC                 | 10        | 12     | 29.41%  |
| Toshiba             | 4         | 4      | 11.76%  |
| HGST                | 3         | 3      | 8.82%   |
| TO Exter            | 1         | 1      | 2.94%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| MARSHAL             | 1         | 1      | 2.94%   |
| JMicron Technology  | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 21.88%  |
| Kingston            | 5         | 5      | 15.63%  |
| WDC                 | 4         | 4      | 12.5%   |
| SanDisk             | 3         | 3      | 9.38%   |
| A-DATA Technology   | 2         | 2      | 6.25%   |
| TCSUNBOW            | 1         | 1      | 3.13%   |
| Mushkin             | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 1      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |
| Lexar               | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| BHT                 | 1         | 1      | 3.13%   |
| ASMedia             | 1         | 1      | 3.13%   |
| Unknown             | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 37     | 41.1%   |
| SSD  | 26        | 32     | 35.62%  |
| NVMe | 16        | 20     | 21.92%  |
| MMC  | 1         | 1      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 63     | 66.18%  |
| NVMe | 16        | 20     | 23.53%  |
| SAS  | 6         | 6      | 8.82%   |
| MMC  | 1         | 1      | 1.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 46     | 61.4%   |
| 0.51-1.0   | 13        | 13     | 22.81%  |
| 1.01-2.0   | 5         | 6      | 8.77%   |
| 2.01-3.0   | 3         | 3      | 5.26%   |
| 4.01-10.0  | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 10        | 18.52%  |
| 101-250        | 9         | 16.67%  |
| 1-20           | 8         | 14.81%  |
| 501-1000       | 7         | 12.96%  |
| 1001-2000      | 5         | 9.26%   |
| 51-100         | 5         | 9.26%   |
| Unknown        | 5         | 9.26%   |
| 21-50          | 2         | 3.7%    |
| 2001-3000      | 2         | 3.7%    |
| More than 3000 | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 46.3%   |
| 21-50          | 7         | 12.96%  |
| 501-1000       | 5         | 9.26%   |
| Unknown        | 5         | 9.26%   |
| 101-250        | 4         | 7.41%   |
| 251-500        | 3         | 5.56%   |
| 51-100         | 3         | 5.56%   |
| More than 3000 | 1         | 1.85%   |
| 2001-3000      | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB   | 2         | 2      | 12.5%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1         | 1      | 6.25%   |
| WDC WD6400AAKS-65A7B2 640GB       | 1         | 1      | 6.25%   |
| WDC WD3200BPVT-22ZEST0 320GB      | 1         | 1      | 6.25%   |
| WDC WD20NPVZ-82WFZT0 2TB          | 1         | 1      | 6.25%   |
| WDC WD Green 2.5 480GB SSD        | 1         | 1      | 6.25%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 6.25%   |
| Seagate ST8000DM004-2CX188 8TB    | 1         | 1      | 6.25%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 6.25%   |
| Mushkin MKNSSDEC240GB             | 1         | 1      | 6.25%   |
| MARSHAL MAL2500SA-T54L 500GB      | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 6.25%   |
| A-DATA Technology SU635 240GB SSD | 1         | 1      | 6.25%   |
| Unknown                           | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 5         | 5      | 31.25%  |
| Seagate           | 4         | 4      | 25%     |
| Toshiba           | 1         | 1      | 6.25%   |
| Mushkin           | 1         | 1      | 6.25%   |
| MARSHAL           | 1         | 1      | 6.25%   |
| Hitachi           | 1         | 1      | 6.25%   |
| HGST              | 1         | 1      | 6.25%   |
| A-DATA Technology | 1         | 1      | 6.25%   |
| Unknown           | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 33.33%  |
| WDC     | 3         | 3      | 25%     |
| Toshiba | 1         | 1      | 8.33%   |
| MARSHAL | 1         | 1      | 8.33%   |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |
| Unknown | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 75%     |
| SSD  | 4         | 4      | 25%     |

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
| Works    | 40        | 65     | 62.5%   |
| Malfunc  | 15        | 16     | 23.44%  |
| Detected | 8         | 8      | 12.5%   |
| Failed   | 1         | 1      | 1.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 37        | 57.81%  |
| AMD                          | 11        | 17.19%  |
| Samsung Electronics          | 5         | 7.81%   |
| Nvidia                       | 2         | 3.13%   |
| Micron Technology            | 2         | 3.13%   |
| KIOXIA                       | 2         | 3.13%   |
| Toshiba America Info Systems | 1         | 1.56%   |
| SK hynix                     | 1         | 1.56%   |
| Phison Electronics           | 1         | 1.56%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.56%   |
| Kingston Technology Company  | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 10.81%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 6.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 4.05%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 4.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.7%    |
| Intel SATA Controller [RAID mode]                                              | 2         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.35%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.35%   |
| Phison E8 PCIe3 x2 NVMe Controller                                             | 1         | 1.35%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.35%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.35%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.35%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.35%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.35%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.35%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 1         | 1.35%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.35%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.35%   |
| Intel SSD 660P Series                                                          | 1         | 1.35%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.35%   |
| Intel C604/X79 series chipset 4-Port SATA/SAS Storage Control Unit             | 1         | 1.35%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.35%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.35%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.35%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 61.76%  |
| NVMe | 16        | 23.53%  |
| RAID | 6         | 8.82%   |
| IDE  | 3         | 4.41%   |
| SAS  | 1         | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 75.93%  |
| AMD    | 13        | 24.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-5200U CPU @ 2.20GHz              | 3         | 5.56%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 2         | 3.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz              | 2         | 3.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 2         | 3.7%    |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1         | 1.85%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz            | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1         | 1.85%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1         | 1.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 1         | 1.85%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 1.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 1.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 1.85%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 1         | 1.85%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1         | 1.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz              | 1         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 1.85%   |
| Intel Core i5-4210M CPU @ 2.60GHz              | 1         | 1.85%   |
| Intel Core i5-3437U CPU @ 1.90GHz              | 1         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 1.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 1.85%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 1.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz           | 1         | 1.85%   |
| Intel Celeron CPU U3600 @ 1.20GHz              | 1         | 1.85%   |
| Intel 12th Gen Core i7-12700T                  | 1         | 1.85%   |
| Intel 12th Gen Core i7-12700H                  | 1         | 1.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 1.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 1         | 1.85%   |
| AMD Ryzen Threadripper 2920X 12-Core Processor | 1         | 1.85%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 1.85%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 1         | 1.85%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 17        | 31.48%  |
| Intel Core i7           | 8         | 14.81%  |
| Other                   | 7         | 12.96%  |
| Intel Pentium           | 3         | 5.56%   |
| Intel Xeon              | 2         | 3.7%    |
| AMD Ryzen 7             | 2         | 3.7%    |
| AMD Ryzen 5             | 2         | 3.7%    |
| AMD A6                  | 2         | 3.7%    |
| Intel Pentium Dual-Core | 1         | 1.85%   |
| Intel Core i3           | 1         | 1.85%   |
| Intel Core 2 Quad       | 1         | 1.85%   |
| Intel Core 2 Duo        | 1         | 1.85%   |
| Intel Celeron           | 1         | 1.85%   |
| AMD Ryzen Threadripper  | 1         | 1.85%   |
| AMD Ryzen 9             | 1         | 1.85%   |
| AMD FX                  | 1         | 1.85%   |
| AMD E2                  | 1         | 1.85%   |
| AMD Athlon 64           | 1         | 1.85%   |
| AMD A10                 | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 40.74%  |
| 4      | 18        | 33.33%  |
| 1      | 4         | 7.41%   |
| 12     | 3         | 5.56%   |
| 8      | 3         | 5.56%   |
| 6      | 2         | 3.7%    |
| 14     | 1         | 1.85%   |
| 3      | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 70.37%  |
| 1      | 16        | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 14.81%  |
| 0x306a9    | 5         | 9.26%   |
| 0x306d4    | 4         | 7.41%   |
| 0x806c1    | 3         | 5.56%   |
| 0x206a7    | 3         | 5.56%   |
| 0x506e3    | 2         | 3.7%    |
| 0x306c3    | 2         | 3.7%    |
| 0xa0652    | 1         | 1.85%   |
| 0x906ea    | 1         | 1.85%   |
| 0x906e9    | 1         | 1.85%   |
| 0x906a3    | 1         | 1.85%   |
| 0x90672    | 1         | 1.85%   |
| 0x806e9    | 1         | 1.85%   |
| 0x706e5    | 1         | 1.85%   |
| 0x6fb      | 1         | 1.85%   |
| 0x406e3    | 1         | 1.85%   |
| 0x40651    | 1         | 1.85%   |
| 0x306e4    | 1         | 1.85%   |
| 0x20655    | 1         | 1.85%   |
| 0x106a5    | 1         | 1.85%   |
| 0x1067a    | 1         | 1.85%   |
| 0x10676    | 1         | 1.85%   |
| 0x0a20120a | 1         | 1.85%   |
| 0x0a201016 | 1         | 1.85%   |
| 0x08701021 | 1         | 1.85%   |
| 0x08600106 | 1         | 1.85%   |
| 0x0800820b | 1         | 1.85%   |
| 0x08001137 | 1         | 1.85%   |
| 0x07030106 | 1         | 1.85%   |
| 0x06006705 | 1         | 1.85%   |
| 0x0600111f | 1         | 1.85%   |
| 0x06001119 | 1         | 1.85%   |
| 0x06001116 | 1         | 1.85%   |
| 0x06000822 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 6         | 11.11%  |
| Haswell          | 6         | 11.11%  |
| Broadwell        | 5         | 9.26%   |
| SandyBridge      | 4         | 7.41%   |
| Piledriver       | 4         | 7.41%   |
| KabyLake         | 4         | 7.41%   |
| TigerLake        | 3         | 5.56%   |
| Skylake          | 3         | 5.56%   |
| Zen 3            | 2         | 3.7%    |
| Zen 2            | 2         | 3.7%    |
| Penryn           | 2         | 3.7%    |
| IceLake          | 2         | 3.7%    |
| Alderlake Hybrid | 2         | 3.7%    |
| Zen+             | 1         | 1.85%   |
| Zen              | 1         | 1.85%   |
| Westmere         | 1         | 1.85%   |
| Puma             | 1         | 1.85%   |
| Nehalem          | 1         | 1.85%   |
| K8 Hammer        | 1         | 1.85%   |
| Excavator        | 1         | 1.85%   |
| Core             | 1         | 1.85%   |
| CometLake        | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 56.25%  |
| Nvidia | 15        | 23.44%  |
| AMD    | 13        | 20.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                        | 5         | 7.69%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 6.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 6.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 4.62%   |
| Intel HD Graphics 530                                                         | 2         | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 3.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 3.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 3.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.54%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1         | 1.54%   |
| Nvidia MCP7A [GeForce 9400]                                                   | 1         | 1.54%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 1.54%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 1.54%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 1.54%   |
| Nvidia GK107M [GeForce GT 740M]                                               | 1         | 1.54%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1         | 1.54%   |
| Nvidia GF119M [Quadro NVS 4200M]                                              | 1         | 1.54%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.54%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 1         | 1.54%   |
| Nvidia G94GL [Quadro FX 1800]                                                 | 1         | 1.54%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.54%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.54%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.54%   |
| Intel HD Graphics 630                                                         | 1         | 1.54%   |
| Intel HD Graphics 620                                                         | 1         | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.54%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.54%   |
| Intel AlderLake-S GT1                                                         | 1         | 1.54%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 1         | 1.54%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 1         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 1.54%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                    | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 46.3%   |
| 1 x AMD        | 9         | 16.67%  |
| 1 x Nvidia     | 8         | 14.81%  |
| Intel + Nvidia | 7         | 12.96%  |
| Intel + AMD    | 3         | 5.56%   |
| 2 x Intel      | 1         | 1.85%   |
| 2 x AMD        | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 94.44%  |
| Proprietary | 2         | 3.7%    |
| Unknown     | 1         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 53.7%   |
| 0.51-1.0   | 7         | 12.96%  |
| 1.01-2.0   | 6         | 11.11%  |
| 7.01-8.0   | 5         | 9.26%   |
| 0.01-0.5   | 4         | 7.41%   |
| 3.01-4.0   | 2         | 3.7%    |
| 5.01-6.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 8         | 14.29%  |
| AU Optronics            | 7         | 12.5%   |
| LG Display              | 6         | 10.71%  |
| Samsung Electronics     | 4         | 7.14%   |
| Dell                    | 4         | 7.14%   |
| Acer                    | 4         | 7.14%   |
| Hewlett-Packard         | 3         | 5.36%   |
| BOE                     | 3         | 5.36%   |
| Apple                   | 3         | 5.36%   |
| Sharp                   | 2         | 3.57%   |
| Goldstar                | 2         | 3.57%   |
| Chi Mei Optoelectronics | 2         | 3.57%   |
| Vizio                   | 1         | 1.79%   |
| ViewSonic               | 1         | 1.79%   |
| Sceptre Tech            | 1         | 1.79%   |
| Philips                 | 1         | 1.79%   |
| PANDA                   | 1         | 1.79%   |
| Lenovo                  | 1         | 1.79%   |
| Iiyama                  | 1         | 1.79%   |
| Grundig                 | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch               | 2         | 3.51%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 2         | 3.51%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                        | 1         | 1.75%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 1.75%   |
| Sharp LQ173M1JW08 SHP1544 1920x1080 382x215mm 17.3-inch                   | 1         | 1.75%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch                   | 1         | 1.75%   |
| Sceptre Tech Sceptre H43 SPT1103 1920x1080 575x323mm 26.0-inch            | 1         | 1.75%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch        | 1         | 1.75%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch      | 1         | 1.75%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 1         | 1.75%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 1         | 1.75%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch               | 1         | 1.75%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 1         | 1.75%   |
| Iiyama PL2773H IVM660A 1920x1080 600x340mm 27.2-inch                      | 1         | 1.75%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch                | 1         | 1.75%   |
| Hewlett-Packard V221 HWP3111 1920x1080 477x268mm 21.5-inch                | 1         | 1.75%   |
| Hewlett-Packard Contino HPN404C 1920x1080 597x366mm 27.6-inch             | 1         | 1.75%   |
| Grundig WXGA GRU4448 1600x1200                                            | 1         | 1.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 1         | 1.75%   |
| Goldstar E1960 GSM4BE5 1360x768 406x229mm 18.4-inch                       | 1         | 1.75%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                         | 1         | 1.75%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                       | 1         | 1.75%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                        | 1         | 1.75%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                         | 1         | 1.75%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 1.75%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 27        | 50.94%  |
| 1366x768 (WXGA)   | 10        | 18.87%  |
| 1600x900 (HD+)    | 5         | 9.43%   |
| 3840x2160 (4K)    | 3         | 5.66%   |
| 2560x1440 (QHD)   | 2         | 3.77%   |
| 1440x900 (WXGA+)  | 2         | 3.77%   |
| 1920x1200 (WUXGA) | 1         | 1.89%   |
| 1360x768          | 1         | 1.89%   |
| 1280x800 (WXGA)   | 1         | 1.89%   |
| 1280x1024 (SXGA)  | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 13        | 23.21%  |
| 14     | 8         | 14.29%  |
| 13     | 6         | 10.71%  |
| 17     | 5         | 8.93%   |
| 27     | 4         | 7.14%   |
| 21     | 4         | 7.14%   |
| 31     | 3         | 5.36%   |
| 23     | 3         | 5.36%   |
| 26     | 2         | 3.57%   |
| 19     | 2         | 3.57%   |
| 18     | 2         | 3.57%   |
| 54     | 1         | 1.79%   |
| 25     | 1         | 1.79%   |
| 24     | 1         | 1.79%   |
| 11     | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 46.43%  |
| 501-600     | 11        | 19.64%  |
| 401-500     | 8         | 14.29%  |
| 351-400     | 4         | 7.14%   |
| 601-700     | 3         | 5.36%   |
| 201-300     | 3         | 5.36%   |
| 1001-1500   | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 88.46%  |
| 16/10 | 5         | 9.62%   |
| 5/4   | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 23.21%  |
| 101-110        | 13        | 23.21%  |
| 201-250        | 6         | 10.71%  |
| 151-200        | 5         | 8.93%   |
| 301-350        | 4         | 7.14%   |
| 121-130        | 4         | 7.14%   |
| 351-500        | 3         | 5.36%   |
| 251-300        | 3         | 5.36%   |
| 141-150        | 2         | 3.57%   |
| More than 1000 | 1         | 1.79%   |
| 71-80          | 1         | 1.79%   |
| 51-60          | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 20        | 35.71%  |
| 101-120 | 17        | 30.36%  |
| 51-100  | 17        | 30.36%  |
| 1-50    | 1         | 1.79%   |
| 161-240 | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 46        | 85.19%  |
| 2     | 7         | 12.96%  |
| 0     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 34.57%  |
| Realtek Semiconductor | 25        | 30.86%  |
| Qualcomm Atheros      | 13        | 16.05%  |
| TP-Link               | 4         | 4.94%   |
| Broadcom              | 4         | 4.94%   |
| Nvidia                | 2         | 2.47%   |
| Lenovo                | 2         | 2.47%   |
| Sierra Wireless       | 1         | 1.23%   |
| Gemtek                | 1         | 1.23%   |
| ASUSTek Computer      | 1         | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 16.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 5.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 4.04%   |
| Intel Wireless 7265                                                    | 4         | 4.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 3.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 2.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 2.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 2.02%   |
| Intel Wireless 7260                                                    | 2         | 2.02%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 2.02%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 2.02%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 2.02%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 2.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.02%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                            | 1         | 1.01%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 1.01%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                          | 1         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.01%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1         | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.01%   |
| Realtek 802.11ac NIC                                                   | 1         | 1.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1         | 1.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.01%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 1.01%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.01%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.01%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 1.01%   |
| Lenovo P2a42                                                           | 1         | 1.01%   |
| Intel Wireless 8265 / 8275                                             | 1         | 1.01%   |
| Intel Wireless 8260                                                    | 1         | 1.01%   |
| Intel Wireless 3165                                                    | 1         | 1.01%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 45.65%  |
| Qualcomm Atheros      | 12        | 26.09%  |
| TP-Link               | 4         | 8.7%    |
| Realtek Semiconductor | 4         | 8.7%    |
| Broadcom              | 2         | 4.35%   |
| Sierra Wireless       | 1         | 2.17%   |
| Gemtek                | 1         | 2.17%   |
| ASUSTek Computer      | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 4         | 8.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 6.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 6.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 4.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 4.35%   |
| Intel Wireless 7260                                            | 2         | 4.35%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.35%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1         | 2.17%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 2.17%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.17%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.17%   |
| Realtek 802.11ac NIC                                           | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 2.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.17%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.17%   |
| Intel Wireless 8260                                            | 1         | 2.17%   |
| Intel Wireless 3165                                            | 1         | 2.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 2.17%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.17%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 2.17%   |
| Gemtek WUBR-177G [Ralink RT2571W]                              | 1         | 2.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.17%   |
| ASUS 802.11ac NIC                                              | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 46.15%  |
| Intel                 | 18        | 34.62%  |
| Qualcomm Atheros      | 3         | 5.77%   |
| Broadcom              | 3         | 5.77%   |
| Nvidia                | 2         | 3.85%   |
| Lenovo                | 2         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 30.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 9.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 7.55%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 3.77%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 3.77%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 3.77%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 3.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 3.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.89%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 1.89%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.89%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.89%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 1.89%   |
| Lenovo P2a42                                                           | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.89%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.89%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.89%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.89%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 1.89%   |
| Intel 82575EB Gigabit Network Connection                               | 1         | 1.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 54.35%  |
| WiFi     | 42        | 45.65%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 50.88%  |
| WiFi     | 28        | 49.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 59.26%  |
| 1     | 20        | 37.04%  |
| 4     | 1         | 1.85%   |
| 0     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 38        | 70.37%  |
| Yes  | 16        | 29.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 50%     |
| Qualcomm Atheros Communications | 5         | 15.63%  |
| Broadcom                        | 4         | 12.5%   |
| Apple                           | 3         | 9.38%   |
| Realtek Semiconductor           | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |
| Cambridge Silicon Radio         | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 25%     |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 9.38%   |
| Intel AX201 Bluetooth                               | 3         | 9.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 6.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 6.25%   |
| Realtek Bluetooth Radio                             | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.13%   |
| Intel AX211 Bluetooth                               | 1         | 3.13%   |
| Intel AX210 Bluetooth                               | 1         | 3.13%   |
| Intel AX200 Bluetooth                               | 1         | 3.13%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.13%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.13%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 3.13%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.13%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 40        | 54.05%  |
| Nvidia              | 14        | 18.92%  |
| AMD                 | 14        | 18.92%  |
| Roland              | 1         | 1.35%   |
| Plantronics         | 1         | 1.35%   |
| Logitech            | 1         | 1.35%   |
| Lenovo              | 1         | 1.35%   |
| C-Media Electronics | 1         | 1.35%   |
| ASUSTek Computer    | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP High Definition Audio Controller                      | 5         | 5.56%   |
| Intel Broadwell-U Audio Controller                                           | 5         | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller          | 5         | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller          | 4         | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller   | 4         | 4.44%   |
| AMD FCH Azalia Controller                                                    | 4         | 4.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                  | 3         | 3.33%   |
| AMD Trinity HDMI Audio Controller                                            | 3         | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                              | 2         | 2.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                        | 2         | 2.22%   |
| Nvidia GK107 HDMI Audio Controller                                           | 2         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller             | 2         | 2.22%   |
| Intel Sunrise Point-LP HD Audio                                              | 2         | 2.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                             | 2         | 2.22%   |
| Intel 8 Series HD Audio Controller                                           | 2         | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller              | 2         | 2.22%   |
| AMD Starship/Matisse HD Audio Controller                                     | 2         | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                          | 2         | 2.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                   | 2         | 2.22%   |
| Roland QUAD-CAPTURE                                                          | 1         | 1.11%   |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter) | 1         | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller               | 1         | 1.11%   |
| Nvidia TU106 High Definition Audio Controller                                | 1         | 1.11%   |
| Nvidia MCP79 High Definition Audio                                           | 1         | 1.11%   |
| Nvidia MCP61 High Definition Audio                                           | 1         | 1.11%   |
| Nvidia GP108 High Definition Audio Controller                                | 1         | 1.11%   |
| Nvidia GF119 HDMI Audio Controller                                           | 1         | 1.11%   |
| Nvidia GA106 High Definition Audio Controller                                | 1         | 1.11%   |
| Nvidia GA104 High Definition Audio Controller                                | 1         | 1.11%   |
| Logitech [G533 Wireless Headset Dongle]                                      | 1         | 1.11%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                    | 1         | 1.11%   |
| Intel Tiger Lake-H HD Audio Controller                                       | 1         | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                    | 1         | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                        | 1         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                    | 1         | 1.11%   |
| Intel CM238 HD Audio Controller                                              | 1         | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                       | 1         | 1.11%   |
| Intel Cannon Lake PCH cAVS                                                   | 1         | 1.11%   |
| Intel C600/X79 series chipset High Definition Audio Controller               | 1         | 1.11%   |
| Intel Alder Lake-S HD Audio Controller                                       | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 15        | 23.08%  |
| Samsung Electronics | 15        | 23.08%  |
| Kingston            | 7         | 10.77%  |
| Crucial             | 7         | 10.77%  |
| Micron Technology   | 5         | 7.69%   |
| Corsair             | 3         | 4.62%   |
| Unknown             | 2         | 3.08%   |
| G.Skill             | 2         | 3.08%   |
| Elpida              | 2         | 3.08%   |
| A-DATA Technology   | 2         | 3.08%   |
| Team                | 1         | 1.54%   |
| Ramaxel Technology  | 1         | 1.54%   |
| Apacer              | 1         | 1.54%   |
| A Force             | 1         | 1.54%   |
| 8A020000802C        | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.78%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 2.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.78%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2         | 2.78%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 2.78%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.39%   |
| Unknown RAM Module 1GB DIMM 400MT/s                          | 1         | 1.39%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s         | 1         | 1.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.39%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 1         | 1.39%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1         | 1.39%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s       | 1         | 1.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.39%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 1.39%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1.39%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.39%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.39%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Samsung RAM M471B5173BH0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s          | 1         | 1.39%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s       | 1         | 1.39%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.39%   |
| Samsung RAM 456789ABCDEFGHIJKL 4GB SODIMM DDR3 1600MT/s      | 1         | 1.39%   |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.39%   |
| Micron RAM Module 4GB SODIMM DDR3 1333MT/s                   | 1         | 1.39%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.39%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s               | 1         | 1.39%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 51.85%  |
| DDR4    | 21        | 38.89%  |
| LPDDR4  | 2         | 3.7%    |
| DDR2    | 2         | 3.7%    |
| Unknown | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 61.82%  |
| DIMM         | 17        | 30.91%  |
| Row Of Chips | 3         | 5.45%   |
| Chip         | 1         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 41.67%  |
| 4096  | 18        | 30%     |
| 16384 | 9         | 15%     |
| 2048  | 5         | 8.33%   |
| 1024  | 2         | 3.33%   |
| 32768 | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 21        | 36.84%  |
| 3200  | 8         | 14.04%  |
| 2667  | 6         | 10.53%  |
| 1333  | 4         | 7.02%   |
| 4267  | 2         | 3.51%   |
| 3600  | 2         | 3.51%   |
| 2400  | 2         | 3.51%   |
| 2133  | 2         | 3.51%   |
| 800   | 2         | 3.51%   |
| 49926 | 1         | 1.75%   |
| 3933  | 1         | 1.75%   |
| 3800  | 1         | 1.75%   |
| 2933  | 1         | 1.75%   |
| 1648  | 1         | 1.75%   |
| 1334  | 1         | 1.75%   |
| 1067  | 1         | 1.75%   |
| 400   | 1         | 1.75%   |

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
| Chicony Electronics                    | 6         | 18.18%  |
| Bison Electronics                      | 5         | 15.15%  |
| Realtek Semiconductor                  | 4         | 12.12%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 9.09%   |
| Apple                                  | 3         | 9.09%   |
| Sunplus Innovation Technology          | 2         | 6.06%   |
| Quanta                                 | 2         | 6.06%   |
| Microdia                               | 2         | 6.06%   |
| Lite-On Technology                     | 2         | 6.06%   |
| Suyin                                  | 1         | 3.03%   |
| Silicon Motion                         | 1         | 3.03%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.03%   |
| IMC Networks                           | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                 | 3         | 9.09%   |
| Realtek Integrated_Webcam_HD                            | 2         | 6.06%   |
| Lite-On HP HD Webcam                                    | 2         | 6.06%   |
| Chicony Integrated Camera                               | 2         | 6.06%   |
| Chicony HP HD Webcam                                    | 2         | 6.06%   |
| Bison HD Webcam                                         | 2         | 6.06%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 3.03%   |
| Sunplus Integrated Webcam                               | 1         | 3.03%   |
| Sunplus Asus Webcam                                     | 1         | 3.03%   |
| Silicon Motion ATIV VGA Camera                          | 1         | 3.03%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 1         | 3.03%   |
| Realtek USB Camera                                      | 1         | 3.03%   |
| Realtek Integrated Camera                               | 1         | 3.03%   |
| Quanta HP TrueVision HD Camera                          | 1         | 3.03%   |
| Quanta HP 5MP Camera                                    | 1         | 3.03%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD                           | 1         | 3.03%   |
| IMC Networks Integrated Camera                          | 1         | 3.03%   |
| Chicony HP Truevision HD                                | 1         | 3.03%   |
| Chicony HP HD Camera                                    | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 3.03%   |
| Apple FaceTime HD Camera (Built-in)                     | 1         | 3.03%   |
| Apple FaceTime HD Camera                                | 1         | 3.03%   |
| Apple Built-in iSight                                   | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 66.67%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| Synaptics                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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
| 0     | 34        | 62.96%  |
| 1     | 17        | 31.48%  |
| 2     | 2         | 3.7%    |
| 3     | 1         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 9         | 42.86%  |
| Net/wireless       | 5         | 23.81%  |
| Graphics card      | 2         | 9.52%   |
| Chipcard           | 2         | 9.52%   |
| Unassigned class   | 1         | 4.76%   |
| Card reader        | 1         | 4.76%   |
| Camera             | 1         | 4.76%   |

