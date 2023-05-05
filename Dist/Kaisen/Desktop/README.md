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

Total: 16

| Vendor   | Model               | Probe                                                      | Date         |
|----------|---------------------|------------------------------------------------------------|--------------|
| MSI      | Z87-G43             | [6babb6024e](https://linux-hardware.org/?probe=6babb6024e) | Apr 23, 2023 |
| MSI      | X399 SLI PLUS       | [ebb44ab29d](https://linux-hardware.org/?probe=ebb44ab29d) | Apr 22, 2023 |
| HP       | 1825                | [3ba7cec175](https://linux-hardware.org/?probe=3ba7cec175) | Feb 22, 2023 |
| MSI      | Z87-G43             | [acbef2e01a](https://linux-hardware.org/?probe=acbef2e01a) | Feb 21, 2023 |
| MSI      | B550-A PRO          | [d2ebdf5627](https://linux-hardware.org/?probe=d2ebdf5627) | Dec 20, 2022 |
| Dell     | 0M017G A00          | [6d65d5022d](https://linux-hardware.org/?probe=6d65d5022d) | Dec 20, 2022 |
| HP       | 339A                | [7cfe4b70f8](https://linux-hardware.org/?probe=7cfe4b70f8) | Jun 30, 2022 |
| HP       | 8053                | [ff703fcbf1](https://linux-hardware.org/?probe=ff703fcbf1) | Jun 23, 2022 |
| ASUSTek  | 970 PRO GAMING/AURA | [67dbfe0d98](https://linux-hardware.org/?probe=67dbfe0d98) | May 14, 2022 |
| Gigabyte | B550M AORUS ELITE   | [0105f991c1](https://linux-hardware.org/?probe=0105f991c1) | Dec 01, 2021 |
| Gigabyte | M61PM-S2            | [ed3a73a8a0](https://linux-hardware.org/?probe=ed3a73a8a0) | Nov 02, 2021 |
| HP       | 81C3                | [df2caaf484](https://linux-hardware.org/?probe=df2caaf484) | Oct 11, 2021 |
| Gigabyte | AX370-Gaming K5-CF  | [d08d8c22f3](https://linux-hardware.org/?probe=d08d8c22f3) | Aug 06, 2021 |
| Intel    | H61M-S2PV           | [a7ed913051](https://linux-hardware.org/?probe=a7ed913051) | Aug 05, 2021 |
| Foxconn  | 2ABF                | [e722057484](https://linux-hardware.org/?probe=e722057484) | Jul 29, 2021 |
| HP       | 0B4Ch D             | [775cf09e30](https://linux-hardware.org/?probe=775cf09e30) | Jul 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Kaisen 2.2 | 5        | 33.33%  |
| Kaisen 1.8 | 4        | 26.67%  |
| Kaisen 1.7 | 3        | 20%     |
| Kaisen 2.1 | 2        | 13.33%  |
| Kaisen 2.0 | 1        | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Kaisen | 15       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-kaisen5-amd64   | 6        | 40%     |
| 6.0.0-1kaisen-amd64    | 4        | 26.67%  |
| 5.17.0-kaisen1-amd64   | 2        | 13.33%  |
| 5.15.0-kaisen1-amd64   | 2        | 13.33%  |
| 6.0.0-1kaisen-rt-amd64 | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 6        | 40%     |
| 6.0.0   | 5        | 33.33%  |
| 5.17.0  | 2        | 13.33%  |
| 5.15.0  | 2        | 13.33%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 6        | 40%     |
| 6.0     | 5        | 33.33%  |
| 5.17    | 2        | 13.33%  |
| 5.15    | 2        | 13.33%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 15       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MATE | 7        | 46.67%  |
| KDE5 | 5        | 33.33%  |
| XFCE | 2        | 13.33%  |
| LXQt | 1        | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 15       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 11       | 73.33%  |
| TDM     | 4        | 26.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 10       | 66.67%  |
| fr_FR | 2        | 13.33%  |
| en_ZA | 1        | 6.67%   |
| en_GB | 1        | 6.67%   |
| de_DE | 1        | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 8        | 53.33%  |
| BIOS | 7        | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 9        | 60%     |
| Overlay | 6        | 40%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 10       | 66.67%  |
| MBR     | 4        | 26.67%  |
| Unknown | 1        | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 66.67%  |
| Yes       | 5        | 33.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8        | 53.33%  |
| No        | 7        | 46.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 33.33%  |
| MSI                 | 3        | 20%     |
| Gigabyte Technology | 3        | 20%     |
| Intel               | 1        | 6.67%   |
| Foxconn             | 1        | 6.67%   |
| Dell                | 1        | 6.67%   |
| ASUSTek Computer    | 1        | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| MSI MS-7C56                | 1        | 6.67%   |
| MSI MS-7B09                | 1        | 6.67%   |
| MSI MS-7816                | 1        | 6.67%   |
| Intel H61M-S2PV            | 1        | 6.67%   |
| HP Z400 Workstation        | 1        | 6.67%   |
| HP EliteDesk 800 G2 TWR    | 1        | 6.67%   |
| HP EliteDesk 800 G1 DM     | 1        | 6.67%   |
| HP Elite Slice             | 1        | 6.67%   |
| HP Compaq Pro 6300 MT      | 1        | 6.67%   |
| Gigabyte M61PM-S2          | 1        | 6.67%   |
| Gigabyte B550M AORUS ELITE | 1        | 6.67%   |
| Gigabyte AX370-Gaming K5   | 1        | 6.67%   |
| Foxconn s5-1204            | 1        | 6.67%   |
| Dell Studio 540            | 1        | 6.67%   |
| ASUS 970 PRO GAMING/AURA   | 1        | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP EliteDesk          | 2        | 13.33%  |
| MSI MS-7C56           | 1        | 6.67%   |
| MSI MS-7B09           | 1        | 6.67%   |
| MSI MS-7816           | 1        | 6.67%   |
| Intel H61M-S2PV       | 1        | 6.67%   |
| HP Z400               | 1        | 6.67%   |
| HP Elite              | 1        | 6.67%   |
| HP Compaq             | 1        | 6.67%   |
| Gigabyte M61PM-S2     | 1        | 6.67%   |
| Gigabyte B550M        | 1        | 6.67%   |
| Gigabyte AX370-Gaming | 1        | 6.67%   |
| Foxconn s5-1204       | 1        | 6.67%   |
| Dell Studio           | 1        | 6.67%   |
| ASUS 970              | 1        | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 3        | 20%     |
| 2020 | 2        | 13.33%  |
| 2017 | 2        | 13.33%  |
| 2011 | 2        | 13.33%  |
| 2014 | 1        | 6.67%   |
| 2013 | 1        | 6.67%   |
| 2012 | 1        | 6.67%   |
| 2010 | 1        | 6.67%   |
| 2008 | 1        | 6.67%   |
| 2006 | 1        | 6.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 15       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 15       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 4        | 26.67%  |
| 4.01-8.0    | 3        | 20%     |
| 8.01-16.0   | 3        | 20%     |
| 64.01-256.0 | 2        | 13.33%  |
| 3.01-4.0    | 1        | 6.67%   |
| 24.01-32.0  | 1        | 6.67%   |
| 1.01-2.0    | 1        | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 6        | 40%     |
| 4.01-8.0  | 3        | 20%     |
| 0.51-1.0  | 3        | 20%     |
| 3.01-4.0  | 1        | 6.67%   |
| 2.01-3.0  | 1        | 6.67%   |
| 8.01-16.0 | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 46.67%  |
| 4      | 3        | 20%     |
| 2      | 2        | 13.33%  |
| 5      | 1        | 6.67%   |
| 3      | 1        | 6.67%   |
| 0      | 1        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 53.33%  |
| Yes       | 7        | 46.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 80%     |
| Yes       | 3        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 7        | 46.67%  |
| UK           | 2        | 13.33%  |
| France       | 2        | 13.33%  |
| Spain        | 1        | 6.67%   |
| South Africa | 1        | 6.67%   |
| Mexico       | 1        | 6.67%   |
| Germany      | 1        | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Segovia                | 1        | 6.67%   |
| Rieschweiler-Muehlbach | 1        | 6.67%   |
| Prattville             | 1        | 6.67%   |
| Milwaukee              | 1        | 6.67%   |
| Middlesbrough          | 1        | 6.67%   |
| Miami                  | 1        | 6.67%   |
| Medway                 | 1        | 6.67%   |
| Manchester             | 1        | 6.67%   |
| Los Angeles            | 1        | 6.67%   |
| La Clotte              | 1        | 6.67%   |
| Edenvale               | 1        | 6.67%   |
| Columbus               | 1        | 6.67%   |
| Brive-la-Gaillarde     | 1        | 6.67%   |
| Apodaca                | 1        | 6.67%   |
| Albany                 | 1        | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 24%     |
| Seagate             | 5        | 6      | 20%     |
| Samsung Electronics | 3        | 6      | 12%     |
| SanDisk             | 2        | 2      | 8%      |
| Kingston            | 2        | 2      | 8%      |
| A-DATA Technology   | 2        | 2      | 8%      |
| Toshiba             | 1        | 1      | 4%      |
| Intel               | 1        | 1      | 4%      |
| China               | 1        | 1      | 4%      |
| ASMedia             | 1        | 1      | 4%      |
| Unknown             | 1        | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 2        | 6.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 3.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 3.45%   |
| WDC WD800BB-55JKC0 80GB              | 1        | 3.45%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 3.45%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 3.45%   |
| WDC WD20NPVZ-82WFZT0 2TB             | 1        | 3.45%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1        | 3.45%   |
| Toshiba HDWD130 3TB                  | 1        | 3.45%   |
| Seagate ST8000DM004-2CX188 8TB       | 1        | 3.45%   |
| Seagate ST2000DM008-2UB102 2TB       | 1        | 3.45%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 3.45%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD  | 1        | 3.45%   |
| SanDisk Portable SSD 1TB             | 1        | 3.45%   |
| Samsung SSD 970 EVO Plus 500GB       | 1        | 3.45%   |
| Samsung SSD 970 EVO Plus 1TB         | 1        | 3.45%   |
| Samsung SSD 960 EVO 250GB            | 1        | 3.45%   |
| Samsung SSD 860 QVO 1TB              | 1        | 3.45%   |
| Samsung SSD 850 EVO 500GB            | 1        | 3.45%   |
| Samsung HD154UI 1TB                  | 1        | 3.45%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 3.45%   |
| Kingston RBUSC180DS37128GH 128GB SSD | 1        | 3.45%   |
| Intel SSDPEKNW010T8 1TB              | 1        | 3.45%   |
| China SATA SSD 256GB                 | 1        | 3.45%   |
| ASMedia ASM1153E 2TB                 | 1        | 3.45%   |
| A-DATA XPG EX500 240GB SSD           | 1        | 3.45%   |
| A-DATA SU635 240GB SSD               | 1        | 3.45%   |
| Unknown                              | 1        | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 38.46%  |
| Seagate             | 5        | 6      | 38.46%  |
| Toshiba             | 1        | 1      | 7.69%   |
| Samsung Electronics | 1        | 1      | 7.69%   |
| ASMedia             | 1        | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 16.67%  |
| SanDisk             | 2        | 2      | 16.67%  |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Kingston            | 2        | 2      | 16.67%  |
| A-DATA Technology   | 2        | 2      | 16.67%  |
| China               | 1        | 1      | 8.33%   |
| Unknown             | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 9        | 12     | 42.86%  |
| HDD  | 9        | 14     | 42.86%  |
| NVMe | 3        | 4      | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 23     | 70%     |
| SAS  | 3        | 3      | 15%     |
| NVMe | 3        | 4      | 15%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 9        | 13     | 42.86%  |
| 0.51-1.0   | 5        | 5      | 23.81%  |
| 1.01-2.0   | 4        | 5      | 19.05%  |
| 2.01-3.0   | 2        | 2      | 9.52%   |
| 4.01-10.0  | 1        | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 4        | 26.67%  |
| 101-250        | 3        | 20%     |
| Unknown        | 3        | 20%     |
| More than 3000 | 1        | 6.67%   |
| 251-500        | 1        | 6.67%   |
| 1-20           | 1        | 6.67%   |
| 501-1000       | 1        | 6.67%   |
| 51-100         | 1        | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 5        | 33.33%  |
| 501-1000       | 4        | 26.67%  |
| Unknown        | 3        | 20%     |
| More than 3000 | 1        | 6.67%   |
| 251-500        | 1        | 6.67%   |
| 21-50          | 1        | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 1      | 25%     |
| WDC WD20NPVZ-82WFZT0 2TB          | 1        | 1      | 25%     |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 1      | 25%     |
| A-DATA Technology SU635 240GB SSD | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 2        | 2      | 50%     |
| Seagate           | 1        | 1      | 25%     |
| A-DATA Technology | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 2        | 2      | 50%     |
| HDD  | 2        | 2      | 50%     |

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
| Works    | 11       | 22     | 57.89%  |
| Detected | 4        | 4      | 21.05%  |
| Malfunc  | 4        | 4      | 21.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 10       | 58.82%  |
| AMD                 | 4        | 23.53%  |
| Samsung Electronics | 2        | 11.76%  |
| Nvidia              | 1        | 5.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 9.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 9.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 9.52%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 9.52%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 9.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 4.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 4.76%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 4.76%   |
| Nvidia MCP61 IDE                                                               | 1        | 4.76%   |
| Intel SSD 660P Series                                                          | 1        | 4.76%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 4.76%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 4.76%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 4.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 4.76%   |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 4.76%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 4.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 64.71%  |
| NVMe | 3        | 17.65%  |
| IDE  | 2        | 11.76%  |
| RAID | 1        | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 60%     |
| AMD    | 6        | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz               | 2        | 13.33%  |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1        | 6.67%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 6.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 6.67%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 6.67%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 6.67%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 6.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 6.67%   |
| AMD Ryzen Threadripper 2920X 12-Core Processor | 1        | 6.67%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 1        | 6.67%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 6.67%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 6.67%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 6.67%   |
| AMD Athlon 64 Processor 3800+                  | 1        | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 4        | 26.67%  |
| Intel Pentium          | 2        | 13.33%  |
| AMD Ryzen 5            | 2        | 13.33%  |
| Intel Xeon             | 1        | 6.67%   |
| Intel Core i3          | 1        | 6.67%   |
| Intel Core 2 Quad      | 1        | 6.67%   |
| AMD Ryzen Threadripper | 1        | 6.67%   |
| AMD Ryzen 7            | 1        | 6.67%   |
| AMD FX                 | 1        | 6.67%   |
| AMD Athlon 64          | 1        | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 40%     |
| 2      | 3        | 20%     |
| 1      | 2        | 13.33%  |
| 12     | 1        | 6.67%   |
| 8      | 1        | 6.67%   |
| 6      | 1        | 6.67%   |
| 3      | 1        | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 60%     |
| 2      | 6        | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 15       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 2        | 13.33%  |
| 0x206a7    | 2        | 13.33%  |
| Unknown    | 2        | 13.33%  |
| 0x6fb      | 1        | 6.67%   |
| 0x306c3    | 1        | 6.67%   |
| 0x306a9    | 1        | 6.67%   |
| 0x106a5    | 1        | 6.67%   |
| 0x0a20120a | 1        | 6.67%   |
| 0x08701021 | 1        | 6.67%   |
| 0x0800820b | 1        | 6.67%   |
| 0x08001137 | 1        | 6.67%   |
| 0x06000822 | 1        | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 2        | 13.33%  |
| SandyBridge | 2        | 13.33%  |
| Haswell     | 2        | 13.33%  |
| Zen+        | 1        | 6.67%   |
| Zen 3       | 1        | 6.67%   |
| Zen 2       | 1        | 6.67%   |
| Zen         | 1        | 6.67%   |
| Piledriver  | 1        | 6.67%   |
| Nehalem     | 1        | 6.67%   |
| K8 Hammer   | 1        | 6.67%   |
| IvyBridge   | 1        | 6.67%   |
| Core        | 1        | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 43.75%  |
| Nvidia | 6        | 37.5%   |
| AMD    | 3        | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 2        | 12.5%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 12.5%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 6.25%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 6.25%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 6.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 6.25%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 6.25%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 6.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 6.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 6.25%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 6.25%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 6.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 6.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 5        | 33.33%  |
| 1 x Intel      | 5        | 33.33%  |
| 1 x AMD        | 3        | 20%     |
| 2 x Intel      | 1        | 6.67%   |
| Intel + Nvidia | 1        | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 14       | 93.33%  |
| Unknown | 1        | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 46.67%  |
| 7.01-8.0   | 3        | 20%     |
| 0.51-1.0   | 2        | 13.33%  |
| 3.01-4.0   | 1        | 6.67%   |
| 1.01-2.0   | 1        | 6.67%   |
| 0.01-0.5   | 1        | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 30%     |
| Samsung Electronics | 2        | 20%     |
| Vizio               | 1        | 10%     |
| Philips             | 1        | 10%     |
| Hewlett-Packard     | 1        | 10%     |
| Grundig             | 1        | 10%     |
| Acer                | 1        | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                   | 1        | 9.09%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 9.09%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch | 1        | 9.09%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 9.09%   |
| Hewlett-Packard V221 HWP3111 1920x1080 477x268mm 21.5-inch           | 1        | 9.09%   |
| Grundig WUXGA GRU4448 1920x540                                       | 1        | 9.09%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                    | 1        | 9.09%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                  | 1        | 9.09%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                   | 1        | 9.09%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 1        | 9.09%   |
| Acer ET322QK ACR0631 3840x2160 698x393mm 31.5-inch                   | 1        | 9.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 6        | 60%     |
| 3840x2160 (4K)  | 2        | 20%     |
| 2560x1440 (QHD) | 1        | 10%     |
| 1366x768 (WXGA) | 1        | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 31     | 2        | 20%     |
| 23     | 2        | 20%     |
| 54     | 1        | 10%     |
| 27     | 1        | 10%     |
| 26     | 1        | 10%     |
| 25     | 1        | 10%     |
| 24     | 1        | 10%     |
| 21     | 1        | 10%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 60%     |
| 601-700     | 2        | 20%     |
| 401-500     | 1        | 10%     |
| 1001-1500   | 1        | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 10       | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 30%     |
| 351-500        | 2        | 20%     |
| 251-300        | 2        | 20%     |
| More than 1000 | 1        | 10%     |
| 301-350        | 1        | 10%     |
| 151-200        | 1        | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 60%     |
| 101-120 | 2        | 20%     |
| 1-50    | 1        | 10%     |
| 121-160 | 1        | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 86.67%  |
| 2     | 1        | 6.67%   |
| 0     | 1        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 36.36%  |
| Intel                 | 6        | 27.27%  |
| TP-Link               | 3        | 13.64%  |
| Qualcomm Atheros      | 2        | 9.09%   |
| Nvidia                | 1        | 4.55%   |
| Lenovo                | 1        | 4.55%   |
| Broadcom              | 1        | 4.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5        | 20.83%  |
| Intel I211 Gigabit Network Connection                             | 2        | 8.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 8.33%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                       | 1        | 4.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 4.17%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 4.17%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1        | 4.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 4.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 4.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 4.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 4.17%   |
| Nvidia MCP61 Ethernet                                             | 1        | 4.17%   |
| Lenovo P2a42                                                      | 1        | 4.17%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.17%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 4.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 3        | 50%     |
| Qualcomm Atheros      | 2        | 33.33%  |
| Realtek Semiconductor | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1        | 16.67%  |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 16.67%  |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 16.67%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1        | 16.67%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 16.67%  |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 41.18%  |
| Intel                 | 6        | 35.29%  |
| Qualcomm Atheros      | 1        | 5.88%   |
| Nvidia                | 1        | 5.88%   |
| Lenovo                | 1        | 5.88%   |
| Broadcom              | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5        | 27.78%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.11%  |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 11.11%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 5.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 5.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 5.56%   |
| Lenovo P2a42                                                      | 1        | 5.56%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 5.56%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 5.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 71.43%  |
| WiFi     | 6        | 28.57%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 81.25%  |
| WiFi     | 3        | 18.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 73.33%  |
| 2     | 2        | 13.33%  |
| 4     | 1        | 6.67%   |
| 0     | 1        | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 80%     |
| Yes  | 3        | 20%     |

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
| Intel               | 9        | 39.13%  |
| AMD                 | 6        | 26.09%  |
| Nvidia              | 5        | 21.74%  |
| Logitech            | 1        | 4.35%   |
| C-Media Electronics | 1        | 4.35%   |
| ASUSTek Computer    | 1        | 4.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 7.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 7.69%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 7.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 7.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 3.85%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 3.85%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 3.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 3.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 3.85%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 3.85%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 3.85%   |
| ASUSTek Computer Xonar SoundCard                                           | 1        | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 3.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 3.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 4        | 23.53%  |
| Kingston            | 4        | 23.53%  |
| Micron Technology   | 2        | 11.76%  |
| G.Skill             | 2        | 11.76%  |
| Unknown             | 1        | 5.88%   |
| Samsung Electronics | 1        | 5.88%   |
| Crucial             | 1        | 5.88%   |
| Corsair             | 1        | 5.88%   |
| A Force             | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 2        | 10.53%  |
| Unknown RAM Module 1GB DIMM 400MT/s                    | 1        | 5.26%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s           | 1        | 5.26%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s  | 1        | 5.26%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s   | 1        | 5.26%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1        | 5.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 1        | 5.26%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 5.26%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 5.26%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 1        | 5.26%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 1        | 5.26%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 5.26%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s   | 1        | 5.26%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 1        | 5.26%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s     | 1        | 5.26%   |
| Crucial RAM RM51264BA1339.16FR 4GB DIMM DDR3 1333MT/s  | 1        | 5.26%   |
| Corsair RAM CMX4GX3M1A1600C11 4GB DIMM DDR3 1600MT/s   | 1        | 5.26%   |
| A Force RAM 1GX64V160K 8GB DIMM DDR3 1600MT/s          | 1        | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 6        | 42.86%  |
| DDR3    | 6        | 42.86%  |
| DDR2    | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 85.71%  |
| SODIMM | 2        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 37.5%   |
| 4096  | 6        | 37.5%   |
| 16384 | 2        | 12.5%   |
| 2048  | 1        | 6.25%   |
| 1024  | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 26.67%  |
| 3600  | 2        | 13.33%  |
| 1333  | 2        | 13.33%  |
| 49926 | 1        | 6.67%   |
| 3733  | 1        | 6.67%   |
| 3200  | 1        | 6.67%   |
| 2933  | 1        | 6.67%   |
| 2133  | 1        | 6.67%   |
| 1648  | 1        | 6.67%   |
| 400   | 1        | 6.67%   |

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
| 0     | 10       | 66.67%  |
| 1     | 5        | 33.33%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 60%     |
| Unassigned class | 1        | 20%     |
| Graphics card    | 1        | 20%     |

