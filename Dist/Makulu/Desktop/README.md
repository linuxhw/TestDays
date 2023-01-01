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

Total: 36

| Vendor        | Model                 | Probe                                                      | Date         |
|---------------|-----------------------|------------------------------------------------------------|--------------|
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
| Makulu 2020              | 15       | 60%     |
| Makulu 2021              | 4        | 16%     |
| Makulu Build: 2021.12.15 | 2        | 8%      |
| Makulu Bld-2022.08.19    | 1        | 4%      |
| Makulu Bld-2022.08.10    | 1        | 4%      |
| Makulu 20                | 1        | 4%      |
| Makulu 14                | 1        | 4%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Makulu | 25       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.8.0-44-generic       | 4        | 15.38%  |
| 5.4.0-42-generic       | 2        | 7.69%   |
| 5.14.0-2-amd64         | 2        | 7.69%   |
| 5.11.0-41-generic      | 2        | 7.69%   |
| 5.10.0-8-amd64         | 2        | 7.69%   |
| 5.8.0-59-generic       | 1        | 3.85%   |
| 5.8.0-50-generic       | 1        | 3.85%   |
| 5.8.0-48-generic       | 1        | 3.85%   |
| 5.8.0-41-generic       | 1        | 3.85%   |
| 5.8.0-23-generic       | 1        | 3.85%   |
| 5.4.0-54-generic       | 1        | 3.85%   |
| 5.15.0-48-generic      | 1        | 3.85%   |
| 5.15.0-46-generic      | 1        | 3.85%   |
| 5.12.11-051211-generic | 1        | 3.85%   |
| 5.11.0-38-generic      | 1        | 3.85%   |
| 5.11.0-27-generic      | 1        | 3.85%   |
| 5.10.0-7-amd64         | 1        | 3.85%   |
| 5.10.0-3-amd64         | 1        | 3.85%   |
| 4.14.0-041400-generic  | 1        | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.0   | 9        | 34.62%  |
| 5.11.0  | 4        | 15.38%  |
| 5.10.0  | 4        | 15.38%  |
| 5.4.0   | 3        | 11.54%  |
| 5.15.0  | 2        | 7.69%   |
| 5.14.0  | 2        | 7.69%   |
| 5.12.11 | 1        | 3.85%   |
| 4.14.0  | 1        | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 9        | 34.62%  |
| 5.11    | 4        | 15.38%  |
| 5.10    | 4        | 15.38%  |
| 5.4     | 3        | 11.54%  |
| 5.15    | 2        | 7.69%   |
| 5.14    | 2        | 7.69%   |
| 5.12    | 1        | 3.85%   |
| 4.14    | 1        | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 16       | 64%     |
| X-Cinnamon | 7        | 28%     |
| Core       | 1        | 4%      |
| Cinnamon   | 1        | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 25       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 84%     |
| TDM     | 2        | 8%      |
| MDM     | 1        | 4%      |
| LightDM | 1        | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 7        | 28%     |
| de_DE   | 6        | 24%     |
| en_GB   | 3        | 12%     |
| en_CA   | 3        | 12%     |
| pt_BR   | 2        | 8%      |
| en_AU   | 2        | 8%      |
| tr_TR   | 1        | 4%      |
| Unknown | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 72%     |
| EFI  | 7        | 28%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 25       | 96.15%  |
| Btrfs | 1        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 84%     |
| MBR     | 2        | 8%      |
| GPT     | 2        | 8%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 92%     |
| Yes       | 2        | 8%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 92%     |
| Yes       | 2        | 8%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 24%     |
| Gigabyte Technology | 5        | 20%     |
| ASUSTek Computer    | 4        | 16%     |
| MSI                 | 3        | 12%     |
| ASRock              | 2        | 8%      |
| Lenovo              | 1        | 4%      |
| Flextronics         | 1        | 4%      |
| ELSA                | 1        | 4%      |
| Alienware           | 1        | 4%      |
| Acer                | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| MSI PPPPPPP-CCC#MMMMMMMM   | 1        | 4%      |
| MSI MS-7721                | 1        | 4%      |
| MSI MS-7693                | 1        | 4%      |
| Lenovo IdeaCentre K430     | 1        | 4%      |
| Gigabyte Z390 AORUS ULTRA  | 1        | 4%      |
| Gigabyte GA-MA785GM-US2H   | 1        | 4%      |
| Gigabyte GA-880GM-UD2H     | 1        | 4%      |
| Gigabyte B85M-HD3          | 1        | 4%      |
| Gigabyte 990FXA-UD5        | 1        | 4%      |
| Flextronics 7238US00       | 1        | 4%      |
| ELSA EA H410M-E            | 1        | 4%      |
| Dell XPS420                | 1        | 4%      |
| Dell Precision Tower 3620  | 1        | 4%      |
| Dell OptiPlex 9020         | 1        | 4%      |
| Dell OptiPlex 7010         | 1        | 4%      |
| Dell Inspiron 660s         | 1        | 4%      |
| Dell Inspiron 580          | 1        | 4%      |
| ASUS TUF Gaming B550M-PLUS | 1        | 4%      |
| ASUS PRIME B450M-A         | 1        | 4%      |
| ASUS P5QC                  | 1        | 4%      |
| ASUS M5A97 R2.0            | 1        | 4%      |
| ASRock Z77 Pro4            | 1        | 4%      |
| ASRock B450 Pro4           | 1        | 4%      |
| Alienware Aurora R8        | 1        | 4%      |
| Acer Nitro N50-600         | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 2        | 8%      |
| Dell Inspiron            | 2        | 8%      |
| MSI PPPPPPP-CCC#MMMMMMMM | 1        | 4%      |
| MSI MS-7721              | 1        | 4%      |
| MSI MS-7693              | 1        | 4%      |
| Lenovo IdeaCentre        | 1        | 4%      |
| Gigabyte Z390            | 1        | 4%      |
| Gigabyte GA-MA785GM-US2H | 1        | 4%      |
| Gigabyte GA-880GM-UD2H   | 1        | 4%      |
| Gigabyte B85M-HD3        | 1        | 4%      |
| Gigabyte 990FXA-UD5      | 1        | 4%      |
| Flextronics 7238US00     | 1        | 4%      |
| ELSA EA                  | 1        | 4%      |
| Dell XPS420              | 1        | 4%      |
| Dell Precision           | 1        | 4%      |
| ASUS TUF                 | 1        | 4%      |
| ASUS PRIME               | 1        | 4%      |
| ASUS P5QC                | 1        | 4%      |
| ASUS M5A97               | 1        | 4%      |
| ASRock Z77               | 1        | 4%      |
| ASRock B450              | 1        | 4%      |
| Alienware Aurora         | 1        | 4%      |
| Acer Nitro               | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 5        | 20%     |
| 2018 | 4        | 16%     |
| 2013 | 4        | 16%     |
| 2020 | 3        | 12%     |
| 2014 | 2        | 8%      |
| 2010 | 2        | 8%      |
| 2009 | 2        | 8%      |
| 2017 | 1        | 4%      |
| 2008 | 1        | 4%      |
| 2007 | 1        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 25       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 25       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 32.01-64.0 | 6        | 24%     |
| 3.01-4.0   | 6        | 24%     |
| 8.01-16.0  | 6        | 24%     |
| 4.01-8.0   | 5        | 20%     |
| 16.01-24.0 | 2        | 8%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 14       | 50%     |
| 1.01-2.0 | 12       | 42.86%  |
| 4.01-8.0 | 1        | 3.57%   |
| 3.01-4.0 | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 52%     |
| 2      | 5        | 20%     |
| 4      | 4        | 16%     |
| 3      | 2        | 8%      |
| 5      | 1        | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 60%     |
| No        | 10       | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 50%     |
| No        | 13       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 68%     |
| Yes       | 8        | 32%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 28%     |
| Germany     | 5        | 20%     |
| Canada      | 4        | 16%     |
| UK          | 3        | 12%     |
| Brazil      | 2        | 8%      |
| Australia   | 2        | 8%      |
| Turkey      | 1        | 4%      |
| Switzerland | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Zurich              | 1        | 4%      |
| Weirton             | 1        | 4%      |
| Sydney              | 1        | 4%      |
| Spanaway            | 1        | 4%      |
| Pinhalzinho         | 1        | 4%      |
| Palmopolis          | 1        | 4%      |
| Oberhausen          | 1        | 4%      |
| Mayen               | 1        | 4%      |
| Manitouwadge        | 1        | 4%      |
| Los Angeles         | 1        | 4%      |
| London              | 1        | 4%      |
| Kitchener           | 1        | 4%      |
| Izmir               | 1        | 4%      |
| Helensburgh         | 1        | 4%      |
| Heidenrod           | 1        | 4%      |
| Einbeck             | 1        | 4%      |
| Edmonton            | 1        | 4%      |
| Dollard-des-Ormeaux | 1        | 4%      |
| Dallas              | 1        | 4%      |
| Berlin              | 1        | 4%      |
| Beaverton           | 1        | 4%      |
| Arroyo Grande       | 1        | 4%      |
| Anniston            | 1        | 4%      |
| Adelaide            | 1        | 4%      |
| Addlestone          | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 9        | 11     | 20.45%  |
| WDC                       | 5        | 7      | 11.36%  |
| Samsung Electronics       | 5        | 6      | 11.36%  |
| SanDisk                   | 4        | 4      | 9.09%   |
| Kingston                  | 3        | 4      | 6.82%   |
| Toshiba                   | 2        | 2      | 4.55%   |
| Hitachi                   | 2        | 2      | 4.55%   |
| Unknown                   | 1        | 1      | 2.27%   |
| T-FORCE                   | 1        | 1      | 2.27%   |
| SK hynix                  | 1        | 1      | 2.27%   |
| Origin                    | 1        | 1      | 2.27%   |
| Micron/Crucial Technology | 1        | 1      | 2.27%   |
| Micron Technology         | 1        | 1      | 2.27%   |
| Maxtor                    | 1        | 1      | 2.27%   |
| LITEONIT                  | 1        | 1      | 2.27%   |
| Leven                     | 1        | 1      | 2.27%   |
| JMicron Technology        | 1        | 1      | 2.27%   |
| Crucial                   | 1        | 1      | 2.27%   |
| China                     | 1        | 1      | 2.27%   |
| ASMT                      | 1        | 1      | 2.27%   |
| A-DATA Technology         | 1        | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| SanDisk NVMe SSD Drive 500GB                 | 2        | 4.35%   |
| Kingston SA400S37240G 240GB SSD              | 2        | 4.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1        | 2.17%   |
| WDC WD5000AADS-00L4B1 500GB                  | 1        | 2.17%   |
| WDC WD3200AAKS-75L9A0 320GB                  | 1        | 2.17%   |
| WDC WD1600AAJS-22PSA0 160GB                  | 1        | 2.17%   |
| WDC WD10EZEX-00KUWA0 1TB                     | 1        | 2.17%   |
| Unknown MMC Card  128GB                      | 1        | 2.17%   |
| Toshiba NVMe SSD Drive 512GB                 | 1        | 2.17%   |
| Toshiba DT01ACA050 500GB                     | 1        | 2.17%   |
| T-FORCE 1TB                                  | 1        | 2.17%   |
| SK hynix NVMe SSD Drive 512GB                | 1        | 2.17%   |
| Seagate ST940210AS 40GB                      | 1        | 2.17%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 2.17%   |
| Seagate ST3500418AS 500GB                    | 1        | 2.17%   |
| Seagate ST3320820AS 320GB                    | 1        | 2.17%   |
| Seagate ST3320620AS 320GB                    | 1        | 2.17%   |
| Seagate ST31000524AS 1TB                     | 1        | 2.17%   |
| Seagate ST250DM000-1BD141 250GB              | 1        | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB               | 1        | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1        | 2.17%   |
| Seagate BarraCuda 120 SSD ZA500CM10003 500GB | 1        | 2.17%   |
| SanDisk SSD PLUS 480GB                       | 1        | 2.17%   |
| SanDisk SSD PLUS 1000GB                      | 1        | 2.17%   |
| Samsung SSD 870 QVO 2TB                      | 1        | 2.17%   |
| Samsung SSD 860 EVO mSATA 500GB              | 1        | 2.17%   |
| Samsung NVMe SSD Drive 250GB                 | 1        | 2.17%   |
| Samsung NVMe SSD Drive 1TB                   | 1        | 2.17%   |
| Samsung MZVLB256HAHQ-000L7 256GB             | 1        | 2.17%   |
| Samsung MZMPC064HBDR-000L1 64GB SSD          | 1        | 2.17%   |
| Origin Inception TLC830 SSD 256GB            | 1        | 2.17%   |
| Micron/Crucial NVMe SSD Drive 500GB          | 1        | 2.17%   |
| Micron Crucial X6 SSD 500GB                  | 1        | 2.17%   |
| Maxtor 7L250S0 256GB                         | 1        | 2.17%   |
| LITEONIT LMT-512L9M-11 MSATA 512GB SSD       | 1        | 2.17%   |
| Leven JAJS600M512C 512GB SSD                 | 1        | 2.17%   |
| Kingston SV300S37A120G 120GB SSD             | 1        | 2.17%   |
| JMicron Generic 240GB SSD                    | 1        | 2.17%   |
| Hitachi HDS728080PLA380 82GB                 | 1        | 2.17%   |
| Hitachi HDS721010CLA332 1TB                  | 1        | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 8        | 10     | 47.06%  |
| WDC     | 4        | 6      | 23.53%  |
| Hitachi | 2        | 2      | 11.76%  |
| Toshiba | 1        | 1      | 5.88%   |
| Maxtor  | 1        | 1      | 5.88%   |
| ASMT    | 1        | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 16.67%  |
| Kingston            | 3        | 4      | 16.67%  |
| SanDisk             | 2        | 2      | 11.11%  |
| WDC                 | 1        | 1      | 5.56%   |
| Seagate             | 1        | 1      | 5.56%   |
| Origin              | 1        | 1      | 5.56%   |
| Micron Technology   | 1        | 1      | 5.56%   |
| LITEONIT            | 1        | 1      | 5.56%   |
| Leven               | 1        | 1      | 5.56%   |
| JMicron Technology  | 1        | 1      | 5.56%   |
| Crucial             | 1        | 1      | 5.56%   |
| China               | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 15       | 19     | 41.67%  |
| HDD     | 14       | 21     | 38.89%  |
| NVMe    | 5        | 8      | 13.89%  |
| MMC     | 1        | 1      | 2.78%   |
| Unknown | 1        | 1      | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 38     | 72.73%  |
| NVMe | 5        | 8      | 15.15%  |
| SAS  | 3        | 3      | 9.09%   |
| MMC  | 1        | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 28     | 65.52%  |
| 0.51-1.0   | 9        | 11     | 31.03%  |
| 1.01-2.0   | 1        | 1      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 9        | 36%     |
| 501-1000       | 8        | 32%     |
| 251-500        | 3        | 12%     |
| 51-100         | 2        | 8%      |
| More than 3000 | 1        | 4%      |
| 21-50          | 1        | 4%      |
| 1001-2000      | 1        | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 13       | 48.15%  |
| 251-500        | 5        | 18.52%  |
| 21-50          | 5        | 18.52%  |
| 51-100         | 3        | 11.11%  |
| More than 3000 | 1        | 3.7%    |

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
| Detected | 22       | 41     | 81.48%  |
| Works    | 3        | 6      | 11.11%  |
| Malfunc  | 2        | 3      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 15       | 39.47%  |
| AMD                          | 10       | 26.32%  |
| Samsung Electronics          | 3        | 7.89%   |
| ASMedia Technology           | 3        | 7.89%   |
| SanDisk                      | 2        | 5.26%   |
| Marvell Technology Group     | 2        | 5.26%   |
| Toshiba America Info Systems | 1        | 2.63%   |
| SK hynix                     | 1        | 2.63%   |
| Micron/Crucial Technology    | 1        | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 6.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 6.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 6.82%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 6.82%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 4.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 4.55%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 4.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 4.55%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 2.27%   |
| SK hynix PC400 NVMe SSD                                                        | 1        | 2.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 2.27%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 2.27%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 2.27%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 2.27%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 2.27%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 2.27%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family IDE-r Controller                     | 1        | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 2.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 2.27%   |
| ASMedia ASM1061 SATA IDE Controller                                            | 1        | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 57.14%  |
| IDE  | 8        | 22.86%  |
| NVMe | 5        | 14.29%  |
| RAID | 2        | 5.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 60%     |
| AMD    | 10       | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 8%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 4%      |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 4%      |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 4%      |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 4%      |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 4%      |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 4%      |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 4%      |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 4%      |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 4%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 4%      |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 4%      |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 4%      |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 4%      |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 4%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 4%      |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 4%      |
| AMD R-464L APU with Radeon HD Graphics      | 1        | 4%      |
| AMD Phenom II X4 955 Processor              | 1        | 4%      |
| AMD Phenom 9750 Quad-Core Processor         | 1        | 4%      |
| AMD FX-9590 Eight-Core Processor            | 1        | 4%      |
| AMD FX-8370 Eight-Core Processor            | 1        | 4%      |
| AMD FX-4300 Quad-Core Processor             | 1        | 4%      |
| AMD A8-6600K APU with Radeon HD Graphics    | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 5        | 20%     |
| Intel Core i5           | 4        | 16%     |
| AMD FX                  | 3        | 12%     |
| Intel Core i3           | 2        | 8%      |
| Intel Core 2 Quad       | 2        | 8%      |
| Other                   | 1        | 4%      |
| Intel Pentium Dual-Core | 1        | 4%      |
| Intel Pentium           | 1        | 4%      |
| AMD Ryzen 7             | 1        | 4%      |
| AMD Ryzen 5             | 1        | 4%      |
| AMD Ryzen 3             | 1        | 4%      |
| AMD Phenom II X4        | 1        | 4%      |
| AMD Phenom              | 1        | 4%      |
| AMD A8                  | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 52%     |
| 2      | 7        | 28%     |
| 6      | 3        | 12%     |
| 8      | 2        | 8%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 52%     |
| 1      | 12       | 48%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 28%     |
| 0x306a9    | 4        | 16%     |
| 0x08108109 | 2        | 8%      |
| 0x06001119 | 2        | 8%      |
| 0x06000852 | 2        | 8%      |
| 0x906ed    | 1        | 4%      |
| 0x6fb      | 1        | 4%      |
| 0x506e3    | 1        | 4%      |
| 0x306c3    | 1        | 4%      |
| 0x20655    | 1        | 4%      |
| 0x08701021 | 1        | 4%      |
| 0x010000c9 | 1        | 4%      |
| 0x010000c8 | 1        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Piledriver | 5        | 20%     |
| IvyBridge  | 4        | 16%     |
| KabyLake   | 3        | 12%     |
| Zen+       | 2        | 8%      |
| K10        | 2        | 8%      |
| Haswell    | 2        | 8%      |
| Core       | 2        | 8%      |
| Zen 2      | 1        | 4%      |
| Westmere   | 1        | 4%      |
| Skylake    | 1        | 4%      |
| Penryn     | 1        | 4%      |
| CometLake  | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 40%     |
| Intel  | 9        | 30%     |
| AMD    | 9        | 30%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 2        | 6.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2        | 6.67%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]     | 2        | 6.67%   |
| Nvidia TU106 [GeForce GTX 1650]                                           | 1        | 3.33%   |
| Nvidia GT218 [GeForce 210]                                                | 1        | 3.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 3.33%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 1        | 3.33%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1        | 3.33%   |
| Nvidia GM107 [GeForce GTX 750]                                            | 1        | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1        | 3.33%   |
| Nvidia GK107GL [Quadro K2000D]                                            | 1        | 3.33%   |
| Nvidia GK107 [GeForce GT 640]                                             | 1        | 3.33%   |
| Nvidia GK107 [GeForce GT 630 OEM]                                         | 1        | 3.33%   |
| Nvidia GK104 [GeForce GTX 760]                                            | 1        | 3.33%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                         | 1        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 3.33%   |
| Intel HD Graphics 530                                                     | 1        | 3.33%   |
| Intel Core Processor Integrated Graphics Controller                       | 1        | 3.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 3.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 3.33%   |
| AMD Trinity [Radeon HD 7660G]                                             | 1        | 3.33%   |
| AMD RV730 PRO [Radeon HD 4650]                                            | 1        | 3.33%   |
| AMD RV710 [Radeon HD 4350/4550]                                           | 1        | 3.33%   |
| AMD RS880 [Radeon HD 4200]                                                | 1        | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 3.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 1        | 3.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 11       | 40.74%  |
| 1 x AMD        | 9        | 33.33%  |
| 1 x Intel      | 6        | 22.22%  |
| Intel + Nvidia | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 76%     |
| Proprietary | 6        | 24%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 38.46%  |
| 1.01-2.0   | 9        | 34.62%  |
| 0.51-1.0   | 2        | 7.69%   |
| 0.01-0.5   | 2        | 7.69%   |
| 7.01-8.0   | 1        | 3.85%   |
| 5.01-6.0   | 1        | 3.85%   |
| 3.01-4.0   | 1        | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 12.5%   |
| Goldstar            | 3        | 12.5%   |
| Dell                | 3        | 12.5%   |
| AOC                 | 2        | 8.33%   |
| Acer                | 2        | 8.33%   |
| Toshiba             | 1        | 4.17%   |
| Sony                | 1        | 4.17%   |
| Samsung Electronics | 1        | 4.17%   |
| Panasonic           | 1        | 4.17%   |
| LG Electronics      | 1        | 4.17%   |
| HannStar            | 1        | 4.17%   |
| Gateway             | 1        | 4.17%   |
| Element             | 1        | 4.17%   |
| BenQ                | 1        | 4.17%   |
| AUS                 | 1        | 4.17%   |
| ASUSTek Computer    | 1        | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Toshiba LCD Monitor TV 1920x1080                                | 1        | 4%      |
| Sony TV SNYDC01 1360x768                                        | 1        | 4%      |
| Samsung Electronics LCD Monitor SMS27A850T 2560x1440            | 1        | 4%      |
| Panasonic TV MEIC135 1920x1080 698x392mm 31.5-inch              | 1        | 4%      |
| LG Electronics LCD Monitor LG IPS FULLHD                        | 1        | 4%      |
| LG Electronics LCD Monitor LG HDR 4K 7360x2160                  | 1        | 4%      |
| Hewlett-Packard LCD Monitor w1907 3120x1050                     | 1        | 4%      |
| Hewlett-Packard LCD Monitor 2310 1920x1080                      | 1        | 4%      |
| Hewlett-Packard LCD Monitor 2009                                | 1        | 4%      |
| HannStar Hanns.G HH241 HSD2275 1920x1080 521x293mm 23.5-inch    | 1        | 4%      |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch            | 1        | 4%      |
| Goldstar TV SSCR2 GSM8080 3840x2160                             | 1        | 4%      |
| Goldstar E2050 GSM4EAD 1600x900 443x249mm 20.0-inch             | 1        | 4%      |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch           | 1        | 4%      |
| Element E2SW3918 E2SW3918 ELE6308 1366x768 1365x768mm 61.7-inch | 1        | 4%      |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch               | 1        | 4%      |
| Dell P2217H DELA0D7 1920x1080 476x267mm 21.5-inch               | 1        | 4%      |
| Dell LCD Monitor E228WFP                                        | 1        | 4%      |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch              | 1        | 4%      |
| AUS LCD Monitor VA32AQ 2560x1440                                | 1        | 4%      |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch    | 1        | 4%      |
| AOC L19W931 AOC1993 1360x768 410x256mm 19.0-inch                | 1        | 4%      |
| AOC 2243W AOC2243 1920x1080 477x268mm 21.5-inch                 | 1        | 4%      |
| Acer K243Y ACR08B7 1920x1080 527x296mm 23.8-inch                | 1        | 4%      |
| Acer G226HQL ACR02EA 1920x1080 477x268mm 21.5-inch              | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 12       | 50%     |
| 3840x2160 (4K)  | 3        | 12.5%   |
| 2560x1440 (QHD) | 2        | 8.33%   |
| 1360x768        | 2        | 8.33%   |
| Unknown         | 2        | 8.33%   |
| 7360x2160       | 1        | 4.17%   |
| 3120x1050       | 1        | 4.17%   |
| 1600x900 (HD+)  | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 27.27%  |
| 23      | 5        | 22.73%  |
| 21      | 3        | 13.64%  |
| 72      | 2        | 9.09%   |
| 31      | 2        | 9.09%   |
| 61      | 1        | 4.55%   |
| 27      | 1        | 4.55%   |
| 20      | 1        | 4.55%   |
| 19      | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 6        | 27.27%  |
| 501-600     | 5        | 22.73%  |
| 401-500     | 5        | 22.73%  |
| 601-700     | 3        | 13.64%  |
| 1501-2000   | 2        | 9.09%   |
| 1001-1500   | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 15       | 68.18%  |
| Unknown | 6        | 27.27%  |
| 16/10   | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 27.27%  |
| Unknown        | 6        | 27.27%  |
| 151-200        | 4        | 18.18%  |
| More than 1000 | 3        | 13.64%  |
| 351-500        | 2        | 9.09%   |
| 301-350        | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 40.91%  |
| Unknown | 6        | 27.27%  |
| 101-120 | 3        | 13.64%  |
| 1-50    | 2        | 9.09%   |
| 121-160 | 2        | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 23       | 92%     |
| 3     | 1        | 4%      |
| 2     | 1        | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 44.44%  |
| Intel                           | 8        | 22.22%  |
| Qualcomm Atheros                | 4        | 11.11%  |
| TP-Link                         | 1        | 2.78%   |
| Ralink                          | 1        | 2.78%   |
| Qualcomm Atheros Communications | 1        | 2.78%   |
| MediaTek                        | 1        | 2.78%   |
| Edimax Technology               | 1        | 2.78%   |
| D-Link System                   | 1        | 2.78%   |
| Broadcom                        | 1        | 2.78%   |
| AVM                             | 1        | 2.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 13       | 33.33%  |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 5.13%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 2.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 2.56%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 2.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 2.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 2.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 2.56%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 2.56%   |
| MediaTek WiFi                                                          | 1        | 2.56%   |
| Intel Wireless-AC 9260                                                 | 1        | 2.56%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 2.56%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 2.56%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 2.56%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]               | 1        | 2.56%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 2.56%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1        | 2.56%   |
| AVM FRITZ!WLAN AC 860                                                  | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 28.57%  |
| Qualcomm Atheros                | 2        | 14.29%  |
| TP-Link                         | 1        | 7.14%   |
| Realtek Semiconductor           | 1        | 7.14%   |
| Ralink                          | 1        | 7.14%   |
| Qualcomm Atheros Communications | 1        | 7.14%   |
| MediaTek                        | 1        | 7.14%   |
| Edimax Technology               | 1        | 7.14%   |
| D-Link System                   | 1        | 7.14%   |
| AVM                             | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 14.29%  |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 7.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 7.14%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 7.14%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 7.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 7.14%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 7.14%   |
| MediaTek WiFi                                                          | 1        | 7.14%   |
| Intel Wireless-AC 9260                                                 | 1        | 7.14%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 7.14%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]               | 1        | 7.14%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 7.14%   |
| AVM FRITZ!WLAN AC 860                                                  | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 64%     |
| Intel                 | 5        | 20%     |
| Qualcomm Atheros      | 3        | 12%     |
| Broadcom              | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 52%     |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 4%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 4%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 4%      |
| Intel Ethernet Connection I217-LM                                 | 1        | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4%      |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4%      |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 4%      |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 65.79%  |
| WiFi     | 13       | 34.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 73.08%  |
| WiFi     | 7        | 26.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 68%     |
| 2     | 8        | 32%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 84%     |
| Yes  | 4        | 16%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 44.44%  |
| Realtek Semiconductor   | 1        | 11.11%  |
| Dell                    | 1        | 11.11%  |
| Cambridge Silicon Radio | 1        | 11.11%  |
| Broadcom                | 1        | 11.11%  |
| ASUSTek Computer        | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 22.22%  |
| Realtek Bluetooth Radio                             | 1        | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 11.11%  |
| Intel AX200 Bluetooth                               | 1        | 11.11%  |
| Dell BT Mini-Receiver                               | 1        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 11.11%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 15       | 35.71%  |
| AMD                 | 14       | 33.33%  |
| Nvidia              | 12       | 28.57%  |
| C-Media Electronics | 1        | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                            | 5        | 10.42%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 4        | 8.33%   |
| Nvidia GK107 HDMI Audio Controller                                      | 3        | 6.25%   |
| Intel Cannon Lake PCH cAVS                                              | 2        | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2        | 4.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                        | 2        | 4.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2        | 4.17%   |
| AMD FCH Azalia Controller                                               | 2        | 4.17%   |
| AMD Family 17h/19h HD Audio Controller                                  | 2        | 4.17%   |
| Nvidia TU106 High Definition Audio Controller                           | 1        | 2.08%   |
| Nvidia High Definition Audio Controller                                 | 1        | 2.08%   |
| Nvidia GP106 High Definition Audio Controller                           | 1        | 2.08%   |
| Nvidia GM206 High Definition Audio Controller                           | 1        | 2.08%   |
| Nvidia GM204 High Definition Audio Controller                           | 1        | 2.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1        | 2.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 1        | 2.08%   |
| Nvidia GK104 HDMI Audio Controller                                      | 1        | 2.08%   |
| Nvidia GF116 High Definition Audio Controller                           | 1        | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1        | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 2.08%   |
| Intel Comet Lake PCH-V cAVS                                             | 1        | 2.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                        | 1        | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                          | 1        | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                | 1        | 2.08%   |
| Intel 200 Series PCH HD Audio                                           | 1        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 1        | 2.08%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                           | 1        | 2.08%   |
| AMD Trinity HDMI Audio Controller                                       | 1        | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                | 1        | 2.08%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                            | 1        | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 1        | 2.08%   |
| AMD Navi 10 HDMI Audio                                                  | 1        | 2.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                  | 1        | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Unknown  | 1        | 25%     |
| Team     | 1        | 25%     |
| Smart    | 1        | 25%     |
| SK hynix | 1        | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 1066MT/s                 | 1        | 25%     |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s     | 1        | 25%     |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s     | 1        | 25%     |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 1        | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 2        | 50%     |
| DDR4    | 1        | 25%     |
| Unknown | 1        | 25%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 4        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 2        | 50%     |
| 32768 | 1        | 25%     |
| 4096  | 1        | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 1        | 25%     |
| 1800  | 1        | 25%     |
| 1333  | 1        | 25%     |
| 1066  | 1        | 25%     |

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
| 0     | 23       | 92%     |
| 1     | 2        | 8%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Network      | 1        | 50%     |
| Net/wireless | 1        | 50%     |

