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

Total: 32

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ECS      | GeForce 8000 series         | [d436bb4acc](https://linux-hardware.org/?probe=d436bb4acc) | Dec 19, 2023 |
| MSI      | PRO H410M-B                 | [0729c86d23](https://linux-hardware.org/?probe=0729c86d23) | Dec 15, 2023 |
| ASUSTek  | PRIME B450-PLUS             | [7e201ea559](https://linux-hardware.org/?probe=7e201ea559) | Dec 11, 2023 |
| ASUSTek  | PRIME A320M-K               | [5f06f30bd3](https://linux-hardware.org/?probe=5f06f30bd3) | Nov 09, 2023 |
| MSI      | MPG Z390 GAMING PRO CARB... | [414894f4aa](https://linux-hardware.org/?probe=414894f4aa) | Nov 08, 2023 |
| ASUSTek  | PRIME A320M-K               | [3fb2d2a6f0](https://linux-hardware.org/?probe=3fb2d2a6f0) | Nov 06, 2023 |
| MSI      | X570-A PRO                  | [78df342ad3](https://linux-hardware.org/?probe=78df342ad3) | Oct 21, 2023 |
| Gigabyte | B560M AORUS PRO AX          | [5573fff3e6](https://linux-hardware.org/?probe=5573fff3e6) | Oct 17, 2023 |
| ASRock   | A520M-HVS                   | [0a29d5f7f6](https://linux-hardware.org/?probe=0a29d5f7f6) | Sep 22, 2023 |
| ASRock   | A520M-HVS                   | [2a7bf627ba](https://linux-hardware.org/?probe=2a7bf627ba) | Sep 19, 2023 |
| ASUSTek  | ROG STRIX Z590-A GAMING ... | [6d7c6c42f5](https://linux-hardware.org/?probe=6d7c6c42f5) | Sep 14, 2023 |
| ASUSTek  | ROG STRIX Z590-A GAMING ... | [fe64bd3017](https://linux-hardware.org/?probe=fe64bd3017) | Sep 13, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [376e22722b](https://linux-hardware.org/?probe=376e22722b) | Sep 05, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [388f380783](https://linux-hardware.org/?probe=388f380783) | Sep 02, 2023 |
| ASUSTek  | PRIME B450-PLUS             | [679cf99998](https://linux-hardware.org/?probe=679cf99998) | Aug 19, 2023 |
| ASUSTek  | PRIME B450-PLUS             | [cd3074537b](https://linux-hardware.org/?probe=cd3074537b) | Aug 15, 2023 |
| ASUSTek  | ROG STRIX B550-I GAMING     | [01846991de](https://linux-hardware.org/?probe=01846991de) | Aug 04, 2023 |
| ASUSTek  | PRIME B450-PLUS             | [fde0e0e94f](https://linux-hardware.org/?probe=fde0e0e94f) | Jul 29, 2023 |
| ASRock   | H170M Pro4                  | [818c9bc358](https://linux-hardware.org/?probe=818c9bc358) | Jun 14, 2023 |
| Lenovo   | 30D9 SDK0J40697 WIN 3305... | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| MSI      | PRO Z690-A WIFI DDR4        | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Gigabyte | H81M-HD3                    | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| Dell     | 051FJ8 A02                  | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek  | TUF Gaming H470-PRO         | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek  | TUF Gaming H470-PRO         | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [886aa04456](https://linux-hardware.org/?probe=886aa04456) | Mar 07, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [9088ef4d11](https://linux-hardware.org/?probe=9088ef4d11) | Mar 06, 2023 |
| ASUSTek  | P8H61-M LX                  | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| ASRock   | Z270M-ITX/ac                | [4f507f4e5a](https://linux-hardware.org/?probe=4f507f4e5a) | Feb 20, 2023 |
| ASUSTek  | PRIME H410M-K               | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| HP       | 2B34                        | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| HP       | 8906 SMVB                   | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| TUXEDO OS 22.04 | 25       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| TUXEDO OS | 25       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 6.2.0-10018-tuxedo  | 4        | 16%     |
| 6.1.0-1009-tuxedo   | 4        | 16%     |
| 6.5.0-10010-tuxedo  | 3        | 12%     |
| 6.2.0-10007-tuxedo  | 3        | 12%     |
| 5.15.0-10058-tuxedo | 3        | 12%     |
| 6.5.0-10006-tuxedo  | 2        | 8%      |
| 6.2.0-10027-tuxedo  | 2        | 8%      |
| 6.2.0-10022-tuxedo  | 2        | 8%      |
| 5.15.0-10057-tuxedo | 1        | 4%      |
| 5.15.0-10056-tuxedo | 1        | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 11       | 44%     |
| 6.5.0   | 5        | 20%     |
| 5.15.0  | 5        | 20%     |
| 6.1.0   | 4        | 16%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 11       | 44%     |
| 6.5     | 5        | 20%     |
| 5.15    | 5        | 20%     |
| 6.1     | 4        | 16%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 24       | 96%     |
| X-Cinnamon | 1        | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 22       | 88%     |
| Wayland | 3        | 12%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 92%     |
| SDDM    | 2        | 8%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| de_DE | 10       | 40%     |
| en_US | 6        | 24%     |
| en_ZA | 2        | 8%      |
| pt_PT | 1        | 4%      |
| pl_PL | 1        | 4%      |
| it_IT | 1        | 4%      |
| en_IN | 1        | 4%      |
| en_AG | 1        | 4%      |
| de_CH | 1        | 4%      |
| de_AT | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 23       | 92%     |
| EFI  | 2        | 8%      |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 21       | 80.77%  |
| Btrfs | 3        | 11.54%  |
| Xfs   | 2        | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 92%     |
| GPT     | 2        | 8%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 96%     |
| Yes       | 1        | 4%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 92%     |
| Yes       | 2        | 8%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 36%     |
| MSI                 | 6        | 24%     |
| ASRock              | 3        | 12%     |
| Hewlett-Packard     | 2        | 8%      |
| Gigabyte Technology | 2        | 8%      |
| Lenovo              | 1        | 4%      |
| ECS                 | 1        | 4%      |
| Dell                | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS PRIME B450-PLUS                 | 3        | 12%     |
| MSI MS-7D17                          | 2        | 8%      |
| MSI MS-7D82                          | 1        | 4%      |
| MSI MS-7D25                          | 1        | 4%      |
| MSI MS-7C37                          | 1        | 4%      |
| MSI MS-7B17                          | 1        | 4%      |
| Lenovo ThinkCentre M700 10GSS05X48   | 1        | 4%      |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 4%      |
| HP 280 G1 MT                         | 1        | 4%      |
| Gigabyte H81M-HD3                    | 1        | 4%      |
| Gigabyte B560M AORUS PRO AX          | 1        | 4%      |
| ECS GeForce 8000 series              | 1        | 4%      |
| Dell OptiPlex 9010                   | 1        | 4%      |
| ASUS TUF Gaming H470-PRO             | 1        | 4%      |
| ASUS ROG STRIX Z590-A GAMING WIFI    | 1        | 4%      |
| ASUS ROG STRIX B550-I GAMING         | 1        | 4%      |
| ASUS PRIME H410M-K                   | 1        | 4%      |
| ASUS PRIME A320M-K                   | 1        | 4%      |
| ASUS P8H61-M LX                      | 1        | 4%      |
| ASRock Z270M-ITX/ac                  | 1        | 4%      |
| ASRock H170M Pro4                    | 1        | 4%      |
| ASRock A520M-HVS                     | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 5        | 20%     |
| MSI MS-7D17        | 2        | 8%      |
| ASUS ROG           | 2        | 8%      |
| MSI MS-7D82        | 1        | 4%      |
| MSI MS-7D25        | 1        | 4%      |
| MSI MS-7C37        | 1        | 4%      |
| MSI MS-7B17        | 1        | 4%      |
| Lenovo ThinkCentre | 1        | 4%      |
| HP Pavilion        | 1        | 4%      |
| HP 280             | 1        | 4%      |
| Gigabyte H81M-HD3  | 1        | 4%      |
| Gigabyte B560M     | 1        | 4%      |
| ECS GeForce        | 1        | 4%      |
| Dell OptiPlex      | 1        | 4%      |
| ASUS TUF           | 1        | 4%      |
| ASUS P8H61-M       | 1        | 4%      |
| ASRock Z270M-ITX   | 1        | 4%      |
| ASRock H170M       | 1        | 4%      |
| ASRock A520M-HVS   | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 7        | 28%     |
| 2020 | 4        | 16%     |
| 2018 | 4        | 16%     |
| 2013 | 2        | 8%      |
| 2022 | 1        | 4%      |
| 2019 | 1        | 4%      |
| 2017 | 1        | 4%      |
| 2016 | 1        | 4%      |
| 2015 | 1        | 4%      |
| 2014 | 1        | 4%      |
| 2011 | 1        | 4%      |
| 2008 | 1        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 25       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 25       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 7        | 28%     |
| 32.01-64.0  | 6        | 24%     |
| 3.01-4.0    | 4        | 16%     |
| 4.01-8.0    | 3        | 12%     |
| 8.01-16.0   | 3        | 12%     |
| 24.01-32.0  | 1        | 4%      |
| 64.01-256.0 | 1        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 8        | 30.77%  |
| 1.01-2.0  | 7        | 26.92%  |
| 4.01-8.0  | 5        | 19.23%  |
| 3.01-4.0  | 3        | 11.54%  |
| 8.01-16.0 | 3        | 11.54%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 36%     |
| 4      | 7        | 28%     |
| 1      | 4        | 16%     |
| 5      | 3        | 12%     |
| 6      | 1        | 4%      |
| 3      | 1        | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 68%     |
| Yes       | 8        | 32%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 96%     |
| No        | 1        | 4%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 60%     |
| No        | 10       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 50%     |
| No        | 13       | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 11       | 44%     |
| South Africa | 2        | 8%      |
| Italy        | 2        | 8%      |
| USA          | 1        | 4%      |
| Switzerland  | 1        | 4%      |
| Romania      | 1        | 4%      |
| Portugal     | 1        | 4%      |
| Poland       | 1        | 4%      |
| Netherlands  | 1        | 4%      |
| India        | 1        | 4%      |
| Egypt        | 1        | 4%      |
| Austria      | 1        | 4%      |
| Aruba        | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Hürth                    | 2        | 8%      |
| Zurich                    | 1        | 4%      |
| Zalău                    | 1        | 4%      |
| Vienna                    | 1        | 4%      |
| Ulm                       | 1        | 4%      |
| Stimpfach                 | 1        | 4%      |
| Quarteira                 | 1        | 4%      |
| Peitz                     | 1        | 4%      |
| Oranjestad                | 1        | 4%      |
| Offenbach                 | 1        | 4%      |
| Lublin                    | 1        | 4%      |
| Leipzig                   | 1        | 4%      |
| Johannesburg              | 1        | 4%      |
| Indore                    | 1        | 4%      |
| Frankfurt am Main         | 1        | 4%      |
| Florence                  | 1        | 4%      |
| Erding                    | 1        | 4%      |
| Eberswalde                | 1        | 4%      |
| Cairo                     | 1        | 4%      |
| Cagliari                  | 1        | 4%      |
| Bullhead City             | 1        | 4%      |
| Bloemfontein              | 1        | 4%      |
| Bad Neustadt an der Saale | 1        | 4%      |
| Amsterdam                 | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 11       | 18     | 18.64%  |
| Seagate                     | 9        | 14     | 15.25%  |
| WDC                         | 5        | 6      | 8.47%   |
| SanDisk                     | 5        | 7      | 8.47%   |
| Kingston                    | 3        | 3      | 5.08%   |
| Micron/Crucial Technology   | 2        | 4      | 3.39%   |
| Hitachi                     | 2        | 3      | 3.39%   |
| GOODRAM                     | 2        | 2      | 3.39%   |
| SPCC                        | 1        | 1      | 1.69%   |
| SK hynix                    | 1        | 1      | 1.69%   |
| Silicon Motion              | 1        | 2      | 1.69%   |
| Phison                      | 1        | 1      | 1.69%   |
| Netac                       | 1        | 1      | 1.69%   |
| Lite-On Technology          | 1        | 1      | 1.69%   |
| Kingston Technology Company | 1        | 1      | 1.69%   |
| KingFast                    | 1        | 1      | 1.69%   |
| Intenso                     | 1        | 1      | 1.69%   |
| HS-SSD-E100                 | 1        | 1      | 1.69%   |
| HS-SSD-E                    | 1        | 1      | 1.69%   |
| Hikvision                   | 1        | 2      | 1.69%   |
| HGST HTS                    | 1        | 1      | 1.69%   |
| HGST                        | 1        | 1      | 1.69%   |
| Crucial                     | 1        | 1      | 1.69%   |
| China                       | 1        | 1      | 1.69%   |
| ASMT                        | 1        | 1      | 1.69%   |
| Apacer                      | 1        | 1      | 1.69%   |
| AMD                         | 1        | 2      | 1.69%   |
| A-DATA Technology           | 1        | 2      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 980 500GB                               | 3        | 4.23%   |
| Seagate ST3500418AS 500GB                           | 2        | 2.82%   |
| Seagate ST1000VT001-1RE172 1TB                      | 2        | 2.82%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2        | 2.82%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 2        | 2.82%   |
| SanDisk SSD PLUS 120GB                              | 2        | 2.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 2.82%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2        | 2.82%   |
| Hitachi HCS545050GLA380 500GB                       | 2        | 2.82%   |
| WDC WD80EAZZ-00BKLB0 8TB                            | 1        | 1.41%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 1.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 1.41%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1        | 1.41%   |
| WDC WD10JPVX-11JC3T0 1TB                            | 1        | 1.41%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1        | 1.41%   |
| SPCC Solid State Disk 512GB                         | 1        | 1.41%   |
| SK hynix SHGP31-1000GM 1TB                          | 1        | 1.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB   | 1        | 1.41%   |
| Seagate ST500DM002-1BD142 500GB                     | 1        | 1.41%   |
| Seagate ST3500413AS 500GB                           | 1        | 1.41%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1        | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1        | 1.41%   |
| Seagate ST1000DX001-1NS162-SSHD 1TB                 | 1        | 1.41%   |
| Seagate ST10000NM001G-2MW103 10TB                   | 1        | 1.41%   |
| Sandisk WD_BLACK SN770 2TB                          | 1        | 1.41%   |
| Sandisk WD Black SN850 1024GB                       | 1        | 1.41%   |
| Samsung SSD 990 PRO 2TB                             | 1        | 1.41%   |
| Samsung SSD 980 1TB                                 | 1        | 1.41%   |
| Samsung SSD 870 EVO 2TB                             | 1        | 1.41%   |
| Samsung SSD 860 QVO 1TB                             | 1        | 1.41%   |
| Samsung SSD 860 PRO 1TB                             | 1        | 1.41%   |
| Samsung SSD 860 EVO 250GB                           | 1        | 1.41%   |
| Samsung SSD 860 EVO 1TB                             | 1        | 1.41%   |
| Samsung SSD 850 PRO 128GB                           | 1        | 1.41%   |
| Samsung SSD 850 EVO 500GB                           | 1        | 1.41%   |
| Samsung HD321KJ 320GB                               | 1        | 1.41%   |
| Samsung HD103UJ 1TB                                 | 1        | 1.41%   |
| Phison Sabrent Rocket Q4 2TB                        | 1        | 1.41%   |
| Netac SSD 120GB                                     | 1        | 1.41%   |
| Micron/Crucial CT1000P5PSSD8 1TB                    | 1        | 1.41%   |

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
| HGST                | 1        | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 26.32%  |
| SanDisk             | 2        | 3      | 10.53%  |
| Kingston            | 2        | 2      | 10.53%  |
| GOODRAM             | 2        | 2      | 10.53%  |
| SPCC                | 1        | 1      | 5.26%   |
| Netac               | 1        | 1      | 5.26%   |
| Intenso             | 1        | 1      | 5.26%   |
| Crucial             | 1        | 1      | 5.26%   |
| China               | 1        | 1      | 5.26%   |
| ASMT                | 1        | 1      | 5.26%   |
| Apacer              | 1        | 1      | 5.26%   |
| A-DATA Technology   | 1        | 2      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 17       | 27     | 34%     |
| NVMe    | 16       | 28     | 32%     |
| SSD     | 14       | 23     | 28%     |
| Unknown | 3        | 3      | 6%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 50     | 53.85%  |
| NVMe | 16       | 28     | 41.03%  |
| SAS  | 2        | 3      | 5.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 14       | 19     | 43.75%  |
| 0.01-0.5   | 13       | 25     | 40.63%  |
| 1.01-2.0   | 3        | 4      | 9.38%   |
| 4.01-10.0  | 2        | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 7        | 26.92%  |
| 251-500        | 4        | 15.38%  |
| 101-250        | 4        | 15.38%  |
| 1001-2000      | 4        | 15.38%  |
| More than 3000 | 2        | 7.69%   |
| 21-50          | 2        | 7.69%   |
| 2001-3000      | 2        | 7.69%   |
| 51-100         | 1        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 7        | 26.92%  |
| 1-20           | 6        | 23.08%  |
| 501-1000       | 4        | 15.38%  |
| 251-500        | 2        | 7.69%   |
| 101-250        | 2        | 7.69%   |
| 51-100         | 2        | 7.69%   |
| More than 3000 | 1        | 3.85%   |
| 2001-3000      | 1        | 3.85%   |
| 1001-2000      | 1        | 3.85%   |

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
| Detected | 23       | 73     | 88.46%  |
| Works    | 3        | 8      | 11.54%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 16       | 36.36%  |
| AMD                         | 8        | 18.18%  |
| Samsung Electronics         | 7        | 15.91%  |
| SanDisk                     | 3        | 6.82%   |
| Micron/Crucial Technology   | 2        | 4.55%   |
| Kingston Technology Company | 2        | 4.55%   |
| SK hynix                    | 1        | 2.27%   |
| Silicon Motion              | 1        | 2.27%   |
| Phison Electronics          | 1        | 2.27%   |
| Nvidia                      | 1        | 2.27%   |
| Lite-On Technology          | 1        | 2.27%   |
| ASMedia Technology          | 1        | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 11.11%  |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 9.26%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 7.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 7.41%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 3.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 3.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 1.85%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.85%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.85%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 1.85%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 1        | 1.85%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.85%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 1.85%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 1.85%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 1.85%   |
| Lite-On M9PeG, M9PeGN, M9PeY NVMe SSD                                                   | 1        | 1.85%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                                  | 1        | 1.85%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 1        | 1.85%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.85%   |
| AMD FCH SATA Controller [RAID Bottom]                                                   | 1        | 1.85%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 54.76%  |
| NVMe | 16       | 38.1%   |
| IDE  | 2        | 4.76%   |
| RAID | 1        | 2.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 64%     |
| AMD    | 9        | 36%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz         | 2        | 8%      |
| AMD Ryzen 5 5600G with Radeon Graphics   | 2        | 8%      |
| Intel Pentium CPU G3420 @ 3.20GHz        | 1        | 4%      |
| Intel Core i7-8700K CPU @ 3.70GHz        | 1        | 4%      |
| Intel Core i5-7600T CPU @ 2.80GHz        | 1        | 4%      |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1        | 4%      |
| Intel Core i5-10500 CPU @ 3.10GHz        | 1        | 4%      |
| Intel Core i5-10400F CPU @ 2.90GHz       | 1        | 4%      |
| Intel Core i5-10400 CPU @ 2.90GHz        | 1        | 4%      |
| Intel Core i3-6300 CPU @ 3.80GHz         | 1        | 4%      |
| Intel Core i3-6100 CPU @ 3.70GHz         | 1        | 4%      |
| Intel Core i3-10105F CPU @ 3.70GHz       | 1        | 4%      |
| Intel 12th Gen Core i9-12900KS           | 1        | 4%      |
| Intel 11th Gen Core i7-11700 @ 2.50GHz   | 1        | 4%      |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz | 1        | 4%      |
| Intel 11th Gen Core i5-11400T @ 1.30GHz  | 1        | 4%      |
| AMD Ryzen 7 5700G with Radeon Graphics   | 1        | 4%      |
| AMD Ryzen 7 3700X 8-Core Processor       | 1        | 4%      |
| AMD Ryzen 7 2700X Eight-Core Processor   | 1        | 4%      |
| AMD Ryzen 5 3600X 6-Core Processor       | 1        | 4%      |
| AMD Ryzen 5 1600 Six-Core Processor      | 1        | 4%      |
| AMD Ryzen 3 4100 4-Core Processor        | 1        | 4%      |
| AMD Phenom II X2 B59 Processor           | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 7        | 28%     |
| Other            | 4        | 16%     |
| AMD Ryzen 5      | 4        | 16%     |
| Intel Core i3    | 3        | 12%     |
| AMD Ryzen 7      | 3        | 12%     |
| Intel Pentium    | 1        | 4%      |
| Intel Core i7    | 1        | 4%      |
| AMD Ryzen 3      | 1        | 4%      |
| AMD Phenom II X2 | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 10       | 40%     |
| 4      | 6        | 24%     |
| 8      | 4        | 16%     |
| 2      | 4        | 16%     |
| 16     | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 76%     |
| 1      | 6        | 24%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 88%     |
| 0xa0653    | 1        | 4%      |
| 0x0a50000d | 1        | 4%      |
| 0x08701030 | 1        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| CometLake | 4        | 16%     |
| Unknown   | 4        | 16%     |
| Zen 3     | 3        | 12%     |
| Zen 2     | 3        | 12%     |
| Skylake   | 2        | 8%      |
| KabyLake  | 2        | 8%      |
| IvyBridge | 2        | 8%      |
| Haswell   | 2        | 8%      |
| Zen+      | 1        | 4%      |
| Zen       | 1        | 4%      |
| K10       | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 13       | 50%     |
| Intel  | 9        | 34.62%  |
| AMD    | 4        | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 11.11%  |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 11.11%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 7.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 7.41%   |
| Intel HD Graphics 530                                                       | 2        | 7.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 3.7%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 3.7%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 3.7%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 3.7%    |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 3.7%    |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.7%    |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 3.7%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 3.7%    |
| Intel HD Graphics 630                                                       | 1        | 3.7%    |
| Intel AlderLake-S GT1                                                       | 1        | 3.7%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 13       | 52%     |
| 1 x Intel  | 8        | 32%     |
| 1 x AMD    | 4        | 16%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 13       | 52%     |
| Proprietary | 12       | 48%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 56%     |
| 7.01-8.0   | 2        | 8%      |
| 5.01-6.0   | 2        | 8%      |
| 3.01-4.0   | 2        | 8%      |
| 1.01-2.0   | 2        | 8%      |
| 8.01-16.0  | 2        | 8%      |
| 0.01-0.5   | 1        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 30.77%  |
| Acer                | 5        | 19.23%  |
| Dell                | 3        | 11.54%  |
| Goldstar            | 2        | 7.69%   |
| BenQ                | 2        | 7.69%   |
| AOC                 | 2        | 7.69%   |
| ViewSonic           | 1        | 3.85%   |
| Philips             | 1        | 3.85%   |
| Hewlett-Packard     | 1        | 3.85%   |
| Eizo                | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                   | 2        | 6.45%   |
| Acer EK240Y ACR0758 1920x1080 520x320mm 24.0-inch                     | 2        | 6.45%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                      | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch   | 1        | 3.23%   |
| Samsung Electronics SMB1930HD SAM0708 1360x768 410x230mm 18.5-inch    | 1        | 3.23%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch     | 1        | 3.23%   |
| Samsung Electronics S24R35A SAM729F 1920x1080 527x296mm 23.8-inch     | 1        | 3.23%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 3.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 3.23%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1        | 3.23%   |
| Samsung Electronics LC27T55 SAM701E 1920x1080 609x349mm 27.6-inch     | 1        | 3.23%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1        | 3.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.23%   |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch                   | 1        | 3.23%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 1        | 3.23%   |
| Goldstar E2041 GSM4EC9 1600x900 443x249mm 20.0-inch                   | 1        | 3.23%   |
| Goldstar 24MB65 GSM5A4D 1920x1200 520x330mm 24.2-inch                 | 1        | 3.23%   |
| Eizo EV2736W ENC2383 2560x1440 597x336mm 27.0-inch                    | 1        | 3.23%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 1        | 3.23%   |
| Dell S2421HN DEL41F2 1920x1080 527x296mm 23.8-inch                    | 1        | 3.23%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                        | 1        | 3.23%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 1        | 3.23%   |
| AOC LCD Monitor 25G3ZM 3840x1080                                      | 1        | 3.23%   |
| AOC LCD Monitor 25G3ZM                                                | 1        | 3.23%   |
| AOC 2050W AOC2050 1600x900 432x240mm 19.5-inch                        | 1        | 3.23%   |
| Acer Z35 ACR0478 2560x1080 814x346mm 34.8-inch                        | 1        | 3.23%   |
| Acer VG270 ACR06C0 1920x1080 598x336mm 27.0-inch                      | 1        | 3.23%   |
| Acer QG241Y ACR079C 1920x1080 527x296mm 23.8-inch                     | 1        | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 13       | 50%     |
| 2560x1440 (QHD)   | 3        | 11.54%  |
| 1920x1200 (WUXGA) | 2        | 7.69%   |
| 1600x900 (HD+)    | 2        | 7.69%   |
| 3840x1080         | 1        | 3.85%   |
| 2560x1080         | 1        | 3.85%   |
| 1440x900 (WXGA+)  | 1        | 3.85%   |
| 1360x768          | 1        | 3.85%   |
| 1280x1024 (SXGA)  | 1        | 3.85%   |
| Unknown           | 1        | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 27.59%  |
| 27      | 7        | 24.14%  |
| 23      | 3        | 10.34%  |
| 20      | 2        | 6.9%    |
| Unknown | 2        | 6.9%    |
| 46      | 1        | 3.45%   |
| 34      | 1        | 3.45%   |
| 31      | 1        | 3.45%   |
| 21      | 1        | 3.45%   |
| 19      | 1        | 3.45%   |
| 18      | 1        | 3.45%   |
| 17      | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 57.69%  |
| 401-500     | 5        | 19.23%  |
| Unknown     | 2        | 7.69%   |
| 801-900     | 1        | 3.85%   |
| 601-700     | 1        | 3.85%   |
| 301-350     | 1        | 3.85%   |
| 1001-1500   | 1        | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 75%     |
| 16/10   | 3        | 12.5%   |
| 5/4     | 1        | 4.17%   |
| 21/9    | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 31.03%  |
| 301-350        | 7        | 24.14%  |
| 251-300        | 3        | 10.34%  |
| 151-200        | 3        | 10.34%  |
| 351-500        | 2        | 6.9%    |
| 141-150        | 2        | 6.9%    |
| Unknown        | 2        | 6.9%    |
| 501-1000       | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 72%     |
| 101-120 | 4        | 16%     |
| Unknown | 2        | 8%      |
| 1-50    | 1        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 72%     |
| 2     | 5        | 20%     |
| 3     | 2        | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 50%     |
| Intel                 | 12       | 35.29%  |
| TP-Link               | 1        | 2.94%   |
| Ralink Technology     | 1        | 2.94%   |
| Qualcomm Atheros      | 1        | 2.94%   |
| D-Link                | 1        | 2.94%   |
| Broadcom              | 1        | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 13       | 30.95%  |
| Intel Ethernet Controller I225-V                                      | 4        | 9.52%   |
| Intel Wi-Fi 6 AX200                                                   | 3        | 7.14%   |
| Realtek RTL8125 2.5GbE Controller                                     | 2        | 4.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 2        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                                  | 2        | 4.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                          | 1        | 2.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1        | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 1        | 2.38%   |
| Realtek 802.11ac NIC                                                  | 1        | 2.38%   |
| Ralink Airlink101 AWLL6070 802.11bgn Wireless Adapter [Ralink RT2770] | 1        | 2.38%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1        | 2.38%   |
| Intel Wireless-AC 9260                                                | 1        | 2.38%   |
| Intel Wireless 3160                                                   | 1        | 2.38%   |
| Intel I211 Gigabit Network Connection                                 | 1        | 2.38%   |
| Intel Ethernet Connection (7) I219-V                                  | 1        | 2.38%   |
| Intel Ethernet Connection (11) I219-V                                 | 1        | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                       | 1        | 2.38%   |
| Intel Alder Lake-S PCH CNVi WiFi                                      | 1        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 1        | 2.38%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]  | 1        | 2.38%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                        | 1        | 2.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 56.25%  |
| Realtek Semiconductor | 3        | 18.75%  |
| TP-Link               | 1        | 6.25%   |
| Ralink Technology     | 1        | 6.25%   |
| Qualcomm Atheros      | 1        | 6.25%   |
| D-Link                | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                   | 3        | 18.75%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 2        | 12.5%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                          | 1        | 6.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 1        | 6.25%   |
| Realtek 802.11ac NIC                                                  | 1        | 6.25%   |
| Ralink Airlink101 AWLL6070 802.11bgn Wireless Adapter [Ralink RT2770] | 1        | 6.25%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1        | 6.25%   |
| Intel Wireless-AC 9260                                                | 1        | 6.25%   |
| Intel Wireless 3160                                                   | 1        | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                       | 1        | 6.25%   |
| Intel Alder Lake-S PCH CNVi WiFi                                      | 1        | 6.25%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]  | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 60%     |
| Intel                 | 9        | 36%     |
| Broadcom              | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 50%     |
| Intel Ethernet Controller I225-V                                  | 4        | 15.38%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 7.69%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.85%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.85%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1        | 3.85%   |

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
| Ethernet | 18       | 69.23%  |
| WiFi     | 8        | 30.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 48%     |
| 2     | 10       | 40%     |
| 3     | 2        | 8%      |
| 0     | 1        | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 72%     |
| Yes  | 7        | 28%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 61.54%  |
| Cambridge Silicon Radio | 3        | 23.08%  |
| Realtek Semiconductor   | 1        | 7.69%   |
| Unknown                 | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 23.08%  |
| Intel AX210 Bluetooth                               | 2        | 15.38%  |
| Intel AX200 Bluetooth                               | 2        | 15.38%  |
| Realtek Bluetooth Radio                             | 1        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| Intel Bluetooth Device                              | 1        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.69%   |
| Unknown                                             | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 15       | 37.5%   |
| Nvidia              | 13       | 32.5%   |
| AMD                 | 7        | 17.5%   |
| Valve Software      | 1        | 2.5%    |
| Razer USA           | 1        | 2.5%    |
| JMTek               | 1        | 2.5%    |
| Creative Technology | 1        | 2.5%    |
| Creative Labs       | 1        | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                                              | 4        | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 4        | 8.33%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 3        | 6.25%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 2        | 4.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2        | 4.17%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 2        | 4.17%   |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 2        | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 4.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 4.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 2        | 4.17%   |
| Valve Software Valve VR Radio & HMD Mic                                                         | 1        | 2.08%   |
| Razer USA Razer Seiren Mini                                                                     | 1        | 2.08%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1        | 2.08%   |
| Nvidia TU102 High Definition Audio Controller                                                   | 1        | 2.08%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                       | 1        | 2.08%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 2.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 1        | 2.08%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1        | 2.08%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 2.08%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 1        | 2.08%   |
| JMTek SADES Audio Device                                                                        | 1        | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 2.08%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 1        | 2.08%   |
| Intel Comet Lake PCH cAVS                                                                       | 1        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                      | 1        | 2.08%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 1        | 2.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 1        | 2.08%   |
| Intel 200 Series PCH HD Audio                                                                   | 1        | 2.08%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                    | 1        | 2.08%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 1        | 2.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 1        | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Micron Technology | 1        | 25%     |
| KLEVV             | 1        | 25%     |
| Kingston          | 1        | 25%     |
| Crucial           | 1        | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s    | 1        | 25%     |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s     | 1        | 25%     |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 1        | 25%     |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s | 1        | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 3        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 3        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 2        | 66.67%  |
| 16384 | 1        | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3733  | 1        | 33.33%  |
| 3200  | 1        | 33.33%  |
| 2666  | 1        | 33.33%  |

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
| Valve Software                         | 1        | 14.29%  |
| Sunplus Innovation Technology          | 1        | 14.29%  |
| Sony Ericsson Mobile Communications AB | 1        | 14.29%  |
| Microdia                               | 1        | 14.29%  |
| Logitech                               | 1        | 14.29%  |
| Lenovo                                 | 1        | 14.29%  |
| KYE Systems (Mouse Systems)            | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Valve Software 3D Camera                  | 1        | 14.29%  |
| Sunplus SPCA2281 Web Camera               | 1        | 14.29%  |
| Sony Ericsson Mobile AB XQ-CC54           | 1        | 14.29%  |
| Microdia Sonix USB 2.0 Camera             | 1        | 14.29%  |
| Logitech HD Pro Webcam C920               | 1        | 14.29%  |
| Lenovo FHD Webcam                         | 1        | 14.29%  |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 14.29%  |

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
| 0     | 22       | 88%     |
| 1     | 3        | 12%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 1        | 33.33%  |
| Graphics card | 1        | 33.33%  |
| Camera        | 1        | 33.33%  |

