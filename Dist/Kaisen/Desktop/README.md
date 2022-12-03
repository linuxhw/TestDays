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

Total: 10

| Vendor   | Model               | Probe                                                      | Date         |
|----------|---------------------|------------------------------------------------------------|--------------|
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
| Kaisen 1.8 | 4        | 40%     |
| Kaisen 1.7 | 3        | 30%     |
| Kaisen 2.1 | 2        | 20%     |
| Kaisen 2.0 | 1        | 10%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Kaisen | 10       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.0-kaisen5-amd64 | 6        | 60%     |
| 5.17.0-kaisen1-amd64 | 2        | 20%     |
| 5.15.0-kaisen1-amd64 | 2        | 20%     |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 6        | 60%     |
| 5.17.0  | 2        | 20%     |
| 5.15.0  | 2        | 20%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 6        | 60%     |
| 5.17    | 2        | 20%     |
| 5.15    | 2        | 20%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MATE | 5        | 50%     |
| KDE5 | 4        | 40%     |
| LXQt | 1        | 10%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 10       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 6        | 60%     |
| TDM     | 4        | 40%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 7        | 70%     |
| fr_FR | 1        | 10%     |
| en_ZA | 1        | 10%     |
| en_GB | 1        | 10%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 5        | 50%     |
| EFI  | 5        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Overlay | 5        | 50%     |
| Btrfs   | 5        | 50%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 6        | 60%     |
| MBR     | 3        | 30%     |
| Unknown | 1        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 60%     |
| Yes       | 4        | 40%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 60%     |
| Yes       | 4        | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 40%     |
| Gigabyte Technology | 3        | 30%     |
| Intel               | 1        | 10%     |
| Foxconn             | 1        | 10%     |
| ASUSTek Computer    | 1        | 10%     |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Intel H61M-S2PV            | 1        | 10%     |
| HP Z400 Workstation        | 1        | 10%     |
| HP EliteDesk 800 G2 TWR    | 1        | 10%     |
| HP Elite Slice             | 1        | 10%     |
| HP Compaq Pro 6300 MT      | 1        | 10%     |
| Gigabyte M61PM-S2          | 1        | 10%     |
| Gigabyte B550M AORUS ELITE | 1        | 10%     |
| Gigabyte AX370-Gaming K5   | 1        | 10%     |
| Foxconn s5-1204            | 1        | 10%     |
| ASUS 970 PRO GAMING/AURA   | 1        | 10%     |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Intel H61M-S2PV       | 1        | 10%     |
| HP Z400               | 1        | 10%     |
| HP EliteDesk          | 1        | 10%     |
| HP Elite              | 1        | 10%     |
| HP Compaq             | 1        | 10%     |
| Gigabyte M61PM-S2     | 1        | 10%     |
| Gigabyte B550M        | 1        | 10%     |
| Gigabyte AX370-Gaming | 1        | 10%     |
| Foxconn s5-1204       | 1        | 10%     |
| ASUS 970              | 1        | 10%     |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 3        | 30%     |
| 2011 | 2        | 20%     |
| 2020 | 1        | 10%     |
| 2017 | 1        | 10%     |
| 2012 | 1        | 10%     |
| 2010 | 1        | 10%     |
| 2006 | 1        | 10%     |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 10       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 10       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 2        | 20%     |
| 16.01-24.0  | 2        | 20%     |
| 8.01-16.0   | 2        | 20%     |
| 3.01-4.0    | 1        | 10%     |
| 24.01-32.0  | 1        | 10%     |
| 64.01-256.0 | 1        | 10%     |
| 1.01-2.0    | 1        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 5        | 50%     |
| 0.51-1.0 | 3        | 30%     |
| 4.01-8.0 | 2        | 20%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 60%     |
| 5      | 1        | 10%     |
| 4      | 1        | 10%     |
| 3      | 1        | 10%     |
| 0      | 1        | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 70%     |
| No        | 3        | 30%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5        | 50%     |
| No        | 5        | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 80%     |
| Yes       | 2        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 4        | 40%     |
| UK           | 2        | 20%     |
| Spain        | 1        | 10%     |
| South Africa | 1        | 10%     |
| Mexico       | 1        | 10%     |
| France       | 1        | 10%     |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Segovia            | 1        | 10%     |
| Milwaukee          | 1        | 10%     |
| Middlesbrough      | 1        | 10%     |
| Miami              | 1        | 10%     |
| Medway             | 1        | 10%     |
| Manchester         | 1        | 10%     |
| Edenvale           | 1        | 10%     |
| Brive-la-Gaillarde | 1        | 10%     |
| Apodaca            | 1        | 10%     |
| Albany             | 1        | 10%     |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 31.25%  |
| Seagate             | 2        | 2      | 12.5%   |
| SanDisk             | 2        | 2      | 12.5%   |
| Kingston            | 2        | 2      | 12.5%   |
| Samsung Electronics | 1        | 2      | 6.25%   |
| China               | 1        | 1      | 6.25%   |
| ASMedia             | 1        | 1      | 6.25%   |
| A-DATA Technology   | 1        | 1      | 6.25%   |
| Unknown             | 1        | 1      | 6.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 5.56%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 5.56%   |
| WDC WD800BB-55JKC0 80GB              | 1        | 5.56%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 5.56%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 5.56%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1        | 5.56%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 5.56%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 5.56%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD  | 1        | 5.56%   |
| SanDisk Portable SSD 1TB             | 1        | 5.56%   |
| Samsung SSD 960 EVO 250GB            | 1        | 5.56%   |
| Samsung SSD 860 QVO 1TB              | 1        | 5.56%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 5.56%   |
| Kingston RBUSC180DS37128GH 128GB SSD | 1        | 5.56%   |
| China SATA SSD 256GB                 | 1        | 5.56%   |
| ASMedia ASM1153E 240GB SSD           | 1        | 5.56%   |
| A-DATA XPG EX500 240GB SSD           | 1        | 5.56%   |
| Unknown                              | 1        | 5.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 66.67%  |
| Seagate | 2        | 2      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 18.18%  |
| SanDisk             | 2        | 2      | 18.18%  |
| Kingston            | 2        | 2      | 18.18%  |
| Samsung Electronics | 1        | 1      | 9.09%   |
| China               | 1        | 1      | 9.09%   |
| ASMedia             | 1        | 1      | 9.09%   |
| A-DATA Technology   | 1        | 1      | 9.09%   |
| Unknown             | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 8        | 11     | 61.54%  |
| HDD  | 4        | 6      | 30.77%  |
| NVMe | 1        | 1      | 7.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 9        | 14     | 69.23%  |
| SAS  | 3        | 3      | 23.08%  |
| NVMe | 1        | 1      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 8        | 11     | 57.14%  |
| 0.51-1.0   | 4        | 4      | 28.57%  |
| 2.01-3.0   | 1        | 1      | 7.14%   |
| 1.01-2.0   | 1        | 1      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 3        | 30%     |
| 1001-2000  | 2        | 20%     |
| Unknown    | 2        | 20%     |
| 1-20       | 1        | 10%     |
| 501-1000   | 1        | 10%     |
| 51-100     | 1        | 10%     |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 5        | 50%     |
| 501-1000 | 2        | 20%     |
| Unknown  | 2        | 20%     |
| 251-500  | 1        | 10%     |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 100%    |

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
| Works    | 7        | 13     | 58.33%  |
| Detected | 4        | 4      | 33.33%  |
| Malfunc  | 1        | 1      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 6        | 60%     |
| AMD                 | 2        | 20%     |
| Samsung Electronics | 1        | 10%     |
| Nvidia              | 1        | 10%     |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 16.67%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 16.67%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 8.33%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 8.33%   |
| Nvidia MCP61 IDE                                                              | 1        | 8.33%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 8.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 1        | 8.33%   |
| AMD X370 Series Chipset SATA Controller                                       | 1        | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1        | 8.33%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 8.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7        | 70%     |
| RAID | 1        | 10%     |
| NVMe | 1        | 10%     |
| IDE  | 1        | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 6        | 60%     |
| AMD    | 4        | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz      | 2        | 20%     |
| Intel Xeon CPU W3565 @ 3.20GHz        | 1        | 10%     |
| Intel Core i5-6500T CPU @ 2.50GHz     | 1        | 10%     |
| Intel Core i5-6500 CPU @ 3.20GHz      | 1        | 10%     |
| Intel Core i3-3220 CPU @ 3.30GHz      | 1        | 10%     |
| AMD Ryzen 7 1700 Eight-Core Processor | 1        | 10%     |
| AMD Ryzen 5 3600 6-Core Processor     | 1        | 10%     |
| AMD FX-6300 Six-Core Processor        | 1        | 10%     |
| AMD Athlon 64 Processor 3800+         | 1        | 10%     |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Pentium | 2        | 20%     |
| Intel Core i5 | 2        | 20%     |
| Intel Xeon    | 1        | 10%     |
| Intel Core i3 | 1        | 10%     |
| AMD Ryzen 7   | 1        | 10%     |
| AMD Ryzen 5   | 1        | 10%     |
| AMD FX        | 1        | 10%     |
| AMD Athlon 64 | 1        | 10%     |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 3        | 30%     |
| 2      | 3        | 30%     |
| 1      | 2        | 20%     |
| 8      | 1        | 10%     |
| 3      | 1        | 10%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 60%     |
| 2      | 4        | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 10       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 2        | 20%     |
| 0x206a7    | 2        | 20%     |
| 0x306a9    | 1        | 10%     |
| 0x106a5    | 1        | 10%     |
| 0x08701021 | 1        | 10%     |
| 0x08001137 | 1        | 10%     |
| 0x06000822 | 1        | 10%     |
| Unknown    | 1        | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 2        | 20%     |
| SandyBridge | 2        | 20%     |
| Zen 2       | 1        | 10%     |
| Zen         | 1        | 10%     |
| Piledriver  | 1        | 10%     |
| Nehalem     | 1        | 10%     |
| K8 Hammer   | 1        | 10%     |
| IvyBridge   | 1        | 10%     |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 5        | 45.45%  |
| Intel  | 5        | 45.45%  |
| AMD    | 1        | 9.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                     | 2        | 18.18%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2        | 18.18%  |
| Nvidia GP108 [GeForce GT 1030]                                            | 1        | 9.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1        | 9.09%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1        | 9.09%   |
| Nvidia G94GL [Quadro FX 1800]                                             | 1        | 9.09%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                    | 1        | 9.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 9.09%   |
| AMD RV710 [Radeon HD 4350/4550]                                           | 1        | 9.09%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 4        | 40%     |
| 1 x Intel      | 4        | 40%     |
| Intel + Nvidia | 1        | 10%     |
| 1 x AMD        | 1        | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 9        | 90%     |
| Unknown | 1        | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 50%     |
| 0.51-1.0   | 2        | 20%     |
| 3.01-4.0   | 1        | 10%     |
| 1.01-2.0   | 1        | 10%     |
| 0.01-0.5   | 1        | 10%     |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 33.33%  |
| Dell                | 2        | 33.33%  |
| Vizio               | 1        | 16.67%  |
| Philips             | 1        | 16.67%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                   | 1        | 16.67%  |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 16.67%  |
| Samsung Electronics LCD Monitor SAM0D4B 1360x768 609x347mm 27.6-inch | 1        | 16.67%  |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 16.67%  |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                    | 1        | 16.67%  |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                  | 1        | 16.67%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 4        | 66.67%  |
| 2560x1440 (QHD) | 1        | 16.67%  |
| 1366x768 (WXGA) | 1        | 16.67%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 2        | 33.33%  |
| 31     | 1        | 16.67%  |
| 27     | 1        | 16.67%  |
| 26     | 1        | 16.67%  |
| 25     | 1        | 16.67%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 83.33%  |
| 601-700     | 1        | 16.67%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 6        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 251-300        | 2        | 33.33%  |
| 201-250        | 2        | 33.33%  |
| 351-500        | 1        | 16.67%  |
| 301-350        | 1        | 16.67%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4        | 66.67%  |
| 1-50    | 1        | 16.67%  |
| 101-120 | 1        | 16.67%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 90%     |
| 0     | 1        | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 31.25%  |
| Intel                 | 4        | 25%     |
| TP-Link               | 3        | 18.75%  |
| Qualcomm Atheros      | 1        | 6.25%   |
| Nvidia                | 1        | 6.25%   |
| Lenovo                | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 11.11%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2        | 11.11%  |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 11.11%  |
| TP-Link Archer T4UH wireless Realtek 8812AU                       | 1        | 5.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1        | 5.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 5.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 5.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 5.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 5.56%   |
| Lenovo P2a42                                                      | 1        | 5.56%   |
| Intel I211 Gigabit Network Connection                             | 1        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 5.56%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 5.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 5.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 3        | 60%     |
| Realtek Semiconductor | 1        | 20%     |
| Qualcomm Atheros      | 1        | 20%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| TP-Link 802.11ac WLAN Adapter                                  | 2        | 40%     |
| TP-Link Archer T4UH wireless Realtek 8812AU                    | 1        | 20%     |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1        | 20%     |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 20%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 33.33%  |
| Intel                 | 4        | 33.33%  |
| Qualcomm Atheros      | 1        | 8.33%   |
| Nvidia                | 1        | 8.33%   |
| Lenovo                | 1        | 8.33%   |
| Broadcom              | 1        | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2        | 15.38%  |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 15.38%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 7.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 7.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 7.69%   |
| Nvidia MCP61 Ethernet                                             | 1        | 7.69%   |
| Lenovo P2a42                                                      | 1        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 1        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 7.69%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 7.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 7.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 66.67%  |
| WiFi     | 5        | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 8        | 80%     |
| WiFi     | 2        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 70%     |
| 4     | 1        | 10%     |
| 2     | 1        | 10%     |
| 0     | 1        | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 80%     |
| Yes  | 2        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Broadcom | 2        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Broadcom BCM20702A0 Bluetooth 4.0 | 2        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 6        | 40%     |
| Nvidia              | 4        | 26.67%  |
| AMD                 | 3        | 20%     |
| C-Media Electronics | 1        | 6.67%   |
| ASUSTek Computer    | 1        | 6.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 12.5%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 12.5%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 6.25%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 6.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 6.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 6.25%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 6.25%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 6.25%   |
| ASUSTek Computer Xonar SoundCard                                           | 1        | 6.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 6.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 6.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 6.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 23.08%  |
| SK hynix            | 2        | 15.38%  |
| Micron Technology   | 2        | 15.38%  |
| Unknown             | 1        | 7.69%   |
| Samsung Electronics | 1        | 7.69%   |
| G.Skill             | 1        | 7.69%   |
| Crucial             | 1        | 7.69%   |
| Corsair             | 1        | 7.69%   |
| A Force             | 1        | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 1GB DIMM 400MT/s                    | 1        | 7.14%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s           | 1        | 7.14%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s   | 1        | 7.14%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 7.14%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 7.14%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 1        | 7.14%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 1        | 7.14%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 1        | 7.14%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 7.14%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s   | 1        | 7.14%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s     | 1        | 7.14%   |
| Crucial RAM RM51264BA1339.16FR 4096MB DIMM 1333MT/s    | 1        | 7.14%   |
| Corsair RAM CMX4GX3M1A1600C11 4GB DIMM DDR3 1600MT/s   | 1        | 7.14%   |
| A Force RAM 1GX64V160K 8GB DIMM DDR3 1600MT/s          | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 5        | 50%     |
| DDR4    | 4        | 40%     |
| Unknown | 1        | 10%     |

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
| 4096  | 5        | 45.45%  |
| 8192  | 4        | 36.36%  |
| 16384 | 1        | 9.09%   |
| 1024  | 1        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 27.27%  |
| 1333  | 2        | 18.18%  |
| 3733  | 1        | 9.09%   |
| 3600  | 1        | 9.09%   |
| 2933  | 1        | 9.09%   |
| 2133  | 1        | 9.09%   |
| 1648  | 1        | 9.09%   |
| 400   | 1        | 9.09%   |

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
| 0     | 6        | 60%     |
| 1     | 4        | 40%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 3        | 75%     |
| Graphics card | 1        | 25%     |

