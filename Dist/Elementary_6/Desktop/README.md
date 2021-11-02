Elementary 6 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=elementary-6

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | P67 Extreme4                | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock   | P67 Extreme4                | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI      | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| HP       | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| HP       | 339A                        | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Dell     | 0M9KCM A02                  | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Gigabyte | AB350-Gaming 3-CF           | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| MSI      | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek  | TUF GAMING B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle  | FS61                        | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Apple    | Mac-F221BEC8                | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| ASUSTek  | P7H55-M                     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell     | 0Y5DDC A00                  | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell     | 0Y5DDC A00                  | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| ASRock   | M3A790GXH/128M              | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Intel    | X79 V1.x                    | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| ASUSTek  | M4N78-AM                    | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| ASRock   | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Intel    | H61                         | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP       | 8767 A                      | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| Gigabyte | B450M DS3H V2               | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| ASUSTek  | ROG STRIX Z590-F GAMING ... | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Gigabyte | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| ASRock   | H81TM-ITX R2.0              | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| ASUSTek  | M5A78L-M LX/BR              | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| ASUSTek  | P6X58D-E                    | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| MSI      | X470 GAMING PLUS MAX        | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| ASUSTek  | TUF GAMING B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| ASUSTek  | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| ASRock   | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| ASUSTek  | ROG STRIX B450-I GAMING     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| ASUSTek  | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| HP       | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-27-generic | 10       | 29.41%  |
| 5.11.0-37-generic | 6        | 17.65%  |
| 5.11.0-25-generic | 5        | 14.71%  |
| 5.8.0-50-generic  | 3        | 8.82%   |
| 5.11.0-38-generic | 2        | 5.88%   |
| 5.11.0-36-generic | 2        | 5.88%   |
| 5.11.0-34-generic | 2        | 5.88%   |
| 5.8.0-63-generic  | 1        | 2.94%   |
| 5.8.0-55-generic  | 1        | 2.94%   |
| 5.4.0-58-generic  | 1        | 2.94%   |
| 5.4.0-56-generic  | 1        | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 27       | 79.41%  |
| 5.8.0   | 5        | 14.71%  |
| 5.4.0   | 2        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 27       | 79.41%  |
| 5.8     | 5        | 14.71%  |
| 5.4     | 2        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 34       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 30       | 88.24%  |
| Unknown  | 2        | 5.88%   |
| MATE     | 1        | 2.94%   |
| GNOME    | 1        | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 34       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 82.35%  |
| TDM     | 3        | 8.82%   |
| LightDM | 3        | 8.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 15       | 44.12%  |
| de_DE | 5        | 14.71%  |
| es_ES | 4        | 11.76%  |
| pt_BR | 2        | 5.88%   |
| tr_TR | 1        | 2.94%   |
| ru_RU | 1        | 2.94%   |
| it_IT | 1        | 2.94%   |
| fr_FR | 1        | 2.94%   |
| es_MX | 1        | 2.94%   |
| en_GB | 1        | 2.94%   |
| en_AU | 1        | 2.94%   |
| ca_ES | 1        | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 19       | 55.88%  |
| BIOS | 15       | 44.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 33       | 97.06%  |
| Btrfs | 1        | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 85.29%  |
| MBR     | 3        | 8.82%   |
| GPT     | 2        | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 91.18%  |
| Yes       | 3        | 8.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 76.47%  |
| Yes       | 8        | 23.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 32.35%  |
| Gigabyte Technology | 5        | 14.71%  |
| ASRock              | 5        | 14.71%  |
| Hewlett-Packard     | 4        | 11.76%  |
| MSI                 | 3        | 8.82%   |
| Intel               | 2        | 5.88%   |
| Dell                | 2        | 5.88%   |
| Shuttle             | 1        | 2.94%   |
| Apple               | 1        | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Shuttle DS61                         | 1        | 2.94%   |
| MSI MS-7C83                          | 1        | 2.94%   |
| MSI MS-7B79                          | 1        | 2.94%   |
| MSI Elite 7100 Microtower PC         | 1        | 2.94%   |
| Intel X64                            | 1        | 2.94%   |
| Intel H61                            | 1        | 2.94%   |
| HP Z820 Workstation                  | 1        | 2.94%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 2.94%   |
| HP Pavilion Desktop 590-p0xxx        | 1        | 2.94%   |
| HP 339A                              | 1        | 2.94%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 2.94%   |
| Gigabyte H310M M.2 2.0               | 1        | 2.94%   |
| Gigabyte F2A55M-HD2                  | 1        | 2.94%   |
| Gigabyte B450M DS3H V2               | 1        | 2.94%   |
| Gigabyte AB350-Gaming 3              | 1        | 2.94%   |
| Dell OptiPlex 9020M                  | 1        | 2.94%   |
| Dell OptiPlex 9010                   | 1        | 2.94%   |
| ASUS TUF GAMING B560M-PLUS           | 1        | 2.94%   |
| ASUS TUF GAMING B550M-PLUS           | 1        | 2.94%   |
| ASUS TUF GAMING B450M-PRO II         | 1        | 2.94%   |
| ASUS ROG STRIX Z590-F GAMING WIFI    | 1        | 2.94%   |
| ASUS ROG STRIX B450-I GAMING         | 1        | 2.94%   |
| ASUS P7H55-M                         | 1        | 2.94%   |
| ASUS P6X58D-E                        | 1        | 2.94%   |
| ASUS P5KPL-AM SE                     | 1        | 2.94%   |
| ASUS M5A99X EVO R2.0                 | 1        | 2.94%   |
| ASUS M5A78L-M LX/BR                  | 1        | 2.94%   |
| ASUS M4N78-AM                        | 1        | 2.94%   |
| ASRock P67 Extreme4                  | 1        | 2.94%   |
| ASRock M3A790GXH/128M                | 1        | 2.94%   |
| ASRock H81TM-ITX R2.0                | 1        | 2.94%   |
| ASRock B450 Pro4                     | 1        | 2.94%   |
| ASRock A320M-HDV                     | 1        | 2.94%   |
| Apple MacPro5,1                      | 1        | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS TUF              | 3        | 8.82%   |
| HP Pavilion           | 2        | 5.88%   |
| Dell OptiPlex         | 2        | 5.88%   |
| ASUS ROG              | 2        | 5.88%   |
| Shuttle DS61          | 1        | 2.94%   |
| MSI MS-7C83           | 1        | 2.94%   |
| MSI MS-7B79           | 1        | 2.94%   |
| MSI Elite             | 1        | 2.94%   |
| Intel X64             | 1        | 2.94%   |
| Intel H61             | 1        | 2.94%   |
| HP Z820               | 1        | 2.94%   |
| HP 339A               | 1        | 2.94%   |
| Gigabyte X570         | 1        | 2.94%   |
| Gigabyte H310M        | 1        | 2.94%   |
| Gigabyte F2A55M-HD2   | 1        | 2.94%   |
| Gigabyte B450M        | 1        | 2.94%   |
| Gigabyte AB350-Gaming | 1        | 2.94%   |
| ASUS P7H55-M          | 1        | 2.94%   |
| ASUS P6X58D-E         | 1        | 2.94%   |
| ASUS P5KPL-AM         | 1        | 2.94%   |
| ASUS M5A99X           | 1        | 2.94%   |
| ASUS M5A78L-M         | 1        | 2.94%   |
| ASUS M4N78-AM         | 1        | 2.94%   |
| ASRock P67            | 1        | 2.94%   |
| ASRock M3A790GXH      | 1        | 2.94%   |
| ASRock H81TM-ITX      | 1        | 2.94%   |
| ASRock B450           | 1        | 2.94%   |
| ASRock A320M-HDV      | 1        | 2.94%   |
| Apple MacPro5         | 1        | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 7        | 20.59%  |
| 2020 | 5        | 14.71%  |
| 2019 | 4        | 11.76%  |
| 2018 | 3        | 8.82%   |
| 2013 | 3        | 8.82%   |
| 2015 | 2        | 5.88%   |
| 2014 | 2        | 5.88%   |
| 2012 | 2        | 5.88%   |
| 2011 | 2        | 5.88%   |
| 2010 | 2        | 5.88%   |
| 2017 | 1        | 2.94%   |
| 2009 | 1        | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 34       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 91.18%  |
| Enabled  | 3        | 8.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 11       | 32.35%  |
| 32.01-64.0  | 10       | 29.41%  |
| 4.01-8.0    | 7        | 20.59%  |
| 3.01-4.0    | 3        | 8.82%   |
| 8.01-16.0   | 2        | 5.88%   |
| 64.01-256.0 | 1        | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 14       | 41.18%  |
| 2.01-3.0  | 11       | 32.35%  |
| 3.01-4.0  | 5        | 14.71%  |
| 4.01-8.0  | 3        | 8.82%   |
| 8.01-16.0 | 1        | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 38.24%  |
| 1      | 13       | 38.24%  |
| 3      | 4        | 11.76%  |
| 4      | 3        | 8.82%   |
| 5      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 73.53%  |
| Yes       | 9        | 26.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 52.94%  |
| No        | 16       | 47.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 58.82%  |
| Yes       | 14       | 41.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 4        | 11.76%  |
| USA         | 3        | 8.82%   |
| UK          | 3        | 8.82%   |
| Spain       | 2        | 5.88%   |
| Russia      | 2        | 5.88%   |
| Indonesia   | 2        | 5.88%   |
| Finland     | 2        | 5.88%   |
| Brazil      | 2        | 5.88%   |
| Argentina   | 2        | 5.88%   |
| Turkey      | 1        | 2.94%   |
| Netherlands | 1        | 2.94%   |
| Mexico      | 1        | 2.94%   |
| Italy       | 1        | 2.94%   |
| Greece      | 1        | 2.94%   |
| France      | 1        | 2.94%   |
| Denmark     | 1        | 2.94%   |
| Czechia     | 1        | 2.94%   |
| Colombia    | 1        | 2.94%   |
| Canada      | 1        | 2.94%   |
| Austria     | 1        | 2.94%   |
| Australia   | 1        | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Znojmo            | 1        | 2.94%   |
| Wriezen           | 1        | 2.94%   |
| Wigan             | 1        | 2.94%   |
| Vienna            | 1        | 2.94%   |
| Vantaa            | 1        | 2.94%   |
| Ullastrell        | 1        | 2.94%   |
| Tucson            | 1        | 2.94%   |
| Staropyshminsk    | 1        | 2.94%   |
| Sparti            | 1        | 2.94%   |
| S??o Paulo        | 1        | 2.94%   |
| Saskatoon         | 1        | 2.94%   |
| Rosario           | 1        | 2.94%   |
| Roermond          | 1        | 2.94%   |
| Rio de Janeiro    | 1        | 2.94%   |
| Rheinberg         | 1        | 2.94%   |
| Potsdam           | 1        | 2.94%   |
| Paris             | 1        | 2.94%   |
| Morelia           | 1        | 2.94%   |
| Milan             | 1        | 2.94%   |
| Medan             | 1        | 2.94%   |
| Kobenhavn NV      | 1        | 2.94%   |
| Klaukkala         | 1        | 2.94%   |
| Kediri            | 1        | 2.94%   |
| Kazan?ˆ™          | 1        | 2.94%   |
| Izmir             | 1        | 2.94%   |
| Hostalric         | 1        | 2.94%   |
| Hephzibah         | 1        | 2.94%   |
| East Malvern      | 1        | 2.94%   |
| Bonnybridge       | 1        | 2.94%   |
| Bernau bei Berlin | 1        | 2.94%   |
| Berazategui       | 1        | 2.94%   |
| Bathgate          | 1        | 2.94%   |
| Barranquilla      | 1        | 2.94%   |
| Ames              | 1        | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 11       | 14     | 19.3%   |
| Seagate                   | 7        | 8      | 12.28%  |
| Samsung Electronics       | 7        | 11     | 12.28%  |
| Kingston                  | 7        | 7      | 12.28%  |
| SanDisk                   | 5        | 5      | 8.77%   |
| Crucial                   | 3        | 4      | 5.26%   |
| OCZ                       | 2        | 2      | 3.51%   |
| Intel                     | 2        | 2      | 3.51%   |
| Hitachi                   | 2        | 2      | 3.51%   |
| USB3.1                    | 1        | 1      | 1.75%   |
| Toshiba                   | 1        | 1      | 1.75%   |
| Team                      | 1        | 1      | 1.75%   |
| SK Hynix                  | 1        | 1      | 1.75%   |
| Phison                    | 1        | 1      | 1.75%   |
| Patriot                   | 1        | 1      | 1.75%   |
| Micron/Crucial Technology | 1        | 2      | 1.75%   |
| Micron Technology         | 1        | 1      | 1.75%   |
| LITEON                    | 1        | 1      | 1.75%   |
| Gigabyte Technology       | 1        | 1      | 1.75%   |
| Apacer                    | 1        | 1      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD   | 3        | 4.55%   |
| WDC WD10EZEX-60WN4A0 1TB          | 2        | 3.03%   |
| Samsung SSD 850 EVO 250GB         | 2        | 3.03%   |
| Samsung NVMe SSD Drive 500GB      | 2        | 3.03%   |
| Intel NVMe SSD Drive 512GB        | 2        | 3.03%   |
| WDC WD5000AAKX-603CA0 500GB       | 1        | 1.52%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1.52%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 1.52%   |
| WDC WD2500AAKS-00B3A0 250GB       | 1        | 1.52%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 1.52%   |
| WDC WD10EZRX-00L4HB0 1TB          | 1        | 1.52%   |
| WDC WD10EZEX-75ZF5A0 1TB          | 1        | 1.52%   |
| WDC WD10EZEX-22MFCA0 1TB          | 1        | 1.52%   |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 1.52%   |
| WDC WD10EZEX-00RKKA0 1TB          | 1        | 1.52%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 1.52%   |
| WDC WD10EURX-63UY4Y0 1TB          | 1        | 1.52%   |
| USB3.1 Disk 500GB                 | 1        | 1.52%   |
| Toshiba DT01ACA100 1TB            | 1        | 1.52%   |
| Team L5 LITE SSD 120GB            | 1        | 1.52%   |
| SK Hynix SH920 2.5 7MM 256GB SSD  | 1        | 1.52%   |
| Seagate ST940210AS 40GB           | 1        | 1.52%   |
| Seagate ST3500312CS 500GB         | 1        | 1.52%   |
| Seagate ST3160813AS 160GB         | 1        | 1.52%   |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1.52%   |
| Seagate ST1000NM0053-1C1173 1TB   | 1        | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1.52%   |
| Seagate NVMe SSD Drive 2TB        | 1        | 1.52%   |
| Seagate Backup+ BK 1TB            | 1        | 1.52%   |
| SanDisk SDSSDRC032G 32GB          | 1        | 1.52%   |
| SanDisk SDSSDHII480G 480GB        | 1        | 1.52%   |
| SanDisk SDSSDA-1T00 1TB           | 1        | 1.52%   |
| Sandisk NVMe SSD Drive 500GB      | 1        | 1.52%   |
| Sandisk NVMe SSD Drive 1TB        | 1        | 1.52%   |
| Samsung SSD 980 PRO 1TB           | 1        | 1.52%   |
| Samsung SSD 960 EVO 500GB         | 1        | 1.52%   |
| Samsung SSD 870 QVO 1TB           | 1        | 1.52%   |
| Samsung SSD 840 Series 500GB      | 1        | 1.52%   |
| Samsung Portable SSD T5 500GB     | 1        | 1.52%   |
| Samsung NVMe SSD Drive 1TB        | 1        | 1.52%   |
| Samsung HD154UI 1TB               | 1        | 1.52%   |
| Phison NVMe SSD Drive 256GB       | 1        | 1.52%   |
| Patriot Burst Elite 480GB SSD     | 1        | 1.52%   |
| OCZ AGILITY4 256GB SSD            | 1        | 1.52%   |
| OCZ AGILITY3 240GB SSD            | 1        | 1.52%   |
| Micron/Crucial NVMe SSD Drive 1TB | 1        | 1.52%   |
| Micron NVMe SSD Drive 500GB       | 1        | 1.52%   |
| LITEON LCH-512V2S 512GB SSD       | 1        | 1.52%   |
| Kingston SV100S2128G 128GB SSD    | 1        | 1.52%   |
| Kingston SA400S37480G 480GB SSD   | 1        | 1.52%   |
| Kingston NVMe SSD Drive 500GB     | 1        | 1.52%   |
| Kingston NVMe SSD Drive 1TB       | 1        | 1.52%   |
| Hitachi HTS723225A7A364 250GB     | 1        | 1.52%   |
| Hitachi HDT722516DLA380 164GB     | 1        | 1.52%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB  | 1        | 1.52%   |
| Crucial CT250MX500SSD1 250GB      | 1        | 1.52%   |
| Crucial CT240BX500SSD1 240GB      | 1        | 1.52%   |
| Crucial CT240BX200SSD1 240GB      | 1        | 1.52%   |
| Crucial CT1000MX500SSD1 1TB       | 1        | 1.52%   |
| Apacer AS340 120GB SSD            | 1        | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 14     | 52.38%  |
| Seagate             | 6        | 6      | 28.57%  |
| Hitachi             | 2        | 2      | 9.52%   |
| Toshiba             | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 22.73%  |
| Samsung Electronics | 4        | 5      | 18.18%  |
| SanDisk             | 3        | 3      | 13.64%  |
| Crucial             | 3        | 4      | 13.64%  |
| OCZ                 | 2        | 2      | 9.09%   |
| Team                | 1        | 1      | 4.55%   |
| SK Hynix            | 1        | 1      | 4.55%   |
| Patriot             | 1        | 1      | 4.55%   |
| LITEON              | 1        | 1      | 4.55%   |
| Apacer              | 1        | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 19       | 24     | 38%     |
| SSD     | 18       | 24     | 36%     |
| NVMe    | 11       | 17     | 22%     |
| Unknown | 2        | 2      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 47     | 69.05%  |
| NVMe | 11       | 17     | 26.19%  |
| SAS  | 2        | 3      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 29     | 60%     |
| 0.51-1.0   | 14       | 17     | 35%     |
| 1.01-2.0   | 2        | 2      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 13       | 38.24%  |
| 251-500    | 10       | 29.41%  |
| 21-50      | 3        | 8.82%   |
| 1001-2000  | 3        | 8.82%   |
| 501-1000   | 3        | 8.82%   |
| 2001-3000  | 1        | 2.94%   |
| 51-100     | 1        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 20       | 58.82%  |
| 21-50   | 5        | 14.71%  |
| 51-100  | 4        | 11.76%  |
| 101-250 | 3        | 8.82%   |
| 251-500 | 2        | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD3200AAJS-56B4A0 320GB | 1        | 1      | 33.33%  |
| WDC WD10EZEX-00KUWA0 1TB    | 1        | 1      | 33.33%  |
| Seagate ST3160813AS 160GB   | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 100%    |

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
| Detected | 29       | 54     | 78.38%  |
| Works    | 5        | 10     | 13.51%  |
| Malfunc  | 3        | 3      | 8.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 19       | 37.25%  |
| AMD                         | 13       | 25.49%  |
| Samsung Electronics         | 4        | 7.84%   |
| Sandisk                     | 2        | 3.92%   |
| Marvell Technology Group    | 2        | 3.92%   |
| Kingston Technology Company | 2        | 3.92%   |
| ASMedia Technology          | 2        | 3.92%   |
| VIA Technologies            | 1        | 1.96%   |
| Seagate Technology          | 1        | 1.96%   |
| Phison Electronics          | 1        | 1.96%   |
| Nvidia                      | 1        | 1.96%   |
| Micron/Crucial Technology   | 1        | 1.96%   |
| Micron Technology           | 1        | 1.96%   |
| Broadcom / LSI              | 1        | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 11.43%  |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.86%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 2.86%   |
| Intel SSD 660P Series                                                                   | 2        | 2.86%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 2.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.86%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.86%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 1.43%   |
| Seagate FireCuda 510 SSD                                                                | 1        | 1.43%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.43%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.43%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 1.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.43%   |
| Micron Non-Volatile memory controller                                                   | 1        | 1.43%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 1.43%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.43%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.43%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.43%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.43%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 1.43%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.43%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.43%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.43%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 25       | 52.08%  |
| NVMe | 11       | 22.92%  |
| IDE  | 8        | 16.67%  |
| RAID | 3        | 6.25%   |
| SAS  | 1        | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 55.88%  |
| AMD    | 15       | 44.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 11.76%  |
| Intel Core i3 CPU 530 @ 2.93GHz                | 2        | 5.88%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 5.88%   |
| Intel Xeon CPU E5520 @ 2.27GHz                 | 1        | 2.94%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 2.94%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz             | 1        | 2.94%   |
| Intel Core i7-4785T CPU @ 2.20GHz              | 1        | 2.94%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 2.94%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 2.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 2.94%   |
| Intel Core i5-3550 CPU @ 3.30GHz               | 1        | 2.94%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 2.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 2.94%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 2.94%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 2.94%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz          | 1        | 2.94%   |
| Intel Celeron G4930 CPU @ 3.20GHz              | 1        | 2.94%   |
| Intel Celeron CPU G1610 @ 2.60GHz              | 1        | 2.94%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 2.94%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz         | 1        | 2.94%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 2.94%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 2.94%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 2.94%   |
| AMD Phenom II X4 925 Processor                 | 1        | 2.94%   |
| AMD Phenom 9850 Quad-Core Processor            | 1        | 2.94%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 2.94%   |
| AMD FX-6100 Six-Core Processor                 | 1        | 2.94%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1        | 2.94%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 5        | 14.71%  |
| AMD Ryzen 7       | 4        | 11.76%  |
| AMD Ryzen 5       | 4        | 11.76%  |
| Intel Xeon        | 3        | 8.82%   |
| Intel Core i7     | 3        | 8.82%   |
| Intel Core i3     | 3        | 8.82%   |
| Other             | 2        | 5.88%   |
| Intel Celeron     | 2        | 5.88%   |
| AMD FX            | 2        | 5.88%   |
| Intel Core 2 Quad | 1        | 2.94%   |
| AMD Ryzen 3       | 1        | 2.94%   |
| AMD Phenom II X4  | 1        | 2.94%   |
| AMD Phenom        | 1        | 2.94%   |
| AMD A4            | 1        | 2.94%   |
| AMD A10           | 1        | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 32.35%  |
| 8      | 9        | 26.47%  |
| 2      | 6        | 17.65%  |
| 6      | 5        | 14.71%  |
| 12     | 1        | 2.94%   |
| 3      | 1        | 2.94%   |
| 1      | 1        | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 94.12%  |
| 2      | 2        | 5.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 70.59%  |
| 1      | 10       | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 34       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 4        | 11.76%  |
| 0x206a7    | 3        | 8.82%   |
| 0xa0671    | 2        | 5.88%   |
| 0x306c3    | 2        | 5.88%   |
| 0x306a9    | 2        | 5.88%   |
| 0x206d7    | 2        | 5.88%   |
| 0x20652    | 2        | 5.88%   |
| 0x106a5    | 2        | 5.88%   |
| 0x08701013 | 2        | 5.88%   |
| 0x0800820d | 2        | 5.88%   |
| 0xa0655    | 1        | 2.94%   |
| 0xa0653    | 1        | 2.94%   |
| 0x906eb    | 1        | 2.94%   |
| 0x1067a    | 1        | 2.94%   |
| 0x08101007 | 1        | 2.94%   |
| 0x0600611a | 1        | 2.94%   |
| 0x06001119 | 1        | 2.94%   |
| 0x06000852 | 1        | 2.94%   |
| 0x0600063e | 1        | 2.94%   |
| 0x01000095 | 1        | 2.94%   |
| Unknown    | 1        | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 6        | 17.65%  |
| SandyBridge | 5        | 14.71%  |
| Zen+        | 2        | 5.88%   |
| Westmere    | 2        | 5.88%   |
| Piledriver  | 2        | 5.88%   |
| Nehalem     | 2        | 5.88%   |
| K10         | 2        | 5.88%   |
| IvyBridge   | 2        | 5.88%   |
| Icelake     | 2        | 5.88%   |
| Haswell     | 2        | 5.88%   |
| CometLake   | 2        | 5.88%   |
| Zen         | 1        | 2.94%   |
| Penryn      | 1        | 2.94%   |
| KabyLake    | 1        | 2.94%   |
| Excavator   | 1        | 2.94%   |
| Bulldozer   | 1        | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 15       | 39.47%  |
| Nvidia           | 14       | 36.84%  |
| Intel            | 8        | 21.05%  |
| Conexant Systems | 1        | 2.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 10.26%  |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 5.13%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 5.13%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 2.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.56%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 2.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.56%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 2.56%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 2.56%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 2.56%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2.56%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2.56%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 2.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.56%   |
| Conexant Systems Conexant Display controller                                | 1        | 2.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 2.56%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 2.56%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 2.56%   |
| AMD RS780D [Radeon HD 3300]                                                 | 1        | 2.56%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 2.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.56%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 2.56%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 1        | 2.56%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                            | 1        | 2.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.56%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 2.56%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x AMD                        | 13       | 38.24%  |
| 1 x Nvidia                     | 12       | 35.29%  |
| 1 x Intel                      | 6        | 17.65%  |
| 2 x AMD + 1 x Conexant Systems | 1        | 2.94%   |
| Intel + Nvidia                 | 1        | 2.94%   |
| AMD + Nvidia                   | 1        | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 85.29%  |
| Proprietary | 5        | 14.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 8        | 23.53%  |
| Unknown    | 8        | 23.53%  |
| 3.01-4.0   | 7        | 20.59%  |
| 7.01-8.0   | 4        | 11.76%  |
| 0.51-1.0   | 4        | 11.76%  |
| 5.01-6.0   | 1        | 2.94%   |
| 2.01-3.0   | 1        | 2.94%   |
| 8.01-16.0  | 1        | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 20.59%  |
| Hewlett-Packard      | 5        | 14.71%  |
| Goldstar             | 4        | 11.76%  |
| Dell                 | 4        | 11.76%  |
| AOC                  | 4        | 11.76%  |
| Ancor Communications | 2        | 5.88%   |
| Acer                 | 2        | 5.88%   |
| ViewSonic            | 1        | 2.94%   |
| TBD                  | 1        | 2.94%   |
| SKY                  | 1        | 2.94%   |
| Grundig              | 1        | 2.94%   |
| BenQ                 | 1        | 2.94%   |
| Unknown              | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 2        | 5%      |
| ViewSonic LCD Monitor VSC732E 1920x1080 520x290mm 23.4-inch           | 1        | 2.5%    |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                         | 1        | 2.5%    |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                  | 1        | 2.5%    |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch     | 1        | 2.5%    |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch     | 1        | 2.5%    |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch     | 1        | 2.5%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1        | 2.5%    |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch     | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 890x500mm 40.2-inch | 1        | 2.5%    |
| Samsung Electronics LCD Monitor S24F350 5760x1080                     | 1        | 2.5%    |
| Samsung Electronics LCD Monitor S24F350                               | 1        | 2.5%    |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch    | 1        | 2.5%    |
| Hewlett-Packard P204v HPN3634 1600x900 432x240mm 19.5-inch            | 1        | 2.5%    |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 546x352mm 25.6-inch         | 1        | 2.5%    |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch             | 1        | 2.5%    |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch             | 1        | 2.5%    |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch            | 1        | 2.5%    |
| Grundig G2 1080p dig GRU4448 1920x1080 1600x900mm 72.3-inch           | 1        | 2.5%    |
| Goldstar TV SSCR GSMC0C8 3840x2160 1600x900mm 72.3-inch               | 1        | 2.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.5%    |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1        | 2.5%    |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                | 1        | 2.5%    |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 1        | 2.5%    |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                     | 1        | 2.5%    |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 1        | 2.5%    |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 1        | 2.5%    |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                     | 1        | 2.5%    |
| Dell 1707FPV DEL4021 1280x1024 338x270mm 17.0-inch                    | 1        | 2.5%    |
| BenQ LCD Monitor PD2700U 3840x2160                                    | 1        | 2.5%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 2.5%    |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1        | 2.5%    |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                     | 1        | 2.5%    |
| Ancor Communications LCD Monitor ASUS VE278 1920x1080                 | 1        | 2.5%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1        | 2.5%    |
| Acer XB321HK ACR049C 1920x1080 710x400mm 32.1-inch                    | 1        | 2.5%    |
| Acer LCD Monitor XV270U 5120x1440                                     | 1        | 2.5%    |
| Acer LCD Monitor VG272U                                               | 1        | 2.5%    |
| Unknown                                                               | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 17       | 50%     |
| 3840x2160 (4K)    | 6        | 17.65%  |
| 1600x900 (HD+)    | 2        | 5.88%   |
| Unknown           | 2        | 5.88%   |
| 5760x1080         | 1        | 2.94%   |
| 5120x1440         | 1        | 2.94%   |
| 3840x1080         | 1        | 2.94%   |
| 2560x1440 (QHD)   | 1        | 2.94%   |
| 2560x1080         | 1        | 2.94%   |
| 1920x1200 (WUXGA) | 1        | 2.94%   |
| 1280x1024 (SXGA)  | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 6        | 17.65%  |
| 23      | 5        | 14.71%  |
| 24      | 4        | 11.76%  |
| Unknown | 4        | 11.76%  |
| 27      | 3        | 8.82%   |
| 72      | 2        | 5.88%   |
| 40      | 2        | 5.88%   |
| 49      | 1        | 2.94%   |
| 33      | 1        | 2.94%   |
| 32      | 1        | 2.94%   |
| 28      | 1        | 2.94%   |
| 25      | 1        | 2.94%   |
| 19      | 1        | 2.94%   |
| 17      | 1        | 2.94%   |
| 15      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 33.33%  |
| 401-500     | 7        | 21.21%  |
| Unknown     | 4        | 12.12%  |
| 801-900     | 2        | 6.06%   |
| 701-800     | 2        | 6.06%   |
| 601-700     | 2        | 6.06%   |
| 301-350     | 2        | 6.06%   |
| 1501-2000   | 2        | 6.06%   |
| 1001-1500   | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 22       | 73.33%  |
| Unknown | 4        | 13.33%  |
| 5/4     | 1        | 3.33%   |
| 32/9    | 1        | 3.33%   |
| 21/9    | 1        | 3.33%   |
| 16/10   | 1        | 3.33%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 33.33%  |
| 151-200        | 4        | 12.12%  |
| Unknown        | 4        | 12.12%  |
| 301-350        | 3        | 9.09%   |
| 501-1000       | 3        | 9.09%   |
| More than 1000 | 2        | 6.06%   |
| 351-500        | 2        | 6.06%   |
| 251-300        | 2        | 6.06%   |
| 141-150        | 1        | 3.03%   |
| 101-110        | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 56.25%  |
| 101-120 | 7        | 21.88%  |
| Unknown | 4        | 12.5%   |
| 1-50    | 2        | 6.25%   |
| 121-160 | 1        | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 76.47%  |
| 2     | 6        | 17.65%  |
| 3     | 2        | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 25       | 52.08%  |
| Intel                    | 11       | 22.92%  |
| Xiaomi                   | 2        | 4.17%   |
| Ralink Technology        | 2        | 4.17%   |
| TP-Link                  | 1        | 2.08%   |
| Ralink                   | 1        | 2.08%   |
| Nvidia                   | 1        | 2.08%   |
| NetGear                  | 1        | 2.08%   |
| Mercucys                 | 1        | 2.08%   |
| Marvell Technology Group | 1        | 2.08%   |
| Edimax Technology        | 1        | 2.08%   |
| ASUSTek Computer         | 1        | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 32.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 5.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 3.57%   |
| Intel I211 Gigabit Network Connection                             | 2        | 3.57%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.57%   |
| TP-Link 802.11ac NIC                                              | 1        | 1.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.79%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 1.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.79%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.79%   |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1        | 1.79%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.79%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]            | 1        | 1.79%   |
| Mercucys 802.11n NIC                                              | 1        | 1.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.79%   |
| Intel Wireless 7260                                               | 1        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.79%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.79%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.79%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.79%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1        | 1.79%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]    | 1        | 1.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 31.58%  |
| Intel                 | 5        | 26.32%  |
| Ralink Technology     | 2        | 10.53%  |
| TP-Link               | 1        | 5.26%   |
| Ralink                | 1        | 5.26%   |
| NetGear               | 1        | 5.26%   |
| Mercucys              | 1        | 5.26%   |
| Edimax Technology     | 1        | 5.26%   |
| ASUSTek Computer      | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| TP-Link 802.11ac NIC                                           | 1        | 5.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 5.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 5.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 5.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 5.26%   |
| Realtek RTL8187 Wireless Adapter                               | 1        | 5.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 5.26%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 5.26%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1        | 5.26%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]         | 1        | 5.26%   |
| Mercucys 802.11n NIC                                           | 1        | 5.26%   |
| Intel Wireless 7260                                            | 1        | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 5.26%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 5.26%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 5.26%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 5.26%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072] | 1        | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 23       | 63.89%  |
| Intel                    | 9        | 25%     |
| Xiaomi                   | 2        | 5.56%   |
| Nvidia                   | 1        | 2.78%   |
| Marvell Technology Group | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 48.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 8.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 8.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 5.41%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.41%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 5.41%   |
| Nvidia MCP77 Ethernet                                             | 1        | 2.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 2.7%    |
| Intel Ethernet Controller I225-V                                  | 1        | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.7%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 65.38%  |
| WiFi     | 18       | 34.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 70.21%  |
| WiFi     | 14       | 29.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 64.71%  |
| 2     | 12       | 35.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 73.53%  |
| Yes  | 9        | 26.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 35.71%  |
| Cambridge Silicon Radio | 4        | 28.57%  |
| Realtek Semiconductor   | 1        | 7.14%   |
| Broadcom                | 1        | 7.14%   |
| Belkin Components       | 1        | 7.14%   |
| ASUSTek Computer        | 1        | 7.14%   |
| Apple                   | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 28.57%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.14%   |
| Intel Bluetooth wireless interface                  | 1        | 7.14%   |
| Intel AX210 Bluetooth                               | 1        | 7.14%   |
| Intel AX201 Bluetooth                               | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 7.14%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 7.14%   |
| ASUS Bluetooth Radio                                | 1        | 7.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 20       | 33.33%  |
| Intel                                | 18       | 30%     |
| Nvidia                               | 14       | 23.33%  |
| Thesycon Systemsoftware & Consulting | 1        | 1.67%   |
| Razer USA                            | 1        | 1.67%   |
| JMTek                                | 1        | 1.67%   |
| Generalplus Technology               | 1        | 1.67%   |
| Creative Technology                  | 1        | 1.67%   |
| Creative Labs                        | 1        | 1.67%   |
| C-Media Electronics                  | 1        | 1.67%   |
| ASUSTek Computer                     | 1        | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 8.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4        | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3        | 4.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 4.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3        | 4.11%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 2.74%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 2.74%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 2.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 2.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 2.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 2.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 2.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 2.74%   |
| Thesycon Systemsoftware & Consulting DX7 Pro                                      | 1        | 1.37%   |
| Razer USA Kraken Tournament Edition                                               | 1        | 1.37%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.37%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 1.37%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 1.37%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.37%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 1.37%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.37%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 1.37%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 1.37%   |
| JMTek USB PnP Audio Device                                                        | 1        | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 1.37%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                    | 1        | 1.37%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.37%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 1.37%   |
| Generalplus Technology Usb Audio Device                                           | 1        | 1.37%   |
| Creative Technology Sound BlasterX Kratos S5                                      | 1        | 1.37%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 1        | 1.37%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                | 1        | 1.37%   |
| ASUSTek Computer USB Audio                                                        | 1        | 1.37%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 1.37%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 1        | 1.37%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 1.37%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1        | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                          | 1        | 1.37%   |
| AMD FCH Azalia Controller                                                         | 1        | 1.37%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 1        | 1.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1        | 1.37%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 21.43%  |
| G.Skill             | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| Corsair             | 2        | 14.29%  |
| Unknown             | 1        | 7.14%   |
| SK Hynix            | 1        | 7.14%   |
| Neo Forza           | 1        | 7.14%   |
| Crucial             | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 6.67%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s     | 1        | 6.67%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 1        | 6.67%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s      | 1        | 6.67%   |
| Neo Forza RAM NMUD380D81-1600D 8192MB DIMM DDR3          | 1        | 6.67%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s        | 1        | 6.67%   |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3 1333MT/s | 1        | 6.67%   |
| Kingston RAM 9965516-069.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 6.67%   |
| Kingston RAM 9965516-003.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 6.67%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 6.67%   |
| G.Skill RAM F3-1866C11-8GRSL 8GB SODIMM DDR3 1333MT/s    | 1        | 6.67%   |
| G.Skill RAM F3-14900CL9-4GBSR 4096MB DIMM DDR3 1600MT/s  | 1        | 6.67%   |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 2133MT/s    | 1        | 6.67%   |
| Corsair RAM CMK4GX4M1A2400C14 4GB DIMM DDR4 3007MT/s     | 1        | 6.67%   |
| Corsair RAM CMH32GX4M2D3600C18 16GB DIMM DDR4 2133MT/s   | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 5        | 50%     |
| DDR4 | 4        | 40%     |
| DDR2 | 1        | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 9        | 90%     |
| SODIMM | 1        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 50%     |
| 16384 | 2        | 20%     |
| 4096  | 2        | 20%     |
| 2048  | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 23.08%  |
| 1333    | 2        | 15.38%  |
| 3600    | 1        | 7.69%   |
| 3200    | 1        | 7.69%   |
| 3007    | 1        | 7.69%   |
| 3000    | 1        | 7.69%   |
| 2133    | 1        | 7.69%   |
| 1867    | 1        | 7.69%   |
| 800     | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Microdia                | 2        | 25%     |
| Logitech                | 2        | 25%     |
| Z-Star Microelectronics | 1        | 12.5%   |
| Microsoft               | 1        | 12.5%   |
| Generalplus Technology  | 1        | 12.5%   |
| Creative Technology     | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Sirius USB2.0 Camera     | 1        | 12.5%   |
| Microsoft LifeCam HD-3000       | 1        | 12.5%   |
| Microdia USB 2.0 Camera         | 1        | 12.5%   |
| Microdia Integrated Camera      | 1        | 12.5%   |
| Logitech HD Webcam C615         | 1        | 12.5%   |
| Logitech BRIO 4K Stream Edition | 1        | 12.5%   |
| Generalplus GENERAL WEBCAM      | 1        | 12.5%   |
| Creative Live! Cam Sync 1080p   | 1        | 12.5%   |

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
| 0     | 30       | 88.24%  |
| 1     | 4        | 11.76%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 4        | 100%    |

