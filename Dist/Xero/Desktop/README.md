Xero - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Xero.

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

Total: 31

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Acer     | Aspire XC-886 V:2.0      | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| ASUSTek  | ROG Maximus X HERO       | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| MSI      | Z170-A PRO               | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| MSI      | Z170-A PRO               | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| HP       | 843B                     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron | 2AC2                     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek  | Maximus IX HERO          | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| ASUSTek  | Maximus IX HERO          | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO  | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS    | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| MSI      | Z170A PC MATE            | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte | Z170X-UD3-CF             | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| ASUSTek  | P5Q PRO TURBO            | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS    | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| HP       | 1906                     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP       | 2179                     | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek  | TUF B360M-PLUS GAMING/BR | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| HP       | 2179                     | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASRock   | X570 Taichi              | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek  | TUF Gaming X570-PLUS     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek  | PRIME A320M-K            | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| ASUSTek  | TUF Z390-PLUS GAMING     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI      | Z370 GAMING PLUS         | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Dell     | 0XC7MM A01               | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| ASRock   | B450M Pro4               | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock   | X570 Taichi              | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte | X570 AORUS MASTER        | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock   | X570 Taichi              | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer     | FIH57                    | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Xero Rolling | 21       | 87.5%   |
| Xero         | 3        | 12.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Xero | 24       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.16.15-arch1-1         | 2        | 7.14%   |
| 5.16.12-arch1-1         | 2        | 7.14%   |
| 5.18.0-arch1-1          | 1        | 3.57%   |
| 5.17.5-arch1-1          | 1        | 3.57%   |
| 5.17.1-arch1-1          | 1        | 3.57%   |
| 5.16.16-zen1-1-zen      | 1        | 3.57%   |
| 5.16.16-arch1-1         | 1        | 3.57%   |
| 5.16.13-arch1-1         | 1        | 3.57%   |
| 5.16.1-arch1-1          | 1        | 3.57%   |
| 5.15.4-arch1-1          | 1        | 3.57%   |
| 5.15.33-1-lts           | 1        | 3.57%   |
| 5.15.3-zen1-1-zen       | 1        | 3.57%   |
| 5.15.13-AMD             | 1        | 3.57%   |
| 5.15.12-zen1-1-zen      | 1        | 3.57%   |
| 5.15.12-arch1-1-surface | 1        | 3.57%   |
| 5.15.12-arch1-1         | 1        | 3.57%   |
| 5.15.11-arch2-1-surface | 1        | 3.57%   |
| 5.15.10-arch1-1         | 1        | 3.57%   |
| 5.14.9-zen2-1-zen       | 1        | 3.57%   |
| 5.14.8-zen1-1-zen       | 1        | 3.57%   |
| 5.14.15-zen1-1-zen      | 1        | 3.57%   |
| 5.14.14-arch1-1         | 1        | 3.57%   |
| 5.13.4-zen1-1-zen       | 1        | 3.57%   |
| 5.13.13-AMD             | 1        | 3.57%   |
| 5.12.5-AMD              | 1        | 3.57%   |
| 5.11.16-zen1-1-zen      | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 3        | 10.71%  |
| 5.16.16 | 2        | 7.14%   |
| 5.16.15 | 2        | 7.14%   |
| 5.16.12 | 2        | 7.14%   |
| 5.18.0  | 1        | 3.57%   |
| 5.17.5  | 1        | 3.57%   |
| 5.17.1  | 1        | 3.57%   |
| 5.16.13 | 1        | 3.57%   |
| 5.16.1  | 1        | 3.57%   |
| 5.15.4  | 1        | 3.57%   |
| 5.15.33 | 1        | 3.57%   |
| 5.15.3  | 1        | 3.57%   |
| 5.15.13 | 1        | 3.57%   |
| 5.15.11 | 1        | 3.57%   |
| 5.15.10 | 1        | 3.57%   |
| 5.14.9  | 1        | 3.57%   |
| 5.14.8  | 1        | 3.57%   |
| 5.14.15 | 1        | 3.57%   |
| 5.14.14 | 1        | 3.57%   |
| 5.13.4  | 1        | 3.57%   |
| 5.13.13 | 1        | 3.57%   |
| 5.12.5  | 1        | 3.57%   |
| 5.11.16 | 1        | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 8        | 29.63%  |
| 5.15    | 8        | 29.63%  |
| 5.14    | 4        | 14.81%  |
| 5.17    | 2        | 7.41%   |
| 5.13    | 2        | 7.41%   |
| 5.18    | 1        | 3.7%    |
| 5.12    | 1        | 3.7%    |
| 5.11    | 1        | 3.7%    |

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


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 22       | 88%     |
| XFCE  | 2        | 8%      |
| GNOME | 1        | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 20       | 83.33%  |
| Wayland | 2        | 8.33%   |
| Tty     | 2        | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 16       | 64%     |
| LightDM | 4        | 16%     |
| Unknown | 3        | 12%     |
| TDM     | 1        | 4%      |
| GDM     | 1        | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 14       | 58.33%  |
| en_GB | 2        | 8.33%   |
| C     | 2        | 8.33%   |
| pl_PL | 1        | 4.17%   |
| en_IN | 1        | 4.17%   |
| en_CA | 1        | 4.17%   |
| en_AU | 1        | 4.17%   |
| de_DE | 1        | 4.17%   |
| de_AT | 1        | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 16       | 66.67%  |
| BIOS | 8        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 18       | 72%     |
| Ext4    | 5        | 20%     |
| Overlay | 2        | 8%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 17       | 70.83%  |
| MBR     | 4        | 16.67%  |
| Unknown | 3        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 72%     |
| Yes       | 7        | 28%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 58.33%  |
| Yes       | 10       | 41.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 41.67%  |
| MSI                 | 3        | 12.5%   |
| Hewlett-Packard     | 3        | 12.5%   |
| Gigabyte Technology | 2        | 8.33%   |
| ASRock              | 2        | 8.33%   |
| Acer                | 2        | 8.33%   |
| Pegatron            | 1        | 4.17%   |
| Dell                | 1        | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7971                   | 2        | 8.33%   |
| ASUS TUF Gaming X570-PLUS     | 2        | 8.33%   |
| Pegatron p6-2026              | 1        | 4.17%   |
| MSI MS-7B61                   | 1        | 4.17%   |
| HP Z230 SFF Workstation       | 1        | 4.17%   |
| HP ProOne 400 G1 AiO          | 1        | 4.17%   |
| HP Pavilion Desktop 590-p0xxx | 1        | 4.17%   |
| Gigabyte Z170X-UD3            | 1        | 4.17%   |
| Gigabyte X570 AORUS MASTER    | 1        | 4.17%   |
| Dell Precision T1500          | 1        | 4.17%   |
| ASUS TUF Z390-PLUS GAMING     | 1        | 4.17%   |
| ASUS TUF Gaming B550M-PLUS    | 1        | 4.17%   |
| ASUS TUF B360M-PLUS GAMING/BR | 1        | 4.17%   |
| ASUS ROG Maximus X HERO       | 1        | 4.17%   |
| ASUS ROG CROSSHAIR VIII HERO  | 1        | 4.17%   |
| ASUS PRIME A320M-K            | 1        | 4.17%   |
| ASUS P5Q PRO TURBO            | 1        | 4.17%   |
| ASUS Maximus IX HERO          | 1        | 4.17%   |
| ASRock X570 Taichi            | 1        | 4.17%   |
| ASRock B450M Pro4             | 1        | 4.17%   |
| Acer Aspire XC-886            | 1        | 4.17%   |
| Acer Aspire X5950             | 1        | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS TUF           | 5        | 20.83%  |
| MSI MS-7971        | 2        | 8.33%   |
| ASUS ROG           | 2        | 8.33%   |
| Acer Aspire        | 2        | 8.33%   |
| Pegatron p6-2026   | 1        | 4.17%   |
| MSI MS-7B61        | 1        | 4.17%   |
| HP Z230            | 1        | 4.17%   |
| HP ProOne          | 1        | 4.17%   |
| HP Pavilion        | 1        | 4.17%   |
| Gigabyte Z170X-UD3 | 1        | 4.17%   |
| Gigabyte X570      | 1        | 4.17%   |
| Dell Precision     | 1        | 4.17%   |
| ASUS PRIME         | 1        | 4.17%   |
| ASUS P5Q           | 1        | 4.17%   |
| ASUS Maximus       | 1        | 4.17%   |
| ASRock X570        | 1        | 4.17%   |
| ASRock B450M       | 1        | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 5        | 20.83%  |
| 2018 | 5        | 20.83%  |
| 2017 | 3        | 12.5%   |
| 2015 | 3        | 12.5%   |
| 2010 | 2        | 8.33%   |
| 2021 | 1        | 4.17%   |
| 2020 | 1        | 4.17%   |
| 2014 | 1        | 4.17%   |
| 2013 | 1        | 4.17%   |
| 2011 | 1        | 4.17%   |
| 2009 | 1        | 4.17%   |

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


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 7        | 29.17%  |
| 16.01-24.0  | 7        | 29.17%  |
| 8.01-16.0   | 6        | 25%     |
| 4.01-8.0    | 3        | 12.5%   |
| 64.01-256.0 | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 7        | 24.14%  |
| 2.01-3.0   | 7        | 24.14%  |
| 1.01-2.0   | 5        | 17.24%  |
| 3.01-4.0   | 3        | 10.34%  |
| 8.01-16.0  | 3        | 10.34%  |
| 0.01-0.5   | 2        | 6.9%    |
| 16.01-24.0 | 1        | 3.45%   |
| 0.51-1.0   | 1        | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 33.33%  |
| 3      | 6        | 25%     |
| 2      | 5        | 20.83%  |
| 6      | 2        | 8.33%   |
| 4      | 2        | 8.33%   |
| 7      | 1        | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 75%     |
| Yes       | 6        | 25%     |

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
| Yes       | 15       | 62.5%   |
| No        | 9        | 37.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 62.5%   |
| No        | 9        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 29.17%  |
| UK          | 1        | 4.17%   |
| Sweden      | 1        | 4.17%   |
| Spain       | 1        | 4.17%   |
| Portugal    | 1        | 4.17%   |
| Poland      | 1        | 4.17%   |
| Netherlands | 1        | 4.17%   |
| Mexico      | 1        | 4.17%   |
| Lebanon     | 1        | 4.17%   |
| Italy       | 1        | 4.17%   |
| India       | 1        | 4.17%   |
| Greece      | 1        | 4.17%   |
| Germany     | 1        | 4.17%   |
| Colombia    | 1        | 4.17%   |
| Canada      | 1        | 4.17%   |
| Brazil      | 1        | 4.17%   |
| Austria     | 1        | 4.17%   |
| Australia   | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Zell am See    | 1        | 4.17%   |
| Wrexham        | 1        | 4.17%   |
| Wells          | 1        | 4.17%   |
| Warsaw         | 1        | 4.17%   |
| Springfield    | 1        | 4.17%   |
| Salt Lake City | 1        | 4.17%   |
| Phoenix        | 1        | 4.17%   |
| Passos         | 1        | 4.17%   |
| Oberursel      | 1        | 4.17%   |
| Monterrey      | 1        | 4.17%   |
| Longview       | 1        | 4.17%   |
| Lisbon         | 1        | 4.17%   |
| Kista          | 1        | 4.17%   |
| Ernakulam      | 1        | 4.17%   |
| Chicago        | 1        | 4.17%   |
| Canovelles     | 1        | 4.17%   |
| Candiac        | 1        | 4.17%   |
| Brisbane       | 1        | 4.17%   |
| Brindisi       | 1        | 4.17%   |
| Bogotá        | 1        | 4.17%   |
| Beirut         | 1        | 4.17%   |
| Athens         | 1        | 4.17%   |
| Almere Stad    | 1        | 4.17%   |
| Aiken          | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 11       | 15     | 21.57%  |
| Seagate                   | 9        | 18     | 17.65%  |
| Samsung Electronics       | 8        | 19     | 15.69%  |
| Toshiba                   | 4        | 6      | 7.84%   |
| Kingston                  | 3        | 4      | 5.88%   |
| Sandisk                   | 2        | 2      | 3.92%   |
| Phison                    | 2        | 2      | 3.92%   |
| HGST                      | 2        | 2      | 3.92%   |
| China                     | 2        | 2      | 3.92%   |
| XPG                       | 1        | 1      | 1.96%   |
| SK Hynix                  | 1        | 1      | 1.96%   |
| PNY                       | 1        | 1      | 1.96%   |
| Micron/Crucial Technology | 1        | 1      | 1.96%   |
| Intel                     | 1        | 2      | 1.96%   |
| Hitachi                   | 1        | 1      | 1.96%   |
| A-DATA Technology         | 1        | 1      | 1.96%   |
| 2-Power                   | 1        | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB       | 2        | 3.08%   |
| Samsung SSD 970 EVO 1TB              | 2        | 3.08%   |
| Kingston SA400S37240G 240GB SSD      | 2        | 3.08%   |
| XPG GAMMIX S50 1TB                   | 1        | 1.54%   |
| WDC WDS512G1X0C-00ENX0 512GB         | 1        | 1.54%   |
| WDC WDS500G3XHC-00SJG0 500GB         | 1        | 1.54%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1        | 1.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 1.54%   |
| WDC WD800JD-00MSA1 80GB              | 1        | 1.54%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1        | 1.54%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1        | 1.54%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1        | 1.54%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 1.54%   |
| WDC WD2500BEVT-60ZCT1 250GB          | 1        | 1.54%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1        | 1.54%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1        | 1.54%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1        | 1.54%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1        | 1.54%   |
| Toshiba MQ04ABF100 1TB               | 1        | 1.54%   |
| Toshiba MQ01ABD100 1TB               | 1        | 1.54%   |
| Toshiba MK4058GSX 400GB              | 1        | 1.54%   |
| Toshiba HDWR160 6TB                  | 1        | 1.54%   |
| Toshiba HDWE160 6TB                  | 1        | 1.54%   |
| Toshiba DT01ACA300 3TB               | 1        | 1.54%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1        | 1.54%   |
| Seagate ST3500418AS 500GB            | 1        | 1.54%   |
| Seagate ST250DM000-1BD141 250GB      | 1        | 1.54%   |
| Seagate ST2000DX001-1CM164 2TB       | 1        | 1.54%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1.54%   |
| Seagate ST2000DM006-2DM164 2TB       | 1        | 1.54%   |
| Seagate ST2000DM001-1ER164 2TB       | 1        | 1.54%   |
| Seagate ST1000VN002-2EY102 1TB       | 1        | 1.54%   |
| Seagate ST1000LM048-2E7172 1TB       | 1        | 1.54%   |
| Seagate ST1000DX001-SSHD-8GB         | 1        | 1.54%   |
| Seagate ST1000DM003-1SB102 1TB       | 1        | 1.54%   |
| Seagate ST10000NE0008-2JM101 10TB    | 1        | 1.54%   |
| Seagate Backup+ Hub BK 8TB           | 1        | 1.54%   |
| SanDisk SDSSDH31024G 1TB             | 1        | 1.54%   |
| Sandisk NVMe SSD Drive 500GB         | 1        | 1.54%   |
| Samsung SSD 980 PRO 2TB              | 1        | 1.54%   |
| Samsung SSD 980 PRO 1TB              | 1        | 1.54%   |
| Samsung SSD 970 EVO Plus 500GB       | 1        | 1.54%   |
| Samsung SSD 960 EVO 250GB            | 1        | 1.54%   |
| Samsung SSD 860 EVO 1TB              | 1        | 1.54%   |
| Samsung SSD 850 EVO 250GB            | 1        | 1.54%   |
| Samsung SSD 840 EVO 120GB            | 1        | 1.54%   |
| Samsung SSD 830 Series 64GB          | 1        | 1.54%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD | 1        | 1.54%   |
| Samsung HD161HJ 160GB                | 1        | 1.54%   |
| PNY CS900 500GB SSD                  | 1        | 1.54%   |
| Phison Sabrent Rocket 4.0 1TB        | 1        | 1.54%   |
| Phison NVMe SSD Drive 240GB          | 1        | 1.54%   |
| Micron/Crucial NVMe SSD Drive 1TB    | 1        | 1.54%   |
| Kingston SUV400S37240G 240GB SSD     | 1        | 1.54%   |
| Intel SSDPEKNW010T8 1TB              | 1        | 1.54%   |
| Hitachi HTS725050A9A364 500GB        | 1        | 1.54%   |
| HGST HTS545050A7E680 500GB           | 1        | 1.54%   |
| HGST HTS541010A9E680 1TB             | 1        | 1.54%   |
| China SATA3 240GB SSD                | 1        | 1.54%   |
| China SATA SSD 120GB                 | 1        | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 11     | 34.62%  |
| Seagate             | 9        | 18     | 34.62%  |
| Toshiba             | 4        | 6      | 15.38%  |
| HGST                | 2        | 2      | 7.69%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| Hitachi             | 1        | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 7      | 30.77%  |
| Kingston            | 3        | 4      | 23.08%  |
| China               | 2        | 2      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| SanDisk             | 1        | 1      | 7.69%   |
| PNY                 | 1        | 1      | 7.69%   |
| 2-Power             | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 39     | 44.19%  |
| NVMe | 13       | 23     | 30.23%  |
| SSD  | 11       | 17     | 25.58%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 55     | 61.11%  |
| NVMe | 13       | 23     | 36.11%  |
| SAS  | 1        | 1      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 14       | 25     | 40%     |
| 0.51-1.0   | 13       | 19     | 37.14%  |
| 1.01-2.0   | 4        | 7      | 11.43%  |
| 4.01-10.0  | 3        | 4      | 8.57%   |
| 2.01-3.0   | 1        | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 11       | 40.74%  |
| 501-1000       | 5        | 18.52%  |
| 1001-2000      | 4        | 14.81%  |
| 251-500        | 2        | 7.41%   |
| 101-250        | 2        | 7.41%   |
| 2001-3000      | 1        | 3.7%    |
| 1-20           | 1        | 3.7%    |
| 51-100         | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 9        | 33.33%  |
| 1-20      | 6        | 22.22%  |
| 51-100    | 5        | 18.52%  |
| 251-500   | 2        | 7.41%   |
| 1001-2000 | 2        | 7.41%   |
| 501-1000  | 2        | 7.41%   |
| 2001-3000 | 1        | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 1      | 12.5%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 2      | 12.5%   |
| Toshiba MQ01ABD100 1TB           | 1        | 1      | 12.5%   |
| Toshiba MK4058GSX 400GB          | 1        | 1      | 12.5%   |
| Seagate ST2000DM006-2DM164 2TB   | 1        | 1      | 12.5%   |
| Kingston SUV400S37240G 240GB SSD | 1        | 1      | 12.5%   |
| Hitachi HTS725050A9A364 500GB    | 1        | 1      | 12.5%   |
| China SATA3 240GB SSD            | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 2        | 3      | 28.57%  |
| Toshiba  | 1        | 2      | 14.29%  |
| Seagate  | 1        | 1      | 14.29%  |
| Kingston | 1        | 1      | 14.29%  |
| Hitachi  | 1        | 1      | 14.29%  |
| China    | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 3      | 40%     |
| Toshiba | 1        | 2      | 20%     |
| Seagate | 1        | 1      | 20%     |
| Hitachi | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 7      | 71.43%  |
| SSD  | 2        | 2      | 28.57%  |

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
| Works    | 21       | 59     | 65.63%  |
| Malfunc  | 7        | 9      | 21.88%  |
| Detected | 4        | 11     | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 17       | 43.59%  |
| AMD                       | 8        | 20.51%  |
| Sandisk                   | 4        | 10.26%  |
| Samsung Electronics       | 4        | 10.26%  |
| Phison Electronics        | 2        | 5.13%   |
| SK Hynix                  | 1        | 2.56%   |
| Realtek Semiconductor     | 1        | 2.56%   |
| Micron/Crucial Technology | 1        | 2.56%   |
| ADATA Technology          | 1        | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 15.91%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 6.82%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 6.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 6.82%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2        | 4.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 4.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 4.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 4.55%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1        | 2.27%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1        | 2.27%   |
| Sandisk WD Black NVMe SSD                                                      | 1        | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.27%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 2.27%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 2.27%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.27%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 2.27%   |
| Intel SSD 660P Series                                                          | 1        | 2.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.27%   |
| AMD FCH SATA Controller D                                                      | 1        | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.27%   |
| ADATA Non-Volatile memory controller                                           | 1        | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 57.89%  |
| NVMe | 13       | 34.21%  |
| RAID | 3        | 7.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 66.67%  |
| AMD    | 8        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| AMD Ryzen 5 3600X 6-Core Processor         | 3        | 12.5%   |
| Intel Genuine CPU 0000 @ 2.10GHz           | 1        | 4.17%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 1        | 4.17%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 1        | 4.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 1        | 4.17%   |
| Intel Core i7 CPU 870 @ 2.93GHz            | 1        | 4.17%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 1        | 4.17%   |
| Intel Core i5-9400F CPU @ 2.90GHz          | 1        | 4.17%   |
| Intel Core i5-9400 CPU @ 2.90GHz           | 1        | 4.17%   |
| Intel Core i5-6600 CPU @ 3.30GHz           | 1        | 4.17%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 1        | 4.17%   |
| Intel Core i5-4670 CPU @ 3.40GHz           | 1        | 4.17%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 1        | 4.17%   |
| Intel Core i3-8100 CPU @ 3.60GHz           | 1        | 4.17%   |
| Intel Core i3-2120 CPU @ 3.30GHz           | 1        | 4.17%   |
| Intel Core i3 CPU 540 @ 3.07GHz            | 1        | 4.17%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz      | 1        | 4.17%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 1        | 4.17%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 4.17%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 4.17%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 1        | 4.17%   |
| AMD Athlon 200GE with Radeon Vega Graphics | 1        | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 7        | 29.17%  |
| AMD Ryzen 5       | 5        | 20.83%  |
| Intel Core i7     | 4        | 16.67%  |
| Intel Core i3     | 3        | 12.5%   |
| Intel Genuine     | 1        | 4.17%   |
| Intel Core 2 Quad | 1        | 4.17%   |
| AMD Ryzen 9       | 1        | 4.17%   |
| AMD Ryzen 7       | 1        | 4.17%   |
| AMD Athlon        | 1        | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 9        | 37.5%   |
| 4      | 9        | 37.5%   |
| 2      | 3        | 12.5%   |
| 8      | 2        | 8.33%   |
| 12     | 1        | 4.17%   |

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
| 2      | 15       | 62.5%   |
| 1      | 9        | 37.5%   |

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
| Unknown    | 4        | 16.67%  |
| 0x906ea    | 3        | 12.5%   |
| 0x506e3    | 3        | 12.5%   |
| 0x08701021 | 3        | 12.5%   |
| 0x306c3    | 2        | 8.33%   |
| 0x0a201016 | 2        | 8.33%   |
| 0x906ed    | 1        | 4.17%   |
| 0x906eb    | 1        | 4.17%   |
| 0x906e9    | 1        | 4.17%   |
| 0x20655    | 1        | 4.17%   |
| 0x1067a    | 1        | 4.17%   |
| 0x08701013 | 1        | 4.17%   |
| 0x0810100b | 1        | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 7        | 29.17%  |
| Zen 2       | 4        | 16.67%  |
| Skylake     | 3        | 12.5%   |
| Zen 3       | 2        | 8.33%   |
| Haswell     | 2        | 8.33%   |
| Zen+        | 1        | 4.17%   |
| Zen         | 1        | 4.17%   |
| Westmere    | 1        | 4.17%   |
| SandyBridge | 1        | 4.17%   |
| Penryn      | 1        | 4.17%   |
| Nehalem     | 1        | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 48%     |
| AMD    | 8        | 32%     |
| Intel  | 5        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 12%     |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 8%      |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 8%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 8%      |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 4%      |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 4%      |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 4%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 4%      |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 4%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 4%      |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 4%      |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4%      |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 4%      |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 4%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 4%      |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 4%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 12       | 50%     |
| 1 x AMD    | 8        | 33.33%  |
| 1 x Intel  | 4        | 16.67%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 50%     |
| Proprietary | 10       | 41.67%  |
| Unknown     | 2        | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 37.5%   |
| 7.01-8.0   | 5        | 20.83%  |
| 1.01-2.0   | 5        | 20.83%  |
| 5.01-6.0   | 2        | 8.33%   |
| 8.01-16.0  | 2        | 8.33%   |
| 3.01-4.0   | 1        | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 6        | 23.08%  |
| Goldstar             | 3        | 11.54%  |
| Ancor Communications | 3        | 11.54%  |
| Hewlett-Packard      | 2        | 7.69%   |
| AOC                  | 2        | 7.69%   |
| Acer                 | 2        | 7.69%   |
| Kogan                | 1        | 3.85%   |
| KOC                  | 1        | 3.85%   |
| Iiyama               | 1        | 3.85%   |
| Idek Iiyama          | 1        | 3.85%   |
| Hitachi              | 1        | 3.85%   |
| Gigabyte Technology  | 1        | 3.85%   |
| Dell                 | 1        | 3.85%   |
| ASUSTek Computer     | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch  | 1        | 3.7%    |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch  | 1        | 3.7%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                      | 1        | 3.7%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 1        | 3.7%    |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch              | 1        | 3.7%    |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch               | 1        | 3.7%    |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 1        | 3.7%    |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                             | 1        | 3.7%    |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch               | 1        | 3.7%    |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch           | 1        | 3.7%    |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 3.7%    |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 1        | 3.7%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 1        | 3.7%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 3.7%    |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1        | 3.7%    |
| Dell U3219Q DELA124 3840x2160 697x392mm 31.5-inch                     | 1        | 3.7%    |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch        | 1        | 3.7%    |
| AOC 27V2G5 AOC2702 1920x1080 600x340mm 27.2-inch                      | 1        | 3.7%    |
| AOC 2460G5 AOC246A 1920x1080 530x300mm 24.0-inch                      | 1        | 3.7%    |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1        | 3.7%    |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 800x340mm 34.2-inch | 1        | 3.7%    |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 600x340mm 27.2-inch | 1        | 3.7%    |
| Acer X233H ACR0093 1920x1080 510x287mm 23.0-inch                      | 1        | 3.7%    |
| Acer S240HL ACR0289 1920x1080 531x299mm 24.0-inch                     | 1        | 3.7%    |
| Acer G215H ACR0109 1920x1080 480x270mm 21.7-inch                      | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 9        | 37.5%   |
| 2560x1440 (QHD)  | 5        | 20.83%  |
| 3840x2160 (4K)   | 4        | 16.67%  |
| 3440x1440        | 3        | 12.5%   |
| 3840x1080        | 1        | 4.17%   |
| 1920x540         | 1        | 4.17%   |
| 1280x1024 (SXGA) | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 23.08%  |
| 34      | 3        | 11.54%  |
| 24      | 3        | 11.54%  |
| 23      | 3        | 11.54%  |
| 21      | 3        | 11.54%  |
| 31      | 2        | 7.69%   |
| Unknown | 2        | 7.69%   |
| 84      | 1        | 3.85%   |
| 54      | 1        | 3.85%   |
| 48      | 1        | 3.85%   |
| 18      | 1        | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 44%     |
| 701-800     | 3        | 12%     |
| 401-500     | 3        | 12%     |
| 601-700     | 2        | 8%      |
| 1001-1500   | 2        | 8%      |
| Unknown     | 2        | 8%      |
| 351-400     | 1        | 4%      |
| 1501-2000   | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 72.73%  |
| 21/9    | 3        | 13.64%  |
| 5/4     | 1        | 4.55%   |
| 32/9    | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 32%     |
| 301-350        | 6        | 24%     |
| 351-500        | 5        | 20%     |
| More than 1000 | 2        | 8%      |
| Unknown        | 2        | 8%      |
| 151-200        | 1        | 4%      |
| 501-1000       | 1        | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 45.45%  |
| 101-120 | 7        | 31.82%  |
| Unknown | 2        | 9.09%   |
| 1-50    | 1        | 4.55%   |
| 161-240 | 1        | 4.55%   |
| 121-160 | 1        | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 68%     |
| 2     | 6        | 24%     |
| 0     | 2        | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 42.86%  |
| Intel                 | 13       | 37.14%  |
| Broadcom              | 2        | 5.71%   |
| TP-Link               | 1        | 2.86%   |
| Qualcomm Atheros      | 1        | 2.86%   |
| Qualcomm              | 1        | 2.86%   |
| NetGear               | 1        | 2.86%   |
| Microsoft             | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 11       | 25.58%  |
| Intel Wi-Fi 6 AX200                                                       | 4        | 9.3%    |
| Intel Ethernet Connection (2) I219-V                                      | 4        | 9.3%    |
| Realtek RTL8125 2.5GbE Controller                                         | 3        | 6.98%   |
| Intel I211 Gigabit Network Connection                                     | 3        | 6.98%   |
| Intel Ethernet Connection (7) I219-V                                      | 2        | 4.65%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1        | 2.33%   |
| Qualcomm Redmi Note 9S                                                    | 1        | 2.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1        | 2.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1        | 2.33%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 2.33%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 2.33%   |
| Intel Wireless-AC 9260                                                    | 1        | 2.33%   |
| Intel Ethernet Connection I217-LM                                         | 1        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 2.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 1        | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1        | 2.33%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 43.75%  |
| Realtek Semiconductor | 3        | 18.75%  |
| Broadcom              | 2        | 12.5%   |
| TP-Link               | 1        | 6.25%   |
| Qualcomm Atheros      | 1        | 6.25%   |
| NetGear               | 1        | 6.25%   |
| Microsoft             | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 4        | 25%     |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 6.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 6.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1        | 6.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1        | 6.25%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 6.25%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 6.25%   |
| Intel Wireless-AC 9260                                                    | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1        | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 6.25%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1        | 6.25%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 51.85%  |
| Intel                 | 10       | 37.04%  |
| Qualcomm Atheros      | 1        | 3.7%    |
| Qualcomm              | 1        | 3.7%    |
| Broadcom              | 1        | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11       | 40.74%  |
| Intel Ethernet Connection (2) I219-V                              | 4        | 14.81%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 11.11%  |
| Intel I211 Gigabit Network Connection                             | 3        | 11.11%  |
| Intel Ethernet Connection (7) I219-V                              | 2        | 7.41%   |
| Qualcomm Redmi Note 9S                                            | 1        | 3.7%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 61.54%  |
| WiFi     | 15       | 38.46%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 70.83%  |
| WiFi     | 7        | 29.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 50%     |
| 2     | 10       | 41.67%  |
| 3     | 2        | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 76%     |
| Yes  | 6        | 24%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 46.67%  |
| Realtek Semiconductor   | 2        | 13.33%  |
| Cambridge Silicon Radio | 2        | 13.33%  |
| Broadcom                | 2        | 13.33%  |
| ASUSTek Computer        | 2        | 13.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 4        | 26.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 13.33%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 6.67%   |
| Realtek Bluetooth Radio                             | 1        | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 6.67%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 6.67%   |
| ASUS Bluetooth Radio                                | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 16       | 32%     |
| Nvidia                 | 12       | 24%     |
| AMD                    | 10       | 20%     |
| Razer USA              | 2        | 4%      |
| Corsair                | 2        | 4%      |
| C-Media Electronics    | 2        | 4%      |
| Tenx Technology        | 1        | 2%      |
| Plantronics            | 1        | 2%      |
| Logitech               | 1        | 2%      |
| Kingston Technology    | 1        | 2%      |
| Hewlett-Packard        | 1        | 2%      |
| Generalplus Technology | 1        | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 8.77%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 7.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 5.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 5.26%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 5.26%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 3.51%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 3.51%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.75%   |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1        | 1.75%   |
| Razer USA Razer Kraken X USB                                               | 1        | 1.75%   |
| Plantronics C320-M                                                         | 1        | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.75%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.75%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.75%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.75%   |
| Logitech G633 Gaming Headset                                               | 1        | 1.75%   |
| Kingston Technology HyperX Cloud Flight Wireless                           | 1        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.75%   |
| Hewlett-Packard E240C                                                      | 1        | 1.75%   |
| Generalplus Technology Usb Audio Device                                    | 1        | 1.75%   |
| Corsair Slipstream Multi-Device Receiver                                   | 1        | 1.75%   |
| Corsair HS60 PRO Surround USB Sound Adapter                                | 1        | 1.75%   |
| C-Media Electronics USB Modi Device                                        | 1        | 1.75%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.75%   |
| C-Media Electronics Blue Snowball                                          | 1        | 1.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.75%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 5        | 20.83%  |
| Corsair             | 5        | 20.83%  |
| Unknown             | 3        | 12.5%   |
| SK Hynix            | 2        | 8.33%   |
| Samsung Electronics | 2        | 8.33%   |
| Crucial             | 2        | 8.33%   |
| Unifosa             | 1        | 4.17%   |
| Team                | 1        | 4.17%   |
| PNY                 | 1        | 4.17%   |
| Micron Technology   | 1        | 4.17%   |
| Kingston            | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 3.85%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 3.85%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s        | 1        | 3.85%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s       | 1        | 3.85%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 3.85%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s     | 1        | 3.85%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 3.85%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 3.85%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s      | 1        | 3.85%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s      | 1        | 3.85%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s      | 1        | 3.85%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s      | 1        | 3.85%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s     | 1        | 3.85%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s   | 1        | 3.85%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 3.85%   |
| G.Skill RAM F4-3200C16-8GTZKW 8192MB DIMM DDR4 3200MT/s  | 1        | 3.85%   |
| G.Skill RAM F4-3200C16-8GTZKO 8GB DIMM DDR4 3200MT/s     | 1        | 3.85%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4096MB DIMM DDR4 2400MT/s | 1        | 3.85%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s    | 1        | 3.85%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s     | 1        | 3.85%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 1        | 3.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 3.85%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s    | 1        | 3.85%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s    | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 15       | 75%     |
| DDR3 | 4        | 20%     |
| DDR2 | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 19       | 95%     |
| SODIMM | 1        | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 45.45%  |
| 16384 | 5        | 22.73%  |
| 4096  | 5        | 22.73%  |
| 2048  | 2        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 2        | 9.52%   |
| 3200  | 2        | 9.52%   |
| 2400  | 2        | 9.52%   |
| 1600  | 2        | 9.52%   |
| 4400  | 1        | 4.76%   |
| 4133  | 1        | 4.76%   |
| 3800  | 1        | 4.76%   |
| 3400  | 1        | 4.76%   |
| 3067  | 1        | 4.76%   |
| 2933  | 1        | 4.76%   |
| 2747  | 1        | 4.76%   |
| 2666  | 1        | 4.76%   |
| 2176  | 1        | 4.76%   |
| 2133  | 1        | 4.76%   |
| 1450  | 1        | 4.76%   |
| 1333  | 1        | 4.76%   |
| 800   | 1        | 4.76%   |

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 1        | 25%     |
| Generalplus Technology                 | 1        | 25%     |
| Chicony Electronics                    | 1        | 25%     |
| Cheng Uei Precision Industry (Foxlink) | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech Webcam C600                                                 | 1        | 25%     |
| Generalplus CAMERA - UVC                                             | 1        | 25%     |
| Chicony HP High Definition 1MP Webcam                                | 1        | 25%     |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 25%     |

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
| Graphics card | 2        | 40%     |
| Bluetooth     | 2        | 40%     |
| Net/wireless  | 1        | 20%     |

