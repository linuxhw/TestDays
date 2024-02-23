TUXEDO OS - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 2AA7 H                      | [4dbc7b0fe9](https://linux-hardware.org/?probe=4dbc7b0fe9) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c766c9daaf](https://linux-hardware.org/?probe=c766c9daaf) | Jan 22, 2024 |
| BESSTAR Te... | HM80                        | [3d9f1350b3](https://linux-hardware.org/?probe=3d9f1350b3) | Jan 14, 2024 |
| ASRock        | H170M Pro4                  | [27e24a6ef3](https://linux-hardware.org/?probe=27e24a6ef3) | Dec 30, 2023 |
| ECS           | GeForce 8000 series         | [d436bb4acc](https://linux-hardware.org/?probe=d436bb4acc) | Dec 19, 2023 |
| MSI           | PRO H410M-B                 | [0729c86d23](https://linux-hardware.org/?probe=0729c86d23) | Dec 15, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [7e201ea559](https://linux-hardware.org/?probe=7e201ea559) | Dec 11, 2023 |
| ASUSTek       | PRIME A320M-K               | [5f06f30bd3](https://linux-hardware.org/?probe=5f06f30bd3) | Nov 09, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [414894f4aa](https://linux-hardware.org/?probe=414894f4aa) | Nov 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [3fb2d2a6f0](https://linux-hardware.org/?probe=3fb2d2a6f0) | Nov 06, 2023 |
| MSI           | X570-A PRO                  | [78df342ad3](https://linux-hardware.org/?probe=78df342ad3) | Oct 21, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [5573fff3e6](https://linux-hardware.org/?probe=5573fff3e6) | Oct 17, 2023 |
| ASRock        | A520M-HVS                   | [0a29d5f7f6](https://linux-hardware.org/?probe=0a29d5f7f6) | Sep 22, 2023 |
| ASRock        | A520M-HVS                   | [2a7bf627ba](https://linux-hardware.org/?probe=2a7bf627ba) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [6d7c6c42f5](https://linux-hardware.org/?probe=6d7c6c42f5) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [fe64bd3017](https://linux-hardware.org/?probe=fe64bd3017) | Sep 13, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [376e22722b](https://linux-hardware.org/?probe=376e22722b) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [388f380783](https://linux-hardware.org/?probe=388f380783) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [679cf99998](https://linux-hardware.org/?probe=679cf99998) | Aug 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [cd3074537b](https://linux-hardware.org/?probe=cd3074537b) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [01846991de](https://linux-hardware.org/?probe=01846991de) | Aug 04, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [fde0e0e94f](https://linux-hardware.org/?probe=fde0e0e94f) | Jul 29, 2023 |
| ASRock        | H170M Pro4                  | [818c9bc358](https://linux-hardware.org/?probe=818c9bc358) | Jun 14, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Gigabyte      | H81M-HD3                    | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| Dell          | 051FJ8 A02                  | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [886aa04456](https://linux-hardware.org/?probe=886aa04456) | Mar 07, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [9088ef4d11](https://linux-hardware.org/?probe=9088ef4d11) | Mar 06, 2023 |
| ASUSTek       | P8H61-M LX                  | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| ASRock        | Z270M-ITX/ac                | [4f507f4e5a](https://linux-hardware.org/?probe=4f507f4e5a) | Feb 20, 2023 |
| ASUSTek       | PRIME H410M-K               | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| HP            | 2B34                        | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| HP            | 8906 SMVB                   | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| TUXEDO OS 22.04 | 28       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| TUXEDO OS | 28       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 6.2.0-10018-tuxedo  | 4        | 13.79%  |
| 6.1.0-1009-tuxedo   | 4        | 13.79%  |
| 6.5.0-10013-tuxedo  | 3        | 10.34%  |
| 6.5.0-10010-tuxedo  | 3        | 10.34%  |
| 6.2.0-10007-tuxedo  | 3        | 10.34%  |
| 5.15.0-10058-tuxedo | 3        | 10.34%  |
| 6.5.0-10006-tuxedo  | 2        | 6.9%    |
| 6.2.0-10027-tuxedo  | 2        | 6.9%    |
| 6.2.0-10022-tuxedo  | 2        | 6.9%    |
| 6.5.0-10022-tuxedo  | 1        | 3.45%   |
| 5.15.0-10057-tuxedo | 1        | 3.45%   |
| 5.15.0-10056-tuxedo | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 11       | 37.93%  |
| 6.5.0   | 9        | 31.03%  |
| 5.15.0  | 5        | 17.24%  |
| 6.1.0   | 4        | 13.79%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 11       | 37.93%  |
| 6.5     | 9        | 31.03%  |
| 5.15    | 5        | 17.24%  |
| 6.1     | 4        | 13.79%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 28       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 27       | 96.43%  |
| X-Cinnamon | 1        | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 25       | 89.29%  |
| Wayland | 3        | 10.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 89.29%  |
| SDDM    | 3        | 10.71%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| de_DE | 10       | 35.71%  |
| en_US | 7        | 25%     |
| it_IT | 2        | 7.14%   |
| en_ZA | 2        | 7.14%   |
| pt_PT | 1        | 3.57%   |
| pl_PL | 1        | 3.57%   |
| en_IN | 1        | 3.57%   |
| en_GB | 1        | 3.57%   |
| en_AG | 1        | 3.57%   |
| de_CH | 1        | 3.57%   |
| de_AT | 1        | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 25       | 89.29%  |
| EFI  | 3        | 10.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 24       | 82.76%  |
| Btrfs | 3        | 10.34%  |
| Xfs   | 2        | 6.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 89.29%  |
| GPT     | 3        | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 96.43%  |
| Yes       | 1        | 3.57%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 89.29%  |
| Yes       | 3        | 10.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 35.71%  |
| MSI                 | 6        | 21.43%  |
| Hewlett-Packard     | 3        | 10.71%  |
| ASRock              | 3        | 10.71%  |
| Gigabyte Technology | 2        | 7.14%   |
| Lenovo              | 1        | 3.57%   |
| ECS                 | 1        | 3.57%   |
| Dell                | 1        | 3.57%   |
| BESSTAR Tech        | 1        | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS PRIME B450-PLUS                 | 3        | 10.71%  |
| MSI MS-7D17                          | 2        | 7.14%   |
| ASUS ROG STRIX B550-I GAMING         | 2        | 7.14%   |
| MSI MS-7D82                          | 1        | 3.57%   |
| MSI MS-7D25                          | 1        | 3.57%   |
| MSI MS-7C37                          | 1        | 3.57%   |
| MSI MS-7B17                          | 1        | 3.57%   |
| Lenovo ThinkCentre M700 10GSS05X48   | 1        | 3.57%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 3.57%   |
| HP F01                               | 1        | 3.57%   |
| HP 280 G1 MT                         | 1        | 3.57%   |
| Gigabyte H81M-HD3                    | 1        | 3.57%   |
| Gigabyte B560M AORUS PRO AX          | 1        | 3.57%   |
| ECS GeForce 8000 series              | 1        | 3.57%   |
| Dell OptiPlex 9010                   | 1        | 3.57%   |
| BESSTAR Tech HM80                    | 1        | 3.57%   |
| ASUS TUF Gaming H470-PRO             | 1        | 3.57%   |
| ASUS ROG STRIX Z590-A GAMING WIFI    | 1        | 3.57%   |
| ASUS PRIME H410M-K                   | 1        | 3.57%   |
| ASUS PRIME A320M-K                   | 1        | 3.57%   |
| ASUS P8H61-M LX                      | 1        | 3.57%   |
| ASRock Z270M-ITX/ac                  | 1        | 3.57%   |
| ASRock H170M Pro4                    | 1        | 3.57%   |
| ASRock A520M-HVS                     | 1        | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 5        | 17.86%  |
| ASUS ROG           | 3        | 10.71%  |
| MSI MS-7D17        | 2        | 7.14%   |
| MSI MS-7D82        | 1        | 3.57%   |
| MSI MS-7D25        | 1        | 3.57%   |
| MSI MS-7C37        | 1        | 3.57%   |
| MSI MS-7B17        | 1        | 3.57%   |
| Lenovo ThinkCentre | 1        | 3.57%   |
| HP Pavilion        | 1        | 3.57%   |
| HP F01             | 1        | 3.57%   |
| HP 280             | 1        | 3.57%   |
| Gigabyte H81M-HD3  | 1        | 3.57%   |
| Gigabyte B560M     | 1        | 3.57%   |
| ECS GeForce        | 1        | 3.57%   |
| Dell OptiPlex      | 1        | 3.57%   |
| BESSTAR Tech HM80  | 1        | 3.57%   |
| ASUS TUF           | 1        | 3.57%   |
| ASUS P8H61-M       | 1        | 3.57%   |
| ASRock Z270M-ITX   | 1        | 3.57%   |
| ASRock H170M       | 1        | 3.57%   |
| ASRock A520M-HVS   | 1        | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 8        | 28.57%  |
| 2020 | 5        | 17.86%  |
| 2018 | 4        | 14.29%  |
| 2013 | 2        | 7.14%   |
| 2022 | 1        | 3.57%   |
| 2019 | 1        | 3.57%   |
| 2017 | 1        | 3.57%   |
| 2016 | 1        | 3.57%   |
| 2015 | 1        | 3.57%   |
| 2014 | 1        | 3.57%   |
| 2011 | 1        | 3.57%   |
| 2010 | 1        | 3.57%   |
| 2008 | 1        | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 28       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 28       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 8        | 28.57%  |
| 16.01-24.0  | 8        | 28.57%  |
| 3.01-4.0    | 4        | 14.29%  |
| 4.01-8.0    | 3        | 10.71%  |
| 8.01-16.0   | 3        | 10.71%  |
| 24.01-32.0  | 1        | 3.57%   |
| 64.01-256.0 | 1        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 9        | 30%     |
| 4.01-8.0  | 7        | 23.33%  |
| 1.01-2.0  | 7        | 23.33%  |
| 3.01-4.0  | 4        | 13.33%  |
| 8.01-16.0 | 3        | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 35.71%  |
| 4      | 7        | 25%     |
| 1      | 4        | 14.29%  |
| 5      | 3        | 10.71%  |
| 3      | 3        | 10.71%  |
| 6      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 67.86%  |
| Yes       | 9        | 32.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 96.43%  |
| No        | 1        | 3.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 57.14%  |
| No        | 12       | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 51.72%  |
| Yes       | 14       | 48.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 11       | 39.29%  |
| Italy        | 3        | 10.71%  |
| USA          | 2        | 7.14%   |
| South Africa | 2        | 7.14%   |
| UK           | 1        | 3.57%   |
| Switzerland  | 1        | 3.57%   |
| Romania      | 1        | 3.57%   |
| Portugal     | 1        | 3.57%   |
| Poland       | 1        | 3.57%   |
| Netherlands  | 1        | 3.57%   |
| India        | 1        | 3.57%   |
| Egypt        | 1        | 3.57%   |
| Austria      | 1        | 3.57%   |
| Aruba        | 1        | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Hürth                    | 2        | 6.9%    |
| Zurich                    | 1        | 3.45%   |
| Zalău                    | 1        | 3.45%   |
| Vienna                    | 1        | 3.45%   |
| Ulm                       | 1        | 3.45%   |
| Stimpfach                 | 1        | 3.45%   |
| Quarteira                 | 1        | 3.45%   |
| Peitz                     | 1        | 3.45%   |
| Oranjestad                | 1        | 3.45%   |
| Offenbach                 | 1        | 3.45%   |
| Milan                     | 1        | 3.45%   |
| Middlesbrough             | 1        | 3.45%   |
| Lublin                    | 1        | 3.45%   |
| Leipzig                   | 1        | 3.45%   |
| Landau                    | 1        | 3.45%   |
| Johannesburg              | 1        | 3.45%   |
| Indore                    | 1        | 3.45%   |
| Frankfurt am Main         | 1        | 3.45%   |
| Florence                  | 1        | 3.45%   |
| Erding                    | 1        | 3.45%   |
| Eberswalde                | 1        | 3.45%   |
| Camarillo                 | 1        | 3.45%   |
| Cairo                     | 1        | 3.45%   |
| Cagliari                  | 1        | 3.45%   |
| Bullhead City             | 1        | 3.45%   |
| Bloemfontein              | 1        | 3.45%   |
| Bad Neustadt an der Saale | 1        | 3.45%   |
| Amsterdam                 | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 14       | 22     | 21.54%  |
| Seagate                     | 9        | 14     | 13.85%  |
| WDC                         | 5        | 6      | 7.69%   |
| Sandisk                     | 5        | 7      | 7.69%   |
| Kingston                    | 3        | 3      | 4.62%   |
| SK hynix                    | 2        | 3      | 3.08%   |
| Micron/Crucial Technology   | 2        | 4      | 3.08%   |
| Hitachi                     | 2        | 3      | 3.08%   |
| GOODRAM                     | 2        | 2      | 3.08%   |
| Crucial                     | 2        | 2      | 3.08%   |
| SPCC                        | 1        | 1      | 1.54%   |
| Silicon Motion              | 1        | 2      | 1.54%   |
| Phison                      | 1        | 1      | 1.54%   |
| Netac                       | 1        | 1      | 1.54%   |
| Lite-On Technology          | 1        | 1      | 1.54%   |
| Kingston Technology Company | 1        | 1      | 1.54%   |
| KingFast                    | 1        | 1      | 1.54%   |
| Intenso                     | 1        | 1      | 1.54%   |
| HS-SSD-E100                 | 1        | 1      | 1.54%   |
| HS-SSD-E                    | 1        | 1      | 1.54%   |
| Hikvision                   | 1        | 2      | 1.54%   |
| HGST HTS                    | 1        | 1      | 1.54%   |
| HGST                        | 1        | 2      | 1.54%   |
| Fanxiang                    | 1        | 1      | 1.54%   |
| China                       | 1        | 1      | 1.54%   |
| ASMT                        | 1        | 1      | 1.54%   |
| Apacer                      | 1        | 1      | 1.54%   |
| AMD                         | 1        | 2      | 1.54%   |
| A-DATA Technology           | 1        | 2      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 980 500GB                               | 3        | 3.85%   |
| Seagate ST3500418AS 500GB                           | 2        | 2.56%   |
| Seagate ST1000VT001-1RE172 1TB                      | 2        | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2        | 2.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 2        | 2.56%   |
| SanDisk SSD PLUS 120GB                              | 2        | 2.56%   |
| Samsung SSD 860 EVO 250GB                           | 2        | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 2        | 2.56%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2        | 2.56%   |
| Hitachi HCS545050GLA380 500GB                       | 2        | 2.56%   |
| WDC WD80EAZZ-00BKLB0 8TB                            | 1        | 1.28%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 1.28%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 1.28%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1        | 1.28%   |
| WDC WD10JPVX-11JC3T0 1TB                            | 1        | 1.28%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1        | 1.28%   |
| SPCC Solid State Disk 512GB                         | 1        | 1.28%   |
| SK hynix SHPP41-2000GM 2TB                          | 1        | 1.28%   |
| SK hynix SHGP31-1000GM-2 1TB                        | 1        | 1.28%   |
| SK hynix SHGP31-1000GM 1TB                          | 1        | 1.28%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 480GB | 1        | 1.28%   |
| Seagate ST500DM002-1BD142 500GB                     | 1        | 1.28%   |
| Seagate ST3500413AS 500GB                           | 1        | 1.28%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1        | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1        | 1.28%   |
| Seagate ST1000DX001-1NS162-SSHD 1TB                 | 1        | 1.28%   |
| Seagate ST10000NM001G-2MW103 10TB                   | 1        | 1.28%   |
| Sandisk WD_BLACK SN770 2TB                          | 1        | 1.28%   |
| Sandisk WD Black SN850 1024GB                       | 1        | 1.28%   |
| Samsung SSD 990 PRO 2TB                             | 1        | 1.28%   |
| Samsung SSD 980 1TB                                 | 1        | 1.28%   |
| Samsung SSD 870 EVO 2TB                             | 1        | 1.28%   |
| Samsung SSD 860 QVO 1TB                             | 1        | 1.28%   |
| Samsung SSD 860 PRO 1TB                             | 1        | 1.28%   |
| Samsung SSD 860 EVO 500GB                           | 1        | 1.28%   |
| Samsung SSD 860 EVO 1TB                             | 1        | 1.28%   |
| Samsung SSD 850 PRO 128GB                           | 1        | 1.28%   |
| Samsung SSD 850 EVO 500GB                           | 1        | 1.28%   |
| Samsung SSD 850 EVO 1TB                             | 1        | 1.28%   |
| Samsung HD321KJ 320GB                               | 1        | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 14     | 45%     |
| WDC                 | 5        | 6      | 25%     |
| Samsung Electronics | 2        | 2      | 10%     |
| Hitachi             | 2        | 3      | 10%     |
| HGST HTS            | 1        | 1      | 5%      |
| HGST                | 1        | 2      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 10     | 34.78%  |
| SanDisk             | 2        | 3      | 8.7%    |
| Kingston            | 2        | 2      | 8.7%    |
| GOODRAM             | 2        | 2      | 8.7%    |
| Crucial             | 2        | 2      | 8.7%    |
| SPCC                | 1        | 1      | 4.35%   |
| Netac               | 1        | 1      | 4.35%   |
| Intenso             | 1        | 1      | 4.35%   |
| China               | 1        | 1      | 4.35%   |
| ASMT                | 1        | 1      | 4.35%   |
| Apacer              | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 2      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 18       | 32     | 32.73%  |
| SSD     | 17       | 27     | 30.91%  |
| HDD     | 17       | 28     | 30.91%  |
| Unknown | 3        | 3      | 5.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 55     | 54.55%  |
| NVMe | 18       | 32     | 40.91%  |
| SAS  | 2        | 3      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 15       | 18     | 39.47%  |
| 0.01-0.5   | 15       | 28     | 39.47%  |
| 1.01-2.0   | 6        | 7      | 15.79%  |
| 4.01-10.0  | 2        | 2      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 9        | 30%     |
| 101-250        | 5        | 16.67%  |
| 1001-2000      | 5        | 16.67%  |
| 251-500        | 4        | 13.33%  |
| More than 3000 | 2        | 6.67%   |
| 21-50          | 2        | 6.67%   |
| 2001-3000      | 2        | 6.67%   |
| 51-100         | 1        | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9        | 31.03%  |
| 21-50          | 7        | 24.14%  |
| 501-1000       | 4        | 13.79%  |
| 251-500        | 2        | 6.9%    |
| 101-250        | 2        | 6.9%    |
| 51-100         | 2        | 6.9%    |
| More than 3000 | 1        | 3.45%   |
| 2001-3000      | 1        | 3.45%   |
| 1001-2000      | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 25       | 79     | 86.21%  |
| Works    | 4        | 11     | 13.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 17       | 34.69%  |
| AMD                         | 10       | 20.41%  |
| Samsung Electronics         | 7        | 14.29%  |
| SanDisk                     | 3        | 6.12%   |
| SK hynix                    | 2        | 4.08%   |
| Micron/Crucial Technology   | 2        | 4.08%   |
| Kingston Technology Company | 2        | 4.08%   |
| Silicon Motion              | 1        | 2.04%   |
| Phison Electronics          | 1        | 2.04%   |
| Nvidia                      | 1        | 2.04%   |
| Lite-On Technology          | 1        | 2.04%   |
| INNOGRIT                    | 1        | 2.04%   |
| ASMedia Technology          | 1        | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 11.67%  |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 8.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 6.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 6.67%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 5%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2        | 3.33%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 3.33%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.33%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 1.67%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.67%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 1.67%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 1        | 1.67%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.67%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 1.67%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 1.67%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 1.67%   |
| Lite-On M9PeG, M9PeGN, M9PeY NVMe SSD                                                   | 1        | 1.67%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 1        | 1.67%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 1        | 1.67%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.67%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.67%   |
| INNOGRIT NVMe SSD Controller IG5236                                                     | 1        | 1.67%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 1        | 1.67%   |
| AMD FCH SATA Controller [RAID Bottom]                                                   | 1        | 1.67%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 55.32%  |
| NVMe | 18       | 38.3%   |
| IDE  | 2        | 4.26%   |
| RAID | 1        | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 60.71%  |
| AMD    | 11       | 39.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz         | 2        | 7.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 2        | 7.14%   |
| Intel Pentium CPU G3420 @ 3.20GHz        | 1        | 3.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz        | 1        | 3.57%   |
| Intel Core i5-7600T CPU @ 2.80GHz        | 1        | 3.57%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1        | 3.57%   |
| Intel Core i5-10500 CPU @ 3.10GHz        | 1        | 3.57%   |
| Intel Core i5-10400F CPU @ 2.90GHz       | 1        | 3.57%   |
| Intel Core i5-10400 CPU @ 2.90GHz        | 1        | 3.57%   |
| Intel Core i5 CPU 650 @ 3.20GHz          | 1        | 3.57%   |
| Intel Core i3-6300 CPU @ 3.80GHz         | 1        | 3.57%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 1        | 3.57%   |
| Intel Core i3-10105F CPU @ 3.70GHz       | 1        | 3.57%   |
| Intel 12th Gen Core i9-12900KS           | 1        | 3.57%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz   | 1        | 3.57%   |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz | 1        | 3.57%   |
| Intel 11th Gen Core i5-11400T @ 1.30GHz  | 1        | 3.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics   | 1        | 3.57%   |
| AMD Ryzen 7 4800U with Radeon Graphics   | 1        | 3.57%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 1        | 3.57%   |
| AMD Ryzen 7 2700X Eight-Core Processor   | 1        | 3.57%   |
| AMD Ryzen 5 3600X 6-Core Processor       | 1        | 3.57%   |
| AMD Ryzen 5 1600 Six-Core Processor      | 1        | 3.57%   |
| AMD Ryzen 3 4100 4-Core Processor        | 1        | 3.57%   |
| AMD Ryzen 3 3100 4-Core Processor        | 1        | 3.57%   |
| AMD Phenom II X2 B59 Processor           | 1        | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 8        | 28.57%  |
| Other            | 4        | 14.29%  |
| AMD Ryzen 7      | 4        | 14.29%  |
| AMD Ryzen 5      | 4        | 14.29%  |
| Intel Core i3    | 3        | 10.71%  |
| AMD Ryzen 3      | 2        | 7.14%   |
| Intel Pentium    | 1        | 3.57%   |
| Intel Core i7    | 1        | 3.57%   |
| AMD Phenom II X2 | 1        | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 10       | 35.71%  |
| 4      | 7        | 25%     |
| 8      | 5        | 17.86%  |
| 2      | 5        | 17.86%  |
| 16     | 1        | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 78.57%  |
| 1      | 6        | 21.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 28       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 85.71%  |
| 0xa0653    | 1        | 3.57%   |
| 0x0a50000d | 1        | 3.57%   |
| 0x08701030 | 1        | 3.57%   |
| 0x08701021 | 1        | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Zen 2     | 5        | 17.86%  |
| CometLake | 4        | 14.29%  |
| Unknown   | 4        | 14.29%  |
| Zen 3     | 3        | 10.71%  |
| Skylake   | 2        | 7.14%   |
| KabyLake  | 2        | 7.14%   |
| IvyBridge | 2        | 7.14%   |
| Haswell   | 2        | 7.14%   |
| Zen+      | 1        | 3.57%   |
| Zen       | 1        | 3.57%   |
| Westmere  | 1        | 3.57%   |
| K10       | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 14       | 48.28%  |
| Intel  | 9        | 31.03%  |
| AMD    | 6        | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 10%     |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 10%     |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 6.67%   |
| Intel HD Graphics 530                                                       | 2        | 6.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 3.33%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 3.33%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 3.33%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 3.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.33%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 3.33%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.33%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 3.33%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 3.33%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 3.33%   |
| Intel HD Graphics 630                                                       | 1        | 3.33%   |
| Intel AlderLake-S GT1                                                       | 1        | 3.33%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 1        | 3.33%   |
| AMD Pinewood [Mobility Radeon HD 5570/6550A]                                | 1        | 3.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 14       | 50%     |
| 1 x Intel  | 8        | 28.57%  |
| 1 x AMD    | 6        | 21.43%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 53.57%  |
| Proprietary | 13       | 46.43%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 57.14%  |
| 7.01-8.0   | 3        | 10.71%  |
| 5.01-6.0   | 2        | 7.14%   |
| 3.01-4.0   | 2        | 7.14%   |
| 1.01-2.0   | 2        | 7.14%   |
| 8.01-16.0  | 2        | 7.14%   |
| 0.01-0.5   | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 27.59%  |
| Acer                 | 5        | 17.24%  |
| Dell                 | 4        | 13.79%  |
| Hewlett-Packard      | 2        | 6.9%    |
| Goldstar             | 2        | 6.9%    |
| BenQ                 | 2        | 6.9%    |
| AOC                  | 2        | 6.9%    |
| ViewSonic            | 1        | 3.45%   |
| Philips              | 1        | 3.45%   |
| Eizo                 | 1        | 3.45%   |
| Ancor Communications | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                   | 2        | 5.71%   |
| Acer EK240Y ACR0758 1920x1080 527x296mm 23.8-inch                     | 2        | 5.71%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1        | 2.86%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                      | 1        | 2.86%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch   | 1        | 2.86%   |
| Samsung Electronics SMB1930HD SAM0708 1360x768 410x230mm 18.5-inch    | 1        | 2.86%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 600x340mm 27.2-inch     | 1        | 2.86%   |
| Samsung Electronics S24R35A SAM729F 1920x1080 527x296mm 23.8-inch     | 1        | 2.86%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 2.86%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 2.86%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1        | 2.86%   |
| Samsung Electronics LC27T55 SAM701E 1920x1080 609x349mm 27.6-inch     | 1        | 2.86%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1        | 2.86%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 2.86%   |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch                   | 1        | 2.86%   |
| Hewlett-Packard TouchSmart HWP4205 1920x1080 510x287mm 23.0-inch      | 1        | 2.86%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 1        | 2.86%   |
| Goldstar E2041 GSM4EC9 1600x900 443x249mm 20.0-inch                   | 1        | 2.86%   |
| Goldstar 24MB65 GSM5A4D 1920x1200 520x330mm 24.2-inch                 | 1        | 2.86%   |
| Eizo EV2736W ENC2383 2560x1440 597x336mm 27.0-inch                    | 1        | 2.86%   |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                    | 1        | 2.86%   |
| Dell S2421HN DEL41F2 1920x1080 527x296mm 23.8-inch                    | 1        | 2.86%   |
| Dell S2415H DELA0B5 1920x1080 527x296mm 23.8-inch                     | 1        | 2.86%   |
| Dell P2424HT DELD170 1920x1080 527x296mm 23.8-inch                    | 1        | 2.86%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                        | 1        | 2.86%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 1        | 2.86%   |
| AOC LCD Monitor 25G3ZM 3840x1080                                      | 1        | 2.86%   |
| AOC LCD Monitor 25G3ZM                                                | 1        | 2.86%   |
| AOC 2050 AOC2050 1600x900 443x249mm 20.0-inch                         | 1        | 2.86%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 1        | 2.86%   |
| Acer Z35 ACR0478 2560x1080 814x346mm 34.8-inch                        | 1        | 2.86%   |
| Acer VG270 ACR06C0 1920x1080 598x336mm 27.0-inch                      | 1        | 2.86%   |
| Acer QG241Y ACR079C 1920x1080 527x296mm 23.8-inch                     | 1        | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 16       | 55.17%  |
| 2560x1440 (QHD)   | 3        | 10.34%  |
| 1920x1200 (WUXGA) | 2        | 6.9%    |
| 1600x900 (HD+)    | 2        | 6.9%    |
| 3840x1080         | 1        | 3.45%   |
| 2560x1080         | 1        | 3.45%   |
| 1440x900 (WXGA+)  | 1        | 3.45%   |
| 1360x768          | 1        | 3.45%   |
| 1280x1024 (SXGA)  | 1        | 3.45%   |
| Unknown           | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 27.27%  |
| 27      | 7        | 21.21%  |
| 23      | 5        | 15.15%  |
| 21      | 2        | 6.06%   |
| 20      | 2        | 6.06%   |
| Unknown | 2        | 6.06%   |
| 46      | 1        | 3.03%   |
| 34      | 1        | 3.03%   |
| 31      | 1        | 3.03%   |
| 19      | 1        | 3.03%   |
| 18      | 1        | 3.03%   |
| 17      | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 58.62%  |
| 401-500     | 6        | 20.69%  |
| Unknown     | 2        | 6.9%    |
| 801-900     | 1        | 3.45%   |
| 601-700     | 1        | 3.45%   |
| 301-350     | 1        | 3.45%   |
| 1001-1500   | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 21       | 77.78%  |
| 16/10   | 3        | 11.11%  |
| 5/4     | 1        | 3.7%    |
| 21/9    | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 37.5%   |
| 301-350        | 7        | 21.88%  |
| 251-300        | 3        | 9.38%   |
| 151-200        | 3        | 9.38%   |
| 351-500        | 2        | 6.25%   |
| 141-150        | 2        | 6.25%   |
| Unknown        | 2        | 6.25%   |
| 501-1000       | 1        | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 71.43%  |
| 101-120 | 5        | 17.86%  |
| Unknown | 2        | 7.14%   |
| 1-50    | 1        | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 71.43%  |
| 2     | 6        | 21.43%  |
| 3     | 2        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 51.28%  |
| Intel                 | 14       | 35.9%   |
| TP-Link               | 1        | 2.56%   |
| Ralink Technology     | 1        | 2.56%   |
| Qualcomm Atheros      | 1        | 2.56%   |
| D-Link                | 1        | 2.56%   |
| Broadcom              | 1        | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15       | 31.25%  |
| Intel Ethernet Controller I225-V                                       | 6        | 12.5%   |
| Intel Wi-Fi 6 AX200                                                    | 4        | 8.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 4.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2        | 4.17%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 4.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 2.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 2.08%   |
| Realtek 802.11ac NIC                                                   | 1        | 2.08%   |
| Ralink Airlink101 AWLL6070 802.11bgn Wireless Adapter [Ralink RT2770]  | 1        | 2.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 2.08%   |
| Intel Wireless 3160                                                    | 1        | 2.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 2.08%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 2.08%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 2.08%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1        | 2.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 2.08%   |
| D-Link Wireless N Nano USB Adapter                                     | 1        | 2.08%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                         | 1        | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 58.82%  |
| Realtek Semiconductor | 3        | 17.65%  |
| TP-Link               | 1        | 5.88%   |
| Ralink Technology     | 1        | 5.88%   |
| Qualcomm Atheros      | 1        | 5.88%   |
| D-Link                | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                   | 4        | 23.53%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]             | 2        | 11.76%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                          | 1        | 5.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1        | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 1        | 5.88%   |
| Realtek 802.11ac NIC                                                  | 1        | 5.88%   |
| Ralink Airlink101 AWLL6070 802.11bgn Wireless Adapter [Ralink RT2770] | 1        | 5.88%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1        | 5.88%   |
| Intel Wireless 3160                                                   | 1        | 5.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]               | 1        | 5.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                       | 1        | 5.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                                      | 1        | 5.88%   |
| D-Link Wireless N Nano USB Adapter                                    | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 60%     |
| Intel                 | 11       | 36.67%  |
| Broadcom              | 1        | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15       | 48.39%  |
| Intel Ethernet Controller I225-V                                       | 6        | 19.35%  |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 6.45%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 6.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 3.23%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 3.23%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 3.23%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 3.23%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                         | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 62.79%  |
| WiFi     | 16       | 37.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 72.41%  |
| WiFi     | 8        | 27.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 46.43%  |
| 2     | 12       | 42.86%  |
| 3     | 2        | 7.14%   |
| 0     | 1        | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 72.41%  |
| Yes  | 8        | 27.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 57.14%  |
| Cambridge Silicon Radio | 3        | 21.43%  |
| Realtek Semiconductor   | 1        | 7.14%   |
| Broadcom                | 1        | 7.14%   |
| Unknown                 | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 21.43%  |
| Intel AX210 Bluetooth                               | 2        | 14.29%  |
| Intel AX200 Bluetooth                               | 2        | 14.29%  |
| Realtek Bluetooth Radio                             | 1        | 7.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.14%   |
| Intel Bluetooth wireless interface                  | 1        | 7.14%   |
| Intel Bluetooth Device                              | 1        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.14%   |
| Broadcom HP Bluethunder                             | 1        | 7.14%   |
| Unknown                                             | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 16       | 35.56%  |
| Nvidia              | 14       | 31.11%  |
| AMD                 | 9        | 20%     |
| Valve Software      | 1        | 2.22%   |
| Razer USA           | 1        | 2.22%   |
| JMTek               | 1        | 2.22%   |
| Creative Technology | 1        | 2.22%   |
| Creative Labs       | 1        | 2.22%   |
| C-Media Electronics | 1        | 2.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                                              | 5        | 9.26%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 5        | 9.26%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 3        | 5.56%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 2        | 3.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2        | 3.7%    |
| Nvidia GA104 High Definition Audio Controller                                                   | 2        | 3.7%    |
| Intel Tiger Lake-H HD Audio Controller                                                          | 2        | 3.7%    |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 2        | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 3.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                                        | 2        | 3.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 2        | 3.7%    |
| Valve Software Valve VR Radio & HMD Mic                                                         | 1        | 1.85%   |
| Razer USA Razer Seiren Mini                                                                     | 1        | 1.85%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1        | 1.85%   |
| Nvidia TU102 High Definition Audio Controller                                                   | 1        | 1.85%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                       | 1        | 1.85%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 1        | 1.85%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1        | 1.85%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 1.85%   |
| JMTek SADES Audio Device                                                                        | 1        | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 1.85%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 1        | 1.85%   |
| Intel Comet Lake PCH cAVS                                                                       | 1        | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                      | 1        | 1.85%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 1        | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 1        | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 1        | 1.85%   |
| Intel 200 Series PCH HD Audio                                                                   | 1        | 1.85%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                    | 1        | 1.85%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.85%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 1        | 1.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 1        | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Micron Technology | 1        | 20%     |
| KLEVV             | 1        | 20%     |
| Kingston          | 1        | 20%     |
| Crucial           | 1        | 20%     |
| Corsair           | 1        | 20%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s    | 1        | 20%     |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s     | 1        | 20%     |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 1        | 20%     |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s | 1        | 20%     |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 100%    |

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
| 16384 | 2        | 50%     |
| 8192  | 2        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3733  | 2        | 50%     |
| 3200  | 1        | 25%     |
| 2666  | 1        | 25%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Prolific Technology | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Valve Software                         | 1        | 12.5%   |
| Sunplus Innovation Technology          | 1        | 12.5%   |
| Sony Ericsson Mobile Communications AB | 1        | 12.5%   |
| Microdia                               | 1        | 12.5%   |
| Logitech                               | 1        | 12.5%   |
| Lenovo                                 | 1        | 12.5%   |
| KYE Systems (Mouse Systems)            | 1        | 12.5%   |
| Chicony Electronics                    | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Valve Software 3D Camera                  | 1        | 12.5%   |
| Sunplus SPCA2281 Web Camera               | 1        | 12.5%   |
| Sony Ericsson Mobile AB XQ-CC54           | 1        | 12.5%   |
| Microdia Sonix USB 2.0 Camera             | 1        | 12.5%   |
| Logitech HD Pro Webcam C920               | 1        | 12.5%   |
| Lenovo FHD Webcam Audio                   | 1        | 12.5%   |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 12.5%   |
| Chicony HP High Definition Webcam         | 1        | 12.5%   |

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
| 0     | 23       | 82.14%  |
| 1     | 5        | 17.86%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 2        | 40%     |
| Net/wireless          | 1        | 20%     |
| Multimedia controller | 1        | 20%     |
| Camera                | 1        | 20%     |

