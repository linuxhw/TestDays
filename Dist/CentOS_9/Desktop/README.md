CentOS 9 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 9.

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

Total: 32

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H670-PLUS D4          | [5a711c0ff0](https://linux-hardware.org/?probe=5a711c0ff0) | Jan 20, 2024 |
| ASUSTek       | AT4NM10T-I                  | [7adc9b4d41](https://linux-hardware.org/?probe=7adc9b4d41) | Jan 06, 2024 |
| MSI           | MAG B760M MORTAR WIFI       | [342164a6a4](https://linux-hardware.org/?probe=342164a6a4) | Dec 29, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | [bd7c6e2693](https://linux-hardware.org/?probe=bd7c6e2693) | Dec 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [e8965075d3](https://linux-hardware.org/?probe=e8965075d3) | Dec 14, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [e9e5956d89](https://linux-hardware.org/?probe=e9e5956d89) | Dec 10, 2023 |
| MSI           | MEG Z790 ACE                | [41d0e4fddd](https://linux-hardware.org/?probe=41d0e4fddd) | Oct 24, 2023 |
| ASUSTek       | P8H61/USB3                  | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Gateway       | H61H2-AD V1.0               | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| ASUSTek       | P8H67-M LE                  | [a69366e2b7](https://linux-hardware.org/?probe=a69366e2b7) | May 29, 2023 |
| ASUSTek       | P8H67-M LE                  | [07202660b9](https://linux-hardware.org/?probe=07202660b9) | May 26, 2023 |
| Acer          | Predator G3-605             | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| Dell          | 0NKW6Y A02                  | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| MSI           | X470 GAMING PRO             | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| Intel         | D34010WYK H14771-303        | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | H81M-K                      | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| ASUSTek       | H81M-K                      | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| NCR           | Pocono BIOS.6.0             | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.14.0-391.el9.x86_64          | 2        | 7.69%   |
| 5.14.0-202.el9.x86_64          | 2        | 7.69%   |
| 5.17.2-lqx3.0.el9.x86_64       | 1        | 3.85%   |
| 5.14.0-86.el9.x86_64           | 1        | 3.85%   |
| 5.14.0-407.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-390.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-375.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-362.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-352.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-344.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-340.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-325.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-319.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-316.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-305.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-302.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-267.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-214.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-183.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-134.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1        | 3.85%   |
| 5.14.0-115.el9.x86_64          | 1        | 3.85%   |
| 5.14.0-109.el9.x86_64          | 1        | 3.85%   |
| 4.18.0-529.el8.x86_64          | 1        | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 18       | 90%     |
| 5.17.2  | 1        | 5%      |
| 4.18.0  | 1        | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 18       | 90%     |
| 5.17    | 1        | 5%      |
| 4.18    | 1        | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 20       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 15       | 75%     |
| KDE5          | 2        | 10%     |
| GNOME Classic | 2        | 10%     |
| Unknown       | 1        | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 11       | 52.38%  |
| X11     | 9        | 42.86%  |
| Unknown | 1        | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 61.9%   |
| GDM     | 7        | 33.33%  |
| SDDM    | 1        | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 11       | 55%     |
| ja_JP   | 2        | 10%     |
| zh_CN   | 1        | 5%      |
| ru_UA   | 1        | 5%      |
| pt_BR   | 1        | 5%      |
| it_IT   | 1        | 5%      |
| en_AU   | 1        | 5%      |
| de_DE   | 1        | 5%      |
| Unknown | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 14       | 66.67%  |
| BIOS | 7        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 17       | 85%     |
| Ext4 | 3        | 15%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 54.55%  |
| GPT     | 7        | 31.82%  |
| MBR     | 3        | 13.64%  |

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
| No        | 16       | 72.73%  |
| Yes       | 6        | 27.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 45%     |
| MSI                 | 3        | 15%     |
| Gigabyte Technology | 2        | 10%     |
| SHANGZHAOYUAN       | 1        | 5%      |
| Intel               | 1        | 5%      |
| Gateway             | 1        | 5%      |
| Dell                | 1        | 5%      |
| Colorful Technology | 1        | 5%      |
| Acer                | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS PRIME H670-PLUS D4           | 2        | 10%     |
| SHANGZHAOYUAN B85M-PRO V1.1       | 1        | 5%      |
| MSI MS-7E01                       | 1        | 5%      |
| MSI MS-7D86                       | 1        | 5%      |
| MSI MS-7B79                       | 1        | 5%      |
| Intel D34010WYK H14771-303        | 1        | 5%      |
| Gigabyte X99-UD4-CF               | 1        | 5%      |
| Gigabyte 970A-DS3P                | 1        | 5%      |
| Gateway SX2865                    | 1        | 5%      |
| Dell OptiPlex 790                 | 1        | 5%      |
| Colorful CVN Z590 GAMING PRO      | 1        | 5%      |
| ASUS TUF Gaming X570-PLUS         | 1        | 5%      |
| ASUS ROG STRIX B560-G GAMING WIFI | 1        | 5%      |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 5%      |
| ASUS P8H67-M LE                   | 1        | 5%      |
| ASUS P8H61/USB3                   | 1        | 5%      |
| ASUS AT4NM10T-I                   | 1        | 5%      |
| ASUS All Series                   | 1        | 5%      |
| Acer Predator G3-605              | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 2        | 10%     |
| ASUS PRIME             | 2        | 10%     |
| SHANGZHAOYUAN B85M-PRO | 1        | 5%      |
| MSI MS-7E01            | 1        | 5%      |
| MSI MS-7D86            | 1        | 5%      |
| MSI MS-7B79            | 1        | 5%      |
| Intel D34010WYK        | 1        | 5%      |
| Gigabyte X99-UD4-CF    | 1        | 5%      |
| Gigabyte 970A-DS3P     | 1        | 5%      |
| Gateway SX2865         | 1        | 5%      |
| Dell OptiPlex          | 1        | 5%      |
| Colorful CVN           | 1        | 5%      |
| ASUS TUF               | 1        | 5%      |
| ASUS P8H67-M           | 1        | 5%      |
| ASUS P8H61             | 1        | 5%      |
| ASUS AT4NM10T-I        | 1        | 5%      |
| ASUS All               | 1        | 5%      |
| Acer Predator          | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 6        | 30%     |
| 2021 | 4        | 20%     |
| 2011 | 3        | 15%     |
| 2022 | 2        | 10%     |
| 2023 | 1        | 5%      |
| 2020 | 1        | 5%      |
| 2019 | 1        | 5%      |
| 2018 | 1        | 5%      |
| 2014 | 1        | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 20       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 18       | 90%     |
| Enabled  | 2        | 10%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 6        | 30%     |
| 64.01-256.0 | 5        | 25%     |
| 32.01-64.0  | 4        | 20%     |
| 16.01-24.0  | 2        | 10%     |
| 8.01-16.0   | 2        | 10%     |
| 3.01-4.0    | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 8        | 34.78%  |
| 2.01-3.0   | 8        | 34.78%  |
| 4.01-8.0   | 2        | 8.7%    |
| 1.01-2.0   | 2        | 8.7%    |
| 8.01-16.0  | 2        | 8.7%    |
| 16.01-24.0 | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 6        | 30%     |
| 4      | 5        | 25%     |
| 2      | 4        | 20%     |
| 1      | 4        | 20%     |
| 5      | 1        | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 75%     |
| Yes       | 5        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11       | 55%     |
| No        | 9        | 45%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 50%     |
| No        | 10       | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 25%     |
| Bulgaria    | 3        | 15%     |
| Japan       | 2        | 10%     |
| Ukraine     | 1        | 5%      |
| Russia      | 1        | 5%      |
| Puerto Rico | 1        | 5%      |
| Myanmar     | 1        | 5%      |
| Italy       | 1        | 5%      |
| Germany     | 1        | 5%      |
| China       | 1        | 5%      |
| Brazil      | 1        | 5%      |
| Belarus     | 1        | 5%      |
| Australia   | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sofia          | 2        | 9.09%   |
| Yangon         | 1        | 4.55%   |
| Wuhan          | 1        | 4.55%   |
| Vitebsk        | 1        | 4.55%   |
| Tomah          | 1        | 4.55%   |
| San Juan       | 1        | 4.55%   |
| Rome           | 1        | 4.55%   |
| Porto Alegre   | 1        | 4.55%   |
| Portland       | 1        | 4.55%   |
| Perth          | 1        | 4.55%   |
| Okazaki        | 1        | 4.55%   |
| New Cumberland | 1        | 4.55%   |
| Navapolatsk    | 1        | 4.55%   |
| Nagoya         | 1        | 4.55%   |
| Moscow         | 1        | 4.55%   |
| Milpitas       | 1        | 4.55%   |
| Meieki         | 1        | 4.55%   |
| Kyiv           | 1        | 4.55%   |
| Durham         | 1        | 4.55%   |
| Dortmund       | 1        | 4.55%   |
| Burgas         | 1        | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 15     | 23.26%  |
| Seagate             | 6        | 9      | 13.95%  |
| Toshiba             | 4        | 6      | 9.3%    |
| Samsung Electronics | 4        | 5      | 9.3%    |
| Kingston            | 4        | 6      | 9.3%    |
| Sandisk             | 3        | 13     | 6.98%   |
| Crucial             | 2        | 12     | 4.65%   |
| WD MediaMax         | 1        | 1      | 2.33%   |
| Team                | 1        | 2      | 2.33%   |
| Plextor             | 1        | 1      | 2.33%   |
| Phison Electronics  | 1        | 1      | 2.33%   |
| Phison              | 1        | 1      | 2.33%   |
| OCZ                 | 1        | 1      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| Hitachi             | 1        | 1      | 2.33%   |
| Gigabyte Technology | 1        | 2      | 2.33%   |
| A-DATA Technology   | 1        | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB             | 2        | 4.17%   |
| Sandisk WD_BLACK SN770 1TB                 | 2        | 4.17%   |
| SanDisk SDSSDH3 1T00 1TB                   | 2        | 4.17%   |
| Crucial CT525MX300SSD1 528GB               | 2        | 4.17%   |
| WDC WDS250G2B0A-00SM50 250GB SSD           | 1        | 2.08%   |
| WDC WD6003FZBX-00K5WB0 6TB                 | 1        | 2.08%   |
| WDC WD5000BEVT-55A0RT0 500GB               | 1        | 2.08%   |
| WDC WD3200AAKX-753CA1 320GB                | 1        | 2.08%   |
| WDC WD2500AAJS-60M0A0 250GB                | 1        | 2.08%   |
| WDC WD22EJRX-89BEMY0 2TB                   | 1        | 2.08%   |
| WDC WD2003FZEX-00Z4SA0 2TB                 | 1        | 2.08%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 2.08%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 2.08%   |
| WDC WD10EZEX-00BN5A0 1TB                   | 1        | 2.08%   |
| WDC WD Blue SA510 2.5 500GB                | 1        | 2.08%   |
| WD MediaMax WL750GSA6472 752GB             | 1        | 2.08%   |
| Toshiba MK2561GSYN 250GB                   | 1        | 2.08%   |
| Toshiba MK1234GSX 120GB                    | 1        | 2.08%   |
| Toshiba DT01ACA200 2TB                     | 1        | 2.08%   |
| Toshiba DT01ACA100 1TB                     | 1        | 2.08%   |
| Team T253X1480G 480GB SSD                  | 1        | 2.08%   |
| Seagate ST3500413AS 500GB                  | 1        | 2.08%   |
| Seagate ST3250820AS 249GB                  | 1        | 2.08%   |
| Seagate ST320LM001 HN-M320MBB 320GB        | 1        | 2.08%   |
| Seagate ST2000DL003-9VT166 2TB             | 1        | 2.08%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 2.08%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB | 1        | 2.08%   |
| Sandisk WD_BLACK SN850X 4000GB             | 1        | 2.08%   |
| Samsung SSD 870 QVO 2TB                    | 1        | 2.08%   |
| Samsung SSD 870 EVO 250GB                  | 1        | 2.08%   |
| Samsung SSD 860 PRO 2TB                    | 1        | 2.08%   |
| Samsung MZ7LN256HAJQ-00000 256GB SSD       | 1        | 2.08%   |
| Plextor PX-256M8VC 256GB SSD               | 1        | 2.08%   |
| Phison NVMe SSD Drive 1024GB               | 1        | 2.08%   |
| Phison E16 PCIe4 NVMe Controller 2TB       | 1        | 2.08%   |
| OCZ AGILITY3 64GB SSD                      | 1        | 2.08%   |
| Kingston SUV400S37480G 480GB SSD           | 1        | 2.08%   |
| Kingston SHFS37A480G 480GB SSD             | 1        | 2.08%   |
| Kingston SFYRD2000G 2TB                    | 1        | 2.08%   |
| Kingston RBU-SMS100S3128GA 128GB SSD       | 1        | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 8        | 13     | 42.11%  |
| Seagate     | 5        | 7      | 26.32%  |
| Toshiba     | 4        | 6      | 21.05%  |
| WD MediaMax | 1        | 1      | 5.26%   |
| Hitachi     | 1        | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 22.22%  |
| Kingston            | 3        | 5      | 16.67%  |
| WDC                 | 2        | 2      | 11.11%  |
| SanDisk             | 2        | 6      | 11.11%  |
| Crucial             | 2        | 12     | 11.11%  |
| Team                | 1        | 2      | 5.56%   |
| Plextor             | 1        | 1      | 5.56%   |
| OCZ                 | 1        | 1      | 5.56%   |
| Gigabyte Technology | 1        | 2      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 14       | 37     | 41.18%  |
| HDD  | 12       | 28     | 35.29%  |
| NVMe | 8        | 13     | 23.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 65     | 69.23%  |
| NVMe | 8        | 13     | 30.77%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 23     | 44.83%  |
| 0.51-1.0   | 9        | 29     | 31.03%  |
| 1.01-2.0   | 6        | 11     | 20.69%  |
| 4.01-10.0  | 1        | 2      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 7        | 33.33%  |
| 101-250        | 4        | 19.05%  |
| 251-500        | 3        | 14.29%  |
| More than 3000 | 2        | 9.52%   |
| 21-50          | 1        | 4.76%   |
| 2001-3000      | 1        | 4.76%   |
| 501-1000       | 1        | 4.76%   |
| 51-100         | 1        | 4.76%   |
| Unknown        | 1        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 6        | 30%     |
| 21-50          | 4        | 20%     |
| 51-100         | 4        | 20%     |
| 501-1000       | 3        | 15%     |
| More than 3000 | 1        | 5%      |
| 251-500        | 1        | 5%      |
| Unknown        | 1        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD10EZEX-60M2NA0 1TB  | 1        | 1      | 25%     |
| Toshiba MK2561GSYN 250GB  | 1        | 1      | 25%     |
| Toshiba MK1234GSX 120GB   | 1        | 1      | 25%     |
| Seagate ST3250820AS 249GB | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 50%     |
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 50%     |
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 4      | 100%    |

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
| Detected | 13       | 47     | 52%     |
| Works    | 9        | 27     | 36%     |
| Malfunc  | 3        | 4      | 12%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 17       | 54.84%  |
| AMD                         | 4        | 12.9%   |
| SanDisk                     | 3        | 9.68%   |
| Phison Electronics          | 2        | 6.45%   |
| Silicon Image               | 1        | 3.23%   |
| Seagate Technology          | 1        | 3.23%   |
| Kingston Technology Company | 1        | 3.23%   |
| JMicron Technology          | 1        | 3.23%   |
| ASMedia Technology          | 1        | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 12.5%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 9.38%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 9.38%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2        | 6.25%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 6.25%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 6.25%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 6.25%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 3.13%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1        | 3.13%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 3.13%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 3.13%   |
| Phison E12 NVMe Controller                                                     | 1        | 3.13%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1        | 3.13%   |
| JMicron JMB362 SATA Controller                                                 | 1        | 3.13%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1        | 3.13%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 3.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 3.13%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 1        | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 65.52%  |
| NVMe | 8        | 27.59%  |
| RAID | 2        | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 80%     |
| AMD    | 4        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel 12th Gen Core i5-12600K          | 2        | 10%     |
| Intel Core i7-5930K CPU @ 3.50GHz      | 1        | 5%      |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 5%      |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 5%      |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 5%      |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 5%      |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 5%      |
| Intel Core i5-2400S CPU @ 2.50GHz      | 1        | 5%      |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 5%      |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1        | 5%      |
| Intel Core i3-2130 CPU @ 3.40GHz       | 1        | 5%      |
| Intel Atom CPU D425 @ 1.80GHz          | 1        | 5%      |
| Intel 13th Gen Core i9-13900K          | 1        | 5%      |
| Intel 13th Gen Core i7-13700K          | 1        | 5%      |
| Intel 11th Gen Core i5-11400 @ 2.60GHz | 1        | 5%      |
| AMD Ryzen 9 5950X 16-Core Processor    | 1        | 5%      |
| AMD Ryzen 9 3950X 16-Core Processor    | 1        | 5%      |
| AMD Ryzen 5 3600 6-Core Processor      | 1        | 5%      |
| AMD FX-8120 Eight-Core Processor       | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Other         | 5        | 25%     |
| Intel Core i5 | 5        | 25%     |
| Intel Core i7 | 3        | 15%     |
| Intel Core i3 | 2        | 10%     |
| AMD Ryzen 9   | 2        | 10%     |
| Intel Atom    | 1        | 5%      |
| AMD Ryzen 5   | 1        | 5%      |
| AMD FX        | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 35%     |
| 6      | 4        | 20%     |
| 16     | 3        | 15%     |
| 10     | 2        | 10%     |
| 2      | 2        | 10%     |
| 24     | 1        | 5%      |
| 1      | 1        | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 75%     |
| 1      | 5        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 20       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 40%     |
| 0x306c3    | 2        | 10%     |
| 0xa0671    | 1        | 5%      |
| 0xa0653    | 1        | 5%      |
| 0x90672    | 1        | 5%      |
| 0x40651    | 1        | 5%      |
| 0x306f2    | 1        | 5%      |
| 0x206a7    | 1        | 5%      |
| 0x0a201016 | 1        | 5%      |
| 0x08701021 | 1        | 5%      |
| 0x08701013 | 1        | 5%      |
| 0x0600063d | 1        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 5        | 23.81%  |
| Alderlake Hybrid | 4        | 19.05%  |
| SandyBridge      | 3        | 14.29%  |
| Zen 2            | 2        | 9.52%   |
| Zen 3            | 1        | 4.76%   |
| IvyBridge        | 1        | 4.76%   |
| Icelake          | 1        | 4.76%   |
| CometLake        | 1        | 4.76%   |
| Bulldozer        | 1        | 4.76%   |
| Bonnell          | 1        | 4.76%   |
| Unknown          | 1        | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 38.1%   |
| Intel  | 8        | 38.1%   |
| AMD    | 5        | 23.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 8.7%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 8.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 8.7%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 4.35%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 4.35%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 4.35%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 4.35%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 4.35%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 4.35%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4.35%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 4.35%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 4.35%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                       | 1        | 4.35%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                   | 1        | 4.35%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 1        | 4.35%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 4.35%   |
| AMD Juniper XT [Radeon HD 6770]                                             | 1        | 4.35%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 8        | 40%     |
| 1 x Intel  | 7        | 35%     |
| 1 x AMD    | 4        | 20%     |
| 2 x AMD    | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 66.67%  |
| Proprietary | 6        | 28.57%  |
| Unknown     | 1        | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 40.91%  |
| 5.01-6.0   | 3        | 13.64%  |
| 3.01-4.0   | 3        | 13.64%  |
| 1.01-2.0   | 2        | 9.09%   |
| 8.01-16.0  | 2        | 9.09%   |
| 0.51-1.0   | 2        | 9.09%   |
| 0.01-0.5   | 1        | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 21.74%  |
| Goldstar            | 4        | 17.39%  |
| Dell                | 3        | 13.04%  |
| ViewSonic           | 2        | 8.7%    |
| Iiyama              | 2        | 8.7%    |
| AOC                 | 2        | 8.7%    |
| LG Electronics      | 1        | 4.35%   |
| HKC                 | 1        | 4.35%   |
| Hewlett-Packard     | 1        | 4.35%   |
| BenQ                | 1        | 4.35%   |
| Acer                | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 620x340mm 27.8-inch                  | 2        | 7.41%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1        | 3.7%    |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1        | 3.7%    |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch     | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch  | 1        | 3.7%    |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1        | 3.7%    |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch     | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1        | 3.7%    |
| LG Electronics LCD Monitor LG FULL HD                                 | 1        | 3.7%    |
| HKC 24N1 HKC2413 1920x1080 527x296mm 23.8-inch                        | 1        | 3.7%    |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch            | 1        | 3.7%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1        | 3.7%    |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1        | 3.7%    |
| Goldstar 27GL650F GSM5B70 1920x1080 531x298mm 24.0-inch               | 1        | 3.7%    |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                 | 1        | 3.7%    |
| Dell U2720Q DEL41B0 3840x2160 597x336mm 27.0-inch                     | 1        | 3.7%    |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 1        | 3.7%    |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                     | 1        | 3.7%    |
| Dell U2520D DELA14E 2560x1440 553x311mm 25.0-inch                     | 1        | 3.7%    |
| Dell U2520D DELA14C 2560x1440 553x311mm 25.0-inch                     | 1        | 3.7%    |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                    | 1        | 3.7%    |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                    | 1        | 3.7%    |
| BenQ ZOWIE XL LCD BNQ7F83 1920x1080 544x303mm 24.5-inch               | 1        | 3.7%    |
| AOC LCD Monitor 24G1WG4 3840x1080                                     | 1        | 3.7%    |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch                        | 1        | 3.7%    |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                     | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 60.87%  |
| 3840x2160 (4K)     | 4        | 17.39%  |
| 3840x1080          | 1        | 4.35%   |
| 2560x1440 (QHD)    | 1        | 4.35%   |
| 1920x1200 (WUXGA)  | 1        | 4.35%   |
| 1680x1050 (WSXGA+) | 1        | 4.35%   |
| Unknown            | 1        | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 29.17%  |
| 21      | 6        | 25%     |
| 24      | 3        | 12.5%   |
| 23      | 3        | 12.5%   |
| 84      | 1        | 4.17%   |
| 38      | 1        | 4.17%   |
| 25      | 1        | 4.17%   |
| 22      | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 39.13%  |
| 401-500     | 7        | 30.43%  |
| 601-700     | 4        | 17.39%  |
| 801-900     | 1        | 4.35%   |
| 1501-2000   | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 84.21%  |
| 16/10   | 2        | 10.53%  |
| Unknown | 1        | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 43.48%  |
| 301-350        | 7        | 30.43%  |
| 251-300        | 3        | 13.04%  |
| More than 1000 | 1        | 4.35%   |
| 501-1000       | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 47.83%  |
| 101-120 | 8        | 34.78%  |
| 121-160 | 2        | 8.7%    |
| 161-240 | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 61.9%   |
| 2     | 5        | 23.81%  |
| 0     | 2        | 9.52%   |
| 4     | 1        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 41.18%  |
| Intel                 | 12       | 35.29%  |
| Qualcomm Atheros      | 3        | 8.82%   |
| U-Blox                | 1        | 2.94%   |
| TP-Link               | 1        | 2.94%   |
| DisplayLink           | 1        | 2.94%   |
| Ceton Technologies    | 1        | 2.94%   |
| Aquantia              | 1        | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 8        | 20.51%  |
| Realtek RTL8125 2.5GbE Controller                                               | 4        | 10.26%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 2        | 5.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                | 2        | 5.13%   |
| Intel Wi-Fi 6 AX200                                                             | 2        | 5.13%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                               | 2        | 5.13%   |
| Intel Ethernet Controller I225-V                                                | 2        | 5.13%   |
| U-Blox [u-blox 8]                                                               | 1        | 2.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                          | 1        | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 1        | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 1        | 2.56%   |
| Intel Wireless 7260                                                             | 1        | 2.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 1        | 2.56%   |
| Intel I211 Gigabit Network Connection                                           | 1        | 2.56%   |
| Intel Ethernet Controller I226-V                                                | 1        | 2.56%   |
| Intel Ethernet Connection I218-V                                                | 1        | 2.56%   |
| Intel Ethernet Connection I217-V                                                | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-V                                            | 1        | 2.56%   |
| Intel 82579V Gigabit Network Connection                                         | 1        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 1        | 2.56%   |
| Intel 82574L Gigabit Network Connection                                         | 1        | 2.56%   |
| DisplayLink Plugable UD-6950PDZ                                                 | 1        | 2.56%   |
| Ceton InfiniTV Network                                                          | 1        | 2.56%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 50%     |
| Qualcomm Atheros      | 3        | 25%     |
| Realtek Semiconductor | 2        | 16.67%  |
| TP-Link               | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 16.67%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2        | 16.67%  |
| Intel Wi-Fi 6 AX200                                        | 2        | 16.67%  |
| Intel Raptor Lake-S PCH CNVi WiFi                          | 2        | 16.67%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 8.33%   |
| Intel Wireless 7260                                        | 1        | 8.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]    | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 48%     |
| Intel                 | 10       | 40%     |
| DisplayLink           | 1        | 4%      |
| Ceton Technologies    | 1        | 4%      |
| Aquantia              | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 8        | 30.77%  |
| Realtek RTL8125 2.5GbE Controller                                               | 4        | 15.38%  |
| Intel Ethernet Controller I225-V                                                | 2        | 7.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 1        | 3.85%   |
| Intel I211 Gigabit Network Connection                                           | 1        | 3.85%   |
| Intel Ethernet Controller I226-V                                                | 1        | 3.85%   |
| Intel Ethernet Connection I218-V                                                | 1        | 3.85%   |
| Intel Ethernet Connection I217-V                                                | 1        | 3.85%   |
| Intel Ethernet Connection (2) I218-V                                            | 1        | 3.85%   |
| Intel 82579V Gigabit Network Connection                                         | 1        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 1        | 3.85%   |
| Intel 82574L Gigabit Network Connection                                         | 1        | 3.85%   |
| DisplayLink Plugable UD-6950PDZ                                                 | 1        | 3.85%   |
| Ceton InfiniTV Network                                                          | 1        | 3.85%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1        | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 62.5%   |
| WiFi     | 11       | 34.38%  |
| Modem    | 1        | 3.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 90.48%  |
| WiFi     | 2        | 9.52%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 10       | 50%     |
| 1     | 7        | 35%     |
| 3     | 3        | 15%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 70%     |
| Yes  | 6        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 60%     |
| Qualcomm Atheros Communications | 1        | 10%     |
| Lite-On Technology              | 1        | 10%     |
| Cambridge Silicon Radio         | 1        | 10%     |
| ASUSTek Computer                | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 2        | 20%     |
| Intel AX200 Bluetooth                               | 2        | 20%     |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 10%     |
| Lite-On Bluetooth Device                            | 1        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 10%     |
| Intel Bluetooth wireless interface                  | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 10%     |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 16       | 44.44%  |
| Nvidia                   | 8        | 22.22%  |
| AMD                      | 7        | 19.44%  |
| SteelSeries ApS          | 3        | 8.33%   |
| Micro Star International | 1        | 2.78%   |
| Anlya.cn                 | 1        | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 10%     |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 7.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 7.5%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 5%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 5%      |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 5%      |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 5%      |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1        | 2.5%    |
| SteelSeries ApS SteelSeries GameDAC                                        | 1        | 2.5%    |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1        | 2.5%    |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 2.5%    |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 2.5%    |
| Nvidia GM200 High Definition Audio                                         | 1        | 2.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.5%    |
| Micro Star International USB Audio                                         | 1        | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.5%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 2.5%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 2.5%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 1        | 2.5%    |
| Anlya.cn AB13X USB Audio                                                   | 1        | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.5%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 2.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.5%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 2        | 18.18%  |
| Crucial             | 2        | 18.18%  |
| Corsair             | 2        | 18.18%  |
| Unknown             | 1        | 9.09%   |
| Team                | 1        | 9.09%   |
| SK hynix            | 1        | 9.09%   |
| Samsung Electronics | 1        | 9.09%   |
| Kingston            | 1        | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s               | 1        | 9.09%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s       | 1        | 9.09%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 9.09%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s      | 1        | 9.09%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 9.09%   |
| G.Skill RAM F5-5600J3036D32G 32GB DIMM DDR5 5600MT/s     | 1        | 9.09%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s    | 1        | 9.09%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s | 1        | 9.09%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s    | 1        | 9.09%   |
| Corsair RAM CMK64GX4M2Z4000C18 32GB DIMM DDR4 4000MT/s   | 1        | 9.09%   |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s  | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 6        | 54.55%  |
| DDR4 | 4        | 36.36%  |
| DDR5 | 1        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 10       | 90.91%  |
| SODIMM | 1        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 3        | 27.27%  |
| 8192  | 3        | 27.27%  |
| 16384 | 2        | 18.18%  |
| 4096  | 2        | 18.18%  |
| 2048  | 1        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 27.27%  |
| 1800  | 2        | 18.18%  |
| 5600  | 1        | 9.09%   |
| 4000  | 1        | 9.09%   |
| 3600  | 1        | 9.09%   |
| 2933  | 1        | 9.09%   |
| 2133  | 1        | 9.09%   |
| 800   | 1        | 9.09%   |

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
| Sunplus Innovation Technology | 2        | 40%     |
| Logitech                      | 2        | 40%     |
| KYE Systems                   | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus Full HD webcam          | 2        | 40%     |
| Logitech Webcam C270            | 1        | 20%     |
| Logitech C922 Pro Stream Webcam | 1        | 20%     |
| KYE Systems FaceCam 1320        | 1        | 20%     |

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
| 0     | 15       | 68.18%  |
| 1     | 6        | 27.27%  |
| 2     | 1        | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 37.5%   |
| Unassigned class | 1        | 12.5%   |
| Storage/ata      | 1        | 12.5%   |
| Graphics card    | 1        | 12.5%   |
| Dvb card         | 1        | 12.5%   |
| Bluetooth        | 1        | 12.5%   |

