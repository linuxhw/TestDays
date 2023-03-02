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

Total: 32

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
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
| Sparky 6    | 7        | 30.43%  |
| Sparky 7    | 4        | 17.39%  |
| Sparky 5.12 | 3        | 13.04%  |
| Sparky 6.3  | 2        | 8.7%    |
| Sparky 6.2  | 2        | 8.7%    |
| Sparky 6.1  | 2        | 8.7%    |
| Sparky 6.5  | 1        | 4.35%   |
| Sparky 6.0  | 1        | 4.35%   |
| Sparky 5.10 | 1        | 4.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 21       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.1.0-3-amd64             | 1        | 4.17%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1        | 4.17%   |
| 6.0.0-5-amd64             | 1        | 4.17%   |
| 5.9.13-sparky-amd64       | 1        | 4.17%   |
| 5.7.2-sparky-amd64        | 1        | 4.17%   |
| 5.6.0-2-amd64             | 1        | 4.17%   |
| 5.18.3-sparky-amd64       | 1        | 4.17%   |
| 5.18.0-4-amd64            | 1        | 4.17%   |
| 5.18.0-2-amd64            | 1        | 4.17%   |
| 5.17.3-sparky-amd64       | 1        | 4.17%   |
| 5.16.5-sparky-amd64       | 1        | 4.17%   |
| 5.10.0-9-amd64            | 1        | 4.17%   |
| 5.10.0-8-amd64            | 1        | 4.17%   |
| 5.10.0-7-amd64            | 1        | 4.17%   |
| 5.10.0-6-amd64            | 1        | 4.17%   |
| 5.10.0-3-amd64            | 1        | 4.17%   |
| 5.10.0-2-amd64            | 1        | 4.17%   |
| 5.10.0-14-amd64           | 1        | 4.17%   |
| 5.10.0-12-amd64           | 1        | 4.17%   |
| 5.10.0-11-686             | 1        | 4.17%   |
| 4.19.0-8-amd64            | 1        | 4.17%   |
| 4.19.0-12-amd64           | 1        | 4.17%   |
| 4.19.0-10-amd64           | 1        | 4.17%   |
| 4.19.0-10-686             | 1        | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 9        | 37.5%   |
| 4.19.0  | 4        | 16.67%  |
| 5.18.0  | 2        | 8.33%   |
| 6.1.0   | 1        | 4.17%   |
| 6.0.11  | 1        | 4.17%   |
| 6.0.0   | 1        | 4.17%   |
| 5.9.13  | 1        | 4.17%   |
| 5.7.2   | 1        | 4.17%   |
| 5.6.0   | 1        | 4.17%   |
| 5.18.3  | 1        | 4.17%   |
| 5.17.3  | 1        | 4.17%   |
| 5.16.5  | 1        | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 9        | 39.13%  |
| 4.19    | 4        | 17.39%  |
| 5.18    | 3        | 13.04%  |
| 6.1     | 1        | 4.35%   |
| 6.0     | 1        | 4.35%   |
| 5.9     | 1        | 4.35%   |
| 5.7     | 1        | 4.35%   |
| 5.6     | 1        | 4.35%   |
| 5.17    | 1        | 4.35%   |
| 5.16    | 1        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 19       | 90.48%  |
| i686   | 2        | 9.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 9        | 42.86%  |
| LXQt             | 5        | 23.81%  |
| KDE5             | 2        | 9.52%   |
| X-Cinnamon       | 1        | 4.76%   |
| lightdm-xsession | 1        | 4.76%   |
| ICEWM            | 1        | 4.76%   |
| GNOME            | 1        | 4.76%   |
| Unknown          | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 21       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 38.1%   |
| TDM     | 6        | 28.57%  |
| SDDM    | 4        | 19.05%  |
| LightDM | 3        | 14.29%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 4        | 19.05%  |
| pt_BR | 3        | 14.29%  |
| fr_FR | 2        | 9.52%   |
| es_ES | 2        | 9.52%   |
| en_GB | 2        | 9.52%   |
| sv_SE | 1        | 4.76%   |
| es_US | 1        | 4.76%   |
| es_AR | 1        | 4.76%   |
| en_ZA | 1        | 4.76%   |
| en_DK | 1        | 4.76%   |
| en_CA | 1        | 4.76%   |
| de_CH | 1        | 4.76%   |
| cs_CZ | 1        | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 13       | 61.9%   |
| EFI  | 8        | 38.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 20       | 95.24%  |
| Zfs  | 1        | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 8        | 38.1%   |
| Unknown | 8        | 38.1%   |
| MBR     | 5        | 23.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 80.95%  |
| Yes       | 4        | 19.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 66.67%  |
| Yes       | 7        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 5        | 23.81%  |
| Intel               | 4        | 19.05%  |
| MSI                 | 3        | 14.29%  |
| Hewlett-Packard     | 3        | 14.29%  |
| ASUSTek Computer    | 2        | 9.52%   |
| Foxconn             | 1        | 4.76%   |
| Dell                | 1        | 4.76%   |
| Acer                | 1        | 4.76%   |
| Unknown             | 1        | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| MSI MS-7C09                 | 1        | 4.76%   |
| MSI MS-7B86                 | 1        | 4.76%   |
| MSI MS-7721                 | 1        | 4.76%   |
| Intel H61                   | 1        | 4.76%   |
| Intel H55                   | 1        | 4.76%   |
| Intel DG43RK AAE78175-402   | 1        | 4.76%   |
| Intel DG41TY AAE47335-300   | 1        | 4.76%   |
| HP t5740                    | 1        | 4.76%   |
| HP EliteDesk 800 G2 DM 65W  | 1        | 4.76%   |
| HP EliteDesk 705 G2 MINI    | 1        | 4.76%   |
| Gigabyte X570S AORUS PRO AX | 1        | 4.76%   |
| Gigabyte M68M-S2P           | 1        | 4.76%   |
| Gigabyte H97-Gaming 3       | 1        | 4.76%   |
| Gigabyte H410M H            | 1        | 4.76%   |
| Gigabyte G41M-ES2L          | 1        | 4.76%   |
| Foxconn p6-2010fr           | 1        | 4.76%   |
| Dell OptiPlex 580           | 1        | 4.76%   |
| ASUS G20AJ                  | 1        | 4.76%   |
| ASUS CROSSHAIR VI HERO      | 1        | 4.76%   |
| Acer Aspire X3470           | 1        | 4.76%   |
| Unknown                     | 1        | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP EliteDesk        | 2        | 9.52%   |
| MSI MS-7C09         | 1        | 4.76%   |
| MSI MS-7B86         | 1        | 4.76%   |
| MSI MS-7721         | 1        | 4.76%   |
| Intel H61           | 1        | 4.76%   |
| Intel H55           | 1        | 4.76%   |
| Intel DG43RK        | 1        | 4.76%   |
| Intel DG41TY        | 1        | 4.76%   |
| HP t5740            | 1        | 4.76%   |
| Gigabyte X570S      | 1        | 4.76%   |
| Gigabyte M68M-S2P   | 1        | 4.76%   |
| Gigabyte H97-Gaming | 1        | 4.76%   |
| Gigabyte H410M      | 1        | 4.76%   |
| Gigabyte G41M-ES2L  | 1        | 4.76%   |
| Foxconn p6-2010fr   | 1        | 4.76%   |
| Dell OptiPlex       | 1        | 4.76%   |
| ASUS G20AJ          | 1        | 4.76%   |
| ASUS CROSSHAIR      | 1        | 4.76%   |
| Acer Aspire         | 1        | 4.76%   |
| Unknown             | 1        | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 4        | 19.05%  |
| 2014 | 3        | 14.29%  |
| 2021 | 2        | 9.52%   |
| 2018 | 2        | 9.52%   |
| 2015 | 2        | 9.52%   |
| 2011 | 2        | 9.52%   |
| 2020 | 1        | 4.76%   |
| 2019 | 1        | 4.76%   |
| 2017 | 1        | 4.76%   |
| 2012 | 1        | 4.76%   |
| 2010 | 1        | 4.76%   |
| 2007 | 1        | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 21       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 21       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 6        | 28.57%  |
| 3.01-4.0   | 5        | 23.81%  |
| 4.01-8.0   | 3        | 14.29%  |
| 8.01-16.0  | 3        | 14.29%  |
| 1.01-2.0   | 2        | 9.52%   |
| 24.01-32.0 | 1        | 4.76%   |
| 2.01-3.0   | 1        | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 15       | 65.22%  |
| 2.01-3.0 | 3        | 13.04%  |
| 4.01-8.0 | 2        | 8.7%    |
| 0.51-1.0 | 2        | 8.7%    |
| 3.01-4.0 | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 58.33%  |
| 2      | 4        | 16.67%  |
| 4      | 3        | 12.5%   |
| 6      | 2        | 8.33%   |
| 3      | 1        | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 66.67%  |
| Yes       | 7        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 95.24%  |
| No        | 1        | 4.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 57.14%  |
| Yes       | 9        | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 76.19%  |
| Yes       | 5        | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| France       | 3        | 14.29%  |
| Brazil       | 3        | 14.29%  |
| UK           | 2        | 9.52%   |
| Indonesia    | 2        | 9.52%   |
| Argentina    | 2        | 9.52%   |
| Venezuela    | 1        | 4.76%   |
| Switzerland  | 1        | 4.76%   |
| Sweden       | 1        | 4.76%   |
| Spain        | 1        | 4.76%   |
| South Africa | 1        | 4.76%   |
| Lebanon      | 1        | 4.76%   |
| Germany      | 1        | 4.76%   |
| Czechia      | 1        | 4.76%   |
| Canada       | 1        | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Woking           | 1        | 4.55%   |
| Trelaze          | 1        | 4.55%   |
| Surabaya         | 1        | 4.55%   |
| Sin el Fil       | 1        | 4.55%   |
| San Cristóbal   | 1        | 4.55%   |
| Rosario          | 1        | 4.55%   |
| Rio de Janeiro   | 1        | 4.55%   |
| Rio Claro        | 1        | 4.55%   |
| Posadas          | 1        | 4.55%   |
| Montreuil        | 1        | 4.55%   |
| Mnisek pod Brdy  | 1        | 4.55%   |
| Kirkcaldy        | 1        | 4.55%   |
| Kage             | 1        | 4.55%   |
| Grabs            | 1        | 4.55%   |
| Fuveau           | 1        | 4.55%   |
| Frankfurt (Oder) | 1        | 4.55%   |
| Duque de Caxias  | 1        | 4.55%   |
| Dartmouth        | 1        | 4.55%   |
| Cape Town        | 1        | 4.55%   |
| Calanda          | 1        | 4.55%   |
| Bordeaux         | 1        | 4.55%   |
| Bandung          | 1        | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 27.78%  |
| Seagate             | 7        | 9      | 19.44%  |
| Samsung Electronics | 6        | 17     | 16.67%  |
| Kingston            | 3        | 3      | 8.33%   |
| Toshiba             | 2        | 2      | 5.56%   |
| Hitachi             | 2        | 2      | 5.56%   |
| XPG                 | 1        | 1      | 2.78%   |
| SanDisk             | 1        | 2      | 2.78%   |
| Intel               | 1        | 1      | 2.78%   |
| HGST                | 1        | 1      | 2.78%   |
| Gigabyte Technology | 1        | 1      | 2.78%   |
| ASMedia             | 1        | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST500LT012-1DG142 500GB         | 2        | 4.88%   |
| Samsung HD161GJ 160GB                   | 2        | 4.88%   |
| XPG GAMMIX S11 Pro 512GB                | 1        | 2.44%   |
| WDC WD800JD-08MSA1 80GB                 | 1        | 2.44%   |
| WDC WD5000AVVS-63ZWB0 500GB             | 1        | 2.44%   |
| WDC WD5000AAKS-75V0A0 500GB             | 1        | 2.44%   |
| WDC WD50 00LPLX-08ZNTT0 500GB           | 1        | 2.44%   |
| WDC WD2500AAKX-07U6AA0 250GB            | 1        | 2.44%   |
| WDC WD2500AAJS-00L7A0 250GB             | 1        | 2.44%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 2.44%   |
| WDC WD1600AAJS-08L7A0 160GB             | 1        | 2.44%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 2.44%   |
| WDC WD10EADS-00M2B0 1TB                 | 1        | 2.44%   |
| Toshiba DT01ACA100 1TB                  | 1        | 2.44%   |
| Toshiba DT01ACA050 500GB                | 1        | 2.44%   |
| Seagate ST975042 0AS 752GB              | 1        | 2.44%   |
| Seagate ST9250315AS 250GB               | 1        | 2.44%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 2.44%   |
| Seagate ST3500312CS 500GB               | 1        | 2.44%   |
| Seagate ST3320418AS 320GB               | 1        | 2.44%   |
| Seagate ST2000VM003-1ET164 2TB          | 1        | 2.44%   |
| Seagate BarraCuda Q5 ZP500CV30001 500GB | 1        | 2.44%   |
| SanDisk NVMe SSD Drive 500GB            | 1        | 2.44%   |
| Samsung SSD 850 EVO 500GB               | 1        | 2.44%   |
| Samsung SSD 850 EVO 250GB               | 1        | 2.44%   |
| Samsung SSD 840 PRO Series 512GB        | 1        | 2.44%   |
| Samsung MZVPV256HDGL-000H1 256GB        | 1        | 2.44%   |
| Samsung HN-M320MBB 320GB                | 1        | 2.44%   |
| Samsung HD753LJ 752GB                   | 1        | 2.44%   |
| Samsung HD154UI 1TB                     | 1        | 2.44%   |
| Kingston SV300S37A480G 480GB SSD        | 1        | 2.44%   |
| Kingston SA400S37120G 120GB SSD         | 1        | 2.44%   |
| Kingston SA400M8240G 240GB SSD          | 1        | 2.44%   |
| Intel SSDSA2BW120G3H 120GB              | 1        | 2.44%   |
| Hitachi HTS723232A7A364 320GB           | 1        | 2.44%   |
| Hitachi HTS543232A7A384 320GB           | 1        | 2.44%   |
| HGST HTS545050A7E380 500GB              | 1        | 2.44%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD    | 1        | 2.44%   |
| ASMedia ASM1153E 1TB                    | 1        | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 40%     |
| Seagate             | 7        | 8      | 28%     |
| Samsung Electronics | 3        | 10     | 12%     |
| Toshiba             | 2        | 2      | 8%      |
| Hitachi             | 2        | 2      | 8%      |
| HGST                | 1        | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 33.33%  |
| Kingston            | 3        | 3      | 33.33%  |
| Intel               | 1        | 1      | 11.11%  |
| Gigabyte Technology | 1        | 1      | 11.11%  |
| ASMedia             | 1        | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 33     | 62.07%  |
| SSD  | 8        | 12     | 27.59%  |
| NVMe | 3        | 5      | 10.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 42     | 84.62%  |
| NVMe | 3        | 5      | 11.54%  |
| SAS  | 1        | 3      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 31     | 76.92%  |
| 0.51-1.0   | 5        | 13     | 19.23%  |
| 1.01-2.0   | 1        | 1      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 6        | 27.27%  |
| 101-250    | 5        | 22.73%  |
| 501-1000   | 4        | 18.18%  |
| 51-100     | 3        | 13.64%  |
| 2001-3000  | 2        | 9.09%   |
| 1-20       | 1        | 4.55%   |
| Unknown    | 1        | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 11       | 50%     |
| 21-50     | 3        | 13.64%  |
| 251-500   | 2        | 9.09%   |
| 51-100    | 2        | 9.09%   |
| 101-250   | 1        | 4.55%   |
| 1001-2000 | 1        | 4.55%   |
| 501-1000  | 1        | 4.55%   |
| Unknown   | 1        | 4.55%   |

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
| Works    | 13       | 19     | 50%     |
| Detected | 9        | 27     | 34.62%  |
| Malfunc  | 4        | 4      | 15.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 12       | 46.15%  |
| AMD                      | 7        | 26.92%  |
| VIA Technologies         | 1        | 3.85%   |
| Seagate Technology       | 1        | 3.85%   |
| SanDisk                  | 1        | 3.85%   |
| Samsung Electronics      | 1        | 3.85%   |
| Nvidia                   | 1        | 3.85%   |
| Marvell Technology Group | 1        | 3.85%   |
| ADATA Technology         | 1        | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6        | 18.18%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 6.06%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1        | 3.03%   |
| VIA VT8237A SATA 2-Port Controller                                            | 1        | 3.03%   |
| Seagate Non-Volatile memory controller                                        | 1        | 3.03%   |
| SanDisk WD Blue SN570 NVMe SSD                                                | 1        | 3.03%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1        | 3.03%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 3.03%   |
| Nvidia MCP61 IDE                                                              | 1        | 3.03%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                     | 1        | 3.03%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 3.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 3.03%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1        | 3.03%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                    | 1        | 3.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 3.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1        | 3.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1        | 3.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 3.03%   |
| AMD X370 Series Chipset SATA Controller                                       | 1        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1        | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.03%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 14       | 53.85%  |
| IDE  | 7        | 26.92%  |
| NVMe | 3        | 11.54%  |
| RAID | 2        | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 61.9%   |
| AMD    | 8        | 38.1%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 1        | 4.76%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz  | 1        | 4.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 1        | 4.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 4.76%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1        | 4.76%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 1        | 4.76%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 4.76%   |
| Intel Core i5-2500 CPU @ 3.30GHz             | 1        | 4.76%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1        | 4.76%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 4.76%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 4.76%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 1        | 4.76%   |
| Intel Atom CPU N280 @ 1.66GHz                | 1        | 4.76%   |
| AMD Sempron 145 Processor                    | 1        | 4.76%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 4.76%   |
| AMD Ryzen 7 1800X Eight-Core Processor       | 1        | 4.76%   |
| AMD Ryzen 3 3100 4-Core Processor            | 1        | 4.76%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G  | 1        | 4.76%   |
| AMD Athlon II X2 B22 Processor               | 1        | 4.76%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G | 1        | 4.76%   |
| AMD A6-3600 APU with Radeon HD Graphics      | 1        | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 4        | 19.05%  |
| Intel Core i7           | 3        | 14.29%  |
| Intel Core 2 Duo        | 2        | 9.52%   |
| AMD A6                  | 2        | 9.52%   |
| Intel Pentium Gold      | 1        | 4.76%   |
| Intel Pentium Dual-Core | 1        | 4.76%   |
| Intel Core 2 Quad       | 1        | 4.76%   |
| Intel Atom              | 1        | 4.76%   |
| AMD Sempron             | 1        | 4.76%   |
| AMD Ryzen 9             | 1        | 4.76%   |
| AMD Ryzen 7             | 1        | 4.76%   |
| AMD Ryzen 3             | 1        | 4.76%   |
| AMD PRO A8              | 1        | 4.76%   |
| AMD Athlon II X2        | 1        | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 42.86%  |
| 2      | 6        | 28.57%  |
| 1      | 3        | 14.29%  |
| 12     | 1        | 4.76%   |
| 8      | 1        | 4.76%   |
| 6      | 1        | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 52.38%  |
| 2      | 10       | 47.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 20       | 95.24%  |
| 32-bit         | 1        | 4.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 19.05%  |
| 0x306c3    | 2        | 9.52%   |
| 0x0600611a | 2        | 9.52%   |
| 0xa0653    | 1        | 4.76%   |
| 0x6fd      | 1        | 4.76%   |
| 0x6fb      | 1        | 4.76%   |
| 0x506e3    | 1        | 4.76%   |
| 0x306a9    | 1        | 4.76%   |
| 0x206a7    | 1        | 4.76%   |
| 0x106e5    | 1        | 4.76%   |
| 0x1067a    | 1        | 4.76%   |
| 0x0a201016 | 1        | 4.76%   |
| 0x08701021 | 1        | 4.76%   |
| 0x08001138 | 1        | 4.76%   |
| 0x03000027 | 1        | 4.76%   |
| 0x010000c8 | 1        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 2        | 9.52%   |
| K10         | 2        | 9.52%   |
| Haswell     | 2        | 9.52%   |
| Excavator   | 2        | 9.52%   |
| Core        | 2        | 9.52%   |
| Zen 3       | 1        | 4.76%   |
| Zen 2       | 1        | 4.76%   |
| Zen         | 1        | 4.76%   |
| Skylake     | 1        | 4.76%   |
| SandyBridge | 1        | 4.76%   |
| Nehalem     | 1        | 4.76%   |
| KabyLake    | 1        | 4.76%   |
| K10 Llano   | 1        | 4.76%   |
| IvyBridge   | 1        | 4.76%   |
| CometLake   | 1        | 4.76%   |
| Bonnell     | 1        | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 10       | 43.48%  |
| Intel            | 7        | 30.43%  |
| Nvidia           | 5        | 21.74%  |
| VIA Technologies | 1        | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 8.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 8.33%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 4.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 4.17%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 4.17%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 4.17%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 4.17%   |
| Intel HD Graphics 530                                                       | 1        | 4.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 4.17%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 4.17%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 4.17%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 4.17%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 4.17%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 4.17%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 4.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 4.17%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 1        | 4.17%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 4.17%   |
| AMD Barts LE [Radeon HD 6790]                                               | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 9        | 42.86%  |
| 1 x Intel      | 6        | 28.57%  |
| 1 x Nvidia     | 4        | 19.05%  |
| 1 x VIA        | 1        | 4.76%   |
| Intel + Nvidia | 1        | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 76.19%  |
| Unknown     | 4        | 19.05%  |
| Proprietary | 1        | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 54.55%  |
| 0.51-1.0   | 3        | 13.64%  |
| 0.01-0.5   | 3        | 13.64%  |
| 7.01-8.0   | 2        | 9.09%   |
| 3.01-4.0   | 1        | 4.55%   |
| 1.01-2.0   | 1        | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 26.32%  |
| Goldstar            | 4        | 21.05%  |
| Dell                | 3        | 15.79%  |
| BenQ                | 2        | 10.53%  |
| AOC                 | 2        | 10.53%  |
| Unknown             | 1        | 5.26%   |
| Toshiba             | 1        | 5.26%   |
| JCH                 | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 4.55%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1        | 4.55%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1        | 4.55%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1        | 4.55%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1        | 4.55%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1        | 4.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 4.55%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1        | 4.55%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1        | 4.55%   |
| Goldstar TV GSM9CF6 1360x768 708x398mm 32.0-inch                     | 1        | 4.55%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1        | 4.55%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1        | 4.55%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                | 1        | 4.55%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1        | 4.55%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1        | 4.55%   |
| Dell LCD Monitor S2715H                                              | 1        | 4.55%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1        | 4.55%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1        | 4.55%   |
| BenQ FP202W BNQ76C2 1680x1050 430x270mm 20.0-inch                    | 1        | 4.55%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                     | 1        | 4.55%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                      | 1        | 4.55%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 38.1%   |
| 1280x1024 (SXGA)   | 3        | 14.29%  |
| 1366x768 (WXGA)    | 2        | 9.52%   |
| 3840x1080          | 1        | 4.76%   |
| 2288x1287          | 1        | 4.76%   |
| 1680x1050 (WSXGA+) | 1        | 4.76%   |
| 1600x900 (HD+)     | 1        | 4.76%   |
| 1360x768           | 1        | 4.76%   |
| 1280x960           | 1        | 4.76%   |
| 1024x768 (XGA)     | 1        | 4.76%   |
| Unknown            | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 20%     |
| 17      | 3        | 15%     |
| 21      | 2        | 10%     |
| 20      | 2        | 10%     |
| 18      | 2        | 10%     |
| 142     | 1        | 5%      |
| 74      | 1        | 5%      |
| 72      | 1        | 5%      |
| 24      | 1        | 5%      |
| 16      | 1        | 5%      |
| 13      | 1        | 5%      |
| Unknown | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 6        | 30%     |
| 501-600        | 5        | 25%     |
| 301-350        | 4        | 20%     |
| 1501-2000      | 2        | 10%     |
| More than 2000 | 1        | 5%      |
| 201-300        | 1        | 5%      |
| Unknown        | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 11       | 55%     |
| 5/4     | 3        | 15%     |
| 4/3     | 2        | 10%     |
| 16/10   | 2        | 10%     |
| 1.00    | 1        | 5%      |
| Unknown | 1        | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 25%     |
| 141-150        | 5        | 25%     |
| 151-200        | 4        | 20%     |
| More than 1000 | 3        | 15%     |
| 81-90          | 1        | 5%      |
| 121-130        | 1        | 5%      |
| Unknown        | 1        | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 68.42%  |
| 1-50    | 3        | 15.79%  |
| 101-120 | 2        | 10.53%  |
| Unknown | 1        | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 76.19%  |
| 2     | 3        | 14.29%  |
| 0     | 2        | 9.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 37.93%  |
| Intel                 | 5        | 17.24%  |
| Ralink Technology     | 3        | 10.34%  |
| Qualcomm Atheros      | 3        | 10.34%  |
| Broadcom Limited      | 2        | 6.9%    |
| VIA Technologies      | 1        | 3.45%   |
| TP-Link               | 1        | 3.45%   |
| Nvidia                | 1        | 3.45%   |
| D-Link System         | 1        | 3.45%   |
| Broadcom              | 1        | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 8        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 6.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 3.13%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 3.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 3.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 3.13%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 3.13%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 3.13%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 3.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 3.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 3.13%   |
| Nvidia MCP61 Ethernet                                                                       | 1        | 3.13%   |
| Intel Wireless 8260                                                                         | 1        | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 3.13%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 3.13%   |
| Intel Ethernet Controller I225-V                                                            | 1        | 3.13%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1        | 3.13%   |
| Intel Ethernet Connection (2) I218-V                                                        | 1        | 3.13%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 3.13%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 3.13%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1        | 3.13%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1        | 3.13%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1        | 3.13%   |

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
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 9.09%   |
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
| Realtek Semiconductor | 10       | 47.62%  |
| Intel                 | 5        | 23.81%  |
| Broadcom Limited      | 2        | 9.52%   |
| VIA Technologies      | 1        | 4.76%   |
| Qualcomm Atheros      | 1        | 4.76%   |
| Nvidia                | 1        | 4.76%   |
| Broadcom              | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 38.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 9.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 4.76%   |
| Nvidia MCP61 Ethernet                                             | 1        | 4.76%   |
| Intel I211 Gigabit Network Connection                             | 1        | 4.76%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 4.76%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.76%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 4.76%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 4.76%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 4.76%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1        | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 66.67%  |
| WiFi     | 10       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 66.67%  |
| WiFi     | 8        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 76.19%  |
| 2     | 5        | 23.81%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 90.48%  |
| Yes  | 2        | 9.52%   |

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
| Intel               | 12       | 38.71%  |
| AMD                 | 11       | 35.48%  |
| Nvidia              | 5        | 16.13%  |
| VIA Technologies    | 1        | 3.23%   |
| Plantronics         | 1        | 3.23%   |
| C-Media Electronics | 1        | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 5.26%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 5.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 5.26%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 5.26%   |
| AMD FCH Azalia Controller                                                  | 2        | 5.26%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 2        | 5.26%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 2.63%   |
| Plantronics USB DSP v4 Audio Interface                                     | 1        | 2.63%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.63%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.63%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.63%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.63%   |
| C-Media Electronics USB Audio Device                                       | 1        | 2.63%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.63%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 2.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.63%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2.63%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]      | 1        | 2.63%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 2.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 28.57%  |
| Kingston            | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| Corsair             | 2        | 14.29%  |
| G.Skill             | 1        | 7.14%   |
| Crucial             | 1        | 7.14%   |
| Avant               | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2        | 14.29%  |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 7.14%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 7.14%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 1        | 7.14%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s | 1        | 7.14%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s            | 1        | 7.14%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 1        | 7.14%   |
| Kingston RAM 99U5471-030.A00LF 8192MB DIMM DDR3 1333MT/s | 1        | 7.14%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 1        | 7.14%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 1        | 7.14%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s   | 1        | 7.14%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4             | 1        | 7.14%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s         | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 42.86%  |
| DDR4    | 4        | 28.57%  |
| Unknown | 2        | 14.29%  |
| SDRAM   | 1        | 7.14%   |
| DDR2    | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 11       | 78.57%  |
| SODIMM | 3        | 21.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 50%     |
| 2048  | 3        | 21.43%  |
| 4096  | 2        | 14.29%  |
| 16384 | 1        | 7.14%   |
| 1024  | 1        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 28.57%  |
| 800     | 3        | 21.43%  |
| 3666    | 1        | 7.14%   |
| 3200    | 1        | 7.14%   |
| 2666    | 1        | 7.14%   |
| 2400    | 1        | 7.14%   |
| 2133    | 1        | 7.14%   |
| 1333    | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

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
| Logitech            | 2        | 40%     |
| Samsung Electronics | 1        | 20%     |
| Guillemot           | 1        | 20%     |
| Unknown             | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)             | 1        | 20%     |
| Logitech Webcam C270                | 1        | 20%     |
| Logitech QuickCam Notebook Pro      | 1        | 20%     |
| Guillemot Hercules Dualpix Exchange | 1        | 20%     |
| Unknown                             | 1        | 20%     |

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
| 0     | 14       | 66.67%  |
| 1     | 6        | 28.57%  |
| 2     | 1        | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 62.5%   |
| Net/wireless  | 2        | 25%     |
| Camera        | 1        | 12.5%   |

