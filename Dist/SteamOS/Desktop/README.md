SteamOS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for SteamOS.

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

Total: 30

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | PRIME A320M-K           | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| MSI       | MS-B9201                | [b5c80c8c2c](https://linux-hardware.org/?probe=b5c80c8c2c) | Aug 29, 2022 |
| Gigabyte  | B550 AORUS ELITE AX V2  | [9e3df56c3b](https://linux-hardware.org/?probe=9e3df56c3b) | Aug 28, 2022 |
| ASUSTek   | PRIME B550-PLUS         | [67b791eb17](https://linux-hardware.org/?probe=67b791eb17) | Aug 25, 2022 |
| ASUSTek   | H97-PRO GAMER           | [663bc0a517](https://linux-hardware.org/?probe=663bc0a517) | Aug 25, 2022 |
| ASUSTek   | H97-PRO GAMER           | [e934af2a60](https://linux-hardware.org/?probe=e934af2a60) | Aug 23, 2022 |
| Gigabyte  | AB350-Gaming 3-CF       | [9661c799c9](https://linux-hardware.org/?probe=9661c799c9) | Aug 18, 2022 |
| Gigabyte  | X570 GAMING X           | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| ASUSTek   | TUF Gaming X570-PLUS    | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| MSI       | MS-B9351                | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI       | MS-B9351                | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| MSI       | B450 TOMAHAWK MAX II    | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| ASUSTek   | SABERTOOTH X99          | [54ea6926a0](https://linux-hardware.org/?probe=54ea6926a0) | Aug 13, 2022 |
| Dell      | 00F82W A00              | [8e74c57731](https://linux-hardware.org/?probe=8e74c57731) | Aug 07, 2022 |
| Gigabyte  | H310M S2V               | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| ASRock    | A520M-ITX/ac            | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| ASRock    | B450M-HDV R4.0          | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| ASUSTek   | EX-A320M-GAMING         | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Gigabyte  | H170N-WIFI-CF           | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| Gigabyte  | B550 GAMING X V2        | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte  | B550 GAMING X V2        | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Gigabyte  | X570 I AORUS PRO WIFI   | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Alienware | 02XRCM A01              | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| ASUSTek   | H61M-K                  | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek   | ROG STRIX B550-F GAMING | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock    | B550 PG Velocita        | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock    | B365M Pro4-F            | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte  | B560M AORUS PRO         | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte  | B560M AORUS PRO         | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Gigabyte  | Z170XP-SLI-CF           | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| SteamOS 3.3                  | 13       | 52%     |
| SteamOS 3.2 (steamdeck-main) | 7        | 28%     |
| SteamOS Snapshot             | 3        | 12%     |
| SteamOS 3.2                  | 1        | 4%      |
| SteamOS                      | 1        | 4%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SteamOS | 25       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 11       | 44%     |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 7        | 28%     |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 2        | 8%      |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2        | 8%      |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 1        | 4%      |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1        | 4%      |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 1        | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 24       | 96%     |
| 5.18.1  | 1        | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 24       | 96%     |
| 5.18    | 1        | 4%      |

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


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 25       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 25       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 20       | 80%     |
| pt_PT | 1        | 4%      |
| fr_FR | 1        | 4%      |
| en_IE | 1        | 4%      |
| en_GB | 1        | 4%      |
| C     | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 25       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 25       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 32%     |
| ASUSTek Computer    | 8        | 32%     |
| ASRock              | 4        | 16%     |
| MSI                 | 3        | 12%     |
| Dell                | 1        | 4%      |
| Alienware           | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 2        | 8%      |
| MSI MS-7C02                        | 1        | 4%      |
| MSI MPG H510 Trident 3 (MS-B935)   | 1        | 4%      |
| MSI H310 Gaming Trident3 (MS-B920) | 1        | 4%      |
| Gigabyte X570 I AORUS PRO WIFI     | 1        | 4%      |
| Gigabyte X570 GAMING X             | 1        | 4%      |
| Gigabyte MBB-670016                | 1        | 4%      |
| Gigabyte H310M S2V 2.0             | 1        | 4%      |
| Gigabyte H170N-WIFI                | 1        | 4%      |
| Gigabyte B560M AORUS PRO           | 1        | 4%      |
| Gigabyte B550 GAMING X V2          | 1        | 4%      |
| Gigabyte AB350-Gaming 3            | 1        | 4%      |
| Dell OptiPlex 9010                 | 1        | 4%      |
| ASUS TUF Gaming X570-PLUS          | 1        | 4%      |
| ASUS ROG STRIX B550-F GAMING       | 1        | 4%      |
| ASUS PRIME B550-PLUS               | 1        | 4%      |
| ASUS PRIME A320M-K                 | 1        | 4%      |
| ASUS H61M-K                        | 1        | 4%      |
| ASUS EX-A320M-GAMING               | 1        | 4%      |
| ASRock B550 PG Velocita            | 1        | 4%      |
| ASRock B450M-HDV R4.0              | 1        | 4%      |
| ASRock B365M Pro4-F                | 1        | 4%      |
| ASRock A520M-ITX/ac                | 1        | 4%      |
| Alienware Aurora R8                | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Gigabyte X570         | 2        | 8%      |
| ASUS PRIME            | 2        | 8%      |
| ASUS All              | 2        | 8%      |
| MSI MS-7C02           | 1        | 4%      |
| MSI MPG               | 1        | 4%      |
| MSI H310              | 1        | 4%      |
| Gigabyte MBB-670016   | 1        | 4%      |
| Gigabyte H310M        | 1        | 4%      |
| Gigabyte H170N-WIFI   | 1        | 4%      |
| Gigabyte B560M        | 1        | 4%      |
| Gigabyte B550         | 1        | 4%      |
| Gigabyte AB350-Gaming | 1        | 4%      |
| Dell OptiPlex         | 1        | 4%      |
| ASUS TUF              | 1        | 4%      |
| ASUS ROG              | 1        | 4%      |
| ASUS H61M-K           | 1        | 4%      |
| ASUS EX-A320M-GAMING  | 1        | 4%      |
| ASRock B550           | 1        | 4%      |
| ASRock B450M-HDV      | 1        | 4%      |
| ASRock B365M          | 1        | 4%      |
| ASRock A520M-ITX      | 1        | 4%      |
| Alienware Aurora      | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 8        | 32%     |
| 2019 | 5        | 20%     |
| 2018 | 4        | 16%     |
| 2021 | 2        | 8%      |
| 2013 | 2        | 8%      |
| 2022 | 1        | 4%      |
| 2017 | 1        | 4%      |
| 2016 | 1        | 4%      |
| 2014 | 1        | 4%      |

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
| 16.01-24.0  | 14       | 56%     |
| 32.01-64.0  | 6        | 24%     |
| 8.01-16.0   | 2        | 8%      |
| 4.01-8.0    | 1        | 4%      |
| 24.01-32.0  | 1        | 4%      |
| 64.01-256.0 | 1        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 12       | 48%     |
| 3.01-4.0 | 7        | 28%     |
| 4.01-8.0 | 4        | 16%     |
| 1.01-2.0 | 2        | 8%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 32%     |
| 3      | 7        | 28%     |
| 2      | 7        | 28%     |
| 4      | 2        | 8%      |
| 7      | 1        | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 92%     |
| Yes       | 2        | 8%      |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 100%    |

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
| Yes       | 13       | 52%     |
| No        | 12       | 48%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 7        | 28%     |
| UK        | 4        | 16%     |
| Australia | 3        | 12%     |
| France    | 2        | 8%      |
| Turkey    | 1        | 4%      |
| Spain     | 1        | 4%      |
| Portugal  | 1        | 4%      |
| Poland    | 1        | 4%      |
| Oman      | 1        | 4%      |
| Ireland   | 1        | 4%      |
| Hong Kong | 1        | 4%      |
| Canada    | 1        | 4%      |
| Cambodia  | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Walsall                 | 1        | 4%      |
| Vilas                   | 1        | 4%      |
| Tuam                    | 1        | 4%      |
| Sterling Heights        | 1        | 4%      |
| Skarzysko-Kamienna      | 1        | 4%      |
| Phnom Penh              | 1        | 4%      |
| Perth                   | 1        | 4%      |
| Paris                   | 1        | 4%      |
| Norwich                 | 1        | 4%      |
| Noble Park              | 1        | 4%      |
| Muscat                  | 1        | 4%      |
| Mascot                  | 1        | 4%      |
| Lisbon                  | 1        | 4%      |
| Langley                 | 1        | 4%      |
| Ivry-sur-Seine          | 1        | 4%      |
| Istanbul                | 1        | 4%      |
| Hornsea                 | 1        | 4%      |
| Henderson               | 1        | 4%      |
| Detroit                 | 1        | 4%      |
| Dallas                  | 1        | 4%      |
| Corning                 | 1        | 4%      |
| Chiclana de la Frontera | 1        | 4%      |
| Central                 | 1        | 4%      |
| Buffalo                 | 1        | 4%      |
| Bexleyheath             | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 8        | 10     | 16.67%  |
| Samsung Electronics       | 8        | 13     | 16.67%  |
| WDC                       | 5        | 6      | 10.42%  |
| Toshiba                   | 3        | 5      | 6.25%   |
| SanDisk                   | 3        | 3      | 6.25%   |
| Phison                    | 3        | 3      | 6.25%   |
| Realtek Semiconductor     | 2        | 2      | 4.17%   |
| PNY                       | 2        | 2      | 4.17%   |
| Micron/Crucial Technology | 2        | 2      | 4.17%   |
| Kingston                  | 2        | 2      | 4.17%   |
| Crucial                   | 2        | 2      | 4.17%   |
| A-DATA Technology         | 2        | 2      | 4.17%   |
| Union Memory (Shenzhen)   | 1        | 1      | 2.08%   |
| SK hynix                  | 1        | 1      | 2.08%   |
| HS-SSD-C100               | 1        | 1      | 2.08%   |
| GALAX                     | 1        | 1      | 2.08%   |
| China                     | 1        | 1      | 2.08%   |
| Unknown                   | 1        | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                   | 3        | 5.36%   |
| Realtek NVMe SSD Drive 256GB                 | 2        | 3.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1        | 1.79%   |
| WDC WDBNCE0010PNC 1TB SSD                    | 1        | 1.79%   |
| WDC WD7500BPVT-80HXZT3 752GB                 | 1        | 1.79%   |
| WDC WD5000BPKT-60PK4T0 500GB                 | 1        | 1.79%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1        | 1.79%   |
| WDC WD10EURX-83UY4Y0 1TB                     | 1        | 1.79%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1        | 1.79%   |
| Toshiba MQ01ABD100 1TB                       | 1        | 1.79%   |
| Toshiba MK3275GSX 320GB                      | 1        | 1.79%   |
| Toshiba HDWD130 3TB                          | 1        | 1.79%   |
| Toshiba DT01ACA200 2TB                       | 1        | 1.79%   |
| SK hynix NVMe SSD Drive 256GB                | 1        | 1.79%   |
| Seagate ST9320325AS 320GB                    | 1        | 1.79%   |
| Seagate ST6000DM003-2CY186 6TB               | 1        | 1.79%   |
| Seagate ST4000DX001-1CE168 4TB               | 1        | 1.79%   |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 1.79%   |
| Seagate ST3500413AS 500GB                    | 1        | 1.79%   |
| Seagate ST3500312CS 500GB                    | 1        | 1.79%   |
| Seagate ST3160318AS 160GB                    | 1        | 1.79%   |
| Seagate ST2000DM008-2FR102 2TB               | 1        | 1.79%   |
| Seagate ST1000LM049-2GH172 1TB               | 1        | 1.79%   |
| Seagate ST1000LM014-1EJ164 1TB               | 1        | 1.79%   |
| SanDisk X400 M.2 2280 128GB SSD              | 1        | 1.79%   |
| SanDisk NVMe SSD Drive 500GB                 | 1        | 1.79%   |
| SanDisk NVMe SSD Drive 2TB                   | 1        | 1.79%   |
| Samsung SSD 860 EVO 500GB                    | 1        | 1.79%   |
| Samsung SSD 860 EVO 250GB                    | 1        | 1.79%   |
| Samsung SSD 850 EVO mSATA 500GB              | 1        | 1.79%   |
| Samsung SSD 850 EVO 250GB                    | 1        | 1.79%   |
| Samsung SSD 840 Series 120GB                 | 1        | 1.79%   |
| Samsung SSD 840 EVO 250GB                    | 1        | 1.79%   |
| Samsung NVMe SSD Drive 512GB                 | 1        | 1.79%   |
| Samsung NVMe SSD Drive 250GB                 | 1        | 1.79%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD         | 1        | 1.79%   |
| PNY CS900 120GB SSD                          | 1        | 1.79%   |
| PNY CS1311 240GB SSD                         | 1        | 1.79%   |
| Phison NVMe SSD Drive 2TB                    | 1        | 1.79%   |
| Phison NVMe SSD Drive 250GB                  | 1        | 1.79%   |
| Phison NVMe SSD Drive 1024GB                 | 1        | 1.79%   |
| Micron/Crucial NVMe SSD Drive 2TB            | 1        | 1.79%   |
| Micron/Crucial NVMe SSD Drive 1TB            | 1        | 1.79%   |
| Kingston SA400S37240G 240GB SSD              | 1        | 1.79%   |
| Kingston SA400M8120G 120GB SSD               | 1        | 1.79%   |
| HS-SSD-C100 240G                             | 1        | 1.79%   |
| GALAX TA1D0120N 120GB                        | 1        | 1.79%   |
| Crucial CT525MX300SSD1 528GB                 | 1        | 1.79%   |
| Crucial CT1000BX500SSD1 1TB                  | 1        | 1.79%   |
| China SSD 120GB                              | 1        | 1.79%   |
| A-DATA SU650 240GB SSD                       | 1        | 1.79%   |
| A-DATA SU630 240GB SSD                       | 1        | 1.79%   |
| Unknown                                      | 1        | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 8        | 10     | 57.14%  |
| WDC     | 3        | 4      | 21.43%  |
| Toshiba | 3        | 5      | 21.43%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 7      | 33.33%  |
| WDC                 | 2        | 2      | 11.11%  |
| PNY                 | 2        | 2      | 11.11%  |
| Kingston            | 2        | 2      | 11.11%  |
| Crucial             | 2        | 2      | 11.11%  |
| A-DATA Technology   | 2        | 2      | 11.11%  |
| SanDisk             | 1        | 1      | 5.56%   |
| China               | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 15       | 17     | 33.33%  |
| SSD     | 15       | 19     | 33.33%  |
| HDD     | 12       | 19     | 26.67%  |
| Unknown | 3        | 3      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 41     | 58.33%  |
| NVMe | 15       | 17     | 41.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 22     | 51.72%  |
| 0.51-1.0   | 8        | 9      | 27.59%  |
| 3.01-4.0   | 2        | 2      | 6.9%    |
| 1.01-2.0   | 2        | 2      | 6.9%    |
| 2.01-3.0   | 1        | 2      | 3.45%   |
| 4.01-10.0  | 1        | 1      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 40%     |
| 501-1000       | 6        | 24%     |
| 1001-2000      | 4        | 16%     |
| 251-500        | 3        | 12%     |
| More than 3000 | 2        | 8%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 13       | 52%     |
| 51-100    | 7        | 28%     |
| 21-50     | 3        | 12%     |
| 2001-3000 | 1        | 4%      |
| 101-250   | 1        | 4%      |

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
| Detected | 25       | 58     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 13       | 33.33%  |
| Intel                     | 11       | 28.21%  |
| Samsung Electronics       | 4        | 10.26%  |
| Phison Electronics        | 3        | 7.69%   |
| SanDisk                   | 2        | 5.13%   |
| Realtek Semiconductor     | 2        | 5.13%   |
| Micron/Crucial Technology | 2        | 5.13%   |
| Union Memory (Shenzhen)   | 1        | 2.56%   |
| SK hynix                  | 1        | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 9        | 19.57%  |
| AMD 500 Series Chipset SATA Controller                                        | 5        | 10.87%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3        | 6.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3        | 6.52%   |
| Phison Electronics Non-Volatile memory controller                             | 2        | 4.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 4.35%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 4.35%   |
| AMD FCH SATA Controller D                                                     | 2        | 4.35%   |
| AMD 400 Series Chipset SATA Controller                                        | 2        | 4.35%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 1        | 2.17%   |
| SK hynix Non-Volatile memory controller                                       | 1        | 2.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1        | 2.17%   |
| SanDisk Non-Volatile memory controller                                        | 1        | 2.17%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1        | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 2.17%   |
| Realtek RTS5763DL NVMe SSD Controller                                         | 1        | 2.17%   |
| Realtek Realtek Non-Volatile memory controller                                | 1        | 2.17%   |
| Phison E12 NVMe Controller                                                    | 1        | 2.17%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1        | 2.17%   |
| Micron/Crucial Non-Volatile memory controller                                 | 1        | 2.17%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 2.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1        | 2.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1        | 2.17%   |
| AMD 300 Series Chipset SATA Controller                                        | 1        | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 58.97%  |
| NVMe | 15       | 38.46%  |
| RAID | 1        | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 52%     |
| Intel  | 12       | 48%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor        | 2        | 8%      |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz        | 1        | 4%      |
| Intel Core i7-8700 CPU @ 3.20GHz           | 1        | 4%      |
| Intel Core i7-6700K CPU @ 4.00GHz          | 1        | 4%      |
| Intel Core i5-9400 CPU @ 2.90GHz           | 1        | 4%      |
| Intel Core i5-8500T CPU @ 2.10GHz          | 1        | 4%      |
| Intel Core i5-6600 CPU @ 3.30GHz           | 1        | 4%      |
| Intel Core i5-4590 CPU @ 3.30GHz           | 1        | 4%      |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1        | 4%      |
| Intel Core i5-2400 CPU @ 3.10GHz           | 1        | 4%      |
| Intel Core i3-9100F CPU @ 3.60GHz          | 1        | 4%      |
| Intel 11th Gen Core i7-11700F @ 2.50GHz    | 1        | 4%      |
| Intel 11th Gen Core i5-11400F @ 2.60GHz    | 1        | 4%      |
| AMD Ryzen 9 5900X 12-Core Processor        | 1        | 4%      |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 4%      |
| AMD Ryzen 7 5700G with Radeon Graphics     | 1        | 4%      |
| AMD Ryzen 7 3700X 8-Core Processor         | 1        | 4%      |
| AMD Ryzen 7 2700 Eight-Core Processor      | 1        | 4%      |
| AMD Ryzen 7 1700X Eight-Core Processor     | 1        | 4%      |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 4%      |
| AMD Ryzen 5 3600X 6-Core Processor         | 1        | 4%      |
| AMD Ryzen 5 2600X Six-Core Processor       | 1        | 4%      |
| AMD Ryzen 5 1600 Six-Core Processor        | 1        | 4%      |
| AMD Athlon 3000G with Radeon Vega Graphics | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i5 | 6        | 24%     |
| AMD Ryzen 7   | 5        | 20%     |
| AMD Ryzen 5   | 4        | 16%     |
| AMD Ryzen 9   | 3        | 12%     |
| Other         | 2        | 8%      |
| Intel Core i7 | 2        | 8%      |
| Intel Xeon    | 1        | 4%      |
| Intel Core i3 | 1        | 4%      |
| AMD Athlon    | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 8        | 32%     |
| 4      | 7        | 28%     |
| 8      | 6        | 24%     |
| 12     | 3        | 12%     |
| 2      | 1        | 4%      |

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
| 2      | 18       | 72%     |
| 1      | 7        | 28%     |

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


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 4        | 16%     |
| Zen 3       | 4        | 16%     |
| Zen 2       | 4        | 16%     |
| KabyLake    | 4        | 16%     |
| Skylake     | 2        | 8%      |
| Haswell     | 2        | 8%      |
| Unknown     | 2        | 8%      |
| Zen         | 1        | 4%      |
| SandyBridge | 1        | 4%      |
| IvyBridge   | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 17       | 58.62%  |
| Nvidia | 7        | 24.14%  |
| Intel  | 5        | 17.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 17.24%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 10.34%  |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 10.34%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 6.9%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 6.9%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 6.9%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 6.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.45%   |
| Intel HD Graphics 530                                                       | 1        | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 3.45%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 3.45%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 3.45%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x AMD    | 17       | 68%     |
| 1 x Nvidia | 7        | 28%     |
| 1 x Intel  | 1        | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 18       | 72%     |
| Proprietary | 7        | 28%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 72%     |
| 3.01-4.0   | 5        | 20%     |
| 5.01-6.0   | 2        | 8%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 4        | 15.38%  |
| Philips              | 3        | 11.54%  |
| Dell                 | 3        | 11.54%  |
| Acer                 | 3        | 11.54%  |
| Sony                 | 2        | 7.69%   |
| Goldstar             | 2        | 7.69%   |
| ASUSTek Computer     | 2        | 7.69%   |
| ___                  | 1        | 3.85%   |
| ViewSonic            | 1        | 3.85%   |
| Unknown              | 1        | 3.85%   |
| Sceptre Tech         | 1        | 3.85%   |
| HannStar             | 1        | 3.85%   |
| DZX                  | 1        | 3.85%   |
| Ancor Communications | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 3.85%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1        | 3.85%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1        | 3.85%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 3.85%   |
| Sony TV *00 SNY8204 3840x2160 1218x685mm 55.0-inch                    | 1        | 3.85%   |
| Sceptre Tech Sceptre E22 SPT08D5 1920x1080 470x300mm 22.0-inch        | 1        | 3.85%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch     | 1        | 3.85%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 890x500mm 40.2-inch | 1        | 3.85%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 1        | 3.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1        | 3.85%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 3.85%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 3.85%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                    | 1        | 3.85%   |
| HannStar HF289H HSD190B 1920x1200 610x350mm 27.7-inch                 | 1        | 3.85%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 1        | 3.85%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 1        | 3.85%   |
| DZX K3-1 DZX1581 1920x1080 350x190mm 15.7-inch                        | 1        | 3.85%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 1        | 3.85%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                     | 1        | 3.85%   |
| Dell E2420H DELF11B 1920x1080 527x296mm 23.8-inch                     | 1        | 3.85%   |
| ASUSTek Computer VP248 AUS24CB 1920x1080 531x299mm 24.0-inch          | 1        | 3.85%   |
| ASUSTek Computer VG32VQ1B AUS32E0 2560x1440 697x392mm 31.5-inch       | 1        | 3.85%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 1        | 3.85%   |
| Acer VG270U ACR06C9 2560x1440 600x340mm 27.2-inch                     | 1        | 3.85%   |
| Acer VG240Y S ACR0750 1920x1080 527x296mm 23.8-inch                   | 1        | 3.85%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                     | 1        | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 14       | 58.33%  |
| 2560x1440 (QHD)   | 3        | 12.5%   |
| 3840x2160 (4K)    | 2        | 8.33%   |
| 3840x1080         | 1        | 4.17%   |
| 1920x1200 (WUXGA) | 1        | 4.17%   |
| 1440x900 (WXGA+)  | 1        | 4.17%   |
| 1366x768 (WXGA)   | 1        | 4.17%   |
| 1360x768          | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 6        | 25%     |
| 72      | 3        | 12.5%   |
| 27      | 3        | 12.5%   |
| 48      | 2        | 8.33%   |
| 31      | 2        | 8.33%   |
| 24      | 2        | 8.33%   |
| 21      | 2        | 8.33%   |
| 65      | 1        | 4.17%   |
| 18      | 1        | 4.17%   |
| 15      | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 41.67%  |
| 601-700     | 3        | 12.5%   |
| 401-500     | 3        | 12.5%   |
| 1501-2000   | 3        | 12.5%   |
| 1001-1500   | 3        | 12.5%   |
| 301-350     | 1        | 4.17%   |
| Unknown     | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 21       | 95.45%  |
| 32/9  | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 41.67%  |
| More than 1000 | 5        | 20.83%  |
| 301-350        | 3        | 12.5%   |
| 351-500        | 2        | 8.33%   |
| 141-150        | 1        | 4.17%   |
| 101-110        | 1        | 4.17%   |
| 501-1000       | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 66.67%  |
| 1-50    | 3        | 12.5%   |
| 101-120 | 3        | 12.5%   |
| 121-160 | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 84%     |
| 2     | 4        | 16%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 14       | 38.89%  |
| Intel                         | 13       | 36.11%  |
| Broadcom                      | 2        | 5.56%   |
| TP-Link                       | 1        | 2.78%   |
| Samsung Electronics           | 1        | 2.78%   |
| Qualcomm Atheros              | 1        | 2.78%   |
| OnePlus Technology (Shenzhen) | 1        | 2.78%   |
| Microsoft                     | 1        | 2.78%   |
| Huawei Technologies           | 1        | 2.78%   |
| Google                        | 1        | 2.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 26.09%  |
| Intel Wi-Fi 6 AX200                                               | 4        | 8.7%    |
| Intel Ethernet Connection (2) I219-V                              | 4        | 8.7%    |
| Intel Ethernet Controller I225-V                                  | 3        | 6.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.35%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 4.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 2.17%   |
| Realtek 802.11ac NIC                                              | 1        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.17%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 2.17%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.17%   |
| Intel Wireless 8260                                               | 1        | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.17%   |
| Huawei JNY-LX1                                                    | 1        | 2.17%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 53.33%  |
| Realtek Semiconductor | 2        | 13.33%  |
| Broadcom              | 2        | 13.33%  |
| TP-Link               | 1        | 6.67%   |
| Qualcomm Atheros      | 1        | 6.67%   |
| Microsoft             | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 4        | 26.67%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 2        | 13.33%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 6.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 6.67%   |
| Realtek 802.11ac NIC                                       | 1        | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 6.67%   |
| Microsoft Xbox 360 Wireless Adapter                        | 1        | 6.67%   |
| Intel Wireless 8260                                        | 1        | 6.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 14       | 46.67%  |
| Intel                         | 11       | 36.67%  |
| Samsung Electronics           | 1        | 3.33%   |
| Qualcomm Atheros              | 1        | 3.33%   |
| OnePlus Technology (Shenzhen) | 1        | 3.33%   |
| Huawei Technologies           | 1        | 3.33%   |
| Google                        | 1        | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 38.71%  |
| Intel Ethernet Connection (2) I219-V                              | 4        | 12.9%   |
| Intel Ethernet Controller I225-V                                  | 3        | 9.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 6.45%   |
| Intel I211 Gigabit Network Connection                             | 2        | 6.45%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 6.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 3.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 3.23%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.23%   |
| Huawei JNY-LX1                                                    | 1        | 3.23%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 62.5%   |
| WiFi     | 15       | 37.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 80.77%  |
| WiFi     | 5        | 19.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 52%     |
| 2     | 11       | 44%     |
| 3     | 1        | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 80%     |
| Yes  | 5        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 61.54%  |
| TP-Link                         | 1        | 7.69%   |
| Qualcomm Atheros Communications | 1        | 7.69%   |
| Integrated System Solution      | 1        | 7.69%   |
| Cambridge Silicon Radio         | 1        | 7.69%   |
| Broadcom                        | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 4        | 30.77%  |
| TP-Link UB500 Adapter                                 | 1        | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 7.69%   |
| Intel Bluetooth wireless interface                    | 1        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 7.69%   |
| Intel AX210 Bluetooth                                 | 1        | 7.69%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 20       | 40.82%  |
| Intel               | 12       | 24.49%  |
| Nvidia              | 7        | 14.29%  |
| Logitech            | 2        | 4.08%   |
| Tenx Technology     | 1        | 2.04%   |
| SteelSeries ApS     | 1        | 2.04%   |
| Quanta              | 1        | 2.04%   |
| Kingston Technology | 1        | 2.04%   |
| Creative Labs       | 1        | 2.04%   |
| Corsair             | 1        | 2.04%   |
| C-Media Electronics | 1        | 2.04%   |
| Apple               | 1        | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 11.48%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 9.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 8.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 6.56%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 4.92%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 4.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 3.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 3.28%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 3.28%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 3.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 3.28%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 3.28%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.64%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1        | 1.64%   |
| Quanta USB Audio                                                           | 1        | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.64%   |
| Logitech PRO X                                                             | 1        | 1.64%   |
| Logitech Blue Microphones                                                  | 1        | 1.64%   |
| Kingston Technology HyperX Cloud Alpha S                                   | 1        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.64%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.64%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.64%   |
| Corsair VOID ELITE Wireless Gaming Dongle                                  | 1        | 1.64%   |
| C-Media Electronics Blue Snowball                                          | 1        | 1.64%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 1        | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.64%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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
| Sunplus Innovation Technology | 1        | 25%     |
| Quanta                        | 1        | 25%     |
| Magic Control Technology      | 1        | 25%     |
| Apple                         | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus USB 2.0 Camera          | 1        | 25%     |
| Quanta HD Camera                | 1        | 25%     |
| Magic Control j5 WebCam JVCU100 | 1        | 25%     |
| Apple iPhone 5/5C/5S/6/SE       | 1        | 25%     |

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
| 0     | 21       | 84%     |
| 1     | 4        | 16%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 60%     |
| Unassigned class | 1        | 20%     |
| Net/ethernet     | 1        | 20%     |

