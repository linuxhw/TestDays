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

Total: 69

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI      | B460M PRO-VDH WIFI          | Desktop     | [5a29438f61](https://linux-hardware.org/?probe=5a29438f61) | Aug 21, 2025 |
| MSI      | B460M PRO-VDH WIFI          | Desktop     | [2ead43ee65](https://linux-hardware.org/?probe=2ead43ee65) | Aug 21, 2025 |
| HP       | Laptop 14-dq0xxx            | Notebook    | [cd8729c918](https://linux-hardware.org/?probe=cd8729c918) | Aug 21, 2025 |
| Intel    | S2600GZ G11481-352          | Server      | [2909ba8bfe](https://linux-hardware.org/?probe=2909ba8bfe) | Feb 18, 2025 |
| ASUSTek  | Z97-A                       | Desktop     | [1ba96d29e9](https://linux-hardware.org/?probe=1ba96d29e9) | Jan 14, 2025 |
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
| Kaisen 1.8 | 12        | 20.69%  |
| Kaisen 2.2 | 11        | 18.97%  |
| Kaisen 2.1 | 9         | 15.52%  |
| Kaisen 2.3 | 8         | 13.79%  |
| Kaisen 2.0 | 6         | 10.34%  |
| Kaisen 1.7 | 3         | 5.17%   |
| Kaisen 1.6 | 3         | 5.17%   |
| Kaisen 1.4 | 3         | 5.17%   |
| Kaisen 3.0 | 2         | 3.45%   |
| Kaisen 1.0 | 1         | 1.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Kaisen | 58        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-kaisen5-amd64   | 12        | 20.69%  |
| 5.17.0-kaisen1-amd64   | 8         | 13.79%  |
| 6.0.0-1kaisen-amd64    | 7         | 12.07%  |
| 5.15.0-kaisen1-amd64   | 7         | 12.07%  |
| 6.1.0-1kaisen-amd64    | 6         | 10.34%  |
| 6.5.0-1kaisen-amd64    | 4         | 6.9%    |
| 5.10.0-kaisen3-amd64   | 3         | 5.17%   |
| 6.12.9-1kaisen-amd64   | 2         | 3.45%   |
| 5.8.0-kaisen2-amd64    | 2         | 3.45%   |
| 6.8.9-1kaisen-amd64    | 1         | 1.72%   |
| 6.0.0-1kaisen-rt-amd64 | 1         | 1.72%   |
| 5.9.0-kaisen2-amd64    | 1         | 1.72%   |
| 5.5.0-kaisen1-amd64    | 1         | 1.72%   |
| 5.19.0-kaisen1-amd64   | 1         | 1.72%   |
| 5.16.0-kaisen1-amd64   | 1         | 1.72%   |
| 5.14.0-kaisen1-amd64   | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 25.86%  |
| 6.0.0   | 8         | 13.79%  |
| 5.17.0  | 8         | 13.79%  |
| 5.15.0  | 7         | 12.07%  |
| 6.1.0   | 6         | 10.34%  |
| 6.5.0   | 4         | 6.9%    |
| 6.12.9  | 2         | 3.45%   |
| 5.8.0   | 2         | 3.45%   |
| 6.8.9   | 1         | 1.72%   |
| 5.9.0   | 1         | 1.72%   |
| 5.5.0   | 1         | 1.72%   |
| 5.19.0  | 1         | 1.72%   |
| 5.16.0  | 1         | 1.72%   |
| 5.14.0  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 25.86%  |
| 6.0     | 8         | 13.79%  |
| 5.17    | 8         | 13.79%  |
| 5.15    | 7         | 12.07%  |
| 6.1     | 6         | 10.34%  |
| 6.5     | 4         | 6.9%    |
| 6.12    | 2         | 3.45%   |
| 5.8     | 2         | 3.45%   |
| 6.8     | 1         | 1.72%   |
| 5.9     | 1         | 1.72%   |
| 5.5     | 1         | 1.72%   |
| 5.19    | 1         | 1.72%   |
| 5.16    | 1         | 1.72%   |
| 5.14    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 27        | 46.55%  |
| KDE5    | 18        | 31.03%  |
| XFCE    | 9         | 15.52%  |
| LXQt    | 2         | 3.45%   |
| LXDE    | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 56        | 96.55%  |
| Tty  | 2         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 43        | 74.14%  |
| TDM     | 12        | 20.69%  |
| SDDM    | 2         | 3.45%   |
| Unknown | 1         | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 29        | 50%     |
| fr_FR   | 13        | 22.41%  |
| pt_BR   | 3         | 5.17%   |
| de_DE   | 3         | 5.17%   |
| C       | 2         | 3.45%   |
| nl_NL   | 1         | 1.72%   |
| fr_BE   | 1         | 1.72%   |
| es_ES   | 1         | 1.72%   |
| en_ZA   | 1         | 1.72%   |
| en_IN   | 1         | 1.72%   |
| en_GB   | 1         | 1.72%   |
| de_CH   | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 40        | 68.97%  |
| BIOS | 18        | 31.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 31        | 53.45%  |
| Overlay | 22        | 37.93%  |
| Ext4    | 5         | 8.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 42        | 72.41%  |
| MBR     | 15        | 25.86%  |
| Unknown | 1         | 1.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 68.97%  |
| Yes       | 18        | 31.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 65.52%  |
| Yes       | 20        | 34.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 31.03%  |
| MSI                 | 8         | 13.79%  |
| Lenovo              | 8         | 13.79%  |
| Dell                | 6         | 10.34%  |
| Gigabyte Technology | 4         | 6.9%    |
| ASUSTek Computer    | 4         | 6.9%    |
| Apple               | 3         | 5.17%   |
| Samsung Electronics | 2         | 3.45%   |
| Intel               | 2         | 3.45%   |
| Pegatron            | 1         | 1.72%   |
| Foxconn             | 1         | 1.72%   |
| Acer                | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP EliteBook 840 G2                      | 2         | 3.45%   |
| Samsung 950QDB                           | 1         | 1.72%   |
| Samsung 370E4K                           | 1         | 1.72%   |
| Pegatron NP201AA-ABA a6814y              | 1         | 1.72%   |
| MSI Vector GP76 12UH                     | 1         | 1.72%   |
| MSI MS-7C91                              | 1         | 1.72%   |
| MSI MS-7C83                              | 1         | 1.72%   |
| MSI MS-7C56                              | 1         | 1.72%   |
| MSI MS-7B09                              | 1         | 1.72%   |
| MSI MS-7817                              | 1         | 1.72%   |
| MSI MS-7816                              | 1         | 1.72%   |
| MSI Crosshair 15 A11UEK                  | 1         | 1.72%   |
| Lenovo ThinkPad T520 4243E51             | 1         | 1.72%   |
| Lenovo ThinkPad T450 20BV003SMS          | 1         | 1.72%   |
| Lenovo ThinkPad T431s 20AA000MUS         | 1         | 1.72%   |
| Lenovo ThinkPad T430 23427YU             | 1         | 1.72%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW    | 1         | 1.72%   |
| Lenovo ThinkPad L470 20J4CTO1WW          | 1         | 1.72%   |
| Lenovo Legion Y530-15ICH 81FV            | 1         | 1.72%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.72%   |
| Intel S2600GZ                            | 1         | 1.72%   |
| Intel H61M-S2PV                          | 1         | 1.72%   |
| HP Z400 Workstation                      | 1         | 1.72%   |
| HP ProBook 650 G2                        | 1         | 1.72%   |
| HP ProBook 645 G1                        | 1         | 1.72%   |
| HP ProBook 640 G1                        | 1         | 1.72%   |
| HP Pavilion g7                           | 1         | 1.72%   |
| HP Pavilion All-in-One Desktop 27-ca1xxx | 1         | 1.72%   |
| HP Pavilion 15                           | 1         | 1.72%   |
| HP Notebook                              | 1         | 1.72%   |
| HP Laptop 15-bw0xx                       | 1         | 1.72%   |
| HP Laptop 14-dq0xxx                      | 1         | 1.72%   |
| HP ENVY x360 Convertible 15m-dr0xxx      | 1         | 1.72%   |
| HP EliteDesk 800 G2 TWR                  | 1         | 1.72%   |
| HP EliteDesk 800 G1 DM                   | 1         | 1.72%   |
| HP EliteBook 840 G1                      | 1         | 1.72%   |
| HP Elite Slice                           | 1         | 1.72%   |
| HP Compaq Pro 6300 MT                    | 1         | 1.72%   |
| Gigabyte M61PM-S2                        | 1         | 1.72%   |
| Gigabyte GA-6PXSV1                       | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 10.34%  |
| HP ProBook            | 3         | 5.17%   |
| HP Pavilion           | 3         | 5.17%   |
| HP EliteBook          | 3         | 5.17%   |
| HP Laptop             | 2         | 3.45%   |
| HP EliteDesk          | 2         | 3.45%   |
| Dell Inspiron         | 2         | 3.45%   |
| Samsung 950QDB        | 1         | 1.72%   |
| Samsung 370E4K        | 1         | 1.72%   |
| Pegatron NP201AA-ABA  | 1         | 1.72%   |
| MSI Vector            | 1         | 1.72%   |
| MSI MS-7C91           | 1         | 1.72%   |
| MSI MS-7C83           | 1         | 1.72%   |
| MSI MS-7C56           | 1         | 1.72%   |
| MSI MS-7B09           | 1         | 1.72%   |
| MSI MS-7817           | 1         | 1.72%   |
| MSI MS-7816           | 1         | 1.72%   |
| MSI Crosshair         | 1         | 1.72%   |
| Lenovo Legion         | 1         | 1.72%   |
| Lenovo IdeaPad        | 1         | 1.72%   |
| Intel S2600GZ         | 1         | 1.72%   |
| Intel H61M-S2PV       | 1         | 1.72%   |
| HP Z400               | 1         | 1.72%   |
| HP Notebook           | 1         | 1.72%   |
| HP ENVY               | 1         | 1.72%   |
| HP Elite              | 1         | 1.72%   |
| HP Compaq             | 1         | 1.72%   |
| Gigabyte M61PM-S2     | 1         | 1.72%   |
| Gigabyte GA-6PXSV1    | 1         | 1.72%   |
| Gigabyte B550M        | 1         | 1.72%   |
| Gigabyte AX370-Gaming | 1         | 1.72%   |
| Foxconn s5-1204       | 1         | 1.72%   |
| Dell XPS              | 1         | 1.72%   |
| Dell Studio           | 1         | 1.72%   |
| Dell Latitude         | 1         | 1.72%   |
| Dell G3               | 1         | 1.72%   |
| ASUS X751LAB          | 1         | 1.72%   |
| ASUS N76VB            | 1         | 1.72%   |
| ASUS All              | 1         | 1.72%   |
| ASUS 970              | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 9         | 15.52%  |
| 2013 | 8         | 13.79%  |
| 2017 | 5         | 8.62%   |
| 2015 | 5         | 8.62%   |
| 2014 | 5         | 8.62%   |
| 2011 | 5         | 8.62%   |
| 2012 | 4         | 6.9%    |
| 2022 | 3         | 5.17%   |
| 2021 | 3         | 5.17%   |
| 2016 | 3         | 5.17%   |
| 2010 | 2         | 3.45%   |
| 2009 | 2         | 3.45%   |
| 2019 | 1         | 1.72%   |
| 2018 | 1         | 1.72%   |
| 2008 | 1         | 1.72%   |
| 2006 | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 30        | 51.72%  |
| Desktop     | 20        | 34.48%  |
| Convertible | 3         | 5.17%   |
| All in one  | 3         | 5.17%   |
| Server      | 2         | 3.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 58        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 17        | 29.31%  |
| 4.01-8.0    | 16        | 27.59%  |
| 8.01-16.0   | 12        | 20.69%  |
| 32.01-64.0  | 4         | 6.9%    |
| 3.01-4.0    | 4         | 6.9%    |
| 64.01-256.0 | 3         | 5.17%   |
| 24.01-32.0  | 1         | 1.72%   |
| 1.01-2.0    | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 28        | 48.28%  |
| 2.01-3.0  | 11        | 18.97%  |
| 3.01-4.0  | 6         | 10.34%  |
| 4.01-8.0  | 5         | 8.62%   |
| 8.01-16.0 | 4         | 6.9%    |
| 0.51-1.0  | 4         | 6.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 50%     |
| 2      | 22        | 37.93%  |
| 4      | 3         | 5.17%   |
| 15     | 1         | 1.72%   |
| 5      | 1         | 1.72%   |
| 3      | 1         | 1.72%   |
| 0      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 62.07%  |
| Yes       | 22        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 91.38%  |
| No        | 5         | 8.62%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 75.86%  |
| No        | 14        | 24.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 60.34%  |
| No        | 23        | 39.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 21        | 36.21%  |
| France       | 13        | 22.41%  |
| Brazil       | 5         | 8.62%   |
| Spain        | 3         | 5.17%   |
| Germany      | 3         | 5.17%   |
| UK           | 2         | 3.45%   |
| Switzerland  | 2         | 3.45%   |
| India        | 2         | 3.45%   |
| Belgium      | 2         | 3.45%   |
| South Africa | 1         | 1.72%   |
| Slovakia     | 1         | 1.72%   |
| Netherlands  | 1         | 1.72%   |
| Mexico       | 1         | 1.72%   |
| Australia    | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toulouse               | 2         | 3.45%   |
| Philadelphia           | 2         | 3.45%   |
| Paris                  | 2         | 3.45%   |
| Meulan-en-Yvelines     | 2         | 3.45%   |
| Westfield              | 1         | 1.72%   |
| Vitoria-Gasteiz        | 1         | 1.72%   |
| Villejuif              | 1         | 1.72%   |
| Valencia               | 1         | 1.72%   |
| Tresses                | 1         | 1.72%   |
| Starkville             | 1         | 1.72%   |
| Short Hills            | 1         | 1.72%   |
| Segovia                | 1         | 1.72%   |
| Sao Paulo              | 1         | 1.72%   |
| Santa Clara            | 1         | 1.72%   |
| Salt Lake City         | 1         | 1.72%   |
| Roesrath               | 1         | 1.72%   |
| Rio de Janeiro         | 1         | 1.72%   |
| Rieschweiler-Muehlbach | 1         | 1.72%   |
| Reno                   | 1         | 1.72%   |
| Prattville             | 1         | 1.72%   |
| Pinckney               | 1         | 1.72%   |
| Perth                  | 1         | 1.72%   |
| Onex                   | 1         | 1.72%   |
| Nova Iguaçu           | 1         | 1.72%   |
| Nitra                  | 1         | 1.72%   |
| Nieuw-Vossemeer        | 1         | 1.72%   |
| Milwaukee              | 1         | 1.72%   |
| Middlesbrough          | 1         | 1.72%   |
| Miami                  | 1         | 1.72%   |
| Medway                 | 1         | 1.72%   |
| Mechanicsburg          | 1         | 1.72%   |
| Manchester             | 1         | 1.72%   |
| Malappuram             | 1         | 1.72%   |
| Madrid                 | 1         | 1.72%   |
| Maceió                | 1         | 1.72%   |
| Liège                 | 1         | 1.72%   |
| Lawley                 | 1         | 1.72%   |
| Las Vegas              | 1         | 1.72%   |
| Lagorce                | 1         | 1.72%   |
| Joaima                 | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 13        | 16     | 14.94%  |
| Seagate                     | 12        | 24     | 13.79%  |
| Samsung Electronics         | 12        | 16     | 13.79%  |
| Kingston                    | 6         | 6      | 6.9%    |
| Toshiba                     | 5         | 5      | 5.75%   |
| Intel                       | 5         | 7      | 5.75%   |
| SanDisk                     | 4         | 4      | 4.6%    |
| HGST                        | 3         | 3      | 3.45%   |
| Unknown                     | 2         | 2      | 2.3%    |
| Micron Technology           | 2         | 2      | 2.3%    |
| KIOXIA                      | 2         | 2      | 2.3%    |
| A-DATA Technology           | 2         | 2      | 2.3%    |
| Unknown                     | 2         | 2      | 2.3%    |
| TO Exter                    | 1         | 1      | 1.15%   |
| TCSUNBOW                    | 1         | 1      | 1.15%   |
| SSK                         | 1         | 1      | 1.15%   |
| SK hynix                    | 1         | 1      | 1.15%   |
| Mushkin                     | 1         | 1      | 1.15%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.15%   |
| MARSHAL                     | 1         | 1      | 1.15%   |
| LITEONIT                    | 1         | 1      | 1.15%   |
| LITEON                      | 1         | 1      | 1.15%   |
| Lexar                       | 1         | 1      | 1.15%   |
| JMicron Technology          | 1         | 1      | 1.15%   |
| Hitachi                     | 1         | 1      | 1.15%   |
| Crucial                     | 1         | 1      | 1.15%   |
| Corsair                     | 1         | 1      | 1.15%   |
| China                       | 1         | 1      | 1.15%   |
| BHT                         | 1         | 1      | 1.15%   |
| ASMedia                     | 1         | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB              | 2         | 2.11%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 2.11%   |
| Seagate ST500DM002-1BD142 500GB           | 2         | 2.11%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 2.11%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 2.11%   |
| HGST HTS541010A9E680 1TB                  | 2         | 2.11%   |
| Unknown                                   | 2         | 2.11%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 1.05%   |
| WDC WD800BB-55JKC0 80GB                   | 1         | 1.05%   |
| WDC WD6400AAKS-65A7B2 640GB               | 1         | 1.05%   |
| WDC WD5003ABYX-18WERA0 500GB              | 1         | 1.05%   |
| WDC WD5000AAKX-60U6AA0 500GB              | 1         | 1.05%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1         | 1.05%   |
| WDC WD3200BPVT-22ZEST0 320GB              | 1         | 1.05%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1.05%   |
| WDC WD20NPVZ-82WFZT0 2TB                  | 1         | 1.05%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.05%   |
| WDC WD10EZEX-75WN4A1 1TB                  | 1         | 1.05%   |
| WDC WD10EZEX-00BN5A0 1TB                  | 1         | 1.05%   |
| WDC WD Green 2.5 480GB                    | 1         | 1.05%   |
| Unknown SD  1GB                           | 1         | 1.05%   |
| Unknown CUTB42  64GB                      | 1         | 1.05%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.05%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.05%   |
| Toshiba KXG6AZNV1T02 1TB                  | 1         | 1.05%   |
| Toshiba HDWD130 3TB                       | 1         | 1.05%   |
| Toshiba DT01ACA050 500GB                  | 1         | 1.05%   |
| TO Exter nal USB 3.0 250GB                | 1         | 1.05%   |
| TCSUNBOW N4 120GB SSD                     | 1         | 1.05%   |
| SSK Storage 1TB                           | 1         | 1.05%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.05%   |
| Seagate ST8000DM004-2CX188 8TB            | 1         | 1.05%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1.05%   |
| Seagate ST32000645SS 2TB                  | 1         | 1.05%   |
| Seagate ST31000528AS 1TB                  | 1         | 1.05%   |
| Seagate ST3000DM001-1ER166 3TB            | 1         | 1.05%   |
| Seagate ST2000DM008-2UB102 2TB            | 1         | 1.05%   |
| Seagate ST2000DM008-2FR102 2TB            | 1         | 1.05%   |
| Seagate ST2000DM006-2DM164 2TB            | 1         | 1.05%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 24     | 34.29%  |
| WDC                 | 10        | 12     | 28.57%  |
| Toshiba             | 4         | 4      | 11.43%  |
| HGST                | 3         | 3      | 8.57%   |
| TO Exter            | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| MARSHAL             | 1         | 1      | 2.86%   |
| JMicron Technology  | 1         | 1      | 2.86%   |
| Hitachi             | 1         | 1      | 2.86%   |
| Unknown             | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 20.59%  |
| Kingston            | 5         | 5      | 14.71%  |
| WDC                 | 4         | 4      | 11.76%  |
| SanDisk             | 4         | 4      | 11.76%  |
| Intel               | 2         | 3      | 5.88%   |
| A-DATA Technology   | 2         | 2      | 5.88%   |
| TCSUNBOW            | 1         | 1      | 2.94%   |
| Mushkin             | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 1      | 2.94%   |
| LITEON              | 1         | 1      | 2.94%   |
| Lexar               | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| BHT                 | 1         | 1      | 2.94%   |
| ASMedia             | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 49     | 39.74%  |
| SSD  | 28        | 35     | 35.9%   |
| NVMe | 17        | 22     | 21.79%  |
| MMC  | 2         | 2      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 75     | 63.51%  |
| NVMe | 17        | 21     | 22.97%  |
| SAS  | 8         | 10     | 10.81%  |
| MMC  | 2         | 2      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 49     | 61.02%  |
| 0.51-1.0   | 15        | 15     | 25.42%  |
| 1.01-2.0   | 4         | 16     | 6.78%   |
| 2.01-3.0   | 3         | 3      | 5.08%   |
| 4.01-10.0  | 1         | 1      | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 10        | 17.24%  |
| 1-20           | 10        | 17.24%  |
| 101-250        | 9         | 15.52%  |
| 501-1000       | 9         | 15.52%  |
| 1001-2000      | 5         | 8.62%   |
| 51-100         | 5         | 8.62%   |
| Unknown        | 5         | 8.62%   |
| 21-50          | 2         | 3.45%   |
| 2001-3000      | 2         | 3.45%   |
| More than 3000 | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 27        | 46.55%  |
| 21-50          | 8         | 13.79%  |
| 501-1000       | 6         | 10.34%  |
| Unknown        | 5         | 8.62%   |
| 101-250        | 4         | 6.9%    |
| 251-500        | 3         | 5.17%   |
| 51-100         | 3         | 5.17%   |
| More than 3000 | 1         | 1.72%   |
| 2001-3000      | 1         | 1.72%   |

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
| WDC WD Green 2.5 480GB            | 1         | 1      | 6.25%   |
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
| Works    | 43        | 79     | 62.32%  |
| Malfunc  | 15        | 16     | 21.74%  |
| Detected | 10        | 12     | 14.49%  |
| Failed   | 1         | 1      | 1.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 40        | 57.97%  |
| AMD                          | 11        | 15.94%  |
| Samsung Electronics          | 6         | 8.7%    |
| Nvidia                       | 2         | 2.9%    |
| Micron Technology            | 2         | 2.9%    |
| KIOXIA                       | 2         | 2.9%    |
| Toshiba America Info Systems | 1         | 1.45%   |
| SK hynix                     | 1         | 1.45%   |
| Phison Electronics           | 1         | 1.45%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.45%   |
| Kingston Technology Company  | 1         | 1.45%   |
| Broadcom / LSI               | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 10%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 6.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 3.75%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 3.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.5%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.5%    |
| Intel SATA Controller [RAID mode]                                              | 2         | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.5%    |
| Intel C604/X79 series chipset 4-Port SATA/SAS Storage Control Unit             | 2         | 2.5%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.25%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.25%   |
| Phison E8 PCIe3 x2 NVMe Controller                                             | 1         | 1.25%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.25%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.25%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.25%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.25%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.25%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.25%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 1         | 1.25%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.25%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.25%   |
| Intel SSD 660P Series                                                          | 1         | 1.25%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.25%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.25%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.25%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.25%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 45        | 60.81%  |
| NVMe | 17        | 22.97%  |
| RAID | 7         | 9.46%   |
| IDE  | 3         | 4.05%   |
| SAS  | 2         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 77.59%  |
| AMD    | 13        | 22.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 5.17%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2         | 3.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 2         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 3.45%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1         | 1.72%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1         | 1.72%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1         | 1.72%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.72%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 1.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.72%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1         | 1.72%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.72%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.72%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1         | 1.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.72%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1         | 1.72%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1         | 1.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.72%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.72%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.72%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.72%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.72%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.72%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.72%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 1         | 1.72%   |
| Intel Celeron N4120 CPU @ 1.10GHz           | 1         | 1.72%   |
| Intel Celeron CPU U3600 @ 1.20GHz           | 1         | 1.72%   |
| Intel 12th Gen Core i7-12700T               | 1         | 1.72%   |
| Intel 12th Gen Core i7-12700H               | 1         | 1.72%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 1         | 1.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 31.03%  |
| Intel Core i7           | 9         | 15.52%  |
| Other                   | 7         | 12.07%  |
| Intel Xeon              | 3         | 5.17%   |
| Intel Pentium           | 3         | 5.17%   |
| Intel Celeron           | 2         | 3.45%   |
| AMD Ryzen 7             | 2         | 3.45%   |
| AMD Ryzen 5             | 2         | 3.45%   |
| AMD A6                  | 2         | 3.45%   |
| Intel Pentium Dual-Core | 1         | 1.72%   |
| Intel Core i3           | 1         | 1.72%   |
| Intel Core 2 Quad       | 1         | 1.72%   |
| Intel Core 2 Duo        | 1         | 1.72%   |
| AMD Ryzen Threadripper  | 1         | 1.72%   |
| AMD Ryzen 9             | 1         | 1.72%   |
| AMD FX                  | 1         | 1.72%   |
| AMD E2                  | 1         | 1.72%   |
| AMD Athlon 64           | 1         | 1.72%   |
| AMD A10                 | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 37.93%  |
| 4      | 20        | 34.48%  |
| 12     | 4         | 6.9%    |
| 1      | 4         | 6.9%    |
| 8      | 3         | 5.17%   |
| 6      | 3         | 5.17%   |
| 14     | 1         | 1.72%   |
| 3      | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 98.28%  |
| 2      | 1         | 1.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 70.69%  |
| 1      | 17        | 29.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 58        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 17.24%  |
| 0x306a9    | 5         | 8.62%   |
| 0x306d4    | 4         | 6.9%    |
| 0x806c1    | 3         | 5.17%   |
| 0x306c3    | 3         | 5.17%   |
| 0x206a7    | 3         | 5.17%   |
| 0x506e3    | 2         | 3.45%   |
| 0xa0652    | 1         | 1.72%   |
| 0x906ea    | 1         | 1.72%   |
| 0x906e9    | 1         | 1.72%   |
| 0x906a3    | 1         | 1.72%   |
| 0x90672    | 1         | 1.72%   |
| 0x806e9    | 1         | 1.72%   |
| 0x706e5    | 1         | 1.72%   |
| 0x6fb      | 1         | 1.72%   |
| 0x406e3    | 1         | 1.72%   |
| 0x40651    | 1         | 1.72%   |
| 0x306e4    | 1         | 1.72%   |
| 0x206d7    | 1         | 1.72%   |
| 0x20655    | 1         | 1.72%   |
| 0x106a5    | 1         | 1.72%   |
| 0x1067a    | 1         | 1.72%   |
| 0x10676    | 1         | 1.72%   |
| 0x0a20120a | 1         | 1.72%   |
| 0x0a201016 | 1         | 1.72%   |
| 0x08701021 | 1         | 1.72%   |
| 0x08600106 | 1         | 1.72%   |
| 0x0800820b | 1         | 1.72%   |
| 0x08001137 | 1         | 1.72%   |
| 0x07030106 | 1         | 1.72%   |
| 0x06006705 | 1         | 1.72%   |
| 0x0600111f | 1         | 1.72%   |
| 0x06001119 | 1         | 1.72%   |
| 0x06001116 | 1         | 1.72%   |
| 0x06000822 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 7         | 12.07%  |
| IvyBridge        | 6         | 10.34%  |
| SandyBridge      | 5         | 8.62%   |
| Broadwell        | 5         | 8.62%   |
| Piledriver       | 4         | 6.9%    |
| KabyLake         | 4         | 6.9%    |
| TigerLake        | 3         | 5.17%   |
| Skylake          | 3         | 5.17%   |
| Zen 3            | 2         | 3.45%   |
| Zen 2            | 2         | 3.45%   |
| Penryn           | 2         | 3.45%   |
| Icelake          | 2         | 3.45%   |
| CometLake        | 2         | 3.45%   |
| Alderlake Hybrid | 2         | 3.45%   |
| Zen+             | 1         | 1.72%   |
| Zen              | 1         | 1.72%   |
| Westmere         | 1         | 1.72%   |
| Puma             | 1         | 1.72%   |
| Nehalem          | 1         | 1.72%   |
| K8 Hammer        | 1         | 1.72%   |
| Goldmont plus    | 1         | 1.72%   |
| Excavator        | 1         | 1.72%   |
| Core             | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 37        | 54.41%  |
| Nvidia                     | 15        | 22.06%  |
| AMD                        | 15        | 22.06%  |
| Matrox Electronics Systems | 1         | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Broadwell-U GT2 [HD Graphics 5500]                                      | 5         | 7.25%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 5.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 5.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 4.35%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                         | 2         | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.9%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 2.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.45%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1         | 1.45%   |
| Nvidia MCP7A [GeForce 9400]                                                   | 1         | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 1.45%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 1.45%   |
| Nvidia GK107M [GeForce GT 740M]                                               | 1         | 1.45%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1         | 1.45%   |
| Nvidia GF119M [Quadro NVS 4200M]                                              | 1         | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.45%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 1         | 1.45%   |
| Nvidia G94GL [Quadro FX 1800]                                                 | 1         | 1.45%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 1.45%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 1         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.45%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                         | 1         | 1.45%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                       | 1         | 1.45%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                       | 1         | 1.45%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.45%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                     | 1         | 1.45%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 1         | 1.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 1         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 44.83%  |
| 1 x AMD        | 11        | 18.97%  |
| 1 x Nvidia     | 8         | 13.79%  |
| Intel + Nvidia | 7         | 12.07%  |
| Intel + AMD    | 3         | 5.17%   |
| 2 x Intel      | 1         | 1.72%   |
| 2 x AMD        | 1         | 1.72%   |
| 1 x Matrox     | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 55        | 94.83%  |
| Proprietary | 2         | 3.45%   |
| Unknown     | 1         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 53.45%  |
| 0.51-1.0   | 7         | 12.07%  |
| 7.01-8.0   | 6         | 10.34%  |
| 1.01-2.0   | 6         | 10.34%  |
| 0.01-0.5   | 4         | 6.9%    |
| 3.01-4.0   | 3         | 5.17%   |
| 5.01-6.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 9         | 14.75%  |
| AU Optronics            | 7         | 11.48%  |
| LG Display              | 6         | 9.84%   |
| Hewlett-Packard         | 5         | 8.2%    |
| Samsung Electronics     | 4         | 6.56%   |
| Dell                    | 4         | 6.56%   |
| Acer                    | 4         | 6.56%   |
| BOE                     | 3         | 4.92%   |
| Apple                   | 3         | 4.92%   |
| ViewSonic               | 2         | 3.28%   |
| Sharp                   | 2         | 3.28%   |
| Lenovo                  | 2         | 3.28%   |
| Goldstar                | 2         | 3.28%   |
| Chi Mei Optoelectronics | 2         | 3.28%   |
| Vizio                   | 1         | 1.64%   |
| Sceptre Tech            | 1         | 1.64%   |
| Philips                 | 1         | 1.64%   |
| PANDA                   | 1         | 1.64%   |
| Iiyama                  | 1         | 1.64%   |
| Grundig                 | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 2         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 3.23%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1         | 1.61%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 1.61%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch            | 1         | 1.61%   |
| Sharp LQ173M1JW08 SHP1544 1920x1080 382x215mm 17.3-inch               | 1         | 1.61%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch               | 1         | 1.61%   |
| Sceptre Tech Sceptre H43 SPT1103 1920x1080 575x323mm 26.0-inch        | 1         | 1.61%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 1.61%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch  | 1         | 1.61%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 1.61%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 1         | 1.61%   |
| LG Display LCD Monitor LGD40BA 1920x1080 340x190mm 15.3-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch           | 1         | 1.61%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch           | 1         | 1.61%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 1.61%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 1.61%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                  | 1         | 1.61%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch            | 1         | 1.61%   |
| Hewlett-Packard V27ie G5 HPN3889 1920x1080 597x336mm 27.0-inch        | 1         | 1.61%   |
| Hewlett-Packard V221 HWP3111 1920x1080 477x268mm 21.5-inch            | 1         | 1.61%   |
| Hewlett-Packard Contino HPN404C 1920x1080 597x366mm 27.6-inch         | 1         | 1.61%   |
| Hewlett-Packard Contino HPN4035 1920x1080 597x336mm 27.0-inch         | 1         | 1.61%   |
| Grundig WUXGA GRU4448 1360x768                                        | 1         | 1.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.61%   |
| Goldstar E1960 GSM4BE5 1360x768 406x229mm 18.4-inch                   | 1         | 1.61%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1         | 1.61%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                   | 1         | 1.61%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                    | 1         | 1.61%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 1         | 1.61%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch       | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 51.72%  |
| 1366x768 (WXGA)    | 11        | 18.97%  |
| 1600x900 (HD+)     | 5         | 8.62%   |
| 3840x2160 (4K)     | 3         | 5.17%   |
| 2560x1440 (QHD)    | 2         | 3.45%   |
| 1440x900 (WXGA+)   | 2         | 3.45%   |
| 1920x1200 (WUXGA)  | 1         | 1.72%   |
| 1680x1050 (WSXGA+) | 1         | 1.72%   |
| 1360x768           | 1         | 1.72%   |
| 1280x800 (WXGA)    | 1         | 1.72%   |
| 1280x1024 (SXGA)   | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 19.67%  |
| 14     | 8         | 13.11%  |
| 13     | 7         | 11.48%  |
| 27     | 6         | 9.84%   |
| 21     | 5         | 8.2%    |
| 17     | 5         | 8.2%    |
| 23     | 4         | 6.56%   |
| 31     | 3         | 4.92%   |
| 26     | 2         | 3.28%   |
| 19     | 2         | 3.28%   |
| 18     | 2         | 3.28%   |
| 54     | 1         | 1.64%   |
| 25     | 1         | 1.64%   |
| 24     | 1         | 1.64%   |
| 22     | 1         | 1.64%   |
| 11     | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 42.62%  |
| 501-600     | 14        | 22.95%  |
| 401-500     | 10        | 16.39%  |
| 351-400     | 4         | 6.56%   |
| 601-700     | 3         | 4.92%   |
| 201-300     | 3         | 4.92%   |
| 1001-1500   | 1         | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 87.72%  |
| 16/10 | 6         | 10.53%  |
| 5/4   | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 22.95%  |
| 101-110        | 12        | 19.67%  |
| 201-250        | 9         | 14.75%  |
| 301-350        | 6         | 9.84%   |
| 151-200        | 5         | 8.2%    |
| 121-130        | 4         | 6.56%   |
| 351-500        | 3         | 4.92%   |
| 251-300        | 3         | 4.92%   |
| 141-150        | 2         | 3.28%   |
| More than 1000 | 1         | 1.64%   |
| 71-80          | 1         | 1.64%   |
| 51-60          | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 20        | 33.33%  |
| 121-160 | 19        | 31.67%  |
| 101-120 | 19        | 31.67%  |
| 1-50    | 1         | 1.67%   |
| 161-240 | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 49        | 84.48%  |
| 2     | 8         | 13.79%  |
| 0     | 1         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 36.05%  |
| Realtek Semiconductor | 27        | 31.4%   |
| Qualcomm Atheros      | 13        | 15.12%  |
| TP-Link               | 4         | 4.65%   |
| Broadcom              | 4         | 4.65%   |
| Nvidia                | 2         | 2.33%   |
| Lenovo                | 2         | 2.33%   |
| Sierra Wireless       | 1         | 1.16%   |
| Gemtek                | 1         | 1.16%   |
| ASUSTek Computer      | 1         | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 17        | 16.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 4.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 3.85%   |
| Intel Wireless 7265                                                    | 4         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 2.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 1.92%   |
| Intel Wireless 7260                                                    | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.92%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.92%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.92%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                            | 1         | 0.96%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 0.96%   |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 0.96%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.96%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 0.96%   |
| Realtek 802.11ac NIC                                                   | 1         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.96%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.96%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.96%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.96%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.96%   |
| Lenovo P2a42                                                           | 1         | 0.96%   |
| Intel Wireless 8265 / 8275                                             | 1         | 0.96%   |
| Intel Wireless 8260                                                    | 1         | 0.96%   |
| Intel Wireless 3165                                                    | 1         | 0.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 45.83%  |
| Qualcomm Atheros      | 12        | 25%     |
| Realtek Semiconductor | 5         | 10.42%  |
| TP-Link               | 4         | 8.33%   |
| Broadcom              | 2         | 4.17%   |
| Sierra Wireless       | 1         | 2.08%   |
| Gemtek                | 1         | 2.08%   |
| ASUSTek Computer      | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 4         | 8.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 6.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 4.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 4.17%   |
| Intel Wireless 7260                                            | 2         | 4.17%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.17%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1         | 2.08%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 2.08%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 2.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 2.08%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.08%   |
| Realtek 802.11ac NIC                                           | 1         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 2.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.08%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.08%   |
| Intel Wireless 8260                                            | 1         | 2.08%   |
| Intel Wireless 3165                                            | 1         | 2.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 2.08%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.08%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 2.08%   |
| Gemtek WUBR-177G [Ralink RT2571W]                              | 1         | 2.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.08%   |
| ASUS 802.11ac NIC                                              | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 45.45%  |
| Intel                 | 20        | 36.36%  |
| Qualcomm Atheros      | 3         | 5.45%   |
| Broadcom              | 3         | 5.45%   |
| Nvidia                | 2         | 3.64%   |
| Lenovo                | 2         | 3.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 17        | 30.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 8.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 7.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 3.57%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 3.57%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 3.57%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 3.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 3.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 1.79%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.79%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.79%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 1.79%   |
| Lenovo P2a42                                                           | 1         | 1.79%   |
| Intel I350 Gigabit Network Connection                                  | 1         | 1.79%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.79%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.79%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.79%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.79%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 1.79%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 1.79%   |
| Intel 82575EB Gigabit Network Connection                               | 1         | 1.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 54.64%  |
| WiFi     | 44        | 45.36%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 50%     |
| Ethernet | 30        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 56.9%   |
| 1     | 22        | 37.93%  |
| 4     | 2         | 3.45%   |
| 0     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 70.69%  |
| Yes  | 17        | 29.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 48.57%  |
| Qualcomm Atheros Communications | 5         | 14.29%  |
| Broadcom                        | 4         | 11.43%  |
| Realtek Semiconductor           | 3         | 8.57%   |
| Apple                           | 3         | 8.57%   |
| IMC Networks                    | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Cambridge Silicon Radio         | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 22.86%  |
| Realtek Bluetooth Radio                             | 3         | 8.57%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 8.57%   |
| Intel AX201 Bluetooth                               | 3         | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 5.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 5.71%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.86%   |
| Intel Bluetooth Device                              | 1         | 2.86%   |
| Intel AX210 Bluetooth                               | 1         | 2.86%   |
| Intel AX200 Bluetooth                               | 1         | 2.86%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.86%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.86%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.86%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.86%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 43        | 54.43%  |
| AMD                 | 16        | 20.25%  |
| Nvidia              | 14        | 17.72%  |
| Roland              | 1         | 1.27%   |
| Plantronics         | 1         | 1.27%   |
| Logitech            | 1         | 1.27%   |
| Lenovo              | 1         | 1.27%   |
| C-Media Electronics | 1         | 1.27%   |
| ASUSTek Computer    | 1         | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP High Definition Audio Controller                      | 5         | 5.26%   |
| Intel Broadwell-U Audio Controller                                           | 5         | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller          | 5         | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller          | 4         | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller   | 4         | 4.21%   |
| AMD FCH Azalia Controller                                                    | 4         | 4.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                  | 3         | 3.16%   |
| AMD Trinity HDMI Audio Controller                                            | 3         | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                              | 2         | 2.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                        | 2         | 2.11%   |
| Nvidia GK107 HDMI Audio Controller                                           | 2         | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller             | 2         | 2.11%   |
| Intel Sunrise Point-LP HD Audio                                              | 2         | 2.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                             | 2         | 2.11%   |
| Intel 8 Series HD Audio Controller                                           | 2         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller              | 2         | 2.11%   |
| AMD Starship/Matisse HD Audio Controller                                     | 2         | 2.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                      | 2         | 2.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                          | 2         | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                   | 2         | 2.11%   |
| Roland QUAD-CAPTURE                                                          | 1         | 1.05%   |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter) | 1         | 1.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller               | 1         | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                | 1         | 1.05%   |
| Nvidia MCP79 High Definition Audio                                           | 1         | 1.05%   |
| Nvidia MCP61 High Definition Audio                                           | 1         | 1.05%   |
| Nvidia GP108 High Definition Audio Controller                                | 1         | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                           | 1         | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                                | 1         | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                                | 1         | 1.05%   |
| Logitech [G533 Wireless Headset Dongle]                                      | 1         | 1.05%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                    | 1         | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                       | 1         | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                    | 1         | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                        | 1         | 1.05%   |
| Intel Comet Lake PCH-V cAVS                                                  | 1         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                    | 1         | 1.05%   |
| Intel CM238 HD Audio Controller                                              | 1         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                 | 1         | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                       | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 22.86%  |
| SK hynix            | 15        | 21.43%  |
| Kingston            | 9         | 12.86%  |
| Crucial             | 7         | 10%     |
| Micron Technology   | 5         | 7.14%   |
| Corsair             | 4         | 5.71%   |
| A-DATA Technology   | 3         | 4.29%   |
| Unknown             | 2         | 2.86%   |
| G.Skill             | 2         | 2.86%   |
| Elpida              | 2         | 2.86%   |
| Team                | 1         | 1.43%   |
| Ramaxel Technology  | 1         | 1.43%   |
| Apacer              | 1         | 1.43%   |
| A Force             | 1         | 1.43%   |
| 8A020000802C        | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s       | 2         | 2.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 2.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s        | 2         | 2.56%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2         | 2.56%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 2.56%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.28%   |
| Unknown RAM Module 1GB DIMM 400MT/s                          | 1         | 1.28%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s         | 1         | 1.28%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.28%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 1         | 1.28%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1         | 1.28%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1         | 1.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.28%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.28%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s      | 1         | 1.28%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.28%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 1.28%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1.28%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.28%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.28%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.28%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s        | 1         | 1.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.28%   |
| Samsung RAM M471B5173BH0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.28%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.28%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s          | 1         | 1.28%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s       | 1         | 1.28%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 1.28%   |
| Samsung RAM 456789ABCDEFGHIJKL 8GB SODIMM DDR3 1600MT/s      | 1         | 1.28%   |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.28%   |
| Micron RAM Module 4GB SODIMM DDR3 1333MT/s                   | 1         | 1.28%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.28%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 30        | 51.72%  |
| DDR4    | 23        | 39.66%  |
| LPDDR4  | 2         | 3.45%   |
| DDR2    | 2         | 3.45%   |
| Unknown | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 59.32%  |
| DIMM         | 20        | 33.9%   |
| Row Of Chips | 3         | 5.08%   |
| Chip         | 1         | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 42.19%  |
| 4096  | 19        | 29.69%  |
| 16384 | 8         | 12.5%   |
| 2048  | 5         | 7.81%   |
| 32768 | 3         | 4.69%   |
| 1024  | 2         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 23        | 36.51%  |
| 3200  | 10        | 15.87%  |
| 2667  | 6         | 9.52%   |
| 1333  | 5         | 7.94%   |
| 3600  | 4         | 6.35%   |
| 4267  | 2         | 3.17%   |
| 2400  | 2         | 3.17%   |
| 2133  | 2         | 3.17%   |
| 800   | 2         | 3.17%   |
| 49926 | 1         | 1.59%   |
| 3933  | 1         | 1.59%   |
| 3800  | 1         | 1.59%   |
| 2933  | 1         | 1.59%   |
| 1648  | 1         | 1.59%   |
| 1067  | 1         | 1.59%   |
| 400   | 1         | 1.59%   |

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


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung M2070 Series            | 1         | 50%     |
| Kyocera Kyocera ECOSYS P5021cdw | 1         | 50%     |

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
| Chicony Electronics                    | 6         | 17.65%  |
| Bison Electronics                      | 5         | 14.71%  |
| Realtek Semiconductor                  | 4         | 11.76%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 8.82%   |
| Apple                                  | 3         | 8.82%   |
| Sunplus Innovation Technology          | 2         | 5.88%   |
| Quanta                                 | 2         | 5.88%   |
| Microdia                               | 2         | 5.88%   |
| Lite-On Technology                     | 2         | 5.88%   |
| Suyin                                  | 1         | 2.94%   |
| Silicon Motion                         | 1         | 2.94%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 2.94%   |
| Luxvisions Innotech Limited            | 1         | 2.94%   |
| IMC Networks                           | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                 | 3         | 8.82%   |
| Realtek Integrated_Webcam_HD                            | 2         | 5.88%   |
| Lite-On HP HD Webcam                                    | 2         | 5.88%   |
| Chicony Integrated Camera                               | 2         | 5.88%   |
| Chicony HP HD Webcam                                    | 2         | 5.88%   |
| Bison HD Webcam                                         | 2         | 5.88%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 2.94%   |
| Sunplus Integrated Webcam                               | 1         | 2.94%   |
| Sunplus Asus Webcam                                     | 1         | 2.94%   |
| Silicon Motion ATIV VGA Camera                          | 1         | 2.94%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 1         | 2.94%   |
| Realtek USB Camera                                      | 1         | 2.94%   |
| Realtek Integrated Camera                               | 1         | 2.94%   |
| Quanta HP TrueVision HD Camera                          | 1         | 2.94%   |
| Quanta HP 5MP Camera                                    | 1         | 2.94%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 2.94%   |
| Microdia Integrated_Webcam_HD                           | 1         | 2.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 1         | 2.94%   |
| IMC Networks Integrated Camera                          | 1         | 2.94%   |
| Chicony HP Truevision HD                                | 1         | 2.94%   |
| Chicony HP HD Camera                                    | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 2.94%   |
| Apple FaceTime HD Camera (Built-in)                     | 1         | 2.94%   |
| Apple FaceTime HD Camera                                | 1         | 2.94%   |
| Apple Built-in iSight                                   | 1         | 2.94%   |

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
| 0     | 37        | 63.79%  |
| 1     | 18        | 31.03%  |
| 2     | 2         | 3.45%   |
| 3     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 40.91%  |
| Net/wireless             | 5         | 22.73%  |
| Graphics card            | 2         | 9.09%   |
| Chipcard                 | 2         | 9.09%   |
| Unassigned class         | 1         | 4.55%   |
| Communication controller | 1         | 4.55%   |
| Card reader              | 1         | 4.55%   |
| Camera                   | 1         | 4.55%   |

