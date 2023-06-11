BigLinux - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for BigLinux.

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

Total: 38

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Toshiba       | STI 005492G              | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| MSI           | MAG B550 TOMAHAWK        | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| HP            | 1495                     | [96283c0a09](https://linux-hardware.org/?probe=96283c0a09) | Apr 01, 2023 |
| HP            | 1495                     | [f25125625a](https://linux-hardware.org/?probe=f25125625a) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI       | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| HP            | 3397                     | [0b74e11cdd](https://linux-hardware.org/?probe=0b74e11cdd) | Mar 12, 2023 |
| HP            | 1495                     | [058beaa7d1](https://linux-hardware.org/?probe=058beaa7d1) | Mar 12, 2023 |
| HP            | 1495                     | [517a7a6401](https://linux-hardware.org/?probe=517a7a6401) | Mar 12, 2023 |
| Lenovo        | NOK                      | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS ELITE        | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| Intel         | H61                      | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE        | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN     | [7c6973f1fa](https://linux-hardware.org/?probe=7c6973f1fa) | Feb 21, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF     | [4bcfe32668](https://linux-hardware.org/?probe=4bcfe32668) | Feb 12, 2023 |
| Intel         | H61                      | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| BESSTAR Te... | HM90                     | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| Intel         | H55                      | [4fdea85eec](https://linux-hardware.org/?probe=4fdea85eec) | Jan 14, 2023 |
| Intel         | H55                      | [d875a18037](https://linux-hardware.org/?probe=d875a18037) | Jan 14, 2023 |
| Gigabyte      | Z87-HD3                  | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Gigabyte      | Z87-HD3                  | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S   | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| eMachines     | EMCP61M                  | [711594c5b4](https://linux-hardware.org/?probe=711594c5b4) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S   | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S   | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| Intel         | DH61WW AAG23116-203      | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| ASUSTek       | Z87M-PLUS                | [0efc94e34d](https://linux-hardware.org/?probe=0efc94e34d) | Jul 24, 2022 |
| Intel         | DH61WW AAG23116-203      | [cfd6e87e09](https://linux-hardware.org/?probe=cfd6e87e09) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                | [c30806c628](https://linux-hardware.org/?probe=c30806c628) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                | [b805fa0cd8](https://linux-hardware.org/?probe=b805fa0cd8) | Jul 23, 2022 |
| ECS           | H67H2-M2                 | [d82e4c4eb4](https://linux-hardware.org/?probe=d82e4c4eb4) | Apr 10, 2021 |
| ASUSTek       | H110M-C/BR               | [0c4cd978f2](https://linux-hardware.org/?probe=0c4cd978f2) | Jul 24, 2020 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR | [3cef63e59d](https://linux-hardware.org/?probe=3cef63e59d) | Jul 17, 2020 |
| PCWare        | IPX1800E2                | [0990462881](https://linux-hardware.org/?probe=0990462881) | Jun 21, 2020 |
| PCWare        | IPX1800E2                | [93916c17f2](https://linux-hardware.org/?probe=93916c17f2) | Jun 21, 2020 |
| ASRock        | 775Dual-VSTA             | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| ASRock        | 775Dual-VSTA             | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| ASRock        | 775Dual-VSTA             | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| ASRock        | 775Dual-VSTA             | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| BigLinux 20.04    | 5        | 19.23%  |
| BigLinux 22.0.4   | 3        | 11.54%  |
| BigLinux 23.02.20 | 2        | 7.69%   |
| BigLinux 22.1.0   | 2        | 7.69%   |
| BigLinux 22.0.0   | 2        | 7.69%   |
| BigLinux 21.3.5   | 2        | 7.69%   |
| BigLinux 23.02.24 | 1        | 3.85%   |
| BigLinux 23.02.07 | 1        | 3.85%   |
| BigLinux 23.01.30 | 1        | 3.85%   |
| BigLinux 22.12.24 | 1        | 3.85%   |
| BigLinux 22.10.28 | 1        | 3.85%   |
| BigLinux 22.1.1   | 1        | 3.85%   |
| BigLinux 22.09.09 | 1        | 3.85%   |
| BigLinux 22.0.2   | 1        | 3.85%   |
| BigLinux 21.3.7   | 1        | 3.85%   |
| BigLinux 19.04    | 1        | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| BigLinux | 24       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.1.12-1-MANJARO      | 4        | 14.29%  |
| 5.4.0-37-generic      | 2        | 7.14%   |
| 5.15.94-1-MANJARO     | 2        | 7.14%   |
| 5.15.71-1-MANJARO     | 2        | 7.14%   |
| 5.15.60-1-MANJARO     | 2        | 7.14%   |
| 6.2.12-1-MANJARO      | 1        | 3.57%   |
| 6.1.9-x64v1-xanmod1-1 | 1        | 3.57%   |
| 6.1.9-1-MANJARO       | 1        | 3.57%   |
| 6.1.26-1-MANJARO      | 1        | 3.57%   |
| 5.8.0-48-generic      | 1        | 3.57%   |
| 5.7.9-xanmod1         | 1        | 3.57%   |
| 5.6.6-xanmod1         | 1        | 3.57%   |
| 5.6.10-xanmod1        | 1        | 3.57%   |
| 5.4.0-33-generic      | 1        | 3.57%   |
| 5.4.0-31-generic      | 1        | 3.57%   |
| 5.17.15-1-MANJARO     | 1        | 3.57%   |
| 5.16.11-1-BIGLINUX    | 1        | 3.57%   |
| 5.15.89-1-MANJARO     | 1        | 3.57%   |
| 5.15.85-1-MANJARO     | 1        | 3.57%   |
| 5.15.76-1-MANJARO     | 1        | 3.57%   |
| 5.15.55-1-MANJARO     | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.12  | 4        | 14.81%  |
| 5.4.0   | 3        | 11.11%  |
| 6.1.9   | 2        | 7.41%   |
| 5.15.94 | 2        | 7.41%   |
| 5.15.71 | 2        | 7.41%   |
| 5.15.60 | 2        | 7.41%   |
| 6.2.12  | 1        | 3.7%    |
| 6.1.26  | 1        | 3.7%    |
| 5.8.0   | 1        | 3.7%    |
| 5.7.9   | 1        | 3.7%    |
| 5.6.6   | 1        | 3.7%    |
| 5.6.10  | 1        | 3.7%    |
| 5.17.15 | 1        | 3.7%    |
| 5.16.11 | 1        | 3.7%    |
| 5.15.89 | 1        | 3.7%    |
| 5.15.85 | 1        | 3.7%    |
| 5.15.76 | 1        | 3.7%    |
| 5.15.55 | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 8        | 33.33%  |
| 6.1     | 7        | 29.17%  |
| 5.4     | 3        | 12.5%   |
| 6.2     | 1        | 4.17%   |
| 5.8     | 1        | 4.17%   |
| 5.7     | 1        | 4.17%   |
| 5.6     | 1        | 4.17%   |
| 5.17    | 1        | 4.17%   |
| 5.16    | 1        | 4.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 24       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 20       | 83.33%  |
| KDE  | 4        | 16.67%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 23       | 95.83%  |
| Unknown | 1        | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 19       | 79.17%  |
| Unknown | 4        | 16.67%  |
| LXDM    | 1        | 4.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| pt_BR | 11       | 45.83%  |
| en_US | 6        | 25%     |
| pt_PT | 2        | 8.33%   |
| en_GB | 2        | 8.33%   |
| es_MX | 1        | 4.17%   |
| es_ES | 1        | 4.17%   |
| es_AR | 1        | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 15       | 62.5%   |
| BIOS | 9        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 23       | 95.83%  |
| Ext4  | 1        | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 14       | 56%     |
| MBR     | 6        | 24%     |
| Unknown | 5        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 58.33%  |
| No        | 10       | 41.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 4        | 16.67%  |
| ASUSTek Computer    | 4        | 16.67%  |
| Gigabyte Technology | 3        | 12.5%   |
| MSI                 | 2        | 8.33%   |
| Lenovo              | 2        | 8.33%   |
| Hewlett-Packard     | 2        | 8.33%   |
| ASRock              | 2        | 8.33%   |
| Semp Toshiba        | 1        | 4.17%   |
| PCWare              | 1        | 4.17%   |
| eMachines           | 1        | 4.17%   |
| ECS                 | 1        | 4.17%   |
| BESSTAR Tech        | 1        | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Intel H61                          | 2        | 8.33%   |
| ASRock 775Dual-VSTA                | 2        | 8.33%   |
| Semp Toshiba STI                   | 1        | 4.17%   |
| PCWare IPX1800E2                   | 1        | 4.17%   |
| MSI MS-7C95                        | 1        | 4.17%   |
| MSI MS-7C91                        | 1        | 4.17%   |
| Lenovo ThinkCentre M93p 10AB0010US | 1        | 4.17%   |
| Lenovo 63 90AT0002BR               | 1        | 4.17%   |
| Intel H55                          | 1        | 4.17%   |
| Intel DH61WW AAG23116-203          | 1        | 4.17%   |
| HP Compaq Elite 8300 SFF           | 1        | 4.17%   |
| HP Compaq 8200 Elite SFF PC        | 1        | 4.17%   |
| Gigabyte Z87-HD3                   | 1        | 4.17%   |
| Gigabyte X399 DESIGNARE EX         | 1        | 4.17%   |
| Gigabyte B560M AORUS ELITE         | 1        | 4.17%   |
| eMachines EL1321                   | 1        | 4.17%   |
| ECS H67H2-M2                       | 1        | 4.17%   |
| BESSTAR Tech HM90                  | 1        | 4.17%   |
| ASUS TUF Gaming B450M-PRO S        | 1        | 4.17%   |
| ASUS TUF B360M-PLUS GAMING/BR      | 1        | 4.17%   |
| ASUS H110M-C/BR                    | 1        | 4.17%   |
| ASUS All Series                    | 1        | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel H61           | 2        | 8.33%   |
| HP Compaq           | 2        | 8.33%   |
| ASUS TUF            | 2        | 8.33%   |
| ASRock 775Dual-VSTA | 2        | 8.33%   |
| Semp Toshiba STI    | 1        | 4.17%   |
| PCWare IPX1800E2    | 1        | 4.17%   |
| MSI MS-7C95         | 1        | 4.17%   |
| MSI MS-7C91         | 1        | 4.17%   |
| Lenovo ThinkCentre  | 1        | 4.17%   |
| Lenovo 63           | 1        | 4.17%   |
| Intel H55           | 1        | 4.17%   |
| Intel DH61WW        | 1        | 4.17%   |
| Gigabyte Z87-HD3    | 1        | 4.17%   |
| Gigabyte X399       | 1        | 4.17%   |
| Gigabyte B560M      | 1        | 4.17%   |
| eMachines EL1321    | 1        | 4.17%   |
| ECS H67H2-M2        | 1        | 4.17%   |
| BESSTAR Tech HM90   | 1        | 4.17%   |
| ASUS H110M-C        | 1        | 4.17%   |
| ASUS All            | 1        | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2017 | 4        | 16.67%  |
| 2020 | 3        | 12.5%   |
| 2014 | 3        | 12.5%   |
| 2013 | 3        | 12.5%   |
| 2021 | 2        | 8.33%   |
| 2018 | 2        | 8.33%   |
| 2011 | 2        | 8.33%   |
| 2009 | 2        | 8.33%   |
| 2006 | 2        | 8.33%   |
| 2012 | 1        | 4.17%   |

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
| Disabled | 23       | 95.83%  |
| Enabled  | 1        | 4.17%   |

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
| 32.01-64.0 | 6        | 25%     |
| 3.01-4.0   | 4        | 16.67%  |
| 16.01-24.0 | 4        | 16.67%  |
| 8.01-16.0  | 4        | 16.67%  |
| 4.01-8.0   | 3        | 12.5%   |
| 2.01-3.0   | 3        | 12.5%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 10       | 37.04%  |
| 1.01-2.0  | 8        | 29.63%  |
| 4.01-8.0  | 3        | 11.11%  |
| 3.01-4.0  | 2        | 7.41%   |
| 0.51-1.0  | 2        | 7.41%   |
| 8.01-16.0 | 1        | 3.7%    |
| 0.01-0.5  | 1        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 7        | 28%     |
| 1      | 7        | 28%     |
| 3      | 6        | 24%     |
| 6      | 2        | 8%      |
| 4      | 2        | 8%      |
| 0      | 1        | 4%      |

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
| Yes       | 24       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 54.17%  |
| Yes       | 11       | 45.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 66.67%  |
| Yes       | 8        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Brazil    | 13       | 54.17%  |
| USA       | 2        | 8.33%   |
| UK        | 2        | 8.33%   |
| Portugal  | 2        | 8.33%   |
| Spain     | 1        | 4.17%   |
| Mexico    | 1        | 4.17%   |
| Japan     | 1        | 4.17%   |
| Greece    | 1        | 4.17%   |
| Argentina | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sao Paulo              | 2        | 8.33%   |
| Vila Nova de Famalicao | 1        | 4.17%   |
| Tokyo                  | 1        | 4.17%   |
| Tlajomulco de Zuniga   | 1        | 4.17%   |
| Thessaloniki           | 1        | 4.17%   |
| The Villages           | 1        | 4.17%   |
| Sao Joaquim da Barra   | 1        | 4.17%   |
| Sao Domingos do Capim  | 1        | 4.17%   |
| Santo André           | 1        | 4.17%   |
| Santa Cruz de Tenerife | 1        | 4.17%   |
| Rio de Janeiro         | 1        | 4.17%   |
| Ribeirao Grande        | 1        | 4.17%   |
| Osasco                 | 1        | 4.17%   |
| Maringá               | 1        | 4.17%   |
| Macapa                 | 1        | 4.17%   |
| Guimaraes              | 1        | 4.17%   |
| Fresno                 | 1        | 4.17%   |
| Franca                 | 1        | 4.17%   |
| El Palomar             | 1        | 4.17%   |
| Dumbarton              | 1        | 4.17%   |
| Brasília              | 1        | 4.17%   |
| Bournemouth            | 1        | 4.17%   |
| Belo Horizonte         | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 10       | 19     | 22.22%  |
| WDC                         | 7        | 11     | 15.56%  |
| SanDisk                     | 3        | 3      | 6.67%   |
| Samsung Electronics         | 3        | 4      | 6.67%   |
| Kingston                    | 3        | 6      | 6.67%   |
| Hitachi                     | 3        | 3      | 6.67%   |
| Toshiba                     | 2        | 2      | 4.44%   |
| PNY                         | 2        | 2      | 4.44%   |
| KingSpec                    | 2        | 2      | 4.44%   |
| China                       | 2        | 4      | 4.44%   |
| XrayDisk                    | 1        | 1      | 2.22%   |
| Micron/Crucial Technology   | 1        | 1      | 2.22%   |
| Kingston Technology Company | 1        | 1      | 2.22%   |
| JMicron Technology          | 1        | 1      | 2.22%   |
| Intel                       | 1        | 1      | 2.22%   |
| BHT                         | 1        | 1      | 2.22%   |
| Apacer                      | 1        | 1      | 2.22%   |
| ADATA Technology            | 1        | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 2        | 3.85%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2        | 3.85%   |
| Kingston SV300S37A240G 240GB SSD                    | 2        | 3.85%   |
| XrayDisk 512GB SSD                                  | 1        | 1.92%   |
| WDC WD800AAJS-75M0A0 80GB                           | 1        | 1.92%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 1.92%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1        | 1.92%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1        | 1.92%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 1        | 1.92%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1        | 1.92%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 1        | 1.92%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1        | 1.92%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1        | 1.92%   |
| WDC WD1001FALS-41Y6A1 1TB                           | 1        | 1.92%   |
| Toshiba MQ01ABD050V -63 500GB                       | 1        | 1.92%   |
| Toshiba DT01ACA050 500GB                            | 1        | 1.92%   |
| Seagate ST9500325AS 500GB                           | 1        | 1.92%   |
| Seagate ST9100824AS 100GB                           | 1        | 1.92%   |
| Seagate ST8000VN0022-2EL112 8TB                     | 1        | 1.92%   |
| Seagate ST8000AS0002-1NA17Z 8TB                     | 1        | 1.92%   |
| Seagate ST3320613AS 320GB                           | 1        | 1.92%   |
| Seagate ST32000542AS 2TB                            | 1        | 1.92%   |
| Seagate ST3160212SCE 160GB                          | 1        | 1.92%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1.92%   |
| Seagate Expansion 1TB                               | 1        | 1.92%   |
| Sandisk WD Blue SN570 1TB                           | 1        | 1.92%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 1        | 1.92%   |
| SanDisk SDSSDXPS480G 480GB                          | 1        | 1.92%   |
| Samsung SSD 870 QVO 2TB                             | 1        | 1.92%   |
| Samsung SSD 850 EVO M.2 500GB                       | 1        | 1.92%   |
| Samsung SSD 840 EVO 1TB                             | 1        | 1.92%   |
| PNY CS900 240GB SSD                                 | 1        | 1.92%   |
| PNY CS900 120GB SSD                                 | 1        | 1.92%   |
| Micron/Crucial CT500P5SSD8 500GB                    | 1        | 1.92%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB             | 1        | 1.92%   |
| Kingston SNVS250G 250GB                             | 1        | 1.92%   |
| Kingston SA400S37240G 240GB SSD                     | 1        | 1.92%   |
| KingSpec P3-256 256GB SSD                           | 1        | 1.92%   |
| KingSpec P3-1TB SSD                                 | 1        | 1.92%   |
| JMicron Tech 250GB                                  | 1        | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 19     | 45.45%  |
| WDC     | 7        | 11     | 31.82%  |
| Hitachi | 3        | 3      | 13.64%  |
| Toshiba | 2        | 2      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 18.75%  |
| Kingston            | 3        | 5      | 18.75%  |
| PNY                 | 2        | 2      | 12.5%   |
| KingSpec            | 2        | 2      | 12.5%   |
| China               | 2        | 4      | 12.5%   |
| XrayDisk            | 1        | 1      | 6.25%   |
| SanDisk             | 1        | 1      | 6.25%   |
| BHT                 | 1        | 1      | 6.25%   |
| Apacer              | 1        | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 17       | 35     | 43.59%  |
| SSD     | 15       | 21     | 38.46%  |
| NVMe    | 6        | 7      | 15.38%  |
| Unknown | 1        | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 55     | 73.33%  |
| NVMe | 6        | 7      | 20%     |
| SAS  | 2        | 2      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 33     | 62.07%  |
| 0.51-1.0   | 6        | 12     | 20.69%  |
| 3.01-4.0   | 2        | 6      | 6.9%    |
| 1.01-2.0   | 2        | 3      | 6.9%    |
| 4.01-10.0  | 1        | 2      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 6        | 25%     |
| 101-250        | 5        | 20.83%  |
| 251-500        | 4        | 16.67%  |
| 2001-3000      | 3        | 12.5%   |
| 501-1000       | 3        | 12.5%   |
| More than 3000 | 2        | 8.33%   |
| 1-20           | 1        | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 21-50    | 9        | 34.62%  |
| 501-1000 | 5        | 19.23%  |
| 251-500  | 4        | 15.38%  |
| 101-250  | 3        | 11.54%  |
| 1-20     | 3        | 11.54%  |
| 51-100   | 2        | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB       | 1        | 1      | 12.5%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 1      | 12.5%   |
| WDC WD1001FALS-41Y6A1 1TB       | 1        | 2      | 12.5%   |
| Seagate ST9100824AS 100GB       | 1        | 1      | 12.5%   |
| Seagate ST8000AS0002-1NA17Z 8TB | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 2      | 12.5%   |
| Seagate ST3320613AS 320GB       | 1        | 1      | 12.5%   |
| Hitachi HDS721050DLE630 500GB   | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 50%     |
| WDC     | 3        | 4      | 37.5%   |
| Hitachi | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 50%     |
| WDC     | 3        | 4      | 37.5%   |
| Hitachi | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 10     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 13       | 32     | 40.63%  |
| Detected | 11       | 21     | 34.38%  |
| Malfunc  | 7        | 10     | 21.88%  |
| Failed   | 1        | 1      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 16       | 51.61%  |
| AMD                         | 5        | 16.13%  |
| VIA Technologies            | 2        | 6.45%   |
| SanDisk                     | 2        | 6.45%   |
| Kingston Technology Company | 2        | 6.45%   |
| Phison Electronics          | 1        | 3.23%   |
| Nvidia                      | 1        | 3.23%   |
| Micron/Crucial Technology   | 1        | 3.23%   |
| ADATA Technology            | 1        | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 10.53%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 10.53%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 7.89%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 5.26%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 2        | 5.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 5.26%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1        | 2.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 2.63%   |
| Phison E12 NVMe Controller                                                              | 1        | 2.63%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 2.63%   |
| Micron/Crucial NVMe Storage Controller                                                  | 1        | 2.63%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 2.63%   |
| Kingston Company NVMe Controller                                                        | 1        | 2.63%   |
| Intel SSD 660P Series                                                                   | 1        | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 2.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1        | 2.63%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 2.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 59.38%  |
| NVMe | 6        | 18.75%  |
| IDE  | 5        | 15.63%  |
| RAID | 2        | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 75%     |
| AMD    | 6        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Pentium D CPU 3.00GHz                    | 2        | 8.33%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz    | 1        | 4.17%   |
| Intel Pentium CPU G4400 @ 3.30GHz              | 1        | 4.17%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 4.17%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 4.17%   |
| Intel Core i7 CPU S 860 @ 2.53GHz              | 1        | 4.17%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 4.17%   |
| Intel Core i5-4570T CPU @ 2.90GHz              | 1        | 4.17%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 4.17%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 1        | 4.17%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 4.17%   |
| Intel Core i5-2300 CPU @ 2.80GHz               | 1        | 4.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 4.17%   |
| Intel Core i3-3250 CPU @ 3.50GHz               | 1        | 4.17%   |
| Intel Celeron CPU J1800 @ 2.41GHz              | 1        | 4.17%   |
| Intel Celeron CPU G530 @ 2.40GHz               | 1        | 4.17%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1        | 4.17%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 4.17%   |
| AMD Ryzen 9 4900H with Radeon Graphics         | 1        | 4.17%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 4.17%   |
| AMD Ryzen 5 5600 6-Core Processor              | 1        | 4.17%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 4.17%   |
| AMD Athlon Processor LE-1660                   | 1        | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 6        | 25%     |
| Intel Core i7           | 3        | 12.5%   |
| Intel Pentium D         | 2        | 8.33%   |
| Intel Core i3           | 2        | 8.33%   |
| Intel Celeron           | 2        | 8.33%   |
| AMD Ryzen 5             | 2        | 8.33%   |
| Other                   | 1        | 4.17%   |
| Intel Pentium Dual-Core | 1        | 4.17%   |
| Intel Pentium           | 1        | 4.17%   |
| AMD Ryzen Threadripper  | 1        | 4.17%   |
| AMD Ryzen 9             | 1        | 4.17%   |
| AMD Ryzen 7             | 1        | 4.17%   |
| AMD Athlon              | 1        | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 37.5%   |
| 4      | 7        | 29.17%  |
| 6      | 4        | 16.67%  |
| 8      | 2        | 8.33%   |
| 12     | 1        | 4.17%   |
| 1      | 1        | 4.17%   |

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
| 32-bit, 64-bit | 24       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 4        | 16.67%  |
| 0x306c3    | 3        | 12.5%   |
| Unknown    | 3        | 12.5%   |
| 0xf64      | 2        | 8.33%   |
| 0x306a9    | 2        | 8.33%   |
| 0xa0671    | 1        | 4.17%   |
| 0x906ed    | 1        | 4.17%   |
| 0x506e3    | 1        | 4.17%   |
| 0x30678    | 1        | 4.17%   |
| 0x1067a    | 1        | 4.17%   |
| 0x0a201025 | 1        | 4.17%   |
| 0x08701021 | 1        | 4.17%   |
| 0x08600106 | 1        | 4.17%   |
| 0x0800820d | 1        | 4.17%   |
| 0x08001137 | 1        | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 4        | 16.67%  |
| Haswell     | 4        | 16.67%  |
| Zen 2       | 2        | 8.33%   |
| NetBurst    | 2        | 8.33%   |
| IvyBridge   | 2        | 8.33%   |
| Zen+        | 1        | 4.17%   |
| Zen 3       | 1        | 4.17%   |
| Zen         | 1        | 4.17%   |
| Skylake     | 1        | 4.17%   |
| Silvermont  | 1        | 4.17%   |
| Penryn      | 1        | 4.17%   |
| Nehalem     | 1        | 4.17%   |
| KabyLake    | 1        | 4.17%   |
| K8 Hammer   | 1        | 4.17%   |
| Icelake     | 1        | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 11       | 42.31%  |
| Intel  | 8        | 30.77%  |
| AMD    | 7        | 26.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 7.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 7.69%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 7.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 3.85%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 3.85%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 3.85%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 3.85%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 3.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 3.85%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.85%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 3.85%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.85%   |
| Intel HD Graphics 510                                                       | 1        | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 3.85%   |
| AMD Renoir                                                                  | 1        | 3.85%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 3.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 3.85%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 1        | 3.85%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 1        | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 9        | 37.5%   |
| 1 x AMD        | 7        | 29.17%  |
| 1 x Intel      | 6        | 25%     |
| Intel + Nvidia | 2        | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 58.33%  |
| Proprietary | 9        | 37.5%   |
| Unknown     | 1        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 8        | 33.33%  |
| Unknown    | 8        | 33.33%  |
| 0.01-0.5   | 3        | 12.5%   |
| 3.01-4.0   | 2        | 8.33%   |
| 5.01-6.0   | 1        | 4.17%   |
| 8.01-16.0  | 1        | 4.17%   |
| 0.51-1.0   | 1        | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 33.33%  |
| Goldstar            | 5        | 20.83%  |
| Philips             | 2        | 8.33%   |
| AOC                 | 2        | 8.33%   |
| Unknown (XXX)       | 1        | 4.17%   |
| Positivo            | 1        | 4.17%   |
| NEC Computers       | 1        | 4.17%   |
| LG Electronics      | 1        | 4.17%   |
| Dell                | 1        | 4.17%   |
| BenQ                | 1        | 4.17%   |
| ASUSTek Computer    | 1        | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch | 2        | 7.41%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch       | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch  | 1        | 3.7%    |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch    | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM02C9 1360x768 885x498mm 40.0-inch | 1        | 3.7%    |
| Samsung Electronics LCD Monitor C24F390 1920x1080                    | 1        | 3.7%    |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                 | 1        | 3.7%    |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch              | 1        | 3.7%    |
| Philips 237E4 PHLC0AD 1920x1080 509x286mm 23.0-inch                  | 1        | 3.7%    |
| NEC Computers LCD1770VX NEC6697 1280x960 338x270mm 17.0-inch         | 1        | 3.7%    |
| LG Electronics LCD Monitor LG FULL HD 3200x1080                      | 1        | 3.7%    |
| LG Electronics LCD Monitor LG FULL HD                                | 1        | 3.7%    |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1        | 3.7%    |
| Goldstar ULTRAWIDE GSM5C0C 2560x1080 601x254mm 25.7-inch             | 1        | 3.7%    |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                | 1        | 3.7%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1        | 3.7%    |
| Goldstar HD 16 GSM3E92 1366x768 344x194mm 15.5-inch                  | 1        | 3.7%    |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 1        | 3.7%    |
| Dell LCD Monitor E170S 3200x1080                                     | 1        | 3.7%    |
| Dell LCD Monitor E170S                                               | 1        | 3.7%    |
| BenQ LCD Monitor EL2870U 3840x2160                                   | 1        | 3.7%    |
| ASUSTek Computer VP249 AUS24AA 1920x1080 530x300mm 24.0-inch         | 1        | 3.7%    |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 1        | 3.7%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 25%     |
| 1366x768 (WXGA)    | 3        | 12.5%   |
| 1360x768           | 3        | 12.5%   |
| 3840x2160 (4K)     | 2        | 8.33%   |
| 2560x1080          | 2        | 8.33%   |
| 1680x1050 (WSXGA+) | 2        | 8.33%   |
| 3200x1080          | 1        | 4.17%   |
| 1920x1200 (WUXGA)  | 1        | 4.17%   |
| 1600x900 (HD+)     | 1        | 4.17%   |
| 1280x960           | 1        | 4.17%   |
| 1280x1024 (SXGA)   | 1        | 4.17%   |
| Unknown            | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 3        | 12.5%   |
| 20      | 3        | 12.5%   |
| 18      | 3        | 12.5%   |
| Unknown | 3        | 12.5%   |
| 24      | 2        | 8.33%   |
| 17      | 2        | 8.33%   |
| 54      | 1        | 4.17%   |
| 40      | 1        | 4.17%   |
| 34      | 1        | 4.17%   |
| 31      | 1        | 4.17%   |
| 27      | 1        | 4.17%   |
| 25      | 1        | 4.17%   |
| 21      | 1        | 4.17%   |
| 15      | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 7        | 30.43%  |
| 501-600     | 5        | 21.74%  |
| 301-350     | 3        | 13.04%  |
| Unknown     | 3        | 13.04%  |
| 601-700     | 2        | 8.7%    |
| 801-900     | 1        | 4.35%   |
| 701-800     | 1        | 4.35%   |
| 1001-1500   | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 56.52%  |
| 16/10   | 3        | 13.04%  |
| Unknown | 3        | 13.04%  |
| 5/4     | 2        | 8.7%    |
| 21/9    | 2        | 8.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 21.74%  |
| 141-150        | 5        | 21.74%  |
| 151-200        | 3        | 13.04%  |
| Unknown        | 3        | 13.04%  |
| 351-500        | 2        | 8.7%    |
| More than 1000 | 1        | 4.35%   |
| 301-350        | 1        | 4.35%   |
| 251-300        | 1        | 4.35%   |
| 101-110        | 1        | 4.35%   |
| 501-1000       | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 63.64%  |
| 101-120 | 3        | 13.64%  |
| Unknown | 3        | 13.64%  |
| 1-50    | 2        | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 70.83%  |
| 2     | 5        | 20.83%  |
| 0     | 2        | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 45.71%  |
| Intel                 | 9        | 25.71%  |
| VIA Technologies      | 2        | 5.71%   |
| Qualcomm Atheros      | 2        | 5.71%   |
| D-Link System         | 2        | 5.71%   |
| Samsung Electronics   | 1        | 2.86%   |
| Ralink Technology     | 1        | 2.86%   |
| MediaTek              | 1        | 2.86%   |
| D-Link                | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 10       | 24.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 4        | 9.76%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 3        | 7.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2        | 4.88%   |
| Realtek 802.11ac NIC                                                                  | 2        | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2        | 4.88%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                       | 2        | 4.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1        | 2.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 2.44%   |
| Ralink RT5370 Wireless Adapter                                                        | 1        | 2.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1        | 2.44%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 2.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 2.44%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 2.44%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 2.44%   |
| Intel I211 Gigabit Network Connection                                                 | 1        | 2.44%   |
| Intel Ethernet Controller I225-V                                                      | 1        | 2.44%   |
| Intel Ethernet Connection I217-LM                                                     | 1        | 2.44%   |
| Intel Ethernet Connection (7) I219-V                                                  | 1        | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 2.44%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 2.44%   |
| Intel 82579V Gigabit Network Connection                                               | 1        | 2.44%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1        | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 36.36%  |
| Realtek Semiconductor | 3        | 27.27%  |
| Ralink Technology     | 1        | 9.09%   |
| Qualcomm Atheros      | 1        | 9.09%   |
| MediaTek              | 1        | 9.09%   |
| D-Link                | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                                                  | 2        | 18.18%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 9.09%   |
| Ralink RT5370 Wireless Adapter                                                        | 1        | 9.09%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 9.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 9.09%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 9.09%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 9.09%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 53.57%  |
| Intel                 | 7        | 25%     |
| VIA Technologies      | 2        | 7.14%   |
| D-Link System         | 2        | 7.14%   |
| Samsung Electronics   | 1        | 3.57%   |
| Qualcomm Atheros      | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 13.33%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 10%     |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 6.67%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 6.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 3.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.33%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.33%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.33%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 68.57%  |
| WiFi     | 11       | 31.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 79.17%  |
| WiFi     | 5        | 20.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 58.33%  |
| 2     | 8        | 33.33%  |
| 3     | 2        | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 70.83%  |
| Yes  | 7        | 29.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 37.5%   |
| Cambridge Silicon Radio | 3        | 37.5%   |
| Realtek Semiconductor   | 1        | 12.5%   |
| MediaTek                | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 37.5%   |
| Realtek Bluetooth 5.1 Radio                         | 1        | 12.5%   |
| MediaTek Wireless_Device                            | 1        | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 12.5%   |
| Intel Bluetooth wireless interface                  | 1        | 12.5%   |
| Intel AX200 Bluetooth                               | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 16       | 38.1%   |
| Nvidia                 | 10       | 23.81%  |
| AMD                    | 10       | 23.81%  |
| C-Media Electronics    | 3        | 7.14%   |
| Creative Labs          | 2        | 4.76%   |
| Generalplus Technology | 1        | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 11.11%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4        | 8.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 6.67%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2        | 4.44%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 4.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 4.44%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2        | 4.44%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 4.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 4.44%   |
| Nvidia TU102 High Definition Audio Controller                                     | 1        | 2.22%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 2.22%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 2.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 2.22%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 2.22%   |
| Generalplus Technology USB Audio Device                                           | 1        | 2.22%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 1        | 2.22%   |
| C-Media Electronics CM108 Audio Controller                                        | 1        | 2.22%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1        | 2.22%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 1        | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 2.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1        | 2.22%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 2.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 26.09%  |
| Unknown             | 4        | 17.39%  |
| Corsair             | 3        | 13.04%  |
| SK hynix            | 2        | 8.7%    |
| Samsung Electronics | 2        | 8.7%    |
| Smart               | 1        | 4.35%   |
| Ramaxel Technology  | 1        | 4.35%   |
| PLEXHD              | 1        | 4.35%   |
| Nanya Technology    | 1        | 4.35%   |
| Crucial             | 1        | 4.35%   |
| Unknown             | 1        | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM SDRAM                         | 1        | 4.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 4.17%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 4.17%   |
| Unknown RAM Module 2GB DIMM DDR2 266MT/s                  | 1        | 4.17%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s       | 1        | 4.17%   |
| SK hynix RAM MD4512NSE-CB3M2 00 4096MB DIMM DDR4 2400MT/s | 1        | 4.17%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s      | 1        | 4.17%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1        | 4.17%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM 2200MT/s            | 1        | 4.17%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| PLEXHD RAM er 4GB DIMM DDR3 1600MT/s                      | 1        | 4.17%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 4.17%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 4.17%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 1        | 4.17%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 1        | 4.17%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s   | 1        | 4.17%   |
| Kingston RAM 9905471-001.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 4.17%   |
| Kingston RAM 9905316-004.A03LF0 1GB DIMM DDR2 266MT/s     | 1        | 4.17%   |
| Crucial RAM CT16G4DFRA32A.M16FE 16GB DIMM DDR4 3200MT/s   | 1        | 4.17%   |
| Corsair RAM CML8GX3M1A1600C9 8192MB DIMM DDR3 1600MT/s    | 1        | 4.17%   |
| Corsair RAM CMK32GX4M2C3000C16 16GB DIMM DDR4 2133MT/s    | 1        | 4.17%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s     | 1        | 4.17%   |
| Unknown                                                   | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 8        | 44.44%  |
| DDR4  | 6        | 33.33%  |
| SDRAM | 3        | 16.67%  |
| DDR2  | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 88.89%  |
| SODIMM | 2        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 30%     |
| 4096  | 6        | 30%     |
| 2048  | 4        | 20%     |
| 16384 | 3        | 15%     |
| 1024  | 1        | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 23.81%  |
| 1333    | 4        | 19.05%  |
| 3200    | 3        | 14.29%  |
| 2400    | 2        | 9.52%   |
| 2133    | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| 2200    | 1        | 4.76%   |
| 1867    | 1        | 4.76%   |
| 266     | 1        | 4.76%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 1        | 33.33%  |
| Lenovo                        | 1        | 33.33%  |
| Jieli Technology              | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus FHD Camera Microphone | 1        | 33.33%  |
| Lenovo FHD Webcam             | 1        | 33.33%  |
| Jieli USB PHY 2.0             | 1        | 33.33%  |

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
| 0     | 19       | 79.17%  |
| 1     | 5        | 20.83%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 3        | 60%     |
| Network       | 1        | 20%     |
| Graphics card | 1        | 20%     |

