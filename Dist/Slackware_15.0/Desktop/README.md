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

Total: 39

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | TUF Gaming B450-PLUS II | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Dell     | 0MY171 A00              | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| ASUSTek  | PRIME B450M-A           | [053498458e](https://linux-hardware.org/?probe=053498458e) | Mar 03, 2023 |
| Dell     | 0MY171 A00              | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Dell     | 04YP6J A03              | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| ASRock   | 990FX Extreme4          | [7ce91f2b1e](https://linux-hardware.org/?probe=7ce91f2b1e) | Feb 16, 2023 |
| ASRock   | N68-S UCC               | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| ASUSTek  | ROG STRIX B550-I GAMING | [1c9dc6792e](https://linux-hardware.org/?probe=1c9dc6792e) | Jan 13, 2023 |
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
| 5.15.19        | 5        | 13.89%  |
| 5.19.17        | 4        | 11.11%  |
| 5.15.63        | 3        | 8.33%   |
| 5.15.30-Unraid | 2        | 5.56%   |
| 5.15.27        | 2        | 5.56%   |
| 6.1.20         | 1        | 2.78%   |
| 6.1.13         | 1        | 2.78%   |
| 5.19.17-Unraid | 1        | 2.78%   |
| 5.19.16        | 1        | 2.78%   |
| 5.17.2         | 1        | 2.78%   |
| 5.17.0-custom  | 1        | 2.78%   |
| 5.16.18        | 1        | 2.78%   |
| 5.16.13        | 1        | 2.78%   |
| 5.16.11        | 1        | 2.78%   |
| 5.15.94        | 1        | 2.78%   |
| 5.15.6         | 1        | 2.78%   |
| 5.15.38        | 1        | 2.78%   |
| 5.15.14        | 1        | 2.78%   |
| 5.15.13        | 1        | 2.78%   |
| 5.15.103       | 1        | 2.78%   |
| 5.14.15-Unraid | 1        | 2.78%   |
| 5.14.15        | 1        | 2.78%   |
| 5.14.12        | 1        | 2.78%   |
| 5.14.11        | 1        | 2.78%   |
| 5.13.12        | 1        | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.19.17  | 5        | 13.89%  |
| 5.15.19  | 5        | 13.89%  |
| 5.15.63  | 3        | 8.33%   |
| 5.15.30  | 2        | 5.56%   |
| 5.15.27  | 2        | 5.56%   |
| 5.14.15  | 2        | 5.56%   |
| 6.1.20   | 1        | 2.78%   |
| 6.1.13   | 1        | 2.78%   |
| 5.19.16  | 1        | 2.78%   |
| 5.17.2   | 1        | 2.78%   |
| 5.17.0   | 1        | 2.78%   |
| 5.16.18  | 1        | 2.78%   |
| 5.16.13  | 1        | 2.78%   |
| 5.16.11  | 1        | 2.78%   |
| 5.15.94  | 1        | 2.78%   |
| 5.15.6   | 1        | 2.78%   |
| 5.15.38  | 1        | 2.78%   |
| 5.15.14  | 1        | 2.78%   |
| 5.15.13  | 1        | 2.78%   |
| 5.15.103 | 1        | 2.78%   |
| 5.14.12  | 1        | 2.78%   |
| 5.14.11  | 1        | 2.78%   |
| 5.13.12  | 1        | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 18       | 51.43%  |
| 5.19    | 6        | 17.14%  |
| 5.14    | 4        | 11.43%  |
| 5.16    | 3        | 8.57%   |
| 5.17    | 2        | 5.71%   |
| 6.1     | 1        | 2.86%   |
| 5.13    | 1        | 2.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 32       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 13       | 39.39%  |
| XFCE       | 9        | 27.27%  |
| Unknown    | 8        | 24.24%  |
| X-Generic  | 1        | 3.03%   |
| X-Cinnamon | 1        | 3.03%   |
| FVWM       | 1        | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 19       | 55.88%  |
| Tty     | 9        | 26.47%  |
| Unknown | 4        | 11.76%  |
| Wayland | 2        | 5.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 15       | 45.45%  |
| Unknown | 11       | 33.33%  |
| XDM     | 4        | 12.12%  |
| LightDM | 3        | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 16       | 50%     |
| Unknown     | 8        | 25%     |
| en_GB       | 2        | 6.25%   |
| ru_RU       | 1        | 3.13%   |
| pt_PT       | 1        | 3.13%   |
| it_IT       | 1        | 3.13%   |
| es_ES.UTF8  | 1        | 3.13%   |
| es_ES       | 1        | 3.13%   |
| en_US.ASCII | 1        | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 56.25%  |
| EFI  | 14       | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 19       | 59.38%  |
| Btrfs   | 5        | 15.63%  |
| Xfs     | 3        | 9.38%   |
| Overlay | 2        | 6.25%   |
| Tmpfs   | 1        | 3.13%   |
| F2fs    | 1        | 3.13%   |
| Ext2    | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 25       | 75.76%  |
| MBR     | 5        | 15.15%  |
| Unknown | 3        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 60.61%  |
| Yes       | 13       | 39.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 68.75%  |
| Yes       | 10       | 31.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 7        | 21.88%  |
| ASUSTek Computer    | 7        | 21.88%  |
| ASRock              | 6        | 18.75%  |
| Hewlett-Packard     | 4        | 12.5%   |
| Dell                | 3        | 9.38%   |
| Lenovo              | 1        | 3.13%   |
| Gigabyte Technology | 1        | 3.13%   |
| Biostar             | 1        | 3.13%   |
| Acer                | 1        | 3.13%   |
| Unknown             | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7C52                          | 1        | 3.13%   |
| MSI MS-7C02                          | 1        | 3.13%   |
| MSI MS-7996                          | 1        | 3.13%   |
| MSI MS-7788                          | 1        | 3.13%   |
| MSI MS-7693                          | 1        | 3.13%   |
| MSI MS-7529                          | 1        | 3.13%   |
| MSI MS-7365                          | 1        | 3.13%   |
| Lenovo H50-05 90BH001WIX             | 1        | 3.13%   |
| HP Z440 Workstation                  | 1        | 3.13%   |
| HP xw8400 Workstation                | 1        | 3.13%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 3.13%   |
| HP Compaq dc7900 Small Form Factor   | 1        | 3.13%   |
| Gigabyte N3160TN                     | 1        | 3.13%   |
| Dell Precision WorkStation 690       | 1        | 3.13%   |
| Dell OptiPlex 780                    | 1        | 3.13%   |
| Dell OptiPlex 3020                   | 1        | 3.13%   |
| Biostar X470GTA                      | 1        | 3.13%   |
| ASUS TUF Gaming B450-PLUS II         | 1        | 3.13%   |
| ASUS TUF B450-PLUS GAMING            | 1        | 3.13%   |
| ASUS ROG STRIX B550-I GAMING         | 1        | 3.13%   |
| ASUS ROG CROSSHAIR VIII HERO         | 1        | 3.13%   |
| ASUS PRIME Z390-A                    | 1        | 3.13%   |
| ASUS PRIME B450M-A                   | 1        | 3.13%   |
| ASUS All Series                      | 1        | 3.13%   |
| ASRock N68-S3 FX                     | 1        | 3.13%   |
| ASRock N68-S UCC                     | 1        | 3.13%   |
| ASRock H410M-ITX/ac                  | 1        | 3.13%   |
| ASRock H270 Pro4                     | 1        | 3.13%   |
| ASRock B550 Taichi                   | 1        | 3.13%   |
| ASRock 990FX Extreme4                | 1        | 3.13%   |
| Acer Aspire R3610                    | 1        | 3.13%   |
| Unknown                              | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Dell OptiPlex    | 2        | 6.25%   |
| ASUS TUF         | 2        | 6.25%   |
| ASUS ROG         | 2        | 6.25%   |
| ASUS PRIME       | 2        | 6.25%   |
| MSI MS-7C52      | 1        | 3.13%   |
| MSI MS-7C02      | 1        | 3.13%   |
| MSI MS-7996      | 1        | 3.13%   |
| MSI MS-7788      | 1        | 3.13%   |
| MSI MS-7693      | 1        | 3.13%   |
| MSI MS-7529      | 1        | 3.13%   |
| MSI MS-7365      | 1        | 3.13%   |
| Lenovo H50-05    | 1        | 3.13%   |
| HP Z440          | 1        | 3.13%   |
| HP xw8400        | 1        | 3.13%   |
| HP Pavilion      | 1        | 3.13%   |
| HP Compaq        | 1        | 3.13%   |
| Gigabyte N3160TN | 1        | 3.13%   |
| Dell Precision   | 1        | 3.13%   |
| Biostar X470GTA  | 1        | 3.13%   |
| ASUS All         | 1        | 3.13%   |
| ASRock N68-S3    | 1        | 3.13%   |
| ASRock N68-S     | 1        | 3.13%   |
| ASRock H410M-ITX | 1        | 3.13%   |
| ASRock H270      | 1        | 3.13%   |
| ASRock B550      | 1        | 3.13%   |
| ASRock 990FX     | 1        | 3.13%   |
| Acer Aspire      | 1        | 3.13%   |
| Unknown          | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 12.5%   |
| 2019 | 4        | 12.5%   |
| 2011 | 4        | 12.5%   |
| 2018 | 3        | 9.38%   |
| 2008 | 3        | 9.38%   |
| 2022 | 2        | 6.25%   |
| 2017 | 2        | 6.25%   |
| 2015 | 2        | 6.25%   |
| 2014 | 2        | 6.25%   |
| 2009 | 2        | 6.25%   |
| 2021 | 1        | 3.13%   |
| 2016 | 1        | 3.13%   |
| 2010 | 1        | 3.13%   |
| 2007 | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 32       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 9        | 27.27%  |
| 32.01-64.0  | 6        | 18.18%  |
| 3.01-4.0    | 4        | 12.12%  |
| 64.01-256.0 | 4        | 12.12%  |
| 1.01-2.0    | 3        | 9.09%   |
| 8.01-16.0   | 3        | 9.09%   |
| 4.01-8.0    | 2        | 6.06%   |
| 24.01-32.0  | 2        | 6.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 10       | 30.3%   |
| 1.01-2.0   | 7        | 21.21%  |
| 2.01-3.0   | 6        | 18.18%  |
| 0.51-1.0   | 4        | 12.12%  |
| 8.01-16.0  | 2        | 6.06%   |
| 32.01-64.0 | 1        | 3.03%   |
| 3.01-4.0   | 1        | 3.03%   |
| 16.01-24.0 | 1        | 3.03%   |
| 0.01-0.5   | 1        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 9        | 26.47%  |
| 2      | 9        | 26.47%  |
| 1      | 7        | 20.59%  |
| 6      | 4        | 11.76%  |
| 4      | 2        | 5.88%   |
| 11     | 1        | 2.94%   |
| 9      | 1        | 2.94%   |
| 0      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 51.52%  |
| No        | 16       | 48.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 57.58%  |
| Yes       | 14       | 42.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 62.5%   |
| Yes       | 12       | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 7        | 21.88%  |
| UK           | 4        | 12.5%   |
| Kazakhstan   | 3        | 9.38%   |
| Italy        | 3        | 9.38%   |
| Brazil       | 3        | 9.38%   |
| Russia       | 2        | 6.25%   |
| Hong Kong    | 2        | 6.25%   |
| Germany      | 2        | 6.25%   |
| Spain        | 1        | 3.13%   |
| South Africa | 1        | 3.13%   |
| Portugal     | 1        | 3.13%   |
| Japan        | 1        | 3.13%   |
| Canada       | 1        | 3.13%   |
| Argentina    | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Ust-Kamenogorsk   | 2        | 6.06%   |
| Winter Springs    | 1        | 3.03%   |
| Warwick           | 1        | 3.03%   |
| Tsukuba           | 1        | 3.03%   |
| Toronto           | 1        | 3.03%   |
| Tatuí            | 1        | 3.03%   |
| St Petersburg     | 1        | 3.03%   |
| Sham Shui Po      | 1        | 3.03%   |
| Senhora da Hora   | 1        | 3.03%   |
| Santa Cruz do Sul | 1        | 3.03%   |
| Saint Paul        | 1        | 3.03%   |
| Rome              | 1        | 3.03%   |
| Rock              | 1        | 3.03%   |
| Porto Alegre      | 1        | 3.03%   |
| Moscow            | 1        | 3.03%   |
| Milwaukee         | 1        | 3.03%   |
| Milan             | 1        | 3.03%   |
| Mead              | 1        | 3.03%   |
| McKinney          | 1        | 3.03%   |
| London            | 1        | 3.03%   |
| Lisbon            | 1        | 3.03%   |
| Karaganda         | 1        | 3.03%   |
| Hamburg           | 1        | 3.03%   |
| Granada           | 1        | 3.03%   |
| Frosinone         | 1        | 3.03%   |
| Fayetteville      | 1        | 3.03%   |
| Erfurt            | 1        | 3.03%   |
| Colorado Springs  | 1        | 3.03%   |
| Central           | 1        | 3.03%   |
| Cape Town         | 1        | 3.03%   |
| Buenos Aires      | 1        | 3.03%   |
| Belfast           | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 21     | 21.92%  |
| WDC                 | 13       | 30     | 17.81%  |
| Samsung Electronics | 9        | 12     | 12.33%  |
| Toshiba             | 7        | 18     | 9.59%   |
| Hitachi             | 5        | 8      | 6.85%   |
| Crucial             | 4        | 5      | 5.48%   |
| Kingston            | 3        | 5      | 4.11%   |
| Transcend           | 2        | 2      | 2.74%   |
| ZHITAI              | 1        | 2      | 1.37%   |
| SK hynix            | 1        | 1      | 1.37%   |
| PNY                 | 1        | 1      | 1.37%   |
| Phison Electronics  | 1        | 1      | 1.37%   |
| Patriot             | 1        | 1      | 1.37%   |
| KIOXIA              | 1        | 1      | 1.37%   |
| Intenso             | 1        | 1      | 1.37%   |
| Intel               | 1        | 2      | 1.37%   |
| HGST                | 1        | 1      | 1.37%   |
| Hewlett-Packard     | 1        | 1      | 1.37%   |
| Gigabyte Technology | 1        | 1      | 1.37%   |
| DUEX                | 1        | 1      | 1.37%   |
| China               | 1        | 1      | 1.37%   |
| A-DATA Technology   | 1        | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 2.25%   |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 2.25%   |
| Seagate ST2000DL003-9VT166 2TB    | 2        | 2.25%   |
| Seagate ST1000DM003-1SB102 1TB    | 2        | 2.25%   |
| Seagate Expansion Desk 8TB        | 2        | 2.25%   |
| Samsung SSD 970 EVO 250GB         | 2        | 2.25%   |
| Crucial CT500MX500SSD1 500GB      | 2        | 2.25%   |
| ZHITAI SC001 Active 1TB SSD       | 1        | 1.12%   |
| ZHITAI PC005 Active 512GB         | 1        | 1.12%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1        | 1.12%   |
| WDC WDS480G2G0A-00JH30 480GB SSD  | 1        | 1.12%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 1.12%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 1.12%   |
| WDC WD5000AAKS-007AA0 500GB       | 1        | 1.12%   |
| WDC WD40EZRX-00SPEB0 4TB          | 1        | 1.12%   |
| WDC WD40EJRX-89T1XY0 4TB          | 1        | 1.12%   |
| WDC WD400BD-60LTA0 40GB           | 1        | 1.12%   |
| WDC WD3200AAJS-65B4A0 320GB       | 1        | 1.12%   |
| WDC WD30EZRX-00SPEB0 3TB          | 1        | 1.12%   |
| WDC WD30EZRX-00MMMB0 3TB          | 1        | 1.12%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1        | 1.12%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 1.12%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 1.12%   |
| WDC WD10EZEX-00RKKA0 1TB          | 1        | 1.12%   |
| WDC WD10EZEX-00MFCA0 1TB          | 1        | 1.12%   |
| Transcend TS480GSSD220S 480GB     | 1        | 1.12%   |
| Transcend TS32GSSD370S 32GB       | 1        | 1.12%   |
| Toshiba THNSNH128GBST SSD         | 1        | 1.12%   |
| Toshiba THNSF5512GPUK 512GB       | 1        | 1.12%   |
| Toshiba MK5055GSX 500GB           | 1        | 1.12%   |
| Toshiba MG08ADA800E 8TB           | 1        | 1.12%   |
| Toshiba MG05ACA800E 8TB           | 1        | 1.12%   |
| Toshiba MD04ABA400V 4TB           | 1        | 1.12%   |
| Toshiba HDWD240 4TB               | 1        | 1.12%   |
| Toshiba HDWD130 3TB               | 1        | 1.12%   |
| Toshiba DT01ACA300 3TB            | 1        | 1.12%   |
| SK hynix SHGS31-500GS-2 500GB SSD | 1        | 1.12%   |
| Seagate ST4000VX000-2AG166 4TB    | 1        | 1.12%   |
| Seagate ST4000VN006-3CW104 4TB    | 1        | 1.12%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1.12%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 21     | 39.02%  |
| WDC                 | 12       | 27     | 29.27%  |
| Toshiba             | 6        | 13     | 14.63%  |
| Hitachi             | 5        | 8      | 12.2%   |
| Samsung Electronics | 1        | 1      | 2.44%   |
| HGST                | 1        | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 6      | 16.67%  |
| Kingston            | 3        | 5      | 12.5%   |
| Crucial             | 3        | 4      | 12.5%   |
| WDC                 | 2        | 3      | 8.33%   |
| Transcend           | 2        | 2      | 8.33%   |
| ZHITAI              | 1        | 1      | 4.17%   |
| Toshiba             | 1        | 3      | 4.17%   |
| SK hynix            | 1        | 1      | 4.17%   |
| PNY                 | 1        | 1      | 4.17%   |
| Patriot             | 1        | 1      | 4.17%   |
| Intenso             | 1        | 1      | 4.17%   |
| Intel               | 1        | 2      | 4.17%   |
| Hewlett-Packard     | 1        | 1      | 4.17%   |
| DUEX                | 1        | 1      | 4.17%   |
| China               | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 71     | 44.44%  |
| SSD  | 20       | 33     | 37.04%  |
| NVMe | 10       | 13     | 18.52%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 102    | 70.73%  |
| NVMe | 10       | 13     | 24.39%  |
| SAS  | 2        | 2      | 4.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 34     | 37.93%  |
| 0.51-1.0   | 12       | 27     | 20.69%  |
| 1.01-2.0   | 8        | 11     | 13.79%  |
| 3.01-4.0   | 7        | 14     | 12.07%  |
| 4.01-10.0  | 5        | 7      | 8.62%   |
| 2.01-3.0   | 4        | 11     | 6.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 6        | 17.14%  |
| 501-1000       | 6        | 17.14%  |
| Unknown        | 6        | 17.14%  |
| 251-500        | 4        | 11.43%  |
| 2001-3000      | 4        | 11.43%  |
| 1001-2000      | 3        | 8.57%   |
| 1-20           | 3        | 8.57%   |
| More than 3000 | 2        | 5.71%   |
| 51-100         | 1        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 23.53%  |
| Unknown        | 6        | 17.65%  |
| 501-1000       | 5        | 14.71%  |
| 1-20           | 4        | 11.76%  |
| 251-500        | 3        | 8.82%   |
| 21-50          | 3        | 8.82%   |
| 1001-2000      | 3        | 8.82%   |
| More than 3000 | 1        | 2.94%   |
| 51-100         | 1        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 7.14%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1        | 1      | 7.14%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1        | 1      | 7.14%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1        | 1      | 7.14%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 7.14%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 7.14%   |
| Seagate ST380011A 80GB                | 1        | 1      | 7.14%   |
| Seagate ST3000VX006-1HH166 3TB        | 1        | 1      | 7.14%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 1      | 7.14%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 2      | 7.14%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 7.14%   |
| Hitachi HUA723030ALA640 3TB           | 1        | 1      | 7.14%   |
| Hitachi HDS721016CLA382 160GB         | 1        | 1      | 7.14%   |
| DUEX DX300256A5xnEMLC 256GB SSD       | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 7      | 41.67%  |
| Seagate             | 3        | 5      | 25%     |
| Hitachi             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| DUEX                | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 6      | 44.44%  |
| Seagate | 3        | 5      | 33.33%  |
| Hitachi | 2        | 2      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 13     | 70%     |
| SSD  | 2        | 2      | 20%     |
| NVMe | 1        | 1      | 10%     |

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
| Works    | 25       | 73     | 59.52%  |
| Malfunc  | 10       | 16     | 23.81%  |
| Detected | 7        | 28     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 15       | 30%     |
| AMD                          | 13       | 26%     |
| Samsung Electronics          | 5        | 10%     |
| Nvidia                       | 3        | 6%      |
| Marvell Technology Group     | 3        | 6%      |
| JMicron Technology           | 2        | 4%      |
| Yangtze Memory Technologies  | 1        | 2%      |
| Toshiba America Info Systems | 1        | 2%      |
| Realtek Semiconductor        | 1        | 2%      |
| Phison Electronics           | 1        | 2%      |
| Micron/Crucial Technology    | 1        | 2%      |
| LSI Logic / Symbios Logic    | 1        | 2%      |
| KIOXIA                       | 1        | 2%      |
| ASMedia Technology           | 1        | 2%      |
| Adaptec                      | 1        | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 10.61%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 6.06%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 3.03%   |
| Nvidia MCP61 IDE                                                                        | 2        | 3.03%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 3.03%   |
| JMicron JMB58x AHCI SATA controller                                                     | 2        | 3.03%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 3.03%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 3.03%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 3.03%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 3.03%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 3.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 3.03%   |
| Yangtze Memory Non-Volatile memory controller                                           | 1        | 1.52%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.52%   |
| Samsung Electronics SATA controller                                                     | 1        | 1.52%   |
| Realtek NVMe Controller                                                                 | 1        | 1.52%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.52%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 1.52%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.52%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.52%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 1.52%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 1        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.52%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 1.52%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 1.52%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 1        | 1.52%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.52%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 25       | 52.08%  |
| NVMe | 10       | 20.83%  |
| IDE  | 10       | 20.83%  |
| SCSI | 2        | 4.17%   |
| RAID | 1        | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 53.13%  |
| AMD    | 15       | 46.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 6.06%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 6.06%   |
| Intel Xeon CPU X5355 @ 2.66GHz              | 1        | 3.03%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz         | 1        | 3.03%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 3.03%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 3.03%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 3.03%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 3.03%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 3.03%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 3.03%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 3.03%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 3.03%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 3.03%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 3.03%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 3.03%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 3.03%   |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1        | 3.03%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 3.03%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 1        | 3.03%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 3.03%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics  | 1        | 3.03%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 3.03%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 3.03%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 3.03%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1        | 3.03%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 3.03%   |
| AMD FX-8320 Eight-Core Processor            | 1        | 3.03%   |
| AMD FX-8150 Eight-Core Processor            | 1        | 3.03%   |
| AMD FX-6300 Six-Core Processor              | 1        | 3.03%   |
| AMD Athlon II X2 250 Processor              | 1        | 3.03%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 1        | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 5        | 15.15%  |
| AMD Ryzen 5        | 4        | 12.12%  |
| Intel Core i7      | 3        | 9.09%   |
| Intel Core i5      | 3        | 9.09%   |
| Intel Core 2 Duo   | 3        | 9.09%   |
| AMD FX             | 3        | 9.09%   |
| AMD Ryzen 9        | 2        | 6.06%   |
| AMD Ryzen 7        | 2        | 6.06%   |
| Intel Pentium Dual | 1        | 3.03%   |
| Intel Core i3      | 1        | 3.03%   |
| Intel Celeron      | 1        | 3.03%   |
| Intel Atom         | 1        | 3.03%   |
| AMD Ryzen 7 PRO    | 1        | 3.03%   |
| AMD Ryzen 3        | 1        | 3.03%   |
| AMD Athlon II X2   | 1        | 3.03%   |
| AMD A8             | 1        | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 12       | 36.36%  |
| 2      | 6        | 18.18%  |
| 8      | 5        | 15.15%  |
| 6      | 5        | 15.15%  |
| 16     | 1        | 3.03%   |
| 14     | 1        | 3.03%   |
| 12     | 1        | 3.03%   |
| 10     | 1        | 3.03%   |
| 3      | 1        | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 93.75%  |
| 2      | 2        | 6.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 59.38%  |
| 1      | 13       | 40.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 32       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 15.63%  |
| 0x08701021 | 3        | 9.38%   |
| 0x306f2    | 2        | 6.25%   |
| 0x1067a    | 2        | 6.25%   |
| 0x0a50000c | 2        | 6.25%   |
| 0x0a201016 | 2        | 6.25%   |
| 0xa0653    | 1        | 3.13%   |
| 0x906ea    | 1        | 3.13%   |
| 0x906e9    | 1        | 3.13%   |
| 0x6fd      | 1        | 3.13%   |
| 0x6fb      | 1        | 3.13%   |
| 0x506e3    | 1        | 3.13%   |
| 0x406c4    | 1        | 3.13%   |
| 0x306e4    | 1        | 3.13%   |
| 0x306c3    | 1        | 3.13%   |
| 0x306a9    | 1        | 3.13%   |
| 0x106c2    | 1        | 3.13%   |
| 0x0810100b | 1        | 3.13%   |
| 0x07030105 | 1        | 3.13%   |
| 0x06000822 | 1        | 3.13%   |
| 0x010000b6 | 1        | 3.13%   |
| 0x00000000 | 1        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Zen 3      | 4        | 12.5%   |
| Zen 2      | 4        | 12.5%   |
| Penryn     | 3        | 9.38%   |
| Haswell    | 3        | 9.38%   |
| Core       | 3        | 9.38%   |
| Piledriver | 2        | 6.25%   |
| KabyLake   | 2        | 6.25%   |
| IvyBridge  | 2        | 6.25%   |
| Zen+       | 1        | 3.13%   |
| Zen        | 1        | 3.13%   |
| Skylake    | 1        | 3.13%   |
| Silvermont | 1        | 3.13%   |
| Puma       | 1        | 3.13%   |
| K10        | 1        | 3.13%   |
| CometLake  | 1        | 3.13%   |
| Bulldozer  | 1        | 3.13%   |
| Bonnell    | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 15       | 45.45%  |
| AMD    | 12       | 36.36%  |
| Intel  | 6        | 18.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 8.82%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 5.88%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 5.88%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 5.88%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 5.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 5.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 2.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 2.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 2.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 2.94%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 2.94%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 2.94%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 2.94%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 2.94%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1        | 2.94%   |
| Nvidia C79 [ION]                                                                         | 1        | 2.94%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 2.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 2.94%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 14       | 43.75%  |
| 1 x AMD        | 11       | 34.38%  |
| 1 x Intel      | 5        | 15.63%  |
| 2 x AMD        | 1        | 3.13%   |
| Intel + Nvidia | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 68.75%  |
| Proprietary | 7        | 21.88%  |
| Unknown     | 3        | 9.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 31.25%  |
| 0.51-1.0   | 5        | 15.63%  |
| 7.01-8.0   | 4        | 12.5%   |
| 0.01-0.5   | 4        | 12.5%   |
| 8.01-16.0  | 3        | 9.38%   |
| 3.01-4.0   | 2        | 6.25%   |
| 1.01-2.0   | 2        | 6.25%   |
| 5.01-6.0   | 1        | 3.13%   |
| 2.01-3.0   | 1        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 7        | 21.21%  |
| Dell                    | 6        | 18.18%  |
| Hewlett-Packard         | 3        | 9.09%   |
| BenQ                    | 3        | 9.09%   |
| Ancor Communications    | 3        | 9.09%   |
| Acer                    | 2        | 6.06%   |
| Wacom                   | 1        | 3.03%   |
| Lenovo                  | 1        | 3.03%   |
| IOD                     | 1        | 3.03%   |
| Goldstar                | 1        | 3.03%   |
| GDH                     | 1        | 3.03%   |
| Chi Mei Optoelectronics | 1        | 3.03%   |
| ASUSTek Computer        | 1        | 3.03%   |
| AOC                     | 1        | 3.03%   |
| Unknown                 | 1        | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch               | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                       | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch   | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch   | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch   | 1        | 2.94%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch     | 1        | 2.94%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch      | 1        | 2.94%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch      | 1        | 2.94%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                      | 1        | 2.94%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                  | 1        | 2.94%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                   | 1        | 2.94%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch             | 1        | 2.94%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch           | 1        | 2.94%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch              | 1        | 2.94%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                    | 1        | 2.94%   |
| GDH CHHWJT GDH0030 1440x900 1150x650mm 52.0-inch                       | 1        | 2.94%   |
| Dell U2722D DEL422D 2560x1440 597x336mm 27.0-inch                      | 1        | 2.94%   |
| Dell SP2208WFP DEL4038 1680x1050 473x296mm 22.0-inch                   | 1        | 2.94%   |
| Dell LCD Monitor P190S 3200x1080                                       | 1        | 2.94%   |
| Dell E1913 DELD051 1440x900 408x255mm 18.9-inch                        | 1        | 2.94%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch               | 1        | 2.94%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                      | 1        | 2.94%   |
| Chi Mei Optoelectronics CMC 22 W CMO2228 1680x1050 473x296mm 22.0-inch | 1        | 2.94%   |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                     | 1        | 2.94%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 1        | 2.94%   |
| BenQ G610HDAL BNQ785B 1366x768 344x194mm 15.5-inch                     | 1        | 2.94%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch           | 1        | 2.94%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 1        | 2.94%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch  | 1        | 2.94%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 1        | 2.94%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch  | 1        | 2.94%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                     | 1        | 2.94%   |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                      | 1        | 2.94%   |
| Unknown                                                                | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 36.36%  |
| 1280x1024 (SXGA)   | 4        | 12.12%  |
| 3840x2160 (4K)     | 3        | 9.09%   |
| 1680x1050 (WSXGA+) | 3        | 9.09%   |
| 1366x768 (WXGA)    | 3        | 9.09%   |
| 1920x1200 (WUXGA)  | 2        | 6.06%   |
| 3440x1440          | 1        | 3.03%   |
| 3200x1080          | 1        | 3.03%   |
| 2560x1440 (QHD)    | 1        | 3.03%   |
| 1600x1200          | 1        | 3.03%   |
| 1440x900 (WXGA+)   | 1        | 3.03%   |
| Unknown            | 1        | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 15.15%  |
| 24      | 5        | 15.15%  |
| 22      | 3        | 9.09%   |
| 21      | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |
| 23      | 2        | 6.06%   |
| 20      | 2        | 6.06%   |
| 19      | 2        | 6.06%   |
| 18      | 2        | 6.06%   |
| 17      | 2        | 6.06%   |
| 15      | 2        | 6.06%   |
| 52      | 1        | 3.03%   |
| 34      | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 34.38%  |
| 401-500     | 9        | 28.13%  |
| 301-350     | 4        | 12.5%   |
| Unknown     | 3        | 9.38%   |
| 351-400     | 2        | 6.25%   |
| 701-800     | 1        | 3.13%   |
| 601-700     | 1        | 3.13%   |
| 1001-1500   | 1        | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 53.33%  |
| 16/10   | 6        | 20%     |
| 5/4     | 4        | 13.33%  |
| Unknown | 2        | 6.67%   |
| 4/3     | 1        | 3.33%   |
| 21/9    | 1        | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 31.25%  |
| 301-350        | 5        | 15.63%  |
| 151-200        | 5        | 15.63%  |
| 141-150        | 3        | 9.38%   |
| Unknown        | 3        | 9.38%   |
| 251-300        | 2        | 6.25%   |
| 101-110        | 2        | 6.25%   |
| More than 1000 | 1        | 3.13%   |
| 351-500        | 1        | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 63.64%  |
| 101-120 | 7        | 21.21%  |
| Unknown | 3        | 9.09%   |
| 1-50    | 1        | 3.03%   |
| 121-160 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 78.13%  |
| 2     | 3        | 9.38%   |
| 0     | 3        | 9.38%   |
| 3     | 1        | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 43.48%  |
| Intel                 | 13       | 28.26%  |
| Qualcomm Atheros      | 3        | 6.52%   |
| Broadcom              | 3        | 6.52%   |
| Nvidia                | 2        | 4.35%   |
| TP-Link               | 1        | 2.17%   |
| Ralink Technology     | 1        | 2.17%   |
| Ralink                | 1        | 2.17%   |
| Qualcomm              | 1        | 2.17%   |
| Broadcom Limited      | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 24.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 5.66%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 3.77%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.77%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 3.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 1.89%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 1.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.89%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.89%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.89%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 1.89%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 1.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 1.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.89%   |
| Nvidia MCP79 Ethernet                                             | 1        | 1.89%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.89%   |
| Intel Wireless-AC 9260                                            | 1        | 1.89%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.89%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.89%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.89%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1        | 1.89%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 1.89%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.89%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 35.71%  |
| Realtek Semiconductor | 3        | 21.43%  |
| Qualcomm Atheros      | 3        | 21.43%  |
| TP-Link               | 1        | 7.14%   |
| Ralink Technology     | 1        | 7.14%   |
| Ralink                | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 2        | 14.29%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 7.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 7.14%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 7.14%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 7.14%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 7.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 7.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 7.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 7.14%   |
| Intel Wireless-AC 9260                                         | 1        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 7.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 48.72%  |
| Intel                 | 12       | 30.77%  |
| Broadcom              | 3        | 7.69%   |
| Nvidia                | 2        | 5.13%   |
| Qualcomm Atheros      | 1        | 2.56%   |
| Qualcomm              | 1        | 2.56%   |
| Broadcom Limited      | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 7.69%   |
| Intel Ethernet Controller I225-V                                  | 2        | 5.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 5.13%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 5.13%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.56%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 2.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.56%   |
| Nvidia MCP79 Ethernet                                             | 1        | 2.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.56%   |
| Intel I350 Gigabit Network Connection                             | 1        | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.56%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 2.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 2.56%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 2.56%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 69.57%  |
| WiFi     | 14       | 30.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 78.79%  |
| WiFi     | 7        | 21.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 60.61%  |
| 2     | 9        | 27.27%  |
| 3     | 2        | 6.06%   |
| 5     | 1        | 3.03%   |
| 4     | 1        | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 87.88%  |
| Yes  | 4        | 12.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 5        | 38.46%  |
| Intel                    | 4        | 30.77%  |
| TP-Link                  | 1        | 7.69%   |
| Realtek Semiconductor    | 1        | 7.69%   |
| Micro Star International | 1        | 7.69%   |
| MediaTek                 | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 38.46%  |
| Intel AX200 Bluetooth                               | 2        | 15.38%  |
| TP-Link UB500 Adapter                               | 1        | 7.69%   |
| Realtek Bluetooth Radio                             | 1        | 7.69%   |
| Micro Star International Bluetooth Dongle           | 1        | 7.69%   |
| MediaTek Wireless_Device                            | 1        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 16       | 33.33%  |
| Nvidia              | 12       | 25%     |
| Intel               | 12       | 25%     |
| Creative Labs       | 4        | 8.33%   |
| Texas Instruments   | 1        | 2.08%   |
| RME                 | 1        | 2.08%   |
| Kingston Technology | 1        | 2.08%   |
| ASUSTek Computer    | 1        | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 6        | 10.17%  |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 5.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 5.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 5.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 3.39%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 3.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 3.39%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 3.39%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2        | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2        | 3.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 3.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 3.39%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 3.39%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 3.39%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1        | 1.69%   |
| RME ADI-2 DAC (57750512)                                                                          | 1        | 1.69%   |
| Nvidia MCP79 High Definition Audio                                                                | 1        | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.69%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 1.69%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 1.69%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1        | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 1.69%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1        | 1.69%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 1.69%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1        | 1.69%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1        | 1.69%   |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1        | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 1        | 1.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 1.69%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1        | 1.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 8        | 21.05%  |
| Corsair             | 5        | 13.16%  |
| Samsung Electronics | 4        | 10.53%  |
| Unknown             | 3        | 7.89%   |
| Team                | 2        | 5.26%   |
| SK hynix            | 2        | 5.26%   |
| G.Skill             | 2        | 5.26%   |
| Crucial             | 2        | 5.26%   |
| Unknown             | 2        | 5.26%   |
| Transcend           | 1        | 2.63%   |
| Strontium           | 1        | 2.63%   |
| Smart               | 1        | 2.63%   |
| Silicon Power       | 1        | 2.63%   |
| Patriot             | 1        | 2.63%   |
| GLOWAY              | 1        | 2.63%   |
| AMD                 | 1        | 2.63%   |
| A-DATA Technology   | 1        | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 5%      |
| Unknown                                                     | 2        | 5%      |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                    | 1        | 2.5%    |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1        | 2.5%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s         | 1        | 2.5%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s          | 1        | 2.5%    |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1        | 2.5%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s         | 1        | 2.5%    |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 2.5%    |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s        | 1        | 2.5%    |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s   | 1        | 2.5%    |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 2.5%    |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s        | 1        | 2.5%    |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 2.5%    |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 2.5%    |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 2.5%    |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s             | 1        | 2.5%    |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s             | 1        | 2.5%    |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s        | 1        | 2.5%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 2.5%    |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s         | 1        | 2.5%    |
| Kingston RAM HP32D4U2S8MR-8 8GB DIMM DDR4 3200MT/s          | 1        | 2.5%    |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 975MT/s      | 1        | 2.5%    |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3600MT/s       | 1        | 2.5%    |
| Kingston RAM 9905678-023.A00G 8GB DIMM DDR4 2187MT/s        | 1        | 2.5%    |
| GLOWAY RAM TYA4U2666D19161C 16384MB DIMM DDR4 2667MT/s      | 1        | 2.5%    |
| G.Skill RAM F4-3200C16-16GTZSW 16GB DIMM DDR4 3200MT/s      | 1        | 2.5%    |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s        | 1        | 2.5%    |
| Crucial RAM CT8G4DFRA32A.C8FJ 8GB DIMM DDR4 2400MT/s        | 1        | 2.5%    |
| Crucial RAM BLS4G4D240FSB.8FBD2 4096MB DIMM DDR4 2400MT/s   | 1        | 2.5%    |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2472MT/s       | 1        | 2.5%    |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s        | 1        | 2.5%    |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s       | 1        | 2.5%    |
| Corsair RAM CMK32GX4M4A2800C16 8GB DIMM DDR4 2133MT/s       | 1        | 2.5%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 1        | 2.5%    |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s       | 1        | 2.5%    |
| AMD RAM R534G1601S1SL 4GB DIMM DDR3 1600MT/s                | 1        | 2.5%    |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 15       | 51.72%  |
| DDR3  | 9        | 31.03%  |
| DDR2  | 3        | 10.34%  |
| SDRAM | 2        | 6.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 27       | 90%     |
| SODIMM  | 1        | 3.33%   |
| RIMM    | 1        | 3.33%   |
| FB-DIMM | 1        | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 31.25%  |
| 4096  | 8        | 25%     |
| 16384 | 5        | 15.63%  |
| 2048  | 4        | 12.5%   |
| 32768 | 3        | 9.38%   |
| 1024  | 2        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 17.65%  |
| 3600    | 4        | 11.76%  |
| 2400    | 3        | 8.82%   |
| 3800    | 2        | 5.88%   |
| 3200    | 2        | 5.88%   |
| 2667    | 2        | 5.88%   |
| 1333    | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 65535   | 1        | 2.94%   |
| 3733    | 1        | 2.94%   |
| 2933    | 1        | 2.94%   |
| 2800    | 1        | 2.94%   |
| 2472    | 1        | 2.94%   |
| 2187    | 1        | 2.94%   |
| 2133    | 1        | 2.94%   |
| 1866    | 1        | 2.94%   |
| 975     | 1        | 2.94%   |
| 667     | 1        | 2.94%   |
| 533     | 1        | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| QinHeng Electronics | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |
| Dell                | 1        | 20%     |
| Canon               | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| QinHeng CH340S               | 1        | 20%     |
| HP OfficeJet Pro 9010 series | 1        | 20%     |
| Dell 2330d Laser Printer     | 1        | 20%     |
| Canon CanoScan LiDE 300      | 1        | 20%     |
| Brother HL-L5102DW           | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 50%     |
| Canon CanoScan LIDE 25                        | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Logitech  | 6        | 75%     |
| Microsoft | 1        | 12.5%   |
| Microdia  | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 3        | 37.5%   |
| Microsoft LifeCam HD-3000       | 1        | 12.5%   |
| Microdia Camera                 | 1        | 12.5%   |
| Logitech QuickCam Pro 9000      | 1        | 12.5%   |
| Logitech Logitech Webcam C160   | 1        | 12.5%   |
| Logitech C922 Pro Stream Webcam | 1        | 12.5%   |

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
| 0     | 23       | 71.88%  |
| 1     | 5        | 15.63%  |
| 4     | 2        | 6.25%   |
| 3     | 1        | 3.13%   |
| 2     | 1        | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 5        | 29.41%  |
| Graphics card            | 4        | 23.53%  |
| Unassigned class         | 2        | 11.76%  |
| Communication controller | 2        | 11.76%  |
| Net/wireless             | 1        | 5.88%   |
| Net/ethernet             | 1        | 5.88%   |
| Chipcard                 | 1        | 5.88%   |
| Camera                   | 1        | 5.88%   |

