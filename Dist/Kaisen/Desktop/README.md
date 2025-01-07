Kaisen - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Kaisen.

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

Total: 20

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Pegatron | Benicia                     | [a4f82b02e6](https://linux-hardware.org/?probe=a4f82b02e6) | Nov 07, 2024 |
| ASUSTek  | PRIME B450M-GAMING II       | [43ae0c9603](https://linux-hardware.org/?probe=43ae0c9603) | Sep 02, 2024 |
| MSI      | H81M-E33                    | [471e20b9ee](https://linux-hardware.org/?probe=471e20b9ee) | Oct 11, 2023 |
| MSI      | MPG B550 GAMING EDGE WIF... | [9f8e4c6a70](https://linux-hardware.org/?probe=9f8e4c6a70) | Jun 30, 2023 |
| MSI      | Z87-G43                     | [6babb6024e](https://linux-hardware.org/?probe=6babb6024e) | Apr 23, 2023 |
| MSI      | X399 SLI PLUS               | [ebb44ab29d](https://linux-hardware.org/?probe=ebb44ab29d) | Apr 22, 2023 |
| HP       | 1825                        | [3ba7cec175](https://linux-hardware.org/?probe=3ba7cec175) | Feb 22, 2023 |
| MSI      | Z87-G43                     | [acbef2e01a](https://linux-hardware.org/?probe=acbef2e01a) | Feb 21, 2023 |
| MSI      | B550-A PRO                  | [d2ebdf5627](https://linux-hardware.org/?probe=d2ebdf5627) | Dec 20, 2022 |
| Dell     | 0M017G A00                  | [6d65d5022d](https://linux-hardware.org/?probe=6d65d5022d) | Dec 20, 2022 |
| HP       | 339A                        | [7cfe4b70f8](https://linux-hardware.org/?probe=7cfe4b70f8) | Jun 30, 2022 |
| HP       | 8053                        | [ff703fcbf1](https://linux-hardware.org/?probe=ff703fcbf1) | Jun 23, 2022 |
| ASUSTek  | 970 PRO GAMING/AURA         | [67dbfe0d98](https://linux-hardware.org/?probe=67dbfe0d98) | May 14, 2022 |
| Gigabyte | B550M AORUS ELITE           | [0105f991c1](https://linux-hardware.org/?probe=0105f991c1) | Dec 01, 2021 |
| Gigabyte | M61PM-S2                    | [ed3a73a8a0](https://linux-hardware.org/?probe=ed3a73a8a0) | Nov 02, 2021 |
| HP       | 81C3                        | [df2caaf484](https://linux-hardware.org/?probe=df2caaf484) | Oct 11, 2021 |
| Gigabyte | AX370-Gaming K5-CF          | [d08d8c22f3](https://linux-hardware.org/?probe=d08d8c22f3) | Aug 06, 2021 |
| Intel    | H61M-S2PV                   | [a7ed913051](https://linux-hardware.org/?probe=a7ed913051) | Aug 05, 2021 |
| Foxconn  | 2ABF                        | [e722057484](https://linux-hardware.org/?probe=e722057484) | Jul 29, 2021 |
| HP       | 0B4Ch D                     | [775cf09e30](https://linux-hardware.org/?probe=775cf09e30) | Jul 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Kaisen 2.2 | 6        | 33.33%  |
| Kaisen 1.8 | 4        | 22.22%  |
| Kaisen 2.1 | 3        | 16.67%  |
| Kaisen 1.7 | 3        | 16.67%  |
| Kaisen 2.3 | 1        | 5.56%   |
| Kaisen 2.0 | 1        | 5.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Kaisen | 18       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-kaisen5-amd64   | 6        | 33.33%  |
| 6.0.0-1kaisen-amd64    | 5        | 27.78%  |
| 5.17.0-kaisen1-amd64   | 3        | 16.67%  |
| 5.15.0-kaisen1-amd64   | 2        | 11.11%  |
| 6.1.0-1kaisen-amd64    | 1        | 5.56%   |
| 6.0.0-1kaisen-rt-amd64 | 1        | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.0   | 6        | 33.33%  |
| 5.10.0  | 6        | 33.33%  |
| 5.17.0  | 3        | 16.67%  |
| 5.15.0  | 2        | 11.11%  |
| 6.1.0   | 1        | 5.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 6        | 33.33%  |
| 5.10    | 6        | 33.33%  |
| 5.17    | 3        | 16.67%  |
| 5.15    | 2        | 11.11%  |
| 6.1     | 1        | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 18       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MATE | 8        | 44.44%  |
| KDE5 | 5        | 27.78%  |
| XFCE | 4        | 22.22%  |
| LXQt | 1        | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 16       | 88.89%  |
| Tty  | 2        | 11.11%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 14       | 77.78%  |
| TDM     | 4        | 22.22%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 61.11%  |
| fr_FR | 2        | 11.11%  |
| fr_BE | 1        | 5.56%   |
| es_ES | 1        | 5.56%   |
| en_ZA | 1        | 5.56%   |
| en_GB | 1        | 5.56%   |
| de_DE | 1        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 9        | 50%     |
| EFI  | 9        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 10       | 55.56%  |
| Overlay | 8        | 44.44%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 11       | 61.11%  |
| MBR     | 6        | 33.33%  |
| Unknown | 1        | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 72.22%  |
| Yes       | 5        | 27.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 50%     |
| No        | 9        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 5        | 27.78%  |
| Hewlett-Packard     | 5        | 27.78%  |
| Gigabyte Technology | 3        | 16.67%  |
| Pegatron            | 1        | 5.56%   |
| Intel               | 1        | 5.56%   |
| Foxconn             | 1        | 5.56%   |
| Dell                | 1        | 5.56%   |
| ASUSTek Computer    | 1        | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Pegatron NP201AA-ABA a6814y | 1        | 5.56%   |
| MSI MS-7C91                 | 1        | 5.56%   |
| MSI MS-7C56                 | 1        | 5.56%   |
| MSI MS-7B09                 | 1        | 5.56%   |
| MSI MS-7817                 | 1        | 5.56%   |
| MSI MS-7816                 | 1        | 5.56%   |
| Intel H61M-S2PV             | 1        | 5.56%   |
| HP Z400 Workstation         | 1        | 5.56%   |
| HP EliteDesk 800 G2 TWR     | 1        | 5.56%   |
| HP EliteDesk 800 G1 DM      | 1        | 5.56%   |
| HP Elite Slice              | 1        | 5.56%   |
| HP Compaq Pro 6300 MT       | 1        | 5.56%   |
| Gigabyte M61PM-S2           | 1        | 5.56%   |
| Gigabyte B550M AORUS ELITE  | 1        | 5.56%   |
| Gigabyte AX370-Gaming K5    | 1        | 5.56%   |
| Foxconn s5-1204             | 1        | 5.56%   |
| Dell Studio 540             | 1        | 5.56%   |
| ASUS 970 PRO GAMING/AURA    | 1        | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP EliteDesk          | 2        | 11.11%  |
| Pegatron NP201AA-ABA  | 1        | 5.56%   |
| MSI MS-7C91           | 1        | 5.56%   |
| MSI MS-7C56           | 1        | 5.56%   |
| MSI MS-7B09           | 1        | 5.56%   |
| MSI MS-7817           | 1        | 5.56%   |
| MSI MS-7816           | 1        | 5.56%   |
| Intel H61M-S2PV       | 1        | 5.56%   |
| HP Z400               | 1        | 5.56%   |
| HP Elite              | 1        | 5.56%   |
| HP Compaq             | 1        | 5.56%   |
| Gigabyte M61PM-S2     | 1        | 5.56%   |
| Gigabyte B550M        | 1        | 5.56%   |
| Gigabyte AX370-Gaming | 1        | 5.56%   |
| Foxconn s5-1204       | 1        | 5.56%   |
| Dell Studio           | 1        | 5.56%   |
| ASUS 970              | 1        | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 16.67%  |
| 2016 | 3        | 16.67%  |
| 2017 | 2        | 11.11%  |
| 2013 | 2        | 11.11%  |
| 2011 | 2        | 11.11%  |
| 2014 | 1        | 5.56%   |
| 2012 | 1        | 5.56%   |
| 2010 | 1        | 5.56%   |
| 2009 | 1        | 5.56%   |
| 2008 | 1        | 5.56%   |
| 2006 | 1        | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 18       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 18       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 4        | 22.22%  |
| 16.01-24.0  | 4        | 22.22%  |
| 8.01-16.0   | 4        | 22.22%  |
| 64.01-256.0 | 3        | 16.67%  |
| 3.01-4.0    | 1        | 5.56%   |
| 24.01-32.0  | 1        | 5.56%   |
| 1.01-2.0    | 1        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 8        | 44.44%  |
| 4.01-8.0  | 3        | 16.67%  |
| 0.51-1.0  | 3        | 16.67%  |
| 2.01-3.0  | 2        | 11.11%  |
| 3.01-4.0  | 1        | 5.56%   |
| 8.01-16.0 | 1        | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 55.56%  |
| 4      | 3        | 16.67%  |
| 2      | 2        | 11.11%  |
| 5      | 1        | 5.56%   |
| 3      | 1        | 5.56%   |
| 0      | 1        | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 50%     |
| No        | 9        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 61.11%  |
| Yes       | 7        | 38.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 83.33%  |
| Yes       | 3        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 8        | 44.44%  |
| UK           | 2        | 11.11%  |
| Spain        | 2        | 11.11%  |
| France       | 2        | 11.11%  |
| South Africa | 1        | 5.56%   |
| Mexico       | 1        | 5.56%   |
| Germany      | 1        | 5.56%   |
| Belgium      | 1        | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Westfield              | 1        | 5.56%   |
| Segovia                | 1        | 5.56%   |
| Rieschweiler-Muehlbach | 1        | 5.56%   |
| Reno                   | 1        | 5.56%   |
| Prattville             | 1        | 5.56%   |
| Milwaukee              | 1        | 5.56%   |
| Middlesbrough          | 1        | 5.56%   |
| Miami                  | 1        | 5.56%   |
| Medway                 | 1        | 5.56%   |
| Manchester             | 1        | 5.56%   |
| Madrid                 | 1        | 5.56%   |
| Liège                 | 1        | 5.56%   |
| Lagorce                | 1        | 5.56%   |
| Edenvale               | 1        | 5.56%   |
| Columbus               | 1        | 5.56%   |
| Brive-la-Gaillarde     | 1        | 5.56%   |
| Apodaca                | 1        | 5.56%   |
| Albany                 | 1        | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 27.59%  |
| Seagate             | 5        | 6      | 17.24%  |
| Samsung Electronics | 4        | 7      | 13.79%  |
| Toshiba             | 2        | 2      | 6.9%    |
| SanDisk             | 2        | 2      | 6.9%    |
| Kingston            | 2        | 2      | 6.9%    |
| A-DATA Technology   | 2        | 2      | 6.9%    |
| Intel               | 1        | 1      | 3.45%   |
| China               | 1        | 1      | 3.45%   |
| ASMedia             | 1        | 1      | 3.45%   |
| Unknown             | 1        | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 2        | 5.88%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 2.94%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 2.94%   |
| WDC WD800BB-55JKC0 80GB              | 1        | 2.94%   |
| WDC WD6400AAKS-65A7B2 640GB          | 1        | 2.94%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 2.94%   |
| WDC WD5000AAKX-00U6AA0 500GB         | 1        | 2.94%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 2.94%   |
| WDC WD20NPVZ-82WFZT0 2TB             | 1        | 2.94%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1        | 2.94%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 2.94%   |
| Toshiba HDWD130 3TB                  | 1        | 2.94%   |
| Toshiba DT01ACA050 500GB             | 1        | 2.94%   |
| Seagate ST8000DM004-2CX188 8TB       | 1        | 2.94%   |
| Seagate ST2000DM008-2UB102 2TB       | 1        | 2.94%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 2.94%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD  | 1        | 2.94%   |
| SanDisk Portable SSD 2TB             | 1        | 2.94%   |
| Samsung SSD 980 PRO 1TB              | 1        | 2.94%   |
| Samsung SSD 970 EVO Plus 500GB       | 1        | 2.94%   |
| Samsung SSD 970 EVO Plus 1TB         | 1        | 2.94%   |
| Samsung SSD 960 EVO 250GB            | 1        | 2.94%   |
| Samsung SSD 860 QVO 1TB              | 1        | 2.94%   |
| Samsung SSD 850 EVO 500GB            | 1        | 2.94%   |
| Samsung HD154UI 1TB                  | 1        | 2.94%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 2.94%   |
| Kingston RBUSC180DS37128GH 128GB SSD | 1        | 2.94%   |
| Intel SSDPEKNW010T8 1TB              | 1        | 2.94%   |
| China SATA SSD 256GB                 | 1        | 2.94%   |
| ASMedia ASM1153E 500GB               | 1        | 2.94%   |
| A-DATA XPG EX500 240GB SSD           | 1        | 2.94%   |
| A-DATA SU635 240GB SSD               | 1        | 2.94%   |
| Unknown                              | 1        | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 46.67%  |
| Seagate             | 5        | 6      | 33.33%  |
| Toshiba             | 2        | 2      | 13.33%  |
| Samsung Electronics | 1        | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 15.38%  |
| SanDisk             | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 2      | 15.38%  |
| Kingston            | 2        | 2      | 15.38%  |
| A-DATA Technology   | 2        | 2      | 15.38%  |
| China               | 1        | 1      | 7.69%   |
| ASMedia             | 1        | 1      | 7.69%   |
| Unknown             | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 18     | 48%     |
| SSD  | 9        | 13     | 36%     |
| NVMe | 4        | 5      | 16%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 17       | 28     | 70.83%  |
| NVMe | 4        | 5      | 16.67%  |
| SAS  | 3        | 3      | 12.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 17     | 48%     |
| 0.51-1.0   | 6        | 6      | 24%     |
| 1.01-2.0   | 4        | 5      | 16%     |
| 2.01-3.0   | 2        | 2      | 8%      |
| 4.01-10.0  | 1        | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 4        | 22.22%  |
| 101-250        | 3        | 16.67%  |
| Unknown        | 3        | 16.67%  |
| 251-500        | 2        | 11.11%  |
| 1-20           | 2        | 11.11%  |
| 501-1000       | 2        | 11.11%  |
| More than 3000 | 1        | 5.56%   |
| 51-100         | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 7        | 38.89%  |
| 501-1000       | 4        | 22.22%  |
| Unknown        | 3        | 16.67%  |
| 251-500        | 2        | 11.11%  |
| More than 3000 | 1        | 5.56%   |
| 21-50          | 1        | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 1      | 16.67%  |
| WDC WD6400AAKS-65A7B2 640GB       | 1        | 1      | 16.67%  |
| WDC WD20NPVZ-82WFZT0 2TB          | 1        | 1      | 16.67%  |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 16.67%  |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 1      | 16.67%  |
| A-DATA Technology SU635 240GB SSD | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 3        | 3      | 50%     |
| Toshiba           | 1        | 1      | 16.67%  |
| Seagate           | 1        | 1      | 16.67%  |
| A-DATA Technology | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Toshiba | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

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
| Works    | 13       | 26     | 56.52%  |
| Malfunc  | 6        | 6      | 26.09%  |
| Detected | 4        | 4      | 17.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 12       | 57.14%  |
| AMD                 | 5        | 23.81%  |
| Samsung Electronics | 3        | 14.29%  |
| Nvidia              | 1        | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 12%     |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 12%     |
| Intel SATA Controller [RAID mode]                                              | 2        | 8%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 8%      |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 8%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 4%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 4%      |
| Nvidia MCP61 SATA Controller                                                   | 1        | 4%      |
| Nvidia MCP61 IDE                                                               | 1        | 4%      |
| Intel SSD 660P Series                                                          | 1        | 4%      |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 4%      |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 4%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 4%      |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 4%      |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 61.9%   |
| NVMe | 4        | 19.05%  |
| RAID | 2        | 9.52%   |
| IDE  | 2        | 9.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 61.11%  |
| AMD    | 7        | 38.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz               | 2        | 11.11%  |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1        | 5.56%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 5.56%   |
| Intel Pentium CPU G3250 @ 3.20GHz              | 1        | 5.56%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 5.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 5.56%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 5.56%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 5.56%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 5.56%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 5.56%   |
| AMD Ryzen Threadripper 2920X 12-Core Processor | 1        | 5.56%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 5.56%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 5.56%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 5.56%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 5.56%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 5.56%   |
| AMD Athlon 64 Processor 3800+                  | 1        | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 4        | 22.22%  |
| Intel Pentium           | 3        | 16.67%  |
| AMD Ryzen 5             | 2        | 11.11%  |
| Intel Xeon              | 1        | 5.56%   |
| Intel Pentium Dual-Core | 1        | 5.56%   |
| Intel Core i3           | 1        | 5.56%   |
| Intel Core 2 Quad       | 1        | 5.56%   |
| AMD Ryzen Threadripper  | 1        | 5.56%   |
| AMD Ryzen 9             | 1        | 5.56%   |
| AMD Ryzen 7             | 1        | 5.56%   |
| AMD FX                  | 1        | 5.56%   |
| AMD Athlon 64           | 1        | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 33.33%  |
| 2      | 5        | 27.78%  |
| 12     | 2        | 11.11%  |
| 1      | 2        | 11.11%  |
| 8      | 1        | 5.56%   |
| 6      | 1        | 5.56%   |
| 3      | 1        | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 61.11%  |
| 2      | 7        | 38.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 18       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 2        | 11.11%  |
| 0x306c3    | 2        | 11.11%  |
| 0x206a7    | 2        | 11.11%  |
| Unknown    | 2        | 11.11%  |
| 0x6fb      | 1        | 5.56%   |
| 0x306a9    | 1        | 5.56%   |
| 0x106a5    | 1        | 5.56%   |
| 0x10676    | 1        | 5.56%   |
| 0x0a20120a | 1        | 5.56%   |
| 0x0a201016 | 1        | 5.56%   |
| 0x08701021 | 1        | 5.56%   |
| 0x0800820b | 1        | 5.56%   |
| 0x08001137 | 1        | 5.56%   |
| 0x06000822 | 1        | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 3        | 16.67%  |
| Zen 3       | 2        | 11.11%  |
| Skylake     | 2        | 11.11%  |
| SandyBridge | 2        | 11.11%  |
| Zen+        | 1        | 5.56%   |
| Zen 2       | 1        | 5.56%   |
| Zen         | 1        | 5.56%   |
| Piledriver  | 1        | 5.56%   |
| Penryn      | 1        | 5.56%   |
| Nehalem     | 1        | 5.56%   |
| K8 Hammer   | 1        | 5.56%   |
| IvyBridge   | 1        | 5.56%   |
| Core        | 1        | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 42.11%  |
| Intel  | 8        | 42.11%  |
| AMD    | 3        | 15.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 2        | 10.53%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 10.53%  |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 5.26%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 5.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 5.26%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 5.26%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 5.26%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 5.26%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 5.26%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 5.26%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 5.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 5.26%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 5.26%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 7        | 38.89%  |
| 1 x Intel      | 6        | 33.33%  |
| 1 x AMD        | 3        | 16.67%  |
| 2 x Intel      | 1        | 5.56%   |
| Intel + Nvidia | 1        | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 17       | 94.44%  |
| Unknown | 1        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 44.44%  |
| 7.01-8.0   | 3        | 16.67%  |
| 1.01-2.0   | 3        | 16.67%  |
| 0.51-1.0   | 2        | 11.11%  |
| 3.01-4.0   | 1        | 5.56%   |
| 0.01-0.5   | 1        | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| Hewlett-Packard     | 2        | 14.29%  |
| Vizio               | 1        | 7.14%   |
| ViewSonic           | 1        | 7.14%   |
| Sceptre Tech        | 1        | 7.14%   |
| Philips             | 1        | 7.14%   |
| Grundig             | 1        | 7.14%   |
| Goldstar            | 1        | 7.14%   |
| Acer                | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                   | 1        | 6.67%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch           | 1        | 6.67%   |
| Sceptre Tech Sceptre H43 SPT1103 1920x1080 575x323mm 26.0-inch       | 1        | 6.67%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 6.67%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch | 1        | 6.67%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 6.67%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch           | 1        | 6.67%   |
| Hewlett-Packard V221 HWP3111 1920x1080 477x268mm 21.5-inch           | 1        | 6.67%   |
| Grundig WXGA GRU4448 1600x1200                                       | 1        | 6.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 6.67%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                    | 1        | 6.67%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                  | 1        | 6.67%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                   | 1        | 6.67%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 1        | 6.67%   |
| Acer ET322QK ACR0631 3840x2160 698x393mm 31.5-inch                   | 1        | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 8        | 57.14%  |
| 3840x2160 (4K)   | 3        | 21.43%  |
| 2560x1440 (QHD)  | 1        | 7.14%   |
| 1366x768 (WXGA)  | 1        | 7.14%   |
| 1280x1024 (SXGA) | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 31     | 3        | 21.43%  |
| 23     | 3        | 21.43%  |
| 26     | 2        | 14.29%  |
| 54     | 1        | 7.14%   |
| 27     | 1        | 7.14%   |
| 25     | 1        | 7.14%   |
| 24     | 1        | 7.14%   |
| 21     | 1        | 7.14%   |
| 17     | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 57.14%  |
| 601-700     | 3        | 21.43%  |
| 401-500     | 1        | 7.14%   |
| 301-350     | 1        | 7.14%   |
| 1001-1500   | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 13       | 92.86%  |
| 5/4   | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4        | 28.57%  |
| 351-500        | 3        | 21.43%  |
| 251-300        | 3        | 21.43%  |
| More than 1000 | 1        | 7.14%   |
| 301-350        | 1        | 7.14%   |
| 151-200        | 1        | 7.14%   |
| 141-150        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 71.43%  |
| 101-120 | 2        | 14.29%  |
| 1-50    | 1        | 7.14%   |
| 121-160 | 1        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 88.89%  |
| 2     | 1        | 5.56%   |
| 0     | 1        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 42.31%  |
| Intel                 | 6        | 23.08%  |
| TP-Link               | 3        | 11.54%  |
| Qualcomm Atheros      | 2        | 7.69%   |
| Nvidia                | 1        | 3.85%   |
| Lenovo                | 1        | 3.85%   |
| Gemtek                | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 7        | 25%     |
| Intel I211 Gigabit Network Connection                                  | 2        | 7.14%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 7.14%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                            | 1        | 3.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 3.57%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1        | 3.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1        | 3.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 3.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1        | 3.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 3.57%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 3.57%   |
| Lenovo P2a42                                                           | 1        | 3.57%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 3.57%   |
| Intel 82575EB Gigabit Network Connection                               | 1        | 3.57%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                      | 1        | 3.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 3.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 3        | 42.86%  |
| Qualcomm Atheros      | 2        | 28.57%  |
| Realtek Semiconductor | 1        | 14.29%  |
| Gemtek                | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1        | 14.29%  |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 14.29%  |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 14.29%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1        | 14.29%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 14.29%  |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 14.29%  |
| Gemtek WUBR-177G [Ralink RT2571W]                              | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 50%     |
| Intel                 | 6        | 30%     |
| Qualcomm Atheros      | 1        | 5%      |
| Nvidia                | 1        | 5%      |
| Lenovo                | 1        | 5%      |
| Broadcom              | 1        | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 7        | 33.33%  |
| Intel I211 Gigabit Network Connection                                  | 2        | 9.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 9.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 4.76%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 4.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 4.76%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 4.76%   |
| Lenovo P2a42                                                           | 1        | 4.76%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 4.76%   |
| Intel 82575EB Gigabit Network Connection                               | 1        | 4.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 72%     |
| WiFi     | 7        | 28%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 78.95%  |
| WiFi     | 4        | 21.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 77.78%  |
| 2     | 2        | 11.11%  |
| 4     | 1        | 5.56%   |
| 0     | 1        | 5.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 77.78%  |
| Yes  | 4        | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Broadcom | 3        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Broadcom BCM20702A0 Bluetooth 4.0 | 2        | 66.67%  |
| Broadcom BCM2045 Bluetooth        | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 11       | 40.74%  |
| Nvidia              | 7        | 25.93%  |
| AMD                 | 6        | 22.22%  |
| Logitech            | 1        | 3.7%    |
| C-Media Electronics | 1        | 3.7%    |
| ASUSTek Computer    | 1        | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 10%     |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 6.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 6.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 6.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 6.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 6.67%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 3.33%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 3.33%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 3.33%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 3.33%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 3.33%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 3.33%   |
| ASUSTek Computer Xonar SoundCard                                           | 1        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 3.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 3.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 3.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 23.81%  |
| SK hynix            | 4        | 19.05%  |
| Micron Technology   | 2        | 9.52%   |
| G.Skill             | 2        | 9.52%   |
| Crucial             | 2        | 9.52%   |
| Corsair             | 2        | 9.52%   |
| Unknown             | 1        | 4.76%   |
| Samsung Electronics | 1        | 4.76%   |
| Elpida              | 1        | 4.76%   |
| A Force             | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 8.33%   |
| Unknown RAM Module 1GB DIMM 400MT/s                      | 1        | 4.17%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s             | 1        | 4.17%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s    | 1        | 4.17%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 4.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 4.17%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s           | 1        | 4.17%   |
| Micron RAM 16JTF51264AZ-1G4M1 4096MB DIMM DDR3 1333MT/s  | 1        | 4.17%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s    | 1        | 4.17%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 4.17%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s     | 1        | 4.17%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 1        | 4.17%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3800MT/s       | 1        | 4.17%   |
| Elpida RAM EBE21UE8AEFA-8G-E 2GB DIMM DDR2 800MT/s       | 1        | 4.17%   |
| Elpida RAM EBE10UE8AEFA-8G-E 1GB DIMM DDR2 800MT/s       | 1        | 4.17%   |
| Crucial RAM RM51264BA1339.16FR 4GB DIMM DDR3 1333MT/s    | 1        | 4.17%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s | 1        | 4.17%   |
| Corsair RAM CMX4GX3M1A1600C11 4GB DIMM DDR3 1600MT/s     | 1        | 4.17%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3200MT/s     | 1        | 4.17%   |
| A Force RAM 1GX64V160K 8GB DIMM DDR3 1600MT/s            | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 8        | 44.44%  |
| DDR3    | 7        | 38.89%  |
| DDR2    | 2        | 11.11%  |
| Unknown | 1        | 5.56%   |

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
| 8192  | 7        | 33.33%  |
| 4096  | 7        | 33.33%  |
| 16384 | 2        | 9.52%   |
| 2048  | 2        | 9.52%   |
| 1024  | 2        | 9.52%   |
| 32768 | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 26.32%  |
| 3600  | 2        | 10.53%  |
| 3200  | 2        | 10.53%  |
| 1333  | 2        | 10.53%  |
| 49926 | 1        | 5.26%   |
| 3933  | 1        | 5.26%   |
| 3800  | 1        | 5.26%   |
| 2933  | 1        | 5.26%   |
| 2133  | 1        | 5.26%   |
| 1648  | 1        | 5.26%   |
| 800   | 1        | 5.26%   |
| 400   | 1        | 5.26%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 13       | 72.22%  |
| 1     | 5        | 27.78%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 50%     |
| Graphics card    | 2        | 33.33%  |
| Unassigned class | 1        | 16.67%  |

