Makulu - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Makulu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 46

| Vendor        | Model                 | Probe                                                      | Date         |
|---------------|-----------------------|------------------------------------------------------------|--------------|
| MSI           | H81M-P33              | [7f7dc5c76e](https://linux-hardware.org/?probe=7f7dc5c76e) | Nov 03, 2024 |
| ASRock        | Z790-C                | [b76164a1d1](https://linux-hardware.org/?probe=b76164a1d1) | Sep 26, 2024 |
| ASRock        | Z790-C                | [70d265a433](https://linux-hardware.org/?probe=70d265a433) | Sep 17, 2024 |
| Dell          | 0GXM1W A02            | [daa70c78f0](https://linux-hardware.org/?probe=daa70c78f0) | Dec 12, 2023 |
| Dell          | 0GXM1W A02            | [9b084ae5b9](https://linux-hardware.org/?probe=9b084ae5b9) | Dec 11, 2023 |
| Dell          | 0P01GV A03            | [a2ef6d8517](https://linux-hardware.org/?probe=a2ef6d8517) | Jun 27, 2023 |
| MSI           | Z97 MPOWER            | [0cf75057cc](https://linux-hardware.org/?probe=0cf75057cc) | Jun 24, 2023 |
| Eii           | GB01                  | [eb73cef296](https://linux-hardware.org/?probe=eb73cef296) | Jan 22, 2023 |
| Eii           | GB01                  | [0b5b540112](https://linux-hardware.org/?probe=0b5b540112) | Jan 22, 2023 |
| Eii           | GB01                  | [35c7a7739d](https://linux-hardware.org/?probe=35c7a7739d) | Jan 18, 2023 |
| MSI           | 970A-G43              | [cf36036d1d](https://linux-hardware.org/?probe=cf36036d1d) | Oct 18, 2022 |
| MSI           | 970A-G43              | [c9c2e07ada](https://linux-hardware.org/?probe=c9c2e07ada) | Oct 10, 2022 |
| MSI           | 970A-G43              | [0b6ff268e1](https://linux-hardware.org/?probe=0b6ff268e1) | Oct 10, 2022 |
| ASRock        | B450 Pro4             | [d750223c3f](https://linux-hardware.org/?probe=d750223c3f) | Sep 12, 2022 |
| ASUSTek       | M5A97 R2.0            | [5e75c2d00d](https://linux-hardware.org/?probe=5e75c2d00d) | May 29, 2022 |
| ASUSTek       | P5QC                  | [2f4a501c6a](https://linux-hardware.org/?probe=2f4a501c6a) | Mar 05, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF   | [5d298b8068](https://linux-hardware.org/?probe=5d298b8068) | Jan 04, 2022 |
| ASUSTek       | M5A97 R2.0            | [d3dc0d2eec](https://linux-hardware.org/?probe=d3dc0d2eec) | Nov 04, 2021 |
| Dell          | 0TP406                | [df97b29e2e](https://linux-hardware.org/?probe=df97b29e2e) | Oct 23, 2021 |
| Dell          | 0TP406                | [5e3ac96715](https://linux-hardware.org/?probe=5e3ac96715) | Oct 22, 2021 |
| MSI           | Boston                | [c45a00b3d6](https://linux-hardware.org/?probe=c45a00b3d6) | Oct 22, 2021 |
| Gigabyte      | 990FXA-UD5            | [f3168dad1b](https://linux-hardware.org/?probe=f3168dad1b) | Oct 21, 2021 |
| Acer          | Nitro N50-600 V:1.1   | [d3c50b3461](https://linux-hardware.org/?probe=d3c50b3461) | Sep 26, 2021 |
| MSI           | Boston                | [d95f0de735](https://linux-hardware.org/?probe=d95f0de735) | Sep 21, 2021 |
| MSI           | Boston                | [50f3ed26ef](https://linux-hardware.org/?probe=50f3ed26ef) | Sep 21, 2021 |
| Dell          | 0WR7PY A02            | [b5e3a47db9](https://linux-hardware.org/?probe=b5e3a47db9) | Sep 06, 2021 |
| ELSA          | EA H410M-E            | [b67c732be6](https://linux-hardware.org/?probe=b67c732be6) | Jul 19, 2021 |
| ELSA          | EA H410M-E            | [97d82b0054](https://linux-hardware.org/?probe=97d82b0054) | Jul 19, 2021 |
| Dell          | 0MWYPT A00            | [3577268e97](https://linux-hardware.org/?probe=3577268e97) | Jul 14, 2021 |
| Gigabyte      | B85M-HD3              | [0da2654313](https://linux-hardware.org/?probe=0da2654313) | Jun 21, 2021 |
| Alienware     | 02XRCM A01            | [42fb24801d](https://linux-hardware.org/?probe=42fb24801d) | Jun 18, 2021 |
| Alienware     | 02XRCM A01            | [929ffb30b7](https://linux-hardware.org/?probe=929ffb30b7) | Jun 18, 2021 |
| Dell          | 0XFWHV A00            | [e318737297](https://linux-hardware.org/?probe=e318737297) | May 02, 2021 |
| Lenovo        | IdeaCentre K430       | [cfee2604e5](https://linux-hardware.org/?probe=cfee2604e5) | Apr 30, 2021 |
| MSI           | A68HM-P33             | [52eb515b91](https://linux-hardware.org/?probe=52eb515b91) | Apr 01, 2021 |
| ASRock        | Z77 Pro4              | [981009625b](https://linux-hardware.org/?probe=981009625b) | Mar 29, 2021 |
| Flextronic... | CPU-5A-C21 C21        | [4aca4558e4](https://linux-hardware.org/?probe=4aca4558e4) | Mar 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS | [323c65cc17](https://linux-hardware.org/?probe=323c65cc17) | Mar 11, 2021 |
| Dell          | 0XCR8D A01            | [3ed805ccdf](https://linux-hardware.org/?probe=3ed805ccdf) | Feb 26, 2021 |
| Dell          | 0XCR8D A01            | [4f32c299db](https://linux-hardware.org/?probe=4f32c299db) | Feb 21, 2021 |
| Gigabyte      | GA-880GM-UD2H         | [61834d7ebf](https://linux-hardware.org/?probe=61834d7ebf) | Dec 03, 2020 |
| Gigabyte      | GA-880GM-UD2H         | [80ed244689](https://linux-hardware.org/?probe=80ed244689) | Dec 02, 2020 |
| ASUSTek       | PRIME B450M-A         | [c588dc3be6](https://linux-hardware.org/?probe=c588dc3be6) | Nov 27, 2020 |
| Dell          | 0C2KJT A00            | [b27a626476](https://linux-hardware.org/?probe=b27a626476) | Oct 03, 2020 |
| Dell          | 0C2KJT A00            | [c8a79a4b9f](https://linux-hardware.org/?probe=c8a79a4b9f) | Sep 30, 2020 |
| Gigabyte      | GA-MA785GM-US2H       | [585646c033](https://linux-hardware.org/?probe=585646c033) | Feb 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Makulu 2020              | 15       | 48.39%  |
| Makulu 2021              | 4        | 12.9%   |
| Makulu Build: 2021.12.15 | 2        | 6.45%   |
| Makulu Beta1             | 2        | 6.45%   |
| Makulu Testing           | 1        | 3.23%   |
| Makulu Bld-2022.08.19    | 1        | 3.23%   |
| Makulu Bld-2022.08.10    | 1        | 3.23%   |
| Makulu Beta-2            | 1        | 3.23%   |
| Makulu Beta-1            | 1        | 3.23%   |
| Makulu 2022.12.29        | 1        | 3.23%   |
| Makulu 20                | 1        | 3.23%   |
| Makulu 14                | 1        | 3.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Makulu | 31       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.8.0-44-generic       | 4        | 12.5%   |
| 6.3.0-1-amd64          | 2        | 6.25%   |
| 6.0.0-5-amd64          | 2        | 6.25%   |
| 5.4.0-42-generic       | 2        | 6.25%   |
| 5.14.0-2-amd64         | 2        | 6.25%   |
| 5.11.0-41-generic      | 2        | 6.25%   |
| 5.10.0-8-amd64         | 2        | 6.25%   |
| 6.10.9-amd64           | 1        | 3.13%   |
| 5.8.0-59-generic       | 1        | 3.13%   |
| 5.8.0-50-generic       | 1        | 3.13%   |
| 5.8.0-48-generic       | 1        | 3.13%   |
| 5.8.0-41-generic       | 1        | 3.13%   |
| 5.8.0-23-generic       | 1        | 3.13%   |
| 5.4.0-54-generic       | 1        | 3.13%   |
| 5.15.0-56-generic      | 1        | 3.13%   |
| 5.15.0-48-generic      | 1        | 3.13%   |
| 5.15.0-46-generic      | 1        | 3.13%   |
| 5.12.11-051211-generic | 1        | 3.13%   |
| 5.11.0-38-generic      | 1        | 3.13%   |
| 5.11.0-27-generic      | 1        | 3.13%   |
| 5.10.0-7-amd64         | 1        | 3.13%   |
| 5.10.0-3-amd64         | 1        | 3.13%   |
| 4.14.0-041400-generic  | 1        | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.0   | 9        | 28.13%  |
| 5.11.0  | 4        | 12.5%   |
| 5.10.0  | 4        | 12.5%   |
| 5.4.0   | 3        | 9.38%   |
| 5.15.0  | 3        | 9.38%   |
| 6.3.0   | 2        | 6.25%   |
| 6.0.0   | 2        | 6.25%   |
| 5.14.0  | 2        | 6.25%   |
| 6.10.9  | 1        | 3.13%   |
| 5.12.11 | 1        | 3.13%   |
| 4.14.0  | 1        | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 9        | 28.13%  |
| 5.11    | 4        | 12.5%   |
| 5.10    | 4        | 12.5%   |
| 5.4     | 3        | 9.38%   |
| 5.15    | 3        | 9.38%   |
| 6.3     | 2        | 6.25%   |
| 6.0     | 2        | 6.25%   |
| 5.14    | 2        | 6.25%   |
| 6.10    | 1        | 3.13%   |
| 5.12    | 1        | 3.13%   |
| 4.14    | 1        | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 31       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 20       | 64.52%  |
| X-Cinnamon | 8        | 25.81%  |
| KDE5       | 1        | 3.23%   |
| Core       | 1        | 3.23%   |
| Cinnamon   | 1        | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 31       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 74.19%  |
| LightDM | 5        | 16.13%  |
| TDM     | 2        | 6.45%   |
| MDM     | 1        | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 9        | 29.03%  |
| de_DE   | 7        | 22.58%  |
| en_GB   | 4        | 12.9%   |
| en_CA   | 3        | 9.68%   |
| pt_BR   | 2        | 6.45%   |
| en_AU   | 2        | 6.45%   |
| tr_TR   | 1        | 3.23%   |
| eu_ES   | 1        | 3.23%   |
| en_ZA   | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 23       | 74.19%  |
| EFI  | 8        | 25.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 27       | 84.38%  |
| Tmpfs | 4        | 12.5%   |
| Btrfs | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 74.19%  |
| GPT     | 5        | 16.13%  |
| MBR     | 3        | 9.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 90.32%  |
| Yes       | 3        | 9.68%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 87.1%   |
| Yes       | 4        | 12.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 25.81%  |
| MSI                 | 5        | 16.13%  |
| Gigabyte Technology | 5        | 16.13%  |
| ASUSTek Computer    | 4        | 12.9%   |
| ASRock              | 3        | 9.68%   |
| Lenovo              | 1        | 3.23%   |
| Flextronics         | 1        | 3.23%   |
| ELSA                | 1        | 3.23%   |
| Eii                 | 1        | 3.23%   |
| Alienware           | 1        | 3.23%   |
| Acer                | 1        | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell OptiPlex 7010         | 2        | 6.45%   |
| MSI PPPPPPP-CCC#MMMMMMMM   | 1        | 3.23%   |
| MSI MS-7915                | 1        | 3.23%   |
| MSI MS-7817                | 1        | 3.23%   |
| MSI MS-7721                | 1        | 3.23%   |
| MSI MS-7693                | 1        | 3.23%   |
| Lenovo IdeaCentre K430     | 1        | 3.23%   |
| Gigabyte Z390 AORUS ULTRA  | 1        | 3.23%   |
| Gigabyte GA-MA785GM-US2H   | 1        | 3.23%   |
| Gigabyte GA-880GM-UD2H     | 1        | 3.23%   |
| Gigabyte B85M-HD3          | 1        | 3.23%   |
| Gigabyte 990FXA-UD5        | 1        | 3.23%   |
| Flextronics 7238US00       | 1        | 3.23%   |
| ELSA EA H410M-E            | 1        | 3.23%   |
| Eii M1T                    | 1        | 3.23%   |
| Dell XPS420                | 1        | 3.23%   |
| Dell Precision Tower 3620  | 1        | 3.23%   |
| Dell OptiPlex 9020         | 1        | 3.23%   |
| Dell OptiPlex 5070         | 1        | 3.23%   |
| Dell Inspiron 660s         | 1        | 3.23%   |
| Dell Inspiron 580          | 1        | 3.23%   |
| ASUS TUF Gaming B550M-PLUS | 1        | 3.23%   |
| ASUS PRIME B450M-A         | 1        | 3.23%   |
| ASUS P5QC                  | 1        | 3.23%   |
| ASUS M5A97 R2.0            | 1        | 3.23%   |
| ASRock Z790-C              | 1        | 3.23%   |
| ASRock Z77 Pro4            | 1        | 3.23%   |
| ASRock B450 Pro4           | 1        | 3.23%   |
| Alienware Aurora R8        | 1        | 3.23%   |
| Acer Nitro N50-600         | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 4        | 12.9%   |
| Dell Inspiron            | 2        | 6.45%   |
| MSI PPPPPPP-CCC#MMMMMMMM | 1        | 3.23%   |
| MSI MS-7915              | 1        | 3.23%   |
| MSI MS-7817              | 1        | 3.23%   |
| MSI MS-7721              | 1        | 3.23%   |
| MSI MS-7693              | 1        | 3.23%   |
| Lenovo IdeaCentre        | 1        | 3.23%   |
| Gigabyte Z390            | 1        | 3.23%   |
| Gigabyte GA-MA785GM-US2H | 1        | 3.23%   |
| Gigabyte GA-880GM-UD2H   | 1        | 3.23%   |
| Gigabyte B85M-HD3        | 1        | 3.23%   |
| Gigabyte 990FXA-UD5      | 1        | 3.23%   |
| Flextronics 7238US00     | 1        | 3.23%   |
| ELSA EA                  | 1        | 3.23%   |
| Eii M1T                  | 1        | 3.23%   |
| Dell XPS420              | 1        | 3.23%   |
| Dell Precision           | 1        | 3.23%   |
| ASUS TUF                 | 1        | 3.23%   |
| ASUS PRIME               | 1        | 3.23%   |
| ASUS P5QC                | 1        | 3.23%   |
| ASUS M5A97               | 1        | 3.23%   |
| ASRock Z790-C            | 1        | 3.23%   |
| ASRock Z77               | 1        | 3.23%   |
| ASRock B450              | 1        | 3.23%   |
| Alienware Aurora         | 1        | 3.23%   |
| Acer Nitro               | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 6        | 19.35%  |
| 2020 | 5        | 16.13%  |
| 2013 | 5        | 16.13%  |
| 2018 | 4        | 12.9%   |
| 2014 | 2        | 6.45%   |
| 2010 | 2        | 6.45%   |
| 2009 | 2        | 6.45%   |
| 2023 | 1        | 3.23%   |
| 2017 | 1        | 3.23%   |
| 2016 | 1        | 3.23%   |
| 2008 | 1        | 3.23%   |
| 2007 | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 9        | 29.03%  |
| 4.01-8.0   | 7        | 22.58%  |
| 32.01-64.0 | 7        | 22.58%  |
| 3.01-4.0   | 6        | 19.35%  |
| 16.01-24.0 | 2        | 6.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 15       | 44.12%  |
| 1.01-2.0  | 14       | 41.18%  |
| 4.01-8.0  | 2        | 5.88%   |
| 3.01-4.0  | 2        | 5.88%   |
| 8.01-16.0 | 1        | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 48.39%  |
| 2      | 7        | 22.58%  |
| 4      | 5        | 16.13%  |
| 3      | 2        | 6.45%   |
| 8      | 1        | 3.23%   |
| 5      | 1        | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 51.61%  |
| Yes       | 15       | 48.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 96.77%  |
| No        | 1        | 3.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 56.25%  |
| No        | 14       | 43.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 61.29%  |
| Yes       | 12       | 38.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 9        | 29.03%  |
| Germany      | 6        | 19.35%  |
| UK           | 4        | 12.9%   |
| Canada       | 4        | 12.9%   |
| Brazil       | 2        | 6.45%   |
| Australia    | 2        | 6.45%   |
| Turkey       | 1        | 3.23%   |
| Switzerland  | 1        | 3.23%   |
| Spain        | 1        | 3.23%   |
| South Africa | 1        | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| London              | 2        | 6.45%   |
| Zurich              | 1        | 3.23%   |
| Weirton             | 1        | 3.23%   |
| Sydney              | 1        | 3.23%   |
| Stralsund           | 1        | 3.23%   |
| Spanaway            | 1        | 3.23%   |
| Santurtzi           | 1        | 3.23%   |
| Pinhalzinho         | 1        | 3.23%   |
| Palmopolis          | 1        | 3.23%   |
| Oberhausen          | 1        | 3.23%   |
| Mayen               | 1        | 3.23%   |
| Manitouwadge        | 1        | 3.23%   |
| Los Angeles         | 1        | 3.23%   |
| Kitchener           | 1        | 3.23%   |
| Kansas City         | 1        | 3.23%   |
| Izmir               | 1        | 3.23%   |
| Helensburgh         | 1        | 3.23%   |
| Einbeck             | 1        | 3.23%   |
| Edmonton            | 1        | 3.23%   |
| Dollard-des-Ormeaux | 1        | 3.23%   |
| Dallas              | 1        | 3.23%   |
| Daleville           | 1        | 3.23%   |
| Cape Town           | 1        | 3.23%   |
| Berlin              | 1        | 3.23%   |
| Beaverton           | 1        | 3.23%   |
| Bad Schwalbach      | 1        | 3.23%   |
| Arroyo Grande       | 1        | 3.23%   |
| Anniston            | 1        | 3.23%   |
| Adelaide            | 1        | 3.23%   |
| Addlestone          | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 10       | 12     | 16.67%  |
| Samsung Electronics       | 8        | 12     | 13.33%  |
| WDC                       | 7        | 9      | 11.67%  |
| SanDisk                   | 5        | 5      | 8.33%   |
| Unknown                   | 3        | 3      | 5%      |
| Toshiba                   | 3        | 3      | 5%      |
| Kingston                  | 3        | 4      | 5%      |
| Crucial                   | 3        | 3      | 5%      |
| Hitachi                   | 2        | 2      | 3.33%   |
| T-FORCE                   | 1        | 1      | 1.67%   |
| SK hynix                  | 1        | 1      | 1.67%   |
| PNY                       | 1        | 1      | 1.67%   |
| Patriot                   | 1        | 1      | 1.67%   |
| Origin                    | 1        | 1      | 1.67%   |
| ORICO                     | 1        | 1      | 1.67%   |
| Micron/Crucial Technology | 1        | 1      | 1.67%   |
| Micron Technology         | 1        | 1      | 1.67%   |
| Maxtor                    | 1        | 1      | 1.67%   |
| LITEONIT                  | 1        | 1      | 1.67%   |
| Leven                     | 1        | 1      | 1.67%   |
| JMicron Technology        | 1        | 1      | 1.67%   |
| Intenso                   | 1        | 1      | 1.67%   |
| China                     | 1        | 1      | 1.67%   |
| ASMT                      | 1        | 1      | 1.67%   |
| A-DATA Technology         | 1        | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Unknown MMC Card  128GB                              | 2        | 3.23%   |
| SanDisk NVMe SSD Drive 500GB                         | 2        | 3.23%   |
| Kingston SA400S37240G 240GB SSD                      | 2        | 3.23%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 1        | 1.61%   |
| WDC WD5000AADS-00L4B1 500GB                          | 1        | 1.61%   |
| WDC WD40EZRZ-00GXCB0 4TB                             | 1        | 1.61%   |
| WDC WD40EZAZ-00SF3B0 4TB                             | 1        | 1.61%   |
| WDC WD3200AAKS-75L9A0 320GB                          | 1        | 1.61%   |
| WDC WD1600AAJS-22PSA0 160GB                          | 1        | 1.61%   |
| WDC WD10EZEX-00KUWA0 1TB                             | 1        | 1.61%   |
| Unknown Compact Flash 977MB                          | 1        | 1.61%   |
| Toshiba NVMe SSD Drive 512GB                         | 1        | 1.61%   |
| Toshiba HDWD130 3TB                                  | 1        | 1.61%   |
| Toshiba DT01ACA050 500GB                             | 1        | 1.61%   |
| T-FORCE 1TB                                          | 1        | 1.61%   |
| SK hynix NVMe SSD Drive 512GB                        | 1        | 1.61%   |
| Seagate ST9500325AS 500GB                            | 1        | 1.61%   |
| Seagate ST940210AS 40GB                              | 1        | 1.61%   |
| Seagate ST500DM002-1BD142 500GB                      | 1        | 1.61%   |
| Seagate ST3500418AS 500GB                            | 1        | 1.61%   |
| Seagate ST3320820AS 320GB                            | 1        | 1.61%   |
| Seagate ST3320620AS 320GB                            | 1        | 1.61%   |
| Seagate ST31000524AS 1TB                             | 1        | 1.61%   |
| Seagate ST250DM000-1BD141 250GB                      | 1        | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB                       | 1        | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 1        | 1.61%   |
| Seagate BarraCuda 120 SSD ZA500CM10003 500GB         | 1        | 1.61%   |
| SanDisk SSD PLUS 480GB                               | 1        | 1.61%   |
| SanDisk SSD PLUS 1000GB                              | 1        | 1.61%   |
| SanDisk SDSSDH3 512G                                 | 1        | 1.61%   |
| Samsung SSD 870 QVO 2TB                              | 1        | 1.61%   |
| Samsung SSD 860 EVO mSATA 500GB                      | 1        | 1.61%   |
| Samsung SSD 850 EVO 500GB                            | 1        | 1.61%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB               | 1        | 1.61%   |
| Samsung NVMe SSD Drive 1TB                           | 1        | 1.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 1        | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 1        | 1.61%   |
| Samsung MZVLB256HAHQ-000L7 256GB                     | 1        | 1.61%   |
| Samsung MZMPC064HBDR-000L1 64GB SSD                  | 1        | 1.61%   |
| PNY CS900 500GB SSD                                  | 1        | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 9        | 11     | 42.86%  |
| WDC                | 6        | 8      | 28.57%  |
| Toshiba            | 2        | 2      | 9.52%   |
| Hitachi            | 2        | 2      | 9.52%   |
| Maxtor             | 1        | 1      | 4.76%   |
| JMicron Technology | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 16%     |
| SanDisk             | 3        | 3      | 12%     |
| Kingston            | 3        | 4      | 12%     |
| Crucial             | 3        | 3      | 12%     |
| WDC                 | 1        | 1      | 4%      |
| Seagate             | 1        | 1      | 4%      |
| PNY                 | 1        | 1      | 4%      |
| Patriot             | 1        | 1      | 4%      |
| Origin              | 1        | 1      | 4%      |
| Micron Technology   | 1        | 1      | 4%      |
| LITEONIT            | 1        | 1      | 4%      |
| Leven               | 1        | 1      | 4%      |
| Intenso             | 1        | 1      | 4%      |
| China               | 1        | 1      | 4%      |
| ASMT                | 1        | 1      | 4%      |
| A-DATA Technology   | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 19       | 27     | 40.43%  |
| HDD     | 16       | 25     | 34.04%  |
| NVMe    | 7        | 12     | 14.89%  |
| Unknown | 3        | 3      | 6.38%   |
| MMC     | 2        | 2      | 4.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 50     | 67.44%  |
| NVMe | 7        | 12     | 16.28%  |
| SAS  | 5        | 5      | 11.63%  |
| MMC  | 2        | 2      | 4.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 34     | 57.89%  |
| 0.51-1.0   | 11       | 13     | 28.95%  |
| 3.01-4.0   | 2        | 2      | 5.26%   |
| 1.01-2.0   | 2        | 2      | 5.26%   |
| 2.01-3.0   | 1        | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 32.26%  |
| 501-1000       | 8        | 25.81%  |
| 251-500        | 6        | 19.35%  |
| More than 3000 | 3        | 9.68%   |
| 51-100         | 2        | 6.45%   |
| 21-50          | 1        | 3.23%   |
| 1001-2000      | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 14       | 42.42%  |
| 21-50          | 7        | 21.21%  |
| 251-500        | 5        | 15.15%  |
| 51-100         | 3        | 9.09%   |
| More than 3000 | 2        | 6.06%   |
| 2001-3000      | 1        | 3.03%   |
| 101-250        | 1        | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD3200AAKS-75L9A0 320GB | 1        | 2      | 50%     |
| Seagate ST31000524AS 1TB    | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 100%    |

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
| Detected | 29       | 60     | 85.29%  |
| Works    | 3        | 6      | 8.82%   |
| Malfunc  | 2        | 3      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 21       | 44.68%  |
| AMD                          | 10       | 21.28%  |
| Samsung Electronics          | 5        | 10.64%  |
| ASMedia Technology           | 4        | 8.51%   |
| SanDisk                      | 2        | 4.26%   |
| Marvell Technology Group     | 2        | 4.26%   |
| Toshiba America Info Systems | 1        | 2.13%   |
| SK hynix                     | 1        | 2.13%   |
| Micron/Crucial Technology    | 1        | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 7.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 7.41%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 5.56%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3        | 5.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 5.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 5.56%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 5.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 3.7%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 1.85%   |
| SK hynix PC400 NVMe SSD                                                        | 1        | 1.85%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 1        | 1.85%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                      | 1        | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 1.85%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.85%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 1.85%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 1        | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family IDE-r Controller                     | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.85%   |
| ASMedia ASM1061 Serial ATA Controller                                          | 1        | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 24       | 55.81%  |
| IDE  | 9        | 20.93%  |
| NVMe | 7        | 16.28%  |
| RAID | 3        | 6.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 21       | 67.74%  |
| AMD    | 10       | 32.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 6.45%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 6.45%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 3.23%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 3.23%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 3.23%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 3.23%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 3.23%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 3.23%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 3.23%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 3.23%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 3.23%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 3.23%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 3.23%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 3.23%   |
| Intel Core i3-9100T CPU @ 3.10GHz           | 1        | 3.23%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 3.23%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 3.23%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1        | 3.23%   |
| Intel 13th Gen Core i9-13900KF              | 1        | 3.23%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 3.23%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 3.23%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 3.23%   |
| AMD R-464L APU with Radeon HD Graphics      | 1        | 3.23%   |
| AMD Phenom II X4 955 Processor              | 1        | 3.23%   |
| AMD Phenom 9750 Quad-Core Processor         | 1        | 3.23%   |
| AMD FX-9590 Eight-Core Processor            | 1        | 3.23%   |
| AMD FX-8370 Eight-Core Processor            | 1        | 3.23%   |
| AMD FX-4300 Quad-Core Processor             | 1        | 3.23%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 6        | 19.35%  |
| Intel Core i5           | 5        | 16.13%  |
| Intel Core i3           | 3        | 9.68%   |
| AMD FX                  | 3        | 9.68%   |
| Other                   | 2        | 6.45%   |
| Intel Pentium           | 2        | 6.45%   |
| Intel Core 2 Quad       | 2        | 6.45%   |
| Intel Pentium Dual-Core | 1        | 3.23%   |
| Intel Celeron           | 1        | 3.23%   |
| AMD Ryzen 7             | 1        | 3.23%   |
| AMD Ryzen 5             | 1        | 3.23%   |
| AMD Ryzen 3             | 1        | 3.23%   |
| AMD Phenom II X4        | 1        | 3.23%   |
| AMD Phenom              | 1        | 3.23%   |
| AMD A8                  | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 17       | 54.84%  |
| 2      | 8        | 25.81%  |
| 6      | 3        | 9.68%   |
| 8      | 2        | 6.45%   |
| 24     | 1        | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 51.61%  |
| 2      | 15       | 48.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 31       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 38.71%  |
| 0x306a9    | 4        | 12.9%   |
| 0x08108109 | 2        | 6.45%   |
| 0x06001119 | 2        | 6.45%   |
| 0x06000852 | 2        | 6.45%   |
| 0x906ed    | 1        | 3.23%   |
| 0x706a1    | 1        | 3.23%   |
| 0x6fb      | 1        | 3.23%   |
| 0x506e3    | 1        | 3.23%   |
| 0x306c3    | 1        | 3.23%   |
| 0x20655    | 1        | 3.23%   |
| 0x08701021 | 1        | 3.23%   |
| 0x010000c9 | 1        | 3.23%   |
| 0x010000c8 | 1        | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Piledriver    | 5        | 16.13%  |
| IvyBridge     | 5        | 16.13%  |
| KabyLake      | 4        | 12.9%   |
| Haswell       | 4        | 12.9%   |
| Zen+          | 2        | 6.45%   |
| K10           | 2        | 6.45%   |
| Core          | 2        | 6.45%   |
| Zen 2         | 1        | 3.23%   |
| Westmere      | 1        | 3.23%   |
| Skylake       | 1        | 3.23%   |
| Penryn        | 1        | 3.23%   |
| Goldmont plus | 1        | 3.23%   |
| CometLake     | 1        | 3.23%   |
| Unknown       | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 15       | 39.47%  |
| Intel  | 13       | 34.21%  |
| AMD    | 10       | 26.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 7.89%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.26%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 5.26%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 5.26%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 2.63%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 2.63%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 2.63%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 2.63%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 2.63%   |
| Nvidia GK107GL [Quadro K2000D]                                              | 1        | 2.63%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 2.63%   |
| Nvidia GK107 [GeForce GT 630 OEM]                                           | 1        | 2.63%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 2.63%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 2.63%   |
| Nvidia AD103 [GeForce RTX 4080]                                             | 1        | 2.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.63%   |
| Intel HD Graphics 530                                                       | 1        | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.63%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.63%   |
| AMD Trinity [Radeon HD 7660G]                                               | 1        | 2.63%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 2.63%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 2.63%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 2.63%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 1        | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 2.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 14       | 42.42%  |
| 1 x AMD        | 10       | 30.3%   |
| 1 x Intel      | 8        | 24.24%  |
| Intel + Nvidia | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 25       | 80.65%  |
| Proprietary | 6        | 19.35%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 50%     |
| 1.01-2.0   | 9        | 28.13%  |
| 0.51-1.0   | 2        | 6.25%   |
| 0.01-0.5   | 2        | 6.25%   |
| 7.01-8.0   | 1        | 3.13%   |
| 5.01-6.0   | 1        | 3.13%   |
| 3.01-4.0   | 1        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 5        | 16.13%  |
| Hewlett-Packard     | 4        | 12.9%   |
| Dell                | 3        | 9.68%   |
| Acer                | 3        | 9.68%   |
| Samsung Electronics | 2        | 6.45%   |
| BenQ                | 2        | 6.45%   |
| AOC                 | 2        | 6.45%   |
| Toshiba             | 1        | 3.23%   |
| Sony                | 1        | 3.23%   |
| Ruijiang            | 1        | 3.23%   |
| Panasonic           | 1        | 3.23%   |
| LG Electronics      | 1        | 3.23%   |
| HannStar            | 1        | 3.23%   |
| Gateway             | 1        | 3.23%   |
| Element             | 1        | 3.23%   |
| AUS                 | 1        | 3.23%   |
| ASUSTek Computer    | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Toshiba LCD Monitor TV 1920x1080                                  | 1        | 3.13%   |
| Sony TV SNYDC01 1360x768                                          | 1        | 3.13%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch | 1        | 3.13%   |
| Samsung Electronics LCD Monitor SMS27A850T 2560x1440              | 1        | 3.13%   |
| Ruijiang RJT HDMI RJT1200 1920x1080 320x180mm 14.5-inch           | 1        | 3.13%   |
| Panasonic TV MEIC135 1920x1080 698x392mm 31.5-inch                | 1        | 3.13%   |
| LG Electronics LCD Monitor LG IPS FULLHD                          | 1        | 3.13%   |
| LG Electronics LCD Monitor LG HDR 4K 7360x2160                    | 1        | 3.13%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                       | 1        | 3.13%   |
| Hewlett-Packard LCD Monitor 2310 1920x1080                        | 1        | 3.13%   |
| Hewlett-Packard LCD Monitor 2009                                  | 1        | 3.13%   |
| Hewlett-Packard 24m HPN3577 1920x1080 527x297mm 23.8-inch         | 1        | 3.13%   |
| HannStar Hanns.G HH241 HSD2275 1920x1080 521x293mm 23.5-inch      | 1        | 3.13%   |
| Goldstar W2343 GSM5700 1920x1080 474x296mm 22.0-inch              | 1        | 3.13%   |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch              | 1        | 3.13%   |
| Goldstar TV SSCR2 GSM8080 3840x2160                               | 1        | 3.13%   |
| Goldstar FHD GSM5BCA 1920x1080 480x270mm 21.7-inch                | 1        | 3.13%   |
| Goldstar E2050 GSM4EAD 1600x900 450x250mm 20.3-inch               | 1        | 3.13%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch             | 1        | 3.13%   |
| Element ELSW3917BF ELE6308 1366x768 1365x768mm 61.7-inch          | 1        | 3.13%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                 | 1        | 3.13%   |
| Dell P2217H DELA0D7 1920x1080 476x267mm 21.5-inch                 | 1        | 3.13%   |
| Dell LCD Monitor E228WFP                                          | 1        | 3.13%   |
| BenQ M2700HD BNQ7C06 1920x1080 600x340mm 27.2-inch                | 1        | 3.13%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                | 1        | 3.13%   |
| AUS LCD Monitor VA32AQ 2560x1440                                  | 1        | 3.13%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch      | 1        | 3.13%   |
| AOC L19W931 AOC1993 1360x768 410x256mm 19.0-inch                  | 1        | 3.13%   |
| AOC 2243W AOC2243 1920x1080 477x268mm 21.5-inch                   | 1        | 3.13%   |
| Acer XB281HK ACR0460 3840x2160 621x341mm 27.9-inch                | 1        | 3.13%   |
| Acer K243Y ACR08B7 1920x1080 527x296mm 23.8-inch                  | 1        | 3.13%   |
| Acer G226HQL ACR02EA 1920x1080 509x286mm 23.0-inch                | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 15       | 53.57%  |
| 3840x2160 (4K)  | 4        | 14.29%  |
| 2560x1440 (QHD) | 2        | 7.14%   |
| 1360x768        | 2        | 7.14%   |
| Unknown         | 2        | 7.14%   |
| 7360x2160       | 1        | 3.57%   |
| 3120x1050       | 1        | 3.57%   |
| 1600x900 (HD+)  | 1        | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 6        | 22.22%  |
| Unknown | 6        | 22.22%  |
| 27      | 3        | 11.11%  |
| 21      | 3        | 11.11%  |
| 72      | 2        | 7.41%   |
| 31      | 2        | 7.41%   |
| 86      | 1        | 3.7%    |
| 61      | 1        | 3.7%    |
| 24      | 1        | 3.7%    |
| 20      | 1        | 3.7%    |
| 19      | 1        | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 29.63%  |
| Unknown     | 6        | 22.22%  |
| 401-500     | 5        | 18.52%  |
| 601-700     | 4        | 14.81%  |
| 1501-2000   | 3        | 11.11%  |
| 1001-1500   | 1        | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 72%     |
| Unknown | 6        | 24%     |
| 16/10   | 1        | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 29.63%  |
| Unknown        | 6        | 22.22%  |
| More than 1000 | 4        | 14.81%  |
| 151-200        | 4        | 14.81%  |
| 301-350        | 3        | 11.11%  |
| 351-500        | 2        | 7.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 44.44%  |
| Unknown | 6        | 22.22%  |
| 1-50    | 3        | 11.11%  |
| 121-160 | 3        | 11.11%  |
| 101-120 | 3        | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 87.1%   |
| 3     | 3        | 9.68%   |
| 2     | 1        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 17       | 38.64%  |
| Intel                           | 13       | 29.55%  |
| Qualcomm Atheros                | 5        | 11.36%  |
| Broadcom                        | 2        | 4.55%   |
| TP-Link                         | 1        | 2.27%   |
| Ralink                          | 1        | 2.27%   |
| Qualcomm Atheros Communications | 1        | 2.27%   |
| MediaTek                        | 1        | 2.27%   |
| Edimax Technology               | 1        | 2.27%   |
| D-Link System                   | 1        | 2.27%   |
| AVM                             | 1        | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14       | 28.57%  |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 4.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 4.08%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 2.04%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 2.04%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 2.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 2.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 2.04%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 2.04%   |
| MediaTek WiFi                                                          | 1        | 2.04%   |
| Intel Wireless 7265                                                    | 1        | 2.04%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 2.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 2.04%   |
| Intel Ethernet Controller I219-V                                       | 1        | 2.04%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 2.04%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 2.04%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 2.04%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]               | 1        | 2.04%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 2.04%   |
| Broadcom Network controller                                            | 1        | 2.04%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1        | 2.04%   |
| AVM FRITZ!WLAN AC 860                                                  | 1        | 2.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 31.58%  |
| Qualcomm Atheros                | 3        | 15.79%  |
| Realtek Semiconductor           | 2        | 10.53%  |
| TP-Link                         | 1        | 5.26%   |
| Ralink                          | 1        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 5.26%   |
| MediaTek                        | 1        | 5.26%   |
| Edimax Technology               | 1        | 5.26%   |
| D-Link System                   | 1        | 5.26%   |
| Broadcom                        | 1        | 5.26%   |
| AVM                             | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 10.53%  |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 5.26%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 5.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 5.26%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 5.26%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 5.26%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 5.26%   |
| MediaTek WiFi                                                          | 1        | 5.26%   |
| Intel Wireless 7265                                                    | 1        | 5.26%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 5.26%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 5.26%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]               | 1        | 5.26%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 5.26%   |
| Broadcom Network controller                                            | 1        | 5.26%   |
| AVM FRITZ!WLAN AC 860                                                  | 1        | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 56.67%  |
| Intel                 | 9        | 30%     |
| Qualcomm Atheros      | 3        | 10%     |
| Broadcom              | 1        | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14       | 46.67%  |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 3.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 3.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 3.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 3.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 3.33%   |
| Intel Ethernet Controller I219-V                                       | 1        | 3.33%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 3.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 3.33%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 3.33%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 3.33%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1        | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 62.5%   |
| WiFi     | 18       | 37.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 69.7%   |
| WiFi     | 10       | 30.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 64.52%  |
| 2     | 11       | 35.48%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 74.19%  |
| Yes  | 8        | 25.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 46.15%  |
| Realtek Semiconductor           | 1        | 7.69%   |
| Qualcomm Atheros Communications | 1        | 7.69%   |
| Dell                            | 1        | 7.69%   |
| Cambridge Silicon Radio         | 1        | 7.69%   |
| Broadcom                        | 1        | 7.69%   |
| ASUSTek Computer                | 1        | 7.69%   |
| Actions                         | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 15.38%  |
| Realtek Bluetooth Radio                             | 1        | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| Intel AX200 Bluetooth                               | 1        | 7.69%   |
| Dell BT Mini-Receiver                               | 1        | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 7.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.69%   |
| Actions general adapter                             | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 21       | 38.89%  |
| Nvidia              | 15       | 27.78%  |
| AMD                 | 15       | 27.78%  |
| ROCCAT              | 1        | 1.85%   |
| Creative Labs       | 1        | 1.85%   |
| C-Media Electronics | 1        | 1.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 5        | 8.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 5        | 8.33%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 3        | 5%      |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 3        | 5%      |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 2        | 3.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                | 2        | 3.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2        | 3.33%   |
| AMD FCH Azalia Controller                                                                       | 2        | 3.33%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                      | 2        | 3.33%   |
| ROCCAT Elo 7.1 USB                                                                              | 1        | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1        | 1.67%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.67%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1        | 1.67%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 1.67%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1        | 1.67%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 1        | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 1        | 1.67%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 1        | 1.67%   |
| Nvidia GF116 High Definition Audio Controller                                                   | 1        | 1.67%   |
| Nvidia Audio device                                                                             | 1        | 1.67%   |
| Intel Raptor Lake High Definition Audio Controller                                              | 1        | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 1        | 1.67%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 1        | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                    | 1        | 1.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 1        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 1        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 1        | 1.67%   |
| Intel 200 Series PCH HD Audio                                                                   | 1        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 1        | 1.67%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.67%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                   | 1        | 1.67%   |
| AMD Trinity HDMI Audio Controller                                                               | 1        | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 1        | 1.67%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                    | 1        | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 1        | 1.67%   |
| AMD Navi 10 HDMI Audio                                                                          | 1        | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 1        | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 1        | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| SK hynix                     | 2        | 28.57%  |
| Unknown                      | 1        | 14.29%  |
| Team                         | 1        | 14.29%  |
| Smart                        | 1        | 14.29%  |
| Patriot Memory (PDP Systems) | 1        | 14.29%  |
| Kingston                     | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 1066MT/s                                  | 1        | 14.29%  |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s                      | 1        | 14.29%  |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s                      | 1        | 14.29%  |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s                     | 1        | 14.29%  |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 1        | 14.29%  |
| Patriot Memory (PDP Systems) RAM 5600 C36 Series 16GB DIMM DDR5 5600MT/s | 1        | 14.29%  |
| Kingston RAM K531R8-HYA 4GB DIMM DDR3 1600MT/s                           | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 3        | 50%     |
| DDR5    | 1        | 16.67%  |
| DDR4    | 1        | 16.67%  |
| Unknown | 1        | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 6        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 2        | 33.33%  |
| 2048  | 2        | 33.33%  |
| 32768 | 1        | 16.67%  |
| 16384 | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1800  | 2        | 28.57%  |
| 5600  | 1        | 14.29%  |
| 3600  | 1        | 14.29%  |
| 1600  | 1        | 14.29%  |
| 1333  | 1        | 14.29%  |
| 1066  | 1        | 14.29%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon PIXMA MX920 Series | 1        | 100%    |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Sonix Technology | 1        | 25%     |
| Microsoft        | 1        | 25%     |
| Microdia         | 1        | 25%     |
| Logitech         | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Sonix USB 2.0 Camera       | 1        | 25%     |
| Microsoft LifeCam VX-2000  | 1        | 25%     |
| Microdia Integrated Camera | 1        | 25%     |
| Logitech Webcam B500       | 1        | 25%     |

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
| 0     | 29       | 93.55%  |
| 1     | 2        | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Network      | 1        | 50%     |
| Net/wireless | 1        | 50%     |

