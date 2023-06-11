Sparky - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| ASRock   | FM2A58M-VG3+ R2.0    | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| HP       | 1589                 | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| HP       | 1589                 | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| HP       | 0A5Ch                | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Acer     | Aspire X3470         | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| Foxconn  | 2ABF                 | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
| Foxconn  | 2ABF                 | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| Foxconn  | 2ABF                 | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| ASUSTek  | G20AJ                | [7e1557713a](https://linux-hardware.org/?probe=7e1557713a) | Sep 06, 2022 |
| Gigabyte | X570S AORUS PRO AX   | [4fb948980f](https://linux-hardware.org/?probe=4fb948980f) | Aug 25, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel    | H61                  | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| HP       | 3641h                | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| Intel    | H55                  | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| MSI      | B450 GAMING PLUS MAX | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| MSI      | H310M PRO-VDH PLUS   | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| MSI      | H310M PRO-VDH PLUS   | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP       | 805B                 | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Gigabyte | H97-Gaming 3         | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| MSI      | A68HM-E33 V2         | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| Gigabyte | H410M H              | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| Pegatron | 2AC2A                | [8a5448bc07](https://linux-hardware.org/?probe=8a5448bc07) | Jan 17, 2021 |
| Pegatron | 2AC2A                | [c76bbefc71](https://linux-hardware.org/?probe=c76bbefc71) | Jan 09, 2021 |
| Pegatron | 2AC2A                | [95ead72109](https://linux-hardware.org/?probe=95ead72109) | Dec 17, 2020 |
| HP       | 8056                 | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Intel    | DG41TY AAE47335-300  | [e3457f83fa](https://linux-hardware.org/?probe=e3457f83fa) | Oct 22, 2020 |
| Gigabyte | M68M-S2P             | [0e4bab3503](https://linux-hardware.org/?probe=0e4bab3503) | Oct 05, 2020 |
| Unknown  | 4CoreDX90-VSTA       | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Gigabyte | G41M-ES2L            | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte | G41M-ES2L            | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Dell     | 039VR8 A00           | [d386006ad9](https://linux-hardware.org/?probe=d386006ad9) | Jun 15, 2020 |
| Vorke    | V1 Plus              | [e371a7cf42](https://linux-hardware.org/?probe=e371a7cf42) | Mar 29, 2020 |
| Intel    | DG43RK AAE78175-402  | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| ASRock   | H61M-VG4             | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Sparky 6    | 7        | 26.92%  |
| Sparky 7    | 5        | 19.23%  |
| Sparky 5.12 | 3        | 11.54%  |
| Sparky 6.3  | 2        | 7.69%   |
| Sparky 6.2  | 2        | 7.69%   |
| Sparky 6.1  | 2        | 7.69%   |
| Sparky 6.7  | 1        | 3.85%   |
| Sparky 6.6  | 1        | 3.85%   |
| Sparky 6.5  | 1        | 3.85%   |
| Sparky 6.0  | 1        | 3.85%   |
| Sparky 5.10 | 1        | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 24       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.1.0-7-amd64             | 1        | 3.7%    |
| 6.1.0-3-amd64             | 1        | 3.7%    |
| 6.0.11-x64v2-rt14-xanmod1 | 1        | 3.7%    |
| 6.0.0-5-amd64             | 1        | 3.7%    |
| 5.9.13-sparky-amd64       | 1        | 3.7%    |
| 5.7.2-sparky-amd64        | 1        | 3.7%    |
| 5.6.0-2-amd64             | 1        | 3.7%    |
| 5.18.3-sparky-amd64       | 1        | 3.7%    |
| 5.18.0-4-amd64            | 1        | 3.7%    |
| 5.18.0-2-amd64            | 1        | 3.7%    |
| 5.17.3-sparky-amd64       | 1        | 3.7%    |
| 5.16.5-sparky-amd64       | 1        | 3.7%    |
| 5.10.0-9-amd64            | 1        | 3.7%    |
| 5.10.0-8-amd64            | 1        | 3.7%    |
| 5.10.0-7-amd64            | 1        | 3.7%    |
| 5.10.0-6-amd64            | 1        | 3.7%    |
| 5.10.0-3-amd64            | 1        | 3.7%    |
| 5.10.0-23-amd64           | 1        | 3.7%    |
| 5.10.0-21-amd64           | 1        | 3.7%    |
| 5.10.0-2-amd64            | 1        | 3.7%    |
| 5.10.0-14-amd64           | 1        | 3.7%    |
| 5.10.0-12-amd64           | 1        | 3.7%    |
| 5.10.0-11-686             | 1        | 3.7%    |
| 4.19.0-8-amd64            | 1        | 3.7%    |
| 4.19.0-12-amd64           | 1        | 3.7%    |
| 4.19.0-10-amd64           | 1        | 3.7%    |
| 4.19.0-10-686             | 1        | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 11       | 40.74%  |
| 4.19.0  | 4        | 14.81%  |
| 6.1.0   | 2        | 7.41%   |
| 5.18.0  | 2        | 7.41%   |
| 6.0.11  | 1        | 3.7%    |
| 6.0.0   | 1        | 3.7%    |
| 5.9.13  | 1        | 3.7%    |
| 5.7.2   | 1        | 3.7%    |
| 5.6.0   | 1        | 3.7%    |
| 5.18.3  | 1        | 3.7%    |
| 5.17.3  | 1        | 3.7%    |
| 5.16.5  | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 11       | 42.31%  |
| 4.19    | 4        | 15.38%  |
| 5.18    | 3        | 11.54%  |
| 6.1     | 2        | 7.69%   |
| 6.0     | 1        | 3.85%   |
| 5.9     | 1        | 3.85%   |
| 5.7     | 1        | 3.85%   |
| 5.6     | 1        | 3.85%   |
| 5.17    | 1        | 3.85%   |
| 5.16    | 1        | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 22       | 91.67%  |
| i686   | 2        | 8.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 10       | 41.67%  |
| LXQt             | 6        | 25%     |
| KDE5             | 3        | 12.5%   |
| X-Cinnamon       | 1        | 4.17%   |
| lightdm-xsession | 1        | 4.17%   |
| ICEWM            | 1        | 4.17%   |
| GNOME            | 1        | 4.17%   |
| Unknown          | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 24       | 96%     |
| Tty  | 1        | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 37.5%   |
| TDM     | 6        | 25%     |
| SDDM    | 6        | 25%     |
| LightDM | 3        | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 5        | 20.83%  |
| pt_BR | 3        | 12.5%   |
| en_GB | 3        | 12.5%   |
| fr_FR | 2        | 8.33%   |
| es_ES | 2        | 8.33%   |
| sv_SE | 1        | 4.17%   |
| id_ID | 1        | 4.17%   |
| es_US | 1        | 4.17%   |
| es_AR | 1        | 4.17%   |
| en_ZA | 1        | 4.17%   |
| en_DK | 1        | 4.17%   |
| en_CA | 1        | 4.17%   |
| de_CH | 1        | 4.17%   |
| cs_CZ | 1        | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 15       | 62.5%   |
| EFI  | 9        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 23       | 95.83%  |
| Zfs  | 1        | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 37.5%   |
| GPT     | 8        | 33.33%  |
| MBR     | 7        | 29.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 83.33%  |
| Yes       | 4        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 70.83%  |
| Yes       | 7        | 29.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 20.83%  |
| Gigabyte Technology | 5        | 20.83%  |
| Intel               | 4        | 16.67%  |
| MSI                 | 3        | 12.5%   |
| ASUSTek Computer    | 2        | 8.33%   |
| Foxconn             | 1        | 4.17%   |
| Dell                | 1        | 4.17%   |
| ASRock              | 1        | 4.17%   |
| Acer                | 1        | 4.17%   |
| Unknown             | 1        | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C09                         | 1        | 4.17%   |
| MSI MS-7B86                         | 1        | 4.17%   |
| MSI MS-7721                         | 1        | 4.17%   |
| Intel H61                           | 1        | 4.17%   |
| Intel H55                           | 1        | 4.17%   |
| Intel DG43RK AAE78175-402           | 1        | 4.17%   |
| Intel DG41TY AAE47335-300           | 1        | 4.17%   |
| HP Z420 Workstation                 | 1        | 4.17%   |
| HP t5740                            | 1        | 4.17%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 4.17%   |
| HP EliteDesk 705 G2 MINI            | 1        | 4.17%   |
| HP Compaq dc7700 Ultra-slim Desktop | 1        | 4.17%   |
| Gigabyte X570S AORUS PRO AX         | 1        | 4.17%   |
| Gigabyte M68M-S2P                   | 1        | 4.17%   |
| Gigabyte H97-Gaming 3               | 1        | 4.17%   |
| Gigabyte H410M H                    | 1        | 4.17%   |
| Gigabyte G41M-ES2L                  | 1        | 4.17%   |
| Foxconn p6-2010fr                   | 1        | 4.17%   |
| Dell OptiPlex 580                   | 1        | 4.17%   |
| ASUS G20AJ                          | 1        | 4.17%   |
| ASUS CROSSHAIR VI HERO              | 1        | 4.17%   |
| ASRock FM2A58M-VG3+ R2.0            | 1        | 4.17%   |
| Acer Aspire X3470                   | 1        | 4.17%   |
| Unknown                             | 1        | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP EliteDesk        | 2        | 8.33%   |
| MSI MS-7C09         | 1        | 4.17%   |
| MSI MS-7B86         | 1        | 4.17%   |
| MSI MS-7721         | 1        | 4.17%   |
| Intel H61           | 1        | 4.17%   |
| Intel H55           | 1        | 4.17%   |
| Intel DG43RK        | 1        | 4.17%   |
| Intel DG41TY        | 1        | 4.17%   |
| HP Z420             | 1        | 4.17%   |
| HP t5740            | 1        | 4.17%   |
| HP Compaq           | 1        | 4.17%   |
| Gigabyte X570S      | 1        | 4.17%   |
| Gigabyte M68M-S2P   | 1        | 4.17%   |
| Gigabyte H97-Gaming | 1        | 4.17%   |
| Gigabyte H410M      | 1        | 4.17%   |
| Gigabyte G41M-ES2L  | 1        | 4.17%   |
| Foxconn p6-2010fr   | 1        | 4.17%   |
| Dell OptiPlex       | 1        | 4.17%   |
| ASUS G20AJ          | 1        | 4.17%   |
| ASUS CROSSHAIR      | 1        | 4.17%   |
| ASRock FM2A58M-VG3+ | 1        | 4.17%   |
| Acer Aspire         | 1        | 4.17%   |
| Unknown             | 1        | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 4        | 16.67%  |
| 2014 | 3        | 12.5%   |
| 2021 | 2        | 8.33%   |
| 2018 | 2        | 8.33%   |
| 2015 | 2        | 8.33%   |
| 2012 | 2        | 8.33%   |
| 2011 | 2        | 8.33%   |
| 2007 | 2        | 8.33%   |
| 2020 | 1        | 4.17%   |
| 2019 | 1        | 4.17%   |
| 2017 | 1        | 4.17%   |
| 2016 | 1        | 4.17%   |
| 2010 | 1        | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 24       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 24       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 6        | 25%     |
| 16.01-24.0 | 6        | 25%     |
| 4.01-8.0   | 4        | 16.67%  |
| 8.01-16.0  | 4        | 16.67%  |
| 1.01-2.0   | 2        | 8.33%   |
| 24.01-32.0 | 1        | 4.17%   |
| 2.01-3.0   | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 17       | 65.38%  |
| 2.01-3.0 | 3        | 11.54%  |
| 0.51-1.0 | 3        | 11.54%  |
| 4.01-8.0 | 2        | 7.69%   |
| 3.01-4.0 | 1        | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 59.26%  |
| 2      | 5        | 18.52%  |
| 4      | 3        | 11.11%  |
| 6      | 2        | 7.41%   |
| 3      | 1        | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 66.67%  |
| Yes       | 8        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 95.83%  |
| No        | 1        | 4.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 62.5%   |
| Yes       | 9        | 37.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 79.17%  |
| Yes       | 5        | 20.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| UK           | 3        | 12.5%   |
| Indonesia    | 3        | 12.5%   |
| France       | 3        | 12.5%   |
| Brazil       | 3        | 12.5%   |
| Argentina    | 2        | 8.33%   |
| Venezuela    | 1        | 4.17%   |
| Switzerland  | 1        | 4.17%   |
| Sweden       | 1        | 4.17%   |
| Spain        | 1        | 4.17%   |
| South Africa | 1        | 4.17%   |
| Lebanon      | 1        | 4.17%   |
| Germany      | 1        | 4.17%   |
| Czechia      | 1        | 4.17%   |
| Canada       | 1        | 4.17%   |
| Belgium      | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Bandung          | 2        | 7.69%   |
| Woking           | 1        | 3.85%   |
| Trelaze          | 1        | 3.85%   |
| Surabaya         | 1        | 3.85%   |
| Sin el Fil       | 1        | 3.85%   |
| San Cristóbal   | 1        | 3.85%   |
| Rosario          | 1        | 3.85%   |
| Rio de Janeiro   | 1        | 3.85%   |
| Rio Claro        | 1        | 3.85%   |
| Posadas          | 1        | 3.85%   |
| Montreuil        | 1        | 3.85%   |
| Mnisek pod Brdy  | 1        | 3.85%   |
| Kirkcaldy        | 1        | 3.85%   |
| Kage             | 1        | 3.85%   |
| Harlow           | 1        | 3.85%   |
| Grabs            | 1        | 3.85%   |
| Fuveau           | 1        | 3.85%   |
| Frankfurt (Oder) | 1        | 3.85%   |
| Enfield          | 1        | 3.85%   |
| Duque de Caxias  | 1        | 3.85%   |
| Dartmouth        | 1        | 3.85%   |
| Cape Town        | 1        | 3.85%   |
| Calanda          | 1        | 3.85%   |
| Brussels         | 1        | 3.85%   |
| Bordeaux         | 1        | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 26.32%  |
| Seagate             | 8        | 10     | 21.05%  |
| Samsung Electronics | 7        | 18     | 18.42%  |
| Kingston            | 3        | 3      | 7.89%   |
| Toshiba             | 2        | 2      | 5.26%   |
| Hitachi             | 2        | 2      | 5.26%   |
| XPG                 | 1        | 1      | 2.63%   |
| SanDisk             | 1        | 2      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |
| Gigabyte Technology | 1        | 1      | 2.63%   |
| ASMedia             | 1        | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST500LT012-1DG142 500GB         | 2        | 4.65%   |
| Samsung HD161GJ 160GB                   | 2        | 4.65%   |
| XPG GAMMIX S11 Pro 512GB                | 1        | 2.33%   |
| WDC WD800JD-08MSA1 80GB                 | 1        | 2.33%   |
| WDC WD5000AVVS-63ZWB0 500GB             | 1        | 2.33%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1        | 2.33%   |
| WDC WD50 00LPLX-08ZNTT0 500GB           | 1        | 2.33%   |
| WDC WD2500AAKX-07U6AA0 250GB            | 1        | 2.33%   |
| WDC WD2500AAJS-00L7A0 250GB             | 1        | 2.33%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 2.33%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1        | 2.33%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 2.33%   |
| WDC WD10EADS-00M2B0 1TB                 | 1        | 2.33%   |
| Toshiba DT01ACA100 1TB                  | 1        | 2.33%   |
| Toshiba DT01ACA050 500GB                | 1        | 2.33%   |
| Seagate ST975042 0AS 752GB              | 1        | 2.33%   |
| Seagate ST9500420AS 500GB               | 1        | 2.33%   |
| Seagate ST9250315AS 250GB               | 1        | 2.33%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 2.33%   |
| Seagate ST3500312CS 500GB               | 1        | 2.33%   |
| Seagate ST3320418AS 320GB               | 1        | 2.33%   |
| Seagate ST2000VM003-1ET164 2TB          | 1        | 2.33%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB | 1        | 2.33%   |
| SanDisk NVMe SSD Drive 500GB            | 1        | 2.33%   |
| Samsung SSD 850 EVO 500GB               | 1        | 2.33%   |
| Samsung SSD 850 EVO 250GB               | 1        | 2.33%   |
| Samsung SSD 840 PRO Series 512GB        | 1        | 2.33%   |
| Samsung MZVPV256HDGL-000H1 256GB        | 1        | 2.33%   |
| Samsung HN-M320MBB 320GB                | 1        | 2.33%   |
| Samsung HD753LJ 752GB                   | 1        | 2.33%   |
| Samsung HD322GJ 320GB                   | 1        | 2.33%   |
| Samsung HD154UI 1TB                     | 1        | 2.33%   |
| Kingston SV300S37A480G 480GB SSD        | 1        | 2.33%   |
| Kingston SA400S37120G 120GB SSD         | 1        | 2.33%   |
| Kingston SA400M8240G 240GB SSD          | 1        | 2.33%   |
| Intel SSDSA2BW120G3H 120GB              | 1        | 2.33%   |
| Hitachi HTS723232A7A364 320GB           | 1        | 2.33%   |
| Hitachi HTS543232A7A384 320GB           | 1        | 2.33%   |
| HGST HTS545050A7E380 500GB              | 1        | 2.33%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD    | 1        | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 35.71%  |
| Seagate             | 8        | 9      | 28.57%  |
| Samsung Electronics | 4        | 11     | 14.29%  |
| Toshiba             | 2        | 2      | 7.14%   |
| Hitachi             | 2        | 2      | 7.14%   |
| HGST                | 1        | 1      | 3.57%   |
| ASMedia             | 1        | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 37.5%   |
| Kingston            | 3        | 3      | 37.5%   |
| Intel               | 1        | 1      | 12.5%   |
| Gigabyte Technology | 1        | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 36     | 64.52%  |
| SSD  | 8        | 11     | 25.81%  |
| NVMe | 3        | 5      | 9.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 44     | 85.71%  |
| NVMe | 3        | 5      | 10.71%  |
| SAS  | 1        | 3      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 34     | 78.57%  |
| 0.51-1.0   | 5        | 12     | 17.86%  |
| 1.01-2.0   | 1        | 1      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 8        | 32%     |
| 101-250    | 5        | 20%     |
| 501-1000   | 4        | 16%     |
| 2001-3000  | 3        | 12%     |
| 51-100     | 3        | 12%     |
| 1-20       | 1        | 4%      |
| Unknown    | 1        | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 12       | 48%     |
| 251-500   | 3        | 12%     |
| 21-50     | 3        | 12%     |
| 1001-2000 | 2        | 8%      |
| 51-100    | 2        | 8%      |
| 101-250   | 1        | 4%      |
| 501-1000  | 1        | 4%      |
| Unknown   | 1        | 4%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AVVS-63ZWB0 500GB | 1        | 1      | 25%     |
| WDC WD1600AAJS-08L7A0 160GB | 1        | 1      | 25%     |
| WDC WD10EADS-00M2B0 1TB     | 1        | 1      | 25%     |
| Seagate ST9250315AS 250GB   | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 100%    |

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
| Works    | 14       | 20     | 50%     |
| Detected | 10       | 28     | 35.71%  |
| Malfunc  | 4        | 4      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 14       | 46.67%  |
| AMD                       | 8        | 26.67%  |
| VIA Technologies          | 1        | 3.33%   |
| Seagate Technology        | 1        | 3.33%   |
| SanDisk                   | 1        | 3.33%   |
| Samsung Electronics       | 1        | 3.33%   |
| Nvidia                    | 1        | 3.33%   |
| Marvell Technology Group  | 1        | 3.33%   |
| LSI Logic / Symbios Logic | 1        | 3.33%   |
| ADATA Technology          | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 7        | 17.5%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 5%      |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1        | 2.5%    |
| VIA VT8237A SATA 2-Port Controller                                            | 1        | 2.5%    |
| Seagate Non-Volatile memory controller                                        | 1        | 2.5%    |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                            | 1        | 2.5%    |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1        | 2.5%    |
| Nvidia MCP61 SATA Controller                                                  | 1        | 2.5%    |
| Nvidia MCP61 IDE                                                              | 1        | 2.5%    |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                     | 1        | 2.5%    |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                | 1        | 2.5%    |
| Intel SATA Controller [RAID mode]                                             | 1        | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 2.5%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1        | 2.5%    |
| Intel C600/X79 series chipset IDE-r Controller                                | 1        | 2.5%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1        | 2.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 2.5%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1        | 2.5%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                    | 1        | 2.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 2.5%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 1        | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 2.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1        | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1        | 2.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 2.5%    |
| AMD X370 Series Chipset SATA Controller                                       | 1        | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1        | 2.5%    |
| AMD FCH IDE Controller                                                        | 1        | 2.5%    |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 2.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 48.48%  |
| IDE  | 10       | 30.3%   |
| NVMe | 3        | 9.09%   |
| RAID | 2        | 6.06%   |
| SAS  | 1        | 3.03%   |
| SCSI | 1        | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 62.5%   |
| AMD    | 9        | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz          | 1        | 4.17%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 1        | 4.17%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz  | 1        | 4.17%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1        | 4.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 4.17%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1        | 4.17%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 1        | 4.17%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 4.17%   |
| Intel Core i5-2500 CPU @ 3.30GHz             | 1        | 4.17%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1        | 4.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 4.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 4.17%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 1        | 4.17%   |
| Intel Core 2 CPU 6300 @ 1.86GHz              | 1        | 4.17%   |
| Intel Atom CPU N280 @ 1.66GHz                | 1        | 4.17%   |
| AMD Sempron 145 Processor                    | 1        | 4.17%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 4.17%   |
| AMD Ryzen 7 1800X Eight-Core Processor       | 1        | 4.17%   |
| AMD Ryzen 3 3100 4-Core Processor            | 1        | 4.17%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G  | 1        | 4.17%   |
| AMD Athlon II X2 B22 Processor               | 1        | 4.17%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G | 1        | 4.17%   |
| AMD A6-6400K APU with Radeon HD Graphics     | 1        | 4.17%   |
| AMD A6-3600 APU with Radeon HD Graphics      | 1        | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 4        | 16.67%  |
| Intel Core i7           | 3        | 12.5%   |
| AMD A6                  | 3        | 12.5%   |
| Intel Core 2 Duo        | 2        | 8.33%   |
| Intel Xeon              | 1        | 4.17%   |
| Intel Pentium Gold      | 1        | 4.17%   |
| Intel Pentium Dual-Core | 1        | 4.17%   |
| Intel Core 2 Quad       | 1        | 4.17%   |
| Intel Core 2            | 1        | 4.17%   |
| Intel Atom              | 1        | 4.17%   |
| AMD Sempron             | 1        | 4.17%   |
| AMD Ryzen 9             | 1        | 4.17%   |
| AMD Ryzen 7             | 1        | 4.17%   |
| AMD Ryzen 3             | 1        | 4.17%   |
| AMD PRO A8              | 1        | 4.17%   |
| AMD Athlon II X2        | 1        | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 37.5%   |
| 2      | 7        | 29.17%  |
| 1      | 4        | 16.67%  |
| 8      | 2        | 8.33%   |
| 12     | 1        | 4.17%   |
| 6      | 1        | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 50%     |
| 1      | 12       | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 95.83%  |
| 32-bit         | 1        | 4.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 16.67%  |
| 0x306c3    | 2        | 8.33%   |
| 0x0600611a | 2        | 8.33%   |
| 0xa0653    | 1        | 4.17%   |
| 0x6fd      | 1        | 4.17%   |
| 0x6fb      | 1        | 4.17%   |
| 0x6f2      | 1        | 4.17%   |
| 0x506e3    | 1        | 4.17%   |
| 0x306a9    | 1        | 4.17%   |
| 0x206d7    | 1        | 4.17%   |
| 0x206a7    | 1        | 4.17%   |
| 0x106e5    | 1        | 4.17%   |
| 0x1067a    | 1        | 4.17%   |
| 0x0a201016 | 1        | 4.17%   |
| 0x08701021 | 1        | 4.17%   |
| 0x08001138 | 1        | 4.17%   |
| 0x06001119 | 1        | 4.17%   |
| 0x03000027 | 1        | 4.17%   |
| 0x010000c8 | 1        | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Core        | 3        | 12.5%   |
| SandyBridge | 2        | 8.33%   |
| Penryn      | 2        | 8.33%   |
| K10         | 2        | 8.33%   |
| Haswell     | 2        | 8.33%   |
| Excavator   | 2        | 8.33%   |
| Zen 3       | 1        | 4.17%   |
| Zen 2       | 1        | 4.17%   |
| Zen         | 1        | 4.17%   |
| Skylake     | 1        | 4.17%   |
| Piledriver  | 1        | 4.17%   |
| Nehalem     | 1        | 4.17%   |
| KabyLake    | 1        | 4.17%   |
| K10 Llano   | 1        | 4.17%   |
| IvyBridge   | 1        | 4.17%   |
| CometLake   | 1        | 4.17%   |
| Bonnell     | 1        | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 11       | 42.31%  |
| Intel            | 8        | 30.77%  |
| Nvidia           | 6        | 23.08%  |
| VIA Technologies | 1        | 3.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 7.41%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 7.41%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 3.7%    |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 3.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.7%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 3.7%    |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 3.7%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 3.7%    |
| Intel HD Graphics 530                                                       | 1        | 3.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.7%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 3.7%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 3.7%    |
| AMD Turks GL [FirePro V4900]                                                | 1        | 3.7%    |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 3.7%    |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 3.7%    |
| AMD Richland [Radeon HD 8470D]                                              | 1        | 3.7%    |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 3.7%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.7%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.7%    |
| AMD Cypress XT [Radeon HD 5870]                                             | 1        | 3.7%    |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 3.7%    |
| AMD Barts LE [Radeon HD 6790]                                               | 1        | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 10       | 41.67%  |
| 1 x Intel      | 7        | 29.17%  |
| 1 x Nvidia     | 5        | 20.83%  |
| 1 x VIA        | 1        | 4.17%   |
| Intel + Nvidia | 1        | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 79.17%  |
| Unknown     | 4        | 16.67%  |
| Proprietary | 1        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 52%     |
| 0.51-1.0   | 5        | 20%     |
| 0.01-0.5   | 3        | 12%     |
| 7.01-8.0   | 2        | 8%      |
| 3.01-4.0   | 1        | 4%      |
| 1.01-2.0   | 1        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 23.81%  |
| Goldstar            | 5        | 23.81%  |
| Dell                | 3        | 14.29%  |
| BenQ                | 2        | 9.52%   |
| AOC                 | 2        | 9.52%   |
| Unknown             | 1        | 4.76%   |
| Toshiba             | 1        | 4.76%   |
| JCH                 | 1        | 4.76%   |
| HUYINIUDA           | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 4.17%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                   | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1        | 4.17%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1        | 4.17%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1        | 4.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 4.17%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1        | 4.17%   |
| HUYINIUDA HUYINIUDA HUY1850 1366x768 410x220mm 18.3-inch             | 1        | 4.17%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1        | 4.17%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                 | 1        | 4.17%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                     | 1        | 4.17%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1        | 4.17%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1        | 4.17%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                | 1        | 4.17%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1        | 4.17%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1        | 4.17%   |
| Dell LCD Monitor S2715H                                              | 1        | 4.17%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1        | 4.17%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1        | 4.17%   |
| BenQ FP202W BNQ76C2 1680x1050 430x270mm 20.0-inch                    | 1        | 4.17%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                     | 1        | 4.17%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                      | 1        | 4.17%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1        | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 34.78%  |
| 1366x768 (WXGA)    | 3        | 13.04%  |
| 1280x1024 (SXGA)   | 3        | 13.04%  |
| 1680x1050 (WSXGA+) | 2        | 8.7%    |
| 3840x1080          | 1        | 4.35%   |
| 2288x1287          | 1        | 4.35%   |
| 1600x900 (HD+)     | 1        | 4.35%   |
| 1360x768           | 1        | 4.35%   |
| 1280x960           | 1        | 4.35%   |
| 1024x768 (XGA)     | 1        | 4.35%   |
| Unknown            | 1        | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 18.18%  |
| 20      | 3        | 13.64%  |
| 18      | 3        | 13.64%  |
| 17      | 3        | 13.64%  |
| 21      | 2        | 9.09%   |
| 142     | 1        | 4.55%   |
| 74      | 1        | 4.55%   |
| 72      | 1        | 4.55%   |
| 24      | 1        | 4.55%   |
| 16      | 1        | 4.55%   |
| 13      | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 8        | 36.36%  |
| 501-600        | 5        | 22.73%  |
| 301-350        | 4        | 18.18%  |
| 1501-2000      | 2        | 9.09%   |
| More than 2000 | 1        | 4.55%   |
| 201-300        | 1        | 4.55%   |
| Unknown        | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 12       | 54.55%  |
| 5/4     | 3        | 13.64%  |
| 16/10   | 3        | 13.64%  |
| 4/3     | 2        | 9.09%   |
| 1.00    | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 22.73%  |
| 151-200        | 5        | 22.73%  |
| 141-150        | 5        | 22.73%  |
| More than 1000 | 3        | 13.64%  |
| 81-90          | 1        | 4.55%   |
| 131-140        | 1        | 4.55%   |
| 121-130        | 1        | 4.55%   |
| Unknown        | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 71.43%  |
| 1-50    | 3        | 14.29%  |
| 101-120 | 2        | 9.52%   |
| Unknown | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 79.17%  |
| 2     | 3        | 12.5%   |
| 0     | 2        | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 36.36%  |
| Intel                 | 7        | 21.21%  |
| Ralink Technology     | 3        | 9.09%   |
| Qualcomm Atheros      | 3        | 9.09%   |
| Broadcom Limited      | 2        | 6.06%   |
| Broadcom              | 2        | 6.06%   |
| VIA Technologies      | 1        | 3.03%   |
| TP-Link               | 1        | 3.03%   |
| Nvidia                | 1        | 3.03%   |
| D-Link System         | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 9        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 5.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 2.78%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1        | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 2.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 2.78%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 2.78%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 2.78%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 2.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 2.78%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 2.78%   |
| Nvidia MCP61 Ethernet                                                                       | 1        | 2.78%   |
| Intel Wireless 8260                                                                         | 1        | 2.78%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 2.78%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 2.78%   |
| Intel Ethernet Controller I225-V                                                            | 1        | 2.78%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1        | 2.78%   |
| Intel Ethernet Connection (2) I218-V                                                        | 1        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 1        | 2.78%   |
| Intel 82566DM Gigabit Network Connection                                                    | 1        | 2.78%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 2.78%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 2.78%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1        | 2.78%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                                     | 1        | 2.78%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1        | 2.78%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1        | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Ralink Technology     | 3        | 27.27%  |
| Realtek Semiconductor | 2        | 18.18%  |
| Qualcomm Atheros      | 2        | 18.18%  |
| Intel                 | 2        | 18.18%  |
| TP-Link               | 1        | 9.09%   |
| D-Link System         | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N Version 5 RTL8192EU                                                       | 1        | 9.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 9.09%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 9.09%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 9.09%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 9.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 9.09%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 9.09%   |
| Intel Wireless 8260                                                                         | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 9.09%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 44%     |
| Intel                 | 7        | 28%     |
| Broadcom Limited      | 2        | 8%      |
| Broadcom              | 2        | 8%      |
| VIA Technologies      | 1        | 4%      |
| Qualcomm Atheros      | 1        | 4%      |
| Nvidia                | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 36%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 8%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 4%      |
| Nvidia MCP61 Ethernet                                             | 1        | 4%      |
| Intel I211 Gigabit Network Connection                             | 1        | 4%      |
| Intel Ethernet Controller I225-V                                  | 1        | 4%      |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 4%      |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4%      |
| Intel 82566DM Gigabit Network Connection                          | 1        | 4%      |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 4%      |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 4%      |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 4%      |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 4%      |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1        | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 69.7%   |
| WiFi     | 10       | 30.3%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 70.37%  |
| WiFi     | 8        | 29.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 75%     |
| 2     | 6        | 25%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 91.67%  |
| Yes  | 2        | 8.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 2        | 40%     |
| Qualcomm Atheros Communications | 1        | 20%     |
| IMC Networks                    | 1        | 20%     |
| Cambridge Silicon Radio         | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Qualcomm Atheros Bluetooth                          | 1        | 20%     |
| Intel Bluetooth wireless interface                  | 1        | 20%     |
| Intel AX200 Bluetooth                               | 1        | 20%     |
| IMC Networks Bluetooth Radio                        | 1        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 13       | 38.24%  |
| AMD                 | 12       | 35.29%  |
| Nvidia              | 5        | 14.71%  |
| VIA Technologies    | 1        | 2.94%   |
| Plantronics         | 1        | 2.94%   |
| Creative Labs       | 1        | 2.94%   |
| C-Media Electronics | 1        | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD FCH Azalia Controller                                                  | 3        | 7.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 4.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 4.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 4.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 4.88%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 2        | 4.88%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 2.44%   |
| Plantronics USB DSP v4 Audio Interface                                     | 1        | 2.44%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.44%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2.44%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.44%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.44%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.44%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 1        | 2.44%   |
| C-Media Electronics USB Audio Device                                       | 1        | 2.44%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.44%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 2.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.44%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2.44%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]      | 1        | 2.44%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 26.67%  |
| Samsung Electronics | 3        | 20%     |
| Kingston            | 3        | 20%     |
| Corsair             | 2        | 13.33%  |
| G.Skill             | 1        | 6.67%   |
| Crucial             | 1        | 6.67%   |
| Avant               | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                | 2        | 11.76%  |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 5.88%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 1        | 5.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 5.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 5.88%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s   | 1        | 5.88%   |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s   | 1        | 5.88%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s  | 1        | 5.88%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s         | 1        | 5.88%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 1        | 5.88%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s | 1        | 5.88%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s    | 1        | 5.88%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s | 1        | 5.88%   |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s   | 1        | 5.88%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s | 1        | 5.88%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s      | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 37.5%   |
| DDR4    | 4        | 25%     |
| SDRAM   | 2        | 12.5%   |
| DDR2    | 2        | 12.5%   |
| Unknown | 2        | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 80%     |
| SODIMM | 3        | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 43.75%  |
| 2048  | 4        | 25%     |
| 4096  | 2        | 12.5%   |
| 1024  | 2        | 12.5%   |
| 16384 | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 17.65%  |
| 800     | 3        | 17.65%  |
| 3666    | 1        | 5.88%   |
| 3200    | 1        | 5.88%   |
| 2666    | 1        | 5.88%   |
| 2400    | 1        | 5.88%   |
| 2133    | 1        | 5.88%   |
| 2048    | 1        | 5.88%   |
| 1800    | 1        | 5.88%   |
| 1639    | 1        | 5.88%   |
| 1333    | 1        | 5.88%   |
| 667     | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 33.33%  |
| Samsung Electronics | 1        | 16.67%  |
| Guillemot           | 1        | 16.67%  |
| Alcor Micro         | 1        | 16.67%  |
| Unknown             | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 1        | 16.67%  |
| Logitech Webcam C270                    | 1        | 16.67%  |
| Logitech QuickCam Notebook Pro          | 1        | 16.67%  |
| Guillemot Hercules Dualpix Exchange     | 1        | 16.67%  |
| Alcor Micro USB 2.0 Camera              | 1        | 16.67%  |
| Unknown                                 | 1        | 16.67%  |

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
| 0     | 17       | 70.83%  |
| 1     | 6        | 25%     |
| 2     | 1        | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 62.5%   |
| Net/wireless  | 2        | 25%     |
| Camera        | 1        | 12.5%   |

