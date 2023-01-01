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

Total: 31

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| ASRock   | B550 Taichi             | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| Dell     | 0MY171 A00              | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| ASUSTek  | SABERTOOTH X99          | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| HP       | 8906 SMVB               | [d000e4e926](https://linux-hardware.org/?probe=d000e4e926) | Dec 02, 2022 |
| Lenovo   | 31900058 STD            | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
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
| 5.15.19        | 4        | 14.29%  |
| 5.19.17        | 3        | 10.71%  |
| 5.15.63        | 2        | 7.14%   |
| 5.15.30-Unraid | 2        | 7.14%   |
| 5.15.27        | 2        | 7.14%   |
| 5.19.16        | 1        | 3.57%   |
| 5.17.2         | 1        | 3.57%   |
| 5.17.0-custom  | 1        | 3.57%   |
| 5.16.18        | 1        | 3.57%   |
| 5.16.13        | 1        | 3.57%   |
| 5.16.11        | 1        | 3.57%   |
| 5.15.6         | 1        | 3.57%   |
| 5.15.38        | 1        | 3.57%   |
| 5.15.14        | 1        | 3.57%   |
| 5.15.13        | 1        | 3.57%   |
| 5.14.15-Unraid | 1        | 3.57%   |
| 5.14.15        | 1        | 3.57%   |
| 5.14.12        | 1        | 3.57%   |
| 5.14.11        | 1        | 3.57%   |
| 5.13.12        | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.19 | 4        | 14.29%  |
| 5.19.17 | 3        | 10.71%  |
| 5.15.63 | 2        | 7.14%   |
| 5.15.30 | 2        | 7.14%   |
| 5.15.27 | 2        | 7.14%   |
| 5.14.15 | 2        | 7.14%   |
| 5.19.16 | 1        | 3.57%   |
| 5.17.2  | 1        | 3.57%   |
| 5.17.0  | 1        | 3.57%   |
| 5.16.18 | 1        | 3.57%   |
| 5.16.13 | 1        | 3.57%   |
| 5.16.11 | 1        | 3.57%   |
| 5.15.6  | 1        | 3.57%   |
| 5.15.38 | 1        | 3.57%   |
| 5.15.14 | 1        | 3.57%   |
| 5.15.13 | 1        | 3.57%   |
| 5.14.12 | 1        | 3.57%   |
| 5.14.11 | 1        | 3.57%   |
| 5.13.12 | 1        | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 14       | 50%     |
| 5.19    | 4        | 14.29%  |
| 5.14    | 4        | 14.29%  |
| 5.16    | 3        | 10.71%  |
| 5.17    | 2        | 7.14%   |
| 5.13    | 1        | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 26       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| KDE5      | 13       | 48.15%  |
| XFCE      | 7        | 25.93%  |
| Unknown   | 5        | 18.52%  |
| X-Generic | 1        | 3.7%    |
| FVWM      | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 16       | 57.14%  |
| Tty     | 8        | 28.57%  |
| Unknown | 3        | 10.71%  |
| Wayland | 1        | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 14       | 51.85%  |
| Unknown | 8        | 29.63%  |
| XDM     | 3        | 11.11%  |
| LightDM | 2        | 7.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 16       | 61.54%  |
| Unknown     | 4        | 15.38%  |
| ru_RU       | 1        | 3.85%   |
| pt_PT       | 1        | 3.85%   |
| it_IT       | 1        | 3.85%   |
| es_ES.UTF8  | 1        | 3.85%   |
| en_US.ASCII | 1        | 3.85%   |
| en_GB       | 1        | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 14       | 53.85%  |
| EFI  | 12       | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 16       | 61.54%  |
| Btrfs   | 4        | 15.38%  |
| Xfs     | 3        | 11.54%  |
| Overlay | 2        | 7.69%   |
| F2fs    | 1        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 20       | 74.07%  |
| MBR     | 4        | 14.81%  |
| Unknown | 3        | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 70.37%  |
| Yes       | 8        | 29.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 73.08%  |
| Yes       | 7        | 26.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 7        | 26.92%  |
| Hewlett-Packard     | 4        | 15.38%  |
| ASUSTek Computer    | 4        | 15.38%  |
| ASRock              | 4        | 15.38%  |
| Dell                | 2        | 7.69%   |
| Lenovo              | 1        | 3.85%   |
| Gigabyte Technology | 1        | 3.85%   |
| Biostar             | 1        | 3.85%   |
| Acer                | 1        | 3.85%   |
| Unknown             | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7C52                          | 1        | 3.85%   |
| MSI MS-7C02                          | 1        | 3.85%   |
| MSI MS-7996                          | 1        | 3.85%   |
| MSI MS-7788                          | 1        | 3.85%   |
| MSI MS-7693                          | 1        | 3.85%   |
| MSI MS-7529                          | 1        | 3.85%   |
| MSI MS-7365                          | 1        | 3.85%   |
| Lenovo H50-05 90BH001WIX             | 1        | 3.85%   |
| HP Z440 Workstation                  | 1        | 3.85%   |
| HP xw8400 Workstation                | 1        | 3.85%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 3.85%   |
| HP Compaq dc7900 Small Form Factor   | 1        | 3.85%   |
| Gigabyte N3160TN                     | 1        | 3.85%   |
| Dell Precision WorkStation 690       | 1        | 3.85%   |
| Dell OptiPlex 780                    | 1        | 3.85%   |
| Biostar X470GTA                      | 1        | 3.85%   |
| ASUS TUF B450-PLUS GAMING            | 1        | 3.85%   |
| ASUS ROG CROSSHAIR VIII HERO         | 1        | 3.85%   |
| ASUS PRIME Z390-A                    | 1        | 3.85%   |
| ASUS All Series                      | 1        | 3.85%   |
| ASRock N68-S3 FX                     | 1        | 3.85%   |
| ASRock H410M-ITX/ac                  | 1        | 3.85%   |
| ASRock H270 Pro4                     | 1        | 3.85%   |
| ASRock B550 Taichi                   | 1        | 3.85%   |
| Acer Aspire R3610                    | 1        | 3.85%   |
| Unknown                              | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MSI MS-7C52      | 1        | 3.85%   |
| MSI MS-7C02      | 1        | 3.85%   |
| MSI MS-7996      | 1        | 3.85%   |
| MSI MS-7788      | 1        | 3.85%   |
| MSI MS-7693      | 1        | 3.85%   |
| MSI MS-7529      | 1        | 3.85%   |
| MSI MS-7365      | 1        | 3.85%   |
| Lenovo H50-05    | 1        | 3.85%   |
| HP Z440          | 1        | 3.85%   |
| HP xw8400        | 1        | 3.85%   |
| HP Pavilion      | 1        | 3.85%   |
| HP Compaq        | 1        | 3.85%   |
| Gigabyte N3160TN | 1        | 3.85%   |
| Dell Precision   | 1        | 3.85%   |
| Dell OptiPlex    | 1        | 3.85%   |
| Biostar X470GTA  | 1        | 3.85%   |
| ASUS TUF         | 1        | 3.85%   |
| ASUS ROG         | 1        | 3.85%   |
| ASUS PRIME       | 1        | 3.85%   |
| ASUS All         | 1        | 3.85%   |
| ASRock N68-S3    | 1        | 3.85%   |
| ASRock H410M-ITX | 1        | 3.85%   |
| ASRock H270      | 1        | 3.85%   |
| ASRock B550      | 1        | 3.85%   |
| Acer Aspire      | 1        | 3.85%   |
| Unknown          | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 11.54%  |
| 2011 | 3        | 11.54%  |
| 2008 | 3        | 11.54%  |
| 2022 | 2        | 7.69%   |
| 2020 | 2        | 7.69%   |
| 2018 | 2        | 7.69%   |
| 2017 | 2        | 7.69%   |
| 2015 | 2        | 7.69%   |
| 2014 | 2        | 7.69%   |
| 2009 | 2        | 7.69%   |
| 2021 | 1        | 3.85%   |
| 2016 | 1        | 3.85%   |
| 2007 | 1        | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 26       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 26       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 7        | 25.93%  |
| 32.01-64.0  | 5        | 18.52%  |
| 3.01-4.0    | 4        | 14.81%  |
| 64.01-256.0 | 4        | 14.81%  |
| 4.01-8.0    | 2        | 7.41%   |
| 1.01-2.0    | 2        | 7.41%   |
| 8.01-16.0   | 2        | 7.41%   |
| 24.01-32.0  | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 7        | 25.93%  |
| 2.01-3.0   | 6        | 22.22%  |
| 1.01-2.0   | 6        | 22.22%  |
| 0.51-1.0   | 4        | 14.81%  |
| 32.01-64.0 | 1        | 3.7%    |
| 3.01-4.0   | 1        | 3.7%    |
| 8.01-16.0  | 1        | 3.7%    |
| 0.01-0.5   | 1        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 8        | 28.57%  |
| 2      | 7        | 25%     |
| 1      | 6        | 21.43%  |
| 6      | 3        | 10.71%  |
| 4      | 2        | 7.14%   |
| 9      | 1        | 3.57%   |
| 0      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 51.85%  |
| No        | 13       | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 100%    |

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
| No        | 16       | 61.54%  |
| Yes       | 10       | 38.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 6        | 23.08%  |
| UK           | 3        | 11.54%  |
| Kazakhstan   | 3        | 11.54%  |
| Italy        | 3        | 11.54%  |
| Russia       | 2        | 7.69%   |
| Hong Kong    | 2        | 7.69%   |
| Brazil       | 2        | 7.69%   |
| Spain        | 1        | 3.85%   |
| South Africa | 1        | 3.85%   |
| Portugal     | 1        | 3.85%   |
| Japan        | 1        | 3.85%   |
| Canada       | 1        | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Ust-Kamenogorsk   | 2        | 7.69%   |
| Winter Springs    | 1        | 3.85%   |
| Tsukuba           | 1        | 3.85%   |
| Toronto           | 1        | 3.85%   |
| St Petersburg     | 1        | 3.85%   |
| Sham Shui Po      | 1        | 3.85%   |
| Senhora da Hora   | 1        | 3.85%   |
| Santa Cruz do Sul | 1        | 3.85%   |
| Saint Paul        | 1        | 3.85%   |
| Rome              | 1        | 3.85%   |
| Rock              | 1        | 3.85%   |
| Porto Alegre      | 1        | 3.85%   |
| Moscow            | 1        | 3.85%   |
| Milwaukee         | 1        | 3.85%   |
| Milan             | 1        | 3.85%   |
| Mead              | 1        | 3.85%   |
| McKinney          | 1        | 3.85%   |
| London            | 1        | 3.85%   |
| Karaganda         | 1        | 3.85%   |
| Granada           | 1        | 3.85%   |
| Frosinone         | 1        | 3.85%   |
| Colorado Springs  | 1        | 3.85%   |
| Central           | 1        | 3.85%   |
| Cape Town         | 1        | 3.85%   |
| Belfast           | 1        | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 21.82%  |
| WDC                 | 9        | 16     | 16.36%  |
| Samsung Electronics | 6        | 9      | 10.91%  |
| Toshiba             | 5        | 9      | 9.09%   |
| Hitachi             | 5        | 8      | 9.09%   |
| Kingston            | 3        | 5      | 5.45%   |
| Crucial             | 2        | 2      | 3.64%   |
| ZHITAI              | 1        | 2      | 1.82%   |
| PNY                 | 1        | 1      | 1.82%   |
| Phison Electronics  | 1        | 1      | 1.82%   |
| Patriot             | 1        | 1      | 1.82%   |
| KIOXIA              | 1        | 1      | 1.82%   |
| Intenso             | 1        | 1      | 1.82%   |
| Intel               | 1        | 2      | 1.82%   |
| HGST                | 1        | 1      | 1.82%   |
| Hewlett-Packard     | 1        | 1      | 1.82%   |
| Gigabyte Technology | 1        | 1      | 1.82%   |
| DUEX                | 1        | 1      | 1.82%   |
| China               | 1        | 1      | 1.82%   |
| A-DATA Technology   | 1        | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 2.94%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 2.94%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 2.94%   |
| Samsung SSD 970 EVO 250GB        | 2        | 2.94%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 2.94%   |
| ZHITAI SC001 Active 1TB SSD      | 1        | 1.47%   |
| ZHITAI PC005 Active 512GB        | 1        | 1.47%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 1.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 1.47%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1        | 1.47%   |
| WDC WD40EJRX-89T1XY0 4TB         | 1        | 1.47%   |
| WDC WD400BD-60LTA0 40GB          | 1        | 1.47%   |
| WDC WD3200AAJS-65B4A0 320GB      | 1        | 1.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 1.47%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 1.47%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1        | 1.47%   |
| WDC WD10EZEX-00MFCA0 1TB         | 1        | 1.47%   |
| Toshiba THNSNH128GBST SSD        | 1        | 1.47%   |
| Toshiba THNSF5512GPUK 512GB      | 1        | 1.47%   |
| Toshiba MK5055GSX 500GB          | 1        | 1.47%   |
| Toshiba MD04ABA400V 4TB          | 1        | 1.47%   |
| Toshiba HDWD240 4TB              | 1        | 1.47%   |
| Toshiba DT01ACA300 3TB           | 1        | 1.47%   |
| Seagate ST4000VX000-2AG166 4TB   | 1        | 1.47%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 1.47%   |
| Seagate ST380011A 80GB           | 1        | 1.47%   |
| Seagate ST3160211AS 160GB        | 1        | 1.47%   |
| Seagate ST3000VX006-1HH166 3TB   | 1        | 1.47%   |
| Seagate ST3000NM0033-9ZM178 3TB  | 1        | 1.47%   |
| Seagate ST3000DM001-1ER166 3TB   | 1        | 1.47%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 1.47%   |
| Seagate ST2000DL003-9VT166 2TB   | 1        | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 1.47%   |
| Seagate ST1000DM003-1ER162 1TB   | 1        | 1.47%   |
| Seagate ST10000DM005-3AW101 10TB | 1        | 1.47%   |
| Seagate Expansion Desk 5TB       | 1        | 1.47%   |
| Samsung SSD 970 EVO Plus 500GB   | 1        | 1.47%   |
| Samsung SSD 970 EVO Plus 1TB     | 1        | 1.47%   |
| Samsung SSD 860 EVO 500GB        | 1        | 1.47%   |
| Samsung SSD 860 500GB            | 1        | 1.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 12       | 16     | 38.71%  |
| WDC     | 9        | 14     | 29.03%  |
| Hitachi | 5        | 8      | 16.13%  |
| Toshiba | 4        | 6      | 12.9%   |
| HGST    | 1        | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 16.67%  |
| Kingston            | 3        | 5      | 16.67%  |
| Crucial             | 2        | 2      | 11.11%  |
| ZHITAI              | 1        | 1      | 5.56%   |
| WDC                 | 1        | 2      | 5.56%   |
| Toshiba             | 1        | 1      | 5.56%   |
| PNY                 | 1        | 1      | 5.56%   |
| Patriot             | 1        | 1      | 5.56%   |
| Intenso             | 1        | 1      | 5.56%   |
| Intel               | 1        | 2      | 5.56%   |
| Hewlett-Packard     | 1        | 1      | 5.56%   |
| DUEX                | 1        | 1      | 5.56%   |
| China               | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 45     | 44.19%  |
| SSD  | 16       | 24     | 37.21%  |
| NVMe | 8        | 11     | 18.6%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 23       | 68     | 71.88%  |
| NVMe | 8        | 11     | 25%     |
| SAS  | 1        | 1      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 26     | 41.86%  |
| 0.51-1.0   | 9        | 15     | 20.93%  |
| 3.01-4.0   | 5        | 11     | 11.63%  |
| 1.01-2.0   | 5        | 7      | 11.63%  |
| 2.01-3.0   | 3        | 7      | 6.98%   |
| 4.01-10.0  | 3        | 3      | 6.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 6        | 20.69%  |
| 101-250        | 5        | 17.24%  |
| 2001-3000      | 4        | 13.79%  |
| Unknown        | 4        | 13.79%  |
| 251-500        | 3        | 10.34%  |
| More than 3000 | 2        | 6.9%    |
| 1001-2000      | 2        | 6.9%    |
| 1-20           | 2        | 6.9%    |
| 51-100         | 1        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 28.57%  |
| 501-1000       | 4        | 14.29%  |
| Unknown        | 4        | 14.29%  |
| 21-50          | 3        | 10.71%  |
| 1001-2000      | 3        | 10.71%  |
| 1-20           | 3        | 10.71%  |
| 251-500        | 2        | 7.14%   |
| More than 3000 | 1        | 3.57%   |

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
| Works    | 20       | 53     | 60.61%  |
| Malfunc  | 8        | 13     | 24.24%  |
| Detected | 5        | 14     | 15.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 14       | 35%     |
| AMD                          | 9        | 22.5%   |
| Samsung Electronics          | 4        | 10%     |
| Nvidia                       | 2        | 5%      |
| Marvell Technology Group     | 2        | 5%      |
| Yangtze Memory Technologies  | 1        | 2.5%    |
| Toshiba America Info Systems | 1        | 2.5%    |
| Realtek Semiconductor        | 1        | 2.5%    |
| Phison Electronics           | 1        | 2.5%    |
| LSI Logic / Symbios Logic    | 1        | 2.5%    |
| KIOXIA                       | 1        | 2.5%    |
| JMicron Technology           | 1        | 2.5%    |
| ASMedia Technology           | 1        | 2.5%    |
| Adaptec                      | 1        | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 11.11%  |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 9.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 5.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 3.7%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 3.7%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 3.7%    |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 3.7%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 3.7%    |
| Yangtze Memory Non-Volatile memory controller                                           | 1        | 1.85%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.85%   |
| Samsung Electronics SATA controller                                                     | 1        | 1.85%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 1.85%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.85%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 1.85%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.85%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.85%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.85%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 1.85%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 1        | 1.85%   |
| JMicron JMB58x AHCI SATA controller                                                     | 1        | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.85%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 1.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.85%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 1        | 1.85%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.85%   |
| Adaptec SCSI storage controller                                                         | 1        | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 51.28%  |
| NVMe | 8        | 20.51%  |
| IDE  | 8        | 20.51%  |
| SCSI | 2        | 5.13%   |
| RAID | 1        | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 61.54%  |
| AMD    | 10       | 38.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 7.41%   |
| Intel Xeon CPU X5355 @ 2.66GHz              | 1        | 3.7%    |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz         | 1        | 3.7%    |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 3.7%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 3.7%    |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 3.7%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 3.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 3.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 3.7%    |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 3.7%    |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 3.7%    |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 3.7%    |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 3.7%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 3.7%    |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1        | 3.7%    |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 3.7%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 1        | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 3.7%    |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics  | 1        | 3.7%    |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 3.7%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 3.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 3.7%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1        | 3.7%    |
| AMD FX-8320 Eight-Core Processor            | 1        | 3.7%    |
| AMD FX-6300 Six-Core Processor              | 1        | 3.7%    |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 1        | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 5        | 18.52%  |
| Intel Core i7      | 3        | 11.11%  |
| Intel Core 2 Duo   | 3        | 11.11%  |
| Intel Core i5      | 2        | 7.41%   |
| AMD Ryzen 9        | 2        | 7.41%   |
| AMD Ryzen 7        | 2        | 7.41%   |
| AMD Ryzen 5        | 2        | 7.41%   |
| AMD FX             | 2        | 7.41%   |
| Intel Pentium Dual | 1        | 3.7%    |
| Intel Core i3      | 1        | 3.7%    |
| Intel Celeron      | 1        | 3.7%    |
| Intel Atom         | 1        | 3.7%    |
| AMD Ryzen 7 PRO    | 1        | 3.7%    |
| AMD A8             | 1        | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 33.33%  |
| 8      | 5        | 18.52%  |
| 2      | 5        | 18.52%  |
| 6      | 3        | 11.11%  |
| 16     | 1        | 3.7%    |
| 14     | 1        | 3.7%    |
| 12     | 1        | 3.7%    |
| 10     | 1        | 3.7%    |
| 3      | 1        | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 92.31%  |
| 2      | 2        | 7.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 16       | 61.54%  |
| 1      | 10       | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 26       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 11.54%  |
| 0x306f2    | 2        | 7.69%   |
| 0x1067a    | 2        | 7.69%   |
| 0x0a50000c | 2        | 7.69%   |
| 0x0a201016 | 2        | 7.69%   |
| 0xa0653    | 1        | 3.85%   |
| 0x906ea    | 1        | 3.85%   |
| 0x906e9    | 1        | 3.85%   |
| 0x6fd      | 1        | 3.85%   |
| 0x6fb      | 1        | 3.85%   |
| 0x506e3    | 1        | 3.85%   |
| 0x406c4    | 1        | 3.85%   |
| 0x306e4    | 1        | 3.85%   |
| 0x306a9    | 1        | 3.85%   |
| 0x106c2    | 1        | 3.85%   |
| 0x08701021 | 1        | 3.85%   |
| 0x0810100b | 1        | 3.85%   |
| 0x07030105 | 1        | 3.85%   |
| 0x06000822 | 1        | 3.85%   |
| 0x00000000 | 1        | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Zen 3      | 4        | 15.38%  |
| Penryn     | 3        | 11.54%  |
| Core       | 3        | 11.54%  |
| Zen 2      | 2        | 7.69%   |
| Piledriver | 2        | 7.69%   |
| KabyLake   | 2        | 7.69%   |
| IvyBridge  | 2        | 7.69%   |
| Haswell    | 2        | 7.69%   |
| Zen        | 1        | 3.85%   |
| Skylake    | 1        | 3.85%   |
| Silvermont | 1        | 3.85%   |
| Puma       | 1        | 3.85%   |
| CometLake  | 1        | 3.85%   |
| Bonnell    | 1        | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 44.44%  |
| AMD    | 10       | 37.04%  |
| Intel  | 5        | 18.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 7.14%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 7.14%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 7.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 7.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 7.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 3.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 3.57%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 3.57%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 3.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 3.57%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 3.57%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 3.57%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 3.57%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1        | 3.57%   |
| Nvidia C79 [ION]                                                                         | 1        | 3.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 3.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.57%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 3.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 3.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 3.57%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 3.57%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1        | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 11       | 42.31%  |
| 1 x AMD        | 9        | 34.62%  |
| 1 x Intel      | 4        | 15.38%  |
| 2 x AMD        | 1        | 3.85%   |
| Intel + Nvidia | 1        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 73.08%  |
| Proprietary | 6        | 23.08%  |
| Unknown     | 1        | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 26.92%  |
| 0.51-1.0   | 5        | 19.23%  |
| 7.01-8.0   | 3        | 11.54%  |
| 8.01-16.0  | 3        | 11.54%  |
| 0.01-0.5   | 3        | 11.54%  |
| 3.01-4.0   | 2        | 7.69%   |
| 5.01-6.0   | 1        | 3.85%   |
| 2.01-3.0   | 1        | 3.85%   |
| 1.01-2.0   | 1        | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 6        | 21.43%  |
| Dell                 | 5        | 17.86%  |
| Hewlett-Packard      | 3        | 10.71%  |
| Ancor Communications | 3        | 10.71%  |
| BenQ                 | 2        | 7.14%   |
| Acer                 | 2        | 7.14%   |
| Wacom                | 1        | 3.57%   |
| Lenovo               | 1        | 3.57%   |
| IOD                  | 1        | 3.57%   |
| Goldstar             | 1        | 3.57%   |
| GDH                  | 1        | 3.57%   |
| AOC                  | 1        | 3.57%   |
| Unknown              | 1        | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch  | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1        | 3.57%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1        | 3.57%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1        | 3.57%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 3.57%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                | 1        | 3.57%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1        | 3.57%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1        | 3.57%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1        | 3.57%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 3.57%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                   | 1        | 3.57%   |
| GDH CHHWJT GDH0030 1440x900 1150x650mm 52.0-inch                      | 1        | 3.57%   |
| Dell U2722D DEL422D 2560x1440 597x336mm 27.0-inch                     | 1        | 3.57%   |
| Dell SP2208WFP DEL4038 1680x1050 473x296mm 22.0-inch                  | 1        | 3.57%   |
| Dell LCD Monitor P190S 3200x1080                                      | 1        | 3.57%   |
| Dell LCD Monitor DELA026 1920x1200 520x330mm 24.2-inch                | 1        | 3.57%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 1        | 3.57%   |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                    | 1        | 3.57%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1        | 3.57%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1        | 3.57%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 3.57%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 3.57%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 620x340mm 27.8-inch | 1        | 3.57%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                    | 1        | 3.57%   |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1        | 3.57%   |
| Unknown                                                               | 1        | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 39.29%  |
| 1280x1024 (SXGA)   | 4        | 14.29%  |
| 3840x2160 (4K)     | 2        | 7.14%   |
| 1920x1200 (WUXGA)  | 2        | 7.14%   |
| 1680x1050 (WSXGA+) | 2        | 7.14%   |
| 1366x768 (WXGA)    | 2        | 7.14%   |
| 3440x1440          | 1        | 3.57%   |
| 3200x1080          | 1        | 3.57%   |
| 2560x1440 (QHD)    | 1        | 3.57%   |
| 1600x1200          | 1        | 3.57%   |
| Unknown            | 1        | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 18.52%  |
| 24      | 4        | 14.81%  |
| 21      | 3        | 11.11%  |
| 23      | 2        | 7.41%   |
| 22      | 2        | 7.41%   |
| 20      | 2        | 7.41%   |
| 19      | 2        | 7.41%   |
| 17      | 2        | 7.41%   |
| 52      | 1        | 3.7%    |
| 34      | 1        | 3.7%    |
| 18      | 1        | 3.7%    |
| 15      | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 38.46%  |
| 401-500     | 7        | 26.92%  |
| 301-350     | 3        | 11.54%  |
| 351-400     | 2        | 7.69%   |
| 701-800     | 1        | 3.85%   |
| 601-700     | 1        | 3.85%   |
| 1001-1500   | 1        | 3.85%   |
| Unknown     | 1        | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 56%     |
| 5/4     | 4        | 16%     |
| 16/10   | 4        | 16%     |
| 4/3     | 1        | 4%      |
| 21/9    | 1        | 4%      |
| Unknown | 1        | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 30.77%  |
| 301-350        | 5        | 19.23%  |
| 151-200        | 4        | 15.38%  |
| 141-150        | 3        | 11.54%  |
| 251-300        | 2        | 7.69%   |
| More than 1000 | 1        | 3.85%   |
| 351-500        | 1        | 3.85%   |
| 101-110        | 1        | 3.85%   |
| Unknown        | 1        | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 66.67%  |
| 101-120 | 6        | 22.22%  |
| 1-50    | 1        | 3.7%    |
| 121-160 | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 76.92%  |
| 2     | 3        | 11.54%  |
| 0     | 2        | 7.69%   |
| 3     | 1        | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 43.59%  |
| Intel                 | 11       | 28.21%  |
| Qualcomm Atheros      | 3        | 7.69%   |
| Broadcom              | 2        | 5.13%   |
| TP-Link               | 1        | 2.56%   |
| Ralink Technology     | 1        | 2.56%   |
| Ralink                | 1        | 2.56%   |
| Qualcomm              | 1        | 2.56%   |
| Nvidia                | 1        | 2.56%   |
| Broadcom Limited      | 1        | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 22.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 6.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.44%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 4.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 2.22%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 2.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.22%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.22%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 2.22%   |
| Qualcomm MegaFon M150-4                                           | 1        | 2.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 2.22%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 2.22%   |
| Nvidia MCP79 Ethernet                                             | 1        | 2.22%   |
| Intel Wireless-AC 9260                                            | 1        | 2.22%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.22%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.22%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.22%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.22%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.22%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.22%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.22%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1        | 2.22%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 2.22%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 30.77%  |
| Realtek Semiconductor | 3        | 23.08%  |
| Qualcomm Atheros      | 3        | 23.08%  |
| TP-Link               | 1        | 7.69%   |
| Ralink Technology     | 1        | 7.69%   |
| Ralink                | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 7.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 7.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 7.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 7.69%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 7.69%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 7.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 7.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 7.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 7.69%   |
| Intel Wireless-AC 9260                                         | 1        | 7.69%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 7.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 50%     |
| Intel                 | 10       | 31.25%  |
| Broadcom              | 2        | 6.25%   |
| Qualcomm Atheros      | 1        | 3.13%   |
| Qualcomm              | 1        | 3.13%   |
| Nvidia                | 1        | 3.13%   |
| Broadcom Limited      | 1        | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 31.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 9.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 6.25%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 6.25%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 3.13%   |
| Qualcomm MegaFon M150-4                                           | 1        | 3.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.13%   |
| Nvidia MCP79 Ethernet                                             | 1        | 3.13%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.13%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.13%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.13%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.13%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 3.13%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 3.13%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 3.13%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 66.67%  |
| WiFi     | 13       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 76.92%  |
| WiFi     | 6        | 23.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 59.26%  |
| 2     | 8        | 29.63%  |
| 3     | 2        | 7.41%   |
| 4     | 1        | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 92.31%  |
| Yes  | 2        | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 4        | 40%     |
| Intel                    | 3        | 30%     |
| TP-Link                  | 1        | 10%     |
| Realtek Semiconductor    | 1        | 10%     |
| Micro Star International | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 40%     |
| TP-Link UB500 Adapter                               | 1        | 10%     |
| Realtek Bluetooth Radio                             | 1        | 10%     |
| Micro Star International Bluetooth Dongle           | 1        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |
| Intel AX200 Bluetooth                               | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 12       | 30%     |
| Intel             | 11       | 27.5%   |
| Nvidia            | 10       | 25%     |
| Creative Labs     | 4        | 10%     |
| Texas Instruments | 1        | 2.5%    |
| RME               | 1        | 2.5%    |
| ASUSTek Computer  | 1        | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 8.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 6.25%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 4.17%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 4.17%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2        | 4.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 4.17%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 4.17%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 4.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 4.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 4.17%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1        | 2.08%   |
| RME ADI-2 DAC (57750520)                                                                          | 1        | 2.08%   |
| Nvidia MCP79 High Definition Audio                                                                | 1        | 2.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 2.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 2.08%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 2.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 2.08%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 2.08%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 2.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 2.08%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 2.08%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1        | 2.08%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1        | 2.08%   |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1        | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 2.08%   |
| AMD FCH Azalia Controller                                                                         | 1        | 2.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 2.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1        | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 8        | 25.81%  |
| Samsung Electronics | 4        | 12.9%   |
| Corsair             | 3        | 9.68%   |
| Unknown             | 2        | 6.45%   |
| Team                | 2        | 6.45%   |
| SK hynix            | 2        | 6.45%   |
| Unknown             | 2        | 6.45%   |
| Transcend           | 1        | 3.23%   |
| Strontium           | 1        | 3.23%   |
| Silicon Power       | 1        | 3.23%   |
| GLOWAY              | 1        | 3.23%   |
| G.Skill             | 1        | 3.23%   |
| Crucial             | 1        | 3.23%   |
| AMD                 | 1        | 3.23%   |
| A-DATA Technology   | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 6.06%   |
| Unknown                                                     | 2        | 6.06%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1        | 3.03%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s          | 1        | 3.03%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s         | 1        | 3.03%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1        | 3.03%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 3.03%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1        | 3.03%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s   | 1        | 3.03%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 3.03%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s        | 1        | 3.03%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 3.03%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 3.03%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 3.03%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s             | 1        | 3.03%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s        | 1        | 3.03%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 3.03%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s         | 1        | 3.03%   |
| Kingston RAM HP32D4U2S8MR-8 8GB DIMM DDR4 3200MT/s          | 1        | 3.03%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 975MT/s      | 1        | 3.03%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3600MT/s       | 1        | 3.03%   |
| Kingston RAM 9905678-023.A00G 8GB DIMM DDR4 2187MT/s        | 1        | 3.03%   |
| GLOWAY RAM TYA4U2666D19161C 16384MB DIMM DDR4 2667MT/s      | 1        | 3.03%   |
| G.Skill RAM F4-3200C16-16GTZSW 16GB DIMM DDR4 3200MT/s      | 1        | 3.03%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4096MB DIMM DDR4 2400MT/s   | 1        | 3.03%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2472MT/s       | 1        | 3.03%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s        | 1        | 3.03%   |
| Corsair RAM CMK32GX4M4A2800C16 8GB DIMM DDR4 2133MT/s       | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s       | 1        | 3.03%   |
| AMD RAM R534G1601S1SL 4GB DIMM DDR3 1600MT/s                | 1        | 3.03%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 12       | 52.17%  |
| DDR3  | 7        | 30.43%  |
| SDRAM | 2        | 8.7%    |
| DDR2  | 2        | 8.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 21       | 87.5%   |
| SODIMM  | 1        | 4.17%   |
| RIMM    | 1        | 4.17%   |
| FB-DIMM | 1        | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 26.92%  |
| 4096  | 7        | 26.92%  |
| 16384 | 4        | 15.38%  |
| 32768 | 3        | 11.54%  |
| 2048  | 3        | 11.54%  |
| 1024  | 2        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 14.81%  |
| 3800    | 2        | 7.41%   |
| 3600    | 2        | 7.41%   |
| 3200    | 2        | 7.41%   |
| 2667    | 2        | 7.41%   |
| 2400    | 2        | 7.41%   |
| 1333    | 2        | 7.41%   |
| Unknown | 2        | 7.41%   |
| 65535   | 1        | 3.7%    |
| 3733    | 1        | 3.7%    |
| 2933    | 1        | 3.7%    |
| 2472    | 1        | 3.7%    |
| 2187    | 1        | 3.7%    |
| 2133    | 1        | 3.7%    |
| 1866    | 1        | 3.7%    |
| 975     | 1        | 3.7%    |
| 667     | 1        | 3.7%    |

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
| Canon CanoScan LiDE 300      | 1        | 25%     |

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


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Logitech  | 4        | 66.67%  |
| Microsoft | 1        | 16.67%  |
| Microdia  | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 2        | 33.33%  |
| Microsoft LifeCam HD-3000       | 1        | 16.67%  |
| Microdia Camera                 | 1        | 16.67%  |
| Logitech QuickCam Pro 9000      | 1        | 16.67%  |
| Logitech C922 Pro Stream Webcam | 1        | 16.67%  |

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
| 0     | 19       | 73.08%  |
| 1     | 4        | 15.38%  |
| 4     | 1        | 3.85%   |
| 3     | 1        | 3.85%   |
| 2     | 1        | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 4        | 30.77%  |
| Unassigned class         | 2        | 15.38%  |
| Graphics card            | 2        | 15.38%  |
| Communication controller | 2        | 15.38%  |
| Net/wireless             | 1        | 7.69%   |
| Net/ethernet             | 1        | 7.69%   |
| Chipcard                 | 1        | 7.69%   |

