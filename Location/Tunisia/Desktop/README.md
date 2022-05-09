Linux in Tunisia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Tunisia.

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

Total: 41

| Vendor   | Model                 | Probe                                                      | Date         |
|----------|-----------------------|------------------------------------------------------------|--------------|
| MSI      | H81M-P33              | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| MSI      | B550M PRO-VDH         | [9597b0a2d9](https://linux-hardware.org/?probe=9597b0a2d9) | Apr 09, 2022 |
| ASUSTek  | PRIME B450M-K         | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Intel    | H61                   | [6d80839afa](https://linux-hardware.org/?probe=6d80839afa) | Feb 09, 2022 |
| ASUSTek  | PRIME B450M-K         | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek  | PRIME B450M-K         | [f56c7ea90a](https://linux-hardware.org/?probe=f56c7ea90a) | Jan 29, 2022 |
| ASUSTek  | PRIME B450M-K         | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASUSTek  | PRIME B450M-K         | [23f6223c1a](https://linux-hardware.org/?probe=23f6223c1a) | Jan 19, 2022 |
| ASUSTek  | PRIME B450M-K         | [bd9fb4fcc1](https://linux-hardware.org/?probe=bd9fb4fcc1) | Jan 17, 2022 |
| ASUSTek  | PRIME B450M-K         | [869a119983](https://linux-hardware.org/?probe=869a119983) | Jan 17, 2022 |
| ASUSTek  | PRIME B450M-K         | [b9999bcf7a](https://linux-hardware.org/?probe=b9999bcf7a) | Jan 17, 2022 |
| MSI      | H110M PRO-VD PLUS     | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| Gigabyte | B75M-D3H              | [b882e1c0f7](https://linux-hardware.org/?probe=b882e1c0f7) | Sep 22, 2021 |
| HP       | 1494                  | [ae5165603a](https://linux-hardware.org/?probe=ae5165603a) | Sep 09, 2021 |
| HP       | 1494                  | [62e74e0c1a](https://linux-hardware.org/?probe=62e74e0c1a) | Sep 09, 2021 |
| Lenovo   | SHARKBAY NOK          | [e57d0a5518](https://linux-hardware.org/?probe=e57d0a5518) | Sep 01, 2021 |
| Dell     | 0M5DCD A00            | [77faf70869](https://linux-hardware.org/?probe=77faf70869) | Jun 14, 2021 |
| Lenovo   | 3138 NO DPK           | [8488c59a11](https://linux-hardware.org/?probe=8488c59a11) | May 18, 2021 |
| ASUSTek  | PRIME B450M-K         | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| ASUSTek  | PRIME B450M-K         | [0df80890c0](https://linux-hardware.org/?probe=0df80890c0) | May 17, 2021 |
| ASUSTek  | PRIME B450M-K         | [6bfaa47826](https://linux-hardware.org/?probe=6bfaa47826) | May 13, 2021 |
| ASUSTek  | PRIME B450M-K         | [77a0428e6b](https://linux-hardware.org/?probe=77a0428e6b) | May 13, 2021 |
| ASUSTek  | PRIME B450M-K         | [88e106999e](https://linux-hardware.org/?probe=88e106999e) | May 11, 2021 |
| ASUSTek  | PRIME B450M-K         | [2b14268533](https://linux-hardware.org/?probe=2b14268533) | May 10, 2021 |
| ASUSTek  | PRIME B450M-K         | [d7ab2def9e](https://linux-hardware.org/?probe=d7ab2def9e) | May 01, 2021 |
| ASUSTek  | PRIME B450M-K         | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Dell     | 0TTDMJ A00            | [aef24f2346](https://linux-hardware.org/?probe=aef24f2346) | Oct 28, 2020 |
| ASUSTek  | M32CD_A_F_K20CD_K31CD | [cdce66a7de](https://linux-hardware.org/?probe=cdce66a7de) | Jul 07, 2020 |
| Foxconn  | 2ABF                  | [65d6dca78e](https://linux-hardware.org/?probe=65d6dca78e) | May 27, 2020 |
| MSI      | MS-7502 Fab D         | [242c5b8d0d](https://linux-hardware.org/?probe=242c5b8d0d) | Mar 30, 2020 |
| Foxconn  | 2ABF                  | [7c6e2d2c29](https://linux-hardware.org/?probe=7c6e2d2c29) | Mar 10, 2020 |
| Pegatron | Eureka3               | [77bc52c3d9](https://linux-hardware.org/?probe=77bc52c3d9) | Mar 02, 2020 |
| Pegatron | Eureka3               | [84ee26b4e7](https://linux-hardware.org/?probe=84ee26b4e7) | Mar 02, 2020 |
| Pegatron | Eureka3               | [33ae5ebabc](https://linux-hardware.org/?probe=33ae5ebabc) | Feb 18, 2020 |
| Lenovo   | 3138 NO DPK           | [7878eb9e27](https://linux-hardware.org/?probe=7878eb9e27) | Dec 30, 2019 |
| Lenovo   | 3138 NO DPK           | [21f916c3ef](https://linux-hardware.org/?probe=21f916c3ef) | Dec 30, 2019 |
| Unknown  | Pine Trail - M CRB    | [ef1e6295a8](https://linux-hardware.org/?probe=ef1e6295a8) | Oct 30, 2019 |
| Foxconn  | 2ABF                  | [4521f814c9](https://linux-hardware.org/?probe=4521f814c9) | Sep 17, 2019 |
| Foxconn  | 2ABF                  | [6a57b2ea85](https://linux-hardware.org/?probe=6a57b2ea85) | Sep 17, 2019 |
| Pegatron | 2A94h                 | [3b6656bb11](https://linux-hardware.org/?probe=3b6656bb11) | Jul 04, 2019 |
| Foxconn  | 2ABF                  | [f6873739a8](https://linux-hardware.org/?probe=f6873739a8) | Mar 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 18.04      | 4        | 19.05%  |
| Ubuntu 20.04      | 3        | 14.29%  |
| OpenMandriva 4.2  | 3        | 14.29%  |
| Ubuntu 19.10      | 2        | 9.52%   |
| Ubuntu 21.10      | 1        | 4.76%   |
| Ubuntu 19.04      | 1        | 4.76%   |
| Ubuntu 16.04      | 1        | 4.76%   |
| ROSA R10          | 1        | 4.76%   |
| OpenMandriva 4.3  | 1        | 4.76%   |
| Gentoo 2.7        | 1        | 4.76%   |
| Debian 11         | 1        | 4.76%   |
| ArcoLinux Rolling | 1        | 4.76%   |
| Arch              | 1        | 4.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 10       | 52.63%  |
| OpenMandriva | 4        | 21.05%  |
| ROSA         | 1        | 5.26%   |
| Gentoo       | 1        | 5.26%   |
| Debian       | 1        | 5.26%   |
| ArcoLinux    | 1        | 5.26%   |
| Arch         | 1        | 5.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 3        | 12.5%   |
| 5.9.1-arch1-1                   | 1        | 4.17%   |
| 5.4.0-73-generic                | 1        | 4.17%   |
| 5.4.0-40-generic                | 1        | 4.17%   |
| 5.4.0-31-generic                | 1        | 4.17%   |
| 5.3.0-40-generic                | 1        | 4.17%   |
| 5.3.0-26-generic                | 1        | 4.17%   |
| 5.3.0-19-generic                | 1        | 4.17%   |
| 5.16.7-desktop-1omv4003         | 1        | 4.17%   |
| 5.15.5-arch1-1                  | 1        | 4.17%   |
| 5.15.11-gentoo                  | 1        | 4.17%   |
| 5.13.0-39-generic               | 1        | 4.17%   |
| 5.11.0-27-generic               | 1        | 4.17%   |
| 5.10.76-gentoo-r1               | 1        | 4.17%   |
| 5.10.27-gentoo                  | 1        | 4.17%   |
| 5.10.0-12-amd64                 | 1        | 4.17%   |
| 5.0.0-13-generic                | 1        | 4.17%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 1        | 4.17%   |
| 4.4.0-176-generic               | 1        | 4.17%   |
| 4.18.0-25-generic               | 1        | 4.17%   |
| 4.15.0-91-generic               | 1        | 4.17%   |
| 4.15.0-89-generic               | 1        | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 3        | 12.5%   |
| 5.3.0   | 3        | 12.5%   |
| 5.10.14 | 3        | 12.5%   |
| 4.15.0  | 2        | 8.33%   |
| 5.9.1   | 1        | 4.17%   |
| 5.16.7  | 1        | 4.17%   |
| 5.15.5  | 1        | 4.17%   |
| 5.15.11 | 1        | 4.17%   |
| 5.13.0  | 1        | 4.17%   |
| 5.11.0  | 1        | 4.17%   |
| 5.10.76 | 1        | 4.17%   |
| 5.10.27 | 1        | 4.17%   |
| 5.10.0  | 1        | 4.17%   |
| 5.0.0   | 1        | 4.17%   |
| 4.9.60  | 1        | 4.17%   |
| 4.4.0   | 1        | 4.17%   |
| 4.18.0  | 1        | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 5        | 21.74%  |
| 5.4     | 3        | 13.04%  |
| 5.3     | 3        | 13.04%  |
| 5.15    | 2        | 8.7%    |
| 4.15    | 2        | 8.7%    |
| 5.9     | 1        | 4.35%   |
| 5.16    | 1        | 4.35%   |
| 5.13    | 1        | 4.35%   |
| 5.11    | 1        | 4.35%   |
| 5.0     | 1        | 4.35%   |
| 4.9     | 1        | 4.35%   |
| 4.4     | 1        | 4.35%   |
| 4.18    | 1        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 18       | 94.74%  |
| i686   | 1        | 5.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 8        | 38.1%   |
| Unknown         | 5        | 23.81%  |
| KDE5            | 4        | 19.05%  |
| KDE4            | 1        | 4.76%   |
| i3              | 1        | 4.76%   |
| GNOME Flashback | 1        | 4.76%   |
| Cinnamon        | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 15       | 78.95%  |
| Wayland | 3        | 15.79%  |
| Tty     | 1        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 50%     |
| SDDM    | 5        | 25%     |
| GDM     | 3        | 15%     |
| KDM     | 1        | 5%      |
| GDM3    | 1        | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| fr_FR   | 7        | 35%     |
| en_US   | 6        | 30%     |
| Unknown | 4        | 20%     |
| en_AG   | 1        | 5%      |
| de_DE   | 1        | 5%      |
| ar_TN   | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 60%     |
| EFI  | 8        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 14       | 73.68%  |
| Overlay | 4        | 21.05%  |
| Unknown | 1        | 5.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 60%     |
| GPT     | 7        | 35%     |
| MBR     | 1        | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 78.95%  |
| Yes       | 4        | 21.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11       | 57.89%  |
| No        | 8        | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 4        | 21.05%  |
| Pegatron            | 3        | 15.79%  |
| Lenovo              | 2        | 10.53%  |
| Foxconn             | 2        | 10.53%  |
| Dell                | 2        | 10.53%  |
| ASUSTek Computer    | 2        | 10.53%  |
| Intel               | 1        | 5.26%   |
| Hewlett-Packard     | 1        | 5.26%   |
| Gigabyte Technology | 1        | 5.26%   |
| Unknown             | 1        | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Pegatron VS342AA-AB6 m9801af        | 2        | 10.53%  |
| Foxconn Pro 3400 Series MT          | 2        | 10.53%  |
| Pegatron Pro 3010 Microtower PC     | 1        | 5.26%   |
| MSI MS-7C95                         | 1        | 5.26%   |
| MSI MS-7A15                         | 1        | 5.26%   |
| MSI MS-7817                         | 1        | 5.26%   |
| MSI MS-7502                         | 1        | 5.26%   |
| Lenovo ThinkStation P330 30C6S33L00 | 1        | 5.26%   |
| Lenovo H50-50 90B70040AL            | 1        | 5.26%   |
| Intel H61                           | 1        | 5.26%   |
| HP Compaq 8200 Elite CMT PC         | 1        | 5.26%   |
| Gigabyte B75M-D3H                   | 1        | 5.26%   |
| Dell OptiPlex 390                   | 1        | 5.26%   |
| Dell OptiPlex 3040                  | 1        | 5.26%   |
| ASUS PRIME B450M-K                  | 1        | 5.26%   |
| ASUS M32CD_A_F_K20CD_K31CD          | 1        | 5.26%   |
| Unknown                             | 1        | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Pegatron VS342AA-AB6 | 2        | 10.53%  |
| Foxconn Pro          | 2        | 10.53%  |
| Dell OptiPlex        | 2        | 10.53%  |
| Pegatron Pro         | 1        | 5.26%   |
| MSI MS-7C95          | 1        | 5.26%   |
| MSI MS-7A15          | 1        | 5.26%   |
| MSI MS-7817          | 1        | 5.26%   |
| MSI MS-7502          | 1        | 5.26%   |
| Lenovo ThinkStation  | 1        | 5.26%   |
| Lenovo H50-50        | 1        | 5.26%   |
| Intel H61            | 1        | 5.26%   |
| HP Compaq            | 1        | 5.26%   |
| Gigabyte B75M-D3H    | 1        | 5.26%   |
| ASUS PRIME           | 1        | 5.26%   |
| ASUS M32CD           | 1        | 5.26%   |
| Unknown              | 1        | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 4        | 21.05%  |
| 2016 | 3        | 15.79%  |
| 2009 | 3        | 15.79%  |
| 2012 | 2        | 10.53%  |
| 2020 | 1        | 5.26%   |
| 2019 | 1        | 5.26%   |
| 2018 | 1        | 5.26%   |
| 2017 | 1        | 5.26%   |
| 2015 | 1        | 5.26%   |
| 2013 | 1        | 5.26%   |
| 2007 | 1        | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 19       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 19       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 5        | 26.32%  |
| 1.01-2.0   | 5        | 26.32%  |
| 3.01-4.0   | 3        | 15.79%  |
| 16.01-24.0 | 3        | 15.79%  |
| 8.01-16.0  | 3        | 15.79%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 11       | 47.83%  |
| 2.01-3.0  | 4        | 17.39%  |
| 4.01-8.0  | 2        | 8.7%    |
| 0.51-1.0  | 2        | 8.7%    |
| 0.01-0.5  | 2        | 8.7%    |
| 3.01-4.0  | 1        | 4.35%   |
| 8.01-16.0 | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 65%     |
| 2      | 5        | 25%     |
| 4      | 1        | 5%      |
| 0      | 1        | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 52.63%  |
| No        | 9        | 47.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 50%     |
| No        | 10       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 78.95%  |
| Yes       | 4        | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Tunisia | 19       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Tunis           | 7        | 30.43%  |
| Manouba         | 2        | 8.7%    |
| Aryanah         | 2        | 8.7%    |
| Sousse          | 1        | 4.35%   |
| Rades           | 1        | 4.35%   |
| Nabeul          | 1        | 4.35%   |
| Moknine         | 1        | 4.35%   |
| Jendouba        | 1        | 4.35%   |
| Hammamet        | 1        | 4.35%   |
| Cite Bouzaiene  | 1        | 4.35%   |
| Cite 18 Janvier | 1        | 4.35%   |
| Carthage        | 1        | 4.35%   |
| Bizerte         | 1        | 4.35%   |
| Beja            | 1        | 4.35%   |
| As Sanad        | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 10     | 33.33%  |
| Seagate             | 7        | 12     | 29.17%  |
| Toshiba             | 2        | 2      | 8.33%   |
| Team                | 1        | 1      | 4.17%   |
| Sandisk             | 1        | 2      | 4.17%   |
| Samsung Electronics | 1        | 1      | 4.17%   |
| Kingston            | 1        | 1      | 4.17%   |
| HGST                | 1        | 1      | 4.17%   |
| EMTEC               | 1        | 3      | 4.17%   |
| addlink             | 1        | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD10EADS-65M2B0 1TB              | 2        | 7.41%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 7.41%   |
| WDC WD5000AVDS-63U7B1 500GB          | 1        | 3.7%    |
| WDC WD5000AAKS-402AA0 500GB          | 1        | 3.7%    |
| WDC WD5000AACS-00ZUB0 500GB          | 1        | 3.7%    |
| WDC WD3200AAJS-60M0A1 320GB          | 1        | 3.7%    |
| WDC WD2500AAJS-75M0A0 249GB          | 1        | 3.7%    |
| WDC WD10PURZ-85U8XY0 1TB             | 1        | 3.7%    |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 3.7%    |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1        | 3.7%    |
| Toshiba DT01ACA100 1TB               | 1        | 3.7%    |
| Toshiba DT01ACA050 500GB             | 1        | 3.7%    |
| Team T253X1240G 240GB SSD            | 1        | 3.7%    |
| Seagate ST500DM002-1SB10A 500GB      | 1        | 3.7%    |
| Seagate ST500DM002-1BD142 500GB      | 1        | 3.7%    |
| Seagate ST3500413AS 500GB            | 1        | 3.7%    |
| Seagate ST3320813AS 320GB            | 1        | 3.7%    |
| Seagate ST1000DM003-1SB102 1TB       | 1        | 3.7%    |
| Seagate ST1000DM003-1ER162 1TB       | 1        | 3.7%    |
| Sandisk NVMe SSD Drive 512GB         | 1        | 3.7%    |
| Samsung SSD 980 500GB                | 1        | 3.7%    |
| Kingston SV300S37A120G 120GB SSD     | 1        | 3.7%    |
| HGST HTS545050A7E380 500GB           | 1        | 3.7%    |
| EMTEC X250 512GB SSD                 | 1        | 3.7%    |
| addlink SATA SSD 256GB               | 1        | 3.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 9      | 41.18%  |
| Seagate | 7        | 12     | 41.18%  |
| Toshiba | 2        | 2      | 11.76%  |
| HGST    | 1        | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Team     | 1        | 1      | 25%     |
| Kingston | 1        | 1      | 25%     |
| EMTEC    | 1        | 3      | 25%     |
| addlink  | 1        | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 24     | 72.73%  |
| SSD  | 4        | 6      | 18.18%  |
| NVMe | 2        | 4      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 30     | 90%     |
| NVMe | 2        | 4      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 16     | 68.42%  |
| 0.51-1.0   | 6        | 14     | 31.58%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 7        | 35%     |
| 251-500    | 5        | 25%     |
| 501-1000   | 3        | 15%     |
| 21-50      | 2        | 10%     |
| 1001-2000  | 1        | 5%      |
| 51-100     | 1        | 5%      |
| Unknown    | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 11       | 47.83%  |
| 21-50    | 5        | 21.74%  |
| 51-100   | 3        | 13.04%  |
| 251-500  | 1        | 4.35%   |
| 101-250  | 1        | 4.35%   |
| 501-1000 | 1        | 4.35%   |
| Unknown  | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Desktops | Drives | Percent |
|----------------------------|----------|--------|---------|
| Seagate ST3500413AS 500GB  | 1        | 1      | 25%     |
| Seagate ST3320813AS 320GB  | 1        | 1      | 25%     |
| HGST HTS545050A7E380 500GB | 1        | 1      | 25%     |
| EMTEC X250 512GB SSD       | 1        | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 50%     |
| HGST    | 1        | 1      | 25%     |
| EMTEC   | 1        | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| HGST    | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 75%     |
| SSD  | 1        | 2      | 25%     |

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
| Detected | 9        | 16     | 42.86%  |
| Works    | 8        | 13     | 38.1%   |
| Malfunc  | 4        | 5      | 19.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 17       | 80.95%  |
| AMD                 | 2        | 9.52%   |
| Sandisk             | 1        | 4.76%   |
| Samsung Electronics | 1        | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 11.11%  |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 11.11%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 11.11%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 11.11%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 7.41%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 3.7%    |
| Samsung NVMe SSD Controller 980                                                         | 1        | 3.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 3.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 3.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 3.7%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 3.7%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 3.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 10       | 47.62%  |
| IDE  | 9        | 42.86%  |
| NVMe | 2        | 9.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 89.47%  |
| AMD    | 2        | 10.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 10.53%  |
| Intel Xeon E-2144G CPU @ 3.60GHz            | 1        | 5.26%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 5.26%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 5.26%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 5.26%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 5.26%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 5.26%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 5.26%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 5.26%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 5.26%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 5.26%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 5.26%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 5.26%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 5.26%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 5.26%   |
| Intel Atom CPU N455 @ 1.66GHz               | 1        | 5.26%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 1        | 5.26%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 1        | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium           | 4        | 21.05%  |
| Intel Core i3           | 4        | 21.05%  |
| Intel Core 2 Quad       | 3        | 15.79%  |
| Intel Core i7           | 2        | 10.53%  |
| AMD Ryzen 5             | 2        | 10.53%  |
| Intel Xeon              | 1        | 5.26%   |
| Intel Pentium Dual-Core | 1        | 5.26%   |
| Intel Core i5           | 1        | 5.26%   |
| Intel Atom              | 1        | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 8        | 42.11%  |
| 4       | 7        | 36.84%  |
| 6       | 2        | 10.53%  |
| 1       | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 11       | 55%     |
| 1       | 8        | 40%     |
| Unknown | 1        | 5%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 19       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 5        | 23.81%  |
| 0x1067a    | 3        | 14.29%  |
| Unknown    | 3        | 14.29%  |
| 0x506e3    | 2        | 9.52%   |
| 0x906ea    | 1        | 4.76%   |
| 0x906e9    | 1        | 4.76%   |
| 0x6fb      | 1        | 4.76%   |
| 0x306c3    | 1        | 4.76%   |
| 0x306a9    | 1        | 4.76%   |
| 0x106ca    | 1        | 4.76%   |
| 0x08701013 | 1        | 4.76%   |
| 0x00000000 | 1        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 5        | 26.32%  |
| Penryn      | 3        | 15.79%  |
| Skylake     | 2        | 10.53%  |
| KabyLake    | 2        | 10.53%  |
| Haswell     | 2        | 10.53%  |
| Zen 3       | 1        | 5.26%   |
| Zen 2       | 1        | 5.26%   |
| IvyBridge   | 1        | 5.26%   |
| Core        | 1        | 5.26%   |
| Bonnell     | 1        | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 10       | 47.62%  |
| Nvidia | 9        | 42.86%  |
| AMD    | 2        | 9.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [GeForce 210]                                                  | 3        | 14.29%  |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 14.29%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 9.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 4.76%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 4.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 4.76%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 4.76%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 4.76%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4.76%   |
| Intel HD Graphics 530                                                       | 1        | 4.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 1        | 4.76%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 4.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 4.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 4.76%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 9        | 47.37%  |
| 1 x Intel  | 8        | 42.11%  |
| 1 x AMD    | 2        | 10.53%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 80%     |
| Proprietary | 3        | 15%     |
| Unknown     | 1        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 42.86%  |
| 1.01-2.0   | 6        | 28.57%  |
| 0.51-1.0   | 3        | 14.29%  |
| 5.01-6.0   | 2        | 9.52%   |
| 3.01-4.0   | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 31.82%  |
| Hewlett-Packard     | 6        | 27.27%  |
| S2-Tek              | 1        | 4.55%   |
| PKB                 | 1        | 4.55%   |
| Philips             | 1        | 4.55%   |
| Packard Bell        | 1        | 4.55%   |
| Medion              | 1        | 4.55%   |
| Lenovo              | 1        | 4.55%   |
| Dell                | 1        | 4.55%   |
| BenQ                | 1        | 4.55%   |
| AU Optronics        | 1        | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch          | 2        | 8.7%    |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch | 1        | 4.35%   |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch | 1        | 4.35%   |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch    | 1        | 4.35%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1        | 4.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 1        | 4.35%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch     | 1        | 4.35%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 1        | 4.35%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                      | 1        | 4.35%   |
| PKB LCD Monitor VIS220WS 1680x1050                                   | 1        | 4.35%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1        | 4.35%   |
| Packard Bell PKB VIS220WS PKB5064 1680x1050 460x290mm 21.4-inch      | 1        | 4.35%   |
| Medion MD30422PV MED86F6 1680x1050 474x296mm 22.0-inch               | 1        | 4.35%   |
| Lenovo T24v-10 LEN61BC 1920x1080 527x296mm 23.8-inch                 | 1        | 4.35%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch           | 1        | 4.35%   |
| Hewlett-Packard LE2001w HWP2841 1600x900 442x249mm 20.0-inch         | 1        | 4.35%   |
| Hewlett-Packard LCD Monitor 2011 1600x900                            | 1        | 4.35%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch            | 1        | 4.35%   |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch            | 1        | 4.35%   |
| Dell S2721HGF DEL41E8 1920x1080 597x336mm 27.0-inch                  | 1        | 4.35%   |
| BenQ BenQT221W BNQ7719 1680x1050 473x296mm 22.0-inch                 | 1        | 4.35%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch        | 1        | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 7        | 35%     |
| 1600x900 (HD+)     | 6        | 30%     |
| 1680x1050 (WSXGA+) | 3        | 15%     |
| 1366x768 (WXGA)    | 2        | 10%     |
| 1280x1024 (SXGA)   | 1        | 5%      |
| 1024x600           | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 20      | 5        | 22.73%  |
| 21      | 3        | 13.64%  |
| 24      | 2        | 9.09%   |
| 23      | 2        | 9.09%   |
| 22      | 2        | 9.09%   |
| Unknown | 2        | 9.09%   |
| 42      | 1        | 4.55%   |
| 27      | 1        | 4.55%   |
| 19      | 1        | 4.55%   |
| 18      | 1        | 4.55%   |
| 17      | 1        | 4.55%   |
| 10      | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 11       | 55%     |
| 501-600     | 4        | 20%     |
| Unknown     | 2        | 10%     |
| 301-350     | 1        | 5%      |
| 201-300     | 1        | 5%      |
| 901-1000    | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 15       | 71.43%  |
| 16/10   | 3        | 14.29%  |
| Unknown | 2        | 9.52%   |
| 5/4     | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 36.36%  |
| 151-200        | 7        | 31.82%  |
| 141-150        | 2        | 9.09%   |
| Unknown        | 2        | 9.09%   |
| 41-50          | 1        | 4.55%   |
| 301-350        | 1        | 4.55%   |
| 501-1000       | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 75%     |
| 101-120 | 3        | 15%     |
| Unknown | 2        | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 84.21%  |
| 2     | 3        | 15.79%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 58.62%  |
| Intel                 | 4        | 13.79%  |
| Ralink Technology     | 3        | 10.34%  |
| Ralink                | 3        | 10.34%  |
| Samsung Electronics   | 1        | 3.45%   |
| IMC Networks          | 1        | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 15       | 45.45%  |
| Ralink MT7601U Wireless Adapter                                        | 3        | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 6.06%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 6.06%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 3.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 3.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 3.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 3.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 3.03%   |
| Intel Wireless 7265                                                    | 1        | 3.03%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 3.03%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 3.03%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1        | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 27.27%  |
| Ralink Technology     | 3        | 27.27%  |
| Ralink                | 3        | 27.27%  |
| Intel                 | 1        | 9.09%   |
| IMC Networks          | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                        | 3        | 27.27%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 18.18%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 9.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 9.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 9.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1        | 9.09%   |
| Intel Wireless 7265                                                    | 1        | 9.09%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 80.95%  |
| Intel                 | 3        | 14.29%  |
| Samsung Electronics   | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15       | 68.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 9.09%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 4.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.55%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 65.52%  |
| WiFi     | 10       | 34.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 66.67%  |
| WiFi     | 7        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 63.16%  |
| 2     | 7        | 36.84%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Ralink                  | 1        | 25%     |
| Intel                   | 1        | 25%     |
| IMC Networks            | 1        | 25%     |
| Cambridge Silicon Radio | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Ralink RT3290 Bluetooth                             | 1        | 25%     |
| Intel Bluetooth wireless interface                  | 1        | 25%     |
| IMC Networks Bluetooth Radio                        | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 54.84%  |
| Nvidia | 9        | 29.03%  |
| AMD    | 4        | 12.9%   |
| Lenovo | 1        | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 15.63%  |
| Nvidia High Definition Audio Controller                                           | 3        | 9.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 9.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 9.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 6.25%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 6.25%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 3.13%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 3.13%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 3.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 3.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 3.13%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 3.13%   |
| Lenovo ThinkVision T24v Wide Monitor for USB-Audio                                | 1        | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 3.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 3.13%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 20%     |
| Samsung Electronics | 3        | 20%     |
| SK Hynix            | 2        | 13.33%  |
| TwinMOS             | 1        | 6.67%   |
| Team                | 1        | 6.67%   |
| Patriot             | 1        | 6.67%   |
| Micron Technology   | 1        | 6.67%   |
| GOODRAM             | 1        | 6.67%   |
| Elpida              | 1        | 6.67%   |
| Unknown             | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 1        | 6.67%   |
| Unknown RAM Module 4GB DIMM DDR3                       | 1        | 6.67%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 1        | 6.67%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s       | 1        | 6.67%   |
| Team RAM TEAMGROUP-UD4-2400 16384MB DIMM DDR4 2400MT/s | 1        | 6.67%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1333MT/s          | 1        | 6.67%   |
| SK Hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s  | 1        | 6.67%   |
| Samsung RAM Module 4096MB DIMM DDR3 1333MT/s           | 1        | 6.67%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s    | 1        | 6.67%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 6.67%   |
| Patriot RAM 3000 C15 Series 8GB DIMM DDR4 3000MT/s     | 1        | 6.67%   |
| Micron RAM 8JTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s | 1        | 6.67%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s     | 1        | 6.67%   |
| Elpida RAM HMT451S6AFR8C-H9 4GB DIMM DDR3              | 1        | 6.67%   |
| Unknown                                                | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 50%     |
| DDR4    | 4        | 33.33%  |
| SDRAM   | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 11       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 4        | 33.33%  |
| 2048  | 3        | 25%     |
| 16384 | 2        | 16.67%  |
| 8192  | 2        | 16.67%  |
| 1024  | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 4        | 33.33%  |
| 1600    | 2        | 16.67%  |
| 3200    | 1        | 8.33%   |
| 3000    | 1        | 8.33%   |
| 2667    | 1        | 8.33%   |
| 2400    | 1        | 8.33%   |
| 667     | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP LaserJet P1005      | 1        | 50%     |
| HP DeskJet 5810 series | 1        | 50%     |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Syntek     | 1        | 50%     |
| Cubeternet | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Syntek Integrated RGB Camera | 1        | 50%     |
| Cubeternet WebCam            | 1        | 50%     |

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
| 0     | 17       | 77.27%  |
| 1     | 3        | 13.64%  |
| 3     | 1        | 4.55%   |
| 2     | 1        | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 40%     |
| Net/wireless  | 1        | 20%     |
| Net/ethernet  | 1        | 20%     |
| Bluetooth     | 1        | 20%     |

