Slackware 15.0 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 26

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| HP       | 3031h                   | [b6849a29a2](https://linux-hardware.org/?probe=b6849a29a2) | Sep 24, 2022 |
| HP       | 3031h                   | [40160588bb](https://linux-hardware.org/?probe=40160588bb) | Sep 20, 2022 |
| MSI      | H110M PRO-VD            | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Dell     | 0200DY A03              | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Gigabyte | N3160TN                 | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| ASUSTek  | TUF B450-PLUS GAMING    | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI      | 970 GAMING              | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| ASRock   | N68-S3 FX               | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI      | MS-7365                 | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown  | X79-P3                  | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| HP       | 0A08h                   | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| ASRock   | H410M-ITX/ac            | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek  | PRIME Z390-A            | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Acer     | FMCP7A-ION-LE           | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| ASRock   | H270 Pro4               | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| Lenovo   | 31900058 STD            | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| Biostar  | X470GTA                 | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| MSI      | G31TM-P21               | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP       | 212B                    | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI      | B450 TOMAHAWK MAX       | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI      | G31TM-P21               | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI      | H61M-P31                | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| MSI      | B450M-A PRO MAX         | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek  | SABERTOOTH X99          | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI      | B450M-A PRO MAX         | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 5.15.19        | 4        | 17.39%  |
| 5.15.30-Unraid | 2        | 8.7%    |
| 5.15.27        | 2        | 8.7%    |
| 5.17.2         | 1        | 4.35%   |
| 5.17.0-custom  | 1        | 4.35%   |
| 5.16.18        | 1        | 4.35%   |
| 5.16.13        | 1        | 4.35%   |
| 5.16.11        | 1        | 4.35%   |
| 5.15.63        | 1        | 4.35%   |
| 5.15.6         | 1        | 4.35%   |
| 5.15.38        | 1        | 4.35%   |
| 5.15.14        | 1        | 4.35%   |
| 5.15.13        | 1        | 4.35%   |
| 5.14.15-Unraid | 1        | 4.35%   |
| 5.14.15        | 1        | 4.35%   |
| 5.14.12        | 1        | 4.35%   |
| 5.14.11        | 1        | 4.35%   |
| 5.13.12        | 1        | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.19 | 4        | 17.39%  |
| 5.15.30 | 2        | 8.7%    |
| 5.15.27 | 2        | 8.7%    |
| 5.14.15 | 2        | 8.7%    |
| 5.17.2  | 1        | 4.35%   |
| 5.17.0  | 1        | 4.35%   |
| 5.16.18 | 1        | 4.35%   |
| 5.16.13 | 1        | 4.35%   |
| 5.16.11 | 1        | 4.35%   |
| 5.15.63 | 1        | 4.35%   |
| 5.15.6  | 1        | 4.35%   |
| 5.15.38 | 1        | 4.35%   |
| 5.15.14 | 1        | 4.35%   |
| 5.15.13 | 1        | 4.35%   |
| 5.14.12 | 1        | 4.35%   |
| 5.14.11 | 1        | 4.35%   |
| 5.13.12 | 1        | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 13       | 56.52%  |
| 5.14    | 4        | 17.39%  |
| 5.16    | 3        | 13.04%  |
| 5.17    | 2        | 8.7%    |
| 5.13    | 1        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 23       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 11       | 45.83%  |
| XFCE    | 7        | 29.17%  |
| Unknown | 5        | 20.83%  |
| FVWM    | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 13       | 54.17%  |
| Tty     | 8        | 33.33%  |
| Unknown | 3        | 12.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 14       | 60.87%  |
| Unknown | 6        | 26.09%  |
| LightDM | 2        | 8.7%    |
| XDM     | 1        | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 15       | 65.22%  |
| Unknown     | 4        | 17.39%  |
| it_IT       | 1        | 4.35%   |
| es_ES.UTF8  | 1        | 4.35%   |
| en_US.ASCII | 1        | 4.35%   |
| en_GB       | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 13       | 56.52%  |
| EFI  | 10       | 43.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 14       | 60.87%  |
| Btrfs   | 4        | 17.39%  |
| Xfs     | 2        | 8.7%    |
| Overlay | 2        | 8.7%    |
| F2fs    | 1        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 18       | 75%     |
| MBR     | 4        | 16.67%  |
| Unknown | 2        | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 69.57%  |
| Yes       | 7        | 30.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 69.57%  |
| Yes       | 7        | 30.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 7        | 30.43%  |
| ASUSTek Computer    | 4        | 17.39%  |
| Hewlett-Packard     | 3        | 13.04%  |
| ASRock              | 3        | 13.04%  |
| Lenovo              | 1        | 4.35%   |
| Gigabyte Technology | 1        | 4.35%   |
| Dell                | 1        | 4.35%   |
| Biostar             | 1        | 4.35%   |
| Acer                | 1        | 4.35%   |
| Unknown             | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7C52                        | 1        | 4.35%   |
| MSI MS-7C02                        | 1        | 4.35%   |
| MSI MS-7996                        | 1        | 4.35%   |
| MSI MS-7788                        | 1        | 4.35%   |
| MSI MS-7693                        | 1        | 4.35%   |
| MSI MS-7529                        | 1        | 4.35%   |
| MSI MS-7365                        | 1        | 4.35%   |
| Lenovo H50-05 90BH001WIX           | 1        | 4.35%   |
| HP Z440 Workstation                | 1        | 4.35%   |
| HP xw8400 Workstation              | 1        | 4.35%   |
| HP Compaq dc7900 Small Form Factor | 1        | 4.35%   |
| Gigabyte N3160TN                   | 1        | 4.35%   |
| Dell OptiPlex 780                  | 1        | 4.35%   |
| Biostar X470GTA                    | 1        | 4.35%   |
| ASUS TUF B450-PLUS GAMING          | 1        | 4.35%   |
| ASUS ROG CROSSHAIR VIII HERO       | 1        | 4.35%   |
| ASUS PRIME Z390-A                  | 1        | 4.35%   |
| ASUS All Series                    | 1        | 4.35%   |
| ASRock N68-S3 FX                   | 1        | 4.35%   |
| ASRock H410M-ITX/ac                | 1        | 4.35%   |
| ASRock H270 Pro4                   | 1        | 4.35%   |
| Acer Aspire R3610                  | 1        | 4.35%   |
| Unknown                            | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MSI MS-7C52      | 1        | 4.35%   |
| MSI MS-7C02      | 1        | 4.35%   |
| MSI MS-7996      | 1        | 4.35%   |
| MSI MS-7788      | 1        | 4.35%   |
| MSI MS-7693      | 1        | 4.35%   |
| MSI MS-7529      | 1        | 4.35%   |
| MSI MS-7365      | 1        | 4.35%   |
| Lenovo H50-05    | 1        | 4.35%   |
| HP Z440          | 1        | 4.35%   |
| HP xw8400        | 1        | 4.35%   |
| HP Compaq        | 1        | 4.35%   |
| Gigabyte N3160TN | 1        | 4.35%   |
| Dell OptiPlex    | 1        | 4.35%   |
| Biostar X470GTA  | 1        | 4.35%   |
| ASUS TUF         | 1        | 4.35%   |
| ASUS ROG         | 1        | 4.35%   |
| ASUS PRIME       | 1        | 4.35%   |
| ASUS All         | 1        | 4.35%   |
| ASRock N68-S3    | 1        | 4.35%   |
| ASRock H410M-ITX | 1        | 4.35%   |
| ASRock H270      | 1        | 4.35%   |
| Acer Aspire      | 1        | 4.35%   |
| Unknown          | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 13.04%  |
| 2011 | 3        | 13.04%  |
| 2020 | 2        | 8.7%    |
| 2018 | 2        | 8.7%    |
| 2017 | 2        | 8.7%    |
| 2015 | 2        | 8.7%    |
| 2014 | 2        | 8.7%    |
| 2009 | 2        | 8.7%    |
| 2008 | 2        | 8.7%    |
| 2022 | 1        | 4.35%   |
| 2016 | 1        | 4.35%   |
| 2007 | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 23       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 6        | 26.09%  |
| 3.01-4.0    | 4        | 17.39%  |
| 32.01-64.0  | 3        | 13.04%  |
| 64.01-256.0 | 3        | 13.04%  |
| 4.01-8.0    | 2        | 8.7%    |
| 1.01-2.0    | 2        | 8.7%    |
| 8.01-16.0   | 2        | 8.7%    |
| 24.01-32.0  | 1        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 6        | 25%     |
| 1.01-2.0   | 6        | 25%     |
| 2.01-3.0   | 5        | 20.83%  |
| 0.51-1.0   | 4        | 16.67%  |
| 32.01-64.0 | 1        | 4.17%   |
| 3.01-4.0   | 1        | 4.17%   |
| 0.01-0.5   | 1        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 7        | 30.43%  |
| 2      | 5        | 21.74%  |
| 1      | 5        | 21.74%  |
| 6      | 2        | 8.7%    |
| 4      | 2        | 8.7%    |
| 9      | 1        | 4.35%   |
| 0      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 52.17%  |
| No        | 11       | 47.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 52.17%  |
| Yes       | 11       | 47.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 65.22%  |
| Yes       | 8        | 34.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 5        | 21.74%  |
| UK           | 3        | 13.04%  |
| Kazakhstan   | 3        | 13.04%  |
| Italy        | 3        | 13.04%  |
| Hong Kong    | 2        | 8.7%    |
| Brazil       | 2        | 8.7%    |
| Spain        | 1        | 4.35%   |
| South Africa | 1        | 4.35%   |
| Russia       | 1        | 4.35%   |
| Japan        | 1        | 4.35%   |
| Canada       | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Ust-Kamenogorsk   | 2        | 8.7%    |
| Winter Springs    | 1        | 4.35%   |
| Tsukuba           | 1        | 4.35%   |
| Toronto           | 1        | 4.35%   |
| St Petersburg     | 1        | 4.35%   |
| Sham Shui Po      | 1        | 4.35%   |
| Santa Cruz do Sul | 1        | 4.35%   |
| Saint Paul        | 1        | 4.35%   |
| Rome              | 1        | 4.35%   |
| Rock              | 1        | 4.35%   |
| Porto Alegre      | 1        | 4.35%   |
| Milwaukee         | 1        | 4.35%   |
| Milan             | 1        | 4.35%   |
| Mead              | 1        | 4.35%   |
| London            | 1        | 4.35%   |
| Karaganda         | 1        | 4.35%   |
| Granada           | 1        | 4.35%   |
| Frosinone         | 1        | 4.35%   |
| Colorado Springs  | 1        | 4.35%   |
| Central           | 1        | 4.35%   |
| Cape Town         | 1        | 4.35%   |
| Belfast           | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 15     | 22.92%  |
| WDC                 | 8        | 12     | 16.67%  |
| Samsung Electronics | 6        | 8      | 12.5%   |
| Hitachi             | 5        | 8      | 10.42%  |
| Toshiba             | 4        | 7      | 8.33%   |
| Kingston            | 3        | 4      | 6.25%   |
| Crucial             | 2        | 2      | 4.17%   |
| ZHITAI              | 1        | 2      | 2.08%   |
| Patriot             | 1        | 1      | 2.08%   |
| Intenso             | 1        | 1      | 2.08%   |
| HGST                | 1        | 1      | 2.08%   |
| Hewlett-Packard     | 1        | 1      | 2.08%   |
| Gigabyte Technology | 1        | 1      | 2.08%   |
| DUEX                | 1        | 1      | 2.08%   |
| China               | 1        | 1      | 2.08%   |
| A-DATA Technology   | 1        | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD20EFRX-68EUZN0 2TB             | 2        | 3.51%   |
| Seagate ST1000DM003-1SB102 1TB       | 2        | 3.51%   |
| Samsung SSD 970 EVO 250GB            | 2        | 3.51%   |
| Crucial CT500MX500SSD1 500GB         | 2        | 3.51%   |
| ZHITAI SC001 Active 1TB SSD          | 1        | 1.75%   |
| ZHITAI PC005 Active 512GB            | 1        | 1.75%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1        | 1.75%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 1.75%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1        | 1.75%   |
| WDC WD40EJRX-89T1XY0 4TB             | 1        | 1.75%   |
| WDC WD400BD-60LTA0 40GB              | 1        | 1.75%   |
| WDC WD3200AAJS-65B4A0 320GB          | 1        | 1.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 1.75%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1        | 1.75%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 1.75%   |
| Toshiba THNSF5512GPUK 512GB          | 1        | 1.75%   |
| Toshiba MD04ABA400V 4TB              | 1        | 1.75%   |
| Toshiba HDWD240 4TB                  | 1        | 1.75%   |
| Toshiba DT01ACA300 3TB               | 1        | 1.75%   |
| Seagate ST4000VX000-2AG166 4TB       | 1        | 1.75%   |
| Seagate ST380011A 80GB               | 1        | 1.75%   |
| Seagate ST3160211AS 160GB            | 1        | 1.75%   |
| Seagate ST3000VX006-1HH166 3TB       | 1        | 1.75%   |
| Seagate ST3000NM0033-9ZM178 3TB      | 1        | 1.75%   |
| Seagate ST3000DM001-1ER166 3TB       | 1        | 1.75%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1.75%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 1.75%   |
| Seagate ST1000DM003-1ER162 1TB       | 1        | 1.75%   |
| Seagate ST10000DM005-3AW101 10TB     | 1        | 1.75%   |
| Seagate Expansion Desk 2TB           | 1        | 1.75%   |
| Samsung SSD 970 EVO Plus 500GB       | 1        | 1.75%   |
| Samsung SSD 970 EVO Plus 1TB         | 1        | 1.75%   |
| Samsung SSD 860 EVO 500GB            | 1        | 1.75%   |
| Samsung SSD 860 500GB                | 1        | 1.75%   |
| Samsung SSD 840 Series 250GB         | 1        | 1.75%   |
| Samsung MZHPV512HDGL-00000 512GB SSD | 1        | 1.75%   |
| Patriot Burst Elite 120GB SSD        | 1        | 1.75%   |
| Kingston SUV500MS120G 120GB SSD      | 1        | 1.75%   |
| Kingston SM2280S3G2120G 120GB SSD    | 1        | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 15     | 39.29%  |
| WDC     | 8        | 10     | 28.57%  |
| Hitachi | 5        | 8      | 17.86%  |
| Toshiba | 3        | 5      | 10.71%  |
| HGST    | 1        | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 20%     |
| Kingston            | 3        | 4      | 20%     |
| Crucial             | 2        | 2      | 13.33%  |
| ZHITAI              | 1        | 1      | 6.67%   |
| WDC                 | 1        | 2      | 6.67%   |
| Patriot             | 1        | 1      | 6.67%   |
| Intenso             | 1        | 1      | 6.67%   |
| Hewlett-Packard     | 1        | 1      | 6.67%   |
| DUEX                | 1        | 1      | 6.67%   |
| China               | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 39     | 45.95%  |
| SSD  | 13       | 18     | 35.14%  |
| NVMe | 7        | 9      | 18.92%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 56     | 71.43%  |
| NVMe | 7        | 9      | 25%     |
| SAS  | 1        | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 16       | 22     | 43.24%  |
| 0.51-1.0   | 8        | 10     | 21.62%  |
| 1.01-2.0   | 5        | 8      | 13.51%  |
| 3.01-4.0   | 3        | 8      | 8.11%   |
| 2.01-3.0   | 3        | 7      | 8.11%   |
| 4.01-10.0  | 2        | 2      | 5.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 6        | 25%     |
| 101-250        | 4        | 16.67%  |
| 251-500        | 3        | 12.5%   |
| 2001-3000      | 3        | 12.5%   |
| Unknown        | 3        | 12.5%   |
| 1-20           | 2        | 8.33%   |
| More than 3000 | 1        | 4.17%   |
| 1001-2000      | 1        | 4.17%   |
| 51-100         | 1        | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 34.78%  |
| 1-20           | 3        | 13.04%  |
| 501-1000       | 3        | 13.04%  |
| Unknown        | 3        | 13.04%  |
| 251-500        | 2        | 8.7%    |
| 21-50          | 2        | 8.7%    |
| More than 3000 | 1        | 4.35%   |
| 1001-2000      | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 1      | 9.09%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1        | 1      | 9.09%   |
| WDC WD3200AAJS-65B4A0 320GB      | 1        | 1      | 9.09%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 2      | 9.09%   |
| Seagate ST380011A 80GB           | 1        | 1      | 9.09%   |
| Seagate ST3000VX006-1HH166 3TB   | 1        | 1      | 9.09%   |
| Seagate ST2000DL003-9VT166 2TB   | 1        | 1      | 9.09%   |
| Seagate ST1000DM003-1ER162 1TB   | 1        | 2      | 9.09%   |
| Hitachi HUA723030ALA640 3TB      | 1        | 1      | 9.09%   |
| Hitachi HDS721016CLA382 160GB    | 1        | 1      | 9.09%   |
| DUEX DX300256A5xnEMLC 256GB SSD  | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 5      | 40%     |
| Seagate | 3        | 5      | 30%     |
| Hitachi | 2        | 2      | 20%     |
| DUEX    | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 4      | 37.5%   |
| Seagate | 3        | 5      | 37.5%   |
| Hitachi | 2        | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 11     | 75%     |
| SSD  | 2        | 2      | 25%     |

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
| Works    | 18       | 45     | 60%     |
| Malfunc  | 8        | 13     | 26.67%  |
| Detected | 4        | 8      | 13.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 13       | 39.39%  |
| AMD                          | 7        | 21.21%  |
| Samsung Electronics          | 4        | 12.12%  |
| Nvidia                       | 2        | 6.06%   |
| Yangtze Memory Technologies  | 1        | 3.03%   |
| Toshiba America Info Systems | 1        | 3.03%   |
| Realtek Semiconductor        | 1        | 3.03%   |
| Phison Electronics           | 1        | 3.03%   |
| Marvell Technology Group     | 1        | 3.03%   |
| JMicron Technology           | 1        | 3.03%   |
| Adaptec                      | 1        | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 11.11%  |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 8.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 6.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 4.44%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 4.44%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 4.44%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 4.44%   |
| Yangtze Memory Non-Volatile memory controller                                           | 1        | 2.22%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 2.22%   |
| Samsung Electronics SATA controller                                                     | 1        | 2.22%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 2.22%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 2.22%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 2.22%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 2.22%   |
| Nvidia MCP61 IDE                                                                        | 1        | 2.22%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 2.22%   |
| JMicron JMB58x AHCI SATA controller                                                     | 1        | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 2.22%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 2.22%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 2.22%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 2.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.22%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 1        | 2.22%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.22%   |
| Adaptec SCSI storage controller                                                         | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 17       | 51.52%  |
| NVMe | 7        | 21.21%  |
| IDE  | 7        | 21.21%  |
| RAID | 1        | 3.03%   |
| SCSI | 1        | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 65.22%  |
| AMD    | 8        | 34.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 8.7%    |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz         | 1        | 4.35%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 4.35%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 4.35%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 4.35%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 4.35%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 4.35%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 4.35%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 4.35%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 4.35%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 4.35%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 4.35%   |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1        | 4.35%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 4.35%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 1        | 4.35%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 4.35%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 4.35%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 4.35%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1        | 4.35%   |
| AMD FX-8320 Eight-Core Processor            | 1        | 4.35%   |
| AMD FX-6300 Six-Core Processor              | 1        | 4.35%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 4        | 17.39%  |
| Intel Core 2 Duo   | 3        | 13.04%  |
| Intel Core i7      | 2        | 8.7%    |
| Intel Core i5      | 2        | 8.7%    |
| AMD Ryzen 9        | 2        | 8.7%    |
| AMD Ryzen 7        | 2        | 8.7%    |
| AMD FX             | 2        | 8.7%    |
| Intel Pentium Dual | 1        | 4.35%   |
| Intel Core i3      | 1        | 4.35%   |
| Intel Celeron      | 1        | 4.35%   |
| Intel Atom         | 1        | 4.35%   |
| AMD Ryzen 5        | 1        | 4.35%   |
| AMD A8             | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 39.13%  |
| 2      | 5        | 21.74%  |
| 8      | 3        | 13.04%  |
| 16     | 1        | 4.35%   |
| 14     | 1        | 4.35%   |
| 12     | 1        | 4.35%   |
| 10     | 1        | 4.35%   |
| 6      | 1        | 4.35%   |
| 3      | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 95.65%  |
| 2      | 1        | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 60.87%  |
| 1      | 9        | 39.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 13.04%  |
| 0x306f2    | 2        | 8.7%    |
| 0x1067a    | 2        | 8.7%    |
| 0x0a201016 | 2        | 8.7%    |
| 0xa0653    | 1        | 4.35%   |
| 0x906ea    | 1        | 4.35%   |
| 0x906e9    | 1        | 4.35%   |
| 0x6fd      | 1        | 4.35%   |
| 0x506e3    | 1        | 4.35%   |
| 0x406c4    | 1        | 4.35%   |
| 0x306e4    | 1        | 4.35%   |
| 0x306a9    | 1        | 4.35%   |
| 0x106c2    | 1        | 4.35%   |
| 0x08701021 | 1        | 4.35%   |
| 0x0810100b | 1        | 4.35%   |
| 0x07030105 | 1        | 4.35%   |
| 0x06000822 | 1        | 4.35%   |
| 0x00000000 | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Penryn     | 3        | 13.04%  |
| Zen 3      | 2        | 8.7%    |
| Zen 2      | 2        | 8.7%    |
| Piledriver | 2        | 8.7%    |
| KabyLake   | 2        | 8.7%    |
| IvyBridge  | 2        | 8.7%    |
| Haswell    | 2        | 8.7%    |
| Core       | 2        | 8.7%    |
| Zen        | 1        | 4.35%   |
| Skylake    | 1        | 4.35%   |
| Silvermont | 1        | 4.35%   |
| Puma       | 1        | 4.35%   |
| CometLake  | 1        | 4.35%   |
| Bonnell    | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 11       | 45.83%  |
| AMD    | 8        | 33.33%  |
| Intel  | 5        | 20.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 8.33%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 8.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 8.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 4.17%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 4.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 4.17%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 4.17%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 4.17%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 4.17%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1        | 4.17%   |
| Nvidia C79 [ION]                                                                         | 1        | 4.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 4.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 4.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 4.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 4.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 4.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1        | 4.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 4.17%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 10       | 43.48%  |
| 1 x AMD        | 8        | 34.78%  |
| 1 x Intel      | 4        | 17.39%  |
| Intel + Nvidia | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 17       | 73.91%  |
| Proprietary | 5        | 21.74%  |
| Unknown     | 1        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 30.43%  |
| 0.51-1.0   | 5        | 21.74%  |
| 7.01-8.0   | 3        | 13.04%  |
| 8.01-16.0  | 3        | 13.04%  |
| 0.01-0.5   | 2        | 8.7%    |
| 5.01-6.0   | 1        | 4.35%   |
| 2.01-3.0   | 1        | 4.35%   |
| 1.01-2.0   | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 20%     |
| Hewlett-Packard      | 3        | 12%     |
| Dell                 | 3        | 12%     |
| Ancor Communications | 3        | 12%     |
| BenQ                 | 2        | 8%      |
| Acer                 | 2        | 8%      |
| Wacom                | 1        | 4%      |
| Lenovo               | 1        | 4%      |
| IOD                  | 1        | 4%      |
| Goldstar             | 1        | 4%      |
| GDH                  | 1        | 4%      |
| AOC                  | 1        | 4%      |
| Unknown              | 1        | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1        | 4%      |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch  | 1        | 4%      |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1        | 4%      |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1        | 4%      |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1        | 4%      |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 4%      |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                | 1        | 4%      |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1        | 4%      |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1        | 4%      |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch          | 1        | 4%      |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 4%      |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                   | 1        | 4%      |
| GDH CHHWJT GDH0030 1440x900 1150x650mm 52.0-inch                      | 1        | 4%      |
| Dell SP2208WFP DEL4038 1680x1050 473x296mm 22.0-inch                  | 1        | 4%      |
| Dell LCD Monitor P190S 3200x1080                                      | 1        | 4%      |
| Dell LCD Monitor DELA026 1920x1200 520x330mm 24.2-inch                | 1        | 4%      |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                    | 1        | 4%      |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1        | 4%      |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1        | 4%      |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 4%      |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 4%      |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 1        | 4%      |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                    | 1        | 4%      |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1        | 4%      |
| Unknown                                                               | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 44%     |
| 1280x1024 (SXGA)   | 3        | 12%     |
| 3840x2160 (4K)     | 2        | 8%      |
| 1920x1200 (WUXGA)  | 2        | 8%      |
| 1366x768 (WXGA)    | 2        | 8%      |
| 3440x1440          | 1        | 4%      |
| 3200x1080          | 1        | 4%      |
| 1680x1050 (WSXGA+) | 1        | 4%      |
| 1600x1200          | 1        | 4%      |
| Unknown            | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 16.67%  |
| 24      | 4        | 16.67%  |
| 21      | 3        | 12.5%   |
| 23      | 2        | 8.33%   |
| 20      | 2        | 8.33%   |
| 17      | 2        | 8.33%   |
| 52      | 1        | 4.17%   |
| 34      | 1        | 4.17%   |
| 22      | 1        | 4.17%   |
| 19      | 1        | 4.17%   |
| 18      | 1        | 4.17%   |
| 15      | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 39.13%  |
| 401-500     | 6        | 26.09%  |
| 301-350     | 3        | 13.04%  |
| 701-800     | 1        | 4.35%   |
| 601-700     | 1        | 4.35%   |
| 351-400     | 1        | 4.35%   |
| 1001-1500   | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 59.09%  |
| 5/4     | 3        | 13.64%  |
| 16/10   | 3        | 13.64%  |
| 4/3     | 1        | 4.55%   |
| 21/9    | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 30.43%  |
| 301-350        | 4        | 17.39%  |
| 151-200        | 3        | 13.04%  |
| 141-150        | 3        | 13.04%  |
| 251-300        | 2        | 8.7%    |
| More than 1000 | 1        | 4.35%   |
| 351-500        | 1        | 4.35%   |
| 101-110        | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 66.67%  |
| 101-120 | 5        | 20.83%  |
| 1-50    | 1        | 4.17%   |
| 121-160 | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 78.26%  |
| 2     | 2        | 8.7%    |
| 0     | 2        | 8.7%    |
| 3     | 1        | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 41.18%  |
| Intel                 | 10       | 29.41%  |
| Qualcomm Atheros      | 3        | 8.82%   |
| TP-Link               | 1        | 2.94%   |
| Ralink Technology     | 1        | 2.94%   |
| Ralink                | 1        | 2.94%   |
| Qualcomm              | 1        | 2.94%   |
| Nvidia                | 1        | 2.94%   |
| Broadcom Limited      | 1        | 2.94%   |
| Broadcom              | 1        | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 20.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 7.69%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 5.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 2.56%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 2.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.56%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.56%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 2.56%   |
| Qualcomm Mobile Router                                            | 1        | 2.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 2.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 2.56%   |
| Nvidia MCP79 Ethernet                                             | 1        | 2.56%   |
| Intel Wireless-AC 9260                                            | 1        | 2.56%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.56%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1        | 2.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 2.56%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 2.56%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 36.36%  |
| Qualcomm Atheros      | 3        | 27.27%  |
| TP-Link               | 1        | 9.09%   |
| Realtek Semiconductor | 1        | 9.09%   |
| Ralink Technology     | 1        | 9.09%   |
| Ralink                | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 9.09%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 9.09%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 9.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 9.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 9.09%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 9.09%   |
| Intel Wireless-AC 9260                                         | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 9.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 50%     |
| Intel                 | 9        | 32.14%  |
| Qualcomm Atheros      | 1        | 3.57%   |
| Qualcomm              | 1        | 3.57%   |
| Nvidia                | 1        | 3.57%   |
| Broadcom Limited      | 1        | 3.57%   |
| Broadcom              | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 28.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 10.71%  |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 7.14%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 3.57%   |
| Qualcomm Mobile Router                                            | 1        | 3.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.57%   |
| Nvidia MCP79 Ethernet                                             | 1        | 3.57%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.57%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.57%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 3.57%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 3.57%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 3.57%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 3.57%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 67.65%  |
| WiFi     | 11       | 32.35%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 82.61%  |
| WiFi     | 4        | 17.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 60.87%  |
| 2     | 6        | 26.09%  |
| 3     | 2        | 8.7%    |
| 4     | 1        | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 95.65%  |
| Yes  | 1        | 4.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 4        | 50%     |
| Intel                    | 3        | 37.5%   |
| Micro Star International | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 50%     |
| Micro Star International Bluetooth Dongle           | 1        | 12.5%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 12.5%   |
| Intel AX200 Bluetooth                               | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 10       | 29.41%  |
| AMD              | 10       | 29.41%  |
| Nvidia           | 9        | 26.47%  |
| Creative Labs    | 4        | 11.76%  |
| ASUSTek Computer | 1        | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 10%     |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 7.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 5%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 5%      |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2        | 5%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 5%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 5%      |
| Nvidia MCP79 High Definition Audio                                                                | 1        | 2.5%    |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 2.5%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 2.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 2.5%    |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 2.5%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 2.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 2.5%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1        | 2.5%    |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1        | 2.5%    |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1        | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 2.5%    |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 2.5%    |
| AMD FCH Azalia Controller                                                                         | 1        | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 1        | 2.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 2.5%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1        | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 22.22%  |
| Samsung Electronics | 4        | 14.81%  |
| Unknown             | 2        | 7.41%   |
| Team                | 2        | 7.41%   |
| SK hynix            | 2        | 7.41%   |
| Corsair             | 2        | 7.41%   |
| Transcend           | 1        | 3.7%    |
| Strontium           | 1        | 3.7%    |
| Silicon Power       | 1        | 3.7%    |
| GLOWAY              | 1        | 3.7%    |
| G.Skill             | 1        | 3.7%    |
| Crucial             | 1        | 3.7%    |
| AMD                 | 1        | 3.7%    |
| A-DATA Technology   | 1        | 3.7%    |
| Unknown             | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 6.9%    |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1        | 3.45%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 1        | 3.45%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s          | 1        | 3.45%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1        | 3.45%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 3.45%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1        | 3.45%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s   | 1        | 3.45%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 3.45%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s        | 1        | 3.45%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 3.45%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 3.45%   |
| Samsung RAM M378B5173EB0-CK0 4096MB DIMM DDR3 1600MT/s      | 1        | 3.45%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s             | 1        | 3.45%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s        | 1        | 3.45%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 3.45%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s         | 1        | 3.45%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 975MT/s      | 1        | 3.45%   |
| Kingston RAM 9905678-023.A00G 8GB DIMM DDR4 2187MT/s        | 1        | 3.45%   |
| GLOWAY RAM TYA4U2666D19161C 16GB DIMM DDR4 2667MT/s         | 1        | 3.45%   |
| G.Skill RAM F4-3200C16-16GTZSW 16384MB DIMM DDR4 3200MT/s   | 1        | 3.45%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s      | 1        | 3.45%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4096MB DIMM DDR4 2472MT/s    | 1        | 3.45%   |
| Corsair RAM CMZ8GX3M1A1600C10 8192MB DIMM DDR3 1600MT/s     | 1        | 3.45%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s       | 1        | 3.45%   |
| AMD RAM R534G1601S1SL 4GB DIMM DDR3 1600MT/s                | 1        | 3.45%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 3.45%   |
| Unknown                                                     | 1        | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 10       | 47.62%  |
| DDR3  | 7        | 33.33%  |
| SDRAM | 2        | 9.52%   |
| DDR2  | 2        | 9.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 18       | 85.71%  |
| SODIMM  | 1        | 4.76%   |
| RIMM    | 1        | 4.76%   |
| FB-DIMM | 1        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 7        | 31.82%  |
| 8192  | 5        | 22.73%  |
| 16384 | 3        | 13.64%  |
| 2048  | 3        | 13.64%  |
| 32768 | 2        | 9.09%   |
| 1024  | 2        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 16.67%  |
| 3600    | 2        | 8.33%   |
| 3200    | 2        | 8.33%   |
| 2400    | 2        | 8.33%   |
| 1333    | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |
| 65535   | 1        | 4.17%   |
| 3800    | 1        | 4.17%   |
| 2933    | 1        | 4.17%   |
| 2667    | 1        | 4.17%   |
| 2472    | 1        | 4.17%   |
| 2187    | 1        | 4.17%   |
| 2133    | 1        | 4.17%   |
| 1866    | 1        | 4.17%   |
| 975     | 1        | 4.17%   |
| 667     | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| QinHeng Electronics | 1        | 25%     |
| Hewlett-Packard     | 1        | 25%     |
| Dell                | 1        | 25%     |
| Canon               | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| QinHeng CH340S               | 1        | 25%     |
| HP OfficeJet Pro 9010 series | 1        | 25%     |
| Dell 2330d Laser Printer     | 1        | 25%     |
| Canon LiDE 300               | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 4        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 2        | 50%     |
| Logitech QuickCam Pro 9000      | 1        | 25%     |
| Logitech C922 Pro Stream Webcam | 1        | 25%     |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 17       | 73.91%  |
| 1     | 3        | 13.04%  |
| 4     | 1        | 4.35%   |
| 3     | 1        | 4.35%   |
| 2     | 1        | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 3        | 25%     |
| Unassigned class         | 2        | 16.67%  |
| Graphics card            | 2        | 16.67%  |
| Communication controller | 2        | 16.67%  |
| Net/wireless             | 1        | 8.33%   |
| Net/ethernet             | 1        | 8.33%   |
| Chipcard                 | 1        | 8.33%   |

