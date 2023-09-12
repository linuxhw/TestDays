Archcraft - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Archcraft.

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

Total: 21

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | 0KP561                      | [90055b146d](https://linux-hardware.org/?probe=90055b146d) | Sep 06, 2023 |
| ASUSTek  | K30BF_M32BF_A_F_K31BF_6     | [08d5b71848](https://linux-hardware.org/?probe=08d5b71848) | Jul 22, 2023 |
| Gigabyte | B650 AORUS ELITE AX         | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| Lenovo   | Win8 Pro DPK TPG            | [0efc49ca3a](https://linux-hardware.org/?probe=0efc49ca3a) | Jun 28, 2023 |
| Lenovo   | Win8 Pro DPK TPG            | [72514911c8](https://linux-hardware.org/?probe=72514911c8) | Jun 28, 2023 |
| MSI      | A320M-A PRO                 | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| ASUSTek  | P8H61-M LX R2.0             | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| ASRock   | B550M Pro4                  | [8529d01687](https://linux-hardware.org/?probe=8529d01687) | May 27, 2023 |
| ASRock   | B550M Pro4                  | [8301ca5155](https://linux-hardware.org/?probe=8301ca5155) | May 27, 2023 |
| ASUSTek  | PRIME X470-PRO              | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| ASUSTek  | H110M-E/M.2                 | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| ASUSTek  | H110M-E/M.2                 | [fb73fb5efc](https://linux-hardware.org/?probe=fb73fb5efc) | Oct 18, 2022 |
| ASUSTek  | H110M-E/M.2                 | [77fd87ca91](https://linux-hardware.org/?probe=77fd87ca91) | Oct 18, 2022 |
| Gigabyte | B550I AORUS PRO AX          | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Gigabyte | F2A68HM-DS2                 | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| Lenovo   | 3111 SDK0J40705 WIN 3425... | [543fe6b6a7](https://linux-hardware.org/?probe=543fe6b6a7) | Aug 07, 2022 |
| MSI      | MAG B550 TOMAHAWK           | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| ECS      | G31T-M                      | [3820396d91](https://linux-hardware.org/?probe=3820396d91) | Jan 29, 2022 |
| ASRock   | H97M Pro4                   | [232f2dad91](https://linux-hardware.org/?probe=232f2dad91) | Dec 15, 2021 |
| ASUSTek  | ROG DOMINUS EXTREME         | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek  | ROG DOMINUS EXTREME         | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Archcraft Rolling | 14       | 87.5%   |
| Archcraft         | 2        | 12.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Archcraft | 16       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.3.9-arch1-1         | 2        | 11.76%  |
| 5.19.13-arch1-1       | 2        | 11.76%  |
| 6.4.4-zen1-1-zen      | 1        | 5.88%   |
| 6.4.12-arch1-1        | 1        | 5.88%   |
| 6.4.1-arch2-1         | 1        | 5.88%   |
| 6.3.8-arch1-1         | 1        | 5.88%   |
| 6.3.4-arch1-1         | 1        | 5.88%   |
| 6.1.9-x64v1-xanmod1-1 | 1        | 5.88%   |
| 6.0.12-arch1-1        | 1        | 5.88%   |
| 5.19.9-arch1-1        | 1        | 5.88%   |
| 5.18.16-arch1-1       | 1        | 5.88%   |
| 5.18.0-arch1-1        | 1        | 5.88%   |
| 5.16.3-arch1-1        | 1        | 5.88%   |
| 5.15.7-zen1-1-zen     | 1        | 5.88%   |
| 5.14.10-arch1-1       | 1        | 5.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3.9   | 2        | 11.76%  |
| 5.19.13 | 2        | 11.76%  |
| 6.4.4   | 1        | 5.88%   |
| 6.4.12  | 1        | 5.88%   |
| 6.4.1   | 1        | 5.88%   |
| 6.3.8   | 1        | 5.88%   |
| 6.3.4   | 1        | 5.88%   |
| 6.1.9   | 1        | 5.88%   |
| 6.0.12  | 1        | 5.88%   |
| 5.19.9  | 1        | 5.88%   |
| 5.18.16 | 1        | 5.88%   |
| 5.18.0  | 1        | 5.88%   |
| 5.16.3  | 1        | 5.88%   |
| 5.15.7  | 1        | 5.88%   |
| 5.14.10 | 1        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3     | 4        | 23.53%  |
| 6.4     | 3        | 17.65%  |
| 5.19    | 3        | 17.65%  |
| 5.18    | 2        | 11.76%  |
| 6.1     | 1        | 5.88%   |
| 6.0     | 1        | 5.88%   |
| 5.16    | 1        | 5.88%   |
| 5.15    | 1        | 5.88%   |
| 5.14    | 1        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 16       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| openbox | 5        | 31.25%  |
| XFCE    | 4        | 25%     |
| bspwm   | 3        | 18.75%  |
| qtile   | 1        | 6.25%   |
| KDE5    | 1        | 6.25%   |
| awesome | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 14       | 87.5%   |
| Wayland | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 12       | 75%     |
| LightDM | 2        | 12.5%   |
| Unknown | 2        | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 68.75%  |
| en_GB | 2        | 12.5%   |
| pt_BR | 1        | 6.25%   |
| es_MX | 1        | 6.25%   |
| en_IN | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 10       | 62.5%   |
| BIOS | 6        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 10       | 62.5%   |
| Btrfs | 4        | 25%     |
| Xfs   | 2        | 12.5%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 13       | 81.25%  |
| Unknown | 2        | 12.5%   |
| MBR     | 1        | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 75%     |
| Yes       | 4        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8        | 50%     |
| No        | 8        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 5        | 31.25%  |
| Gigabyte Technology | 3        | 18.75%  |
| MSI                 | 2        | 12.5%   |
| Lenovo              | 2        | 12.5%   |
| ASRock              | 2        | 12.5%   |
| ECS                 | 1        | 6.25%   |
| Dell                | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C91                         | 1        | 6.25%   |
| MSI MS-7C51                         | 1        | 6.25%   |
| Lenovo ThinkCentre M710q 10MR0047US | 1        | 6.25%   |
| Lenovo ThinkCentre Edge72 3484HPU   | 1        | 6.25%   |
| Gigabyte F2A68HM-DS2                | 1        | 6.25%   |
| Gigabyte B650 AORUS ELITE AX        | 1        | 6.25%   |
| Gigabyte B550I AORUS PRO AX         | 1        | 6.25%   |
| ECS G31T-M                          | 1        | 6.25%   |
| Dell OptiPlex 330                   | 1        | 6.25%   |
| ASUS ROG DOMINUS EXTREME            | 1        | 6.25%   |
| ASUS PRIME X470-PRO                 | 1        | 6.25%   |
| ASUS P8H61-M LX R2.0                | 1        | 6.25%   |
| ASUS K30BF_M32BF_A_F_K31BF_6        | 1        | 6.25%   |
| ASUS H110M-E/M.2                    | 1        | 6.25%   |
| ASRock H97M Pro4                    | 1        | 6.25%   |
| ASRock B550M Pro4                   | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Lenovo ThinkCentre   | 2        | 12.5%   |
| MSI MS-7C91          | 1        | 6.25%   |
| MSI MS-7C51          | 1        | 6.25%   |
| Gigabyte F2A68HM-DS2 | 1        | 6.25%   |
| Gigabyte B650        | 1        | 6.25%   |
| Gigabyte B550I       | 1        | 6.25%   |
| ECS G31T-M           | 1        | 6.25%   |
| Dell OptiPlex        | 1        | 6.25%   |
| ASUS ROG             | 1        | 6.25%   |
| ASUS PRIME           | 1        | 6.25%   |
| ASUS P8H61-M         | 1        | 6.25%   |
| ASUS K30BF           | 1        | 6.25%   |
| ASUS H110M-E         | 1        | 6.25%   |
| ASRock H97M          | 1        | 6.25%   |
| ASRock B550M         | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 18.75%  |
| 2019 | 2        | 12.5%   |
| 2014 | 2        | 12.5%   |
| 2012 | 2        | 12.5%   |
| 2007 | 2        | 12.5%   |
| 2022 | 1        | 6.25%   |
| 2018 | 1        | 6.25%   |
| 2017 | 1        | 6.25%   |
| 2016 | 1        | 6.25%   |
| 2015 | 1        | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 16       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 16       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 4        | 25%     |
| 32.01-64.0  | 4        | 25%     |
| 8.01-16.0   | 3        | 18.75%  |
| 3.01-4.0    | 2        | 12.5%   |
| 2.01-3.0    | 1        | 6.25%   |
| 64.01-256.0 | 1        | 6.25%   |
| 16.01-24.0  | 1        | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 3.01-4.0  | 5        | 29.41%  |
| 4.01-8.0  | 3        | 17.65%  |
| 2.01-3.0  | 3        | 17.65%  |
| 1.01-2.0  | 3        | 17.65%  |
| 8.01-16.0 | 2        | 11.76%  |
| 0.51-1.0  | 1        | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 5        | 31.25%  |
| 2      | 4        | 25%     |
| 5      | 2        | 12.5%   |
| 4      | 2        | 12.5%   |
| 3      | 2        | 12.5%   |
| 7      | 1        | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 87.5%   |
| Yes       | 2        | 12.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8        | 50%     |
| No        | 8        | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| USA      | 5        | 31.25%  |
| UK       | 2        | 12.5%   |
| Mexico   | 2        | 12.5%   |
| Brazil   | 2        | 12.5%   |
| Slovakia | 1        | 6.25%   |
| Poland   | 1        | 6.25%   |
| India    | 1        | 6.25%   |
| Hungary  | 1        | 6.25%   |
| Czechia  | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Tábor                | 1        | 6.25%   |
| Paulista              | 1        | 6.25%   |
| Osasco                | 1        | 6.25%   |
| Milton Keynes         | 1        | 6.25%   |
| Manchester            | 1        | 6.25%   |
| Guadalajara           | 1        | 6.25%   |
| Gdansk                | 1        | 6.25%   |
| Frisco                | 1        | 6.25%   |
| Dallas                | 1        | 6.25%   |
| Ciudad Nezahualcoyotl | 1        | 6.25%   |
| Čadca                | 1        | 6.25%   |
| Budapest              | 1        | 6.25%   |
| Brookville            | 1        | 6.25%   |
| Bengaluru             | 1        | 6.25%   |
| Atlanta               | 1        | 6.25%   |
| Abilene               | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 6        | 8      | 16.67%  |
| Seagate                   | 6        | 10     | 16.67%  |
| Samsung Electronics       | 3        | 3      | 8.33%   |
| Hitachi                   | 3        | 3      | 8.33%   |
| Toshiba                   | 2        | 2      | 5.56%   |
| Sandisk                   | 2        | 2      | 5.56%   |
| Phison Electronics        | 2        | 2      | 5.56%   |
| Kingston                  | 2        | 2      | 5.56%   |
| Intel                     | 2        | 5      | 5.56%   |
| ROG                       | 1        | 1      | 2.78%   |
| Patriot                   | 1        | 1      | 2.78%   |
| Micron/Crucial Technology | 1        | 1      | 2.78%   |
| Crucial                   | 1        | 1      | 2.78%   |
| China                     | 1        | 2      | 2.78%   |
| Apacer                    | 1        | 1      | 2.78%   |
| A-DATA Technology         | 1        | 2      | 2.78%   |
| Unknown                   | 1        | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 5%      |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1        | 2.5%    |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 2.5%    |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 2.5%    |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 2.5%    |
| WDC WD20 EARX-00PASB0 2TB                           | 1        | 2.5%    |
| WDC WD10EZEX-22RKKA0 1TB                            | 1        | 2.5%    |
| WDC WD10EZEX-21M2NA0 1TB                            | 1        | 2.5%    |
| WDC WD10EARS-00MVWB0 1TB                            | 1        | 2.5%    |
| Toshiba DT01ACA200 2TB                              | 1        | 2.5%    |
| Toshiba DT01ACA100 1TB                              | 1        | 2.5%    |
| Seagate ST6000DM003-2CY186 6TB                      | 1        | 2.5%    |
| Seagate ST3500410AS 500GB                           | 1        | 2.5%    |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1        | 2.5%    |
| Seagate ST3160815AS 160GB                           | 1        | 2.5%    |
| Seagate ST31500341AS 1TB                            | 1        | 2.5%    |
| Seagate ST2000DM 008-2FR102 2TB                     | 1        | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 2.5%    |
| Seagate Expansion Desk 2TB                          | 1        | 2.5%    |
| Sandisk WD_BLACK SN770 1TB                          | 1        | 2.5%    |
| SanDisk SDSSDA240G 240GB                            | 1        | 2.5%    |
| Samsung SSD 970 EVO Plus 1TB                        | 1        | 2.5%    |
| ROG ESD-S1C 1024GB                                  | 1        | 2.5%    |
| Phison E16 PCIe4 NVMe Controller 1TB                | 1        | 2.5%    |
| Phison E12 NVMe Controller 256GB                    | 1        | 2.5%    |
| Patriot Burst 120GB SSD                             | 1        | 2.5%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 1        | 2.5%    |
| Kingston SFYRS500G 500GB                            | 1        | 2.5%    |
| Kingston SA400M8240G 240GB SSD                      | 1        | 2.5%    |
| Intel SSDSC2KW256G8 256GB                           | 1        | 2.5%    |
| Intel SSDPE21D480GA 480GB                           | 1        | 2.5%    |
| Hitachi HTS547550A9E384 500GB                       | 1        | 2.5%    |
| Hitachi HTS545050A7E380 500GB                       | 1        | 2.5%    |
| Hitachi HDS721010CLA332 1TB                         | 1        | 2.5%    |
| Crucial M4-CT064M4SSD2 64GB                         | 1        | 2.5%    |
| China SATA SSD 512GB                                | 1        | 2.5%    |
| Apacer AS350 128GB SSD                              | 1        | 2.5%    |
| A-DATA SU650 240GB SSD                              | 1        | 2.5%    |
| Unknown                                             | 1        | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 8      | 35.29%  |
| Seagate | 6        | 10     | 35.29%  |
| Hitachi | 3        | 3      | 17.65%  |
| Toshiba | 2        | 2      | 11.76%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| SanDisk           | 1        | 1      | 11.11%  |
| Patriot           | 1        | 1      | 11.11%  |
| Kingston          | 1        | 1      | 11.11%  |
| Intel             | 1        | 1      | 11.11%  |
| Crucial           | 1        | 1      | 11.11%  |
| China             | 1        | 2      | 11.11%  |
| Apacer            | 1        | 1      | 11.11%  |
| A-DATA Technology | 1        | 2      | 11.11%  |
| Unknown           | 1        | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 10       | 23     | 40%     |
| NVMe    | 7        | 12     | 28%     |
| SSD     | 7        | 11     | 28%     |
| Unknown | 1        | 1      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 31     | 59.09%  |
| NVMe | 7        | 12     | 31.82%  |
| SAS  | 2        | 4      | 9.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 11       | 19     | 57.89%  |
| 0.51-1.0   | 5        | 10     | 26.32%  |
| 1.01-2.0   | 2        | 4      | 10.53%  |
| 4.01-10.0  | 1        | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 4        | 25%     |
| 251-500        | 3        | 18.75%  |
| 101-250        | 3        | 18.75%  |
| 501-1000       | 2        | 12.5%   |
| More than 3000 | 1        | 6.25%   |
| 2001-3000      | 1        | 6.25%   |
| 51-100         | 1        | 6.25%   |
| Unknown        | 1        | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 4        | 25%     |
| 1-20           | 3        | 18.75%  |
| 251-500        | 2        | 12.5%   |
| 51-100         | 2        | 12.5%   |
| More than 3000 | 1        | 6.25%   |
| 21-50          | 1        | 6.25%   |
| 1001-2000      | 1        | 6.25%   |
| 501-1000       | 1        | 6.25%   |
| Unknown        | 1        | 6.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB  | 1        | 1      | 25%     |
| WDC WD5000AAKX-60U6AA0 500GB  | 1        | 1      | 25%     |
| WDC WD10EARS-00MVWB0 1TB      | 1        | 1      | 25%     |
| Hitachi HTS547550A9E384 500GB | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Hitachi | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Hitachi | 1        | 1      | 25%     |

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

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500410AS 500GB | 1        | 2      | 50%     |
| Seagate ST31500341AS 1TB  | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 13       | 32     | 61.9%   |
| Detected | 4        | 7      | 19.05%  |
| Malfunc  | 3        | 4      | 14.29%  |
| Failed   | 1        | 4      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 8        | 32%     |
| AMD                         | 8        | 32%     |
| Samsung Electronics         | 3        | 12%     |
| Phison Electronics          | 2        | 8%      |
| SanDisk                     | 1        | 4%      |
| Micron/Crucial Technology   | 1        | 4%      |
| Kingston Technology Company | 1        | 4%      |
| ASMedia Technology          | 1        | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 4        | 12.9%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3        | 9.68%   |
| AMD 500 Series Chipset SATA Controller                                        | 3        | 9.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 6.45%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 1        | 3.23%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 3.23%   |
| Phison E12 NVMe Controller                                                    | 1        | 3.23%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1        | 3.23%   |
| Kingston Company KC3000/Renegade NVMe SSD                                     | 1        | 3.23%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1        | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 3.23%   |
| Intel Optane SSD 900P Series                                                  | 1        | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1        | 3.23%   |
| Intel C620 Series Chipset Family IDE Redirection                              | 1        | 3.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 3.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 3.23%   |
| AMD FCH SATA Controller [IDE mode]                                            | 1        | 3.23%   |
| AMD FCH SATA Controller D                                                     | 1        | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 15       | 57.69%  |
| NVMe | 7        | 26.92%  |
| IDE  | 3        | 11.54%  |
| RAID | 1        | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 50%     |
| AMD    | 8        | 50%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 2        | 12.5%   |
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1        | 6.25%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 6.25%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 6.25%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 6.25%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1        | 6.25%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 6.25%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz           | 1        | 6.25%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 6.25%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 6.25%   |
| AMD Ryzen 7 7700X 8-Core Processor             | 1        | 6.25%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 6.25%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 6.25%   |
| AMD Ryzen 5 4600G with Radeon Graphics         | 1        | 6.25%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 3        | 18.75%  |
| AMD Ryzen 5      | 3        | 18.75%  |
| Intel Core 2 Duo | 2        | 12.5%   |
| AMD Ryzen 7      | 2        | 12.5%   |
| AMD A10          | 2        | 12.5%   |
| Intel Xeon       | 1        | 6.25%   |
| Intel Core i7    | 1        | 6.25%   |
| Intel Core i3    | 1        | 6.25%   |
| AMD Ryzen 9      | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 31.25%  |
| 4      | 4        | 25%     |
| 6      | 3        | 18.75%  |
| 8      | 2        | 12.5%   |
| 28     | 1        | 6.25%   |
| 12     | 1        | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 68.75%  |
| 1      | 5        | 31.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 16       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 37.5%   |
| 0x906e9    | 1        | 6.25%   |
| 0x6fd      | 1        | 6.25%   |
| 0x506e3    | 1        | 6.25%   |
| 0x50654    | 1        | 6.25%   |
| 0x306c3    | 1        | 6.25%   |
| 0x0a601203 | 1        | 6.25%   |
| 0x0a201016 | 1        | 6.25%   |
| 0x0a201009 | 1        | 6.25%   |
| 0x08701021 | 1        | 6.25%   |
| 0x06003106 | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 2        | 12.5%   |
| Zen 2       | 2        | 12.5%   |
| Steamroller | 2        | 12.5%   |
| Skylake     | 2        | 12.5%   |
| Core        | 2        | 12.5%   |
| Zen+        | 1        | 6.25%   |
| SandyBridge | 1        | 6.25%   |
| KabyLake    | 1        | 6.25%   |
| IvyBridge   | 1        | 6.25%   |
| Haswell     | 1        | 6.25%   |
| Unknown     | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 8        | 44.44%  |
| Nvidia | 6        | 33.33%  |
| Intel  | 4        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]               | 3        | 14.29%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                    | 2        | 9.52%   |
| AMD Kaveri [Radeon R7 Graphics]                                       | 2        | 9.52%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                 | 1        | 4.76%   |
| Nvidia TU102 [TITAN RTX]                                              | 1        | 4.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                   | 1        | 4.76%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                        | 1        | 4.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller      | 1        | 4.76%   |
| Intel HD Graphics 630                                                 | 1        | 4.76%   |
| Intel HD Graphics 530                                                 | 1        | 4.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                | 1        | 4.76%   |
| AMD RV710 [Radeon HD 4350/4550]                                       | 1        | 4.76%   |
| AMD Renoir                                                            | 1        | 4.76%   |
| AMD Raphael                                                           | 1        | 4.76%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]            | 1        | 4.76%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM] | 1        | 4.76%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                              | 1        | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 4        | 25%     |
| 1 x AMD        | 4        | 25%     |
| 2 x AMD        | 3        | 18.75%  |
| 1 x Intel      | 2        | 12.5%   |
| 2 x Intel      | 1        | 6.25%   |
| Intel + Nvidia | 1        | 6.25%   |
| AMD + Nvidia   | 1        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 70.59%  |
| Proprietary | 5        | 29.41%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 35.29%  |
| 7.01-8.0   | 3        | 17.65%  |
| 16.01-24.0 | 2        | 11.76%  |
| 0.51-1.0   | 2        | 11.76%  |
| 5.01-6.0   | 1        | 5.88%   |
| 3.01-4.0   | 1        | 5.88%   |
| 1.01-2.0   | 1        | 5.88%   |
| 8.01-16.0  | 1        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 4        | 20%     |
| Goldstar             | 3        | 15%     |
| Ancor Communications | 3        | 15%     |
| Samsung Electronics  | 2        | 10%     |
| Toshiba              | 1        | 5%      |
| Lenovo               | 1        | 5%      |
| Hewlett-Packard      | 1        | 5%      |
| BenQ                 | 1        | 5%      |
| ASUSTek Computer     | 1        | 5%      |
| AGO                  | 1        | 5%      |
| Acer                 | 1        | 5%      |
| Unknown              | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Toshiba TV TSB0206 1920x1080                                          | 1        | 4.55%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 4.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 4.55%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                  | 1        | 4.55%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch            | 1        | 4.55%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                  | 1        | 4.55%   |
| Goldstar HDR WFHD GSM5BB9 2560x1080 798x334mm 34.1-inch               | 1        | 4.55%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch                | 1        | 4.55%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 1        | 4.55%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                   | 1        | 4.55%   |
| Dell S2421NX DEL41FB 1920x1080 527x296mm 23.8-inch                    | 1        | 4.55%   |
| Dell S2240T DELA094 1920x1080 477x268mm 21.5-inch                     | 1        | 4.55%   |
| Dell E198WFP DELF005 1440x900 408x255mm 18.9-inch                     | 1        | 4.55%   |
| BenQ BL3200 BNQ8017 2560x1440 708x398mm 32.0-inch                     | 1        | 4.55%   |
| ASUSTek Computer ROG PG65UQ AUS65A1 3840x2160 1430x800mm 64.5-inch    | 1        | 4.55%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 4.55%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 4.55%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 1        | 4.55%   |
| AGO LCD Monitor AGO0001 1920x1080 300x230mm 14.9-inch                 | 1        | 4.55%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                 | 1        | 4.55%   |
| Acer XF251Q ACR0624 1920x1080 544x303mm 24.5-inch                     | 1        | 4.55%   |
| Unknown                                                               | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 8        | 42.11%  |
| 2560x1440 (QHD)  | 3        | 15.79%  |
| 3840x2160 (4K)   | 1        | 5.26%   |
| 3840x1080        | 1        | 5.26%   |
| 3440x1440        | 1        | 5.26%   |
| 3200x1080        | 1        | 5.26%   |
| 2560x1080        | 1        | 5.26%   |
| 1440x900 (WXGA+) | 1        | 5.26%   |
| 1280x1024 (SXGA) | 1        | 5.26%   |
| Unknown          | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 3        | 14.29%  |
| 21      | 3        | 14.29%  |
| 34      | 2        | 9.52%   |
| 23      | 2        | 9.52%   |
| 74      | 1        | 4.76%   |
| 64      | 1        | 4.76%   |
| 48      | 1        | 4.76%   |
| 32      | 1        | 4.76%   |
| 31      | 1        | 4.76%   |
| 27      | 1        | 4.76%   |
| 19      | 1        | 4.76%   |
| 17      | 1        | 4.76%   |
| 14      | 1        | 4.76%   |
| 12      | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 30%     |
| 401-500     | 4        | 20%     |
| 701-800     | 3        | 15%     |
| 1001-1500   | 2        | 10%     |
| 601-700     | 1        | 5%      |
| 301-350     | 1        | 5%      |
| 201-300     | 1        | 5%      |
| 1501-2000   | 1        | 5%      |
| Unknown     | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 55.56%  |
| 21/9    | 2        | 11.11%  |
| 16/10   | 2        | 11.11%  |
| 5/4     | 1        | 5.56%   |
| 4/3     | 1        | 5.56%   |
| 32/9    | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 28.57%  |
| 351-500        | 4        | 19.05%  |
| More than 1000 | 2        | 9.52%   |
| 151-200        | 2        | 9.52%   |
| 71-80          | 1        | 4.76%   |
| 301-350        | 1        | 4.76%   |
| 251-300        | 1        | 4.76%   |
| 141-150        | 1        | 4.76%   |
| 101-110        | 1        | 4.76%   |
| 501-1000       | 1        | 4.76%   |
| Unknown        | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 55%     |
| 101-120 | 4        | 20%     |
| 121-160 | 2        | 10%     |
| 1-50    | 1        | 5%      |
| 161-240 | 1        | 5%      |
| Unknown | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 62.5%   |
| 2     | 5        | 31.25%  |
| 3     | 1        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 57.14%  |
| Intel                 | 5        | 23.81%  |
| Ralink Technology     | 1        | 4.76%   |
| MediaTek              | 1        | 4.76%   |
| Broadcom Limited      | 1        | 4.76%   |
| Aquantia              | 1        | 4.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 27.59%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 10.34%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 6.9%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 3.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 3.45%   |
| Realtek 802.11ac NIC                                              | 1        | 3.45%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 3.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 3.45%   |
| Intel Wireless-AC 9260                                            | 1        | 3.45%   |
| Intel Wireless 8265 / 8275                                        | 1        | 3.45%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.45%   |
| Intel Ethernet Connection (3) I219-LM                             | 1        | 3.45%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.45%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.45%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 3.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 37.5%   |
| Intel                 | 3        | 37.5%   |
| Ralink Technology     | 1        | 12.5%   |
| MediaTek              | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2        | 22.22%  |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1        | 11.11%  |
| Realtek 802.11ac NIC                                          | 1        | 11.11%  |
| Ralink MT7601U Wireless Adapter                               | 1        | 11.11%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 11.11%  |
| Intel Wireless-AC 9260                                        | 1        | 11.11%  |
| Intel Wireless 8265 / 8275                                    | 1        | 11.11%  |
| Intel Wi-Fi 6 AX200                                           | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 64.71%  |
| Intel                 | 4        | 23.53%  |
| Broadcom Limited      | 1        | 5.88%   |
| Aquantia              | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 40%     |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 15%     |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 5%      |
| Intel I211 Gigabit Network Connection                             | 1        | 5%      |
| Intel Ethernet Connection (3) I219-LM                             | 1        | 5%      |
| Intel Ethernet Connection (2) I219-V                              | 1        | 5%      |
| Intel Ethernet Connection (2) I218-V                              | 1        | 5%      |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 5%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 66.67%  |
| WiFi     | 8        | 33.33%  |

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
| 1     | 8        | 50%     |
| 2     | 7        | 43.75%  |
| 3     | 1        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11       | 68.75%  |
| Yes  | 5        | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 50%     |
| MediaTek                | 1        | 16.67%  |
| IMC Networks            | 1        | 16.67%  |
| Cambridge Silicon Radio | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                            | 1        | 16.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 16.67%  |
| Intel Bluetooth wireless interface                  | 1        | 16.67%  |
| Intel AX200 Bluetooth                               | 1        | 16.67%  |
| IMC Networks Bluetooth Radio                        | 1        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 11       | 32.35%  |
| Intel               | 8        | 23.53%  |
| Nvidia              | 6        | 17.65%  |
| Logitech            | 3        | 8.82%   |
| C-Media Electronics | 2        | 5.88%   |
| Texas Instruments   | 1        | 2.94%   |
| Oculus VR           | 1        | 2.94%   |
| Kingston Technology | 1        | 2.94%   |
| JMTek               | 1        | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 7.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 7.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 4.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 4.76%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 4.76%   |
| AMD FCH Azalia Controller                                                  | 2        | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 4.76%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 2.38%   |
| Oculus VR Rift CV1 Audio                                                   | 1        | 2.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.38%   |
| Logitech Logitech USB Microphone                                           | 1        | 2.38%   |
| Logitech H390 headset with microphone                                      | 1        | 2.38%   |
| Logitech G432 Gaming Headset                                               | 1        | 2.38%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 2.38%   |
| JMTek USB PnP Audio Device                                                 | 1        | 2.38%   |
| Intel Lewisburg MROM 0                                                     | 1        | 2.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 2.38%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 2.38%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 2.38%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.38%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1        | 2.38%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 1        | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 18.75%  |
| Unknown             | 2        | 12.5%   |
| Crucial             | 2        | 12.5%   |
| Corsair             | 2        | 12.5%   |
| A-DATA Technology   | 2        | 12.5%   |
| Team                | 1        | 6.25%   |
| SK hynix            | 1        | 6.25%   |
| Samsung Electronics | 1        | 6.25%   |
| Micron Technology   | 1        | 6.25%   |
| G.Skill             | 1        | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s             | 1        | 5.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 5.56%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 1        | 5.56%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s    | 1        | 5.56%   |
| SK hynix RAM HYMP512U64CP8-S6 1GB DIMM DDR2 800MT/s   | 1        | 5.56%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s | 1        | 5.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s | 1        | 5.56%   |
| Micron RAM F6451U64F9333G 4GB DIMM DDR3 1333MT/s      | 1        | 5.56%   |
| Kingston RAM KF552C40-8 8GB DIMM DDR5 4800MT/s        | 1        | 5.56%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s | 1        | 5.56%   |
| Kingston RAM 9905402-532.A00LF 4GB DIMM DDR3 1600MT/s | 1        | 5.56%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3200MT/s   | 1        | 5.56%   |
| Crucial RAM CT51264BA1339.M16F 4GB DIMM DDR3 1333MT/s | 1        | 5.56%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s | 1        | 5.56%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s | 1        | 5.56%   |
| Corsair RAM CMT16GX4M2K4266C19 8GB DIMM DDR4 2133MT/s | 1        | 5.56%   |
| A-DATA RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 5.56%   |
| A-DATA RAM DDR4 3600 2OZ 8GB DIMM DDR4 2667MT/s       | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 7        | 50%     |
| DDR3  | 4        | 28.57%  |
| SDRAM | 1        | 7.14%   |
| DDR5  | 1        | 7.14%   |
| DDR2  | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 92.86%  |
| SODIMM | 1        | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 50%     |
| 4096  | 2        | 12.5%   |
| 2048  | 2        | 12.5%   |
| 1024  | 2        | 12.5%   |
| 32768 | 1        | 6.25%   |
| 16384 | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 18.75%  |
| 2667    | 2        | 12.5%   |
| 2133    | 2        | 12.5%   |
| 49926   | 1        | 6.25%   |
| 4800    | 1        | 6.25%   |
| 3800    | 1        | 6.25%   |
| 3733    | 1        | 6.25%   |
| 3600    | 1        | 6.25%   |
| 3200    | 1        | 6.25%   |
| 1333    | 1        | 6.25%   |
| 800     | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP DeskJet 4720 series | 1        | 100%    |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 1        | 50%     |
| Generalplus Technology | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech HD Pro Webcam C920 | 1        | 50%     |
| Generalplus WEB CAM         | 1        | 50%     |

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
| 0     | 13       | 81.25%  |
| 1     | 2        | 12.5%   |
| 2     | 1        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 2        | 66.67%  |
| Unassigned class | 1        | 33.33%  |

